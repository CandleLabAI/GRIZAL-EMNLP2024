

<div align="center">

[![Paper](https://img.shields.io/badge/paper-arxiv.2310.02835-B31B1B.svg)](https://aclanthology.org/2024.emnlp-main.1061/)


# GRIZAL: Generative Prior-guided Zero-Shot Temporal Action Localization

<div align="left">

Official repository on "GRIZAL: Generative Prior-guided Zero-Shot Temporal Action Localization", accepted in EMNLP 2024

# Setup

We recommend the use of a Linux machine with CUDA compatible GPUs. We provide a Conda environment to configure the required libraries.

Clone the repo with:

```bash
git clone ...
cd T3AL
```

## Conda

The environment can be installed and activated with:

```bash
conda create --name t3al python=3.8
conda activate t3al
pip install -r requirements.txt
```

# Preparing Datasets
We recommend to use pre-extracted by GAFNet or any MultiModal features to accelerate inference. Please download the extracted features for THUMOS14 and ActivityNet-v1.3 datasets from links below. 

In the same folder, you will find captions generated with GPT4o. Given the size of the datasets, we generated caption at 15 fps for THUMOS14 and 1 fps for ActivityNet-v1.3.


# Citation

Please consider citing our paper in your publications if the project helps your research.


```
@inproceedings{susladkar-etal-2024-grizal,
    title = "{GRIZAL}: Generative Prior-guided Zero-Shot Temporal Action Localization",
    author = "Susladkar, Onkar Kishor  and
      Deshmukh, Gayatri Sudhir  and
      Gorade, Vandan  and
      Mittal, Sparsh",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.emnlp-main.1061/",
    doi = "10.18653/v1/2024.emnlp-main.1061",
}

```