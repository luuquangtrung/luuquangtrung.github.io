---
layout: post
permalink: /projects/asu-stic
title: Reducing the Energy Footprint of Communication Systems using Energy-Efficient Softwarized Networks
description: ASU-STIC Grant Proposal.
---

<img src="/assets/projects/stic_qr-project-on-web.png" width="600" />


### Background

The ever-increasing demand for data traffic and the rollout of new technologies like 5G and beyond (6G) pose a significant challenge: the growing energy consumption of communication networks [NGMN2021][^NGMN2021green]. This escalating energy footprint not only increases operational costs for network operators but also raises environmental concerns. As reported in  [Setiawan2023][^Setiawan2023energy], the information and communications technology (ICT) sector contributed to more than $$2\%$$ of the total global production of the greenhouse gases in 2020, in which the primary part is CO2. This urges the need to use connectivity and technology as fundamental components for realizing the United Nations’ sustainable development goals (SDGs). To address this challenging problem, this research project delves into software-driven strategies to reduce the energy consumption of communication networks by leveraging the potential of network slicing—a key feature of next-generation mobile networks (5G and beyond) [Setiawan2023][^Setiawan2023energy]. Network slicing allows for the creation of virtual networks within a physical network infrastructure (see Figure 1) [Li2017][^Li2017network]. These slices can be tailored to specific applications with unique performance and resource requirements. 

<img src="/assets/projects/stic_slicing.png" width="700" />

Figure 1. Illustration of slices tailored to diverse services running on the common network infrastructure [^Li2017network].

### Purpose
The project will focus on developing intelligent algorithms that can dynamically adjust resource allocation within network slices. These algorithms will consider factors like traffic patterns, user requirements, and energy consumption to ensure optimal performance while minimizing energy usage. By reducing energy consumption within network slices, operators can lower their environmental impact and operating expenses. Additionally, these software-driven solutions can be readily integrated into existing network management systems, ensuring a smooth transition to a more energy-efficient network operation.

Briefly, this project aims to propose **algorithmic** and **software-driven** solutions to
1. ensure **reliable** operation of network services
1. reduce **energy consumption** of networks by leveraging **network slicing**

Figure 2 shows an example of using network slicing to control the energy consumption of various network services according to their priorities.

<img src="/assets/projects/stic_energy-management.png" width="400" />

Figure 2. Illustration of energy-efficient network management using network slicing.

### Financial support from other projects

* Project: Optimizing resouce allocation for O-RAN slices in next-generation communication systems\
  Funded by Hanoi University of Science and Technology (HUST)\
  Duration: Nov. 2023 - Oct. 2025\
  Role: Principal investigator\
  Budget: $11,500
  

### Our previous work on network slicing

##### Patents
1.  Sylvaine Kerboeuf, **Quang-Trung Luu**, Michel Kieffer, and Alexandre Mouradian, 
"[Method and Apparatus for Mapping Network Slices Onto Network Infrastructures With SLA Guarantee](https://patents.google.com/patent/US11431562B2/en)," 
*US Patent 11,431,562 B2*, filed 07 December 2018, issued 16 December 2021, granted 30 August 2022.

##### Journal papers

