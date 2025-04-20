# 🛣️ MLLM Reasoning Enhancement Guide - Roadmap

本路线图旨在指导该项目从内容搭建到功能扩展的整体发展路径，适用于维护者及社区贡献者协作推进。本项目将分为以下四个阶段推进：

---

## 📍阶段一：内容建设（已启动 ✅）

### 🎯 目标：
- 搭建初始项目框架
- 整理主流推理增强方法与分类
- 汇总核心论文与代表项目链接

### ✅ 已完成：
- `README.md` 主体结构搭建
- 分类方法表格整理
- 基础教程与论文索引目录（resources/）

### 🔜 待完成任务：
- [ ] 对每类方法写详细技术解析（如 `GRPO_training.md`, `symbolic_reasoning.md`）
- [ ] 每篇代表论文撰写简要解读和亮点总结（10篇内优先）

---

## 📍阶段二：教程搭建（进行中 🔧）

### 🎯 目标：
- 提供可复现的多模态推理教程与代码
- 覆盖从 CoT 到神经符号融合的核心路径

### 🔜 计划任务：
- [ ] 补全 `tutorials/` 下每种方法的原理 + 示例 + 代码（参考 PyTorch Notebook）
- [ ] 引入图示（如框架结构、信息流路径图）配合教程讲解
- [ ] 提供一个完整推理 pipeline 的 SFT + RL + Eval 教程

---

## 📍阶段三：实践拓展（待开始 🧪）

### 🎯 目标：
- 提供若干复现路径和增强模块的参考实现
- 加入真实 benchmark 评估流程

### 🔜 计划任务：
- [ ] 构建 `examples/` 路径下的完整复现项目：
  - rejection_sampling/
  - LoRA_finetune/（mini LLaVA）
  - logic_data_gen/（数据生成脚本）
- [ ] 加入真实任务的 benchmark 测评（如 MathQA, ScienceQA, MMBench）

---

## 📍阶段四：社区协作与自动化（中长期规划 ✨）

### 🎯 目标：
- 引入自动化脚本提升维护效率
- 接入社区贡献者与反馈通道

### 🔜 计划任务：
- [ ] 接入 `all-contributors` 进行贡献者识别与徽章生成
- [ ] 编写 `CONTRIBUTING.md` 与 Issue 模板，开放内容类、代码类协作
- [ ] 推出轻量 Web Demo 展示核心技术（如 Symbolic-Reasoning Chatbot）

---


## 📌 附注

- 所有计划任务均支持以 PR / Issue 形式推进
- 路线图会随项目演进不断更新，欢迎大家参与共建！

> ✨ Let’s reason better, together. Welcome to build with us.
