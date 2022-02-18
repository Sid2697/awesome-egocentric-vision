# Awesome Egocentric Vision [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of egocentric vision resources.

Egocentric (first-person) vision is a sub-field of computer vision that analyses image/video data obtained using a wearable camera simulating a person's visual field.

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
    - [Miscellaneous](#Miscellaneous)

    > Clustered according to the conferences.
    - [CVPR](#CVPR)
    - [ECCV](#ECCV)
    - [ICCV](#ICCV)
    - [WACV](#WACV)
    - [BMVC](#BMVC)

- [Datasets](#datasets)

## Papers

> Clustered in various problem statements.

### Action/Activity Recognition

- [Domain Generalization through Audio-Visual Relative Norm Alignment in First Person Action Recognition](https://openaccess.thecvf.com/content/WACV2022/papers/Planamente_Domain_Generalization_Through_Audio-Visual_Relative_Norm_Alignment_in_First_Person_WACV_2022_paper.pdf) - Mirco Planamente, Chiara Plizzari, Emanuele Alberti, and Barbara Caputo. In WACV 2021.

- [With a Little Help from my Temporal Context: Multimodal Egocentric Action Recognition](https://www.bmvc2021-virtualconference.com/assets/papers/0610.pdf) - Evangelos Kazakos, Jaesung Huh, Arsha Nagrani, Andrew Zisserman, and Dima Damen. In BMVC 2021. [[project page]](https://ekazakos.github.io/MTCN-project/) [[code]](https://github.com/ekazakos/MTCN)

- [Stacked Temporal Attention: Improving First-person Action Recognition by Emphasizing Discriminative Clips](https://www.bmvc2021-virtualconference.com/assets/papers/0243.pdf) - Lijin Yang, Yifei Huang, Yusuke Sugano, and Yoichi Sato. In BMVC 2021. [[project page]](https://www.bmvc2021-virtualconference.com/conference/papers/paper_0243.html)

- [Interactive Prototype Learning for Egocentric Action Recognition](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Interactive_Prototype_Learning_for_Egocentric_Action_Recognition_ICCV_2021_paper.html) - Xiaohan Wang, Linchao Zhu, Heng Wang, and Yi Yang. In ICCV 2021.

- [Multi-Modal Domain Adaptation for Fine-Grained Action Recognition](https://openaccess.thecvf.com/content_CVPR_2020/papers/Munro_Multi-Modal_Domain_Adaptation_for_Fine-Grained_Action_Recognition_CVPR_2020_paper.pdf) - Jonathan Munro and Dima Damen. In CVPR 2020. [[project page]](https://jonmun.github.io/mmsada/) [[code]](https://github.com/jonmun/MM-SADA-code)

- [Integrating Human Gaze Into Attention for Egocentric Activity Recognition](https://openaccess.thecvf.com/content/WACV2021/html/Min_Integrating_Human_Gaze_Into_Attention_for_Egocentric_Activity_Recognition_WACV_2021_paper.html) - Kyle Min, Jason J. Corso. In WACV 2021.

- [EPIC-Fusion: Audio-Visual Temporal Binding for Egocentric Action Recognition](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kazakos_EPIC-Fusion_Audio-Visual_Temporal_Binding_for_Egocentric_Action_Recognition_ICCV_2019_paper.pdf) - Evangelos Kazakos, Arsha Nagrani, Andrew Zisserman, and Dima Damen. In ICCV 2019. [[code]](https://github.com/ekazakos/temporal-binding-network) [[project page]](https://ekazakos.github.io/TBN/)

- [LSTA: Long Short-Term Attention for Egocentric Action Recognition](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sudhakaran_LSTA_Long_Short-Term_Attention_for_Egocentric_Action_Recognition_CVPR_2019_paper.pdf) - Swathikiran Sudhakaran, Sergio Escalera, and Oswald Lanz. In CVPR 2019. [[code]](https://github.com/swathikirans/LSTA)

- [Egocentric Activity Recognition on a Budget](https://openaccess.thecvf.com/content_cvpr_2018/papers/Possas_Egocentric_Activity_Recognition_CVPR_2018_paper.pdf) - Rafael Possas, Sheila Pinto Caceres, and Fabio Ramos. In CVPR 2018. [[demo]](https://youtu.be/GBo4sFNzhtU)

- [From Lifestyle VLOGs to Everyday Interaction](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0733.pdf) - David F. Fouhey, Weicheng Kuo, Alexei A. Efros, and Jitendra Malik. In CVPR 2018. [[project page]](http://web.eecs.umich.edu/~fouhey/2017/VLOG/index.html)

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


### Object/Hand Recognition

- [Whose Hand Is This? Person Identification From Egocentric Hand Gestures](https://openaccess.thecvf.com/content/WACV2021/html/Tsutsui_Whose_Hand_Is_This_Person_Identification_From_Egocentric_Hand_Gestures_WACV_2021_paper.html) - Satoshi Tsutsui, Yanwei Fu, and David J. Crandall. In WACV 2021.

- [Generalizing Hand Segmentation in Egocentric Videos with Uncertainty-Guided Model Adaptation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_Generalizing_Hand_Segmentation_in_Egocentric_Videos_With_Uncertainty-Guided_Model_Adaptation_CVPR_2020_paper.pdf) - Minjie Cai, Feng Lu, and Yoichi Sato. In CVPR 2020. [[code]](https://github.com/cai-mj/UMA)

- [H+O: Unified Egocentric Recognition of 3D Hand-Object Poses and Interactions](https://openaccess.thecvf.com/content_CVPR_2019/papers/Tekin_HO_Unified_Egocentric_Recognition_of_3D_Hand-Object_Poses_and_Interactions_CVPR_2019_paper.pdf) - Bugra Tekin, Federica Bogo, and Marc Pollefeys. In CVPR 2019. [[video]](https://youtu.be/ko6kNZ9DuAk?t=3240)

- [Analysis of Hand Segmentation in the Wild](https://arxiv.org/pdf/1803.03317) - Aisha Urooj Khan and Ali Borji. In CVPR 2018.

- [First-Person Hand Action Benchmark with RGB-D Videos and 3D Hand Pose Annotations](https://openaccess.thecvf.com/content_cvpr_2018/papers/Garcia-Hernando_First-Person_Hand_Action_CVPR_2018_paper.pdf) - Guillermo Garcia-Hernando, Shanxin Yuan, Seungryul Baek, and Tae-Kyun Kim. In CVPR 2018. [[project page]](https://guiggh.github.io/publications/first-person-hands/) [[code]](https://github.com/guiggh/hand_pose_action)

- [Egocentric Gesture Recognition Using Recurrent 3D Convolutional Neural Networks with Spatiotemporal Transformer Modules](https://openaccess.thecvf.com/content_ICCV_2017/papers/Cao_Egocentric_Gesture_Recognition_ICCV_2017_paper.pdf) - Congqi Cao, Yifan Zhang, Yi Wu, Hanqing Lu, and Jian Cheng. In ICCV 2017.

- [Lending a hand: Detecting hands and recognizing activities in complex egocentric interactions](http://homes.sice.indiana.edu/sbambach/papers/iccv-egohands.pdf) - Sven Bambach, Stefan Lee, David J. Crandall, and Chen Yu. In ICCV 2015.

- [Detecting Snap Points in Egocentric Video with a Web Photo Prior](https://www.cs.utexas.edu/~grauman/papers/bo-eccv2014.pdf) - Bo Xiong and Kristen Grauman. In ECCV 2014. [[project page]](http://vision.cs.utexas.edu/projects/ego_snappoints/) [[code]](http://vision.cs.utexas.edu/projects/ego_snappoints/#code)

- [Pixel-level hand detection in ego-centric videos](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Li_Pixel-Level_Hand_Detection_2013_CVPR_paper.pdf) - Cheng Li and Kris M. Kitani. In CVPR 2013. [[video]](https://youtu.be/N756YmLpZyY) [[code]](https://github.com/irllabs/handtrack)

- [Context-based vision system for place and object recognition](https://www.cs.ubc.ca/~murphyk/Papers/iccv03.pdf) - Antonio Torralba, Kevin P. Murphy, William T. Freeman, Mark A. Rubin. In ICCV 2003. [[project page]](https://www.cs.ubc.ca/~murphyk/Vision/placeRecognition.html)


### Action/Gaze Anticipation

- [Learning to Anticipate Egocentric Actions by Imagination](https://arxiv.org/pdf/2101.04924.pdf) - Yu Wu, Linchao Zhu, Xiaohan Wang, Yi Yang, and Fei Wu. In TIP 2021.

- [Forecasting Human-Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf) - Miao Liu, Siyu Tang, Yin Li, and James M. Rehg. In ECCV 2020. [[project page]](https://aptx4869lm.github.io/ForecastingHOI/)

- [How Can I See My Future? FvTraj: Using First-person View for Pedestrian Trajectory Prediction](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520562.pdf) - Huikun Bi, Ruisi Zhang, Tianlu Mao, Zhigang Deng, and Zhaoqi Wang. In ECCV 2020. [[presentation video]](https://youtu.be/HcsyH7zMHAw) [[summary video]](https://youtu.be/X1cSNWT6Gr0)

- [Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior](https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf) - Osama Makansi, Ozgun Cicek, Kevin Buchicchio, and Thomas Brox. In CVPR 2020. [[demo]](https://youtu.be/_9Ml5IFwbSY) [[code]](https://github.com/lmb-freiburg/FLN-EPN-RPN) [[project page]](https://lmb.informatik.uni-freiburg.de/Publications/2020/MCBB20/)

- [EGO-TOPO: Environment Affordances from Egocentric Video](https://openaccess.thecvf.com/content_CVPR_2020/papers/Nagarajan_Ego-Topo_Environment_Affordances_From_Egocentric_Video_CVPR_2020_paper.pdf) - Tushar Nagarajan, Yanghao Li, Christoph Feichtenhofer, and Kristen Grauman. In CVPR 2020. [[project page]](http://vision.cs.utexas.edu/projects/ego-topo/) [[demo]](http://vision.cs.utexas.edu/projects/ego-topo/demo.html)

- [What Would You Expect? Anticipating Egocentric Actions with Rolling-Unrolling LSTMs and Modality Attention](https://arxiv.org/pdf/1905.09035) - Antonino Furnari and Giovanni Maria Farinella. In ICCV 2019 [[code]](https://github.com/fpv-iplab/rulstm) [[demo]](https://youtu.be/buIEKFHTVIg)

- [Digging Deeper into Egocentric Gaze Prediction](https://arxiv.org/pdf/1904.06090) - Hamed R. Tavakoli, Esa Rahtu, Juho Kannala, and Ali Borji. In WACV 2019.

- [Predicting Gaze in Egocentric Video by Learning Task-dependent Attention Transition](https://arxiv.org/pdf/1803.09125) - Yifei Huang, Minjie Cai, Zhenqiang Li, and Yoichi Sato. In ECCV 2018 [[code]](https://github.com/hyf015/egocentric-gaze-prediction)

- [First-Person Activity Forecasting with Online Inverse Reinforcement Learning](https://arxiv.org/pdf/1612.07796) - Nicholas Rhinehart and Kris M. Kitani. In ICCV 2017. [[project page]](https://people.eecs.berkeley.edu/~nrhinehart/darko.html) [[video]](https://youtu.be/rvVoW3iuq-s)

- [Deep future gaze: Gaze anticipation on egocentric videos using adversarial networks](https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Deep_Future_Gaze_CVPR_2017_paper.pdf) - Mengmi Zhang, Keng Teck Ma, Joo Hwee Lim, Qi Zhao, and Jiashi Feng. In CVPR 2017. [[code]](https://github.com/Mengmi/deepfuturegaze_gan)

- [Going deeper into first-person activity recognition](http://www.cs.cmu.edu/~kkitani/pdf/MFK-CVPR2016.pdf) - Minghuang Ma, Haoqi Fan, and Kris M. Kitani. In CVPR 2016.

- [Learning to predict gaze in egocentric video](http://ai.stanford.edu/~alireza/publication/Li-Fathi-Rehg-ICCV13.pdf) - Yin Li, Alireza Fathi, and James M. Rehg. In ICCV 2013.


### Localization

- [Hand-Priming in Object Localization for Assistive Egocentric Vision](https://openaccess.thecvf.com/content_WACV_2020/papers/Lee_Hand-Priming_in_Object_Localization_for_Assistive_Egocentric_Vision_WACV_2020_paper.pdf) - Kyungjun Lee, Abhinav Shrivastava, and Hernisa Kacorri. In WACV 2020.

- [Egocentric Shopping Cart Localization](https://iplab.dmi.unict.it/EgocentricShoppingCartLocalization/home/_paper/egocentric%20shopping%20cart%20localization.pdf) - Emiliano Spera, Antonino Furnari, Sebastiano Battiato, and Giovanni Maria Farinella. In ICPR 2018.

- [Recognizing personal locations from egocentric videos](https://ieeexplore.ieee.org/document/7588113) - Antonino Furnari, Giovanni Maria Farinella, and Sebastiano Battiato. In IEEE Transactions on Human-Machine Systems 2017.

- [Personal-Location-Based Temporal Segmentation of Egocentric Video for Lifelogging Applications](https://iplab.dmi.unict.it/PersonalLocationSegmentation/downloads/furnari2018personal.pdf) - Antonino Furnari, Sebastiano Battiato, and Giovanni Maria Farinella. In Journal of Visual Communication and Image Representation 2017. [[demo]](https://youtu.be/URM0EdYuKEw) [[project page]](https://iplab.dmi.unict.it/EgocentricShoppingCartLocalization/)

- [Egocentric Future Localization](https://openaccess.thecvf.com/content_cvpr_2016/papers/Park_Egocentric_Future_Localization_CVPR_2016_paper.pdf) - Hyun Soo Park, Jyh-Jing Hwang, Yedong Niu, and Jianbo Shi. In CVPR 2016. [[demo]](https://youtu.be/i_9CTMZ60zc)

- [Real-time localization and mapping with wearable active vision](https://ieeexplore.ieee.org/document/1240684) - A.J. Davison, W.W. Mayol, and D.W. Murray. In The Second IEEE and ACM International Symposium 2003.


### Clustering

- [Sr-clustering: Semantic regularized clustering for egocentric photo streams segmentation](https://arxiv.org/pdf/1512.07143) - Mariella Dimiccoli, Marc Bolanosa, Estefania Talavera Maedeh Aghaei, Stavri G. Nikolov, and Petia Radeva. In Computer Vision and Image Understanding 2017.

- [Summarization and Classification of Wearable Camera Streams by Learning the Distributions over Deep Features of Out-of-Sample Image Sequences](https://openaccess.thecvf.com/content_ICCV_2017/papers/Perina_Summarization_and_Classification_ICCV_2017_paper.pdf) - Alessandro Perina, Sadegh Mohammadi, Nebojsa Jojic, and Vittorio Murino. In ICCV 2017.


### Video Summarization

- [Toward storytelling from visual lifelogging: An overview](https://arxiv.org/pdf/1507.06120.pdf) - Marc Bolanos, Mariella Dimiccoli, and Petia Radeva. In IEEE Transactions on Human-Machine Systems 2017.

- [Story-Driven Summarization for Egocentric Video](https://www.cs.utexas.edu/~grauman/papers/lu-grauman-cvpr2013.pdf) - Zheng Lu and Kristen Grauman. In CVPR 2013 [[project page]](http://vision.cs.utexas.edu/projects/egocentric/storydriven.html)

- [Discovering Important People and Objects for Egocentric Video Summarization](http://vision.cs.utexas.edu/projects/egocentric/egocentric_cvpr2012.pdf) - Yong Jae Lee, Joydeep Ghosh, and Kristen Grauman. In CVPR 2012. [[project page]](http://vision.cs.utexas.edu/projects/egocentric/index.html)


### Social Interactions

- [EgoCom: A Multi-person Multi-modal Egocentric Communications Dataset](https://ieeexplore.ieee.org/document/9200754) - Curtis G. Northcutt, Shengxin Zha, Steven Lovegrove, and Richard Newcombe. In PAMI 2020.

- [Deep Dual Relation Modeling for Egocentric Interaction Recognition](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Deep_Dual_Relation_Modeling_for_Egocentric_Interaction_Recognition_CVPR_2019_paper.pdf) - Haoxin Li, Yijun Cai, and Wei-Shi Zheng. In CVPR 2019.

- [Recognizing Micro-Actions and Reactions from Paired Egocentric Videos](https://openaccess.thecvf.com/content_cvpr_2016/papers/Yonetani_Recognizing_Micro-Actions_and_CVPR_2016_paper.pdf) - Ryo Yonetani, Kris M. Kitani, and Yoichi Sato. In CVPR 2016.


### Pose Estimation

- [Automatic Calibration of the Fisheye Camera for Egocentric 3D Human Pose Estimation From a Single Image](https://openaccess.thecvf.com/content/WACV2021/html/Zhang_Automatic_Calibration_of_the_Fisheye_Camera_for_Egocentric_3D_Human_WACV_2021_paper.html) - Yahui Zhang, Shaodi You, and Theo Gevers. In WACV 2021.

- [You2Me: Inferring Body Pose in Egocentric Video via First and Second Person Interactions](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ng_You2Me_Inferring_Body_Pose_in_Egocentric_Video_via_First_and_CVPR_2020_paper.pdf) - Evonne Ng, Donglai Xiang, Hanbyul Joo, and Kristen Grauman. In CVPR 2020. [[demo]](http://vision.cs.utexas.edu/projects/you2me/demo.mp4) [[project page]](http://vision.cs.utexas.edu/projects/you2me/) [[dataset]](https://github.com/facebookresearch/you2me/tree/master/data#) [[code]](https://github.com/facebookresearch/you2me#)

- [Ego-Pose Estimation and Forecasting as Real-Time PD Control](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yuan_Ego-Pose_Estimation_and_Forecasting_As_Real-Time_PD_Control_ICCV_2019_paper.pdf) - Ye Yuan and Kris Kitani. In ICCV 2019. [[code]](https://github.com/Khrylx/EgoPose) [[project page]](https://www.ye-yuan.com/ego-pose) [[demo]](https://youtu.be/968IIDZeWE0)

- [xR-EgoPose: Egocentric 3D Human Pose From an HMD Camera](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tome_xR-EgoPose_Egocentric_3D_Human_Pose_From_an_HMD_Camera_ICCV_2019_paper.pdf) - Denis Tome, Patrick Peluse, Lourdes Agapito, and Hernan Badino. In ICCV 2019. [[demo]](https://youtu.be/zem03fZWLrQ) [[dataset]](https://github.com/facebookresearch/xR-EgoPose)

- [Seeing Invisible Poses: Estimating 3D Body Pose from Egocentric Video](https://openaccess.thecvf.com/content_cvpr_2017/papers/Jiang_Seeing_Invisible_Poses_CVPR_2017_paper.pdf) - Hao Jiang and Kristen Grauman. In CVPR 2017.

- [First-Person Pose Recognition using Egocentric Workspaces](https://openaccess.thecvf.com/content_cvpr_2015/papers/Rogez_First-Person_Pose_Recognition_2015_CVPR_paper.pdf) - Gregory Rogez, James S. Supancic, and Deva Ramanan. In CVPR 2015.

### Human Object Interaction

- [Hand-Object Contact Prediction via Motion-Based Pseudo-Labeling and Guided Progressive Label Correction](https://www.bmvc2021-virtualconference.com/assets/papers/0096.pdf) - Takuma Yagi, Md Tasnimul Hasan, and Yoichi Sato. In BMVC 2021. [[project page]](https://www.bmvc2021-virtualconference.com/conference/papers/paper_0096.html) [[code]](https://github.com/takumayagi/hand_object_contact_prediction/)

- [The MECCANO Dataset: Understanding Human-Object Interactions from Egocentric Videos in an Industrial-like Domain](https://arxiv.org/abs/2010.05654) - Francesco Ragusa, Antonino Furnari, Salvatore Livatino, and Giovanni Maria Farinella. In WACV 2021. [[project page]](https://iplab.dmi.unict.it/MECCANO/)

- [Forecasting Human-Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf) - Miao Liu, Siyu Tang, Yin Li, and James M. Rehg. In ECCV 2020. [[project page]](https://aptx4869lm.github.io/ForecastingHOI/)

- [You-Do, I-Learn: Discovering Task Relevant Objects and their Modes of Interaction from Multi-User Egocentric Video](https://dimadamen.github.io/You-Do-I-Learn/Damen_BMVC2014.pdf) - Dima Damen, Tessid Leelasawassuk, Osian Haines, Andrew Calway,and Walterio Mayol-Cuevas. In BMVC 2014 [[project page]](http://www.bmva.org/bmvc/2014/papers/paper059/index.html)

- [Automated capture and delivery of assistive task guidance with an eyewear computer: the GlaciAR system](https://arxiv.org/pdf/1701.02586) -  Teesid Leelasawassuk, Dima Damen, and Walterio Mayol-Cuevas. In Augmented Human International Conference, ACM 2017.


### Temporal Boundary Detection

- [Trespassing the Boundaries: Labeling Temporal Bounds for Object Interactions in Egocentric Video](https://openaccess.thecvf.com/content_ICCV_2017/papers/Moltisanti_Trespassing_the_Boundaries_ICCV_2017_paper.pdf) - Davide Moltisanti, Michael Wray, Walterio Mayol-Cuevas, and Dima Damen. In ICCV 2017.

- [Temporal segmentation of egocentric videos](https://www.cse.iitd.ac.in/~chetan/papers/egocentric-cvpr14.pdf) -Yair Poleg, Chetan Arora, and Shmuel Peleg. In CVPR 2014.


### Privacy in Egocentric Videos

- [Is Sharing of Egocentric Video Giving Away Your Biometric Signature?](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620392.pdf) - Daksh Thapar, Chetan Arora, and Aditya Nigam. In ECCV 2020. [[project page]](https://egocentricbiometric.github.io)

- [Mitigating Bystander Privacy Concerns in Egocentric Activity Recognition with Deep Learning and Intentional Image Degradation](http://users.ece.utexas.edu/~ethomaz/papers/j2.pdf) - Mariella Dimiccoli, Juan Marin, and Edison Thomaz. In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies 2018.

- [Privacy-Preserving Human Activity Recognition from Extreme Low Resolution](https://arxiv.org/pdf/1604.03196) - Michael S. Ryoo, Brandon Rothrock, Charles Fleming, and Hyun Jong Yang. In AAAI 2017.

- [Ego-Surfing First Person Videos](https://openaccess.thecvf.com/content_cvpr_2015/papers/Yonetani_Ego-Surfing_First-Person_Videos_2015_CVPR_paper.pdf) - Ryo Yonetani, Kris M. Kitani, and Yoichi Sato. In CVPR 2015.


### Multiple Egocentric Tasks

- [Ego4D: Around the World in 3,000 Hours of Egocentric Video](https://arxiv.org/abs/2110.07058) - Kristen Grauman, Andrew Westbury, Eugene Byrne, Zachary Chavis, Antonino Furnari, Rohit Girdhar, Jackson Hamburger, Hao Jiang, Miao Liu, Xingyu Liu, Miguel Martin, Tushar Nagarajan, Ilija Radosavovic, Santhosh Kumar Ramakrishnan, Fiona Ryan, Jayant Sharma, Michael Wray, Mengmeng Xu, Eric Zhongcong Xu, Chen Zhao, Siddhant Bansal, Dhruv Batra, Vincent Cartillier, Sean Crane, Tien Do, Morrie Doulaty, Akshay Erapalli, Christoph Feichtenhofer, Adriano Fragomeni, Qichen Fu, Christian Fuegen, Abrham Gebreselasie, Cristina Gonzalez, James Hillis, Xuhua Huang, Yifei Huang, Wenqi Jia, Weslie Khoo, Jachym Kolar, Satwik Kottur, Anurag Kumar, Federico Landini, Chao Li, Yanghao Li, Zhenqiang Li, Karttikeya Mangalam, Raghava Modhugu, Jonathan Munro, Tullie Murrell, Takumi Nishiyasu, Will Price, Paola Ruiz Puentes, Merey Ramazanova, Leda Sari, Kiran Somasundaram, Audrey Southerland, Yusuke Sugano, Ruijie Tao, Minh Vo, Yuchen Wang, Xindi Wu, Takuma Yagi, Yunyi Zhu, Pablo Arbelaez, David Crandall, Dima Damen, Giovanni Maria Farinella, Bernard Ghanem, Vamsi Krishna Ithapu, C. V. Jawahar, Hanbyul Joo, Kris Kitani, Haizhou Li, Richard Newcombe, Aude Oliva, Hyun Soo Park, James M. Rehg, Yoichi Sato, Jianbo Shi, Mike Zheng Shou, Antonio Torralba, Lorenzo Torresani, Mingfei Yan, and Jitendra Malik. In arXiv. [[Github]](https://github.com/EGO4D) [[project page]](https://ego4d-data.org) [[video]](https://drive.google.com/file/d/1oknfQIH9w1rXy6I1j5eUE6Cqh96UwZ4L/view?usp=sharing)


### Miscellaneous

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

### CVPR

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

- [From Lifestyle VLOGs to Everyday Interaction](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0733.pdf) - David F. Fouhey, Weicheng Kuo, Alexei A. Efros, and Jitendra Malik. In CVPR 2018. [[project page]](http://web.eecs.umich.edu/~fouhey/2017/VLOG/index.html)

- [Actor and Observer: Joint Modeling of First and Third-Person Videos](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sigurdsson_Actor_and_Observer_CVPR_2018_paper.pdf) - Gunnar A. Sigurdsson, Abhinav Gupta, Cordelia Schmid, Ali Farhadi, and Karteek Alahari. In CVPR 2018. [[code]](https://github.com/gsig/actor-observer)

- [Analysis of Hand Segmentation in the Wild](https://arxiv.org/pdf/1803.03317) - Aisha Urooj Khan and Ali Borji. In CVPR 2018.

- [First-Person Hand Action Benchmark with RGB-D Videos and 3D Hand Pose Annotations](https://openaccess.thecvf.com/content_cvpr_2018/papers/Garcia-Hernando_First-Person_Hand_Action_CVPR_2018_paper.pdf) - Guillermo Garcia-Hernando, Shanxin Yuan, Seungryul Baek, and Tae-Kyun Kim. In CVPR 2018. [[project page]](https://guiggh.github.io/publications/first-person-hands/) [[code]](https://github.com/guiggh/hand_pose_action)

- [Egocentric Basketball Motion Planning from a Single First-Person Image](https://openaccess.thecvf.com/content_cvpr_2018/papers/Bertasius_Egocentric_Basketball_Motion_CVPR_2018_paper.pdf) - Gedas Bertasius, Aaron Chan, and Jianbo Shi. In CVPR 2018. [[demo]](https://youtu.be/wRRRl4QsUQg)

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

### ECCV 

- [Forecasting Human-Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf) - Miao Liu, Siyu Tang, Yin Li, and James M. Rehg. In ECCV 2020. [[project page]](https://aptx4869lm.github.io/ForecastingHOI/)

- [How Can I See My Future? FvTraj: Using First-person View for Pedestrian Trajectory Prediction](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520562.pdf) - Huikun Bi, Ruisi Zhang, Tianlu Mao, Zhigang Deng, and Zhaoqi Wang. In ECCV 2020. [[presentation video]](https://youtu.be/HcsyH7zMHAw) [[summary video]](https://youtu.be/X1cSNWT6Gr0)

- [Forecasting Human-Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460681.pdf) - Miao Liu, Siyu Tang, Yin Li, and James M. Rehg. In ECCV 2020. [[project page]](https://aptx4869lm.github.io/ForecastingHOI/)

- [Is Sharing of Egocentric Video Giving Away Your Biometric Signature?](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620392.pdf) - Daksh Thapar, Chetan Arora, and Aditya Nigam. In ECCV 2020. [[project page]](https://egocentricbiometric.github.io)

- [In the eye of beholder: Joint learning of gaze and actions in first person video](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yin_Li_In_the_Eye_ECCV_2018_paper.pdf) - Yin Li, Miao Liu, and James M. Rehg. In ECCV 2018.

- [Predicting Gaze in Egocentric Video by Learning Task-dependent Attention Transition](https://arxiv.org/pdf/1803.09125) - Yifei Huang, Minjie Cai, Zhenqiang Li, and Yoichi Sato. In ECCV 2018 [[code]](https://github.com/hyf015/egocentric-gaze-prediction)

- [Detecting engagement in egocentric video](http://www.cs.utexas.edu/~grauman/papers/su-eccv2016-ego.pdf) - Yu-Chuan Su and Kristen Grauman. In ECCV 2016.

- [Detecting Snap Points in Egocentric Video with a Web Photo Prior](https://www.cs.utexas.edu/~grauman/papers/bo-eccv2014.pdf) - Bo Xiong and Kristen Grauman. In ECCV 2014. [[project page]](http://vision.cs.utexas.edu/projects/ego_snappoints/) [[code]](http://vision.cs.utexas.edu/projects/ego_snappoints/#code)

- [Learning to recognize daily actions using gaze](http://ai.stanford.edu/~alireza/publication/ECCV12.pdf) - Alireza Fathi, Yin Li, and James M. Rehg. In ECCV 2012.

### ICCV

- [Interactive Prototype Learning for Egocentric Action Recognition](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Interactive_Prototype_Learning_for_Egocentric_Action_Recognition_ICCV_2021_paper.html) - Xiaohan Wang, Linchao Zhu, Heng Wang, and Yi Yang. In ICCV 2021.

- [EPIC-Fusion: Audio-Visual Temporal Binding for Egocentric Action Recognition](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kazakos_EPIC-Fusion_Audio-Visual_Temporal_Binding_for_Egocentric_Action_Recognition_ICCV_2019_paper.pdf) - Evangelos Kazakos, Arsha Nagrani, Andrew Zisserman, and Dima Damen. In ICCV 2019. [[code]](https://github.com/ekazakos/temporal-binding-network) [[project page]](https://ekazakos.github.io/TBN/)

- [What Would You Expect? Anticipating Egocentric Actions with Rolling-Unrolling LSTMs and Modality Attention](https://arxiv.org/pdf/1905.09035) - Antonino Furnari and Giovanni Maria Farinella. In ICCV 2019 [[code]](https://github.com/fpv-iplab/rulstm) [[demo]](https://youtu.be/buIEKFHTVIg)

- [Ego-Pose Estimation and Forecasting as Real-Time PD Control](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yuan_Ego-Pose_Estimation_and_Forecasting_As_Real-Time_PD_Control_ICCV_2019_paper.pdf) - Ye Yuan and Kris Kitani. In ICCV 2019. [[code]](https://github.com/Khrylx/EgoPose) [[project page]](https://www.ye-yuan.com/ego-pose) [[demo]](https://youtu.be/968IIDZeWE0)

- [xR-EgoPose: Egocentric 3D Human Pose From an HMD Camera](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tome_xR-EgoPose_Egocentric_3D_Human_Pose_From_an_HMD_Camera_ICCV_2019_paper.pdf) - Denis Tome, Patrick Peluse, Lourdes Agapito, and Hernan Badino. In ICCV 2019. [[demo]](https://youtu.be/zem03fZWLrQ) [[dataset]](https://github.com/facebookresearch/xR-EgoPose)

- [Jointly Recognizing Object Fluents and Tasks in Egocentric Videos](https://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_Jointly_Recognizing_Object_ICCV_2017_paper.pdf) - Yang Liu, Ping Wei, and Song-Chun Zhu. In ICCV 2017.

- [Egocentric Gesture Recognition Using Recurrent 3D Convolutional Neural Networks with Spatiotemporal Transformer Modules](https://openaccess.thecvf.com/content_ICCV_2017/papers/Cao_Egocentric_Gesture_Recognition_ICCV_2017_paper.pdf) - Congqi Cao, Yifan Zhang, Yi Wu, Hanqing Lu, and Jian Cheng. In ICCV 2017.

- [First-Person Activity Forecasting with Online Inverse Reinforcement Learning](https://arxiv.org/pdf/1612.07796) - Nicholas Rhinehart and Kris M. Kitani. In ICCV 2017. [[project page]](https://people.eecs.berkeley.edu/~nrhinehart/darko.html) [[video]](https://youtu.be/rvVoW3iuq-s)

- [Summarization and Classification of Wearable Camera Streams by Learning the Distributions over Deep Features of Out-of-Sample Image Sequences](https://openaccess.thecvf.com/content_ICCV_2017/papers/Perina_Summarization_and_Classification_ICCV_2017_paper.pdf) - Alessandro Perina, Sadegh Mohammadi, Nebojsa Jojic, and Vittorio Murino. In ICCV 2017.

- [Trespassing the Boundaries: Labeling Temporal Bounds for Object Interactions in Egocentric Video](https://openaccess.thecvf.com/content_ICCV_2017/papers/Moltisanti_Trespassing_the_Boundaries_ICCV_2017_paper.pdf) - Davide Moltisanti, Michael Wray, Walterio Mayol-Cuevas, and Dima Damen. In ICCV 2017.

- [Generating Notifications for Missing Actions: Don't forget to turn the lights off!](https://homes.cs.washington.edu/~ali/alarm-iccv.pdf) - Bilge Soran, Ali Farhadi, and Linda Shapiro. In ICCV 2015.

- [Lending a hand: Detecting hands and recognizing activities in complex egocentric interactions](http://homes.sice.indiana.edu/sbambach/papers/iccv-egohands.pdf) - Sven Bambach, Stefan Lee, David J. Crandall, and Chen Yu. In ICCV 2015.

- [Learning to predict gaze in egocentric video](http://ai.stanford.edu/~alireza/publication/Li-Fathi-Rehg-ICCV13.pdf) - Yin Li, Alireza Fathi, and James M. Rehg. In ICCV 2013.

- [Context-based vision system for place and object recognition](https://www.cs.ubc.ca/~murphyk/Papers/iccv03.pdf) - Antonio Torralba, Kevin P. Murphy, William T. Freeman, Mark A. Rubin. In ICCV 2003. [[project page]](https://www.cs.ubc.ca/~murphyk/Vision/placeRecognition.html)

### WACV

- [Domain Generalization through Audio-Visual Relative Norm Alignment in First Person Action Recognition](https://openaccess.thecvf.com/content/WACV2022/papers/Planamente_Domain_Generalization_Through_Audio-Visual_Relative_Norm_Alignment_in_First_Person_WACV_2022_paper.pdf) - Mirco Planamente, Chiara Plizzari, Emanuele Alberti, and Barbara Caputo. In WACV 2021.

- [Integrating Human Gaze Into Attention for Egocentric Activity Recognition](https://openaccess.thecvf.com/content/WACV2021/html/Min_Integrating_Human_Gaze_Into_Attention_for_Egocentric_Activity_Recognition_WACV_2021_paper.html) - Kyle Min, Jason J. Corso. In WACV 2021.

- [Whose Hand Is This? Person Identification From Egocentric Hand Gestures](https://openaccess.thecvf.com/content/WACV2021/html/Tsutsui_Whose_Hand_Is_This_Person_Identification_From_Egocentric_Hand_Gestures_WACV_2021_paper.html) - Satoshi Tsutsui, Yanwei Fu, and David J. Crandall. In WACV 2021.

- [The MECCANO Dataset: Understanding Human-Object Interactions from Egocentric Videos in an Industrial-like Domain](https://arxiv.org/abs/2010.05654) - Francesco Ragusa, Antonino Furnari, Salvatore Livatino, and Giovanni Maria Farinella. In WACV 2021. [[project page]](https://iplab.dmi.unict.it/MECCANO/)

- [Automatic Calibration of the Fisheye Camera for Egocentric 3D Human Pose Estimation From a Single Image](https://openaccess.thecvf.com/content/WACV2021/html/Zhang_Automatic_Calibration_of_the_Fisheye_Camera_for_Egocentric_3D_Human_WACV_2021_paper.html) - Yahui Zhang, Shaodi You, and Theo Gevers. In WACV 2021.

- [Hand-Priming in Object Localization for Assistive Egocentric Vision](https://openaccess.thecvf.com/content_WACV_2020/papers/Lee_Hand-Priming_in_Object_Localization_for_Assistive_Egocentric_Vision_WACV_2020_paper.pdf) - Kyungjun Lee, Abhinav Shrivastava, and Hernisa Kacorri. In WACV 2020.

- [Digging Deeper into Egocentric Gaze Prediction](https://arxiv.org/pdf/1904.06090) - Hamed R. Tavakoli, Esa Rahtu, Juho Kannala, and Ali Borji. In WACV 2019.

- [EGO-SLAM: A Robust Monocular SLAM for Egocentric Videos](https://www.cse.iitd.ac.in/~chetan/papers/wacv19-egoslam.pdf) - Suvam Patra, Kartikeya Gupta, Faran Ahmad, Chetan Arora, and Subhashis Banerjee. In WACV 2019. [[code]](https://github.com/IITD-COMPUTER-VISION-GROUP/ego-slam)

- [Compact CNN for Indexing Egocentric Videos](https://www.cs.huji.ac.il/~peleg/papers/wacv16-cnn-indexing.pdf) - Yair Poleg, Ariel Ephrat, Shmuel Peleg, and Chetan Arora. In WACV 2016.

### BMVC

- [With a Little Help from my Temporal Context: Multimodal Egocentric Action Recognition](https://www.bmvc2021-virtualconference.com/assets/papers/0610.pdf) - Evangelos Kazakos, Jaesung Huh, Arsha Nagrani, Andrew Zisserman, and Dima Damen. In BMVC 2021. [[project page]](https://ekazakos.github.io/MTCN-project/) [[code]](https://github.com/ekazakos/MTCN)

- [Stacked Temporal Attention: Improving First-person Action Recognition by Emphasizing Discriminative Clips](https://www.bmvc2021-virtualconference.com/assets/papers/0243.pdf) - Lijin Yang, Yifei Huang, Yusuke Sugano, and Yoichi Sato. In BMVC 2021. [[project page]](https://www.bmvc2021-virtualconference.com/conference/papers/paper_0243.html)

- [Hand-Object Contact Prediction via Motion-Based Pseudo-Labeling and Guided Progressive Label Correction](https://www.bmvc2021-virtualconference.com/assets/papers/0096.pdf) - Takuma Yagi, Md Tasnimul Hasan, and Yoichi Sato. In BMVC 2021. [[project page]](https://www.bmvc2021-virtualconference.com/conference/papers/paper_0096.html) [[code]](https://github.com/takumayagi/hand_object_contact_prediction/)

- [You-Do, I-Learn: Discovering Task Relevant Objects and their Modes of Interaction from Multi-User Egocentric Video](https://dimadamen.github.io/You-Do-I-Learn/Damen_BMVC2014.pdf) - Dima Damen, Tessid Leelasawassuk, Osian Haines, Andrew Calway,and Walterio Mayol-Cuevas. In BMVC 2014 [[project page]](http://www.bmva.org/bmvc/2014/papers/paper059/index.html)


## Datasets

- [Ego4D](https://ego4d-data.org) - 3,025 hours of daily-life activity video spanning hundreds of scenarios (household, outdoor, workplace, leisure, etc.) captured by 855 unique camera wearers from 74 worldwide locations and 9 different countries.
- [EgoCom](https://github.com/facebookresearch/EgoCom-Dataset) - A natural conversations dataset containing multi-modal human communication data captured simultaneously from the participants' egocentric perspectives.
- [TREK-100](https://machinelearning.uniud.it/datasets/trek100/) - Object tracking in first person vision.
- [MECCANO](https://iplab.dmi.unict.it/MECCANO/) - 20 subject assembling a toy motorbike.
- [EPIC-Kitchens 2020](https://epic-kitchens.github.io/2020-100) - Subjects performing unscripted actions in their native environments.
- [EPIC-Tent](https://data.bristol.ac.uk/data/dataset/2ite3tu1u53n42hjfh3886sa86) - 29 participants assembling a tent while wearing two head-mounted cameras. [[paper]](https://ieeexplore.ieee.org/document/9022634)
- [EGO-CH](https://iplab.dmi.unict.it/EGO-CH/) - 70 subjects visiting two cultural sites in Sicily, Italy.
- [EPIC-Kitchens 2018](https://epic-kitchens.github.io/2018) - 32 subjects performing unscripted actions in their native environments.
- [Charade-Ego](https://allenai.org/plato/charades/) - Paired first-third person videos.
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
- [UNICT-VEDI](http://iplab.dmi.unict.it/VEDI/) - Different subjects visiting a museum.
- [UNICT-VEDI-POI](http://iplab.dmi.unict.it/VEDI_POIs/) - Different subjects visiting a museum.
- [Simulated Egocentric Navigations](http://iplab.dmi.unict.it/SimulatedEgocentricNavigations/) - Simulated navigations of a virtual agent within a large building.
- [EgoCart](http://iplab.dmi.unict.it/EgocentricShoppingCartLocalization/) - Egocentric images collected by a shopping cart in a retail store.
- [Unsupervised Segmentation of Daily Living Activities](http://iplab.dmi.unict.it/dailylivingactivities) - Egocentric videos of daily activities.
- [Visual Market Basket Analysis](http://iplab.dmi.unict.it/vmba/) - Egocentric images collected by a shopping cart in a retail store.
- [Location Based Segmentation of Egocentric Videos](http://iplab.dmi.unict.it/PersonalLocationSegmentation/) - Egocentric videos of daily activities.
- [Recognition of Personal Locations from Egocentric Videos](http://iplab.dmi.unict.it/PersonalLocations/) - Egocentric videos clips of daily.
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
- [Multimodal Focused Interaction Dataset](https://cvip.computing.dundee.ac.uk/datasets/focusedinteraction/) - Contains 377 minutes of continuous multimodal recording captured during 19 sessions, with 17 conversational partners in 18 different indoor/outdoor locations.

## Contribute

This is a work in progress. Contributions welcome! Read the [contribution guidelines](contributing.md) first.
