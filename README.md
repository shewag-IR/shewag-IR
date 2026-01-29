# 🛡️ SOC L1 Incident Reports – Hands-On Blue Team Practice

This repository contains **realistic SOC Level-1 incident reports** created from hands-on investigations performed in a **production-style SOC lab environment**.

All reports are based on **real log evidence**, SIEM detections, and end-to-end incident handling — from alert triage to containment and recommendations.

This is not theory or CTF-only content.  
It reflects **how an L1 SOC analyst actually works**.

---

## 👤 About Me

**SOC Analyst (L1)** focused on:
- Alert triage
- Log analysis
- Web & endpoint attack detection
- Evidence-based incident reporting

I actively practice SOC workflows using **SIEM, EDR, and network telemetry**, simulating real enterprise incidents across Windows, Linux, and web environments.

---

## 🔍 What This Repository Demonstrates

- SOC Level-1 **alert investigation workflow**
- **True Positive vs False Positive** decision-making
- Web attack and endpoint attack detection
- Correlation across **SIEM, EDR, IDS, and host logs**
- Clear **incident documentation** with timelines and evidence
- Mapping activity to **MITRE ATT&CK**
- Practical containment and remediation recommendations

---

## 📂 Incident Reports Included

### 🔹 Web Shell Upload & Command Execution
- Detection of malicious file upload via web application
- Identification of command execution through web shell
- Correlation between:
  - Web server access logs
  - IDS alerts
  - Host-based audit logs
- Confirmed **true positive**
- Containment: file removal, IP blocking, monitoring

### 🔹 Real-World RDP Brute Force Attack
- High-volume RDP brute force detected via Windows Security logs
- **4,800+ failed login attempts** (Event ID 4625)
- Attacker IP reputation validated using threat intelligence
- No successful authentication observed
- Containment recommendations:
  - Firewall blocking
  - RDP exposure hardening
  - VPN-only access enforcement 1

---

## 🧠 Skills Demonstrated

### SOC & Detection
- Alert triage and escalation
- Log analysis (Web, Windows, Linux, Authentication)
- IDS/IPS alert validation
- Incident severity assessment

### Security Domains
- Web attacks (file upload abuse, command injection, directory fuzzing)
- Endpoint attacks (RDP brute force)
- Network-based detections
- Threat intelligence validation

### Reporting
- Executive summary writing
- Evidence-driven investigation notes
- Clear conclusions and remediation steps
- SOC-style incident documentation

---

## 🛠️ Tools & Platforms Used

- **Splunk Enterprise** (SIEM)
- **Wazuh** (EDR / HIDS)
- **Suricata** (IDS)
- Linux audit logs
- Windows Event Logs
- LetsDefend
- TryHackMe
- Custom SOC lab on **Google Cloud Platform (GCP)**

---

## 🎯 Focus

This repository is maintained to:
- Build **job-ready SOC Level-1 skills**
- Practice real detection and response workflows
- Create **portfolio-grade incident reports**
- Continuously improve investigation depth and reporting quality

New incidents and reports are added regularly.

---

## 📬 Contact & Profiles

- **LinkedIn:** https://www.linkedin.com/in/analystshewag  
- **GitHub:** https://github.com/shewag-IR  

If you’re a SOC analyst, blue teamer, or recruiter — feel free to connect.
