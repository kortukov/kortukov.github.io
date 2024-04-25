---
title: "Studying Large Language Model Behaviors Under Realistic Knowledge Conflicts"
type: Preprint
collection: publications
permalink: /publication/2024-04-25-realistic-kc
excerpt: 'Studying context-memory knowledge conflicts as they appear in practice: how does factual knowledge influence LLM reading behaviors?'
date: 2024-04-25
paperurl: 'https://arxiv.org/abs/2404.16032'
codeurl: https://github.com/kortukov/realistic_knowledge_conflicts/
authors: '**Evgenii Kortukov**, Alexander Rubinstein, Elisa Nguyen, Seong Joon Oh'
venue: 'arXiv'
bibtex: "@misc{kortukov2024studying, <br>
      title={Studying Large Language Model Behaviors Under Realistic Knowledge Conflicts},  <br>
      author={Evgenii Kortukov and Alexander Rubinstein and Elisa Nguyen and Seong Joon Oh}, <br>
      year={2024}, <br>
      eprint={2404.16032}, <br>
      archivePrefix={arXiv}, <br>
      primaryClass={cs.LG} <br>
}"
---
Retrieval-augmented generation (RAG) mitigates many problems of fully parametric language models, such as temporal degradation, hallucinations, and lack of grounding. In RAG, the model's knowledge can be updated from documents provided in context. This leads to cases of conflict between the model's parametric knowledge and the contextual information, where the model may not always update its knowledge. Previous work studied knowledge conflicts by creating synthetic documents that contradict the model's correct parametric answers. We present a framework for studying knowledge conflicts in a realistic setup. We update incorrect parametric knowledge using real conflicting documents. This reflects how knowledge conflicts arise in practice. In this realistic scenario, we find that knowledge updates fail less often than previously reported. In cases where the models still fail to update their answers, we find a parametric bias: the incorrect parametric answer appearing in context makes the knowledge update likelier to fail. These results suggest that the factual parametric knowledge of LLMs can negatively influence their reading abilities and behaviors.

[<i class="fa fa-fw fa-book" aria-hidden="true"></i>Full paper](https://arxiv.org/abs/2404.16032) &nbsp;&nbsp;
[<i class="fa fa-fw fa-globe" aria-hidden="true"></i>Code](https://github.com/kortukov/realistic_knowledge_conflicts/)