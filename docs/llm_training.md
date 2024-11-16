# LLM Training

- [LLM Training](#llm-training) 
  - [Survey](#survey)
  - [LLM Training](#llm-training-1)
  - [Pretraining](#pretraining)
  - [Finetuning](#finetuning)
  - [Optimization](#optimization)
  - [Architecture](#architecture)
  - [Mixture Of Experts](#mixture-of-experts)
  - [Merge](#merge)
  - [Online Learning](#online-learning)
  - [Toolkits](#toolkits)
  - [Misc](#misc)


## Survey


## LLM Training

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

## Finetuning

- **DELIFT: Data Efficient Language model Instruction Fine Tuning**, `arXiv, 2411.04425`, [arxiv](http://arxiv.org/abs/2411.04425v2), [pdf](http://arxiv.org/pdf/2411.04425v2.pdf), cication: [**-1**](None) 

	 *Ishika Agarwal, Krishnateja Killamsetty, Lucian Popa, ..., Marina Danilevksy* · ([𝕏](https://x.com/wonderingishika/status/1854770402590851119))
- **SemiEvol: Semi-supervised Fine-tuning for LLM Adaptation**, `arXiv, 2410.14745`, [arxiv](http://arxiv.org/abs/2410.14745v1), [pdf](http://arxiv.org/pdf/2410.14745v1.pdf), cication: [**-1**](None) 

	 *Junyu Luo, Xiao Luo, Xiusi Chen, ..., Wei Ju, Ming Zhang*

## Optimization

- [The Practitioner’s Guide to the Maximal Update Parameterization](https://cerebras.ai/blog/the-practitioners-guide-to-the-maximal-update-parameterization/) 

	 · ([nanoGPT-mup](https://github.com/EleutherAI/nanoGPT-mup) - EleutherAI) ![Star](https://img.shields.io/github/stars/EleutherAI/nanoGPT-mup.svg?style=social&label=Star)
- **Polynomial Composition Activations: Unleashing the Dynamics of Large 
  Language Models**, `arXiv, 2411.03884`, [arxiv](http://arxiv.org/abs/2411.03884v1), [pdf](http://arxiv.org/pdf/2411.03884v1.pdf), cication: [**-1**](None) 

	 *Zhijian Zhuo, Ya Wang, Yutao Zeng, ..., Xun Zhou, Jinwen Ma* · ([PolyCom](https://github.com/BryceZhuo/PolyCom) - BryceZhuo) ![Star](https://img.shields.io/github/stars/BryceZhuo/PolyCom.svg?style=social&label=Star)
- **The Road Less Scheduled**, `arXiv, 2405.15682`, [arxiv](http://arxiv.org/abs/2405.15682v4), [pdf](http://arxiv.org/pdf/2405.15682v4.pdf), cication: [**-1**](None) 

	 *Aaron Defazio, Xingyu Alice Yang, Harsh Mehta, ..., Ahmed Khaled, Ashok Cutkosky* · ([schedule_free](https://github.com/facebookresearch/schedule_free) - facebookresearch) ![Star](https://img.shields.io/github/stars/facebookresearch/schedule_free.svg?style=social&label=Star)
- :clapper: [Hacks to Make LLM Training Faster - Daniel Han, Unsloth AI](https://www.youtube.com/watch?v=PdtKkc5jB4g) 

## Architecture


## Mixture Of Experts

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

- **Exploring Model Kinship for Merging Large Language Models**, `arXiv, 2410.12613`, [arxiv](http://arxiv.org/abs/2410.12613v1), [pdf](http://arxiv.org/pdf/2410.12613v1.pdf), cication: [**-1**](None) 

	 *Yedi Hu, Yunzhi Yao, Ningyu Zhang, ..., Shumin Deng, Huajun Chen* · ([ModelKinship](https://github.com/zjunlp/ModelKinship) - zjunlp) ![Star](https://img.shields.io/github/stars/zjunlp/ModelKinship.svg?style=social&label=Star)

## Online Learning


## Toolkits

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

- **Pretraining on the Test Set Is All You Need**, `arXiv, 2309.08632`, [arxiv](http://arxiv.org/abs/2309.08632v1), [pdf](http://arxiv.org/pdf/2309.08632v1.pdf), cication: [**14**](https://scholar.google.com/scholar?cites=12205479803973588820&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Rylan Schaeffer*
- [SGLang Developer Sync - 20241102](https://www.youtube.com/watch?v=k8Jo6-XcStM)  :clapper: 
- [Argilla 2.4: Easily Build Fine-Tuning and Evaluation Datasets on the Hub — No Code Required](https://huggingface.co/blog/argilla-ui-hub)  🤗 