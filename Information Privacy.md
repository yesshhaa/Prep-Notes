# Intellectual Property & Types of Confidential Information — Study Notes

## 1. Information Assets
- **Information asset** = information/data of value (e.g., patient records, customer info, IP).
- Can exist **physically** (paper, disks) or **electronically** (databases, files).

### Data → Information → Insights
| Term | Definition | Example |
|---|---|---|
| **Data** | Raw values/facts, usually collected by automated systems | Page visits, link clicks, monthly sales |
| **Information** | Summary of raw data | Positive/negative results after a change |
| **Insights** | Conclusions drawn from analyzed information; drive business decisions | Store maintains new hours after a positive trend follows the change |

**Data analytics** = turning raw data into meaningful information.

## 2. Intellectual Property (IP)
- Creations of the mind — generally **not tangible**.
- Protected by **copyright, trademark, and patent law**.
- Examples: industrial designs, trade secrets, research discoveries, even certain employee knowledge.
- **NDA (Non-Disclosure Agreement)** = legally binding document preventing sharing of sensitive information.

### Digital Products
- Non-tangible company assets: software, online music/courses, e-books/audiobooks, web themes (WordPress, Shopify).
- Must be protected from **piracy and reverse engineering**; source code, licenses, and activation keys need protection from hackers and insider threats.
- **DRM (Digital Rights Management)** — code added to files to prevent copying/piracy (though some tools can remove it).
- **DMCA (Digital Millennium Copyright Act)** — makes it illegal to bypass copy protections, or to build tech that helps bypass them.

## 3. Data-Driven Business Decisions
Good data → better response to real events (sales/marketing trends, production/fulfillment issues, etc.).

- **Data capture** — collecting data from multiple sources & storing it securely (relational databases or, more commonly, semi-structured data warehouses). Sources include:
  - Server logs (customer browsing)
  - IoT sensors (appliances, business tech)
  - Customer/employee surveys
  - Rating systems
- **Data correlation** — analyzing raw data points to find connections/links (e.g., Netflix comparing searches/views/ratings to predict hit shows). AI/ML automates parts of this.
- **Meaningful reporting** — presenting analyzed data (charts, keyword searches, graphs) to support further analysis/insights.

## 4. Confidential Information
Information employees must keep secret; companies rank info by sensitivity (ranking varies by company). **Four universal types:**

| Type | Definition | Examples |
|---|---|---|
| **PII** (Personally Identifiable Information) | Identifies a specific person | Gov't ID numbers, birthdates, addresses, phone numbers |
| **Company Confidential** | Info used to run the company | IP, product designs, procedures, plans, employee records, financial data |
| **Customer Confidential Information** | Info customers/partners provide | Includes PII + purchase history, credit card info |
| **PHI** (Protected Health Information) | Health-related identifying info from diagnosis/treatment | PII + medical history, prescription lists, photos, etc. |

### Careless Handling (examples)
- Entering credit card info into an unencrypted database.
- Leaving a patient's medical file unattended at the front desk.
- Letting a coworker borrow your password to download files.

### Proper Handling
- Restrict access to only those who need it.
- Prevent unauthorized views/copies.
- Store securely: encryption, firewalls, permissions.
- **Destroy** unneeded file copies (not just discard).
- Get **explicit consent** before processing/storing data, including how long it will be retained.
- Require strong passwords — not written down/shared, changed regularly.

## 5. PII vs. PCI vs. SPI
Often used interchangeably in non-legal contexts, but technically distinct:

| Term | Meaning |
|---|---|
| **PII** — Personally Identifiable Information | Identifies a person |
| **PCI** — Personal Customer Information | Identifies/describes a *customer*: name, address, contact info, account login, demographics, age, gender, job title, marital status |
| **SPI** — Sensitive Personal Information | Does **not** identify a person, but can cause harm if made public |

## Quick Recap
- Data → Information → Insights → business decisions.
- IP = creations of the mind, protected by copyright/trademark/patent + NDAs.
- DRM protects digital products; DMCA makes bypassing copy protection illegal.
- 4 universal types of confidential info: **PII, Company Confidential, Customer Confidential, PHI**.
- **PII** identifies, **PCI** describes a customer, **SPI** doesn't identify but can still cause harm if leaked.
