# Harshanandhan Reddy Gajulaplli

**GenAI / ML Security · Cybersecurity · Blockchain**  
Erie / Pennsylvania, USA · Open to work

[Portfolio](https://harshanandhanreddy.com) · [GitHub](https://github.com/Harshanandhan) · [LinkedIn](https://www.linkedin.com/in/harshanandhan-reddy-gajulapalli-91a951395/) · [Email](mailto:harshanandhanreddy820@gmail.com) · **+1 (814) 504-1946**

I build and ship AI-adjacent security labs and small LLM products, apply OWASP / MITRE ATT&CK thinking to detection work, and practice smart-contract security with Hardhat, Foundry, and Slither. Looking for **SOC analyst**, **security engineer**, **AI security**, and **blockchain security** roles.

---

## Contact & details

| | |
|---|---|
| **Full name** | Harshanandhan Reddy Gajulaplli |
| **Phone** | +1 (814) 504-1946 |
| **Email** | [harshanandhanreddy820@gmail.com](mailto:harshanandhanreddy820@gmail.com) |
| **GitHub** | [@Harshanandhan](https://github.com/Harshanandhan) |
| **LinkedIn** | [harshanandhan-reddy-gajulapalli](https://www.linkedin.com/in/harshanandhan-reddy-gajulapalli-91a951395/) |
| **Portfolio** | [harshanandhanreddy.com](https://harshanandhanreddy.com) |
| **Location** | Erie / Pennsylvania, USA |

---

## Professional summary

GenAI/ML security engineer with hands-on experience productionizing LLM systems (Repostly, Documind, Claude/Groq agentic workflows) and applying offensive-security fundamentals (OWASP Top 10, MITRE ATT&CK, SIEM / threat detection) to AI-adjacent attack surfaces. Background includes evaluating ML-based vulnerability detectors, smart-contract security research, and turning findings into concrete mitigations. MS Cybersecurity (Gannon University); thesis on an MCP-enhanced AI framework combining LLM and ensemble-ML pipelines.

---

## Education

- **MS Cybersecurity** — Gannon University, Erie, PA (Jan 2024 – Dec 2025)
- **BTech, AI & Data Science** — Amrita Vishwa Vidyapeetham, India (Jun 2019 – May 2023)

### Graduate thesis

**MCP-Enhanced AI Framework for Early Detection of Pancreatic Cancer** — Gannon University  
Proof-of-concept diagnostic framework combining ensemble ML (XGBoost / SVM, LightGBM, Dynamic ConvNets) with n8n workflow automation and a Google Gemini LLM backend, containerized with Docker.

---

## Experience

### Cybersecurity Lab Assistant — Gannon University, Erie, PA  
*Jan 2025 – Dec 2025*

- Built and managed Kali Linux VMs for **40+** students; automated setup with Bash/Ansible (reported ~30% faster deploy, ~20% better lab network uptime)
- Taught hands-on labs (Wireshark, subnetting, OSI); mentored students on AI/ML-enhanced security and smart-contract development, framing risks as attacker TTPs and mitigations

### Blockchain Security Auditor — Independent projects & research  
*Jun 2021 – Dec 2023*

- Reviewed **20+** Solidity/Rust smart contracts with Slither and MythX; focused on reentrancy and access-control findings turned into mitigations (input validation, access-control patterns, circuit breakers)
- Deployed ERC-20 staking/dividend contracts to Sepolia; documented flash-loan / DeFi risk research with mitigation notes (TWAP oracles, circuit breakers) for a non-technical audience

### Conference Volunteer — BSides Rock, Rochester, PA  
*Jun 2024*

- Coordinated security workshops for **300+** professionals; contributed to an AI/ML-powered threat-detection demo

---

## Live demos (clickable)

| Project | Live | Repo |
|---|---|---|
| **SIEM Dashboard** (SOC-style lab UI + deterministic pattern hunter) | [buggerhunt.vercel.app](https://buggerhunt.vercel.app) | private lab |
| **Solidity Vulnerability Detector** | [Railway demo](https://solidity-vuln-detector-demo-production.up.railway.app) | [code](https://github.com/Harshanandhan/solidity-vulnerability-detector) |
| **Solidity Lab Demos** (staking + dividend) | [solidity-lab-demos.vercel.app](https://solidity-lab-demos.vercel.app) | [staking](https://github.com/Harshanandhan/erc20-staking-vault) · [dividend](https://github.com/Harshanandhan/dividend-token) |
| **BharatBot** (RAG over 10 local chunks) | [Railway](https://bharatbot-production-9181.up.railway.app) | [bharatbot](https://github.com/Harshanandhan/bharatbot) |
| **Documind** (PDF/CSV/Excel extract; Groq optional) | [Railway](https://documind-free-production.up.railway.app) | [Documind-Free-version](https://github.com/Harshanandhan/Documind-Free-version) |
| **document-agent** (Claude tool-use lab) | [Railway](https://luminous-compassion-production-1f80.up.railway.app) | [document-agent](https://github.com/Harshanandhan/document-agent) |
| **Portfolio** | [harshanandhanreddy.com](https://harshanandhanreddy.com) | [portfolio](https://github.com/Harshanandhan/portfolio) |

---

## Featured projects (evidence-honest)

### Security & detection

| Project | What it is | Evidence / limits |
|---|---|---|
| [SIEM Detection Lab](https://github.com/Harshanandhan/siem-detection-lab) | Python detection rules on generated auth / Apache / iptables logs; MITRE-mapped alerts | 2026-09-09: **3** alerts (SSH brute force T1110.001, SQLi T1190, port scan T1046). Lab — **not** Elastic / not a production SOC |
| [SIEM Dashboard](https://buggerhunt.vercel.app) | Next.js SOC-style UI + pattern hunter (no LLM / threat-intel APIs) | Live demo + Vitest coverage; demo logs only |
| [Host Security Scanner](https://github.com/Harshanandhan/host-security-scanner) | TCP connect, banners, web checks, headers, TLS peek | 2026-09-09 on scanme.nmap.org: **4** open ports, **5** missing headers. **No** CVE database |
| [Solidity Vulnerability Detector](https://github.com/Harshanandhan/solidity-vulnerability-detector) | Pattern triage for reentrancy-style calls, owner checks, unchecked calls, timestamp, `tx.origin` (+ optional Slither) | Sample ~**7** vs ~**0** clean. Pattern checks — **not** a full ML audit product |

### Blockchain

| Project | What it is | Evidence / limits |
|---|---|---|
| [ERC-20 Staking Vault](https://github.com/Harshanandhan/erc20-staking-vault) | Stake / withdraw STK with ReentrancyGuard + CEI | Hardhat: **6** passing (2026-09-09). Lab — not mainnet |
| [DividendToken](https://github.com/Harshanandhan/dividend-token) | Holder dividends vs staking on the same balance | Hardhat: **33** passing (2026-09-09) |
| [dvde-flash-loan-exploit](https://github.com/Harshanandhan/dvde-flash-loan-exploit) | Flash-loan lab notes / research placeholder | Verify any exploit claims against Foundry runs before citing |

### AI / product

| Project | What it is | Evidence / limits |
|---|---|---|
| [Repostly](https://github.com/Harshanandhan/yt-repurposer-web) | Next.js YouTube → LinkedIn drafts (Supabase / Claude / Stripe wired in code) | `npm` build verified. **repostly.org TLS expired** — do not treat as a reliable live SaaS or paying-customer proof |
| [Documind](https://github.com/Harshanandhan/Documind-Free-version) | FastAPI extract from PDF/CSV/Excel; optional Groq Llama 3.3 structuring | Extract proven; **no OCR**; live UI may be extract-only without key |
| [document-agent](https://github.com/Harshanandhan/document-agent) | FastAPI + Claude tool-use document agent | Live lab UI; needs `ANTHROPIC_API_KEY` for full agent path |
| [BharatBot](https://github.com/Harshanandhan/bharatbot) | FastAPI RAG over 10 Indian history chunks | Live; retrieval always; Groq optional |
| [Hatch Agent](https://github.com/Harshanandhan/hatch-agent) | Student job agent: find → pattern tailor → review-before-submit | Public README pitch; implementation stays private |
| [IRIS Vessel Segmentation](https://github.com/Harshanandhan/IRIS-Vessel-Segmentation) | U-Net + EfficientNetB3 notebook | Educational CV — not a production biometric system |

---

## Technical skills

- **AI security & red teaming:** adversarial ML evaluation, LLM system-prompt hardening concepts, OWASP Top 10 for LLM Apps, MITRE ATT&CK (applied), agentic workflow risk analysis, prompt engineering
- **AI / ML:** Python, Claude API, Groq / Llama 3.3, LangChain, n8n, CrewAI, TensorFlow, scikit-learn, CodeBERT, LSTM, SHAP
- **Cybersecurity:** SIEM concepts (Splunk / ELK familiarity), vulnerability assessment, Kali, Burp Suite, Nmap, Metasploit, Nessus, OWASP Top 10, NIST CSF, MITRE ATT&CK
- **Blockchain / Web3 security:** Solidity, Rust, Ethereum, Hardhat, Foundry, Slither, MythX, EVM, ERC-20, OpenZeppelin, DeFi risk research
- **Development:** Next.js, TypeScript, JavaScript, FastAPI, SQL, Docker, Bash, Stripe, Supabase

---

## Certifications

- Cybersecurity Foundations — Google / Coursera (Jan 2026)
- Solidity / Ethereum Developer Bootcamp — Alchemy University (Dec 2024)
- Claude 101, Claude Code 101, Introduction to Claude Cowork — Anthropic Academy (Jun 2026)
- Claude Code in Action, Claude Platform 101 — Anthropic Academy (Jun 2026)
- AI Fluency: Framework & Foundations (10/10), Building with the Claude API — Anthropic Academy (Jun 2026)
- In progress: CompTIA Security+

---

## Contact

Open to full-time **SOC / security engineering / AI security / blockchain security** roles.

**Phone:** +1 (814) 504-1946  
**Email:** harshanandhanreddy820@gmail.com  
**LinkedIn:** [harshanandhan-reddy-gajulapalli](https://www.linkedin.com/in/harshanandhan-reddy-gajulapalli-91a951395/)  
**Site:** [harshanandhanreddy.com](https://harshanandhanreddy.com)