# 🛡️ CyberSec Toolkit

> **Free, open-source cybersecurity templates built by [Jaswanth K L](https://www.linkedin.com/in/jaswanthkl)**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-00C8E8?style=for-the-badge)](https://jaswanthkl.github.io/cybersec-toolkit)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Templates](https://img.shields.io/badge/Templates-45%2B-brightgreen?style=for-the-badge)]()
[![Domains](https://img.shields.io/badge/Domains-9-blue?style=for-the-badge)]()
[![Cost](https://img.shields.io/badge/Cost-Free-gold?style=for-the-badge)]()

---

## 🔗 [→ Live Demo: jaswanthkl.github.io/cybersec-toolkit](https://jaswanthkl.github.io/cybersec-toolkit)

Click any template on the site — it opens as a **fully interactive spreadsheet** right in your browser. No login. No Excel. No cost.

---

## 📖 About This Project

I built this toolkit because cybersecurity professionals spend too much time building trackers and templates from scratch. Every domain — from SOC operations to cloud security to GRC — needs the same core documents, and they shouldn't be locked behind a paywall.

This project gives you:
- **Interactive browser-based templates** pre-filled with realistic sample data
- **Export to CSV** — download any template for use in Excel or Google Sheets
- **9 complete security domains** with dashboards and operational templates
- **Zero setup** — works entirely in the browser, no install required

---

## 🗂️ Security Domains

| # | Domain | Templates | What's Included |
|---|--------|-----------|-----------------|
| 1 | 🌐 Network Security | 8 templates | DDoS tracker, IP whitelist/blacklist, NAC log, device inventory, risk reports, VPN log |
| 2 | 🗄️ Data Security | 5 templates | Data classification, breach notification, DLP log, retention schedule, risk matrix |
| 3 | 💻 Endpoint Security | 5 templates | Asset inventory, malware detection log, baseline checklist, isolation tracker, cost analysis |
| 4 | ⚖️ GRC | 6 templates | Audit findings, compliance tracker, control framework mapping, KRI tracker, vendor risk |
| 5 | 🔭 SOC | 5 templates | IR playbook, triage checklist, log source onboarding, malware analysis report, RCA |
| 6 | ☁️ Cloud Security | 5 templates | IAM matrix, asset inventory, backup testing, cloud IR log, config baseline |
| 7 | 🔏 Information Security | 5 templates | Access rights matrix, policy compliance, incident tracking, breach notification |
| 8 | 🛡️ Application Security | 5 templates | Vuln register, SAST/DAST tracker, dependency risk log, pen test results, code review |
| 9 | 🔍 Vulnerability Management | 5 templates | Risk scoring matrix, patch tracker, CVE log, SLA tracker, scan schedule |

**Plus:** 27 Security Management Documents covering Incident Management, Problem Management, and Disaster Recovery.

---

## ✨ Features

- **45+ interactive templates** — click to open, edit directly in browser
- **Realistic sample data** — every template comes pre-filled so you know exactly how to use it
- **Export to CSV** — one click exports any template as a CSV file
- **Color-coded status fields** — severity, risk levels, and statuses are colour coded
- **No login required** — completely open, no account needed
- **Mobile responsive** — works on any device
- **MIT Licensed** — use it, fork it, build on it

---

## 📁 Project Structure

```
cybersec-toolkit/
│
├── index.html              ← Main application (entire toolkit)
│
├── src/
│   ├── templates/          ← Template data definitions (JSON)
│   │   ├── network.js
│   │   ├── data-security.js
│   │   ├── endpoint.js
│   │   ├── grc.js
│   │   ├── soc.js
│   │   ├── cloud.js
│   │   ├── infosec.js
│   │   ├── appsec.js
│   │   └── vuln-mgmt.js
│   └── styles/
│       └── main.css        ← Extracted stylesheet
│
├── templates/              ← Downloadable CSV versions
│   ├── network-security/
│   ├── data-security/
│   ├── endpoint-security/
│   ├── grc/
│   ├── soc/
│   ├── cloud-security/
│   ├── infosec/
│   ├── appsec/
│   └── vuln-management/
│
├── docs/
│   ├── DOMAINS.md          ← Detailed domain documentation
│   ├── CONTRIBUTING.md     ← How to contribute
│   └── CHANGELOG.md        ← Version history
│
├── assets/
│   └── preview.png         ← Screenshot for README
│
├── LICENSE                 ← MIT License
└── README.md               ← This file
```

---

## 🚀 Usage

### Option 1 — Use the live site
Just go to **[jaswanthkl.github.io/cybersec-toolkit](https://jaswanthkl.github.io/cybersec-toolkit)** and start clicking templates.

### Option 2 — Run locally
```bash
# Clone the repo
git clone https://github.com/jaswanthkl/cybersec-toolkit.git
cd cybersec-toolkit

# Just open index.html in your browser — no server needed
open index.html
```

### Option 3 — Fork and customise
```bash
# Fork on GitHub, then clone your fork
git clone https://github.com/YOUR_USERNAME/cybersec-toolkit.git

# Make your changes to index.html or the src/ files
# Push back to GitHub and enable GitHub Pages
```

---

## 📋 Template Details

<details>
<summary><strong>🌐 Network Security (8 templates)</strong></summary>

| Template | Purpose |
|----------|---------|
| DDoS Attack Mitigation Plan Tracker | Track DDoS events, response times, and mitigation effectiveness |
| IP Whitelist-Blacklist Tracker | Maintain and audit your IP allow/block lists |
| Network Access Control Log | Log NAC decisions and authentication events |
| Network Device Inventory | Full inventory of network devices with firmware and patch status |
| Network Security Risk Mitigation Report | Risk-rated mitigation actions for network threats |
| Patch Management Schedule (Network Devices) | Schedule and track firmware updates |
| Security Event Correlation Tracker | Correlate events across log sources |
| VPN Usage Log | Audit VPN connections by user, device, and location |

</details>

<details>
<summary><strong>⚖️ GRC — Governance, Risk & Compliance (6 templates)</strong></summary>

| Template | Purpose |
|----------|---------|
| Audit Findings Remediation Tracker | Track audit findings from discovery to closure |
| Compliance Requirements Tracker | Monitor obligations across ISO, NIST, PCI, GDPR |
| Control Framework Mapping | Map controls across multiple frameworks |
| Control Mapping Matrix | Matrix view of controls vs risk categories |
| Key Risk Indicators (KRI) Tracker | Monitor leading risk indicators with thresholds |
| Third Party Vendor Risk Assessment | Score and track vendor cybersecurity risk |

</details>

<details>
<summary><strong>🔭 SOC — Security Operations (5 templates)</strong></summary>

| Template | Purpose |
|----------|---------|
| Incident Response Playbook | Step-by-step IR procedures with owner and SLA |
| Incident Triage Checklist | Structured L1/L2 triage with escalation triggers |
| Log Source Onboarding Checklist | Track SIEM log source onboarding and validation |
| Malware Analysis Report | Static and dynamic analysis with IOCs and TTPs |
| Root Cause Analysis | 5-Why RCA with corrective action tracking |

</details>

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. **Fork** the repository
2. **Create a branch** — `git checkout -b feat/new-template`
3. **Add your template** — follow the existing data structure in `index.html`
4. **Test it** — open `index.html` locally and verify it works
5. **Submit a PR** with a description of what you added

### Ideas for contributions:
- New templates for existing domains
- New security domains (e.g. OT/ICS Security, Identity & Access Management)
- Improved sample data
- Dark/light theme toggle
- Search/filter functionality

---

## 📄 License

MIT License — free to use, modify, and distribute. See [LICENSE](LICENSE) for details.

---

## 👤 Author

**Jaswanth K L**
Cybersecurity professional passionate about making security operations more accessible.

- 🔗 LinkedIn: [linkedin.com/in/jaswanthkl](https://www.linkedin.com/in/jaswanth-cybersec)
- 💻 GitHub: [github.com/jaswanthkl](https://github.com/jaswanthkl)

---

## ⭐ If this helped you, please star the repo!

It helps others find it and encourages me to keep adding more templates.
