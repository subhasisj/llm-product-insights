# Customer Experience Insights from Car Reviews

## Problem Statement
Car manufacturers are constantly looking for ways to improve their products and services. One way to do this is to collect and analyze customer feedback. However, it can be difficult to make sense of large amounts of unstructured data, such as customer car reviews.

## Solution
In this hypothetical scenario of gaining insights from customer reviews, we will use a dataset of car reviews to demonstrate how to extract insights from customer reviews using Large Language Models (LLMs). We will use the [Huggingface Transformers](https://huggingface.co/transformers/) library to extract embeddings from the reviews, and then use [LangChain](https://python.langchain.com/en/latest/index.html) to extract insights from the embeddings.
This notebooks listed below provide a step-by-step guide on how to solve and extract insights from customer online reviews for cars using Large Language Models. We showcase to solve the problem using 3 different approaches:
1.  [01. car-review-cx-analytics-hf-api](./01.%20car-review-cx-analytics-hf-api.ipynb) - Using Huggingface Transformers API
2.  [02. car-review-mpt7b-llm-langchain-local-8bit](./02.%20car-review-mpt7b-llm-langchain-local-8bit.ipynb) - Using LangChain Local 8-bit Quantized MPT-7B LLM
3.  [03. car-review-guanaco7b-insights-qlora-local-4bit](./03.%20car-review-guanaco7b-insights-qlora-local-4bit.ipynb) - Using LangChain Local 4-bit Quantized Guanaco-7B LLM with Qlora

## Benefits
By following the steps in the notebook, you will be able to:
- Extract insights using LLMs and LangChain. The same approach can be used to extract insights from other types of unstructured data, such as customer feedback, product reviews, etc.
- Understand how to optimize the inference of LLMs using LangChain. This is especially useful for deployment on smaller GPUs.


