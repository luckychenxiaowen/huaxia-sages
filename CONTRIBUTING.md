# 新增 Skill 规范

1. **先过问题域**：只收人物视角/思想框架的结构化蒸馏。别的类型请另立主题仓。
2. **目录结构**：`skills/<name>/SKILL.md` + `README.md`。`SKILL.md` 必须含 frontmatter（`name` / `description`）与六段骨架：心智模型、决策启发式、表达 DNA、价值反模式、诚实边界、蒸馏来源。
3. **README 不许写「(见 SKILL.md)」**：必须写清「这个视角解决什么问题 / 模型速览 / 触发词 / 与仓内其他视角怎么选 / 边界」。
4. **归属与免责**：在 `ATTRIBUTION.md` 补对应条目。涉及在世作者、医疗健康、法律投资等话题的，必须在该 Skill 的 `SKILL.md` 内也写明声明。
5. **更新白名单**：改 `scripts/check-before-push.py` 的 `ALLOWED_SKILLS`，并同步 `README.md` 的清单表与 `CHANGELOG.md`。
6. **跑检查**：`python scripts/check-before-push.py` 全项 PASS 才能提交。

不接收：第三方代码的直接拷贝（除非附上原许可证与署名）、任何凭据或真实配置、雇主相关语境、需要联网或付费 API 才能跑的运行时依赖。
