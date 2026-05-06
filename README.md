# cyber-attack-simulation-incident-response
Cybersecurity project simulating a large-scale cyber attack and incident response strategy
# 🔐 Cyber Attack Simulation & Incident Response

🚨 This project simulates a real-world multi-stage cyber attack on an organization, including phishing intrusion, malware propagation, and ransomware execution.

It demonstrates how attackers exploit vulnerabilities and how security teams detect, contain, and recover from such incidents using structured incident response strategies.

## ⏱ Attack Timeline

| Stage | Description |
|------|------------|
| Reconnaissance | Attacker gathers employee data |
| Initial Access | Phishing email sent |
| Execution | Malware installed |
| Lateral Movement | Spread across systems |
| Exfiltration | Sensitive data accessed |
| Impact | Ransomware encrypts files |

## 🔍 Key Findings

- Human error (phishing) is the primary entry point  
- Lack of monitoring allowed lateral movement  
- No early detection of abnormal traffic  
- Absence of strong access control increased impact

- ## 🚀 Future Scope

- Integrate SIEM tools like Splunk for real-time monitoring  
- Automate threat detection using Python scripts  
- Simulate advanced attacks (MITRE ATT&CK techniques)  
- Add alerting and dashboard systems

### 🔹 Log Analysis
Identified suspicious IP activity and ransomware behavior during analysis.

![Logs](screenshots/log_analysis.png)

## 🛡 Incident Response Strategy

- Identification: Detected abnormal traffic patterns  
- Containment: Isolated infected systems  
- Eradication: Removed malicious components  
- Recovery: Restored systems from backup
