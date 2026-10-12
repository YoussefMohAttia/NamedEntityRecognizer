<div align="center">

# Named Entity Recognizer

### HMM and Maximum Entropy Markov Model Approaches to Sequence Labeling

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)

</div>

## Overview

This repository contains two notebook implementations of named entity recognition. The first builds a bigram Hidden Markov Model with greedy and Viterbi decoding. The second builds a Maximum Entropy Markov Model using logistic regression, contextual features, regular expressions, and prior-tag features.

## Implementations

| Notebook | Model | Main ideas |
| --- | --- | --- |
| `A2P1_Named_Entity_Recognition_HMM.ipynb` | HMM | Maximum-likelihood initial, transition, and emission probabilities; greedy and Viterbi decoding |
| `A2P2_Named_Entity_Recognition_MEMM.ipynb` | MEMM | Logistic-regression classifier; contextual word features, regex features, and prior-tag encoding |

Both notebooks evaluate sequence predictions with F1 score and confusion-matrix utilities.

## Getting Started

```bash
python -m venv .venv
source .venv/bin/activate
pip install jupyter numpy scipy scikit-learn tqdm
jupyter notebook
```

Open the HMM notebook or the MEMM notebook, then run the cells in order. The notebook setup is responsible for loading the corpus used by the assignment.

## Author

**Youssef Mohamed Attia**  
[GitHub](https://github.com/YoussefMohAttia) · [LinkedIn](https://www.linkedin.com/in/youssefmohattia/)
