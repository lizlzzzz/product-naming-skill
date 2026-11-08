# 产品命名 · Product Naming Skill

为互联网产品、App、SaaS 和 AI 工具起名。输入产品、用户和市场，得到一组中文名、英文名或双语配对，以及构词理由、取舍和初步查重状态。

从豆包、剪映、飞书等中文案例出发，对照 TikTok、CapCut、Claude、Cursor、Notion 等英文案例，归纳可复用的构词方式。样本是研究素材，品牌归属与词义解读分别记录。

## 使用

将 [skills/product-naming](skills/product-naming) 整个目录复制到客户端的 Skills 目录。Codex 项目内可放到 `.agents/skills/product-naming/`。也可直接让支持 Agent Skills 的助手读取 [SKILL.md](skills/product-naming/SKILL.md) 并按步骤执行。

> 使用 $product-naming 给一款把采访视频变成可检索金句库的 App 起名。面向中美创作者团队，风格轻松但可信，给我 5 组中英文名字。

默认交付 5 个候选或 5 组配对。用户准备上线时，可进一步按市场核查同业、应用商店、域名和商标。

## 样本与规则

- [中文样本库](skills/product-naming/references/naming-library-zh.csv) · 37 个
- [英文样本库](skills/product-naming/references/naming-library-en.csv) · 38 个
- [分类与构词](skills/product-naming/references/taxonomy.md)
- [双语命名](skills/product-naming/references/bilingual-naming.md)
- [评分与初步查重](skills/product-naming/references/evaluation-rubric.md)

## English

An Agent Skill for naming apps, SaaS products, AI tools, and developer platforms. It supports Chinese, English, and bilingual naming and includes a 75-name reference set with source links and editorial analysis. Copy the skill folder into your client’s Skills directory, then ask for a shortlist with your product, audience, market, and tone.

## License

[MIT](LICENSE) covers the original skill instructions and editorial analysis. Referenced product names and marks belong to their respective owners.
