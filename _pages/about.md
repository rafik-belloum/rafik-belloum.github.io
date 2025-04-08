---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

About me
======

Hi, I’m Rafik. I’m a *maître de conférences* (~associate professor) in Computer Science at Université Polytechnique Hauts-de-France and a member of the [LAMIH lab (UMR CNRS 8201)](https://www.uphf.fr/lamih). Before that, I was a postdoc in the [DIVA group](https://diva.telecom-paristech.fr/) at [Télécom Paris](https://www.telecom-paris.fr/). I received my Ph.D. in 2020 at [Inria Bordeaux](https://www.inria.fr/fr/centre-inria-universite-bordeaux) in the [PHOENIX team](http://phoenix.inria.fr/).

My research is in Human-Computer Interaction (HCI), with a focus on making intelligent systems easier to design and use in ways that meet people’s needs. I apply this in domains like smart homes for older adults and explainable AI (XAI).

You can find more details about my [research activities](/research/) and [teaching responsibilities](/teaching/).

### News

<div id="news-box" style="margin-top: 1em; border-left: 4px solid #ccc; padding-left: 1em; font-size: 0.95em;">
  <ul id="news-list" style="list-style: none; padding-left: 0; margin: 0;">
    <li style="margin-bottom: 0.7em;">
      Our XAI4U workshop has been accepted at <a href="https://ihm2025.afihm.org/" target="_blank">IHM 2025</a> (Toulouse). Program coming soon.
    </li>
    <li style="margin-bottom: 0.7em;">
      José Cezar Filho will present our work at <a href="https://conf.researchr.org/home/vlhcc-2024" target="_blank">VL/HCC 2024</a>.
    </li>
    <div id="extra-news" style="overflow: hidden; height: 0; transition: height 0.4s ease;">
      <li style="margin-bottom: 0.7em;">
        Our <a href="https://chi2023.acm.org/" target="_blank">CHI</a> paper received an Honorable Mention.
      </li>
    </div>
  </ul>
  <a id="toggle-news" style="cursor: pointer; font-size: 0.85em; display: inline-block; margin-top: 0.3em; color: #555; text-decoration: underline;">
    See more <span id="chevron">↧</span>
  </a>
</div>

<script>
  document.addEventListener('DOMContentLoaded', () => {
    const toggleBtn = document.getElementById('toggle-news');
    const extraNews = document.getElementById('extra-news');
    const chevron = document.getElementById('chevron');
    let expanded = false;

    toggleBtn.addEventListener('click', () => {
      expanded = !expanded;
      extraNews.style.height = expanded ? extraNews.scrollHeight + "px" : "0";
      toggleBtn.innerHTML = expanded ? 'See less <span id="chevron">↥</span>' : 'See more <span id="chevron">↧</span>';
    });
  });
</script>













