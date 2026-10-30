# Products | معرفی محصولات

[← Profile](../../profile/README.md) · [Ecosystem map](ecosystem.md) · [Repositories](repository-map.md)

**How to read this page:** Product examples explain intended user journeys. Source evidence is not a claim of live production availability. The 2026 ecosystem catalog supplies vision; repository audits supply code scope.

## Hamava Design

**User:** Building and ELV designers. **Problem:** Drawings, quantities and revisions become disconnected from purchasing and maintenance.

**Example:** Design a building network and prepare a bill of materials for later procurement. **Evidence:** The catalog describes this goal. The current Hamava_Design GitHub code still requires reconciliation with the actual product, so the integrated workflow is not verified from that source.

## Furnish

**User:** Cabinet designers and customers. **Problem:** Layout choices, workshop quantities and previews are scattered.

**Example:** Create a kitchen project, change cabinet layout, save versions, prepare a rendering-reference package and import an externally rendered result.

**Evidence:** Django accounts/billing/designer modules, Three.js-based interaction, geometry and material calculations. **Limit:** Direct third-party AI rendering inside the web app is not established in the reviewed source.

## XRM and XRM-ME

**User:** Teams tracking companies, contacts, equipment, services and approvals. **Example:** Authorized staff access a service/equipment record with controlled permissions.

**Evidence:** XRM contains Next.js, FastAPI, PostgreSQL/Alembic, architecture contracts and testing tools. The separate XRM-ME repository currently has contracts and infrastructure notes, not a full product README. The 12-module XRM ecosystem remains a broader product vision.

## HamDirect

**User:** Instagram business page managers. **Example:** Create a draft rule for a product-price keyword, prepare proposed comment and DM text, then preview before operation.

**Evidence:** Next.js RTL dashboard, FastAPI page roles, draft rules, keyword matching, simulation and guarded account integration. **Limit:** The reviewed source labels the draft, simulation and parts of the integration non-sending; real message dispatch was not verified.

## VISISTECH Commerce

**User:** Professional buyers of network and ELV hardware. **Example:** Find a technical product, add it to a cart and move to checkout.

**Evidence:** Next.js storefront and FastAPI catalog, inventory, order and payment modules. **Limit:** Code presence alone does not verify every production payment journey.

## HamavaYar Workforce

**User:** Employees and site managers. **Example:** Check in from the field and record daily tasks for supervisor review.

**Evidence:** Attendance Mini App with Telegram identity and location/selfie checks; separate workforce core for reports, KPIs and performance records. Deployment interconnection needs separate verification. [Public case study](https://github.com/HamavaELV/hamavayar-attendance-case-study).

## Hamava Support

**User:** Customers and support staff. **Example:** Create a ticket and follow it through a connected CRM support process.

**Evidence:** Django API, React portal, attachments, background work and CRM integration. [Public case study](https://github.com/HamavaELV/customer-support-crm-case-study).

## VISIS Platform

**User:** ELV customers and network design teams. **Example:** Request consultation, map a network and organize quantities.

**Evidence:** Multi-application repository for customer portal and network mapping. [Public case study](https://github.com/HamavaELV/elv-platform-network-mapping-case-study).

## ShenavaPlus

**User:** Swimmers and coaches looking for online or in-person classes. **Vision:** Discover coaching, plans and enrollment paths.

**Source limitation:** The organization repository `shenava` is empty in the reviewed snapshot, so implementation claims require a source push and audit.

## Hamava Sakht

**User:** Construction operations teams. **Vision:** Structured site workflows and construction project operations.

**Evidence:** Frontend/backend/infra folders plus a brief architectural README. End-to-end production behavior has not been verified.

---

**Publication rule:** Show a feature as *planned*, *present in source*, *accepted*, or *released* based on evidence. Never expose private infrastructure or customer data.
