# PyTerrier MSMARCO Document Ranking Task Leaderboard Runs

This repository contains notebooks to reproduce run submissions made to the MSMARCO Document Ranking Task Leaderboard using [PyTerrier](https://github.com/terrier-org/pyterrier).

## Submissions

1. [uogTrBaseDPH](uogTrBaseDPH.ipynb) - DPH applied on a basic index. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cmacdonald/pyterrier-msmarco-document-leaderboard-runs/blob/master/uogTrBaseDPH.ipynb)

2. [uogTrBaseDPHQ](uogTrBaseDPHQ.ipynb) - DPH applied on a basic index, applying Bo1 DFR query expansion. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cmacdonald/pyterrier-msmarco-document-leaderboard-runs/blob/master/uogTrBaseDPHQ.ipynb)

## Performances

Performances obtained from the [MSMARCO Document Ranking task Test Set Leaderboard](https://microsoft.github.io/msmarco/).

| Run Name       | MRR@100 |
| -------------- | ------- | 
| uogTrBaseDPH   | 0.2298  |
| uogTrBaseDPHQ  | 0.2186  |

## Reproducibility

In the spirit of demonstrating and recording reproducibility, if you have been able to reproduce a notebook, please submit a Pull Request for this repository, noting your name on this page.

## Credits

Craig Macdonald, University of Glasgow
