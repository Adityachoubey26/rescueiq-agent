# 🚨 RescueIQ - Disaster Intelligence Agent

Built for **Fetch-A-Thon 3.0** (October 2026).

RescueIQ is an autonomous disaster-intelligence agent powered by the **Fetch.ai uAgents Framework** and compatible with the **Agent Chat Protocol (ACP)** for integration with **ASI:One**.

---

## 📂 Project Structure

```
rescueiq-agent/
├── agent.py          # Main uAgent setup and ACP chat handlers
├── tools.py          # Real-world data tools (GDACS, Open-Meteo, Wikipedia)
├── requirements.txt  # Pinned dependencies
├── .gitignore        # Excludes venv, secrets, and caches
└── README.md         # Project documentation and quickstart
```

---

## 🛠️ Setup & Installation

### 1. Prerequisites
- Python 3.10+ (Current: Python 3.11.5)
- PowerShell (Windows) or Terminal

### 2. Virtual Environment Setup
A dedicated virtual environment `venv` is configured in this repository.

To activate on Windows PowerShell:
```powershell
.\venv\Scripts\Activate.ps1
```
*(Alternatively, execute python scripts directly using `.\venv\Scripts\python.exe` without altering PowerShell execution policies).*

### 3. Dependencies
Install required packages:
```powershell
.\venv\Scripts\pip.exe install -r requirements.txt
```

---

## 🚀 Status
- [x] Environment & Package Verification (uagents 0.26.1, uagents-core 0.4.12)
- [x] Agent Chat Protocol (ACP) Import Verification
- [x] Minimal Project Skeleton
- [ ] Real-time Data Retrieval Tools (tools.py)
- [ ] Agent Chat Handler & ASI LLM Synthesis (agent.py)
- [ ] Agentverse Registration & ASI:One Testing
