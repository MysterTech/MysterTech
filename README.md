<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=C%20M%20Sanjay%20Krishna&fontSize=42&fontColor=ffffff&fontAlignY=32&desc=Quant%20systems%20%C2%B7%20Agentic%20AI%20%C2%B7%20Trading%20infrastructure&descAlignY=52&descSize=16&animation=fadeIn" width="100%" alt="C M Sanjay Krishna" />

<a href="https://github.com/MysterTech">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=720&height=60&lines=I+build+quant+systems.;And+the+agents+that+build+them.;Backtests%2C+not+backtested+opinions." alt="Typing intro" />
</a>

<br/>

<a href="https://www.mystertech.com"><img src="https://img.shields.io/badge/mystertech.com-0A0A0A?style=for-the-badge&logo=safari&logoColor=58A6FF" alt="Website" /></a>
<a href="https://x.com/MysterTechWeb"><img src="https://img.shields.io/badge/@MysterTechWeb-0A0A0A?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
<img src="https://img.shields.io/badge/Bengaluru,%20India-0A0A0A?style=for-the-badge&logo=googlemaps&logoColor=EA4335" alt="Bengaluru, India" />

</div>

<br/>

I work at the seam between **quantitative finance** and **agentic AI** — building trading
research infrastructure, and building the multi-agent systems that do the research.

**Most of my work lives in private repositories.** Commercial systems, client products, and
strategy research that stops being an edge the moment it's public. So this page does the
thing a green squares grid can't: it tells you what I actually build, and what's hard about it.

<br/>

## What I'm building

<table>
<tr>
<td width="50%" valign="top">

### 🔬 TraderBro · `private`

**Strategy discovery as a governed search problem.**

Most quant research dies the same way: you try a thousand configurations, one looks
significant, and you've discovered nothing but your own search. TraderBro is built against
that failure mode.

Hypotheses must carry an economic rationale before they're specified into a backtest.
Results are judged by an **adversarial validator that deflates significance against the size
of the search that produced it**, and checks novelty against everything already in the book.
Campaigns run on an explicit trial budget with a futility margin — so the system knows when
to stop rather than mine noise until something looks good.

`Python` · multi-agent research pipeline · backtesting · statistical rigor guards

</td>
<td width="50%" valign="top">

### 🎓 Beyond Classroom · `private`

**Education platform, shipped and in production.**

End-to-end product work — architecture through deployment, running live on Vercel.

`TypeScript` · `Next.js` · `React` · `Vercel`

<br/>

### ⚙️ AlphaBot · `private`

**The execution layer beneath the research.**

Trading engine and research harness — the part that has to be correct when the market is
open and nobody is watching.

`Python` · execution · market data

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🩺 MedScribe · `private`

**Clinical documentation from live consultation audio.**

Speech-to-text with speaker diarization separating provider from patient, then structured
SOAP note generation with clinical entity extraction. The hard part isn't transcription —
it's producing notes a clinician will actually sign.

A public proof-of-concept is linked below.

`TypeScript` · `React` · speech + LLM pipeline

</td>
<td width="50%" valign="top">

### 🧰 VestLedger Skills · `private`

**Making coding agents competent in a narrow vertical.**

Domain-specific skill packs — the difference between an agent that writes plausible code
and one that knows the domain's rules.

`agent tooling` · `MCP` · `Claude Code`

</td>
</tr>
</table>

<br/>

## What's open

Smaller surface than the above, but these you can read.

| | |
|---|---|
| **[ELCMS](https://github.com/MysterTech/lyzr-hackathon-submission)** | Context virtualization for agentic systems — keeps agents accurate across sessions far exceeding the context window. Demand-paged segment selection, Pareto frontier optimization, hierarchical coverage guarantees. **≥97.5% citation coverage at 48% lower token cost.** `Python` |
| **[Medical Scribe AI](https://github.com/MysterTech/curaconnect-demo)** | Public POC of the MedScribe pipeline — Whisper transcription, diarization, automated SOAP notes, full session lifecycle. `TypeScript` · [live demo](https://curaconnect-demo.vercel.app) |
| **[Market Oracle](https://github.com/MysterTech/market-oracle)** | Portfolio-centric market intelligence for Indian equities. Next.js prototype with Playwright capture tests pinning the UI. `TypeScript` |
| **[apache-poi-xirr](https://github.com/MysterTech/apache-poi-xirr)** | XIRR without a spreadsheet — irregular-cashflow returns in Java. Small, self-contained, the kind of thing you find at 2am and are grateful for. `Java` |

<br/>

## Stack

<div align="center">

**Systems & research**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />

**Quant & markets**

<img src="https://img.shields.io/badge/freqtrade-2E86C1?style=flat-square&logo=bitcoin&logoColor=white" />
<img src="https://img.shields.io/badge/TA--Lib-1F618D?style=flat-square" />
<img src="https://img.shields.io/badge/OpenBB-FFD700?style=flat-square&logoColor=black" />
<img src="https://img.shields.io/badge/NumerAI-00D1B2?style=flat-square" />
<img src="https://img.shields.io/badge/NSE%20%2F%20India-FF6F00?style=flat-square" />

**Product & web**

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />

**Agents & infra**

<img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/MCP-6E56CF?style=flat-square" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />

</div>

<br/>

<div align="center">

**Open to conversations about quant infrastructure, agentic systems, and the space between them.**

<a href="https://www.mystertech.com">mystertech.com</a> · <a href="https://x.com/MysterTechWeb">@MysterTechWeb</a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" alt="" />

</div>
