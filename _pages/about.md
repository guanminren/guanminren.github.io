---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About Me

I am Yanru Guan, an undergraduate student in the [Turing Class](https://cfcs.pku.edu.cn/english/research/turing_program/introduction1/index.htm) at Peking University (EECS’27), currently studying as an exchange student at Carnegie Mellon University's School of Computer Science for Spring 2026. 

My interests lie in the design and analysis of algorithmic systems that involving incentives, information asymmetry, and strategic behavior. I am fortunate to be advised by Prof. [Xiaotie Deng](https://cfcs.pku.edu.cn/english/people/faculty/xiaotiedeng/index.htm) at Peking University. My research to date has primarily focused on auction theory, specifically mechanism design and the design and analysis of auto-bidding algorithms.

I have served as a Teaching Assistant for various courses at both Carnegie Mellon University and Peking University, honored to work alongside Profs [Yang Liu](https://yangpliu.github.io/), [Richard Peng](https://www.cs.cmu.edu/~yangp/) and [Shaofeng Jiang](https://www.shaofengjiang.cn/).

In addition to research, I have been actively involved in competitive programming for over a decade. I achieved **5th place at the ICPC World Finals 2025** and was awarded a Gold Medal and the Best Female Player distinction at the National Olympiad in Informatics (NOI) 2022. 

Here is my [CV](yanru_cv 202604.pdf).

<div style="
  margin-bottom: 10px;
  line-height: 1;
  padding: 0;
">&nbsp;</div>

# News
- *2026.03*: Attended the 2026 ICPC North America Championship and served as a trainer at [North America Programming Camp (NAPC)](https://nac.icpc.global/napc-trainers/).
- *2026.03*: Attended **Northwestern CS Theory Seminar** and presented a talk.
- *2026.03*: &nbsp;🎉🎉 One paper accepted by [**ICLR 2026 Workshop AIMS**](https://alimama-tech.github.io/aims-2026/). 
- *2026.01*: &nbsp;🎉🎉 I am on a one-semester exchange at the **Carnegie Mellon University** School of Computer Science (SCS). 
- *2025.12*: Attended **WINE 2025** at Rutgers University and presented a talk.
- *2025.11*: Honored to be recoginzed as **Rising Star** in Computer Science Research by School of Computer Science, Peking University.

<div style="
  margin-bottom: 5px;
  line-height: 0.5;
  padding: 0;
">&nbsp;</div>

# Educations
- *2026.1 ~ 2026.5(Expected)*, Exchange student, School of Computer Science, **Carnegie Mellon University**. 
- *2023.8 ~ 2027.6(Expected)*, Undergraduate, **Turing Class**, School of Electronic Engineering & Computer Science(EECS), **Peking University** \\
    - **GPA 3.913/4.000**
    - TOEFL 113/120, Speaking 29
<div style="
  margin-bottom: 5px;
  line-height: 0.5;
  padding: 0;
">&nbsp;</div>

# Publications and Manuscripts

- [Selling Data as a Digital Good with Scaling Valuations](https://openreview.net/forum?id=Ew04f1iN1K), Xiaotie Deng, **Yanru Guan**, Ningyuan Li, Zihe Wang, Wu Xin, Jie Zhang, **ICLR 2026 Workshop AIMS**

- [Ex-Ante Truthful Distribution-Reporting Mechanisms](https://arxiv.org/abs/2507.04030)，Xiaotie Deng, **Yanru Guan**, Ningyuan Li, Zihe Wang and Jie Zhang，**WINE 2025**

- [On the Coordination of Value-Maximizing Bidders](https://arxiv.org/abs/2511.04993), **Yanru Guan**, Jiahao Zhang, Zhe Feng and Tao Lin, **Under review**

  <div class="publications">
    <h1>Publications</h1>
    <ol class="bibliography">
      <!-- ══════════════════════════════════════════
           示例条目 1：ArXiv Preprint
           复制此 <li> 并替换内容即可添加更多论文
      ══════════════════════════════════════════ -->
      <li>
        <div class="row">
          <div class="col-sm-2 abbr">
            <abbr class="badge" style="background-color:#CBCBCB">
              <a href="https://arxiv.org/" rel="external nofollow noopener" target="_blank">ArXiv Preprint</a>
            </abbr>
          </div>
          <div class="col-sm-8">
            <div class="title">Paper Title Here</div>

            <div class="author">
              <!-- 用 <em> 包裹第一作者/通讯作者 -->
              <em>Your Name</em>,&nbsp;
              <!-- 其他作者用 <a>，rel 属性保持不变 -->
              <a href="https://example.com/" rel="external nofollow noopener" target="_blank">Co-author Name</a>,&nbsp;
              <!-- &nbsp; 后接下一个作者，末尾用 &nbsp;and&nbsp; -->
              and&nbsp;<a href="https://example2.com/" rel="external nofollow noopener" target="_blank">Another Author</a>
            </div>

            <div class="periodical">
              <em>arXiv preprint arXiv:XXXX.XXXXX</em>, 2026
            </div>

            <!-- 可选：额外说明（奖项、报告等），直接写 HTML -->
            <!-- <div class="periodical">
              <b style="color:Red">Best Paper Award</b>
            </div> -->

            <div class="links">
              <a href="http://arxiv.org/abs/XXXX" class="btn btn-sm z-depth-0" role="button"
                 rel="external nofollow noopener" target="_blank">arXiv</a>
              <!-- 继续添加 PDF / Slides / Poster / Video 等按钮 -->
              <a href="./assets/pdf/paper.pdf" class="btn btn-sm z-depth-0" role="button">PDF</a>
              <a href="./assets/pdf/slides.pdf" class="btn btn-sm z-depth-0" role="button">Slides</a>
            </div>

            <!-- 可选：Altmetric / Dimensions 徽章（需外网加载） -->
            <!--
            <div class="badges">
              <span class="altmetric-embed"
                    data-altmetric-id=""
                    data-hide-no-mentions="true"
                    data-hide-less-than="15"
                    data-badge-type="2"
                    data-badge-popover="right"
                    data-uuid="YOUR-UUID"></span>
              <span class="__dimensions_badge_embed__"
                    data-pmid=""
                    data-hide-zero-citations="true"
                    data-style="small_rectangle"
                    data-legend="hover-right"
                    style="margin-bottom: 6px;"></span>
            </div>
            -->

            <!-- 可选：点击展开的 Abstract / Notes（需配合 JS） -->
            <!--
            <div class="hidden abstract" onclick="this.classList.toggle('open')">
              <p>Abstract text goes here...</p>
            </div>
            -->
          </div>
        </div>
      </li>
   </ol>
  </div>

<div style="
  margin-bottom: 5px;
  line-height: 0.5;
  padding: 0;
">&nbsp;</div>

# Research Experiences
- *2023.10 ~ Present*, **Research Intern at DaGAME Lab, Peking University** \\
  - Advised by Prof. [Xiaotie Deng](https://cfcs.pku.edu.cn/english/people/faculty/xiaotiedeng/index.htm).

- *2024.12 ~ 2025.3*, Research Intern at Microsoft Research Asia(MSRA) \\
  - Advised by [Yuhui Yuan](https://openreview.net/profile?id=~Yuhui_Yuan1).

<div style="
  margin-bottom: 5px;
  line-height: 0.5;
  padding: 0;
">&nbsp;</div>

# Professional Services
- *2026.3*, **Trainer at 2026 ICPC North America Programming Camp (NAPC)**\\
  - Also joined ICPC Live as a guest commentator and conducted the post-contest interview for the 2026 ICPC North America Championship.
  
- *2026.1 ~ 2026.5*, **Teaching Assistant at Carnegie Mellon University**\\
  - 15-451: [Algorithm Design and Analysis](https://www.cs.cmu.edu/~yangp/15-451/) (Prof. [Yang Liu](https://yangpliu.github.io/) & [Richard Peng](https://www.cs.cmu.edu/~yangp/)). 

- *2025.2 ~ 2025.6*, **Teaching Assistant at Peking University** \\
  - 04831760: Practice of Programming in C&C++(Honor Track) (Prof. [Shaofeng Jiang](https://www.shaofengjiang.cn/)).

- **Conference Reviewer** \\
  - FOCS 2024, AIMS @ ICLR 2026

<div style="
  margin-bottom: 5px;
  line-height: 0.5;
  padding: 0;
">&nbsp;</div>

# Invited Talks
- *2026.03*, **Northwestern CS Theory Seminar** \\
  Presented paper “Ex-Ante Truthful Distribution-Reporting Mechanisms”.

- *2026.02*, **CMU Econ-CS Seminar** \\
  Presented paper “Ex-Ante Truthful Distribution-Reporting Mechanisms”.

- *2025.12*, **The 21st Conference on Web and Internet Economics (WINE 2025)** \\
  Presented paper ”Improved Budget-Feasible Mechanisms for Submodular Valuations: Beating 4 Deterministically in Linear Time”on behalf of the authors Kai Han and Pinyan Lu.

- *2025.12*, **China IOI 2026 Training Camp**\\
  Shared reflections on my personal growth from high school to college, focusing on the transition between the two stages and encouragingyounger students to aim higher and stay true to their interests.

- *2024.05*, **Asia-Paciffc Informatics Olympiad (APIO) 2024**\\
  Expert lecturer, delivering a lecture to 650 contestants on-site. Lecture topic: “Probability Theory and Probabilistic Methods”.

<div style="
  margin-bottom: 5px;
  line-height: 0.5;
  padding: 0;
">&nbsp;</div>

# Selected Honors and Awards

**Research Awards**

- *2025.12* HuanYu Information Quest Award, EECS, Peking University. 
- *2025.11* **Rising Star** in Computer Science Research, School of Computer Science, Peking University. 
- *2024.12* **Outstanding Student**, by Center on Frontiers of Computing Studies (CFCS). 

**Scholarships**

- *2025.09* <span style="color: red;">**May Fourth Scholarship**</span>, the highest-level scholarship for Peking University, 125/65k+. 
- *2024.09* <span style="color: red;">**National Scholarship**</span>, the highest honor for undergraduates in China, top 0.5%. 
- *2024.09* Merit Student, by Peking University. 
- *2023.09* Freshman Scholarship, by Peking University. 
- *2023.09* Dean’s Freshman Scholarship, by School of Electronic Engineering & Computer Science (EECS). 

**Competitive Programming**

- *2025.09* <span style="color: red;">**5th place, The 2025 ICPC World Finals**</span>. 
- *2024.12* Gold Medal, The 2024 ICPC East-Asia Continent Final Contest. 
- *2024.11* Champion, The 2024 ICPC Asia Hangzhou Regional Contest. 
- *2024.03* Gold Medal, The 9th China Collegiate Programming Contest(CCPC) Final Contest. 
- *2024.01* Gold Medal, The 2023 ICPC East-Asia Continent Final Contest. 
- *2023.12* Champion, The 2023 ICPC Asia Jinan Regional Contest. 
- *2023.11* Champion, 2023 China Collegiate Programming Contest (Shenzhen). 
- *2022.08* Gold Medal, Best Female Player, National Olympiad in Informatics(NOI). 

