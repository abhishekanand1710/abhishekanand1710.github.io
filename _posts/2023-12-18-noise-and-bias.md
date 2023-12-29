---
layout: page
title: "Understanding Relation Between Noise and Bias in Annotated Datasets"
categories:
- projects
tags:
- research
---
Is there a relation between hard-to-learn samples and annotator disagreement for subjective tasks like hate speech classification for language models? Does discarding minority votes lead to a biased perspective? Can multi-annotator models learn valuable information from minority votes that are generally discarded as noise during aggregation? We answer these questions by training standard single ground truth (RoBERTa-base) and multi-annotator (DisCo) models and evaluate prediction confidence using Dataset Cartography.
