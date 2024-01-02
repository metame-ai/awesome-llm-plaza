# Awesome llm data

- [Awesome llm data](#awesome-llm-data)
	- [Datasets](#datasets)
		- [Misc](#misc)
		- [MulitiMod](#mulitimod)
		- [Reasoning \& Action](#reasoning--action)
		- [Synthetic](#synthetic)
	- [Toolkits](#toolkits)
	- [Extra reference](#extra-reference)


## Survey
- **Data Management For Large Language Models: A Survey**, `arXiv, 2312.01700`, [arxiv](http://arxiv.org/abs/2312.01700v1), [pdf](http://arxiv.org/pdf/2312.01700v1.pdf), cication: [**-1**](None)

	 *Zige Wang, Wanjun Zhong, Yufei Wang, Qi Zhu, Fei Mi, Baojun Wang, Lifeng Shang, Xin Jiang, Qun Liu*

## Techs
- **What Makes Good Data for Alignment? A Comprehensive Study of Automatic
  Data Selection in Instruction Tuning**, `arXiv, 2312.15685`, [arxiv](http://arxiv.org/abs/2312.15685v1), [pdf](http://arxiv.org/pdf/2312.15685v1.pdf), cication: [**-1**](None)

	 *Wei Liu, Weihao Zeng, Keqing He, Yong Jiang, Junxian He* · ([deita](https://github.com/hkust-nlp/deita) - hkust-nlp) ![Star](https://img.shields.io/github/stars/hkust-nlp/deita.svg?style=social&label=Star)
- **Order Matters in the Presence of Dataset Imbalance for Multilingual
  Learning**, `arXiv, 2312.06134`, [arxiv](http://arxiv.org/abs/2312.06134v1), [pdf](http://arxiv.org/pdf/2312.06134v1.pdf), cication: [**-1**](None)

	 *Dami Choi, Derrick Xin, Hamid Dadkhahi, Justin Gilmer, Ankush Garg, Orhan Firat, Chih-Kuan Yeh, Andrew M. Dai, Behrooz Ghorbani*
- **Scaling Data-Constrained Language Models**, `arXiv, 2305.16264`, [arxiv](http://arxiv.org/abs/2305.16264v4), [pdf](http://arxiv.org/pdf/2305.16264v4.pdf), cication: [**-1**](None)

	 *Niklas Muennighoff, Alexander M. Rush, Boaz Barak, Teven Le Scao, Aleksandra Piktus, Nouamane Tazi, Sampo Pyysalo, Thomas Wolf, Colin Raffel*

	 · ([datablations](https://github.com/huggingface/datablations) - huggingface) ![Star](https://img.shields.io/github/stars/huggingface/datablations.svg?style=social&label=Star)

## Datasets
- [**oasst2**](https://huggingface.co/datasets/OpenAssistant/oasst2) - OpenAssistant 🤗
- [**wikisource**](https://huggingface.co/datasets/wikimedia/wikisource) - wikimedia 🤗
- [**pii-masking-200k**](https://huggingface.co/datasets/ai4privacy/pii-masking-200k) - ai4privacy 🤗
- [**SlimPajama-627B**](https://huggingface.co/datasets/cerebras/SlimPajama-627B) - cerebras  🤗

	 · ([modelzoo](https://github.com/Cerebras/modelzoo/tree/main/modelzoo/transformers/data_processing/slimpajama) - Cerebras) ![Star](https://img.shields.io/github/stars/Cerebras/modelzoo.svg?style=social&label=Star)
- [**MADLAD-400**](https://huggingface.co/datasets/allenai/MADLAD-400) - allenai 🤗
- [**peS2o**](https://huggingface.co/datasets/allenai/peS2o) - allenai 🤗

### Misc
- [**openhathi_instruct**](https://github.com/pacman100/openhathi_instruct) - pacman100 ![Star](https://img.shields.io/github/stars/pacman100/openhathi_instruct.svg?style=social&label=Star)

	 *This repository contains the code for dataset curation and finetuning of instruct variant of the Bilingual OpenHathi model. The resulting model is meant to follow instructions and chat in Hindi and Hinglish.*
- **MADLAD-400: A Multilingual And Document-Level Large Audited Dataset**, `arXiv, 2309.04662`, [arxiv](http://arxiv.org/abs/2309.04662v1), [pdf](http://arxiv.org/pdf/2309.04662v1.pdf), cication: [**-1**](None)

	 *Sneha Kudugunta, Isaac Caswell, Biao Zhang, Xavier Garcia, Christopher A. Choquette-Choo, Katherine Lee, Derrick Xin, Aditya Kusupati, Romi Stella, Ankur Bapna*

	 · ([google-research](https://github.com/google-research/google-research/tree/master/madlad_400) - google-research) ![Star](https://img.shields.io/github/stars/google-research/google-research.svg?style=social&label=Star)
- [Phi-2: The surprising power of small language models - Microsoft Research](https://www.microsoft.com/en-us/research/blog/phi-2-the-surprising-power-of-small-language-models/)
- **What's In My Big Data?**, `arXiv, 2310.20707`, [arxiv](http://arxiv.org/abs/2310.20707v1), [pdf](http://arxiv.org/pdf/2310.20707v1.pdf), cication: [**-1**](None)

	 *Yanai Elazar, Akshita Bhagia, Ian Magnusson, Abhilasha Ravichander, Dustin Schwenk, Alane Suhr, Pete Walsh, Dirk Groeneveld, Luca Soldaini, Sameer Singh*
- [**orca**](https://github.com/nuochenpku/orca) - nuochenpku ![Star](https://img.shields.io/github/stars/nuochenpku/orca.svg?style=social&label=Star)

	 *Orca: A Few-shot Benchmark for Chinese Conversational Machine Reading Comprehension*
- [**UltraFeedback**](https://github.com/OpenBMB/UltraFeedback) - OpenBMB ![Star](https://img.shields.io/github/stars/OpenBMB/UltraFeedback.svg?style=social&label=Star)

	 *A large-scale, fine-grained, diverse preference dataset (and models).*
- **How Abilities in Large Language Models are Affected by Supervised
  Fine-tuning Data Composition**, `arXiv, 2310.05492`, [arxiv](http://arxiv.org/abs/2310.05492v2), [pdf](http://arxiv.org/pdf/2310.05492v2.pdf), cication: [**-1**](None)

	 *Guanting Dong, Hongyi Yuan, Keming Lu, Chengpeng Li, Mingfeng Xue, Dayiheng Liu, Wei Wang, Zheng Yuan, Chang Zhou, Jingren Zhou*
- **LMSYS-Chat-1M: A Large-Scale Real-World LLM Conversation Dataset**, `arXiv, 2309.11998`, [arxiv](http://arxiv.org/abs/2309.11998v3), [pdf](http://arxiv.org/pdf/2309.11998v3.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=1730324882341676130&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lianmin Zheng, Wei-Lin Chiang, Ying Sheng, Tianle Li, Siyuan Zhuang, Zhanghao Wu, Yonghao Zhuang, Zhuohan Li, Zi Lin, Eric. P Xing*
- **SlimPajama-DC: Understanding Data Combinations for LLM Training**, `arXiv, 2309.10818`, [arxiv](http://arxiv.org/abs/2309.10818v2), [pdf](http://arxiv.org/pdf/2309.10818v2.pdf), cication: [**-1**](None)

	 *Zhiqiang Shen, Tianhua Tao, Liqun Ma, Willie Neiswanger, Zhengzhong Liu, Hongyi Wang, Bowen Tan, Joel Hestness, Natalia Vassilieva, Daria Soboleva*
- **CulturaX: A Cleaned, Enormous, and Multilingual Dataset for Large
  Language Models in 167 Languages**, `arXiv, 2309.09400`, [arxiv](http://arxiv.org/abs/2309.09400v1), [pdf](http://arxiv.org/pdf/2309.09400v1.pdf), cication: [**-1**](None)

	 *Thuat Nguyen, Chien Van Nguyen, Viet Dac Lai, Hieu Man, Nghia Trung Ngo, Franck Dernoncourt, Ryan A. Rossi, Thien Huu Nguyen*
- **Textbooks Are All You Need II: phi-1.5 technical report**, `arXiv, 2309.05463`, [arxiv](http://arxiv.org/abs/2309.05463v1), [pdf](http://arxiv.org/pdf/2309.05463v1.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=5479111836130062736&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuanzhi Li, Sébastien Bubeck, Ronen Eldan, Allie Del Giorno, Suriya Gunasekar, Yin Tat Lee*
- **The RefinedWeb Dataset for Falcon LLM: Outperforming Curated Corpora
  with Web Data, and Web Data Only**, `arXiv, 2306.01116`, [arxiv](http://arxiv.org/abs/2306.01116v1), [pdf](http://arxiv.org/pdf/2306.01116v1.pdf), cication: [**108**](https://scholar.google.com/scholar?cites=11817774409349721692&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Guilherme Penedo, Quentin Malartic, Daniel Hesslow, Ruxandra Cojocaru, Alessandro Cappelli, Hamza Alobeidli, Baptiste Pannier, Ebtesam Almazrouei, Julien Launay*
- **FunQA: Towards Surprising Video Comprehension**, `arXiv, 2306.14899`, [arxiv](http://arxiv.org/abs/2306.14899v1), [pdf](http://arxiv.org/pdf/2306.14899v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=8892098396061186028&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Binzhu Xie, Sicheng Zhang, Zitang Zhou, Bo Li, Yuanhan Zhang, Jack Hessel, Jingkang Yang, Ziwei Liu* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652375491&idx=4&sn=1689842b2c0462dca7dd40032a51e7d1))
- **The Belebele Benchmark: a Parallel Reading Comprehension Dataset in 122
  Language Variants**, `arXiv, 2308.16884`, [arxiv](http://arxiv.org/abs/2308.16884v1), [pdf](http://arxiv.org/pdf/2308.16884v1.pdf), cication: [**-1**](None)

	 *Lucas Bandarkar, Davis Liang, Benjamin Muller, Mikel Artetxe, Satya Narayan Shukla, Donald Husa, Naman Goyal, Abhinandan Krishnan, Luke Zettlemoyer, Madian Khabsa*
- **MedAlign: A Clinician-Generated Dataset for Instruction Following with
  Electronic Medical Records**, `arXiv, 2308.14089`, [arxiv](http://arxiv.org/abs/2308.14089v1), [pdf](http://arxiv.org/pdf/2308.14089v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=14452160277245991469&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Scott L. Fleming, Alejandro Lozano, William J. Haberkorn, Jenelle A. Jindal, Eduardo P. Reis, Rahul Thapa, Louis Blankemeier, Julian Z. Genkins, Ethan Steinberg, Ashwin Nayak*
- **Platypus: Quick, Cheap, and Powerful Refinement of LLMs**, `arXiv, 2308.07317`, [arxiv](http://arxiv.org/abs/2308.07317v1), [pdf](http://arxiv.org/pdf/2308.07317v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=7583571905036356732&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ariel N. Lee, Cole J. Hunter, Nataniel Ruiz*
- **Leveraging Implicit Feedback from Deployment Data in Dialogue**, `arXiv, 2307.14117`, [arxiv](http://arxiv.org/abs/2307.14117v1), [pdf](http://arxiv.org/pdf/2307.14117v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=15986635725815668847&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Richard Yuanzhe Pang, Stephen Roller, Kyunghyun Cho, He He, Jason Weston*
- [**UltraChat**](https://github.com/thunlp/UltraChat) - thunlp ![Star](https://img.shields.io/github/stars/thunlp/UltraChat.svg?style=social&label=Star)

	 *Large-scale, Informative, and Diverse Multi-round Chat Data (and Models)*
- **Textbooks Are All You Need**, `arXiv, 2306.11644`, [arxiv](http://arxiv.org/abs/2306.11644v2), [pdf](http://arxiv.org/pdf/2306.11644v2.pdf), cication: [**51**](https://scholar.google.com/scholar?cites=6827925014385411453&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Suriya Gunasekar, Yi Zhang, Jyoti Aneja, Caio César Teodoro Mendes, Allie Del Giorno, Sivakanth Gopi, Mojan Javaheripi, Piero Kauffmann, Gustavo de Rosa, Olli Saarikivi* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-23)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-14-4))


### MulitiMod
- **MADLAD-400: A Multilingual And Document-Level Large Audited Dataset**, `arXiv, 2309.04662`, [arxiv](http://arxiv.org/abs/2309.04662v1), [pdf](http://arxiv.org/pdf/2309.04662v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=3403145482648559011&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Sneha Kudugunta, Isaac Caswell, Biao Zhang, Xavier Garcia, Christopher A. Choquette-Choo, Katherine Lee, Derrick Xin, Aditya Kusupati, Romi Stella, Ankur Bapna*
- [**OBELICS**](https://huggingface.co/datasets/HuggingFaceM4/OBELICS) - HuggingFaceM4 🤗
- **Improving Multimodal Datasets with Image Captioning**, `arXiv, 2307.10350`, [arxiv](http://arxiv.org/abs/2307.10350v2), [pdf](http://arxiv.org/pdf/2307.10350v2.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=8121125897314064081&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Thao Nguyen, Samir Yitzhak Gadre, Gabriel Ilharco, Sewoong Oh, Ludwig Schmidt*
- **InternVid: A Large-scale Video-Text Dataset for Multimodal Understanding
  and Generation**, `arXiv, 2307.06942`, [arxiv](http://arxiv.org/abs/2307.06942v1), [pdf](http://arxiv.org/pdf/2307.06942v1.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=5470122915354183756&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yi Wang, Yinan He, Yizhuo Li, Kunchang Li, Jiashuo Yu, Xin Ma, Xinyuan Chen, Yaohui Wang, Ping Luo, Ziwei Liu*
- **Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and
  Language Models**, `arXiv, 2306.05424`, [arxiv](http://arxiv.org/abs/2306.05424v1), [pdf](http://arxiv.org/pdf/2306.05424v1.pdf), cication: [**30**](https://scholar.google.com/scholar?cites=13699030569069918768&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Muhammad Maaz, Hanoona Rasheed, Salman Khan, Fahad Shahbaz Khan*
- [Paper page - Youku-mPLUG: A 10 Million Large-scale Chinese Video-Language Dataset for Pre-training and Benchmarks](https://huggingface.co/papers/2306.04362)
- **M$^3$IT: A Large-Scale Dataset towards Multi-Modal Multilingual
  Instruction Tuning**, `arXiv, 2306.04387`, [arxiv](http://arxiv.org/abs/2306.04387v2), [pdf](http://arxiv.org/pdf/2306.04387v2.pdf), cication: [**13**](https://scholar.google.com/scholar?cites=1260710386346983464&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lei Li, Yuwei Yin, Shicheng Li, Liang Chen, Peiyi Wang, Shuhuai Ren, Mukai Li, Yazheng Yang, Jingjing Xu, Xu Sun*
### Reasoning & Action
- **Can Large Language Models Infer Causation from Correlation?**, `arXiv, 2306.05836`, [arxiv](http://arxiv.org/abs/2306.05836v1), [pdf](http://arxiv.org/pdf/2306.05836v1.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=10622702130608075727&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhijing Jin, Jiarui Liu, Zhiheng Lyu, Spencer Poff, Mrinmaya Sachan, Rada Mihalcea, Mona Diab, Bernhard Schölkopf*
- **Mind2Web: Towards a Generalist Agent for the Web**, `arXiv, 2306.06070`, [arxiv](http://arxiv.org/abs/2306.06070v2), [pdf](http://arxiv.org/pdf/2306.06070v2.pdf), cication: [**16**](https://scholar.google.com/scholar?cites=17415845647081249140&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xiang Deng, Yu Gu, Boyuan Zheng, Shijie Chen, Samuel Stevens, Boshi Wang, Huan Sun, Yu Su*

### Synthetic 
- **Ensemble-Instruct: Generating Instruction-Tuning Data with a
  Heterogeneous Mixture of LMs**, `arXiv, 2310.13961`, [arxiv](http://arxiv.org/abs/2310.13961v1), [pdf](http://arxiv.org/pdf/2310.13961v1.pdf), cication: [**-1**](None)

	 *Young-Suk Lee, Md Arafat Sultan, Yousef El-Kurdi, Tahira Naseem Asim Munawar, Radu Florian, Salim Roukos, Ramón Fernandez Astudillo*
- **Let's Synthesize Step by Step: Iterative Dataset Synthesis with Large
  Language Models by Extrapolating Errors from Small Models**, `arXiv, 2310.13671`, [arxiv](http://arxiv.org/abs/2310.13671v1), [pdf](http://arxiv.org/pdf/2310.13671v1.pdf), cication: [**-1**](None)

	 *Ruida Wang, Wangchunshu Zhou, Mrinmaya Sachan*
- **PIPPA: A Partially Synthetic Conversational Dataset**, `arXiv, 2308.05884`, [arxiv](http://arxiv.org/abs/2308.05884v1), [pdf](http://arxiv.org/pdf/2308.05884v1.pdf), cication: [**-1**](None)

	 *Tear Gosling, Alpin Dale, Yinhe Zheng*
- **Simple synthetic data reduces sycophancy in large language models**, `arXiv, 2308.03958`, [arxiv](http://arxiv.org/abs/2308.03958v1), [pdf](http://arxiv.org/pdf/2308.03958v1.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=15897243719772431083&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jerry Wei, Da Huang, Yifeng Lu, Denny Zhou, Quoc V. Le* · ([qbitai](https://www.qbitai.com/2023/08/75836.html))
- **DialogStudio: Towards Richest and Most Diverse Unified Dataset
  Collection for Conversational AI**, `arXiv, 2307.10172`, [arxiv](http://arxiv.org/abs/2307.10172v2), [pdf](http://arxiv.org/pdf/2307.10172v2.pdf), cication: [**-1**](None)

	 *Jianguo Zhang, Kun Qian, Zhiwei Liu, Shelby Heinecke, Rui Meng, Ye Liu, Zhou Yu, Huan Wang, Silvio Savarese, Caiming Xiong*
- **Large Language Model as Attributed Training Data Generator: A Tale of
  Diversity and Bias**, `arXiv, 2306.15895`, [arxiv](http://arxiv.org/abs/2306.15895v2), [pdf](http://arxiv.org/pdf/2306.15895v2.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=11839381200951011410&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yue Yu, Yuchen Zhuang, Jieyu Zhang, Yu Meng, Alexander Ratner, Ranjay Krishna, Jiaming Shen, Chao Zhang* · ([attrprompt](https://github.com/yueyu1030/attrprompt) - yueyu1030) ![Star](https://img.shields.io/github/stars/yueyu1030/attrprompt.svg?style=social&label=Star)
- **GPT Self-Supervision for a Better Data Annotator**, `arXiv, 2306.04349`, [arxiv](http://arxiv.org/abs/2306.04349v2), [pdf](http://arxiv.org/pdf/2306.04349v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=11223890126401627613&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xiaohuan Pei, Yanxi Li, Chang Xu* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652341615&idx=5&sn=5ac2958f3637b06663a8f314bc91ab47))
- **The Curse of Recursion: Training on Generated Data Makes Models Forget**, `arXiv, 2305.17493`, [arxiv](http://arxiv.org/abs/2305.17493v2), [pdf](http://arxiv.org/pdf/2305.17493v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=1584346861720994454&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ilia Shumailov, Zakhar Shumaylov, Yiren Zhao, Yarin Gal, Nicolas Papernot, Ross Anderson*

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652341615&idx=2&sn=31657c3e2252da120239487be278bfd7))
- **Increasing Diversity While Maintaining Accuracy: Text Data Generation
  with Large Language Models and Human Interventions**, `arXiv, 2306.04140`, [arxiv](http://arxiv.org/abs/2306.04140v1), [pdf](http://arxiv.org/pdf/2306.04140v1.pdf), cication: [**8**](https://scholar.google.com/scholar?cites=12703069969279861984&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *John Joon Young Chung, Ece Kamar, Saleema Amershi*
- **Harnessing large-language models to generate private synthetic text**, `arXiv, 2306.01684`, [arxiv](http://arxiv.org/abs/2306.01684v1), [pdf](http://arxiv.org/pdf/2306.01684v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=10930355231623511291&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Alexey Kurakin, Natalia Ponomareva, Umar Syed, Liam MacDermed, Andreas Terzis*
- **LIMA: Less Is More for Alignment**, `arXiv, 2305.11206`, [arxiv](http://arxiv.org/abs/2305.11206v1), [pdf](http://arxiv.org/pdf/2305.11206v1.pdf), cication: [**116**](https://scholar.google.com/scholar?cites=593239175873479851&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chunting Zhou, Pengfei Liu, Puxin Xu, Srini Iyer, Jiao Sun, Yuning Mao, Xuezhe Ma, Avia Efrat, Ping Yu, Lili Yu*
	 - [GitHub - h2oai/h2o-llmstudio: H2O LLM Studio - a framework and no-code GUI for fine-tuning LLMs](https://github.com/h2oai/h2o-llmstudio)
- **Maybe Only 0.5% Data is Needed: A Preliminary Exploration of Low
  Training Data Instruction Tuning**, `arXiv, 2305.09246`, [arxiv](http://arxiv.org/abs/2305.09246v1), [pdf](http://arxiv.org/pdf/2305.09246v1.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=6084596237044949489&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hao Chen, Yiming Zhang, Qi Zhang, Hantao Yang, Xiaomeng Hu, Xuetao Ma, Yifan Yanggong, Junbo Zhao*

## Toolkits
- [**dsir**](https://github.com/p-lambda/dsir) - p-lambda ![Star](https://img.shields.io/github/stars/p-lambda/dsir.svg?style=social&label=Star)

	 *DSIR large-scale data selection framework*
- [**data-juicer**](https://github.com/alibaba/data-juicer) - alibaba ![Star](https://img.shields.io/github/stars/alibaba/data-juicer.svg?style=social&label=Star)

	 *A one-stop data processing system to make data higher-quality, juicier, and more digestible for LLMs! 🍎 🍋 🌽 ➡️ ➡️🍸 🍹 🍷为大语言模型提供更高质量、更丰富、更易”消化“的数据！*

## Extra reference