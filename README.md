# Finetuning Pegasus Large for News Summarization

This project involves fine-tuning Google's **Pegasus Large** model for a specific task of **news summarization**.

## Project Description

The Pegasus Large model has been fine-tuned using the **XSum** dataset, a dataset designed for summarization tasks. The main goal was to improve the model's ability to summarize news articles accurately and concisely.

## Implementation

The implementation was done using **PyTorch** along with the **Hugging Face Transformers** library to obtain and fine-tune the model.

## Evaluation Metrics

To evaluate the model's improvements before and after fine-tuning, **ROUGE** metrics were used:

- **ROUGE-1**: Measures accuracy based on single words.
- **ROUGE-2**: Measures accuracy based on pairs of words.
- **ROUGE-L**: Measures accuracy based on the longest common subsequences.


In the notebook, you will find all the information you need, various examples of article summaries, comparisons with the base model, and human summaries.
