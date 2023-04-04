---
title: "Highlighting exact matching via marking strategies for ad hoc document ranking with pretrained contextualized language models"
collection: publications
permalink: /publication/2022_exactmatchmarking
excerpt: ''
date: 06 August 2022
venue: 'Information Retrieval Journal 25, 414-460'
# paperurl: 'https://hal.science/hal-03011890/document'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

<a href="https://link.springer.com/article/10.1007/s10791-022-09414-x" target="_blank">
   <button class="btn" ><i class="fa fa-file-download"></i> Download Paper </button>
</a>

---
Pretrained language models (PLMs) exemplified by BERT have proven to be remarkably effective for ad hoc ranking. As opposed to pre-BERT models that required specialized neural components to capture different aspects of query-document relevance, PLMs are solely based on transformers where attention is the only mechanism used for extracting signals from term interactions. Thanks to the transformer’s cross-match attention, BERT was found to be an effective soft matching model. However, exact matching is still an essential signal for assessing the relevance of a document to an information-seeking query aside from semantic matching. We assume that BERT might benefit from explicit exact match cues to better adapt to the relevance classification task. In this work, we explore strategies for integrating exact matching signals using marker tokens to highlight exact term-matches between the query and the document. We find that this simple marking approach significantly improves over the common vanilla baseline. We empirically demonstrate the effectiveness of our approach through exhaustive experiments on three standard ad hoc benchmarks. Results show that explicit exact match cues conveyed by marker tokens are beneficial for BERT and ELECTRA variant to achieve higher or at least comparable performance. Our findings support that traditional information retrieval cues such as exact matching are still valuable for large pretrained contextualized models such as BERT.

<!-- [Download pdf](https://link.springer.com/article/10.1007/s10791-022-09414-x) -->

**Bibtex Citation** 

<pre>
    @article{boualili2022highlighting,
    title={Highlighting exact matching via marking strategies for ad hoc document ranking with pretrained contextualized language models},
    author={Boualili, Lila and Moreno, Jose G and Boughanem, Mohand},
    journal={Information Retrieval Journal},
    volume={25},
    number={4},
    pages={414--460},
    year={2022},
    publisher={Springer}
    }
</pre>

