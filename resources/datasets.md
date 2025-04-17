# 📦 推理增强相关数据集整理（Reasoning-related Datasets）

本页收录与多模态大模型（MLLM）推理能力提升密切相关的经典与最新数据集，涵盖视觉问答（VQA）、图文逻辑判断、因果推理、视频理解、多轮对话等典型任务。

---

## 🧠 通用推理数据集（文本 + 多模态）

| 数据集 | 模态 | 简介 | 链接 |
|--------|------|------|------|
| **GSM8K** | Text | 小学数学文字题，标准CoT推理数据集（8k+） | https://github.com/openai/grade-school-math |
| **AQUA-RAT** | Text | 多选题 + 逻辑推理 + 解析（含步骤） | https://github.com/deepmind/AQuA |
| **OpenBookQA** | Text | 开卷考试型科学问答，考查多跳推理能力 | https://allenai.org/data/openbookqa |
| **CommonsenseQA** | Text | 常识逻辑问答，需理解隐含因果关系 | https://www.tau-nlp.org/commonsenseqa |
| **StrategyQA** | Text | 策略性复杂问题，需外部信息与判断推理 | https://allenai.org/data/strategyqa |

---

## 🖼️ 多模态视觉推理（VQA / 图文逻辑）

| 数据集 | 简介 | 链接 |
|--------|------|------|
| **GQA** | 基于图像的结构化问答，测试空间逻辑与属性组合推理 | https://cs.stanford.edu/people/dorarad/gqa/ |
| **A-OKVQA** | 多模态常识问答（图+文本），要求模型具备知识迁移能力 | https://allenai.org/data/a-okvqa |
| **ScienceQA** | 包含图表/文本/语音，涵盖科学常识与因果推理 | https://github.com/lupantech/ScienceQA |
| **VCR** | Visual Commonsense Reasoning，多选题+解释（rationale）组合 | https://visualcommonsense.com/ |
| **CLEVR / CLEVR-HYP** | 人工构造图形与语言任务，适合因果、多跳、可解释性研究 | https://cs.stanford.edu/people/jcjohns/clevr/ |

---

## 🎬 视频推理与多模态时间序列理解

| 数据集 | 简介 | 链接 |
|--------|------|------|
| **Next-QA** | 视频中的因果关系推理与预测任务 | https://next-qas.github.io/ |
| **TVQA** | 基于字幕+画面联合推理的问题理解数据集 | http://tvqa.cs.unc.edu/ |
| **VideoCoT-QA** | CoT格式的视频问答数据，支持多轮可视推理 | https://github.com/Video-CoT/VideoCoT |

---

## 🧪 结构化逻辑推理数据（神经-符号方法适用）

| 数据集 | 简介 | 链接 |
|--------|------|------|
| **ProofWriter** | 合成的逻辑证明数据集，支持多步证明链 | https://github.com/allenai/proofwriter |
| **EntailmentBank** | 科学文本中的因果推理与蕴含链 | https://allenai.org/data/entailmentbank |
| **MathQA / DeepSeekMath** | 面向数学表达式推理，适用于程序生成 + 符号模块 | https://github.com/amazon-science/mathqa / https://github.com/deepseek-ai/DeepSeek-Math |

---

## ✅ 推荐使用方式

- 📥 可作为 pretraining / finetuning / evaluation 用途
- 🔧 建议结合 CoT/GRPO 结构化方法使用
- 🧠 可通过 prompt 编写或 symbolic 工具生成新变种

如有更多优质数据集推荐，欢迎通过 PR 提交至本文件 🙌