# Team Skills

增量团队共享的 Skill 仓库，用 Git 管理技能说明和配套资料。

## 目录

```text
skills/                    技能目录，每个技能一个子目录
template/SKILL.md          手工复制的技能模板
spec/agent-skills-spec.md  格式与编写规范
AGENTS.md                  仓库维护约定
```

## 新增与维护

1. 在功能分支中，将 `template/SKILL.md` 复制到 `skills/<skill-name>/SKILL.md`。
2. 按[编写规范](spec/agent-skills-spec.md)填写名称、触发描述和正文，删除占位内容。
3. 用真实请求验证执行结果，并检查一个容易混淆但不应触发的请求。
4. 提交评审，说明用途、变更及验证结果，评审通过后合并。

版本由 Git 提交和标签管理。删除或改名已使用的技能时，说明替代方案与迁移方式。引入第三方资料时，在对应技能目录保留来源和许可说明。
