# Multiperspective-Answer-Summariser

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)

This repo contains the code for implementation of multiperspective answer summarizer model.  

# Requirements
- torch
- transformers
- python3

# Instructions

The models were trained on the following data [DATASET](https://huggingface.co/datasets/alexfabbri/answersumm)

There are three models - two baseline models and one finetuned model. The code for the models can be found in the `Models` directory. `Report.pdf` contains the information about the results obtained. 

# Folder Structure

The folder structure is as follows:

```
.
├── README.md
├── Report.pdf
├── Models
│   ├── anlp_baseline1.py
│   ├── anlp_baseline2.py
│   └── model.py
└──  Dataset_Paper.pdf
```
