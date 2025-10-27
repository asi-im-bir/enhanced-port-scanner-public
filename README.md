# 🛡️ Enhanced Python Port Scanner — Educational Demo (Public)

⚠️ **Ethics & Legal Notice**  
This repository is for **educational purposes only**. Demo materials are restricted to `localhost` or a supplied demo environment.  
Do **not** scan systems you do not own or do not have explicit written permission to test.

---

## 🎯 One-line Summary  
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

## 👩‍💻 From a Security Engineer’s Perspective — How I’d Use This Project

> As a future Security Engineer, this tool forms the foundation for several operational and compliance improvements.

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

## ⚙️ Future Enhancements
- Structured JSON/CSV output for SIEM or CMDB ingestion  
- RBAC and audit logging for governed scanning  
- Service banner fingerprinting (authorized only)  
- Automatic correlation with CVE databases  
- Auto-ticket generation and compliance dashboard

---

## 🔗 Related Project (Reference)
**GRC Config Auditor — Configuration Drift & Shadow IT Auditor**  
Companion GRC tool that reconciles the CMDB baseline with network reality (detects config drift, ghost assets, and shadow IT).  
It extends the port-scanner’s logic for GRC evidence generation aligned with ISO 27001 and NIS2.  
**Code available on request.**

---

## 📬 Contact & Access  
Full implementation available for authorized technical review or interviews.  
Contact: [github.com/asi-im-bir](https://github.com/asi-im-bir)

---

## 🪪 License  
MIT License © 2025 asi-im-bir  
