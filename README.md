# Awesome LLM Training & Inference

> Curated list of frameworks, tools, and resources for LLM training and inference. Covers the full pipeline from data processing to deployment.

[![License](https://img.shields.io/badge/license-CC0--1.0-blue)](LICENSE)

<!-- keywords: LLM, large language model, training, inference, deep learning, machine learning, PyTorch, transformers, distributed training, model serving -->

## Contents

- [Training Frameworks](#training-frameworks)
- [Inference Frameworks](#inference-frameworks)
- [Distributed Training](#distributed-training)
- [Model Compression & Quantization](#model-compression--quantization)
- [Data Processing](#data-processing)
- [Evaluation & Benchmarking](#evaluation--benchmarking)
- [Deployment & Serving](#deployment--serving)
- [Monitoring & Observability](#monitoring--observability)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)
- [License](#license)

---

## Training Frameworks

### Deep Learning Frameworks

| Framework | Stars | Description |
|-----------|-------|-------------|
| [PyTorch](https://github.com/pytorch/pytorch) | ![Stars](https://img.shields.io/github/stars/pytorch/pytorch) | Open source machine learning framework |
| [transformers](https://github.com/huggingface/transformers) | ![Stars](https://img.shields.io/github/stars/huggingface/transformers) | State-of-the-art ML for text, vision, audio |
| [JAX](https://github.com/google/jax) | ![Stars](https://img.shields.io/github/stars/google/jax) | Composable transformations for ML |
| [Flax](https://github.com/google/flax) | ![Stars](https://img.shields.io/github/stars/google/flax) | Neural network library for JAX |

### Training Libraries

| Framework | Stars | Description |
|-----------|-------|-------------|
| [Accelerate](https://github.com/huggingface/accelerate) | ![Stars](https://img.shields.io/github/stars/huggingface/accelerate) | Easy distributed training in PyTorch |
| [Lightning](https://github.com/Lightning-AI/pytorch-lightning) | ![Stars](https://img.shields.io/github/stars/Lightning-AI/pytorch-lightning) | Deep learning framework for scalable training |
| [DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | ![Stars](https://img.shields.io/github/stars/deepspeedai/DeepSpeed) | Deep learning optimization and RLHF training |
| [Fairscale](https://github.com/facebookresearch/fairscale) | ![Stars](https://img.shields.io/github/stars/facebookresearch/fairscale) | PyTorch extensions for high-performance training |

---

## Inference Frameworks

### High-Performance Inference

| Framework | Stars | Description |
|-----------|-------|-------------|
| [vLLM](https://github.com/vllm-project/vllm) | ![Stars](https://img.shields.io/github/stars/vllm-project/vllm) | High-throughput LLM inference engine |
| [SGLang](https://github.com/sgl-project/sglang) | ![Stars](https://img.shields.io/github/stars/sgl-project/sglang) | High-performance serving framework for LLMs |
| [Text Generation Inference](https://github.com/huggingface/text-generation-inference) | ![Stars](https://img.shields.io/github/stars/huggingface/text-generation-inference) | Hugging Face's production-ready inference server |
| [LightLLM](https://github.com/ModelTC/LightLLM) | ![Stars](https://img.shields.io/github/stars/ModelTC/LightLLM) | Lightweight LLM inference framework |
| [llama.cpp](https://github.com/ggerganov/llama.cpp) | ![Stars](https://img.shields.io/github/stars/ggerganov/llama.cpp) | LLM inference in C/C++ |
| [Ollama](https://github.com/ollama/ollama) | ![Stars](https://img.shields.io/github/stars/ollama/ollama) | Run LLMs locally |
| [ktransformers](https://github.com/kvcache-ai/ktransformers) | ![Stars](https://img.shields.io/github/stars/kvcache-ai/ktransformers) | Flexible framework for heterogeneous LLM inference optimizations |
| [GPUSstack](https://github.com/gpustack/gpustack) | ![Stars](https://img.shields.io/github/stars/gpustack/gpustack) | Performance-optimized AI inference on GPUs |
| [JetStream](https://github.com/AI-Hypercomputer/JetStream) | ![Stars](https://img.shields.io/github/stars/AI-Hypercomputer/JetStream) | Throughput-optimized engine for LLM inference on XLA devices |
| [NanoLLM](https://github.com/dusty-nv/NanoLLM) | ![Stars](https://img.shields.io/github/stars/dusty-nv/NanoLLM) | Optimized local inference with quantization and vision models |

### Local & Edge Inference

| Framework | Stars | Description |
|-----------|-------|-------------|
| [LM Studio](https://github.com/lmstudio-ai/lmstudio) | ![Stars](https://img.shields.io/github/stars/lmstudio-ai/lmstudio) | Discover and run local LLMs |
| [IPEX-LLM](https://github.com/intel/ipex-llm) | ![Stars](https://img.shields.io/github/stars/intel/ipex-llm) | Accelerate LLM inference on Intel hardware |

---

## Distributed Training

### Parallel Training Frameworks

| Framework | Stars | Description |
|-----------|-------|-------------|
| [DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | ![Stars](https://img.shields.io/github/stars/deepspeedai/DeepSpeed) | Distributed training with ZeRO optimization |
| [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) | ![Stars](https://img.shields.io/github/stars/NVIDIA/Megatron-LM) | Large-scale transformer training |
| [ColossalAI](https://github.com/hpcaitech/ColossalAI) | ![Stars](https://img.shields.io/github/stars/hpcaitech/ColossalAI) | Large-scale model training system |

### Training Optimizations

| Framework | Stars | Description |
|-----------|-------|-------------|
| [FlashAttention](https://github.com/Dao-AILab/flash-attention) | ![Stars](https://img.shields.io/github/stars/Dao-AILab/flash-attention) | Fast and memory-efficient attention |
| [xFormers](https://github.com/facebookresearch/xformers) | ![Stars](https://img.shields.io/github/stars/facebookresearch/xformers) | Modular components for transformers |

---

## Fine-Tuning & PEFT

### Parameter-Efficient Fine-Tuning

| Framework | Stars | Description |
|-----------|-------|-------------|
| [PEFT](https://github.com/huggingface/peft) | ![Stars](https://img.shields.io/github/stars/huggingface/peft) | State-of-the-art parameter-efficient fine-tuning |
| [LlamaFactory](https://github.com/hiyouga/LlamaFactory) | ![Stars](https://img.shields.io/github/stars/hiyouga/LlamaFactory) | Unified efficient fine-tuning of 100+ LLMs |
| [xTuring](https://github.com/stochasticai/xTuring) | ![Stars](https://img.shields.io/github/stars/stochasticai/xTuring) | Build, personalize and control your own LLMs |
| [Unsloth](https://github.com/unslothai/unsloth) | ![Stars](https://img.shields.io/github/stars/unslothai/unsloth) | Memory-efficient fine-tuning (2x faster, 70% less memory) |

### RLHF & Alignment

| Framework | Stars | Description |
|-----------|-------|-------------|
| [TRL](https://github.com/huggingface/trl) | ![Stars](https://img.shields.io/github/stars/huggingface/trl) | Train language models with RLHF and DPO |
| [DeepSpeed-Chat](https://github.com/microsoft/DeepSpeed) | ![Stars](https://img.shields.io/github/stars/microsoft/DeepSpeed) | Easy-to-use RLHF training pipeline |

---

## Model Compression & Quantization

### Quantization Tools

| Framework | Stars | Description |
|-----------|-------|-------------|
| [BitsAndBytes](https://github.com/TimDettmers/bitsandbytes) | ![Stars](https://img.shields.io/github/stars/TimDettmers/bitsandbytes) | 8-bit quantization for LLMs |
| [AWQ](https://github.com/mit-han-lab/awq) | ![Stars](https://img.shields.io/github/stars/mit-han-lab/awq) | Activation-aware weight quantization |
| [GPTQ](https://github.com/IST-DASLab/gptq) | ![Stars](https://img.shields.io/github/stars/IST-DASLab/gptq) | GPT post-training quantization |
| [GGML](https://github.com/ggerganov/ggml) | ![Stars](https://img.shields.io/github/stars/ggerganov/ggml) | Tensor library for ML |
| [exllamav2](https://github.com/turboderp-org/exllamav2) | ![Stars](https://img.shields.io/github/stars/turboderp-org/exllamav2) | Optimized quantization for running LLMs on consumer GPUs |

### Compression Frameworks

| Framework | Stars | Description |
|-----------|-------|-------------|
| [NNCF](https://github.com/openvinotoolkit/nncf) | ![Stars](https://img.shields.io/github/stars/openvinotoolkit/nncf) | Neural network compression framework |
| [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) | ![Stars](https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM) | NVIDIA's LLM inference optimization |
| [Optimum](https://github.com/huggingface/optimum) | ![Stars](https://img.shields.io/github/stars/huggingface/optimum) | Optimization tools for transformers |

---

## Data Processing

### Data Pipelines

| Framework | Stars | Description |
|-----------|-------|-------------|
| [DataLoader](https://github.com/pytorch/data) | ![Stars](https://img.shields.io/github/stars/pytorch/data) | Data loading utility for PyTorch |
| [Datasets](https://github.com/huggingface/datasets) | ![Stars](https://img.shields.io/github/stars/huggingface/datasets) | Public datasets for ML |
| [WebDataset](https://github.com/webdataset/webdataset) | ![Stars](https://img.shields.io/github/stars/webdataset/webdataset) | Large-scale dataset handling |
| [PyArrow](https://github.com/apache/arrow) | ![Stars](https://img.shields.io/github/stars/apache/arrow) | Columnar data format |

---

## Evaluation & Benchmarking

### Evaluation Frameworks

| Framework | Stars | Description |
|-----------|-------|-------------|
| [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | ![Stars](https://img.shields.io/github/stars/EleutherAI/lm-evaluation-harness) | LLM evaluation framework |
| [promptfoo](https://github.com/promptfoo/promptfoo) | ![Stars](https://img.shields.io/github/stars/promptfoo/promptfoo) | Test prompts and LLM outputs |
| [LangChain](https://github.com/langchain-ai/langchain) | ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain) | LLM application framework |

---

## Deployment & Serving

### Model Serving Platforms

| Framework | Stars | Description |
|-----------|-------|-------------|
| [Ray Serve](https://github.com/ray-project/ray) | ![Stars](https://img.shields.io/github/stars/ray-project/ray) | Scalable model serving |
| [TorchServe](https://github.com/pytorch/serve) | ![Stars](https://img.shields.io/github/stars/pytorch/serve) | PyTorch model serving |
| [Triton Inference Server](https://github.com/triton-inference-server/server) | ![Stars](https://img.shields.io/github/stars/triton-inference-server/server) | NVIDIA's inference server |
| [BentoML](https://github.com/bentoml/BentoML) | ![Stars](https://img.shields.io/github/stars/bentoml/BentoML) | Unified platform for AI apps |
| [ONNX Runtime](https://github.com/microsoft/onnxruntime) | ![Stars](https://img.shields.io/github/stars/microsoft/onnxruntime) | Cross-platform ML inference |
| [OpenVINO](https://github.com/openvinotoolkit/openvino) | ![Stars](https://img.shields.io/github/stars/openvinotoolkit/openvino) | Intel's inference optimization |

---

## Monitoring & Observability

### Training Monitoring

| Framework | Stars | Description |
|-----------|-------|-------------|
| [Weights & Biases](https://github.com/wandb/wandb) | ![Stars](https://img.shields.io/github/stars/wandb/wandb) | ML experiment tracking |
| [MLflow](https://github.com/mlflow/mlflow) | ![Stars](https://img.shields.io/github/stars/mlflow/mlflow) | ML lifecycle management |
| [TensorBoard](https://github.com/tensorflow/tensorboard) | ![Stars](https://img.shields.io/github/stars/tensorflow/tensorboard) | Visualization toolkit |
| [Aim](https://github.com/aimhubio/aim) | ![Stars](https://img.shields.io/github/stars/aimhubio/aim) | Self-hosted ML experiment tracker |

### Inference Monitoring

| Framework | Stars | Description |
|-----------|-------|-------------|
| [LangSmith](https://github.com/langchain-ai/langsmith) | ![Stars](https://img.shields.io/github/stars/langchain-ai/langsmith) | LLM application observability |
| [LangFuse](https://github.com/langfuse/langfuse) | ![Stars](https://img.shields.io/github/stars/langfuse/langfuse) | Open-source LLM engineering platform |
| [Phoenix](https://github.com/Arize-ai/phoenix) | ![Stars](https://img.shields.io/github/stars/Arize-ai/phoenix) | ML observability platform |
| [Helicone](https://github.com/Helicone/helicone) | ![Stars](https://img.shields.io/github/stars/Helicone/helicone) | Open-source LLM observability |

---

## Learning Resources

### Official Documentation

- [PyTorch Documentation](https://pytorch.org/docs/) - Deep learning framework docs
- [Hugging Face Docs](https://huggingface.co/docs) - Transformers and model hub
- [DeepSpeed Documentation](https://www.deepspeed.ai/getting-started/) - Distributed training
- [vLLM Documentation](https://docs.vllm.ai/) - Inference optimization

### Tutorials & Courses

- [DeepLearning.AI](https://www.deeplearning.ai/) - AI courses
- [Fast.ai](https://www.fast.ai/) - Practical deep learning
- [Lightning Academy](https://lightning.ai/pages/education/) - ML training courses

---

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## License

[CC0 1.0 Universal](LICENSE) - Free and open source.
