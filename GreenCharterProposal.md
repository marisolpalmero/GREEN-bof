Charter proposal for Get Ready Energy Efficiency Network (GREEN)

**Background and Motivation**

Energy efficiency gains for communication systems are highly sought after, for environmental, business, and technical reasons. Network operators are seeking for tools and solutions to better assess and control the energy consumption of links, devices, and devices/components across their networks. That trend influences also Standards Development Organizations (SDOs) in the information technology field, e.g., work on energy efficiency metrics and various technology improvements.

Network energy-efficiency management involves deploying and managing network infrastructures with the goal of
optimizing energy use on network devices while improving the overall network utilization. This includes adopting technologies to monitor and effectively manage energy consumption, evaluating the effectiveness of energy-saving policies beyond
simply reducing consumption, implementing control strategies that enhance overall energy efficiency in network operations.

RFC 6988 provides a set of requirements and guidelines for monitoring and managing power usage of devices within, or connected to, networks such as Power over Ethernet (PoE) switches. The GREEN Working Group will examine that work with a view to re-using it where possible, and developing new requirements (e.g., related to static device capabilities and energy efficiency metrics) for operator-managed network devices according to current use cases and applications. More recently, RFC 9547 highlighted the need of further work on metrics, measurements, ability to slow down and sleep devices or part of them, etc. However, there is no consistent view within the industry for terminologies to categorize various type of metrics and measurements.

In addition, the absence of standardized interfaces for measuring, reporting, and controlling energy consumption across diverse network setups remains a significant challenge. Therefore, new data models, metrics, and methods are required to optimize energy efficiency across the network. The EMAN WG specified a set of relevant MIBs in this area, but YANG models are now the rule (see also [1]).

As models and metrics are developed, standardized, and implemented in production networks, it will take many years before nearly all equipment in the field supports the new models and metrics. Therefore it will be necessary to map legacy metrics to the new models and allow a wide variety of collection mechanisms. Specifically, even though the collection process itself is modeled in YANG, devices cannot generally be assumed to have the data which is to be collected available in any YANG-based management interface.

**Goals and Scope**

The GREEN WG is chartered to concentrate on the following short-term deliverables:

   - Defining terms and definitions related to energy metrics. Where possible, terms and definitions in existing RFCs will be reused.
   - Developing YANG models to enable controling, monitoring and reporting of energy usage through metrics and attributes at component, device, and network levels.
   - Providing YANG models to control and optimize energy usage in network devices, and across the network, including energy saving capabilities. 
   - Documenting both the energy consumption metrics and their associated YANG data models, along with guidance on how to use and interpret them.
   - Developing or selecting a framework to collect, aggregate, and consume the above mentioned metrics and attributes developed in the WG from existing and new devices of almost every kind.

It may be complex and time-consuming to attempt to address all issues related to power consumption and energy efficiency 
in a single step. It can be practical to define building blocks that enhance both static device capabilities (related to 
inventory attributes) and dynamic energy efficiency metrics contributing to the network device operational lifecycle. 
The GREEN WG will provide tools that will serve as a foundation for new energy efficiency strategies. To ensure the 
effectiveness and alignment of these efforts, the GREEN Working Group will closely coordinate with the IVY Working 
Group for inventory related extensions.

**Out of Scope**

To stay focused, the Working Group will not address energy-related issues in every networking area. Some topics are already be covered in other venues while others may not be mature enough or present major shortcomings (e.g., have well-documented but unresolved security threats). The following topics are not within the scope of the Working Group:

   - Routing protocols and algorithms, including those that consider energy factors.
   - Benchmarking methodology for power consumption in networking devices.
   - The carbon accounting and reporting protocol to measure, manage, and report their greenhouse gas emissions and other 
     sustainability-related data. 
   - Methodologies for asessing environmental sustainability and related performance for the network devices.
   - Methodologies for understanding the impact of energy efficiency optimization on service quality.
   - Regulatory, compliance, and corporate responsibility related matters.

**Work Items**

The GREEN Working Group will focus on the following program of work:

- An Informational document defining Use cases for identifying energy efficiency metrics, methods related to energy consumption of the networking devices, to optimize energy efficiency across the network. The 
  document will describe 2-3 scenarios and for each of them, it will identify key points needed for interoperability.

- An Informational Architecture document that defines common terminology and metric definitions,categorizes various type of metrics and measurements at component level,device level and network level, defines a set 
  of architectural components for energy efficiency network management.

- A Proposed Standard document that defines YANG data models for energy efficiency network lifecycle management including energy usage monitoring, energy saving capability control and energy usage optimization

- An Informational document defining Framework for Energy metrics collection and aggregation to support incremental deployment of new energy efficiency metrics. 

**Dependencies and Liaisons**

The GREEN Working Group will closely collaborate with:

   - Other IETF Working Groups that address topics related to power consumption observability and energy efficiency
     management, such as IVY, OPSAWG, and NETMOD.
   - Working Groups that might have related work or expertise with defining and standardizing metrics and measurement 
     frameworks (e.g., IPPM and BMWG). 
   - Other IRTF Research Groups that provide research inputs and reviews, including PANRG, NMRG.
   - The IAB e-impact program to identify and receive short term metrics related work and to propose longer term problems 
     for further study.
     
Collaboration with Industry stakeholders and regulatory bodies to ensure alignment with current and future regulatory 
framework is encouraged. The GREEN Working Groups will also liaise with other SDOs on benchmarking methodologies for collaboration and consultation, mainly:

   - The European Telecommunications Standards Institute (ETSI), particularly with regard to the Technical
     Committee of Environment Engineering (TCEE).
   - The International Telecommunication Union (ITU), particularly with regard to ITU-T-SG-5.

**Milestones:** 

   - Develop and agree upon a standardized set of terminologies and definitions related to energy use and efficiency in 
     networking (Q4 2024).
   - Publish YANG models for operational energy use and efficiency related metrics that might be leveraged in other work to 
     improve energy efficiency within a network. (Q2 2025)
   - Develop a framework for incremental deployment of an energy-aware tools management (Q3 2025).
   - Demonstrate initial implementations and use cases of the YANG models in network devices (Q4 2025). 

[1] https://datatracker.ietf.org/doc/statement-iesg-writable-mib-module-iesg-statement-20140302/ 
