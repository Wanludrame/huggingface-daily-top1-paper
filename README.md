# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-04-09 | [Think in Strokes, Not Pixels: Process-Driven Image Generation via Interleaved Reasoning](papers/2026-04-09.md) |
| 2026-04-08 | [ThinkTwice: Jointly Optimizing Large Language Models for Reasoning and Self-Refinement](papers/2026-04-08.md) |
| 2026-04-07 | [Test-Time Scaling Makes Overtraining Compute-Optimal](papers/2026-04-07.md) |
| 2026-04-06 | [SpatialEdit: Benchmarking Fine-Grained Image Spatial Editing](papers/2026-04-06.md) |
| 2026-04-05 | [AURA: Always-On Understanding and Real-Time Assistance via Video Streams](papers/2026-04-05.md) |
| 2026-04-03 | [Self-Distilled RLVR](papers/2026-04-03.md) |
| 2026-04-02 | [Dynin-Omni: Omnimodal Unified Large Diffusion Language Model](papers/2026-04-02.md) |
| 2026-04-01 | [FIPO: Eliciting Deep Reasoning with Future-KL Influenced Policy Optimization](papers/2026-04-01.md) |
| 2026-03-31 | [PackForcing: Short Video Training Suffices for Long Video Sampling and Long Context Inference](papers/2026-03-31.md) |
| 2026-03-30 | [Out of Sight but Not Out of Mind: Hybrid Memory for Dynamic Video World Models](papers/2026-03-30.md) |

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
