<h1 align="center">Rivindu Vinsara Kumarage</h1>

<p align="center"><b>Robotics · Computer Vision · ML/AI · Embedded & IoT · Linux</b></p>

<p align="center">
  <img src="https://github.com/rivindu02/rivindu02/blob/main/github_intro.gif" width="520" alt="Banner" />
</p>

<p align="center">
  <img src="https://api.visitorbadge.io/api/visitors?path=rivindu02%2Frivindu02&label=Explorers&countColor=%238a2be2&style=for-the-badge" />
  <a href="https://mail.google.com/mail/?view=cm&fs=1&to=kumaragerivindu@gmail.com">
    <img src="https://img.shields.io/badge/Connect-D14836?style=for-the-badge&logo=gmail&logoColor=white&label=Email" />
  </a>
  <a href="https://instagram.com/rivindu_k">
    <img src="https://img.shields.io/badge/Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white&label=Instagram" />
  </a>
  <a href="https://github.com/rivindu02/rivindu02/raw/main/Rivindu_Kumarage_CV.pdf">
    <img src="https://img.shields.io/badge/My%20Resume-5BCDEC?style=for-the-badge&logo=adobeacrobatreader&logoColor=white&color=green" alt="View Resume (PDF)" />
  </a>
</p>

---

## About Me

I'm an **Electronic & Telecommunication Engineering undergraduate at the University of Moratuwa**, focused on **robotics, computer vision, machine learning, and embedded/IoT systems**.

---

## Robotics & Simulation

