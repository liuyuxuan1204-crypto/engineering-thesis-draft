# 工科本科论文初稿 Skill

这是一个用于协助工科本科生从选题、开题、文献与工程材料核验，推进到实验或仿真、逐章写作及初稿核查的 Codex Skill。它提供流程与验收关口，不附带任何人的论文、学校模板、仿真模型或数据，也不替代导师审批和学校终稿审核。

## 安装

将整个 `engineering-thesis-draft` 文件夹放入个人技能目录 `~/.agents/skills/`；只在某个项目中使用时，放入该项目的 `.agents/skills/`。保持 `SKILL.md` 与 `references/workflow.md` 的相对位置不变。若 Codex 没有识别到新 Skill，可重启 Codex。

## 使用

在 Codex 中明确指定 `$engineering-thesis-draft`，例如：

> $engineering-thesis-draft 请先阅读我学校的毕业论文要求和已有研究材料，帮我检查选题是否可行。本轮先不要撰写正文。

也可以在任务与 Skill 描述匹配时由 Codex 自动选用。使用者应提供自己的当届学校要求、专业方向、真实文献、工程或实验资料；Skill 不预设文献篇数、论文字数、软件、章节结构或结果。

## 内容

- [`SKILL.md`](SKILL.md)：目标、原则和阶段关口。
- [`references/workflow.md`](references/workflow.md)：从选题到初稿的分步流程、产物与核验办法。

本仓库目前未附开源许可证。公开可见不等于授予复制、修改或再发布许可；仓库所有者可以在决定授权方式后补充许可证。
