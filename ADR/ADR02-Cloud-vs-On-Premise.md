
# ADR 2 : Cloud Hosting

## Status  

Accepted

## Rationale 

#### On-Premise Hosting
Advantages:
Data Control: Full control over the physical storage and handling of data, which could be crucial for businesses with stringent compliance or data sovereignty requirements.

Customization: On-premise solutions can be customized to meet the specific needs of the organization, down to the hardware level.

No Vendor Lock-in: Reduced dependency on vendor pricing models and migration concerns.

Network Latency: In-house network access can be faster as there are no hops over the public internet.

Disadvantages:
Initial Cost: Higher upfront costs for hardware, facility, and personnel.

Maintenance: Requires a dedicated IT team for maintenance, updates, and handling outages.

Scalability: Scaling hardware typically involves downtime and is often more complicated compared to cloud scaling.

Tech Stack Outdated: Hardware can become outdated and requires periodic reinvestment.

### Cloud Hosting 
Advantages:
Speed: Faster deployment and development cycle, aiding quicker time-to-market for products.

Operational Costs: Low initial costs and a pay-as-you-go model can make this more financially flexible.

Scalability: Easy to scale resources up or down as needed, often without any downtime.

Maintenance: Handled by the vendor, reducing the burden on internal IT staff.

Disadvantages:
Data Control: Less control over data storage and potential for compliance issues.

Vendor Lock-in: Migration to a different cloud provider can be complicated and costly.

Ongoing Costs: Though initially cheaper, costs can mount over time, especially if usage surges unexpectedly.

Latency: Potential for latency issues, especially if data centers are located far from end-users.
### Decision:
Given our startup's need for speed-to-market, flexibility, and scalability, we have opted for cloud-based hosting.

### Consequences:
 #### Positive:
  Operational Efficiency: With reduced need for in-house IT staff for maintenance, existing resources can focus on core business functions.

+ Budget Impact: The pay-as-you-go model will help manage costs, but budgeting will need to include potential for scaling costs.

+ Compliance: We'll need to ensure that our cloud provider meets the required compliance standards for data handling and storage.

+ Vendor Management: The choice ties us to a vendor, requiring ongoing management of that relationship.

+ Network Latency: We may need to consider using a Content Delivery Network (CDN) or similar services to mitigate potential latency issues.

By making this decision, we are embracing flexibility and speed, but it requires us to manage new kinds of risks including data compliance and vendor reliance. The architecture team should remain vigilant in monitoring the impacts of this decision on our operational effectiveness and costs.
