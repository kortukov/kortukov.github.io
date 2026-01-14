---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a research associate and a PhD candidate at the [XAI group at Fraunhofer HHI](https://www.hhi.fraunhofer.de/en/departments/ai/research-groups/explainable-artificial-intelligence.html), working under the supervision of [Sebastian Lapuschkin](https://iphome.hhi.de/lapuschkin/) and [Wojciech Samek](https://iphome.hhi.de/samek/).
I am excited about understanding what happens inside LLMs with the goal of making them more trustworthy, secure and safe.
More broadly, my research interests revolve around mitigating the [risks associated with increasingly powerful ML systems](https://80000hours.org/problem-profiles/artificial-intelligence/).

Prior to joining Fraunhofer, I did a research master's at the [University of Tübingen](https://uni-tuebingen.de/en/).
I had the pleasure to work at the [STAI group](https://scalabletrustworthyai.github.io/member/joon/), where I investigated  knowledge conflicts in retrieval-augmented LLMs.
Before that, I worked as a student research assistant at the [Decision Making group](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/decision-making/), where I explored the Multi-Armed Bandit problem under distribution shifts and its application to recommender systems.

Before coming to Tübingen, I got my Bachelor degree in Computer Science from [Lomonosov Moscow State University](https://www.msu.ru/en/) in 2020. During and after my studies, I worked for about 2.5 years as a software engineer at [Yandex](https://yandex.com/company).


I am passionate about using technical expertise to help solve the world's most pressing problems.

Latest Publications
======
  {% assign reversed_publications = site.publications | reverse %}
  <ul>{% for post in reversed_publications limit:3 %}
    {% include about-single-publication.html %}
  {% endfor %}</ul>
  <a href="./publications">More publications</a>
