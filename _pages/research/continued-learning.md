---
title: "Continued Learning"
permalink: /research/continued-learning/
layout: single
classes: wide
---

<style>
.project-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px 0;
}

.project-description {
  margin-bottom: 30px;
  text-align: justify;
  line-height: 1.6;
}

.project-box {
  border: 1px solid #eaeaea;
  margin-bottom: 30px;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.project-heading {
  background-color: #f8f8f8;
  padding: 15px 20px;
  font-size: 1.4em;
  font-weight: bold;
  border-bottom: 1px solid #eaeaea;
}

.project-heading a {
  text-decoration: none;
  color: #0366d6;
}

.project-heading a:hover {
  text-decoration: underline;
}

.project-content {
  padding: 20px;
  text-align: justify;
  line-height: 1.5;
}

.project-image {
  padding: 0 20px 20px;
  text-align: center;
}

.project-image img {
  max-width: 100%;
  height: auto;
  border: 1px solid #eee;
}

.back-link {
  display: inline-block;
  margin-top: 30px;
  margin-bottom: 20px;
  color: #0366d6;
  font-weight: 500;
}

.back-link:hover {
  text-decoration: underline;
}
</style>

<div class="project-description">
  Our research in Continued Learning focuses on developing AI systems that can continuously acquire and refine knowledge over time without forgetting previously learned information. We utilize analytical learning approaches to create methods that efficiently adapt to new data while preserving existing capabilities.
</div>

<div class="project-box">
  <div class="project-heading">
    <a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/4b74a42fc81fc7ee252f6bcb6e26c8be-Abstract-Conference.html">ACIL: Analytic class-incremental learning with absolute memorization and privacy protection</a>
  </div>
  <div class="project-content">
    We introduce a novel approach to class-incremental learning (CIL) that addresses the challenges of catastrophic forgetting and data privacy. The proposed Analytic Class-Incremental Learning (ACIL) framework allows for absolute memorization of past knowledge without storing historical data, thereby ensuring data privacy. We theoretically validate that ACIL can achieve results identical to traditional joint-learning methods while only using current data. Empirical results demonstrate that ACIL outperforms existing state-of-the-art methods, particularly in large-phase scenarios (e.g., 25 and 50 phases).
  </div>
  <div class="project-image">
    <img src="/assets/images/papers/2022-1.png" alt="ACIL Paper">
  </div>
</div>

<div class="project-box">
  <div class="project-heading">
    <a href="https://arxiv.org/abs/2405.16240">Analytic Federated Learning</a>
  </div>
  <div class="project-content">
    In this paper, we introduce analytic federated learning (AFL), a new training paradigm that brings analytical (i.e., closed-form) solutions to the federated learning (FL) community. Our AFL draws inspiration from analytic learning -- a gradient-free technique that trains neural networks with analytical solutions in one epoch. In the local client training stage, the AFL facilitates a one-epoch training, eliminating the necessity for multi-epoch updates. In the aggregation stage, we derive an absolute aggregation (AA) law. This AA law allows a single-round aggregation, removing the need for multiple aggregation rounds.
  </div>
</div>

<a href="/research" class="back-link">← Back to Research</a>
