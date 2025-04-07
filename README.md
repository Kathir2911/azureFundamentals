
# Azure Fundamentals Guide

## Introduction to Cloud Computing

Cloud computing is the delivery of computing services over the internet. These services include:
- Common IT infrastructure (virtual machines, storage, databases, networking)
- Advanced services (IoT, machine learning, artificial intelligence)

Unlike traditional datacenters, cloud computing isn't constrained by physical infrastructure, allowing for rapid expansion of IT capabilities when needed.

## Shared Responsibility Model

The responsibility for security and management is shared between the cloud provider and the consumer:

**Cloud Provider is Always Responsible For:**
- Physical datacenter
- Physical network
- Physical hosts

**Customer is Always Responsible For:**
- Information and data stored in the cloud
- Devices allowed to connect to your cloud
- Accounts and identities of people, services, and devices

**Responsibility Based on Service Model:**
- Operating systems
- Network controls
- Applications
- Identity and infrastructure

## Cloud Models

### Private Cloud
A private cloud delivers IT services over the internet for a single entity. It provides greater control but comes with higher costs and fewer benefits compared to public cloud. It may be hosted:
- In your on-site datacenter
- In a dedicated offsite datacenter (potentially by a third party)

### Public Cloud
Built, controlled, and maintained by a third-party cloud provider. Anyone can purchase and access resources. The general public availability is the key difference from private clouds.

### Hybrid Cloud
A computing environment using both public and private clouds in an interconnected way. Benefits include:
- Handling increased temporary demand by deploying public cloud resources
- Providing additional security layers
- Flexibility in choosing which services to keep in public vs private cloud

### Multi-cloud
Using multiple public cloud providers simultaneously. This might occur when:
- Using different features from different providers
- Migrating from one provider to another

**Example: Hybrid Multi-Cloud for Enterprises**
A large enterprise combining multiple cloud platforms:
- AWS: Hosting main application backend
- Azure: Used for Microsoft-based workloads (Active Directory, Office 365)
- Google Cloud: Handling AI/ML workloads with TensorFlow and BigQuery

**Benefit:** Avoid vendor lock-in and optimize cloud resources

### Azure Arc and VMware Solutions
- **Azure Arc:** A set of technologies that helps manage your cloud environment across public, private, hybrid, or multi-cloud configurations
- **Azure VMware Solution (AVS):** Provides a seamless way to run VMware workloads in Microsoft Azure without significant changes

## Cloud Economics: CapEx vs OpEx

### Capital Expenditure (CapEx)
One-time, up-front expenditure to purchase or secure tangible resources (e.g., new building, datacenter, company vehicle)

### Operational Expenditure (OpEx)
Spending money on services or products over time (e.g., renting convention center, leasing vehicles, cloud services)

**Cloud computing uses a consumption-based OpEx model with benefits:**
- No upfront costs
- No need to purchase and manage potentially underutilized infrastructure
- Pay for more resources only when needed
- Stop paying for resources when no longer needed

## Key Cloud Concepts

### Service Level Agreements (SLA)
A formal agreement between a customer and service provider guaranteeing stated services. Azure SLAs are represented as percentages, with service availability measured as uptime.

### Scalability
The ability to adjust resources to meet demand, ensuring you're not overpaying for unused services.

**Types of Scaling:**
- **Vertical Scaling:** Increasing or decreasing the capabilities of resources (adding CPU/RAM)
- **Horizontal Scaling:** Adding or removing number of resources (like VMs or containers)

### Reliability
The ability of a system to recover from failures and continue functioning. The cloud's decentralized design naturally supports reliable and recoverable infrastructure.

### Predictability

**Performance Predictability:**
Focuses on predicting resources needed for positive customer experiences, using:
- Autoscaling
- Load balancing
- High availability

**Cost Predictability:**
Focuses on forecasting cloud spending using tools like Total Cost of Ownership (TCO) calculator or Pricing Calculator.

### Governance
Ensuring cloud resources follow company policies and regulatory rules:
- Templates for consistency
- Automatic updates to standards
- Auditing & compliance monitoring
- Mitigation strategies

**Benefits of early governance:**
- Secure cloud environment
- Compliance with regulations
- Automated software updates
- Reduced security risks and downtime

### Management
Methods for managing cloud resources:
- Web portal
- Command line interface
- APIs
- PowerShell

**Cloud management capabilities:**
- Automatic scaling based on need
- Template-based resource deployment
- Resource health monitoring
- Automatic alerts based on metrics

## Cloud Service Types

### Infrastructure as a Service (IaaS)
The most flexible cloud service category with maximum control. The provider maintains hardware, network connectivity, and physical security.

**Common Use Cases:**
- Lift-and-shift migration
- Testing and development environments

### Platform as a Service (PaaS)
Middle ground between IaaS and SaaS. The provider maintains physical infrastructure, internet access, operating systems, databases, and development tools.

**Common Use Cases:**
- Development frameworks
- Analytics and business intelligence

### Software as a Service (SaaS)
The most complete cloud service model. You rent or use fully developed applications with minimal technical expertise required.

**Common Use Cases:**
- Email and messaging
- Business productivity applications
- Finance and expense tracking

### Reference from Microsoft Learn and chatgpt
