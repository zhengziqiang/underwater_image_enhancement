# awsome-underwater-image-enhancement
The repo to collect underwater image enhancement.
>If you are a newcomer to the Deep Learning area and interested on underwater research, the first question you may have is "Which paper should I start reading from?"

>Here is a reading roadmap of Deep Learning based underwater image enhancement and restoration!

The roadmap is constructed in accordance with the following four guidelines:

- From outline to detail
- From old to state-of-the-art
- from generic to specific areas
- focus on state-of-the-art

## Survey
- [Diving Deeper into Underwater Image Enhancement- A Survey]()
- [An Underwater Image Enhancement Benchmark Dataset and Beyond](); Tianjin University, Chongyi Li

## Datasets

- [UOD](https://github.com/Peterchen111/FERNet): [Dual Refinement Underwater Object Detection Network](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650273.pdf) (Not available)
- [ChinaMM](https://pan.baidu.com/s/1XpXJo7H5NXYvq0aQUJ_wzw) (passwd: 6qci). [Website](https://rwenqi.github.io/chinaMM2019uw/); [Real-world Underwater Enhancement: Challenges,Benchmarks, and Solutions](https://arxiv.org/pdf/1901.05320.pdf)
- [URPC](http://www.cnurpc.org/index.html)
- [UDD](https://pan.baidu.com/s/1byq7wEID-OzLSJ8p5A6Z5g#list/path=%2F) (passwd: 2kse); [Website](https://github.com/chongweiliu/UDD_Official); [UDD: An Underwater Open-sea Farm Object Detection Dataset for Underwater Robot Picking](https://arxiv.org/pdf/2003.01446.pdf); DLUT
- [RUIE](https://github.com/dlut-dimt/Realworld-Underwater-Image-Enhancement-RUIE-Benchmark); [Real-world Underwater Enhancement: Challenging, Benchmark and Efficient Solutions](https://arxiv.org/abs/1901.05320); DLUT
- [EUVP](http://irvlab.cs.umn.edu/resources/euvp-dataset); [Website](https://github.com/xahidbuffon/FUnIE-GAN); [Fast Underwater Image Enhancement for Improved Visual Perception](https://ieeexplore.ieee.org/document/9001231)
- [Underwater_imagenet](https://drive.google.com/file/d/1LOM-2A1BSLaFjCY2EEK3DA2Lo37rNw-7/view); [Website](https://github.com/cameronfabbri/Underwater-Color-Correction); [Enhancing Underwater Imagery using Generative Adversarial Networks(UGAN)](https://arxiv.org/abs/1801.04011)
- [UFO-120](http://irvlab.cs.umn.edu/resources/ufo-120-dataset); [SESR: Simultaneous Enhancement and Super-Resolution](http://www.roboticsproceedings.org/rss16/p018.pdf)
- [SUIM](https://github.com/xahidbuffon/SUIM); [Semantic Segmentation of Underwater Imagery: Dataset and Benchmark](https://arxiv.org/pdf/2004.01241.pdf); For semantic segmentation; 7 object categories (Human divers, Aquatic plants and sea-grass, Wrecks and ruins, Robots, Reefs and invertebrates, Fish and vertebrates, Sea-floor and rocks) + Background; Train/Val (1525 pairs), Test(110 pairs)
- [UIEBD](https://li-chongyi.github.io/proj_benchmark.html); [An Underwater Image Enhancement Benchmark Dataset and Beyond(Water-Net)](https://arxiv.org/pdf/1901.05495.pdf)
- [U-45](https://github.com/IPNUISTlegal/underwater-test-dataset-U45-); [A Fusion Adversarial Underwater Image Enhancement Network with a Public Test Dataset](https://arxiv.org/abs/1906.06819); Codes not available
- [Water-GAN dataset](https://github.com/kskin/data); For [WaterGAN](https://github.com/kskin/WaterGAN/)
- [SQUID dataset](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html); [Underwater Single Image Color Restoration Using Haze-Lines and a New Quantitative Dataset](https://arxiv.org/abs/1811.01343); Underwater-hl
- [NOAA](http://www.lirmm.fr/aqualoc/); [AQUALOC: An Underwater Dataset for Visual-Inertial-Pressure Localization](https://arxiv.org/abs/1910.14532); Underwater, Deepsea (275m and 352m); IMU; Camera trajectory (from colmap); Magnitude
- [Sea-thru](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/sea_thru/index.html); [A Method For Removing Water From Underwater Images](http://csms.haifa.ac.il/profiles/tTreibitz/webfiles/sea-thru_cvpr2019.pdf); With depth range(sparse)
- [CADDY stereo data](http://caddy-underwater-datasets.ge.issia.cnr.it/); [CADDY Underwater Stereo-Vision Dataset for Human–Robot Interaction (HRI) in the Context of Diver Activities](https://www.mdpi.com/2077-1312/7/1/16)
- [UWStereoNet](https://github.com/kskin/data); [UWStereoNet: Unsupervised Learning for Depth Estimation and Color Correction of Underwater Stereo Imagery](https://ieeexplore.ieee.org/abstract/document/8794272)  
## Codes
- [Shallow-UWnet](https://github.com/mkartik/Shallow-UWnet); [Shallow-UWnet : Compressed Model for Underwater Image Enhancement](https://arxiv.org/abs/2101.02073) 
- [Positional Normalization](https://github.com/Boyiliee/PONO); [Positional Normalization](https://proceedings.neurips.cc/paper/2019/file/6d0f846348a856321729a2f36734d1a7-Paper.pdf); A general framework, normalization method
- [All-In-One Underwater Image Enhancement using Domain-Adversarial Learning](https://github.com/VITA-Group/All-In-One-Underwater-Image-Enhancement-using-Domain-Adversarial-Learning); [paper](https://openaccess.thecvf.com/content_CVPRW_2019/html/UG2_Prize_Challenge/Uplavikar_All-in-One_Underwater_Image_Enhancement_Using_Domain-Adversarial_Learning_CVPRW_2019_paper.html); CVPRW 2019
- [Underwater-hl](https://github.com/danaberman/underwater-hl); [Diving into Haze-Lines: Color Restoration of Underwater Images](https://www.eng.tau.ac.il/~berman/UnderwaterColorRestoration/UnderwaterHazeLines_BMVC2017.pdf); No-deep, require the depth information, matlab codes
- [Funie-GAN](https://github.com/xahidbuffon/funie-gan); [Fast Underwater Image Enhancement for Improved Visual Perception](https://arxiv.org/pdf/1903.09766.pdf); real time, a good basline, proposed EUVP dataset
- [Review codes](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration); [An Experimental-based Review of Image Enhancement and Image Restoration Methods for Underwater Imaging](https://ieeexplore.ieee.org/abstract/document/8782094/); collect some relative underwater image enhancement methods: [DCP](http://kaiminghe.com/publications/cvpr09.pdf), [GBdehazingRCorrection](https://ieeexplore.ieee.org/document/7471973), [CLAHE](https://ieeexplore.ieee.org/document/6968381), [ULAP](https://research-repository.griffith.edu.au/handle/10072/385140), [Fusion](https://projet.liris.cnrs.fr/imagine/pub/proceedings/CVPR2012/data/papers/011_P1A-11.pdf) and etc.
![More details](imgs/img_enhancement.png)
- [UWGAN_UIE](https://github.com/infrontofme/UWGAN_UIE); [Underwater GAN for Real-world Underwater Color Restoration and Dehazing](arxiv.org/abs/1912.10269);
- [UIEC^2-Net](https://github.com/BIGWangYuDong/UWEnhancement); [CNN-based underwater image enhancement using two color space](https://arxiv.org/abs/2103.07138)
- [Underwater-Image-Enhancement-via-Style-Transfer](https://github.com/AdarshMJ/Underwater-Image-Enhancement-via-Style-Transfer); [Exemplar-based Underwater Image Enhancement Augmented by Wavelet Corrected Transforms](https://openaccess.thecvf.com/content_CVPRW_2019/html/AAMVEM/Jamadandi_Exemplar-based_Underwater_Image_Enhancement_Augmented_by_Wavelet_Corrected_Transforms_CVPRW_2019_paper.html)
- [HybridDetectionGAN](https://github.com/LongChenCV/HybridDetectionGAN); [Perceptual underwater image enhancement with deep learning and physical priors](https://arxiv.org/abs/2008.09697); boost the downstream detection performance, OUC-VISION group
- [Deep_SESR](https://github.com/xahidbuffon/Deep_SESR); [SESR: Simultaneous Enhancement and Super-Resolution](http://www.roboticsproceedings.org/rss16/p018.pdf); UFO dataset; super resolution and image enhancement
- [FusionGAN](https://arxiv.org/pdf/1906.06819.pdf) (No codes)

## Evaluation Metrics
- [UIQM](https://ieeexplore.ieee.org/abstract/document/7305804); [Codes](https://www.dropbox.com/s/6wistdivcjnbm98/UIQM_MATLAB.zip?dl=0)

## Related low-light image enhancement
### Datasets

- [Extreme-Dark](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset/)

### Codes

- [UEGAN](https://github.com/eezkni/UEGAN); [Towards Unsupervised Deep Image Enhancement with Generative Adversarial Network](https://arxiv.org/abs/2012.15020)
- [Zero-DCE](https://github.com/Li-Chongyi/Zero-DCE); [Zero-reference deep curve estimation for low-light image enhancement](https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_Zero-Reference_Deep_Curve_Estimation_for_Low-Light_Image_Enhancement_CVPR_2020_paper.pdf); CVPR 2020
- [DeblurGANv2](https://github.com/VITA-Group/DeblurGANv2); [DeblurGAN-v2: Deblurring (Orders-of-Magnitude) Faster and Better](https://arxiv.org/abs/1908.03826); ICCV 2019
- [CycleISP](https://github.com/swz30/CycleISP); [CycleISP: Real Image Restoration via Improved Data Synthesis](https://arxiv.org/abs/2003.07761); [Youtube](https://www.youtube.com/watch?v=41XKXY--7_E); CVPR 2020 Oral

### Future work
- [Few-shot learning](https://arxiv.org/abs/1904.05046); [Broader case: A Broader Study of Cross-Domain Few-Shot Learning](https://arxiv.org/abs/1912.07200) 
- [Transfer learning](https://arxiv.org/pdf/1911.02685.pdf)
- [Unsupervised learning](https://arxiv.org/abs/2011.00362)

### Research Groups
- [Haifa](https://www.viseaon.haifa.ac.il/) :star::star::star::star::star:
- [UMN](http://irvlab.cs.umn.edu/); :star::star::star::star::star:
- [Marine Robotics Group](http://marinerobotics.mit.edu/biblio); MIT
- [Robust Field Autonomy](https://personal.stevens.edu/~benglot/index.html); Stevens Institute of Technology
- [Mars](https://www.mbari.org/at-sea/cabled-observatory/)
- [AFRL](https://afrl.cse.sc.edu/afrl/home/); University of South Carolina, Columbia
- [Tianjin University](https://li-chongyi.github.io/proj_benchmark.html); UIEBD dataset
- [OUC-Vision](http://ai-ouc.cn/papers.html)
- [OUC-Ai](http://ouc.ai/zhenghaiyong/research/)

### Underwater SLAM and 3D reconstruction
- [Underwater Robot SLAM : Instrumentation and Frameworks](http://ieeexplore.ieee.org/abstract/document/7081165/)
- [Sonar Visual Inertial SLAM of Underwater Structures](https://afrl.cse.sc.edu/afrl/publications/public_html/papers/ICRA18_1211.pdf); Sonar+IMU; ICRA 2018
- [SVIn2: An Underwater SLAM System using Sonar, Visual, Inertial, and Depth Sensor](https://afrl.cse.sc.edu/afrl/publications/public_html/papers/IROS19_0269_FI.pdf); [Code](https://github.com/sharminrahman/SVIn2) Sonar+IMU+Depth(sparse); IROS 2019
- [Contour based Reconstruction of Underwater Structures Using Sonar, Visual, Inertial, and Depth Sensor](https://afrl.cse.sc.edu/afrl/publications/public_html/papers/IROS19_1537_FI.pdf)(https://afrl.cse.sc.edu/afrl/publications/public_html/papers/IROS19_1537_FI.pdf); AFRL; University of South Carolina, Columbia
- [Feature-based SLAM for Imaging Sonar with Under-constrained Landmarks](https://www.cs.cmu.edu/~kaess/pub/Westman18icra.pdf); ICRA 2018
- [Pose-graph SLAM using Forward-looking Sonar](https://frc.ri.cmu.edu/~kaess/pub/Li18ral.pdf); ICRA 2018
- [Simultaneous 3D Reconstruction for Water Surface and Underwater Scene](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yiming_Qian_Simultaneous_3D_Reconstruction_ECCV_2018_paper.pdf); ECCV 2018
- [Fusing Concurrent Orthogonal Wide-Aperture Sonar Images for Dense Underwater 3D Reconstruction](https://arxiv.org/pdf/2007.10407.pdf)
- [DeepURL: Deep Pose Estimation Framework for Underwater Relative Localization](https://arxiv.org/abs/2003.05523)
- [Dense, Sonar-based Reconstruction of Underwater Scenes](https://ieeexplore.ieee.org/document/8968071)
- [Design and Experiments with LoCO AUV: A Low Cost Open-Source Autonomous Underwater Vehicle](); UMN group
- [Matching Color Aerial Images and Underwater Sonar Images using Deep Laearning for Underwater Localization](https://ieeexplore.ieee.org/document/9158356)
- [ratslam](https://github.com/davidmball/ratslam); [RatSLAM: a hippocampal model for simultaneous localization and mapping]()

### Navigation 
- [Coverage Path Planning with Track Spacing Adaptation for Autonomous Underwater Vehicles](https://arxiv.org/abs/2006.12896)
- [Towards Micro Robot Hydrobatics: Vision-based Guidance, Navigation, and Control for Agile Underwater Vehicles in Confined Environments](http://ras.papercept.net/images/temp/IROS/files/3246.pdf)

### Underwater depth estimation
- [Underwater Monocular Image Depth Estimation Using Single-Beam Echosounder](http://ras.papercept.net/images/temp/IROS/files/0791.pdf); [Youtube](https://www.youtube.com/watch?v=JVtbxtM12yA)

### Underwater simulation 
- [uwSim](https://github.com/hblasins/uwSim)

 ## Acknowledgments
- [Underwater_datasets](https://github.com/xinzhichao/underwater_datasets)
- [Funie-GAN](https://github.com/xahidbuffon/funie-gan)
