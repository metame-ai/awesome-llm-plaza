# Awesome llm training

- [Awesome llm training](#awesome-llm-training)
	- [Pretrain](#pretrain)
		- [Other](#other)
	- [Alignment](#alignment)
		- [Survey](#survey)
		- [Paper \& Projects](#paper--projects)
		- [Other](#other-1)
	- [Scaling](#scaling)
		- [Other](#other-2)
	- [Finetuning](#finetuning)
	- [Architectures](#architectures)
	- [Optimization](#optimization)
	- [Ensemble](#ensemble)
	- [MoE](#moe)
	- [Toolkits](#toolkits)
	- [Misc](#misc)
	- [Courses](#courses)
	- [Other](#other-3)
	- [Extra reference](#extra-reference)


## Pretrain
- **MindLLM: Pre-training Lightweight Large Language Model from Scratch,
  Evaluations and Domain Applications**, `arXiv, 2310.15777`, [arxiv](http://arxiv.org/abs/2310.15777v2), [pdf](http://arxiv.org/pdf/2310.15777v2.pdf), cication: [**-1**](None)

	 *Yizhe Yang, Huashan Sun, Jiawei Li, Runheng Liu, Yinghao Li, Yuhang Liu, Heyan Huang, Yang Gao* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-30-5))
- **In-Context Pretraining: Language Modeling Beyond Document Boundaries**, `arXiv, 2310.10638`, [arxiv](http://arxiv.org/abs/2310.10638v3), [pdf](http://arxiv.org/pdf/2310.10638v3.pdf), cication: [**-1**](None)

	 *Weijia Shi, Sewon Min, Maria Lomeli, Chunting Zhou, Margaret Li, Xi Victoria Lin, Noah A. Smith, Luke Zettlemoyer, Scott Yih, Mike Lewis*
- **When Less is More: Investigating Data Pruning for Pretraining LLMs at
  Scale**, `arXiv, 2309.04564`, [arxiv](http://arxiv.org/abs/2309.04564v1), [pdf](http://arxiv.org/pdf/2309.04564v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=1052346843253959809&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Max Marion, Ahmet Üstün, Luiza Pozzobon, Alex Wang, Marzieh Fadaee, Sara Hooker*
- [**metaseq**](https://github.com/facebookresearch/metaseq/blob/main/projects/OPT/chronicles/OPT175B_Logbook.pdf) - facebookresearch ![Star](https://img.shields.io/github/stars/facebookresearch/metaseq.svg?style=social&label=Star)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247524339&idx=4&sn=d2389ee4d55f74472ac0236a849dbd4e)) · ([bilibili](https://www.bilibili.com/video/BV1XT411v7c9/?vd_source=63e5fa02f07bfd58e74de3c6d149e31f))
### Other
- [贫穷让我预训练](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494110&idx=2&sn=52bfbf2d51d1704efc596263bccf23db)

## Alignment
### Survey
- **AI Alignment: A Comprehensive Survey**, `arXiv, 2310.19852`, [arxiv](http://arxiv.org/abs/2310.19852v2), [pdf](http://arxiv.org/pdf/2310.19852v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=2143607605171939849&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jiaming Ji, Tianyi Qiu, Boyuan Chen, Borong Zhang, Hantao Lou, Kaile Wang, Yawen Duan, Zhonghao He, Jiayi Zhou, Zhaowei Zhang*
- **Instruction Tuning for Large Language Models: A Survey**, `arXiv, 2308.10792`, [arxiv](http://arxiv.org/abs/2308.10792v4), [pdf](http://arxiv.org/pdf/2308.10792v4.pdf), cication: [**19**](https://scholar.google.com/scholar?cites=10868294172009796896&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shengyu Zhang, Linfeng Dong, Xiaoya Li, Sen Zhang, Xiaofei Sun, Shuhe Wang, Jiwei Li, Runyi Hu, Tianwei Zhang, Fei Wu* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494678&idx=2&sn=8f5065a21416564f369666744d144452))
- **Large Language Model Alignment: A Survey**, `arXiv, 2309.15025`, [arxiv](http://arxiv.org/abs/2309.15025v1), [pdf](http://arxiv.org/pdf/2309.15025v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=12166333814159585377&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tianhao Shen, Renren Jin, Yufei Huang, Chuang Liu, Weilong Dong, Zishan Guo, Xinwei Wu, Yan Liu, Deyi Xiong* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-07-11)) · ([llm-alignment-survey](https://github.com/Magnetic2014/llm-alignment-survey) - Magnetic2014) ![Star](https://img.shields.io/github/stars/Magnetic2014/llm-alignment-survey.svg?style=social&label=Star)
- **Aligning Large Language Models with Human: A Survey**, `arXiv, 2307.12966`, [arxiv](http://arxiv.org/abs/2307.12966v1), [pdf](http://arxiv.org/pdf/2307.12966v1.pdf), cication: [**29**](https://scholar.google.com/scholar?cites=2762352632434587623&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yufei Wang, Wanjun Zhong, Liangyou Li, Fei Mi, Xingshan Zeng, Wenyong Huang, Lifeng Shang, Xin Jiang, Qun Liu* · ([AlignLLMHumanSurvey](https://github.com/GaryYufei/AlignLLMHumanSurvey) - GaryYufei) ![Star](https://img.shields.io/github/stars/GaryYufei/AlignLLMHumanSurvey.svg?style=social&label=Star)

### Paper & Projects
- [**wizardlm**](https://github.com/nlpxucan/wizardlm) - nlpxucan ![Star](https://img.shields.io/github/stars/nlpxucan/wizardlm.svg?style=social&label=Star)

	 *Family of instruction-following LLMs powered by Evol-Instruct: WizardLM, WizardCoder*
- **Trusted Source Alignment in Large Language Models**, `arXiv, 2311.06697`, [arxiv](http://arxiv.org/abs/2311.06697v1), [pdf](http://arxiv.org/pdf/2311.06697v1.pdf), cication: [**-1**](None)

	 *Vasilisa Bashlovkina, Zhaobin Kuang, Riley Matthews, Edward Clifford, Yennie Jun, William W. Cohen, Simon Baumgartner*
- **Zephyr: Direct Distillation of LM Alignment**, `arXiv, 2310.16944`, [arxiv](http://arxiv.org/abs/2310.16944v1), [pdf](http://arxiv.org/pdf/2310.16944v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=5826276281263581161&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lewis Tunstall, Edward Beeching, Nathan Lambert, Nazneen Rajani, Kashif Rasul, Younes Belkada, Shengyi Huang, Leandro von Werra, Clémentine Fourrier, Nathan Habib* · ([alignment-handbook](https://github.com/huggingface/alignment-handbook) - huggingface) ![Star](https://img.shields.io/github/stars/huggingface/alignment-handbook.svg?style=social&label=Star)

- **Controlled Decoding from Language Models**, `arXiv, 2310.17022`, [arxiv](http://arxiv.org/abs/2310.17022v1), [pdf](http://arxiv.org/pdf/2310.17022v1.pdf), cication: [**-1**](None)

	 *Sidharth Mudgal, Jong Lee, Harish Ganapathy, YaGuang Li, Tao Wang, Yanping Huang, Zhifeng Chen, Heng-Tze Cheng, Michael Collins, Trevor Strohman*
- **Auto-Instruct: Automatic Instruction Generation and Ranking for
  Black-Box Language Models**, `arXiv, 2310.13127`, [arxiv](http://arxiv.org/abs/2310.13127v1), [pdf](http://arxiv.org/pdf/2310.13127v1.pdf), cication: [**-1**](None)

	 *Zhihan Zhang, Shuohang Wang, Wenhao Yu, Yichong Xu, Dan Iter, Qingkai Zeng, Yang Liu, Chenguang Zhu, Meng Jiang*
- **An Emulator for Fine-Tuning Large Language Models using Small Language
  Models**, `arXiv, 2310.12962`, [arxiv](http://arxiv.org/abs/2310.12962v1), [pdf](http://arxiv.org/pdf/2310.12962v1.pdf), cication: [**-1**](None)

	 *Eric Mitchell, Rafael Rafailov, Archit Sharma, Chelsea Finn, Christopher D. Manning*
- **NEFTune: Noisy Embeddings Improve Instruction Finetuning**, `arXiv, 2310.05914`, [arxiv](http://arxiv.org/abs/2310.05914v2), [pdf](http://arxiv.org/pdf/2310.05914v2.pdf), cication: [**-1**](None)

	 *Neel Jain, Ping-yeh Chiang, Yuxin Wen, John Kirchenbauer, Hong-Min Chu, Gowthami Somepalli, Brian R. Bartoldson, Bhavya Kailkhura, Avi Schwarzschild, Aniruddha Saha* · ([qbitai](https://www.qbitai.com/2023/10/91833.html))
- [**alignment-handbook**](https://github.com/huggingface/alignment-handbook) - huggingface ![Star](https://img.shields.io/github/stars/huggingface/alignment-handbook.svg?style=social&label=Star)

	 *Robust recipes for to align language models with human and AI preferences*
- [**Xwin-LM**](https://github.com/Xwin-LM/Xwin-LM) - Xwin-LM ![Star](https://img.shields.io/github/stars/Xwin-LM/Xwin-LM.svg?style=social&label=Star)

	 *Xwin-LM: Powerful, Stable, and Reproducible LLM Alignment* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652380317&idx=2&sn=24c7c3d53878d939d60a53b38c525869))
- **Self-Alignment with Instruction Backtranslation**, `arXiv, 2308.06259`, [arxiv](http://arxiv.org/abs/2308.06259v2), [pdf](http://arxiv.org/pdf/2308.06259v2.pdf), cication: [**13**](https://scholar.google.com/scholar?cites=14196853842712224571&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xian Li, Ping Yu, Chunting Zhou, Timo Schick, Luke Zettlemoyer, Omer Levy, Jason Weston, Mike Lewis* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-15-13))
- **Simple synthetic data reduces sycophancy in large language models**, `arXiv, 2308.03958`, [arxiv](http://arxiv.org/abs/2308.03958v1), [pdf](http://arxiv.org/pdf/2308.03958v1.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=15897243719772431083&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jerry Wei, Da Huang, Yifeng Lu, Denny Zhou, Quoc V. Le*
- [**alignllmhumansurvey**](https://github.com/garyyufei/alignllmhumansurvey) - garyyufei ![Star](https://img.shields.io/github/stars/garyyufei/alignllmhumansurvey.svg?style=social&label=Star)

	 *Aligning Large Language Models with Human: A Survey*
- **RLCD: Reinforcement Learning from Contrast Distillation for Language
  Model Alignment**, `arXiv, 2307.12950`, [arxiv](http://arxiv.org/abs/2307.12950v2), [pdf](http://arxiv.org/pdf/2307.12950v2.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=2633095818852088890&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Kevin Yang, Dan Klein, Asli Celikyilmaz, Nanyun Peng, Yuandong Tian*
- **AlpaGasus: Training A Better Alpaca with Fewer Data**, `arXiv, 2307.08701`, [arxiv](http://arxiv.org/abs/2307.08701v4), [pdf](http://arxiv.org/pdf/2307.08701v4.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=5256571148060741678&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lichang Chen, Shiyang Li, Jun Yan, Hai Wang, Kalpa Gunaratna, Vikas Yadav, Zheng Tang, Vijay Srinivasan, Tianyi Zhou, Heng Huang* · ([lichang-chen.github](https://lichang-chen.github.io/AlpaGasus/))
- **Instruction Mining: When Data Mining Meets Large Language Model
  Finetuning**, `arXiv, 2307.06290`, [arxiv](http://arxiv.org/abs/2307.06290v2), [pdf](http://arxiv.org/pdf/2307.06290v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=18128512597851597026&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yihan Cao, Yanbin Kang, Chi Wang, Lichao Sun*
- **Becoming self-instruct: introducing early stopping criteria for minimal
  instruct tuning**, `arXiv, 2307.03692`, [arxiv](http://arxiv.org/abs/2307.03692v1), [pdf](http://arxiv.org/pdf/2307.03692v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=8663508115372331640&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Waseem AlShikh, Manhal Daaboul, Kirk Goddard, Brock Imel, Kiran Kamble, Parikshith Kulkarni, Melisa Russak*
- **Training Models to Generate, Recognize, and Reframe Unhelpful Thoughts**, `arXiv, 2307.02768`, [arxiv](http://arxiv.org/abs/2307.02768v1), [pdf](http://arxiv.org/pdf/2307.02768v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=8502039692890912470&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Mounica Maddela, Megan Ung, Jing Xu, Andrea Madotto, Heather Foran, Y-Lan Boureau*
- **Goal Representations for Instruction Following: A Semi-Supervised
  Language Interface to Control**, `arXiv, 2307.00117`, [arxiv](http://arxiv.org/abs/2307.00117v2), [pdf](http://arxiv.org/pdf/2307.00117v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=9646982711872255783&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Vivek Myers, Andre He, Kuan Fang, Homer Walke, Philippe Hansen-Estruch, Ching-An Cheng, Mihai Jalobeanu, Andrey Kolobov, Anca Dragan, Sergey Levine*
- **On the Exploitability of Instruction Tuning**, `arXiv, 2306.17194`, [arxiv](http://arxiv.org/abs/2306.17194v2), [pdf](http://arxiv.org/pdf/2306.17194v2.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=14521585596237389103&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Manli Shu, Jiongxiao Wang, Chen Zhu, Jonas Geiping, Chaowei Xiao, Tom Goldstein*
- **Are aligned neural networks adversarially aligned?**, `arXiv, 2306.15447`, [arxiv](http://arxiv.org/abs/2306.15447v1), [pdf](http://arxiv.org/pdf/2306.15447v1.pdf), cication: [**30**](https://scholar.google.com/scholar?cites=3768131676399480172&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Nicholas Carlini, Milad Nasr, Christopher A. Choquette-Choo, Matthew Jagielski, Irena Gao, Anas Awadalla, Pang Wei Koh, Daphne Ippolito, Katherine Lee, Florian Tramer*
- **Constitutional AI: Harmlessness from AI Feedback**, `arXiv, 2212.08073`, [arxiv](http://arxiv.org/abs/2212.08073v1), [pdf](http://arxiv.org/pdf/2212.08073v1.pdf), cication: [**249**](https://scholar.google.com/scholar?cites=4609886220529082012&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuntao Bai, Saurav Kadavath, Sandipan Kundu, Amanda Askell, Jackson Kernion, Andy Jones, Anna Chen, Anna Goldie, Azalia Mirhoseini, Cameron McKinnon*
- **A General Language Assistant as a Laboratory for Alignment**, `arXiv, 2112.00861`, [arxiv](http://arxiv.org/abs/2112.00861v3), [pdf](http://arxiv.org/pdf/2112.00861v3.pdf), cication: [**61**](https://scholar.google.com/scholar?cites=7633810469345389198&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Amanda Askell, Yuntao Bai, Anna Chen, Dawn Drain, Deep Ganguli, Tom Henighan, Andy Jones, Nicholas Joseph, Ben Mann, Nova DasSarma*

### Other
- [OpenAI超级对齐负责人Jan Leike：如何破解对齐难题？用可扩展监督](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247619616&idx=1&sn=fb6bbb82ad3514091fe390e3302834eb)
- [The History of Open-Source LLMs: Imitation and Alignment (Part Three)](https://cameronrwolfe.substack.com/p/the-history-of-open-source-llms-imitation)
- [有被混合后的SFT数据伤到](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494859&idx=1&sn=d92a88e6554b86a16e67ec89529916ce)
- [OpenAI的Superalignment策略：计算为王](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494388&idx=1&sn=ef2dc97c9f05564114b6df6746d16460)
- [当 OpenAI 说 Superalignment 说的是什么](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494216&idx=2&sn=404ea6eeb9d10baf0abfceeb04939c27)
- [用AI对齐AI？超级对齐团队领导人详解OpenAI对齐超级智能四年计划 | 机器之心](https://www.jiqizhixin.com/articles/2023-08-11-3)
- [领域大模型-训练Trick&落地思考](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494320&idx=2&sn=8edd6ea37bbd73768caa306d9daa2cf7)

## Scaling
- **DiLoCo: Distributed Low-Communication Training of Language Models**, `arXiv, 2311.08105`, [arxiv](http://arxiv.org/abs/2311.08105v1), [pdf](http://arxiv.org/pdf/2311.08105v1.pdf), cication: [**-1**](None)

	 *Arthur Douillard, Qixuan Feng, Andrei A. Rusu, Rachita Chhaparia, Yani Donchev, Adhiguna Kuncoro, Marc'Aurelio Ranzato, Arthur Szlam, Jiajun Shen*
- **Microscaling Data Formats for Deep Learning**, `arXiv, 2310.10537`, [arxiv](http://arxiv.org/abs/2310.10537v3), [pdf](http://arxiv.org/pdf/2310.10537v3.pdf), cication: [**-1**](None)

	 *Bita Darvish Rouhani, Ritchie Zhao, Ankit More, Mathew Hall, Alireza Khodamoradi, Summer Deng, Dhruv Choudhary, Marius Cornea, Eric Dellinger, Kristof Denolf*
- **A Distributed Data-Parallel PyTorch Implementation of the Distributed
  Shampoo Optimizer for Training Neural Networks At-Scale**, `arXiv, 2309.06497`, [arxiv](http://arxiv.org/abs/2309.06497v1), [pdf](http://arxiv.org/pdf/2309.06497v1.pdf), cication: [**-1**](None)

	 *Hao-Jun Michael Shi, Tsung-Hsien Lee, Shintaro Iwasaki, Jose Gallego-Posada, Zhijing Li, Kaushik Rangadurai, Dheevatsa Mudigere, Michael Rabbat*
- **Scaling Laws for Sparsely-Connected Foundation Models**, `arXiv, 2309.08520`, [arxiv](http://arxiv.org/abs/2309.08520v1), [pdf](http://arxiv.org/pdf/2309.08520v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=7913780078158927003&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Elias Frantar, Carlos Riquelme, Neil Houlsby, Dan Alistarh, Utku Evci*
- **Scaling TransNormer to 175 Billion Parameters**, `arXiv, 2307.14995`, [arxiv](http://arxiv.org/abs/2307.14995v1), [pdf](http://arxiv.org/pdf/2307.14995v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=9228697006147703773&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhen Qin, Dong Li, Weigao Sun, Weixuan Sun, Xuyang Shen, Xiaodong Han, Yunshen Wei, Baohong Lv, Fei Yuan, Xiao Luo* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-28-5))
- [Go smol or go home | Harm de Vries](https://www.harmdevries.com/post/model-size-vs-compute-overhead/)
- **Inverse Scaling: When Bigger Isn't Better**, `arXiv, 2306.09479`, [arxiv](http://arxiv.org/abs/2306.09479v1), [pdf](http://arxiv.org/pdf/2306.09479v1.pdf), cication: [**15**](https://scholar.google.com/scholar?cites=7207127851750296093&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ian R. McKenzie, Alexander Lyzhov, Michael Pieler, Alicia Parrish, Aaron Mueller, Ameya Prabhu, Euan McLean, Aaron Kirtland, Alexis Ross, Alisa Liu*
- **Tune As You Scale: Hyperparameter Optimization For Compute Efficient
  Training**, `arXiv, 2306.08055`, [arxiv](http://arxiv.org/abs/2306.08055v1), [pdf](http://arxiv.org/pdf/2306.08055v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=7982331810308735377&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Abraham J. Fetterman, Ellie Kitanidis, Joshua Albrecht, Zachary Polizzi, Bryden Fogelman, Maksis Knutins, Bartosz Wróblewski, James B. Simon, Kanjun Qiu*
- **Training Compute-Optimal Large Language Models**, `arXiv, 2203.15556`, [arxiv](http://arxiv.org/abs/2203.15556v1), [pdf](http://arxiv.org/pdf/2203.15556v1.pdf), cication: [**202**](https://scholar.google.com/scholar?cites=4527570165872937408&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jordan Hoffmann, Sebastian Borgeaud, Arthur Mensch, Elena Buchatskaya, Trevor Cai, Eliza Rutherford, Diego de Las Casas, Lisa Anne Hendricks, Johannes Welbl, Aidan Clark*

### Other
- [Techniques for training large neural networks](https://openai.com/research/techniques-for-training-large-neural-networks)
- [How to Train Really Large Models on Many GPUs? | Lil'Log](https://lilianweng.github.io/posts/2021-09-25-train-large/)
- [Chinchilla之死：只要训练足够长时间，小模型也能超过大模型 | 机器之心](https://www.jiqizhixin.com/articles/2023-10-03-9)

## Fine-tuning
- **Camels in a Changing Climate: Enhancing LM Adaptation with Tulu 2**, `arXiv, 2311.10702`, [arxiv](http://arxiv.org/abs/2311.10702v1), [pdf](http://arxiv.org/pdf/2311.10702v1.pdf), cication: [**-1**](None)

	 *Hamish Ivison, Yizhong Wang, Valentina Pyatkin, Nathan Lambert, Matthew Peters, Pradeep Dasigi, Joel Jang, David Wadden, Noah A. Smith, Iz Beltagy*
- **Are We Falling in a Middle-Intelligence Trap? An Analysis and Mitigation
  of the Reversal Curse**, `arXiv, 2311.07468`, [arxiv](http://arxiv.org/abs/2311.07468v2), [pdf](http://arxiv.org/pdf/2311.07468v2.pdf), cication: [**-1**](None)

	 *Ang Lv, Kaiyi Zhang, Shufang Xie, Quan Tu, Yuhan Chen, Ji-Rong Wen, Rui Yan* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-18-5))
- **Parameter-Efficient Orthogonal Finetuning via Butterfly Factorization**, `arXiv, 2311.06243`, [arxiv](http://arxiv.org/abs/2311.06243v1), [pdf](http://arxiv.org/pdf/2311.06243v1.pdf), cication: [**-1**](None)

	 *Weiyang Liu, Zeju Qiu, Yao Feng, Yuliang Xiu, Yuxuan Xue, Longhui Yu, Haiwen Feng, Zhen Liu, Juyeon Heo, Songyou Peng*

### Other
- [Fine-tuning GPT3.5-turbo based on 140k slack messages · Ross Lazerowitz](https://rosslazer.com/posts/fine-tuning/)

## Architectures
- **Rethinking Attention: Exploring Shallow Feed-Forward Neural Networks as
  an Alternative to Attention Layers in Transformers**, `arXiv, 2311.10642`, [arxiv](http://arxiv.org/abs/2311.10642v1), [pdf](http://arxiv.org/pdf/2311.10642v1.pdf), cication: [**-1**](None)

	 *Vukasin Bozic, Danilo Dordervic, Daniele Coppola, Joseph Thommes*
- **UT5: Pretraining Non autoregressive T5 with unrolled denoising**, `arXiv, 2311.08552`, [arxiv](http://arxiv.org/abs/2311.08552v1), [pdf](http://arxiv.org/pdf/2311.08552v1.pdf), cication: [**-1**](None)

	 *Mahmoud G. Salem, Jiayu Ye, Chu-Cheng Lin, Frederick Liu*
- **How to Build Low-cost Networks for Large Language Models (without
  Sacrificing Performance)?**, `arXiv, 2307.12169`, [arxiv](http://arxiv.org/abs/2307.12169v3), [pdf](http://arxiv.org/pdf/2307.12169v3.pdf), cication: [**-1**](None)

	 *Weiyang Wang, Manya Ghobadi, Kayvon Shakeri, Ying Zhang, Naader Hasani*
- **Stack More Layers Differently: High-Rank Training Through Low-Rank
  Updates**, `arXiv, 2307.05695`, [arxiv](http://arxiv.org/abs/2307.05695v3), [pdf](http://arxiv.org/pdf/2307.05695v3.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=16347103820657222273&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Vladislav Lialin, Namrata Shivagunde, Sherin Muckatira, Anna Rumshisky*
- [Medusa: Simple Framework for Accelerating LLM Generation with Multiple Decoding Heads](https://sites.google.com/view/medusa-llm)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652375732&idx=2&sn=1cb4cefcd791af2a6ffacdf99e35225c))

## Optimization
- **CAME: Confidence-guided Adaptive Memory Efficient Optimization**, `arXiv, 2307.02047`, [arxiv](http://arxiv.org/abs/2307.02047v2), [pdf](http://arxiv.org/pdf/2307.02047v2.pdf), cication: [**-1**](None)

	 *Yang Luo, Xiaozhe Ren, Zangwei Zheng, Zhuo Jiang, Xin Jiang, Yang You* · ([qbitai](https://www.qbitai.com/2023/07/67814.html))
 
## Ensemble
- **Routing to the Expert: Efficient Reward-guided Ensemble of Large
  Language Models**, `arXiv, 2311.08692`, [arxiv](http://arxiv.org/abs/2311.08692v1), [pdf](http://arxiv.org/pdf/2311.08692v1.pdf), cication: [**-1**](None)

	 *Keming Lu, Hongyi Yuan, Runji Lin, Junyang Lin, Zheng Yuan, Chang Zhou, Jingren Zhou*
- **Language Models are Super Mario: Absorbing Abilities from Homologous
  Models as a Free Lunch**, `arXiv, 2311.03099`, [arxiv](http://arxiv.org/abs/2311.03099v1), [pdf](http://arxiv.org/pdf/2311.03099v1.pdf), cication: [**-1**](None)

	 *Le Yu, Bowen Yu, Haiyang Yu, Fei Huang, Yongbin Li* · ([mergelm](https://github.com/yule-buaa/mergelm) - yule-buaa) ![Star](https://img.shields.io/github/stars/yule-buaa/mergelm.svg?style=social&label=Star)
- **LLM-Blender: Ensembling Large Language Models with Pairwise Ranking and
  Generative Fusion**, `arXiv, 2306.02561`, [arxiv](http://arxiv.org/abs/2306.02561v3), [pdf](http://arxiv.org/pdf/2306.02561v3.pdf), cication: [**16**](https://scholar.google.com/scholar?cites=3251394917352088026&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Dongfu Jiang, Xiang Ren, Bill Yuchen Lin* · ([LLM-Blender](https://github.com/yuchenlin/LLM-Blender) - yuchenlin) ![Star](https://img.shields.io/github/stars/yuchenlin/LLM-Blender.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652343982&idx=4&sn=ce5c51039d91531178257024d883db90))

## MoE
- [**SmartMoE**](https://github.com/zms1999/SmartMoE) - zms1999 ![Star](https://img.shields.io/github/stars/zms1999/SmartMoE.svg?style=social&label=Star)

	 *A MoE impl for PyTorch, [ATC'23] SmartMoE* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-07-7))
- **Mixture-of-Experts Meets Instruction Tuning:A Winning Combination for
  Large Language Models**, `arXiv, 2305.14705`, [arxiv](http://arxiv.org/abs/2305.14705v2), [pdf](http://arxiv.org/pdf/2305.14705v2.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=9670032780085101117&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Sheng Shen, Le Hou, Yanqi Zhou, Nan Du, Shayne Longpre, Jason Wei, Hyung Won Chung, Barret Zoph, William Fedus, Xinyun Chen* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-07-9))
- [**OpenMoE**](https://github.com/XueFuzhao/OpenMoE) - XueFuzhao ![Star](https://img.shields.io/github/stars/XueFuzhao/OpenMoE.svg?style=social&label=Star)

	 *A family of open-sourced Mixture-of-Experts (MoE) Large Language Models*
- [模块化大模型来了！IBM公开WastonX核心架构技术细节](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247522084&idx=3&sn=ceba2b0c3e6434599101f7604ff109c4)

## Toolkits
- [**saturn**](https://github.com/knagrecha/saturn) - knagrecha ![Star](https://img.shields.io/github/stars/knagrecha/saturn.svg?style=social&label=Star)

	 *Saturn accelerates the training of large-scale deep learning models with a novel joint optimization approach.*
- [**SynapseML**](https://github.com/microsoft/SynapseML) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/SynapseML.svg?style=social&label=Star)

	 *Simple and Distributed Machine Learning*
- [**gpt-llm-trainer**](https://github.com/mshumer/gpt-llm-trainer) - mshumer ![Star](https://img.shields.io/github/stars/mshumer/gpt-llm-trainer.svg?style=social&label=Star)

	 · ([qbitai](https://www.qbitai.com/2023/08/78155.html))
- [**LLaMA-Factory**](https://github.com/hiyouga/LLaMA-Factory) - hiyouga ![Star](https://img.shields.io/github/stars/hiyouga/LLaMA-Factory.svg?style=social&label=Star)

	 *Easy-to-use LLM fine-tuning framework (LLaMA, BLOOM, Mistral, Baichuan, Qwen, ChatGLM)*
- [**Megatron-LLaMA**](https://github.com/alibaba/Megatron-LLaMA) - alibaba ![Star](https://img.shields.io/github/stars/alibaba/Megatron-LLaMA.svg?style=social&label=Star)

	 *Best practice for training LLaMA models in Megatron-LM* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-12-5))
- [**Efficient-PyTorch**](https://github.com/Lyken17/Efficient-PyTorch) - Lyken17 ![Star](https://img.shields.io/github/stars/Lyken17/Efficient-PyTorch.svg?style=social&label=Star)

	 *My best practice of training large dataset using PyTorch.*

## Misc
- **Tell Your Model Where to Attend: Post-hoc Attention Steering for LLMs**, `arXiv, 2311.02262`, [arxiv](http://arxiv.org/abs/2311.02262v1), [pdf](http://arxiv.org/pdf/2311.02262v1.pdf), cication: [**-1**](None)

	 *Qingru Zhang, Chandan Singh, Liyuan Liu, Xiaodong Liu, Bin Yu, Jianfeng Gao, Tuo Zhao*
- **Tensor Programs VI: Feature Learning in Infinite-Depth Neural Networks**, `arXiv, 2310.02244`, [arxiv](http://arxiv.org/abs/2310.02244v5), [pdf](http://arxiv.org/pdf/2310.02244v5.pdf), cication: [**-1**](None)

	 *Greg Yang, Dingli Yu, Chen Zhu, Soufiane Hayou* · ([qbitai](https://www.qbitai.com/2023/10/91674.html))
- **Think before you speak: Training Language Models With Pause Tokens**, `arXiv, 2310.02226`, [arxiv](http://arxiv.org/abs/2310.02226v1), [pdf](http://arxiv.org/pdf/2310.02226v1.pdf), cication: [**-1**](None)

	 *Sachin Goyal, Ziwei Ji, Ankit Singh Rawat, Aditya Krishna Menon, Sanjiv Kumar, Vaishnavh Nagarajan* · ([qbitai](https://www.qbitai.com/2023/10/89955.html))
- **Textbooks Are All You Need II: phi-1.5 technical report**, `arXiv, 2309.05463`, [arxiv](http://arxiv.org/abs/2309.05463v1), [pdf](http://arxiv.org/pdf/2309.05463v1.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=5479111836130062736&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuanzhi Li, Sébastien Bubeck, Ronen Eldan, Allie Del Giorno, Suriya Gunasekar, Yin Tat Lee* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-14-4))
- **Towards Robust and Efficient Continual Language Learning**, `arXiv, 2307.05741`, [arxiv](http://arxiv.org/abs/2307.05741v1), [pdf](http://arxiv.org/pdf/2307.05741v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=856239084750569233&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Adam Fisch, Amal Rannen-Triki, Razvan Pascanu, Jörg Bornschein, Angeliki Lazaridou, Elena Gribovskaya, Marc'Aurelio Ranzato*

## Courses
- [Pathways 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1xB4y1m7Xi/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)
- [GPipe论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1v34y1E7zu/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)
- [Megatron LM 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1nB4y1R7Yz/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)
- [Zero 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1tY411g7ZT/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)

## Other
- [0代码微调大模型火了，只需5步，成本低至150块 | 量子位](https://www.qbitai.com/2023/07/66833.html)
- [Fine-tuning Llama 2 70B using PyTorch FSDP](https://huggingface.co/blog/ram-efficient-pytorch-fsdp)
- [Everything about Distributed Training and Efficient Finetuning | Sumanth's Personal Website](https://sumanthrh.com/post/distributed-and-efficient-finetuning/)
- [GPU 利用率低常见原因分析及优化](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247609210&idx=3&sn=01686c5f7d7d70d4383667296ae7d823)

## Extra reference 
- [**llm-alignment-survey**](https://github.com/Magnetic2014/llm-alignment-survey) - Magnetic2014 ![Star](https://img.shields.io/github/stars/Magnetic2014/llm-alignment-survey.svg?style=social&label=Star)

	 *A curated reading list for large language model (LLM) alignment. Take a look at our new survey "Large Language Model Alignment: A Survey" for more details!*