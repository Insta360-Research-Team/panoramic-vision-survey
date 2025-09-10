[![Project page](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://insta360-research-team.github.io/Survey-of-Panorama)
[![arXiv](https://img.shields.io/badge/Paper-arXiv-blue.svg?style=flat)](https://arxiv.org/abs/2509.04444) 

<br />
<p align="center">
  <h1 align="center">One Flight Over the Gap: A Survey from Perspective to Panoramic Vision</h1>
</p>
<br />

[*Xin Lin*](https://linxin0.github.io/),
[*Xian Ge*](),
[*Dizhe Zhang*](),
[*Zhaoliang Wan*](https://wan-zhaoliang.vercel.app/),
[*Xianshun Wang*](),
[*Xiangtai Li*](https://lxtgh.github.io/),
[*Wenjie Jiang*](), 


[*Bo Du*]()
[*Dacheng Tao*]()
[*Ming-Hsuan Yang*](https://faculty.ucmerced.edu/mhyang/)
[*Lu Qi*](http://luqi.info/)

![main_fig](./teaser.png)

## 💖 Citation
**If you find value in our survey paper or curated collection, please consider citing our work and starring our repo to support us.**

```text
@article{lin2025panorama,
  title={One Flight Over the Gap: A Survey from Perspective to Panoramic Vision},
  author={Lin, Xin and Ge, Xian and Zhang, Dizhe and Wan, Zhaoliang and Wang, Xianshun and Li, Xiangtai and Jiang, Wenjie and Du, Bo and Tao, Dacheng and Yang, Ming-Hsuan and Qi, Lu},
  journal={arXiv},
  year={2025}
}
```

## 🌈 Contents

- [Visual Quality Enhancement](#Visual-Quality-Enhancement)
  - [Super Resolution](#Super-Resolution)
  - [Reflection Removal](#Reflection-Removal)
  - [Restoration](#Restoration)
  - [Quality Assessment](#Quality-Assessment)
- [Visual Understanding](#Visual-Understanding)
  - [Segmentation](#Segmentation)
  - [Mapping](#Mapping)
  - [Detection](#Detection)
  - [Tracking](#Tracking)
  - [Pose Estimation](#Pose-Estimation)
  - [Saliency Prediction](#Saliency-Prediction)
  - [Layout Estimation](#Layout-Estimation)
  - [Optical Flow Estimation](#Optical-Flow-Estimation)
  - [Keypoint Matching](#Keypoint-Matching)
  - [Decomposition](#Decomposition)
  - [Lighting Estimation](#Lighting-Estimation)
  - [Depth Estimation](#Depth-Estimation)
- [Multimodel](#Multimodel)
  - [Audio](#Audio)
  - [Ladar](#Ladar)
  - [Text](#Text)
- [Visual Generation](#Visual-Generation)
  - [Text-guided Generation](#Text-guided-Generation)
  - [Completion](#Completion)
  - [Novel View Synthesis](#Novel-View-Synthesis)
  

  
<!-- start -->
## 🚀 Visual Quality Enhancement

### 🍇 Super Resolution

### 🍉 Image:

- [LAUNet (CVPR 2021)](https://openaccess.thecvf.com/content/CVPR2021/papers/Deng_LAU-Net_Latitude_Adaptive_Upscaling_Network_for_Omnidirectional_Image_Super-Resolution_CVPR_2021_paper.pdf)
- [360-SISR (ICIP 2021)](https://ieeexplore.ieee.org/abstract/document/9506233/)
- [OSRGAN (International Workshop on Multimedia Signal Processing 2019)](https://arxiv.org/pdf/1908.04297)
- [OSRT (CVPR 2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Yu_OSRT_Omnidirectional_Image_Super-Resolution_With_Distortion-Aware_Transformer_CVPR_2023_paper.pdf)
- [An et al. (ICIP 2023)](https://ieeexplore.ieee.org/abstract/document/10222760/)
- [OPDN (CVPRW 2023)](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Sun_OPDN_Omnidirectional_Position-Aware_Deformable_Network_for_Omnidirectional_Image_Super-Resolution_CVPRW_2023_paper.pdf)
- [FATO (ACMMM Asia 2024)](https://dl.acm.org/doi/pdf/10.1145/3696409.3700232)
- [GDGT-OSR (TCSVT 2025)](https://arxiv.org/pdf/2406.10869)
- [Cao et al. (Signal, Image and Video Processing, 2025)](https://link.springer.com/article/10.1007/s11760-025-03963-6)
- [FAOR (AAAI 2025)](https://ojs.aaai.org/index.php/AAAI/article/view/32733)
- [MambaOSR (Entropy 2025)](https://www.mdpi.com/1099-4300/27/4/446)
- [SRCNN_FT (VISAPP 2018)](https://pdfs.semanticscholar.org/5030/36c4a96fa9a1d5c5be3fd27d41d1c9edbf65.pdf)
- [OESRGAN (CVPRW 2020)](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w38/Zhang_Toward_Real-World_Panoramic_Image_Enhancement_CVPRW_2020_paper.pdf)
- [SphereSR (CVPR 2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Yoon_SphereSR_360deg_Image_Super-Resolution_With_Arbitrary_Projection_via_Continuous_Spherical_CVPR_2022_paper.pdf)
- [OmniZoomer (ICCV 2023)](https://openaccess.thecvf.com/content/ICCV2023/papers/Cao_OmniZoomer_Learning_to_Move_and_Zoom_in_on_Sphere_at_ICCV_2023_paper.pdf)
- [BPOSR (AAAI 2024)](https://ojs.aaai.org/index.php/AAAI/article/view/28354)
- [Cai et al. (AAAI 2024)](https://ojs.aaai.org/index.php/AAAI/article/view/27846)
- [OmniSSR (ECCV 2024)](https://arxiv.org/pdf/2404.10312)
- [DiffOSR (KBS 2025)](https://www.sciencedirect.com/science/article/abs/pii/S0950705125002916)
- [RealOSR (arXiv 2024)](https://arxiv.org/pdf/2412.09646)


### 🍉 Video:
- [SMFN (EAAI 2024)](https://arxiv.org/pdf/2008.10320)
- [S3PO (TMM 2023)](https://arxiv.org/pdf/2506.14803)
- [STDAN (arXiv 2024)](https://arxiv.org/pdf/2410.11506?)
- [Wang et al. (BDIOT 2023)](https://dl.acm.org/doi/abs/10.1145/3617695.3617721)


### 🍇 Reflection Removal:


- [Hong et al. (CVPR 2021)](https://openaccess.thecvf.com/content/CVPR2021/papers/Hong_Panoramic_Image_Reflection_Removal_CVPR_2021_paper.pdf)
- [PAR2Net (TPAMI 2023)](https://ieeexplore.ieee.org/abstract/document/10153662/)
- [ZS360 (ECCV 2022)](https://link.springer.com/chapter/10.1007/978-3-031-19800-7_31)
- [Park et al. (WACV 2024)](https://openaccess.thecvf.com/content/WACV2024/papers/Park_Fully-Automatic_Reflection_Removal_for_360-Degree_Images_WACV_2024_paper.pdf)

### 🍇 Restoration

### 🍉 Denoising:

- [Bigot et al. (VISAPP 2007)](https://www.scitepress.org/Papers/2007/20523/20523.pdf)
- [Iazzi et al. (Research Journal of Applied Sciences, Engineering and Technology 2014)](https://www.airitilibrary.com/Article/Detail/20407467-201411-201503110021-201503110021-1966-1972)
- [Phan et al. (Signal Processing Letters 2020)](https://www.researchgate.net/profile/Khoa-Phan/publication/339895846_A_Space-Variant_Nonlinear_Algorithm_for_Denoising_Omnidirectional_Images_Corrupted_by_Poisson_Noise/links/5ff5bf1592851c13fef06681/A-Space-Variant-Nonlinear-Algorithm-for-Denoising-Omnidirectional-Images-Corrupted-by-Poisson-Noise.pdf)
- [Spheredrunet (ISMAR-Adjunct 2023)](https://hal.science/hal-04197479/document)

### 🍉 Deblurring:
- [Li et al. (International Journal of Optics 2014)](https://onlinelibrary.wiley.com/doi/pdf/10.1155/2014/732937)
- [Peng et al. (SMC 2012)](https://ieeexplore.ieee.org/abstract/document/6378313/)
- [Liu et al. (Optik, 2014)](https://www.sciencedirect.com/science/article/abs/pii/S0030402613008231)
- [Alibouch et al. (International Symposium on Ubiquitous Networking 2021)](https://link.springer.com/chapter/10.1007/978-3-030-86356-2_25)

### 🍉 Dehazing:
- [Zhao et al. (TVCG 2023)](https://ieeexplore.ieee.org/abstract/document/10005621/)

### 🍇 Quality Assessment

### 🍉 Image:
- [MC360IQA (IEEE Journal of Selected Topics in Signal Processing 2019)](https://drive.google.com/file/d/1EeJ8lzKMrFb5OKRa2xAh99NFNYzieoOn/view)
- [VGCN (TCSVT 2020)](https://arxiv.org/pdf/2002.09140)
- [TVFormer (ACMMM 2022)](https://dl.acm.org/doi/abs/10.1145/3503161.3547748)
- [JointNet (ACMMM 2022)](https://dl.acm.org/doi/abs/10.1145/3503161.3548175)
- [DeepVR-IQA (TCSVT 2019)](https://ieeexplore.ieee.org/abstract/document/8638985/)
- [Assessor360 (NeurIPS 2023)](https://proceedings.neurips.cc/paper_files/paper/2023/file/ccf4a7323b9ee3e54bf77f0e876b3f8b-Paper-Conference.pdf)
- [ST360IQ (ICASSP 2023)](https://arxiv.org/pdf/2303.06907)
- [VSBNet (TCSVT 2022)](https://ieeexplore.ieee.org/abstract/document/9964240/)
- [SCPOIQA (TIM 2024)](https://ieeexplore.ieee.org/abstract/document/10731918/)
- [WS-PSNR (IEEE Signal Processing Letters 2017)](https://ieeexplore.ieee.org/abstract/document/7961186/)
- [WS-SSIM (ICSP 2018)](https://ieeexplore.ieee.org/abstract/document/8652269/)
- [S-PSNR (ICUFN 2017)](https://www.researchgate.net/profile/Tran-Huyen-10/publication/318751919_An_evaluation_of_quality_metrics_for_360_videos/links/5d29d144458515c11c2b7494/An-evaluation-of-quality-metrics-for-360-videos.pdf)
- [CPBQA (TIP 2021)](https://ieeexplore.ieee.org/abstract/document/9334423/)
- [BOIQA (TCSVT 2021)](https://ieeexplore.ieee.org/abstract/document/9614114/)
- [MFILGN (TCSVT 2024)](https://arxiv.org/pdf/2102.11393)
- [Yang et al. (arXiv 2025)](https://arxiv.org/pdf/2506.21925)
- [GAT (arXiv 2025)](https://arxiv.org/pdf/2508.09843?)

### 🍉 Video:
- [OV-PSNR (TMM, 2020)](https://ieeexplore.ieee.org/abstract/document/9296376/)
- [V-CNN (CVPR, 2019)](https://ieeexplore.ieee.org/abstract/document/8953510/)
- [360-VQA (ICME, 2020)](https://infoscience.epfl.ch/server/api/core/bitstreams/5f92fd75-54b3-4d3d-b9ce-fb8ffabc2b0e/content)
- [CIQNet (IEEE Transactions on Broadcasting, 2024)](https://ieeexplore.ieee.org/abstract/document/10380455/)
- [NR-OVQA (Optik, 2021)](https://www.sciencedirect.com/science/article/abs/pii/S0030402620317046)

## 🚀 Visual Understanding

### 🍇 Segmentation:

- [DensePASS (ITSC 2021)](https://arxiv.org/pdf/2108.06383)
- [DPPASS (CVPR 2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Zheng_Both_Style_and_Distortion_Matter_Dual-Path_Unsupervised_Domain_Adaptation_for_CVPR_2023_paper.pdf)
- [Trans4PASS (CVPR 2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Bending_Reality_Distortion-Aware_Transformers_for_Adapting_to_Panoramic_Semantic_Segmentation_CVPR_2022_paper.pdf)
- [Trans4PASS+ (TPAMI 2024)](https://arxiv.org/pdf/2207.11860)
- [360SFUDA (CVPR 2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Zheng_Semantics_Distortion_and_Style_Matter_Towards_Source-free_UDA_for_Panoramic_CVPR_2024_paper.pdf)
- [360SFUDA++ (TPAMI 2024)](https://arxiv.org/pdf/2404.16501)
- [Yang et al. - Omnisupervised Semantic Segmentation (TITS 2020)](https://www.researchgate.net/profile/Kailun-Yang/publication/345419595_Omnisupervised_Omnidirectional_Semantic_Segmentation/links/609daf06458515c2658cb643/Omnisupervised-Omnidirectional-Semantic-Segmentation.pdf)
- [GoodSAM (CVPR 2024)](https://arxiv.org/pdf/2403.16370)
- [GoodSAM++ (arXiv 2024)](https://arxiv.org/pdf/2408.09115)
- [OmniSAM (arXiv 2025)](https://arxiv.org/pdf/2503.07098)
- [PASS (TITS 2019)](https://core.ac.uk/download/pdf/524787714.pdf)
- [DS-PASS (IV 2020)](https://arxiv.org/pdf/1909.07721)
- [DDCNet (TIM 2022)](https://ieeexplore.ieee.org/abstract/document/9667494/)
- [Zheng et al. (WACV 2023)](https://openaccess.thecvf.com/content/WACV2023/papers/Zheng_Complementary_Bi-Directional_Feature_Compression_for_Indoor_360deg_Semantic_Segmentation_With_WACV_2023_paper.pdf)
- [DeepPanoContext (ICCV 2021)](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_DeepPanoContext_Panoramic_3D_Scene_Understanding_With_Holistic_Scene_Context_Graph_ICCV_2021_paper.pdf)
- [HexRUNet (ICCV 2019)](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Orientation-Aware_Semantic_Segmentation_on_Icosahedron_Spheres_ICCV_2019_paper.pdf)
- [PRF (TITS 2023)](https://arxiv.org/pdf/2206.10711)
- [SGAT4PASS (IJCAI 2023)](https://arxiv.org/pdf/2306.03403)
- [PanoVOS (ECCV 2024)](https://arxiv.org/pdf/2309.12303)
- [Pano-SfMLearner (IEEE SPL 2021)](https://ieeexplore.ieee.org/abstract/document/9406330/)
- [OASS (ECCV 2024)](https://arxiv.org/pdf/2407.02182)
- [OOOPS (ECCV 2024)](https://arxiv.org/pdf/2407.02685)
- [Liu et al. (arXiv 2025)](https://arxiv.org/pdf/2507.09216)

### 🍇 Mapping:
- [360Mapper (WACV 2024)](https://openaccess.thecvf.com/content/WACV2024/papers/Teng_360BEV_Panoramic_Semantic_Mapping_for_Indoor_Birds-Eye_View_WACV_2024_paper.pdf)  
- [OneBEV (ACCV 2024)](https://openaccess.thecvf.com/content/ACCV2024/papers/Wei_OneBEV_Using_One_Panoramic_Image_for_BirdAos-Eye-View_Semantic_Mapping_ACCV_2024_paper.pdf)  
- [HumanoidPano (arXiv 2025)](https://arxiv.org/pdf/2503.09010)  

### 🍇 Detection:
- [Multi-Projection YOLO (ICPR 2018)](https://arxiv.org/pdf/1805.08009)  
- [RepR-CNN (AAAI 2020)](https://ojs.aaai.org/index.php/AAAI/article/view/6995)  
- [SphereNet (ECCV 2018)](https://openaccess.thecvf.com/content_ECCV_2018/papers/Benjamin_Coors_SphereNet_Learning_Spherical_ECCV_2018_paper.pdf)  
- [SPHCONV (NeurIPS 2017)](https://proceedings.neurips.cc/paper/2017/file/0c74b7f78409a4022a2c4c5a5ca3ee19-Paper.pdf)  
- [Curved-Space Faster R-CNN (ICASSP 2019)](https://www.cs.nthu.edu.tw/~lai/pdf/publications/2019/Object_Detection_in_Curved_Space_for_360-Degree_Camera.pdf)  
- [MS-RPN (IET Computer Vision 2019)](https://ietresearch.onlinelibrary.wiley.com/doi/pdf/10.1049/iet-cvi.2018.5304)  
- [PDAT (arXiv 2025)](https://arxiv.org/pdf/2503.14228)  
- [PanoGlassNet (TIM 2024)](https://ieeexplore.ieee.org/abstract/document/10504145)  
- [UnbiasedIoU (AAAI 2022)](https://ojs.aaai.org/index.php/AAAI/article/view/19929)  
- [FoV-IoU (TIP 2023)](https://www.academia.edu/download/85054461/2202.03176v1.pdf)  
- [Sph2Pob (IJCAI 2023)](https://www.ijcai.org/proceedings/2023/0137.pdf)  

### 🍇 Tracking:

- [Jiang et al. (TIM 2021)](https://ieeexplore.ieee.org/abstract/document/9335293/)  
- [MMPAT (CVPRW 2021)](https://openaccess.thecvf.com/content/CVPR2021W/JRDB/papers/He_Know_Your_Surroundings_Panoramic_Multi-Object_Tracking_by_Multimodality_Collaboration_CVPRW_2021_paper.pdf)  
- [CC3DT (arXiv 2022)](https://arxiv.org/pdf/2212.01247)  
- [360VOT (ICCV 2023)](http://openaccess.thecvf.com/content/ICCV2023/papers/Huang_360VOT_A_New_Benchmark_Dataset_for_Omnidirectional_Visual_Object_Tracking_ICCV_2023_paper.pdf)  
- [360VOTS (arXiv 2024)](https://arxiv.org/pdf/2404.13953)  
- [Luo et al. (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Luo_Omnidirectional_Multi-Object_Tracking_CVPR_2025_paper.pdf)


### 🍇 Pose Estimation:

- [CoVisPose (ECCV 2022)](https://fq.pkwyx.com/default/https/www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136920610.pdf)  
- [Graph-CoVis (CVPRW 2023)](https://openaccess.thecvf.com/content/CVPR2023W/OmniCV/papers/Nejatishahidin_Graph-CoVis_GNN-Based_Multi-View_Panorama_Global_Pose_Estimation_CVPRW_2023_paper.pdf)  
- [PanoPose (CVPR 2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Tu_PanoPose_Self-supervised_Relative_Pose_Estimation_for_Panoramic_Images_CVPR_2024_paper.pdf)
- [PriOr-Flow (ICCV 2025)](https://arxiv.org/pdf/2506.23897)

### 🍇 Saliency Prediction:

### 🍉 Image:
- [SalNet (Signal Processing: Image Communication, 2018)](https://arxiv.org/pdf/1709.06505)  
- [Suzuki et al. (SMC, 2018)](https://arxiv.org/pdf/1807.06329)  
- [Dai et al. (ICASSP, 2020)](https://ieeexplore.ieee.org/abstract/document/9053888/)  
- [Djemai et al. (ISCAS, 2020)](https://arxiv.org/pdf/2002.09196)  
- [SalGAN360 (ICMEW, 2018)](http://openhevc.insa-rennes.fr/wp-content/uploads/2018/07/camera-ready_icme2018template.pdf)  
- [SalbiNet (VR, 2020)](https://ieeexplore.ieee.org/abstract/document/9089519)  
- [Dedhia et al. (ICASSP, 2019)](https://arxiv.org/pdf/1903.01380)  
- [SalGCN (ACMMM, 2020)](https://dl.acm.org/doi/abs/10.1145/3394171.3413733)  
- [SalReGCN360 (TCSVT, 2022)](https://ieeexplore.ieee.org/abstract/document/9852252/)  
- [SalGFCN (VCIP, 2021)](https://ieeexplore.ieee.org/abstract/document/9675373/)  
- [GBCNN (TCSVT, 2021)](https://drive.google.com/file/d/1KpfyuzRSJg87zk41jphNkmgU2lvzowIU/view)  
- [Zhu et al. (ICME, 2021)](https://drive.google.com/file/d/1m-Px48yeG_inPyi8_Bk_dYL8DWOyRh1f/view)  
- [RANSP (Neurocomputing, 2021)](https://drive.google.com/file/d/1yz1g2ca6yEsy2xuY2un5JQWh7bMXPudZ/view)  
- [Zhu et al. (ICPR, 2021)](https://ieeexplore.ieee.org/abstract/document/9412001/)  
- [Abreu et al. (QoMEX, 2017)](https://d1wqtxts1xzle7.cloudfront.net/109434453/Abreu2017Look-libre.pdf?1703281511=&response-content-disposition=inline%3B+filename%3DLook_around_you_Saliency_maps_for_omnidi.pdf&Expires=1754478656&Signature=IPoyqhMN1qy-Ln~u1QirBbVcEgwSdOegbGc-50MJ36j4QGHwFLDmhx-XAIJt-DlY06ES7BrEuR~cVtOgb1wswgrdLLEWxuwgvlQ-beMajgj8BbMH8RcrgMsCDmEwcTMyuiQbYd3vZHvKp5Vw8KgJ0CqGmFyeopjgqvEtog0zX~fB4pkRmmVeFS54YSFJWE~gkU0z6L7RpfgX3J8x~ynyyLbUg81YLKrmmrQJ6wjuuco54nsqmPITdQ0nXk5VJfi4FWWE9zBnMi5mBrj9nSVsIMRux9zVcciQGS1kqm0G2SQXQ1PhvxNLm0zDxlVuU4qkuuOKU61CS41t3~PqEL2HFA__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)  
- [Zhu et al. (Signal Processing: Image Communication, 2018)](https://drive.google.com/file/d/1eEJ3-eLAdLDhJu8VFeYBRlMb9p-J8ny3/view)  
- [Bur et al. (ICPR, 2006)](https://d1wqtxts1xzle7.cloudfront.net/42320377/2006-ICPR-libre.pdf?1454870019=&response-content-disposition=inline%3B+filename%3DRobot_Navigation_by_Panoramic_Vision_and.pdf&Expires=1754478718&Signature=GH-ABTTkZ~0W6kAIx7llzfvjJuCu7y9hZiDJLpyu9JVbOidKqYb1EApf2bNQDth9YKM4o2DCiYR01JGonkFQzD5KPjG7UaCKeG2stCfNbvyO33-sY30pVQKTqw7c6YuEWRw5Nqm~hYs55Zectq0gJY7tRK1Udvi2VKrDpyTFI6oigw55qv0VgPGPUEH~ZwZueU8MFXvRucGlwwOvbtjpfzKe1Y0AaDp5uHnxTRKUM3PUEi2ep0CVwlfVjKNwitE6AHwyUNumRdckW0zpDN6NzQOCHPLAIVb55JkczeHAsUhk1kDFpfBais0JM8Y70xLUYPP4Hi6oR9LpM9lXUP64Iw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)  
- [Bogdanova et al. (TIP, 2008)](http://wwwa.unine.ch/parlab/pub/pdf/2008-TIP.pdf)
  


### 🍉 Video:

- [PanoSalNet (ACMMM, 2018)](https://mason.gmu.edu/~zyan4/papers/panosalnet_mm18.pdf)  
- [Cheng et al. (CVPR, 2018)](https://openaccess.thecvf.com/content_cvpr_2018/papers/Cheng_Cube_Padding_for_CVPR_2018_paper.pdf)  
- [MT-DNN (TMM, 2020)](https://ieeexplore.ieee.org/abstract/document/9072511/)  
- [DHP (TPAMI, 2018)](https://arxiv.org/pdf/1710.10755)  
- [ATSal (ICPR, 2021)](https://arxiv.org/pdf/2011.10600)  
- [Guo et al. (ACMMM, 2024)](https://openreview.net/pdf?id=0Q9zTGHOda)  
- [SphericalU-Net (ECCV, 2018)](https://openaccess.thecvf.com/content_ECCV_2018/papers/Ziheng_Zhang_Saliency_Detection_in_ECCV_2018_paper.pdf)  
- [360Spred (TCSVT, 2024)](https://ieeexplore.ieee.org/abstract/document/10542218)
- [Cokelek et al. (TPAMI 2025)](https://ieeexplore.ieee.org/abstract/document/11144923)
  

### 🍇 Layout Estimation:
- [DuLa-Net (CVPR 2019)](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yang_DuLa-Net_A_Dual-Projection_Network_for_Estimating_Room_Layouts_From_a_CVPR_2019_paper.pdf)
- [PSMNet (CVPR 2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_PSMNet_Position-Aware_Stereo_Merging_Network_for_Room_Layout_Estimation_CVPR_2022_paper.pdf)
- [uLayout (WACV 2025)](https://arxiv.org/pdf/2503.21562)
- [HorizonNet (CVPR 2019)](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_HorizonNet_Learning_Room_Layout_With_1D_Representation_and_Pano_Stretch_CVPR_2019_paper.pdf)
- [DOPNet (CVPR 2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Shen_Disentangling_Orthogonal_Planes_for_Indoor_Panoramic_Room_Layout_Estimation_With_CVPR_2023_paper.pdf)
- [MV-DOPNet (CVPR 2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Shen_Disentangling_Orthogonal_Planes_for_Indoor_Panoramic_Room_Layout_Estimation_With_CVPR_2023_paper.pdf)
- [C2P-Net (TPAMI 2025)](https://ieeexplore.ieee.org/abstract/document/10878466/)
- [LED2Net (CVPR 2021)](https://arxiv.org/pdf/2104.00568)
- [Seg2Reg (CVPR 2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Sun_Seg2Reg_Differentiable_2D_Segmentation_to_1D_Regression_Rendering_for_360_CVPR_2024_paper.pdf)
- [LGT-Net (CVPR 2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Jiang_LGT-Net_Indoor_Panoramic_Room_Layout_Estimation_With_Geometry-Aware_Transformer_Network_CVPR_2022_paper.pdf)
- [HoHoNet (CVPR 2021)](https://openaccess.thecvf.com/content/CVPR2021/papers/Sun_HoHoNet_360_Indoor_Holistic_Understanding_With_Latent_Horizontal_Features_CVPR_2021_paper.pdf)
- [Fernandez et al. (RAL 2018)](https://arxiv.org/pdf/1806.08294)
- [PanoContext (ECCV 2014)](https://oar.princeton.edu/bitstream/88435/pr1qg23/1/PanoContext.pdf)
- [GPRNet (CVPRW 2023)](https://openaccess.thecvf.com/content/CVPR2023W/OmniCV/papers/Su_GPR-Net_Multi-View_Layout_Estimation_via_a_Geometry-Aware_Panorama_Registration_Network_CVPRW_2023_paper.pdf)
- [Bi-Layout (CVPR 2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Tsai_No_More_Ambiguity_in_360deg_Room_Layout_via_Bi-Layout_Estimation_CVPR_2024_paper.pdf)
- [Jia et al. (CVPRW 2022)](https://openaccess.thecvf.com/content/CVPR2022W/OmniCV/papers/Jia_3D_Room_Layout_Recovery_Generalizing_Across_Manhattan_and_Non-Manhattan_Worlds_CVPRW_2022_paper.pdf)
- [SSLayout360 (CVPR 2021)](https://openaccess.thecvf.com/content/CVPR2021/papers/Tran_SSLayout360_Semi-Supervised_Indoor_Layout_Estimation_From_360deg_Panorama_CVPR_2021_paper.pdf)
- [SemiLayout360 (arXiv 2024)](https://arxiv.org/pdf/2503.01114)

### 🍇 Optical Flow Estimation:

- [Cubes3D (arXiv 2018)](https://arxiv.org/pdf/1804.09004)
- [SimpleNet (3DC 2019)](https://ieeexplore.ieee.org/abstract/document/8885962)
- [OmniFlowNet (ICPR 2021)](https://hal.science/hal-02968191/file/ICPR_2020_FINAL.pdf)
- [LiteFlowNet360 (ICPR 2021)](https://arxiv.org/pdf/2010.08045)
- [PanoFlow (TITS 2023)](https://www.researchgate.net/profile/Kailun-Yang/publication/368434489_PanoFlow_Learning_360circ_Optical_Flow_for_Surrounding_Temporal_Understanding/links/63eafd26bd78607643646dd1/PanoFlow-Learning-360circ-Optical-Flow-for-Surrounding-Temporal-Understanding.pdf)
- [Yuan et al. (BMVC 2021)](https://researchportal.bath.ac.uk/files/228201204/360Flow_YuanRichardt_BMVC2021.pdf)
- [Li et al. (ECCV 2022)](https://arxiv.org/pdf/2208.00776)

### 🍇 Keypoint Matching:

- [SPHORB (IJCV 2015)](https://cic.tju.edu.cn/faculty/lwan/paper/SPHORB/pdf/SPHORB-final-small.pdf)
- [Chuang et al. (PE&RS 2018)](https://www.ingentaconnect.com/contentone/asprs/pers/2018/00000084/00000001/art00012?crawler=true&mimetype=application/pdf)
- [PanoPoint (CVPRW 2023)](https://openaccess.thecvf.com/content/CVPR2023W/OmniCV/papers/Zhang_PanoPoint_Self-Supervised_Feature_Points_Detection_and_Description_for_360deg_Panorama_CVPRW_2023_paper.pdf)
- [SphereGlue (CVPRW 2023)](https://openaccess.thecvf.com/content/CVPR2023W/IMW/papers/Gava_SphereGlue_Learning_Keypoint_Matching_on_High_Resolution_Spherical_Images_CVPRW_2023_paper.pdf)
- [EDM (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Jung_EDM_Equirectangular_Projection-Oriented_Dense_Kernelized_Feature_Matching_CVPR_2025_paper.pdf)

### 🍇 Decomposition:

- [Li et al. (CVPR 2021)](https://arxiv.org/pdf/2104.09886)
- [PhyIR (CVPR 2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_PhyIR_Physics-Based_Inverse_Rendering_for_Panoramic_Indoor_Images_CVPR_2022_paper.pdf)
- [Xu et al. (TVCG 2024)](https://d197for5662m48.cloudfront.net/documents/publicationstatus/170307/preprint_pdf/a3fb7c56754575bae23aeb6c7b28cd44.pdf)
  

### 🍇 Lighting Estimation:

- [Weber et al. (3DV 2018)](https://arxiv.org/pdf/1806.03994)
- [Gkitsas et al. (CVPRW 2020)](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w38/Gkitsas_Deep_Lighting_Environment_Map_Estimation_From_Spherical_Panoramas_CVPRW_2020_paper.pdf)
- [Hold et al. (CVPR 2017)](https://openaccess.thecvf.com/content_cvpr_2017/papers/Hold-Geoffroy_Deep_Outdoor_Illumination_CVPR_2017_paper.pdf)
- [Hold et al. (CVPR 2019)](https://openaccess.thecvf.com/content_CVPR_2019/papers/Hold-Geoffroy_Deep_Sky_Modeling_for_Single_Image_Outdoor_Lighting_Estimation_CVPR_2019_paper.pdf)
- [Zhang et al. (CVPR 2019)](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_All-Weather_Deep_Outdoor_Lighting_Estimation_CVPR_2019_paper.pdf)
- [Song et al. (CVPR 2019)](https://openaccess.thecvf.com/content_CVPR_2019/papers/Song_Neural_Illumination_Lighting_Prediction_for_Indoor_Environments_CVPR_2019_paper.pdf)
- [Garon et al. (CVPR 2019)](https://openaccess.thecvf.com/content_CVPR_2019/papers/Garon_Fast_Spatially-Varying_Indoor_Lighting_Estimation_CVPR_2019_paper.pdf)
- [EnvMapNet (CVPR 2021)](https://openaccess.thecvf.com/content/CVPR2021/papers/Somanath_HDR_Environment_Map_Estimation_for_Real-Time_Augmented_Reality_CVPR_2021_paper.pdf)
- [StyleLight (ECCV 2022)](https://arxiv.org/pdf/2207.14811)
- [IllumiDiff (TVCG 2025)](https://ieeexplore.ieee.org/abstract/document/10945728/)
- [Emlight (AAAI 2021)](https://ojs.aaai.org/index.php/AAAI/article/view/16440)
- [Gmlight (TIP 2021)](https://arxiv.org/pdf/2102.10244)
- [Weber et al. (ECCV 2022)](https://arxiv.org/pdf/2211.03928)
- [EverLight (ICCV 2023)](https://openaccess.thecvf.com/content/ICCV2023/papers/Dastjerdi_EverLight_Indoor-Outdoor_Editable_HDR_Lighting_Estimation_ICCV_2023_paper.pdf)
- [SOLID-Net (CVPR 2021)](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_Spatially-Varying_Outdoor_Lighting_Estimation_From_Intrinsics_CVPR_2021_paper.pdf)
- [SALENet (TIP 2024)](https://ieeexplore.ieee.org/abstract/document/10794602/)
- [CleAR (arXiv 2024)](https://arxiv.org/pdf/2411.02179)
- [Hilliard et al. (arXiv 2025)](https://arxiv.org/pdf/2507.21261)

  
### 🍇 Depth Estimation:

- [OmniDepth (ECCV 2018)](https://openaccess.thecvf.com/content_ECCV_2018/papers/NIKOLAOS_ZIOULIS_OmniDepth_Dense_Depth_ECCV_2018_paper.pdf)
- [Tateno et al. (ECCV 2018)](https://openaccess.thecvf.com/content_ECCV_2018/papers/Keisuke_Tateno_Distortion-Aware_Convolutional_Filters_ECCV_2018_paper.pdf)
- [ACDNet (AAAI 2022)](https://ojs.aaai.org/index.php/AAAI/article/view/20278)
- [PanoFormer (ECCV 2022)](https://arxiv.org/pdf/2203.09283)
- [EGFormer (ICCV 2023)](https://openaccess.thecvf.com/content/ICCV2023/papers/Yun_EGformer_Equirectangular_Geometry-biased_Transformer_for_360_Depth_Estimation_ICCV_2023_paper.pdf)
- [OmniDiffusion (WACV 2025)](https://ieeexplore.ieee.org/abstract/document/10943472/)
- [HUSH (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Lee_HUSH_Holistic_Panoramic_3D_Scene_Understanding_using_Spherical_Harmonics_CVPR_2025_paper.pdf)
- [BiFuse (CVPR 2020)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_BiFuse_Monocular_360_Depth_Estimation_via_Bi-Projection_Fusion_CVPR_2020_paper.pdf)
- [UniFuse (RAL 2021)](https://arxiv.org/pdf/2102.03550)
- [Peng et al. (WACV 2023)](https://openaccess.thecvf.com/content/WACV2023/papers/Peng_High-Resolution_Depth_Estimation_for_360deg_Panoramas_Through_Perspective_and_Panoramic_WACV_2023_paper.pdf)
- [GLPanoDepth (TIP 2024)](https://arxiv.org/pdf/2202.02796)
- [HRDFuse (CVPR 2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Ai_HRDFuse_Monocular_360deg_Depth_Estimation_by_Collaboratively_Learning_Holistic-With-Regional_Depth_CVPR_2023_paper.pdf)
- [Elite360d (CVPR 2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Ai_Elite360D_Towards_Efficient_360_Depth_Estimation_via_Semantic-_and_Distance-Aware_CVPR_2024_paper.pdf)
- [Elite360m (arXiv 2024)](https://arxiv.org/pdf/2408.09336)
- [OmniFusion (CVPR 2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_OmniFusion_360_Monocular_Depth_Estimation_via_Geometry-Aware_Fusion_CVPR_2022_paper.pdf)
- [360MonoDepth (CVPR 2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Rey-Area_360MonoDepth_High-Resolution_360deg_Monocular_Depth_Estimation_CVPR_2022_paper.pdf)
- [SphereUFormer (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Benny_SphereUFormer_A_U-Shaped_Transformer_for_Spherical_360_Perception_CVPR_2025_paper.pdf)
- [S2Net (RAL 2023)](https://arxiv.org/pdf/2301.05845)
- [MS360 (GI 2024)](https://openreview.net/pdf?id=LPTbjVqgWo)
- [SGFormer (TCSVT 2025)](https://arxiv.org/pdf/2404.14979)
- [PGFuse (arXiv 2024)](https://arxiv.org/pdf/2408.16227)
- [OmniStereo (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Deng_OmniStereo_Real-time_Omnidireactional_Depth_Estimation_with_Multiview_Fisheye_Cameras_CVPR_2025_paper.pdf)
- [Slicenet (CVPR 2021)](https://openaccess.thecvf.com/content/CVPR2021/papers/Pintore_SliceNet_Deep_Dense_Depth_Estimation_From_a_Single_Indoor_Panorama_CVPR_2021_paper.pdf)
- [HoHoNet (CVPR 2021)](https://openaccess.thecvf.com/content/CVPR2021/papers/Sun_HoHoNet_360_Indoor_Holistic_Understanding_With_Latent_Horizontal_Features_CVPR_2021_paper.pdf)
- [PanelNet (CVPR 2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Yu_PanelNet_Understanding_360_Indoor_Environment_via_Panel_Representation_CVPR_2023_paper.pdf)
- [Huang et al. (arXiv 2024)](https://arxiv.org/pdf/2411.01749)
- [PanoPopups (3DV 2019)](https://arxiv.org/pdf/1907.00939)
- [Feng et al. (3DV 2020)](https://par.nsf.gov/servlets/purl/10280515)
- [Zioulis et al. (3DV 2019)](https://arxiv.org/pdf/1909.08112)
- [Wang et al. (TMM 2023)](https://ieeexplore.ieee.org/abstract/document/10261254/)
- [Yun et al. (AAAI)](https://ojs.aaai.org/index.php/AAAI/article/view/20231)
- [Spdet (TPAMI 2023)](https://ieeexplore.ieee.org/abstract/document/10115484/)
- [Garg et al. (ECCV 2016)](https://arxiv.org/pdf/1603.04992)
- [DepthAnywhere (NeurIPS 2024)](https://proceedings.neurips.cc/paper_files/paper/2024/file/e6c2e85db1f1039177c4495ccd399ac4-Paper-Conference.pdf)
- [PanDA (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Cao_PanDA_Towards_Panoramic_Depth_Anything_with_Unlabeled_Panoramas_and_Mobius_CVPR_2025_paper.pdf)


## 🚀 Multimodel

### 🍇 Audio:

- [Audible Panorama (CHI 2019)](https://dl.acm.org/doi/abs/10.1145/3290605.3300851)  
- [Li et al. (TOG 2018)](https://arxiv.org/pdf/1805.04792)  
- [Morgado et al. (NeurIPS 2018)](https://proceedings.neurips.cc/paper/2018/file/01161aaa0b6d1345dd8fe4e481144d84-Paper.pdf)  
- [AVS-ODV (ICIG 2023)](https://arxiv.org/pdf/2311.05190)  
- [PAV-SOD (ACM Transactions on Multimedia Computing, Communications and Applications 2023)](https://dl.acm.org/doi/abs/10.1145/3565267)  
- [PAV-SOR (ACM MM 2024)](https://dl.acm.org/doi/abs/10.1145/3664647.3681070)  
- [Pano-AVQA (ICCV 2021)](https://openaccess.thecvf.com/content/ICCV2021/papers/Yun_Pano-AVQA_Grounded_Audio-Visual_Question_Answering_on_360deg_Videos_ICCV_2021_paper.pdf)  
- [Masuyama et al. (IROS 2020)](https://arxiv.org/pdf/2007.13976)  
- [Vasudevan et al. (ECCV 2020)](https://arxiv.org/pdf/2003.04210)
- [OAVQA (CAAI 2023)](https://arxiv.org/pdf/2307.10813)
- [Fela et al. (ICMEW 2022)](https://arxiv.org/pdf/2205.08007)  
- [Sonic4D (arXiv 2025)](https://arxiv.org/pdf/2506.15759)  



### 🍇 Ladar:

- [SPOMP (TFR 2024)](https://arxiv.org/pdf/2407.09902)
- [HumanoidPano (arXiv 2025)](https://arxiv.org/pdf/2503.09010)
- [Ma et al. (arXiv 2020)](https://arxiv.org/pdf/2010.14270)
- [OmniColor (ICRA 2024)](https://arxiv.org/pdf/2404.04693)
- [Zhao et al. (arXiv 2022)](https://arxiv.org/pdf/2212.02757)
- [Bernreiter et al. (ICRA 2021)](https://arxiv.org/pdf/2104.10067)
- [PanoramicVO (arXiv 2024)](https://arxiv.org/pdf/2409.09287)
- [MMPAT (CVPRW 2021)](https://openaccess.thecvf.com/content/CVPR2021W/JRDB/papers/He_Know_Your_Surroundings_Panoramic_Multi-Object_Tracking_by_Multimodality_Collaboration_CVPRW_2021_paper.pdf)


### 🍇 Text:

- [VQA 360 (WACV 2020)](https://openaccess.thecvf.com/content_WACV_2020/papers/Chou_Visual_Question_Answering_on_360deg_Images_WACV_2020_paper.pdf)
- [VIEW-QA (arXiv 2024)](https://arxiv.org/pdf/2405.19794)
- [OmniVQA (arXiv 2025)](https://arxiv.org/pdf/2505.14197)
- [OSR-Bench (arXiv 2025)](https://arxiv.org/pdf/2505.11907)
- [Dense360 (arXiv 2025)](https://arxiv.org/pdf/2506.14471)

## 🚀 Visual Generation 

### 🍇 Text-guided Generation:

### 🍉 T2I:

- [Text2Light (TOG 2022)](https://dl.acm.org/doi/abs/10.1145/3550454.3555447)
- [PanFusion (CVPR 2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Taming_Stable_Diffusion_for_Text_to_360_Panorama_Image_Generation_CVPR_2024_paper.pdf)
- [SphereDiffusion (AAAI 2024)](https://ojs.aaai.org/index.php/AAAI/article/view/28429)
- [SMGD (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Sun_Spherical_Manifold_Guided_Diffusion_Model_for_Panoramic_Image_Generation_CVPR_2025_paper.pdf)
- [SphereDiff (arXiv 2025)](https://arxiv.org/pdf/2504.14396)
- [TanDiT (arXiv 2025)](https://arxiv.org/pdf/2506.21681)
- [Diffusion360 (arXiv 2023)](https://arxiv.org/pdf/2311.13141)
- [StitchDiffusion (WACV 2024)](https://openaccess.thecvf.com/content/WACV2024/papers/Wang_Customizing_360-Degree_Panoramas_Through_Text-to-Image_Diffusion_Models_WACV_2024_paper.pdf)
- [PAR (arXiv 2025)](https://arxiv.org/pdf/2505.16862)
- [Panofree (ECCV 2024)](https://link.springer.com/chapter/10.1007/978-3-031-73383-3_9)
- [DreamCube (ICCV 2025)](https://arxiv.org/pdf/2506.17206)

### 🍉 T2V:

- [360DVD (CVPR 2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_360DVD_Controllable_Panorama_Video_Generation_with_360-Degree_Video_Diffusion_Model_CVPR_2024_paper.pdf)
- [PanoWan (arXiv 2025)](https://arxiv.org/pdf/2505.22016)
- [DynamicScaler (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Liu_DynamicScaler_Seamless_and_Scalable_Video_Generation_for_Panoramic_Scenes_CVPR_2025_paper.pdf)
- [PanoDiT (AAAI 2025)](https://ojs.aaai.org/index.php/AAAI/article/view/33089)
- [VidPanos (SIGGRAPH Asia 2024)](https://dl.acm.org/doi/pdf/10.1145/3680528.3687664)
- [VideoPanda (arXiv 2025)](https://arxiv.org/pdf/2504.11389)
- [ViewPoint (arXiv 2025)](https://arxiv.org/pdf/2506.23513) 
- [OmniDrag (arXiv 2024)](https://arxiv.org/pdf/2412.09623)
- [TiP4GEN (ACMMM 2025)](https://arxiv.org/pdf/2508.12415)

  
### 🍉 Text to video:

- [VideoPanda](https://arxiv.org/pdf/2504.11389)
- [HoloTime](https://arxiv.org/pdf/2504.21650)
- [4K4DGen](https://arxiv.org/pdf/2406.13527)
- [PVSR-JSCC (IEEE)](https://ieeexplore.ieee.org/abstract/document/10966439/)

### 🍉 App.:
 
- [DreamScene360 (ECCV 2024)](https://arxiv.org/pdf/2404.06903)
- [SceneDreamer360 (arXiv 2024)](https://arxiv.org/pdf/2408.13711)
- [LayerPano3D (arXiv 2024)](https://arxiv.org/pdf/2408.13252)
- [HoloDreamer (arXiv 2024)](https://arxiv.org/pdf/2407.15187)
- [HoloTime (ACMMM 2025)](https://arxiv.org/pdf/2504.21650)
- [4K4DGen (ICLR 2025)](https://arxiv.org/pdf/2406.13527)
- [Matrix-3D (arXiv 2025)](https://arxiv.org/pdf/2508.08086)
- [HunyuanWorld 1.0 (arXiv 2025)](https://arxiv.org/pdf/2507.21809)
- [PanoGen (NeurIPS 2023)](https://proceedings.neurips.cc/paper_files/paper/2023/file/4522de4178bddb36b49aa26efad537cf-Paper-Conference.pdf)
- [PanoGen++ (Neural Networks 2025)](https://arxiv.org/pdf/2503.09938)
- [VLN-RAM (arXiv 2025)](https://arxiv.org/pdf/2503.18065)
- [Omni2 (arXiv 2025)](https://arxiv.org/pdf/2504.11379)

### 🍇 Completion:

- [Cylin-Painting (TIP 2023)](https://ieeexplore.ieee.org/abstract/document/10370742/)
- [Dream360 (TVCG 2024)](https://arxiv.org/pdf/2401.10564)
- [PanoDecouple (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Zheng_Panorama_Generation_From_NFoV_Image_Done_Right_CVPR_2025_paper.pdf)
- [PanoDiff (arXiv 2023)](https://arxiv.org/pdf/2308.14686)
- [PanoDiffusion (arXiv 2023)](https://arxiv.org/pdf/2307.03177)
- [Diverse Plausible 360° Outpainting (Akimoto et al., CVPR 2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Akimoto_Diverse_Plausible_360-Degree_Image_Outpainting_for_Efficient_3DCG_Background_Creation_CVPR_2022_paper.pdf)
- [BIPS (ECCV 2022)](https://arxiv.org/pdf/2112.06179)
- [2S-ODIS (ECCV 2024)](https://arxiv.org/pdf/2409.09969)
- [ImmerseGAN (3DV 2022)](https://arxiv.org/pdf/2204.07286)
- [AOG-Net (AAAI 2024)](https://ojs.aaai.org/index.php/AAAI/article/view/29332)


### 🍇 Novel View Synthesis:

### 🍉 NeRF:

- [EgoNeRF (CVPR 2023)](https://openaccess.thecvf.com/content/CVPR2023/papers/Choi_Balanced_Spherical_Grid_for_Egocentric_View_Synthesis_CVPR_2023_paper.pdf)  
- [PanoGRF (NeurIPS 2023)](https://proceedings.neurips.cc/paper_files/paper/2023/file/16049e0c3f47899091ac46f8b3afb178-Paper-Conference.pdf)  
- [Omni-NeRF (ICME 2022)](https://inria.hal.science/hal-03646688/document)  
- [OmniLocalRF (CVPR 2024)](https://openaccess.thecvf.com/content/CVPR2024/papers/Choi_OmniLocalRF_Omnidirectional_Local_Radiance_Fields_from_Dynamic_Videos_CVPR_2024_paper.pdf)  
- [360Roam (arXiv 2022)](https://arxiv.org/pdf/2208.02705)  
- [360FusionNeRF (IROS 2023)](https://arxiv.org/pdf/2209.14265)  
- [PERF (TPAMI 2024)](https://arxiv.org/pdf/2310.16831)  
- [PanoHDR-NeRF (arXiv 2022)](https://arxiv.org/pdf/2208.07903)  


### 🍉 3DGS:

- [360-GS (arXiv 2024)](https://arxiv.org/pdf/2402.00763)
- [ODGS (NeurIPS 2024)](https://proceedings.neurips.cc/paper_files/paper/2024/file/6882dbdc34bcd094e6f858c06ce30edb-Paper-Conference.pdf)
- [PanSplat (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhang_PanSplat_4K_Panorama_Synthesis_with_Feed-Forward_Gaussian_Splatting_CVPR_2025_paper.pdf)  
- [OmniGS (arXiv 2024)](https://arxiv.org/pdf/2404.03202)   
- [Splatter-360 (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Chen_Splatter-360_Generalizable_360_Gaussian_Splatting_for_Wide-baseline_Panoramic_Images_CVPR_2025_paper.pdf)  
- [OmniSplat (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025/papers/Lee_OmniSplat_Taming_Feed-Forward_3D_Gaussian_Splatting_for_Omnidirectional_Images_with_CVPR_2025_paper.pdf)  
- [TPGS (arXiv 2025)](https://arxiv.org/pdf/2504.09062)
- [ErpGS (arXiv 2025)](https://arxiv.org/pdf/2505.19883) 
- [OB3D (arXiv 2025)](https://arxiv.org/pdf/2505.20126)
- [PanoSplatt3R (ICCV 2025)](https://arxiv.org/pdf/2507.21960)
- [Seam360GS (arXiv 2025)](https://arxiv.org/pdf/2508.20080)
  
 

### 🍉 Lightweight:

- [OmniSyn (VRW 2022)](https://arxiv.org/pdf/2202.08752)  
- [SOMSI (CVPR 2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Habtegebrial_SOMSI_Spherical_Novel_View_Synthesis_With_Soft_Occlusion_Multi-Sphere_Images_CVPR_2022_paper.pdf)  
- [Casual 6-DoF (TVCG 2022)](https://arxiv.org/pdf/2203.16756)  

<!-- end -->





