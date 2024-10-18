# Configure Virtual Machine Availability

## Topics Covered
This module explores the key concepts required to ensure high availability for virtual machines in Azure, including:

- **Availability Sets**: A strategy to group VMs into update domains and fault domains to improve redundancy. By placing VMs in different fault domains, Azure can protect workloads from failures at the hardware level.
  
---

## 1. Availability Sets
An Availability Set ensures that VMs are distributed across multiple **Update Domains** (for handling planned maintenance) and **Fault Domains** (for unplanned outages). This helps protect against hardware and data center failures.

- **Update Domains**: Prevent all VMs in an application from being updated simultaneously during Azure's maintenance cycles.
- **Fault Domains**: Ensure that VMs run on different physical hardware to minimize the impact of server or rack failures.

---

## 2. Availability Zones
Azure’s **Availability Zones** provide a higher level of resilience by distributing VMs across multiple physical data centers within a region. Each zone has independent power, cooling, and networking. If one zone goes down, others remain operational.

- Ideal for mission-critical applications requiring the highest availability.
- Azure provides a **99.99% SLA** for VMs deployed in Availability Zones.

---

## 3. Scaling Virtual Machines
There are two types of scaling:

- **Vertical Scaling**: Increasing the resources (CPU, memory) of an individual VM. This is useful for scaling up a specific application.
- **Horizontal Scaling**: Adding more VMs to handle increased traffic or demand. This is a more flexible and cost-effective method.

---

## 4. Azure Virtual Machine Scale Sets
**Azure VM Scale Sets** allow you to create and manage a group of identical, load-balanced VMs. You can define rules to automatically increase or decrease the number of instances based on demand.

- Perfect for auto-scaling based on CPU usage or memory thresholds.
- Enables seamless scaling of stateless applications across multiple instances.

---

## 5. Autoscaling
Autoscaling is the automatic adjustment of VM instances in response to resource usage patterns. You can set rules to:

- Increase VM instances during high demand.
- Reduce instances during low usage, saving costs.

Autoscaling ensures optimal resource utilization and cost efficiency without manual intervention.

---

## 6. Cost Considerations
When designing for availability, there are costs associated with redundancy. To optimize cost:

- Use **Azure Spot VMs** for non-critical workloads to take advantage of unused capacity at a lower price.
- Consider the balance between high availability and the budget, especially for VMs in Availability Zones or Scale Sets.

---

For more details, refer to the full module [here](https://learn.microsoft.com/en-gb/training/modules/configure-virtual-machine-availability/).

