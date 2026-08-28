
# 👋 Hi, I'm Miracle Ejimma

### Cloud Security and DevSecOps Engineer (AWS) | Identity and Access Management | Infrastructure and Runtime Environment Security | Detection Engineering 

---

## About Me

I am a Cloud Security and DevSecOps Engineer with a focus on building and orchestrating automated and scalable systems that detect and neutralize threats in real time. My background in Security Operations gave me a strong foundation in threat detection and incident response, which I now apply at the infrastructure and platform level by designing systems that are secure by default.

I am skilled at implementing and securing infrastructure as code and CI/CD pipelines, enforcing identity and access management for users and services, deploying zero trust architecture with network and micro segmentation, secrets management, cloud security posture management, runtime threat detection with automated response, logging, observability, and security monitoring for visibility and audit. 


---

### Professional Experience in Cybersecurity

**Cloud Security and DevSecOps Engineer** *(Obiveri Limited: January 2026 - Present)*

- Enforced secure, consistent, and auditable infrastructure by managing all cloud resources through Terraform IaC and securing the CI/CD pipeline with automated scanning gates in GitHub Actions, preventing misconfigured infrastructure and vulnerable artifacts from reaching production.
  
- Secured microservices east-west traffic by deploying Linkerd service mesh with Vault PKI as the internal certificate authority and cert-manager as the certificate orchestrator, automating certificate issuance and renewal into Linkerd's control plane and providing mutual authentication across all service-to-service communication.
  
- Protected ingress traffic by deploying Envoy Gateway as the cluster ingress controller behind an AWS ALB, which enabled fine-grained L7 routing and secure traffic policy at the ingress layer.

- Managed users' authentication and authorization by deploying Keycloak as the central identity provider, configuring realms and clients to enforce consistent authentication policies as well as single sign-on across platform interfaces

- Eliminated credential sprawl and enforced least privilege permissions by implementing IRSA and OIDC federation, ensuring every workload and pipeline role uses short-lived tokens scoped to its exact permissions.

- Eliminated static credentials by deploying HashiCorp Vault with ESO as the secrets broker, enabling dynamic short-lived database credentials through the Vault Database Engine.

  
**Security Analyst (Security Operations & Engineering)** *(Obiveri Limited: January 2025 - January 2026)*

- I performed daily continuous monitoring and analysis of network and system logs; triaged and reviewied 50+ daily security alerts logged to SIEM solution (Wazuh), filtered out noise, reducing mean time to detect (MTTD) by 20%

- I built and fine-tuned custom detection rules mapped to MITRE ATT&CK and achieved automated threat detection and response in less than 30 seconds using SIEM/SOAR solutions, reducing mean time to respond (MTTR) by 30%.

- I engineered CSPM solutions using AWS Lambda and Config to automatically remediate cloud misconfigurations in seconds, ensuring continuous compliance with the required security posture.

- I Integrated security into CI/CD pipelines (GitHub Actions) through automated SAST, SCA, and container scanning, providing shift-left security.

- I participated in HyperCare security monitoring for IAM infrastructure ensuring that new identity deployments are secure and stable.

- I performed vulnerability assessments of company infrastructure using OpenVAS, Nmap, and Burp Suite, identified vulnerabilities and made recommendations to control identified risks which reduced attack surface by 15%


**Network Security Volunteer** *(Confidential IT Services Company: August 2023 - January 2025)*

- Collaborated with Security Analysts to run basic network audits, and prevented potential exploitation of vulnerabilities. 

- Assisted the network engineering team in configuring and provisioning enterprise Cisco switches and routers for network isolation and segmentation.

- Assisted the network security team in implementing ACLs and basic Port Security protocols to mitigate unauthorized access.


## Key Career Achievement

- Recipient of the Linux Foundation Training (LiFT) Scholarship 2026
  
## Certifications & Education

- **CompTIA Security+** (Issued: February 2026)
- **Certified Kubernetes Administrator (CKA)** (Scheduled: October, 2026)
- **B.Sc. Medical Laboratory Sciences** - University of Nigeria, Nsukka (CGPA: 3.7)

