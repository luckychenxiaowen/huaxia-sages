# 华夏圣贤 Skill

把华夏传统思想里的人物思维框架，蒸馏成 Agent 可直接加载的分析脚手架——用来在决策时强制换一个角度看问题，而不是查史料。

本仓收 **5 个视角 Skill**：鬼谷子、黄石公、姜太公（先秦）、白云先生（当代）、倪海厦（近现代）。每个目录独立可用，复制进你的 Agent 的 `skills/` 目录即可；无依赖、无运行时、不需要 API Key。

> **关于命名（如实说明）**：仓库 slug 为 `huaxia-sages`，显示名沿用「华夏圣贤 Skill」。严格按中文语义，「圣贤」多指先秦儒家道统；本仓有 2 位是后世思想实践者，属宽泛用法。若你介意名实不符，可把显示名读作「华夏思想人物视角集」——目录名与 slug 不变。这是风格判断，不影响使用。

## 这个仓解决哪一类问题

当你要做一个决策、却只在同一套现代商业框架里打转时，用一套结构化的传统思维框架强制换视角。5 个 Skill 共用同一套章节骨架：**心智模型 → 决策启发式 → 表达 DNA → 价值反模式 → 诚实边界 → 蒸馏来源**。可单独用，也可并列对照。

## 5 个视角怎么选

| Skill | 人物 / 时期 | 最擅长的问题 | 心智模型数 |
|---|---|---|---|
| [guiguzi-perspective](skills/guiguzi-perspective) | 鬼谷子 · 先秦纵横家 | 谈判、博弈、说服、组织中的信息差 | 6 |
| [huangshigong-perspective](skills/huangshigong-perspective) | 黄石公 · 秦汉 | 进退取舍、功成身退、位与时的匹配 | 5 |
| [taigong-perspective](skills/taigong-perspective) | 姜太公（吕尚）· 西周 | 战略布局、识人用人、竞争态势 | 5 |
| [baiyun-perspective](skills/baiyun-perspective) | 白云先生 · 当代 | 周期位置、方向（道）与方法（器）的分层 | 5 |
| [nihaixia-perspective](skills/nihaixia-perspective) | 倪海厦 · 近现代 | 本源追溯、整体系统、天时窗口；**含医疗免责** | 5 |

## 用法

1. 进 `skills/<name>/`，读 `SKILL.md` 的 frontmatter（触发词写在 `description` / `triggers` 里）
2. 把整个目录复制到你的 Agent 的 `skills/` 目录
3. 对话里说「用 X 视角看这件事」即可

不需要额外安装依赖，也没有配置文件。

## 边界（请务必读 [ATTRIBUTION.md](ATTRIBUTION.md)）

- 这些是**结构化整理与蒸馏**，不是原典权威解读、不是史料考据，也不代表相关人物或其传承方的观点。
- 其中 1 位为当代在世作者、1 位为近现代中医师；本仓与相关人物、出版方、传承机构**均无授权或隶属关系**。
- **不构成医疗、法律、投资、职业建议**。`nihaixia-perspective` 内有明确医疗免责声明。
- 框架是工具，判断是你的。

## 声明

个人业余项目，与雇主无关，不含公司内部数据、业务代码或内部文件。

## 许可

[MIT](LICENSE)。Copyright (c) 2026 luckychenxiaowen。观点归属与第三方边界见 [ATTRIBUTION.md](ATTRIBUTION.md)。

## 发布前

`python scripts/check-before-push.py` 必须全项 PASS；新增 Skill 的规范见 [CONTRIBUTING.md](CONTRIBUTING.md)。
