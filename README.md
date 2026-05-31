## 🔐 Building security tools, one zero‑day at a time

Security engineer. Rust builder. Zero‑trust practitioner.

I build tools that make security **measurable**, **actionable**, and **free**.  
No SaaS. No exfiltration. No licensing traps — just a binary, your terminal, and your code.

---

### 🛡️ What I've Built

| Project | Description | Stack |
|---|---|---|
| **[ApeGuard][apeguard]** | One-command local security audit — 5 scanner layers, ZT mapping, multi-format reports | Rust · CLI · MCP |
| **[UZTF][uztf]** | The Unified Zero Trust Framework — 8-pillar maturity model that extends CISA ZTMM with quantitative scoring | Spec · YAML · Kyōto |

> `brew install apeguard` → finds **secrets**, **vulns**, **misconfigs**, and **attack chains** in your codebase.  
> Outputs Markdown, JSON, SARIF, or HTML — for engineers, leadership, and auditors.

### 📦 Quick Start

```bash
# Install ApeGuard (macOS / Linux)
brew tap pirateape/tap && brew install apeguard

# Full audit — your source code right now
apeguard run --dir . --report md
```

---

### 📊 What I'm Focused On

- **Making security posture zero‑cost** — every team deserves enterprise‑grade tooling
- **Closing the CISA-to-execution gap** — frameworks are useless without CLI tools that implement them
- **Rust-native security tooling** — memory‑safe, single binary, no runtime deps
- **AI‑augmented remediation** — using LLMs to close findings, not just find them

---

### 🔗 Links

[![ApeGuard][badge-apeguard]][apeguard]
[![UZTF][badge-uztf]][uztf]
[![Homebrew][badge-brew]][tap]

---

<details>
<summary><b>📈 Activity & Stats</b></summary>

<br>

```
▲   ApeGuard     — Rust security scanner      ▲ 131 tests · 0 warnings · v0.1.0
▲   UZTF         — Zero Trust Framework       ▲ Released v1.0 · CISA-aligned
▲   homebrew-tap — ApeGuard Homebrew formula   ▲ SHA-256 pinned · auto-updated
```

</details>

[apeguard]: https://github.com/pirateape/ape-guard
[uztf]: https://github.com/pirateape/unified-zero-trust-framework
[tap]: https://github.com/pirateape/homebrew-tap

[badge-apeguard]: https://img.shields.io/badge/ApeGuard-FF6B35?style=flat-square&logo=rust&logoColor=white
[badge-uztf]: https://img.shields.io/badge/UZTF-1A1A2E?style=flat-square&logo=letsencrypt&logoColor=white
[badge-brew]: https://img.shields.io/badge/Homebrew-FBB040?style=flat-square&logo=homebrew&logoColor=black
