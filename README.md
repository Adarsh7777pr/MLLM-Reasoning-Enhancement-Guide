# 🧠 MLLM Reasoning Enhancement Guide 多模态大模型推理增强指南

[![Stars](https://img.shields.io/github/stars/Jeffjeno/MLLM-Reasoning-Enhancement-Guide?style=social)](https://github.com/Jeffjeno/MLLM-Reasoning-Enhancement-Guide/stargazers)
[![Issues](https://img.shields.io/github/issues/Jeffjeno/MLLM-Reasoning-Enhancement-Guide)](https://github.com/Jeffjeno/MLLM-Reasoning-Enhancement-Guide/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Jeffjeno/MLLM-Reasoning-Enhancement-Guide/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 📘 项目简介

本项目旨在提供一个系统性的多模态大模型（MLLM）推理增强方法指南，涵盖方法综述、核心论文、工具使用、数据资源和教程笔记，帮助研究者和开发者全面理解和掌握 MLLM 的推理能力提升路径。

> ✨ 参考自 Embodied-AI-Guide、Awesome-Multimodal-LLM、LangChain 等项目构建风格，结合实用性与系统性。

---

## 🗂️ 内容索引（Contents）

1. [快速导航入口](#1-快速导航入口)
2. [适用人群与使用建议](#2-适用人群与使用建议)
3. [代表方法与分类](#3-代表方法与分类)
4. [推荐阅读与项目实践](#4-推荐阅读与项目实践)
5. [项目文件结构](#5-项目文件结构)
6. [路线图与发展方向](#6-路线图与发展方向)
7. [参与贡献](#7-参与贡献)

---

## 1. 🚀 快速导航入口

- 📄 [resources/papers.md](resources/papers.md)：核心论文与技术路径分类
- 📊 [resources/benchmarks.md](resources/benchmarks.md)：主流推理评估指标与任务
- 📦 [resources/datasets.md](resources/datasets.md)：推理相关训练数据集（含视觉、语言、视频等）
- 🧰 [resources/tools.md](resources/tools.md)：辅助工具如 ReAct、Prover9、提示构造器等
- 📘 [tutorials/](tutorials/)：GRPO / CoT / 神经符号融合等技术的教程解析
- 🧪 [examples/](examples/)：可复现项目、增强路径代码
- 🛣️ [ROADMAP.md](ROADMAP.md)：发展阶段计划与模块任务清单

---

## 2. 🧠 适用人群与使用建议

- 🧑‍🔬 **研究者**：可从 `resources/` 阅读论文、数据、基准，快速了解研究现状
- 🧑‍💻 **开发者**：聚焦 `examples/` 和 `tutorials/` 模块，获取实用工具与强化路径
- 🧑‍🎓 **学生学习者**：建议阅读 CoT / GRPO / Symbolic Reasoning 教程，结合 benchmark 理解全流程

---

## 3. 🔧 代表方法与分类

| 类别 | 技术代表 | 简述 |
|------|------------|------|
| 数据增强 | Auto-CoT, Self-Instruct | 自动生成推理链样本，提升泛化能力 |
| 强化训练 | GRPO, RLAIF | 利用逻辑奖励信号优化多轮推理路径 |
| 神经符号融合 | PAL, NS-Concept Learners | 外接程序与逻辑工具辅助长链式推理 |
| 模块路由 | Dynamic Routing, MoE | 输入驱动动态调用模块提升效率 |
| 输出优化 | Rejection Sampling, TruthfulQA | 逻辑一致性与可信度输出提升机制 |

---

## 4. 📄 推荐阅读与项目实践

### 4.1 🔬 核心论文（详见 [`resources/papers.md`](resources/papers.md)）

- Chain-of-Thought Prompting – Wei et al., 2022  
- Self-Instruct – Wang et al., 2022  
- ReAct – Yao et al., 2022  
- GRPO – Gao et al., 2023  
- PAL – Gao et al., 2022  
- DeepSeekMath – DeepSeek-AI, 2024  
- VideoCoT – Luo et al., 2023  
- ViperGPT – Surís et al., 2023  
- NS-Concept Learner – Mao et al., 2019

### 4.2 🔧 开源项目

- [LLaVA](https://github.com/haotian-liu/LLaVA)
- [MiniGPT-4](https://github.com/Vision-CAIR/MiniGPT-4)
- [GRPO](https://github.com/Luodian/Reinforced-CoT)
- [ReAct](https://github.com/ysymyth/ReAct)
- [VideoCoT](https://github.com/Video-CoT/VideoCoT)
- [ViperGPT](https://github.com/StanfordVL/ViperGPT)
- [DeepSeekMath](https://github.com/deepseek-ai/DeepSeek-Math)
- [COT-Prompting](https://www.promptingguide.ai/techniques/cot)
---

## 5. 🗂️ 项目文件结构

```
MLLM-Reasoning-Enhancement-Guide/
├── README.md
├── ROADMAP.md
├── resources/
│   ├── papers.md
│   ├── datasets.md
│   ├── benchmarks.md
│   └── tools.md
├── tutorials/
│   ├── symbolic_reasoning.md
│   ├── GRPO_training.md
│   ├── cot_prompting.md
│   └── evaluation_metrics.md
├── examples/
│   ├── rejection_sampling/
│   ├── logic_data_gen/
│   └── LoRA_finetune/
└── figures/
```

---

## 6. 🛣️ 路线图与发展方向

详见 [`ROADMAP.md`](ROADMAP.md)，涵盖四个阶段：内容建设 → 教程搭建 → 实践拓展 → 社区协作。

---

## 7. 🤝 参与贡献

- Maintainer: Jeffjeno  
- Email: jenojeff66@gmail.com
- 欢迎提交 PR、Issue，参与资料补充、格式优化、代码贡献
- 计划接入 `all-contributors` 自动贡献人展示，敬请期待 ✨

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

## Contributors ✨

感谢这些杰出的贡献者（👋 Emoji表示贡献类型）:

<!-- prettier-ignore-start -->
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Jeffjeno">
        <img src="https://avatars.githubusercontent.com/Jeffjeno?v=4" width="100px;" alt="Jeffjeno"/>
        <br /><sub><b>Jeffjeno</b></sub>
      </a>
      <br />💻 📖
    </td>
    <td align="center">
      <a href="https://github.com/Dcx-swjtu">
        <img src="https://avatars.githubusercontent.com/u/199071563?v=4" width="100px;" alt="Dcx-swjtu"/>
        <br /><sub><b>Dcx-swjtu</b></sub>
      </a>
      <br />🛠️
    </td>
    <td align="center">
      <a href="https://github.com/tower567">
        <img src="https://avatars.githubusercontent.com/u/151821673?v=4" width="100px;" alt="tower567"/>
        <br /><sub><b>tower567</b></sub>
      </a>
      <br />📖 🤔
    </td>
    <td align="center">
      <a href="https://github.com/Ynimi">
        <img src="https://avatars.githubusercontent.com/u/183828395?v=4" width="100px;" alt="Ynimi"/>
        <br /><sub><b>Ynimi</b></sub>
      </a>
      <br />🤔 ⭐
    </td>
    <td align="center">
      <a href="https://github.com/Shoemaker112">
        <img src="https://avatars.githubusercontent.com/u/187404473?v=4" width="100px;" alt="Shoemaker112"/>
        <br /><sub><b>Shoemaker112</b></sub>
      </a>
      <br />💻 📖
    </td>
  </tr>
</table>
<!-- prettier-ignore-end -->

---

> 参考项目：Embodied-AI-Guide, Awesome-Multimodal-LLM, GRPO, LangChain, LLaVA 等

🧠 **Together, let’s reason better with multimodal LLMs.**

## ⭐ Star History

[![Star History Chart](figures/star-history.png)](https://star-history.com/#Jeffjeno/MLLM-Reasoning-Enhancement-Guide&Date)

