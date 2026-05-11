---
layout: default
title: 关于
permalink: /resume/
---

<div class="page-content resume-page">
  <h1 class="page-heading">关于我</h1>

  <section class="resume-section">
    <h2 class="section-title">基本信息</h2>
    <div class="info-grid">
      <div class="info-item"><span class="info-label">姓名</span><span class="info-value">唐皓涵</span></div>
      <div class="info-item"><span class="info-label">年龄</span><span class="info-value">21 岁</span></div>
      <div class="info-item"><span class="info-label">学历</span><span class="info-value">北京航空航天大学 / 大三</span></div>
      <div class="info-item"><span class="info-label">专业</span><span class="info-value">软件工程 + 应用数学（辅修）</span></div>
      <div class="info-item"><span class="info-label">邮箱</span><span class="info-value">tanghaohan@buaa.edu.cn</span></div>
      <div class="info-item"><span class="info-label">电话</span><span class="info-value">17783691761</span></div>
      <div class="info-item full"><span class="info-label">研究方向</span><span class="info-value">数据挖掘(Data Mining) · 具身智能 · 大模型(LLM)</span></div>
    </div>
  </section>

  <section class="resume-section">
    <h2 class="section-title">完整简历</h2>
    <p class="resume-note">请查看首页了解详细的教育背景、科研经历、项目经历和获奖情况。</p>
  </section>

</div>

<style>
.resume-page { max-width: 800px; margin: 0 auto; padding: 2rem; }
.resume-section { margin-bottom: 3rem; }
.resume-section .section-title {
  font-size: 1.4rem;
  font-weight: 700;
  color: #1a1a2e;
  margin-bottom: 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 3px solid #e94560;
  display: inline-block;
}
.info-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}
.info-item {
  background: #fff;
  border-radius: 8px;
  padding: 1rem 1.2rem;
  display: flex;
  gap: 1rem;
  box-shadow: 0 2px 15px rgba(0,0,0,0.05);
}
.info-item.full { grid-column: 1 / -1; }
.info-label {
  background: #1a1a2e;
  color: #fff;
  padding: 0.3rem 0.8rem;
  border-radius: 4px;
  font-weight: 600;
  font-size: 0.8rem;
  white-space: nowrap;
}
.info-value { color: #555; display: flex; align-items: center; }
.resume-note { color: #888; font-style: italic; }
@media (max-width: 600px) {
  .info-grid { grid-template-columns: 1fr; }
}
</style>