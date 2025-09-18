---
title: 'The Art of Repair: Optimizing Iterative Program Repair with Instruction-Tuned
  Models'
authors:
- Fernando Vallecillos Ruiz
- Max Hort
- Leon Moonen
date: '2025-05-01'
publishDate: '2025-09-18T16:13:48.890719Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2505.02931
abstract: 'Automatic program repair (APR) aims to reduce the manual efforts required
  to identify and fix errors in source code. Before the rise of LLM-based agents,
  a common strategy was to increase the number of generated patches, sometimes to
  the thousands, to achieve better repair results on benchmarks. More recently, self-iterative
  capabilities enabled LLMs to refine patches over multiple rounds guided by feedback.
  However, literature often focuses on many iterations and disregards different numbers
  of outputs. We investigate an APR pipeline that balances these two approaches, the
  generation of multiple outputs and multiple rounds of iteration, while imposing
  a limit of 10 total patches per bug. We apply three SOTA instruction-tuned LLMs
  - DeepSeekCoder-Instruct, Codellama-Instruct, Llama3.1-Instruct - to the APR task.
  We further fine-tune each model on an APR dataset with three sizes (1K, 30K, 65K)
  and two techniques (Full Fine-Tuning and LoRA), allowing us to assess their repair
  capabilities on two APR benchmarks: HumanEval-Java and Defects4J. Our results show
  that by using only a fraction ($<$1%) of the fine-tuning dataset, we can achieve
  improvements of up to 78% in the number of plausible patches generated, challenging
  prior studies that reported limited gains using Full Fine-Tuning. However, we find
  that exceeding certain thresholds leads to diminishing outcomes, likely due to overfitting.
  Moreover, we show that base models greatly benefit from creating patches in an iterative
  fashion rather than generating them all at once. In addition, the benefit of iterative
  strategies becomes more pronounced in complex benchmarks. Even fine-tuned models,
  while benefiting less from iterations, still gain advantages, particularly on complex
  benchmarks. The research underscores the need for balanced APR strategies that combine
  multi-output generation and iterative refinement.'
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Computation and Language
- Computer Science - Machine Learning
- Computer Science - Software Engineering
links:
- name: arXiv
  url: https://arxiv.org/abs/2505.02931
---
