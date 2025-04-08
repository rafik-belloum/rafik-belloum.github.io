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
    <li style="margin-bottom: 0.7em;"> Our <strong>XAI4U</strong> workshop has been accepted at IHM 2025 (Toulouse). Program and website coming soon.</li>
    <li style="margin-bottom: 0.7em;"> Cezar Filho will present at the Doctoral Colloquium of ACM FAccT 2025.</li>
    <li class="news-hidden" style="margin-bottom: 0.7em;"> I joined the Program Committee of ACM ASSETS 2025.</li>
    <li class="news-hidden" style="margin-bottom: 0.7em;"> New study on progressive disclosure and transparency published at CHIRA.</li>
    <li class="news-hidden" style="margin-bottom: 0.7em;"> Systematic review on trust in XAI under submission.</li>
  </ul>
  <a id="toggle-news" style="cursor: pointer; font-size: 0.85em; display: inline-block; margin-top: 0.3em; color: #555; text-decoration: underline;">See more</a>
</div>
<script>
  document.addEventListener('DOMContentLoaded', function () {
    const toggleBtn = document.getElementById('toggle-news');
    const hiddenItems = document.querySelectorAll('.news-hidden');
    let expanded = false;

  function updateView() {
      hiddenItems.forEach(item => {
        item.style.display = expanded ? 'list-item' : 'none';
      });
      toggleBtn.textContent = expanded ? 'See less' : 'See more';
    }

  toggleBtn.addEventListener('click', function () {
      expanded = !expanded;
      updateView();
    });

   updateView(); // Initialize
  });
</script>











