# LLM Training

- [LLM Training](#llm-training) 
	- [Survey](#survey)
	- [LLM Training](#llm-training-1)
	- [Pretraining](#pretraining)
	- [Post Training](#post-training)
	- [Finetuning](#finetuning)
	- [Optimization](#optimization)
	- [Architecture](#architecture)
	- [Mixture Of Experts](#mixture-of-experts)
	- [Merge](#merge)
	- [Online Learning](#online-learning)
	- [Toolkits](#toolkits)
	- [Misc](#misc)


## Survey

- [**awesome-open-source-lms**](https://github.com/allenai/awesome-open-source-lms) - allenai ![Star](https://img.shields.io/github/stars/allenai/awesome-open-source-lms.svg?style=social&label=Star) 

	 · ([docs.google](https://docs.google.com/presentation/d/179dpzWSQ9G7EAUlvaJdeE0av9PLuk9Rl33nfhHSJ4xI/edit?usp=sharing))

## LLM Training

- **On the Generalization of SFT: A Reinforcement Learning Perspective with 
  Reward Rectification**, `arXiv, 2508.05629`, [arxiv](http://arxiv.org/abs/2508.05629v1), [pdf](http://arxiv.org/pdf/2508.05629v1.pdf), cication: [**-1**](None) 

	 *Yongliang Wu, Yizhou Zhou, Zhou Ziheng, ..., Ming-Hsuan Yang, Xu Yang* · ([DFT.](https://github.com/yongliang-wu/DFT.) - yongliang-wu) ![Star](https://img.shields.io/github/stars/yongliang-wu/DFT..svg?style=social&label=Star)
- **Scaling Laws for Optimal Data Mixtures**, `arXiv, 2507.09404`, [arxiv](http://arxiv.org/abs/2507.09404v1), [pdf](http://arxiv.org/pdf/2507.09404v1.pdf), cication: [**-1**](None) 

	 *Mustafa Shukor, Louis Bethune, Dan Busbridge, ..., Alaaeldin El-Nouby, Pierre Ablin*
- 🌟 **Reinforcement Pre-Training**, `arXiv, 2506.08007`, [arxiv](http://arxiv.org/abs/2506.08007v1), [pdf](http://arxiv.org/pdf/2506.08007v1.pdf), cication: [**-1**](None) 

	 *Qingxiu Dong, Li Dong, Yao Tang, ..., Zhifang Sui, Furu Wei*
- **Estimating the Effects of Sample Training Orders for Large Language 
  Models without Retraining**, `arXiv, 2505.22042`, [arxiv](http://arxiv.org/abs/2505.22042v1), [pdf](http://arxiv.org/pdf/2505.22042v1.pdf), cication: [**-1**](None) 

	 *Hao Yang, Haoxuan Li, Mengyue Yang, ..., Xu Chen, Mingming Gong*
- **Parallel Scaling Law for Language Models**, `arXiv, 2505.10475`, [arxiv](http://arxiv.org/abs/2505.10475v1), [pdf](http://arxiv.org/pdf/2505.10475v1.pdf), cication: [**-1**](None) 

	 *Mouxiang Chen, Binyuan Hui, Zeyu Cui, ..., Junyang Lin, Zhongxin Liu* · ([ParScale](https://github.com/QwenLM/ParScale) - QwenLM) ![Star](https://img.shields.io/github/stars/QwenLM/ParScale.svg?style=social&label=Star)
- **CLIMB: CLustering-based Iterative Data Mixture Bootstrapping for 
  Language Model Pre-training**, `arXiv, 2504.13161`, [arxiv](http://arxiv.org/abs/2504.13161v1), [pdf](http://arxiv.org/pdf/2504.13161v1.pdf), cication: [**-1**](None) 

	 *Shizhe Diao, Yu Yang, Yonggan Fu, ..., Jan Kautz, Pavlo Molchanov* · ([research.nvidia](https://research.nvidia.com/labs/lpr/climb/))
- 🌟 **ZClip: Adaptive Spike Mitigation for LLM Pre-Training**, `arXiv, 2504.02507`, [arxiv](http://arxiv.org/abs/2504.02507v1), [pdf](http://arxiv.org/pdf/2504.02507v1.pdf), cication: [**-1**](None) 

	 *Abhay Kumar, Louis Owen, Nilabhra Roy Chowdhury, ..., Fabian Güra* · ([ZClip.](https://github.com/bluorion-com/ZClip.) - bluorion-com) ![Star](https://img.shields.io/github/stars/bluorion-com/ZClip..svg?style=social&label=Star)
- 🌟 [The Ultra-Scale Playbook: Training LLMs on GPU Clusters](https://huggingface.co/spaces/nanotron/ultrascale-playbook)  🤗 
- **Gemstones: A Model Suite for Multi-Faceted Scaling Laws**, `arXiv, 2502.06857`, [arxiv](http://arxiv.org/abs/2502.06857v1), [pdf](http://arxiv.org/pdf/2502.06857v1.pdf), cication: [**-1**](None) 

	 *Sean McLeish, John Kirchenbauer, David Yu Miller, ..., Ashwinee Panda, Tom Goldstein* · ([huggingface](https://huggingface.co/collections/tomg-group-umd/gemstone-models-679408ee3f19f1d4d00e8b10)) · ([gemstone-scaling-laws](https://github.com/mcleish7/gemstone-scaling-laws) - mcleish7) ![Star](https://img.shields.io/github/stars/mcleish7/gemstone-scaling-laws.svg?style=social&label=Star)
- **Optimizing Large Language Model Training Using FP4 Quantization**, `arXiv, 2501.17116`, [arxiv](http://arxiv.org/abs/2501.17116v1), [pdf](http://arxiv.org/pdf/2501.17116v1.pdf), cication: [**-1**](None) 

	 *Ruizhe Wang, Yeyun Gong, Xiao Liu, ..., Zhengjun Zha, Peng Cheng*
- **Scaling Embedding Layers in Language Models**, `arXiv, 2502.01637`, [arxiv](http://arxiv.org/abs/2502.01637v1), [pdf](http://arxiv.org/pdf/2502.01637v1.pdf), cication: [**-1**](None) 

	 *Da Yu, Edith Cohen, Badih Ghazi, ..., Daogao Liu, Chiyuan Zhang*
- **RandLoRA: Full-rank parameter-efficient fine-tuning of large models**, `arXiv, 2502.00987`, [arxiv](http://arxiv.org/abs/2502.00987v1), [pdf](http://arxiv.org/pdf/2502.00987v1.pdf), cication: [**-1**](None) 

	 *Paul Albert, Frederic Z. Zhang, Hemanth Saratchandran, ..., Anton van den Hengel, Ehsan Abbasnejad*
- 🌟 [How to Scale Your Model](https://jax-ml.github.io/scaling-book/) 
- **Streaming DiLoCo with overlapping communication: Towards a Distributed 
  Free Lunch**, `arXiv, 2501.18512`, [arxiv](http://arxiv.org/abs/2501.18512v1), [pdf](http://arxiv.org/pdf/2501.18512v1.pdf), cication: [**-1**](None) 

	 *Arthur Douillard, Yanislav Donchev, Keith Rush, ..., Marc'Aurelio Ranzato, Paul Barham*
- **Grokking at the Edge of Numerical Stability**, `arXiv, 2501.04697`, [arxiv](http://arxiv.org/abs/2501.04697v1), [pdf](http://arxiv.org/pdf/2501.04697v1.pdf), cication: [**-1**](None) 

	 *Lucas Prieto, Melih Barsbey, Pedro A. M. Mediano, ..., Tolga Birdal* · ([grokking-at-the-edge-of-numerical-stability.](https://github.com/LucasPrietoAl/grokking-at-the-edge-of-numerical-stability.) - LucasPrietoAl) ![Star](https://img.shields.io/github/stars/LucasPrietoAl/grokking-at-the-edge-of-numerical-stability..svg?style=social&label=Star)
- **Scaling Laws for Floating Point Quantization Training**, `arXiv, 2501.02423`, [arxiv](http://arxiv.org/abs/2501.02423v1), [pdf](http://arxiv.org/pdf/2501.02423v1.pdf), cication: [**-1**](None) 

	 *Xingwu Sun, Shuaipeng Li, Ruobing Xie, ..., Di Wang, Jie Jiang*
- [Flash LLMs: Pipeline Parallel](https://www.youtube.com/watch?v=76gulNlhiE4&list=PLO45-80-XKkT6BUKCYeBMTEqnlcpYavxq&index=1)  :clapper: 
- [**360-LLaMA-Factory**](https://github.com/Qihoo360/360-LLaMA-Factory) - Qihoo360 ![Star](https://img.shields.io/github/stars/Qihoo360/360-LLaMA-Factory.svg?style=social&label=Star) 
- **Metadata Conditioning Accelerates Language Model Pre-training**, `arXiv, 2501.01956`, [arxiv](http://arxiv.org/abs/2501.01956v1), [pdf](http://arxiv.org/pdf/2501.01956v1.pdf), cication: [**-1**](None) 

	 *Tianyu Gao, Alexander Wettig, Luxi He, ..., Sadhika Malladi, Danqi Chen* · ([MeCo](https://github.com/princeton-pli/MeCo) - princeton-pli) ![Star](https://img.shields.io/github/stars/princeton-pli/MeCo.svg?style=social&label=Star)
- 🌟 [**picotron**](https://github.com/huggingface/picotron) - huggingface ![Star](https://img.shields.io/github/stars/huggingface/picotron.svg?style=social&label=Star) 

	 *The minimalist & most-hackable repository for pre-training Llama-like models with 4D Parallelism* · ([youtube](https://www.youtube.com/playlist?list=PL-_armZiJvAnhcRr6yTJ0__f3Oi-LLi9S))
- **Multi-matrix Factorization Attention**, `arXiv, 2412.19255`, [arxiv](http://arxiv.org/abs/2412.19255v1), [pdf](http://arxiv.org/pdf/2412.19255v1.pdf), cication: [**-1**](None) 

	 *Jingcheng Hu, Houyi Li, Yinmin Zhang, ..., Xiangyu Zhang, Heung-Yeung Shum*
- **Rate of Model Collapse in Recursive Training**, `arXiv, 2412.17646`, [arxiv](http://arxiv.org/abs/2412.17646v1), [pdf](http://arxiv.org/pdf/2412.17646v1.pdf), cication: [**-1**](None) 

	 *Ananda Theertha Suresh, Andrew Thangaraj, Aditya Nanda Kishore Khandavally*
- [[10 December 2024, NeurIPs] Tutorial on Language Modeling](https://docs.google.com/presentation/d/179dpzWSQ9G7EAUlvaJdeE0av9PLuk9Rl33nfhHSJ4xI/edit) 
- **Establishing Task Scaling Laws via Compute-Efficient Model Ladders**, `arXiv, 2412.04403`, [arxiv](http://arxiv.org/abs/2412.04403v1), [pdf](http://arxiv.org/pdf/2412.04403v1.pdf), cication: [**-1**](None) 

	 *Akshita Bhagia, Jiacheng Liu, Alexander Wettig, ..., Jesse Dodge, Hannaneh Hajishirzi* · ([𝕏](https://x.com/liujc1998/status/1866161269012873312))
- **Q-SFT: Q-Learning for Language Models via Supervised Fine-Tuning**, `arXiv, 2411.05193`, [arxiv](http://arxiv.org/abs/2411.05193v2), [pdf](http://arxiv.org/pdf/2411.05193v2.pdf), cication: [**-1**](None) 

	 *Joey Hong, Anca Dragan, Sergey Levine* · ([𝕏](https://x.com/svlevine/status/1860874248166027683))
- 🌟 **Predicting Emergent Capabilities by Finetuning**, `arXiv, 2411.16035`, [arxiv](http://arxiv.org/abs/2411.16035v1), [pdf](http://arxiv.org/pdf/2411.16035v1.pdf), cication: [**-1**](None) 

	 *Charlie Snell, Eric Wallace, Dan Klein, ..., Sergey Levine* · ([𝕏](https://x.com/sea_snell/status/1861538504024416365))
- 🌟 **Observational Scaling Laws and the Predictability of Language Model 
  Performance**, `arXiv, 2405.10938`, [arxiv](http://arxiv.org/abs/2405.10938v3), [pdf](http://arxiv.org/pdf/2405.10938v3.pdf), cication: [**-1**](None) 

	 *Yangjun Ruan, Chris J. Maddison, Tatsunori Hashimoto*
- **Balancing Pipeline Parallelism with Vocabulary Parallelism**, `arXiv, 2411.05288`, [arxiv](http://arxiv.org/abs/2411.05288v1), [pdf](http://arxiv.org/pdf/2411.05288v1.pdf), cication: [**-1**](None) 

	 *Man Tsung Yeung, Penghui Qi, Min Lin, ..., Xinyi Wan* · ([VocabularyParallelism](https://github.com/sail-sg/VocabularyParallelism) - sail-sg) ![Star](https://img.shields.io/github/stars/sail-sg/VocabularyParallelism.svg?style=social&label=Star)
- **Learning to (Learn at Test Time): RNNs with Expressive Hidden States**, `arXiv, 2407.04620`, [arxiv](http://arxiv.org/abs/2407.04620v2), [pdf](http://arxiv.org/pdf/2407.04620v2.pdf), cication: [**19**](https://scholar.google.com/scholar?cites=4859112994803550513&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Yu Sun, Xinhao Li, Karan Dalal, ..., Tatsunori Hashimoto, Carlos Guestrin* · ([yueatsprograms.github](https://yueatsprograms.github.io/ttt/home.html)) · ([ttt-lm-pytorch](https://github.com/test-time-training/ttt-lm-pytorch) - test-time-training) ![Star](https://img.shields.io/github/stars/test-time-training/ttt-lm-pytorch.svg?style=social&label=Star)
- **What Happened in LLMs Layers when Trained for Fast vs. Slow Thinking: A 
  Gradient Perspective**, `arXiv, 2410.23743`, [arxiv](http://arxiv.org/abs/2410.23743v1), [pdf](http://arxiv.org/pdf/2410.23743v1.pdf), cication: [**-1**](None)

	 *Ming Li, Yanhong Li, Tianyi Zhou* · ([Layer_Gradient](https://github.com/MingLiiii/Layer_Gradient) - MingLiiii) ![Star](https://img.shields.io/github/stars/MingLiiii/Layer_Gradient.svg?style=social&label=Star) · ([aimodels](https://www.aimodels.fyi/papers/arxiv/what-happened-llms-layers-when-trained-fast))

## Pretraining

- **MiniPLM: Knowledge Distillation for Pre-Training Language Models**, `arXiv, 2410.17215`, [arxiv](http://arxiv.org/abs/2410.17215v2), [pdf](http://arxiv.org/pdf/2410.17215v2.pdf), cication: [**-1**](None) 

	 *Yuxian Gu, Hao Zhou, Fandong Meng, ..., Jie Zhou, Minlie Huang*
- **Pre-training Distillation for Large Language Models: A Design Space 
  Exploration**, `arXiv, 2410.16215`, [arxiv](http://arxiv.org/abs/2410.16215v1), [pdf](http://arxiv.org/pdf/2410.16215v1.pdf), cication: [**-1**](None)

	 *Hao Peng, Xin Lv, Yushi Bai, ..., Lei Hou, Juanzi Li*

## Post Training


## Finetuning

- **$\text{Transformer}^2$: Self-adaptive LLMs**, `arXiv, 2501.06252`, [arxiv](http://arxiv.org/abs/2501.06252v2), [pdf](http://arxiv.org/pdf/2501.06252v2.pdf), cication: [**-1**](None) 

	 *Qi Sun, Edoardo Cetin, Yujin Tang*
- **Let the Expert Stick to His Last: Expert-Specialized Fine-Tuning for 
  Sparse Architectural Large Language Models**, `arXiv, 2407.01906`, [arxiv](http://arxiv.org/abs/2407.01906v2), [pdf](http://arxiv.org/pdf/2407.01906v2.pdf), cication: [**-1**](None) 

	 *Zihan Wang, Deli Chen, Damai Dai, ..., Zhuoshu Li, Y. Wu* · ([𝕏](https://x.com/wzihanw/status/1809089857320521899))
- **DELIFT: Data Efficient Language model Instruction Fine Tuning**, `arXiv, 2411.04425`, [arxiv](http://arxiv.org/abs/2411.04425v2), [pdf](http://arxiv.org/pdf/2411.04425v2.pdf), cication: [**-1**](None) 

	 *Ishika Agarwal, Krishnateja Killamsetty, Lucian Popa, ..., Marina Danilevksy* · ([𝕏](https://x.com/wonderingishika/status/1854770402590851119))
- **SemiEvol: Semi-supervised Fine-tuning for LLM Adaptation**, `arXiv, 2410.14745`, [arxiv](http://arxiv.org/abs/2410.14745v1), [pdf](http://arxiv.org/pdf/2410.14745v1.pdf), cication: [**-1**](None) 

	 *Junyu Luo, Xiao Luo, Xiusi Chen, ..., Wei Ju, Ming Zhang*

## Optimization

- **Practical Efficiency of Muon for Pretraining**, `arXiv, 2505.02222`, [arxiv](http://arxiv.org/abs/2505.02222v4), [pdf](http://arxiv.org/pdf/2505.02222v4.pdf), cication: [**-1**](None) 

	 *Essential AI, :, Ishaan Shah, ..., Yash Vanjani, Ashish Vaswani*
- [explored further to EXTREME beta values like 0.2](https://x.com/cloneofsimo/status/1903080158627762234)  𝕏 
- [**dolphinflow-optimizer**](https://github.com/cognitivecomputations/dolphinflow-optimizer) - cognitivecomputations ![Star](https://img.shields.io/github/stars/cognitivecomputations/dolphinflow-optimizer.svg?style=social&label=Star) 
- **Stable-SPAM: How to Train in 4-Bit More Stably than 16-Bit Adam**, `arXiv, 2502.17055`, [arxiv](http://arxiv.org/abs/2502.17055v1), [pdf](http://arxiv.org/pdf/2502.17055v1.pdf), cication: [**-1**](None) 

	 *Tianjin Huang, Haotian Hu, Zhenyu Zhang, ..., Zhangyang Wang, Shiwei Liu* · ([StableSPAM.git.](https://github.com/TianjinYellow/StableSPAM.git.) - TianjinYellow) ![Star](https://img.shields.io/github/stars/TianjinYellow/StableSPAM.git..svg?style=social&label=Star)
- **Harmonic Loss Trains Interpretable AI Models**, `arXiv, 2502.01628`, [arxiv](http://arxiv.org/abs/2502.01628v1), [pdf](http://arxiv.org/pdf/2502.01628v1.pdf), cication: [**-1**](None) 

	 *David D. Baek, Ziming Liu, Riya Tyagi, ..., Max Tegmark*
- [**C-Optim**](https://github.com/kyleliang919/C-Optim) - kyleliang919 ![Star](https://img.shields.io/github/stars/kyleliang919/C-Optim.svg?style=social&label=Star) 

	 *Improving Training with One Line of Code*
- **Spike No More: Stabilizing the Pre-training of Large Language Models**, `arXiv, 2312.16903`, [arxiv](http://arxiv.org/abs/2312.16903v3), [pdf](http://arxiv.org/pdf/2312.16903v3.pdf), cication: [**-1**](None) 

	 *Sho Takase, Shun Kiyono, Sosuke Kobayashi, ..., Jun Suzuki*
- **No More Adam: Learning Rate Scaling at Initialization is All You Need**, `arXiv, 2412.11768`, [arxiv](http://arxiv.org/abs/2412.11768v2), [pdf](http://arxiv.org/pdf/2412.11768v2.pdf), cication: [**-1**](None) 

	 *Minghao Xu, Lichuan Xiang, Xu Cai, ..., Hongkai Wen* · ([SGD_SaI](https://github.com/AnonymousAlethiometer/SGD_SaI) - AnonymousAlethiometer) ![Star](https://img.shields.io/github/stars/AnonymousAlethiometer/SGD_SaI.svg?style=social&label=Star)
- **Mix-LN: Unleashing the Power of Deeper Layers by Combining Pre-LN and 
  Post-LN**, `arXiv, 2412.13795`, [arxiv](http://arxiv.org/abs/2412.13795v1), [pdf](http://arxiv.org/pdf/2412.13795v1.pdf), cication: [**-1**](None) 

	 *Pengxiang Li, Lu Yin, Shiwei Liu* · ([MixLN.](https://github.com/pixeli99/MixLN.) - pixeli99) ![Star](https://img.shields.io/github/stars/pixeli99/MixLN..svg?style=social&label=Star)
- 🌟 [Muon scaling again](https://x.com/Yuchenj_UW/status/1846964136204173318)  𝕏 
- **APOLLO: SGD-like Memory, AdamW-level Performance**, `arXiv, 2412.05270`, [arxiv](http://arxiv.org/abs/2412.05270v2), [pdf](http://arxiv.org/pdf/2412.05270v2.pdf), cication: [**-1**](None) 

	 *Hanqing Zhu, Zhenyu Zhang, Wenyan Cong, ..., Zhangyang Wang, Jinwon Lee* · ([zhuhanqing.github](https://zhuhanqing.github.io/APOLLO/))
- **DeMo: Decoupled Momentum Optimization**, `arXiv, 2411.19870`, [arxiv](http://arxiv.org/abs/2411.19870v1), [pdf](http://arxiv.org/pdf/2411.19870v1.pdf), cication: [**-1**](None) 

	 *Bowen Peng, Jeffrey Quesnelle, Diederik P. Kingma* · ([DeMo](https://github.com/bloc97/DeMo) - bloc97) ![Star](https://img.shields.io/github/stars/bloc97/DeMo.svg?style=social&label=Star)
- **ADOPT: Modified Adam Can Converge with Any $β_2$ with the Optimal 
  Rate**, `arXiv, 2411.02853`, [arxiv](http://arxiv.org/abs/2411.02853v3), [pdf](http://arxiv.org/pdf/2411.02853v3.pdf), cication: [**-1**](None) 

	 *Shohei Taniguchi, Keno Harada, Gouki Minegishi, ..., Yusuke Iwasawa, Yutaka Matsuo* · ([adopt](https://github.com/iShohei220/adopt) - iShohei220) ![Star](https://img.shields.io/github/stars/iShohei220/adopt.svg?style=social&label=Star)
- [**unit-scaling**](https://github.com/graphcore-research/unit-scaling) - graphcore-research ![Star](https://img.shields.io/github/stars/graphcore-research/unit-scaling.svg?style=social&label=Star) 
- **Natural Language Reinforcement Learning**, `arXiv, 2411.14251`, [arxiv](http://arxiv.org/abs/2411.14251v1), [pdf](http://arxiv.org/pdf/2411.14251v1.pdf), cication: [**-1**](None) 

	 *Xidong Feng, Ziyu Wan, Haotian Fu, ..., Ying Wen, Jun Wang* · ([Natural-language-RL](https://github.com/waterhorse1/Natural-language-RL) - waterhorse1) ![Star](https://img.shields.io/github/stars/waterhorse1/Natural-language-RL.svg?style=social&label=Star)
- **Cautious Optimizers: Improving Training with One Line of Code**, `arXiv, 2411.16085`, [arxiv](http://arxiv.org/abs/2411.16085v1), [pdf](http://arxiv.org/pdf/2411.16085v1.pdf), cication: [**-1**](None) 

	 *Kaizhao Liang, Lizhang Chen, Bo Liu, ..., Qiang Liu* · ([C-Optim](https://github.com/kyleliang919/C-Optim) - kyleliang919) ![Star](https://img.shields.io/github/stars/kyleliang919/C-Optim.svg?style=social&label=Star) · ([qbitai](https://www.qbitai.com/2024/11/224904.html))
- **MARS: Unleashing the Power of Variance Reduction for Training Large 
  Models**, `arXiv, 2411.10438`, [arxiv](http://arxiv.org/abs/2411.10438v1), [pdf](http://arxiv.org/pdf/2411.10438v1.pdf), cication: [**-1**](None) 

	 *Huizhuo Yuan, Yifeng Liu, Shuang Wu, ..., Xun Zhou, Quanquan Gu* · ([MARS.](https://github.com/AGI-Arena/MARS.) - AGI-Arena) ![Star](https://img.shields.io/github/stars/AGI-Arena/MARS..svg?style=social&label=Star)
- **nGPT: Normalized Transformer with Representation Learning on the 
  Hypersphere**, `arXiv, 2410.01131`, [arxiv](http://arxiv.org/abs/2410.01131v1), [pdf](http://arxiv.org/pdf/2410.01131v1.pdf), cication: [**-1**](None) 

	 *Ilya Loshchilov, Cheng-Ping Hsieh, Simeng Sun, ..., Boris Ginsburg* · ([ngpt](https://github.com/NVIDIA/ngpt?tab=readme-ov-file) - NVIDIA) ![Star](https://img.shields.io/github/stars/NVIDIA/ngpt.svg?style=social&label=Star)
- **Top-$nσ$: Not All Logits Are You Need**, `arXiv, 2411.07641`, [arxiv](http://arxiv.org/abs/2411.07641v1), [pdf](http://arxiv.org/pdf/2411.07641v1.pdf), cication: [**-1**](None) 

	 *Chenxia Tang, Jianchun Liu, Hongli Xu, ..., Liusheng Huang* · ([top_nsigma](https://github.com/Tomorrowdawn/top_nsigma) - Tomorrowdawn) ![Star](https://img.shields.io/github/stars/Tomorrowdawn/top_nsigma.svg?style=social&label=Star)
- **Cut Your Losses in Large-Vocabulary Language Models**, `arXiv, 2411.09009`, [arxiv](http://arxiv.org/abs/2411.09009v1), [pdf](http://arxiv.org/pdf/2411.09009v1.pdf), cication: [**-1**](None) 

	 *Erik Wijmans, Brody Huval, Alexander Hertzberg, ..., Vladlen Koltun, Philipp Krähenbühl* · ([ml-cross-entropy](https://github.com/apple/ml-cross-entropy) - apple) ![Star](https://img.shields.io/github/stars/apple/ml-cross-entropy.svg?style=social&label=Star)
- [The Practitioner’s Guide to the Maximal Update Parameterization](https://cerebras.ai/blog/the-practitioners-guide-to-the-maximal-update-parameterization/) 

	 · ([nanoGPT-mup](https://github.com/EleutherAI/nanoGPT-mup) - EleutherAI) ![Star](https://img.shields.io/github/stars/EleutherAI/nanoGPT-mup.svg?style=social&label=Star)
- **Polynomial Composition Activations: Unleashing the Dynamics of Large 
  Language Models**, `arXiv, 2411.03884`, [arxiv](http://arxiv.org/abs/2411.03884v1), [pdf](http://arxiv.org/pdf/2411.03884v1.pdf), cication: [**-1**](None) 

	 *Zhijian Zhuo, Ya Wang, Yutao Zeng, ..., Xun Zhou, Jinwen Ma* · ([PolyCom](https://github.com/BryceZhuo/PolyCom) - BryceZhuo) ![Star](https://img.shields.io/github/stars/BryceZhuo/PolyCom.svg?style=social&label=Star)
- **The Road Less Scheduled**, `arXiv, 2405.15682`, [arxiv](http://arxiv.org/abs/2405.15682v4), [pdf](http://arxiv.org/pdf/2405.15682v4.pdf), cication: [**-1**](None) 

	 *Aaron Defazio, Xingyu Alice Yang, Harsh Mehta, ..., Ahmed Khaled, Ashok Cutkosky* · ([schedule_free](https://github.com/facebookresearch/schedule_free) - facebookresearch) ![Star](https://img.shields.io/github/stars/facebookresearch/schedule_free.svg?style=social&label=Star)
- :clapper: [Hacks to Make LLM Training Faster - Daniel Han, Unsloth AI](https://www.youtube.com/watch?v=PdtKkc5jB4g) 

## Architecture

- **You Do Not Fully Utilize Transformer's Representation Capacity**, `arXiv, 2502.09245`, [arxiv](http://arxiv.org/abs/2502.09245v1), [pdf](http://arxiv.org/pdf/2502.09245v1.pdf), cication: [**-1**](None) 

	 *Gleb Gerasimov, Yaroslav Aksenov, Nikita Balagansky, ..., Viacheslav Sinii, Daniil Gavrilov* · ([𝕏](https://x.com/yaaksenov/status/1892206045579141227))
- **The Curse of Depth in Large Language Models**, `arXiv, 2502.05795`, [arxiv](http://arxiv.org/abs/2502.05795v1), [pdf](http://arxiv.org/pdf/2502.05795v1.pdf), cication: [**-1**](None) 

	 *Wenfang Sun, Xinyuan Song, Pengxiang Li, ..., Yefeng Zheng, Shiwei Liu*
- **TransMLA: Multi-Head Latent Attention Is All You Need**, `arXiv, 2502.07864`, [arxiv](http://arxiv.org/abs/2502.07864v2), [pdf](http://arxiv.org/pdf/2502.07864v2.pdf), cication: [**-1**](None) 

	 *Fanxu Meng, Zengwei Yao, Muhan Zhang*
- **Memory Layers at Scale**, `arXiv, 2412.09764`, [arxiv](http://arxiv.org/abs/2412.09764v2), [pdf](http://arxiv.org/pdf/2412.09764v2.pdf), cication: [**-1**](None) 

	 *Vincent-Pierre Berges, Barlas Oğuz, Daniel Haziza, ..., Luke Zettlemoyer, Gargi Ghosh*

## Mixture Of Experts

- **Stabilizing MoE Reinforcement Learning by Aligning Training and 
  Inference Routers**, `arXiv, 2510.11370`, [arxiv](http://arxiv.org/abs/2510.11370v1), [pdf](http://arxiv.org/pdf/2510.11370v1.pdf), cication: [**-1**](None) 

	 *Wenhan Ma, Hailin Zhang, Liang Zhao, ..., Zhifang Sui, Fuli Luo*
- **Chain-of-Experts: Unlocking the Communication Power of 
  Mixture-of-Experts Models**, `arXiv, 2506.18945`, [arxiv](http://arxiv.org/abs/2506.18945v1), [pdf](http://arxiv.org/pdf/2506.18945v1.pdf), cication: [**-1**](None) 

	 *Zihan Wang, Rui Pan, Jiarui Yao, ..., Manling Li, Shiwei Liu* · ([coe.](https://github.com/ZihanWang314/coe.) - ZihanWang314) ![Star](https://img.shields.io/github/stars/ZihanWang314/coe..svg?style=social&label=Star)
- [**flux**](https://github.com/bytedance/flux) - bytedance ![Star](https://img.shields.io/github/stars/bytedance/flux.svg?style=social&label=Star) 
- **Mixture of Experts Made Intrinsically Interpretable**, `arXiv, 2503.07639`, [arxiv](http://arxiv.org/abs/2503.07639v1), [pdf](http://arxiv.org/pdf/2503.07639v1.pdf), cication: [**-1**](None) 

	 *Xingyi Yang, Constantin Venhoff, Ashkan Khakzar, ..., Adel Bibi, Philip Torr*
- **MoM: Linear Sequence Modeling with Mixture-of-Memories**, `arXiv, 2502.13685`, [arxiv](http://arxiv.org/abs/2502.13685v1), [pdf](http://arxiv.org/pdf/2502.13685v1.pdf), cication: [**-1**](None) 

	 *Jusen Du, Weigao Sun, Disen Lan, ..., Jiaxi Hu, Yu Cheng* · ([Linear-MoE.](https://github.com/OpenSparseLLMs/Linear-MoE.) - OpenSparseLLMs) ![Star](https://img.shields.io/github/stars/OpenSparseLLMs/Linear-MoE..svg?style=social&label=Star)
- 🌟 **R2-T2: Re-Routing in Test-Time for Multimodal Mixture-of-Experts**, `arXiv, 2502.20395`, [arxiv](http://arxiv.org/abs/2502.20395v2), [pdf](http://arxiv.org/pdf/2502.20395v2.pdf), cication: [**-1**](None) 

	 *Zhongyang Li, Ziyue Li, Tianyi Zhou* · ([R2-T2](https://github.com/tianyi-lab/R2-T2) - tianyi-lab) ![Star](https://img.shields.io/github/stars/tianyi-lab/R2-T2.svg?style=social&label=Star)
- [**CoE**](https://github.com/ZihanWang314/CoE) - ZihanWang314 ![Star](https://img.shields.io/github/stars/ZihanWang314/CoE.svg?style=social&label=Star) 

	 *Unlocking the Communication Power of MoEs*
- **LASP-2: Rethinking Sequence Parallelism for Linear Attention and Its 
  Hybrid**, `arXiv, 2502.07563`, [arxiv](http://arxiv.org/abs/2502.07563v1), [pdf](http://arxiv.org/pdf/2502.07563v1.pdf), cication: [**-1**](None) 

	 *Weigao Sun, Disen Lan, Yiran Zhong, ..., Xiaoye Qu, Yu Cheng* · ([Linear-MoE](https://github.com/OpenSparseLLMs/Linear-MoE) - OpenSparseLLMs) ![Star](https://img.shields.io/github/stars/OpenSparseLLMs/Linear-MoE.svg?style=social&label=Star)
- **Parameters vs FLOPs: Scaling Laws for Optimal Sparsity for 
  Mixture-of-Experts Language Models**, `arXiv, 2501.12370`, [arxiv](http://arxiv.org/abs/2501.12370v2), [pdf](http://arxiv.org/pdf/2501.12370v2.pdf), cication: [**-1**](None) 

	 *Samira Abnar, Harshay Shah, Dan Busbridge, ..., Josh Susskind, Vimal Thilak*
- [详细谈谈DeepSeek MoE相关的技术发展](https://mp.weixin.qq.com/s/WFJxnTF9fGIIXPA7GQ5V2w) 
- **Autonomy-of-Experts Models**, `arXiv, 2501.13074`, [arxiv](http://arxiv.org/abs/2501.13074v1), [pdf](http://arxiv.org/pdf/2501.13074v1.pdf), cication: [**-1**](None) 

	 *Ang Lv, Ruobing Xie, Yining Qian, ..., Di Wang, Rui Yan*
- 🌟 **Demons in the Detail: On Implementing Load Balancing Loss for Training 
  Specialized Mixture-of-Expert Models**, `arXiv, 2501.11873`, [arxiv](http://arxiv.org/abs/2501.11873v1), [pdf](http://arxiv.org/pdf/2501.11873v1.pdf), cication: [**-1**](None) 

	 *Zihan Qiu, Zeyu Huang, Bo Zheng, ..., Jingren Zhou, Junyang Lin* · ([𝕏](https://x.com/Alibaba_Qwen/status/1882064440159596725))
- **ReMoE: Fully Differentiable Mixture-of-Experts with ReLU Routing**, `arXiv, 2412.14711`, [arxiv](http://arxiv.org/abs/2412.14711v1), [pdf](http://arxiv.org/pdf/2412.14711v1.pdf), cication: [**-1**](None) 

	 *Ziteng Wang, Jianfei Chen, Jun Zhu* · ([ReMoE](https://github.com/thu-ml/ReMoE) - thu-ml) ![Star](https://img.shields.io/github/stars/thu-ml/ReMoE.svg?style=social&label=Star)
- **ReMoE: Fully Differentiable Mixture-of-Experts with ReLU Routing**, `arXiv, 2412.14711`, [arxiv](http://arxiv.org/abs/2412.14711v1), [pdf](http://arxiv.org/pdf/2412.14711v1.pdf), cication: [**-1**](None) 

	 *Ziteng Wang, Jianfei Chen, Jun Zhu* · ([ReMoE](https://github.com/thu-ml/ReMoE) - thu-ml) ![Star](https://img.shields.io/github/stars/thu-ml/ReMoE.svg?style=social&label=Star)
- **MoDEM: Mixture of Domain Expert Models**, `arXiv, 2410.07490`, [arxiv](http://arxiv.org/abs/2410.07490v1), [pdf](http://arxiv.org/pdf/2410.07490v1.pdf), cication: [**-1**](None) 

	 *Toby Simonds, Kemal Kurniawan, Jey Han Lau* · ([reddit](https://www.reddit.com/r/LocalLLaMA/comments/1h06abs/modem_mixture_of_domain_expert_models/))
- **MH-MoE: Multi-Head Mixture-of-Experts**, `arXiv, 2411.16205`, [arxiv](http://arxiv.org/abs/2411.16205v2), [pdf](http://arxiv.org/pdf/2411.16205v2.pdf), cication: [**-1**](None) 

	 *Shaohan Huang, Xun Wu, Shuming Ma, ..., Furu Wei*
- **MoE Jetpack: From Dense Checkpoints to Adaptive Mixture of Experts for 
  Vision Tasks**, `arXiv, 2406.04801`, [arxiv](http://arxiv.org/abs/2406.04801v1), [pdf](http://arxiv.org/pdf/2406.04801v1.pdf), cication: [**-1**](None) 

	 *Xingkui Zhu, Yiran Guan, Dingkang Liang, ..., Yuliang Liu, Xiang Bai* · ([MoE-Jetpack](https://github.com/Adlith/MoE-Jetpack) - Adlith) ![Star](https://img.shields.io/github/stars/Adlith/MoE-Jetpack.svg?style=social&label=Star)
- [Overview of the Largest Mixture of Expert Models Released So Far](https://buttondown.com/ainews/archive/ainews-common-corpus-2t-open-tokens-with/) 

	 · ([reddit](https://reddit.com/r/LocalLLaMA/comments/1gprkxw/overview_of_the_largest_mixture_of_expert_models/))
- **LIBMoE: A Library for comprehensive benchmarking Mixture of Experts in 
  Large Language Models**, `arXiv, 2411.00918`, [arxiv](http://arxiv.org/abs/2411.00918v1), [pdf](http://arxiv.org/pdf/2411.00918v1.pdf), cication: [**-1**](None) 

	 *Nam V. Nguyen, Thong T. Doan, Luong Tran, ..., Van Nguyen, Quang Pham* · ([LibMoE](https://github.com/Fsoft-AIC/LibMoE) - Fsoft-AIC) ![Star](https://img.shields.io/github/stars/Fsoft-AIC/LibMoE.svg?style=social&label=Star)
- **Mixture of Parrots: Experts improve memorization more than reasoning**, `arXiv, 2410.19034`, [arxiv](http://arxiv.org/abs/2410.19034v1), [pdf](http://arxiv.org/pdf/2410.19034v1.pdf), cication: [**-1**](None) 

	 *Samy Jelassi, Clara Mohri, David Brandfonbrener, ..., Sham M. Kakade, Eran Malach*
- **Read-ME: Refactorizing LLMs as Router-Decoupled Mixture of Experts with 
  System Co-Design**, `arXiv, 2410.19123`, [arxiv](http://arxiv.org/abs/2410.19123v1), [pdf](http://arxiv.org/pdf/2410.19123v1.pdf), cication: [**-1**](None)

	 *Ruisi Cai, Yeonju Ro, Geon-Woo Kim, ..., Aditya Akella, Zhangyang Wang* · ([READ-ME](https://github.com/VITA-Group/READ-ME) - VITA-Group) ![Star](https://img.shields.io/github/stars/VITA-Group/READ-ME.svg?style=social&label=Star)
- **Stealing User Prompts from Mixture of Experts**, `arXiv, 2410.22884`, [arxiv](http://arxiv.org/abs/2410.22884v1), [pdf](http://arxiv.org/pdf/2410.22884v1.pdf), cication: [**-1**](None) 

	 *Itay Yona, Ilia Shumailov, Jamie Hayes, ..., Nicholas Carlini*

## Merge

- **Adapting Language-Specific LLMs to a Reasoning Model in One Day via 
  Model Merging - An Open Recipe**, `arXiv, 2502.09056`, [arxiv](http://arxiv.org/abs/2502.09056v2), [pdf](http://arxiv.org/pdf/2502.09056v2.pdf), cication: [**-1**](None) 

	 *Kunat Pipatanakul, Pittawat Taveekitworachai, Potsawee Manakul, ..., Kasima Tharnpipitchai*
- **Safeguard Fine-Tuned LLMs Through Pre- and Post-Tuning Model Merging**, `arXiv, 2412.19512`, [arxiv](http://arxiv.org/abs/2412.19512v1), [pdf](http://arxiv.org/pdf/2412.19512v1.pdf), cication: [**-1**](None) 

	 *Hua Farn, Hsuan Su, Shachi H Kumar, ..., Shang-Tse Chen, Hung-yi Lee*
- **How to Merge Your Multimodal Models Over Time?**, `arXiv, 2412.06712`, [arxiv](http://arxiv.org/abs/2412.06712v1), [pdf](http://arxiv.org/pdf/2412.06712v1.pdf), cication: [**-1**](None) 

	 *Sebastian Dziadzio, Vishaal Udandarao, Karsten Roth, ..., Samuel Albanie, Matthias Bethge* · ([𝕏](https://x.com/vishaal_urao/status/1867238865918189934))
- **Exploring Model Kinship for Merging Large Language Models**, `arXiv, 2410.12613`, [arxiv](http://arxiv.org/abs/2410.12613v1), [pdf](http://arxiv.org/pdf/2410.12613v1.pdf), cication: [**-1**](None) 

	 *Yedi Hu, Yunzhi Yao, Ningyu Zhang, ..., Shumin Deng, Huajun Chen* · ([ModelKinship](https://github.com/zjunlp/ModelKinship) - zjunlp) ![Star](https://img.shields.io/github/stars/zjunlp/ModelKinship.svg?style=social&label=Star)

## Online Learning


## Toolkits

- [**DeepGEMM**](https://github.com/deepseek-ai/DeepGEMM) - deepseek-ai ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepGEMM.svg?style=social&label=Star) 
- [**DualPipe**](https://github.com/deepseek-ai/DualPipe) - deepseek-ai ![Star](https://img.shields.io/github/stars/deepseek-ai/DualPipe.svg?style=social&label=Star) 
- [**oumi**](https://github.com/oumi-ai/oumi) - oumi-ai ![Star](https://img.shields.io/github/stars/oumi-ai/oumi.svg?style=social&label=Star) 
- [**dolomite-engine**](https://github.com/IBM/dolomite-engine) - IBM ![Star](https://img.shields.io/github/stars/IBM/dolomite-engine.svg?style=social&label=Star) 
- [**lingua**](https://github.com/facebookresearch/lingua) - facebookresearch ![Star](https://img.shields.io/github/stars/facebookresearch/lingua.svg?style=social&label=Star) 
- [Supercharging Training using float8 and FSDP2](https://pytorch.org/blog/training-using-float8-fsdp2/) 
- [**unsloth**](https://github.com/unslothai/unsloth) - unslothai ![Star](https://img.shields.io/github/stars/unslothai/unsloth.svg?style=social&label=Star) 
- [**cohere-finetune**](https://github.com/cohere-ai/cohere-finetune) - cohere-ai ![Star](https://img.shields.io/github/stars/cohere-ai/cohere-finetune.svg?style=social&label=Star) 
- 🌟 [**open-instruct**](https://github.com/allenai/open-instruct) - allenai ![Star](https://img.shields.io/github/stars/allenai/open-instruct.svg?style=social&label=Star) 

	 · ([arxiv](https://arxiv.org/abs/2406.09279))
- [**academic-pretraining**](https://github.com/apoorvkh/academic-pretraining) - apoorvkh ![Star](https://img.shields.io/github/stars/apoorvkh/academic-pretraining.svg?style=social&label=Star) 

	 *Trade-offs when Pre-Training with Academic Resources* · ([arxiv](https://arxiv.org/abs/2410.23261))
- [experimental async-TP](https://x.com/StasBekman/status/1850696223092850848)  𝕏 

	 · ([t](https://t.co/1eA0rHU25a))
- :clapper: [torchtune: Easy and Accessible Finetuning in Native PyTorch - Evan Smothers, Meta](https://www.youtube.com/watch?v=43X9E25-Qg0) 
- [Fixing Gradient Accumulation](https://huggingface.co/blog/gradient_accumulation)  🤗 
- [Fixed a bug which caused all training losses to diverge for large gradient accumulation sizes.](https://x.com/danielhanchen/status/1846235913443262891)  𝕏 
- **AutoTrain: No-code training for state-of-the-art models**, `arXiv, 2410.15735`, [arxiv](http://arxiv.org/abs/2410.15735v1), [pdf](http://arxiv.org/pdf/2410.15735v1.pdf), cication: [**-1**](None) 

	 *Abhishek Thakur*

	 · ([autotrain-advanced](https://github.com/huggingface/autotrain-advanced) - huggingface) ![Star](https://img.shields.io/github/stars/huggingface/autotrain-advanced.svg?style=social&label=Star)

## Misc

- [cover how scaling laws have evolved since their inception](https://x.com/FeinbergVlad/status/1915847967313154400)  𝕏 
- [**9a567910c1a8663f7aa04520075e0ba8**](https://gist.github.com/abacaj/9a567910c1a8663f7aa04520075e0ba8) - abacaj ![Star](https://img.shields.io/github/stars/abacaj/9a567910c1a8663f7aa04520075e0ba8.svg?style=social&label=Star) 

	 · ([𝕏](https://x.com/abacaj/status/1887206493700645300))
- [What's the deal with mid-training?](https://vintagedata.org/blog/posts/what-is-mid-training) 

	 · ([𝕏](https://x.com/Dorialexander/status/1875955536912691694))
- [Cool things from DeepSeek v3's paper](https://x.com/danielhanchen/status/1872719599029850391)  𝕏 
- [Fixing bugs in Gemma, Llama, & Phi 3: Daniel Han](https://www.youtube.com/watch?v=TKmfBnW0mQA)  :clapper: 
- [OLMo 2 and building effective teams for training language models](https://www.interconnects.ai/p/olmo-2-and-building-language-model-training) 
- 🌟 [**modded-nanogpt**](https://github.com/KellerJordan/modded-nanogpt) - KellerJordan ![Star](https://img.shields.io/github/stars/KellerJordan/modded-nanogpt.svg?style=social&label=Star) 
- **Pretraining on the Test Set Is All You Need**, `arXiv, 2309.08632`, [arxiv](http://arxiv.org/abs/2309.08632v1), [pdf](http://arxiv.org/pdf/2309.08632v1.pdf), cication: [**14**](https://scholar.google.com/scholar?cites=12205479803973588820&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Rylan Schaeffer*
- [SGLang Developer Sync - 20241102](https://www.youtube.com/watch?v=k8Jo6-XcStM)  :clapper: 
- [Argilla 2.4: Easily Build Fine-Tuning and Evaluation Datasets on the Hub — No Code Required](https://huggingface.co/blog/argilla-ui-hub)  🤗 