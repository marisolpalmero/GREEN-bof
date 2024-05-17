# Name: Getting Ready for Energy-Efficient Networking (GREEN)
## Description 

As the desire to improve energy efficiency gains momentum, network operators increasingly focus on understanding energy consumption by different links, nodes, and devices within their networks. Network Energy-efficiency management involves deploying and managing network infrastructures with the dual goals of optimizing energy use and minimizing environmental impact. This will involve technologies to monitor energy consumption, evaluate the effectiveness of energy saving polices, use control strategies to improve energy efficiency, and foster sustainability in network operations.

This BoF is intended to discuss these objectives and determine whether there is a community of interest to work on these topics within the IETF through a new working group (provisionally called GREEN).

The BoF discussion should identify a suite of short-term deliverables aimed at enhancing energy efficiency within networks. Key objectives include standardizing terms and definitions for energy metrics, and YANG models for reporting energy consumption usage and performing energy management. Additionally, the group could create a framework to describe the effective collection and utilization of these metrics and attributes. The proposed approach is to tackle energy efficiency challenges in a systematic and incremental manner, focusing on practical building blocks that contribute to overarching energy efficiency goals.

## Required Details

- Status: WG Forming
- Responsible AD: Mahesh Jethanandani
- Chairs: TBD
- BOF proponents: Emile Stephan(emile.stephan@orange.com), Marisol Palmero(mpalmero@cisco.com), Qin Wu(bill.wu@huawei.com), Tony Li(tony.li@tony.li)
- Number of people expected to attend: 150
- Length of session: 2 hours
- Conflicts (whole Areas and/or WGs)
   - Chair Conflicts: TBD
   - Technology Overlap: OPS Area, RTGWG, LSR
   - Key Participant Conflict: MPLS, TVR

## Information for IAB/IESG
To allow evaluation of your proposal, please include the following items:

- Any protocols or practices that already exist in this space:
  - See the new work of IVY working group on energy management and the existing work of the closed EMAN working group.
  - See metrics work discussion in section 3.3 and section 3.4 of RFC9547.
  - [See IAB Environment Impact Workshop on Mertrics](https://datatracker.ietf.org/meeting/interim-2022-eimpactws-03/materials/slides-interim-2022-eimpactws-03-sessa-iab-e-impact-ws-session-3-metrics-01.pdf) 
- Which (if any) modifications to existing protocols or practices are required:
  - Approaches are likely to use Netconf/Restconf and YANG.
  - Proposals to LSR for IGP enhancements for energy-efficient path computation.
- Which (if any) entirely new protocols or practices are required:
  - None identified so far.
- Open source projects (if any) implementing this work:
  - None identified so far.


## Agenda

   [BoF Agenda Proposal](https://github.com/marisolpalmero/GREEN-bof/blob/main/BoFAgenda.md)

## Links to the mailing list, draft charter if any, relevant Internet-Drafts, etc.
   - Mailing List: https://www.ietf.org/mailman/listinfo/green-bof
   - Draft charter: <TBUpdated> (https://datatracker.ietf.org/doc/charter-ietf-EXAMPLE/),(https://github.com/marisolpalmero/GREEN-bof/blob/main/GreenCharterProposal.md)
   - 
   - Relevant Internet-Drafts:

     - Terminology 
       - Candidate documents:[draft-cparsk-eimpact-sustainability-considerations](https://datatracker.ietf.org/doc/draft-cparsk-eimpact-sustainability-considerations/)
     - Power metrics collection and aggregation framework.
       - Candidate documents: [draft-lindblad-tlm-philatelist](https://datatracker.ietf.org/doc/draft-lindblad-tlm-philatelist), [draft-kll-yang-label-tsdb](https://datatracker.ietf.org/doc/draft-kll-yang-label-tsdb), [draft-cx-opsawg-green-metrics](https://datatracker.ietf.org/doc/draft-cx-opsawg-green-metrics)
     - Use Cases:
       - Candidate documents: [draft-almprs-sustainability-insights](https://datatracker.ietf.org/doc/draft-almprs-sustainability-insights)
     - YANG model for power consumption observability and energy saving management.
       - Candidate documents: [draft-li-ivy-power](https://datatracker.ietf.org/doc/draft-li-ivy-power); [draft-cwbgp-ivy-energy-saving-management](https://datatracker.ietf.org/doc/draft-cwbgp-ivy-energy-saving-management); [draft-petra-path-energy-api](https://datatracker.ietf.org/doc/draft-cwbgp-ivy-energy-saving-management); [draft-opsawg-poweff](https://datatracker.ietf.org/doc/draft-opsawg-poweff)


     

