# HuggingFace Daily Top 1 Paper Reading

每天自动抓取 [HuggingFace Daily Papers](https://huggingface.co/papers) 热门论文 Top 1，并通过 AI 生成中文深度解读。

Daily automatic fetch of the #1 trending paper from [HuggingFace Daily Papers](https://huggingface.co/papers), with AI-generated in-depth analysis in Chinese.

日期按 UTC 计算：北京时间每日 07:00 抓取前一 UTC 日期的论文；无论文的日期自动跳过。
Dates use UTC: the daily 07:00 China-time run fetches the previous UTC date; dates without papers are skipped.

---

## Latest / 最新论文解读

| 日期 Date | 论文 Paper |
|-----------|-----------|
| 2026-11-12 | [Scaling Mathematical Proof Supervision from Structured Textbooks](papers/2026-11-12.md) |
| 2026-11-11 | [World In-Context Learning for Agentic Robot Manipulation](papers/2026-11-11.md) |
| 2026-11-10 | [Learning Heterogeneous Tactile Representation for General Dexterous Manipulation](papers/2026-11-10.md) |
| 2026-11-09 | [Confucius4-R2T2: A Stable-Prefix Streaming ASR Model for Real Real-Time Transcription](papers/2026-11-09.md) |
| 2026-11-06 | [VFlash: Fast, Accurate Visual Planning via Flash Primitive Decoding](papers/2026-11-06.md) |
| 2026-11-05 | [Every Token Needs Its Own Teacher: Multi-teacher Adaptive On-policy Self-distillation](papers/2026-11-05.md) |
| 2026-11-04 | [SWE-Trail: History-Guided Trajectory Collection for Coding Agent Training](papers/2026-11-04.md) |
| 2026-11-03 | [Follow the Gradient: Tracing Safety Degradation Back to Training Data](papers/2026-11-03.md) |
| 2026-11-02 | [Proving and Improving the Platonic Representation Hypothesis with JEPAs](papers/2026-11-02.md) |
| 2026-10-30 | [Look Only When Needed: Certificate-Guided Visual Routing for Efficient Diffusion VLMs](papers/2026-10-30.md) |

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
