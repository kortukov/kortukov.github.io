---
title: "Strategic Dishonesty Can Undermine AI Safety Evaluations of Frontier LLMs"
type: Conference
collection: publications
permalink: /publication/2026-01-26-aside
excerpt: "LLMs dishonesty breaks jailbreak evaluations but activation probes can catch it."
date: 2026-01-27
paperurl: "https://openreview.net/forum?id=IbDr8xgUMW"
codeurl: "https://github.com/kotekjedi/strategic_dishonesty_mcq"
authors: Alexander Panfilov*, **Evgenii Kortukov***, Kristina Nikolić, Matthias Bethge, Sebastian Lapuschkin, Wojciech Samek, Ameya Prabhu, Maksym Andriushchenko, Jonas Geiping
venue: "ICLR"
bibtex: "@inproceedings{ <br>
    panfilov2026strategic,  <br>
    title={Strategic Dishonesty Can Undermine {AI} Safety Evaluations of Frontier {LLM}s},  <br>
    author={Alexander Panfilov and Evgenii Kortukov and Kristina Nikoli{\'c} and Matthias Bethge and Sebastian Lapuschkin and Wojciech Samek and Ameya Prabhu and Maksym Andriushchenko and Jonas Geiping},  <br>
    booktitle={The Fourteenth International Conference on Learning Representations},  <br>
    year={2026},  <br>
    url={https://openreview.net/forum?id=IbDr8xgUMW}  <br>
}"
---
Large language model (LLM) developers aim for their models to be honest, helpful, and harmless. However, when faced with malicious requests, models are trained to refuse, sacrificing helpfulness. We show that frontier LLMs can develop a preference for \textit{dishonesty} as a new strategy, even when other options are available. Affected models respond to harmful requests with outputs that sound harmful but are crafted to be subtly incorrect or otherwise harmless in practice. This behavior emerges with hard-to-predict variations even within models from the same model family. We find no apparent cause for the propensity to deceive, but show that more capable models are better at executing this strategy. Strategic dishonesty already has a practical impact on safety evaluations, as we show that dishonest responses fool \emph{all} output-based monitors used to detect jailbreaks that we test, rendering benchmark scores unreliable. Further, strategic dishonesty can act like a \emph{honeypot} against malicious users, which noticeably obfuscates prior jailbreak attacks. While output monitors fail, we show that linear probes on internal activations can be used to reliably detect strategic dishonesty. We validate probes on datasets with verifiable outcomes and by using them as steering vectors. Overall, we consider strategic dishonesty as a concrete example of a broader concern that alignment of LLMs is hard to control, especially when helpfulness and harmlessness conflict.
[<i class="fa fa-fw fa-book" aria-hidden="true"></i>Full paper](https://openreview.net/forum?id=IbDr8xgUMW) &nbsp;&nbsp;
[<i class="fa fa-fw fa-globe" aria-hidden="true"></i>Code](https://github.com/kotekjedi/strategic_dishonesty_mcq)