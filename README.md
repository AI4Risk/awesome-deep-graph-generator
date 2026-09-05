[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/AI4Risk/awesome-deep-graph-generator)

# awesome-synthetic-graph-generator

- **Update**: This repository is actively updated. `2026/9/5`
- **Collection**: We've compiled a comprehensive list of synthetic graph generators.
- **Collaborate**: If there’s anything missing or if you'd like to contribute, please don't hesitate to get in touch!

## Contents

- [LLM-based Multi-Agent Simulation](#llm-based-multi-agent-simulation)
- [Learning based generative models](#Learning-based-generative-models)
- [Graph Autoencoders](#Graph-Autoencoders)
- [Traditional generative models](#Traditional-generative-models)
- [Configuration models](#Configuration-models)
- [Evaluation](#Evaluation)
- [Books](#Books)

## LLM-based Multi-Agent Simulation

#### LLM Multi-Agent Graph Generation

- **GRAPHIA: Harnessing Social Graph Data to Enhance LLM-Based Social Simulation**  
  Jiarui Ji, Zehua Zhang, Zhewei Wei, Bin Tong, Guan Wang, Bo Zheng  
  ACL 2026.  
  [Paper](https://arxiv.org/pdf/2510.24251) | [Code](https://github.com/Ji-Cather/Graphia)

- **LLM-Based Multi-Agent Systems are Scalable Graph Generative Models**  
  Jiarui Ji, Runlin Lei, Jialing Bi, Zhewei Wei, Xu Chen, Yankai Lin, Xuchen Pan, Yaliang Li, Bolin Ding  
  ACL 2025.  
  [Paper](https://aclanthology.org/2025.findings-acl.78.pdf) | [Code](https://github.com/Ji-Cather/GraphAgent)

- **SAMAG: Structure-Aware Multi-Agent Graph Generation with Large Language Models**  
  Jingcheng Cen, Jiarui Ji, Zhen Wang, Zhewei Wei, Yaliang Li, Bolin Ding  
  BigData 2025.  
  [Paper](https://ieeexplore.ieee.org/abstract/document/11402080)

#### LLM Multi-Agent Topology Construction

- **Dynamic Generation of Multi LLM Agents Communication Topologies with Graph Diffusion Models**  
  Eric Hanchen Jiang, Mengting Li, Guancheng Wan, Xiao Liang, Sophia Yin, Yuchen Wu, Xinfeng Li, Yizhou Sun, Wei Wang, Kai-Wei Chang, Ying Nian Wu  
  ACL 2026.  
  [Paper](https://aclanthology.org/2026.acl-long.1764/) | [Code](https://github.com/ericjiang18/diffusion_agent)

- **TopoDIM: One-shot Topology Generation of Diverse Interaction Modes for Multi-Agent Systems**  
  Rui Sun, Jie Ding, Chenghua Gong, Tianjun Gu, Yihang Jiang, Juyuan Zhang, Liming Pan, Linyuan Lü  
  Findings of ACL 2026.  
  [Paper](https://aclanthology.org/2026.findings-acl.207/) | [Code](https://github.com/Sundiasy/TopoDIM)

- **GoAgent: Group-of-Agents Communication Topology Generation for LLM-based Multi-Agent Systems**  
  Hongjiang Chen, Xin Zheng, Yixin Liu, Pengfei Jiao, Shiyuan Li, Huan Liu, Zhidong Zhao, Ziqi Xu, Ibrahim Khalil, Shirui Pan  
  arXiv 2026.  
  [Paper](https://arxiv.org/pdf/2603.19677)

- **ReSo: A Reward-driven Self-organizing LLM-based Multi-Agent System for Reasoning Tasks**  
  Heng Zhou, Hejia Geng, Xiangyuan Xue, Li Kang, Yiran Qin, Zhiyong Wang, Zhenfei Yin, Lei Bai  
  ACL 2025.  
  [Paper](https://aclanthology.org/2025.emnlp-main.808/) | [Code](https://github.com/hengzzzhou/ReSo)

## Learning based generative models

- **Bures-Wasserstein Flow Matching for Graph Generation**  
  Keyue Jiang, Jiahao Cui, Xiaowen Dong, Laura Toni  
  ICLR 2026.  
  [Paper](https://arxiv.org/abs/2506.14020)

- **HOG-Diff: Higher-Order Guided Diffusion for Graph Generation**  
  Yiming Huang, Tolga Birdal  
  ICLR 2026.  
  [Paper](https://arxiv.org/abs/2502.04308) | [Code](https://github.com/Yiminghh/HOG-Diff)

- **Efficient Dynamic Attributed Graph Generation**  
  Fan Li, Xiaoyang Wang, Dawei Cheng, Cong Chen, Ying Zhang, Xuemin Lin  
  ICDE 2025.  
  [Paper](https://arxiv.org/abs/2412.08810) | [Code](https://github.com/AI4Risk/GraphGenerator)

- **Efficient Learning-Based Graph Simulation for Temporal Graphs**  
  Sheng Xiang, Chenhao Xu, Dawei Cheng, Xiaoyang Wang, Ying Zhang  
  ICDE 2025.  
  [Paper](https://arxiv.org/abs/2510.05569) | [Code](https://github.com/AI4Risk/GraphGenerator)

- **Scalable Learning-Based Community-Preserving Graph Generation**  
  Sheng Xiang, Chenhao Xu, Dawei Cheng, Ying Zhang  
  TBD 2025.  
  [Paper](https://doi.org/10.1109/TBDATA.2025.3533898) | [Code](https://github.com/xiangsheng1325/SCPGAN)

- **Diffusion-Free Graph Generation with Next-Scale Prediction**  
  Samuel Belkadi, Steve Hong, Marian Chen, Miruna Cretu, Charles Harris, Pietro Lio  
  ICML 2025 GenBio Workshop.  
  [Paper](https://arxiv.org/pdf/2503.23612)

- **DeFoG: Discrete Flow Matching for Graph Generation**  
  Yiming Qin, Manuel Madeira, Dorina Thanou, Pascal Frossard  
  ICML 2025.  
  [Paper](https://arxiv.org/pdf/2410.04263) | [Code](https://github.com/manuelmlmadeira/DeFoG)

- **Variational Flow Matching for Graph Generation**  
  Floor Eijkelboom, Grigory Bartosh, Christian A. Naesseth, Max Welling, Jan-Willem van de Meent  
  NeurIPS 2024.  
  [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/15b780350b302a1bf9a3bd273f5c15a4-Paper-Conference.pdf) | [Code](https://github.com/vincenttsai2015/VFM_CatFlow)

- **SaGess: Sampling Graph Denoising Diffusion Model for Scalable Graph Generation**  
  Stratis Limnios, Praveen Selvaraj, Mihai Cucuringu, Carsten Maple, Gesine Reinert, Andrew Elliott  
  ECAI 2024.  
  [Paper](https://arxiv.org/abs/2306.16827) | [Code](https://github.com/Slimnios/SaGess)

- **Conditional Diffusion Based on Discrete Graph Structures for Molecular Graph Generation**  
  Han Huang, Leilei Sun, Bowen Du, Weifeng Lv  
  AAAI 2023.  
  [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25549) | [Code](https://github.com/GRAPH-0/CDGS)

- **Efficient and Degree-Guided Graph Generation via Discrete Diffusion Modeling**  
  Xiaohui Chen, Jiaxing He Xu Han, Li-Ping Liu  
  ICML 2023.  
  [Paper](https://arxiv.org/abs/2305.04111) | [Code](https://github.com/tufts-ml/graph-generation-EDGE)

- **FlowGEN: A Generative Model for Flow Graphs**  
  Furkan Kocayusufoglu, A. Silva, Ambuj K. Singh  
  KDD 2022.  
  [Paper](https://dl.acm.org/doi/10.1145/3534678.3539406)

- **Efficient Learning-based Community-Preserving Graph Generation**  
  Sheng Xiang, Dawei Cheng, Jianfu Zhang, Zhenwei Ma, Xiaoyang Wang, Ying Zhang  
  ICDE 2022.  
  [Paper](https://ieeexplore.ieee.org/document/9835281)

- **Scalable Deep Generative Modeling for Sparse Graphs**  
  Hanjun Dai, Azade Nazi, Yujia Li, Bo Dai, Dale Schuurmans  
  ICML 2020.  
  [Paper](https://arxiv.org/abs/2006.15502) | [Code](https://github.com/google-research/google-research/tree/master/bigg)

- **NetGAN without GAN: From Random Walks to Low-Rank Approximations**  
  Luca Rendsburg, Holger Heidrich, Ulrike Von Luxburg  
  ICML 2020.  
  [Paper](https://proceedings.mlr.press/v119/rendsburg20a.html) | [Code](https://github.com/sverdoot/netgan-without-gan)

- **Variational graph recurrent neural networks**  
  Ehsan Hajiramezanali, Arman Hasanzadeh, Nick Duffield, Krishna Narayanan, Mingyuan Zhou, Xiaoning Qian  
  NeurIPS 2019.  
  [Paper](https://dl.acm.org/doi/10.5555/3454287.3455247) | [Code](https://github.com/VGraphRNN/VGRNN)

- **Stochastic Blockmodels meet Graph Neural Networks**  
  Nikhil Mehta, Lawrence Carin Duke, Piyush Rai  
  ICML 2019.  
  [Paper](https://proceedings.mlr.press/v97/mehta19a.html) | [Code](https://github.com/lirt1231/SBM-meet-GNN-pytorch)

- **Graphite: Iterative Generative Modeling of Graphs**  
  Aditya Grover, Aaron Zweig, Stefano Ermon  
  ICML 2019.  
  [Paper](https://arxiv.org/pdf/1803.10459) | [Code](https://github.com/ermongroup/graphite)

- **Efficient Graph Generation with Graph Recurrent Attention Networks**  
  Renjie Liao, Yujia Li, Yang Song, Shenlong Wang, Will Hamilton, David Duvenaud, Raquel Urtasun, Richard Zemel  
  NeurIPS 2019.  
  [Paper](https://proceedings.neurips.cc/paper/2019/file/d0921d442ee91b896ad95059d13df618-Paper.pdf) | [Code](https://github.com/lrjconan/GRAN)

- **GraphRNN: Generating Realistic Graphs with Deep Auto-regressive Models**  
  Jiaxuan You, Rex Ying, Xiang Ren, William L. Hamilton, Jure Leskovec  
  ICML 2018.  
  [Paper](https://ar5iv.labs.arxiv.org/html/1802.08773) | [Code](https://github.com/JiaxuanYou/graph-generation)

- **NetGAN: Generating Graphs via Random Walks**  
  Aleksandar Bojchevski, Oleksandr Shchur, Daniel Zügner, Stephan Günnemann  
  ICML 2018.  
  [Paper](https://paperswithcode.com/paper/netgan-generating-graphs-via-random-walks) | [Code](https://github.com/danielzuegner/netgan)

## Graph Autoencoders

- **HAGGLE: Get a better deal using a Hierarchical Autoencoder for Graph Generation and Latent-space Expressivity**  
  Audun Myers, Stephen J. Young, Tegan Emerson  
  TAG-DS 2025 (published 2026).  
  [Paper](https://proceedings.mlr.press/v321/myers26a.html)

- **GraphMAE2: A Decoding-Enhanced Masked Self-Supervised Graph Learner**  
  Zhenyu Hou, Yufei He, Yukuo Cen, Xiao Liu, Yuxiao Dong, Evgeny Kharlamov, Jie Tang  
  WWW 2023.  
  [Paper](https://arxiv.org/abs/2304.04779) | [Code](https://github.com/THUDM/GraphMAE2)

- **GraphMAE: Self-Supervised Masked Graph Autoencoders**  
  Zhenyu Hou, Xiao Liu, Yukuo Cen, Yuxiao Dong, Hongxia Yang, Chunjie Wang, Jie Tang  
  KDD 2022.  
  [Paper](https://arxiv.org/abs/2205.10803) | [Code](https://github.com/THUDM/GraphMAE)

- **Adaptive Graph Encoder for Attributed Graph Embedding**  
  Ganqu Cui, Jie Zhou, Cheng Yang, Zhiyuan Liu  
  KDD 2020.  
  [Paper](https://arxiv.org/abs/2007.01594) | [Code](https://github.com/thunlp/AGE)

- **GPT-GNN: Generative Pre-Training of Graph Neural Networks**  
  Ziniu Hu, Yuxiao Dong, Kuansan Wang, Kai-Wei Chang, Yizhou Sun  
  KDD 2020.  
  [Paper](https://arxiv.org/abs/2007.01594) | [Code](https://github.com/acbull/GPT-GNN)

- **Adversarially Regularized Graph Autoencoder for Graph Embedding**  
  Shirui Pan, Ruiqi Hu, Guodong Long, Jing Jiang, Lina Yao, Chengqi Zhang  
  IJCAI 2018.  
  [Paper](https://arxiv.org/abs/1802.04407) | [Code](https://github.com/TrustAGI-Lab/ARGA)

- **MGAE: Marginalized Graph Autoencoder for Graph Clustering**  
  Chun Wang, Shirui Pan, Guodong Long, Xingquan Zhu, Jing Jiang  
  CIKM 2017.  
  [Paper](https://dl.acm.org/doi/10.1145/3132847.3132967) | [Code](https://github.com/TrustAGI-Lab/MGAE/tree/master)

- **Variational Graph Auto-Encoders**  
  Thomas N. Kipf, Max Welling  
  NeurIPS 2016.  
  [Paper](https://arxiv.org/abs/1611.07308) | [Code](https://github.com/tkipf/gae)

## Traditional generative models

- **A Scalable Generative Graph Model with Community Structure**  
  Tamara G. Kolda, Ali Pinar, Todd Plantenga, C. Seshadhri  
  SIAM 2014.  
  [Paper](https://arxiv.org/abs/1302.6636)

- **Community Detection in Networks with Node Attributes**  
  Jaewon Yang, Julian McAuley, Jure Leskovec  
  ICDM 2013.  
  [Paper](https://arxiv.org/abs/1401.7267)

- **Kronecker Graphs: An Approach to Modeling Networks**  
  Jure Leskovec, Deepayan Chakrabarti, Jon Kleinberg, Christos Faloutsos, Zoubin Ghahramani  
  JMLR 2010.  
  [Paper](https://www.jmlr.org/papers/volume11/leskovec10a/leskovec10a.pdf)

- **Community detection in graphs (Stochastic BlockModels)**  
  Santo Fortunato  
  Physics Reports 2010.  
  [Paper](https://arxiv.org/abs/0906.0612)

- **R-MAT: A Recursive Model for Graph Mining**  
  Deepayan Chakrabarti, Yiping Zhan, Christos Faloutsos  
  SIAM 2004.  
  [Paper](https://epubs.siam.org/doi/abs/10.1137/1.9781611972740.43)

## Configuration models

- **Erdős–Rényi model**  
  P. Erdős, A. Rényi (Budapest).  
  Publicationes Mathematicae 1959.  
  [Paper](https://www.renyi.hu/~p_erdos/1959-11.pdf)

## Evaluation

- **On the Role of Edge Dependency in Graph Generative Models**  
  Sudhanshu Chanpuriya, Cameron Musco, Konstantinos Sotiropoulos, Charalampos Tsourakakis  
  arXiv 2023.  
  [Paper](https://arxiv.org/abs/2312.03691)

- **On the Power of Edge Independent Graph Models**  
  Sudhanshu Chanpuriya, Cameron Musco, Konstantinos Sotiropoulos, Charalampos E. Tsourakakis  
  NeurIPS 2021.  
  [Paper](https://arxiv.org/abs/2111.00048)

## Books

- **Inductive Bias in Machine Learning**  
  Luca Silvester Rendsburg  
  arXiv 2023.  
  [Book](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=h48H5WEAAAAJ&citation_for_view=h48H5WEAAAAJ:zYLM7Y9cAGgC)

## All Thanks to Our Contributors :

<a href="https://github.com/AI4Risk/awesome-deep-graph-generator/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=AI4Risk/awesome-deep-graph-generator" />
</a>
