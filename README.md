# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

日期按 UTC 计算：北京时间每日 07:00 抓取前一 UTC 日期的论文；无论文的日期自动跳过。
Dates use UTC: the daily 07:00 China-time run fetches the previous UTC date; dates without papers are skipped.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-11-27 | [Stable Gated DeltaNet-2: Understanding and Mitigating Recurrent State Instability](papers/2026-11-27.md) |
| 2026-11-26 | [Real2SimLab: A Unified Platform for Real-to-Simulation Transfer](papers/2026-11-26.md) |
| 2026-11-25 | [Antom 3-in-1 Transformer: A Payment Foundation Model](papers/2026-11-25.md) |
| 2026-11-24 | [Motion Mamba 2.0: Autoregressive Diffusion Mamba for Long-Horizon Humanoid Control](papers/2026-11-24.md) |
| 2026-11-23 | [cmHC: Balancing Stream Mixing in Hyper-Connections via Geometric Contraction](papers/2026-11-23.md) |
| 2026-11-20 | [WeVisForensics: Self-Evolving Agent for Omni AI-Generated Video Detection](papers/2026-11-20.md) |
| 2026-11-19 | [Jeveration: System One Models Now Generate](papers/2026-11-19.md) |
| 2026-11-18 | [TeleChat to Xing4: Advancing Frontier Agentic Models on Domestic Chips and Frameworks](papers/2026-11-18.md) |
| 2026-11-17 | [Sage S2.1 Flash Technical Report](papers/2026-11-17.md) |
| 2026-11-16 | [Envisioning Agentic Robotics: A New Era of Robotic Systems](papers/2026-11-16.md) |

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
