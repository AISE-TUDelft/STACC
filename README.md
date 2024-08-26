# STACC: a set of SentenceTransformer Assisted Comment Classifiers 📚

![Static Badge](https://img.shields.io/badge/https%3A%2F%2Fhuggingface.co%2Fcollections%2FAISE-TUDelft%2FSTACC-65254a9b4d1fadc125a731dc?style=for-the-badge&logo=huggingface&label=Huggingface&color=%23FF9D00&link=https%3A%2F%2Fhuggingface.co%2Fcollections%2FAISE-TUDelft%2Fstacc-65254a9b4d1fadc125a731dc)
![Static Badge](https://img.shields.io/badge/arXiv-2302.13149-b31b1b?style=for-the-badge&logo=arxiv&logoColor=b31b1b&link=https%3A%2F%2Farxiv.org%2Fabs%2F2302.13149)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=for-the-badge)](https://opensource.org/licenses/Apache-2.0)

This repository contains our notebooks for the train, test and use *STACC*, our submission to the NLBSE'23 [Code Comment Classification tool competition.](https://github.com/nlbse2023/code-comment-classification) 

## Quickstart Guide
Install [SetFit](https://github.com/huggingface/setfit) with the [Optuna](https://github.com/optuna/optuna) backend:

```pip install setfit[optuna]```

Now you're ready to roll 

## Notebook Descriptions:
- 1-Model_selection.ipynb outlines how we selected the base model and tuned the hyperparameters
- 2-Creating_classifiers.ipynb shows how we created the 19 classifiers that make up STACC 📚
- 3-Inference.ipynb shows how you can put STACC to good use by loading a classifier and start predicting. 

## Google Colab
If you wish to run the notebooks in Google Colab we provide the following ready-to-go notebooks:
- [1-Model_selection](https://gist.github.com/aalkaswan/4d8073919af126bf7fc403ce7e716f52)
- [2-Creating_classifiers.ipynb](https://gist.github.com/aalkaswan/75324d94f47137ecddc875c8e3c58e80)
- [3-Inference.ipynb](https://gist.github.com/aalkaswan/a53dc60a8e90aadfe9b64eb91d1ed21f)

## Huggingface Space
We also integrated STACC 📚 in a [Huggingface space.](https://huggingface.co/spaces/AISE-TUDelft/STACC) 

[![image](https://user-images.githubusercontent.com/33690937/217076101-0f892518-768c-4aff-8fa2-67c3d272402b.png)](https://huggingface.co/spaces/AISE-TUDelft/STACC)

## Citation
```
@software{STACC_2023,
  author = {Al-Kaswan, Ali and Izadi, Maliheh and van Deursen, Arie},
  year = {2023},
  title = {STACC: a set of SentenceTransformer Assisted Comment Classifiers},
  url = {https://github.com/AISE-TUDelft/STACC},
  version = {1.0}
```

