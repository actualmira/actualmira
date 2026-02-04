# 👋 Hi, I'm Miracle Ejimma

### Security Analyst | Detection Engineering | Cloud & Endpoint Security | DevSecOps 

---

## 🎯 About Me

I'm a Security Analyst with hands-on experience in **threat detection, incident response, and vulnerability management** across cloud and on-premises environments. I deploy and tune SIEM/SOAR platforms, conduct behavioral malware analysis, investigate security incidents, perform compliance audits, and implement security controls that enforce defense-in-depth principles.

**My Unique Edge:**  

My background in Medical Laboratory Science isn't just a career pivot, it's a **strategic advantage** that shapes how I approach cybersecurity:

- **Precision in Threat Detection**: Clinical laboratory work demands 99.9%+ accuracy. I apply the same rigor to security monitoring, minimizing false positives while ensuring no real threats slip through.

- **Systematic Root Cause Analysis**: Troubleshooting complex diagnostic equipment failures taught me methodical investigation techniques I now apply to incident response and vulnerability analysis.

- **Data Integrity as Core Principle**: Managing sensitive patient data with 99.9% accuracy and precision for 3 years translates directly into robust cybersecurity controls and meticulous audit trail management.

- **Regulatory Compliance Expertise**: Experience with Quality Management Systems (QMS), HIPAA-equivalent regulations, and laboratory accreditation standards gives me deep understanding of compliance frameworks like NIST, ISO 27001, and PCI DSS.

- **Chain of Custody Management**: Maintaining strict chain-of-custody procedures for clinical specimens directly translates to forensic analysis and security log management.

### Current Role

**Cybersecurity Analyst at Obiveri Limited** *(January 2025 - Present)*

I protect company infrastructure through threat detection, incident response, and vulnerability management. My daily work involves deploying and tuning SIEM/SOAR solutions to catch threats while minimizing false positives, investigating security incidents, and conducting vulnerability assessments to identify weaknesses. I implement CSPM, identity and access controls, and I integrate security scanning into CI/CD pipelines. I also contribute to security documentation including compliance reports and incident procedures, and deliver security awareness training to strengthen organizational security culture.


###  Certifications & Education

- **CompTIA Security+** (January 2026)
- **B.Sc. Medical Laboratory Sciences** - University of Nigeria, Nsukka (CGPA: 3.7)

---

## Current Work & Open Source Engagement
Active Contribution Proposal
Ubuntu Security Documentation - Integrating Snort and Fail2ban on Ubuntu 24.04 LTS 
I recently identified a significant documentation gap in Ubuntu's official security guides: the Snort and Fail2ban documentation hasn't been updated since 2010-2013 and the available documentation references Ubuntu versions that has reached end-of-life and with deprecated tools.

