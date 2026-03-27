# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-03-27 | [EVA: Efficient Reinforcement Learning for End-to-End Video Agent](papers/2026-03-27.md) |
| 2026-03-26 | [RealMaster: Lifting Rendered Scenes into Photorealistic Video](papers/2026-03-26.md) |
| 2026-03-25 | [Look Where It Matters: High-Resolution Crops Retrieval for Efficient VLMs](papers/2026-03-25.md) |
| 2026-03-24 | [Reasoning as Compression: Unifying Budget Forcing via the Conditional Information Bottleneck](papers/2026-03-24.md) |
| 2026-03-23 | [Reasoning as Compression: Unifying Budget Forcing via the Conditional Information Bottleneck](papers/2026-03-23.md) |
| 2026-03-19 | [MosaicMem: Hybrid Spatial Memory for Controllable Video World Models](papers/2026-03-19.md) |

## All Papers / 完整目录

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-03-27 | [EVA: Efficient Reinforcement Learning for End-to-End Video Agent](papers/2026-03-27.md) |
| 2026-03-26 | [RealMaster: Lifting Rendered Scenes into Photorealistic Video](papers/2026-03-26.md) |
| 2026-03-25 | [Look Where It Matters: High-Resolution Crops Retrieval for Efficient VLMs](papers/2026-03-25.md) |
| 2026-03-24 | [Reasoning as Compression: Unifying Budget Forcing via the Conditional Information Bottleneck](papers/2026-03-24.md) |
| 2026-03-23 | [Reasoning as Compression: Unifying Budget Forcing via the Conditional Information Bottleneck](papers/2026-03-23.md) |
| 2026-03-19 | [MosaicMem: Hybrid Spatial Memory for Controllable Video World Models](papers/2026-03-19.md) |

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
