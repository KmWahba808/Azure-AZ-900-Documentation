# AZ-900: Microsoft Azure Fundamentals
---

### Complete Study Documentation

---

## Table of Contents

| # | Section |
|---|---|
| 1 | [Course Overview & Exam Guide](#section-1--course-overview--exam-guide) |
| 2 | [Cloud Computing & Core Vocabulary](#section-2--cloud-computing--core-vocabulary) |
| 3 | [Economies of Scale](#section-3--economies-of-scale) |
| 4 | [CapEx vs OpEx](#section-4--capex-vs-opex) |
| 5 | [Consumption-Based Model](#section-5--consumption-based-model) |
| 6 | [IaaS vs PaaS vs SaaS](#section-6--iaas-vs-paas-vs-saas) |
| 7 | [Public, Private & Hybrid Cloud](#section-7--public-private--hybrid-cloud) |
| 8 | [Geographies, Regions & Availability Zones](#section-8--geographies-regions--availability-zones) |
| 9 | [Resources, Resource Groups & Resource Manager](#section-9--resources-resource-groups--resource-manager) |
| 10 | [Compute Services](#section-10--compute-services) |
| 11 | [Networking Services](#section-11--networking-services) |
| 12 | [Storage Services](#section-12--storage-services) |
| 13 | [Database Services](#section-13--database-services) |
| 14 | [Azure Marketplace](#section-14--azure-marketplace) |
| 15 | [Azure IoT Services](#section-15--azure-iot-services) |
| 16 | [Big Data & Analytics Services](#section-16--big-data--analytics-services) |
| 17 | [Azure AI & Machine Learning](#section-17--azure-ai--machine-learning) |
| 18 | [Serverless Computing Services](#section-18--serverless-computing-services) |
| 19 | [Azure DevOps Solutions](#section-19--azure-devops-solutions) |
| 20 | [Azure Management Tools](#section-20--azure-management-tools) |
| 21 | [Azure Advisor & Monitoring](#section-21--azure-advisor--monitoring) |
| 22 | [Network & Application Security Groups](#section-22--network--application-security-groups) |
| 23 | [User-Defined Routes & Route Tables](#section-23--user-defined-routes--route-tables) |
| 24 | [Azure Firewall](#section-24--azure-firewall) |
| 25 | [Azure DDoS Protection](#section-25--azure-ddos-protection) |
| 26 | [Azure Identity Services](#section-26--azure-identity-services) |
| 27 | [Microsoft Defender for Cloud](#section-27--microsoft-defender-for-cloud) |
| 28 | [Azure Key Vault](#section-28--azure-key-vault) |
| 29 | [Azure Role-Based Access Control (RBAC)](#section-29--azure-role-based-access-control-rbac) |
| 30 | [Azure Resource Tags](#section-30--azure-resource-tags) |
| 31 | [Azure Policy & Resource Locks](#section-31--azure-policy--resource-locks) |
| 32 | [Azure Blueprints](#section-32--azure-blueprints) |
| 33 | [Cloud Adoption Framework for Azure](#section-33--cloud-adoption-framework-for-azure) |
| 34 | [Security, Privacy & Compliance](#section-34--security-privacy--compliance) |
| 35 | [Cost-Affecting Factors](#section-35--cost-affecting-factors) |
| 36 | [Cost Reduction Methods](#section-36--cost-reduction-methods) |
| 37 | [Azure Cost Management](#section-37--azure-cost-management) |
| 38 | [SLA & Composite SLA](#section-38--sla--composite-sla) |
| 39 | [Service Lifecycle: Preview & GA](#section-39--service-lifecycle-preview--ga) |

---

> ## Section 1 — Course Overview & Exam Guide

The **AZ-900: Microsoft Azure Fundamentals** exam is Microsoft's entry-level cloud certification. Passing it earns the **Microsoft Certified: Azure Fundamentals** badge — ideal for anyone beginning their Azure or cloud journey.

---

### Exam at a Glance

| Item | Detail |
|---|---|
| **Exam Code** | AZ-900 |
| **Certification** | Microsoft Certified: Azure Fundamentals |
| **Difficulty** | Beginner |
| **Prerequisites** | None |
| **Key Skill Required** | Ability to **describe** each concept (not configure or implement) |

---

### Exam Sections

The AZ-900 exam is divided into four domains, each carrying roughly equal weight:

| Domain | Topics Covered |
|---|---|
| **Cloud Concepts** | Core cloud principles, terminology, service models |
| **Azure Services** | Core Azure products and services |
| **Security, Privacy, Compliance & Trust** | Security tools, compliance frameworks, identity |
| **Azure Pricing & Support** | Pricing models, SLAs, support plans |

> 📝 **Exam Tip:** Every domain carries equal weight — you cannot skip any area. The keyword throughout the exam objectives is **"Describe"**: you must understand each topic well enough to explain it to someone else, not configure or implement it.

---

### How to Prepare

**Step 1 — Download the Official Skills Outline**
Visit the AZ-900 page on **Microsoft Learn** and download the **Exam Skills Outline PDF**. This document lists every testable topic and subtopic. Use it as a checklist before and after studying.

**Step 2 — Monitor for Exam Updates**
Microsoft periodically updates the exam. The Skills Outline PDF contains a **"Recent Changes"** section at the bottom — always review it before your exam date.

---

### Study Materials Per Section

| Resource | Description |
|---|---|
| **Skills Learned** | Maps directly to the Microsoft exam skills outline |
| **Study Guide** | Official Microsoft documentation links |
| **Cheat Sheet** | Condensed summary of key points for revision |
| **Practice Test** | Section-specific questions to test understanding |

---

> ## Section 2 — Cloud Computing & Core Vocabulary

Cloud computing is the **delivery of IT services over the internet** — from storage and compute to networking and analytics — on a pay-as-you-go basis. Instead of owning physical hardware, you consume services on-demand from a cloud provider like Microsoft Azure.

---

### The Four Core Cloud Service Categories

| Category | Description |
|---|---|
| **Compute** | Virtual machines, containers, and other resources to run applications |
| **Storage** | Structured and unstructured data — files, databases, migration tools |
| **Networking** | Secure connectivity between cloud components and on-premises environments |
| **Analytics** | Monitoring, telemetry, performance insights, and operational data |

---

### Core Cloud Vocabulary

#### Scalability
The ability to add or remove resources in response to demand. Two types exist:

| Type | Direction | What Changes | Terms |
|---|---|---|---|
| **Vertical Scaling** | Up / Down | Size/power of an existing resource | Scale Up = increase size; Scale Down = decrease |
| **Horizontal Scaling** | Out / In | Number of resource instances | Scale Out = add instances; Scale In = remove |

#### Elasticity
The ability to scale **automatically and dynamically** based on real-time workload. Elasticity = Scalability + Automation. An auto-scaling system allocates resources when demand rises and deallocates them when it drops.

> 📝 **Exam Tip:** The key differentiator between scalability and elasticity is **automation**. Scalability is the capability; elasticity is scaling happening automatically.

#### Agility
The ability to **provision and deprovision cloud resources within seconds to minutes**, compared to days or weeks on-premises. Agility is about speed of provisioning — not scaling.

#### Fault Tolerance
The ability of a system to **remain operational during localized component failures**. Azure automatically moves workloads to healthy servers if a server or disk fails. Fault tolerance handles small, local failures — it does not cover region-wide outages.

#### Disaster Recovery
The ability to **recover from large-scale, catastrophic failures** such as floods, earthquakes, or power grid outages that could take down an entire Azure region. A standard DR setup involves deploying two copies of an application in separate regions with data replication and DNS failover between them.

> 📝 **Exam Tip:** Fault tolerance ≠ Disaster Recovery. Fault tolerance = localized component failure. Disaster Recovery = region-wide or service-wide catastrophic failure.

#### High Availability (HA)
A measure of how much **uptime** a system provides, expressed as a percentage — often called "nines":

| Availability | Downtime per Year |
|---|---|
| 99% (two nines) | ~3.65 days |
| 99.9% (three nines) | ~8.76 hours |
| 99.99% (four nines) | ~52 minutes |
| 99.999% (five nines) | ~5 minutes |

HA is not automatic — it depends on your architecture (redundant instances, load balancing, Availability Zones) and the Azure service tier selected.

#### Reliability
The ability to **recover from failures and continue functioning**. Achieved by deploying resources across multiple regions. Reliability must be deliberately designed — it is not a default behavior.

> 📝 **Exam Tip:** HA = staying up. Reliability = recovering when something goes wrong. They are related but distinct.

#### Predictability
Confidence that performance and cost will behave as expected:

| Dimension | How Azure Delivers It |
|---|---|
| **Performance Predictability** | Autoscaling, load balancing, and HA guarantee consistent application behavior |
| **Cost Predictability** | Pricing Calculator, TCO Calculator, and real-time cost tracking for budget forecasting |

#### Security
Cloud security responsibility varies by service model:
- **IaaS** — maximum control; you manage OS, software, and configuration
- **PaaS/SaaS** — Microsoft handles the OS and platform; you focus on applications and data
- Azure provides built-in **DDoS protection** at the network level for all services.

#### Governance
Ensures resources comply with corporate standards and regulations. Templates enforce consistent configurations; Azure Policy can block non-compliant resources from being created; automated patches maintain compliance as the environment grows.

#### Manageability

| Dimension | What It Covers |
|---|---|
| **Management of the Cloud** | Autoscaling, auto-healing, template-based deployments, real-time alerts |
| **Management in the Cloud** | Azure Portal, Azure CLI, Azure PowerShell, REST APIs |

---

### Summary

| Concept | Key Point |
|---|---|
| **Cloud Computing** | On-demand delivery of IT services (Compute, Storage, Networking, Analytics) over the internet |
| **Scalability** | Add/remove resources — Vertical (Up/Down) or Horizontal (Out/In) |
| **Elasticity** | Scalability + automation — auto-scales in real time based on demand |
| **Agility** | Provision resources in seconds vs. weeks on-premises |
| **Fault Tolerance** | Stays up during localized component failures |
| **Disaster Recovery** | Recovers from region-wide or catastrophic failures — requires multi-region setup |
| **High Availability** | Minimal downtime; measured in "nines"; backed by SLAs |
| **Reliability** | Recovers from failures and continues functioning — built by design |
| **Predictability** | Performance and cost behave as expected — via autoscaling, calculators, monitoring |
| **Governance** | Enforces standards via policies, templates, and automated compliance checks |
| **Manageability** | Management of the cloud (autoscaling, alerts) + in the cloud (Portal, CLI, PS, REST) |

---

> ## Section 3 — Economies of Scale

**Economies of scale** is a business principle stating that as a company grows, its **cost per unit decreases** due to greater operational efficiency. This is the core reason why cloud services become cheaper over time.

---

### How It Applies to Azure

As Microsoft Azure grows — more customers, more data centers, better hardware deals — the cost to deliver services per unit falls. To stay competitive, those savings are passed on to customers through lower service prices.

| Driver | Effect on Cost |
|---|---|
| **Bulk hardware purchasing** | Lower per-unit hardware cost |
| **Efficient data center construction** | Lower per-unit operational cost |
| **Hardware advancements** | More compute/storage per dollar over time |
| **Operational efficiencies at scale** | Fewer staff per managed resource |

The result: Microsoft can deliver cloud services at a price no individual company can match by running its own on-premises infrastructure.

---

### Summary

| Concept | Key Point |
|---|---|
| **Economies of Scale** | As scale increases, cost per unit decreases |
| **Why it matters for Azure** | Azure's growing scale = lower prices passed on to customers |
| **Benefit to customers** | Cloud services are typically cheaper than equivalent on-premises infrastructure |

> 📝 **Exam Tip:** You do not need to know the business mechanics deeply — just understand that **bigger cloud = lower prices**, and that this is a fundamental advantage of cloud over on-premises.

---

> ## Section 4 — CapEx vs OpEx

Understanding how companies spend on IT infrastructure is foundational to understanding why the cloud is economically appealing.

---

### Capital Expenditure (CapEx)

CapEx means **buying and owning your own infrastructure** with a large upfront investment.

| Characteristic | Detail |
|---|---|
| **Upfront Cost** | Very high — servers, networking, storage purchased in advance |
| **Ongoing Cost** | Low — power, cooling, minor maintenance |
| **Capacity** | Fixed — risk of over- or under-provisioning |
| **Maintenance** | Entirely your responsibility |
| **Tax Treatment** | Deducted over time via depreciation |
| **Early Termination** | Not possible — you own the hardware |

#### CapEx vs OpEx — Full Comparison

| Category | CapEx (On-Premises) | OpEx (Cloud) |
|---|---|---|
| **Upfront Cost** | Very high | None |
| **Ongoing Cost** | Low (maintenance only) | Based entirely on usage |
| **Tax Deduction** | Over time via depreciation | In the same year |
| **Early Termination** | Not possible — you own the hardware | Cancel anytime |
| **Maintenance** | Significant — managed by you | Minimal — handled by provider |
| **Value Over Time** | Decreases — hardware depreciates | No depreciation, always current |
| **Capacity** | Fixed/static | Dynamic — always matches usage |

---

### Operational Expenditure (OpEx)

OpEx means **renting infrastructure or paying for services** — no ownership, pay only for what you use. Cloud computing is the OpEx model.

> 📝 **Exam Tip:** Cloud computing = OpEx. The most common exam question is: *"Which expenditure model does cloud computing use?"* — always **OpEx**. Also remember: CapEx is deducted over years (depreciation), while OpEx is deducted in the same year.

---

### Summary

| Concept | Key Point |
|---|---|
| **CapEx** | Large upfront cost; own the hardware; fixed capacity; you manage everything |
| **OpEx** | No upfront cost; pay-as-you-go; dynamic capacity; provider manages infrastructure |
| **Cloud = OpEx** | Consume services, pay for usage, cancel anytime — no hardware ownership |
| **Tax difference** | CapEx = depreciated over years; OpEx = deducted in the current year |

---

> ## Section 5 — Consumption-Based Model

The **consumption-based model** is the practical implementation of OpEx in the cloud: you **pay only for what you use, when you use it**. No upfront cost, no idle billing, no wasted capacity.

---

### How Azure Calculates Consumption

Different services have different billing metrics based on their complexity. Azure bills at a granular level — often per second of use.

**Example: Virtual Machine Billing**

| Billing Component | What It Measures |
|---|---|
| **Compute** | vCPU and memory — charged per second of use |
| **Storage** | Disk attached to the VM — charged by size |
| **Networking** | Data transferred in and out |

A VM used for 20 seconds is billed for exactly 20 seconds of compute. A Logic App used on only two days this month generates costs only on those two days.

---

### Visualizing Consumption

The **Azure Cost Management** tool inside the Azure Portal lets you:
- View costs broken down by day
- Group costs by service to identify top spenders
- Review historical spending trends

---

### Summary

| Concept | Key Point |
|---|---|
| **Consumption-based model** | Pay only for what you use, when you use it |
| **No upfront cost** | Billing starts only when you consume a resource |
| **No wasted resources** | Allocate only what you need at any given time |
| **Granular billing** | Multiple pricing components per service, billed to the second |
| **Cost Management** | Azure Portal tool to analyze spending by service, day, and resource group |

> 📝 **Exam Tip:** Remember the three "nos" of consumption-based pricing: **no upfront cost**, **no wasted resources**, and **no paying for idle resources**.

---

> ## Section 6 — IaaS vs PaaS vs SaaS

Cloud service models define **who manages what** across the technology stack. Understanding the layers of a complete IT environment is the foundation for understanding these models.

---

### The IT Stack

| Layer | Examples |
|---|---|
| **Hardware** | Physical servers, networking equipment |
| **Networking** | Internet connectivity, switches, firewalls |
| **Storage** | Hard drives, SSDs, RAID arrays |
| **Virtualization** | Software to run multiple VMs on one physical machine |
| **Operating System** | Windows, Linux |
| **Middleware** | Software required to support the application runtime |
| **Runtime** | IIS, Docker, or other application host environments |
| **Application** | Your application code |
| **Data** | Data stored and used by the application |

These layers group into three tiers: **Infrastructure** (Hardware → Virtualization), **Platform** (OS → Runtime), and **Software** (Application + Data).

---

### The Three Cloud Service Models

#### Infrastructure as a Service (IaaS)
**Microsoft manages:** Infrastructure (hardware, networking, storage, virtualization)
**You manage:** Platform + Software (OS, middleware, runtime, application, data)

| Aspect | Detail |
|---|---|
| **Typical use cases** | VM migration, test/dev environments, backup, disaster recovery |
| **Common Azure services** | Virtual Machines, Virtual Networks, Managed Disks |
| **Rule of thumb** | If the solution uses lots of VMs, it's IaaS |

#### Platform as a Service (PaaS)
**Microsoft manages:** Infrastructure + Platform (hardware through to runtime)
**You manage:** Software only (application code and data)

| Aspect | Detail |
|---|---|
| **Typical use cases** | Building cloud-native apps, AI/ML, web apps, analytics |
| **Common Azure services** | Azure SQL Database, App Service, Logic Apps, Azure Functions |
| **Rule of thumb** | If someone is "developing cloud applications," they're using PaaS |

#### Software as a Service (SaaS)
**Microsoft manages:** Everything
**You manage:** Nothing — just use the application

| Aspect | Detail |
|---|---|
| **Typical use cases** | Buying and using off-the-shelf applications |
| **Common examples** | Microsoft 365, Outlook, Skype, OneDrive |

---

### Full Responsibility Matrix

| Layer | On-Premises | IaaS | PaaS | SaaS |
|---|---|---|---|---|
| Hardware | You | Microsoft | Microsoft | Microsoft |
| Networking | You | Microsoft | Microsoft | Microsoft |
| Storage | You | Microsoft | Microsoft | Microsoft |
| Virtualization | You | Microsoft | Microsoft | Microsoft |
| Operating System | You | **You** | Microsoft | Microsoft |
| Middleware | You | **You** | Microsoft | Microsoft |
| Runtime | You | **You** | Microsoft | Microsoft |
| Application | You | **You** | **You** | Microsoft |
| Data | You | **You** | **You** | Microsoft |

---

### The Shared Responsibility Model

Two responsibilities **never change** — the customer always owns:
1. **Data** stored in the cloud
2. **User identities and access** (who can connect and what they can do)

Microsoft **always owns**: Physical datacenter security, power, cooling, and physical network infrastructure.

> 📝 **Exam Tip:** Memorize the responsibility matrix. The dividing line shifts with each model: IaaS splits at virtualization, PaaS splits at runtime, SaaS means Microsoft manages everything. Regardless of the model, the customer is **always responsible for their data and identities**.

---

### Summary

| Topic | Key Point |
|---|---|
| **IaaS** | You manage OS and above; Microsoft manages hardware and virtualization |
| **PaaS** | You manage app and data only; Microsoft manages everything else including the OS |
| **SaaS** | Microsoft manages everything; you just use the application |
| **On-Premises** | You manage every layer — hardware through to data |
| **IaaS Use Cases** | VM migration, test/dev, backup, disaster recovery |
| **PaaS Use Cases** | Cloud-native apps, AI/ML, web apps, business analytics |
| **SaaS Examples** | Microsoft 365, Outlook, Skype, OneDrive |
| **Always Microsoft** | Physical datacenter, power, cooling, physical network and hosts |
| **Always Customer** | Data stored in the cloud + user identities and access |

---

> ## Section 7 — Public, Private & Hybrid Cloud

Cloud **deployment models** describe **where your resources are hosted** — this is a separate concept from service models (IaaS/PaaS/SaaS), which describe what is managed.

---

### Public Cloud

All resources are hosted by the cloud provider (e.g., Microsoft Azure). You own no hardware.

| Advantages | Disadvantages |
|---|---|
| No CapEx — no upfront hardware investment | Limited security/compliance for regulated industries |
| Pay-as-you-go billing | No hardware ownership or control |
| Built-in HA, scalability, and global reach | Specific business requirements may not be fully supported |
| No infrastructure maintenance responsibility | |

---

### Private Cloud

All resources are hosted in **your own data center**, with self-service capabilities matching a public cloud experience.

| Advantages | Disadvantages |
|---|---|
| Full control over hardware and configuration | High CapEx — large upfront hardware investment |
| Meet any security or compliance requirement | Limited agility — constrained by available hardware |
| No restrictions on what you can run | Requires skilled internal IT team |
| | Ongoing staffing and maintenance costs are high |

---

### Hybrid Cloud

Combines public and private cloud, allowing workloads to run in whichever environment is most appropriate.

| Advantages | Disadvantages |
|---|---|
| Maximum flexibility — run any workload anywhere | Higher cost — operating two environments |
| Legacy app support on-premises | More complex to manage and govern |
| Use existing infrastructure investments | Team must understand both on-prem and cloud |
| Meet strict compliance requirements for sensitive workloads | |

---

### Full Comparison

| Criteria | Public | Private | Hybrid |
|---|---|---|---|
| **Hardware ownership** | Microsoft | You | Both |
| **CapEx required** | No | Yes | Yes (private portion) |
| **Security control** | Limited | Full | Full (private portion) |
| **Agility** | High | Limited by hardware | High for cloud portion |
| **Compliance flexibility** | Limited | Maximum | Maximum |
| **Management complexity** | Low | High | Highest |
| **Cost model** | OpEx only | CapEx + OpEx | Both |

---

### Multi-Cloud & Azure Tools

**Multi-cloud** means using services from more than one public cloud provider simultaneously (e.g., Azure + AWS). Common reasons include using unique provider-specific features, avoiding vendor lock-in, or meeting regulations requiring provider diversity.

**Azure Arc** extends Azure management and governance to any infrastructure — on-premises, AWS, GCP, Kubernetes clusters, and edge environments. It does not migrate resources to Azure; it brings Azure's management plane to those resources.

| What Azure Arc Enables | Detail |
|---|---|
| **Centralized management** | Non-Azure resources appear in Azure Portal via Azure Resource Manager |
| **Unified governance** | Apply Azure Policy, RBAC, and Tags to on-prem and multi-cloud resources |
| **Azure services anywhere** | Run Azure data services (e.g., Azure SQL Managed Instance) on any infrastructure |

**Azure VMware Solution** allows organizations that built their infrastructure on VMware to migrate and run those workloads natively in Azure without redesigning their applications.

---

### Summary

| Model / Tool | Where Resources Live | Best For |
|---|---|---|
| **Public Cloud** | Microsoft's data centers | Most workloads; cost-effective and scalable |
| **Private Cloud** | Your own data center | Strict compliance or security requirements |
| **Hybrid Cloud** | Both public and private | Legacy systems, mixed compliance requirements |
| **Multi-Cloud** | Multiple cloud providers | Provider diversity, regulatory requirements |
| **Azure Arc** | Any infrastructure (on-prem, AWS, GCP) | Managing hybrid and multi-cloud from one place |
| **Azure VMware Solution** | Azure (VMware-native) | Migrating existing VMware environments to the cloud |

> 📝 **Exam Tip:** A common scenario question: *"A company has strict compliance requirements but wants to use the cloud for other workloads — which deployment model?"* → **Hybrid Cloud**. Azure Arc = manage hybrid/multi-cloud resources through Azure without migrating them.

---

> ## Section 8 — Geographies, Regions & Availability Zones

All Azure services run on physical hardware. Understanding how that hardware is organized globally is critical for designing resilient, compliant, and low-latency architectures.

**Hierarchy (smallest to largest):** Data Center → Availability Zone → Region → Region Pair → Geography

---

### Data Centers

A **data center** is a physical facility housing the servers running Azure services. Each has its own independent power, cooling, and networking. It is the fundamental building block of the entire Azure infrastructure.

---

### Regions

A **region** is a geographical area containing one or more data centers connected via a low-latency network (under 2ms between data centers). Azure has **50+ regions** worldwide.

Key rules:
- Selecting a region is a mandatory step when deploying any Azure service
- Not all services are available in all regions — always verify availability before designing
- Global services (e.g., Azure AD, Traffic Manager) have no specific region

**Choosing a Region — Balance These Factors:**
1. **Proximity to users** — lower latency
2. **Service availability** — does the region offer what you need?
3. **Price** — the same service costs different amounts in different regions
4. **Compliance** — data sovereignty may restrict region choice

---

### Availability Zones

An **Availability Zone (AZ)** is a physically separate data center (or group) within a region, each with its own independent power, cooling, and networking. Designed to protect against data center-level failures. Each supporting region has a **minimum of 3 zones**.

| AZ Service Type | How It Works | Example |
|---|---|---|
| **Zonal Services** | You explicitly choose which AZ to deploy to | Virtual Machines |
| **Zone-Redundant Services** | Automatically replicates across all AZs | Azure Storage, Azure SQL Database |

---

### Region Pairs

Every Azure region is paired with exactly one other region, at least **300 miles away**, within the same geography.

| Benefit | Explanation |
|---|---|
| **Natural disaster protection** | 300-mile separation means floods/earthquakes rarely affect both |
| **Staggered platform updates** | Microsoft updates one paired region first; only updates the second after success |
| **Data residency** | Pairs remain within the same geography — compliance is maintained |
| **Platform-level replication** | Some services can replicate data across paired regions automatically |

| Region | Paired With |
|---|---|
| East US | West US |
| North Europe (Ireland) | West Europe (Netherlands) |
| UK West | UK South |
| East Asia (Hong Kong) | Southeast Asia (Singapore) |

---

### Geographies

A **geography** is the highest-level grouping — a discrete market containing two or more regions. Ensures data residency, sovereignty, and compliance requirements are met.

---

### Summary

| Concept | Key Point |
|---|---|
| **Hierarchy** | Data Center → Availability Zone → Region → Region Pair → Geography |
| **Data Center** | Physical facility with independent power, cooling, networking |
| **Region** | 1+ data centers, <2ms latency internally; 50+ worldwide |
| **Availability Zone** | Physically separate DC within a region; minimum 3 per region; protects against DC failure |
| **Zonal Services** | You pick the AZ (e.g., Virtual Machines) |
| **Zone-Redundant Services** | Automatically replicate across all AZs (e.g., Azure Storage, SQL Database) |
| **Region Pair** | 300+ miles apart; staggered updates; best DR replication target |
| **Geography** | Discrete market with 2+ regions; ensures data residency and compliance |

> 📝 **Exam Tip:** The full hierarchy is **Data Center → AZ → Region → Region Pair → Geography**. For disaster recovery, always replicate to the **paired region**. For resilience within a region, use **Availability Zones**.

---

> ## Section 9 — Resources, Resource Groups & Resource Manager

Every service you purchase in Azure — a VM, SQL database, storage account, or web app — is represented as a **resource**. Understanding how resources are organized and managed is foundational to everything else in Azure.

---

### Resources

A resource is a generic Azure object that:
- Represents the lifecycle of a service (created when purchased, deleted when removed)
- Stores all service configuration as **properties**
- Can be exported as a **JSON template** for automation and repeatability

---

### Resource Groups

A **resource group** is a logical container that holds related Azure resources. Every Azure resource must belong to exactly one resource group.

**Common Grouping Strategies:**

| Strategy | Example |
|---|---|
| By application + environment | `HRPortal-Production`, `HRPortal-Dev` |
| By department | `Finance-Resources`, `IT-Resources` |
| By resource type | `AllVMs`, `AllDatabases` |
| By billing/cost center | Resources aligned to budget units |

**Benefits of Resource Groups:**
- **Access control** — assign RBAC roles at the group level; they apply to all resources inside
- **Lifecycle management** — delete an entire application by deleting its resource group
- **Cost tracking** — view spending broken down by resource group
- **Policy application** — apply Azure Policy to all resources in a group at once

---

### Azure Resource Manager (ARM)

No matter how you interact with Azure — Portal, CLI, PowerShell, REST API, or SDK — all requests go through **Azure Resource Manager (ARM)**: Azure's centralized management layer.

ARM validates every request, checks permissions via Azure AD, and ensures consistency regardless of which interface was used.

| Interface | Description |
|---|---|
| **Azure Portal** | Web-based GUI at portal.azure.com |
| **Azure CLI** | Command-line tool (Bash-based) |
| **Azure PowerShell** | PowerShell scripting and automation |
| **REST API** | Programmatic access for any language |
| **SDKs** | Language-specific libraries (.NET, Python, Java, etc.) |

---

### Azure Subscriptions

A **subscription** is a logical unit of Azure services linked to an Azure account. It acts as both a billing boundary and an access control boundary.

| Boundary Type | Description |
|---|---|
| **Billing boundary** | Separate invoices generated per subscription — used for cost separation by department or project |
| **Access control boundary** | RBAC and Azure Policy are applied at the subscription level |

Common reasons for multiple subscriptions: isolating dev/test/production environments, aligning to departments, meeting compliance requirements.

---

### Management Groups

**Management Groups** sit above subscriptions in the hierarchy, allowing governance policies and RBAC to be applied across multiple subscriptions at once.

```
Root Management Group
  └── Management Group ("Production")
        └── Subscription A, Subscription B
  └── Management Group ("Development")
        └── Subscription C
```

| Limit | Value |
|---|---|
| Maximum management groups per directory | 10,000 |
| Maximum nesting depth (below root, above subscription) | 6 levels |
| Parents per management group or subscription | 1 (single parent only) |

---

### Infrastructure as Code (IaC)

IaC is the practice of defining and managing Azure infrastructure through code files rather than manual portal configuration — making deployments repeatable, version-controlled, and consistent.

#### ARM Templates
Declarative JSON files that define what Azure resources to deploy. ARM handles dependencies and parallel deployments automatically.

#### Bicep
Microsoft's purpose-built language for Azure deployments. Bicep compiles to ARM JSON under the hood but is significantly simpler to read and write — the recommended modern approach for Azure-native IaC.

| Aspect | ARM Templates | Bicep |
|---|---|---|
| **Syntax** | Verbose JSON | Concise, readable |
| **Learning curve** | Steeper | Lower |
| **Feature parity** | Full | Full (immediate support for new APIs) |
| **Idempotency** | Yes | Yes |

---

### Summary

| Concept | Key Point |
|---|---|
| **Resource** | Object representing any Azure service; stored as JSON; has properties, lifecycle |
| **Resource Group** | Mandatory logical container for all resources; used for access, lifecycle, cost, and policy |
| **ARM** | Centralized management layer — every Azure interface routes through ARM |
| **Subscription** | Billing and access control boundary; separate invoice per subscription |
| **Management Groups** | Governance hierarchy above subscriptions; max 10,000 groups, 6 nesting levels |
| **ARM Templates** | Declarative JSON for repeatable, automated Azure deployments |
| **Bicep** | Simpler Azure IaC language that compiles to ARM JSON — recommended modern approach |

> 📝 **Exam Tip:** The full Azure organizational hierarchy is **Management Group → Subscription → Resource Group → Resource**. Governance (policies, RBAC) assigned at a higher level cascades down to all children.

---

> ## Section 10 — Compute Services

Azure compute services provide the processing power to run applications — from traditional virtual machines to fully managed serverless platforms.

---

### 1. Virtual Machines (VMs)

**Azure Virtual Machines** are on-demand, scalable computing resources with full OS control. They are the foundation of IaaS in Azure.

| Aspect | Detail |
|---|---|
| **Service model** | IaaS |
| **OS support** | Windows and Linux |
| **Control level** | Highest — full OS and software control |
| **Maintenance** | Highest — you manage OS, patches, and software |
| **Best for** | Custom configurations, lift-and-shift migration, full OS control |

**Containers vs VMs:** Containers share the host OS kernel (faster to start, smaller footprint). VMs have a full isolated OS (stronger isolation, more overhead). Both run on Azure VMs underneath.

---

### 2. VM Scale Sets

**VM Scale Sets** automatically manage and scale groups of identical, load-balanced VMs.

| Aspect | Detail |
|---|---|
| **Service model** | IaaS |
| **Auto-scaling** | Yes — scales based on demand or schedule |
| **Max nodes** | 1,000 VMs per scale set |
| **Load balancing** | Built in |
| **Best for** | Workloads that need high availability and automatic scaling |

---

### 3. Azure Container Instances (ACI)

**ACI** is the fastest and simplest way to run a container in Azure — no need to manage virtual machines or orchestration.

| Aspect | Detail |
|---|---|
| **Service model** | PaaS |
| **Auto-scaling** | No |
| **Max containers** | ~20 |
| **Best for** | Simple, quick, single container deployments with no orchestration needed |

---

### 4. Azure Kubernetes Service (AKS)

**AKS** is a fully managed Kubernetes container orchestration service for large-scale, production-grade containerized workloads.

| Aspect | Detail |
|---|---|
| **Service model** | PaaS |
| **Auto-scaling** | Yes |
| **Max nodes** | 100 |
| **Best for** | Large-scale container deployments, microservices architectures |
| **Note** | Kubernetes is open-source and also available on AWS and GCP |

---

### 5. Azure Container Apps

**Azure Container Apps** is a PaaS container service that extends ACI by adding **built-in load balancing and auto-scaling** for production-grade, elastic containerized applications.

| Feature | ACI | Azure Container Apps |
|---|---|---|
| Load balancing | No | Yes |
| Auto-scaling | No | Yes |
| Best for | Simple, single containers | Scalable microservices and production APIs |

---

### 6. Azure App Service

**App Service** is Azure's enterprise-grade web hosting platform. Developers deploy their code and Azure handles everything else.

| Aspect | Detail |
|---|---|
| **Service model** | PaaS |
| **Supported languages** | .NET, .NET Core, Node.js, Python, PHP, Java, Ruby, containers |
| **Auto-scaling** | Yes — up to 20–100 nodes depending on tier |
| **Best for** | Enterprise web apps, REST APIs, applications in any major language |

**App Service Hosting Types:**

| Type | Description |
|---|---|
| **Web Apps** | Host websites on Windows or Linux |
| **API Apps** | Build REST APIs with full Swagger support |
| **WebJobs** | Run background scripts or executables on a schedule or trigger |
| **Mobile Apps** | Backend for iOS and Android apps with social auth, push notifications, SQL storage |

---

### 7. Azure Functions

**Azure Functions** is a serverless compute service for running small event-triggered pieces of code without managing any servers.

| Aspect | Detail |
|---|---|
| **Service model** | PaaS / Serverless |
| **Auto-scaling** | Yes — from 0 to 200 nodes |
| **Pricing** | Consumption-based (~$0.20 per 1 million executions) or App Service Plan |
| **Best for** | Nano-services, event-driven code, scheduled tasks, lightweight APIs |
| **Key differentiator** | Scale-to-zero capability — no servers (and no charges) when idle |

---

### 8. VM Availability Sets

**Availability Sets** group VMs to protect against hardware failures and planned maintenance within a single data center.

| Mechanism | Protects Against | How |
|---|---|---|
| **Update Domains** | Planned maintenance/reboots | Only one update domain offline at a time (default: 5) |
| **Fault Domains** | Power or hardware failure | Spreads VMs across separate power/network racks (default: 2) |

No additional cost — you only pay for the VMs. Best practice: always place at least **two VMs** in an Availability Set for production workloads.

> 📝 **Exam Tip:** Availability Sets ≠ Availability Zones. Availability Sets protect **within a single datacenter**. Availability Zones protect across **physically separate datacenters** within a region.

---

### 9. Azure Virtual Desktop

**Azure Virtual Desktop (AVD)** is a cloud-hosted desktop virtualization service. Users access a full Windows desktop from any device via a browser or Remote Desktop client.

| Feature | Detail |
|---|---|
| **Access** | Any device (Windows, Mac, iOS, Android) via browser or Remote Desktop app |
| **Multi-session** | Windows 10/11 Enterprise multi-session: multiple concurrent users on one VM |
| **Security** | Identity via Microsoft Entra ID; data stays in the cloud; MFA support |
| **Cost** | Pay only for what you use; no physical hardware per user |

---

### Full Compute Services Comparison

| Service | Model | Auto-Scale | Max Nodes | Control | Maintenance | Best For |
|---|---|---|---|---|---|---|
| **Virtual Machines** | IaaS | No | 1 | Highest | Highest | Custom OS, lift-and-shift |
| **VM Scale Sets** | IaaS | Yes | 1,000 | High | High | Auto-scaling VM workloads |
| **Container Instances** | PaaS | No | ~20 | Medium | Low | Simple/quick containers |
| **Kubernetes Service** | PaaS | Yes | 100 | High | High | Large-scale containers |
| **Container Apps** | PaaS | Yes | Variable | Medium | Low | Production containers with scaling |
| **App Service** | PaaS | Yes | 20–100 | Low | Low | Web apps and APIs |
| **Azure Functions** | PaaS/Serverless | Yes | 200 | Lowest | Lowest | Nano-services, event-driven |

---

### Summary

| Service | Best For |
|---|---|
| **Virtual Machines** | Full OS control, custom configuration, lift-and-shift migration |
| **VM Scale Sets** | Auto-scaling groups of identical VMs — load-balanced, high availability |
| **Availability Sets** | Protect VMs from planned/unplanned downtime within one datacenter |
| **Container Instances (ACI)** | Simple, fast single-container deployments — no orchestration needed |
| **Kubernetes Service (AKS)** | Large-scale container orchestration — microservices, production APIs |
| **Container Apps** | Production containers with built-in load balancing and auto-scaling |
| **App Service** | Web apps, API apps, WebJobs (background tasks), Mobile app backends |
| **Azure Functions** | Serverless code triggered by events; billed per execution; scales to zero |
| **Azure Virtual Desktop** | Cloud-hosted Windows desktop accessible from any device via a browser |

---

> ## Section 11 — Networking Services

Azure networking services enable you to connect cloud and on-premises resources, protect and monitor traffic, and deliver applications at global scale.

---

### 1. Azure Virtual Network (VNet)

A **VNet** is an emulation of a physical network in the cloud. Every Azure resource that needs network connectivity must be placed in a VNet.

VNets allow you to:
- Create, manage, monitor, and secure connectivity between Azure resources
- Connect Azure resources to on-premises environments
- Segment the network into smaller pieces using **subnets**

**Subnets** serve two purposes: efficient IP address allocation, and grouping related resources to apply traffic rules.

A VNet is **scoped to a single Azure region**. To connect VNets across regions, use:

| Option | Description |
|---|---|
| **VNet Peering** | Connects VNets so they act as one network — low latency, uses Microsoft backbone |
| **VPN Gateway** | Connects VNets via an encrypted tunnel (also used for on-premises connectivity) |

---

### 2. VPN Gateway

**VPN Gateway** sends encrypted traffic between Azure Virtual Networks and on-premises networks **over the public internet**.

**VPN Types:**

| Type | Description | Use Case |
|---|---|---|
| **Policy-Based** | Encrypts based on statically defined IP address sets | Legacy/specific compatibility scenarios |
| **Route-Based** (recommended) | Tunnels modelled as virtual network interfaces; dynamic routing | VNet-to-VNet, point-to-site, multi-site, ExpressRoute coexistence |

**High Availability Options:**

| Configuration | Description |
|---|---|
| **Active/Standby** (default) | Auto-failover in seconds (planned) or ~90 seconds (unplanned) |
| **Active/Active** | Both instances live; separate tunnels from on-premises; requires BGP on-premises device |
| **ExpressRoute Failover** | VPN Gateway as a backup path if ExpressRoute circuit fails |
| **Zone-Redundant** | Deploy gateway across Availability Zones; requires specific SKUs and Standard public IPs |

---

### 3. Azure Load Balancer

**Azure Load Balancer** distributes incoming network traffic evenly across multiple backend VMs. Works at Layer 4 (TCP/UDP).

| Type | Description |
|---|---|
| **Public Load Balancer** | Has a public IP — handles internet-facing traffic |
| **Internal Load Balancer** | Private IP only — handles traffic between internal tiers |

Load Balancer automatically performs **health checks** and stops sending traffic to unhealthy instances. VMs in separate Availability Zones behind a load balancer achieve a **99.99% SLA**.

> 📝 **Exam Tip:** Load Balancer = TCP/UDP (non-web) traffic distribution. For HTTP/HTTPS web traffic, use **Application Gateway** instead.

---

### 4. Application Gateway

**Application Gateway** is a web traffic load balancer specifically designed for **HTTP/HTTPS traffic** with additional security features.

| Feature | Description |
|---|---|
| **Web Application Firewall (WAF)** | Scans and filters all incoming web traffic for threats |
| **URL-based routing** | Route traffic to different backends based on URL path |
| **SSL termination** | Decrypts HTTPS at the gateway; sends plain traffic to backends |
| **Session affinity** | Ensures a user's requests go to the same backend server |

---

### 5. Content Delivery Network (CDN)

**Azure CDN** caches static content (images, JS, CSS, HTML) across **120+ Point of Presence (PoP) locations** worldwide, so users receive content from the nearest location — dramatically reducing latency and offloading frontend servers.

---

### 6. Azure ExpressRoute

**ExpressRoute** provides a **dedicated private connection** from your on-premises network into Azure — bypassing the public internet entirely.

| Aspect | VPN Gateway | ExpressRoute |
|---|---|---|
| **Connection path** | Over public internet (encrypted) | Private dedicated line |
| **Speed** | Up to several Gbps | Up to 100 Gbps |
| **Latency** | Variable | Consistent and predictable |
| **Security** | Encrypted tunnel | Inherently private |

**ExpressRoute Connectivity Models:**

| Model | Description |
|---|---|
| **CloudExchange colocation** | Virtual cross-connect at a shared facility |
| **Point-to-point Ethernet** | Direct dedicated link from your facility to Azure |
| **Any-to-any (IP VPN)** | Integrate existing WAN with Azure |
| **ExpressRoute Direct** | Connect directly into Microsoft's global network at up to 100 Gbps |

Uses **BGP (Border Gateway Protocol)** for dynamic routing. Built-in redundancy at every peering location.

---

### 7. Azure DNS

**Azure DNS** hosts DNS domains using Microsoft's global anycast infrastructure. It does **not** allow purchasing domain names — only hosting and managing DNS records.

Key features: RBAC integration, private DNS zones for internal VNet name resolution, and **alias records** that automatically update when an Azure resource's IP changes.

---

### Summary

| Service | Purpose | Key Detail |
|---|---|---|
| **Virtual Network (VNet)** | Isolated network for Azure resources | Regional; uses subnets; NSGs control traffic |
| **VNet Peering** | Connect two VNets privately | Low latency; Microsoft backbone; bidirectional |
| **VPN Gateway** | Encrypted on-premises to Azure tunnel | Route-based (preferred) vs. Policy-based (legacy) |
| **Load Balancer** | Distribute TCP/UDP traffic across VMs | Layer 4; public or internal; health checks built in |
| **Application Gateway** | Web traffic load balancing with security | Layer 7; WAF; SSL termination; URL routing |
| **CDN** | Cache static content globally | 120+ PoP locations; reduces latency |
| **ExpressRoute** | Private dedicated connection to Azure | Up to 100 Gbps; consistent latency; no public internet |
| **Azure DNS** | Host DNS domains in Azure | Anycast resolution; alias records track Azure IP changes |

---

> ## Section 12 — Storage Services

Azure storage services cover all three data types: structured (relational), semi-structured (NoSQL), and unstructured (files, blobs).

---

### Types of Data

| Data Type | Description | Example |
|---|---|---|
| **Structured** | Strict schema; rows in tables with defined columns and relationships | SQL databases |
| **Semi-structured** | Tables/rows but no strict schema — each row can have different properties | NoSQL, JSON documents |
| **Unstructured** | No schema — any kind of file or binary data | Images, videos, PDFs, logs |

---

### 1. Azure Blob Storage

**Blob** = Binary Large Object = any kind of file. Designed for **unstructured data** of any type or size.

| Term | Blob Storage Equivalent |
|---|---|
| File | Blob |
| Folder / Bucket | Container |

**Blob Storage Access Tiers:**

| Tier | Access Frequency | Performance | Cost |
|---|---|---|---|
| **Hot** | Frequent | Highest | Higher storage cost |
| **Cool** | Infrequent | Lower | Cheaper storage; good for backups |
| **Archive** | Rare / never | Lowest (hours to retrieve) | Cheapest (~10x cheaper than Hot) |

---

### 2. Azure Queue Storage

**Queue Storage** stores small messages between application components, enabling **asynchronous, decoupled processing**.

How it works: a front-end app writes tasks as messages to a queue; background workers pick them up at their own pace. Benefits include offloading the frontend, enabling scalable architectures, and allowing different services to handle different tasks independently.

---

### 3. Azure Table Storage

**Table Storage** is Azure's simple **NoSQL database** for semi-structured data.

Key characteristics:
- Schema-less — each row (entity) can have different properties
- Only requires a **compound key** (Partition Key + Row Key) to uniquely identify rows
- No foreign keys, joins, or relationships
- Extremely scalable — petabytes of data with millisecond response times via compound key access

> 📝 **Exam Tip:** Use Table Storage for fast, simple semi-structured data without complex relationships. For geo-replication or advanced NoSQL features, use **Azure Cosmos DB** instead.

---

### 4. Azure File Storage

**Azure File Storage** provides **fully managed file shares** accessible via the **SMB (Server Message Block) protocol** — the same protocol used by Windows and Linux for shared drives. This makes it a direct replacement for on-premises file servers.

Key features: mount as a drive letter on Windows, macOS, or Linux; access from on-premises using VPN or ExpressRoute; replaces legacy on-premises file servers without changing applications.

---

### 5. Azure Storage Account

A **Storage Account** is the top-level container that groups all Azure storage services (Blobs, Queues, Tables, Files) under a single resource.

| Feature | Detail |
|---|---|
| **Unique namespace** | Each storage account gets a globally unique URL (`storageaccountname.blob.core.windows.net`) |
| **Redundancy options** | LRS, GRS, ZRS, GZRS — configurable per account |
| **Tiers** | Standard (HDD) or Premium (SSD) |

**Replication Options:**

| Option | Full Name | Description |
|---|---|---|
| **LRS** | Locally Redundant Storage | 3 copies within one datacenter — cheapest, lowest protection |
| **GRS** | Geo-Redundant Storage | 3 copies locally + 3 copies in a paired region |
| **ZRS** | Zone-Redundant Storage | 3 copies across 3 Availability Zones in one region |
| **GZRS** | Geo-Zone-Redundant Storage | 3 zone copies locally + 3 copies in a paired region — highest protection |

---

### 6. Azure Disk Storage

**Azure Disk Storage** provides managed virtual disks for Azure VMs. Microsoft manages the underlying hardware — you manage the disk capacity and type.

| Tier | Use Case |
|---|---|
| **Ultra Disk** | Highest performance — mission-critical, latency-sensitive workloads |
| **Premium SSD** | High-performance production workloads |
| **Standard SSD** | Consistent performance for web servers and dev environments |
| **Standard HDD** | Backup storage and infrequently accessed workloads |

---

### Summary

| Service | Data Type | Best For |
|---|---|---|
| **Blob Storage** | Unstructured | Any file type — images, videos, backups, logs |
| **Queue Storage** | Messages | Asynchronous, decoupled processing between services |
| **Table Storage** | Semi-structured (NoSQL) | Fast, simple key-value data without complex relationships |
| **File Storage** | Unstructured | Managed SMB file shares — replacement for on-premises file servers |
| **Disk Storage** | VM disks | Managed disks for Azure VMs (Ultra, Premium SSD, Standard SSD, HDD) |
| **Storage Account** | Container | Groups Blob, Queue, Table, and File under one resource |
| **Blob Tiers** | — | Hot (frequent), Cool (infrequent), Archive (rare/never) |
| **Storage Redundancy** | — | LRS (local), ZRS (zones), GRS (geo), GZRS (geo + zones) |

---

> ## Section 13 — Database Services

Azure offers a range of managed database services covering relational, NoSQL, and massively parallel analytics workloads.

---

### 1. Azure Cosmos DB

**Azure Cosmos DB** is a **globally distributed, multi-model NoSQL database** designed for applications requiring extremely low latency and global scale.

| Aspect | Detail |
|---|---|
| **Data type** | Semi-structured (NoSQL) |
| **Service model** | PaaS |
| **APIs supported** | SQL, MongoDB, Cassandra, Gremlin, Table — same data, multiple query formats |
| **Global distribution** | Replicate data to any Azure region with a single click |
| **SLA guarantees** | <10ms reads and <15ms writes at the 99th percentile globally |
| **Consistency models** | 5 tunable levels — from strong to eventual consistency |

Best for: globally distributed apps, IoT telemetry, user profile stores, any workload needing <10ms latency at scale.

---

### 2. Azure SQL Database

**Azure SQL Database** is a fully managed **relational database service** (PaaS) based on the latest stable version of Microsoft SQL Server.

| Aspect | Detail |
|---|---|
| **Data type** | Structured (relational) |
| **Service model** | PaaS |
| **Management** | Microsoft manages infrastructure, backups, patching, and HA |
| **Best for** | Cloud-native relational applications |

---

### 3. Azure SQL Family

| Product | Description | Use Case |
|---|---|---|
| **Azure SQL Database** | PaaS — latest SQL Server, slightly reduced feature set | New cloud-native apps |
| **Azure SQL Managed Instance** | PaaS — full SQL Server feature set | Lift-and-shift from on-premises SQL Server |
| **SQL Server on VM** | IaaS — full control over SQL Server and OS | Maximum control, custom configurations |
| **Azure Synapse Analytics** | Massively parallel processing SQL | Big data, data warehousing |

---

### 4. Azure Database for MySQL

Fully managed **MySQL** database in Azure. Ideal for migrating existing MySQL applications to the cloud without changing your application — same MySQL engine, same queries.

---

### 5. Azure Database for PostgreSQL

Fully managed **PostgreSQL** database in Azure. Same platform benefits as Azure Database for MySQL, with the PostgreSQL engine. Choose based on which engine your existing application uses.

---

### Summary

| Service | Data Type | Engine | Model | Best For |
|---|---|---|---|---|
| **Cosmos DB** | Semi-structured (NoSQL) | Multi-API | PaaS | Global distribution, <10ms latency |
| **Azure SQL Database** | Structured (relational) | SQL Server | PaaS | Cloud-native relational apps |
| **SQL Managed Instance** | Structured (relational) | SQL Server (full) | PaaS | Lift-and-shift from on-prem SQL Server |
| **SQL Server on VM** | Structured (relational) | SQL Server | IaaS | Full OS + SQL Server control |
| **Azure Database for MySQL** | Structured (relational) | MySQL | PaaS | Migrating MySQL applications |
| **Azure Database for PostgreSQL** | Structured (relational) | PostgreSQL | PaaS | Migrating PostgreSQL applications |
| **Azure Synapse Analytics** | Structured (big data) | SQL MPP | PaaS | Data warehousing and big data analytics |

> 📝 **Exam Tip:** The most important distinction: **Cosmos DB = NoSQL/semi-structured** while **Azure SQL = relational/structured**. For the SQL family: SQL Database = cloud-native PaaS; SQL Managed Instance = full SQL Server features in PaaS; SQL on VM = IaaS full control.

---

> ## Section 14 — Azure Marketplace

**Azure Marketplace** is Azure's built-in shop where you can browse and provision **pre-built templates and solutions** created by both Microsoft and third-party vendors — covering all three service models (IaaS, PaaS, SaaS).

---

### How to Access

| Access Point | How |
|---|---|
| **Azure Portal** | Create a Resource → opens the Marketplace directly |
| **Marketplace website** | `marketplace.microsoft.com` → "Get it now" redirects to Portal |

---

### Key Features

- Templates may provision a single resource or a complete multi-resource bundle
- License costs from third-party solutions are **integrated into your Azure invoice** — no separate procurement needed
- Companies can publish their own solutions for customers to discover and purchase

---

### Azure Marketplace vs. Microsoft AppSource

| Portal | Products | Target Users |
|---|---|---|
| **Azure Marketplace** | Azure infrastructure and services | Developers and IT professionals |
| **Microsoft AppSource** | Azure, Power BI, Dynamics 365, Microsoft 365 | Business users |

---

### Summary

| Aspect | Detail |
|---|---|
| **Azure Marketplace** | Azure's built-in shop for service templates and solutions |
| **Content creators** | Microsoft + third-party vendors |
| **Service models covered** | IaaS, PaaS, and SaaS |
| **Billing** | Integrated — license costs billed through your Azure invoice |
| **Target audience** | Developers and IT professionals |

> 📝 **Exam Tip:** Azure Marketplace contains products from both Microsoft and third-party vendors. Billing is integrated — no separate vendor invoices. AppSource = business users; Azure Marketplace = technical users.

---

> ## Section 15 — Azure IoT Services

The **Internet of Things (IoT)** is a network of internet-connected devices that collect and transmit data. Azure provides three services for building IoT solutions, ranging from a raw PaaS building block to a complete end-to-end security platform.

---

### 1. Azure IoT Hub

**IoT Hub** is a managed PaaS service that enables **bi-directional communication** between the cloud and IoT devices — the foundation for building custom IoT solutions.

| Aspect | Detail |
|---|---|
| **Service model** | PaaS |
| **Communication** | Bi-directional (cloud ↔ device) |
| **Best for** | Building **custom** IoT solutions from scratch |
| **Integration** | Works with Stream Analytics, Azure Functions, and other Azure services |

---

### 2. Azure IoT Central

**IoT Central** is a higher-level **SaaS IoT application platform** built on top of IoT Hub. It provides pre-built industry-specific templates for managing IoT devices without deep technical expertise.

| Aspect | Detail |
|---|---|
| **Service model** | SaaS |
| **Built on** | IoT Hub + 30+ other Azure services |
| **Technical skill required** | Low — template-based configuration |
| **Best for** | Organizations wanting IoT solutions without building from scratch |

---

### IoT Hub vs. IoT Central

| | IoT Hub | IoT Central |
|---|---|---|
| **Model** | PaaS | SaaS |
| **Customization** | Full (build anything) | Template-based |
| **Technical skill** | High (custom development) | Low (configuration) |
| **Best for** | Custom IoT solutions | Out-of-the-box IoT management |

---

### 3. Azure Sphere

**Azure Sphere** is a **complete end-to-end security solution** for IoT devices, combining three components:

| Component | Description |
|---|---|
| **MCU (Microcontroller Unit)** | Certified chips built to Microsoft's security specifications |
| **Azure Sphere OS** | Microsoft-managed OS that runs on the MCU — always kept up to date |
| **Azure Sphere Security Service** | Secure cloud channel for app updates and OS patching |

Together, these three components ensure trusted hardware, secured OS, and authenticated communication.

---

### Summary

| Service | Model | Best For |
|---|---|---|
| **IoT Hub** | PaaS | Custom IoT application development with bi-directional communication |
| **IoT Central** | SaaS | Ready-to-use IoT platform without building from scratch |
| **Azure Sphere** | Hardware + OS + Service | End-to-end secure IoT device solutions |

> 📝 **Exam Tip:** IoT Hub = PaaS building block for custom IoT. IoT Central = SaaS platform with templates. Azure Sphere = end-to-end **security** for IoT — if a question mentions IoT + security, Sphere is the answer.

---

> ## Section 16 — Big Data & Analytics Services

**Big data** is characterized by the **3 Vs** — high **Velocity** (fast-arriving data), high **Volume** (terabytes/petabytes), and high **Variety** (structured, semi-structured, unstructured). Traditional databases cannot handle all three simultaneously — this is where Azure's big data services come in.

**Typical Big Data Pipeline:**
```
Data Sources → Ingest → Transform → Store → Serve → Reporting/Analytics
```

---

### 1. Azure Synapse Analytics

**Azure Synapse Analytics** is Azure's **end-to-end big data and analytics platform** — a unified service covering the entire data pipeline from ingestion to reporting.

> Previously known as **Azure SQL Data Warehouse** — this rename is a commonly tested fact.

| Component | Purpose |
|---|---|
| **Synapse Pipelines** | Visual workflow tool for ingesting and transforming data |
| **Apache Spark** | Big data processing and transformation engine |
| **Synapse SQL (MPP)** | Massively Parallel Processing SQL — runs queries across huge datasets |
| **Synapse Studio** | Unified web interface to manage all components |
| **Data Lake Integration** | Native integration with Azure Data Lake for large-scale storage |

---

### 2. Azure HDInsight

**Azure HDInsight** is a fully managed, flexible open-source big data platform. You provision clusters of popular open-source technologies — Microsoft manages the clusters.

| Technology | Purpose |
|---|---|
| **Hadoop** | Batch processing of large datasets |
| **Apache Spark** | Fast, in-memory data processing |
| **Kafka** | Real-time data streaming |
| **HBase** | NoSQL database for large datasets |
| **Hive** | SQL-like querying over big data |

---

### 3. Azure Databricks

**Azure Databricks** is a **big data collaboration platform** built on Apache Spark — combining powerful data processing with a shared workspace for data engineers and data scientists.

| Feature | Description |
|---|---|
| **Notebooks** | Interactive Python, Scala, SQL, and R scripts for data analysis |
| **Collaboration workspace** | Shared environment for teams to work together on data projects |
| **Auto-scaling** | Clusters scale automatically based on workload |
| **Auto-terminate** | Clusters shut down when idle — controls cost |
| **Azure integration** | Built-in connectors to Data Lake, Blob Storage, SQL, Cosmos DB, and more |

---

### Summary

| Service | Core Technology | Best For |
|---|---|---|
| **Azure Synapse Analytics** | Spark + SQL MPP + Pipelines | End-to-end analytics platform, data warehousing |
| **Azure HDInsight** | Hadoop, Spark, Kafka, and more | Flexible open-source big data processing |
| **Azure Databricks** | Apache Spark | Collaborative big data transformation and ML |

> 📝 **Exam Tip:** Synapse = unified analytics platform (formerly SQL Data Warehouse). HDInsight = managed open-source clusters (choose from many technologies). Databricks = Spark-focused collaboration workspace.

---

> ## Section 17 — Azure AI & Machine Learning

**Artificial Intelligence (AI)** is software that simulates human intelligence. **Machine Learning (ML)** is a subcategory of AI where software is trained on data to make predictions — without being explicitly programmed with rules.

---

### The Machine Learning Lifecycle
```
Data → Train Model → Package & Validate → Deploy as Web Service → Monitor → Retrain
```

---

### Azure Machine Learning Service

**Azure Machine Learning** is a fully managed, end-to-end PaaS platform for creating, training, and deploying ML models.

| Aspect | Detail |
|---|---|
| **Service model** | PaaS |
| **Top-level resource** | ML **Workspace** — ties all compute, data, experiments, and deployments together |
| **Interface** | **Azure ML Studio** — web-based visual portal |

**Three Ways to Build ML Models:**

| Method | Description | Code Required |
|---|---|---|
| **Notebooks** | Write Python/R scripts in a Jupyter-style browser interface | Yes |
| **Automated ML (AutoML)** | Azure automatically tests multiple algorithms and selects the best-performing one | No |
| **Visual Designer** | Drag-and-drop pipeline builder for data prep, training, and deployment | No |

**Key Features:**

| Feature | Description |
|---|---|
| **Compute Management** | Provision and manage VMs for training and deploying models |
| **Data Stores** | Connect to Azure data sources (Blob, File Shares, etc.) |
| **Pipelines** | Orchestrate end-to-end model training, validation, and deployment |
| **Model Registry** | Store, version, and manage trained models |
| **Endpoints** | Deploy models as REST API web services |

> 📝 **Exam Tip:** There are **two different ML Studio products** in Azure — the old "Machine Learning Studio (classic)" and the current **Azure Machine Learning Studio**. Know the current platform for the exam.

---

### Summary

| Concept | Key Point |
|---|---|
| **AI** | Software that simulates human intelligence |
| **Machine Learning** | Subset of AI — software learns from data to make predictions |
| **Azure Machine Learning** | End-to-end PaaS platform for training and deploying ML models |
| **ML Workspace** | Top-level resource — manages all ML assets, compute, and deployments |
| **AutoML** | Automatically finds the best algorithm for your data — no code |
| **Visual Designer** | No-code drag-and-drop pipeline builder |

---

> ## Section 18 — Serverless Computing Services

**Serverless computing** is a cloud model where you deploy applications without managing any infrastructure. Microsoft automatically provisions, scales, and manages all underlying servers — you only focus on application logic and pay only for what you use.

Azure's three primary serverless services are **Azure Functions**, **Azure Logic Apps**, and **Azure Event Grid**.

---

### 1. Azure Functions

Azure Functions is the core **serverless coding platform** — run small pieces of code as web-callable functions without managing servers. *(Full details in Section 10 — Compute Services.)*

Key serverless characteristics: scales from 0 to 200 instances automatically; consumption-based billing; no charges when idle; code-first approach.

---

### 2. Azure Logic Apps

**Azure Logic Apps** is a serverless **workflow automation service** — build step-by-step business workflows using a visual, no-code designer.

| Aspect | Detail |
|---|---|
| **Service model** | PaaS / Serverless |
| **Code required** | None — fully visual drag-and-drop designer |
| **Connectors** | 200+ connectors to Microsoft and third-party services |
| **Triggers** | Blob Storage events, emails, Office 365 events, scheduled timers, web requests |

**Workflow Capabilities:** sequential steps, if/else conditions, loops, and parallel execution branches.

**Example:** *When a file is uploaded to Azure Blob Storage → automatically send an email via Outlook with the filename and path* — built entirely in the visual designer with no code.

---

### 3. Azure Event Grid

**Azure Event Grid** is a fully managed serverless **event routing service** — its sole purpose is to reliably route events from publishers to subscribers.

```
Event Publishers → Event Grid (Topics) → Event Subscribers
```

| Aspect | Detail |
|---|---|
| **Pattern** | Publish/Subscribe (Pub/Sub) |
| **Publishers** | Blob Storage, Azure Subscriptions, Event Hubs, custom apps |
| **Subscribers** | Azure Functions, Logic Apps, webhooks, Storage Queues |
| **Use case** | Event-driven architectures, reacting to Azure resource events in near real time |

---

### Functions vs. Logic Apps vs. Event Grid

| Service | Purpose | Code Required | Best For |
|---|---|---|---|
| **Azure Functions** | Run small pieces of code as web services | Yes | Custom nano-services, event-triggered code |
| **Azure Logic Apps** | Build automated workflows and integrations | No (visual) | Business process automation, app integration |
| **Azure Event Grid** | Route events between Azure services | No | Event-driven architectures, reacting to Azure events |

> 📝 **Exam Tip:** "Automatically process files on upload without writing code" → **Logic Apps** (no-code, Blob trigger + 200 connectors). "Custom code triggered by events" → **Azure Functions**. "Route events between multiple services" → **Event Grid**.

---

### Summary

| Concept | Key Point |
|---|---|
| **Serverless** | No server management; auto-scaling; pay per execution |
| **Azure Functions** | Serverless code execution; scales 0→200; billed per execution; scale-to-zero |
| **Logic Apps** | No-code visual workflow automation; 200+ connectors; triggers from many Azure/third-party sources |
| **Event Grid** | Serverless event router; pub/sub model; connects publishers to subscribers |

---

> ## Section 19 — Azure DevOps Solutions

**DevOps** combines software development (Dev) and IT operations (Ops) to shorten development lifecycles and deliver software faster with higher quality. The core methodology is **CI/CD**: Continuous Integration (automatically build and test on commit) and Continuous Delivery/Deployment (automatically deploy tested code).

---

### 1. Azure DevOps

**Azure DevOps** is an end-to-end DevOps platform covering the entire software development lifecycle.

> Previously known as TFS (on-premises) → VSTS (cloud) → **Azure DevOps**.

**Five Core Services:**

| Service | Purpose |
|---|---|
| **Azure Boards** | Track work, manage user stories, features, bugs, and project progress |
| **Azure Repos** | Host code repositories with Git or TFVC version control |
| **Azure Pipelines** | Build CI/CD pipelines — automate build, test, and deployment |
| **Azure Artifacts** | Create, host, and share packages (NuGet, npm, Maven) integrated into pipelines |
| **Azure Test Plans** | Manage manual and exploratory testing — track test cases and results |

The **Azure DevOps Marketplace** offers 1,000+ extensions to customize the platform further.

---

### 2. Azure DevTest Labs

**Azure DevTest Labs** is a managed workspace for developers and testers to quickly provision VMs for development and testing — without needing admin access to the full Azure subscription.

**How It Works:**

1. An **admin** configures: allowed VM images, allowed VM sizes, user quotas, auto-shutdown and auto-start policies
2. **Developers/testers** choose a base image, add pre-configured tool artifacts (Visual Studio, Git, etc.), and create a VM in minutes
3. When done, the VM is stopped or deleted — you only pay for actual use

| Feature | Description |
|---|---|
| **Self-service VMs** | Users create their own VMs without admin involvement |
| **Artifacts** | Pre-built installers for popular dev tools added at VM creation |
| **Custom images** | Create reusable VM templates from configured machines |
| **Lab policies** | Quotas, allowed sizes, auto-shutdown to control costs |

---

### Summary

| Service | Purpose |
|---|---|
| **Azure DevOps** | End-to-end DevOps platform: Boards, Repos, Pipelines, Artifacts, Test Plans |
| **Azure Boards** | Project tracking — user stories, bugs, features |
| **Azure Repos** | Code hosting with Git or TFVC |
| **Azure Pipelines** | CI/CD automation — build, test, deploy |
| **Azure Artifacts** | Package hosting and sharing |
| **Azure Test Plans** | Manual and exploratory testing management |
| **Azure DevTest Labs** | Self-service dev/test VMs with policies, quotas, and auto-shutdown |

> 📝 **Exam Tip:** Know the five services of Azure DevOps individually — Boards (planning), Repos (code), Pipelines (CI/CD), Artifacts (packages), Test Plans (testing). DevTest Labs = self-service, policy-governed dev/test VMs for cost control.

---

> ## Section 20 — Azure Management Tools

Azure provides multiple tools for managing resources — from visual web interfaces to command-line and scripting environments.

---

### Azure Portal

The **Azure Portal** (`portal.azure.com`) is a web-based graphical interface for managing all Azure services. Features include: customizable dashboards, resource management and creation forms, monitoring and alerting, built-in Cloud Shell, and access control (RBAC) management.

The portal supports **Preview features** — experimental capabilities that can be toggled on/off per user. The preview portal at `preview.portal.azure.com` provides access to upcoming portal features before general availability.

---

### Azure CLI

The **Azure CLI** is a cross-platform command-line tool for managing Azure resources. Uses Bash-style commands (e.g., `az vm create`). Available on Windows, macOS, Linux, and in Cloud Shell. Ideal for scripting and automation in non-Windows environments.

---

### Azure PowerShell

**Azure PowerShell** is a module that adds Azure-specific cmdlets to PowerShell (e.g., `New-AzVM`). Preferred by Windows administrators already familiar with PowerShell. Available cross-platform.

---

### Azure Cloud Shell

**Azure Cloud Shell** is a browser-based shell environment integrated into the Azure Portal. It supports both **Bash (Azure CLI)** and **PowerShell**, with no local installation required. Automatically authenticated with your Azure account and comes with the Azure CLI, PowerShell module, and common tools pre-installed.

---

### CLI vs PowerShell vs Portal

| Tool | Best For |
|---|---|
| **Azure Portal** | Visual management, exploration, one-off tasks |
| **Azure CLI** | Bash/Linux scripting, cross-platform automation |
| **Azure PowerShell** | Windows/PowerShell scripting and automation |
| **Cloud Shell** | Quick browser-based scripting without local installation |

---

### ARM Templates & Bicep

Azure Resource Manager Templates (JSON) and Bicep allow **Infrastructure as Code** deployments — covered in Section 9.

---

### Summary

| Tool | Type | Best For |
|---|---|---|
| **Azure Portal** | Web GUI | Visual management, exploration, one-off tasks |
| **Azure CLI** | Command line | Bash scripting and automation |
| **Azure PowerShell** | Scripting shell | Windows/PowerShell scripting and automation |
| **Azure Cloud Shell** | Browser shell | Quick scripts without local tools |
| **ARM Templates** | JSON IaC | Declarative, repeatable infrastructure deployment |
| **Bicep** | IaC language | Simplified Azure IaC — compiles to ARM JSON |

> 📝 **Exam Tip:** All management tools route through **Azure Resource Manager (ARM)**. Cloud Shell = browser-based CLI/PowerShell with no installation. ARM Templates and Bicep = Infrastructure as Code.

---

> ## Section 21 — Azure Advisor & Monitoring

Azure provides a suite of advisory and monitoring tools to help you optimize, track, and respond to the health and performance of your resources.

---

### Azure Advisor

**Azure Advisor** is a free, personalized best-practice consultant that analyzes your deployed resources and provides **actionable recommendations** across five categories:

| Category | What It Recommends |
|---|---|
| **Cost** | Eliminate idle resources, rightsize VMs, use reservations |
| **Security** | Enable MFA, restrict management port access, install endpoint protection |
| **Reliability** | Enable geo-redundant storage, add VMs to Availability Sets |
| **Performance** | Upgrade VM SKUs for better throughput, reduce latency |
| **Operational Excellence** | Monitor subscriptions, apply service health alerts |

Each recommendation includes a description, suggested action, and impact level. You can configure **Advisor Alerts** to be notified when new recommendations appear.

> 📝 **Exam Tip:** Azure Advisor is **free** and covers five pillars: Cost, Security, Reliability, Performance, and Operational Excellence. These align with the Azure Well-Architected Framework.

---

### Azure Health Services

Three interconnected services track Azure's health at different scopes:

| Service | Scope | Purpose |
|---|---|---|
| **Azure Status** | Global (`status.azure.com`) | Broadly impacting incidents across all Azure regions |
| **Azure Service Health** | Your subscriptions/regions | Personalized — incidents, planned maintenance, and advisories for your services |
| **Azure Resource Health** | Individual resource | Is *this specific VM/service* healthy or affected by an Azure issue? |

---

### Azure Monitor

**Azure Monitor** is a comprehensive platform for collecting, analyzing, visualizing, and acting on telemetry from resources in Azure, on-premises, and other clouds.

**Data Flow:**
```
Sources (Apps, OS, Network, Azure Resources)
    ↓
Central Repositories (Metrics store + Log Analytics workspace)
    ↓
Actions (Dashboards, Alerts, Autoscaling, Power BI, Logic Apps)
```

#### Azure Log Analytics
The tool within Azure Monitor for writing and running queries against collected log data. Uses **Kusto Query Language (KQL)**.

#### Azure Monitor Alerts
Automatically notify or trigger actions when monitored conditions exceed thresholds:

| Alert Type | Monitors | Example |
|---|---|---|
| **Metric alerts** | Numeric values (CPU %, memory, disk I/O) | Alert when CPU > 80% for 5 minutes |
| **Log alerts** | Log query results | Alert when error rate exceeds a threshold |

**Action Groups** define what happens when an alert fires: email, SMS, push notification, Azure Function, Logic App, or webhook.

#### Application Insights
Monitors **live web applications** — tracking performance, failures, dependencies, and user behavior in real time. Add the SDK to your application code, or install the agent (no code changes).

Tracks: request rates, response times, failure rates, dependency performance, page views, user and session counts, and server performance counters.

---

### Summary

| Tool | Purpose |
|---|---|
| **Azure Advisor** | Free personalized best-practice recommendations — Cost, Security, Reliability, Performance, OE |
| **Azure Status** | Global Azure health — broadly impacting incidents |
| **Azure Service Health** | Your personalized health — incidents/maintenance for your services and regions |
| **Azure Resource Health** | Individual resource health — is *this specific resource* affected? |
| **Azure Monitor** | Collect, analyze, and act on telemetry from all resources |
| **Log Analytics** | Query log data using KQL |
| **Monitor Alerts** | Automated notifications/actions when thresholds are exceeded |
| **Action Groups** | Define who to notify and what to do when an alert fires |
| **Application Insights** | Live web app monitoring — requests, failures, dependencies, users |

---

> ## Section 22 — Network & Application Security Groups

By default, Azure allows all traffic between resources in a VNet and from the internet — a major security risk. **Network Security Groups (NSGs)** and **Application Security Groups (ASGs)** are the tools to enforce traffic restrictions.

---

### 1. Network Security Groups (NSGs)

An **NSG** is a set of inbound and outbound traffic rules applied to Azure resources within a VNet to **filter network traffic**. Applied to a **subnet** (all resources within) or a **network interface** (specific VM).

**Rule Properties:**

| Property | Description | Example |
|---|---|---|
| **Source** | Where traffic comes from | Any, IP, IP range, Service Tag, or ASG |
| **Destination** | Where traffic is going | Any, IP, IP range, Service Tag, or ASG |
| **Protocol** | TCP, UDP, or Any | TCP |
| **Port / Port Range** | Which ports to filter | 3389 (RDP), 443 (HTTPS), * (any) |
| **Direction** | Inbound or Outbound | Inbound |
| **Action** | Allow or Deny | Allow |
| **Priority** | Rule evaluation order | Lower number = evaluated first |

Rules are evaluated in **priority order** (lowest number first). The first matching rule wins. Default rules deny all inbound and allow all outbound if no custom rules match.

---

### 2. Application Security Groups (ASGs)

**ASGs** allow you to group VMs by role and use those groups in NSG rules — instead of managing individual static IP addresses.

**Example workflow:**
1. Create ASGs: `WebServers`, `AppServers`, `DatabaseServers`
2. Assign VMs to their respective ASGs
3. Write NSG rules using ASG names as source/destination:
   - Allow `Internet` → `WebServers` on port 443
   - Allow `WebServers` → `AppServers` on port 8080
   - Allow `AppServers` → `DatabaseServers` on port 1433
   - Deny everything else

When VMs are added or removed, just update ASG membership — NSG rules don't change.

**Important:** ASGs only work with resources within the **same Virtual Network**.

---

### Summary

| Feature | NSG | ASG |
|---|---|---|
| **What it is** | Set of traffic filter rules | Logical grouping of VMs by role |
| **Applied to** | Subnets or network interfaces | Individual VM network interfaces |
| **Purpose** | Allow or deny traffic | Simplify NSG rule management |
| **Rules reference** | IPs, Service Tags, or ASGs | Used as source/destination in NSG rules |

> 📝 **Exam Tip:** NSGs **filter traffic** (allow/deny rules). ASGs **group resources** to make filtering easier. They work together: ASGs remove the need to manage individual IP addresses in NSG rules.

---

> ## Section 23 — User-Defined Routes & Route Tables

**Routing** is the process of finding a path for traffic to travel between servers across one or more networks.

---

### Azure Default Routing

Azure automatically creates an internal routing table for every VNet. By default, VMs in the same VNet can communicate immediately, and VMs can reach the internet without any configuration. No manual setup is needed for basic connectivity.

---

### User-Defined Routes (UDRs)

**UDRs** are custom static routes that **override Azure's default routing** and redirect traffic to a specific next hop — most commonly a **Network Virtual Appliance (NVA)** (a VM running firewall software).

**Without UDR:**
```
Web Server → API Server  (direct, 1 hop)
```

**With UDR routing via NVA:**
```
Web Server → NVA (Firewall) → API Server  (traffic inspected, 2 hops)
```

---

### Route Tables

A **Route Table** is the Azure resource used to create and manage UDRs.

| Aspect | Detail |
|---|---|
| **Association** | Attached to one or more subnets — all traffic leaving follows the route table |
| **Reusability** | One route table can be used across multiple subnets |
| **Route components** | Destination address prefix + Next hop type + Next hop address |

**Configuration Steps:**
1. Create a Route Table resource
2. Add a route (address prefix, next hop type, next hop address)
3. Associate the route table with the originating subnet

---

### Summary

| Concept | Key Point |
|---|---|
| **Default routing** | Azure auto-configures routes between VMs and to the internet |
| **UDR** | Custom static route that overrides Azure's default routing |
| **Route Table** | Azure resource holding UDRs; associated with subnets |
| **NVA** | Specialized VM (e.g., firewall) used as a next hop for traffic inspection |
| **Common use case** | Force all traffic through a firewall before reaching its destination |

> 📝 **Exam Tip:** Route tables are associated with **subnets**, not individual VMs. One route table can be reused across multiple subnets. The most common use case is routing traffic through an NVA/firewall for inspection.

---

> ## Section 24 — Azure Firewall

A **firewall** monitors and controls incoming and outgoing network traffic based on configured rules. NSGs provide basic IP/port filtering; Azure Firewall adds **advanced, centralized protection** across multiple VNets.

---

### Azure Firewall

**Azure Firewall** is a fully managed, cloud-based firewall service (PaaS) that provides centralized advanced network protection.

**Advantages over NVA-based firewalls:** fully managed (no VM to maintain), built-in high availability, auto-scaling, and centralized management across multiple subnets and VNets.

**Key Features:**

| Feature | Description |
|---|---|
| **Managed service (PaaS)** | Microsoft manages infrastructure; you manage rules |
| **High availability** | Built in by default — no configuration needed |
| **Auto-scaling** | Scales automatically to meet traffic demand |
| **FQDN filtering** | Allow/deny traffic based on domain names (e.g., `*.microsoft.com`) — not just IPs |
| **Inbound & outbound filtering** | Filter traffic in both directions |
| **Azure Monitor integration** | Centralized logging and analytics |

**Architecture:**
```
VM (in subnet) → Route Table (UDR) → Azure Firewall Subnet → Internet / Destination
```
Traffic is redirected to Azure Firewall by a UDR. If no rule matches → **traffic is denied by default**.

---

### Azure Firewall vs. NSG

| Feature | NSG | Azure Firewall |
|---|---|---|
| **Filter by IP/Port** | Yes | Yes |
| **Filter by FQDN** | No | Yes |
| **Scope** | Subnet or NIC | Multiple subnets and VNets |
| **Logging** | Basic | Full Azure Monitor integration |
| **Cost** | Free | Paid |

---

### Summary

| Aspect | Detail |
|---|---|
| **Azure Firewall** | Managed PaaS firewall (Firewall-as-a-Service) |
| **Key differentiator** | FQDN filtering — allow/deny by domain name, not just IP |
| **High availability** | Built-in by default |
| **Scalability** | Auto-scales automatically |
| **Logging** | Full Azure Monitor integration |
| **Default behavior** | Deny all unmatched traffic |

> 📝 **Exam Tip:** Azure Firewall's key differentiator from NSGs: **FQDN-based filtering** and **centralized management across multiple VNets**. NSGs filter by IP/port; Azure Firewall adds domain-name-based filtering.

---

> ## Section 25 — Azure DDoS Protection

A **DoS (Denial of Service)** attack floods a server with traffic to disrupt service. A **DDoS (Distributed DoS)** attack does the same from thousands of servers simultaneously, making it much harder to block since traffic comes from many different source IPs.

---

### Azure DDoS Protection

Azure DDoS Protection detects and mitigates DDoS attacks against Azure-hosted resources.

```
Internet → DDoS Protection (filters attacks) → Your Azure Service
```

---

### Two Tiers

| Tier | Cost | Coverage | Features |
|---|---|---|---|
| **Basic** | Free (included automatically) | All Azure public endpoints | Always-on monitoring, automatic mitigation |
| **Standard** | Paid | Resources in protected Virtual Networks | Advanced mitigation, ML-based analysis, monitoring dashboards, cost protection |

---

### Standard Tier Features

| Feature | Description |
|---|---|
| **Advanced attack mitigation** | Handles sophisticated, targeted DDoS attacks |
| **Machine learning** | Analyzes your application's normal traffic patterns for accurate detection |
| **Real-time monitoring** | Dashboards showing attack metrics and traffic analysis |
| **Cost protection** | Prevents auto-scaling bills from spiking during an attack — Azure absorbs extra compute costs |
| **Rapid response team** | Access to Microsoft DDoS experts during an active attack |

**How to Enable Standard:** Create a **DDoS Protection Plan** resource and associate it with a Virtual Network. All resources within that VNet are then protected.

---

### Summary

| Aspect | Basic Tier | Standard Tier |
|---|---|---|
| **Cost** | Free | Paid |
| **Enablement** | Automatic for all Azure services | Manual — create a DDoS Protection Plan |
| **Coverage** | All public Azure endpoints | Resources in protected Virtual Networks |
| **ML-based detection** | No | Yes |
| **Cost protection** | No | Yes — covers auto-scaling costs during attacks |
| **Monitoring dashboards** | No | Yes |

> 📝 **Exam Tip:** Basic = **free and automatic** for every Azure service. Standard adds **ML-based detection** and **cost protection** against billing spikes from auto-scaling during attacks. Standard is applied at the **Virtual Network** level.

---

> ## Section 26 — Azure Identity Services

---

### Core Identity Concepts

| Concept | Definition |
|---|---|
| **Identity** | A representation of a user, application, or service that can be authenticated |
| **Authentication (AuthN)** | Verifying *who* you are — e.g., confirming your password |
| **Authorization (AuthZ)** | Determining *what* you're allowed to do after identity is confirmed |
| **Access Management** | The overall practice of controlling, verifying, tracking, and managing access |

> 📝 **Exam Tip:** Authentication always comes first — you must prove who you are before the system checks what you're allowed to do.

---

### Azure Active Directory (Microsoft Entra ID)

**Azure Active Directory (Azure AD)** — now officially rebranded as **Microsoft Entra ID** — is Azure's centralized identity and access management service. Both names refer to the same service.

It governs access to Azure subscriptions, Microsoft 365, Live.com services (Skype, Outlook.com, OneDrive), and custom applications.

**Key Features:**

| Feature | Description |
|---|---|
| **User & group management** | Create and manage user accounts and groups |
| **Role assignments** | Grant users or groups specific roles on Azure resources |
| **SSO** | One login for all Microsoft cloud services |
| **Azure AD Connect** | Sync on-premises Active Directory to Azure AD for hybrid identity |
| **Multi-Factor Authentication** | Require additional verification beyond passwords |

---

### Multi-Factor Authentication (MFA)

MFA requires **two or more pieces of evidence** to verify identity. The three factor types:

| Factor Type | Description | Examples |
|---|---|---|
| **Knowledge** | Something you know | Password, PIN |
| **Possession** | Something you have | Phone, token, smart card |
| **Inherence** | Something you are | Fingerprint, face ID, iris scan |

A true MFA requires at least **two different factor types**. Azure AD supports MFA natively and can be enforced via Conditional Access policies.

---

### Microsoft Entra Domain Services

**Microsoft Entra Domain Services** provides managed domain services — domain join, group policy, LDAP, Kerberos/NTLM — **without deploying or managing domain controllers**. Ideal for legacy applications requiring traditional AD protocols.

One-way sync: `On-premises AD → Entra ID → Entra Domain Services` (objects created in Entra Domain Services are not synced back).

---

### Passwordless Authentication

Three passwordless methods in Azure:

| Method | How It Works | Security Level |
|---|---|---|
| **Windows Hello for Business** | Biometric or PIN tied to a specific Windows device | High |
| **Microsoft Authenticator App** | Phone notification + biometric confirmation | High |
| **FIDO2 Security Keys** | Hardware USB/NFC key; private key never leaves the device; unphishable | Highest |

---

### Azure External Identities (Entra External ID)

| Scenario | Description |
|---|---|
| **B2B Collaboration** | Invite external partners as guests in your directory — they authenticate with their own credentials |
| **B2B Direct Connect** | Two-way trust between two Entra ID orgs for Teams shared channels — no guest accounts |
| **Azure AD B2C** | Consumer-facing identity — customers use social logins (Google, Facebook); scales to millions |

---

### Azure Conditional Access

**Conditional Access** evaluates signals during sign-in and makes dynamic access decisions: grant, require MFA, or block — based on context.

**Signal → Decision → Enforcement:**
- Signals: user identity, device compliance, location, application, real-time risk score
- Decision: Allow / Require MFA / Block
- Common policies: always require MFA for admins; block sign-ins from unusual countries; restrict unmanaged devices to approved apps

---

### Summary

| Concept | Key Point |
|---|---|
| **Azure AD / Microsoft Entra ID** | Same service, rebranded — centralized identity for all Microsoft cloud services |
| **Azure AD Connect** | Syncs on-premises AD to Azure AD — enables hybrid identity |
| **MFA** | Requires 2+ factor types: Knowledge, Possession, Inherence |
| **Entra Domain Services** | Managed LDAP/Kerberos/NTLM — no domain controllers to manage |
| **Passwordless — Windows Hello** | Device-bound biometric or PIN; SSO supported |
| **Passwordless — Authenticator App** | Phone notification + biometric; cross-platform |
| **Passwordless — FIDO2** | Hardware security key; unphishable; highest security |
| **B2B Collaboration** | External partners as guests; authenticate with own credentials |
| **B2C** | Consumer identity; social logins; millions of users |
| **Conditional Access** | If-then policy engine — evaluates signals to allow/MFA/block access |

---

> ## Section 27 — Microsoft Defender for Cloud

**Microsoft Defender for Cloud** (formerly Azure Security Center + Azure Defender) is a unified security management platform that continuously assesses, secures, and defends your Azure resources — and extends to on-premises and multi-cloud environments.

---

### Three Core Functions

| Function | Description |
|---|---|
| **Continuously Assess** | Vulnerability assessments for VMs, container registries, and SQL servers |
| **Secure** | Secure Score tracks your security posture; recommendations prioritized by impact |
| **Defend** | Real-time threat detection, security alerts with context and remediation steps |

---

### Secure Score

**Secure Score** is a numerical measure of your overall security posture. The higher the score, the lower the risk. It increases as you implement Defender's recommendations.

---

### Key Features

| Feature | Description |
|---|---|
| **Recommendations** | Actionable best-practice guidance sorted by potential security impact |
| **Security Alerts** | Detects active threats and provides investigation and remediation steps |
| **Regulatory Compliance** | Measures compliance against standards (ISO, PCI DSS, GDPR, NIST, etc.) |
| **JIT VM Access** | Opens management ports (RDP, SSH) only when needed — reduces brute-force attack surface |
| **Hybrid Support** | Extend protection to on-premises servers via Azure Arc agents |
| **Multi-cloud Support** | Assess and protect AWS and GCP resources |

---

### Service Tiers

| Tier | Cost | Features |
|---|---|---|
| **Free** | Included by default | Continuous assessment + basic Secure Score recommendations |
| **Paid (Azure Defender)** | Per-resource cost | JIT VM Access, threat alerts, vulnerability scanning, compliance dashboards |

---

### Defense in Depth

**Defense in Depth** is a security strategy using **multiple layered controls** so that if one layer is breached, others remain in place. Azure's seven concentric layers (from outermost to innermost):

| Layer | What It Protects |
|---|---|
| **Physical** | Physical access to data centers |
| **Identity & Access** | Azure AD, MFA, RBAC |
| **Perimeter** | DDoS protection, Azure Firewall |
| **Network** | NSGs, VNet segmentation |
| **Compute** | VM security, patching, endpoint protection |
| **Application** | Secure code, no hardcoded secrets |
| **Data** | Encryption at rest and in transit |

---

### Zero Trust Model

**Zero Trust** is a security model based on three principles:
1. **Verify Explicitly** — always authenticate and authorize using all available signals
2. **Use Least Privilege Access** — limit user access to only what is needed
3. **Assume Breach** — minimize blast radius; verify end-to-end encryption; use analytics to detect threats

---

### Summary

| Concept | Key Point |
|---|---|
| **Defender for Cloud** | Unified security: assess, secure, and defend Azure (and hybrid/multi-cloud) resources |
| **Secure Score** | Numerical posture measure — higher = better; increases as recommendations are implemented |
| **JIT VM Access** | Opens ports only when needed — reduces attack surface |
| **Free Tier** | Continuous assessment + basic recommendations — included by default |
| **Paid Tier** | JIT, advanced threat alerts, vulnerability scanning, compliance dashboards |
| **Zero Trust** | Verify Explicitly, Least Privilege, Assume Breach |
| **Defense in Depth** | 7 layers: Physical, Identity, Perimeter, Network, Compute, Application, Data |

---

> ## Section 28 — Azure Key Vault

**Azure Key Vault** is a managed PaaS service for securely storing and managing sensitive application information: **encryption keys, application secrets, and SSL/TLS certificates**.

---

### What It Stores

| Item | Description |
|---|---|
| **Keys** | Encryption keys for encrypting/decrypting data (e.g., VM disk encryption) |
| **Secrets** | Sensitive configuration values (e.g., database passwords, API keys, connection strings) |
| **Certificates** | SSL/TLS certificates for securing web traffic and service-to-service authentication |

---

### Why Use Azure Key Vault

- **Prevent hardcoded secrets** — store credentials in Key Vault; applications retrieve them at runtime via the API
- **Centralize shared secrets** — if 10 services use the same password, store it once; all services retrieve from Key Vault; change it once and all services update immediately
- **Manage disk encryption** — store customer-managed keys for VM disk encryption
- **Certificate lifecycle management** — store, renew, and manage SSL certificates centrally

---

### Key Features

| Feature | Description |
|---|---|
| **HSM-backed storage** | Hardware Security Module for maximum key protection |
| **Versioning** | Every secret/key update creates a new version — full history maintained |
| **Expiration dates** | Set activation and expiration dates on secrets |
| **Access policies** | Fine-grained control over who/what can access keys, secrets, certificates |
| **Audit logging** | Full log of every access — who accessed what and when |
| **Azure integration** | Native connectors for VMs, App Service, Functions, Logic Apps, Data Factory |

---

### Summary

| Aspect | Detail |
|---|---|
| **Azure Key Vault** | Managed PaaS service for centralized, secure storage of keys, secrets, and certificates |
| **What Key Vault stores** | Encryption keys, application secrets, SSL/TLS certificates |
| **Key benefit** | Centralized, secure, audited storage — change a secret once, all services update |
| **Versioning** | Every change creates a new version — full history maintained |
| **Access control** | Fine-grained access policies per user, group, or application |
| **Audit logging** | Complete log of all access events |

> 📝 **Exam Tip:** Key Vault stores three things: **Keys** (encryption), **Secrets** (passwords/config), **Certificates** (SSL/TLS). The key benefit is **centralization** — one location for all sensitive data, accessed securely by all services.

---

> ## Section 29 — Azure Role-Based Access Control (RBAC)

**Azure RBAC** is Azure's authorization system built on top of Azure Resource Manager. It controls **who can do what on which Azure resources** — answering three questions:

| Question | Element |
|---|---|
| **What** can be done? | Role Definition |
| **Who** can do it? | Security Principal |
| **Where** can it be done? | Scope |

---

### 1. Role Definition (What)

A role definition is a **collection of permitted actions**. Azure has hundreds of built-in roles; organizations can also create custom roles.

| Built-in Role | Permissions |
|---|---|
| **Owner** | Full access — manage everything including access assignments |
| **Contributor** | Manage everything except access assignments |
| **Reader** | View resources only — no changes allowed |
| **User Access Administrator** | Manage user access to Azure resources only |

---

### 2. Security Principal (Who)

| Type | Description |
|---|---|
| **User** | Individual Azure AD user account |
| **Group** | Azure AD group — role applies to all members automatically |
| **Service Principal** | Application identity in Azure AD |
| **Managed Identity** | Azure-managed identity for services (e.g., a VM accessing Key Vault) |

Best practice: assign roles to **groups**, not individual users — when someone joins a team, add them to the group; no individual role assignments needed.

---

### 3. Scope (Where)

RBAC uses a hierarchical scope structure:
```
Management Group → Subscription → Resource Group → Resource
```

Roles assigned at a higher level are **automatically inherited** by all child scopes.

| Scope Level | Effect |
|---|---|
| **Management Group** | Role applies to all subscriptions, resource groups, and resources within |
| **Subscription** | Role applies to all resource groups and resources within |
| **Resource Group** | Role applies to all resources within the group |
| **Resource** | Role applies to that specific resource only |

---

### RBAC vs. Azure Policy

| Feature | RBAC | Azure Policy |
|---|---|---|
| **Controls** | User actions (who can act) | Resource properties (what can be created) |
| **Question answered** | Can this user create a resource? | Does this resource meet our standards? |
| **Enforcement** | Blocks unauthorized users | Blocks non-compliant configurations |

---

### Summary

| Concept | Key Point |
|---|---|
| **Role Definition** | Collection of permitted actions — defines what can be done |
| **Security Principal** | User, group, or application — defines who acts |
| **Scope** | MG → Subscription → Resource Group → Resource — defines where |
| **Role Assignment** | Combination of role + principal + scope |
| **Scope Inheritance** | Roles at higher scopes cascade down to all children |
| **Custom Roles** | Organization-defined roles for fine-grained permission control |
| **RBAC vs. Policy** | RBAC = who can act; Policy = what configuration is allowed |

> 📝 **Exam Tip:** RBAC controls **user permissions**; Azure Policy controls **resource configuration**. Both use the same scope hierarchy. Both can block actions but for different reasons.

---

> ## Section 30 — Azure Resource Tags

**Resource tags** are **key-value pairs** attached to Azure resources, resource groups, and subscriptions to add **custom metadata** for organization, automation, and cost tracking.

| Component | Example |
|---|---|
| **Tag Name (Key)** | `Department`, `Owner`, `Environment`, `CostCenter` |
| **Tag Value** | `Finance`, `adam@company.com`, `Production`, `327` |

---

### Why Use Tags

Resource groups organize by application or workload — but you can't easily cross-query them. Tags add a **second dimension of organization** that cuts across resource group boundaries.

**Common Use Cases:**

| Use Case | Example Tags |
|---|---|
| **Cost management / chargeback** | `CostCenter: 327`, `Department: Finance` |
| **Ownership** | `Owner: adam@company.com`, `Team: DevOps` |
| **Environment classification** | `Environment: Production`, `Environment: Dev` |
| **Automation** | `AutoShutdown: 22:00`, `BackupPolicy: Daily` |
| **Security / compliance** | `DataSensitivity: Restricted`, `Compliance: PCI` |

---

### Key Rules

| Rule | Detail |
|---|---|
| **Not inherited by default** | Tags on a resource group are NOT applied to resources inside it |
| **Multiple tags allowed** | Up to 50 tags per resource |
| **Applied to** | Resources, resource groups, and subscriptions |
| **Free** | No cost to use tags |
| **Case-sensitive values** | `Production` and `production` are different values |

> 📝 **Exam Tip:** The most important rule: tags are **NOT inherited by default**. To enforce tag inheritance, use **Azure Policy** (the "Inherit resource group tags" built-in policy).

---

### Summary

| Aspect | Detail |
|---|---|
| **Azure Resource Tags** | Key-value metadata pairs attached to Azure resources |
| **Inheritance** | Not inherited by default — enforce with Azure Policy |
| **Apply to** | Resources, resource groups, subscriptions |
| **Max tags** | 50 per resource |
| **Common uses** | Cost tracking, ownership, automation, environment classification |

---

> ## Section 31 — Azure Policy & Resource Locks

---

### Azure Policy

**Azure Policy** is an Azure governance service that defines and enforces rules about **the properties of Azure resources** — ensuring all resources comply with organizational standards.

While RBAC controls **who can act**, Azure Policy controls **what resources look like when created**.

**How It Works:**
```
Request → 1. Validation → 2. RBAC check → 3. Policy check → Deploy or Deny
```
If a resource fails the policy check, deployment is **denied** — even if the user has Owner-level permissions.

---

### Policy Effects

| Effect | Description |
|---|---|
| **Deny** | Blocks the deployment entirely |
| **Audit** | Allows deployment but flags the resource as non-compliant |
| **Append** | Adds additional properties to the resource during creation |
| **Modify** | Modifies resource properties during creation or update |
| **DeployIfNotExists** | Deploys a related resource if it doesn't already exist |

---

### Policy Initiatives

A **policy initiative** (policy set) is a **collection of policy definitions** grouped and assigned as a single unit.

| | Policy Definition | Policy Initiative |
|---|---|---|
| **Scope** | Single rule | Multiple rules bundled |
| **Use case** | Enforce one rule | Enforce a full compliance standard |

**Built-in initiative examples:** UK Official (59 policies), PCI DSS, Azure Security Benchmark.

---

### Policy Assignment & Scope

Policies must be assigned to a scope to take effect: Management Group, Subscription, Resource Group, or Resource. Policies assigned at a higher scope apply to all children. **Exclusions** can exempt specific child scopes.

**Remediation:** Policies only apply to new/modified resources by default. Create a **remediation task** to retroactively apply policies to existing non-compliant resources.

---

### Resource Locks

**Resource locks** prevent Azure resources from being **accidentally deleted or modified** — independently of RBAC permissions. Even a resource Owner must explicitly remove the lock first.

| Lock Type | Read | Modify | Delete |
|---|---|---|---|
| **Delete** | ✅ Yes | ✅ Yes | ❌ Blocked |
| **ReadOnly** | ✅ Yes | ❌ Blocked | ❌ Blocked |

Locks can be applied at the resource, resource group, or subscription level. Locks set at a parent scope are **inherited** by all child resources.

---

### Summary

| Concept | Key Point |
|---|---|
| **Policy Definition** | Evaluate a resource property → apply an effect (Deny, Audit, Append, etc.) |
| **Policy Initiative** | Bundle of multiple policy definitions assigned together |
| **Policy Assignment** | Attach a policy or initiative to a scope |
| **Scope Inheritance** | Policies at higher scopes apply to all children |
| **Remediation** | Retroactively apply policies to existing non-compliant resources |
| **Built-in Policies** | Allowed locations, allowed SKUs, require tags, inherit resource group tags |
| **Resource Locks** | Prevent accidental deletion/modification — overrides even Owner-level RBAC |
| **Delete Lock** | Can read and modify, but cannot delete |
| **ReadOnly Lock** | Can only read — no modifications or deletions |
| **Lock Inheritance** | Locks cascade down to all child resources |

> 📝 **Exam Tip:** RBAC controls **user permissions**. Azure Policy controls **resource configuration**. Resource Locks prevent **accidental changes/deletions**, overriding even Owner permissions.

---

> ## Section 32 — Azure Blueprints

**Azure Blueprints** packages resource groups, ARM templates, role assignments, and policy assignments into a single **versioned, repeatable environment definition** — allowing governance teams to deploy consistent, pre-approved environments across subscriptions.

---

### Key Concepts

#### Blueprint Definition
The reusable package containing **artifacts**:

| Artifact Type | Description |
|---|---|
| **Resource Groups** | Define the resource group(s) to be created |
| **ARM Templates** | Deploy Azure resources (VMs, storage, etc.) declaratively |
| **Role Assignments** | Grant specific roles to users, groups, or service principals |
| **Policy Assignments** | Apply Azure policies to enforce compliance |

Definitions support **parameters** (fill in at assignment time, e.g., region, resource group name).

#### Blueprint Assignment
The deployment of a definition to a specific scope (subscription or management group). Each assignment is a separate deployment; the definition can be assigned many times to different scopes.

#### Versioning
Definitions support draft → publish with a version number. Older versions remain available for tracking.

---

### Blueprints vs. ARM Templates vs. Azure Policy

| Feature | ARM Templates | Azure Policy | Azure Blueprints |
|---|---|---|---|
| **Deploys resources** | Yes | No | Yes (via ARM templates) |
| **Assigns roles** | No | No | Yes |
| **Assigns policies** | No | Yes | Yes |
| **Versioning** | Manual | No | Yes (built-in) |
| **Tracks deployment** | No | No | Yes |
| **Single package** | No | No | Yes |

---

### Summary

| Concept | Key Point |
|---|---|
| **Blueprint Definition** | Reusable package of artifacts — describes what to deploy |
| **Blueprint Assignment** | Deployment of a definition to a scope — describes where to deploy |
| **Artifacts** | Resource Groups, ARM Templates, Role Assignments, Policy Assignments |
| **Versioning** | Draft → publish with version number — full history maintained |
| **Purpose** | Consistent, repeatable, pre-approved environment deployments at scale |

> 📝 **Exam Tip:** Blueprints is the orchestrator — combines ARM, RBAC, and Policy into one versioned, trackable package. Unlike ARM templates alone, blueprints maintain a live connection between the definition and the deployed assignment.

---

> ## Section 33 — Cloud Adoption Framework for Azure

The **Cloud Adoption Framework (CAF)** is a set of tools, best practices, guidelines, and documentation from Microsoft to help organizations successfully adopt Azure.

---

### The CAF Lifecycle
```
Strategy → Plan → Ready → Adopt
                   ↕          ↕
               Govern ←→ Manage
                   ↕
                Organize
```

---

### Stage 1 — Strategy
**Goal:** Build organizational alignment and justify the move to the cloud.

- **Motivations:** Document migration triggers (cost savings, agility, compliance) and innovation triggers (new capabilities, digital transformation)
- **Business outcomes:** Define measurable goals (cost savings %, time-to-market, compliance achievements)
- **Business case:** Financial model including cloud costs, OpEx vs. CapEx comparison, and TCO

---

### Stage 2 — Plan
**Goal:** Create a concrete actionable cloud adoption plan.

- **Digital estate assessment:** Inventory all on-premises assets; determine what to migrate, modernize, or retire
- **Rationalization (5 Rs):**

| Option | Description |
|---|---|
| **Rehost** | Lift-and-shift — move as-is to IaaS |
| **Refactor** | Minor code changes to use PaaS |
| **Rearchitect** | Redesign application for the cloud |
| **Rebuild** | Rewrite from scratch using cloud-native services |
| **Replace** | Drop the existing app and use a SaaS alternative |

- **Adoption plan:** Skills readiness, gap analysis, timeline

---

### Stage 3 — Ready (Landing Zone)
**Goal:** Prepare the Azure environment for adoption.

A **Landing Zone** is a pre-configured Azure environment meeting security, governance, and operational requirements. Built using **CAF Landing Zone Accelerators** (ARM Templates and Blueprints).

---

### Stage 4 — Adopt
**Goal:** Execute the migration or innovation.

| Path | Focus |
|---|---|
| **Migrate** | Move existing workloads to Azure (rehost, refactor, rearchitect) using Azure Migrate |
| **Innovate** | Build new cloud-native solutions, leverage AI/ML, IoT, and modern architecture |

---

### Continuous Processes

| Process | Purpose |
|---|---|
| **Govern** | Establish governance policies; maintain Cost Management, Security, Identity, and Resource Consistency disciplines |
| **Manage** | Define operational baselines, monitor resources, automate operations |
| **Organize** | Align teams and responsibilities; define RACI for cloud adoption |

---

### Summary

| Stage/Process | Key Point |
|---|---|
| **Strategy** | Why move? Business outcomes, motivations, financial justification |
| **Plan** | What to move? Digital estate assessment, 5 Rs rationalization, adoption plan |
| **Ready** | Prepare Azure environment — Landing Zone with governance and security baselines |
| **Adopt (Migrate)** | Execute migration using Azure Migrate and the 5 Rs |
| **Adopt (Innovate)** | Build cloud-native solutions using Azure-specific services |
| **Govern** | Ongoing compliance, cost management, security, and resource governance |
| **Manage** | Operational monitoring, baseline management, and automation |

---

> ## Section 34 — Security, Privacy & Compliance

This section covers Microsoft's legal, compliance, and governance documents, sovereign cloud regions, data governance tools, and the compliance portal.

---

### Microsoft Compliance Documents

| Document | Purpose | Audience |
|---|---|---|
| **Privacy Statement** | How Microsoft collects and uses personal data across all products | Everyone |
| **Online Services Terms (OST)** | Legal licensing and usage rights for Microsoft online services | Legal teams |
| **Data Protection Addendum (DPA)** | Data processing and security obligations — appendix to the OST | Legal + security teams |
| **Trust Center** | One-stop overview of Microsoft security, privacy, and compliance | All organizational roles |
| **Azure Compliance Documentation** | Azure-specific compliance offerings and certifications | Azure-focused teams |

---

### Azure Sovereign Regions

Beyond standard public regions, Azure has **sovereign regions** — isolated instances meeting unique government or regulatory requirements.

#### Azure Government (United States)

| Aspect | Detail |
|---|---|
| **Designed for** | US government agencies and their partners |
| **Physical isolation** | Yes — isolated from public cloud regions |
| **Personnel access** | Only authorized and vetted US personnel |
| **Operated by** | Microsoft |

#### Azure China

| Aspect | Detail |
|---|---|
| **Designed for** | Chinese market — mainland China compliance requirements |
| **Operated by** | **21Vianet** — not Microsoft directly (required by Chinese law) |
| **Physical isolation** | Yes — isolated from public cloud |
| **Note** | Azure East Asia (Hong Kong) is part of the public cloud, not the sovereign China region |

> 📝 **Exam Tip:** The fact that Azure China is operated by **21Vianet** (not Microsoft) is a frequently tested detail. Azure Government = operated by Microsoft, US government only, physically isolated.

---

### Microsoft Purview

**Microsoft Purview** is a data governance, risk, and compliance suite providing a unified view of data across on-premises, multi-cloud, and SaaS environments.

| Solution Area | Description |
|---|---|
| **Risk and Compliance** | Protects sensitive data across Microsoft 365 services; supports GDPR, HIPAA compliance |
| **Unified Data Governance** | Maps, discovers, classifies, and governs data across Azure, on-prem, and other clouds (including AWS S3) |

| Tool | Focus |
|---|---|
| **Azure Policy** | Govern Azure resource configuration |
| **Microsoft Purview** | Govern data — discovery, classification, lineage, access |
| **Defender for Cloud** | Security posture and threat protection |

---

### Service Trust Portal

The **Microsoft Service Trust Portal** (`servicetrust.microsoft.com`) provides access to security, privacy, and compliance documentation — including audit reports, compliance certifications, and details on how Microsoft protects your data.

| Section | Content |
|---|---|
| **My Library** | Save/pin documents; set up update notifications |
| **All Documents** | Central library of audit reports, certifications, and compliance documents |

Documents remain available for at least **12 months** after publishing.

---

### Summary

| Resource / Concept | Key Point |
|---|---|
| **Privacy Statement** | Microsoft's data collection and usage practices — all products |
| **OST** | Legal licensing and usage rights for online services |
| **DPA** | Data processing and security obligations — appendix to the OST |
| **Trust Center** | One-stop overview of Microsoft security, privacy, and compliance |
| **Azure Compliance Documentation** | Azure-specific compliance — for Azure-focused teams |
| **Azure Government** | US sovereign region — operated by Microsoft; physically isolated; vetted US personnel |
| **Azure China** | Chinese sovereign region — operated by **21Vianet**, not Microsoft |
| **Microsoft Purview** | Data governance — discovery, classification, lineage, compliance across all data sources |
| **Service Trust Portal** | `servicetrust.microsoft.com` — download actual SOC reports, ISO certs, audit results |

---

> ## Section 35 — Cost-Affecting Factors

Understanding what drives Azure costs is essential for designing cost-effective solutions.

---

### 1. Resource Types

**What service you use and how you configure it** is the largest cost driver. Each service has its own billing metrics:

| Service | Billing Metrics |
|---|---|
| **Virtual Machine** | vCPU count × memory × uptime (per second) |
| **Azure SQL Database** | vCores + storage + uptime |
| **Azure Functions** | Number of executions × memory consumed |
| **Storage Account** | GB stored + access tier + number of operations |
| **Logic Apps** | Number of actions executed |
| **Resource Groups** | **Free** — organizational containers only |

> 📝 **Exam Tip:** Resource groups, management groups, and subscriptions are **free** — only actual services incur costs.

---

### 2. Services / Purchase Type

How you buy Azure affects your pricing rates:

| Offer Type | Description |
|---|---|
| **Pay-As-You-Go** | Monthly billing, standard rates, no commitment |
| **Enterprise Agreement (EA)** | Contract with Microsoft — negotiated discounts |
| **Cloud Solution Provider (CSP)** | Purchased through a Microsoft partner — partner sets pricing |
| **Azure Free Account** | Free credits for testing — limited services |
| **Visual Studio subscription** | Monthly Azure credits for developers |

---

### 3. Location (Azure Region)

The same service configuration costs different amounts in different regions — because data center operational costs vary by geography. Balance these factors when choosing a region:

1. Proximity to customers (latency)
2. Service availability
3. Price
4. Compliance requirements

---

### 4. Bandwidth (Ingress & Egress)

| Traffic Type | Direction | Cost |
|---|---|---|
| **Ingress** | Data flowing *into* Azure | **Usually free** |
| **Egress** | Data flowing *out of* Azure | **Charged** |

Moving data between Azure regions or continents incurs charges. Moving data within the same region is typically free.

---

### 5. Hidden Costs

- **Orphaned resources:** Deleting a VM does NOT automatically delete its attached disks, network interfaces, or public IPs — these continue billing
- **Azure Marketplace third-party solutions:** Dual billing — Azure infrastructure cost (Microsoft) + vendor software fee (vendor)

---

### Summary

| Factor | What Drives Cost | Key Detail |
|---|---|---|
| **Resource Type** | Service type and configuration | Each service bills differently (per second, per GB, per operation) |
| **Purchase Type** | EA, CSP, Pay-as-you-go | Negotiated rates can significantly lower costs |
| **Location** | Azure region | Same service costs differ by region |
| **Bandwidth** | Outbound data transfer | Ingress is usually free; egress is charged |
| **Orphaned Resources** | Leftover resources after deletion | Disks, NICs, public IPs continue billing after VM deletion |

---

> ## Section 36 — Cost Reduction Methods

Once you understand cost drivers, the next step is knowing how to **reduce** them.

---

### 1. Azure Reservations

By committing to use a service for **1 or 3 years**, you receive significant discounts vs. pay-as-you-go:

| Commitment | Example Monthly Cost | Discount |
|---|---|---|
| Pay-as-you-go | $50/month | 0% |
| 1-year reservation | $30/month | ~40% off |
| 3-year reservation | $20/month | ~60% off |

**What can be reserved:**

| Reservation Type | Applies To |
|---|---|
| **Reserved Instances** | Virtual Machine compute |
| **Reserved Capacity** | PaaS services — Azure SQL, Storage, Cosmos DB, Databricks |
| **Software Plans** | OS licensing — Red Hat, SUSE Linux |

Best for **stable, always-on workloads**. Reservations change the pricing model — they don't turn services on or off.

---

### 2. Azure Spot Virtual Machines

**Spot VMs** allow you to use Azure's unused compute capacity at a **steep discount** (up to 90% off pay-as-you-go). The tradeoff: Azure can reclaim the VM with **2 minutes' notice** when capacity is needed elsewhere.

**Best for:** batch jobs, background processing, dev/test — workloads that can tolerate interruption. **Not suitable for:** production web servers or any workload requiring continuous availability.

---

### 3. Azure Hybrid Use Benefit

If your organization owns **Windows Server or SQL Server licenses with Software Assurance**, you can reuse those licenses in Azure to avoid paying for new OS/SQL licenses.

| Scenario | Savings |
|---|---|
| Windows Server with existing license | Up to 40% savings on Windows VM costs |
| SQL Server with existing license | Up to 55% savings on Azure SQL |
| Combined (Windows + SQL) | Up to 80% savings on SQL workloads |

Activated per-VM during creation or post-deployment in the Azure Portal.

---

### 4. Azure Pricing Calculator

A free web tool for **estimating the cost of Azure services before deploying** them.

- Add services (VM, storage, SQL, etc.) with specific configurations
- View estimated monthly costs broken down per service and in total
- Export estimates to Excel or share via link for collaboration

---

### 5. Total Cost of Ownership (TCO) Calculator

A free tool for calculating the **financial benefit of migrating from on-premises to Azure**.

- Input your current on-premises infrastructure (servers, storage, networking, databases)
- Specify assumptions (power cost, IT labor cost, hardware refresh cycles)
- View the 5-year cost comparison between on-premises and Azure
- Results show total savings and cost breakdown

**Pricing Calculator vs. TCO Calculator:**

| Calculator | Purpose |
|---|---|
| **Pricing Calculator** | Estimate the cost of *specific Azure services* for a new deployment |
| **TCO Calculator** | Compare on-premises costs vs. Azure to justify a *migration* |

---

### Summary

| Method | Description | Savings Potential |
|---|---|---|
| **Reservations** | 1 or 3 year commitment for predictable workloads | Up to 60–72% |
| **Spot VMs** | Use unused Azure capacity at discount — interruptible | Up to 90% |
| **Azure Hybrid Use Benefit** | Reuse existing Windows/SQL Server licenses in Azure | Up to 80% |
| **Pricing Calculator** | Estimate costs before deploying | Cost visibility |
| **TCO Calculator** | Justify migration by comparing on-prem vs. Azure costs | Migration justification |

---

> ## Section 37 — Azure Cost Management

**Azure Cost Management** is a free service inside the Azure Portal for **monitoring, analyzing, and controlling your Azure spending**.

---

### Core Features

| Feature | Description |
|---|---|
| **Cost Analysis** | Visualize spending by time period, service, resource group, or tag |
| **Budgets** | Set spending thresholds — receive alerts when costs approach or exceed the limit |
| **Recommendations** | Integrated with Azure Advisor — highlights optimization opportunities |
| **Export** | Export billing data to Azure Storage for custom reporting |

---

### Budgets & Alerts

Create a **Budget** by:
1. Setting a spending limit (e.g., $500/month)
2. Defining alert thresholds (e.g., notify at 80%, 100%, 120%)
3. Configuring alert recipients (email addresses or action groups)

> Budgets **do not stop spending** — they only alert. To stop spending, you must manually delete or stop the resources.

---

### Cost Management + Billing Integration

Cost Management integrates with **Azure Billing** to provide:
- Invoice history and download
- Payment method management
- Subscription cost breakdown

---

### Summary

| Feature | Purpose |
|---|---|
| **Cost Analysis** | Visualize and analyze spending patterns by resource, time, tag, or service |
| **Budgets** | Set spending thresholds and receive proactive alerts |
| **Recommendations** | Advisor-powered cost optimization suggestions |
| **Export** | Send billing data to storage for custom analysis |

> 📝 **Exam Tip:** Azure Cost Management is **free**. Budgets **alert** on spending thresholds — they do not stop or block spending. Use tags to enable granular cost breakdown by department, application, or environment.

---

> ## Section 38 — SLA & Composite SLA

---

### What is an SLA?

A **Service Level Agreement (SLA)** is Microsoft's formal commitment to the availability of a specific Azure service, expressed as a percentage per month. If Microsoft fails to meet the SLA target, customers receive a **service credit** (a discount on their bill).

---

### Common Azure SLA Values

| SLA | Monthly Downtime |
|---|---|
| **99.9%** (three nines) | ~43 min 49 sec |
| **99.95%** | ~21 min 54 sec |
| **99.99%** (four nines) | ~4 min 22 sec |

**Services with no SLA:**
- **Free tier** services
- **Public Preview** services

---

### What Affects Your SLA

| Action | Effect on SLA |
|---|---|
| Use free or preview services | Decreases (no SLA guarantee) |
| Add more services in sequence | Decreases (AND logic) |
| Use lower service tiers | Decreases |
| Add redundancy (load balancer + multiple instances) | Increases |
| Deploy zone-redundant configurations | Increases |
| Use higher service tiers | Increases |

---

### Composite SLA

When your solution uses **multiple services**, the overall availability is a **Composite SLA** — calculated by combining individual SLAs.

#### AND Logic (Services in Sequence)
Both services must work for the application to function — multiply their SLAs:
```
Composite SLA = SLA₁ × SLA₂ × SLA₃ ...
```
**Result: always lower than any individual component.**

Example: App Service (99.95%) + SQL Database (99.99%)
```
0.9995 × 0.9999 = 0.9994 ≈ 99.94%
```

#### OR Logic (Redundant Services)
Either service can handle the request — multiply the *unavailabilities* then subtract from 1:
```
Composite SLA = 1 - (1 - SLA₁) × (1 - SLA₂)
```
**Result: always higher than any individual component — redundancy improves availability.**

Example: Two App Service instances, each 99.95%
```
1 - (0.0005 × 0.0005) = 1 - 0.00000025 ≈ 99.9999%
```

---

### Summary

| Concept | Key Point |
|---|---|
| **SLA** | Microsoft's formal availability promise per service per month |
| **99.9%** | ~43 min 49 sec downtime/month |
| **99.95%** | ~21 min 54 sec downtime/month |
| **99.99%** | ~4 min 22 sec downtime/month |
| **Service Credit** | Discount on your bill if Microsoft misses the SLA target |
| **Free / Preview services** | No SLA — not suitable for production |
| **Composite SLA (AND)** | Multiply all SLAs — result is **lower** than any single component |
| **Composite SLA (OR)** | Multiply *unavailabilities*, subtract from 1 — redundancy **improves** SLA |
| **AND formula** | SLA₁ × SLA₂ × SLA₃ ... |
| **OR formula** | 1 - (1 - SLA₁) × (1 - SLA₂) |

> 📝 **Exam Tip:** AND logic (services in sequence) lowers composite SLA. OR logic (redundancy via load balancer) dramatically improves composite SLA. Know both formulas and when each applies.

---

> ## Section 39 — Service Lifecycle: Preview & GA

Every Azure service follows a defined **release lifecycle** before becoming production-ready.

---

### The Lifecycle Stages
```
Internal Development → Private Preview → Public Preview → General Availability (GA)
```

---

### Stage 1: Private Preview
- Released to a **narrow, selected audience** (high-profile customers, Microsoft MVPs, Microsoft employees)
- Covered by an **NDA (Non-Disclosure Agreement)**
- Goal: prove value and test before a wider release
- Not accessible to the general public

---

### Stage 2: Public Preview (Beta)
- Released to **all Azure customers** for testing and feedback
- Goal: gather real-world feedback, validate functionality, and refine pricing

**Key limitations of Public Preview:**

| Limitation | Detail |
|---|---|
| **No SLA** | Preview services are excluded from SLAs |
| **Limited support** | Microsoft may not provide full customer support |
| **Limited regions** | Often released to a subset of Azure regions |
| **Different pricing** | Often discounted or different from final GA pricing |
| **May be cancelled** | Microsoft can change direction or cancel a preview feature |

---

### Stage 3: General Availability (GA)
The **production-ready, fully supported release**:
- Full SLA applies
- Full customer support available
- Available in all applicable Azure regions
- Pricing is finalized

> **Important:** A GA service can still have **individual features in Public Preview**. Always check whether the specific feature you're using is GA or preview.

---

### How to Stay Up to Date

| Resource | Purpose |
|---|---|
| **Azure Updates Portal** | `azure.microsoft.com/updates` — filter by category or update type; subscribe via RSS |
| **Azure Preview Portal** | `preview.portal.azure.com` — access upcoming portal features before GA |
| **In-Portal Feedback** | Smiley face button — Microsoft actively reads and uses submitted feedback |

---

### Summary

| Stage / Concept | Key Point |
|---|---|
| **Private Preview** | Selected customers + NDA; not public; not for production |
| **Public Preview** | All Azure customers; no SLA; limited support; may be cancelled |
| **General Availability (GA)** | Full SLA; full support; all regions; finalized pricing; production-ready |
| **GA service with Preview features** | A GA service can still have individual features in Public Preview |
| **Azure Updates Portal** | `azure.microsoft.com/updates` — track what's in preview vs. GA; subscribe via RSS |
| **Azure Preview Portal** | `preview.portal.azure.com` — upcoming portal features before GA |

> 📝 **Exam Tip:** Public Preview = **no SLA, no guaranteed support, not for production**. GA = **full SLA, full support, production-ready**. Individual features of a GA service can still be in Preview — always check at the feature level.

---

## Exam Domain Coverage

| Domain | Sections |
|---|---|
| **Cloud Concepts** | 1–7 (Cloud computing, CapEx/OpEx, service models, deployment models) |
| **Core Azure Services** | 8–19 (Regions, compute, networking, storage, databases, IoT, AI, DevOps, tools) |
| **Security, Privacy & Compliance** | 20–28 (NSG, firewall, DDoS, identity, Defender, Key Vault) |
| **Azure Governance** | 29–34 (RBAC, Tags, Policy, Blueprints, CAF, compliance documents) |
| **Pricing & Support** | 35–39 (Cost factors, reduction methods, Cost Management, SLA, service lifecycle) |

---

