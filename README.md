# **Can LMs Generalize to Future Data? An Empirical Analysis on Text Summarization**

This repository contains data for the paper [Can LMs Generalize to Future Data? An Empirical Analysis on Text Summarization](https://arxiv.org/abs/2305.01951)

```
@inproceedings{temposum23,
    title="{Can LMs Generalize to Future Data? An Empirical Analysis on Text Summarization}",
    author = {Chi Seng Cheang and
                  Hou Pong Chan and
                  Derek F. Wong and
                  Xuebo Liu and
                  Zhaocong Li and
                  Yanming Sun and
                  Shudong Liu and
                  Lidia S. Chao},
    booktitle = "Proceedings of the Conference on Empirical Methods in Natural Language Processing ({EMNLP})",
    month = {December},
    year = "2023",
    publisher = "Association for Computational Linguistics",
    }
```


## Getting the data

### Download the datasets from Huggingface Datasets Library 

Run the following commands to to load the datasets from Huggingface Datasets Library.

```python
import datasets

# BBC in-distribution test set
dataset = datasets.load_dataset('chiseng-cheang/TempoSum', 'BBC_in-distribution')

# BBC future test set
dataset = datasets.load_dataset('chiseng-cheang/TempoSum', 'BBC_future')

# CNN in-distribution test set
dataset = datasets.load_dataset('chiseng-cheang/TempoSum', 'CNN_in-distribution')

# CNN future test set
dataset = datasets.load_dataset('chiseng-cheang/TempoSum', 'CNN_future')
```

### Manual Download

All datasets are also available at: [https://drive.google.com/drive/folders/1BdeTFqoea8GD240h78PgXBO68e53ea9E?usp=sharing
](https://drive.google.com/drive/folders/1AWV-fwMKD9lXBwB0_4vV-HuYJE2NvRH4?usp=sharing)https://drive.google.com/drive/folders/1AWV-fwMKD9lXBwB0_4vV-HuYJE2NvRH4?usp=sharing
