---
title: Mechanistically Guided LoRA Improves Paraphrase Consistency in Medical Vision-Language
  Models
abstract: Medical vision-language models can give different yes or no answers to rephrasings
  of the same clinical question. We study this in MedGemma-4B using PSF-Med, which
  provides paraphrase pairs for systematic consistency evaluation on medical VQA.
  On MIMIC-CXR binary questions ($n=158$), the baseline flip rate is 14.6% and mean
  margin difference is 1.63 logits. We validate that Gemma Scope 2 Sparse Autoencoders
  (SAEs) transfer to MedGemma activations, achieving $R^2 \approx 0.997$ on both medical
  and general text ($n=100$ prompts each, $p<0.001$ for exceeding a 0.95 threshold).
  We then fine-tune Low-Rank Adaptation (LoRA) adapters with a combined loss that
  balances paraphrase consistency with answer accuracy. This combined approach prevents
  mode collapse that occurs with pure consistency training while reducing flip rate
  from 14.6% to 4.4% ($p=0.002$, two-proportion z-test) and margin difference from
  1.63 to 0.33 (79.5% reduction). Accuracy remains stable at 84.2% baseline versus
  82.3% after training (-1.9pp, not significant). On PadChest Balanced ($n=250$),
  flip rate drops from 13.6% to 7.8%, mean margin difference drops from 1.08 to 0.35
  (67.9% reduction), and accuracy increases from 66.4% to 69.4%. A layer-range ablation
  shows that early layers reduce margin differences more than mechanistically selected
  middle layers.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sadanandan26a
month: 0
tex_title: Mechanistically Guided LoRA Improves Paraphrase Consistency in Medical
  Vision-Language Models
firstpage: 703
lastpage: 720
page: 703-720
order: 703
cycles: false
bibtex_author: Sadanandan, Binesh and Behzadan, Vahid
author:
- given: Binesh
  family: Sadanandan
- given: Vahid
  family: Behzadan
date: 2026-06-29
address:
container-title: Proceedings of the 7th Conference on Health, Inference, and Learning
volume: '333'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 6
  - 29
pdf: https://raw.githubusercontent.com/mlresearch/v333/main/assets/sadanandan26a/sadanandan26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
