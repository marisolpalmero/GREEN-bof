Charter proposal for Get Ready Energy Efficiency Network (GREEN)

**Background and Motivation**

Energy efficiency gains for communication systems are highly sought after, for environmental, business, and technical reasons. Network operators increasingly focus on understanding energy consumption by links, nodes and devices/components across their networks. This influences of course also standards organizations in the information technology field, e.g., work on energy efficiency metrics and various technology improvements.

Network Energy-efficiency management involves deploying and managing network infrastructure with the dual goals of optimizing energy use and minimizing environmental impact. This includes adopting technologies to monitor and effectively manage energy consumption, evaluating the environmental benefits of energy-saving policies beyond just reducing consumption, implementing control strategies that enhance overall energy efficiency, and promoting sustainable practices in network operations. It also recognizes that, in some cases, strategic increases in energy use from sustainable sources can lead to long-term environmental improvements.

RFC 6988 provides some requirements and guidelines for monitoring and managing energy usage in network devices. 
The GREEN working group will examine that work with a view to re-using it where possible, and developing new requirements according to current use cases and applications. More recently, RFC 9547 highlighted the need of further work on metrics, measurements, ability to slow down and sleep devices or part of them, etc. However, there is no consistent view in the industry for terminologies to categorize various type of metrics and measurements.
In addition, the absence of standardized interfaces for measuring, reporting, and controlling energy consumption across diverse network setups remains a significant challenge. Therefore, new data models, metrics and methods are required to optimize energy efficiency across the network.

As models and metrics are developed, standardized and implemented in production networks, it will take many years before nearly all equipment in the field supports the new models and metrics. Therefore it will be necessary to map legacy metrics to the new models and allow a wide variety of collection mechanisms. Specifically, even though the collection process itself is modeled in YANG, devices cannot generally be assumed to have the data which is to be collected available in any YANG-based management interface.

**Goals and Scope**

The GREEN WG is chartered to concentrate on the following short-term deliverables:
   - Terms and definitions related to energy metrics. Where possible, terms and definitions existing in prior RFCs will be reused.
   - Developing YANG models or augmenting existing models to enable reporting of energy usage through metrics and attributes at component, device, and network levels.
   - Create a unified document that includes both the energy consumption metrics and their associated YANG data models, along with guidance on how to use, interpret, and handle them.
   - Providing YANG models to control and optimize energy usage in network devices, including energy saving capabilities. 
   - Develop or select a framework that will enable the collection, aggregation and consumption of mentioned metrics and attributes developed in the WG from existing and new devices of almost every kind.

It may be complex and time-consuming to attempt to address all issues related to power consumption and energy efficiency in one go, but it can be practical to select building-blocks that will contribute to the larger effort. The GREEN WG will combine concrete approaches to develop tools that will serve as a foundation for new energy efficiency strategies.


**Out of Scope**

To stay focused, this working group will not address all issues. Some topics may already be covered elsewhere while others may not be mature enough or have unresolved security models. The following topics are not within the scope of the working group:

   - Routing protocols and energy aware routing algorithms considering green energy factors.
   - Benchmarking methodology for power consumption in networking devices (a work item of the BMWG).
   - Methodologies for understanding the impact of energy efficiency optimization on service quality.
   - Regulatory, compliance, and corporate responsibility related matters

 Adopting a longer-term approach to global sustainability efforts requires enhancing inventory attributes. This enhancement will contribute to a more sustainable lifecycle for network devices. To ensure the effectiveness and alignment of these efforts, it will be essential to coordinate the work of the GREEN WG with the IVY WG.

**Work Items**

Use Cases:
   - Candidate documents: draft-almprs-sustainability-insights

Terminology 
   - Candidate documents: draft-cparsk-eimpact-sustainability-considerations

YANG model for energy consumption observability and energy saving management.
   - Candidate documents: draft-li-ivy-power; draft-cwbgp-ivy-energy-saving-management; draft-petra-path-energy-api; draft-opsawg-poweff

Energy metrics collection and aggregation framework.
   - Candidate documents: draft-lindblad-tlm-philatelist, draft-kll-yang-label-tsdb, draft-cx-opsawg-green-metrics


**Dependencies and Liaisons**

The GREEN Energy working group will closely collaborate with:

   - Other IETF Working Groups that address topics related to power consumption observability and energy efficiency
     management, such as IVY, OPSAWG, and NETMOD.
   - WGs that might have related work or expertise with defining and standardizing metrics and measurement frameworks (e.g., IPPM and BMWG). 
   - Other IRTF Research Groups that provide research inputs and reviews, including PANRG, NMRG.
   - The IAB e-impact program to identify and receive short term metrics related work and to propose longer term problems for further study. 

The GREEN WG will liaise with ITU-T and ETSI on benchmarking methodologies for collaboration and consultation,as follows:

   - The European Telecommunications Standards Institute (ETSI), particularly with regard to the TCEE (Technical
     Committee of Environment Engineering).
   - The International Telecommunication Union (ITU), particularly with regard to ITU-T-SG-5.

**Milestones:** 

   - Develop and agree upon a standardized set of terminologies and definitions related to energy efficiency and sustainability in networking (Q4 2024).
   - Draft and publish YANG models for operational energy efficiency related metrics. While metrics are valuable, they should be leveraged to guide and inspire changes in operational practices to improve energy efficiency and sustainability practices. (Q2 2025)
   - Propose and ratify an architectural framework for energy consumption reporting (Q3 2025).
   - Develop a framework for incremental deployment of an energy-aware tools management (Q3 2025).
   - Demonstrate initial implementations and use cases of the YANG models in network devices (Q4 2025). 
