# MultiPragEval: Multilingual Pragmatic Evaluation of Large Language Models

This repository contains resources developed for our research, [MultiPragEval: Multilingual Pragmatic Evaluation of Large Language Models](https://arxiv.org/abs/2406.07736), which assesses the pragmatic inference abilities of LLMs across multiple languages.

## Dataset Description

The **MultiPragEval** dataset comprises 1200 question units designed to evaluate the pragmatic understanding of LLMs in English, German, Korean, and Chinese. The dataset is structured around Grice's Cooperative Principle and its four conversational maxims: Quantity, Quality, Relation, and Manner, as well as an additional category for literal interpretation.
## Data Structure

Each data point in `test_suite.csv` is formatted with the following columns:

* **id**: Unique identifier for each test unit.
* **type**: Conversational maxim type (quantity, quality, relation, manner) or literal interpretation.
* **english**: The test unit in English.
* **german**: The test unit in German.
* **korean**: The test unit in Korean.
* **chinese**: The test unit in Chinese.
* **answer**: The correct answer option for the multiple-choice question



## Usage

This dataset is intended for academic and research purposes. It allows for the development, testing, and comparison of LLMs' pragmatic inference abilities across multiple languages.

## Citation

If you utilize the dataset in your research, please cite our paper:

```bibtex
@article{park2024pragmatic,
  title={MultiPragEval: Multilingual Pragmatic Evaluation of Large Language Models},
  author={Park, Dojun and Lee, Jiwoo and Park, Seohyun and Jeong, Hyeyun and Koo, Youngeun and Hwang, Soonha and Park, Seonwoo and Lee, Sungeun},
  journal={arXiv preprint arXiv:2406.07736},
  year={2024},
  url={https://arxiv.org/abs/2406.07736}
}

