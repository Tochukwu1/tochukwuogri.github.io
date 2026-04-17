---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## [Information Driven Guidance for Target Tracking with a Learned Motion Model](/projects/info_driven_guidance_project/)

<img src="/images/mml_lcss.gif" width="455" /> 
<img src="/images/FigFramework_annotated.png" width="450" /> 

Project consisted of designing here should a drone go to gain to better track another unknown ground robot by collecting noisy and intermittent measurements. The planning algorithm improves the target tracking performance by choosing the location with the most informative measurement predicted by a transformer-based neural network. To read more about the project, click [here](/projects/info_driven_guidance_project/).


## [Bathy-drone: Autonomous Drone and Boat-Tethered Robot](/projects/bathydrone_project/)
<img src="/images/bathydrone_footage.gif" width="500" /> 
<img src="/images/bathydrone_annotated.png" width="425" /> 

The Bathy-Drone robot is an autonomous drone towing a tethered boat equipped with sonar. It can be flown to the survey location to perform applications such as bathymetry, underwater structure inspection, marine life surveying. I was in charge of anything software related including autonomy. I developed or supervised the simulation, perception, planning, localization and controls algorithms. To read more about the project, click [here](/projects/bathydrone_project/).

## Robust Multi-Camera Multi-object Tracking and Attack Detection System
<img src="/images/RAITE_homography.gif" width="600" /> 

Developed a ML model to track aerial and ground robots moving around in a cluttered environment and be robust against attacks. The attacks were physical disturbances such as glare, netting and optical filters in the camera, smoke, clutter from other moving objects, images, etc. I was part of the team that trained the vision model and designed/implemented a multi-camera estimator to keep track of the robots even under occlusions from one camera. The estimator was implemented as a Kalman Filter with a Global Nearest Neighbor to associate the measurements from different cameras.  
The project's goal is to developed a system that can accurately detect when an attack has occurred on the system, determine which sensor has been attacked, generate timely alerts to notify human operators of the detected attack and compromised sensor, and leverage data from uncompromised systems to recover from the attack. [Auto Label Code](https://github.com/andrespulido8/sam2_yolo_autolabel) [[Conference Paper]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13480/3053971/Lessons-from-RAITE--real-world-evaluation-of-robust-multimodal/10.1117/12.3053971.short)


## Scientific Diving for Human-Robot Collaboration to Perform Underwater Gesture Recognition
<img src="/images/diver_recognition.png" width="350" /> 
<img src="/images/cave_cut.gif" width="455" /> 


These two complementary projects establish a comprehensive framework for underwater diver gesture recognition to advance human-robot collaboration in marine environments. The first project developed the Scuba Gesture Dataset (SGD11), a pioneering publicly available dataset containing annotated video sequences of 11 standard diver hand gestures captured in controlled underwater conditions, complete with benchmark evaluations of three gesture recognition models to serve as a foundation for autonomous underwater systems research. The second project built upon this foundation by creating a novel Spatio-Temporal Transformer-based algorithm that overcomes the limitations of traditional frame-wise detection methods by integrating temporal modeling to capture sequential motion patterns, significantly improving recognition accuracy and robustness against challenging underwater conditions including lighting fluctuations, visibility degradation, and partial occlusions. Together, these projects provide both the essential data infrastructure and advanced algorithmic capabilities needed for reliable underwater human-robot interaction, establishing a practical foundation for intelligent diver assistance systems and autonomous underwater vehicle collaboration in real-world marine operations: [[Dataset Paper]](https://xiaominlin.github.io/files/ICRA2025_AQ2UASIM_Workshop_Diver_Dataset.pdf), [[Dataset Repo]](https://github.com/theaprilab/SDG11), [[Algorithm Paper]](https://ieeexplore.ieee.org/document/11247289)


## System ID, dynamic modeling, control, and state estimation of a underwater vehicle (SubjuGator) and an autonomous surface vehicle (NaviGator) for competitions  
<img src="/images/subjugator.png" width="335" /> 
<img src="/images/NaviGator.png" width="450" /> 

As part of the Machine Intelligence Lab (MIL) at the University of Florida, since 2018, I served as the lead mechanical engineer, a software team member and I am now adivising the team. A small sample of the projects I have led are: [[Website]](http://subjugator.org/), [[Code]](https://github.com/uf-mil/mil/)
- To take into account external disturbances, I implemented a Concurrent Learning-based adaptive controller for the surface vehicle boat that learns systems parameters.  
- The model of a submarine contains unknown parameters that needed to be found in either simulations or experimentation with the physical vehicle. Therefore, I performed a system ID method by fitting data collected in the pool to a dynamic model and find the drag and inertia parameters of the submarine.
- Documented an optimization-based thruster mapping ROS node for stable control of the autonomous submarine
- Provided guidance and supervised the individual projects from the team members such as a water cooling computer system that used closed loop water to carry the heat from the computers vessel and dissipate it externally as well as the manufacturing of the sub's pressure vessels
- Performed stress analysis in four nodes that connect the carbon fiber chassis of the Submarine to prevent failure


## Optimal Control Theory for Trajectory Generation of an Orbital Spacecraft  
<img src="/images/polar_traj.png" width="450" /> 

I have taken several courses that have allowed me to work on interesting projects. Some of are Nonlinear Programming, Optimal Control, and Reinfocement Learning, Adaptive Control, Neural Networks and Machine Learning, and more. This project is an example of a course project: 
Optimal control theory was used to solve a trajectory generation of an orbital spacecraft and a minimum time transfer of a ground mobile between a given initial and terminal state problems. Indirect and direct with single and multiple shooting methods were implemented from scratch in Python. 
[[Code]](https://github.com/andrespulido8/optimal_control_examples)
