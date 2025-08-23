#  Risk Treatment Plan

This document summarizes how identified risks are being treated across SecureBridge-GRC.  
Each entry corresponds to a risk in the Risk Register and links to its full assessment and applicable ISO 27001 controls.

---

## Treatment Strategy Options
- **Mitigate** – Reduce likelihood or impact through controls
- **Transfer** – Shift risk to a third party (e.g., insurance, vendor contracts)
- **Accept** – Acknowledge and monitor without active mitigation
- **Avoid** – Eliminate the activity or asset causing the risk

---

## Treatment Plan Table

| Risk ID | Risk Description | Treatment Strategy | Mitigation Actions | Owner | Target Date | Linked Control(s) | Status |
|---------|------------------|--------------------|---------------------|--------|-------------|-------------------|--------|
| RSK-001 | Unauthorized access to production database | Mitigate | Implement RBAC and MFA | DevOps Lead | 2025-09-30 | A.9.1.2, A.12.4.1 | In Progress |
| RSK-002 | Phishing attack targeting employee credentials | Mitigate | Awareness training + phishing simulations | IT Security | 2025-09-15 | A.7.2.2, A.12.6.2 | Open |
| RSK-006 | Insecure third-party vendor integration | Transfer | Update contracts with security SLAs and audit rights | Vendor Manager | 2025-09-25 | A.15.1.1, A.15.2.1 | In Progress |

---

##  Review Cycle
Treatment plans are reviewed:
- Quarterly
- After major incidents
- When risk scores change significantly

---

##  Notes
- Treatment actions must be realistic, time-bound, and assigned to a responsible owner.
- Link each row to the full assessment in `archive/previous-assessments/`.
- Update status as actions progress (e.g., Open → In Progress → Closed).