[Proposal Status: Issue #86 - Ubuntu Security Documentation](https://github.com/canonical/ubuntu-security-documentation/issues/86)

I proposed a comprehensive documentation on building a cost-effective and automated Intrusion Detection/Prevention System (IPS) by integrating Snort IDS with Fail2ban on Ubuntu 24.04 LTS. The guide will cover:

- Snort 2.9.20 installation and configuration on Ubuntu 24.04
- Custom detection rules for SSH brute force, port scanning, and ICMP attacks
- Fail2ban 1.0.2 integration with Snort alert logs
- Automated IP blocking via Fail2ban + UFW integration
- Testing and validation procedures (simulated attacks)
- Tuning detection thresholds for false positive reduction
- Extending detection with additional Cisco Talos rules

Reference Implementation: [Linux Endpoint Security: Defense-in-Depth Implementation](https://github.com/actualmira/Linux-Endpoint-Security)

A hands-on integration on Ubuntu 24.04 where I demonstrated <60 second detection-to-block response time. Complete defense-in-depth architecture with multiple security layers

Why This Matters:
This addresses the needs of resource-constrained organizations, educational institutions, and home labs that can't afford commercial IPS solutions but need enterprise-grade automated threat response.

## 🛡️ Technical Expertise

### Security Operations
```
SOC Operations • Threat Detection & Analysis • Incident Response • Alert Triage • Vulnerability Management
Security Monitoring • Log Analysis & Correlation • SIEM Operations • Intrusion Detection & Prevention 
SOAR Automation • Threat Hunting • IOC Extraction • Threat Intelligence Correlation & Validation
Behavioral Malware Analysis • Security Auditing • Endpoint Detection and Response • Root Cause Analysis
Security Architecture Design • Security Automation • Real-time Network Monitoring • Threat Pattern Recognition
Emerging Threats and Risk Analysis • Remediation Support • Security Controls Implementation
```

### Cloud & Infrastructure Security
```
AWS (VPC, IAM, GuardDuty, CloudWatch, CloudTrail, Lambda, S3, EventBridge, Config, Systems Manager)
Network Segmentation • Microsegmentation • Access Control • CSPM
Security Group Management • Defense-in-Depth Implementation
```

### Security Tools & Platforms
```
Wazuh (SIEM/XDR) • Snort IDS • Fail2Ban • Wireshark
NetworkMiner • Splunk • Microsoft Sentinel • CrowdStrike 
Sysinternals Suite (Process Monitor, Process Explorer, Autoruns)
OWASP ZAP • Snyk • Trivy • VirusTotal • AbuseIPDB • OpenVAS • Nmap • Burp Suite 
rkhunter • auditd • UFW Firewall • iptables • NGFWs • WAF
```

### DevSecOps & Automation
```
GitHub Actions (CI/CD) • Docker • Container Security
SAST (Static Application Security Testing)
SCA (Software Composition Analysis)
DAST (Dynamic Application Security Testing)
Shift-Left Security • Pipeline Integration
```

### Security Frameworks & Compliance
```
MITRE ATT&CK • NIST Cybersecurity Framework • HIPAA
PCI DSS • CIS Benchmarks • ISO 27001 • OWASP Top 10
NIST RMF • ISO 31000 • NIST SP 800-61 • CVE/CWE Standards
```

### Scripting & Programming
```
Python • Bash • PowerShell • XML • JSON
```
---

##  🛡️ Security Projects

### 1. [Cloud-Native Security Implementation](https://github.com/actualmira/cloud-security-implementation)
**AWS | Wazuh SIEM | SOAR | CSPM | Network Segmentation**

A multi-layered cloud security architecture demonstrating defense-in-depth principles with automated threat detection and response in AWS.

**What I Built:**
- **Network Segmentation**: VPC with public/private subnets across multiple availability zones for workload isolation and redundancy
- **Microsegmentation**: Security group restrictions limiting inter-instance communication to essential ports only, preventing lateral movement within the same subnet
- **IAM Security**: Least-privilege policies with role-based access controls preventing unauthorized access escalation
- **Centralized Monitoring**:Wazuh SIEM aggregating AWS CloudTrail (API audit logs), VPC Flow Logs (network traffic metadata), file integrity monitoring (FIM), and host-based security events for unified visibility
- **Custom Detection Rules**: 5+ MITRE ATT&CK-mapped rules detecting security group modifications, root account usage, and brute force attempts
- **SOAR Automation**: Wazuh Active Response achieving <60-second automated threat blocking via iptables integration
- **CSPM Implementation**: AWS Config + Lambda + EventBridge for continuous S3 compliance monitoring with automatic remediation preventing potential data exposure

**Key Metrics:**
- 📁 Real-time file integrity monitoring with instant modification detection
- ⚡ <60 seconds from threat detection to automated blocking (SOAR)
- ⚙️ <29 seconds from misconfiguration to automatic remediation (CSPM)
- 🎯 5+ custom MITRE ATT&CK-mapped detection rules
- 🔒 Zero SSH port exposure (bastion-less access via AWS Systems Manager)
- 🛡️ Microsegmentation enforcing least-privilege network access between instances


---

### 2 [Linux Endpoint Security: Defense-in-Depth Implementation](https://github.com/actualmira/Linux-Endpoint-Security)
**Ubuntu Server | Snort IDS | Fail2Ban | SSH Hardening | File Integrity Monitoring **

A progressive security hardening project demonstrating layered defense implementation on Ubuntu Server, starting from baseline configuration through enterprise-grade security controls.

**What I Built:**
- **Intrusion Detection**: Snort IDS with custom detection rules for nmap scans, SSH brute force, ICMP floods, and UDP scans
- **Automated Prevention**: Fail2Ban integration with UFW firewall for real-time IP blocking based on IDS alerts
- **SSH Hardening**: Key-only authentication, non-standard ports, root login disabled, max authentication attempts reduced from 6 to 3, session timeouts, and user restrictions
- **Firewall Configuration**: UFW with default-deny policy, rate limiting, protocol blocking, and comprehensive logging
- **File Integrity Monitoring**: auditd monitoring critical system files and file permission enforcement
- **System Hardening**: Password policy enforcement, disabled unused services to reduce attack surface, and strict file permissions
- **Rootkit Detection**: rkhunter for system binary verification and malware detection
- **Security Baseline**: Documented initial security posture for measuring improvement metrics

**Key Metrics:**
- ⚡ <60 seconds automated response time to detected attacks
- 🎯 100% detection rate against simulated attack patterns
- 🔐 Multi-layered defense preventing single point of failure
- 🔒 Attack surface reduced through service minimization and hardened configurations


---

### 3. [Security Incident Lifecycle: Malware Analysis, IR & Phishing Simulation](https://github.com/actualmira/Malware-Analysis-and-Phishing-Simulation)
**Behavioral Analysis | Threat Intelligence | IOC Extraction | Digital Forensics | Phishing Simulation**

A comprehensive security operations workflow demonstrating malware analysis, IOC extraction and correlation, incident response procedures, and an independent phishing simulation with credential harvesting assessment.

**What I Built:**

**Malware Analysis & Incident Response:**
- **Isolated Lab Environment**: VirtualBox-based malware analysis lab with network segmentation preventing malware escape
- **Behavioral Analysis**: Custom malware script execution with Sysinternals Suite (Process Monitor, Process Explorer, Autoruns) capturing system-level artifacts
- **Network Analysis**: Wireshark packet capture identifying C2 beacon patterns and domain communications
- **IOC Extraction**: File hashes (SHA-256), file creation/writing events, registry changes, process behaviors, and C2 domain indicators
- **Threat Intelligence Correlation**: IOC validation against VirusTotal
- **Incident Response Execution (NIST)**: Demonstrated containment, eradication/eradication verification, and recovery procedures.

**Phishing Simulation (Independent Assessment):**
- **Custom Phishing Infrastructure**: HTML/JavaScript credential harvesting page mimicking Microsoft login portal
- **Traffic Analysis**: Wireshark and NetworkMiner analysis of credential submission and network behavior
- **Attack Chain Documentation**: Complete phishing workflow from delivery through credential exfiltration

**Key Artifacts:**
- Complete IOC dataset (file hashes, registry keys, file creation events, C2 domains)
- Behavioral analysis reports with timeline correlation
- Phishing simulation demonstrating credential harvesting techniques


---

### 4.  [DevSecOps Security Pipeline](https://github.com/actualmira/DevSecOps_Pipeline)
**GitHub Actions | SAST | SCA | Container Security (Trivy) | DAST**

An automated security testing pipeline demonstrating shift-left security principles by integrating comprehensive security scanning into the CI/CD workflow.

**What I Built:**
- **GitHub Actions Workflow**: Automated CI/CD pipeline triggering on code commits
- **SAST Implementation**: Snyk Code scanning for source code vulnerabilities
- **SCA Implementation**: Snyk Open Source analyzing dependency vulnerabilities
- **Container Security**: Trivy scanning Docker images and OS packages
- **DAST Implementation**: OWASP ZAP testing deployed application for runtime vulnerabilities
- **Workflow Optimization**: Strategic path filtering and artifact management reducing unnecessary executions
- **Containerization**: Docker deployment with hardened node:20-alpine base image


**Key Metrics:**
- 🛡️ 4 security testing layers (SAST, SCA, Container, DAST)
- ⚡ Automated scanning on every code commit

---

## 🎯 What I'm Currently Working On
- Building expertise in threat detection engineering and defense-indepth architecture
- Advancing DevSecOps expertise through Secure Infrastructure as Code (IaC)
- Expanding cloud security expertise across AWS and Azure environments
- Exploring machine learning applications in threat detection and anomaly identification
- Pursuing advanced certifications: GSEC and CISSP
---

## 🤝 Let's Connect

I'm actively seeking opportunities in **SOC Operations, threat detection, vulnerability management, incident response, and security automation**.

**Open to:**
- Cybersecurity Analyst and Security Operations roles
- Security research collaborations
- Knowledge sharing with the cybersecurity community

**📧 Email**: ralzchrist@gmail.com  
**💼 LinkedIn**: [My LinkedIn Profile URL](https://linkedin.com/in/miracle-ejimma-46b21628a)   
**📍 Location**: Enugu, Nigeria

---
