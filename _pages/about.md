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
</style>

<div class="about-language-toggle" aria-label="About language">
  <button type="button" class="about-language-button is-active" data-about-language-button="en" aria-pressed="true">English</button>
  <button type="button" class="about-language-button" data-about-language-button="zh" aria-pressed="false">中文</button>
</div>

<div class="about-language-panel" data-about-language-panel="en" markdown="1">

I am currently a Ph.D. student in Data Science and Artificial Intelligence at <img class="link-icon" src="https://www.google.com/s2/favicons?domain=polyu.edu.hk&sz=32" alt="">[The Hong Kong Polytechnic University](https://www.polyu.edu.hk/), supervised by Prof. <img class="link-icon" src="https://www.google.com/s2/favicons?domain=scholar.google.com&sz=32" alt="">[KC Tan](https://scholar.google.com/citations?user=LFngSp0AAAAJ&hl=en). My research lies at the intersection of <a class="topic-rl" href="/#diversity-rl">Reinforcement Learning </a> and <a class="topic-llm" href="/#llm-reasoning">LLM Reasoning</a>. More broadly, I am interested in <span class="topic-other">Interpretability</span>, <span class="topic-other">Evolutionary Computation with RL (EC + RL)</span>, and <span class="topic-other">Model Reuse</span>.

I received my M.S. in Applied Statistics from <img class="link-icon" src="https://www.google.com/s2/favicons?domain=fudan.edu.cn&sz=32" alt="">[Fudan University](https://www.fudan.edu.cn/en/) and my B.S. in Statistics from <img class="link-icon" src="https://www.google.com/s2/favicons?domain=sysu.edu.cn&sz=32" alt="">[Sun Yat-sen University](https://www.sysu.edu.cn/sysuen/). I was fortunate to enjoy research experiences at [Tencent AI Lab](https://ai.tencent.com/ailab/en/index), advised by Dr. <img class="link-icon" src="https://www.google.com/s2/favicons?domain=haobofu.github.io&sz=32" alt="">[Haobo Fu](https://haobofu.github.io/), where I focused on Policy Diversity in RL; at [ByteDance Seed](https://seed.bytedance.com/en/), advised by Xiongcai Luo, where I worked on efficient reasoning and on-policy distillation; and at [Amazon Web Services (AWS)](https://aws.amazon.com/), advised by <img class="link-icon" src="https://www.google.com/s2/favicons?domain=scholar.google.com&sz=32" alt="">[Tong He](https://scholar.google.com/citations?user=hV5D8GYAAAAJ&hl=en) and <img class="link-icon" src="https://www.google.com/s2/favicons?domain=scholar.google.com&sz=32" alt="">[Tianjun Xiao](https://scholar.google.com/citations?user=DaKJ9pAAAAAJ&hl=en), where I worked on video object segmentation.

I am always happy to discuss research ideas around <a class="topic-rl" href="/#diversity-rl">RL</a>, <a class="topic-llm" href="/#llm-reasoning">LLM Reasoning</a>, <span class="topic-other">Interpretability</span>, <span class="topic-other">EC + RL</span>, and <span class="topic-other">Model Reuse</span>. Please feel free to contact me at [nigelyaoj@gmail.com](mailto:nigelyaoj@gmail.com).

</div>

<div class="about-language-panel" data-about-language-panel="zh" markdown="1" hidden>

我目前是[香港理工大学](https://www.polyu.edu.hk/)数据科学与人工智能方向的博士生，由 KC Tan 教授指导。我的研究兴趣主要集中在强化学习（RL）与大语言模型（LLM）推理的交叉方向，也关注可解释性、演化计算与强化学习（EC + RL）以及模型复用。

我硕士毕业于[复旦大学](https://www.fudan.edu.cn/)应用统计专业，本科毕业于[中山大学](https://www.sysu.edu.cn/)统计学专业。关于研究经历，我有幸在 [Tencent AI Lab](https://ai.tencent.com/ailab/en/index) 参与研究，在 Haobo Fu 指导下关注 RL 中的策略多样性；在 [ByteDance Seed](https://seed.bytedance.com/en/) 参与 efficient reasoning 和 on-policy distillation 相关研究，由 Xiongcai Luo 指导；也曾在 [Amazon Web Services（AWS）](https://aws.amazon.com/) 参与 video object segmentation 相关研究，由 [Tong He](https://scholar.google.com/citations?user=hV5D8GYAAAAJ&hl=en) 和 [Tianjun Xiao](https://scholar.google.com/citations?user=DaKJ9pAAAAAJ&hl=en) 指导。

欢迎交流 RL、LLM Reasoning、可解释性、EC + RL 和模型复用相关研究问题，也可以通过 [nigelyaoj@gmail.com](mailto:nigelyaoj@gmail.com) 联系我。

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
