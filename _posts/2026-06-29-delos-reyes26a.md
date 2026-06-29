---
title: Generating synthetic electronic health record data using agent-based models
  to evaluate machine learning robustness under mass casualty incidents
abstract: 'Machine learning (ML) models in healthcare are typically evaluated using
  curated real-world electronic health record (EHR) data. A key limitation of such
  evaluations is that they may fail to assess the robustness of ML models to changes
  in the data at deployment, which is a common issue because EHR data used for ML
  model development cannot capture all such changes. Mass casualty incidents (MCIs)
  caused by disasters are critical instances where this will be an issue, as they
  induce rare, uncertain, and novel changes to routine system conditions. Because
  real-world EHR data from MCIs are often limited or unavailable, assessing ML robustness
  under such conditions before deployment remains challenging. Here, we propose an
  agent-based modelling approach for generating synthetic EHR data to evaluate the
  robustness of ML models under MCI scenarios. We use real-world EHR data to develop
  and calibrate an agent-based model (ABM) of an emergency department (ED) that explicitly
  models patient arrivals, resource capacity, and clinical workflow. By changing these
  system conditions to reflect plausible MCI scenarios, the ED model generates synthetic
  versions of the real-world EHR data that exhibit shifts in system behaviour. Using
  these synthetic data, we test ML models for predicting length of stay. We observed
  consistent declines in recall under MCI conditions relative to baseline system conditions,
  resulting in an increase in the number of patients with prolonged length of stay
  that were missed by the ML models. These results highlight the impact of changes
  in system conditions on patient outcomes, EHR data, and ML model performance. Our
  work establishes ABM-based synthetic EHR data generation as a proactive and systematic
  approach for evaluating the robustness of ML models under MCI or other system conditions
  not captured in real-world EHR data, supporting the safer and more effective deployment
  of ML models in healthcare systems. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: delos-reyes26a
month: 0
tex_title: Generating synthetic electronic health record data using agent-based models
  to evaluate machine learning robustness under mass casualty incidents
firstpage: 134
lastpage: 147
page: 134-147
order: 134
cycles: false
bibtex_author: Delos Reyes, Roben and Capurro, Daniel and Geard, Nicholas
author:
- given: Roben
  family: Delos Reyes
- given: Daniel
  family: Capurro
- given: Nicholas
  family: Geard
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
pdf: https://raw.githubusercontent.com/mlresearch/v333/main/assets/delos-reyes26a/delos-reyes26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
