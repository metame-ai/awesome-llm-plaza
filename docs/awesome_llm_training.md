# Awesome llm training

- [Awesome llm training](#awesome-llm-training)
	- [Pretrain](#pretrain)
		- [Other](#other)
	- [Scaling](#scaling)
		- [Other](#other-1)
	- [Fine-tuning](#fine-tuning)
		- [Other](#other-2)
	- [Architectures](#architectures)
	- [Optimization](#optimization)
	- [Ensemble](#ensemble)
		- [Other](#other-3)
	- [MoE](#moe)
		- [Other](#other-4)
	- [Toolkits](#toolkits)
	- [Misc](#misc)
	- [Courses](#courses)
	- [Other](#other-5)
	- [Extra reference](#extra-reference)


## Pretrain
- **Efficient Continual Pre-training by Mitigating the Stability Gap**, `arXiv, 2406.14833`, [arxiv](http://arxiv.org/abs/2406.14833v1), [pdf](http://arxiv.org/pdf/2406.14833v1.pdf), cication: [**-1**](None)

	 *Yiduo Guo, Jie Fu, Huishuai Zhang, Dongyan Zhao, Yikang Shen*
- **Instruction Pre-Training: Language Models are Supervised Multitask
  Learners**, `arXiv, 2406.14491`, [arxiv](http://arxiv.org/abs/2406.14491v1), [pdf](http://arxiv.org/pdf/2406.14491v1.pdf), cication: [**-1**](None)

	 *Daixuan Cheng, Yuxian Gu, Shaohan Huang, Junyu Bi, Minlie Huang, Furu Wei* · ([LMOps](https://github.com/microsoft/LMOps) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/LMOps.svg?style=social&label=Star)
- **Stacking Your Transformers: A Closer Look at Model Growth for Efficient
  LLM Pre-Training**, `arXiv, 2405.15319`, [arxiv](http://arxiv.org/abs/2405.15319v1), [pdf](http://arxiv.org/pdf/2405.15319v1.pdf), cication: [**-1**](None)

	 *Wenyu Du, Tongxu Luo, Zihan Qiu, Zeyu Huang, Yikang Shen, Reynold Cheng, Yike Guo, Jie Fu* · ([llm-stacking.github](https://llm-stacking.github.io))
- **Data Mixing Made Efficient: A Bivariate Scaling Law for Language Model
  Pretraining**, `arXiv, 2405.14908`, [arxiv](http://arxiv.org/abs/2405.14908v1), [pdf](http://arxiv.org/pdf/2405.14908v1.pdf), cication: [**-1**](None)

	 *Ce Ge, Zhijian Ma, Daoyuan Chen, Yaliang Li, Bolin Ding*
- **Pre-training Small Base LMs with Fewer Tokens**, `arXiv, 2404.08634`, [arxiv](http://arxiv.org/abs/2404.08634v1), [pdf](http://arxiv.org/pdf/2404.08634v1.pdf), cication: [**-1**](None)

	 *Sunny Sanyal, Sujay Sanghavi, Alexandros G. Dimakis* · ([LLM-Inheritune](https://github.com/sanyalsunny111/LLM-Inheritune) - sanyalsunny111) ![Star](https://img.shields.io/github/stars/sanyalsunny111/LLM-Inheritune.svg?style=social&label=Star)
- **Training LLMs over Neurally Compressed Text**, `arXiv, 2404.03626`, [arxiv](http://arxiv.org/abs/2404.03626v1), [pdf](http://arxiv.org/pdf/2404.03626v1.pdf), cication: [**-1**](None)

	 *Brian Lester, Jaehoon Lee, Alex Alemi, Jeffrey Pennington, Adam Roberts, Jascha Sohl-Dickstein, Noah Constant*
- **The Fine Line: Navigating Large Language Model Pretraining with
  Down-streaming Capability Analysis**, `arXiv, 2404.01204`, [arxiv](http://arxiv.org/abs/2404.01204v1), [pdf](http://arxiv.org/pdf/2404.01204v1.pdf), cication: [**-1**](None)

	 *Chen Yang, Junzhuo Li, Xinyao Niu, Xinrun Du, Songyang Gao, Haoran Zhang, Zhaoliang Chen, Xingwei Qu, Ruibin Yuan, Yizhi Li*
- **Mitigating Reversal Curse in Large Language Models via Semantic-aware
  Permutation Training**, `arXiv, 2403.00758`, [arxiv](http://arxiv.org/abs/2403.00758v3), [pdf](http://arxiv.org/pdf/2403.00758v3.pdf), cication: [**-1**](None)

	 *Qingyan Guo, Rui Wang, Junliang Guo, Xu Tan, Jiang Bian, Yujiu Yang*
- **Reverse Training to Nurse the Reversal Curse**, `arXiv, 2403.13799`, [arxiv](http://arxiv.org/abs/2403.13799v1), [pdf](http://arxiv.org/pdf/2403.13799v1.pdf), cication: [**-1**](None)

	 *Olga Golovneva, Zeyuan Allen-Zhu, Jason Weston, Sainbayar Sukhbaatar*
- **Language models scale reliably with over-training and on downstream
  tasks**, `arXiv, 2403.08540`, [arxiv](http://arxiv.org/abs/2403.08540v1), [pdf](http://arxiv.org/pdf/2403.08540v1.pdf), cication: [**-1**](None)

	 *Samir Yitzhak Gadre, Georgios Smyrnis, Vaishaal Shankar, Suchin Gururangan, Mitchell Wortsman, Rulin Shao, Jean Mercat, Alex Fang, Jeffrey Li, Sedrick Keh*
- [**fm-cheatsheet**](https://github.com/allenai/fm-cheatsheet/tree/main) - allenai ![Star](https://img.shields.io/github/stars/allenai/fm-cheatsheet.svg?style=social&label=Star)

	 *Website for hosting the Open Foundation Models Cheat Sheet.* · ([fmcheatsheet](https://fmcheatsheet.org/))
- **SpacTor-T5: Pre-training T5 Models with Span Corruption and Replaced
  Token Detection**, `arXiv, 2401.13160`, [arxiv](http://arxiv.org/abs/2401.13160v1), [pdf](http://arxiv.org/pdf/2401.13160v1.pdf), cication: [**-1**](None)

	 *Ke Ye, Heinrich Jiang, Afshin Rostamizadeh, Ayan Chakrabarti, Giulia DeSalvo, Jean-François Kagy, Lazaros Karydas, Gui Citovsky, Sanjiv Kumar*
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
- [useful AI paper on optimizing training, comment with your finds](https://twitter.com/far__el/status/1770218968126820773)

- [如何从零开始训练大模型（minicpm分享&讨论） - 知乎](https://zhuanlan.zhihu.com/p/686664720)
- [贫穷让我预训练](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494110&idx=2&sn=52bfbf2d51d1704efc596263bccf23db)

## Scaling
- **Scaling Laws for Linear Complexity Language Models**, `arXiv, 2406.16690`, [arxiv](http://arxiv.org/abs/2406.16690v1), [pdf](http://arxiv.org/pdf/2406.16690v1.pdf), cication: [**-1**](None)

	 *Xuyang Shen, Dong Li, Ruitao Leng, Zhen Qin, Weigao Sun, Yiran Zhong*
- **D-CPT Law: Domain-specific Continual Pre-Training Scaling Law for Large
  Language Models**, `arXiv, 2406.01375`, [arxiv](http://arxiv.org/abs/2406.01375v1), [pdf](http://arxiv.org/pdf/2406.01375v1.pdf), cication: [**-1**](None)

	 *Haoran Que, Jiaheng Liu, Ge Zhang, Chenchen Zhang, Xingwei Qu, Yinghao Ma, Feiyu Duan, Zhiqi Bai, Jiakai Wang, Yuanxing Zhang*
- **Why Has Predicting Downstream Capabilities of Frontier AI Models with
  Scale Remained Elusive?**, `arXiv, 2406.04391`, [arxiv](http://arxiv.org/abs/2406.04391v1), [pdf](http://arxiv.org/pdf/2406.04391v1.pdf), cication: [**-1**](None)

	 *Rylan Schaeffer, Hailey Schoelkopf, Brando Miranda, Gabriel Mukobi, Varun Madan, Adam Ibrahim, Herbie Bradley, Stella Biderman, Sanmi Koyejo*
- **Observational Scaling Laws and the Predictability of Language Model
  Performance**, `arXiv, 2405.10938`, [arxiv](http://arxiv.org/abs/2405.10938v1), [pdf](http://arxiv.org/pdf/2405.10938v1.pdf), cication: [**-1**](None)

	 *Yangjun Ruan, Chris J. Maddison, Tatsunori Hashimoto*
- **Beyond Scaling Laws: Understanding Transformer Performance with
  Associative Memory**, `arXiv, 2405.08707`, [arxiv](http://arxiv.org/abs/2405.08707v1), [pdf](http://arxiv.org/pdf/2405.08707v1.pdf), cication: [**-1**](None)

	 *Xueyan Niu, Bo Bai, Lei Deng, Wei Han*
- **Chinchilla Scaling: A replication attempt**, `arXiv, 2404.10102`, [arxiv](http://arxiv.org/abs/2404.10102v1), [pdf](http://arxiv.org/pdf/2404.10102v1.pdf), cication: [**-1**](None)

	 *Tamay Besiroglu, Ege Erdil, Matthew Barnett, Josh You*
- **Physics of Language Models: Part 3.3, Knowledge Capacity Scaling Laws**, `arXiv, 2404.05405`, [arxiv](http://arxiv.org/abs/2404.05405v1), [pdf](http://arxiv.org/pdf/2404.05405v1.pdf), cication: [**-1**](None)

	 *Zeyuan Allen-Zhu, Yuanzhi Li*
- **DiPaCo: Distributed Path Composition**, `arXiv, 2403.10616`, [arxiv](http://arxiv.org/abs/2403.10616v1), [pdf](http://arxiv.org/pdf/2403.10616v1.pdf), cication: [**-1**](None)

	 *Arthur Douillard, Qixuan Feng, Andrei A. Rusu, Adhiguna Kuncoro, Yani Donchev, Rachita Chhaparia, Ionel Gog, Marc'Aurelio Ranzato, Jiajun Shen, Arthur Szlam*
- **Algorithmic progress in language models**, `arXiv, 2403.05812`, [arxiv](http://arxiv.org/abs/2403.05812v1), [pdf](http://arxiv.org/pdf/2403.05812v1.pdf), cication: [**-1**](None)

	 *Anson Ho, Tamay Besiroglu, Ege Erdil, David Owen, Robi Rahman, Zifan Carl Guo, David Atkinson, Neil Thompson, Jaime Sevilla*

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652455514&idx=3&sn=8955e6ac82257fc0b3da29e34d1e5467))
	- `since 2012, the computational efficiency for pretraining language models (including large language models) has doubled approximately every 8 months, a pace much faster than the hardware advancements predicted by Moore's Law.`
- **When Scaling Meets LLM Finetuning: The Effect of Data, Model and
  Finetuning Method**, `arXiv, 2402.17193`, [arxiv](http://arxiv.org/abs/2402.17193v1), [pdf](http://arxiv.org/pdf/2402.17193v1.pdf), cication: [**-1**](None)

	 *Biao Zhang, Zhongtao Liu, Colin Cherry, Orhan Firat*
- **MegaScale: Scaling Large Language Model Training to More Than 10,000
  GPUs**, `arXiv, 2402.15627`, [arxiv](http://arxiv.org/abs/2402.15627v1), [pdf](http://arxiv.org/pdf/2402.15627v1.pdf), cication: [**-1**](None)

	 *Ziheng Jiang, Haibin Lin, Yinmin Zhong, Qi Huang, Yangrui Chen, Zhi Zhang, Yanghua Peng, Xiang Li, Cong Xie, Shibiao Nong*
- **OpenFedLLM: Training Large Language Models on Decentralized Private Data
  via Federated Learning**, `arXiv, 2402.06954`, [arxiv](http://arxiv.org/abs/2402.06954v1), [pdf](http://arxiv.org/pdf/2402.06954v1.pdf), cication: [**-1**](None)

	 *Rui Ye, Wenhao Wang, Jingyi Chai, Dihan Li, Zexi Li, Yinda Xu, Yaxin Du, Yanfeng Wang, Siheng Chen* · ([openfedllm](https://github.com/rui-ye/openfedllm) - rui-ye) ![Star](https://img.shields.io/github/stars/rui-ye/openfedllm.svg?style=social&label=Star)
- **A Tale of Tails: Model Collapse as a Change of Scaling Laws**, `arXiv, 2402.07043`, [arxiv](http://arxiv.org/abs/2402.07043v1), [pdf](http://arxiv.org/pdf/2402.07043v1.pdf), cication: [**-1**](None)

	 *Elvis Dohmatob, Yunzhen Feng, Pu Yang, Francois Charton, Julia Kempe*
- **Scaling Laws for Downstream Task Performance of Large Language Models**, `arXiv, 2402.04177`, [arxiv](http://arxiv.org/abs/2402.04177v1), [pdf](http://arxiv.org/pdf/2402.04177v1.pdf), cication: [**-1**](None)

	 *Berivan Isik, Natalia Ponomareva, Hussein Hazimeh, Dimitris Paparas, Sergei Vassilvitskii, Sanmi Koyejo*
- **T3: Transparent Tracking & Triggering for Fine-grained Overlap of
  Compute & Collectives**, `arXiv, 2401.16677`, [arxiv](http://arxiv.org/abs/2401.16677v1), [pdf](http://arxiv.org/pdf/2401.16677v1.pdf), cication: [**-1**](None)

	 *Suchita Pati, Shaizeen Aga, Mahzabeen Islam, Nuwan Jayasena, Matthew D. Sinclair*
- **Zero Bubble Pipeline Parallelism**, `arXiv, 2401.10241`, [arxiv](http://arxiv.org/abs/2401.10241v1), [pdf](http://arxiv.org/pdf/2401.10241v1.pdf), cication: [**-1**](None)

	 *Penghui Qi, Xinyi Wan, Guangxing Huang, Min Lin* · ([zero-bubble-pipeline-parallelism](https://github.com/sail-sg/zero-bubble-pipeline-parallelism) - sail-sg) ![Star](https://img.shields.io/github/stars/sail-sg/zero-bubble-pipeline-parallelism.svg?style=social&label=Star)
- **Asynchronous Local-SGD Training for Language Modeling**, `arXiv, 2401.09135`, [arxiv](http://arxiv.org/abs/2401.09135v1), [pdf](http://arxiv.org/pdf/2401.09135v1.pdf), cication: [**-1**](None)

	 *Bo Liu, Rachita Chhaparia, Arthur Douillard, Satyen Kale, Andrei A. Rusu, Jiajun Shen, Arthur Szlam, Marc'Aurelio Ranzato*
- **DeepSeek LLM: Scaling Open-Source Language Models with Longtermism**, `arXiv, 2401.02954`, [arxiv](http://arxiv.org/abs/2401.02954v1), [pdf](http://arxiv.org/pdf/2401.02954v1.pdf), cication: [**-1**](None)

	 *DeepSeek-AI, :, Xiao Bi, Deli Chen, Guanting Chen, Shanhuang Chen, Damai Dai, Chengqi Deng, Honghui Ding, Kai Dong*
- **Beyond Chinchilla-Optimal: Accounting for Inference in Language Model
  Scaling Laws**, `arXiv, 2401.00448`, [arxiv](http://arxiv.org/abs/2401.00448v1), [pdf](http://arxiv.org/pdf/2401.00448v1.pdf), cication: [**-1**](None)

	 *Nikhil Sardana, Jonathan Frankle*
- **Unicron: Economizing Self-Healing LLM Training at Scale**, `arXiv, 2401.00134`, [arxiv](http://arxiv.org/abs/2401.00134v1), [pdf](http://arxiv.org/pdf/2401.00134v1.pdf), cication: [**-1**](None)

	 *Tao He, Xue Li, Zhibin Wang, Kun Qian, Jingbo Xu, Wenyuan Yu, Jingren Zhou*
- **SOLAR 10.7B: Scaling Large Language Models with Simple yet Effective
  Depth Up-Scaling**, `arXiv, 2312.15166`, [arxiv](http://arxiv.org/abs/2312.15166v1), [pdf](http://arxiv.org/pdf/2312.15166v1.pdf), cication: [**-1**](None)

	 *Dahyun Kim, Chanjun Park, Sanghoon Kim, Wonsung Lee, Wonho Song, Yunsu Kim, Hyeonwoo Kim, Yungi Kim, Hyeonju Lee, Jihoo Kim*
- **Distributed Inference and Fine-tuning of Large Language Models Over The
  Internet**, `arXiv, 2312.08361`, [arxiv](http://arxiv.org/abs/2312.08361v1), [pdf](http://arxiv.org/pdf/2312.08361v1.pdf), cication: [**-1**](None)

	 *Alexander Borzunov, Max Ryabinin, Artem Chumachenko, Dmitry Baranchuk, Tim Dettmers, Younes Belkada, Pavel Samygin, Colin Raffel*

	 · ([petals](https://github.com/bigscience-workshop/petals) - bigscience-workshop) ![Star](https://img.shields.io/github/stars/bigscience-workshop/petals.svg?style=social&label=Star)
- **Vary: Scaling up the Vision Vocabulary for Large Vision-Language Models**, `arXiv, 2312.06109`, [arxiv](http://arxiv.org/abs/2312.06109v1), [pdf](http://arxiv.org/pdf/2312.06109v1.pdf), cication: [**-1**](None)

	 *Haoran Wei, Lingyu Kong, Jinyue Chen, Liang Zhao, Zheng Ge, Jinrong Yang, Jianjian Sun, Chunrui Han, Xiangyu Zhang*
- **EE-LLM: Large-Scale Training and Inference of Early-Exit Large Language
  Models with 3D Parallelism**, `arXiv, 2312.04916`, [arxiv](http://arxiv.org/abs/2312.04916v1), [pdf](http://arxiv.org/pdf/2312.04916v1.pdf), cication: [**-1**](None)

	 *Yanxi Chen, Xuchen Pan, Yaliang Li, Bolin Ding, Jingren Zhou* · ([EE-LLM](https://github.com/pan-x-c/EE-LLM) - pan-x-c) ![Star](https://img.shields.io/github/stars/pan-x-c/EE-LLM.svg?style=social&label=Star)
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
- **To Repeat or Not To Repeat: Insights from Scaling LLM under Token-Crisis**, `arXiv, 2305.13230`, [arxiv](http://arxiv.org/abs/2305.13230v2), [pdf](http://arxiv.org/pdf/2305.13230v2.pdf), cication: [**-1**](None)

	 *Fuzhao Xue, Yao Fu, Wangchunshu Zhou, Zangwei Zheng, Yang You*
- **Training Compute-Optimal Large Language Models**, `arXiv, 2203.15556`, [arxiv](http://arxiv.org/abs/2203.15556v1), [pdf](http://arxiv.org/pdf/2203.15556v1.pdf), cication: [**202**](https://scholar.google.com/scholar?cites=4527570165872937408&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jordan Hoffmann, Sebastian Borgeaud, Arthur Mensch, Elena Buchatskaya, Trevor Cai, Eliza Rutherford, Diego de Las Casas, Lisa Anne Hendricks, Johannes Welbl, Aidan Clark*
- **Pythia: A Suite for Analyzing Large Language Models Across Training and
  Scaling**, `ICML, 2023`, [arxiv](http://arxiv.org/abs/2304.01373v2), [pdf](http://arxiv.org/pdf/2304.01373v2.pdf), cication: [**-1**](None)

	 *Stella Biderman, Hailey Schoelkopf, Quentin Anthony, Herbie Bradley, Kyle O'Brien, Eric Hallahan, Mohammad Aflah Khan, Shivanshu Purohit, USVSN Sai Prashanth, Edward Raff*
	 - [twitter](https://twitter.com/rasbt/status/1734920232173539796)

### Other
- [scaling laws allow us to accurately predict the performance of larger training runs from much cheaper ones.](https://twitter.com/cwolferesearch/status/1777424149415145882)
- [Techniques for training large neural networks](https://openai.com/research/techniques-for-training-large-neural-networks)
- [How to Train Really Large Models on Many GPUs? | Lil'Log](https://lilianweng.github.io/posts/2021-09-25-train-large/)

- [揭开OpenAI Scaling Laws面纱](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495782&idx=1&sn=0a2a3b7fdf40f0127b5cd30e90eb7968)
- [Chinchilla之死：只要训练足够长时间，小模型也能超过大模型 | 机器之心](https://www.jiqizhixin.com/articles/2023-10-03-9)

## Fine-tuning
- **LlamaFactory: Unified Efficient Fine-Tuning of 100+ Language Models**, `arXiv, 2403.13372`, [arxiv](http://arxiv.org/abs/2403.13372v1), [pdf](http://arxiv.org/pdf/2403.13372v1.pdf), cication: [**-1**](None)

	 *Yaowei Zheng, Richong Zhang, Junhao Zhang, Yanhan Ye, Zheyan Luo* · ([LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) - hiyouga) ![Star](https://img.shields.io/github/stars/hiyouga/LLaMA-Factory.svg?style=social&label=Star)
- **Reawakening knowledge: Anticipatory recovery from catastrophic
  interference via structured training**, `arXiv, 2403.09613`, [arxiv](http://arxiv.org/abs/2403.09613v1), [pdf](http://arxiv.org/pdf/2403.09613v1.pdf), cication: [**-1**](None)

	 *Yanlai Yang, Matt Jones, Michael C. Mozer, Mengye Ren*

- **Larimar: Large Language Models with Episodic Memory Control**, `arXiv, 2403.11901`, [arxiv](http://arxiv.org/abs/2403.11901v1), [pdf](http://arxiv.org/pdf/2403.11901v1.pdf), cication: [**-1**](None)

	 *Payel Das, Subhajit Chaudhury, Elliot Nelson, Igor Melnyk, Sarath Swaminathan, Sihui Dai, Aurélie Lozano, Georgios Kollias, Vijil Chenthamarakshan, Jiří*
- **Simple and Scalable Strategies to Continually Pre-train Large Language
  Models**, `arXiv, 2403.08763`, [arxiv](http://arxiv.org/abs/2403.08763v1), [pdf](http://arxiv.org/pdf/2403.08763v1.pdf), cication: [**-1**](None)

	 *Adam Ibrahim, Benjamin Thérien, Kshitij Gupta, Mats L. Richter, Quentin Anthony, Timothée Lesort, Eugene Belilovsky, Irina Rish*

	 · ([twitter](https://twitter.com/rasbt/status/1768629533509370279))
	- `LLMs can be efficiently updated with new data through a combination of simple learning rate rewarming and adding a small fraction of previous training data to counteract catastrophic forgetting.`
- **Personalized Large Language Models**, `arXiv, 2402.09269`, [arxiv](http://arxiv.org/abs/2402.09269v1), [pdf](http://arxiv.org/pdf/2402.09269v1.pdf), cication: [**-1**](None)

	 *Stanisław Woźniak, Bartłomiej Koptyra, Arkadiusz Janz, Przemysław Kazienko, Jan Kocoń*
- **BitDelta: Your Fine-Tune May Only Be Worth One Bit**, `arXiv, 2402.10193`, [arxiv](http://arxiv.org/abs/2402.10193v1), [pdf](http://arxiv.org/pdf/2402.10193v1.pdf), cication: [**-1**](None)

	 *James Liu, Guangxuan Xiao, Kai Li, Jason D. Lee, Song Han, Tri Dao, Tianle Cai* · ([BitDelta](https://github.com/FasterDecoding/BitDelta) - FasterDecoding) ![Star](https://img.shields.io/github/stars/FasterDecoding/BitDelta.svg?style=social&label=Star)
- **EE-Tuning: An Economical yet Scalable Solution for Tuning Early-Exit
  Large Language Models**, `arXiv, 2402.00518`, [arxiv](http://arxiv.org/abs/2402.00518v1), [pdf](http://arxiv.org/pdf/2402.00518v1.pdf), cication: [**-1**](None)

	 *Xuchen Pan, Yanxi Chen, Yaliang Li, Bolin Ding, Jingren Zhou* · ([EE-LLM](https://github.com/pan-x-c/EE-LLM) - pan-x-c) ![Star](https://img.shields.io/github/stars/pan-x-c/EE-LLM.svg?style=social&label=Star)
- **Scaling Sparse Fine-Tuning to Large Language Models**, `arXiv, 2401.16405`, [arxiv](http://arxiv.org/abs/2401.16405v1), [pdf](http://arxiv.org/pdf/2401.16405v1.pdf), cication: [**-1**](None)

	 *Alan Ansell, Ivan Vulić, Hannah Sterz, Anna Korhonen, Edoardo M. Ponti* · ([peft](https://github.com/AlanAnsell/peft) - AlanAnsell) ![Star](https://img.shields.io/github/stars/AlanAnsell/peft.svg?style=social&label=Star) · ([sft-llm](https://github.com/ducdauge/sft-llm) - ducdauge) ![Star](https://img.shields.io/github/stars/ducdauge/sft-llm.svg?style=social&label=Star)
- **Tuning Language Models by Proxy**, `arXiv, 2401.08565`, [arxiv](http://arxiv.org/abs/2401.08565v1), [pdf](http://arxiv.org/pdf/2401.08565v1.pdf), cication: [**-1**](None)

	 *Alisa Liu, Xiaochuang Han, Yizhong Wang, Yulia Tsvetkov, Yejin Choi, Noah A. Smith*

	 · ([lightning](https://lightning.ai/lightning-ai/studios/improve-llms-with-proxy-tuning?view=public))
- **LLaMA Pro: Progressive LLaMA with Block Expansion**, `arXiv, 2401.02415`, [arxiv](http://arxiv.org/abs/2401.02415v1), [pdf](http://arxiv.org/pdf/2401.02415v1.pdf), cication: [**-1**](None)

	 *Chengyue Wu, Yukang Gan, Yixiao Ge, Zeyu Lu, Jiahao Wang, Ye Feng, Ping Luo, Ying Shan* · ([LLaMA-Pro](https://github.com/TencentARC/LLaMA-Pro) - TencentARC) ![Star](https://img.shields.io/github/stars/TencentARC/LLaMA-Pro.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/TencentARC/LLaMA-Pro-8B))
- **Self-Play Fine-Tuning Converts Weak Language Models to Strong Language
  Models**, `arXiv, 2401.01335`, [arxiv](http://arxiv.org/abs/2401.01335v1), [pdf](http://arxiv.org/pdf/2401.01335v1.pdf), cication: [**-1**](None)

	 *Zixiang Chen, Yihe Deng, Huizhuo Yuan, Kaixuan Ji, Quanquan Gu*

	 · ([SPIN](https://github.com/uclaml/SPIN) - uclaml) ![Star](https://img.shields.io/github/stars/uclaml/SPIN.svg?style=social&label=Star)
- **Federated Full-Parameter Tuning of Billion-Sized Language Models with
  Communication Cost under 18 Kilobytes**, `arXiv, 2312.06353`, [arxiv](http://arxiv.org/abs/2312.06353v1), [pdf](http://arxiv.org/pdf/2312.06353v1.pdf), cication: [**-1**](None)

	 *Zhen Qin, Daoyuan Chen, Bingchen Qian, Bolin Ding, Yaliang Li, Shuiguang Deng*
- **Camels in a Changing Climate: Enhancing LM Adaptation with Tulu 2**, `arXiv, 2311.10702`, [arxiv](http://arxiv.org/abs/2311.10702v1), [pdf](http://arxiv.org/pdf/2311.10702v1.pdf), cication: [**-1**](None)

	 *Hamish Ivison, Yizhong Wang, Valentina Pyatkin, Nathan Lambert, Matthew Peters, Pradeep Dasigi, Joel Jang, David Wadden, Noah A. Smith, Iz Beltagy*
- **Are We Falling in a Middle-Intelligence Trap? An Analysis and Mitigation
  of the Reversal Curse**, `arXiv, 2311.07468`, [arxiv](http://arxiv.org/abs/2311.07468v2), [pdf](http://arxiv.org/pdf/2311.07468v2.pdf), cication: [**-1**](None)

	 *Ang Lv, Kaiyi Zhang, Shufang Xie, Quan Tu, Yuhan Chen, Ji-Rong Wen, Rui Yan* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-18-5))
- **Parameter-Efficient Orthogonal Finetuning via Butterfly Factorization**, `arXiv, 2311.06243`, [arxiv](http://arxiv.org/abs/2311.06243v1), [pdf](http://arxiv.org/pdf/2311.06243v1.pdf), cication: [**-1**](None)

	 *Weiyang Liu, Zeju Qiu, Yao Feng, Yuliang Xiu, Yuxuan Xue, Longhui Yu, Haiwen Feng, Zhen Liu, Juyeon Heo, Songyou Peng*

### Other
- [Efficiently fine-tune Llama 3 with PyTorch FSDP and Q-Lora](https://www.philschmid.de/fsdp-qlora-llama3)
- [Answer.AI - Efficient finetuning of Llama 3 with FSDP QDoRA](https://www.answer.ai/posts/2024-04-26-fsdp-qdora-llama3.html)
- [How to Fine-Tune LLMs in 2024 with Hugging Face](https://www.philschmid.de/fine-tune-llms-in-2024-with-trl)
- [Combating Evaluation Data Contamination in LLMs: Strategies for High-Quality Finetuning and Model Merging](https://huggingface.co/blog/rishiraj/merge-models-without-contamination)
- [Fine-tuning GPT3.5-turbo based on 140k slack messages · Ross Lazerowitz](https://rosslazer.com/posts/fine-tuning/)

## Architectures
- **Boosting Large-scale Parallel Training Efficiency with C4: A
  Communication-Driven Approach**, `arXiv, 2406.04594`, [arxiv](http://arxiv.org/abs/2406.04594v1), [pdf](http://arxiv.org/pdf/2406.04594v1.pdf), cication: [**-1**](None)

	 *Jianbo Dong, Bin Luo, Jun Zhang, Pengcheng Zhang, Fei Feng, Yikai Zhu, Ang Liu, Zian Chen, Yi Shi, Hairong Jiao*
- **Linear Transformers with Learnable Kernel Functions are Better
  In-Context Models**, `arXiv, 2402.10644`, [arxiv](http://arxiv.org/abs/2402.10644v1), [pdf](http://arxiv.org/pdf/2402.10644v1.pdf), cication: [**-1**](None)

	 *Yaroslav Aksenov, Nikita Balagansky, Sofia Maria Lo Cicero Vaina, Boris Shaposhnikov, Alexey Gorbatovski, Daniil Gavrilov*
- **Rethinking Optimization and Architecture for Tiny Language Models**, `arXiv, 2402.02791`, [arxiv](http://arxiv.org/abs/2402.02791v2), [pdf](http://arxiv.org/pdf/2402.02791v2.pdf), cication: [**-1**](None)

	 *Yehui Tang, Fangcheng Liu, Yunsheng Ni, Yuchuan Tian, Zheyuan Bai, Yi-Qi Hu, Sichao Liu, Shangling Jui, Kai Han, Yunhe Wang* · ([RethinkTinyLM](https://github.com/YuchuanTian/RethinkTinyLM) - YuchuanTian) ![Star](https://img.shields.io/github/stars/YuchuanTian/RethinkTinyLM.svg?style=social&label=Star)
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
- **Diffusion Forcing: Next-token Prediction Meets Full-Sequence Diffusion**, `arXiv, 2407.01392`, [arxiv](http://arxiv.org/abs/2407.01392v3), [pdf](http://arxiv.org/pdf/2407.01392v3.pdf), cication: [**-1**](None)

	 *Boyuan Chen, Diego Marti Monso, Yilun Du, Max Simchowitz, Russ Tedrake, Vincent Sitzmann*

	 · ([diffusion-forcing](https://github.com/buoyancy99/diffusion-forcing) - buoyancy99) ![Star](https://img.shields.io/github/stars/buoyancy99/diffusion-forcing.svg?style=social&label=Star)
- [MiniCPM: Unveiling the Potential of End-side Large Language Models](https://shengdinghu.notion.site/MiniCPM-Unveiling-the-Potential-of-End-side-Large-Language-Models-d4d3a8c426424654a4e80e42a711cb20)
- **Adam-mini: Use Fewer Learning Rates To Gain More**, `arXiv, 2406.16793`, [arxiv](http://arxiv.org/abs/2406.16793v2), [pdf](http://arxiv.org/pdf/2406.16793v2.pdf), cication: [**-1**](None)

	 *Yushun Zhang, Congliang Chen, Ziniu Li, Tian Ding, Chenwei Wu, Yinyu Ye, Zhi-Quan Luo, Ruoyu Sun*
- **Be like a Goldfish, Don't Memorize! Mitigating Memorization in
  Generative LLMs**, `arXiv, 2406.10209`, [arxiv](http://arxiv.org/abs/2406.10209v1), [pdf](http://arxiv.org/pdf/2406.10209v1.pdf), cication: [**-1**](None)

	 *Abhimanyu Hans, Yuxin Wen, Neel Jain, John Kirchenbauer, Hamid Kazemi, Prajwal Singhania, Siddharth Singh, Gowthami Somepalli, Jonas Geiping, Abhinav Bhatele* · ([goldfish-loss](https://github.com/ahans30/goldfish-loss) - ahans30) ![Star](https://img.shields.io/github/stars/ahans30/goldfish-loss.svg?style=social&label=Star)
- **2BP: 2-Stage Backpropagation**, `arXiv, 2405.18047`, [arxiv](http://arxiv.org/abs/2405.18047v1), [pdf](http://arxiv.org/pdf/2405.18047v1.pdf), cication: [**-1**](None)

	 *Christopher Rae, Joseph K. L. Lee, James Richings*
- **The Road Less Scheduled**, `arXiv, 2405.15682`, [arxiv](http://arxiv.org/abs/2405.15682v1), [pdf](http://arxiv.org/pdf/2405.15682v1.pdf), cication: [**-1**](None)

	 *Aaron Defazio, Xingyu, Yang, Harsh Mehta, Konstantin Mishchenko, Ahmed Khaled, Ashok Cutkosky* · ([schedule_free](https://github.com/facebookresearch/schedule_free) - facebookresearch) ![Star](https://img.shields.io/github/stars/facebookresearch/schedule_free.svg?style=social&label=Star)
- **Thermodynamic Natural Gradient Descent**, `arXiv, 2405.13817`, [arxiv](http://arxiv.org/abs/2405.13817v1), [pdf](http://arxiv.org/pdf/2405.13817v1.pdf), cication: [**-1**](None)

	 *Kaelan Donatella, Samuel Duffield, Maxwell Aifer, Denis Melanson, Gavin Crooks, Patrick J. Coles*
- **The Entropy Enigma: Success and Failure of Entropy Minimization**, `arXiv, 2405.05012`, [arxiv](http://arxiv.org/abs/2405.05012v2), [pdf](http://arxiv.org/pdf/2405.05012v2.pdf), cication: [**-1**](None)

	 *Ori Press, Ravid Shwartz-Ziv, Yann LeCun, Matthias Bethge* · ([EntropyEnigma](https://github.com/oripress/EntropyEnigma) - oripress) ![Star](https://img.shields.io/github/stars/oripress/EntropyEnigma.svg?style=social&label=Star)
- [**psgd_torch**](https://github.com/lixilinx/psgd_torch) - lixilinx ![Star](https://img.shields.io/github/stars/lixilinx/psgd_torch.svg?style=social&label=Star)

	 *Pytorch implementation of preconditioned stochastic gradient descent (affine group preconditioner, low-rank approximation preconditioner and more)* · ([Preconditioned-Stochastic-Gradient-Descent](https://github.com/opooladz/Preconditioned-Stochastic-Gradient-Descent) - opooladz) ![Star](https://img.shields.io/github/stars/opooladz/Preconditioned-Stochastic-Gradient-Descent.svg?style=social&label=Star)
- **A Large-Scale Exploration of $μ$-Transfer**, `arXiv, 2404.05728`, [arxiv](http://arxiv.org/abs/2404.05728v1), [pdf](http://arxiv.org/pdf/2404.05728v1.pdf), cication: [**-1**](None)

	 *Lucas Lingle*
- [**schedule_free**](https://github.com/facebookresearch/schedule_free) - facebookresearch ![Star](https://img.shields.io/github/stars/facebookresearch/schedule_free.svg?style=social&label=Star)

	 *Schedule-Free Optimization in PyTorch*
- **Reverse Training to Nurse the Reversal Curse**, `arXiv, 2403.13799`, [arxiv](http://arxiv.org/abs/2403.13799v1), [pdf](http://arxiv.org/pdf/2403.13799v1.pdf), cication: [**-1**](None)

	 *Olga Golovneva, Zeyuan Allen-Zhu, Jason Weston, Sainbayar Sukhbaatar*
- **Towards Optimal Learning of Language Models**, `arXiv, 2402.17759`, [arxiv](http://arxiv.org/abs/2402.17759v1), [pdf](http://arxiv.org/pdf/2402.17759v1.pdf), cication: [**-1**](None)

	 *Yuxian Gu, Li Dong, Yaru Hao, Qingxiu Dong, Minlie Huang, Furu Wei* · ([aka](https://aka.ms/LearningLaw))
- **Stabilizing Transformer Training by Preventing Attention Entropy
  Collapse**, `ICML, 2023`, [arxiv](http://arxiv.org/abs/2303.06296v2), [pdf](http://arxiv.org/pdf/2303.06296v2.pdf), cication: [**-1**](None)

	 *Shuangfei Zhai, Tatiana Likhomanenko, Etai Littwin, Dan Busbridge, Jason Ramapuram, Yizhe Zhang, Jiatao Gu, Josh Susskind* · ([ml-sigma-reparam](https://github.com/apple/ml-sigma-reparam) - apple) ![Star](https://img.shields.io/github/stars/apple/ml-sigma-reparam.svg?style=social&label=Star)
- **CAME: Confidence-guided Adaptive Memory Efficient Optimization**, `arXiv, 2307.02047`, [arxiv](http://arxiv.org/abs/2307.02047v2), [pdf](http://arxiv.org/pdf/2307.02047v2.pdf), cication: [**-1**](None)

	 *Yang Luo, Xiaozhe Ren, Zangwei Zheng, Zhuo Jiang, Xin Jiang, Yang You* · ([qbitai](https://www.qbitai.com/2023/07/67814.html))

---
- [Adam学习率Scaling law的「浪涌现象」](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247496722&idx=1&sn=26b0b52e8497b7af6182b6eab7e6e103)
- [用最酷的LR，训最猛的模型](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247496626&idx=1&sn=4ba786f28cd4f55d69ed91effe3e82fd)

## Ensemble
- **Octopus v4: Graph of language models**, `arXiv, 2404.19296`, [arxiv](http://arxiv.org/abs/2404.19296v1), [pdf](http://arxiv.org/pdf/2404.19296v1.pdf), cication: [**-1**](None)

	 *Wei Chen, Zhiyuan Li*
- **Training-Free Pretrained Model Merging**, `arXiv, 2403.01753`, [arxiv](http://arxiv.org/abs/2403.01753v3), [pdf](http://arxiv.org/pdf/2403.01753v3.pdf), cication: [**-1**](None)

	 *Zhengqi Xu, Ke Yuan, Huiqiong Wang, Yong Wang, Mingli Song, Jie Song*
	- `The proposed model merging framework addresses the challenge of balancing unit similarity inconsistencies between weight and activation spaces during model merging by linearly combining similarity matrices of both, resulting in better multi-task model performance.`
- **Evolutionary Optimization of Model Merging Recipes**, `arXiv, 2403.13187`, [arxiv](http://arxiv.org/abs/2403.13187v1), [pdf](http://arxiv.org/pdf/2403.13187v1.pdf), cication: [**-1**](None)

	 *Takuya Akiba, Makoto Shing, Yujin Tang, Qi Sun, David Ha*

	 · ([evolutionary-model-merge](https://github.com/sakanaai/evolutionary-model-merge) - sakanaai) ![Star](https://img.shields.io/github/stars/sakanaai/evolutionary-model-merge.svg?style=social&label=Star)
- **Branch-Train-MiX: Mixing Expert LLMs into a Mixture-of-Experts LLM**, `arXiv, 2403.07816`, [arxiv](http://arxiv.org/abs/2403.07816v1), [pdf](http://arxiv.org/pdf/2403.07816v1.pdf), cication: [**-1**](None)

	 *Sainbayar Sukhbaatar, Olga Golovneva, Vasu Sharma, Hu Xu, Xi Victoria Lin, Baptiste Rozière, Jacob Kahn, Daniel Li, Wen-tau Yih, Jason Weston*
- [**AutoMerger**](https://huggingface.co/spaces/mlabonne/AutoMerger) - mlabonne 🤗

	 · ([huggingface](https://huggingface.co/blog/mlabonne/merge-models))
- **Learning to Decode Collaboratively with Multiple Language Models**, `arXiv, 2403.03870`, [arxiv](http://arxiv.org/abs/2403.03870v1), [pdf](http://arxiv.org/pdf/2403.03870v1.pdf), cication: [**-1**](None)

	 *Shannon Zejiang Shen, Hunter Lang, Bailin Wang, Yoon Kim, David Sontag* · ([co-llm](https://github.com/clinicalml/co-llm) - clinicalml) ![Star](https://img.shields.io/github/stars/clinicalml/co-llm.svg?style=social&label=Star)
- **FuseChat: Knowledge Fusion of Chat Models**, `arXiv, 2402.16107`, [arxiv](http://arxiv.org/abs/2402.16107v1), [pdf](http://arxiv.org/pdf/2402.16107v1.pdf), cication: [**-1**](None)

	 *Fanqi Wan, Ziyi Yang, Longguang Zhong, Xiaojun Quan, Xinting Huang, Wei Bi* · ([FuseLLM](https://github.com/fanqiwan/FuseLLM) - fanqiwan) ![Star](https://img.shields.io/github/stars/fanqiwan/FuseLLM.svg?style=social&label=Star)
- **Knowledge Fusion of Large Language Models**, `arXiv, 2401.10491`, [arxiv](http://arxiv.org/abs/2401.10491v1), [pdf](http://arxiv.org/pdf/2401.10491v1.pdf), cication: [**-1**](None)

	 *Fanqi Wan, Xinting Huang, Deng Cai, Xiaojun Quan, Wei Bi, Shuming Shi* · ([FuseLLM](https://github.com/fanqiwan/FuseLLM) - fanqiwan) ![Star](https://img.shields.io/github/stars/fanqiwan/FuseLLM.svg?style=social&label=Star)
- [**Beagle14-7B**](https://huggingface.co/mlabonne/Beagle14-7B) - mlabonne 🤗
- **Blending Is All You Need: Cheaper, Better Alternative to
  Trillion-Parameters LLM**, `arXiv, 2401.02994`, [arxiv](http://arxiv.org/abs/2401.02994v1), [pdf](http://arxiv.org/pdf/2401.02994v1.pdf), cication: [**-1**](None)

	 *Xiaoding Lu, Adian Liusie, Vyas Raina, Yuwen Zhang, William Beauchamp*
- **LLM Augmented LLMs: Expanding Capabilities through Composition**, `arXiv, 2401.02412`, [arxiv](http://arxiv.org/abs/2401.02412v1), [pdf](http://arxiv.org/pdf/2401.02412v1.pdf), cication: [**8**](https://scholar.google.com/scholar?cites=3668029210306898471&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Rachit Bansal, Bidisha Samanta, Siddharth Dalmia, Nitish Gupta, Shikhar Vashishth, Sriram Ganapathy, Abhishek Bapna, Prateek Jain, Partha Talukdar*
- [Model Merging - a osanseviero Collection](https://huggingface.co/collections/osanseviero/model-merging-65097893623330a3a51ead66)
- [Papers about model merging - a julien-c Collection](https://huggingface.co/collections/julien-c/papers-about-model-merging-659596e6fa54621c41cd60b1)
- [**mergekit**](https://github.com/cg123/mergekit) - cg123 ![Star](https://img.shields.io/github/stars/cg123/mergekit.svg?style=social&label=Star)

	 *Tools for merging pretrained large language models.*
- **LM-Cocktail: Resilient Tuning of Language Models via Model Merging**, `arXiv, 2311.13534`, [arxiv](http://arxiv.org/abs/2311.13534v4), [pdf](http://arxiv.org/pdf/2311.13534v4.pdf), cication: [**-1**](None)

	 *Shitao Xiao, Zheng Liu, Peitian Zhang, Xingrun Xing* · ([FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding/tree/master/LM_Cocktail) - FlagOpen) ![Star](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding.svg?style=social&label=Star)
- **Routing to the Expert: Efficient Reward-guided Ensemble of Large
  Language Models**, `arXiv, 2311.08692`, [arxiv](http://arxiv.org/abs/2311.08692v1), [pdf](http://arxiv.org/pdf/2311.08692v1.pdf), cication: [**-1**](None)

	 *Keming Lu, Hongyi Yuan, Runji Lin, Junyang Lin, Zheng Yuan, Chang Zhou, Jingren Zhou*
- **Language Models are Super Mario: Absorbing Abilities from Homologous
  Models as a Free Lunch**, `arXiv, 2311.03099`, [arxiv](http://arxiv.org/abs/2311.03099v1), [pdf](http://arxiv.org/pdf/2311.03099v1.pdf), cication: [**-1**](None)

	 *Le Yu, Bowen Yu, Haiyang Yu, Fei Huang, Yongbin Li* · ([mergelm](https://github.com/yule-buaa/mergelm) - yule-buaa) ![Star](https://img.shields.io/github/stars/yule-buaa/mergelm.svg?style=social&label=Star)
- **LLM-Blender: Ensembling Large Language Models with Pairwise Ranking and
  Generative Fusion**, `arXiv, 2306.02561`, [arxiv](http://arxiv.org/abs/2306.02561v3), [pdf](http://arxiv.org/pdf/2306.02561v3.pdf), cication: [**16**](https://scholar.google.com/scholar?cites=3251394917352088026&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Dongfu Jiang, Xiang Ren, Bill Yuchen Lin* · ([LLM-Blender](https://github.com/yuchenlin/LLM-Blender) - yuchenlin) ![Star](https://img.shields.io/github/stars/yuchenlin/LLM-Blender.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652343982&idx=4&sn=ce5c51039d91531178257024d883db90))

### Other
- [Evolutionary Model Merging For All](https://blog.arcee.ai/tutorial-tutorial-how-to-get-started-with-evolutionary-model-merging/)
- [**mergekit-gui**](https://huggingface.co/spaces/julien-c/mergekit-gui) - julien-c 🤗
- [Model merging lessons in The Waifu Research Department](https://www.interconnects.ai/p/model-merging)
- [Model Merging - a osanseviero Collection](https://huggingface.co/collections/osanseviero/model-merging-65097893623330a3a51ead66)
- [🤗 PEFT welcomes new merging methods](https://huggingface.co/blog/peft_merging)
- [Weight averaging and model merging for LLMs seem to be the most interesting themes in 2024 so far. ](https://twitter.com/rasbt/status/1750180383398744106)

## MoE
- **A Closer Look into Mixture-of-Experts in Large Language Models**, `arXiv, 2406.18219`, [arxiv](http://arxiv.org/abs/2406.18219v1), [pdf](http://arxiv.org/pdf/2406.18219v1.pdf), cication: [**-1**](None)

	 *Ka Man Lo, Zeyu Huang, Zihan Qiu, Zili Wang, Jie Fu* · ([Look-into-MoEs](https://github.com/kamanphoebe/Look-into-MoEs) - kamanphoebe) ![Star](https://img.shields.io/github/stars/kamanphoebe/Look-into-MoEs.svg?style=social&label=Star)
- **Self-MoE: Towards Compositional Large Language Models with
  Self-Specialized Experts**, `arXiv, 2406.12034`, [arxiv](http://arxiv.org/abs/2406.12034v1), [pdf](http://arxiv.org/pdf/2406.12034v1.pdf), cication: [**-1**](None)

	 *Junmo Kang, Leonid Karlinsky, Hongyin Luo, Zhen Wang, Jacob Hansen, James Glass, David Cox, Rameswar Panda, Rogerio Feris, Alan Ritter*
- **Skywork-MoE: A Deep Dive into Training Techniques for Mixture-of-Experts
  Language Models**, `arXiv, 2406.06563`, [arxiv](http://arxiv.org/abs/2406.06563v1), [pdf](http://arxiv.org/pdf/2406.06563v1.pdf), cication: [**-1**](None)

	 *Tianwen Wei, Bo Zhu, Liang Zhao, Cheng Cheng, Biye Li, Weiwei Lü, Peng Cheng, Jianhao Zhang, Xiaoyu Zhang, Liang Zeng*
- **MoEUT: Mixture-of-Experts Universal Transformers**, `arXiv, 2405.16039`, [arxiv](http://arxiv.org/abs/2405.16039v1), [pdf](http://arxiv.org/pdf/2405.16039v1.pdf), cication: [**-1**](None)

	 *Róbert Csordás, Kazuki Irie, Jürgen Schmidhuber, Christopher Potts, Christopher D. Manning* · ([moeut](https://github.com/robertcsordas/moeut) - robertcsordas) ![Star](https://img.shields.io/github/stars/robertcsordas/moeut.svg?style=social&label=Star)
- **Multi-Head Mixture-of-Experts**, `arXiv, 2404.15045`, [arxiv](http://arxiv.org/abs/2404.15045v1), [pdf](http://arxiv.org/pdf/2404.15045v1.pdf), cication: [**-1**](None)

	 *Xun Wu, Shaohan Huang, Wenhui Wang, Furu Wei*
- [**mergoo**](https://github.com/Leeroo-AI/mergoo) - Leeroo-AI ![Star](https://img.shields.io/github/stars/Leeroo-AI/mergoo.svg?style=social&label=Star)

	 *A library for easily merging multiple LLM experts, and efficiently train the merged LLM.*
- **Mixture-of-Depths: Dynamically allocating compute in transformer-based
  language models**, `arXiv, 2404.02258`, [arxiv](http://arxiv.org/abs/2404.02258v1), [pdf](http://arxiv.org/pdf/2404.02258v1.pdf), cication: [**-1**](None)

	 *David Raposo, Sam Ritter, Blake Richards, Timothy Lillicrap, Peter Conway Humphreys, Adam Santoro* · ([qbitai](https://www.qbitai.com/2024/04/133189.html)) · ([OLMo](https://github.com/thepowerfuldeez/OLMo/blob/main/olmo/mod.py) - thepowerfuldeez) ![Star](https://img.shields.io/github/stars/thepowerfuldeez/OLMo.svg?style=social&label=Star) · ([twitter](https://twitter.com/haeggee/status/1776166583959687444))
- [**JetMoE**](https://github.com/myshell-ai/JetMoE) - myshell-ai ![Star](https://img.shields.io/github/stars/myshell-ai/JetMoE.svg?style=social&label=Star)

	 *Reaching LLaMA2 Performance with 0.1M Dollars*

	 · ([research.myshell](https://research.myshell.ai/jetmoe))
	- `JetMoE-8B has 24 blocks where each block has two MoE layers: Mixture of Attention heads (MoA) and Mixture of MLP Experts (MoE); each MoA and MoE layer has 8 experts, and 2 experts are activated for each input token with 2.2B active parameters.`
- [**megablocks**](https://github.com/databricks/megablocks) - databricks ![Star](https://img.shields.io/github/stars/databricks/megablocks.svg?style=social&label=Star)
- **Scattered Mixture-of-Experts Implementation**, `arXiv, 2403.08245`, [arxiv](http://arxiv.org/abs/2403.08245v1), [pdf](http://arxiv.org/pdf/2403.08245v1.pdf), cication: [**-1**](None)

	 *Shawn Tan, Yikang Shen, Rameswar Panda, Aaron Courville*
- **Scaling Laws for Fine-Grained Mixture of Experts**, `arXiv, 2402.07871`, [arxiv](http://arxiv.org/abs/2402.07871v1), [pdf](http://arxiv.org/pdf/2402.07871v1.pdf), cication: [**-1**](None)

	 *Jakub Krajewski, Jan Ludziejewski, Kamil Adamczewski, Maciej Pióro, Michał Krutul, Szymon Antoniak, Kamil Ciebiera, Krystian Król, Tomasz Odrzygóźdź, Piotr Sankowski*
- **BlackMamba: Mixture of Experts for State-Space Models**, `arXiv, 2402.01771`, [arxiv](http://arxiv.org/abs/2402.01771v1), [pdf](http://arxiv.org/pdf/2402.01771v1.pdf), cication: [**-1**](None)

	 *Quentin Anthony, Yury Tokpanov, Paolo Glorioso, Beren Millidge* · ([BlackMamba](https://github.com/Zyphra/BlackMamba) - Zyphra) ![Star](https://img.shields.io/github/stars/Zyphra/BlackMamba.svg?style=social&label=Star)
- **LocMoE: A Low-overhead MoE for Large Language Model Training**, `arXiv, 2401.13920`, [arxiv](http://arxiv.org/abs/2401.13920v1), [pdf](http://arxiv.org/pdf/2401.13920v1.pdf), cication: [**-1**](None)

	 *Jing Li, Zhijie Sun, Xuan He, Li Zeng, Yi Lin, Entong Li, Binfan Zheng, Rongqian Zhao, Xin Chen* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-02-04-6))
- **MoE-Mamba: Efficient Selective State Space Models with Mixture of
  Experts**, `arXiv, 2401.04081`, [arxiv](http://arxiv.org/abs/2401.04081v1), [pdf](http://arxiv.org/pdf/2401.04081v1.pdf), cication: [**-1**](None)

	 *Maciej Pióro, Kamil Ciebiera, Krystian Król, Jan Ludziejewski, Sebastian Jaszczur*
- **DeepSeekMoE: Towards Ultimate Expert Specialization in
  Mixture-of-Experts Language Models**, `arXiv, 2401.06066`, [arxiv](http://arxiv.org/abs/2401.06066v1), [pdf](http://arxiv.org/pdf/2401.06066v1.pdf), cication: [**-1**](None)

	 *Damai Dai, Chengqi Deng, Chenggang Zhao, R. X. Xu, Huazuo Gao, Deli Chen, Jiashi Li, Wangding Zeng, Xingkai Yu, Y. Wu* · ([DeepSeek-MoE](https://github.com/deepseek-ai/DeepSeek-MoE) - deepseek-ai) ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-MoE.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/deepseek-ai/deepseek-moe-16b-chat))
- **Mixtral of Experts**, `arXiv, 2401.04088`, [arxiv](http://arxiv.org/abs/2401.04088v1), [pdf](http://arxiv.org/pdf/2401.04088v1.pdf), cication: [**-1**](None)

	 *Albert Q. Jiang, Alexandre Sablayrolles, Antoine Roux, Arthur Mensch, Blanche Savary, Chris Bamford, Devendra Singh Chaplot, Diego de las Casas, Emma Bou Hanna, Florian Bressand*
- **MoE-Mamba: Efficient Selective State Space Models with Mixture of
  Experts**, `arXiv, 2401.04081`, [arxiv](http://arxiv.org/abs/2401.04081v1), [pdf](http://arxiv.org/pdf/2401.04081v1.pdf), cication: [**-1**](None)

	 *Maciej Pióro, Kamil Ciebiera, Krystian Król, Jan Ludziejewski, Sebastian Jaszczur*
- **Mixture of Cluster-conditional LoRA Experts for Vision-language
  Instruction Tuning**, `arXiv, 2312.12379`, [arxiv](http://arxiv.org/abs/2312.12379v1), [pdf](http://arxiv.org/pdf/2312.12379v1.pdf), cication: [**-1**](None)

	 *Yunhao Gou, Zhili Liu, Kai Chen, Lanqing Hong, Hang Xu, Aoxue Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang* · ([qbitai](https://www.qbitai.com/2023/12/110658.html))

- **SwitchHead: Accelerating Transformers with Mixture-of-Experts Attention**, `arXiv, 2312.07987`, [arxiv](http://arxiv.org/abs/2312.07987v2), [pdf](http://arxiv.org/pdf/2312.07987v2.pdf), cication: [**-1**](None)

	 *Róbert Csordás, Piotr Piękos, Kazuki Irie, Jürgen Schmidhuber*

	 · ([moe_attention](https://github.com/robertcsordas/moe_attention) - robertcsordas) ![Star](https://img.shields.io/github/stars/robertcsordas/moe_attention.svg?style=social&label=Star)
- [Mixture of Experts Explained](https://huggingface.co/blog/moe)
- [**megablocks-public**](https://github.com/mistralai/megablocks-public) - mistralai ![Star](https://img.shields.io/github/stars/mistralai/megablocks-public.svg?style=social&label=Star)

	 · ([qbitai](https://www.qbitai.com/2023/12/105154.html))
- [**llama-mistral**](https://github.com/dzhulgakov/llama-mistral?tab=readme-ov-file) - dzhulgakov ![Star](https://img.shields.io/github/stars/dzhulgakov/llama-mistral?tab=readme-ov-file.svg?style=social&label=Star)

	 *Inference code for Mistral and Mixtral hacked up into original Llama implementation*
- [**SmartMoE**](https://github.com/zms1999/SmartMoE) - zms1999 ![Star](https://img.shields.io/github/stars/zms1999/SmartMoE.svg?style=social&label=Star)

	 *A MoE impl for PyTorch, [ATC'23] SmartMoE* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-07-7))
- **Mixture-of-Experts Meets Instruction Tuning:A Winning Combination for
  Large Language Models**, `arXiv, 2305.14705`, [arxiv](http://arxiv.org/abs/2305.14705v2), [pdf](http://arxiv.org/pdf/2305.14705v2.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=9670032780085101117&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Sheng Shen, Le Hou, Yanqi Zhou, Nan Du, Shayne Longpre, Jason Wei, Hyung Won Chung, Barret Zoph, William Fedus, Xinyun Chen* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-07-9))
- **OpenMoE: An Early Effort on Open Mixture-of-Experts Language Models**, `arXiv, 2402.01739`, [arxiv](http://arxiv.org/abs/2402.01739v1), [pdf](http://arxiv.org/pdf/2402.01739v1.pdf), cication: [**-1**](None)

	 *Fuzhao Xue, Zian Zheng, Yao Fu, Jinjie Ni, Zangwei Zheng, Wangchunshu Zhou, Yang You*
- [**OpenMoE**](https://github.com/XueFuzhao/OpenMoE) - XueFuzhao ![Star](https://img.shields.io/github/stars/XueFuzhao/OpenMoE.svg?style=social&label=Star)

	 *A family of open-sourced Mixture-of-Experts (MoE) Large Language Models*


	 · ([OpenMoE](https://github.com/XueFuzhao/OpenMoE/blob/main/paper/paper.pdf) - XueFuzhao) ![Star](https://img.shields.io/github/stars/XueFuzhao/OpenMoE.svg?style=social&label=Star)
- **Mixture-of-Experts Meets Instruction Tuning:A Winning Combination for
  Large Language Models**, `arXiv, 2305.14705`, [arxiv](http://arxiv.org/abs/2305.14705v2), [pdf](http://arxiv.org/pdf/2305.14705v2.pdf), cication: [**-1**](None)

	 *Sheng Shen, Le Hou, Yanqi Zhou, Nan Du, Shayne Longpre, Jason Wei, Hyung Won Chung, Barret Zoph, William Fedus, Xinyun Chen*
- **MegaBlocks: Efficient Sparse Training with Mixture-of-Experts**, `proceedings of machine learning and systems, 2023`, [arxiv](http://arxiv.org/abs/2211.15841v1), [pdf](http://arxiv.org/pdf/2211.15841v1.pdf), cication: [**-1**](None)

	 *Trevor Gale, Deepak Narayanan, Cliff Young, Matei Zaharia*
- **Switch Transformers: Scaling to Trillion Parameter Models with Simple
  and Efficient Sparsity**, `the journal of machine learning research, 2022`, [arxiv](http://arxiv.org/abs/2101.03961v3), [pdf](http://arxiv.org/pdf/2101.03961v3.pdf), cication: [**-1**](None)

	 *William Fedus, Barret Zoph, Noam Shazeer*
- **GShard: Scaling Giant Models with Conditional Computation and Automatic
  Sharding**, `arXiv, 2006.16668`, [arxiv](http://arxiv.org/abs/2006.16668v1), [pdf](http://arxiv.org/pdf/2006.16668v1.pdf), cication: [**-1**](None)

	 *Dmitry Lepikhin, HyoukJoong Lee, Yuanzhong Xu, Dehao Chen, Orhan Firat, Yanping Huang, Maxim Krikun, Noam Shazeer, Zhifeng Chen*
- **Outrageously Large Neural Networks: The Sparsely-Gated
  Mixture-of-Experts Layer**, `arXiv, 1701.06538`, [arxiv](http://arxiv.org/abs/1701.06538v1), [pdf](http://arxiv.org/pdf/1701.06538v1.pdf), cication: [**-1**](None)

	 *Noam Shazeer, Azalia Mirhoseini, Krzysztof Maziarz, Andy Davis, Quoc Le, Geoffrey Hinton, Jeff Dean*

### Other
- [How do mixture-of-experts layers affect transformer models? - Stack Overflow](https://stackoverflow.blog/2024/04/04/how-do-mixture-of-experts-layers-affect-transformer-models)
- [Accelerating MoE model inference with Locality-Aware Kernel Design | PyTorch](https://pytorch.org/blog/accelerating-moe-model/?utm_content=288416924&utm_medium=social&utm_source=twitter&hss_channel=tw-776585502606721024)
- [a mini-tutorial on three types of Mixture of Experts (MoE): Pre-trained MoE, upcycled MoEs, and FrankenMoEs](https://twitter.com/osanseviero/status/1773360705682411750?utm_source=ainews&utm_medium=email&utm_campaign=ainews-evals-based-ai-engineering)
- [**makeMoE**](https://github.com/AviSoori1x/makeMoE/tree/main) - AviSoori1x ![Star](https://img.shields.io/github/stars/AviSoori1x/makeMoE.svg?style=social&label=Star)

	 *From scratch implementation of a sparse mixture of experts language model inspired by Andrej Karpathy's makemore :)* · ([huggingface](https://huggingface.co/blog/AviSoori1x/makemoe-from-scratch)) · ([qbitai](https://www.qbitai.com/2024/01/117335.html))
- [Mixture of Experts - a mlabonne Collection](https://huggingface.co/collections/mlabonne/mixture-of-experts-65980c40330942d1282b76f5)
- [**8x7B-MoE-test-NOT-MIXTRAL**](https://huggingface.co/CausalLM/8x7B-MoE-test-NOT-MIXTRAL) - CausalLM 🤗

- [从Mixtral-8x7B到LLaMA MOE再到DeepSeek-MoE](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495494&idx=2&sn=78c2bfec35367bd52253efbad8e796ee)
- [模块化大模型来了！IBM公开WastonX核心架构技术细节](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247522084&idx=3&sn=ceba2b0c3e6434599101f7604ff109c4)


##  Online Learning
- **Unlocking Continual Learning Abilities in Language Models**, `arXiv, 2406.17245`, [arxiv](http://arxiv.org/abs/2406.17245v1), [pdf](http://arxiv.org/pdf/2406.17245v1.pdf), cication: [**-1**](None)

	 *Wenyu Du, Shuang Cheng, Tongxu Luo, Zihan Qiu, Zeyu Huang, Ka Chun Cheung, Reynold Cheng, Jie Fu* · ([MIGU](https://github.com/wenyudu/MIGU) - wenyudu) ![Star](https://img.shields.io/github/stars/wenyudu/MIGU.svg?style=social&label=Star)
- **Online Training of Large Language Models: Learn while chatting**, `arXiv, 2403.04790`, [arxiv](http://arxiv.org/abs/2403.04790v1), [pdf](http://arxiv.org/pdf/2403.04790v1.pdf), cication: [**-1**](None)

	 *Juhao Liang, Ziwei Wang, Zhuoheng Ma, Jianquan Li, Zhiyi Zhang, Xiangbo Wu, Benyou Wang*

## Toolkits
- [**mistral-finetune**](https://github.com/mistralai/mistral-finetune) - mistralai ![Star](https://img.shields.io/github/stars/mistralai/mistral-finetune.svg?style=social&label=Star)
- [ZeRO++ - DeepSpeed](https://www.deepspeed.ai/tutorials/zeropp/)
- [**torchtitan**](https://github.com/pytorch/torchtitan) - pytorch ![Star](https://img.shields.io/github/stars/pytorch/torchtitan.svg?style=social&label=Star)

	 *A native PyTorch Library for large model training*
- [**ColossalAI**](https://github.com/hpcaitech/ColossalAI) - hpcaitech ![Star](https://img.shields.io/github/stars/hpcaitech/ColossalAI.svg?style=social&label=Star)

	 *Making large AI models cheaper, faster and more accessible*
- [**xtuner**](https://github.com/InternLM/xtuner) - InternLM ![Star](https://img.shields.io/github/stars/InternLM/xtuner.svg?style=social&label=Star)

	 *An efficient, flexible and full-featured toolkit for fine-tuning large models (InternLM, Llama, Baichuan, Qwen, ChatGLM)*
- [**corenet**](https://github.com/apple/corenet) - apple ![Star](https://img.shields.io/github/stars/apple/corenet.svg?style=social&label=Star)

	 *CoreNet: A library for training deep neural networks*
- [**maxtext**](https://github.com/google/maxtext) - google ![Star](https://img.shields.io/github/stars/google/maxtext.svg?style=social&label=Star)

	 *A simple, performant and scalable Jax LLM!*
- [**lightning-thunder**](https://github.com/Lightning-AI/lightning-thunder) - Lightning-AI ![Star](https://img.shields.io/github/stars/Lightning-AI/lightning-thunder.svg?style=social&label=Star)

	 *Source to source compiler for PyTorch. It makes PyTorch programs faster on single accelerators and distributed.*
- [**zero-bubble-pipeline-parallelism**](https://github.com/sail-sg/zero-bubble-pipeline-parallelism) - sail-sg ![Star](https://img.shields.io/github/stars/sail-sg/zero-bubble-pipeline-parallelism.svg?style=social&label=Star)

	 *Zero Bubble Pipeline Parallelism* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247541193&idx=3&sn=eadcb731bffb88d56cecbc3d60acbae3))
- [**levanter**](https://github.com/stanford-crfm/levanter) - stanford-crfm ![Star](https://img.shields.io/github/stars/stanford-crfm/levanter.svg?style=social&label=Star)

	 *Legibile, Scalable, Reproducible Foundation Models with Named Tensors and Jax*
- [**axolotl**](https://github.com/OpenAccess-AI-Collective/axolotl) - OpenAccess-AI-Collective ![Star](https://img.shields.io/github/stars/OpenAccess-AI-Collective/axolotl.svg?style=social&label=Star)

	 *Go ahead and axolotl questions*
- [**LLMtuner**](https://github.com/promptslab/LLMtuner) - promptslab ![Star](https://img.shields.io/github/stars/promptslab/LLMtuner.svg?style=social&label=Star)

	 *Tune LLM in few lines of code*
- [**LLM-FineTuning-Large-Language-Models**](https://github.com/rohan-paul/LLM-FineTuning-Large-Language-Models) - rohan-paul ![Star](https://img.shields.io/github/stars/rohan-paul/LLM-FineTuning-Large-Language-Models.svg?style=social&label=Star)

	 *LLM (Large Language Model) FineTuning*
- [**Megatron-LM**](https://github.com/NVIDIA/Megatron-LM) - NVIDIA ![Star](https://img.shields.io/github/stars/NVIDIA/Megatron-LM.svg?style=social&label=Star)

	 *Ongoing research training transformer models at scale*
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
- [Fetching Title#hxa6](https://magazine.sebastianraschka.com/p/using-and-finetuning-pretrained-transformers)
- [Pathways 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1xB4y1m7Xi/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)
- [GPipe论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1v34y1E7zu/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)
- [Megatron LM 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1nB4y1R7Yz/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)
- [Zero 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1tY411g7ZT/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)

## Other
- [**deepspeed-to-fsdp-and-back**](https://huggingface.co/blog/deepspeed-to-fsdp-and-back) -  🤗
- [Training great LLMs entirely from ground zero in the wilderness as a startup — Yi Tay](https://www.yitay.net/blog/training-great-llms-entirely-from-ground-zero-in-the-wilderness)

	 · ([twitter](https://twitter.com/karpathy/status/1765424847705047247)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652453339&idx=2&sn=15a1060927a2fe7e56d2dc5bfd3e1db1))
- [Fine-tuning Llama 2 70B using PyTorch FSDP](https://huggingface.co/blog/ram-efficient-pytorch-fsdp)
- [Everything about Distributed Training and Efficient Finetuning | Sumanth's Personal Website](https://sumanthrh.com/post/distributed-and-efficient-finetuning/)

- [如何从零开始训练大模型（minicpm分享&讨论） - 知乎](https://zhuanlan.zhihu.com/p/686664720)
- [0代码微调大模型火了，只需5步，成本低至150块 | 量子位](https://www.qbitai.com/2023/07/66833.html)
- [GPU 利用率低常见原因分析及优化](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247609210&idx=3&sn=01686c5f7d7d70d4383667296ae7d823)

## Extra reference 
- [**llm-alignment-survey**](https://github.com/Magnetic2014/llm-alignment-survey) - Magnetic2014 ![Star](https://img.shields.io/github/stars/Magnetic2014/llm-alignment-survey.svg?style=social&label=Star)

	 *A curated reading list for large language model (LLM) alignment. Take a look at our new survey "Large Language Model Alignment: A Survey" for more details!*