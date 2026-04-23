# Roger Sherman

20 Cumming Street, North Toowoomba, QLD 4350
rsherman@linux.com | +61 405 655 689
LinkedIn: https://www.linkedin.com/in/roger-sherman-48527736/  
GitHub: https://github.com/simplycycling  

---

## Professional Summary

Senior DevOps and Platform Engineer with 12+ years of experience across cloud infrastructure, Kubernetes, and large-scale bare metal environments. Deep hands-on expertise in AWS, Terraform, Ansible, and Kubernetes — with a consistent track record of inheriting messy infrastructure and leaving it significantly better. Experienced across the full platform engineering lifecycle: greenfield builds, complex migrations, security hardening, and operational automation. Has worked at scale in trading, data analytics, and SaaS environments. Experienced operating at the intersection of architecture and hands-on execution, with a track record of defining platform standards and mentoring engineers. Currently pursuing AWS Solutions Architect and CKA/CKAD certifications.

---

## Professional Experience

### Dash — Senior DevOps Engineer
**June 2023 – Present | North Sydney (Hybrid)**

- Migrated legacy deployment pipeline from AWS OpsWorks (end-of-life) to Azure Pipelines, authoring PowerShell automation to support the transition
- Built greenfield Terraform modules to fully codify the legacy platform infrastructure, enabling repeatable, version-controlled environment provisioning
- Authored all Ansible automation for configuration management and day-2 operations across the legacy platform
- Contributed to the migration of a Kubernetes cluster from kOps to EKS; upgraded all four clusters to supported versions, including remediating clusters running past end-of-life
- Completely refactored AWS IAM across ~160 accounts — eliminating ~180 inline policies and replacing them with a structured, role-based model — significantly improving security posture, auditability, and scalability
- Upgraded AWS WAFv1 to WAFv2 across all non-production environments
- Executed major database upgrades across both self-hosted and RDS instances: MongoDB 6 → 8 and PostgreSQL 11 → 15
- Initiated a proof-of-concept deployment of Ansible Automation Platform on AWS to standardise and scale automation workflows
- Supported observability and monitoring operations using Datadog as part of broader platform engineering responsibilities
- Managed and operated Kafka on Kubernetes as part of the platform stack

---

### Westpac — Senior DevOps Engineer
**November 2020 – May 2023 | Remote**

- Administered, maintained, and upgraded three RHEL bare metal clusters hosting Westpac's low-latency trading platform, spanning data centres in New York and London
- Led a major RHEL 6 → 7 infrastructure migration, coordinating application teams across independently developed workloads — managing the complexity of aligning multiple teams and release schedules simultaneously
- Built out a new 30-node cluster from the ground up in London — from disk provisioning through OS installation to full configuration management via Puppet
- Inherited fundamentally broken Ansible automation: playbooks were serial-only, relied heavily on shell modules, and were "version controlled" by copying dated directories. Refactored into properly parallelised, idempotent playbooks under real version control
- Participated in regular on-call rotation, performing weekend deployments, security patching, and out-of-hours maintenance
- Transitioned time synchronisation from NTP to PTP, reducing clock drift for latency-sensitive trading workloads

---

### Quantium — DevSecOps Engineer
**March 2020 – November 2020 | Sydney**

- Deployed and configured HashiCorp Vault for secrets management, rolling out adoption across multiple business units
- Embedded within the security team to introduce and teach DevOps methodology to a team operating entirely without automation practices — shifting the team from manual, GUI-driven workflows toward code-driven operations

### Quantium — Platform Engineer
**February 2017 – March 2020 | Sydney**

- Operated and maintained three Apache Mesos/MapR Hadoop bare metal clusters — two production clusters of 150+ nodes each — while leading the team's transition to Kubernetes from 2019, building foundational cluster networking using MetalLB for bare metal load balancer IP assignment and a dual CoreDNS architecture to expose pod DNS publicly, and integrating Ceph for persistent storage
- Operated Kafka on bare metal Mesos clusters as part of the core data platform, supporting high-throughput data pipelines for analytics workloads
- Supported QOS (Quantium Operating System), a bespoke in-house Go application providing a TUI-driven "app store" for analysts to launch dockerised data workloads onto clusters with quota and data attachment management — an early and genuinely novel approach to internal developer platforms
- Implemented Calico network policy across Mesos clusters with no community documentation to reference — required reading upstream source code to understand integration points, working with one other engineer to solve a problem nobody had publicly solved
- Upgraded and significantly refactored Ansible automation across the platform; upgraded Sensu monitoring infrastructure and led evaluation of replacement platforms including Prometheus
- Embedded at Google's Sydney office (Circular Quay) to learn their data stack and evaluate integration with Kubernetes — one of several cloud PoC engagements conducted with Google, AWS, and Azure engineers

---

### Viddler — Senior Systems Engineer / Systems Administrator
**March 2014 – January 2017 | Bethlehem, PA**

- Led a HIPAA/PCI compliance initiative working directly with the CISO — hardening the target environment to satisfy both regulatory frameworks, ensuring encryption at rest and in transit throughout
- Drove a full infrastructure modernisation triggered by Heartbleed: audited all software across the environment, migrated Debian infrastructure to Ubuntu, and used the opportunity to migrate configuration management from Puppet to Ansible
- Architected AWS environments for new applications, establishing the team's first cloud footprint
- Managed physical-to-virtual migration and orchestrated the transition from co-location to a dedicated datacenter

---

### Tekmark — Systems Administrator
**October 2012 – March 2014 | Red Bank, NJ**

- Promoted from Tier 2 customer support into the Ops team, supporting the Redbox Instant video streaming platform
- Handled infrastructure operations, issue reproduction, and platform reliability improvements

---

## Skills

| Area | Technologies |
|---|---|
| **Cloud** | AWS (EC2, EKS, RDS, IAM, WAF, EventBridge, S3), Azure |
| **Infrastructure as Code** | Terraform, Ansible, Ansible Automation Platform |
| **Containers & Orchestration** | Kubernetes (EKS, kOps, bare metal), Docker, Mesos, Calico, Cilium |
| **CI/CD** | Azure Pipelines, GitOps methodology |
| **Observability** | Datadog, Prometheus, Sensu, Grafana LGTM |
| **Databases** | PostgreSQL, MongoDB, Elasticsearch |
| **Storage** | Ceph |
| **Messaging** | Kafka |
| **Security** | HashiCorp Vault, IAM design, HIPAA/PCI compliance, WAF, Kyverno |
| **Operating Systems** | RHEL/CentOS, Ubuntu/Debian |
| **Languages** | Python, Go, Bash, PowerShell, Ruby |
| **Configuration Management** | Ansible, Puppet |

---

## Community & Speaking

- Presented at the New York City Ansible Meetup Group while at Viddler, sharing operational experience and best practices with the local DevOps community
