
# Automated Valet Parking (AVP)

Automated Valet Parking (AVP) represents a last-mile extension of autonomous driving and a challenging application for Generative Autonomous Driving Models (GADMs). Unlike conventional road driving, AVP requires precise low-speed maneuvering, interaction-aware trajectory generation, and reliable perception in confined and potentially occluded environments. These characteristics make AVP a valuable testbed for integrating generative world modeling, motion planning, and vision-language-action intelligence.

## Representative Studies

| Method | Focus |
| --- | --- |
| **ParkDiffusion** | Heterogeneous multi-agent trajectory prediction for automated parking |
| **ParkDiffusion++** | Ego-intention-conditioned joint multi-agent trajectory prediction |
| **Automated Valet Parking Trajectory Planning With Dual-Branch Conditional Transformer** | Learning-based trajectory planning for automated valet parking |
| **V2X-VLM** | Cooperative vehicle-infrastructure perception and reasoning relevant to occluded parking environments |

## Evaluation Considerations

Evaluating GADMs in AVP environments requires assessing both maneuvering performance and operational safety. Representative evaluation criteria include:

- **Parking success rate:** Proportion of parking tasks successfully completed.
- **Final parking accuracy:** Position and orientation errors relative to the target parking pose.
- **Collision avoidance and clearance:** Minimum distance to obstacles, vehicles, and parking boundaries.
- **Maneuver efficiency:** Number of forward/reverse maneuvers and total completion time.
- **Safety and robustness:** Collision rate, safety interventions, and performance under occlusion, restricted visibility, and dynamic interactions.

These metrics can help assess whether generative models provide reliable and physically feasible behavior in confined parking environments.

## Publication Links

| Resource / Study | Publication |
| --- | --- |
| **ParkDiffusion** | [DOI](https://doi.org/10.1109/IROS60139.2025.11246467) |
| **ParkDiffusion++** | [arXiv](https://arxiv.org/abs/2602.20923) |
| **Automated Valet Parking Trajectory Planning With Dual-Branch Conditional Transformer** | [DOI](https://doi.org/10.1109/OJITS.2026.3658779) |
| **V2X-VLM** | [DOI](https://doi.org/10.1016/j.trc.2025.105457) |
| **The Future of Parking: A Survey on Automated Valet Parking With an Outlook on High Density Parking** | [DOI](https://doi.org/10.1109/IVS.2017.7995971) |
| **From Smart Parking Towards Autonomous Valet Parking: A Survey, Challenges and Future Works** | [DOI](https://doi.org/10.1016/j.jnca.2020.102935) |

See the [complete bibliography](bibliography.md) for full paper titles and publication details.
