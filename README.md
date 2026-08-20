# IT Knowledge Base — Professional Portfolio

> Operational documentation developed and maintained in a multinational enterprise environment.  
> All documents have been sanitized: company names, usernames, internal URLs, and sensitive data have been removed or replaced with generic values.

---

## About this portfolio

This repository is a curated selection of technical procedures I developed, reviewed, and standardized throughout my work in corporate IT. The work goes beyond execution: it involves understanding the process, identifying gaps in existing documentation, reorganizing knowledge, and making it reproducible by anyone on the team.

Some documents were created from scratch. Others were originally written by other professionals and went through technical review, structural standardization, and content updates — which required understanding the process in order to improve it.

**I can perform virtually all of these procedures without consulting the documentation.** The documents exist so others can too.

---

## Areas of expertise

### 🔐 Identity & Access — Authentication and Identity

Focus on modern authentication methods, including the transition from traditional MFA to passwordless. The set of documents covers everything from initial setup to recovery and troubleshooting.

| Document | Technologies |
|---|---|
| [Configure YubiKey](./Identity%20%26%20Access/Configure%20YubiKey.docx) | FIDO2 · Hardware Token · Entra ID · Passwordless |
| [YubiKey Factory Reset](./Identity%20%26%20Access/YubiKey%20Factory%20Reset.docx) | FIDO2 · Troubleshooting · Token Recovery |
| [Configure Passkey on Microsoft Authenticator](./Identity%20%26%20Access/Configure%20Passkey%20on%20Microsoft%20Authenticator.docx) | Passkey · Entra ID · Passwordless · Authenticator App |
| [Configure MFA](./Identity%20%26%20Access/Configure%20MFA.docx) | MFA · Entra ID · Microsoft Authenticator |

---

### 🖥️ Endpoint Management — Provisioning and Administration

Full endpoint lifecycle coverage: automated provisioning via Autopilot, Active Directory administration, cross-platform MDM with Jamf, and on-premises AD to Entra ID integration.

| Document | Technologies |
|---|---|
| [Windows Autopilot](./Tools%20%26%20Operations/Autopilot.docx) | Autopilot · Intune · Entra ID · PowerShell · Hardware Hash · Group Tag |
| [Move Workstation in AD via Shell](./Tools%20%26%20Operations/Move%20Workstation%20in%20AD%20via%20Shell.docx) | PowerShell · Active Directory · OU · GPO · Entra ID |
| [Move Workstation in AD Manually](./Tools%20%26%20Operations/Move%20Workstation%20in%20AD%20Manually.docx) | ADUC · Active Directory · OU · GPO |
| [Enroll Mac via Jamf](./Tools%20%26%20Operations/Enroll%20Mac%20via%20Jamf.docx) | Jamf · macOS · MDM · Enrollment |

---

### ⚙️ Tools & Operations — Enterprise Tools and Processes

Operation of enterprise tools and ITSM process management. Demonstrates familiarity with the corporate support ecosystem beyond Microsoft technologies.

| Document | Technologies |
|---|---|
| [BeyondTrust - Bomgar - Remote Access](./Tools%20%26%20Operations/BeyondTrust%20-%20Bomgar%20-%20Remote%20Access.docx) | BeyondTrust · Remote Support · Privileged Access |
| [Citrix Access Guide](./Tools%20%26%20Operations/Citrix%20Access%20Guide.docx) | Citrix · VDI · Desktop Virtualization |
| [Password Reset - Microsoft Admin Panel](./Identity%20%26%20Access/Password%20Reset%20-%20Microsoft%20Admin%20Panel.docx) | Microsoft 365 · Admin Center · Identity Management |
| [Guide - Release Change in ServiceNow](./Ticket%20Management/Guide%20-%20Release%20Change%20in%20ServiceNow.docx) | ServiceNow · ITSM · Change Management |

---

## Full structure

The repository contains **35 documents** organized across 4 domains. The 12 documents above are the strongest selection for technical demonstration purposes; the rest complements the full operational picture.

```
Ticket Management     → Ticket creation, ITSM processes
Identity & Access     → MFA, Passwordless, YubiKey, AD, M365
Tools & Operations    → Autopilot, Jamf, Citrix, BeyondTrust, AD
Telephony & Finance   → Corporate line and invoice management
```

---

## Document standard

Each document follows this structure:

**Objective** → **Prerequisites** → **Responsibility** → **Step-by-Step** → **Version History**

The Version History records author, date, and a description of each revision — allowing anyone to trace who created and who updated each procedure over time.

---

## Sanitization note

All documents were sanitized prior to publication:

- Company name replaced with **Contoso**
- Internal URLs replaced with fictional equivalents (`portal.contoso.com`)
- Corporate email addresses anonymized (`user@contoso.com`)
- Employee names removed from screenshots via automated OCR redaction
- Credentials replaced with `[REDACTED]`

The technical content of the procedures — tools, configurations, workflows, and troubleshooting steps — has been fully preserved.

---

*Lucas Souza — IT Support | Endpoint & Identity Operations*  
[linkedin.com/in/lucassouza](https://linkedin.com/in/lucassouza) · [github.com/](https://github.com/)
