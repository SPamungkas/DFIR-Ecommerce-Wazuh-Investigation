# DFIR: E-Commerce Security Incident Investigation 🛡️

> **Final Grade: 90/100 | Awarded Most Valuable Participant (MVP)**
> 
> Investigating and mitigating real-world cyber attacks on a compromised infrastructure using **Wazuh SIEM & XDR**.

---

## 🔍 Investigation Highlights

### 1. Brute Force Analysis
* **Incident:** Detected a massive **Distributed SSH Brute Force** campaign.
* **Scale:** 1,600+ failed login attempts from multiple global source IPs.
* **Mitigation:** Implemented SSH hardening, disabled root login, and configured real-time alerting.

### 2. File Integrity Monitoring (FIM)
* **Incident:** Identified unauthorized modifications to critical system libraries (`/etc/ld.so.cache`).
* **Technical Root Cause:** Correlated with web directory traversal and fuzzing activities.
* **Outcome:** Successfully established a compromise timeline using Wazuh FIM logs.

### 3. Risk & Threat Mapping
* **Framework:** All findings mapped to the **MITRE ATT&CK Framework**.
* **Prioritization:** Used a **5x5 Risk Assessment Matrix** to determine business impact and remediation priority.

---

## 🛠️ Technical Stack
* **SIEM/XDR:** Wazuh
* **Platform:** Ubuntu Server
* **Methodology:** NIST Incident Response Lifecycle, Risk Management.

---

## 📄 Documentation
For the detailed forensic report, including log evidence, full methodology, and step-by-step remediation:

👉 **[View Full Technical Report (Google Drive)](https://docs.google.com/document/d/16_Q1EJru2qSAyPZuUXAOiE3srfFlf28K/edit?usp=sharing&ouid=115041731891512654248&rtpof=true&sd=true)**

---

## 👤 Author
**Satria Pamungkas**
*Cybersecurity Professional | MVP Bootcamp Batch 4*
