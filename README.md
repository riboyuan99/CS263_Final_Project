# Evaluate LLM’s performance in reading-comprehension tasks

This project tests LLM understanding of complex reading materials and their ability to answer exam-level questions. 

## Introduction
This project evaluates and compares [Llama-3](https://llama.meta.com/llama3/) and [Mistral](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2)'s ability on reading-comprehension tasks. We used [RACE](https://huggingface.co/datasets/ehovy/race), a dataset for benchmark evaluation of methods in the reading comprehension task, as our dataset.
The experiment is conducted in four scenarios: zero-shot, one-shot, three-shot and fine-tuned. 
## Method

The flowchart below outlines the high-level method for this project.
![Alt Text](https://github.com/riboyuan99/CS263_Final_Project/blob/main/flowchart.png)

Note that accuracy is calculated as a metric to compare two model's performance.

## Result

|  | Zero-shot | One-shot | Three-shot | Fine-tuned |
|----------|----------|----------|----------|----------|
| Llama-3    | 61%   | 64%   | 63%   | 61%   |
| Mistral    | 56%   | 58%   | 60%   | 56%   |

## Work distribution

This project is done by Ribo Yuan, Zhihan Chen, and Hongyi Qi.

Ribo Yuan is in charge of dataset selection and evaluation pipeline. He ensured that the chosen dataset is representative of the task and implemented the necessary steps to evaluate model performance and analyze the results.

Zhihan Chen is in charge of setting up and optimizing workflows for Mis- tral 7B, with a focus on system configuration, integration, and assessing performance.

Hongyi Qi is in charge of set-ting up, integrating, and evaluating the perfor-mance of the latest version of Meta Llama–Llama3.
