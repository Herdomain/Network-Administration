# 🔍 Risk Management Plan — DHAEI Case Study

DHAEI is a growing software development and internet services company 
operating across multiple branch offices, hybrid cloud environments, and 
remote endpoints. This project applies the ISO 27001 Risk Management 
Framework to identify, assess, and treat the most critical security risks 
facing DHAEI's infrastructure and operations.

---

## Organization Overview

DHAEI is led by CEO **Alan Hake**, with operations managed across three 
executive functions:

- **Amanda Wilson (CIO)** — oversees IT infrastructure, security, and 
  systems management
- **Richard Xavier (COO)** — oversees networking, corporate security, 
  and helpdesk operations
- **Rachel Xieng (CFO)** — oversees financial operations and risk exposure

Security is managed under the CIO by **Paul Alexander (CISO)**, supported 
by one security technician (Harold Fry), one intern (Lewis Mableton), and 
one vacant technician position — a staffing gap that directly increases 
operational risk.

---

## Risk Environment

DHAEI's infrastructure introduces several compounding vulnerabilities:

- **Hybrid cloud workloads** across Rackspace and AWS with varied 
  security configurations
- **Distributed branch offices** each running RODCs with a single 
  support technician and limited oversight
- **20 remote programmers** connecting via L2TP VPN from home offices 
  on company-issued laptops
- **New Brampton branch office** temporarily storing user data on the 
  main file server FSI during transition — an elevated exposure window
- **One unfilled security technician position** reducing detection and 
  response capacity across the team

---

## Top Three Identified Risks

| Risk | CIA Impact | Likelihood (0–5) | Impact (0–10) |
|---|---|---|---|
| Unauthorized access via compromised VPN credentials | Confidentiality, Integrity | 4 | 8 |
| Data exposure during Brampton branch office transition | Confidentiality, Availability | 3 | 7 |
| Insider threat from privileged account misuse | Confidentiality, Integrity, Availability | 3 | 9 |

---

## Risk Ownership Chain

**Unauthorized VPN Access**
- Ground level: Harold Fry (Security Technician) — monitors authentication 
  logs and flags anomalies
- Mid level: Paul Alexander (CISO) — owns the security policy and response 
  protocol
- Executive level: Amanda Wilson (CIO) — accountable for infrastructure 
  security decisions and escalation to CEO

**Data Exposure During Branch Transition**
- Ground level: Branch support technician — monitors local data handling 
  during migration
- Mid level: William Freund (Manager, Systems) — oversees server 
  configuration and data movement
- Executive level: Richard Xavier (COO) — accountable for operational 
  continuity and risk to business operations

**Privileged Account Misuse**
- Ground level: Lewis Mableton (Intern) / Harold Fry — monitors access 
  logs for anomalous privileged activity
- Mid level: Paul Alexander (CISO) — enforces least privilege and 
  access control policies
- Executive level: Amanda Wilson (CIO) and Rachel Xieng (CFO) — 
  accountable for compliance and financial risk exposure

---

## Risk Treatment Recommendations

**Priority 1 — Unauthorized VPN Access**
Enforce MFA on all L2TP VPN connections for remote programmers. 
Implement continuous session monitoring and anomaly detection. 
Aligned with NIST SP 800-207 Zero Trust principles and 
ISO 27001 Access Control (Annex A.9).

**Priority 2 — Privileged Account Misuse**
Apply role-based access control (RBAC) scoped to job function. 
Conduct quarterly access reviews. Deploy user activity monitoring 
across privileged accounts. Aligned with CIS Controls v8 and 
ISO 27001 Annex A.9.

**Priority 3 — Data Exposure During Branch Transition**
Enforce full disk encryption on FSI during the transition period. 
Restrict access to Brampton user data to authorized personnel only. 
Implement a formal data migration checklist with sign-off requirements. 
Aligned with ISO 27001 Annex A.8 and NIST SP 800-111.

---

## Framework Alignment

| Framework | Application |
|---|---|
| ISO/IEC 27001:2022 | Risk assessment methodology, access control, asset management |
| NIST SP 800-207 | Zero Trust principles for remote access |
| CIS Controls v8 | Privileged access management, continuous monitoring |
| NIST SP 800-111 | Storage encryption for portable and transitional data |

---

## Artifacts & Outputs

- Risk Assessment Table (assets, threats, vulnerabilities, CIA impact)
- Risk Treatment Table with prioritized mitigations
- Statement of Applicability (SOA)
- Organizational risk ownership chain
- Executive summary written for non-technical leadership

> 📌 *Risk assessment tables and executive summary coming soon.*
