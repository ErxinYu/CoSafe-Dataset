# CoSafe: Evaluating Large Language Model Safety in Multi-Turn Dialogue Coreference 

This repository contains the dataset for the EMNLP 2024 paper **CoSafe**: Evaluating Large Language Model Safety in Multi-Turn Dialogue Coreference. Erxin Yu, Jing Li, Ming Liao, Siqi Wang, Gao Zuchen, Fei Mi, Lanqing Hong. [pdf](https://aclanthology.org/2024.emnlp-main.968/)


## Description

As large language models (LLMs) constantly evolve, ensuring their safety remains a critical research issue. Previous red teaming approaches for LLM safety have primarily focused on single prompt attacks or goal hijacking. To the best of our knowledge, we are the first to study LLM safety in multi-turn dialogue coreference. We created a dataset of 1,400 questions across 14 categories, each featuring multi-turn coreference safety attacks. We then conducted detailed evaluations on five widely used open-source LLMs. The results indicated that under multi-turn coreference safety attacks, the highest attack success rate was 56% with the LLaMA2-Chat-7b model, while the lowest was 13.9% with the Mistral-7B-Instruct model. These findings highlight the safety vulnerabilities in LLMs during dialogue coreference interactions.

<img src=intro.png width="600" height="300">


## Citation

If you use CoSafe in your research, please cite our paper:

```markdown
@inproceedings{yu-etal-2024-cosafe,
    title = "{C}o{S}afe: Evaluating Large Language Model Safety in Multi-Turn Dialogue Coreference",
    author = "Yu, Erxin  and
      Li, Jing  and
      Liao, Ming  and
      Wang, Siqi  and
      Zuchen, Gao  and
      Mi, Fei  and
      Hong, Lanqing",
    editor = "Al-Onaizan, Yaser  and
      Bansal, Mohit  and
      Chen, Yun-Nung",
    booktitle = "Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.emnlp-main.968",
    pages = "17494--17508",
}
