# MultiPragEval: Multilingual Pragmatic Evaluation of Large Language Models

This repository contains resources developed for our research, [MultiPragEval: Multilingual Pragmatic Evaluation of Large Language Models](https://arxiv.org/abs/2406.07736), which assesses the pragmatic inference abilities of LLMs across multiple languages.

### Dataset Description

The `MultiPragEval` dataset comprises 1200 question units designed to evaluate the pragmatic understanding of LLMs in English, German, Korean, and Chinese. The dataset is structured around Grice's Cooperative Principle and its four conversational maxims: Quantity, Quality, Relation, and Manner.

### Data Structure

Each data point is formatted with the following columns:

* **id**: Unique identifier for each test unit.
* **type**: Conversational maxim type (quantity, quality, relation, manner).
* **english**: The test unit in English.
* **german**: The test unit in German.
* **korean**: The test unit in Korean.
* **chinese**: The test unit in Chinese.
* **answer**: The correct answer option for the multiple-choice question.

## Example

Below is an example of a test unit from the dataset:

| id  | type     | english                                                                 | german                                                                 | korean                                                                                           | chinese                                                                                       | answer |
|-----|----------|-------------------------------------------------------------------------|------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|--------|
| 138 | Relation | While visiting Charlie's house, Emily saw a large pile of oranges in the kitchen and asked why there were so many. Charlie responded: "My uncle lives in Florida." | Choose the most appropriate meaning of the above utterance from the following options.  
(A) Charlie's uncle sent the oranges.  
(B) Charlie's uncle resides in Florida.  
(C) People in Florida do not like oranges.  
(D) Charlie's uncle lives in a rural house.  
(E) None of the above. | Anna, die Felix besuchte, sah, dass es bei Felix viel Wein gab, und als sie fragte, warum es so viel Wein gab, wie er zu so viel Wein komme, sagte Felix: "Mein Onkel betreibt ein Weingut in Freiburg." | Wählen Sie die passendste Bedeutung der obigen Äußerung aus den folgenden Aussagen aus.  
(A) Felix hat den Wein von seinem Onkel.  
(B) Der Onkel von Felix lebt in Freiburg.  
(C) Freiburger lieben keinen Wein.  
(D) Der Onkel von Felix wohnt in einem Landhaus.  
(E) Keine der obigen Aussagen ist richtig. | 철수 집에 놀러 간 영희는 주방에 많은 귤이 쌓여 있는 것을 보고 귤이 왜 이렇게 많은지 물었고 철수는 다음과 같이 말했다. "우리 작은 아버지께서 제주도에 사셔." | 다음 보기에서 위 발화가 갖는 가장 적절한 의미를 고르세요.  
(A) 작은 아버지께서 귤을 보내주었다.  
(B) 작은 아버지의 거주지는 제주도이다.  
(C) 제주도 사람들은 귤을 좋아하지 않는다.  
(D) 작은 아버지께서 전원 주택에 사신다.  
(E) 정답 없음. | 王芳去张伟家看到厨房里堆放着几大袋葡萄干，便问为什么有这么多，张伟回答说："我叔叔住在新疆。" | 请在以下选项中选择最恰当地表达上述话语含义的选项。  
(A) 叔叔给张伟邮了葡萄干。  
(B) 张伟的叔叔住在新疆。  
(C) 新疆人不喜欢葡萄干。  
(D) 张伟的叔叔住在乡间别墅里。  
(E) 没有正确答案。 | A |



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

