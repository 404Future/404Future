# 404Future

**Security Researcher · AppSec · Web3 · AI/LLM**  
[Intigriti](https://app.intigriti.com/profile/404Future) · [YesWeHack](https://yeswehack.com/hunters/404Future)

---

Security researcher with a background in defensive security operations and a focus on offensive research across three tracks: web application security, smart contract auditing, and AI/LLM vulnerability research.

My approach is informed by both sides of the discipline — understanding how defenders detect attacks shapes how I look for what they miss.

---

## Bug Bounty

Active on **Intigriti** and **YesWeHack**. Findings to date:

| Severity | Vulnerability | Status |
|---|---|---|
| P2 | Authentication bypass — chained logic flaw enabling full organisational impersonation | Disclosed |
| P2 | Account takeover — session fixation combined with absent rate limiting in QR-based login flow | Disclosed |
| P3 | Information disclosure — unauthenticated endpoint exposing internal infrastructure metrics | Disclosed |
| P3 | Path traversal — symlink traversal in widely-used developer tool enabling arbitrary file read | Disclosed |

Writeups are published in [`bug-bounty-writeups`](https://github.com/404Future/bug-bounty-writeups) as programmes clear findings for public disclosure.

---

## Research Tracks

**Web Application Security**  
Full recon-to-exploitation workflow covering XSS, IDOR, SSRF, CORS misconfiguration, business logic flaws, GraphQL abuse, prototype pollution, and API security. Core tooling: Burp Suite Pro, ffuf, Nuclei, Subfinder, httpx, gau, TruffleHog, Gitleaks, Kiterunner, Arjun, SSTImap.

**Web3 / Smart Contract Security**  
Working through the Cyfrin Updraft curriculum and completing First Flights audits. Methodology covers static analysis, manual code review with per-protocol threat modelling, invariant definition, fuzzing (Echidna, Medusa), and Foundry PoC development. Targeting competitive audit platforms (Sherlock, Code4rena) as the contest track builds. See [`audit-portfolio`](https://github.com/404Future/audit-portfolio) for full methodology and findings.

**AI / LLM Security**  
Focus on prompt injection, indirect prompt injection, agentic attack surfaces, and MCP server exploitation. Particularly interested in the convergence of AI agents with on-chain execution — an intersection with almost no published methodology and significant real-world risk. Tools: PyRIT, PyRIT-Ship (Burp extension), Garak, Promptfoo. See [`ai-security-research`](https://github.com/404Future/ai-security-research) for methodology and findings.

---

## Repositories

| Repository | Description |
|---|---|
| [`audit-portfolio`](https://github.com/404Future/audit-portfolio) | Audit reports, PoCs, and methodology for smart contract engagements |
| [`ai-security-research`](https://github.com/404Future/ai-security-research) | AI/LLM vulnerability research, CTF writeups, and tooling |
| [`bug-bounty-writeups`](https://github.com/404Future/bug-bounty-writeups) | Web application security writeups from Intigriti and YesWeHack |
| [`web3-security-tools`](https://github.com/404Future/web3-security-tools) | Scripts, templates, and tooling for smart contract audit workflows |

---

## Certifications

- Microsoft Certified: Security Operations Analyst Associate (SC-200) — 2026
- Blue Team Level 1 (BTL1) — Security Blue Team, 2025
- Google Cybersecurity Specialization — 2024

---

## Currently

- Completing Cyfrin Updraft (Solidity → Foundry → Smart Contract Security track)
- Running First Flights audits and documenting findings for public portfolio
- Hunting on Intigriti and YesWeHack
- Working through HTB AI Red Teamer path and Dreadnode Crucible challenges
- Building toward Cyfrin CESR certification
