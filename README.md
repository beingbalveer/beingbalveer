### Balveer Dhanoriya

**AI engineer — agentic systems, RAG, voice AI.**

Eight years shipping software that has to survive production. I started in mobile —
offline-first POS on broken hardware, a VPN client on three form factors — which is
where I learned that the interesting failures are never in the model.

Today I build AI systems end to end: architecture, cloud, delivery.

**What I'm working on**

- **[GraphMind](https://github.com/beingbalveer/GraphMind)** — open-source, AI-native
  knowledge workspace. Conversations branch into a DAG instead of scrolling away;
  `O(N)` token-budgeted lineage pruning, hybrid RRF retrieval over Postgres
  (`tsvector` + `pgvector`), provider-agnostic core across Gemini, Claude, OpenAI,
  DeepSeek and local Ollama.
- **[Vantage](https://github.com/beingbalveer/Vantage)** — a fast, local review deck for
  AI-agent commits. Tauri + Rust + Svelte, MIT, macOS/Windows/Linux, no telemetry.
  Read-only code browser with blame and definition peek, one to three repos side by side,
  heuristic triage for secrets / large deletions / dependency churn / removed tests, and a
  persistent PTY terminal per repo. I built it because auditing agent output meant
  alt-tabbing between VS Code, GitHub Desktop and a terminal all day.
- **Production voice AI** — sub-600ms speech-to-speech over WebRTC, in-call tool
  execution, and code-mixed Hindi–English ASR for the Indian market.
- **Deterministic agents** — a six-stage research pipeline that verifies every
  citation against its source text with an adversarial LLM judge.

**How I think about it**

Agents are 20% prompts and 80% distributed systems. Idempotency, stop conditions,
context budgets and evals are what make the difference between a demo and something
a business runs on.

**Elsewhere**

[balveerdhanoriya.com](https://balveerdhanoriya.com) · [LinkedIn](https://linkedin.com/in/balveer-dhanoriya)
