# Awesome-Cloud-Application-Infrastructure

## Top Cloud Application Infrastructure Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Compute, Storage, Networking & Managed Platform Services*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Application Infrastructure**. These platforms provide the foundational compute, storage, networking, and managed services required to build, deploy, and scale modern applications—covering everything from hyperscale public clouds to developer-friendly alternatives and self-hosted infrastructure stacks.

**Examples** include AWS, Microsoft Azure, Google Cloud Platform, IBM Cloud, Oracle Cloud Infrastructure, DigitalOcean, Linode (Akamai), OVHcloud, Alibaba Cloud, and Freshworks Cloud Infrastructure (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted cloud infrastructure, open-source platform-as-a-service, and infrastructure-as-code frameworks—ideal for platform engineers, DevOps teams, and organizations seeking transparent, vendor-neutral alternatives to proprietary cloud services.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Amazon Web Services (AWS)](https://aws.amazon.com/)** | The largest public cloud provider with 200+ services spanning compute (EC2), storage (S3), databases (RDS, DynamoDB), networking, AI/ML, and serverless (Lambda). Global infrastructure across 30+ regions. | EC2 from ~$0.0104/hour (t3.micro Linux); S3 from $0.023/GB/month | **12-month free tier**: 750 hours/month t2.micro/t3.micro EC2, 5GB S3, 750 hours RDS; new accounts get up to $200 credits (6-month validity) |
| **[Microsoft Azure](https://azure.microsoft.com/)** | Microsoft's enterprise cloud with deep integration into Active Directory, Office 365, and the .NET ecosystem. Strong hybrid cloud capabilities via Azure Arc and ExpressRoute. | Virtual Machines from ~$0.0116/hour (B1s Linux); Blob Storage from $0.018/GB/month | **12-month free tier**: 750 hours B1s VM, 5GB Blob Storage; $200 credit for 30 days; 55+ always-free services |
| **[Google Cloud Platform (GCP)](https://cloud.google.com/)** | Google's cloud with strengths in data analytics (BigQuery), Kubernetes (GKE), and machine learning (Vertex AI). Premium global network and live migration for VMs. | Compute Engine from ~$0.0104/hour (e2-micro); Cloud Storage from $0.020/GB/month | **$300 credit for 90 days**; always-free tier: 1 e2-micro VM (us regions), 5GB Cloud Storage, 1GB BigQuery queries/month |
| **[IBM Cloud](https://www.ibm.com/cloud)** | Enterprise-focused cloud with strength in regulated industries, AI (Watson), and hybrid cloud via Red Hat OpenShift. | Virtual Servers from ~$0.047/hour (bx2-2x8); Object Storage from $0.023/GB/month | **Lite plan**: free services including 25GB Object Storage, 500MB Cloudant, limited Kubernetes cluster; $200 credit for 30 days |
| **[Oracle Cloud Infrastructure (OCI)](https://www.oracle.com/cloud/)** | Oracle's cloud with aggressive free tier and strong database (Autonomous Database) and enterprise application (ERP, HCM) integration. | Compute from ~$0.0075/hour (VM.Standard.E4.Flex); Block Volume from $0.0255/GB/month | **Always Free**: 2 AMD VMs (1/8 OCPU, 1GB RAM each), 4 Arm Ampere A1 cores + 24GB RAM, 200GB Block Volume, 10GB Object Storage, 2 Autonomous Databases |
| **[DigitalOcean](https://www.digitalocean.com/)** | Developer-friendly cloud with simplified pricing and strong documentation. Popular for small teams, startups, and individual developers. | Droplets from $4/month (512MB RAM); Spaces from $5/month (250GB) | **$200 credit for 60 days**; no permanent free tier for Droplets |
| **[Linode (Akamai)](https://www.linode.com/)** | Developer-focused cloud (acquired by Akamai) with predictable pricing and a loyal community. Strong for small-to-mid workloads. | Nanode 1GB from $5/month; Block Storage from $0.10/GB/month | **$100 credit for 60 days**; no permanent free tier |
| **[OVHcloud](https://www.ovhcloud.com/)** | European cloud provider with strong data sovereignty positioning, competitive bare-metal, and public cloud offerings. | VPS from ~$3.50/month; Public Cloud instances from ~$0.0087/hour | No permanent free tier; trial credits occasionally available via promotions |
| **[Alibaba Cloud](https://www.alibabacloud.com/)** | China's largest cloud provider with global regions, strong e-commerce ecosystem integration, and competitive pricing for Asia-Pacific workloads. | ECS from ~$0.012/hour (t5-lc1m1.small); OSS from $0.018/GB/month | **Free trial**: $300–$1,200 in credits depending on region; 12-month free tier for select services |
| **[Freshworks Cloud Infrastructure](https://www.freshworks.com/)** | SaaS application platform (not IaaS) providing customer engagement, ITSM, and CRM software. Underlying infrastructure is managed by Freshworks; users consume applications rather than raw compute. | Freshdesk from $19/agent/month; Freshservice from $23/agent/month | Freshdesk free for 1–2 agents for 6 months; Freshsales free for 3 users; 14–21 day trials |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Kubernetes](https://github.com/kubernetes/kubernetes)** | [![Stars](https://img.shields.io/github/stars/kubernetes/kubernetes?style=social&color=white)](https://github.com/kubernetes/kubernetes/stargazers) | Container orchestration platform that has become the de facto standard for deploying and managing containerized applications across clouds. CNCF graduated project; the foundation for most modern platform engineering. |
| **[OpenStack](https://github.com/openstack/openstack)** | [![Stars](https://img.shields.io/github/stars/openstack/openstack?style=social&color=white)](https://github.com/openstack/openstack/stargazers) | Open-source cloud computing platform for building public and private IaaS clouds. Provides compute (Nova), storage (Swift, Cinder), networking (Neutron), and identity (Keystone) services. |
| **[Terraform](https://github.com/hashicorp/terraform)** | [![Stars](https://img.shields.io/github/stars/hashicorp/terraform?style=social&color=white)](https://github.com/hashicorp/terraform/stargazers) | Infrastructure-as-code tool for provisioning and managing cloud resources across providers (AWS, Azure, GCP, and 100+ others). The standard for declarative infrastructure management. |
| **[OpenTofu](https://github.com/opentofu/opentofu)** | [![Stars](https://img.shields.io/github/stars/opentofu/opentofu?style=social&color=white)](https://github.com/opentofu/opentofu/stargazers) | Open-source Terraform fork (MPL-2.0) under Linux Foundation governance. Drop-in compatible with Terraform while remaining fully open-source and community-driven. |
| **[Pulumi](https://github.com/pulumi/pulumi)** | [![Stars](https://img.shields.io/github/stars/pulumi/pulumi?style=social&color=white)](https://github.com/pulumi/pulumi/stargazers) | Infrastructure-as-code using general-purpose programming languages (TypeScript, Python, Go, .NET). Apache 2.0 licensed; supports all major clouds. |
| **[Cloud Foundry](https://github.com/cloudfoundry)** | [![Stars](https://img.shields.io/github/stars/cloudfoundry?style=social&color=white)](https://github.com/cloudfoundry/stargazers) | Open-source platform-as-a-service for deploying and scaling applications without managing infrastructure. Provides buildpacks, service brokers, and container orchestration. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[OpenShift (OKD)](https://github.com/openshift/okd)** | [![Stars](https://img.shields.io/github/stars/openshift/okd?style=social&color=white)](https://github.com/openshift/okd/stargazers) | The community distribution of Kubernetes that powers Red Hat OpenShift. Adds developer workflows, CI/CD, and operational tooling on top of vanilla Kubernetes. |
| **[Proxmox VE](https://github.com/proxmox)** | [![Stars](https://img.shields.io/github/stars/proxmox?style=social&color=white)](https://github.com/proxmox/stargazers) | Open-source virtualization platform combining KVM and LXC for private cloud and homelab infrastructure. Web-based management interface; AGPL licensed. |
| **[Apache CloudStack](https://github.com/apache/cloudstack)** | [![Stars](https://img.shields.io/github/stars/apache/cloudstack?style=social&color=white)](https://github.com/apache/cloudstack/stargazers) | Open-source IaaS platform for building public, private, and hybrid clouds. Apache 2.0 licensed; used by service providers worldwide. |
| **[Crossplane](https://github.com/crossplane/crossplane)** | [![Stars](https://img.shields.io/github/stars/crossplane/crossplane?style=social&color=white)](https://github.com/crossplane/crossplane/stargazers) | Kubernetes-native control plane for provisioning and managing cloud infrastructure using CRDs. CNCF project; enables platform teams to build internal developer platforms. |

**Frameworks for building custom systems**: Combine **Kubernetes** for container orchestration, **Terraform** or **OpenTofu** for infrastructure provisioning, **Crossplane** for Kubernetes-native cloud resource management, and **Proxmox VE** or **OpenStack** for private cloud foundations—creating a fully self-hosted application infrastructure stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud infrastructure platforms handle sensitive workloads and data; enforce least-privilege IAM policies, network segmentation, and encryption at rest and in transit.
- Free tier limits and pricing change frequently; always verify against the provider's current pricing page before making architectural or budgetary decisions.

---

**Made for platform engineers, DevOps teams, cloud architects, and developers building application infrastructure.**  
Let's make cloud infrastructure more open, observable, and cost-transparent.
