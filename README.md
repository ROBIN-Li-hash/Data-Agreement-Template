# Farmer Data Participation Agreement

**Version:** 1.0  
**Effective Date:** 17 September 2026  
**Review Cycle:** Annual  
**Jurisdiction:** England and Wales  
**Legal Framework:** UK GDPR · Data Protection Act 2018 · EU GDPR 2016/679

---

## Table of Contents

1. [Preamble & Scope](#1-preamble--scope)
2. [Parties to this Agreement](#2-parties-to-this-agreement)
3. [Privacy & Data Protection](#3-privacy--data-protection)
4. [Purpose of Data Use](#4-purpose-of-data-use)
5. [FAIR Data Principles](#5-fair-data-principles)
6. [Amendment Process](#6-amendment-process)
7. [Cloud & Technology Infrastructure](#7-cloud--technology-infrastructure)
8. [Farmer Rights](#8-farmer-rights)
9. [Governance & Contacts](#9-governance--contacts)
10. [Signatures](#10-signatures)

---

## 1. Preamble & Scope

This Farmer Data Participation Agreement ("**Agreement**") sets out the terms under which agricultural data contributed by participating farmers is collected, stored, processed, analysed, and shared as part of the Research Programme ("**Programme**").

The Programme aims to advance sustainable farming knowledge through rigorous, open, and reproducible data science practices. It is guided by four foundational commitments:

- Respect for farmer sovereignty over their own data
- The highest standards of personal data protection under applicable law
- Transparency about every stage of data handling
- Adherence to the internationally recognised **FAIR Data Principles** — making data Findable, Accessible, Interoperable, and Reusable

This Agreement supersedes any prior informal data-sharing arrangements with the Research Team and applies to all data collected from the effective date forward. Retroactive data previously shared will be brought under these terms unless a farmer explicitly requests its deletion.

> **Farmer-First Commitment:** Farmers are not passive data sources — they are partners. Nothing in this Agreement diminishes the right of any farmer to withdraw, question, or restrict use of their data at any time, without penalty or loss of access to Programme services.

---

## 2. Parties to this Agreement

### 2.1 The Farmer — Data Subject & Data Contributor

Any individual farmer, farm operator, or farm business that voluntarily contributes data to the Programme. This includes sole traders, partnerships, limited companies, and tenant farmers. Each farmer is an independent data subject and retains legal ownership of their contributed data at all times.

### 2.2 The Research Institution — Data Controller

The academic or research organisation overseeing the Programme, responsible for determining the purposes and means of processing personal and farm-level data. The Research Institution registers as a Data Controller with the relevant supervisory authority and appoints a Data Protection Officer (DPO).

### 2.3 Third-Party Platforms & Cloud Providers — Data Processor(s)

Technology companies that process data on behalf of the Research Institution under strict Data Processing Agreements (DPAs). This includes cloud infrastructure providers, analytics platforms, and data pipeline services. A complete list of processors is maintained in Section 7.

### 2.4 Authorised Investigators — Research Team

Named researchers, data scientists, and academic collaborators who have received ethics approval, signed a confidentiality agreement, and been granted role-based access to specific data subsets. Only authorised investigators may access identifiable farm data.

### 2.5 Data Protection Officer (DPO)

An independent or organisationally appointed officer responsible for monitoring compliance with this Agreement and applicable data protection law. The DPO is the first point of contact for farmer queries about data rights (see Section 9 for contact details).

### 2.6 Research Ethics Committee

An institutional or independent ethics committee that reviews the Programme's data practices, approves data collection instruments, and evaluates any proposed changes to data use. The Committee's approval is required before any significant amendment to this Agreement takes effect.

### 2.7 Third-Party Collaborators

Where external academic institutions, government bodies, or agri-food industry partners are granted access to aggregated, anonymised datasets for secondary research, they become subsidiary data processors and must sign a Data Sharing Agreement consistent with the terms of this Agreement. No identifiable farm data is shared with third parties without explicit, specific, and informed consent from the relevant farmer.

---

## 3. Privacy & Data Protection

All personal and farm-level data is processed in strict compliance with the **UK General Data Protection Regulation (UK GDPR)**, the **Data Protection Act 2018**, and — where applicable — the **EU General Data Protection Regulation (EU GDPR 2016/679)**. For international collaborators, the equivalent national data protection legislation of the participating country applies.

### 3.1 Lawful Basis for Processing

Processing rests on two primary lawful bases:

1. **Explicit consent** freely given by the farmer upon signing this Agreement
2. **Legitimate interests** of the Research Institution in conducting scientific research in the public interest, where these interests do not override the fundamental rights and freedoms of the farmer

Any change to the lawful basis requires notification and, where necessary, renewed consent.

### 3.2 Categories of Data Collected

| Category | Examples |
|---|---|
| Farm identification data | Farm name, reference number, approximate location (county level), farm type and size classification |
| Agricultural operational data | Crop types, rotations, yield records, input usage, machinery data, irrigation records |
| Environmental monitoring data | Soil health indicators, weather station readings, biodiversity survey results, carbon sequestration estimates |
| Economic data (optional) | Input costs and output revenues, contributed voluntarily in aggregated form |
| Contact data | Name and email of the farm contact person, used only for Programme communication |

### 3.3 Data Minimisation & Purpose Limitation

Only data strictly necessary for the stated research purposes is collected. Data collected for one purpose will not be re-purposed without explicit notice and, where required, renewed consent. The Research Team undertakes a Data Minimisation Review annually.

### 3.4 Pseudonymisation & Anonymisation

All farm-level data is **pseudonymised** at the point of ingestion: the farm's identity is replaced by a randomly generated identifier (**FarmID**), and the mapping between real identity and FarmID is stored in a separate, access-controlled key vault.

Data used for publication or shared with collaborators is **fully anonymised** through k-anonymity techniques (k ≥ 5) to prevent re-identification from location or operational characteristics.

### 3.5 Data Retention

| Data Type | Retention Period |
|---|---|
| Personal contact data | Duration of active participation + 12 months |
| Pseudonymised research data | Maximum 10 years from date of collection |
| Anonymised published datasets | Indefinite (in public repository) |

### 3.6 Security Measures

- Data in transit: encrypted via **TLS 1.3**
- Data at rest: **AES-256 encryption** on cloud storage
- Access control: **Role-Based Access Control (RBAC)** with mandatory Multi-Factor Authentication (MFA)
- Annual penetration testing by an independent security firm
- Data breach notification to the ICO within **72 hours**; notification to affected farmers within **5 working days**

---

## 4. Purpose of Data Use

Data contributed by farmers will be used exclusively for the following stated research purposes. Use for any purpose outside this list requires an amendment to this Agreement (see Section 6) and, where material, renewed farmer consent.

### 4.1 Primary Research Purposes

1. **Agronomic Modelling** — Developing and validating predictive models for crop yield, soil health trajectories, and the effectiveness of different farming practices across varied soil types, climates, and management systems.

2. **Climate Adaptation Research** — Assessing how farms in different regions are responding to changing climate patterns and identifying management practices that improve resilience to extreme weather events, drought, and shifting growing seasons.

3. **Environmental Impact Assessment** — Quantifying on-farm environmental outcomes including greenhouse gas emissions, biodiversity indices, water quality, and carbon sequestration, to support evidence-based policy and voluntary environmental markets.

4. **Benchmarking & Farm Advisory Tools** — Creating anonymised benchmarking datasets that allow farmers to compare their own performance against regional and national averages. Benchmarking tools are made freely available to all contributing farmers.

5. **Policy & Academic Publication** — Contributing findings — based solely on aggregated, anonymised data — to peer-reviewed academic journals, government policy consultations, and open-access research repositories. No publication will contain data from which an individual farm could be identified.

6. **Machine Learning & AI Development (with additional consent)** — Where farmers provide specific additional consent, data may be used to train machine learning models for agricultural prediction and decision support. Farmers may opt out of AI training uses without affecting participation in other aspects of the Programme.

### 4.2 Restrictions

> **Commercial Use Restriction:** Farm data contributed to this Programme will **not** be sold, licensed, or otherwise made available to commercial agri-businesses, input suppliers, or commodity traders for commercial purposes. Findings published in open-access literature may be read and cited by commercial parties, but the underlying farm-level data remains non-commercial research property.

---

## 5. FAIR Data Principles

The Programme is committed to the **FAIR Data Principles** (Wilkinson et al., 2016), embedded in major research funding requirements including those of UK Research & Innovation (UKRI) and the European Research Council (ERC). Each principle is defined and its specific application within the Programme is described below.

---

### 5.1 Findable

**Core concept:** Data and metadata should be easy to find by both humans and computer systems. This requires globally unique and persistent identifiers and rich, searchable metadata.

**Application in this Programme:**

Every dataset generated or curated by the Programme is assigned a **globally unique persistent identifier (PID)**, implemented as a **Digital Object Identifier (DOI)** minted through a recognised DOI registry (e.g., DataCite). Anonymised, published datasets are deposited in the UK Data Service or another recognised domain repository and indexed by **OpenAIRE** and **Google Dataset Search**.

**Metadata standard:** All datasets carry structured metadata conforming to the **Dublin Core Metadata Initiative (DCMI)** standard, supplemented by agricultural domain-specific fields from the **AGROVOC Controlled Vocabulary** maintained by FAO. Metadata records are machine-readable in JSON-LD.

**Data catalogue:** An internal data catalogue (implemented in **Databricks Unity Catalog** and mirrored to a public-facing interface) records all datasets by FarmID category, collection date, data type, and research use. This catalogue is the authoritative reference for what data exists and where it can be found.

**Key implementations:**
- DOI registration via DataCite
- AGROVOC controlled vocabulary for agricultural domain terms
- Dublin Core + JSON-LD machine-readable metadata
- Databricks Unity Catalog as internal data catalogue
- Indexing via OpenAIRE and Google Dataset Search

---

### 5.2 Accessible

**Core concept:** Data should be retrievable by their identifier using standardised, open, and universally implementable communications protocols. Metadata should remain accessible even when the data itself is no longer available.

**Application in this Programme:**

Published anonymised datasets are accessible via **HTTPS** through repository APIs, with no authentication required for public data. Where datasets contain residual sensitivity requiring restricted access, the **metadata record remains open** and access can be requested through a documented, transparent access request process (see the Data Access Protocol published in this repository).

**Authentication for restricted data:** Researchers applying for restricted-access datasets must complete an access form, agree to a Data Access Agreement, and receive approval from the Programme Data Access Committee within **20 working days**. Access is granted via time-limited, audited API tokens.

**Long-term accessibility:** The Programme commits to maintaining dataset DOI resolution and metadata accessibility for a minimum of **10 years** beyond the Programme's end date, through deposit with a long-term preservation repository (e.g., UK Data Archive).

**Key implementations:**
- Open HTTPS access for public datasets
- Persistent metadata even for restricted datasets
- Time-limited API token access for restricted data
- Long-term deposit with UK Data Archive

---

### 5.3 Interoperable

**Core concept:** Data should use formal, shared, and broadly applicable knowledge representations and follow community standards so they can be integrated with other datasets without bespoke transformation.

**Application in this Programme:**

All data is stored and published in **open, non-proprietary file formats**:

| Data Type | Format |
|---|---|
| Tabular data | CSV, Parquet |
| Geospatial data | GeoJSON, GeoTIFF |
| Time-series sensor data | NetCDF |
| Metadata | JSON-LD, Dublin Core XML |

**Ontologies used for variable annotation:**

| Ontology | Purpose |
|---|---|
| AGRO (Agronomy Ontology) | Crop and farming practice terms |
| ENVO (Environment Ontology) | Environmental variables and habitats |
| CHEBI (Chemical Entities of Biological Interest) | Fertiliser and pesticide compounds |

**API design:** The Programme's internal data platform (built on **Databricks**) exposes data through a standardised **REST API** conforming to the **OpenAPI 3.1** specification. Data exchange with collaborating institutions uses the **W3C PROV-O** provenance ontology to trace data lineage.

**Geospatial reference:** All geospatial data is published in **EPSG:4326 (WGS84)**, with transformations to British National Grid (EPSG:27700) available on request.

---

### 5.4 Reusable

**Core concept:** Data should be richly described so they can be replicated and combined in different settings. This requires clear usage licences, provenance information, and domain-relevant community standards.

**Application in this Programme:**

**Licensing:**

| Dataset Type | Licence |
|---|---|
| Fully anonymised, public datasets | Creative Commons Attribution 4.0 International (CC BY 4.0) |
| Restricted-access datasets with residual sensitivity | Creative Commons Attribution Non-Commercial 4.0 (CC BY-NC 4.0) |
| Analysis code and pipelines | MIT Licence |

Licence terms are machine-readable and embedded in each dataset's metadata record.

**Data Quality Documentation:** Every dataset is accompanied by a **Data Quality Statement** describing the collection methodology, known limitations, quality control procedures applied, and the degree of completeness. This follows the **ISO 8000** data quality framework.

**Provenance tracking:** The full processing history of each dataset — from ingestion through transformation to publication — is recorded in a lineage graph using **Apache Atlas** and the **Databricks Unity Catalog lineage feature**. This allows any researcher to trace exactly how a published variable was derived.

**Farmer attribution:** Where farmers consent to acknowledgement, their contribution is recognised in dataset citations using the **CRediT contributor taxonomy**. Farmers who prefer anonymity will not be named.

---

### 5.5 Additional Open Science Commitments

Beyond the four FAIR principles, the Programme adopts the following additional open science practices:

- **Open code:** All analysis code, data pipelines, and ML model architectures are published under the MIT Licence on this GitHub repository, enabling full methodological transparency and replication.
- **Pre-registration:** Where feasible, research hypotheses and analytical plans are pre-registered on the **Open Science Framework (OSF)** before analysis begins.
- **Open peer review:** The Programme encourages submission to journals offering open peer review.
- **Data papers:** Significant new datasets are accompanied by a descriptive data paper published in a data journal (e.g., *Scientific Data*, *Data in Brief*), so that farmer contributions receive formal academic citation credit.

> **Note on FAIR and openness:** FAIR does not mean all data must be openly published. For this Programme, the principle is: *"as open as possible, as closed as necessary."* Sensitive operational data is never published openly, but its metadata remains publicly findable and accessible.

---

## 6. Amendment Process

This Agreement is a living document. Changes to data uses, infrastructure, or farmer rights provisions require a structured amendment process.

### 6.1 Amendment Tiers

**Tier 1 — Material Amendment**

Applies to: changes to data use purposes, parties with access to data, categories of data collected, retention periods, or farmer rights.

Requirements:
- Ethics Committee written approval
- Minimum **60 days** advance notice to all participating farmers
- Explicit re-consent required for continued participation
- Farmers who do not consent may withdraw without prejudice

**Tier 2 — Administrative Amendment**

Applies to: contact detail updates, cloud provider changes (where data protection standards are maintained), formatting updates, or clarificatory language that does not change the substance of farmer rights.

Requirements:
- Published on GitHub
- Minimum **30 days** email notice to all farmers
- No re-consent required; continued participation after notice period constitutes acceptance
- Farmers may still withdraw their data within the notice period

### 6.2 Amendment Steps

1. **Internal Proposal & Classification** — The Research Team drafts the proposed amendment, classifies it as Tier 1 or Tier 2, and prepares a plain-English summary for farmer communication.

2. **DPO Review** — The Data Protection Officer reviews the proposal for compliance with UK GDPR and applicable law, and may request modifications before it proceeds.

3. **Ethics Committee Approval (Tier 1 only)** — The Research Ethics Committee reviews and provides written approval. This process typically takes 4–8 weeks.

4. **Farmer Notification** — All participating farmers are notified by email with the plain-English summary, a link to the full amended Agreement on GitHub, the tier classification, and the effective date.

5. **Consultation Period** — During the notice period, farmers may submit questions or objections to the DPO. The Research Team will publish a Q&A document responding to any substantive questions raised.

6. **Consent Collection or Continuation** — For Tier 1 amendments, farmers must actively re-sign the updated Agreement. For Tier 2, continued participation after the notice period constitutes acceptance.

7. **Publication on GitHub** — The new version is published with a commit message stating the version number, date, and a brief description of changes. A `CHANGELOG.md` is maintained alongside this Agreement.

---

## 7. Cloud & Technology Infrastructure

All third-party processors are bound by Data Processing Agreements (DPAs) consistent with UK GDPR requirements. Data is not transferred outside the UK/EEA unless adequate mechanisms (Standard Contractual Clauses or equivalent) are in place.

### 7.1 Infrastructure Register

| Platform / Service | Provider | Role in Processing | Data Location |
|---|---|---|---|
| **Databricks Lakehouse** | Databricks Inc. | Primary data engineering, ETL pipelines, ML model training, Unity Catalog metadata management, data lineage tracking, and all analytical workloads | UK / EU West |
| **Azure Blob Storage / ADLS Gen2** | Microsoft Azure | Persistent storage for Bronze, Silver, and Gold data layers. Encrypted at rest with customer-managed keys held in Azure Key Vault | UK South / UK West |
| **Azure Key Vault** | Microsoft Azure | Secure storage of encryption keys, FarmID-to-identity pseudonymisation mapping, API credentials, and secrets. Access restricted to authorised system identities only | UK South |
| **Apache Spark (via Databricks)** | Apache Foundation / Databricks | Distributed data processing for large-scale transformations, geospatial analytics, and time-series modelling. Ephemeral compute clusters; no data persists on compute nodes | Processing only |
| **Delta Lake** | Linux Foundation / Databricks | ACID-compliant open table format for all structured data. Provides time-travel (version history), schema enforcement, and audit logging | UK / EU West |
| **GitHub** | GitHub Inc. (Microsoft) | Version control for all analysis code, data pipelines, model code, and this Agreement. No personal or farm-level data is stored on GitHub | Global CDN (code only) |
| **Apache Atlas** | Apache Foundation | Data catalogue and metadata governance. Manages business glossary, data classification, and lineage graphs across the Databricks environment | UK / EU West |
| **MLflow (via Databricks)** | Linux Foundation / Databricks | Tracking and versioning of all ML experiments, model parameters, and model artefacts. Supports reproducibility and publication of model cards | UK / EU West |
| **Power BI / Tableau** | Microsoft / Salesforce | Visualisation dashboards for anonymised benchmarking outputs shared with farmers. Connected to Gold-layer curated datasets only | UK / EU |
| **UK Data Service / Figshare** | UKRI / Figshare Ltd. | Long-term archival and public repository for anonymised, published datasets. Provides DOI minting and persistent metadata hosting | UK |
| **Airflow / Databricks Workflows** | Apache Foundation / Databricks | Orchestration of scheduled data ingestion, transformation, and validation pipelines | Processing only |
| **Microsoft Entra ID (Azure AD)** | Microsoft Azure | Identity and access management. Enforces MFA, role-based access policies, and conditional access. Provides audit logs of all access events | UK |

> Changes to the above infrastructure are treated as Tier 2 amendments unless they materially reduce data protection standards, in which case they become Tier 1 amendments. This file (`DATA_AGREEMENT.md`) and the adjacent `INFRASTRUCTURE.md` in this repository are the authoritative, version-controlled records.

### 7.2 Data Architecture: Medallion Layers

Data flows through a three-layer Medallion Architecture within the Databricks Lakehouse:

| Layer | Contents | Access |
|---|---|---|
| **Bronze** (raw) | Data as received from farmers, ingested with minimal transformation. Full audit trail preserved | Data engineers only |
| **Silver** (cleansed) | Validated, deduplicated, pseudonymised data. FarmID replaces all personal identifiers | Authorised researchers (RBAC) |
| **Gold** (curated) | Aggregated, anonymised analytical datasets ready for modelling, publication, or farmer dashboards | Programme-wide; published openly where appropriate |

---

## 8. Farmer Rights

Under UK GDPR and this Agreement, every participating farmer has the following rights. The Research Institution will respond to any rights request within **30 calendar days** of receipt (extendable to 90 days for complex requests, with notification).

### 8.1 Rights Summary

| Right | Basis | Description |
|---|---|---|
| **Right of Access** | Article 15 UK GDPR | Request a copy of all personal data held, the purposes for which it is being processed, who it has been shared with, and for how long it will be retained |
| **Right to Rectification** | Article 16 | Request correction of inaccurate personal data or completion of incomplete data |
| **Right to Erasure** | Article 17 | Request deletion of all personal data. Pseudonymised research data may be retained if required for scientific integrity under Article 17(3)(d), with explanation |
| **Right to Restriction** | Article 18 | Request that processing be paused while a dispute about accuracy or lawful basis is resolved |
| **Right to Data Portability** | Article 20 | Receive all directly provided data in a structured, machine-readable format (CSV or JSON) |
| **Right to Object** | Article 21 | Object to processing based on legitimate interests at any time |
| **Right to Withdraw Consent** | UK GDPR | Withdraw consent to any or all processing at any time, without affecting the lawfulness of prior processing |
| **Right to Complain** | Article 77 | Lodge a complaint with the Information Commissioner's Office (ICO) at [ico.org.uk](https://ico.org.uk) or call 0303 123 1113 |

### 8.2 How to Exercise Your Rights

1. **Contact the DPO** at the address listed in Section 9. No formal language is required.
2. **Identity verification** — We will ask you to confirm your FarmID and registered email address to protect against unauthorised access to another farmer's data.
3. **Acknowledgement within 5 working days** — We will confirm receipt and provide an estimated completion date.
4. **Resolution within 30 calendar days** — We will complete your request, or explain clearly why we cannot.

---

## 9. Governance & Contacts

### 9.1 Governing Law

This Agreement is governed by and construed in accordance with the law of **England and Wales**. Any disputes that cannot be resolved informally shall be subject to the exclusive jurisdiction of the courts of England and Wales.

### 9.2 Contact Information

| Role | Contact |
|---|---|
| **Data Protection Officer** | dpo@[institution].ac.uk |
| **Research Programme Team** | research@[institution].ac.uk |
| **GitHub Repository** | github.com/[organisation] |

Response times: DPO — 5 working days. Research Team — 10 working days.

### 9.3 Dispute Resolution

1. Contact the DPO directly in the first instance.
2. If unresolved within 30 days, escalate to the Research Institution's **Research Integrity Officer**.
3. At any time, farmers may raise a formal complaint with the **ICO** without prejudice to any other legal remedy.

### 9.4 Annual Transparency Report

The Research Team publishes an annual **Data Transparency Report** covering:

- Number of participating farmers
- Categories and volumes of data processed
- Amendments made to this Agreement
- Data rights requests received and their outcomes
- Any security incidents
- Progress on open data and FAIR principle implementation

This report is published in this GitHub repository and is freely available to all farmers and the public.

---

## 10. Signatures

By signing below, the farmer confirms that they have read and understood this Agreement, that they agree to contribute their data under these terms, and that they understand their right to withdraw participation at any time without penalty.

> **Digital signature note:** For farmers participating via the Programme's digital onboarding platform, a digitally signed and timestamped copy of this Agreement is automatically archived against your FarmID upon completion of the digital consent process. A PDF copy is sent to your registered email address for your records. Paper copies are available on request.

---

**Farmer / Authorised Farm Representative**

Signature: ___________________________

Printed name: ________________________

Role / capacity: ______________________

Farm trading name: ___________________

FarmID (if known): ___________________

Date: ________________________________

---

**On behalf of the Research Institution**

Signature: ___________________________

Printed name: ________________________

Role: ________________________________

Institution: __________________________

Date: ________________________________

DPO countersign: _____________________

---

> **Right to withdraw:** Signing this Agreement does not lock you in permanently. You may withdraw your consent and participation at any time by contacting the DPO (details in Section 9). Withdrawal will not result in any penalty, and will not affect any research outputs already published based on aggregated, anonymised data.

---

*Farmer Data Participation Agreement · Version 1.0 · Effective 17 September 2026*  
*Published under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) · Governed by the laws of England and Wales*
