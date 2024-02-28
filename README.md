# Lightweight Fine-Tuning Project 🚀
This project is all about showing how one can fine-tune models in a simple, straightforward way. Lightweight fine-tuning is one of the most important techniques for adapting foundation models, because it allows you to modify foundation models for your needs without needing substantial computational resources.

## About the Project 📄

In this project, we will bring together all of the essential components of a PyTorch + Hugging Face training and inference process. Specifically, we will:

- Load a pre-trained model and evaluate its performance
- Perform parameter-efficient fine tuning using the pre-trained model
- Perform inference using the fine-tuned model and compare its performance to the original model

## Dataset Description 📊

The dataset consists of two columns:

- tweet: where each line includes the text of a tweet that included emoji (but the emoji has been removed).
- emoji: where each line includes the name of the emoji for the corresponding text in tweet.

## Key Findings 🔍

- **Is Fine-Tuning Necessary?**
- **Predictive Modeling**: We used transformers to train our dataset and make it predict tweets or text by giving certain Emojis suitable for that given text.
- **Analysis On PEFT**

For a detailed look into the analysis, check out this [Jupyter Notebook](https://nbviewer.org/github/DrRuin/Lightweight-Fine-Tuning/blob/main/Lightweight-Fine-Tuning.ipynb)
