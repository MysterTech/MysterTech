<h1> Hi, I'm Sanjay Krishna aka MysterTech 👋 </h1>

I build quant systems, and the agents that build them.

Most of my work is private — commercial systems, client products, and strategy research that
stops being an edge the moment it's public. So this page isn't a wall of repos. It's a
description of what I actually work on, and what's hard about it.

**Lately, I've been working on**

- **TraderBro** — a quantitative research engine that treats strategy discovery as a governed
  search problem. Every hypothesis has to carry an economic rationale before it becomes a
  backtest, and results are judged by an adversarial validator that deflates significance
  against the size of the search that produced it. Campaigns run on a trial budget with a
  futility margin, so the system knows when to stop instead of mining noise.
- **AlphaBot** — the execution layer underneath the research. A trading engine and research
  harness that has to be correct when the market is open and nobody is watching.
- **MedScribe** — clinical documentation from live consultation audio. Speech-to-text with
  speaker diarization, then structured SOAP notes with clinical entity extraction. The hard
  part was never transcription; it's producing a note a clinician will actually sign.
- **Beyond Classroom** — an education platform, shipped and running in production. End-to-end
  product work from architecture through deployment.
- **VestLedger Skills** — domain-specific skill packs for coding agents. The difference between
  an agent that writes plausible code and one that knows the domain's rules.

Most of the interesting problems live in the same place: a system has to decide something under
uncertainty, and the expensive failure is confident nonsense. Backtests that found a pattern in
their own search. Agents that lose the thread and keep talking. Notes that read fine and say the
wrong thing. Almost everything I build has some machinery for catching itself being wrong.

**What's public**

- [ELCMS](https://github.com/MysterTech/lyzr-hackathon-submission) — context virtualization for
  agentic systems. Keeps agents accurate across sessions far exceeding the context window, using
  demand-paged segment selection and Pareto frontier optimization. 97.5% citation coverage at 48%
  lower token cost than conventional RAG.
- [Medical Scribe AI](https://github.com/MysterTech/curaconnect-demo) — a public proof-of-concept
  of the MedScribe pipeline, with a [live demo](https://curaconnect-demo.vercel.app).
- [Market Oracle](https://github.com/MysterTech/market-oracle) — portfolio-centric market
  intelligence for Indian equities, with Playwright capture tests pinning the UI.
- [apache-poi-xirr](https://github.com/MysterTech/apache-poi-xirr) — XIRR for irregular cashflows
  in Java. Small and self-contained; the kind of thing you find at 2am and are grateful for.

<h2> A bit about me </h2>

- Based in **Bengaluru, India**. I've been writing code on this account since 2014 — it started
  with Java and Spring microservices, went through a long TypeScript and GraphQL stretch, and
  landed on Python, quant research, and agent infrastructure.

- Python, TypeScript, and Rust day to day. Next.js and Vercel for anything with a UI. freqtrade,
  TA-Lib, OpenBB, and the NSE data stack for markets. Claude Code and MCP for the agent work.

- I write at [mystertech.com](https://www.mystertech.com) and post at
  [@MysterTechWeb](https://x.com/MysterTechWeb).

If you're building something at the intersection of markets and agents, I'd like to hear about it.
Reach out — that's usually the more interesting conversation.
