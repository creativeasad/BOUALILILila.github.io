---
title: "Deep learning for information retrieval: studying relevant signals for ad hoc search based on transformer models"
collection: publications
permalink: /publication/2022_thesis
excerpt: ''
date: 23 November 2022
venue: 'theses.fr'
# paperurl: 'https://hal.science/hal-03011890/document'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
<a href="https://theses.hal.science/tel-03969050/file/2022TOU30188a.pdf" target="_blank">
   <button class="btn" ><i class="fa fa-file-download"></i> Download Paper </button>
</a>

---

In the past decade, supervised deep learning models have yielded substantial improvements to many Natural Language Processing (NLP) tasks. Deep neural networks have been used to learn continuous vector representations of text capable of modeling semantics. Several deep learning models were proposed to take advantage of semantic matching, often adapted from those designed for NLP tasks, to meet different Information Retrieval (IR) tasks such as ad~hoc search. However, improvements in IR tasks lagged behind those in similar NLP tasks, despite considerable efforts from the community. Although there are various contributing factors, a critical reason for this ``failure'' comes from the unique characteristics of the ranking task in IR, particularly when compared to the tasks of text matching in NLP. Indeed, in IR, through query-document matching, we try to model the relevance of the document w.r.t the query, i.e., the adequacy of the document's content with respect to the information need formulated in the query. We do not try to calculate the semantic similarity between a few words of the query and a document that may contain tens or even thousands of words. However, this is precisely what most neural models achieve in NLP tasks, learning representations to match two texts. Recently, Pre-trained Language Models (PLMs), of which BERT is the most known instance, are capable of learning representations of words in context and have achieved state-of-the-art results in ad~hoc search with substantial performance leaps. Although PLM-based ranking models are also adapted from similar sentence-matching tasks in NLP, they have proven to be highly effective as opposed to previous attempts. This success can be owed to the heavy pre-training on language modeling objectives and the flexibility of the contextualization process in transformers. Additionally, the availability of large amounts of labeled data for the ranking task enables effective fine-tuning of PLMs. In this thesis, we focus on adapting PLMs to the specific task of ad~hoc ranking. We explore different research directions for building better ranking models: (1) exploring the impact of integrating the traditional exact matching intuition on the ranking effectiveness of PLMs; (2) investigating the role of the contextualization process for ranking to gain insights into what is important for ranking which could motivate more efficient ranking-specific redesigns of PLMs. Regarding the first direction, we propose considering a traditional intuition important for ranking: exact matching, which has been used in IR for decades until very recently in the design of pre-BERT neural models. Instead of building larger neural models or improving their supervision, we take a different path forward by integrating knowledge in the field of IR. We propose a simple yet effective marking strategy that emphasizes exact term matches between the query and the document at the input level by strategically introducing special marker tokens. This approach takes advantage of the flexibility of the transformer architecture in PLMs to integrate additional task-specific intuitions to improve their effectiveness. For the second direction, we explore the contextualization process in PLMs for soft matching in the context of ranking. Because this same contextualization process performed by transformers in PLMs can perform different downstream tasks effectively, we investigate if it can be constrained to a simpler process for the ranking task. We propose distillation from a PLM into simpler carefully-designed modules based on static embeddings and information bottlenecks to analyze the role of the contextualization process for ranking. While the previous research direction integrates more signals into the contextualization process of PLMs (increase effectiveness), the later direction constrains the signals in this process to only what is necessary for ranking (better efficiency/effectiveness trade-offs).

<!-- [Download pdf](https://theses.hal.science/tel-03969050/file/2022TOU30188a.pdf) -->

**Bibtex Citation** 

<pre>
    @phdthesis{boualili2022deep,
    title={Deep learning for information retrieval: studying relevant signals for ad hoc search based on transformer models},
    author={Boualili, Lila},
    year={2022},
    school={Universit{\'e} Paul Sabatier-Toulouse III}
    }
</pre>

