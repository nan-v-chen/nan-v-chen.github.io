---
title: "EleMi: A Robust Method to Infer Soil Ecological Networks with Better Community Structure"
date: 2024-04-14 00:01:00 +0100
selected: true
pub: "International Conference on Complex Networks (CompleNet), "
pub_date: "2024"
abstract: >-
  Soil ecological networks enable us to better understand the complex interactions among a great number of organisms in soil. Soil communities are biotic groups with similar environmental and resource preferences. Community detection thus provides insights into the mechanisms of the soil ecosystem. Therefore, inferring ecological networks with clear community structure is essential for investigating the soil ecosystem. We propose Elastic net regularized Multi-regression (EleMi), a new method to infer soil ecological networks. To better find the community structure, EleMi does not infer pairwise interactions, but considers all organisms simultaneously. Specifically, it regresses the abundance of all other taxa to one taxon (with shared parameters across soil samples) and employs Elastic net to avoid over-sparsity and stochasticity. The results on both synthetic and real biotic data show that EleMi is more robust and can infer ecological networks with clearer community structure.
cover: /assets/images/covers/elemi.jpg
authors:
  - Nan Chen
  - Doina Bucur
links:
  Paper: https://link.springer.com/chapter/10.1007/978-3-031-57515-0_13
  Code: https://github.com/nan-v-chen/EleMi
---