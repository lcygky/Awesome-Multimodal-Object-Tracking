<div align="center">
<img src="https://github.com/983632847/Awesome-Multimodal-Object-Tracking/blob/main/MMOT.png" width="600">
  
**Awesome Multi-modal Object Tracking (MMOT)**
  
------
<p align="center">
</p>
</div>

# Awesome Multi-modal Object Tracking (MMOT)
A continuously updated project to track the latest progress in multi-modal object tracking.

#### If this repository can bring you some inspiration, we would feel greatly honored.
#### If you like our project, please give us a star ⭐ on this GitHub.
#### If you have any suggestions, please feel free to contact: [andyzhangchunhui@gmail.com](andyzhangchunhui@gmail.com). 

## :collision: Highlights
- 2024.05.30: The Paper of WebUOT-1M was Online [arXiv](https://arxiv.org/abs/2405.19818).
- 2024.05.24: The Report of Awesome MMOT Project was Online [arXiv](https://arxiv.org/abs/2405.14200) [知乎](https://zhuanlan.zhihu.com/p/699538389).
- 2024.05.20: Awesome MMOT Project Started.


## Contents

- [Survey](#Survey) 
- [Vision-Language Tracking (RGBL Tracking)](#vision-language-tracking)
- - [Datasets](#datasets)
- - [Papers](#papers)
- [RGBE Tracking](#rgbe-tracking)
- - [Datasets](#datasets)
- - [Papers](#papers)
- [RGBD Tracking](#rgbd-tracking)
- - [Datasets](#datasets)
- - [Papers](#papers)
- [RGBT Tracking](#rgbt-tracking)
- - [Datasets](#datasets)
- - [Papers](#papers)
- [Miscellaneous (RGB+X)](#miscellaneous)
- - [Datasets](#datasets)
- - [Papers](#papers)
- [Awesome Repositories for MMOT](#awesome-repositories-for-mmot)

## Citation

If you find our work useful in your research, please consider citing:
```
@article{zhang2024awesome,
  title={Awesome Multi-modal Object Tracking},
  author={Zhang, Chunhui and Liu, Li and Wen, Hao and Zhou, Xi and Wang, Yanfeng},
  journal={arXiv preprint arXiv:2405.14200},
  year={2024}
}
```


## Survey
- Pengyu Zhang, Dong Wang, Huchuan Lu.<br />
  "Multi-modal Visual Tracking: Review and Experimental Comparison." ArXiv (2022).
  [[paper](https://arxiv.org/abs/2012.04176)] 

- Zhangyong Tang, Tianyang Xu, Xiao-Jun Wu.<br />
  "A Survey for Deep RGBT Tracking." ArXiv (2022).
  [[paper](https://arxiv.org/abs/2201.09296)] 

- Jinyu Yang, Zhe Li, Song Yan, Feng Zheng, Aleš Leonardis, Joni-Kristian Kämäräinen, Ling Shao.<br />
  "RGBD Object Tracking: An In-depth Review." ArXiv (2022).
  [[paper](https://arxiv.org/abs/2203.14134)] 

- Chenglong Li, Andong Lu, Lei Liu, Jin Tang.<br />
  "Multi-modal visual tracking: a survey. 多模态视觉跟踪方法综述" Journal of Image and Graphics.中国图象图形学报 (2023).
  [[paper](http://www.cjig.cn/html/2023/1/20230103.htm)] 

- Ou Zhou, Ying Ge, Zhang Dawei, and Zheng Zhonglong.<br />
  "A Survey of RGB-Depth Object Tracking. RGB-D 目标跟踪综述" Journal of Computer-Aided Design & Computer Graphics. 计算机辅助设计与图形学学报 (2024).
  [[paper](https://www.jcad.cn/cn/article/doi/10.3724/SP.J.1089.null.2023-00537)] 

- Zhang, ZhiHao and Wang, Jun and Zang, Zhuli and Jin, Lei and Li, Shengjie and Wu, Hao and Zhao, Jian and Bo, Zhang.<br />
  "Review and Analysis of RGBT Single Object Tracking Methods: A Fusion Perspective." ACM Transactions on Multimedia Computing, Communications and Applications (2024).
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3651308)] 

- **MV-RGBT & MoETrack:** Zhangyong Tang, Tianyang Xu, Zhenhua Feng, Xuefeng Zhu, He Wang, Pengcheng Shao, Chunyang Cheng, Xiao-Jun Wu, Muhammad Awais, Sara Atito, Josef Kittler.<br />
  "Revisiting RGBT Tracking Benchmarks from the Perspective of Modality Validity: A New Benchmark, Problem, and Method." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.00168)] 
  [[code](https://github.com/Zhangyong-Tang/MoETrack)]

- Xingchen Zhang and Ping Ye and Henry Leung and Ke Gong and Gang Xiao.<br />
  "Object fusion tracking based on visible and infrared images: A comprehensive review." Information Fusion (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S1566253520302657)] 

- Mingzheng Feng and Jianbo Su.<br />
  "RGBT tracking: A comprehensive review." Information Fusion (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S1566253524002707)] 


## Vision-Language Tracking
### Datasets
| Dataset | Pub. & Date  | WebSite | Introduction |
|:-----:|:-----:|:-----:|:-----:|
|  [OTB99-L](https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Tracking_by_Natural_CVPR_2017_paper.pdf)   |  CVPR-2017  |  [OTB99-L](https://github.com/QUVA-Lab/lang-tracker)  |   99 videos  |  
|  [LaSOT](https://arxiv.org/abs/2009.03465)   |   CVPR-2019   |  [LaSOT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)  | 1400 videos  |  
|  [LaSOT_EXT](https://arxiv.org/pdf/1809.07845.pdf)   |   IJCV-2021   |  [LaSOT_EXT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)  |  150 videos  |  
|  [TNL2K](https://arxiv.org/pdf/2103.16746.pdf)   |   CVPR-2021  |  [TNL2K](https://github.com/wangxiao5791509/TNL2K_evaluation_toolkit)  |  2000 videos  |  
|  [WebUAV-3M](https://arxiv.org/abs/2201.07425)   |   TPAMI-2023   |  [WebUAV-3M](https://github.com/983632847/WebUAV-3M)  |  4500 videos, 3.3 million frames, UAV tracking, vision-language-audio |  
|  [MGIT](https://huuuuusy.github.io/files/MGIT.pdf)   |   NeurIPS-2023   |  [MGIT](http://videocube.aitestunion.com/)  |  150 long video sequences, 2.03 million frames,  three semantic grains (i.e., action, activity, and story)  |  
|  [VastTrack](https://arxiv.org/abs/2403.03493)   |   arXiv-2024   |  [VastTrack](https://github.com/HengLan/VastTrack)  |  50,610 video sequences, 4.2 million frames, 2,115 classes  |  
|  [WebUOT-1M](https://arxiv.org/abs/2405.19818)   |   arXiv-2024   |  [WebUOT-1M](https://github.com/983632847/Awesome-Multimodal-Object-Tracking)  |  The first million-scale underwater object tracking dataset contains 1,500 video sequences, 1.1 million frames |  


### Papers
#### 2024
- **DTLLM-VLT:** Xuchen Li, Xiaokun Feng, Shiyu Hu, Meiqi Wu, Dailing Zhang, Jing Zhang, Kaiqi Huang.<br />
  "DTLLM-VLT: Diverse Text Generation for Visual Language Tracking Based on LLM." CVPRW (2024).
  [[paper](https://arxiv.org/abs/2405.12139)] 

- **UVLTrack:** Yinchao Ma, Yuyang Tang, Wenfei Yang, Tianzhu Zhang, Jinpeng Zhang, Mengxue Kang.<br />
  "Unifying Visual and Vision-Language Tracking via Contrastive Learning." AAAI (2024).
  [[paper](https://arxiv.org/abs/2401.11228)] 
  [[code](https://github.com/OpenSpaceAI/UVLTrack)]

- **QueryNLT:** Yanyan Shao, Shuting He, Qi Ye, Yuchao Feng, Wenhan Luo, Jiming Chen.<br />
  "Context-Aware Integration of Language and Visual References for Natural Language Tracking." CVPR (2024).
  [[paper](https://arxiv.org/abs/2403.19975)] 
  [[code](https://github.com/twotwo2/QueryNLT)]

- **OSDT:** Guangtong Zhang, Bineng Zhong, Qihua Liang, Zhiyi Mo, Ning Li, Shuxiang Song.<br />
  "One-Stream Stepwise Decreasing for Vision-Language Tracking." TCSVT (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10510485)] 

- **TTCTrack:** Zhongjie Mao; Yucheng Wang; Xi Chen; Jia Yan.<br />
  "Textual Tokens Classification for Multi-Modal Alignment in Vision-Language Tracking." ICASSP (2024).
  [[paper](https://ieeexplore.ieee.org/document/10446122)] 

- **MMTrack:** Zheng, Yaozong and Zhong, Bineng and Liang, Qihua and Li, Guorong and Ji, Rongrong and Li, Xianxian.<br />
  "Toward Unified Token Learning for Vision-Language Tracking." TCSVT (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10208210)] 

- Ping Ye, Gang Xiao, Jun Liu .<br />
  "Multimodal Features Alignment for Vision–Language Object Tracking." Remote Sensing (2024).
  [[paper](https://www.mdpi.com/2072-4292/16/7/1168)] 



#### 2023

- **All in One:** Chunhui Zhang, Xin Sun, Li Liu, Yiqian Yang, Qiong Liu, Xi Zhou, Yanfeng Wang.<br />
  "All in One: Exploring Unified Vision-Language Tracking with Multi-Modal Alignment." ACM MM (2023).
  [[paper](https://arxiv.org/abs/2307.03373)] 
  [[code](https://github.com/983632847/All-in-One)]

- **CiteTracker:** Xin Li, Yuqing Huang, Zhenyu He, Yaowei Wang, Huchuan Lu, Ming-Hsuan Yang.<br />
  "CiteTracker: Correlating Image and Text for Visual Tracking." ICCV (2023).
  [[paper](https://arxiv.org/abs/2308.11322)] 
  [[code]( https://github.com/NorahGreen/CiteTracker)]

- **JointNLT:** Li Zhou, Zikun Zhou, Kaige Mao, Zhenyu He.<br />
  "Joint Visual Grounding and Tracking with Natural Language Specifcation." CVPR (2023).
  [[paper](https://arxiv.org/abs/2303.12027#:~:text=Tracking%20by%20natural%20language%20specification%20aims%20to%20locate,tracking%20model%20to%20implement%20these%20two%20steps%2C%20respectively.)] 
  [[code](https://github.com/lizhou-cs/JointNLT)]

- **DecoupleTNL:** Ma, Ding and Wu, Xiangqian.<br />
  "Tracking by Natural Language Specification with Long Short-term Context Decoupling." ICCV (2023).
  [[paper](https://ieeexplore.ieee.org/document/10378598/references#references)] 

- Haojie Zhao, Xiao Wang, Dong Wang, Huchuan Lu, Xiang Ruan.<br />
  "Transformer vision-language tracking via proxy token guided
cross-modal fusion." PRL (2023).
  [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0167865523000545)] 

- **OVLM:** Zhang, Huanlong and Wang, Jingchao and Zhang, Jianwei and Zhang, Tianzhu and Zhong, Bineng.<br />
  "One-Stream Vision-Language Memory Network for Object Tracking." TMM (2023).
  [[paper](https://ieeexplore.ieee.org/document/10149530)] 

- **SATracker:** Jiawei Ge, Xiangmei Chen, Jiuxin Cao, Xuelin Zhu, Bo Liu.<br />
  "Beyond Visual Cues: Synchronously Exploring Target-Centric Semantics for Vision-Language Tracking." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2311.17085)] 
  
- **VLATrack:** Zuo, Jixiang and Wu, Tao and Shi, Meiping and Liu, Xueyan and Zhao, Xijun.<br />
  "Multi-Modal Object Tracking with Vision-Language Adaptive Fusion and Alignment." RICAI (2023).
  [[paper](https://ieeexplore.ieee.org/document/10489325)] 

- **VLT_TT:** Mingzhe Guo, Zhipeng Zhang, Liping Jing, Haibin Ling, Heng Fan.<br />
  "Divert More Attention to Vision-Language Object Tracking." ArXiv (2023).
  [[paper]()] 
  [[code](https://github.com/JudasDie/SOTS)]

#### 2022

- **VLT_TT:** Mingzhe Guo, Zhipeng Zhang, Heng Fan, Liping Jing.<br />
  "Divert More Attention to Vision-Language Tracking." NeurIPS (2022).
  [[paper](https://arxiv.org/abs/2207.01076)] 
  [[code](https://github.com/JudasDie/SOTS)]


- **AdaRS:** Li, Yihao and Yu, Jun and Cai, Zhongpeng and Pan, Yuwen.<br />
  "Cross-modal Target Retrieval for Tracking by Natural Language." CVPR Workshops (2022).
  [[paper](https://ieeexplore.ieee.org/document/9857151)] 

#### 2021

- **SNLT:** Qi Feng, Vitaly Ablavsky, Qinxun Bai, Stan Sclaroff.<br />
  "Siamese Natural Language Tracker: Tracking by Natural Language Descriptions with Siamese Trackers." CVPR  (2021).
  [[paper](https://arxiv.org/abs/1912.02048)] 
  [[code](https://github.com/fredfung007/snlt)]


## RGBE Tracking
### Datasets
| Dataset | Pub. & Date  | WebSite | Introduction |
|:-----:|:-----:|:-----:|:-----:|
|  [FE108](https://arxiv.org/abs/2109.09052)   |  ICCV-2021   |  [FE108](https://zhangjiqing.com/dataset/)  |  108 event videos  |  
|  [COESOT](https://arxiv.org/abs/2211.11010)   |   arXiv-2022   |  [COESOT](https://github.com/Event-AHU/COESOT)  |  1354 RGB-event video pairs  |  
|  [VisEvent](https://arxiv.org/abs/2108.05015)   |   TC-2023   |  [VisEvent](https://github.com/wangxiao5791509/VisEvent_SOT_Benchmark)  |  820 RGB-event video pairs |  
|  [EventVOT](https://arxiv.org/abs/2309.14611)   |   CVPR-2023   |  [EventVOT](https://github.com/Event-AHU/EventVOT_Benchmark)  |  1141 event videos  |  
|  [CRSOT](https://arxiv.org/abs/2401.02826)   |   arXiv-2024   |  [CRSOT](https://github.com/Event-AHU/Cross_Resolution_SOT)  |   1030 RGB-event video pairs |  
|  [FELT](https://arxiv.org/pdf/2403.05839.pdf)   |   arXiv-2024   |  [FELT](https://github.com/Event-AHU/FELT_SOT_Benchmark)  |  742 RGB-event video pairs  |  


### Papers
#### 2024
- **Mamba-FETrack:** Ju Huang, Shiao Wang, Shuai Wang, Zhe Wu, Xiao Wang, Bo Jiang.<br />
  "Mamba-FETrack: Frame-Event Tracking via State Space Model." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2404.18174)] 
  [[code](https://github.com/Event-AHU/Mamba_FETrack)]

- **AMTTrack:** Xiao Wang, Ju Huang, Shiao Wang, Chuanming Tang, Bo Jiang, Yonghong Tian, Jin Tang, Bin Luo.<br />
  "Long-term Frame-Event Visual Tracking: Benchmark Dataset and Baseline." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.02826)] 
  [[code](https://github.com/Event-AHU/FELT_SOT_Benchmark)]

- **TENet:** Pengcheng Shao, Tianyang Xu, Zhangyong Tang, Linze Li, Xiao-Jun Wu, Josef Kittler.<br />
  "TENet: Targetness Entanglement Incorporating with Multi-Scale Pooling and Mutually-Guided Fusion for RGB-E Object Tracking." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.05004)] 
  [[code](https://github.com/SSSpc333/TENet)]

- **HDETrack:** Xiao Wang, Shiao Wang, Chuanming Tang, Lin Zhu, Bo Jiang, Yonghong Tian, Jin Tang.<br />
  "Event Stream-based Visual Object Tracking: A High-Resolution Benchmark Dataset and A Novel Baseline." CVPR (2024).
  [[paper](https://arxiv.org/abs/2309.14611)] 
  [[code](https://github.com/Event-AHU/EventVOT_Benchmark)]

- Yabin Zhu, Xiao Wang, Chenglong Li, Bo Jiang, Lin Zhu, Zhixiang Huang, Yonghong Tian, Jin Tang.<br />
  "CRSOT: Cross-Resolution Object Tracking using Unaligned Frame and Event Cameras." ArXiv (2024).
  [[paper](https://arxiv.org/pdf/2403.05839.pdf)] 
  [[code](https://github.com/Event-AHU/FELT_SOT_Benchmark)]

- **CDFI:** Jiqing Zhang, Xin Yang, Yingkai Fu, Xiaopeng Wei, Baocai Yin, Bo Dong.<br />
  "Object Tracking by Jointly Exploiting Frame and Event Domain." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2109.09052)]

- **MMHT:** Hongze Sun, Rui Liu, Wuque Cai, Jun Wang, Yue Wang, Huajin Tang, Yan Cui, Dezhong Yao, Daqing Guo.<br />
  "Reliable Object Tracking by Multimodal Hybrid Feature Extraction and Transformer-Based Fusion." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.17903)] 


#### 2023
- Zhiyu Zhu, Junhui Hou, Dapeng Oliver Wu.<br />
  "Cross-modal Orthogonal High-rank Augmentation for RGB-Event Transformer-trackers." ICCV (2023).
  [[paper](https://arxiv.org/abs/2307.04129)] 
  [[code](https://github.com/ZHU-Zhiyu/High-Rank_RGB-Event_Tracker)]

- **AFNet:** Jiqing Zhang, Yuanchen Wang, Wenxi Liu, Meng Li, Jinpeng Bai, Baocai Yin, Xin Yang.<br />
  "Frame-Event Alignment and Fusion Network for High Frame Rate Tracking." CVPR (2023).
  [[paper](https://arxiv.org/abs/2305.15688)] 
  [[code](https://github.com/Jee-King/AFNet)]

- **RT-MDNet:** Xiao Wang, Jianing Li, Lin Zhu, Zhipeng Zhang, Zhe Chen, Xin Li, Yaowei Wang, Yonghong Tian, Feng Wu.<br />
  "VisEvent: Reliable Object Tracking via Collaboration of Frame and Event Flows." TC (2023).
  [[paper](https://arxiv.org/abs/2108.05015)] 
  [[code](https://github.com/wangxiao5791509/VisEvent_SOT_Benchmark)]

#### 2022
- **Event-tracking:** Zhiyu Zhu, Junhui Hou, Xianqiang Lyu.<br />
  "Learning Graph-embedded Key-event Back-tracing for Object Tracking in Event Clouds." NeurIPS (2022).
  [[paper](https://dl.acm.org/doi/10.5555/3600270.3600812)] 
  [[code](https://github.com/ZHU-Zhiyu/Event-tracking)]

- **STNet:** Jiqing Zhang, Bo Dong, Haiwei Zhang, Jianchuan Ding, Felix Heide, Baocai Yin, Xin Yang.<br />
  "Spiking Transformers for Event-based Single Object Tracking." CVPR (2022).
  [[paper](https://ieeexplore.ieee.org/document/9879994)] 
  [[code](https://github.com/Jee-King/CVPR2022_STNet)]

- **CEUTrack:** Chuanming Tang, Xiao Wang, Ju Huang, Bo Jiang, Lin Zhu, Jianlin Zhang, Yaowei Wang, Yonghong Tian.<br />
  "Revisiting Color-Event based Tracking: A Unified Network, Dataset, and Metric." ArXiv (2022).
  [[paper](https://arxiv.org/abs/2211.11010)] 
  [[code](https://github.com/Event-AHU/COESOT)]


#### 2021

- **CFE:** Jiqing Zhang, Kai Zhao, Bo Dong, Yingkai Fu, Yuxin Wang, Xin Yang, Baocai Yin.<br />
  "Multi-domain Collaborative Feature Representation for Robust Visual Object Tracking." The Visual Computer (2021).
  [[paper]()] 
  [[paper](https://arxiv.org/abs/2108.04521)]


## RGBD Tracking
### Datasets
| Dataset | Pub. & Date  | WebSite | Introduction |
|:-----:|:-----:|:-----:|:-----:|
|  [PTB](https://vision.princeton.edu/projects/2013/tracking/paper.pdf)   |   ICCV-2013   |  [PTB](https://tracking.cs.princeton.edu/index.html)  |  100 sequences  |  
|  [STC](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8026575)   |   TC-2018   |  [STC](https://beardatashare.bham.ac.uk/dl/fiVnhJRjkyNN8QjSAoiGSiBY/RGBDdataset.zip)  |  36 sequences  |  
|  [CDTB](https://arxiv.org/pdf/1907.00618.pdf)   |   ICCV-2019  |  [CDTB](https://www.votchallenge.net/vot2019/dataset.html)  |  80 sequences  |  
|  [DepthTrack](https://arxiv.org/abs/2108.13962)   |   ICCV-2021   |  [DepthTrack](http://doi.org/10.5281/zenodo.4716441)  |  200 sequences  |  
|  [RGBD1K](https://arxiv.org/abs/2208.09787)   |   AAAI-2023   |  [RGBD1K](https://github.com/xuefeng-zhu5/RGBD1K)  |   1,050 sequences, 2.5M frames |  
|  [DTTD](https://arxiv.org/abs/2302.05991)   |   CVPR Workshops-2023   |  [DTTD](https://github.com/augcog/DTTDv1)  | 103 scenes, 55691 frames   |  
|  [ARKitTrack](https://arxiv.org/abs/2303.13885)   |   CVPR-2023   |  [ARKitTrack](https://arkittrack.github.io)  |  300 RGB-D sequences, 455 targets, 229.7K video frames  |  

### Papers
#### 2024
- **SSLTrack:** Xue-Feng Zhu, Tianyang Xu, Sara Atito, Muhammad Awais,
Xiao-Jun Wu, Zhenhua Feng, Josef Kittler.<br />
  "Self-supervised learning for RGB-D object tracking." PR (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0031320324002942)] 

- **VADT:** Zhang, Guangtong and Liang, Qihua and Mo, Zhiyi and Li, Ning and Zhong, Bineng.<br />
  "Visual Adapt for RGBD Tracking." ICASSP (2024).
  [[paper](https://ieeexplore.ieee.org/document/10447728)] 

- **FECD:** Xue-Feng Zhu, Tianyang Xu, Xiao-Jun Wu, Josef Kittler.<br />
  "Feature enhancement and coarse-to-fine detection for RGB-D tracking." PRL (2024).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0167865524000412)] 

- **CDAAT:** Xue-Feng Zhu, Tianyang Xu, Xiao-Jun Wu, Zhenhua Feng, Josef Kittler.<br />
  "Adaptive Colour-Depth Aware Attention for RGB-D Object Tracking." SPL (2024).
  [[paper](https://ieeexplore.ieee.org/document/10472092/)] 
  [[code](https://github.com/xuefeng-zhu5/CDAAT)]


#### 2023
- **SPT:** Xue-Feng Zhu, Tianyang Xu, Zhangyong Tang, Zucheng Wu, Haodong Liu, Xiao Yang, Xiao-Jun Wu, Josef Kittler.<br />
  "RGBD1K: A Large-scale Dataset and Benchmark for RGB-D Object Tracking." AAAI (2023).
  [[paper](https://arxiv.org/pdf/2208.09787.pdf)] 
  [[code](https://github.com/xuefeng-zhu5/RGBD1K)]

- **EMT:** Yang, Jinyu and Gao, Shang and Li, Zhe and Zheng, Feng and Leonardis, Ale\v{s}.<br />
  "Resource-Effcient RGBD Aerial Tracking." CVPR (2023).
  [[paper](https://ieeexplore.ieee.org/document/10204937/)] 
  [[code](https://github.com/yjybuaa/RGBDAerialTracking)]

#### 2022
- **Track-it-in-3D:** Jinyu Yang, Zhongqun Zhang, Zhe Li, Hyung Jin Chang, Aleš Leonardis, Feng Zheng.<br />
  "Towards Generic 3D Tracking in RGBD Videos: Benchmark and Baseline." ECCV  (2022).
  [[paper](https://link.springer.com/chapter/10.1007/978-3-031-20047-2_7)] 
  [[code](https://github.com/yjybuaa/Track-it-in-3D)]

- **DMTracker:** Shang Gao, Jinyu Yang, Zhe Li, Feng Zheng, Aleš Leonardis, Jingkuan Song.<br />
  "Learning Dual-Fused Modality-Aware Representations for RGBD Tracking." ECCVW (2022).
  [[paper](https://arxiv.org/abs/2211.03055)] 


#### 2021

- **DeT:** Song Yan, Jinyu Yang, Jani Käpylä, Feng Zheng, Aleš Leonardis, Joni-Kristian Kämäräinen.<br />
  "DepthTrack: Unveiling the Power of RGBD Tracking." ICCV (2021).
  [[paper](https://arxiv.org/abs/2108.13962)] 
  [[code](https://github.com/xiaozai/DeT)]

- **TSDM:** Pengyao Zhao, Quanli Liu, Wei Wang and Qiang Guo.<br />
  "TSDM: Tracking by SiamRPN++ with a Depth-refiner and a Mask-generator." ICPR (2021).
  [[paper](https://arxiv.org/ftp/arxiv/papers/2005/2005.04063.pdf)] 
  [[code](https://github.com/lql-team/TSDM)]

- **3s-RGBD:** Feng Xiao, Qiuxia Wu, Han Huang.<br />
  "Single-scale siamese network based RGB-D object tracking with adaptive bounding boxes." Neurocomputing (2021).
  [[paper](https://www.sciencedirect.com/sdfe/reader/pii/S0925231221005439/pdf)] 
  

#### 2020
- **DAL:** Yanlin Qian, Alan Lukezic, Matej Kristan, Joni-Kristian Kämäräinen, Jiri Matas.<br />
  "DAL : A deep depth-aware long-term tracker." ICPR (2020).
  [[paper](https://arxiv.org/abs/1912.00660)] 
  [[code](https://github.com/xiaozai/DAL)]

- **RF-CFF:** Yong Wang, Xian Wei, Hao Shen, Lu Ding, Jiuqing Wan.<br />
  "Robust fusion for RGB-D tracking using CNN features." Applied Soft Computing Journal (2020).
  [[paper](https://www.sciencedirect.com/sdfe/reader/pii/S1568494620302428/pdf)] 

- **SiamOC:** Wenli Zhang, Kun Yang, Yitao Xin, Rui Meng.<br />
  "An Occlusion-Aware RGB-D Visual Object Tracking Method Based on Siamese Network.." ICSP (2020).
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9320907)] 

- **WCO:** Weichun Liu, Xiaoan Tang, Chengling Zhao.<br />
  "Robust RGBD Tracking via Weighted Convlution Operators." Sensors (2020).
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8950173/)] 

#### 2019
- **OTR:** Ugur Kart, Alan Lukezic, Matej Kristan, Joni-Kristian Kamarainen, Jiri Matas.<br />
  "Object Tracking by Reconstruction with View-Specific Discriminative Correlation Filters." CVPR (2019).
  [[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kart_Object_Tracking_by_Reconstruction_With_View-Specific_Discriminative_Correlation_Filters_CVPR_2019_paper.pdf)] 
  [[code](https://github.com/ugurkart/OTR)]

- **H-FCN:** Ming-xin Jiang, Chao Deng, Jing-song Shan, Yuan-yuan Wang, Yin-jie Jia, Xing Sun.<br />
  "Hierarchical multi-modal fusion FCN with attention model for RGB-D tracking." Information Fusion (2019).
  [[paper](https://www.sciencedirect.com/sdfe/reader/pii/S1566253517306784/pdf)] 

- Kuai, Yangliu and Wen, Gongjian and Li, Dongdong and Xiao, Jingjing.<br />
  "Target-Aware Correlation Filter Tracking in RGBD Videos." IEEE Sensors Journal (2019).
  [[paper](https://ieeexplore.ieee.org/abstract/document/8752050)] 

- **RGBD-OD:** Yujun Xie, Yao Lu, Shuang Gu.<br />
  "RGB-D Object Tracking with Occlusion Detection." CIS (2019).
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9023755)] 

- **3DMS:** Alexander Gutev, Carl James Debono.<br />
  "Exploiting Depth Information to Increase Object Tracking Robustness." ICST (2019).
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8861628/)] 

- **CA3DMS:** Ye Liu, Xiao-Yuan Jing, Jianhui Nie, Hao Gao, Jun Liu, Guo-Ping Jiang.<br />
  "Context-Aware Three-Dimensional Mean-Shift With Occlusion Handling for Robust Object Tracking in RGB-D Videos." TMM (2019).
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8425768)] 
  [[code](https://github.com/yeliu2013/ca3dms-toh)]

- **Depth-CCF:** Guanqun Li, Lei Huang, Peichang Zhang, Qiang Li, YongKai Huo.<br />
  "Depth Information Aided Constrained correlation Filter for Visual Tracking." GSKI  (2019).
  [[paper](https://iopscience.iop.org/article/10.1088/1755-1315/234/1/012005)] 


#### 2018
- **STC:** Jingjing Xiao, Rustam Stolkin, Yuqing Gao, Aleš Leonardis.<br />
  "Robust Fusion of Color and Depth Data for RGB-D Target Tracking Using Adaptive Range-Invariant Depth Models and Spatio-Temporal Consistency Constraints." TC (2018).
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8026575)] 
  [[code](https://github.com/shine636363/RGBDtracker)]

- Kart, Uğur and Kämäräinen, Joni-Kristian and Matas, Jiří.<br />
  "How to Make an RGBD Tracker ?." ECCVW (2018).
  [[paper](https://link.springer.com/chapter/10.1007/978-3-030-11009-3_8)] 
  [[code](https://github.com/ugurkart/rgbdconverter)]

- Jiaxu Leng, Ying Liu.<br />
  "Real-Time RGB-D Visual Tracking With Scale Estimation and Occlusion Handling." IEEE Access (2018).
  [[paper](https://ieeexplore.ieee.org/document/8353501)] 

- **DM-DCF:** Uğur Kart, Joni-Kristian Kämäräinen, Jiří Matas, Lixin Fan, Francesco Cricri.<br />
  "Depth Masked Discriminative Correlation Filter." ICPR (2018).
  [[paper](https://arxiv.org/pdf/1802.09227.pdf)] 

- **OACPF:** Yayu Zhai, Ping Song, Zonglei Mou, Xiaoxiao Chen, Xiongjun Liu.<br />
  "Occlusion-Aware Correlation Particle FilterTarget Tracking Based on RGBD Data." Access (2018).
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8463446)] 

- **RT-KCF:** Han Zhang, Meng Cai, Jianxun Li.<br />
  "A Real-time RGB-D tracker based on KCF." CCDC (2018).
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8407972)] 

#### 2017
- **ODIOT:** Wei-Long Zheng, Shan-Chun Shen, Bao-Liang Lu.<br />
  "Online Depth Image-Based Object Tracking with Sparse Representation and Object Detection." Neural Process Letters (2017).
  [[paper](https://link.springer.com/content/pdf/10.1007/s11063-016-9509-y.pdf)] 

- **ROTSL:** Zi-ang Ma, Zhi-yu Xiang.<br />
  "Robust Object Tracking with RGBD-based Sparse Learning." ITEE  (2017).
  [[paper](https://link.springer.com/article/10.1631/FITEE.1601338)] 

#### 2016

- **DLS:** Ning An, Xiao-Guang Zhao, Zeng-Guang Hou.<br />
  "Online RGB-D Tracking via Detection-Learning-Segmentation." ICPR  (2016).
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7899805)] 

- **DS-KCF_shape:** Sion Hannuna, Massimo Camplani, Jake Hall, Majid Mirmehdi, Dima Damen, Tilo Burghardt, Adeline Paiement, Lili Tao.<br />
  "DS-KCF: A Real-time Tracker for RGB-D Data." RTIP (2016).
  [[paper](https://link.springer.com/content/pdf/10.1007/s11554-016-0654-3.pdf)] 
  [[code](https://github.com/mcamplan/DSKCF_JRTIP2016)]

- **3D-T:** Adel Bibi, Tianzhu Zhang, Bernard Ghanem.<br />
  "3D Part-Based Sparse Tracker with Automatic Synchronization and Registration." CVPR  (2016).
  [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Bibi_3D_Part-Based_Sparse_CVPR_2016_paper.pdf)] 
  [[code](https://github.com/adelbibi/3D-Part-Based-Sparse-Tracker-with-Automatic-Synchronization-and-Registration)]

- **OAPF:** Kourosh Meshgia, Shin-ichi Maedaa, Shigeyuki Obaa, Henrik Skibbea, Yu-zhe Lia, Shin Ishii.<br />
  "Occlusion Aware Particle Filter Tracker to Handle Complex and Persistent Occlusions." CVIU  (2016).
  [[paper](http://ishiilab.jp/member/meshgi-k/files/ai/prl14/OAPF.pdf)] 

#### 2015
- **CDG:** Huizhang Shi, Changxin Gao, Nong Sang.<br />
  "Using Consistency of Depth Gradient to Improve Visual Tracking in RGB-D sequences." CAC (2015).
  [[paper](https://ieeexplore.ieee.org/document/7382555)] 

- **DS-KCF:** Massimo Camplani, Sion Hannuna, Majid Mirmehdi, Dima Damen, Adeline Paiement, Lili Tao, Tilo Burghardt.<br />
  "Real-time RGB-D Tracking with Depth Scaling Kernelised Correlation Filters and Occlusion Handling." BMVC (2015).
  [[paper](https://core.ac.uk/reader/78861956)] 
  [[code](https://github.com/mcamplan/DSKCF_BMVC2015)]

- **DOHR:** Ping Ding, Yan Song.<br />
  "Robust Object Tracking Using Color and Depth Images with a Depth Based Occlusion Handling and Recovery." FSKD (2015).
  [[paper](https://ieeexplore.ieee.org/document/7382068)] 

- **ISOD:** Yan Chen, Yingju Shen, Xin Liu, Bineng Zhong.<br />
  "3D Object Tracking via Image Sets and Depth-Based Occlusion Detection." SP  (2015).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0165168414004204)] 

- **OL3DC:** Bineng Zhong, Yingju Shen, Yan Chen, Weibo Xie, Zhen Cui, Hongbo Zhang, Duansheng Chen ,Tian Wang, Xin Liu, Shujuan Peng, Jin Gou, Jixiang Du, Jing Wang, Wenming Zheng.<br />
  "Online Learning 3D Context for Robust Visual Tracking." Neurocomputing  (2015).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0925231214013757)] 


#### 2014
- **MCBT:** Qi Wang, Jianwu Fang, Yuan Yuan. Multi-Cue Based Tracking.<br />
  "Multi-Cue Based Tracking." Neurocomputing  (2014).
  [[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.700.8771&rep=rep1&type=pdf)] 

#### 2013
- **PT:** Shuran Song, Jianxiong Xiao.<br />
  "Tracking Revisited using RGBD Camera: Unified Benchmark and Baselines." ICCV (2013).
  [[paper](https://vision.princeton.edu/projects/2013/tracking/paper.pdf)] 
  [[code](https://tracking.cs.princeton.edu/index.html)]

#### 2012

- Matteo Munaro, Filippo Basso and Emanuele Menegatti
.<br />
  "Tracking people within groups with RGB-D data." IROS (2012).
  [[paper](https://ieeexplore.ieee.org/abstract/document/6385772/)] 

- **AMCT:** Germán Martín García, Dominik Alexander Klein, Jörg Stückler, Simone Frintrop, Armin B. Cremers.<br />
  "Adaptive Multi-cue 3D Tracking of Arbitrary Objects." JDOS (2012).
  [[paper](https://link.springer.com/chapter/10.1007/978-3-642-32717-9_36)] 

## RGBT Tracking
### Datasets
| Dataset | Pub. & Date  | WebSite | Introduction |
|:-----:|:-----:|:-----:|:-----:|
|  [GTOT](https://ieeexplore.ieee.org/abstract/document/7577747)   |   TIP-2016   |  [GTOT](https://pan.baidu.com/s/1QNidEo-HepRaS6OIZr7-Cw)  |  50 video pairs, 1.5W frames |  
|  [RGBT210](https://dl.acm.org/doi/10.1145/3123266.3123289)   |   ACM MM-2017   |  [RGBT210](https://drive.google.com/file/d/0B3i2rdXLNbdUTkhsLVRwcTBTMlU/view?resourcekey=0-vytg_w3hqlQfLhoiS2J8Dg)  |  210 video pairs  |  
|  [RGBT234](https://arxiv.org/abs/1805.08982)   |   PR-2018   |  [RGBT234](https://sites.google.com/view/ahutracking001/)  |   234 video pairs, the extension of RGBT210  |  
|  [LasHeR](https://arxiv.org/pdf/2104.13202.pdf)   |   TIP-2021  |  [LasHeR](https://github.com/BUGPLEASEOUT/LasHeR)  | 1224 video pairs, 730K frames  |  
|  [VTUAV](https://arxiv.org/pdf/2204.04120.pdf)   |   CVPR-2022   |  [VTUAV](https://zhang-pengyu.github.io/DUT-VTUAV/)  |  Visible-thermal UAV tracking, 500 sequences, 1.7 million high-resolution frame pairs |  
|  [MV-RGBT](https://arxiv.org/abs/2405.00168)   |   arXiv-2024   |  [MV-RGBT](https://github.com/Zhangyong-Tang/MoETrack)  | 122 video pairs, 89.9K frames   |  



### Papers

#### 2024
- **GMMT:** Zhangyong Tang, Tianyang Xu, Xuefeng Zhu, Xiao-Jun Wu, Josef Kittler.<br />
  "Generative-based Fusion Mechanism for Multi-Modal Tracking." AAAI (2024).
  [[paper](https://arxiv.org/abs/2309.01728)] 
  [[code](https://github.com/Zhangyong-Tang/GMMT)]

- **BAT:** Bing Cao, Junliang Guo, Pengfei Zhu, Qinghua Hu.<br />
  "Bi-directional Adapter for Multi-modal Tracking." AAAI (2024).
  [[paper](https://arxiv.org/abs/2312.10611)] 
  [[code](https://github.com/SparkTempest/BAT)]

- **ProFormer:** Yabin Zhu, Chenglong Li, Xiao Wang, Jin Tang, Zhixiang Huang.<br />
  "RGBT Tracking via Progressive Fusion Transformer with Dynamically Guided Learning." TCSVT (2024).
  [[paper](https://ieeexplore.ieee.org/document/10506555/)] 

- **QueryTrack:** Fan, Huijie and Yu, Zhencheng and Wang, Qiang and Fan, Baojie and Tang, Yandong.<br />
  "QueryTrack: Joint-Modality Query Fusion Network for RGBT Tracking." TIP (2024).
  [[paper](https://ieeexplore.ieee.org/document/10516307)] 

- **CAT++:** Liu, Lei and Li, Chenglong and Xiao, Yun and Ruan, Rui and Fan, Minghao.<br />
  "RGBT Tracking via Challenge-Based Appearance Disentanglement and Interaction." TIP (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10460420)] 

- **TATrack:** Hongyu Wang, Xiaotao Liu, Yifan Li, Meng Sun, Dian Yuan, Jing Liu.<br />
  "Temporal Adaptive RGBT Tracking with Modality Prompt." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2401.01244)] 

- **MArMOT:** Chenglong Li, Tianhao Zhu, Lei Liu, Xiaonan Si, Zilin Fan, Sulan Zhai.<br />
  "Cross-Modal Object Tracking: Modality-Aware Representations and A Unified Benchmark." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2111.04264)] 

- **AMNet:** Zhang, Tianlu and He, Xiaoyi and Jiao, Qiang and Zhang, Qiang and Han, Jungong.<br />
  "AMNet: Learning to Align Multi-modality for RGB-T Tracking." TCSVT (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10472533)] 

- **MCTrack:** Hu, Xiantao and Zhong, Bineng and Liang, Qihua and Zhang, Shengping and Li, Ning and Li, Xianxian.<br />
  "Towards Modalities Correlation for RGB-T Tracking." TCSVT (2024).
  [[paper](https://ieeexplore.ieee.org/abstract/document/10517645)] 

- **AFter:** Andong Lu, Wanyu Wang, Chenglong Li, Jin Tang, Bin Luo.<br />
  "AFter: Attention-based Fusion Router for RGBT Tracking." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.02717)] 
  [[code](https://github.com/Alexadlu/AFter)]

- **CSTNet:** Yunfeng Li, Bo Wang, Ye Li, Zhiwen Yu, Liang Wang.<br />
  "Transformer-based RGB-T Tracking with Channel and Spatial Feature Fusion." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2405.03177)] 
  [[code](https://github.com/LiYunfengLYF/CSTNet)]

#### 2023
- **TBSI:** Hui, Tianrui and Xun, Zizheng and Peng, Fengguang and Huang, Junshi and Wei, Xiaoming and Wei, Xiaolin and Dai, Jiao and Han, Jizhong and Liu, Si.<br />
  "Bridging Search Region Interaction with Template for RGB-T Tracking." CVPR (2023).
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Hui_Bridging_Search_Region_Interaction_With_Template_for_RGB-T_Tracking_CVPR_2023_paper.pdf)] 
  [[code](https://github.com/RyanHTR/TBSI)]

- **DFNet:** Jingchao Peng , Haitao Zhao , and Zhengwei Hu.<br />
  "Dynamic Fusion Network for RGBT Tracking." TITS (2023).
  [[paper](https://arxiv.org/abs/2109.07662)] 
  [[code](https://github.com/PengJingchao/DFNet)]

- **CMD:** Zhang, Tianlu and Guo, Hongyuan and Jiao, Qiang and Zhang, Qiang and Han, Jungong.<br />
  "Efficient RGB-T Tracking via Cross-Modality Distillation." CVPR (2023).
  [[paper](https://ieeexplore.ieee.org/document/10205202)] 

- **DFAT:** Zhangyong Tang, Tianyang Xu, Hui Li, Xiao-Jun Wu, XueFeng Zhu, Josef Kittler.<br />
  "Exploring fusion strategies for accurate RGBT visual object tracking." Information Fusion (2023).
  [[paper](https://arxiv.org/abs/2201.08673)] 
  [[code](https://github.com/Zhangyong-Tang/DFAT)]

- **QAT:** Lei Liu, Chenglong Li, Yun Xiao, Jin Tang.<br />
  "Quality-Aware RGBT Tracking via Supervised Reliability Learning and Weighted Residual Guidance." ACM MM  (2023).
  [[paper](https://dl.acm.org/doi/10.1145/3581783.3612341)] 

- **GuideFuse:** Zhang, Zeyang and Li, Hui and Xu, Tianyang and Wu, Xiao-Jun and Fu, Yu.<br />
  "GuideFuse: A Novel Guided Auto-Encoder Fusion Network for Infrared and Visible Images." TIM (2023).
  [[paper](https://ieeexplore.ieee.org/document/10330731)] 

- **MPLT:** Yang Luo, Xiqing Guo, Hui Feng, Lei Ao.<br />
  "RGB-T Tracking via Multi-Modal Mutual Prompt Learning." ArXiv (2023).
  [[paper](https://arxiv.org/abs/2308.16386)] 
  [[code](https://github.com/HusterYoung/MPLT)]

#### 2022
- **HMFT:** Pengyu Zhang, Jie Zhao, Dong Wang, Huchuan Lu, Xiang Ruan.<br />
  "Visible-Thermal UAV Tracking: A Large-Scale Benchmark and New Baseline." CVPR (2022).
  [[paper](https://arxiv.org/abs/2204.04120)] 
  [[code](https://github.com/zhang-pengyu/HMFT)]

- **MFGNet:** Xiao Wang, Xiujun Shu, Shiliang Zhang, Bo Jiang, Yaowei Wang, Yonghong Tian, Feng Wu.<br />
  "MFGNet: Dynamic Modality-Aware Filter Generation for RGB-T Tracking." TMM  (2022).
  [[paper](https://arxiv.org/abs/2107.10433)] 
  [[code](https://github.com/wangxiao5791509/MFG_RGBT_Tracking_PyTorch)]

- **MBAFNet:** Li, Yadong and Lai, Huicheng and Wang, Liejun and Jia, Zhenhong.<br />
  "Multibranch Adaptive Fusion Network for RGBT Tracking." IEEE Sensors Journal (2022).
  [[paper](https://ieeexplore.ieee.org/document/9721310)] 

- **AGMINet:** Mei, Jiatian and Liu, Yanyu and Wang, Changcheng and Zhou, Dongming and Nie, Rencan and Cao, Jinde.<br />
  "Asymmetric Global–Local Mutual Integration Network for RGBT Tracking." TIM (2022).
  [[paper](https://ieeexplore.ieee.org/abstract/document/9840392/)] 

- **APFNet:** Yun Xiao, Mengmeng Yang, Chenglong Li, Lei Liu, Jin Tang.<br />
  "Attribute-Based Progressive Fusion Network for RGBT Tracking." AAAI (2022).
  [[paper](https://cdn.aaai.org/ojs/20187/20187-13-24200-1-2-20220628.pdf)] 
  [[code](https://github.com/yangmengmeng1997/APFNet)]

- **DMCNet:** Lu, Andong and Qian, Cun and Li, Chenglong and Tang, Jin and Wang, Liang.<br />
  "Duality-Gated Mutual Condition Network for RGBT Tracking." TNNLS (2022).
  [[paper](https://ieeexplore.ieee.org/document/9737634)] 

- **TFNet:** Zhu, Yabin and Li, Chenglong and Tang, Jin and Luo, Bin and Wang, Liang.<br />
  "RGBT Tracking by Trident Fusion Network." TCSVT (2022).
  [[paper](https://ieeexplore.ieee.org/document/9383014)] 

- Mingzheng Feng, Jianbo Su
.<br />
  "Learning reliable modal weight with transformer for robust RGBT tracking." KBS (2022).
  [[paper](https://www.sciencedirect.com/science/article/pii/S0950705122004579)] 


#### 2021
- **JMMAC:** Zhang, Pengyu and Zhao, Jie and Bo, Chunjuan and Wang, Dong and Lu, Huchuan and Yang, Xiaoyun.<br />
  "Jointly Modeling Motion and Appearance Cues for Robust RGB-T Tracking." TIP (2021).
  [[paper](https://ieeexplore.ieee.org/document/9364880/)] 
  [[code](https://github.com/zhang-pengyu/JMMAC)]

- **ADRNet:** Pengyu Zhang, Dong Wang, Huchuan Lu, Xiaoyun Yang.<br />
  "Learning Adaptive Attribute-Driven Representation for Real-Time RGB-T Tracking." IJCV (2021).
  [[paper](https://github.com/zhang-pengyu/ADRNet/blob/main/Zhang_IJCV2021_ADRNet.pdf)] 
  [[code](https://github.com/zhang-pengyu/ADRNet)]

- **SiamCDA:** Zhang, Tianlu and Liu, Xueru and Zhang, Qiang and Han, Jungong.<br />
  "SiamCDA: Complementarity-and distractor-aware RGB-T tracking based on Siamese network." TCSVT (2021).
  [[paper](https://ieeexplore.ieee.org/abstract/document/9399460/)] 
  [[code](https://github.com/Tianlu-Zhang/LSS-Dataset)]

- Wang, Yong and Wei, Xian and Tang, Xuan and Shen, Hao and Zhang, Huanlong.<br />
  "Adaptive Fusion CNN Features for RGBT Object Tracking." TITS (2021).
  [[paper](https://ieeexplore.ieee.org/document/9426573)] 

- **M5L:** Zhengzheng Tu, Chun Lin, Chenglong Li, Jin Tang, Bin Luo.<br />
  "M5L: Multi-Modal Multi-Margin Metric Learning for RGBT Tracking." TIP (2021).
  [[paper](https://arxiv.org/abs/2003.07650)] 

- **CBPNet:** Qin Xu, Yiming Mei, Jinpei Liu, and Chenglong Li.<br />
  "Multimodal Cross-Layer Bilinear Pooling for RGBT Tracking." TMM (2021).
  [[paper](https://ieeexplore.ieee.org/document/9340007/)] 

- **MANet++:** Andong Lu, Chenglong Li, Yuqing Yan, Jin Tang, Bin Luo.<br />
  "RGBT Tracking via Multi-Adapter Network with Hierarchical Divergence Loss." TIP (2021).
  [[paper](https://arxiv.org/abs/2011.07189)] 

- **CMR:** Li, Chenglong and Xiang, Zhiqiang and Tang, Jin and Luo, Bin and Wang, Futian.<br />
  "RGBT Tracking via Noise-Robust Cross-Modal Ranking." TNNLS (2021).
  [[paper](https://ieeexplore.ieee.org/document/9406193/)] 

- **GCMP:** Rui Yang, Xiao Wang, Chenglong Li, Jinmin Hu, Jin Tang.<br />
  "RGBT tracking via cross-modality message passing." Neurocomputing (2021).
  [[paper](https://dl.acm.org/doi/10.1016/j.neucom.2021.08.012)] 

- **HDINet:** Mei, Jiatian and Zhou, Dongming and Cao, Jinde and Nie, Rencan and Guo, Yanbu.<br />
  "HDINet: Hierarchical Dual-Sensor Interaction Network for RGBT Tracking." IEEE Sensors Journal (2021).
  [[paper](https://ieeexplore.ieee.org/abstract/document/9426927)] 

#### 2020
- **CMPP:** Chaoqun Wang, Chunyan Xu, Zhen Cui, Ling Zhou, Tong Zhang, Xiaoya Zhang, Jian Yang.<br />
  "Cross-Modal Pattern-Propagation for RGB-T Tracking."CVPR (2020).
  [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Cross-Modal_Pattern-Propagation_for_RGB-T_Tracking_CVPR_2020_paper.pdf)] 

- **CAT:** Chenglong Li, Lei Liu, Andong Lu, Qing Ji, Jin Tang.<br />
  "Challenge-Aware RGBT Tracking." ECCV (2020).
  [[paper](https://ar5iv.labs.arxiv.org/abs/2007.13143)] 

- **FANet:** Yabin Zhu, Chenglong Li, Bin Luo, Jin Tang .<br />
 "FANet: Quality-Aware Feature Aggregation Network for Robust RGB-T Tracking." TIV (2020).
  [[paper](https://arxiv.org/abs/1811.09855)] 


#### 2019
- **mfDiMP:** Lichao Zhang, Martin Danelljan, Abel Gonzalez-Garcia, Joost van de Weijer, Fahad Shahbaz Khan.<br />
  "Multi-Modal Fusion for End-to-End RGB-T Tracking." ICCVW (2019).
  [[paper](https://arxiv.org/abs/1908.11714)] 
  [[code](https://github.com/zhanglichao/end2end_rgbt_tracking)]

- **DAPNet:** Yabin Zhu, Chenglong Li, Bin Luo, Jin Tang, Xiao Wang.<br />
  "Dense Feature Aggregation and Pruning for RGBT Tracking." ACM MM (2019).
  [[paper](https://arxiv.org/abs/1907.10451)] 

- **DAFNet:** Yuan Gao, Chenglong Li, Yabin Zhu, Jin Tang, Tao He, Futian Wang.<br />
  "Deep Adaptive Fusion Network for High Performance RGBT Tracking." ICCVW (2019).
  [[paper](https://openaccess.thecvf.com/content_ICCVW_2019/html/VISDrone/Gao_Deep_Adaptive_Fusion_Network_for_High_Performance_RGBT_Tracking_ICCVW_2019_paper.html)] 
  [[code](https://github.com/mjt1312/DAFNet)]

- **MANet:** Chenglong Li, Andong Lu, Aihua Zheng, Zhengzheng Tu, Jin Tang.<br />
  "Multi-Adapter RGBT Tracking." ICCV (2019).
  [[paper](https://arxiv.org/abs/1907.07485)] 
  [[code](https://github.com/Alexadlu/MANet)]



## Miscellaneous
### Datasets
| Dataset | Pub. & Date  | WebSite | Introduction |
|:-----:|:-----:|:-----:|:-----:|
|  [WebUAV-3M](https://arxiv.org/abs/2201.07425)   |   TPAMI-2023   |  [WebUAV-3M](https://github.com/983632847/WebUAV-3M)  |  4500 videos, 3.3 million frames, UAV tracking, Vision-language-audio |  
|  [UniMod1K](https://link.springer.com/article/10.1007/s11263-024-01999-8)   |   IJCV-2024  |  [UniMod1K](https://github.com/xuefeng-zhu5/UniMod1K)  |  1050 video  pairs, 2.5 million frames, Vision-depth-language  |  


### Papers
#### 2024
- **OneTracker:** Lingyi Hong, Shilin Yan, Renrui Zhang, Wanyun Li, Xinyu Zhou, Pinxue Guo, Kaixun Jiang, Yiting Chen, Jinglun Li, Zhaoyu Chen, Wenqiang Zhang.<br />
  "OneTracker: Unifying Visual Object Tracking with Foundation Models and Efficient Tuning." CVPR (2024).
  [[paper](https://arxiv.org/abs/2403.09634)] 

- **SDSTrack:** Xiaojun Hou, Jiazheng Xing, Yijie Qian, Yaowei Guo, Shuo Xin, Junhao Chen, Kai Tang, Mengmeng Wang, Zhengkai Jiang, Liang Liu, Yong Liu.<br />
  "SDSTrack: Self-Distillation Symmetric Adapter Learning for Multi-Modal Visual Object Tracking." CVPR (2024).
  [[paper](https://arxiv.org/abs/2403.16002)] 
  [[code](https://github.com/hoqolo/SDSTrack)]

- **Un-Track:** Zongwei Wu, Jilai Zheng, Xiangxuan Ren, Florin-Alexandru Vasluianu, Chao Ma, Danda Pani Paudel, Luc Van Gool, Radu Timofte.<br />
  "Single-Model and Any-Modality for Video Object Tracking." CVPR (2024).
  [[paper](https://arxiv.org/abs/2311.15851)] 
  [[code](https://github.com/Zongwei97/UnTrack)]

- **ELTrack:** Alansari, Mohamad and Alnuaimi, Khaled and Alansari, Sara and Werghi, Naoufel and Javed, Sajid.<br />
  "ELTrack: Correlating Events and Language for Visual Tracking." ArXiv (2024).
  [[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4764503)] 
  [[code](https://github.com/HamadYA/ELTrack-Correlating-Events-and-Language-for-Visual-Tracking)]

- **KSTrack:** He, Yuhang and Ma, Zhiheng and Wei, Xing and Gong, Yihong.<br />
  "Knowledge Synergy Learning for Multi-Modal
Tracking." TCSVT (2024).
  [[paper](https://ieeexplore.ieee.org/document/10388341)] 
 
- **SeqTrackv2:** Xin Chen, Ben Kang, Jiawen Zhu, Dong Wang, Houwen Peng, Huchuan Lu.<br />
  "Unified Sequence-to-Sequence Learning for Single- and Multi-Modal Visual Object Tracking." ArXiv (2024).
  [[paper](https://arxiv.org/abs/2304.14394)] 
  [[code](https://github.com/chenxin-dlut/SeqTrackv2)]

#### 2023
- **ViPT:** Jiawen Zhu, Simiao Lai, Xin Chen, Dong Wang, Huchuan Lu.<br />
  "Visual Prompt Multi-Modal Tracking." CVPR (2023).
  [[paper](https://arxiv.org/abs/2303.10826)] 
  [[code](https://github.com/jiawen-zhu/ViPT)]


#### 2022

- **ProTrack:** Jinyu Yang, Zhe Li, Feng Zheng, Aleš Leonardis, Jingkuan Song.<br />
  "Prompting for Multi-Modal Tracking." ACM MM (2022).
  [[paper](https://arxiv.org/abs/2207.14571)] 



## Awesome Repositories for MMOT
- [Vision-Language_Tracking_Paper_List](https://github.com/PeterBishop0/Vision-Language_Tracking_Paper_List)
- [VisEvent_SOT_Benchmark](https://github.com/wangxiao5791509/VisEvent_SOT_Benchmark)
- [RGBD-tracking-review](https://github.com/memoryunreal/RGBD-tracking-review)
- [Datasets-and-benchmark-code](https://github.com/mmic-lcl/Datasets-and-benchmark-code)
- [RGBT-Tracking-Results-Datasets-and-Methods](https://github.com/Zhangyong-Tang/RGBT-Tracking-Results-Datasets-and-Methods)
- [Multimodal-Tracking-Survey](https://github.com/zhang-pengyu/Multimodal-Tracking-Survey)



## License 
This project is released under the MIT license. Please see the [LICENSE](LICENSE) file for more information.
