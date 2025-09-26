---
title: Sampling Techniques and Parameters in LLM
permalink: sampling-techniques-and-parameters
aliases: sampling-techniques-and-parameters
draft: false
date: 2025-09-25 18:47
tags:
---

A variety of sampling techniques can be employed to determine how the model chooses the next token in a sequence. They are essential for controlling the **quality, creativity, and diversity** of the LLM’s output. The following is a breakdown of different sampling techniques
and their important parameters:

- **Greedy search**: Selects the token with the highest probability at each step. This is the simplest option but it can lead to repetitive and predictable outputs.

- **Random sampling**: Selects the next token according to the probability distribution, where each token is sampled proportionally to its predicted probability. This can produce more surprising and creative text, but also a higher chance of nonsensical output.

- **Temperature sampling**: Adjusts the probability distribution by a temperature parameter. Higher temperatures promote diversity, lower temperatures favor high-probability tokens.

- **Top-K sampling**: Randomly samples from the top K most probable tokens. The value of K controls the degree of randomness.

- **Top-P sampling (nucleus sampling)**:51 Samples from a dynamic subset of tokens whose cumulative probability adds up to P. This allows the model to adapt the number of potential candidates depending on its confidence, favoring more diversity when uncertain and focusing on a smaller set of highly probable words when confident.

- **Best-of-N sampling**: Generates N separate responses and selects the one deemed best according to a predetermined metric (e.g., a reward model or a logical consistency check). This is particularly useful for short snippets or situations where logic and reasoning are key.

