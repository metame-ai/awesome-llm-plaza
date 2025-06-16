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

- **EfficientLLM: Efficiency in Large Language Models**, `arXiv, 2505.13840`, [arxiv](http://arxiv.org/abs/2505.13840v1), [pdf](http://arxiv.org/pdf/2505.13840v1.pdf), cication: [**-1**](None) 

	 *Zhengqing Yuan, Weixiang Sun, Yixin Liu, ..., Lichao Sun, Yanfang Ye*
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

- **Hardware-Efficient Attention for Fast Decoding**, `arXiv, 2505.21487`, [arxiv](http://arxiv.org/abs/2505.21487v1), [pdf](http://arxiv.org/pdf/2505.21487v1.pdf), cication: [**-1**](None) 

	 *Ted Zadouri, Hubert Strauss, Tri Dao*
- **Shifting AI Efficiency From Model-Centric to Data-Centric Compression**, `arXiv, 2505.19147`, [arxiv](http://arxiv.org/abs/2505.19147v1), [pdf](http://arxiv.org/pdf/2505.19147v1.pdf), cication: [**-1**](None) 

	 *Xuyang Liu, Zichen Wen, Shaobo Wang, ..., Conghui He, Linfeng Zhang*
- **Insights into DeepSeek-V3: Scaling Challenges and Reflections on 
  Hardware for AI Architectures**, `arXiv, 2505.09343`, [arxiv](http://arxiv.org/abs/2505.09343v1), [pdf](http://arxiv.org/pdf/2505.09343v1.pdf), cication: [**-1**](None) 

	 *Chenggang Zhao, Chengqi Deng, Chong Ruan, ..., Yuxuan Liu, Y. X. Wei*
- **Q-Filters: Leveraging QK Geometry for Efficient KV Cache Compression**, `arXiv, 2503.02812`, [arxiv](http://arxiv.org/abs/2503.02812v1), [pdf](http://arxiv.org/pdf/2503.02812v1.pdf), cication: [**-1**](None) 

	 *Nathan Godey, Alessio Devoto, Yu Zhao, ..., Éric de la Clergerie, Benoît Sagot* · ([𝕏](https://x.com/nthngdy/status/1897301390470603245))
- **How Much Knowledge Can You Pack into a LoRA Adapter without Harming LLM?**, `arXiv, 2502.14502`, [arxiv](http://arxiv.org/abs/2502.14502v2), [pdf](http://arxiv.org/pdf/2502.14502v2.pdf), cication: [**-1**](None) 

	 *Sergey Pletenev, Maria Marina, Daniil Moskovskiy, ..., Alexander Panchenko, Mikhail Salnikov*
- **Make LoRA Great Again: Boosting LoRA with Adaptive Singular Values and 
  Mixture-of-Experts Optimization Alignment**, `arXiv, 2502.16894`, [arxiv](http://arxiv.org/abs/2502.16894v2), [pdf](http://arxiv.org/pdf/2502.16894v2.pdf), cication: [**-1**](None) 

	 *Chenghao Fan, Zhenyi Lu, Sichen Liu, ..., Chengfeng Gu, Yu Cheng*
- 🌟 **Native Sparse Attention: Hardware-Aligned and Natively Trainable Sparse 
  Attention**, `arXiv, 2502.11089`, [arxiv](http://arxiv.org/abs/2502.11089v1), [pdf](http://arxiv.org/pdf/2502.11089v1.pdf), cication: [**-1**](None) 

	 *Jingyang Yuan, Huazuo Gao, Damai Dai, ..., Wenfeng Liang, Wangding Zeng* · ([𝕏](https://x.com/deepseek_ai/status/1891745487071609327))
- **iFormer: Integrating ConvNet and Transformer for Mobile Application**, `arXiv, 2501.15369`, [arxiv](http://arxiv.org/abs/2501.15369v1), [pdf](http://arxiv.org/pdf/2501.15369v1.pdf), cication: [**-1**](None) 

	 *Chuanyang Zheng*

	 · ([iFormer](https://github.com/ChuanyangZheng/iFormer) - ChuanyangZheng) ![Star](https://img.shields.io/github/stars/ChuanyangZheng/iFormer.svg?style=social&label=Star)
- 🌟 **Reward-Guided Speculative Decoding for Efficient LLM Reasoning**, `arXiv, 2501.19324`, [arxiv](http://arxiv.org/abs/2501.19324v2), [pdf](http://arxiv.org/pdf/2501.19324v2.pdf), cication: [**-1**](None) 

	 *Baohao Liao, Yuhui Xu, Hanze Dong, ..., Doyen Sahoo, Caiming Xiong*
- **Distillation Scaling Laws**, `arXiv, 2502.08606`, [arxiv](http://arxiv.org/abs/2502.08606v1), [pdf](http://arxiv.org/pdf/2502.08606v1.pdf), cication: [**-1**](None) 

	 *Dan Busbridge, Amitis Shidani, Floris Weers, ..., Etai Littwin, Russ Webb*
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

- **Matryoshka Quantization**, `arXiv, 2502.06786`, [arxiv](http://arxiv.org/abs/2502.06786v1), [pdf](http://arxiv.org/pdf/2502.06786v1.pdf), cication: [**-1**](None) 

	 *Pranav Nair, Puranjay Datta, Jeff Dean, ..., Prateek Jain, Aditya Kusupati*
- **Optimizing Large Language Model Training Using FP4 Quantization**, `arXiv, 2501.17116`, [arxiv](http://arxiv.org/abs/2501.17116v1), [pdf](http://arxiv.org/pdf/2501.17116v1.pdf), cication: [**-1**](None) 

	 *Ruizhe Wang, Yeyun Gong, Xiao Liu, ..., Zhengjun Zha, Peng Cheng*
- **QuEST: Stable Training of LLMs with 1-Bit Weights and Activations**, `arXiv, 2502.05003`, [arxiv](http://arxiv.org/abs/2502.05003v1), [pdf](http://arxiv.org/pdf/2502.05003v1.pdf), cication: [**-1**](None) 

	 *Andrei Panferov, Jiale Chen, Soroush Tabesh, ..., Mahdi Nikdan, Dan Alistarh* · ([QuEST](https://github.com/IST-DASLab/QuEST) - IST-DASLab) ![Star](https://img.shields.io/github/stars/IST-DASLab/QuEST.svg?style=social&label=Star)
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

- **Distilling LLM Agent into Small Models with Retrieval and Code Tools**, `arXiv, 2505.17612`, [arxiv](http://arxiv.org/abs/2505.17612v1), [pdf](http://arxiv.org/pdf/2505.17612v1.pdf), cication: [**-1**](None) 

	 *Minki Kang, Jongwon Jeong, Seanie Lee, ..., Jaewoong Cho, Sung Ju Hwang* · ([agent-distillation](https://github.com/Nardien/agent-distillation) - Nardien) ![Star](https://img.shields.io/github/stars/Nardien/agent-distillation.svg?style=social&label=Star)
- **Antidistillation Sampling**, `arXiv, 2504.13146`, [arxiv](http://arxiv.org/abs/2504.13146v2), [pdf](http://arxiv.org/pdf/2504.13146v2.pdf), cication: [**-1**](None) 

	 *Yash Savani, Asher Trockman, Zhili Feng, ..., Marc Finzi, J. Zico Kolter*
- [TAID: Temporally Adaptive Interpolated Distillation for Efficient Knowledge Transfer in Language Models](https://openreview.net/forum?id=cqsw28DuMW) 
- **TAID: Temporally Adaptive Interpolated Distillation for Efficient 
  Knowledge Transfer in Language Models**, `arXiv, 2501.16937`, [arxiv](http://arxiv.org/abs/2501.16937v2), [pdf](http://arxiv.org/pdf/2501.16937v2.pdf), cication: [**-1**](None) 

	 *Makoto Shing, Kou Misaki, Han Bao, ..., Sho Yokoi, Takuya Akiba* · ([TAID](https://github.com/SakanaAI/TAID) - SakanaAI) ![Star](https://img.shields.io/github/stars/SakanaAI/TAID.svg?style=social&label=Star)
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

- 🌟 **SEAP: Training-free Sparse Expert Activation Pruning Unlock the 
  Brainpower of Large Language Models**, `arXiv, 2503.07605`, [arxiv](http://arxiv.org/abs/2503.07605v1), [pdf](http://arxiv.org/pdf/2503.07605v1.pdf), cication: [**-1**](None) 

	 *Xun Liang, Hanyu Wang, Huayi Lai, ..., Bo Tang, Zhiyu Li*
- **The Super Weight in Large Language Models**, `arXiv, 2411.07191`, [arxiv](http://arxiv.org/abs/2411.07191v1), [pdf](http://arxiv.org/pdf/2411.07191v1.pdf), cication: [**-1**](None) 

	 *Mengxia Yu, De Wang, Qi Shan, ..., Colorado Reed, Alvin Wan*
- **Sparsing Law: Towards Large Language Models with Greater Activation 
  Sparsity**, `arXiv, 2411.02335`, [arxiv](http://arxiv.org/abs/2411.02335v1), [pdf](http://arxiv.org/pdf/2411.02335v1.pdf), cication: [**-1**](None) 

	 *Yuqi Luo, Chenyang Song, Xu Han, ..., Zhiyuan Liu, Maosong Sun*
- **What Matters in Transformers? Not All Attention is Needed**, `arXiv, 2406.15786`, [arxiv](http://arxiv.org/abs/2406.15786v6), [pdf](http://arxiv.org/pdf/2406.15786v6.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=18204847320375312044&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Shwai He, Guoheng Sun, Zheyu Shen, ..., Ang Li*

## Inference

- [**nano-vllm**](https://github.com/GeeeekExplorer/nano-vllm) - GeeeekExplorer ![Star](https://img.shields.io/github/stars/GeeeekExplorer/nano-vllm.svg?style=social&label=Star)
- [Look Ma, No Bubbles! Designing a Low-Latency Megakernel for Llama-1B](https://hazyresearch.stanford.edu/blog/2025-05-27-no-bubbles) 
- [Deploying DeepSeek with PD Disaggregation and Large-Scale Expert Parallelism on 96 H100 GPUs](https://lmsys.org/blog/2025-05-05-large-scale-ep/) 
- **A Survey on Inference Engines for Large Language Models: Perspectives on 
  Optimization and Efficiency**, `arXiv, 2505.01658`, [arxiv](http://arxiv.org/abs/2505.01658v2), [pdf](http://arxiv.org/pdf/2505.01658v2.pdf), cication: [**-1**](None) 

	 *Sihyeong Park, Sungryeol Jeon, Chaelyn Lee, ..., Byung-Soo Kim, Jemin Lee* · ([Awesome-LLM-Inference-Engine](https://github.com/sihyeong/Awesome-LLM-Inference-Engine) - sihyeong) ![Star](https://img.shields.io/github/stars/sihyeong/Awesome-LLM-Inference-Engine.svg?style=social&label=Star)
- **RetroInfer: A Vector-Storage Approach for Scalable Long-Context LLM 
  Inference**, `arXiv, 2505.02922`, [arxiv](http://arxiv.org/abs/2505.02922v1), [pdf](http://arxiv.org/pdf/2505.02922v1.pdf), cication: [**-1**](None) 

	 *Yaoqi Chen, Jinkai Zhang, Baotong Lu, ..., Fan Yang, Mao Yang* · ([RetrievalAttention](https://github.com/microsoft/RetrievalAttention) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/RetrievalAttention.svg?style=social&label=Star)
- **70% Size, 100% Accuracy: Lossless LLM Compression for Efficient GPU 
  Inference via Dynamic-Length Float**, `arXiv, 2504.11651`, [arxiv](http://arxiv.org/abs/2504.11651v1), [pdf](http://arxiv.org/pdf/2504.11651v1.pdf), cication: [**-1**](None) 

	 *Tianyi Zhang, Yang Sui, Shaochen Zhong, ..., Xia Hu, Anshumali Shrivastava* · ([DFloat11](https://github.com/LeanModels/DFloat11) - LeanModels) ![Star](https://img.shields.io/github/stars/LeanModels/DFloat11.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/DFloat11))
- 🌟 **PRIMA.CPP: Speeding Up 70B-Scale LLM Inference on Low-Resource Everyday 
  Home Clusters**, `arXiv, 2504.08791`, [arxiv](http://arxiv.org/abs/2504.08791v1), [pdf](http://arxiv.org/pdf/2504.08791v1.pdf), cication: [**-1**](None) 

	 *Zonghang Li, Tao Li, Wenjiao Feng, ..., Mohsen Guizani, Hongfang Yu* · ([prima.cpp.](https://github.com/Lizonghang/prima.cpp.) - Lizonghang) ![Star](https://img.shields.io/github/stars/Lizonghang/prima.cpp..svg?style=social&label=Star)
- [**skypilot**](https://github.com/skypilot-org/skypilot) - skypilot-org ![Star](https://img.shields.io/github/stars/skypilot-org/skypilot.svg?style=social&label=Star) 
- **Hogwild! Inference: Parallel LLM Generation via Concurrent Attention**, `arXiv, 2504.06261`, [arxiv](http://arxiv.org/abs/2504.06261v2), [pdf](http://arxiv.org/pdf/2504.06261v2.pdf), cication: [**-1**](None) 

	 *Gleb Rodionov, Roman Garipov, Alina Shutova, ..., Denis Kuznedelev, Dan Alistarh*
- **EAGLE-3: Scaling up Inference Acceleration of Large Language Models via 
  Training-Time Test**, `arXiv, 2503.01840`, [arxiv](http://arxiv.org/abs/2503.01840v1), [pdf](http://arxiv.org/pdf/2503.01840v1.pdf), cication: [**-1**](None) 

	 *Yuhui Li, Fangyun Wei, Chao Zhang, ..., Hongyang Zhang* · ([EAGLE.](https://github.com/SafeAILab/EAGLE.) - SafeAILab) ![Star](https://img.shields.io/github/stars/SafeAILab/EAGLE..svg?style=social&label=Star)
- **From Hours to Minutes: Lossless Acceleration of Ultra Long Sequence 
  Generation up to 100K Tokens**, `arXiv, 2502.18890`, [arxiv](http://arxiv.org/abs/2502.18890v1), [pdf](http://arxiv.org/pdf/2502.18890v1.pdf), cication: [**-1**](None) 

	 *Tong Wu, Junzhe Shen, Zixia Jia, ..., Yuxuan Wang, Zilong Zheng* · ([TokenSwift](https://github.com/bigai-nlco/TokenSwift) - bigai-nlco) ![Star](https://img.shields.io/github/stars/bigai-nlco/TokenSwift.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/abs/2502.18890)) · ([huggingface](https://huggingface.co/TokenSwift))
- **SpargeAttn: Accurate Sparse Attention Accelerating Any Model Inference**, `arXiv, 2502.18137`, [arxiv](http://arxiv.org/abs/2502.18137v1), [pdf](http://arxiv.org/pdf/2502.18137v1.pdf), cication: [**-1**](None) 

	 *Jintao Zhang, Chendong Xiang, Haofeng Huang, ..., Jun Zhu, Jianfei Chen* · ([SpargeAttn](https://github.com/thu-ml/SpargeAttn) - thu-ml) ![Star](https://img.shields.io/github/stars/thu-ml/SpargeAttn.svg?style=social&label=Star)
- **Autellix: An Efficient Serving Engine for LLM Agents as General Programs**, `arXiv, 2502.13965`, [arxiv](http://arxiv.org/abs/2502.13965v1), [pdf](http://arxiv.org/pdf/2502.13965v1.pdf), cication: [**-1**](None) 

	 *Michael Luo, Xiaoxiang Shi, Colin Cai, ..., Joseph E. Gonzalez, Ion Stoica*
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

- **Towards Economical Inference: Enabling DeepSeek's Multi-Head Latent 
  Attention in Any Transformer-based LLMs**, `arXiv, 2502.14837`, [arxiv](http://arxiv.org/abs/2502.14837v1), [pdf](http://arxiv.org/pdf/2502.14837v1.pdf), cication: [**-1**](None) 

	 *Tao Ji, Bin Guo, Yuanbin Wu, ..., Qi Zhang, Tao Gui* · ([MHA2MLA](https://github.com/JT-Ushio/MHA2MLA) - JT-Ushio) ![Star](https://img.shields.io/github/stars/JT-Ushio/MHA2MLA.svg?style=social&label=Star)
- 🌟 **Transformers without Normalization**, `arXiv, 2503.10622`, [arxiv](http://arxiv.org/abs/2503.10622v1), [pdf](http://arxiv.org/pdf/2503.10622v1.pdf), cication: [**-1**](None) 

	 *Jiachen Zhu, Xinlei Chen, Kaiming He, ..., Yann LeCun, Zhuang Liu*
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

- **Ladder-residual: parallelism-aware architecture for accelerating large 
  model inference with communication overlapping**, `arXiv, 2501.06589`, [arxiv](http://arxiv.org/abs/2501.06589v4), [pdf](http://arxiv.org/pdf/2501.06589v4.pdf), cication: [**-1**](None) 

	 *Muru Zhang, Mayank Mishra, Zhongzhu Zhou, ..., Ben Athiwaratkun, Tri Dao* · ([ladder-residual-inference](https://github.com/mayank31398/ladder-residual-inference) - mayank31398) ![Star](https://img.shields.io/github/stars/mayank31398/ladder-residual-inference.svg?style=social&label=Star) · ([𝕏](https://x.com/zhang_muru/status/1886870194443968529))
- [database of Machine Learning Hardware](https://x.com/EpochAIResearch/status/1849135255833158124)  𝕏 

## Tutorials

- [Dynamic  Sparsity  in  Machine  Learning](https://dynamic-sparsity.github.io/) 
- :clapper: [Lecture 32: Unsloth](https://www.youtube.com/watch?v=hfb_AIhDYnA) 

## Projects

- [**flux**](https://github.com/bytedance/flux) - bytedance ![Star](https://img.shields.io/github/stars/bytedance/flux.svg?style=social&label=Star) 
- [**MoBA**](https://github.com/MoonshotAI/MoBA) - MoonshotAI ![Star](https://img.shields.io/github/stars/MoonshotAI/MoBA.svg?style=social&label=Star) 

	 *Mixture of Block Attention for Long-Context LLMs* · ([MoBA](https://github.com/MoonshotAI/MoBA/blob/master/MoBA_Tech_Report.pdf) - MoonshotAI) ![Star](https://img.shields.io/github/stars/MoonshotAI/MoBA.svg?style=social&label=Star) · ([zhuanlan.zhihu](https://zhuanlan.zhihu.com/p/24642612039?utm_campaign=shareopn&utm_medium=social&utm_psn=1875312875339395072&utm_source=wechat_timeline&wechatShare=1&s_r=0&utm_id=0))
- [**LLMcalc**](https://github.com/Raskoll2/LLMcalc) - Raskoll2 ![Star](https://img.shields.io/github/stars/Raskoll2/LLMcalc.svg?style=social&label=Star) 
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