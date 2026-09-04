# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-09-05 | [Compile by Training: Turning Natural-Language Specifications into Local Neural Functions](papers/2026-09-05.md) |
| 2026-09-04 | [NeoMME: A Single-Tower Multimodal-Native Multilingual Foundation Encoder for Efficient Fine-Tuning and Inference](papers/2026-09-04.md) |
| 2026-09-03 | [From Production Traffic to Post-Training: Building a Self-Hosted LLM That Covers the Corporate Request Mix](papers/2026-09-03.md) |
| 2026-09-02 | [DreamX-Creator: Democratizing Native Audio-Video Generation at 2K Resolution](papers/2026-09-02.md) |
| 2026-09-01 | [LoopArena: Benchmarking Models as Runtime Controllers for Loop Engineering](papers/2026-09-01.md) |
| 2026-08-31 | [Agentic Game Development as a Verifiable Trajectory Data Engine for Scaling World Models](papers/2026-08-31.md) |
| 2026-08-30 | [Agentic Game Development as a Verifiable Trajectory Data Engine for Scaling World Models](papers/2026-08-30.md) |
| 2026-08-29 | [Agentic Game Development as a Verifiable Trajectory Data Engine for Scaling World Models](papers/2026-08-29.md) |
| 2026-08-28 | [Is Next-Chunk Reasoning RL Really Better than SFT? Revisiting Training Strategies under no-CoT Data](papers/2026-08-28.md) |
| 2026-08-27 | [GigaBrain-0.7: Scaling Embodied Foundation Models to Emergent Capabilities with a Three-System Architecture](papers/2026-08-27.md) |

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
