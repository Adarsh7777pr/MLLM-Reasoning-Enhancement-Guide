# 🧠 MLLM Reasoning Enhancement Guide 多模态大模型推理增强指南

这是一个持续更新的知识型仓库，参考 `Awesome-*` 系列的设计风格，旨在系统梳理与收录当前用于提升 **多模态大语言模型（Multimodal Large Language Models, MLLMs）** 推理能力的核心方法、数据集、工具、教程与开源项目。

> ✨ 本项目强调“方法整合 + 资源组织 + 实践引导”，为研究者与开发者提供逻辑推理增强在 MLLM 场景中的系统化导航。

---

## 📦 项目结构与模块设计

本仓库按模块组织内容，推荐通过跳转查阅：

- 📄 [resources/papers.md](resources/papers.md)：经典论文、技术路线与方法分类整理
- 📊 [resources/benchmarks.md](resources/benchmarks.md)：推理相关的公开评测与指标
- 🧰 [resources/tools.md](resources/tools.md)：推理增强工具包、逻辑链构造器等
- 📦 [resources/datasets.md](resources/datasets.md)：多模态推理训练与评测数据集
- 📘 [tutorials/GRPO_training.md](tutorials/GRPO_training.md)：GRPO 强化学习推理训练教程
- 📘 [tutorials/symbolic_reasoning.md](tutorials/symbolic_reasoning.md)：神经-符号融合方法概述
- 🧪 [examples/](examples/)：典型项目复现路径与增强技术代码链接

---

## 🔍 内容覆盖范围

- 🔧 推理增强的典型技术路径（Auto-CoT、ReAct、GRPO 等）
- 📚 多模态 CoT / 神经符号融合 / 路由控制机制方法横向比较
- 🧠 训练方案：指令微调（SFT）、RLHF、RLAIF、拒绝采样
- 🧪 推理相关数据集与 benchmark 指标全景汇总
- 🔗 工程落地：LLaVA / MiniGPT / GRPO / ReAct / ViperGPT 等项目结构分析

---

## 🧩 推理增强方法概览

| 类别 | 技术代表 | 简述 |
|------|------------|------|
| 数据增强 | Auto-CoT, Self-Instruct | 自动生成推理链路样本，提升泛化能力 |
| 强化训练 | GRPO, RLAIF | 通过逻辑一致性反馈优化多轮推理轨迹 |
| 神经符号融合 | PAL, NeuroSymbolic Learners | 外接规则/程序支持复杂推理任务 |
| 模块化结构 | Dynamic Routing, MoE | 基于任务/输入动态调用子模块 |
| 逻辑输出优化 | Rejection Sampling, TruthfulQA | 过滤不一致/无因果回答，提升鲁棒性 |

---

## 📄 代表论文与开源项目

详见 [`resources/papers.md`](resources/papers.md)，部分代表内容如下：

### 🔬 核心论文

- **Chain-of-Thought Prompting** – Wei et al., 2022
- **Self-Instruct** – Wang et al., 2022
- **ReAct** – Yao et al., 2022
- **GRPO** – Gao et al., 2023
- **PAL** – Gao et al., 2022
- **DeepSeekMath** – DeepSeek-AI, 2024
- **VideoCoT** – Luo et al., 2023
- **ViperGPT** – Surís et al., 2023
- **NS-Concept Learner** – Mao et al., 2019

### 🔧 开源项目

- [LLaVA](https://github.com/haotian-liu/LLaVA)
- [MiniGPT-4](https://github.com/Vision-CAIR/MiniGPT-4)
- [GRPO](https://github.com/Luodian/Reinforced-CoT)
- [ReAct](https://github.com/ysymyth/ReAct)
- [VideoCoT](https://github.com/Video-CoT/VideoCoT)
- [ViperGPT](https://github.com/StanfordVL/ViperGPT)
- [DeepSeekMath](https://github.com/deepseek-ai/DeepSeek-Math)

---

## 📌 推荐使用方式

该项目作为“研究 & 实践导航指南”推荐如下使用方式：

1. 通过 `resources/` 获取系统资料与对比综述
2. 阅读 `tutorials/` 了解具体方法原理与流程
3. 参考 `examples/` 跟踪代码与实践项目
4. 根据 `roadmap.md` 提建议、开 issue 或参与共建

---

## 🗂️ 项目文件结构

```
MLLM-Reasoning-Enhancement-Guide/
├── README.md                # 项目总览
├── roadmap.md               # 更新计划
├── resources/               # 核心资料汇总
│   ├── papers.md
│   ├── datasets.md
│   ├── benchmarks.md
│   └── tools.md
├── tutorials/               # 方法解释与流程笔记
│   ├── symbolic_reasoning.md
│   ├── GRPO_training.md
│   └── visual_reasoning.md
├── examples/                # 复现链接与实践指导
│   ├── rejection_sampling/
│   ├── logic_data_gen/
│   └── LoRA_finetune/
└── figures/                 # 示意图与结构流程图
```

---

## 📬 联系与参与

- Maintainer: Jeffjeno
- Email: jenojeff66@gmail.com
- 欢迎提交 PR / Issue，一起完善多模态推理生态


---

> 参考项目：`Awesome-Multimodal-LLM`, `ReAct`, `MiniGPT-4`, `LLaVA`, `GRPO`, `LangChain`, `HuggingFace Blog` 等

🧠 **Together, let’s reason better with multimodal LLMs.**

