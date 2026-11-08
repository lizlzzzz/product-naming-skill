---
name: product-naming
description: Generate, refine, and compare Chinese, English, or bilingual names for internet products, apps, SaaS, AI tools, and developer platforms. Use for product naming, renaming, brand-family naming, candidate shortlists, and preliminary name-collision checks. 为互联网产品、App、AI 工具和平台起名、改名、筛选候选名或初步查重时使用。
---

# 产品命名 / Product Naming

## 1. 还原产品约束

提炼目标用户、他们正在做的事、产品给出的结果、差异化、市场与输出语言、品牌层级和硬性限制。把产品类别、命名机制、感知风格分开。市场或语言缺失时，参考上下文并标注假设。只有答案会改变生成方向时才追问，最多两个问题。

## 2. 选择有区分度的方向

阅读 [分类与构词](references/taxonomy.md)。选 3–4 种互补机制，包含一个探索方向。从对应语言的样本库选 4–8 条参考，覆盖至少两种构词和两家公司（明确指定单一品牌时除外）。

- 中文：[中文样本库](references/naming-library-zh.csv)。
- 英文：[英文样本库](references/naming-library-en.csv)。
- 双语：读取两份样本库与[双语命名](references/bilingual-naming.md)，先确定品牌关系与两地都要传递的价值，再分别构词和配对。

迁移构词操作，例如把用户动作和产物压缩成短词。排除参考品牌原名、近似名及易被理解为对方子品牌的变体。把来源能证明的事实与对名字的解读区分开。

## 3. 发散、筛选、解释

默认工作池为 30 个草案。单语在易懂、有辨识度、探索三个方向各起约 10 个。双语先各生成约 15 个，再从其中配对。按用户要求缩放。先筛掉近重复、明显同业撞名、严重负面联想、歧义和功能误导，再按[评分与查重](references/evaluation-rubric.md)排序。分数只辅助排序。

默认交付 5 个名称或 5 组配对，质量合格者不足时可少给并说明。每项给出构词、用户可能听出的意思、一项具体取舍和查重状态。英文拼写或读法存在歧义时标记读法，双语候选补充配对依据。说明首选理由和一个具体反对理由。完整草案池只在用户需要时展示。

## 4. 核查

用户要求查重或表明准备上线时，对候选逐一按指定市场核查，分开记录同业产品、商标初筛、应用商店和域名。查不到、没查、发现相似项分别记录。未经核查的候选统一标为“未查重”。按用户的沟通语言写解释，保留候选名称的原始拼写。
