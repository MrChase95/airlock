# Privacy Policy — Airlock

**Last updated:** May 2026  

This Privacy Policy explains how **Airlock** (“we”, “us”, “the application”, or “the software”) handles information when you install and use the **Airlock** desktop application — a local REST client (collections, environments, history, scripts, JWT, and related features).

This document is designed to reflect common requirements and principles from multiple jurisdictions, including in particular the **European Economic Area (EEA)**, the **United Kingdom (UK)**, **Switzerland**, **Canada**, **Australia**, **Singapore**, **Japan** (APPI-aligned transparency practices), and **OECD** privacy principles (collection limitation, purpose specification, security, openness, individual participation). It is **not** legal advice.

**Regional supplements (use together with this Policy):**

| Document | When it applies |
|----------|-----------------|
| [US State Privacy Supplement](./privacy-policy-us-supplement.md) | Residents of U.S. states with comprehensive consumer privacy laws (e.g. California, Virginia, Colorado, Connecticut, Utah, and others as enacted). |
| [Brazil LGPD Supplement (English)](./privacy-policy-brazil-lgpd-supplement.md) | Data subjects in Brazil under Lei Geral de Proteção de Dados. |

If a valid, final **supplement** conflicts with this Policy **for your region only**, the **supplement** prevails for that region.

If you obtained a **third-party build or fork**, documentation shipped with that distribution may override this Policy.

---

## Table of contents

