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

- **A Silver Bullet or a Compromise for Full Attention? A Comprehensive 
  Study of Gist Token-based Context Compression**, `arXiv, 2412.17483`, [arxiv](http://arxiv.org/abs/2412.17483v1), [pdf](http://arxiv.org/pdf/2412.17483v1.pdf), cication: [**-1**](None) 

	 *Chenlong Deng, Zhisong Zhang, Kelong Mao, ..., Dong Yu, Zhicheng Dou*
- **A Survey on Large Language Model Acceleration based on KV Cache 
  Management**, `arXiv, 2412.19442`, [arxiv](http://arxiv.org/abs/2412.19442v1), [pdf](http://arxiv.org/pdf/2412.19442v1.pdf), cication: [**-1**](None) 

	 *Haoyang Li, Yiming Li, Anxin Tian, ..., Qing Li, Lei Chen* · ([Awesome-KV-Cache-Management](https://github.com/TreeAI-Lab/Awesome-KV-Cache-Management) - TreeAI-Lab) ![Star](https://img.shields.io/github/stars/TreeAI-Lab/Awesome-KV-Cache-Management.svg?style=social&label=Star)
- **A Comprehensive Survey of Small Language Models in the Era of Large 
  Language Models: Techniques, Enhancements, Applications, Collaboration with
  LLMs, and Trustworthiness**, `arXiv, 2411.03350`, [arxiv](http://arxiv.org/abs/2411.03350v1), [pdf](http://arxiv.org/pdf/2411.03350v1.pdf), cication: [**-1**](None) 

	 *Fali Wang, Zhiwei Zhang, Xianren Zhang, ..., Ming Huang, Suhang Wang* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650944101&idx=5&sn=3a152e75e79b5564a7e9431c343cfbfd&chksm=85dcf1f7161fc8c550369473d6d519fe84f962e2772d920667f1fa32b27263069f8ab1047a18&scene=0&xtrack=1))
- **A Comprehensive Survey of Small Language Models in the Era of Large 
  Language Models: Techniques, Enhancements, Applications, Collaboration with
  LLMs, and Trustworthiness**, `arXiv, 2411.03350`, [arxiv](http://arxiv.org/abs/2411.03350v1), [pdf](http://arxiv.org/pdf/2411.03350v1.pdf), cication: [**-1**](None) 

	 *Fali Wang, Zhiwei Zhang, Xianren Zhang, ..., Ming Huang, Suhang Wang*
- **A Survey of Small Language Models**, `arXiv, 2410.20011`, [arxiv](http://arxiv.org/abs/2410.20011v1), [pdf](http://arxiv.org/pdf/2410.20011v1.pdf), cication: [**-1**](None) 

	 *Chien Van Nguyen, Xuan Shen, Ryan Aponte, ..., Ryan A. Rossi, Thien Huu Nguyen*

## Efficient LLM

- **Sigma: Differential Rescaling of Query, Key and Value for Efficient
  Language Models**, `arXiv, 2501.13629`, [arxiv](http://arxiv.org/abs/2501.13629v1), [pdf](http://arxiv.org/pdf/2501.13629v1.pdf), cication: [**-1**](None) 

	 *Zhenghao Lin, Zihao Tang, Xiao Liu, ..., Peng Cheng, Mao Yang*
- 🌟 **Tensor Product Attention Is All You Need**, `arXiv, 2501.06425`, [arxiv](http://arxiv.org/abs/2501.06425v1), [pdf](http://arxiv.org/pdf/2501.06425v1.pdf), cication: [**-1**](None) 

	 *Yifan Zhang, Yifeng Liu, Huizhuo Yuan, ..., Quanquan Gu, Andrew Chi-Chih Yao* · ([tensorgi.github](https://tensorgi.github.io/T6/)) · ([T6](https://github.com/tensorgi/T6) - tensorgi) ![Star](https://img.shields.io/github/stars/tensorgi/T6.svg?style=social&label=Star)
- 🌟 **Better & Faster Large Language Models via Multi-token Prediction**, `arXiv, 2404.19737`, [arxiv](http://arxiv.org/abs/2404.19737v1), [pdf](http://arxiv.org/pdf/2404.19737v1.pdf), cication: [**-1**](None) 

	 *Fabian Gloeckle, Badr Youbi Idrissi, Baptiste Rozière, ..., David Lopez-Paz, Gabriel Synnaeve*
- **SepLLM: Accelerate Large Language Models by Compressing One Segment into 
  One Separator**, `arXiv, 2412.12094`, [arxiv](http://arxiv.org/abs/2412.12094v2), [pdf](http://arxiv.org/pdf/2412.12094v2.pdf), cication: [**-1**](None) 

	 *Guoxuan Chen, Han Shi, Jiawei Li, ..., Weiyang Liu, Chao Huang*
- **Yi-Lightning Technical Report**, `arXiv, 2412.01253`, [arxiv](http://arxiv.org/abs/2412.01253v3), [pdf](http://arxiv.org/pdf/2412.01253v3.pdf), cication: [**-1**](None) 

	 *01. AI, :, Alan Wake, ..., Zhiyuan Liu, Zirui Zhang*

## Finetune

- **Knowledge Composition using Task Vectors with Learned Anisotropic 
  Scaling**, `arXiv, 2407.02880`, [arxiv](http://arxiv.org/abs/2407.02880v2), [pdf](http://arxiv.org/pdf/2407.02880v2.pdf), cication: [**-1**](None) 

	 *Frederic Z. Zhang, Paul Albert, Cristian Rodriguez-Opazo, ..., Anton van den Hengel, Ehsan Abbasnejad* · ([atlas](https://github.com/fredzzhang/atlas?tab=readme-ov-file) - fredzzhang) ![Star](https://img.shields.io/github/stars/fredzzhang/atlas.svg?style=social&label=Star)
- **Parameter-Efficient Fine-Tuning of Large Language Models for Unit Test 
  Generation: An Empirical Study**, `arXiv, 2411.02462`, [arxiv](http://arxiv.org/abs/2411.02462v1), [pdf](http://arxiv.org/pdf/2411.02462v1.pdf), cication: [**-1**](None) 

	 *André Storhaug, Jingyue Li* · ([peft-unit-test-generation-replication-package](https://github.com/andstor/peft-unit-test-generation-replication-package) - andstor) ![Star](https://img.shields.io/github/stars/andstor/peft-unit-test-generation-replication-package.svg?style=social&label=Star)
- **LoRA vs Full Fine-tuning: An Illusion of Equivalence**, `arXiv, 2410.21228`, [arxiv](http://arxiv.org/abs/2410.21228v1), [pdf](http://arxiv.org/pdf/2410.21228v1.pdf), cication: [**-1**](None) 

	 *Reece Shuttleworth, Jacob Andreas, Antonio Torralba, ..., Pratyusha Sharma* · ([𝕏](https://x.com/danielhanchen/status/1854992153992479165))

## Quantization

- [Unsloth - Dynamic 4-bit Quantization](https://unsloth.ai/blog/dynamic-4bit) 

	 · ([𝕏](https://x.com/UnslothAI/status/1864384960666456535))
- [**auto-round**](https://github.com/intel/auto-round) - intel ![Star](https://img.shields.io/github/stars/intel/auto-round.svg?style=social&label=Star) 

	 · ([reddit](https://www.reddit.com/r/LocalLLaMA/comments/1h0aev6/lossless_4bit_quantization_for_large_models_are/))
- **Low-Bit Quantization Favors Undertrained LLMs: Scaling Laws for 
  Quantized LLMs with 100T Training Tokens**, `arXiv, 2411.17691`, [arxiv](http://arxiv.org/abs/2411.17691v2), [pdf](http://arxiv.org/pdf/2411.17691v2.pdf), cication: [**-1**](None) 

	 *Xu Ouyang, Tao Ge, Thomas Hartvigsen, ..., Haitao Mi, Dong Yu* · ([huggingface](https://huggingface.co/Xu-Ouyang))
- **PrefixQuant: Static Quantization Beats Dynamic through Prefixed Outliers 
  in LLMs**, `arXiv, 2410.05265`, [arxiv](http://arxiv.org/abs/2410.05265v1), [pdf](http://arxiv.org/pdf/2410.05265v1.pdf), cication: [**-1**](None) 

	 *Mengzhao Chen, Yi Liu, Jiahao Wang, ..., Wenqi Shao, Ping Luo* · ([PrefixQuant](https://github.com/ChenMnZ/PrefixQuant) - ChenMnZ) ![Star](https://img.shields.io/github/stars/ChenMnZ/PrefixQuant.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/abs/2410.05265v1))
- 🌟 **Scaling Laws for Precision**, `arXiv, 2411.04330`, [arxiv](http://arxiv.org/abs/2411.04330v1), [pdf](http://arxiv.org/pdf/2411.04330v1.pdf), cication: [**-1**](None) 

	 *Tanishq Kumar, Zachary Ankner, Benjamin F. Spector, ..., Christopher Ré, Aditi Raghunathan* · ([𝕏](https://x.com/Tim_Dettmers/status/1856338252120068523)) · ([𝕏](https://x.com/Tanishq97836660/status/1856045610756886750))
- 🌟 **BitNet a4.8: 4-bit Activations for 1-bit LLMs**, `arXiv, 2411.04965`, [arxiv](http://arxiv.org/abs/2411.04965v1), [pdf](http://arxiv.org/pdf/2411.04965v1.pdf), cication: [**-1**](None) 

	 *Hongyu Wang, Shuming Ma, Furu Wei*
- **"Give Me BF16 or Give Me Death"? Accuracy-Performance Trade-Offs in LLM 
  Quantization**, `arXiv, 2411.02355`, [arxiv](http://arxiv.org/abs/2411.02355v1), [pdf](http://arxiv.org/pdf/2411.02355v1.pdf), cication: [**-1**](None) 

	 *Eldar Kurtic, Alexandre Marques, Shubhra Pandit, ..., Mark Kurtz, Dan Alistarh*
- **QTIP: Quantization with Trellises and Incoherence Processing**, `arXiv, 2406.11235`, [arxiv](http://arxiv.org/abs/2406.11235v3), [pdf](http://arxiv.org/pdf/2406.11235v3.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=11756629272535530144&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Albert Tseng, Qingyao Sun, David Hou, ..., Christopher De Sa* · ([qtip](https://github.com/Cornell-RelaxML/qtip) - Cornell-RelaxML) ![Star](https://img.shields.io/github/stars/Cornell-RelaxML/qtip.svg?style=social&label=Star) · ([x](https://x.com/togethercompute/status/1851698873347235986)) · ([t](https://t.co/GSxwHHJ7EW))

## Distillation

- **Distillation Quantification for Large Language Models**, `arXiv, 2501.12619`, [arxiv](http://arxiv.org/abs/2501.12619v2), [pdf](http://arxiv.org/pdf/2501.12619v2.pdf), cication: [**-1**](None) 

	 *Sunbowen Lee, Junting Zhou, Chang Ao, ..., Zhoufutu Wen, Shiwen Ni* · ([LLMs-Distillation-Quantification](https://github.com/Aegis1863/LLMs-Distillation-Quantification) - Aegis1863) ![Star](https://img.shields.io/github/stars/Aegis1863/LLMs-Distillation-Quantification.svg?style=social&label=Star)
- **Active Data Curation Effectively Distills Large-Scale Multimodal Models**, `arXiv, 2411.18674`, [arxiv](http://arxiv.org/abs/2411.18674v1), [pdf](http://arxiv.org/pdf/2411.18674v1.pdf), cication: [**-1**](None) 

	 *Vishaal Udandarao, Nikhil Parthasarathy, Muhammad Ferjad Naeem, ..., Alessio Tonioni, Olivier J. Hénaff* · ([𝕏](https://x.com/nikparth1/status/1863633339950813691))
- **Stronger Models are NOT Stronger Teachers for Instruction Tuning**, `arXiv, 2411.07133`, [arxiv](http://arxiv.org/abs/2411.07133v2), [pdf](http://arxiv.org/pdf/2411.07133v2.pdf), cication: [**-1**](None) 

	 *Zhangchen Xu, Fengqing Jiang, Luyao Niu, ..., Bill Yuchen Lin, Radha Poovendran*
- **Speculative Knowledge Distillation: Bridging the Teacher-Student Gap 
  Through Interleaved Sampling**, `arXiv, 2410.11325`, [arxiv](http://arxiv.org/abs/2410.11325v1), [pdf](http://arxiv.org/pdf/2410.11325v1.pdf), cication: [**-1**](None)

	 *Wenda Xu, Rujun Han, Zifeng Wang, ..., Chen-Yu Lee, Tomas Pfister*

## Pruning

- **The Super Weight in Large Language Models**, `arXiv, 2411.07191`, [arxiv](http://arxiv.org/abs/2411.07191v1), [pdf](http://arxiv.org/pdf/2411.07191v1.pdf), cication: [**-1**](None) 

	 *Mengxia Yu, De Wang, Qi Shan, ..., Colorado Reed, Alvin Wan*
- **Sparsing Law: Towards Large Language Models with Greater Activation 
  Sparsity**, `arXiv, 2411.02335`, [arxiv](http://arxiv.org/abs/2411.02335v1), [pdf](http://arxiv.org/pdf/2411.02335v1.pdf), cication: [**-1**](None) 

	 *Yuqi Luo, Chenyang Song, Xu Han, ..., Zhiyuan Liu, Maosong Sun*
- **What Matters in Transformers? Not All Attention is Needed**, `arXiv, 2406.15786`, [arxiv](http://arxiv.org/abs/2406.15786v6), [pdf](http://arxiv.org/pdf/2406.15786v6.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=18204847320375312044&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Shwai He, Guoheng Sun, Zheyu Shen, ..., Ang Li*

## Inference

- [Efficient Large Language Model Deployment with Quantization](https://llm-class.github.io/speakers.html) 
- [Sparsity for Efficient LLM Inference](https://llm-class.github.io/speakers.html) 
- **Efficiently Serving LLM Reasoning Programs with Certaindex**, `arXiv, 2412.20993`, [arxiv](http://arxiv.org/abs/2412.20993v1), [pdf](http://arxiv.org/pdf/2412.20993v1.pdf), cication: [**-1**](None) 

	 *Yichao Fu, Junda Chen, Siqi Zhu, ..., Aurick Qiao, Hao Zhang*
- 🌟 [**sglang**](https://github.com/sgl-project/sglang) - sgl-project ![Star](https://img.shields.io/github/stars/sgl-project/sglang.svg?style=social&label=Star) 
- [FlashInfer 0.2 - Efficient and Customizable Kernels for LLM Inference Serving](https://flashinfer.ai/2024/12/16/flashinfer-v02-release.html) 

	 · ([𝕏](https://x.com/ye_combinator/status/1869823582261653787))
- [TGI v3 overview](https://huggingface.co/docs/text-generation-inference/conceptual/chunking)  🤗 

	 · ([𝕏](https://x.com/narsilou/status/1866423560799158775))
- [Efficient LLM Inference with SGLang, Lianmin Zheng, xAI](https://www.youtube.com/watch?v=Ny4xxErgFgQ)  :clapper: 
- [**ZhiLight**](https://github.com/zhihu/ZhiLight) - zhihu ![Star](https://img.shields.io/github/stars/zhihu/ZhiLight.svg?style=social&label=Star) 
- [Introducing SGLang Router: a cache-aware router for LLM Inference in SGLang v0.4](https://x.com/hsu_byron/status/1864449841239347341)  𝕏 
- **Puzzle: Distillation-Based NAS for Inference-Optimized LLMs**, `arXiv, 2411.19146`, [arxiv](http://arxiv.org/abs/2411.19146v1), [pdf](http://arxiv.org/pdf/2411.19146v1.pdf), cication: [**-1**](None) 

	 *Akhiad Bercovich, Tomer Ronen, Talor Abramovich, ..., Ran Zilberstein, Ran El-Yaniv*
- **Star Attention: Efficient LLM Inference over Long Sequences**, `arXiv, 2411.17116`, [arxiv](http://arxiv.org/abs/2411.17116v1), [pdf](http://arxiv.org/pdf/2411.17116v1.pdf), cication: [**-1**](None) 

	 *Shantanu Acharya, Fei Jia, Boris Ginsburg* · ([Star-Attention](https://github.com/NVIDIA/Star-Attention?tab=readme-ov-file) - NVIDIA) ![Star](https://img.shields.io/github/stars/NVIDIA/Star-Attention.svg?style=social&label=Star)
- [**Mooncake**](https://github.com/kvcache-ai/Mooncake) - kvcache-ai ![Star](https://img.shields.io/github/stars/kvcache-ai/Mooncake.svg?style=social&label=Star) 

	 *A KVCache-centric Disaggregated Architecture for LLM Serving*
- **Draft Model Knows When to Stop: A Self-Verification Length Policy for 
  Speculative Decoding**, `arXiv, 2411.18462`, [arxiv](http://arxiv.org/abs/2411.18462v1), [pdf](http://arxiv.org/pdf/2411.18462v1.pdf), cication: [**-1**](None) 

	 *Ziyin Zhang, Jiahao Xu, Tian Liang, ..., Rui Wang, Zhaopeng Tu*
- **SAM Decoding: Speculative Decoding via Suffix Automaton**, `arXiv, 2411.10666`, [arxiv](http://arxiv.org/abs/2411.10666v1), [pdf](http://arxiv.org/pdf/2411.10666v1.pdf), cication: [**-1**](None) 

	 *Yuxuan Hu, Ke Wang, Jing Zhang, ..., Cuiping Li, Hong Chen* · ([SAM-Decoding](https://github.com/hyx1999/SAM-Decoding?tab=readme-ov-file) - hyx1999) ![Star](https://img.shields.io/github/stars/hyx1999/SAM-Decoding.svg?style=social&label=Star)
- **FastDraft: How to Train Your Draft**, `arXiv, 2411.11055`, [arxiv](http://arxiv.org/abs/2411.11055v1), [pdf](http://arxiv.org/pdf/2411.11055v1.pdf), cication: [**-1**](None) 

	 *Ofir Zafrir, Igor Margulis, Dorin Shteyman, ..., Guy Boudoukh*
- **SageAttention2 Technical Report: Accurate 4 Bit Attention for 
  Plug-and-play Inference Acceleration**, `arXiv, 2411.10958`, [arxiv](http://arxiv.org/abs/2411.10958v1), [pdf](http://arxiv.org/pdf/2411.10958v1.pdf), cication: [**-1**](None) 

	 *Jintao Zhang, Haofeng Huang, Pengle Zhang, ..., Jun Zhu, Jianfei Chen* · ([SageAttention](https://github.com/thu-ml/SageAttention) - thu-ml) ![Star](https://img.shields.io/github/stars/thu-ml/SageAttention.svg?style=social&label=Star)
- [Faster Text Generation with Self-Speculative Decoding](https://huggingface.co/blog/layerskip)  🤗 
- [**distributed-llama**](https://github.com/b4rtaz/distributed-llama) - b4rtaz ![Star](https://img.shields.io/github/stars/b4rtaz/distributed-llama.svg?style=social&label=Star) 
- [SGLang: Fast Serving Framework for Large Language and Vision-Language Models on AMD GPUs](https://rocm.blogs.amd.com/artificial-intelligence/sglang/README.html) 
- [OpenAI beats Anthropic and Fireworks to releasing Speculative Decoding](https://buttondown.com/ainews/archive/ainews-openai-beats-anthropic-and-fireworks-to/) 
- [Latency optimizationImprove latency across a wide variety of LLM-related use cases.](https://platform.openai.com/docs/guides/latency-optimization) 
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

- **SlimLM: An Efficient Small Language Model for On-Device Document 
  Assistance**, `arXiv, 2411.09944`, [arxiv](http://arxiv.org/abs/2411.09944v1), [pdf](http://arxiv.org/pdf/2411.09944v1.pdf), cication: [**-1**](None) 

	 *Thang M. Pham, Phat T. Nguyen, Seunghyun Yoon, ..., Franck Dernoncourt, Trung Bui*
- **Hymba: A Hybrid-head Architecture for Small Language Models**, `arXiv, 2411.13676`, [arxiv](http://arxiv.org/abs/2411.13676v1), [pdf](http://arxiv.org/pdf/2411.13676v1.pdf), cication: [**-1**](None) 

	 *Xin Dong, Yonggan Fu, Shizhe Diao, ..., Jan Kautz, Pavlo Molchanov*
- [MobileLLM is an auto-regressive language model leveraging an optimized transformer architecture](https://huggingface.co/facebook/MobileLLM-125M)  🤗 

	 · ([arxiv](https://arxiv.org/abs/2402.14905))

## Transformer

- 🌟 **SageAttention2 Technical Report: Accurate 4 Bit Attention for 
  Plug-and-play Inference Acceleration**, `arXiv, 2411.10958`, [arxiv](http://arxiv.org/abs/2411.10958v1), [pdf](http://arxiv.org/pdf/2411.10958v1.pdf), cication: [**-1**](None) 

	 *Jintao Zhang, Haofeng Huang, Pengle Zhang, ..., Jun Zhu, Jianfei Chen* · ([SageAttention.](https://github.com/thu-ml/SageAttention.) - thu-ml) ![Star](https://img.shields.io/github/stars/thu-ml/SageAttention..svg?style=social&label=Star)
- **ThunderKittens: Simple, Fast, and Adorable AI Kernels**, `arXiv, 2410.20399`, [arxiv](http://arxiv.org/abs/2410.20399v1), [pdf](http://arxiv.org/pdf/2410.20399v1.pdf), cication: [**-1**](None) 

	 *Benjamin F. Spector, Simran Arora, Aaryan Singhal, ..., Daniel Y. Fu, Christopher Ré*
- :clapper: [Differential Transformer 论文原理逐段讲解](https://www.bilibili.com/video/BV1Jq1PYPEYG/) 
- **SeerAttention: Learning Intrinsic Sparse Attention in Your LLMs**, `arXiv, 2410.13276`, [arxiv](http://arxiv.org/abs/2410.13276v2), [pdf](http://arxiv.org/pdf/2410.13276v2.pdf), cication: [**-1**](None) 

	 *Yizhao Gao, Zhichen Zeng, Dayou Du, ..., Fan Yang, Mao Yang*
- **MoH: Multi-Head Attention as Mixture-of-Head Attention**, `arXiv, 2410.11842`, [arxiv](http://arxiv.org/abs/2410.11842v1), [pdf](http://arxiv.org/pdf/2410.11842v1.pdf), cication: [**-1**](None) 

	 *Peng Jin, Bo Zhu, Li Yuan, ..., Shuicheng Yan* · ([arxiv](https://arxiv.org/pdf/2410.11842)) · ([MoH](https://github.com/SkyworkAI/MoH) - SkyworkAI) ![Star](https://img.shields.io/github/stars/SkyworkAI/MoH.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/collections/Chat-UniVi/moh-66f4277375c1c1b2ad61a2c1))

## Hardware

- [database of Machine Learning Hardware](https://x.com/EpochAIResearch/status/1849135255833158124)  𝕏 

## Tutorials

- [Dynamic  Sparsity  in  Machine  Learning](https://dynamic-sparsity.github.io/) 
- :clapper: [Lecture 32: Unsloth](https://www.youtube.com/watch?v=hfb_AIhDYnA) 

## Projects

- [**nano-sparse-attention**](https://github.com/PiotrNawrot/nano-sparse-attention) - PiotrNawrot ![Star](https://img.shields.io/github/stars/PiotrNawrot/nano-sparse-attention.svg?style=social&label=Star) 

	 · ([𝕏](https://x.com/p_nawrot/status/1858903361858265460))
- [**sgl-learning-materials**](https://github.com/sgl-project/sgl-learning-materials) - sgl-project ![Star](https://img.shields.io/github/stars/sgl-project/sgl-learning-materials.svg?style=social&label=Star) 
- [**exo**](https://github.com/exo-explore/exo) - exo-explore ![Star](https://img.shields.io/github/stars/exo-explore/exo.svg?style=social&label=Star) 

	 *Run your own AI cluster at home with everyday devices.*

## Products


## Misc

- [Ways to use torch.compile](http://blog.ezyang.com/2024/11/ways-to-use-torch-compile/) 

	 · ([𝕏](https://x.com/ezyang/status/1866131758862721453))
- [JPEG compress your LLM weights](http://pepijndevos.nl/2024/12/01/jpeg-compress-your-llm-weights.html) 
- :clapper: [How FlashAttention Accelerates the Generative AI Revolution](https://www.youtube.com/watch?v=gBMO1JZav44) 
- [k-mktr / gpu-poor-llm-arena](https://huggingface.co/spaces/k-mktr/gpu-poor-llm-arena/tree/main)  🤗 