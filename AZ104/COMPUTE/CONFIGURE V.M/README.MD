# Configure Virtual Machines

## Topics Covered
This module covers the following key areas related to configuring virtual machines (VMs) in Azure:

- **VM Name and Location**: Selecting appropriate naming conventions and regions for your VM.
- **VM Sizing**: Choosing the right size based on workload requirements.
- **Storage Options**: Configuring storage types, including OS disks and data disks.
- **VM Creation Methods**: Various ways to create VMs (Azure portal, CLI, PowerShell, etc.).
- **Connecting to VMs**: Exploring different connection methods like RDP and SSH.

---

## 1. Cloud Service Responsibilities
Virtual Machines (VMs) in Azure provide more control compared to other services. As a part of **Infrastructure as a Service (IaaS)**, VMs give cloud administrators control over the operating system, storage, and networking, while Azure manages the underlying infrastructure (hardware, networking, and virtualization).

In contrast to other cloud services like Platform as a Service (PaaS), where more of the system is managed by the cloud provider, VMs allow for greater customization and management by the administrator.

---

## 2. Why Use Virtual Machines?
Some of the key benefits of choosing Azure Virtual Machines include:

- **Scalability**: Easily scale up or down to meet demand.
- **Cost-Effective Hosting**: Suitable for workloads with varying demands, helping reduce costs.
- **Handling Unpredicted Demand**: VMs can efficiently handle spikes in resource usage.
- **Disaster Recovery**: VMs offer options for quick system recovery in case of failures.
- **High-Performance Computing**: Ideal for tasks like big data processing or applications requiring high computational power.
- **On-Premises Extension**: If on-premises storage or computing power needs to be extended, VMs can quickly be added.

---

## 3. Steps Involved in Creating a Virtual Machine
When creating a VM, it's important to plan the following:

- **Location**: Choose the appropriate region for your VM to optimize performance and meet regulatory requirements.
- **Sizing**: Select a VM size based on the expected workload (memory, CPU, and storage).
- **Storage**: Choose between standard HDD, premium SSD, or other options depending on performance needs.
- **Budget**: Evaluate costs to ensure the VM fits within your budget.
- **Configuration**: Detailed configuration settings for each parameter are explained in this section.

---

## 4. Sizing of a Virtual Machine
VMs come in various sizes, and choosing the correct size is crucial for performance and cost management. Factors include:

- **Workload Requirements**: CPU, memory, and disk needs based on the application or service.
- **Scaling Options**: Consider if the workload will need to scale dynamically or remain stable over time.

---

## 5. Storage for Virtual Machines
When configuring storage for a VM, consider the following options:

- **OS Disk**: Stores the operating system and is mandatory for every VM.
- **Temporary Disk**: Provides temporary storage (used for swapping) and is not persistent.
- **Managed Disks**: For data storage, offering better performance and reliability.

---

## 6. Creating a Virtual Machine
The process of creating a VM includes:

- **Selecting an Image**: Choose an OS image (Windows, Linux, etc.) from the Azure Marketplace or upload a custom image.
- **Filling Configuration Details**: Specify the VM’s name, region, size, storage options, networking, and security configurations.

---

## 7. Connecting to a Virtual Machine
VMs can be accessed using the following methods:

- **RDP (Remote Desktop Protocol)**: For Windows-based VMs.
- **SSH (Secure Shell)**: For Linux-based VMs.
- **Azure Bastion**: Provides secure and seamless RDP/SSH connectivity without exposing the VM’s public IP.

---

## 8. Cost Optimization for Virtual Machines
To reduce costs, consider the following strategies:

- **Appropriate Storage**: Choose cost-effective storage options that meet performance needs.
- **Azure Spot Instances**: Use spot pricing for non-critical workloads to save on costs.
- **Existing Licenses**: Apply existing Windows licenses to avoid extra charges.
- **Auto Shutdown**: Configure automatic shutdown for inactive VMs to save on usage costs.

---
