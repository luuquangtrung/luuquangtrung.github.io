---
layout: page
title: maestro-5G
description: MAnagEment of Slices in The Radio access Of 5G networks (MAESTRO-5G)
img: assets/projects/oran_slicing.png
importance: 1
category: work
---

# Summary
5G networks are expected to revolution our living environments, our cities and our industry by connecting everything. 5G design has, thus, to meet the requirements of two “new” mobile services: massive Machine-Type Communications (mMTC), and Ultra Reliable Low Latency Communications (URLLC). Slicing concept facilitates serving these services with very heterogeneous requirements on a unique infrastructure. Indeed, slicing allows logically-isolated network partitioning with a slice representing a unit of programmable resources such as networking, computation and storage. Slicing was originally proposed for core networks, but is now being discussed for the Radio Access Network (RAN) owing to the evolution of technologies which now enable its implementation. These technologies include mainly the tendency for virtualizing the RAN equipment and its programmable control, the advent of Mobile Edge Computing (MEC) and the flexible design of 5G on the physical and MAC layers.
However, the complete implementation of slicing in the RAN faces several challenges, in particular to manage the slices and associated control and data planes and for scheduling and resources allocation mechanisms.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/projects/oran_slicing.png" title="o-ran slicing" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The tentative architecture of EC-enabled O-RAN slicing systems.
</div>

MAESTRO-5G project develops enablers for implementing and managing slices in the 5G radio access network, not only for the purpose of serving heterogeneous services, but also for dynamic sharing of infrastructure between operators. For this aim the project puts together exerts on performance evaluation, queuing theory, network economy, game theory and operations research. MAESTRO-5G is expected to provide:
- A resource allocation framework for slices, integrating heterogeneous QoS requirements and spanning on multiple resources including radio, backhauling/fronthauling and processing resources in the RAN.
- A complete slice management architecture including provisioning and re-optimization modules and their integration with NFV and SDN strata.
- A business layer for slicing in 5G, enabling win-win situations between players from the telecommunications industry and the verticals, ensuring that the 5G services are commercially viable and gain acceptance in the market.
- A demonstrator showing the practical feasibility as well as integration of the major functions and mechanisms proposed by the project, on a 5G Cloud RAN platform. The enhanced platform is expected to support the different 5G services (eMBB and IoT) and to demonstrate key aspects of slicing, such as:
  - Ability to create and operate in parallel multiple slices, on the same infrastructure and sharing the same radio resources (e.g. spectrum), each having different service requirements.
  - Ability to create and operate in parallel and independently different slices, sharing the same infrastructure/spectrum, belonging to different business actors, such as different operators.
  - Demonstrate inter-slice control ensuring respect of SLAs and a fair resource sharing.
