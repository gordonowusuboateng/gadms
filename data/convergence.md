# Functional Convergence Toward Unified GADMs

> Curated from *A Survey on Generative Autonomous Driving Models: Foundations, Taxonomy, and Convergence* (manuscript version, October 2026). Reference numbers correspond to the current paper PDF; links are generated from the author-supplied BibTeX; no external validation is implied.

The survey distinguishes **functional convergence** from architectural uniformity. Sharing a backbone or representation does not by itself demonstrate that imagined worlds or reasoning change downstream decisions.

| Property | Evaluation question | Illustrative methods | Ref. |
|---|---|---|---|
| Action sensitivity | Do alternative candidate ego actions change predicted futures? | Drive-WM, Drive-OccWorld | [8], [57] |
| Semantic-geometric consistency | Do semantic intentions correspond to feasible geometric motion? | DriveVLM, OccLLaMA | [45], [66] |
| Consequence-aware action selection | Do imagined consequences change candidate motion ranking? | Drive-WM, World4Drive | [8], [101] |
| Closed-loop adaptation | Do execution observations revise later decisions? | DrivingGPT, DriveWorld-VLA | [35], [102] |

Illustrative methods motivate each property but may not fully validate it. Verification needs counterfactual tests, controlled ablations, reactive closed-loop evaluations, and safety checks.

> **Links:** DOI links are preferred where the supplied BibTeX includes a DOI; otherwise, an arXiv or supplied publisher/PDF link is used. Some entries lack an official link in the supplied metadata.

| Study | Year | Venue / status | Publication link |
| --- | --- | --- | --- |
| **Drive-WM** | 2024 | 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) | [DOI](https://doi.org/10.1109/CVPR52733.2024.01397) |
| **Drive-OccWorld** | 2025 | Proceedings of the AAAI Conference on Artificial Intelligence | [DOI](https://doi.org/10.1609/aaai.v39i9.33010) |
| **DriveVLM** | 2024 | Preprint | [Paper](https://arxiv.org/abs/2402.12289) |
| **OccLLaMA** | 2024 | Preprint | [Paper](https://arxiv.org/abs/2409.03272) |
| **World4Drive** | 2025 | 2025 IEEE/CVF International Conference on Computer Vision (ICCV) | [DOI](https://doi.org/10.1109/ICCV51701.2025.02659) |
| **DrivingGPT** | 2025 | 2025 IEEE/CVF International Conference on Computer Vision (ICCV) | [DOI](https://doi.org/10.1109/ICCV51701.2025.02496) |
| **DriveWorld-VLA** | 2026 | Preprint | [Paper](https://arxiv.org/abs/2602.06521) |
| **AutoVLA** | 2025 | Advances in Neural Information Processing Systems | [DOI](https://doi.org/10.52202/085713-0942) |
| **ORION** | 2025 | 2025 IEEE/CVF International Conference on Computer Vision (ICCV) | [DOI](https://doi.org/10.1109/ICCV51701.2025.02302) |
| **GenAD** | 2025 | Computer Vision -- ECCV 2024 | Not provided |
| **PlanAgent** | 2026 | IEEE Transactions on Cognitive and Developmental Systems | [DOI](https://doi.org/10.1109/TCDS.2026.3664120) |

**Classification note:** Categories follow the survey’s functional taxonomy. Inclusion does not establish causal correctness or closed-loop safety.

See [complete supplied bibliography](bibliography.md) for full paper titles and reference keys.
