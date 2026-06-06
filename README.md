# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-06-07 | [Code2LoRA: Hypernetwork-Generated Adapters for Code Language Models under Software Evolution](papers/2026-06-07.md) |
| 2026-06-06 | [Code2LoRA: Hypernetwork-Generated Adapters for Code Language Models under Software Evolution](papers/2026-06-06.md) |
| 2026-06-05 | [ZipSplat: Fewer Gaussians, Better Splats](papers/2026-06-05.md) |
| 2026-06-04 | [KVarN: Variance-Normalized KV-Cache Quantization Mitigates Error Accumulation in Reasoning Tasks](papers/2026-06-04.md) |
| 2026-06-03 | [Harness-1: Reinforcement Learning for Search Agents with State-Externalizing Harnesses](papers/2026-06-03.md) |
| 2026-06-02 | [Harness Updating Is Not Harness Benefit: Disentangling Evolution Capabilities in Self-Evolving LLM Agents](papers/2026-06-02.md) |
| 2026-06-01 | [Why Far Looks Up: Probing Spatial Representation in Vision-Language Models](papers/2026-06-01.md) |
| 2026-05-31 | [Why Far Looks Up: Probing Spatial Representation in Vision-Language Models](papers/2026-05-31.md) |
| 2026-05-29 | [GUI-CIDER: Mid-training GUI Agents via Causal Internalization and Density-aware Exemplar Reselection](papers/2026-05-29.md) |
| 2026-05-28 | [JLT: Clean-Latent Prediction in Latent Diffusion Transformers](papers/2026-05-28.md) |

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
