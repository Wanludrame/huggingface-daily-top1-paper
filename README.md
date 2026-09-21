# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-09-22 | [IntBMoE: Integrating Block-Level Conditioning into Expert Composition for Full-Participation Mixture-of-Experts](papers/2026-09-22.md) |
| 2026-09-18 | [LimiX-2: A Contextual Mechanism Network Towards General Structured-Data Intelligence](papers/2026-09-18.md) |
| 2026-09-17 | [HarnessVLN: Unifying Training-Free Embodied Navigation through an Agent Harness](papers/2026-09-17.md) |
| 2026-09-16 | [LynnReal-Omni: Native multi-modal Video Generation for Agentic Visual Workflows](papers/2026-09-16.md) |
| 2026-09-15 | [DataFlex-RL: An Evaluation Platform for RLVR Data Policies](papers/2026-09-15.md) |
| 2026-09-14 | [Memory as Plans: World-Action Modeling with Memory-Grounded Planning](papers/2026-09-14.md) |
| 2026-09-13 | [Memory as Plans: World-Action Modeling with Memory-Grounded Planning](papers/2026-09-13.md) |
| 2026-09-12 | [Memory as Plans: World-Action Modeling with Memory-Grounded Planning](papers/2026-09-12.md) |
| 2026-09-10 | [What Did I Just Say? Self-Listening for Full-Duplex Speech Models](papers/2026-09-10.md) |
| 2026-09-09 | [Unlocking Lossless Speedups in LLMs via Discrete Diffusion](papers/2026-09-09.md) |

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
