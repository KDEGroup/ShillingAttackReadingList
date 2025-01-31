# Shilling Attack and Defense on Recommender System (Updating)

### 👉 Table of Contents 👈
- [Attack](#attack)
  * [2024](#2024)
  * [2023](#2023)
  * [2022](#2022)
  * [2021](#2021)
  * [2020](#2020)
  * [2019](#2019)
  * [2018](#2018)
  * [2017](#2017)
  * [2016](#2016)
  * [2015](#2015)
  * [2014](#2014)
  * [2013](#2013)
  * [2005](#2005)
  * [2004](#2004)
  * [2002](#2002)
- [Defense](#defense)
  * [2024](#2024-1)
  * [2023](#2023-1)
  * [2022](#2022-1)
  * [2021](#2021-1)
  * [2020](#2020-1)
  * [2019](#2019-1)
  * [2018](#2018-1)
  * [2017](#2017-1)
  * [2016](#2016-1)
  * [2015](#2015-1)
  * [2014](#2014-1)
  * [2012](#2012)
  * [2009](#2009)
  * [2008](#2008)
  * [2007](#2007)
  * [2006](#2006)
  * [2005](#2005-1)
- [Survey](#survey)
  * [2024](#2024-2)
  * [2022](#2022-2)
  * [2021](#2021-2)
  * [2020](#2020-2)
  * [2014](#2014-2)
  * [2008](#2008-1)
- [Tutorial](#tutorial)
  * [2023](#2023-2)
  * [2020-2021](#2020-2021)
- [Library](#library)
  * [2023](#2023-3)

# Attack

## 2024

- **Attacking Click-through Rate Predictors via Generating Realistic Fake Samples**, *TKDD*. [📝Paper](https://dl.acm.org/doi/10.1145/3643685)
- **Uplift Modeling for Target User Attacks on Recommender Systems**, *arXiv*. [📝Paper](http://arxiv.org/abs/2403.02692)
- **ToDA: Target-oriented Diffusion Attacker against Recommendation System**, *arXiv*. [📝Paper](http://arxiv.org/abs/2401.12578)
- **Collaborative Denoising Shilling Attack for Recommendation Systems**, *CSCWD*. [📝Paper](https://ieeexplore.ieee.org/document/10580115)
- **A novel shilling attack on black-box recommendation systems for multiple targets**, *NCA*. [📝Paper](https://doi.org/10.3233/IDA-230575)
- **PARL: Poisoning Attacks Against Reinforcement Learning-based Recommender Systems**, *AsiaCCS*. [📝Paper](https://dl.acm.org/doi/10.1145/3634737.3637660), [📃Code](https://github.com/PARL-RS/PARL)
- **Accelerating the Surrogate Retraining for Poisoning Attacks against Recommender Systems**, *RecSys*. [📝Paper](https://dl.acm.org/doi/10.1145/3640457.3688148), [📃Code](https://github.com/WuYunfan/GradientPassingAttack)
- **Poisoning Federated Recommender Systems with Fake Users**, *WWW*. [📝Paper](https://dl.acm.org/doi/10.1145/3589334.3645492)

### other poisoning attack
- **ClusterPoison: Poisoning Attacks on Recommender Systems with Limited Fake Users**, *Commun. Mag.*. [📝Paper](https://ieeexplore.ieee.org/document/10494850), [📃Code](https://github.com/yanling02/ClusterPoison)
- **Eyes on Federated Recommendation: Targeted Poisoning With Competition and Its Mitigation**, *IEEE Trans. Inf. Forensics Secur.*. [📝Paper](https://ieeexplore.ieee.org/document/10739366)
- **Poisoning Decentralized Collaborative Recommender System and Its Countermeasures**, *SIGIR*. [📝Paper](https://dl.acm.org/doi/10.1145/3626772.3657814)

## 2023

- **Adversarial Attacks for Black-Box Recommender Systems via Copying Transferable Cross-Domain User Profiles**, *TKDE*. [📝Paper](https://ieeexplore.ieee.org/document/10114977)
- **Influence-Driven Data Poisoning for Robust Recommender Systems**, *TPAMI*. [📝Paper](https://ieeexplore.ieee.org/document/10122715), [📃Code](https://github.com/Daftstone/Inf_recommender)
- **Planning Data Poisoning Attacks on Heterogeneous Recommender Systems in a Multiplayer Setting**, *ICDE*. [📝Paper](https://ieeexplore.ieee.org/document/10184597), [📃Code](https://github.com/jimmy-academia/MSOPDS)
- **Poisoning GNN-based Recommender Systems with Generative Surrogate-based Attacks**, *TOIS*. [📝Paper](https://dl.acm.org/doi/10.1145/3567420)
- **Poisoning Self-supervised Learning Based Sequential Recommendations**, *SIGIR*. [📝Paper](https://dl.acm.org/doi/10.1145/3539618.3591751), [📃Code](https://github.com/CongGroup/Poisoning-SSL-based-RS)
- **Practical Cross-System Shilling Attacks with Limited Access to Data**, *AAAI*. [📝Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25612), [📃Code](https://github.com/KDEGroup/PC-Attack)
- **Revisiting Item Promotion in GNN-Based Collaborative Filtering: A Masked Targeted Topological Attack Perspective**, *AAAI*. [📝Paper](https://ojs.aaai.org/index.php/AAAI/article/view/26774)
- **Shilling Black-box Review-based Recommender Systems through Fake Review Generation**, *KDD*. [📝Paper](https://dl.acm.org/doi/10.1145/3580305.3599502), [📃Code](https://github.com/hongyuntw/RBRS-ARG)
- **Single-User Injection for Invisible Shilling Attack against Recommender Systems**, *CIKM*. [📝Paper](https://dl.acm.org/doi/10.1145/3583780.3615062), [📃Code](https://github.com/kdegroup/sui-attack)
- **Targeted Shilling Attacks on GNN-based Recommender Systems**, *CIKM*. [📝Paper](https://dl.acm.org/doi/10.1145/3583780.3615073)
- **The Dark Side of Explanations: Poisoning Recommender Systems with Counterfactual Examples**, *SIGIR*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3539618.3592070)
- **UA-FedRec: Untargeted Attack on Federated News Recommendation**, *KDD*. [📝Paper](https://dl.acm.org/doi/10.1145/3580305.3599923), [📃Code](https://github.com/yjw1029/UA-FedRec)
- **Untargeted Black-box Attacks for Social Recommendations**, *arXiv*. [📝Paper](https://arxiv.org/abs/2311.07127)
- **Targeted Data Poisoning Attack on News Recommendation System by Content Perturbation**, *arXiv*. [📝Paper](https://arxiv.org/abs/2203.03560)
- **Poisoning Attacks Against Contrastive Recommender Systems**, *arXiv*. [📝Paper](https://arxiv.org/abs/2311.18244)
- **Topic-oriented Adversarial Attacks against Black-box Neural Ranking Models**, *arXiv*. [📝Paper](https://arxiv.org/abs/2304.14867)

## 2022

- **FedAttack: Effective and Covert Poisoning Attack on Federated Recommendation via Hard Sampling**, *KDD*. [📝Paper](https://dl.acm.org/doi/10.1145/3534678.3539119), [📃Code](https://github.com/wuch15/FedAttack)
- **Gray-Box Shilling Attack: An Adversarial Learning Approach**, *TIST*. [📝Paper](https://dl.acm.org/doi/full/10.1145/3512352)
- **Knowledge-enhanced Black-box Attacks for Recommendations**, *KDD*. [📝Paper](https://dl.acm.org/doi/10.1145/3534678.3539359)
- **PipAttack: Poisoning Federated Recommender Systems for Manipulating Item Promotion**, *WSDM*. [📝Paper](https://dl.acm.org/doi/10.1145/3488560.3498386)
- **Revisiting Injective Attacks on Recommender Systems**, *NeurIPS*. [📝Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/c1bb0e3b062f0a443f2cc8a4ec4bb30d-Abstract-Conference.html)
- **Shilling Black-box Recommender Systems by Learning to Generate Fake User Profiles**, *TNNLS*. [📝Paper](https://ieeexplore.ieee.org/document/9806457), [📃Code](https://github.com/XMUDM/ShillingAttack)

## 2021

- **A Black-Box Attack Model for Visually-Aware Recommender Systems**, *NDSS*. [📝Paper](https://dl.acm.org/doi/10.1145/3437963.3441757), [📃Code](https://github.com/vis-rs-attack/code)  
- **Attacking Black-box Recommendations via Copying Cross-domain User Profiles**, *ICDE*. [📝Paper](https://ieeexplore.ieee.org/document/9458627)
- **Attacking Recommender Systems With Plausible Profile**, *TIFS*. [📝Paper](https://ieeexplore.ieee.org/document/9555630)
- **Black-Box Attacks on Sequential Recommenders via Data-Free Model Extraction**, *RecSys*.  [📝Paper](https://dl.acm.org/doi/10.1145/3460231.3474275), [📃Code](https://github.com/Yueeeeeeee/RecSys-Extraction-Attack)
- **Data Poisoning Attack against Recommender System Using Incomplete and Perturbed Data**, *KDD*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467233)
- **Data Poisoning Attacks to Deep Learning Based Recommender Systems**, *NDSS*. [📝Paper](https://www.ndss-symposium.org/ndss-paper/data-poisoning-attacks-to-deep-learning-based-recommender-systems/)
- **Ready for Emerging Threats to Recommender Systems? A Graph Convolution-based Generative Shilling Attack**, *Information Sciences*. [📝Paper](https://www.sciencedirect.com/science/article/abs/pii/S0020025521007313)
- **Reverse Attack: Black-box Attacks on Collaborative Recommendation**, *CCS*. [📝Paper](https://dl.acm.org/doi/10.1145/3460120.3484805)
- **Triple Adversarial Learning for Influence based Poisoning Attack in Recommender Systems**, *KDD*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467335), [📃Code](https://github.com/Daftstone/TrialAttack)

## 2020

- **Attacking Recommender Systems with Augmented User Profiles**, *CIKM*. [📝Paper](https://dl.acm.org/doi/10.1145/3340531.3411884), [📃Code](https://github.com/XMUDM/ShillingAttack)
- **How Dataset Characteristics Affect the Robustness of Collaborative Recommendation Modelss**, *SIGIR*. [📝Paper](https://dl.acm.org/doi/10.1145/3397271.3401046)
- **Influence Function based Data Poisoning Attacks to Top-N Recommender Systems**, *WWW*. [📝Paper](https://dl.acm.org/doi/10.1145/3366423.3380072)
- **PoisonRec: An Adaptive Data Poisoning Framework for Attacking Black-box Recommender Systems**, *ICDE*. [📝Paper](https://ieeexplore.ieee.org/document/9101655)
- **Practical Data Poisoning Attack against Next-Item Recommendation**, *WWW*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3379992)
- **Revisiting Adversarially Learned Injection Attacks Against Recommender Systems.**, *RecSys*. [📝Paper](https://dl.acm.org/doi/10.1145/3383313.3412243), [📃Code](https://github.com/graytowne/revisit_adv_rec)  

## 2019

- **Adversarial Attacks on an Oblivious Recommender**, *RecSys*. [📝Paper](https://dl.acm.org/doi/10.1145/3298689.3347031)
- **Data Poisoning Attacks on Cross-domain RecommendationData Poisoning Attacks on Cross-domain Recommendation**, *CIKM*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3357384.3358116)

## 2018

- **Poisoning Attacks to Graph-Based Recommender Systems**, *ACSAC*. [📝Paper](https://dl.acm.org/doi/10.1145/3274694.3274706)

## 2017

- **Fake Co-visitation Injection Attacks to Recommender Systems**, *NDSS*. [📝Paper](https://www.ndss-symposium.org/ndss2017/ndss-2017-programme/fake-co-visitation-injection-attacks-recommender-systems/)

## 2016

- **Data Poisoning Attacks on Factorization-Based Collaborative Filtering**, *NeurIPS*. [📝Paper](https://proceedings.neurips.cc/paper/2016/hash/83fa5a432ae55c253d0e60dbfa716723-Abstract.html)

## 2015

- **Collaborative Filtering Under a Sybil Attack: Analysis of a Privacy Threat**, *EuroSec*. [📝Paper](https://dl.acm.org/doi/10.1145/2751323.2751328)

## 2014

- **Assessing Impacts of a Power User Attack on a Matrix Factorization Collaborative Recommender System**, *FLAIRS*. [📝Paper](https://aaai.org/papers/flairs-2014-7835/)
- **Attacking Item-Based Recommender Systems with Power Items**, *RecSys*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/2645710.2645722)
- **Evil Twins: Modeling Power Users in Attacks on Recommender Systems**, *UMAP*. [📝Paper](https://link.springer.com/chapter/10.1007/978-3-319-08786-3_20)

## 2013

- **Shilling Attacks against Memory-Based Privacy-Preserving Recommendation Algorithms**, *TIIS*. [📝Paper](https://avesis.akdeniz.edu.tr/yayin/4ae1f8bd-1178-4bde-b1ce-997cd2f61f21/shilling-attacks-against-memory-based-privacy-preserving-recommendation-algorithms)
- **Take This Personally: Pollution Attacks on Personalized Services**, *USENIX Security Symposium*. [📝Paper](https://www.usenix.org/conference/usenixsecurity13/technical-sessions/paper/xing)
- **When Power Users Attack: Assessing Impacts in Collaborative Recommender Systems**, *RecSys*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/2507157.2507220)

## 2005

- **Effective Attack Models for Shilling Item-Based Collaborative Filtering System**, *WEBKDD*. [📝Paper](https://www.researchgate.net/profile/Robin-Burke-3/publication/243787659_Effective_Attack_Models_for_Shilling_Item-Based_Collaborative_Filtering_Systems/links/0c96053aafccfd7e5d000000/Effective-Attack-Models-for-Shilling-Item-Based-Collaborative-Filtering-Systems.pdf)
- **Limited Knowledge Shilling Attacks in Collaborative Filtering Systems**, *IJCAI*. [📝Paper](http://facweb.cs.depaul.edu/mobasher/research/papers/sp-itwp05.pdf)
- **Recommender Systems: Attack Types and Strategies**, *AAAI*. [📝Paper](https://dl.acm.org/doi/abs/10.5555/1619332.1619387)
- **Segment-Based Injection Attacks against Collaborative Filtering Recommender Systems**, *ICDM*. [📝Paper](https://ieeexplore.ieee.org/document/1565730)

## 2004

- **Shilling Recommender Systems for Fun and Profit**, *WWW*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/988672.988726)

## 2002

- **Promoting Recommendations: An Attack on Collaborative Filtering**, *DEXA*. [📝Paper](https://link.springer.com/chapter/10.1007/3-540-46146-9_49)

# Defense

## 2024
- **Detecting Group Shilling Attacks In Recommender Systems Based On User Multi-dimensional Features And Collusive Behaviour Analysis**, *Comput. J.*. [📝Paper](https://doi.org/10.1093/comjnl/bxad003)
- **A Research on Shilling Attacks Based on Variational graph auto-encoders for Improving the Robustness of Recommendation Systems**, *GAIIS*. [📝Paper](https://dl.acm.org/doi/10.1145/3665348.3665370)
- **Unveiling Vulnerabilities of Contrastive Recommender Systems to Poisoning Attacks**, *KDD*. [📝Paper](https://dl.acm.org/doi/10.1145/3637528.3671795), [📃Code](https://github.com/CoderWZW/ARLib)
- **Poison-Tolerant Collaborative Filtering Against Poisoning Attacks on Recommender Systems**, *IEEE Trans. Dependable Secur. Comput.*. [📝Paper](https://ieeexplore.ieee.org/document/10400891)
- **Robust Federated Contrastive Recommender System against Model Poisoning Attack**, *arxiv*. [📝Paper](https://arxiv.org/pdf/2403.20107)
- **LoRec: Large Language Model for Robust Sequential Recommendation against Poisoning Attacks**, *arxiv*. [📝Paper](https://arxiv.org/pdf/2401.17723)

## 2023

- **Anti-FakeU: Defending Shilling Attacks on Graph Neural Network based Recommender Model**, *WWW*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3543507.3583289)
- **Enhancing Adversarial Robustness of Multi-modal Recommendation via Modality Balancing**, *MM*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3612337)
- **Influence-Driven Data Poisoning for Robust Recommender Systems**, *TPAMI*. [📝Paper](https://ieeexplore.ieee.org/abstract/document/10122715)
- **On the Vulnerability of Graph Learning-based Collaborative Filtering**, *TOIS*. [📝Paper](https://dl.acm.org/doi/full/10.1145/3572834)
- **Towards Adversarially Robust Recommendation from Adaptive Fraudster Detection**, *TIFS*. [📝Paper](https://ieeexplore.ieee.org/abstract/document/10296883)    
- **PORE: Provably Robust Recommender Systems against Data Poisoning Attacks**, *arXiv*. [📝Paper](https://arxiv.org/abs/2303.14601), [📃Code](https://github.com/liu00222/PORE-Provably-Robust-Recommender-Systems-against-Data-Poisoning-Attacks)
- **Toward Robust Recommendation via Real-time Vicinal Defense**, *arXiv*. [📝Paper](https://arxiv.org/abs/2309.17278)

## 2022

- **Defending Substitution-Based Profile Pollution Attacks on Sequential Recommenders**, *RecSys*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3523227.3546770), [📃Code](https://github.com/Yueeeeeeee/RecSys-Substitution-Defense)
- **Detect Professional Malicious User With Metric Learning in Recommender Systems**, *TKDE*. [📝Paper](https://ieeexplore.ieee.org/abstract/document/9271919)
- **RGRecSys: A Toolkit for Robustness Evaluation of Recommender Systems**, *WSDM*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3488560.3502192), [📃Code](https://github.com/salesforce/rgrecsys)
- **Three Birds with One Stone: User Intention Understanding and Influential Neighbor Disclosure for Injection Attack Detection**, *TIFS*. [📝Paper](https://ieeexplore.ieee.org/abstract/document/9693911)
- **Towards Robust Recommender Systems via Triple Cooperative Defense**, *WISE*. [📝Paper](https://link.springer.com/chapter/10.1007/978-3-031-20891-1_40), [📃Code](https://github.com/greensun0830/TCD)

## 2021

- **Fight Fire with Fire: Towards Robust Recommender Systems via Adversarial Poisoning Training**, *SIGIR*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3404835.3462914), [📃Code](https://github.com/rastegarpanah/antidote-data-framework)
- **Identification of Malicious Injection Attacks in Dense Rating and Co-Visitation Behaviors**, *TIFS*. [📝Paper](https://ieeexplore.ieee.org/abstract/document/9167299)

## 2020

- **GCN-Based User Representation Learning for Unifying Robust Recommendation and Fraudster Detection**, *SIGIR*. [📝Paper](https://dl.acm.org/doi/10.1145/3397271.3401165), [📃Code](https://github.com/zsjdddhr/GraphRfi)
- **On Detecting Data Pollution Attacks On Recommender Systems Using Sequential GANs**, *arXiv*. [📝Paper](https://arxiv.org/abs/2012.02509)

## 2019

- **Enhancing the Robustness of Neural Collaborative Filtering Systems under Malicious Attacks**, *TMM*. [📝Paper](https://ieeexplore.ieee.org/document/8576563)
- **Evaluating Recommender System Stability with Influence-Guided Fuzzing**, *AAAI*. [📝Paper](https://ojs.aaai.org/index.php/AAAI/article/view/4423)
- **Quick and Accurate Attack Detection in Recommender Systems through User Attributes**, *RecSys*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3298689.3347050)

## 2018

- **Unorganized Malicious Attacks Detection**, *NeurIPS*. [📝Paper](https://proceedings.neurips.cc/paper/2018/hash/322f62469c5e3c7dc3e58f5a4d1ea399-Abstract.html)

## 2017

- **Detecting Abnormal Profiles in Collaborative Filtering Recommender Systems**, *JIIS*. [📝Paper](https://link.springer.com/article/10.1007/s10844-016-0424-5)

## 2016

- **Re-Scale Adaboost for Attack Detection in Collaborative Filtering Recommender Systems**, *KBS*. [📝Paper](https://www.sciencedirect.com/science/article/pii/S0950705116000861)

## 2015

- **Catch the Black Sheep: Unified Framework for Shilling Attack Detection Based on Fraudulent Action Propagation**, *IJCAI*. [📝Paper](https://www.ijcai.org/Abstract/15/341), [📃Code](https://github.com/Coder-Yu/SDLib)
- **Mitigating Power User Attacks on a User-Based Collaborative Recommender System**, *FLAIRS*. [📝Paper](https://aaai.org/papers/513-flairs-2015-10451/)
- **Shilling Attacks Detection in Recommender Systems Based on Target Item Analysis**, *PloS One*. [📝Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0130968)

## 2014

- **Defending Recommender Systems by Influence Analysis**, *Information Retrieval*. [📝Paper](https://link.springer.com/article/10.1007/s10791-013-9224-5)

## 2012

- **Stability of Matrix Factorization for Collaborative Filtering**, *ICML*. [📝Paper](https://icml.cc/2012/papers/233.pdf)

## 2009

- **Unsupervised Strategies for Shilling Detection and Robust Collaborative Filtering**, *UMUAI*. [📝Paper](https://link.springer.com/article/10.1007/s11257-008-9050-4)

## 2008

- **Attack Resistant Collaborative Filtering**, *SIGIR*. [📝Paper](https://dl.acm.org/doi/10.1145/1390334.1390350)
- **Unsupervised Retrieval of Attack Profiles in Collaborative Recommender Systems**, *RecSys*. [📝Paper](https://dl.acm.org/doi/10.1145/1454008.1454034)

## 2007

- **Defending Recommender Systems: Detection of Profile Injection Attacks**, *SOCA*. [📝Paper](https://link.springer.com/article/10.1007/s11761-007-0013-0)
- **Robust Collaborative Filtering**, *RecSys*. [📝Paper](https://dl.acm.org/doi/10.1145/1297231.1297240)
- **Robustness of Collaborative Recommendation Based on Association Rule Mining**, *RecSys*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/1297231.1297249)
- **The Influence Limiter: Provably Manipulation-Resistant Recommender Systems**, *RecSys*. [📝Paper](https://dl.acm.org/doi/10.1145/1297231.1297236)
- **Toward trustworthy recommender systems: An Analysis of Attack Models and Algorithm Robustness**, *TOIT*. [📝Paper](https://dl.acm.org/doi/10.1145/1278366.1278372)
- **Unsupervised Shilling Detection for Collaborative Filtering**, *AAAI*. [📝Paper](https://cdn.aaai.org/AAAI/2007/AAAI07-222.pdf)

## 2006

- **Classification Features for Attack Detection in Collaborative Recommender Systems**, *KDD*. [📝Paper](https://dl.acm.org/doi/10.1145/1150402.1150465)
- **Detection of Obfuscated Attacks in Collaborative Recommender Systems**, *ECAI Workshop on Recommender Systems*. [📝Paper](http://facweb.cs.depaul.edu/mobasher/research/papers/wmbsb-ecai-ws06.pdf)
- **Securing Collaborative Filtering against Malicious Attacks through Anomaly Detection**, *ITWP*. [📝Paper](https://www.researchgate.net/profile/Bamshad-Mobasher/publication/228945166_Securing_collaborative_filtering_against_malicious_attacks_through_anomaly_detection/links/0fcfd507477e71cb6e000000/Securing-collaborative-filtering-against-malicious-attacks-through-anomaly-detection.pdf)
- **The Impact of Attack Profile Classification on the Robustness of Collaborative Recommendation**, *WEBKDD*. [📝Paper](https://www.researchgate.net/profile/Bamshad-Mobasher/publication/228945172_The_Impact_of_Attack_Profile_Classification_on_the_Robustness_of_Collaborative_Recommendation/links/0fcfd507477e6d1092000000/The-Impact-of-Attack-Profile-Classification-on-the-Robustness-of-Collaborative-Recommendation.pdf)

## 2005

- **Analysis and Detection of Segment-Focused Attacks against Collaborative Recommendation**, *WEBKDD*. [📝Paper](https://link.springer.com/chapter/10.1007/11891321_6)
- **Finding Group Shilling in Recommendation System**, *WWW*. [📝Paper](https://dl.acm.org/doi/10.1145/1062745.1062818)
- **Identifying Attack Models for Secure Recommendation**, *Beyond Personalization IUI*. [📝Paper](http://facweb.cs.depaul.edu/mobasher/research/papers/sp-iui05.pdf)
- **Preventing Shilling Attacks in Online Recommender Systems**, *WIDM*. [📝Paper](https://dl.acm.org/doi/10.1145/1097047.1097061)

# Survey

## 2024

- **Manipulating Recommender Systems: A Survey of Poisoning Attacks and Countermeasures**, *arXiv*. [📝Paper](http://arxiv.org/abs/2404.14942)
- **Towards Robust Recommendation: A Review and an Adversarial Robustness Evaluation Library**, *arXiv*. [📝Paper](http://arxiv.org/abs/2404.17844)
- **Poisoning Attacks against Recommender Systems: A Survey**, *arxiv*. [📝Paper](https://arxiv.org/abs/2401.01527), [📃Code](https://github.com/CoderWZW/ARLib)

## 2022

- **Latest Trends of Security and Privacy in Recommender Systems: A Comprehensive Review and Future Perspectives**, *Computers & Security*. [📝Paper](https://doi.org/10.1016/j.cose.2022.102746)
- **A Survey for Trust-Aware Recommender Systems: A Deep Learning Perspective**, *KBS*. [📝Paper](https://doi.org/10.1016/j.knosys.2022.108954)
- **Trustworthy Recommender Systems**, *arXiv*. [📝Paper](https://arxiv.org/abs/2208.06265)
- **A Survey on Trustworthy Recommender Systems**, *arXiv*. [📝Paper](https://arxiv.org/abs/2207.12515)
- **A Comprehensive Survey on Trustworthy Recommender Systems**, *arXiv*. [📝Paper](https://arxiv.org/abs/2209.10117)

## 2021

- **A Survey on Adversarial Recommender Systems: From Attack/Defense Strategies to Generative Adversarial Networks**, *ACM Computing Surveys*. [📝Paper](https://dl.acm.org/doi/10.1145/3439729)

## 2020

- **Shilling Attacks against Collaborative Recommender Systems: A Review**, *Artificial Intelligence Review*. [📝Paper](https://link.springer.com/article/10.1007/s10462-018-9655-x)

## 2014

- **Shilling Attacks against Recommender Systems: A Comprehensive Survey**, *Artificial Intelligence Review*. [📝Paper](https://link.springer.com/article/10.1007/s10462-012-9364-9)

## 2008

- **A Survey of Attack-Resistant Collaborative Filtering Algorithms**, *Data Engineering Bulletin Issues*. [📝Paper](http://sites.computer.org/debull/A08June/mehta.pdf)
- **A Survey of Collaborative Recommendation and the Robustness of Model-Based Algorithms**, *Data Engineering Bulletin Issues*. [📝Paper](http://sites.computer.org/debull/A08June/sandvig.pdf)

# Tutorial

## 2023

- **Trustworthy Recommender Systems: Foundations and Frontiers**, *KDD & The Web Conference*. [🌐Website](https://advanced-recommender-systems.github.io/trustworthiness-tutorial)
- **Trustworthy Recommender Systems: Technical, Ethical, Legal, and Regulatory Perspectives**, *RecSys*. [🌐Website](https://github.com/socialcomplab/Trustworthy-RS-Tutorial-RecSys23)

## 2020-2021

- **Adversarial Machine Learning in Recommender Systems**, *WSDM & RecSys & ECIR*. [🌐Website](https://github.com/sisinflab/amlrecsys-tutorial)

# Library

## 2023

- **RecAD: Towards A Unified Library for Recommender Attack and Defense**, *RecSys*. [📝Paper](https://dl.acm.org/doi/abs/10.1145/3604915.3609490), [📃Code](https://github.com/gusye1234/recad)
