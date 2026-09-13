# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-09-14 | [Memory as Plans: World-Action Modeling with Memory-Grounded Planning](papers/2026-09-14.md) |
| 2026-09-13 | [Memory as Plans: World-Action Modeling with Memory-Grounded Planning](papers/2026-09-13.md) |
| 2026-09-12 | [Memory as Plans: World-Action Modeling with Memory-Grounded Planning](papers/2026-09-12.md) |
| 2026-09-10 | [What Did I Just Say? Self-Listening for Full-Duplex Speech Models](papers/2026-09-10.md) |
| 2026-09-09 | [Unlocking Lossless Speedups in LLMs via Discrete Diffusion](papers/2026-09-09.md) |
| 2026-09-08 | [Bilevel Coordinated Reflection: A Game-Theoretic Approach to Multi-Agent LLM Systems](papers/2026-09-08.md) |
| 2026-09-07 | [RoboTok: An Internet-Scale Data Engine for Human Demonstration Retrieval and Dexterous Manipulation Learning](papers/2026-09-07.md) |
| 2026-09-06 | [RoboTok: An Internet-Scale Data Engine for Human Demonstration Retrieval and Dexterous Manipulation Learning](papers/2026-09-06.md) |
| 2026-09-05 | [Compile by Training: Turning Natural-Language Specifications into Local Neural Functions](papers/2026-09-05.md) |
| 2026-09-04 | [NeoMME: A Single-Tower Multimodal-Native Multilingual Foundation Encoder for Efficient Fine-Tuning and Inference](papers/2026-09-04.md) |

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
