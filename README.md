## Papers on Topology + Learning.

A biased list of papar on the application of topology in machine learning. Feel free to suggest related paper. I will add them gradually. 

### Content
1. [Survey Papers/Books ](#survey-papers)
2. [Persistence Diagram for ML ](#models)
    1. [Vector method](#kernel-method)
    1. [Kernel method](#kernel-method)
    1. [Others](#Others)
3. [Applications](#applications)
    1. [Graph Classification ](#graph-classification)
    1. [Neural Network](#neural-network)
    1. [Natural Language Processing](#natural-language-processing)
    1. [Vision](#vision)

### [Survey Papers](#content)

1. **Computational topology: an introduction**
*Herbert Edelsbrunner and John Harer* [book](https://www.maths.ed.ac.uk/~v1ranick/papers/edelcomp.pdf)

1. **Persistence Theory: From Quiver Representations to Data Analysis**
  *Steve Y. Oudot* [book](https://geometrica.saclay.inria.fr/team/Steve.Oudot/books/o-pt-fqrtda-15/surv-209.pdf)

1. **Topology and data**
*Gunnar Carlsson* [paper](https://www.ams.org/journals/bull/2009-46-02/S0273-0979-09-01249-X/)

1. **Elementary Applied Topology**
*Robert Ghrist* [book](https://www.math.upenn.edu/~ghrist/notes.html)

1. **A roadmap for the computation of persistent homology**
*Nina Otter, Mason A. Porter, Ulrike Tillmann, Peter Grindrod, Heather A. Harrington* [paper](https://arxiv.org/abs/1506.08903)


### [Persistence Diagram for ML](#content)

#### [Vector method](#content)
1. **A persistence landscapes toolbox for topological statistics**
   *Peter Bubenik, Pawel Dlotko* [paper](https://arxiv.org/abs/1501.00179)
1. **Stable topological signatures for points on 3D shapes**
*Mathieu Carrière, Steve Yann Oudot, Maks Ovsjanikov* Computer Graphics Forum 2015  [paper](https://dl.acm.org/doi/10.1111/cgf.12692)
1. **Stochastic Convergence of Persistence Landscapes and Silhouettes**
*Frédéric Chazal, Brittany Terese Fasy, Fabrizio Lecci, Alessandro Rinaldo, Larry Wasserman* SoCG 2014 [paper](https://arxiv.org/abs/1312.0308)
1. **Persistence Images: A Stable Vector Representation of
  Persistent Homology**
  *Henry Adams, Sofya Chepushtanova, Tegan Emerson, Eric Hanson, Michael Kirby, Francis Motta, Rachel Neville, Chris Peterson, Patrick Shipman, and Lori Ziegelmeier* JMLR 2017 [paper](http://www.jmlr.org/papers/volume18/16-337/16-337.pdf)

#### [Kernel method](#content)

1. **Sliced wasserstein kernel for persistence diagrams**
*Mathieu Carriere and Marco Cuturi and Steve Oudot*  ICML 2017 [paper](https://arxiv.org/abs/1706.03358)

1. **Persistence weighted Gaussian kernel for topological data analysis**
*Genki Kusano, Yasuaki Hiraoka and Kenji Fukumizu* ICML 2016 [paper](https://arxiv.org/abs/1601.01741)

1. **A stable multi-scale kernel for topological machine learning**
*Jan Reininghaus, Stefan Huber, Ulrich Bauer, Roland Kwitt* CVPR 2015 [paper](https://arxiv.org/abs/1412.6821)

1. **Persistence Fisher Kernel: A Riemannian Manifold Kernel for Persistence Diagrams**
*Tam Le, Makoto Yamada* NeurIPS 2018 [paper](https://arxiv.org/abs/1802.03569)

1. **On the Metric Distortion of Embedding Persistence Diagrams into separable Hilbert spaces**

  *Mathieu Carriere, Ulrich Bauer* SoCG 2019 [paper](https://arxiv.org/abs/1806.06924)

1. **Learning metrics for persistence-based summaries and applications for graph classification**
*Qi Zhao, Yusu Wang* NeurIPS 2019 [paper](https://arxiv.org/abs/1904.12189)

#### [Others](#content)
1. **PersLay: A Neural Network Layer for Persistence Diagrams and New Graph Topological Signatures**
*Mathieu Carrière, Frédéric Chazal, Yuichi Ike, Théo Lacombe, Martin Royer, Yuhei Umeda* AISTATS 2010 [paper](https://arxiv.org/abs/1904.09378)

1. **Understanding the Power of Persistence Pairing via Permutation Test**
*Chen Cai, Yusu Wang* Arxiv 2020 [paper](https://arxiv.org/abs/2001.06058)

### [Applications](#content)
#### [Graph Classification](#content)

1. **Deep Learning with Topological Signatures**
*Christoph Hofer, Roland Kwitt, Marc Niethammer, Andreas Uhl* NeurIPS 2018 [paper](https://arxiv.org/abs/1707.04041)

1. **A Persistent Weisfeiler-Lehman Procedure for Graph Classification**
*Bastian Rieck, Christian Bock, Karsten Borgwardt* ICML 2019 [paper](http://proceedings.mlr.press/v97/rieck19a.html)

#### [Neural Network](#content)

1. **A Topology Layer for Machine Learning**
*Rickard Brüel-Gabrielsson, Bradley J. Nelson, Anjan Dwaraknath, Primoz Skraba, Leonidas J. Guibas, Gunnar Carlsson*  Arxiv 2019 [paper](https://arxiv.org/abs/1905.12200)
1. **Topological Autoencoders**
*Michael Moor, Max Horn, Bastian Rieck, Karsten Borgwardt* Arxiv 2019 [paper](https://arxiv.org/abs/1906.00722)
1. **Characterizing the Shape of Activation Space in Deep Neural Networks**
*Thomas Gebhart, Paul Schrater, Alan Hylton* Arxiv 2019 [paper](https://arxiv.org/abs/1901.09496)
1. **Neural Persistence: A Complexity Measure for Deep Neural Networks Using Algebraic Topology**
*Bastian Rieck, Matteo Togninalli, Christian Bock, Michael Moor, Max Horn, Thomas Gumbsch, Karsten Borgwardt* ICLR 2019 [paper](https://arxiv.org/abs/1812.09764)
1. **Empirical study of the topology and geometry of deep networks**
*Alhussein Fawzi ; Seyed-Mohsen Moosavi-Dezfooli ; Pascal Frossard; Stefano Soatto* CVPR 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Fawzi_Empirical_Study_of_CVPR_2018_paper.pdf)
1. **Topology and Geometry of Half-Rectified Network Optimization**
*C. Daniel Freeman, Joan Bruna* ICLR 2017 [paper](https://arxiv.org/abs/1611.01540)
1. **Topological Data Analysis of Decision Boundaries with Application to Model Selection**
*Karthikeyan Natesan Ramamurthy, Kush R. Varshney, Krishnan Mody*  ICML 2019 [paper](https://arxiv.org/abs/1805.09949)
1. **A Topological Regularizer for Classifiers via Persistent Homology**
*Chao Chen, Xiuyan Ni, Qinxun Bai, Yusu Wang* AISTATS 2019 [paper](https://arxiv.org/abs/1806.10714)

1. **Connectivity-Optimized Representation Learning via Persistent Homology**
*Christoph Hofer, Roland Kwitt, Marc Niethammer, Mandar Dixit* ICML 2019 [paper](http://proceedings.mlr.press/v97/hofer19a.html)

1. **Topology of deep neural networks**
*Gregory Naitzat, Andrey Zhitnikov, Lek-Heng Lim* [paper](https://openreview.net/forum?id=SkgBfaNKPr)

#### [Natural Language Processing](#content)
1. **Does the Geometry of Word Embeddings Help Document Classification? A Case Study on Persistent Homology Based Representations**
*Paul Michel, Abhilasha Ravichander, Shruti Rijhwani* [paper](https://arxiv.org/abs/1705.10900)

#### [Vision](#content)
1. **Topology-Preserving Deep Image Segmentation**
*Xiaoling Hu, Li Fuxin, Dimitris Samaras, Chao Chen* NeurIPS 2019 [paper](https://arxiv.org/abs/1906.05404)


### [Event](#content)

1. **AI Institute “Geometry of Deep Learning” 2019**
   [Link](https://www.microsoft.com/en-us/research/event/ai-institute-2019/)