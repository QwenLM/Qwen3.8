# Qwen3.8

<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README.zh-CN.md">简体中文</a>
</p>

<div style="text-align: center">
  <p align="center">
    <a href="https://chat.qwen.ai/">💜 Qwen Studio</a> |
    <a href="https://huggingface.co/Qwen">🤗 Hugging Face</a> | 
    <a href="https://modelscope.cn/organization/qwen">🤖 ModelScope</a> | 
    <a href="https://github.com/QwenLM/Qwen/blob/main/assets/wechat.png">💬 微信</a> |
    <a href="https://discord.gg/CV4E9rpNSD">🫨 Discord</a>   
  </p>
</div>

欢迎来到 Qwen3.5 开源模型系列的 GitHub 仓库，其中包括 Qwen3.5、Qwen3.6 以及最新的 Qwen3.8。在这里，你可以找到关于 Qwen3.8 的官方信息、提出你的问题（[Issues](https://github.com/QwenLM/Qwen3.8/issues)），并与社区分享你的想法（[Discussions](https://github.com/QwenLM/Qwen3.8/discussions)）。

## 简介

### Qwen3.8

Qwen3.8 首次将 Qwen-Max 级别的模型开源发布。在 Qwen3.5 的架构基础之上，Qwen3.8 在编程、专业工作、研究以及长程智能体任务方面均取得了大幅提升。除了回答更困难的问题之外，Qwen3.8 的设计目标是更可靠地将复杂的多步骤任务执行到底。

Qwen3.8 具有以下增强特性：
- **核心能力**：在编程、专业工作、研究以及长程智能体任务上全面提升。
- **智能体执行**：更强的自主规划能力以及对环境反馈的更好处理，带来更可靠的端到端任务完成度。
- **下游兼容性**：对主流 harness 与开发工具提供更广泛的支持，使其更易于集成到你现有的技术栈中。
- **灵活的思考控制**：可通过 `reasoning_effort` 调节推理深度，并通过 `preserve_thinking` 保留历史消息中的推理上下文。

### Qwen3.6

在 Qwen3.5 的根本性突破之上，Qwen3.6 以稳定性与实际可用性为优先。它依托社区的直接反馈，为开发者带来更直观、更响应迅速、并真正高效的编程体验。本次更新带来了大幅升级，尤其是在以下方面：

- **智能体编程（Agentic Coding）**：模型现在能够更流畅、更精确地处理前端工作流与仓库级推理。
- **思考保留（Thinking Preservation）**：新增功能可在对话历史中保留思考上下文，从而简化迭代开发流程并降低额外开销。

### Qwen3.5

在近几个月里，我们加大了对基础模型的研发投入，以交付卓越的实用性与性能。Qwen3.5 是一次重大飞跃，融合了多模态学习、架构效率、强化学习规模化和全球可访问性等方面的突破，为开发者和企业带来前所未有的能力与效率。

Qwen3.5 具有以下增强特性：

- **统一视觉-语言基础模型**：在数万亿多模态 token 上进行早期融合训练，在推理、编程、智能体和视觉理解等基准测试中达到与 Qwen3 同代相当的水平，并优于 Qwen3-VL 系列模型。
- **高效混合架构**：门控 Delta 网络（Gated Delta Networks）结合稀疏混合专家（MoE），实现高吞吐推理，并将延迟与成本开销降至最低。
- **可扩展的强化学习泛化能力**：强化学习在数百万智能体环境中规模化扩展，任务分布逐步复杂化，具备稳健的真实世界适应能力。
- **全球语言覆盖**：支持的语言和方言扩展至 201 种，可支持包容性的全球部署，并具备对文化与区域差异的细致理解。
- **新一代训练基础设施**：相比纯文本训练，多模态训练效率接近 100%；异步强化学习框架支持大规模智能体脚手架与环境编排。

## 最新动态

- 2026-08-14：Qwen3.8-27B 现已在 [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen38) 和 [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen38) 上发布。更多信息请参阅模型卡片。
- 2026-08-12：Qwen3.8-2.4T-A95B 现已在 [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen38) 和 [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen38) 上发布。更多信息请参阅模型卡片。
- 2026-04-22：Qwen3.6-27B 现已在 [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen36) 和 [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen36) 上发布。详情请阅读我们的[发布博客](https://qwen.ai/blog?id=qwen3.6-27b)！
- 2026-04-16：Qwen3.6-35B-A3B 现已在 [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen36) 和 [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen36) 上发布。详情请阅读我们的[发布博客](https://qwen.ai/blog?id=qwen3.6-35b-a3b)！
- 2026-03-02：Qwen3.5-9B、Qwen3.5-4B、Qwen3.5-2B 和 Qwen3.5-0.8B 现已在 [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen35) 和 [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen35) 上发布！
- 2026-02-24：Qwen3.5-122B-A10B、Qwen3.5-35B-A3B 和 Qwen3.5-27B 正式发布。请查看 [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen35) 或 [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen35) 上的模型卡片以获取更多信息！
- 2026-02-16：我们发布了 Qwen3.5。首个版本包含一个 397B-A17B 的 MoE 模型。详情请阅读我们的[发布博客](https://qwen.ai/blog?id=qwen3.5)。更多规格即将推出，新年快乐！
- 2025-09-11：我们发布了 Qwen3-Next-80B-A3B，这是一个采用混合注意力架构的超稀疏混合专家模型，专为极致效率而设计。详情请阅读我们的[博客](https://qwen.ai/blog?id=qwen3-next)。

## 模型

官方模型权重发布于：

- [🤗Hugging Face Hub](https://huggingface.co/Qwen)：大多数 LLM 框架与应用都支持通过指定模型 ID（例如 `Qwen/Qwen3.8-27B`、`Qwen/Qwen3.6-35B-A3B` 和 `Qwen/Qwen3.5-397B-A17B`）自动从 Hugging Face Hub 下载模型文件。
  你也可以使用 `huggingface download` 或 `git clone` 手动下载模型文件。
  请遵循模型页面上的说明操作。
- [🤖ModelScope](https://www.modelscope.cn/organization/Qwen)：对于无法访问 Hugging Face Hub 的用户，我们强烈推荐使用 ModelScope。
  对于受支持的框架，你可以通过设置环境变量（例如 `SGLANG_USE_MODELSCOPE=true` 或 `VLLM_USE_MODELSCOPE=true`）从 ModelScope 下载。
  你也可以使用 `modelscope download` 或 `git clone` 手动下载模型文件。
  请遵循模型页面上的说明操作。

## 基准测试

**Qwen3.8 开源模型**

详细结果请查看 [Qwen3.8-2.4T-A95B 模型卡片](https://huggingface.co/Qwen/Qwen3.8-2.4T-A95B) 和 [Qwen3.8-27B 模型卡片](https://huggingface.co/Qwen/Qwen3.8-27B)。

**Qwen3.6 开源模型**

![Qwen3.6-27B 基准测试结果](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.6/Figures/qwen3.6_27b_score.png)

![Qwen3.6-35B-A3B 基准测试结果](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.6/Figures/qwen3.6_35b_a3b_score.png)

详细结果请查看 [Qwen3.6-35B-A3B 博客](https://qwen.ai/blog?id=qwen3.6-35b-a3b) 和 [Qwen3.6-27B 博客](https://qwen.ai/blog?id=qwen3.6-27b)。

**Qwen3.5 开源模型**

![Qwen3.5-397B-A17B 基准测试结果](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.5/Figures/qwen3.5_397b_a17b_score.png)

![Qwen3.5-122B-A10B、Qwen3.5-35B-A3B 和 Qwen3.5-27B 基准测试结果](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.5/Figures/qwen3.5_middle_size_score.png)

![Qwen3.5-9B 和 Qwen3.5-4B 基准测试结果](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.5/Figures/qwen3.5_small_size_score.png)

详细结果请查看 [Qwen3.5 博客](https://qwen.ai/blog?id=qwen3.5)。

## 快速开始

### 官方渠道

你可以在我们的官方网站上试用 Qwen3.8，体验原生功能以及深度研究、网页开发、自适应工具调用等额外特性。

#### Qwen Studio

如果你只是想试试 Qwen3.8，[Qwen Studio](https://chat.qwen.ai) 是一个面向所有人的 AI 助手。它免费使用、对所有人开放，随时为创意、协作以及无限可能提供帮助。

#### Qoder

Qwen3.8 现已直接上线 [Qoder](https://qoder.com/)。Qoder 是一个面向真实软件开发的智能体编程平台。Qoder 提供独立应用程序，请遵循[其文档](https://docs.qoder.com/quick-start)开始使用！

#### QwenWork

Qwen3.8 现已直接上线 [QwenWork](https://qwenwork.cn)。QwenWork 是阿里巴巴推出的一站式 AI 工作平台。请遵循[其文档](https://qwenwork.cn/docs/getting-started/basic-workflow)开始使用！

#### Qwen API

[QwenCloud](https://www.qwencloud.com) 为 Qwen3.8 提供一流的支持，兼容包括 OpenAI 和 Anthropic 在内的多种 API 规范，让你可以轻松地在自己的应用中试用 Qwen3.8。

#### Qwen Code

[Qwen Code](https://qwen.ai/qwencode) 是一个面向终端、针对 Qwen 模型优化的开源 AI 智能体。它可以帮助你理解大型代码库、自动化繁琐工作，并更快地交付成果。请遵循[其文档](https://qwenlm.github.io/qwen-code-docs/)开始使用！

### 本地使用

#### Hugging Face Transformers

在当前的开源权重 LLM 生态中，[`transformers`](https://huggingface.co/docs/transformers) 充当模型定义框架。
它还包含 LLM 推理与训练功能。`transformers` 中新增的服务能力使在你的开发中集成新模型变得更加容易。

要启动服务，只需使用 `transformers serve` 命令：
```shell
transformers serve Qwen/Qwen3.8-27B --port 8000 --continuous-batching
```
一个兼容 OpenAI 的 API 将在 `http://localhost:8000/v1` 上提供。
更多信息请参阅 [Serve CLI 指南](https://huggingface.co/docs/transformers/serve-cli/serving)。

#### llama.cpp

[`llama.cpp`](https://github.com/ggml-org/llama.cpp) 可在各类硬件上以最少的配置和业界领先的性能实现 LLM 推理。
llama.cpp 支持 Qwen3.5 开源模型系列（文本与视觉）。
请在 Hugging Face Hub 上查找以 GGUF 结尾的模型。

#### MLX（Apple Silicon）

如果你在 Apple Silicon 上运行，[`mlx-lm`](https://github.com/ml-explore/mlx-lm)（仅文本）和 [`mlx-vlm`](https://github.com/Blaizzy/mlx-vlm)（视觉 + 文本）均支持 Qwen3.5 开源模型系列。请在 Hugging Face Hub 上查找以 MLX 结尾的模型。

#### Unsloth

[Unsloth](https://unsloth.ai) 包含一个本地 UI，可用于运行和训练 LLM 与扩散模型，包括 Qwen3.8 等。
请参阅 [Qwen3.8 指南](https://unsloth.ai/docs/models/qwen3.8)，了解如何使用 Unsloth 运行 Qwen3.8 量化版本。

### 部署

Qwen3.5 开源模型系列受多种推理框架支持。
这里我们演示 SGLang、vLLM 和 TokenSpeed 的用法。

#### SGLang

[SGLang](https://github.com/sgl-project/sglang) 是一个面向大语言模型与视觉语言模型的快速服务框架。
SGLang 可用于启动提供兼容 OpenAI 的 API 服务的服务器。

```shell
sglang serve --model-path Qwen/Qwen3.8-27B --port 8000 --tp-size 4 --context-length 262144 --reasoning-parser qwen3 --tool-call-parser qwen3_coder
```

一个兼容 OpenAI 的 API 将在 `http://localhost:8000/v1` 上提供。

另请参阅 SGLang Cookbook 中关于[部署 Qwen3.8](https://docs.sglang.io/cookbook/autoregressive/Qwen/Qwen3.8) 的内容。

#### vLLM

[vLLM](https://github.com/vllm-project/vllm) 是一个面向 LLM 的高吞吐、内存高效的推理与服务引擎。
vLLM 可用于启动提供兼容 OpenAI 的 API 服务的服务器。

```shell
vllm serve Qwen/Qwen3.8-27B --port 8000 --tensor-parallel-size 4 --max-model-len 262144 --reasoning-parser qwen3 --enable-auto-tool-choice --tool-call-parser qwen3_coder
```

一个兼容 OpenAI 的 API 将在 `http://localhost:8000/v1` 上提供。

另请参阅 vLLM Recipes 中关于[部署 Qwen3.8](https://recipes.vllm.ai/Qwen) 的内容。

#### TokenSpeed

[TokenSpeed](https://github.com/lightseekorg/tokenspeed) 是一个光速级 LLM 推理引擎。
TokenSpeed 可用于启动提供兼容 OpenAI 的 API 服务的服务器。

```shell
tokenspeed serve Qwen/Qwen3.8-27B --port 8000 --tensor-parallel-size 4 --max-model-len 262144 --reasoning-parser qwen3 --enable-auto-tool-choice --tool-call-parser qwen3_coder
```

一个兼容 OpenAI 的 API 将在 `http://localhost:8000/v1` 上提供。

另请参阅 TokenSpeed Recipes 中关于[部署 Qwen3.8](https://lightseek.org/tokenspeed/recipes/models#qwen3-8) 的内容。

### 微调

我们建议使用训练框架，包括 [Unsloth](https://github.com/unslothai/unsloth)、[Swift](https://github.com/modelscope/swift)、[Llama-Factory](https://github.com/hiyouga/LLaMA-Factory)，通过 SFT、DPO、GRPO 等方式对你的模型进行微调。

## 许可协议

请查阅随模型权重一同发布在 Hugging Face Hub 或 ModelScope 上的许可文件。

## 引用

如果你觉得我们的工作有帮助，欢迎引用。

```bibtex
@misc{qwen3.8,
    title  = {{Qwen3.8-Max}: A New Bar for Coding and Cowork},
    author = {{Qwen Team}},
    year   = {2026},
    month  = {August},
    url    = {https://qwen.ai/blog?id=qwen3.8}
}

@misc{qwen3.6-27b,
    title  = {{Qwen3.6-27B}: Flagship-Level Coding in a {27B} Dense Model},
    author = {{Qwen Team}},
    year   = {2026},
    month  = {April},
    url    = {https://qwen.ai/blog?id=qwen3.6-27b}
}

@misc{qwen3.6-35b-a3b,
    title  = {{Qwen3.6-35B-A3B}: Agentic Coding Power, Now Open to All},
    author = {{Qwen Team}},
    year   = {2026},
    month  = {April},
    url    = {https://qwen.ai/blog?id=qwen3.6-35b-a3b}
}

@misc{qwen3.5,
    title  = {{Qwen3.5}: Towards Native Multimodal Agents},
    author = {{Qwen Team}},
    year   = {2026},
    month  = {February},
    url    = {https://qwen.ai/blog?id=qwen3.5}
}
```

## 联系我们

如果你有兴趣给我们的研究团队或产品团队留言，欢迎加入我们的 [Discord](https://discord.gg/CV4E9rpNSD) 或[微信群](https://github.com/QwenLM/Qwen/blob/main/assets/wechat.png)！
