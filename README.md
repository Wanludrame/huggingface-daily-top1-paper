# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-08-22 | [Thinking in a Low-Resource Language: What SFT Builds, What RL Fixes, What Accuracy Cannot See](papers/2026-08-22.md) |
| 2026-08-21 | [Co-RL: Unsupervised Reasoning Emerges from Diverse Cohort in Multi-agent RL](papers/2026-08-21.md) |
| 2026-08-20 | [Demystifying Agent Skills: Why They Work-Until They Don't](papers/2026-08-20.md) |
| 2026-08-19 | [StateM: Reaching 95.3% Raw Accuracy, or a \$15 Frontier Run, on Terminal-Bench 2.1 via Harness Scaling](papers/2026-08-19.md) |
| 2026-08-04 | [SAF-OPD: Stable Advantage Fusion for On-Policy Distillation](papers/2026-08-04.md) |
| 2026-08-03 | [See2Think: Do Multimodal Models Really Use Intermediate Visual States?](papers/2026-08-03.md) |
| 2026-08-02 | [See2Think: Do Multimodal Models Really Use Intermediate Visual States?](papers/2026-08-02.md) |
| 2026-08-01 | [See2Think: Do Multimodal Models Really Use Intermediate Visual States?](papers/2026-08-01.md) |
| 2026-07-31 | [MindForge: Teaching Small Language Models Whole-Life-Cycle Software Engineering via Source-Free Program Synthesis](papers/2026-07-31.md) |
| 2026-07-30 | [CodeNib: A Multi-View Data System for Serving Repository Context to Coding Agents](papers/2026-07-30.md) |

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
