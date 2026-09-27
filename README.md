<h1 align="center">Hi, I'm Mohamed Abdelkader 👋</h1>
<h3 align="center">Robotics researcher · Autonomous drones · AI + Control</h3>

<p align="center">
  Assistant Professor at <a href="https://www.psu.edu.sa/">Prince Sultan University</a> ·
  Robotics track lead at the <a href="https://www.riotu-lab.org/">RIOTU Lab</a>
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?user=hk5GW30AAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="https://www.linkedin.com/in/mohamed-abdelkader-zahana"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://www.riotu-lab.org/"><img src="https://img.shields.io/badge/RIOTU_Lab-111111?style=for-the-badge&logo=googlechrome&logoColor=white" alt="RIOTU Lab"/></a>
  <a href="https://github.com/mzahana?tab=followers"><img src="https://img.shields.io/github/followers/mzahana?style=for-the-badge&logo=github&label=Followers&color=24292e" alt="GitHub followers"/></a>
</p>

---

## 🚁 About me

I build **autonomous aerial robots** — from the control and estimation math to the software that flies on real hardware.
My work is strategic applied research aligned with **Saudi Vision 2030**: counter-UAS, GNSS-denied navigation,
smart mobility and precision agriculture. My newer research thread is the intersection of **AI and control**.

- 🎓 PhD in Mechanical Engineering, **KAUST** — distributed planning for multi-robot systems
- 🏭 Former Lab Scientist at the **Saudi Aramco R&D Center** — inspection & in-pipe robots; co-inventor on **12 granted US patents**
- 🧑‍🏫 I teach mobile robotics and UAVs, and graduate topics in control theory, model predictive control and vision-based drone control
- 🛠️ Most of what I build is open source here: **PX4 + ROS 2** tooling, estimation, tracking and planning for drones

## 🔬 Research interests

| Autonomy & control | Perception & estimation | Learning |
|---|---|---|
| Model predictive control<br>Controller auto-tuning<br>Multi-robot systems<br>Counter-UAS interception | Drone detection & tracking<br>Sensor fusion & Kalman filtering<br>GNSS-denied navigation (TERCOM, VIO, SLAM) | AI + control<br>Trajectory prediction<br>Vision-language model benchmarking |

## 📄 Research code — papers with open-source implementations

