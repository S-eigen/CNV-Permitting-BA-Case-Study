# CNV Permit Application Process - Business Analysis Case Study

**Prepared by:** Sara Zhanturina  
**Date:** April 2026  
**Tools:** Canva, Microsoft Word, Microsoft Excel, BABOK Guide

---

## Project Background

The City of North Vancouver 2024 Annual Municipal Report identified the implementation of a new Enterprise Permitting and Licensing software as a key initiative for the Planning and Development Department.

This case study applies Business Analysis methodology to analyze the current permit process, identify pain points, and propose a future-state solution.

**Key CNV facts (source: CNV Annual Municipal Report 2024):**
- 4,500+ resident service requests processed annually
- 1,000+ street use permits issued annually
- 250+ building permits issued (2024)
- Approximately 7,000 registered businesses requiring annual licence renewals

---

## Problem Statement

The current permit application process relies on manual steps, email-based communication, and paper submissions. This results in long processing times and limited visibility for applicants into their application status.

---

## Artifacts

| File | Description |
|------|-------------|
| `BPMN_AsIs.png` | Current state process - swim lane diagram showing pain points |
| `BPMN_ToBe.png` | Future state process - automated workflow with BR references |
| `RootCause.png` | Why-Why analysis - 4 root causes traced to solution |
| `UseCase.png` | Use Case diagram - 4 actors, 9 use cases |
| `BRD.docx` | Business Requirements Document - 23 requirements with MoSCoW prioritisation |
| `RTM.xlsx` | Requirements Traceability Matrix - all requirements with stakeholders and test criteria |

---

## Key Findings (Current State)

- Applications submitted by paper or email with no digital portal
- No automated completeness check - staff manually review every submission
- Referrals to Engineering and Fire sent by email with no tracking system
- Applicants must call Planning to get status updates
- No SLA monitoring or automated reminders

---

## Proposed Solution (Future State)

Enterprise Permitting and Licensing System addressing 4 root causes:

- **BR-01, BR-05** - Online application portal with guided checklist
- **BR-02** - Automated completeness validation
- **BR-06** - Automated routing to departments
- **BR-07** - Shared review dashboard
- **BR-08** - Auto-generated decision letter
- **BR-11, BR-12** - Self-service status tracking and notifications

---

## Tools and Frameworks Used

- BPMN (Business Process Model and Notation)
- BABOK Guide
- MoSCoW prioritisation
- Why-Why Root Cause Analysis
- Use Case modeling
- Requirements Traceability Matrix (RTM)

---

*Data sourced from CNV 2024 Annual Municipal Report (audited by BDO Canada LLP)*  
*github.com/S-eigen*
