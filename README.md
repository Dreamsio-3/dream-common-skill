# dream-common-skill

梦璃若的通用 skill 合集。

## Skill 列表

| Skill | 说明 |
| --- | --- |
| [dream-common-workflow-skill](dream-common-workflow-skill/SKILL.md) | 通用前后端开发流程规范，适用于任意语言和框架。覆盖数据库变更、后端、前端、联调、调试排查、回滚、提交推送与 Merge Request。 |

## 目录结构

```
dream-common-workflow-skill/
├── SKILL.md                    # 主流程：开发阶段、回滚、工作风格、通用约束
└── references/
    ├── database.md             # 数据库变更安全规范
    ├── debugging.md            # 调试与部署排查
    └── git-commit-push.md      # 提交、推送与 Merge Request
```

## 使用方式

将 skill 目录复制到 Claude Code 的 skills 目录下即可：

- 全局使用：`~/.claude/skills/dream-common-workflow-skill/`
- 单个项目使用：`<项目根目录>/.claude/skills/dream-common-workflow-skill/`

## 维护

流程规范的唯一来源是各 skill 目录下的 `SKILL.md` 和 `references/`。修改规范时只改这些文件；新增 skill 时在上方表格补一行。
