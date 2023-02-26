# Are-LLMs-the-Master-of-All-Trades-Exploring-Domain-Agnostic-Reasoning-Skills-of-LLMs
Evaluating the performance of GPT-3 Davinci and ChatGPT across analogical, spatial and moral reasoning domains.

## TODOs

- [x] Creation of toy analogical and spatial reasoning datasets.
- [ ] Add free-form natural language questions for evaluation analogical reasoning.
- [ ] Add free-form natural language questions for evaluation spatial reasoning.
- [ ] Add free-form natural language questions for evaluation moral reasoning.

## References

If you intend to use the BATS dataset for analogical reasoning please cite the following paper.

```
[1] @inproceedings{gladkova-etal-2016-analogy,
    title = "Analogy-based detection of morphological and semantic relations with word embeddings: what works and what doesn{'}t.",
    author = "Gladkova, Anna  and
      Drozd, Aleksandr  and
      Matsuoka, Satoshi",
    booktitle = "Proceedings of the {NAACL} Student Research Workshop",
    month = jun,
    year = "2016",
    address = "San Diego, California",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/N16-2002",
    doi = "10.18653/v1/N16-2002",
    pages = "8--15",
}
```

The creation of the spatial reasoning dataset draws inspiration from the following paper. Please consider citing them.
```
[2] @inproceedings{mirzaee-etal-2021-spartqa,
    title = "{SPARTQA}: A Textual Question Answering Benchmark for Spatial Reasoning",
    author = "Mirzaee, Roshanak  and
      Rajaby Faghihi, Hossein  and
      Ning, Qiang  and
      Kordjamshidi, Parisa",
    booktitle = "Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.naacl-main.364",
    doi = "10.18653/v1/2021.naacl-main.364",
    pages = "4582--4598",
    abstract = "This paper proposes a question-answering (QA) benchmark for spatial reasoning on natural language text which contains more realistic spatial phenomena not covered by prior work and is challenging for state-of-the-art language models (LM). We propose a distant supervision method to improve on this task. Specifically, we design grammar and reasoning rules to automatically generate a spatial description of visual scenes and corresponding QA pairs. Experiments show that further pretraining LMs on these automatically generated data significantly improves LMs{'} capability on spatial understanding, which in turn helps to better solve two external datasets, bAbI, and boolQ. We hope that this work can foster investigations into more sophisticated models for spatial reasoning over text.",
}
```
