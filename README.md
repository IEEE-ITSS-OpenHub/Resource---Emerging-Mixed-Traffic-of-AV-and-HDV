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




# Website

**Website** at [https://qiqiqi.gitbook.io/resource-for-emerging-mixed-traffic-of-av-and-hdv/](https://qiqiqi.gitbook.io/resource-for-emerging-mixed-traffic-of-av-and-hdv/) 

# Want to contribute
If you want to contribute to this open repository please contact [Yongqi Dong](https://yongqidong.github.io/) by emailing yongqidong@berkeley.edu.  
