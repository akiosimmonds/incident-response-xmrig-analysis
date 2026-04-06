# XMRig Incident Response Analysis

## Overview
This project documents the detection, investigation, and remediation of a cryptomining malware incident involving XMRig on a Windows Server 2019 system.

## Incident Summary
Users reported severe application slowdowns and timeouts affecting Pro-Engineer. Initial indicators suggested a potential system compromise due to abnormal performance and resource utilization. Investigation identified high CPU usage and suspicious outbound traffic on port 3333, which led to confirmation of XMRig cryptomining malware.

## Key Findings
- XMRig miner was identified on the impacted host
- High CPU utilization degraded system performance
- Outbound traffic on port 3333 indicated cryptomining activity
- Malware was removed and malicious traffic was blocked

## Actions Taken
- Reconfigured Windows Defender Antivirus policies
- Restarted the security service and ran a malware scan
- Removed the XMRig miner
- Added a firewall rule to block TCP/UDP traffic on port 3333
- Conducted follow-up validation to confirm remediation

## Lessons Learned
- Harden systems to reduce unauthorized software execution
- Configure SIEM alerts for suspicious outbound traffic and abnormal CPU usage
- Maintain regular patching and periodic security audits
- Strengthen user awareness and reporting of abnormal system behavior

## Skills Demonstrated
- Incident detection
- Malware investigation
- Log and traffic analysis
- Endpoint remediation
- Firewall-based containment
- Security reporting

## Artifact
See the `docs` folder for the full incident response report.

## Author
Akio Simmonds  
Senior Analyst | Cybersecurity | GRC
