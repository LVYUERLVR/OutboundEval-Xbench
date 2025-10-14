<div align="center">
<h2 style="font-size: 40px;">OutboundEval: A Dual-Dimensional Benchmark for Expert-Level Intelligent Outbound Evaluation of Xbench's Professional-Aligned Series</h2>
</div>

<p align="center">
  <!-- arxiv badges -->
  <a href="https://arxiv.org/abs/">
    <img src="https://img.shields.io/badge/Paper-red?style=flat&logo=arxiv">
  </a>
  <!-- Chinese Version -->
  <a href="https://baidu.com">
    <img src="https://img.shields.io/badge/Project Page-white?style=flat&logo=google-docs">
  </a>
  <!-- Github -->
  <a href="https://github.com/">
    <img src="https://img.shields.io/badge/Code-black?style=flat&logo=github">
  </a>
</p>

<div align="center">
  <p>
    <a>Pengyu Xu</a><sup>1,4*</sup>, 
    <a>Shijia Li</a><sup>1,5*</sup>, 
    <a>Ao Sun</a><sup>1,6*</sup>,
    <a>Yahan Li</a><sup>1,7</sup>, 
    <a>Bo Wu</a><sup>1,8</sup>,
    <a>Zhanyu Ma</a><sup>1</sup>, <br>
    <a>Jiguo Li</a><sup>1</sup>,
    <a>Jun Xu</a><sup>1</sup>,
    <a>Jiuchong Gao</a><sup>1</sup>,
    <a>Jinghua Hao</a><sup>1</sup>,
    <a>Renqing He</a><sup>1</sup>,
    <a>Rui Wang</a><sup>2</sup>,
    <a>Yang Liu</a><sup>2</sup>,
    <a>Xiaobo Hu</a><sup>2</sup>,
    <a>Xbench</a><sup>2</sup>,
    <a>Fan Yang</a><sup>3</sup>,
    <a>Jia Zheng</a><sup>3</sup>,
    <a>Guanghua Yao</a><sup>3</sup>,
  </p>
  <p>
    <sup>1</sup><a>Meituan</a>, <sup>2</sup><a>Xbench</a>, <sup>3</sup><a>Agora</a>, <sup>4</sup><a>Beijing Jiaotong University</a>, <br>
    <sup>5</sup><a>BUPT</a>, <sup>6</sup><a>The Chinese University of Hong Kong, Shenzhen</a>, <sup>7</sup><a>Jilin University</a>, <sup>8</sup><a>Peking University</a>
  </p>
</div>

<div align="center"><small><sup>*</sup>Equal Contribution.</small></div>

## 🤖 Introduction
Welcome to the GitHub repository for our paper titled "OutboundEval: A Dual-Dimensional Benchmark for Expert-Level Intelligent Outbound Evaluation of Xbench's Professional-Aligned Series". 
In this work, we propose **OutboundEval**, a comprehensive benchmark for evaluating large language models (LLMs) in expert-level intelligent outbound calling scenarios. Unlike existing methods that suffer from three key limitations—insufficient dataset diversity and category coverage, unrealistic user simulation, and inaccurate evaluation metrics—OutboundEval addresses these issues through a structured framework. First, we design a benchmark spanning six major business domains and 30 representative sub-scenarios, each with scenario-specific process decomposition, weighted scoring, and domain-adaptive metrics. Second, we develop a large-model-driven **User Simulator** that generates diverse, persona-rich virtual users with realistic behaviors, emotional variability, and communication styles, providing a controlled yet authentic testing environment. Third, we introduce a dynamic evaluation method that adapts to task variations, integrating automated and human-in-the-loop assessment to measure task execution accuracy, professional knowledge application, adaptability, and user experience quality. Experiments on 12 state-of-the-art LLMs reveal distinct trade-offs between expert-level task completion and interaction fluency, offering practical insights for building reliable, human-like outbound AI systems. OutboundEval establishes a practical, extensible, and domain-oriented standard for benchmarking LLMs in professional applications.

![llm_12](./imgs/main.png)





![llm_12](./imgs/llm_12.jpg)
