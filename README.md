# Security Labs Portfolio

This repository serves as a central index for my hands-on cybersecurity labs. Each lab is documented in its own repository and focuses on **analyst reasoning, telemetry validation, and investigative decision making**, not just tool output.

---

## SOC & Detection Labs

### [Lab 01 – Endpoint Telemetry Validation Using Sysmon and Microsoft Defender](https://github.com/rickeyalaniz/01-endpoint-telemetry-sysmon-defender)
**Focus:** Process creation telemetry, endpoint prevention behavior, and Sysmon visibility gaps  
**Tools:** Sysmon, Microsoft Defender, PowerShell, VirusTotal  

### [Lab 02 – Suspicious PowerShell Activity Using Sysmon](https://github.com/rickeyalaniz/02-suspicious-powershell-activity-using-sysmon)
**Focus:** PowerShell logging validation and suspicious execution patterns, including encoded commands and LOLBIN style behavior  
**Tools:** Sysmon, Windows Event Logs (PowerShell), Microsoft Defender, Event Viewer, KQL (optional)  

### [Lab 03 – Windows Persistence Telemetry (Run Keys and Scheduled Tasks)](https://github.com/rickeyalaniz/03-persistence-runkeys-scheduledtasks)
**Focus:** Persistence simulation and telemetry validation across Sysmon Event IDs 1 and 13, and TaskScheduler Operational Event IDs 200 and 201  
**Tools:** Sysmon, Task Scheduler Operational Logs, PowerShell, Event Viewer, schtasks.exe  

### [Lab 04 – M365 Suspicious Sign in Investigation](https://github.com/rickeyalaniz/04_m365_suspicious_sign_ins)
**Focus:** Identity based investigation of suspicious Microsoft Entra sign in activity, portal triage, session revocation, MFA remediation, and post remediation validation  
**Tools:** Microsoft Entra ID, Microsoft 365 Defender, Azure Portal, Azure Monitor Logs (demo data), KQL  

---

## Upcoming Labs

- **Lab 05:** M365 Post Compromise Investigation, Inbox Rule Abuse and OAuth Consent Persistence  
- **Lab 06:** M365 Phishing Email Investigation  

---

## About This Portfolio

These labs are built to reflect how a SOC analyst or detection focused role works in practice:

- Validates telemetry pipelines before trusting results  
- Investigates blocked versus executed activity using evidence, not assumptions  
- Correlates artifacts across log sources, including Sysmon, Windows event logs, and cloud identity telemetry  
- Documents pivots, troubleshooting steps, and decision points in a reproducible way  

**Where I’m headed next:** expanding from endpoint visibility into Microsoft 365 investigation workflows, then into detection tuning and higher fidelity alert logic.
