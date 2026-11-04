# Functional Convergence Toward Unified GADMs

> Curated from *A Survey on Generative Autonomous Driving Models: Foundations, Taxonomy, and Convergence* (manuscript version, October 2026). Reference numbers correspond to the current paper PDF; official publication/code URLs have not yet been independently verified.

The survey distinguishes **functional convergence** from architectural uniformity. Sharing a backbone or representation does not by itself demonstrate that imagined worlds or reasoning change downstream decisions.

| Property | Evaluation question | Illustrative methods | Ref. |
|---|---|---|---|
| Action sensitivity | Do alternative candidate ego actions change predicted futures? | Drive-WM, Drive-OccWorld | [8], [57] |
| Semantic-geometric consistency | Do semantic intentions correspond to feasible geometric motion? | DriveVLM, OccLLaMA | [45], [66] |
| Consequence-aware action selection | Do imagined consequences change candidate motion ranking? | Drive-WM, World4Drive | [8], [101] |
| Closed-loop adaptation | Do execution observations revise later decisions? | DrivingGPT, DriveWorld-VLA | [35], [102] |

Illustrative methods motivate each property but may not fully validate it. Verification needs counterfactual tests, controlled ablations, reactive closed-loop evaluations, and safety checks.
