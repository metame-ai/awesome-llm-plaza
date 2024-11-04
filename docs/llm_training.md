# LLM Training

- [LLM Training](#llm-training) 
  - [Survey](#survey)
  - [LLM Training](#llm-training)
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

- **SemiEvol: Semi-supervised Fine-tuning for LLM Adaptation**, `arXiv, 2410.14745`, [arxiv](http://arxiv.org/abs/2410.14745v1), [pdf](http://arxiv.org/pdf/2410.14745v1.pdf), cication: [**-1**](None) 

	 *Junyu Luo, Xiao Luo, Xiusi Chen, ..., Wei Ju, Ming Zhang*

## Optimization

- :clapper: [Hacks to Make LLM Training Faster - Daniel Han, Unsloth AI](https://www.youtube.com/watch?v=PdtKkc5jB4g) 

## Architecture


## Mixture Of Experts

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

- :star2: [**open-instruct**](https://github.com/allenai/open-instruct) - allenai ![Star](https://img.shields.io/github/stars/allenai/open-instruct.svg?style=social&label=Star) 

	 · ([arxiv](https://arxiv.org/abs/2406.09279))
- [**academic-pretraining**](https://github.com/apoorvkh/academic-pretraining) - apoorvkh ![Star](https://img.shields.io/github/stars/apoorvkh/academic-pretraining.svg?style=social&label=Star) 

	 *Trade-offs when Pre-Training with Academic Resources* · ([arxiv](https://arxiv.org/abs/2410.23261))
- [experimental async-TP](https://x.com/StasBekman/status/1850696223092850848) 

	 · ([t](https://t.co/1eA0rHU25a))
- :clapper: [torchtune: Easy and Accessible Finetuning in Native PyTorch - Evan Smothers, Meta](https://www.youtube.com/watch?v=43X9E25-Qg0) 
- [Fixing Gradient Accumulation](https://huggingface.co/blog/gradient_accumulation)  🤗
- [Fixed a bug which caused all training losses to diverge for large gradient accumulation sizes.](https://x.com/danielhanchen/status/1846235913443262891) 
- **AutoTrain: No-code training for state-of-the-art models**, `arXiv, 2410.15735`, [arxiv](http://arxiv.org/abs/2410.15735v1), [pdf](http://arxiv.org/pdf/2410.15735v1.pdf), cication: [**-1**](None) 

	 *Abhishek Thakur*

	 · ([autotrain-advanced](https://github.com/huggingface/autotrain-advanced) - huggingface) ![Star](https://img.shields.io/github/stars/huggingface/autotrain-advanced.svg?style=social&label=Star)

## Misc