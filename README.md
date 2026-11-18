# Semiconductor Value Chain — Cybersecurity & Export Control Compliance Matrix

> A clause-level map of the mandatory cybersecurity, data-protection and export-control obligations that apply to each segment of the semiconductor value chain, across China, the United States, the European Union and industry/customer-mandated standards.

**60 clauses · 30 evidence items · 10 customer segments · 8 obligation types**

Companion repository to [biopharma-cybersecurity-compliance-matrix](https://github.com/sixgods2020/biopharma-cybersecurity-compliance-matrix).

This is a compliance-obligation mapping, not legal advice. Article numbers must be verified against the official texts before external use — see the *Items to Verify* sheet.

---

## Why this one is different from the pharma edition

Semiconductors add **two enforcement lines that do not exist in pharma**:

1. **Export licensing.** No licence means illegality *and* immediate supply cut-off — worse than a fine, and without the remediation window that data compliance usually offers.
2. **Customer-mandated obligations.** Industry standards that carry no statutory force nevertheless decide whether a product can be sold at all.

The second one is the finding that took longest to accept: **in this industry the real legislator is frequently the customer, not the regulator.**

SEMI E187 is an industry standard. It is not law. But TSMC has written it into supplier procurement contracts since 2023. An equipment OEM that cannot produce the documentation does not enter the line — and there is no appeal, no hearing, no administrative review. Its practical force exceeds any fine in the table.

That is why this matrix expands the obligation taxonomy from six categories to eight, and adds `Customer-mandated` as a first-class enforcement class rather than a footnote.

## What is inside

| Sheet | Contents | Rows |
|---|---|---|
| **Coverage Overview** | Auto-calculated breakdown by jurisdiction, value-chain tier and enforcement strength, plus three conclusions drawn from the numbers | — |
| **Compliance Matrix** | The main deliverable: 60 clauses × 14 columns — regulation, article, obligation type, trigger, requirement, evidence, penalty, accountable party, field action | 60 |
| **Evidence Checklist** | Printable on-site checklist by customer type: what to request, what to look for, what its absence implies | 30 |
| **Items to Verify** | Clauses resting on public reporting or industry commentary rather than confirmed official text, with verification instructions | 10 |
| **How to Use** | Conventions, working sequence, known limitations | — |

### Segments covered

| Tier | Segments |
|---|---|
| Upstream | Semiconductor materials · Semiconductor equipment · Equipment components · EDA & IP cores |
| Midstream | Chip design (Fabless) · Wafer fabrication (Foundry / IDM) · Assembly & test (OSAT) |
| Downstream | Distribution · End applications (automotive, consumer, industrial, AI) |

### Jurisdictions covered

China · United States · European Union · Industry standard / Customer requirement

## How to read the enforcement grading

| Obligation type | What it means | Clauses |
|---|---|---|
| **Export licence** | No licence, no shipment. Harder than a fine because there is no remediation path. | 18 |
| **Customer-mandated** | Not law. The customer simply will not buy without it, and there is no appeal. | 8 |
| **Market authorization** | No certificate or certification, no market. | 8 |
| **Ongoing compliance** | Inspections, audits, annual assessments. No finish line. | 18 |
| **Incident reporting** | Statutory deadlines. Late reporting is itself a violation. | 2 |
| **Cross-border** | Unfiled transfer is unlawful, penalties at the top of the range. | 3 |
| **Ex-post penalty** | Only bites after an incident — but it bites named individuals. | 2 |
| **Contractual flow-down** | No statutory duty at all. Pressure arrives via customer contracts. | 1 |

## Three things this matrix changes

**1. Export control is harder than data compliance here.** Export-licence clauses cluster in materials, equipment, EDA and distribution, and none can be engineered around. No licence means no shipment; data compliance at least offers a remediation window. For semiconductor customers, export control is the opening topic and data compliance is the second.

**2. The real legislator is the customer.** Upstream equipment and component makers take most of their obligations from SEMI E187/E188 and fab procurement clauses, not from statutes. A component supplier has no statutory cybersecurity duty at all — it has a contractual one, imposed by an OEM that is itself under pressure from a fab.

**3. Design houses are now inside the compliance chain.** The BIS rule of November 2026 ties designer status — whether a company is an Approved or Authorized IC Designer — to whether its foundry and OSAT can ship. Design houses could previously outsource compliance to the foundry. Now their own identity documents determine their access to capacity.

## Anchor obligations

| Jurisdiction | Instrument | Why it is the anchor |
|---|---|---|
| China | 出口管制法 + 两用物项出口管制条例 (in force 1 Dec 2024) | Unified dual-use regime with a single control list. Art. 12(3) extends licensing to items *outside* the list where the exporter knows or should know of national security risk. |
| China | 网络安全法 (2025 amendment, in force 1 Jan 2026) + CII Regulations + 网络安全审查办法 | Leading fabs are very likely CII-designated. Procurement of EDA, tools and cloud all trigger review. |
| China | 反不正当竞争法 / 刑法 Art. 219 | Process recipes, layouts and yields are the core assets. No regulator inspects for this — the risk is commercial, not administrative. |
| US | EAR §744.24 (interim final rule, 16 Nov 2026) | Extends controls from physical shipment to remote compute: >12,000,000 aggregate TPP supplied to D:5 or Macao-headquartered entities. |
| US | EAR §744.23(a)(3)(i)(C) | Binds designer identity to foundry/OSAT licensing for advanced logic ICs. |
| US | NIST SP 800-171 + DFARS 252.204-7012 + CMMC 2.0 | 110 controls for CUI. **CMMC Phase 2 third-party certification was suspended on 13 July 2026** — self-assessment, SPRS posting and annual affirmation remain in force. |
| EU | NIS2 (EU) 2022/2555, Annex II C26 | Semiconductor manufacturing sits in C26 = *important entity* (not essential). Same obligations as essential entities; supervision is mainly ex-post. |
| EU | Dual-Use Regulation (EU) 2021/821, Annex I (updated 14 Sep 2026) | The 2026 update brought the whole EUV chain — mask and reticle inspection, Mo/Ru ALD, single-wafer cleaning — plus software and technology under control. |
| EU | Cyber Resilience Act (EU) 2024/2847 | Applies to products with digital elements. A chip sold standalone may fall directly in scope; as a component, obligations flow upward. |
| Industry | SEMI E187 / E188 / E191 | Fab equipment cybersecurity baseline, malware-free integration, status reporting. Contractually binding via fab procurement. |
| Industry | ISO/SAE 21434 + UN R155/R156 + GB 44495-2024 + SAE J3101 | Automotive chips. The 2026 compliance evidence package is as important as the datasheet. |

## Files

| File | Language | Sheets |
|---|---|---|
| `Semiconductor_Cybersecurity_Compliance_Matrix_EN.xlsx` | English | Coverage Overview · Compliance Matrix · Evidence Checklist · Items to Verify · How to Use |
| `Semiconductor_Cybersecurity_Compliance_Matrix_ZH.xlsx` | 中文 | 覆盖概览 · 合规对照主表 · 现场索取清单 · 待复核事项 · 使用说明 |

Both workbooks are generated from a single bilingual data source, so clause numbering and content are guaranteed to align one-to-one (1–60, same order, same evidence items).

## How to use it

1. **Locate the customer.** Filter the Compliance Matrix by `Tier` and `Segment`.
2. **Read the enforcement strength.** `Export licence` and `Market authorization` are where budget can be discussed now. `Customer-mandated` means the customer is being squeezed by its own customer — the sale has to ride that pressure. `Contractual flow-down` means there is no legal driver at all; bundle, never lead.
3. **Collect evidence.** Work through the Evidence Checklist. The *What its absence means* column is written as talking points.
4. **Clear the verification list.** Several instruments moved during 2025–2026. Confirm every "Pending" item before external use.

## Known limitations

- **No market sizing, fund allocations or local subsidies.** Compliance obligations only.
- **Article numbers require version checks.** The Cybersecurity Law, the EU dual-use list, EAR §744.24 and CMMC are all in motion.
- **Sub-domains not itemised.** Photomask manufacturing, compound semiconductors and advanced packaging are not broken out separately; refurbished and second-hand equipment trade is out of scope.
- **CMMC status is a moving target.** Phase 2 was suspended in July 2026 pending a reform review. Confirm the current position before advising a customer.

## Scope note

Built for compliance assessment and pre-sales qualification. It maps obligations to evidence; it does not interpret how a specific regulator will apply them to a specific product or transaction. Engage qualified export-control and regulatory counsel for licensing decisions.

## Disclaimer

Not legal advice. No warranty of completeness or accuracy. Export-control determinations are fact-specific and jurisdiction-specific; verify against official texts before relying on any clause.

## Licence

Content released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Reuse with attribution.
