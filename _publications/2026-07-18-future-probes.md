---
title: "Predicting Future Behaviors in Reasoning Models Enables Better Steering"
type: Workshop
collection: publications
permalink: /publication/2026-07-18-future-probes
excerpt: 'Reasoning models represent distributions over future behaviors; probing these lets us steer the outcome by selecting reasoning sentences.'
date: 2026-07-18
paperurl: 'https://arxiv.org/abs/2606.11172'
codeurl: 'https://github.com/kortukov/future_probes'
authors: '**Evgenii Kortukov**, Piotr Komorowski, Florian Klein, Paula Engl, Gabriele Sarti, Seong Joon Oh, Sebastian Lapuschkin, Wojciech Samek'
venue: 'ICML Workshop Mechanistic Interpretability'
bibtex: "@inproceedings{kortukov2026predicting, <br>
    title={Predicting Future Behaviors in Reasoning Models Enables Better Steering}, <br>
    author={Evgenii Kortukov and Piotr Komorowski and Florian Klein and Paula Engl and Gabriele Sarti and Seong Joon Oh and Sebastian Lapuschkin and Wojciech Samek}, <br>
    booktitle={Mechanistic Interpretability Workshop at ICML 2026}, <br>
    year={2026}, <br>
    url={https://openreview.net/forum?id=48NnVTsirb} <br>
}"
---
Interpretability tools that predict and control model behaviors typically rely on contrastive input pairs. This binary data hides the probabilistic nature of language model decision making. During reasoning, LLMs can keep track of multiple behavioral options before committing. We find that these future behavior distributions are reflected in their representations. We can steer the behavioral outcome by choosing the reasoning sentences that maximize the estimated probability of a future behavior. We propose a simple algorithm — Future Probe Controlled Generation (FPCG) — that samples multiple candidate sentences at each reasoning step and selects the one that maximizes the activation of a probe predicting future behavior likelihoods, enabling steering at the text level without modifying activations and with less quality degradation than standard activation steering.

[<i class="fa fa-fw fa-book" aria-hidden="true"></i>Full paper](https://arxiv.org/abs/2606.11172) &nbsp;&nbsp;
[<i class="fa fa-fw fa-globe" aria-hidden="true"></i>Code](https://github.com/kortukov/future_probes) &nbsp;&nbsp;
[<i class="fa fa-fw fa-external-link" aria-hidden="true"></i>OpenReview](https://openreview.net/forum?id=48NnVTsirb) &nbsp;&nbsp;
[<i class="fa fa-fw fa-desktop" aria-hidden="true"></i>Demo](https://behavior-distributions-demo.github.io/)
