---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .topic-llm {
    color: #c95757;
    font-weight: 700;
  }

  .topic-rl {
    color: #9b5aa0;
    font-weight: 700;
  }

  .topic-other {
    font-weight: 700;
  }

  .link-icon {
    width: 1em;
    height: 1em;
    margin: 0 0.25em 0 0.1em;
    vertical-align: -0.12em;
    border-radius: 3px;
  }

  .about-language-toggle {
    display: inline-flex;
    gap: 0.2rem;
    margin-bottom: 1rem;
    padding: 0.18rem;
    border: 1px solid #ccc;
    border-radius: 6px;
  }

  .about-language-button {
    border: 0;
    border-radius: 4px;
    background: transparent;
    color: #494e52;
    cursor: pointer;
    font: inherit;
    padding: 0.25rem 0.65rem;
  }

  .about-language-button.is-active {
    background: #494e52;
    color: #fff;
  }

  .about-language-panel[hidden] {
    display: none;
  }

  .visitor-counter {
    margin-top: 1.5rem;
  }

  .visitor-counter img {
    max-width: 100%;
    border: 0;
  }

  .experience-list { margin: 0 0 1.5rem; }
  .experience-item {
    display: grid;
    grid-template-columns: 64px minmax(0, 1fr);
    gap: 1.1rem;
    padding: 1.25rem 0;
    border-bottom: 1px solid var(--global-border-color, #e6e8eb);
  }
  .experience-item:last-child { border-bottom: 0; }
  .experience-logo {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 64px;
    height: 64px;
    margin-top: 0.15rem;
    border: 1px solid #e6e8eb;
    border-radius: 14px;
    background: #fff;
  }
  .experience-logo img { width: 48px; height: 48px; object-fit: contain; }
  /* Show the colored mark at the left of the high-resolution Seed wordmark. */
  .experience-logo--seed img { width: 48px; height: 42px; object-fit: cover; object-position: left; }
  .experience-heading { display: flex; flex-wrap: wrap; align-items: baseline; justify-content: space-between; gap: 0.25rem 1rem; }
  .page__content .experience-title { margin: 0; font-size: 1.12em; line-height: 1.4; }
  .experience-title a { color: inherit; text-decoration: none; }
  .experience-title a:hover { text-decoration: underline; }
  .experience-dates { color: var(--global-text-color-light, #6b7280); font-size: 0.78em; white-space: nowrap; }
  .page__content .experience-role { margin: 0.15rem 0 0; font-size: 0.85em; font-weight: 600; }
  .page__content .experience-supervision { margin: 0.2rem 0 0; font-size: 0.8em; color: var(--global-text-color-light, #6b7280); }
  .page__content .experience-description { margin-top: 0.5rem; font-size: 0.9em; line-height: 1.6; }
  .page__content .experience-description p { margin: 0; }
  @media (max-width: 480px) {
    .experience-item { grid-template-columns: 48px minmax(0, 1fr); gap: 0.75rem; }
    .experience-logo { width: 48px; height: 48px; border-radius: 10px; }
    .experience-logo img { width: 36px; height: 36px; }
    .experience-logo--seed img { width: 36px; height: 32px; }
    .experience-heading { flex-direction: column; }
  }
</style>

<div class="about-language-toggle" aria-label="About language">
  <button type="button" class="about-language-button is-active" data-about-language-button="en" aria-pressed="true">English</button>
  <button type="button" class="about-language-button" data-about-language-button="zh" aria-pressed="false">中文</button>
</div>

<div class="about-language-panel" data-about-language-panel="en" markdown="1">

I am currently a Ph.D. student in Data Science and Artificial Intelligence at <img class="link-icon" src="https://www.google.com/s2/favicons?domain=polyu.edu.hk&sz=32" alt="">[The Hong Kong Polytechnic University](https://www.polyu.edu.hk/), supervised by Prof. <img class="link-icon" src="https://www.google.com/s2/favicons?domain=scholar.google.com&sz=32" alt="">[KC Tan](https://scholar.google.com/citations?user=LFngSp0AAAAJ&hl=en). Previously, I received my M.S. in Applied Statistics from <img class="link-icon" src="https://www.google.com/s2/favicons?domain=fudan.edu.cn&sz=32" alt="">[Fudan University](https://www.fudan.edu.cn/en/) and my B.S. in Statistics from <img class="link-icon" src="https://www.google.com/s2/favicons?domain=sysu.edu.cn&sz=32" alt="">[Sun Yat-sen University](https://www.sysu.edu.cn/sysuen/).

My research spans <a class="topic-rl" href="#diversity-rl">policy diversity in traditional reinforcement learning</a> and <a class="topic-llm" href="#llm-reasoning">reinforcement learning for LLM reasoning (RL for LLM)</a>. In **policy diversity**, I study how to learn and recover diverse behaviors while maintaining policy quality. I also investigate how diverse opponent populations can improve multi-agent training. ([ICLR 2023](#2023-01-01-quality-similar-diversity), [NeurIPS 2023](#2023-01-02-policy-space-diversity), [ICLR 2025](#2025-01-01-diverse-policies-recovering)) In **RL for LLM**, I study how diversity-aware optimization and self-play can strengthen reasoning, and how to reduce redundant reasoning. I also develop robust evaluation methods to assess whether performance gains reflect genuine reasoning ability. ([NeurIPS 2025 Spotlight](#2025-05-29-diversity-aware-policy-optimization), [VAR-MATH](#2025-05-28-var-math), [ICML 2026](#2026-01-01-slat), NeurIPS 2026)

I am always happy to discuss research ideas around <a class="topic-rl" href="#diversity-rl">RL</a>, <a class="topic-llm" href="#llm-reasoning">LLM Reasoning</a>, <span class="topic-other">Interpretability</span>, and <span class="topic-other">EC + RL</span>. Please feel free to contact me at [nigelyaoj@gmail.com](mailto:nigelyaoj@gmail.com).

</div>

<div class="about-language-panel" data-about-language-panel="zh" markdown="1" hidden>

我目前是[香港理工大学](https://www.polyu.edu.hk/)数据科学与人工智能方向的博士生，导师为 [KC Tan](https://scholar.google.com/citations?user=LFngSp0AAAAJ&hl=en) 教授。此前，我在[复旦大学](https://www.fudan.edu.cn/)获得应用统计硕士学位，在[中山大学](https://www.sysu.edu.cn/)获得统计学理学学士学位。

我的研究从<a class="topic-rl" href="#diversity-rl">传统强化学习中的策略多样性</a>，延伸至<a class="topic-llm" href="#llm-reasoning">面向大语言模型推理的强化学习（RL for LLM）</a>。在**策略多样性**方面，我研究如何在保持策略质量的同时，学习与恢复多样化行为。我也探索如何利用对手种群的多样性，改善多智能体对抗训练。（[ICLR 2023](#2023-01-01-quality-similar-diversity)、[NeurIPS 2023](#2023-01-02-policy-space-diversity)、[ICLR 2025](#2025-01-01-diverse-policies-recovering)）在 **RL for LLM** 方面，我关注如何通过多样性感知优化与自博弈训练提升推理能力，并减少冗余推理。我也研究稳健的评估方法，以检验性能提升是否反映真实推理能力。（[NeurIPS 2025 Spotlight](#2025-05-29-diversity-aware-policy-optimization)、[VAR-MATH](#2025-05-28-var-math)、[ICML 2026](#2026-01-01-slat)、NeurIPS 2026）

欢迎交流 RL、LLM Reasoning、可解释性相关研究问题，也可以通过 [nigelyaoj@gmail.com](mailto:nigelyaoj@gmail.com) 联系我。

</div>

<script>
  (function() {
    var buttons = document.querySelectorAll("[data-about-language-button]");
    var panels = document.querySelectorAll("[data-about-language-panel]");

    function setLanguage(language) {
      buttons.forEach(function(button) {
        var isActive = button.getAttribute("data-about-language-button") === language;
        button.classList.toggle("is-active", isActive);
        button.setAttribute("aria-pressed", isActive ? "true" : "false");
      });

      panels.forEach(function(panel) {
        panel.hidden = panel.getAttribute("data-about-language-panel") !== language;
      });
    }

    buttons.forEach(function(button) {
      button.addEventListener("click", function() {
        setLanguage(button.getAttribute("data-about-language-button"));
      });
    });
  }());
</script>

{% include experience.html %}

<h2 id="selected-publications">Publications</h2>

{% include selected-publications.html show_note=false %}

<h2 id="academic-services">Academic Services</h2>

- Reviewer for NeurIPS, ICLR, and ICML, 2023-present
- Reviewer for AAAI, 2025-present
- Reviewer for IEEE Transactions on Evolutionary Computation (TEVC)
- Reviewer for IEEE Transactions on Cognitive and Developmental Systems (TCDS)

<h2 id="teaching-assistant">Teaching Assistant</h2>

- ENG 2003: Information Technology, The Hong Kong Polytechnic University, Fall 2024
- COMP 6707: Computational Intelligence, The Hong Kong Polytechnic University, Spring 2025
- DSAI 4205: Big Data Analysis, The Hong Kong Polytechnic University, Fall 2025 and Spring 2026

{% comment %}
<h2 id="awards">Awards</h2>

- PolyU Presidential PhD Fellowship Scheme (PPPFS), 2025-2028
- Fudan University Master's First-Class Scholarship, 2020
- National Third Prize and Guangdong First Prize, Chinese Mathematics Competitions, 2018
- Sun Yat-sen University Outstanding Graduate, 2020
- Sun Yat-sen University First-Class Scholarship, 2016-2018
- Samsung Scholarship, 2017-2018
{% endcomment %}

<div class="visitor-counter">
  <a href="https://info.flagcounter.com/YXqG"><img src="https://s01.flagcounter.com/count2/YXqG/bg_FFFFFF/txt_000000/border_CCCCCC/columns_4/maxflags_20/viewers_0/labels_0/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
</div>
