---
layout: archive
title: ""
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}


Research Work
=

My research work on Electric Machines is focusing on:
* **Design of Electric Machines**:   
The initial phase of the design process involves selecting the machine topology tailored to the specific application requirements. Typically, the machine is geometrically designed, often employing intricate mathematical equations to ensure the creation of viable machine geometries—a crucial aspect throughout the optimization phase. Assessment of the machine's diverse performances can be conducted through analytical or finite element models. In my practice, I rely on software tools such as Ansys, Comsol, and Femm to evaluate electromagnetic, mechanical, and thermal performances (<a href="https://www.mdpi.com/2075-1702/11/1/57" target="_blank">read more</a>). My studies have encompassed various machine types, including V-shaped PMSM, Inserted PMSM, Surface PMSM, and others.  
<div><img src="/images/Design_Electric_Machine.png"
       alt="Picture"
       align="center"
       width="600px"
       style="display: block; margin: 0 auto">
</div>  

<hr style="height:1px;border:none;color:#969696;background-color:#969696;">

+ **High-Speed Machines**:  
High-speed machines offer compact solutions across diverse applications, but addressing associated challenges is imperative. Issues such as the mechanical integrity of the rotor and high-frequency phenomena in various machine components demand thorough investigation. In my research, I concentrated on analyzing high-frequency phenomena within windings, stator, and rotor core, particularly delving into electromagnetic aspects. Additionally, I explored the mechanical and thermal dimensions. Achieving high power density in lieu of high speed involves alternatives like elevating current density and fill factor in slots, necessitating robust cooling techniques (<a href="https://www.mdpi.com/2075-1702/11/1/57" target="_blank">read more</a>).  
<!--- To avoid aligned photo, rather than two spaces at the end, it is possible to add <div> at the beginning and </div> at the end --->
<div><img src="/images/HighSpeed.png"
       alt="Picture"
       align="center"
       width="300px"
       style="display: block; margin: 0 auto">
</div>  

<hr style="height:1px;border:none;color:#969696;background-color:#969696;">

- **High-Frequency losses in windings**:  
Losses in windings are usually assumed to be equal to Joule losses during the design process of the machine. High frequency losses are often left to post-processing, in which the windings configuration and wires dimensions are determined to mitigate high frequency effects. However, at high-frequency, new electromagnetic phenomena appear. These effects are: skin effect, proximity effect, and circulating currents. These effects need to be considered and included in the desing process of the machine. In my work, I reviewed all models of high frequency losses in windings and proposed a methodology to include these losses during the optimization process using Hybrid Model Simple Finite Element Analysis (<a href="https://www.mdpi.com/2075-1702/11/1/57" target="_blank">read more</a>). A particular attention was brought to circulating currents properties. The fact that circulating currents always induce higher losses compared to the DC case is mathematically demonstrated (<a href="https://ieeexplore.ieee.org/document/10366258" target="_blank">read more</a>). Further, a mitigitation method of circulating currents consisting of having longer active length compared to end windings length is also mathematically demonstrated (<a href="https://ieeexplore.ieee.org/document/10366258" target="_blank">read more</a>).  
<div><img src="/images/AC_Losses.png"
       alt="Picture"
       align="center"
       width="600px"
       style="display: block; margin: 0 auto">
</div>  

<hr style="height:1px;border:none;color:#969696;background-color:#969696;">

- **Optimization of Electric Machines**:   
Optimizing machines according to specified criteria holds significant implications across diverse industries, including automotive and aeronautics. Through the optimization of geometry, materials, and winding configurations, machines can align with specifications and requirements by employing a multi-physics model encompassing electromagnetic, mechanical, and thermal aspects. In my research, I focus on multi-objective optimization, which allows considering many objectives and constraints (<a href="https://www.mdpi.com/2075-1702/11/1/57" target="_blank">read more</a>). Optimization results are represented in a Pareto Front, striking a balance between conflicting performances such as efficiency and power density. I perform large-scale optimization using CPUs on the server, in which millions of machines can be simulated. I use various optimization tools (Genetic Algorithm, Particle Swarm, ...).  
<div><img src="/images/Optimization_Machines_Flowchart_10_0.png"
       alt="Picture"
       align="center"
       width="600px"
       style="display: block; margin: 0 auto">
