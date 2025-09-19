---
title: "A Novel Approach for Automatic Program Repair Using Round-Trip Translation with Large Language Models"

# Authors
authors:
  - Fernando Vallecillos Ruiz
  - Anastasiia Grishina
  - Max Hort
  - Leon Moonen

# Author notes (optional)
author_notes: []

date: "2024-01-01T00:00:00Z" # month/year from BibTeX

# Schedule page publish date (when you want it visible on your site, NOT the pub date)
publishDate: "2025-09-18T00:00:00Z" # your urldate, but can be adjusted

# Publication type (CSL standard).
# Since it’s under review in a journal, you may choose either:
# - "paper-conference" if you want it shown as a conference preprint
# - "article-journal" if you want it shown as a journal submission
publication_types: ["article-journal"]

# Publication name
publication: "Under review"

# Optional short name
publication_short: ""

abstract: >
  Research shows that grammatical mistakes in a sentence can be corrected by translating it
  to another language and back using neural machine translation with language models.
  We investigate whether this correction capability of Large Language Models (LLMs) extends
  to Automatic Program Repair (APR). Current generative models for APR are pre-trained on
  source code and fine-tuned for repair. This paper proposes bypassing the fine-tuning step
  and using Round-Trip Translation (RTT): translation of code from one programming language
  to another programming or natural language, and back. We hypothesize that RTT with LLMs
  restores the most commonly seen patterns in code during pre-training, i.e., performs a
  regression toward the mean, which removes bugs as they are a form of noise with respect
  to the more frequent, natural, bug-free code in the training data. To test this hypothesis,
  we employ eight recent LLMs pre-trained on code, including the latest GPT versions, and
  four common program repair benchmarks in Java. We find that RTT with English as an
  intermediate language repaired 101 of 164 bugs with GPT-4 on the HumanEval-Java dataset.
  Moreover, 46 of these are unique bugs that are not repaired by other LLMs fine-tuned for
  APR. Our findings highlight the viability of round-trip translation with LLMs as a
  technique for automated program repair and its potential for research in software
  engineering.

# Optional short summary
summary: "Round-trip translation with LLMs shows strong potential for automatic program repair without fine-tuning."

tags:
  - Automated Program Repair
  - Large Language Models
  - Machine Translation
  - Software Engineering

# Featured on homepage?
featured: true

# Identifiers
hugoblox:
  ids:
    doi: 10.48550/arXiv.2401.07994
    arxiv: 2401.07994

# Links
links:
  - type: pdf
    url: https://arxiv.org/pdf/2401.07994
  - type: code
    url: ""
  - type: dataset
    url: ""
  - type: slides
    url: ""
  - type: video
    url: ""
  - type: source
    url: ""

# Featured image (optional, place `featured.jpg/png` in the same folder)
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com)"
  focal_point: ""
  preview_only: false

# Associated projects (optional)
projects: []

# Slides (optional)
slides: ""
---
