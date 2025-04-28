---
title: "gFlora: a topology-aware method to discover functional co-response groups in soil microbial communities"
date: 2024-07-04 12:43:53 +0000
selected: true
pub: "IEEE Transactions on Computational Biology and Bioinformatics, "
# pub_pre: "Submitted to "
# pub_post: 'Under review.'
pub_last: '<span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date: "2024"

abstract: >-
  Microorganisms such as bacteria perform critical functions in the soil ecosystem: they mediate essential carbon, nitrogen, and nutrient cycling processes in soils. To manage the health and functions of soils, it is important to understand which soil functions are related the most to which microbial taxa—but this taxon-to-function link is difficult to discover because of the size and complexity of the soil ecosystem. A feasible solution is to discover functional links at the level of groups instead of individuals, using observational data of both taxa abundance and soil function indicators. We thus aim to learn the functional co-response group: a group of taxa whose co-response effect (the representative characteristic of the whole functional group) co-responds (associates well statistically) to a functional variable. Unlike the existing method, we model the soil microbial community as an ecological co-occurrence network with the taxa as nodes (weighted by their abundance) and their relationships (a combination from both spatial and functional ecological aspects) as edges (weighted by the strength of the relationships). Then, we design a method called gFlora which notably uses graph convolution over this co-occurrence network to compute the co-response effect of the group, such that the network topology is also considered in the discovery process. We evaluate gFlora on four real-world soil microbiome datasets (bacteria and nematodes combined with two soil functions: nitrogen mineralization and crop yield). gFlora outperforms the competing method on all evaluation metrics, and it discovers new functional evidence for taxa which were so far under-studied. We show that the graph convolution is crucial to taxa with relatively low abundance (thus removing the bias towards taxa with higher abundance), and the discovered bacteria of different genera are distributed in the co-occurrence network but remain tightly connected among themselves, demonstrating that topologically they fill different but collaborative functional roles in the ecological community.
cover: /assets/images/covers/gFlora.jpg
authors:
  - Nan Chen
  - Merlijn Schram
  - Doina Bucur
links:
  Paper: https://ieeexplore.ieee.org/abstract/document/10964872
  Code: https://github.com/nan-v-chen/gFlora
---
