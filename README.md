# 🛡️ Enhanced Python Port Scanner — Educational Demo (Public)

⚠️ **Ethics & Legal Notice**  
This repository is for **educational purposes only**. Demo materials are restricted to `localhost` or a supplied demo environment.  
Do **not** scan systems you do not own or do not have explicit written permission to test.

---
## 🎯 Summary  
Small educational TCP port scanner (demo-only). Demonstrates socket programming, input validation, and safe-by-default design; public demo restricted to `127.0.0.1`.

![Educational demo — localhost only](demo.gif)

---

## 🧠 Project Overview  
This public repository intentionally contains **only demo assets and documentation** so reviewers can understand the project safely.  
The full implementation is available **on request** (private branch/repo for interviews).

### 🔧 What I Built
- Interactive TCP port scanner that probes ports and reports open services  
- Input validation for IPv4 addresses and port ranges  
- UTF-8 safe logging and clear, colorized terminal messages  
- A demo-mode design that restricts scans to `127.0.0.1` for safe public demonstration  
- Documentation and assets suitable for a professional security portfolio

### 💡 What I Learned
- TCP socket fundamentals (connect probes, timeouts, network exceptions)  
- Input validation and defensive programming for CLI tools  
- UTF-8 logging and safe output handling across systems  
- Ethical design and responsible demo configuration  
- How to document and communicate security projects for recruiters  
- Scan performance vs. detection tradeoffs  
- Cross-team awareness of safe testing practices

---

## ⚙️ Future Enhancements
- Structured JSON/CSV output for SIEM or CMDB ingestion  
- RBAC and audit logging for governed scanning  
- Service banner fingerprinting (authorized only)  
- Automatic correlation with CVE databases  
- Auto-ticket generation and compliance dashboard

---
## 👩‍💼  How I’d Operationalize This Project in the future

>This tool forms the foundation for several operational and compliance improvements.

| Security Objective | How I’d Apply It |
|---------------------|-----------------|
| **Asset Discovery & CMDB Accuracy** | Schedule internal scans to verify reachable ports and cross-check asset records |
| **Vulnerability Management** | Map discovered ports to services and CVEs for prioritized patching |
| **Detection & Monitoring** | Use authorized scan patterns to tune IDS/IPS and reduce false positives |
| **Incident Response** | Include scanner checks in triage playbooks for rapid exposure assessment |
| **Secure DevOps** | Add lightweight scan steps in staging to detect unexpected service exposure |
| **ISO 27001/NIS2 Evidence** | Treat scanner logs as auditable artifacts for A.8 (Asset Mgmt) and A.12 (Ops Security) |
| **Awareness & Training** | Use the demo to educate Dev/IT teams on exposure risk and remediation |

---
### 🔗 Related GRC Project — My Extended Work

**GRC Config Auditor — Configuration Drift & Shadow IT Auditor**  
This project extends my original scanner framework into a GRC automation tool that reconciles CMDB baselines with network reality.  
It detects configuration drift, ghost assets, and shadow IT, and produces audit-ready evidence mapped to ISO 27001 and NIS2 controls.  
Together, both projects form a continuous loop:  
**Discovery → Validation → Compliance → Governance.**

---

## 🧭 Project Evolution Map — From Technical Security to GRC Automation

> How my projects evolved from hands-on technical security to full GRC engineering alignment.

| **Phase** | **Project** | **Technical Focus** | **GRC / Security Engineering Outcome** |
|:--:|:--|:--|:--|
| **1** | 🧩 *Enhanced Port Scanner* | Core networking, socket programming, validation, logging, and safe demo execution. | Foundation for automated asset discovery and configuration verification. |
| **2** | ⚙️ *GRC Config Auditor* | CMDB reconciliation using `pandas`, drift analytics, and shadow IT detection. | Automated CMDB integrity checks and audit-ready ISO/NIS2 evidence. |
| **3** | 🧠 *GRC Engineering Framework* | Exception handling, risk scoring, evidence export, and dashboards. | Continuous monitoring and compliance automation foundation. |

---

### 🚀 Strategic Impact

- **Bridges SecOps and Governance:** Turns technical findings into measurable compliance evidence.  
- **Automates Trust:** Reduces manual audit prep through continuous verification.  
- **Builds Maturity:** Shows growth from tool-building → process automation → governance-integrated engineering.

---

### 📬 Contact & Controlled Access

Full implementations and demo environments are available for authorized technical review or audits.  
📎 [github.com/asi-im-bir](https://github.com/asi-im-bir)  
or contact via corporate email for private access.

---

### 🪪 License
MIT License © 2025 asi-im-bir

--- 
