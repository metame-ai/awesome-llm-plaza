# Awesome llm reasoning

- [Awesome llm reasoning](#awesome-llm-reasoning)
	- [Survey](#survey)
	- [Reasoning](#reasoning)
		- [Other](#other)
	- [Math reasoning](#math-reasoning)
		- [Benchmarks](#benchmarks)
		- [Other](#other-1)
	- [Self correction](#self-correction)
	- [Prompting](#prompting)
		- [Other](#other-2)
	- [In context learning](#in-context-learning)
		- [Other](#other-3)
	- [Knowledge graph](#knowledge-graph)
		- [Other](#other-4)
	- [Tutorials](#tutorials)
	- [Extra reference](#extra-reference)


## Survey
- **Internal Consistency and Self-Feedback in Large Language Models: A
  Survey**, `arXiv, 2407.14507`, [arxiv](http://arxiv.org/abs/2407.14507v1), [pdf](http://arxiv.org/pdf/2407.14507v1.pdf), cication: [**-1**](None)

	 *Xun Liang, Shichao Song, Zifan Zheng, Hanyu Wang, Qingchen Yu, Xunkai Li, Rong-Hua Li, Feiyu Xiong, Zhiyu Li* · ([ICSFSurvey](https://github.com/IAAR-Shanghai/ICSFSurvey) - IAAR-Shanghai) ![Star](https://img.shields.io/github/stars/IAAR-Shanghai/ICSFSurvey.svg?style=social&label=Star) · ([yuque](https://www.yuque.com/zhiyu-n2wnm/ugzwgf/gmqfkfigd6xw26eg))

	 · ([x](https://x.com/Ki_Seki_here/status/1836020241538908529))
- **The Prompt Report: A Systematic Survey of Prompting Techniques**, `arXiv, 2406.06608`, [arxiv](http://arxiv.org/abs/2406.06608v1), [pdf](http://arxiv.org/pdf/2406.06608v1.pdf), cication: [**-1**](None)

	 *Sander Schulhoff, Michael Ilie, Nishant Balepur, Konstantine Kahadze, Amanda Liu, Chenglei Si, Yinheng Li, Aayush Gupta, HyoJung Han, Sevien Schulhoff*
- **Efficient Prompting Methods for Large Language Models: A Survey**, `arXiv, 2404.01077`, [arxiv](http://arxiv.org/abs/2404.01077v1), [pdf](http://arxiv.org/pdf/2404.01077v1.pdf), cication: [**-1**](None)

	 *Kaiyan Chang, Songcheng Xu, Chenglong Wang, Yingfeng Luo, Tong Xiao, Jingbo Zhu*
- **A Survey of Reasoning with Foundation Models: Concepts, Methodologies,
  and Outlook**, `arXiv, 2312.11562`, [arxiv](http://arxiv.org/abs/2312.11562v3), [pdf](http://arxiv.org/pdf/2312.11562v3.pdf), cication: [**-1**](None)

	 *Jiankai Sun, Chuanyang Zheng, Enze Xie, Zhengying Liu, Ruihang Chu, Jianing Qiu, Jiaqi Xu, Mingyu Ding, Hongyang Li, Mengzhe Geng* · ([Awesome-Reasoning-Foundation-Models](https://github.com/reasoning-survey/Awesome-Reasoning-Foundation-Models) - reasoning-survey) ![Star](https://img.shields.io/github/stars/reasoning-survey/Awesome-Reasoning-Foundation-Models.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652421688&idx=3&sn=fcdc24edc7bc89ebcbcca0f7665e40f6))

## O1-Reasoning
- **Thinking LLMs: General Instruction Following with Thought Generation**, `arXiv, 2410.10630`, [arxiv](http://arxiv.org/abs/2410.10630v1), [pdf](http://arxiv.org/pdf/2410.10630v1.pdf), cication: [**-1**](None)

	 *Tianhao Wu, Janice Lan, Weizhe Yuan, Jiantao Jiao, Jason Weston, Sainbayar Sukhbaatar*
- **Dualformer: Controllable Fast and Slow Thinking by Learning with
  Randomized Reasoning Traces**, `arXiv, 2410.09918`, [arxiv](http://arxiv.org/abs/2410.09918v1), [pdf](http://arxiv.org/pdf/2410.09918v1.pdf), cication: [**-1**](None)

	 *DiJia Su, Sainbayar Sukhbaatar, Michael Rabbat, Yuandong Tian, Qinqing Zheng*
- [**awesome-o1**](https://github.com/srush/awesome-o1/) - srush ![Star](https://img.shields.io/github/stars/srush/awesome-o1.svg?style=social&label=Star)
- **Inference Scaling for Long-Context Retrieval Augmented Generation**, `arXiv, 2410.04343`, [arxiv](http://arxiv.org/abs/2410.04343v1), [pdf](http://arxiv.org/pdf/2410.04343v1.pdf), cication: [**-1**](None)

	 *Zhenrui Yue, Honglei Zhuang, Aijun Bai, Kai Hui, Rolf Jagerman, Hansi Zeng, Zhen Qin, Dong Wang, Xuanhui Wang, Michael Bendersky*
- [**openr**](https://github.com/openreasoner/openr/blob/main/reports/Tutorial-LLM-Reasoning-Wang.pdf) - openreasoner ![Star](https://img.shields.io/github/stars/openreasoner/openr.svg?style=social&label=Star)
- [**O1-Journey**](https://github.com/GAIR-NLP/O1-Journey) - GAIR-NLP ![Star](https://img.shields.io/github/stars/GAIR-NLP/O1-Journey.svg?style=social&label=Star)

	 *O1 Replication Journey: A Strategic Progress Report – Part I* · ([O1-Journey](https://github.com/GAIR-NLP/O1-Journey/blob/main/resource/report.pdf) - GAIR-NLP) ![Star](https://img.shields.io/github/stars/GAIR-NLP/O1-Journey.svg?style=social&label=Star) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-10-09-3))
- **Rewarding Progress: Scaling Automated Process Verifiers for LLM
  Reasoning**, `arXiv, 2410.08146`, [arxiv](http://arxiv.org/abs/2410.08146v1), [pdf](http://arxiv.org/pdf/2410.08146v1.pdf), cication: [**-1**](None)

	 *Amrith Setlur, Chirag Nagpal, Adam Fisch, Xinyang Geng, Jacob Eisenstein, Rishabh Agarwal, Alekh Agarwal, Jonathan Berant, Aviral Kumar*
- **LLMs Still Can't Plan; Can LRMs? A Preliminary Evaluation of OpenAI's o1
  on PlanBench**, `arXiv, 2409.13373`, [arxiv](http://arxiv.org/abs/2409.13373v1), [pdf](http://arxiv.org/pdf/2409.13373v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=13149528520885859987&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Karthik Valmeekam, Kaya Stechly, Subbarao Kambhampati*
- **Training Language Models to Self-Correct via Reinforcement Learning**, `arXiv, 2409.12917`, [arxiv](http://arxiv.org/abs/2409.12917v2), [pdf](http://arxiv.org/pdf/2409.12917v2.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=2657384453197838851&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Aviral Kumar, Vincent Zhuang, Rishabh Agarwal, Yi Su, John D Co-Reyes, Avi Singh, Kate Baumli, Shariq Iqbal, Colton Bishop, Rebecca Roelofs*
- [**g1**](https://github.com/bklieger-groq/g1) - bklieger-groq ![Star](https://img.shields.io/github/stars/bklieger-groq/g1.svg?style=social&label=Star)

	 *g1: Using Llama-3.1 70b on Groq to create o1-like reasoning chains*
- **Chain of Thought Empowers Transformers to Solve Inherently Serial
  Problems**, `arXiv, 2402.12875`, [arxiv](http://arxiv.org/abs/2402.12875v4), [pdf](http://arxiv.org/pdf/2402.12875v4.pdf), cication: [**24**](https://scholar.google.com/scholar?cites=11728270641767049962&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhiyuan Li, Hong Liu, Denny Zhou, Tengyu Ma*
- [Improving LLM Reasoning using SElf-generated data: RL and Verifiers](https://drive.google.com/file/d/1komQ7s9kPPvDx_8AxTh9A6tlfJA0j6dR/view)
- [**Awesome-LLM-Strawberry**](https://github.com/hijkzzz/Awesome-LLM-Strawberry) - hijkzzz ![Star](https://img.shields.io/github/stars/hijkzzz/Awesome-LLM-Strawberry.svg?style=social&label=Star)

	 *A collection of LLM papers, blogs, and projects, with a focus on OpenAI o1 and reasoning techniques.* · ([mp.weixin.qq](https://mp.weixin.qq.com/s/sPYeM5LbfAwyHUxbQ78Vsg))
- **Scaling LLM Test-Time Compute Optimally can be More Effective than
  Scaling Model Parameters**, `arXiv, 2408.03314`, [arxiv](http://arxiv.org/abs/2408.03314v1), [pdf](http://arxiv.org/pdf/2408.03314v1.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=10282131377233540155&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Charlie Snell, Jaehoon Lee, Kelvin Xu, Aviral Kumar*
- **Alphazero-like Tree-Search can Guide Large Language Model Decoding and
  Training**, `arXiv, 2309.17179`, [arxiv](http://arxiv.org/abs/2309.17179v2), [pdf](http://arxiv.org/pdf/2309.17179v2.pdf), cication: [**29**](https://scholar.google.com/scholar?cites=12391024127440976227&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xidong Feng, Ziyu Wan, Muning Wen, Stephen Marcus McAleer, Ying Wen, Weinan Zhang, Jun Wang*
- **Large Language Monkeys: Scaling Inference Compute with Repeated Sampling**, `arXiv, 2407.21787`, [arxiv](http://arxiv.org/abs/2407.21787v1), [pdf](http://arxiv.org/pdf/2407.21787v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=5658336227944123944&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Bradley Brown, Jordan Juravsky, Ryan Ehrlich, Ronald Clark, Quoc V. Le, Christopher Ré, Azalia Mirhoseini*
- **Quiet-STaR: Language Models Can Teach Themselves to Think Before
  Speaking**, `arXiv, 2403.09629`, [arxiv](http://arxiv.org/abs/2403.09629v2), [pdf](http://arxiv.org/pdf/2403.09629v2.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=14769685511035391680&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Eric Zelikman, Georges Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah D. Goodman*
- **Let's Verify Step by Step**, `arXiv, 2305.20050`, [arxiv](http://arxiv.org/abs/2305.20050v1), [pdf](http://arxiv.org/pdf/2305.20050v1.pdf), cication: [**294**](https://scholar.google.com/scholar?cites=3594089577812846684&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hunter Lightman, Vineet Kosaraju, Yura Burda, Harri Edwards, Bowen Baker, Teddy Lee, Jan Leike, John Schulman, Ilya Sutskever, Karl Cobbe*

**Other**
- [**o1**](https://huggingface.co/spaces/yuntian-deng/o1) - yuntian-deng 🤗
- [**o1mini**](https://huggingface.co/spaces/yuntian-deng/o1mini) - yuntian-deng 🤗
## Reasoning
- **RATIONALYST: Pre-training Process-Supervision for Improving Reasoning**, `arXiv, 2410.01044`, [arxiv](http://arxiv.org/abs/2410.01044v1), [pdf](http://arxiv.org/pdf/2410.01044v1.pdf), cication: [**-1**](None)

	 *Dongwei Jiang, Guoxuan Wang, Yining Lu, Andrew Wang, Jingyu Zhang, Chuyu Liu, Benjamin Van Durme, Daniel Khashabi*
- **Iteration of Thought: Leveraging Inner Dialogue for Autonomous Large
  Language Model Reasoning**, `arXiv, 2409.12618`, [arxiv](http://arxiv.org/abs/2409.12618v2), [pdf](http://arxiv.org/pdf/2409.12618v2.pdf), cication: [**-1**](None)

	 *Santosh Kumar Radha, Yasamin Nouri Jelyani, Ara Ghukasyan, Oktay Goktas*
- [LLM-Reasoning-Berkeley.pdf](https://dennyzhou.github.io/LLM-Reasoning-Berkeley.pdf)
- **To CoT or not to CoT? Chain-of-thought helps mainly on math and symbolic
  reasoning**, `arXiv, 2409.12183`, [arxiv](http://arxiv.org/abs/2409.12183v1), [pdf](http://arxiv.org/pdf/2409.12183v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=15167469291991704150&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zayne Sprague, Fangcong Yin, Juan Diego Rodriguez, Dongwei Jiang, Manya Wadhwa, Prasann Singhal, Xinyu Zhao, Xi Ye, Kyle Mahowald, Greg Durrett*
- **Mutual Reasoning Makes Smaller LLMs Stronger Problem-Solvers**, `arXiv, 2408.06195`, [arxiv](http://arxiv.org/abs/2408.06195v1), [pdf](http://arxiv.org/pdf/2408.06195v1.pdf), cication: [**-1**](None)

	 *Zhenting Qi, Mingyuan Ma, Jiahang Xu, Li Lyna Zhang, Fan Yang, Mao Yang* · ([rStar](https://github.com/zhentingqi/rStar) - zhentingqi) ![Star](https://img.shields.io/github/stars/zhentingqi/rStar.svg?style=social&label=Star)
- **CoverBench: A Challenging Benchmark for Complex Claim Verification**, `arXiv, 2408.03325`, [arxiv](http://arxiv.org/abs/2408.03325v1), [pdf](http://arxiv.org/pdf/2408.03325v1.pdf), cication: [**-1**](None)

	 *Alon Jacovi, Moran Ambar, Eyal Ben-David, Uri Shaham, Amir Feder, Mor Geva, Dror Marcus, Avi Caciularu* · ([huggingface](https://huggingface.co/datasets/google/coverbench))
- **Self-Training with Direct Preference Optimization Improves
  Chain-of-Thought Reasoning**, `arXiv, 2407.18248`, [arxiv](http://arxiv.org/abs/2407.18248v1), [pdf](http://arxiv.org/pdf/2407.18248v1.pdf), cication: [**-1**](None)

	 *Tianduo Wang, Shichen Li, Wei Lu* · ([DPO-ST](https://github.com/TianduoWang/DPO-ST) - TianduoWang) ![Star](https://img.shields.io/github/stars/TianduoWang/DPO-ST.svg?style=social&label=Star)
- **Q*: Improving Multi-step Reasoning for LLMs with Deliberative Planning**, `arXiv, 2406.14283`, [arxiv](http://arxiv.org/abs/2406.14283v2), [pdf](http://arxiv.org/pdf/2406.14283v2.pdf), cication: [**-1**](None)

	 *Chaojie Wang, Yanchen Deng, Zhiyi Lv, Shuicheng Yan, An Bo*
- **Transformers meet Neural Algorithmic Reasoners**, `arXiv, 2406.09308`, [arxiv](http://arxiv.org/abs/2406.09308v1), [pdf](http://arxiv.org/pdf/2406.09308v1.pdf), cication: [**-1**](None)

	 *Wilfried Bounsi, Borja Ibarz, Andrew Dudzik, Jessica B. Hamrick, Larisa Markeeva, Alex Vitvitskyi, Razvan Pascanu, Petar Veličković*
- **TextGrad: Automatic "Differentiation" via Text**, `arXiv, 2406.07496`, [arxiv](http://arxiv.org/abs/2406.07496v1), [pdf](http://arxiv.org/pdf/2406.07496v1.pdf), cication: [**-1**](None)

	 *Mert Yuksekgonul, Federico Bianchi, Joseph Boen, Sheng Liu, Zhi Huang, Carlos Guestrin, James Zou* · ([textgrad](https://github.com/zou-group/textgrad) - zou-group) ![Star](https://img.shields.io/github/stars/zou-group/textgrad.svg?style=social&label=Star)
- **Husky: A Unified, Open-Source Language Agent for Multi-Step Reasoning**, `arXiv, 2406.06469`, [arxiv](http://arxiv.org/abs/2406.06469v1), [pdf](http://arxiv.org/pdf/2406.06469v1.pdf), cication: [**-1**](None)

	 *Joongwon Kim, Bhargavi Paranjape, Tushar Khot, Hannaneh Hajishirzi* · ([Husky-v1](https://github.com/agent-husky/Husky-v1) - agent-husky) ![Star](https://img.shields.io/github/stars/agent-husky/Husky-v1.svg?style=social&label=Star)
- **Buffer of Thoughts: Thought-Augmented Reasoning with Large Language
  Models**, `arXiv, 2406.04271`, [arxiv](http://arxiv.org/abs/2406.04271v1), [pdf](http://arxiv.org/pdf/2406.04271v1.pdf), cication: [**-1**](None)

	 *Ling Yang, Zhaochen Yu, Tianjun Zhang, Shiyi Cao, Minkai Xu, Wentao Zhang, Joseph E. Gonzalez, Bin Cui*

	 · ([buffer-of-thought-llm](https://github.com/YangLing0818/buffer-of-thought-llm) - YangLing0818) ![Star](https://img.shields.io/github/stars/YangLing0818/buffer-of-thought-llm.svg?style=social&label=Star)
- **LLMs achieve adult human performance on higher-order theory of mind
  tasks**, `arXiv, 2405.18870`, [arxiv](http://arxiv.org/abs/2405.18870v2), [pdf](http://arxiv.org/pdf/2405.18870v2.pdf), cication: [**-1**](None)

	 *Winnie Street, John Oliver Siy, Geoff Keeling, Adrien Baranes, Benjamin Barnett, Michael McKibben, Tatenda Kanyere, Alison Lentz, Blaise Aguera y Arcas, Robin I. M. Dunbar*
- **Grokked Transformers are Implicit Reasoners: A Mechanistic Journey to
  the Edge of Generalization**, `arXiv, 2405.15071`, [arxiv](http://arxiv.org/abs/2405.15071v1), [pdf](http://arxiv.org/pdf/2405.15071v1.pdf), cication: [**-1**](None)

	 *Boshi Wang, Xiang Yue, Yu Su, Huan Sun*
- **ALPINE: Unveiling the Planning Capability of Autoregressive Learning in
  Language Models**, `arXiv, 2405.09220`, [arxiv](http://arxiv.org/abs/2405.09220v1), [pdf](http://arxiv.org/pdf/2405.09220v1.pdf), cication: [**-1**](None)

	 *Siwei Wang, Yifei Shen, Shi Feng, Haoran Sun, Shang-Hua Teng, Wei Chen*
- **MAmmoTH2: Scaling Instructions from the Web**, `arXiv, 2405.03548`, [arxiv](http://arxiv.org/abs/2405.03548v1), [pdf](http://arxiv.org/pdf/2405.03548v1.pdf), cication: [**-1**](None)

	 *Xiang Yue, Tuney Zheng, Ge Zhang, Wenhu Chen* · ([tiger-ai-lab.github](https://tiger-ai-lab.github.io/MAmmoTH2/)) · ([MAmmoTH2](https://github.com/TIGER-AI-Lab/MAmmoTH2) - TIGER-AI-Lab) ![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/MAmmoTH2.svg?style=social&label=Star)
- **Toward Self-Improvement of LLMs via Imagination, Searching, and
  Criticizing**, `arXiv, 2404.12253`, [arxiv](http://arxiv.org/abs/2404.12253v1), [pdf](http://arxiv.org/pdf/2404.12253v1.pdf), cication: [**-1**](None)

	 *Ye Tian, Baolin Peng, Linfeng Song, Lifeng Jin, Dian Yu, Haitao Mi, Dong Yu*
- **Ferret-v2: An Improved Baseline for Referring and Grounding with Large
  Language Models**, `arXiv, 2404.07973`, [arxiv](http://arxiv.org/abs/2404.07973v1), [pdf](http://arxiv.org/pdf/2404.07973v1.pdf), cication: [**-1**](None)

	 *Haotian Zhang, Haoxuan You, Philipp Dufter, Bowen Zhang, Chen Chen, Hong-You Chen, Tsu-Jui Fu, William Yang Wang, Shih-Fu Chang, Zhe Gan*
- **Can Small Language Models Help Large Language Models Reason Better?:
  LM-Guided Chain-of-Thought**, `arXiv, 2404.03414`, [arxiv](http://arxiv.org/abs/2404.03414v1), [pdf](http://arxiv.org/pdf/2404.03414v1.pdf), cication: [**-1**](None)

	 *Jooyoung Lee, Fan Yang, Thanh Tran, Qian Hu, Emre Barut, Kai-Wei Chang, Chengwei Su*
- **SELF-[IN]CORRECT: LLMs Struggle with Refining Self-Generated Responses**, `arXiv, 2404.04298`, [arxiv](http://arxiv.org/abs/2404.04298v1), [pdf](http://arxiv.org/pdf/2404.04298v1.pdf), cication: [**-1**](None)

	 *Dongwei Jiang, Jingyu Zhang, Orion Weller, Nathaniel Weir, Benjamin Van Durme, Daniel Khashabi*
- **RoT: Enhancing Large Language Models with Reflection on Search Trees**, `arXiv, 2404.05449`, [arxiv](http://arxiv.org/abs/2404.05449v1), [pdf](http://arxiv.org/pdf/2404.05449v1.pdf), cication: [**-1**](None)

	 *Wenyang Hui, Yan Wang, Kewei Tu, Chengyue Jiang*
- **THOUGHTSCULPT: Reasoning with Intermediate Revision and Search**, `arXiv, 2404.05966`, [arxiv](http://arxiv.org/abs/2404.05966v1), [pdf](http://arxiv.org/pdf/2404.05966v1.pdf), cication: [**-1**](None)

	 *Yizhou Chi, Kevin Yang, Dan Klein* · ([thoughtsculpt](https://github.com/cyzus/thoughtsculpt) - cyzus) ![Star](https://img.shields.io/github/stars/cyzus/thoughtsculpt.svg?style=social&label=Star)
- **Visualization-of-Thought Elicits Spatial Reasoning in Large Language
  Models**, `arXiv, 2404.03622`, [arxiv](http://arxiv.org/abs/2404.03622v1), [pdf](http://arxiv.org/pdf/2404.03622v1.pdf), cication: [**-1**](None)

	 *Wenshan Wu, Shaoguang Mao, Yadong Zhang, Yan Xia, Li Dong, Lei Cui, Furu Wei*
	- `VoT enables LLMs to "visualize" their reasoning traces, creating internal mental images, that help to guide subsequent reasoning steps; when tested on multi-hop spatial reasoning tasks like visual tiling and visual navigation, VoT outperforms existing multimodal LLMs.`

	 · ([pywinassistant](https://github.com/a-real-ai/pywinassistant) - a-real-ai) ![Star](https://img.shields.io/github/stars/a-real-ai/pywinassistant.svg?style=social&label=Star)
- **Advancing LLM Reasoning Generalists with Preference Trees**, `arXiv, 2404.02078`, [arxiv](http://arxiv.org/abs/2404.02078v1), [pdf](http://arxiv.org/pdf/2404.02078v1.pdf), cication: [**-1**](None)

	 *Lifan Yuan, Ganqu Cui, Hanbin Wang, Ning Ding, Xingyao Wang, Jia Deng, Boji Shan, Huimin Chen, Ruobing Xie, Yankai Lin* · ([Eurus](https://github.com/OpenBMB/Eurus) - OpenBMB) ![Star](https://img.shields.io/github/stars/OpenBMB/Eurus.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/collections/openbmb/eurus-660bc40bec5376b3adc9d1c5))
	- ` Eurus-70B outperforms GPT-3.5 Turbo in reasoning largely due to a newly curated, high-quality alignment dataset designed for complex reasoning tasks; the data includes instructions with preference tree consisting of reasoning chains, multi-turn interactions and pairwise data for preference learning.`
- **ReALM: Reference Resolution As Language Modeling**, `arXiv, 2403.20329`, [arxiv](http://arxiv.org/abs/2403.20329v1), [pdf](http://arxiv.org/pdf/2403.20329v1.pdf), cication: [**-1**](None)

	 *Joel Ruben Antony Moniz, Soundarya Krishnan, Melis Ozyildirim, Prathamesh Saraf, Halim Cagri Ates, Yuan Zhang, Hong Yu, Nidhi Rajshree*
- **RankPrompt: Step-by-Step Comparisons Make Language Models Better
  Reasoners**, `arXiv, 2403.12373`, [arxiv](http://arxiv.org/abs/2403.12373v1), [pdf](http://arxiv.org/pdf/2403.12373v1.pdf), cication: [**-1**](None)

	 *Chi Hu, Yuan Ge, Xiangnan Ma, Hang Cao, Qiang Li, Yonghua Yang, Tong Xiao, Jingbo Zhu*
- **RAT: Retrieval Augmented Thoughts Elicit Context-Aware Reasoning in
  Long-Horizon Generation**, `arXiv, 2403.05313`, [arxiv](http://arxiv.org/abs/2403.05313v1), [pdf](http://arxiv.org/pdf/2403.05313v1.pdf), cication: [**-1**](None)

	 *Zihao Wang, Anji Liu, Haowei Lin, Jiaqi Li, Xiaojian Ma, Yitao Liang*

	 · ([craftjarvis.github](https://craftjarvis.github.io/RAT))
- **Quiet-STaR: Language Models Can Teach Themselves to Think Before
  Speaking**, `arXiv, 2403.09629`, [arxiv](http://arxiv.org/abs/2403.09629v1), [pdf](http://arxiv.org/pdf/2403.09629v1.pdf), cication: [**-1**](None)

	 *Eric Zelikman, Georges Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah D. Goodman*
- **Can Large Language Models Reason and Plan?**, `arXiv, 2403.04121`, [arxiv](http://arxiv.org/abs/2403.04121v1), [pdf](http://arxiv.org/pdf/2403.04121v1.pdf), cication: [**-1**](None)

	 *Subbarao Kambhampati*
- **Beyond Natural Language: LLMs Leveraging Alternative Formats for
  Enhanced Reasoning and Communication**, `arXiv, 2402.18439`, [arxiv](http://arxiv.org/abs/2402.18439v1), [pdf](http://arxiv.org/pdf/2402.18439v1.pdf), cication: [**-1**](None)

	 *Weize Chen, Chenfei Yuan, Jiarui Yuan, Yusheng Su, Chen Qian, Cheng Yang, Ruobing Xie, Zhiyuan Liu, Maosong Sun* · ([AutoForm](https://github.com/thunlp/AutoForm) - thunlp) ![Star](https://img.shields.io/github/stars/thunlp/AutoForm.svg?style=social&label=Star)
- **Do Large Language Models Latently Perform Multi-Hop Reasoning?**, `arXiv, 2402.16837`, [arxiv](http://arxiv.org/abs/2402.16837v1), [pdf](http://arxiv.org/pdf/2402.16837v1.pdf), cication: [**-1**](None)

	 *Sohee Yang, Elena Gribovskaya, Nora Kassner, Mor Geva, Sebastian Riedel*
- **Premise Order Matters in Reasoning with Large Language Models**, `arXiv, 2402.08939`, [arxiv](http://arxiv.org/abs/2402.08939v1), [pdf](http://arxiv.org/pdf/2402.08939v1.pdf), cication: [**-1**](None)

	 *Xinyun Chen, Ryan A. Chi, Xuezhi Wang, Denny Zhou* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652447872&idx=2&sn=183f861667efc607df5a7450e56f17e9))
- **Same Task, More Tokens: the Impact of Input Length on the Reasoning
  Performance of Large Language Models**, `arXiv, 2402.14848`, [arxiv](http://arxiv.org/abs/2402.14848v1), [pdf](http://arxiv.org/pdf/2402.14848v1.pdf), cication: [**-1**](None)

	 *Mosh Levy, Alon Jacoby, Yoav Goldberg*
- **When is Tree Search Useful for LLM Planning? It Depends on the
  Discriminator**, `arXiv, 2402.10890`, [arxiv](http://arxiv.org/abs/2402.10890v1), [pdf](http://arxiv.org/pdf/2402.10890v1.pdf), cication: [**-1**](None)

	 *Ziru Chen, Michael White, Raymond Mooney, Ali Payani, Yu Su, Huan Sun* · ([llm-planning-eval](https://github.com/OSU-NLP-Group/llm-planning-eval) - OSU-NLP-Group) ![Star](https://img.shields.io/github/stars/OSU-NLP-Group/llm-planning-eval.svg?style=social&label=Star)
- **Large Language Models as an Indirect Reasoner: Contrapositive and
  Contradiction for Automated Reasoning**, `arXiv, 2402.03667`, [arxiv](http://arxiv.org/abs/2402.03667v1), [pdf](http://arxiv.org/pdf/2402.03667v1.pdf), cication: [**-1**](None)

	 *Yanfang Zhang, Yiliu Sun, Yibing Zhan, Dapeng Tao, Dacheng Tao, Chen Gong*
- **GLoRe: When, Where, and How to Improve LLM Reasoning via Global and
  Local Refinements**, `arXiv, 2402.10963`, [arxiv](http://arxiv.org/abs/2402.10963v1), [pdf](http://arxiv.org/pdf/2402.10963v1.pdf), cication: [**-1**](None)

	 *Alex Havrilla, Sharath Raparthy, Christoforus Nalmpantis, Jane Dwivedi-Yu, Maksym Zhuravinskyi, Eric Hambro, Roberta Railneau*
- **Chain-of-Thought Reasoning Without Prompting**, `arXiv, 2402.10200`, [arxiv](http://arxiv.org/abs/2402.10200v1), [pdf](http://arxiv.org/pdf/2402.10200v1.pdf), cication: [**-1**](None)

	 *Xuezhi Wang, Denny Zhou*
- **Premise Order Matters in Reasoning with Large Language Models**, `arXiv, 2402.08939`, [arxiv](http://arxiv.org/abs/2402.08939v1), [pdf](http://arxiv.org/pdf/2402.08939v1.pdf), cication: [**-1**](None)

	 *Xinyun Chen, Ryan A. Chi, Xuezhi Wang, Denny Zhou*
- **Policy Improvement using Language Feedback Models**, `arXiv, 2402.07876`, [arxiv](http://arxiv.org/abs/2402.07876v2), [pdf](http://arxiv.org/pdf/2402.07876v2.pdf), cication: [**-1**](None)

	 *Victor Zhong, Dipendra Misra, Xingdi Yuan, Marc-Alexandre Côté*
- **CodeIt: Self-Improving Language Models with Prioritized Hindsight Replay**, `arXiv, 2402.04858`, [arxiv](http://arxiv.org/abs/2402.04858v1), [pdf](http://arxiv.org/pdf/2402.04858v1.pdf), cication: [**-1**](None)

	 *Natasha Butt, Blazej Manczak, Auke Wiggers, Corrado Rainone, David Zhang, Michaël Defferrard, Taco Cohen*
- **K-Level Reasoning with Large Language Models**, `arXiv, 2402.01521`, [arxiv](http://arxiv.org/abs/2402.01521v1), [pdf](http://arxiv.org/pdf/2402.01521v1.pdf), cication: [**-1**](None)

	 *Yadong Zhang, Shaoguang Mao, Tao Ge, Xun Wang, Yan Xia, Man Lan, Furu Wei*
- **Self-Discover: Large Language Models Self-Compose Reasoning Structures**, `arXiv, 2402.03620`, [arxiv](http://arxiv.org/abs/2402.03620v1), [pdf](http://arxiv.org/pdf/2402.03620v1.pdf), cication: [**-1**](None)

	 *Pei Zhou, Jay Pujara, Xiang Ren, Xinyun Chen, Heng-Tze Cheng, Quoc V. Le, Ed H. Chi, Denny Zhou, Swaroop Mishra, Huaixiu Steven Zheng*
- **CogGPT: Unleashing the Power of Cognitive Dynamics on Large Language
  Models**, `arXiv, 2401.08438`, [arxiv](http://arxiv.org/abs/2401.08438v1), [pdf](http://arxiv.org/pdf/2401.08438v1.pdf), cication: [**-1**](None)

	 *Yaojia Lv, Haojie Pan, Ruiji Fu, Ming Liu, Zhongyuan Wang, Bing Qin* · ([CogGPT](https://github.com/KwaiKEG/CogGPT) - KwaiKEG) ![Star](https://img.shields.io/github/stars/KwaiKEG/CogGPT.svg?style=social&label=Star)
- **The Impact of Reasoning Step Length on Large Language Models**, `arXiv, 2401.04925`, [arxiv](http://arxiv.org/abs/2401.04925v1), [pdf](http://arxiv.org/pdf/2401.04925v1.pdf), cication: [**-1**](None)

	 *Mingyu Jin, Qinkai Yu, Dong shu, Haiyan Zhao, Wenyue Hua, Yanda Meng, Yongfeng Zhang, Mengnan Du*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-01-25-7))
- **Reasons to Reject? Aligning Language Models with Judgments**, `arXiv, 2312.14591`, [arxiv](http://arxiv.org/abs/2312.14591v1), [pdf](http://arxiv.org/pdf/2312.14591v1.pdf), cication: [**-1**](None)

	 *Weiwen Xu, Deng Cai, Zhisong Zhang, Wai Lam, Shuming Shi*
- **The Truth is in There: Improving Reasoning in Language Models with
  Layer-Selective Rank Reduction**, `arXiv, 2312.13558`, [arxiv](http://arxiv.org/abs/2312.13558v1), [pdf](http://arxiv.org/pdf/2312.13558v1.pdf), cication: [**-1**](None)

	 *Pratyusha Sharma, Jordan T. Ash, Dipendra Misra*

	 · ([pratyushasharma.github](https://pratyushasharma.github.io/laser/)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-12-26-7))
- **Self-Evaluation Improves Selective Generation in Large Language Models**, `arXiv, 2312.09300`, [arxiv](http://arxiv.org/abs/2312.09300v1), [pdf](http://arxiv.org/pdf/2312.09300v1.pdf), cication: [**-1**](None)

	 *Jie Ren, Yao Zhao, Tu Vu, Peter J. Liu, Balaji Lakshminarayanan*
- **Let's Think Outside the Box: Exploring Leap-of-Thought in Large Language
  Models with Creative Humor Generation**, `arXiv, 2312.02439`, [arxiv](http://arxiv.org/abs/2312.02439v2), [pdf](http://arxiv.org/pdf/2312.02439v2.pdf), cication: [**-1**](None)

	 *Shanshan Zhong, Zhongzhan Huang, Shanghua Gao, Wushao Wen, Liang Lin, Marinka Zitnik, Pan Zhou* · ([clot](https://github.com/sail-sg/clot) - sail-sg) ![Star](https://img.shields.io/github/stars/sail-sg/clot.svg?style=social&label=Star)
- **PathFinder: Guided Search over Multi-Step Reasoning Paths**, `arXiv, 2312.05180`, [arxiv](http://arxiv.org/abs/2312.05180v1), [pdf](http://arxiv.org/pdf/2312.05180v1.pdf), cication: [**-1**](None)

	 *Olga Golovneva, Sean O'Brien, Ramakanth Pasunuru, Tianlu Wang, Luke Zettlemoyer, Maryam Fazel-Zarandi, Asli Celikyilmaz*
- **Training Chain-of-Thought via Latent-Variable Inference**, `arXiv, 2312.02179`, [arxiv](http://arxiv.org/abs/2312.02179v1), [pdf](http://arxiv.org/pdf/2312.02179v1.pdf), cication: [**-1**](None)

	 *Du Phan, Matthew D. Hoffman, David Dohan, Sholto Douglas, Tuan Anh Le, Aaron Parisi, Pavel Sountsov, Charles Sutton, Sharad Vikram, Rif A. Saurous*
- **LLMs cannot find reasoning errors, but can correct them!**, `arXiv, 2311.08516`, [arxiv](http://arxiv.org/abs/2311.08516v1), [pdf](http://arxiv.org/pdf/2311.08516v1.pdf), cication: [**-1**](None)

	 *Gladys Tyen, Hassan Mansoor, Peter Chen, Tony Mak, Victor Cărbune* · ([BIG-Bench-Mistake](https://github.com/WHGTyen/BIG-Bench-Mistake) - WHGTyen) ![Star](https://img.shields.io/github/stars/WHGTyen/BIG-Bench-Mistake.svg?style=social&label=Star) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-28))
- **System 2 Attention (is something you might need too)**, `arXiv, 2311.11829`, [arxiv](http://arxiv.org/abs/2311.11829v1), [pdf](http://arxiv.org/pdf/2311.11829v1.pdf), cication: [**-1**](None)

	 *Jason Weston, Sainbayar Sukhbaatar*
- **Orca 2: Teaching Small Language Models How to Reason**, `arXiv, 2311.11045`, [arxiv](http://arxiv.org/abs/2311.11045v1), [pdf](http://arxiv.org/pdf/2311.11045v1.pdf), cication: [**-1**](None)

	 *Arindam Mitra, Luciano Del Corro, Shweti Mahajan, Andres Codas, Clarisse Simoes, Sahaj Agrawal, Xuxi Chen, Anastasia Razdaibiedina, Erik Jones, Kriti Aggarwal*
- **Thread of Thought Unraveling Chaotic Contexts**, `arXiv, 2311.08734`, [arxiv](http://arxiv.org/abs/2311.08734v1), [pdf](http://arxiv.org/pdf/2311.08734v1.pdf), cication: [**-1**](None)

	 *Yucheng Zhou, Xiubo Geng, Tao Shen, Chongyang Tao, Guodong Long, Jian-Guang Lou, Jianbing Shen*
- **UNcommonsense Reasoning: Abductive Reasoning about Uncommon Situations**, `arXiv, 2311.08469`, [arxiv](http://arxiv.org/abs/2311.08469v1), [pdf](http://arxiv.org/pdf/2311.08469v1.pdf), cication: [**-1**](None)

	 *Wenting Zhao, Justin T Chiu, Jena D. Hwang, Faeze Brahman, Jack Hessel, Sanjiban Choudhury, Yejin Choi, Xiang Lorraine Li, Alane Suhr*
- **The ART of LLM Refinement: Ask, Refine, and Trust**, `arXiv, 2311.07961`, [arxiv](http://arxiv.org/abs/2311.07961v1), [pdf](http://arxiv.org/pdf/2311.07961v1.pdf), cication: [**-1**](None)

	 *Kumar Shridhar, Koustuv Sinha, Andrew Cohen, Tianlu Wang, Ping Yu, Ram Pasunuru, Mrinmaya Sachan, Jason Weston, Asli Celikyilmaz*
- **ADaPT: As-Needed Decomposition and Planning with Language Models**, `arXiv, 2311.05772`, [arxiv](http://arxiv.org/abs/2311.05772v1), [pdf](http://arxiv.org/pdf/2311.05772v1.pdf), cication: [**-1**](None)

	 *Archiki Prasad, Alexander Koller, Mareike Hartmann, Peter Clark, Ashish Sabharwal, Mohit Bansal, Tushar Khot*
- **Everything of Thoughts: Defying the Law of Penrose Triangle for Thought
  Generation**, `arXiv, 2311.04254`, [arxiv](http://arxiv.org/abs/2311.04254v2), [pdf](http://arxiv.org/pdf/2311.04254v2.pdf), cication: [**-1**](None)

	 *Ruomeng Ding, Chaoyun Zhang, Lu Wang, Yong Xu, Minghua Ma, Wei Zhang, Si Qin, Saravan Rajmohan, Qingwei Lin, Dongmei Zhang*
- **Rephrase and Respond: Let Large Language Models Ask Better Questions for
  Themselves**, `arXiv, 2311.04205`, [arxiv](http://arxiv.org/abs/2311.04205v1), [pdf](http://arxiv.org/pdf/2311.04205v1.pdf), cication: [**-1**](None)

	 *Yihe Deng, Weitong Zhang, Zixiang Chen, Quanquan Gu* · ([Rephrase-and-Respond](https://github.com/uclaml/Rephrase-and-Respond) - uclaml) ![Star](https://img.shields.io/github/stars/uclaml/Rephrase-and-Respond.svg?style=social&label=Star)
- **Take a Step Back: Evoking Reasoning via Abstraction in Large Language
  Models**, `arXiv, 2310.06117`, [arxiv](http://arxiv.org/abs/2310.06117v1), [pdf](http://arxiv.org/pdf/2310.06117v1.pdf), cication: [**-1**](None)

	 *Huaixiu Steven Zheng, Swaroop Mishra, Xinyun Chen, Heng-Tze Cheng, Ed H. Chi, Quoc V Le, Denny Zhou*
- **Learning From Mistakes Makes LLM Better Reasoner**, `arXiv, 2310.20689`, [arxiv](http://arxiv.org/abs/2310.20689v1), [pdf](http://arxiv.org/pdf/2310.20689v1.pdf), cication: [**-1**](None)

	 *Shengnan An, Zexiong Ma, Zeqi Lin, Nanning Zheng, Jian-Guang Lou, Weizhu Chen*
- **Branch-Solve-Merge Improves Large Language Model Evaluation and
  Generation**, `arXiv, 2310.15123`, [arxiv](http://arxiv.org/abs/2310.15123v1), [pdf](http://arxiv.org/pdf/2310.15123v1.pdf), cication: [**-1**](None)

	 *Swarnadeep Saha, Omer Levy, Asli Celikyilmaz, Mohit Bansal, Jason Weston, Xian Li*
- **Democratizing Reasoning Ability: Tailored Learning from Large Language
  Model**, `arXiv, 2310.13332`, [arxiv](http://arxiv.org/abs/2310.13332v1), [pdf](http://arxiv.org/pdf/2310.13332v1.pdf), cication: [**-1**](None)

	 *Zhaoyang Wang, Shaohan Huang, Yuxuan Liu, Jiahai Wang, Minghui Song, Zihan Zhang, Haizhen Huang, Furu Wei, Weiwei Deng, Feng Sun*
- **Teaching Language Models to Self-Improve through Interactive
  Demonstrations**, `arXiv, 2310.13522`, [arxiv](http://arxiv.org/abs/2310.13522v1), [pdf](http://arxiv.org/pdf/2310.13522v1.pdf), cication: [**-1**](None)

	 *Xiao Yu, Baolin Peng, Michel Galley, Jianfeng Gao, Zhou Yu*
- [**automix**](https://github.com/automix-llm/automix) - automix-llm ![Star](https://img.shields.io/github/stars/automix-llm/automix.svg?style=social&label=Star)

	 *Mixing Language Models with Self-Verification and Meta-Verification*
- **The Consensus Game: Language Model Generation via Equilibrium Search**, `arXiv, 2310.09139`, [arxiv](http://arxiv.org/abs/2310.09139v1), [pdf](http://arxiv.org/pdf/2310.09139v1.pdf), cication: [**-1**](None)

	 *Athul Paul Jacob, Yikang Shen, Gabriele Farina, Jacob Andreas* · ([qbitai](https://www.qbitai.com/2023/10/90471.html))
- **When can transformers reason with abstract symbols?**, `arXiv, 2310.09753`, [arxiv](http://arxiv.org/abs/2310.09753v1), [pdf](http://arxiv.org/pdf/2310.09753v1.pdf), cication: [**-1**](None)

	 *Enric Boix-Adsera, Omid Saremi, Emmanuel Abbe, Samy Bengio, Etai Littwin, Joshua Susskind*
- **Avalon's Game of Thoughts: Battle Against Deception through Recursive
  Contemplation**, `arXiv, 2310.01320`, [arxiv](http://arxiv.org/abs/2310.01320v3), [pdf](http://arxiv.org/pdf/2310.01320v3.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=14812032290058835837&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shenzhi Wang, Chang Liu, Zilong Zheng, Siyuan Qi, Shuo Chen, Qisen Yang, Andrew Zhao, Chaofei Wang, Shiji Song, Gao Huang* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-16-8))
- **Large Language Models can Learn Rules**, `arXiv, 2310.07064`, [arxiv](http://arxiv.org/abs/2310.07064v1), [pdf](http://arxiv.org/pdf/2310.07064v1.pdf), cication: [**-1**](None)

	 *Zhaocheng Zhu, Yuan Xue, Xinyun Chen, Denny Zhou, Jian Tang, Dale Schuurmans, Hanjun Dai* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247614207&idx=3&sn=7ab22ec350ce81f634c4534a089581a7))
- **Large Language Models as Analogical Reasoners**, `arXiv, 2310.01714`, [arxiv](http://arxiv.org/abs/2310.01714v2), [pdf](http://arxiv.org/pdf/2310.01714v2.pdf), cication: [**-1**](None)

	 *Michihiro Yasunaga, Xinyun Chen, Yujia Li, Panupong Pasupat, Jure Leskovec, Percy Liang, Ed H. Chi, Denny Zhou*
- **Language Agent Tree Search Unifies Reasoning Acting and Planning in
  Language Models**, `arXiv, 2310.04406`, [arxiv](http://arxiv.org/abs/2310.04406v1), [pdf](http://arxiv.org/pdf/2310.04406v1.pdf), cication: [**-1**](None)

	 *Andy Zhou, Kai Yan, Michal Shlapentokh-Rothman, Haohan Wang, Yu-Xiong Wang* · ([andyz245.github](https://andyz245.github.io/LanguageAgentTreeSearch/)) · ([LanguageAgentTreeSearch](https://github.com/andyz245/LanguageAgentTreeSearch) - andyz245) ![Star](https://img.shields.io/github/stars/andyz245/LanguageAgentTreeSearch.svg?style=social&label=Star)
- **Thought Propagation: An Analogical Approach to Complex Reasoning with
  Large Language Models**, `arXiv, 2310.03965`, [arxiv](http://arxiv.org/abs/2310.03965v2), [pdf](http://arxiv.org/pdf/2310.03965v2.pdf), cication: [**-1**](None)

	 *Junchi Yu, Ran He, Rex Ying* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652388609&idx=3&sn=fbb7e539a1f9192ad7213a069ce37fa3))
- **Large Language Model Cascades with Mixture of Thoughts Representations
  for Cost-efficient Reasoning**, `arXiv, 2310.03094`, [arxiv](http://arxiv.org/abs/2310.03094v2), [pdf](http://arxiv.org/pdf/2310.03094v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=3633402015473153407&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Murong Yue, Jie Zhao, Min Zhang, Liang Du, Ziyu Yao*
- **Large Language Models as Analogical Reasoners**, `arXiv, 2310.01714`, [arxiv](http://arxiv.org/abs/2310.01714v2), [pdf](http://arxiv.org/pdf/2310.01714v2.pdf), cication: [**-1**](None)

	 *Michihiro Yasunaga, Xinyun Chen, Yujia Li, Panupong Pasupat, Jure Leskovec, Percy Liang, Ed H. Chi, Denny Zhou*
- **Large Language Models Cannot Self-Correct Reasoning Yet**, `arXiv, 2310.01798`, [arxiv](http://arxiv.org/abs/2310.01798v1), [pdf](http://arxiv.org/pdf/2310.01798v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=3909307420246116708&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jie Huang, Xinyun Chen, Swaroop Mishra, Huaixiu Steven Zheng, Adams Wei Yu, Xinying Song, Denny Zhou*
- **Enable Language Models to Implicitly Learn Self-Improvement From Data**, `arXiv, 2310.00898`, [arxiv](http://arxiv.org/abs/2310.00898v2), [pdf](http://arxiv.org/pdf/2310.00898v2.pdf), cication: [**-1**](None)

	 *Ziqi Wang, Le Hou, Tianjian Lu, Yuexin Wu, Yunxuan Li, Hongkun Yu, Heng Ji*
- **Evaluating Cognitive Maps and Planning in Large Language Models with
  CogEval**, `arXiv, 2309.15129`, [arxiv](http://arxiv.org/abs/2309.15129v1), [pdf](http://arxiv.org/pdf/2309.15129v1.pdf), cication: [**-1**](None)

	 *Ida Momennejad, Hosein Hasanbeig, Felipe Vieira, Hiteshi Sharma, Robert Osazuwa Ness, Nebojsa Jojic, Hamid Palangi, Jonathan Larson*
- [**reconcile**](https://github.com/dinobby/reconcile) - dinobby ![Star](https://img.shields.io/github/stars/dinobby/reconcile.svg?style=social&label=Star)
- **DSPy: Compiling Declarative Language Model Calls into Self-Improving
  Pipelines**, `arXiv, 2310.03714`, [arxiv](http://arxiv.org/abs/2310.03714v1), [pdf](http://arxiv.org/pdf/2310.03714v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=10905723418597745738&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Omar Khattab, Arnav Singhvi, Paridhi Maheshwari, Zhiyuan Zhang, Keshav Santhanam, Sri Vardhamanan, Saiful Haq, Ashutosh Sharma, Thomas T. Joshi, Hanna Moazam* · ([dspy](https://github.com/stanfordnlp/dspy) - stanfordnlp) ![Star](https://img.shields.io/github/stars/stanfordnlp/dspy.svg?style=social&label=Star)
- **Physics of Language Models: Part 3.2, Knowledge Manipulation**, `arXiv, 2309.14402`, [arxiv](http://arxiv.org/abs/2309.14402v1), [pdf](http://arxiv.org/pdf/2309.14402v1.pdf), cication: [**-1**](None)

	 *Zeyuan Allen-Zhu, Yuanzhi Li* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-03-5)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247618883&idx=2&sn=bedc3095f20cd2c4ac476ed5562fe86a))
- **Cumulative Reasoning with Large Language Models**, `arXiv, 2308.04371`, [arxiv](http://arxiv.org/abs/2308.04371v4), [pdf](http://arxiv.org/pdf/2308.04371v4.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=12498281829120693895&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yifan Zhang, Jingqin Yang, Yang Yuan, Andrew Chi-Chih Yao* · ([qbitai](https://www.qbitai.com/2023/09/87067.html))
- **SCREWS: A Modular Framework for Reasoning with Revisions**, `arXiv, 2309.13075`, [arxiv](http://arxiv.org/abs/2309.13075v1), [pdf](http://arxiv.org/pdf/2309.13075v1.pdf), cication: [**-1**](None)

	 *Kumar Shridhar, Harsh Jhamtani, Hao Fang, Benjamin Van Durme, Jason Eisner, Patrick Xia*
- **Contrastive Decoding Improves Reasoning in Large Language Models**, `arXiv, 2309.09117`, [arxiv](http://arxiv.org/abs/2309.09117v2), [pdf](http://arxiv.org/pdf/2309.09117v2.pdf), cication: [**-1**](None)

	 *Sean O'Brien, Mike Lewis*
- **Compositional Foundation Models for Hierarchical Planning**, `arXiv, 2309.08587`, [arxiv](http://arxiv.org/abs/2309.08587v2), [pdf](http://arxiv.org/pdf/2309.08587v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=6553254235550482566&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Anurag Ajay, Seungwook Han, Yilun Du, Shuang Li, Abhi Gupta, Tommi Jaakkola, Josh Tenenbaum, Leslie Kaelbling, Akash Srivastava, Pulkit Agrawal*
- **Unleashing Cognitive Synergy in Large Language Models: A Task-Solving
  Agent through Multi-Persona Self-Collaboration**, `arXiv, 2307.05300`, [arxiv](http://arxiv.org/abs/2307.05300v2), [pdf](http://arxiv.org/pdf/2307.05300v2.pdf), cication: [**25**](https://scholar.google.com/scholar?cites=9934573878831049619&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhenhailong Wang, Shaoguang Mao, Wenshan Wu, Tao Ge, Furu Wei, Heng Ji* · ([solo-performance-prompting](https://github.com/mikewangwzhl/solo-performance-prompting) - mikewangwzhl) ![Star](https://img.shields.io/github/stars/mikewangwzhl/solo-performance-prompting.svg?style=social&label=Star)
- **SelfCheck: Using LLMs to Zero-Shot Check Their Own Step-by-Step
  Reasoning**, `arXiv, 2308.00436`, [arxiv](http://arxiv.org/abs/2308.00436v3), [pdf](http://arxiv.org/pdf/2308.00436v3.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=4713238228992296406&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ning Miao, Yee Whye Teh, Tom Rainforth*
- **Measuring Faithfulness in Chain-of-Thought Reasoning**, `arXiv, 2307.13702`, [arxiv](http://arxiv.org/abs/2307.13702v1), [pdf](http://arxiv.org/pdf/2307.13702v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=61084667767590785&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tamera Lanham, Anna Chen, Ansh Radhakrishnan, Benoit Steiner, Carson Denison, Danny Hernandez, Dustin Li, Esin Durmus, Evan Hubinger, Jackson Kernion*
- [Enhancing Document-level Event Argument Extraction with Contextual Clues and Role Relevance - ACL Anthology](https://aclanthology.org/2023.findings-acl.817)

	 · ([SCPRG-master](https://github.com/LWL-cpu/SCPRG-master) - LWL-cpu) ![Star](https://img.shields.io/github/stars/LWL-cpu/SCPRG-master.svg?style=social&label=Star)
- **Question Decomposition Improves the Faithfulness of Model-Generated
  Reasoning**, `arXiv, 2307.11768`, [arxiv](http://arxiv.org/abs/2307.11768v2), [pdf](http://arxiv.org/pdf/2307.11768v2.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=12532806564457556180&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ansh Radhakrishnan, Karina Nguyen, Anna Chen, Carol Chen, Carson Denison, Danny Hernandez, Esin Durmus, Evan Hubinger, Jackson Kernion, Kamilė Lukošiūtė*
- **Promoting Exploration in Memory-Augmented Adam using Critical Momenta**, `arXiv, 2307.09638`, [arxiv](http://arxiv.org/abs/2307.09638v1), [pdf](http://arxiv.org/pdf/2307.09638v1.pdf), cication: [**-1**](None)

	 *Pranshu Malviya, Gonçalo Mordido, Aristide Baratin, Reza Babanezhad Harikandeh, Jerry Huang, Simon Lacoste-Julien, Razvan Pascanu, Sarath Chandar*
- **Does Visual Pretraining Help End-to-End Reasoning?**, `arXiv, 2307.08506`, [arxiv](http://arxiv.org/abs/2307.08506v1), [pdf](http://arxiv.org/pdf/2307.08506v1.pdf), cication: [**-1**](None)

	 *Chen Sun, Calvin Luo, Xingyi Zhou, Anurag Arnab, Cordelia Schmid*
- **Self-consistency for open-ended generations**, `arXiv, 2307.06857`, [arxiv](http://arxiv.org/abs/2307.06857v2), [pdf](http://arxiv.org/pdf/2307.06857v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=4865541108613295875&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Siddhartha Jain, Xiaofei Ma, Anoop Deoras, Bing Xiang*
- **Unleashing Cognitive Synergy in Large Language Models: A Task-Solving
  Agent through Multi-Persona Self-Collaboration**, `arXiv, 2307.05300`, [arxiv](http://arxiv.org/abs/2307.05300v2), [pdf](http://arxiv.org/pdf/2307.05300v2.pdf), cication: [**25**](https://scholar.google.com/scholar?cites=9934573878831049619&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhenhailong Wang, Shaoguang Mao, Wenshan Wu, Tao Ge, Furu Wei, Heng Ji* · ([Solo-Performance-Prompting.git](https://github.com/MikeWangWZHL/Solo-Performance-Prompting.git) - MikeWangWZHL) ![Star](https://img.shields.io/github/stars/MikeWangWZHL/Solo-Performance-Prompting.git.svg?style=social&label=Star)
- **Curious Replay for Model-based Adaptation**, `arXiv, 2306.15934`, [arxiv](http://arxiv.org/abs/2306.15934v1), [pdf](http://arxiv.org/pdf/2306.15934v1.pdf), cication: [**-1**](None)

	 *Isaac Kauvar, Chris Doyle, Linqi Zhou, Nick Haber* · ([curiousreplay](https://github.com/AutonomousAgentsLab/curiousreplay) - AutonomousAgentsLab) ![Star](https://img.shields.io/github/stars/AutonomousAgentsLab/curiousreplay.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652349432&idx=4&sn=38c3b34b788691c26ab3c9c124743d42))
- **PokemonChat: Auditing ChatGPT for Pokémon Universe Knowledge**, `arXiv, 2306.03024`, [arxiv](http://arxiv.org/abs/2306.03024v1), [pdf](http://arxiv.org/pdf/2306.03024v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=3082987323159200245&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Laura Cabello, Jiaang Li, Ilias Chalkidis*
- **Orca: Progressive Learning from Complex Explanation Traces of GPT-4**, `arXiv, 2306.02707`, [arxiv](http://arxiv.org/abs/2306.02707v1), [pdf](http://arxiv.org/pdf/2306.02707v1.pdf), cication: [**32**](https://scholar.google.com/scholar?cites=11148593440500525469&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Subhabrata Mukherjee, Arindam Mitra, Ganesh Jawahar, Sahaj Agarwal, Hamid Palangi, Ahmed Awadallah* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652341615&idx=4&sn=dc577632658a7f6c7d81395a703414af))
- **REFLECT: Summarizing Robot Experiences for Failure Explanation and
  Correction**, `arXiv, 2306.15724`, [arxiv](http://arxiv.org/abs/2306.15724v4), [pdf](http://arxiv.org/pdf/2306.15724v4.pdf), cication: [**13**](https://scholar.google.com/scholar?cites=13568943050059915533&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zeyi Liu, Arpit Bahety, Shuran Song*
- **From Word Models to World Models: Translating from Natural Language to
  the Probabilistic Language of Thought**, `arXiv, 2306.12672`, [arxiv](http://arxiv.org/abs/2306.12672v2), [pdf](http://arxiv.org/pdf/2306.12672v2.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=13778788929096574993&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lionel Wong, Gabriel Grand, Alexander K. Lew, Noah D. Goodman, Vikash K. Mansinghka, Jacob Andreas, Joshua B. Tenenbaum*
- **DERA: Enhancing Large Language Model Completions with Dialog-Enabled
  Resolving Agents**, `arXiv, 2303.17071`, [arxiv](http://arxiv.org/abs/2303.17071v1), [pdf](http://arxiv.org/pdf/2303.17071v1.pdf), cication: [**20**](https://scholar.google.com/scholar?cites=11750047789546195567&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Varun Nair, Elliot Schumacher, Geoffrey Tso, Anitha Kannan*
- **Toward Grounded Social Reasoning**, `arXiv, 2306.08651`, [arxiv](http://arxiv.org/abs/2306.08651v1), [pdf](http://arxiv.org/pdf/2306.08651v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=17552510382523367052&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Minae Kwon, Hengyuan Hu, Vivek Myers, Siddharth Karamcheti, Anca Dragan, Dorsa Sadigh*
- [**tart**](https://github.com/hazyresearch/tart) - hazyresearch ![Star](https://img.shields.io/github/stars/hazyresearch/tart.svg?style=social&label=Star)

	 *TART: A plug-and-play Transformer module for task-agnostic reasoning*
- **SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex
  Interactive Tasks**, `arXiv, 2305.17390`, [arxiv](http://arxiv.org/abs/2305.17390v1), [pdf](http://arxiv.org/pdf/2305.17390v1.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=3844178012869500706&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Bill Yuchen Lin, Yicheng Fu, Karina Yang, Prithviraj Ammanabrolu, Faeze Brahman, Shiyu Huang, Chandra Bhagavatula, Yejin Choi, Xiang Ren* · ([yuchenlin](https://yuchenlin.xyz/swiftsage/)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-15-5))
- **TART: A plug-and-play Transformer module for task-agnostic reasoning**, `arXiv, 2306.07536`, [arxiv](http://arxiv.org/abs/2306.07536v1), [pdf](http://arxiv.org/pdf/2306.07536v1.pdf), cication: [**-1**](None)

	 *Kush Bhatia, Avanika Narayan, Christopher De Sa, Christopher Ré*
- **Can Large Language Models Infer Causation from Correlation?**, `arXiv, 2306.05836`, [arxiv](http://arxiv.org/abs/2306.05836v1), [pdf](http://arxiv.org/pdf/2306.05836v1.pdf), cication: [**12**](https://scholar.google.com/scholar?cites=10622702130608075727&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhijing Jin, Jiarui Liu, Zhiheng Lyu, Spencer Poff, Mrinmaya Sachan, Rada Mihalcea, Mona Diab, Bernhard Schölkopf*
- **Certified Deductive Reasoning with Language Models**, `arXiv, 2306.04031`, [arxiv](http://arxiv.org/abs/2306.04031v2), [pdf](http://arxiv.org/pdf/2306.04031v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=17100771379034868545&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Gabriel Poesia, Kanishk Gandhi, Eric Zelikman, Noah D. Goodman*
- **Triggering Multi-Hop Reasoning for Question Answering in Language Models
  using Soft Prompts and Random Walks**, `arXiv, 2306.04009`, [arxiv](http://arxiv.org/abs/2306.04009v1), [pdf](http://arxiv.org/pdf/2306.04009v1.pdf), cication: [**-1**](None)

	 *Kanishka Misra, Cicero Nogueira dos Santos, Siamak Shakeri*
- [**Thought-Cloning**](https://github.com/ShengranHu/Thought-Cloning) - ShengranHu ![Star](https://img.shields.io/github/stars/ShengranHu/Thought-Cloning.svg?style=social&label=Star)

	 *Thought Cloning: Learning to Think while Acting by Imitating Human Thinking*
- **PlaSma: Making Small Language Models Better Procedural Knowledge Models
  for (Counterfactual) Planning**, `arXiv, 2305.19472`, [arxiv](http://arxiv.org/abs/2305.19472v2), [pdf](http://arxiv.org/pdf/2305.19472v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=8835166591986464637&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Faeze Brahman, Chandra Bhagavatula, Valentina Pyatkin, Jena D. Hwang, Xiang Lorraine Li, Hirona J. Arai, Soumya Sanyal, Keisuke Sakaguchi, Xiang Ren, Yejin Choi*
- **Think Before You Act: Decision Transformers with Internal Working Memory**, `arXiv, 2305.16338`, [arxiv](http://arxiv.org/abs/2305.16338v1), [pdf](http://arxiv.org/pdf/2305.16338v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=4074666689465839415&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jikun Kang, Romain Laroche, Xindi Yuan, Adam Trischler, Xue Liu, Jie Fu*
- **Improving Factuality and Reasoning in Language Models through Multiagent
  Debate**, `arXiv, 2305.14325`, [arxiv](http://arxiv.org/abs/2305.14325v1), [pdf](http://arxiv.org/pdf/2305.14325v1.pdf), cication: [**52**](https://scholar.google.com/scholar?cites=4306390936519288835&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yilun Du, Shuang Li, Antonio Torralba, Joshua B. Tenenbaum, Igor Mordatch* · ([composable-models.github](https://composable-models.github.io/llm_debate/))
- **LLMs as Factual Reasoners: Insights from Existing Benchmarks and Beyond**, `arXiv, 2305.14540`, [arxiv](http://arxiv.org/abs/2305.14540v1), [pdf](http://arxiv.org/pdf/2305.14540v1.pdf), cication: [**8**](https://scholar.google.com/scholar?cites=9081535082559746395&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Philippe Laban, Wojciech Kryściński, Divyansh Agarwal, Alexander R. Fabbri, Caiming Xiong, Shafiq Joty, Chien-Sheng Wu*
- **Language Models of Code are Few-Shot Commonsense Learners**, `arXiv, 2210.07128`, [arxiv](http://arxiv.org/abs/2210.07128v3), [pdf](http://arxiv.org/pdf/2210.07128v3.pdf), cication: [**54**](https://scholar.google.com/scholar?cites=8413916372764514138&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Aman Madaan, Shuyan Zhou, Uri Alon, Yiming Yang, Graham Neubig*
- **OPT-R: Exploring the Role of Explanations in Finetuning and Prompting
  for Reasoning Skills of Large Language Models**, `arXiv, 2305.12001`, [arxiv](http://arxiv.org/abs/2305.12001v2), [pdf](http://arxiv.org/pdf/2305.12001v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=6515568236027532637&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Badr AlKhamissi, Siddharth Verma, Ping Yu, Zhijing Jin, Asli Celikyilmaz, Mona Diab*
- **Introspective Tips: Large Language Model for In-Context Decision Making**, `arXiv, 2305.11598`, [arxiv](http://arxiv.org/abs/2305.11598v1), [pdf](http://arxiv.org/pdf/2305.11598v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=1596475359256317938&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Liting Chen, Lu Wang, Hang Dong, Yali Du, Jie Yan, Fangkai Yang, Shuang Li, Pu Zhao, Si Qin, Saravan Rajmohan*
- **CRITIC: Large Language Models Can Self-Correct with Tool-Interactive
  Critiquing**, `arXiv, 2305.11738`, [arxiv](http://arxiv.org/abs/2305.11738v2), [pdf](http://arxiv.org/pdf/2305.11738v2.pdf), cication: [**19**](https://scholar.google.com/scholar?cites=847439943785631377&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhibin Gou, Zhihong Shao, Yeyun Gong, Yelong Shen, Yujiu Yang, Nan Duan, Weizhu Chen*
- **Tree of Thoughts: Deliberate Problem Solving with Large Language Models**, `arXiv, 2305.10601`, [arxiv](http://arxiv.org/abs/2305.10601v1), [pdf](http://arxiv.org/pdf/2305.10601v1.pdf), cication: [**188**](https://scholar.google.com/scholar?cites=4359362721511170604&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shunyu Yao, Dian Yu, Jeffrey Zhao, Izhak Shafran, Thomas L. Griffiths, Yuan Cao, Karthik Narasimhan*
- **Imitation versus Innovation: What children can do that large language
  and language-and-vision models cannot (yet)?**, `arXiv, 2305.07666`, [arxiv](http://arxiv.org/abs/2305.07666v1), [pdf](http://arxiv.org/pdf/2305.07666v1.pdf), cication: [**-1**](None)

	 *Eunice Yiu, Eliza Kosoy, Alison Gopnik* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652419464&idx=3&sn=7c2ab936e933e14cc88fae98ea053210&poc_token=HD_bfmWj9pDzGyIzWOOEQ-lqpK0YnSC2-6uHtVw5))
- [**chameleon-llm**](https://github.com/lupantech/chameleon-llm) - lupantech ![Star](https://img.shields.io/github/stars/lupantech/chameleon-llm.svg?style=social&label=Star)
- **Boosting Theory-of-Mind Performance in Large Language Models via
  Prompting**, `arXiv, 2304.11490`, [arxiv](http://arxiv.org/abs/2304.11490v3), [pdf](http://arxiv.org/pdf/2304.11490v3.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=8440877199679501480&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shima Rahimi Moghaddam, Christopher J. Honey*
- **Reflexion: Language Agents with Verbal Reinforcement Learning**, `arXiv, 2303.11366`, [arxiv](http://arxiv.org/abs/2303.11366v4), [pdf](http://arxiv.org/pdf/2303.11366v4.pdf), cication: [**110**](https://scholar.google.com/scholar?cites=5851912057675548738&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Noah Shinn, Federico Cassano, Edward Berman, Ashwin Gopinath, Karthik Narasimhan, Shunyu Yao*

	 · ([promptingguide](https://www.promptingguide.ai/techniques/reflexion))
- **Large Language Models Are Reasoning Teachers**, `arXiv, 2212.10071`, [arxiv](http://arxiv.org/abs/2212.10071v2), [pdf](http://arxiv.org/pdf/2212.10071v2.pdf), cication: [**59**](https://scholar.google.com/scholar?cites=6306842148145703485&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Namgyu Ho, Laura Schmid, Se-Young Yun* · ([reasoning-teacher](https://github.com/itsnamgyu/reasoning-teacher) - itsnamgyu) ![Star](https://img.shields.io/github/stars/itsnamgyu/reasoning-teacher.svg?style=social&label=Star)

### Other
- [LLM Reasoning Papers - a philschmid Collection](https://huggingface.co/collections/philschmid/llm-reasoning-papers-66e6abbdf5579b829f214de8)

- [陶哲轩支持！AI奥林匹克数学奖来了，奖金500万美元，寻找能得IMO金牌的大模型 | 量子位](https://www.qbitai.com/2023/11/101471.html)
- [Keynote IV: Teaching LLMs to Reason](https://icml.cc/virtual/2023/29160)
- [大模型Fewshot推理如何选择更好的示例](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495177&idx=2&sn=fe8353efed16a81e35462be06d5a6cea)

## Math reasoning
- **MathCoder2: Better Math Reasoning from Continued Pretraining on
  Model-translated Mathematical Code**, `arXiv, 2410.08196`, [arxiv](http://arxiv.org/abs/2410.08196v1), [pdf](http://arxiv.org/pdf/2410.08196v1.pdf), cication: [**-1**](None)

	 *Zimu Lu, Aojun Zhou, Ke Wang, Houxing Ren, Weikang Shi, Junting Pan, Mingjie Zhan, Hongsheng Li* · ([mathllm.github](https://mathllm.github.io/mathcoder2/))
- **GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in
  Large Language Models**, `arXiv, 2410.05229`, [arxiv](http://arxiv.org/abs/2410.05229v1), [pdf](http://arxiv.org/pdf/2410.05229v1.pdf), cication: [**-1**](None)

	 *Iman Mirzadeh, Keivan Alizadeh, Hooman Shahrokhi, Oncel Tuzel, Samy Bengio, Mehrdad Farajtabar*

	 · ([x](https://x.com/denny_zhou/status/1845115215450604019))
- **LLaMA-Berry: Pairwise Optimization for O1-like Olympiad-Level
  Mathematical Reasoning**, `arXiv, 2410.02884`, [arxiv](http://arxiv.org/abs/2410.02884v1), [pdf](http://arxiv.org/pdf/2410.02884v1.pdf), cication: [**-1**](None)

	 *Di Zhang, Jianbo Wu, Jingdi Lei, Tong Che, Jiatong Li, Tong Xie, Xiaoshui Huang, Shufei Zhang, Marco Pavone, Yuqiang Li*
- **MathHay: An Automated Benchmark for Long-Context Mathematical Reasoning
  in LLMs**, `arXiv, 2410.04698`, [arxiv](http://arxiv.org/abs/2410.04698v1), [pdf](http://arxiv.org/pdf/2410.04698v1.pdf), cication: [**-1**](None)

	 *Lei Wang, Shan Dong, Yuhui Xu, Hanze Dong, Yalu Wang, Amrita Saha, Ee-Peng Lim, Caiming Xiong, Doyen Sahoo*
- **Not All LLM Reasoners Are Created Equal**, `arXiv, 2410.01748`, [arxiv](http://arxiv.org/abs/2410.01748v1), [pdf](http://arxiv.org/pdf/2410.01748v1.pdf), cication: [**-1**](None)

	 *Arian Hosseini, Alessandro Sordoni, Daniel Toyama, Aaron Courville, Rishabh Agarwal*
- [**Omni-MATH**](https://github.com/KbsdJames/Omni-MATH/?tab=readme-ov-file) - KbsdJames ![Star](https://img.shields.io/github/stars/KbsdJames/Omni-MATH.svg?style=social&label=Star)

	 *The official repository of the Omni-MATH benchmark.* · ([omni-math.github](https://omni-math.github.io/))
- **To CoT or not to CoT? Chain-of-thought helps mainly on math and symbolic
  reasoning**, `arXiv, 2409.12183`, [arxiv](http://arxiv.org/abs/2409.12183v1), [pdf](http://arxiv.org/pdf/2409.12183v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=15167469291991704150&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zayne Sprague, Fangcong Yin, Juan Diego Rodriguez, Dongwei Jiang, Manya Wadhwa, Prasann Singhal, Xinyu Zhao, Xi Ye, Kyle Mahowald, Greg Durrett*

	 · ([To-CoT-or-not-to-CoT](https://github.com/Zayne-sprague/To-CoT-or-not-to-CoT) - Zayne-sprague) ![Star](https://img.shields.io/github/stars/Zayne-sprague/To-CoT-or-not-to-CoT.svg?style=social&label=Star)
- [Qwen2.5-Math - a Qwen Collection](https://huggingface.co/collections/Qwen/qwen25-math-66eaa240a1b7d5ee65f1da3e)
- **Building Math Agents with Multi-Turn Iterative Preference Learning**, `arXiv, 2409.02392`, [arxiv](http://arxiv.org/abs/2409.02392v1), [pdf](http://arxiv.org/pdf/2409.02392v1.pdf), cication: [**-1**](None)

	 *Wei Xiong, Chengshuai Shi, Jiaming Shen, Aviv Rosenberg, Zhen Qin, Daniele Calandriello, Misha Khalman, Rishabh Joshi, Bilal Piot, Mohammad Saleh*
- **InfinityMATH: A Scalable Instruction Tuning Dataset in Programmatic
  Mathematical Reasoning**, `arXiv, 2408.07089`, [arxiv](http://arxiv.org/abs/2408.07089v1), [pdf](http://arxiv.org/pdf/2408.07089v1.pdf), cication: [**-1**](None)

	 *Bo-Wen Zhang, Yan Yan, Lin Li, Guang Liu* · ([huggingface](https://huggingface.co/datasets/flagopen/InfinityMATH))
- **DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for
  Reinforcement Learning and Monte-Carlo Tree Search**, `arXiv, 2408.08152`, [arxiv](http://arxiv.org/abs/2408.08152v1), [pdf](http://arxiv.org/pdf/2408.08152v1.pdf), cication: [**-1**](None)

	 *Huajian Xin, Z. Z. Ren, Junxiao Song, Zhihong Shao, Wanjia Zhao, Haocheng Wang, Bo Liu, Liyue Zhang, Xuan Lu, Qiushi Du*
- [Introducing Qwen2-Math | Qwen](https://qwenlm.github.io/blog/qwen2-math/)

	 · ([huggingface](https://huggingface.co/collections/Qwen/qwen2-math-66b4c9e072eda65b5ec7534d))
- **LEAN-GitHub: Compiling GitHub LEAN repositories for a versatile LEAN
  prover**, `arXiv, 2407.17227`, [arxiv](http://arxiv.org/abs/2407.17227v1), [pdf](http://arxiv.org/pdf/2407.17227v1.pdf), cication: [**-1**](None)

	 *Zijian Wu, Jiayu Wang, Dahua Lin, Kai Chen* · ([InternLM-Math](https://github.com/InternLM/InternLM-Math) - InternLM) ![Star](https://img.shields.io/github/stars/InternLM/InternLM-Math.svg?style=social&label=Star)
- [AI achieves silver-medal standard solving International Mathematical Olympiad problems](https://deepmind.google/discover/blog/ai-solves-imo-problems-at-silver-medal-level/?utm_source=x&utm_medium=social&utm_campaign=&utm_content=)
- [NuminaMath - a AI-MO Collection](https://huggingface.co/collections/AI-MO/numinamath-6697df380293bcfdbc1d978c)
- **Is Your Model Really A Good Math Reasoner? Evaluating Mathematical
  Reasoning with Checklist**, `arXiv, 2407.08733`, [arxiv](http://arxiv.org/abs/2407.08733v1), [pdf](http://arxiv.org/pdf/2407.08733v1.pdf), cication: [**-1**](None)

	 *Zihao Zhou, Shudong Liu, Maizhen Ning, Wei Liu, Jindong Wang, Derek F. Wong, Xiaowei Huang, Qiufeng Wang, Kaizhu Huang*
- **Skywork-Math: Data Scaling Laws for Mathematical Reasoning in Large
  Language Models -- The Story Goes On**, `arXiv, 2407.08348`, [arxiv](http://arxiv.org/abs/2407.08348v2), [pdf](http://arxiv.org/pdf/2407.08348v2.pdf), cication: [**-1**](None)

	 *Liang Zeng, Liangjun Zhong, Liang Zhao, Tianwen Wei, Liu Yang, Jujie He, Cheng Cheng, Rui Hu, Yang Liu, Shuicheng Yan*
- [MathΣtral | Mistral AI | Frontier AI in your hands](https://mistral.ai/news/mathstral/)

	 · ([huggingface](https://huggingface.co/mistralai/mathstral-7B-v0.1))
- [**dart-math**](https://github.com/hkust-nlp/dart-math) - hkust-nlp ![Star](https://img.shields.io/github/stars/hkust-nlp/dart-math.svg?style=social&label=Star)

	 *Official implementation for the paper \*🎯DART-Math: Difficulty-Aware Rejection Tuning for Mathematical Problem-Solving\** · ([tongyx361.github](https://tongyx361.github.io/assets/dart-math/paper-dart-math.pdf))
- [**NuminaMath-7B-TIR**](https://huggingface.co/AI-MO/NuminaMath-7B-TIR) - AI-MO 🤗
	- 
- **We-Math: Does Your Large Multimodal Model Achieve Human-like
  Mathematical Reasoning?**, `arXiv, 2407.01284`, [arxiv](http://arxiv.org/abs/2407.01284v1), [pdf](http://arxiv.org/pdf/2407.01284v1.pdf), cication: [**-1**](None)

	 *Runqi Qiao, Qiuna Tan, Guanting Dong, Minhui Wu, Chong Sun, Xiaoshuai Song, Zhuoma GongQue, Shanglin Lei, Zhe Wei, Miaoxuan Zhang*

	 · ([We-Math](https://github.com/We-Math/We-Math) - We-Math) ![Star](https://img.shields.io/github/stars/We-Math/We-Math.svg?style=social&label=Star)
- **Q*: Improving Multi-step Reasoning for LLMs with Deliberative Planning**, `arXiv, 2406.14283`, [arxiv](http://arxiv.org/abs/2406.14283v3), [pdf](http://arxiv.org/pdf/2406.14283v3.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=8397897944203451859&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chaojie Wang, Yanchen Deng, Zhiyi Lv, Zeng Liang, Jujie He, Shuicheng Yan, An Bo*
- **Math-LLaVA: Bootstrapping Mathematical Reasoning for Multimodal Large
  Language Models**, `arXiv, 2406.17294`, [arxiv](http://arxiv.org/abs/2406.17294v2), [pdf](http://arxiv.org/pdf/2406.17294v2.pdf), cication: [**-1**](None)

	 *Wenhao Shi, Zhiqiang Hu, Yi Bin, Junhua Liu, Yang Yang, See-Kiong Ng, Lidong Bing, Roy Ka-Wei Lee* · ([Math-LLaVA](https://github.com/HZQ950419/Math-LLaVA) - HZQ950419) ![Star](https://img.shields.io/github/stars/HZQ950419/Math-LLaVA.svg?style=social&label=Star)
- **ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search**, `arXiv, 2406.03816`, [arxiv](http://arxiv.org/abs/2406.03816v1), [pdf](http://arxiv.org/pdf/2406.03816v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=16501772350745075519&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Dan Zhang, Sining Zhoubian, Yisong Yue, Yuxiao Dong, Jie Tang*
- **Accessing GPT-4 level Mathematical Olympiad Solutions via Monte Carlo
  Tree Self-refine with LLaMa-3 8B**, `arXiv, 2406.07394`, [arxiv](http://arxiv.org/abs/2406.07394v2), [pdf](http://arxiv.org/pdf/2406.07394v2.pdf), cication: [**-1**](None)

	 *Di Zhang, Xiaoshui Huang, Dongzhan Zhou, Yuqiang Li, Wanli Ouyang*
- **Improve Mathematical Reasoning in Language Models by Automated Process
  Supervision**, `arXiv, 2406.06592`, [arxiv](http://arxiv.org/abs/2406.06592v1), [pdf](http://arxiv.org/pdf/2406.06592v1.pdf), cication: [**-1**](None)

	 *Liangchen Luo, Yinxiao Liu, Rosanne Liu, Samrat Phatale, Harsh Lara, Yunxuan Li, Lei Shu, Yun Zhu, Lei Meng, Jiao Sun*
- **Accessing GPT-4 level Mathematical Olympiad Solutions via Monte Carlo
  Tree Self-refine with LLaMa-3 8B**, `arXiv, 2406.07394`, [arxiv](http://arxiv.org/abs/2406.07394v1), [pdf](http://arxiv.org/pdf/2406.07394v1.pdf), cication: [**-1**](None)

	 *Di Zhang, Jiatong Li, Xiaoshui Huang, Dongzhan Zhou, Yuqiang Li, Wanli Ouyang*
- **Improve Mathematical Reasoning in Language Models by Automated Process
  Supervision**, `arXiv, 2406.06592`, [arxiv](http://arxiv.org/abs/2406.06592v1), [pdf](http://arxiv.org/pdf/2406.06592v1.pdf), cication: [**-1**](None)

	 *Liangchen Luo, Yinxiao Liu, Rosanne Liu, Samrat Phatale, Harsh Lara, Yunxuan Li, Lei Shu, Yun Zhu, Lei Meng, Jiao Sun*
- [**arithmetic**](https://github.com/mcleish7/arithmetic) - mcleish7 ![Star](https://img.shields.io/github/stars/mcleish7/arithmetic.svg?style=social&label=Star)

	 *Code to reproduce "Transformers Can Do Arithmetic with the Right Embeddings", McLeish et al (2024)*
- **DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale
  Synthetic Data**, `arXiv, 2405.14333`, [arxiv](http://arxiv.org/abs/2405.14333v1), [pdf](http://arxiv.org/pdf/2405.14333v1.pdf), cication: [**-1**](None)

	 *Huajian Xin, Daya Guo, Zhihong Shao, Zhizhou Ren, Qihao Zhu, Bo Liu, Chong Ruan, Wenda Li, Xiaodan Liang*
- **AlphaMath Almost Zero: process Supervision without process**, `arXiv, 2405.03553`, [arxiv](http://arxiv.org/abs/2405.03553v1), [pdf](http://arxiv.org/pdf/2405.03553v1.pdf), cication: [**-1**](None)

	 *Guoxin Chen, Minpeng Liao, Chengxi Li, Kai Fan*
- **Rho-1: Not All Tokens Are What You Need**, `arXiv, 2404.07965`, [arxiv](http://arxiv.org/abs/2404.07965v1), [pdf](http://arxiv.org/pdf/2404.07965v1.pdf), cication: [**-1**](None)

	 *Zhenghao Lin, Zhibin Gou, Yeyun Gong, Xiao Liu, Yelong Shen, Ruochen Xu, Chen Lin, Yujiu Yang, Jian Jiao, Nan Duan* · ([huggingface](https://huggingface.co/microsoft/rho-math-7b-interpreter-v0.1))
- **Achieving >97% on GSM8K: Deeply Understanding the Problems Makes LLMs
  Perfect Reasoners**, `arXiv, 2404.14963`, [arxiv](http://arxiv.org/abs/2404.14963v1), [pdf](http://arxiv.org/pdf/2404.14963v1.pdf), cication: [**-1**](None)

	 *Qihuang Zhong, Kang Wang, Ziyang Xu, Juhua Liu, Liang Ding, Bo Du, Dacheng Tao*
- **Towards Large Language Models as Copilots for Theorem Proving in Lean**, `arXiv, 2404.12534`, [arxiv](http://arxiv.org/abs/2404.12534v1), [pdf](http://arxiv.org/pdf/2404.12534v1.pdf), cication: [**-1**](None)

	 *Peiyang Song, Kaiyu Yang, Anima Anandkumar* · ([LeanCopilot](https://github.com/lean-dojo/LeanCopilot) - lean-dojo) ![Star](https://img.shields.io/github/stars/lean-dojo/LeanCopilot.svg?style=social&label=Star)
- **ChatGLM-Math: Improving Math Problem-Solving in Large Language Models
  with a Self-Critique Pipeline**, `arXiv, 2404.02893`, [arxiv](http://arxiv.org/abs/2404.02893v1), [pdf](http://arxiv.org/pdf/2404.02893v1.pdf), cication: [**-1**](None)

	 *Yifan Xu, Xiao Liu, Xinghan Liu, Zhenyu Hou, Yueyan Li, Xiaohan Zhang, Zihan Wang, Aohan Zeng, Zhengxiao Du, Wenyi Zhao* · ([ChatGLM-Math](https://github.com/THUDM/ChatGLM-Math) - THUDM) ![Star](https://img.shields.io/github/stars/THUDM/ChatGLM-Math.svg?style=social&label=Star)
- **Common 7B Language Models Already Possess Strong Math Capabilities**, `arXiv, 2403.04706`, [arxiv](http://arxiv.org/abs/2403.04706v1), [pdf](http://arxiv.org/pdf/2403.04706v1.pdf), cication: [**-1**](None)

	 *Chen Li, Weiqi Wang, Jingcheng Hu, Yixuan Wei, Nanning Zheng, Han Hu, Zheng Zhang, Houwen Peng*
	- `LLaMA-2 7B model's surprising mathematical skills even though it only underwent standard pretraining, and its consistency improves with scaled-up supervised instruction-finetuning data.`
- **MathScale: Scaling Instruction Tuning for Mathematical Reasoning**, `arXiv, 2403.02884`, [arxiv](http://arxiv.org/abs/2403.02884v1), [pdf](http://arxiv.org/pdf/2403.02884v1.pdf), cication: [**-1**](None)

	 *Zhengyang Tang, Xingxing Zhang, Benyou Wang, Furu Wei*
- **Orca-Math: Unlocking the potential of SLMs in Grade School Math**, `arXiv, 2402.14830`, [arxiv](http://arxiv.org/abs/2402.14830v1), [pdf](http://arxiv.org/pdf/2402.14830v1.pdf), cication: [**-1**](None)

	 *Arindam Mitra, Hamed Khanpour, Corby Rosset, Ahmed Awadallah*
- **OpenMathInstruct-1: A 1.8 Million Math Instruction Tuning Dataset**, `arXiv, 2402.10176`, [arxiv](http://arxiv.org/abs/2402.10176v1), [pdf](http://arxiv.org/pdf/2402.10176v1.pdf), cication: [**-1**](None)

	 *Shubham Toshniwal, Ivan Moshkov, Sean Narenthiran, Daria Gitman, Fei Jia, Igor Gitman*
- **InternLM-Math: Open Math Large Language Models Toward Verifiable
  Reasoning**, `arXiv, 2402.06332`, [arxiv](http://arxiv.org/abs/2402.06332v1), [pdf](http://arxiv.org/pdf/2402.06332v1.pdf), cication: [**-1**](None)

	 *Huaiyuan Ying, Shuo Zhang, Linyang Li, Zhejian Zhou, Yunfan Shao, Zhaoye Fei, Yichuan Ma, Jiawei Hong, Kuikun Liu, Ziyi Wang* · ([InternLM-Math](https://github.com/InternLM/InternLM-Math) - InternLM) ![Star](https://img.shields.io/github/stars/InternLM/InternLM-Math.svg?style=social&label=Star)
- **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open
  Language Models**, `arXiv, 2402.03300`, [arxiv](http://arxiv.org/abs/2402.03300v2), [pdf](http://arxiv.org/pdf/2402.03300v2.pdf), cication: [**-1**](None)

	 *Zhihong Shao, Peiyi Wang, Qihao Zhu, Runxin Xu, Junxiao Song, Mingchuan Zhang, Y. K. Li, Y. Wu, Daya Guo*
- **Large Language Models for Mathematical Reasoning: Progresses and
  Challenges**, `arXiv, 2402.00157`, [arxiv](http://arxiv.org/abs/2402.00157v1), [pdf](http://arxiv.org/pdf/2402.00157v1.pdf), cication: [**-1**](None)

	 *Janice Ahn, Rishu Verma, Renze Lou, Di Liu, Rui Zhang, Wenpeng Yin*
- **Generative AI for Math: Part I -- MathPile: A Billion-Token-Scale
  Pretraining Corpus for Math**, `arXiv, 2312.17120`, [arxiv](http://arxiv.org/abs/2312.17120v1), [pdf](http://arxiv.org/pdf/2312.17120v1.pdf), cication: [**-1**](None)

	 *Zengzhi Wang, Rui Xia, Pengfei Liu* · ([huggingface](https://huggingface.co/datasets/GAIR/MathPile.))

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-01-12-3))
- [Mathematical discoveries from program search with large language models | Nature](https://www.nature.com/articles/s41586-023-06924-6)

	 · ([funsearch](https://github.com/google-deepmind/funsearch) - google-deepmind) ![Star](https://img.shields.io/github/stars/google-deepmind/funsearch.svg?style=social&label=Star)
- **Modeling Complex Mathematical Reasoning via Large Language Model based
  MathAgent**, `arXiv, 2312.08926`, [arxiv](http://arxiv.org/abs/2312.08926v1), [pdf](http://arxiv.org/pdf/2312.08926v1.pdf), cication: [**-1**](None)

	 *Haoran Liao, Qinyi Du, Shaohua Hu, Hao He, Yanyan Xu, Jidong Tian, Yaohui Jin*
- **TinyGSM: achieving >80% on GSM8k with small language models**, `arXiv, 2312.09241`, [arxiv](http://arxiv.org/abs/2312.09241v1), [pdf](http://arxiv.org/pdf/2312.09241v1.pdf), cication: [**-1**](None)

	 *Bingbin Liu, Sebastien Bubeck, Ronen Eldan, Janardhan Kulkarni, Yuanzhi Li, Anh Nguyen, Rachel Ward, Yi Zhang*
- [FunSearch: Making new discoveries in mathematical sciences using Large Language Models - Google DeepMind](https://deepmind.google/discover/blog/funsearch-making-new-discoveries-in-mathematical-sciences-using-large-language-models/?utm_source=twitter&utm_medium=social)
- **Mathematical Language Models: A Survey**, `arXiv, 2312.07622`, [arxiv](http://arxiv.org/abs/2312.07622v2), [pdf](http://arxiv.org/pdf/2312.07622v2.pdf), cication: [**-1**](None)

	 *Wentao Liu, Hanglei Hu, Jie Zhou, Yuyang Ding, Junsong Li, Jiayi Zeng, Mengliang He, Qin Chen, Bo Jiang, Aimin Zhou*
- [**LeanCopilot**](https://github.com/lean-dojo/LeanCopilot) - lean-dojo ![Star](https://img.shields.io/github/stars/lean-dojo/LeanCopilot.svg?style=social&label=Star)

	 *LLMs as Copilots for Theorem Proving in Lean*
- **Large Language Models for Mathematicians**, `arXiv, 2312.04556`, [arxiv](http://arxiv.org/abs/2312.04556v1), [pdf](http://arxiv.org/pdf/2312.04556v1.pdf), cication: [**-1**](None)

	 *Simon Frieder, Julius Berner, Philipp Petersen, Thomas Lukasiewicz*
- **LEGO-Prover: Neural Theorem Proving with Growing Libraries**, `arXiv, 2310.00656`, [arxiv](http://arxiv.org/abs/2310.00656v3), [pdf](http://arxiv.org/pdf/2310.00656v3.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=11019300421337297004&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Haiming Wang, Huajian Xin, Chuanyang Zheng, Lin Li, Zhengying Liu, Qingxing Cao, Yinya Huang, Jing Xiong, Han Shi, Enze Xie* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-30-14))
- **ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving**, `arXiv, 2309.17452`, [arxiv](http://arxiv.org/abs/2309.17452v2), [pdf](http://arxiv.org/pdf/2309.17452v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=4348118988413656609&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhibin Gou, Zhihong Shao, Yeyun Gong, Yelong Shen, Yujiu Yang, Minlie Huang, Nan Duan, Weizhu Chen* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652396659&idx=3&sn=7389f937cf8f17d93ee848cfa6b7a8a8&poc_token=HHQrPGWjIc5d6CkOP2aEZpbYX8LSyHSBLODQXNxT))
- **Improving Large Language Model Fine-tuning for Solving Math Problems**, `arXiv, 2310.10047`, [arxiv](http://arxiv.org/abs/2310.10047v1), [pdf](http://arxiv.org/pdf/2310.10047v1.pdf), cication: [**-1**](None)

	 *Yixin Liu, Avi Singh, C. Daniel Freeman, John D. Co-Reyes, Peter J. Liu*
- **Llemma: An Open Language Model For Mathematics**, `arXiv, 2310.10631`, [arxiv](http://arxiv.org/abs/2310.10631v1), [pdf](http://arxiv.org/pdf/2310.10631v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=8004581123322544769&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhangir Azerbayev, Hailey Schoelkopf, Keiran Paster, Marco Dos Santos, Stephen McAleer, Albert Q. Jiang, Jia Deng, Stella Biderman, Sean Welleck*
- **Query and Response Augmentation Cannot Help Out-of-domain Math Reasoning
  Generalization**, `arXiv, 2310.05506`, [arxiv](http://arxiv.org/abs/2310.05506v2), [pdf](http://arxiv.org/pdf/2310.05506v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=1294833622151867887&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chengpeng Li, Zheng Yuan, Hongyi Yuan, Guanting Dong, Keming Lu, Jiancan Wu, Chuanqi Tan, Xiang Wang, Chang Zhou*
- **MathCoder: Seamless Code Integration in LLMs for Enhanced Mathematical
  Reasoning**, `arXiv, 2310.03731`, [arxiv](http://arxiv.org/abs/2310.03731v1), [pdf](http://arxiv.org/pdf/2310.03731v1.pdf), cication: [**-1**](None)

	 *Ke Wang, Houxing Ren, Aojun Zhou, Zimu Lu, Sichun Luo, Weikang Shi, Renrui Zhang, Linqi Song, Mingjie Zhan, Hongsheng Li* · ([qbitai](https://www.qbitai.com/2023/10/88096.html))
- **ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving**, `arXiv, 2309.17452`, [arxiv](http://arxiv.org/abs/2309.17452v2), [pdf](http://arxiv.org/pdf/2309.17452v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=4348118988413656609&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhibin Gou, Zhihong Shao, Yeyun Gong, Yelong Shen, Yujiu Yang, Minlie Huang, Nan Duan, Weizhu Chen* · ([tora](https://github.com/microsoft/tora) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/tora.svg?style=social&label=Star)
- **MetaMath: Bootstrap Your Own Mathematical Questions for Large Language
  Models**, `arXiv, 2309.12284`, [arxiv](http://arxiv.org/abs/2309.12284v3), [pdf](http://arxiv.org/pdf/2309.12284v3.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=4019642283454829969&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Longhui Yu, Weisen Jiang, Han Shi, Jincheng Yu, Zhengying Liu, Yu Zhang, James T. Kwok, Zhenguo Li, Adrian Weller, Weiyang Liu* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-11))
- **MAmmoTH: Building Math Generalist Models through Hybrid Instruction
  Tuning**, `arXiv, 2309.05653`, [arxiv](http://arxiv.org/abs/2309.05653v3), [pdf](http://arxiv.org/pdf/2309.05653v3.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=12987789151489880737&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xiang Yue, Xingwei Qu, Ge Zhang, Yao Fu, Wenhao Huang, Huan Sun, Yu Su, Wenhu Chen* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-25-9)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652379686&idx=4&sn=183caf45719e87371d837c592544b775))
- [**abel**](https://github.com/GAIR-NLP/abel) - GAIR-NLP ![Star](https://img.shields.io/github/stars/GAIR-NLP/abel.svg?style=social&label=Star)

	 *SOTA Math Opensource LLM* · ([qbitai](https://www.qbitai.com/2023/09/85500.html))
- **Large Language Model for Science: A Study on P vs. NP**, `arXiv, 2309.05689`, [arxiv](http://arxiv.org/abs/2309.05689v1), [pdf](http://arxiv.org/pdf/2309.05689v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=10209613850404633620&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Qingxiu Dong, Li Dong, Ke Xu, Guangyan Zhou, Yaru Hao, Zhifang Sui, Furu Wei* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-14-5))
- **Large Language Models as Optimizers**, `arXiv, 2309.03409`, [arxiv](http://arxiv.org/abs/2309.03409v1), [pdf](http://arxiv.org/pdf/2309.03409v1.pdf), cication: [**32**](https://scholar.google.com/scholar?cites=3095277683017219202&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chengrun Yang, Xuezhi Wang, Yifeng Lu, Hanxiao Liu, Quoc V. Le, Denny Zhou, Xinyun Chen* · ([qbitai](https://www.qbitai.com/2023/09/82700.html))
- **GPT Can Solve Mathematical Problems Without a Calculator**, `arXiv, 2309.03241`, [arxiv](http://arxiv.org/abs/2309.03241v2), [pdf](http://arxiv.org/pdf/2309.03241v2.pdf), cication: [**-1**](None)

	 *Zhen Yang, Ming Ding, Qingsong Lv, Zhihuan Jiang, Zehai He, Yuyi Guo, Jinfeng Bai, Jie Tang* · ([mathglm](https://github.com/thudm/mathglm) - thudm) ![Star](https://img.shields.io/github/stars/thudm/mathglm.svg?style=social&label=Star)
- **When Do Program-of-Thoughts Work for Reasoning?**, `arXiv, 2308.15452`, [arxiv](http://arxiv.org/abs/2308.15452v3), [pdf](http://arxiv.org/pdf/2308.15452v3.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=12435074525863344012&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhen Bi, Ningyu Zhang, Yinuo Jiang, Shumin Deng, Guozhou Zheng, Huajun Chen* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494505&idx=2&sn=579d94fd02f98c04eccb9b3631f38aaf))
- **Solving Challenging Math Word Problems Using GPT-4 Code Interpreter with
  Code-based Self-Verification**, `arXiv, 2308.07921`, [arxiv](http://arxiv.org/abs/2308.07921v1), [pdf](http://arxiv.org/pdf/2308.07921v1.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=14436709317034576117&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Aojun Zhou, Ke Wang, Zimu Lu, Weikang Shi, Sichun Luo, Zipeng Qin, Shaoqing Lu, Anya Jia, Linqi Song, Mingjie Zhan* · ([qbitai](https://www.qbitai.com/2023/08/77452.html)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652371869&idx=4&sn=93249fb61623c30bb79ef80f1932db8e))
- **Scaling Relationship on Learning Mathematical Reasoning with Large
  Language Models**, `arXiv, 2308.01825`, [arxiv](http://arxiv.org/abs/2308.01825v2), [pdf](http://arxiv.org/pdf/2308.01825v2.pdf), cication: [**17**](https://scholar.google.com/scholar?cites=4908426319510085302&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zheng Yuan, Hongyi Yuan, Chengpeng Li, Guanting Dong, Keming Lu, Chuanqi Tan, Chang Zhou, Jingren Zhou* · ([gsm8k-screl](https://github.com/ofa-sys/gsm8k-screl) - ofa-sys) ![Star](https://img.shields.io/github/stars/ofa-sys/gsm8k-screl.svg?style=social&label=Star)
- **Self-Supervised Learning with Lie Symmetries for Partial Differential
  Equations**, `arXiv, 2307.05432`, [arxiv](http://arxiv.org/abs/2307.05432v1), [pdf](http://arxiv.org/pdf/2307.05432v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=11609232228283802783&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Grégoire Mialon, Quentin Garrido, Hannah Lawrence, Danyal Rehman, Yann LeCun, Bobak T. Kiani*
- **Teaching Arithmetic to Small Transformers**, `arXiv, 2307.03381`, [arxiv](http://arxiv.org/abs/2307.03381v1), [pdf](http://arxiv.org/pdf/2307.03381v1.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=15358450351006592493&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Nayoung Lee, Kartik Sreenivasan, Jason D. Lee, Kangwook Lee, Dimitris Papailiopoulos*
- **Length Generalization in Arithmetic Transformers**, `arXiv, 2306.15400`, [arxiv](http://arxiv.org/abs/2306.15400v1), [pdf](http://arxiv.org/pdf/2306.15400v1.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=8252907095497982991&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Samy Jelassi, Stéphane d'Ascoli, Carles Domingo-Enrich, Yuhuai Wu, Yuanzhi Li, François Charton*
-  [[2305.14201] Goat: Fine-tuned LLaMA Outperforms GPT-4 on Arithmetic Tasks](https://arxiv.org/abs/2305.14201)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652337228&idx=3&sn=5661ca28d0e1d4a185994a54040c2bc3)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652338143&idx=4&sn=d8450601423187ad56073750ca4dff16))
- **An Empirical Study on Challenging Math Problem Solving with GPT-4**, `arXiv, 2306.01337`, [arxiv](http://arxiv.org/abs/2306.01337v2), [pdf](http://arxiv.org/pdf/2306.01337v2.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=14478748604749128668&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yiran Wu, Feiran Jia, Shaokun Zhang, Hangyu Li, Erkang Zhu, Yue Wang, Yin Tat Lee, Richard Peng, Qingyun Wu, Chi Wang*
- **Evaluating Language Models for Mathematics through Interactions**, `arXiv, 2306.01694`, [arxiv](http://arxiv.org/abs/2306.01694v2), [pdf](http://arxiv.org/pdf/2306.01694v2.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=746809488338256413&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Katherine M. Collins, Albert Q. Jiang, Simon Frieder, Lionel Wong, Miri Zilka, Umang Bhatt, Thomas Lukasiewicz, Yuhuai Wu, Joshua B. Tenenbaum, William Hart*
- **Let's Verify Step by Step**, `arXiv, 2305.20050`, [arxiv](http://arxiv.org/abs/2305.20050v1), [pdf](http://arxiv.org/pdf/2305.20050v1.pdf), cication: [**65**](https://scholar.google.com/scholar?cites=3594089577812846684&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hunter Lightman, Vineet Kosaraju, Yura Burda, Harri Edwards, Bowen Baker, Teddy Lee, Jan Leike, John Schulman, Ilya Sutskever, Karl Cobbe* · ([openai](https://openai.com/research/improving-mathematical-reasoning-with-process-supervision)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652335829&idx=1&sn=12e7bf6e15bbc833b1ee6e2a4734220c))
-  [GitHub - zwq2018/Multi-view-Consistency-for-MWP: EMNLP22: Multi-View Reasoning: Consistent Contrastive Learning for Math Word Problem](https://github.com/zwq2018/multi-view-consistency-for-mwp)

### Benchmarks
- **Omni-MATH: A Universal Olympiad Level Mathematic Benchmark For Large
  Language Models**, `arXiv, 2410.07985`, [arxiv](http://arxiv.org/abs/2410.07985v2), [pdf](http://arxiv.org/pdf/2410.07985v2.pdf), cication: [**-1**](None)

	 *Bofei Gao, Feifan Song, Zhe Yang, Zefan Cai, Yibo Miao, Qingxiu Dong, Lei Li, Chenghao Ma, Liang Chen, Runxin Xu* · ([Omni-MATH](https://github.com/KbsdJames/Omni-MATH) - KbsdJames) ![Star](https://img.shields.io/github/stars/KbsdJames/Omni-MATH.svg?style=social&label=Star) · ([omni-math.github](https://omni-math.github.io/))
- **MathVista: Evaluating Math Reasoning in Visual Contexts with GPT-4V,
  Bard, and Other Large Multimodal Models**, `arXiv, 2310.02255`, [arxiv](http://arxiv.org/abs/2310.02255v2), [pdf](http://arxiv.org/pdf/2310.02255v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=8391766948698077395&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Pan Lu, Hritik Bansal, Tony Xia, Jiacheng Liu, Chunyuan Li, Hannaneh Hajishirzi, Hao Cheng, Kai-Wei Chang, Michel Galley, Jianfeng Gao* · ([huggingface](https://huggingface.co/datasets/AI4Math/MathVista)) · ([mathvista.github](https://mathvista.github.io/))

### Other
- [千亿级、数学专用，MathGPT大模型开始公测了 | 机器之心](https://www.jiqizhixin.com/articles/2023-08-24-2)

## Self correction
- **V-STaR: Training Verifiers for Self-Taught Reasoners**, `arXiv, 2402.06457`, [arxiv](http://arxiv.org/abs/2402.06457v2), [pdf](http://arxiv.org/pdf/2402.06457v2.pdf), cication: [**19**](https://scholar.google.com/scholar?cites=12044817922319023148&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Arian Hosseini, Xingdi Yuan, Nikolay Malkin, Aaron Courville, Alessandro Sordoni, Rishabh Agarwal*

	 · ([x](https://x.com/_philschmid/status/1835936839057740043))
- **Step-On-Feet Tuning: Scaling Self-Alignment of LLMs via Bootstrapping**, `arXiv, 2402.07610`, [arxiv](http://arxiv.org/abs/2402.07610v1), [pdf](http://arxiv.org/pdf/2402.07610v1.pdf), cication: [**-1**](None)

	 *Haoyu Wang, Guozheng Ma, Ziqiao Meng, Zeyu Qin, Li Shen, Zhong Zhang, Bingzhe Wu, Liu Liu, Yatao Bian, Tingyang Xu*
- **Can Large Language Models Really Improve by Self-critiquing Their Own
  Plans?**, `arXiv, 2310.08118`, [arxiv](http://arxiv.org/abs/2310.08118v1), [pdf](http://arxiv.org/pdf/2310.08118v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=4626190714577979337&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Karthik Valmeekam, Matthew Marquez, Subbarao Kambhampati* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-25-12))
- **Self-RAG: Learning to Retrieve, Generate, and Critique through
  Self-Reflection**, `arXiv, 2310.11511`, [arxiv](http://arxiv.org/abs/2310.11511v1), [pdf](http://arxiv.org/pdf/2310.11511v1.pdf), cication: [**-1**](None)

	 *Akari Asai, Zeqiu Wu, Yizhong Wang, Avirup Sil, Hannaneh Hajishirzi*
- **GPT-4 Doesn't Know It's Wrong: An Analysis of Iterative Prompting for
  Reasoning Problems**, `arXiv, 2310.12397`, [arxiv](http://arxiv.org/abs/2310.12397v1), [pdf](http://arxiv.org/pdf/2310.12397v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=9992342853277132205&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Kaya Stechly, Matthew Marquez, Subbarao Kambhampati* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652394497&idx=1&sn=e209092f1b524667aaa1e7c8725b690c))
- **Shepherd: A Critic for Language Model Generation**, `arXiv, 2308.04592`, [arxiv](http://arxiv.org/abs/2308.04592v1), [pdf](http://arxiv.org/pdf/2308.04592v1.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=7835216224974647817&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tianlu Wang, Ping Yu, Xiaoqing Ellen Tan, Sean O'Brien, Ramakanth Pasunuru, Jane Dwivedi-Yu, Olga Golovneva, Luke Zettlemoyer, Maryam Fazel-Zarandi, Asli Celikyilmaz* · ([shepherd](https://github.com/facebookresearch/shepherd) - facebookresearch) ![Star](https://img.shields.io/github/stars/facebookresearch/shepherd.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652366759&idx=3&sn=f183f4c8080a338c4c9fad0f026b14af))

## Prompting
- **Minstrel: Structural Prompt Generation with Multi-Agents Coordination
  for Non-AI Experts**, `arXiv, 2409.13449`, [arxiv](http://arxiv.org/abs/2409.13449v1), [pdf](http://arxiv.org/pdf/2409.13449v1.pdf), cication: [**-1**](None)

	 *Ming Wang, Yuanzhong Liu, Xiaoyu Liang, Yijie Huang, Daling Wang, Xiaocui Yang, Sijia Shen, Shi Feng, Xiaoming Zhang, Chaofeng Guan*
- [**sammo**](https://github.com/microsoft/sammo) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/sammo.svg?style=social&label=Star)

	 *A library for prompt engineering and optimization (SAMMO = Structure-aware Multi-Objective Metaprompt Optimization)*
- **Superposition Prompting: Improving and Accelerating Retrieval-Augmented
  Generation**, `arXiv, 2404.06910`, [arxiv](http://arxiv.org/abs/2404.06910v2), [pdf](http://arxiv.org/pdf/2404.06910v2.pdf), cication: [**-1**](None)

	 *Thomas Merth, Qichen Fu, Mohammad Rastegari, Mahyar Najibi* · ([ml-superposition-prompting](https://github.com/apple/ml-superposition-prompting) - apple) ![Star](https://img.shields.io/github/stars/apple/ml-superposition-prompting.svg?style=social&label=Star)
- [**ell**](https://github.com/MadcowD/ell) - MadcowD ![Star](https://img.shields.io/github/stars/MadcowD/ell.svg?style=social&label=Star)

	 *A language model programming library.*
- **PAS: Data-Efficient Plug-and-Play Prompt Augmentation System**, `arXiv, 2407.06027`, [arxiv](http://arxiv.org/abs/2407.06027v1), [pdf](http://arxiv.org/pdf/2407.06027v1.pdf), cication: [**-1**](None)

	 *Miao Zheng, Hao Liang, Fan Yang, Haoze Sun, Tianpeng Li, Lingchu Xiong, Yan Zhang, Yozhen Wu, Kun Li, Yanjun Sheng*
- **AdvPrompter: Fast Adaptive Adversarial Prompting for LLMs**, `arXiv, 2404.16873`, [arxiv](http://arxiv.org/abs/2404.16873v1), [pdf](http://arxiv.org/pdf/2404.16873v1.pdf), cication: [**-1**](None)

	 *Anselm Paulus, Arman Zharmagambetov, Chuan Guo, Brandon Amos, Yuandong Tian*
- **Automatic Prompt Selection for Large Language Models**, `arXiv, 2404.02717`, [arxiv](http://arxiv.org/abs/2404.02717v1), [pdf](http://arxiv.org/pdf/2404.02717v1.pdf), cication: [**-1**](None)

	 *Viet-Tung Do, Van-Khanh Hoang, Duy-Hung Nguyen, Shahab Sabahi, Jeff Yang, Hajime Hotta, Minh-Tien Nguyen, Hung Le*
- [**aici**](https://github.com/microsoft/aici) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/aici.svg?style=social&label=Star)

	 *AICI: Prompts as (Wasm) Programs*
- **Supervisory Prompt Training**, `arXiv, 2403.18051`, [arxiv](http://arxiv.org/abs/2403.18051v1), [pdf](http://arxiv.org/pdf/2403.18051v1.pdf), cication: [**-1**](None)

	 *Jean Ghislain Billa, Min Oh, Liang Du*
- [**gpt-prompt-engineer**](https://github.com/mshumer/gpt-prompt-engineer) - mshumer ![Star](https://img.shields.io/github/stars/mshumer/gpt-prompt-engineer.svg?style=social&label=Star)
- [**ChainForge**](https://github.com/ianarawjo/ChainForge) - ianarawjo ![Star](https://img.shields.io/github/stars/ianarawjo/ChainForge.svg?style=social&label=Star)

	 *An open-source visual programming environment for battle-testing prompts to LLMs.*
- **LLMLingua-2: Data Distillation for Efficient and Faithful Task-Agnostic
  Prompt Compression**, `arXiv, 2403.12968`, [arxiv](http://arxiv.org/abs/2403.12968v1), [pdf](http://arxiv.org/pdf/2403.12968v1.pdf), cication: [**-1**](None)

	 *Zhuoshi Pan, Qianhui Wu, Huiqiang Jiang, Menglin Xia, Xufang Luo, Jue Zhang, Qingwei Lin, Victor Rühle, Yuqing Yang, Chin-Yew Lin*
- **The Unreasonable Effectiveness of Eccentric Automatic Prompts**, `arXiv, 2402.10949`, [arxiv](http://arxiv.org/abs/2402.10949v2), [pdf](http://arxiv.org/pdf/2402.10949v2.pdf), cication: [**-1**](None)

	 *Rick Battle, Teja Gollapudi* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-03-18-6))
- **User-LLM: Efficient LLM Contextualization with User Embeddings**, `arXiv, 2402.13598`, [arxiv](http://arxiv.org/abs/2402.13598v1), [pdf](http://arxiv.org/pdf/2402.13598v1.pdf), cication: [**-1**](None)

	 *Lin Ning, Luyang Liu, Jiaxing Wu, Neo Wu, Devora Berlowitz, Sushant Prakash, Bradley Green, Shawn O'Banion, Jun Xie*
- [**autoprompt**](https://github.com/eladlev/autoprompt) - eladlev ![Star](https://img.shields.io/github/stars/eladlev/autoprompt.svg?style=social&label=Star)

	 *A framework for prompt tuning using Intent-based Prompt Calibration*
- [**LangGPT**](https://github.com/EmbraceAGI/LangGPT) - EmbraceAGI ![Star](https://img.shields.io/github/stars/EmbraceAGI/LangGPT.svg?style=social&label=Star)

	 *LangGPT: Empowering everyone to become a prompt expert!🚀 Structured Prompt，Language of GPT, 结构化提示词，结构化Prompt*
- **Meta-Prompting: Enhancing Language Models with Task-Agnostic Scaffolding**, `arXiv, 2401.12954`, [arxiv](http://arxiv.org/abs/2401.12954v1), [pdf](http://arxiv.org/pdf/2401.12954v1.pdf), cication: [**-1**](None)

	 *Mirac Suzgun, Adam Tauman Kalai*

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652438343&idx=1&sn=ba3fb0089b1e8c14f2744d5559da8223))
- **Principled Instructions Are All You Need for Questioning LLaMA-1/2,
  GPT-3.5/4**, `arXiv, 2312.16171`, [arxiv](http://arxiv.org/abs/2312.16171v1), [pdf](http://arxiv.org/pdf/2312.16171v1.pdf), cication: [**-1**](None)

	 *Sondos Mahmoud Bsharat, Aidar Myrzakhan, Zhiqiang Shen*

	 · ([ATLAS](https://github.com/VILA-Lab/ATLAS) - VILA-Lab) ![Star](https://img.shields.io/github/stars/VILA-Lab/ATLAS.svg?style=social&label=Star)
- [**promptbase**](https://github.com/microsoft/promptbase) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/promptbase.svg?style=social&label=Star)

	 *All things prompt engineering*
- [**plum**](https://github.com/research4pan/plum) - research4pan ![Star](https://img.shields.io/github/stars/research4pan/plum.svg?style=social&label=Star)

	 *Prompt Learning using Metaheuristics*
- **Contrastive Chain-of-Thought Prompting**, `arXiv, 2311.09277`, [arxiv](http://arxiv.org/abs/2311.09277v1), [pdf](http://arxiv.org/pdf/2311.09277v1.pdf), cication: [**-1**](None)

	 *Yew Ken Chia, Guizhen Chen, Luu Anh Tuan, Soujanya Poria, Lidong Bing*
- **Fast Chain-of-Thought: A Glance of Future from Parallel Decoding Leads
  to Answers Faster**, `arXiv, 2311.08263`, [arxiv](http://arxiv.org/abs/2311.08263v1), [pdf](http://arxiv.org/pdf/2311.08263v1.pdf), cication: [**-1**](None)

	 *Hongxuan Zhang, Zhining Liu, Jiaqi Zheng, Chenyi Zhuang, Jinjie Gu, Guihai Chen*
- **Prompt Engineering a Prompt Engineer**, `arXiv, 2311.05661`, [arxiv](http://arxiv.org/abs/2311.05661v1), [pdf](http://arxiv.org/pdf/2311.05661v1.pdf), cication: [**-1**](None)

	 *Qinyuan Ye, Maxamed Axmed, Reid Pryzant, Fereshte Khani*
- **TopicGPT: A Prompt-based Topic Modeling Framework**, `arXiv, 2311.01449`, [arxiv](http://arxiv.org/abs/2311.01449v1), [pdf](http://arxiv.org/pdf/2311.01449v1.pdf), cication: [**-1**](None)

	 *Chau Minh Pham, Alexander Hoyle, Simeng Sun, Mohit Iyyer* · ([topicgpt](https://github.com/chtmp223/topicgpt) - chtmp223) ![Star](https://img.shields.io/github/stars/chtmp223/topicgpt.svg?style=social&label=Star)
- **Quantifying Language Models' Sensitivity to Spurious Features in Prompt
  Design or: How I learned to start worrying about prompt formatting**, `arXiv, 2310.11324`, [arxiv](http://arxiv.org/abs/2310.11324v1), [pdf](http://arxiv.org/pdf/2310.11324v1.pdf), cication: [**-1**](None)

	 *Melanie Sclar, Yejin Choi, Yulia Tsvetkov, Alane Suhr*
- **Eliciting Human Preferences with Language Models**, `arXiv, 2310.11589`, [arxiv](http://arxiv.org/abs/2310.11589v1), [pdf](http://arxiv.org/pdf/2310.11589v1.pdf), cication: [**-1**](None)

	 *Belinda Z. Li, Alex Tamkin, Noah Goodman, Jacob Andreas* · ([qbitai](https://www.qbitai.com/2023/10/91326.html))
- **Meta-CoT: Generalizable Chain-of-Thought Prompting in Mixed-task
  Scenarios with Large Language Models**, `arXiv, 2310.06692`, [arxiv](http://arxiv.org/abs/2310.06692v2), [pdf](http://arxiv.org/pdf/2310.06692v2.pdf), cication: [**-1**](None)

	 *Anni Zou, Zhuosheng Zhang, Hai Zhao, Xiangru Tang*
- [**ChatGPT-AutoExpert**](https://github.com/spdustin/ChatGPT-AutoExpert) - spdustin ![Star](https://img.shields.io/github/stars/spdustin/ChatGPT-AutoExpert.svg?style=social&label=Star)

	 *🚀🧠💬 Supercharged Custom Instructions for ChatGPT (non-coding) and ChatGPT Advanced Data Analysis (coding).*
- **VPA: Fully Test-Time Visual Prompt Adaptation**, `proceedings of the 31st acm international conference on multimedia, 2023`, [arxiv](http://arxiv.org/abs/2309.15251v1), [pdf](http://arxiv.org/pdf/2309.15251v1.pdf), cication: [**-1**](None)

	 *Jiachen Sun, Mark Ibrahim, Melissa Hall, Ivan Evtimov, Z. Morley Mao, Cristian Canton Ferrer, Caner Hazirbas*
- **Connecting Large Language Models with Evolutionary Algorithms Yields
  Powerful Prompt Optimizers**, `arXiv, 2309.08532`, [arxiv](http://arxiv.org/abs/2309.08532v1), [pdf](http://arxiv.org/pdf/2309.08532v1.pdf), cication: [**8**](https://scholar.google.com/scholar?cites=5062683469637672606&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Qingyan Guo, Rui Wang, Junliang Guo, Bei Li, Kaitao Song, Xu Tan, Guoqing Liu, Jiang Bian, Yujiu Yang* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652386443&idx=2&sn=7b119047143a8c7269762abbde872b9c&poc_token=HN98IGWjo79E6PJ2NEsKaiMszu87rPuYJh2ajobG))
- **From Sparse to Dense: GPT-4 Summarization with Chain of Density
  Prompting**, `arXiv, 2309.04269`, [arxiv](http://arxiv.org/abs/2309.04269v1), [pdf](http://arxiv.org/pdf/2309.04269v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=12499531921270454735&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Griffin Adams, Alexander Fabbri, Faisal Ladhak, Eric Lehman, Noémie Elhadad* · ([huggingface](https://huggingface.co/datasets/griffin/chain_of_density))
- **Structured Chain-of-Thought Prompting for Code Generation**, `arXiv, 2305.06599`, [arxiv](http://arxiv.org/abs/2305.06599v3), [pdf](http://arxiv.org/pdf/2305.06599v3.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=13875879814754245021&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jia Li, Ge Li, Yongmin Li, Zhi Jin*
- **Large Language Models Understand and Can be Enhanced by Emotional
  Stimuli**, `arXiv, 2307.11760`, [arxiv](http://arxiv.org/abs/2307.11760v7), [pdf](http://arxiv.org/pdf/2307.11760v7.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=5825846437972489885&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Cheng Li, Jindong Wang, Yixuan Zhang, Kaijie Zhu, Wenxin Hou, Jianxun Lian, Fang Luo, Qiang Yang, Xing Xie*
- [**thor-isa**](https://github.com/scofield7419/thor-isa) - scofield7419 ![Star](https://img.shields.io/github/stars/scofield7419/thor-isa.svg?style=social&label=Star)

	 *Codes for ACL 2023 paper: Reasoning Implicit Sentiment with Chain-of-Thought Prompting*
- [**awesome-chatgpt-prompts-zh**](https://github.com/PlexPt/awesome-chatgpt-prompts-zh) - PlexPt ![Star](https://img.shields.io/github/stars/PlexPt/awesome-chatgpt-prompts-zh.svg?style=social&label=Star)

	 *ChatGPT 中文调教指南。各种场景使用指南。学习怎么让它听你的话。*
- **InstructZero: Efficient Instruction Optimization for Black-Box Large
  Language Models**, `arXiv, 2306.03082`, [arxiv](http://arxiv.org/abs/2306.03082v2), [pdf](http://arxiv.org/pdf/2306.03082v2.pdf), cication: [**8**](https://scholar.google.com/scholar?cites=11656455885715424620&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lichang Chen, Jiuhai Chen, Tom Goldstein, Heng Huang, Tianyi Zhou* · ([instructzero](https://github.com/lichang-chen/instructzero) - lichang-chen) ![Star](https://img.shields.io/github/stars/lichang-chen/instructzero.svg?style=social&label=Star)
- **PromptBench: Towards Evaluating the Robustness of Large Language Models
  on Adversarial Prompts**, `arXiv, 2306.04528`, [arxiv](http://arxiv.org/abs/2306.04528v4), [pdf](http://arxiv.org/pdf/2306.04528v4.pdf), cication: [**32**](https://scholar.google.com/scholar?cites=6727691362756502405&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Kaijie Zhu, Jindong Wang, Jiaheng Zhou, Zichen Wang, Hao Chen, Yidong Wang, Linyi Yang, Wei Ye, Yue Zhang, Neil Zhenqiang Gong*
- **Deductive Verification of Chain-of-Thought Reasoning**, `arXiv, 2306.03872`, [arxiv](http://arxiv.org/abs/2306.03872v3), [pdf](http://arxiv.org/pdf/2306.03872v3.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=3205644836692572249&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhan Ling, Yunhao Fang, Xuanlin Li, Zhiao Huang, Mingu Lee, Roland Memisevic, Hao Su*
- **Chain-of-Thought Hub: A Continuous Effort to Measure Large Language
  Models' Reasoning Performance**, `arXiv, 2305.17306`, [arxiv](http://arxiv.org/abs/2305.17306v1), [pdf](http://arxiv.org/pdf/2305.17306v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=2470699605167186448&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yao Fu, Litu Ou, Mingyu Chen, Yuhao Wan, Hao Peng, Tushar Khot* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652336472&idx=4&sn=df92f87c972bde0eeb5cf8604b599357))
- **Graph of Thoughts: Solving Elaborate Problems with Large Language Models**, `arXiv, 2308.09687`, [arxiv](http://arxiv.org/abs/2308.09687v2), [pdf](http://arxiv.org/pdf/2308.09687v2.pdf), cication: [**32**](https://scholar.google.com/scholar?cites=17683626683142997620&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Maciej Besta, Nils Blach, Ales Kubicek, Robert Gerstenberger, Lukas Gianinazzi, Joanna Gajda, Tomasz Lehmann, Michal Podstawski, Hubert Niewiadomski, Piotr Nyczyk* · ([graph-of-thoughts](https://github.com/spcl/graph-of-thoughts) - spcl) ![Star](https://img.shields.io/github/stars/spcl/graph-of-thoughts.svg?style=social&label=Star) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-25-3))

### Other
- [Apple Intelligence instructions](https://www.theverge.com/2024/8/5/24213861/apple-intelligence-instructions-macos-15-1-sequoia-beta)
- [Modern Advances in Prompt Engineering](https://cameronrwolfe.substack.com/p/modern-advances-in-prompt-engineering)
- [Improving Prompt Consistency with Structured Generations](https://huggingface.co/blog/evaluation-structured-outputs)
- [Lessons after a half-billion GPT tokens - Ken Kantzer's Blog](https://kenkantzer.com/lessons-after-a-half-billion-gpt-tokens)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-04-19-13))
- [How Chain-of-Thought Reasoning Helps Neural Networks Compute | Quanta Magazine](https://www.quantamagazine.org/how-chain-of-thought-reasoning-helps-neural-networks-compute-20240321/)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247633311&idx=3&sn=2d77962dd4951e03b03b84cd3c969bb7))
- [Stanford CS25: V3 I Beyond LLMs: Agents, Emergent Abilities, Intermediate-Guided Reasoning, BabyLM - YouTube](https://youtu.be/ylEk1TE1uBo?list=PLoROMvodv4rNiJRchCzutFw5ItR_Z27CM&t=469)
- [Steering at the Frontier: Extending the Power of Prompting - Microsoft Research](https://www.microsoft.com/en-us/research/blog/steering-at-the-frontier-extending-the-power-of-prompting/)

- [Claude才是真正的Open AI？连系统提示词都公布了！](https://mp.weixin.qq.com/s/A1RCQY4bY8H9JZ2G06qADQ)
- [万字长文 - LLM prompt tutorial](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247634224&idx=1&sn=d08626602cdeba68c01761b86bbddc1b)
- [Meta官方的Prompt工程指南：Llama 2这样用更高效 | 机器之心](https://www.jiqizhixin.com/articles/2024-01-29-13)
- [OpenAI官方的Prompt工程指南：你可以这么玩ChatGPT | 机器之心](https://www.jiqizhixin.com/articles/2023-12-18-17)
- [我用 ChatGPT 寫了一個 ChatGPT 指令大全網站 - 軟體工程師面試、職涯、新加坡生活分享 - ExplainThis](https://www.explainthis.io/zh-hant/chatgpt/website)
- [ChatGPT 詠唱案例懶人包 - 超過 40 個現實世界的應用範例 (持續更新) - 雷司紀的小道投資 raysky](https://www.rayskyinvest.com/96682/chatgpt-examples)

## In context learning
- **Learning vs Retrieval: The Role of In-Context Examples in Regression
  with LLMs**, `arXiv, 2409.04318`, [arxiv](http://arxiv.org/abs/2409.04318v1), [pdf](http://arxiv.org/pdf/2409.04318v1.pdf), cication: [**-1**](None)

	 *Aliakbar Nafar, Kristen Brent Venable, Parisa Kordjamshidi*
- **ContextCite: Attributing Model Generation to Context**, `arXiv, 2409.00729`, [arxiv](http://arxiv.org/abs/2409.00729v1), [pdf](http://arxiv.org/pdf/2409.00729v1.pdf), cication: [**-1**](None)

	 *Benjamin Cohen-Wang, Harshay Shah, Kristian Georgiev, Aleksander Madry* · ([context-cite](https://github.com/MadryLab/context-cite) - MadryLab) ![Star](https://img.shields.io/github/stars/MadryLab/context-cite.svg?style=social&label=Star)
- **Learning to grok: Emergence of in-context learning and skill composition
  in modular arithmetic tasks**, `arXiv, 2406.02550`, [arxiv](http://arxiv.org/abs/2406.02550v1), [pdf](http://arxiv.org/pdf/2406.02550v1.pdf), cication: [**-1**](None)

	 *Tianyu He, Darshil Doshi, Aritra Das, Andrey Gromov*
- **LLM In-Context Recall is Prompt Dependent**, `arXiv, 2404.08865`, [arxiv](http://arxiv.org/abs/2404.08865v1), [pdf](http://arxiv.org/pdf/2404.08865v1.pdf), cication: [**-1**](None)

	 *Daniel Machlab, Rick Battle*
- **Many-Shot In-Context Learning**, `arXiv, 2404.11018`, [arxiv](http://arxiv.org/abs/2404.11018v1), [pdf](http://arxiv.org/pdf/2404.11018v1.pdf), cication: [**-1**](None)

	 *Rishabh Agarwal, Avi Singh, Lei M. Zhang, Bernd Bohnet, Stephanie Chan, Ankesh Anand, Zaheer Abbas, Azade Nova, John D. Co-Reyes, Eric Chu*
- **Can large language models explore in-context?**, `arXiv, 2403.15371`, [arxiv](http://arxiv.org/abs/2403.15371v1), [pdf](http://arxiv.org/pdf/2403.15371v1.pdf), cication: [**-1**](None)

	 *Akshay Krishnamurthy, Keegan Harris, Dylan J. Foster, Cyril Zhang, Aleksandrs Slivkins*
	- `contemporary Large Language Models, including GPT-3.5, GPT-4, and Llama2, do not reliably engage in exploratory behavior in multi-armed bandit environments without significant interventions`
- **In-Context Principle Learning from Mistakes**, `arXiv, 2402.05403`, [arxiv](http://arxiv.org/abs/2402.05403v2), [pdf](http://arxiv.org/pdf/2402.05403v2.pdf), cication: [**-1**](None)

	 *Tianjun Zhang, Aman Madaan, Luyu Gao, Steven Zheng, Swaroop Mishra, Yiming Yang, Niket Tandon, Uri Alon*
- **Towards Truly Zero-shot Compositional Visual Reasoning with LLMs as
  Programmers**, `arXiv, 2401.01974`, [arxiv](http://arxiv.org/abs/2401.01974v1), [pdf](http://arxiv.org/pdf/2401.01974v1.pdf), cication: [**-1**](None)

	 *Aleksandar Stanić, Sergi Caelles, Michael Tschannen*
- **Supervised Knowledge Makes Large Language Models Better In-context
  Learners**, `arXiv, 2312.15918`, [arxiv](http://arxiv.org/abs/2312.15918v1), [pdf](http://arxiv.org/pdf/2312.15918v1.pdf), cication: [**-1**](None)

	 *Linyi Yang, Shuibai Zhang, Zhuohao Yu, Guangsheng Bao, Yidong Wang, Jindong Wang, Ruochen Xu, Wei Ye, Xing Xie, Weizhu Chen*
- **In-Context Learning with Iterative Demonstration Selection**, `arXiv, 2310.09881`, [arxiv](http://arxiv.org/abs/2310.09881v2), [pdf](http://arxiv.org/pdf/2310.09881v2.pdf), cication: [**-1**](None)

	 *Chengwei Qin, Aston Zhang, Anirudh Dagar, Wenming Ye* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495177&idx=2&sn=fe8353efed16a81e35462be06d5a6cea&poc_token=HE6fdWWjA3UlhR8UcCAzGYGsTFLzGAxqYc3EV_8T))
- **In-Context Learning Creates Task Vectors**, `arXiv, 2310.15916`, [arxiv](http://arxiv.org/abs/2310.15916v1), [pdf](http://arxiv.org/pdf/2310.15916v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=587881729416371854&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Roee Hendel, Mor Geva, Amir Globerson*
- **Ambiguity-Aware In-Context Learning with Large Language Models**, `arXiv, 2309.07900`, [arxiv](http://arxiv.org/abs/2309.07900v1), [pdf](http://arxiv.org/pdf/2309.07900v1.pdf), cication: [**-1**](None)

	 *Lingyu Gao, Aditi Chaudhary, Krishna Srinivasan, Kazuma Hashimoto, Karthik Raman, Michael Bendersky*
- **FIAT: Fusing learning paradigms with Instruction-Accelerated Tuning**, `arXiv, 2309.04663`, [arxiv](http://arxiv.org/abs/2309.04663v2), [pdf](http://arxiv.org/pdf/2309.04663v2.pdf), cication: [**-1**](None)

	 *Xinyi Wang, John Wieting, Jonathan H. Clark*
- **RAVEN: In-Context Learning with Retrieval Augmented Encoder-Decoder
  Language Models**, `arXiv, 2308.07922`, [arxiv](http://arxiv.org/abs/2308.07922v1), [pdf](http://arxiv.org/pdf/2308.07922v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=3988423161346149970&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jie Huang, Wei Ping, Peng Xu, Mohammad Shoeybi, Kevin Chen-Chuan Chang, Bryan Catanzaro*
- **CausalLM is not optimal for in-context learning**, `arXiv, 2308.06912`, [arxiv](http://arxiv.org/abs/2308.06912v2), [pdf](http://arxiv.org/pdf/2308.06912v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=10831266460306494065&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Nan Ding, Tomer Levinboim, Jialin Wu, Sebastian Goodman, Radu Soricut*
- **FLIRT: Feedback Loop In-context Red Teaming**, `arXiv, 2308.04265`, [arxiv](http://arxiv.org/abs/2308.04265v1), [pdf](http://arxiv.org/pdf/2308.04265v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=3679628265599247085&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ninareh Mehrabi, Palash Goyal, Christophe Dupuy, Qian Hu, Shalini Ghosh, Richard Zemel, Kai-Wei Chang, Aram Galstyan, Rahul Gupta*
- **Skills-in-Context Prompting: Unlocking Compositionality in Large
  Language Models**, `arXiv, 2308.00304`, [arxiv](http://arxiv.org/abs/2308.00304v2), [pdf](http://arxiv.org/pdf/2308.00304v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=12576437854212500464&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jiaao Chen, Xiaoman Pan, Dian Yu, Kaiqiang Song, Xiaoyang Wang, Dong Yu, Jianshu Chen*
- **Large Language Models as General Pattern Machines**, `arXiv, 2307.04721`, [arxiv](http://arxiv.org/abs/2307.04721v2), [pdf](http://arxiv.org/pdf/2307.04721v2.pdf), cication: [**23**](https://scholar.google.com/scholar?cites=9776723022121320548&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Suvir Mirchandani, Fei Xia, Pete Florence, Brian Ichter, Danny Driess, Montserrat Gonzalez Arenas, Kanishka Rao, Dorsa Sadigh, Andy Zeng*
- **Trained Transformers Learn Linear Models In-Context**, `arXiv, 2306.09927`, [arxiv](http://arxiv.org/abs/2306.09927v3), [pdf](http://arxiv.org/pdf/2306.09927v3.pdf), cication: [**26**](https://scholar.google.com/scholar?cites=9948501466759463012&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ruiqi Zhang, Spencer Frei, Peter L. Bartlett* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-29-3))
- **Learning to Retrieve In-Context Examples for Large Language Models**, `arXiv, 2307.07164`, [arxiv](http://arxiv.org/abs/2307.07164v1), [pdf](http://arxiv.org/pdf/2307.07164v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=16148148717507486356&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Liang Wang, Nan Yang, Furu Wei*
- **Understanding In-Context Learning via Supportive Pretraining Data**, `arXiv, 2306.15091`, [arxiv](http://arxiv.org/abs/2306.15091v1), [pdf](http://arxiv.org/pdf/2306.15091v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=3489214222287357008&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xiaochuang Han, Daniel Simig, Todor Mihaylov, Yulia Tsvetkov, Asli Celikyilmaz, Tianlu Wang*

### Other
- [大模型Fewshot推理如何选择更好的示例](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495177&idx=2&sn=fe8353efed16a81e35462be06d5a6cea&poc_token=HE6fdWWjA3UlhR8UcCAzGYGsTFLzGAxqYc3EV_8T)

## Knowledge
- [**fact-finder**](https://github.com/chrschy/fact-finder) - chrschy ![Star](https://img.shields.io/github/stars/chrschy/fact-finder.svg?style=social&label=Star)
- [**Triplex**](https://huggingface.co/SciPhi/Triplex) - SciPhi 🤗
- **StructLM: Towards Building Generalist Models for Structured Knowledge
  Grounding**, `arXiv, 2402.16671`, [arxiv](http://arxiv.org/abs/2402.16671v1), [pdf](http://arxiv.org/pdf/2402.16671v1.pdf), cication: [**-1**](None)

	 *Alex Zhuang, Ge Zhang, Tianyu Zheng, Xinrun Du, Junjie Wang, Weiming Ren, Stephen W. Huang, Jie Fu, Xiang Yue, Wenhu Chen*
- **Think-on-Graph: Deep and Responsible Reasoning of Large Language Model
  on Knowledge Graph**, `arXiv, 2307.07697`, [arxiv](http://arxiv.org/abs/2307.07697v5), [pdf](http://arxiv.org/pdf/2307.07697v5.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=17400716338910902015&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jiashuo Sun, Chengjin Xu, Lumingyuan Tang, Saizhuo Wang, Chen Lin, Yeyun Gong, Lionel M. Ni, Heung-Yeung Shum, Jian Guo* · ([ToG](https://github.com/IDEA-FinAI/ToG) - IDEA-FinAI) ![Star](https://img.shields.io/github/stars/IDEA-FinAI/ToG.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652411844&idx=5&sn=41f06f5d9101904abad348a9128fab96))
- **Unifying Large Language Models and Knowledge Graphs: A Roadmap**, `arXiv, 2306.08302`, [arxiv](http://arxiv.org/abs/2306.08302v2), [pdf](http://arxiv.org/pdf/2306.08302v2.pdf), cication: [**53**](https://scholar.google.com/scholar?cites=11970242962650523595&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shirui Pan, Linhao Luo, Yufei Wang, Chen Chen, Jiapu Wang, Xindong Wu*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-03-6))
- **KoLA: Carefully Benchmarking World Knowledge of Large Language Models**, `arXiv, 2306.09296`, [arxiv](http://arxiv.org/abs/2306.09296v2), [pdf](http://arxiv.org/pdf/2306.09296v2.pdf), cication: [**14**](https://scholar.google.com/scholar?cites=13925067843687558202&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jifan Yu, Xiaozhi Wang, Shangqing Tu, Shulin Cao, Daniel Zhang-Li, Xin Lv, Hao Peng, Zijun Yao, Xiaohan Zhang, Hanming Li*
 
### Other
- [再看知识图谱增强大模型问答范式](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495228&idx=2&sn=13e9d1012a44b56ee2d7282d636d4216)
- [面向知识图谱构建的垂直微调大模型：KnowLM、TechGPT](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494182&idx=2&sn=5db8ad3a148ce6e2db707f790960ed54)

## Tutorials
- [**courses**](https://github.com/anthropics/courses) - anthropics ![Star](https://img.shields.io/github/stars/anthropics/courses.svg?style=social&label=Star)

	 *Anthropic's educational courses*
- [Prompt Engineering Guide | Prompt Engineering Guide](https://www.promptingguide.ai/)
- [**prompt-engineering-for-developers**](https://github.com/datawhalechina/prompt-engineering-for-developers) - datawhalechina ![Star](https://img.shields.io/github/stars/datawhalechina/prompt-engineering-for-developers.svg?style=social&label=Star)

	 *吴恩达大模型系列课程中文版，包括《Prompt Engineering》、《Building System》和《LangChain》*

## Extra reference
- [**system-2-research**](https://github.com/open-thought/system-2-research) - open-thought ![Star](https://img.shields.io/github/stars/open-thought/system-2-research.svg?style=social&label=Star)
- [**Awesome-Reasoning-Foundation-Models**](https://github.com/reasoning-survey/Awesome-Reasoning-Foundation-Models) - reasoning-survey ![Star](https://img.shields.io/github/stars/reasoning-survey/Awesome-Reasoning-Foundation-Models.svg?style=social&label=Star)

	 *✨✨Latest Papers and Benchmarks in Reasoning with Foundation Models*
- [**OpenPrompt**](https://github.com/thunlp/OpenPrompt) - thunlp ![Star](https://img.shields.io/github/stars/thunlp/OpenPrompt.svg?style=social&label=Star)

	 *An Open-Source Framework for Prompt-Learning.*
- [**Awesome_Prompting_Papers_in_Computer_Vision**](https://github.com/ttengwang/Awesome_Prompting_Papers_in_Computer_Vision) - ttengwang ![Star](https://img.shields.io/github/stars/ttengwang/Awesome_Prompting_Papers_in_Computer_Vision.svg?style=social&label=Star)

	 *A curated list of prompt-based paper in computer vision and vision-language learning.*
- [**PromptPapers**](https://github.com/thunlp/PromptPapers) - thunlp ![Star](https://img.shields.io/github/stars/thunlp/PromptPapers.svg?style=social&label=Star)

	 *Must-read papers on prompt-based tuning for pre-trained language models.*
- [**self-correction-llm-papers**](https://github.com/teacherpeterpan/self-correction-llm-papers) - teacherpeterpan ![Star](https://img.shields.io/github/stars/teacherpeterpan/self-correction-llm-papers.svg?style=social&label=Star)

	 *This is a collection of research papers for Self-Correcting Large Language Models with Automated Feedback.*