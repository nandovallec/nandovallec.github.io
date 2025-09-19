---
title: "The Art of Repair: Optimizing Iterative Program Repair with Instruction-Tuned Models"

# Authors (match to your site’s profiles if available)
authors:
  - Fernando Vallecillos Ruiz
  - Max Hort
  - Leon Moonen

# Optional notes (e.g., equal contribution, corresponding author)
author_notes: []

date: "2025-05-01T00:00:00Z"

# Schedule page publish date (when you want it to appear on the site)
publishDate: "2025-09-19T00:00:00Z"

# Publication type (CSL standard)
publication_types: ["paper-conference"]

# Conference name
publication: "In *International Conference on Evaluation and Assessment in Software Engineering (EASE 2025)*"
publication_short: "In *EASE 2025*"

abstract: |
  Automatic program repair (APR) aims to reduce the manual efforts required to identify and fix errors in source code. Before the rise of LLM-based agents, a common strategy was to increase the number of generated patches, sometimes to the thousands, to achieve better repair results on benchmarks. More recently, self-iterative capabilities enabled LLMs to refine patches over multiple rounds guided by feedback. However, literature often focuses on many iterations and disregards different numbers of outputs. We investigate an APR pipeline that balances these two approaches, the generation of multiple outputs and multiple rounds of iteration, while imposing a limit of 10 total patches per bug. We apply three SOTA instruction-tuned LLMs — DeepSeekCoder-Instruct, Codellama-Instruct, Llama3.1-Instruct — to the APR task. We further fine-tune each model on an APR dataset with three sizes (1K, 30K, 65K) and two techniques (Full Fine-Tuning and LoRA), allowing us to assess their repair capabilities on two APR benchmarks: HumanEval-Java and Defects4J. Our results show that by using only a fraction (<1%) of the fine-tuning dataset, we can achieve improvements of up to 78% in the number of plausible patches generated, challenging prior studies that reported limited gains using Full Fine-Tuning. However, we find that exceeding certain thresholds leads to diminishing outcomes, likely due to overfitting. Moreover, we show that base models greatly benefit from creating patches in an iterative fashion rather than generating them all at once. In addition, the benefit of iterative strategies becomes more pronounced in complex benchmarks. Even fine-tuned models, while benefiting less from iterations, still gain advantages, particularly on complex benchmarks. The research underscores the need for balanced APR strategies that combine multi-output generation and iterative refinement.

# Shortened abstract/summary
summary: "We investigate balanced strategies for automatic program repair combining multi-output generation and iterative refinement with LLMs."

tags:
  - Automatic Program Repair
  - Large Language Models
  - Software Engineering
  - Machine Learning

featured: true

# Identifiers (no DOI yet, fallback to arXiv)
hugoblox:
  ids:
    arxiv: "2505.02931"

# Links
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2505.02931"
  - type: code
    url: "https://zenodo.org/records/15294696"   # Add GitHub repo if available
  # - type: dataset
  #   url: ""   # Add dataset link if available
  # - type: slides
  #   url: ""   # Add conference slides later
  # - type: video
  #   url: ""   # Add recording if published
  # - type: source
  #   url: ""   # Add supplementary repo if needed

# Featured image
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects
projects: []

# Slides (Markdown deck integration)
slides: ""
---
