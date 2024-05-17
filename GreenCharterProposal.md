Charter proposal for Get Ready Energy Efficiency Network (GREEN)

**Background and Motivation**

Energy efficiency gains for communication systems are highly sought after, for environmental, business, and technical reasons. Network operators are seeking for tools and solutions to better assess and control the energy consumption by links, nodes, and devices/components across their networks. That trend influences also Standards Development Organizations (SDOs) in the information technology field, e.g., work on energy efficiency metrics and various technology improvements.

Network energy-efficiency management involves deploying and managing network infrastructures with the dual goals of optimizing energy use and minimizing environmental impact. This includes adopting technologies to monitor and effectively manage energy consumption, evaluating the environmental benefits of energy-saving policies beyond just reducing consumption, implementing control strategies that enhance overall energy efficiency, and promoting sustainable practices in network operations. It also recognizes that, in some cases, strategic increases in energy use from sustainable sources can lead to long-term environmental improvements.

RFC 6988 provides some requirements and guidelines for monitoring and managing power usage of devices within, or connected to, networks such as Power over Ethernet devices, network devices. The GREEN working group will examine that work with a view to re-using it where possible, and developing new requirements for operators managed network devices according to current use cases and applications. More recently, RFC 9547 highlighted the need of further work on metrics, measurements, ability to slow down and sleep devices or part of them, etc. However, there is no consistent view in the industry for terminologies to categorize various type of metrics and measurements.

In addition, the absence of standardized interfaces for measuring, reporting, and controlling energy consumption across diverse network setups remains a significant challenge. Therefore, new data models, metrics and methods are required to optimize energy efficiency across the network.

As models and metrics are developed, standardized and implemented in production networks, it will take many years before nearly all equipment in the field supports the new models and metrics. Therefore it will be necessary to map legacy metrics to the new models and allow a wide variety of collection mechanisms. Specifically, even though the collection process itself is modeled in YANG, devices cannot generally be assumed to have the data which is to be collected available in any YANG-based management interface.

**Goals and Scope**

The GREEN WG is chartered to concentrate on the following short-term deliverables:

   - Defining terms and definitions related to energy metrics. Where possible, terms and definitions existing in existing RFCs will be reused.
   - Developing YANG models or augmenting existing models to enable controling and reporting of energy usage through metrics and attributes at component, device, and network levels.
   - Documenting both the energy consumption metrics and their associated YANG data models, along with guidance on how to use and interpret them.
   - Providing YANG models to control and optimize energy usage in network devices, including energy saving capabilities. 
   - Developing or selecting a framework to collect, aggregate, and consume the above mentioned metrics and attributes developed in the WG from existing and new devices of almost every kind.

It may be complex and time-consuming to attempt to address all issues related to power consumption and energy efficiency in one step, but it can be practical to select building-blocks that will contribute to the larger effort. The GREEN WG will consider approaches to facilitate the emergence of tools that will serve as a foundation for new energy efficiency strategies.


**Out of Scope**

To stay focused, the Working Group will not address energy-related issues in every networking area. Some topics may already be covered in other venues while others may not be mature enough or present major shortcomings (e.g., have well-documented but unresolved security threats). The following topics are not within the scope of the Working Group:

   - Routing protocols and energy-aware routing algorithms considering energy factors.
   - Benchmarking methodology for power consumption in networking devices.
   - Methodologies for understanding the impact of energy efficiency optimization on service quality.
   - Regulatory, compliance, and corporate responsibility related matters.

Adopting a longer-term approach to global sustainability efforts requires enhancing inventory attributes. This enhancement will contribute to a more sustainable lifecycle for network devices. To ensure the effectiveness and alignment of these efforts, the GREEN Working Group will closely coordinate with the IVY Working Group.

**Work Items**

Use Cases
   - Candidate documents: draft-almprs-sustainability-insights

Terminology 
   - Candidate documents: draft-cparsk-eimpact-sustainability-considerations

YANG model(s) for energy consumption observability and energy saving management
   - Candidate documents: draft-li-ivy-power, draft-cwbgp-ivy-energy-saving-management, draft-petra-path-energy-api, draft-opsawg-poweff

Energy metrics collection and aggregation framework
   - Candidate documents: draft-lindblad-tlm-philatelist, draft-kll-yang-label-tsdb, draft-cx-opsawg-green-metrics

**Dependencies and Liaisons**

The GREEN Working Group will closely collaborate with:

   - Other IETF Working Groups that address topics related to power consumption observability and energy efficiency
     management, such as IVY, OPSAWG, and NETMOD.
   - Working Groups that might have related work or expertise with defining and standardizing metrics and measurement frameworks (e.g., IPPM and BMWG). 
   - Other IRTF Research Groups that provide research inputs and reviews, including PANRG, NMRG.
   - The IAB e-impact program to identify and receive short term metrics related work and to propose longer term problems for further study. 

The GREEN Working Groups will liaise with other SDOs on benchmarking methodologies for collaboration and consultation, mainly:

   - The European Telecommunications Standards Institute (ETSI), particularly with regard to the Technical
     Committee of Environment Engineering (TCEE).
   - The International Telecommunication Union (ITU), particularly with regard to ITU-T-SG-5.

**Milestones:** 

   - Develop and agree upon a standardized set of terminologies and definitions related to energy efficiency and sustainability in networking (Q4 2024).
   - Publish YANG models for operational energy efficiency related metrics. While metrics are valuable, they should be leveraged to guide and inspire changes 
     in operational practices to improve energy efficiency and sustainability practices. (Q2 2025)
   - Develop a framework for incremental deployment of an energy-aware tools management (Q3 2025).
   - Demonstrate initial implementations and use cases of the YANG models in network devices (Q4 2025). 
