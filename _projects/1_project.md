---
layout: page
title: Galaxy Clusters in the CFHTLS
description: Detection and galaxy luminosity funtion of clusters in the CFHTLS survey
img: assets/img/Sarron2018_illustration.png
importance: 1
category: work
related_publications: true
---

In 2016-2017, early in my PhD, I designed an algorithm called the Adami, MAzure and Sarron Cluster FInder (AMASCFI) to detect clusters of galaxies using large photometric surveys.
The main idea behind AMASCFI is to look for overdensities in overlapping redshift slices of the galaxy catalogue and then merge them into cluster candidates using a friend-of-friend algorithm. A mass estimate of the cluster candidates is derived a posterori using a scaling relation with the cluster richness.
The algorithm was built to handle large data sets such as Euclid or the Rubin Large Synoptic Survey Telescope (LSST), particularly using parallel programming on computer clusters.

I successfully applied AMASCFI to the full 154 deg2 of the CFHTLS in Sarron et al. (2018). We detected 7100 cluster candidates up to z = 1.1. The cluster candidate catalogue is publicly available on the VizieR portal.

Details on the AMASCFI algorithm, its selection function and the CFHTLS cluster candidate catalogue can be found in {% cite Sarron2018 %}.