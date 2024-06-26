---
title: Using and Finetuning Pretrained Transformers
date: '2024-04-20'
linkTitle: https://sebastianraschka.com/blog/2024/using-finetuning-transformers.html
source: Sebastian Raschka, PhD
description: What are the different ways to use and finetune pretrained large language
  models (LLMs)? The three most common ways to use and finetune pretrained LLMs include
  a feature-based approach, in-context prompting, and updating a subset of the model
  parameters. First, most pretrained LLMs or language transformers can be utilized
  without the need for further finetuning. For instance, we can employ a feature-based
  method to train a new downstream model, such as a linear classifier, using embeddings
  generated by a pretrained transformer. Second, we can showcase examples of a new
  task within the input ...
disable_comments: true
---
What are the different ways to use and finetune pretrained large language models (LLMs)? The three most common ways to use and finetune pretrained LLMs include a feature-based approach, in-context prompting, and updating a subset of the model parameters. First, most pretrained LLMs or language transformers can be utilized without the need for further finetuning. For instance, we can employ a feature-based method to train a new downstream model, such as a linear classifier, using embeddings generated by a pretrained transformer. Second, we can showcase examples of a new task within the input ...