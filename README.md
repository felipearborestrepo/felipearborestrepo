<h1 align="center">Hi, I'm Felipe Restrepo 👋</h1>
<h3 align="center">IT System Administrator / Engineer · Identity & Access Management · Cloud Security</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Okta-007DC1?style=for-the-badge&logo=okta&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
</p>

---

## 🎯 About Me

I'm an IT System Administrator/Engineer focused on **Identity & Access Management**, **cloud security**, and **automation**. This profile is a portfolio of hands-on labs and projects covering Okta, Microsoft Entra ID, PowerShell + Microsoft Graph automation, vulnerability management, threat hunting, and incident response.

---

## 🏅 Certifications

| Certification | Issuer | Status |
|---|---|---|
| Okta Certified Administrator | Okta | ✅ Earned |
| Okta Certified Professional | Okta | ✅ Earned |
| SC-300: Identity and Access Administrator Associate | Microsoft | ✅ Earned |
| AZ-104: Azure Administrator Associate | Microsoft | ✅ Earned |
| Security+ | CompTIA | ✅ Earned |
| AZ-900: Azure Fundamentals | Microsoft | ✅ Earned |
| SC-900: Security, Compliance & Identity Fundamentals | Microsoft | ✅ Earned |
| SC-500: Azure Cloud AI Security Engineer Associate | Microsoft | 🔄 In Progress |

---

## 🧰 Skills

| Area | Tools & Concepts |
|---|---|
| 🔐 **Identity & Access Management** | Okta · Microsoft Entra ID · Conditional Access · MFA · FIDO2/WebAuthn · SSO · SAML 2.0 · OIDC · Lifecycle Management (JML) · Provisioning/Deprovisioning · Access Reviews · PIM/PAM |
| ⚙️ **Automation, AI & Scripting** | PowerShell · Microsoft Graph API · Python · Microsoft Copilot · Claude Cowork · Process Automation |
| 💻 **Endpoint & Device Management** | Intune · Autopilot · Windows 11 · macOS · Compliance Policies · Endpoint Security · Patch Management · Software Deployment · BitLocker · Imaging & Deployment |
| 🏗️ **Infrastructure & Security** | Windows Server · Active Directory · DNS · DHCP · TCP/IP · VPN · Firewalls · Zscaler ZIA (Zero Trust/SASE) · Microsoft Sentinel (KQL) · Vulnerability Management · SOC 2 Awareness |
| 📋 **IT Service Management** | ITIL (Incident · Problem · Change · Request) · ServiceNow · CMDB · SLA & KPI Monitoring · Continual Service Improvement · Vendor & Contract Management |

---

## 📂 Projects

> Click a category to expand it.

<details open>
<summary><h3>🔑 Okta</h3></summary>

