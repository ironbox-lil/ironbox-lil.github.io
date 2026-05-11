---
layout: default
title: 作品集
permalink: /about/
---

<div class="page-content">
  <h1 class="page-heading">作品集</h1>
  <p class="page-subtitle">科研项目与技术实践</p>

  <div class="portfolio-grid">

    <div class="portfolio-item">
      <div class="portfolio-header">
        <h3>时空数据挖掘研究</h3>
        <span class="portfolio-period">2024.9 ~ 至今</span>
      </div>
      <p class="portfolio-supervisor">邓攀教授实验室</p>
      <div class="portfolio-tags">
        <span class="tag">Transformer</span>
        <span class="tag">Diffusion</span>
        <span class="tag">轨迹生成</span>
        <span class="tag">LLM</span>
      </div>
      <p class="portfolio-desc">从事时空数据前沿研究，参与 KDD、IJCAI 论文工作。</p>
    </div>

    <div class="portfolio-item">
      <div class="portfolio-header">
        <h3>SkillForge</h3>
        <span class="portfolio-period">2025.3 ~ 2025.7</span>
      </div>
      <p class="portfolio-supervisor">王海泉教授指导</p>
      <div class="portfolio-tags">
        <span class="tag">LLM+RAG</span>
        <span class="tag">Full-Stack</span>
        <span class="tag">Python</span>
      </div>
      <p class="portfolio-desc">LLM + RAG 赋能的训考评一体系统，获 2025 中国软件杯国家二等奖。</p>
    </div>

    <div class="portfolio-item">
      <div class="portfolio-header">
        <h3>StarOps</h3>
        <span class="portfolio-period">2025.6 ~ 2025.10</span>
      </div>
      <p class="portfolio-supervisor">潘海侠教授、沃天宇教授指导</p>
      <div class="portfolio-tags">
        <span class="tag">银河麒麟</span>
        <span class="tag">智能运维</span>
        <span class="tag">NLP</span>
      </div>
      <p class="portfolio-desc">基于银河麒麟操作系统的智能运维管家工具，获 2025 大挑揭榜挂帅特等奖擂主。</p>
    </div>

    <div class="portfolio-item">
      <div class="portfolio-header">
        <h3>形式化方法 + LLM</h3>
        <span class="portfolio-period">2025.9 ~ 至今</span>
      </div>
      <p class="portfolio-supervisor">葛宁教授实验室</p>
      <div class="portfolio-tags">
        <span class="tag">形式化方法</span>
        <span class="tag">LLM优化</span>
        <span class="tag">软件建模</span>
      </div>
      <p class="portfolio-desc">安全关键系统软件建模，结合形式化方法优化大模型生成质量。</p>
    </div>

    <div class="portfolio-item">
      <div class="portfolio-header">
        <h3>AI4Science with MLLM</h3>
        <span class="portfolio-period">2025.9 ~ 至今</span>
      </div>
      <p class="portfolio-supervisor">陈天宇博士实验室</p>
      <div class="portfolio-tags">
        <span class="tag">MLLM</span>
        <span class="tag">天文学</span>
        <span class="tag">Agent</span>
      </div>
      <p class="portfolio-desc">应用 MLLM 对天文学星图分类及科学推理的 Agent 研究。</p>
    </div>

  </div>
</div>

<style>
.page-subtitle {
  color: #888;
  margin-top: -1.5rem;
  margin-bottom: 2rem;
  font-size: 1.1rem;
}
.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 1.5rem;
}
.portfolio-item {
  background: #fff;
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 20px rgba(0,0,0,0.06);
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}
.portfolio-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
}
.portfolio-header h3 { font-size: 1.1rem; color: #1a1a2e; }
.portfolio-period { color: #888; font-size: 0.8rem; }
.portfolio-supervisor { color: #e94560; font-size: 0.85rem; }
.portfolio-tags { display: flex; flex-wrap: wrap; gap: 0.4rem; }
.tag {
  background: #f0f4f8;
  color: #4a90d9;
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
  font-size: 0.75rem;
  font-weight: 600;
}
.portfolio-desc { color: #666; font-size: 0.9rem; margin-top: 0.5rem; }
</style>