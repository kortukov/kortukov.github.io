---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am an aspiring ML scientist currently on the lookout for PhD positions! I am interested in LLM interpretability and trustworthiness. 
More broadly, my research interests revolve around mitigating the [risks associated with increasingly powerful ML systems](https://80000hours.org/problem-profiles/artificial-intelligence/).

I recently finished a research master's at the [University of Tübingen](https://uni-tuebingen.de/en/).
I had the pleasure to work at [STAI group](https://scalabletrustworthyai.github.io/), supervised by Seong Joon Oh. I did research on knowledge conflicts in retrieval-augmented language models.

Prior to joining the STAI group, I worked as a student research assistant in the [Decision Making group](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/decision-making/) at the University of Tübingen, where I explored the Multi-Armed Bandit problem under distribution shifts and its application to recommender systems.
Before that, I receieved my Bachelor degree in Computer Science from [Lomonosov Moscow State University](https://www.msu.ru/en/) in 2020. During and after my studies, I worked for about 2.5 years as a software engineer at [Yandex](https://yandex.com/company).


I am passionate about using technical expertise to help solve the world's most pressing problems.

Latest Publications
======
  {% assign reversed_publications = site.publications | reverse %}
  <ul>{% for post in reversed_publications limit:3 %}
    {% include about-single-publication.html %}
  {% endfor %}</ul>
  <a href="./publications">More publications</a>
