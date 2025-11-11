---
sidebar: true
permalink: /Research/
title: "Research Interest Areas"
---

<!-- ![](/images/Draft%20Group%20Overview.png) -->
<!-- Overview image, not helpful? -->

At the SAM lab, we develop and employ the most powerful computational techniques available to tackle crucial materials challenges for a better world.
Currently, this includes quantum-mechanical (e.g. DFT, GW) and machine-learning approaches, which we use to investigate, design and develop advanced materials across a range of technologies.

We have a particularly strong interest in materials for energy conversion (such as solar cells, photocatalysts and thermoelectrics) and energy storage (e.g. batteries).
Some core focus areas are given below, but we are flexible to the skillsets and interests of those who join our team!

## Our Tools
<div style="float: right; width: 200px; margin-left: 15px;">
  <img src="/images/Orbitals.jpg" alt="Orbitals" style="width: 100%; border-radius: 8px;">
</div>
### Quantum Mechanics
First-principles quantum-mechanical theories, such as Density Functional Theory (DFT) and Green's functions (GW), allow us to predict the behaviour of materials without any experimental input.
While this may sound complicated, these theories are implemented for us in robust codes which we use on high-performance computers; such as [Archer2](https://www.archer2.ac.uk/).



### Machine Learning (ML) / Artificial Intelligence (AI)
<div style="float: right; width: 325px; margin-left: 15px; margin-bottom: 40px;">
  <img src="/images/Materials_GNN.jpg" alt="Materials_GNN" style="width: 100%; border-radius: 8px;">
</div>  
<!-- Image from https://www.nature.com/articles/s43246-022-00315-6/figures/1 -->
Machine learning (ML) has emerged as a revolutionary tool in many areas of research and technology.
In our work, we develop and deploy large machine-learning models which can reproduce the results of quantum-mechanical simulations, but at far greater speeds and scales.
This allows us to greatly expand the scope and accuracy of our simulations.

For example; searching for a specific type of defect ('split vacancies') in [all known crystalline inorganic materials](https://iopscience.iop.org/article/10.1088/2515-7655/ade916), or developing large [foundation models for inorganic materials](https://matbench-discovery.materialsproject.org/).
These efforts often involve collaboration (and sometimes friendly competition) with industry teams, such as NVIDIA, Bosch, Meta, Microsoft, Google DeepMind and more.

## Our Challenges
### Energy Materials
One of our primary motivations is to contribute to a better society (which combined with our curiosity-driven problem-solving work makes quite a fulfilling combination!).
This goal has inspired our interest in advanced materials for energy conversion and storage.
This includes the design of advanced solar cell technologies, cathodes for high-capacity batteries, ultra-efficient photo-catalysts and more.

We often collaborate closely with experimental groups on these projects, who synthesise the materials and fabricate devices in their labs; testing our predictions and asking us to help explain their observations.
These can be highly impactful team projects, with a lot of fun along the way.
<div style="float: right; width: 275px; margin-left: 15px;">
  <img src="/images/Faded_AgBiS2_NC_Cover_Image.jpg" alt="AgBiS₂ Solar Cells" style="width: 100%; border-radius: 8px;">
</div>

- [Intrinsic point defect tolerance in selenium for indoor and tandem photovoltaics](https://pubs.rsc.org/en/content/articlelanding/2025/ee/d4ee04647a) _Energy & Environmental Science_ 2025
- [Cation disorder engineering yields AgBiS₂ nanocrystals with enhanced optical absorption for efficient ultrathin solar cells](https://www.nature.com/articles/s41566-021-00950-4) _Nature Photonics_ 2022
- [Strong absorption and ultrafast localisation in NaBiS₂ nanocrystals with slow charge-carrier recombination](https://www.nature.com/articles/s41467-022-32669-3) _Nature Communications_ 2022
- [Defect Tolerance via External Passivation in the Photocatalyst SrTiO₃:Al](https://pubs.acs.org/doi/10.1021/jacs.5c07104) _Journal of the American Chemical Society_ 2025

### Defects
<div style="float: right; width: 200px; margin-left: 15px;">
  <img src="/images/Te_i_0.jpg" alt="Te_i_0 in CdTe" style="width: 100%; border-radius: 8px;">
</div>  
Defects are imperfections or 'mistakes' in the arrangement of atoms in materials.
Like mutations in DNA, they are rare events but with major macroscopic effects, in fact dictating the performance of most functional materials; including semiconductors (defects are what allow them to 'conduct'), solar cells, transparent conducting materials, thermoelectrics, photo/electro-catalysts, quantum sensors, LEDs...
<div style="float: right; width: 200px; margin-left: 15px; margin-bottom: 40px;">
  <img src="/images/Solar Cell Defect Recombination.png" alt="Solar Cell Defect Recombination" style="width: 100%; border-radius: 8px;">
</div>  

However, they are incredibly difficult to study experimentally due to their low concentrations.
This makes them very interesting for us, as we can investigate them with computational approaches at far greater resolution than experimental measurements, to give crucial insights.
<!-- Our work in this area combines chemistry, physics and computational methods to  -->

- [Identifying split vacancy defects with machine-learned foundation models and electrostatics](https://iopscience.iop.org/article/10.1088/2515-7655/ade916) _JPhys Energy_ 2025
- [Identifying the ground state structures of point defects in solids](https://www.nature.com/articles/s41524-023-00973-1) _npj Computational Materials_ 2023

### Disorder
<div style="float: right; width: 275px; margin-left: 15px;">
  <img src="/images/AgBiS2_Disorder.jpg" alt="AgBiS₂ Disorder" style="width: 100%; border-radius: 8px;">
</div>
Computational studies inevitably require approximations to model materials and devices, using idealised high-symmetry structure models.
Real materials have ~~curves~~ imperfections such as defects, surfaces, interfaces and disorder, however, which in most cases are what _actually_ limit device performance.
We develop and employ computational techniques to properly account for such disorder and thus make effective predictions.
An exciting new avenue of research is the adoption of machine-learning approaches to model these imperfections with high levels of accuracy.

- [Cation disorder engineering yields AgBiS₂ nanocrystals with enhanced optical absorption for efficient ultrathin solar cells](https://www.nature.com/articles/s41566-021-00950-4) _Nature Photonics_ 2022
- [Strong absorption and ultrafast localisation in NaBiS₂ nanocrystals with slow charge-carrier recombination](https://www.nature.com/articles/s41467-022-32669-3) _Nature Communications_ 2022
- [Cation disorder dominates the defect chemistry of high-voltage LiMn1.5Ni0.5O4 (LMNO) spinel cathodes](https://pubs.rsc.org/en/content/articlelanding/2023/ta/d3ta00532a) _Journal of Materials Chemistry A_ 2023
- [Interplay of Static and Dynamic Disorder in the Mixed-Metal Chalcohalide Sn2SbS2I3](https://pubs.acs.org/doi/full/10.1021/jacs.2c13336) _Journal of the American Chemical Society_ 2023

### Method & Software Development
Along with targeted investigations of advanced materials technologies, we develop novel methods to help tackle major challenges in the field.
Often, these new approaches start from simple ideas – such as [`ShakeNBreak`](https://shakenbreak.readthedocs.io); a strategy for identifying the lowest-energy arrangements of defects, crucial for material properties such as conductivity, solar cell efficiency, quantum sensing and more – but with far-reaching impacts.

<a href="https://shakenbreak.readthedocs.io">
  <img src="https://raw.githubusercontent.com/SMTG-Bham/ShakeNBreak/main/docs/SnB_Supercell_Schematic_PES_2sec_Compressed.gif">
</a>

Alongside, we use and develop computational software to implement our approaches.
These tools allow us to dramatically accelerate and expand the scope of our research, giving us more time for thinking and problem-solving (one of the best parts of being a computational scientist if you ask us!).
See the [Codes](/Codes.html) page for more details on the software developed in our group.

<a href="https://doped.readthedocs.io">
  <img src="https://raw.githubusercontent.com/SMTG-Bham/doped/main/docs/JOSS/doped_JOSS_workflow_figure.png">
</a>

- [ShakeNBreak: Navigating the defect configurational landscape](https://joss.theoj.org/papers/10.21105/joss.04817) _Journal of Open Source Software_ 2022
- [doped: Python toolkit for robust and repeatable charged defect supercell calculations](https://joss.theoj.org/papers/10.21105/joss.06433) _Journal of Open Source Software_ 2024
- [easyunfold: A Python package for unfolding electronic band structures](https://joss.theoj.org/papers/10.21105/joss.05974) _Journal of Open Source Software_ 2024


<br><br>
Some of these studies are showcased on Seán's [YouTube](https://www.youtube.com/c/Se%C3%A1nRKavanagh) channel!