---
layout: page
title: Cosmic web filaments in the CFHTLS
description: On the detection of cosmic filaments around cluster using photometric surveys. Constraints on galaxy quenching in filaments connected to clusters.
img: assets/img/Sarron2019_illustration.png
importance: 1
category: Astrophysics
related_publications: true
---

In the hierarchical model struture formation in the Universe, matter aggregates in larger and larger structures over cosmic time. In particular, galaxy clusters, the most dense and massive of these large-scale structures happen to be located at the intersection of large cosmic filaments. Matter fall along these filaments into the gravitotional potential well of the cluster, either as isolated galaxies, or as galaxies already in smaller galaxy groups.

Yet, living in groups or cosmic filaments affect galaxy properties. In particular, their star-formation process can be stopped (quenching). Hence, it is beleived that the part of the large fraction of quenched galaxies observed in clusters in the present day Universe could have quenched before they enter these clusters. This phenomenon is referred to as _pre-processing_. In 2018, when this work started, the relative importance of this pre-processing was yet unclear.

As part of my PhD work, in {% cite Sarron2019 %} we focused on this aspect. We did so using a large photometric survey (CFHTLS), with the idea that this could give us interesting insights thanks to the cosmic volume covered by the survey, and despite the inherent noisiness of galaxy distance measures in such data. This choice was made building upon the great pioneer work of [Laigle et al., 2018](https://ui.adsabs.harvard.edu/abs/2018MNRAS.474.5437L) that showed the effect of cosmic filaments could be recovered in COSMOS photometric data.

We adapted the method to detect cosmic filaments around AMASCFI clusters in the CFHTLS survey, for which the photometric redshift are less precise than in COSMOS. The method consists in looking for filaments in the two-dimensional projected galaxy distribution in photometric redshift slices. The filament detection is done with DisPerSE ([Sousbie, 2011](https://ui.adsabs.harvard.edu/abs/2011MNRAS.414..350S)), a ridge finder algorithm.  
We showed that cosmic filaments effects could be _statistically_ recovered for regime of multiband photometric surveys where the uncertainty of the photometric redshift is $$\sigma_{\rm NMAD} \leq 0.03 \times (1 + z)$$.

We then studied the fraction of quenched galaxies in the detected candidate cosmic filaments in the vicinity of galaxy clusters. We showed that in our CFHTLS data:

1. the fraction of quenched galaxies around clusters is higher in filaments than in random regions up to $$d \sim 5 {\rm cMpc}$$,
2. this fraction decreases as one gets further away for the clusters, both in filaments and random regions.

---

This work lead us to start a project inside the _Euclid_ consortium together with Clotilde Laigle and Ulrike Kuchner in 2020 on the role of the cosmic web role in driving galaxy evolution, and what can be inferred about it with _Euclid_ data. A project on which later joined Pascale Jablonka, Nicola Malavasi, Michael Balogh, Katarina Kraljic among others.  
This team work has lead to many interesting methodological developments, some of them will be featured in publications of the Euclid consortium in 2024, and we now have a better view of what will be reachable with _Euclid_ data in the years to come.
