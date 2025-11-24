---
title: "Dragon: Data-driven causal discovery for soils in the presence of latent and discrete variables"
date: 2025-11-15 12:43:53 +0000
selected: true
pub: "Ecological Informatics, "
# pub_pre: "Submitted to "
# pub_post: 'Under review.'
pub_last: '<span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date: "2025"

abstract: >-
  Understanding causal mechanisms in soils is essential for advancing sustainable soil management. However, this remains challenging due to the inherent complexity of soils and soil data, as well as the difficulty of intuitively disentangling the intricate interactions among diverse soil processes. To address this, we propose Dragon, a novel causal discovery method designed for soils. Dragon is a data-driven method that learns causal graphs directly from observed cross-sectional data, without relying on expert knowledge. It is mainly designed to handle two common challenges in soil datasets: the presence of latent (unobserved) and discrete variables. In particular, Dragon leverages Maximal Ancestral Graphs (MAGs) to represent causal structures that may involve latent confounding. In addition, it extends the Degenerate Gaussian (DG) score to the MAG setting to handle mixed data types. Dragon employs a greedy search to optimize the DG score with two variants: Dragon_GSMAG and Dragon_M3HC. We evaluate Dragon on both synthetic and real-world datasets. Specifically, on the synthetic datasets, Dragon_M3HC consistently achieves superior performance, with precision and recall reaching up to 0.61 and 0.70, respectively. On the real-world soil datasets, Dragon also uncovers relatively accurate and interpretable causal relationships that reflect known domain knowledge while also suggesting novel hypotheses. The learned causal graphs exhibit clear hierarchical structures, from management practices to functions, where management practices play leading roles in the graphs.
cover: /assets/images/covers/dragon.jpg
authors:
  - Nan Chen
  - E.R. Jasper Wubs
  - Doina Bucur
links:
  Paper: https://www.sciencedirect.com/science/article/pii/S1574954125005369
  Code: https://github.com/nan-v-chen/Dragon
---