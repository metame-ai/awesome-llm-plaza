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

- **Logical Reasoning in Large Language Models: A Survey**, `arXiv, 2502.09100`, [arxiv](http://arxiv.org/abs/2502.09100v1), [pdf](http://arxiv.org/pdf/2502.09100v1.pdf), cication: [**-1**](None) 

	 *Hanmeng Liu, Zhizhang Fu, Mengru Ding, ..., Xiaozhang Liu, Yue Zhang*
- 🌟 **Towards Large Reasoning Models: A Survey on Scaling LLM Reasoning 
  Capabilities**, `arXiv, 2501.09686`, [arxiv](http://arxiv.org/abs/2501.09686v2), [pdf](http://arxiv.org/pdf/2501.09686v2.pdf), cication: [**-1**](None) 

	 *Fengli Xu, Qianyue Hao, Zefang Zong, ..., Chen Gao, Yong Li*
- 🌟 **Test-time Computing: from System-1 Thinking to System-2 Thinking**, `arXiv, 2501.02497`, [arxiv](http://arxiv.org/abs/2501.02497v1), [pdf](http://arxiv.org/pdf/2501.02497v1.pdf), cication: [**-1**](None) 

	 *Yixin Ji, Juntao Li, Hai Ye, ..., Linjian Mo, Min Zhang* · ([Awesome_Test_Time_LLMs](https://github.com/Dereck0602/Awesome_Test_Time_LLMs) - Dereck0602) ![Star](https://img.shields.io/github/stars/Dereck0602/Awesome_Test_Time_LLMs.svg?style=social&label=Star)
- **A Survey on LLM Inference-Time Self-Improvement**, `arXiv, 2412.14352`, [arxiv](http://arxiv.org/abs/2412.14352v1), [pdf](http://arxiv.org/pdf/2412.14352v1.pdf), cication: [**-1**](None) 

	 *Xiangjue Dong, Maria Teleki, James Caverlee*

## Reasoning

- **CodeI/O: Condensing Reasoning Patterns via Code Input-Output Prediction**, `arXiv, 2502.07316`, [arxiv](http://arxiv.org/abs/2502.07316v3), [pdf](http://arxiv.org/pdf/2502.07316v3.pdf), cication: [**-1**](None) 

	 *Junlong Li, Daya Guo, Dejian Yang, ..., Yu Wu, Junxian He* · ([codei-o.github](https://codei-o.github.io/))
- **Teaching Language Models to Critique via Reinforcement Learning**, `arXiv, 2502.03492`, [arxiv](http://arxiv.org/abs/2502.03492v1), [pdf](http://arxiv.org/pdf/2502.03492v1.pdf), cication: [**-1**](None) 

	 *Zhihui Xie, Jie chen, Liyu Chen, ..., Jingjing Xu, Lingpeng Kong* · ([critic-rl.github](https://critic-rl.github.io/)) · ([critic-rl](https://github.com/HKUNLP/critic-rl) - HKUNLP) ![Star](https://img.shields.io/github/stars/HKUNLP/critic-rl.svg?style=social&label=Star)
- **MME-CoT: Benchmarking Chain-of-Thought in Large Multimodal Models for 
  Reasoning Quality, Robustness, and Efficiency**, `arXiv, 2502.09621`, [arxiv](http://arxiv.org/abs/2502.09621v1), [pdf](http://arxiv.org/pdf/2502.09621v1.pdf), cication: [**-1**](None) 

	 *Dongzhi Jiang, Renrui Zhang, Ziyu Guo, ..., Peng Gao, Hongsheng Li* · ([mmecot.github](https://mmecot.github.io/))
- **Diverse Inference and Verification for Advanced Reasoning**, `arXiv, 2502.09955`, [arxiv](http://arxiv.org/abs/2502.09955v1), [pdf](http://arxiv.org/pdf/2502.09955v1.pdf), cication: [**-1**](None) 

	 *Iddo Drori, Gaston Longhitano, Mao Mao, ..., Alon Amit, Madeleine Udell*
- **Large Language Models Think Too Fast To Explore Effectively**, `arXiv, 2501.18009`, [arxiv](http://arxiv.org/abs/2501.18009v1), [pdf](http://arxiv.org/pdf/2501.18009v1.pdf), cication: [**-1**](None) 

	 *Lan Pan, Hanbo Xie, Robert C. Wilson*
- **Satori: Reinforcement Learning with Chain-of-Action-Thought Enhances LLM 
  Reasoning via Autoregressive Search**, `arXiv, 2502.02508`, [arxiv](http://arxiv.org/abs/2502.02508v1), [pdf](http://arxiv.org/pdf/2502.02508v1.pdf), cication: [**-1**](None) 

	 *Maohao Shen, Guangtao Zeng, Zhenting Qi, ..., David Cox, Chuang Gan*
- **BOLT: Bootstrap Long Chain-of-Thought in Language Models without 
  Distillation**, `arXiv, 2502.03860`, [arxiv](http://arxiv.org/abs/2502.03860v1), [pdf](http://arxiv.org/pdf/2502.03860v1.pdf), cication: [**-1**](None) 

	 *Bo Pang, Hanze Dong, Jiacheng Xu, ..., Yingbo Zhou, Caiming Xiong*
- **Step Back to Leap Forward: Self-Backtracking for Boosting Reasoning of 
  Language Models**, `arXiv, 2502.04404`, [arxiv](http://arxiv.org/abs/2502.04404v1), [pdf](http://arxiv.org/pdf/2502.04404v1.pdf), cication: [**-1**](None) 

	 *Xiao-Wen Yang, Xuan-Yi Zhu, Wen-Da Wei, ..., Lan-Zhe Guo, Yu-Feng Li* · ([Self-Backtracking](https://github.com/LAMDASZ-ML/Self-Backtracking) - LAMDASZ-ML) ![Star](https://img.shields.io/github/stars/LAMDASZ-ML/Self-Backtracking.svg?style=social&label=Star)
- 🌟 **Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth 
  Approach**, `arXiv, 2502.05171`, [arxiv](http://arxiv.org/abs/2502.05171v1), [pdf](http://arxiv.org/pdf/2502.05171v1.pdf), cication: [**-1**](None) 

	 *Jonas Geiping, Sean McLeish, Neel Jain, ..., Abhinav Bhatele, Tom Goldstein* · ([huggingface](https://huggingface.co/tomg-group-umd/huginn-0125)) · ([𝕏](https://x.com/tomgoldsteincs/status/1888980680790393085))
- **Iterate to Accelerate: A Unified Framework for Iterative Reasoning and 
  Feedback Convergence**, `arXiv, 2502.03787`, [arxiv](http://arxiv.org/abs/2502.03787v1), [pdf](http://arxiv.org/pdf/2502.03787v1.pdf), cication: [**-1**](None) 

	 *Jacob Fein-Ashley*

	 · ([reddit](https://www.reddit.com/r/MachineLearning/comments/1ijjq5y/r_it_turns_out_we_really_did_need_rnns/))
- **Token Assorted: Mixing Latent and Text Tokens for Improved Language 
  Model Reasoning**, `arXiv, 2502.03275`, [arxiv](http://arxiv.org/abs/2502.03275v1), [pdf](http://arxiv.org/pdf/2502.03275v1.pdf), cication: [**-1**](None) 

	 *DiJia Su, Hanlin Zhu, Yingchen Xu, ..., Yuandong Tian, Qinqing Zheng*
- 🌟 **LIMO: Less is More for Reasoning**, `arXiv, 2502.03387`, [arxiv](http://arxiv.org/abs/2502.03387v1), [pdf](http://arxiv.org/pdf/2502.03387v1.pdf), cication: [**-1**](None) 

	 *Yixin Ye, Zhen Huang, Yang Xiao, ..., Shijie Xia, Pengfei Liu* · ([LIMO](https://github.com/GAIR-NLP/LIMO) - GAIR-NLP) ![Star](https://img.shields.io/github/stars/GAIR-NLP/LIMO.svg?style=social&label=Star)
- **Critique Fine-Tuning: Learning to Critique is More Effective than 
  Learning to Imitate**, `arXiv, 2501.17703`, [arxiv](http://arxiv.org/abs/2501.17703v3), [pdf](http://arxiv.org/pdf/2501.17703v3.pdf), cication: [**-1**](None) 

	 *Yubo Wang, Xiang Yue, Wenhu Chen* · ([CritiqueFineTuning](https://github.com/TIGER-AI-Lab/CritiqueFineTuning) - TIGER-AI-Lab) ![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/CritiqueFineTuning.svg?style=social&label=Star)
- **Reasoning Language Models: A Blueprint**, `arXiv, 2501.11223`, [arxiv](http://arxiv.org/abs/2501.11223v3), [pdf](http://arxiv.org/pdf/2501.11223v3.pdf), cication: [**-1**](None) 

	 *Maciej Besta, Julia Barth, Eric Schreiber, ..., Hubert Niewiadomski, Torsten Hoefler*
- **PokerBench: Training Large Language Models to become Professional Poker 
  Players**, `arXiv, 2501.08328`, [arxiv](http://arxiv.org/abs/2501.08328v1), [pdf](http://arxiv.org/pdf/2501.08328v1.pdf), cication: [**-1**](None) 

	 *Richard Zhuang, Akshat Gupta, Richard Yang, ..., Zhengyu Li, Gopala Anumanchipalli* · ([pokerbench](https://github.com/pokerllm/pokerbench) - pokerllm) ![Star](https://img.shields.io/github/stars/pokerllm/pokerbench.svg?style=social&label=Star)
- 🌟 **OmniThink: Expanding Knowledge Boundaries in Machine Writing through 
  Thinking**, `arXiv, 2501.09751`, [arxiv](http://arxiv.org/abs/2501.09751v1), [pdf](http://arxiv.org/pdf/2501.09751v1.pdf), cication: [**-1**](None) 

	 *Zekun Xi, Wenbiao Yin, Jizhan Fang, ..., Fei Huang, Huajun Chen* · ([zjunlp.github](https://zjunlp.github.io/project/OmniThink/))
- 🌟 **Evolving Deeper LLM Thinking**, `arXiv, 2501.09891`, [arxiv](http://arxiv.org/abs/2501.09891v1), [pdf](http://arxiv.org/pdf/2501.09891v1.pdf), cication: [**-1**](None) 

	 *Kuang-Huei Lee, Ian Fischer, Yueh-Hua Wu, ..., Dale Schuurmans, Xinyun Chen*
- **Multiple Choice Questions: Reasoning Makes Large Language Models (LLMs) 
  More Self-Confident Even When They Are Wrong**, `arXiv, 2501.09775`, [arxiv](http://arxiv.org/abs/2501.09775v1), [pdf](http://arxiv.org/pdf/2501.09775v1.pdf), cication: [**-1**](None) 

	 *Tairan Fu, Javier Conde, Gonzalo Martínez, ..., María Grandury, Pedro Reviriego*
- **Multiagent Finetuning: Self Improvement with Diverse Reasoning Chains**, `arXiv, 2501.05707`, [arxiv](http://arxiv.org/abs/2501.05707v1), [pdf](http://arxiv.org/pdf/2501.05707v1.pdf), cication: [**-1**](None) 

	 *Vighnesh Subramaniam, Yilun Du, Joshua B. Tenenbaum, ..., Shuang Li, Igor Mordatch* · ([llm-multiagent-ft.github](https://llm-multiagent-ft.github.io/))
- [Towards AI Superhuman Reasoning for Math and beyond](https://llm-class.github.io/speakers.html) 

	 · ([youtu](https://youtu.be/y5qEFrZv-2Q))
- **Aligning with Logic: Measuring, Evaluating and Improving Logical 
  Consistency in Large Language Models**, `arXiv, 2410.02205`, [arxiv](http://arxiv.org/abs/2410.02205v2), [pdf](http://arxiv.org/pdf/2410.02205v2.pdf), cication: [**-1**](None) 

	 *Yinhong Liu, Zhijiang Guo, Tianya Liang, ..., Ivan Vulić, Nigel Collier*
- 🌟 **Quiet-STaR: Language Models Can Teach Themselves to Think Before 
  Speaking**, `arXiv, 2403.09629`, [arxiv](http://arxiv.org/abs/2403.09629v2), [pdf](http://arxiv.org/pdf/2403.09629v2.pdf), cication: [**-1**](None) 

	 *Eric Zelikman, Georges Harik, Yijia Shao, ..., Nick Haber, Noah D. Goodman*
- 🌟 **Token-Budget-Aware LLM Reasoning**, `arXiv, 2412.18547`, [arxiv](http://arxiv.org/abs/2412.18547v2), [pdf](http://arxiv.org/pdf/2412.18547v2.pdf), cication: [**-1**](None) 

	 *Tingxu Han, Chunrong Fang, Shiyu Zhao, ..., Zhenyu Chen, Zhenting Wang* · ([TALE](https://github.com/GeniusHTX/TALE) - GeniusHTX) ![Star](https://img.shields.io/github/stars/GeniusHTX/TALE.svg?style=social&label=Star) · ([𝕏](https://x.com/wang1999_zt/status/1871967246685557130))
- 🌟 **B-STaR: Monitoring and Balancing Exploration and Exploitation in 
  Self-Taught Reasoners**, `arXiv, 2412.17256`, [arxiv](http://arxiv.org/abs/2412.17256v1), [pdf](http://arxiv.org/pdf/2412.17256v1.pdf), cication: [**-1**](None) 

	 *Weihao Zeng, Yuzhen Huang, Lulu Zhao, ..., Zifei Shan, Junxian He*
- **Deliberation in Latent Space via Differentiable Cache Augmentation**, `arXiv, 2412.17747`, [arxiv](http://arxiv.org/abs/2412.17747v1), [pdf](http://arxiv.org/pdf/2412.17747v1.pdf), cication: [**-1**](None) 

	 *Luyang Liu, Jonas Pfeiffer, Jiaxing Wu, ..., Jun Xie, Arthur Szlam*
- **Ensembling Large Language Models with Process Reward-Guided Tree Search 
  for Better Complex Reasoning**, `arXiv, 2412.15797`, [arxiv](http://arxiv.org/abs/2412.15797v1), [pdf](http://arxiv.org/pdf/2412.15797v1.pdf), cication: [**-1**](None) 

	 *Sungjin Park, Xiao Liu, Yeyun Gong, ..., Edward Choi*
- 🌟 **Chain-of-Thought Reasoning Without Prompting**, `arXiv, 2402.10200`, [arxiv](http://arxiv.org/abs/2402.10200v2), [pdf](http://arxiv.org/pdf/2402.10200v2.pdf), cication: [**-1**](None) 

	 *Xuezhi Wang, Denny Zhou* · ([𝕏](https://x.com/denny_zhou/status/1872366450020659483))
- **SPaR: Self-Play with Tree-Search Refinement to Improve 
  Instruction-Following in Large Language Models**, `arXiv, 2412.11605`, [arxiv](http://arxiv.org/abs/2412.11605v1), [pdf](http://arxiv.org/pdf/2412.11605v1.pdf), cication: [**-1**](None) 

	 *Jiale Cheng, Xiao Liu, Cunxiang Wang, ..., Hongning Wang, Minlie Huang* · ([SPaR](https://github.com/thu-coai/SPaR) - thu-coai) ![Star](https://img.shields.io/github/stars/thu-coai/SPaR.svg?style=social&label=Star)
- 🌟 **Are Your LLMs Capable of Stable Reasoning?**, `arXiv, 2412.13147`, [arxiv](http://arxiv.org/abs/2412.13147v2), [pdf](http://arxiv.org/pdf/2412.13147v2.pdf), cication: [**-1**](None) 

	 *Junnan Liu, Hongwei Liu, Linchen Xiao, ..., Songyang Zhang, Kai Chen* · ([GPassK.](https://github.com/open-compass/GPassK.) - open-compass) ![Star](https://img.shields.io/github/stars/open-compass/GPassK..svg?style=social&label=Star)
- **Compressed Chain of Thought: Efficient Reasoning Through Dense 
  Representations**, `arXiv, 2412.13171`, [arxiv](http://arxiv.org/abs/2412.13171v1), [pdf](http://arxiv.org/pdf/2412.13171v1.pdf), cication: [**-1**](None) 

	 *Jeffrey Cheng, Benjamin Van Durme*
- **LongBench v2: Towards Deeper Understanding and Reasoning on Realistic 
  Long-context Multitasks**, `arXiv, 2412.15204`, [arxiv](http://arxiv.org/abs/2412.15204v1), [pdf](http://arxiv.org/pdf/2412.15204v1.pdf), cication: [**-1**](None) 

	 *Yushi Bai, Shangqing Tu, Jiajie Zhang, ..., Jie Tang, Juanzi Li* · ([longbench2.github](https://longbench2.github.io))
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

- **Goedel-Prover: A Frontier Model for Open-Source Automated Theorem 
  Proving**, `arXiv, 2502.07640`, [arxiv](http://arxiv.org/abs/2502.07640v2), [pdf](http://arxiv.org/pdf/2502.07640v2.pdf), cication: [**-1**](None) 

	 *Yong Lin, Shange Tang, Bohan Lyu, ..., Sanjeev Arora, Chi Jin* · ([goedel-lm.github](https://goedel-lm.github.io/))
- **PDE-Controller: LLMs for Autoformalization and Reasoning of PDEs**, `arXiv, 2502.00963`, [arxiv](http://arxiv.org/abs/2502.00963v1), [pdf](http://arxiv.org/pdf/2502.00963v1.pdf), cication: [**-1**](None) 

	 *Mauricio Soroco, Jialin Song, Mengzhou Xia, ..., Weiran Sun, Wuyang Chen* · ([pde-controller.github](https://pde-controller.github.io/))
- [OpenR1-Math-220k is a large-scale dataset for mathematical reasoning.](https://huggingface.co/datasets/open-r1/OpenR1-Math-220k)  🤗 
- [MathArena: Evaluating LLMs on Uncontaminated Math Competitions](https://matharena.ai/) 
- 🌟 **Gold-medalist Performance in Solving Olympiad Geometry with 
  AlphaGeometry2**, `arXiv, 2502.03544`, [arxiv](http://arxiv.org/abs/2502.03544v1), [pdf](http://arxiv.org/pdf/2502.03544v1.pdf), cication: [**-1**](None) 

	 *Yuri Chervonyi, Trieu H. Trinh, Miroslav Olšák, ..., Quoc V. Le, Thang Luong* · ([𝕏](https://x.com/lmthang/status/1887928665100665111))
- **Step-KTO: Optimizing Mathematical Reasoning through Stepwise Binary 
  Feedback**, `arXiv, 2501.10799`, [arxiv](http://arxiv.org/abs/2501.10799v1), [pdf](http://arxiv.org/pdf/2501.10799v1.pdf), cication: [**-1**](None) 

	 *Yen-Ting Lin, Di Jin, Tengyu Xu, ..., Hao Ma, Han Fang*
- 🌟 **The Lessons of Developing Process Reward Models in Mathematical 
  Reasoning**, `arXiv, 2501.07301`, [arxiv](http://arxiv.org/abs/2501.07301v1), [pdf](http://arxiv.org/pdf/2501.07301v1.pdf), cication: [**-1**](None) 

	 *Zhenru Zhang, Chujie Zheng, Yangzhen Wu, ..., Jingren Zhou, Junyang Lin*
- 🌟 **BoostStep: Boosting mathematical capability of Large Language Models via 
  improved single-step reasoning**, `arXiv, 2501.03226`, [arxiv](http://arxiv.org/abs/2501.03226v1), [pdf](http://arxiv.org/pdf/2501.03226v1.pdf), cication: [**-1**](None) 

	 *Beichen Zhang, Yuhong Liu, Xiaoyi Dong, ..., Dahua Lin, Jiaqi Wang* · ([BoostStep](https://github.com/beichenzbc/BoostStep) - beichenzbc) ![Star](https://img.shields.io/github/stars/beichenzbc/BoostStep.svg?style=social&label=Star)
- **URSA: Understanding and Verifying Chain-of-thought Reasoning in 
  Multimodal Mathematics**, `arXiv, 2501.04686`, [arxiv](http://arxiv.org/abs/2501.04686v1), [pdf](http://arxiv.org/pdf/2501.04686v1.pdf), cication: [**-1**](None) 

	 *Ruilin Luo, Zhuofan Zheng, Yifan Wang, ..., Jin Zeng, Yujiu Yang* · ([ursa-math.github](https://ursa-math.github.io/))
- 🌟 **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open 
  Language Models**, `arXiv, 2402.03300`, [arxiv](http://arxiv.org/abs/2402.03300v3), [pdf](http://arxiv.org/pdf/2402.03300v3.pdf), cication: [**155**](https://scholar.google.com/scholar?cites=10831144174319627990&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Zhihong Shao, Peiyi Wang, Qihao Zhu, ..., Y. Wu, Daya Guo* · ([𝕏](https://x.com/_philschmid/status/1875084210110599334))
- [continual-pre-training of Llama-3.2-3B on a mix of  📐 FineMath (our new high quality math dataset) and FineWeb-Edu.](https://huggingface.co/HuggingFaceTB/FineMath-Llama-3B)  🤗 
- **Slow Perception: Let's Perceive Geometric Figures Step-by-step**, `arXiv, 2412.20631`, [arxiv](http://arxiv.org/abs/2412.20631v1), [pdf](http://arxiv.org/pdf/2412.20631v1.pdf), cication: [**-1**](None) 

	 *Haoran Wei, Youyang Yin, Yumeng Li, ..., Zheng Ge, Xiangyu Zhang* · ([Slow-Perception](https://github.com/Ucas-HaoranWei/Slow-Perception) - Ucas-HaoranWei) ![Star](https://img.shields.io/github/stars/Ucas-HaoranWei/Slow-Perception.svg?style=social&label=Star)
- **HUNYUANPROVER: A Scalable Data Synthesis Framework and Guided Tree 
  Search for Automated Theorem Proving**, `arXiv, 2412.20735`, [arxiv](http://arxiv.org/abs/2412.20735v2), [pdf](http://arxiv.org/pdf/2412.20735v2.pdf), cication: [**-1**](None) 

	 *Yang Li, Dong Du, Linfeng Song, ..., Tao Yang, Haitao Mi*
- **AceMath: Advancing Frontier Math Reasoning with Post-Training and Reward 
  Modeling**, `arXiv, 2412.15084`, [arxiv](http://arxiv.org/abs/2412.15084v1), [pdf](http://arxiv.org/pdf/2412.15084v1.pdf), cication: [**-1**](None) 

	 *Zihan Liu, Yang Chen, Mohammad Shoeybi, ..., Bryan Catanzaro, Wei Ping* · ([research.nvidia](https://research.nvidia.com/labs/adlr/acemath))
- **Formal Mathematical Reasoning: A New Frontier in AI**, `arXiv, 2412.16075`, [arxiv](http://arxiv.org/abs/2412.16075v1), [pdf](http://arxiv.org/pdf/2412.16075v1.pdf), cication: [**-1**](None) 

	 *Kaiyu Yang, Gabriel Poesia, Jingxuan He, ..., Swarat Chaudhuri, Dawn Song*
- [FineMath consists of 34B tokens (FineMath-3+) and 54B tokens (FineMath-3+ with InfiMM-WebMath-3+) of mathematical educational content filtered from CommonCrawl.](https://huggingface.co/datasets/HuggingFaceTB/finemath)  🤗 

	 · ([𝕏](https://x.com/anton_lozhkov/status/1869771053146464507))
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

- **LLMs Can Easily Learn to Reason from Demonstrations Structure, not 
  content, is what matters!**, `arXiv, 2502.07374`, [arxiv](http://arxiv.org/abs/2502.07374v1), [pdf](http://arxiv.org/pdf/2502.07374v1.pdf), cication: [**-1**](None) 

	 *Dacheng Li, Shiyi Cao, Tyler Griggs, ..., Joseph E. Gonzalez, Ion Stoica* · ([SkyThought](https://github.com/NovaSky-AI/SkyThought) - NovaSky-AI) ![Star](https://img.shields.io/github/stars/NovaSky-AI/SkyThought.svg?style=social&label=Star)
- **The Danger of Overthinking: Examining the Reasoning-Action Dilemma in 
  Agentic Tasks**, `arXiv, 2502.08235`, [arxiv](http://arxiv.org/abs/2502.08235v1), [pdf](http://arxiv.org/pdf/2502.08235v1.pdf), cication: [**-1**](None) 

	 *Alejandro Cuadron, Dacheng Li, Wenjie Ma, ..., Graham Neubig, Joseph E. Gonzalez* · ([Overthinking](https://github.com/AlexCuadron/Overthinking) - AlexCuadron) ![Star](https://img.shields.io/github/stars/AlexCuadron/Overthinking.svg?style=social&label=Star)
- 🌟 **Exploring the Limit of Outcome Reward for Learning Mathematical 
  Reasoning**, `arXiv, 2502.06781`, [arxiv](http://arxiv.org/abs/2502.06781v1), [pdf](http://arxiv.org/pdf/2502.06781v1.pdf), cication: [**-1**](None) 

	 *Chengqi Lyu, Songyang Gao, Yuzhe Gu, ..., Dahua Lin, Kai Chen* · ([OREAL](https://github.com/InternLM/OREAL) - InternLM) ![Star](https://img.shields.io/github/stars/InternLM/OREAL.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s/o6csP1xSdg6gISXVmrnNcw))
- **Process Reinforcement through Implicit Rewards**, `arXiv, 2502.01456`, [arxiv](http://arxiv.org/abs/2502.01456v1), [pdf](http://arxiv.org/pdf/2502.01456v1.pdf), cication: [**-1**](None) 

	 *Ganqu Cui, Lifan Yuan, Zefan Wang, ..., Bowen Zhou, Ning Ding* · ([PRIME](https://github.com/PRIME-RL/PRIME) - PRIME-RL) ![Star](https://img.shields.io/github/stars/PRIME-RL/PRIME.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/PRIME-RL))
- 🌟 **Can 1B LLM Surpass 405B LLM? Rethinking Compute-Optimal Test-Time 
  Scaling**, `arXiv, 2502.06703`, [arxiv](http://arxiv.org/abs/2502.06703v1), [pdf](http://arxiv.org/pdf/2502.06703v1.pdf), cication: [**-1**](None) 

	 *Runze Liu, Junqi Gao, Jian Zhao, ..., Wanli Ouyang, Bowen Zhou* · ([ryanliu112.github](https://ryanliu112.github.io/compute-optimal-tts/))
- [Reasoning LLM using REINFORCE](https://charm-octagon-74d.notion.site/Reasoning-LLM-using-REINFORCE-194e4301cb9980e7b73dd8c2f0fdc6a0) 
- **On the Emergence of Thinking in LLMs I: Searching for the Right 
  Intuition**, `arXiv, 2502.06773`, [arxiv](http://arxiv.org/abs/2502.06773v1), [pdf](http://arxiv.org/pdf/2502.06773v1.pdf), cication: [**-1**](None) 

	 *Guanghao Ye, Khiem Duc Pham, Xinzhi Zhang, ..., Janardhan Kulkarni, Huseyin A. Inan*
- [7B Model and 8K Examples: Emerging Reasoning with Reinforcement Learning is Both Effective and Efficient](https://hkust-nlp.notion.site/simplerl-reason) 
- [There May Not be Aha Moment in R1-Zero-like Training — A Pilot Study](https://oatllm.notion.site/oat-zero) 
- [Qwen 0.5b on GRPO](https://colab.research.google.com/drive/1bfhs1FMLW3FGa8ydvkOZyBNxLYOu0Hev?usp=sharing) 
- [DeepScaleR: Surpassing O1-Preview with a 1.5B Model by Scaling RL](https://pretty-radio-b75.notion.site/DeepScaleR-Surpassing-O1-Preview-with-a-1-5B-Model-by-Scaling-RL-19681902c1468005bed8ca303013a4e2) 

	 · ([𝕏](https://x.com/agentica_)) · ([deepscaler](https://github.com/agentica-project/deepscaler) - agentica-project) ![Star](https://img.shields.io/github/stars/agentica-project/deepscaler.svg?style=social&label=Star)
- 🌟 **s1: Simple test-time scaling**, `arXiv, 2501.19393`, [arxiv](http://arxiv.org/abs/2501.19393v2), [pdf](http://arxiv.org/pdf/2501.19393v2.pdf), cication: [**-1**](None) 

	 *Niklas Muennighoff, Zitong Yang, Weijia Shi, ..., Emmanuel Candès, Tatsunori Hashimoto* · ([s1](https://github.com/simplescaling/s1) - simplescaling) ![Star](https://img.shields.io/github/stars/simplescaling/s1.svg?style=social&label=Star)
- [a fine-tuned version of Qwen/Qwen2.5-32B-Instruct on the Bespoke-Stratos-17k dataset.](https://huggingface.co/bespokelabs/Bespoke-Stratos-32B)  🤗 
- 🌟 **Thoughts Are All Over the Place: On the Underthinking of o1-Like LLMs**, `arXiv, 2501.18585`, [arxiv](http://arxiv.org/abs/2501.18585v1), [pdf](http://arxiv.org/pdf/2501.18585v1.pdf), cication: [**-1**](None) 

	 *Yue Wang, Qiuzhi Liu, Jiahao Xu, ..., Haitao Mi, Dong Yu*
- [How DeepSeek Changes the LLM Story](https://www.youtube.com/watch?v=0eMzc-WnBfQ)  :clapper: 
- [o1复现的一点点心得](https://zhuanlan.zhihu.com/p/13872128423) 
- 🌟 [**simpleRL-reason**](https://github.com/hkust-nlp/simpleRL-reason) - hkust-nlp ![Star](https://img.shields.io/github/stars/hkust-nlp/simpleRL-reason.svg?style=social&label=Star) 

	 *Emerging Reasoning with Reinforcement Learning is Both Effective and Efficient* · ([hkust-nlp.notion](https://hkust-nlp.notion.site/simplerl-reason))
- 🌟 [**open-r1**](https://github.com/huggingface/open-r1) - huggingface ![Star](https://img.shields.io/github/stars/huggingface/open-r1.svg?style=social&label=Star) 
- [**TinyZero**](https://github.com/Jiayi-Pan/TinyZero) - Jiayi-Pan ![Star](https://img.shields.io/github/stars/Jiayi-Pan/TinyZero.svg?style=social&label=Star) 

	 · ([𝕏](https://x.com/jiayi_pirate/status/1882839370505621655)) · ([wandb](https://wandb.ai/jiayipan/TinyZero))
- [With R1, a lot of people have been asking “how come we didn't discover this 2 years ago?”](https://x.com/its_dibya/status/1883595705736163727)  𝕏 
- **O1-Pruner: Length-Harmonizing Fine-Tuning for O1-Like Reasoning Pruning**, `arXiv, 2501.12570`, [arxiv](http://arxiv.org/abs/2501.12570v2), [pdf](http://arxiv.org/pdf/2501.12570v2.pdf), cication: [**-1**](None) 

	 *Haotian Luo, Li Shen, Haiying He, ..., Xiaochun Cao, Dacheng Tao* · ([O1-Pruner](https://github.com/StarDewXXX/O1-Pruner) - StarDewXXX) ![Star](https://img.shields.io/github/stars/StarDewXXX/O1-Pruner.svg?style=social&label=Star)
- [DeepSeek R1's recipe to replicate o1 and the future of reasoning LMs](https://www.interconnects.ai/p/deepseek-r1-recipe-for-o1) 
- 🌟 [Meta Chain-of-Thought: Unlocking System 2 Reasoning in LLMs](https://www.synthlabs.ai/) 

	 · ([𝕏](https://x.com/synth_labs/status/1879277225977209113))
- **O1 Replication Journey -- Part 3: Inference-time Scaling for Medical 
  Reasoning**, `arXiv, 2501.06458`, [arxiv](http://arxiv.org/abs/2501.06458v1), [pdf](http://arxiv.org/pdf/2501.06458v1.pdf), cication: [**-1**](None) 

	 *Zhongzhen Huang, Gui Geng, Shengyi Hua, ..., Pengfei Liu, Xiaofan Zhang*
- 🌟 [**DeepSeek-R1**](https://github.com/deepseek-ai/DeepSeek-R1) - deepseek-ai ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-R1.svg?style=social&label=Star) 
- [**Kimi-k1.5**](https://github.com/MoonshotAI/Kimi-k1.5) - MoonshotAI ![Star](https://img.shields.io/github/stars/MoonshotAI/Kimi-k1.5.svg?style=social&label=Star) 

	 *Scaling Reinforcement Learning with LLMs*
- 🌟 [Sky-T1: Train your own O1 preview model within $450](https://novasky-ai.github.io/posts/sky-t1/) 

	 · ([SkyThought](https://github.com/NovaSky-AI/SkyThought) - NovaSky-AI) ![Star](https://img.shields.io/github/stars/NovaSky-AI/SkyThought.svg?style=social&label=Star)
- 🌟 **rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep 
  Thinking**, `arXiv, 2501.04519`, [arxiv](http://arxiv.org/abs/2501.04519v1), [pdf](http://arxiv.org/pdf/2501.04519v1.pdf), cication: [**-1**](None) 

	 *Xinyu Guan, Li Lyna Zhang, Yifei Liu, ..., Fan Yang, Mao Yang* · ([rStar](https://github.com/microsoft/rStar) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/rStar.svg?style=social&label=Star)
- 🌟 **Towards System 2 Reasoning in LLMs: Learning How to Think With Meta 
  Chain-of-Thought**, `arXiv, 2501.04682`, [arxiv](http://arxiv.org/abs/2501.04682v1), [pdf](http://arxiv.org/pdf/2501.04682v1.pdf), cication: [**-1**](None) 

	 *Violet Xiang, Charlie Snell, Kanishk Gandhi, ..., Nick Haber, Chelsea Finn*
- **PRMBench: A Fine-grained and Challenging Benchmark for Process-Level 
  Reward Models**, `arXiv, 2501.03124`, [arxiv](http://arxiv.org/abs/2501.03124v2), [pdf](http://arxiv.org/pdf/2501.03124v2.pdf), cication: [**-1**](None) 

	 *Mingyang Song, Zhaochen Su, Xiaoye Qu, ..., Jiawei Zhou, Yu Cheng* · ([prmbench.github](https://prmbench.github.io/)) · ([PRMBench](https://github.com/ssmisya/PRMBench) - ssmisya) ![Star](https://img.shields.io/github/stars/ssmisya/PRMBench.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/abs/2501.03124)) · ([huggingface](https://huggingface.co/datasets/hitsmy/PRMBench_Preview))
- **Dolphin: Closed-loop Open-ended Auto-research through Thinking, 
  Practice, and Feedback**, `arXiv, 2501.03916`, [arxiv](http://arxiv.org/abs/2501.03916v1), [pdf](http://arxiv.org/pdf/2501.03916v1.pdf), cication: [**-1**](None) 

	 *Jiakang Yuan, Xiangchao Yan, Botian Shi, ..., Yu Qiao, Bowen Zhou*
- **Search-o1: Agentic Search-Enhanced Large Reasoning Models**, `arXiv, 2501.05366`, [arxiv](http://arxiv.org/abs/2501.05366v1), [pdf](http://arxiv.org/pdf/2501.05366v1.pdf), cication: [**-1**](None) 

	 *Xiaoxi Li, Guanting Dong, Jiajie Jin, ..., Peitian Zhang, Zhicheng Dou* · ([Search-o1](https://github.com/sunnynexus/Search-o1) - sunnynexus) ![Star](https://img.shields.io/github/stars/sunnynexus/Search-o1.svg?style=social&label=Star)
- **Inference-Aware Fine-Tuning for Best-of-N Sampling in Large Language 
  Models**, `arXiv, 2412.15287`, [arxiv](http://arxiv.org/abs/2412.15287v1), [pdf](http://arxiv.org/pdf/2412.15287v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=10740790454342887028&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Yinlam Chow, Guy Tennenholtz, Izzeddin Gur, ..., Aviral Kumar, Aleksandra Faust* · ([𝕏](https://x.com/papers_anon/status/1871202582045356159))
- **Do NOT Think That Much for 2+3=? On the Overthinking of o1-Like LLMs**, `arXiv, 2412.21187`, [arxiv](http://arxiv.org/abs/2412.21187v1), [pdf](http://arxiv.org/pdf/2412.21187v1.pdf), cication: [**-1**](None) 

	 *Xingyu Chen, Jiahao Xu, Tian Liang, ..., Haitao Mi, Dong Yu*
- [Reasoning with o1](https://www.deeplearning.ai/short-courses/reasoning-with-o1/) 
- [Reasoning with o1](https://www.bilibili.com/video/BV1M1kCYnETm/)  :clapper: 
- [**PRIME**](https://github.com/PRIME-RL/PRIME) - PRIME-RL ![Star](https://img.shields.io/github/stars/PRIME-RL/PRIME.svg?style=social&label=Star) 

	 · ([curvy-check-498.notion](https://curvy-check-498.notion.site/Process-Reinforcement-through-Implicit-Rewards-15f4fcb9c42180f1b498cc9b2eaf896f)) · ([𝕏](https://x.com/lifan__yuan/status/1874867809983033649))
- [SmallThinker-3B-preview, a new model fine-tuned from the Qwen2.5-3b-Instruct model.](https://huggingface.co/PowerInfer/SmallThinker-3B-Preview)  🤗 
- [distill its thinking capacities into a smaller model, enhancing their reasoning performances](https://x.com/ADarmouni/status/1871257176733556849)  𝕏 

	 · ([t](https://t.co/i9FfvkTEg1))
- **OpenAI o1 System Card**, `arXiv, 2412.16720`, [arxiv](http://arxiv.org/abs/2412.16720v1), [pdf](http://arxiv.org/pdf/2412.16720v1.pdf), cication: [**-1**](None) 

	 *OpenAI, :, Aaron Jaech, ..., Zheng Shao, Zhuohan Li*
- **Imitate, Explore, and Self-Improve: A Reproduction Report on 
  Slow-thinking Reasoning Systems**, `arXiv, 2412.09413`, [arxiv](http://arxiv.org/abs/2412.09413v2), [pdf](http://arxiv.org/pdf/2412.09413v2.pdf), cication: [**-1**](None) 

	 *Yingqian Min, Zhipeng Chen, Jinhao Jiang, ..., Zhongyuan Wang, Ji-Rong Wen* · ([Slow_Thinking_with_LLMs](https://github.com/RUCAIBox/Slow_Thinking_with_LLMs?tab=readme-ov-file) - RUCAIBox) ![Star](https://img.shields.io/github/stars/RUCAIBox/Slow_Thinking_with_LLMs.svg?style=social&label=Star)
- 🌟 [**search-and-learn**](https://github.com/huggingface/search-and-learn) - huggingface ![Star](https://img.shields.io/github/stars/huggingface/search-and-learn.svg?style=social&label=Star) 

	 · ([huggingface](https://huggingface.co/spaces/HuggingFaceH4/blogpost-scaling-test-time-compute)) · ([𝕏](https://x.com/_lewtun/status/1868703456602865880))
- [Beyond Decoding: Meta-Generation Algorithms for Large Language Models](https://cmu-l3.github.io/neurips2024-inference-tutorial/) 

	 · ([cmu-l3.github](https://cmu-l3.github.io/neurips2024-inference-tutorial/static/slides/neurips2024metageneration-tutorial-all.pdf))
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

- **ProgCo: Program Helps Self-Correction of Large Language Models**, `arXiv, 2501.01264`, [arxiv](http://arxiv.org/abs/2501.01264v1), [pdf](http://arxiv.org/pdf/2501.01264v1.pdf), cication: [**-1**](None) 

	 *Xiaoshuai Song, Yanan Wu, Weixun Wang, ..., Wenbo Su, Bo Zheng*

## Knowledge


## Context Learning

- 🌟 **Explanatory Instructions: Towards Unified Vision Tasks Understanding and 
  Zero-shot Generalization**, `arXiv, 2412.18525`, [arxiv](http://arxiv.org/abs/2412.18525v2), [pdf](http://arxiv.org/pdf/2412.18525v2.pdf), cication: [**-1**](None) 

	 *Yang Shen, Xiu-Shen Wei, Yifan Sun, ..., Yazhou Yao, Errui Ding*
- **The broader spectrum of in-context learning**, `arXiv, 2412.03782`, [arxiv](http://arxiv.org/abs/2412.03782v2), [pdf](http://arxiv.org/pdf/2412.03782v2.pdf), cication: [**-1**](None) 

	 *Andrew Kyle Lampinen, Stephanie C. Y. Chan, Aaditya K. Singh, ..., Murray Shanahan* · ([𝕏](https://x.com/AndrewLampinen/status/1866546723210011077))

## Chain Of Thought

- 🌟 **Demystifying Long Chain-of-Thought Reasoning in LLMs**, `arXiv, 2502.03373`, [arxiv](http://arxiv.org/abs/2502.03373v1), [pdf](http://arxiv.org/pdf/2502.03373v1.pdf), cication: [**-1**](None) 

	 *Edward Yeo, Yuxuan Tong, Morry Niu, ..., Graham Neubig, Xiang Yue* · ([𝕏](https://x.com/xiangyue96/status/1887332772198371514)) · ([demystify-long-cot](https://github.com/eddycmu/demystify-long-cot) - eddycmu) ![Star](https://img.shields.io/github/stars/eddycmu/demystify-long-cot.svg?style=social&label=Star)
- **Can We Generate Images with CoT? Let's Verify and Reinforce Image 
  Generation Step by Step**, `arXiv, 2501.13926`, [arxiv](http://arxiv.org/abs/2501.13926v1), [pdf](http://arxiv.org/pdf/2501.13926v1.pdf), cication: [**-1**](None) 

	 *Ziyu Guo, Renrui Zhang, Chengzhuo Tong, ..., Hongsheng Li, Pheng-Ann Heng* · ([Image-Generation-CoT](https://github.com/ZiyuGuo99/Image-Generation-CoT) - ZiyuGuo99) ![Star](https://img.shields.io/github/stars/ZiyuGuo99/Image-Generation-CoT.svg?style=social&label=Star)
- **Audio-CoT: Exploring Chain-of-Thought Reasoning in Large Audio Language 
  Model**, `arXiv, 2501.07246`, [arxiv](http://arxiv.org/abs/2501.07246v1), [pdf](http://arxiv.org/pdf/2501.07246v1.pdf), cication: [**-1**](None) 

	 *Ziyang Ma, Zhuo Chen, Yuping Wang, ..., Eng Siong Chng, Xie Chen*
- **To CoT or not to CoT? Chain-of-thought helps mainly on math and symbolic 
  reasoning**, `arXiv, 2409.12183`, [arxiv](http://arxiv.org/abs/2409.12183v2), [pdf](http://arxiv.org/pdf/2409.12183v2.pdf), cication: [**24**](https://scholar.google.com/scholar?cites=15167469291991704150&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Zayne Sprague, Fangcong Yin, Juan Diego Rodriguez, ..., Kyle Mahowald, Greg Durrett* · ([To-CoT-or-not-to-CoT](https://github.com/Zayne-sprague/To-CoT-or-not-to-CoT) - Zayne-sprague) ![Star](https://img.shields.io/github/stars/Zayne-sprague/To-CoT-or-not-to-CoT.svg?style=social&label=Star) · ([𝕏](https://x.com/_jasonwei/status/1875268874859344349))
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

- [**open-thoughts**](https://github.com/open-thoughts/open-thoughts) - open-thoughts ![Star](https://img.shields.io/github/stars/open-thoughts/open-thoughts.svg?style=social&label=Star) 

	 · ([𝕏](https://x.com/madiator/status/1884284103354376283))
- [**Open-Reasoning-Tasks**](https://github.com/NousResearch/Open-Reasoning-Tasks) - NousResearch ![Star](https://img.shields.io/github/stars/NousResearch/Open-Reasoning-Tasks.svg?style=social&label=Star) 
- [**prompt-poet**](https://github.com/character-ai/prompt-poet) - character-ai ![Star](https://img.shields.io/github/stars/character-ai/prompt-poet.svg?style=social&label=Star) 
- [**V0-system-prompt**](https://github.com/2-fly-4-ai/V0-system-prompt) - 2-fly-4-ai ![Star](https://img.shields.io/github/stars/2-fly-4-ai/V0-system-prompt.svg?style=social&label=Star) 

	 · ([reddit](https://www.reddit.com/r/LocalLLaMA/comments/1gwwyia/leaked_system_prompts_from_v0_vercels_ai/))
- [steiner-preview  updated			3 days ago Reasoning models trained on synthetic data using reinforcement learning.](https://huggingface.co/collections/peakji/steiner-preview-6712c6987110ce932a44e9a6)  🤗 

## Planning

- **Learning to Plan & Reason for Evaluation with Thinking-LLM-as-a-Judge**, `arXiv, 2501.18099`, [arxiv](http://arxiv.org/abs/2501.18099v1), [pdf](http://arxiv.org/pdf/2501.18099v1.pdf), cication: [**-1**](None) 

	 *Swarnadeep Saha, Xian Li, Marjan Ghazvininejad, ..., Jason Weston, Tianlu Wang* · ([𝕏](https://x.com/jaseweston/status/1885153770662760472))
- **Dynamic Planning with a LLM**, `arXiv, 2308.06391`, [arxiv](http://arxiv.org/abs/2308.06391v1), [pdf](http://arxiv.org/pdf/2308.06391v1.pdf), cication: [**-1**](None) 

	 *Gautier Dagan, Frank Keller, Alex Lascarides*
- **On the Planning Abilities of Large Language Models (A Critical 
  Investigation with a Proposed Benchmark)**, `arXiv, 2302.06706`, [arxiv](http://arxiv.org/abs/2302.06706v1), [pdf](http://arxiv.org/pdf/2302.06706v1.pdf), cication: [**-1**](None) 

	 *Karthik Valmeekam, Sarath Sreedharan, Matthew Marquez, ..., Alberto Olmo, Subbarao Kambhampati*
- **Phenomenal Yet Puzzling: Testing Inductive Reasoning Capabilities of 
  Language Models with Hypothesis Refinement**, `arXiv, 2310.08559`, [arxiv](http://arxiv.org/abs/2310.08559v4), [pdf](http://arxiv.org/pdf/2310.08559v4.pdf), cication: [**-1**](None) 

	 *Linlu Qiu, Liwei Jiang, Ximing Lu, ..., Nouha Dziri, Xiang Ren*
- **Revealing the Barriers of Language Agents in Planning**, `arXiv, 2410.12409`, [arxiv](http://arxiv.org/abs/2410.12409v1), [pdf](http://arxiv.org/pdf/2410.12409v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=3286664752846199&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Jian Xie, Kexun Zhang, Jiangjie Chen, ..., Lei Li, Yanghua Xiao*

	 *Jian Xie, Kexun Zhang, Jiangjie Chen, ..., Lei Li, Yanghua Xiao*

## Misc

- [Denny Zhou: LLM Reasoning: Key Ideas and Limitations](https://www.youtube.com/watch?v=-SZAciVbswk)  :clapper: 
- [Jason Wei: Scaling Paradigms for Large Language Models](https://www.youtube.com/watch?v=yhpjpNXJDco)  :clapper: 
- [智谱版o1终于也来了：直接拿下考研数学，一句话就能做小游戏！](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247770241&idx=1&sn=fd6fb22d91ca671905f8ff8a338f7662&chksm=e9ba73fe67399d9a51136457259305a5005bcc02ee12913d9c33515743e7668528772b93fe50&scene=0&xtrack=1) 
- [Quick recap on the state of reasoning -- can LMs reason?](https://x.com/interconnectsai/status/1874850900352840129)  𝕏 

	 · ([youtube](https://www.youtube.com/watch?v=2pHE9L4ZZXM&ab_channel=InterconnectsAI))
- [【北大对齐团队独家解读：OpenAI o1开启「后训练」时代强化学习新范式】](https://www.bilibili.com/list/watchlater?oid=113201647719044&bvid=BV15Rx5eXEnW)  :clapper: 
- [The Problem with Reasoners](https://aidanmclaughlin.notion.site/reasoners-problem) 