</div>  

<hr style="height:1px;border:none;color:#969696;background-color:#969696;">

- **Electric Vehicles Propulsion**:   
The design of electric vehicles propulsion include all the components of the electric powertrain. In my research work, I mainly focus on the design of electric machine and the gearbox. I worked on the design of machines for city electric vehicles in collaboration with automotive companies. Based on automotive specifications, different machines are designed and compared to achieve best trade-off between efficiency and power density. The gearbox used is a multi-stage external, cylindrical, and helicoidal gear. The gear is geometrically designed considering profile shifting. To obtain overall optimum performances, I consider both the electric machine and the gearbox.  
<div><img src="/images/Electric_Vehicle_Propulsion.png"
       alt="Picture"
       align="center"
       width="600px"
       style="display: block; margin: 0 auto">
</div>  

<hr style="height:1px;border:none;color:#969696;background-color:#969696;">

- **Electric Aircraft Propulsion**:   
Paragraph Text  
<div><img src="/images/Electric_Aircraft_Propulsion.png"
       alt="Picture"
       align="center"
       width="600px"
       style="display: block; margin: 0 auto">
</div>  

<hr style="height:1px;border:none;color:#969696;background-color:#969696;">

- **Experimental Work**:   
Amongst my experimental works, I focused on experimental measurment of high frequency losses in windings. A new methodology is developed to measure proximity effect losses in windings and applied to the case of a winded slot. Although additional losses due to proximity effect are relatively small, obtained results show the variation of total losses in windings with respect to frequency and current. The methodology consists of twisting two conductors with each other: the first one (principal conductor) is the conductor in which losses are measured and the second one represents is an auxiliary conductor used for the methodology calculation.   
<div><img src="/images/Experimental_AC_Losses.png"
       alt="Picture"
       align="center"
       width="600px"
       style="display: block; margin: 0 auto">
</div>  

<br/><br/>

<hr style="border:2px solid gray">
*References:*  
- T. El Hajji, "Modeling and optimization of high speed electric machines for electric vehicles", PhD Dissertation, Ecole Normale Superieure Paris-Saclay, Paris-Saclay University, March 2023, <a href="https://www.theses.fr/2023UPAST017" target="_blank">Manuscript file</a> (accessible starting from 08-03-2028)  
- T. E. Hajji et al., "AC Losses in Windings: Review and Comparison of Models With Application in Electric Machines," in IEEE Access, vol. 12, pp. 1552-1569, 2024, doi: <a href="https://ieeexplore.ieee.org/document/10366258" target="_blank">10.1109/ACCESS.2023.3345014</a>  
- El Hajji, T.; Hlioui, S.; Louf, F.; Gabsi, M.; Mermaz-Rollet, G.; Belhadi, M. Optimal Design of High-Speed Electric Machines for Electric Vehicles: A Case Study of 100 kW V-Shaped Interior PMSM. Machines 2023, 11, 57. doi: <a href="https://www.mdpi.com/2075-1702/11/1/57" target="_blank">10.3390/machines11010057</a>  
- T. El Hajji, S. Hlioui, F. Louf, M. Gabsi, G. Mermaz-Rollet and M. Belhadi, "Hybrid model for AC Losses in High Speed PMSM for arbitrary flux density waveforms," 2020 International Conference on Electrical Machines (ICEM), Gothenburg, Sweden, 2020, pp. 2426-2432, doi:  <a href="https://ieeexplore.ieee.org/document/9271017" target="_blank">10.1109/ICEM49940.2020.9271017</a>  
