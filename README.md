# Joe Kollie - Cloud Security Engineer

> Building AWS security infrastructure in public, and codifying it with Terraform.

---

## 📍 Right Now

- 🎓 Pursuing a **Master of Science in Cybersecurity** at **Saint Louis University**
- 📘 Preparing for the **HashiCorp Terraform Associate (004)** exam
- 🧪 Publishing hands-on Terraform labs as I study: state refactoring, module design, testing, and CI

---

## 🔐 What I Build

| Area | Focus |
|------|-------|
| AWS Security | VPC architecture · IAM · GuardDuty · Security Hub |
| Detection Engineering | MITRE ATT&CK · CloudTrail · VPC Flow Logs |
| Infrastructure as Code | Terraform modules · `terraform test` · CI/CD security gates · Auto-remediation |
| Identity & Access | Entra ID · RBAC · Conditional Access · RACF |

---

## 🚀 Featured Projects

### [🛡️ Secure Multi-Tier AWS VPC](https://github.com/JoeKollie01/aws-secure-multi-tier-vpc)
Production-style 4-tier AWS VPC across 2 Availability Zones with least-privilege security group chaining, VPC Flow Logs, and bastion host access control. Security controls were verified live: direct SSH to private instances is blocked, confirmed with a network timeout test.

`AWS` `VPC` `Security Groups` `CloudWatch` `EC2` `Flow Logs`

---

### [📊 AWS Security Logging Pipeline](https://github.com/JoeKollie01/aws-security-logging-pipeline)
Terraform-deployed security baseline: multi-region CloudTrail, GuardDuty, VPC Flow Logs, and encrypted S3 log storage with lifecycle management. One `terraform apply` deploys the full account security baseline.

`Terraform` `CloudTrail` `GuardDuty` `IaC` `AWS`

---

### [🧱 Secure S3 Bucket Terraform Module](https://github.com/JoeKollie01/terraform-aws-s3-bucket-module)
Reusable, secure-by-default S3 module: enforced public access block, encryption (AES256 or KMS), HTTPS-only bucket policy, versioning, and mandatory tags that callers can't override. Unit tested with `terraform test` and mocked providers (no AWS credentials needed), validated in GitHub Actions CI, and released with semantic versioning and Git tags.

`Terraform` `Modules` `terraform test` `GitHub Actions` `S3` `Security by Default`

---

### [🔁 Terraform State Refactoring Lab](https://github.com/JoeKollie01/terraform-state-refactoring-lab)
Scenario-based lab for refactoring a legacy Terraform config **without destroying anything**: renaming with `moved` blocks, migrating `count` to `for_each`, extracting modules, importing hand-made resources with `import` blocks, splitting state between teams with `removed` blocks, and recovering from state mistakes.

`Terraform` `State Management` `moved` `import` `removed` `Refactoring`

---

## 🏫 Education

- **M.S. Cybersecurity**, Saint Louis University, *in progress*
- **B.S. Cybersecurity**, Rasmussen University, *Summa Cum Laude* (GPA 3.89)
- **A.A.S. Network & System Administration**, Hennepin Technical College, *Cum Laude* (GPA 3.57), Phi Theta Kappa

---

## 🏅 Certifications

- ✅ AWS Certified Solutions Architect – Associate
- ✅ AWS Certified Cloud Practitioner
- ✅ Cisco CCNA
- ✅ Fortinet NSE 2
- 📘 HashiCorp Terraform Associate (004), *in progress*

---

## 📡 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Joe_Kollie-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/joe-kollie-a38711148)
[![GitHub](https://img.shields.io/badge/GitHub-JoeKollie01-181717?style=flat&logo=github)](https://github.com/JoeKollie01)
