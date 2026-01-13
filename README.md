# 👋 Hi, I'm Ejimma Miracle Ngozi

### Cybersecurity Analyst | Threat Hunter | Security Operations Specialist


---

## 🎯 About Me

I'm a results-driven **Cybersecurity Analyst** with a unique background that combines rigorous scientific methodology from **Medical Laboratory Science** with hands-on **cybersecurity expertise**. This intersection gives me a distinctive edge in threat detection, data integrity enforcement, and systematic problem-solving.

###  What Makes Me Different?

My background in Medical Laboratory Science isn't just a career pivot, it's a **strategic advantage** that shapes how I approach cybersecurity:

- **Precision in Threat Detection**: Clinical laboratory work demands 99.9%+ accuracy. I apply the same rigor to security monitoring, minimizing false positives while ensuring no real threats slip through.

- **Systematic Root Cause Analysis**: Troubleshooting complex diagnostic equipment failures taught me methodical investigation techniques I now apply to incident response and vulnerability analysis.

- **Data Integrity as Core Principle**: Managing sensitive patient data with 99.9% accuracy and precision for 3 years translates directly into robust cybersecurity controls and meticulous audit trail management.

- **Regulatory Compliance Expertise**: Experience with Quality Management Systems (QMS), HIPAA-equivalent regulations, and laboratory accreditation standards gives me deep understanding of compliance frameworks like NIST, ISO 27001, and PCI DSS.

- **Chain of Custody Management**: Maintaining strict chain-of-custody procedures for clinical specimens directly translates to forensic analysis and security log management.

### Current Role

**Cybersecurity Analyst at Obiveri Limited** *(January 2025 - Present)*

I monitor network infrastructure and cloud environments using SIEM tools, conduct incident response investigations, perform security audits against NIST/ISO 27001 standards, and deploy IAM solutions with least-privilege access controls. My daily work includes infrastructure change reviews, HyperCare monitoring, and incident reviews to maintain security posture and operational continuity.

### 🎓 Certifications & Education

- **CompTIA Security+** (January 2026)
- **B.Sc. Medical Laboratory Sciences** - University of Nigeria, Nsukka (CGPA: 3.7)
- **Medical Laboratory Science Council of Nigeria (MLSCN)** - Annual License to Practice

---

## 🛡️ Technical Expertise

### Security Operations
```
Threat Detection & Analysis • Incident Response • Vulnerability Management
Security Monitoring • Log Analysis & Correlation • SIEM Operations
SOAR Automation • Threat Hunting • IOC Extraction & Validation
Malware Analysis (Behavioral) • Digital Forensics • Security Auditing
```

### Cloud & Infrastructure Security
```
AWS (VPC, IAM, CloudTrail, Lambda, S3, EventBridge, Config, Systems Manager)
Network Segmentation • Microsegmentation • Access Control • CSPM
Security Group Management • Defense-in-Depth Implementation
```

### Security Tools & Platforms
```
Wazuh (SIEM/XDR) • Snort IDS • Fail2Ban • Wireshark
Sysinternals Suite (Process Monitor, Process Explorer, Autoruns)
OWASP ZAP • Snyk • Trivy • VirusTotal • AlienVault OTX
AbuseIPDB • SET (Social Engineer Toolkit) • rkhunter
auditd • UFW Firewall • iptables
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
```

### Scripting & Programming
```
Python • Bash • PowerShell • XML • JSON
```

---

##  Featured Projects

### 1.  [Cloud-Native Security Architecture]
**AWS | Wazuh SIEM | SOAR | CSPM | Network Segmentation**

A comprehensive, multi-layered cloud security defense architecture demonstrating enterprise-grade security implementation in AWS.

**What I Built:**
- **Network Segmentation**: VPC with public/private subnets across multiple availability zones for fault tolerance
- **IAM Security**: Least-privilege policies preventing lateral movement and unauthorized access
- **Centralized Monitoring**: Wazuh SIEM aggregating AWS CloudTrail (API audit logs) and VPC Flow Logs (network traffic metadata)
- **Custom Detection Rules**: 5+ rules mapped to MITRE ATT&CK framework detecting security group modifications, root account usage, and brute force attempts
- **SOAR Automation**: Automated threat response achieving <60-second detection-to-blocking pipeline via iptables
- **CSPM Implementation**: AWS Config + Lambda + EventBridge for continuous S3 compliance monitoring with automatic remediation

**Key Metrics:**
- ⚡ <60 seconds from threat detection to automated response
- 🎯 5+ custom MITRE ATT&CK-mapped detection rules
- 🔒 Zero SSH port exposure (bastion-less access via AWS Systems Manager)

**Skills Demonstrated**: Cloud Security Architecture, SIEM/SOAR, Network Segmentation, Compliance Automation, Incident Response Automation

---

