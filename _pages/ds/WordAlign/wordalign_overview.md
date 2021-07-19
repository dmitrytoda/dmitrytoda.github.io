---
layout: single
permalink: /ds/WordAlign
sidebar:
  - nav: sidebar-ds
---

# Generating word alignments for Russian-Chinese parallel corpus with BERT

Parellel corpus is a collection of texts in two or more languages, aligned on a sentence level. It is a useful tool for linguists studying those languages, as well as for machine learning specialists working with NLP. Most modern machine translation systems are trained using such corpora.

The [Russian-Chinese parallel corpus](https://linghub.ru/rnc_parallel_chinese/search) is a part of [Russian National Corpus of language](https://ruscorpora.ru/new/en/index.html). To our best knowledge, it is the first parallel corpus avaiable online for this language pair.

Having not just sentence-level, but also word-level alignments on a parallel corpus is important for a variety of downstream NLP tasks, such as automatic evaluation of translation outputs, generating translation lexicons or knowledge transfer from high-resource to low-resource languages.

This is an example of what word alignment looks like for a short sentence. If there is an X in the cell, it means corresponding Russian and Chinese words are aligned to each other. Generally speaking, this may be a many-to-many relationship.

![Mapping](/assets/images/wordalign/mapping.png "Mapping")


Example of alignment for the word "carriage" (карета / 车 or 马车) in UI:

![Carriage](/assets/images/wordalign/carriage.png "Carriage")

For this project, I am collaborating with a team of linguists, machine learning engineers and software developers from the [Russian Language Institute](http://www.ruslang.ru/) of Russian Academy of Sciences and [Higher School of Economics](https://www.hse.ru/en/).

**Project overview:**
* Extracting word alignments from BERT and LaBSE's contextualized word embeddings, as suggested in [Word Alignment by Fine-tuning Embeddings on Parallel Corpora](https://arxiv.org/abs/2101.08231) by Dou, Zi-Yi and Neubig, Graham
* Further fine-tuning pretrained BERT and LaBSE on unique Russian-Chinese parallel corpus of 2.3 million words / 779,632 sentence pairs
* Working with a team of Chinese language experts to produce ~500 gold standard sentence pairs, manually aligned on word level, to be used for further fine-tuning in supervised learning mode and as test set
* Putting the model to work in production, highlighting specific word translations in different contexts
* Planned launch date - September 2021
* Preliminary results presented at [International Symposium PaCor 2021](https://www.ehu.eus/en/web/pacor2020/aurkezpena) at the University of Basque Country (see [paper abstract](/ds/WordAlign/PaCor) and [slide deck](/ds/WordAlign/presentation))