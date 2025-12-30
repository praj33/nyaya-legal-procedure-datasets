# NYAYA Legal Procedure Datasets

This repository contains **structured, ingestion-ready legal procedure datasets** and **law coverage audits** for use in NYAYA AI.

## Scope

## Versions

- **v1.1** — Frozen procedural datasets  
  - Country- and domain-specific legal procedures  
  - Conditional branching, outcome intelligence, cost/effort, and risk flags  
  - Fully ingestion-ready and production-stable  

- **v2.0** — Executable procedural intelligence (schema-only)  
  - System-level schemas for escalation, failure paths, evidence readiness, and compliance  
  - No procedural JSONs modified  
  - Designed to power reasoning engines, RL training, and UI flow control

### Jurisdictions
- India
- United Arab Emirates (UAE)
- United Kingdom (UK)
- Saudi Arabia (KSA)

### Legal Domains
- Criminal
- Civil
- Family
- Consumer / Commercial

## Repository Structure

```text
data/
├── procedures/
│   ├── india/
│   ├── uae/
│   ├── uk/
│   └── ksa/
│
├── audits/
│   ├── law_coverage_india.md
│   ├── law_coverage_uae.md
│   ├── law_coverage_uk.md
│   └── law_coverage_ksa.md
│
└── sources/
    ├── sources_india.md
    ├── sources_uae.md
    ├── sources_uk.md
    └── sources_ksa.md
```
## Data Principles
- Source-based only (official statutes and government portals)
- No legal interpretation or inference
- Additive and non-invasive
- Structured for direct ingestion by downstream systems

## Contents
- **Procedure JSONs**: Step-by-step legal workflows per country and domain
- **Law Coverage Audits**: Visibility into covered vs missing laws
- **Source Lists**: Verified reference links (links only)

## Usage
Designed for direct consumption by:
- Legal AI ingestion pipelines
- Agent behavior and reasoning systems
- Frontend procedural flow rendering

---

**Status:**  
- v1.1 procedures: Complete and ingestion-ready  
- v2.0 schemas: Production-ready (execution intelligence, schema-only)

