# <img src="https://github.com/OpenGSL/OpenGSL/blob/main/docs/source/img/opengsl.jpg" width="90"> Awesome Graph Structure Learning Papers 
[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
>An awesome&amp;curated list of the advanced graph structure learning papers(2023-present) with summaries.

> \*We have developed [OpenGSL](https://github.com/OpenGSL/OpenGSL), a fair and comprehensive platform to evaluate existing GSL works and facilitate future GSL research.Please feel free to explore and contribute our project.

## 2024
- [WWW 2024] [Self-Guided Robust Graph Structure Refinement](https://dl.acm.org/doi/10.1145/3589334.3645522) propose to extract clean subgraphs and refine the extracted graph structure by leveraging both topological and feature similarity. Additionally, it employ a degree-based group training strategy to address the unbalanced degree distribution.[[Code](https://github.com/yeonjun-in/torch-SG-GSR)]
## 2023
- [NIPS 2023] [On the Ability of Graph Neural Networks to Model Interactions Between Vertices](https://proceedings.neurips.cc/paper_files/paper/2023/hash/543ec10715d964122ab7cb15f648772b-Abstract-Conference.html) first propose a novel graph characteristic, the walk index, which reflects interactions between two groups.Then, it develop the Walk Index Sparsification (WIS) algorithm, a graph structure sparsification method that removes noise edges potentially lowering the walk index between the two groups.[[Code](https://github.com/noamrazin/gnn_interactions)]
- [ICLR 2023] [Empowering Graph Representation Learning with Test-Time Graph Transformation](https://openreview.net/pdf?id=Lnxl5pr018) incorporate a learnable perturbation matrix with the graph adjacency matrix and adopt a self-supervised contrastive loss as a surrogate to perform optimization at test time. This approach can mitigates distribution shifts between training data and test data.[[Code](https://github.com/ChandlerBang/GTrans)]
- [NIPS 2023][Optimal Block-wise Asymmetric Graph Construction for Graph-based Semi-supervised Learning](https://proceedings.neurips.cc/paper_files/paper/2023/hash/e142fd2b70f10db2543c64bca1417de8-Abstract-Conference.html) construct an asymmetric graph structure that maintains indirect connections from labeled nodes to unlabeled nodes, enhancing the propagation of supervised signals on unlabeled data. Notably, this paper aims to perform Graph Structure Learning (GSL) in the absence of an initial graph structure.
- 
