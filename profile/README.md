<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/GILCHRIST_RESEARCH-Security_at_the_Speed_of_Inference-ff2d55?style=for-the-badge&labelColor=0d0d0d">
  <img alt="Gilchrist Research" src="https://img.shields.io/badge/GILCHRIST_RESEARCH-Security_at_the_Speed_of_Inference-ff2d55?style=for-the-badge&labelColor=0d0d0d">
</picture>

```
 ██████╗ ██╗██╗      ██████╗██╗  ██╗██████╗ ██╗███████╗████████╗
██╔════╝ ██║██║     ██╔════╝██║  ██║██╔══██╗██║██╔════╝╚══██╔══╝
██║  ███╗██║██║     ██║     ███████║██████╔╝██║███████╗   ██║   
██║   ██║██║██║     ██║     ██╔══██║██╔══██╗██║╚════██║   ██║   
╚██████╔╝██║███████╗╚██████╗██║  ██║██║  ██║██║███████║   ██║   
 ╚═════╝ ╚═╝╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝╚══════╝   ╚═╝   
                    R E S E A R C H
```

> **We build AI systems that find vulnerabilities before attackers do.**

---

### The Problem

DeFi protocols lost **$4B+** in 2024-2025. Traditional audits take weeks, cost $200K+, and miss economic exploits that only emerge at runtime. The industry needs autonomous, continuous security that thinks like an attacker.

### Our Approach

We combine static analysis engines (Slither, Semgrep, Mythril) with **AI reasoning** that understands DeFi economics: flash loan paths, oracle manipulation, MEV extraction, liquidation cascades, governance attacks. The scanner finds the code issues. The AI finds the money.

---

### 🔴 DeepThreat Platform

<table>
<tr>
<td width="33%" valign="top">

**⚡ Hunt**<br>
Autonomous bug bounty agent. Finds vulnerabilities, writes PoC exploits, submits reports. 24/7.

</td>
<td width="33%" valign="top">

**🔍 Review**<br>
AI code review for security. Catches what linters miss. Understands cross-contract interactions.

</td>
<td width="33%" valign="top">

**🛡️ Guard**<br>
CI/CD security gate. GitHub App that blocks vulnerable code before it ships.

</td>
</tr>
<tr>
<td width="33%" valign="top">

**📡 Intel**<br>
Threat intelligence feed. 4,200+ indexed incidents. Real-time exploit pattern matching.

</td>
<td width="33%" valign="top">

**📄 Wiki**<br>
Auto-generated threat models and security documentation from your codebase.

</td>
<td width="33%" valign="top">

**☁️ Cloud**<br>
Infrastructure and cloud security scanning. Coming soon.

</td>
</tr>
</table>

---

### Key Repos

| Repo | What it does |
|:-----|:-------------|
| [`deepthreat-core`](https://github.com/gilchrist-research/deepthreat-core) | The engine. Scanner orchestration + AI reasoning layer |
| [`deepthreat-intel-v1`](https://github.com/gilchrist-research/deepthreat-intel-v1) | Threat intelligence database. 6,900+ entries with structured metadata |
| [`deepthreat-bot`](https://github.com/gilchrist-research/deepthreat-bot) | GitHub App for automated security ops |
| [`deepthreat-wiki`](https://github.com/gilchrist-research/deepthreat-wiki) | Visual threat modeling with Mermaid.js |
| [`research`](https://github.com/gilchrist-research/research) | Security research, writeups, and tooling |
| [`agentic-hq`](https://github.com/gilchrist-research/agentic-hq) | Agent infrastructure-as-code. Configs, memory, automation |

---

### By the Numbers

```
461     security incidents indexed and analyzed
$1.15B  in recorded losses from our threat intel database
6,900+  structured threat intelligence entries
9       DeFi economic attack patterns modeled
6       integrated security products
24/7    autonomous agent operation
```

---

### Tech Stack

`TypeScript` `Python` `Rust` `Solidity` · `Slither` `Semgrep` `Mythril` `Aderyn` `Trivy` · `Claude` `GPT` `Gemini` · `NixOS`

---

### Philosophy

```
Ship fast. Automate everything. AI-first, human-reviewed.
Every finding is version-controlled. Every decision is auditable.
The scanner finds the code issues. The AI finds the money.
```

<sub>Security research and autonomous tooling from Texas · [deepthreat.io](https://deepthreat.io)</sub>
