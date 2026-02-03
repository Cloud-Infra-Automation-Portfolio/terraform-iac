## Terraform Infrastructure as Code: Multi-Cloud Automation and Governance

Designed and implemented a multi-cloud Terraform project to provision and manage infrastructure across AWS and Azure, using modular code, remote state backends, and policy-as-code to enforce consistency, security and governance.

---

## Overview

This project demonstrates practical Infrastructure as Code workflows using Terraform, including multi-cloud provisioning, modular design, secure remote state management and policy enforcement. The focus is on repeatability, safe change management and production-aligned IaC practices.

---

## What I Built

- Multi-cloud Terraform configuration for AWS and Azure.
- Modular IaC structure for reusable infrastructure components.
- Secure remote state backends (S3 + DynamoDB, Azure Blob Storage)
- Resource tagging, versioning, and lifecycle automation.
- Policy-as-Code validation using OPA and Conftest.

---

## Diagram

![Terraform Architecture](diagram.png)

---

## Implementation Highlights

- Provisioned AWS and Azure resources using separate Terraform providers.
- Configured secure remote state with locking and versioning.
- Applied modular design for scalable infrastructure reuse.
- Deployed and validated resources across both cloud consoles.
- Cleaned up all infrastructure using Terraform destroy workflows.

---

### Advanced Terraform Capabilities
- Multi-region AWS deployments using provider aliases
- Reusable infrastructure via Terraform Registry modules
- Policy-as-Code enforcement using OPA and Conftest to validate plans before apply
  
---

## Screenshots

Selected screenshots validating Terraform plans, applies and remote state configuration are included in the `screenshots/` directory.

---

## Key Takeaways

- Terraform enables consistent, repeatable infrastructure across clouds.
- Remote state and locking are critical for safe team workflows.
- Modular IaC improves maintainability and scalability.
- Policy-as-Code shifts security and compliance earlier in the lifecycle.

---

## Notes

This project was developed for portfolio purposes to demonstrate production-aligned Terraform workflows. Some configurations are simplified compared to enterprise environments.

---

## References

- [Terraform Docs – AWS Provider](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
- [Terraform Docs – Azure Provider](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)
- [Terraform Remote State](https://developer.hashicorp.com/terraform/language/state/remote)

---

## Contact

Maintained by Sebastian Silva C. – Berlin, Germany  
LinkedIn: https://www.linkedin.com/in/sebastiansilc
