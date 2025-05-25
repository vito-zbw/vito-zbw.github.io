---
title: "Research"
permalink: /research/
layout: splash
classes: wide
---

<style>
.research-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.research-item {
  width: 30%;
  margin-bottom: 30px;
  display: flex;
  flex-direction: column;
}

.research-image {
  height: 200px;
  overflow: hidden;
  margin-bottom: 15px;
}

.research-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.research-title {
  font-size: 1.5em;
  font-weight: bold;
  margin-bottom: 10px;
}

.research-text {
  flex-grow: 1;
  text-align: justify;
}

.research-button {
  align-self: flex-start;
  margin-top: 15px;
  background-color: #f2f2f2;
  color: #333;
  padding: 8px 15px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 4px;
}

.research-button:hover {
  background-color: #ddd;
}

@media (max-width: 992px) {
  .research-item {
    width: 48%;
  }
}

@media (max-width: 768px) {
  .research-item {
    width: 100%;
  }
}

.project-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px 0;
}

.project-title {
  font-size: 2em;
  font-weight: bold;
  color: #333;
  margin-bottom: 30px;
  text-align: center;
}

.project-box {
  border: 1px solid #eaeaea;
  margin-bottom: 20px;
  border-radius: 5px;
  overflow: hidden;
}

.project-heading {
  background-color: #f8f8f8;
  padding: 10px 15px;
  font-size: 1.4em;
  font-weight: bold;
  text-align: center;
  border-bottom: 1px solid #eaeaea;
}

.project-description {
  padding: 15px;
  text-align: justify;
  line-height: 1.5;
  border-bottom: 1px solid #eaeaea;
}

</style>

<div class="research-container">
  <div class="research-item">
    <div class="research-image">
      <img src="/assets/images/projects/CL.png" alt="Continued Learning">
    </div>
    <div class="research-title">Continued Learning</div>
    <div class="research-text">
      We study how AI systems can learn continuously over time without forgetting previous knowledge. Using analytic learning approaches, we develop methods that efficiently adapt to new data while preserving existing capabilities. Our frameworks support lifelong learning for applications in robotics and intelligent systems.
    </div>
    <a href="#continued-learning-details" class="research-button">Learn More</a>
  </div>
  
  <div class="research-item">
    <div class="research-image">
      <img src="/assets/images/projects/EI.jpg" alt="Embodied Intelligence">
    </div>
    <div class="research-title">Embodied Intelligence</div>
    <div class="research-text">
      We explore how intelligence emerges from the interaction between an agent's physical body and its control systems. Our research develops AI methods that leverage this physical embodiment to enhance adaptability in changing environments, creating more robust and responsive autonomous systems.
    </div>
    <a href="#embodied-intelligence-details" class="research-button">Learn More</a>
  </div>
  
  <div class="research-item">
    <div class="research-image">
      <img src="/assets/images/projects/LLM.png" alt="Large Language Models">
    </div>
    <div class="research-title">Large Language Models</div>
    <div class="research-text">
      Our work on large language models focuses on architectural improvements, efficient training methods, and practical applications. We investigate how to integrate LLMs with embodied systems to enable more natural human-machine interactions in physical environments.
    </div>
    <a href="#large-language-models-details" class="research-button">Learn More</a>
  </div>
</div>

<div class="project-container">
  <h2 class="project-title" id="continued-learning-details">Continued Learning</h2>
  
  <div class="project-box">
    <div class="project-heading"> <a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/4b74a42fc81fc7ee252f6bcb6e26c8be-Abstract-Conference.html">ACIL: Analytic class-incremental learning with absolute memorization and privacy protection</a></div>
    <div class="project-description">
      We introduce a novel approach to class-incremental learning (CIL) that addresses the challenges of catastrophic forgetting and data privacy. The proposed Analytic Class-Incremental Learning (ACIL) framework allows for absolute memorization of past knowledge without storing historical data, thereby ensuring data privacy. The authors theoretically validate that ACIL can achieve results identical to traditional joint-learning methods while only using current data. Empirical results demonstrate that ACIL outperforms existing state-of-the-art methods, particularly in large-phase scenarios (e.g., 25 and 50 phases).
    </div>
    <div class="project-image" style="height: auto; padding: 20px; display: block;">
      <img src="/assets/images/papers/2022-1.png" alt="ACIL Paper" style="width: 100%; max-width: 100%; height: auto; display: block; margin: 0 auto;">
    </div>
  </div>
  
  <div class="project-box">
    <div class="project-heading"><a href="https://arxiv.org/abs/2405.16240">Analytic Federated Learning</a></div>
    <div class="project-description">
      In this paper, we introduce analytic federated learning (AFL), a new training paradigm that brings analytical (i.e., closed-form) solutions to the federated learning (FL) community. Our AFL draws inspiration from analytic learning -- a gradient-free technique that trains neural networks with analytical solutions in one epoch. In the local client training stage, the AFL facilitates a one-epoch training, eliminating the necessity for multi-epoch updates. In the aggregation stage, we derive an absolute aggregation (AA) law. This AA law allows a single-round aggregation, removing the need for multiple aggregation rounds. The AFL exhibits a weight-invariant property, meaning that regardless of how the full dataset is distributed among clients, the aggregated result remains identical.
    </div>
  </div>
