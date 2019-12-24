# Awesome Temporal Action Localization: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of temporal action localization/detection and related area (e.g. temporal action proposal) resources.

## Contents
- [Temporal Action Localization](#1)
    - [Paper](#11)
        - [2019](#111) - [2018](#112) - [2017](#113) - [2016](#114)
    - [Dataset](#12)
    - [Benchmark Results](#13)
        - [THUMOS14](#131) - [ActivityNet v1.3](#132)
- [Weakly Supervised Temporal Action Localization](#2)
    - [Paper](#21)
        - [2019](#211) - [2018](#212) - [2017](#213)
    - [Dataset](#22)
    - [Benchmark Results](#23)
        - [THUMOS14](#231) - [ActivityNet v1.3](#232) - [ActivityNet v1.2](#233)

---

## <span id = "1">**Temporal Action Localization**</span>

## <span id = "11">Papers</span>

### <span id = "111">2019</span>

- <span id = "2195">[[PGCN]](#1195)</span> [**Graph Convolutional Networks for Temporal Action Localization**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zeng_Graph_Convolutional_Networks_for_Temporal_Action_Localization_ICCV_2019_paper.pdf) - Runhao Zeng et al, `ICCV 2019`. [[code]](<https://github.com/Alvin-Zeng/PGCN>)
- <span id = "2196">[[RAM]](#1196)</span> [**Graph Convolutional Networks for Temporal Action Localization**](https://ieeexplore.ieee.org/document/8933113) - Peihao Chen et al, `TMM 2019`. 
- <span id = "2194">[[BMN]](#1194)</span> [**BMN: Boundary-Matching Network for Temporal Action Proposal Generation**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Lin_BMN_Boundary-Matching_Network_for_Temporal_Action_Proposal_Generation_ICCV_2019_paper.pdf) - Tianwei Lin et al, `ICCV 2019`.
- <span id = "2193">[[GTAN]](#1193)</span> [**Gaussian Temporal Awareness Networks for Action Localization**](https://arxiv.org/abs/1909.03877) - Fuchen Long et al, `CVPR 2019`.
- <span id = "2192">[[DBS]](#1192)</span> [**Video Imprint Segmentation for Temporal Action Detection in Untrimmed Videos**](https://www.aaai.org/ojs/index.php/AAAI/article/view/4846) - Zhanning Gao et al, `AAAI 2019`.
- <span id = "2191">[[C-TCN]](#1191)</span> [**Deep Concept-wise Temporal Convolutional Networks for Action Localization**](https://arxiv.org/abs/1908.09442) - Xin Li et al, `arXiv 2019`.
- <span id = "2197">[[PGCN]](#1197)</span> [**G-TAD: Sub-Graph Localization for Temporal Action Detection**](https://arxiv.org/pdf/1911.11462.pdf) - MengMeng Xu et al, `arXiv 2019`. 

### <span id = "112">2018</span>

- <span id = "2181">[[TAL-Net]](#1181)</span> [**Rethinking the Faster R-CNN Architecture for Temporal Action Localization**](https://arxiv.org/abs/1804.07667) - Yuwei Chao et al, `CVPR 2018`.
- <span id = "2182">[[Action-Search]](#1182)</span> [**Action Search: Spotting Actions in Videos and Its Application to Temporal Action Localization**](https://arxiv.org/abs/1706.04269) - Humam Alwassel et al, `ECCV 2018`. [[code]](<http://www.humamalwassel.com/publication/action-search/>)
- <span id = "2183">[[BSN]](#1183)</span> [**BSN: Boundary Sensitive Network for Temporal Action Proposal Generation**](https://arxiv.org/abs/1806.02964) - Tianwei Lin et al, `ECCV 2018`. [[code]](<https://github.com/wzmsltw/BSN-boundary-sensitive-network>)
- <span id = "2184">[[TPC]](#1184)</span> [**Exploring Temporal Preservation Networks for Precise Temporal Action Localization**](https://arxiv.org/abs/1708.03280) - Ke Yang et al, `AAAI 2018`.
- <span id = "2185">[[Self-Ad]](#1185)</span> [**A Self-Adaptive Proposal Model for Temporal Action Detection based on Reinforcement Learning**](https://arxiv.org/abs/1706.07251) - Jingjia Huang et al, `AAAI 2018`.

### <span id = "113">2017</span>

- <span id = "2171">[[CDC]](#1171)</span> [**CDC: Convolutional-De-Convolutional Networks for Precise Temporal Action Localization in Untrimmed Videos**](https://arxiv.org/abs/1703.01515) - Zheng Shou et al, `CVPR 2017`. [[code]](<https://bibucket.org/columbiadvmm/cdc>)
- <span id = "2172">[[SMS]](#1172)</span> [**Temporal Action Localization by Structured Maximal Sums**](https://arxiv.org/abs/1704.04671) - Zehuan Yuan et al, `CVPR 2017`.
- <span id = "2173">[[SCC]](#1173)</span> [**SCC: Semantic Context Cascade for Efficient Action Detection**](https://ieeexplore.ieee.org/document/8099821) - Fabian Caba Heilbron et al, `CVPR 2017`.
- <span id = "2174">[[SSN]](#1174)</span> [**Temporal Action Detection with Structured Segment Networks**](https://arxiv.org/abs/1704.06228) - Yue Zhao et al, `ICCV 2017`. [[code]](<http://yjxiong.me/others/ssn>)
- <span id = "2175">[[R-C3D]](#1175)</span> [**R-C3D: Region Convolutional 3D Network for Temporal Activity Detection**](https://arxiv.org/abs/1703.07814) - Huijuan Xu et al, `ICCV 2017`. [[code]](<http://ai.bu.edu/r-c3d/>)
- <span id = "2176">[[TCN]](#1176)</span> [**Temporal Context Network for Activity Localization in Videos**](https://arxiv.org/abs/1708.02349) - Xiyang Dai et al, `ICCV 2017`.
- <span id = "2177">[[TURN]](#1177)</span> [**TURN TAP: Temporal Unit Regression Network for Temporal Action Proposals**](https://arxiv.org/abs/1703.06189) - Jiyang Gao et al, `ICCV 2017`. [[code]](<https://github.com/jiyanggao/TURN-TAP>)
- <span id = "2178">[[SST]](#1178)</span> [**SST: Single-Stream Temporal Action Proposals**](https://ieeexplore.ieee.org/abstract/document/8100158) - Shyamal Buch et al, `ICCV 2017`.

### <span id = "114">2016</span>

- <span id = "2161">[[FG]](#1161)</span>  [**End-to-end Learning of Action Detection from Frame Glimpses in Videos**](https://arxiv.org/abs/1511.06984) - Serena Yeung et al, `CVPR 2016`.
- <span id = "2162">[[PSDF]](#1162)</span> [**Temporal Action Localization with Pyramid of Score Distribution Features**](https://ieeexplore.ieee.org/abstract/document/7780706) - Jun Yuan et al, `CVPR 2016`.
- <span id = "2163">[[SLM]](#1163)</span> [**Temporal Action Detection Using a Statistical Language Model**](https://ieeexplore.ieee.org/document/7780710) - Alexander Richard et al, `CVPR 2016`.
- <span id = "2164">[[S-CNN]](#1164)</span> [**Temporal Action Localization in Untrimmed Videos via Multi-stage CNNs**](https://arxiv.org/abs/1601.02129) - Zheng Shou et al, `CVPR 2016`. [[code]](<https://github.com/zhengshou/scnn/>)
- <span id = "2165">[[DAPs]](#1165)</span> [**DAPs: Deep Action Proposals for Action Understanding**](https://link.springer.com/chapter/10.1007%2F978-3-319-46487-9_47) - Victor Escorcia et al, `ECCV 2016`.

## <span id = "12">Dataset</span>

- [THUMOS14](https://www.crcv.ucf.edu/THUMOS14/)
- [ActivityNet v1.3](http://activity-net.org/download.html)

## <span id = "13">Benchmark Results</span>

#### <span id = "131">THUMOS14</span>

|                     Method                      |  Conference   |   IoU@0.1   |   IoU@0.2   |   IoU@0.3   |   IoU@0.4   |   IoU@0.5   |   IoU@0.6   |   IoU@0.7   |
| :---------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "1161">[FG](#2161)</span>            |   CVPR-2016   |    48.9     |    44.0     |    36.0     |    26.4     |    17.1     |      -      |      -      |
| <span id = "1162">[PSDF](#2162)</span>          |   CVPR-2016   |    51.4     |    42.6     |    33.6     |    26.1     |    18.8     |      -      |      -      |
| <span id = "1163">[SLM](#2163)</span>           |   CVPR-2016   |    39.7     |    35.7     |    30.0     |    23.2     |    15.2     |      -      |      -      |
| <span id = "1164">[S-CNN](#2164)</span>         |   CVPR-2016   |    47.7     |    43.5     |    36.3     |    28.7     |    19.0     |    10.3     |     5.3     |
| <span id = "1165">[DAPs](#2165)</span>          |   ECCV-2016   |      -      |      -      |      -      |      -      |    13.9     |      -      |      -      |
| <span id = "1171">[CDC](#2171)</span>           |   CVPR-2017   |      -      |      -      |    40.1     |    29.4     |    23.3     |    13.1     |     7.9     |
| <span id = "1172">[SMS](#2172)</span>           |   CVPR-2017   |    51.0     |    45.2     |    36.5     |    27.8     |    17.8     |      -      |      -      |
| <span id = "1173">[SCC](#2173)</span>           |   CVPR-2017   |      -      |      -      |      -      |      -      |      -      |      -      |      -      |
| <span id = "1174">[SSN](#2174)</span>           |   ICCV-2017   |    66.0     |    59.4     |    51.9     |    41.0     |    29.8     |      -      |      -      |
| <span id = "1175">[R-C3D](#2175)</span>         |   ICCV-2017   |    54.5     |    51.5     |    44.8     |    35.6     |    28.9     |      -      |      -      |
| <span id = "1176">[TCN](#2176)</span>           |   ICCV-2017   |      -      |      -      |      -      |    33.3     |    25.6     |    15.9     |     9.0     |
| <span id = "1177">[TURN](#2177)</span>          |   ICCV-2017   |    54.0     |    50.9     |    44.1     |    34.9     |    25.6     |      -      |      -      |
| <span id = "1178">[SST](#2178)</span>           |   ICCV-2017   |      -      |      -      |      -      |      -      |    23.0     |      -      |      -      |
| <span id = "1182">[Action-Search](#2182)</span> |   ECCV-2018   |      -      |      -      |    51.8     |    42.4     |    30.8     |    20.2     |    11.1     |
| <span id = "1183">[BSN](#2183)</span>           |   ECCV-2018   |      -      |      -      |    53.5     |    45.0     |    36.9     |    28.4     |    20.0     |
| <span id = "1184">[TPC](#2184)</span>           |   AAAI-2018   |      -      |      -      |    44.1     |    37.1     |    28.2     |    20.6     |    12.7     |
| <span id = "1185">[Self-Ad](#2185)</span>       |   AAAI-2018   |      -      |      -      |      -      |      -      |    27.7     |      -      |      -      |
| <span id = "1192">[DBS](#2192)</span>           |   AAAI-2019   |    56.7     |    54.7     |    50.6     |    43.1     |    34.3     |    24.4     |    14.7     |
| <span id = "1193">[GTAN](#2193)</span>          |   CVPR-2019   |    69.1     |    63.7     |    57.8     |    47.2     |    38.8     |      -      |      -      |
| <span id = "1194">[BMN](#2194)</span>           |   ICCV-2019   |      -      |      -      |    56.0     |    47.4     |    38.8     |    29.7     |    20.5     |
| <span id = "1181">[TAL-Net](#2181)</span>       |   CVPR-2018   |    59.8     |    57.1     |    53.2     |    48.5     |    42.8     |    33.8     |    20.8     |
| <span id = "1196">[RAM](#2196)</span>           |   TMM-2019    |    65.4     |    63.1     |    58.8     |    52.7     |    43.7     |      -      |      -      |
| <span id = "1195">[PGCN](#2195)</span>          |   ICCV-2019   |    69.5     |    67.8     |    63.6     |    57.8     |    49.1     |      -      |      -      |

|                     Method                      |  Conference   |   IoU@0.1   |   IoU@0.2   |   IoU@0.3   |   IoU@0.4   |   IoU@0.5   |   IoU@0.6   |   IoU@0.7   |
| :---------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "1191">[C-TCN](#2191)</span>         |     arXiv     |    72.2     |    71.4     |    68.0     |    62.3     |    52.1     |      -      |      -      |
| <span id = "1197">[G-TAD](#2197)</span>         |     arXiv     |      -      |      -      |    54.5     |    47.6     |    40.2     |    30.8     |    23.4     |

#### <span id = "132">ActivityNet v1.3</span>

|         Method         |  Conference   |   IoU@0.5   |   IoU@0.75   |   IoU@0.95   |   IoU@Avg   |
| :--------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [FG](#2161)            |   CVPR-2016   |      -      |      -       |      -       |      -      |
| [PSDF](#2162)          |   CVPR-2016   |      -      |      -       |      -       |      -      |
| [SLM](#2163)           |   CVPR-2016   |      -      |      -       |      -       |      -      |
| [S-CNN](#2164)         |   CVPR-2016   |      -      |      -       |      -       |      -      |
| [DAPs](#2165)          |   ECCV-2016   |      -      |      -       |      -       |      -      |
| [CDC](#2171)           |   CVPR-2017   |    45.3     |    26.0      |     0.2      |    23.8     |
| [SMS](#2172)           |   CVPR-2017   |      -      |      -       |      -       |      -      |
| [SCC](#2173)           |   CVPR-2017   |    39.9     |    18.7      |     4.7      |    19.3     |
| [SSN](#2174)           |   ICCV-2017   |    43.26    |    28.70     |     5.63     |    28.28    |
| [R-C3D](#2175)         |   ICCV-2017   |    26.8     |      -       |      -       |      -      |
| [TCN](#2176)           |   ICCV-2017   |    37.49    |    23.47     |     4.47     |    23.58    |
| [TURN](#2177)          |   ICCV-2017   |      -      |      -       |      -       |      -      |
| [SST](#2178)           |   ICCV-2017   |      -      |      -       |      -       |      -      |
| [TAL-Net](#2181)       |   CVPR-2018   |    38.23    |    18.30     |     1.30     |    20.22    |
| [Action-Search](#2182) |   ECCV-2018   |      -      |      -       |      -       |      -      |
| [BSN](#2183)           |   ECCV-2018   |    46.45    |    29.96     |     8.02     |    30.03    |
| [TPC](#2184)           |   AAAI-2018   |      -      |      -       |      -       |      -      |
| [Self-Ad](#2185)       |   AAAI-2018   |      -      |      -       |      -       |      -      |
| [DBS](#2192)           |   CVPR-2019   |    43.2     |    25.8      |     6.1      |    26.1     |
| [RAM](#2196)           |   TMM         |    36.99    |    23.10     |     3.34     |    23.03    |
| [PGCN](#2195)          |   ICCV-2019   |    42.90    |    28.14     |     2.47     |    26.99    |
| [BMN](#2194)           |   ICCV-2019   |    50.07    |    34.78     |     8.29     |    33.85    |
| [GTAN](#2193)          |   CVPR-2019   |    52.61    |    34.14     |     8.91     |    34.31    |

|         Method         |  Conference   |   IoU@0.5   |   IoU@0.75   |   IoU@0.95   |   IoU@Avg   |
| :--------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [C-TCN](#2191)         |     arXiv     |    47.6     |    31.9      |     6.2      |    31.1     |
| [G-TAD](#2197)         |     arXiv     |    50.36    |   34.60      |     9.02     |    34.09    |

---

## <span id = "2">**Weakly Supervised Temporal Action Localization**</span>

## <span id = "21">Paper</span>

### <span id = "211">2019</span>

- <span id = "4196">[[IWO-Net]](#3196)</span> [**Breaking Winner-Takes-All: Iterative-Winners-Out Networks for Weakly Supervised Temporal Action Localization**](https://ieeexplore.ieee.org/document/8737877) - Runhao Zeng et al, `TIP 2019`.
- <span id = "4195">[[BM]](#3195)</span> [**Weakly-supervised Action Localization with Background Modeling**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Nguyen_Weakly-Supervised_Action_Localization_With_Background_Modeling_ICCV_2019_paper.pdf) - Phuc Xuan Nguyen et al, `ICCV 2019`.
- <span id = "4194">[[TSM]](#3194)</span> [**Temporal Structure Mining for Weakly Supervised Action Detection**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Temporal_Structure_Mining_for_Weakly_Supervised_Action_Detection_ICCV_2019_paper.pdf) - Tan Yu et al, `ICCV 2019`.
- <span id = "4193">[[CleanNet]](#3193)</span> [**Weakly Supervised Temporal Action Localization through Contrast based Evaluation Networks**](https://arxiv.org/abs/1811.07460) - Ziyi Liu et al, `ICCV 2019`.
- <span id = "4191">[[CMCS]](#3191)</span> [**Completeness Modeling and Context Separation for Weakly Supervised Temporal Action Localization**](http://openaccess.thecvf.com/content_CVPR_2019/html/Liu_Completeness_Modeling_and_Context_Separation_for_Weakly_Supervised_Temporal_Action_CVPR_2019_paper.html) - Daochang Liu et al, `CVPR 2019`.
- <span id = "4192">[[STAR]](#3192)</span> [**Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection**](https://arxiv.org/abs/1811.07460) - Yunlu Xu et al, `AAAI 2019`.

### <span id = "212">2018</span>

- <span id = "4181">[[One-Shot]](#3181)</span> [**One-Shot Action Localization by Learning Sequence Matching Network**](https://ieeexplore.ieee.org/document/8578255) - Hongtao Yang et al, `CVPR 2018`.
- <span id = "4182">[[STPN]](#3182)</span> [**Weakly Supervised Action Localization by Sparse Temporal Pooling Network**](https://arxiv.org/abs/1712.05080) - Phuc Nguyen et al, `CVPR 2018`.
- <span id = "4183">[[AutoLoc]](#3183)</span> [**AutoLoc: Weakly-supervised Temporal Action Localization in Untrimmed Videos**](https://arxiv.org/abs/1807.08333) - Zheng Shou et al, `ECCV 2018`. [[code]](<https://github.com/zhengshou/AutoLoc>)
- <span id = "4184">[[W-TALC]](#3184)</span> [**W-TALC: Weakly-supervised Temporal Activity Localization and Classification**](https://arxiv.org/abs/1807.10418) - Sujoy Paul et al, `ECCV 2018`. [[code]](<https://github.com/sujoyp/wtalc-pytorch>)

### <span id = "213">2017</span>

- <span id = "4171">[[UNet]](#3171)</span> [**UntrimmedNets for Weakly Supervised Action Recognition and Detection**](https://arxiv.org/abs/1703.03329) - Limin Wang et al, `CVPR 2017`. [[code]](<https://github.com/wanglimin/UntrimmedNet>)
- <span id = "4172">[[H&S]](#3172)</span> [**Hide-and-Seek: Forcing a Network to be Meticulous for Weakly-supervised Object and Action Localization**](https://arxiv.org/abs/1704.04232) - Krishna Kumar Singh et al, `CVPR 2017`.

## <span id = "22">Dataset</span>

- [THUMOS14](https://www.crcv.ucf.edu/THUMOS14/)
- [ActivityNet v1.3](http://activity-net.org/download.html)

## <span id = "23">Benchmark Results</span>

#### <span id = "231">THUMOS14</span>

|                     Method                     |  Conference   |   IoU@0.1   |   IoU@0.2   |   IoU@0.3   |   IoU@0.4   |   IoU@0.5   |   IoU@0.6   |   IoU@0.7   |
| :--------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "3171">[UNet](#4171)</span>         |   CVPR-2017   |    44.4     |    37.7     |    28.2     |    21.1     |    13.7     |      -      |      -      |
| <span id = "3172">[H&S](#4172)</span>          |   ICCV-2017   |    36.44    |    27.84    |    19.49    |    12.66    |    6.84     |      -      |      -      |
| <span id = "3181">[One-Shot](#4181)</span>     |   CVPR-2018   |      -      |      -      |      -      |      -      |    14.7     |      -      |      -      |
| <span id = "3182">[STPN](#4182)</span>         |   CVPR-2018   |    52.0     |    44.7     |    35.5     |    25.8     |    16.9     |     9.9     |     4.3     |
| <span id = "3183">[AutoLoc](#4183)</span>      |   ECCV-2018   |      -      |      -      |    35.8     |    29.0     |    21.2     |    13.4     |     5.8     |
| <span id = "3184">[W-TAL](#4184)</span>        |   ECCV-2018   |    55.2     |    49.6     |    40.1     |    31.1     |    22.8     |      -      |     7.6     |
| <span id = "3191">[CMCS](#4191)</span>         |   CVPR-2019   |    57.4     |    50.8     |    41.2     |    32.1     |    23.1     |    15.0     |     7.0     |
| <span id = "3192">[STAR](#4192)</span>         |   AAAI-2019   |    68.8     |    60.0     |    48.7     |    34.7     |    23.0     |      -      |      -      |
| <span id = "3193">[CleanNet](#4193)</span>     |   ICCV-2019   |    68.8     |    60.0     |    37.0     |    30.9     |    23.9     |    13.9     |     7.1     |
| <span id = "3194">[TSM](#4194)</span>          |   ICCV-2019   |      -      |      -      |    39.5     |      -      |    24.5     |      -      |     7.1     |
| <span id = "3196">[IWO-Net](#4196)</span>      |   TIP-2019    |    57.6     |    48.9     |    38.9     |    29.3     |    20.5     |      -      |      -      |
| <span id = "3195">[BM](#4195)</span>           |   ICCV-2019   |    60.4     |    56.0     |    46.6     |    37.5     |    26.8     |    17.6     |     9.0     |

#### <span id = "232">ActivityNet v1.3</span>

|        Method         |  Conference   |   IoU@0.5   |   IoU@0.75   |   IoU@0.95   |   IoU@Avg   |
| :-------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [STPN](#4182)         |   CVPR-2018   |    29.3     |     16.9     |     2.6      |    20.07    |
| [CMCS](#4191)         |   CVPR-2019   |    34.0     |     20.9     |     5.7      |    21.2     |
| [STAR](#4192)         |   AAAI-2019   |    31.1     |     18.8     |     4.7      |      -      |
| [BM](#4195)           |   ICCV-2019   |    36.4     |     19.2     |     2.9      |      -      |
| [TSM](#4194)          |   ICCV-2019   |    30.3     |     19.0     |     4.5      |      -      |
| [IWO-Net](#4196)      |   TIP-2019    |    29.8     |     17.6     |     4.7      |      -      |


#### <span id = "233">ActivityNet v1.2</span>

|        Method         |  Conference   |   IoU@0.5   |   IoU@0.75   |   IoU@0.95   |   IoU@Avg   |
| :-------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [UNet](#4171)         |   CVPR-2017   |     7.4     |      3.2     |     0.7      |      -      |
| [AutoLoc](#4183)      |   ECCV-2018   |    27.3     |     15.1     |     3.3      |      -      |
| [W-TALC](#4184)       |   ECCV-2018   |    37.0     |      -       |      -       |    18.0     |
| [CMCS](#4191)         |   CVPR-2019   |    36.8     |     22.0     |     5.6      |    22.4     |
| [STAR](#4192)         |   AAAI-2019   |    31.1     |     18.8     |     4.7      |      -      |
| [TSM](#4194)          |   ICCV-2019   |    28.3     |     17.0     |     3.5      |      -      |
| [CleanNet](#4193)     |   ICCV-2019   |    37.1     |     20.3     |     5.0      |    21.6     |
