# FUTURE_CS_02
# Security Alert Monitoring & Incident Response (SOC)

## Internship Details
Intern Name: Rishika Joshi  
Internship Program: Cyber Security Internship – Future Interns  
Task: Security Alert Monitoring & Incident Response Simulation  
SIEM Tool Used: Splunk  
Environment: Windows  

#Project Overview
This project simulates real-world operations performed inside a Security Operations Center (SOC).
As a SOC analyst intern, security alerts were monitored, suspicious events were analyzed, and
incident response actions were simulated using a SIEM platform (Splunk).

Using simulated enterprise security logs, activities such as user logins, authentication failures,
network events, and malware alerts were analyzed to detect potential cyber threats and respond
to them just like a real SOC team working 24/7.


#Scope of Testing

# In-Scope
- Log ingestion into Splunk (SIEM)
- Monitoring security alerts
- Analysis of login activity, malware, and system events

# Out-of-Scope
- External domains (Google, GitHub, CDN links, social media)
- Third-party services

# Tools Used
- Splunk Enterprise (Free Trial) – SIEM log monitoring & search
- Sample SOC Logs (SOC_Task2_Sample_Logs)
- Windows Machine
- MS Word / PPT for documentation and reporting

# Methodology
1. Log ingestion into Splunk  
2. Log search and filtering  
3. Event review and field extraction  
4. Threat identification  
5. Incident response recommendation  

#Security Findings

# 1. Malware Alert
Severity: High  
Action: Isolate system and perform deep scan immediately  

Malware activity such as ransomware, rootkit, or trojan was detected in system logs,
indicating a serious security threat requiring immediate isolation and scanning.

# 2. Login Failed Events
Severity: Medium  
Action: Monitor user and enforce Multi-Factor Authentication (MFA)  

Multiple login failures were observed, indicating possible brute-force attacks or
unauthorized access attempts.

# 3. Successful Login
Severity: Low  
Action: No action – baseline monitoring only  

Normal login activity was observed and considered safe for baseline monitoring.


# Conclusion
This SOC internship simulation successfully demonstrated how SIEM-based security monitoring
helps detect threats early and supports cybersecurity defense operations.  
By analyzing logs and responding to alerts, this project reflects how real SOC teams protect
organizations from cyber attacks.

