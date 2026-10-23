# Kenneth (Bicheng) Wang

**Principal-level Machine Learning Engineer**: AI agents, agent memory and reasoning, and large-scale pricing & marketplace ML systems. Based in the Bay Area; building [Altair AI](https://altairworld.com); industry experience at Salesforce, xAI, and Uber.

[LinkedIn](https://www.linkedin.com/in/kennethbcwang/) · [GitHub](https://github.com/BichengWang) · [Medium](https://medium.com/@bichengwang17) · [X](https://x.com/BichengW81192) · [YouTube](https://www.youtube.com/@kenneth_channel) · [Email](mailto:bichengwang17@gmail.com)

## Current Focus
- **Enterprise AI agents**: memory, reasoning, and personalization
- **Multi-agent coding teams**: measuring whether a team of agents beats a single agent on results and cost
- **Pricing & marketplace ML**: pricing, promotions, ranking, causal modeling, and experimentation at scale
- **Decision reliability**: replayable, verifiable records, calibration, and release gates for ML and LLM decisions
- **LLM training**: fine-tuning (SFT / RL), agent evaluation, and data flywheels

## Altair AI
[Altair AI](https://altairworld.com) is a financial and AI consulting firm in the San Francisco Bay Area, listed in the Claude and OpenAI partner networks. It runs its own research and agent systems:

- **[AI equity research](https://altairworld.com/TradingAgents/)**: Claude, GPT, and Gemini models each run the same multi-agent TradingAgents pipeline on about 70 US stocks and ETFs, refreshed weekly.
- **Agent access over MCP**: a free, read-only [remote MCP server](https://altairworld.com/mcp), listed in [awesome-remote-mcp-servers](https://github.com/punkpeye/awesome-remote-mcp-servers), plus the [altair-research](https://github.com/altair-world/altair-skills) agent skill (v1.0.0) for Claude Code, Codex, Cursor, and Gemini CLI.
- **[Market indicators](https://altairworld.com/indicators)**: factor and breadth indicators for the S&P 500, Nasdaq-100, and PHLX Semiconductor indices.

## Writing
Technical articles on [Medium](https://medium.com/@bichengwang17):

| Date | Article |
| --- | --- |
| 2026-10 | Replayable AI decisions, part 5: [Your LangGraph Approval Is Not Evidence](https://medium.com/@bichengwang17/your-langgraph-approval-is-not-evidence-3bb623a387f3) |
| 2026-10 | Replayable AI decisions, part 4: [5 of 7 Decisions Made on a Mac Failed to Replay on Linux](https://medium.com/@bichengwang17/5-of-7-decisions-made-on-a-mac-failed-to-replay-on-linux-a9f5e5d192a8) |
| 2026-10 | Replayable AI decisions, part 3: [One 2.0 Broke My JSON Hash in Node.js](https://medium.com/@bichengwang17/one-2-0-broke-my-json-hash-in-node-js-571078ea7f58) |
| 2026-10 | Replayable AI decisions, part 2: [A Hash Won't Stop the Forger Who Uses Your Own Tool](https://medium.com/@bichengwang17/a-hash-wont-stop-the-forger-who-uses-your-own-tool-3672ce42f390) |
| 2026-10 | Replayable AI decisions, part 1: [Your AI Shipped a Model. Can You Prove Why Six Months Later?](https://medium.com/@bichengwang17/your-ai-shipped-a-model-can-you-prove-why-six-months-later-da0ca762c808) |
| 2026-09 | [The Model Was Never the Bottleneck: Reliability Engineering for Real-Time ML Decisions](https://medium.com/@bichengwang17/the-model-was-never-the-bottleneck-reliability-engineering-for-real-time-ml-decisions-8d05416cf66c) |
| 2026-09 | [Compliance Is an Architecture Problem: Building Priced Decisions You Can Actually Audit](https://medium.com/@bichengwang17/compliance-is-an-architecture-problem-building-priced-decisions-you-can-actually-audit-d0760456b884) |
| 2026-09 | [Nobody Owns the Evaluator: Building a Calibration Standard for Fleets of Models](https://medium.com/@bichengwang17/nobody-owns-the-evaluator-building-a-calibration-standard-for-fleets-of-models-8cd93ac93688) |
| 2026-09 | [Your Model Is Accurate and Your Decision Is Wrong: Uplift Modeling in Production](https://medium.com/@bichengwang17/your-model-is-accurate-and-your-decision-is-wrong-uplift-modeling-in-production-64267468695d) |
| 2026-09 | [When Your Best Features Don't Exist: Graph Learning for Cross-Entity Sparsity in Marketplace Decisions](https://medium.com/@bichengwang17/when-your-best-features-dont-exist-graph-learning-for-cross-entity-sparsity-in-marketplace-09077c364fbc) |
| 2025-02 | [Large-Scale AI System: How Dynamic Recommendations and Pricing Real-time Optimization](https://medium.com/@bichengwang17/2023-how-does-large-scale-pricing-ml-eco-system-work-ccb2235e2aff) |

## Open Source

| Project | What it does |
| --- | --- |
| [ai-decision-system](https://github.com/BichengWang/ai-decision-system) ![stars](https://img.shields.io/github/stars/BichengWang/ai-decision-system?style=flat-square&label=%E2%98%85) | Replayable, offline-verifiable records for AI-assisted go/no-go decisions: typed model answers, policy-gated approvals, A/B ship gates, and release gates. |
| [multi-agents](https://github.com/BichengWang/multi-agents) ![stars](https://img.shields.io/github/stars/BichengWang/multi-agents?style=flat-square&label=%E2%98%85) | Teams of coding agents (Claude Code, Codex, or any model via the OpenAI Agents SDK) in isolated git worktrees, with a benchmark that measures whether the team beats a single agent on results and cost. On PyPI as [`multi-agent`](https://pypi.org/project/multi-agent/). |
| [financial-agent](https://github.com/BichengWang/financial-agent) ![stars](https://img.shields.io/github/stars/BichengWang/financial-agent?style=flat-square&label=%E2%98%85) | RL and portfolio-simulation research (Stable-Baselines3 A2C / DDPG / PPO / SAC / TD3) plus tooling that audits equity-research reports. |
| [RL-pricing](https://github.com/BichengWang/RL-pricing) ![stars](https://img.shields.io/github/stars/BichengWang/RL-pricing?style=flat-square&label=%E2%98%85) | Multi-stock RL trading strategies, a validation-Sharpe rolling ensemble, and an LSTM forecast-driven strategy, backtested against rule-based portfolios. |
| [TradingAgents](https://github.com/BichengWang/TradingAgents) ![stars](https://img.shields.io/github/stars/BichengWang/TradingAgents?style=flat-square&label=%E2%98%85) | Fork of [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents), a multi-agent LLM trading framework, extended with resumable batch report runs and multi-model [research reports](https://altairworld.com/TradingAgents/). |
| [altair-skills](https://github.com/altair-world/altair-skills) ![stars](https://img.shields.io/github/stars/altair-world/altair-skills?style=flat-square&label=%E2%98%85) | Agent skill that pulls each AI model's latest call on about 70 US stocks and ETFs from Altair's free MCP server and shows where the models disagree. |

Upstream: fixes and features submitted to agent frameworks and tools including Anthropic's Claude Agent SDK, Google ADK, OpenAI and Gemini cookbooks, Honcho, AG2, and Orca; merged in [VoiceStudio](https://github.com/debpalash/VoiceStudio/pull/2702).

## Research
- **Stanford CS230 — Deep Learning on Stock Trading** ([paper](https://drive.google.com/file/d/1-ogSAAA5L0sdy1iLt8HQKwV2kcN1UuCc/view?usp=sharing) · [video](https://www.youtube.com/watch?v=bE8MFq4sB2k) · [code](https://github.com/BichengWang/RL-pricing)): portfolio strategies combining auto-regressive forecasting with RL (PPO, A2C, DDPG, TD3, SAC). Beat the S&P 500 in rolling backtests with 1.33 Sharpe, 15% alpha, beta = 0.9.
- **UC Irvine — Recommendation System & Data Storage**: recurrent PageRank on Hadoop MapReduce using adjacency-matrix and embedding representations for real-time user and content recommendation.

## Patents
Granted Chinese invention patents on mobile user authentication from touch-behavior signals:

- [CN105068743B](https://patents.google.com/patent/CN105068743B/en): mobile-terminal user identity authentication based on multi-finger touch behavior (granted 2018)
- [CN104966016B](https://patents.google.com/patent/CN104966016B/en): cooperative child-user detection and operating-permission restriction on mobile terminals (granted 2018)
- [CN104850773B](https://patents.google.com/patent/CN104850773B/en): user identity authentication for smart mobile terminals (granted 2018)

## Skills
- **Languages**: Python, Go, Java, C++
- **LLM / Agents**: vLLM, LangChain, LlamaIndex, AutoGen, OpenAI Agents SDK, DeepEval; agent orchestration, memory, and evaluation
- **ML Frameworks**: PyTorch, Horovod, Ray, Stable-Baselines3
- **Data / Streaming**: Spark, Flink, Kafka
- **Infra**: Kubernetes, Yarn, Redis, Cassandra
- **Domains**: pricing, promotions, marketplace optimization, ranking, causal modeling, experimentation, simulation

## GitHub Stats
![Bicheng Wang's GitHub stats](https://github-readme-stats.vercel.app/api?username=bichengwang&show_icons=true&hide_border=true)

---

Open to collaborating on agents, decision reliability, and pricing ML: [bichengwang17@gmail.com](mailto:bichengwang17@gmail.com).
