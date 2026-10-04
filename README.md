# Qwen3.8

<div style="text-align: center">
  <p align="center">
    <a href="https://chat.qwen.ai/">💜 Qwen Studio</a> |
    <a href="https://huggingface.co/Qwen">🤗 Hugging Face</a> | 
    <a href="https://modelscope.cn/organization/qwen">🤖 ModelScope</a> | 
    <a href="https://github.com/QwenLM/Qwen/blob/main/assets/wechat.png">💬 WeChat (微信)</a> |
    <a href="https://discord.gg/CV4E9rpNSD">🫨 Discord</a>   
  </p>
</div>

Welcome to the GitHub repository of the Qwen3.5 open model series, including Qwen3.5, Qwen3.6, and the latest Qwen3.8. Here, you can find official information about Qwen3.8, post your questions ([Issues](https://github.com/QwenLM/Qwen3.8/issues)), and share your ideas with the community ([Discussions](https://github.com/QwenLM/Qwen3.8/discussions)).

## Introduction

### Qwen3.8

For the first time, Qwen3.8 brings a Qwen-Max-class model to open release. Built on the architectural foundation of Qwen3.5, Qwen3.8 delivers substantial gains across coding, professional work, research, and long-horizon agentic tasks. Beyond answering harder questions, Qwen3.8 is designed to carry complex, multi-step tasks through to completion with greater reliability.

Qwen3.8 features the following enhancements:
- **Core Capabilities**: Comprehensive improvements across coding, professional work, research, and long-horizon agentic tasks.
- **Agent Execution**: Stronger autonomous planning and better handling of environment feedback, leading to more reliable end-to-end task completion.
- **Downstream Compatibility**: Broader support for popular harnesses and development tools, making it easier to integrate into your existing stack.
- **Flexible Thinking Control**: Reasoning depth can be tuned with `reasoning_effort`, and reasoning context from historical messages is retained via `preserve_thinking`.

### Qwen3.6

Building upon the fundamental breakthroughs of Qwen3.5, Qwen3.6 prioritizes stability and real-world utility. It offers developers a more intuitive, responsive, and genuinely productive coding experience, shaped by direct community feedback. This update delivers substantial upgrades, particularly in:

- **Agentic Coding:** The model now handles front-end workflows and repository-level reasoning with greater fluency and precision.
- **Thinking Preservation:** A new feature retains thinking context across conversation history, streamlining iterative development and reducing overhead.

### Qwen3.5

Over recent months, we have intensified our focus on developing foundation models that deliver exceptional utility and performance. Qwen3.5 represents a significant leap forward, integrating breakthroughs in multimodal learning, architectural efficiency, reinforcement learning scale, and global accessibility to empower developers and enterprises with unprecedented capability and efficiency.

Qwen3.5 features the following enhancements:

- **Unified Vision-Language Foundation**: Early fusion training on trillions of multimodal tokens achieves cross-generational parity with Qwen3 and outperforms Qwen3-VL models across reasoning, coding, agents, and visual understanding benchmarks.
- **Efficient Hybrid Architecture**: Gated Delta Networks combined with sparse Mixture-of-Experts deliver high-throughput inference with minimal latency and cost overhead.
- **Scalable RL Generalization**: Reinforcement learning scaled across million-agent environments with progressively complex task distributions for robust real-world adaptability.
- **Global Linguistic Coverage**: Expanded support to 201 languages and dialects, enabling inclusive, worldwide deployment with nuanced cultural and regional understanding.
- **Next-Generation Training Infrastructure**: Near-100% multimodal training efficiency compared to text-only training and asynchronous RL frameworks supporting massive-scale agent scaffolds and environment orchestration.

## News

- 2026-08-14: Qwen3.8-27B is now available on [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen38) and [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen38). Read more on the model card.
- 2026-08-12: Qwen3.8-2.4T-A95B is now available on [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen38) and [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen38). Read more on the model card.
- 2026-04-22: Qwen3.6-27B is now available on [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen36) and [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen36). Read more on our [release blog](https://qwen.ai/blog?id=qwen3.6-27b)!
- 2026-04-16: Qwen3.6-35B-A3B is now available on [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen36) and [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen36). Read more on our [release blog](https://qwen.ai/blog?id=qwen3.6-35b-a3b)!
- 2026-03-02: Qwen3.5-9B, Qwen3.5-4B, Qwen3.5-2B, and Qwen3.5-0.8B are now available on [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen35) and [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen35)!
- 2026-02-24: Qwen3.5-122B-A10B, Qwen3.5-35B-A3B, and Qwen3.5-27B are released. Check out the model cards on [Hugging Face Hub](https://huggingface.co/collections/Qwen/qwen35) or [ModelScope](https://www.modelscope.cn/collections/Qwen/Qwen35) for more information!
- 2026-02-16: We release Qwen3.5. The first release includes a 397B-A17B MoE model. Read more on our [release blog](https://qwen.ai/blog?id=qwen3.5). More sizes are coming & Happy Chinese New Year!
- 2025-09-11: We release Qwen3-Next-80B-A3B, an ultra-sparse mixture-of-experts model with hybrid attention architecture, designed for extreme efficiency. Read more on our [blog](https://qwen.ai/blog?id=qwen3-next).

## Models

The official model weights are released on:
- [🤗Hugging Face Hub](https://huggingface.co/Qwen): Most LLM frameworks and applications support downloading model files from Hugging Face Hub automatically by specifying the model ID, e.g., `Qwen/Qwen3.8-27B`, `Qwen/Qwen3.6-35B-A3B`, and `Qwen/Qwen3.5-397B-A17B`.
  You can also download model files manually using `huggingface download` or `git clone`.
  Please follow the instructions on the model page.
- [🤖ModelScope](https://www.modelscope.cn/organization/Qwen): For users unable to access Hugging Face Hub, we strongly recommend using ModelScope.
  For supported frameworks, you can download from ModelScope by setting environment variables, such as `SGLANG_USE_MODELSCOPE=true` or `VLLM_USE_MODELSCOPE=true`.
  You can also download model files manually using `modelscope download` or `git clone`.
  Please follow the instructions on the model page.

## Benchmarks

**Qwen3.8 Open Models**

For detailed results, please check out the [Qwen3.8-2.4T-A95B Model Card](https://huggingface.co/Qwen/Qwen3.8-2.4T-A95B) and the [Qwen3.8-27B Model Card](https://huggingface.co/Qwen/Qwen3.8-27B).

**Qwen3.6 Open Models**

![Qwen3.6-27B Benchmark Results](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.6/Figures/qwen3.6_27b_score.png)

![Qwen3.6-35B-A3B Benchmark Results](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.6/Figures/qwen3.6_35b_a3b_score.png)

For detailed results, please check out the [Qwen3.6-35B-A3B blog](https://qwen.ai/blog?id=qwen3.6-35b-a3b) and the [Qwen3.6-27B blog](https://qwen.ai/blog?id=qwen3.6-27b).

**Qwen3.5 Open Models**

![Qwen3.5-397B-A17B Benchmark Results](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.5/Figures/qwen3.5_397b_a17b_score.png)

![Qwen3.5-122B-A10B, Qwen3.5-35B-A3B, and Qwen3.5-27B Benchmark Results](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.5/Figures/qwen3.5_middle_size_score.png)

![Qwen3.5-9B and Qwen3.5-4B Benchmark Results](https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3.5/Figures/qwen3.5_small_size_score.png)

For detailed results, please check out the [Qwen3.5 blog](https://qwen.ai/blog?id=qwen3.5).

## Quickstart

### Official

You can try Qwen3.8 on our official sites and enjoy the native experience with extra features, such as deep research, web dev, and adaptive tool use.

#### Qwen Studio

If you simply want to try Qwen3.8, [Qwen Studio](https://chat.qwen.ai) is an AI assistant for everyone. It’s free to use, open to all, and ready to help with creativity, collaboration, and endless possibilities.

#### Qoder

Qwen3.8 is now available directly on [Qoder](https://qoder.com/). Qoder is an agentic coding platform designed for real software development. Qoder is available as a standalone application. Follow [its documentation](https://docs.qoder.com/quick-start) to get started!

#### QwenWork

Qwen3.8 is now available directly on [QwenWork](https://qwenwork.cn). QwenWork is a one-stop AI working platform launched by Alibaba. Follow [its documentation](https://qwenwork.cn/docs/getting-started/basic-workflow) to get started!

#### Qwen API

[QwenCloud](https://www.qwencloud.com) provides first-class support for Qwen3.8, which is compatible with various API specifications, including OpenAI and Anthropic, making it simple for you to try Qwen3.8 in your own applications.

#### Qwen Code

[Qwen Code](https://qwen.ai/qwencode) is an open-source AI agent for the terminal, optimized for Qwen models. It helps you understand large codebases, automate tedious work, and ship faster. Follow [its documentation](https://qwenlm.github.io/qwen-code-docs/) to get started!

### Local Use

#### Hugging Face Transformers

[`transformers`](https://huggingface.co/docs/transformers) acts as the model-definition framework in the current open-weight LLM landscape.
It also includes functionalities for LLM inference and training. The addition of serving capabilities in `transformers` makes it much easier to integrate new models in your development.

To launch a server, simply use the `transformers serve` command:
```shell
transformers serve Qwen/Qwen3.8-27B --port 8000 --continuous-batching
```
An OpenAI-compatible API will be available at `http://localhost:8000/v1`.
See [the Serve CLI guide](https://huggingface.co/docs/transformers/serve-cli/serving) for more information.

#### llama.cpp

[`llama.cpp`](https://github.com/ggml-org/llama.cpp) enables LLM inference with minimal setup and state-of-the-art performance on a wide range of hardware.
llama.cpp supports the Qwen3.5 open model series (text & vision).
Look for models ending with GGUF on Hugging Face Hub.

#### MLX (Apple Silicon)

If you are running on Apple Silicon, both [`mlx-lm`](https://github.com/ml-explore/mlx-lm) (text-only) and [`mlx-vlm`](https://github.com/Blaizzy/mlx-vlm) (vision + text) support the Qwen3.5 open model series. Look for models ending with MLX on Hugging Face Hub.

#### Unsloth

[Unsloth](https://unsloth.ai) contains a local UI to run and train LLMs and diffusion models, including Qwen3.8 and more.
See [the Qwen3.8 guide](https://unsloth.ai/docs/models/qwen3.8) for running Qwen3.8 quants with Unsloth.

### Deployment

The Qwen3.5 open model series is supported by multiple inference frameworks.
Here we demonstrate the usage of SGLang, vLLM, and TokenSpeed.

#### SGLang

[SGLang](https://github.com/sgl-project/sglang) is a fast serving framework for large language models and vision language models.
SGLang can be used to launch a server with an OpenAI-compatible API service.

```shell
sglang serve --model-path Qwen/Qwen3.8-27B --port 8000 --tp-size 4 --context-length 262144 --reasoning-parser qwen3 --tool-call-parser qwen3_coder
```

An OpenAI-compatible API will be available at `http://localhost:8000/v1`.

Also see SGLang Cookbook on [serving Qwen3.8-27B](https://docs.sglang.io/cookbook/autoregressive/Qwen/Qwen3.8-27B).

#### vLLM

[vLLM](https://github.com/vllm-project/vllm) is a high-throughput and memory-efficient inference and serving engine for LLMs.
vLLM can be used to launch a server with an OpenAI-compatible API service.

```shell
vllm serve Qwen/Qwen3.8-27B --port 8000 --tensor-parallel-size 4 --max-model-len 262144 --reasoning-parser qwen3 --enable-auto-tool-choice --tool-call-parser qwen3_coder
```

An OpenAI-compatible API will be available at `http://localhost:8000/v1`.

Also see vLLM Recipes on [serving Qwen3.8-27B](https://recipes.vllm.ai/Qwen/Qwen3.8-27B).

#### TokenSpeed

[TokenSpeed](https://github.com/lightseekorg/tokenspeed) is a speed-of-light LLM inference engine.
TokenSpeed can be used to launch a server with an OpenAI-compatible API service.

```shell
tokenspeed serve Qwen/Qwen3.8-27B --port 8000 --tensor-parallel-size 4 --max-model-len 262144 --reasoning-parser qwen3 --enable-auto-tool-choice --tool-call-parser qwen3_coder
```

An OpenAI-compatible API will be available at `http://localhost:8000/v1`.

Also see TokenSpeed Recipes on [serving Qwen3.8-27B](https://lightseek.org/tokenspeed/recipes/models#qwen3-8-27b).

### Finetuning

We advise you to use training frameworks, including [Unsloth](https://github.com/unslothai/unsloth), [Swift](https://github.com/modelscope/swift), [Llama-Factory](https://github.com/hiyouga/LLaMA-Factory), to finetune your models with SFT, DPO, GRPO, etc.

## License Agreement

Please find the license file released with the model weights on Hugging Face Hub or ModelScope.

## Citation

If you find our work helpful, feel free to give us a cite.

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

## Contact Us

If you are interested in leaving a message to either our research team or product team, join our [Discord](https://discord.gg/CV4E9rpNSD) or [WeChat groups](https://github.com/QwenLM/Qwen/blob/main/assets/wechat.png)!
