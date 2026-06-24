# Contributing

This is an open, collaborative manuscript written with [Manubot](https://manubot.org), paired with the companion repository [greenelab/fm-pm-evaluator](https://github.com/greenelab/fm-pm-evaluator).
See [`USAGE.md`](USAGE.md) for how to use Manubot and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) for community norms.
All contributions are evaluated against one guiding question: do biomedical foundation and world models generalize to out-of-distribution tasks well enough to drive personalized medicine?

## Issues

Issues are spaces to discuss models, datasets, tasks, and the structure of the evaluation.
Open one to propose a model to benchmark, a dataset or tranche to add, or a prediction task.

## Pull requests

Contributions operate on a pull request model.
Open a pull request against the default branch; never commit to it directly.
Follow the repository conventions: one sentence per line, and citation by identifier (for example `[@doi:10.1371/journal.pcbi.1007128]`).
Per-fork preview deploys are enabled, so you can view your rendered change before it is merged.

## Peer review

All pull requests undergo peer review, and at least one affirmative review is required before a maintainer merges.
Reviewers should indicate the type of review performed, and may suggest or directly make changes.

## Authorship

Authorship follows the [ICMJE Guidelines](http://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html) and requires a substantial intellectual contribution made through issues and pull requests, not only committed text.
Author order is pre-registered: corresponding authors are listed as designated, and remaining authors are ordered within their contribution category (framework design, prediction submission, experimental validation, analysis, writing or review) by a deterministic randomized procedure fixed before the list is finalized [@doi:10.1371/journal.pcbi.1007128].

Because this is a prospective benchmark, some key contributions, such as providing a data tranche, running an experiment, or submitting locked predictions, never appear as committed text.
Record them in the table below so contributors stay visible at authorship time.

| Name | GitHub | Contribution category | Description | Date |
|:-----|:-------|:----------------------|:------------|:-----|
|      |        |                       |             |      |

## Maintainers

Maintainers hold merge rights and arbitrate contested pull requests; more will be added as contributors join.

- Lucas A. Gillenwater ([@lagillenwater](https://github.com/lagillenwater))
- Casey S. Greene ([@cgreene](https://github.com/cgreene))

## Protecting the prospective design

Predictions must be registered before results are known.
Sealed tranches and unrevealed predictions stay out of the public repository until each reveal, and the project uses [OpenTimestamps](https://opentimestamps.org/) to prove a prediction set existed before the experiment ran.
