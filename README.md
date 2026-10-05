# Awesome-Privacy-Risk-Management-Software

## Top Privacy Risk Management Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Privacy Program Automation, Consent Management & Data Subject Rights*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Privacy Risk Management**. These tools help organizations comply with privacy regulations (GDPR, CCPA, HIPAA, LGPD), manage data subject requests, assess privacy risks, and govern consent across systems.



**Examples** include Microsoft Priva, OneTrust Privacy, DataGrail, Securiti, TrustArc, BigID Privacy, Ketch, WireWheel, MineOS, and Transcend (the category leaders).



**Open-source emphasis**: Privacy engineering is a growing open-source domain. **Fides** (Ethyca) leads as the most mature privacy-as-code platform, **CISO Assistant** provides comprehensive GDPR/compliance management, and **Probo** delivers a self-hostable GRC platform with 270+ MCP tools for AI agents. **OpenOptOut** automates data broker removal, while **Conzent OCI** and **OpenFGC** handle consent management. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Microsoft Priva](https://www.microsoft.com/en-us/security/business/privacy)**  

  Microsoft's privacy management solution integrated with Microsoft 365 and Purview. **Best for Microsoft-centric organizations** — privacy risk assessments, subject rights requests, and consent management.



- **[OneTrust Privacy](https://www.onetrust.com/)**  

  **The market leader in privacy management** — comprehensive platform covering assessments, consent, data mapping, subject rights, and incident management.



- **[DataGrail](https://www.datagrail.io/)**  

  Privacy management platform with automated data discovery and integration across 2,000+ systems.



- **[Securiti](https://securiti.ai/)**  

  Unified data controls platform with privacy, security, governance, and compliance capabilities.



- **[TrustArc](https://trustarc.com/)**  

  Privacy compliance platform with assessments, consent, and certification management.



- **[BigID Privacy](https://bigid.com/)**  

  Data intelligence platform with privacy, security, and governance modules.



- **[Ketch](https://www.ketch.com/)**  

  Privacy automation platform for consent and data rights across web, mobile, and backend systems.



- **[WireWheel](https://wirewheel.io/)**  

  Privacy management platform focused on data subject rights and vendor risk.



- **[MineOS](https://www.mineos.ai/)**  

  AI-powered data privacy platform with automated data subject rights fulfillment.



- **[Transcend](https://transcend.io/)**  

  Privacy infrastructure for consent and data subject requests across systems.



## Open-Source GitHub Projects



- **[Fides (Ethyca)](https://github.com/ethyca/fides)**  

  **The leading open-source privacy engineering platform**, Apache-2.0 licensed. **"Privacy as Code"** — manage data subject requests (DSR) in your runtime environment and enforce privacy regulations in code. Features **Fides Admin UI** for managing requests, **Privacy Center** for users to submit requests, **automated data discovery** across databases, and **policy enforcement as code**. Quick-start with `fides deploy up` — runs a sample project with a full DSR workflow in under 5 minutes . **The de facto open-source privacy automation platform** — designed for developers and privacy engineers.



- **[CISO Assistant](https://github.com/intuitem/ciso-assistant-community)**  

  **Comprehensive open-source GRC platform covering privacy and risk management**, AGPL-3.0 licensed. **One-stop-shop for Risk Management, AppSec, Compliance & Audit, TPRM, Privacy, and Reporting**. Supports **130+ global frameworks** with automatic control mapping including **GDPR, HIPAA, ISO 27001, NIST CSF, SOC 2, NIS2, and DORA** . **The most comprehensive open-source privacy/GRC platform** — used by European public sector and enterprises.



- **[Probo](https://github.com/getprobo/probo)**  

  **Self-hostable GRC platform with strong privacy capabilities**, ISC licensed. **270+ MCP tools** expose every entity and operation for AI agent integration (Claude, Cursor, Continue). Features **data privacy (DPIA/TIA), rights requests (SAR/erasure), processing activity records, data inventory, vendor risk, and cookie/consent management**. **CLI (`prb`), GraphQL API, and n8n community node** for automation. **The best open-source GRC platform for engineering teams** wanting AI-native privacy workflows .



- **[OpenOptOut](https://github.com/rlnunez/OpenOptOut)**  

  **Self-hosted, distributed privacy platform for automating personal data removal**, open-source. **Zero-knowledge identity vaults, multi-tenant consortium ILS routing, distributed queue workers, and sandboxed plugin extensibility**. Designed for **libraries, schools, credit unions, and non-profits** — patron self-service with OIDC, SAML 2.0, LDAP, or SIP2 authentication . **The best open-source tool for data broker opt-out automation** — ideal for institutions wanting to protect patron/member privacy.



- **[Conzent OCI](https://github.com/conzent-net/oci)**  

  **Open-source cookie consent and privacy compliance platform**, PHP-based. Features **cookie detection and categorization, consent collection and logging, banner configuration with IAB TCF v2.2/v2.3 and Google Consent Mode v2 support, privacy policy generation, and scheduled reporting** . **Built-in headless Chromium scanner** detects cookies, scripts, and tracking technologies automatically. **The best open-source alternative to OneTrust for consent management** — self-hosted with full control.



- **[OpenFGC (WSO2)](https://github.com/wso2/openfgc)**  

  **Industry-agnostic fine-grained consent management engine for developers**, Apache-2.0 licensed. Features **consent purposes, consent elements, consent records with full lifecycle (Created → Active → Expired/Revoked), and audit trails**. **Go-based with MySQL/PostgreSQL support** — designed for integration into applications . **Best for developers building consent into applications** — flexible and extensible.



- **[PrivaShield](https://github.com/Nehil1984/PrivaShild)**  

  **Open-source GDPR compliance management platform**, Apache-2.0 licensed. Features **Verzeichnis der Verarbeitungstätigkeiten (VVT/processing activities), Auftragsverarbeitungsverträge (AVV/DPAs), Datenschutz-Folgenabschätzungen (DSFA/DPIAs), data breach management, data subject rights, TOM catalog, deletion concepts, task/measure management, internal audits, and AI compliance** . **Best for German/European organizations** needing structured GDPR documentation.



- **[PILLAR (LINDDUN)](https://github.com/stfbk/pillar)**  

  **AI-powered privacy threat modeling tool based on LINDDUN framework**, open-source. Uses **LLMs to identify privacy threats** from application descriptions or Data Flow Diagrams (DFDs). Supports **LINDDUN SIMPLE, LINDDUN GO simulation with multi-agent LLMs, and LINDDUN PRO methodology**. **Impact assessment and control measure suggestions** based on privacy patterns. **Local model support via Ollama and LM Studio** for privacy-preserving analysis . **Best for developers wanting AI-assisted privacy threat modeling**.



- **[KafkaCode](https://github.com/nikhil-kapu/kafkacode)**  

  **Local-first PII scanner and secret detection CLI**, open-source. Scans source code for **PII leaks, hardcoded secrets, and privacy compliance risks** with a **privacy grade (A+ to F)**. Supports **GDPR/CCPA risk detection, SARIF/JSON output for GitHub code scanning, and CI/CD integration** . **Best for developers wanting privacy checks in CI pipelines** — no signup, no config, local-first.



### Additional Strong Open-Source Options



- **Comp AI** — Open-source compliance platform for SOC 2, ISO 27001, HIPAA, and GDPR with AI Policy Editor and automated evidence collection .

- **Vulos Compliance** — Minimal POPIA/GDPR data-subject rights request intake with SQLite/Postgres storage, intentionally a "request recorder" not an automated engine .

- **The OpenLane Core** — Open-source compliance automation for SOC 2, GDPR, ISO27001, NIST 800-53 .

- **Cozy Cloud / Twake** — LINAGORA's open-source personal data management platform with strong sovereignty focus .



**Frameworks for building custom privacy solutions**: Combine **Fides** for privacy-as-code DSR automation and policy enforcement . Use **CISO Assistant** for comprehensive GDPR/GRC management with 130+ framework mappings . Deploy **Probo** for AI-native GRC with 270+ MCP tools for agent integration . Choose **Conzent OCI** for cookie consent and IAB TCF compliance . Use **OpenOptOut** for data broker removal automation . For developers, **PILLAR** provides AI-assisted privacy threat modeling  and **KafkaCode** enables privacy scanning in CI . Note that true enterprise privacy management with automated data mapping across thousands of systems, global regulatory coverage, and vendor-supported SLAs remains primarily commercial territory; open-source stacks provide strong consent, DSR, and compliance foundations that require integration for complete privacy programs.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Privacy management tools process sensitive personal data. Self-hosted solutions require proper security hardening, encryption at rest and in transit, access controls, and compliance with data privacy regulations.

- **Privacy regulations vary by jurisdiction** — GDPR (EU), CCPA/CPRA (California), LGPD (Brazil), PIPEDA (Canada), POPIA (South Africa). Verify tool compliance with your specific regulatory requirements.

- **Open-source privacy tools vary in maturity** — Fides and CISO Assistant are production-ready; some tools are early-stage or focused on specific use cases (OpenOptOut for broker removal, KafkaCode for code scanning) .

- The open-source ecosystem provides strong consent, DSR, and compliance foundations, but **automated data mapping across thousands of systems, global regulatory coverage, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for privacy engineers, DPOs, compliance officers, and organizations seeking privacy sovereignty.**  

Let's make privacy risk management more open, transparent, and developer-friendly.
