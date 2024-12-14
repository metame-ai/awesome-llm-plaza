# LLM Reasoning

- [LLM Reasoning](#llm-reasoning) 
  - [Survey](#survey)
  - [Reasoning](#reasoning)
  - [Math Reasoning](#math-reasoning)
  - [O1 Reasoning](#o1-reasoning)
  - [Disentanglement](#disentanglement)
  - [Self Correction](#self-correction)
  - [Knowledge](#knowledge)
  - [Context Learning](#context-learning)
  - [Chain Of Thought](#chain-of-thought)
  - [Prompt](#prompt)
  - [Projects](#projects)
  - [Misc](#misc)
  - [Planning](#planning)


## Survey


## Reasoning

- **RARE: Retrieval-Augmented Reasoning Enhancement for Large Language 
  Models**, `arXiv, 2412.02830`, [arxiv](http://arxiv.org/abs/2412.02830v3), [pdf](http://arxiv.org/pdf/2412.02830v3.pdf), cication: [**-1**](None) 

	 *Hieu Tran, Zonghai Yao, Junda Wang, ..., Zhichao Yang, Hong Yu*
- **Mind the Gap: Examining the Self-Improvement Capabilities of Large 
  Language Models**, `arXiv, 2412.02674`, [arxiv](http://arxiv.org/abs/2412.02674v1), [pdf](http://arxiv.org/pdf/2412.02674v1.pdf), cication: [**-1**](None) 

	 *Yuda Song, Hanlin Zhang, Carson Eisenach, ..., Dean Foster, Udaya Ghai* · ([𝕏](https://x.com/yus167/status/1865091023778779479))
- **Frontier Models are Capable of In-context Scheming**, `arXiv, 2412.04984`, [arxiv](http://arxiv.org/abs/2412.04984v1), [pdf](http://arxiv.org/pdf/2412.04984v1.pdf), cication: [**-1**](None) 

	 *Alexander Meinke, Bronson Schoen, Jérémy Scheurer, ..., Rusheb Shah, Marius Hobbhahn*
- 🌟 **Training Large Language Models to Reason in a Continuous Latent Space**, `arXiv, 2412.06769`, [arxiv](http://arxiv.org/abs/2412.06769v1), [pdf](http://arxiv.org/pdf/2412.06769v1.pdf), cication: [**-1**](None) 

	 *Shibo Hao, Sainbayar Sukhbaatar, DiJia Su, ..., Jason Weston, Yuandong Tian* · ([𝕏](https://x.com/Ber18791531/status/1866561188664087017))
- 🌟 [Paper page - Critical Tokens Matter: Token-Level Contrastive Estimation Enhence LLM's  Reasoning Capability](https://huggingface.co/papers/2411.19943) 
- **MALT: Improving Reasoning with Multi-Agent LLM Training**, `arXiv, 2412.01928`, [arxiv](http://arxiv.org/abs/2412.01928v1), [pdf](http://arxiv.org/pdf/2412.01928v1.pdf), cication: [**-1**](None) 

	 *Sumeet Ramesh Motwani, Chandler Smith, Rocktim Jyoti Das, ..., Ronald Clark, Christian Schroeder de Witt*
- **Reverse Thinking Makes LLMs Stronger Reasoners**, `arXiv, 2411.19865`, [arxiv](http://arxiv.org/abs/2411.19865v1), [pdf](http://arxiv.org/pdf/2411.19865v1.pdf), cication: [**-1**](None) 

	 *Justin Chih-Yao Chen, Zifeng Wang, Hamid Palangi, ..., Chen-Yu Lee, Tomas Pfister*
- 🌟 **Beyond Examples: High-level Automated Reasoning Paradigm in In-Context 
  Learning via MCTS**, `arXiv, 2411.18478`, [arxiv](http://arxiv.org/abs/2411.18478v1), [pdf](http://arxiv.org/pdf/2411.18478v1.pdf), cication: [**-1**](None) 

	 *Jinyang Wu, Mingkuan Feng, Shuai Zhang, ..., Zengqi Wen, Jianhua Tao* · ([arxiv](https://arxiv.org/pdf/2411.18478)) · ([jinyangwu.github](https://jinyangwu.github.io/hiar-icl/))
- [DeepSeek-R1-Lite-Preview is now live: unleashing supercharged reasoning power](https://x.com/deepseek_ai/status/1859200145037869485)  𝕏 
- **BALROG: Benchmarking Agentic LLM and VLM Reasoning On Games**, `arXiv, 2411.13543`, [arxiv](http://arxiv.org/abs/2411.13543v1), [pdf](http://arxiv.org/pdf/2411.13543v1.pdf), cication: [**-1**](None) 

	 *Davide Paglieri, Bartłomiej Cupiał, Samuel Coward, ..., Jack Parker-Holder, Tim Rocktäschel*
- 🌟 **Language Models are Hidden Reasoners: Unlocking Latent Reasoning 
  Capabilities via Self-Rewarding**, `arXiv, 2411.04282`, [arxiv](http://arxiv.org/abs/2411.04282v1), [pdf](http://arxiv.org/pdf/2411.04282v1.pdf), cication: [**-1**](None) 

	 *Haolin Chen, Yihao Feng, Zuxin Liu, ..., Caiming Xiong, Huan Wang* · ([LaTRO](https://github.com/SalesforceAIResearch/LaTRO) - SalesforceAIResearch) ![Star](https://img.shields.io/github/stars/SalesforceAIResearch/LaTRO.svg?style=social&label=Star)
- **Large Language Models Can Self-Improve in Long-context Reasoning**, `arXiv, 2411.08147`, [arxiv](http://arxiv.org/abs/2411.08147v1), [pdf](http://arxiv.org/pdf/2411.08147v1.pdf), cication: [**-1**](None) 

	 *Siheng Li, Cheng Yang, Zesen Cheng, ..., Yujiu Yang, Wai Lam*
- :star2: **Combining Induction and Transduction for Abstract Reasoning**, `arXiv, 2411.02272`, [arxiv](http://arxiv.org/abs/2411.02272v1), [pdf](http://arxiv.org/pdf/2411.02272v1.pdf), cication: [**-1**](None) 

	 *Wen-Ding Li, Keya Hu, Carter Larsen, ..., Yewen Pu, Kevin Ellis* · ([𝕏](https://x.com/ellisk_kellis/status/1852690768042897661))
- :star2: [The Surprising Effectiveness ofTest-Time Training for Abstract Reasoning](https://ekinakyurek.github.io/papers/ttt.pdf) 

	 · ([𝕏](https://x.com/akyurekekin/status/1855680785715478546)) · ([marc](https://github.com/ekinakyurek/marc) - ekinakyurek) ![Star](https://img.shields.io/github/stars/ekinakyurek/marc.svg?style=social&label=Star)
- **Can Language Models Learn to Skip Steps?**, `arXiv, 2411.01855`, [arxiv](http://arxiv.org/abs/2411.01855v1), [pdf](http://arxiv.org/pdf/2411.01855v1.pdf), cication: [**-1**](None) 

	 *Tengxiao Liu, Qipeng Guo, Xiangkun Hu, ..., Xipeng Qiu, Zheng Zhang*
- **SocialGPT: Prompting LLMs for Social Relation Reasoning via Greedy 
  Segment Optimization**, `arXiv, 2410.21411`, [arxiv](http://arxiv.org/abs/2410.21411v1), [pdf](http://arxiv.org/pdf/2410.21411v1.pdf), cication: [**-1**](None)

	 *Wanhua Li, Zibin Meng, Jiawei Zhou, ..., Chuang Gan, Hanspeter Pfister* · ([SocialGPT](https://github.com/Mengzibin/SocialGPT) - Mengzibin) ![Star](https://img.shields.io/github/stars/Mengzibin/SocialGPT.svg?style=social&label=Star)
- **A Pointer Network-based Approach for Joint Extraction and Detection of 
  Multi-Label Multi-Class Intents**, `arXiv, 2410.22476`, [arxiv](http://arxiv.org/abs/2410.22476v1), [pdf](http://arxiv.org/pdf/2410.22476v1.pdf), cication: [**-1**](None)

	 *Ankan Mullick, Sombit Bose, Abhilash Nandy, ..., Gajula Sai Chaitanya, Pawan Goyal*
- [Combining Induction and Transduction for Abstract Reasoning](https://openreview.net/forum?id=UmdotAAVDe) 
- **Improve Vision Language Model Chain-of-thought Reasoning**, `arXiv, 2410.16198`, [arxiv](http://arxiv.org/abs/2410.16198v1), [pdf](http://arxiv.org/pdf/2410.16198v1.pdf), cication: [**-1**](None) 

	 *Ruohong Zhang, Bowen Zhang, Yanghao Li, ..., Ruoming Pang, Yiming Yang*

	 · ([LLaVA-Reasoner-DPO](https://github.com/RifleZhang/LLaVA-Reasoner-DPO) - RifleZhang) ![Star](https://img.shields.io/github/stars/RifleZhang/LLaVA-Reasoner-DPO.svg?style=social&label=Star)

## Math Reasoning

- **U-MATH: A University-Level Benchmark for Evaluating Mathematical Skills 
  in LLMs**, `arXiv, 2412.03205`, [arxiv](http://arxiv.org/abs/2412.03205v2), [pdf](http://arxiv.org/pdf/2412.03205v2.pdf), cication: [**-1**](None) 

	 *Konstantin Chernyshev, Vitaliy Polshkov, Ekaterina Artemova, ..., Alexei Miasnikov, Sergei Tilga* · ([u-math](https://github.com/Toloka/u-math/) - Toloka) ![Star](https://img.shields.io/github/stars/Toloka/u-math.svg?style=social&label=Star)
- **ProcessBench: Identifying Process Errors in Mathematical Reasoning**, `arXiv, 2412.06559`, [arxiv](http://arxiv.org/abs/2412.06559v2), [pdf](http://arxiv.org/pdf/2412.06559v2.pdf), cication: [**-1**](None) 

	 *Chujie Zheng, Zhenru Zhang, Beichen Zhang, ..., Jingren Zhou, Junyang Lin*
- **FrontierMath: A Benchmark for Evaluating Advanced Mathematical Reasoning 
  in AI**, `arXiv, 2411.04872`, [arxiv](http://arxiv.org/abs/2411.04872v1), [pdf](http://arxiv.org/pdf/2411.04872v1.pdf), cication: [**-1**](None) 

	 *Elliot Glazer, Ege Erdil, Tamay Besiroglu, ..., Tetiana Grechuk, Shreepranav Varma Enugandla* · ([epochai](https://epochai.org/frontiermath)) · ([𝕏](https://x.com/EpochAIResearch/status/1854993676524831046))
- **Flow-DPO: Improving LLM Mathematical Reasoning through Online 
  Multi-Agent Learning**, `arXiv, 2410.22304`, [arxiv](http://arxiv.org/abs/2410.22304v1), [pdf](http://arxiv.org/pdf/2410.22304v1.pdf), cication: [**-1**](None)

	 *Yihe Deng, Paul Mineiro*
- **Arithmetic Without Algorithms: Language Models Solve Math With a Bag of 
  Heuristics**, `arXiv, 2410.21272`, [arxiv](http://arxiv.org/abs/2410.21272v1), [pdf](http://arxiv.org/pdf/2410.21272v1.pdf), cication: [**-1**](None)

	 *Yaniv Nikankin, Anja Reusch, Aaron Mueller, ..., Yonatan Belinkov* · ([x](https://x.com/omarsar0/status/1851233281116946923))
- **Omni-MATH: A Universal Olympiad Level Mathematic Benchmark For Large 
  Language Models**, `arXiv, 2410.07985`, [arxiv](http://arxiv.org/abs/2410.07985v2), [pdf](http://arxiv.org/pdf/2410.07985v2.pdf), cication: [**-1**](None)

	 *Bofei Gao, Feifan Song, Zhe Yang, ..., Tianyu Liu, Baobao Chang* · ([Omni-MATH](https://github.com/KbsdJames/Omni-MATH) - KbsdJames) ![Star](https://img.shields.io/github/stars/KbsdJames/Omni-MATH.svg?style=social&label=Star) · ([omni-math.github](https://omni-math.github.io/)) · ([huggingface](https://huggingface.co/datasets/KbsdJames/Omni-MATH)) · ([huggingface](https://huggingface.co/KbsdJames/Omni-Judge))

## O1 Reasoning

- [Beyond Decoding: Meta-Generation Algorithms for Large Language Models](https://cmu-l3.github.io/neurips2024-inference-tutorial/) 
- [Beyond Decoding: Meta-Generation Algorithmsfor Large Language Models](https://cmu-l3.github.io/neurips2024-inference-tutorial/static/slides/neurips2024metageneration-tutorial-all.pdf) 
- [uncensored version of Qwen/QwQ-32B-Preview created with abliteration](https://huggingface.co/huihui-ai/QwQ-32B-Preview-abliterated)  🤗 

	 · ([remove-refusals-with-transformers](https://github.com/Sumandora/remove-refusals-with-transformers) - Sumandora) ![Star](https://img.shields.io/github/stars/Sumandora/remove-refusals-with-transformers.svg?style=social&label=Star)
- [OpenAI's o1 using "search" was a PSYOP](https://www.interconnects.ai/p/openais-o1-using-search-was-a-psyop) 
- [Inference Time Compute](https://www.youtube.com/watch?v=_Bw5o55SRL8)  :clapper: 
- **Free Process Rewards without Process Labels**, `arXiv, 2412.01981`, [arxiv](http://arxiv.org/abs/2412.01981v1), [pdf](http://arxiv.org/pdf/2412.01981v1.pdf), cication: [**-1**](None) 

	 *Lifan Yuan, Wendi Li, Huayu Chen, ..., Zhiyuan Liu, Hao Peng*
- **Natural Language Reinforcement Learning**, `arXiv, 2411.14251`, [arxiv](http://arxiv.org/abs/2411.14251v1), [pdf](http://arxiv.org/pdf/2411.14251v1.pdf), cication: [**-1**](None) 

	 *Xidong Feng, Ziyu Wan, Haotian Fu, ..., Ying Wen, Jun Wang* · ([arxiv](https://arxiv.org/abs/2411.14251)) · ([Natural-language-RL](https://github.com/waterhorse1/Natural-language-RL) - waterhorse1) ![Star](https://img.shields.io/github/stars/waterhorse1/Natural-language-RL.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650946144&idx=4&sn=4460db77bcb06cfbd62b2cd023211654&chksm=858b9489f4ce7b11539b33373d489ca004cbcddbe6fa787ba11461b6adf907c132336878169e&scene=0&xtrack=1))
- [Can we make any smaller opensource LLM models smarter than human?](https://medium.com/@harishhacker3010/can-we-make-any-smaller-opensource-ai-models-smarter-than-human-1ea507e644a0) 
- [OpenAI o1开启「后训练」时代强化学习新范式](https://mp.weixin.qq.com/s/FXGdJA8OyZvLl89rXJiyAQ) 

	 · ([bilibili](https://www.bilibili.com/video/BV15Rx5eXEnW/?spm_id_from=333.1007.top_right_bar_window_history.content.click&vd_source=63e5fa02f07bfd58e74de3c6d149e31f))
- **Inference Scaling fLaws: The Limits of LLM Resampling with Imperfect 
  Verifiers**, `arXiv, 2411.17501`, [arxiv](http://arxiv.org/abs/2411.17501v2), [pdf](http://arxiv.org/pdf/2411.17501v2.pdf), cication: [**-1**](None) 

	 *Benedikt Stroebl, Sayash Kapoor, Arvind Narayanan* · ([𝕏](https://x.com/benediktstroebl/status/1861764215947903208)) · ([𝕏](https://x.com/TheAITimeline/status/1863350162849997113))
- [Exploring OpenAI O1 Model Replication](https://hijkzzz.notion.site/exploring-openai-o1-model-replication) 
- [**Open-O1**](https://github.com/Open-Source-O1/Open-O1) - Open-Source-O1 ![Star](https://img.shields.io/github/stars/Open-Source-O1/Open-O1.svg?style=social&label=Star) 

	 *A Model Matching Proprietary Power with Open-Source Innovation*
- **Patience Is The Key to Large Language Model Reasoning**, `arXiv, 2411.13082`, [arxiv](http://arxiv.org/abs/2411.13082v2), [pdf](http://arxiv.org/pdf/2411.13082v2.pdf), cication: [**-1**](None) 

	 *Yijiong Yu*

	 · ([huggingface](https://huggingface.co/datasets/yuyijiong/patient-math-cot))
- 🌟 **O1 Replication Journey -- Part 2: Surpassing O1-preview through Simple 
  Distillation, Big Progress or Bitter Lesson?**, `arXiv, 2411.16489`, [arxiv](http://arxiv.org/abs/2411.16489v1), [pdf](http://arxiv.org/pdf/2411.16489v1.pdf), cication: [**-1**](None) 

	 *Zhen Huang, Haoyang Zou, Xuefeng Li, ..., Weizhe Yuan, Pengfei Liu* · ([O1-Journey](https://github.com/GAIR-NLP/O1-Journey) - GAIR-NLP) ![Star](https://img.shields.io/github/stars/GAIR-NLP/O1-Journey.svg?style=social&label=Star)
- **Enhancing LLM Reasoning via Critique Models with Test-Time and 
  Training-Time Supervision**, `arXiv, 2411.16579`, [arxiv](http://arxiv.org/abs/2411.16579v1), [pdf](http://arxiv.org/pdf/2411.16579v1.pdf), cication: [**-1**](None) 

	 *Zhiheng Xi, Dingwen Yang, Jixuan Huang, ..., Xuanjing Huang, Yu-Gang Jiang* · ([mathcritique.github](https://mathcritique.github.io/))
- [QwQ: Reflect Deeply on the Boundaries of the Unknown](http://qwenlm.github.io/blog/qwq-32b-preview/) 

	 · ([huggingface](https://huggingface.co/Qwen/QwQ-32B-Preview))
- [Skywork o1 Open model series](https://huggingface.co/Skywork/Skywork-o1-Open-Llama-3.1-8B)  🤗 
- 🌟 [**O1-Journey**](https://github.com/GAIR-NLP/O1-Journey) - GAIR-NLP ![Star](https://img.shields.io/github/stars/GAIR-NLP/O1-Journey.svg?style=social&label=Star) 
- [Beyond Decoding: Meta-Generation Algorithms for Large Language Models](https://neurips.cc/virtual/2024/tutorial/99522) 

	 · ([simons.berkeley](https://simons.berkeley.edu/talks/sean-welleck-carnegie-mellon-university-2024-11-19))
- 🌟 **From Decoding to Meta-Generation: Inference-time Algorithms for Large 
  Language Models**, `arXiv, 2406.16838`, [arxiv](http://arxiv.org/abs/2406.16838v2), [pdf](http://arxiv.org/pdf/2406.16838v2.pdf), cication: [**-1**](None) 

	 *Sean Welleck, Amanda Bertsch, Matthew Finlayson, ..., Ilia Kulikov, Zaid Harchaoui* · ([cmu-l3.github](https://cmu-l3.github.io/neurips2024-inference-tutorial/))
- [honorable mentions to Nous Forge Reasoning API and Fireworks f1, DeepSeek appear to have made the first convincing attempt](https://buttondown.com/ainews/archive/ainews-deepseek-r1-claims-to-beat-o1-preview-and/) 
- [DeepSeek-R1-Lite-Preview is now live: unleashing supercharged reasoning power!](https://x.com/deepseek_ai/status/1859200141355536422)  𝕏 

	 · ([t](https://t.co/v1TFy7LHNy))
- 🌟 **Marco-o1: Towards Open Reasoning Models for Open-Ended Solutions**, `arXiv, 2411.14405`, [arxiv](http://arxiv.org/abs/2411.14405v1), [pdf](http://arxiv.org/pdf/2411.14405v1.pdf), cication: [**-1**](None) 

	 *Yu Zhao, Huifeng Yin, Bo Zeng, ..., Weihua Luo, Kaifu Zhang* · ([Marco-o1](https://github.com/AIDC-AI/Marco-o1) - AIDC-AI) ![Star](https://img.shields.io/github/stars/AIDC-AI/Marco-o1.svg?style=social&label=Star)
- 🌟 [**entropix**](https://github.com/xjdr-alt/entropix) - xjdr-alt ![Star](https://img.shields.io/github/stars/xjdr-alt/entropix.svg?style=social&label=Star) 
- [**Thinking-Claude**](https://github.com/richards199999/Thinking-Claude) - richards199999 ![Star](https://img.shields.io/github/stars/richards199999/Thinking-Claude.svg?style=social&label=Star) 
- [Speculations on Test-Time Scaling (o1)](https://www.youtube.com/watch?v=6PEJ96k1kiw)  :clapper: 
- [Tess-R1 is designed with test-time compute in mind, and has the capabilities to produce a Chain-of-Thought (CoT) reasoning before producing the final output.](https://huggingface.co/migtissera/Tess-R1-Limerick-Llama-3.1-70B)  🤗 
- [**LLaMA-O1**](https://github.com/SimpleBerry/LLaMA-O1) - SimpleBerry ![Star](https://img.shields.io/github/stars/SimpleBerry/LLaMA-O1.svg?style=social&label=Star) 

	 *Open Large Reasoning Model Frameworks For Training, Inference and Evaluation With PyTorch and HuggingFace* · ([qbitai](https://www.qbitai.com/2024/11/215576.html))
- **A Comparative Study on Reasoning Patterns of OpenAI's o1 Model**, `arXiv, 2410.13639`, [arxiv](http://arxiv.org/abs/2410.13639v2), [pdf](http://arxiv.org/pdf/2410.13639v2.pdf), cication: [**-1**](None) 

	 *Siwei Wu, Zhongyuan Peng, Xinrun Du, ..., Chenghua Lin, J. H. Liu*
- **Dualformer: Controllable Fast and Slow Thinking by Learning with 
  Randomized Reasoning Traces**, `arXiv, 2410.09918`, [arxiv](http://arxiv.org/abs/2410.09918v1), [pdf](http://arxiv.org/pdf/2410.09918v1.pdf), cication: [**-1**](None)

	 *DiJia Su, Sainbayar Sukhbaatar, Michael Rabbat, ..., Yuandong Tian, Qinqing Zheng*
- [**O1-Journey**](https://github.com/GAIR-NLP/O1-Journey) - GAIR-NLP ![Star](https://img.shields.io/github/stars/GAIR-NLP/O1-Journey.svg?style=social&label=Star) 

	 *A Strategic Progress Report*
- **A Comparative Study on Reasoning Patterns of OpenAI's o1 Model**, `arXiv, 2410.13639`, [arxiv](http://arxiv.org/abs/2410.13639v2), [pdf](http://arxiv.org/pdf/2410.13639v2.pdf), cication: [**-1**](None) 

	 *Siwei Wu, Zhongyuan Peng, Xinrun Du, ..., Chenghua Lin, J. H. Liu*

## Disentanglement

- **Disentangling Memory and Reasoning Ability in Large Language Models**, `arXiv, 2411.13504`, [arxiv](http://arxiv.org/abs/2411.13504v2), [pdf](http://arxiv.org/pdf/2411.13504v2.pdf), cication: [**-1**](None) 

	 *Mingyu Jin, Weidi Luo, Sitao Cheng, ..., William Yang Wang, Yongfeng Zhang* · ([Disentangling-Memory-and-Reasoning](https://github.com/MingyuJ666/Disentangling-Memory-and-Reasoning?tab=readme-ov-file) - MingyuJ666) ![Star](https://img.shields.io/github/stars/MingyuJ666/Disentangling-Memory-and-Reasoning.svg?style=social&label=Star)

## Self Correction


## Knowledge


## Context Learning

- **The broader spectrum of in-context learning**, `arXiv, 2412.03782`, [arxiv](http://arxiv.org/abs/2412.03782v2), [pdf](http://arxiv.org/pdf/2412.03782v2.pdf), cication: [**-1**](None) 

	 *Andrew Kyle Lampinen, Stephanie C. Y. Chan, Aaditya K. Singh, ..., Murray Shanahan* · ([𝕏](https://x.com/AndrewLampinen/status/1866546723210011077))

## Chain Of Thought

- [**Internalize_CoT_Step_by_Step**](https://github.com/da03/Internalize_CoT_Step_by_Step) - da03 ![Star](https://img.shields.io/github/stars/da03/Internalize_CoT_Step_by_Step.svg?style=social&label=Star) 

	 · ([huggingface](https://huggingface.co/spaces/yuntian-deng/gpt2-multiplication))
- **LLMs Do Not Think Step-by-step In Implicit Reasoning**, `arXiv, 2411.15862`, [arxiv](http://arxiv.org/abs/2411.15862v1), [pdf](http://arxiv.org/pdf/2411.15862v1.pdf), cication: [**-1**](None) 

	 *Yijiong Yu*

	 · ([𝕏](https://x.com/TheAITimeline/status/1863350188019949808))
- **A Theoretical Understanding of Chain-of-Thought: Coherent Reasoning and 
  Error-Aware Demonstration**, `arXiv, 2410.16540`, [arxiv](http://arxiv.org/abs/2410.16540v1), [pdf](http://arxiv.org/pdf/2410.16540v1.pdf), cication: [**-1**](None) 

	 *Yingqian Cui, Pengfei He, Xianfeng Tang, ..., Jiliang Tang, Yue Xing* · ([𝕏](https://x.com/_philschmid/status/1855926845855699311))
- **Mind Your Step (by Step): Chain-of-Thought can Reduce Performance on 
  Tasks where Thinking Makes Humans Worse**, `arXiv, 2410.21333`, [arxiv](http://arxiv.org/abs/2410.21333v1), [pdf](http://arxiv.org/pdf/2410.21333v1.pdf), cication: [**-1**](None)

	 *Ryan Liu, Jiayi Geng, Addison J. Wu, ..., Tania Lombrozo, Thomas L. Griffiths*

## Prompt

- [Prompt Design at Character.AI](https://research.character.ai/prompt-design-at-character-ai/) 
- **Does Prompt Formatting Have Any Impact on LLM Performance?**, `arXiv, 2411.10541`, [arxiv](http://arxiv.org/abs/2411.10541v1), [pdf](http://arxiv.org/pdf/2411.10541v1.pdf), cication: [**-1**](None) 

	 *Jia He, Mukund Rungta, David Koleczek, ..., Franklin X Wang, Sadid Hasan*
- [automatic prompt optimization algorithms](https://x.com/cwolferesearch/status/1853465302031556725)  𝕏 
- [Automatic Prompt Optimization](https://cameronrwolfe.substack.com/p/automatic-prompt-optimization) 
- [MacOS 15.1 Apple Intelligence Prompt Templates](https://x.com/reach_vb/status/1851264423450587302)  𝕏 
- [use RL to automatically improve our prompts](https://x.com/cwolferesearch/status/1850919005407662435)  𝕏 
- **ProSA: Assessing and Understanding the Prompt Sensitivity of LLMs**, `arXiv, 2410.12405`, [arxiv](http://arxiv.org/abs/2410.12405v1), [pdf](http://arxiv.org/pdf/2410.12405v1.pdf), cication: [**-1**](None) 

	 *Jingming Zhuo, Songyang Zhang, Xinyu Fang, ..., Dahua Lin, Kai Chen* · ([ProSA](https://github.com/open-compass/ProSA) - open-compass) ![Star](https://img.shields.io/github/stars/open-compass/ProSA.svg?style=social&label=Star)

## Projects

- [**prompt-poet**](https://github.com/character-ai/prompt-poet) - character-ai ![Star](https://img.shields.io/github/stars/character-ai/prompt-poet.svg?style=social&label=Star) 
- [**V0-system-prompt**](https://github.com/2-fly-4-ai/V0-system-prompt) - 2-fly-4-ai ![Star](https://img.shields.io/github/stars/2-fly-4-ai/V0-system-prompt.svg?style=social&label=Star) 

	 · ([reddit](https://www.reddit.com/r/LocalLLaMA/comments/1gwwyia/leaked_system_prompts_from_v0_vercels_ai/))
- [steiner-preview  updated			3 days ago Reasoning models trained on synthetic data using reinforcement learning.](https://huggingface.co/collections/peakji/steiner-preview-6712c6987110ce932a44e9a6)  🤗 

## Misc

- [【北大对齐团队独家解读：OpenAI o1开启「后训练」时代强化学习新范式】](https://www.bilibili.com/list/watchlater?oid=113201647719044&bvid=BV15Rx5eXEnW)  :clapper: 
- [The Problem with Reasoners](https://aidanmclaughlin.notion.site/reasoners-problem) 


## Planning
- **Revealing the Barriers of Language Agents in Planning**, `arXiv, 2410.12409`, [arxiv](http://arxiv.org/abs/2410.12409v1), [pdf](http://arxiv.org/pdf/2410.12409v1.pdf), cication: [**-1**](None) 

	 *Jian Xie, Kexun Zhang, Jiangjie Chen, ..., Lei Li, Yanghua Xiao*