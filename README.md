# Awesome Temporal Action Localization: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of temporal action localization/detection and related area (e.g. temporal action proposal) resources.

## Contents
- [Temporal Action Localization](#tal)
    - [Paper](#tal-paper)
        - [2020](#tal-2020) - [2019](#tal-2019) - [2018](#tal-2018) - [2017](#tal-2017) - [2016](#tal-2016)
    - [Dataset](#tal-data)
    - [Benchmark Results](#tal-result)
        - [THUMOS14](#tal-result-thumos14) - [ActivityNet v1.3](#tal-result-activitynet13)
- [Weakly Supervised Temporal Action Localization](#wstal)
    - [Paper](#wstal-paper)
        - [2020](#wstal-2020) - [2019](#wstal-2019) - [2018](#wstal-2018) - [2017](#wstal-2017)
    - [Dataset](#wstal-data)
    - [Benchmark Results](#wstal-result)
        - [THUMOS14](#wstal-thumos14) - [ActivityNet v1.3](#wstal-activitynet13) - [ActivityNet v1.2](#wstal-activitynet12)

---

## <span id = "tal"> **Temporal Action Localization** </span>

## <span id = "tal-paper"> Papers </span>

### <span id = "tal-2020"> 2020 </span>

- <span id = "2203">[[G-TAD]](#1203)</span> [**G-TAD: Sub-Graph Localization for Temporal Action Detection**](https://arxiv.org/abs/1911.11462) - Mengmeng Xu et al, `CVPR 2020`. [[code]](<https://github.com/frostinassiky/gtad>)
- <span id = "2202">[[PBRNet]](#1202)</span> [**Progressive Boundary Refinement Network for Temporal Action Detection**](https://aaai.org/Papers/AAAI/2020GB/AAAI-LiuQ.4870.pdf) - Qinying Liu et al, `AAAI 2020`.
- <span id = "2201">[[AGCN]](#1201)</span> [**Graph Attention based Proposal 3D ConvNets for Action Detection**](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-LiJ.1424.pdf) - Jun Li et al, `AAAI 2020`.

### <span id = "tal-2019"> 2019 </span>

- <span id = "2196">[[PGCN]](#1196)</span> [**Graph Convolutional Networks for Temporal Action Localization**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zeng_Graph_Convolutional_Networks_for_Temporal_Action_Localization_ICCV_2019_paper.pdf) - Runhao Zeng et al, `ICCV 2019`. [[code]](<https://github.com/Alvin-Zeng/PGCN>)
- <span id = "2195">[[RAM]](#1195)</span> [**Graph Convolutional Networks for Temporal Action Localization**](https://ieeexplore.ieee.org/document/8933113) - Peihao Chen et al, `TMM 2019`. 
- <span id = "2194">[[BMN]](#1194)</span> [**BMN: Boundary-Matching Network for Temporal Action Proposal Generation**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Lin_BMN_Boundary-Matching_Network_for_Temporal_Action_Proposal_Generation_ICCV_2019_paper.pdf) - Tianwei Lin et al, `ICCV 2019`.
- <span id = "2193">[[GTAN]](#1193)</span> [**Gaussian Temporal Awareness Networks for Action Localization**](https://arxiv.org/abs/1909.03877) - Fuchen Long et al, `CVPR 2019`.
- <span id = "2192">[[DBS]](#1192)</span> [**Video Imprint Segmentation for Temporal Action Detection in Untrimmed Videos**](https://www.aaai.org/ojs/index.php/AAAI/article/view/4846) - Zhanning Gao et al, `AAAI 2019`.
- <span id = "2191">[[C-TCN]](#1191)</span> [**Deep Concept-wise Temporal Convolutional Networks for Action Localization**](https://arxiv.org/abs/1908.09442) - Xin Li et al, `arXiv 2019`.

### <span id = "tal-2018"> 2018 </span>

- <span id = "2185">[[TAL-Net]](#1185)</span> [**Rethinking the Faster R-CNN Architecture for Temporal Action Localization**](https://arxiv.org/abs/1804.07667) - Yuwei Chao et al, `CVPR 2018`.
- <span id = "2184">[[BSN]](#1184)</span> [**BSN: Boundary Sensitive Network for Temporal Action Proposal Generation**](https://arxiv.org/abs/1806.02964) - Tianwei Lin et al, `ECCV 2018`. [[code]](<https://github.com/wzmsltw/BSN-boundary-sensitive-network>)
- <span id = "2183">[[Action-Search]](#1183)</span> [**Action Search: Spotting Actions in Videos and Its Application to Temporal Action Localization**](https://arxiv.org/abs/1706.04269) - Humam Alwassel et al, `ECCV 2018`. [[code]](<http://www.humamalwassel.com/publication/action-search/>)
- <span id = "2182">[[TPC]](#1182)</span> [**Exploring Temporal Preservation Networks for Precise Temporal Action Localization**](https://arxiv.org/abs/1708.03280) - Ke Yang et al, `AAAI 2018`.
- <span id = "2181">[[Self-Ad]](#1181)</span> [**A Self-Adaptive Proposal Model for Temporal Action Detection based on Reinforcement Learning**](https://arxiv.org/abs/1706.07251) - Jingjia Huang et al, `AAAI 2018`.

### <span id = "tal-2017"> 2017 </span>

- <span id = "2178">[[SSN]](#1178)</span> [**Temporal Action Detection with Structured Segment Networks**](https://arxiv.org/abs/1704.06228) - Yue Zhao et al, `ICCV 2017`. [[code]](<http://yjxiong.me/others/ssn>)
- <span id = "2177">[[R-C3D]](#1177)</span> [**R-C3D: Region Convolutional 3D Network for Temporal Activity Detection**](https://arxiv.org/abs/1703.07814) - Huijuan Xu et al, `ICCV 2017`. [[code]](<http://ai.bu.edu/r-c3d/>)
- <span id = "2176">[[TCN]](#1176)</span> [**Temporal Context Network for Activity Localization in Videos**](https://arxiv.org/abs/1708.02349) - Xiyang Dai et al, `ICCV 2017`.
- <span id = "2175">[[TURN]](#1175)</span> [**TURN TAP: Temporal Unit Regression Network for Temporal Action Proposals**](https://arxiv.org/abs/1703.06189) - Jiyang Gao et al, `ICCV 2017`. [[code]](<https://github.com/jiyanggao/TURN-TAP>)
- <span id = "2174">[[SST]](#1174)</span> [**SST: Single-Stream Temporal Action Proposals**](https://ieeexplore.ieee.org/abstract/document/8100158) - Shyamal Buch et al, `ICCV 2017`.
- <span id = "2173">[[CDC]](#1173)</span> [**CDC: Convolutional-De-Convolutional Networks for Precise Temporal Action Localization in Untrimmed Videos**](https://arxiv.org/abs/1703.01515) - Zheng Shou et al, `CVPR 2017`. [[code]](<https://bibucket.org/columbiadvmm/cdc>)
- <span id = "2172">[[SCC]](#1172)</span> [**SCC: Semantic Context Cascade for Efficient Action Detection**](https://ieeexplore.ieee.org/document/8099821) - Fabian Caba Heilbron et al, `CVPR 2017`.
- <span id = "2171">[[SMS]](#1171)</span> [**Temporal Action Localization by Structured Maximal Sums**](https://arxiv.org/abs/1704.04671) - Zehuan Yuan et al, `CVPR 2017`.

### <span id = "tal-2016"> 2016 </span>

- <span id = "2165">[[S-CNN]](#1165)</span> [**Temporal Action Localization in Untrimmed Videos via Multi-stage CNNs**](https://arxiv.org/abs/1601.02129) - Zheng Shou et al, `CVPR 2016`. [[code]](<https://github.com/zhengshou/scnn/>)
- <span id = "2164">[[PSDF]](#1164)</span> [**Temporal Action Localization with Pyramid of Score Distribution Features**](https://ieeexplore.ieee.org/abstract/document/7780706) - Jun Yuan et al, `CVPR 2016`.
- <span id = "2163">[[FG]](#1163)</span>  [**End-to-end Learning of Action Detection from Frame Glimpses in Videos**](https://arxiv.org/abs/1511.06984) - Serena Yeung et al, `CVPR 2016`.
- <span id = "2162">[[SLM]](#1162)</span> [**Temporal Action Detection Using a Statistical Language Model**](https://ieeexplore.ieee.org/document/7780710) - Alexander Richard et al, `CVPR 2016`.
- <span id = "2161">[[DAPs]](#1161)</span> [**DAPs: Deep Action Proposals for Action Understanding**](https://link.springer.com/chapter/10.1007%2F978-3-319-46487-9_47) - Victor Escorcia et al, `ECCV 2016`.

## <span id = "tal-data"> Dataset </span>

- [THUMOS14](https://www.crcv.ucf.edu/THUMOS14/)
- [ActivityNet v1.3](http://activity-net.org/download.html)

## <span id = "tal-result"> Benchmark Results </span>

#### <span id = "tal-result-thumos14"> THUMOS14 </span>

|                     Method                      |  Conference   |   IoU@0.1   |   IoU@0.2   |   IoU@0.3   |   IoU@0.4   |   IoU@0.5   |   IoU@0.6   |   IoU@0.7   |
| :---------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "1161">[DAPs](#2161)</span>          |   ECCV-2016   |      -      |      -      |      -      |      -      |    13.9     |      -      |      -      |
| <span id = "1162">[SLM](#2162)</span>           |   CVPR-2016   |    39.7     |    35.7     |    30.0     |    23.2     |    15.2     |      -      |      -      |
| <span id = "1163">[FG](#2163)</span>            |   CVPR-2016   |    48.9     |    44.0     |    36.0     |    26.4     |    17.1     |      -      |      -      |
| <span id = "1171">[SMS](#2171)</span>           |   CVPR-2017   |    51.0     |    45.2     |    36.5     |    27.8     |    17.8     |      -      |      -      |
| <span id = "1164">[PSDF](#2164)</span>          |   CVPR-2016   |    51.4     |    42.6     |    33.6     |    26.1     |    18.8     |      -      |      -      |
| <span id = "1165">[S-CNN](#2165)</span>         |   CVPR-2016   |    47.7     |    43.5     |    36.3     |    28.7     |    19.0     |    10.3     |     5.3     |
| <span id = "1174">[SST](#2174)</span>           |   ICCV-2017   |      -      |      -      |      -      |      -      |    23.0     |      -      |      -      |
| <span id = "1173">[CDC](#2173)</span>           |   CVPR-2017   |      -      |      -      |    40.1     |    29.4     |    23.3     |    13.1     |     7.9     |
| <span id = "1175">[TURN](#2175)</span>          |   ICCV-2017   |    54.0     |    50.9     |    44.1     |    34.9     |    25.6     |      -      |      -      |
| <span id = "1176">[TCN](#2176)</span>           |   ICCV-2017   |      -      |      -      |      -      |    33.3     |    25.6     |    15.9     |     9.0     |
| <span id = "1181">[Self-Ad](#2181)</span>       |   AAAI-2018   |      -      |      -      |      -      |      -      |    27.7     |      -      |      -      |
| <span id = "1182">[TPC](#2182)</span>           |   AAAI-2018   |      -      |      -      |    44.1     |    37.1     |    28.2     |    20.6     |    12.7     |
| <span id = "1177">[R-C3D](#2177)</span>         |   ICCV-2017   |    54.5     |    51.5     |    44.8     |    35.6     |    28.9     |      -      |      -      |
| <span id = "1178">[SSN](#2178)</span>           |   ICCV-2017   |    66.0     |    59.4     |    51.9     |    41.0     |    29.8     |      -      |      -      |
| <span id = "1183">[Action-Search](#2183)</span> |   ECCV-2018   |      -      |      -      |    51.8     |    42.4     |    30.8     |    20.2     |    11.1     |
| <span id = "1192">[DBS](#2192)</span>           |   AAAI-2019   |    56.7     |    54.7     |    50.6     |    43.1     |    34.3     |    24.4     |    14.7     |
| <span id = "1184">[BSN](#2184)</span>           |   ECCV-2018   |      -      |      -      |    53.5     |    45.0     |    36.9     |    28.4     |    20.0     |
| <span id = "1201">[AGCN](#2201)</span>          |   AAAI-2020   |    59.3     |    59.6     |    57.1     |    51.6     |    38.6     |    28.9     |     17.0    |
| <span id = "1193">[GTAN](#2193)</span>          |   CVPR-2019   |    69.1     |    63.7     |    57.8     |    47.2     |    38.8     |      -      |      -      |
| <span id = "1194">[BMN](#2194)</span>           |   ICCV-2019   |      -      |      -      |    56.0     |    47.4     |    38.8     |    29.7     |    20.5     |
| <span id = "1185">[TAL-Net](#2185)</span>       |   CVPR-2018   |    59.8     |    57.1     |    53.2     |    48.5     |    42.8     |    33.8     |    20.8     |
| <span id = "1195">[RAM](#2195)</span>           |   TMM-2019    |    65.4     |    63.1     |    58.8     |    52.7     |    43.7     |      -      |      -      |
| <span id = "1196">[PGCN](#2196)</span>          |   ICCV-2019   |    69.5     |    67.8     |    63.6     |    57.8     |    49.1     |      -      |      -      |
| <span id = "1202">[PBRNet](#2202)</span>        |   AAAI-2020   |      -      |      -      |    58.5     |    54.6     |    51.3     |    41.8     |     29.5    |
| <span id = "1203">[G-TAD](#2203)</span>         |   CVPR-2020   |      -      |      -      |    66.4     |    60.4     |    51.6     |    37.6     |     22.9    |

|                     Method                      |  Conference   |   IoU@0.1   |   IoU@0.2   |   IoU@0.3   |   IoU@0.4   |   IoU@0.5   |   IoU@0.6   |   IoU@0.7   |
| :---------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "1191">[C-TCN](#2191)</span>         |     arXiv     |    72.2     |    71.4     |    68.0     |    62.3     |    52.1     |      -      |      -      |

#### <span id = "tal-result-activitynet13"> ActivityNet v1.3 </span>

|         Method         |  Conference   |   IoU@0.5   |   IoU@0.75   |   IoU@0.95   |   IoU@Avg   |
| :--------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [R-C3D](#2177)         |   ICCV-2017   |    26.8     |      -       |      -       |      -      |
| [AGCN](#2201)          |   AAAI-2020   |    30.4     |      -       |      -       |      -      |
| [SCC](#2172)           |   CVPR-2017   |    39.9     |    18.7      |     4.7      |    19.3     |
| [TAL-Net](#2185)       |   CVPR-2018   |    38.23    |    18.30     |     1.30     |    20.22    |
| [RAM](#2195)           |   TMM-2019    |    36.99    |    23.10     |     3.34     |    23.03    |
| [TCN](#2176)           |   ICCV-2017   |    37.49    |    23.47     |     4.47     |    23.58    |
| [CDC](#2173)           |   CVPR-2017   |    45.3     |    26.0      |     0.2      |    23.8     |
| [DBS](#2192)           |   CVPR-2019   |    43.2     |    25.8      |     6.1      |    26.1     |
| [PGCN](#2196)          |   ICCV-2019   |    42.90    |    28.14     |     2.47     |    26.99    |
| [SSN](#2178)           |   ICCV-2017   |    43.26    |    28.70     |     5.63     |    28.28    |
| [BSN](#2184)           |   ECCV-2018   |    46.45    |    29.96     |     8.02     |    30.03    |
| [BMN](#2194)           |   ICCV-2019   |    50.07    |    34.78     |     8.29     |    33.85    |
| [G-TAD](#2203)         |   CVPR-2020   |    50.36    |    34.60     |     9.02     |    34.09    |
| [GTAN](#2193)          |   CVPR-2019   |    52.61    |    34.14     |     8.91     |    34.31    |
| [PBRNet](#2202)        |   AAAI-2020   |    53.96    |    34.97     |     8.98     |    35.01    |

|         Method         |  Conference   |   IoU@0.5   |   IoU@0.75   |   IoU@0.95   |   IoU@Avg   |
| :--------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [C-TCN](#2191)         |     arXiv     |    47.6     |    31.9      |     6.2      |    31.1     |

---

## <span id = "wstal"> **Weakly Supervised Temporal Action Localization** </span>

## <span id = "wstal-paper"> Paper </span>

### <span id = "wstal-2020"> 2020 </span>

- <span id = "4205">[[RPN]](#3205)</span> [**Relational Prototypical Network for Weakly Supervised Temporal Action Localization**](https://aaai.org/Papers/AAAI/2020GB/AAAI-HuangL.1235.pdf) - Linjiang Huang et al, `AAAI 2020`.
- <span id = "4204">[[BaSNet]](#3204)</span> [**Background Suppression Network for Weakly-supervised Temporal Action Localization**](https://arxiv.org/abs/1911.09963) - Pilhyeon Lee et al, `AAAI 2020`.
- <span id = "4203">[[DML]](#3203)</span> [**Weakly Supervised Temporal Action Localization Using Deep Metric Learning**](https://arxiv.org/abs/2001.07793) - Ashraful Islam et al, `WACV 2020`.
- <span id = "4202">[[MCASL]](#3202)</span> [**Action Graphs: Weakly-supervised Action Localization with Graph Convolution Networks**](https://arxiv.org/abs/2002.01449) - Maheen Rashid et al, `WACV 2020`.
- <span id = "4201">[[WSGN]](#3201)</span> [**Weakly Supervised Gaussian Networks for Action Detection**](https://arxiv.org/abs/1904.07774) - Basura Fernando et al, `WACV 2020`.

### <span id = "wstal-2019"> 2019 </span>

- <span id = "4196">[[IWO-Net]](#3196)</span> [**Breaking Winner-Takes-All: Iterative-Winners-Out Networks for Weakly Supervised Temporal Action Localization**](https://ieeexplore.ieee.org/document/8737877) - Runhao Zeng et al, `TIP 2019`.
- <span id = "4195">[[BM]](#3195)</span> [**Weakly-supervised Action Localization with Background Modeling**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Nguyen_Weakly-Supervised_Action_Localization_With_Background_Modeling_ICCV_2019_paper.pdf) - Phuc Xuan Nguyen et al, `ICCV 2019`.
- <span id = "4194">[[TSM]](#3194)</span> [**Temporal Structure Mining for Weakly Supervised Action Detection**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Temporal_Structure_Mining_for_Weakly_Supervised_Action_Detection_ICCV_2019_paper.pdf) - Tan Yu et al, `ICCV 2019`.
- <span id = "4193">[[CleanNet]](#3193)</span> [**Weakly Supervised Temporal Action Localization through Contrast based Evaluation Networks**](https://arxiv.org/abs/1811.07460) - Ziyi Liu et al, `ICCV 2019`.
- <span id = "4192">[[CMCS]](#3192)</span> [**Completeness Modeling and Context Separation for Weakly Supervised Temporal Action Localization**](http://openaccess.thecvf.com/content_CVPR_2019/html/Liu_Completeness_Modeling_and_Context_Separation_for_Weakly_Supervised_Temporal_Action_CVPR_2019_paper.html) - Daochang Liu et al, `CVPR 2019`.
- <span id = "4191">[[STAR]](#3191)</span> [**Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection**](https://arxiv.org/abs/1811.07460) - Yunlu Xu et al, `AAAI 2019`.

### <span id = "wstal-2018"> 2018 </span>

- <span id = "4184">[[W-TALC]](#3184)</span> [**W-TALC: Weakly-supervised Temporal Activity Localization and Classification**](https://arxiv.org/abs/1807.10418) - Sujoy Paul et al, `ECCV 2018`. [[code]](<https://github.com/sujoyp/wtalc-pytorch>)
- <span id = "4183">[[AutoLoc]](#3183)</span> [**AutoLoc: Weakly-supervised Temporal Action Localization in Untrimmed Videos**](https://arxiv.org/abs/1807.08333) - Zheng Shou et al, `ECCV 2018`. [[code]](<https://github.com/zhengshou/AutoLoc>)
- <span id = "4182">[[STPN]](#3182)</span> [**Weakly Supervised Action Localization by Sparse Temporal Pooling Network**](https://arxiv.org/abs/1712.05080) - Phuc Nguyen et al, `CVPR 2018`.
- <span id = "4181">[[One-Shot]](#3181)</span> [**One-Shot Action Localization by Learning Sequence Matching Network**](https://ieeexplore.ieee.org/document/8578255) - Hongtao Yang et al, `CVPR 2018`.

### <span id = "wstal-2017"> 2017 </span>

- <span id = "4172">[[UNet]](#3172)</span> [**UntrimmedNets for Weakly Supervised Action Recognition and Detection**](https://arxiv.org/abs/1703.03329) - Limin Wang et al, `CVPR 2017`. [[code]](<https://github.com/wanglimin/UntrimmedNet>)
- <span id = "4171">[[H&S]](#3171)</span> [**Hide-and-Seek: Forcing a Network to be Meticulous for Weakly-supervised Object and Action Localization**](https://arxiv.org/abs/1704.04232) - Krishna Kumar Singh et al, `CVPR 2017`.

## <span id = "wstal-data"> Dataset </span>

- [THUMOS14](https://www.crcv.ucf.edu/THUMOS14/)
- [ActivityNet v1.3](http://activity-net.org/download.html)

## <span id = "wstal-result"> Benchmark Results </span>

#### <span id = "wstal-thumos14"> THUMOS14 </span>

|                     Method                     |  Conference   |   IoU@0.1   |   IoU@0.2   |   IoU@0.3   |   IoU@0.4   |   IoU@0.5   |   IoU@0.6   |   IoU@0.7   |
| :--------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "3171">[H&S](#4171)</span>          |   ICCV-2017   |    36.44    |    27.84    |    19.49    |    12.66    |    6.84     |      -      |      -      |
| <span id = "3172">[UNet](#4172)</span>         |   CVPR-2017   |    44.4     |    37.7     |    28.2     |    21.1     |    13.7     |      -      |      -      |
| <span id = "3181">[One-Shot](#4181)</span>     |   CVPR-2018   |      -      |      -      |      -      |      -      |    14.7     |      -      |      -      |
| <span id = "3182">[STPN](#4182)</span>         |   CVPR-2018   |    52.0     |    44.7     |    35.5     |    25.8     |    16.9     |     9.9     |     4.3     |
| <span id = "3196">[IWO-Net](#4196)</span>      |   TIP-2019    |    57.6     |    48.9     |    38.9     |    29.3     |    20.5     |      -      |      -      |
| <span id = "3201">[WSGN](#4201)</span>         |   WACV-2020   |    55.3     |    47.6     |    38.9     |    30.0     |    21.1     |      -      |      -      |
| <span id = "3183">[AutoLoc](#4183)</span>      |   ECCV-2018   |      -      |      -      |    35.8     |    29.0     |    21.2     |    13.4     |     5.8     |
| <span id = "3184">[W-TAL](#4184)</span>        |   ECCV-2018   |    55.2     |    49.6     |    40.1     |    31.1     |    22.8     |      -      |     7.6     |
| <span id = "3191">[STAR](#4191)</span>         |   AAAI-2019   |    68.8     |    60.0     |    48.7     |    34.7     |    23.0     |      -      |      -      |
| <span id = "3192">[CMCS](#4192)</span>         |   CVPR-2019   |    57.4     |    50.8     |    41.2     |    32.1     |    23.1     |    15.0     |     7.0     |
| <span id = "3193">[CleanNet](#4193)</span>     |   ICCV-2019   |    68.8     |    60.0     |    37.0     |    30.9     |    23.9     |    13.9     |     7.1     |
| <span id = "3194">[TSM](#4194)</span>          |   ICCV-2019   |      -      |      -      |    39.5     |      -      |    24.5     |      -      |     7.1     |
| <span id = "3202">[MCASL](#4202)</span>        |   WACV-2020   |    63.7     |    56.9     |    47.3     |    36.4     |    26.1     |      -      |      -      |
| <span id = "3195">[BM](#4195)</span>           |   ICCV-2019   |    60.4     |    56.0     |    46.6     |    37.5     |    26.8     |    17.6     |     9.0     |
| <span id = "3204">[BaSNet](#4204)</span>       |   AAAI-2020   |    58.2     |    52.3     |    44.6     |    36.0     |    27.0     |    18.6     |    10.4     |
| <span id = "3205">[RPN](#4205)</span>          |   AAAI-2020   |    62.3     |    57.0     |    48.2     |    37.2     |    27.9     |    16.7     |     8.1     |
| <span id = "3203">[DML](#4203)</span>          |   AAAI-2020   |    62.3     |      -      |    46.8     |      -      |    29.6     |      -      |     9.7     |

#### <span id = "wstal-activitynet13"> ActivityNet v1.3 </span>

|        Method         |  Conference   |   IoU@0.5   |   IoU@0.75   |   IoU@0.95   |   IoU@Avg   |
| :-------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [STPN](#4182)         |   CVPR-2018   |    29.3     |     16.9     |     2.6      |    20.07    |
| [IWO-Net](#4196)      |   TIP-2019    |    29.8     |     17.6     |     4.7      |      -      |
| [TSM](#4194)          |   ICCV-2019   |    30.3     |     19.0     |     4.5      |      -      |
| [STAR](#4192)         |   AAAI-2019   |    31.1     |     18.8     |     4.7      |      -      |
| [CMCS](#4191)         |   CVPR-2019   |    34.0     |     20.9     |     5.7      |    21.2     |
| [BaSNet](#4204)       |   AAAI-2019   |    34.5     |     22.5     |     4.9      |    22.2     |
| [BM](#4195)           |   ICCV-2019   |    36.4     |     19.2     |     2.9      |      -      |

#### <span id = "wstal-activitynet12"> ActivityNet v1.2 </span>

|        Method         |  Conference   |   IoU@0.5   |   IoU@0.75   |   IoU@0.95   |   IoU@Avg   |
| :-------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [UNet](#4171)         |   CVPR-2017   |     7.4     |      3.2     |     0.7      |      -      |
| [AutoLoc](#4183)      |   ECCV-2018   |    27.3     |     15.1     |     3.3      |      -      |
| [TSM](#4194)          |   ICCV-2019   |    28.3     |     17.0     |     3.5      |      -      |
| [MCASL](#4202)        |   AAAI-2020   |    29.4     |      -       |      -       |      -      |
| [STAR](#4192)         |   AAAI-2019   |    31.1     |     18.8     |     4.7      |      -      |
| [DML](#4203)          |   AAAI-2020   |    35.2     |      -       |      -       |      -      |
| [W-TALC](#4184)       |   ECCV-2018   |    37.0     |      -       |      -       |    18.0     |
| [CleanNet](#4193)     |   ICCV-2019   |    37.1     |     20.3     |     5.0      |    21.6     |
| [CMCS](#4191)         |   CVPR-2019   |    36.8     |     22.0     |     5.6      |    22.4     |
| [RPN](#4205)          |   AAAI-2020   |    37.6     |     23.9     |     5.4      |    23.3     |
| [BaSNet](#4204)       |   AAAI-2020   |    38.5     |     24.2     |     5.6      |    24.3     |
