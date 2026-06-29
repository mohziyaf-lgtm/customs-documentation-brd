# Customs Documentation Workflow — Gap Analysis BRD

**N M Ziyaf**

Supply Chain Business Analyst
---

## Overview

This Business Requirements Document presents the findings of a structured gap analysis I conducted on the customs documentation workflow within a CargoWise One freight forwarding environment.

The analysis was driven by a pattern of recurring customs clearance delays and documentation errors I identified through operational performance data review. The document covers the full BA lifecycle from problem identification through to implementation planning and success metrics.

---

## Business Problem

Customs documentation errors were affecting approximately 12 percent of shipments, causing average clearance delays of 2.4 days per affected shipment, manual document chasing on 35 percent of shipments, and SOP compliance rates of only 68 percent across operational teams.

---

## Key Findings

| Gap | As-Is | To-Be | Priority |
|-----|-------|-------|----------|
| Mandatory field validation | No validation enforced in CargoWise One | Mandatory fields configured, incomplete records blocked | Critical |
| Pre-submission checkpoint | No check before external lodgement | Automated checklist before broker submission | Critical |
| Milestone trigger linkage | Document generation not linked to milestones | Triggers linked to shipment milestone events | High |
| SOP enforcement | SOPs outside system, operator memory only | In-system guided checklist aligned to SOP | High |

---

## Target Outcomes

| KPI | Baseline | Target |
|-----|----------|--------|
| Documentation error rate | 12% | Less than 3% |
| Clearance delay due to documentation | 2.4 days | Less than 0.5 days |
| Manual document chase rate | 35% | Less than 5% |
| SOP compliance rate | 68% | Greater than 95% |

---

## Document Contents

| Section | Content |
|---------|---------|
| 1 | Executive Summary |
| 2 | Background and Business Context |
| 3 | Scope |
| 4 | Stakeholders |
| 5 | As-Is Process Analysis and Root Cause Analysis |
| 6 | Gap Analysis |
| 7 | Functional Requirements FR-001 to FR-011 |
| 8 | To-Be Process Design |
| 9 | Non-Functional Requirements |
| 10 | UAT Approach and Test Scenarios |
| 11 | Implementation Plan |
| 12 | Success Metrics |
| 13 | Assumptions and Constraints |
| 14 | Document Control |

---

## Files

Customs_Documentation_BRD_v1.2.docx — Full BRD in Word format

Customs_Documentation_BRD_v1.2.pdf — Full BRD in PDF format

---

## Methodology Applied

Gap analysis using as-is vs to-be state mapping across four workflow areas. Root cause analysis using the 5-Why methodology applied to primary failure patterns. Requirements elicitation producing 11 functional requirements with full traceability to identified gaps. UAT design with six test scenarios mapped to acceptance criteria. Six Sigma process improvement principles applied to defect identification and classification.

---

## Project Context

This document replicates the business analysis artefact I produced during gap analysis work on CargoWise One customs workflows in an international freight forwarding environment. All organisational references and process data are based on anonymised scenarios from real operational experience. No proprietary or confidential data has been used.

---

## Author

N M Ziyaf
Supply Chain Business Analyst, Sydney NSW
linkedin.com/in/ziyafmohamed
