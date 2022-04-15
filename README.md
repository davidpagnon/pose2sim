# Pose2Sim
This Python repository offers a way to perform a markerless kinematic analysis from multiple calibrated views as a unified workflow from an OpenPose input to an OpenSim result. \
Code and instructions at this address: [https://gitlab.inria.fr/perfanalytics/pose2sim](https://gitlab.inria.fr/perfanalytics/pose2sim)

<img src="Content/Overview.png" width="760">

## Contents
1. [Installation and Demonstration](#installation-and-demonstration)
2. [Use on your own data](#use-on-your-own-data)
   1. [Prepare for running on your own data](#prepare-for-running-on-your-own-data)
   2. [2D pose estimation](#2d-pose-estimation)
   3. [Cameras calibration](#cameras-calibration)
   4. [2D Tracking of person](#2d-tracking-of-person)
   5. [3D triangulation](#3d-triangulation)
   6. [3D filtering](#3d-filtering)
   7. [OpenSim kinematics](#opensim-kinematics)
3. [Utilities](#utilities)
4. [How to cite](#how-to-cite)


## How to cite
If you use this code or data, please cite [Pagnon et al., 2022](https://www.mdpi.com/1424-8220/22/7/2712) or [Pagnon et al., 2021](https://www.mdpi.com/1424-8220/21/19/6530).
    
    @Article{Pagnon_2022_Pose2Sim,
      AUTHOR = {Pagnon, David and Domalain, Mathieu and Reveret, Lionel},
      TITLE = {Pose2Sim: An End-to-End Workflow for 3D Markerless Sports Kinematics—Part 2: Accuracy},
      JOURNAL = {Sensors},
      YEAR = {2022},
      PUBLISHER = {Multidisciplinary Digital Publishing Institute},
      URL = {https://www.mdpi.com/1424-8220/22/7/2712}
    }

    @Article{Pagnon_2021_Pose2Sim,
      AUTHOR = {Pagnon, David and Domalain, Mathieu and Reveret, Lionel},
      TITLE = {Pose2Sim: An End-to-End Workflow for 3D Markerless Sports Kinematics—Part 1: Robustness},
      JOURNAL = {Sensors},
      YEAR = {2021},
      PUBLISHER = {Multidisciplinary Digital Publishing Institute},
      URL = {https://www.mdpi.com/1424-8220/21/19/6530},
    }
