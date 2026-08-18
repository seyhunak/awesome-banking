<div align="center">

# 🏦 Awesome Banking [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A curated, production-first guide to the banking domain — products, payments, security, compliance, architecture, AI, low-code/no-code, and mobile design.**

Conventional & Islamic · Retail & Corporate · from account opening to remittance.

<!-- Repository badges -->

[![GitHub stars](https://img.shields.io/github/stars/seyhunak/awesome-banking?style=for-the-badge&logo=github&color=FFD700)](https://github.com/seyhunak/awesome-banking/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/seyhunak/awesome-banking?style=for-the-badge&logo=github&color=8A2BE2)](https://github.com/seyhunak/awesome-banking/network/members)
[![GitHub watchers](https://img.shields.io/github/watchers/seyhunak/awesome-banking?style=for-the-badge&logo=github&color=00BFFF)](https://github.com/seyhunak/awesome-banking/watchers)
[![GitHub contributors](https://img.shields.io/github/contributors/seyhunak/awesome-banking?style=for-the-badge&logo=github&color=FF69B4)](https://github.com/seyhunak/awesome-banking/graphs/contributors)

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

| | Knowledge & Design | | Products & Segments | | Regional Banking |
|---|---|---|---|---|---|
| 📚 | [Banking Fundamentals](#banking-fundamentals--domain-knowledge) | 💳 | [Accounts](#accounts) | 🇦🇪 | [Banking in the UAE](#banking-in-the-uae) |
| 🛡️ | [Security](#security) | 🏦 | [Savings & Deposits](#savings--deposits) | 🇸🇦 | [Banking in Saudi Arabia (KSA)](#banking-in-saudi-arabia-ksa) |
| ⚖️ | [Compliance & Regulation](#compliance--regulation) | 💳 | [Credit Cards](#credit-cards) | 🇪🇺 | [Banking in the EU](#banking-in-the-eu) |
| 🏗️ | [Banking Architecture](#banking-architecture) | 📝 | [Personal Loans](#personal-loans) | 🇬🇧 | [Banking in the UK](#banking-in-the-uk) |
| 📱 | [Mobile Banking Design](#mobile-banking-design) | 🏠 | [Mortgage](#mortgage) | | |
| 🧩 | [Low-Code & No-Code Tools](#low-code--no-code-tools) | 📈 | [Investment & Wealth](#investment--wealth) | | |
| 🤖 | [AI in Banking](#ai-in-banking) | 🧾 | [Insurance](#insurance) | | |
| 👥 | [Customers & Experience](#customers--experience) | 🌍 | [Trade Finance](#trade-finance) | | |
| 🪪 | [KYC & Customer Due Diligence](#kyc--customer-due-diligence) | 💸 | [Domestic & International Remittance](#domestic--international-remittance) | | |
| | | 👤 | [Personal Banking](#personal-banking) | | |
| | | 🏢 | [Corporate Banking](#corporate-banking) | | |
| | | 🕌 | [Conventional & Islamic Banking](#conventional--islamic-banking) | | |
| | | 🔓 | [Open Banking & Open Finance](#open-banking--open-finance) | | |
| | | 🧭 | [Core Sectors & Products](#core-sectors--products) | | |
| | | 🖥️ | [Core Banking Systems (CBS)](#core-banking-systems-cbs) | | |
| | | 🔀 | [Payment Gateways](#payment-gateways) | | |
| | | 📊 | [Asset-Liability Management (ALM)](#asset-liability-management-alm) | | |

🎓 [Learning, Courses & Community](#learning-courses--community)

🏦 [Bank & Fintech Directory](#bank--fintech-directory)

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
| [Euromoney Learning](https://www.euromoneylearning.com) 💰 | Structured courses on trade finance, treasury, and risk from the trade press |
| [The Financial Brand](https://thefinancialbrand.com) 🆓 | Retail-banking, digital, and marketing intelligence for banking leaders |

### Business models

| Model | Description |
|---|---|
| **Universal bank** | Retail + corporate + investment banking under one roof — the European and Asian default |
| **Retail / commercial bank** | Consumers and SMEs; the US community and regional model |
| **Investment bank** | Capital markets, advisory, trading, and research — deposit-taking not required |
| **Private bank** | Wealth management, advice, and bespoke products for high-net-worth clients |
| **Digital / neobank** | App-native challenger built on BaaS and open APIs |
| **Development bank** | State-backed long-term finance (e.g., IsDB, EIB, KfW) |
| **Islamic bank** | Shariah-compliant balance sheet (see [Conventional & Islamic Banking](#conventional--islamic-banking)) |

### Economics & ratios

| Term | Meaning |
|---|---|
| **NIM** | Net interest margin — the spread between what the bank pays for deposits and earns on loans |
| **ROE / ROTE** | Return on (tangible) equity — the shareholder performance yardstick |
| **CET1** | Common Equity Tier 1 — the highest-quality capital ratio (Basel floor: 4.5%) |
| **LCR** | Liquidity coverage ratio — high-quality liquid assets vs 30-day net outflows |
| **NSFR** | Net stable funding ratio — structural funding stability over one year |
| **Cost-to-income** | Operating cost ÷ income — the efficiency ratio every bank reports |
| **Provisioning** | Money set aside for expected loan losses (IFRS 9 / CECL) |
| **Pass-through** | How central-bank policy rates flow to deposit and lending rates |

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

### Identity & authentication

| Platform | Description |
|---|---|
| [Keycloak](https://www.keycloak.org) 🔓 | The open-source IAM standard — SSO, MFA, social login, and federation |
| [Auth0](https://auth0.com) ☁️ | Developer-first identity — drop-in SSO and MFA for customer apps |
| [Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id) ☁️ | The enterprise identity default in Microsoft shops (formerly Azure AD) |
| [Incognia](https://incognia.com) ☁️ | Location- and device-based fraud prevention for mobile banking |
| [BioCatch](https://www.biocatch.com) 💰 | Behavioral biometrics that catch account-takeover and mule behavior in real time |

### Fraud detection & prevention

| Platform | Description |
|---|---|
| [Feedzai](https://feedzai.com) ⭐ 💰 | AI-first transaction monitoring and fraud risk for payments, cards, and A2A |
| [Featurespace](https://www.featurespace.com) 💰 | Real-time behavioral analytics (Adaptive Behavioral Analytics) across the customer lifecycle |
| [Sift](https://sift.com) 💰 | Digital trust and fraud platform for account abuse, payments, and chargebacks |
| [NICE Actimize](https://www.niceactimize.com) ⭐ 💰 | The enterprise mainstay for fraud and AML across banking, cards, and brokerage |
| [DataVisor](https://www.datavisor.com) 💰 | Unsupervised machine learning that catches coordinated fraud rings early |
| [LexisNexis ThreatMetrix](https://risk.lexisnexis.com/products/threatmetrix) ☁️ | Digital identity network that fingerprints devices and behavior for risk scoring |
| [Signifyd](https://www.signifyd.com) 💰 | AI e-commerce fraud decisions with a chargeback guarantee |
| [Forter](https://www.forter.com) 💰 | Real-time fraud decisioning for payments and account creation |
| [Ravelin](https://www.ravelin.com) 💰 | Payment-risk and fraud platform for marketplaces and platforms |

### Application security & DevSecOps

| Tool | Description |
|---|---|
| [Snyk](https://snyk.io) ☁️ | Dependency, container, and code scanning wired into the CI/CD pipeline |
| [GitHub Advanced Security](https://github.com/features/security) 🔓 | Secret scanning, code scanning (CodeQL), and dependency review |
| [Burp Suite](https://portswigger.net/burp) 💰 | The standard tool for manual and automated web-app penetration testing |
| [OWASP ZAP](https://www.zaproxy.org) 🔓 | Free, open-source DAST for automated app-layer security testing |
| [Wazuh](https://wazuh.com) 🔓 | Open-source SIEM/XDR for log monitoring, alerting, and compliance |
| [Elastic Security](https://www.elastic.co/security) · [Splunk](https://www.splunk.com) 💰 | Enterprise SIEM platforms for security operations and threat hunting |

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
| [EU AML package / AMLA](https://www.consilium.europa.eu/en/policies/anti-money-laundering/) | EU | The single EU AML rulebook and the new AMLA supervisor (Frankfurt) |
| [DORA](https://digital-strategy.ec.europa.eu/en/policies/digital-finance) | EU | Digital Operational Resilience Act — ICT risk, resilience testing, and third-party oversight |
| [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) | EU | Risk-tiered rules for AI — high-risk systems include credit scoring |
| [Consumer Duty](https://www.fca.org.uk/firms/consumer-duty) | UK | The FCA conduct rule: deliver good outcomes for customers, and prove it |
| [SEC](https://www.sec.gov) | US | Securities regulation for banks' broker-dealer and advisory arms |
| [FINRA](https://www.finra.org) | US | Broker-dealer conduct, exams, and enforcement |
| [Model Risk Management (SR 11-7 → SR 26-2)](https://www.federalreserve.gov/supervisionreg/srletters/SR2602.htm) | US | Fed/OCC/FDIC guidance governing every model a bank runs |

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
| [Wolters Kluwer OneSumX](https://www.wolterskluwer.com/en/solutions/onesumx) 💰 | Regulatory reporting, risk, and compliance suite (FINREP/COREP, Basel, LCR/NSFR) |
| [Lucinity](https://www.lucinity.com) 💰 | AI copilots for AML investigations, SARs, and reporting |
| [Flagright](https://flagright.com) ☁️ | AML-compliance and fraud-detection APIs for modern stacks |
| [Sanction Scanner](https://sanctionscanner.com) ☁️ | Screening-as-an-API with low false-positive tuning |

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
| [Finastra](https://www.finastra.com) 💰 | Enterprise core | Fusion banking suite — a global heavyweight across retail, wholesale, and treasury |
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
| [10x Banking](https://www.10xbanking.com) 💰 | Cloud-native core | API-first, AI-enabled core powering Chase UK and NatWest |
| [Volaris](https://www.volarisgroup.com) 💰 | Cloud-native core | Event-driven, composable core built on Oracle technology |

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

### APIs, open banking & integration

| Tool | Description |
|---|---|
| [OpenAPI](https://www.openapis.org) ⭐ | The API-contract standard every bank's developer portal exposes |
| [Postman](https://www.postman.com) 💰 | API design, testing, documentation, and governance workflow |
| [Kong](https://konghq.com) ☁️ | The API gateway and platform layer for banking APIs |
| [MuleSoft](https://www.mulesoft.com) ☁️ | Enterprise integration connecting cores to channels and partners |
| [Akamai](https://www.akamai.com) · [Cloudflare](https://www.cloudflare.com) ☁️ | Edge security, DDoS protection, and API shielding |

### Enterprise architecture & standards

| Standard | Description |
|---|---|
| [BIAN](https://www.bian.org) ⭐ | Banking Industry Architecture Network — the shared service-landscape blueprint and API model for core banking |
| [TOGAF](https://www.opengroup.org/togaf) | The enterprise-architecture framework used to map bank target states |
| [ArchiMate](https://www.opengroup.org/archimate-forum) | The modeling language for architecture views and stakeholder communication |

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
| [Carbon Design System (IBM)](https://carbondesignsystem.com) 🔓 | Enterprise design system with strong data-dense, dashboard-grade patterns |
| [Polaris (Shopify)](https://polaris.shopify.com) 🔓 | Reference for merchant and small-business financial interfaces |
| [Primer (GitHub)](https://primer.style) 🔓 | A well-documented open-source design system with strong tokens |
| [GOV.UK Design System](https://design-system.service.gov.uk) 🔓 | The accessibility-and-consistency benchmark for regulated public services |

### UX patterns & inspiration

| Resource | Description |
|---|---|
| [Mobbin](https://mobbin.com) 💰 | Searchable screenshot library of real banking-app flows and screens |
| [UX Archive](https://uxarchive.com) 🆓 | Interaction-level reference for flows and micro-interactions |
| [Pttrns](https://pttrns.com) 💰 | Curated mobile UI patterns for app screens |
| [Dribbble](https://dribbble.com) 🆓 | Design inspiration and motion examples for finance and fintech |

### UX research & testing

| Tool | Description |
|---|---|
| [Figma](https://www.figma.com) ⭐ | The standard design tool — prototypes, design systems, and handoff |
| [Maze](https://maze.co) 💰 | Rapid usability testing on prototypes — catch confusion before code |
| [Optimal Workshop](https://www.optimalworkshop.com) 💰 | Card sorts and tree tests to validate navigation and information architecture |
| [UsabilityHub](https://usabilityhub.com) ☁️ | Quick five-second and preference tests on designs |
| [Overflow](https://overflow.io) 💰 | User-flow diagrams and handoff for multi-screen journeys |

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

### Document & workflow automation

| Platform | Description |
|---|---|
| [DocuSign](https://www.docusign.com) ☁️ | E-signature and agreement workflow — the default for account opening and loans |
| [Nintex](https://www.nintex.com) 💰 | Process automation, document generation, and e-forms |
| [Kissflow](https://kissflow.com) 💰 | Low-code workflow, case management, and approvals |
| [UiPath](https://www.uipath.com) 💰 | RPA — automating legacy mainframe and screen workflows |
| [Automation Anywhere](https://www.automationanywhere.com) 💰 | Enterprise RPA and intelligent automation |
| [Hyland OnBase](https://www.hyland.com) 💰 | Enterprise content and document management for banking |

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
| [Kasisto KAI](https://kasisto.com) 💰 | Conversational AI built specifically for banking — intents, flows, and PSD2-aware |
| [Boost.ai](https://www.boost.ai) 💰 | No-code conversational AI for financial-services customer service |

### AI governance & model risk

| Standard / Platform | Description |
|---|---|
| [Model Risk Management (SR 26-2)](https://www.federalreserve.gov/supervisionreg/srletters/SR2602.htm) ⭐ | The Fed/OCC/FDIC guidance (successor to SR 11-7) every model in a bank must satisfy |
| [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) | The US framework for trustworthy, governable AI |
| [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) | The EU's risk-tiered AI regulation — high-risk systems include credit scoring |
| [Credo AI](https://www.credo.ai) 💰 | AI-governance software for inventory, risk, and compliance |
| [Holistic AI](https://www.holisticai.com) 💰 | AI-risk assessment and remediation platform |

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

### Personalization & engagement

| Platform | Description |
|---|---|
| [Braze](https://www.braze.com) 💰 | Cross-channel customer engagement and lifecycle messaging |
| [Iterable](https://iterable.com) 💰 | Marketing automation and journey orchestration for digital banking |
| [SAP Emarsys](https://emarsys.com) 💰 | Personalization for high-volume B2C banking and commerce |

### Customer insights & analytics

| Tool | Description |
|---|---|
| [ThoughtSpot](https://www.thoughtspot.com) 💰 | Search-and-AI analytics for business teams |
| [Looker](https://cloud.google.com/looker) ☁️ | Embedded analytics and data modeling for banking products |
| [Tableau](https://www.tableau.com) 💰 | Visual analytics for operations and performance |
| [Mixpanel](https://mixpanel.com) 💰 | Product and funnel analytics for digital channels |

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
| [Sanction Scanner](https://sanctionscanner.com) ☁️ | Screening-as-an-API with low false-positive tuning |

### KYB & entity verification

| Platform | Description |
|---|---|
| [Dun & Bradstreet](https://www.dnb.com) ⭐ ☁️ | The global standard for business identity, credit, and ownership data |
| [Moody's Orbis (Bureau van Dijk)](https://www.bvdinfo.com) ☁️ | The company-and-ownership database behind corporate KYC |
| [OpenCorporates](https://opencorporates.com) 🔓 | Open company-registry data for verification and screening |
| [North Data](https://northdata.com) 🔓 | European company-registry intelligence |
| [Trulioo Business](https://www.trulioo.com) ☁️ | Business verification across 330+ data sources |

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
| [CHAPS](https://www.bankofengland.co.uk/payments/chaps) | UK | The UK's large-value real-time gross settlement |
| [Bacs](https://www.bacs.co.uk) | UK | The UK's batched direct-debit and direct-credit rail |
| [Zengin](https://www.zengin-net.jp/en/) | Japan | Japan's domestic interbank network |
| [PIX](https://www.bcb.gov.br/en/financialstability/pix_en) | Brazil | Brazil's instant-payments system — the global reference for adoption |

### Account identifiers & standards

| Standard | Description |
|---|---|
| [IBAN](https://www.iban.com) ⭐ | ISO 13616 — the international account-number format used across Europe and beyond |
| [BIC / SWIFT code](https://www.swift.com) | ISO 9362 — the bank identifier used with IBANs and SWIFT messaging |
| [EPC (European Payments Council)](https://www.europeanpaymentscouncil.eu) | Maintains the SEPA rulebooks and IBAN-validation standards |
| [ISO 20022](https://www.iso20022.org) | The message standard behind modern payments and account data |

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

### Deposit products

| Product | Description |
|---|---|
| Instant-access savings | Liquid, lower-rate — the everyday savings bucket |
| Money-market account | Rate tracks short-term money-market instruments; often used for excess liquidity |
| Term deposit / CD | Fixed term and rate; breaking early costs penalty or lost interest |
| Notice account | Withdrawal requires an advance-notice period |
| Fixed-rate / structured deposit | Fixed coupon, or return linked to an index or basket |
| Salary / premium account | Higher rate and perks conditional on salary direct-debit |
| Islamic profit-sharing deposit | Mudarabah-based — the Shariah-compliant alternative to interest |

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
| [i2c](https://www.i2cinc.com) 💰 | Global card issuing and processing platform for banks and brands |
| [Deserve](https://deserve.com) ☁️ | Credit-card issuing platform with credit lifecycle automation |

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

### Disputes & chargebacks

| Platform | Description |
|---|---|
| [Verifi (Visa)](https://www.verifi.com) 💰 | Visa's dispute-automation and chargeback-prevention suite |
| [Ethoca (Mastercard)](https://www.ethoca.com) 💰 | Consumer-collaboration dispute resolution and alerts |
| [Chargebacks911](https://chargebacks911.com) 💰 | Chargeback management, representment, and prevention services |

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

### Collections & debt recovery

| Platform | Description |
|---|---|
| [FICO Debt Manager](https://www.fico.com/en/products/fico-debt-manager) 💰 | The collections-and-recovery system used across US lenders |
| [TrueAccord](https://trueaccord.com) 💰 | Digital-first, consumer-friendly debt collection |
| [InDebted](https://indebted.com) 💰 | Digital collections with integrated payment plans |

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

### Valuation & property analytics

| Platform | Description |
|---|---|
| [HouseCanary](https://www.housecanary.com) 💰 | Property valuation and analytics for underwriting and portfolio risk |
| [Regrid](https://regrid.com) 💰 | Parcel-boundary and property data for appraisal and review workflows |

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

### Wealthtech & platform infrastructure

| Platform | Description |
|---|---|
| [FNZ](https://www.fnz.com) 💰 | The wealth-platform engine behind many banks' retail investing and pensions |
| [InvestCloud](https://www.investcloud.com) 💰 | Digital wealth-management platform — advice, portfolio, and client reporting |
| [Addepar](https://www.addepar.com) 💰 | Portfolio analytics for advisors, family offices, and private banks |
| [Temenos Wealth](https://www.temenos.com/products/wealth-management/) 💰 | Wealth core, advice, and digital on the Temenos platform |

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
| [Verisk](https://www.verisk.com) 💰 | Data, analytics, and decision solutions for P&C and bancassurance |
| [Origami Risk](https://www.origamirisk.com) 💰 | Risk-management and claims software for enterprises and insurers |

### Bancassurance & embedded insurance

| Platform | Description |
|---|---|
| [Cover Genius](https://covergenius.com) 💰 | Embedded insurance for retailers, travel, and rentals |
| [Qover](https://www.qover.com) 💰 | White-label, embedded insurance for platforms and banks |
| [bolttech](https://www.bolttech.io) 💰 | Insurance distribution and embedded solutions across APAC and beyond |
| [Tractable](https://tractable.ai) 💰 | AI computer vision for claims (photo-based estimates) |
| [FRISS](https://www.friss.com) 💰 | AI fraud and risk detection for underwriting and claims |
| [Lemonade](https://www.lemonade.com) 💰 | The AI-native, fully digital insurer — a reference for modern insurance UX |
| [wefox](https://www.wefox.com) 💰 | Digital insurance platform across Europe — distribution and embedded cover |

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
| [Surecomp](https://www.surecomp.com) 💰 | Trade-finance and treasury software for banks |
| [ITFA](https://www.itfa.org) | The trade association driving eBL and digital-trade standards |

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
| [OFX](https://www.ofx.com) 💰 | International transfers for consumers and SMEs with strong FX rates |
| [Payoneer](https://www.payoneer.com) 💰 | Cross-border payments for freelancers, marketplaces, and SMEs |

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
| [Ally](https://www.ally.com) | US digital bank — high-yield savings, no-fee checking, auto loans |
| [SoFi](https://www.sofi.com) | The US super-app — banking, investing, lending, and credit |
| [Marcus (Goldman Sachs)](https://www.marcus.com) | Online savings and personal loans from Goldman Sachs |
| [Bunq](https://www.bunq.com) | European mobile bank — multi-currency accounts and savings |
| [Tide](https://www.tide.co) | UK SME banking — accounts, invoicing, and expense tools |

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
| [SWIFT for Corporates](https://www.swift.com/corporates) ⭐ | Direct corporate connectivity to the SWIFT network |
| [EBICS](https://www.ebics.org) | The European file-exchange standard between corporates and banks |

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
| [IIFM](https://www.iifm.net) | International Islamic Financial Market — standardizes Islamic capital- and money-market products |
| [FATF](https://www.fatf-gafi.org) | Islamic banks follow the same AML/CFT standard as conventional — compliance is not waived |
| [ISRA](https://isra.my) | International Shari'ah Research Academy — research, journals, and training for Islamic finance |
| [Amanie Advisors](https://www.amanie.com) 💰 | The leading Shariah-advisory and audit firm across the Gulf and Asia |

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

## Open Banking & Open Finance

> Open banking is the **consent-based sharing of a customer's bank data with third parties** (account information and payment initiation). Open finance extends the same model beyond current accounts to loans, savings, cards, mortgages, pensions, and insurance; open data goes further into telecom, utilities, and beyond. The commercial prize is a **single, portable view of a customer's financial life** — and the death of data lock-in. PSD2 (EU) and the CMA order (UK) started the wave; PSD3/PSR, the US CFPB **Section 1033** rule, Australia's **CDR**, and Gulf frameworks are extending it.

### Key concepts

- **Consent is the product** — nothing is shared without the customer's explicit, revocable consent; the consent screen is the moment of trust.
- **AISP / PISP** — Account Information Service Providers read data; Payment Initiation Service Providers initiate payments from the customer's own account (bank-agnostic checkout).
- **PSD2 → PSD3 / PSR** — the EU's original open-banking directive is being replaced by PSD3 + the Payment Services Regulation (stricter APIs, stronger security, more participants).
- **UK CMA Order** — the world's first mandated open-banking regime; now run by the FCA and including Variable Recurring Payments (VRP) and Confirmation of Payee.
- **US Section 1033** — the CFPB's personal financial data rights rule: free, machine-readable access to bank data, with FDX as the industry API standard.
- **Open finance vs open data** — open banking was phase one; regulators are now extending the consent model to the whole financial (and beyond-financial) stack.
- **Standards matter more than regulation** — FAPI (financial-grade OAuth), OAuth 2.0, OIDC, mTLS, and PKCE are the technical substrate; Berlin Group/STET (EU) and OBIE (UK) define the API specs.
- **Aggregation is the on-ramp** — screen-scraping and token-based aggregation (Plaid, TrueLayer, Tink, Yapily) gave open banking its first products: PFM, credit decisions, and instant payment initiation.

### Regulations & frameworks by region

| Region | Framework | Notes |
|---|---|---|
| 🇪🇺 EU | [PSD2 → PSD3 / PSR](https://www.eba.europa.eu/regulation-and-policy/payment-services-and-electronic-money) ⭐ | The original open-banking directive and its successor; AISP/PISP access rights, SCA, and open-API mandates |
| 🇬🇧 UK | [Open Banking Ltd](https://www.openbanking.org.uk) ⭐ | The CMA-mandated regime — the world's reference implementation, now with VRP and Confirmation of Payee |
| 🇺🇸 US | [CFPB Section 1033](https://www.consumerfinance.gov/rules-policy/final-rules/required-rulemaking-on-personal-financial-data-rights/) | Personal financial data rights rule requiring free bank-data access; FDX API as the market standard |
| 🇦🇺 Australia | [CDR (Consumer Data Right)](https://www.cdr.gov.au) | The broadest consent-based data regime — banking first, then energy, telecom, and beyond |
| 🇮🇳 India | [Sahamati / Account Aggregator](https://sahamati.org.in) | The AA framework — licensed aggregators flow consent-based financial data (UPI-scale model) |
| 🇧🇷 Brazil | [Open Finance Brasil](https://openfinancebrasil.org.br) | Mandated open finance across banking, cards, FX, insurance, and investments |
| 🇸🇦 KSA | [SAMA Open Banking](https://www.sama.gov.sa/en-US/Pages/default.aspx) | SAMA's open-banking framework with AISP/PISP licensing and API standards |
| 🇦🇪 UAE | [CBUAE Open Banking](https://www.cbuae.gov.ae) | The UAE's framework sits inside its Payments Infrastructure (Aani instant payments, open APIs) |

### Standards & technology

| Standard | Description |
|---|---|
| [FAPI (Financial-grade API)](https://openid.net/wg/fapi/) ⭐ | The OAuth 2.0/OIDC profile with the security bar financial APIs require — mTLS, PKCE, high assurance |
| [OAuth 2.0](https://oauth.net) ⭐ | The delegation-and-authorization protocol every consent flow is built on |
| [OpenID Connect](https://openid.net/connect/) | Identity layer on top of OAuth — used for customer authentication at the bank |
| [Berlin Group](https://www.berlin-group.org) | The European payment-initiation and account-information API standard (NextGenPSD2) |
| [STET](https://www.stet.eu) | The French PSD2 API scheme — an alternative EU API specification |
| [FDX](https://www.fdx.org) | The Financial Data Exchange API — the de-facto US open-banking standard |
| [ISO 20022](https://www.iso.org) | The rich-data messaging standard open-banking APIs increasingly serialize to |

### Data access & aggregation platforms

| Platform | Notes |
|---|---|
| [Plaid](https://plaid.com) ⭐ | The US standard for consent-based account connection — auth, balances, transactions, identity |
| [TrueLayer](https://truelayer.com) ⭐ | European AIS/PIS with strong open-banking payment-initiation capabilities |
| [Tink](https://tink.com) ⭐ | European aggregation and payment initiation (part of Visa) |
| [Yapily](https://www.yapily.com) | Pan-European AIS/PIS API with rich coverage |
| [MX](https://www.mx.com) | Data platform and personalization layer for banks and fintechs |
| [Envestnet Yodlee](https://www.yodlee.com) | The veteran aggregation provider with deep transaction categorization |
| [Finicity](https://www.finicity.com) | US open-banking data (part of Mastercard) |
| [Flinks](https://flinks.com) | Canadian account connectivity and data platform |

### Use cases & commercial models

- **Bank-agnostic checkout** — pay from any account via PISP (TrueLayer/Tink-style) instead of card networks; lower merchant fees, instant settlement.
- **A credit view from real cash flow** — lenders underwrite from consented transaction data instead of (or alongside) bureau scores; the engine of affordability-based lending and thin-file credit.
- **PFM & consolidation** — aggregation turns a bank app (or a neobank, or a fintech) into the customer's single window on every account, card, and loan.
- **VRP / Confirmation of Payee** — variable recurring payments (sweeping, subscriptions) and payee-name checks cut fraud and unlock new recurring-payment products.
- **Identity & onboarding** — consented account data verifies income and identity, replacing paper bank statements in KYC and underwriting.
- **Premium API services** — banks monetize the same data as a **read/write/verification** API tier (balance checks, income verification, fraud alerts) — the BaaS-adjacent "open banking as a business line."

### Learning & reference

| Resource | Description |
|---|---|
| [The Paypers](https://www.thepaypers.com) | The leading trade publication tracking open banking, open finance, and payments |
| [BAI](https://www.bai.org) | Banking-industry research and events with strong digital/API coverage |
| [Berlin Group](https://www.berlin-group.org) | The reference API specs for European open banking |
| [Open Banking Ltd](https://www.openbanking.org.uk) | The UK regime's standards, specifications, and developer resources |

**[⬆ back to top](#table-of-contents)**

---

## Core Sectors & Products

> Banks organize around three core sectors by customer — **retail** (individuals), **corporate** (businesses), and **investment** (institutional clients). Universal banks run all three under one roof; the products, risk profiles, and regulators differ sharply between them. Every other section of this guide is a deeper dive into a product or capability that lives inside one of these sectors.

### Retail banking

> Services for individuals: savings/checking accounts, mortgages, and personal loans.

- **Mass-market distribution** — branches, apps, and cards; the lowest-margin but most stable funding base (deposits).
- **Product stack** — accounts, cards, savings, mortgages, and personal loans; cross-sell is the growth engine.
- **See also** — [Accounts](#accounts), [Savings & Deposits](#savings--deposits), [Credit Cards](#credit-cards), [Personal Loans](#personal-loans), [Mortgage](#mortgage), [Personal Banking](#personal-banking).

### Corporate banking

> Services for businesses: commercial loans, trade finance, and cash management.

- **Relationship-led** — fewer, larger clients with dedicated relationship managers and treasury teams.
- **Product stack** — commercial and SME lending, trade finance, cash management, FX, and payments.
- **See also** — [Corporate Banking](#corporate-banking), [Trade Finance](#trade-finance), [Domestic & International Remittance](#domestic--international-remittance).

### Investment banking

> Capital raising, mergers and acquisitions (M&A), and trading of assets.

- **Advisory & capital markets** — M&A and restructuring advisory; equity/debt issuance (IPO) via the capital-markets desks.
- **Markets** — trading (FICC, equities) for clients and for the bank's own book.
- **See also** — [Investment & Wealth](#investment--wealth), [Banking Fundamentals & Domain Knowledge](#banking-fundamentals--domain-knowledge).

| Reference | Notes |
|---|---|
| [Goldman Sachs Investment Banking](https://www.goldmansachs.com/what-we-do/investment-banking/) | Advisory, capital raising, and financing |
| [Morgan Stanley Investment Banking](https://www.morganstanley.com/what-we-do/investment-banking) | M&A and capital-markets advisory |
| [J.P. Morgan Investment Banking](https://www.jpmorgan.com/investment-banking) | Global advisory and capital markets |

**[⬆ back to top](#table-of-contents)**

---

## Core Banking Systems (CBS)

> The **central software backend** that processes a bank's daily transactions — deposits, withdrawals, loans, and interest — and updates the **general ledger**. "Core" literally means the system of record for accounts and balances; every channel (app, branch, ATM) and every product is a front-end to it. Replacing the core is the industry's hardest IT project.

### Key concepts

- **System of record** — the CBS holds the authoritative account, balance, and ledger state; channels and analytics read from and write to it.
- **Posting & ledgering** — every transaction posts to the general ledger with double-entry bookkeeping; balances are the running result.
- **Products as code** — modern cores (Thought Machine Vault, Mambu) model products as code/config rather than hard-coded modules.
- **Batch vs real-time** — legacy cores reconcile overnight in batches; cloud-native cores post in real time with event streams.
- **Modernization** — banks use the *strangler pattern* (new core alongside old, cutting over account by account) and API-first vendor cores to de-risk replacement.

### What a CBS does

| Function | Description |
|---|---|
| Account management | Open, maintain, and close accounts; product assignment and eligibility |
| Deposits & withdrawals | Post transactions, accruals, and interest across accounts |
| Loans & credit | Originate, service, and collect loans; amortization schedules |
| General ledger | Double-entry posting, trial balance, and financial reporting |
| Customer & limits | Party records, product limits, fees, and pricing |
| Payments interface | Hand off to payment rails and gateways for clearing and settlement |

### Major CBS platforms

| Platform | Model | Notes |
|---|---|---|
| [Temenos Transact](https://www.temenos.com) ⭐ 💰 | Enterprise core | The global market leader (T24 lineage), now cloud-native |
| [Finastra](https://www.finastra.com) ⭐ 💰 | Enterprise core | Fusion banking suite — the other global heavyweight across retail, wholesale, and treasury |
| [Thought Machine Vault](https://www.thoughtmachine.net) 💰 | Cloud-native core | Products as code (smart contracts); used by Lloyds, Atom, Standard Chartered |
| [Mambu](https://mambu.com) 💰 | Cloud-native core | API-first SaaS core for deposits, lending, and payments |
| [FIS](https://www.fisglobal.com) 💰 | Enterprise core | US powerhouse across retail/commercial banking and payments |
| [Fiserv / Finxact](https://www.fiserv.com) 💰 | Enterprise core | Community/regional mainstay; Finxact is its cloud-native core |
| [Jack Henry](https://www.jackhenry.com) 💰 | Enterprise core | The dominant core for US community banks and credit unions |
| [Oracle FLEXCUBE](https://www.oracle.com/industries/financial-services/flexcube/) 💰 | Enterprise core | Global retail/corporate core, strong in emerging markets |
| [Infosys Finacle](https://www.edgeverve.com/finacle/) 💰 | Enterprise core | India-origin global core with deep banking-process coverage |
| [TCS BaNCS](https://www.tcs.com/bancs) 💰 | Enterprise core | Large-scale retail, payments, and corporate banking platform |
| [Avaloq](https://www.avaloq.com) 💰 | Wealth core | The core of choice for private banking and wealth management |
| [Skaleet](https://www.skaleet.com) 💰 | Modular core | Composable, modular core for digital banks and EMIs |
| [Nymbus](https://nymbus.com) ☁️ | Neobank-in-a-box | Digital bank and core platform for fast launches |
| [10x Banking](https://www.10xbanking.com) 💰 | Cloud-native core | API-first core powering Chase UK and NatWest |
| [Volaris](https://www.volarisgroup.com) 💰 | Cloud-native core | Event-driven, composable core built on Oracle technology |

### Selection & vendor intelligence

| Resource | Notes |
|---|---|
| [Celent](https://www.celent.com) | The analyst house famous for core-banking vendor evaluations and the XCelent awards |
| [BIAN](https://www.bian.org) | The shared service-landscape blueprint and API model for modern core architecture |

**[⬆ back to top](#table-of-contents)**

---

## Payment Gateways

> The software and networks that **move money** between customers, merchants, banks, and countries. A gateway is the connective layer that hands a payment from an app, merchant, or bank to a rail (ACH, cards, wires, instant schemes) and returns status. The term spans merchant gateways (online checkout), acquiring processors, and the money-movement networks themselves.

### Key concepts

- **Rails vs gateways** — rails are the underlying settlement networks (ACH, SWIFT, Fedwire, card schemes); gateways and PSPs are the layers that route, authorize, and reconcile payments over them.
- **Authorization vs settlement** — cards are authorized (hold) at checkout, then settled (captured) later; other rails settle directly.
- **Clearing vs settlement** — clearing is the exchange/processing of payment instructions; settlement is where funds become final (netting between banks).
- **Acquiring** — the merchant's side of card payments: acquiring bank, processor, and scheme fees.

### Merchant gateways & PSPs

| Platform | Notes |
|---|---|
| [Stripe](https://stripe.com) ⭐ | The developer default for online payments — checkout, billing, payouts |
| [Adyen](https://www.adyen.com) ⭐ | Unified commerce payments at global scale |
| [Checkout.com](https://www.checkout.com) | Enterprise acquiring and alternative payments |
| [PayPal](https://www.paypal.com) | The consumer wallet and merchant checkout network |
| [Braintree](https://www.braintreepayments.com) | PayPal's developer-first payment gateway |
| [Worldpay](https://www.worldpay.com) | One of the largest global acquiring networks |
| [Global Payments](https://www.globalpayments.com) | Omnichannel acquiring and issuer processing |
| [ACI Worldwide](https://www.aciworldwide.com) | Enterprise real-time payment and acquiring software |
| [Rapyd](https://www.rapyd.net) | Local-payment-network aggregation across 100+ countries |
| [Mollie](https://www.mollie.com) | European gateway popular with SMBs |
| [Paddle](https://www.paddle.com) | Merchant-of-record checkout for software |
| [Nuvei](https://www.nuvei.com) | Global acquiring and alternative-payment processing |
| [PPRO](https://www.ppro.com) | Alternative-payment-method aggregation |
| [dLocal](https://dlocal.com) | Local payment methods across emerging markets |
| [Wise Platform](https://wise.com/platform/) | Embedding cross-border payments and multi-currency accounts |
| [Square](https://squareup.com) | Card-present and online payments for small business |

### Rails & networks

| Rail | Region | Notes |
|---|---|---|
| [ACH (NACHA)](https://www.nacha.org) ⭐ | US | The batched direct-deposit / bill-pay rail |
| [Fedwire](https://www.frbservices.org/resources/financial-services/wires/) | US | The Fed's real-time gross-settlement wire for large-value transfers |
| [FedNow](https://www.frbservices.org/financial-services/fednow) | US | The Fed's 24/7 instant-payment rail |
| [RTP (The Clearing House)](https://www.theclearinghouse.org/payments/rtp) | US | Real-time payments from US banks |
| [SEPA](https://www.ecb.europa.eu/paym/integration/retail/sepa/html/index.en.html) | EU | Euro credit transfers and direct debits; SEPA Instant for real time |
| [UK Faster Payments](https://www.fasterpayments.org.uk) | UK | The UK's near-instant 24/7 interbank rail |
| [SWIFT](https://www.swift.com) | Global | Correspondent messaging for cross-border payments |

**[⬆ back to top](#table-of-contents)**

---

## Asset-Liability Management (ALM)

> The discipline of **balancing a bank's deposits (liabilities) against its loans (assets)** to manage liquidity and interest-rate risk. ALM protects net interest margin (NIM), ensures the bank can fund itself in a crisis (LCR/NSFR), and is owned by the ALCO committee. It is the balance-sheet counterpart to the capital rules covered in Compliance & Regulation.

### Key concepts

- **Net interest income (NII) / margin (NIM)** — the core earnings engine: interest earned on assets minus interest paid on liabilities.
- **Interest-rate risk** — repricing/gap risk (assets and liabilities reprice at different times), basis risk, and duration risk; measured via gap analysis, duration, and EVE (economic value of equity).
- **Liquidity risk** — can the bank meet withdrawals and maturities? Measured by LCR (30-day) and NSFR (structural) under Basel III.
- **Funds transfer pricing (FTP)** — attributing funding cost/benefit to business lines so each product's true margin is visible; ALM sets the internal yield curve.
- **ALCO** — the asset-liability committee (treasury, finance, risk) that owns balance-sheet mix, hedging, and the contingency funding plan.
- **Stress testing** — running the balance sheet against rate shocks and liquidity scenarios (ICAAP/ILAAP exercises).

### ALM & treasury systems

| System | Notes |
|---|---|
| [Murex](https://www.murex.com) ⭐ 💰 | The leading treasury, ALM, and risk system for large banks |
| [Calypso](https://www.calypso.com) 💰 | Treasury, collateral, and risk management across markets |
| [QRM](https://www.qrm.com) 💰 | Dedicated ALM and liquidity-management platform |
| [Kaufman Hall](https://www.kaufmanhall.com) 💰 | ALM, budgeting, and balance-sheet planning (strong in US banking) |
| [Intellect iGTB](https://www.intellectdesign.com/igtb/) 💰 | Global transaction-banking and treasury suite |
| [Wall Street Systems](https://www.wallstreetsystems.com) 💰 | Treasury, payments, and liquidity management |
| [Oracle Financial Services](https://www.oracle.com) 💰 | ALM, FTP, and liquidity-risk analytics on the Oracle suite |
| [FIS](https://www.fisglobal.com) 💰 | Integrated treasury, ALM, and risk platforms |

### Data & reference

| Resource | Notes |
|---|---|
| [FRED](https://fred.stlouisfed.org) 🆓 | Yield-curve and interest-rate data for ALM analysis and FTP curve construction |
| [Basel III](https://www.bis.org/bcbs/basel3.htm) ⭐ | The LCR/NSFR framework that ALM exists to satisfy |

**[⬆ back to top](#table-of-contents)**

---

## Banking in the UAE

> The UAE is the Gulf's **financial hub**: two international financial centres (DIFC in Dubai, ADGM in Abu Dhabi) with common-law courts, a dual regulator (CBUAE for onshore banking, DFSA/FSRA for the centres), and an aggressive push on **digital payments (Aani instant payments) and open banking**. It is also the region's richest Islamic-banking market.

### Key concepts

- **Dual banking** — onshore banks are licensed by the **Central Bank of the UAE (CBUAE)**; international institutions can instead operate from **DIFC (DFSA)** or **ADGM (FSRA)** under common law with more liberal rules.
- **Ownership & regulation** — foreign banks operate through branches or locally incorporated subsidiaries; CBUAE regulates retail, wholesale, and Islamic banking (the same window).
- **Payments** — **UAESWITCH** is the national payments switch; **Aani** (Al Etihad Payments) is the instant-payment rail; cheques are processed via cheque imaging.
- **AML/CFT** — the UAE was on the FATF grey list (2022–2024) and has been removed since; the CBUAE's goAML portal is the mandatory filing channel.
- **Crypto & virtual assets** — VARA (Dubai) and ADGM's FSRA license crypto exchanges; the UAE is the most crypto-friendly jurisdiction in the Gulf.

### Regulators & infrastructure

| Body | Description |
|---|---|
| [CBUAE](https://www.centralbank.ae) ⭐ | The Central Bank of the UAE — onshore licensing, payments, and regulation |
| [DFSA](https://www.dfsa.ae) | Dubai Financial Services Authority — regulator of DIFC |
| [ADGM (FSRA)](https://www.adgm.com) | Abu Dhabi Global Market and its Financial Services Regulatory Authority |
| [DIFC](https://www.difc.ae) | The Dubai International Financial Centre — common-law jurisdiction for finance |
| [SCA](https://www.sca.gov.ae) | Securities and Commodities Authority — capital-markets oversight |
| [Aani](https://www.aani.ae) | The UAE's instant-payments platform (Al Etihad Payments) |

### Major banks

| Bank | Notes |
|---|---|
| [Emirates NBD](https://www.emiratesnbd.com) ⭐ | The largest bank in the UAE — retail, corporate, and Islamic (Emirates Islamic) |
| [First Abu Dhabi Bank (FAB)](https://www.fab.ae) ⭐ | The largest bank in the region by assets |
| [Abu Dhabi Commercial Bank](https://www.adcb.com) | Universal bank across retail, corporate, and wealth |
| [Dubai Islamic Bank](https://www.dib.ae) | The world's first full-fledged Islamic bank (1975) |
| [Mashreq](https://www.mashreqbank.com) | Dubai's oldest bank — home of Mashreq Neo and Mashreq Global Network |
| [ADIB](https://www.adib.ae) | Abu Dhabi Islamic Bank — Islamic retail and corporate banking |
| [Emirates Islamic](https://www.emiratesislamic.ae) | The Islamic banking arm of Emirates NBD |
| [RAKBANK](https://www.rakbank.ae) | Retail-focused bank strong in cards and personal finance |
| [Commercial Bank of Dubai](https://www.cbd.ae) | Retail and corporate banking group |

### Digital banks & fintech

| Platform | Notes |
|---|---|
| [Liv](https://www.liv.ae) | Emirates NBD's digital-first lifestyle bank |
| [Wio](https://www.wio.ae) | The region's first platform bank (FAB + partners) |
| [Zand](https://www.zand.ae) | The UAE's first integrated digital bank |
| [Al Maryah Community Bank](https://www.almaryahcb.ae) | Abu Dhabi digital bank focused on lending |

**[⬆ back to top](#table-of-contents)**

---

## Banking in Saudi Arabia (KSA)

> Saudi Arabia runs the Gulf's **largest banking market** and is the epicentre of Islamic finance. SAMA (the central bank) regulates a concentrated system of mega-banks plus a fast-growing wave of **digital banks** (STC Pay, D360, Rize, Meem, Tahaluf) under a dedicated framework. Payments run on **mada** (cards), **SADAD** (bill payments), **SARIE** (RTGS) and **SPI** (instant payments).

### Key concepts

- **Islamic is default** — most Saudi banks operate Islamic windows or fully Shariah-compliant books; Al Rajhi and Alinma are fully Islamic.
- **Concentration** — the top ten banks (SNB, Al Rajhi, Riyad, SABB, BSFR, ANB, Alinma, SAIB, Albilad, Aljazira) dominate; mergers (NCB–Samba → SNB; SABB–Alawwal) created megabanks.
- **Payments** — **mada** is the domestic debit/card scheme; **SADAD** is the ubiquitous bill-payment platform; **SARIE** moves large values in real time; **SPI** powers instant person-to-person transfers.
- **Vision 2030** — the National Transformation Program pushes digitization, fintech licensing, and open banking; the target is 70% cashless transactions.
- **Open banking** — SAMA published an open-banking framework; banks must expose APIs under its standards.

### Regulators & infrastructure

| Body | Description |
|---|---|
| [SAMA](https://www.sama.gov.sa) ⭐ | Saudi Central Bank — licensing, payments, and monetary policy |
| [CMA](https://cma.org.sa) | Capital Market Authority — securities, asset management, and fintech |
| [mada](https://www.mada.com.sa) | The Saudi domestic card scheme |
| [SADAD](https://www.sadad.com) | The national bill-payment and presentment system |
| [SARIE / SPI](https://www.sama.gov.sa) | Real-time gross settlement and instant-payments infrastructure |

### Major banks

| Bank | Notes |
|---|---|
| [Al Rajhi Bank](https://www.alrajhibank.com.sa) ⭐ | The largest Islamic bank in the world by market value |
| [SNB](https://www.snb.com.sa) ⭐ | Saudi National Bank — the largest by assets (NCB + Samba merger) |
| [Riyad Bank](https://www.riyadbank.com) | Universal bank with a strong corporate franchise |
| [SABB](https://www.sabb.com) | HSBC-affiliated (merged with Alawwal) |
| [Alinma Bank](https://www.alinma.com) | Fully Islamic retail and corporate bank |
| [Banque Saudi Fransi](https://www.alfransi.com.sa) | Universal bank strong in corporate and trade services |
| [Arab National Bank](https://www.anb.com.sa) | Retail, corporate, and treasury banking |
| [Bank Albilad](https://www.bankalbilad.com) | Islamic retail bank |

### Digital banks & fintech

| Platform | Notes |
|---|---|
| [STC Pay](https://www.stcpay.com.sa) | The kingdom's digital wallet from stc group |
| [D360 Bank](https://d360.com.sa) | Digital bank backed by Saudi institutional investors |
| [Rize](https://rize.sa) | Digital SME bank focused on micro-businesses |
| [Meem](https://www.meem.sa) | Alinma's digital bank |
| [Tahaluf](https://www.tahaluf.sa) | Digital bank from stc group |
| [Lesan](https://lesan.sa) | Digital bank backed by the PIF ecosystem |

**[⬆ back to top](#table-of-contents)**

---

## Banking in the EU

> The EU is the world's **most integrated banking market**: a single banking license (passporting), harmonized rulebooks (CRR/CRD, PSD, GDPR, DORA, AML), one payments market (SEPA), and a centralized supervisor for the largest banks (the ECB). The 2020s agenda is the **Capital Markets Union, PSD3/PSR, DORA, and the single AML authority (AMLA)**.

### Key concepts

- **Single passport** — a license in one member state grants access across the EEA; banks and EMIs passport through subsidiaries or branches.
- **Two-layer supervision** — the **ECB/SSM** directly supervises ~110 significant banks; national authorities (e.g., BaFin, ACPR, Banca d'Italia) handle the rest under EBA convergence.
- **Payments** — **SEPA** standardizes euro credit transfers and direct debits; **SEPA Instant** and **TIPS** deliver near-real-time euro payments; local schemes (iDEAL in NL, BLIK in PL, Bizum in ES) persist for domestic use.
- **The 2020s rulebook** — **PSD3 + PSR** (successor to PSD2), **DORA** (ICT resilience), the **AML package** (single rulebook + AMLA in Frankfurt), **CRR3/CRD6** (Basel III final), **MiFID II/MiFIR**, **GDPR**, and the **AI Act**.
- **Open banking** — PSD2's AISP/PISP access rights made the EU the global leader in open-banking APIs (Tink, TrueLayer, Yapily, Plaid EU).

### Regulators & infrastructure

| Body | Description |
|---|---|
| [ECB](https://www.ecb.europa.eu) ⭐ | Monetary policy and direct supervision of significant euro-area banks |
| [EBA](https://www.eba.europa.eu) ⭐ | The rulebook-setter for banking, payments, and AML convergence |
| [ESMA](https://www.esma.europa.eu) | Securities and markets regulation (MiFID II, EMIR) |
| [EIOPA](https://www.eiopa.europa.eu) | Insurance and occupational pensions (Solvency II) |
| [EPC](https://www.europeanpaymentscouncil.eu) | Maintains the SEPA schemes and rulebooks |
| [AMLA](https://finance.ec.europa.eu/financial-crime/anti-money-laundering-and-countering-financing-terrorism_en) | The new EU AML authority (Frankfurt, operational from 2025–2028) |

### Payment rails & schemes

| Rail / Scheme | Region | Notes |
|---|---|---|
| [SEPA / SEPA Instant](https://www.ecb.europa.eu/paym/integration/retail/sepa/html/index.en.html) ⭐ | Euro area | Standardized euro credit transfers and instant payments |
| [TARGET Services (T2 / TIPS)](https://www.ecb.europa.eu/paym/target/html/index.en.html) | Euro area | Large-value RTGS (T2) and instant settlement (TIPS) in central bank money |
| [iDEAL](https://www.ideal.nl/en/) | NL | The Dutch instant online-payments default |
| [BLIK](https://www.blik.com) | PL | Poland's mobile instant-payment standard |
| [Bizum](https://bizum.es) | ES | Spain's mobile P2P and payment-scheme standard |
| [girocard](https://www.girocard.eu) | DE | The German debit-card scheme |

### Notable players

| Institution | Notes |
|---|---|
| [Revolut](https://www.revolut.com) ⭐ | The EU super-app with a Lithuanian banking license (passported) |
| [N26](https://n26.com) | Fully licensed digital bank (BaFin) |
| [Bunq](https://www.bunq.com) | Dutch digital bank with multi-currency and sustainability focus |
| [Adyen](https://www.adyen.com) | Dutch acquiring and payments infrastructure leader |
| [Klarna](https://www.klarna.com) | Swedish BNPL and payments company |
| [Deutsche Bank](https://www.db.com) | The largest German bank |
| [BNP Paribas](https://group.bnpparibas.com) | The largest euro-area bank group |
| [ING](https://www.ing.com) | Dutch universal bank and digital-banking leader |
| [Santander](https://www.santander.com) | Global universal bank headquartered in Spain |
| [BBVA](https://www.bbva.com) | Spanish bank with a strong digital and BaaS arm |
| [Intesa Sanpaolo](https://www.intesasanpaolo.com) | Italy's largest retail bank |

**[⬆ back to top](#table-of-contents)**

---

## Banking in the UK

> The UK is one of the world's **deepest and most competitive banking markets** — a global hub for wholesale finance, a hyper-competitive retail market that produced the modern neobank, and the birthplace of **open banking** (CMA order) and **faster payments**. Regulation is split between the Bank of England/PRA (prudential) and the FCA (conduct), with the Payment Systems Regulator (PSR) overseeing payment systems.

### Key concepts

- **Twin-peaks regulation** — the **PRA** (Bank of England) supervises prudential soundness; the **FCA** regulates conduct and consumer protection; the **PSR** regulates payment systems.
- **Open banking** — the CMA-mandated regime made the UK the world's reference implementation; it now includes **Variable Recurring Payments (VRP)** and Confirmation of Payee.
- **Payments** — **Faster Payments** (24/7 instant), **Bacs** (batched direct debit/credit), **CHAPS** (large-value RTGS), and the long-planned **New Payments Architecture (NPA)**.
- **Consumer protection** — the **Consumer Duty** (fair-value rule), FSCS deposit protection (£85,000), and the Senior Managers & Certification Regime (SMCR) define how banks behave.
- **Challenger ecosystem** — Monzo, Starling, Revolut, Chase UK, Zopa, Kroo, Atom, and ClearBank make the UK the most competitive digital-banking market in Europe.

### Regulators & infrastructure

| Body | Description |
|---|---|
| [Bank of England](https://www.bankofengland.co.uk) ⭐ | Central bank, monetary policy, and financial stability |
| [PRA](https://www.bankofengland.co.uk/prudential-regulation) | Prudential Regulation Authority — banks, insurers, and major investment firms |
| [FCA](https://www.fca.org.uk) ⭐ | Conduct and consumer-protection regulator |
| [PSR](https://www.psr.org.uk) | Payment Systems Regulator |
| [FSCS](https://www.fscs.org.uk) | Deposit-protection scheme (£85,000 per person per institution) |
| [Open Banking Ltd](https://www.openbanking.org.uk) | The regime's standards and operating entity |

### Payment rails

| Rail | Description |
|---|---|
| [Faster Payments](https://www.bankofengland.co.uk/payments) | The UK's near-instant 24/7 interbank rail |
| [CHAPS](https://www.bankofengland.co.uk/payments/chaps) | Large-value real-time gross settlement |
| [Bacs](https://www.bacs.co.uk) | Batched direct-debit and direct-credit rail |
| [New Payments Architecture](https://www.bankofengland.co.uk/payments) | The future NPA settlement platform being implemented |

### Notable players

| Institution | Notes |
|---|---|
| [Monzo](https://monzo.com) ⭐ | The PFM-focused neobank with a UK banking license |
| [Starling Bank](https://www.starlingbank.com) | Digital bank strong in SME and marketplace banking |
| [Chase UK](https://www.chase.co.uk) | JPMorgan's UK retail app — cashback and savings |
| [Barclays](https://www.barclays.co.uk) | The largest UK retail bank |
| [Lloyds](https://www.lloydsbank.com) | The largest UK retail franchise |
| [HSBC UK](https://www.hsbc.co.uk) | Global bank with a strong UK retail arm |
| [NatWest](https://www.natwest.com) | The UK's biggest business bank |
| [Nationwide](https://www.nationwide.co.uk) | The UK's largest building society |
| [Virgin Money](https://www.virginmoney.com) | Full-service bank now part of Nationwide |
| [Kroo](https://www.kroo.com) | The sustainability-focused neobank |
| [ClearBank](https://www.clear.bank) | The clearing bank powering BaaS and fintech settlement |
| [Atom Bank](https://www.atombank.co.uk) | UK app-only savings and mortgage bank |
| [Allica](https://www.alliica.com) | Business bank for established SMEs |

**[⬆ back to top](#table-of-contents)**

---

## Bank & Fintech Directory

> Every bank and fintech company referenced across this guide, gathered into one place. Organized by region for licensed banks and by segment for fintech companies.

### Licensed banks — Middle East

| Bank | Country | Notes |
|---|---|---|
| [Emirates NBD](https://www.emiratesnbd.com) ⭐ | 🇦🇪 UAE | The largest bank in the UAE — retail, corporate, and Islamic |
| [First Abu Dhabi Bank (FAB)](https://www.fab.ae) ⭐ | 🇦🇪 UAE | The largest bank in the region by assets |
| [Abu Dhabi Commercial Bank](https://www.adcb.com) | 🇦🇪 UAE | Universal bank across retail, corporate, and wealth |
| [Dubai Islamic Bank](https://www.dib.ae) | 🇦🇪 UAE | The world's first full-fledged Islamic bank (1975) |
| [Mashreq](https://www.mashreqbank.com) | 🇦🇪 UAE | Dubai's oldest bank — Mashreq Neo and Global Network |
| [ADIB](https://www.adib.ae) | 🇦🇪 UAE | Abu Dhabi Islamic Bank |
| [Emirates Islamic](https://www.emiratesislamic.ae) | 🇦🇪 UAE | Islamic banking arm of Emirates NBD |
| [RAKBANK](https://www.rakbank.ae) | 🇦🇪 UAE | Retail-focused — cards and personal finance |
| [Commercial Bank of Dubai](https://www.cbd.ae) | 🇦🇪 UAE | Retail and corporate banking group |
| [Al Rajhi Bank](https://www.alrajhibank.com.sa) ⭐ | 🇸🇦 KSA | The largest Islamic bank in the world by market value |
| [SNB](https://www.snb.com.sa) ⭐ | 🇸🇦 KSA | Saudi National Bank — the largest by assets |
| [Riyad Bank](https://www.riyadbank.com) | 🇸🇦 KSA | Universal bank with a strong corporate franchise |
| [SABB](https://www.sabb.com) | 🇸🇦 KSA | HSBC-affiliated (merged with Alawwal) |
| [Alinma Bank](https://www.alinma.com) | 🇸🇦 KSA | Fully Islamic retail and corporate bank |
| [Banque Saudi Fransi](https://www.alfransi.com.sa) | 🇸🇦 KSA | Universal bank strong in corporate and trade services |
| [Arab National Bank](https://www.anb.com.sa) | 🇸🇦 KSA | Retail, corporate, and treasury banking |
| [Bank Albilad](https://www.bankalbilad.com) | 🇸🇦 KSA | Islamic retail bank |
| [IsDB](https://www.isdb.org) | 🌍 Multilateral | Islamic Development Bank — development finance |

### Licensed banks — Europe & UK

| Bank | Country | Notes |
|---|---|---|
| [Deutsche Bank](https://www.db.com) | 🇩🇪 Germany | The largest German bank |
| [BNP Paribas](https://group.bnpparibas.com) | 🇫🇷 France | The largest euro-area bank group |
| [ING](https://www.ing.com) | 🇳🇱 Netherlands | Dutch universal bank and digital-banking leader |
| [Santander](https://www.santander.com) | 🇪🇸 Spain | Global universal bank |
| [BBVA](https://www.bbva.com) | 🇪🇸 Spain | Spanish bank with a strong digital and BaaS arm |
| [Intesa Sanpaolo](https://www.intesasanpaolo.com) | 🇮🇹 Italy | Italy's largest retail bank |
| [Barclays](https://www.barclays.co.uk) | 🇬🇧 UK | The largest UK retail bank |
| [Lloyds](https://www.lloydsbank.com) | 🇬🇧 UK | The largest UK retail franchise |
| [HSBC UK](https://www.hsbc.co.uk) | 🇬🇧 UK | Global bank with a strong UK retail arm |
| [NatWest](https://www.natwest.com) | 🇬🇧 UK | The UK's biggest business bank |
| [Nationwide](https://www.nationwide.co.uk) | 🇬🇧 UK | The UK's largest building society |
| [Virgin Money](https://www.virginmoney.com) | 🇬🇧 UK | Full-service bank now part of Nationwide |
| [ClearBank](https://www.clear.bank) | 🇬🇧 UK | Clearing bank powering BaaS and fintech settlement |

### Digital banks & neobanks

| Bank | Country | Notes |
|---|---|---|
| [Monzo](https://monzo.com) ⭐ | 🇬🇧 UK | PFM-focused neobank with a UK banking license |
| [Starling Bank](https://www.starlingbank.com) ⭐ | 🇬🇧 UK | Digital bank strong in SME and marketplace banking |
| [Revolut](https://www.revolut.com) ⭐ | 🇬🇧/🇪🇺 UK/EU | The super-app — FX, cards, investing, crypto |
| [N26](https://n26.com) | 🇩🇪/🇪🇺 DE/EU | Fully licensed European digital bank |
| [Chime](https://www.chime.com) | 🇺🇸 US | The largest US neobank |
| [Varo](https://www.varomoney.com) | 🇺🇸 US | US mobile bank with its own national charter |
| [Current](https://current.com) | 🇺🇸 US | US neobank with teen and spending tools |
| [Ally](https://www.ally.com) | 🇺🇸 US | US digital bank — savings, checking, auto loans |
| [SoFi](https://www.sofi.com) | 🇺🇸 US | The US super-app — banking, investing, lending |
| [Marcus (Goldman Sachs)](https://www.marcus.com) | 🇺🇸 US | Online savings and personal loans from Goldman Sachs |
| [Chase UK](https://www.chase.co.uk) | 🇬🇧 UK | JPMorgan's UK retail app — cashback and savings |
| [Bunq](https://www.bunq.com) | 🇳🇱/🇪🇺 NL/EU | European mobile bank — multi-currency and sustainability |
| [Zopa](https://www.zopa.com) | 🇬🇧 UK | From P2P pioneer to licensed UK digital bank |
| [Tide](https://www.tide.co) | 🇬🇧 UK | UK SME banking — accounts, invoicing, expenses |
| [Kroo](https://www.kroo.com) | 🇬🇧 UK | The sustainability-focused neobank |
| [Atom Bank](https://www.atombank.co.uk) | 🇬🇧 UK | UK app-only savings and mortgage bank |
| [Allica](https://www.alliica.com) | 🇬🇧 UK | Business bank for established SMEs |
| [Liv](https://www.liv.ae) | 🇦🇪 UAE | Emirates NBD's digital-first lifestyle bank |
| [Wio](https://www.wio.ae) | 🇦🇪 UAE | The region's first platform bank (FAB + partners) |
| [Zand](https://www.zand.ae) | 🇦🇪 UAE | The UAE's first integrated digital bank |
| [Al Maryah Community Bank](https://www.almaryahcb.ae) | 🇦🇪 UAE | Abu Dhabi digital bank focused on lending |
| [STC Pay](https://www.stcpay.com.sa) | 🇸🇦 KSA | The kingdom's digital wallet from stc group |
| [D360 Bank](https://d360.com.sa) | 🇸🇦 KSA | Digital bank backed by Saudi institutional investors |
| [Rize](https://rize.sa) | 🇸🇦 KSA | Digital SME bank focused on micro-businesses |
| [Meem](https://www.meem.sa) | 🇸🇦 KSA | Alinma's digital bank |
| [Tahaluf](https://www.tahaluf.sa) | 🇸🇦 KSA | Digital bank from stc group |
| [Lesan](https://lesan.sa) | 🇸🇦 KSA | Digital bank backed by the PIF ecosystem |

### Payments, acquiring & card networks

| Company | Segment | Notes |
|---|---|---|
| [Visa](https://www.visa.com) ⭐ | Network | The largest global card network |
| [Mastercard](https://www.mastercard.com) ⭐ | Network | Visa's global competitor |
| [American Express](https://www.americanexpress.com) | Network | Three-party model — issuer and network in one |
| [Discover](https://www.discover.com) | Network | US card network |
| [UnionPay](https://en.unionpay.com) | Network | The Chinese scheme with the largest cardholder base |
| [JCB](https://www.global.jcb/en/) | Network | Japanese card scheme with global acceptance |
| [Stripe](https://stripe.com) ⭐ | Acquiring | The developer default for online payments |
| [Adyen](https://www.adyen.com) ⭐ | Acquiring | Unified commerce payments at global scale |
| [Checkout.com](https://www.checkout.com) | Acquiring | Enterprise acquiring and alternative payments |
| [Worldpay](https://www.worldpay.com) | Acquiring | One of the largest global acquiring networks (FIS) |
| [Global Payments](https://www.globalpayments.com) | Acquiring | Omnichannel acquiring and issuer processing |
| [Rapyd](https://www.rapyd.net) | Acquiring | Local-payment-network aggregation across 100+ countries |
| [SWIFT](https://www.swift.com) ⭐ | Messaging | The correspondent network for cross-border payments |
| [SWIFT gpi](https://www.swift.com/payments/global-payments-innovation) | Messaging | Cross-border payment tracking standard |
| [Volante](https://www.volante.com) | Processing | Payments modernization and ISO 20022 processing |

### Card issuing, BaaS & embedded finance

| Company | Segment | Notes |
|---|---|---|
| [Marqeta](https://www.marqeta.com) ⭐ | Issuing | The modern card-issuing platform — tokenized, programmatic |
| [Galileo (SoFi Tech Solutions)](https://www.galileo-ft.com) | Issuing | High-volume card and payment processing infrastructure |
| [Lithic](https://www.lithic.com) | Issuing | Programmatic card issuing with instant card creation |
| [Highnote](https://highnote.com) | Issuing | Card issuing and program management for fintechs |
| [Bond](https://www.bond.tech) | Issuing/BaaS | BaaS for cards, accounts, and payments |
| [Pismo](https://www.pismo.io) | Issuing | Cloud-native payments and card issuing (Visa) |
| [i2c](https://www.i2cinc.com) | Issuing | Global card issuing and processing platform |
| [Deserve](https://deserve.com) | Issuing | Credit-card issuing platform |
| [Unit](https://www.unit.co) ⭐ | BaaS | Programmable BaaS — accounts, cards, payments |
| [Solaris](https://www.solarisgroup.com) | BaaS | European licensed bank behind many fintechs |
| [Railsr](https://www.railsr.com) | BaaS | UK/EU BaaS — card issuing, wallets, embedded banking |
| [Treasury Prime](https://treasuryprime.com) | BaaS | US BaaS connecting fintechs to partner banks |
| [SDK.finance](https://sdk.finance) | BaaS | Open-source-friendly banking and wallet platform |
| [Modern Treasury](https://www.moderntreasury.com) | Ledger | Ledger-as-a-service and payment operations |
| [Moov](https://moov.io) | Ledger | Open-source payments and money-movement infrastructure |
| [LedgerFi](https://www.ledgerfi.com) | Ledger | Real-time ledger and treasury infrastructure |

### Remittance & cross-border payments

| Company | Segment | Notes |
|---|---|---|
| [Wise](https://wise.com) ⭐ | Consumer remittance | The transparent, mid-market-rate pioneer |
| [Remitly](https://www.remitly.com) | Consumer remittance | Digital remittance focused on speed and emerging corridors |
| [Western Union](https://www.westernunion.com) | Consumer remittance | The global cash and digital remittance network |
| [MoneyGram](https://www.moneygram.com) | Consumer remittance | Global money movement with strong cash-out networks |
| [WorldRemit (Zepz)](https://www.worldremit.com) | Consumer remittance | Digital remittance across 130+ countries |
| [Ria](https://www.ria.com) | Consumer remittance | Cash and digital remittance with broad agent network |
| [Xoom (PayPal)](https://www.xoom.com) | Consumer remittance | Fast digital remittance from the US |
| [TransferGo](https://www.transfergo.com) | Consumer remittance | European remittance and borderless payments |
| [OFX](https://www.ofx.com) | Remittance | International transfers for consumers and SMEs |
| [Payoneer](https://www.payoneer.com) | B2B | Cross-border payments for freelancers, marketplaces, SMEs |
| [Nium](https://www.nium.com) | B2B | Embedded cross-border payments and card issuance |
| [Thunes](https://www.thunes.com) | B2B | Cross-border network connecting wallets, banks, mobile money |
| [TerraPay](https://terrapay.com) | B2B | Interoperable payments network across 100+ countries |
| [Airwallex](https://www.airwallex.com) | B2B | Global payments, FX, and treasury infrastructure |
| [Ebury](https://www.ebury.com) | B2B | FX and international payments for SMEs |
| [Convera](https://www.convera.com) | B2B | Enterprise cross-border payments and FX risk |
| [dLocal](https://dlocal.com) | B2B | Local-payment-method aggregation across emerging markets |

### Open banking, account aggregation & data

| Company | Notes |
|---|---|
| [Plaid](https://plaid.com) ⭐ | The US standard for connecting bank accounts |
| [MX](https://www.mx.com) | Financial data platform and personalization layer |
| [Envestnet Yodlee](https://www.yodlee.com) | The veteran data-aggregation provider |
| [TrueLayer](https://truelayer.com) | European open-banking aggregator (AIS/PIS) |
| [Tink](https://tink.com) | European open-banking aggregator (part of Visa) |
| [Yapily](https://www.yapily.com) | European open-banking aggregator |
| [Flinks](https://flinks.com) | Canadian account-connectivity and data platform |
| [Finicity](https://www.finicity.com) | Open-banking data (part of Mastercard) |
| [YNAB](https://www.ynab.com) | Zero-based budgeting app |
| [Rocket Money](https://www.rocketmoney.com) | Subscription management and bill negotiation |

### KYC, identity & verification

| Company | Notes |
|---|---|
| [Onfido](https://onfido.com) ⭐ | Document and biometric identity verification |
| [Alloy](https://www.alloy.com) ⭐ | The decisioning engine orchestrating KYC/KYB providers |
| [Persona](https://withpersona.com) | Identity platform and workflow builder |
| [Jumio](https://www.jumio.com) | Identity verification and AML/KYC |
| [Sumsub](https://sumsub.com) | Global KYB/KYC orchestration |
| [Veriff](https://www.veriff.com) | IDV with 230+ document types |
| [Trulioo](https://www.trulioo.com) | Identity and business verification across 195+ countries |
| [Ondato](https://ondato.com) | Identity verification and AML workflow |
| [iDenfy](https://www.idenfy.com) | ID verification with AML and fraud screening |
| [AU10TIX](https://www.au10tix.com) | The veteran ID-verification vendor |
| [Dun & Bradstreet](https://www.dnb.com) ⭐ | Business identity, credit, and ownership data |
| [Moody's Orbis (Bureau van Dijk)](https://www.bvdinfo.com) | The company-and-ownership database for corporate KYC |
| [OpenCorporates](https://opencorporates.com) | Open company-registry data |
| [North Data](https://northdata.com) | European company-registry intelligence |

### AML, screening & RegTech

| Company | Notes |
|---|---|
| [ComplyAdvantage](https://complyadvantage.com) ⭐ | Real-time AML data, sanctions, PEP screening via API |
| [NICE Actimize](https://www.niceactimize.com) ⭐ | The enterprise mainstay for AML transaction monitoring |
| [LSEG World-Check](https://www.lseg.com/en/data-analytics/products/world-check) ⭐ | The screening database of record |
| [Quantexa](https://www.quantexa.com) | Decision intelligence over connected data |
| [Fenergo](https://www.fenergo.com) | Client lifecycle management and KYC automation |
| [Dow Jones Risk & Compliance](https://www.dowjones.com/professional/risk/) | Watchlist and ownership research data |
| [Wolters Kluwer OneSumX](https://www.wolterskluwer.com/en/solutions/onesumx) | Regulatory reporting, risk, and compliance suite |
| [Regnology](https://www.regnology.net) | Regulatory reporting and data collection |
| [AxiomSL (Moody's)](https://www.moodys.com) | Regulatory capital and reporting analytics |
| [Lucinity](https://www.lucinity.com) | AI copilots for AML investigations |
| [Flagright](https://flagright.com) | AML-compliance and fraud-detection APIs |
| [Sanction Scanner](https://sanctionscanner.com) | Screening-as-an-API |
| [Tookitaki](https://www.tookitaki.com) | AI-native AML and sanctions systems |
| [Chainalysis](https://www.chainalysis.com) | Blockchain data, AML, and investigations |
| [Elliptic](https://www.elliptic.co) | Crypto transaction monitoring |

### Fraud detection & risk decisioning

| Company | Notes |
|---|---|
| [Feedzai](https://feedzai.com) ⭐ | AI-first transaction monitoring and fraud risk |
| [Featurespace](https://www.featurespace.com) | Real-time behavioral analytics |
| [Sift](https://sift.com) | Digital trust and fraud platform |
| [DataVisor](https://www.datavisor.com) | Unsupervised ML catching coordinated fraud rings |
| [LexisNexis ThreatMetrix](https://risk.lexisnexis.com/products/threatmetrix) | Digital identity network for device risk scoring |
| [Signifyd](https://www.signifyd.com) | AI e-commerce fraud decisions with chargeback guarantee |
| [Forter](https://www.forter.com) | Real-time fraud decisioning |
| [Ravelin](https://www.ravelin.com) | Payment-risk and fraud platform for marketplaces |
| [BioCatch](https://www.biocatch.com) | Behavioral biometrics catching account-takeover |
| [Incognia](https://incognia.com) | Location- and device-based fraud prevention |
| [Verifi (Visa)](https://www.verifi.com) | Visa's dispute-automation suite |
| [Ethoca (Mastercard)](https://www.ethoca.com) | Consumer-collaboration dispute resolution |
| [Chargebacks911](https://chargebacks911.com) | Chargeback management and representment |
| [FICO Falcon](https://www.fico.com/en/products/falcon-platform) | The industry-standard card fraud engine |
| [FICO Platform](https://www.fico.com) | Decisioning across credit and fraud |
| [FICO Debt Manager](https://www.fico.com/en/products/fico-debt-manager) | Collections-and-recovery system |

### Lending, credit & wealth

| Company | Segment | Notes |
|---|---|---|
| [Experian](https://www.experian.com) ⭐ | Credit bureau | Bureau data and PowerCurve decisioning |
| [Klarna](https://www.klarna.com) ⭐ | BNPL | The global BNPL leader, expanding into banking |
| [Affirm](https://www.affirm.com) | BNPL | US BNPL with transparent, risk-based pricing |
| [Afterpay](https://www.afterpay.com) | BNPL | Installment payments (part of Block) |
| [PayPal Pay Later](https://www.paypal.com) | BNPL | BNPL embedded in the PayPal checkout |
| [Blend](https://blend.com) | Origination | Digital origination across consumer and mortgage lending |
| [nCino](https://www.ncino.com) | Origination | Cloud banking platform for commercial and SME lending |
| [MeridianLink](https://www.meridianlink.com) | Origination | Consumer-lending origination for banks and credit unions |
| [Abrigo](https://www.abrigo.com) | Origination | Lending and compliance software for community banks |
| [ICE Mortgage Technology](https://www.icemortgagetechnology.com) | Mortgage | The dominant US mortgage and consumer-lending platform |
| [Zest AI](https://www.zest.ai) | Decisioning | Interpretable ML credit models |
| [Scienaptic](https://scienaptic.com) | Decisioning | AI credit decisioning |
| [Provenir](https://www.provenir.com) | Decisioning | Risk decisioning across consumer and SME lending |
| [TrueAccord](https://trueaccord.com) | Collections | Digital-first, consumer-friendly debt collection |
| [InDebted](https://indebted.com) | Collections | Digital collections with integrated payment plans |
| [Betterment](https://www.betterment.com) | Robo-advice | The original robo-advisor |
| [Wealthfront](https://www.wealthfront.com) | Robo-advice | Automated investing and financial planning |
| [Vanguard](https://investor.vanguard.com) | Investing | The low-cost investing default and Digital Advisor |
| [Interactive Brokers](https://www.interactivebrokers.com) | Brokerage | Full-featured brokerage at scale |
| [Alpaca](https://alpaca.markets) | Brokerage API | Commission-free brokerage API |
| [DriveWealth](https://www.drivewealth.com) | Brokerage | Fractional investing infrastructure |
| [FNZ](https://www.fnz.com) | Wealthtech | The wealth-platform engine behind many banks |
| [InvestCloud](https://www.investcloud.com) | Wealthtech | Digital wealth-management platform |
| [Addepar](https://www.addepar.com) | Wealthtech | Portfolio analytics for advisors and private banks |
| [Wahed](https://wahed.com) | Islamic investing | The leading halal robo-advisor |
| [Zoya](https://zoya.finance) | Islamic investing | Halal investing app — Shariah-screened stocks, ETFs, funds |
| [Coinbase](https://www.coinbase.com) | Digital assets | The largest US retail crypto exchange |
| [Fireblocks](https://www.fireblocks.com) | Digital assets | Institutional custody and settlement infrastructure |

### Insurance & insurtech

| Company | Notes |
|---|---|
| [Guidewire](https://www.guidewire.com) ⭐ | The P&C insurance operating system |
| [Lemonade](https://www.lemonade.com) | The AI-native, fully digital insurer |
| [wefox](https://www.wefox.com) | Digital insurance platform across Europe |
| [Cover Genius](https://covergenius.com) | Embedded insurance for retailers, travel, rentals |
| [Qover](https://www.qover.com) | White-label, embedded insurance for platforms |
| [bolttech](https://www.bolttech.io) | Insurance distribution and embedded solutions |
| [Tractable](https://tractable.ai) | AI computer vision for claims |
| [FRISS](https://www.friss.com) | AI fraud and risk detection for underwriting and claims |
| [Verisk](https://www.verisk.com) | Data, analytics, and decision solutions for P&C |
| [Origami Risk](https://www.origamirisk.com) | Risk-management and claims software |

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
