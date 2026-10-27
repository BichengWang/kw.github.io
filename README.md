# Kenneth (Bicheng) Wang

**Principal-level Machine Learning Engineer**: AI agents, agent memory and reasoning, and large-scale pricing & marketplace ML systems. Based in the Bay Area; building [Altair AI](https://altairworld.com); industry experience at Salesforce, xAI, and Uber.

[LinkedIn](https://www.linkedin.com/in/kennethbcwang/) · [GitHub](https://github.com/BichengWang) · [Medium](https://medium.com/@bichengwang17) · [X](https://x.com/BichengW81192) · [YouTube](https://www.youtube.com/@kenneth_channel) · [Email](mailto:bichengwang17@gmail.com)

## Current Focus
- **Enterprise AI agents**: memory, reasoning, and personalization
- **Multi-agent coding teams**: measuring whether a team of agents beats a single agent on results and cost
- **Pricing & marketplace ML**: pricing, promotions, ranking, causal modeling, and experimentation at scale
- **Decision reliability**: replayable, verifiable records, calibration, and release gates for ML and LLM decisions
- **Reproducible trading AI**: re-testing published RL and LLM trading claims, my own included, under a pre-registered protocol
- **LLM training**: fine-tuning (SFT / RL), agent evaluation, and data flywheels

## Altair AI
[Altair AI](https://altairworld.com) is a financial and AI consulting firm in the San Francisco Bay Area, listed in the Claude and OpenAI partner networks. It runs its own research and agent systems:

- **[AI equity research](https://altairworld.com/TradingAgents/)**: Claude, GPT, and Gemini models each run the same multi-agent TradingAgents pipeline on about 70 US stocks and ETFs, refreshed weekly.
- **Agent access over MCP**: a [remote MCP server](https://altairworld.com/mcp), listed in [awesome-remote-mcp-servers](https://github.com/punkpeye/awesome-remote-mcp-servers), with free reports, market breadth, and indicators, plus structured research signals at $0.01 per call via x402. The [altair-research and altair-market](https://github.com/altair-world/altair-skills) agent skills (v1.1) work in Claude Code, Codex, Cursor, and Gemini CLI.
- **[Market indicators](https://altairworld.com/indicators)**: factor and breadth indicators for the S&P 500, Nasdaq-100, and PHLX Semiconductor indices, with S&P 500 breadth by sector and five years of history.

Altair is [hiring](https://altairworld.com/careers) a Member of Technical Staff to build AI agents, research tools, and the workspace behind them.

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
| [financial-agent](https://github.com/BichengWang/financial-agent) ![stars](https://img.shields.io/github/stars/BichengWang/financial-agent?style=flat-square&label=%E2%98%85) | Risk-managed systematic ETF trading in Python: cost-aware backtests, statistical certification, paper trading, and gated Alpaca / IBKR execution, plus equity and RL research. On PyPI as [`fa-quant`](https://pypi.org/project/fa-quant/). |
| [RL-pricing](https://github.com/BichengWang/RL-pricing) ![stars](https://img.shields.io/github/stars/BichengWang/RL-pricing?style=flat-square&label=%E2%98%85) | A reproducibility lab for trading AI: published RL and LLM trading claims re-tested under a pre-registered protocol, with a causal backtesting benchmark, a live decision ledger, and a public [leaderboard](https://bichengwang.github.io/RL-pricing/). |
| [TradingAgents](https://github.com/BichengWang/TradingAgents) ![stars](https://img.shields.io/github/stars/BichengWang/TradingAgents?style=flat-square&label=%E2%98%85) | Fork of [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents), a multi-agent LLM trading framework, extended with resumable batch report runs and multi-model [research reports](https://altairworld.com/TradingAgents/). |
| [altair-skills](https://github.com/altair-world/altair-skills) ![stars](https://img.shields.io/github/stars/altair-world/altair-skills?style=flat-square&label=%E2%98%85) | Agent skills for Altair's MCP server: `altair-research` pulls each AI model's latest call on about 70 US stocks and ETFs and shows where the models disagree; `altair-market` reads market breadth and factor indicators. |

### Contributions
Merged pull requests in widely used open-source projects:

| Project | Merged work |
| --- | --- |
| [VoiceStudio](https://github.com/debpalash/VoiceStudio) ![stars](https://img.shields.io/github/stars/debpalash/VoiceStudio?style=flat-square&label=%E2%98%85) | Stop silent default-voice retries after MLX model errors ([#2739](https://github.com/debpalash/VoiceStudio/pull/2739)); load the MOSS model and codec from independently pinned snapshots ([#2702](https://github.com/debpalash/VoiceStudio/pull/2702)) |
| [Gemini API Cookbook](https://github.com/google-gemini/cookbook) ![stars](https://img.shields.io/github/stars/google-gemini/cookbook?style=flat-square&label=%E2%98%85) | Link-checker and notebook-linter fixes ([#1425](https://github.com/google-gemini/cookbook/pull/1425), [#1418](https://github.com/google-gemini/cookbook/pull/1418), [#1414](https://github.com/google-gemini/cookbook/pull/1414), [#1405](https://github.com/google-gemini/cookbook/pull/1405)); Next steps for four REST quickstarts ([#1415](https://github.com/google-gemini/cookbook/pull/1415)) |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) ![stars](https://img.shields.io/github/stars/microsoft/agent-framework?style=flat-square&label=%E2%98%85) | `service_url` for the OpenAI and Ollama chat clients ([#9225](https://github.com/microsoft/agent-framework/pull/9225), [#9222](https://github.com/microsoft/agent-framework/pull/9222)); session persistence in the hosting quickstart ([#9030](https://github.com/microsoft/agent-framework/pull/9030)) |
| [Honcho](https://github.com/plastic-labs/honcho) ![stars](https://img.shields.io/github/stars/plastic-labs/honcho?style=flat-square&label=%E2%98%85) | Workspace-scoped `clone_session` lookups ([#1284](https://github.com/plastic-labs/honcho/pull/1284)); warnings for unused provider credentials ([#1344](https://github.com/plastic-labs/honcho/pull/1344)); dependency security bumps ([#1266](https://github.com/plastic-labs/honcho/pull/1266)) |
| [AG2](https://github.com/ag2ai/ag2) ![stars](https://img.shields.io/github/stars/ag2ai/ag2?style=flat-square&label=%E2%98%85) | A2A push-notification URL validation ([#3348](https://github.com/ag2ai/ag2/pull/3348)); toolkit merging that keeps tools and middleware ([#3387](https://github.com/ag2ai/ag2/pull/3387)); eval and filesystem-tool fixes ([#3423](https://github.com/ag2ai/ag2/pull/3423), [#3376](https://github.com/ag2ai/ag2/pull/3376), [#3303](https://github.com/ag2ai/ag2/pull/3303)) |
| [TensorFlow Docs](https://github.com/tensorflow/docs) ![stars](https://img.shields.io/github/stars/tensorflow/docs?style=flat-square&label=%E2%98%85) | Documentation fix ([#1834](https://github.com/tensorflow/docs/pull/1834)) |

Open pull requests to Anthropic's Claude Agent SDK, Claude Cookbooks, and Skills, Google ADK, the OpenAI Cookbook, TradingAgents, and Orca.

## Research
- **Deep Reinforcement Learning for Equity Trading: Benchmarking Actor-Critic Methods with Forward Retraining** (Wang & Zhang, 2026, [arXiv:2609.31870](https://arxiv.org/abs/2609.31870)): DDPG, TD3, SAC, PPO, and A2C on 20 large-cap stocks. Re-tested over five seeds in the [RL-pricing lab](https://github.com/BichengWang/RL-pricing/blob/main/reports/r0-wang-zhang-2026/report.md): the Sharpe claims partly hold; DDPG's 55.5% annual return does not (24.6%).
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