1. [Summary](#summary)
2. [Controller and scope](#controller-and-scope)
3. [Personal information we may process](#personal-information-we-may-process)
4. [Purposes and lawful bases](#purposes-and-lawful-bases)
5. [Sharing and recipients](#sharing-and-recipients)
6. [HTTP cookies, certificates, and request content](#http-cookies-certificates-and-request-content)
7. [Storage, international transfers](#storage-international-transfers)
8. [Security](#security)
9. [Retention and your controls](#retention-and-your-controls)
10. [Your privacy rights](#your-privacy-rights)
11. [Automated decision-making](#automated-decision-making)
12. [Children](#children)
13. [Changes](#changes)
14. [Contact and complaints](#contact-and-complaints)

---

## Summary

- Airlock **does not** require you to register for **our** online service to operate.
- Workspace data (collections, environments, request history, HTTP cookies used for testing, imported certificates, runner plans, tenant/workspace metadata) is stored **locally** on your device, under the Electron **userData** directory (e.g. on Windows, typically under `%APPDATA%`, under an application-specific folder name).
- Network traffic is sent **only to destinations you configure** (API URLs, authentication servers, etc.). That traffic is **not routed through our servers** as an application intermediary.
- The reference codebase this Policy describes **does not** include product telemetry, remote crash reporting to us, or forced automatic updates to our infrastructure.

---

## Controller and scope

For personal information processed **solely on your device** by the Airlock application **without transmission to us**, **you** are often the effective controller of that content (e.g. API payloads you type). For information practices **described in this Policy** as relating to **our** distribution of the software (e.g. communications you send to us, or future optional cloud features if ever added), the **controller** is the entity identified in **Contact** below, unless we notify you otherwise.

This Policy covers the **desktop application** behaviour described here. It does **not** govern third-party APIs or websites you contact using Airlock.

---

## Personal information we may process

What is processed depends on how you use the app. It may include:

| Category | Examples |
|----------|----------|
| **Information you enter** | URLs, HTTP methods, headers, bodies, scripts, environment variables, tokens or keys in headers or environments, collection/folder names, notes. |
| **Information persisted on disk** | JSON files for collections, environments, request history, client cookie jar, imported certificates, runner plans, tenant metadata. |
| **Information generated through use** | History entries, stored responses where the feature exists. |
| **Technical information (indirect)** | When you send requests, **your** OS and network stack may disclose IP addresses, DNS metadata, and TLS information to **third-party servers you choose** — inherent to the Internet and outside our control as a “cloud backend” for Airlock. |

Airlock is **not intended** to process special categories of data under GDPR (e.g. health, biometric data for identification, political opinions). If you place such content in requests or environments, you are responsible for lawful grounds and safeguards.

**Sensitive information (U.S. and other contexts):** see the [US supplement](./privacy-policy-us-supplement.md) for California-style sensitive personal information disclosures where required.

---

## Purposes and lawful bases

We process the information above **on the device** to:

- Provide REST client functionality (create, edit, send, repeat requests).
- Persist your work between sessions.
- Apply settings you configure (environments, certificates, test cookies).

**Lawful bases (GDPR / UK GDPR / Swiss FADP-style framing):** performance at your request prior to a contract / provision of the software; **legitimate interests** in operating and securing a local developer tool; **consent** where we introduce optional processing that requires it and ask you separately.

**LGPD (Brazil):** see the [Brazil supplement](./privacy-policy-brazil-lgpd-supplement.md) for bases under Brazilian law in English.

---

## Sharing and recipients

- **Us (reference distribution):** we **do not** automatically receive your collection contents or API response bodies. There is **no mandatory** Airlock cloud backend described in this Policy.
- **Third parties you choose:** when you send a request, it goes to **your** specified server; that party’s privacy policy applies to that processing.
- **System providers:** OS vendors, antivirus, backup, or MDM solutions may access application data folders on your machine — outside our direct control.

We **do not sell** your personal information (as “sale” is commonly defined in U.S. state laws) in the operation of this local application as described. Details for U.S. residents are in the [US supplement](./privacy-policy-us-supplement.md).

---

## HTTP cookies, certificates, and request content

- **“Cookies”** here means **HTTP cookies** stored locally for API testing workflows, **not** tracking cookies for a website we operate.
- **Certificates** you import remain in local storage; protect your OS user account.
- **Request/response content** may contain personal data if you put it there; you are responsible for minimisation and lawful transmission to each destination.

---

## Storage, international transfers

Processing described as part of the **application** occurs **on your device**. We do not, under this Policy, operate a cloud service that **receives** that workspace data from the app by default.

**International transfers** may occur when **you** send HTTP requests to servers in other countries. In that case, the laws and contracts applicable to **that** recipient govern.

For any future processing where **we** act as controller and transfer data from the **EEA**, **UK**, or **Switzerland** to countries without an adequacy decision, we will rely on appropriate safeguards (e.g. Standard Contractual Clauses) and describe them in an updated Policy or product notice.

---

## Security

- Use **full-disk encryption**, an **OS login password**, and **careful backups** (environment files may contain secrets).
- Keep **Airlock** and your **OS** updated.
- Do not share exports of collections/environments that contain credentials.

No software is free of vulnerabilities. Report security issues via the contact channel below.

---

## Retention and your controls

Data remains until you **delete it in the app**, **delete files** in the user data folder, or **uninstall** and remove residual files per your OS.

For data **already transmitted** to third parties, deletion must be requested from **those** controllers.

---

## Your privacy rights

Rights vary by country. Below is a **non-exhaustive** overview for common cases. They apply to processing **for which we are controller**; for purely **local** files, you exercise access, correction, erasure, and portability in practice by **managing files and settings** on your device.

| Region | Highlights |
|--------|------------|
| **EEA / UK / Switzerland** | Access, rectification, erasure, restriction, objection (where applicable), data portability, withdraw consent, lodge a complaint with a supervisory authority. |
| **Canada** | Access and correction under PIPEDA (federal) or substantially similar provincial laws; withdrawal of consent where reasonable, subject to legal/contractual limits. |
| **Australia** | Access and correction under the *Privacy Act 1988* (Cth) and Australian Privacy Principles where we act as APP entity for covered processing. |
| **Singapore** | Access and correction under the PDPA; withdrawal of consent subject to exceptions. |
| **Japan** | Disclosure, correction, cessation of use, cessation of third-party provision, and records of third-party provision under APPI, where applicable to our role. |

**United States:** see the [US supplement](./privacy-policy-us-supplement.md).  

**Brazil:** see the [Brazil supplement](./privacy-policy-brazil-lgpd-supplement.md).

We will respond to verifiable requests within timelines required by applicable law. We may need to verify your identity. You may **appeal** a refusal where local law provides an appeal right (e.g. certain U.S. states).

---

## Automated decision-making

Airlock **does not** use personal data for automated decisions that produce legal or similarly significant effects concerning you, as described in GDPR Article 22.

---

## Children

Airlock is a **professional developer tool** and is **not directed** at children. We do not knowingly solicit personal information from children. If you are a parent or guardian and believe we have received information from a child in a context we control, contact us and we will take appropriate steps.

---

## Changes

We may update this Policy when software behaviour changes (network, storage, or integrations). The date at the top shows the last revision. Review release notes for your distribution.

---

## Contact and complaints

**Reference publisher (as per project metadata):** Matheus — **Airlock** (see `package.json` and project metadata).

- **Support website / repository:** https://github.com/MrChase95/airlock  
- **Support and privacy contact email:** mferreira95@protonmail.com

**Supervisory authorities (examples — non-exhaustive):**

- **EEA:** your local data protection authority.  
- **UK:** Information Commissioner’s Office (ICO).  
- **Switzerland:** Federal Data Protection and Information Commissioner (FDPIC).  
- **Canada:** Office of the Privacy Commissioner of Canada (OPC).  
- **Australia:** Office of the Australian Information Commissioner (OAIC).  
- **Singapore:** Personal Data Protection Commission (PDPC).  
- **Japan:** Personal Information Protection Commission (PPC).  

Brazil-specific authority and wording: [Brazil LGPD supplement](./privacy-policy-brazil-lgpd-supplement.md).

---

*This text is informational and does not constitute legal advice. Adapt entity name, contacts, and roles (controller/processor) to your actual publishing model (individual, company, app store, enterprise distribution).*

**Other languages:** [Portuguese (Português)](./politica-de-privacidade.md)
