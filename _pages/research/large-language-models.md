---
title: "Large Language Models"
permalink: /research/large-language-models/
layout: single
classes: wide
---

<style>
:root {
  --primary-color: #1a76d2;
  --primary-hover: #0d5caf;
  --heading-color: #333333;
  --text-color: #444444;
  --light-text: #666666;
  --border-color: #e5e5e5;
  --background-light: #f8f9fa;
  --card-background: #ffffff;
  --shadow-color: rgba(0,0,0,0.08);
}

.project-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px 0;
}

.project-description {
  margin-bottom: 30px;
  text-align: justify;
  line-height: 1.6;
  color: var(--text-color);
}

.project-box {
  border: 1px solid var(--border-color);
  margin-bottom: 30px;
  border-radius: 8px;
  overflow: hidden;
  background-color: var(--card-background);
  box-shadow: 0 2px 5px var(--shadow-color);
}

.project-heading {
  background-color: var(--background-light);
  padding: 15px 20px;
  font-size: 1.4em;
  font-weight: bold;
  border-bottom: 1px solid var(--border-color);
  color: var(--heading-color);
}

.project-heading a {
  text-decoration: none;
  color: var(--primary-color);
}

.project-heading a:hover {
  text-decoration: underline;
  color: var(--primary-hover);
}

.project-content {
  padding: 20px;
  text-align: justify;
  line-height: 1.5;
  color: var(--text-color);
}

.project-image {
  padding: 0 20px 20px;
  text-align: center;
}

.project-image img {
  max-width: 100%;
  height: auto;
  border: 1px solid var(--border-color);
  border-radius: 4px;
}

.back-link {
  display: inline-block;
  margin-top: 30px;
  margin-bottom: 20px;
  color: var(--primary-color);
  font-weight: 500;
  text-decoration: none;
}

.back-link:hover {
  text-decoration: underline;
  color: var(--primary-hover);
}

h1 {
  color: var(--heading-color);
  margin-bottom: 25px;
}
</style>

<div class="project-description">
  Our research on Large Language Models focuses on architectural improvements, efficient training methods, and practical applications. We investigate how LLMs can be integrated with embodied systems to enable more natural and efficient interactions between agents and their environments.
</div>

<div class="project-box">
  <div class="project-heading">
    <a href="#">ResDecode: Accelerating Large Language Models Inference</a>
  </div>
  <div class="project-content">
    This research introduces a novel approach for accelerating inference in large language models through the use of residual decoding heads. By optimizing the decoding process, we achieve significant performance improvements without sacrificing model quality, enabling more efficient deployment of LLMs in resource-constrained environments.
  </div>
</div>

<div class="project-box">
  <div class="project-heading">
    <a href="#">Privacy-Preserving Fine-Tuning for LLMs</a>
  </div>
  <div class="project-content">
    We explore methods for fine-tuning large language models while preserving data privacy. Our approach uses synthetic data generation techniques to create training examples that maintain utility while protecting sensitive information, allowing for specialized model adaptation without compromising user privacy.
  </div>
</div>

<a href="/research" class="back-link">← Back to Research</a>