| Project | Work and technologies |
| --- | --- |
| [Micromouse Robot](https://github.com/rivindu02/Micromouse-Robot) | STM32F411 robot for 16×16 mazes: flood-fill exploration, shortest-path navigation, embedded C, custom Altium PCB, and mechanical CAD. |
| [Unitree Go2 in Isaac Sim](https://github.com/rivindu02/isaac-go2-ros2) | Isaac Sim and ROS 2 work for my final-year project, including camera/depth sensing, waypoint navigation, and synthetic dataset recording. Based on [Zhefan Xu's isaac-go2-ros2](https://github.com/Zhefan-Xu/isaac-go2-ros2). |
| [Unitree Go2 in MuJoCo](https://github.com/rivindu02/unitree_mujoco) | Extended [Unitree's MuJoCo simulator](https://github.com/unitreerobotics/unitree_mujoco) with a verified C++ ROS 2 sensor bridge: 4,000-point 10 Hz LiDAR, IMU and simulation clock, Go2 teleoperation, KISS-ICP 3D mapping, and RViz visualisation. |
| [Go1/Go2 Gazebo Sim LiDAR & SLAM](https://github.com/rivindu02/go2_ros2_sim_py) | Added a 16-channel GPU LiDAR, ROS 2 point-cloud bridge, and KISS-ICP/RTAB-Map launch setups to the Gazebo Sim project. |
| 2D EKF-SLAM Mini Project | Explicit Python landmark EKF, 120 paired trials across six scenarios, and a Gazebo Classic 11 + ROS 2 Humble physics demo. Baseline mean trajectory RMSE was 0.238 ± 0.146 m versus 3.233 ± 1.172 m for odometry alone. |
| [ZED Mapping & Relocalisation](https://github.com/rivindu02/zed_mapping_check) | Experimental ZED 2i pipeline combining DROID-SLAM poses, voxel mapping, ACE relocalisation, and Open3D. End-to-end validation is pending. |
| [SLRC 2025 Finals](https://github.com/rivindu02/SLRC-2025-final-round) | Team PixieBots' top-five finalist robot with autonomous navigation and a 4-DoF arm; C++, PlatformIO, servos, and colour sensors. |

More robotics work: [autonomous robot design and competition](https://github.com/rivindu02/EN2533-Robotic-Design-and-Competition-) and [MATLAB robotics labs](https://github.com/rivindu02/EN3563-Robotics-Module) covering coordinate frames, forward/inverse kinematics, and trajectory generation.

---

## Vision, Machine Learning & AI

| Project | Work and technologies |
| --- | --- |
| [CNN Experiments on CIFAR-10](https://github.com/rivindu02/EN4554-Assignment-2-on-CNNs) | PyTorch coursework covering manual backpropagation, optimizers, regularization, residual networks, and a compact CNN. |
| [Boxsmith](https://github.com/rivindu02/boxsmith) | A tiny CNN trained from scratch on synthetic shapes, with an interactive object-detection lab for bounding boxes, NMS, IoU, precision–recall, and mAP. |
| [Noise to Vogue](https://github.com/rivindu02/noise-to-vogue) | DDPMs trained on Fashion-MNIST, with linear/cosine noise-schedule comparisons, denoising animations, and an interactive prediction viewer. |
| [Image Processing & Computer Vision](https://github.com/rivindu02/EN3160-Image-Processing-and-Computer-Vision) | OpenCV, NumPy, and scikit-image coursework: filtering, RANSAC, homography, SIFT stitching, and segmentation. |
| [StyleNStay: Composed Image Retrieval](https://github.com/rivindu02/Zero-shot-CIR-EN3160-project) | Team project using TransAgg and a BLIP backbone to retrieve fashion images from a reference image and a text modification. |
| [Jute Pest Classification](https://github.com/rivindu02/Jute-Pest-CNN-A3) | Team coursework comparing a custom CNN with transfer learning using VGG19, InceptionV3, and DenseNet201. |

Foundations: [Pattern Recognition](https://github.com/rivindu02/EN3150-Pattern-Recognition)—regression, classification, robust losses, and model evaluation.

In development: [Shortcut Sleuth](https://github.com/rivindu02/shortcut-sleuth), a planned CNN vs. ViT experiment on background shortcuts. The protocol is published; implementation and training are pending.

---

## Embedded Systems & IoT

| Project | Work and technologies |
| --- | --- |
| [Echo-Guard](https://github.com/rivindu02/Echo-Guard) | Noise monitoring with ESP32 sensors, MQTT, a Raspberry Pi server, WebSockets, and a React interface. |
| [Medibox](https://github.com/rivindu02/EN2853-Medibox) | ESP32 medicine reminders and environmental monitoring, with MQTT, Node-RED, and Wokwi simulation. |
| [AmpAware](https://github.com/rivindu02/AmpAware) | Team smart-plug project. My contribution: PCB design, hardware testing, and system integration. |
| [UART Between FPGAs](https://github.com/rivindu02/EN2111-UART-Based-Data-Transmission-Between-FPGAs) | Verilog UART transmitter/receiver design, baud-rate generation, and FPGA display integration. |

Other hardware work includes a [Raspberry Pi security camera](https://github.com/rivindu02/Smart-Security-camera), a team [strain-gauge torque sensor](https://github.com/rivindu02/Torque-Sensor), and a [torque-readings dashboard](https://github.com/rivindu02/Torque-sensor-Dashboard).

---

## Software, Cloud & DevOps

| Project | Work and technologies |
| --- | --- |
| [School Management API](https://github.com/rivindu02/School-Management-API) | TypeScript/Express CRUD APIs for students, teachers, and courses; MongoDB, JWT authentication, role-based access, Zod validation, and OpenAPI documentation. |
| [AWS Infrastructure with Terraform & Ansible](https://github.com/rivindu02/private-server-tf) | Modular infrastructure for a containerised application: VPC networking, EC2, an Application Load Balancer, and Ansible provisioning. |
| [AWS ECS Infrastructure](https://github.com/rivindu02/TF-ECS) | Terraform modules for container deployment, networking, load balancing, and ECS capacity configuration. |
| [Serverless API on AWS Lambda](https://github.com/rivindu02/Serverless-AWS-Lambda-SAM-) | A containerised Express API using AWS SAM, Lambda Web Adapter, API Gateway, ECR, and Terraform. |
| Java / Vert.x service project (internship) | Built single-process and Hazelcast-clustered service prototypes with Vert.x event-bus service proxies; verified cross-process messaging and compared latency/throughput. |
| Auth0-to-Keycloak migration work (internship) | Added Keycloak OIDC login support to an Auth0-backed frontend and validated the local redirect and token flow. The Kubernetes deployment stage was still pending. |

I also work with Docker Compose, automated tests, and GitHub Actions, and explore software design through projects such as [Document Life Cycle](https://github.com/rivindu02/Document-Life-cycle).

---

## Technical Arsenal

<table align="center" width="100%" border="0" cellspacing="0" cellpadding="8">
  <tr>
    <td align="center" valign="top" width="33%">
      <b>Robotics &amp; Simulation</b><br><br>
      <img src="https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&amp;logo=ros&amp;logoColor=white" alt="ROS 2" />
      <img src="https://img.shields.io/badge/Isaac%20Sim-76B900?style=for-the-badge&amp;logo=nvidia&amp;logoColor=white" alt="Isaac Sim" />
      <img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&amp;logo=mathworks&amp;logoColor=white" alt="MATLAB" />
      <img src="https://img.shields.io/badge/Robotics%20Toolbox-0B7285?style=for-the-badge" alt="Robotics Toolbox" />
      <img src="https://img.shields.io/badge/Gazebo%20Classic-F58113?style=for-the-badge" alt="Gazebo Classic" />
      <img src="https://img.shields.io/badge/MuJoCo-0075C9?style=for-the-badge" alt="MuJoCo" />
    </td>
    <td align="center" valign="top" width="33%">
      <b>Computer Vision &amp; ML</b><br><br>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch" />
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&amp;logo=tensorflow&amp;logoColor=white" alt="TensorFlow" />
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&amp;logo=opencv&amp;logoColor=white" alt="OpenCV" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&amp;logo=numpy&amp;logoColor=white" alt="NumPy" />
      <img src="https://img.shields.io/badge/scikit-learn-F7931E?style=for-the-badge" alt="scikit-learn" />
    </td>
    <td align="center" valign="top" width="33%">
      <b>3D Vision &amp; Mapping</b><br><br>
      <img src="https://img.shields.io/badge/ZED%20SDK-0066FF?style=for-the-badge" alt="ZED SDK" />
      <img src="https://img.shields.io/badge/Open3D-59666C?style=for-the-badge" alt="Open3D" />
      <img src="https://img.shields.io/badge/DROID-SLAM-2453A6?style=for-the-badge" alt="DROID-SLAM" />
      <img src="https://img.shields.io/badge/ACE-7655C2?style=for-the-badge" alt="ACE" />
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="33%">
      <b>Embedded Systems &amp; IoT</b><br><br>
      <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&amp;logo=stmicroelectronics&amp;logoColor=white" alt="STM32" />
      <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&amp;logo=espressif&amp;logoColor=white" alt="ESP32" />
      <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&amp;logo=arduino&amp;logoColor=white" alt="Arduino" />
      <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&amp;logo=raspberrypi&amp;logoColor=white" alt="Raspberry Pi" />
      <img src="https://img.shields.io/badge/PlatformIO-F5822A?style=for-the-badge&amp;logo=platformio&amp;logoColor=white" alt="PlatformIO" />
      <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&amp;logo=mqtt&amp;logoColor=white" alt="MQTT" />
      <img src="https://img.shields.io/badge/Node-RED-8F0000?style=for-the-badge&amp;logo=nodered&amp;logoColor=white" alt="Node-RED" />
    </td>
    <td align="center" valign="top" width="33%">
      <b>Linux &amp; Systems</b><br><br>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&amp;logo=linux&amp;logoColor=white" alt="Linux" />
      <img src="https://img.shields.io/badge/Hyprland-58E1FF?style=for-the-badge" alt="Hyprland" />
      <img src="https://img.shields.io/badge/Zsh-F15A24?style=for-the-badge&amp;logo=gnubash&amp;logoColor=white" alt="Zsh" />
      <img src="https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&amp;logo=neovim&amp;logoColor=white" alt="Neovim" />
      <img src="https://img.shields.io/badge/systemd-202020?style=for-the-badge" alt="systemd" />
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Git" />
    </td>
    <td align="center" valign="top" width="33%">
      <b>Software &amp; APIs</b><br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&amp;logo=c&amp;logoColor=white" alt="C" />
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&amp;logo=cplusplus&amp;logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&amp;logo=nodedotjs&amp;logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&amp;logo=react&amp;logoColor=white" alt="React" />
      <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&amp;logo=express&amp;logoColor=white" alt="Express" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&amp;logo=mongodb&amp;logoColor=white" alt="MongoDB" />
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge" alt="Java" />
      <img src="https://img.shields.io/badge/Vert.x-782A90?style=for-the-badge" alt="Vert.x" />
      <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge" alt="Keycloak" />
      <img src="https://img.shields.io/badge/Hazelcast-FFDB00?style=for-the-badge" alt="Hazelcast" />
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="33%">
      <b>Cloud &amp; DevOps</b><br><br>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&amp;logo=amazonaws&amp;logoColor=white" alt="AWS" />
      <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&amp;logo=terraform&amp;logoColor=white" alt="Terraform" />
      <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&amp;logo=ansible&amp;logoColor=white" alt="Ansible" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&amp;logo=docker&amp;logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions" />
      <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&amp;logo=pytest&amp;logoColor=white" alt="pytest" />
    </td>
    <td align="center" valign="top" width="33%">
      <b>Electronics, FPGA &amp; CAD</b><br><br>
      <img src="https://img.shields.io/badge/Altium%20Designer-A5915F?style=for-the-badge&amp;logo=altiumdesigner&amp;logoColor=white" alt="Altium Designer" />
      <img src="https://img.shields.io/badge/SolidWorks-FF0000?style=for-the-badge&amp;logo=dassaultsystemes&amp;logoColor=white" alt="SolidWorks" />
      <img src="https://img.shields.io/badge/Verilog-B2B2B2?style=for-the-badge" alt="Verilog" />
      <img src="https://img.shields.io/badge/Quartus%20Prime-0071C5?style=for-the-badge&amp;logo=intel&amp;logoColor=white" alt="Quartus Prime" />
      <img src="https://img.shields.io/badge/QuestaSim-00A0E1?style=for-the-badge" alt="QuestaSim" />
      <img src="https://img.shields.io/badge/PCB%20Design-0D1117?style=for-the-badge" alt="PCB Design" />
    </td>
    <td width="33%"></td>
  </tr>
</table>

**Linux** is part of my day-to-day work: I configure systems, write shell automation, and maintain services and developer tools (using Arch Linux, a Linux distribution). My [dotfiles](https://github.com/rivindu02/dotfiles) bring together Hyprland, Waybar, Neovim, Zsh, and GNU Stow.

- Desktop and terminal customisation, shell scripting, and CLI utilities.
- systemd services/timers, udev rules, package hooks, and system configuration.
- Backup automation with restic and rclone, plus firewall configuration and secret-handling safeguards.

---

## Academics

- **Completed:** Electronic Circuits & Analysis · Signals & Systems · Computer Organization & Design · Robotics Design & Competition · Electronic Control Systems · Communication Systems Engineering · Electronic Design Realization · Electromagnetics · Pattern Recognition · Image Processing & Machine Vision · Internet of Things · Robotics


---


## GitHub Analytics

<table border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td width="50%" valign="top" align="center">
      <img src="https://github-readme-stats-gules-two-98.vercel.app/api?username=rivindu02&show=reviews,prs_merged,prs_merged_percentage&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=5BCDEC&icon_color=FF6B6B&text_color=C9D1D9&border_color=30363D&border_radius=10&hide_border=false&cache_seconds=0" alt="GitHub Stats"/>
      <br/>
      <img src="https://github-readme-streak-stats-salesp07.vercel.app/?user=rivindu02&theme=tokyonight&hide_border=true&background=0D1117&ring=5BCDEC&fire=5BCDEC&currStreakLabel=5BCDEC" alt="GitHub Streak" width="100%" />
    </td>
    <td width="50%" valign="top" align="center">
      <img src="https://github-readme-stats-gules-two-98.vercel.app/api/top-langs/?username=rivindu02&layout=pie&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=5BCDEC&text_color=FFFFFF" alt="Language usage (pie)" width="75%" />
    </td>
  </tr>
</table>




---

