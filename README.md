<div align="center">

<img src="https://raw.githubusercontent.com/dongridong/dongridong/main/assets/banner.png" alt="dongridong with robotics" width="100%" />

**Robotics Software Engineer** &nbsp;·&nbsp; Rainbow Robotics

Real-time control for mobile dual-arm robots, and the teleoperation tools that teach them.

<a href="mailto:ndh970914@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/RB--Y1-1a1a1a?style=flat-square" alt="RB-Y1" />
<img src="https://img.shields.io/badge/Physical%20AI-5a8a5e?style=flat-square" alt="Physical AI" />

</div>

<br>

```
human motion  ──>  retargeting  ──>  whole-body control  ──>  RB-Y1
                                                                │
   VLA policy  <──  demonstration data  <───────────────────────┘
```

I own two pieces of that loop.

**RB-Y1 Core** — the real-time control stack running on the robot. Whole-body impedance and optimal control, friction compensation, IMU-driven active damping, functional safety.

**Teleoperation for VLA** — the capture side. XR interfaces on Meta Quest and Galaxy XR, hand and HMD retargeting, demonstration pipelines that feed vision-language-action models.

Fifth year building this. C++ where it has to meet a deadline, Python where it has to move fast.

<br>

<div align="center">

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)

![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-4B6BFB?style=flat-square)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![CAN](https://img.shields.io/badge/CAN-B45309?style=flat-square)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LeRobot](https://img.shields.io/badge/LeRobot-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

<br>

## Projects

<!-- Add a project by copying the row template at the bottom of this section. -->

| | |
| :--- | :--- |
| [**Galaxy for Teleoperation**](https://github.com/dongridong/Galaxy_for_teleoperation) | Android XR app streaming passthrough, hand tracking and controller input to RB-Y1 as NDJSON pose frames |
| [**Meta for Teleoperation**](https://github.com/dongridong/Meta_for_teleoperation) | Meta Quest counterpart on the same pose schema, so either headset drives the same receiver |
| [**Teleoperation with RB-Y1**](https://github.com/dongridong/Teleopeartion_with_RBY1) | Receiver and control side of the XR teleoperation loop |
| [**T5-M-Mb**](https://github.com/dongridong/T5-M-Mb) | MJCF and URDF models for the T5 and M / Mb platforms |

<!-- ROW TEMPLATE, copy above this line
| [**Name**](https://github.com/dongridong/REPO) | One line on what it does |
-->

<br>

## Open Source

[![MuJoCo Menagerie](https://img.shields.io/badge/MuJoCo%20Menagerie-Google%20DeepMind-4B6BFB?style=flat-square)](https://github.com/google-deepmind/mujoco_menagerie/tree/main/rainbow_robotics_rby1)

Author of the **RB-Y1** model in Google DeepMind's reference collection of high-quality robot models — A and M variants, v1.2 and v1.3, with and without grippers.
&nbsp;<sub>[#134](https://github.com/google-deepmind/mujoco_menagerie/pull/134) &nbsp;·&nbsp; [#238](https://github.com/google-deepmind/mujoco_menagerie/pull/238)</sub>

<br>

<div align="center">

<a href="mailto:ndh970914@gmail.com"><img src="https://img.shields.io/badge/ndh970914@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

<!--
═══════════════════════════════════════════════════════════════════════
  HIDDEN SECTIONS. Nothing below renders on the profile.

  When you have something to show, cut that block out of this comment
  and paste it above the Projects section. Keep the rest in here.
═══════════════════════════════════════════════════════════════════════


## Publications

| | |
| :--- | :--- |
| **2026** | **Paper Title** · Authors, with **your name** in bold <br> *Venue* &nbsp;·&nbsp; [Paper](URL) &nbsp;·&nbsp; [Code](URL) |

ROW TEMPLATE
| **YEAR** | **Title** · Authors <br> *Venue* &nbsp;·&nbsp; [Paper](URL) |


## Patents

| | | |
| :--- | :--- | :--- |
| **2026** | Patent title | 10-2026-0000000 · Filed |

ROW TEMPLATE
| **YEAR** | Title | Number · Filed / Registered |


## Awards

| | |
| :--- | :--- |
| **2026** | Award name · Issuing organization |

ROW TEMPLATE
| **YEAR** | Award name · Issuing organization |

═══════════════════════════════════════════════════════════════════════
-->
