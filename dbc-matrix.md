---
name: dbc-matrix
description: 将DBC文件解析为CAN信号矩阵表CSV，包含所有报文和信号的详细信息
---

当用户要求将 DBC 文件转换为矩阵表/CSV 时，执行以下步骤：

1. 找到用户指定的 `.dbc` 文件路径
2. 运行脚本生成 CSV：
   ```
   python3 ~/scripts/dbc_to_matrix.py <input.dbc> [output.csv]
   ```
3. 如果用户未指定输出路径，脚本会在 DBC 同目录生成 `原文件名_矩阵表.csv`
4. 告诉用户生成完成，告知输出文件路径

输出 CSV 包含列：序号, 报文ID(Hex), 报文ID(Dec), 报文名称, 发送节点, 周期(ms), 长度(Byte), 信号名称, 起始位(bit), 长度(bit), 字节序, 符号, 因子, 偏移, 范围, 单位, 接收节点
