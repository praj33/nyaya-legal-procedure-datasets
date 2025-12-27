# NYAYA Legal Procedure Datasets

This repository contains **structured, ingestion-ready legal procedure datasets** and **law coverage audits** for use in NYAYA AI.

## Scope

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

data/
├── procedures/
│ ├── india/
│ ├── uae/
│ ├── uk/
│ └── ksa/
│
├── audits/
│ ├── law_coverage_india.md
│ ├── law_coverage_uae.md
│ ├── law_coverage_uk.md
│ └── law_coverage_ksa.md
│
└── sources/
├── sources_india.md
├── sources_uae.md
├── sources_uk.md
└── sources_ksa.md

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

**Status:** Complete and ingestion-ready
