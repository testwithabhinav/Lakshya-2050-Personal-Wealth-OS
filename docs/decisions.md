# Engineering Decision Log

This document records major architectural, engineering, and financial decisions made during the development of Lakshya 2050.

---

# EDR-001

## Title

Adopt Git Flow for Development

## Date

01 July 2026

## Decision

Use three permanent branches:

- main
- develop
- feature/sprint-x-name

## Reason

Maintain a stable production branch while enabling structured feature development.

---

# EDR-002

## Title

Excel as MVP

## Date

01 July 2026

## Decision

Use Microsoft Excel as the first implementation before moving to Power BI and Spring Boot.

## Reason

Rapid development and validation of the financial model before investing in application development.

---

# EDR-003

## Title

Three-Layer Workbook Architecture

## Decision

Separate the workbook into:

- Input Layer
- Calculation Layer
- Dashboard Layer

## Reason

Improve maintainability, scalability, and testing.

---

# EDR-004

## Title

Sprint-Based Development

## Decision

Development will follow sprint-based iterations.

## Reason

Deliver small, testable increments and maintain consistent progress.

---

# EDR-005

## Title

Semantic Versioning

## Decision

Adopt Semantic Versioning.

Examples:

- v0.1.0
- v0.2.0
- v1.0.0

## Reason

Provide predictable release management.

---

# EDR-006

## Title

Excel as Single Source of Truth

## Decision

Power BI and future AI modules will consume data from the Excel model.

## Reason

Maintain one authoritative data source during MVP development.

---

# EDR-007

## Title

Definition of Done

A feature is complete only when:

- Development complete
- Documentation updated
- Sample data added
- Tested
- Committed
- Merged to develop

---

# Future Decisions

This section will be expanded as the project evolves.