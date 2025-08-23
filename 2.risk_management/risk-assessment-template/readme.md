# Risk Assessment Template

Use this template to document individual risk assessments in detail.  
Each completed assessment should be saved in `archive/previous-assessments/` and linked from the corresponding row in `risk-register.xlsx`.

---

##  Risk ID
`RSK-XXX`  
*(Assign a unique identifier, e.g., RSK-001)*

## Risk Description
Describe the nature of the risk, including threat, vulnerability, and potential impact.  
> Example: Unauthorized access to production database due to weak access controls.

## Asset Affected
Name the asset, system, or process at risk.  
> Example: Production Database

##  Likelihood
Estimate the probability of occurrence:  
- Low (1) – Rare or unlikely  
- Medium (2) – Possible under certain conditions  
- High (3) – Likely or frequent

##  Impact
Estimate the severity of consequences:  
- Low (1) – Minimal disruption or damage  
- Medium (2) – Noticeable impact on operations or data  
- High (3) – Significant financial, reputational, or legal damage

##  Risk Score
`Likelihood × Impact = Risk Score`  
> Example: 3 × 3 = 9 (High Risk)

##  Risk Level
Based on score:  
- Low (1–3)  
- Medium (4–6)  
- High (7–9)

## Risk Owner
Name and role of the person responsible for managing this risk.  
> Example: DevOps Lead

##  Treatment Strategy
Choose one:  
- Mitigate  
- Transfer  
- Accept  
- Avoid

##  Treatment Plan
Outline the actions to be taken, including timelines and responsible parties.  
> Example: Implement role-based access controls and enable multi-factor authentication by Q4.

##  Linked Control(s)
Reference applicable ISO 27001 Annex A controls.  
> Example: A.9.1.2 – Access to networks and network services

## Review Date
Set a date for next review or reassessment.  
> Example: 2025-09-30

---

*Completed assessments should be version-controlled and stored in `archive/previous-assessments/RSK-XXX-risk-assessment.md` for traceability.*
