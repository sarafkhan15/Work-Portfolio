**Optimising Faith‑Driven Operations with BPMN — FaithWorks Case Study
**
A visual, GitHub‑friendly summary of a full BPM lifecycle redesign: from AS‑IS pain points to TO‑BE automation using barcode‑enabled IMS and cloud POS.

TL;DR

Org: FaithWorks Food Assist (non‑profit food relief)

Scope: 2 core processes — Categorical Sorting & Storage and Customer Service & Checkout

Method: BPM Lifecycle → AS‑IS → Gap Analysis → TO‑BE BPMN → Improvement Plan

Tech: Barcode inventory (IMS), cloud POS with discount logic, digital receipts

Impact (expected): Lower errors, faster checkout, traceability, data for continuous improvement

Problem & Goal

FaithWorks serves ~180–200 families daily but relies on manual, verbally taught procedures. This causes duplicated work, inconsistent discount rules, and limited visibility. We aimed to standardise, digitise, and de‑risk operations while keeping costs low and processes volunteer‑friendly.

What I Did

Conducted stakeholder interview with the store manager

Modelled AS‑IS BPMN for Sorting/Storage and Checkout

Designed TO‑BE BPMN with barcode‑enabled IMS, POS integration, and exception handling

Built comparison tables and a change plan (training, documentation, pilots)

Full 20+ page report in /docs/report.pdf

Before → After (at a glance)

Area

AS‑IS

TO‑BE

Inventory tracking

Memory/paper, ad hoc

Barcode + IMS with digital traceability

Sorting & allocation

Repetitive cross‑handoffs

IMS rules suggest allocation; team verifies

Free‑item rules

Applied inconsistently

POS applies rules automatically

Produce weighing

Manual calc

Integrated scale auto‑charges over 2kg

Receipts

Handwritten / skipped

Printed or SMS/email fallback

Exceptions

Ad hoc workarounds

Defined fallbacks for scan/pos/printer issues

Diagrams (Previews)

Replace image file names with your exported PNG/SVGs.

AS‑IS — Categorical Sorting & Storage

AS‑IS — Customer Service & Checkout

TO‑BE — End‑to‑End Barcode Stock Flow

TO‑BE — Digitally Assisted Checkout

Tip: keep filenames lowercase-with-dashes and export at 2x for crisp GitHub rendering.

Key Design Choices

Low‑lift tech: Barcode IMS + cloud POS chosen for low cost and simple training

Human‑centred: Clear fallbacks (manual receipts, off‑system pay) during outages

Data first: Weekly automated stock updates; auditable logs for reviews

BPM alignment: Models reflect gateways for exceptions and volunteer variability

Repo Guide

.
├── README.md                  # You are here
└── docs/
    ├── report.pdf             # Full report (exported from Word)
    ├── as-is-diagrams/        # PNG/SVG exports
    │   ├── as-is-sorting.png
    │   └── as-is-checkout.png
    └── to-be-diagrams/
        ├── to-be-inventory.png
        └── to-be-checkout.png

Results & Next Steps

Expected outcomes: Shorter queues, fewer pricing mistakes, consistent benefits, transparent stock

Pilot plan: Run a small‑scale pilot in storage + checkout; collect metrics (wait time, error rate)

Iterate: Use IMS/POS analytics for monthly reviews; expand automation gradually

How to Use This Repo

Read the diagrams above (open images full‑screen for detail).

Dive into the full report for lifecycle analysis and recommendations: /docs/report.pdf.

Open comparison tables in the report appendices to trace each change to an AS‑IS pain point.

