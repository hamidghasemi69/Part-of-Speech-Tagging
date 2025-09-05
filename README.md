# Part-of-Speech Tagging

**Implementing a Hidden Markov Model (HMM) for Part-of-Speech (POS) Tagging**

This project demonstrates the implementation of a Hidden Markov Model (HMM) for Part-of-Speech (POS) tagging. The model is trained using a corpus with a universal tagset, and the implementation leverages the Pomegranate library.

---

## Project Overview

- **Objective**: Develop an HMM-based POS tagger to assign grammatical categories (such as noun, verb, adjective) to each word in a given text.
- **Dataset**: Utilizes a corpus with a universal tagset for training and evaluation.
- **Model**: Implements a Hidden Markov Model using the Pomegranate library.
- **Accuracy**: Achieves over 96% tag accuracy with a universal tagset on realistic text corpora.

---

## Repository Structure

- **HMM_Tagger.ipynb** — Jupyter notebook containing the implementation of the HMM-based POS tagger.
- **HMM warmup (optional).ipynb** — Optional notebook for understanding the basics of HMMs.
- **helpers.py** — Helper functions used in the implementation.
- **tags-universal.txt** — File containing the universal tagset used for POS tagging.
- **README.md** — This file.

---

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

`pip install pomegranate`

---

## Running the Notebooks

1. Clone the repository:
   
   `git clone https://github.com/hamidghasemi69/Part-of-Speech-Tagging.git`
   
   `cd Part-of-Speech-Tagging`

2. Open the Jupyter notebooks:
   
   `jupyter notebook`

3. Follow the instructions in the notebooks to understand and implement the HMM-based POS tagger.

   
---

## Results

The implemented HMM-based POS tagger achieves over `96%` accuracy with a universal tagset on realistic text corpora, demonstrating its effectiveness in POS tagging tasks.

---

## Acknowledgements

`Pomegranate Library`: Utilized for implementing the Hidden Markov Model.

`Universal Tagset`: Used for training and evaluating the POS tagger.

---

## Contact & Contributions

- Author: `Hamid Ghasemi`

- Contributions are welcome! Please submit a pull request or raise an issue if you find a bug or have suggestions for improvement.


