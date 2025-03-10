# awesome-humanoid-learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources relevant to humanoid robots learning.

Given the similarities between the locomotion of humanoid robots and bipedal robots, we have included some works on bipedal locomotion for reference.

In recent research, I have noticed an increasing convergence between humanoid robotics and physics-based animation. I believe this is a highly promising direction for the development of humanoid robots. Therefore, I will be updating this repository with animation works that I find beneficial for humanoid robotics.

## Robot models

### Bipeds

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|------|-------|---------|---------|--------|----------|------------|
| Bolt | ODRI | [URDF](https://github.com/Gepetto/example-robot-data/tree/master/robots/bolt_description) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| Cassie (MJCF) | Agility Robotics | [MJCF](https://github.com/deepmind/mujoco_menagerie/tree/main/agility_cassie) | MIT | ✔️ | ✔️ | ✔️ |
| Cassie (URDF) | Agility Robotics | [URDF](https://github.com/robot-descriptions/cassie_description) | MIT | ✔️ | ✔️ | ✔️ |
| Spryped | Benjamin Bokser | [URDF](https://github.com/bbokser/spryped/tree/master/spryped_urdf_rev06) | GPL-3.0 | ✔️ | ✔️ | ✔️ |
| Upkie | Tast's Robots | [URDF](https://github.com/tasts-robots/upkie_description) | Apache-2.0 | ✔️ | ✔️ | ✔️ |
| Hector | [USC DRCL](https://sites.usc.edu/quann/robots/) | [URDF](https://github.com/DRCL-USC/Hector_Simulation) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| SA01 | [EngineAI](https://www.engineai.com.cn/) | [URDF & MJCF](https://github.com/engineai-robotics/engineai_legged_gym) | :heavy_minus_sign: | ✔️ | ✔️ | ✔️ |

### Humanoids

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|------|-------|---------|---------|--------|----------|------------|
| Atlas DRC (v3) | Boston Dynamics | [URDF](https://github.com/RobotLocomotion/drake/tree/master/examples/atlas) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| Atlas v4 | Boston Dynamics | [URDF](https://github.com/openai/roboschool/tree/1.0.49/roboschool/models_robot/atlas_description) | MIT | ✔️ | ✔️ | ✔️ |
| Digit | Agility Robotics | [URDF](https://github.com/adubredu/DigitRobot.jl) | ✖️ | ✔️ | ✔️ | ✔️ |
| iCub | IIT | [URDF](https://github.com/robotology/icub-models/tree/master/iCub) | CC-BY-SA-4.0 | ✔️ | ✔️ | ✔️ |
| JAXON | JSK | [COLLADA](https://github.com/stephane-caron/openrave_models/tree/master/JAXON), [URDF](https://github.com/robot-descriptions/jaxon_description), [VRML](https://github.com/start-jsk/rtmros_choreonoid/tree/master/jvrc_models/JAXON_JVRC) | CC-BY-SA-4.0 | ✔️ | ✔️ | ✔️ |
| JVRC-1 | AIST | [MJCF](https://github.com/isri-aist/jvrc_mj_description/), [URDF](https://github.com/stephane-caron/jvrc_description) | BSD-2-Clause | ✔️ | ✔️ | ✔️ |
| NAO | SoftBank Robotics | [URDF](https://github.com/ros-naoqi/nao_robot/tree/master/nao_description/urdf/naoV50_generated_urdf), [Xacro](https://github.com/ros-naoqi/nao_robot/tree/master/nao_description/) | BSD-3-Clause | [:heavy_minus_sign:](https://github.com/ros-naoqi/nao_meshes#readme) | ✔️ | ✔️ |
| Robonaut 2 | NASA JSC Robotics | [URDF](https://github.com/gkjohnson/nasa-urdf-robots/tree/master/r2_description) | NASA-1.3 | ✔️ | ✔️ | ✔️ |
| Romeo | Aldebaran Robotics | [URDF](https://github.com/ros-aldebaran/romeo_robot/tree/master/romeo_description) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| SigmaBan | Rhoban | [URDF](https://github.com/Rhoban/sigmaban_urdf) | MIT | ✔️ | ✔️ | ✔️ |
| TALOS | PAL Robotics | [URDF](https://github.com/stack-of-tasks/talos-data) | LGPL-3.0 | ✔️ | ✔️ | ✔️ |
| Valkyrie | NASA JSC Robotics | [URDF](https://github.com/gkjohnson/nasa-urdf-robots/tree/master/val_description/model), [Xacro](https://gitlab.com/nasa-jsc-robotics/val_description) | NASA-1.3 | ✔️ | ✔️ | ✔️ |
| WALK-MAN | IIT | [Xacro](https://github.com/ADVRHumanoids/iit-walkman-ros-pkg/tree/master/walkman_urdf) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| H1 | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_ros/tree/master/robots/h1_description), [USD](https://github.com/unitreerobotics/unitree_model/tree/main/H1/usd) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| G1 | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_ros/tree/master/robots/g1_description) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| H1-2 (preview) | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_rl_gym/tree/main/resources/robots/h1_2), [Simplified URDF](https://github.com/unitreerobotics/unitree_rl_gym/tree/main/resources/robots/h1_2) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |

## News

- **[20250218]** **Unitree G1 Continues to Dance Despite All Obstacles | Unitree G1 Humanoid Robot** [[YouTube](https://www.youtube.com/watch?v=XF8U2i62Ob4)]

- **[20250214]** **Unitree's G1 Humanoid Robots are RUNNING Now** [[YouTube](https://www.youtube.com/watch?v=jylMk0qbDjc)]

- **[20241224]** Happy Holidays | 2024 | Boston Dynamics [[YouTube](https://www.youtube.com/watch?v=sFkUH5XFHKU)]

- **[20241213]** **Meta Releases humanoid Env and Project** [[project](https://metamotivo.metademolab.com/)]

- **[20241130]** **Tesla Optimus Robot Catching a Ball** [[Youtube](https://www.youtube.com/watch?v=htXUNnrUFOs)]

- **[20241106]** **XPENG unveils its advanced humanoid AI Robot Iron, marking a new frontier in robotics applications.** [[News](https://www.xpeng.com/news/019301d2135392fa562d8a0282200016)] [[Youtube](https://www.youtube.com/watch?v=743hskjFraE)]

- **[20241024]** **EngineAI-robotics demonstrate a very natural gait** [[YouTube](https://www.youtube.com/watch?v=R7tgKCi3DOs)] [[bilibili](https://space.bilibili.com/3546728498202679/)]

- **[20241024]** **AgibotTech open-source their hardware design schematics and training framework** [[AgibotTech Github](https://github.com/AgibotTech)]

- **[20241011]** **Tesla 'We, Robot'** [[Youtube](https://www.youtube.com/watch?v=6v6dbxPlsXs)]

- **[20240821]** **The World Robot Conference was held in Beijing, with a total of 27 humanoid robots participating in the event.** [[WRC2024](https://www.worldrobotconference.com/)]

- **[20240705]** **Humanoid robot vanguard matrix & Optiums at WAIC 2024** [[YouTube](https://www.youtube.com/shorts/HNNQmPNxR3I)]

- **[20240704]** **Figure x BMW Group's Spartanburg Plant** [[YouTube](https://www.youtube.com/watch?v=UBTELOuy6Us)]

- **[20240514]** **Unitree G1 Humanoid Agent | AI Avatar** [[YouTube](https://www.youtube.com/watch?v=GzX1qOIO1bE)]
  
- **[20240417]** **All New Atlas | Boston Dynamics** [[YouTube](https://www.youtube.com/watch?v=29ECwExc-_M) | [IEEE SPECTRUM](https://spectrum.ieee.org/atlas-humanoid-robot-ceo-interview)]

- **[20240416]** **Farewell to HD Atlas** 😢❤️ For almost a decade, Atlas has sparked our imagination, inspired the next generations of roboticists, and leapt over technical barriers in the field. ❤️ [[YouTube](https://www.youtube.com/watch?v=-9EM5_VFlt8)] 

- **[20240408]** Sanctuary AI - Phoenix at Human-Equivalent Speed [[YouTube](https://www.youtube.com/watch?v=FH3zbUSMAAU)]

- **[20240320]** Unitree H1 The World's First Full-size Motor Drive Humanoid Robot Flips on Ground! AWESOME! [[YouTube](https://www.youtube.com/watch?v=V1LyWsiTgms)]

- **[20240318]** **NVIDIA showcase the intelligent future of humanoid robots at GTC 2024 and announce a new project called GR00T** [[project](https://developer.nvidia.com/project-gr00t) | [video1](https://www.youtube.com/watch?v=kr7FaZPFp6M) | [video2](https://www.youtube.com/watch?v=51TYhPJ4zys)]

- **[20240306]** Robot Era releases their humanoid reinforcement sim2real code! [[project](https://sites.google.com/view/humanoid-gym/) | [Code](https://github.com/roboterax/humanoid-gym)]

- **[20240302]** Unitree H1 Breaking humanoid robot speed world record [full-size humanoid] Evolution V3.0 [[YouTube](https://www.youtube.com/watch?v=83ShvgtyFAg)]

- **[20240229]** PNDbotics announces their humanoid robot 'Adam' [[project](https://greatsjk.github.io/Adam-PNDbotics/) | [paper](https://arxiv.org/abs/2402.18294) | [YouTube](https://www.youtube.com/watch?v=7hK2ySYBa1I)]

- **[20240119]** Figure announces commercial agreement with BMW Manufacturing to bring general purpose robots into automotive production [[PR Newswire](https://www.prnewswire.com/news-releases/figure-announces-commercial-agreement-with-bmw-manufacturing-to-bring-general-purpose-robots-into-automotive-production-302036263.html) | [YouTube](https://www.youtube.com/watch?v=mXF1qOv74z8)]

- **[20240116]** Tesla Optimus Bot Folds Laundry [ [X](https://twitter.com/elonmusk/status/1746970616060580326) | [YouTube](https://www.youtube.com/watch?v=gyURDZB7imo) ]



## Papers

### 2025

- [2025] Kaiwu: A Multimodal Manipulation Dataset and Framework for Robot Learning and Human-Robot Interaction [[paper](https://arxiv.org/pdf/2503.05231)]

- [2025] BEHAVIOR Robot Suite: Streamlining Real-World Whole-Body Manipulation for Everyday Household Activities [[paper](https://arxiv.org/pdf/2503.05652)] [[project](https://behavior-robot-suite.github.io/)] 

- [2025] Learning Perceptive Humanoid Locomotion over Challenging Terrain [[paper](https://arxiv.org/pdf/2503.00692)]

- [2025] Learning Getting-Up Policies for Real-World Humanoid Robots [[project](https://humanoid-getup.github.io/)]

- [2025] VB-Com: Learning Vision-Blind Composite Humanoid Locomotion Against Deficient Perception [[paper](https://arxiv.org/pdf/2502.14814)]

- [2025] Diffusion-based Planning with Learned Viability Filters [[paper](https://arxiv.org/pdf/2502.19564)]

- [2025] InterMimic: Towards Universal Whole-Body Control for Physics-Based Human-Object Interactions [[paper](https://arxiv.org/pdf/2502.20390)] [[project](https://sirui-xu.github.io/InterMimic)]

- [2025] HiFAR: Multi-Stage Curriculum Learning for High-Dynamics Humanoid Fall Recovery [[paper](https://arxiv.org/pdf/2502.20061)]

- [2025] Think on your feet: Seamless Transition between Human-like Locomotion in Response to Changing Commands [[paper](https://arxiv.org/pdf/2502.18901)]

- [2025] Learning Humanoid Locomotion with World Model Reconstruction [[paper](https://arxiv.org/pdf/2502.16230)]

- [2025] COMPASS: Cross-embOdiment Mobility Policy via ResiduAl RL and Skill Synthesis [[paper](https://arxiv.org/pdf/2502.16372)]

- [2025] Humanoid Whole-Body Locomotion on Narrow Terrain via Dynamic Balance and Reinforcement Learning [[paper](https://arxiv.org/pdf/2502.17219)] [[project](https://whole-body-loco.github.io/)]

- [2025] BeamDojo: Learning Agile Humanoid Locomotion on Sparse Footholds [[paper](https://arxiv.org/abs/2502.10363)] [[project](https://why618188.github.io/beamdojo/)]
 
- [2025] HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit [[paper](https://arxiv.org/abs/2502.13013)] [[project](https://homietele.github.io/)]
  
- [2025] Humanoid Locomotion and Manipulation: Current Progress and Challenges in Control, Planning, and Learning [**Survey**] [[paper](https://arxiv.org/abs/2501.02116)]
  
- [2025] ASAP: Aligning Simulation and Real-World Physics for Learning Agile Humanoid Whole-Body Skills [[project](https://agile.human2humanoid.com/)] [[github](https://github.com/LeCAR-Lab/ASAP)]
 
- [2025] Embrace Collisions: Humanoid Shadowing for Deployable Contact-Agnostics Motions [[paper](https://arxiv.org/abs/2502.01465)]

- [2025] Learning Getting-Up Policies for Real-World Humanoid Robots [[paper](https://arxiv.org/pdf/2502.12152)]

### 2024

- [2024] ARMADA: Augmented Reality for Robot Manipulation and Robot-Free Data Acquisition [[project](https://nataliya.dev/armada)]

- [2024] ARMOR: Egocentric Perception for Humanoid Robot Collision Avoidance and Motion Planning [[paper](https://arxiv.org/pdf/2412.00396v1)]

- [2024] Exbody2: Advanced Expressive Humanoid Whole-Body Control [[project](https://exbody2.github.io/)]

- [2024] Mobile-TeleVision: Predictive Motion Priors for Humanoid Whole-Body Control [[project](https://mobile-tv.github.io/)]

- [2024] Zero-Shot Whole-Body Humanoid Control via Behavioral Foundation Models [[project](https://metamotivo.metademolab.com/)] [[github](https://github.com/facebookresearch/metamotivo?tab=readme-ov-file)] [[paper](https://ai.meta.com/research/publications/zero-shot-whole-body-humanoid-control-via-behavioral-foundation-models/)]

- [2024] HOVER: Versatile Neural Whole-Body Controller for Humanoid Robots [[project](https://hover-versatile-humanoid.github.io/)]
- [2024] Learning Humanoid Locomotion with Perceptive Internal Model [[project](https://junfeng-long.github.io/PIM/)]

- [2024] Learning Humanoid Locomotion over Challenging Terrain [[paper](https://arxiv.org/pdf/2410.03654)]

- [**CoRL**] One Policy to Run Them All: an End-to-end Learning Approach to Multi-Embodiment Locomotion [**XLA**] [[paper](https://arxiv.org/abs/2409.06366)] [[code](https://github.com/nico-bohlinger/one_policy_to_run_them_all)] [[OpenReview](https://openreview.net/forum?id=PbQOZntuXO)]

- [**CoRL**] DiffuseLoco: Real-Time Legged Locomotion Control with Diffusion from Offline Datasets [[paper](https://arxiv.org/abs/2404.19264)] [[OpenReview](https://openreview.net/forum?id=nVJm2RdPDu)]

- [2024] Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies [[paper](https://arxiv.org/abs/2410.10803)]

- [**CoRL**] OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation [[paper](https://arxiv.org/pdf/2410.11792)]

- [2024] Learning Smooth Humanoid Locomotion through Lipschitz-Constrained Policies [[project](https://lipschitz-constrained-policy.github.io/)] [[paper](https://arxiv.org/abs/2410.11825)] [[code](https://github.com/zixuan417/smooth-humanoid-locomotion)]

- [2024] Stage-Wise Reward Shaping for Acrobatic Robots: A Constrained Multi-Objective Reinforcement Learning Approach [[paper](https://arxiv.org/pdf/2409.15755)] 

- [**SIGGRAPH**] MaskedMimic: Unified Physics-Based Character Control Through Masked Motion Inpainting [[project](https://research.nvidia.com/labs/par/maskedmimic/)] [[paper](https://research.nvidia.com/labs/par/maskedmimic/assets/SIGGRAPHAsia2024_MaskedMimic.pdf)]

- [**CoRL**] Adapting Humanoid Locomotion over Challenging Terrain via Two-Phase Training [[project](https://sites.google.com/view/adapting-humanoid-locomotion/two-phase-training)] [[OpenReview](https://openreview.net/forum?id=O0oK2bVist)]

- [**SIGGRAPH**] Robot Motion Diffusion Model: Motion Generation for Robotic Characters [[project](https://la.disneyresearch.com/publication/robot-motion-diffusion-model-motion-generation-for-robotic-characters/)]

- [2024] Teleoperation of Humanoid Robots: A Survey [[paper](https://arxiv.org/pdf/2301.04317)]

- [***SIGGRAPH***] VMP: Versatile Motion Priors for Robustly Tracking Motion on Physical Characters [[project](https://la.disneyresearch.com/publication/vmp-versatile-motion-priors-for-robustly-tracking-motion-on-physical-characters/)]

- [2024] Tailoring Solution Accuracy for Fast Whole-body Model Predictive Control of Legged Robots [[paper](https://arxiv.org/abs/2407.10789)] [[video](https://www.youtube.com/watch?v=Xmi7AFGhlFc)]

- [**RSS**] Advancing Humanoid Locomotion: Mastering Challenging Terrains with Denoising World Model Learning [[paper](https://roboticsconference.org/program/papers/58/)]

- [**RSS**] Design and Control of a Bipedal Robotic Character [[paper](https://la.disneyresearch.com/publication/design-and-control-of-a-bipedal-robotic-character/)] [[video](https://www.youtube.com/watch?v=7_LW7u-nk6Q)]

- [2024] Open-TeleVision : Teleoperation with Immersive Active Visual Feedback [[project](https://robot-tv.github.io/)]

- [2024] Learning Generic and Dynamic Locomotion of Humanoids Across Discrete Terrains [[paper](https://arxiv.org/abs/2405.17227)] [[video](https://www.youtube.com/watch?v=h0k11Ess_kc)]

- [2024] HumanPlus: Humanoid Shadowing and Imitation from Humans [[project](https://humanoid-ai.github.io/)] [[paper](https://humanoid-ai.github.io/HumanPlus.pdf)] [[code](https://github.com/MarkFzp/humanplus)]

- [2024] WoCoCo: Learning Whole-Body Humanoid Control with Sequential Contacts [[project](https://lecar-lab.github.io/wococo/)] [[paper](https://arxiv.org/abs/2406.06005)]

- [2024] OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning [[project](https://omni.human2humanoid.com/)] [[paper](https://omni.human2humanoid.com/resources/OmniH2O_paper.pdf)] 

- [2024] Humanoid Parkour Learning [[project](https://humanoid4parkour.github.io/)] 

- [2024] Hierarchical World Models as Visual Whole-Body Humanoid Controllers [[paper](https://arxiv.org/pdf/2405.18418v1)] [[code](https://github.com/nicklashansen/puppeteer)]

- [2024] Toward Understanding Key Estimation in Learning Robust Humanoid Locomotion [[paper](https://arxiv.org/abs/2403.05868)]

- [2024] Unsupervised Neural Motion Retargeting for Humanoid Teleoperation [[paper](https://arxiv.org/pdf/2406.00727)]

- [2024] Deep Reinforcement Learning for Bipedal Locomotion: A Brief Survey [[paper](https://arxiv.org/abs/2404.17070)]

- [2024] Revisiting Reward Design and Evaluation for Robust Humanoid Standing and Walking [[project](https://b-vm.github.io/Robust-SaW/)] [[paper](https://b-vm.github.io/Robust-SaW/IROS_2024__Revisiting_Reward_Design_and_Evaluation_for_Robust_Humanoid_Walking.pdf)]

- [2024] Humanoid-Gym: Reinforcement Learning for Humanoid Robot with Zero-Shot Sim2Real Transfer [[paper](https://arxiv.org/abs/2404.05695)] [[code](https://github.com/roboterax/humanoid-gym)]

- [2024] Humanoid Robots at work: where are we ? [**Survey**] [[paper](https://arxiv.org/abs/2404.04249)]

- [2024] Diffusing in Someone Else's Shoes: Robotic Perspective Taking with Diffusion [Manipulation] [[paper](https://arxiv.org/abs/2404.07735)]

- [2024] Large Language Models for Orchestrating Bimanual Robots [Manipulation] [[paper](https://arxiv.org/abs/2404.02018)]

- [2024] Humanoid Locomotion as Next Token Prediction [[paper](https://arxiv.org/abs/2402.19469)]

- [2024] HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation [**benchmark**] [[project](https://humanoid-bench.github.io/)] [[paper](https://arxiv.org/abs/2403.10506)] [[code](https://github.com/carlosferrazza/humanoid-bench)]

- [2024] Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation [[paper](https://arxiv.org/abs/2403.04436)] [[video](https://www.youtube.com/watch?v=0W4N2q7xtcQ)]

- [2024] Reinforcement Learning for Versatile, Dynamic, and Robust Bipedal Locomotion Control [[paper](https://arxiv.org/abs/2401.16889)] [[video](https://www.youtube.com/watch?v=sQEnDbET75g)]

- [2024] Whole-body Humanoid Robot Locomotion with Human Reference [**imitation**] [[project](https://greatsjk.github.io/Adam-PNDbotics/)] [[paper](https://arxiv.org/abs/2402.18294)] [[video](https://www.youtube.com/watch?v=7hK2ySYBa1I)]

- [2024] Expressive Whole-Body Control for Humanoid Robots [**imitation**] [[project](https://expressive-humanoid.github.io/)] [[paper](https://arxiv.org/abs/2402.16796)]

### 2023

- [**Nature-Machine-Intelligence**] Hierarchical generative modelling for autonomous robots [[paper](https://www.nature.com/articles/s42256-023-00752-z)]

- [**ICRA**] Optimizing Bipedal Locomotion for The 100m Dash With Comparison to Human Running. [[paper](https://ieeexplore.ieee.org/document/10160436/)]

- [2023] Learning Vision-Based Bipedal Locomotion for Challenging Terrain. [[paper](http://arxiv.org/abs/2309.14594)]

- [**IROS**] Development of a Whole-body Work Imitation Learning System by a Biped and Bi-armed Humanoid [[paper](https://arxiv.org/abs/2309.15756)] [[project](https://haraduka.github.io/jaxon-tablis-imitation/)]

- [2023] Learning Bipedal Walking for Humanoids with Current Feedback. [[paper](https://arxiv.org/pdf/2303.03724.pdf)] [[code](https://github.com/rohanpsingh/LearningHumanoidWalking/tree/topic/omnidirectional-walk)]

- [2023] Learning Humanoid Locomotion with Transformers. [[paper](https://arxiv.org/pdf/2303.03381.pdf)]

- [**Humanoid**] Deep Imitation Learning for Humanoid Loco-manipulation through Human Teleoperation [**imitation**] [**Tele-Opreation**] [[paper](https://arxiv.org/pdf/2309.01952.pdf)] [[project](https://ut-austin-rpl.github.io/TRILL/)] [[code](https://github.com/UT-Austin-RPL/TRILL)]

- [**ICRA**] Benchmarking Potential Based Rewards for Learning Humanoid Locomotion. [[paper](https://ieeexplore.ieee.org/abstract/document/10160885)]

- [**IEEE-RAL**] Learning Complex Motor Skills for Legged Robot Fall Recovery. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10138662)]

### 2022

- [2022] MoCapAct: A Multi-Task Dataset for Simulated Humanoid Control. [**imitation**] [[paper](https://arxiv.org/pdf/2208.07363.pdf)] [[project](https://microsoft.github.io/MoCapAct/)]

- [2022] Imitate and Repurpose: Learning Reusable Robot Movement Skills From Human and Animal Behaviors. [**imitation**] [[paper](https://arxiv.org/abs/2203.17138)]

- [2022] NeRF2Real: Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields. [[paper](https://arxiv.org/pdf/2210.04932.pdf)]

- [2022] Learning Bipedal Walking On Planned Footsteps For Humanoid Robots. [[paper](https://arxiv.org/pdf/2207.12644.pdf)] [[code](https://github.com/rohanpsingh/LearningHumanoidWalking)]

- [2022] Dynamic Bipedal Maneuvers through Sim-to-Real Reinforcement Learning. [[paper](https://arxiv.org/abs/2207.07835)]

- [2022] Sim-to-Real Learning of Compliant Bipedal Locomotion on Torque Sensor-Less Gear-Driven Humanoid. [[paper](https://arxiv.org/abs/2204.03897)]

- [**PMLR**] Towards Real Robot Learning in the Wild: A Case Study in Bipedal Locomotion. [[paper](https://proceedings.mlr.press/v164/bloesch22a/bloesch22a.pdf)]

- [**PMLR**] Learning to Walk in Minutes Using Massively Parallel Deep Reinforcement Learning. [**platform**] [[paper](https://proceedings.mlr.press/v164/rudin22a/rudin22a.pdf)] [[code](https://github.com/leggedrobotics/legged_gym)]

- [**ICRA**] Sim-to-Real Learning of Footstep-Constrained Bipedal Dynamic Walking. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9812015)]


- [**ACM GRAPH**] ASE: Large-Scale Reusable Adversarial Skill Embeddings for Physically Simulated Characters [[paper](https://dl.acm.org/doi/pdf/10.1145/3528223.3530110)]

- [**ICMA**] Custom Sine Waves Are Enough for Imitation Learning of Bipedal Gaits with Different Styles. [[paper](https://arxiv.org/abs/2204.04157)]

- [**Machines**] Deep Reinforcement Learning for Model Predictive Controller Based on Disturbed Single Rigid Body Model of Biped Robots. [[paper](https://www.mdpi.com/2075-1702/10/11/975)]

- [**IEEE-RAS**] Improving Sample Efficiency of Deep Reinforcement Learning for Bipedal Walking. [[paper](https://ieeexplore.ieee.org/document/10000068)] [[code](https://github.com/rgalljamov/learn2walk)] 

- [**IEEE-RAS**] Dynamic Bipedal Turning through Sim-to-Real Reinforcement Learning. [[paper](https://ieeexplore.ieee.org/abstract/document/10000225)]

- [**IEEE-RAS**] Learning Bipedal Walking On Planned Footsteps For Humanoid Robots. [[paper](https://arxiv.org/pdf/2207.12644.pdf)] [[code](https://github.com/rohanpsingh/learninghumanoidwalking)]

- [**TCAS-II**] Parallel Deep Reinforcement Learning Method for Gait Control of Biped Robot. [[paper](https://ieeexplore.ieee.org/document/9690599)]

- [**IEEE-RAL**] Linear Policies are Sufficient to Realize Robust Bipedal Walking on Challenging Terrains. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9682564)]



### 2021


- [2021] Pushing the Limits: Running at 3.2m/s on Cassie. [**sim2real**][[paper](https://static1.squarespace.com/static/6005cfec3753c24df2490e0a/t/60babe4adeed3270f74ee15f/1622851147856/Jeremy+Dao+-+DW_2021__Fast_Running.pdf)]

- [**ICRA**] Reinforcement Learning for Robust Parameterized Locomotion Control of Bipedal Robots. [**sim2real**] [[paper](https://ieeexplore.ieee.org/abstract/document/9560769)]

- [**ICRA**] Sim-to-Real Learning of All Common Bipedal Gaits via Periodic Reward Composition. [[paper](https://arxiv.org/abs/2011.01387)]

- [**ICRA**] Deepwalk: Omnidirectional bipedal gait by deep reinforcement learning. [[paper](https://www.ais.uni-bonn.de/papers/ICRA_2021_Rodriguez.pdf)]

- [**IROS**] Robust Feedback Motion Policy Design Using Reinforcement Learning on a 3D Digit Bipedal Robot. [[paper](https://ieeexplore.ieee.org/abstract/document/9636467)]

- [**RSS**] Blind Bipedal Stair Traversal via Sim-to-Real Reinforcement Learning. [[paper](https://www.ais.uni-bonn.de/papers/ICRA_2021_Rodriguez.pdf)]

- [**ICRA**] Learning Task Space Actions for Bipedal Locomotion [[paper](https://arxiv.org/pdf/2011.04741.pdf)]


### 2020

- [**RSS**] Learning Memory-Based Control for Human-Scale Bipedal Locomotion. [**sim2real**] [[paper](https://arxiv.org/abs/2006.02402)] [[unofficial_code](https://github.com/osudrl/RSS-2020-learning-memory-based-control)]


- [**PMLR**] Learning Locomotion Skills for Cassie: Iterative Design and Sim-to-Real. [[paper](http://proceedings.mlr.press/v100/xie20a/xie20a.pdf)]


- [**IEEE-RAL**] Learning Natural Locomotion Behaviors for Humanoid Robots Using Human Bias. [[paper](https://ieeexplore.ieee.org/document/8990011)]


- [**3DV**] Grasping Field: Learning Implicit Representations for Human Grasps [[paper](https://arxiv.org/pdf/2008.04451.pdf)]



### 2019

- [**IROS**] Sim-to-Real Transfer for Biped Locomotion. [[paper](https://ieeexplore.ieee.org/abstract/document/8968053)]

- [**SIG GRAPH**] Catch & Carry: Reusable Neural Controllers for Vision-Guided Whole-Body Tasks [[paper](https://arxiv.org/abs/1911.06636)]



- [**Science Robotics**] Learning Agile and Dynamic Motor Skills for Legged Robots. [[paper](https://arxiv.org/pdf/1901.08652.pdf)] [[code](https://github.com/junja94/anymal_science_robotics_supplementary)]



### 2018



- [**IEEE RAS**] Learning Whole-body Motor Skills for Humanoids. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8625045)]





## Related awesome-lists

- [awesome-isaac-gym](https://github.com/wangcongrobot/awesome-isaac-gym)
- [Hybrid Robotics Publications](https://hybrid-robotics.berkeley.edu/publications/)
- [Reinforcement-Learning-in-Robotics](https://github.com/Skylark0924/Reinforcement-Learning-in-Robotics)
- [bipedal-robot-learning-collection](https://github.com/zita-ch/bipedal-robot-learning-collection)
- [Awesome_Quadrupedal_Robots](https://github.com/curieuxjy/Awesome_Quadrupedal_Robots)
- [Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)
- [Legged-Robots](https://github.com/singhaman1750/Legged-Robots)
- [Awesome Robot Descriptions](https://github.com/robot-descriptions/awesome-robot-descriptions)
- [awesome-legged-locomotion-learning](https://github.com/gaiyi7788/awesome-legged-locomotion-learning)
- [awesome-humanoid-manipulation](https://github.com/Tsunami-kun/awesome-humanoid-manipulation)


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=jonyzhang2023/awesome-humanoid-learning&type=Date)](https://star-history.com/#jonyzhang2023/awesome-humanoid-learning&Date)