| Project | Focus |
|---|---|
| [Hybrid Identity Lab: Active Directory → Entra ID → Okta](#) | Hybrid identity, directory integration |
| [Okta + Salesforce SAML 2.0 Single Sign-On](#) | SSO, SAML 2.0 |
| [Okta SCIM 2.0 Provisioning Lab: Joiner, Mover, Leaver[([#](https://github.com/felipearborestrepo/Okta-SCIM-2.0-Provisioning-Lab---Joiner---Mover---Leaver/blob/main/README.md)) | SCIM, SAML 2.0, JML |

</details>

<details>
<summary><h3>🔄 Identity Lifecycle Automation (Microsoft Graph + PowerShell)</h3></summary>

| Project | Focus |
|---|---|
| [Automated User Onboarding](#) | Graph API, provisioning |
| [Automated Offboarding: Secure Account Termination](#) | Graph API, deprovisioning |
| [Entitlement Management: Governed Access Packages](#) | Entra ID Governance |
| [Dynamic Groups Auditor](#) | Membership rule validation |

</details>

<details>
<summary><h3>🏥 Entra ID Security Health Check (PowerShell)</h3></summary>

| Script | What It Does |
|---|---|
| [MFA Combined Report](#) | Reports MFA method type and registration age |
| [No-MFA Detector](#) | Finds users without MFA and remediates |
| [Stale User Finder](#) | Detects inactive accounts |
| [App Secret & Certificate Expiry Scanner](#) | Flags expiring credentials |
| [Admin Role Auditor](#) | Discovers privileged access |
| [Guest User Access Auditor](#) | Reviews external user access |
| [App Registration Ownership Auditor](#) | Finds ownerless or risky app registrations |

</details>

<details>
<summary><h3>🏢 Microsoft Entra ID & IAM Architecture</h3></summary>

**Conditional Access & Zero Trust**
- [Enterprise Conditional Access & Zero Trust Architecture](#)
- [Conditional Access & Zero Trust Enforcement Lab](#)
- [Conditional Access Policy Creation (MFA)](#)
- [Conditional Access: Enforcing MFA with PIM & Sign-In Log Validation](#)
- [Passwordless & Phishing-Resistant Authentication Architecture](#)

**Privileged Access**
- [Privileged Identity Management (PIM) & Just-In-Time Admin Access](#)
- [Break-Glass Emergency Administrator Accounts](#)

**Identity Governance**
- [Identity Governance & Access Reviews](#)
- [Identity Governance & Access Reviews Lab](#)
- [HR Onboarding Access Package](#)
- [Dynamic Group IAM Model: Automated Lifecycle Management (JML)](#)

**Hybrid Identity & Applications**
- [Hybrid Identity Lab: Active Directory → Entra ID Sync](#)
- [Hybrid IAM & Secure Application Access Architecture](#)
- [Enterprise Application & SSO Engineering Lab](#)
- [Entra ID IAM Foundation Lab](#)

**Active Directory**
- [Active Directory Domain Controller Lab (Azure)](#)
- [Active Directory Troubleshooting Lab](#)

</details>

<details>
<summary><h3>⚠️ Vulnerability Management (Tenable Nessus)</h3></summary>

**Program & Scanning**
- [Vulnerability Management Program Implementation](#)
- [Discovery Scan: Entire Subnet](#)
- [Unauthenticated vs Authenticated Scans: Windows](#)
- [Unauthenticated vs Authenticated Scans: Linux](#)
- [Nessus Agent Scan Implementation: Windows](#)
- [Nessus Agent Scan Implementation: Linux](#)
- [DISA STIG Template & Scan Execution](#)

**Remediation**
- [Programmatic Vulnerability Remediation (PowerShell & Bash)](#)
- [Programmatic Vulnerability Remediation: Windows 10](#)
- [Manual Vulnerability Creation & Remediation (Firefox / SMB)](#)
- [DISA STIG Remediation: WN10-SO-000100 SMB Packet Signing](#)

</details>

<details>
<summary><h3>🚨 Threat Hunting & Incident Response</h3></summary>

**Threat Hunting (Microsoft Defender, KQL)**
- [Unauthorized Tor Browser Usage](#)
- [Brute Force Investigation on Exposed Azure VMs](#)
- [Sudden Network Slowdowns (Simulated Attack)](#)
- [Data Exfiltration by a PIP'd Employee (Simulated)](#)

**Incident Response (Microsoft Sentinel, NIST 800-61)**
- [Brute Force Detection & Response](#)
- [PowerShell Suspicious Web Request](#)
- [Impossible Travel Alert](#)

**Network Analysis**
- [Wireshark + VirusTotal OSINT: Exfiltration (HawkEye)](#)

</details>

---

## 📫 Connect With Me

<p>
  <a href="[https://www.linkedin.com/in/YOUR-LINKEDIN](https://www.linkedin.com/in/felipe-restrepo-ab56a5318/?isSelfProfile=true)"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

## 🎥 My Youtube Channel 
  <a href="https://www.youtube.com/@feliperestrepocyber"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
</p>


