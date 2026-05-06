# SOC Analyst Lab

## Project Overview

This project is a hands-on Security Operations Center lab designed to show skills in log analysis, alert review, threat detection, and incident response.

The goal of this lab is to practice real SOC analyst tasks that employers look for in cybersecurity candidates.

---

## Skills Demonstrated

- Security log analysis
- Suspicious login detection
- Brute-force attack investigation
- Incident documentation
- SIEM alert review
- Basic threat hunting
- Windows event log review
- Remediation recommendations

---

## Lab Tools

- Windows Server
- Windows Event Viewer
- Splunk or Microsoft Sentinel
- Kali Linux
- Nmap
- Wireshark
- VirtualBox or VMware
- PowerShell

---

## Lab Scenario

A Windows machine receives multiple failed login attempts from an unknown source. The goal is to identify the suspicious activity, review event logs, document the attack pattern, and recommend security controls.

---

## Investigation Steps

1. Reviewed Windows Security logs.
2. Identified repeated failed login attempts.
3. Checked source IP address.
4. Looked for successful login after failed attempts.
5. Documented possible brute-force activity.
6. Recommended account lockout policy and MFA.

---

## Sample Findings

| Finding | Severity | Recommendation |
|---|---|---|
| Multiple failed login attempts | High | Enable account lockout policy |
| Unknown login source | Medium | Review firewall and access logs |
| Weak authentication controls | High | Require MFA |

---

## Recommended Controls

- Enable Multi-Factor Authentication
- Use account lockout policies
- Monitor failed login attempts
- Configure SIEM alerts
- Review privileged accounts
- Apply least privilege access

---

## What I Learned

This lab helped me understand how SOC analysts review logs, detect suspicious behavior, document findings, and recommend security improvements.