- **SMART-TRACK** — Kalman-filter-guided sensor fusion for robust UAV object tracking. *IEEE Sensors Journal*, 2024.
  [[paper]](https://doi.org/10.1109/JSEN.2024.3505939) [[code]](https://github.com/mzahana/smart_track) [[video]](https://youtu.be/7ZM_gwgNcZg)
- **VECTOR** — velocity-enhanced GRU network for real-time 3D UAV trajectory prediction. *Drones*, 2025.
  [[paper]](https://doi.org/10.3390/drones9010008) [[code]](https://github.com/mzahana/drone_path_predictor_ros) [[dataset]](https://github.com/mzahana/drone_trajectories) [[video]](https://youtu.be/CDp69R_izqo)
- **VLM benchmarking** — vision-language models for automated quality control. *Scientific Reports*, 2026.
  [[paper]](https://doi.org/10.1038/s41598-026-55179-4) [[code]](https://github.com/mzahana/vlm-bench)
- **TERCOM-EKF vs. ViSensorRF** — UAV localization in GNSS-denied environments. *Results in Engineering*, 2026.
  [[paper]](https://doi.org/10.1016/j.rineng.2025.108279) [[code]](https://github.com/mzahana/tercom_nav) [[video]](https://youtu.be/uHy-kTAIA1A)
- **OCTUNE** — optimal control tuning using real-time data. *Sensors*, 2022.
  [[paper]](https://doi.org/10.3390/s22239240) [[code]](https://github.com/mzahana/octune) [[PX4 interface]](https://github.com/mzahana/px4_octune_ros) [[video]](https://youtu.be/a3mrDvK2b-c)
- **D2DTracker** — real-time trajectory prediction for agile drone-to-drone tracking. *IEEE UVS*, 2024.
  [[paper]](https://doi.org/10.1109/UVS59630.2024.10467173) [[detector]](https://github.com/mzahana/d2dtracker_drone_detector) [[prediction]](https://github.com/mzahana/d2dtracker_trajectory_prediction)
- **FLIGHTGEN** — ROS 2-powered automated UAV dataset generator. *SMARTTECH*, Springer LNNS, 2025.
  [[paper]](https://doi.org/10.1007/978-3-031-91235-1_28) [[code]](https://github.com/mzahana/uav_dataset_generation_ros)

➡️ Full list on [Google Scholar](https://scholar.google.com/citations?user=hk5GW30AAAAJ&hl=en).

## 🛠️ Open-source tools for the drone & robotics community

### 🛩️ PX4 autonomy & control
| Repository | Description | |
|---|---|---|
| [**px4_fast_planner**](https://github.com/mzahana/px4_fast_planner) | Fast-Planner integrated with PX4 for fast multi-rotor navigation with obstacle avoidance | ![](https://img.shields.io/github/stars/mzahana/px4_fast_planner?style=flat-square&label=%E2%98%85) |
| [**mavros_apriltag_tracking**](https://github.com/mzahana/mavros_apriltag_tracking) | A PX4 multi-rotor tracking a moving vehicle using AprilTags | ![](https://img.shields.io/github/stars/mzahana/mavros_apriltag_tracking?style=flat-square&label=%E2%98%85) |
| [**px4_pid_tuner**](https://github.com/mzahana/px4_pid_tuner) | System identification and PID tuning of PX4 loops from flight logs | ![](https://img.shields.io/github/stars/mzahana/px4_pid_tuner?style=flat-square&label=%E2%98%85) |
| [**px4-flight-doctor**](https://github.com/mzahana/px4-flight-doctor) | Diagnoses PX4 `.ulg` logs against your drone's real physical specs | ![](https://img.shields.io/github/stars/mzahana/px4-flight-doctor?style=flat-square&label=%E2%98%85) |
| [**mavros_trajectory_tracking**](https://github.com/mzahana/mavros_trajectory_tracking) | Trajectory generation and tracking with a PX4 interface | ![](https://img.shields.io/github/stars/mzahana/mavros_trajectory_tracking?style=flat-square&label=%E2%98%85) |
| [**mav_controllers_ros**](https://github.com/mzahana/mav_controllers_ros) | ROS 2 implementations of micro-aerial-vehicle controllers | ![](https://img.shields.io/github/stars/mzahana/mav_controllers_ros?style=flat-square&label=%E2%98%85) |
| [**trajectory_generation**](https://github.com/mzahana/trajectory_generation) | Trajectory generation, including model predictive control methods | ![](https://img.shields.io/github/stars/mzahana/trajectory_generation?style=flat-square&label=%E2%98%85) |

### 🎯 Detection, tracking & state estimation
| Repository | Description | |
|---|---|---|
| [**multi_target_kf**](https://github.com/mzahana/multi_target_kf) | Kalman filters for multi-target state estimation (ROS) | ![](https://img.shields.io/github/stars/mzahana/multi_target_kf?style=flat-square&label=%E2%98%85) |
| [**roboeye**](https://github.com/mzahana/roboeye) | Visual-inertial odometry on a Raspberry Pi | ![](https://img.shields.io/github/stars/mzahana/roboeye?style=flat-square&label=%E2%98%85) |
| [**VINS-Fusion-ROS2-jazzy**](https://github.com/mzahana/VINS-Fusion-ROS2-jazzy) | VINS-Fusion ported to ROS 2 Jazzy | ![](https://img.shields.io/github/stars/mzahana/VINS-Fusion-ROS2-jazzy?style=flat-square&label=%E2%98%85) |
| [**jetson_vins_fusion_docker**](https://github.com/mzahana/jetson_vins_fusion_docker) | GPU VINS-Fusion in Docker on NVIDIA Jetson | ![](https://img.shields.io/github/stars/mzahana/jetson_vins_fusion_docker?style=flat-square&label=%E2%98%85) |
| [**imu_calib**](https://github.com/mzahana/imu_calib) | ROS 2 package for computing and applying IMU calibration | ![](https://img.shields.io/github/stars/mzahana/imu_calib?style=flat-square&label=%E2%98%85) |

### 📷 Hardware drivers
| Repository | Description | |
|---|---|---|
| [**siyi_sdk**](https://github.com/mzahana/siyi_sdk) | Python SDK for SIYI gimbal-camera systems | ![](https://img.shields.io/github/stars/mzahana/siyi_sdk?style=flat-square&label=%E2%98%85) |
| [**siyi_ros2**](https://github.com/mzahana/siyi_ros2) | ROS 2 Jazzy driver for SIYI gimbals (ZT30, ZT6, ZR30, ZR10, A8 Mini, A2 Mini) | ![](https://img.shields.io/github/stars/mzahana/siyi_ros2?style=flat-square&label=%E2%98%85) |
| [**rtsp_camera**](https://github.com/mzahana/rtsp_camera) | Low-latency RTSP camera streams into ROS 2 via GStreamer | ![](https://img.shields.io/github/stars/mzahana/rtsp_camera?style=flat-square&label=%E2%98%85) |
| [**raspberrypi_ai_camera_ros2**](https://github.com/mzahana/raspberrypi_ai_camera_ros2) | ROS 2 package for the Raspberry Pi AI Camera (IMX500) | ![](https://img.shields.io/github/stars/mzahana/raspberrypi_ai_camera_ros2?style=flat-square&label=%E2%98%85) |
| [**ZLAC8030L_CAN_controller**](https://github.com/mzahana/ZLAC8030L_CAN_controller) | CANopen control of the ZLAC8030L motor driver | ![](https://img.shields.io/github/stars/mzahana/ZLAC8030L_CAN_controller?style=flat-square&label=%E2%98%85) |

### 🐳 Dev environments & simulation
| Repository | Description | |
|---|---|---|
| [**px4_ros2_humble**](https://github.com/mzahana/px4_ros2_humble) | Docker development environment for PX4 + ROS 2 Humble | ![](https://img.shields.io/github/stars/mzahana/px4_ros2_humble?style=flat-square&label=%E2%98%85) |
| [**conveyor_sim_ros2**](https://github.com/mzahana/conveyor_sim_ros2) | Conveyor-belt simulation in Gazebo Harmonic with a ROS 2 interface | ![](https://img.shields.io/github/stars/mzahana/conveyor_sim_ros2?style=flat-square&label=%E2%98%85) |
| [**containers**](https://github.com/mzahana/containers) | Reusable Docker containers for robotics development | ![](https://img.shields.io/github/stars/mzahana/containers?style=flat-square&label=%E2%98%85) |

### 🧪 Lab tools
| Repository | Description | |
|---|---|---|
| [**cortex**](https://github.com/mzahana/cortex) | Self-hosted lab asset & inventory management — QR-scan checkout, reservations, low-stock alerts | ![](https://img.shields.io/github/stars/mzahana/cortex?style=flat-square&label=%E2%98%85) |

<p align="right"><a href="https://github.com/mzahana?tab=repositories&type=source&sort=stargazers">All repositories →</a></p>

## 🧰 Tech stack

**Robotics** &nbsp;
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![PX4](https://img.shields.io/badge/PX4-1F2C5C?style=flat-square&logo=dronecode&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=flat-square&logoColor=white)
![MAVLink](https://img.shields.io/badge/MAVLink-2B6CB0?style=flat-square&logoColor=white)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

**Languages** &nbsp;
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-E16737?style=flat-square&logo=mathworks&logoColor=white)

**AI & perception** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Tools** &nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks-D52B1E?style=flat-square&logo=dassaultsystemes&logoColor=white)

## 🎥 See it fly

| | |
|---|---|
| [![SMART-TRACK: sensor-fusion target tracking](https://img.youtube.com/vi/7ZM_gwgNcZg/mqdefault.jpg)](https://youtu.be/7ZM_gwgNcZg) | [![VECTOR: GRU trajectory prediction](https://img.youtube.com/vi/CDp69R_izqo/mqdefault.jpg)](https://youtu.be/CDp69R_izqo) |
| SMART-TRACK: sensor-fusion target tracking | VECTOR: GRU trajectory prediction |
| [![TERCOM: GNSS-denied navigation](https://img.youtube.com/vi/uHy-kTAIA1A/mqdefault.jpg)](https://youtu.be/uHy-kTAIA1A) | [![OCTUNE: real-time controller tuning](https://img.youtube.com/vi/a3mrDvK2b-c/mqdefault.jpg)](https://youtu.be/a3mrDvK2b-c) |
| TERCOM: GNSS-denied navigation | OCTUNE: real-time controller tuning |
| [![Obstacle-free navigation with PX4 + Fast-Planner](https://img.youtube.com/vi/KXXjLYjIxD0/mqdefault.jpg)](https://youtu.be/KXXjLYjIxD0) | [![Vision-based tracking of a moving vehicle](https://img.youtube.com/vi/5bqOWKYBr0k/mqdefault.jpg)](https://youtu.be/5bqOWKYBr0k) |
| Obstacle-free navigation with PX4 + Fast-Planner | Vision-based tracking of a moving vehicle |
| [![PSU on-campus drone delivery](https://img.youtube.com/vi/42VqK-V7Uhg/mqdefault.jpg)](https://youtu.be/42VqK-V7Uhg) | [![Multi-drone search and pick](https://img.youtube.com/vi/oDX5QexRK_I/mqdefault.jpg)](https://youtu.be/oDX5QexRK_I) |
| PSU on-campus drone delivery | Multi-drone search and pick |

## 📊 GitHub activity

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mzahana&theme=github" alt="Contribution summary"/>
</p>
<p align="center">
  <img width="41%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=mzahana&theme=github" alt="Repositories per language"/>
  <img width="41%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=mzahana&theme=github" alt="Most-committed languages"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=mzahana&hide_border=true&theme=transparent" alt="Contribution streak"/>
</p>

---

<p align="center"><i>Students interested in drones, control or robot learning at PSU — reach out through the <a href="https://www.riotu-lab.org/">RIOTU Lab</a>.</i></p>
