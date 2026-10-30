# GitHub portfolio inventory — what is actually here?

[← Organization profile](../../profile/README.md) · [Products explained](products.md) · [Ecosystem vision](ecosystem.md)

**Audit date: 2026-10-30.** The connected HamavaELV GitHub organization exposes **20 repositories** at this snapshot: **15 private and 5 public**. Repo count does not equal product count; one product may use multiple repositories, and infrastructure or case-study repositories are not standalone products.

**Status vocabulary:** `SOURCE` = tracked implementation/docs exist; `CASE STUDY` = public narrative without private source; `EARLY` = foundation or limited evidence; `RECONCILE` = registered repository does not yet establish product source parity; `EMPTY` = no tracked contents. None of these status labels means live deployment has been verified.

## The 20 repositories

| Repository | Visibility | Its purpose | Evidence/status |
| --- | --- | --- | --- |
| `hamava-landing` | Private | Corporate web experience and product/engineering portfolio notes | SOURCE; portfolio draft PR exists |
| `Visis-Platform` | Private | ELV digital customer services + engineering network mapping | SOURCE; public mapping case study available |
| `hamavaelv-support` | Private | Customer support portal and CRM integration | SOURCE; public support case study available |
| `hamavayar-secure-attendance-miniapp` | Private | Telegram field attendance safeguards and workflows | SOURCE; public attendance case study available |
| `hamavayar-attendance-case-study` | Public | Explain attendance architecture and decisions without releasing source | CASE STUDY |
| `customer-support-crm-case-study` | Public | Explain customer support/CRM workflow | CASE STUDY |
| `elv-platform-network-mapping-case-study` | Public | Explain digital ELV portal and network map | CASE STUDY |
| `persian-rtl-corporate-web-case-study` | Public | Explain corporate UI and content experience | CASE STUDY |
| `.github` | Public | Organization GitHub profile and contributor policies | SOURCE — this public portfolio documentation |
| `hamavayar-core` | Private | Tasks, work reports, QC/KPI and performance administration | SOURCE |
| `XRM-ME` | Private | Separate XRM-ME contracts/infrastructure workspace | EARLY; root README empty at audit |
| `Hamava-Sakht` | Private | Construction operations platform foundation | EARLY; basic architecture present |
| `Hamava_Design` | Private | Named design project repository | RECONCILE; tracked code needs verified ownership/product match |
| `hamava-core` | Private | Middleware/integration backend for organizational automations | SOURCE; different from XRM core |
| `n8n-infra` | Private | Workflow orchestration service infrastructure | SOURCE; infrastructure, not a customer product |
| `XRM` | Private | Modular XRM-ME web/API development and security contracts | SOURCE; review release status independently |
| `visistech-commerce` | Private | Network/ELV product storefront and commerce APIs | SOURCE; backend/frontend |
| `Furnish` | Private | Kitchen/cabinet layout, versioning, billing and materials | SOURCE; reviewed implementation and audit docs |
| `HamavaDirect` | Private | Instagram engagement rule design and guarded integration | SOURCE; sending unverified in audited branch |
| `shenava` | Private | Target source repository for ShenavaPlus | EMPTY in this GitHub snapshot |

## Why some public projects don't show their application source

The **four public case studies** are for prospective employers, collaborators or customers who want to understand the engineering without obtaining access to a confidential deployment. They highlight problems, design decisions, technology and implementation context. They are **not open-source versions** of the private applications.

- [Telegram attendance](https://github.com/HamavaELV/hamavayar-attendance-case-study)
- [Customer support and CRM](https://github.com/HamavaELV/customer-support-crm-case-study)
- [ELV mapping and platform](https://github.com/HamavaELV/elv-platform-network-mapping-case-study)
- [RTL corporate web](https://github.com/HamavaELV/persian-rtl-corporate-web-case-study)

## What to verify before a polished public launch

1. **Design:** Resolve the Hamava Design source mismatch before asserting concrete modules are shipped.
2. **ShenavaPlus:** Push an approved source snapshot to the currently empty `shenava` repository.
3. **HamDirect:** Check the active deployment and Meta permissions separately from draft/simulator code.
4. **XRM:** Resolve relationship between `XRM` and `XRM-ME`; cite one authoritative release lineage.
5. **Illustrations:** Approve anonymized actual screenshots before adding them to public case studies.
6. **Outcomes:** Only publish performance, uptime, adoption or ROI figures if independently evidenced.

## Repository organization ≠ the catalog's 12 product modules

The **12 catalog modules** are functional capabilities around an XRM vision. The **20 GitHub repositories** are source/documentation/infrastructure units. The counts measure different things, and should never be combined to suggest 20 fully launched software products.

*Portfolio inventory. No private source, customer data, secrets or live internal addresses reproduced.*