</div>

<div class="project-container">
  <h2 class="project-title" id="embodied-intelligence-details">Embodied Intelligence</h2>
  
  <div class="project-box">
    <div class="project-heading"> <a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/4b74a42fc81fc7ee252f6bcb6e26c8be-Abstract-Conference.html">ACIL: Analytic class-incremental learning with absolute memorization and privacy protection</a></div>
    <div class="project-description">
      We introduce a novel approach to class-incremental learning (CIL) that addresses the challenges of catastrophic forgetting and data privacy. The proposed Analytic Class-Incremental Learning (ACIL) framework allows for absolute memorization of past knowledge without storing historical data, thereby ensuring data privacy. The authors theoretically validate that ACIL can achieve results identical to traditional joint-learning methods while only using current data. Empirical results demonstrate that ACIL outperforms existing state-of-the-art methods, particularly in large-phase scenarios (e.g., 25 and 50 phases).
    </div>
    <div class="project-image" style="height: auto; padding: 20px; display: block;">
      <img src="/assets/images/papers/2022-1.png" alt="ACIL Paper" style="width: 100%; max-width: 100%; height: auto; display: block; margin: 0 auto;">
    </div>
  </div>
  
  <div class="project-box">
    <div class="project-heading"><a href="https://arxiv.org/abs/2405.16240">Analytic Federated Learning</a></div>
    <div class="project-description">
      In this paper, we introduce analytic federated learning (AFL), a new training paradigm that brings analytical (i.e., closed-form) solutions to the federated learning (FL) community. Our AFL draws inspiration from analytic learning -- a gradient-free technique that trains neural networks with analytical solutions in one epoch. In the local client training stage, the AFL facilitates a one-epoch training, eliminating the necessity for multi-epoch updates. In the aggregation stage, we derive an absolute aggregation (AA) law. This AA law allows a single-round aggregation, removing the need for multiple aggregation rounds. The AFL exhibits a weight-invariant property, meaning that regardless of how the full dataset is distributed among clients, the aggregated result remains identical.
    </div>
  </div>
</div>

<div class="project-container">
  <h2 class="project-title" id="large-language-models-details">Large Language Models</h2>
  
  <div class="project-box">
    <div class="project-heading"> <a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/4b74a42fc81fc7ee252f6bcb6e26c8be-Abstract-Conference.html">ACIL: Analytic class-incremental learning with absolute memorization and privacy protection</a></div>
    <div class="project-description">
      We introduce a novel approach to class-incremental learning (CIL) that addresses the challenges of catastrophic forgetting and data privacy. The proposed Analytic Class-Incremental Learning (ACIL) framework allows for absolute memorization of past knowledge without storing historical data, thereby ensuring data privacy. The authors theoretically validate that ACIL can achieve results identical to traditional joint-learning methods while only using current data. Empirical results demonstrate that ACIL outperforms existing state-of-the-art methods, particularly in large-phase scenarios (e.g., 25 and 50 phases).
    </div>
    <div class="project-image" style="height: auto; padding: 20px; display: block;">
      <img src="/assets/images/papers/2022-1.png" alt="ACIL Paper" style="width: 100%; max-width: 100%; height: auto; display: block; margin: 0 auto;">
    </div>
  </div>
  
  <div class="project-box">
    <div class="project-heading"><a href="https://arxiv.org/abs/2405.16240">Analytic Federated Learning</a></div>
    <div class="project-description">
      In this paper, we introduce analytic federated learning (AFL), a new training paradigm that brings analytical (i.e., closed-form) solutions to the federated learning (FL) community. Our AFL draws inspiration from analytic learning -- a gradient-free technique that trains neural networks with analytical solutions in one epoch. In the local client training stage, the AFL facilitates a one-epoch training, eliminating the necessity for multi-epoch updates. In the aggregation stage, we derive an absolute aggregation (AA) law. This AA law allows a single-round aggregation, removing the need for multiple aggregation rounds. The AFL exhibits a weight-invariant property, meaning that regardless of how the full dataset is distributed among clients, the aggregated result remains identical.
    </div>
  </div>
</div>