### 2 [Linux Endpoint Security: Defense-in-Depth]
**Ubuntu Server | Snort IDS | Fail2Ban | SSH Hardening | File Integrity Monitoring**

A progressive security hardening project demonstrating layered defense implementation on Ubuntu Server, starting from baseline configuration through enterprise-grade security controls.

**What I Built:**
- **Intrusion Detection**: Snort IDS with custom detection rules for nmap scans, SSH brute force, ICMP floods, and UDP scans
- **Automated Prevention**: Fail2Ban integration with UFW firewall for real-time IP blocking
- **SSH Hardening**: Key-only authentication, non-standard ports, session timeouts, user restrictions
- **Firewall Configuration**: UFW with default-deny policy, rate limiting, protocol blocking, and comprehensive logging
- **File Integrity Monitoring**: auditd monitoring critical system files for unauthorized changes
- **Rootkit Detection**: rkhunter for system binary verification
- **Security Baseline**: Documented initial security posture for measuring improvements

**Key Metrics:**
- ⚡ <60 seconds automated response time to detected attacks
- 🎯 100% detection rate against simulated attack patterns
- 🔐 Multi-layered defense preventing single point of failure

**Skills Demonstrated**: Linux System Hardening, IDS/IPS, Network Security, Access Control, Security Monitoring

---

### 3. [End-to-End Security Operations: Malware Analysis to Incident Response]
**Behavioral Analysis | Threat Intelligence | IOC Extraction | Digital Forensics**

A comprehensive security operations workflow demonstrating the complete journey from malware analysis through incident response, threat intelligence correlation, and social engineering assessment.

**What I Built:**
- **Isolated Lab Environment**: VirtualBox-based malware analysis lab with network segmentation preventing escape
- **Behavioral Analysis**: Custom malware script execution with Sysinternals Suite (Process Monitor, Process Explorer, Autoruns) capturing system-level artifacts
- **Network Analysis**: Wireshark packet capture identifying C2 beacon patterns and network signatures
- **IOC Extraction**: File hashes (SHA-256), registry modifications, process behaviors, network indicators (IPs, domains)
- **Threat Intelligence Validation**: IOC correlation against VirusTotal, AlienVault OTX, and AbuseIPDB
- **Phishing Simulation**: SET (Social Engineer Toolkit) campaign assessing detection capabilities
- **Incident Response Playbook**: Complete documentation from identification through recovery procedures

**Key Artifacts:**
- 📊 Complete IOC dataset (file hashes, registry keys, C2 infrastructure)
- 📝 Incident response playbook with step-by-step procedures
- 🔍 Behavioral analysis reports with timeline correlation

**Skills Demonstrated**: Malware Analysis, Digital Forensics, Threat Intelligence, OSINT, Incident Response, Social Engineering Assessment


---

### 4.  [DevSecOps Security Pipeline]
**GitHub Actions | SAST | SCA | Container Security | DAST**

An automated security testing pipeline demonstrating shift-left security principles by integrating comprehensive security scanning into the CI/CD workflow.

**What I Built:**
- **GitHub Actions Workflow**: Automated CI/CD pipeline triggering on code commits
- **SAST Implementation**: Snyk Code scanning for source code vulnerabilities
- **SCA Implementation**: Snyk Open Source analyzing dependency vulnerabilities
- **Container Security**: Trivy scanning Docker images and OS packages
- **DAST Implementation**: OWASP ZAP testing deployed application for runtime vulnerabilities
- **Workflow Optimization**: Strategic path filtering and artifact management reducing unnecessary executions
- **Containerization**: Docker deployment with hardened node:20-alpine base image

**Security Layers Tested:**
1. **Code Level** → SAST catches code vulnerabilities
2. **Dependency Level** → SCA identifies vulnerable libraries
3. **Container Level** → Trivy scans image and OS packages
4. **Runtime Level** → DAST tests deployed application

**Key Metrics:**
- 🛡️ 4 security testing layers (SAST, SCA, Container, DAST)
- ⚡ Automated scanning on every code commit
- 📦 Hardened Docker containers with minimal attack surface

**Skills Demonstrated**: DevSecOps, CI/CD Security, Container Security, Automated Security Testing, Shift-Left Security

---

## 🎯 What I'm Currently Working On

- ☁️ Building multi-cloud security monitoring (AWS, Azure, GCP)
- 🤖 Developing automated security orchestration playbooks
- 📚 Pursuing advanced certifications (CISSP, CEH)
---


## 🤝 Let's Connect

I'm always interested in:
- 🔐 Collaborating on security research projects
- 💼 Discussing cybersecurity career opportunities
- 🎓 Sharing knowledge with the security community
- 🤖 Exploring automation and security engineering

**📧 Email**: Ralzchrist@gmail.com  
**📍 Location**: Abuja, Nigeria

---


**⭐ If you find my projects useful, consider giving them a star!**

---

*Last Updated: January 2025*
