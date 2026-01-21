# 🔐 Network Security Monitoring Project

## 📌 Project Overview
This project demonstrates hands-on experience in **Network Security Monitoring (NSM)** using open-source tools to detect, analyze, and investigate malicious network activity.  
The goal is to simulate a **SOC analyst workflow** and produce actionable security findings.

---

## 🎯 Objectives
- Monitor network traffic for suspicious activity
- Detect reconnaissance and malicious connections
- Analyze logs and correlate security events
- Create incident-ready documentation

---

## 🛠 Tools & Technologies
- Zeek (Network traffic analysis)
- Suricata (Network IDS)
- Wireshark (Packet analysis)
- Sysmon (Endpoint telemetry)
- Kali Linux (Attack simulation)
- Windows 10 (Victim machine)

---

## 🧪 Lab Environment
- Attacker: Kali Linux (VM)
- Victim: Windows 10
- Network Mode: Bridged / Internal Network
- Traffic Types:
  - Port scanning (Nmap)
  - HTTP requests
  - Suspicious outbound connections

---

## 🔍 Detection & Analysis
### Example Alerts & Logs
- Zeek `conn.log` – connection behavior analysis
- Suricata alerts – IDS signatures triggered
- Sysmon Event ID 3 – network connection telemetry

---

## 🧾 Findings
| Detection | Tool | Evidence |
|--------|------|---------|
| Port scan detected | Zeek | conn.log |
| Suspicious outbound HTTP | Sysmon | Event ID 3 |
| IDS alert triggered | Suricata | alert.log |

---

## 📊 Screenshots & Evidence
Screenshots showing:
- Alerts triggered
- Log analysis
- Traffic visualization

📂 Evidence stored in `/screenshots` and `/logs`

---

## 🚨 Incident Summary
- **Threat Type:** Network Reconnaissance
- **Severity:** Medium
- **MITRE ATT&CK:** TA0043 – Reconnaissance
- **Recommendation:** Block attacker IP, enable IDS alerting, continuous monitoring

---

## 📚 Skills Demonstrated
- Network traffic analysis
- Log correlation
- Incident investigation
- SOC documentation
- MITRE ATT&CK mapping

---

## ✅ Project Status
✔ Completed  
📅 Date: 2025

---

## 🔗 References
- MITRE ATT&CK
- Zeek Documentation
- Suricata Rules

