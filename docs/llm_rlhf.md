# LLM RLHF

- [LLM RLHF](#llm-rlhf) 
  - [Survey](#survey)
  - [RLHF](#rlhf)
  - [Reward Models](#reward-models)
  - [Projects](#projects)
  - [Misc](#misc)


## Survey


## RLHF

- **Inverse Reinforcement Learning Meets Large Language Model Post-Training: 
  Basics, Advances, and Opportunities**, `arXiv, 2507.13158`, [arxiv](http://arxiv.org/abs/2507.13158v1), [pdf](http://arxiv.org/pdf/2507.13158v1.pdf), cication: [**-1**](None) 

	 *Hao Sun, Mihaela van der Schaar*
- **WorldPM: Scaling Human Preference Modeling**, `arXiv, 2505.10527`, [arxiv](http://arxiv.org/abs/2505.10527v2), [pdf](http://arxiv.org/pdf/2505.10527v2.pdf), cication: [**-1**](None) 

	 *Binghai Wang, Runji Lin, Keming Lu, ..., Jingren Zhou, Junyang Lin*
- **Back to Basics: Revisiting REINFORCE Style Optimization for Learning 
  from Human Feedback in LLMs**, `arXiv, 2402.14740`, [arxiv](http://arxiv.org/abs/2402.14740v2), [pdf](http://arxiv.org/pdf/2402.14740v2.pdf), cication: [**-1**](None) 

	 *Arash Ahmadian, Chris Cremer, Matthias Gallé, ..., Ahmet Üstün, Sara Hooker*
- [ByteDance's Platform for Reinforcement Learning from Human Feedback | Ray Summit 2024](https://www.youtube.com/watch?v=MrhMcXkXvJU&list=PLzTswPQNepXntmT8jr9WaNfqQ60QwW7-U&index=37)  :clapper: 
- 🌟 **Self-Play Preference Optimization for Language Model Alignment**, `arXiv, 2405.00675`, [arxiv](http://arxiv.org/abs/2405.00675v5), [pdf](http://arxiv.org/pdf/2405.00675v5.pdf), cication: [**76**](https://scholar.google.com/scholar?cites=14552805419899502113&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Yue Wu, Zhiqing Sun, Huizhuo Yuan, ..., Yiming Yang, Quanquan Gu* · ([𝕏](https://x.com/FrankYueWu1/status/1893850023919505534))
- 🌟 [Train your own R1 reasoning model with UnslothFeb 6, 2025 • By Daniel & Michael](https://unsloth.ai/blog/r1-reasoning) 
- **SFT Memorizes, RL Generalizes: A Comparative Study of Foundation Model 
  Post-training**, `arXiv, 2501.17161`, [arxiv](http://arxiv.org/abs/2501.17161v1), [pdf](http://arxiv.org/pdf/2501.17161v1.pdf), cication: [**-1**](None) 

	 *Tianzhe Chu, Yuexiang Zhai, Jihan Yang, ..., Sergey Levine, Yi Ma* · ([tianzhechu](https://tianzhechu.com/SFTvsRL))
- **Diverse Preference Optimization**, `arXiv, 2501.18101`, [arxiv](http://arxiv.org/abs/2501.18101v2), [pdf](http://arxiv.org/pdf/2501.18101v2.pdf), cication: [**-1**](None) 

	 *Jack Lanchantin, Angelica Chen, Shehzaad Dhuliawala, ..., Sainbayar Sukhbaatar, Ilia Kulikov* · ([𝕏](https://x.com/jaseweston/status/1885399530419450257))
- **Enabling Scalable Oversight via Self-Evolving Critic**, `arXiv, 2501.05727`, [arxiv](http://arxiv.org/abs/2501.05727v1), [pdf](http://arxiv.org/pdf/2501.05727v1.pdf), cication: [**-1**](None) 

	 *Zhengyang Tang, Ziniu Li, Zhenyang Xiao, ..., Bowen Yu, Junyang Lin*
- [Preference Optimization for Large Language Models](https://llm-class.github.io/speakers.html) 
- 🌟 **REINFORCE++: A Simple and Efficient Approach for Aligning Large Language 
  Models**, `arXiv, 2501.03262`, [arxiv](http://arxiv.org/abs/2501.03262v1), [pdf](http://arxiv.org/pdf/2501.03262v1.pdf), cication: [**-1**](None) 

	 *Jian Hu*

	 · ([OpenRLHF](https://github.com/OpenRLHF/OpenRLHF/blob/main/examples/scripts/train_reinforce_llama_ray.sh) - OpenRLHF) ![Star](https://img.shields.io/github/stars/OpenRLHF/OpenRLHF.svg?style=social&label=Star)
- 🌟 **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open 
  Language Models**, `arXiv, 2402.03300`, [arxiv](http://arxiv.org/abs/2402.03300v3), [pdf](http://arxiv.org/pdf/2402.03300v3.pdf), cication: [**155**](https://scholar.google.com/scholar?cites=10831144174319627990&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Zhihong Shao, Peiyi Wang, Qihao Zhu, ..., Y. Wu, Daya Guo* · ([𝕏](https://x.com/_philschmid/status/1875084210110599334))
- [REINFORCE++: A SIMPLE AND EFFICIENT APPROACH FOR ALIGNING LARGE LANGUAGE MODELS](https://www.researchgate.net/publication/387487679_REINFORCE_A_SIMPLE_AND_EFFICIENT_APPROACH_FOR_ALIGNING_LARGE_LANGUAGE_MODELS) 
- [如何正确复现 Instruct GPT / RLHF?](https://zhuanlan.zhihu.com/p/622134699) 
- 🌟 **VinePPO: Unlocking RL Potential For LLM Reasoning Through Refined Credit 
  Assignment**, `arXiv, 2410.01679`, [arxiv](http://arxiv.org/abs/2410.01679v1), [pdf](http://arxiv.org/pdf/2410.01679v1.pdf), cication: [**-1**](None) 

	 *Amirhossein Kazemnejad, Milad Aghajohari, Eva Portelance, ..., Aaron Courville, Nicolas Le Roux* · ([VinePPO](https://github.com/McGill-NLP/VinePPO) - McGill-NLP) ![Star](https://img.shields.io/github/stars/McGill-NLP/VinePPO.svg?style=social&label=Star)
- [Analyzing OpenAI’s Reinforcement Fine-Tuning: Less Data, Better Results](https://openpipe.ai/blog/openai-rft) 
- **Enhancing Multi-Step Reasoning Abilities of Language Models through 
  Direct Q-Function Optimization**, `arXiv, 2410.09302`, [arxiv](http://arxiv.org/abs/2410.09302v1), [pdf](http://arxiv.org/pdf/2410.09302v1.pdf), cication: [**-1**](None) 

	 *Guanlin Liu, Kaixuan Ji, Renjie Zheng, ..., Quanquan Gu, Lin Yan*
- [Spurious Correlation, Shortcut Learning, and Reward Hacking](https://yihe-deng.notion.site/Spurious-Correlation-Shortcut-Learning-and-Reward-Hacking-163ab2d2c1fb808bbfd7c6a17b01a39d) 
- **Offline Reinforcement Learning for LLM Multi-Step Reasoning**, `arXiv, 2412.16145`, [arxiv](http://arxiv.org/abs/2412.16145v1), [pdf](http://arxiv.org/pdf/2412.16145v1.pdf), cication: [**-1**](None) 

	 *Huaijie Wang, Shibo Hao, Hanze Dong, ..., Ziran Yang, Yi Wu* · ([OREO](https://github.com/jwhj/OREO) - jwhj) ![Star](https://img.shields.io/github/stars/jwhj/OREO.svg?style=social&label=Star)
- **Search, Verify and Feedback: Towards Next Generation Post-training 
  Paradigm of Foundation Models via Verifier Engineering**, `arXiv, 2411.11504`, [arxiv](http://arxiv.org/abs/2411.11504v1), [pdf](http://arxiv.org/pdf/2411.11504v1.pdf), cication: [**-1**](None) 

	 *Xinyan Guan, Yanjiang Liu, Xinyu Lu, ..., Yaojie Lu, Hongyu Lin*
- **Evaluating the role of `Constitutions` for learning from AI feedback**, `arXiv, 2411.10168`, [arxiv](http://arxiv.org/abs/2411.10168v1), [pdf](http://arxiv.org/pdf/2411.10168v1.pdf), cication: [**-1**](None) 

	 *Saskia Redgate, Andrew M. Bean, Adam Mahdi*
- 🌟 **Unpacking DPO and PPO: Disentangling Best Practices for Learning from 
  Preference Feedback**, `arXiv, 2406.09279`, [arxiv](http://arxiv.org/abs/2406.09279v2), [pdf](http://arxiv.org/pdf/2406.09279v2.pdf), cication: [**-1**](None) 

	 *Hamish Ivison, Yizhong Wang, Jiacheng Liu, ..., Yejin Choi, Hannaneh Hajishirzi* · ([EasyLM)](https://github.com/hamishivi/EasyLM)) - hamishivi) ![Star](https://img.shields.io/github/stars/hamishivi/EasyLM)· ([open-instruct)](https://github.com/allenai/open-instruct)) - allenai) ![Star](https://img.shields.io/github/stars/allenai/open-instruct)· ([huggingface](https://huggingface.co/collections/allenai/tulu-v25-suite-66676520fd578080e126f618).))
- 🌟 [Tülu 3: The next era in open post-training](https://allenai.org/blog/tulu-3-technical) 

	 · ([hf](https://hf.co/allenai/Llama-3.1-Tulu-3-70B)) · ([hf](https://hf.co/allenai/Llama-3.1-Tulu-3-8B)) · ([hf](https://hf.co/collections/allenai/tulu-3-datasets673b8df14442393f7213f372)) · ([open-instruct](https://github.com/allenai/open-instruct) - allenai) ![Star](https://img.shields.io/github/stars/allenai/open-instruct.svg?style=social&label=Star) · ([olmes](https://github.com/allenai/olmes) - allenai) ![Star](https://img.shields.io/github/stars/allenai/olmes.svg?style=social&label=Star) · ([playground.allenai](https://playground.allenai.org/))
- 🌟 [Everything You Wanted to Know About LLM Post-Training, with Nathan Lambert of Allen Institute for AI](https://www.youtube.com/watch?v=LVXtFnEbNU0)  :clapper: 
- **Direct Preference Optimization Using Sparse Feature-Level Constraints**, `arXiv, 2411.07618`, [arxiv](http://arxiv.org/abs/2411.07618v1), [pdf](http://arxiv.org/pdf/2411.07618v1.pdf), cication: [**-1**](None) 

	 *Qingyu Yin, Chak Tou Leong, Hongbo Zhang, ..., Yue Zhang, Linyi Yang*
- [Mira: A Decentralized Network for Trustless AI Output Verification](https://mira.network/research/mira-whitepaper.pdf) 

	 · ([mira](https://mira.network/)) · ([huggingface](https://huggingface.co/datasets/Mira-Network/ensemble-validation?row=0))
- **Self-Evolved Reward Learning for LLMs**, `arXiv, 2411.00418`, [arxiv](http://arxiv.org/abs/2411.00418v1), [pdf](http://arxiv.org/pdf/2411.00418v1.pdf), cication: [**-1**](None) 

	 *Chenghua Huang, Zhizhen Fan, Lu Wang, ..., Saravan Rajmohan, Qi Zhang*
- **Self-Consistency Preference Optimization**, `arXiv, 2411.04109`, [arxiv](http://arxiv.org/abs/2411.04109v2), [pdf](http://arxiv.org/pdf/2411.04109v2.pdf), cication: [**-1**](None) 

	 *Archiki Prasad, Weizhe Yuan, Richard Yuanzhe Pang, ..., Jason Weston, Jane Yu*
- **Evolving Alignment via Asymmetric Self-Play**, `arXiv, 2411.00062`, [arxiv](http://arxiv.org/abs/2411.00062v1), [pdf](http://arxiv.org/pdf/2411.00062v1.pdf), cication: [**-1**](None) 

	 *Ziyu Ye, Rishabh Agarwal, Tianqi Liu, ..., Qijun Tan, Yuan Liu* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-11-05-6))
- **Hybrid Preferences: Learning to Route Instances for Human vs. AI 
  Feedback**, `arXiv, 2410.19133`, [arxiv](http://arxiv.org/abs/2410.19133v2), [pdf](http://arxiv.org/pdf/2410.19133v2.pdf), cication: [**-1**](None)

	 *Lester James V. Miranda, Yizhong Wang, Yanai Elazar, ..., Hannaneh Hajishirzi, Pradeep Dasigi*
- **LongReward: Improving Long-context Large Language Models with AI 
  Feedback**, `arXiv, 2410.21252`, [arxiv](http://arxiv.org/abs/2410.21252v1), [pdf](http://arxiv.org/pdf/2410.21252v1.pdf), cication: [**-1**](None)

	 *Jiajie Zhang, Zhongni Hou, Xin Lv, ..., Ling Feng, Juanzi Li* · ([LongReward](https://github.com/THUDM/LongReward) - THUDM) ![Star](https://img.shields.io/github/stars/THUDM/LongReward.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/datasets/THUDM/LongReward-10k))
- [Thinking LLMs: General Instruction Following With Thought Generation](https://x.com/rasbt/status/1850177459930497118)  𝕏 
- **MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large 
  Vision-Language Models**, `arXiv, 2410.17637`, [arxiv](http://arxiv.org/abs/2410.17637v1), [pdf](http://arxiv.org/pdf/2410.17637v1.pdf), cication: [**-1**](None)

	 *Ziyu Liu, Yuhang Zang, Xiaoyi Dong, ..., Dahua Lin, Jiaqi Wang*

## Reward Models

- **What Makes a Reward Model a Good Teacher? An Optimization Perspective**, `arXiv, 2503.15477`, [arxiv](http://arxiv.org/abs/2503.15477v1), [pdf](http://arxiv.org/pdf/2503.15477v1.pdf), cication: [**-1**](None) 

	 *Noam Razin, Zixuan Wang, Hubert Strauss, ..., Jason D. Lee, Sanjeev Arora*
- **Skywork-Reward: Bag of Tricks for Reward Modeling in LLMs**, `arXiv, 2410.18451`, [arxiv](http://arxiv.org/abs/2410.18451v1), [pdf](http://arxiv.org/pdf/2410.18451v1.pdf), cication: [**-1**](None) 

	 *Chris Yuhao Liu, Liang Zeng, Jiacai Liu, ..., Yang Liu, Yahui Zhou*

	 · ([huggingface](https://huggingface.co/Skywork/Skywork-Reward-Llama-3.1-8B-v0.2)) · ([huggingface](https://huggingface.co/Skywork/Skywork-Reward-Gemma-2-27B-v0.2)) · ([huggingface](https://huggingface.co/datasets/Skywork/Skywork-Reward-Preference-80K-v0.2))
- [benchmark: Preference Proxy Evaluations (PPE)](https://x.com/lmarena_ai/status/1848778976585781369)  𝕏 

	 · ([blog.lmarena](https://blog.lmarena.ai/blog/2024/preference-proxy-evaluations/)) · ([arxiv](https://arxiv.org/abs/2410.14872)) · ([PPE](https://github.com/lmarena/PPE) - lmarena) ![Star](https://img.shields.io/github/stars/lmarena/PPE.svg?style=social&label=Star)
- **RM-Bench: Benchmarking Reward Models of Language Models with Subtlety 
  and Style**, `arXiv, 2410.16184`, [arxiv](http://arxiv.org/abs/2410.16184v1), [pdf](http://arxiv.org/pdf/2410.16184v1.pdf), cication: [**-1**](None)

	 *Yantao Liu, Zijun Yao, Rui Min, ..., Lei Hou, Juanzi Li* · ([RM-Bench](https://github.com/THU-KEG/RM-Bench) - THU-KEG) ![Star](https://img.shields.io/github/stars/THU-KEG/RM-Bench.svg?style=social&label=Star)

## Projects

- [**RL**](https://github.com/NVIDIA-NeMo/RL) - NVIDIA-NeMo ![Star](https://img.shields.io/github/stars/NVIDIA-NeMo/RL.svg?style=social&label=Star)

	 *A Scalable and Efficient Post-Training Library*
- :star2: [**OpenRLHF**](https://github.com/OpenRLHF/OpenRLHF) - OpenRLHF ![Star](https://img.shields.io/github/stars/OpenRLHF/OpenRLHF.svg?style=social&label=Star) 

	 · ([arxiv](https://arxiv.org/abs/2405.11143)) · ([docs.google](https://docs.google.com/presentation/d/1JRhB1d7csofx0PIZBmfyBdMluxNd5JLPpUHrrvVhGnk/edit?usp=sharing))
- [**verl**](https://github.com/volcengine/verl) - volcengine ![Star](https://img.shields.io/github/stars/volcengine/verl.svg?style=social&label=Star) 

	 *Volcano Engine Reinforcement Learning for LLM* · ([arxiv](https://arxiv.org/abs/2409.19256v2))

## Misc

- [Why RLHF (and Other RL-Like Methods) Don’t Bring “True RL” to LLMs—and Why It Matters                                                                                                                                                                                                                                                                                                                        Report this article](https://www.linkedin.com/pulse/why-rlhf-other-rl-like-methods-dont-bring-true-rl-llmsand-atlas-wang-s1efc) 
- [Advanced Tricks for Training Large Language Models with Proximal Policy Optimization](https://hijkzzz.notion.site/rlhf-implementation-tricks?v=158d9a33ecc98132bf9e000c39227361) 
- [Tulu 3: Exploring Frontiers in Open Language Model Post-Training - Nathan Lambert (AI2)](https://www.youtube.com/watch?v=ltSzUIJ9m6s&list=PLWRU-w8UhT6jNg64UfBB0VtlvI4Upe914&index=6)  :clapper: 
- :clapper: [Generative Reward Models: Merging the Power of RLHF and RLAIF for Smarter AI](https://www.youtube.com/watch?v=Ak0vkBKOz0U) 