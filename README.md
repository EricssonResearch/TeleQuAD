# TeleQuAD: Telecom Question Answering Dataset Suite

TeleQuAD is a suite of question-answering datasets and models specifically designed for the telecommunications domain.
It provides various QA capabilities including extractive, generative, retrieval-augmented generation (RAG), and tabular structured data question answering.


## Repository Structure

TeleQuAD is organized into the following task-specific subdirectories, each containing the respective dataset:

- [**TeleQuAD-Extractive**](./extractive/v4/): The extractive QA dataset based on technical documentation from 3GPP documents.
- [**TeleQuAD-Tabular**](./tabular/v1/): QA systems for table structured telecom data (specs, configurations, etc.)

## Usage

1. Clone the repository and change to the directory.
2. Choose your QA task type and change to the relevant subdirectory.
3. Follow the task-specific README available for each dataset in the respective folder.

## Contributing to the Dataset

Contributions to the dataset are welcome, please raise a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) and we would review the changes.

## Usage of TeleQuAD in Literature

[1] Holm, Henrik. "[Bidirectional Encoder Representations from Transformers (BERT) for question answering in the telecom domain: Adapting a BERT-like language model to the telecom domain using the electra pre-training approach.](https://www.diva-portal.org/smash/get/diva2%253A1591952/FULLTEXT01.pdf)" (2021).

[2] Gunnarsson, Maria. "[Multi-hop neural question answering in the telecom domain.](https://lup.lub.lu.se/luur/download?func%253DdownloadFile%2526recordOId%253D9063863%2526fileOId%253D9063864))" LTH, Lund University: Lund, Sweden(2021).

[3] Bissessar, Daniel and Alexander Bois. "[Evaluation of methods for question answering data generation: Using large language models.](https://www.diva-portal.org/smash/get/diva2%253A1692087/FULLTEXT01.pdf)" (2022).

[4] Nimara, Doumitrou Daniil, Fitsum Gaim Gebre and Vincent Huang. "[Entity Recognition in Telecommunications using Domain-adapted Language Models.](https://ieeexplore.ieee.org/abstract/document/10624809/)" 2024 IEEE International Conference on Machine Learning for Communication and Networking (ICMLCN 2024).

[5] Karapantelakis, Athanasios, et al. "[Using Large Language Models to understand telecom standards.](https://ieeexplore.ieee.org/abstract/document/10624786)" 2024 IEEE International Conference on Machine Learning for Communication and Networking (ICMLCN 2024).

[6] Roychowdhury, Sujoy, Sumit Soman, HG Ranjani, Avantika Sharma, Neeraj Gunda and Sai Krishna Bala. “[Evaluation of Table Representations to Answer Questions from Tables in Documents : A Case Study using 3GPP Specifications](https://arxiv.org/pdf/2408.17008)”. arXiv preprint arXiv:2408.17008 (2024).

[7] Roychowdhury, Sujoy, Sumit Soman, HG Ranjani, Neeraj Gunda, Vansh Chhabra and Sai Krishna Bala. "[Evaluation of RAG Metrics for Question Answering in the Telecom Domain.](https://openreview.net/forum?id%253DL74piNoToX)" Workshop on Foundation Models in the Wild, International Conference on Machine Learning (ICML 2024). 

[8] Roychowdhury, Sujoy, Sumit Soman, HG Ranjani, Neeraj Gunda, Vansh Chhabra, Subhadip Bandyopadhyay and Sai Krishna Bala. “[Investigating Distributions of Telecom Adapted Sentence Embeddings for Document Retrieval](https://arxiv.org/pdf/2406.12336)”, Workshop on Next-Gen Networks through LLMs, Action Models, and Multi-Agent Systems, International Conference on Communications (ICC 2025).



## Citation

If you use TeleQuAD in your research, please cite:

```bibtex
@article{
  telequad2025,
  title={TeleQuAD: A Suite of Question Answering Datasets for the Telecom Domain},
  author={Fitsum Gebre and Henrik Holm and Maria Gunnarsson and Doumitrou Nimara and Jieqiang Wei and Vincent Huang and Avantika Sharma and H G Ranjani},
  booktitle={Ericsson},
  year={2025}
  }
```

## License

Ericsson (c) 2024-2025

This work is licensed under a [Creative Commons Attribution-NoDerivatives 4.0 International License][cc-by-nd].

[![CC BY-SA 4.0][cc-by-nd-image]][cc-by-nd]

[cc-by-nd]: https://creativecommons.org/licenses/by-nd/4.0/
[cc-by-nd-image]: https://licensebuttons.net/l/by-nd/4.0/88x31.png

## Acknowledgments

TeleQuAD is developed and maintained by Ericsson AB and published for research purposes.
