Charter proposal for Get Ready for Energy Efficient Networking (GREEN) Working Group

**Background and Motivation**

Energy efficiency gains for communication systems are highly sought after, for environmental, business, and technical reasons. Network operators seek tools and solutions to understand and control the energy consumption of networks, devices, and components across their networks, and support a robust and comprehensive Energy Efficiency strategy. That trend also influences Standards Development Organizations (SDOs) in information technology, e.g., work on energy efficiency metrics and various technology improvements.

Energy efficient network management involves deploying and managing network infrastructures to optimize energy use on network devices while improving overall network utilization. This includes adopting management plane technologies to monitor and manage energy consumption, evaluating the effectiveness of energy-saving policies beyond simply reducing consumption, and implementing control strategies that enhance overall energy efficiency in network operations.

RFC 6988 provides a set of requirements and guidelines for monitoring and managing power usage of devices (e.g., IP cameras, access points) within, or connected to, networks. The GREEN Working Group will examine that work to re-use it where possible, and develop new requirements (e.g., related to static device capabilities and energy efficiency metrics) for operator-managed IP devices according to current use cases and applications. More recently, RFC 9547 highlighted the need for further work on metrics, measurements, and the ability to slow down or sleep devices or components, etc. However, there is no consistent view within the networking industry for terminologies to categorize various metrics and measurements in IETF.

In addition, the absence of standardized interfaces for measuring, reporting, and controlling energy consumption across diverse network setups remains a significant challenge. Therefore, new data models, and metrics are required to optimize energy efficiency across the network. The EMAN WG specified a set of relevant MIBs in this area, but YANG models are now preferred [1].

As models and metrics are developed, standardized, and implemented in production networks, it will take many years before nearly all equipment in the field provides support. Therefore it is important to provide guidance for incremental deployment of energy-efficient functions in both network devices and the energy efficiency network management system.

**Goals and Scope**

The GREEN WG is chartered to explore use cases and requirements for identifying energy efficiency metrics, methods related to energy consumption of IP devices, and optimizing energy efficiency across the network. It will concentrate on the following short-term deliverables:

   - Define use cases for energy efficiency network management.
   - Define terms and definitions related to energy efficient metrics. Where possible, terms and definitions in existing RFCs 
     will be reused.
   - Develop YANG models to enable measuring and reporting of energy usage through metrics and attributes at component, 
     device, and network levels.
   - Provide YANG models to allow operators optimize energy usage in network devices, and across the network, via energy 
     saving capabilities control.
   - Develop or select a multi-level framework for energy efficiency monitoring, energy efficiency capability discovery and 
     control within a network domain. 

It may be complex and time-consuming to address all issues related to power consumption and energy efficiency 
in a single step. It can be practical to define building blocks that enhance both static device capabilities (related to 
inventory attributes) and dynamic energy efficiency metrics contributing to the network device operational lifecycle. 
The GREEN WG will provide tools to serve as a foundation for new energy efficiency strategies for operators. The working group will strive for implementation of YANG models before requesting publication as an RFC.

**Out of Scope**

To stay focused, the Working Group will not address energy-related issues in every networking area. Some topics are already covered in other venues while others may not be mature enough or present major shortcomings (e.g., have well-documented but unresolved security threats). The following topics are not within the scope of the Working Group:

   - Regulatory, compliance, and corporate responsibility related matters.
   - Routing protocols and algorithms, including those that consider energy factors.
   - Cross-domain telemetry and use of these measurements between trusted or untrusted parties.
   - Methodologies for understanding the impact of energy efficiency optimization on service quality.
   - Methodologies for assessing environmental sustainability and related performance for the network devices.
   - The carbon accounting and reporting protocol to measure, manage, and report greenhouse gas emissions and other 
     sustainability-related data such as renewable energy data.
   - Metadata formats for renewable energy or carbon related data within the energy efficiency network management system.

There is, however, considerable interest in carbon aware work from network operators,
for instance, and a future recharter of this working group is likely to address this in some manner.

**Work Items**

The GREEN Working Group will focus on the following:

- An Informational document that (1) defines common terminology and metric definitions, (2) categorizes various types of metrics and measurements at component, device, and network levels.

- Standard Track definitions of YANG data models at both the device level and network level for energy efficiency network management including energy usage monitoring, energy saving capability, and control.

- An Informational document that (1) defines a set of architectural components for energy efficient network management and (2) describes incremental deployment considerations for new energy efficiency metrics monitoring and capability discovery, and control within a network domain.

**Dependencies and Liaisons**

The GREEN Working Group will closely collaborate with:

   - Other IETF Working Groups that address topics related to power consumption observability and energy efficiency
     management, such as IVY, OPSAWG, and NETMOD.
   - Working Groups that might have related work or expertise with defining and standardizing metrics, measurement 
     frameworks and benchmarking methodology (e.g., IPPM and BMWG). 
   - Other IRTF Research Groups that provide research inputs and reviews, including PANRG and NMRG.
   - The IAB e-impact program to identify short-term metrics-related work and propose longer-term problems for further study.
     
The WG will collaborate with industry stakeholders and regulatory bodies to ensure alignment with current and future regulatory frameworks. The GREEN Working Group will also liaise with other SDOs on benchmarking methodologies for collaboration and consultation, mainly:

   - The European Telecommunications Standards Institute (ETSI), particularly the Technical Committee of Environment 
     Engineering (TCEE).
   - The International Telecommunication Union (ITU), specifically with ITU-T-SG-5.

**Milestones:** 

   - Develop and agree upon a standardized set of terminologies and definitions related to energy use and efficiency in 
     networking (Q4 2024).
   - Publish YANG models for operational energy use and efficiency related metrics that might be leveraged in other work to 
     improve energy efficiency within a network. (Q2 2025)
   - Develop a framework for incremental deployment of an energy-aware tools management (Q3 2025). 

[1] https://datatracker.ietf.org/doc/statement-iesg-writable-mib-module-iesg-statement-20140302/ 
