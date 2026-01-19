# Security Labs Portfolio

This repository serves as a central index for my hands-on cybersecurity labs.  
Each lab is documented in its own repository and focuses on **analyst reasoning, telemetry validation, and investigative decision-making** — not just tool output.

---

## SOC & Detection Labs

### [Lab 01 – Endpoint Telemetry Validation Using Sysmon and Microsoft Defender](https://github.com/rickeyalaniz/01-endpoint-telemetry-sysmon-defender)
**Focus:** Process creation telemetry, endpoint prevention behavior, and Sysmon visibility gaps  
**Tools:** Sysmon, Microsoft Defender, PowerShell, VirusTotal  

### [Lab 02 – Suspicious PowerShell Activity Using Sysmon](https://github.com/rickeyalaniz/02-suspicious-powershell-activity-using-sysmon)
**Focus:** PowerShell logging validation + suspicious execution patterns (encoded command, LOLBIN-like behavior)  
**Tools:** Sysmon, Windows Event Logs (PowerShell), Microsoft Defender, KQL (optional), Event Viewer  

---

## Upcoming Labs

- **Lab 03:** Detection Gaps in Script-Based Execution  
- **Lab 04:** Persistence Techniques and Telemetry Correlation  

---

## About This Portfolio

These labs are designed to reflect how a SOC analyst or detection engineer:

- Validates telemetry pipelines  
- Investigates blocked vs. executed activity  
- Correlates endpoint artifacts across log sources  
- Documents assumptions, pivots, and findings  
