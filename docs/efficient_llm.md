# Efficient LLM

- [Efficient LLM](#efficient-llm) 
  - [Survey](#survey)
  - [Efficient LLM](#efficient-llm-1)
  - [Finetune](#finetune)
  - [Quantization](#quantization)
  - [Distillation](#distillation)
  - [Pruning](#pruning)
  - [Inference](#inference)
  - [Small Language Models](#small-language-models)
  - [Transformer](#transformer)
  - [Hardware](#hardware)
  - [Tutorials](#tutorials)
  - [Projects](#projects)
  - [Products](#products)
  - [Misc](#misc)


## Survey

- **A Survey of Small Language Models**, `arXiv, 2410.20011`, [arxiv](http://arxiv.org/abs/2410.20011v1), [pdf](http://arxiv.org/pdf/2410.20011v1.pdf), cication: [**-1**](None) 

	 *Chien Van Nguyen, Xuan Shen, Ryan Aponte, ..., Ryan A. Rossi, Thien Huu Nguyen*

## Efficient LLM


## Finetune


## Quantization

- **QTIP: Quantization with Trellises and Incoherence Processing**, `arXiv, 2406.11235`, [arxiv](http://arxiv.org/abs/2406.11235v3), [pdf](http://arxiv.org/pdf/2406.11235v3.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=11756629272535530144&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Albert Tseng, Qingyao Sun, David Hou, ..., Christopher De Sa* · ([qtip](https://github.com/Cornell-RelaxML/qtip) - Cornell-RelaxML) ![Star](https://img.shields.io/github/stars/Cornell-RelaxML/qtip.svg?style=social&label=Star) · ([x](https://x.com/togethercompute/status/1851698873347235986)) · ([t](https://t.co/GSxwHHJ7EW))

## Distillation

- **Speculative Knowledge Distillation: Bridging the Teacher-Student Gap 
  Through Interleaved Sampling**, `arXiv, 2410.11325`, [arxiv](http://arxiv.org/abs/2410.11325v1), [pdf](http://arxiv.org/pdf/2410.11325v1.pdf), cication: [**-1**](None)

	 *Wenda Xu, Rujun Han, Zifeng Wang, ..., Chen-Yu Lee, Tomas Pfister*

## Pruning

- **What Matters in Transformers? Not All Attention is Needed**, `arXiv, 2406.15786`, [arxiv](http://arxiv.org/abs/2406.15786v6), [pdf](http://arxiv.org/pdf/2406.15786v6.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=18204847320375312044&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Shwai He, Guoheng Sun, Zheyu Shen, ..., Ang Li*

## Inference

- **A Simple and Effective $L_2$ Norm-Based Strategy for KV Cache 
  Compression**, `arXiv, 2406.11430`, [arxiv](http://arxiv.org/abs/2406.11430v3), [pdf](http://arxiv.org/pdf/2406.11430v3.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=5168052951707843815&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Alessio Devoto, Yu Zhao, Simone Scardapane, ..., Pasquale Minervini*
- **SageAttention: Accurate 8-Bit Attention for Plug-and-play Inference 
  Acceleration**, `arXiv, 2410.02367`, [arxiv](http://arxiv.org/abs/2410.02367v1), [pdf](http://arxiv.org/pdf/2410.02367v1.pdf), cication: [**-1**](None)

	 *Jintao Zhang, Jia wei, Pengle Zhang, ..., Jun Zhu, Jianfei Chen*
- **Fast Best-of-N Decoding via Speculative Rejection**, `arXiv, 2410.20290`, [arxiv](http://arxiv.org/abs/2410.20290v2), [pdf](http://arxiv.org/pdf/2410.20290v2.pdf), cication: [**-1**](None) 

	 *Hanshi Sun, Momin Haider, Ruiqi Zhang, ..., Peter Bartlett, Andrea Zanette*
- [Optimizing and Characterizing High-Throughput Low-Latency LLM Inference in MLCEngine](https://blog.mlc.ai/2024/10/10/optimizing-and-characterizing-high-throughput-low-latency-llm-inference) 

	 · ([reddit](https://www.reddit.com/r/LocalLLaMA/comments/1ge1ojk/updated_with_corrected_settings_for_llamacpp/))
- [Battle of Inference Engines: Llama.cpp vs MLC LLM vs vLLM](https://buttondown.com/ainews/archive/ainews-not-much-happened-this-weekend-2670/) 

	 · ([reddit](https://www.reddit.com/gallery/1gdccyr))
- [Universal Assisted Generation: Faster Decoding with Any Assistant Model](https://huggingface.co/blog/universal_assisted_generation)  🤗
- [Models continually pretrained using LayerSkip](https://huggingface.co/collections/facebook/layerskip-666b25c50c8ae90e1965727a)  🤗

	 · ([arxiv](https://arxiv.org/abs/2404.16710))

## Small Language Models

- [MobileLLM is an auto-regressive language model leveraging an optimized transformer architecture](https://huggingface.co/facebook/MobileLLM-125M)  🤗

	 · ([arxiv](https://arxiv.org/abs/2402.14905))

## Transformer

- **ThunderKittens: Simple, Fast, and Adorable AI Kernels**, `arXiv, 2410.20399`, [arxiv](http://arxiv.org/abs/2410.20399v1), [pdf](http://arxiv.org/pdf/2410.20399v1.pdf), cication: [**-1**](None) 

	 *Benjamin F. Spector, Simran Arora, Aaryan Singhal, ..., Daniel Y. Fu, Christopher Ré*
- :clapper: [Differential Transformer 论文原理逐段讲解](https://www.bilibili.com/video/BV1Jq1PYPEYG/) 
- **SeerAttention: Learning Intrinsic Sparse Attention in Your LLMs**, `arXiv, 2410.13276`, [arxiv](http://arxiv.org/abs/2410.13276v2), [pdf](http://arxiv.org/pdf/2410.13276v2.pdf), cication: [**-1**](None) 

	 *Yizhao Gao, Zhichen Zeng, Dayou Du, ..., Fan Yang, Mao Yang*
- **MoH: Multi-Head Attention as Mixture-of-Head Attention**, `arXiv, 2410.11842`, [arxiv](http://arxiv.org/abs/2410.11842v1), [pdf](http://arxiv.org/pdf/2410.11842v1.pdf), cication: [**-1**](None) 

	 *Peng Jin, Bo Zhu, Li Yuan, ..., Shuicheng Yan* · ([arxiv](https://arxiv.org/pdf/2410.11842)) · ([MoH](https://github.com/SkyworkAI/MoH) - SkyworkAI) ![Star](https://img.shields.io/github/stars/SkyworkAI/MoH.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/collections/Chat-UniVi/moh-66f4277375c1c1b2ad61a2c1))

## Hardware

- [database of Machine Learning Hardware](https://x.com/EpochAIResearch/status/1849135255833158124) 

## Tutorials

- :clapper: [Lecture 32: Unsloth](https://www.youtube.com/watch?v=hfb_AIhDYnA) 

## Projects


## Products


## Misc

- :clapper: [How FlashAttention Accelerates the Generative AI Revolution](https://www.youtube.com/watch?v=gBMO1JZav44) 
- [k-mktr / gpu-poor-llm-arena](https://huggingface.co/spaces/k-mktr/gpu-poor-llm-arena/tree/main)  🤗