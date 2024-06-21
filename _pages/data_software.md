---
layout: archive
title: "Data & Software"
permalink: /data_software/
author_profile: true
---

## Data
--------------------------

* ### PolyNews

  PolyNews is a multilingual dataset containing news titles in 77 languages and 19 scripts.

  PolyNews aims to provide an easily-accessible, unified and de-duplicated dataset that combines five disparate data sources. It can be used for domain adaptation of language models, language modeling, or text generation in both high-resource and low-resource languages.

  Access the dataset on [HuggingFace](https://huggingface.co/datasets/aiana94/polynews-parallel)

  Paper: [News Without Borders: Domain Adaptation of Multilingual Sentence Embeddings for Cross-lingual News Recommendation](https://arxiv.org/pdf/2406.12634)


* ### PolyNewsParallel

  PolyNews is a multilingual parallel dataset containing news titles 833 language pairs, spanning in 64 languages and 17 scripts.

  PolyNewsParallel aims to provide an easily-accessible, unified and de-duplicated dataset that combines three disparate data sources. It can be used for machine translation or text retrieval in both high-resource and low-resource languages.

  Access the dataset on [HuggingFace](https://huggingface.co/datasets/aiana94/polynews-parallel)

  Paper: [News Without Borders: Domain Adaptation of Multilingual Sentence Embeddings for Cross-lingual News Recommendation](https://arxiv.org/pdf/2406.12634)

* ### xMIND (A Multilingual Dataset for Cross-lingual News Recommendation)

  xMIND is a large-scale multilingual news dataset for multi- and cross-lingual news recommendation. xMIND is derived from the English [MIND](https://msnews.github.io/) dataset using open-source neural machine translation (i.e., NLLB 3.3B). 
  
  xMIND contains 130K news translated into 14 linguistically and geographically diverse languages, with digital footprints of varying sizes. The goal of xMIND is to serve as a benchmark dataset for news recommendation, and to foster broader research into multilingual and cross-lingual news recommendation, for speakers of both high and low-resource languages. 

  Access the dataset on [GitHub](https://github.com/andreeaiana/xMIND)
  
  Paper: [MIND Your Language: A Multilingual Dataset for Cross-lingual News Recommendation](https://arxiv.org/pdf/2403.17876v1.pdf) 


* ### NeMig - A Bilingual News Collection and Knowledge Graph about Migration

  NeMig represents a bilingual news collection and knowledge graphs on the topic of migration. The news corpora in German and English were collected from online media outlets from Germany and the US, respectively. NeMIg contains rich textual and metadata information, sentiment and political orientation annotations, as well as named entities extracted from the articles' content and metadata and linked to Wikidata. The corresponding knowledge graphs (NeMigKG) built from each corpus are expanded with up to two-hop neighbors from Wikidata of the initial set of linked entities.

  Access the dataset on [Zenodo](https://zenodo.org/records/7908392).
  
  Paper: [NeMig - A Bilingual News Collection and Knowledge Graph about Migration](https://ceur-ws.org/Vol-3561/paper3.pdf)

## Models

* ### NaSE (News-adapted Sentence Encoder)

  NaSE is a news-adapted sentence encoder, domain-specialized starting from a pretrained massively multilingual sentence encoder. It leverages the [PolyNews](https://huggingface.co/datasets/aiana94/polynews) and [PolyNewsParallel](https://huggingface.co/datasets/aiana94/polynews-parallel) corpora, and was pretrained using two objectives, namely denoising auto-encoding and sequence-to-sequence machine translation. 

  Paper: [News Without Borders: Domain Adaptation of Multilingual Sentence Embeddings for Cross-lingual News Recommendation](https://arxiv.org/pdf/2406.12634)
  
  Code: [https://github.com/andreeaiana/nase/](https://github.com/andreeaiana/nase/)


## Software
-----------

* ### NewsRecLib: A PyTorch-Lightning Library for Neural News Recommendation
  * Code: [GitHub](https://github.com/andreeaiana/newsreclib)
  * Documentation: [Read the Docs](https://newsreclib.readthedocs.io/en/latest/)
  * Paper: [NewsRecLib: A PyTorch-Lightning Library for Neural News Recommendation](https://aclanthology.org/2023.emnlp-demo.26/)
  
