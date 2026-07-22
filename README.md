# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-07-23 | [Text Template Tokens Are Implicit Semantic Registers in Diffusion Transformers](papers/2026-07-23.md) |
| 2026-07-22 | [Open-AoE: An Open Egocentric Manipulation Dataset and Toolchain for Embodied Learning](papers/2026-07-22.md) |
| 2026-07-21 | [RESOURCE2SKILL: Distilling Executable Agent Skills from Human-Created Multimodal Resources](papers/2026-07-21.md) |
| 2026-07-20 | [LongStraw: Long-Context RL Beyond 2M Tokens under a Fixed GPU Budget](papers/2026-07-20.md) |
| 2026-07-19 | [LongStraw: Long-Context RL Beyond 2M Tokens under a Fixed GPU Budget](papers/2026-07-19.md) |
| 2026-07-18 | [LongStraw: Long-Context RL Beyond 2M Tokens under a Fixed GPU Budget](papers/2026-07-18.md) |
| 2026-07-17 | [Registers Matter for Pixel-Space Diffusion Transformers](papers/2026-07-17.md) |
| 2026-07-15 | [4D Human-Scene Reconstruction from Low-Overlap Captures](papers/2026-07-15.md) |
| 2026-07-14 | [Long-Horizon-Terminal-Bench: Testing the Limits of Agents on Long-Horizon Terminal Tasks with Dense Reward-Based Grading](papers/2026-07-14.md) |
| 2026-07-13 | [Why Can't I Open My Drawer? Mitigating Object-Driven Shortcuts in Zero-Shot Compositional Action Recognition](papers/2026-07-13.md) |

[All Papers / 完整目录 →](CATALOG.md)

---

## How it works / 工作原理

1. Fetch the #1 most upvoted paper from HuggingFace Daily Papers API / 从 HuggingFace API 抓取当日最热论文
2. Retrieve abstract from arXiv / 从 arXiv 获取摘要
3. Generate structured Chinese analysis via Claude API / 通过 Claude API 生成中文结构化解读
4. Auto-commit and push / 自动提交并推送

Each paper analysis includes / 每篇解读包含：
- Core contributions & innovations / 核心贡献与创新点
- Technical method analysis / 技术方法分析
- Potential impact & applications / 潜在影响与应用场景
- Recommendation rationale / 推荐理由
