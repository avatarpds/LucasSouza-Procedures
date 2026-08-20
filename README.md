# LucasSouza-Procedures
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
| [Configure YubiKey](./02%20-%20Identidade%20e%20Acesso/Configurar%20YubiKey.docx) | FIDO2 · Hardware Token · Entra ID · Passwordless |
| [YubiKey Factory Reset](./02%20-%20Identidade%20e%20Acesso/Reset%20de%20F%C3%A1brica%20de%20YubiKey.docx) | FIDO2 · Troubleshooting · Token Recovery |
| [Passkey on Microsoft Authenticator](./02%20-%20Identidade%20e%20Acesso/Configurar%20Passkey%20no%20Microsoft%20Authenticator.docx) | Passkey · Entra ID · Passwordless · Authenticator App |
| [Configure MFA](./02%20-%20Identidade%20e%20Acesso/Configurar%20MFA.docx) | MFA · Entra ID · Microsoft Authenticator |

---

### 🖥️ Endpoint Management — Provisioning and Administration

Full endpoint lifecycle coverage: automated provisioning via Autopilot, Active Directory administration, cross-platform MDM with Jamf, and on-premises AD to Entra ID integration.

| Document | Technologies |
|---|---|
| [Windows Autopilot](./03%20-%20Infraestrutura%20e%20Ferramentas/Autopilot.docx) | Autopilot · Intune · Entra ID · PowerShell · Hardware Hash · Group Tag |
| [Workstation in AD via Shell](./03%20-%20Infraestrutura%20e%20Ferramentas/Movimentar%20Workstation%20no%20AD%20via%20Shell.docx) | PowerShell · Active Directory · OU · GPO · Entra ID |
| [Workstation in AD Manually](./03%20-%20Infraestrutura%20e%20Ferramentas/Movimentar%20Workstation%20no%20AD%20Manualmente.docx) | ADUC · Active Directory · OU · GPO |
| [Enroll Mac via Jamf](./03%20-%20Infraestrutura%20e%20Ferramentas/ingressar%20MAC%20via%20Jamf%202022.docx) | Jamf · macOS · MDM · Enrollment |

---

### ⚙️ Tools & Operations — Enterprise Tools and Processes

Operation of enterprise tools and ITSM process management. Demonstrates familiarity with the corporate support ecosystem beyond Microsoft technologies.

| Document | Technologies |
|---|---|
| [BeyondTrust / Bomgar](./03%20-%20Infraestrutura%20e%20Ferramentas/BeyondTrust%20-%20Bomgar%20-%20Acesso%20Remoto.docx) | BeyondTrust · Remote Support · Privileged Access |
| [Citrix Access Guide](./03%20-%20Infraestrutura%20e%20Ferramentas/Guia%20de%20acesso%20Citrix.docx) | Citrix · VDI · Desktop Virtualization |
| [M365 Password Reset — Admin](./02%20-%20Identidade%20e%20Acesso/Troca%20de%20Senha%20-%20Painel%20Admin%20Microsoft.docx) | Microsoft 365 · Admin Center · Identity Management |
| [Release Change in ServiceNow](./01%20-%20Gest%C3%A3o%20de%20Chamados/Guia%20-%20Release%20Change%20no%20ServiceNow.docx) | ServiceNow · ITSM · Change Management |

---

## Full structure

The repository contains **35 documents** organized across 4 domains. The 12 documents above are the strongest selection for technical demonstration purposes; the rest complements the full operational picture.

```
01 - Ticket Management        → Ticket creation, ITSM processes
02 - Identity & Access        → MFA, Passwordless, YubiKey, AD, M365
03 - Infrastructure & Tools   → Autopilot, Jamf, Citrix, BeyondTrust, AD
04 - Telephony & Finance      → Corporate line and invoice management
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
[linkedin.com/in/](https://linkedin.com/in/lucaspereirasou) · [github.com/](https://github.com/avatarpds/LucasSouza-Procedures)
