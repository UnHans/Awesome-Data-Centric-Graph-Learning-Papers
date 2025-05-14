# <img src="https://github.com/OpenGSL/OpenGSL/blob/main/docs/source/img/opengsl.jpg" width="90"> Awesome Data-Centric Graph Learning Papers 
[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
>An awesome&amp;curated list of the advanced data-centric graph (i.e.,graph sparsification,graph data denoise,graph condensation) learning papers(2023-present) with summaries. We will track the development of graph data-centric learning and update the list frequently. :pray:**Please star us if you found our repository helpful**. :pray:

> We have developed [OpenGSL](https://github.com/OpenGSL/OpenGSL), a fair and comprehensive platform to evaluate existing GSL works and facilitate future GSL research. **Please star us and explore our project if you found our repositories helpful**.

## 2025
- **[ICLR 2025|Node Selection|Graph Condensation]** [Bonsai: Gradient-free Graph Condensation for Node Classification
](https://arxiv.org/abs/2410.17579) This paper aims to select representative and diverse nodes from the training set to accelerate GNN training.
- **[Arxiv 2025|LLM4GSL]** [Rethinking Graph Structure Learning in the Era of LLMs](https://arxiv.org/abs/2408.07191).
- **[KDD 2025|LLM+GSL]** [Can Large Language Models Improve the Adversarial Robustness of Graph Neural Networks?](https://arxiv.org/abs/2408.08685)  training an LM-based edge predictor for robustness GNN.
- **[Arxiv 2025|Pure LLM+Prompt for Graph learning]** [Exploring Graph Tasks with LLMs: A Comprehensive Benchmark and Investigation](https://arxiv.org/abs/2502.18771) A pure LLM, combined with appropriate prompts, can outperform various GNN models.
- **[WWW 2025|Structure Refinement]** [Uncertainty-aware Graph Structure Learning](https://arxiv.org/abs/2502.12618) proposes a lightweight plug-in module, UnGSL, that can be seamlessly integrated into SOTA GSL models to enhance their accuracy and robustness. UnGSL is both simple and effective; it employs node-wise learnable thresholds to differentiate neighbors based on varying confidence levels and adaptively adjusts the corresponding edge weights.
- **[ICLR 2025|Structure Sparsification]** [Graph Sparsification via Mixture of Graphs](https://arxiv.org/abs/2405.14260) proposes a MoE-based sparsification framework that combines multiple sparsification approaches.
- **[ICLR 2025|Structure and Feature Denoise]** [Joint Graph Rewiring and Feature Denoising via Spectral Resonance](https://arxiv.org/abs/2405.14260).
- **[ICLR 2025|Graph Feature Selection]** [Let Your Features Tell The Differences: Understanding Graph Convolution By Feature Splitting](https://iclr.cc/virtual/2025/poster/30186).
- **[Arxiv 2025 Graph Uncertainty]** [Uncertainty in Graph Neural Networks: A Survey](https://arxiv.org/abs/2403.07185).
## 2024
- **[KDD 2024|Graph Domain Adaptation]** [Can Modifying Data Address Graph Domain Adaptation?](https://arxiv.org/abs/2407.19311)
- **[NIPS 2024 Graph Condensation]** [GC-Bench: An Open and Unified Benchmark for Graph Condensation](https://arxiv.org/abs/2407.00615) introduce a benchmark for graph condensation methods.
- **[Arxiv 2024 Sparsification|Condensation]** [Data-centric Graph Learning: A Survey](https://arxiv.org/abs/2310.04987).
- **[Arxiv 2024 LLM4GSL]** [Bridging Large Language Models and Graph Structure Learning Models for Robust Representation Learning](https://arxiv.org/abs/2410.12096) first utilizes a large language model (LLM) to derive cleaned node text information, and then adopts an iterative learning paradigm along with a pseudo-labeling strategy to incorporate text features into the structural representation.
- **[Arxiv 2024 LLM4GSL]** [GraphEdit: Large Language Models for Graph Structure Learning](https://arxiv.org/abs/2402.15183) utilize a text classification task to fine-tune the text encoder in the LLM, and then use the pretrained text embeddings to construct the learned graph.
- **[CIKM 2024|Structure Refinement&Feature Denoising]** [You Can't Ignore Either: Unifying Structure and Feature Denoising for Robust Graph Learning](https://arxiv.org/abs/2408.00700) remove noise from structural features and node attribute features.
- **[Arxiv 2024|Structure Refinement Theory]** [Rethinking Structure Learning For Graph Neural Networks](https://arxiv.org/abs/2411.07672) This paper analyzes the mutual information between node representations in learned graphs and their corresponding labels, and claims that the predominant similarity-based GSL models is unnecessary for GNNs.
- **[NIPS 2024|Heterogeneous Structure Refinement]** [Beyond Redundancy: Information-aware Unsupervised Multiplex Graph Structure Learning](https://arxiv.org/abs/2409.17386) deal with heterophily node classification datasets.[[Code](https://github.com/zxlearningdeep/InfoMGF)]
- **[WWW 2024|Structure Refinement]** [Self-Guided Robust Graph Structure Refinement](https://dl.acm.org/doi/10.1145/3589334.3645522) propose to extract clean subgraphs and refine the extracted graph structure by leveraging both topological and feature similarity. Additionally, it employ a degree-based group training strategy to address the unbalanced degree distribution.[[Code](https://github.com/yeonjun-in/torch-SG-GSR)]
- **[WWW 2024|Structure Refinement]**[DSLR: Diversity Enhancement and Structure Learning for Rehearsal-based Graph Continual Learning](https://dl.acm.org/doi/10.1145/3589334.3645561)
## 2023
- **[NIPS 2023|Structure Sparsification]** [On the Ability of Graph Neural Networks to Model Interactions Between Vertices](https://proceedings.neurips.cc/paper_files/paper/2023/hash/543ec10715d964122ab7cb15f648772b-Abstract-Conference.html) first propose a novel graph characteristic, the walk index, which reflects interactions between two groups.Then, it develop the Walk Index Sparsification (WIS) algorithm, a graph structure sparsification method that removes noise edges potentially lowering the walk index between the two groups.[[Code](https://github.com/noamrazin/gnn_interactions)]
- **[ICLR 2023|TTA+Structure Refinement+Feature Denoise]** [Empowering Graph Representation Learning with Test-Time Graph Transformation](https://openreview.net/pdf?id=Lnxl5pr018) incorporate a learnable perturbation matrix with the graph adjacency matrix and adopt a self-supervised contrastive loss as a surrogate to perform optimization at test time. This approach can mitigates distribution shifts between training data and test data.[[Code](https://github.com/ChandlerBang/GTrans)]
- **[NIPS 2023|Structure Refinement]**[Optimal Block-wise Asymmetric Graph Construction for Graph-based Semi-supervised Learning](https://proceedings.neurips.cc/paper_files/paper/2023/hash/e142fd2b70f10db2543c64bca1417de8-Abstract-Conference.html) construct an asymmetric graph structure that maintains indirect connections from labeled nodes to unlabeled nodes, enhancing the propagation of supervised signals on unlabeled data. Notably, this paper aims to perform Graph Structure Learning (GSL) in the absence of an initial graph structure.
- **[NIPS 2023|Structure Refinement]**[Latent Graph Inference with Limited Supervision](https://proceedings.neurips.cc/paper_files/paper/2023/hash/67101f97dc23fcc10346091181fff6cb-Abstract-Conference.html) aims to reduce the occurrence of starved nodes(nodes with mutiple unlabeled high-order neighbors) in the graph structure. It construct a similarity matrix between labeled and unlabeled nodes and fuse it with the original graph structure matrix to enhance the propagation of supervised signals to unlabeled data.[[Code](https://github.com/Jianglin954/LGI-LS)]
- **[NIPS 2023|Graph Curriculum Learning]**[Curriculum Learning for Graph Neural Networks: Which Edges Should We Learn First](https://github.com/rollingstonezz/Curriculum_learning_for_GNNs) utilize a Variational Autoencoder (VAE) to recover the graph structure and sort edges using residual loss. Subsequently, it progressively train a GNN by feeding it easier edges(edge with lower residual loss). In this way, the GNN are well-trained and focus on optimizing performance on good structure data.[[Code](https://github.com/rollingstonezz/Curriculum_learning_for_GNNs)]
- **[NIPS 2023|Structure Refinement+Recommendation]**[Contrastive Graph Structure Learning via Information Bottleneck for Recommendation](https://proceedings.neurips.cc/paper_files/paper/2022/hash/803b9c4a8e4784072fdd791c54d614e2-Abstract-Conference.html) aims to address popularity bias in recommendation systems. First, it introduces a multi-view (node- and edge-drop) graph augmentation technique to eliminate noise structures. Then, it employs an information bottleneck approach to minimize mutual information between original features and augmented features, which can learn invariant information related to labels.[[Code](https://github.com/weicy15/CGI)]
- **[ICML 2023|Structure Refinement]**[Beyond Homophily: Reconstructing Structure for Graph-agnostic Clustering](https://proceedings.mlr.press/v202/pan23b/pan23b.pdf) aims to adaptively address graph structures with varying levels of homophily. It begins by transforming the graph into homogeneous and heterogeneous graphs. Next, it employs mixed-pass filters to encode graph structure features. Finally, dual encoders are utilized to separately learn attribute and topological features.[[Code](https://github.com/Panern/DGCN)]
- **[ICML 2023|Structure Refinement]** [Towards Understanding and Reducing Graph Structural Noise for GNNs](https://proceedings.mlr.press/v202/dong23a.html)
- **[KDD 2023|Structure Refinement]**[PROSE: Graph Structure Learning via Progressive Strategy](https://dl.acm.org/doi/abs/10.1145/3580305.3599476) aims to progressively identify influential nodes using PageRank scores and reconstruct the graph structure by connecting these influential nodes. This approach prioritizes connecting important nodes within graph. [[Code](https://github.com/tigerbunny2023/PROSE)]
- **[KDD 2023|Structure Refinement+OOD]**[GraphGLOW: Universal and Generalizable Structure Learning for Graph Neural Networks](https://dl.acm.org/doi/abs/10.1145/3580305.3599373) This paper aims to learn invariant structural information across diverse graph datasets. The model includes a structure learner and multiple Graph Neural Networks (GNNs) tailored to different graph structures. To streamline structure refinement complexity, the model employs the pivot node trick, avoiding the $O(N^2)$ complexity.[[Code](https://github.com/WtaoZhao/GraphGLOW)]
## Contributors
<!-- readme: collaborators,contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/zzysh12345">
            <img src="https://avatars.githubusercontent.com/u/60538191?v=4" width="120;" alt="hilinxinhui"/>
            <br />
            <sub><b>zzysh12345</b></sub>
        </a>
    </td>
     <td align="center">
        <a href="https://github.com/UnHans">
            <img src="https://avatars.githubusercontent.com/u/71540260?v=4" width="120;" alt="hilinxinhui"/>
            <br />
            <sub><b>UnHans</b></sub>
        </a>
    </td>
</tr>
</table>
<!-- readme: collaborators,contributors -end -->
