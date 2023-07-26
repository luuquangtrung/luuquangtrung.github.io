---
layout: page
title: maestro-5G
description: MAnagEment of Slices in The Radio access Of 5G networks (MAESTRO-5G)
img: assets/projects/maestro-5g.png
importance: 100
category: work
---

# General information
- Funded by [ANR](https://anr.fr/) (Agence nationale de la recherche)
- Website: [anr.fr/Project-ANR-18-CE25-0012](https://anr.fr/Project-ANR-18-CE25-0012)
- Role: Junior member (PhD student)

# Summary
5G networks are expected to revolution our living environments, our cities and our industry by connecting everything. 5G design has, thus, to meet the requirements of two “new” mobile services: massive Machine-Type Communications (mMTC), and Ultra Reliable Low Latency Communications (URLLC). Slicing concept facilitates serving these services with very heterogeneous requirements on a unique infrastructure. Indeed, slicing allows logically-isolated network partitioning with a slice representing a unit of programmable resources such as networking, computation and storage. Slicing was originally proposed for core networks, but is now being discussed for the Radio Access Network (RAN) owing to the evolution of technologies which now enable its implementation. These technologies include mainly the tendency for virtualizing the RAN equipment and its programmable control, the advent of Mobile Edge Computing (MEC) and the flexible design of 5G on the physical and MAC layers.
However, the complete implementation of slicing in the RAN faces several challenges, in particular to manage the slices and associated control and data planes and for scheduling and resources allocation mechanisms.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/projects/maestro-5g.png" title="maestro-5g" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example scenario of a geographical area (the Stade de France and its vicinity) covered by three different slices. Blue markers show the location of RRH nodes of Orange. See more <a href="https://ieeexplore.ieee.org/document/9187556/">here</a>.
</div>

MAESTRO-5G project develops enablers for implementing and managing slices in the 5G radio access network, not only for the purpose of serving heterogeneous services, but also for dynamic sharing of infrastructure between operators. For this aim the project puts together exerts on performance evaluation, queuing theory, network economy, game theory and operations research. MAESTRO-5G is expected to provide:
- A resource allocation framework for slices, integrating heterogeneous QoS requirements and spanning on multiple resources including radio, backhauling/fronthauling and processing resources in the RAN.
- A complete slice management architecture including provisioning and re-optimization modules and their integration with NFV and SDN strata.
- A business layer for slicing in 5G, enabling win-win situations between players from the telecommunications industry and the verticals, ensuring that the 5G services are commercially viable and gain acceptance in the market.
- A demonstrator showing the practical feasibility as well as integration of the major functions and mechanisms proposed by the project, on a 5G Cloud RAN platform. The enhanced platform is expected to support the different 5G services (eMBB and IoT) and to demonstrate key aspects of slicing, such as:
  - Ability to create and operate in parallel multiple slices, on the same infrastructure and sharing the same radio resources (e.g. spectrum), each having different service requirements.
  - Ability to create and operate in parallel and independently different slices, sharing the same infrastructure/spectrum, belonging to different business actors, such as different operators.
  - Demonstrate inter-slice control ensuring respect of SLAs and a fair resource sharing.

# Related Publications
1. **Q.-T. Luu**, S. Kerboeuf, A. Mouradian, and M. Kieffer, 
"[Coverage-Aware Resource Provisioning Method for Network Slicing](https://ieeexplore.ieee.org/document/9187556/)," 
in *IEEE/ACM Transactions on Networking*, vol. 28, no. 6, pp. 2393-2406, Dec. 2020. 
(hal: [hal-03097001](https://hal-centralesupelec.archives-ouvertes.fr/hal-03097001),
arXiv: [1907.09211v3](https://arxiv.org/abs/1907.09211v3)).
1. **Q.-T. Luu**, S. Kerboeuf, A. Mouradian, and M. Kieffer, 
"[Radio Resource Provisioning for Network Slicing with Coverage Constraints](https://ieeexplore.ieee.org/document/9148897)," 
in *Proc. IEEE International Conference on Communications (ICC)*, Dublin, Ireland, pp. 1-6, June, 2020 
(hal: [hal-03097210](https://hal-centralesupelec.archives-ouvertes.fr/hal-03097210)).
1. **Q.-T. Luu**, M. Kieffer, A. Mouradian, and S. Kerboeuf, 
"[Resource Provisioning for Network Slices with Coverage Constraints](https://orch5g.roc.cnam.fr/)," 
*ANR MAESTRO-5G Workshop on Orchestration of 5G Networks and Beyond*, CentraleSupélec, Gif-sur-Yvette, June, 2020.
1. B. Orlandi, S. Kerboeuf, F. Faucheux, J.-L. Lafragette, and **Q.-T. Luu**, 
"[Network Slicing Made Easy! From Graph-based Design to Automated Deployment of Network Slices in 5G](https://www.youtube.com/watch?v=pLkylDVwdcA&t=29s)," 
*Nokia 5G Smart Campus Event*, Nozay, 2018.
