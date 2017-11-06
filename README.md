## Must-read papers on NRL/NE.
NRL: network representation learning. NE: network embedding.

Contributed by [Cunchao Tu](http://thunlp.org/~tcc/) and Yuan Yao.

We release [OpenNE](https://github.com/thunlp/openne), an open source toolkit for NE/NRL. This repository provides a standard NE/NRL(Network Representation Learning）training and testing framework. Currently, the implemented models in OpenNE include DeepWalk, LINE, node2vec, GraRep, TADW and GCN.

### Survey papers:

1. **Representation Learning on Graphs: Methods and Applications.**
*William L. Hamilton, Rex Ying, Jure Leskovec* 2017. [paper](https://arxiv.org/pdf/1709.05584.pdf)

1. **Graph Embedding Techniques, Applications, and Performance: A Survey.**
*Palash Goyal, Emilio Ferrara* 2017. [paper](https://arxiv.org/pdf/1705.02801.pdf)

1. **A Comprehensive Survey of Graph Embedding: Problems, Techniques and Applications.**
*Hongyun Cai, Vincent W. Zheng, Kevin Chen-Chuan Chang* 2017. [paper](https://arxiv.org/pdf/1709.07604.pdf)

### Journal and Conference papers:

1. **DeepWalk: Online Learning of Social Representations.**
*Bryan Perozzi, Rami Al-Rfou, Steven Skiena.*  KDD 2014. [paper](https://arxiv.org/pdf/1403.6652) [code](https://github.com/phanein/deepwalk)

1. **Learning Latent Representations of Nodes for Classifying in Heterogeneous Social Networks.**
*Yann Jacob, Ludovic Denoyer, Patrick Gallinar.* WSDM 2014. [paper](http://webia.lip6.fr/~gallinar/gallinari/uploads/Teaching/WSDM2014-jacob.pdf)

1. **Non-transitive Hashing with Latent Similarity Componets.**
*Mingdong Ou, Peng Cui, Fei Wang, Jun Wang, Wenwu Zhu.*  KDD 2015. [paper](http://media.cs.tsinghua.edu.cn/~multimedia/cuipeng/papers/KDD-NonTransitiveHashing.pdf)

1. **GraRep: Learning Graph Representations with Global Structural Information.**
*Shaosheng Cao, Wei Lu, Qiongkai Xu.*  CIKM 2015. [paper](https://www.researchgate.net/profile/Qiongkai_Xu/publication/301417811_GraRep/links/5847ecdb08ae8e63e633b5f2/GraRep.pdf) [code](https://github.com/ShelsonCao/GraRep)

1. **LINE: Large-scale Information Network Embedding.**
*Jian Tang, Meng Qu, Mingzhe Wang, Ming Zhang, Jun Yan, Qiaozhu Me.*  WWW 2015. [paper](https://arxiv.org/pdf/1503.03578.pdf) [code](https://github.com/tangjianpku/LINE)

1. **Network Representation Learning with Rich Text Information.**
*Cheng Yang, Zhiyuan Liu, Deli Zhao, Maosong Sun, Edward Y. Chang.*  IJCAI 2015. [paper](http://thunlp.org/~yangcheng/publications/ijcai15.pdf) [code](https://github.com/thunlp/tadw)

1. **PTE: Predictive Text Embedding through Large-scale Heterogeneous Text Networks.**
*Jian Tang, Meng Qu, Qiaozhu Mei.*  KDD 2015. [paper](https://arxiv.org/pdf/1508.00200.pdf) [code](https://github.com/mnqu/PTE)

1. **Heterogeneous Network Embedding via Deep Architectures.**
*Shiyu Chang, Wei Han, Jiliang Tang, Guo-Jun Qi, Charu C. Aggarwal, Thomas S. Huang.* KDD 2015. [paper](http://www.ifp.illinois.edu/~chang87/papers/kdd_2015.pdf)

1. **Deep Neural Networks for Learning Graph Representations.**
*Shaosheng Cao, Wei Lu, Xiongkai Xu.* AAAI 2016. [paper](https://pdfs.semanticscholar.org/1a37/f07606d60df365d74752857e8ce909f700b3.pdf) [code](https://github.com/ShelsonCao/DNGR)

1. **Asymmetric Transitivity Preserving Graph Embedding.**
*Mingdong Ou, Peng Cui, Jian Pei, Ziwei Zhang, Wenwu Zhu.*  KDD 2016. [paper](http://media.cs.tsinghua.edu.cn/~multimedia/cuipeng/papers/hoppe.pdf)

1. **Revisiting Semi-supervised Learning with Graph Embeddings.**
*Zhilin Yang, William W. Cohen, Ruslan Salakhutdinov.* ICML 2016. [paper](http://www.jmlr.org/proceedings/papers/v48/yanga16.pdf)

1. **node2vec: Scalable Feature Learning for Networks.**
*Aditya Grover, Jure Leskovec.*  KDD 2016. [paper](http://www.kdd.org/kdd2016/papers/files/rfp0218-groverA.pdf) [code](https://github.com/aditya-grover/node2vec)

1. **Max-Margin DeepWalk: Discriminative Learning of Network Representation.**
*Cunchao Tu, Weicheng Zhang, Zhiyuan Liu, Maosong Sun.*  IJCAI 2016. [paper](http://thunlp.org/~tcc/publications/ijcai2016_mmdw.pdf) [code](https://github.com/thunlp/mmdw)

1. **Structural Deep Network Embedding.**
*Daixin Wang, Peng Cui, Wenwu Zhu.*  KDD 2016. [paper](http://media.cs.tsinghua.edu.cn/~multimedia/cuipeng/papers/SDNE.pdf)

1. **Community Preserving Network Embedding.**
*Xiao Wang, Peng Cui, Jing Wang, Jian Pei, Wenwu Zhu, Shiqiang Yang.* AAAI 2017. [paper](http://media.cs.tsinghua.edu.cn/~multimedia/cuipeng/papers/NE-Community.pdf)

1. **Semi-supervised Classification with Graph Convolutional Networks.**
*Thomas N. Kipf, Max Welling.* ICLR 2017. [paper](https://arxiv.org/pdf/1609.02907.pdf) [code](https://github.com/tkipf/gcn)

1. **CANE: Context-Aware Network Embedding for Relation Modeling.**
*Cunchao Tu, Han Liu, Zhiyuan Liu, Maosong Sun.* ACL 2017. [paper](http://thunlp.org/~tcc/publications/acl2017_cane.pdf) [code](https://github.com/thunlp/cane)

1. **Fast Network Embedding Enhancement via High Order Proximity Approximation.**
*Cheng Yang, Maosong Sun, Zhiyuan Liu, Cunchao Tu.* IJCAI 2017. [paper](http://thunlp.org/~tcc/publications/ijcai2017_neu.pdf) [code](https://github.com/thunlp/neu)

1. **TransNet: Translation-Based Network Representation Learning for Social Relation Extraction.**
*Cunchao Tu, Zhengyan Zhang, Zhiyuan Liu, Maosong Sun.* IJCAI 2017. [paper](http://thunlp.org/~tcc/publications/ijcai2017_transnet.pdf) [code](https://github.com/thunlp/transnet)

1. **metapath2vec: Scalable Representation Learning for Heterogeneous Networks.**
*Yuxiao Dong, Nitesh V. Chawla, Ananthram Swami.* KDD 2017. [paper](https://www3.nd.edu/~dial/publications/dong2017metapath2vec.pdf) [code](https://ericdongyx.github.io/metapath2vec/m2v.html)

1. **Learning from Labeled and Unlabeled Vertices in Networks.**
*Wei Ye, Linfei Zhou, Dominik Mautz, Claudia Plant, Christian Böhm.* KDD 2017. [paper](http://dl.acm.org/citation.cfm?id=3098142)

1. **Unsupervised Feature Selection in Signed Social Networks.**
*Kewei Cheng, Jundong Li, Huan Liu.* KDD 2017. [paper](http://www.public.asu.edu/~jundongl/paper/KDD17_SignedFS.pdf)

1. **struc2vec: Learning Node Representations from Structural Identity.**
*Leonardo F. R. Ribeiro, Pedro H. P. Saverese, Daniel R. Figueiredo.* KDD 2017. [paper](https://arxiv.org/pdf/1704.03165.pdf) [code](https://github.com/leoribeiro/struc2vec)

1. **Inductive Representation Learning on Large Graphs.**
*William L. Hamilton, Rex Ying, Jure Leskovec.* NIPS 2017. [paper](https://arxiv.org/pdf/1706.02216.pdf) [code](https://github.com/williamleif/GraphSAGE)

1. **Variation Autoencoder Based Network Representation Learning for Classification.**
*Hang Li, Haozheng Wang, Zhenglu Yang, Masato Odagaki.* ACL 2017. [paper](http://aclweb.org/anthology/P17-3010)

1. **Preserving Proximity and Global Ranking for Node Embedding.**
*Yi-An Lai, Chin-Chi Hsu, Wenhao Chen, Mi-Yen Yeh, Shou-De Lin.* NIPS 2017. 

1. **Learning Graph Embeddings with Embedding Propagation.**
*Alberto Garcia Duran, Mathias Niepert.* NIPS 2017. [paper](https://arxiv.org/pdf/1710.03059.pdf)

1. **Name Disambiguation in Anonymized Graphs using Network Embedding.**
*Baichuan Zhang, Mohammad Al Hasan.* CIKM 2017. [paper](https://arxiv.org/pdf/1702.02287.pdf)

1. **Enhancing the Network Embedding Quality with Structural Similarity.**
*Tianshu Lyu, Yuan Zhang, Yan Zhang.* CIKM 2017. [paper](http://www.cis.pku.edu.cn/faculty/system/zhangyan/papers/CIKM2017-lts.pdf)

1. **Attributed Signed Network Embedding.**
*Suhang Wang, Charu Aggarwal, Jiliang Tang, Huan Liu.* CIKM 2017. [paper](http://www.public.asu.edu/~swang187/publications/SNEA.pdf)

1. **Attributed Network Embedding for Learning in a Dynamic Environment.**
*Jundong Li, Harsh Dani, Xia Hu, Jiliang Tang, Yi Chang, Huan Liu.* CIKM 2017. [paper](https://arxiv.org/pdf/1706.01860.pdf)

1. **HIN2Vec: Explore Meta-paths in Heterogeneous Information Networks for Representation Learning.**
*Tao-yang Fu, Wang-Chien Lee, Zhen Lei.* CIKM 2017.

1. **From Properties to Links: Deep Network Embedding on Incomplete Graphs.**
*Dejian Yang, Senzhang Wang, Chaozhuo Li, Xiaoming Zhang, Zhoujun Li.* CIKM 2017.

1. **An Attention-based Collaboration Framework for Multi-View Network Representation Learning.**
*Meng Qu, Jian Tang, Jingbo Shang, Xiang Ren, Ming Zhang, Jiawei Han.* CIKM 2017. [paper](https://arxiv.org/pdf/1709.06636.pdf)

1. **On Embedding Uncertain Graphs.**
*Jiafeng Hu, Reynold Cheng, Zhipeng Huang, Yixang Fang, Siqiang Luo.* CIKM 2017. [paper](http://i.cs.hku.hk/~zphuang/pub/CIKM17.pdf)

1. **Multi-view Clustering with Graph Embedding for Connectome Analysis.**
*Guixiang Ma, Lifang He, Chun-Ta Lu, Weixiang Shao, Philip S Yu, Alex D Leow, Ann B Ragin.* CIKM 2017. [paper](https://www.cs.uic.edu/~clu/doc/cikm17_mcge.pdf)

1. **Learning Node Embeddings in Interaction Graphs.**
*Yao Zhang, Yun Xiong, Xiangnan Kong, Yangyong Zhu.* CIKM 2017. [paper](https://web.cs.wpi.edu/~xkong/publications/papers/cikm17.pdf)

1. **Learning Community Embedding with Community Detection and Node Embedding on Graphs.**
*Sandro Cavallari, Vincent W. Zheng, Hongyun Cai, Kevin ChenChuan Chang, Erik Cambria.* CIKM 2017. [paper](http://sentic.net/community-embedding.pdf) [code](https://github.com/andompesta/ComE)

1. **Network Embedding as Matrix Factorization: Unifying DeepWalk, LINE, PTE, and node2vec.**
*Jiezhong Qiu, Yuxiao Dong, Hao Ma, Jian Li, Kuansan Wang, Jie Tang.* WSDM 2018. [paper](https://arxiv.org/pdf/1710.02971.pdf)