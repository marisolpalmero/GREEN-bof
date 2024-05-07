** Birds of a Feather WG Creation Proposal ** 


**Title:**  

Green Metrics BoF 


**Background and Problem Statement:** 


The IT industry is facing the intertwined challenges of improving energy efficiency and embracing sustainable practices. Organizations are seeking to align energy management with circular economy principles, extending the lifecycle of network devices through improved design strategies that enhance modularity, repairability, and upgradeability. 


The first step in addressing these energy management challenges is in measuring, collecting and aggregating metrics to quantify the energy impact of Internet technologies in deployed networks.  While there have been ongoing attempts to generate and collect sustainability related metrics, these metrics have not been standardized and vary widely between different networks and operators. This makes it very difficult to have a consistent view of the metrics in a multi-vendor and/or multi-operator environment. Also, even when the metrics are for similar items the definitions of the metrics and the collection methodologies vary widely across the industry. This leads to inconsistent, redundant, and possibly contradictory metrics. Hence there is a need for consistent and standardized metrics with precise definitions that are commonly used across networks. 

While this standardized set of sustainability and energy management metrics is being developed there will be a period where a large fraction of deployed equipment in the field will be incapable of supporting these standardized metrics and there needs to be a framework to normalize these legacy metrics (either from dynamic or static data) to conform to the new standard metrics to support incremental deployment of these new metrics and mechanisms.  


The proposed GREEN metrics WG aims to address these challenges by: 

- Developing standardized power metrics and control mechanisms reflecting the latest energy management techniques and enabling adaptive energy usage optimization. 

- Introducing sustainability metrics based on circular design principles to reduce resource consumption, waste, and environmental footprint throughout the network device lifecycle. 

- Creating YANG data models that encompass operational energy efficiency and complete metrics for lifecycle assessment (LCA – ISO 14040:44), allowing network devices to support circular economy strategies, including material recovery and end-of-life management. 

   

The GREEN metrics WG will concentrate on short-term deliverables such as: 

- Establishing energy-related terminology, definitions, and architectural frameworks, referencing existing published sources where possible. 

- Reporting energy usage and sustainability metrics at the device and network layers through operational YANG models. 

- Providing configuration or YANG RPCs to influence and optimize energy usage in network devices. 

  

By integrating energy management with sustainable and circular economy practices, the GREEN WG will foster the development of innovative network management systems. These systems will not only enhance energy efficiency but also contribute to the longevity and responsible use of network devices, aligning with global sustainability efforts.  

Long-term goals related to broader energy efficiency and green networking initiatives will initially be considered out of scope and should be addressed outside the WG, e.g., within a new or existing research group or within the E-Impact IAB program.  

Areas that will not be considered as part of the short-term initial approach of the working group: 

- Interdomian, outside of the operators control  

- Work related in other SDOs WG, to avoid any overlap, i.e. ITU WG5 

- Energy aware routing protocol 

- Regulatory Reporting and Compliance 

  


The GREEN WG will aim to develop standards and guidelines that: 

- will concentrate on a comprehensive examination of network components and devices, focusing on energy-related attributes such as "idle" power, and advocating for eco-design to enhance sustainability. This includes setting and adhering to precise metrics that measure impact, establish baselines, and define targets for energy efficiency and sustainability. 

- Prioritizing a solution-based approach, the WG will be dedicated to implementing practical and operational methods that favor action over mere measurement, ensuring that strategies for energy optimization are actionable, with a framework that supports both YANG-capable and non-YANG-capable devices through controller-level management and data aggregation. 

- The group will standardize terminology to differentiate between energy efficiency and sustainability, ensuring a unified understanding within the IETF. It will also focus on the operational integration of these concepts, supported by a collection of use cases that demonstrate the application of energy-aware and sustainable practices in network infrastructure within the IETF scope and not overlaping with other SDO work, 

 

**Milestones:** 


- Develop and agree upon a standardized set of terminologies and definitions related to energy and sustainability in networking (Q4 2024). 

- Propose and ratify an architectural framework for energy and sustainability reporting (Q1 2025). 

- Draft and publish YANG models for operational energy efficiency and lifecycle assessment reporting (Q2 2025). 

- Demonstrate initial implementations and use cases of the YANG models in network devices (Q4 2025). 


**Collaborations:** 

  
The GREEN WG will actively work in collaboration with: 


- Related IETF WGs, such as the IVY and OPSA WG, to build upon existing work. 

- Other standards organizations focused on sustainability, such as the International Organization for Standardization (ISO) and ITU. 

- Industry stakeholders and regulatory bodies to ensure alignment with current and future regulatory frameworks. 

- The IAB eimpact program to identify and receive short term metrics related work and to propose longer term problems for further study. 

- WGs that might have related work or expertise with defining and standardizing metrics and measurement frameworks (e.g., IPPM and BMWG). 
