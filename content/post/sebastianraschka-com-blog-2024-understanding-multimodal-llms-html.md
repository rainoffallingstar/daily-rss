---
title: Understanding Multimodal LLMs
date: '2024-11-03'
linkTitle: https://sebastianraschka.com/blog/2024/understanding-multimodal-llms.html
source: Sebastian Raschka, PhD
description: There has been a lot of new research on the multimodal LLM front, including
  the latest Llama 3.2 vision models, which employ diverse architectural strategies
  to integrate various data types like text and images. For instance, The decoder-only
  method uses a single stack of decoder blocks to process all modalities sequentially.
  On the other hand, cross-attention methods (for example, used in Llama 3.2) involve
  separate encoders for different modalities with a cross-attention layer that allows
  these encoders to interact. This article explains how these different types of multimodal
  LLMs ...
disable_comments: true
---
There has been a lot of new research on the multimodal LLM front, including the latest Llama 3.2 vision models, which employ diverse architectural strategies to integrate various data types like text and images. For instance, The decoder-only method uses a single stack of decoder blocks to process all modalities sequentially. On the other hand, cross-attention methods (for example, used in Llama 3.2) involve separate encoders for different modalities with a cross-attention layer that allows these encoders to interact. This article explains how these different types of multimodal LLMs ...