---
title: "A Study of Term-Topic Embeddings for Ranking"
collection: publications
permalink: /publication/2023_termtopic
excerpt: ''
date: 17 March 2023
venue: 'Proceedings of the 45th European Conference on Information Retrieval, ECIR, Dublin, Ireland'
# paperurl: 'https://hal.science/hal-03011890/document'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

<a href="https://link.springer.com/content/pdf/10.1007/978-3-031-28238-6_25" target="_blank">
   <button class="btn" ><i class="fa fa-file-download"></i> Download Paper </button>
</a>

---

Contextualized representations from transformer models have significantly improved the performance of neural ranking models. Late interactions popularized by ColBERT and recently compressed with clustering in ColBERTv2 deliver state-of-the-art quality on many benchmarks. ColBERTv2 uses centroids along with occurrence-specific delta vectors to approximate contextualized embeddings without reducing ranking effectiveness. Analysis of this work suggests that these centroids are “term-topic embeddings”. We examine whether term-topic embeddings can be created in a differentiable end-to-end way, finding that this is a viable strategy for removing the separate clustering step. We investigate the importance of local context for contextualizing these term-topic embeddings, analogous to refining centroids with delta vectors. We find this end-to-end approach is sufficient for matching the effectiveness of the original contextualized embeddings.

<!-- [Download pdf](https://link.springer.com/content/pdf/10.1007/978-3-031-28238-6_25) -->

**Bibtex Citation** 

<pre>
    @inproceedings{boualili2023study,
    title={A Study of Term-Topic Embeddings for Ranking},
    author={Boualili, Lila and Yates, Andrew},
    booktitle={Advances in Information Retrieval: 45th European Conference on Information Retrieval, ECIR 2023, Dublin, Ireland, April 2--6, 2023, Proceedings, Part II},
    pages={359--366},
    year={2023},
    organization={Springer}
    }
</pre>

