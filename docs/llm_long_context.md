# LLM Long Context

- [LLM Long Context](#llm-long-context) 
  - [Survey](#survey)
  - [Long Context](#long-context)
  - [Evaluation](#evaluation)
  - [Projects](#projects)
  - [Misc](#misc)


## Survey


## Long Context

- **Long Context vs. RAG for LLMs: An Evaluation and Revisits**, `arXiv, 2501.01880`, [arxiv](http://arxiv.org/abs/2501.01880v1), [pdf](http://arxiv.org/pdf/2501.01880v1.pdf), cication: [**-1**](None) 

	 *Xinze Li, Yixin Cao, Yubo Ma, ..., Aixin Sun*
- **SCOPE: Optimizing Key-Value Cache Compression in Long-context Generation**, `arXiv, 2412.13649`, [arxiv](http://arxiv.org/abs/2412.13649v1), [pdf](http://arxiv.org/pdf/2412.13649v1.pdf), cication: [**-1**](None) 

	 *Jialong Wu, Zhenglin Wang, Linhai Zhang, ..., Yulan He, Deyu Zhou* · ([SCOPE.](https://github.com/Linking-ai/SCOPE.) - Linking-ai) ![Star](https://img.shields.io/github/stars/Linking-ai/SCOPE..svg?style=social&label=Star)
- **Revisiting In-Context Learning with Long Context Language Models**, `arXiv, 2412.16926`, [arxiv](http://arxiv.org/abs/2412.16926v1), [pdf](http://arxiv.org/pdf/2412.16926v1.pdf), cication: [**-1**](None) 

	 *Jinheon Baek, Sun Jae Lee, Prakhar Gupta, ..., Siddharth Dalmia, Prateek Kolhar*
- **Fourier Position Embedding: Enhancing Attention's Periodic Extension for 
  Length Generalization**, `arXiv, 2412.17739`, [arxiv](http://arxiv.org/abs/2412.17739v1), [pdf](http://arxiv.org/pdf/2412.17739v1.pdf), cication: [**-1**](None) 

	 *Ermo Hua, Che Jiang, Xingtai Lv, ..., Xue Kai Zhu, Bowen Zhou*
- **SCBench: A KV Cache-Centric Analysis of Long-Context Methods**, `arXiv, 2412.10319`, [arxiv](http://arxiv.org/abs/2412.10319v1), [pdf](http://arxiv.org/pdf/2412.10319v1.pdf), cication: [**-1**](None) 

	 *Yucheng Li, Huiqiang Jiang, Qianhui Wu, ..., Yuqing Yang, Lili Qiu* · ([aka](https://aka.ms/SCBench))
- **Star Attention: Efficient LLM Inference over Long Sequences**, `arXiv, 2411.17116`, [arxiv](http://arxiv.org/abs/2411.17116v1), [pdf](http://arxiv.org/pdf/2411.17116v1.pdf), cication: [**-1**](None) 

	 *Shantanu Acharya, Fei Jia, Boris Ginsburg* · ([Star-Attention](https://github.com/NVIDIA/Star-Attention?tab=readme-ov-file) - NVIDIA) ![Star](https://img.shields.io/github/stars/NVIDIA/Star-Attention.svg?style=social&label=Star)
- **When Precision Meets Position: BFloat16 Breaks Down RoPE in Long-Context 
  Training**, `arXiv, 2411.13476`, [arxiv](http://arxiv.org/abs/2411.13476v1), [pdf](http://arxiv.org/pdf/2411.13476v1.pdf), cication: [**-1**](None) 

	 *Haonan Wang, Qian Liu, Chao Du, ..., Kenji Kawaguchi, Tianyu Pang* · ([AnchorContext](https://github.com/haonan3/AnchorContext) - haonan3) ![Star](https://img.shields.io/github/stars/haonan3/AnchorContext.svg?style=social&label=Star)
- **Long Term Memory: The Foundation of AI Self-Evolution**, `arXiv, 2410.15665`, [arxiv](http://arxiv.org/abs/2410.15665v2), [pdf](http://arxiv.org/pdf/2410.15665v2.pdf), cication: [**-1**](None) 

	 *Xun Jiang, Feng Li, Han Zhao, ..., Mengdi Wang, Tianqiao Chen* · ([𝕏](https://x.com/TankaChat/status/1857272126358880267))
- **Large Language Models Can Self-Improve in Long-context Reasoning**, `arXiv, 2411.08147`, [arxiv](http://arxiv.org/abs/2411.08147v1), [pdf](http://arxiv.org/pdf/2411.08147v1.pdf), cication: [**-1**](None) 

	 *Siheng Li, Cheng Yang, Zesen Cheng, ..., Yujiu Yang, Wai Lam*
- **KV-Compress: Paged KV-Cache Compression with Variable Compression Rates 
  per Attention Head**, `arXiv, 2410.00161`, [arxiv](http://arxiv.org/abs/2410.00161v2), [pdf](http://arxiv.org/pdf/2410.00161v2.pdf), cication: [**-1**](None) 

	 *Isaac Rehg*

	 · ([vllm-kvcompress](https://github.com/IsaacRe/vllm-kvcompress/tree/main?tab=readme-ov-file) - IsaacRe) ![Star](https://img.shields.io/github/stars/IsaacRe/vllm-kvcompress.svg?style=social&label=Star)
- **A Simple and Effective $L_2$ Norm-Based Strategy for KV Cache 
  Compression**, `arXiv, 2406.11430`, [arxiv](http://arxiv.org/abs/2406.11430v3), [pdf](http://arxiv.org/pdf/2406.11430v3.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=5168052951707843815&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Alessio Devoto, Yu Zhao, Simone Scardapane, ..., Pasquale Minervini*
- **Language Models can Self-Lengthen to Generate Long Texts**, `arXiv, 2410.23933`, [arxiv](http://arxiv.org/abs/2410.23933v1), [pdf](http://arxiv.org/pdf/2410.23933v1.pdf), cication: [**-1**](None) 

	 *Shanghaoran Quan, Tianyi Tang, Bowen Yu, ..., Jingren Zhou, Junyang Lin* · ([Self-Lengthen](https://github.com/QwenLM/Self-Lengthen) - QwenLM) ![Star](https://img.shields.io/github/stars/QwenLM/Self-Lengthen.svg?style=social&label=Star)
- **ShadowKV: KV Cache in Shadows for High-Throughput Long-Context LLM 
  Inference**, `arXiv, 2410.21465`, [arxiv](http://arxiv.org/abs/2410.21465v1), [pdf](http://arxiv.org/pdf/2410.21465v1.pdf), cication: [**-1**](None)

	 *Hanshi Sun, Li-Wen Chang, Wenlei Bao, ..., Yuejie Chi, Beidi Chen* · ([ShadowKV](https://github.com/bytedance/ShadowKV) - bytedance) ![Star](https://img.shields.io/github/stars/bytedance/ShadowKV.svg?style=social&label=Star)
- **LongReward: Improving Long-context Large Language Models with AI 
  Feedback**, `arXiv, 2410.21252`, [arxiv](http://arxiv.org/abs/2410.21252v1), [pdf](http://arxiv.org/pdf/2410.21252v1.pdf), cication: [**-1**](None)

	 *Jiajie Zhang, Zhongni Hou, Xin Lv, ..., Ling Feng, Juanzi Li* · ([LongReward](https://github.com/THUDM/LongReward) - THUDM) ![Star](https://img.shields.io/github/stars/THUDM/LongReward.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/datasets/THUDM/LongReward-10k))
- **In Defense of RAG in the Era of Long-Context Language Models**, `arXiv, 2409.01666`, [arxiv](http://arxiv.org/abs/2409.01666v1), [pdf](http://arxiv.org/pdf/2409.01666v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=3261789221345650637&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Tan Yu, Anbang Xu, Rama Akkiraju* · ([zyphra](https://www.zyphra.com/post/reaching-1b-context-length-with-rag))
- **LOGO -- Long cOntext aliGnment via efficient preference Optimization**, `arXiv, 2410.18533`, [arxiv](http://arxiv.org/abs/2410.18533v1), [pdf](http://arxiv.org/pdf/2410.18533v1.pdf), cication: [**-1**](None) 

	 *Zecheng Tang, Zechen Sun, Juntao Li, ..., Qiaoming Zhu, Min Zhang*
- **How to Train Long-Context Language Models (Effectively)**, `arXiv, 2410.02660`, [arxiv](http://arxiv.org/abs/2410.02660v1), [pdf](http://arxiv.org/pdf/2410.02660v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=16129934205797752579&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Tianyu Gao, Alexander Wettig, Howard Yen, ..., Danqi Chen*

	 · ([prolong](https://github.com/princeton-nlp/prolong?tab=readme-ov-file) - princeton-nlp) ![Star](https://img.shields.io/github/stars/princeton-nlp/prolong.svg?style=social&label=Star)
- **Why Does the Effective Context Length of LLMs Fall Short?**, `arXiv, 2410.18745`, [arxiv](http://arxiv.org/abs/2410.18745v1), [pdf](http://arxiv.org/pdf/2410.18745v1.pdf), cication: [**-1**](None) 

	 *Chenxin An, Jun Zhang, Ming Zhong, ..., Jingjing Xu, Lingpeng Kong*

	 · ([STRING](https://github.com/HKUNLP/STRING) - HKUNLP) ![Star](https://img.shields.io/github/stars/HKUNLP/STRING.svg?style=social&label=Star)
- **LLM$\times$MapReduce: Simplified Long-Sequence Processing using Large 
  Language Models**, `arXiv, 2410.09342`, [arxiv](http://arxiv.org/abs/2410.09342v1), [pdf](http://arxiv.org/pdf/2410.09342v1.pdf), cication: [**-1**](None)

	 *Zihan Zhou, Chong Li, Xinyi Chen, ..., Zhiyuan Liu, Maosong Sun*

## Evaluation


## Projects

- [**360-LLaMA-Factory**](https://github.com/Qihoo360/360-LLaMA-Factory) - Qihoo360 ![Star](https://img.shields.io/github/stars/Qihoo360/360-LLaMA-Factory.svg?style=social&label=Star)
- [**LLMTest_NeedleInAHaystack**](https://github.com/gkamradt/LLMTest_NeedleInAHaystack) - gkamradt ![Star](https://img.shields.io/github/stars/gkamradt/LLMTest_NeedleInAHaystack.svg?style=social&label=Star) 
- [**KVCache-Factory**](https://github.com/Zefan-Cai/KVCache-Factory) - Zefan-Cai ![Star](https://img.shields.io/github/stars/Zefan-Cai/KVCache-Factory.svg?style=social&label=Star) 
- [**Awesome-LLM-Long-Context-Modeling**](https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling) - Xnhyacinth ![Star](https://img.shields.io/github/stars/Xnhyacinth/Awesome-LLM-Long-Context-Modeling.svg?style=social&label=Star) 

## Misc
## Misc
- [Extending the Context Length to 1M Tokens!](http://qwenlm.github.io/blog/qwen2.5-turbo/) 