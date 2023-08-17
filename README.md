# Unveiling the Power of AWS 3-Tier Architecture with Terraform: Building a Resilient and Scalable VPC

---

## Architecture Diagram

![AWS 3 tier Architecture - VPC and Components](/architecture-diagram/AWS%203%20Tier%20Architecture.png)

---

## Introduction

In the realm of cloud infrastructure, the AWS 3-tier architecture has emerged as a steadfast approach for creating resilient, scalable, and secure applications. This repository serves as your gateway into the world of architecting such an environment, powered by the dynamic capabilities of Terraform.

Here, you'll find a meticulously crafted collection of Terraform manifest files that encapsulate the intricate layers of the AWS 3-tier architecture. Our focus is crystal clear: crafting a Virtual Private Cloud (VPC) that spans two Availability Zones (AZs), fortified with a public subnet for the all-important NAT Gateway, and dual private subnets tailored to house the core components - EC2 instances and RDS databases.

But the story doesn't end there. Our commitment to robustness drives us to replicate this architecture across both AZs, ensuring not only high availability but also robust disaster recovery mechanisms. Additionally, we'll guide you through the creation of Internet Gateways and Route Tables, crucial elements that bind the different tiers together into a harmonious whole.

The beauty of Terraform lies in its ability to translate infrastructure into code, enabling rapid, consistent, and auditable deployment. Inside this repository, you'll discover organized manifest files that bring our architectural vision to life. Alongside, we've thoughtfully included architecture diagrams that provide a visual guide to help you understand the flow and connections within this multi-layered setup.

Whether you're an AWS enthusiast, a Terraform aficionado, or a curious explorer of cloud architectures, this repository aims to cater to all. By navigating through the manifest files and diagrams, you'll unravel the intricacies of AWS 3-tier architecture implementation while mastering the art of orchestrating it with Terraform.

So, embark on this journey with us as we combine the best of AWS and Terraform to sculpt an architecture that's not just resilient, but also a testament to the power of infrastructure-as-code. Clone, modify, experiment, and elevate your understanding of cloud architecture and deployment through this comprehensive GitHub repository.

---

## Problem Statement and Solution

**Problem Statement:**

Building a robust and scalable cloud infrastructure on Amazon Web Services (AWS) demands a comprehensive understanding of architectural principles and efficient deployment techniques. Aspiring cloud architects often grapple with the challenge of designing a 3-tier architecture that ensures high availability, disaster recovery, and secure communication between different components. Navigating through the intricacies of creating a Virtual Private Cloud (VPC) spanning multiple Availability Zones (AZs), configuring public and private subnets, setting up a NAT Gateway, managing Internet Gateways, and establishing Route Tables can be overwhelming, especially for newcomers to AWS. Moreover, ensuring consistent replication of this architecture across multiple AZs adds another layer of complexity.

**Solution:**

This video tutorial is designed to be your definitive guide in overcoming the challenges of constructing an AWS 3-tier architecture using Terraform. By walking you through every step of the process, we'll demystify the creation of a resilient and scalable VPC that spans two AZs, comprising a public subnet for a NAT Gateway and private subnets housing EC2 instances and RDS databases. Furthermore, we'll delve into the critical task of replicating this architecture across both AZs, cementing its robustness and disaster recovery capabilities.

Our solution harnesses the power of Terraform, a cutting-edge infrastructure-as-code tool, to streamline the deployment process. You'll gain hands-on experience as we guide you through writing and executing Terraform manifest files that orchestrate the entire architecture. We'll not only explain the theoretical underpinnings of each component but also provide real-world insights and best practices that seasoned cloud architects employ.

By the end of this tutorial, you'll not only possess a deep understanding of AWS 3-tier architecture but also be well-versed in leveraging Terraform's capabilities for consistent, repeatable, and efficient infrastructure deployment. Whether you're an AWS novice or an experienced practitioner seeking to enhance your skills, this tutorial will equip you with the knowledge and confidence to architect and deploy complex cloud infrastructures that meet modern standards of scalability, security, and resilience.

---

## Terraform Commands

### Terraform Initialize

```shell
terraform init
```

---

### Terraform Validate

```shell
terraform validate
```

---

### Terraform plan

```shell
terraform plan
```

---

### Terraform Apply

```shell
terraform apply
```

---

### Terraform Destroy

```shell
terraform apply -destroy -auto-approve
```

---
