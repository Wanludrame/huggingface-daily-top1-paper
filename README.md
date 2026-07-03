# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-07-04 | [Breaking Failure Cascades: Step-Aware Reinforcement Learning for Medical Multimodal Reasoning](papers/2026-07-04.md) |
| 2026-07-03 | [Are Performance-Optimization Benchmarks Reliably Measuring Coding Agents?](papers/2026-07-03.md) |
| 2026-07-02 | [Does VLA Even Know the Basics? Measuring Commonsense and World Knowledge Retention in Vision-Language-Action Models](papers/2026-07-02.md) |
| 2026-07-01 | [One Model, Many Latencies: Universal Speech Enhancement for Diverse Real-Time Applications](papers/2026-07-01.md) |
| 2026-06-30 | [Vesta: A Generalist Embodied Reasoning Model](papers/2026-06-30.md) |
| 2026-06-29 | [JetSpec: Breaking the Scaling Ceiling of Speculative Decoding with Parallel Tree Drafting](papers/2026-06-29.md) |
| 2026-06-28 | [JetSpec: Breaking the Scaling Ceiling of Speculative Decoding with Parallel Tree Drafting](papers/2026-06-28.md) |
| 2026-06-27 | [JetSpec: Breaking the Scaling Ceiling of Speculative Decoding with Parallel Tree Drafting](papers/2026-06-27.md) |
| 2026-06-26 | [ReNIO: Reweighting Negative Trajectory Importance for LLM On-Policy Distillation](papers/2026-06-26.md) |
| 2026-06-25 | [LingxiDiagBench: A Multi-Agent Framework for Benchmarking LLMs in Chinese Psychiatric Consultation and Diagnosis](papers/2026-06-25.md) |

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
