# Awesome Temporal Action Localization: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![Update](https://img.shields.io/github/last-commit/Alvin-Zeng/Awesome-Temporal-Action-Localization?color=green&label=last-updated&logo=update&style=flat-squre) [![Contributor](https://img.shields.io/static/v1?label=by&message=bolixinyu&color=blue&style=flat-squre)](https://github.com/bolixinyu)

A curated list of temporal action localization/detection and related area (e.g. temporal action proposal) resources.

## Contents
- [Temporal Action Localization](#tal)
    - [Paper](#tal-paper)
        - [2021](#tal-2021) - [2020](#tal-2020) - [2019](#tal-2019) - [2018](#tal-2018) - [2017](#tal-2017) - [2016](#tal-2016)
    - [Dataset](#tal-data)
    - [Benchmark Results](#tal-result)
        - [THUMOS14](#tal-result-thumos14) - [ActivityNet v1.3](#tal-result-activitynet13)
- [Weakly Supervised Temporal Action Localization](#wstal)
    - [Paper](#wstal-paper)
        - [2021](#wstal-2021) - [2020](#wstal-2020) - [2019](#wstal-2019) - [2018](#wstal-2018) - [2017](#wstal-2017)
    - [Dataset](#wstal-data)
    - [Benchmark Results](#wstal-result)
        - [THUMOS14](#wstal-thumos14) - [ActivityNet v1.3](#wstal-activitynet13) - [ActivityNet v1.2](#wstal-activitynet12)

---

## <span id = "tal"> **Temporal Action Localization** </span>

## <span id = "tal-paper"> Papers </span>
### <span id = "tal-2021"> 2021 </span>
- <span id = "22112">[[AVFusion]](#12106)</span> [**Hear Me Out: Fusional Approaches for AudioAugmented Temporal Action Localization**](https://arxiv.org/pdf/2106.14118v1.pdf) - Bagchi et al,`arXiv 2021`. [[code]](<https://github.com/skelemoa/tal-hmo/>)
- <span id = "22111">[[ContextLoc]](#12111)</span> [**Enriching Local and Global Contexts for Temporal Action Localization**](https://arxiv.org/pdf/2107.12960.pdf) - Zixin Zhu et al, `ICCV 2021`.
- <span id = "22110">[[CSA]](#12110)</span> [**Class Semantics-based Attention for Action Detection**](https://arxiv.org/pdf/2109.02613.pdf) - Deepak Sridhar et al, `ICCV 2021`.
- <span id = "22109">[[TCANet]](#12109)</span> [**Temporal Context Aggregation Network for Temporal Action Proposal Refinement**](https://arxiv.org/pdf/2103.13141.pdf) - Zhiwu Qing et al, `CVPR 2021`.
- <span id = "22108">[[TadTR]](#12108)</span> [**End-to-end Temporal Action Detection with Transformer**](https://arxiv.org/pdf/2106.10271.pdf) - Xiaolong Liu et al, `arxiv 2021`. [[code]](<https://github.com/xlliu7/TadTR>)
- <span id = "22107">[[Multi-Task TAD]](#12107)</span> [**Three Birds with One Stone: Multi-Task Temporal Action Detection via Recycling Temporal Annotations**](http://arxiv.org/abs/2103.01302) - Zhihui Li et al, `CVPR 2021`.
- <span id = "22106">[[Coarse-Fine Networks]](#12106)</span> [**Coarse-Fine Networks for Temporal Activity Detection in Videos**](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Three_Birds_with_One_Stone_Multi-Task_Temporal_Action_Detection_via_CVPR_2021_paper.pdf) - Kahatapitiya et al, `CVPR 2021`.
- <span id = "22105">[[AFSD]](#12105)</span> [**Learning Salient Boundary Feature for Anchor-free Temporal Action Localization**](https://arxiv.org/abs/2103.13137) - Chuming Lin et al, `CVPR 2021`. [[code]](<https://github.com/TencentYoutuResearch/ActionDetection-AFSD>)
- <span id = "22104">[[MUSeS]](#12104)</span> [**Multi-shot temporal event localization: A Benchmark**](https://arxiv.org/pdf/2012.09434.pdf) - Xiaolong Liu et al, `CVPR 2021`
- <span id = "22103">[[SALAD]](#12103)</span> [**SALAD: Self-Assessment Learning for Action Detection**](https://openaccess.thecvf.com/content/WACV2021/html/Vaudaux-Ruth_SALAD_Self-Assessment_Learning_for_Action_Detection_WACV_2021_paper.html) - Guillaume Vaudaux-Ruth et al, `WACV 2021`
- <span id = "22102">[[RTD-Net]](#12102)</span> [**Relaxed Transformer Decoders for Direct Action Proposal Generation**](https://arxiv.org/pdf/2102.01894) - Jing Tan et al, `arxiv 2021`. [[code]](https://github.com/MCG-NJU/RTD-Action)
- <span id = "22101">[[AGT]](#12101)</span> [**Activity Graph Transformer for Temporal Action Localization**](https://arxiv.org/pdf/2101.08540.pdf) - Megha Nawhal et al, `arxiv 2021`

### <span id = "tal-2020"> 2020 </span>
- <span id = "22011">[[VSGN]](#12011)</span> [**Video Self-Stitching Graph Network for Temporal Action Localization**](https://arxiv.org/pdf/2011.14598.pdf) - Chen Zhao et al, `arxiv 2020`
- <span id = "22010">[[UFA]](#12010)</span> [**Temporal Action Detection with Multi-level Supervision**](https://arxiv.org/pdf/2011.11893.pdf) - Baifeng Shi et al, `arxiv 2020`
- <span id = "22009">[[TSP]](#12009)</span> [**TSP: Temporally-Sensitive Pretraining of Video Encoders for Localization Tasks**](https://arxiv.org/pdf/2011.11479) - Humam Alwassel et al, `arxiv 2020`
- <span id = "22008">[[BSP]](#12008)</span> [**Boundary-sensitive Pre-training for Temporal Localization in Videos**](https://arxiv.org/pdf/2011.10830.pdf) - Mengmeng Xu et al, `arxiv 2020`
- <span id = "22007">[[VAN]](#12007)</span> [**Temporal Action Localization with Variance-Aware Networks**](https://arxiv.org/pdf/2008.11254.pdf) - Ting-Ting Xie et al, `arxiv 2020`
- <span id = "22006">[[TSI]](#12006)</span> [**TSI: Temporal Scale Invariant Network for Action Proposal Generation**](https://openaccess.thecvf.com/content/ACCV2020/html/Liu_TSI_Temporal_Scale_Invariant_Network_for_Action_Proposal_Generation_ACCV_2020_paper.html) - Shuming Liu et al, `ACCV 2020`. [[code]](https://github.com/sming256/TSI)
- <span id = "22005">[[BU-TAL]](#12005)</span> [**Bottom-Up Temporal Action Localization with Mutual Regularization**](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123530528.pdf) - Peisen Zhao et al, `ECCV 2020`.
- <span id = "22004">[[DBG]](#12004)</span> [**Fast Learning of Temporal Action Proposal via Dense Boundary Generator**](https://arxiv.org/pdf/1911.04127) - Chuming Lin et al, `AAAI 2020`. [[code]](<https://github.com/Tencent/ActionDetection-DBG>)
- <span id = "22003">[[G-TAD]](#12003)</span> [**G-TAD: Sub-Graph Localization for Temporal Action Detection**](https://arxiv.org/abs/1911.11462) - Mengmeng Xu et al, `CVPR 2020`. [[code]](<https://github.com/frostinassiky/gtad>)
- <span id = "22002">[[PBRNet]](#12002)</span> [**Progressive Boundary Refinement Network for Temporal Action Detection**](https://aaai.org/Papers/AAAI/2020GB/AAAI-LiuQ.4870.pdf) - Qinying Liu et al, `AAAI 2020`.
- <span id = "22001">[[AGCN]](#12001)</span> [**Graph Attention based Proposal 3D ConvNets for Action Detection**](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-LiJ.1424.pdf) - Jun Li et al, `AAAI 2020`.

### <span id = "tal-2019"> 2019 </span>
- <span id = "21906">[[PGCN]](#11906)</span> [**Graph Convolutional Networks for Temporal Action Localization**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zeng_Graph_Convolutional_Networks_for_Temporal_Action_Localization_ICCV_2019_paper.pdf) - Runhao Zeng et al, `ICCV 2019`. [[code]](<https://github.com/Alvin-Zeng/PGCN>)
- <span id = "21905">[[RAM]](#11905)</span> [**Relation Attention for Temporal Action Localization**](https://ieeexplore.ieee.org/document/8933113) - Peihao Chen et al, `TMM 2019`. 
- <span id = "21904">[[BMN]](#11904)</span> [**BMN: Boundary-Matching Network for Temporal Action Proposal Generation**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Lin_BMN_Boundary-Matching_Network_for_Temporal_Action_Proposal_Generation_ICCV_2019_paper.pdf) - Tianwei Lin et al, `ICCV 2019`.
- <span id = "21903">[[GTAN]](#11903)</span> [**Gaussian Temporal Awareness Networks for Action Localization**](https://arxiv.org/abs/1909.03877) - Fuchen Long et al, `CVPR 2019`.
- <span id = "21902">[[DBS]](#11902)</span> [**Video Imprint Segmentation for Temporal Action Detection in Untrimmed Videos**](https://www.aaai.org/ojs/index.php/AAAI/article/view/4846) - Zhanning Gao et al, `AAAI 2019`.
- <span id = "21901">[[C-TCN]](#11901)</span> [**Deep Concept-wise Temporal Convolutional Networks for Action Localization**](https://arxiv.org/abs/1908.09442) - Xin Li et al, `arXiv 2019`.

### <span id = "tal-2018"> 2018 </span>
- <span id = "21805">[[TAL-Net]](#11805)</span> [**Rethinking the Faster R-CNN Architecture for Temporal Action Localization**](https://arxiv.org/abs/1804.07667) - Yuwei Chao et al, `CVPR 2018`.
- <span id = "21804">[[BSN]](#11804)</span> [**BSN: Boundary Sensitive Network for Temporal Action Proposal Generation**](https://arxiv.org/abs/1806.02964) - Tianwei Lin et al, `ECCV 2018`. [[code]](<https://github.com/wzmsltw/BSN-boundary-sensitive-network>)
- <span id = "21803">[[Action-Search]](#11803)</span> [**Action Search: Spotting Actions in Videos and Its Application to Temporal Action Localization**](https://arxiv.org/abs/1706.04269) - Humam Alwassel et al, `ECCV 2018`. [[code]](<http://www.humamalwassel.com/publication/action-search/>)
- <span id = "21802">[[TPC]](#11802)</span> [**Exploring Temporal Preservation Networks for Precise Temporal Action Localization**](https://arxiv.org/abs/1708.03280) - Ke Yang et al, `AAAI 2018`.
- <span id = "21801">[[Self-Ad]](#11801)</span> [**A Self-Adaptive Proposal Model for Temporal Action Detection based on Reinforcement Learning**](https://arxiv.org/abs/1706.07251) - Jingjia Huang et al, `AAAI 2018`.

### <span id = "tal-2017"> 2017 </span>
- <span id = "21708">[[SSN]](#11708)</span> [**Temporal Action Detection with Structured Segment Networks**](https://arxiv.org/abs/1704.06228) - Yue Zhao et al, `ICCV 2017`. [[code]](<http://yjxiong.me/others/ssn>)
- <span id = "21707">[[R-C3D]](#11707)</span> [**R-C3D: Region Convolutional 3D Network for Temporal Activity Detection**](https://arxiv.org/abs/1703.07814) - Huijuan Xu et al, `ICCV 2017`. [[code]](<http://ai.bu.edu/r-c3d/>)
- <span id = "21706">[[TCN]](#11706)</span> [**Temporal Context Network for Activity Localization in Videos**](https://arxiv.org/abs/1708.02349) - Xiyang Dai et al, `ICCV 2017`.
- <span id = "21705">[[TURN]](#11705)</span> [**TURN TAP: Temporal Unit Regression Network for Temporal Action Proposals**](https://arxiv.org/abs/1703.06189) - Jiyang Gao et al, `ICCV 2017`. [[code]](<https://github.com/jiyanggao/TURN-TAP>)
- <span id = "21704">[[SST]](#11704)</span> [**SST: Single-Stream Temporal Action Proposals**](https://ieeexplore.ieee.org/abstract/document/8100158) - Shyamal Buch et al, `ICCV 2017`.
- <span id = "21703">[[CDC]](#11703)</span> [**CDC: Convolutional-De-Convolutional Networks for Precise Temporal Action Localization in Untrimmed Videos**](https://arxiv.org/abs/1703.01515) - Zheng Shou et al, `CVPR 2017`. [[code]](<https://bibucket.org/columbiadvmm/cdc>)
- <span id = "21702">[[SCC]](#11702)</span> [**SCC: Semantic Context Cascade for Efficient Action Detection**](https://ieeexplore.ieee.org/document/8099821) - Fabian Caba Heilbron et al, `CVPR 2017`.
- <span id = "21701">[[SMS]](#11701)</span> [**Temporal Action Localization by Structured Maximal Sums**](https://arxiv.org/abs/1704.04671) - Zehuan Yuan et al, `CVPR 2017`.

### <span id = "tal-2016"> 2016 </span>
- <span id = "21605">[[S-CNN]](#11605)</span> [**Temporal Action Localization in Untrimmed Videos via Multi-stage CNNs**](https://arxiv.org/abs/1601.02129) - Zheng Shou et al, `CVPR 2016`. [[code]](<https://github.com/zhengshou/scnn/>)
- <span id = "21604">[[PSDF]](#11604)</span> [**Temporal Action Localization with Pyramid of Score Distribution Features**](https://ieeexplore.ieee.org/abstract/document/7780706) - Jun Yuan et al, `CVPR 2016`.
- <span id = "21603">[[FG]](#11603)</span>  [**End-to-end Learning of Action Detection from Frame Glimpses in Videos**](https://arxiv.org/abs/1511.06984) - Serena Yeung et al, `CVPR 2016`.
- <span id = "21602">[[SLM]](#11602)</span> [**Temporal Action Detection Using a Statistical Language Model**](https://ieeexplore.ieee.org/document/7780710) - Alexander Richard et al, `CVPR 2016`.
- <span id = "21601">[[DAPs]](#11601)</span> [**DAPs: Deep Action Proposals for Action Understanding**](https://link.springer.com/chapter/10.1007%2F978-3-319-46487-9_47) - Victor Escorcia et al, `ECCV 2016`.

## <span id = "tal-data"> Dataset </span>

- [THUMOS14](https://www.crcv.ucf.edu/THUMOS14/)
- [ActivityNet v1.3](http://activity-net.org/download.html)

## <span id = "tal-result"> Benchmark Results </span>

#### <span id = "tal-result-thumos14"> THUMOS14 </span>

|                     Method                      |  Conference   |   IoU=0.1   |   IoU=0.2   |   IoU=0.3   |   IoU=0.4   |   IoU=0.5   |   IoU=0.6   |   IoU=0.7   |
| :---------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "11601">[DAPs](#21601)</span>          |   ECCV-2016   |      -      |      -      |      -      |      -      |    13.9     |      -      |      -      |
| <span id = "11602">[SLM](#21602)</span>           |   CVPR-2016   |    39.7     |    35.7     |    30.0     |    23.2     |    15.2     |      -      |      -      |
| <span id = "11603">[FG](#21603)</span>            |   CVPR-2016   |    48.9     |    44.0     |    36.0     |    26.4     |    17.1     |      -      |      -      |
| <span id = "11701">[SMS](#21701)</span>           |   CVPR-2017   |    51.0     |    45.2     |    36.5     |    27.8     |    17.8     |      -      |      -      |
| <span id = "11604">[PSDF](#21604)</span>          |   CVPR-2016   |    51.4     |    42.6     |    33.6     |    26.1     |    18.8     |      -      |      -      |
| <span id = "11605">[S-CNN](#21605)</span>         |   CVPR-2016   |    47.7     |    43.5     |    36.3     |    28.7     |    19.0     |    10.3     |     5.3     |
| <span id = "11704">[SST](#21704)</span>           |   ICCV-2017   |      -      |      -      |      -      |      -      |    23.0     |      -      |      -      |
| <span id = "11703">[CDC](#21703)</span>           |   CVPR-2017   |      -      |      -      |    40.1     |    29.4     |    23.3     |    13.1     |     7.9     |
| <span id = "11705">[TURN](#21705)</span>          |   ICCV-2017   |    54.0     |    50.9     |    44.1     |    34.9     |    25.6     |      -      |      -      |
| <span id = "11706">[TCN](#21706)</span>           |   ICCV-2017   |      -      |      -      |      -      |    33.3     |    25.6     |    15.9     |     9.0     |
| <span id = "11801">[Self-Ad](#21801)</span>       |   AAAI-2018   |      -      |      -      |      -      |      -      |    27.7     |      -      |      -      |
| <span id = "11802">[TPC](#21802)</span>           |   AAAI-2018   |      -      |      -      |    44.1     |    37.1     |    28.2     |    20.6     |    12.7     |
| <span id = "11707">[R-C3D](#21707)</span>         |   ICCV-2017   |    54.5     |    51.5     |    44.8     |    35.6     |    28.9     |      -      |      -      |
| <span id = "11708">[SSN](#21708)</span>           |   ICCV-2017   |    66.0     |    59.4     |    51.9     |    41.0     |    29.8     |      -      |      -      |
| <span id = "11803">[Action-Search](#21803)</span> |   ECCV-2018   |      -      |      -      |    51.8     |    42.4     |    30.8     |    20.2     |    11.1     |
| <span id = "11902">[DBS](#21902)</span>           |   AAAI-2019   |    56.7     |    54.7     |    50.6     |    43.1     |    34.3     |    24.4     |    14.7     |
| <span id = "11804">[BSN](#21804)</span>           |   ECCV-2018   |      -      |      -      |    53.5     |    45.0     |    36.9     |    28.4     |    20.0     |
| <span id = "12001">[AGCN](#22001)</span>          |   AAAI-2020   |    59.3     |    59.6     |    57.1     |    51.6     |    38.6     |    28.9     |     17.0    |
| <span id = "11903">[GTAN](#21903)</span>          |   CVPR-2019   |    69.1     |    63.7     |    57.8     |    47.2     |    38.8     |      -      |      -      |
| <span id = "11904">[BMN](#21904)</span>           |   ICCV-2019   |      -      |      -      |    56.0     |    47.4     |    38.8     |    29.7     |    20.5     |
| <span id = "12004">[DBG](#22004)</span>           |   AAAI-2020   |      -      |      -      |    57.8     |    49.4     |    39.8     |    30.2     |    21.7     |
| <span id = "11805">[TAL-Net](#21805)</span>       |   CVPR-2018   |    59.8     |    57.1     |    53.2     |    48.5     |    42.8     |    33.8     |    20.8     |
| <span id = "11905">[RAM](#21905)</span>           |   TMM-2019    |    65.4     |    63.1     |    58.8     |    52.7     |    43.7     |      -      |      -      |
| <span id = "11906">[PGCN](#21906)</span>          |   ICCV-2019   |    69.5     |    67.8     |    63.6     |    57.8     |    49.1     |      -      |      -      |
| <span id = "12002">[PBRNet](#22002)</span>        |   AAAI-2020   |      -      |      -      |    58.5     |    54.6     |    51.3     |    41.8     |     29.5    |
| <span id = "12003">[G-TAD](#22003)</span>         |   CVPR-2020   |      -      |      -      |    66.4     |    60.4     |    51.6     |    37.6     |     22.9    |
| <span id = "12005">[BU-TAL](#22005)</span>        |   ECCV-2020   |      -      |      -      |    53.9     |    50.7     |    45.4     |    38.0     |     28.5    |
| <span id = "12006">[TSI](#22006)</span>           |   ACCV-2020   |      -      |      -      |    61.0     |    52.1     |    42.6     |    33.2     |    22.4     |
| <span id = "12103">[SALAD](#22103)</span>         |   WACV-2021   |    73.3     |    70.7     |    65.7     |    57.0     |    44.6     |      -      |      -      |
| <span id = "12104">[MUSES](#22104)</span>         |   CVPR-2021   |      -      |      -      |    68.9     |    64.0     |    56.9     |     46.3    |     31.0    |
| <span id = "12105">[AFSD](#22105)</span>          |   CVPR-2021   |      -      |      -      |    67.3     |    62.4     |    55.5     |     43.7    |     31.1    |
| <span id = "12107">[Multi-Task TAD](#22107)</span>|   CVPR-2021   |      -      |      -      |    63.2     |    58.5     |    54.8     |     44.3    |     32.4    |
| <span id = "12109">[TCANet](#22109)</span>        |   CVPR-2021   |      -      |      -      |    60.6     |    53.2     |    44.6     |     36.8    |     26.7    |
| <span id = "12110">[CSA](#22110)</span>           |   ICCV-2021   |      -      |      -      |    64.4     |    58.0     |    49.2     |     38.2    |     27.8    |
| <span id = "12111">[ContextLoc](#22110)</span>    |   ICCV-2021   |      -      |      -      |    68.3     |    63.8     |    54.3     |     41.8    |     26.2    |

|                     Method                      |  Conference   |   IoU=0.1   |   IoU=0.2   |   IoU=0.3   |   IoU=0.4   |   IoU=0.5   |   IoU=0.6   |   IoU=0.7   |
| :---------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "11901">[C-TCN](#21901)</span>       |     arXiv     |    72.2     |    71.4     |    68.0     |    62.3     |    52.1     |      -      |      -      |
| <span id = "12011">[VSGN](#22011)</span>        |     arXiv     |      -      |      -      |    66.7     |    60.4     |    52.4     |    41.0     |    30.4     |
| <span id = "12010">[UFA](#22010)</span>         |     arXiv     |      -      |      -      |    45.6     |    36.4     |    26.2     |    15.5     |    7.1      |
| <span id = "12009">[TSP](#22009)</span>         |     arXiv     |      -      |      -      |    69.1     |    63.3     |    53.5     |    40.4     |    26.0     |
| <span id = "12007">[VAN](#22008)</span>         |     arXiv     |      -      |      -      |    55.0     |    48.6     |    39.2     |    26.9     |    15.0     |
| <span id = "12101">[AGT](#22101)</span>         |     arXiv     |    72.1     |    69.8     |    65.0     |    58.1     |    50.2     |      -      |      -      |
| <span id = "12102">[RTD-Net](#22102)</span>     |     arXiv     |      -      |      -      |    68.3     |    62.3     |    51.9     |    38.8     |    23.7     |
| <span id = "12108">[TadTR](#22108)</span>       |     arXiv     |      -      |      -      |    59.6     |    55.0     |    46.6     |    35.7     |    24.3     |
| <span id = "12112">[AVFusion](#22106)</span>    |   arXiv-2021  |      -      |      -      |    70.18    |    64.98    |    57.18    |     45.42   |     28.86   |

#### <span id = "tal-result-activitynet13"> ActivityNet v1.3 </span>

|         Method         |  Conference   |   IoU=0.5   |   IoU=0.75   |   IoU=0.95   |   Avg   |
| :--------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [R-C3D](#21707)         |   ICCV-2017   |    26.8     |      -       |      -       |      -      |
| [AGCN](#22001)          |   AAAI-2020   |    30.4     |      -       |      -       |      -      |
| [SCC](#21702)           |   CVPR-2017   |    39.9     |    18.7      |     4.7      |    19.3     |
| [TAL-Net](#21805)       |   CVPR-2018   |    38.23    |    18.30     |     1.30     |    20.22    |
| [RAM](#21905)           |   TMM-2019    |    36.99    |    23.10     |     3.34     |    23.03    |
| [TCN](#21706)           |   ICCV-2017   |    37.49    |    23.47     |     4.47     |    23.58    |
| [CDC](#21703)           |   CVPR-2017   |    45.3     |    26.0      |     0.2      |    23.8     |
| [DBS](#21902)           |   CVPR-2019   |    43.2     |    25.8      |     6.1      |    26.1     |
| [PGCN](#21906)          |   ICCV-2019   |    42.90    |    28.14     |     2.47     |    26.99    |
| [SSN](#21708)           |   ICCV-2017   |    43.26    |    28.70     |     5.63     |    28.28    |
| [BSN](#21804)           |   ECCV-2018   |    46.45    |    29.96     |     8.02     |    30.03    |
| [BMN](#21904)           |   ICCV-2019   |    50.07    |    34.78     |     8.29     |    33.85    |
| [G-TAD](#22003)         |   CVPR-2020   |    50.36    |    34.60     |     9.02     |    34.09    |
| [GTAN](#21903)          |   CVPR-2019   |    52.61    |    34.14     |     8.91     |    34.31    |
| [PBRNet](#22002)        |   AAAI-2020   |    53.96    |    34.97     |     8.98     |    35.01    |
| [BU-TAL](#22005)        |   ECCV-2020   |    43.47    |    33.91     |     9.21     |    30.12    |
| [TSI](#22006)           |   ACCV-2020   |    51.18    |    35.02     |     6.59     |    34.15    |
| [SALAD](#22103)         |   WACV-2021   |    51.72    |    31.21     |     3.33     |    31.02    |
| [MUSES](#22104)         |   CVPR-2021   |    50.02    |    34.97     |     6.57     |    33.99    |
| [AFSD](#22105)          |   CVPR-2021   |    52.38    |    35.27     |     6.47     |    34.39    |
| [Multi-Task TAD](#22107)|   CVPR-2021   |    57.8     |    37.6      |     9.6      |    35.0     |
| [TCANet](#22109)        |   CVPR-2021   |    52.27    |    36.73     |     6.86     |    35.52    |
| [CSA](#22110)           |   ICCV-2021   |    51.88    |    36.88     |     8.74     |    35.69    |   
| [ContextLoc](#22111)    |   ICCV-2021   |    56.01    |    35.19     |     3.55     |    34.23    |

|         Method         |  Conference   |   IoU=0.5   |   IoU=0.75   |   IoU=0.95   |   IoU=Avg   |
| :--------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [C-TCN](#21901)        |     arXiv     |    47.6     |    31.9      |     6.2      |    31.1     |
| [VSGN](#22011)         |     arXiv     |    52.4     |    36.0      |     8.4      |    35.1     |
| [TSP](#22009)          |     arXiv     |    51.3     |    37.2      |     9.3      |    35.8     |
| [BSP](#22008)          |     arXiv     |    50.1     |    34.7      |     7.9      |    34.0     |
| [RTD-Net](#22102)      |     arXiv     |    46.4     |    30.4      |     8.6      |    30.5     |
| [TadTR](#22108)        |     arXiv     |    47.57    |    31.65     |     7.98     |    31.32    |
| [AVFusion](#22112)     |   arXiv       |    52.73    |    37.78     |     9.39     |    36.63    |

---

## <span id = "wstal"> **Weakly Supervised Temporal Action Localization** </span>

## <span id = "wstal-paper"> Paper </span>

### <span id = "wstal-2021"> 2021 </span>
- <span id = "42101">[[HAM-Net]](#32101)</span> [**A Hybrid Attention Mechanism for Weakly-Supervised Temporal Action Localization**](https://arxiv.org/pdf/2101.00545) - Ashraful Islam et al, `arxiv 2021`. [[code]](https://github.com/asrafulashiq/hamnet)

### <span id = "wstal-2020"> 2020 </span>
- <span id = "42013">[[ECM]](#32013)</span> [**Equivalent Classification Mapping for Weakly Supervised Temporal Action Localization**](https://arxiv.org/pdf/2008.07728.pdf) - Le Yang et al, `arxiv 2020`
- <span id = "42012">[[TCA]](#32012)</span> [**Learning Temporal Co-Attention Models for Unsupervised Video Action Localization**](https://openaccess.thecvf.com/content_CVPR_2020/html/Gong_Learning_Temporal_Co-Attention_Models_for_Unsupervised_Video_Action_Localization_CVPR_2020_paper.html) - Guoqiang Gong et al, `CVPR 2020`
- <span id = "42011">[[EM-MIL]](#32011)</span> [**Weakly-Supervised Action Localization with Expectation-Maximization Multi-Instance**](https://arxiv.org/abs/2004.00163) - Zhekun Luo et al, `ECCV 2020`.
- <span id = "42010">[[SF-Net]](#32010)</span> [**SF-Net: Single-Frame Supervision for Temporal Action Localization**](https://arxiv.org/abs/2003.06845) - Fan Ma et al, `ECCV 2020`. [[code]](<https://github.com/Flowerfan/SF-Net>)
- <span id = "42009">[[A2CL-PT]](#32009)</span> [**Adversarial Background-Aware Loss for Weakly-supervised Temporal Activity Localization**](https://arxiv.org/abs/2007.06643) - Kyle Min et al, `ECCV 2020`.
- <span id = "42008">[[TSCN]](#32008)</span> [**Two-Stream Consensus Network for Weakly-Supervised Temporal Action Localization**](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123510035.pdf) - Yuanhao Zhai et al, `ECCV 2020`.
- <span id = "42007">[[ActionBytes]](#32007)</span> [**ActionBytes: Learning from Trimmed Videos to Localize Actions**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Jain_ActionBytes_Learning_From_Trimmed_Videos_to_Localize_Actions_CVPR_2020_paper.pdf) - Mihir Jain et al, `CVPR 2020`.
- <span id = "42006">[[DGAM]](#32006)</span> [**Weakly-Supervised Action Localization by Generative Attention Modeling**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Shi_Weakly-Supervised_Action_Localization_by_Generative_Attention_Modeling_CVPR_2020_paper.pdf) - Baifeng Shi et al, `CVPR 2020`.
- <span id = "42005">[[RPN]](#32005)</span> [**Relational Prototypical Network for Weakly Supervised Temporal Action Localization**](https://ojs.aaai.org//index.php/AAAI/article/view/6760) - Linjiang Huang et al, `AAAI 2020`.
- <span id = "42004">[[BaSNet]](#32004)</span> [**Background Suppression Network for Weakly-supervised Temporal Action Localization**](https://arxiv.org/abs/1911.09963) - Pilhyeon Lee et al, `AAAI 2020`.
- <span id = "42003">[[DML]](#32003)</span> [**Weakly Supervised Temporal Action Localization Using Deep Metric Learning**](https://arxiv.org/abs/2001.07793) - Ashraful Islam et al, `WACV 2020`.
- <span id = "42002">[[MCASL]](#32002)</span> [**Action Graphs: Weakly-supervised Action Localization with Graph Convolution Networks**](https://arxiv.org/abs/2002.01449) - Maheen Rashid et al, `WACV 2020`.
- <span id = "42001">[[WSGN]](#32001)</span> [**Weakly Supervised Gaussian Networks for Action Detection**](https://arxiv.org/abs/1904.07774) - Basura Fernando et al, `WACV 2020`.

### <span id = "wstal-2019"> 2019 </span>
- <span id = "41908">[[MAAN]](#31908)</span> [**Marginalized Average Attentional Network for Weakly Supervised Learning**](https://openreview.net/pdf?id=HkljioCcFQ) - Yuan Yuan et al, `ICLR 2019`.
- <span id = "41907">[[IWO-Net]](#31907)</span> [**Breaking Winner-Takes-All: Iterative-Winners-Out Networks for Weakly Supervised Temporal Action Localization**](https://ieeexplore.ieee.org/document/8737877) - Runhao Zeng et al, `TIP 2019`.
- <span id = "41906">[[3C-Net]](#31906)</span> [**3C-Net: Category Count and Center Loss for Weakly-Supervised Action Localization**](https://ieeexplore.ieee.org/document/8737877) - Sanath Narayan et al, `TIP 2019`. [[code]](<https://github.com/naraysa/3c-net>)
- <span id = "41905">[[BM]](#31905)</span> [**Weakly-supervised Action Localization with Background Modeling**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Nguyen_Weakly-Supervised_Action_Localization_With_Background_Modeling_ICCV_2019_paper.pdf) - Phuc Xuan Nguyen et al, `ICCV 2019`.
- <span id = "41904">[[TSM]](#31904)</span> [**Temporal Structure Mining for Weakly Supervised Action Detection**](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Temporal_Structure_Mining_for_Weakly_Supervised_Action_Detection_ICCV_2019_paper.pdf) - Tan Yu et al, `ICCV 2019`.
- <span id = "41903">[[CleanNet]](#31903)</span> [**Weakly Supervised Temporal Action Localization through Contrast based Evaluation Networks**](https://openaccess.thecvf.com/content_ICCV_2019/html/Liu_Weakly_Supervised_Temporal_Action_Localization_Through_Contrast_Based_Evaluation_Networks_ICCV_2019_paper.html) - Ziyi Liu et al, `ICCV 2019`.
- <span id = "41902">[[CMCS]](#31902)</span> [**Completeness Modeling and Context Separation for Weakly Supervised Temporal Action Localization**](http://openaccess.thecvf.com/content_CVPR_2019/html/Liu_Completeness_Modeling_and_Context_Separation_for_Weakly_Supervised_Temporal_Action_CVPR_2019_paper.html) - Daochang Liu et al, `CVPR 2019`.
- <span id = "41901">[[STAR]](#31901)</span> [**Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection**](https://arxiv.org/abs/1811.07460) - Yunlu Xu et al, `AAAI 2019`.

### <span id = "wstal-2018"> 2018 </span>
- <span id = "41804">[[W-TALC]](#31804)</span> [**W-TALC: Weakly-supervised Temporal Activity Localization and Classification**](https://arxiv.org/abs/1807.10418) - Sujoy Paul et al, `ECCV 2018`. [[code]](<https://github.com/sujoyp/wtalc-pytorch>)
- <span id = "41803">[[AutoLoc]](#31803)</span> [**AutoLoc: Weakly-supervised Temporal Action Localization in Untrimmed Videos**](https://arxiv.org/abs/1807.08333) - Zheng Shou et al, `ECCV 2018`. [[code]](<https://github.com/zhengshou/AutoLoc>)
- <span id = "41802">[[STPN]](#31802)</span> [**Weakly Supervised Action Localization by Sparse Temporal Pooling Network**](https://arxiv.org/abs/1712.05080) - Phuc Nguyen et al, `CVPR 2018`.
- <span id = "41801">[[One-Shot]](#31801)</span> [**One-Shot Action Localization by Learning Sequence Matching Network**](https://ieeexplore.ieee.org/document/8578255) - Hongtao Yang et al, `CVPR 2018`.

### <span id = "wstal-2017"> 2017 </span>
- <span id = "41702">[[UNet]](#31702)</span> [**UntrimmedNets for Weakly Supervised Action Recognition and Detection**](https://arxiv.org/abs/1703.03329) - Limin Wang et al, `CVPR 2017`. [[code]](<https://github.com/wanglimin/UntrimmedNet>)
- <span id = "41701">[[H&S]](#31701)</span> [**Hide-and-Seek: Forcing a Network to be Meticulous for Weakly-supervised Object and Action Localization**](https://arxiv.org/abs/1704.04232) - Krishna Kumar Singh et al, `CVPR 2017`.

## <span id = "wstal-data"> Dataset </span>

- [THUMOS14](https://www.crcv.ucf.edu/THUMOS14/)
- [ActivityNet v1.3](http://activity-net.org/download.html)

## <span id = "wstal-result"> Benchmark Results </span>

#### <span id = "wstal-thumos14"> THUMOS14 </span>

|                     Method                     |  Conference   |   IoU=0.1   |   IoU=0.2   |   IoU=0.3   |   IoU=0.4   |   IoU=0.5   |   IoU=0.6   |   IoU=0.7   |
| :--------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "31701">[H&S](#41701)</span>          |   ICCV-2017   |    36.44    |    27.84    |    19.49    |    12.66    |    6.84     |      -      |      -      |
| <span id = "31702">[UNet](#41702)</span>         |   CVPR-2017   |    44.4     |    37.7     |    28.2     |    21.1     |    13.7     |      -      |      -      |
| <span id = "31801">[One-Shot](#41801)</span>     |   CVPR-2018   |      -      |      -      |      -      |      -      |    14.7     |      -      |      -      |
| <span id = "31802">[STPN](#41802)</span>         |   CVPR-2018   |    52.0     |    44.7     |    35.5     |    25.8     |    16.9     |     9.9     |     4.3     |
| <span id = "31907">[IWO-Net](#41907)</span>      |   TIP-2019    |    57.6     |    48.9     |    38.9     |    29.3     |    20.5     |      -      |      -      |
| <span id = "31908">[MAAN](#41908)</span>         |   ICLR-2019   |    59.8     |    50.8     |    41.1     |    30.6     |    20.3     |     12.0    |     6.9     |
| <span id = "32001">[WSGN](#42001)</span>         |   WACV-2020   |    55.3     |    47.6     |    38.9     |    30.0     |    21.1     |      -      |      -      |
| <span id = "31803">[AutoLoc](#41803)</span>      |   ECCV-2018   |      -      |      -      |    35.8     |    29.0     |    21.2     |    13.4     |     5.8     |
| <span id = "31804">[W-TAL](#41804)</span>        |   ECCV-2018   |    55.2     |    49.6     |    40.1     |    31.1     |    22.8     |      -      |     7.6     |
| <span id = "31901">[STAR](#41901)</span>         |   AAAI-2019   |    68.8     |    60.0     |    48.7     |    34.7     |    23.0     |      -      |      -      |
| <span id = "31902">[CMCS](#41902)</span>         |   CVPR-2019   |    57.4     |    50.8     |    41.2     |    32.1     |    23.1     |    15.0     |     7.0     |
| <span id = "31903">[CleanNet](#41903)</span>     |   ICCV-2019   |      -      |      -      |    37.0     |    30.9     |    23.9     |    13.9     |     7.1     |
| <span id = "31904">[TSM](#41904)</span>          |   ICCV-2019   |      -      |      -      |    39.5     |      -      |    24.5     |      -      |     7.1     |
| <span id = "32002">[MCASL](#42002)</span>        |   WACV-2020   |    63.7     |    56.9     |    47.3     |    36.4     |    26.1     |      -      |      -      |
| <span id = "31906">[3C-Net](#41906)</span>       |   ICCV-2019   |    59.1     |    53.5     |    44.2     |    34.1     |    26.6     |      -      |     8.1     |
| <span id = "31905">[BM](#41905)</span>           |   ICCV-2019   |    60.4     |    56.0     |    46.6     |    37.5     |    26.8     |    17.6     |     9.0     |
| <span id = "32004">[BaSNet](#42004)</span>       |   AAAI-2020   |    58.2     |    52.3     |    44.6     |    36.0     |    27.0     |    18.6     |    10.4     |
| <span id = "32005">[RPN](#42005)</span>          |   AAAI-2020   |    62.3     |    57.0     |    48.2     |    37.2     |    27.9     |    16.7     |     8.1     |
| <span id = "32003">[DML](#42003)</span>          |   AAAI-2020   |    62.3     |      -      |    46.8     |      -      |    29.6     |      -      |     9.7     |
| <span id = "32006">[DGAM](#42006)</span>         |   CVPR-2020   |    60.0     |    54.2     |    46.8     |    38.2     |    28.8     |    19.8     |    11.5     |
| <span id = "32007">[ActionBytes](#42007)</span>  |   CVPR-2020   |      -      |      -      |    43.0     |    35.8     |    29.0     |      -      |     9.5     |
| <span id = "32009">[A2CL-PT](#42009)</span>      |   ECCV-2020   |    61.2     |    56.1     |    48.1     |    39.0     |    30.1     |    19.2     |    10.6     |
| <span id = "32010">[SF-Net](#42010)</span>     |   ECCV-2020   |    71.0     |    63.4     |    53.2     |    40.7     |    29.3     |    18.4     |     9.6     |
| <span id = "32011">[EM-MIL](#42011)</span>     |   ECCV-2020   |    59.1     |    52.7     |    45.5     |    36.8     |    30.5     |    22.7     |    16.4     |
| <span id = "32012">[TCA](#42012)</span>        |   CVPR-2020   |      -      |      -      |    46.9     |    38.9     |    30.1     |    19.8     |    10.4     |

|                     Method                     |  Conference   |   IoU=0.1   |   IoU=0.2   |   IoU=0.3   |   IoU=0.4   |   IoU=0.5   |   IoU=0.6   |   IoU=0.7   |
| :--------------------------------------------: | :-----------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| <span id = "32013">[ECM](#42013)</span>       |     arXiv     |    62.6     |    55.1     |    46.5     |    38.2     |    29.1     |     19.5    |      10.9     |
| <span id = "32101">[HAM-Net](#42101)</span>       |     arXiv     |    65.4     |    59.0     |    50.3     |    41.1     |    31.0     |     20.7    |      11.2     |

#### <span id = "wstal-activitynet13"> ActivityNet v1.3 </span>

|        Method         |  Conference   |   IoU=0.5   |   IoU=0.75   |   IoU=0.95   |   IoU=Avg   |
| :-------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [STPN](#41802)         |   CVPR-2018   |    29.3     |     16.9     |     2.6      |    20.07    |
| [IWO-Net](#41907)      |   TIP-2019    |    29.8     |     17.6     |     4.7      |      -      |
| [TSM](#41904)          |   ICCV-2019   |    30.3     |     19.0     |     4.5      |      -      |
| [STAR](#41901)         |   AAAI-2019   |    31.1     |     18.8     |     4.7      |      -      |
| [CMCS](#41902)         |   CVPR-2019   |    34.0     |     20.9     |     5.7      |    21.2     |
| [BaSNet](#42004)       |   AAAI-2019   |    34.5     |     22.5     |     4.9      |    22.2     |
| [MAAN](#41908)         |   ICLR-2019   |    33.7     |     21.9     |     5.5      |      -      |
| [BM](#41905)           |   ICCV-2019   |    36.4     |     19.2     |     2.9      |      -      |
| [A2CL-PT](#42009)      |   ECCV-2020   |    36.8     |     22.0     |     5.2      |    22.5     |

|        Method         |  Conference   |   IoU=0.5   |   IoU=0.75   |   IoU=0.95   |   IoU=Avg   |
| :-------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [ECM](#42013)          |     arxiv     |    36.7     |    23.6     |     5.9      |    23.5     |

#### <span id = "wstal-activitynet12"> ActivityNet v1.2 </span>

|        Method         |  Conference   |   IoU=0.5   |   IoU=0.75   |   IoU=0.95   |   IoU=Avg   |
| :-------------------: | :-----------: | :---------: | :----------: | :----------: | :---------: |
| [UNet](#41701)         |   CVPR-2017   |     7.4     |      3.2     |     0.7      |      -      |
| [AutoLoc](#41803)      |   ECCV-2018   |    27.3     |     15.1     |     3.3      |      -      |
| [TSM](#41904)          |   ICCV-2019   |    28.3     |     17.0     |     3.5      |      -      |
| [MCASL](#42002)        |   AAAI-2020   |    29.4     |      -       |      -       |      -      |
| [STAR](#41901)         |   AAAI-2019   |    31.1     |     18.8     |     4.7      |      -      |
| [DML](#42003)          |   AAAI-2020   |    35.2     |      -       |      -       |      -      |
| [W-TALC](#41804)       |   ECCV-2018   |    37.0     |      -       |      -       |    18.0     |
| [CleanNet](#41903)     |   ICCV-2019   |    37.1     |     20.3     |     5.0      |    21.6     |
| [3C-Net](#41906)       |   ICCV-2019   |    37.2     |      -       |      -       |      -      |
| [CMCS](#41902)         |   CVPR-2019   |    36.8     |     22.0     |     5.6      |    22.4     |
| [RPN](#42005)          |   AAAI-2020   |    37.6     |     23.9     |     5.4      |    23.3     |
| [BaSNet](#42004)       |   AAAI-2020   |    38.5     |     24.2     |     5.6      |    24.3     |
| [ActionBytes](#42007)  |   CVPR-2020   |    39.4     |      -       |      -       |      -      |
| [EM-MIL](#42011)      |   ECCV-2020   |    37.4     |      -       |      -       |      -      |
| [TCA](#42012)          |   CVPR-2020   |    40.0     |    25.0     |     4.6      |    24.6     |
