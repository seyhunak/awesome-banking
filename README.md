<div align="center">

# 🏦 Awesome Banking [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A curated, production-first guide to the banking domain — products, payments, security, compliance, architecture, AI, low-code/no-code, and mobile design.**

Conventional & Islamic · Retail & Corporate · from account opening to remittance.

<!-- Repository badges -->

[![GitHub stars](https://img.shields.io/github/stars/seyhunak/awesome-banking?style=for-the-badge&logo=github&color=FFD700)](https://github.com/seyhunak/awesome-banking/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/seyhunak/awesome-banking?style=for-the-badge&logo=github&color=8A2BE2)](https://github.com/seyhunak/awesome-banking/network/members)
[![GitHub watchers](https://img.shields.io/github/watchers/seyhunak/awesome-banking?style=for-the-badge&logo=github&color=00BFFF)](https://github.com/seyhunak/awesome-banking/watchers)
[![GitHub contributors](https://img.shields.io/github/contributors/seyhunak/awesome-banking?style=for-the-badge&logo=github&color=FF69B4)](https://github.com/seyhunak/awesome-banking/graphs/contributors)

[![Link Check](https://img.shields.io/github/actions/workflow/status/seyhunak/awesome-banking/link-check.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=links)](https://github.com/seyhunak/awesome-banking/actions/workflows/link-check.yml)
[![License: MIT](https://img.shields.io/github/license/seyhunak/awesome-banking?style=flat-square&color=green)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![Last commit](https://img.shields.io/github/last-commit/seyhunak/awesome-banking?style=flat-square&logo=git&logoColor=white)](https://github.com/seyhunak/awesome-banking/commits/main)
[![Commit activity](https://img.shields.io/github/commit-activity/m/seyhunak/awesome-banking?style=flat-square)](https://github.com/seyhunak/awesome-banking/pulse)
[![Issues](https://img.shields.io/github/issues/seyhunak/awesome-banking?style=flat-square&logo=github)](https://github.com/seyhunak/awesome-banking/issues)
[![Pull requests](https://img.shields.io/github/issues-pr/seyhunak/awesome-banking?style=flat-square&logo=github)](https://github.com/seyhunak/awesome-banking/pulls)
[![Repo size](https://img.shields.io/github/repo-size/seyhunak/awesome-banking?style=flat-square)](https://github.com/seyhunak/awesome-banking)
[![Code of Conduct](https://img.shields.io/badge/Code%20of%20Conduct-v2.1-blueviolet.svg?style=flat-square)](CODE_OF_CONDUCT.md)

<!-- Author badges -->

[![GitHub followers](https://img.shields.io/github/followers/seyhunak?style=social&label=Follow%20%40seyhunak)](https://github.com/seyhunak)
[![Website](https://img.shields.io/badge/Website-seyhunakyurek.com-000000?style=flat-square&logo=safari&logoColor=white)](https://seyhunakyurek.com)
[![Made with Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg?style=flat-square&logo=markdown)](https://commonmark.org)

</div>

---

## 📖 About

This list is opinionated and **production-first**. It is a working **domain knowledge guide** for anyone building, operating, selling, designing, or regulating banking software — product managers, engineers, architects, risk & compliance officers, designers, and founders.

Every section opens with a **domain primer** (the mental model you need), then lists the **tools, standards, and resources** that professionals actually use. Where a category has an obvious default, it is marked with ⭐.

**Legend:** ⭐ widely adopted default · 🔓 open source · 💰 commercial / paid tier · ☁️ managed service · 🆓 free

---

## 📑 Table of Contents

| | Knowledge & Design | | Products & Segments |
|---|---|---|---|
| 📚 | [Banking Fundamentals](#banking-fundamentals--domain-knowledge) | 💳 | [Accounts](#accounts) |
| 🛡️ | [Security](#security) | 🏦 | [Savings & Deposits](#savings--deposits) |
| ⚖️ | [Compliance & Regulation](#compliance--regulation) | 💳 | [Credit Cards](#credit-cards) |
| 🏗️ | [Banking Architecture](#banking-architecture) | 📝 | [Personal Loans](#personal-loans) |
| 📱 | [Mobile Banking Design](#mobile-banking-design) | 🏠 | [Mortgage](#mortgage) |
| 🧩 | [Low-Code & No-Code Tools](#low-code--no-code-tools) | 📈 | [Investment & Wealth](#investment--wealth) |
| 🤖 | [AI in Banking](#ai-in-banking) | 🧾 | [Insurance](#insurance) |
| 👥 | [Customers & Experience](#customers--experience) | 🌍 | [Trade Finance](#trade-finance) |
| 🪪 | [KYC & Customer Due Diligence](#kyc--customer-due-diligence) | 💸 | [Domestic & International Remittance](#domestic--international-remittance) |
| | | 👤 | [Personal Banking](#personal-banking) |
| | | 🏢 | [Corporate Banking](#corporate-banking) |
| | | 🕌 | [Conventional & Islamic Banking](#conventional--islamic-banking) |

🎓 [Learning, Courses & Community](#learning-courses--community)

[Contributing](#contributing) · [Author](#author) · [License](#license)

---

## Banking Fundamentals & Domain Knowledge

> Banking is a **balance-sheet business**: a bank takes deposits (its liabilities) and lends them out or invests them (its assets), earning the difference between what it pays for money and what it charges for it — the **net interest margin (NIM)** — plus fees. Everything in this list ultimately serves one of three jobs: **take deposits, make loans, move money.**

### Key concepts

- **The bank's book** — deposits, savings, and current accounts on the liability side; loans, mortgages, cards, and trade assets on the asset side.
- **Liquidity & solvency** — a bank must survive short-term withdrawals (liquidity, measured by LCR) and absorb long-term losses (solvency, measured by capital ratios like CET1 and NSFR).
- **Risk is the product** — credit risk, market risk, operational risk, and liquidity risk are not side effects; managing them *is* the business.
- **Money movement** — payments sit on rails (ACH, SEPA, SWIFT, RTGS, card networks); *clearing* is the processing in between, *settlement* is where funds become final.
- **Two operating models** — **conventional** banking (interest-based) and **Islamic** banking (Shariah-compliant, profit-and-loss sharing; see [Conventional & Islamic Banking](#conventional--islamic-banking)).
- **Two customer families** — **retail/personal** (mass, affluent, private) and **wholesale/corporate** (SME, mid-market, large corporate, financial institutions).

### Standards bodies & regulators

| Body | Jurisdiction | What it does |
|---|---|---|
| [BIS — Bank for International Settlements](https://www.bis.org) ⭐ | Global | The "central bank of central banks"; publishes banking research and hosts the Basel Committee |
| [Basel Committee on Banking Supervision](https://www.bis.org/bcbs/) ⭐ | Global | Authors the Basel capital frameworks (Basel I → III) that national regulators enforce |
| [Financial Stability Board (FSB)](https://www.fsb.org) | Global (G20) | Coordinates financial regulation to keep the global system stable |
| [FATF](https://www.fatf-gafi.org) | Global | Sets the 40 Recommendations — the global standard for AML/CFT |
| [IMF](https://www.imf.org) | Global | Surveillance, lending, and financial-stability assessments of national systems |
| [World Bank](https://www.worldbank.org) | Global | Development finance, financial-sector diagnostics, and payments modernization |
| [European Banking Authority (EBA)](https://www.eba.europa.eu) | EU | Harmonized banking supervision, stress tests, and payments rulebooks |
| [European Central Bank (ECB)](https://www.ecb.europa.eu) | Euro area | Runs monetary policy and directly supervises the largest euro-area banks |
| [FCA](https://www.fca.org.uk) | UK | Conduct regulator for retail and wholesale banking, payments, and open banking |
| [OCC](https://www.occ.gov) | US | Charters, regulates, and supervises national banks |
| [Federal Reserve](https://www.federalreserve.gov) | US | Central bank; supervises bank holding companies and runs Fedwire/FedNow |
| [FDIC](https://www.fdic.gov) | US | Insures deposits and supervises community banks |
| [APRA](https://www.apra.gov.au) | Australia | Prudential regulator for banks, insurers, and superannuation |
| [MAS](https://www.mas.gov.sg) | Singapore | Integrated regulator — monetary authority, banking, insurance, and securities |
| [SAMA](https://www.sama.gov.sa) | Saudi Arabia | Central bank of the Kingdom; leads Islamic finance and digital banking growth |
| [DFSA](https://www.dfsa.ae) | Dubai (DIFC) | Regulates banking and finance within the Dubai International Financial Centre |
| [ADGM](https://www.adgm.com) | Abu Dhabi | International financial centre with its own common-law framework |

### Learning & reference

| Resource | Description |
|---|---|
| [BIS publications](https://www.bis.org/index.htm) ⭐ | The authoritative library of banking regulation, payment-system, and market papers |
| [Corporate Finance Institute (CFI)](https://corporatefinanceinstitute.com) | Structured courses and free references on banking, credit, and corporate finance |
| [FRED (St. Louis Fed)](https://fred.stlouisfed.org) 🆓 | Free economic and financial data — rates, spreads, money supply — for real examples |
| [Investopedia](https://www.investopedia.com) 🆓 | Accessible explainers for every banking term a PM or engineer will meet |

**[⬆ back to top](#table-of-contents)**

---

## Security

> In banking, **security is the product's foundation, not a feature.** The crown jewels are credentials, card data, money movement, and customer PII. Assume hostile users, hostile third parties, and hostile insiders; design so that one compromised layer cannot reach the money.

### Key concepts

- **Defense in depth** — network, host, application, data, and identity layers each assume the layer above is breached.
- **Data protection** — encryption in transit (TLS) and at rest (AES-256, field-level where needed), tokenization of card data, key management in **HSMs/KMS**, strict access control and least privilege.
- **Identity & authentication** — multi-factor authentication (MFA), biometrics, device binding, behavioral risk scoring, and PSD2 **Strong Customer Authentication (SCA)** for payments.
- **Fraud & transaction monitoring** — real-time scoring of transactions, velocity rules, anomaly detection, and chargeback defense.
- **Zero trust** — verify every request regardless of origin; segment networks; never trust the perimeter.
- **Testing** — threat modeling (STRIDE), penetration testing, bug bounties, and a secure SDLC.

### Frameworks & standards

| Standard | Description |
|---|---|
| [PCI DSS](https://www.pcisecuritystandards.org) ⭐ | The mandatory card-data security standard for anyone storing, processing, or transmitting cardholder data |
| [ISO/IEC 27001](https://www.iso.org/standard/27001) | The international information-security management standard (ISMS) |
| [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) | Risk-based framework widely adopted by financial regulators and institutions |
| [SOC 2](https://www.aicpa-cima.com/topic/audit-assurance/audit-and-assurance-greater-than-soc-2) | Attestation over security, availability, processing integrity, confidentiality, and privacy controls |
| [EMVCo](https://www.emvco.com) | The technical standards body behind EMV chip, tokenization, and 3-D Secure |

### Infrastructure & platforms

| Tool | Description |
|---|---|
| [Thales Luna HSM](https://cpl.thalesgroup.com/encryption/hsms) ⭐ 💰 | The industry-standard hardware security modules for key custody and card personalization |
| [AWS KMS](https://aws.amazon.com/kms/) · [Azure Key Vault](https://azure.microsoft.com/en-us/products/key-vault/) · [Google Cloud KMS](https://cloud.google.com/security/products/cloud-kms) ☁️ | Managed key management and encryption services on the big three clouds |
| [HashiCorp Vault](https://www.vaultproject.io) 🔓 | Dynamic secrets, encryption-as-a-service, and access policy for app-layer secrets |
| [Okta](https://www.okta.com) · [Ping Identity](https://www.pingidentity.com) ☁️ | Enterprise identity platforms — SSO, MFA, and customer identity (CIAM) |
| [OWASP](https://owasp.org) 🆓 🔓 | The reference body for web/app security guidance, testing guides, and the Top 10 |

### Fraud detection & prevention

| Platform | Description |
|---|---|
| [Feedzai](https://feedzai.com) ⭐ 💰 | AI-first transaction monitoring and fraud risk for payments, cards, and A2A |
| [Featurespace](https://www.featurespace.com) 💰 | Real-time behavioral analytics (Adaptive Behavioral Analytics) across the customer lifecycle |
| [Sift](https://sift.com) 💰 | Digital trust and fraud platform for account abuse, payments, and chargebacks |
| [NICE Actimize](https://www.niceactimize.com) ⭐ 💰 | The enterprise mainstay for fraud and AML across banking, cards, and brokerage |
| [DataVisor](https://www.datavisor.com) 💰 | Unsupervised machine learning that catches coordinated fraud rings early |
| [LexisNexis ThreatMetrix](https://risk.lexisnexis.com/products/threatmetrix) ☁️ | Digital identity network that fingerprints devices and behavior for risk scoring |

**[⬆ back to top](#table-of-contents)**

---

## Compliance & Regulation

> Banking is one of the most regulated industries in the world, and compliance is a **license to operate** — miss a requirement and you can be fined, restricted, or shut down. The compliance function owns the bank's relationship with the regulator: reporting, AML/CFT, conduct, consumer protection, and sanctions.

### Key concepts

- **Prudential regulation** — capital and liquidity: Basel III (CET1, LCR, NSFR), the EU CRR/CRD, and the US Dodd-Frank.
- **AML/CFT** — know the customer (KYC), monitor transactions, file suspicious-activity reports, and screen for sanctions. Global bar: the FATF 40 Recommendations.
- **Sanctions** — OFAC (US), EU, and UN lists; screen every party in a transaction and freeze prohibited flows.
- **Conduct & consumer protection** — responsible lending, fair treatment, clear pricing (e.g., the US Truth in Lending Act / TRID), and complaint handling.
- **Payments regulation** — PSD2 evolving into **PSD3 + the Payment Services Regulation (PSR)** in the EU, the UK CMA Open Banking regime, and the US CFPB **Section 1033** rule.
- **Data protection** — GDPR, CCPA, and data-residency rules shape what banks may store, share, and use for scoring.

### Regulations & frameworks

| Regulation / Framework | Region | What it governs |
|---|---|---|
| [Basel III](https://www.bis.org/bcbs/basel3.htm) ⭐ | Global | Bank capital, leverage, and liquidity — the prudential floor for everything else |
| [FATF Recommendations](https://www.fatf-gafi.org/en/publications/fatfrecommendations/fatf-recommendations.html) ⭐ | Global | The 40 AML/CFT standards every national regime implements |
| [PSD2 → PSD3 / PSR](https://www.eba.europa.eu/regulation-and-policy/payment-services-and-electronic-money) ⭐ | EU | Payment services, strong customer authentication, and open-banking access rights |
| [GDPR](https://gdpr-info.eu) | EU | Personal data protection, data-subject rights, and fines up to 4% of turnover |
| [MiFID II](https://www.esma.europa.eu) | EU | Investment services and market conduct (applies to banks' wealth arms) |
| [OFAC Sanctions](https://ofac.treasury.gov) | US | Specially Designated Nationals (SDN) list and sanctions screening |
| [CFPB Section 1033](https://www.consumerfinance.gov/rules-policy/final-rules/required-rulemaking-on-personal-financial-data-rights/) | US | Personal financial data rights — the US open-banking rule |

### RegTech & compliance platforms

| Platform | Description |
|---|---|
| [Fenergo](https://www.fenergo.com) ⭐ 💰 | Client lifecycle management (CLM) and KYC automation across onboarding and regulatory change |
| [ComplyAdvantage](https://complyadvantage.com) ⭐ ☁️ | Real-time AML data, sanctions, PEP, and adverse-media screening via API |
| [NICE Actimize](https://www.niceactimize.com) 💰 | The enterprise mainstay for AML transaction monitoring, screening, and case management |
| [Quantexa](https://www.quantexa.com) 💰 | Decision intelligence over connected data — entity resolution, network analytics, AML |
| [LSEG World-Check](https://www.lseg.com/en/data-analytics/products/world-check) ☁️ | The screening database of record for PEPs, sanctions, and adverse media |
| [Dow Jones Risk & Compliance](https://www.dowjones.com/professional/risk/) ☁️ | Watchlist and ownership research data with global coverage |
| [Regnology](https://www.regnology.net) 💰 | Regulatory reporting and data collection for prudential and markets regulation |
| [AxiomSL (Moody's)](https://www.moodys.com) 💰 | Regulatory capital and reporting analytics across jurisdictions |

**[⬆ back to top](#table-of-contents)**

---

## Banking Architecture

> A modern bank is a **layered stack**: channels on top, a digital experience layer, a core ledger in the middle, and payments, data, and integration underneath. The single most important architectural decision is **where the ledger lives** — legacy cores still run on mainframes, while cloud-native cores treat products as code and the ledger as a service.

### Key concepts

- **Core banking** — the system of record for accounts, deposits, loans, and balances. "Core" literally means the daily transactions that update the ledger.
- **Digital banking platform** — the customer-facing layer (mobile, web, API) that orchestrates journeys in front of the core.
- **Composable banking** — assembling best-of-breed services (ledger, cards, payments, KYC, onboarding) via APIs instead of buying a monolith.
- **Banking-as-a-Service (BaaS) & embedded finance** — licensed banks expose accounts, cards, and payments via API so brands and fintechs can embed banking into their products.
- **ISO 20022** — the common financial messaging standard; payments are migrating to it globally.
- **Data & events** — an event-driven backbone (Kafka) and a cloud data platform (Snowflake/Databricks) feed analytics, risk, and AI.

### Core banking platforms

| Platform | Model | Notes |
|---|---|---|
| [Temenos Transact](https://www.temenos.com) ⭐ 💰 | Enterprise core | The global market leader — 30+ years of T24 lineage, now cloud-native Transact; strong multi-country/multi-currency out of the box |
| [Thought Machine Vault](https://www.thoughtmachine.net) ⭐ 💰 | Cloud-native core | Products expressed as code (smart contracts); used by Lloyds, JPMorgan (UK), Atom, Standard Chartered |
| [Mambu](https://mambu.com) ⭐ 💰 | Cloud-native core | API-first SaaS core for deposits, lending, and payments; popular with neobanks and fintechs |
| [FIS](https://www.fisglobal.com) 💰 | Enterprise core | US powerhouse across retail/commercial banking, payments, and capital markets |
| [Fiserv / Finxact](https://www.fiserv.com) 💰 | Enterprise core | US community/regional banking mainstay; Finxact is its cloud-native core |
| [Jack Henry](https://www.jackhenry.com) 💰 | Enterprise core | The dominant core for US community and credit-union banking |
| [Oracle FLEXCUBE](https://www.oracle.com/industries/financial-services/flexcube/) 💰 | Enterprise core | Global retail/corporate core, strong in emerging markets |
| [Infosys Finacle](https://www.edgeverve.com/finacle/) 💰 | Enterprise core | India-origin global core with deep banking-process coverage |
| [TCS BaNCS](https://www.tcs.com/bancs) 💰 | Enterprise core | Large-scale retail, payments, and corporate banking platform |
| [Avaloq](https://www.avaloq.com) 💰 | Wealth-focused core | The core of choice for private banking and wealth management |
| [NCR Voyix](https://www.ncrvoyix.com) 💰 | Mid-market core | Payments and digital banking across retail and mid-market banks |
| [Skaleet](https://www.skaleet.com) 💰 | Modular core | Composable, modular core for digital banks and EMIs |
| [Nymbus](https://nymbus.com) ☁️ | Neobank-in-a-box | Digital bank and core platform aimed at launching banks fast |

### Digital banking & engagement layers

| Platform | Description |
|---|---|
| [Backbase](https://www.backbase.com) ⭐ 💰 | The leading digital-banking engagement platform — omnichannel journeys that sit in front of any core |
| [nCino](https://www.ncino.com) 💰 | The cloud banking platform for commercial and small-business lending (built on Salesforce) |
| [Q2](https://www.q2.com) 💰 | Digital banking platform strong in the US mid-market and credit-union space |
| [Temenos Infinity](https://www.temenos.com/products/experience/) 💰 | Temenos' omnichannel digital experience layer |

### Banking-as-a-Service & embedded finance

| Platform | Description |
|---|---|
| [Unit](https://www.unit.co) ⭐ 💰 | Programmable BaaS — accounts, cards, and payments for product teams |
| [Solaris](https://www.solarisgroup.com) 💰 | European licensed bank behind many fintechs' banking products |
| [Railsr](https://www.railsr.com) 💰 | UK/EU BaaS — card issuing, wallets, and embedded banking (formerly Railsbank) |
| [Galileo (SoFi Tech Solutions)](https://www.galileo-ft.com) 💰 | Payment and card processing infrastructure at scale (part of SoFi) |
| [Treasury Prime](https://treasuryprime.com) 💰 | US BaaS connecting fintechs to partner banks |
| [ClearBank](https://www.clear.bank) 💰 | UK clearing bank offering BaaS for payment accounts and settlement |
| [SDK.finance](https://sdk.finance) 🔓 💰 | Open-source-friendly banking and wallet platform |

### Data, events & integration

| Tool | Description |
|---|---|
| [Confluent / Apache Kafka](https://www.confluent.io) ⭐ | The event-streaming backbone for modern banking cores and payments |
| [ISO 20022](https://www.iso20022.org) ⭐ | The global standard for financial messaging (payments, cards, trade) |
| [MuleSoft](https://www.mulesoft.com) ☁️ | Integration platform connecting legacy cores to modern channels |
| [Snowflake](https://www.snowflake.com) · [Databricks](https://www.databricks.com) ⭐ ☁️ | Cloud data platforms for the banking data warehouse/lakehouse |

**[⬆ back to top](#table-of-contents)**

---

## Mobile Banking Design

> Mobile is the **primary channel** for retail banking — most customers interact with their bank only through an app. The design bar is trust and clarity: users must understand their money, complete critical flows (payments, transfers, onboarding) without error, and feel that the app is secure. Every screen is a compliance surface too (SCA, disclosures, accessibility).

### Key concepts

- **Show the balance first** — money is the object of anxiety; make it legible before anything else.
- **Confidence before cleverness** — banking reward clarity over surprise; animations and patterns must never obscure a money movement.
- **Friction where it matters** — reduce friction in onboarding, but add deliberate friction (confirmation, delays, warnings) at points of irreversible money movement or fraud risk.
- **Authentication as design** — biometrics, device-bound sessions, and 2FA woven into flows rather than bolted on.
- **Accessibility is mandatory** — banking apps are essential services; WCAG AA is the floor, and regulators increasingly require it.
- **Transparency** — fees, limits, holds, and pending states must be surfaced proactively.

### Design systems & guidelines

| Resource | Description |
|---|---|
| [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/) ⭐ | The iOS patterns every mobile banking app starts from |
| [Material Design 3](https://m3.material.io) ⭐ | Google's design system for Android experiences |
| [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) ⭐ | Web Content Accessibility Guidelines — the accessibility contract for banking UIs |
| [Goldman Sachs Marquee](https://www.marquee.gs) | A public example of a serious financial design system and developer platform |
| [Backbase Design System](https://www.backbase.com) | A banking-specific design system for retail and business journeys |
| [Design Guidelines for Financial Data](https://www.figma.com) | Figma hosts community banking/FinTech UI kits — a fast starting point for prototypes |

### UX research & testing

| Tool | Description |
|---|---|
| [Figma](https://www.figma.com) ⭐ | The standard design tool — prototypes, design systems, and handoff |
| [Maze](https://maze.co) 💰 | Rapid usability testing on prototypes — catch confusion before code |
| [Optimal Workshop](https://www.optimalworkshop.com) 💰 | Card sorts and tree tests to validate navigation and information architecture |

**[⬆ back to top](#table-of-contents)**

---

## Low-Code & No-Code Tools

> Banking teams use low-code/no-code for what they must ship fast and change constantly: internal operations, journey automation, approvals, reconciliation, exception handling, and partner integrations. The selection bar in a regulated environment is higher — you need **auditability, role-based access, versioning, and deployment control** — so prefer platforms with enterprise governance.

### Enterprise low-code platforms

| Platform | Description |
|---|---|
| [OutSystems](https://www.outsystems.com) 💰 | Full-stack low-code with strong enterprise governance and integration capabilities |
| [Mendix](https://www.mendix.com) 💰 | Low-code application development with a marketplace and cloud-native deployment |
| [Appian](https://appian.com) 💰 | Low-code + process automation + case management — popular in banking operations |
| [Pega](https://www.pega.com) 💰 | Workflow and customer-engagement automation, widely deployed in financial services |
| [Microsoft Power Platform](https://powerplatform.microsoft.com) ☁️ | Power Apps, Power Automate, Power BI — the default inside Microsoft shops |
| [Google AppSheet](https://appsheet.com) ☁️ | No-code app building from spreadsheets and data sources |
| [ServiceNow](https://www.servicenow.com) 💰 | IT and workflow automation with a financial-services industry edition |
| [Salesforce Financial Services Cloud](https://www.salesforce.com/products/financial-services-cloud/) 💰 | CRM + banking-specific data model (accounts, households, financial relationships) |
| [Betty Blocks](https://www.bettyblocks.com) 💰 | No-code platform emphasizing governance and IT control |

### Internal tools & automation

| Tool | Description |
|---|---|
| [Retool](https://retool.com) 💰 | Rapidly build internal admin/operations tools on top of your own data |
| [Bubble](https://bubble.io) 💰 | No-code web apps for MVPs and internal products |
| [n8n](https://n8n.io) 🔓 | Fair-code workflow automation with 400+ integrations — the flexible alternative to Zapier |
| [Zapier](https://zapier.com) 💰 | Easy no-code automation between SaaS tools |
| [Airtable](https://airtable.com) 💰 | Spreadsheet-database hybrid for ops tracking and light workflow |
| [Quickbase](https://www.quickbase.com) 💰 | No-code database apps built for operational workflows |
| [Knack](https://www.knack.com) 💰 | No-code databases and apps for small teams |

**[⬆ back to top](#table-of-contents)**

---

## AI in Banking

> AI in banking is **decisioning at the moment of truth**: whether to approve a loan, release a payment, block a transaction, or respond to a customer. The differentiator from other industries is **governance** — models must be explainable, fair, auditable, and defensible to a regulator (model risk management, SR 11-7, EU AI Act).

### Key concepts

- **Where AI lands** — credit underwriting, fraud and AML, collections, contact-center and virtual assistants, document processing, personalization, and investment advice.
- **Generative AI** — copilots for staff (drafting, research, code), customer assistants, and document intelligence; always with human oversight and data-permission guardrails.
- **The governance layer** — model inventory, challenger models, fairness monitoring, drift detection, explainability, and audit trails.
- **Data is the moat** — clean, consented, well-governed data beats model tricks every time.

### Credit & underwriting AI

| Platform | Description |
|---|---|
| [FICO Platform](https://www.fico.com) ⭐ 💰 | The decisioning incumbent — credit scoring and decision engines across the industry |
| [Zest AI](https://www.zest.ai) 💰 | Interpretable ML credit models that outperform traditional scorecards |
| [Scienaptic](https://scienaptic.com) 💰 | AI credit decisioning for banks and credit unions |
| [Provenir](https://www.provenir.com) 💰 | Risk decisioning platform for consumer and SME lending |
| [Experian PowerCurve](https://www.experian.com/decision-analytics/powercurve) 💰 | Decisioning and strategies across the credit lifecycle |

### Fraud & AML AI

| Platform | Description |
|---|---|
| [Feedzai](https://feedzai.com) 💰 | AI transaction monitoring across payments, cards, and A2A |
| [Quantexa](https://www.quantexa.com) 💰 | Network analytics for AML, fraud, and KYC across connected entities |
| [DataVisor](https://www.datavisor.com) 💰 | Unsupervised learning to catch coordinated fraud and money-laundering patterns |
| [Shift Technology](https://www.shift-technology.com) 💰 | AI claims and underwriting intelligence (insurance, but used by banks' insurance arms) |

### Document intelligence & processing

| Platform | Description |
|---|---|
| [ABBYY](https://www.abbyy.com) ⭐ 💰 | The veteran OCR/document-processing vendor — bank statements, IDs, contracts |
| [Hyperscience](https://hyperscience.com) 💰 | Document automation with human-in-the-loop verification |
| [Rossum](https://rossum.ai) 💰 | AI document understanding for invoices, KYC, and trade documents |
| [Ocrolus](https://www.ocrolus.com) 💰 | Automated analysis of bank statements and financial documents for lending |
| [Amazon Textract](https://aws.amazon.com/textract/) ☁️ | Extract text, tables, and forms from documents at cloud scale |

### Conversational AI & virtual assistants

| Platform | Description |
|---|---|
| [Kore.ai](https://kore.ai) 💰 | Enterprise virtual assistants and agent-assist for banking |
| [Amelia](https://amelia.com) 💰 | Digital employee/customer agents with NLU across banking journeys |
| [Cognigy](https://cognigy.com) 💰 | Contact-center AI with low-code conversational flows |
| [IBM watsonx Assistant](https://www.ibm.com/watsonx) 💰 | Conversational AI on the enterprise watsonx platform |
| [LivePerson](https://www.liveperson.com) 💰 | Conversational commerce and messaging for banking customer care |

### Generative AI & ML platforms

| Platform | Description |
|---|---|
| [Anthropic](https://www.anthropic.com) · [OpenAI](https://openai.com) ⭐ | Frontier LLMs used for copilots, assistants, and document understanding |
| [Azure OpenAI](https://azure.microsoft.com/en-us/products/ai-services/openai-service) · [Google Vertex AI](https://cloud.google.com/vertex-ai) · [AWS Bedrock](https://aws.amazon.com/bedrock/) ☁️ | Managed enterprise GenAI access on the big three clouds |
| [Dataiku](https://www.dataiku.com) 💰 | The leading data-science/ML platform in banking — governed AI end to end |
| [DataRobot](https://www.datarobot.com) 💰 | Automated machine learning for model development and deployment |
| [H2O.ai](https://h2o.ai) 💰 | Open-source-rooted ML for credit, fraud, and churn |
| [Fiddler](https://www.fiddler.ai) · [Arthur](https://www.arthur.ai) 💰 | Model observability, monitoring, and explainability |

**[⬆ back to top](#table-of-contents)**

---

## Customers & Experience

> Banking customers are won or lost on **trust and moments that matter**: onboarding, the first transfer, a dispute, a limit increase, a hardship. Banks segment by *wealth, life stage, and business size* — and increasingly measure success by **financial health**, not just product sales.

### Key concepts

- **Segments** — mass retail, affluent, private banking, SMEs, mid-market, large corporate, and institutional (plus conventional vs Islamic needs).
- **Lifecycle** — acquire → onboard → engage → transact → borrow/invest → retain → expand; every stage has a KYC and risk counterpart.
- **Relationship vs product view** — best-in-class banks model the *household/relationship*, not just individual accounts.
- **Financial health** — helping customers save, manage cashflow, and avoid debt traps builds durable loyalty (and is increasingly a regulatory theme).
- **Omnichannel** — branch, call center, app, and web must share one customer view and one journey state.

### CRM & relationship platforms

| Platform | Description |
|---|---|
| [Salesforce Financial Services Cloud](https://www.salesforce.com/products/financial-services-cloud/) ⭐ 💰 | The banking-specific CRM — households, financial accounts, relationship insights |
| [Microsoft Dynamics 365](https://dynamics.microsoft.com) 💰 | Enterprise CRM often paired with Power Platform for banking operations |
| [Pega Customer Engagement](https://www.pega.com) 💰 | Next-best-action personalization and decisioning across channels |
| [Freshworks](https://www.freshworks.com) 💰 | Support/helpdesk for customer service teams |

### CX, feedback & data

| Tool | Description |
|---|---|
| [Medallia](https://www.medallia.com) 💰 | Enterprise experience management — VoC, NPS, and journey analytics |
| [Qualtrics](https://www.qualtrics.com) 💰 | Survey and experience management at scale |
| [Segment](https://segment.com) ☁️ | Customer data platform for unified customer profiles |
| [Amperity](https://amperity.com) · [mParticle](https://www.mparticle.com) ☁️ | Enterprise customer data infrastructure for personalization |

**[⬆ back to top](#table-of-contents)**

---

## KYC & Customer Due Diligence

> KYC is the **front door of the bank**: verify who the customer is (ID verification), assess their risk (due diligence), screen them continuously (sanctions/PEP/adverse media), and monitor activity for the life of the relationship. Modern KYC stacks are orchestrated — identity verification, screening, and risk scoring stitched into the onboarding journey and refreshed on an ongoing basis.

### Key concepts

- **The three pillars of KYC** — customer identification, due diligence (CDD/EDD), and ongoing monitoring.
- **CDD vs EDD** — standard due diligence for low-risk customers; **Enhanced Due Diligence** (source of funds, source of wealth, ownership structures) for PEPs, high-risk jurisdictions, and complex structures.
- **Beneficial ownership** — regulators demand you look through entities to the natural persons who own or control them.
- **Screening** — sanctions lists (OFAC, EU, UN), PEP lists, and adverse media; false positives are the ops burden to tune.
- **The KYC utility** — sharing verified KYC across banks to cut onboarding cost without cutting rigor.

### Identity verification & onboarding

| Platform | Description |
|---|---|
| [Onfido](https://onfido.com) ⭐ ☁️ | Document and biometric identity verification with liveness detection |
| [Persona](https://withpersona.com) ☁️ | Identity platform and workflow builder for verification and fraud prevention |
| [Jumio](https://www.jumio.com) ☁️ | Identity verification and AML/KYC — strong on compliance reporting |
| [Sumsub](https://sumsub.com) ☁️ | Global KYB/KYC orchestration with a compliance dashboard |
| [Veriff](https://www.veriff.com) ☁️ | IDV with 230+ document types and liveness |
| [Trulioo](https://www.trulioo.com) ☁️ | Identity and business verification across 195+ countries |
| [Alloy](https://www.alloy.com) ⭐ ☁️ | The decisioning engine that orchestrates many KYC/KYB providers into one API |
| [Ondato](https://ondato.com) ☁️ | Identity verification and AML workflow platform |
| [iDenfy](https://www.idenfy.com) ☁️ | ID verification with AML and fraud screening |
| [AU10TIX](https://www.au10tix.com) ☁️ | The veteran ID-verification vendor behind many banking and payments flows |

### Screening & intelligence

| Platform | Description |
|---|---|
| [LSEG World-Check](https://www.lseg.com/en/data-analytics/products/world-check) ⭐ ☁️ | The de-facto screening data source for sanctions, PEPs, and adverse media |
| [ComplyAdvantage](https://complyadvantage.com) ☁️ | Real-time watchlist data and screening via API |
| [Dow Jones Risk & Compliance](https://www.dowjones.com/professional/risk/) ☁️ | Third-party risk, ownership, and sanctions research |
| [LexisNexis Risk Solutions](https://risk.lexisnexis.com) ☁️ | Identity, fraud, and compliance data across the US and global markets |

### AML transaction monitoring & analytics

| Platform | Description |
|---|---|
| [NICE Actimize](https://www.niceactimize.com) ⭐ 💰 | The enterprise standard for AML transaction monitoring and case management |
| [Quantexa](https://www.quantexa.com) 💰 | Entity resolution and network analytics that surface hidden money flows |
| [Tookitaki](https://www.tookitaki.com) 💰 | AI-native AML and sanctions systems |
| [Chainalysis](https://www.chainalysis.com) · [Elliptic](https://www.elliptic.co) 💰 | Crypto and digital-asset transaction monitoring and investigation |
| [FATF](https://www.fatf-gafi.org) · [Wolfsberg Group](https://www.wolfsberg-principles.com) ⭐ | The standards that define what "good" KYC/AML looks like |

**[⬆ back to top](#table-of-contents)**

---

## Accounts

> An **account** is the atom of banking — the ledger record a customer deposits into, transacts from, and borrows against. Understanding account types, numbering schemes (IBAN/BIC), rails, and the data layers around accounts is the foundation of nearly every banking product.

### Key concepts

- **Account types** — current/checking (transactional, often non-interest-bearing), savings, term deposits, multi-currency, pooled, and nostro/vostro (a bank's own accounts at other banks).
- **The ledger** — every transaction is a double-entry movement; the account's balance is the running result. Modern cores model accounts as code (products) with attached behavior.
- **Rails** — moving money uses rail-specific identifiers and rules: ACH (US), SEPA (EU), Faster Payments (UK), FedNow/RTP (instant), UPI (India), SWIFT (cross-border), cards (networks).
- **Account opening** — orchestration of KYC, risk checks, and product assignment; the highest-converting moment in retail banking.
- **Account data & aggregation** — reading a customer's accounts (with consent) powers PFM, lending, and open banking.

### Account data & aggregation

| Platform | Description |
|---|---|
| [Plaid](https://plaid.com) ⭐ ☁️ | The US standard for connecting bank accounts — auth, balances, transactions, identity |
| [MX](https://www.mx.com) ☁️ | Financial data platform and personalization layer for banks and fintechs |
| [Envestnet Yodlee](https://www.yodlee.com) ☁️ | The veteran data-aggregation provider with rich transaction categorization |
| [TrueLayer](https://truelayer.com) · [Tink](https://tink.com) · [Yapily](https://www.yapily.com) ☁️ | The leading European open-banking aggregators (AIS/PIS) |
| [Flinks](https://flinks.com) ☁️ | Canadian account-connectivity and data platform |
| [Finicity](https://www.finicity.com) ☁️ | Open-banking data (part of Mastercard) strong in the US |

### Payment rails

| Rail | Region | Notes |
|---|---|---|
| [ACH (NACHA)](https://www.nacha.org) ⭐ | US | The batched direct-deposit / bill-pay rail; final in 1–2 business days |
| [FedNow](https://www.frbservices.org/financial-services/fednow) | US | The Federal Reserve's instant-payment rail (24/7) |
| [RTP (The Clearing House)](https://www.theclearinghouse.org/payments/rtp) | US | Real-time payments from US banks |
| [SEPA](https://www.ecb.europa.eu/paym/integration/retail/sepa/html/index.en.html) ⭐ | EU | Standardized euro credit transfers and direct debits; SEPA Instant for real time |
| [UK Faster Payments](https://www.fasterpayments.org.uk) | UK | The UK's near-instant, 24/7 interbank rail |
| [UPI (NPCI)](https://www.npci.org.in) | India | India's interoperable instant-payments system — billions of transactions monthly |
| [SWIFT](https://www.swift.com) ⭐ | Global | The correspondent network for cross-border payments and messaging |

### Ledger & account infrastructure

| Tool | Description |
|---|---|
| [Modern Treasury](https://www.moderntreasury.com) 💰 | Ledger-as-a-service and payment operations for money-moving products |
| [Moov](https://moov.io) 🔓 | Open-source payments and money-movement infrastructure |
| [Thought Machine Vault](https://www.thoughtmachine.net) 💰 | Cloud-native ledger where products are code (see Architecture) |
| [LedgerFi](https://www.ledgerfi.com) 💰 | Real-time ledger and treasury infrastructure for fintechs |

**[⬆ back to top](#table-of-contents)**

---

## Savings & Deposits

> Deposits are a bank's **cheapest source of funding** and the base of its balance sheet. The product set spans everyday savings, term/time deposits, money-market accounts, and certificates of deposit — priced off the yield curve and protected by deposit-insurance schemes.

### Key concepts

- **Everyday savings** — liquid, low-yield, the "safety bucket"; often bundled with budgeting and round-up features.
- **Term/time deposits (FDs/CDs)** — fixed term and rate; the customer trades liquidity for yield; breaking early usually costs penalty or lost interest.
- **Rate mechanics** — the bank pays the customer a rate, lends at a higher rate; the **spread** is its margin. When the yield curve inverts, margins compress.
- **Deposit insurance** — FDIC (US, $250k), FSCS (UK, £85k), and national schemes make deposits safe and keep money in the system during stress.
- **ALM & liquidity** — banks match the maturity of deposits to assets (asset-liability management); deposits fund loans and are stress-tested (LCR).
- **Islamic deposits** — instead of interest, deposits run on *qard* (interest-free loans) or *mudarabah* (profit-sharing) contracts — see [Conventional & Islamic Banking](#conventional--islamic-banking).

### Tools & data

| Tool | Description |
|---|---|
| [FDIC](https://www.fdic.gov) ⭐ | US deposit insurance and bank data (also the main source of banking-industry statistics) |
| [FSCS](https://www.fscs.org.uk) | UK deposit-protection scheme |
| [Bankrate](https://www.bankrate.com) 🆓 | Rate comparison and deposit-rate benchmarks |
| [DepositAccounts](https://www.depositaccounts.com) 🆓 | Deep deposit-rate tracking and product comparison |
| [FRED](https://fred.stlouisfed.org) 🆓 | Yield-curve and interest-rate data for pricing and ALM analysis |
| [Murex](https://www.murex.com) · [Calypso](https://www.calypso.com) 💰 | Treasury, ALM, and risk systems that price and manage deposit books |

**[⬆ back to top](#table-of-contents)**

---

## Credit Cards

> Credit cards are the most profitable and most complex retail product: a **four-party network** (cardholder, merchant, issuer, acquirer) with authorization, settlement, interchange, and dispute flows. The card data lives under **PCI DSS**, and modern card stacks are tokenized and API-first.

### Key concepts

- **Issuing vs acquiring** — the issuer holds the cardholder relationship; the acquirer (and processor) serves the merchant. Networks (Visa/Mastercard/Amex/Discover) sit in the middle.
- **The card lifecycle** — instant issue or physical, activation, authorization, clearing/settlement, billing, rewards, dispute/chargeback.
- **Money flow** — cardholder pays the issuer; issuer pays the network; network pays the acquirer; acquirer pays the merchant, minus **interchange** and fees.
- **Security** — EMV chip, 3-D Secure, tokenization, PAN masking, and real-time fraud scoring.
- **Profit engine** — interest on revolving balances (APR), interchange, annual fees, and late/foreign-transaction fees; rewards are the retention cost.
- **Schemes & rails** — Visa, Mastercard, American Express (both issuer and network), Discover, JCB, UnionPay, and domestic schemes (e.g., RuPay, iDEAL's sister schemes).

### Card networks & standards

| Network | Description |
|---|---|
| [Visa](https://www.visa.com) ⭐ | The largest global card network |
| [Mastercard](https://www.mastercard.com) ⭐ | Visa's global competitor with heavy fintech push (Finicity, data) |
| [American Express](https://www.americanexpress.com) | Three-party model — issuer and network in one |
| [Discover](https://www.discover.com) | US card network with the Diners Club international alliance |
| [JCB](https://www.global.jcb/en/) | Japanese card scheme with global acceptance |
| [UnionPay](https://en.unionpay.com) | The Chinese scheme with the largest cardholder base |
| [EMVCo](https://www.emvco.com) ⭐ | The standards body for EMV chip, tokenization, and 3-D Secure |

### Issuing platforms

| Platform | Description |
|---|---|
| [Marqeta](https://www.marqeta.com) ⭐ ☁️ | The modern card-issuing platform — tokenized, programmatic, developer-first |
| [Galileo (SoFi Tech Solutions)](https://www.galileo-ft.com) 💰 | High-volume card and payment processing infrastructure |
| [Lithic](https://www.lithic.com) ☁️ | Programmatic card issuing with instant card creation |
| [Highnote](https://highnote.com) ☁️ | Card issuing and program management for modern fintechs |
| [Bond](https://www.bond.tech) ☁️ | BaaS for cards, accounts, and payments |
| [Pismo](https://www.pismo.io) 💰 | Cloud-native payments and card issuing platform (acquired by Visa) |

### Acquiring & processing

| Platform | Description |
|---|---|
| [Stripe](https://stripe.com) ⭐ ☁️ | The developer default for online payments and card acquiring |
| [Adyen](https://www.adyen.com) ⭐ ☁️ | Unified commerce payments — online, in-app, and POS at global scale |
| [Checkout.com](https://www.checkout.com) ☁️ | Enterprise acquiring and alternative-payment methods |
| [Worldpay](https://www.worldpay.com) 💰 | One of the largest global acquiring/processing networks (FIS) |
| [Global Payments](https://www.globalpayments.com) 💰 | Omnichannel acquiring and issuer processing |
| [Rapyd](https://www.rapyd.net) ☁️ | Local-payment-network aggregation across 100+ countries |

### Card risk & decisioning

| Platform | Description |
|---|---|
| [FICO Falcon](https://www.fico.com/en/products/falcon-platform) ⭐ 💰 | The industry-standard card fraud-detection engine |
| [Feedzai](https://feedzai.com) 💰 | AI card fraud and dispute automation |
| [Sift](https://sift.com) 💰 | Digital trust for payments, account abuse, and chargebacks |

**[⬆ back to top](#table-of-contents)**

---

## Personal Loans

> Personal loans are **installment credit**: a fixed amount, a fixed term, and an amortization schedule. The stack is origination → decisioning → disbursement → servicing → collections, and the economics hinge on **pricing risk correctly** (APR vs interest rate, fees, default).

### Key concepts

- **Secured vs unsecured** — unsecured (no collateral, higher rate, the "personal loan" default) vs secured (car, gold, salary-assigned).
- **Credit scoring** — FICO and VantageScore dominate US decisions; bureau data plus alternative data (income, cashflow, open banking) increasingly drive thin-file decisions.
- **APR vs interest rate** — APR folds in fees and is what consumers compare; regulators (Truth in Lending, responsible lending) make it mandatory to show it.
- **Amortization** — fixed-payment schedules where early payments are mostly interest; the model behind every term loan.
- **Buy now, pay later (BNPL)** — the fast-growing short-term installment category, increasingly regulated like credit.

### Origination & servicing

| Platform | Description |
|---|---|
| [Blend](https://blend.com) 💰 | Digital origination platform used across consumer and mortgage lending |
| [nCino](https://www.ncino.com) 💰 | Cloud origination and banking platform for consumer, SME, and commercial credit |
| [MeridianLink](https://www.meridianlink.com) 💰 | Consumer-lending origination for banks and credit unions |
| [Abrigo](https://www.abrigo.com) 💰 | Lending, credit-risk, and compliance software for community banks |
| [ICE Mortgage Technology](https://www.icemortgagetechnology.com) 💰 | The dominant US mortgage and consumer-lending origination platform (Encompass) |

### Decisioning & credit risk

| Platform | Description |
|---|---|
| [FICO](https://www.fico.com) ⭐ 💰 | Scores and decisioning used across the industry |
| [Zest AI](https://www.zest.ai) 💰 | Transparent ML models for consumer and small-business credit |
| [Scienaptic](https://scienaptic.com) 💰 | AI-driven credit decisions for banks and credit unions |
| [Provenir](https://www.provenir.com) 💰 | Real-time risk decisioning across consumer and SME lending |
| [Experian](https://www.experian.com) ⭐ | The credit bureau data and PowerCurve decisioning suite |

### BNPL & short-term credit

| Platform | Description |
|---|---|
| [Klarna](https://www.klarna.com) 💰 | The global BNPL leader, expanding into banking |
| [Affirm](https://www.affirm.com) 💰 | US BNPL with transparent, risk-based pricing |
| [Afterpay](https://www.afterpay.com) 💰 | Installment payments (part of Block) |
| [PayPal Pay Later](https://www.paypal.com) 💰 | BNPL embedded in the PayPal checkout |

**[⬆ back to top](#table-of-contents)**

---

## Mortgage

> Mortgages are the **longest, most regulated loan** — 15–30 year amortization, secured by the home, sold and resold in a government-backed secondary market (Fannie Mae, Freddie Mac, Ginnie Mae). The digital mortgage is a decade-long transformation: apply online, verify income/assets programmatically, close electronically, and service compliantly.

### Key concepts

- **Product types** — fixed-rate, adjustable-rate (ARM), FHA/VA (US government-insured), jumbo (above conforming limits), and HELOCs (home-equity lines of credit).
- **The key ratios** — LTV (loan-to-value), DTI (debt-to-income), and credit score drive price and approval.
- **Amortization & escrow** — fixed monthly payments pay down principal slowly at first; escrow bundles property tax and insurance into the payment.
- **The secondary market** — conforming loans are bundled into mortgage-backed securities by Fannie Mae and Freddie Mac, guaranteed by Ginnie Mae, and traded globally. This is what keeps US mortgage rates liquid.
- **Underwriting** — income, assets, credit, and property value verified to the "AUS" (automated underwriting system) rules of the GSEs.
- **TRID / responsible lending** — the loan estimate and closing disclosure give borrowers standardized, comparable pricing.

### Origination & LOS

| Platform | Description |
|---|---|
| [Blend](https://blend.com) ⭐ 💰 | Digital mortgage and consumer-lending origination — the modern default for lenders |
| [ICE Mortgage Technology](https://www.icemortgagetechnology.com) ⭐ 💰 | The industry-standard LOS (Encompass) plus the Black Knight servicing suite |
| [Maxwell](https://www.maxwell.com) 💰 | Digital mortgage origination for community banks and credit unions |
| [SimpleNexus](https://www.simplenexus.com) 💰 | Mobile-first mortgage origination for independent lenders |
| [nCino](https://www.ncino.com) 💰 | Cloud origination platform (built on Salesforce) for mortgage and commercial |

### Secondary market & infrastructure

| Institution | Description |
|---|---|
| [Fannie Mae](https://www.fanniemae.com) ⭐ | The largest US housing-finance company — buys conforming mortgages |
| [Freddie Mac](https://www.freddiemac.com) ⭐ | The GSE that competes with Fannie in the conforming market |
| [Ginnie Mae](https://www.ginniemae.gov) | The government corporation guaranteeing FHA/VA mortgage-backed securities |
| [Optimal Blue](https://www.optimalblue.com) 💰 | Mortgage pricing, hedging, and lock-desk analytics |

### Servicing

| Platform | Description |
|---|---|
| [ICE (Black Knight) Servicing](https://www.icemortgagetechnology.com) 💰 | The dominant US mortgage-servicing platform (MSP) |
| [Fiserv Mortgage Servicing](https://www.fiserv.com) 💰 | Core and secondary-market servicing at scale |
| [Sagent](https://www.sagent.com) 💰 | Modern, digital-first mortgage servicing |

**[⬆ back to top](#table-of-contents)**

---

## Investment & Wealth

> The wealth arm of a bank manages **other people's money**: brokerage and custody, discretionary portfolios, advice, retirement, and increasingly robo-advisory and digital assets. The operating model is front office (advisors, trading) → middle office (compliance, risk) → back office (settlement, custody, reporting).

### Key concepts

- **Segments** — retail investing, affluent, private banking, and institutional. Private banking adds lending, tax, estate, and lifestyle services.
- **The stack** — an order-management system (OMS) and portfolio-accounting system, market data, risk analytics, and client reporting.
- **Advisory vs discretionary** — advice the client acts on vs the bank managing within a mandate; both are regulated conduct (MiFID II, fiduciary duties).
- **Retirement** — 401(k)/IRA (US), ISA/SIPP (UK), and pensions are the largest retail asset pools banks administer.
- **Digital assets** — custody, trading, and tokenization of crypto and real-world assets is now a mainstream product conversation, with its own risk and AML controls.

### Portfolio & trading systems

| Platform | Description |
|---|---|
| [BlackRock Aladdin](https://www.blackrock.com/aladdin) ⭐ 💰 | The risk-and-portfolio operating system used by the world's largest asset managers |
| [Charles River (State Street)](https://www.crd.com) 💰 | Front-to-back investment management and trading (OMS/EMS) |
| [MSCI RiskMetrics](https://www.msci.com) 💰 | The market-standard risk analytics for portfolios |
| [SS&C Advent](https://www.advent.com) 💰 | Portfolio accounting, trading, and reporting for wealth managers |
| [Bloomberg AIM](https://www.bloomberg.com/professional/enterprise/) 💰 | Portfolio management and trading for the buy side |

### Market data & research

| Platform | Description |
|---|---|
| [Bloomberg Terminal](https://www.bloomberg.com/professional/product/bloomberg-terminal/) ⭐ 💰 | The industry's workstation — data, news, analytics, and execution |
| [LSEG Workspace (Eikon)](https://www.lseg.com/en/data-analytics/products/workspace) 💰 | Refinitiv's data and analytics desktop |
| [FactSet](https://www.factset.com) 💰 | Integrated financial data and analytics platform |
| [S&P Capital IQ](https://www.spglobal.com/marketintelligence/en/solutions/capital-iq-platform) 💰 | Company, credit, and market data with screening tools |
| [Moody's Analytics](https://www.moodys.com) 💰 | Credit data and analytical software |

### Retail investing & robo-advisory

| Platform | Description |
|---|---|
| [Betterment](https://www.betterment.com) 💰 | The original robo-advisor — automated portfolios with advisor access |
| [Wealthfront](https://www.wealthfront.com) 💰 | Automated investing and financial planning |
| [Vanguard](https://investor.vanguard.com) ⭐ 💰 | The low-cost investing default and Digital Advisor |
| [Interactive Brokers](https://www.interactivebrokers.com) 💰 | Full-featured brokerage at scale |
| [Alpaca](https://alpaca.markets) ☁️ | Commission-free brokerage API for building your own investing products |
| [DriveWealth](https://www.drivewealth.com) ☁️ | Fractional investing infrastructure for embedded brokerage |

### Digital assets

| Platform | Description |
|---|---|
| [Coinbase](https://www.coinbase.com) 💰 | The largest US retail crypto exchange |
| [Fireblocks](https://www.fireblocks.com) 💰 | Institutional custody and settlement infrastructure for digital assets |
| [Chainalysis](https://www.chainalysis.com) 💰 | Blockchain data, AML, and investigations for crypto flows |

**[⬆ back to top](#table-of-contents)**

---

## Insurance

> Insurance runs alongside banking in the same institution's balance sheet — **bancassurance** (selling insurance through the bank's channels) is how most customers first buy life, motor, or home cover. The domain splits into product (underwriting/pricing), distribution, claims, and policy administration; the software market is consolidating around cloud-native core systems and AI claims.

### Key concepts

- **Product lines** — life, health, general/P&C (motor, home, liability), and specialty (marine, cyber, trade credit). Islamic **takaful** is the Shariah-compliant equivalent.
- **The insurance cycle** — underwrite (risk select & price) → issue policy → collect premium → manage claims. Profit = premium − claims − expenses − investment income.
- **Bancassurance** — the bank sells insurer products through branches and apps; the insurer pays commission; data sharing is regulated.
- **Embedded insurance** — insurance sold at the point of a related product (e.g., travel cover at checkout, payment protection on a loan).
- **Regulation** — Solvency II (EU) sets capital and governance rules; RBC regimes exist in other markets.

### Core insurance systems

| Platform | Description |
|---|---|
| [Guidewire](https://www.guidewire.com) ⭐ 💰 | The P&C insurance operating system — underwriting, claims, billing, policy |
| [Duck Creek](https://www.duckcreek.com) 💰 | Cloud-native, composable P&C platform (SaaS-first) |
| [Sapiens](https://sapiens.com) 💰 | Core insurance across life, P&C, and reinsurance |
| [EIS Group](https://www.eisgroup.com) 💰 | Cloud-native core for P&C and life with an API-first model |
| [OneShield](https://www.oneshield.com) 💰 | Policy, billing, and claims software for specialty and P&C |

### Bancassurance & embedded insurance

| Platform | Description |
|---|---|
| [Cover Genius](https://covergenius.com) 💰 | Embedded insurance for retailers, travel, and rentals |
| [Qover](https://www.qover.com) 💰 | White-label, embedded insurance for platforms and banks |
| [bolttech](https://www.bolttech.io) 💰 | Insurance distribution and embedded solutions across APAC and beyond |
| [Tractable](https://tractable.ai) 💰 | AI computer vision for claims (photo-based estimates) |
| [FRISS](https://www.friss.com) 💰 | AI fraud and risk detection for underwriting and claims |
| [Lemonade](https://www.lemonade.com) 💰 | The AI-native, fully digital insurer — a reference for modern insurance UX |

### Insurance regulation

| Body | Description |
|---|---|
| [EIOPA](https://www.eiopa.europa.eu) | EU insurance and occupational-pensions authority — Solvency II |
| [AAOIFI](https://aaoifi.com) | Sets standards for **takaful** (Islamic insurance) accounting and governance |

**[⬆ back to top](#table-of-contents)**

---

## Trade Finance

> Trade finance oils **commerce between businesses and countries**: banks guarantee, finance, and de-risk the movement of goods and money. It is document-heavy (letters of credit, bills of lading, invoices), risk-heavy (country, credit, fraud, sanctions), and — after decades on paper — finally being digitized.

### Key concepts

- **The product set** — letters of credit (LCs), documentary collections, guarantees and standby LCs, invoice finance/factoring, forfaiting, and **supply chain finance** (buyer-approved early payment to suppliers).
- **The LC model** — the buyer's bank promises the seller's bank to pay on presentation of compliant documents; banks substitute their credit for the buyer's and check documents, not goods.
- **The documents** — commercial invoice, bill of lading (title to goods), packing list, inspection certificates; matching them to the LC is where fraud and errors live.
- **Rules** — UCP 600 (LCs), URDG 758 (guarantees), URC 522 (collections) from the ICC.
- **Digitalization** — electronic bills of lading (eBL), digital trade platforms, and machine-readable documents are collapsing days of paper handling into hours.
- **Risk controls** — every party screened for sanctions/AML; trade is a known channel for sanctions evasion.

### Trade networks & document platforms

| Platform | Description |
|---|---|
| [SWIFT](https://www.swift.com) ⭐ | The messaging backbone for trade finance (MT7xx series) |
| [Bolero](https://www.bolero.net) 💰 | Digital trade platform for eBLs and trade document exchange |
| [Traydstream](https://www.traydstream.com) 💰 | AI-powered trade-document checking against LC terms |
| [Enigio](https://www.enigio.com) 💰 | Digital original documents (trace:original) for eBLs and trade |
| [ICC](https://iccwbo.org) ⭐ | Publishers of the trade rules (UCP 600, URDG, URC) every product references |

### Supply chain finance

| Platform | Description |
|---|---|
| [Taulia](https://taulia.com) 💰 | Working-capital and dynamic discounting platform (part of SAP) |
| [C2FO](https://c2fo.com) 💰 | Working-capital marketplace where suppliers set their own discount |
| [PrimeRevenue](https://www.primerevenue.com) 💰 | Supply-chain-finance platform for large corporates and their suppliers |
| [Demica](https://www.demica.com) 💰 | Working-capital solutions for banks |
| [Orbian](https://www.orbian.com) 💰 | Supply-chain finance and payments across buyer/supplier networks |

**[⬆ back to top](#table-of-contents)**

---

## Domestic & International Remittance

> Remittance is the **most competitive corner of payments**: customers compare speed, price, and transparency per corridor. Domestic money moves over national rails in seconds; international money moves over correspondent networks in hours-to-days (SWIFT gpi is shrinking that). The 2026 battleground is **instant, transparent, and interoperable cross-border payments**.

### Key concepts

- **Domestic rails** — ACH (US), FedNow/RTP (US instant), SEPA/SEPA Instant (EU), Faster Payments (UK), UPI/IMPS (India), Zengin (Japan), RTGS for large-value.
- **Cross-border** — correspondent banking (a chain of nostro/vostro accounts), SWIFT gpi (tracked, faster), and a fast-growing set of alternative networks.
- **FX is the cost** — the spread between mid-market and customer rate is where margins live; transparent pricing is the regulatory trend (and the Wise model).
- **Corridors** — every origin-destination pair has its own rails, liquidity, and compliance profile; "corridor engineering" is the craft.
- **Compliance** — remittances are AML/fraud-heavy (structuring, sanctions, mule accounts); screening and velocity rules are mandatory.
- **G20 target** — reduce global average cost of cross-border transfers; regulators pressure banks on speed and transparency.

### Consumer remittance

| Platform | Description |
|---|---|
| [Wise](https://wise.com) ⭐ 💰 | The transparent, mid-market-rate pioneer for personal and business transfers |
| [Remitly](https://www.remitly.com) 💰 | Digital remittance focused on speed and emerging-market corridors |
| [Western Union](https://www.westernunion.com) 💰 | The global cash and digital remittance network |
| [MoneyGram](https://www.moneygram.com) 💰 | Global money movement with strong cash-out networks |
| [WorldRemit (Zepz)](https://www.worldremit.com) 💰 | Digital remittance across 130+ countries |
| [Ria](https://www.ria.com) 💰 | Cash and digital remittance with broad agent network |
| [Xoom (PayPal)](https://www.xoom.com) 💰 | Fast digital remittance from the US |
| [TransferGo](https://www.transfergo.com) 💰 | European remittance and borderless payments |

### B2B cross-border & payments infrastructure

| Platform | Description |
|---|---|
| [Nium](https://www.nium.com) 💰 | Embedded cross-border payments and card issuance for businesses |
| [Thunes](https://www.thunes.com) 💰 | Cross-border network connecting wallets, banks, and mobile money |
| [TerraPay](https://terrapay.com) 💰 | Interoperable payments network across 100+ countries |
| [Airwallex](https://www.airwallex.com) 💰 | Global payments, FX, and treasury infrastructure for businesses |
| [Ebury](https://www.ebury.com) 💰 | FX and international payments for SMEs |
| [Convera](https://www.convera.com) 💰 | Enterprise cross-border payments and FX risk management |
| [dLocal](https://dlocal.com) 💰 | Local-payment-method aggregation across emerging markets |

### Cross-border infrastructure

| Tool | Description |
|---|---|
| [SWIFT gpi](https://www.swift.com/payments/global-payments-innovation) ⭐ | The global cross-border payment standard with tracking (gpi) |
| [Volante](https://www.volante.com) 💰 | Payments modernization and ISO 20022 processing for banks |
| [Finastra Payments](https://www.finastra.com) 💰 | Payment hub and corporate treasury solutions |

**[⬆ back to top](#table-of-contents)**

---

## Personal Banking

> **Retail/personal banking** is the mass-market engine: everyday accounts, cards, savings, loans, mortgages, and insurance sold through apps, branches, and call centers. The last decade's disruption came from **digital banks** (neobanks) that rebuilt the product around the phone, and from **open banking** letting third parties build on top of the same accounts.

### Key concepts

- **The product suite** — current account (the anchor), debit/credit cards, savings, personal loans, mortgages, insurance, and increasingly PFM and investing.
- **The economics** — NIM on balances plus fees; the current account is a loss leader that funds cross-sell.
- **Digital banks** — app-native challengers (Monzo, Revolut, N26, Chime, Starling) that iterate weekly and price transparently; they forced incumbents to modernize UX.
- **Personal financial management (PFM)** — budgeting, insights, and goal tracking; powered by account aggregation and now generative insights.
- **Regulation** — consumer protection, responsible lending, DDA fees transparency, and account-switching rights.

### Digital banks & challengers

| Bank | Notes |
|---|---|
| [Monzo](https://monzo.com) ⭐ | UK digital bank known for PFM, pots, and transparent pricing |
| [Revolut](https://www.revolut.com) ⭐ | The super-app — FX, cards, investing, crypto, and business products |
| [N26](https://n26.com) | European digital bank with banking license across the EU |
| [Chime](https://www.chime.com) | The largest US neobank — no-fee banking with early payday access |
| [Starling](https://www.starlingbank.com) | UK digital bank with strong SME and marketplace banking |
| [Varo](https://www.varomoney.com) | US mobile bank with its own national bank charter |
| [Current](https://current.com) | US neobank with teen and spending tools |
| [Zopa](https://www.zopa.com) | From P2P lending pioneer to licensed UK digital bank |

### Personal finance & budgeting tools

| Tool | Description |
|---|---|
| [YNAB](https://www.ynab.com) 💰 | The zero-based budgeting default for power users |
| [Rocket Money](https://www.rocketmoney.com) 💰 | Subscription management and bill negotiation |
| [Plaid-powered apps](https://plaid.com) ⭐ ☁️ | The aggregation layer under nearly every PFM tool |

**[⬆ back to top](#table-of-contents)**

---

## Corporate Banking

> **Corporate/wholesale banking** serves businesses, from SMEs to global corporates and financial institutions. The products are relationship-based and complex: cash management, trade and supply chain finance, lending and syndication, treasury services, escrow, and depositary. Relationships are managed by bankers who orchestrate a small army of product specialists — and the systems are accordingly heavier than retail.

### Key concepts

- **Segments** — SME, mid-market, large corporate, and financial institutions; each has its own KYC (CDD/EDD), credit appetite, and product needs.
- **Cash management** — collection and disbursement services: virtual accounts, cash pooling, sweeping, lockbox, and payment factories.
- **Treasury** — the corporate treasurer uses a **Treasury Management System (TMS)** for cash visibility, forecasting, FX hedging, and payments; banks integrate with it.
- **Trade & supply chain** — LCs, guarantees, invoice finance, and SCF (see [Trade Finance](#trade-finance)).
- **Lending** — term loans, revolving credit facilities (RCFs), syndicated loans, asset finance; all documented, collateralized, and monitored.
- **Corporate onboarding** — KYB (know your business) is harder than retail KYC: entities, ownership, authorized signatories, and UBOs.

### Treasury management systems

| Platform | Description |
|---|---|
| [Kyriba](https://www.kyriba.com) ⭐ 💰 | Cloud TMS — liquidity, payments, FX, and risk |
| [FIS Treasury](https://www.fisglobal.com) 💰 | The enterprise treasury and risk suite (Quantum, Wallstreet Suite) |
| [ION Treasury](https://www.iongroup.com/treasury/) 💰 | Corporate treasury, risk, and payments (Reval heritage) |
| [GTreasury](https://www.gtreasury.com) 💰 | TMS for mid-market and enterprise treasuries |
| [Broadridge](https://www.broadridge.com) 💰 | Investor-communications and securities processing for the corporate/FI complex |

### Corporate banking platforms & payments

| Platform | Description |
|---|---|
| [Finastra](https://www.finastra.com) 💰 | Corporate banking, payments, and lending software (Fusion) |
| [Temenos](https://www.temenos.com) 💰 | Core and digital for corporate and transaction banking |
| [nCino](https://www.ncino.com) 💰 | Commercial and small-business lending origination |
| [Bottomline](https://www.bottomline.com) 💰 | Business payments, treasury, and cash-management software |
| [SAP](https://www.sap.com) 💰 | ERP and payments integration for corporates and their banks |

**[⬆ back to top](#table-of-contents)**

---

## Conventional & Islamic Banking

> Islamic banking delivers the same customer outcomes — deposit, finance, protect, invest, move money — **without interest (riba), excessive uncertainty (gharar), or haram activities**. Money is a medium, not a commodity: banks earn by sharing profit and loss and by providing real services, under the supervision of a Shariah board. It is one of the fastest-growing segments globally, with a core in the Gulf, Southeast Asia, and increasingly the UK and Europe.

### Key concepts

- **The prohibition** — *riba* (interest), *gharar* (uncertainty), *maysir* (gambling), and investing in haram sectors (alcohol, tobacco, conventional finance, etc.).
- **The core contracts** —
  - **Murabaha** — cost-plus sale: the bank buys the asset and sells it to the customer at a disclosed markup (the workhorse of Islamic loans and cards).
  - **Ijara** — leasing: the bank owns and leases the asset; Islamic mortgages (Ijara wa-Iqtina).
  - **Musharakah** — partnership: both parties contribute capital and share profit/loss proportionally.
  - **Mudarabah** — profit-sharing: one party provides capital, the other management; the basis of Islamic deposits.
  - **Wakalah** — agency; **Qard** — benevolent interest-free loans; **Salam/Istisna** — forward and manufacturing contracts.
- **Sukuk** — Islamic "bonds" representing ownership of an asset or its usufruct, not debt.
- **Takaful** — Islamic insurance based on mutual contribution rather than conventional risk transfer.
- **Two delivery models** — **full-fledged Islamic banks** vs **Islamic windows** (a conventional bank running a Shariah-compliant subsidiary/line with a separate book).
- **Governance** — a **Shariah Supervisory Board** approves products, and standards come from **AAOIFI** (accounting and Shariah) and **IFSB** (prudential).

### Standards, bodies & education

| Body | Description |
|---|---|
| [AAOIFI](https://aaoifi.com) ⭐ | The accounting and Shariah standards body for Islamic finance |
| [IFSB](https://www.ifsb.org) ⭐ | Islamic Financial Services Board — prudential standards for the industry |
| [IsDB](https://www.isdb.org) | The Islamic Development Bank — development finance and industry leadership |
| [CIBAFI](https://www.cibafi.org) | The global association of Islamic financial institutions |
| [FATF](https://www.fatf-gafi.org) | Islamic banks follow the same AML/CFT standard as conventional — compliance is not waived |

### Islamic banking software & platforms

| Platform | Description |
|---|---|
| [Path Solutions iMAL](https://www.path-solutions.com) ⭐ 💰 | The dedicated Islamic core banking platform — Shariah-compliant modules end to end |
| [Temenos Islamic Banking](https://www.temenos.com/products/islamic-banking/) 💰 | Islamic core (Murabaha, Ijara, Musharakah, Mudarabah, Sukuk) on the Temenos platform |
| [Mambu](https://mambu.com) 💰 | Cloud core that supports Islamic product structures for digital-first lenders |
| [Shariah-compliant digital banks](https://www.sama.gov.sa) 💰 | Saudi Arabia leads regulation of digital Islamic banks (STC Pay, urpay) — study SAMA's framework |

### Islamic wealth & fintech

| Platform | Description |
|---|---|
| [Wahed](https://wahed.com) 💰 | The leading halal robo-advisor for global investors |
| [Zoya](https://zoya.finance) 💰 | The popular halal investing app — Shariah-screened stocks, ETFs, and funds |
| [Sukuk platforms & funds](https://www.isdb.org) | Development and sovereign sukuk markets are the institutional foundation of Islamic capital markets |

**[⬆ back to top](#table-of-contents)**

---

## Learning, Courses & Community

> The fastest way into banking is a mix of **regulation (the rules), products (the what), and systems (the how)**. The resources below keep practitioners current without needing an MBA in finance.

### Publications & community

| Resource | Description |
|---|---|
| [Finextra](https://www.finextra.com) 🆓 | The daily fintech and banking-technology news site — the industry default for practitioners |
| [The Banker](https://www.thebanker.com) | The Financial Times' banking publication — rankings, strategy, and deals |
| [Banking Dive](https://www.bankingdive.com) 🆓 | US-focused banking news and analysis |
| [American Banker](https://www.americanbanker.com) | The US banking trade paper of record |
| [Tearsheet](https://tearsheet.co) | Fintech and banking-insights publication |
| [The Finanser (Chris Skinner)](https://thefinanser.com) 🆓 | The long-running blog on the future of banking |

### Courses & credentials

| Resource | Description |
|---|---|
| [Wharton FinTech](https://online.wharton.upenn.edu) | Wharton Online's fintech programs covering innovation, payments, and disruption |
| [CFA Institute](https://www.cfainstitute.org) | The credential for investment and wealth professionals |
| [GARP](https://www.garp.org) | The FRM — the risk-management credential banks respect |
| [CFI (Corporate Finance Institute)](https://corporatefinanceinstitute.com) | Practical, role-based courses for banking and credit |
| [BIS Education & Research](https://www.bis.org/index.htm) | The deepest free source on payments, banking structure, and regulation |

---

## Contributing

Contributions are what keep a curated list alive. See [CONTRIBUTING.md](CONTRIBUTING.md) for what belongs here, the entry checklist, and how to run the link check before opening a pull request.

## Author

Built and maintained by [Seyhun Akyürek](https://github.com/seyhunak) — [seyhunakyurek.com](https://seyhunakyurek.com).

## License

Distributed under the [MIT License](LICENSE).

**Made with ❤️ and a lot of spreadsheets.**
