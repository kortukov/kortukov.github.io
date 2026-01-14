---
title: "Studying Large Language Model Behaviors Under Context-Memory Conflicts With Real Documents"
type: Conference
collection: publications
permalink: /publication/2024-04-25-realistic-kc
excerpt: 'Studying context-memory knowledge conflicts as they appear in practice: how does factual knowledge influence LLM reading behaviors?'
date: 2024-04-25
paperurl: 'https://openreview.net/forum?id=xm8zYRfrqE'
codeurl: https://github.com/kortukov/realistic_knowledge_conflicts/
authors: '**Evgenii Kortukov**, Alexander Rubinstein, Elisa Nguyen, Seong Joon Oh'
venue: 'COLM'
bibtex: "@inproceedings{kortukov2024studying, <br>
      title={Studying Large Language Model Behaviors Under Context-Memory Conflicts With Real Documents}, <br>
      author={Evgenii Kortukov and Alexander Rubinstein and Elisa Nguyen and Seong Joon Oh}, <br>
      booktitle={First Conference on Language Modeling}, <br>
      year={2024}, <br>
      url={https://openreview.net/forum?id=xm8zYRfrqE} <br>
}"
---
Retrieval-augmented generation (RAG) mitigates many problems of fully parametric language models, such as temporal degradation, hallucinations, and lack of grounding. In RAG, the model’s knowledge can be updated from documents provided in context. This leads to cases of conflict between the model’s parametric knowledge and the contextual information, where the model may not always update its knowledge. Previous work studied context-memory knowledge conflicts by creating synthetic documents that contradict the model’s correct parametric answers. We present a framework for studying such knowledge conflicts in a realistic setup. We update incorrect parametric knowledge using real conflicting documents. This reflects how knowledge conflicts arise in practice. In this realistic scenario, we find that knowledge updates fail less often than previously reported. In cases where the models still fail to update their answers, we find a parametric bias: the incorrect parametric answer appearing in context makes the knowledge update likelier to fail. These results suggest that the factual parametric knowledge of LLMs can negatively influence their reading abilities and behaviors.

[<i class="fa fa-fw fa-book" aria-hidden="true"></i>Full paper](https://openreview.net/forum?id=xm8zYRfrqE) &nbsp;&nbsp;
[<i class="fa fa-fw fa-globe" aria-hidden="true"></i>Code](https://github.com/kortukov/realistic_knowledge_conflicts/)