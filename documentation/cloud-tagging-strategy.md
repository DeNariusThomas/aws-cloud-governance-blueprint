# Cloud Tagging Strategy

This file outlines a standardized tagging strategy to ensure traceability, ownership, and audit readiness across AWS resources. Tagging is a critical component of governance in cloud environments.

## 🎯 Objectives
- Enforce consistent resource tagging
- Improve cost tracking and accountability
- Support compliance audits and incident response

## 🏷️ Required Tags

| Tag Key        | Description                          | Example           |
|----------------|--------------------------------------|-------------------|
| `Environment`  | Stage of the resource lifecycle      | `Production`      |
| `Owner`        | Resource owner or responsible party  | `dthomas`         |
| `Project`      | Project or initiative name           | `GRC-Tracker`     |
| `CostCenter`   | Billing or finance reference         | `CC-1057`         |
| `Compliance`   | Regulation/standard if applicable    | `HIPAA` or `NIST` |

## 🔒 Enforcement
- IAM and SCPs restrict untagged resource creation
- AWS Config rules monitor for missing required tags
- Resources missing critical tags trigger alerts

## 📌 Notes
This tagging strategy complements broader governance frameworks and should be reviewed quarterly for alignment with evolving policies.

---

Maintained by: **DeNarius Thomas**  
Updated: `June 2025`
