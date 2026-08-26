<div align="center">

# Awesome Humanoid Learning

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/jonyzhang2023/awesome-humanoid-learning?style=social)](https://github.com/jonyzhang2023/awesome-humanoid-learning)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-March%202026-blue)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/jonyzhang2023/awesome-humanoid-learning/pulls)

**A curated collection of resources on humanoid robot learning — locomotion, manipulation, whole-body control, and beyond.**

Given the similarities between the locomotion of humanoid robots and bipedal robots, we have included some works on bipedal locomotion for reference. In recent research, I have noticed an increasing convergence between humanoid robotics and physics-based animation. I believe this is a highly promising direction for the development of humanoid robots. Therefore, I will be updating this repository with animation works that I find beneficial for humanoid robotics.

[Papers](#-papers) &bull; [News](#-news) &bull; [Robot Models](#-robot-models) &bull; [Related Lists](#-related-awesome-lists)

</div>

---

## Contents

- [Robot Models](#-robot-models)
  - [Bipeds](#bipeds)
  - [Humanoids](#humanoids)
- [News](#-news)
- [Papers](#-papers)
  - [2026](#2026) | [2025](#2025) | [2024](#2024) | [2023](#2023) | [2022](#2022) | [2021](#2021) | [2020](#2020) | [2019](#2019) | [2018](#2018)
- [Related Awesome-Lists](#-related-awesome-lists)
- [Star History](#-star-history)
- [Contributing](#-contributing)

---

## 🤖 Robot Models

### Bipeds

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|:-----|:------|:--------|:--------|:------:|:--------:|:----------:|
| Bolt | ODRI | [URDF](https://github.com/Gepetto/example-robot-data/tree/master/robots/bolt_description) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| Cassie (MJCF) | Agility Robotics | [MJCF](https://github.com/deepmind/mujoco_menagerie/tree/main/agility_cassie) | MIT | ✔️ | ✔️ | ✔️ |
| Cassie (URDF) | Agility Robotics | [URDF](https://github.com/robot-descriptions/cassie_description) | MIT | ✔️ | ✔️ | ✔️ |
| Spryped | Benjamin Bokser | [URDF](https://github.com/bbokser/spryped/tree/master/spryped_urdf_rev06) | GPL-3.0 | ✔️ | ✔️ | ✔️ |
| Upkie | Tast's Robots | [URDF](https://github.com/tasts-robots/upkie_description) | Apache-2.0 | ✔️ | ✔️ | ✔️ |
| Hector | [USC DRCL](https://sites.usc.edu/quann/robots/) | [URDF](https://github.com/DRCL-USC/Hector_Simulation) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| SA01 | [EngineAI](https://www.engineai.com.cn/) | [URDF & MJCF](https://github.com/engineai-robotics/engineai_legged_gym) | — | ✔️ | ✔️ | ✔️ |

### Humanoids

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|:-----|:------|:--------|:--------|:------:|:--------:|:----------:|
| Atlas DRC (v3) | Boston Dynamics | [URDF](https://github.com/RobotLocomotion/drake/tree/master/examples/atlas) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| Atlas v4 | Boston Dynamics | [URDF](https://github.com/openai/roboschool/tree/1.0.49/roboschool/models_robot/atlas_description) | MIT | ✔️ | ✔️ | ✔️ |
| Digit | Agility Robotics | [URDF](https://github.com/adubredu/DigitRobot.jl) | ✖️ | ✔️ | ✔️ | ✔️ |
| iCub | IIT | [URDF](https://github.com/robotology/icub-models/tree/master/iCub) | CC-BY-SA-4.0 | ✔️ | ✔️ | ✔️ |
| JAXON | JSK | [COLLADA](https://github.com/stephane-caron/openrave_models/tree/master/JAXON), [URDF](https://github.com/robot-descriptions/jaxon_description), [VRML](https://github.com/start-jsk/rtmros_choreonoid/tree/master/jvrc_models/JAXON_JVRC) | CC-BY-SA-4.0 | ✔️ | ✔️ | ✔️ |
| JVRC-1 | AIST | [MJCF](https://github.com/isri-aist/jvrc_mj_description/), [URDF](https://github.com/stephane-caron/jvrc_description) | BSD-2-Clause | ✔️ | ✔️ | ✔️ |
| NAO | SoftBank Robotics | [URDF](https://github.com/ros-naoqi/nao_robot/tree/master/nao_description/urdf/naoV50_generated_urdf), [Xacro](https://github.com/ros-naoqi/nao_robot/tree/master/nao_description/) | BSD-3-Clause | [—](https://github.com/ros-naoqi/nao_meshes#readme) | ✔️ | ✔️ |
| Robonaut 2 | NASA JSC Robotics | [URDF](https://github.com/gkjohnson/nasa-urdf-robots/tree/master/r2_description) | NASA-1.3 | ✔️ | ✔️ | ✔️ |
| Romeo | Aldebaran Robotics | [URDF](https://github.com/ros-aldebaran/romeo_robot/tree/master/romeo_description) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| SigmaBan | Rhoban | [URDF](https://github.com/Rhoban/sigmaban_urdf) | MIT | ✔️ | ✔️ | ✔️ |
| TALOS | PAL Robotics | [URDF](https://github.com/stack-of-tasks/talos-data) | LGPL-3.0 | ✔️ | ✔️ | ✔️ |
| Valkyrie | NASA JSC Robotics | [URDF](https://github.com/gkjohnson/nasa-urdf-robots/tree/master/val_description/model), [Xacro](https://gitlab.com/nasa-jsc-robotics/val_description) | NASA-1.3 | ✔️ | ✔️ | ✔️ |
| WALK-MAN | IIT | [Xacro](https://github.com/ADVRHumanoids/iit-walkman-ros-pkg/tree/master/walkman_urdf) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| H1 | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_ros/tree/master/robots/h1_description), [USD](https://github.com/unitreerobotics/unitree_model/tree/main/H1/usd), [OmniSim URDF/MJCF variants](https://github.com/omnilink-tech/omnisim/tree/main/projects/robots/unitree/h1/urdf) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| G1 | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_ros/tree/master/robots/g1_description), [OmniSim URDF variants](https://github.com/omnilink-tech/omnisim/tree/main/projects/robots/unitree/g1/urdf) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| H1-2 (preview) | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_rl_gym/tree/main/resources/robots/h1_2) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |

<p align="right">(<a href="#contents">back to top</a>)</p>

---

## 📰 News

| Date | Event |
|:-----|:------|
| **2026-03-16** | **NVIDIA GTC 2026**: Announcing partnerships with TI to accelerate safe deployment of humanoid robots [[Blog](https://blogs.nvidia.com/blog/gtc-2026-news/)] [[Robotics 24/7](https://www.robotics247.com/article/nvidia-gtc-2026-texas-instruments-nvidia-partner-to-accelerate-safe-deployment-of-humanoids)] |
| **2026-03-12** | **Tesla** unveils third-generation Optimus at AWE 2026 in Shanghai, featuring 22-DoF hands and 8-hour battery life [[News](https://chinaroboticsdaily.com/tesla-optimus-gen-3-awe-2026/)] |
| **2026-01-27** | **Figure AI** introduces Helix 02: Full-Body Autonomy, achieving 67 consecutive hours of autonomous work [[Website](https://www.figure.ai/news/helix-02)] |
| **2026-01** | **NVIDIA** unveils Isaac GR00T N1.6 foundation model for humanoid robots at CES 2026 [[Project](https://research.nvidia.com/labs/gear/gr00t-n1_6/)] [[Github](https://github.com/NVIDIA/Isaac-GR00T)] [[HuggingFace](https://huggingface.co/nvidia/GR00T-N1.6-3B)] |
| **2025-08** | **The First Humanoid Robot Games** [[Website](https://www.whrgoc.com/)] |
| **2025-07-30** | **X-Humanoid** releases Humanoid Occupancy, a generalized multimodal perception system [[Project](https://humanoid-occupancy.github.io/)] |
| **2025-07-27** | **Unitree** announces their new robot R1 [[Website](https://www.unitree.com/R1)] |
| **2025-03-19** | **Boston Dynamics** — Walk, Run, Crawl, RL Fun \| Atlas [[Youtube](https://www.youtube.com/watch?v=I44_zbEwz_w)] |
| **2025-02-18** | **Unitree** G1 Continues to Dance Despite All Obstacles [[YouTube](https://www.youtube.com/watch?v=XF8U2i62Ob4)] |
| **2025-02-14** | **Unitree**'s G1 Humanoid Robots are RUNNING Now [[YouTube](https://www.youtube.com/watch?v=jylMk0qbDjc)] |
| **2024-12-24** | **Boston Dynamics** — Happy Holidays 2024 [[YouTube](https://www.youtube.com/watch?v=sFkUH5XFHKU)] |
| **2024-12-13** | **Meta** Releases humanoid Env and Project [[Project](https://metamotivo.metademolab.com/)] |
| **2024-11-30** | **Tesla** Optimus Robot Catching a Ball [[Youtube](https://www.youtube.com/watch?v=htXUNnrUFOs)] |
| **2024-11-06** | **XPENG** unveils its advanced humanoid AI Robot Iron [[News](https://www.xpeng.com/news/019301d2135392fa562d8a0282200016)] [[Youtube](https://www.youtube.com/watch?v=743hskjFraE)] |
| **2024-10-24** | **EngineAI** demonstrates a very natural gait [[YouTube](https://www.youtube.com/watch?v=R7tgKCi3DOs)] [[bilibili](https://space.bilibili.com/3546728498202679/)] |
| **2024-10-24** | **AgibotTech** open-source their hardware design schematics and training framework [[Github](https://github.com/AgibotTech)] |
| **2024-10-11** | **Tesla** 'We, Robot' [[Youtube](https://www.youtube.com/watch?v=6v6dbxPlsXs)] |
| **2024-08-21** | **World Robot Conference** in Beijing, 27 humanoid robots participated [[WRC2024](https://www.worldrobotconference.com/)] |
| **2024-07-05** | Humanoid robot vanguard matrix & Optimus at **WAIC 2024** [[YouTube](https://www.youtube.com/shorts/HNNQmPNxR3I)] |
| **2024-07-04** | **Figure** x BMW Group's Spartanburg Plant [[YouTube](https://www.youtube.com/watch?v=UBTELOuy6Us)] |
| **2024-05-14** | **Unitree** G1 Humanoid Agent \| AI Avatar [[YouTube](https://www.youtube.com/watch?v=GzX1qOIO1bE)] |
| **2024-04-17** | **All New Atlas** \| Boston Dynamics [[YouTube](https://www.youtube.com/watch?v=29ECwExc-_M)] [[IEEE Spectrum](https://spectrum.ieee.org/atlas-humanoid-robot-ceo-interview)] |
| **2024-04-16** | **Farewell to HD Atlas** — For almost a decade, Atlas has sparked our imagination [[YouTube](https://www.youtube.com/watch?v=-9EM5_VFlt8)] |
| **2024-04-08** | **Sanctuary AI** — Phoenix at Human-Equivalent Speed [[YouTube](https://www.youtube.com/watch?v=FH3zbUSMAAU)] |
| **2024-03-20** | **Unitree** H1 — The World's First Full-size Motor Drive Humanoid Robot Flips on Ground [[YouTube](https://www.youtube.com/watch?v=V1LyWsiTgms)] |
| **2024-03-18** | **NVIDIA** showcases humanoid robots at GTC 2024 and announces GR00T [[Project](https://developer.nvidia.com/project-gr00t)] [[Video](https://www.youtube.com/watch?v=kr7FaZPFp6M)] |
| **2024-03-06** | **Robot Era** releases humanoid reinforcement sim2real code [[Project](https://sites.google.com/view/humanoid-gym/)] [[Code](https://github.com/roboterax/humanoid-gym)] |
| **2024-03-02** | **Unitree** H1 Breaking humanoid robot speed world record [[YouTube](https://www.youtube.com/watch?v=83ShvgtyFAg)] |
| **2024-02-29** | **PNDbotics** announces their humanoid robot 'Adam' [[Project](https://greatsjk.github.io/Adam-PNDbotics/)] [[Paper](https://arxiv.org/abs/2402.18294)] [[YouTube](https://www.youtube.com/watch?v=7hK2ySYBa1I)] |
| **2024-01-19** | **Figure** announces commercial agreement with BMW Manufacturing [[PR Newswire](https://www.prnewswire.com/news-releases/figure-announces-commercial-agreement-with-bmw-manufacturing-to-bring-general-purpose-robots-into-automotive-production-302036263.html)] |
| **2024-01-16** | **Tesla** Optimus Bot Folds Laundry [[X](https://twitter.com/elonmusk/status/1746970616060580326)] [[YouTube](https://www.youtube.com/watch?v=gyURDZB7imo)] |

<p align="right">(<a href="#contents">back to top</a>)</p>

---

## 📝 Papers

### 2026

| | Title | Links |
|:--|:------|:------|
| `WBC` | **ULTRA**: Unified Multimodal Control for Autonomous Humanoid Whole-Body Loco-Manipulation | [[paper](https://arxiv.org/abs/2603.03279)] |
| `Manipulation` | **HumDex**: Humanoid Dexterous Manipulation Made Easy | [[paper](https://arxiv.org/abs/2603.12260)] [[code](https://github.com/physical-superintelligence-lab/humdex)] |
| `Manipulation` | **UniHM**: Unified Dexterous Hand Manipulation with Vision Language Model | [[paper](https://arxiv.org/abs/2603.00732)] [[project](https://unihm.github.io/)] |
| `Loco-Manipulation` | **Cybo-Waiter**: A Physical Agentic Framework for Humanoid Whole-Body Locomotion-Manipulation | [[paper](https://arxiv.org/abs/2603.10675)] |
| `Locomotion` | **Perceptive Humanoid Parkour**: Chaining Dynamic Human Skills via Motion Matching | [[paper](https://arxiv.org/abs/2602.15827)] |
| `WBC` | **FAST**: General Humanoid Whole-Body Control via Pretraining and Fast Adaptation | [[paper](https://arxiv.org/abs/2602.11929)] |
| `Locomotion` | **Now You See That**: Learning End-to-End Humanoid Locomotion from Raw Pixels | [[paper](https://arxiv.org/abs/2602.06382)] |
| `WBC` | **XHugWBC**: Scalable and General Whole-Body Control for Cross-Humanoid Locomotion | [[paper](https://arxiv.org/abs/2602.05791)] |
| `WBC` | **EAGLE**: Embodiment-Aware Generalist Specialist Distillation for Unified Humanoid WBC | [[paper](https://arxiv.org/abs/2602.02960)] [[project](https://eagle-wbc.github.io/)] |
| `Loco-Manipulation` | **PILOT**: A Perceptive Integrated Low-level Controller for Loco-manipulation | [[paper](https://arxiv.org/abs/2601.17440)] |

### 2025

| | Title | Links |
|:--|:------|:------|
| `WBC` | **EGM**: Efficiently Learning General Motion Tracking Policy for High Dynamic Humanoid WBC | [[paper](https://arxiv.org/abs/2512.19043)] |
| `VLA` | **WholeBodyVLA**: Towards Unified Latent VLA for Whole-Body Loco-Manipulation Control | [[paper](https://arxiv.org/abs/2512.11047)] |
| `Locomotion` | **Gait-Adaptive Perceptive Humanoid Locomotion** with Real-Time Under-Base Terrain Reconstruction | [[paper](https://arxiv.org/abs/2512.07464)] [[project](https://ga-phl.github.io/)] |
| `Teleoperation` | **Learning Adaptive Neural Teleoperation** for Humanoid Robots | [[paper](https://arxiv.org/abs/2511.12390)] |
| `WBC` | **BFM-Zero**: A Promptable Behavioral Foundation Model for Humanoid Control | [[paper](https://www.alphaxiv.org/abs/2511.04131)] |
| `WBC` | **SONIC**: Supersizing Motion Tracking for Natural Humanoid Whole-Body Control | [[paper](https://www.alphaxiv.org/abs/2511.07820)] |
| `WBC` | **Behavior Foundation Model** for Humanoid Robots | [[paper](https://www.alphaxiv.org/abs/2509.13780)] |
| `Manipulation` | **Dexterous Robotic Piano Playing** at Scale | [[paper](https://arxiv.org/pdf/2511.02504)] |
| `Sim` | **GaussGym**: An open-source real-to-sim framework for learning locomotion from pixels | [[paper](https://arxiv.org/abs/2510.15352)] |
| `WBC` | **AdaMimic**: Towards Adaptable Humanoid Control via Adaptive Motion Tracking | [[project](https://taohuang13.github.io/adamimic.github.io/)] |
| `WBC` | **PhysHSI**: Towards a Real-World Generalizable and Natural Humanoid-Scene Interaction | [[project](https://why618188.github.io/physhsi/)] [[code](https://github.com/InternRobotics/PhysHSI)] |
| `Locomotion` | **DPL**: Depth-only Perceptive Humanoid Locomotion via Realistic Depth Synthesis | [[paper](https://arxiv.org/pdf/2510.07152)] |
| `Retargeting` | **Retargeting Matters**: General Motion Retargeting for Humanoid Motion Tracking | [[paper](https://arxiv.org/pdf/2510.02252)] [[code](https://github.com/YanjieZe/GMR)] |
| `Loco-Manipulation` | **OmniRetarget**: Interaction-Preserving Data Generation for Humanoid WB Loco-Manipulation | [[project](https://omniretarget.github.io/)] [[paper](https://arxiv.org/pdf/2509.26633)] |
| `WBC` | **Track Any Motions** under Any Disturbances | [[paper](https://arxiv.org/abs/2509.13833)] |
| `WBC` | **KungfuBot 2**: Learning Versatile Motion Skills for Humanoid Whole-Body Control | [[project](https://kungfubot2-humanoid.github.io/)] |
| `WBC` | **DreamControl**: Human-Inspired WB Humanoid Control for Scene Interaction via Guided Diffusion | [[project](https://genrobo.github.io/DreamControl/)] [[paper](https://genrobo.github.io/DreamControl/static/paper/DreamControl_arxiv.pdf)] [[code](https://github.com/GenRobo/DreamControl/tree/main)] |
| `WBC` | **HDMI**: Learning Interactive Humanoid Whole-Body Control from Human Videos | [[project](https://hdmi-humanoid.github.io/#/)] [[paper](https://hdmi-humanoid.github.io/assets/hdmi-release-paper-CoIFqbGf.pdf)] [[code](https://github.com/LeCAR-Lab/HDMI)] |
| `Locomotion` | **Attention-Based Map Encoding** for Learning Generalized Legged Locomotion | [[paper](https://arxiv.org/abs/2506.09588)] `Science Robotics` |
| `Imitation` | **GBC**: Generalized Behavior-Cloning Framework for Whole-Body Humanoid Imitation | [[paper](https://www.arxiv.org/abs/2508.09960)] |
| `WBC` | **BeyondMimic**: From Motion Tracking to Versatile Humanoid Control via Guided Diffusion | [[project](https://beyondmimic.github.io/)] [[paper](https://arxiv.org/abs/2508.08241)] [[code](https://github.com/HybridRobotics/whole_body_tracking)] |
| `Perception` | **Humanoid Occupancy**: Enabling Generalized Multimodal Occupancy Perception on Humanoid Robots | [[project](https://humanoid-occupancy.github.io/)] |
| `Survey` | A Survey of **Behavior Foundation Model**: Next-Gen WBC System of Humanoid Robots | [[paper](https://arxiv.org/abs/2506.20487)] |
| `Foundation` | **Fast Adaptation** with Behavioral Foundation Models | [[paper](https://arxiv.org/abs/2504.07896)] |
| `WBC` | **UniTracker**: Learning Universal Whole-Body Motion Tracker for Humanoid Robots | [[paper](https://arxiv.org/abs/2507.07356)] |
| `Manipulation` | **TACT**: Humanoid Whole-body Contact Manipulation through Deep Imitation Learning with Tactile | [[paper](https://arxiv.org/pdf/2506.15146)] |
| `WBC` | **General Motion Tracking** for Humanoid Whole-Body Control | [[project](https://gmt-humanoid.github.io/)] [[paper](https://arxiv.org/abs/2506.14770)] [[code](https://github.com/zixuan417/humanoid-general-motion-tracking)] |
| `Loco-Manipulation` | **SkillBlender**: Towards Versatile Humanoid WB Loco-Manipulation via Skill Blending | [[paper](https://arxiv.org/abs/2506.09366)] [[project](https://usc-gvl.github.io/SkillBlender-web/)] [[code](https://github.com/Humanoid-SkillBlender/SkillBlender)] |
| `WBC` | **R2S2**: Unleashing Humanoid Reaching Potential via Real-world-Ready Skill Space | [[project](https://zzk273.github.io/R2S2/)] [[paper](https://www.arxiv.org/pdf/2505.10918)] [[code](https://github.com/GalaxyGeneralRobotics/OpenWBT)] |
| `Teleoperation` | **CLONE**: Closed-Loop Whole-Body Humanoid Teleoperation for Long-Horizon Tasks | [[project](https://humanoid-clone.github.io/)] |
| `Locomotion` | **Hold My Beer**: Learning Gentle Humanoid Locomotion and End-Effector Stabilization | [[paper](https://lecar-lab.github.io/SoFTA/resources/Main-Paper.pdf)] [[project](https://lecar-lab.github.io/SoFTA/)] [[code](https://github.com/LeCAR-Lab/SoFTA)] |
| `Locomotion` | **One Policy but Many Worlds**: A Scalable Unified Policy for Versatile Humanoid Locomotion | [[paper](https://arxiv.org/pdf/2505.18780)] [[project](https://dreampolicy.github.io/)] |
| `Locomotion` | **TD-GRPC**: Temporal Difference Learning with Group Relative Policy Constraint | [[paper](https://arxiv.org/pdf/2505.13549)] |
| `Locomotion` | **HuB**: Learning Extreme Humanoid Balance | [[paper](https://arxiv.org/pdf/2505.07294)] |
| `Loco-Manipulation` | **FALCON**: Learning Force-Adaptive Humanoid Loco-Manipulation | [[paper](https://arxiv.org/pdf/2505.06776)] [[project](https://lecar-lab.github.io/falcon-humanoid/)] |
| `Locomotion` | **Let Humanoids Hike!** Integrative Skill Development on Complex Trails | [[paper](https://arxiv.org/pdf/2505.06218)] [[project](https://lego-h-humanoidrobothiking.github.io/)] |
| `Locomotion` | Towards **Embodiment Scaling Laws** for Robot Locomotion | [[paper](https://arxiv.org/pdf/2505.05753)] |
| `Teleoperation` | **TWIST**: Teleoperated Whole-Body Imitation System | [[paper](https://arxiv.org/pdf/2505.02833)] [[project](https://yanjieze.com/TWIST/)] |
| `WBC` | **AMO**: Adaptive Motion Optimization for Hyper-Dexterous Humanoid Whole-Body Control | [[paper](https://arxiv.org/pdf/2505.03738)] [[project](https://amo-humanoid.github.io/)] |
| `Imitation` | **Visual Imitation** Enables Contextual Humanoid Control | [[paper](https://arxiv.org/pdf/2505.03729)] [[project](https://videomimic.net/)] |
| `WBC` | **LangWBC**: Language-directed Humanoid Whole-Body Control via End-to-end Learning | [[paper](https://arxiv.org/pdf/2504.21738)] [[video](https://youtu.be/9AN0GulqWwc)] |
| `Loco-Manipulation` | **Physically Consistent Humanoid Loco-Manipulation** using Latent Diffusion Models | [[paper](https://arxiv.org/pdf/2504.16843)] |
| `Perception` | **RoboOcc**: Enhancing the Geometric and Semantic Scene Understanding for Robots | [[paper](https://arxiv.org/pdf/2504.14604)] |
| `Locomotion` | **ALMI**: Adversarial Locomotion and Motion Imitation for Humanoid Policy Learning | [[paper](https://arxiv.org/pdf/2504.14305)] [[project](https://almi-humanoid.github.io/)] |
| `Locomotion` | **Robust Humanoid Walking** on Compliant and Uneven Terrain with Deep RL | [[paper](https://arxiv.org/pdf/2504.13619)] [[code](https://github.com/rohanpsingh/LearningHumanoidWalking)] |
| `Hardware` | **RUKA**: Rethinking the Design of Humanoid Hands with Learning | [[paper](https://arxiv.org/pdf/2504.13165)] |
| `Locomotion` | **Teacher Motion Priors**: Enhancing Robot Locomotion over Challenging Terrain | [[paper](https://arxiv.org/pdf/2504.10390)] |
| `RL` | **GROVE**: A Generalized Reward for Learning Open-Vocabulary Physical Skill | [[paper](https://arxiv.org/pdf/2504.04191)] [[project](https://jiemingcui.github.io/grove/)] |
| `WBC` | **FLAM**: Foundation Model-Based Body Stabilization for Humanoid Locomotion and Manipulation | [[paper](https://arxiv.org/pdf/2503.22249)] [[project](https://xianqi-zhang.github.io/FLAM/)] |
| `Animation` | **Think-Then-React**: Towards Unconstrained Human Action-to-Reaction Generation | [[paper](https://arxiv.org/pdf/2503.16451)] |
| `Perception` | **EmbodiedVSR**: Dynamic Scene Graph-Guided Chain-of-Thought Reasoning for Visual Spatial Tasks | [[paper](https://arxiv.org/pdf/2503.11089)] |
| `Manipulation` | **Humanoids in Hospitals**: A Technical Study of Humanoid Surrogates for Medical Interventions | [[paper](https://arxiv.org/pdf/2503.12725)] [[project](https://surgie-humanoid.github.io/)] |
| `Imitation` | **Humanoid Policy ~ Human Policy** | [[paper](https://arxiv.org/pdf/2503.13441)] [[project](https://human-as-robot.github.io/)] |
| `Locomotion` | **Natural Humanoid Robot Locomotion** with Generative Motion Prior | [[paper](https://arxiv.org/pdf/2503.09015)] [[project](https://sites.google.com/view/humanoid-gmp)] |
| `Imitation` | **NIL**: No-data Imitation Learning by Leveraging Pre-trained Video Diffusion Models | [[paper](https://arxiv.org/pdf/2503.10626)] |
| `Imitation` | **RILe**: Reinforced Imitation Learning | [[paper](https://arxiv.org/pdf/2406.08472)] |
| `Teleoperation` | **NuExo**: A Wearable Exoskeleton for Data Collection and Teleoperation of Humanoid Robots | [[paper](https://arxiv.org/pdf/2503.10554)] |
| `Perception` | **HumanoidPano**: Hybrid Spherical Panoramic-LiDAR Cross-Modal Perception | [[paper](https://arxiv.org/abs/2503.09010)] |
| `Locomotion` | **Distillation-PPO**: A Novel Two-Stage RL Framework for Humanoid Perceptive Locomotion | [[paper](https://arxiv.org/abs/2503.08299)] |
| `System` | **Trinity**: A Modular Humanoid Robot AI System | [[paper](https://arxiv.org/abs/2503.08338)] |
| `RL` | **LiPS**: Large-Scale Humanoid Robot RL with Parallel-Series Structures | [[paper](https://arxiv.org/abs/2503.08349)] |
| `Dataset` | **Kaiwu**: A Multimodal Manipulation Dataset and Framework for Robot Learning | [[paper](https://arxiv.org/pdf/2503.05231)] |
| `Benchmark` | **BEHAVIOR Robot Suite**: Streamlining Real-World WB Manipulation for Household Activities | [[paper](https://arxiv.org/pdf/2503.05652)] [[project](https://behavior-robot-suite.github.io/)] |
| `Locomotion` | **Learning Perceptive Humanoid Locomotion** over Challenging Terrain | [[paper](https://arxiv.org/pdf/2503.00692)] |
| `Locomotion` | **Learning Getting-Up Policies** for Real-World Humanoid Robots | [[project](https://humanoid-getup.github.io/)] |
| `Locomotion` | **VB-Com**: Learning Vision-Blind Composite Humanoid Locomotion | [[paper](https://arxiv.org/pdf/2502.14814)] |
| `Planning` | **Diffusion-based Planning** with Learned Viability Filters | [[paper](https://arxiv.org/pdf/2502.19564)] |
| `WBC` | **InterMimic**: Towards Universal Whole-Body Control for Physics-Based Human-Object Interactions | [[paper](https://arxiv.org/pdf/2502.20390)] [[project](https://sirui-xu.github.io/InterMimic)] |
| `Locomotion` | **HiFAR**: Multi-Stage Curriculum Learning for High-Dynamics Humanoid Fall Recovery | [[paper](https://arxiv.org/pdf/2502.20061)] |
| `Locomotion` | **Think on your feet**: Seamless Transition between Human-like Locomotion | [[paper](https://arxiv.org/pdf/2502.18901)] |
| `Locomotion` | **Learning Humanoid Locomotion** with World Model Reconstruction | [[paper](https://arxiv.org/pdf/2502.16230)] |
| `Locomotion` | **COMPASS**: Cross-embOdiment Mobility Policy via Residual RL and Skill Synthesis | [[paper](https://arxiv.org/pdf/2502.16372)] |
| `Locomotion` | **Humanoid Whole-Body Locomotion** on Narrow Terrain via Dynamic Balance and RL | [[paper](https://arxiv.org/pdf/2502.17219)] [[project](https://whole-body-loco.github.io/)] |
| `Locomotion` | **BeamDojo**: Learning Agile Humanoid Locomotion on Sparse Footholds | [[paper](https://arxiv.org/abs/2502.10363)] [[project](https://why618188.github.io/beamdojo/)] |
| `Teleoperation` | **HOMIE**: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit | [[paper](https://arxiv.org/abs/2502.13013)] [[project](https://homietele.github.io/)] |
| `Survey` | **Humanoid Locomotion and Manipulation**: Current Progress and Challenges | [[paper](https://arxiv.org/abs/2501.02116)] |
| `WBC` | **ASAP**: Aligning Simulation and Real-World Physics for Agile Humanoid WB Skills | [[project](https://agile.human2humanoid.com/)] [[code](https://github.com/LeCAR-Lab/ASAP)] |
| `WBC` | **Embrace Collisions**: Humanoid Shadowing for Deployable Contact-Agnostic Motions | [[paper](https://arxiv.org/abs/2502.01465)] |
| `Locomotion` | **Learning Getting-Up Policies** for Real-World Humanoid Robots | [[paper](https://arxiv.org/pdf/2502.12152)] |

<details>
<summary><b>2024</b> (click to expand)</summary>

### 2024

| | Title | Links |
|:--|:------|:------|
| `Teleoperation` | **ARMADA**: Augmented Reality for Robot Manipulation and Robot-Free Data Acquisition | [[project](https://nataliya.dev/armada)] |
| `Perception` | **ARMOR**: Egocentric Perception for Humanoid Robot Collision Avoidance and Motion Planning | [[paper](https://arxiv.org/pdf/2412.00396v1)] |
| `WBC` | **Exbody2**: Advanced Expressive Humanoid Whole-Body Control | [[project](https://exbody2.github.io/)] |
| `WBC` | **Mobile-TeleVision**: Predictive Motion Priors for Humanoid Whole-Body Control | [[project](https://mobile-tv.github.io/)] |
| `Foundation` | **Zero-Shot Whole-Body Humanoid Control** via Behavioral Foundation Models | [[project](https://metamotivo.metademolab.com/)] [[code](https://github.com/facebookresearch/metamotivo)] [[paper](https://ai.meta.com/research/publications/zero-shot-whole-body-humanoid-control-via-behavioral-foundation-models/)] |
| `WBC` | **HOVER**: Versatile Neural Whole-Body Controller for Humanoid Robots | [[project](https://hover-versatile-humanoid.github.io/)] |
| `Locomotion` | **PIM**: Learning Humanoid Locomotion with Perceptive Internal Model | [[project](https://junfeng-long.github.io/PIM/)] |
| `Locomotion` | **Learning Humanoid Locomotion** over Challenging Terrain | [[paper](https://arxiv.org/pdf/2410.03654)] |
| `Locomotion` | **One Policy to Run Them All**: End-to-end Multi-Embodiment Locomotion | [[paper](https://arxiv.org/abs/2409.06366)] [[code](https://github.com/nico-bohlinger/one_policy_to_run_them_all)] `CoRL` |
| `Locomotion` | **DiffuseLoco**: Real-Time Legged Locomotion Control with Diffusion | [[paper](https://arxiv.org/abs/2404.19264)] `CoRL` |
| `Manipulation` | **Generalizable Humanoid Manipulation** with Improved 3D Diffusion Policies | [[paper](https://arxiv.org/abs/2410.10803)] |
| `Imitation` | **OKAMI**: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation | [[paper](https://arxiv.org/pdf/2410.11792)] `CoRL` |
| `Locomotion` | **Learning Smooth Humanoid Locomotion** through Lipschitz-Constrained Policies | [[project](https://lipschitz-constrained-policy.github.io/)] [[paper](https://arxiv.org/abs/2410.11825)] [[code](https://github.com/zixuan417/smooth-humanoid-locomotion)] |
| `RL` | **Stage-Wise Reward Shaping** for Acrobatic Robots: Constrained Multi-Objective RL | [[paper](https://arxiv.org/pdf/2409.15755)] |
| `Animation` | **MaskedMimic**: Unified Physics-Based Character Control Through Masked Motion Inpainting | [[project](https://research.nvidia.com/labs/par/maskedmimic/)] [[paper](https://research.nvidia.com/labs/par/maskedmimic/assets/SIGGRAPHAsia2024_MaskedMimic.pdf)] `SIGGRAPH` |
| `Locomotion` | **Adapting Humanoid Locomotion** over Challenging Terrain via Two-Phase Training | [[project](https://sites.google.com/view/adapting-humanoid-locomotion/two-phase-training)] `CoRL` |
| `Animation` | **Robot Motion Diffusion Model**: Motion Generation for Robotic Characters | [[project](https://la.disneyresearch.com/publication/robot-motion-diffusion-model-motion-generation-for-robotic-characters/)] `SIGGRAPH` |
| `Survey` | **Teleoperation of Humanoid Robots**: A Survey | [[paper](https://arxiv.org/pdf/2301.04317)] |
| `Animation` | **VMP**: Versatile Motion Priors for Robustly Tracking Motion on Physical Characters | [[project](https://la.disneyresearch.com/publication/vmp-versatile-motion-priors-for-robustly-tracking-motion-on-physical-characters/)] `SIGGRAPH` |
| `MPC` | **Tailoring Solution Accuracy** for Fast Whole-body MPC of Legged Robots | [[paper](https://arxiv.org/abs/2407.10789)] [[video](https://www.youtube.com/watch?v=Xmi7AFGhlFc)] |
| `Locomotion` | **Advancing Humanoid Locomotion**: Mastering Challenging Terrains with Denoising World Model | [[paper](https://roboticsconference.org/program/papers/58/)] `RSS` |
| `Animation` | **Design and Control of a Bipedal Robotic Character** | [[paper](https://la.disneyresearch.com/publication/design-and-control-of-a-bipedal-robotic-character/)] [[video](https://www.youtube.com/watch?v=7_LW7u-nk6Q)] `RSS` |
| `Teleoperation` | **Open-TeleVision**: Teleoperation with Immersive Active Visual Feedback | [[project](https://robot-tv.github.io/)] |
| `Locomotion` | **Learning Generic and Dynamic Locomotion** of Humanoids Across Discrete Terrains | [[paper](https://arxiv.org/abs/2405.17227)] [[video](https://www.youtube.com/watch?v=h0k11Ess_kc)] |
| `Imitation` | **HumanPlus**: Humanoid Shadowing and Imitation from Humans | [[project](https://humanoid-ai.github.io/)] [[paper](https://humanoid-ai.github.io/HumanPlus.pdf)] [[code](https://github.com/MarkFzp/humanplus)] |
| `WBC` | **WoCoCo**: Learning Whole-Body Humanoid Control with Sequential Contacts | [[project](https://lecar-lab.github.io/wococo/)] [[paper](https://arxiv.org/abs/2406.06005)] |
| `Teleoperation` | **OmniH2O**: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation | [[project](https://omni.human2humanoid.com/)] [[paper](https://omni.human2humanoid.com/resources/OmniH2O_paper.pdf)] |
| `Locomotion` | **Humanoid Parkour Learning** | [[project](https://humanoid4parkour.github.io/)] |
| `WBC` | **Hierarchical World Models** as Visual Whole-Body Humanoid Controllers | [[paper](https://arxiv.org/pdf/2405.18418v1)] [[code](https://github.com/nicklashansen/puppeteer)] |
| `Locomotion` | **Toward Understanding Key Estimation** in Learning Robust Humanoid Locomotion | [[paper](https://arxiv.org/abs/2403.05868)] |
| `Retargeting` | **Unsupervised Neural Motion Retargeting** for Humanoid Teleoperation | [[paper](https://arxiv.org/pdf/2406.00727)] |
| `Survey` | **Deep Reinforcement Learning for Bipedal Locomotion**: A Brief Survey | [[paper](https://arxiv.org/abs/2404.17070)] |
| `Locomotion` | **Revisiting Reward Design** and Evaluation for Robust Humanoid Standing and Walking | [[project](https://b-vm.github.io/Robust-SaW/)] [[paper](https://b-vm.github.io/Robust-SaW/IROS_2024__Revisiting_Reward_Design_and_Evaluation_for_Robust_Humanoid_Walking.pdf)] |
| `Sim2Real` | **Humanoid-Gym**: RL for Humanoid Robot with Zero-Shot Sim2Real Transfer | [[paper](https://arxiv.org/abs/2404.05695)] [[code](https://github.com/roboterax/humanoid-gym)] |
| `Survey` | **Humanoid Robots at work**: where are we? | [[paper](https://arxiv.org/abs/2404.04249)] |
| `Manipulation` | **Diffusing in Someone Else's Shoes**: Robotic Perspective Taking with Diffusion | [[paper](https://arxiv.org/abs/2404.07735)] |
| `Manipulation` | **Large Language Models** for Orchestrating Bimanual Robots | [[paper](https://arxiv.org/abs/2404.02018)] |
| `Locomotion` | **Humanoid Locomotion as Next Token Prediction** | [[paper](https://arxiv.org/abs/2402.19469)] |
| `Benchmark` | **HumanoidBench**: Simulated Humanoid Benchmark for WB Locomotion and Manipulation | [[project](https://humanoid-bench.github.io/)] [[paper](https://arxiv.org/abs/2403.10506)] [[code](https://github.com/carlosferrazza/humanoid-bench)] |
| `Teleoperation` | **Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation** | [[paper](https://arxiv.org/abs/2403.04436)] [[video](https://www.youtube.com/watch?v=0W4N2q7xtcQ)] |
| `Locomotion` | **RL for Versatile, Dynamic, and Robust Bipedal Locomotion Control** | [[paper](https://arxiv.org/abs/2401.16889)] [[video](https://www.youtube.com/watch?v=sQEnDbET75g)] |
| `Imitation` | **Whole-body Humanoid Robot Locomotion** with Human Reference | [[project](https://greatsjk.github.io/Adam-PNDbotics/)] [[paper](https://arxiv.org/abs/2402.18294)] [[video](https://www.youtube.com/watch?v=7hK2ySYBa1I)] |
| `Imitation` | **Expressive Whole-Body Control** for Humanoid Robots | [[project](https://expressive-humanoid.github.io/)] [[paper](https://arxiv.org/abs/2402.16796)] |

</details>

<details>
<summary><b>2023</b> (click to expand)</summary>

### 2023

| | Title | Links |
|:--|:------|:------|
| `Generative` | **Hierarchical generative modelling** for autonomous robots | [[paper](https://www.nature.com/articles/s42256-023-00752-z)] `Nature Machine Intelligence` |
| `Locomotion` | **Optimizing Bipedal Locomotion** for The 100m Dash With Comparison to Human Running | [[paper](https://ieeexplore.ieee.org/document/10160436/)] `ICRA` |
| `Locomotion` | **Learning Vision-Based Bipedal Locomotion** for Challenging Terrain | [[paper](http://arxiv.org/abs/2309.14594)] |
| `Imitation` | **Development of a Whole-body Work Imitation Learning System** by a Biped and Bi-armed Humanoid | [[paper](https://arxiv.org/abs/2309.15756)] [[project](https://haraduka.github.io/jaxon-tablis-imitation/)] `IROS` |
| `Locomotion` | **Learning Bipedal Walking** for Humanoids with Current Feedback | [[paper](https://arxiv.org/pdf/2303.03724.pdf)] [[code](https://github.com/rohanpsingh/LearningHumanoidWalking/tree/topic/omnidirectional-walk)] |
| `Locomotion` | **Learning Humanoid Locomotion** with Transformers | [[paper](https://arxiv.org/pdf/2303.03381.pdf)] |
| `Teleoperation` | **Deep Imitation Learning** for Humanoid Loco-manipulation through Human Teleoperation | [[paper](https://arxiv.org/pdf/2309.01952.pdf)] [[project](https://ut-austin-rpl.github.io/TRILL/)] [[code](https://github.com/UT-Austin-RPL/TRILL)] `Humanoid` |
| `RL` | **Benchmarking Potential Based Rewards** for Learning Humanoid Locomotion | [[paper](https://ieeexplore.ieee.org/abstract/document/10160885)] `ICRA` |
| `Locomotion` | **Learning Complex Motor Skills** for Legged Robot Fall Recovery | [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10138662)] `IEEE-RAL` |

</details>

<details>
<summary><b>2022</b> (click to expand)</summary>

### 2022

| | Title | Links |
|:--|:------|:------|
| `Imitation` | **MoCapAct**: A Multi-Task Dataset for Simulated Humanoid Control | [[paper](https://arxiv.org/pdf/2208.07363.pdf)] [[project](https://microsoft.github.io/MoCapAct/)] |
| `Imitation` | **Imitate and Repurpose**: Learning Reusable Robot Movement Skills | [[paper](https://arxiv.org/abs/2203.17138)] |
| `Sim2Real` | **NeRF2Real**: Sim2real Transfer of Vision-guided Bipedal Motion Skills | [[paper](https://arxiv.org/pdf/2210.04932.pdf)] |
| `Locomotion` | **Learning Bipedal Walking** On Planned Footsteps For Humanoid Robots | [[paper](https://arxiv.org/pdf/2207.12644.pdf)] [[code](https://github.com/rohanpsingh/LearningHumanoidWalking)] |
| `Sim2Real` | **Dynamic Bipedal Maneuvers** through Sim-to-Real Reinforcement Learning | [[paper](https://arxiv.org/abs/2207.07835)] |
| `Sim2Real` | **Sim-to-Real Learning** of Compliant Bipedal Locomotion on Torque Sensor-Less Humanoid | [[paper](https://arxiv.org/abs/2204.03897)] |
| `Locomotion` | **Towards Real Robot Learning in the Wild**: A Case Study in Bipedal Locomotion | [[paper](https://proceedings.mlr.press/v164/bloesch22a/bloesch22a.pdf)] `PMLR` |
| `Platform` | **Learning to Walk in Minutes** Using Massively Parallel Deep RL | [[paper](https://proceedings.mlr.press/v164/rudin22a/rudin22a.pdf)] [[code](https://github.com/leggedrobotics/legged_gym)] `PMLR` |
| `Sim2Real` | **Sim-to-Real Learning of Footstep-Constrained Bipedal Dynamic Walking** | [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9812015)] `ICRA` |
| `Animation` | **ASE**: Large-Scale Reusable Adversarial Skill Embeddings | [[paper](https://dl.acm.org/doi/pdf/10.1145/3528223.3530110)] `ACM SIGGRAPH` |
| `Imitation` | **Custom Sine Waves Are Enough** for Imitation Learning of Bipedal Gaits | [[paper](https://arxiv.org/abs/2204.04157)] `ICMA` |
| `MPC` | **Deep RL for Model Predictive Controller** Based on Disturbed SRBM of Biped Robots | [[paper](https://www.mdpi.com/2075-1702/10/11/975)] `Machines` |
| `RL` | **Improving Sample Efficiency** of Deep RL for Bipedal Walking | [[paper](https://ieeexplore.ieee.org/document/10000068)] [[code](https://github.com/rgalljamov/learn2walk)] `IEEE-RAS` |
| `Sim2Real` | **Dynamic Bipedal Turning** through Sim-to-Real Reinforcement Learning | [[paper](https://ieeexplore.ieee.org/abstract/document/10000225)] `IEEE-RAS` |
| `Locomotion` | **Learning Bipedal Walking** On Planned Footsteps For Humanoid Robots | [[paper](https://arxiv.org/pdf/2207.12644.pdf)] [[code](https://github.com/rohanpsingh/learninghumanoidwalking)] `IEEE-RAS` |
| `RL` | **Parallel Deep RL Method** for Gait Control of Biped Robot | [[paper](https://ieeexplore.ieee.org/document/9690599)] `TCAS-II` |
| `Locomotion` | **Linear Policies are Sufficient** to Realize Robust Bipedal Walking | [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9682564)] `IEEE-RAL` |

</details>

<details>
<summary><b>2021</b> (click to expand)</summary>

### 2021

| | Title | Links |
|:--|:------|:------|
| `Sim2Real` | **Pushing the Limits**: Running at 3.2m/s on Cassie | [[paper](https://static1.squarespace.com/static/6005cfec3753c24df2490e0a/t/60babe4adeed3270f74ee15f/1622851147856/Jeremy+Dao+-+DW_2021__Fast_Running.pdf)] |
| `Sim2Real` | **RL for Robust Parameterized Locomotion Control** of Bipedal Robots | [[paper](https://ieeexplore.ieee.org/abstract/document/9560769)] `ICRA` |
| `Locomotion` | **Sim-to-Real Learning** of All Common Bipedal Gaits via Periodic Reward Composition | [[paper](https://arxiv.org/abs/2011.01387)] `ICRA` |
| `Locomotion` | **Deepwalk**: Omnidirectional bipedal gait by deep reinforcement learning | [[paper](https://www.ais.uni-bonn.de/papers/ICRA_2021_Rodriguez.pdf)] `ICRA` |
| `Locomotion` | **Robust Feedback Motion Policy Design** Using RL on a 3D Digit Bipedal Robot | [[paper](https://ieeexplore.ieee.org/abstract/document/9636467)] `IROS` |
| `Sim2Real` | **Blind Bipedal Stair Traversal** via Sim-to-Real Reinforcement Learning | [[paper](https://www.ais.uni-bonn.de/papers/ICRA_2021_Rodriguez.pdf)] `RSS` |
| `Locomotion` | **Learning Task Space Actions** for Bipedal Locomotion | [[paper](https://arxiv.org/pdf/2011.04741.pdf)] `ICRA` |

</details>

<details>
<summary><b>2020</b> (click to expand)</summary>

### 2020

| | Title | Links |
|:--|:------|:------|
| `Sim2Real` | **Learning Memory-Based Control** for Human-Scale Bipedal Locomotion | [[paper](https://arxiv.org/abs/2006.02402)] [[code](https://github.com/osudrl/RSS-2020-learning-memory-based-control)] `RSS` |
| `Sim2Real` | **Learning Locomotion Skills for Cassie**: Iterative Design and Sim-to-Real | [[paper](http://proceedings.mlr.press/v100/xie20a/xie20a.pdf)] `PMLR` |
| `Locomotion` | **Learning Natural Locomotion Behaviors** for Humanoid Robots Using Human Bias | [[paper](https://ieeexplore.ieee.org/document/8990011)] `IEEE-RAL` |
| `Manipulation` | **Grasping Field**: Learning Implicit Representations for Human Grasps | [[paper](https://arxiv.org/pdf/2008.04451.pdf)] `3DV` |

</details>

<details>
<summary><b>2019</b> (click to expand)</summary>

### 2019

| | Title | Links |
|:--|:------|:------|
| `Sim2Real` | **Sim-to-Real Transfer** for Biped Locomotion | [[paper](https://ieeexplore.ieee.org/abstract/document/8968053)] `IROS` |
| `WBC` | **Catch & Carry**: Reusable Neural Controllers for Vision-Guided Whole-Body Tasks | [[paper](https://arxiv.org/abs/1911.06636)] `SIGGRAPH` |
| `Locomotion` | **Learning Agile and Dynamic Motor Skills** for Legged Robots | [[paper](https://arxiv.org/pdf/1901.08652.pdf)] [[code](https://github.com/junja94/anymal_science_robotics_supplementary)] `Science Robotics` |

</details>

<details>
<summary><b>2018</b> (click to expand)</summary>

### 2018

| | Title | Links |
|:--|:------|:------|
| `WBC` | **Learning Whole-body Motor Skills** for Humanoids | [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8625045)] `IEEE RAS` |

</details>

<p align="right">(<a href="#contents">back to top</a>)</p>

---

## 🔗 Related Awesome-Lists

| Repository | Description |
|:-----------|:------------|
| [awesome-isaac-gym](https://github.com/wangcongrobot/awesome-isaac-gym) | Resources for NVIDIA Isaac Gym |
| [Hybrid Robotics Publications](https://hybrid-robotics.berkeley.edu/publications/) | Berkeley Hybrid Robotics Lab |
| [RL-in-Robotics](https://github.com/Skylark0924/Reinforcement-Learning-in-Robotics) | Reinforcement Learning in Robotics |
| [bipedal-robot-learning](https://github.com/zita-ch/bipedal-robot-learning-collection) | Bipedal robot learning collection |
| [Awesome Quadrupedal Robots](https://github.com/curieuxjy/Awesome_Quadrupedal_Robots) | Quadrupedal robot resources |
| [Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics) | NeRF in Robotics |
| [Legged-Robots](https://github.com/singhaman1750/Legged-Robots) | Legged robot resources |
| [Awesome Robot Descriptions](https://github.com/robot-descriptions/awesome-robot-descriptions) | Robot model descriptions |
| [awesome-legged-locomotion](https://github.com/gaiyi7788/awesome-legged-locomotion-learning) | Legged locomotion learning |
| [awesome-humanoid-manipulation](https://github.com/Tsunami-kun/awesome-humanoid-manipulation) | Humanoid manipulation resources |

<p align="right">(<a href="#contents">back to top</a>)</p>

---

## ⭐ Star History

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=jonyzhang2023/awesome-humanoid-learning&type=Date)](https://star-history.com/#jonyzhang2023/awesome-humanoid-learning&Date)

</div>

---

## 🤝 Contributing

Contributions are warmly welcomed! If you find a missing paper, news, or robot model, please open a [Pull Request](https://github.com/jonyzhang2023/awesome-humanoid-learning/pulls) or [Issue](https://github.com/jonyzhang2023/awesome-humanoid-learning/issues).

When adding a new paper, please follow this format in the corresponding year's table:

```
| `Category` | **Paper Title** | [[paper](url)] [[project](url)] [[code](url)] |
```

---

<div align="center">
<i>If you find this repository helpful, please consider giving it a star!</i>
</div>
