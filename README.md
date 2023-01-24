# STACC
STACC: a set of SentenceTransformer Assisted Comment Classifiers 📚

## Quickstart Guide
First activate the conda environment:

```conda env create -n STACC --file env.yml```

Next clone the original competition repo into this repo to get access to the training data:

```git clone https://github.com/nlbse2023/code-comment-classification.git```

Now you're ready to roll. 

## Notebook Descriptions:
- 1-Model_selection.ipynb outlines how we selected the model and tuned the hyperparameters
- 2-Creating_classifiers.ipynb shows how we created the 19 classifiers that make up STACC 📚
- 3-Inference.ipynb shows how you can put STACC to good use by loading a classifier and start predicting. 
