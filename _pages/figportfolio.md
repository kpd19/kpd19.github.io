---
layout: splash
author_profile: false
header:
  image: "/assets/images/Lupes3.png"
  caption: "*Beehive Reservoir, Washington*"
permalink: /portfolio
---

## Portfolio of a selection of figures I've created over the years of my research projects

The Douglas-fir tussock moth is a native defoliator in Western North America, which primarily feeds on Douglas-fir (*Pseudotsuga menziesii*) and True firs (*Abies* spp.). The insect can cause extensive amounts of forest damage during outbreaks, when the insect reaches very high densities. The insect population is naturally controlled by widespread infection by a virus, which has two types. The  This figure shows the range of the tree species the insect feeds on, along with the geographic distribution of two types of the virus that infect the Douglas-fir tussock moth (pie charts) across Western North America.
The *Abies* distribution is created by combining the distributions of all trees in the genus. 
The viral subtypes information is a combination of extensive field collections of virus collected caterpillars and historical data reported in the literature.
The pie charts are created by first spatially clustering locations across the distribution before calculating the proportion of insects that are infected by a specific type. 
This figure was created by manipulating shapefiles and dataframes in R using the packages <code>sf</code>, <code>geodata</code>, <code>scatterpie</code>, and <code>tidyverse</code>.

<img align="center" width="75%" src="/assets/images/morph_dist_map.png">

Forest managers occasionally use species-specific biocontrol to manage outbreaks of the Douglas-fir tussock moth, to prevent high levels of forest damage. They currently only use one viral subtype in the biocontrol. This figure shows the simulated effectiveness of using bicontrol to manage the Douglas-fir tussock moth population for three biocontrol types: 100\% of the multi-capsid morphotype, 100\% of the single-capsid morphotype, and a 50-50 combination of the two. The effectiveness is measured as a percent change in the Douglas-fir (host) population, with more negative values meaning the insect population was decreased more. The figure shows the reduction in population for these types across a range of forest compositions (\% Douglas-fir) and range of likelihoods of forest managers conducting the spray (0-1), since it's very costly to perform. The results show that the viral composition of the biocontrol matters greatly, with the mixture being the most effective. The forest composition also matters, with the biocontrol being less effective in high \% Douglas-fir forests. This is due to a complicated interaction between the insect host, the virus, and the trees the insects are feeding on. 

<img align="center" width="75%" src="/assets/images/spray_effectiveness_percent2.pdf">

