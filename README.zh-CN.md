# Awesome LLM 训练与推理

> 精选的 LLM 训练与推理框架、工具和资源列表。涵盖从数据处理到部署的完整流程。

[![License](https://img.shields.io/badge/license-CC0--1.0-blue)](LICENSE)

[English](README.md) | 简体中文

<!-- keywords: LLM, 大语言模型, 训练, 推理, 深度学习, 机器学习, PyTorch, transformers, 分布式训练, 模型服务 -->

## 目录

- [训练框架](#训练框架)
- [推理框架](#推理框架)
- [分布式训练](#分布式训练)
- [模型压缩与量化](#模型压缩与量化)
- [数据处理](#数据处理)
- [评估与基准](#评估与基准)
- [部署与服务](#部署与服务)
- [监控与可观测性](#监控与可观测性)
- [学习资源](#学习资源)
- [贡献指南](#贡献指南)
- [许可证](#许可证)

---

## 训练框架

### 深度学习框架

| 框架 | Stars | 描述 |
|------|-------|------|
| [PyTorch](https://github.com/pytorch/pytorch) | ![Stars](https://img.shields.io/github/stars/pytorch/pytorch) | 开源机器学习框架 |
| [transformers](https://github.com/huggingface/transformers) | ![Stars](https://img.shields.io/github/stars/huggingface/transformers) | 先进的文本、视觉、音频 ML 框架 |
| [JAX](https://github.com/google/jax) | ![Stars](https://img.shields.io/github/stars/google/jax) | ML 可组合转换框架 |
| [Flax](https://github.com/google/flax) | ![Stars](https://img.shields.io/github/stars/google/flax) | 基于 JAX 的神经网络库 |

### 训练库

| 框架 | Stars | 描述 |
|------|-------|------|
| [Accelerate](https://github.com/huggingface/accelerate) | ![Stars](https://img.shields.io/github/stars/huggingface/accelerate) | PyTorch 分布式训练简化工具 |
| [Lightning](https://github.com/Lightning-AI/pytorch-lightning) | ![Stars](https://img.shields.io/github/stars/Lightning-AI/pytorch-lightning) | 可扩展训练的深度学习框架 |
| [DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | ![Stars](https://img.shields.io/github/stars/deepspeedai/DeepSpeed) | 深度学习优化库 |
| [Fairscale](https://github.com/facebookresearch/fairscale) | ![Stars](https://img.shields.io/github/stars/facebookresearch/fairscale) | PyTorch 高性能训练扩展 |

---

## 推理框架

### 高性能推理

| 框架 | Stars | 描述 |
|------|-------|------|
| [vLLM](https://github.com/vllm-project/vllm) | ![Stars](https://img.shields.io/github/stars/vllm-project/vllm) | 高吞吐量 LLM 推理引擎 |
| [SGLang](https://github.com/sgl-project/sglang) | ![Stars](https://img.shields.io/github/stars/sgl-project/sglang) | 高性能 LLM 服务框架 |
| [Text Generation Inference](https://github.com/huggingface/text-generation-inference) | ![Stars](https://img.shields.io/github/stars/huggingface/text-generation-inference) | Hugging Face 生产级推理服务器 |
| [LightLLM](https://github.com/ModelTC/LightLLM) | ![Stars](https://img.shields.io/github/stars/ModelTC/LightLLM) | 轻量级 LLM 推理框架 |
| [llama.cpp](https://github.com/ggerganov/llama.cpp) | ![Stars](https://img.shields.io/github/stars/ggerganov/llama.cpp) | C/C++ LLM 推理 |
| [Ollama](https://github.com/ollama/ollama) | ![Stars](https://img.shields.io/github/stars/ollama/ollama) | 本地运行 LLM |

### 本地与边缘推理

| 框架 | Stars | 描述 |
|------|-------|------|
| [LM Studio](https://github.com/lmstudio-ai/lmstudio) | ![Stars](https://img.shields.io/github/stars/lmstudio-ai/lmstudio) | 发现并运行本地 LLM |
| [IPEX-LLM](https://github.com/intel/ipex-llm) | ![Stars](https://img.shields.io/github/stars/intel/ipex-llm) | Intel 硬件上的 LLM 推理加速 |

---

## 分布式训练

### 并行训练框架

| 框架 | Stars | 描述 |
|------|-------|------|
| [DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | ![Stars](https://img.shields.io/github/stars/deepspeedai/DeepSpeed) | ZeRO 优化的分布式训练 |
| [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) | ![Stars](https://img.shields.io/github/stars/NVIDIA/Megatron-LM) | 大规模 Transformer 训练 |
| [ColossalAI](https://github.com/hpcaitech/ColossalAI) | ![Stars](https://img.shields.io/github/stars/hpcaitech/ColossalAI) | 大规模模型训练系统 |

### 训练优化

| 框架 | Stars | 描述 |
|------|-------|------|
| [FlashAttention](https://github.com/Dao-AILab/flash-attention) | ![Stars](https://img.shields.io/github/stars/Dao-AILab/flash-attention) | 快速且内存高效的注意力机制 |
| [xFormers](https://github.com/facebookresearch/xformers) | ![Stars](https://img.shields.io/github/stars/facebookresearch/xformers) | Transformer 模块化组件 |

---

## 模型压缩与量化

### 量化工具

| 框架 | Stars | 描述 |
|------|-------|------|
| [BitsAndBytes](https://github.com/TimDettmers/bitsandbytes) | ![Stars](https://img.shields.io/github/stars/TimDettmers/bitsandbytes) | LLM 8-bit 量化 |
| [AWQ](https://github.com/mit-han-lab/awq) | ![Stars](https://img.shields.io/github/stars/mit-han-lab/awq) | 激活感知权重量化 |
| [GPTQ](https://github.com/IST-DASLab/gptq) | ![Stars](https://img.shields.io/github/stars/IST-DASLab/gptq) | GPT 后训练量化 |
| [GGML](https://github.com/ggerganov/ggml) | ![Stars](https://img.shields.io/github/stars/ggerganov/ggml) | ML 张量库 |

### 压缩框架

| 框架 | Stars | 描述 |
|------|-------|------|
| [NNCF](https://github.com/openvinotoolkit/nncf) | ![Stars](https://img.shields.io/github/stars/openvinotoolkit/nncf) | 神经网络压缩框架 |
| [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) | ![Stars](https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM) | NVIDIA LLM 推理优化 |
| [Optimum](https://github.com/huggingface/optimum) | ![Stars](https://img.shields.io/github/stars/huggingface/optimum) | Transformers 优化工具 |

---

## 数据处理

### 数据管道

| 框架 | Stars | 描述 |
|------|-------|------|
| [DataLoader](https://github.com/pytorch/data) | ![Stars](https://img.shields.io/github/stars/pytorch/data) | PyTorch 数据加载工具 |
| [Datasets](https://github.com/huggingface/datasets) | ![Stars](https://img.shields.io/github/stars/huggingface/datasets) | ML 公共数据集 |
| [WebDataset](https://github.com/webdataset/webdataset) | ![Stars](https://img.shields.io/github/stars/webdataset/webdataset) | 大规模数据集处理 |
| [PyArrow](https://github.com/apache/arrow) | ![Stars](https://img.shields.io/github/stars/apache/arrow) | 列式数据格式 |

---

## 评估与基准

### 评估框架

| 框架 | Stars | 描述 |
|------|-------|------|
| [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | ![Stars](https://img.shields.io/github/stars/EleutherAI/lm-evaluation-harness) | LLM 评估框架 |
| [promptfoo](https://github.com/promptfoo/promptfoo) | ![Stars](https://img.shields.io/github/stars/promptfoo/promptfoo) | 测试 prompts 和 LLM 输出 |
| [LangChain](https://github.com/langchain-ai/langchain) | ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain) | LLM 应用框架 |

---

## 部署与服务

### 模型服务平台

| 框架 | Stars | 描述 |
|------|-------|------|
| [Ray Serve](https://github.com/ray-project/ray) | ![Stars](https://img.shields.io/github/stars/ray-project/ray) | 可扩展模型服务 |
| [TorchServe](https://github.com/pytorch/serve) | ![Stars](https://img.shields.io/github/stars/pytorch/serve) | PyTorch 模型服务 |
| [Triton Inference Server](https://github.com/triton-inference-server/server) | ![Stars](https://img.shields.io/github/stars/triton-inference-server/server) | NVIDIA 推理服务器 |
| [BentoML](https://github.com/bentoml/BentoML) | ![Stars](https://img.shields.io/github/stars/bentoml/BentoML) | AI 应用统一平台 |
| [ONNX Runtime](https://github.com/microsoft/onnxruntime) | ![Stars](https://img.shields.io/github/stars/microsoft/onnxruntime) | 跨平台 ML 推理 |
| [OpenVINO](https://github.com/openvinotoolkit/openvino) | ![Stars](https://img.shields.io/github/stars/openvinotoolkit/openvino) | Intel 推理优化 |

---

## 监控与可观测性

### 训练监控

| 框架 | Stars | 描述 |
|------|-------|------|
| [Weights & Biases](https://github.com/wandb/wandb) | ![Stars](https://img.shields.io/github/stars/wandb/wandb) | ML 实验跟踪 |
| [MLflow](https://github.com/mlflow/mlflow) | ![Stars](https://img.shields.io/github/stars/mlflow/mlflow) | ML 生命周期管理 |
| [TensorBoard](https://github.com/tensorflow/tensorboard) | ![Stars](https://img.shields.io/github/stars/tensorflow/tensorboard) | 可视化工具包 |
| [Aim](https://github.com/aimhubio/aim) | ![Stars](https://img.shields.io/github/stars/aimhubio/aim) | 自托管 ML 实验跟踪器 |

### 推理监控

| 框架 | Stars | 描述 |
|------|-------|------|
| [LangSmith](https://github.com/langchain-ai/langsmith) | ![Stars](https://img.shields.io/github/stars/langchain-ai/langsmith) | LLM 应用可观测性 |
| [LangFuse](https://github.com/langfuse/langfuse) | ![Stars](https://img.shields.io/github/stars/langfuse/langfuse) | 开源 LLM 工程平台 |
| [Phoenix](https://github.com/Arize-ai/phoenix) | ![Stars](https://img.shields.io/github/stars/Arize-ai/phoenix) | ML 可观测性平台 |
| [Helicone](https://github.com/Helicone/helicone) | ![Stars](https://img.shields.io/github/stars/Helicone/helicone) | 开源 LLM 可观测性 |

---

## 学习资源

### 官方文档

- [PyTorch 文档](https://pytorch.org/docs/) - 深度学习框架文档
- [Hugging Face 文档](https://huggingface.co/docs) - Transformers 和模型中心
- [DeepSpeed 文档](https://www.deepspeed.ai/getting-started/) - 分布式训练
- [vLLM 文档](https://docs.vllm.ai/) - 推理优化

### 教程与课程

- [DeepLearning.AI](https://www.deeplearning.ai/) - AI 课程
- [Fast.ai](https://www.fast.ai/) - 实践深度学习
- [Lightning Academy](https://lightning.ai/pages/education/) - ML 训练课程

---

## 贡献指南

欢迎贡献！请阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 了解指南。

## 许可证

[CC0 1.0 Universal](LICENSE) - 免费和开源。