---

## Security Projects

### 1. [DevSecOps EKS CloudNative Platform](https://github.com/actualmira/DevSecOps-EKS-CloudNative-Platform) (In Progress)
**Threat Modelling | IaC Scanning | Kubernetes Hardening | Container Security | Supply Chain Security | Observability | Runtime Threat Detection**

A defense-in-depth security for cloud-native applications on AWS EKS covering threat modelling, IaC scanning, Kubernetes hardening, container security, supply chain security, observability, and runtime threat detection.

**What I Built**

- **Defence-in-Depth Architecture**: Full-stack security on AWS EKS from threat modelling and infrastructure hardening to runtime detection and automated cloud response
- **Zero Trust Networking**: Cilium default-deny network policies with FQDN-based egress filtering across every namespace, preventing lateral movement between workloads
- **Secrets Management and TLS**: HashiCorp Vault with ESO enforcing path-scoped least privilege, with cert-manager and trust-manager securing Vault-to-ESO communication over TLS
- **Runtime Threat Detection**: Falco with custom-tuned rules forwarding structured alerts to Loki through Falcosidekick, correlated with application logs in Grafana for real-time investigation
- **Cloud Security Posture Management**: GuardDuty finding remediation through EventBridge and Lambda, with AWS Config enforcing continuous compliance and auto-remediating misconfigurations in seconds
- **Node Patch Management and Admin Access**: SSM Patch Manager with scan-only weekly maintenance windows providing vulnerability visibility, and Session Manager as the only administrative access path with all session activity logged to Object-Locked S3 and CloudWatch
- **CI/CD Pipeline Security**: GitHub OIDC federation with separate least-privilege plan and apply roles per workflow file and branch, eliminating hardcoded credentials and preventing cross-workflow privilege escalation

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

### DevSecOps & Automation
```
- Container Security: Docker • Trivy • Snyk (SAST, SCA)

- Infrastructure & Policy as Code: CI/CD (Github Actions) • OPA Gatekeeper • Hadolint • Checkov • kube-linter • kubeconform • Terragrunt • ArgoCD

- Software Supply Chain Security: Trufflehog • GitLeaks • Co-sign • Syft • Amazon ECR

- Kubernetes Runtime & Observability: K8s PSS • Falco • Falco Sidekick • K8s NetworkPolicies • RBAC • LGTM (Loki, Grafana, Prometheus, Alloy)

- Secrets Management: HashiCorp Vault • ESO • KMS 

```

### Cloud Security
```
- Identity & Access Management: AWS IAM • IRSA • OIDC • Keycloak

- Network & Perimeter Security: VPC • Network Segmentation • Microsegmentation • WAF • Cilium CNI • Envoy Gateway • Linkerd • cert-manager • trust-manager 

- CSPM: AWS Config • EventBridge • Lambda • AWS Security Hub

- Detection & Logging: AWS GuardDuty • CloudTrail • VPC Flow Logs • CloudWatch

- Data & Storage Security• S3 Object Lock • Bucket Policies • AWS KMS • Access Control

- Compute & Orchestration: EKS • Amazon ECR


```

### Scripting & Programming
```
Rego • Python • Bash • YAML • HCL

```

### Security Operations
```
SIEM Operations (Wazuh, Splunk) • SOAR Automation • Threat Detection & Analysis • Incident Response •  
Security Architecture Design • Intrusion Detection & Prevention (Snort, Suricata) • Threat Intelligence Correlation
Detection Engineering• Endpoint Detection and Response • Root Cause Analysis

```

### Security Frameworks & Compliance
```
MITRE ATT&CK • NIST Cybersecurity Framework • CIS Benchmarks • HIPAA
CVE/CWE Standards • NIST SP 800-61 • PCI DSS • ISO 27001 • OWASP Top 10

```

---

## 🤝 Let's Connect

**💼 LinkedIn**: [My LinkedIn Profile URL](https://linkedin.com/in/miracle-ejimma-46b21628a)   
**📍 Location**: Enugu, Nigeria

