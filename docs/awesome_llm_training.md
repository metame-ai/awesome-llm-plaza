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

- [贫穷让我预训练](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494110&idx=2&sn=52bfbf2d51d1704efc596263bccf23db)

## Scaling
- **DiPaCo: Distributed Path Composition**, `arXiv, 2403.10616`, [arxiv](http://arxiv.org/abs/2403.10616v1), [pdf](http://arxiv.org/pdf/2403.10616v1.pdf), cication: [**-1**](None)

	 *Arthur Douillard, Qixuan Feng, Andrei A. Rusu, Adhiguna Kuncoro, Yani Donchev, Rachita Chhaparia, Ionel Gog, Marc'Aurelio Ranzato, Jiajun Shen, Arthur Szlam*
- **Algorithmic progress in language models**, `arXiv, 2403.05812`, [arxiv](http://arxiv.org/abs/2403.05812v1), [pdf](http://arxiv.org/pdf/2403.05812v1.pdf), cication: [**-1**](None)

	 *Anson Ho, Tamay Besiroglu, Ege Erdil, David Owen, Robi Rahman, Zifan Carl Guo, David Atkinson, Neil Thompson, Jaime Sevilla*

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652455514&idx=3&sn=8955e6ac82257fc0b3da29e34d1e5467))
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
- [Techniques for training large neural networks](https://openai.com/research/techniques-for-training-large-neural-networks)
- [How to Train Really Large Models on Many GPUs? | Lil'Log](https://lilianweng.github.io/posts/2021-09-25-train-large/)
- [Chinchilla之死：只要训练足够长时间，小模型也能超过大模型 | 机器之心](https://www.jiqizhixin.com/articles/2023-10-03-9)

## Fine-tuning
- **LlamaFactory: Unified Efficient Fine-Tuning of 100+ Language Models**, `arXiv, 2403.13372`, [arxiv](http://arxiv.org/abs/2403.13372v1), [pdf](http://arxiv.org/pdf/2403.13372v1.pdf), cication: [**-1**](None)

	 *Yaowei Zheng, Richong Zhang, Junhao Zhang, Yanhan Ye, Zheyan Luo* · ([LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) - hiyouga) ![Star](https://img.shields.io/github/stars/hiyouga/LLaMA-Factory.svg?style=social&label=Star)
- **Reawakening knowledge: Anticipatory recovery from catastrophic
  interference via structured training**, `arXiv, 2403.09613`, [arxiv](http://arxiv.org/abs/2403.09613v1), [pdf](http://arxiv.org/pdf/2403.09613v1.pdf), cication: [**-1**](None)

	 *Yanlai Yang, Matt Jones, Michael C. Mozer, Mengye Ren*
- **Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for
  Large Language Models**, `arXiv, 2403.12881`, [arxiv](http://arxiv.org/abs/2403.12881v1), [pdf](http://arxiv.org/pdf/2403.12881v1.pdf), cication: [**-1**](None)

	 *Zehui Chen, Kuikun Liu, Qiuchen Wang, Wenwei Zhang, Jiangning Liu, Dahua Lin, Kai Chen, Feng Zhao* · ([Agent-FLAN](https://github.com/InternLM/Agent-FLAN) - InternLM) ![Star](https://img.shields.io/github/stars/InternLM/Agent-FLAN.svg?style=social&label=Star)
- **Larimar: Large Language Models with Episodic Memory Control**, `arXiv, 2403.11901`, [arxiv](http://arxiv.org/abs/2403.11901v1), [pdf](http://arxiv.org/pdf/2403.11901v1.pdf), cication: [**-1**](None)

	 *Payel Das, Subhajit Chaudhury, Elliot Nelson, Igor Melnyk, Sarath Swaminathan, Sihui Dai, Aurélie Lozano, Georgios Kollias, Vijil Chenthamarakshan, Jiří*
- **Simple and Scalable Strategies to Continually Pre-train Large Language
  Models**, `arXiv, 2403.08763`, [arxiv](http://arxiv.org/abs/2403.08763v1), [pdf](http://arxiv.org/pdf/2403.08763v1.pdf), cication: [**-1**](None)

	 *Adam Ibrahim, Benjamin Thérien, Kshitij Gupta, Mats L. Richter, Quentin Anthony, Timothée Lesort, Eugene Belilovsky, Irina Rish*

	 · ([twitter](https://twitter.com/rasbt/status/1768629533509370279))
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
- [How to Fine-Tune LLMs in 2024 with Hugging Face](https://www.philschmid.de/fine-tune-llms-in-2024-with-trl)
- [Combating Evaluation Data Contamination in LLMs: Strategies for High-Quality Finetuning and Model Merging](https://huggingface.co/blog/rishiraj/merge-models-without-contamination)
- [Fine-tuning GPT3.5-turbo based on 140k slack messages · Ross Lazerowitz](https://rosslazer.com/posts/fine-tuning/)

## Architectures
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
- **Reverse Training to Nurse the Reversal Curse**, `arXiv, 2403.13799`, [arxiv](http://arxiv.org/abs/2403.13799v1), [pdf](http://arxiv.org/pdf/2403.13799v1.pdf), cication: [**-1**](None)

	 *Olga Golovneva, Zeyuan Allen-Zhu, Jason Weston, Sainbayar Sukhbaatar*
- **Towards Optimal Learning of Language Models**, `arXiv, 2402.17759`, [arxiv](http://arxiv.org/abs/2402.17759v1), [pdf](http://arxiv.org/pdf/2402.17759v1.pdf), cication: [**-1**](None)

	 *Yuxian Gu, Li Dong, Yaru Hao, Qingxiu Dong, Minlie Huang, Furu Wei* · ([aka](https://aka.ms/LearningLaw))
- **Stabilizing Transformer Training by Preventing Attention Entropy
  Collapse**, `ICML, 2023`, [arxiv](http://arxiv.org/abs/2303.06296v2), [pdf](http://arxiv.org/pdf/2303.06296v2.pdf), cication: [**-1**](None)

	 *Shuangfei Zhai, Tatiana Likhomanenko, Etai Littwin, Dan Busbridge, Jason Ramapuram, Yizhe Zhang, Jiatao Gu, Josh Susskind* · ([ml-sigma-reparam](https://github.com/apple/ml-sigma-reparam) - apple) ![Star](https://img.shields.io/github/stars/apple/ml-sigma-reparam.svg?style=social&label=Star)
- **CAME: Confidence-guided Adaptive Memory Efficient Optimization**, `arXiv, 2307.02047`, [arxiv](http://arxiv.org/abs/2307.02047v2), [pdf](http://arxiv.org/pdf/2307.02047v2.pdf), cication: [**-1**](None)

	 *Yang Luo, Xiaozhe Ren, Zangwei Zheng, Zhuo Jiang, Xin Jiang, Yang You* · ([qbitai](https://www.qbitai.com/2023/07/67814.html))
 
## Ensemble
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
- [🤗 PEFT welcomes new merging methods](https://huggingface.co/blog/peft_merging)
- [Weight averaging and model merging for LLMs seem to be the most interesting themes in 2024 so far. ](https://twitter.com/rasbt/status/1750180383398744106)

## MoE
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
- [**makeMoE**](https://github.com/AviSoori1x/makeMoE/tree/main) - AviSoori1x ![Star](https://img.shields.io/github/stars/AviSoori1x/makeMoE.svg?style=social&label=Star)

	 *From scratch implementation of a sparse mixture of experts language model inspired by Andrej Karpathy's makemore :)* · ([huggingface](https://huggingface.co/blog/AviSoori1x/makemoe-from-scratch)) · ([qbitai](https://www.qbitai.com/2024/01/117335.html))
- [Mixture of Experts - a mlabonne Collection](https://huggingface.co/collections/mlabonne/mixture-of-experts-65980c40330942d1282b76f5)
- [**8x7B-MoE-test-NOT-MIXTRAL**](https://huggingface.co/CausalLM/8x7B-MoE-test-NOT-MIXTRAL) - CausalLM 🤗

- [从Mixtral-8x7B到LLaMA MOE再到DeepSeek-MoE](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495494&idx=2&sn=78c2bfec35367bd52253efbad8e796ee)
- [模块化大模型来了！IBM公开WastonX核心架构技术细节](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247522084&idx=3&sn=ceba2b0c3e6434599101f7604ff109c4)


##  Online Learning
- **Online Training of Large Language Models: Learn while chatting**, `arXiv, 2403.04790`, [arxiv](http://arxiv.org/abs/2403.04790v1), [pdf](http://arxiv.org/pdf/2403.04790v1.pdf), cication: [**-1**](None)

	 *Juhao Liang, Ziwei Wang, Zhuoheng Ma, Jianquan Li, Zhiyi Zhang, Xiangbo Wu, Benyou Wang*

## Toolkits
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
- [Pathways 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1xB4y1m7Xi/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)
- [GPipe论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1v34y1E7zu/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)
- [Megatron LM 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1nB4y1R7Yz/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)
- [Zero 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1tY411g7ZT/?spm_id_from=333.788&vd_source=1453a06a1e0b377f5c40946333b4423a)

## Other
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