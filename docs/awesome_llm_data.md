# Awesome llm data

- [Awesome llm data](#awesome-llm-data)
	- [Survey](#survey)
	- [Techs](#techs)
	- [Datasets](#datasets)
		- [Misc](#misc)
		- [MulitiMod](#mulitimod)
		- [Reasoning \& Action](#reasoning--action)
		- [Synthetic](#synthetic)
	- [Toolkits](#toolkits)
	- [Other](#other)
	- [Extra reference](#extra-reference)


## Survey
- **On Protecting the Data Privacy of Large Language Models (LLMs): A Survey**, `arXiv, 2403.05156`, [arxiv](http://arxiv.org/abs/2403.05156v1), [pdf](http://arxiv.org/pdf/2403.05156v1.pdf), cication: [**-1**](None)

	 *Biwei Yan, Kun Li, Minghui Xu, Yueyan Dong, Yue Zhang, Zhaochun Ren, Xiuzheng Cheng*
- [**fm-cheatsheet**](https://github.com/allenai/fm-cheatsheet/tree/main) - allenai ![Star](https://img.shields.io/github/stars/allenai/fm-cheatsheet.svg?style=social&label=Star)

	 *Website for hosting the Open Foundation Models Cheat Sheet.* · ([fm-cheatsheet](https://github.com/allenai/fm-cheatsheet/blob/main/app/resources/paper.pdf) - allenai) ![Star](https://img.shields.io/github/stars/allenai/fm-cheatsheet.svg?style=social&label=Star)
- **Datasets for Large Language Models: A Comprehensive Survey**, `arXiv, 2402.18041`, [arxiv](http://arxiv.org/abs/2402.18041v1), [pdf](http://arxiv.org/pdf/2402.18041v1.pdf), cication: [**-1**](None)

	 *Yang Liu, Jiahuan Cao, Chongyu Liu, Kai Ding, Lianwen Jin*

	 · ([Awesome-LLMs-Datasets](https://github.com/lmmlzn/Awesome-LLMs-Datasets) - lmmlzn) ![Star](https://img.shields.io/github/stars/lmmlzn/Awesome-LLMs-Datasets.svg?style=social&label=Star)
- **A Survey on Data Selection for Language Models**, `arXiv, 2402.16827`, [arxiv](http://arxiv.org/abs/2402.16827v1), [pdf](http://arxiv.org/pdf/2402.16827v1.pdf), cication: [**-1**](None)

	 *Alon Albalak, Yanai Elazar, Sang Michael Xie, Shayne Longpre, Nathan Lambert, Xinyi Wang, Niklas Muennighoff, Bairu Hou, Liangming Pan, Haewon Jeong*
- **Data Management For Large Language Models: A Survey**, `arXiv, 2312.01700`, [arxiv](http://arxiv.org/abs/2312.01700v1), [pdf](http://arxiv.org/pdf/2312.01700v1.pdf), cication: [**-1**](None)

	 *Zige Wang, Wanjun Zhong, Yufei Wang, Qi Zhu, Fei Mi, Baojun Wang, Lifeng Shang, Xin Jiang, Qun Liu*

## Techs
- **Fewer Truncations Improve Language Modeling**, `arXiv, 2404.10830`, [arxiv](http://arxiv.org/abs/2404.10830v1), [pdf](http://arxiv.org/pdf/2404.10830v1.pdf), cication: [**-1**](None)

	 *Hantian Ding, Zijian Wang, Giovanni Paolini, Varun Kumar, Anoop Deoras, Dan Roth, Stefano Soatto*
- **Best Practices and Lessons Learned on Synthetic Data for Language Models**, `arXiv, 2404.07503`, [arxiv](http://arxiv.org/abs/2404.07503v1), [pdf](http://arxiv.org/pdf/2404.07503v1.pdf), cication: [**-1**](None)

	 *Ruibo Liu, Jerry Wei, Fangyu Liu, Chenglei Si, Yanzhe Zhang, Jinmeng Rao, Steven Zheng, Daiyi Peng, Diyi Yang, Denny Zhou*
- **Scaling Laws for Data Filtering -- Data Curation cannot be Compute
  Agnostic**, `arXiv, 2404.07177`, [arxiv](http://arxiv.org/abs/2404.07177v1), [pdf](http://arxiv.org/pdf/2404.07177v1.pdf), cication: [**-1**](None)

	 *Sachin Goyal, Pratyush Maini, Zachary C. Lipton, Aditi Raghunathan, J. Zico Kolter* · ([scaling_laws_data_filtering](https://github.com/locuslab/scaling_laws_data_filtering) - locuslab) ![Star](https://img.shields.io/github/stars/locuslab/scaling_laws_data_filtering.svg?style=social&label=Star)
- **Training LLMs over Neurally Compressed Text**, `arXiv, 2404.03626`, [arxiv](http://arxiv.org/abs/2404.03626v1), [pdf](http://arxiv.org/pdf/2404.03626v1.pdf), cication: [**-1**](None)

	 *Brian Lester, Jaehoon Lee, Alex Alemi, Jeffrey Pennington, Adam Roberts, Jascha Sohl-Dickstein, Noah Constant*
	- `explores training LLMs with neural text compressors; the proposed compression technique segments text into blocks that each compress to the same bit length; the approach improves at scale and outperforms byte-level baselines on both perplexity and inference speed benchmarks; latency is reduced to the shorter sequence length.`
- **LESS: Selecting Influential Data for Targeted Instruction Tuning**, `arXiv, 2402.04333`, [arxiv](http://arxiv.org/abs/2402.04333v2), [pdf](http://arxiv.org/pdf/2402.04333v2.pdf), cication: [**-1**](None)

	 *Mengzhou Xia, Sadhika Malladi, Suchin Gururangan, Sanjeev Arora, Danqi Chen* · ([cs.princeton](https://www.cs.princeton.edu/~smalladi/blog/2024/04/04/dataselection/))
- **Can LLMs Separate Instructions From Data? And What Do We Even Mean By
  That?**, `arXiv, 2403.06833`, [arxiv](http://arxiv.org/abs/2403.06833v1), [pdf](http://arxiv.org/pdf/2403.06833v1.pdf), cication: [**-1**](None)

	 *Egor Zverev, Sahar Abdelnabi, Mario Fritz, Christoph H. Lampert* · ([Should-It-Be-Executed-Or-Processed](https://github.com/egozverev/Should-It-Be-Executed-Or-Processed) - egozverev) ![Star](https://img.shields.io/github/stars/egozverev/Should-It-Be-Executed-Or-Processed.svg?style=social&label=Star)
- **Data Mixing Laws: Optimizing Data Mixtures by Predicting Language
  Modeling Performance**, `arXiv, 2403.16952`, [arxiv](http://arxiv.org/abs/2403.16952v1), [pdf](http://arxiv.org/pdf/2403.16952v1.pdf), cication: [**-1**](None)

	 *Jiasheng Ye, Peiju Liu, Tianxiang Sun, Yunhua Zhou, Jun Zhan, Xipeng Qiu* · ([mixinglaws](https://github.com/yegcjs/mixinglaws) - yegcjs) ![Star](https://img.shields.io/github/stars/yegcjs/mixinglaws.svg?style=social&label=Star)
- **LLM2LLM: Boosting LLMs with Novel Iterative Data Enhancement**, `arXiv, 2403.15042`, [arxiv](http://arxiv.org/abs/2403.15042v1), [pdf](http://arxiv.org/pdf/2403.15042v1.pdf), cication: [**-1**](None)

	 *Nicholas Lee, Thanakul Wattanawong, Sehoon Kim, Karttikeya Mangalam, Sheng Shen, Gopala Anumanchipali, Michael W. Mahoney, Kurt Keutzer, Amir Gholami*
	- `improves the performance of large language models in low-data scenarios by using a teacher model to generate synthetic data from errors made by a student model during initial training`
- **Are Human Conversations Special? A Large Language Model Perspective**, `arXiv, 2403.05045`, [arxiv](http://arxiv.org/abs/2403.05045v1), [pdf](http://arxiv.org/pdf/2403.05045v1.pdf), cication: [**-1**](None)

	 *Toshish Jawale, Chaitanya Animesh, Sekhar Vallath, Kartik Talamadupula, Larry Heck*
- **Learning to Generate Instruction Tuning Datasets for Zero-Shot Task
  Adaptation**, `arXiv, 2402.18334`, [arxiv](http://arxiv.org/abs/2402.18334v1), [pdf](http://arxiv.org/pdf/2402.18334v1.pdf), cication: [**-1**](None)

	 *Nihal V. Nayak, Yiyang Nan, Avi Trost, Stephen H. Bach* · ([bonito](https://github.com/batsresearch/bonito) - batsresearch) ![Star](https://img.shields.io/github/stars/batsresearch/bonito.svg?style=social&label=Star)
- **How to Train Data-Efficient LLMs**, `arXiv, 2402.09668`, [arxiv](http://arxiv.org/abs/2402.09668v1), [pdf](http://arxiv.org/pdf/2402.09668v1.pdf), cication: [**-1**](None)

	 *Noveen Sachdeva, Benjamin Coleman, Wang-Cheng Kang, Jianmo Ni, Lichan Hong, Ed H. Chi, James Caverlee, Julian McAuley, Derek Zhiyuan Cheng*
- [An Initial Exploration of Theoretical Support for Language Model Data Engineering. Part 1: Pretraining ](https://yaofu.notion.site/An-Initial-Exploration-of-Theoretical-Support-for-Language-Model-Data-Engineering-Part-1-Pretraini-dc480d9bf7ff4659afd8c9fb738086eb)
- **Rephrasing the Web: A Recipe for Compute and Data-Efficient Language
  Modeling**, `arXiv, 2401.16380`, [arxiv](http://arxiv.org/abs/2401.16380v1), [pdf](http://arxiv.org/pdf/2401.16380v1.pdf), cication: [**-1**](None)

	 *Pratyush Maini, Skyler Seto, He Bai, David Grangier, Yizhe Zhang, Navdeep Jaitly*
- **Genie: Achieving Human Parity in Content-Grounded Datasets Generation**, `arXiv, 2401.14367`, [arxiv](http://arxiv.org/abs/2401.14367v1), [pdf](http://arxiv.org/pdf/2401.14367v1.pdf), cication: [**-1**](None)

	 *Asaf Yehudai, Boaz Carmeli, Yosi Mass, Ofir Arviv, Nathaniel Mills, Assaf Toledo, Eyal Shnarch, Leshem Choshen*
- **Unitxt: Flexible, Shareable and Reusable Data Preparation and Evaluation
  for Generative AI**, `arXiv, 2401.14019`, [arxiv](http://arxiv.org/abs/2401.14019v1), [pdf](http://arxiv.org/pdf/2401.14019v1.pdf), cication: [**-1**](None)

	 *Elron Bandel, Yotam Perlitz, Elad Venezian, Roni Friedman-Melamed, Ofir Arviv, Matan Orbach, Shachar Don-Yehyia, Dafna Sheinwald, Ariel Gera, Leshem Choshen* · ([unitxt](https://github.com/IBM/unitxt) - IBM) ![Star](https://img.shields.io/github/stars/IBM/unitxt.svg?style=social&label=Star)
- **The Unreasonable Effectiveness of Easy Training Data for Hard Tasks**, `arXiv, 2401.06751`, [arxiv](http://arxiv.org/abs/2401.06751v1), [pdf](http://arxiv.org/pdf/2401.06751v1.pdf), cication: [**-1**](None)

	 *Peter Hase, Mohit Bansal, Peter Clark, Sarah Wiegreffe* · ([easy-to-hard-generalization](https://github.com/allenai/easy-to-hard-generalization) - allenai) ![Star](https://img.shields.io/github/stars/allenai/easy-to-hard-generalization.svg?style=social&label=Star)
- **A Shocking Amount of the Web is Machine Translated: Insights from
  Multi-Way Parallelism**, `arXiv, 2401.05749`, [arxiv](http://arxiv.org/abs/2401.05749v1), [pdf](http://arxiv.org/pdf/2401.05749v1.pdf), cication: [**-1**](None)

	 *Brian Thompson, Mehak Preet Dhaliwal, Peter Frisch, Tobias Domhan, Marcello Federico*
- **What Makes Good Data for Alignment? A Comprehensive Study of Automatic
  Data Selection in Instruction Tuning**, `arXiv, 2312.15685`, [arxiv](http://arxiv.org/abs/2312.15685v1), [pdf](http://arxiv.org/pdf/2312.15685v1.pdf), cication: [**-1**](None)

	 *Wei Liu, Weihao Zeng, Keqing He, Yong Jiang, Junxian He* · ([deita](https://github.com/hkust-nlp/deita) - hkust-nlp) ![Star](https://img.shields.io/github/stars/hkust-nlp/deita.svg?style=social&label=Star)
- **Order Matters in the Presence of Dataset Imbalance for Multilingual
  Learning**, `arXiv, 2312.06134`, [arxiv](http://arxiv.org/abs/2312.06134v1), [pdf](http://arxiv.org/pdf/2312.06134v1.pdf), cication: [**-1**](None)

	 *Dami Choi, Derrick Xin, Hamid Dadkhahi, Justin Gilmer, Ankush Garg, Orhan Firat, Chih-Kuan Yeh, Andrew M. Dai, Behrooz Ghorbani*
- **When Less is More: Investigating Data Pruning for Pretraining LLMs at
  Scale**, `arXiv, 2309.04564`, [arxiv](http://arxiv.org/abs/2309.04564v1), [pdf](http://arxiv.org/pdf/2309.04564v1.pdf), cication: [**23**](https://scholar.google.com/scholar?cites=1052346843253959809&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Max Marion, Ahmet Üstün, Luiza Pozzobon, Alex Wang, Marzieh Fadaee, Sara Hooker*
- **AlpaGasus: Training A Better Alpaca with Fewer Data**, `arXiv, 2307.08701`, [arxiv](http://arxiv.org/abs/2307.08701v4), [pdf](http://arxiv.org/pdf/2307.08701v4.pdf), cication: [**-1**](None)

	 *Lichang Chen, Shiyang Li, Jun Yan, Hai Wang, Kalpa Gunaratna, Vikas Yadav, Zheng Tang, Vijay Srinivasan, Tianyi Zhou, Heng Huang*
- **DoReMi: Optimizing Data Mixtures Speeds Up Language Model Pretraining**, `NeurIPS, 2024`, [arxiv](http://arxiv.org/abs/2305.10429v4), [pdf](http://arxiv.org/pdf/2305.10429v4.pdf), cication: [**34**](https://scholar.google.com/scholar?cites=8540537205197053386&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Sang Michael Xie, Hieu Pham, Xuanyi Dong, Nan Du, Hanxiao Liu, Yifeng Lu, Percy Liang, Quoc V. Le, Tengyu Ma, Adams Wei Yu*
- **Scaling Data-Constrained Language Models**, `arXiv, 2305.16264`, [arxiv](http://arxiv.org/abs/2305.16264v4), [pdf](http://arxiv.org/pdf/2305.16264v4.pdf), cication: [**-1**](None)

	 *Niklas Muennighoff, Alexander M. Rush, Boaz Barak, Teven Le Scao, Aleksandra Piktus, Nouamane Tazi, Sampo Pyysalo, Thomas Wolf, Colin Raffel*

	 · ([datablations](https://github.com/huggingface/datablations) - huggingface) ![Star](https://img.shields.io/github/stars/huggingface/datablations.svg?style=social&label=Star)

## Datasets
- [**idl-wds**](https://huggingface.co/datasets/pixparse/idl-wds) - pixparse 🤗
- [**synthetic_text_to_sql**](https://huggingface.co/datasets/gretelai/synthetic_text_to_sql) - gretelai 🤗
- [**Caselaw_Access_Project**](https://huggingface.co/datasets/TeraflopAI/Caselaw_Access_Project) - TeraflopAI 🤗

	 · ([twitter](https://twitter.com/EnricoShippole/status/1766157358672359862?s=20))
- [Common Corpus - a PleIAs Collection](https://huggingface.co/collections/PleIAs/common-corpus-65d46e3ea3980fdcd66a5613)

	 · ([huggingface](https://huggingface.co/blog/Pclanglais/common-corpus))
- [**internet_archive_books_en**](https://huggingface.co/datasets/storytracer/internet_archive_books_en) - storytracer 🤗
- [**orca-math-word-problems-200k**](https://huggingface.co/datasets/microsoft/orca-math-word-problems-200k) - microsoft 🤗
- [**OpenHermesPreferences**](https://huggingface.co/datasets/argilla/OpenHermesPreferences) - argilla 🤗
- [**WebSight**](https://huggingface.co/datasets/HuggingFaceM4/WebSight) - HuggingFaceM4 🤗

	 · ([huggingface](https://huggingface.co/blog/websight))
- [**oasst2**](https://huggingface.co/datasets/OpenAssistant/oasst2) - OpenAssistant 🤗
- [**wikisource**](https://huggingface.co/datasets/wikimedia/wikisource) - wikimedia 🤗
- [**pii-masking-200k**](https://huggingface.co/datasets/ai4privacy/pii-masking-200k) - ai4privacy 🤗
- [**SlimPajama-627B**](https://huggingface.co/datasets/cerebras/SlimPajama-627B) - cerebras  🤗

	 · ([modelzoo](https://github.com/Cerebras/modelzoo/tree/main/modelzoo/transformers/data_processing/slimpajama) - Cerebras) ![Star](https://img.shields.io/github/stars/Cerebras/modelzoo.svg?style=social&label=Star)
- [**MADLAD-400**](https://huggingface.co/datasets/allenai/MADLAD-400) - allenai 🤗
- [**peS2o**](https://huggingface.co/datasets/allenai/peS2o) - allenai 🤗

### Misc
- **COIG-CQIA: Quality is All You Need for Chinese Instruction Fine-tuning**, `arXiv, 2403.18058`, [arxiv](http://arxiv.org/abs/2403.18058v1), [pdf](http://arxiv.org/pdf/2403.18058v1.pdf), cication: [**-1**](None)

	 *Yuelin Bai, Xinrun Du, Yiming Liang, Yonggang Jin, Ziqiang Liu, Junting Zhou, Tianyu Zheng, Xincheng Zhang, Nuo Ma, Zekun Wang* · ([huggingface](https://huggingface.co/datasets/m-a-p/COIG-CQIA)) · ([COIG-CQIA](https://github.com/paralym/COIG-CQIA) - paralym) ![Star](https://img.shields.io/github/stars/paralym/COIG-CQIA.svg?style=social&label=Star)

	 · ([qbitai](https://www.qbitai.com/2024/04/133116.html))
- [**10k_prompts_ranked**](https://huggingface.co/datasets/DIBT/10k_prompts_ranked) - DIBT 🤗
- **Aya Dataset: An Open-Access Collection for Multilingual Instruction
  Tuning**, `arXiv, 2402.06619`, [arxiv](http://arxiv.org/abs/2402.06619v1), [pdf](http://arxiv.org/pdf/2402.06619v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=8445225482174528918&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shivalika Singh, Freddie Vargus, Daniel Dsouza, Börje F. Karlsson, Abinaya Mahendiran, Wei-Yin Ko, Herumb Shandilya, Jay Patel, Deividas Mataciunas, Laura OMahony*

	 · ([youtube](https://www.youtube.com/watch?v=APwtG6iWPiA&t=3s&ab_channel=Cohere))
- **Dolma: an Open Corpus of Three Trillion Tokens for Language Model
  Pretraining Research**, `arXiv, 2402.00159`, [arxiv](http://arxiv.org/abs/2402.00159v1), [pdf](http://arxiv.org/pdf/2402.00159v1.pdf), cication: [**-1**](None)

	 *Luca Soldaini, Rodney Kinney, Akshita Bhagia, Dustin Schwenk, David Atkinson, Russell Authur, Ben Bogin, Khyathi Chandu, Jennifer Dumas, Yanai Elazar*
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
- [**Let-It-Wag**](https://huggingface.co/datasets/bethgelab/Let-It-Wag) - bethgelab 🤗
- **MAGID: An Automated Pipeline for Generating Synthetic Multi-modal
  Datasets**, `arXiv, 2403.03194`, [arxiv](http://arxiv.org/abs/2403.03194v1), [pdf](http://arxiv.org/pdf/2403.03194v1.pdf), cication: [**-1**](None)

	 *Hossein Aboutalebi, Hwanjun Song, Yusheng Xie, Arshit Gupta, Justin Sun, Hang Su, Igor Shalyminov, Nikolaos Pappas, Siffi Singh, Saab Mansour*
- **Multimodal ArXiv: A Dataset for Improving Scientific Comprehension of
  Large Vision-Language Models**, `arXiv, 2403.00231`, [arxiv](http://arxiv.org/abs/2403.00231v2), [pdf](http://arxiv.org/pdf/2403.00231v2.pdf), cication: [**-1**](None)

	 *Lei Li, Yuqi Wang, Runxin Xu, Peiyi Wang, Xiachong Feng, Lingpeng Kong, Qi Liu*
- **Panda-70M: Captioning 70M Videos with Multiple Cross-Modality Teachers**, `arXiv, 2402.19479`, [arxiv](http://arxiv.org/abs/2402.19479v1), [pdf](http://arxiv.org/pdf/2402.19479v1.pdf), cication: [**-1**](None)

	 *Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Ekaterina Deyneka, Hsiang-wei Chao, Byung Eun Jeon, Yuwei Fang, Hsin-Ying Lee, Jian Ren, Ming-Hsuan Yang*
- **A Touch, Vision, and Language Dataset for Multimodal Alignment**, `arXiv, 2402.13232`, [arxiv](http://arxiv.org/abs/2402.13232v1), [pdf](http://arxiv.org/pdf/2402.13232v1.pdf), cication: [**-1**](None)

	 *Letian Fu, Gaurav Datta, Huang Huang, William Chung-Ho Panitch, Jaimyn Drake, Joseph Ortiz, Mustafa Mukadam, Mike Lambeta, Roberto Calandra, Ken Goldberg*
- **Let's Go Shopping (LGS) -- Web-Scale Image-Text Dataset for Visual
  Concept Understanding**, `arXiv, 2401.04575`, [arxiv](http://arxiv.org/abs/2401.04575v1), [pdf](http://arxiv.org/pdf/2401.04575v1.pdf), cication: [**-1**](None)

	 *Yatong Bai, Utsav Garg, Apaar Shanker, Haoming Zhang, Samyak Parajuli, Erhan Bas, Isidora Filipovic, Amelia N. Chu, Eugenia D Fomitcheva, Elliot Branson*
- **Video Recognition in Portrait Mode**, `arXiv, 2312.13746`, [arxiv](http://arxiv.org/abs/2312.13746v1), [pdf](http://arxiv.org/pdf/2312.13746v1.pdf), cication: [**-1**](None)

	 *Mingfei Han, Linjie Yang, Xiaojie Jin, Jiashi Feng, Xiaojun Chang, Heng Wang* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-04-03))
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
- [**json-mode-eval?utm_source=ainews&utm_medium=email&utm_campaign=ainews-mm1-apples-first-large-multimodal-model**](https://huggingface.co/datasets/NousResearch/json-mode-eval?utm_source=ainews&utm_medium=email&utm_campaign=ainews-mm1-apples-first-large-multimodal-model) - NousResearch 🤗
- **Can Large Language Models Infer Causation from Correlation?**, `arXiv, 2306.05836`, [arxiv](http://arxiv.org/abs/2306.05836v1), [pdf](http://arxiv.org/pdf/2306.05836v1.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=10622702130608075727&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhijing Jin, Jiarui Liu, Zhiheng Lyu, Spencer Poff, Mrinmaya Sachan, Rada Mihalcea, Mona Diab, Bernhard Schölkopf*
- **Mind2Web: Towards a Generalist Agent for the Web**, `arXiv, 2306.06070`, [arxiv](http://arxiv.org/abs/2306.06070v2), [pdf](http://arxiv.org/pdf/2306.06070v2.pdf), cication: [**16**](https://scholar.google.com/scholar?cites=17415845647081249140&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xiang Deng, Yu Gu, Boyuan Zheng, Shijie Chen, Samuel Stevens, Boshi Wang, Huan Sun, Yu Su*

### Synthetic 
- [**Genstruct-7B**](https://huggingface.co/NousResearch/Genstruct-7B) - NousResearch 🤗
- [Cosmopedia: how to create large-scale synthetic data for pre-training Large Language Models](https://huggingface.co/blog/cosmopedia)

	 · ([cosmopedia](https://github.com/huggingface/cosmopedia) - huggingface) ![Star](https://img.shields.io/github/stars/huggingface/cosmopedia.svg?style=social&label=Star)
- **Gen4Gen: Generative Data Pipeline for Generative Multi-Concept
  Composition**, `arXiv, 2402.15504`, [arxiv](http://arxiv.org/abs/2402.15504v1), [pdf](http://arxiv.org/pdf/2402.15504v1.pdf), cication: [**-1**](None)

	 *Chun-Hsiao Yeh, Ta-Ying Cheng, He-Yen Hsieh, Chuan-En Lin, Yi Ma, Andrew Markham, Niki Trigoni, H. T. Kung, Yubei Chen*
- **LexC-Gen: Generating Data for Extremely Low-Resource Languages with
  Large Language Models and Bilingual Lexicons**, `arXiv, 2402.14086`, [arxiv](http://arxiv.org/abs/2402.14086v1), [pdf](http://arxiv.org/pdf/2402.14086v1.pdf), cication: [**-1**](None)

	 *Zheng-Xin Yong, Cristina Menghini, Stephen H. Bach*
- **Synthetic Data (Almost) from Scratch: Generalized Instruction Tuning for
  Language Models**, `arXiv, 2402.13064`, [arxiv](http://arxiv.org/abs/2402.13064v1), [pdf](http://arxiv.org/pdf/2402.13064v1.pdf), cication: [**-1**](None)

	 *Haoran Li, Qingxiu Dong, Zhengyang Tang, Chaojun Wang, Xingxing Zhang, Haoyang Huang, Shaohan Huang, Xiaolong Huang, Zeqiang Huang, Dongdong Zhang*
- **ALLaVA: Harnessing GPT4V-synthesized Data for A Lite Vision-Language
  Model**, `arXiv, 2402.11684`, [arxiv](http://arxiv.org/abs/2402.11684v1), [pdf](http://arxiv.org/pdf/2402.11684v1.pdf), cication: [**-1**](None)

	 *Guiming Hardy Chen, Shunian Chen, Ruifei Zhang, Junying Chen, Xiangbo Wu, Zhiyi Zhang, Zhihong Chen, Jianquan Li, Xiang Wan, Benyou Wang*
- **DataDreamer: A Tool for Synthetic Data Generation and Reproducible LLM
  Workflows**, `arXiv, 2402.10379`, [arxiv](http://arxiv.org/abs/2402.10379v1), [pdf](http://arxiv.org/pdf/2402.10379v1.pdf), cication: [**-1**](None)

	 *Ajay Patel, Colin Raffel, Chris Callison-Burch* · ([DataDreamer](https://github.com/datadreamer-dev/DataDreamer) - datadreamer-dev) ![Star](https://img.shields.io/github/stars/datadreamer-dev/DataDreamer.svg?style=social&label=Star)
- **Synthetic Dialogue Dataset Generation using LLM Agents**, `arXiv, 2401.17461`, [arxiv](http://arxiv.org/abs/2401.17461v1), [pdf](http://arxiv.org/pdf/2401.17461v1.pdf), cication: [**-1**](None)

	 *Yelaman Abdullin, Diego Molla-Aliod, Bahadorreza Ofoghi, John Yearwood, Qingyang Li*
- **Learning Vision from Models Rivals Learning Vision from Data**, `arXiv, 2312.17742`, [arxiv](http://arxiv.org/abs/2312.17742v1), [pdf](http://arxiv.org/pdf/2312.17742v1.pdf), cication: [**-1**](None)

	 *Yonglong Tian, Lijie Fan, Kaifeng Chen, Dina Katabi, Dilip Krishnan, Phillip Isola* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652431566&idx=5&sn=33d2c2147035223637638b53702ac043&poc_token=HKf6pGWj0ZkyQ3Zn3HWLerDAiWuD-mQ4RKN_fIRb))
- **Ensemble-Instruct: Generating Instruction-Tuning Data with a
  Heterogeneous Mixture of LMs**, `arXiv, 2310.13961`, [arxiv](http://arxiv.org/abs/2310.13961v1), [pdf](http://arxiv.org/pdf/2310.13961v1.pdf), cication: [**-1**](None)

	 *Young-Suk Lee, Md Arafat Sultan, Yousef El-Kurdi, Tahira Naseem Asim Munawar, Radu Florian, Salim Roukos, Ramón Fernandez Astudillo*
- **Let's Synthesize Step by Step: Iterative Dataset Synthesis with Large
  Language Models by Extrapolating Errors from Small Models**, `arXiv, 2310.13671`, [arxiv](http://arxiv.org/abs/2310.13671v1), [pdf](http://arxiv.org/pdf/2310.13671v1.pdf), cication: [**-1**](None)

	 *Ruida Wang, Wangchunshu Zhou, Mrinmaya Sachan*
- **Ada-Instruct: Adapting Instruction Generators for Complex Reasoning**, `arXiv, 2310.04484`, [arxiv](http://arxiv.org/abs/2310.04484v2), [pdf](http://arxiv.org/pdf/2310.04484v2.pdf), cication: [**-1**](None)

	 *Wanyun Cui, Qianle Wang*
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
- [**databonsai**](https://github.com/databonsai/databonsai) - databonsai ![Star](https://img.shields.io/github/stars/databonsai/databonsai.svg?style=social&label=Star)

	 *clean & curate your data with LLMs.*
- [**distilabel**](https://github.com/argilla-io/distilabel) - argilla-io ![Star](https://img.shields.io/github/stars/argilla-io/distilabel.svg?style=social&label=Star)

	 *⚗️ distilabel is a framework for synthetic data and AI feedback for AI engineers that require high-quality outputs, full data ownership, and overall efficiency.*
- **Cleaner Pretraining Corpus Curation with Neural Web Scraping**, `arXiv, 2402.14652`, [arxiv](http://arxiv.org/abs/2402.14652v1), [pdf](http://arxiv.org/pdf/2402.14652v1.pdf), cication: [**-1**](None)

	 *Zhipeng Xu, Zhenghao Liu, Yukun Yan, Zhiyuan Liu, Chenyan Xiong, Ge Yu* · ([NeuScraper](https://github.com/OpenMatch/NeuScraper) - OpenMatch) ![Star](https://img.shields.io/github/stars/OpenMatch/NeuScraper.svg?style=social&label=Star)
- [**dsir**](https://github.com/p-lambda/dsir) - p-lambda ![Star](https://img.shields.io/github/stars/p-lambda/dsir.svg?style=social&label=Star)

	 *DSIR large-scale data selection framework*
- [**data-juicer**](https://github.com/alibaba/data-juicer) - alibaba ![Star](https://img.shields.io/github/stars/alibaba/data-juicer.svg?style=social&label=Star)

	 *A one-stop data processing system to make data higher-quality, juicier, and more digestible for LLMs! 🍎 🍋 🌽 ➡️ ➡️🍸 🍹 🍷为大语言模型提供更高质量、更丰富、更易”消化“的数据！*

## Other
- [Nomic Atlas](https://atlas.nomic.ai/map/f2fba2aa-3647-4f49-a0f3-9347daeee499/ee4a84bd-f125-4bcc-a683-1b4e231cb10f)
- [**community-datasets**](https://huggingface.co/blog/community-datasets) -  🤗
- [Synthetic data: save money, time and carbon with open source](https://huggingface.co/blog/synthetic-data-save-costs)
- [Thinking about High-Quality Human Data | Lil'Log](https://lilianweng.github.io/posts/2024-02-05-human-data-quality/)

- [30 个优质 NLP 数据集和模型，一键使用 8 个 demo](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247561069&idx=3&sn=46849d9ae13a9a51421f839d03151281)

## Extra reference
- [**Awesome-LLMs-Datasets**](https://github.com/lmmlzn/Awesome-LLMs-Datasets) - lmmlzn ![Star](https://img.shields.io/github/stars/lmmlzn/Awesome-LLMs-Datasets.svg?style=social&label=Star)

	 *Summarize existing representative LLMs text datasets.*
- [**awesome-instruction-datasets**](https://github.com/jianzhnie/awesome-instruction-datasets) - jianzhnie ![Star](https://img.shields.io/github/stars/jianzhnie/awesome-instruction-datasets.svg?style=social&label=Star)

	 *A collection of awesome-prompt-datasets, awesome-instruction-dataset, to train ChatLLM such as chatgpt 收录各种各样的指令数据集, 用于训练 ChatLLM 模型。*