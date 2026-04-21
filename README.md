
# 👋 Hi, I'm Miracle Ejimma

### Security Analyst | Cloud Security (AWS) | Endpoint Protection | Detection Engineering | DevSecOps

---

## 🎯 About Me

I am a cybersecurity professional with a strong foundation in Security Operations, threat detection and incident response. I am specializing in Cloud Security Engineering and DevSecOps, with a focus on building and orchestrating automated and scalable systems that detect and neutralize threats in real time.

I have a unique edge with my background in medical laboratory science, I developed the core skills that drive my success in security operations. I analyzed thousands of patient samples where a single oversight could mean a wrong diagnosis, which trained me to catch anomalies others might miss and influences my precision in threat detection. I troubleshot complex diagnostic equipment failures which taught me methodical investigation techniques I now apply to incident response and vulnerability analysis. Also, my experience with Quality Management Systems (QMS), HIPAA-equivalent regulations, and laboratory accreditation standards gives me deep understanding of compliance frameworks like NIST Cybersecurity Framework and CIS Benchmarks.

---

### Professional Experience in Cybersecurity

**Security Analyst (Security Operations & Engineering)** *(Obiveri Limited: January 2025 - Present)*

- I perform daily continuous monitoring and analysis of network and system logs; triage and review 50+ daily security alerts logged to SIEM solution (Wazuh), filter out noise, reducing mean time to detect (MTTD) by 20%

- I build and fine-tune custom detection rules mapped to MITRE ATT&CK and have achieved automated threat detection and response in less than 30 seconds using SIEM/SOAR solutions, reducing mean time to respond (MTTR) by 30%.

- I engineer CSPM solutions using AWS Lambda and Config to automatically remediate cloud misconfigurations in seconds, ensuring continuous compliance with the required security posture.

- I Integrate security into CI/CD pipelines (GitHub Actions) through automated SAST, SCA, and container scanning, providing shift-left security.

- I participate in HyperCare security monitoring for IAM infrastructure ensuring that new identity deployments are secure and stable.

- I performed vulnerability assessments of company infrastructure using OpenVAS, Nmap, and Burp Suite, identified vulnerabilities and made recommendations to control identified risks which reduced attack surface by 15%

###  Certifications & Education

- **CompTIA Security+** (Issued: February 2026)
- **B.Sc. Medical Laboratory Sciences** - University of Nigeria, Nsukka (CGPA: 3.7)

---

##  Security Projects

### 1. [DevSecOps EKS CloudNative Platform](https://github.com/actualmira/DevSecOps-EKS-CloudNative-Platform) (In Progress)
**Threat Modelling | IaC Scanning | Kubernetes Hardening | Container Security | Supply Chain Security | Observability | Runtime Threat Detection**

A defense-in-depth security for cloud-native applications on AWS EKS covering threat modelling, IaC scanning, Kubernetes hardening, container security, supply chain security, observability, and runtime threat detection.

**What I'm Building**

- **Threat-Modelling**: A comprehensive threat modelling for AWS/EKS infrastructure, defines trust boundaries, identifies threats applicable to the system, there impact, severity, and likelihood using STRIDE and DREAD framework, and determines the suitable mitigations.
- **Kubernetes Security Hardening**
- **EKS Infrastructure with AWS Security Controls**
- **Secrets Management and Supply Chain Security**
- **Runtime Threat Detection and Automated Response**
- **Full-Stack Observability and Security Validation with Penetration Testing**

---

### 2.  [DevSecOps: Automated Security Scanning](https://github.com/actualmira/DevSecOps_Pipeline)
**GitHub Actions | SAST | SCA | Container Security (Trivy) | DAST**

An automated security testing pipeline demonstrating shift-left security principles by integrating comprehensive security scanning into the CI/CD workflow.

**What I Built:**
- **GitHub Actions Workflow**: Automated CI/CD pipeline triggering on code commits
- **SAST Implementation**: Snyk Code scanning for source code vulnerabilities
- **SCA Implementation**: Snyk software composition analysis for dependency vulnerabilities
- **Container Security**: Trivy scanning on Docker images and OS packages
- **DAST Implementation**: OWASP ZAP testing on deployed application for runtime vulnerabilities
- **Workflow Optimization**: Strategic path filtering and artifact management reducing unnecessary executions

---

### 3. [Cloud-Native Security Implementation](https://github.com/actualmira/cloud-security-implementation)
**AWS | Wazuh SIEM | SOAR | CSPM | Network Segmentation | Microsegmentation**

A multi-layered cloud security architecture demonstrating defense-in-depth principles with automated threat detection and response in AWS.

