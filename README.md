# Resource---Emerging-Mixed-Traffic-of-AV&HDV
Online Resource Repository: Datasets, Simulation Platforms, and Relevant Publications on Emerging Mixed Traffic of Automated Vehicles and Human-driven Vehicles

**Project Website**: [https://qiqiqi.gitbook.io/resource-for-emerging-mixed-traffic-of-av-and-hdv/](https://qiqiqi.gitbook.io/resource-for-emerging-mixed-traffic-of-av-and-hdv/) 

_This project is part of the [2023 WiE-ITS & YP-ITS Fellowship Program](https://ieee-itss.org/2023-fellowships-for-young-researchers-promoting-diversity-and-leadership-in-its/). The project is developed by [Yongqi Dong](https://yongqidong.github.io/)._

# Background & Aims
Fully-automated vehicles (AVs) are expected to be beneficial to traffic safety and efficiency. Although steady development of higher levels of AVs is witnessed, their deployment will not happen overnight. There will be a transition period during which AVs with various automation levels will share the road with human drivers leading to a mixed traffic condition. 

Data-driven, simulation-based, and empirical research are considered critical for understanding the dynamics of mixed traffic flow, interactive behaviors of Automated Vehicles (AVs) and human-driven vehicles (HDVs), as well as analyzing and evaluating the impact of AVs on traffic safety and efficiency. 

Emerging datasets, especially real-world empirical data, allow researchers to investigate what could happen in the future mixed traffic. The spring-up of various open-sourced datasets from both industry (e.g., Audi Autonomous Driving Dataset (A2D2), TuSimple) and academia (e.g., Berkeley Deep Drive： BDD 100k, UCF-SST-CitySim-Dataset) enables data-driven studies, making modeling and learning from data possible. However, different data sets might be applicable to selected tasks only. There is no integrated data set collection and description yet. Furthermore, the unfamiliarity of the research community with advanced data processing and analysis tools also hampers data-driven research.

Simulation-based research, on the other hand, enables model verification and evaluation in simulated environments. Especially, when training a machine learning based automated driving model, simulation is a must. However, there are also various types of simulation platforms and tools, e.g., SUMO, PTV Vissim, CommonRoad, and CARLA. Different platforms and tools are sometimes more suitable for certain tasks while not applicable to others. Thus an integrated description of these available platforms and tools regarding their application scenarios would be very helpful for researchers.

Lastly, there are already some empirical field tests carried out in the real world, e.g., MegaVanderTest in the USA and OpenACC. A summary of the evidence, lessons, and knowledge learned from these field tests would be beneficial to future test arrangements and studies, while is missing.

With all these gaps above, this project aims to provide an open-sourced online resource repository website to push forward the data-driven, simulation-based, and empirical study on emerging mixed traffic. To be specific, the resource repository:

·Arranges a collection of various datasets related to automated vehicles and mixed traffic research with summarized descriptions of the datasets’ application scenarios and quick-starting guidelines;

·Provides an integrated description of simulation platforms and tools and pinpoint their strengths and weaknesses together with the most suitable application cases;

·Summarizes the evidence, lessons, and knowledge learned from past field tests worldwide with a list of relevant publications;

·Designs a Wiki website with crow-editing functions making everyone can contribute to the editing with an approving mechanism;

The resource repository will be promoted in future IEEE ITSS conferences and events, e.g., ITSC and IV.

# Relevant Datasets
[Berkeley Deep Drive: BDD 100k](https://bdd-data.berkeley.edu/)  
[Waymo Open Dataset](https://waymo.com/open/)  
[Lyft level-5 open dataset](https://woven.toyota/en/prediction-dataset)  
[Honda Driving Datasets](https://openaccess.thecvf.com/content_cvpr_2018/html/Ramanishka_Toward_Driving_Scene_CVPR_2018_paper.html): [HDD](https://openaccess.thecvf.com/content_cvpr_2018/html/Ramanishka_Toward_Driving_Scene_CVPR_2018_paper.html); [H3D](https://openaccess.thecvf.com/content_cvpr_2018/html/Ramanishka_Toward_Driving_Scene_CVPR_2018_paper.html); [HSD](https://arxiv.org/abs/1905.12708); [HEV-I](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8794474&casa_token=7cV3u2F9ljQAAAAA:jKUoLX_oWokQ_6qu5sn43uepvpKSfJBz-w6Ha1XEPnCyo5TkVAO9GdUd28RLP_8av7U3ItIhMw&tag=1); [HAD](https://arxiv.org/abs/1911.06978); [TITAN](https://arxiv.org/abs/2003.13886)  
[D^2-City](https://paperswithcode.com/dataset/d2city)  
[DBNet](http://www.dbehavior.net/)  
[CitySim](https://github.com/ozheng1993/UCF-SST-CitySim-Dataset)  
[highD](https://www.highd-dataset.com/), [inD](https://www.ind-dataset.com/), [rounD](https://www.round-dataset.com/), [exiD](https://www.exid-dataset.com/)  
[KITTI](https://www.cvlibs.net/datasets/kitti/)  
[nuScenes](https://www.nuscenes.org/nuscenes)  
[Argoverse 1 & 2](https://www.argoverse.org/index.html)  
[CULane](https://xingangpan.github.io/projects/CULane.html)  
[ApolloScape Baidu Inc.](http://apolloscape.auto/scene.html)  
[TuSimple](https://github.com/TuSimple/tusimple-benchmark/wiki)  
[KAIST Multi-Spectral](https://sites.google.com/view/multispectral/)  
[KAIST Urban Dataset](https://sites.google.com/view/complex-urban-dataset)  
[Belgium Traffic Sign Dataset](http://www.vision.ee.ethz.ch/~timofter/traffic_signs/)  
[CamVid](http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/)  
[JAAD York University](http://data.nvision2.eecs.yorku.ca/JAAD_dataset/)  
[UAH University of Alcalá](http://www.robesafe.uah.es/personal/eduardo.romera/uah-driveset/)  
[Udacity self-driving-car](https://github.com/udacity/self-driving-car)  
[LISA: Laboratory for Intelligent & Safe Automobiles](http://cvrr.ucsd.edu/LISA/datasets.html)  
[MIT DriveSeg: Dynamic Driving Scene Segmentation](https://agelab.mit.edu/driveseg)  
[Audi Autonomous Driving Dataset (A2D2)](https://www.a2d2.audi/a2d2/en.html)  
[Mapillary Vistas](https://www.mapillary.com/dataset/vistas?pKey=1697734990430617)  
[CADC: Canadian Adverse Driving Conditions Dataset](http://cadcd.uwaterloo.ca/)  
[Lidar Data of Washington DC](https://registry.opendata.aws/dc-lidar/)  
[Oxford RobotCar](http://robotcar-dataset.robots.ox.ac.uk/)  
[V2V4Real](https://mobility-lab.seas.ucla.edu/v2v4real/)  
[Safety Pilot Model Deployment Data](https://catalog.data.gov/dataset/safety-pilot-model-deployment-data)  
[INTERACTION](http://interaction-dataset.com/)  

# Relevant Simulation Platforms
[SUMO](https://sumo.dlr.de/docs/index.html)  
[PTV Vissim](https://www.myptv.com/en-us/mobility-software/ptv-vissim)  
[CARLA](https://carla.org/)  
[SUMMIT](https://paperswithcode.com/dataset/summit)  
[LGSVL Simulator](https://github.com/lgsvl/simulator-2019.05-obsolete)  
[AirSim](https://microsoft.github.io/AirSim/)  
[Deepdrive](https://deepdrive.io/)  
[Highway-env](https://github.com/Farama-Foundation/HighwayEnv)  
[OpenCDA](https://github.com/ucla-mobility/OpenCDA#readme)  

# Relevant Publications
**_Publication regarding data processing_**
Hu, X., Zheng, Z., Chen, D., Zhang, X. and Sun, J., 2022. Processing, assessing, and enhancing the Waymo autonomous vehicle open dataset for driving behavior research. Transportation Research Part C: Emerging Technologies, 134, p.103490. https://doi.org/10.1016/j.trc.2021.103490  
Li, G., Jiao, Y., Knoop, V.L., Calvert, S.C. and van Lint, J.W.C., 2023. Large Car-following Data Based on Lyft level-5 Open Dataset: Following Autonomous Vehicles vs. Human-driven Vehicles. arXiv preprint arXiv:2305.18921.  
Li, G., Jiao, Y., Calvert, S.C. and van Lint, J.W.C., 2023. A Comparative Conflict Resolution Dataset Derived from Argoverse-2: Scenarios with vs. without Autonomous Vehicles. arXiv preprint arXiv:2308.13839.  
Xia, X., Meng, Z., Han, X., Li, H., Tsukiji, T., Xu, R., Zheng, Z. and Ma, J., 2023. An automated driving systems data acquisition and analytics platform. Transportation research part C: emerging technologies, 151, p.104120. https://doi.org/10.1016/j.trc.2023.104120  

**_Publication regarding mixed traffic_**
Andreotti, E., Boyraz, P. and Selpi, S., 2020. Mathematical definitions of scene and scenario for analysis of automated driving systems in mixed-traffic simulations. IEEE Transactions on Intelligent Vehicles, 6(2), pp.366-375.
Ard, T., Dollar, R.A., Vahidi, A., Zhang, Y. and Karbowski, D., 2020. Microsimulation of energy and flow effects from optimal automated driving in mixed traffic. Transportation Research Part C: Emerging Technologies, 120, p.102806.
Ard, T., Guo, L., Dollar, R.A., Fayazi, A., Goulet, N., Jia, Y., Ayalew, B. and Vahidi, A., 2021. Energy and flow effects of optimal automated driving in mixed traffic: Vehicle-in-the-loop experimental results. Transportation Research Part C: Emerging Technologies, 130, p.103168.
Azam, M., Hassan, S.A. and Che Puan, O., 2022. Autonomous Vehicles in Mixed Traffic Conditions—A Bibliometric Analysis. Sustainability, 14(17), p.10743.
Calvert, S.C. and van Arem, B., 2020. A generic multi-level framework for microscopic traffic simulation with automated vehicles in mixed traffic. Transportation Research Part C: Emerging Technologies, 110, pp.291-311.
Chen, Z. and Park, B.B., 2022. Connected preceding vehicle identification for enabling cooperative automated driving in mixed traffic. Journal of transportation engineering, Part A: Systems, 148(5), p.04022013.
Farah, H., Postigo, I., Reddy, N., Dong, Y., Rydergren, C., Raju, N. and Olstam, J., 2022. Modeling Automated Driving in Microscopic Traffic Simulations for Traffic Performance Evaluations: Aspects to Consider and State of the Practice. IEEE Transactions on Intelligent Transportation Systems.
Jin, S., Sun, D.H., Zhao, M., Li, Y. and Chen, J., 2020. Modeling and stability analysis of mixed traffic with conventional and connected automated vehicles from cyber physical perspective. Physica A: Statistical Mechanics and its Applications, 551, p.124217.
Klimke, M., Völz, B. and Buchholz, M., 2023. Automatic Intersection Management in Mixed Traffic Using Reinforcement Learning and Graph Neural Networks. arXiv preprint arXiv:2301.12717.
Lee, S., Jeong, E., Oh, M. and Oh, C., 2019. Driving aggressiveness management policy to enhance the performance of mixed traffic conditions in automated driving environments. Transportation research part A: policy and practice, 121, pp.136-146.
Mullakkal-Babu, F.A., Wang, M., van Arem, B. and Happee, R., 2020. Comparative safety assessment of automated driving strategies at highway merges in mixed traffic. IEEE transactions on intelligent transportation systems, 23(4), pp.3626-3639.
Schwesinger, U., Versari, P., Broggi, A. and Siegwart, R., 2015. Vision-only fully automated driving in dynamic mixed-traffic scenarios. it-Information Technology, 57(4), pp.231-242.
Stange, V., Kühn, M. and Vollrath, M., 2022. Manual drivers’ experience and driving behavior in repeated interactions with automated Level 3 vehicles in mixed traffic on the highway. Transportation research part F: traffic psychology and behaviour, 87, pp.426-443.
Yao, S. and Friedrich, B., 2019, October. Managing connected and automated vehicles in mixed traffic by human-leading platooning strategy: A simulation study. In 2019 IEEE Intelligent Transportation Systems Conference (ITSC) (pp. 3224-3229). IEEE.
Zhao, X., Liao, X., Wang, Z., Wu, G., Barth, M., Han, K. and Tiwari, P., 2022. Co-simulation platform for modeling and evaluating connected and automated vehicles and human behavior in mixed traffic. SAE International Journal of Connected and Automated Vehicles, 5(12-05-04-0025), pp.313-326.
Ziehn, J.R., Baumann, M.V., Beyerer, J., Buck, H.S., Deml, B., Ehrhardt, S., Frese, C., Kleiser, D., Lauer, M., Roschani, M. and Ruf, M., 2023. Cooperative automated driving for bottleneck scenarios in mixed traffic. In 35th IEEE Intelligent Vehicles Symposium (IV 2023), Anchorage, AK, USA, June 4-7, 2023.


**_Publication regarding social-aware driving in mixed traffic_**
Alahi, A., Goel, K., Ramanathan, V., Robicquet, A., Fei-Fei, L., Savarese, S., 2016. Social LSTM: Human trajectory prediction in crowded spaces, in: Proceedings of the IEEE Computer Society Conference on Computer Vision and Pattern Recognition. https://doi.org/10.1109/CVPR.2016.110
Arksey, H., O’Malley, L., 2005. Scoping studies: Towards a methodological framework. Int. J. Soc. Res. Methodol. Theory Pract. 8, 19–32. https://doi.org/10.1080/1364557032000119616 
Buckman, N., Pierson, A., Schwarting, W., Karaman, S., Rus, D., 2019. Sharing is Caring: Socially-Compliant Autonomous Intersection Negotiation. IEEE Int. Conf. Intell. Robot. Syst. 6136–6143. https://doi.org/10.1109/IROS40897.2019.8967997 
Ferrer, G., Sanfeliu, A., 2014. Proactive kinodynamic planning using the Extended Social Force Model and human motion prediction in urban environments. IEEE Int. Conf. Intell. Robot. Syst. 1730–1735. https://doi.org/10.1109/IROS.2014.6942788 
Garcia, R.S., Araujo, D., 2021. Driving in Roundabouts : Why a Different Theory of Expert Cognition in Social Driving Is Needed for Self-driving Cars.
Gupta, A., Johnson, J., Fei-Fei, L., Savarese, S., Alahi, A., 2018. Social GAN: Socially Acceptable Trajectories with Generative Adversarial Networks. Proc. IEEE Comput. Soc. Conf. Comput. Vis. Pattern Recognit. 2255–2264. https://doi.org/10.1109/CVPR.2018.00240 
Hang, P., Huang, C., Hu, Z., Lv, C., 2022. Decision Making for Connected Automated Vehicles at Urban Intersections Considering Social and Individual Benefits 1–14.
Hang, P., Lv, C., Huang, C., Cai, J., Hu, Z., Xing, Y., 2020. An Integrated Framework of Decision Making and Motion Planning for Autonomous Vehicles Considering Social Behaviors. IEEE Trans. Veh. Technol. 69, 14458–14469. https://doi.org/10.1109/TVT.2020.3040398 
Hang, P., Lv, C., Xing, Y., Huang, C., Hu, Z., 2021. Human-Like Decision Making for Autonomous Driving: A Noncooperative Game Theoretic Approach. IEEE Trans. Intell. Transp. Syst. 22, 2076–2087. https://doi.org/10.1109/TITS.2020.3036984 
Jaques, N., Lazaridou, A., Hughes, E., Gulcehre, C., Ortega, P.A., Strouse, D.J., Leibo, J.Z., de Freitas, N., 2019. Social influence as intrinsic motivation for multi-agent deep reinforcement learning, in: 36th International Conference on Machine Learning, ICML 2019.
Kolekar, S., de Winter, J., Abbink, D., 2020. Human-like driving behaviour emerges from a risk-based driver model. Nat. Commun. 11. https://doi.org/10.1038/s41467-020-18353-4 
Larsson, J., Keskin, M.F., Peng, B., Kulcsár, B., Wymeersch, H., 2021. Pro-social control of connected automated vehicles in mixed-autonomy multi-lane highway traffic. Commun. Transp. Res. 1, 100019. https://doi.org/10.1016/j.commtr.2021.100019
Matcha, B.N., Namasivayam, S.N., Hosseini Fouladi, M., Ng, K.C., Sivanesan, S. and Eh Noum, S.Y., 2020. Simulation strategies for mixed traffic conditions: a review of car-following models and simulation frameworks. Journal of engineering, 2020, pp.1-22.
Munn, Z., Peters, M.D.J., Stern, C., Tufanaru, C., McArthur, A., Aromataris, E., 2018. Systematic review or scoping review? Guidance for authors when choosing between a systematic or scoping review approach. BMC Med. Res. Methodol. https://doi.org/10.1186/s12874-018-0611-x
Oliveira, L., Proctor, K., Burns, C.G., Birrell, S., 2019. Driving style: How should an automated vehicle behave? Inf. 10, 1–20. https://doi.org/10.3390/INFO10060219
Othman, K., 2021. Public acceptance and perception of autonomous vehicles: a comprehensive review, AI and Ethics. Springer International Publishing. https://doi.org/10.1007/s43681-021-00041-8
Schneble, C.O., Shaw, D.M., 2021. Driver’s views on driverless vehicles: Public perspectives on defining and using autonomous cars. Transp. Res. Interdiscip. Perspect. 11, 100446. https://doi.org/10.1016/j.trip.2021.100446
Schwarting, W., Pierson, A., Alonso-Mora, J., Karaman, S., Rus, D., 2019. Social behavior for autonomous vehicles. Proc. Natl. Acad. Sci. U. S. A. 116, 2492–24978. https://doi.org/10.1073/pnas.1820676116
Sun, L., Zhan, W., Chan, C.Y., Tomizuka, M., 2019. Behavior planning of autonomous cars with social perception. IEEE Intell. Veh. Symp. Proc. 2019-June, 207–213. https://doi.org/10.1109/IVS.2019.8814223
Sun, L., Zhan, W., Tomizuka, M., Dragan, A.D., 2018. Courteous Autonomous Cars. IEEE Int. Conf. Intell. Robot. Syst. 663–670. https://doi.org/10.1109/IROS.2018.8593969
Tafidis, P., Farah, H., Brijs, T., Pirdavani, A., 2022. Safety implications of higher levels of automated vehicles: a scoping review. Transp. Rev. 42, 245–267. https://doi.org/10.1080/01441647.2021.1971794
Toghi, B., Valiente, R., Sadigh, D., Pedarsani, R., Fallah, Y.P., 2021a. Altruistic Maneuver Planning for Cooperative Autonomous Vehicles Using Multi-agent Advantage Actor-Critic 1–8.
Toghi, B., Valiente, R., Sadigh, D., Pedarsani, R., Fallah, Y.P., 2021b. Cooperative Autonomous Vehicles that Sympathize with Human Drivers. IEEE Int. Conf. Intell. Robot. Syst. 4517–4524. https://doi.org/10.1109/IROS51168.2021.9636151
Vemula, A., Muelling, K., Oh, J., 2018. Social Attention: Modeling Attention in Human Crowds. Proc. - IEEE Int. Conf. Robot. Autom. 4601–4607. https://doi.org/10.1109/ICRA.2018.8460504
Wang, L., Sun, L., Tomizuka, M., Zhan, W., 2021. Socially-Compatible Behavior Design of Autonomous Vehicles with Verification on Real Human Data. IEEE Robot. Autom. Lett. 6, 3421–3428. https://doi.org/10.1109/LRA.2021.3061350
Yoon, D.D., Ayalew, B., 2019. Social force aggregation control for autonomous driving with connected preview. Proc. Am. Control Conf. 2019-July, 1388–1393. https://doi.org/10.23919/acc.2019.8814725
Zhang, Q., Esterwood, C., Yang, J., Robert, L., 2019. An Automated Vehicle (AV) like Me? The Impact of Personality Similarities and Differences between Humans and AVs. SSRN Electron. J. https://doi.org/10.2139/ssrn.3446005




# Website

**Website** at [https://qiqiqi.gitbook.io/resource-for-emerging-mixed-traffic-of-av-and-hdv/](https://qiqiqi.gitbook.io/resource-for-emerging-mixed-traffic-of-av-and-hdv/) 

# Want to contribute
If you want to contribute to this open repository please contact [Yongqi Dong](https://yongqidong.github.io/) by emailing yongqidong@berkeley.edu.  
