# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-04-28 | [From Skills to Talent: Organising Heterogeneous Agents as a Real-World Company](papers/2026-04-28.md) |
| 2026-04-27 | [LLaTiSA: Towards Difficulty-Stratified Time Series Reasoning from Visual Perception to Semantics](papers/2026-04-27.md) |
| 2026-04-25 | [LLaTiSA: Towards Difficulty-Stratified Time Series Reasoning from Visual Perception to Semantics](papers/2026-04-25.md) |
| 2026-04-24 | [OpenMobile: Building Open Mobile Agents with Task and Trajectory Synthesis](papers/2026-04-24.md) |
| 2026-04-23 | [ShadowPEFT: Shadow Network for Parameter-Efficient Fine-Tuning](papers/2026-04-23.md) |
| 2026-04-22 | [The Illusion of Certainty: Decoupling Capability and Calibration in On-Policy Distillation](papers/2026-04-22.md) |
| 2026-04-21 | [Elucidating the SNR-t Bias of Diffusion Probabilistic Models](papers/2026-04-21.md) |
| 2026-04-18 | [Switch-KD: Visual-Switch Knowledge Distillation for Vision-Language Models](papers/2026-04-18.md) |
| 2026-04-17 | [Target Policy Optimization](papers/2026-04-17.md) |
| 2026-04-16 | [RationalRewards: Reasoning Rewards Scale Visual Generation Both Training and Test Time](papers/2026-04-16.md) |

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
