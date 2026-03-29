# DFIR: Digital Forensic & Incident Response (Dibishop E-Commerce) 🛡️

> **Final Grade: 90/100 | Awarded Most Valuable Participant (MVP)**
> 
> Investigating and mitigating security incidents on the **Dibishop** platform by leveraging **Wazuh SIEM & XDR** monitoring and manual **SSH-based Log Analysis**.

---

## 🔍 Investigation Methodology

### 1. Security Monitoring (Wazuh SIEM)
* **Real-time Detection:** Utilized Wazuh to identify a massive **Distributed SSH Brute Force** attack (1,600+ failed attempts).
* **FIM (File Integrity Monitoring):** Tracked unauthorized changes in critical system libraries (`/etc/ld.so.cache`) triggered by directory traversal activities.

### 2. Manual Forensic Analysis (via SSH)
* **Deep-Dive Investigation:** Performed manual log analysis through **SSH access** to verify Wazuh alerts and correlate system events.
* **Root Cause Identification:** Analyzed web and database logs to uncover insecure configurations (e.g., `PermitRootLogin`) and verbose logging that enabled information disclosure.

### 3. Risk Assessment & Mapping
* **Threat Taxonomy:** Mapped all adversary techniques to the **MITRE ATT&CK Framework**.
* **Prioritization:** Developed a **5x5 Risk Matrix** to categorize findings and provide actionable remediation strategies.

---

## 🛠️ Infrastructure & Stack
* **Target Environment:** Ubuntu Server (hosting Dibishop e-commerce platform).
* **Monitoring Tool:** Wazuh SIEM & XDR.
* **Access Method:** Secure Shell (SSH) for manual forensic & log analysis.
* **Frameworks:** MITRE ATT&CK.

---

## 📄 Documentation
For the detailed forensic report, including CLI log evidence, methodology, and hardening recommendations:

👉 **[View Full Technical Report (Google Drive)](https://docs.google.com/document/d/16_Q1EJru2qSAyPZuUXAOiE3srfFlf28K/edit?usp=sharing&ouid=115041731891512654248&rtpof=true&sd=true)**

---

## 👤 Author
**Satria Pamungkas**
*Cybersecurity Professional | MVP Bootcamp Batch 4*
