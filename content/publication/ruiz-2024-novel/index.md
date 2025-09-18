---
title: A Novel Approach for Automatic Program Repair Using Round-Trip Translation
  with Large Language Models
authors:
- Fernando Vallecillos Ruiz
- Anastasiia Grishina
- Max Hort
- Leon Moonen
date: '2024-01-01'
publishDate: '2025-09-18T16:13:48.880052Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2401.07994
abstract: 'Research shows that grammatical mistakes in a sentence can be corrected
  by translating it to another language and back using neural machine translation
  with language models. We investigate whether this correction capability of Large
  Language Models (LLMs) extends to Automatic Program Repair (APR). Current generative
  models for APR are pre-trained on source code and fine-tuned for repair. This paper
  proposes bypassing the fine-tuning step and using Round-Trip Translation (RTT):
  translation of code from one programming language to another programming or natural
  language, and back. We hypothesize that RTT with LLMs restores the most commonly
  seen patterns in code during pre-training, i.e., performs a regression toward the
  mean, which removes bugs as they are a form of noise w.r.t. the more frequent, natural,
  bug-free code in the training data. To test this hypothesis, we employ eight recent
  LLMs pre-trained on code, including the latest GPT versions, and four common program
  repair benchmarks in Java. We find that RTT with English as an intermediate language
  repaired 101 of 164 bugs with GPT-4 on the HumanEval-Java dataset. Moreover, 46
  of these are unique bugs that are not repaired by other LLMs fine-tuned for APR.
  Our findings highlight the viability of round-trip translation with LLMs as a technique
  for automated program repair and its potential for research in software engineering.
  Keywords: automated program repair, large language model, machine translation'
tags:
- Computer Science - Computation and Language
- Computer Science - Machine Learning
- Computer Science - Software Engineering
links:
- name: arXiv
  url: https://arxiv.org/abs/2401.07994
---
