# Generative Autonomous Driving Models (GADMs)

### Foundations, Taxonomy, and Convergence

**Companion research repository for:**

> **A Survey on Generative Autonomous Driving Models: Foundations, Taxonomy, and Convergence**  
> Gordon Owusu Boateng, Qian Dong, Dongyao Jia, Xiansheng Guo, Azzam Mourad, and Nirwan Ansari  
> Manuscript, 2026. *Public paper link will be added when available.*

This repository curates research on **Generative Autonomous Driving Models (GADMs)**, focusing on how **generative world modeling**, **generative trajectory and motion planning**, and **vision-language-action (VLA) intelligence** interact in closed-loop autonomous driving. It accompanies our survey and will be updated with relevant research, datasets, benchmarks, and evaluation methods.

> **Core idea:** Combining models in one architecture does not, by itself, establish convergence. Convergence should be evaluated by whether imagined futures and grounded reasoning *measurably improve driving decisions*.

**Full bibliography:** [Browse all references with DOI/arXiv links](references/bibliography.md) · [Download source BibTeX](references/source-references.bib)

## Contents

- [Complete bibliography](references/bibliography.md)
- [Survey overview](#survey-overview)
- [Research taxonomy](#research-taxonomy)
- [Functional convergence](#functional-convergence)
- [Datasets, benchmarks, and metrics](#datasets-benchmarks-and-metrics)
- [Automated valet parking](#automated-valet-parking)
- [Contributing](#contributing)
- [Citation](#citation)

## Survey overview

Generative models enable autonomous driving systems to represent alternative future environments and agent interactions, generate diverse feasible motions, and use multimodal reasoning to guide actions. Our survey brings together three research directions that are often reviewed separately and examines their *functional interfaces*, particularly their contributions to decision-making and safety.

The survey proposes a **conceptual** closed-loop process:

**Observation → Imagination → Reasoning → Motion Generation → Action → Learning**

This is a functional abstraction, not a required architecture implemented by every model.

![Function-oriented taxonomy and conceptual closed-loop GADM framework](assets/taxonomy-framework.png)

*Function-oriented taxonomy and closed-loop process of GADMs (Fig. 2 of the manuscript).*

## Research taxonomy

| Direction | Main research questions | Curated papers |
| --- | --- | --- |
| **Generative world modeling** | How can future driving scenes, geometry, occupancy, and agent interactions be generated—especially under candidate ego actions? | [World modeling](papers/world-modeling.md) |
| **Generative trajectory and motion planning** | How are diverse, dynamically feasible, interaction-aware trajectories generated, evaluated, and selected? | [Trajectory and motion](papers/trajectory-motion.md) |
| **VLA intelligence** | How do multimodal perception and semantic reasoning influence executable driving actions? | [VLA intelligence](papers/vla-intelligence.md) |

Research directions overlap: studies can appear in more than one collection when their capabilities cross functional boundaries.

## Functional convergence

Our survey identifies four complementary properties:

| Property | Central criterion |
| --- | --- |
| **Action sensitivity** | Predicted worlds respond meaningfully to alternative ego actions. |
| **Semantic–geometric consistency** | Language-level intentions are grounded in spatial, temporal, and kinematic constraints. |
| **Consequence-aware action selection** | Predicted outcomes help evaluate and choose candidate motions. |
| **Closed-loop adaptation** | New observations and execution feedback influence subsequent decisions. |

See the [convergence collection](papers/convergence.md) for illustrative methods, interfaces, and evaluation requirements. **Inclusion in a collection does not imply that a paper empirically demonstrates all four properties.**

## Datasets, benchmarks, and metrics

Datasets contain observations and annotations; benchmarks specify tasks, metrics, and evaluation procedures; simulators provide environments in which tasks can be run. We curate these separately:

- [Datasets](resources/datasets.md)
- [Benchmarks and simulation platforms](resources/benchmarks.md)
- [Evaluation metrics](resources/evaluation-metrics.md)

Evaluations should distinguish **generative fidelity**, **decision utility**, **closed-loop safety**, and **computational efficiency**.

## Automated valet parking

[Automated valet parking (AVP)](resources/automated-valet-parking.md) is considered a demanding last-mile application of GADMs, requiring accurate scene geometry, low-speed interaction modeling, tight-clearance motion, and reliable safety verification.

## Contributing

Suggestions and corrections are welcome through GitHub Issues or Pull Requests. Please include the full title, authors, year, venue/preprint status, official publication link, code link if available, and a brief explanation of the method's generated outputs and decision interface. See [CONTRIBUTING.md](CONTRIBUTING.md).

Entries initially draw from the survey manuscript. **Reference numbers refer to that manuscript** and are not yet substitutes for verified external paper links. We will progressively expand and validate these links.

## Citation

If this resource supports your work, please cite the accompanying survey. The following entry is **provisional** until a public preprint or formal publication record is available:

```bibtex
@misc{boateng2026gadms,
  title  = {A Survey on Generative Autonomous Driving Models: Foundations, Taxonomy, and Convergence},
  author = {Boateng, Gordon Owusu and Dong, Qian and Jia, Dongyao and Guo, Xiansheng and Mourad, Azzam and Ansari, Nirwan},
  year   = {2026},
  note   = {Manuscript}
}
```

**Status:** Curated research repository under active development. This is not an official publication announcement or a claim of journal acceptance.