1. **Quang-Trung Luu**, Sylvaine Kerboeuf, and Michel Kieffer, 
"[Admission Control and Resource Reservation for Prioritized Slice Requests with Guaranteed SLA under Uncertainties](https://ieeexplore.ieee.org/abstract/document/9737314)," 
*IEEE Transactions on Network and Service Management*, vol. 19, no. 3, pp. 3136-3153, Sept. 2022, DOI: 10.1109/TNSM.2022.3160352.
(E-ISSN: 1932-4537,
hal: [hal-03614028](https://hal.archives-ouvertes.fr/hal-03614028/),
arXiv: [2203.09367](https://arxiv.org/abs/2203.09367),
**Scopus Q1, IF 5.3**).

1. **Quang-Trung Luu**, Sylvaine Kerboeuf, and Michel Kieffer, 
"[Uncertainty-Aware Resource Provisioning for Network Slicing](https://ieeexplore.ieee.org/document/9351563)," 
in *IEEE Transactions on Network and Service Management*, vol. 18, no. 1, pp. 79-93, March 2021, DOI: 10.1109/TNSM.2021.3058139. 
(E-ISSN: 1932-4537, 
hal: [hal-03418308](https://hal.archives-ouvertes.fr/hal-03418308), 
arXiv: [2006.01104](https://arxiv.org/abs/2006.01104),
**Scopus Q1, IF 5.3**).

1. **Quang-Trung Luu**, Sylvaine Kerboeuf, Alexandre Mouradian, and Michel Kieffer, 
"[Coverage-Aware Resource Provisioning Method for Network Slicing](https://ieeexplore.ieee.org/document/9187556/)," 
in *IEEE/ACM Transactions on Networking*, vol. 28, no. 6, pp. 2393-2406, Dec. 2020, DOI: 10.1109/TNET.2020.3019098.
(E-ISSN: 1558-2566, 
hal: [hal-03097001](https://hal-centralesupelec.archives-ouvertes.fr/hal-03097001), 
arXiv: [1907.09211v3](https://arxiv.org/abs/1907.09211v3), 
**Scopus Q1, IF 3.7**).


##### Conference and workshop papers

1. Tuan-Vu Truong, **Quang-Trung Luu**, and Van-Dinh Nguyen,
"Efficient Resource Allocation Framework for Network Slicing-enabled Open RAN," 
*IEEE International Conference on Communications and Electronics (ICCE)*, 2024 (accepted, to appear)

1. Minh-Thanh Nguyen, **Quang-Trung Luu**, Tai-Hung Nguyen, Do-Minh Tran, Tuan-Anh Do, Kim-Hoan Do, and Van-Hieu Nguyen,
"Accelerating Network Slice Embedding with Reinforcement Learning," 
*IEEE International Conference on Communications and Electronics (ICCE)*, 2024 (accepted, to appear)

1. **Quang-Trung Luu**, Sylvaine Kerboeuf, and Michel Kieffer, 
"[Foresighted Resource Provisioning for Network Slicing](https://ieeexplore.ieee.org/document/9481832)," 
in *Proc. IEEE International Conference on High Performance Switching and Routing (HPSR)*, Paris, pp. 1-8, June 2021, DOI: 10.1109/HPSR52026.2021.9481832. 
(E-ISSN: 2325-5609,
hal: [hal-03420010](https://hal.archives-ouvertes.fr/hal-03420010)
**invited paper**, **CORE Rank C**).

1. **Quang-Trung Luu**, Sylvaine Kerboeuf, Alexandre Mouradian, and Michel Kieffer, 
"[Radio Resource Provisioning for Network Slicing with Coverage Constraints](https://ieeexplore.ieee.org/document/9148897)," 
in *Proc. IEEE International Conference on Communications (ICC)*, Dublin, Ireland, pp. 1-6, June, 2020, DOI: 10.1109/ICC40277.2020.9148897. 
(E-ISSN: 1938-1883, 
hal: [hal-03097210](https://hal-centralesupelec.archives-ouvertes.fr/hal-03097210)).

1. **Quang-Trung Luu**, Michel Kieffer, Alexandre Mouradian, and Sylvaine Kerboeuf, 
"[Aggregated Resource Provisioning for Network Slices](https://ieeexplore.ieee.org/abstract/document/8648039)," 
in *Proc. IEEE Global Communications Conference (GLOBECOM)*, Abu Dhabi, UAE, pp. 1-6, Dec. 2018, DOI: 10.1109/GLOCOM.2018.8648039.
(ISSN: 2576-6813
hal: [hal-02097749](https://hal.archives-ouvertes.fr/hal-02097749),
**CORE Rank B**).


[^NGMN2021green]: NGMN Alliance, “Green Future Networks Sustainability Challenges and Initiatives in Mobile Networks by NGMN Alliance,” White Paper, p. 36, 2021.
[^Setiawan2023energy]:	I. Setiawan, B. Kar, and S.-H. Shen, “Energy-Efficient Softwarized Networks: A Survey,” arXiv preprint arXiv:2307.11301, pp. 1–21, 2023, [Online]. Available: http://arxiv.org/abs/2307.11301
[^Khan2020network]:	L. U. Khan, I. Yaqoob, N. H. Tran, Z. Han, and C. S. Hong, “Network Slicing: Recent Advances, Taxonomy, Requirements, and Open Research Challenges,” IEEE Access, vol. 8, pp. 36009–36028, 2020, doi: 10.1109/ACCESS.2020.2975072.
[^Li2017network]:	X. Li et al., “Network Slicing for 5G: Challenges and Opportunities,” IEEE Internet Comput., vol. 21, no. 5, pp. 20–27, 2017, doi: 10.1109/LANMAN.2016.7548842.

### References
