# Security Labs Portfolio

This repository is a central index for my hands on cybersecurity labs. Each lab is documented in its own repository and focuses on **analyst reasoning, telemetry validation, and investigative decision making**, not just tool output.

## Recruiter friendly summary

- Practical SOC style investigations with repeatable workflows and evidence
- Endpoint telemetry validation, Splunk based investigations, and Microsoft 365 investigations
- Clear artifacts: screenshots, logs, queries, and remediation validation steps
- Built to communicate how I think, triage, pivot, and confirm outcomes

---

## SOC and detection labs

### [Lab 01, Endpoint Telemetry Validation Using Sysmon and Microsoft Defender](https://github.com/rickeyalaniz/01-endpoint-telemetry-sysmon-defender)
**Focus:** Process creation telemetry, endpoint prevention behavior, and Sysmon visibility gaps  
**Tools:** Sysmon, Microsoft Defender, PowerShell, VirusTotal  

### [Lab 02, Suspicious PowerShell Activity Using Sysmon](https://github.com/rickeyalaniz/02-suspicious-powershell-activity-using-sysmon)
**Focus:** PowerShell logging validation and suspicious execution patterns, including encoded commands and LOLBIN style behavior  
**Tools:** Sysmon, Windows Event Logs (PowerShell), Microsoft Defender, Event Viewer, KQL (optional)  

### [Lab 03, Windows Persistence Telemetry, Run Keys and Scheduled Tasks](https://github.com/rickeyalaniz/03-persistence-runkeys-scheduledtasks)
**Focus:** Persistence simulation and telemetry validation across Sysmon Event IDs 1 and 13, and Task Scheduler Operational Event IDs 200 and 201  
**Tools:** Sysmon, Task Scheduler Operational Logs, PowerShell, Event Viewer, schtasks.exe  

### [Lab 04, M365 Suspicious Sign In Investigation](https://github.com/rickeyalaniz/04_m365_suspicious_sign_ins)
**Focus:** Identity based investigation of suspicious Microsoft Entra sign in activity, portal triage, session revocation, MFA remediation, and post remediation validation  
**Tools:** Microsoft Entra ID, Microsoft 365 Defender, Azure portal, Azure Monitor Logs (demo data), KQL  

### [Lab 05, M365 Post Compromise Investigation, Inbox Rule Abuse and OAuth Consent Persistence](https://github.com/rickeyalaniz/05_m365_inbox_rule_abuse_oauth_consent)
**Focus:** Simulated post compromise behavior using inbox rule abuse and OAuth consent persistence, validated evidence in Purview Audit and Entra audit logs, documented remediation and re validation workflow  
**Tools:** Microsoft Purview Audit (Unified Audit Log), Microsoft Entra ID, Outlook on the web, Exchange Online PowerShell (optional), KQL hunts (optional)  

### [Lab 06, M365 phishing email investigation, message trace, headers, and Defender hunting](https://github.com/rickeyalaniz/06_m365_phishing_email_investigation)
**Focus:** User reported phishing triage, Exchange Online message trace validation, header analysis (SPF, DKIM, DMARC), Microsoft 365 Defender hunting pivots (EmailEvents, EmailUrlInfo, EmailAttachmentInfo), containment by removing the message, and post action validation  
**Tools:** Exchange admin center (message trace), Outlook, Microsoft 365 Defender (Explorer and Advanced Hunting), KQL hunts, header analyzer  

### [Lab 07, Splunk investigation of suspicious PowerShell execution and supporting Defender telemetry](https://github.com/rickeyalaniz/07_splunk_c2_investigation)
**Focus:** Splunk based investigation using imported Windows log data to scope a host, validate source coverage, isolate PowerShell execution context, review supporting Defender Operational telemetry, and reconstruct a timeline around suspicious activity  
**Tools:** Splunk Enterprise, Windows Event Logs (PowerShell), Defender Operational logs, PowerShell, CSV log exports  

---

## Upcoming labs

- **Microsoft Sentinel build out:** create a dedicated lab tenant, enable Microsoft Sentinel, connect data sources, and validate ingestion
- **Detection tuning:** move from individual hunts into repeatable analytics rules, triage logic, and false positive reduction
- **Splunk data pipeline expansion:** add stronger process creation and network telemetry sources to improve investigation depth and correlation

---

## About this portfolio

These labs are built to reflect my thought process as a SOC analyst or detection focused role works in practice:

- Validate telemetry pipelines before trusting results  
- Investigate blocked versus executed activity using evidence, not assumptions  
- Correlate artifacts across log sources, including Sysmon, Windows event logs, Splunk, and cloud identity telemetry  
- Document pivots, troubleshooting notes, and decision points in a reproducible way  

## Where I am headed next

I am expanding from endpoint visibility into deeper Microsoft 365 investigation workflows, Splunk based investigations, then into Microsoft Sentinel ingestion and detection engineering, followed by higher fidelity alert logic and repeatable investigation playbooks.

---

## Links

- Portfolio index: https://github.com/rickeyalaniz/security-labs-portfolio
- LinkedIn: https://www.linkedin.com/in/rickeyalaniz/
- Resume: https://docs.google.com/document/d/1zcgUL5Wx0tnVi3GkyfFfSysvn1h4Ea9rH5zmqeKPUgQ/edit?usp=drive_link
