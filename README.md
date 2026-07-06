# Hix3 — Cyber and IA for RedTeaming Passionate

Offensive security engineer and penetration tester. I build **security tooling** and
research with **no bullshit** — autonomous vulnerability discovery,
rigorous evaluation of AI pentest agents, and high-performance recon.
*Spoiler Claude Cli is better than all opensource framework who try to enhance it.*

---

### 🔬 Featured work

**[LLM-Pentest-Framework-Benchmark](https://github.com/hix3-io/LLM-Pentest-Framework-Benchmark)**
A reproducible, black-box benchmark of AI-assisted pentest frameworks (PentestGPT, PentAGI,
AutoPentest-AI) against a fixed LLM, on custom vulnerable apps with a frozen ground truth.
Two headline results: at a fixed model the interactive baseline beats agentic orchestration once
context is enriched, and *loopback enrichment is not a free lunch* — it degrades fragile
orchestrators. Includes a write-up on **benchmarking non-deterministic agents** and proving a
finding is real. `Python · Docker · evaluation methodology`

**Offensive tooling** (Go, self-contained, built for real engagements):

- **[recondeps](https://github.com/hix3-io/recondeps)** — JS **supply-chain reconnaissance**: mines a target's JavaScript (incl. source maps, minified bundles, obfuscated `require`s) for npm package references, then verifies claimability to surface **dependency-confusion** candidates.
- **[spf-hunter](https://github.com/hix3-io/spf-hunter)** — **email-spoofability engine**: evaluates SPF/DMARC/DKIM the way a receiver does, ranks targets by impersonation value, and proves the verdict end-to-end with a built-in delivery oracle.
- **[urlpassivefinder](https://github.com/hix3-io/urlpassivefinder)** — high-performance passive URL discovery: concurrent workers, streaming, 6+ sources (Wayback, CommonCrawl, OTX, URLScan, crt.sh, VirusTotal, GitHub).

*Selected private work (available on request): a tri-agent autonomous 0-day discovery harness
(CVE-replay validated), and an EASM engine that maps 10k+ domains with LLM-assisted ownership
attribution.* 

---

### 🧭 Focus
- Autonomous vulnerability discovery & remediation with LLM agents
- Evaluation / red-teaming of AI systems in security environments
- All I find fun ! 
- Reproducible methodology for stochastic, agentic pipelines
- Responsible disclosure of findings in open-source software

### 🛠️ Toolbox
`Go` · `Python` · `Docker` · `LLM agents (Claude Code, MCP)` · `raw sockets / network scanners` ·
`web & API security` · `EASM`

> For authorized security research and education only.
