# 🧰 推理增强相关工具与平台（Tools for Reasoning Enhancement in MLLMs）

本页整理用于多模态大语言模型（MLLM）推理能力增强与评估的实用工具、框架与插件，涵盖思维链生成、符号推理模块、图工具链、评估指标脚本等。

---

## 🔧 结构化推理工具（逻辑链生成 / CoT）

| 工具名称 | 链接 | 简介 |
|----------|------|------|
| **Auto-CoT** | https://github.com/kojima-t/auto-cot | 自动生成 Chain-of-Thought 提示，无需人工标注 |
| **InstructZero** | https://github.com/txsun1997/InstructZero | 无监督指令生成用于推理任务的提示语 |
| **ReAct Prompt Generator** | https://github.com/ysymyth/ReAct | 结合工具使用与多步推理的提示模板构建器 |

---

## 🧠 神经符号与程序辅助模块

| 工具名称 | 链接 | 简介 |
|----------|------|------|
| **PAL (Program-Aided Language)** | https://github.com/heyytanay/pal | 使用 Python 程序辅助语言模型执行与推理 |
| **Prover9 + GPT** | https://www.cs.unm.edu/~mccune/prover9/ | 可与 GPT 结合用于生成逻辑证明链 |
| **ViperGPT** | https://github.com/StanfordVL/ViperGPT | 将视觉任务翻译为程序执行流，与 LLM 联合推理 |

---

## 📈 推理一致性与逻辑性评估工具

| 工具名称 | 链接 | 简介 |
|----------|------|------|
| **TruthfulQA Evaluator** | https://github.com/sylinrl/TruthfulQA | 用于评估模型回答的真实性与一致性 |
| **Faithfulness Checkers (ReACT-G)** | https://github.com/ysymyth/ReAct | 可选模块用于检测 CoT 逻辑链是否自洽 |
| **LogicCoT Benchmark Toolkits** | https://github.com/JiehongLin/Logic-COT | 提供形式逻辑题生成与评估脚本 |

---

## 🧪 可复现项目工具包 / Training Recipes

| 工具 | 链接 | 说明 |
|------|------|------|
| **GRPO 训练框架** | https://github.com/Luodian/Reinforced-CoT | 包含 CoT 强化学习训练与拒绝采样策略 |
| **VideoCoT 数据生成器** | https://github.com/Video-CoT/VideoCoT | 视频时序推理数据与测试脚本 |
| **MiniGPT-4 推理接口** | https://github.com/Vision-CAIR/MiniGPT-4 | 提供图文推理 + LoRA 微调接口 |

---

## 📬 欢迎补充与建议

如果你有更多工具推荐，欢迎通过 PR 或 issue 提交！

