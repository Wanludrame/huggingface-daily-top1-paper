# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-06-21 | [Context-Aware RL for Agentic and Multimodal LLMs](papers/2026-06-21.md) |
| 2026-06-20 | [Context-Aware RL for Agentic and Multimodal LLMs](papers/2026-06-20.md) |
| 2026-06-19 | [MolmoMotion: Forecasting Point Trajectories in 3D with Language Instruction](papers/2026-06-19.md) |
| 2026-06-18 | [Self-Evolving Visual Questioner](papers/2026-06-18.md) |
| 2026-06-17 | [Ling and Ring 2.6 Technical Report: Efficient and Instant Agentic Intelligence at Trillion-Parameter Scale](papers/2026-06-17.md) |
| 2026-06-16 | [iMaC: Translating Actions into Motion and Contact Images for Embodied World Models](papers/2026-06-16.md) |
| 2026-06-15 | [Risk Under Pressure: Compute-Aware Evaluation of Adversarial Robustness in Language Models](papers/2026-06-15.md) |
| 2026-06-14 | [Risk Under Pressure: Compute-Aware Evaluation of Adversarial Robustness in Language Models](papers/2026-06-14.md) |
| 2026-06-13 | [Risk Under Pressure: Compute-Aware Evaluation of Adversarial Robustness in Language Models](papers/2026-06-13.md) |
| 2026-06-12 | [Reroute, Don't Remove: Recoverable Visual Token Routing for Vision-Language Models](papers/2026-06-12.md) |

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
