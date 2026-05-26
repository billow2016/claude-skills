# Claude Code Skills

我的 Claude Code 自定义技能包。

## 技能列表

| 名称 | 说明 | 用法 |
|------|------|------|
| [9.5-perspective](9.5-perspective/SKILL.md) | 全球前0.001%人群的完整画像与思维操作系统 | `/9.5` / `用9.5的视角看...` |
| [score](score.md) | W.I.A.T.L. 体系评估人物综合评分与跃迁规划 | `/score <人物描述>` |
| [huashu-nuwa](huashu-nuwa/SKILL.md) | 女娲造人：输入人名/主题，自动蒸馏成可运行的人物Skill | `造skill` / `蒸馏XX` / `女娲` |
| [dbc-matrix](dbc-matrix.md) | 将 DBC 文件解析为 CAN 信号矩阵表 CSV | `/dbc-matrix <file.dbc>` |

## 安装

```bash
# 克隆到用户级 skills 目录
git clone https://github.com/billow2016/claude-skills.git ~/.claude/skills/billow2016
```

或者复制单个 skill 到你的项目：

```bash
cp ~/.claude/skills/billow2016/dbc-matrix.md .claude/skills/
```
