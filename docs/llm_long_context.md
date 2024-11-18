# LLM Long Context

- [LLM Long Context](#llm-long-context) 
  - [Survey](#survey)
  - [Long Context](#long-context)
  - [Evaluation](#evaluation)
  - [Projects](#projects)
  - [Misc](#misc)


## Survey


## Long Context

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

- [**Awesome-LLM-Long-Context-Modeling**](https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling) - Xnhyacinth ![Star](https://img.shields.io/github/stars/Xnhyacinth/Awesome-LLM-Long-Context-Modeling.svg?style=social&label=Star) 

## Misc