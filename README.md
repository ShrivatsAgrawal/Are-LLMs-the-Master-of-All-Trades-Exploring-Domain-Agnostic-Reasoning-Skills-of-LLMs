# Are-LLMs-the-Master-of-All-Trades-Exploring-Domain-Agnostic-Reasoning-Skills-of-LLMs

## Abstract
The potential of large language models (LLMs) to reason like humans has been a highly contested topic in the field of Machine Learning and Natural Language Processing. However, the reasoning abilities of humans are multifaceted and can be seen in various forms, including analogical, spatial, causal and moral reasoning, among others. This fact raises the question whether LLMs can perform equally well across all these different domains. This research work aims to investigate the performance of LLMs on different reasoning tasks by conducting experiments that directly use or draw inspirations from existing datasets on analogical and spatial reasoning. Additionally, to evaluate the ability of LLMs to reason like human, I evaluate their performance on more open-ended, natural language questions for analogical, spatial and moral reasoning. My findings indicate that LLMs excel at analogical and moral reasoning, yet struggle to perform as proficiently on spatial reasoning tasks. I believe these experiments are crucial for informing the future development and practical development of LLMs, particularly in contexts that require diverse reasoning proficiencies. By shedding light on the reasoning abilities of LLMs, this study aims to push forward our understanding of how they can better emulate the cognitive abilities of humans.

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
