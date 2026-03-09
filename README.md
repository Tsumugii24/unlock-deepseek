 <div align='center'>
    <img src="assets/logo.png" alt="logo" width="800"/>
  <h1>Unlock DeepSeek</h1>
  <h3>DeepSeek系列论文解读和动手复现</h3>
  <p><em>面向广泛 AI 研究者群体的 DeepSeek 系列工作解读、扩展和复现。致力于传播 DeepSeek 在 AGI 实践之路上的前沿创新性成果。</em></p>
  <img src="https://img.shields.io/github/stars/datawhalechina/unlock-deepseek?style=flat&logo=github" alt="GitHub stars"/>
  <a rel="License" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="License" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a>
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue.svg" alt="Python"/>
  <a href="https://datawhalechina.github.io/unlock-deepseek/"><img src="https://img.shields.io/badge/在线阅读-Online%20Reading-green?style=flat&logo=gitbook" alt="Online Reading"></a>
     <h4 align="center">
        <b>简体中文</b> | <a href="https://github.com/datawhalechina/unlock-deepseek/blob/main/README_en.md">English</a>
	</h4>
</div>




---



## 📖 项目简介

**Unlock DeepSeek** 是一个面向广大 AI 研究者和学习者的开源学习项目，致力于对 DeepSeek 系列论文进行**系统性解读**与**动手复现**。项目涵盖 DeepSeek 在通用大语言模型、数学推理、代码生成、多模态、推理模型（如 DeepSeek-R1）以及 MoE 架构、训练基础设施等方向的创新成果，旨在将 DeepSeek 在 AGI 实践之路上的前沿技术拆解为可理解、可复现的学习内容。

**核心特色：**
- **论文精读**：从 DeepSeek-LLM 到 DeepSeek-V3.2、DeepSeek-Math、DeepSeek-Coder、DeepSeek-VL 等全系列技术报告的系统解读
- **动手实践**：提供从零开始的复现教程与代码，支持中文社区本地化复现（如 DeepSeek-R1 等）
- **技术拆解**：聚焦 MoE 架构、模型推理与强化学习、数据与 Infra 等关键要素
- **横向对比**：引入 Kimi, GLM, MiniMax 等同类工作比较，呈现 AGI 路径上的不同技术路线

**目标读者**：具备大语言模型基础知识和大学数学水平的初学者、希望深入理解深度推理的学习者，以及希望将推理模型应用于实际工作的从业者。

**项目当前处于⚠️ Alpha内测版本，尚不完整且可能存在错误。**


## 📚 结构预览

<div align="center">

| 章节                                                    | 摘要                         | 状态 |
| ------------------------------------------------------- | ---------------------------- | ---- |
| [引言]()          | 项目概述以及学习建议         | ✅    |
| **通用大语言模型**      |          |     |
| [DeepSeek-LLM]()                  | Scaling Open-Source Language Models with Longtermism     | 🚧    |
| [DeepSeekMoE]()          | Towards Ultimate Expert Specialization in Mixture-of-Experts Language Models   | 🚧    |
| [DeepSeek-V2]()      | A Strong, Economical, and Efficient Mixture-of-Experts Language Model        | 🚧    |
| [DeepSeek-V3]()            | DeepSeek-V3 Technical Report | 🚧    |
| [DeepSeek-V3.2]()          | Pushing the Frontier of Open Large Language Models       | 🚧    |
| [DeepSeek-V3.2-Exp]()          | Boosting Long-Context Efficiency with DeepSeek Sparse Attention       | 🚧    |
| **数学**      |          |     |
| [DeepSeek-Math]()             | Pushing the Limits of Mathematical Reasoning in Open Language Models   | 🚧    |
| [DeepSeek-Math-V2]()             | Towards Self-Verifiable Mathematical Reasoning   | 🚧    |
| [DeepSeek-Prover]()                | Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data       | 🚧    |
| [DeepSeek-Prover-V1.5]()                | Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search       | 🚧    |
| [DeepSeek-Prover-V2]()                | Advancing Formal Mathematical Reasoning via Reinforcement Learning for Subgoal Decomposition       | 🚧    |
| **代码**      |          |     |
| [DeepSeek-Coder]()        | Let the Code Write Itself       | 🚧    |
| [DeepSeek-Coder-V2]()       | Breaking the Barrier of Closed-Source Models in Code Intelligence   | 🚧    |
| **多模态**      |          |     |
| [DeepSeek-OCR]() | Contexts Optical Compression       | 🚧    |
| [DeepSeek-OCR-2]() | Visual Causal Flow       | 🚧    |
| [DeepSeek-VL]() | Towards Real-World Vision-Language Understanding       | 🚧    |
| [DeepSeek-VL2]() | Mixture-of-Experts Vision-Language Models for Advanced Multimodal Understanding       | 🚧    |
| [Janus]() | Decoupling visual encoding for unified multimodal understanding and generation       | 🚧    |
| [JanusFlow]() | Harmonizing Autoregression and Rectified Flow for Unified Multimodal Understanding and Generation       | 🚧    |
| [Janus-Pro]() | Unified Multimodal Understanding and Generation with Data and Model Scaling       | 🚧    |
| **推理模型/强化学习**      |          |     |
| [DeepSeek-R1](./DeepSeek-R1/) | Incentivizing Reasoning Capability in LLMs via Reinforcement Learning       | ✅   |
| **模型架构与训练方法**      |          |     |
| [Engram]() | Conditional Memory via Scalable Lookup       | 🚧    |
| [mHC]() | Manifold-Constrained Hyper-Connections       | 🚧    |
| [FlashMLA]() | Efficient Multi-head Latent Attention Kernels       | 🚧    |
| [LPLB]() | Linear-Programming-Based Load Balancer       | 🚧    |
| [ESFT]() | Expert-Specialized Fine-Tuning for Sparse Architectural Large Language Models       | 🚧    |
| **INFRA**      |          |     |
| [DualPipe]() |        | 🚧    |
| [3FS]() |        | 🚧    |
| [DeepEP]() |        | 🚧    |
| [DeepGEMM]() |        | 🚧    |
| **附录**      |          |     |
| [附录内容]() |        | ✅    |

</div>

## 🤝 项目成员

感谢以下项目的核心贡献者，排名不分先后

- [骆秀韬 - 项目负责人](https://github.com/anine09) （似然实验室）
- [姜舒凡 - 项目负责人](https://github.com/Tsumugii24) （Datawhale 成员）
- [邓恺俊](https://github.com/kedreamix) （深圳大学）
- [陈嘉诺](https://github.com/Tangent-90C) （广州大学）
- [林景豪](https://github.com/linjh1118)  （智谱）



## 🙏 致谢

本项目受益于 [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1), [Open-R1](https://github.com/huggingface/open-r1), [transformers](https://github.com/huggingface/transformers), [pytorch](https://github.com/pytorch/pytorch), [flash-attn](https://github.com/Dao-AILab/flash-attention), [trl](https://github.com/huggingface/trl), [mini-deepseek-r1](https://www.philschmid.de/mini-deepseek-r1), [TinyZero](https://github.com/Jiayi-Pan/TinyZero), [modelscope](https://github.com/modelscope/modelscope), [vllm](https://github.com/vllm-project/vllm) 感谢以上开源项目的杰出工作！



## 📜 开源协议

项目采用[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议](http://creativecommons.org/licenses/by-nc-sa/4.0/)进行许可。
