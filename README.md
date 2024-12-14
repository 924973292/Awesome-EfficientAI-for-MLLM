# Awesome EfficientAI for MLLM

A curated list of awesome resources, research papers, and tools for optimizing and efficiently utilizing Multi-Large Language Models (MLLMs). This repository is designed to serve as a one-stop resource hub for developers, researchers, and enthusiasts aiming to build efficient AI solutions.

---

## 📖 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Categories](#categories)
  - [Optimization Techniques](#optimization-techniques)
  - [Model Compression](#model-compression)
  - [Deployment and Acceleration](#deployment-and-acceleration)
  - [Multimodal Integration](#multimodal-integration)
- [Community](#community)
- [How to Contribute](#how-to-contribute)
- [License](#license)

---

## Introduction

The rise of large language models (LLMs) like GPT, BERT, and LLaMA has brought new challenges in efficiently deploying and utilizing these models. **Awesome EfficientAI for MLLM** compiles state-of-the-art research and tools to help:

- **Optimize Costs**: Reduce computational resource requirements for training and inference.
- **Enhance Efficiency**: Maintain or improve model performance using techniques like quantization, pruning, and distillation.
- **Accelerate Deployment**: Provide practical tools, templates, and guidance to streamline the deployment of optimized models.

Whether you're a researcher exploring new optimization techniques or a practitioner deploying LLMs, this repository is here to help!

---

## Features

- 📚 **Curated Research Papers**: Organized collections of influential papers on efficient AI techniques.
- 🛠️ **Tools and Frameworks**: Comprehensive resources for implementing and deploying efficient models.
- 💡 **Best Practices**: Tutorials and guides for real-world applications.
- 🌐 **Community Support**: Links to forums, discussions, and collaborative projects.

---

## Categories

### Optimization Techniques

#### Papers

- **Pruning**: Methods for removing unnecessary weights to make models smaller and faster.  
  - [FastV: An Image is Worth 1/2 Tokens After Layer 2: Plug-and-Play Inference Acceleration for Large Vision-Language Models](https://arxiv.org/pdf/2403.06764)  [Code](https://github.com/pkunlp-icler/FastV)
  - [SparseVLM: Visual Token Sparsification for Efficient Vision-Language Model Inference](https://arxiv.org/abs/2410.04417) [Code](https://github.com/Gumpest/SparseVLMs)
  - [VisionZip: Longer is Better but Not Necessary in Vision Language Models](https://arxiv.org/abs/2412.04467) [Code](https://github.com/dvlabresearch/VisionZip)
  - [FiCoCo: Rethinking Token Reduction in MLLMs: Towards a Unified Paradigm for Training-Free Acceleration](https://arxiv.org/pdf/2411.17686) [Code](https://ficoco-accelerate.github.io/)
  - [AIM: Adaptive Inference of Multi-Modal LLMs via Token Merging and Pruning](https://arxiv.org/pdf/2412.03248) [Code](https://github.com/LaVi-Lab/AIM)


- **New Architectures**: Novel model architectures designed for efficiency.  
  - [Cobra: Extending Mamba to Multi-Modal Large Language Model for Efficient Inference](https://arxiv.org/abs/2403.14520) Code: [GitHub](https://github.com/h-zhao1997/cobra)

#### Tools

- [Hugging Face Optimum](https://huggingface.co/docs/optimum/index)
- [Intel Neural Compressor](https://github.com/intel/neural-compressor)

---

### Model Compression

#### Papers

- [Knowledge Distillation Techniques](https://arxiv.org/abs/example7)
- [Model Compression with Minimal Performance Loss](https://arxiv.org/abs/example8)

#### Tools

- [ONNX Runtime](https://onnxruntime.ai/)
- [TensorRT](https://developer.nvidia.com/tensorrt)

---

### Deployment and Acceleration

#### Papers

- [Efficient Inference for Large Transformers](https://arxiv.org/abs/example9)
- [Accelerating Model Inference on Edge Devices](https://arxiv.org/abs/example10)

#### Tools

- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html)
- [Deepspeed](https://www.deepspeed.ai/)

---

### Multimodal Integration

#### Papers

- [Aligning Vision and Language Models](https://arxiv.org/abs/example11)
- [Multimodal Fusion Techniques](https://arxiv.org/abs/example12)

#### Tools

- [CLIP Model](https://github.com/openai/CLIP)
- [VLMo Framework](https://github.com/microsoft/VLMo)

---

## Community

Join our community to share your projects, tools, or insights:

- [Discussion Forum](https://example-forum.com)
- [Slack Group](https://example-slack.com)
- [Twitter](https://twitter.com/efficientai_mllm)

---

## How to Contribute

We welcome contributions of any kind!

### Submitting Content

1. Fork this repository.
2. Create a branch and add your content.
3. Submit a pull request (PR) with a description of your changes.

### Adding Papers

- Ensure the paper is relevant to the repository's scope.
- Provide a clear and concise summary if possible.
- Include links to the paper and code (if available).

### Types of Contributions

- Add new papers, tools, or resources.
- Improve descriptions or fix formatting issues.
- Share use cases or practical tutorials.

Check our [Contributing Guide](CONTRIBUTING.md) for more details.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for supporting **Awesome EfficientAI for MLLM**! Let’s build an efficient AI ecosystem 🚀

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=924973292/Awesome-EfficientAI-for-MLLM&type=Date)](https://star-history.com/#924973292/Awesome-EfficientAI-for-MLLM&Date)

## Acknowledgments

I want to express my gratitude to the academic community and everyone contributing to the advancement of multi-modal object re-identification research.

## Contact

Feel free to reach out if you have any questions, suggestions, or collaboration proposals:

- Email: [924973292@mail.dlut.edu.cn](mailto:924973292@mail.dlut.edu.cn)
- Web: [924973292.github.io](https://924973292.github.io//)