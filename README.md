# XMRig Incident Response Analysis

## Overview
This project documents a security incident involving XMRig cryptomining malware on a Windows Server 2019 system.

The objective of this analysis is to simulate a real-world incident response scenario by identifying indicators of compromise (IOCs), analyzing malicious activity, and implementing remediation actions to restore system integrity.

---

## Incident Summary
Users reported system performance degradation and abnormal behavior. Initial investigation revealed unusually high CPU usage and suspicious outbound network traffic.

Further analysis confirmed the presence of XMRig cryptomining malware, which was leveraging system resources for unauthorized mining activity.

---

## Detection & Analysis

The incident was identified through abnormal system behavior, including sustained high CPU utilization and unusual outbound network traffic.

### Indicators of Compromise (IOCs)
- XMRig cryptomining process detected on host system  
- Persistent high CPU usage impacting system performance  
- Outbound traffic over port 3333 associated with mining pools  
- Suspicious process execution and unauthorized resource usage  

### Analysis Performed
- Reviewed system performance metrics and process activity  
- Analyzed network traffic to identify suspicious outbound connections  
- Investigated process behavior consistent with cryptomining malware  
- Correlated findings with known XMRig indicators  

---

## Tools & Techniques
- Windows Defender Antivirus (malware detection and remediation)  
- System performance monitoring (CPU and process analysis)  
- Network traffic analysis (port and outbound connection review)  
- Log analysis concepts (event correlation and anomaly detection)  

---

## MITRE ATT&CK Mapping
- T1496 – Resource Hijacking (Cryptomining)  
- T1046 – Network Service Scanning (potential reconnaissance behavior)  
- T1059 – Command and Scripting Interpreter (possible execution methods)  

---

## Key Findings
- XMRig malware was actively consuming system resources  
- High CPU utilization degraded system performance  
- Outbound traffic on port 3333 indicated active cryptomining activity  
- Unauthorized process execution confirmed system compromise  

---

## Remediation Actions
- Removed XMRig malware from affected system  
- Blocked malicious outbound traffic associated with mining activity  
- Reconfigured Windows Defender Antivirus policies  
- Restarted affected services and validated system integrity  
- Conducted post-remediation monitoring to ensure no persistence mechanisms remained  

---

## Skills Demonstrated
- Incident Response & Threat Investigation  
- Malware Analysis (Cryptomining – XMRig)  
- Network Traffic Analysis  
- Indicator of Compromise (IOC) Identification  
- Threat Detection & Remediation  
- Security Monitoring & Analysis  
