#  Risk Register Documentation

##  Purpose
This file documents the structure and usage of `risk-register.xlsx`, which serves as the central repository for all identified risks within the SecureBridge-GRC framework.  
It supports ISO 27001 compliance by providing a consistent, auditable record of risk assessments, treatment strategies, and control mappings.

##  File Location
`phase-2-risk-management/risk-register.xlsx`

##  Structure
The spreadsheet contains the following columns:

| Column Name             | Description |
|-------------------------|-------------|
| **Risk ID**             | Unique identifier for each risk (e.g., RSK-001) |
| **Risk Description**    | Summary of the threat, vulnerability, and potential impact |
| **Asset**               | The system, data, or process affected |
| **Likelihood (1–3)**    | Probability of occurrence: Low (1), Medium (2), High (3) |
| **Impact (1–3)**        | Severity of consequences: Low (1), Medium (2), High (3) |
| **Risk Score**          | Calculated as Likelihood × Impact |
| **Risk Level**          | Categorized as Low (1–3), Medium (4–6), High (7–9) |
| **Risk Owner**          | Person responsible for managing the risk |
| **Treatment Strategy**  | Mitigate, Transfer, Accept, or Avoid |
| **Treatment Plan Summary** | Brief description of mitigation actions |
| **Linked Control(s)**   | ISO 27001 Annex A control references |
| **Status**              | Open, In Progress, or Closed |
| **Review Date**         | Next scheduled review or reassessment date |

##  Usage Guidelines
- Each row represents a unique risk entry.
- Risk Score determines prioritization and urgency.
- Treatment strategies must be linked to Annex A controls.
- Review dates should be updated after each reassessment.
- Use conditional formatting to highlight high-risk items.
- Link each entry to a full assessment in `archive/previous-assessments/`.

##  Maintenance
- Update the register monthly or after major changes to assets or controls.
- Ensure consistency with `risk-assessment-template.md` and `statement-of-applicability.md`.
- Archive outdated or resolved risks for traceability.

---

For questions or updates, contact the GRC team lead or submit a pull request with your proposed changes.
