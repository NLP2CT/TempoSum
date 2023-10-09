# **Can LMs Generalize to Future Data? An Empirical Analysis on Text Summarization**

This repository contains data for the paper [Can LMs Generalize to Future Data? An Empirical Analysis on Text Summarization](https://arxiv.org/abs/2305.01951)

```
@article{cheang2023temposum,
  title={TempoSum: Evaluating the Temporal Generalization of Abstractive Summarization},
  author={Cheang, Chi Seng and Chan, Hou Pong and Wong, Derek F and Liu, Xuebo and Li, Zhaocong and Sun, Yanming and Liu, Shudong and Chao, Lidia S},
  journal={arXiv preprint arXiv:2305.01951},
  year={2023}
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

All datasets are also available at: https://drive.google.com/drive/folders/1BdeTFqoea8GD240h78PgXBO68e53ea9E?usp=sharing
