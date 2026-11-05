# Generative Autonomous Driving Models (GADMs)

### A Survey on Generative Autonomous Driving Models: Foundations, Taxonomy, and Convergence

[![Stars](https://img.shields.io/github/stars/gordonowusuboateng/gadms?style=social)](https://github.com/gordonowusuboateng/gadms/stargazers) [![Issues](https://img.shields.io/github/issues/gordonowusuboateng/gadms)](https://github.com/gordonowusuboateng/gadms/issues) [![Pull Requests](https://img.shields.io/github/issues-pr/gordonowusuboateng/gadms)](https://github.com/gordonowusuboateng/gadms/pulls) [![Last commit](https://img.shields.io/github/last-commit/gordonowusuboateng/gadms)](https://github.com/gordonowusuboateng/gadms/commits/main)


**Gordon Owusu Boateng<sup>1</sup>, Qian Dong<sup>1</sup>, Dongyao Jia<sup>1</sup>, Xiansheng Guo<sup>2</sup>, Azzam Mourad<sup>3</sup>, Nirwan Ansari<sup>4</sup>**

1. Academy of AI and Advanced Technology, Xi'an Jiaotong-Liverpool University, Suzhou, 215123, China.
2. School of Information and Communication Engineering, University of Electronic Science and Technology of China, Chengdu, 611731, China.
3. Department of Computer Science, Khalifa University, Abu Dhabi, UAE.
4. Advanced Networking Lab, Department of Electrical and Computer Engineering, New Jersey Institute of Technology, Newark, NJ 07102, USA.

**Corresponding author:** Gordon Owusu Boateng ([Gordon.Boateng@xjtlu.edu.cn](mailto:Gordon.Boateng@xjtlu.edu.cn))


📚 This repository serves as the curated research companion to **A Survey on Generative Autonomous Driving Models: Foundations, Taxonomy, and Convergence**. It provides a systematically organized collection of research papers, datasets, benchmarks, and evaluation resources spanning three interconnected directions: **generative world modeling**, **generative trajectory and motion planning**, and **Vision-Language-Action (VLA) intelligence**. Beyond cataloging existing studies, the repository highlights their emerging functional convergence toward unified, intelligent, and closed-loop autonomous driving systems, including applications to **Automated Valet Parking (AVP)**. The collection will be updated to reflect new developments and emerging research directions.

**[Browse papers](#paper-collections)** · **[Datasets & benchmarks](#datasets-benchmarks-and-evaluation)** · **[Full bibliography](bibliography.md)** · **[Contribute a paper](CONTRIBUTING.md)**


📢 **Publication and Repository Updates:** This repository accompanies our survey, **A Survey on Generative Autonomous Driving Models: Foundations, Taxonomy, and Convergence**, currently available as a research manuscript. We maintain this collection as an evolving resource for the research community, incorporating relevant publications, datasets, benchmarks, and emerging developments in generative autonomous driving.

📝 **Contributions are welcome!** Feel free to submit [pull requests](https://github.com/gordonowusuboateng/gadms/pulls) or contact us via [email](mailto:Gordon.Boateng@xjtlu.edu.cn) to suggest new papers, contribute research resources, or report corrections. Please refer to our [contribution guidelines](https://github.com/gordonowusuboateng/gadms/blob/main/CONTRIBUTING.md).

⭐ **Support this repository!** If you find this collection useful, please consider [citing our survey](https://github.com/gordonowusuboateng/gadms#citation), [starring the repository](https://github.com/gordonowusuboateng/gadms), and sharing it with the research community. Your contributions and support will help keep this resource comprehensive, accurate, and up to date.


## Contents

- [About this survey](#about-this-survey)
- [Latest additions and 2026 highlights](#latest-additions-and-2026-highlights)
- [Taxonomy and framework](#taxonomy-and-framework)
- [Related surveys](#related-surveys)
- [Paper collections](#paper-collections)
- [Generative world modeling](#generative-world-modeling)
- [Generative trajectory and motion planning](#generative-trajectory-and-motion-planning)
- [Vision-language-action intelligence](#vision-language-action-intelligence)
- [Functional convergence](#functional-convergence)
- [Datasets, benchmarks, and evaluation](#datasets-benchmarks-and-evaluation)
- [Contributing](#contributing)
- [Citation](#citation)

## About This Survey

Generative Autonomous Driving Models (GADMs) can generate future scenes, occupancy, interacting agent trajectories, and driving actions. This survey organizes the literature into **three interrelated research directions** and studies when their interaction leads to meaningful **functional convergence** in autonomous driving scenarios.

<p align="center">
  <img src="assets/manuscript-figures/fig1-transition-gad.png" alt="Figure 1: Transition from deterministic autonomous driving to generative autonomous driving" width="760" />
</p>

*Fig. 1. Transition from deterministic autonomous driving to GAD. Whereas deterministic systems map observations to a single predicted future and action, GAD represents multiple plausible futures, reasons about their
    consequences, and generates safety-aware decisions under uncertainty.*


## Latest Additions and 2026 Highlights

Selected **2026 Related Work**.

- **GenieDrive** (2026) — [arXiv](https://arxiv.org/abs/2512.12751)
- **OccSora** (2026) — [DOI](https://doi.org/10.1109/TIP.2026.3687468)
- **Hermes++** (2026) — [DOI](https://doi.org/10.1109/TPAMI.2026.3735606)
- **ParkDiffusion++** (2026) — [arXiv](https://arxiv.org/abs/2602.20923)
- **OpenDriveVLA** (2026) — [DOI](https://doi.org/10.1609/aaai.v40i16.38386)
- **PlanAgent** (2026) — [DOI](https://doi.org/10.1109/TCDS.2026.3664120)
- **DriveWorld-VLA** (2026) — [Paper](https://arxiv.org/abs/2602.06521)
- **V2X-VLM** (2026) — [DOI](https://doi.org/10.1016/j.trc.2025.105457)

## Taxonomy and Framework

<p align="center"><img src="assets/manuscript-figures/fig2-taxonomy-framework.png" alt="GADM function-oriented taxonomy and conceptual closed-loop framework" width="900" /></p>

*Fig. 2. Function-oriented taxonomy and closed-loop process of GADMs. Imagination, Reasoning, and Motion Generation correspond broadly to generative world modeling, VLA intelligence, and generative trajectory and motion planning, respectively, while Observation, Action, and Learning represent shared system-level functions.*

| Research direction | Key questions | Detailed collection |
| :--- | :--- | :--- |
| **Generative world modeling** | What futures can the model generate, and how do candidate actions affect them? | [World modeling](data/world-modeling.md) |
| **Generative trajectory and motion planning** | How are multimodal trajectories generated, evaluated, and selected? | [Motion generation](data/trajectory-motion.md) |
| **VLA intelligence** | How do language and grounded semantic reasoning influence driving actions? | [VLA intelligence](data/vla-intelligence.md) |



## Related Surveys

- “Generative AI for Autonomous Driving: Frontiers and Opportunities,” *ACM Computing Surveys, 2026*. [[Paper](https://doi.org/10.1145/3838726)]
- “Generative AI for Autonomous Driving: A Review,” *arXiv, 2025*. [[Paper](https://arxiv.org/abs/2505.15863)]
- “Foundation Models for Autonomous Driving: A Comprehensive Survey,” *Engineering Applications of Artificial Intelligence, 2026*. [[Paper](https://doi.org/10.1016/j.engappai.2026.114805)]
- “World Models for Autonomous Driving: An Initial Survey,” *IEEE Transactions on Intelligent Vehicles, 2024*. [[Paper](https://doi.org/10.1109/TIV.2024.3398357)]
- “A Survey of World Models for Autonomous Driving,” *arXiv, 2025*. [[Paper](https://arxiv.org/abs/2501.11260)]
- “The Role of World Models in Shaping Autonomous Driving: A Comprehensive Survey,” *Frontiers of Computer Science, 2026*. [[Paper](https://doi.org/10.1007/s11704-026-60102-1)]
- “A Survey on Multimodal Large Language Models for Autonomous Driving,” *IEEE/CVF WACV Workshops, 2024*. [[Paper](https://doi.org/10.1109/WACVW60836.2024.00106)]
- “A Survey on Vision-Language-Action Models for Autonomous Driving,” *IEEE/CVF ICCV Workshops, 2025*. [[Paper](https://doi.org/10.1109/ICCVW69036.2025.00476)]
- “Vision-Language-Action Models for Autonomous Driving: Past, Present, and Future,” *arXiv, 2026*. [[Paper](https://arxiv.org/abs/2512.16760)]
- “A Survey on Vision-Language-Action Models for Embodied AI,” *IEEE Transactions on Neural Networks and Learning Systems, 2026*. [[Paper](https://doi.org/10.1109/TNNLS.2025.3650584)]
- “A Survey on Efficient Vision-Language-Action Models,” *IEEE Transactions on Pattern Analysis and Machine Intelligence, 2026*. [[Paper](https://doi.org/10.1109/TPAMI.2026.3734740)]
- “End-to-End Autonomous Driving: Challenges and Frontiers,” *IEEE Transactions on Pattern Analysis and Machine Intelligence, 2024*. [[Paper](https://doi.org/10.1109/TPAMI.2024.3435937)]
- “Foundation Models in Autonomous Driving: A Survey on Scenario Generation and Scenario Analysis,” *IEEE Open Journal of Intelligent Transportation Systems, 2026*. [[Paper](https://doi.org/10.1109/OJITS.2026.3660686)]

See the [full bibliography](data/bibliography.md) for the full collection, including foundational generative models, motion planning, datasets, and benchmarks.




## Paper Collections

**Reading guide:** Each item lists a method, title where available, venue/year, and **[Paper]** (DOI or arXiv). **[Code]** is shown only where the authors identify an official repository. Some works appear in multiple directions where research scopes overlap.

## Generative World Modeling in GADMs

<p align="center">
  <img src="assets/manuscript-figures/fig3-world-modeling-taxonomy.png" alt="Figure 3: Taxonomy of generative world models" width="840" />
</p>

*Fig. 3. Taxonomy of generative world models in GADMs. Visual world models generate future sensor observations, geometric and occupancy world models predict spatial occupancy and scene evolution, and latent and agent-centric world models support efficient prediction, policy learning, and interactive traffic simulation.*

### Visual world models

- **DriveGAN** — S. W. Kim, J. Philion, A. Torralba, and S. Fidler, “Drivegan: Towards a controllable high-quality neural simulation,” in 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021, pp. 5816–5825. [[DOI](https://doi.org/10.1109/CVPR46437.2021.00576)]
- **GAIA-1** — A. Hu, L. Russell, H. Yeo, Z. Murez, G. Fedoseev, A. Kendall, J. Shotton, and G. Corrado, “Gaia-1: A generative world model for autonomous driving,” 2023. [Online]. Available: https://arxiv.org/abs/2309.17080
- **GAIA-2** — L. Russell, A. Hu, L. Bertoni, G. Fedoseev, J. Shotton, E. Arani, and G. Corrado, “Gaia-2: A controllable multi-view generative world model for autonomous driving,” 2025. [Online]. Available: https://arxiv.org/abs/2503.20523
- **UniSim** — Z. Yang, Y. Chen, J. Wang, S. Manivasagam, W.-C. Ma, A. J. Yang, and R. Urtasun, “Unisim: A neural closed-loop sensor simulator,” in 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023, pp. 1389–1399. [[DOI](https://doi.org/10.1109/CVPR52729.2023.00140)]
- **Drive-WM** — Y. Wang, J. He, L. Fan, H. Li, Y. Chen, and Z. Zhang, “Driving into the future: Multiview visual forecasting and planning with world model for autonomous driving,” in 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024, pp. 14749–14759. [[DOI](https://doi.org/10.1109/CVPR52733.2024.01397)]
- **DriveDreamer** — X. Wang, Z. Zhu, G. Huang, X. Chen, J. Zhu, and J. Lu, “Drivedreamer: Towards real-world-drive world models for autonomous driving,” in Computer Vision – ECCV 2024. Cham: Springer Nature Switzerland, 2025, pp. 55–72. [[DOI](https://doi.org/10.1007/978-3-031-73195-2_4)]
- **DrivingDiffusion** — X. Li, Y. Zhang, and X. Ye, “Drivingdiffusion: Layout-guided multi-view driving scenarios video generation with latent diffusion model,” in Computer Vision – ECCV 2024. Cham: Springer Nature Switzerland, 2025, pp. 469– 485. [[DOI](https://doi.org/10.1007/978-3-031-73229-4_27)]
- **Panacea** — Y. Wen, Y. Zhao, Y. Liu, F. Jia, Y. Wang, C. Luo, C. Zhang, T. Wang, X. Sun, and X. Zhang, “Panacea: Panoramic and controllable video generation for autonomous driving,” in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), June 2024, pp. 6902– 6912. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wen_Panacea_Panoramic_and_Controllable_Video_Generation_for_Autonomous_Driving_CVPR_2024_paper.html)]
- **WoVoGen** — J. Lu, Z. Huang, Z. Yang, J. Zhang, and L. Zhang, “Wovogen: World volumeaware diffusion for controllable multi-camera driving scene generation,” in Computer Vision – ECCV 2024. Cham: Springer Nature Switzerland, 2025, pp. 329–345. [[DOI](https://doi.org/10.1007/978-3-031-72989-8_19)]
- **Vista** — S. Gao, J. Yang, L. Chen, K. Chitta, Y. Qiu, A. Geiger, J. Zhang, and H. Li, “Vista: A generalizable driving world model with high fidelity and versatile controllability,” in Advances in Neural Information Processing Systems, vol. 37. Curran Associates, Inc., 2024, pp. 91560–91596. [[DOI](https://doi.org/10.52202/079017-2906)]
- **GenieDrive** — Z. Yang, Z. Liu, Y. Lu, L. Hou, C. Miao, S. Peng, B. Feng, X. Bai, and H. Zhao, “Geniedrive: Towards physics-aware driving world model with 4d occupancy guided video generation,” in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), June 2026, pp. 35680–35690. [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Yang_GenieDrive_Towards_Physics-Aware_Driving_World_Model_with_4D_Occupancy_Guided_CVPR_2026_paper.html)]
- **DriveScape** — W. Wu, X. Guo, W. Tang, T. Huang, C. Wang, and C. Ding, “Drivescape: High-resolution driving video generation by multi-view feature fusion,” in 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025, pp. 17187–17196. [[DOI](https://doi.org/10.1109/CVPR52734.2025.01602)]
- **InstaDrive** — Z. Yang, X. Guo, C. Ding, C. Wang, W. Wu, and Y. Zhang, “Instadrive: Instance-aware driving world models for realistic and consistent video generation,” in 2025 IEEE/CVF International Conference on Computer Vision (ICCV), 2025, pp. 25410–25420. [[DOI](https://doi.org/10.1109/ICCV51701.2025.02357)]
- **DriveDreamer4D** — G. Zhao, C. Ni, X. Wang, Z. Zhu, X. Zhang, Y. Wang, G. Huang, X. Chen, B. Wang, Y. Zhang, W. Mei, and X. Wang, “Drivedreamer4d: World models are effective data machines for 4d driving scene representation,” in 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025, pp. 12015–12026. [[DOI](https://doi.org/10.1109/CVPR52734.2025.01122)]

### Geometric and occupancy world models

- **OccWorld** — W. Zheng, W. Chen, Y. Huang, B. Zhang, Y. Duan, and J. Lu, “Occworld: Learning a 3d occupancy world model for autonomous driving,” in Computer Vision – ECCV 2024. Cham: Springer Nature Switzerland, 2025, pp. 55–72. [[DOI](https://doi.org/10.1007/978-3-031-72624-8_4)] [[Code](https://github.com/wzzheng/OccWorld)]
- **Drive-OccWorld** — Y. Yang, J. Mei, Y. Ma, S. Du, W. Chen, Y. Qian, Y. Feng, and Y. Liu, “Driving in the occupancy world: Vision-centric 4d occupancy forecasting and planning via world models for autonomous driving,” in Proceedings of the AAAI Conference on Artificial Intelligence, vol. 39, no. 9, 2025, pp. 9327–9335. [[DOI](https://doi.org/10.1609/aaai.v39i9.33010)]
- **DOME** — S. Gu, W. Yin, B. Jin, X. Guo, J. Wang, H. Li, Q. Zhang, and X. Long, “Dome: Taming diffusion model into high-fidelity controllable occupancy world model,” 2024. [Online]. Available: https://arxiv.org/abs/2410.10429
- **OccSora** — L. Wang, W. Zheng, Y. Ren, H. Jiang, Z. Cui, H. Yu, and J. Lu, “Occsora: 4d occupancy generation models as world simulators for autonomous driving,” IEEE Transactions on Image Processing, vol. 35, pp. 4947–4960, 2026. [[DOI](https://doi.org/10.1109/TIP.2026.3687468)]
- **DIO** — C. Diehl, Q. Sykora, B. Agro, T. Gilles, S. Casas, and R. Urtasun, “Dio: Decomposable implicit 4d occupancy-flow world model,” in 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025, pp. 27456–27466. [[DOI](https://doi.org/10.1109/CVPR52734.2025.02557)]
- **DynamicCity** — H. Bian, L. Kong, H. Xie, L. Pan, Y. Qiao, and Z. Liu, “Dynamiccity: Large-scale 4d occupancy generation from dynamic scenes,” in International Conference on Learning Representations, vol. 2025, 2025, pp. 40682– 40716. [[Paper](https://proceedings.iclr.cc/paper_files/paper/2025/hash/6506964d22ede4d36adae956e6a9919a-Abstract-Conference.html)]
- **UniScene** — B. Li, J. Guo, H. Liu, Y. Zou, Y. Ding, X. Chen, H. Zhu, F. Tan, C. Zhang, T. Wang, S. Zhou, L. Zhang, X. Qi, H. Zhao, M. Yang, W. Zeng, and X. Jin, “Uniscene: Unified occupancy-centric driving scene generation,” in 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025, pp. 11971–11981. [[DOI](https://doi.org/10.1109/CVPR52734.2025.01118)]
- **DriveWorld** — C. Min, D. Zhao, L. Xiao, J. Zhao, X. Xu, Z. Zhu, L. Jin, J. Li, Y. Guo, J. Xing, L. Jing, Y. Nie, and B. Dai, “Driveworld: 4d pre-trained scene understanding via world models for autonomous driving,” in 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024, pp. 15522–15533. [[DOI](https://doi.org/10.1109/CVPR52733.2024.01470)]
- **Hermes++** — X. Zhou, D. Liang, X. Chen, F. Tan, D. Zhang, H. Zhao, and X. Bai, “Hermes++: Toward a unified driving world model for 3D scene understanding and generation,” IEEE Transactions on Pattern Analysis and Machine Intelligence, pp. 1–18, 2026. [[DOI](https://doi.org/10.1109/TPAMI.2026.3735606)]

### Latent and agent-centric world models

- **MILE** — A. Hu, G. Corrado, N. Griffiths, Z. Murez, C. Gurau, H. Yeo, A. Kendall, R. Cipolla, and J. Shotton, “Model-based imitation learning for urban driving,” in Advances in Neural Information Processing Systems, vol. 35. Curran Associates, Inc., 2022, pp. 20703–20716. [[DOI](https://doi.org/10.52202/068431-1505)]
- **BEVWorld** — Y. Zhang, S. Gong, K. Xiong, X. Ye, X. Li, X. Tan, F. Wang, J. Huang, H. Wu, and H. Wang, “Bevworld: A multimodal world simulator for autonomous driving via scene-level bev latents,” 2025. [Online]. Available: https://arxiv.org/abs/2407.05679
- **TrafficBots** — Z. Zhang, A. Liniger, D. Dai, F. Yu, and L. Van Gool, “Trafficbots: Towards world models for autonomous driving simulation and motion prediction,” in 2023 IEEE International Conference on Robotics and Automation (ICRA), 2023, pp. 1522–1529. [[DOI](https://doi.org/10.1109/ICRA48891.2023.10161243)]
- **SceneDiffuser** — C. M. Jiang, Y. Bai, A. Cornman, C. Davis, X. Huang, H. Jeon, S. Kulshrestha, J. Lambert, S. Li, X. Zhou, C. Fuertes, C. Yuan, M. Tan, Y. Zhou, and D. Anguelov, “Scenediffuser: Efficient and controllable driving simulation initialization and rollout,” in Advances in Neural Information Processing Systems, vol. 37. Curran Associates, Inc., 2024, pp. 55729– 55760. [[DOI](https://doi.org/10.52202/079017-1771)]
- **SceneDiffuser++** — S. Tan, J. Lambert, H. Jeon, S. Kulshrestha, Y. Bai, J. Luo, D. Anguelov, M. Tan, and C. M. Jiang, “Scenediffuser++: City-scale traffic simulation via a generative world model,” in 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025, pp. 1570–1580. [[DOI](https://doi.org/10.1109/CVPR52734.2025.00154)]
- **Think2Drive** — Q. Li, X. Jia, S. Wang, and J. Yan, “Think2Drive: Efficient reinforcement learning by thinking in latent world model for quasi-realistic autonomous driving (in CARLA-v2),” in European Conference on Computer Vision, 2024. [[DOI](https://doi.org/10.1007/978-3-031-72995-9_9)]
- **CarDreamer** — D. Gao, S. Cai, H. Zhou, H. Wang, I. Soltani, and J. Zhang, “Cardreamer: Open-source learning platform for world-model-based autonomous driving,” IEEE Internet of Things Journal, vol. 12, no. 3, pp. 2866–2875, 2025. [[DOI](https://doi.org/10.1109/JIOT.2024.3479088)]
- **OccLLaMA** — J. Wei, S. Yuan, P. Li, Q. Hu, Z. Gan, and W. Ding, “Occllama: An occupancy-language-action generative world model for autonomous driving,” 2024. [Online]. Available: https://arxiv.org/abs/2409.03272

**More detail:** [Generative world modeling collection](data/world-modeling.md).

## Generative Trajectory and Motion Planning in GADMs

<p align="center">
  <img src="assets/manuscript-figures/fig4-trajectory-motion-taxonomy.png" alt="Figure 4: Taxonomy of generative trajectory and motion planning" width="840" />
</p>

*Fig. 4. Taxonomy of generative trajectory and motion planning in GADMs. Multimodal trajectory generation models diverse agent futures through latentvariable, mixture, diffusion, and autoregressive approaches; generative ego-motion planning produces and selects executable trajectories using token-based, diffusion, and flow-based methods; and joint prediction and interactive planning integrates motion forecasting with ego planning and models agent responses to alternative ego decisions.*

### Multimodal trajectory generation

- **DESIRE** — N. Lee, W. Choi, P. Vernaza, C. B. Choy, P. H. S. Torr, and M. Chandraker, “Desire: Distant future prediction in dynamic scenes with interacting agents,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), July 2017. [[DOI](https://doi.org/10.1109/CVPR.2017.233)]
- **Trajectron++** — T. Salzmann, B. Ivanovic, P. Chakravarty, and M. Pavone, “Trajectron++: Dynamically-feasible trajectory forecasting with heterogeneous data,” in Computer Vision – ECCV 2020, A. Vedaldi, H. Bischof, T. Brox, and J.-M. Frahm, Eds. Cham: Springer International Publishing, 2020, pp. 683–700. [[DOI](https://doi.org/10.1007/978-3-030-58523-5_40)]
- **MultiPath++** — B. Varadarajan, A. Hefny, A. Srivastava, K. S. Refaat, N. Nayakanti, A. Cornman, K. Chen, B. Douillard, C. P. Lam, D. Anguelov, and B. Sapp, “Multipath++: Efficient information fusion and trajectory aggregation for behavior prediction,” in 2022 International Conference on Robotics and Automation (ICRA), 2022, pp. 7814–7821. [[DOI](https://doi.org/10.1109/ICRA46639.2022.9812107)]
- **AgentFormer** — Y. Yuan, X. Weng, Y. Ou, and K. M. Kitani, “Agentformer: Agent-aware transformers for socio-temporal multi-agent forecasting,” in Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), October 2021, pp. 9813–9823. [[Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Yuan_AgentFormer_Agent-Aware_Transformers_for_Socio-Temporal_Multi-Agent_Forecasting_ICCV_2021_paper.html)]
- **MotionDiffuser** — C. Jiang, A. Cornman, C. Park, B. Sapp, Y. Zhou, and D. Anguelov, “Motiondiffuser: Controllable multi-agent motion prediction using diffusion,” in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), June 2023, pp. 9644–9653. [[DOI](https://doi.org/10.1109/CVPR52729.2023.00930)]
- **MotionLM** — A. Seff, B. Cera, D. Chen, M. Ng, A. Zhou, N. Nayakanti, K. S. Refaat, R. Al-Rfou, and B. Sapp, “Motionlm: Multi-agent motion forecasting as language modeling,” in 2023 IEEE/CVF International Conference on Computer Vision (ICCV), 2023, pp. 8545–8556. [[DOI](https://doi.org/10.1109/ICCV51070.2023.00788)]
- **ParkDiffusion** — J. Wei, N. V¨odisch, A. Rehr, C. Feist, and A. Valada, “Parkdiffusion: Heterogeneous multi-agent multi-modal trajectory prediction for automated parking using diffusion models,” in 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025, pp. 8297–8304. [[DOI](https://doi.org/10.1109/IROS60139.2025.11246467)]
- **ParkDiffusion++** — J. Wei, A. Rehr, C. Feist, and A. Valada, “Parkdiffusion++: Ego intention conditioned joint multi-agent trajectory prediction for automated parking using diffusion models,” 2026. [Online]. Available: https: //arxiv.org/abs/2602.20923 [[Paper](https://arxiv.org/abs/2602.20923)]
- **Leapfrog Diffusion** — W. Mao, C. Xu, Q. Zhu, S. Chen, and Y. Wang, “Leapfrog diffusion model for stochastic trajectory prediction,” in 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023, pp. 5517–5526. [[DOI](https://doi.org/10.1109/CVPR52729.2023.00534)]
- **Heteroscedastic Diffusion** — G. Capellera, A. Rubio, L. Ferraz, and A. Agudo, “Heteroscedastic diffusion for multi-agent trajectory modeling,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 48, no. 10, pp. 11964–11977, 2026. [[DOI](https://doi.org/10.1109/TPAMI.2026.3692903)]

### Generative ego-motion planning

- **VADv2** — B. Jiang, S. Chen, H. Gao, B. Liao, Q. Zhang, W. Liu, and X. Wang, “Vadv2: End-to-end vectorized autonomous driving via probabilistic planning,” in International Conference on Learning Representations, vol. 2026, 2026, pp. 68886–68900. [[Paper](https://proceedings.iclr.cc/paper_files/paper/2026/hash/70925fe2336ae05917c817d5e4660ab5-Abstract-Conference.html)]
- **Diffusion-ES** — B. Yang, H. Su, N. Gkanatsios, T.-W. Ke, A. Jain, J. Schneider, and K. Fragkiadaki, “Diffusion-es: Gradient-free planning with diffusion for autonomous and instruction-guided driving,” in 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024, pp. 15342– 15353. [[DOI](https://doi.org/10.1109/CVPR52733.2024.01453)]
- **DiffusionDrive** — B. Liao, S. Chen, H. Yin, B. Jiang, C. Wang, S. Yan, X. Zhang, X. Li, Y. Zhang, Q. Zhang, and X. Wang, “Diffusiondrive: Truncated diffusion model for end-to-end autonomous driving,” in 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025, pp. 12037– 12047. [[DOI](https://doi.org/10.1109/CVPR52734.2025.01124)]
- **GoalFlow** — Z. Xing, X. Zhang, Y. Hu, B. Jiang, T. He, Q. Zhang, X. Long, and W. Yin, “Goalflow: Goal-driven flow matching for multimodal trajectories generation in end-to-end autonomous driving,” in 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025, pp. 1602–1611. [[DOI](https://doi.org/10.1109/CVPR52734.2025.00157)]
- **Diffusion Planner** — Y. Zheng, R. Liang, K. Zheng, J. Zheng, L. Mao, J. Li, W. Gu, R. Ai, S. Li, X. Zhan, and J. Liu, “Diffusion-based planning for autonomous driving with flexible guidance,” in International Conference on Learning Representations, vol. 2025, 2025, pp. 37207–37227. [[Paper](https://proceedings.iclr.cc/paper_files/paper/2025/hash/5c0cd43063f087eb32e572d040a19cd2-Abstract-Conference.html)]
- **GenAD** — W. Zheng, R. Song, X. Guo, C. Zhang, and L. Chen, “Genad: Generative end-to-end autonomous driving,” in Computer Vision – ECCV 2024, A. Leonardis, E. Ricci, S. Roth, O. Russakovsky, T. Sattler, and G. Varol, Eds. Cham: Springer Nature Switzerland, 2025, pp. 87–104. [[DOI](https://doi.org/10.1007/978-3-031-73650-6_6)] [[Code](https://github.com/wzzheng/GenAD)]
- **DriveGPT** — X. Huang, E. M. Wolff, P. Vernaza, T. Phan-Minh, H. Chen, D. S. Hayden, M. Edmonds, B. Pierce, X. Chen, P. E. Jacob, X. Chen, C. Tairbekov, P. Agarwal, T. Gao, Y. Chai, and S. Srinivasa, “DriveGPT: Scaling autoregressive behavior models for driving,” in Proceedings of the 42nd International Conference on Machine Learning, ser. Proceedings of Machine Learning Research, A. Singh, M. Fazel, D. Hsu, S. Lacoste-Julien, F. Berkenkamp, T. Maharaj, K. Wagstaff, and J. Zhu, Eds., vol. 267. PMLR, 13–19 Jul 2025, pp. 25908–25921. [[PDF](https://raw.githubusercontent.com/mlresearch/v267/main/assets/huang25ak/huang25ak.pdf)]

### Joint prediction and interactive planning

- **DTPP** — Z. Huang, P. Karkus, B. Ivanovic, Y. Chen, M. Pavone, and C. Lv, “Dtpp: Differentiable joint conditional prediction and cost evaluation for tree policy planning in autonomous driving,” in 2024 IEEE International Conference on Robotics and Automation (ICRA), 2024, pp. 6806–6812. [[DOI](https://doi.org/10.1109/ICRA57147.2024.10610550)]
- **GameFormer** — Z. Huang, H. Liu, and C. Lv, “Gameformer: Game-theoretic modeling and learning of transformer-based interactive prediction and planning for autonomous driving,” in 2023 IEEE/CVF International Conference on Computer Vision (ICCV), 2023, pp. 3880–3890. [[DOI](https://doi.org/10.1109/ICCV51070.2023.00361)]
- **DrivingGPT** — Y. Chen, Y. Wang, and Z. Zhang, “Drivinggpt: Unifying driving world modeling and planning with multi-modal autoregressive transformers,” in Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), October 2025, pp. 26890–26900. [[DOI](https://doi.org/10.1109/ICCV51701.2025.02496)]

**More detail:** [Generative trajectory and motion planning collection](trajectory-motion.md).

## Vision-Language-Action Intelligence in GADMs

<p align="center">
  <img src="assets/manuscript-figures/fig5-vla-taxonomy.png" alt="Figure 5: Taxonomy of vision-language-action intelligence" width="840" />
</p>

*Fig. 5. Taxonomy of VLA intelligence for GADMs. Semantic grounding and reasoning models connect multimodal observations to decision-relevant concepts and geometric representations; language-conditioned action models translate semantic intent into trajectories and controls; and agentic, closed-loop, and cooperative systems integrate memory, tools, planning, and safety verification.*

### Semantic grounding and driving reasoning

- **Talk2BEV** — T. Choudhary, V. Dewangan, S. Chandhok, S. Priyadarshan, A. Jain, A. K. Singh, S. Srivastava, K. M. Jatavallabhula, and K. M. Krishna, “Talk2bev: Language-enhanced bird’s-eye view maps for autonomous driving,” in 2024 IEEE International Conference on Robotics and Automation (ICRA), 2024, pp. 16345–16352. [[DOI](https://doi.org/10.1109/ICRA57147.2024.10611485)]
- **DriveLM** — C. Sima, K. Renz, K. Chitta, L. Chen, H. Zhang, C. Xie, J. Beißwenger, P. Luo, A. Geiger, and H. Li, “Drivelm: Driving with graph visual question answering,” in Computer Vision – ECCV 2024, A. Leonardis, E. Ricci, S. Roth, O. Russakovsky, T. Sattler, and G. Varol, Eds. Cham: Springer Nature Switzerland, 2025, pp. 256–274. [[DOI](https://doi.org/10.1007/978-3-031-72943-0_15)] [[Code](https://github.com/OpenDriveLab/DriveLM)]
- **Reason2Drive** — M. Nie, R. Peng, C. Wang, X. Cai, J. Han, H. Xu, and L. Zhang, “Reason2drive: Towards interpretable and chain-based reasoning for autonomous driving,” in Computer Vision – ECCV 2024, A. Leonardis, E. Ricci, S. Roth, O. Russakovsky, T. Sattler, and G. Varol, Eds. Cham: Springer Nature Switzerland, 2025, pp. 292–308. [[DOI](https://doi.org/10.1007/978-3-031-73347-5_17)]
- **LingoQA** — A.-M. Marcu, L. Chen, J. H¨unermann, A. Karnsund, B. Hanotte, P. Chidananda, S. Nair, V. Badrinarayanan, A. Kendall, J. Shotton, E. Arani, and O. Sinavski, “Lingoqa: Visual question answering for autonomous driving,” in Computer Vision – ECCV 2024, A. Leonardis, E. Ricci, S. Roth, O. Russakovsky, T. Sattler, and G. Varol, Eds. Cham: Springer Nature Switzerland, 2024, pp. 252–269. [[DOI](https://doi.org/10.1007/978-3-031-72980-5_15)] [[Code](https://github.com/wayveai/LingoQA)]
- **GPT-Driver** — J. Mao, Y. Qian, J. Ye, H. Zhao, and Y. Wang, “Gpt-driver: Learning to drive with gpt,” 2023. [Online]. Available: https://arxiv.org/abs/2310.01415
- **DriveVLM** — X. Tian, J. Gu, B. Li, Y. Liu, Y. Wang, Z. Zhao, K. Zhan, P. Jia, X. Lang, and H. Zhao, “Drivevlm: The convergence of autonomous driving and large vision-language models,” 2024. [Online]. Available: https://arxiv.org/abs/2402.12289

### Language-conditioned trajectory and action generation

- **LMDrive** — H. Shao, Y. Hu, L. Wang, G. Song, S. L. Waslander, Y. Liu, and H. Li, “Lmdrive: Closed-loop end-to-end driving with large language models,” in 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024, pp. 15120–15130. [[DOI](https://doi.org/10.1109/CVPR52733.2024.01432)]
- **VLP** — C. Pan, B. Yaman, T. Nesti, A. Mallik, A. G. Allievi, S. Velipasalar, and L. Ren, “Vlp: Vision language planning for autonomous driving,” in 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024, pp. 14760–14769. [[DOI](https://doi.org/10.1109/CVPR52733.2024.01398)]
- **ORION** — H. Fu, D. Zhang, Z. Zhao, J. Cui, D. Liang, C. Zhang, D. Zhang, H. Xie, B. Wang, and X. Bai, “Orion: A holistic end-to-end autonomous driving framework by vision-language instructed action generation,” in 2025 IEEE/CVF International Conference on Computer Vision (ICCV), 2025, pp. 24823–24834. [[DOI](https://doi.org/10.1109/ICCV51701.2025.02302)]
- **AutoVLA** — Z. Zhou, T. Cai, S. Zhao, Y. Zhang, Z. Huang, B. Zhou, and J. Ma, “Autovla: A vision-language-action model for end-to-end autonomous driving with adaptive reasoning and reinforcement fine-tuning,” in Advances in Neural Information Processing Systems, vol. 38, Main Conference. Curran Associates, Inc., 2025, pp. 27920–27956. [[DOI](https://doi.org/10.52202/085713-0942)]
- **OpenDriveVLA** — X. Zhou, X. Han, F. Yang, Y. Ma, V. Tresp, and A. Knoll, “OpenDriveVLA: Towards end-to-end autonomous driving with large vision language action model,” in Proceedings of the AAAI Conference on Artificial Intelligence, vol. 40, no. 16, 2026, pp. 13782–13790. [[DOI](https://doi.org/10.1609/aaai.v40i16.38386)]

### Agentic, closed-loop, and cooperative VLA

- **DiLu** — L. Wen, D. Fu, X. Li, X. Cai, T. Ma, P. Cai, M. Dou, B. Shi, L. He, and Y. Qiao, “Dilu: A knowledge-driven approach to autonomous driving with large language models,” in International Conference on Learning Representations, vol. 2024, 2024, pp. 34503–34522. [[Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/93c936b9e492def9c00782cab79dbc6d-Abstract-Conference.html)]
- **Agent-Driver** — J. Mao, Y. Qian, J. Ye, H. Zhao, and Y. Wang, “Gpt-driver: Learning to drive with gpt,” 2023. [Online]. Available: https://arxiv.org/abs/2310.01415
- **PlanAgent** — Y. Zheng, Z. Xing, Q. Zhang, B. Jin, P. Li, Y. Zheng, Z. Xia, Y. Chen, and D. Zhao, “Planagent: A multimodal large language agent for closedloop vehicle motion planning,” IEEE Transactions on Cognitive and Developmental Systems, vol. 18, no. 4, pp. 1113–1126, 2026. [[DOI](https://doi.org/10.1109/TCDS.2026.3664120)]
- **V2X-VLM** — J. You, Z. Jiang, Z. Huang, H. Shi, R. Gan, K. Wu, X. Cheng, X. Li, and B. Ran, “V2x-vlm: End-to-end v2x cooperative autonomous driving through large vision-language models,” Transportation Research Part C: Emerging Technologies, vol. 183, p. 105457, 2026. [[DOI](https://doi.org/10.1016/j.trc.2025.105457)]
- **OccLLaMA** — J. Wei, S. Yuan, P. Li, Q. Hu, Z. Gan, and W. Ding, “Occllama: An occupancy-language-action generative world model for autonomous driving,” 2024. [Online]. Available: https://arxiv.org/abs/2409.03272
- **DriveWorld-VLA** — F. Jia, L. Liu, Z. Song, C. Jia, H. Ye, X. Hao, and L. Chen, “Driveworld-vla: Unified latent-space world modeling with vision-language-action for autonomous driving,” 2026. [Online]. Available: https://arxiv.org/abs/2602.06521

**More detail:** [Vision-language-action intelligence collection](vla-intelligence.md).

## Functional Convergence Toward Unified GADMs

| Convergence property | Evaluation question |
| :--- | :--- |
| **Action sensitivity** | Do changes in candidate ego actions alter the generated future? |
| **Semantic–geometric consistency** | Are language-level intentions grounded in scene geometry and dynamics? |
| **Consequence-aware action selection** | Do predicted consequences change the chosen action? |
| **Closed-loop adaptation** | Does execution feedback influence the next decision? |

<p align="center">
  <img src="assets/manuscript-figures/fig6-convergence-illustration.png" alt="Figure 6: Action sensitivity and consequence-aware motion selection" width="840" />
</p>

*Fig. 6. Illustration of action sensitivity and consequence-aware motion selection in GADMs, inspired by Drive-WM [8]. A generative world model predicts distinct future outcomes conditioned on alternative ego maneuvers. The imagined consequences guide risk-aware evaluation and selection of a feasible motion, while execution feedback informs subsequent decisions.*

**Illustrative studies:**

- **Drive-WM** — Y. Wang, J. He, L. Fan, H. Li, Y. Chen, and Z. Zhang, “Driving into the future: Multiview visual forecasting and planning with world model for autonomous driving,” in 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024, pp. 14749–14759. [[DOI](https://doi.org/10.1109/CVPR52733.2024.01397)]
- **Drive-OccWorld** — Y. Yang, J. Mei, Y. Ma, S. Du, W. Chen, Y. Qian, Y. Feng, and Y. Liu, “Driving in the occupancy world: Vision-centric 4d occupancy forecasting and planning via world models for autonomous driving,” in Proceedings of the AAAI Conference on Artificial Intelligence, vol. 39, no. 9, 2025, pp. 9327–9335. [[DOI](https://doi.org/10.1609/aaai.v39i9.33010)]
- **DriveVLM** — X. Tian, J. Gu, B. Li, Y. Liu, Y. Wang, Z. Zhao, K. Zhan, P. Jia, X. Lang, and H. Zhao, “Drivevlm: The convergence of autonomous driving and large vision-language models,” 2024. [Online]. Available: https://arxiv.org/abs/2402.12289
- **OccLLaMA** — J. Wei, S. Yuan, P. Li, Q. Hu, Z. Gan, and W. Ding, “Occllama: An occupancy-language-action generative world model for autonomous driving,” 2024. [Online]. Available: https://arxiv.org/abs/2409.03272
- **World4Drive** — Y. Zheng, P. Yang, Z. Xing, Q. Zhang, Y. Zheng, Y. Gao, P. Li, T. Zhang, Z. Xia, P. Jia, X. Lang, and D. Zhao, “World4drive: End-to-end autonomous driving via intention-aware physical latent world model,” in 2025 IEEE/CVF International Conference on Computer Vision (ICCV), 2025, pp. 28632– 28642. [[DOI](https://doi.org/10.1109/ICCV51701.2025.02659)]
- **DrivingGPT** — Y. Chen, Y. Wang, and Z. Zhang, “Drivinggpt: Unifying driving world modeling and planning with multi-modal autoregressive transformers,” in Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), October 2025, pp. 26890–26900. [[DOI](https://doi.org/10.1109/ICCV51701.2025.02496)]
- **DriveWorld-VLA** — F. Jia, L. Liu, Z. Song, C. Jia, H. Ye, X. Hao, and L. Chen, “Driveworld-vla: Unified latent-space world modeling with vision-language-action for autonomous driving,” 2026. [Online]. Available: https://arxiv.org/abs/2602.06521

**More detail:** [Functional convergence collection](convergence.md).

## Datasets, Benchmarks, and Evaluation Metrics

| Resource | Examples or focus | Full list |
| :--- | :--- | :--- |
| **Datasets** | nuScenes, PandaSet, Argoverse 2, nuScenes-QA, Occ3D | [Datasets](datasets.md) |
| **Benchmarks and simulators** | CARLA, nuPlan, NAVSIM, Bench2Drive, DriveArena | [Benchmarks](benchmarks.md) |
| **Metrics** | Generative fidelity, trajectory quality, planning, closed-loop safety | [Evaluation metrics](evaluation-metrics.md) |
| **Last-mile application** | Generative modeling and planning for automated valet parking | [Automated valet parking](automated-valet-parking.md) |



## Contributing

We welcome corrections and additions! Open an [issue](https://github.com/gordonowusuboateng/gadms/issues) or a [pull request](https://github.com/gordonowusuboateng/gadms/pulls) using the conventions in **[CONTRIBUTING.md](CONTRIBUTING.md)**. Please specify the paper title, DOI/arXiv URL, publication venue/year, taxonomy placement, and an official code link where available.

## Citation

Please cite the accompanying survey if it supports your research. **Provisional BibTeX** (replace with the official record once publicly released):

```bibtex
@misc{boateng2026gadms,
  title  = {A Survey on Generative Autonomous Driving Models: Foundations, Taxonomy, and Convergence},
  author = {Boateng, Gordon Owusu and Dong, Qian and Jia, Dongyao and Guo, Xiansheng and Mourad, Azzam and Ansari, Nirwan},
  year   = {2026},
  note   = {Manuscript}
}
```

---


