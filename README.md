# Word pair similarity datasets in Basque and Spanish
# Overview

This repository contains a word similarity dataset that addresses a gap in psycholinguistic research by providing a comprehensive set of noun pairs with quantifications of semantic similarity. The dataset is based on two well-known Natural Language Processing resources: text corpora and knowledge bases. It aims to facilitate research in lexical processing by incorporating variables that play a significant role in semantic analysis.
Dataset Creation

The creation of this dataset involved three key steps:

- Computation of Psycholinguistic Features: Four important psycholinguistic features were computed for each noun in the dataset. These features include concreteness, frequency, semantic neighborhood density, and phonological neighborhood density.

- Pairing Nouns: Nouns were paired based on the aforementioned psycholinguistic features. This process ensured a controlled variation of variables, providing diverse noun pairs for analysis.

- Word Similarity Measurements: For each noun pair, three types of word similarity measurements were assigned. These measurements were computed using text-based methods, WordNet, and hybrid embeddings.

# Dataset Contents

The dataset included in this repository provides noun pairs' information in Basque and European Spanish. It offers a rich collection of noun pairs with associated psycholinguistic features and word similarity measurements. Researchers can leverage this dataset to explore semantic similarity and lexical processing across languages.
Future Work

While the current dataset focuses on Basque and European Spanish, future work aims to expand its coverage to include additional languages. This extension will broaden the scope of research possibilities and enhance cross-linguistic analysis of word similarity.
Usage

Researchers and developers can utilize this dataset for various purposes, such as:

- Analyzing psycholinguistic features and their impact on word similarity
- Developing and evaluating algorithms for semantic analysis
- Comparing different word similarity measurement techniques
- Investigating cross-linguistic variations in word similarity

# Publications

If you use these datasets please cite the following paper:

```
@article{goikoetxea2023bridging,
    title={Bridging Natural Language Processing and Psycholinguistics: computationally grounded semantic similarity datasets for Basque and Spanish},
    author={Goikoetxea, J and Arantzeta, M and San Martin, I},
    journal={arXiv e-prints},
    pages={arXiv--2304},
    year={2023}
}
```
