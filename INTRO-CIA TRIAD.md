# CIA Triad — Study Notes

A comprehensive security program must contain **Confidentiality, Integrity, and Availability** — the **CIA Triad**.

## 1. Confidentiality
Data is protected from **unauthorized access**.

- **Why it matters:** exposed confidential data leads to identity theft, compromised accounts/systems, legal issues, reputational damage.
- **Questions to determine if data should be confidential:**
  - Who is authorized to access it?
  - Do confidentiality regulations apply?
  - Are there conditions for when data can be accessed?
  - What would the impact of disclosure be?
  - Is the data valuable?
- **Protection tools:** control data access, encryption, multifactor authentication (MFA).

## 2. Integrity
Data is protected from **unauthorized changes** — guarantees data is **accurate, complete, and consistent**, across storage, processing, and transit.

- Data is not static — it's transferred, altered, and updated across systems, so integrity must be maintained continuously.
- Without integrity: loss, corruption, or compromise → damage/financial loss for businesses and customers.

**Two types of data integrity:**
| Type | Description |
|---|---|
| Physical | Actions/failsafes protecting the physical systems that store & process data |
| Logical | Checks/protocols protecting data from human error and hackers |

- Unauthorized alteration threatens: financial records, vote totals, health records, news stories, etc.

**Tools to fight unauthorized alteration:**
- **File Integrity Monitoring (FIM)** — audits sensitive files/folders to ensure all activity is authorized.
- **RDBMS (Relational Database Management System)** — records user access and data changes; safer than a spreadsheet.

**To preserve integrity, security plans must:**
1. Prevent unauthorized user access.
2. Prevent unauthorized data changes by *authorized* users.
3. Use error checking and data validation.

## 3. Availability
Authorized users have **immediate and reliable access** to their data whenever needed (e.g., passwords, security questions for access control).

**Threats:**
- **Non-malicious:** hardware failures, unscheduled software downtime, network bandwidth issues.
- **Malicious:** sabotage intended to deny access — e.g., **DoS attacks** (flooding a server with traffic until it can't respond).

**Protections for high-availability systems (99.999% uptime):**
- Network monitoring
- Redundant hardware
- Backup servers ready to take over if the primary system is compromised (maintains business continuity & customer access)

## 4. Regulatory Standards
Companies must follow regulations, contracts, and local laws to secure/maintain data.

| Regulation | Scope |
|---|---|
| **HIPAA** (Health Insurance Portability and Accountability Act) | Regulates use/disclosure of protected health information — U.S. |
| **GDPR** (General Data Protection Regulation) | Regulates digital privacy — applies across EU countries |

- Non-compliance or repeated violations → fines and penalties, which push companies to keep data safe, secure, accurate, and private.

## Quick Recap
- **CIA Triad** = Confidentiality + Integrity + Availability.
- Breaches/data loss → financial losses for consumers *and* companies.
- Integrity requires preventing unauthorized access **and** unauthorized changes.
- **HIPAA** = health data (U.S.); **GDPR** = digital privacy (EU).
- Non-compliance = hefty fines/penalties.
