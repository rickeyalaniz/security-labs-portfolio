
# Security Labs Portfolio

This repository serves as a central index for my hands-on cybersecurity labs. Each lab is documented in its own repository and focuses on **analyst reasoning, telemetry validation, and investigative decision-making**, not just tool output.

---

## SOC & Detection Labs

### [Lab 01 – Endpoint Telemetry Validation Using Sysmon and Microsoft Defender](https://github.com/rickeyalaniz/01-endpoint-telemetry-sysmon-defender)
**Focus:** Process creation telemetry, endpoint prevention behavior, and Sysmon visibility gaps  
**Tools:** Sysmon, Microsoft Defender, PowerShell, VirusTotal  

### [Lab 02 – Suspicious PowerShell Activity Using Sysmon](https://github.com/rickeyalaniz/02-suspicious-powershell-activity-using-sysmon)
**Focus:** PowerShell logging validation + suspicious execution patterns (encoded command, LOLBIN-like behavior)  
**Tools:** Sysmon, Windows Event Logs (PowerShell), Microsoft Defender, KQL (optional), Event Viewer  

### [Lab 03 – Windows Persistence Telemetry (Run Keys + Scheduled Tasks)](https://github.com/rickeyalaniz/03-persistence-runkeys-scheduledtasks)
**Focus:** Persistence simulation and telemetry validation across Sysmon (EID 1/13) and TaskScheduler Operational (EID 200/201)  
**Tools:** Sysmon, Task Scheduler Operational Logs, PowerShell, Event Viewer, `schtasks.exe`

---

## Upcoming Labs

- **Lab 04:** M365 Suspicious Sign-ins (KQL Investigation)  
- **Lab 05:** M365 Post-Compromise Investigation – Inbox Rule Abuse + OAuth Consent Persistence  

---

## About This Portfolio

These labs are built to reflect how a SOC analyst or detection focused role works in practice:

- Validates telemetry pipelines before trusting results  
- Investigates blocked vs. executed activity using evidence, not assumptions  
- Correlates artifacts across log sources (Sysmon, Windows event logs, and cloud identity telemetry)  
- Documents pivots, troubleshooting, and decision points in a reproducible way  

**Where I’m headed next:** expanding from endpoint visibility into Microsoft 365 investigation workflows, then into detection tuning and higher fidelity alert logic.
