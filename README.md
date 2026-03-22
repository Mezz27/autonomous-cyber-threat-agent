# 🛡️ Cyber Energy Threat Intelligence Agent

## 📌 Overview
An autonomous AI-powered agent that monitors, analyzes, and generates intelligence reports on cyber threats impacting energy infrastructure.

This system ingests real-world threat intelligence feeds (CVE, CISA KEV, and energy-sector news), applies AI-driven analysis, and produces structured **threat dossiers** for security teams and researchers.

---

## ⚡ Features

- 🔍 **Multi-source ingestion**
  - CVE feeds
  - CISA Known Exploited Vulnerabilities (KEV)
  - Energy sector cybersecurity news

- 🤖 **AI-powered classification**
  - Identifies threats relevant to energy infrastructure

- 📊 **Impact & severity scoring**
  - Rates threats on a 1–5 scale

- 🏭 **ICS/SCADA relevance detection**
  - Identifies risks to industrial control systems

- 💣 **Exploit intelligence**
  - Checks for known exploitation

- 🧠 **Threat memory & campaign detection**
  - Detects recurring patterns and campaigns

- ⚡ **Sector-specific impact analysis**
  - Differentiates IT vs energy infrastructure impact

- 🧭 **MITRE ATT&CK mapping**
  - Maps threats to known adversary techniques

- 📄 **Automated threat dossiers**
  - Generates structured intelligence reports

---

## 🧱 Architecture

```
Feeds → Classification → Impact Analysis → Risk Engine → Memory → Dossier
```

---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/cyber-energy-threat-agent.git
cd cyber-energy-threat-agent
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure environment variables

Create a `.env` file:

```env
OPENROUTER_API_KEY=your_api_key_here
```

### 4. Run the agent

```bash
python agent.py
```

---

## 📊 Example Output

```
CYBER ENERGY THREAT DOSSIER
===========================

CVE: CVE-2025-61726

Severity Score:
3/5

Confidence:
High

Exploit Available:
False

ICS Relevance:
False

Threat Assessment:
This vulnerability allows for denial-of-service attacks...

Potential Energy Sector Impact:
Limited direct impact expected on energy infrastructure.

MITRE ATT&CK Techniques:
- T0866 – Exploitation of Remote Services
```

---

## 🧠 Tech Stack

- Python 3.11+
- OpenAI / OpenRouter API
- Threat Intelligence Feeds (CVE, CISA KEV)
- MITRE ATT&CK Framework

---

## 🎯 Use Cases

- Security Operations Centers (SOC)
- Critical Infrastructure Monitoring
- Threat Intelligence Automation
- Cyber Risk Analysis
- Energy sector cybersecurity research

---

## 🔮 Future Improvements

- Real-time alerting (Slack, Email)
- Web dashboard UI
- Attack chain visualization
- SIEM integration
- Threat scoring optimization
- Historical analytics

---

## ⚠️ Disclaimer

This project is for educational and research purposes only. It does not guarantee complete threat detection or prevention.

---

## 👤 Author

Meenu Hani

---

## ⭐ Contributing

Contributions, issues, and feature requests are welcome!

---

## 📄 License & Copyright

© 2026 Meenu Hani. All rights reserved.
