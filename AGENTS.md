# 仓库维护约定

编写规则见 `spec/agent-skills-spec.md`，协作流程见 `README.md`。

- 每个 Skill 放在 `skills/<name>/SKILL.md`，目录与 frontmatter 的 `name` 一致。
- 配套资料放在对应技能目录内，使用相对路径引用。
- 修改技能行为后，用真实请求检查触发范围和结果，并在提交中说明。
- 保持仓库精简；仅维护技能、模板和规范，采用工具无关的格式。