**What I Built:**
- **Network Segmentation**: VPC with public/private subnets across multiple availability zones for workload isolation and redundancy
- **Microsegmentation**: Security group restrictions limiting inter-instance communication to essential ports only, preventing lateral movement within the same subnet
- **IAM Security**: Least-privilege policies with role-based access controls preventing unauthorized access escalation
- **Centralized Monitoring**:Wazuh SIEM aggregating AWS CloudTrail (API audit logs), VPC Flow Logs (network traffic metadata), file integrity monitoring (FIM), and host-based security events for unified visibility
- **Custom Detection Rules**: 5+ MITRE ATT&CK-mapped rules detecting security group modifications, root account usage, and brute force attempts
- **SOAR Automation**: Wazuh Active Response achieving <60-second automated threat blocking through iptables integration
- **CSPM Implementation**: AWS Config + Lambda + EventBridge for continuous S3 compliance monitoring with automatic remediation preventing potential data exposure

---

### 4. [Security Incident Lifecycle: Malware Analysis, IR & Phishing Simulation](https://github.com/actualmira/Malware-Analysis-and-Phishing-Simulation)
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

**Phishing Simulation:**
- **Custom Phishing Infrastructure**: HTML/JavaScript credential harvesting page mimicking Microsoft login portal
- **Traffic Analysis**: Wireshark and NetworkMiner analysis of credential submission and network behavior
- **Attack Chain Documentation**: Complete phishing workflow from delivery through credential exfiltration

---

## Current Open Source Engagement

*Active Contribution Proposal*

Ubuntu Security Documentation: Integrating Snort and Fail2ban on Ubuntu 24.04 LTS 

I recently identified a significant documentation gap in Ubuntu's official security guides: the Snort and Fail2ban documentation hasn't been updated since 2010-2013 and the available documentation references Ubuntu versions that has reached end-of-life and with deprecated tools.

[Proposal Status: Issue #86 - Ubuntu Security Documentation](https://github.com/canonical/ubuntu-security-documentation/issues/86)

I proposed a comprehensive documentation on building a cost-effective and automated Intrusion Detection/Prevention System (IPS) by integrating Snort IDS with Fail2ban on Ubuntu 24.04 LTS. 

*Reference Implementation: [Linux Endpoint Security: Defense-in-Depth Implementation](https://github.com/actualmira/Linux-Endpoint-Security)*

A hands-on integration on Ubuntu 24.04 where I demonstrated <60 second detection-to-block response time. A complete defense-in-depth architecture with multiple security layers. 

---

## Technical Expertise

### Security Operations
```
SIEM Operations (Wazuh, Splunk) • SOAR Automation • Threat Detection & Analysis • Incident Response •  
Security Architecture Design • Intrusion Detection & Prevention (Snort, Suricata) • Threat Intelligence Correlation
Detection Engineering• Endpoint Detection and Response • Root Cause Analysis

```

### Cloud Security
```
- Identity & Access Management: AWS IAM • IRSA • OIDC

- Network & Perimeter Security: VPC • Network Segmentation • Microsegmentation • WAF • AWS Shield

- CSPM: AWS Config • EventBridge • Lambda • AWS Security Hub

- Detection & Logging: AWS GuardDuty • CloudTrail • VPC Flow Logs • CloudWatch

- Data & Storage Security• S3 Object Lock • Bucket Policies • AWS KMS • Access Control

- Compute & Orchestration: EKS • Amazon ECR

```
### DevSecOps & Automation
```
- Container Security: Docker • Trivy • Snyk (SAST, SCA)

- Infrastructure & Policy as Code: CI/CD (Github Actions) • OPA Gatekeeper • Hadolint • Checkov • kube-linter • kubeconform

- Software Supply Chain Security: Trufflehog • GitLeaks • Co-sign • Syft • Amazon ECR

- Kubernetes Runtime & Observability: K8s PSS • Falco • Falco Sidekick • K8s NetworkPolicies • RBAC • LGTM (Loki, Grafana, Prometheus, Promtail)

- Secrets & Identity Management: HashiCorp Vault • ESO • IRSA • OIDC • KMS

```

### Security Frameworks & Compliance
```
MITRE ATT&CK • NIST Cybersecurity Framework •  CIS Benchmarks • HIPAA
CVE/CWE Standards • NIST SP 800-61 • PCI DSS  • ISO 27001 • OWASP Top 10

```

### Scripting & Programming
```
Rego • Python • Bash • YAML • HCL

```
---

## 🤝 Let's Connect

I'm actively seeking opportunities in Cloud Security Engineering, DevSecOps, and Threat Detection Engineering

**💼 LinkedIn**: [My LinkedIn Profile URL](https://linkedin.com/in/miracle-ejimma-46b21628a)   
**📍 Location**: Enugu, Nigeria

