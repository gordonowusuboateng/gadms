# Evaluation Metrics for GADMs

> Curated from *A Survey on Generative Autonomous Driving Models: Foundations, Taxonomy, and Convergence* (manuscript version, October 2026). Reference numbers correspond to the current paper PDF; official publication/code URLs have not yet been independently verified.

| Capability | Representative measures |
|---|---|
| Video generation | FID, FVD, view-matching score |
| Occupancy prediction | AP, Soft-IoU |
| Motion forecasting | ADE, FDE, multimodal minimum errors, miss rate, overlap |
| Planning | PDMS, nuPlan planning score, collision, progress, comfort |
| Language and reasoning | Chain-based metrics, Lingo-Judge |
| Language-conditioned execution | Driving Score, Route Completion, Infraction Score |
| Computational cost | Inference latency, denoising steps |
| AVP | Parking success, final pose error, clearance, maneuvers, completion time |

For **functional convergence**, supplement these metrics with action-intervention tests, semantic/geometric constraint checks, candidate-ranking ablations, and closed-loop recovery tests.
