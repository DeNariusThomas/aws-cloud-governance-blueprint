# IAM Policies – Access Control Framework

This folder contains custom IAM policy JSON files used to enforce least-privilege access and align identity permissions with governance standards across AWS environments.

## 📄 Files

- `cross-account-access-policy.json`:  
  Grants specific IAM roles permission to assume roles in other AWS accounts. Used to support centralized governance, auditing, or security tooling from a management account.

- `readonly-audit-policy.json`:  
  Defines read-only access to critical services such as CloudTrail, AWS Config, and S3. Ideal for auditors, compliance roles, or security analysts who need visibility without modification rights.

- `limited-s3-access-policy.json`:  
  Grants fine-grained access to a specific S3 bucket with conditional permissions based on resource tags and IAM conditions.

## ✅ Use Case

These policies support a security-first approach to cloud governance by enabling granular access control and facilitating centralized compliance oversight.

