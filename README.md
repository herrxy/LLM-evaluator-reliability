# Are LLM-based Evaluators Confusing NLG Quality Criteria?

This is the official repository for our ACL 2024 paper [Are LLM-based Evaluators Confusing NLG Quality Criteria?](https://aclanthology.org/2024.acl-long.516.pdf)

We release the following data and codes used in our work:

- Aspect criteria (including the different descriptions):  `aspect_criteria.json`
- Prompts generated for LLM-based evaluation:  `eval_prompt.py`
- Prompts (including the examples and instructions) and codes of using rules for perturbation constructions:  `Perturbations/`
- Data for experiments (including the refined reference, perturbed texts, and other information):  `data_all.json`
- Experimental results for three LLMs (including the average rating for each test item):  `Eval_results/`

### Citation

```
@inproceedings{hu2024llm,
  title={Are LLM-based Evaluators Confusing NLG Quality Criteria?},
  author={Hu, Xinyu and Gao, Mingqi and Hu, Sen and Zhang, Yang and Chen, Yicheng and Xu, Teng and Wan, Xiaojun},
  booktitle={Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages={9530--9570},
  year={2024}
}
```

