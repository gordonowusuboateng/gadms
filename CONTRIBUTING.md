# Contributing to Awesome GADMs

We welcome research papers, correction requests, datasets, benchmarks, and code links related to generative autonomous driving models.

## Paper submission format

Please include **method name, full title, venue/year, DOI or arXiv abstract URL, official code repository (if any), and taxonomy category**. Proposed README entry:

```markdown
- **METHOD** — “Full paper title”, *VENUE, YEAR*. [[Paper](https://doi.org/DOI)] [[Code](https://github.com/OWNER/REPO)]
```

If code has not been confirmed, **omit** the Code link. Do not insert placeholder URLs. A DOI landing page is a publication link and may not provide a free full-text PDF. Use an arXiv abstract link where a DOI is not available.

## Categorization

1. **Generative world modeling:** visual/video, geometric/occupancy, latent/agent-centric modeling.
2. **Generative trajectory and motion planning:** agent forecasting, ego-motion generation, joint prediction and planning.
3. **VLA intelligence:** semantic grounding/reasoning, language-conditioned action, agentic/cooperative intelligence.
4. **Functional convergence:** evidence on action sensitivity, grounding consistency, consequence-aware selection, or closed-loop adaptation.

A method may appear in more than one relevant category. **Do not claim safety or functional convergence merely because an architecture combines modalities.**

## How to contribute

1. Open an Issue for corrections or proposed additions, or fork the repository and submit a Pull Request.
2. Edit the relevant README section and/or topical Markdown file; preserve existing working links.
3. Make sure titles, year/venue, DOI and code attribution refer to the same work.
4. Explain what generated output the paper contributes and whether it affects a downstream decision.

Please avoid adding unverified author lists, publication statuses, repositories, or ungrounded performance claims.
