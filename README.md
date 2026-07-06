# Awesome Egocentric Vision [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of egocentric vision resources.

Egocentric (first-person) vision is a sub-field of computer vision that analyses image/video data obtained using a wearable camera simulating a person's visual field.

## Getting Started

New to egocentric vision? A few landmark resources already in this list are a good entry point:

- **Start here:** [An Outlook into the Future of Egocentric Vision](https://arxiv.org/abs/2308.07123) (IJCV 2024) is a broad survey of the field's tasks, datasets, and open challenges
- **Foundational datasets:** [Ego4D](https://ego4d-data.org), [EPIC-Kitchens 2020](https://epic-kitchens.github.io/2020-100), [Ego-Exo4D](https://ego-exo4d-data.org)

Papers below are grouped by task first (see [Papers](#papers)), then cross-listed by venue for browsing recent conference proceedings; each section is collapsed by default, click "Show papers" to expand. Datasets are listed separately in [Datasets](#datasets), with a highlights table of flagship datasets followed by the full index.

## Contents
- [Papers](#papers)

    > Clustered into various problem statements.
    - [Action/Activity Recognition](#ActionActivity-Recognition)
    - [Object/Hand Recognition](#ObjectHand-Recognition)
    - [Action/Gaze Anticipation](#ActionGaze-Anticipation)
    - [Localization](#Localization)
    - [Clustering](#Clustering)
    - [Video Summarization](#Video-Summarization)
    - [Social Interactions](#Social-Interactions)
    - [Pose Estimation](#Pose-Estimation)
    - [Human Object Interaction](#Human-Object-Interaction)
    - [Temporal Boundary Detection](#Temporal-Boundary-Detection)
    - [Privacy in Egocentric Videos](#Privacy-in-Egocentric-Videos)
    - [Multiple Egocentric Tasks](#Multiple-Egocentric-Tasks)
    - [Task Understanding](#Task-Understanding)
    - [Ego-Exo Cross-View Learning](#ego-exo-cross-view-learning)
    - [Egocentric Video-Language Models & Question Answering](#egocentric-video-language-models--question-answering)
    - [Egocentric Video Generation & World Models](#egocentric-video-generation--world-models)
    - [3D Scene Reconstruction & Mapping](#3d-scene-reconstruction--mapping)
    - [Assistive & Navigation](#assistive--navigation)
    - [Miscellaneous (New Tasks)](#Miscellaneous-New-Tasks)

    > Clustered according to the conferences.
    - [CVPR](#CVPR)
    - [ECCV](#ECCV)
    - [ICCV](#ICCV)
    - [WACV](#WACV)
    - [BMVC](#BMVC)
    - [NeurIPS](#neurips)

- [Datasets](#datasets)
- [Workshops/Tutorials](#workshopstutorials)

## Papers

> Clustered in various problem statements.

### Action/Activity Recognition

<details>
<summary>Show papers (44)</summary>

- [ProbRes: Probabilistic Jump Diffusion for Open-World Egocentric Activity Recognition](https://arxiv.org/abs/2504.03948) - Sanjoy Kundu, Shanmukha Vellamcheti, and Sathyanarayanan N. Aakur. In ICCV 2025.

- [Understanding Multi-Task Activities from Single-Task Videos](https://openaccess.thecvf.com/content/CVPR2025/html/Shen_Understanding_Multi-Task_Activities_from_Single-Task_Videos_CVPR_2025_paper.html) - Yuhan Shen and Ehsan Elhamifar. In CVPR 2025.

- [Test-Time Adaptation for Combating Missing Modalities in Egocentric Videos](https://arxiv.org/abs/2404.15161) - Merey Ramazanova, Alejandro Pardo, Bernard Ghanem, and Motasem Alfarra. In ICLR 2025.

- [On the Utility of 3D Hand Poses for Action Recognition](https://arxiv.org/abs/2403.09805) - Md Salman Shamil, Dibyadip Chatterjee, Fadime Sener, Shugao Ma, and Angela Yao. In ECCV 2024. [[project page]](https://s-shamil.github.io/HandFormer/)

- [SoundingActions: Learning How Actions Sound from Narrated Egocentric Videos](https://arxiv.org/abs/2404.05206) - Changan Chen, Kumar Ashutosh, Rohit Girdhar, David Harwath, and Kristen Grauman. In CVPR 2024. [[project page]](https://vision.cs.utexas.edu/projects/soundingactions)

- [X-MIC: Cross-Modal Instance Conditioning for Egocentric Action Generalization](https://arxiv.org/abs/2403.19811) - Anna Kukleva, Fadime Sener, Edoardo Remelli, Bugra Tekin, Eric Sauser, Bernt Schiele, and Shugao Ma. In CVPR 2024. [[code]](https://github.com/annusha/xmic)

- [Progress-Aware Online Action Segmentation for Egocentric Procedural Task Videos](https://openaccess.thecvf.com/content/CVPR2024/html/Shen_Progress-Aware_Online_Action_Segmentation_for_Egocentric_Procedural_Task_Videos_CVPR_2024_paper.html) - Yuhan Shen and Ehsan Elhamifar. In CVPR 2024. [[code]](https://github.com/Yuhan-Shen/ProTAS)

- [TIM: A Time Interval Machine for Audio-Visual Action Recognition](https://arxiv.org/abs/2404.05559) - Jacob Chalk, Jaesung Huh, Evangelos Kazakos, Andrew Zisserman, and Dima Damen. In CVPR 2024. [[project page]](https://jacobchalk.github.io/TIM-Project) [[code]](https://github.com/JacobChalk/TIM)

- [Multimodal Distillation for Egocentric Action Recognition](https://openaccess.thecvf.com/content/ICCV2023/papers/Radevski_Multimodal_Distillation_for_Egocentric_Action_Recognition_ICCV_2023_paper.pdf) - Gorjan Radevski, Dusan Grujicic, Matthew Blaschko, Marie-Francine Moens, and Tinne Tuytelaars. In ICCV 2023. [[code]](https://github.com/gorjanradevski/multimodal-distillation)

- [What can a cook in Italy teach a mechanic in India? Action Recognition Generalisation Over Scenarios and Locations](https://openaccess.thecvf.com/content/ICCV2023/papers/Plizzari_What_Can_a_Cook_in_Italy_Teach_a_Mechanic_in_ICCV_2023_paper.pdf) - Chiara Plizzari, Toby Perrett, Barbara Caputo, and Dima Damen. In ICCV 2023. [[project page]](https://web.archive.org/web/20241209215715/https://chiaraplizz.github.io/what-can-a-cook/) [[code]](https://github.com/Chiaraplizz/ARGO1M-What-can-a-cook)

- [MMG-Ego4D: Multimodal Generalization in Egocentric Action Recognition](https://openaccess.thecvf.com/content/CVPR2023/papers/Gong_MMG-Ego4D_Multimodal_Generalization_in_Egocentric_Action_Recognition_CVPR_2023_paper.pdf) - Xinyu Gong, Sreyas Mohan, Naina Dhingra, Jean-Charles Bazin, YILEI LI, Zhangyang Wang, Rakesh Ranjan. In CVPR 2023.

- [Therbligs In Action: Video Understanding through Motion Primitives](https://arxiv.org/pdf/2304.03631.pdf) - Eadom Dessalene, Michael Maynord, Cornelia Fermu ̈ller, Yiannis Aloimonos. In CVPR 2023. [[project page]](https://prg.cs.umd.edu/Therbligs)

- [Learning Video Representations from Large Language Models](https://arxiv.org/pdf/2212.04501.pdf; https://facebookresearch.github.io/LaViLa) - Yue Zhao, Ishan Misra, Philipp Krähenbühl, Rohit Girdhar. In CVPR 2023. [[project page]](https://facebookresearch.github.io/LaViLa/) [[code]](https://github.com/facebookresearch/LaViLa) [[demo]](https://huggingface.co/spaces/nateraw/lavila)

- [Learning State-Aware Visual Representations from Audible Interactions](https://arxiv.org/pdf/2209.13583.pdf) - Himangi Mittal, Pedro Morgado, Unnat Jain, Abhinav Gupta. In NeurIPS 2022. [[Code]](https://github.com/HimangiM/RepLAI) [[Video]](https://www.youtube.com/watch?v=hn5P8BPrPZ4)

- [Egocentric Activity Recognition and Localization on a 3D Map](https://arxiv.org/pdf/2105.09544.pdf) - Miao Liu, Lingni Ma, Kiran Somasundaram, Yin Li, Kristen Grauman, James M. Rehg, Chao Li. In ECCV 2022.

- [SOS! Self-supervised Learning Over Sets Of Handled Objects In Egocentric Action Recognition](https://arxiv.org/abs/2204.04796) - Victor Escorcia, Ricardo Guerrero, Xiatian Zhu, Brais Martinez. In ECCV 2022.

- [E2(GO)MOTION: Motion Augmented Event Stream for Egocentric Action Recognition](https://openaccess.thecvf.com/content/CVPR2022/papers/Plizzari_E2GOMOTION_Motion_Augmented_Event_Stream_for_Egocentric_Action_Recognition_CVPR_2022_paper.pdf) - Chiara Plizzari, Mirco Planamente, Gabriele Goletto, Marco Cannici, Emanuele Gusso, Matteo Matteucci, Barbara Caputo. In CVPR 2022.

- [Domain Generalization through Audio-Visual Relative Norm Alignment in First Person Action Recognition](https://openaccess.thecvf.com/content/WACV2022/papers/Planamente_Domain_Generalization_Through_Audio-Visual_Relative_Norm_Alignment_in_First_Person_WACV_2022_paper.pdf) - Mirco Planamente, Chiara Plizzari, Emanuele Alberti, and Barbara Caputo. In WACV 2022.

- [With a Little Help from my Temporal Context: Multimodal Egocentric Action Recognition](https://www.bmvc2021-virtualconference.com/assets/papers/0610.pdf) - Evangelos Kazakos, Jaesung Huh, Arsha Nagrani, Andrew Zisserman, and Dima Damen. In BMVC 2021. [[project page]](https://ekazakos.github.io/MTCN-project/) [[code]](https://github.com/ekazakos/MTCN)

- [Stacked Temporal Attention: Improving First-person Action Recognition by Emphasizing Discriminative Clips](https://www.bmvc2021-virtualconference.com/assets/papers/0243.pdf) - Lijin Yang, Yifei Huang, Yusuke Sugano, and Yoichi Sato. In BMVC 2021. [[project page]](https://www.bmvc2021-virtualconference.com/conference/papers/paper_0243.html)

- [Interactive Prototype Learning for Egocentric Action Recognition](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Interactive_Prototype_Learning_for_Egocentric_Action_Recognition_ICCV_2021_paper.html) - Xiaohan Wang, Linchao Zhu, Heng Wang, and Yi Yang. In ICCV 2021.

- [Multi-Modal Domain Adaptation for Fine-Grained Action Recognition](https://openaccess.thecvf.com/content_CVPR_2020/papers/Munro_Multi-Modal_Domain_Adaptation_for_Fine-Grained_Action_Recognition_CVPR_2020_paper.pdf) - Jonathan Munro and Dima Damen. In CVPR 2020. [[project page]](https://jonmun.github.io/mmsada/) [[code]](https://github.com/jonmun/MM-SADA-code)

- [Integrating Human Gaze Into Attention for Egocentric Activity Recognition](https://openaccess.thecvf.com/content/WACV2021/html/Min_Integrating_Human_Gaze_Into_Attention_for_Egocentric_Activity_Recognition_WACV_2021_paper.html) - Kyle Min, Jason J. Corso. In WACV 2021. [[code]](https://github.com/MichiganCOG/Gaze-Attention)

- [EPIC-Fusion: Audio-Visual Temporal Binding for Egocentric Action Recognition](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kazakos_EPIC-Fusion_Audio-Visual_Temporal_Binding_for_Egocentric_Action_Recognition_ICCV_2019_paper.pdf) - Evangelos Kazakos, Arsha Nagrani, Andrew Zisserman, and Dima Damen. In ICCV 2019. [[code]](https://github.com/ekazakos/temporal-binding-network) [[project page]](https://ekazakos.github.io/TBN/)

- [LSTA: Long Short-Term Attention for Egocentric Action Recognition](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sudhakaran_LSTA_Long_Short-Term_Attention_for_Egocentric_Action_Recognition_CVPR_2019_paper.pdf) - Swathikiran Sudhakaran, Sergio Escalera, and Oswald Lanz. In CVPR 2019. [[code]](https://github.com/swathikirans/LSTA)

- [Egocentric Activity Recognition on a Budget](https://openaccess.thecvf.com/content_cvpr_2018/papers/Possas_Egocentric_Activity_Recognition_CVPR_2018_paper.pdf) - Rafael Possas, Sheila Pinto Caceres, and Fabio Ramos. In CVPR 2018. [[demo]](https://youtu.be/GBo4sFNzhtU)

- [From Lifestyle VLOGs to Everyday Interaction](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0733.pdf) - David F. Fouhey, Weicheng Kuo, Alexei A. Efros, and Jitendra Malik. In CVPR 2018. [[project page]](https://web.archive.org/web/20241102024857/https://web.eecs.umich.edu/~fouhey/2017/VLOG/index.html)

- [Actor and Observer: Joint Modeling of First and Third-Person Videos](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sigurdsson_Actor_and_Observer_CVPR_2018_paper.pdf) - Gunnar A. Sigurdsson, Abhinav Gupta, Cordelia Schmid, Ali Farhadi, and Karteek Alahari. In CVPR 2018. [[code]](https://github.com/gsig/actor-observer)

- [In the eye of beholder: Joint learning of gaze and actions in first person video](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf) - Yin Li, Miao Liu, and James M. Rehg. In ECCV 2018.

- [Privacy-Preserving Human Activity Recognition from Extreme Low Resolution](https://arxiv.org/pdf/1604.03196) - Michael S. Ryoo, Brandon Rothrock, Charles Fleming, and Hyun Jong Yang. In AAAI 2017.

- [Jointly Recognizing Object Fluents and Tasks in Egocentric Videos](https://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_Jointly_Recognizing_Object_ICCV_2017_paper.pdf) - Yang Liu, Ping Wei, and Song-Chun Zhu. In ICCV 2017.

- [Trajectory Aligned Features For First Person Action Recognition](http://cdn.iiit.ac.in/cdn/cvit.iiit.ac.in/images/JournalPublications/2016/Suriya_2016_Trajectory_Features.pdf) - Suriya Singh, Chetan Arora, and C.V. Jawahar. In Pattern Recognition 2017.

- [First Person Action Recognition Using Deep Learned Descriptors](https://www.cv-foundation.org/openaccess/content_cvpr_2016/app/S12-15.pdf) - Suriya Singh, Chetan Arora, and C.V. Jawahar. In CVPR 2016. [[project page]](http://cvit.iiit.ac.in/research/projects/cvit-projects/first-person-action-recognition) [[code]](https://github.com/suriyasingh/EgoConvNet)

- [Understanding Hand-Object Manipulation with Grasp Types and Object Attributes](http://www.cs.cmu.edu/~kkitani/pdf/CKY-RSS16.pdf) - Minjie Cai, Kris M. Kitani, and Yoichi Sato. In Robotics: Science and Systems 2016.

- [Delving into egocentric actions](https://openaccess.thecvf.com/content_cvpr_2015/papers/Li_Delving_Into_Egocentric_2015_CVPR_paper.pdf) - Yin Li, Zhefan Ye, and James M. Rehg. In CVPR 2015.

- [Pooled Motion Features for First-Person Videos](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Ryoo_Pooled_Motion_Features_2015_CVPR_paper.pdf) - Michael S. Ryoo, Brandon Rothrock, and Larry H. Matthies. In CVPR 2015.

- [Generating Notifications for Missing Actions: Don't forget to turn the lights off!](https://homes.cs.washington.edu/~ali/alarm-iccv.pdf) - Bilge Soran, Ali Farhadi, and Linda Shapiro. In ICCV 2015.

- [First-Person Activity Recognition: What Are They Doing to Me?](http://cvrc.ece.utexas.edu/mryoo/papers/cvpr2013_ryoo.pdf) - M. S. Ryoo and Larry Matthies. In CVPR 2013.

- [Detecting activities of daily living in first-person camera views](https://www.cs.cmu.edu/~deva/papers/ADL_2012.pdf) - Hamed Pirsiavash and Deva Ramanan. In CVPR 2012.

- [Learning to recognize daily actions using gaze](http://ai.stanford.edu/~alireza/publication/ECCV12.pdf) - Alireza Fathi, Yin Li, and James M. Rehg. In ECCV 2012.

- [Learning to recognize objects in egocentric activities](https://ai.stanford.edu/~alireza/publication/CVPR11.pdf) - Alireza Fathi, Xiaofeng Ren, and James M. Rehg. In CVPR 2011.

- [Fast unsupervised ego-action learning for first-person sports videos](http://www.dgcv.nii.ac.jp/Publications/Papers/2011/CVPR2011a.pdf) - Kris M. Kitani, Takahiro Okabe, Yoichi Sato, and Akihiro Sugimoto. In CVPR 2011. [[project page]](https://www.ri.cmu.edu/publications/fast-unsupervised-ego-action-learning-for-first-person-sports-videos/)

- [Temporal segmentation and activity classification from first-person sensing](https://ieeexplore.ieee.org/document/5204354) - Ekaterina H. Spriggs, Fernando De La Torre, and Martial Hebert. In CVPR Workshops 2009.

- [Wearable hand activity recognition for event summarization](https://ieeexplore.ieee.org/document/1550796) - W.W. Mayol and D.W. Murray. In IEEE International Symposium on Wearable Computers, 2005.

</details>

### Object/Hand Recognition

<details>
<summary>Show papers (24)</summary>

- [Towards Stable Self-Supervised Object Representations in Unconstrained Egocentric Video](https://arxiv.org/abs/2603.13912) - Yuting Tan, Xilong Cheng, Yunxiao Qin, Zhengnan Li, and Jingjing Zhang. In CVPR 2026.

- [EgoXtreme: A Dataset for Robust Object Pose Estimation in Egocentric Views under Extreme Conditions](https://arxiv.org/abs/2603.25135) - Taegyoon Yoon, Yegyu Han, Seojin Ji, Jaewoo Park, Sojeong Kim, Taein Kwon, and Hyung-Sin Kim. In CVPR 2026. [[project page]](https://taegyoun88.github.io/EgoXtreme/) [[code]](https://github.com/taegyoun88/EgoXtreme)

- [Robust Egocentric Referring Video Object Segmentation via Dual-Modal Causal Intervention](https://arxiv.org/abs/2512.24323) - Haijing Liu, Zhiyuan Song, Hefeng Wu, Tao Pu, Keze Wang, and Liang Lin. In NeurIPS 2025.

- [Is Tracking Really More Challenging in First Person Egocentric Vision?](https://arxiv.org/abs/2507.16015) - Matteo Dunnhofer, Zaira Manigrasso, and Christian Micheloni. In ICCV 2025. [[project page]](https://machinelearning.uniud.it/datasets/vista/) [[code]](https://github.com/matteo-dunnhofer/fpv-tracking-toolkit)

- [HaWoR: World-Space Hand Motion Reconstruction from Egocentric Videos](https://arxiv.org/abs/2501.02973) - Jinglei Zhang, Jiankang Deng, Chao Ma, and Rolandos Alexandros Potamias. In CVPR 2025. [[project page]](https://hawor-project.github.io/)

- [HOT3D: Hand and Object Tracking in 3D from Egocentric Multi-View Videos](https://arxiv.org/abs/2411.19167) - Prithviraj Banerjee, Sindi Shkodrani, Pierre Moulon, Shreyas Hampali, Shangchen Han, Fan Zhang, et al. In CVPR 2025. [[project page]](https://facebookresearch.github.io/hot3d/)

- [ActionVOS: Actions as Prompts for Video Object Segmentation](https://arxiv.org/abs/2407.07402) - Liangyang Ouyang, Ruicong Liu, Yifei Huang, Ryosuke Furuta, and Yoichi Sato. In ECCV 2024. [[code]](https://github.com/ut-vision/ActionVOS)

- [Instance Tracking in 3D Scenes from Egocentric Videos](https://arxiv.org/abs/2312.04117) - Yunhan Zhao, Haoyu Ma, Shu Kong, and Charless Fowlkes. In CVPR 2024. [[code]](https://github.com/IT3DEgo/IT3DEgo)

- [Learning to Segment Referred Objects from Narrated Egocentric Videos](https://openaccess.thecvf.com/content/CVPR2024/html/Shen_Learning_to_Segment_Referred_Objects_from_Narrated_Egocentric_Videos_CVPR_2024_paper.html) - Yuhan Shen, Huiyu Wang, Xitong Yang, Matt Feiszli, Ehsan Elhamifar, Lorenzo Torresani, and Effrosyni Mavroudi. In CVPR 2024.

- [EgoTracks: A Long-term Egocentric Visual Object Tracking Dataset](https://arxiv.org/abs/2301.03213) - Hao Tang, Kevin J Liang, Kristen Grauman, Matt Feiszli, and Weiyao Wang. In NeurIPS 2023. [[dataset]](https://ego4d-data.org/docs/data/egotracks/)

- [Self-Supervised Object Detection from Egocentric Videos](https://openaccess.thecvf.com/content/ICCV2023/papers/Akiva_Self-Supervised_Object_Detection_from_Egocentric_Videos_ICCV_2023_paper.pdf) - Peri Akiva, Jing Huang, Kevin J Liang, Rama Kovvuri, Xingyu Chen, Matt Feiszli, Kristin Dana, and Tal Hassner. In ICCV 2023. 

- [EgoObjects: A Large-Scale Egocentric Dataset for Fine-Grained Object Understanding](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhu_EgoObjects_A_Large-Scale_Egocentric_Dataset_for_Fine-Grained_Object_Understanding_ICCV_2023_paper.pdf) - Chenchen Zhu, Fanyi Xiao, Andres Alvarado, Yasmine Babaei, Jiabo Hu, Hichem El-Mohri, Sean Culatana, Roshan Sumbaly, and Zhicheng Yan. In ICCV 2023. [[project page]](https://research.facebook.com/blog/2023/3/egoobjects-large-scale-egocentric-dataset-for-category-and-instance-level-object-understanding/) [[code]](https://github.com/facebookresearch/EgoObjects)

- [Hierarchical Temporal Transformer for 3D Hand Pose Estimation and Action Recognition from Egocentric RGB Videos](https://arxiv.org/pdf/2209.09484.pdf) - Yilin Wen, Hao Pan, Lei Yang, Jia Pan, Taku Komura, Wenping Wang. In CVPR 2023. [[Code]](https://github.com/fylwen/HTT)

- [Generative Adversarial Network for Future Hand Segmentation from Egocentric Video](https://arxiv.org/pdf/2203.11305.pdf) - Wenqi Jia, Miao Liu, James M. Rehg. In ECCV 2022.

- [Whose Hand Is This? Person Identification From Egocentric Hand Gestures](https://openaccess.thecvf.com/content/WACV2021/html/Tsutsui_Whose_Hand_Is_This_Person_Identification_From_Egocentric_Hand_Gestures_WACV_2021_paper.html) - Satoshi Tsutsui, Yanwei Fu, and David J. Crandall. In WACV 2021.

- [Generalizing Hand Segmentation in Egocentric Videos with Uncertainty-Guided Model Adaptation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_Generalizing_Hand_Segmentation_in_Egocentric_Videos_With_Uncertainty-Guided_Model_Adaptation_CVPR_2020_paper.pdf) - Minjie Cai, Feng Lu, and Yoichi Sato. In CVPR 2020. [[code]](https://github.com/cai-mj/UMA)

- [H+O: Unified Egocentric Recognition of 3D Hand-Object Poses and Interactions](https://openaccess.thecvf.com/content_CVPR_2019/papers/Tekin_HO_Unified_Egocentric_Recognition_of_3D_Hand-Object_Poses_and_Interactions_CVPR_2019_paper.pdf) - Bugra Tekin, Federica Bogo, and Marc Pollefeys. In CVPR 2019. [[video]](https://youtu.be/ko6kNZ9DuAk?t=3240)

- [Analysis of Hand Segmentation in the Wild](https://arxiv.org/pdf/1803.03317) - Aisha Urooj Khan and Ali Borji. In CVPR 2018.

- [First-Person Hand Action Benchmark with RGB-D Videos and 3D Hand Pose Annotations](https://openaccess.thecvf.com/content_cvpr_2018/papers/Garcia-Hernando_First-Person_Hand_Action_CVPR_2018_paper.pdf) - Guillermo Garcia-Hernando, Shanxin Yuan, Seungryul Baek, and Tae-Kyun Kim. In CVPR 2018. [[project page]](https://guiggh.github.io/publications/first-person-hands/) [[code]](https://github.com/guiggh/hand_pose_action)

- [Egocentric Gesture Recognition Using Recurrent 3D Convolutional Neural Networks with Spatiotemporal Transformer Modules](https://openaccess.thecvf.com/content_ICCV_2017/papers/Cao_Egocentric_Gesture_Recognition_ICCV_2017_paper.pdf) - Congqi Cao, Yifan Zhang, Yi Wu, Hanqing Lu, and Jian Cheng. In ICCV 2017.

- [Lending a hand: Detecting hands and recognizing activities in complex egocentric interactions](https://web.archive.org/web/20210117023345/http://homes.sice.indiana.edu/sbambach/papers/iccv-egohands.pdf) - Sven Bambach, Stefan Lee, David J. Crandall, and Chen Yu. In ICCV 2015.

- [Detecting Snap Points in Egocentric Video with a Web Photo Prior](https://www.cs.utexas.edu/~grauman/papers/bo-eccv2014.pdf) - Bo Xiong and Kristen Grauman. In ECCV 2014. [[project page]](http://vision.cs.utexas.edu/projects/ego_snappoints/) [[code]](http://vision.cs.utexas.edu/projects/ego_snappoints/#code)

- [Pixel-level hand detection in ego-centric videos](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Li_Pixel-Level_Hand_Detection_2013_CVPR_paper.pdf) - Cheng Li and Kris M. Kitani. In CVPR 2013. [[video]](https://youtu.be/N756YmLpZyY) [[code]](https://github.com/irllabs/handtrack)

- [Context-based vision system for place and object recognition](https://www.cs.ubc.ca/~murphyk/Papers/iccv03.pdf) - Antonio Torralba, Kevin P. Murphy, William T. Freeman, Mark A. Rubin. In ICCV 2003. [[project page]](https://www.cs.ubc.ca/~murphyk/Vision/placeRecognition.html)

</details>

### Action/Gaze Anticipation

<details>
<summary>Show papers (24)</summary>

- [Gaze Beyond the Frame: Forecasting Egocentric 3D Visual Span](https://arxiv.org/abs/2511.18470) - Heeseung Yun, Joonil Na, Jaeyeon Kim, Calvin Murdock, and Gunhee Kim. In NeurIPS 2025.

- [HOIGaze: Gaze Estimation During Hand-Object Interactions in Extended Reality Exploiting Eye-Hand-Head Coordination](https://arxiv.org/abs/2504.19828) - Zhiming Hu, Daniel Haeufle, Syn Schmitt, and Andreas Bulling. In SIGGRAPH 2025. [[project page]](https://zhiminghu.net/hu25_hoigaze.html) [[code]](https://github.com/CraneHzm/HOIGaze)

- [Test-time Ego-Exo-centric Adaptation for Action Anticipation via Multi-Label Prototype Growing and Dual-Clue Consistency](https://arxiv.org/abs/2603.09798) - Zhaofeng Shi, Heqian Qiu, Lanxiao Wang, Qingbo Wu, Fanman Meng, Lili Pan, and Hongliang Li. In CVPR 2026. [[code]](https://github.com/ZhaofengSHI/DCPGN)

- [Forecasting 3D Scanpaths in Egocentric Video](https://openaccess.thecvf.com/content/CVPR2026/papers/Ryan_Forecasting_3D_Scanpaths_in_Egocentric_Video_CVPR_2026_paper.pdf) - Fiona Ryan, Ishwarya Ananthabhotla, Yijun Qian, Judy Hoffman, James M. Rehg, Vamsi Krishna Ithapu, and Calvin Murdock. In CVPR 2026.

- [FIction: 4D Future Interaction Prediction from Video](https://arxiv.org/abs/2412.00932) - Kumar Ashutosh, Georgios Pavlakos, and Kristen Grauman. In CVPR 2025. [[code]](https://github.com/thechargedneutron/FIction)

- [Listen to Look into the Future: Audio-Visual Egocentric Gaze Anticipation](https://arxiv.org/abs/2305.03907) - Bolin Lai, Fiona Ryan, Wenqi Jia, Miao Liu, and James M. Rehg. In ECCV 2024. [[project page]](https://bolinlai.github.io/CSTS-EgoGazeAnticipation/)

- [AFF-ttention! Affordances and Attention models for Short-Term Object Interaction Anticipation](https://arxiv.org/abs/2406.01194) - Lorenzo Mur-Labadia, Ruben Martinez-Cantin, Jose J. Guerrero, Giovanni Maria Farinella, and Antonino Furnari. In ECCV 2024. [[code]](https://github.com/lmur98/AFFttention)

- [PALM: Predicting Actions through Language Models](https://arxiv.org/abs/2311.17944) - Sanghwan Kim, Daoji Huang, Yongqin Xian, Otmar Hilliges, Luc Van Gool, and Xi Wang. In ECCV 2024.

- [Summarize the Past to Predict the Future: Natural Language Descriptions of Context Boost Multimodal Object Interaction Anticipation](https://arxiv.org/abs/2301.09209) - Razvan-George Pasca, Alexey Gavryushin, Muhammad Hamza, Yen-Ling Kuo, Kaichun Mo, Luc Van Gool, Otmar Hilliges, and Xi Wang. In CVPR 2024. [[project page]](https://eth-ait.github.io/transfusion-proj/)

- [Uncertainty-aware State Space Transformer for Egocentric 3D Hand Trajectory Forecasting](https://openaccess.thecvf.com/content/ICCV2023/papers/Bao_Uncertainty-aware_State_Space_Transformer_for_Egocentric_3D_Hand_Trajectory_Forecasting_ICCV_2023_paper.pdf) - Wentao Bao, Lele Chen, Libing Zeng, Zhong Li, Yi Xu, Junsong Yuan, and Yu Kong. In ICCV 2023. [[project page]](https://web.archive.org/web/20231211050832/https://actionlab-cv.github.io/EgoHandTrajPred/) [[code]](https://github.com/oppo-us-research/USST) 

- [Intention-Conditioned Long-Term Human Egocentric Action Forecasting](https://openaccess.thecvf.com/content/WACV2023/papers/Mascaro_Intention-Conditioned_Long-Term_Human_Egocentric_Action_Anticipation_WACV_2023_paper.pdf) - Esteve Valls Mascaro, Hyemin Ahn, and Dongheui Lee. In WACV 2023.

- [A Hybrid Egocentric Activity Anticipation Framework via Memory-Augmented Recurrent and One-shot Representation Forecasting](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_A_Hybrid_Egocentric_Activity_Anticipation_Framework_via_Memory-Augmented_Recurrent_and_CVPR_2022_paper.pdf) - Tianshan Liu and Kin-Man Lam. In CVPR 2022.

- [Learning to Anticipate Egocentric Actions by Imagination](https://arxiv.org/pdf/2101.04924.pdf) - Yu Wu, Linchao Zhu, Xiaohan Wang, Yi Yang, and Fei Wu. In TIP 2021.

- [Forecasting Human-Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf) - Miao Liu, Siyu Tang, Yin Li, and James M. Rehg. In ECCV 2020. [[project page]](https://aptx4869lm.github.io/ForecastingHOI/)

- [How Can I See My Future? FvTraj: Using First-person View for Pedestrian Trajectory Prediction](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520562.pdf) - Huikun Bi, Ruisi Zhang, Tianlu Mao, Zhigang Deng, and Zhaoqi Wang. In ECCV 2020. [[presentation video]](https://youtu.be/HcsyH7zMHAw) [[summary video]](https://youtu.be/X1cSNWT6Gr0)

- [Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior](https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf) - Osama Makansi, Ozgun Cicek, Kevin Buchicchio, and Thomas Brox. In CVPR 2020. [[demo]](https://youtu.be/_9Ml5IFwbSY) [[code]](https://github.com/lmb-freiburg/FLN-EPN-RPN) [[project page]](https://lmb.informatik.uni-freiburg.de/Publications/2020/MCBB20/)

- [EGO-TOPO: Environment Affordances from Egocentric Video](https://openaccess.thecvf.com/content_CVPR_2020/papers/Nagarajan_Ego-Topo_Environment_Affordances_From_Egocentric_Video_CVPR_2020_paper.pdf) - Tushar Nagarajan, Yanghao Li, Christoph Feichtenhofer, and Kristen Grauman. In CVPR 2020. [[project page]](http://vision.cs.utexas.edu/projects/ego-topo/) [[demo]](http://vision.cs.utexas.edu/projects/ego-topo/demo.html)

- [What Would You Expect? Anticipating Egocentric Actions with Rolling-Unrolling LSTMs and Modality Attention](https://arxiv.org/pdf/1905.09035) - Antonino Furnari and Giovanni Maria Farinella. In ICCV 2019 [[code]](https://github.com/fpv-iplab/rulstm) [[demo]](https://youtu.be/buIEKFHTVIg)

- [Digging Deeper into Egocentric Gaze Prediction](https://arxiv.org/pdf/1904.06090) - Hamed R. Tavakoli, Esa Rahtu, Juho Kannala, and Ali Borji. In WACV 2019.

- [Predicting Gaze in Egocentric Video by Learning Task-dependent Attention Transition](https://arxiv.org/pdf/1803.09125) - Yifei Huang, Minjie Cai, Zhenqiang Li, and Yoichi Sato. In ECCV 2018 [[code]](https://github.com/hyf015/egocentric-gaze-prediction)

- [First-Person Activity Forecasting with Online Inverse Reinforcement Learning](https://arxiv.org/pdf/1612.07796) - Nicholas Rhinehart and Kris M. Kitani. In ICCV 2017. [[video]](https://youtu.be/rvVoW3iuq-s)

- [Deep future gaze: Gaze anticipation on egocentric videos using adversarial networks](https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Deep_Future_Gaze_CVPR_2017_paper.pdf) - Mengmi Zhang, Keng Teck Ma, Joo Hwee Lim, Qi Zhao, and Jiashi Feng. In CVPR 2017. [[code]](https://github.com/Mengmi/deepfuturegaze_gan)

- [Going deeper into first-person activity recognition](http://www.cs.cmu.edu/~kkitani/pdf/MFK-CVPR2016.pdf) - Minghuang Ma, Haoqi Fan, and Kris M. Kitani. In CVPR 2016.

- [Learning to predict gaze in egocentric video](http://ai.stanford.edu/~alireza/publication/Li-Fathi-Rehg-ICCV13.pdf) - Yin Li, Alireza Fathi, and James M. Rehg. In ICCV 2013.

</details>

### Localization

<details>
<summary>Show papers (13)</summary>

- [Beyond Caption-Based Queries for Video Moment Retrieval](https://arxiv.org/abs/2603.02363) - David Pujol-Perich, Albert Clapés, Dima Damen, Sergio Escalera, and Michael Wray. In CVPR 2026.

- [PRVQL: Progressive Knowledge-guided Refinement for Robust Egocentric Visual Query Localization](https://arxiv.org/abs/2502.07707) - Bing Fan, Yunhe Feng, Yapeng Tian, James Chenhao Liang, Yuewei Lin, Yan Huang, and Heng Fan. In ICCV 2025. [[code]](https://github.com/fb-reps/PRVQL)

- [Egocentric Action-aware Inertial Localization in Point Clouds with Vision-Language Guidance](https://arxiv.org/abs/2505.14346) - Mingfang Zhang, Ryo Yonetani, Yifei Huang, Liangyang Ouyang, Ruicong Liu, and Yoichi Sato. In ICCV 2025.

- [Spatial Cognition from Egocentric Video: Out of Sight, Not Out of Mind](https://arxiv.org/abs/2404.05072) - Chiara Plizzari, Shubham Goel, Toby Perrett, Jacob Chalk, Angjoo Kanazawa, and Dima Damen. In 3DV 2025. [[project page]](https://dimadamen.github.io/OSNOM/)

- [Online Episodic Memory Visual Query Localization with Egocentric Streaming Object Memory](https://arxiv.org/abs/2411.16934) - Zaira Manigrasso, Matteo Dunnhofer, Antonino Furnari, Moritz Nottebaum, Antonio Finocchiaro, Davide Marana, Rosario Forte, Giovanni Maria Farinella, and Christian Micheloni. In WACV 2026.

- [Spherical World-Locking for Audio-Visual Localization in Egocentric Videos](https://arxiv.org/abs/2408.05364) - Heeseung Yun, Ruohan Gao, Ishwarya Ananthabhotla, Anurag Kumar, Jacob Donley, Chao Li, Gunhee Kim, Vamsi Krishna Ithapu, and Calvin Murdock. In ECCV 2024. [[project page]](https://hs-yn.github.io/SWL/)

- [EgoLoc: Revisiting 3D Object Localization from Egocentric Videos with Visual Queries](https://openaccess.thecvf.com/content/ICCV2023/papers/Mai_EgoLoc_Revisiting_3D_Object_Localization_from_Egocentric_Videos_with_Visual_ICCV_2023_paper.pdf) - Jinjie Mai, Abdullah Hamdi, Silvio Giancola, Chen Zhao, and Bernard Ghanem. In ICCV 2023. [[code]](https://github.com/Wayne-Mai/EgoLoc)

- [Hand-Priming in Object Localization for Assistive Egocentric Vision](https://openaccess.thecvf.com/content_WACV_2020/papers/Lee_Hand-Priming_in_Object_Localization_for_Assistive_Egocentric_Vision_WACV_2020_paper.pdf) - Kyungjun Lee, Abhinav Shrivastava, and Hernisa Kacorri. In WACV 2020.

- [Egocentric Shopping Cart Localization](https://web.archive.org/web/20240411164853/https://iplab.dmi.unict.it/EgocentricShoppingCartLocalization/home/_paper/egocentric%20shopping%20cart%20localization.pdf) - Emiliano Spera, Antonino Furnari, Sebastiano Battiato, and Giovanni Maria Farinella. In ICPR 2018.

- [Recognizing personal locations from egocentric videos](https://ieeexplore.ieee.org/document/7588113) - Antonino Furnari, Giovanni Maria Farinella, and Sebastiano Battiato. In IEEE Transactions on Human-Machine Systems 2017.

- [Personal-Location-Based Temporal Segmentation of Egocentric Video for Lifelogging Applications](https://web.archive.org/web/20240420050859/https://iplab.dmi.unict.it/PersonalLocationSegmentation/downloads/furnari2018personal.pdf) - Antonino Furnari, Sebastiano Battiato, and Giovanni Maria Farinella. In Journal of Visual Communication and Image Representation 2017. [[demo]](https://youtu.be/URM0EdYuKEw) [[project page]](https://web.archive.org/web/20251111135710/https://iplab.dmi.unict.it/EgocentricShoppingCartLocalization/)

- [Egocentric Future Localization](https://openaccess.thecvf.com/content_cvpr_2016/papers/Park_Egocentric_Future_Localization_CVPR_2016_paper.pdf) - Hyun Soo Park, Jyh-Jing Hwang, Yedong Niu, and Jianbo Shi. In CVPR 2016. [[demo]](https://youtu.be/i_9CTMZ60zc)

- [Real-time localization and mapping with wearable active vision](https://ieeexplore.ieee.org/document/1240684) - A.J. Davison, W.W. Mayol, and D.W. Murray. In The Second IEEE and ACM International Symposium 2003.

</details>

### Clustering

<details>
<summary>Show papers (2)</summary>

- [Sr-clustering: Semantic regularized clustering for egocentric photo streams segmentation](https://arxiv.org/pdf/1512.07143) - Mariella Dimiccoli, Marc Bolanosa, Estefania Talavera Maedeh Aghaei, Stavri G. Nikolov, and Petia Radeva. In Computer Vision and Image Understanding 2017.

- [Summarization and Classification of Wearable Camera Streams by Learning the Distributions over Deep Features of Out-of-Sample Image Sequences](https://openaccess.thecvf.com/content_ICCV_2017/papers/Perina_Summarization_and_Classification_ICCV_2017_paper.pdf) - Alessandro Perina, Sadegh Mohammadi, Nebojsa Jojic, and Vittorio Murino. In ICCV 2017.

</details>

### Video Summarization

<details>
<summary>Show papers (4)</summary>

- [Query-focused video summarization: Dataset, evaluation, and a memory network based approach](https://openaccess.thecvf.com/content_cvpr_2017/papers/Sharghi_Query-Focused_Video_Summarization_CVPR_2017_paper.pdf) - Aidean Sharghi, Jacob S. Laurel and Boqing Gong. In CVPR 2017.

- [Toward storytelling from visual lifelogging: An overview](https://arxiv.org/pdf/1507.06120.pdf) - Marc Bolanos, Mariella Dimiccoli, and Petia Radeva. In IEEE Transactions on Human-Machine Systems 2017.

- [Story-Driven Summarization for Egocentric Video](https://www.cs.utexas.edu/~grauman/papers/lu-grauman-cvpr2013.pdf) - Zheng Lu and Kristen Grauman. In CVPR 2013 [[project page]](http://vision.cs.utexas.edu/projects/egocentric/storydriven.html)

- [Discovering Important People and Objects for Egocentric Video Summarization](http://vision.cs.utexas.edu/projects/egocentric/egocentric_cvpr2012.pdf) - Yong Jae Lee, Joydeep Ghosh, and Kristen Grauman. In CVPR 2012. [[project page]](http://vision.cs.utexas.edu/projects/egocentric/index.html)

</details>

### Social Interactions

<details>
<summary>Show papers (6)</summary>

- [Seeing Conversations: Communication Context Identification in Egocentric Video](https://openaccess.thecvf.com/content/CVPR2026/html/Dorszewski_Seeing_Conversations_Communication_Context_Identification_in_Egocentric_Video_CVPR_2026_paper.html) - Tobias Dorszewski and Jens Hjortkjær. In CVPR 2026.

- [Ex2Eg-MAE: A Framework for Adaptation of Exocentric Video Masked Autoencoders for Egocentric Social Role Understanding](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10301.pdf) - Minh Tran, Yelin Kim, Che-Chun Su, Cheng-Hao Kuo, Min Sun, and Mohammad Soleymani. In ECCV 2024.

- [The Audio-Visual Conversational Graph: From an Egocentric-Exocentric Perspective](https://arxiv.org/abs/2312.12870) - Wenqi Jia, Miao Liu, Hao Jiang, Ishwarya Ananthabhotla, James M. Rehg, Vamsi Krishna Ithapu, and Ruohan Gao. In CVPR 2024. [[project page]](https://vjwq.github.io/AV-CONV/)

- [EgoCom: A Multi-person Multi-modal Egocentric Communications Dataset](https://ieeexplore.ieee.org/document/9200754) - Curtis G. Northcutt, Shengxin Zha, Steven Lovegrove, and Richard Newcombe. In PAMI 2020.

- [Deep Dual Relation Modeling for Egocentric Interaction Recognition](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Deep_Dual_Relation_Modeling_for_Egocentric_Interaction_Recognition_CVPR_2019_paper.pdf) - Haoxin Li, Yijun Cai, and Wei-Shi Zheng. In CVPR 2019.

- [Recognizing Micro-Actions and Reactions from Paired Egocentric Videos](https://openaccess.thecvf.com/content_cvpr_2016/papers/Yonetani_Recognizing_Micro-Actions_and_CVPR_2016_paper.pdf) - Ryo Yonetani, Kris M. Kitani, and Yoichi Sato. In CVPR 2016.

</details>

### Pose Estimation

<details>
<summary>Show papers (50)</summary>

- [EgoHumans: An Egocentric 3D Multi-Human Benchmark](https://arxiv.org/abs/2305.16487) - Rawal Khirodkar, Aayush Bansal, Lingni Ma, Richard Newcombe, Minh Vo, and Kris Kitani. In ICCV 2023 (Oral). [[code]](https://github.com/rawalkhirodkar/egohumans)

- [Towards in-the-wild Egocentric 3D Hand-Object Pose Estimation](https://arxiv.org/abs/2606.30598) - Siddhant Bansal, Zhifan Zhu, Shashank Tripathi, Jiahe Zhao, Michael J. Black, and Dima Damen. In ECCV 2026. [[project page]](https://sid2697.github.io/epic-contact/) [[code]](https://github.com/Sid2697/HOPformer)

- [E-3DPSM: A State Machine for Event-Based Egocentric 3D Human Pose Estimation](https://arxiv.org/abs/2604.08543) - Mayur Deshmukh, Hiroyasu Akada, Helge Rhodin, Christian Theobalt, and Vladislav Golyanik. In CVPR 2026. [[project page]](https://4dqv.mpi-inf.mpg.de/E-3DPSM/)

- [Egocentric Visibility-Aware Human Pose Estimation](https://arxiv.org/abs/2602.23618) - Peng Dai, Yu Zhang, Yiqiang Feng, Zhen Fan, and Yang Zhang. In CVPR 2026.

- [EgoPoseFormer v2: Accurate Egocentric Human Motion Estimation for AR/VR](https://arxiv.org/abs/2603.04090) - Zhenyu Li, Sai Kumar Dwivedi, Filip Maric, Carlos Chacon, Nadine Bertsch, Filippo Arcadu, et al. In CVPR 2026. [[project page]](https://zhyever.github.io/EgoPoseFormerv2/)

- [Towards Egocentric 3D Hand Pose Estimation in Unseen Domains](https://arxiv.org/abs/2601.06537) - Wiktor Mucha, Michael Wray, and Martin Kampel. In WACV 2026.

- [UniEgoMotion: A Unified Model for Egocentric Motion Reconstruction, Forecasting, and Generation](https://arxiv.org/abs/2508.01126) - Chaitanya Patel, Hiroki Nakamura, Yuta Kyuragi, Kazuki Kozuka, Juan Carlos Niebles, and Ehsan Adeli. In ICCV 2025. [[project page]](https://chaitanya100100.github.io/UniEgoMotion/) [[code]](https://github.com/chaitanya100100/UniEgoMotion)

- [Head2Body: Body Pose Generation from Multi-sensory Head-mounted Inputs](https://openaccess.thecvf.com/content/ICCV2025/papers/Tran_Head2Body_Body_Pose_Generation_from_Multi-sensory_Head-mounted_Inputs_ICCV_2025_paper.pdf) - Minh Tran, Hongda Mao, Qingshuang Chen, and Yelin Kim. In ICCV 2025.

- [Bring Your Rear Cameras for Egocentric 3D Human Pose Estimation](https://arxiv.org/abs/2503.11652) - Hiroyasu Akada, Jian Wang, Vladislav Golyanik, and Christian Theobalt. In ICCV 2025. [[project page]](https://4dqv.mpi-inf.mpg.de/EgoRear/)

- [Fish2Mesh Transformer: 3D Human Mesh Recovery from Egocentric Vision](https://arxiv.org/abs/2503.06089) - Tianma Shen, Aditya Puranik, James Vong, Vrushabh Abhijit Deogirikar, Ryan Fell, Julianna Dietrich, Maria Kyrarini, Christopher Kitts, and David C. Jeong. In ICCV 2025. [[project page]](https://fish2mesh.github.io/)

- [EgoMusic-driven Human Dance Motion Estimation with Skeleton Mamba](https://arxiv.org/abs/2508.10522) - Quang Nguyen, Nhat Le, Baoru Huang, Minh Nhat Vu, Chengcheng Tang, Van Nguyen, Ngan Le, Thieu Vo, and Anh Nguyen. In ICCV 2025.

- [REWIND: Real-Time Egocentric Whole-Body Motion Diffusion with Exemplar-Based Identity Conditioning](https://arxiv.org/abs/2504.04956) - Jihyun Lee, Weipeng Xu, Alexander Richard, Shih-En Wei, Shunsuke Saito, Shaojie Bai, Te-Li Wang, Minhyuk Sung, Tae-Kyun Kim, and Jason Saragih. In CVPR 2025. [[project page]](https://jyunlee.github.io/projects/rewind/)

- [FRAME: Floor-aligned Representation for Avatar Motion from Egocentric Video](https://arxiv.org/abs/2503.23094) - Andrea Boscolo Camiletto, Jian Wang, Eduardo Alvarado, Rishabh Dabral, Thabo Beeler, Marc Habermann, and Christian Theobalt. In CVPR 2025. [[project page]](https://vcai.mpi-inf.mpg.de/projects/FRAME/) [[code]](https://github.com/abcamiletto/frame)

- [EgoLM: Multi-Modal Language Model of Egocentric Motions](https://arxiv.org/abs/2409.18127) - Fangzhou Hong, Vladimir Guzov, Hyo Jin Kim, Yuting Ye, Richard Newcombe, Ziwei Liu, and Lingni Ma. In CVPR 2025. [[project page]](https://hongfz16.github.io/projects/EgoLM)

- [Estimating Body and Hand Motion in an Ego-sensed World](https://arxiv.org/abs/2410.03665) - Brent Yi, Vickie Ye, Maya Zheng, Yunqi Li, Lea Müller, Georgios Pavlakos, Yi Ma, Jitendra Malik, and Angjoo Kanazawa. In CVPR 2025. [[project page]](https://egoallo.github.io/)

- [Dyn-HaMR: Recovering 4D Interacting Hand Motion from a Dynamic Camera](https://arxiv.org/abs/2412.12861) - Zhengdi Yu, Stefanos Zafeiriou, and Tolga Birdal. In CVPR 2025. [[project page]](https://dyn-hamr.github.io/)

- [EgoPressure: A Dataset for Hand Pressure and Pose Estimation in Egocentric Vision](https://arxiv.org/abs/2409.02224) - Yiming Zhao, Taein Kwon, Paul Streli, Marc Pollefeys, and Christian Holz. In CVPR 2025. [[project page]](https://yiming-zhao.github.io/EgoPressure/)

- [Ego4o: Egocentric Human Motion Capture and Understanding from Multi-Modal Input](https://arxiv.org/abs/2504.08449) - Jian Wang, Rishabh Dabral, Diogo Luvizon, Zhe Cao, Lingjie Liu, Thabo Beeler, and Christian Theobalt. In CVPR 2025. [[project page]](https://jianwang-mpi.github.io/ego4o/)

- [EgoCast: Forecasting Egocentric Human Pose in the Wild](https://arxiv.org/abs/2412.02903) - Maria Escobar, Juanita Puentes, Cristhian Forigua, Jordi Pont-Tuset, Kevis-Kokitsi Maninis, and Pablo Arbelaez. In WACV 2025. [[code]](https://github.com/BCV-Uniandes/EgoCast)

- [Social EgoMesh Estimation](https://arxiv.org/abs/2411.04598) - Luca Scofano, Alessio Sampieri, Edoardo De Matteis, Indro Spinelli, and Fabio Galasso. In WACV 2025. [[code]](https://github.com/L-Scofano/SEEME)

- [Estimating Ego-Body Pose from Doubly Sparse Egocentric Video Data](https://arxiv.org/abs/2411.03561) - Seunggeun Chi, Pin-Hao Huang, Enna Sachdeva, Hengbo Ma, Karthik Ramani, and Kwonjoon Lee. In NeurIPS 2024. [[project page]](https://sgchi.github.io/dsposer/)

- [EgoSim: An Egocentric Multi-view Simulator and Real Dataset for Body-worn Cameras during Motion and Activity](https://openreview.net/forum?id=eOszT2lepG) - Dominik Hollidt, Paul Streli, Jiaxi Jiang, Yasaman Haghighi, Changlin Qian, Xintong Liu, and Christian Holz. In NeurIPS 2024. [[project page]](https://siplab.org/projects/EgoSim)

- [Nymeria: A Massive Collection of Egocentric Multi-modal Human Motion in the Wild](https://arxiv.org/abs/2406.09905) - Lingni Ma, Yuting Ye, Fangzhou Hong, Vladimir Guzov, Yifeng Jiang, et al. In ECCV 2024. [[project page]](https://www.projectaria.com/datasets/nymeria/)

- [EgoPoseFormer: A Simple Baseline for Stereo Egocentric 3D Human Pose Estimation](https://arxiv.org/abs/2403.18080) - Chenhongyi Yang, Anastasia Tkach, Shreyas Hampali, Linguang Zhang, Elliot J. Crowley, and Cem Keskin. In ECCV 2024. [[code]](https://github.com/ChenhongyiYang/egoposeformer)

- [EgoPoser: Robust Real-Time Egocentric Pose Estimation from Sparse and Intermittent Observations Everywhere](https://arxiv.org/abs/2308.06493) - Jiaxi Jiang, Paul Streli, Manuel Meier, and Christian Holz. In ECCV 2024. [[project page]](https://siplab.org/projects/EgoPoser)

- [3D Hand Pose Estimation in Everyday Egocentric Images](https://arxiv.org/abs/2312.06583) - Aditya Prakash, Ruisen Tu, Matthew Chang, and Saurabh Gupta. In ECCV 2024. [[project page]](https://ap229997.github.io/projects/hands/)

- [EgoBody3M: Egocentric Body Tracking on a VR Headset using a Diverse Dataset](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10261.pdf) - Amy Zhao, Chengcheng Tang, Lezi Wang, Yijing Li, Mihika Dave, Lingling Tao, Christopher D. Twigg, and Robert Y. Wang. In ECCV 2024. [[dataset]](https://github.com/facebookresearch/EgoBody3M)

- [Benchmarks and Challenges in Pose Estimation for Egocentric Hand Interactions with Objects](https://arxiv.org/abs/2403.16428) - Zicong Fan, Takehiko Ohkawa, Linlin Yang, Nie Lin, Zhishan Zhou, Shihao Zhou, et al. In ECCV 2024.

- [EventEgo3D: 3D Human Motion Capture from Egocentric Event Streams](https://arxiv.org/abs/2404.08640) - Christen Millerdurai, Hiroyasu Akada, Jian Wang, Diogo Luvizon, Christian Theobalt, and Vladislav Golyanik. In CVPR 2024. [[project page]](https://4dqv.mpi-inf.mpg.de/EventEgo3D/)

- [3D Human Pose Perception from Egocentric Stereo Videos](https://arxiv.org/abs/2401.00889) - Hiroyasu Akada, Jian Wang, Vladislav Golyanik, and Christian Theobalt. In CVPR 2024. [[code]](https://github.com/hiroyasuakada/3D-Human-Pose-Perception-from-Egocentric-Stereo-Videos)

- [Egocentric Whole-Body Motion Capture with FisheyeViT and Diffusion-Based Motion Refinement](https://arxiv.org/abs/2311.16495) - Jian Wang, Zhe Cao, Diogo Luvizon, Lingjie Liu, Kripasindhu Sarkar, Danhang Tang, Thabo Beeler, and Christian Theobalt. In CVPR 2024. [[code]](https://github.com/jianwang-mpi/egowholemocap)

- [Attention-Propagation Network for Egocentric Heatmap to 3D Pose Lifting](https://arxiv.org/abs/2402.18330) - Taeho Kang and Youngki Lee. In CVPR 2024. [[code]](https://github.com/tho-kn/EgoTAP)

- [Single-to-Dual-View Adaptation for Egocentric 3D Hand Pose Estimation](https://arxiv.org/abs/2403.04381) - Ruicong Liu, Takehiko Ohkawa, Mingfang Zhang, and Yoichi Sato. In CVPR 2024. [[code]](https://github.com/ut-vision/S2DHand)

- [Real-Time Simulated Avatar from Head-Mounted Sensors](https://arxiv.org/abs/2403.06862) - Zhengyi Luo, Jinkun Cao, Rawal Khirodkar, Alexander Winkler, Jing Huang, Kris Kitani, and Weipeng Xu. In CVPR 2024. [[project page]](https://www.zhengyiluo.com/SimXR/)

- [Mocap Everyone Everywhere: Lightweight Motion Capture With Smartwatches and a Head-Mounted Camera](https://arxiv.org/abs/2401.00847) - Jiye Lee and Hanbyul Joo. In CVPR 2024. [[project page]](https://jiyewise.github.io/projects/MocapEvery/)

- [Spectral Graphormer: Spectral Graph-Based Transformer for Egocentric Two-Hand Reconstruction using Multi-View Color Images](https://openaccess.thecvf.com/content/ICCV2023/papers/Tse_Spectral_Graphormer_Spectral_Graph-Based_Transformer_for_Egocentric_Two-Hand_Reconstruction_using_ICCV_2023_paper.pdf) - Tze Ho Elden Tse, Franziska Mueller, Zhengyang Shen, Danhang Tang, Thabo Beeler, Mingsong Dou, Yinda Zhang, Sasa Petrovic, Hyung Jin Chang, Jonathan Taylor, and Bardia Doosti. In ICCV 2023. [[project page]](https://eldentse.github.io/Spectral-Graphormer/)

- [Probabilistic Human Mesh Recovery in 3D Scenes from Egocentric Views](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_Probabilistic_Human_Mesh_Recovery_in_3D_Scenes_from_Egocentric_Views_ICCV_2023_paper.pdf) - Siwei Zhang, Qianli Ma, Yan Zhang, Sadegh Aliakbarian, Darren Cosker, and Siyu Tang. In ICCV 2023. [[project page]](https://sanweiliti.github.io/egohmr/egohmr.html) [[code]](https://github.com/sanweiliti/EgoHMR) 

- [AssemblyHands: Towards Egocentric Activity Understanding via 3D Hand Pose Estimation](https://assemblyhands.github.io) - Takehiko Ohkawa, Kun He, Fadime Sener, Tomas Hodan, LUAN TRAN, Cem Keskin. In CVPR 2023.

- [Scene-aware Egocentric 3D Human Pose Estimation](https://arxiv.org/pdf/2212.11684.pdf) - Jian Wang, Diogo Luvizon, Weipeng Xu, Lingjie Liu, Kripasindhu Sarkar, Christian Theobalt. In CVPR 2023.

- [Ego-Body Pose Estimation via Ego-Head Pose Estimation](https://arxiv.org/pdf/2212.04636.pdf) - Jiaman Li · Karen Liu · Jiajun Wu. In CVPR 2023.

- [EgoBody: Human Body Shape and Motion of Interacting People from Head-Mounted Devices](https://arxiv.org/pdf/2112.07642.pdf) - Siwei Zhang, Qianli Ma, Yan Zhang, Zhiyin Qian, Taein Kwon, Marc Pollefeys, Federica Bogo, Siyu Tang. In ECCV 2022. [[project page]](https://sanweiliti.github.io/egobody/egobody.html) [[dataset]](https://egobody.inf.ethz.ch/) [[code]](https://github.com/sanweiliti/EgoBody)

- [UnrealEgo: A New Dataset for Robust Egocentric 3D Human Motion Capture](https://arxiv.org/abs/2208.01633) - Hiroyasu Akada, Jian Wang, Soshi Shimada, Masaki Takahashi, Christian Theobalt, Vladislav Golyanik. In ECCV 2022. [[project page]](https://4dqv.mpi-inf.mpg.de/UnrealEgo/) [[code]](https://github.com/hiroyasuakada/UnrealEgo) [[dataset]](https://4dqv.mpi-inf.mpg.de/UnrealEgo/) [[demo]](https://4dqv.mpi-inf.mpg.de/UnrealEgo/data/unrealego_distribution.mp4)

- [Estimating Egocentric 3D Human Pose in the Wild with External Weak Supervision](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Estimating_Egocentric_3D_Human_Pose_in_the_Wild_With_External_CVPR_2022_paper.pdf) - Jian Wang, Lingjie Liu, Weipeng Xu, Kripasindhu Sarkar, Diogo Luvizon, Christian Theobalt. In CVPR 2022. [[project page]](https://web.archive.org/web/20240726094113/https://people.mpi-inf.mpg.de/~jianwang/projects/egopw/)

- [Estimating Egocentric 3D Human Pose in Global Space](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Estimating_Egocentric_3D_Human_Pose_in_Global_Space_ICCV_2021_paper.pdf) - Jian Wang, Lingjie Liu, Weipeng Xu, Kripasindhu Sarkar, Christian Theobalt. In ICCV 2021. [[project page]](https://web.archive.org/web/20240423122243/https://people.mpi-inf.mpg.de/~jianwang/projects/globalegomocap/)

- [Automatic Calibration of the Fisheye Camera for Egocentric 3D Human Pose Estimation From a Single Image](https://openaccess.thecvf.com/content/WACV2021/html/Zhang_Automatic_Calibration_of_the_Fisheye_Camera_for_Egocentric_3D_Human_WACV_2021_paper.html) - Yahui Zhang, Shaodi You, and Theo Gevers. In WACV 2021.

- [You2Me: Inferring Body Pose in Egocentric Video via First and Second Person Interactions](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ng_You2Me_Inferring_Body_Pose_in_Egocentric_Video_via_First_and_CVPR_2020_paper.pdf) - Evonne Ng, Donglai Xiang, Hanbyul Joo, and Kristen Grauman. In CVPR 2020. [[demo]](http://vision.cs.utexas.edu/projects/you2me/demo.mp4) [[project page]](http://vision.cs.utexas.edu/projects/you2me/) [[dataset]](https://github.com/facebookresearch/you2me/tree/master/data#) [[code]](https://github.com/facebookresearch/you2me#)

- [Ego-Pose Estimation and Forecasting as Real-Time PD Control](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yuan_Ego-Pose_Estimation_and_Forecasting_As_Real-Time_PD_Control_ICCV_2019_paper.pdf) - Ye Yuan and Kris Kitani. In ICCV 2019. [[code]](https://github.com/Khrylx/EgoPose) [[project page]](https://www.ye-yuan.com/ego-pose) [[demo]](https://youtu.be/968IIDZeWE0)

- [xR-EgoPose: Egocentric 3D Human Pose From an HMD Camera](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tome_xR-EgoPose_Egocentric_3D_Human_Pose_From_an_HMD_Camera_ICCV_2019_paper.pdf) - Denis Tome, Patrick Peluse, Lourdes Agapito, and Hernan Badino. In ICCV 2019. [[demo]](https://youtu.be/zem03fZWLrQ) [[dataset]](https://github.com/facebookresearch/xR-EgoPose)

- [Seeing Invisible Poses: Estimating 3D Body Pose from Egocentric Video](https://openaccess.thecvf.com/content_cvpr_2017/papers/Jiang_Seeing_Invisible_Poses_CVPR_2017_paper.pdf) - Hao Jiang and Kristen Grauman. In CVPR 2017.

- [First-Person Pose Recognition using Egocentric Workspaces](https://openaccess.thecvf.com/content_cvpr_2015/papers/Rogez_First-Person_Pose_Recognition_2015_CVPR_paper.pdf) - Gregory Rogez, James S. Supancic, and Deva Ramanan. In CVPR 2015.

</details>

### Human Object Interaction

<details>
<summary>Show papers (20)</summary>

- [MEgoHand: Multimodal Egocentric Hand-Object Interaction Motion Generation](https://arxiv.org/abs/2505.16602) - Bohan Zhou, Yi Zhan, Zhongbin Zhang, and Zongqing Lu. In NeurIPS 2025. [[project page]](https://beingbeyond.github.io/MEgoHand/) [[code]](https://github.com/BeingBeyond/MEgoHand)

- [Perceiving and Acting in First-Person: A Dataset and Benchmark for Egocentric Human-Object-Human Interactions](https://arxiv.org/abs/2508.04681) - Liang Xu, Chengqun Yang, Zili Lin, Fei Xu, Yifan Liu, Congsheng Xu, et al. In ICCV 2025. [[project page]](https://liangxuy.github.io/InterVLA/)

- [Learning Precise Affordances from Egocentric Videos for Robotic Manipulation](https://arxiv.org/abs/2408.10123) - Gen Li, Nikolaos Tsagkas, Jifei Song, Ruaridh Mon-Williams, Sethu Vijayakumar, Kun Shao, and Laura Sevilla-Lara. In ICCV 2025. [[project page]](https://reagan1311.github.io/affgrasp)

- [ForeHOI: Feed-forward 3D Object Reconstruction from Daily Hand-Object Interaction Videos](https://arxiv.org/abs/2602.06226) - Yuantao Chen, Jiahao Chang, Chongjie Ye, Chaoran Zhang, Zhaojie Fang, Chenghong Li, and Xiaoguang Han. In CVPR 2026. [[project page]](https://tao-11-chen.github.io/project_pages/ForeHOI/) [[code]](https://github.com/Tao-11-chen/ForeHOI)

- [EgoFlow: Gradient-Guided Flow Matching for Egocentric 6DoF Object Motion Generation](https://arxiv.org/abs/2604.01421) - Abhishek Saroha, Huajian Zeng, Xingxing Zuo, Daniel Cremers, and Xi Wang. In CVPR 2026. [[project page]](https://abhi-rf.github.io/egoflow/) [[code]](https://github.com/abhi-rf/egoflow)

- [ParaHome: Parameterizing Everyday Home Activities Towards 3D Generative Modeling of Human-Object Interactions](https://arxiv.org/abs/2401.10232) - Jeonghwan Kim, Jisoo Kim, Jeonghyeon Na, and Hanbyul Joo. In CVPR 2025. [[code]](https://github.com/canoneod/ParaHome)

- [Generating 6DoF Object Manipulation Trajectories from Action Description in Egocentric Vision](https://arxiv.org/abs/2506.03605) - Tomoya Yoshida, Shuhei Kurita, Taichi Nishimura, and Shinsuke Mori. In CVPR 2025. [[project page]](https://biscue5.github.io/egoscaler-project-page/) [[code]](https://github.com/Biscue5/EgoScaler)

- [ANNEXE: Unified Analyzing, Answering, and Pixel Grounding for Egocentric Interaction](https://arxiv.org/abs/2504.01472) - Yuejiao Su, Yi Wang, Qiongyang Hu, Chuang Yang, and Lap-Pui Chau. In CVPR 2025. [[project page]](https://yuggiehk.github.io/annexe/)

- [EgoChoir: Capturing 3D Human-Object Interaction Regions from Egocentric Views](https://arxiv.org/abs/2405.13659) - Yuhang Yang, Wei Zhai, Chengfeng Wang, Chengjun Yu, Yang Cao, and Zheng-Jun Zha. In NeurIPS 2024. [[project page]](https://yyvhang.github.io/EgoChoir/) [[code]](https://github.com/yyvhang/EgoChoir_release)

- [Are Synthetic Data Useful for Egocentric Hand-Object Interaction Detection?](https://arxiv.org/abs/2312.02672) - Rosario Leonardi, Antonino Furnari, Francesco Ragusa, and Giovanni Maria Farinella. In ECCV 2024. [[project page]](https://fpv-iplab.github.io/HOI-Synth/) [[code]](https://github.com/fpv-iplab/HOI-Synth)

- [Fine-grained Affordance Annotation for Egocentric Hand-Object Interaction Videos](https://openaccess.thecvf.com/content/WACV2023/papers/Yu_Fine-Grained_Affordance_Annotation_for_Egocentric_Hand-Object_Interaction_Videos_WACV_2023_paper.pdf) - Zecheng Yu, Yifei Huang, Ryosuke Furuta, Takuma Yagi, Yusuke Goutsu, and Yoichi Sato. In WACV 2023.

- [EgoPCA: A New Framework for Egocentric Hand-Object Interaction Understanding](https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_EgoPCA_A_New_Framework_for_Egocentric_Hand-Object_Interaction_Understanding_ICCV_2023_paper.pdf) - Yue Xu, Yong-Lu Li, Zhemin Huang, Michael Xu Liu, Cewu Lu, Yu-Wing Tai, and Chi-Keung Tang. In ICCV 2023. [[project page]](https://mvig-rhos.com/ego_pca)

- [ARCTIC: A Dataset for Dexterous Bimanual Hand-Object Manipulation](https://arctic.is.tue.mpg.de) - Zicong Fan, Omid Taheri, Dimitrios Tzionas, Muhammed Kocabas, Manuel Kaufmann, Michael J. Black, Otmar Hilliges. In CVPR 2023. [[code]](https://github.com/zc-alexfan/arctic)

- [Fine-Grained Egocentric Hand-Object Segmentation: Dataset, Model, and Applications](https://arxiv.org/pdf/2208.03826.pdf) - Lingzhi Zhang, Shenghao Zhou, Simon Stent, Jianbo Shi. In ECCV 2022. [[project page]](https://web.archive.org/web/20230422000343/https://www.seas.upenn.edu/~shzhou2/projects/eos_dataset/) [[code]](https://github.com/owenzlz/EgoHOS) [[dataset]](https://github.com/owenzlz/EgoHOS)

- [HOI4D: A 4D Egocentric Dataset for Category-Level Human-Object Interaction](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_HOI4D_A_4D_Egocentric_Dataset_for_Category-Level_Human-Object_Interaction_CVPR_2022_paper.pdf) - Yunze Liu, Yun Liu, Che Jiang, Kangbo Lyu, Weikang Wan, Hao Shen, Boqiang Liang, Zhoujie Fu, He Wang, Li Yi. In CVPR 2022. [[project page]](https://hoi4d.github.io/) [[video]](https://youtu.be/yzNqm0JISU0)

- [Hand-Object Contact Prediction via Motion-Based Pseudo-Labeling and Guided Progressive Label Correction](https://www.bmvc2021-virtualconference.com/assets/papers/0096.pdf) - Takuma Yagi, Md Tasnimul Hasan, and Yoichi Sato. In BMVC 2021. [[project page]](https://www.bmvc2021-virtualconference.com/conference/papers/paper_0096.html) [[code]](https://github.com/takumayagi/hand_object_contact_prediction/)

- [The MECCANO Dataset: Understanding Human-Object Interactions from Egocentric Videos in an Industrial-like Domain](https://arxiv.org/abs/2010.05654) - Francesco Ragusa, Antonino Furnari, Salvatore Livatino, and Giovanni Maria Farinella. In WACV 2021. [[project page]](https://iplab.dmi.unict.it/MECCANO/)

- [Forecasting Human-Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf) - Miao Liu, Siyu Tang, Yin Li, and James M. Rehg. In ECCV 2020. [[project page]](https://aptx4869lm.github.io/ForecastingHOI/)

- [You-Do, I-Learn: Discovering Task Relevant Objects and their Modes of Interaction from Multi-User Egocentric Video](https://dimadamen.github.io/You-Do-I-Learn/Damen_BMVC2014.pdf) - Dima Damen, Tessid Leelasawassuk, Osian Haines, Andrew Calway,and Walterio Mayol-Cuevas. In BMVC 2014 [[project page]](http://www.bmva.org/bmvc/2014/papers/paper059/index.html)

- [Automated capture and delivery of assistive task guidance with an eyewear computer: the GlaciAR system](https://arxiv.org/pdf/1701.02586) -  Teesid Leelasawassuk, Dima Damen, and Walterio Mayol-Cuevas. In Augmented Human International Conference, ACM 2017.

</details>

### Temporal Boundary Detection

<details>
<summary>Show papers (4)</summary>

- [Streaming Detection of Queried Event Start](https://arxiv.org/abs/2412.03567) - Cristóbal Eyzaguirre, Eric Tang, Shyamal Buch, Adrien Gaidon, Jiajun Wu, and Juan Carlos Niebles. In NeurIPS 2024. [[project page]](https://sdqesdataset.github.io/)

- [Ego-Only: Egocentric Action Detection without Exocentric Transferring](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Ego-Only_Egocentric_Action_Detection_without_Exocentric_Transferring_ICCV_2023_paper.html) - Huiyu Wang, Mitesh Kumar Singh, and Lorenzo Torresani. In ICCV 2023. 

- [Trespassing the Boundaries: Labeling Temporal Bounds for Object Interactions in Egocentric Video](https://openaccess.thecvf.com/content_ICCV_2017/papers/Moltisanti_Trespassing_the_Boundaries_ICCV_2017_paper.pdf) - Davide Moltisanti, Michael Wray, Walterio Mayol-Cuevas, and Dima Damen. In ICCV 2017.

- [Temporal segmentation of egocentric videos](https://www.cse.iitd.ac.in/~chetan/papers/egocentric-cvpr14.pdf) -Yair Poleg, Chetan Arora, and Shmuel Peleg. In CVPR 2014.

</details>

### Privacy in Egocentric Videos

<details>
<summary>Show papers (4)</summary>

- [Is Sharing of Egocentric Video Giving Away Your Biometric Signature?](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620392.pdf) - Daksh Thapar, Chetan Arora, and Aditya Nigam. In ECCV 2020. [[project page]](https://egocentricbiometric.github.io)

- [Mitigating Bystander Privacy Concerns in Egocentric Activity Recognition with Deep Learning and Intentional Image Degradation](http://users.ece.utexas.edu/~ethomaz/papers/j2.pdf) - Mariella Dimiccoli, Juan Marin, and Edison Thomaz. In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 2018.

- [Privacy-Preserving Human Activity Recognition from Extreme Low Resolution](https://arxiv.org/pdf/1604.03196) - Michael S. Ryoo, Brandon Rothrock, Charles Fleming, and Hyun Jong Yang. In AAAI 2017.

- [Ego-Surfing First Person Videos](https://openaccess.thecvf.com/content_cvpr_2015/papers/Yonetani_Ego-Surfing_First-Person_Videos_2015_CVPR_paper.pdf) - Ryo Yonetani, Kris M. Kitani, and Yoichi Sato. In CVPR 2015.

</details>

### Multiple Egocentric Tasks

<details>
<summary>Show papers (12)</summary>

- [EPFL-Smart-Kitchen: An Ego-Exo Multi-Modal Dataset for Challenging Action and Motion Understanding in Video-Language Models](https://arxiv.org/abs/2506.01608) - Andy Bonnetto, Haozhe Qi, Franklin Leong, Matea Tashkovska, Mahdi Rad, Solaiman Shokur, Friedhelm Hummel, Silvestro Micera, Marc Pollefeys, and Alexander Mathis. In NeurIPS 2025. [[project page]](https://amathislab.github.io/EPFL-Smart-Kitchen/pages/esk.html) [[code]](https://github.com/amathislab/EPFL-Smart-Kitchen)

- [EgoAdapt: Adaptive Multisensory Distillation and Policy Learning for Efficient Egocentric Perception](https://arxiv.org/abs/2506.21080) - Sanjoy Chowdhury, Subrata Biswas, Sayan Nag, Tushar Nagarajan, Calvin Murdock, Ishwarya Ananthabhotla, Yijun Qian, Vamsi Krishna Ithapu, Dinesh Manocha, and Ruohan Gao. In ICCV 2025. [[project page]](https://schowdhury671.github.io/egoadapt_project/)

- [EgoM2P: Egocentric Multimodal Multitask Pretraining](https://arxiv.org/abs/2506.07886) - Gen Li, Yutong Chen, Yiqian Wu, Kaifeng Zhao, Marc Pollefeys, and Siyu Tang. In ICCV 2025. [[project page]](https://egom2p.github.io/)

- [HD-EPIC: A Highly-Detailed Egocentric Video Dataset](https://arxiv.org/abs/2502.04144) - Toby Perrett, Ahmad Darkhalil, Saptarshi Sinha, Omar Emara, Sam Pollard, Kranti Parida, et al. In CVPR 2025. [[project page]](https://hd-epic.github.io/)

- [Ego-VPA: Egocentric Video Understanding with Parameter-Efficient Adaptation](https://arxiv.org/abs/2407.19520) - Tz-Ying Wu, Kyle Min, Subarna Tripathi, and Nuno Vasconcelos. In WACV 2025. [[code]](https://github.com/gina9726/Ego-VPA)

- [A Backpack Full of Skills: Egocentric Video Understanding with Diverse Task Perspectives](https://arxiv.org/pdf/2403.03037) - Simone Alberto Peirone, Francesca Pistilli, Antonio Alliegro, and Giuseppe Averta. In CVPR 2024.

- [An Outlook into the Future of Egocentric Vision](https://arxiv.org/abs/2308.07123) - Chiara Plizzari, Gabriele Goletto, Antonino Furnari, Siddhant Bansal, Francesco Ragusa, Giovanni Maria Farinella, Dima Damen, and Tatiana Tommasi. In IJCV 2024. [[project page]](https://sid2697.github.io/futureofegovision/)

- [Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives](https://arxiv.org/abs/2311.18259) - Kristen Grauman, Andrew Westbury, Lorenzo Torresani, Kris Kitani, Jitendra Malik, Triantafyllos Afouras, Kumar Ashutosh, Vijay Baiyya, Siddhant Bansal, Bikram Boote, Eugene Byrne, Zach Chavis, Joya Chen, Feng Cheng, Fu-Jen Chu, Sean Crane, Avijit Dasgupta, Jing Dong, Maria Escobar, Cristhian Forigua, Abrham Gebreselasie, Sanjay Haresh, Jing Huang, Md Mohaiminul Islam, Suyog Jain, Rawal Khirodkar, Devansh Kukreja, Kevin J Liang, Jia-Wei Liu, Sagnik Majumder, Yongsen Mao, Miguel Martin, Effrosyni Mavroudi, Tushar Nagarajan, Francesco Ragusa, Santhosh Kumar Ramakrishnan, Luigi Seminara, Arjun Somayazulu, Yale Song, Shan Su, Zihui Xue, Edward Zhang, Jinxu Zhang, Angela Castillo, Changan Chen, Xinzhu Fu, Ryosuke Furuta, Cristina Gonzalez, Prince Gupta, Jiabo Hu, Yifei Huang, Yiming Huang, Weslie Khoo, Anush Kumar, Robert Kuo, Sach Lakhavani, Miao Liu, Mi Luo, Zhengyi Luo, Brighid Meredith, Austin Miller, Oluwatumininu Oguntola, Xiaqing Pan, Penny Peng, Shraman Pramanick, Merey Ramazanova, Fiona Ryan, Wei Shan, Kiran Somasundaram, Chenan Song, Audrey Southerland, Masatoshi Tateno, Huiyu Wang, Yuchen Wang, Takuma Yagi, Mingfei Yan, Xitong Yang, Zecheng Yu, Shengxin Cindy Zha, Chen Zhao, Ziwei Zhao, Zhifan Zhu, Jeff Zhuo, Pablo Arbelaez, Gedas Bertasius, David Crandall, Dima Damen, Jakob Engel, Giovanni Maria Farinella, Antonino Furnari, Bernard Ghanem, Judy Hoffman, C. V. Jawahar, Richard Newcombe, Hyun Soo Park, James M. Rehg, Yoichi Sato, Manolis Savva, Jianbo Shi, Mike Zheng Shou, and Michael Wray. In CVPR 2024. [[project page]](https://ego-exo4d-data.org)

- [EgoVLPv2: Egocentric Video-Language Pre-training with Fusion in the Backbone](https://arxiv.org/pdf/2307.05463.pdf) - Shraman Pramanick, Yale Song, Sayan Nag, Kevin Qinghong Lin, Hardik Shah, Mike Zheng Shou, Rama Chellappa, and Pengchuan Zhang. In ICCV 2023. [[project page]](https://shramanpramanick.github.io/EgoVLPv2/) [[code]](https://github.com/facebookresearch/EgoVLPv2/)

- [Egocentric Video-Language Pretraining](https://arxiv.org/pdf/2206.01670.pdf) - Kevin Qinghong Lin, Alex Jinpeng Wang, Mattia Soldan, Michael Wray, Rui Yan, Eric Zhongcong Xu, Difei Gao, Rongcheng Tu, Wenzhe Zhao, Weijie Kong, Chengfei Cai, Hongfa Wang, Dima Damen, Bernard Ghanem, Wei Liu and Mike Zheng Shou. In NeurIPS 2022. [[project page]](https://qinghonglin.github.io/EgoVLP/) [[code]](https://github.com/showlab/EgoVLP)

- [Ego4D: Around the World in 3,000 Hours of Egocentric Video](https://arxiv.org/abs/2110.07058) - Kristen Grauman, Andrew Westbury, Eugene Byrne, Zachary Chavis, Antonino Furnari, Rohit Girdhar, Jackson Hamburger, Hao Jiang, Miao Liu, Xingyu Liu, Miguel Martin, Tushar Nagarajan, Ilija Radosavovic, Santhosh Kumar Ramakrishnan, Fiona Ryan, Jayant Sharma, Michael Wray, Mengmeng Xu, Eric Zhongcong Xu, Chen Zhao, Siddhant Bansal, Dhruv Batra, Vincent Cartillier, Sean Crane, Tien Do, Morrie Doulaty, Akshay Erapalli, Christoph Feichtenhofer, Adriano Fragomeni, Qichen Fu, Christian Fuegen, Abrham Gebreselasie, Cristina Gonzalez, James Hillis, Xuhua Huang, Yifei Huang, Wenqi Jia, Weslie Khoo, Jachym Kolar, Satwik Kottur, Anurag Kumar, Federico Landini, Chao Li, Yanghao Li, Zhenqiang Li, Karttikeya Mangalam, Raghava Modhugu, Jonathan Munro, Tullie Murrell, Takumi Nishiyasu, Will Price, Paola Ruiz Puentes, Merey Ramazanova, Leda Sari, Kiran Somasundaram, Audrey Southerland, Yusuke Sugano, Ruijie Tao, Minh Vo, Yuchen Wang, Xindi Wu, Takuma Yagi, Yunyi Zhu, Pablo Arbelaez, David Crandall, Dima Damen, Giovanni Maria Farinella, Bernard Ghanem, Vamsi Krishna Ithapu, C.V. Jawahar, Hanbyul Joo, Kris Kitani, Haizhou Li, Richard Newcombe, Aude Oliva, Hyun Soo Park, James M. Rehg, Yoichi Sato, Jianbo Shi, Mike Zheng Shou, Antonio Torralba, Lorenzo Torresani, Mingfei Yan, and Jitendra Malik. In CVPR 2022. [[Github]](https://github.com/EGO4D) [[project page]](https://ego4d-data.org) [[video]](https://drive.google.com/file/d/1oknfQIH9w1rXy6I1j5eUE6Cqh96UwZ4L/view?usp=sharing)

- [Assembly101: A Large-Scale Multi-View Video Dataset for Understanding Procedural Activities](https://arxiv.org/abs/2203.14712) - Fadime Sener, Dibyadip Chatterjee, Daniel Shelepov, Kun He, Dipika Singhania, Robert Wang, and Angela Yao. In CVPR 2022. [[project page]](https://assembly-101.github.io/)

</details>

### Task Understanding

<details>
<summary>Show papers (12)</summary>

- [Mistake Attribution: Fine-Grained Mistake Understanding in Egocentric Videos](https://arxiv.org/abs/2511.20525) - Yayuan Li, Aadit Jain, Filippos Bellos, and Jason J. Corso. In CVPR 2026. [[project page]](https://yayuanli.github.io/MATT/)

- [EgoPlan-Bench2: A Benchmark for Multimodal Large Language Model Planning in Real-World Scenarios](https://arxiv.org/abs/2412.04447) - Lu Qiu, Yi Chen, Yuying Ge, Yixiao Ge, Ying Shan, and Xihui Liu. In IJCV 2026. [[project page]](https://qiulu66.github.io/egoplanbench2/)

- [EgoPlan-Bench: Benchmarking Multimodal Large Language Models for Human-Level Planning](https://arxiv.org/abs/2312.06722) - Yi Chen, Yuying Ge, Yixiao Ge, Mingyu Ding, Bohao Li, Rui Wang, Ruifeng Xu, Ying Shan, and Xihui Liu. In IJCV 2026. [[project page]](https://chenyi99.github.io/ego_plan/)

- [IndEgo: A Dataset of Industrial Scenarios and Collaborative Work for Egocentric Assistants](https://arxiv.org/abs/2511.19684) - Vivek Chavan, Yasmina Imgrund, Tung Dao, Sanwantri Bai, Bosong Wang, Ze Lu, Oliver Heimann, and Jörg Krüger. In NeurIPS 2025. [[project page]](https://indego-dataset.github.io/) [[code]](https://github.com/Vivek9Chavan/IndEgo/) [[dataset]](https://huggingface.co/datasets/FraunhoferIPK/IndEgo)

- [HiERO: Understanding the Hierarchy of Human Behavior Enhances Reasoning on Egocentric Videos](https://arxiv.org/abs/2505.12911) - Simone Alberto Peirone, Francesca Pistilli, and Giuseppe Averta. In ICCV 2025. [[project page]](https://sapeirone.github.io/HiERO/) [[code]](https://github.com/sapeirone/HiERO)

- [Gazing Into Missteps: Leveraging Eye-Gaze for Unsupervised Mistake Detection in Egocentric Videos of Skilled Human Activities](https://arxiv.org/abs/2406.08379) - Michele Mazzamuto, Antonino Furnari, Yoichi Sato, and Giovanni Maria Farinella. In CVPR 2025.

- [CaptainCook4D: A Dataset for Understanding Errors in Procedural Activities](https://arxiv.org/abs/2312.14556) - Rohith Peddi, Shivvrat Arya, Bharath Challa, Likhitha Pallapothula, Akshay Vyas, Bhavya Gouripeddi, et al. In NeurIPS 2024. [[project page]](https://captaincook4d.github.io/captain-cook/)

- [Differentiable Task Graph Learning: Procedural Activity Representation and Online Mistake Detection from Egocentric Videos](https://arxiv.org/abs/2406.01486) - Luigi Seminara, Giovanni Maria Farinella, and Antonino Furnari. In NeurIPS 2024. [[code]](https://github.com/fpv-iplab/Differentiable-Task-Graph-Learning)

- [Error Detection in Egocentric Procedural Task Videos](https://openaccess.thecvf.com/content/CVPR2024/html/Lee_Error_Detection_in_Egocentric_Procedural_Task_Videos_CVPR_2024_paper.html) - Shih-Po Lee, Zijia Lu, Zekun Zhang, Minh Hoai, and Ehsan Elhamifar. In CVPR 2024. [[project page]](https://www.khoury.northeastern.edu/home/eelhami/egoper.htm) [[code]](https://github.com/robert80203/EgoPER_official)

- [EgoTV: Egocentric Task Verification from Natural Language Task Descriptions](https://openaccess.thecvf.com/content/ICCV2023/papers/Hazra_EgoTV_Egocentric_Task_Verification_from_Natural_Language_Task_Descriptions_ICCV_2023_paper.pdf) - Rishi Hazra, Brian Chen, Akshara Rai, Nitin Kamra, and Ruta Desai. In ICCV 2023. [[project page]](https://ai.meta.com/datasets/egotv-egocentric-task-verification-dataset/) [[code]](https://github.com/facebookresearch/EgoTV)

- [My View is the Best View: Procedure Learning from Egocentric Videos](https://arxiv.org/pdf/2207.10883) - Siddhant Bansal, Chetan Arora, C.V. Jawahar. In ECCV 2022. [[project page]](https://sid2697.github.io/egoprocel/) [[dataset]](https://sid2697.github.io/egoprocel/#download) [[code]](https://github.com/Sid2697/EgoProceL-egocentric-procedure-learning)

- [AssistQ: Affordance-centric Question-driven Task Completion for Egocentric Assistant](https://arxiv.org/pdf/2203.04203.pdf) - Benita Wong, Joya Chen, You Wu, Stan Weixian Lei, Dongxing Mao, Difei Gao, Mike Zheng Shou. In ECCV 2022. [[project page]](https://showlab.github.io/assistq/) [[code]](https://github.com/showlab/Q2A)

</details>

### Ego-Exo Cross-View Learning

<details>
<summary>Show papers (19)</summary>

- [Exo2Ego: Exocentric Knowledge Guided MLLM for Egocentric Video Understanding](https://arxiv.org/abs/2503.09143) - Haoyu Zhang, Qiaohui Chu, Meng Liu, Haoxiang Shi, Yaowei Wang, and Liqiang Nie. In AAAI 2026. [[project page]](https://egovisiongroup.github.io/Exo2Ego.github.io/)

- [SAVA-X: Ego-to-Exo Imitation Error Detection via Scene-Adaptive View Alignment and Bidirectional Cross View Fusion](https://arxiv.org/abs/2603.12764) - Xiang Li, Heqian Qiu, Lanxiao Wang, Benliu Qiu, Fanman Meng, Linfeng Xu, and Hongliang Li. In CVPR 2026. [[code]](https://github.com/jack1ee/SAVAX)

- [RegionAligner: Bridging Ego-Exo Views for Object Correspondence via Unified Text-Visual Learning](https://openaccess.thecvf.com/content/WACV2026/html/Su_RegionAligner_Bridging_Ego-Exo_Views_for_Object_Correspondence_via_Unified_Text-Visual_WACV_2026_paper.html) - Yuhao Su and Ehsan Elhamifar. In WACV 2026.

- [EgoExOR: An Ego-Exo-Centric Operating Room Dataset for Surgical Activity Understanding](https://arxiv.org/abs/2505.24287) - Ege Özsoy, Arda Mamur, Felix Tristram, Chantal Pellegrini, Magdalena Wysocki, Benjamin Busam, and Nassir Navab. In NeurIPS 2025. [[code]](https://github.com/ardamamur/EgoExOR)

- [Robust Ego-Exo Correspondence with Long-Term Memory](https://arxiv.org/abs/2510.11417) - Yijun Hu, Bing Fan, Xin Gu, Haiqing Ren, Dongfang Liu, Heng Fan, and Libo Zhang. In NeurIPS 2025. [[code]](https://github.com/juneyeeHu/LM-EEC)

- [EgoExoBench: A Benchmark for First- and Third-person View Video Understanding in MLLMs](https://arxiv.org/abs/2507.18342) - Yuping He, Yifei Huang, Guo Chen, Baoqi Pei, Jilan Xu, Tong Lu, Jiangmiao Pang, et al. In NeurIPS 2025. [[code]](https://github.com/ayiyayi/EgoExoBench)

- [ObjectRelator: Enabling Cross-View Object Relation Understanding Across Ego-Centric and Exo-Centric Perspectives](https://arxiv.org/abs/2411.19083) - Yuqian Fu, Runze Wang, Bin Ren, Guolei Sun, Biao Gong, Yanwei Fu, Danda Pani Paudel, Xuanjing Huang, and Luc Van Gool. In ICCV 2025. [[project page]](https://yuqianfu.com/ObjectRelator/)

- [O-MaMa: Learning Object Mask Matching between Egocentric and Exocentric Views](https://arxiv.org/abs/2506.06026) - Lorenzo Mur-Labadia, Maria Santos-Villafranca, Jesus Bermudez-Cameo, Alejandro Perez-Yus, Ruben Martinez-Cantin, and Jose J. Guerrero. In ICCV 2025. [[project page]](https://maria-sanvil.github.io/O-MaMa/) [[code]](https://github.com/Maria-SanVil/O-MaMa)

- [Bootstrap Your Own Views: Masked Ego-Exo Modeling for Fine-grained View-invariant Video Representations](https://arxiv.org/abs/2503.19706) - Jungin Park, Jiyoung Lee, and Kwanghoon Sohn. In CVPR 2025. [[code]](https://github.com/park-jungin/byov)

- [Viewpoint Rosetta Stone: Unlocking Unpaired Ego-Exo Videos for View-invariant Representation Learning](https://openaccess.thecvf.com/content/CVPR2025/papers/Luo_Viewpoint_Rosetta_Stone_Unlocking_Unpaired_Ego-Exo_Videos_for_View-invariant_Representation_CVPR_2025_paper.pdf) - Mi Luo, Zihui Xue, Alex Dimakis, and Kristen Grauman. In CVPR 2025. [[project page]](https://vision.cs.utexas.edu/projects/ViewpointRosetta/)

- [Which Viewpoint Shows it Best? Language for Weakly Supervising View Selection in Multi-view Instructional Videos](https://arxiv.org/abs/2411.08753) - Sagnik Majumder, Tushar Nagarajan, Ziad Al-Halah, Reina Pradhan, and Kristen Grauman. In CVPR 2025. [[project page]](https://vision.cs.utexas.edu/projects/which-view-shows-it-best/)

- [Sound Bridge: Associating Egocentric and Exocentric Videos via Audio Cues](https://openaccess.thecvf.com/content/CVPR2025/html/Huang_Sound_Bridge_Associating_Egocentric_and_Exocentric_Videos_via_Audio_Cues_CVPR_2025_paper.html) - Sihong Huang, Jiaxin Wu, Xiaoyong Wei, Yi Cai, Dongmei Jiang, and Yaowei Wang. In CVPR 2025. [[code]](https://github.com/shhuangcoder/SoundBridge)

- [EgoExo-Gen: Ego-centric Video Prediction by Watching Exo-centric Videos](https://arxiv.org/abs/2504.11732) - Jilan Xu, Yifei Huang, Baoqi Pei, Junlin Hou, Qingqiu Li, Guo Chen, Yuejie Zhang, Rui Feng, and Weidi Xie. In ICLR 2025.

- [Exo2EgoDVC: Dense Video Captioning of Egocentric Procedural Activities Using Web Instructional Videos](https://arxiv.org/abs/2311.16444) - Takehiko Ohkawa, Takuma Yagi, Taichi Nishimura, Ryosuke Furuta, Atsushi Hashimoto, Yoshitaka Ushiku, and Yoichi Sato. In WACV 2025. [[code]](https://github.com/ut-vision/Exo2EgoDVC)

- [EgoExo-Fitness: Towards Egocentric and Exocentric Full-Body Action Understanding](https://arxiv.org/abs/2406.08877) - Yuan-Ming Li, Wei-Jin Huang, An-Lan Wang, Ling-An Zeng, Jing-Ke Meng, and Wei-Shi Zheng. In ECCV 2024. [[code]](https://github.com/iSEE-Laboratory/EgoExo-Fitness)

- [4Diff: 3D-Aware Diffusion Model for Third-to-First Viewpoint Translation](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03536.pdf) - Feng Cheng, Mi Luo, Huiyu Wang, Alex Dimakis, Lorenzo Torresani, Gedas Bertasius, and Kristen Grauman. In ECCV 2024. [[project page]](https://klauscc.github.io/4diff)

- [Synchronization is All You Need: Exocentric-to-Egocentric Transfer for Temporal Action Segmentation with Unlabeled Synchronized Video Pairs](https://arxiv.org/abs/2312.02638) - Camillo Quattrocchi, Antonino Furnari, Daniele Di Mauro, Mario Valerio Giuffrida, and Giovanni Maria Farinella. In ECCV 2024. [[code]](https://github.com/fpv-iplab/synchronization-is-all-you-need)

- [EgoExoLearn: A Dataset for Bridging Asynchronous Ego- and Exo-centric View of Procedural Activities in Real World](https://arxiv.org/abs/2403.16182) - Yifei Huang, Guo Chen, Jilan Xu, Mingfang Zhang, Lijin Yang, Baoqi Pei, et al. In CVPR 2024. [[code]](https://github.com/OpenGVLab/EgoExoLearn)

- [Fusing Personal and Environmental Cues for Identification and Segmentation of First-Person Camera Wearers in Third-Person Views](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_Fusing_Personal_and_Environmental_Cues_for_Identification_and_Segmentation_of_CVPR_2024_paper.html) - Ziwei Zhao, Yuchen Wang, Chuhua Wang, and David Crandall. In CVPR 2024. [[code]](https://github.com/ziweizhao1993/PEN)

</details>

### Egocentric Video-Language Models & Question Answering

<details>
<summary>Show papers (39)</summary>

- [X-LeBench: A Benchmark for Extremely Long Egocentric Video Understanding](https://arxiv.org/abs/2501.06835) - Wenqi Zhou, Kai Cao, Hao Zheng, Yunze Liu, Xinyi Zheng, Miao Liu, Per Ola Kristensson, Walterio W. Mayol-Cuevas, Fan Zhang, Weizhe Lin, and Junxiao Shen. In Findings of EMNLP 2025. [[code]](https://github.com/X-Intelligence-Labs/X-LeBench)

- [Vinci: A Real-time Smart Assistant Based on Egocentric Vision-Language Model for Portable Devices](https://doi.org/10.1145/3749513) - Yifei Huang, Jilan Xu, Baoqi Pei, Lijin Yang, Mingfang Zhang, Yuping He, Guo Chen, Xinyuan Chen, Yaohui Wang, Zheng Nie, Jinyao Liu, Dechen Lin, Fang Fang, Kunpeng Li, Chang Yuan, Yu Qiao, Yali Wang, and Limin Wang. In IMWUT 2025. [[code]](https://github.com/opengvlab/vinci)

- [Ego2Web: A Web Agent Benchmark Grounded in Egocentric Videos](https://arxiv.org/abs/2603.22529) - Shoubin Yu, Lei Shu, Antoine Yang, Yao Fu, Srinivas Sunkara, Maria Wang, Jindong Chen, Mohit Bansal, and Boqing Gong. In CVPR 2026. [[project page]](https://ego2web.github.io/) [[code]](https://github.com/Yui010206/Ego2Web)

- [HanDyVQA: A Video QA Benchmark for Fine-Grained Hand-Object Interaction Dynamics](https://arxiv.org/abs/2512.00885) - Masatoshi Tateno, Gido Kato, Hirokatsu Kataoka, Yoichi Sato, and Takuma Yagi. In CVPR 2026. [[project page]](https://masatate.github.io/HanDyVQA-project-page/)

- [EgoProx: Evaluating MLLMs on Egocentric 3D Proximity Reasoning Across a Cognitive Hierarchy](https://arxiv.org/abs/2605.24456) - Jinzhao Li, Yinuo Chen, Dongxu Piao, Panwang Pan, Yifan Yu, Dong Wang, Honglei Yan, Liang Yue, Shaofei Wang, Yixin Chen, Siyuan Huang, and Miao Liu. In CVPR 2026.

- [Ego-Grounding for Personalized Question-Answering in Egocentric Videos](https://arxiv.org/abs/2604.01966) - Junbin Xiao, Shenglang Zhang, Pengxiang Zhu, and Angela Yao. In CVPR 2026. [[code]](https://github.com/Ryougetsu3606/MyEgo)

- [EgoAVU: Egocentric Audio-Visual Understanding](https://arxiv.org/abs/2602.06139) - Ashish Seth, Xinhao Mei, Changsheng Zhao, Varun Nagaraja, Ernie Chang, Gregory P. Meyer, Gael Le Lan, Yunyang Xiong, Vikas Chandra, Yangyang Shi, Dinesh Manocha, and Zhipeng Cai. In CVPR 2026. [[project page]](https://cs20s030.github.io/EgoAVU/) [[code]](https://github.com/facebookresearch/EgoAVU)

- [EgoSound: Benchmarking Sound Understanding in Egocentric Videos](https://arxiv.org/abs/2602.14122) - Bingwen Zhu, Yuqian Fu, Qiaole Dong, Guolei Sun, Tianwen Qian, Yuzheng Wu, Danda Pani Paudel, Xiangyang Xue, and Yanwei Fu. In CVPR 2026. [[project page]](https://groolegend.github.io/EgoSound/) [[dataset]](https://huggingface.co/datasets/grooLegend/EgoSound)

- [Minerva-Ego: Spatiotemporal Hints for Egocentric Video Understanding](https://arxiv.org/abs/2605.15342) - Arsha Nagrani, Jasper Uijlings, Shyamal Buch, Tobias Weyand, Sudheendra Vijayanarasimhan, Bo Hu, Ramin Mehran, David A Ross, and Cordelia Schmid. In CVPR 2026. [[dataset]](https://github.com/google-deepmind/neptune)

- [Do You See What I Am Pointing At? Gesture-Based Egocentric Video Question Answering](https://arxiv.org/abs/2603.12533) - Yura Choi, Roy Miles, Rolandos Alexandros Potamias, Ismail Elezi, Jiankang Deng, and Stefanos Zafeiriou. In CVPR 2026. [[project page]](https://yuuraa.github.io/papers/choi2026egovqa)

- [ST-Think: How Multimodal Large Language Models Reason About 4D Worlds from Ego-Centric Videos](https://arxiv.org/abs/2503.12542) - Peiran Wu, Yunze Liu, Miao Liu, and Junxiao Shen. In WACV 2026.

- [Ego-EXTRA: video-language Egocentric Dataset for EXpert-TRAinee assistance](https://arxiv.org/abs/2512.13238) - Francesco Ragusa, Michele Mazzamuto, Rosario Forte, Irene D'Ambra, James Fort, Jakob Engel, Antonino Furnari, and Giovanni Maria Farinella. In WACV 2026. [[project page]](https://fpv-iplab.github.io/Ego-EXTRA/)

- [EgoDTM: Towards 3D-Aware Egocentric Video-Language Pretraining](https://arxiv.org/abs/2503.15470) - Boshen Xu, Yuting Mei, Xinbi Liu, Sipeng Zheng, and Qin Jin. In NeurIPS 2025. [[code]](https://github.com/xuboshen/EgoDTM)

- [EgoThinker: Unveiling Egocentric Reasoning with Spatio-Temporal CoT](https://arxiv.org/abs/2510.23569) - Baoqi Pei, Yifei Huang, Jilan Xu, Yuping He, Guo Chen, Fei Wu, Yu Qiao, and Jiangmiao Pang. In NeurIPS 2025. [[code]](https://github.com/InternRobotics/EgoThinker)

- [EOC-Bench: Can MLLMs Identify, Recall, and Forecast Objects in an Egocentric World?](https://arxiv.org/abs/2506.05287) - Yuqian Yuan, Ronghao Dang, Long Li, Wentong Li, Dian Jiao, Xin Li, Deli Zhao, Fan Wang, Wenqiao Zhang, Jun Xiao, and Yueting Zhuang. In NeurIPS 2025. [[project page]](https://circleradon.github.io/EOCBench/) [[code]](https://github.com/alibaba-damo-academy/EOCBench)

- [WearVQA: A Visual Question Answering Benchmark for Wearables in Egocentric Authentic Real-world scenarios](https://arxiv.org/abs/2511.22154) - Eun Chang, Zhuangqun Huang, Yiwei Liao, Sagar Ravi Bhavsar, Amogh Param, Tammy Stark, et al. In NeurIPS 2025.

- [Gaze-VLM: Bridging Gaze and VLMs through Attention Regularization for Egocentric Understanding](https://arxiv.org/abs/2510.21356) - Anupam Pani and Yanchao Yang. In NeurIPS 2025. [[code]](https://github.com/anupampani/Gaze-VLM)

- [In the Eye of MLLM: Benchmarking Egocentric Video Intent Understanding with Gaze-Guided Prompting](https://arxiv.org/abs/2509.07447) - Taiying Peng, Jiacheng Hua, Miao Liu, and Feng Lu. In NeurIPS 2025.

- [OpenMMEgo: Enhancing Egocentric Understanding for LMMs with Open Weights and Data](https://papers.nips.cc/paper_files/paper/2025/hash/24b9e3da4b01ec1e8a41144cfe8dc929-Abstract-Conference.html) - Hao Luo, Zihao Yue, Wanpeng Zhang, Yicheng Feng, Sipeng Zheng, Deheng Ye, and Zongqing Lu. In NeurIPS 2025. [[code]](https://github.com/BeingBeyond/OpenMMEgo)

- [Eyes Wide Open: Ego Proactive Video-LLM for Streaming Video](https://arxiv.org/abs/2510.14560) - Yulin Zhang, Cheng Shi, Yang Wang, and Sibei Yang. In NeurIPS 2025. [[code]](https://github.com/SooLab/EyeWO)

- [Embodied VideoAgent: Persistent Memory from Egocentric Videos and Embodied Sensors Enables Dynamic Scene Understanding](https://arxiv.org/abs/2501.00358) - Yue Fan, Xiaojian Ma, Rongpeng Su, Jun Guo, Rujie Wu, Xi Chen, and Qing Li. In ICCV 2025.

- [Visual Intention Grounding for Egocentric Assistants](https://arxiv.org/abs/2504.13621) - Pengzhan Sun, Junbin Xiao, Tze Ho Elden Tse, Yicong Li, Arjun Akula, and Angela Yao. In ICCV 2025. [[code]](https://github.com/pengzhansun/EgoIntention)

- [EgoLife: Towards Egocentric Life Assistant](https://arxiv.org/abs/2503.03803) - Jingkang Yang, Shuai Liu, Hongming Guo, et al. In CVPR 2025. [[code]](https://github.com/EvolvingLMMs-Lab/EgoLife)

- [EgoTextVQA: Towards Egocentric Scene-Text Aware Video Question Answering](https://arxiv.org/abs/2502.07411) - Sheng Zhou, Junbin Xiao, Qingyun Li, Yicong Li, Xun Yang, Dan Guo, Meng Wang, Tat-Seng Chua, and Angela Yao. In CVPR 2025. [[code]](https://github.com/zhousheng97/EgoTextVQA)

- [Omnia de EgoTempo: Benchmarking Temporal Understanding of Multi-Modal LLMs in Egocentric Videos](https://arxiv.org/abs/2503.13646) - Chiara Plizzari, Alessio Tonioni, Yongqin Xian, Achin Kulshrestha, and Federico Tombari. In CVPR 2025. [[code]](https://github.com/google-research-datasets/egotempo)

- [Object-Shot Enhanced Grounding Network for Egocentric Video](https://arxiv.org/abs/2505.04270) - Yisen Feng, Haoyu Zhang, Meng Liu, Weili Guan, and Liqiang Nie. In CVPR 2025. [[code]](https://github.com/Yisen-Feng/OSGNet)

- [ECBench: Can Multi-modal Foundation Models Understand the Egocentric World? A Holistic Embodied Cognition Benchmark](https://arxiv.org/abs/2501.05031) - Ronghao Dang, Yuqian Yuan, Wenqi Zhang, Yifei Xin, Boqiang Zhang, Long Li, Liuyi Wang, Qinyang Zeng, Xin Li, and Lidong Bing. In CVPR 2025. [[code]](https://github.com/Rh-Dang/ECBench)

- [MM-Ego: Towards Building Egocentric Multimodal LLMs for Video QA](https://arxiv.org/abs/2410.07177) - Hanrong Ye, Haotian Zhang, Erik Daxberger, Lin Chen, Zongyu Lin, et al. In ICLR 2025. [[project page]](https://machinelearning.apple.com/research/mm-ego)

- [Do Egocentric Video-Language Models Truly Understand Hand-Object Interactions?](https://arxiv.org/abs/2405.17719) - Boshen Xu, Ziheng Wang, Yang Du, Zhinan Song, Sipeng Zheng, and Qin Jin. In ICLR 2025. [[code]](https://github.com/xuboshen/EgoNCEpp)

- [Modeling Fine-Grained Hand-Object Dynamics for Egocentric Video Representation Learning](https://arxiv.org/abs/2503.00986) - Baoqi Pei, Yifei Huang, Jilan Xu, Guo Chen, Yuping He, Lijin Yang, Yali Wang, Weidi Xie, Yu Qiao, Fei Wu, and Limin Wang. In ICLR 2025. [[code]](https://github.com/OpenRobotLab/EgoHOD)

- [HourVideo: 1-Hour Video-Language Understanding](https://arxiv.org/abs/2411.04998) - Keshigeyan Chandrasegaran, Agrim Gupta, Lea M. Hadzic, Taran Kota, Jimming He, Cristóbal Eyzaguirre, Zane Durante, Manling Li, Jiajun Wu, and Li Fei-Fei. In NeurIPS 2024. [[project page]](https://hourvideo.stanford.edu/) [[code]](https://github.com/keshik6/HourVideo)

- [HENASY: Learning to Assemble Scene-Entities for Interpretable Egocentric Video-Language Model](https://arxiv.org/abs/2406.00307) - Khoa Vo, Thinh Phan, Kashu Yamazaki, Minh Tran, and Ngan Le. In NeurIPS 2024. [[project page]](https://uark-aicv.github.io/HENASY/) [[code]](https://github.com/UARK-AICV/HENASY)

- [AMEGO: Active Memory from long EGOcentric videos](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02032.pdf) - Gabriele Goletto, Tushar Nagarajan, Giuseppe Averta, and Dima Damen. In ECCV 2024. [[project page]](https://gabrielegoletto.github.io/AMEGO/) [[code]](https://github.com/gabrielegoletto/AMEGO)

- [Video ReCap: Recursive Captioning of Hour-Long Videos](https://arxiv.org/abs/2402.13250) - Md Mohaiminul Islam, Ngan Ho, Xitong Yang, Tushar Nagarajan, Lorenzo Torresani, and Gedas Bertasius. In CVPR 2024. [[project page]](https://sites.google.com/view/vidrecap)

- [Retrieval-Augmented Egocentric Video Captioning](https://arxiv.org/abs/2401.00789) - Jilan Xu, Yifei Huang, Junlin Hou, Guo Chen, Yuejie Zhang, Rui Feng, and Weidi Xie. In CVPR 2024. [[project page]](https://jazzcharles.github.io/Egoinstructor/)

- [Grounded Question-Answering in Long Egocentric Videos](https://arxiv.org/abs/2312.06505) - Shangzhe Di and Weidi Xie. In CVPR 2024. [[project page]](https://dszdsz.cn/GroundVQA) [[code]](https://github.com/Becomebright/GroundVQA)

- [EgoThink: Evaluating First-Person Perspective Thinking Capability of Vision-Language Models](https://arxiv.org/abs/2311.15596) - Sijie Cheng, Zhicheng Guo, Jingwen Wu, Kechen Fang, Peng Li, Huaping Liu, and Yang Liu. In CVPR 2024. [[code]](https://github.com/AdaCheng/EgoThink)

- [EgoVideo: Exploring Egocentric Foundation Model and Downstream Adaptation](https://arxiv.org/abs/2406.18070) - Baoqi Pei, Guo Chen, Jilan Xu, Yuping He, Yicheng Liu, Kanghua Pan, et al. arXiv 2024. [[code]](https://github.com/OpenGVLab/EgoVideo)

- [EgoSchema: A Diagnostic Benchmark for Very Long-form Video Language Understanding](https://arxiv.org/abs/2308.09126) - Karttikeya Mangalam, Raiymbek Akshulakov, and Jitendra Malik. In NeurIPS 2023. [[project page]](https://egoschema.github.io/) [[code]](https://github.com/egoschema/EgoSchema)

</details>

### Egocentric Video Generation & World Models

<details>
<summary>Show papers (13)</summary>

- [EgoControl: Controllable Egocentric Video Generation via 3D Full-Body Poses](https://arxiv.org/abs/2511.18173) - Enrico Pallotta, Sina Mokhtarzadeh Azar, Lars Doorenbos, Serdar Ozsoy, Umar Iqbal, and Juergen Gall. In CVPR 2026. [[project page]](https://cvg-bonn.github.io/EgoControl/)

- [Ego-InBetween: Generating Object State Transitions in Ego-Centric Videos](https://arxiv.org/abs/2604.17749) - Mengmeng Ge, Takashi Isobe, Xu Jia, Yanan Sun, Zetong Yang, Weinong Wang, Dong Zhou, Dong Li, Huchuan Lu, and Emad Barsoum. In CVPR 2026.

- [EgoX: Egocentric Video Generation from a Single Exocentric Video](https://arxiv.org/abs/2512.08269) - Taewoong Kang, Kinam Kim, Dohyeon Kim, Minho Park, Junha Hyung, and Jaegul Choo. In CVPR 2026. [[project page]](https://keh0t0.github.io/EgoX) [[code]](https://github.com/DAVIAN-Robotics/EgoX)

- [Generating Humanless Environment Walkthroughs from Egocentric Walking Tour Videos](https://arxiv.org/abs/2603.29036) - Yujin Ham, Junho Kim, Vivek Boominathan, and Guha Balakrishnan. In CVPR 2026.

- [EgoEdit: Dataset, Real-Time Streaming Model, and Benchmark for Egocentric Video Editing](https://arxiv.org/abs/2512.06065) - Runjia Li, Moayed Haji-Ali, Ashkan Mirzaei, Chaoyang Wang, Arpit Sahni, Ivan Skorokhodov, Aliaksandr Siarohin, Tomas Jakab, Junlin Han, Sergey Tulyakov, Philip Torr, and Willi Menapace. In CVPR 2026. [[project page]](https://snap-research.github.io/EgoEdit) [[code]](https://github.com/snap-research/EgoEdit)

- [PlayerOne: Egocentric World Simulator](https://arxiv.org/abs/2506.09995) - Yuanpeng Tu, Hao Luo, Xi Chen, Xiang Bai, Fan Wang, and Hengshuang Zhao. In NeurIPS 2025. [[project page]](https://playerone-hku.github.io/) [[code]](https://github.com/yuanpengtu/PlayerOne)

- [EgoVid-5M: A Large-Scale Video-Action Dataset for Egocentric Video Generation](https://arxiv.org/abs/2411.08380) - Xiaofeng Wang, Kang Zhao, Feng Liu, Jiayu Wang, Guosheng Zhao, Xiaoyi Bao, Zheng Zhu, Yingya Zhang, and Xingang Wang. In NeurIPS 2025. [[project page]](https://egovid.github.io/) [[code]](https://github.com/JeffWang987/EgoVid)

- [Whole-Body Conditioned Egocentric Video Prediction](https://arxiv.org/abs/2506.21552) - Yutong Bai, Danny Tran, Amir Bar, Yann LeCun, Trevor Darrell, and Jitendra Malik. In NeurIPS 2025. [[project page]](https://dannytran123.github.io/PEVA)

- [EgoAgent: A Joint Predictive Agent Model in Egocentric Worlds](https://arxiv.org/abs/2502.05857) - Lu Chen, Yizhou Wang, Shixiang Tang, Qianhong Ma, Tong He, Wanli Ouyang, Xiaowei Zhou, Hujun Bao, and Sida Peng. In ICCV 2025. [[code]](https://github.com/zju3dv/EgoAgent)

- [GEM: A Generalizable Ego-Vision Multimodal World Model for Fine-Grained Ego-Motion, Object Dynamics, and Scene Composition Control](https://openaccess.thecvf.com/content/CVPR2025/papers/Hassan_GEM_A_Generalizable_Ego-Vision_Multimodal_World_Model_for_Fine-Grained_Ego-Motion_CVPR_2025_paper.pdf) - Mariam Hassan, Sebastian Stapf, Ahmad Rahimi, et al. In CVPR 2025. [[project page]](https://vita-epfl.github.io/GEM.github.io/) [[code]](https://github.com/vita-epfl/GEM)

- [Exocentric-to-Egocentric Video Generation](https://openreview.net/forum?id=UHDCbIrCFL) - Jia-Wei Liu, Weijia Mao, Zhongcong Xu, Jussi Keppo, and Mike Zheng Shou. In NeurIPS 2024. [[code]](https://github.com/showlab/Exo2Ego-V)

- [LEGO: Learning EGOcentric Action Frame Generation via Visual Instruction Tuning](https://arxiv.org/abs/2312.03849) - Bolin Lai, Xiaoliang Dai, Lawrence Chen, Guan Pang, James M. Rehg, and Miao Liu. In ECCV 2024. [[project page]](https://bolinlai.github.io/Lego_EgoActGen/)

- [Put Myself in Your Shoes: Lifting the Egocentric Perspective from Exocentric Videos](https://arxiv.org/abs/2403.06351) - Mi Luo, Zihui Xue, Alex Dimakis, and Kristen Grauman. In ECCV 2024. [[project page]](https://vision.cs.utexas.edu/projects/Exo2Ego/)

</details>

### 3D Scene Reconstruction & Mapping

<details>
<summary>Show papers (8)</summary>

- [FunRec: Reconstructing Functional 3D Scenes from Egocentric Interaction Videos](https://openaccess.thecvf.com/content/CVPR2026/html/Delitzas_FUN_REC__Reconstructing_Functional_3D_Scenes_from_Egocentric_Interaction_CVPR_2026_paper.html) - Alexandros Delitzas, Chenyangguang Zhang, Alexey Gavryushin, Tommaso Di Mario, Boyang Sun, Rishabh Dabral, Leonidas Guibas, Christian Theobalt, Marc Pollefeys, Francis Engelmann, and Daniel Barath. In CVPR 2026. [[project page]](https://functionalscenes.github.io/)

- [Seeing in the Dark: Benchmarking Egocentric 3D Vision with the Oxford Day-and-Night Dataset](https://arxiv.org/abs/2506.04224) - Zirui Wang, Wenjing Bian, Xinghui Li, Yifu Tao, Jianeng Wang, Maurice Fallon, and Victor Adrian Prisacariu. In NeurIPS 2025. [[project page]](https://oxdan.active.vision/)

- [Pandora: Articulated 3D Scene Graphs from Egocentric Vision](https://bmvc2025.bmva.org/proceedings/548/) - Alan Yu, Yun Chang, Christopher Xie, and Luca Carlone. In BMVC 2025.

- [Benchmarking Egocentric Visual-Inertial SLAM at City Scale](https://arxiv.org/abs/2509.26639) - Anusha Krishnan, Shaohui Liu, Paul-Edouard Sarlin, Oscar Gentilhomme, David Caruso, Maurizio Monge, Richard Newcombe, Jakob Engel, and Marc Pollefeys. In ICCV 2025. [[project page]](https://www.lamaria.ethz.ch) [[code]](https://github.com/cvg/lamaria)

- [Self-Supervised Monocular 4D Scene Reconstruction for Egocentric Videos](https://arxiv.org/abs/2411.09145) - Chengbo Yuan, Geng Chen, Li Yi, and Yang Gao. In ICCV 2025. [[project page]](https://egomono4d.github.io/)

- [DIV-FF: Dynamic Image-Video Feature Fields for Environment Understanding in Egocentric Videos](https://arxiv.org/abs/2503.08344) - Lorenzo Mur-Labadia, Jose J. Guerrero, and Ruben Martinez-Cantin. In CVPR 2025. [[code]](https://github.com/lmur98/DIV_FF_CVPR)

- [Layered Motion Fusion: Lifting Motion Segmentation to 3D in Egocentric Videos](https://arxiv.org/abs/2506.05546) - Vadim Tschernezki, Diane Larlus, Iro Laina, and Andrea Vedaldi. In CVPR 2025.

- [EgoLifter: Open-world 3D Segmentation for Egocentric Perception](https://arxiv.org/abs/2403.18118) - Qiao Gu, Zhaoyang Lv, Duncan Frost, Simon Green, Julian Straub, Chris Sweeney, et al. In ECCV 2024. [[project page]](https://egolifter.github.io/)

</details>

### Assistive & Navigation

<details>
<summary>Show papers (6)</summary>

- [LifeEval: A Multimodal Benchmark for Assistive AI in Egocentric Daily Life Tasks](https://arxiv.org/abs/2603.00490) - Hengjian Gao, Kaiwei Zhang, Shibo Wang, Mingjie Chen, Qihang Cao, Xianfeng Wang, Yucheng Zhu, Xiongkuo Min, Wei Sun, Dandan Zhu, and Guangtao Zhai. In CVPR 2026.

- [Benchmarking Egocentric Multimodal Goal Inference for Assistive Wearable Agents](https://arxiv.org/abs/2510.22443) - Vijay Veerabadran, Fanyi Xiao, Nitin Kamra, Pedro Matias, Joy Chen, Caley Drooff, et al. In NeurIPS 2025.

- [EgoBlind: Towards Egocentric Visual Assistance for the Blind](https://arxiv.org/abs/2503.08221) - Junbin Xiao, Nanxin Huang, Hao Qiu, Zhulin Tao, Xun Yang, Richang Hong, Meng Wang, and Angela Yao. In NeurIPS 2025.

- [LookOut: Real-World Humanoid Egocentric Navigation](https://openaccess.thecvf.com/content/ICCV2025/papers/Pan_LookOut_Real-World_Humanoid_Egocentric_Navigation_ICCV_2025_paper.pdf) - Boxiao Pan, Adam W. Harley, Francis Engelmann, C. Karen Liu, and Leonidas J. Guibas. In ICCV 2025. [[project page]](https://sites.google.com/stanford.edu/lookout)

- [Vid2Coach: Transforming How-To Videos into Task Assistants](https://arxiv.org/abs/2506.00717) - Mina Huh, Zihui Xue, Ujjaini Das, Kumar Ashutosh, Kristen Grauman, and Amy Pavel. In UIST 2025. [[project page]](https://minahuh.com/Vid2Coach/)

- [SANPO: A Scene Understanding, Accessibility and Human Navigation Dataset](https://openaccess.thecvf.com/content/WACV2025/html/Waghmare_SANPO_A_Scene_Understanding_Accessibility_and_Human_Navigation_Dataset_WACV_2025_paper.html) - Sagar M. Waghmare, Kimberly Wilber, Dave Hawkey, Xuan Yang, Matthew Wilson, Stephanie Debats, et al. In WACV 2025. [[project page]](https://google-research-datasets.github.io/sanpo_dataset/) [[code]](https://github.com/google-research-datasets/sanpo_dataset)

</details>

### Miscellaneous (New Tasks)

<details>
<summary>Show papers (42)</summary>

- [EgoPet: Egomotion and Interaction Data from an Animal's Perspective](https://arxiv.org/abs/2404.09991) - Amir Bar, Arya Bakhtiar, Danny Tran, Antonio Loquercio, Jathushan Rajasegaran, Yann LeCun, Amir Globerson, and Trevor Darrell. In ECCV 2024. [[project page]](https://www.amirbar.net/egopet/)

- [egoEMOTION: Egocentric Vision and Physiological Signals for Emotion and Personality Recognition in Real-World Tasks](https://arxiv.org/abs/2510.22129) - Matthias Jammot, Björn Braun, Paul Streli, Rafael Wampfler, and Christian Holz. In NeurIPS 2025. [[project page]](https://siplab.org/projects/egoEMOTION) [[code]](https://github.com/eth-siplab/egoEMOTION)

- [egoPPG: Heart Rate Estimation from Eye-Tracking Cameras in Egocentric Systems to Benefit Downstream Vision Tasks](https://arxiv.org/abs/2502.20879) - Björn Braun, Rayan Armani, Manuel Meier, Max Moebus, and Christian Holz. In ICCV 2025. [[project page]](https://siplab.org/projects/egoPPG) [[code]](https://github.com/eth-siplab/egoPPG)

- [Toward Robust Audio-Visual Synchronization Detection in Egocentric Video with Sparse Synchronization Events](https://bmvc2025.bmva.org/proceedings/903/) - Jordan Voas, Wei-Cheng Tseng, Benoit Vallade, Alex Mackin, David Higham, and David Harwath. In BMVC 2025.

- [SkillSight: Efficient First-Person Skill Assessment with Gaze](https://arxiv.org/abs/2511.19629) - Chi Hsuan Wu, Kumar Ashutosh, and Kristen Grauman. In CVPR 2026.

- [PHGC: Procedural Heterogeneous Graph Completion for Natural Language Task Verification in Egocentric Videos](https://openaccess.thecvf.com/content/CVPR2025/papers/Jiang_PHGC_Procedural_Heterogeneous_Graph_Completion_for_Natural_Language_Task_Verification_CVPR_2025_paper.pdf) - Xun Jiang, Zhiyi Huang, Xing Xu, Jingkuan Song, Fumin Shen, and Heng Tao Shen. In CVPR 2025.

- [EgoSonics: Generating Synchronized Audio for Silent Egocentric Videos](https://arxiv.org/abs/2407.20592) - Aashish Rai and Srinath Sridhar. In WACV 2025. [[project page]](https://ivl.cs.brown.edu/research/egosonics.html)

- [E³: Exploring Embodied Emotion Through A Large-Scale Egocentric Video Dataset](https://proceedings.neurips.cc/paper_files/paper/2024/hash/d611d5c0251d9680f869c5d2c46c6fcd-Abstract-Datasets_and_Benchmarks_Track.html) - Wang Lin, Yueying Feng, Wenkang Han, Tao Jin, Zhou Zhao, Fei Wu, Chang Yao, and Jingyuan Chen. In NeurIPS 2024.

- [EgoCVR: An Egocentric Benchmark for Fine-Grained Composed Video Retrieval](https://arxiv.org/abs/2407.16658) - Thomas Hummel, Shyamgopal Karthik, Mariana-Iuliana Georgescu, and Zeynep Akata. In ECCV 2024. [[code]](https://github.com/ExplainableML/EgoCVR)

- [Action2Sound: Ambient-Aware Generation of Action Sounds from Egocentric Videos](https://arxiv.org/abs/2406.09272) - Changan Chen, Puyuan Peng, Ami Baid, Zihui Xue, Wei-Ning Hsu, David Harwath, and Kristen Grauman. In ECCV 2024. [[project page]](https://vision.cs.utexas.edu/projects/action2sound/) [[code]](https://github.com/ChanganVR/action2sound)

- [Masked Video and Body-worn IMU Autoencoder for Egocentric Action Recognition](https://arxiv.org/abs/2407.06628) - Mingfang Zhang, Yifei Huang, Ruicong Liu, and Yoichi Sato. In ECCV 2024. [[code]](https://github.com/mf-zhang/IMU-Video-MAE)

- [EgoGen: An Egocentric Synthetic Data Generator](https://arxiv.org/pdf/2401.08739) -  Gen Li, Kaifeng Zhao, Siwei Zhang, Xiaozhong Lyu, Mihai Dusmanu, Yan Zhang, Marc Pollefeys, and Siyu Tang. In CVPR 2024. [[project page]](https://ego-gen.github.io/)

- [PREGO: online mistake detection in PRocedural EGOcentric videos](https://arxiv.org/pdf/2404.01933) - Alessandro Flaborea, Guido Maria D'Amely di Melendugno, Leonardo Plini, Luca Scofano, Edoardo De Matteis, Antonino Furnari, Giovanni Maria Farinella, and Fabio Galasso. In CVPR 2024.

- [Action Scene Graphs for Long-Form Understanding of Egocentric Videos](https://arxiv.org/pdf/2312.03391) - Ivan Rodin, Antonino Furnari, Kyle Min, Subarna Tripathi, and Giovanni Maria Farinella. In CVPR 2024.

- [Learning Spatial Features from Audio-Visual Correspondence in Egocentric Videos](https://arxiv.org/abs/2307.04760) - Sagnik Majumder, Ziad Al-Halah, and Kristen Grauman. In CVPR 2024. [[project page]](http://vision.cs.utexas.edu/projects/ego_av_corr)

- [Trans4Map: Revisiting Holistic Bird's-Eye-View Mapping from Egocentric Images to Allocentric Semantics with Vision Transformers](https://openaccess.thecvf.com/content/WACV2023/papers/Chen_Trans4Map_Revisiting_Holistic_Birds-Eye-View_Mapping_From_Egocentric_Images_to_Allocentric_WACV_2023_paper.pdf) - Chang Chen, Jiaming Zhang, Kailun Yang, Kunyu Peng, and Rainer Stiefelhagen. In WACV 2023.

- [Multi-label Affordance Mapping from Egocentric Vision](https://openaccess.thecvf.com/content/ICCV2023/papers/Mur-Labadia_Multi-label_Affordance_Mapping_from_Egocentric_Vision_ICCV_2023_paper.pdf) - Lorenzo Mur-Labadia, Jose J. Guerrero, and Ruben Martinez-Cantin. In ICCV 2023.

- [COPILOT: Human-Environment Collision Prediction and Localization from Egocentric Videos](https://openaccess.thecvf.com/content/ICCV2023/papers/Pan_COPILOT_Human-Environment_Collision_Prediction_and_Localization_from_Egocentric_Videos_ICCV_2023_paper.pdf) - Boxiao Pan, Bokui Shen, Davis Rempe, Despoina Paschalidou, Kaichun Mo, Yanchao Yang, and Leonidas J. Guibas. In ICCV 2023. [[project page]](https://sites.google.com/stanford.edu/copilot)

- [Learning from Semantic Alignment between Unpaired Multiviews for Egocentric Video Recognition](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Learning_from_Semantic_Alignment_between_Unpaired_Multiviews_for_Egocentric_Video_ICCV_2023_paper.pdf) - Qitong Wang, Long Zhao, Liangzhe Yuan, Ting Liu, and Xi Peng. In ICCV 2023. [[code]](https://github.com/wqtwjt1996/sum-l)

- [Tracking Multiple Deformable Objects in Egocentric Videos](https://mingzhenhuang.com/projects/detracker.html) - Mingzhen Huang, Xiaoxing Li, Jun Hu, Honghong Peng, Siwei Lyu. In CVPR 2023.

- [Egocentric Audio-Visual Object Localization](https://research.facebook.com/publications/egocentric-audio-visual-object-localization/) - Chao Huang · Yapeng Tian · Anurag Kumar · Chenliang Xu. In CVPR 2023. [[project page]](https://research.facebook.com/publications/egocentric-audio-visual-object-localization/)

- [Balanced Spherical Grid for Egocentric View Synthesis](https://arxiv.org/pdf/2303.12408.pdf) - Changwoon Choi · Sang Min Kim · Young Min Kim. In CVPR 2023. [[code]](https://github.com/changwoonchoi/EgoNeRF)

- [Ego-Body Pose Estimation via Ego-Head Pose Estimation](https://arxiv.org/pdf/2212.04636.pdf) - Jiaman Li · Karen Liu · Jiajun Wu. In CVPR 2023.

- [Egocentric Video Task Translation](https://arxiv.org/pdf/2212.06301.pdf) - Zihui Xue · Yale Song · Kristen Grauman · Lorenzo Torresani. In CVPR 2023.

- [Egocentric Auditory Attention Localization in Conversations](https://arxiv.org/pdf/2303.16024.pdf) - Fiona Ryan · Hao Jiang · Abhinav Shukla · James Rehg · Vamsi Krishna Ithapu. In CVPR 2023. [[project page]](https://fkryan.github.io/saal)

- [Where is my Wallet? Modeling Object Proposal Sets for Egocentric Visual Query Localization](https://arxiv.org/pdf/2211.10528.pdf) - Mengmeng Xu · Yanghao Li · Cheng-Yang Fu · Bernard Ghanem · Tao Xiang · Juan-Manuel Perez-Rua. In CVPR 2023. [[project page]](https://research.facebook.com/publications/where-is-my-wallet-modeling-object-proposal-sets-for-egocentric-visual-query-localization/)

- [Chat2Map: Efficient Scene Mapping from Multi-Ego Conversations](https://arxiv.org/pdf/2301.02184.pdf) - Sagnik Majumder · Hao Jiang · Pierre Moulon · Ethan Henderson · Paul Calamia · Kristen Grauman · Vamsi Krishna Ithapu. In CVPR 2023.


- [EgoTaskQA: Understanding Human Tasks in Egocentric Videos](https://arxiv.org/pdf/2210.03929.pdf) - Baoxiong Jia, Ting Lei, Song-Chun Zhu, Siyuan Huang. In NeurIPS 2022. [[projet page]](https://sites.google.com/view/egotaskqa) [[code]](https://github.com/Buzz-Beater/EgoTaskQA)

- [Robust Egocentric Photo-realistic Facial Expression Transfer for Virtual Reality](https://openaccess.thecvf.com/content/CVPR2022/papers/Jourabloo_Robust_Egocentric_Photo-Realistic_Facial_Expression_Transfer_for_Virtual_Reality_CVPR_2022_paper.pdf) - Amin Jourabloo, Fernando De la Torre, Jason Saragih, Shih-En Wei, Stephen Lombardi, Te-Li Wang, Danielle Belko, Autumn Trimble, Hernan Badino. In CVPR 2022.

- [Joint Hand Motion and Interaction Hotspots Prediction from Egocentric Videos](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Joint_Hand_Motion_and_Interaction_Hotspots_Prediction_From_Egocentric_Videos_CVPR_2022_paper.pdf) - Shaowei Liu, Subarna Tripathi, Somdeb Majumdar, Xiaolong Wang. In CVPR 2022. [[project page]](https://stevenlsw.github.io/hoi-forecast/) [[video]](https://youtu.be/uCUTK9WOhpE) [[slides]](https://drive.google.com/file/d/1N9t4pIZX9usV1QGxTj6nPHQIqZjpf3qg/view?usp=sharing)

- [Egocentric Deep Multi-Channel Audio-Visual Active Speaker Localization](https://openaccess.thecvf.com/content/CVPR2022/papers/Jiang_Egocentric_Deep_Multi-Channel_Audio-Visual_Active_Speaker_Localization_CVPR_2022_paper.pdf) - Hao Jiang, Calvin Murdock, Vamsi Krishna Ithapu. In CVPR 2022.

- [Egocentric Scene Understanding via Multimodal Spatial Rectifier](https://openaccess.thecvf.com/content/CVPR2022/papers/Do_Egocentric_Scene_Understanding_via_Multimodal_Spatial_Rectifier_CVPR_2022_paper.pdf) - Tien Do, Khiem Vuong, Hyun Soo Park. In CVPR 2022.

- [Egocentric Prediction of Action Target in 3D](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Egocentric_Prediction_of_Action_Target_in_3D_CVPR_2022_paper.pdf) - Yiming Li, Ziang Cao, Andrew Liang, Benjamin Liang, Luoyao Chen, Hang Zhao, Chen Feng. In CVPR 2022.

- [Slow-Fast Auditory Streams for Audio Recognition](https://arxiv.org/pdf/2103.03516.pdf) - Evangelos Kazakos, Arsha Nagrani,  Andrew Zisserman, and Dima Damen. ICASSP 2021. [[project page]](https://ekazakos.github.io/auditoryslowfast/) [[code]](https://github.com/ekazakos/auditory-slow-fast)

- [Ego-Exo: Transferring Visual Representations From Third-Person to First-Person Videos](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Ego-Exo_Transferring_Visual_Representations_From_Third-Person_to_First-Person_Videos_CVPR_2021_paper.pdf) - Yanghao Li, Tushar Nagarajan, Bo Xiong, Kristen Grauman. In CVPR 2021. [[code]](https://github.com/facebookresearch/Ego-Exo)

- [EGO-SLAM: A Robust Monocular SLAM for Egocentric Videos](https://www.cse.iitd.ac.in/~chetan/papers/wacv19-egoslam.pdf) - Suvam Patra, Kartikeya Gupta, Faran Ahmad, Chetan Arora, and Subhashis Banerjee. In WACV 2019. [[code]](https://github.com/IITD-COMPUTER-VISION-GROUP/ego-slam)

- [Egocentric Basketball Motion Planning from a Single First-Person Image](https://openaccess.thecvf.com/content_cvpr_2018/papers/Bertasius_Egocentric_Basketball_Motion_CVPR_2018_paper.pdf) - Gedas Bertasius, Aaron Chan, and Jianbo Shi. In CVPR 2018. [[demo]](https://youtu.be/wRRRl4QsUQg)

- [Jointly Learning Energy Expenditures and Activities using Egocentric Multimodal Signals](https://openaccess.thecvf.com/content_cvpr_2017/papers/Nakamura_Jointly_Learning_Energy_CVPR_2017_paper.pdf) - Katsuyuki Nakamura, Serena Yeung, Alexandre Alahi, and Li Fei-Fei. In CVPR 2017.

- [Walk and Learn: Facial Attribute Representation Learning from Egocentric Video and Contextual Data](https://openaccess.thecvf.com/content_cvpr_2016/papers/Wang_Walk_and_Learn_CVPR_2016_paper.pdf) - Jing Wang, Yu Cheng, and Rogerio Schmidt Feris. In CVPR 2016. [[demo]](https://youtu.be/AQKS20Eo7uQ)

- [Compact CNN for Indexing Egocentric Videos](https://www.cs.huji.ac.il/~peleg/papers/wacv16-cnn-indexing.pdf) - Yair Poleg, Ariel Ephrat, Shmuel Peleg, and Chetan Arora. In WACV 2016.

- [Detecting engagement in egocentric video](http://www.cs.utexas.edu/~grauman/papers/su-eccv2016-ego.pdf) - Yu-Chuan Su and Kristen Grauman. In ECCV 2016.

- [EgoSampling: Fast-Forward and Stereo for Egocentric Videos](https://openaccess.thecvf.com/content_cvpr_2015/papers/Poleg_EgoSampling_Fast-Forward_and_2015_CVPR_paper.pdf) - Yair Poleg, Tavi Halperin, Chetan Arora, and Shmuel Peleg. In CVPR 2015.


> Clustered according to the conferences.

</details>

### CVPR

<details>
<summary>Show papers (147)</summary>

- [ForeHOI: Feed-forward 3D Object Reconstruction from Daily Hand-Object Interaction Videos](https://arxiv.org/abs/2602.06226) - Yuantao Chen, Jiahao Chang, Chongjie Ye, Chaoran Zhang, Zhaojie Fang, Chenghong Li, and Xiaoguang Han. In CVPR 2026. [[project page]](https://tao-11-chen.github.io/project_pages/ForeHOI/) [[code]](https://github.com/Tao-11-chen/ForeHOI)

- [EgoFlow: Gradient-Guided Flow Matching for Egocentric 6DoF Object Motion Generation](https://arxiv.org/abs/2604.01421) - Abhishek Saroha, Huajian Zeng, Xingxing Zuo, Daniel Cremers, and Xi Wang. In CVPR 2026. [[project page]](https://abhi-rf.github.io/egoflow/) [[code]](https://github.com/abhi-rf/egoflow)

- [EgoProx: Evaluating MLLMs on Egocentric 3D Proximity Reasoning Across a Cognitive Hierarchy](https://arxiv.org/abs/2605.24456) - Jinzhao Li, Yinuo Chen, Dongxu Piao, Panwang Pan, Yifan Yu, Dong Wang, Honglei Yan, Liang Yue, Shaofei Wang, Yixin Chen, Siyuan Huang, and Miao Liu. In CVPR 2026.

- [Ego-Grounding for Personalized Question-Answering in Egocentric Videos](https://arxiv.org/abs/2604.01966) - Junbin Xiao, Shenglang Zhang, Pengxiang Zhu, and Angela Yao. In CVPR 2026. [[code]](https://github.com/Ryougetsu3606/MyEgo)

- [EgoAVU: Egocentric Audio-Visual Understanding](https://arxiv.org/abs/2602.06139) - Ashish Seth, Xinhao Mei, Changsheng Zhao, Varun Nagaraja, Ernie Chang, Gregory P. Meyer, Gael Le Lan, Yunyang Xiong, Vikas Chandra, Yangyang Shi, Dinesh Manocha, and Zhipeng Cai. In CVPR 2026. [[project page]](https://cs20s030.github.io/EgoAVU/) [[code]](https://github.com/facebookresearch/EgoAVU)

- [EgoSound: Benchmarking Sound Understanding in Egocentric Videos](https://arxiv.org/abs/2602.14122) - Bingwen Zhu, Yuqian Fu, Qiaole Dong, Guolei Sun, Tianwen Qian, Yuzheng Wu, Danda Pani Paudel, Xiangyang Xue, and Yanwei Fu. In CVPR 2026. [[project page]](https://groolegend.github.io/EgoSound/) [[dataset]](https://huggingface.co/datasets/grooLegend/EgoSound)

- [Minerva-Ego: Spatiotemporal Hints for Egocentric Video Understanding](https://arxiv.org/abs/2605.15342) - Arsha Nagrani, Jasper Uijlings, Shyamal Buch, Tobias Weyand, Sudheendra Vijayanarasimhan, Bo Hu, Ramin Mehran, David A Ross, and Cordelia Schmid. In CVPR 2026. [[dataset]](https://github.com/google-deepmind/neptune)

- [Do You See What I Am Pointing At? Gesture-Based Egocentric Video Question Answering](https://arxiv.org/abs/2603.12533) - Yura Choi, Roy Miles, Rolandos Alexandros Potamias, Ismail Elezi, Jiankang Deng, and Stefanos Zafeiriou. In CVPR 2026. [[project page]](https://yuuraa.github.io/papers/choi2026egovqa)

- [Ego-InBetween: Generating Object State Transitions in Ego-Centric Videos](https://arxiv.org/abs/2604.17749) - Mengmeng Ge, Takashi Isobe, Xu Jia, Yanan Sun, Zetong Yang, Weinong Wang, Dong Zhou, Dong Li, Huchuan Lu, and Emad Barsoum. In CVPR 2026.

- [EgoX: Egocentric Video Generation from a Single Exocentric Video](https://arxiv.org/abs/2512.08269) - Taewoong Kang, Kinam Kim, Dohyeon Kim, Minho Park, Junha Hyung, and Jaegul Choo. In CVPR 2026. [[project page]](https://keh0t0.github.io/EgoX) [[code]](https://github.com/DAVIAN-Robotics/EgoX)

- [Generating Humanless Environment Walkthroughs from Egocentric Walking Tour Videos](https://arxiv.org/abs/2603.29036) - Yujin Ham, Junho Kim, Vivek Boominathan, and Guha Balakrishnan. In CVPR 2026.

- [EgoEdit: Dataset, Real-Time Streaming Model, and Benchmark for Egocentric Video Editing](https://arxiv.org/abs/2512.06065) - Runjia Li, Moayed Haji-Ali, Ashkan Mirzaei, Chaoyang Wang, Arpit Sahni, Ivan Skorokhodov, Aliaksandr Siarohin, Tomas Jakab, Junlin Han, Sergey Tulyakov, Philip Torr, and Willi Menapace. In CVPR 2026. [[project page]](https://snap-research.github.io/EgoEdit) [[code]](https://github.com/snap-research/EgoEdit)

- [Mistake Attribution: Fine-Grained Mistake Understanding in Egocentric Videos](https://arxiv.org/abs/2511.20525) - Yayuan Li, Aadit Jain, Filippos Bellos, and Jason J. Corso. In CVPR 2026. [[project page]](https://yayuanli.github.io/MATT/)

- [Egocentric Visibility-Aware Human Pose Estimation](https://arxiv.org/abs/2602.23618) - Peng Dai, Yu Zhang, Yiqiang Feng, Zhen Fan, and Yang Zhang. In CVPR 2026.

- [EgoPoseFormer v2: Accurate Egocentric Human Motion Estimation for AR/VR](https://arxiv.org/abs/2603.04090) - Zhenyu Li, Sai Kumar Dwivedi, Filip Maric, Carlos Chacon, Nadine Bertsch, Filippo Arcadu, et al. In CVPR 2026. [[project page]](https://zhyever.github.io/EgoPoseFormerv2/)

- [Towards Stable Self-Supervised Object Representations in Unconstrained Egocentric Video](https://arxiv.org/abs/2603.13912) - Yuting Tan, Xilong Cheng, Yunxiao Qin, Zhengnan Li, and Jingjing Zhang. In CVPR 2026.

- [EgoXtreme: A Dataset for Robust Object Pose Estimation in Egocentric Views under Extreme Conditions](https://arxiv.org/abs/2603.25135) - Taegyoon Yoon, Yegyu Han, Seojin Ji, Jaewoo Park, Sojeong Kim, Taein Kwon, and Hyung-Sin Kim. In CVPR 2026. [[project page]](https://taegyoun88.github.io/EgoXtreme/) [[code]](https://github.com/taegyoun88/EgoXtreme)

- [Test-time Ego-Exo-centric Adaptation for Action Anticipation via Multi-Label Prototype Growing and Dual-Clue Consistency](https://arxiv.org/abs/2603.09798) - Zhaofeng Shi, Heqian Qiu, Lanxiao Wang, Qingbo Wu, Fanman Meng, Lili Pan, and Hongliang Li. In CVPR 2026. [[code]](https://github.com/ZhaofengSHI/DCPGN)

- [Forecasting 3D Scanpaths in Egocentric Video](https://openaccess.thecvf.com/content/CVPR2026/papers/Ryan_Forecasting_3D_Scanpaths_in_Egocentric_Video_CVPR_2026_paper.pdf) - Fiona Ryan, Ishwarya Ananthabhotla, Yijun Qian, Judy Hoffman, James M. Rehg, Vamsi Krishna Ithapu, and Calvin Murdock. In CVPR 2026.

- [SAVA-X: Ego-to-Exo Imitation Error Detection via Scene-Adaptive View Alignment and Bidirectional Cross View Fusion](https://arxiv.org/abs/2603.12764) - Xiang Li, Heqian Qiu, Lanxiao Wang, Benliu Qiu, Fanman Meng, Linfeng Xu, and Hongliang Li. In CVPR 2026. [[code]](https://github.com/jack1ee/SAVAX)

- [Seeing Conversations: Communication Context Identification in Egocentric Video](https://openaccess.thecvf.com/content/CVPR2026/html/Dorszewski_Seeing_Conversations_Communication_Context_Identification_in_Egocentric_Video_CVPR_2026_paper.html) - Tobias Dorszewski and Jens Hjortkjær. In CVPR 2026.

- [LifeEval: A Multimodal Benchmark for Assistive AI in Egocentric Daily Life Tasks](https://arxiv.org/abs/2603.00490) - Hengjian Gao, Kaiwei Zhang, Shibo Wang, Mingjie Chen, Qihang Cao, Xianfeng Wang, Yucheng Zhu, Xiongkuo Min, Wei Sun, Dandan Zhu, and Guangtao Zhai. In CVPR 2026.

- [SkillSight: Efficient First-Person Skill Assessment with Gaze](https://arxiv.org/abs/2511.19629) - Chi Hsuan Wu, Kumar Ashutosh, and Kristen Grauman. In CVPR 2026.

- [EgoControl: Controllable Egocentric Video Generation via 3D Full-Body Poses](https://arxiv.org/abs/2511.18173) - Enrico Pallotta, Sina Mokhtarzadeh Azar, Lars Doorenbos, Serdar Ozsoy, Umar Iqbal, and Juergen Gall. In CVPR 2026. [[project page]](https://cvg-bonn.github.io/EgoControl/)

- [E-3DPSM: A State Machine for Event-Based Egocentric 3D Human Pose Estimation](https://arxiv.org/abs/2604.08543) - Mayur Deshmukh, Hiroyasu Akada, Helge Rhodin, Christian Theobalt, and Vladislav Golyanik. In CVPR 2026. [[project page]](https://4dqv.mpi-inf.mpg.de/E-3DPSM/)

- [Beyond Caption-Based Queries for Video Moment Retrieval](https://arxiv.org/abs/2603.02363) - David Pujol-Perich, Albert Clapés, Dima Damen, Sergio Escalera, and Michael Wray. In CVPR 2026.

- [Ego2Web: A Web Agent Benchmark Grounded in Egocentric Videos](https://arxiv.org/abs/2603.22529) - Shoubin Yu, Lei Shu, Antoine Yang, Yao Fu, Srinivas Sunkara, Maria Wang, Jindong Chen, Mohit Bansal, and Boqing Gong. In CVPR 2026. [[project page]](https://ego2web.github.io/) [[code]](https://github.com/Yui010206/Ego2Web)

- [HanDyVQA: A Video QA Benchmark for Fine-Grained Hand-Object Interaction Dynamics](https://arxiv.org/abs/2512.00885) - Masatoshi Tateno, Gido Kato, Hirokatsu Kataoka, Yoichi Sato, and Takuma Yagi. In CVPR 2026. [[project page]](https://masatate.github.io/HanDyVQA-project-page/)

- [FunRec: Reconstructing Functional 3D Scenes from Egocentric Interaction Videos](https://openaccess.thecvf.com/content/CVPR2026/html/Delitzas_FUN_REC__Reconstructing_Functional_3D_Scenes_from_Egocentric_Interaction_CVPR_2026_paper.html) - Alexandros Delitzas, Chenyangguang Zhang, Alexey Gavryushin, Tommaso Di Mario, Boyang Sun, Rishabh Dabral, Leonidas Guibas, Christian Theobalt, Marc Pollefeys, Francis Engelmann, and Daniel Barath. In CVPR 2026. [[project page]](https://functionalscenes.github.io/)

- [Object-Shot Enhanced Grounding Network for Egocentric Video](https://arxiv.org/abs/2505.04270) - Yisen Feng, Haoyu Zhang, Meng Liu, Weili Guan, and Liqiang Nie. In CVPR 2025. [[code]](https://github.com/Yisen-Feng/OSGNet)

- [ECBench: Can Multi-modal Foundation Models Understand the Egocentric World? A Holistic Embodied Cognition Benchmark](https://arxiv.org/abs/2501.05031) - Ronghao Dang, Yuqian Yuan, Wenqi Zhang, Yifei Xin, Boqiang Zhang, Long Li, Liuyi Wang, Qinyang Zeng, Xin Li, and Lidong Bing. In CVPR 2025. [[code]](https://github.com/Rh-Dang/ECBench)

- [ANNEXE: Unified Analyzing, Answering, and Pixel Grounding for Egocentric Interaction](https://arxiv.org/abs/2504.01472) - Yuejiao Su, Yi Wang, Qiongyang Hu, Chuang Yang, and Lap-Pui Chau. In CVPR 2025. [[project page]](https://yuggiehk.github.io/annexe/)

- [Understanding Multi-Task Activities from Single-Task Videos](https://openaccess.thecvf.com/content/CVPR2025/html/Shen_Understanding_Multi-Task_Activities_from_Single-Task_Videos_CVPR_2025_paper.html) - Yuhan Shen and Ehsan Elhamifar. In CVPR 2025.

- [Ego4o: Egocentric Human Motion Capture and Understanding from Multi-Modal Input](https://arxiv.org/abs/2504.08449) - Jian Wang, Rishabh Dabral, Diogo Luvizon, Zhe Cao, Lingjie Liu, Thabo Beeler, and Christian Theobalt. In CVPR 2025. [[project page]](https://jianwang-mpi.github.io/ego4o/)

- [Sound Bridge: Associating Egocentric and Exocentric Videos via Audio Cues](https://openaccess.thecvf.com/content/CVPR2025/html/Huang_Sound_Bridge_Associating_Egocentric_and_Exocentric_Videos_via_Audio_Cues_CVPR_2025_paper.html) - Sihong Huang, Jiaxin Wu, Xiaoyong Wei, Yi Cai, Dongmei Jiang, and Yaowei Wang. In CVPR 2025. [[code]](https://github.com/shhuangcoder/SoundBridge)

- [PHGC: Procedural Heterogeneous Graph Completion for Natural Language Task Verification in Egocentric Videos](https://openaccess.thecvf.com/content/CVPR2025/papers/Jiang_PHGC_Procedural_Heterogeneous_Graph_Completion_for_Natural_Language_Task_Verification_CVPR_2025_paper.pdf) - Xun Jiang, Zhiyi Huang, Xing Xu, Jingkuan Song, Fumin Shen, and Heng Tao Shen. In CVPR 2025.

- [Video ReCap: Recursive Captioning of Hour-Long Videos](https://arxiv.org/abs/2402.13250) - Md Mohaiminul Islam, Ngan Ho, Xitong Yang, Tushar Nagarajan, Lorenzo Torresani, and Gedas Bertasius. In CVPR 2024. [[project page]](https://sites.google.com/view/vidrecap)

- [Retrieval-Augmented Egocentric Video Captioning](https://arxiv.org/abs/2401.00789) - Jilan Xu, Yifei Huang, Junlin Hou, Guo Chen, Yuejie Zhang, Rui Feng, and Weidi Xie. In CVPR 2024. [[project page]](https://jazzcharles.github.io/Egoinstructor/)

- [Grounded Question-Answering in Long Egocentric Videos](https://arxiv.org/abs/2312.06505) - Shangzhe Di and Weidi Xie. In CVPR 2024. [[project page]](https://dszdsz.cn/GroundVQA) [[code]](https://github.com/Becomebright/GroundVQA)

- [Learning to Segment Referred Objects from Narrated Egocentric Videos](https://openaccess.thecvf.com/content/CVPR2024/html/Shen_Learning_to_Segment_Referred_Objects_from_Narrated_Egocentric_Videos_CVPR_2024_paper.html) - Yuhan Shen, Huiyu Wang, Xitong Yang, Matt Feiszli, Ehsan Elhamifar, Lorenzo Torresani, and Effrosyni Mavroudi. In CVPR 2024.

- [Error Detection in Egocentric Procedural Task Videos](https://openaccess.thecvf.com/content/CVPR2024/html/Lee_Error_Detection_in_Egocentric_Procedural_Task_Videos_CVPR_2024_paper.html) - Shih-Po Lee, Zijia Lu, Zekun Zhang, Minh Hoai, and Ehsan Elhamifar. In CVPR 2024. [[project page]](https://www.khoury.northeastern.edu/home/eelhami/egoper.htm) [[code]](https://github.com/robert80203/EgoPER_official)

- [Progress-Aware Online Action Segmentation for Egocentric Procedural Task Videos](https://openaccess.thecvf.com/content/CVPR2024/html/Shen_Progress-Aware_Online_Action_Segmentation_for_Egocentric_Procedural_Task_Videos_CVPR_2024_paper.html) - Yuhan Shen and Ehsan Elhamifar. In CVPR 2024. [[code]](https://github.com/Yuhan-Shen/ProTAS)

- [TIM: A Time Interval Machine for Audio-Visual Action Recognition](https://arxiv.org/abs/2404.05559) - Jacob Chalk, Jaesung Huh, Evangelos Kazakos, Andrew Zisserman, and Dima Damen. In CVPR 2024. [[project page]](https://jacobchalk.github.io/TIM-Project) [[code]](https://github.com/JacobChalk/TIM)

- [Real-Time Simulated Avatar from Head-Mounted Sensors](https://arxiv.org/abs/2403.06862) - Zhengyi Luo, Jinkun Cao, Rawal Khirodkar, Alexander Winkler, Jing Huang, Kris Kitani, and Weipeng Xu. In CVPR 2024. [[project page]](https://www.zhengyiluo.com/SimXR/)

- [Mocap Everyone Everywhere: Lightweight Motion Capture With Smartwatches and a Head-Mounted Camera](https://arxiv.org/abs/2401.00847) - Jiye Lee and Hanbyul Joo. In CVPR 2024. [[project page]](https://jiyewise.github.io/projects/MocapEvery/)

- [Fusing Personal and Environmental Cues for Identification and Segmentation of First-Person Camera Wearers in Third-Person Views](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_Fusing_Personal_and_Environmental_Cues_for_Identification_and_Segmentation_of_CVPR_2024_paper.html) - Ziwei Zhao, Yuchen Wang, Chuhua Wang, and David Crandall. In CVPR 2024. [[code]](https://github.com/ziweizhao1993/PEN)

- [Learning Spatial Features from Audio-Visual Correspondence in Egocentric Videos](https://arxiv.org/abs/2307.04760) - Sagnik Majumder, Ziad Al-Halah, and Kristen Grauman. In CVPR 2024. [[project page]](http://vision.cs.utexas.edu/projects/ego_av_corr)

- [REWIND: Real-Time Egocentric Whole-Body Motion Diffusion with Exemplar-Based Identity Conditioning](https://arxiv.org/abs/2504.04956) - Jihyun Lee, Weipeng Xu, Alexander Richard, Shih-En Wei, Shunsuke Saito, Shaojie Bai, Te-Li Wang, Minhyuk Sung, Tae-Kyun Kim, and Jason Saragih. In CVPR 2025. [[project page]](https://jyunlee.github.io/projects/rewind/)

- [FRAME: Floor-aligned Representation for Avatar Motion from Egocentric Video](https://arxiv.org/abs/2503.23094) - Andrea Boscolo Camiletto, Jian Wang, Eduardo Alvarado, Rishabh Dabral, Thabo Beeler, Marc Habermann, and Christian Theobalt. In CVPR 2025. [[project page]](https://vcai.mpi-inf.mpg.de/projects/FRAME/) [[code]](https://github.com/abcamiletto/frame)

- [EgoLM: Multi-Modal Language Model of Egocentric Motions](https://arxiv.org/abs/2409.18127) - Fangzhou Hong, Vladimir Guzov, Hyo Jin Kim, Yuting Ye, Richard Newcombe, Ziwei Liu, and Lingni Ma. In CVPR 2025. [[project page]](https://hongfz16.github.io/projects/EgoLM)

- [Estimating Body and Hand Motion in an Ego-sensed World](https://arxiv.org/abs/2410.03665) - Brent Yi, Vickie Ye, Maya Zheng, Yunqi Li, Lea Müller, Georgios Pavlakos, Yi Ma, Jitendra Malik, and Angjoo Kanazawa. In CVPR 2025. [[project page]](https://egoallo.github.io/)

- [Dyn-HaMR: Recovering 4D Interacting Hand Motion from a Dynamic Camera](https://arxiv.org/abs/2412.12861) - Zhengdi Yu, Stefanos Zafeiriou, and Tolga Birdal. In CVPR 2025. [[project page]](https://dyn-hamr.github.io/)

- [EgoPressure: A Dataset for Hand Pressure and Pose Estimation in Egocentric Vision](https://arxiv.org/abs/2409.02224) - Yiming Zhao, Taein Kwon, Paul Streli, Marc Pollefeys, and Christian Holz. In CVPR 2025. [[project page]](https://yiming-zhao.github.io/EgoPressure/)

- [HaWoR: World-Space Hand Motion Reconstruction from Egocentric Videos](https://arxiv.org/abs/2501.02973) - Jinglei Zhang, Jiankang Deng, Chao Ma, and Rolandos Alexandros Potamias. In CVPR 2025. [[project page]](https://hawor-project.github.io/)

- [HOT3D: Hand and Object Tracking in 3D from Egocentric Multi-View Videos](https://arxiv.org/abs/2411.19167) - Prithviraj Banerjee, Sindi Shkodrani, Pierre Moulon, Shreyas Hampali, Shangchen Han, Fan Zhang, et al. In CVPR 2025. [[project page]](https://facebookresearch.github.io/hot3d/)

- [ParaHome: Parameterizing Everyday Home Activities Towards 3D Generative Modeling of Human-Object Interactions](https://arxiv.org/abs/2401.10232) - Jeonghwan Kim, Jisoo Kim, Jeonghyeon Na, and Hanbyul Joo. In CVPR 2025. [[code]](https://github.com/canoneod/ParaHome)

- [Generating 6DoF Object Manipulation Trajectories from Action Description in Egocentric Vision](https://arxiv.org/abs/2506.03605) - Tomoya Yoshida, Shuhei Kurita, Taichi Nishimura, and Shinsuke Mori. In CVPR 2025. [[project page]](https://biscue5.github.io/egoscaler-project-page/) [[code]](https://github.com/Biscue5/EgoScaler)

- [FIction: 4D Future Interaction Prediction from Video](https://arxiv.org/abs/2412.00932) - Kumar Ashutosh, Georgios Pavlakos, and Kristen Grauman. In CVPR 2025. [[code]](https://github.com/thechargedneutron/FIction)

- [Gazing Into Missteps: Leveraging Eye-Gaze for Unsupervised Mistake Detection in Egocentric Videos of Skilled Human Activities](https://arxiv.org/abs/2406.08379) - Michele Mazzamuto, Antonino Furnari, Yoichi Sato, and Giovanni Maria Farinella. In CVPR 2025.

- [HD-EPIC: A Highly-Detailed Egocentric Video Dataset](https://arxiv.org/abs/2502.04144) - Toby Perrett, Ahmad Darkhalil, Saptarshi Sinha, Omar Emara, Sam Pollard, Kranti Parida, et al. In CVPR 2025. [[project page]](https://hd-epic.github.io/)

- [GEM: A Generalizable Ego-Vision Multimodal World Model for Fine-Grained Ego-Motion, Object Dynamics, and Scene Composition Control](https://openaccess.thecvf.com/content/CVPR2025/papers/Hassan_GEM_A_Generalizable_Ego-Vision_Multimodal_World_Model_for_Fine-Grained_Ego-Motion_CVPR_2025_paper.pdf) - Mariam Hassan, Sebastian Stapf, Ahmad Rahimi, et al. In CVPR 2025. [[project page]](https://vita-epfl.github.io/GEM.github.io/) [[code]](https://github.com/vita-epfl/GEM)

- [DIV-FF: Dynamic Image-Video Feature Fields for Environment Understanding in Egocentric Videos](https://arxiv.org/abs/2503.08344) - Lorenzo Mur-Labadia, Jose J. Guerrero, and Ruben Martinez-Cantin. In CVPR 2025. [[code]](https://github.com/lmur98/DIV_FF_CVPR)

- [Layered Motion Fusion: Lifting Motion Segmentation to 3D in Egocentric Videos](https://arxiv.org/abs/2506.05546) - Vadim Tschernezki, Diane Larlus, Iro Laina, and Andrea Vedaldi. In CVPR 2025.

- [EgoLife: Towards Egocentric Life Assistant](https://arxiv.org/abs/2503.03803) - Jingkang Yang, Shuai Liu, Hongming Guo, et al. In CVPR 2025. [[code]](https://github.com/EvolvingLMMs-Lab/EgoLife)

- [EgoTextVQA: Towards Egocentric Scene-Text Aware Video Question Answering](https://arxiv.org/abs/2502.07411) - Sheng Zhou, Junbin Xiao, Qingyun Li, Yicong Li, Xun Yang, Dan Guo, Meng Wang, Tat-Seng Chua, and Angela Yao. In CVPR 2025. [[code]](https://github.com/zhousheng97/EgoTextVQA)

- [Omnia de EgoTempo: Benchmarking Temporal Understanding of Multi-Modal LLMs in Egocentric Videos](https://arxiv.org/abs/2503.13646) - Chiara Plizzari, Alessio Tonioni, Yongqin Xian, Achin Kulshrestha, and Federico Tombari. In CVPR 2025. [[code]](https://github.com/google-research-datasets/egotempo)

- [Bootstrap Your Own Views: Masked Ego-Exo Modeling for Fine-grained View-invariant Video Representations](https://arxiv.org/abs/2503.19706) - Jungin Park, Jiyoung Lee, and Kwanghoon Sohn. In CVPR 2025. [[code]](https://github.com/park-jungin/byov)

- [Viewpoint Rosetta Stone: Unlocking Unpaired Ego-Exo Videos for View-invariant Representation Learning](https://openaccess.thecvf.com/content/CVPR2025/papers/Luo_Viewpoint_Rosetta_Stone_Unlocking_Unpaired_Ego-Exo_Videos_for_View-invariant_Representation_CVPR_2025_paper.pdf) - Mi Luo, Zihui Xue, Alex Dimakis, and Kristen Grauman. In CVPR 2025. [[project page]](https://vision.cs.utexas.edu/projects/ViewpointRosetta/)

- [Which Viewpoint Shows it Best? Language for Weakly Supervising View Selection in Multi-view Instructional Videos](https://arxiv.org/abs/2411.08753) - Sagnik Majumder, Tushar Nagarajan, Ziad Al-Halah, Reina Pradhan, and Kristen Grauman. In CVPR 2025. [[project page]](https://vision.cs.utexas.edu/projects/which-view-shows-it-best/)

- [EventEgo3D: 3D Human Motion Capture from Egocentric Event Streams](https://arxiv.org/abs/2404.08640) - Christen Millerdurai, Hiroyasu Akada, Jian Wang, Diogo Luvizon, Christian Theobalt, and Vladislav Golyanik. In CVPR 2024. [[project page]](https://4dqv.mpi-inf.mpg.de/EventEgo3D/)

- [3D Human Pose Perception from Egocentric Stereo Videos](https://arxiv.org/abs/2401.00889) - Hiroyasu Akada, Jian Wang, Vladislav Golyanik, and Christian Theobalt. In CVPR 2024. [[code]](https://github.com/hiroyasuakada/3D-Human-Pose-Perception-from-Egocentric-Stereo-Videos)

- [Egocentric Whole-Body Motion Capture with FisheyeViT and Diffusion-Based Motion Refinement](https://arxiv.org/abs/2311.16495) - Jian Wang, Zhe Cao, Diogo Luvizon, Lingjie Liu, Kripasindhu Sarkar, Danhang Tang, Thabo Beeler, and Christian Theobalt. In CVPR 2024. [[code]](https://github.com/jianwang-mpi/egowholemocap)

- [Attention-Propagation Network for Egocentric Heatmap to 3D Pose Lifting](https://arxiv.org/abs/2402.18330) - Taeho Kang and Youngki Lee. In CVPR 2024. [[code]](https://github.com/tho-kn/EgoTAP)

- [Single-to-Dual-View Adaptation for Egocentric 3D Hand Pose Estimation](https://arxiv.org/abs/2403.04381) - Ruicong Liu, Takehiko Ohkawa, Mingfang Zhang, and Yoichi Sato. In CVPR 2024. [[code]](https://github.com/ut-vision/S2DHand)

- [SoundingActions: Learning How Actions Sound from Narrated Egocentric Videos](https://arxiv.org/abs/2404.05206) - Changan Chen, Kumar Ashutosh, Rohit Girdhar, David Harwath, and Kristen Grauman. In CVPR 2024. [[project page]](https://vision.cs.utexas.edu/projects/soundingactions)

- [X-MIC: Cross-Modal Instance Conditioning for Egocentric Action Generalization](https://arxiv.org/abs/2403.19811) - Anna Kukleva, Fadime Sener, Edoardo Remelli, Bugra Tekin, Eric Sauser, Bernt Schiele, and Shugao Ma. In CVPR 2024. [[code]](https://github.com/annusha/xmic)

- [Instance Tracking in 3D Scenes from Egocentric Videos](https://arxiv.org/abs/2312.04117) - Yunhan Zhao, Haoyu Ma, Shu Kong, and Charless Fowlkes. In CVPR 2024. [[code]](https://github.com/IT3DEgo/IT3DEgo)

- [Summarize the Past to Predict the Future: Natural Language Descriptions of Context Boost Multimodal Object Interaction Anticipation](https://arxiv.org/abs/2301.09209) - Razvan-George Pasca, Alexey Gavryushin, Muhammad Hamza, Yen-Ling Kuo, Kaichun Mo, Luc Van Gool, Otmar Hilliges, and Xi Wang. In CVPR 2024. [[project page]](https://eth-ait.github.io/transfusion-proj/)

- [The Audio-Visual Conversational Graph: From an Egocentric-Exocentric Perspective](https://arxiv.org/abs/2312.12870) - Wenqi Jia, Miao Liu, Hao Jiang, Ishwarya Ananthabhotla, James M. Rehg, Vamsi Krishna Ithapu, and Ruohan Gao. In CVPR 2024. [[project page]](https://vjwq.github.io/AV-CONV/)

- [EgoThink: Evaluating First-Person Perspective Thinking Capability of Vision-Language Models](https://arxiv.org/abs/2311.15596) - Sijie Cheng, Zhicheng Guo, Jingwen Wu, Kechen Fang, Peng Li, Huaping Liu, and Yang Liu. In CVPR 2024. [[code]](https://github.com/AdaCheng/EgoThink)

- [EgoExoLearn: A Dataset for Bridging Asynchronous Ego- and Exo-centric View of Procedural Activities in Real World](https://arxiv.org/abs/2403.16182) - Yifei Huang, Guo Chen, Jilan Xu, Mingfang Zhang, Lijin Yang, Baoqi Pei, et al. In CVPR 2024. [[code]](https://github.com/OpenGVLab/EgoExoLearn)

- [EgoGen: An Egocentric Synthetic Data Generator](https://arxiv.org/pdf/2401.08739) -  Gen Li, Kaifeng Zhao, Siwei Zhang, Xiaozhong Lyu, Mihai Dusmanu, Yan Zhang, Marc Pollefeys, and Siyu Tang. In CVPR 2024. [[project page]](https://ego-gen.github.io/)

- [A Backpack Full of Skills: Egocentric Video Understanding with Diverse Task Perspectives](https://arxiv.org/pdf/2403.03037) - Simone Alberto Peirone, Francesca Pistilli, Antonio Alliegro, and Giuseppe Averta. In CVPR 2024.

- [Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives](https://arxiv.org/abs/2311.18259) - Kristen Grauman, Andrew Westbury, Lorenzo Torresani, Kris Kitani, Jitendra Malik, Triantafyllos Afouras, Kumar Ashutosh, Vijay Baiyya, Siddhant Bansal, Bikram Boote, Eugene Byrne, Zach Chavis, Joya Chen, Feng Cheng, Fu-Jen Chu, Sean Crane, Avijit Dasgupta, Jing Dong, Maria Escobar, Cristhian Forigua, Abrham Gebreselasie, Sanjay Haresh, Jing Huang, Md Mohaiminul Islam, Suyog Jain, Rawal Khirodkar, Devansh Kukreja, Kevin J Liang, Jia-Wei Liu, Sagnik Majumder, Yongsen Mao, Miguel Martin, Effrosyni Mavroudi, Tushar Nagarajan, Francesco Ragusa, Santhosh Kumar Ramakrishnan, Luigi Seminara, Arjun Somayazulu, Yale Song, Shan Su, Zihui Xue, Edward Zhang, Jinxu Zhang, Angela Castillo, Changan Chen, Xinzhu Fu, Ryosuke Furuta, Cristina Gonzalez, Prince Gupta, Jiabo Hu, Yifei Huang, Yiming Huang, Weslie Khoo, Anush Kumar, Robert Kuo, Sach Lakhavani, Miao Liu, Mi Luo, Zhengyi Luo, Brighid Meredith, Austin Miller, Oluwatumininu Oguntola, Xiaqing Pan, Penny Peng, Shraman Pramanick, Merey Ramazanova, Fiona Ryan, Wei Shan, Kiran Somasundaram, Chenan Song, Audrey Southerland, Masatoshi Tateno, Huiyu Wang, Yuchen Wang, Takuma Yagi, Mingfei Yan, Xitong Yang, Zecheng Yu, Shengxin Cindy Zha, Chen Zhao, Ziwei Zhao, Zhifan Zhu, Jeff Zhuo, Pablo Arbelaez, Gedas Bertasius, David Crandall, Dima Damen, Jakob Engel, Giovanni Maria Farinella, Antonino Furnari, Bernard Ghanem, Judy Hoffman, C. V. Jawahar, Richard Newcombe, Hyun Soo Park, James M. Rehg, Yoichi Sato, Manolis Savva, Jianbo Shi, Mike Zheng Shou, and Michael Wray. In CVPR 2024. [[project page]](https://ego-exo4d-data.org)

- [PREGO: online mistake detection in PRocedural EGOcentric videos](https://arxiv.org/pdf/2404.01933) - Alessandro Flaborea, Guido Maria D'Amely di Melendugno, Leonardo Plini, Luca Scofano, Edoardo De Matteis, Antonino Furnari, Giovanni Maria Farinella, and Fabio Galasso. In CVPR 2024.

- [Action Scene Graphs for Long-Form Understanding of Egocentric Videos](https://arxiv.org/pdf/2312.03391) - Ivan Rodin, Antonino Furnari, Kyle Min, Subarna Tripathi, and Giovanni Maria Farinella. In CVPR 2024.

- [Therbligs In Action: Video Understanding through Motion Primitives](https://arxiv.org/pdf/2304.03631.pdf) - Eadom Dessalene, Michael Maynord, Cornelia Fermu ̈ller, Yiannis Aloimonos. In CVPR 2023. [[project page]](https://prg.cs.umd.edu/Therbligs)

- [Hierarchical Temporal Transformer for 3D Hand Pose Estimation and Action Recognition from Egocentric RGB Videos](https://arxiv.org/pdf/2209.09484.pdf) - Yilin Wen, Hao Pan, Lei Yang, Jia Pan, Taku Komura, Wenping Wang. In CVPR 2023. [[Code]](https://github.com/fylwen/HTT)

- [MMG-Ego4D: Multimodal Generalization in Egocentric Action Recognition](https://openaccess.thecvf.com/content/CVPR2023/papers/Gong_MMG-Ego4D_Multimodal_Generalization_in_Egocentric_Action_Recognition_CVPR_2023_paper.pdf) - Xinyu Gong, Sreyas Mohan, Naina Dhingra, Jean-Charles Bazin, YILEI LI, Zhangyang Wang, Rakesh Ranjan. In CVPR 2023.

- [AssemblyHands: Towards Egocentric Activity Understanding via 3D Hand Pose Estimation](https://assemblyhands.github.io) - Takehiko Ohkawa, Kun He, Fadime Sener, Tomas Hodan, LUAN TRAN, Cem Keskin. In CVPR 2023.

- [Scene-aware Egocentric 3D Human Pose Estimation](https://arxiv.org/pdf/2212.11684.pdf) - Jian Wang, Diogo Luvizon, Weipeng Xu, Lingjie Liu, Kripasindhu Sarkar, Christian Theobalt. In CVPR 2023.

- [Tracking Multiple Deformable Objects in Egocentric Videos](https://mingzhenhuang.com/projects/detracker.html) - Mingzhen Huang, Xiaoxing Li, Jun Hu, Honghong Peng, Siwei Lyu. In CVPR 2023.

- [Egocentric Audio-Visual Object Localization](https://research.facebook.com/publications/egocentric-audio-visual-object-localization/) - Chao Huang · Yapeng Tian · Anurag Kumar · Chenliang Xu. In CVPR 2023. [[project page]](https://research.facebook.com/publications/egocentric-audio-visual-object-localization/)

- [Balanced Spherical Grid for Egocentric View Synthesis](https://arxiv.org/pdf/2303.12408.pdf) - Changwoon Choi · Sang Min Kim · Young Min Kim. In CVPR 2023. [[code]](https://github.com/changwoonchoi/EgoNeRF)

- [Egocentric Video Task Translation](https://arxiv.org/pdf/2212.06301.pdf) - Zihui Xue · Yale Song · Kristen Grauman · Lorenzo Torresani. In CVPR 2023.

- [Egocentric Auditory Attention Localization in Conversations](https://arxiv.org/pdf/2303.16024.pdf) - Fiona Ryan · Hao Jiang · Abhinav Shukla · James Rehg · Vamsi Krishna Ithapu. In CVPR 2023. [[project page]](https://fkryan.github.io/saal)

- [Chat2Map: Efficient Scene Mapping from Multi-Ego Conversations](https://arxiv.org/pdf/2301.02184.pdf) - Sagnik Majumder · Hao Jiang · Pierre Moulon · Ethan Henderson · Paul Calamia · Kristen Grauman · Vamsi Krishna Ithapu. In CVPR 2023.

- [ARCTIC: A Dataset for Dexterous Bimanual Hand-Object Manipulation](https://arctic.is.tue.mpg.de) - Zicong Fan, Omid Taheri, Dimitrios Tzionas, Muhammed Kocabas, Manuel Kaufmann, Michael J. Black, Otmar Hilliges. In CVPR 2023. [[code]](https://github.com/zc-alexfan/arctic)

- [Learning Video Representations from Large Language Models](https://arxiv.org/pdf/2212.04501.pdf; https://facebookresearch.github.io/LaViLa) - Yue Zhao, Ishan Misra, Philipp Krähenbühl, Rohit Girdhar. In CVPR 2023. [[project page]](https://facebookresearch.github.io/LaViLa/) [[code]](https://github.com/facebookresearch/LaViLa) [[demo]](https://huggingface.co/spaces/nateraw/lavila)

- [Ego4D: Around the World in 3,000 Hours of Egocentric Video](https://arxiv.org/abs/2110.07058) - Kristen Grauman, Andrew Westbury, Eugene Byrne, Zachary Chavis, Antonino Furnari, Rohit Girdhar, Jackson Hamburger, Hao Jiang, Miao Liu, Xingyu Liu, Miguel Martin, Tushar Nagarajan, Ilija Radosavovic, Santhosh Kumar Ramakrishnan, Fiona Ryan, Jayant Sharma, Michael Wray, Mengmeng Xu, Eric Zhongcong Xu, Chen Zhao, Siddhant Bansal, Dhruv Batra, Vincent Cartillier, Sean Crane, Tien Do, Morrie Doulaty, Akshay Erapalli, Christoph Feichtenhofer, Adriano Fragomeni, Qichen Fu, Christian Fuegen, Abrham Gebreselasie, Cristina Gonzalez, James Hillis, Xuhua Huang, Yifei Huang, Wenqi Jia, Weslie Khoo, Jachym Kolar, Satwik Kottur, Anurag Kumar, Federico Landini, Chao Li, Yanghao Li, Zhenqiang Li, Karttikeya Mangalam, Raghava Modhugu, Jonathan Munro, Tullie Murrell, Takumi Nishiyasu, Will Price, Paola Ruiz Puentes, Merey Ramazanova, Leda Sari, Kiran Somasundaram, Audrey Southerland, Yusuke Sugano, Ruijie Tao, Minh Vo, Yuchen Wang, Xindi Wu, Takuma Yagi, Yunyi Zhu, Pablo Arbelaez, David Crandall, Dima Damen, Giovanni Maria Farinella, Bernard Ghanem, Vamsi Krishna Ithapu, C.V. Jawahar, Hanbyul Joo, Kris Kitani, Haizhou Li, Richard Newcombe, Aude Oliva, Hyun Soo Park, James M. Rehg, Yoichi Sato, Jianbo Shi, Mike Zheng Shou, Antonio Torralba, Lorenzo Torresani, Mingfei Yan, and Jitendra Malik. In CVPR 2022. [[Github]](https://github.com/EGO4D) [[project page]](https://ego4d-data.org) [[video]](https://drive.google.com/file/d/1oknfQIH9w1rXy6I1j5eUE6Cqh96UwZ4L/view?usp=sharing)

- [HOI4D: A 4D Egocentric Dataset for Category-Level Human-Object Interaction](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_HOI4D_A_4D_Egocentric_Dataset_for_Category-Level_Human-Object_Interaction_CVPR_2022_paper.pdf) - Yunze Liu, Yun Liu, Che Jiang, Kangbo Lyu, Weikang Wan, Hao Shen, Boqiang Liang, Zhoujie Fu, He Wang, Li Yi. In CVPR 2022. [[project page]](https://hoi4d.github.io/) [[video]](https://youtu.be/yzNqm0JISU0)

- [E2(GO)MOTION: Motion Augmented Event Stream for Egocentric Action Recognition](https://openaccess.thecvf.com/content/CVPR2022/papers/Plizzari_E2GOMOTION_Motion_Augmented_Event_Stream_for_Egocentric_Action_Recognition_CVPR_2022_paper.pdf) - Chiara Plizzari, Mirco Planamente, Gabriele Goletto, Marco Cannici, Emanuele Gusso, Matteo Matteucci, Barbara Caputo. In CVPR 2022.

- [Estimating Egocentric 3D Human Pose in the Wild with External Weak Supervision](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Estimating_Egocentric_3D_Human_Pose_in_the_Wild_With_External_CVPR_2022_paper.pdf) - Jian Wang, Lingjie Liu, Weipeng Xu, Kripasindhu Sarkar, Diogo Luvizon, Christian Theobalt. In CVPR 2022. [[project page]](https://web.archive.org/web/20240726094113/https://people.mpi-inf.mpg.de/~jianwang/projects/egopw/)

- [Robust Egocentric Photo-realistic Facial Expression Transfer for Virtual Reality](https://openaccess.thecvf.com/content/CVPR2022/papers/Jourabloo_Robust_Egocentric_Photo-Realistic_Facial_Expression_Transfer_for_Virtual_Reality_CVPR_2022_paper.pdf) - Amin Jourabloo, Fernando De la Torre, Jason Saragih, Shih-En Wei, Stephen Lombardi, Te-Li Wang, Danielle Belko, Autumn Trimble, Hernan Badino. In CVPR 2022.

- [Joint Hand Motion and Interaction Hotspots Prediction from Egocentric Videos](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Joint_Hand_Motion_and_Interaction_Hotspots_Prediction_From_Egocentric_Videos_CVPR_2022_paper.pdf) - Shaowei Liu, Subarna Tripathi, Somdeb Majumdar, Xiaolong Wang. In CVPR 2022. [[project page]](https://stevenlsw.github.io/hoi-forecast/) [[video]](https://youtu.be/uCUTK9WOhpE) [[slides]](https://drive.google.com/file/d/1N9t4pIZX9usV1QGxTj6nPHQIqZjpf3qg/view?usp=sharing)

- [A Hybrid Egocentric Activity Anticipation Framework via Memory-Augmented Recurrent and One-shot Representation Forecasting](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_A_Hybrid_Egocentric_Activity_Anticipation_Framework_via_Memory-Augmented_Recurrent_and_CVPR_2022_paper.pdf) - Tianshan Liu and Kin-Man Lam. In CVPR 2022.

- [Egocentric Deep Multi-Channel Audio-Visual Active Speaker Localization](https://openaccess.thecvf.com/content/CVPR2022/papers/Jiang_Egocentric_Deep_Multi-Channel_Audio-Visual_Active_Speaker_Localization_CVPR_2022_paper.pdf) - Hao Jiang, Calvin Murdock, Vamsi Krishna Ithapu. In CVPR 2022.

- [Egocentric Scene Understanding via Multimodal Spatial Rectifier](https://openaccess.thecvf.com/content/CVPR2022/papers/Do_Egocentric_Scene_Understanding_via_Multimodal_Spatial_Rectifier_CVPR_2022_paper.pdf) - Tien Do, Khiem Vuong, Hyun Soo Park. In CVPR 2022.

- [Egocentric Prediction of Action Target in 3D](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Egocentric_Prediction_of_Action_Target_in_3D_CVPR_2022_paper.pdf) - Yiming Li, Ziang Cao, Andrew Liang, Benjamin Liang, Luoyao Chen, Hang Zhao, Chen Feng. In CVPR 2022.

- [Assembly101: A Large-Scale Multi-View Video Dataset for Understanding Procedural Activities](https://arxiv.org/abs/2203.14712) - Fadime Sener, Dibyadip Chatterjee, Daniel Shelepov, Kun He, Dipika Singhania, Robert Wang, and Angela Yao. In CVPR 2022. [[project page]](https://assembly-101.github.io/)

- [Ego-Exo: Transferring Visual Representations From Third-Person to First-Person Videos](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Ego-Exo_Transferring_Visual_Representations_From_Third-Person_to_First-Person_Videos_CVPR_2021_paper.pdf) - Yanghao Li, Tushar Nagarajan, Bo Xiong, Kristen Grauman. In CVPR 2021. [[code]](https://github.com/facebookresearch/Ego-Exo)

- [Multi-Modal Domain Adaptation for Fine-Grained Action Recognition](https://openaccess.thecvf.com/content_CVPR_2020/papers/Munro_Multi-Modal_Domain_Adaptation_for_Fine-Grained_Action_Recognition_CVPR_2020_paper.pdf) - Jonathan Munro and Dima Damen. In CVPR 2020. [[project page]](https://jonmun.github.io/mmsada/) [[code]](https://github.com/jonmun/MM-SADA-code)

- [Generalizing Hand Segmentation in Egocentric Videos with Uncertainty-Guided Model Adaptation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_Generalizing_Hand_Segmentation_in_Egocentric_Videos_With_Uncertainty-Guided_Model_Adaptation_CVPR_2020_paper.pdf) - Minjie Cai, Feng Lu, and Yoichi Sato. In CVPR 2020. [[code]](https://github.com/cai-mj/UMA)

- [Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior](https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf) - Osama Makansi, Ozgun Cicek, Kevin Buchicchio, and Thomas Brox. In CVPR 2020. [[demo]](https://youtu.be/_9Ml5IFwbSY) [[code]](https://github.com/lmb-freiburg/FLN-EPN-RPN) [[project page]](https://lmb.informatik.uni-freiburg.de/Publications/2020/MCBB20/)

- [EGO-TOPO: Environment Affordances from Egocentric Video](https://openaccess.thecvf.com/content_CVPR_2020/papers/Nagarajan_Ego-Topo_Environment_Affordances_From_Egocentric_Video_CVPR_2020_paper.pdf) - Tushar Nagarajan, Yanghao Li, Christoph Feichtenhofer, and Kristen Grauman. In CVPR 2020. [[project page]](http://vision.cs.utexas.edu/projects/ego-topo/) [[demo]](http://vision.cs.utexas.edu/projects/ego-topo/demo.html)

- [You2Me: Inferring Body Pose in Egocentric Video via First and Second Person Interactions](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ng_You2Me_Inferring_Body_Pose_in_Egocentric_Video_via_First_and_CVPR_2020_paper.pdf) - Evonne Ng, Donglai Xiang, Hanbyul Joo, and Kristen Grauman. In CVPR 2020. [[demo]](http://vision.cs.utexas.edu/projects/you2me/demo.mp4) [[project page]](http://vision.cs.utexas.edu/projects/you2me/) [[dataset]](https://github.com/facebookresearch/you2me/tree/master/data#) [[code]](https://github.com/facebookresearch/you2me#)

- [LSTA: Long Short-Term Attention for Egocentric Action Recognition](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sudhakaran_LSTA_Long_Short-Term_Attention_for_Egocentric_Action_Recognition_CVPR_2019_paper.pdf) - Swathikiran Sudhakaran, Sergio Escalera, and Oswald Lanz. In CVPR 2019. [[code]](https://github.com/swathikirans/LSTA)

- [H+O: Unified Egocentric Recognition of 3D Hand-Object Poses and Interactions](https://openaccess.thecvf.com/content_CVPR_2019/papers/Tekin_HO_Unified_Egocentric_Recognition_of_3D_Hand-Object_Poses_and_Interactions_CVPR_2019_paper.pdf) - Bugra Tekin, Federica Bogo, and Marc Pollefeys. In CVPR 2019. [[video]](https://youtu.be/ko6kNZ9DuAk?t=3240)

- [Deep Dual Relation Modeling for Egocentric Interaction Recognition](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Deep_Dual_Relation_Modeling_for_Egocentric_Interaction_Recognition_CVPR_2019_paper.pdf) - Haoxin Li, Yijun Cai, and Wei-Shi Zheng. In CVPR 2019.

- [Egocentric Activity Recognition on a Budget](https://openaccess.thecvf.com/content_cvpr_2018/papers/Possas_Egocentric_Activity_Recognition_CVPR_2018_paper.pdf) - Rafael Possas, Sheila Pinto Caceres, and Fabio Ramos. In CVPR 2018. [[demo]](https://youtu.be/GBo4sFNzhtU)

- [From Lifestyle VLOGs to Everyday Interaction](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0733.pdf) - David F. Fouhey, Weicheng Kuo, Alexei A. Efros, and Jitendra Malik. In CVPR 2018. [[project page]](https://web.archive.org/web/20241102024857/https://web.eecs.umich.edu/~fouhey/2017/VLOG/index.html)

- [Actor and Observer: Joint Modeling of First and Third-Person Videos](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sigurdsson_Actor_and_Observer_CVPR_2018_paper.pdf) - Gunnar A. Sigurdsson, Abhinav Gupta, Cordelia Schmid, Ali Farhadi, and Karteek Alahari. In CVPR 2018. [[code]](https://github.com/gsig/actor-observer)

- [Analysis of Hand Segmentation in the Wild](https://arxiv.org/pdf/1803.03317) - Aisha Urooj Khan and Ali Borji. In CVPR 2018.

- [First-Person Hand Action Benchmark with RGB-D Videos and 3D Hand Pose Annotations](https://openaccess.thecvf.com/content_cvpr_2018/papers/Garcia-Hernando_First-Person_Hand_Action_CVPR_2018_paper.pdf) - Guillermo Garcia-Hernando, Shanxin Yuan, Seungryul Baek, and Tae-Kyun Kim. In CVPR 2018. [[project page]](https://guiggh.github.io/publications/first-person-hands/) [[code]](https://github.com/guiggh/hand_pose_action)

- [Egocentric Basketball Motion Planning from a Single First-Person Image](https://openaccess.thecvf.com/content_cvpr_2018/papers/Bertasius_Egocentric_Basketball_Motion_CVPR_2018_paper.pdf) - Gedas Bertasius, Aaron Chan, and Jianbo Shi. In CVPR 2018. [[demo]](https://youtu.be/wRRRl4QsUQg)

- [Query-focused video summarization: Dataset, evaluation, and a memory network based approach](https://openaccess.thecvf.com/content_cvpr_2017/papers/Sharghi_Query-Focused_Video_Summarization_CVPR_2017_paper.pdf) - Aidean Sharghi, Jacob S. Laurel and Boqing Gong. In CVPR 2017.

- [Deep future gaze: Gaze anticipation on egocentric videos using adversarial networks](https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Deep_Future_Gaze_CVPR_2017_paper.pdf) - Mengmi Zhang, Keng Teck Ma, Joo Hwee Lim, Qi Zhao, and Jiashi Feng. In CVPR 2017. [[code]](https://github.com/Mengmi/deepfuturegaze_gan)

- [Jointly Learning Energy Expenditures and Activities using Egocentric Multimodal Signals](https://openaccess.thecvf.com/content_cvpr_2017/papers/Nakamura_Jointly_Learning_Energy_CVPR_2017_paper.pdf) - Katsuyuki Nakamura, Serena Yeung, Alexandre Alahi, and Li Fei-Fei. In CVPR 2017.

- [Seeing Invisible Poses: Estimating 3D Body Pose from Egocentric Video](https://openaccess.thecvf.com/content_cvpr_2017/papers/Jiang_Seeing_Invisible_Poses_CVPR_2017_paper.pdf) - Hao Jiang and Kristen Grauman. In CVPR 2017.

- [First Person Action Recognition Using Deep Learned Descriptors](https://www.cv-foundation.org/openaccess/content_cvpr_2016/app/S12-15.pdf) - Suriya Singh, Chetan Arora, and C.V. Jawahar. In CVPR 2016. [[project page]](http://cvit.iiit.ac.in/research/projects/cvit-projects/first-person-action-recognition) [[code]](https://github.com/suriyasingh/EgoConvNet)

- [Going deeper into first-person activity recognition](http://www.cs.cmu.edu/~kkitani/pdf/MFK-CVPR2016.pdf) - Minghuang Ma, Haoqi Fan, and Kris M. Kitani. In CVPR 2016.

- [Egocentric Future Localization](https://openaccess.thecvf.com/content_cvpr_2016/papers/Park_Egocentric_Future_Localization_CVPR_2016_paper.pdf) - Hyun Soo Park, Jyh-Jing Hwang, Yedong Niu, and Jianbo Shi. In CVPR 2016. [[demo]](https://youtu.be/i_9CTMZ60zc)

- [Recognizing Micro-Actions and Reactions from Paired Egocentric Videos](https://openaccess.thecvf.com/content_cvpr_2016/papers/Yonetani_Recognizing_Micro-Actions_and_CVPR_2016_paper.pdf) - Ryo Yonetani, Kris M. Kitani, and Yoichi Sato. In CVPR 2016.

- [Walk and Learn: Facial Attribute Representation Learning from Egocentric Video and Contextual Data](https://openaccess.thecvf.com/content_cvpr_2016/papers/Wang_Walk_and_Learn_CVPR_2016_paper.pdf) - Jing Wang, Yu Cheng, and Rogerio Schmidt Feris. In CVPR 2016. [[demo]](https://youtu.be/AQKS20Eo7uQ)

- [Delving into egocentric actions](https://openaccess.thecvf.com/content_cvpr_2015/papers/Li_Delving_Into_Egocentric_2015_CVPR_paper.pdf) - Yin Li, Zhefan Ye, and James M. Rehg. In CVPR 2015.

- [Pooled Motion Features for First-Person Videos](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Ryoo_Pooled_Motion_Features_2015_CVPR_paper.pdf) - Michael S. Ryoo, Brandon Rothrock, and Larry H. Matthies. In CVPR 2015.

- [EgoSampling: Fast-Forward and Stereo for Egocentric Videos](https://openaccess.thecvf.com/content_cvpr_2015/papers/Poleg_EgoSampling_Fast-Forward_and_2015_CVPR_paper.pdf) - Yair Poleg, Tavi Halperin, Chetan Arora, and Shmuel Peleg. In CVPR 2015.

- [Ego-Surfing First Person Videos](https://openaccess.thecvf.com/content_cvpr_2015/papers/Yonetani_Ego-Surfing_First-Person_Videos_2015_CVPR_paper.pdf) - Ryo Yonetani, Kris M. Kitani, and Yoichi Sato. In CVPR 2015.

- [First-Person Pose Recognition using Egocentric Workspaces](https://openaccess.thecvf.com/content_cvpr_2015/papers/Rogez_First-Person_Pose_Recognition_2015_CVPR_paper.pdf) - Gregory Rogez, James S. Supancic, and Deva Ramanan. In CVPR 2015.

- [Temporal segmentation of egocentric videos](https://www.cse.iitd.ac.in/~chetan/papers/egocentric-cvpr14.pdf) -Yair Poleg, Chetan Arora, and Shmuel Peleg. In CVPR 2014.

- [First-Person Activity Recognition: What Are They Doing to Me?](http://cvrc.ece.utexas.edu/mryoo/papers/cvpr2013_ryoo.pdf) - M. S. Ryoo and Larry Matthies. In CVPR 2013.

- [Pixel-level hand detection in ego-centric videos](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Li_Pixel-Level_Hand_Detection_2013_CVPR_paper.pdf) - Cheng Li and Kris M. Kitani. In CVPR 2013. [[video]](https://youtu.be/N756YmLpZyY) [[code]](https://github.com/irllabs/handtrack)

- [Story-Driven Summarization for Egocentric Video](https://www.cs.utexas.edu/~grauman/papers/lu-grauman-cvpr2013.pdf) - Zheng Lu and Kristen Grauman. In CVPR 2013 [[project page]](http://vision.cs.utexas.edu/projects/egocentric/storydriven.html)

- [Detecting activities of daily living in first-person camera views](https://www.cs.cmu.edu/~deva/papers/ADL_2012.pdf) - Hamed Pirsiavash and Deva Ramanan. In CVPR 2012.

- [Discovering Important People and Objects for Egocentric Video Summarization](http://vision.cs.utexas.edu/projects/egocentric/egocentric_cvpr2012.pdf) - Yong Jae Lee, Joydeep Ghosh, and Kristen Grauman. In CVPR 2012. [[project page]](http://vision.cs.utexas.edu/projects/egocentric/index.html)

- [Learning to recognize objects in egocentric activities](https://ai.stanford.edu/~alireza/publication/CVPR11.pdf) - Alireza Fathi, Xiaofeng Ren, and James M. Rehg. In CVPR 2011.

- [Fast unsupervised ego-action learning for first-person sports videos](http://www.dgcv.nii.ac.jp/Publications/Papers/2011/CVPR2011a.pdf) - Kris M. Kitani, Takahiro Okabe, Yoichi Sato, and Akihiro Sugimoto. In CVPR 2011. [[project page]](https://www.ri.cmu.edu/publications/fast-unsupervised-ego-action-learning-for-first-person-sports-videos/)

</details>

### ECCV 

<details>
<summary>Show papers (42)</summary>

- [Towards in-the-wild Egocentric 3D Hand-Object Pose Estimation](https://arxiv.org/abs/2606.30598) - Siddhant Bansal, Zhifan Zhu, Shashank Tripathi, Jiahe Zhao, Michael J. Black, and Dima Damen. In ECCV 2026. [[project page]](https://sid2697.github.io/epic-contact/) [[code]](https://github.com/Sid2697/HOPformer)

- [ActionVOS: Actions as Prompts for Video Object Segmentation](https://arxiv.org/abs/2407.07402) - Liangyang Ouyang, Ruicong Liu, Yifei Huang, Ryosuke Furuta, and Yoichi Sato. In ECCV 2024. [[code]](https://github.com/ut-vision/ActionVOS)

- [EgoBody3M: Egocentric Body Tracking on a VR Headset using a Diverse Dataset](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10261.pdf) - Amy Zhao, Chengcheng Tang, Lezi Wang, Yijing Li, Mihika Dave, Lingling Tao, Christopher D. Twigg, and Robert Y. Wang. In ECCV 2024. [[dataset]](https://github.com/facebookresearch/EgoBody3M)

- [Benchmarks and Challenges in Pose Estimation for Egocentric Hand Interactions with Objects](https://arxiv.org/abs/2403.16428) - Zicong Fan, Takehiko Ohkawa, Linlin Yang, Nie Lin, Zhishan Zhou, Shihao Zhou, et al. In ECCV 2024.

- [Are Synthetic Data Useful for Egocentric Hand-Object Interaction Detection?](https://arxiv.org/abs/2312.02672) - Rosario Leonardi, Antonino Furnari, Francesco Ragusa, and Giovanni Maria Farinella. In ECCV 2024. [[project page]](https://fpv-iplab.github.io/HOI-Synth/) [[code]](https://github.com/fpv-iplab/HOI-Synth)

- [Spherical World-Locking for Audio-Visual Localization in Egocentric Videos](https://arxiv.org/abs/2408.05364) - Heeseung Yun, Ruohan Gao, Ishwarya Ananthabhotla, Anurag Kumar, Jacob Donley, Chao Li, Gunhee Kim, Vamsi Krishna Ithapu, and Calvin Murdock. In ECCV 2024. [[project page]](https://hs-yn.github.io/SWL/)

- [AFF-ttention! Affordances and Attention models for Short-Term Object Interaction Anticipation](https://arxiv.org/abs/2406.01194) - Lorenzo Mur-Labadia, Ruben Martinez-Cantin, Jose J. Guerrero, Giovanni Maria Farinella, and Antonino Furnari. In ECCV 2024. [[code]](https://github.com/lmur98/AFFttention)

- [PALM: Predicting Actions through Language Models](https://arxiv.org/abs/2311.17944) - Sanghwan Kim, Daoji Huang, Yongqin Xian, Otmar Hilliges, Luc Van Gool, and Xi Wang. In ECCV 2024.

- [4Diff: 3D-Aware Diffusion Model for Third-to-First Viewpoint Translation](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03536.pdf) - Feng Cheng, Mi Luo, Huiyu Wang, Alex Dimakis, Lorenzo Torresani, Gedas Bertasius, and Kristen Grauman. In ECCV 2024. [[project page]](https://klauscc.github.io/4diff)

- [Synchronization is All You Need: Exocentric-to-Egocentric Transfer for Temporal Action Segmentation with Unlabeled Synchronized Video Pairs](https://arxiv.org/abs/2312.02638) - Camillo Quattrocchi, Antonino Furnari, Daniele Di Mauro, Mario Valerio Giuffrida, and Giovanni Maria Farinella. In ECCV 2024. [[code]](https://github.com/fpv-iplab/synchronization-is-all-you-need)

- [Ex2Eg-MAE: A Framework for Adaptation of Exocentric Video Masked Autoencoders for Egocentric Social Role Understanding](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10301.pdf) - Minh Tran, Yelin Kim, Che-Chun Su, Cheng-Hao Kuo, Min Sun, and Mohammad Soleymani. In ECCV 2024.

- [EgoCVR: An Egocentric Benchmark for Fine-Grained Composed Video Retrieval](https://arxiv.org/abs/2407.16658) - Thomas Hummel, Shyamgopal Karthik, Mariana-Iuliana Georgescu, and Zeynep Akata. In ECCV 2024. [[code]](https://github.com/ExplainableML/EgoCVR)

- [Action2Sound: Ambient-Aware Generation of Action Sounds from Egocentric Videos](https://arxiv.org/abs/2406.09272) - Changan Chen, Puyuan Peng, Ami Baid, Zihui Xue, Wei-Ning Hsu, David Harwath, and Kristen Grauman. In ECCV 2024. [[project page]](https://vision.cs.utexas.edu/projects/action2sound/) [[code]](https://github.com/ChanganVR/action2sound)

- [Masked Video and Body-worn IMU Autoencoder for Egocentric Action Recognition](https://arxiv.org/abs/2407.06628) - Mingfang Zhang, Yifei Huang, Ruicong Liu, and Yoichi Sato. In ECCV 2024. [[code]](https://github.com/mf-zhang/IMU-Video-MAE)

- [LEGO: Learning EGOcentric Action Frame Generation via Visual Instruction Tuning](https://arxiv.org/abs/2312.03849) - Bolin Lai, Xiaoliang Dai, Lawrence Chen, Guan Pang, James M. Rehg, and Miao Liu. In ECCV 2024. [[project page]](https://bolinlai.github.io/Lego_EgoActGen/)

- [Put Myself in Your Shoes: Lifting the Egocentric Perspective from Exocentric Videos](https://arxiv.org/abs/2403.06351) - Mi Luo, Zihui Xue, Alex Dimakis, and Kristen Grauman. In ECCV 2024. [[project page]](https://vision.cs.utexas.edu/projects/Exo2Ego/)

- [EgoLifter: Open-world 3D Segmentation for Egocentric Perception](https://arxiv.org/abs/2403.18118) - Qiao Gu, Zhaoyang Lv, Duncan Frost, Simon Green, Julian Straub, Chris Sweeney, et al. In ECCV 2024. [[project page]](https://egolifter.github.io/)

- [AMEGO: Active Memory from long EGOcentric videos](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02032.pdf) - Gabriele Goletto, Tushar Nagarajan, Giuseppe Averta, and Dima Damen. In ECCV 2024. [[project page]](https://gabrielegoletto.github.io/AMEGO/) [[code]](https://github.com/gabrielegoletto/AMEGO)

- [EgoExo-Fitness: Towards Egocentric and Exocentric Full-Body Action Understanding](https://arxiv.org/abs/2406.08877) - Yuan-Ming Li, Wei-Jin Huang, An-Lan Wang, Ling-An Zeng, Jing-Ke Meng, and Wei-Shi Zheng. In ECCV 2024. [[code]](https://github.com/iSEE-Laboratory/EgoExo-Fitness)

- [Nymeria: A Massive Collection of Egocentric Multi-modal Human Motion in the Wild](https://arxiv.org/abs/2406.09905) - Lingni Ma, Yuting Ye, Fangzhou Hong, Vladimir Guzov, Yifeng Jiang, et al. In ECCV 2024. [[project page]](https://www.projectaria.com/datasets/nymeria/)

- [Listen to Look into the Future: Audio-Visual Egocentric Gaze Anticipation](https://arxiv.org/abs/2305.03907) - Bolin Lai, Fiona Ryan, Wenqi Jia, Miao Liu, and James M. Rehg. In ECCV 2024. [[project page]](https://bolinlai.github.io/CSTS-EgoGazeAnticipation/)

- [On the Utility of 3D Hand Poses for Action Recognition](https://arxiv.org/abs/2403.09805) - Md Salman Shamil, Dibyadip Chatterjee, Fadime Sener, Shugao Ma, and Angela Yao. In ECCV 2024. [[project page]](https://s-shamil.github.io/HandFormer/)

- [EgoPoseFormer: A Simple Baseline for Stereo Egocentric 3D Human Pose Estimation](https://arxiv.org/abs/2403.18080) - Chenhongyi Yang, Anastasia Tkach, Shreyas Hampali, Linguang Zhang, Elliot J. Crowley, and Cem Keskin. In ECCV 2024. [[code]](https://github.com/ChenhongyiYang/egoposeformer)

- [EgoPoser: Robust Real-Time Egocentric Pose Estimation from Sparse and Intermittent Observations Everywhere](https://arxiv.org/abs/2308.06493) - Jiaxi Jiang, Paul Streli, Manuel Meier, and Christian Holz. In ECCV 2024. [[project page]](https://siplab.org/projects/EgoPoser)

- [3D Hand Pose Estimation in Everyday Egocentric Images](https://arxiv.org/abs/2312.06583) - Aditya Prakash, Ruisen Tu, Matthew Chang, and Saurabh Gupta. In ECCV 2024. [[project page]](https://ap229997.github.io/projects/hands/)

- [EgoPet: Egomotion and Interaction Data from an Animal's Perspective](https://arxiv.org/abs/2404.09991) - Amir Bar, Arya Bakhtiar, Danny Tran, Antonio Loquercio, Jathushan Rajasegaran, Yann LeCun, Amir Globerson, and Trevor Darrell. In ECCV 2024. [[project page]](https://www.amirbar.net/egopet/)

- [My View is the Best View: Procedure Learning from Egocentric Videos](https://arxiv.org/pdf/2207.10883) - Siddhant Bansal, Chetan Arora, C.V. Jawahar. In ECCV 2022. [[project page]](https://sid2697.github.io/egoprocel/) [[dataset]](https://sid2697.github.io/egoprocel/#download) [[code]](https://github.com/Sid2697/EgoProceL-egocentric-procedure-learning)

- [AssistQ: Affordance-centric Question-driven Task Completion for Egocentric Assistant](https://arxiv.org/pdf/2203.04203.pdf) - Benita Wong, Joya Chen, You Wu, Stan Weixian Lei, Dongxing Mao, Difei Gao, Mike Zheng Shou. In ECCV 2022. [[project page]](https://showlab.github.io/assistq/) [[code]](https://github.com/showlab/Q2A)

- [EgoBody: Human Body Shape and Motion of Interacting People from Head-Mounted Devices](https://arxiv.org/pdf/2112.07642.pdf) - Siwei Zhang, Qianli Ma, Yan Zhang, Zhiyin Qian, Taein Kwon, Marc Pollefeys, Federica Bogo, Siyu Tang. In ECCV 2022. [[project page]](https://sanweiliti.github.io/egobody/egobody.html) [[dataset]](https://egobody.inf.ethz.ch/) [[code]](https://github.com/sanweiliti/EgoBody)

- [Generative Adversarial Network for Future Hand Segmentation from Egocentric Video](https://arxiv.org/pdf/2203.11305.pdf) - Wenqi Jia, Miao Liu, James M. Rehg. In ECCV 2022.

- [Fine-Grained Egocentric Hand-Object Segmentation: Dataset, Model, and Applications](https://arxiv.org/pdf/2208.03826.pdf) - Lingzhi Zhang, Shenghao Zhou, Simon Stent, Jianbo Shi. In ECCV 2022. [[project page]](https://web.archive.org/web/20230422000343/https://www.seas.upenn.edu/~shzhou2/projects/eos_dataset/) [[code]](https://github.com/owenzlz/EgoHOS) [[dataset]](https://github.com/owenzlz/EgoHOS)

- [Egocentric Activity Recognition and Localization on a 3D Map](https://arxiv.org/pdf/2105.09544.pdf) - Miao Liu, Lingni Ma, Kiran Somasundaram, Yin Li, Kristen Grauman, James M. Rehg, Chao Li. In ECCV 2022.

- [SOS! Self-supervised Learning Over Sets Of Handled Objects In Egocentric Action Recognition](https://arxiv.org/abs/2204.04796) - Victor Escorcia, Ricardo Guerrero, Xiatian Zhu, Brais Martinez. In ECCV 2022.

- [UnrealEgo: A New Dataset for Robust Egocentric 3D Human Motion Capture](https://arxiv.org/abs/2208.01633) - Hiroyasu Akada, Jian Wang, Soshi Shimada, Masaki Takahashi, Christian Theobalt, Vladislav Golyanik. In ECCV 2022. [[project page]](https://4dqv.mpi-inf.mpg.de/UnrealEgo/) [[code]](https://github.com/hiroyasuakada/UnrealEgo) [[dataset]](https://4dqv.mpi-inf.mpg.de/UnrealEgo/) [[demo]](https://4dqv.mpi-inf.mpg.de/UnrealEgo/data/unrealego_distribution.mp4)

- [Forecasting Human-Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf) - Miao Liu, Siyu Tang, Yin Li, and James M. Rehg. In ECCV 2020. [[project page]](https://aptx4869lm.github.io/ForecastingHOI/)

- [How Can I See My Future? FvTraj: Using First-person View for Pedestrian Trajectory Prediction](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520562.pdf) - Huikun Bi, Ruisi Zhang, Tianlu Mao, Zhigang Deng, and Zhaoqi Wang. In ECCV 2020. [[presentation video]](https://youtu.be/HcsyH7zMHAw) [[summary video]](https://youtu.be/X1cSNWT6Gr0)

- [Is Sharing of Egocentric Video Giving Away Your Biometric Signature?](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620392.pdf) - Daksh Thapar, Chetan Arora, and Aditya Nigam. In ECCV 2020. [[project page]](https://egocentricbiometric.github.io)

- [In the eye of beholder: Joint learning of gaze and actions in first person video](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf) - Yin Li, Miao Liu, and James M. Rehg. In ECCV 2018.

- [Predicting Gaze in Egocentric Video by Learning Task-dependent Attention Transition](https://arxiv.org/pdf/1803.09125) - Yifei Huang, Minjie Cai, Zhenqiang Li, and Yoichi Sato. In ECCV 2018 [[code]](https://github.com/hyf015/egocentric-gaze-prediction)

- [Detecting engagement in egocentric video](http://www.cs.utexas.edu/~grauman/papers/su-eccv2016-ego.pdf) - Yu-Chuan Su and Kristen Grauman. In ECCV 2016.

- [Detecting Snap Points in Egocentric Video with a Web Photo Prior](https://www.cs.utexas.edu/~grauman/papers/bo-eccv2014.pdf) - Bo Xiong and Kristen Grauman. In ECCV 2014. [[project page]](http://vision.cs.utexas.edu/projects/ego_snappoints/) [[code]](http://vision.cs.utexas.edu/projects/ego_snappoints/#code)

- [Learning to recognize daily actions using gaze](http://ai.stanford.edu/~alireza/publication/ECCV12.pdf) - Alireza Fathi, Yin Li, and James M. Rehg. In ECCV 2012.

</details>

### ICCV

<details>
<summary>Show papers (56)</summary>

- [Embodied VideoAgent: Persistent Memory from Egocentric Videos and Embodied Sensors Enables Dynamic Scene Understanding](https://arxiv.org/abs/2501.00358) - Yue Fan, Xiaojian Ma, Rongpeng Su, Jun Guo, Rujie Wu, Xi Chen, and Qing Li. In ICCV 2025.

- [Visual Intention Grounding for Egocentric Assistants](https://arxiv.org/abs/2504.13621) - Pengzhan Sun, Junbin Xiao, Tze Ho Elden Tse, Yicong Li, Arjun Akula, and Angela Yao. In ICCV 2025. [[code]](https://github.com/pengzhansun/EgoIntention)

- [EgoAgent: A Joint Predictive Agent Model in Egocentric Worlds](https://arxiv.org/abs/2502.05857) - Lu Chen, Yizhou Wang, Shixiang Tang, Qianhong Ma, Tong He, Wanli Ouyang, Xiaowei Zhou, Hujun Bao, and Sida Peng. In ICCV 2025. [[code]](https://github.com/zju3dv/EgoAgent)

- [EgoM2P: Egocentric Multimodal Multitask Pretraining](https://arxiv.org/abs/2506.07886) - Gen Li, Yutong Chen, Yiqian Wu, Kaifeng Zhao, Marc Pollefeys, and Siyu Tang. In ICCV 2025. [[project page]](https://egom2p.github.io/)

- [O-MaMa: Learning Object Mask Matching between Egocentric and Exocentric Views](https://arxiv.org/abs/2506.06026) - Lorenzo Mur-Labadia, Maria Santos-Villafranca, Jesus Bermudez-Cameo, Alejandro Perez-Yus, Ruben Martinez-Cantin, and Jose J. Guerrero. In ICCV 2025. [[project page]](https://maria-sanvil.github.io/O-MaMa/) [[code]](https://github.com/Maria-SanVil/O-MaMa)

- [Benchmarking Egocentric Visual-Inertial SLAM at City Scale](https://arxiv.org/abs/2509.26639) - Anusha Krishnan, Shaohui Liu, Paul-Edouard Sarlin, Oscar Gentilhomme, David Caruso, Maurizio Monge, Richard Newcombe, Jakob Engel, and Marc Pollefeys. In ICCV 2025. [[project page]](https://www.lamaria.ethz.ch) [[code]](https://github.com/cvg/lamaria)

- [Self-Supervised Monocular 4D Scene Reconstruction for Egocentric Videos](https://arxiv.org/abs/2411.09145) - Chengbo Yuan, Geng Chen, Li Yi, and Yang Gao. In ICCV 2025. [[project page]](https://egomono4d.github.io/)

- [egoPPG: Heart Rate Estimation from Eye-Tracking Cameras in Egocentric Systems to Benefit Downstream Vision Tasks](https://arxiv.org/abs/2502.20879) - Björn Braun, Rayan Armani, Manuel Meier, Max Moebus, and Christian Holz. In ICCV 2025. [[project page]](https://siplab.org/projects/egoPPG) [[code]](https://github.com/eth-siplab/egoPPG)

- [PRVQL: Progressive Knowledge-guided Refinement for Robust Egocentric Visual Query Localization](https://arxiv.org/abs/2502.07707) - Bing Fan, Yunhe Feng, Yapeng Tian, James Chenhao Liang, Yuewei Lin, Yan Huang, and Heng Fan. In ICCV 2025. [[code]](https://github.com/fb-reps/PRVQL)

- [Egocentric Action-aware Inertial Localization in Point Clouds with Vision-Language Guidance](https://arxiv.org/abs/2505.14346) - Mingfang Zhang, Ryo Yonetani, Yifei Huang, Liangyang Ouyang, Ruicong Liu, and Yoichi Sato. In ICCV 2025.

- [Is Tracking Really More Challenging in First Person Egocentric Vision?](https://arxiv.org/abs/2507.16015) - Matteo Dunnhofer, Zaira Manigrasso, and Christian Micheloni. In ICCV 2025. [[project page]](https://machinelearning.uniud.it/datasets/vista/) [[code]](https://github.com/matteo-dunnhofer/fpv-tracking-toolkit)

- [Perceiving and Acting in First-Person: A Dataset and Benchmark for Egocentric Human-Object-Human Interactions](https://arxiv.org/abs/2508.04681) - Liang Xu, Chengqun Yang, Zili Lin, Fei Xu, Yifan Liu, Congsheng Xu, et al. In ICCV 2025. [[project page]](https://liangxuy.github.io/InterVLA/)

- [Learning Precise Affordances from Egocentric Videos for Robotic Manipulation](https://arxiv.org/abs/2408.10123) - Gen Li, Nikolaos Tsagkas, Jifei Song, Ruaridh Mon-Williams, Sethu Vijayakumar, Kun Shao, and Laura Sevilla-Lara. In ICCV 2025. [[project page]](https://reagan1311.github.io/affgrasp)

- [ProbRes: Probabilistic Jump Diffusion for Open-World Egocentric Activity Recognition](https://arxiv.org/abs/2504.03948) - Sanjoy Kundu, Shanmukha Vellamcheti, and Sathyanarayanan N. Aakur. In ICCV 2025.

- [Bring Your Rear Cameras for Egocentric 3D Human Pose Estimation](https://arxiv.org/abs/2503.11652) - Hiroyasu Akada, Jian Wang, Vladislav Golyanik, and Christian Theobalt. In ICCV 2025. [[project page]](https://4dqv.mpi-inf.mpg.de/EgoRear/)

- [Fish2Mesh Transformer: 3D Human Mesh Recovery from Egocentric Vision](https://arxiv.org/abs/2503.06089) - Tianma Shen, Aditya Puranik, James Vong, Vrushabh Abhijit Deogirikar, Ryan Fell, Julianna Dietrich, Maria Kyrarini, Christopher Kitts, and David C. Jeong. In ICCV 2025. [[project page]](https://fish2mesh.github.io/)

- [EgoMusic-driven Human Dance Motion Estimation with Skeleton Mamba](https://arxiv.org/abs/2508.10522) - Quang Nguyen, Nhat Le, Baoru Huang, Minh Nhat Vu, Chengcheng Tang, Van Nguyen, Ngan Le, Thieu Vo, and Anh Nguyen. In ICCV 2025.

- [UniEgoMotion: A Unified Model for Egocentric Motion Reconstruction, Forecasting, and Generation](https://arxiv.org/abs/2508.01126) - Chaitanya Patel, Hiroki Nakamura, Yuta Kyuragi, Kazuki Kozuka, Juan Carlos Niebles, and Ehsan Adeli. In ICCV 2025. [[project page]](https://chaitanya100100.github.io/UniEgoMotion/) [[code]](https://github.com/chaitanya100100/UniEgoMotion)

- [Head2Body: Body Pose Generation from Multi-sensory Head-mounted Inputs](https://openaccess.thecvf.com/content/ICCV2025/papers/Tran_Head2Body_Body_Pose_Generation_from_Multi-sensory_Head-mounted_Inputs_ICCV_2025_paper.pdf) - Minh Tran, Hongda Mao, Qingshuang Chen, and Yelin Kim. In ICCV 2025.

- [ObjectRelator: Enabling Cross-View Object Relation Understanding Across Ego-Centric and Exo-Centric Perspectives](https://arxiv.org/abs/2411.19083) - Yuqian Fu, Runze Wang, Bin Ren, Guolei Sun, Biao Gong, Yanwei Fu, Danda Pani Paudel, Xuanjing Huang, and Luc Van Gool. In ICCV 2025. [[project page]](https://yuqianfu.com/ObjectRelator/)

- [HiERO: Understanding the Hierarchy of Human Behavior Enhances Reasoning on Egocentric Videos](https://arxiv.org/abs/2505.12911) - Simone Alberto Peirone, Francesca Pistilli, and Giuseppe Averta. In ICCV 2025. [[project page]](https://sapeirone.github.io/HiERO/) [[code]](https://github.com/sapeirone/HiERO)

- [EgoAdapt: Adaptive Multisensory Distillation and Policy Learning for Efficient Egocentric Perception](https://arxiv.org/abs/2506.21080) - Sanjoy Chowdhury, Subrata Biswas, Sayan Nag, Tushar Nagarajan, Calvin Murdock, Ishwarya Ananthabhotla, Yijun Qian, Vamsi Krishna Ithapu, Dinesh Manocha, and Ruohan Gao. In ICCV 2025. [[project page]](https://schowdhury671.github.io/egoadapt_project/)

- [LookOut: Real-World Humanoid Egocentric Navigation](https://openaccess.thecvf.com/content/ICCV2025/papers/Pan_LookOut_Real-World_Humanoid_Egocentric_Navigation_ICCV_2025_paper.pdf) - Boxiao Pan, Adam W. Harley, Francis Engelmann, C. Karen Liu, and Leonidas J. Guibas. In ICCV 2025. [[project page]](https://sites.google.com/stanford.edu/lookout)

- [Aria Digital Twin: A New Benchmark Dataset for Egocentric 3D Machine Perception](https://openaccess.thecvf.com/content/ICCV2023/papers/Pan_Aria_Digital_Twin_A_New_Benchmark_Dataset_for_Egocentric_3D_ICCV_2023_paper.pdf) - Xiaqing Pan, Nicholas Charron, Yongqian Yang, Scott Peters, Thomas Whelan, Chen Kong, Omkar Parkhi, Richard Newcombe, and Yuheng (Carl) Ren. In ICCV 2023. [[project page]](https://www.projectaria.com/datasets/adt/)

- [EgoHumans: An Egocentric 3D Multi-Human Benchmark](https://arxiv.org/abs/2305.16487) - Rawal Khirodkar, Aayush Bansal, Lingni Ma, Richard Newcombe, Minh Vo, and Kris Kitani. In ICCV 2023 (Oral). [[code]](https://github.com/rawalkhirodkar/egohumans)

- [Self-Supervised Object Detection from Egocentric Videos](https://openaccess.thecvf.com/content/ICCV2023/papers/Akiva_Self-Supervised_Object_Detection_from_Egocentric_Videos_ICCV_2023_paper.pdf) - Peri Akiva, Jing Huang, Kevin J Liang, Rama Kovvuri, Xingyu Chen, Matt Feiszli, Kristin Dana, and Tal Hassner. In ICCV 2023. 

- [Spectral Graphormer: Spectral Graph-Based Transformer for Egocentric Two-Hand Reconstruction using Multi-View Color Images](https://openaccess.thecvf.com/content/ICCV2023/papers/Tse_Spectral_Graphormer_Spectral_Graph-Based_Transformer_for_Egocentric_Two-Hand_Reconstruction_using_ICCV_2023_paper.pdf) - Tze Ho Elden Tse, Franziska Mueller, Zhengyang Shen, Danhang Tang, Thabo Beeler, Mingsong Dou, Yinda Zhang, Sasa Petrovic, Hyung Jin Chang, Jonathan Taylor, and Bardia Doosti. In ICCV 2023. [[project page]](https://eldentse.github.io/Spectral-Graphormer/)

- [Uncertainty-aware State Space Transformer for Egocentric 3D Hand Trajectory Forecasting](https://openaccess.thecvf.com/content/ICCV2023/papers/Bao_Uncertainty-aware_State_Space_Transformer_for_Egocentric_3D_Hand_Trajectory_Forecasting_ICCV_2023_paper.pdf) - Wentao Bao, Lele Chen, Libing Zeng, Zhong Li, Yi Xu, Junsong Yuan, and Yu Kong. In ICCV 2023. [[project page]](https://web.archive.org/web/20231211050832/https://actionlab-cv.github.io/EgoHandTrajPred/) [[code]](https://github.com/oppo-us-research/USST) 

- [Probabilistic Human Mesh Recovery in 3D Scenes from Egocentric Views](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_Probabilistic_Human_Mesh_Recovery_in_3D_Scenes_from_Egocentric_Views_ICCV_2023_paper.pdf) - Siwei Zhang, Qianli Ma, Yan Zhang, Sadegh Aliakbarian, Darren Cosker, and Siyu Tang. In ICCV 2023. [[project page]](https://sanweiliti.github.io/egohmr/egohmr.html) [[code]](https://github.com/sanweiliti/EgoHMR) 

- [HoloAssist: an Egocentric Human Interaction Dataset for Interactive AI Assistants in the Real World](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_HoloAssist_an_Egocentric_Human_Interaction_Dataset_for_Interactive_AI_Assistants_ICCV_2023_paper.pdf) - Xin Wang, Taein Kwon, Mahdi Rad, Bowen Pan, Ishani Chakraborty, Sean Andrist, Dan Bohus, Ashley Feniello, Bugra Tekin, Felipe Vieira Frujeri, Neel Joshi, and Marc Pollefeys. In ICCV 2023. [[project page]](https://holoassist.github.io)

- [EgoObjects: A Large-Scale Egocentric Dataset for Fine-Grained Object Understanding](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhu_EgoObjects_A_Large-Scale_Egocentric_Dataset_for_Fine-Grained_Object_Understanding_ICCV_2023_paper.pdf) - Chenchen Zhu, Fanyi Xiao, Andres Alvarado, Yasmine Babaei, Jiabo Hu, Hichem El-Mohri, Sean Culatana, Roshan Sumbaly, and Zhicheng Yan. In ICCV 2023. [[project page]](https://research.facebook.com/blog/2023/3/egoobjects-large-scale-egocentric-dataset-for-category-and-instance-level-object-understanding/) [[code]](https://github.com/facebookresearch/EgoObjects)

- [EgoTV: Egocentric Task Verification from Natural Language Task Descriptions](https://openaccess.thecvf.com/content/ICCV2023/papers/Hazra_EgoTV_Egocentric_Task_Verification_from_Natural_Language_Task_Descriptions_ICCV_2023_paper.pdf) - Rishi Hazra, Brian Chen, Akshara Rai, Nitin Kamra, and Ruta Desai. In ICCV 2023. [[project page]](https://ai.meta.com/datasets/egotv-egocentric-task-verification-dataset/) [[code]](https://github.com/facebookresearch/EgoTV)

- [Ego-Only: Egocentric Action Detection without Exocentric Transferring](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Ego-Only_Egocentric_Action_Detection_without_Exocentric_Transferring_ICCV_2023_paper.html) - Huiyu Wang, Mitesh Kumar Singh, and Lorenzo Torresani. In ICCV 2023. 

- [Multimodal Distillation for Egocentric Action Recognition](https://openaccess.thecvf.com/content/ICCV2023/papers/Radevski_Multimodal_Distillation_for_Egocentric_Action_Recognition_ICCV_2023_paper.pdf) - Gorjan Radevski, Dusan Grujicic, Matthew Blaschko, Marie-Francine Moens, and Tinne Tuytelaars. In ICCV 2023. [[code]](https://github.com/gorjanradevski/multimodal-distillation)

- [Multi-label Affordance Mapping from Egocentric Vision](https://openaccess.thecvf.com/content/ICCV2023/papers/Mur-Labadia_Multi-label_Affordance_Mapping_from_Egocentric_Vision_ICCV_2023_paper.pdf) - Lorenzo Mur-Labadia, Jose J. Guerrero, and Ruben Martinez-Cantin. In ICCV 2023.

- [COPILOT: Human-Environment Collision Prediction and Localization from Egocentric Videos](https://openaccess.thecvf.com/content/ICCV2023/papers/Pan_COPILOT_Human-Environment_Collision_Prediction_and_Localization_from_Egocentric_Videos_ICCV_2023_paper.pdf) - Boxiao Pan, Bokui Shen, Davis Rempe, Despoina Paschalidou, Kaichun Mo, Yanchao Yang, and Leonidas J. Guibas. In ICCV 2023. [[project page]](https://sites.google.com/stanford.edu/copilot)

- [Learning from Semantic Alignment between Unpaired Multiviews for Egocentric Video Recognition](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Learning_from_Semantic_Alignment_between_Unpaired_Multiviews_for_Egocentric_Video_ICCV_2023_paper.pdf) - Qitong Wang, Long Zhao, Liangzhe Yuan, Ting Liu, and Xi Peng. In ICCV 2023. [[code]](https://github.com/wqtwjt1996/sum-l)

- [EgoPCA: A New Framework for Egocentric Hand-Object Interaction Understanding](https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_EgoPCA_A_New_Framework_for_Egocentric_Hand-Object_Interaction_Understanding_ICCV_2023_paper.pdf) - Yue Xu, Yong-Lu Li, Zhemin Huang, Michael Xu Liu, Cewu Lu, Yu-Wing Tai, and Chi-Keung Tang. In ICCV 2023. [[project page]](https://mvig-rhos.com/ego_pca)

- [EgoLoc: Revisiting 3D Object Localization from Egocentric Videos with Visual Queries](https://openaccess.thecvf.com/content/ICCV2023/papers/Mai_EgoLoc_Revisiting_3D_Object_Localization_from_Egocentric_Videos_with_Visual_ICCV_2023_paper.pdf) - Jinjie Mai, Abdullah Hamdi, Silvio Giancola, Chen Zhao, and Bernard Ghanem. In ICCV 2023. [[code]](https://github.com/Wayne-Mai/EgoLoc)

- [What can a cook in Italy teach a mechanic in India? Action Recognition Generalisation Over Scenarios and Locations](https://openaccess.thecvf.com/content/ICCV2023/papers/Plizzari_What_Can_a_Cook_in_Italy_Teach_a_Mechanic_in_ICCV_2023_paper.pdf) - Chiara Plizzari, Toby Perrett, Barbara Caputo, and Dima Damen. In ICCV 2023. [[project page]](https://web.archive.org/web/20241209215715/https://chiaraplizz.github.io/what-can-a-cook/) [[code]](https://github.com/Chiaraplizz/ARGO1M-What-can-a-cook)

- [EgoVLPv2: Egocentric Video-Language Pre-training with Fusion in the Backbone](https://arxiv.org/pdf/2307.05463.pdf) - Shraman Pramanick, Yale Song, Sayan Nag, Kevin Qinghong Lin, Hardik Shah, Mike Zheng Shou, Rama Chellappa, and Pengchuan Zhang. In ICCV 2023. [[project page]](https://shramanpramanick.github.io/EgoVLPv2/) [[code]](https://github.com/facebookresearch/EgoVLPv2/)

- [Estimating Egocentric 3D Human Pose in Global Space](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Estimating_Egocentric_3D_Human_Pose_in_Global_Space_ICCV_2021_paper.pdf) - Jian Wang, Lingjie Liu, Weipeng Xu, Kripasindhu Sarkar, Christian Theobalt. In ICCV 2021. [[project page]](https://web.archive.org/web/20240423122243/https://people.mpi-inf.mpg.de/~jianwang/projects/globalegomocap/)

- [Interactive Prototype Learning for Egocentric Action Recognition](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Interactive_Prototype_Learning_for_Egocentric_Action_Recognition_ICCV_2021_paper.html) - Xiaohan Wang, Linchao Zhu, Heng Wang, and Yi Yang. In ICCV 2021.

- [EPIC-Fusion: Audio-Visual Temporal Binding for Egocentric Action Recognition](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kazakos_EPIC-Fusion_Audio-Visual_Temporal_Binding_for_Egocentric_Action_Recognition_ICCV_2019_paper.pdf) - Evangelos Kazakos, Arsha Nagrani, Andrew Zisserman, and Dima Damen. In ICCV 2019. [[code]](https://github.com/ekazakos/temporal-binding-network) [[project page]](https://ekazakos.github.io/TBN/)

- [What Would You Expect? Anticipating Egocentric Actions with Rolling-Unrolling LSTMs and Modality Attention](https://arxiv.org/pdf/1905.09035) - Antonino Furnari and Giovanni Maria Farinella. In ICCV 2019 [[code]](https://github.com/fpv-iplab/rulstm) [[demo]](https://youtu.be/buIEKFHTVIg)

- [Ego-Pose Estimation and Forecasting as Real-Time PD Control](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yuan_Ego-Pose_Estimation_and_Forecasting_As_Real-Time_PD_Control_ICCV_2019_paper.pdf) - Ye Yuan and Kris Kitani. In ICCV 2019. [[code]](https://github.com/Khrylx/EgoPose) [[project page]](https://www.ye-yuan.com/ego-pose) [[demo]](https://youtu.be/968IIDZeWE0)

- [xR-EgoPose: Egocentric 3D Human Pose From an HMD Camera](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tome_xR-EgoPose_Egocentric_3D_Human_Pose_From_an_HMD_Camera_ICCV_2019_paper.pdf) - Denis Tome, Patrick Peluse, Lourdes Agapito, and Hernan Badino. In ICCV 2019. [[demo]](https://youtu.be/zem03fZWLrQ) [[dataset]](https://github.com/facebookresearch/xR-EgoPose)

- [Jointly Recognizing Object Fluents and Tasks in Egocentric Videos](https://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_Jointly_Recognizing_Object_ICCV_2017_paper.pdf) - Yang Liu, Ping Wei, and Song-Chun Zhu. In ICCV 2017.

- [Egocentric Gesture Recognition Using Recurrent 3D Convolutional Neural Networks with Spatiotemporal Transformer Modules](https://openaccess.thecvf.com/content_ICCV_2017/papers/Cao_Egocentric_Gesture_Recognition_ICCV_2017_paper.pdf) - Congqi Cao, Yifan Zhang, Yi Wu, Hanqing Lu, and Jian Cheng. In ICCV 2017.

- [First-Person Activity Forecasting with Online Inverse Reinforcement Learning](https://arxiv.org/pdf/1612.07796) - Nicholas Rhinehart and Kris M. Kitani. In ICCV 2017. [[video]](https://youtu.be/rvVoW3iuq-s)

- [Summarization and Classification of Wearable Camera Streams by Learning the Distributions over Deep Features of Out-of-Sample Image Sequences](https://openaccess.thecvf.com/content_ICCV_2017/papers/Perina_Summarization_and_Classification_ICCV_2017_paper.pdf) - Alessandro Perina, Sadegh Mohammadi, Nebojsa Jojic, and Vittorio Murino. In ICCV 2017.

- [Trespassing the Boundaries: Labeling Temporal Bounds for Object Interactions in Egocentric Video](https://openaccess.thecvf.com/content_ICCV_2017/papers/Moltisanti_Trespassing_the_Boundaries_ICCV_2017_paper.pdf) - Davide Moltisanti, Michael Wray, Walterio Mayol-Cuevas, and Dima Damen. In ICCV 2017.

- [Generating Notifications for Missing Actions: Don't forget to turn the lights off!](https://homes.cs.washington.edu/~ali/alarm-iccv.pdf) - Bilge Soran, Ali Farhadi, and Linda Shapiro. In ICCV 2015.

- [Lending a hand: Detecting hands and recognizing activities in complex egocentric interactions](https://web.archive.org/web/20210117023345/http://homes.sice.indiana.edu/sbambach/papers/iccv-egohands.pdf) - Sven Bambach, Stefan Lee, David J. Crandall, and Chen Yu. In ICCV 2015.

- [Learning to predict gaze in egocentric video](http://ai.stanford.edu/~alireza/publication/Li-Fathi-Rehg-ICCV13.pdf) - Yin Li, Alireza Fathi, and James M. Rehg. In ICCV 2013.

- [Context-based vision system for place and object recognition](https://www.cs.ubc.ca/~murphyk/Papers/iccv03.pdf) - Antonio Torralba, Kevin P. Murphy, William T. Freeman, Mark A. Rubin. In ICCV 2003. [[project page]](https://www.cs.ubc.ca/~murphyk/Vision/placeRecognition.html)

</details>

### WACV

<details>
<summary>Show papers (23)</summary>

- [ST-Think: How Multimodal Large Language Models Reason About 4D Worlds from Ego-Centric Videos](https://arxiv.org/abs/2503.12542) - Peiran Wu, Yunze Liu, Miao Liu, and Junxiao Shen. In WACV 2026.

- [Ego-EXTRA: video-language Egocentric Dataset for EXpert-TRAinee assistance](https://arxiv.org/abs/2512.13238) - Francesco Ragusa, Michele Mazzamuto, Rosario Forte, Irene D'Ambra, James Fort, Jakob Engel, Antonino Furnari, and Giovanni Maria Farinella. In WACV 2026. [[project page]](https://fpv-iplab.github.io/Ego-EXTRA/)

- [Towards Egocentric 3D Hand Pose Estimation in Unseen Domains](https://arxiv.org/abs/2601.06537) - Wiktor Mucha, Michael Wray, and Martin Kampel. In WACV 2026.

- [RegionAligner: Bridging Ego-Exo Views for Object Correspondence via Unified Text-Visual Learning](https://openaccess.thecvf.com/content/WACV2026/html/Su_RegionAligner_Bridging_Ego-Exo_Views_for_Object_Correspondence_via_Unified_Text-Visual_WACV_2026_paper.html) - Yuhao Su and Ehsan Elhamifar. In WACV 2026.

- [Online Episodic Memory Visual Query Localization with Egocentric Streaming Object Memory](https://arxiv.org/abs/2411.16934) - Zaira Manigrasso, Matteo Dunnhofer, Antonino Furnari, Moritz Nottebaum, Antonio Finocchiaro, Davide Marana, Rosario Forte, Giovanni Maria Farinella, and Christian Micheloni. In WACV 2026.

- [Social EgoMesh Estimation](https://arxiv.org/abs/2411.04598) - Luca Scofano, Alessio Sampieri, Edoardo De Matteis, Indro Spinelli, and Fabio Galasso. In WACV 2025. [[code]](https://github.com/L-Scofano/SEEME)

- [Ego-VPA: Egocentric Video Understanding with Parameter-Efficient Adaptation](https://arxiv.org/abs/2407.19520) - Tz-Ying Wu, Kyle Min, Subarna Tripathi, and Nuno Vasconcelos. In WACV 2025. [[code]](https://github.com/gina9726/Ego-VPA)

- [Exo2EgoDVC: Dense Video Captioning of Egocentric Procedural Activities Using Web Instructional Videos](https://arxiv.org/abs/2311.16444) - Takehiko Ohkawa, Takuma Yagi, Taichi Nishimura, Ryosuke Furuta, Atsushi Hashimoto, Yoshitaka Ushiku, and Yoichi Sato. In WACV 2025. [[code]](https://github.com/ut-vision/Exo2EgoDVC)

- [EgoSonics: Generating Synchronized Audio for Silent Egocentric Videos](https://arxiv.org/abs/2407.20592) - Aashish Rai and Srinath Sridhar. In WACV 2025. [[project page]](https://ivl.cs.brown.edu/research/egosonics.html)

- [EgoCast: Forecasting Egocentric Human Pose in the Wild](https://arxiv.org/abs/2412.02903) - Maria Escobar, Juanita Puentes, Cristhian Forigua, Jordi Pont-Tuset, Kevis-Kokitsi Maninis, and Pablo Arbelaez. In WACV 2025. [[code]](https://github.com/BCV-Uniandes/EgoCast)

- [SANPO: A Scene Understanding, Accessibility and Human Navigation Dataset](https://openaccess.thecvf.com/content/WACV2025/html/Waghmare_SANPO_A_Scene_Understanding_Accessibility_and_Human_Navigation_Dataset_WACV_2025_paper.html) - Sagar M. Waghmare, Kimberly Wilber, Dave Hawkey, Xuan Yang, Matthew Wilson, Stephanie Debats, et al. In WACV 2025. [[project page]](https://google-research-datasets.github.io/sanpo_dataset/) [[code]](https://github.com/google-research-datasets/sanpo_dataset)

- [Trans4Map: Revisiting Holistic Bird's-Eye-View Mapping from Egocentric Images to Allocentric Semantics with Vision Transformers](https://openaccess.thecvf.com/content/WACV2023/papers/Chen_Trans4Map_Revisiting_Holistic_Birds-Eye-View_Mapping_From_Egocentric_Images_to_Allocentric_WACV_2023_paper.pdf) - Chang Chen, Jiaming Zhang, Kailun Yang, Kunyu Peng, and Rainer Stiefelhagen. In WACV 2023.

- [Intention-Conditioned Long-Term Human Egocentric Action Forecasting](https://openaccess.thecvf.com/content/WACV2023/papers/Mascaro_Intention-Conditioned_Long-Term_Human_Egocentric_Action_Anticipation_WACV_2023_paper.pdf) - Esteve Valls Mascaro, Hyemin Ahn, and Dongheui Lee. In WACV 2023.

- [Fine-grained Affordance Annotation for Egocentric Hand-Object Interaction Videos](https://openaccess.thecvf.com/content/WACV2023/papers/Yu_Fine-Grained_Affordance_Annotation_for_Egocentric_Hand-Object_Interaction_Videos_WACV_2023_paper.pdf) - Zecheng Yu, Yifei Huang, Ryosuke Furuta, Takuma Yagi, Yusuke Goutsu, and Yoichi Sato. In WACV 2023.

- [Domain Generalization through Audio-Visual Relative Norm Alignment in First Person Action Recognition](https://openaccess.thecvf.com/content/WACV2022/papers/Planamente_Domain_Generalization_Through_Audio-Visual_Relative_Norm_Alignment_in_First_Person_WACV_2022_paper.pdf) - Mirco Planamente, Chiara Plizzari, Emanuele Alberti, and Barbara Caputo. In WACV 2022.

- [Integrating Human Gaze Into Attention for Egocentric Activity Recognition](https://openaccess.thecvf.com/content/WACV2021/html/Min_Integrating_Human_Gaze_Into_Attention_for_Egocentric_Activity_Recognition_WACV_2021_paper.html) - Kyle Min, Jason J. Corso. In WACV 2021. [[code]](https://github.com/MichiganCOG/Gaze-Attention)

- [Whose Hand Is This? Person Identification From Egocentric Hand Gestures](https://openaccess.thecvf.com/content/WACV2021/html/Tsutsui_Whose_Hand_Is_This_Person_Identification_From_Egocentric_Hand_Gestures_WACV_2021_paper.html) - Satoshi Tsutsui, Yanwei Fu, and David J. Crandall. In WACV 2021.

- [The MECCANO Dataset: Understanding Human-Object Interactions from Egocentric Videos in an Industrial-like Domain](https://arxiv.org/abs/2010.05654) - Francesco Ragusa, Antonino Furnari, Salvatore Livatino, and Giovanni Maria Farinella. In WACV 2021. [[project page]](https://iplab.dmi.unict.it/MECCANO/)

- [Automatic Calibration of the Fisheye Camera for Egocentric 3D Human Pose Estimation From a Single Image](https://openaccess.thecvf.com/content/WACV2021/html/Zhang_Automatic_Calibration_of_the_Fisheye_Camera_for_Egocentric_3D_Human_WACV_2021_paper.html) - Yahui Zhang, Shaodi You, and Theo Gevers. In WACV 2021.

- [Hand-Priming in Object Localization for Assistive Egocentric Vision](https://openaccess.thecvf.com/content_WACV_2020/papers/Lee_Hand-Priming_in_Object_Localization_for_Assistive_Egocentric_Vision_WACV_2020_paper.pdf) - Kyungjun Lee, Abhinav Shrivastava, and Hernisa Kacorri. In WACV 2020.

- [Digging Deeper into Egocentric Gaze Prediction](https://arxiv.org/pdf/1904.06090) - Hamed R. Tavakoli, Esa Rahtu, Juho Kannala, and Ali Borji. In WACV 2019.

- [EGO-SLAM: A Robust Monocular SLAM for Egocentric Videos](https://www.cse.iitd.ac.in/~chetan/papers/wacv19-egoslam.pdf) - Suvam Patra, Kartikeya Gupta, Faran Ahmad, Chetan Arora, and Subhashis Banerjee. In WACV 2019. [[code]](https://github.com/IITD-COMPUTER-VISION-GROUP/ego-slam)

- [Compact CNN for Indexing Egocentric Videos](https://www.cs.huji.ac.il/~peleg/papers/wacv16-cnn-indexing.pdf) - Yair Poleg, Ariel Ephrat, Shmuel Peleg, and Chetan Arora. In WACV 2016.

</details>

### BMVC

<details>
<summary>Show papers (6)</summary>

- [Pandora: Articulated 3D Scene Graphs from Egocentric Vision](https://bmvc2025.bmva.org/proceedings/548/) - Alan Yu, Yun Chang, Christopher Xie, and Luca Carlone. In BMVC 2025.

- [Toward Robust Audio-Visual Synchronization Detection in Egocentric Video with Sparse Synchronization Events](https://bmvc2025.bmva.org/proceedings/903/) - Jordan Voas, Wei-Cheng Tseng, Benoit Vallade, Alex Mackin, David Higham, and David Harwath. In BMVC 2025.

- [With a Little Help from my Temporal Context: Multimodal Egocentric Action Recognition](https://www.bmvc2021-virtualconference.com/assets/papers/0610.pdf) - Evangelos Kazakos, Jaesung Huh, Arsha Nagrani, Andrew Zisserman, and Dima Damen. In BMVC 2021. [[project page]](https://ekazakos.github.io/MTCN-project/) [[code]](https://github.com/ekazakos/MTCN)

- [Stacked Temporal Attention: Improving First-person Action Recognition by Emphasizing Discriminative Clips](https://www.bmvc2021-virtualconference.com/assets/papers/0243.pdf) - Lijin Yang, Yifei Huang, Yusuke Sugano, and Yoichi Sato. In BMVC 2021. [[project page]](https://www.bmvc2021-virtualconference.com/conference/papers/paper_0243.html)

- [Hand-Object Contact Prediction via Motion-Based Pseudo-Labeling and Guided Progressive Label Correction](https://www.bmvc2021-virtualconference.com/assets/papers/0096.pdf) - Takuma Yagi, Md Tasnimul Hasan, and Yoichi Sato. In BMVC 2021. [[project page]](https://www.bmvc2021-virtualconference.com/conference/papers/paper_0096.html) [[code]](https://github.com/takumayagi/hand_object_contact_prediction/)

- [You-Do, I-Learn: Discovering Task Relevant Objects and their Modes of Interaction from Multi-User Egocentric Video](https://dimadamen.github.io/You-Do-I-Learn/Damen_BMVC2014.pdf) - Dima Damen, Tessid Leelasawassuk, Osian Haines, Andrew Calway,and Walterio Mayol-Cuevas. In BMVC 2014 [[project page]](http://www.bmva.org/bmvc/2014/papers/paper059/index.html)

</details>

### NeurIPS

<details>
<summary>Show papers (38)</summary>

- [EgoDTM: Towards 3D-Aware Egocentric Video-Language Pretraining](https://arxiv.org/abs/2503.15470) - Boshen Xu, Yuting Mei, Xinbi Liu, Sipeng Zheng, and Qin Jin. In NeurIPS 2025. [[code]](https://github.com/xuboshen/EgoDTM)

- [EgoThinker: Unveiling Egocentric Reasoning with Spatio-Temporal CoT](https://arxiv.org/abs/2510.23569) - Baoqi Pei, Yifei Huang, Jilan Xu, Yuping He, Guo Chen, Fei Wu, Yu Qiao, and Jiangmiao Pang. In NeurIPS 2025. [[code]](https://github.com/InternRobotics/EgoThinker)

- [EOC-Bench: Can MLLMs Identify, Recall, and Forecast Objects in an Egocentric World?](https://arxiv.org/abs/2506.05287) - Yuqian Yuan, Ronghao Dang, Long Li, Wentong Li, Dian Jiao, Xin Li, Deli Zhao, Fan Wang, Wenqiao Zhang, Jun Xiao, and Yueting Zhuang. In NeurIPS 2025. [[project page]](https://circleradon.github.io/EOCBench/) [[code]](https://github.com/alibaba-damo-academy/EOCBench)

- [WearVQA: A Visual Question Answering Benchmark for Wearables in Egocentric Authentic Real-world scenarios](https://arxiv.org/abs/2511.22154) - Eun Chang, Zhuangqun Huang, Yiwei Liao, Sagar Ravi Bhavsar, Amogh Param, Tammy Stark, et al. In NeurIPS 2025.

- [Gaze-VLM: Bridging Gaze and VLMs through Attention Regularization for Egocentric Understanding](https://arxiv.org/abs/2510.21356) - Anupam Pani and Yanchao Yang. In NeurIPS 2025. [[code]](https://github.com/anupampani/Gaze-VLM)

- [In the Eye of MLLM: Benchmarking Egocentric Video Intent Understanding with Gaze-Guided Prompting](https://arxiv.org/abs/2509.07447) - Taiying Peng, Jiacheng Hua, Miao Liu, and Feng Lu. In NeurIPS 2025.

- [OpenMMEgo: Enhancing Egocentric Understanding for LMMs with Open Weights and Data](https://papers.nips.cc/paper_files/paper/2025/hash/24b9e3da4b01ec1e8a41144cfe8dc929-Abstract-Conference.html) - Hao Luo, Zihao Yue, Wanpeng Zhang, Yicheng Feng, Sipeng Zheng, Deheng Ye, and Zongqing Lu. In NeurIPS 2025. [[code]](https://github.com/BeingBeyond/OpenMMEgo)

- [Eyes Wide Open: Ego Proactive Video-LLM for Streaming Video](https://arxiv.org/abs/2510.14560) - Yulin Zhang, Cheng Shi, Yang Wang, and Sibei Yang. In NeurIPS 2025. [[code]](https://github.com/SooLab/EyeWO)

- [PlayerOne: Egocentric World Simulator](https://arxiv.org/abs/2506.09995) - Yuanpeng Tu, Hao Luo, Xi Chen, Xiang Bai, Fan Wang, and Hengshuang Zhao. In NeurIPS 2025. [[project page]](https://playerone-hku.github.io/) [[code]](https://github.com/yuanpengtu/PlayerOne)

- [EgoVid-5M: A Large-Scale Video-Action Dataset for Egocentric Video Generation](https://arxiv.org/abs/2411.08380) - Xiaofeng Wang, Kang Zhao, Feng Liu, Jiayu Wang, Guosheng Zhao, Xiaoyi Bao, Zheng Zhu, Yingya Zhang, and Xingang Wang. In NeurIPS 2025. [[project page]](https://egovid.github.io/) [[code]](https://github.com/JeffWang987/EgoVid)

- [EPFL-Smart-Kitchen: An Ego-Exo Multi-Modal Dataset for Challenging Action and Motion Understanding in Video-Language Models](https://arxiv.org/abs/2506.01608) - Andy Bonnetto, Haozhe Qi, Franklin Leong, Matea Tashkovska, Mahdi Rad, Solaiman Shokur, Friedhelm Hummel, Silvestro Micera, Marc Pollefeys, and Alexander Mathis. In NeurIPS 2025. [[project page]](https://amathislab.github.io/EPFL-Smart-Kitchen/pages/esk.html) [[code]](https://github.com/amathislab/EPFL-Smart-Kitchen)

- [EgoExOR: An Ego-Exo-Centric Operating Room Dataset for Surgical Activity Understanding](https://arxiv.org/abs/2505.24287) - Ege Özsoy, Arda Mamur, Felix Tristram, Chantal Pellegrini, Magdalena Wysocki, Benjamin Busam, and Nassir Navab. In NeurIPS 2025. [[code]](https://github.com/ardamamur/EgoExOR)

- [Robust Ego-Exo Correspondence with Long-Term Memory](https://arxiv.org/abs/2510.11417) - Yijun Hu, Bing Fan, Xin Gu, Haiqing Ren, Dongfang Liu, Heng Fan, and Libo Zhang. In NeurIPS 2025. [[code]](https://github.com/juneyeeHu/LM-EEC)

- [IndEgo: A Dataset of Industrial Scenarios and Collaborative Work for Egocentric Assistants](https://arxiv.org/abs/2511.19684) - Vivek Chavan, Yasmina Imgrund, Tung Dao, Sanwantri Bai, Bosong Wang, Ze Lu, Oliver Heimann, and Jörg Krüger. In NeurIPS 2025. [[project page]](https://indego-dataset.github.io/) [[code]](https://github.com/Vivek9Chavan/IndEgo/) [[dataset]](https://huggingface.co/datasets/FraunhoferIPK/IndEgo)

- [Seeing in the Dark: Benchmarking Egocentric 3D Vision with the Oxford Day-and-Night Dataset](https://arxiv.org/abs/2506.04224) - Zirui Wang, Wenjing Bian, Xinghui Li, Yifu Tao, Jianeng Wang, Maurice Fallon, and Victor Adrian Prisacariu. In NeurIPS 2025. [[project page]](https://oxdan.active.vision/)

- [egoEMOTION: Egocentric Vision and Physiological Signals for Emotion and Personality Recognition in Real-World Tasks](https://arxiv.org/abs/2510.22129) - Matthias Jammot, Björn Braun, Paul Streli, Rafael Wampfler, and Christian Holz. In NeurIPS 2025. [[project page]](https://siplab.org/projects/egoEMOTION) [[code]](https://github.com/eth-siplab/egoEMOTION)

- [Gaze Beyond the Frame: Forecasting Egocentric 3D Visual Span](https://arxiv.org/abs/2511.18470) - Heeseung Yun, Joonil Na, Jaeyeon Kim, Calvin Murdock, and Gunhee Kim. In NeurIPS 2025.

- [Robust Egocentric Referring Video Object Segmentation via Dual-Modal Causal Intervention](https://arxiv.org/abs/2512.24323) - Haijing Liu, Zhiyuan Song, Hefeng Wu, Tao Pu, Keze Wang, and Liang Lin. In NeurIPS 2025.

- [Benchmarking Egocentric Multimodal Goal Inference for Assistive Wearable Agents](https://arxiv.org/abs/2510.22443) - Vijay Veerabadran, Fanyi Xiao, Nitin Kamra, Pedro Matias, Joy Chen, Caley Drooff, et al. In NeurIPS 2025.

- [Whole-Body Conditioned Egocentric Video Prediction](https://arxiv.org/abs/2506.21552) - Yutong Bai, Danny Tran, Amir Bar, Yann LeCun, Trevor Darrell, and Jitendra Malik. In NeurIPS 2025. [[project page]](https://dannytran123.github.io/PEVA)

- [MEgoHand: Multimodal Egocentric Hand-Object Interaction Motion Generation](https://arxiv.org/abs/2505.16602) - Bohan Zhou, Yi Zhan, Zhongbin Zhang, and Zongqing Lu. In NeurIPS 2025. [[project page]](https://beingbeyond.github.io/MEgoHand/) [[code]](https://github.com/BeingBeyond/MEgoHand)

- [EgoExoBench: A Benchmark for First- and Third-person View Video Understanding in MLLMs](https://arxiv.org/abs/2507.18342) - Yuping He, Yifei Huang, Guo Chen, Baoqi Pei, Jilan Xu, Tong Lu, Jiangmiao Pang, et al. In NeurIPS 2025. [[code]](https://github.com/ayiyayi/EgoExoBench)

- [EgoBlind: Towards Egocentric Visual Assistance for the Blind](https://arxiv.org/abs/2503.08221) - Junbin Xiao, Nanxin Huang, Hao Qiu, Zhulin Tao, Xun Yang, Richang Hong, Meng Wang, and Angela Yao. In NeurIPS 2025.

- [EgoChoir: Capturing 3D Human-Object Interaction Regions from Egocentric Views](https://arxiv.org/abs/2405.13659) - Yuhang Yang, Wei Zhai, Chengfeng Wang, Chengjun Yu, Yang Cao, and Zheng-Jun Zha. In NeurIPS 2024. [[project page]](https://yyvhang.github.io/EgoChoir/) [[code]](https://github.com/yyvhang/EgoChoir_release)

- [HourVideo: 1-Hour Video-Language Understanding](https://arxiv.org/abs/2411.04998) - Keshigeyan Chandrasegaran, Agrim Gupta, Lea M. Hadzic, Taran Kota, Jimming He, Cristóbal Eyzaguirre, Zane Durante, Manling Li, Jiajun Wu, and Li Fei-Fei. In NeurIPS 2024. [[project page]](https://hourvideo.stanford.edu/) [[code]](https://github.com/keshik6/HourVideo)

- [CaptainCook4D: A Dataset for Understanding Errors in Procedural Activities](https://arxiv.org/abs/2312.14556) - Rohith Peddi, Shivvrat Arya, Bharath Challa, Likhitha Pallapothula, Akshay Vyas, Bhavya Gouripeddi, et al. In NeurIPS 2024. [[project page]](https://captaincook4d.github.io/captain-cook/)

- [Streaming Detection of Queried Event Start](https://arxiv.org/abs/2412.03567) - Cristóbal Eyzaguirre, Eric Tang, Shyamal Buch, Adrien Gaidon, Jiajun Wu, and Juan Carlos Niebles. In NeurIPS 2024. [[project page]](https://sdqesdataset.github.io/)

- [Estimating Ego-Body Pose from Doubly Sparse Egocentric Video Data](https://arxiv.org/abs/2411.03561) - Seunggeun Chi, Pin-Hao Huang, Enna Sachdeva, Hengbo Ma, Karthik Ramani, and Kwonjoon Lee. In NeurIPS 2024. [[project page]](https://sgchi.github.io/dsposer/)

- [E³: Exploring Embodied Emotion Through A Large-Scale Egocentric Video Dataset](https://proceedings.neurips.cc/paper_files/paper/2024/hash/d611d5c0251d9680f869c5d2c46c6fcd-Abstract-Datasets_and_Benchmarks_Track.html) - Wang Lin, Yueying Feng, Wenkang Han, Tao Jin, Zhou Zhao, Fei Wu, Chang Yao, and Jingyuan Chen. In NeurIPS 2024.

- [EgoSim: An Egocentric Multi-view Simulator and Real Dataset for Body-worn Cameras during Motion and Activity](https://openreview.net/forum?id=eOszT2lepG) - Dominik Hollidt, Paul Streli, Jiaxi Jiang, Yasaman Haghighi, Changlin Qian, Xintong Liu, and Christian Holz. In NeurIPS 2024. [[project page]](https://siplab.org/projects/EgoSim)

- [Exocentric-to-Egocentric Video Generation](https://openreview.net/forum?id=UHDCbIrCFL) - Jia-Wei Liu, Weijia Mao, Zhongcong Xu, Jussi Keppo, and Mike Zheng Shou. In NeurIPS 2024. [[code]](https://github.com/showlab/Exo2Ego-V)

- [HENASY: Learning to Assemble Scene-Entities for Interpretable Egocentric Video-Language Model](https://arxiv.org/abs/2406.00307) - Khoa Vo, Thinh Phan, Kashu Yamazaki, Minh Tran, and Ngan Le. In NeurIPS 2024. [[project page]](https://uark-aicv.github.io/HENASY/) [[code]](https://github.com/UARK-AICV/HENASY)

- [Differentiable Task Graph Learning: Procedural Activity Representation and Online Mistake Detection from Egocentric Videos](https://arxiv.org/abs/2406.01486) - Luigi Seminara, Giovanni Maria Farinella, and Antonino Furnari. In NeurIPS 2024. [[code]](https://github.com/fpv-iplab/Differentiable-Task-Graph-Learning)

- [EgoSchema: A Diagnostic Benchmark for Very Long-form Video Language Understanding](https://arxiv.org/abs/2308.09126) - Karttikeya Mangalam, Raiymbek Akshulakov, and Jitendra Malik. In NeurIPS 2023. [[project page]](https://egoschema.github.io/) [[code]](https://github.com/egoschema/EgoSchema)

- [EgoTracks: A Long-term Egocentric Visual Object Tracking Dataset](https://arxiv.org/abs/2301.03213) - Hao Tang, Kevin J Liang, Kristen Grauman, Matt Feiszli, and Weiyao Wang. In NeurIPS 2023. [[dataset]](https://ego4d-data.org/docs/data/egotracks/)

- [Egocentric Video-Language Pretraining](https://arxiv.org/pdf/2206.01670.pdf) - Kevin Qinghong Lin, Alex Jinpeng Wang, Mattia Soldan, Michael Wray, Rui Yan, Eric Zhongcong Xu, Difei Gao, Rongcheng Tu, Wenzhe Zhao, Weijie Kong, Chengfei Cai, Hongfa Wang, Dima Damen, Bernard Ghanem, Wei Liu and Mike Zheng Shou. In NeurIPS 2022. [[project page]](https://qinghonglin.github.io/EgoVLP/) [[code]](https://github.com/showlab/EgoVLP)

- [EgoTaskQA: Understanding Human Tasks in Egocentric Videos](https://arxiv.org/pdf/2210.03929.pdf) - Baoxiong Jia, Ting Lei, Song-Chun Zhu, Siyuan Huang. In NeurIPS 2022. [[project page]](https://sites.google.com/view/egotaskqa) [[code]](https://github.com/Buzz-Beater/EgoTaskQA)

- [Learning State-Aware Visual Representations from Audible Interactions](https://arxiv.org/pdf/2209.13583.pdf) - Himangi Mittal, Pedro Morgado, Unnat Jain, Abhinav Gupta. In NeurIPS 2022. [[code]](https://github.com/HimangiM/RepLAI) [[Video]](https://www.youtube.com/watch?v=hn5P8BPrPZ4)

</details>

## Datasets

### Flagship Datasets

A quick-reference table of some of the most prominent egocentric datasets/benchmarks. All entries below are also present in the full index in [All Datasets](#all-datasets); scale/modality/task figures are paraphrased from the descriptions already given there.

| Dataset | Scale | Modality/Sensors | Primary Task | Access |
|---|---|---|---|---|
| [Ego4D](https://ego4d-data.org) | 3,025 hours, 855 wearers, 74 locations, 9 countries | Daily-life egocentric video | General-purpose egocentric benchmark suite | Requires Ego4D license |
| [Ego-Exo4D](https://ego-exo4d-data.org) | 1,286 hours, 740 participants, 13 cities | Multi-modal, multiview ego+exo video | Skilled human activity understanding (sports, music, dance, repair) | — |
| [HOT3D](https://facebookresearch.github.io/hot3d/) | 833 minutes, 19 subjects, 33 objects | Multi-view egocentric image streams, 3D hand/object poses | Hand-object 3D tracking | — |
| [Nymeria](https://www.projectaria.com/datasets/nymeria/) | 300h daily activity / 3,600h video, 1,200 sequences, 264 participants, 50 locations | Multiple egocentric multimodal devices | Human motion capture in the wild | — |
| [Aria Digital Twin](https://www.projectaria.com/datasets/adt/) | 200 sequences, 398 object instances, 2 indoor scenes | Aria egocentric video + digital-twin ground truth | Egocentric 3D machine perception | — |
| [HoloAssist](https://holoassist.github.io) | Large-scale (two-person sessions) | Egocentric human interaction video | Interactive AI assistants for physical manipulation tasks | — |
| [HD-EPIC](https://hd-epic.github.io/) | 41 hours, 59.4K actions, 50.9K audio events, 26.6K VQA | Video, audio, 3D digital-twin grounding | Detailed kitchen action/audio understanding + VQA | — |
| [EgoLife](https://github.com/EvolvingLMMs-Lab/EgoLife) | ~300 hours, 6 participants, 1 week | Egocentric, interpersonal, multiview, multimodal (AI glasses) | Long-context daily-life assistance (EgoLifeQA) | — |
| [EgoDex](https://github.com/apple/ml-egodex) | 829 hours, 338K demonstrations, 194 tasks | Apple Vision Pro video + 3D head/hand pose + language | Tabletop manipulation demonstrations | — |
| [EgoSchema](https://egoschema.github.io/) | 5,000+ QA pairs, 250+ hours (from Ego4D) | Video question answering | Very long-form video-language understanding benchmark | — |
| [Aria Everyday Activities](https://www.projectaria.com/datasets/aea/) | 143 sequences, 5 indoor locations | Project Aria (3D trajectories, point clouds, gaze, speech) | Daily-activity egocentric perception | — |
| [EgoBody](https://egobody.inf.ethz.ch/) | Large-scale | Head-mounted device video | 3D human motion in social interactions | — |
| [UnrealEgo](https://4dqv.mpi-inf.mpg.de/UnrealEgo/) | Large-scale | Egocentric stereo video | 3D human pose estimation | — |
| [HOI4D](https://hoi4d.github.io/) | 2.4M RGB-D frames, 4,000 sequences, 9 participants, 800 objects, 16 categories | RGB-D egocentric video | Category-level human-object interaction | — |
| [EgoExoLearn](https://egoexolearn.github.io/) | 120 hours, 747 sequences | Ego+exo video with eye gaze | Procedural activity understanding across asynchronous views | — |
| [CaptainCook4D](https://captaincook4d.github.io/captain-cook/) | 384 recordings, 94.5 hours, 5.3K step / 10K action annotations | Egocentric 4D video | Procedure learning, error recognition | — |
| [EgoProceL](https://sid2697.github.io/egoprocel/#download) | 62 hours, 130 subjects, 16 tasks | Egocentric video | Procedure learning | — |
| [MECCANO](https://iplab.dmi.unict.it/MECCANO/) | 20 subjects | Egocentric video | Human-object interaction (industrial-like assembly) | — |
| [EGTEA Gaze+](http://cbs.ic.gatech.edu/fpv/) | 32 subjects, 86 sessions, 28 hours | Egocentric video + gaze | Cooking activity recognition and gaze | — |
| [EPIC-Tent](https://data.bristol.ac.uk/data/dataset/2ite3tu1u53n42hjfh3886sa86) | 29 participants, dual head-mounted cameras | Egocentric video | Procedural activity (tent assembly) | — |
| [IndEgo](https://indego-dataset.github.io/) | 3,460 ego recordings (~197h) + 1,092 exo recordings (~97h) | Ego+exo video, gaze, narration, hand pose | Procedural task understanding, mistake detection, reasoning QA | — |
| [EPFL-Smart-Kitchen-30](https://github.com/amathislab/EPFL-Smart-Kitchen) | 29.7 hours, 16 subjects, 4 recipes | Exo (9 RGB-D) + ego (HoloLens 2), depth, IMU, gaze, kinematics | Action and motion understanding benchmarks | — |
| [HourVideo](https://hourvideo.stanford.edu/) | 500 videos (20-120 min each), 12,976 QA pairs | Video question answering (from Ego4D) | Long-video language understanding | — |

### All Datasets

- [EgoHumans](https://github.com/rawalkhirodkar/egohumans) - 125K+ egocentric images from an in-the-wild multi-view multi-human capture setup (tennis, fencing, volleyball), with 3D pose, mesh, and tracking ground truth. [[paper]](https://arxiv.org/abs/2305.16487)
- [EgoPet](https://www.amirbar.net/egopet/) - About 84 hours of animal (dogs, cats, and others) egocentric video with interaction annotations, supporting benchmarks for visual interaction prediction, locomotion prediction, and vision-to-proprioception. [[paper]](https://arxiv.org/abs/2404.09991)
- [Assembly101](https://assembly-101.github.io/) - 4,321 videos of assembling/disassembling 101 take-apart toy vehicles, with 8 static and 4 egocentric views, 100K+ coarse and 1M fine-grained action segments, and 18M 3D hand poses, for procedural activity recognition, anticipation, segmentation, and mistake detection. [[paper]](https://arxiv.org/abs/2203.14712)
- [EPIC-Contact](https://sid2697.github.io/epic-contact/) - About 2,300 egocentric video clips (62,300 annotated frames) of bimanual hand-object interactions across nine everyday kitchen objects, for in-the-wild 3D hand-object pose estimation. [[paper]](https://arxiv.org/abs/2606.30598) [[code]](https://github.com/Sid2697/HOPformer)
- [IndEgo](https://indego-dataset.github.io/) - 3,460 egocentric recordings (~197 hours) plus 1,092 exocentric recordings (~97 hours) of industrial tasks including collaborative work, with eye gaze, narration, hand pose, mistake annotations, and benchmarks for procedural task understanding, mistake detection, and reasoning QA. [[paper]](https://arxiv.org/abs/2511.19684)
- [Oxford Day-and-Night](https://oxdan.active.vision/) - Large-scale egocentric dataset captured with Meta Aria glasses spanning over 30 km of trajectories under day and night lighting, with multi-session SLAM ground-truth poses and 3D geometry for novel view synthesis and visual relocalisation benchmarks. [[paper]](https://arxiv.org/abs/2506.04224)
- [egoEMOTION](https://siplab.org/projects/egoEMOTION) - Over 50 hours of recordings from 43 participants wearing Project Aria glasses, coupling eye-tracking video, head-mounted PPG, and inertial data with self-reported emotion and Big Five personality labels. [[paper]](https://arxiv.org/abs/2510.22129)
- [LaMAria](https://www.lamaria.ethz.ch) - City-scale egocentric visual-inertial SLAM benchmark captured with Aria glasses over hours and kilometers of trajectories, with survey-grade control points providing centimeter-accurate ground truth. [[paper]](https://arxiv.org/abs/2509.26639) [[code]](https://github.com/cvg/lamaria)
- [InterVLA](https://liangxuy.github.io/InterVLA/) - Large-scale egocentric human-object-human interaction dataset with 11.4 hours and 1.2M frames of multimodal data (2 egocentric and 5 exocentric views, human/object motion capture, and verbal commands). [[paper]](https://arxiv.org/abs/2508.04681)
- [EPFL-Smart-Kitchen-30](https://github.com/amathislab/EPFL-Smart-Kitchen) - 29.7 hours of 16 subjects cooking four recipes with synchronized exocentric (9 RGB-D cameras) and egocentric (HoloLens 2) video, depth, IMUs, eye gaze, and body/hand kinematics, densely annotated for four action and motion understanding benchmarks. [[paper]](https://arxiv.org/abs/2506.01608)
- [EgoExOR](https://github.com/ardamamur/EgoExOR) - 94 minutes (84,553 frames at 15 FPS) of two emulated spine procedures combining egocentric data (RGB, gaze, hand tracking, audio) from wearable glasses with exocentric RGB-D and ultrasound, annotated with 568,235 scene-graph triplets. [[paper]](https://arxiv.org/abs/2505.24287)
- [EgoVid-5M](https://egovid.github.io/) - 5 million action-annotated egocentric video clips (1080p) with kinematic control signals and text descriptions, curated for egocentric video generation. [[paper]](https://arxiv.org/abs/2411.08380)
- [EOC-Bench](https://circleradon.github.io/EOCBench/) - A benchmark of 3,277 QA pairs over past/present/future temporal dimensions for evaluating object-centric embodied cognition of MLLMs in dynamic egocentric video. [[paper]](https://arxiv.org/abs/2506.05287)
- [egoPPG-DB](https://siplab.org/projects/egoPPG) - 13+ hours of eye-tracking videos from Project Aria glasses of 25 participants performing everyday activities, with synchronized contact PPG and ECG-derived ground-truth heart rate. [[paper]](https://arxiv.org/abs/2502.20879)
- [VISTA](https://machinelearning.uniud.it/datasets/vista/) - A benchmark disentangling first-person viewpoint from the activity domain for visual object tracking and segmentation, with paired egocentric and third-person evaluation scenarios. [[paper]](https://arxiv.org/abs/2507.16015)
- [EgoSchema](https://egoschema.github.io/) - A very long-form video question-answering benchmark derived from Ego4D with over 5,000 human-curated multiple-choice QA pairs spanning over 250 hours of egocentric video, each question grounded in a three-minute clip. [[paper]](https://arxiv.org/abs/2308.09126) [[code]](https://github.com/egoschema/EgoSchema)
- [EgoTracks](https://ego4d-data.org/docs/data/egotracks/) - A long-term egocentric visual object tracking dataset built on Ego4D with 22.42k annotated tracks from 5.9k videos, released as part of the Ego4D benchmark; requires the Ego4D license for access. [[paper]](https://arxiv.org/abs/2301.03213)
- [EgoBody3M](https://github.com/facebookresearch/EgoBody3M) - Large-scale real-image dataset for egocentric body tracking from VR-headset SLAM cameras, with more than 30 hours of recordings and about 3 million frames of diverse subjects and motions. [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10261.pdf)
- [Ego4D-Sounds](https://vision.cs.utexas.edu/projects/action2sound/) - 1.2 million curated egocentric video clips from Ego4D with action-audio correspondence, built for action-to-sound generation. [[paper]](https://arxiv.org/abs/2406.09272)
- [Ego4D-HCap](https://sites.google.com/view/vidrecap) - Hierarchical captioning dataset built on Ego4D with 8,267 manually annotated long-range video summaries for hour-long egocentric videos. [[paper]](https://arxiv.org/abs/2402.13250)
- [EgoPER](https://www.khoury.northeastern.edu/home/eelhami/egoper.htm) - 28 hours of egocentric procedural cooking videos across 5 tasks with normal and erroneous executions, multiple modalities (audio, depth, hand tracking), frame-wise step labels, and object bounding boxes for error detection. [[paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Lee_Error_Detection_in_Egocentric_Procedural_Task_Videos_CVPR_2024_paper.html) [[code]](https://github.com/robert80203/EgoPER_official)
- [HourVideo](https://hourvideo.stanford.edu/) - A long-video benchmark of 500 manually curated egocentric videos from Ego4D (20 to 120 minutes each) with 12,976 five-way multiple-choice questions spanning summarization, perception, visual reasoning, and navigation tasks. [[paper]](https://arxiv.org/abs/2411.04998)
- [CaptainCook4D](https://captaincook4d.github.io/captain-cook/) - An egocentric 4D dataset of 384 recordings (94.5 hours) of people following or deviating from recipes in real kitchens, with 5.3K step and 10K fine-grained action annotations for error recognition, multistep localization, and procedure learning. [[paper]](https://arxiv.org/abs/2312.14556)
- [Ego-EXTRA](https://fpv-iplab.github.io/Ego-EXTRA/) - 50 hours of unscripted egocentric videos of trainees performing procedural activities guided by real experts, with transcribed two-way dialogues, gaze, audio, and more than 15K visual question-answer sets for benchmarking egocentric video-language assistants. [[paper]](https://arxiv.org/abs/2512.13238)
- [EgoXtreme](https://taegyoun88.github.io/EgoXtreme/) - Egocentric 6D object pose estimation dataset of about 1.3M frames (775.5 minutes at 30 fps) captured with Project Aria glasses by 15 participants interacting with 13 objects under extreme lighting, motion blur, and smoke across industrial maintenance, sports, and emergency rescue scenarios. [[paper]](https://arxiv.org/abs/2603.25135)
- [EgoAVU](https://github.com/facebookresearch/EgoAVU) - Egocentric audio-visual understanding suite with a 3M-sample instruction-tuning set (EgoAVU-Instruct) and a manually verified evaluation benchmark (EgoAVU-Bench) covering grounding, temporal reasoning, scene understanding, and audio-visual hallucination. [[paper]](https://arxiv.org/abs/2602.06139)
- [EgoEditData](https://snap-research.github.io/EgoEdit) - Manually curated dataset of 100k egocentric video editing pairs featuring object substitution and removal under hand occlusions, interactions, and large egomotion. [[paper]](https://arxiv.org/abs/2512.06065)
- [MyEgo](https://github.com/Ryougetsu3606/MyEgo) - Egocentric VideoQA dataset with 541 long videos and 5K personalized questions about the camera wearer's things, activities, and past, designed to evaluate MLLM ego-grounding. [[paper]](https://arxiv.org/abs/2604.01966)
- [EgoSound](https://groolegend.github.io/EgoSound/) - Benchmark for egocentric sound understanding in MLLMs with 7,315 validated QA pairs across 900 videos sourced from Ego4D and EgoBlind, spanning a seven-task taxonomy from sound perception to cross-modal reasoning. [[paper]](https://arxiv.org/abs/2602.14122)
- [Minerva-Ego](https://github.com/google-deepmind/neptune) - Egocentric video QA benchmark of 1,160 hand-crafted multiple-choice questions over 156 HD-EPIC videos, each paired with spatiotemporally grounded reasoning traces and object masks. [[paper]](https://arxiv.org/abs/2605.15342)
- [Ego-1K](https://huggingface.co/datasets/facebook/ego-1k) - A large-scale multiview egocentric dataset of 956 short videos (~491K frames) captured by 12 synchronous cameras surrounding a VR headset at 1280×1280, for neural 3D video synthesis and dynamic scene understanding. [[paper]](https://arxiv.org/abs/2603.13741)
- [Aria Gen 2 Pilot Dataset (A2PD)](https://www.projectaria.com/datasets/gen2pilot/) - Egocentric multimodal dataset captured with Aria Gen 2 glasses across everyday scenarios (cleaning, cooking, eating, playing, walking) between a primary user and three friends, with rich sensor streams (RGB, eye tracking, IMU, spatial audio, PPG, GPS) and machine-perception outputs.
- [EgoDex](https://github.com/apple/ml-egodex) - 829 hours of 30 fps 1080p egocentric video (338K demonstrations across 194 tabletop manipulation tasks) collected with Apple Vision Pro, paired with 3D head, upper-body, and hand pose plus natural-language annotations. [[paper]](https://arxiv.org/abs/2505.11709)
- [EgoLife](https://github.com/EvolvingLMMs-Lab/EgoLife) - A ~300-hour egocentric, interpersonal, multiview, multimodal dataset of six people living together for one week wearing AI glasses, accompanied by the EgoLifeQA long-context daily-assistance benchmark. [[paper]](https://arxiv.org/abs/2503.03803)
- [HD-EPIC](https://hd-epic.github.io/) - 41 hours of highly-detailed unscripted kitchen recordings with 3D digital-twin grounding, 59.4K fine-grained actions, 50.9K audio events, 7.7M hand masks and 19.9K object tracks, plus a 26.6K-question VQA benchmark. [[paper]](https://arxiv.org/abs/2502.04144)
- [EgoBlind](https://arxiv.org/abs/2503.08221) - The first egocentric VideoQA dataset collected from blind/visually impaired users: 1,392 first-person videos and 5,311 questions posed or verified by blind individuals for assistive multimodal evaluation.
- [EgoExoBench](https://arxiv.org/abs/2507.18342) - A benchmark of 7,300+ QA pairs across 11 sub-tasks built from public ego-exo datasets to evaluate multimodal LLMs on cross-view (first- and third-person) video understanding.
- [EgoPressure](https://arxiv.org/abs/2409.02224) - An egocentric dataset of hand touch-contact and pressure interactions with accurate hand-pose meshes and per-contact pressure intensities.
- [ParaHome](https://jlogkim.github.io/parahome/) - 486 minutes from 38 participants capturing 3D body and dexterous hand motion with multiple articulated household objects in a shared home environment, with text descriptions. [[paper]](https://arxiv.org/abs/2401.10232) [[code]](https://github.com/canoneod/ParaHome)
- [EgoMask](https://github.com/LaVi-Lab/EgoMask) - A pixel-level spatiotemporal grounding benchmark (with training set EgoMask-Train) built specifically for egocentric video. [[paper]](https://arxiv.org/abs/2508.00518)
- [EgoExo-Fitness](https://github.com/iSEE-Laboratory/EgoExo-Fitness) - Full-body action-understanding dataset of synchronized egocentric and exocentric fitness videos from 40 participants performing 86 types of fitness action sequences, with two-level temporal boundaries, technical-keypoint verification, language comments, and action-quality scores. [[paper]](https://arxiv.org/abs/2406.08877)
- [EgoExoLearn](https://egoexolearn.github.io/) - 120 hours across 747 sequences where camera wearers follow demonstrations to perform tasks in different environments, including eye-gaze signals, spanning daily food preparation to laboratory experiments. [[paper]](https://arxiv.org/abs/2403.16182)
- [Aria Everyday Activities (AEA)](https://www.projectaria.com/datasets/aea/) - 143 daily-activity sequences recorded by multiple wearers in five indoor locations with Project Aria, with globally-aligned 3D trajectories, scene point clouds, per-frame eye gaze, and time-aligned speech. [[paper]](https://arxiv.org/abs/2402.13349)
- [Ego4D Goal-Step](https://github.com/facebookresearch/ego4d-goalstep) - Hierarchical goal–step–substep annotations over Ego4D, with 2,807 hours carrying goal labels and 430 hours of fine-grained step labels (48K step segments). [[paper]](https://openreview.net/forum?id=3BxYAaovKr)
- [EventEgo3D](https://arxiv.org/abs/2404.08640) - An egocentric event-stream dataset and benchmark for 3D human motion capture from a head-mounted event camera.
- [ENIGMA-51](https://iplab.dmi.unict.it/ENIGMA-51/) - An egocentric dataset of sequences recorded in an industrial laboratory, densely annotated for fine-grained human-object interaction understanding. [[paper]](https://arxiv.org/abs/2309.14809)
- [EgoPoints](https://openaccess.thecvf.com/content/WACV2025/html/Darkhalil_EgoPoints_Advancing_Point_Tracking_for_Egocentric_Videos_WACV_2025_paper.html) - A benchmark for point tracking in egocentric video with challenging dynamic, occluded, and re-identification scenarios.
- [SANPO](https://openaccess.thecvf.com/content/WACV2025/html/Waghmare_SANPO_A_Scene_Understanding_Accessibility_and_Human_Navigation_Dataset_WACV_2025_paper.html) - A human egocentric navigation dataset for scene understanding and accessibility, with real and synthetic first-person video and dense depth/segmentation.
- [VIEW360](https://openaccess.thecvf.com/content/WACV2025/html/Song_Anomaly_Detection_for_People_with_Visual_Impairments_using_an_Egocentric_WACV_2025_paper.html) - An egocentric 360° video dataset for anomaly detection to assist people with visual impairments.
- [Ego2HandsPose](https://openaccess.thecvf.com/content/WACV2024/html/Lin_Ego2HandsPose_A_Dataset_for_Egocentric_Two-Hand_3D_Global_Pose_Estimation_WACV_2024_paper.html) - An egocentric dataset for two-hand 3D global pose estimation.
- [Aria Navigation Dataset (AND)](https://openaccess.thecvf.com/content/ICCV2025/html/Pan_LookOut_Real-World_Humanoid_Egocentric_Navigation_ICCV_2025_paper.html) - Roughly 4 hours of Project Aria egocentric recordings for humanoid/egocentric navigation, introduced with LookOut.
- [MultiEgoView](https://siplab.org/projects/EgoSim) - 119 hours of synthetic (rendered from AMASS) plus 5 hours of real footage from 13 participants, captured from six body-worn cameras with full-body 3D pose ground truth; released with the EgoSim simulator. [[paper]](https://openreview.net/forum?id=eOszT2lepG)
- [HOT3D](https://facebookresearch.github.io/hot3d/) - HOT3D is a dataset for benchmarking egocentric tracking of hands and objects in 3D. The dataset includes 833 minutes of multi-view image streams, which show 19 subjects interacting with 33 diverse rigid objects and are annotated with accurate 3D poses and shapes of hands and objects.
- [Nymeria](https://www.projectaria.com/datasets/nymeria/) - Dataset of human motion in the wild, capturing diverse people engaging in diverse activities across diverse locations. Record body motion using multiple egocentric multimodal devices, all accurately synchronized and localized in one single metric 3D world. 300 hours of daily activity, 3600 hours of video data, 1200 sequences, 264 participants, 50 indoor and outdoor locations.
- [Ego-Exo4D](https://ego-exo4d-data.org) - 1,286 hours of multi-modal multiview videos recorded by 740 participants from 13 cities worldwide performing different skilled human activities (e.g., sports, music, dance, bike repair).
- [Aria Digital Twin](https://www.projectaria.com/datasets/adt/) - A comprehensive egocentric dataset containing 200 sequences of real-world activities conducted by Aria wearers in two real indoor scenes with 398 object instances (324 stationary and 74 dynamic).
- [HoloAssist](https://holoassist.github.io) - A large-scale egocentric human interaction dataset, where two people collaboratively complete physical manipulation tasks.
- [EgoProceL](https://sid2697.github.io/egoprocel/#download) -  62 hours of egocentric videos recorded by 130 subjects performing 16 tasks for procedure learning.
- [EgoBody](https://egobody.inf.ethz.ch/) - Large-scale dataset capturing ground-truth 3D human motions during social interactions in 3D scenes.
- [UnrealEgo](https://4dqv.mpi-inf.mpg.de/UnrealEgo/) - Large-scale naturalistic dataset for egocentric 3D human pose estimation.
- [Hand-object Segments](https://web.archive.org/web/20230422000343/https://www.seas.upenn.edu/~shzhou2/projects/eos_dataset/) - Hand-object interactions in 11,235 frames from 1,000 videos covering daily activities in diverse scenarios.
- [Ego4D](https://ego4d-data.org) - 3,025 hours of daily-life activity video spanning hundreds of scenarios (household, outdoor, workplace, leisure, etc.) captured by 855 unique camera wearers from 74 worldwide locations and 9 different countries.
- [HOI4D](https://hoi4d.github.io/) - HOI4D consists of 2.4M RGB-D egocentric video frames over 4000 sequences collected by 9 participants interacting with 800 different object instances from 16 categories over 610 different indoor rooms.
- [EgoCom](https://github.com/facebookresearch/EgoCom-Dataset) - A natural conversations dataset containing multi-modal human communication data captured simultaneously from the participants' egocentric perspectives.
- [TREK-100](https://machinelearning.uniud.it/datasets/trek100/) - Object tracking in first person vision.
- [MECCANO](https://iplab.dmi.unict.it/MECCANO/) - 20 subject assembling a toy motorbike.
- [EPIC-Kitchens 2020](https://epic-kitchens.github.io/2020-100) - Subjects performing unscripted actions in their native environments.
- [EPIC-Tent](https://data.bristol.ac.uk/data/dataset/2ite3tu1u53n42hjfh3886sa86) - 29 participants assembling a tent while wearing two head-mounted cameras. [[paper]](https://ieeexplore.ieee.org/document/9022634)
- [EGO-CH](https://iplab.dmi.unict.it/EGO-CH/) - 70 subjects visiting two cultural sites in Sicily, Italy.
- [EPIC-Kitchens 2018](https://epic-kitchens.github.io/2018) - 32 subjects performing unscripted actions in their native environments.
- [Charade-Ego](https://web.archive.org/web/20191210001736/https://allenai.org/plato/charades/) - Paired first-third person videos.
- [EGTEA Gaze+](http://cbs.ic.gatech.edu/fpv/) - 32 subjects, 86 cooking sessions, 28 hours.
- [ADL](https://www.csee.umbc.edu/~hpirsiav/papers/ADLdataset/) - 20 subjects performing daily activities in their native environments.
- [CMU kitchen](http://kitchen.cs.cmu.edu/index.php) - Multimodal, 18 subjects cooking 5 different recipes: brownies, eggs, pizza, salad, sandwich.
- [EgoSeg](http://www.vision.huji.ac.il/egoseg/) - Long term actions (walking, running, driving, etc.)
- [First-Person Social Interactions](http://ai.stanford.edu/~alireza/Disney/) - 8 subjects at disneyworld.
- [UEC Dataset](http://www.cs.cmu.edu/~kkitani/datasets/) - Two choreographed datasets with different egoactions (walk, jump, climb, etc.) + 6 YouTube sports videos.
- [JPL](http://michaelryoo.com/jpl-interaction.html) - Interaction with a robot.
- [FPPA](http://tamaraberg.com/prediction/Prediction.html) - Five subjects performing 5 daily actions.
- [UT Egocentric](http://vision.cs.utexas.edu/projects/egocentric/index.html) - 3-5 hours long videos capturing a person's day.
- [VINST/ Visual Diaries](http://www.csc.kth.se/cvap/vinst/NovEgoMotion.html) - 31 videos capturing the visual experience of a subject walking from metro station to work.
- [Bristol Egocentric Object Interaction (BEOID)](https://www.cs.bris.ac.uk/~damen/BEOID/) - 8 subjects, six locations. Interaction with objects and environment.
- [Object Search Dataset](https://github.com/Mengmi/deepfuturegaze_gan) - 57 sequences of 55 subjects on search and retrieval tasks.
- [UNICT-VEDI](https://web.archive.org/web/20181218162229/http://iplab.dmi.unict.it/VEDI/) - Different subjects visiting a museum.
- [UNICT-VEDI-POI](https://web.archive.org/web/20210416104242/https://iplab.dmi.unict.it/VEDI_POIs/) - Different subjects visiting a museum.
- [Simulated Egocentric Navigations](https://web.archive.org/web/20240324134246/https://iplab.dmi.unict.it/SimulatedEgocentricNavigations/) - Simulated navigations of a virtual agent within a large building.
- [EgoCart](https://web.archive.org/web/20251111135710/https://iplab.dmi.unict.it/EgocentricShoppingCartLocalization/) - Egocentric images collected by a shopping cart in a retail store.
- [Unsupervised Segmentation of Daily Living Activities](https://web.archive.org/web/20220617075812/https://iplab.dmi.unict.it/dailylivingactivities/homeday.html) - Egocentric videos of daily activities.
- [Visual Market Basket Analysis](https://web.archive.org/web/20240430084141/https://iplab.dmi.unict.it/vmba/) - Egocentric images collected by a shopping cart in a retail store.
- [Location Based Segmentation of Egocentric Videos](https://web.archive.org/web/20181218162209/http://iplab.dmi.unict.it/PersonalLocationSegmentation/) - Egocentric videos of daily activities.
- [Recognition of Personal Locations from Egocentric Videos](https://web.archive.org/web/20231004090353/https://iplab.dmi.unict.it/PersonalLocations/) - Egocentric videos clips of daily.
- [EgoGesture](http://www.nlpr.ia.ac.cn/iva/yfzhang/datasets/egogesture.html) - 2k videos from 50 subjects performing 83 gestures.
- [EgoHands](http://vision.soic.indiana.edu/projects/egohands/) - 48 videos of interactions between two people.
- [DoMSEV](http://www.verlab.dcc.ufmg.br/semantic-hyperlapse/cvpr2018-dataset/) - 80 hours/different activities.
- [DR(eye)VE](http://aimagelab.ing.unimore.it/dreyeve) - 74 videos of people driving.
- [THU-READ](http://ivg.au.tsinghua.edu.cn/dataset/THU_READ.php) - 8 subjects performing 40 actions with a head-mounted RGBD camera.
- [EgoDexter](https://handtracker.mpi-inf.mpg.de/projects/OccludedHands/EgoDexter.htm) - 4 sequences with 4 actors (2 female), and varying interactions with various objects and and cluttered background. [[paper]](https://handtracker.mpi-inf.mpg.de/projects/OccludedHands/index.htm)
- [First-Person Hand Action (FPHA)](https://guiggh.github.io/publications/first-person-hands/) - 3D hand-object interaction. Includes 1175 videos belonging to 45 different activity categories performed by 6 actors. [[paper]](https://arxiv.org/pdf/1704.02463.pdf)
- [UTokyo Paired Ego-Video (PEV)](https://yonetaniryo.github.io/fpv_data.html) - 1,226 pairs of first-person clips extracted from the ones recorded synchronously during dyadic conversations.
- [UTokyo Ego-Surf](https://yonetaniryo.github.io/fpv_data.html) - Contains 8 diverse groups of first-person videos recorded synchronously during face-to-face conversations.
- [TEgO: Teachable Egocentric Objects Dataset](https://iamlabumd.github.io/tego/) -  Contains egocentric images of 19 distinct objects taken by two people for training a teachable object recognizer.
- [Multimodal Focused Interaction Dataset](https://web.archive.org/web/20240420135412/https://cvip.computing.dundee.ac.uk/datasets/focusedinteraction/) - Contains 377 minutes of continuous multimodal recording captured during 19 sessions, with 17 conversational partners in 18 different indoor/outdoor locations.

## Workshops/Tutorials

Recurring workshops focused specifically on egocentric vision, useful for tracking the newest work between README updates:

- [Joint Egocentric Vision (EgoVis) Workshop](https://egovis.github.io/) - The current main community venue for egocentric vision, merging the EPIC and Ego4D workshop series with Project Aria initiatives; held at CVPR 2024, 2025, and 2026, hosting challenges and a distinguished paper award.
- [International Workshop on Egocentric Perception, Interaction and Computing (EPIC)](https://epic-workshop.org/) - Long-running forum on egocentric perception across computer vision, machine learning, multimedia, AR/VR, and HCI, with editions at ECCV 2016, ICCV 2017, CVPR 2019, ICCV 2019, CVPR 2020, ECCV 2020, CVPR 2021, ICCV 2021, CVPR 2022, and CVPR 2023 (its final editions were joint with the Ego4D workshop; the series is now folded into EgoVis).
- [International Ego4D Workshop](https://ego4d-data.org/workshops/cvpr23/) - Challenge-centered workshop around the Ego4D benchmark suite, held at CVPR 2022 (joint with the 10th EPIC workshop), ECCV 2022, and CVPR 2023 (joint with the 11th EPIC workshop); now merged into EgoVis.
- [EgoMotion: Egocentric Body Motion Tracking, Synthesis and Action Recognition](https://egomotion-workshop.github.io/) - Workshop on human motion tracking, synthesis, and activity understanding from egocentric multimodal wearable-sensor data, held at CVPR 2024 and ICCV 2025.

## Contribute

This is a work in progress. Contributions welcome! Read the [contribution guidelines](contributing.md) first.
