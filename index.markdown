---
layout: default
title: Lil Tang
---

<div class="home">

  <!-- Hero Section with Self-Introduction -->
  <section class="hero">
    <div class="hero-content">
      <h1 class="hero-name">{{ site.author.name }}</h1>
      <p class="hero-title">北京航空航天大学软件学院 · 大三</p>
      <p class="hero-focus">数据挖掘 · 具身智能 · 大模型 (LLM)</p>
      <div class="hero-links">
        <a href="mailto:{{ site.author.email }}" class="hero-link-item">
          <span class="icon">✉</span> {{ site.author.email }}
        </a>
        <a href="tel:{{ site.author.phone }}" class="hero-link-item">
          <span class="icon">☎</span> {{ site.author.phone }}
        </a>
        <span class="hero-link-item">
          <span class="icon">⌖</span> {{ site.author.location }}
        </span>
      </div>
    </div>
  </section>

  <!-- Self Introduction -->
  <section class="section intro-section">
    <div class="intro-card">
      <h2 class="section-title">关于我</h2>
      <p class="intro-text">
        我是北航软件学院大三学生，目前在邓攀教授的时空数据挖掘实验室从事科研实习。
        我的研究方向主要集中在数据挖掘与大模型应用，具体包括轨迹生成、时空数据分析以及大模型的结构化输出优化。
      </p>
      <p class="intro-text">
        目前已有 KDD 2026 共同一作在投（CCF-A）、IJCAI 2026 三作在投（CCF-B），
        预计 7 月投递 ICSE，预计 8 月投递 AAAI。本科期间获首都挑战杯擂主特等奖、挑战杯揭榜挂帅擂主特等奖等荣誉。
      </p>
      <div class="intro-tags">
        <span class="intro-tag">科研</span>
        <span class="intro-tag">数据挖掘</span>
        <span class="intro-tag">大模型</span>
        <span class="intro-tag">论文发表</span>
      </div>
    </div>
  </section>

  <!-- Publications -->
  <section class="section" id="publications">
    <h2 class="section-title">论文发表</h2>
    <div class="pub-list">
      <div class="pub-item">
        <div class="pub-level badge-ccf-a">CCF-A</div>
        <div class="pub-info">
          <span class="pub-title">KDD 2026 共同一作在投</span>
          <span class="pub-name">InST: Intent-Aware and Structure-Constrained Large Language Models for Trajectory Generation</span>
        </div>
      </div>
      <div class="pub-item">
        <div class="pub-level badge-ccf-b">CCF-B</div>
        <div class="pub-info">
          <span class="pub-title">IJCAI 2026 三作在投</span>
          <span class="pub-name">TSNorm: Normalization for Multivariate Time Series Forecasting against Cross-Variable Dependency Shift</span>
        </div>
      </div>
      <div class="pub-item upcoming">
        <span class="pub-plan">预计 7 月 ICSE（二作/共一），8 月 AAAI（共一）</span>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section class="section" id="projects">
    <h2 class="section-title">项目实践</h2>
    <div class="proj-list">
      <div class="proj-item">
        <div class="proj-header">
          <h3 class="proj-title">SkillForge — LLM + RAG 赋能的训考评一体系统</h3>
          <span class="proj-period">2025.3 ~ 2025.7</span>
        </div>
        <p class="proj-supervisor">导师：北航软件学院王海泉教授</p>
        <div class="proj-award">🏆 2025 中国软件杯国家二等奖</div>
        <ul class="proj-bullets">
          <li>项目网站服务层前后端开发</li>
          <li>算法层 RAG-LLM 检索增强，多步 Prompt 数据挖掘</li>
        </ul>
      </div>

      <div class="proj-item">
        <div class="proj-header">
          <h3 class="proj-title">StarOps — 银河麒麟智能运维管家</h3>
          <span class="proj-period">2025.6 ~ 2025.10</span>
        </div>
        <p class="proj-supervisor">导师：北航软件学院潘海侠教授、沃天宇教授</p>
        <div class="proj-award">🏆 2025 大挑揭榜挂帅特等奖擂主</div>
        <ul class="proj-bullets">
          <li>自然语言交互、系统异常检测、分布式服务异常根因定位</li>
          <li>系统应用服务缺陷检测、故障自动修复</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Lab Experience Summary -->
  <section class="section" id="experience">
    <h2 class="section-title">科研经历</h2>
    <div class="exp-list">
      <div class="exp-item">
        <div class="exp-header">
          <div class="exp-title-block">
            <h3 class="exp-title">北航时空数据挖掘实验室</h3>
            <span class="exp-role">邓攀教授</span>
          </div>
          <span class="exp-period">2024.9 ~ 至今</span>
        </div>
        <ul class="exp-bullets">
          <li>时空数据相关前沿论文汇报，代码复现</li>
          <li>Transformer、Diffusion 等生成模型，基线实验与论文写作</li>
          <li>KDD 共一、IJCAI 三作在投</li>
        </ul>
      </div>

      <div class="exp-item">
        <div class="exp-header">
          <div class="exp-title-block">
            <h3 class="exp-title">形式化方法实验室</h3>
            <span class="exp-role">葛宁教授</span>
          </div>
          <span class="exp-period">2025.9 ~ 至今</span>
        </div>
        <ul class="exp-bullets">
          <li>安全关键系统软件建模，形式化方法优化大模型生成</li>
          <li>预计 7 月投递 ICSE 论文</li>
        </ul>
      </div>

      <div class="exp-item">
        <div class="exp-header">
          <div class="exp-title-block">
            <h3 class="exp-title">ACT 实验室</h3>
            <span class="exp-role">陈天宇博士</span>
          </div>
          <span class="exp-period">2025.9 ~ 至今</span>
        </div>
        <ul class="exp-bullets">
          <li>AI4Science 与 LLM 结合：MLLM 天文学星图分类、科学推理 Agent</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Awards Preview -->
  <section class="section" id="awards">
    <h2 class="section-title">荣誉奖项</h2>
    <div class="awards-grid">
      <div class="award-item major">
        <span class="award-name">首都挑战杯擂主特等奖</span>
      </div>
      <div class="award-item major">
        <span class="award-name">挑战杯揭榜挂帅擂主特等奖</span>
      </div>
      <div class="award-item major">
        <span class="award-name">北航软件学院团队之星</span>
      </div>
      <div class="award-item">
        <span class="award-name">中国软件杯二等奖</span>
      </div>
      <div class="award-item">
        <span class="award-name">九号公司一等奖学金</span>
      </div>
      <div class="award-item">
        <span class="award-name">美国大学生数学建模竞赛 H 奖</span>
      </div>
    </div>
    <a href="/resume/" class="view-more">查看完整简历 →</a>
  </section>

</div>