# 🛡️ SOC L1 Incident Reports – Hands-On Blue Team Practice

This repository contains **realistic SOC Level-1 incident reports** created from hands-on investigations performed in a **production-style SOC lab environment**.

All reports are based on **real log evidence**, SIEM detections, and end-to-end incident handling — from alert triage to containment and recommendations.

This is not theory or CTF-only content.  
It reflects **how an L1 SOC analyst actually works in real environments**.

---

## 👤 About Me

**Aspiring SOC Analyst (L1)** with hands-on experience in:

- Alert triage and investigation  
- Log analysis across endpoint, network, and web layers  
- Evidence-based incident reporting  
- Operating and comparing multiple SIEM platforms  

I actively practice SOC workflows using **SIEM, EDR, IDS, and host telemetry**, simulating real enterprise incidents across **Windows, Linux, and web environments**.

---

## 🔍 What This Repository Demonstrates

- SOC Level-1 **alert investigation workflow**
- **True Positive vs False Positive** decision-making
- Web, endpoint, and network attack detection
- Correlation across **SIEM, EDR, IDS, and host logs**
- Clear **incident documentation** with timelines and evidence
- Mapping activity to **MITRE ATT&CK**
- Practical containment and remediation recommendations
- Exposure to **both Splunk and Microsoft Sentinel–based investigations**

---

## 📂 Incident Reports Included

### 🔹 Web Shell Upload & Command Execution
- Detection of malicious file upload via web application
- Identification of command execution through a web shell
- Correlation between:
  - Web server access logs
  - IDS (Suricata) alerts
  - Host-based audit logs
- Confirmed **True Positive**
- Containment actions:
  - Malicious file removal
  - Source IP blocking
  - Enhanced monitoring and validation

---

### 🔹 Real-World RDP Brute Force Attack
- High-volume RDP brute force detected via **Windows Security logs**
- **4,800+ failed login attempts** (Event ID 4625)
- Attacker IP reputation validated using threat intelligence
- No successful authentication observed
- Containment recommendations:
  - Firewall blocking
  - RDP exposure hardening
  - VPN-only access enforcement

---

## 🧠 Skills Demonstrated

### SOC & Detection
- Alert triage and prioritization
- Log analysis (Web, Windows, Linux, Authentication)
- IDS/IPS alert validation
- Incident severity assessment
- SIEM query interpretation and refinement

### Security Domains
- Web attacks (file upload abuse, command execution, directory fuzzing)
- Endpoint attacks (RDP brute force, suspicious process activity)
- Network-based detections
- Threat intelligence validation and enrichment

### Reporting & Analysis
- Executive-style incident summaries
- Evidence-driven investigation notes
- Clear conclusions and remediation steps
- SOC-style incident documentation aligned with the IR lifecycle

---

## 🛠️ Tools & Platforms Used

- **Microsoft Sentinel** (SIEM – KQL-based detections & investigations)
- **Splunk Enterprise** (SIEM – SPL-based analysis)
- **Wazuh** (EDR / HIDS)
- **Suricata** (IDS)
- Linux audit logs
- Windows Event Logs
- Web server logs (Apache)
- LetsDefend
- TryHackMe
- Custom SOC lab built using **cloud and on-prem style components**

---

## 🎯 Focus

This repository is maintained to:

- Build **job-ready SOC Level-1 skills**
- Practice real-world detection and response workflows
- Demonstrate **hands-on SIEM investigation capability**
- Create **portfolio-grade incident reports**
- Continuously improve investigation depth, accuracy, and reporting quality

New incident reports and investigations are added regularly as the lab evolves.

---

## 📬 Contact & Profiles

- **LinkedIn:** https://www.linkedin.com/in/analystshewag  
- **GitHub:** https://github.com/shewag-IR  

If you’re a SOC analyst, blue teamer, or recruiter — feel free to connect.