# Vision-Language Models

- [Vision-Language Models](#vision-language-models) 
	- [Survey](#survey)
	- [Vision-Language Models](#vision-language-models-1)
	- [Image](#image)
	- [Video](#video)
	- [Encoder](#encoder)
	- [Alignment](#alignment)
	- [Reasoning](#reasoning)
	- [Evaluation](#evaluation)
	- [Efficient](#efficient)
	- [Generation](#generation)
	- [Dataset](#dataset)
	- [Projects](#projects)
	- [Products](#products)
	- [Misc](#misc)


## Survey

- **Next Token Prediction Towards Multimodal Intelligence: A Comprehensive 
  Survey**, `arXiv, 2412.18619`, [arxiv](http://arxiv.org/abs/2412.18619v2), [pdf](http://arxiv.org/pdf/2412.18619v2.pdf), cication: [**-1**](None) 

	 *Liang Chen, Zekun Wang, Shuhuai Ren, ..., Tianyu Liu, Baobao Chang* · ([Awesome-Multimodal-Next-Token-Prediction](https://github.com/LMM101/Awesome-Multimodal-Next-Token-Prediction) - LMM101) ![Star](https://img.shields.io/github/stars/LMM101/Awesome-Multimodal-Next-Token-Prediction.svg?style=social&label=Star)
- **A Survey of Mathematical Reasoning in the Era of Multimodal Large 
  Language Model: Benchmark, Method & Challenges**, `arXiv, 2412.11936`, [arxiv](http://arxiv.org/abs/2412.11936v1), [pdf](http://arxiv.org/pdf/2412.11936v1.pdf), cication: [**-1**](None) 

	 *Yibo Yan, Jiamin Su, Jianxiang He, ..., Qingsong Wen, Xuming Hu*
- **Personalized Multimodal Large Language Models: A Survey**, `arXiv, 2412.02142`, [arxiv](http://arxiv.org/abs/2412.02142v1), [pdf](http://arxiv.org/pdf/2412.02142v1.pdf), cication: [**-1**](None) 

	 *Junda Wu, Hanjia Lyu, Yu Xia, ..., Jiebo Luo, Julian McAuley*
- **Explainable and Interpretable Multimodal Large Language Models: A 
  Comprehensive Survey**, `arXiv, 2412.02104`, [arxiv](http://arxiv.org/abs/2412.02104v1), [pdf](http://arxiv.org/pdf/2412.02104v1.pdf), cication: [**-1**](None) 

	 *Yunkai Dang, Kaichen Huang, Jiahao Huo, ..., Hui Xiong, Xuming Hu*
- **Personalized Multimodal Large Language Models: A Survey**, `arXiv, 2412.02142`, [arxiv](http://arxiv.org/abs/2412.02142v1), [pdf](http://arxiv.org/pdf/2412.02142v1.pdf), cication: [**-1**](None) 

	 *Junda Wu, Hanjia Lyu, Yu Xia, ..., Jiebo Luo, Julian McAuley*
- [Papers I've read this week: vision language models](https://www.artfintel.com/p/papers-ive-read-this-week-vision) 

	 · ([𝕏](https://x.com/finbarrtimbers/status/1861443335841575282))
- [short survey of trends in VLMs since Llava 1.0 came out](https://x.com/mervenoyann/status/1851708916729798799)  𝕏 

	 · ([huggingface](https://huggingface.co/collections/merve/mit-talk-31-10-papers-671f6a16e156f77739820c89)) · ([youtube](https://www.youtube.com/watch?v=_TlhKHTgWjY))
- **Towards Unifying Understanding and Generation in the Era of Vision 
  Foundation Models: A Survey from the Autoregression Perspective**, `arXiv, 2410.22217`, [arxiv](http://arxiv.org/abs/2410.22217v2), [pdf](http://arxiv.org/pdf/2410.22217v2.pdf), cication: [**-1**](None)

	 *Shenghao Xie, Wenqiang Zu, Mingyang Zhao, ..., Shanghang Zhang, Lei Ma*
- **A Survey of Hallucination in Large Visual Language Models**, `arXiv, 2410.15359`, [arxiv](http://arxiv.org/abs/2410.15359v1), [pdf](http://arxiv.org/pdf/2410.15359v1.pdf), cication: [**-1**](None) 

	 *Wei Lan, Wenyi Chen, Qingfeng Chen, ..., Huiyu Zhou, Yi Pan*

## Vision-Language Models

- **Migician: Revealing the Magic of Free-Form Multi-Image Grounding in 
  Multimodal Large Language Models**, `arXiv, 2501.05767`, [arxiv](http://arxiv.org/abs/2501.05767v2), [pdf](http://arxiv.org/pdf/2501.05767v2.pdf), cication: [**-1**](None) 

	 *You Li, Heyu Huang, Chi Chen, ..., Ruixuan Li, Maosong Sun* · ([migician-vg.github](https://migician-vg.github.io)) · ([arxiv](https://arxiv.org/abs/2501.05767)) · ([Migician](https://github.com/thunlp/Migician) - thunlp) ![Star](https://img.shields.io/github/stars/thunlp/Migician.svg?style=social&label=Star)
- [SAIL-VL is a state-of-the-art vision-language model (VLM) developed by the Bytedance Douyin Content Team.](https://huggingface.co/BytedanceDouyinContent/SAIL-VL-2B)  🤗 
- [Moondream 2025-01-09 Release: Structured Text, Enhanced OCR, Gaze Detection](https://moondream.ai/blog/introducing-a-new-moondream-1-9b-and-gpu-support) 

	 · ([𝕏](https://x.com/vikhyatk/status/1877407680228143370)) · ([docs.moondream](https://docs.moondream.ai/quick-start))
- **The Illusion-Illusion: Vision Language Models See Illusions Where There 
  are None**, `arXiv, 2412.18613`, [arxiv](http://arxiv.org/abs/2412.18613v1), [pdf](http://arxiv.org/pdf/2412.18613v1.pdf), cication: [**-1**](None) 

	 *Tomer Ullman*

	 · ([𝕏](https://x.com/TomerUllman/status/1869742224524861836))
- **Are Vision-Language Models Truly Understanding Multi-vision Sensor?**, `arXiv, 2412.20750`, [arxiv](http://arxiv.org/abs/2412.20750v1), [pdf](http://arxiv.org/pdf/2412.20750v1.pdf), cication: [**-1**](None) 

	 *Sangyun Chung, Youngjoon Yu, Youngchae Chee, ..., Byung-Kwan Lee, Yong Man Ro*
- 🌟 [QVQ-72B-Preview is an experimental research model developed by the Qwen team, focusing on enhancing visual reasoning capabilities.](https://huggingface.co/Qwen/QVQ-72B-Preview)  🤗 
- **SynerGen-VL: Towards Synergistic Image Understanding and Generation with 
  Vision Experts and Token Folding**, `arXiv, 2412.09604`, [arxiv](http://arxiv.org/abs/2412.09604v1), [pdf](http://arxiv.org/pdf/2412.09604v1.pdf), cication: [**-1**](None) 

	 *Hao Li, Changyao Tian, Jie Shao, ..., Lewei Lu, Jifeng Dai*
- **POINTS1.5: Building a Vision-Language Model towards Real World 
  Applications**, `arXiv, 2412.08443`, [arxiv](http://arxiv.org/abs/2412.08443v1), [pdf](http://arxiv.org/pdf/2412.08443v1.pdf), cication: [**-1**](None) 

	 *Yuan Liu, Le Tian, Xiao Zhou, ..., Yang Yu, Jie Zhou*
- **OLA-VLM: Elevating Visual Perception in Multimodal LLMs with Auxiliary 
  Embedding Distillation**, `arXiv, 2412.09585`, [arxiv](http://arxiv.org/abs/2412.09585v1), [pdf](http://arxiv.org/pdf/2412.09585v1.pdf), cication: [**-1**](None) 

	 *Jitesh Jain, Zhengyuan Yang, Humphrey Shi, ..., Jianfeng Gao, Jianwei Yang* · ([OLA-VLM;](https://github.com/SHI-Labs/OLA-VLM;) - SHI-Labs) ![Star](https://img.shields.io/github/stars/SHI-Labs/OLA-VLM;.svg?style=social&label=Star) · ([praeclarumjj3.github](https://praeclarumjj3.github.io/ola_vlm/))
- 🌟 **NVILA: Efficient Frontier Visual Language Models**, `arXiv, 2412.04468`, [arxiv](http://arxiv.org/abs/2412.04468v1), [pdf](http://arxiv.org/pdf/2412.04468v1.pdf), cication: [**-1**](None) 

	 *Zhijian Liu, Ligeng Zhu, Baifeng Shi, ..., Song Han, Yao Lu*
- [moondream is a small vision language model designed to run efficiently on edge devices.](https://huggingface.co/vikhyatk/moondream2)  🤗 
- 🌟 **Expanding Performance Boundaries of Open-Source Multimodal Models with 
  Model, Data, and Test-Time Scaling**, `arXiv, 2412.05271`, [arxiv](http://arxiv.org/abs/2412.05271v1), [pdf](http://arxiv.org/pdf/2412.05271v1.pdf), cication: [**-1**](None) 

	 *Zhe Chen, Weiyun Wang, Yue Cao, ..., Jifeng Dai, Wenhai Wang*
- 🌟 **MAmmoTH-VL: Eliciting Multimodal Reasoning with Instruction Tuning at 
  Scale**, `arXiv, 2412.05237`, [arxiv](http://arxiv.org/abs/2412.05237v1), [pdf](http://arxiv.org/pdf/2412.05237v1.pdf), cication: [**-1**](None) 

	 *Jarvis Guo, Tuney Zheng, Yuelin Bai, ..., Wenhu Chen, Xiang Yue* · ([𝕏](https://x.com/xiangyue96/status/1866305201550114948))
- 🌟 **Molmo and PixMo: Open Weights and Open Data for State-of-the-Art 
  Vision-Language Models**, `arXiv, 2409.17146`, [arxiv](http://arxiv.org/abs/2409.17146v2), [pdf](http://arxiv.org/pdf/2409.17146v2.pdf), cication: [**-1**](None) 

	 *Matt Deitke, Christopher Clark, Sangho Lee, ..., Ali Farhadi, Aniruddha Kembhavi* · ([molmo](https://github.com/allenai/molmo) - allenai) ![Star](https://img.shields.io/github/stars/allenai/molmo.svg?style=social&label=Star)
- 🌟 **Florence-VL: Enhancing Vision-Language Models with Generative Vision 
  Encoder and Depth-Breadth Fusion**, `arXiv, 2412.04424`, [arxiv](http://arxiv.org/abs/2412.04424v1), [pdf](http://arxiv.org/pdf/2412.04424v1.pdf), cication: [**-1**](None) 

	 *Jiuhai Chen, Jianwei Yang, Haiping Wu, ..., Tianyi Zhou, Bin Xiao* · ([huggingface](https://huggingface.co/spaces/jiuhai/Florence-VL-8B))
- **Discriminative Fine-tuning of LVLMs**, `arXiv, 2412.04378`, [arxiv](http://arxiv.org/abs/2412.04378v2), [pdf](http://arxiv.org/pdf/2412.04378v2.pdf), cication: [**-1**](None) 

	 *Yassine Ouali, Adrian Bulat, Alexandros Xenos, ..., Brais Martinez, Georgios Tzimiropoulos*
- **CompCap: Improving Multimodal Large Language Models with Composite 
  Captions**, `arXiv, 2412.05243`, [arxiv](http://arxiv.org/abs/2412.05243v1), [pdf](http://arxiv.org/pdf/2412.05243v1.pdf), cication: [**-1**](None) 

	 *Xiaohui Chen, Satya Narayan Shukla, Mahmoud Azab, ..., Xuewen Zhang, Baosheng He*
- **Maya: An Instruction Finetuned Multilingual Multimodal Model**, `arXiv, 2412.07112`, [arxiv](http://arxiv.org/abs/2412.07112v1), [pdf](http://arxiv.org/pdf/2412.07112v1.pdf), cication: [**-1**](None) 

	 *Nahid Alam, Karthik Reddy Kanjula, Surya Guthikonda, ..., Snehanshu Mukherjee, Alham Fikri Aji* · ([maya](https://github.com/nahidalam/maya) - nahidalam) ![Star](https://img.shields.io/github/stars/nahidalam/maya.svg?style=social&label=Star)
- [Welcome PaliGemma 2 – New vision language models by Google](https://huggingface.co/blog/paligemma2)  🤗 

	 · ([𝕏](https://x.com/mervenoyann/status/1864724906409177365))
- **FINECAPTION: Compositional Image Captioning Focusing on Wherever You 
  Want at Any Granularity**, `arXiv, 2411.15411`, [arxiv](http://arxiv.org/abs/2411.15411v1), [pdf](http://arxiv.org/pdf/2411.15411v1.pdf), cication: [**-1**](None) 

	 *Hang Hua, Qing Liu, Lingzhi Zhang, ..., Jianming Zhang, Jiebo Luo*
- **Llama Guard 3 Vision: Safeguarding Human-AI Image Understanding 
  Conversations**, `arXiv, 2411.10414`, [arxiv](http://arxiv.org/abs/2411.10414v1), [pdf](http://arxiv.org/pdf/2411.10414v1.pdf), cication: [**-1**](None) 

	 *Jianfeng Chi, Ujjwal Karn, Hongyuan Zhan, ..., Kartikeya Upasani, Mahesh Pasupuleti* · ([llama](https://www.llama.com/trust-and-safety/)) · ([llama-recipes](https://github.com/meta-llama/llama-recipes/tree/main/recipes/responsible_ai/llama_guard) - meta-llama) ![Star](https://img.shields.io/github/stars/meta-llama/llama-recipes.svg?style=social&label=Star)
- **Unified Generative and Discriminative Training for Multi-modal Large 
  Language Models**, `arXiv, 2411.00304`, [arxiv](http://arxiv.org/abs/2411.00304v1), [pdf](http://arxiv.org/pdf/2411.00304v1.pdf), cication: [**-1**](None) 

	 *Wei Chow, Juncheng Li, Qifan Yu, ..., Hanwang Zhang, Qianru Sun*
- 🌟 **CLEAR: Character Unlearning in Textual and Visual Modalities**, `arXiv, 2410.18057`, [arxiv](http://arxiv.org/abs/2410.18057v1), [pdf](http://arxiv.org/pdf/2410.18057v1.pdf), cication: [**-1**](None) 

	 *Alexey Dontsov, Dmitrii Korzh, Alexey Zhavoronkin, ..., Ivan Oseledets, Elena Tutubalina* · ([huggingface](https://huggingface.co/datasets/therem/CLEAR)) · ([multimodal_unlearning](https://github.com/somvy/multimodal_unlearning) - somvy) ![Star](https://img.shields.io/github/stars/somvy/multimodal_unlearning.svg?style=social&label=Star)
- **Improve Vision Language Model Chain-of-thought Reasoning**, `arXiv, 2410.16198`, [arxiv](http://arxiv.org/abs/2410.16198v1), [pdf](http://arxiv.org/pdf/2410.16198v1.pdf), cication: [**-1**](None) 

	 *Ruohong Zhang, Bowen Zhang, Yanghao Li, ..., Ruoming Pang, Yiming Yang*

	 · ([LLaVA-Reasoner-DPO](https://github.com/RifleZhang/LLaVA-Reasoner-DPO) - RifleZhang) ![Star](https://img.shields.io/github/stars/RifleZhang/LLaVA-Reasoner-DPO.svg?style=social&label=Star)
- **Mitigating Object Hallucination via Concentric Causal Attention**, `arXiv, 2410.15926`, [arxiv](http://arxiv.org/abs/2410.15926v1), [pdf](http://arxiv.org/pdf/2410.15926v1.pdf), cication: [**-1**](None) 

	 *Yun Xing, Yiheng Li, Ivan Laptev, ..., Shijian Lu*

	 · ([cca-llava](https://github.com/xing0047/cca-llava) - xing0047) ![Star](https://img.shields.io/github/stars/xing0047/cca-llava.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/abs/2410.15926))

## Image

- **ChatRex: Taming Multimodal LLM for Joint Perception and Understanding**, `arXiv, 2411.18363`, [arxiv](http://arxiv.org/abs/2411.18363v2), [pdf](http://arxiv.org/pdf/2411.18363v2.pdf), cication: [**-1**](None) 

	 *Qing Jiang, Gen Luo, Yuqin Yang, ..., Tianhe Ren, Lei Zhang* · ([chatrex](https://github.com/idea-research/chatrex?tab=readme-ov-file) - idea-research) ![Star](https://img.shields.io/github/stars/idea-research/chatrex.svg?style=social&label=Star)
- **DINO-X: A Unified Vision Model for Open-World Object Detection and 
  Understanding**, `arXiv, 2411.14347`, [arxiv](http://arxiv.org/abs/2411.14347v1), [pdf](http://arxiv.org/pdf/2411.14347v1.pdf), cication: [**-1**](None) 

	 *Tianhe Ren, Yihao Chen, Qing Jiang, ..., Kent Yu, Lei Zhang*
- **Teach Multimodal LLMs to Comprehend Electrocardiographic Images**, `arXiv, 2410.19008`, [arxiv](http://arxiv.org/abs/2410.19008v1), [pdf](http://arxiv.org/pdf/2410.19008v1.pdf), cication: [**-1**](None) 

	 *Ruoqi Liu, Yuelin Bai, Xiang Yue, ..., Ping Zhang*

## Video

- **InternVideo2.5: Empowering Video MLLMs with Long and Rich Context 
  Modeling**, `arXiv, 2501.12386`, [arxiv](http://arxiv.org/abs/2501.12386v2), [pdf](http://arxiv.org/pdf/2501.12386v2.pdf), cication: [**-1**](None) 

	 *Yi Wang, Xinhao Li, Ziang Yan, ..., Yali Wang, Limin Wang* · ([InternVideo](https://github.com/OpenGVLab/InternVideo/tree/main/InternVideo2.5) - OpenGVLab) ![Star](https://img.shields.io/github/stars/OpenGVLab/InternVideo.svg?style=social&label=Star)
- **MMVU: Measuring Expert-Level Multi-Discipline Video Understanding**, `arXiv, 2501.12380`, [arxiv](http://arxiv.org/abs/2501.12380v1), [pdf](http://arxiv.org/pdf/2501.12380v1.pdf), cication: [**-1**](None) 

	 *Yilun Zhao, Lujing Xie, Haowei Zhang, ..., Chen Zhao, Arman Cohan* · ([mmvu-benchmark.github](https://mmvu-benchmark.github.io)) · ([MMVU](https://github.com/yale-nlp/MMVU) - yale-nlp) ![Star](https://img.shields.io/github/stars/yale-nlp/MMVU.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/datasets/yale-nlp/MMVU)) · ([mmvu-benchmark.github](https://mmvu-benchmark.github.io/))
- **Video-MMMU: Evaluating Knowledge Acquisition from Multi-Discipline 
  Professional Videos**, `arXiv, 2501.13826`, [arxiv](http://arxiv.org/abs/2501.13826v1), [pdf](http://arxiv.org/pdf/2501.13826v1.pdf), cication: [**-1**](None) 

	 *Kairui Hu, Penghao Wu, Fanyi Pu, ..., Bo Li, Ziwei Liu*
- 🌟 **VideoLLaMA 3: Frontier Multimodal Foundation Models for Image and Video 
  Understanding**, `arXiv, 2501.13106`, [arxiv](http://arxiv.org/abs/2501.13106v2), [pdf](http://arxiv.org/pdf/2501.13106v2.pdf), cication: [**-1**](None) 

	 *Boqiang Zhang, Kehan Li, Zesen Cheng, ..., Lidong Bing, Deli Zhao* · ([VideoLLaMA3](https://github.com/DAMO-NLP-SG/VideoLLaMA3) - DAMO-NLP-SG) ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/VideoLLaMA3.svg?style=social&label=Star)
- **Omni-RGPT: Unifying Image and Video Region-level Understanding via Token 
  Marks**, `arXiv, 2501.08326`, [arxiv](http://arxiv.org/abs/2501.08326v1), [pdf](http://arxiv.org/pdf/2501.08326v1.pdf), cication: [**-1**](None) 

	 *Miran Heo, Min-Hung Chen, De-An Huang, ..., Yu-Chiang Frank Wang, Ryo Hachiuma* · ([miranheo.github](https://miranheo.github.io/omni-rgpt/))
- **Tarsier2: Advancing Large Vision-Language Models from Detailed Video 
  Description to Comprehensive Video Understanding**, `arXiv, 2501.07888`, [arxiv](http://arxiv.org/abs/2501.07888v2), [pdf](http://arxiv.org/pdf/2501.07888v2.pdf), cication: [**-1**](None) 

	 *Liping Yuan, Jiawei Wang, Haomiao Sun, ..., Yuchen Zhang, Yuan Lin*
- **An Empirical Study of Autoregressive Pre-training from Videos**, `arXiv, 2501.05453`, [arxiv](http://arxiv.org/abs/2501.05453v1), [pdf](http://arxiv.org/pdf/2501.05453v1.pdf), cication: [**-1**](None) 

	 *Jathushan Rajasegaran, Ilija Radosavovic, Rahul Ravishankar, ..., Christoph Feichtenhofer, Jitendra Malik* · ([brjathu.github](https://brjathu.github.io/toto/))
- **Dispider: Enabling Video LLMs with Active Real-Time Interaction via 
  Disentangled Perception, Decision, and Reaction**, `arXiv, 2501.03218`, [arxiv](http://arxiv.org/abs/2501.03218v1), [pdf](http://arxiv.org/pdf/2501.03218v1.pdf), cication: [**-1**](None) 

	 *Rui Qian, Shuangrui Ding, Xiaoyi Dong, ..., Dahua Lin, Jiaqi Wang* · ([Dispider](https://github.com/Mark12Ding/Dispider) - Mark12Ding) ![Star](https://img.shields.io/github/stars/Mark12Ding/Dispider.svg?style=social&label=Star)
- **MotionBench: Benchmarking and Improving Fine-grained Video Motion 
  Understanding for Vision Language Models**, `arXiv, 2501.02955`, [arxiv](http://arxiv.org/abs/2501.02955v1), [pdf](http://arxiv.org/pdf/2501.02955v1.pdf), cication: [**-1**](None) 

	 *Wenyi Hong, Yean Cheng, Zhuoyi Yang, ..., Yuxiao Dong, Jie Tang* · ([motion-bench.github](https://motion-bench.github.io))
- **Sa2VA: Marrying SAM2 with LLaVA for Dense Grounded Understanding of 
  Images and Videos**, `arXiv, 2501.04001`, [arxiv](http://arxiv.org/abs/2501.04001v1), [pdf](http://arxiv.org/pdf/2501.04001v1.pdf), cication: [**-1**](None) 

	 *Haobo Yuan, Xiangtai Li, Tao Zhang, ..., Jiashi Feng, Ming-Hsuan Yang* · ([Sa2VA](https://github.com/magic-research/Sa2VA) - magic-research) ![Star](https://img.shields.io/github/stars/magic-research/Sa2VA.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/abs/2501.04001)) · ([huggingface](https://huggingface.co/ByteDance/Sa2VA-4B)) · ([lxtgh.github](https://lxtgh.github.io/project/sa2va/))
- **VideoRefer Suite: Advancing Spatial-Temporal Object Understanding with 
  Video LLM**, `arXiv, 2501.00599`, [arxiv](http://arxiv.org/abs/2501.00599v2), [pdf](http://arxiv.org/pdf/2501.00599v2.pdf), cication: [**-1**](None) 

	 *Yuqian Yuan, Hang Zhang, Wentong Li, ..., Jianke Zhu, Lidong Bing*
- **Video-Panda: Parameter-efficient Alignment for Encoder-free 
  Video-Language Models**, `arXiv, 2412.18609`, [arxiv](http://arxiv.org/abs/2412.18609v1), [pdf](http://arxiv.org/pdf/2412.18609v1.pdf), cication: [**-1**](None) 

	 *Jinhui Yi, Syed Talal Wasim, Yanan Luo, ..., Muzammal Naseer, Juergen Gall* · ([Video-Panda](https://github.com/jh-yi/Video-Panda) - jh-yi) ![Star](https://img.shields.io/github/stars/jh-yi/Video-Panda.svg?style=social&label=Star)
- 🌟 **Apollo: An Exploration of Video Understanding in Large Multimodal Models**, `arXiv, 2412.10360`, [arxiv](http://arxiv.org/abs/2412.10360v1), [pdf](http://arxiv.org/pdf/2412.10360v1.pdf), cication: [**-1**](None) 

	 *Orr Zohar, Xiaohan Wang, Yann Dubois, ..., Serena Yeung-Levy, Xide Xia* · ([apollo-lmms.github](https://apollo-lmms.github.io)) · ([huggingface](https://huggingface.co/spaces/Apollo-LMMs/Apollo-3B)) · ([Apollo](https://github.com/Apollo-LMMs/Apollo/) - Apollo-LMMs) ![Star](https://img.shields.io/github/stars/Apollo-LMMs/Apollo.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/Apollo-LMMs))
- **StreamChat: Chatting with Streaming Video**, `arXiv, 2412.08646`, [arxiv](http://arxiv.org/abs/2412.08646v1), [pdf](http://arxiv.org/pdf/2412.08646v1.pdf), cication: [**-1**](None) 

	 *Jihao Liu, Zhiding Yu, Shiyi Lan, ..., Hongsheng Li, Jose M. Alvare* · ([jihaonew.github](https://jihaonew.github.io/projects/streamchat.html))
- **VideoICL: Confidence-based Iterative In-context Learning for 
  Out-of-Distribution Video Understanding**, `arXiv, 2412.02186`, [arxiv](http://arxiv.org/abs/2412.02186v1), [pdf](http://arxiv.org/pdf/2412.02186v1.pdf), cication: [**-1**](None) 

	 *Kangsan Kim, Geon Park, Youngwan Lee, ..., Woongyeong Yeo, Sung Ju Hwang*
- **Towards Universal Soccer Video Understanding**, `arXiv, 2412.01820`, [arxiv](http://arxiv.org/abs/2412.01820v2), [pdf](http://arxiv.org/pdf/2412.01820v2.pdf), cication: [**-1**](None) 

	 *Jiayuan Rao, Haoning Wu, Hao Jiang, ..., Yanfeng Wang, Weidi Xie* · ([jyrao.github](https://jyrao.github.io/UniSoccer/)) · ([arxiv](https://arxiv.org/abs/2412.01820)) · ([UniSoccer](https://github.com/jyrao/UniSoccer) - jyrao) ![Star](https://img.shields.io/github/stars/jyrao/UniSoccer.svg?style=social&label=Star)
- **VideoEspresso: A Large-Scale Chain-of-Thought Dataset for Fine-Grained 
  Video Reasoning via Core Frame Selection**, `arXiv, 2411.14794`, [arxiv](http://arxiv.org/abs/2411.14794v1), [pdf](http://arxiv.org/pdf/2411.14794v1.pdf), cication: [**-1**](None) 

	 *Songhao Han, Wei Huang, Hairong Shi, ..., Yue Liao, Si Liu* · ([VideoEspresso](https://github.com/hshjerry/VideoEspresso) - hshjerry) ![Star](https://img.shields.io/github/stars/hshjerry/VideoEspresso.svg?style=social&label=Star)
- **TimeMarker: A Versatile Video-LLM for Long and Short Video Understanding 
  with Superior Temporal Localization Ability**, `arXiv, 2411.18211`, [arxiv](http://arxiv.org/abs/2411.18211v1), [pdf](http://arxiv.org/pdf/2411.18211v1.pdf), cication: [**-1**](None) 

	 *Shimin Chen, Xiaohan Lan, Yitian Yuan, ..., Zequn Jie, Lin Ma* · ([TimeMarker](https://github.com/TimeMarker-LLM/TimeMarker/) - TimeMarker-LLM) ![Star](https://img.shields.io/github/stars/TimeMarker-LLM/TimeMarker.svg?style=social&label=Star)
- **Number it: Temporal Grounding Videos like Flipping Manga**, `arXiv, 2411.10332`, [arxiv](http://arxiv.org/abs/2411.10332v1), [pdf](http://arxiv.org/pdf/2411.10332v1.pdf), cication: [**-1**](None) 

	 *Yongliang Wu, Xinting Hu, Yuyang Sun, ..., Bernt Schiele, Xu Yang* · ([NumPro.](https://github.com/yongliang-wu/NumPro.) - yongliang-wu) ![Star](https://img.shields.io/github/stars/yongliang-wu/NumPro..svg?style=social&label=Star)
- **Video-RAG: Visually-aligned Retrieval-Augmented Long Video Comprehension**, `arXiv, 2411.13093`, [arxiv](http://arxiv.org/abs/2411.13093v1), [pdf](http://arxiv.org/pdf/2411.13093v1.pdf), cication: [**-1**](None) 

	 *Yongdong Luo, Xiawu Zheng, Xiao Yang, ..., Jiebo Luo, Rongrong Ji*
- **PPLLaVA: Varied Video Sequence Understanding With Prompt Guidance**, `arXiv, 2411.02327`, [arxiv](http://arxiv.org/abs/2411.02327v2), [pdf](http://arxiv.org/pdf/2411.02327v2.pdf), cication: [**-1**](None) 

	 *Ruyang Liu, Haoran Tang, Haibo Liu, ..., Chen Li, Jiankun Yang* · ([PPLLaVA.](https://github.com/farewellthree/PPLLaVA.) - farewellthree) ![Star](https://img.shields.io/github/stars/farewellthree/PPLLaVA..svg?style=social&label=Star)
- **VideoGLaMM: A Large Multimodal Model for Pixel-Level Visual Grounding in 
  Videos**, `arXiv, 2411.04923`, [arxiv](http://arxiv.org/abs/2411.04923v1), [pdf](http://arxiv.org/pdf/2411.04923v1.pdf), cication: [**-1**](None) 

	 *Shehan Munasinghe, Hanan Gani, Wenqi Zhu, ..., Fahad Shahbaz Khan, Salman Khan* · ([mbzuai-oryx.github](https://mbzuai-oryx.github.io/VideoGLaMM/))
- **xGen-MM-Vid (BLIP-3-Video): You Only Need 32 Tokens to Represent a Video 
  Even in VLMs**, `arXiv, 2410.16267`, [arxiv](http://arxiv.org/abs/2410.16267v1), [pdf](http://arxiv.org/pdf/2410.16267v1.pdf), cication: [**-1**](None)

	 *Michael S. Ryoo, Honglu Zhou, Shrikant Kendre, ..., Caiming Xiong, Juan Carlos Niebles*

	 · ([salesforceairesearch](https://www.salesforceairesearch.com/opensource/xGen-MM-Vid/index.html))
- **LongVU: Spatiotemporal Adaptive Compression for Long Video-Language 
  Understanding**, `arXiv, 2410.17434`, [arxiv](http://arxiv.org/abs/2410.17434v1), [pdf](http://arxiv.org/pdf/2410.17434v1.pdf), cication: [**-1**](None)

	 *Xiaoqian Shen, Yunyang Xiong, Changsheng Zhao, ..., Mohamed Elhoseiny, Vikas Chandra*

	 · ([vision-cair.github](https://vision-cair.github.io/LongVU)) · ([LongVU](https://github.com/Vision-CAIR/LongVU) - Vision-CAIR) ![Star](https://img.shields.io/github/stars/Vision-CAIR/LongVU.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/collections/Vision-CAIR/longvu-67181d2debabfc1eb050c21d)) · ([huggingface](https://huggingface.co/spaces/Vision-CAIR/LongVU))
- **VidEgoThink: Assessing Egocentric Video Understanding Capabilities for 
  Embodied AI**, `arXiv, 2410.11623`, [arxiv](http://arxiv.org/abs/2410.11623v1), [pdf](http://arxiv.org/pdf/2410.11623v1.pdf), cication: [**-1**](None)

	 *Sijie Cheng, Kechen Fang, Yangyang Yu, ..., Lei Han, Yang Liu*
- **OMCAT: Omni Context Aware Transformer**, `arXiv, 2410.12109`, [arxiv](http://arxiv.org/abs/2410.12109v1), [pdf](http://arxiv.org/pdf/2410.12109v1.pdf), cication: [**-1**](None) 

	 *Arushi Goel, Karan Sapra, Matthieu Le, ..., Andrew Tao, Bryan Catanzaro* · ([om-cat.github](https://om-cat.github.io/))

## Encoder

- **Learnings from Scaling Visual Tokenizers for Reconstruction and 
  Generation**, `arXiv, 2501.09755`, [arxiv](http://arxiv.org/abs/2501.09755v1), [pdf](http://arxiv.org/pdf/2501.09755v1.pdf), cication: [**-1**](None) 

	 *Philippe Hansen-Estruch, David Yan, Ching-Yao Chung, ..., Peter Vajda, Xinlei Chen* · ([vitok.github](https://vitok.github.io/))
- **Unifying Specialized Visual Encoders for Video Language Models**, `arXiv, 2501.01426`, [arxiv](http://arxiv.org/abs/2501.01426v1), [pdf](http://arxiv.org/pdf/2501.01426v1.pdf), cication: [**-1**](None) 

	 *Jihoon Chung, Tyler Zhu, Max Gonzalez Saez-Diez, ..., Honglu Zhou, Olga Russakovsky* · ([tylerzhu](https://tylerzhu.com/merv)) · ([merv](https://github.com/princetonvisualai/merv) - princetonvisualai) ![Star](https://img.shields.io/github/stars/princetonvisualai/merv.svg?style=social&label=Star)
- **LLaVA-UHD v2: an MLLM Integrating High-Resolution Feature Pyramid via 
  Hierarchical Window Transformer**, `arXiv, 2412.13871`, [arxiv](http://arxiv.org/abs/2412.13871v1), [pdf](http://arxiv.org/pdf/2412.13871v1.pdf), cication: [**-1**](None) 

	 *Yipeng Zhang, Yifan Liu, Zonghao Guo, ..., Tat-Seng Chua, Maosong Sun* · ([LLaVA-UHD](https://github.com/thunlp/LLaVA-UHD) - thunlp) ![Star](https://img.shields.io/github/stars/thunlp/LLaVA-UHD.svg?style=social&label=Star)
- **FastVLM: Efficient Vision Encoding for Vision Language Models**, `arXiv, 2412.13303`, [arxiv](http://arxiv.org/abs/2412.13303v1), [pdf](http://arxiv.org/pdf/2412.13303v1.pdf), cication: [**-1**](None) 

	 *Pavan Kumar Anasosalu Vasu, Fartash Faghri, Chun-Liang Li, ..., Oncel Tuzel, Hadi Pouransari*
- **TRecViT: A Recurrent Video Transformer**, `arXiv, 2412.14294`, [arxiv](http://arxiv.org/abs/2412.14294v1), [pdf](http://arxiv.org/pdf/2412.14294v1.pdf), cication: [**-1**](None) 

	 *Viorica Pătrăucean, Xu Owen He, Joseph Heyward, ..., João Carreira, Razvan Pascanu* · ([trecvit](https://github.com/google-deepmind/trecvit) - google-deepmind) ![Star](https://img.shields.io/github/stars/google-deepmind/trecvit.svg?style=social&label=Star)
- **PruneVid: Visual Token Pruning for Efficient Video Large Language Models**, `arXiv, 2412.16117`, [arxiv](http://arxiv.org/abs/2412.16117v1), [pdf](http://arxiv.org/pdf/2412.16117v1.pdf), cication: [**-1**](None) 

	 *Xiaohu Huang, Hao Zhou, Kai Han* · ([PruneVid](https://github.com/Visual-AI/PruneVid) - Visual-AI) ![Star](https://img.shields.io/github/stars/Visual-AI/PruneVid.svg?style=social&label=Star)
- **Large Motion Video Autoencoding with Cross-modal Video VAE**, `arXiv, 2412.17805`, [arxiv](http://arxiv.org/abs/2412.17805v1), [pdf](http://arxiv.org/pdf/2412.17805v1.pdf), cication: [**-1**](None) 

	 *Yazhou Xing, Yang Fei, Yingqing He, ..., Xiaowei Chi, Qifeng Chen* · ([VideoVAEPlus](https://github.com/VideoVerses/VideoVAEPlus) - VideoVerses) ![Star](https://img.shields.io/github/stars/VideoVerses/VideoVAEPlus.svg?style=social&label=Star)
- 🌟 **VisionZip: Longer is Better but Not Necessary in Vision Language Models**, `arXiv, 2412.04467`, [arxiv](http://arxiv.org/abs/2412.04467v1), [pdf](http://arxiv.org/pdf/2412.04467v1.pdf), cication: [**-1**](None) 

	 *Senqiao Yang, Yukang Chen, Zhuotao Tian, ..., Bei Yu, Jiaya Jia* · ([202.104.135](http://202.104.135.156:7860/)) · ([youtu](https://youtu.be/sytaAzmxxpo?si=IieArmQ7YNf2dVyM)) · ([VisionZip](https://github.com/dvlab-research/VisionZip) - dvlab-research) ![Star](https://img.shields.io/github/stars/dvlab-research/VisionZip.svg?style=social&label=Star)
- **[CLS] Token Tells Everything Needed for Training-free Efficient MLLMs**, `arXiv, 2412.05819`, [arxiv](http://arxiv.org/abs/2412.05819v1), [pdf](http://arxiv.org/pdf/2412.05819v1.pdf), cication: [**-1**](None) 

	 *Ao Wang, Fengyuan Sun, Hui Chen, ..., Jungong Han, Guiguang Ding* · ([VTC-CLS](https://github.com/THU-MIG/VTC-CLS) - THU-MIG) ![Star](https://img.shields.io/github/stars/THU-MIG/VTC-CLS.svg?style=social&label=Star)
- **FocusLLaVA: A Coarse-to-Fine Approach for Efficient and Effective Visual 
  Token Compression**, `arXiv, 2411.14228`, [arxiv](http://arxiv.org/abs/2411.14228v1), [pdf](http://arxiv.org/pdf/2411.14228v1.pdf), cication: [**-1**](None) 

	 *Yuke Zhu, Chi Xie, Shuang Liang, ..., Bo Zheng, Sheng Guo*
- **DyCoke: Dynamic Compression of Tokens for Fast Video Large Language 
  Models**, `arXiv, 2411.15024`, [arxiv](http://arxiv.org/abs/2411.15024v1), [pdf](http://arxiv.org/pdf/2411.15024v1.pdf), cication: [**-1**](None) 

	 *Keda Tao, Can Qin, Haoxuan You, ..., Yang Sui, Huan Wang*
- **Factorized Visual Tokenization and Generation**, `arXiv, 2411.16681`, [arxiv](http://arxiv.org/abs/2411.16681v2), [pdf](http://arxiv.org/pdf/2411.16681v2.pdf), cication: [**-1**](None) 

	 *Zechen Bai, Jianxiong Gao, Ziteng Gao, ..., Tong He, Mike Zheng Shou* · ([showlab.github](https://showlab.github.io/FQGAN/))
- **REDUCIO! Generating 1024$\times$1024 Video within 16 Seconds using 
  Extremely Compressed Motion Latents**, `arXiv, 2411.13552`, [arxiv](http://arxiv.org/abs/2411.13552v1), [pdf](http://arxiv.org/pdf/2411.13552v1.pdf), cication: [**-1**](None) 

	 *Rui Tian, Qi Dai, Jianmin Bao, ..., Zuxuan Wu, Yu-Gang Jiang* · ([Reducio-VAE](https://github.com/microsoft/Reducio-VAE) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/Reducio-VAE.svg?style=social&label=Star)
- **Multimodal Autoregressive Pre-training of Large Vision Encoders**, `arXiv, 2411.14402`, [arxiv](http://arxiv.org/abs/2411.14402v1), [pdf](http://arxiv.org/pdf/2411.14402v1.pdf), cication: [**-1**](None) 

	 *Enrico Fini, Mustafa Shukor, Xiujun Li, ..., Joshua M. Susskind, Alaaeldin El-Nouby* · ([ml-aim](https://github.com/apple/ml-aim) - apple) ![Star](https://img.shields.io/github/stars/apple/ml-aim.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/collections/apple/aimv2-6720fe1558d94c7805f7688c))
- **Don't Look Twice: Faster Video Transformers with Run-Length Tokenization**, `arXiv, 2411.05222`, [arxiv](http://arxiv.org/abs/2411.05222v1), [pdf](http://arxiv.org/pdf/2411.05222v1.pdf), cication: [**-1**](None) 

	 *Rohan Choudhury, Guanglei Zhu, Sihan Liu, ..., Kris M. Kitani, László Jeni* · ([rccchoudhury.github](https://rccchoudhury.github.io/projects/rlt)) · ([rlt](https://github.com/rccchoudhury/rlt?tab=readme-ov-file) - rccchoudhury) ![Star](https://img.shields.io/github/stars/rccchoudhury/rlt.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247758620&idx=2&sn=27eeae5b60283615f9abf3f8f0dd8780&chksm=e9d9b997a6e17483de1ee3b9e9199635e16afe381d3c7e19c0ccf8d02e937411137cda7f63d0&scene=0&xtrack=1))
- [SigLIP model pre-trained on WebLi at resolution 224x224.](https://huggingface.co/google/siglip-so400m-patch14-224)  🤗 
- 🌟 **LLM2CLIP: Powerful Language Model Unlocks Richer Visual Representation**, `arXiv, 2411.04997`, [arxiv](http://arxiv.org/abs/2411.04997v2), [pdf](http://arxiv.org/pdf/2411.04997v2.pdf), cication: [**-1**](None) 

	 *Weiquan Huang, Aoqi Wu, Yifan Yang, ..., Chong Luo, Lili Qiu* · ([aka](https://aka.ms/llm2clip)) · ([LLM2CLIP](https://github.com/microsoft/LLM2CLIP/) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/LLM2CLIP.svg?style=social&label=Star)
- **In Search of Forgotten Domain Generalization**, `arXiv, 2410.08258`, [arxiv](http://arxiv.org/abs/2410.08258v1), [pdf](http://arxiv.org/pdf/2410.08258v1.pdf), cication: [**-1**](None) 

	 *Prasanna Mayilvahanan, Roland S. Zimmermann, Thaddäus Wiedemer, ..., Matthias Bethge, Wieland Brendel* · ([𝕏](https://x.com/wielandbr/status/1856020430219555266))
- **Adaptive Length Image Tokenization via Recurrent Allocation**, `arXiv, 2411.02393`, [arxiv](http://arxiv.org/abs/2411.02393v1), [pdf](http://arxiv.org/pdf/2411.02393v1.pdf), cication: [**-1**](None) 

	 *Shivam Duggal, Phillip Isola, Antonio Torralba, ..., William T. Freeman*
- **LARP: Tokenizing Videos with a Learned Autoregressive Generative Prior**, `arXiv, 2410.21264`, [arxiv](http://arxiv.org/abs/2410.21264v1), [pdf](http://arxiv.org/pdf/2410.21264v1.pdf), cication: [**-1**](None) 

	 *Hanyu Wang, Saksham Suri, Yixuan Ren, ..., Hao Chen, Abhinav Shrivastava* · ([hywang66.github](https://hywang66.github.io/larp/))
- **Breaking the Memory Barrier: Near Infinite Batch Size Scaling for 
  Contrastive Loss**, `arXiv, 2410.17243`, [arxiv](http://arxiv.org/abs/2410.17243v1), [pdf](http://arxiv.org/pdf/2410.17243v1.pdf), cication: [**-1**](None)

	 *Zesen Cheng, Hang Zhang, Kehan Li, ..., Xin Li, Lidong Bing*

	 · ([Inf-CLIP](https://github.com/DAMO-NLP-SG/Inf-CLIP) - DAMO-NLP-SG) ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/Inf-CLIP.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/pdf/2410.17243))

## Alignment

- **InternLM-XComposer2.5-Reward: A Simple Yet Effective Multi-Modal Reward 
  Model**, `arXiv, 2501.12368`, [arxiv](http://arxiv.org/abs/2501.12368v1), [pdf](http://arxiv.org/pdf/2501.12368v1.pdf), cication: [**-1**](None) 

	 *Yuhang Zang, Xiaoyi Dong, Pan Zhang, ..., Dahua Lin, Jiaqi Wang* · ([InternLM-XComposer](https://github.com/InternLM/InternLM-XComposer) - InternLM) ![Star](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star)
- **Task Preference Optimization: Improving Multimodal Large Language Models 
  with Vision Task Alignment**, `arXiv, 2412.19326`, [arxiv](http://arxiv.org/abs/2412.19326v1), [pdf](http://arxiv.org/pdf/2412.19326v1.pdf), cication: [**-1**](None) 

	 *Ziang Yan, Zhilin Li, Yinan He, ..., Limin Wang, Yi Wang* · ([TPO](https://github.com/OpenGVLab/TPO) - OpenGVLab) ![Star](https://img.shields.io/github/stars/OpenGVLab/TPO.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/OpenGVLab/VideoChat-TPO))
- [Preference Optimization for Vision Language Models with TRL](https://huggingface.co/blog/dpo_vlm)  🤗 
- **On Domain-Specific Post-Training for Multimodal Large Language Models**, `arXiv, 2411.19930`, [arxiv](http://arxiv.org/abs/2411.19930v1), [pdf](http://arxiv.org/pdf/2411.19930v1.pdf), cication: [**-1**](None) 

	 *Daixuan Cheng, Shaohan Huang, Ziyu Zhu, ..., Bo Dai, Zhenliang Zhang* · ([huggingface](https://huggingface.co/AdaptLLM/Adapt-MLLM-to-Domains))
- 🌟 **Enhancing the Reasoning Ability of Multimodal Large Language Models via 
  Mixed Preference Optimization**, `arXiv, 2411.10442`, [arxiv](http://arxiv.org/abs/2411.10442v1), [pdf](http://arxiv.org/pdf/2411.10442v1.pdf), cication: [**-1**](None) 

	 *Weiyun Wang, Zhe Chen, Wenhai Wang, ..., Yu Qiao, Jifeng Dai* · ([internvl.github](https://internvl.github.io/blog/2024-11-14-InternVL-2.0-MPO/))
- **SymDPO: Boosting In-Context Learning of Large Multimodal Models with 
  Symbol Demonstration Direct Preference Optimization**, `arXiv, 2411.11909`, [arxiv](http://arxiv.org/abs/2411.11909v1), [pdf](http://arxiv.org/pdf/2411.11909v1.pdf), cication: [**-1**](None) 

	 *Hongrui Jia, Chaoya Jiang, Haiyang Xu, ..., Fei Huang, Shikun Zhang*
- **V-DPO: Mitigating Hallucination in Large Vision Language Models via 
  Vision-Guided Direct Preference Optimization**, `arXiv, 2411.02712`, [arxiv](http://arxiv.org/abs/2411.02712v1), [pdf](http://arxiv.org/pdf/2411.02712v1.pdf), cication: [**-1**](None) 

	 *Yuxi Xie, Guanzhen Li, Xiao Xu, ..., Min-Yen Kan* · ([V-DPO](https://github.com/YuxiXie/V-DPO) - YuxiXie) ![Star](https://img.shields.io/github/stars/YuxiXie/V-DPO.svg?style=social&label=Star)
- **MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large 
  Vision-Language Models**, `arXiv, 2410.17637`, [arxiv](http://arxiv.org/abs/2410.17637v1), [pdf](http://arxiv.org/pdf/2410.17637v1.pdf), cication: [**-1**](None)

	 *Ziyu Liu, Yuhang Zang, Xiaoyi Dong, ..., Dahua Lin, Jiaqi Wang*

## Reasoning

- **Imagine while Reasoning in Space: Multimodal Visualization-of-Thought**, `arXiv, 2501.07542`, [arxiv](http://arxiv.org/abs/2501.07542v1), [pdf](http://arxiv.org/pdf/2501.07542v1.pdf), cication: [**-1**](None) 

	 *Chengzu Li, Wenshan Wu, Huanyu Zhang, ..., Ivan Vulić, Furu Wei*
- 🌟 **LlamaV-o1: Rethinking Step-by-step Visual Reasoning in LLMs**, `arXiv, 2501.06186`, [arxiv](http://arxiv.org/abs/2501.06186v1), [pdf](http://arxiv.org/pdf/2501.06186v1.pdf), cication: [**-1**](None) 

	 *Omkar Thawakar, Dinura Dissanayake, Ketan More, ..., Fahad Shahbaz Khan, Salman Khan*
- [Multimodal Reasoning and its Applications to Computer Use and Robotics](https://www.youtube.com/watch?v=YdqJSjfi4iw)  :clapper: 
- 🌟 **Virgo: A Preliminary Exploration on Reproducing o1-like MLLM**, `arXiv, 2501.01904`, [arxiv](http://arxiv.org/abs/2501.01904v1), [pdf](http://arxiv.org/pdf/2501.01904v1.pdf), cication: [**-1**](None) 

	 *Yifan Du, Zikang Liu, Yifan Li, ..., Zhongyuan Wang, Ji-Rong Wen* · ([Virgo](https://github.com/RUCAIBox/Virgo) - RUCAIBox) ![Star](https://img.shields.io/github/stars/RUCAIBox/Virgo.svg?style=social&label=Star)
- **URSA: Understanding and Verifying Chain-of-thought Reasoning in 
  Multimodal Mathematics**, `arXiv, 2501.04686`, [arxiv](http://arxiv.org/abs/2501.04686v1), [pdf](http://arxiv.org/pdf/2501.04686v1.pdf), cication: [**-1**](None) 

	 *Ruilin Luo, Zhuofan Zheng, Yifan Wang, ..., Jin Zeng, Yujiu Yang* · ([ursa-math.github](https://ursa-math.github.io/))
- 🌟 **Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via 
  Collective Monte Carlo Tree Search**, `arXiv, 2412.18319`, [arxiv](http://arxiv.org/abs/2412.18319v1), [pdf](http://arxiv.org/pdf/2412.18319v1.pdf), cication: [**-1**](None) 

	 *Huanjin Yao, Jiaxing Huang, Wenhao Wu, ..., Li Shen, Dacheng Tao* · ([Mulberry](https://github.com/HJYao00/Mulberry) - HJYao00) ![Star](https://img.shields.io/github/stars/HJYao00/Mulberry.svg?style=social&label=Star)
- 🌟 **Thinking in Space: How Multimodal Large Language Models See, Remember, 
  and Recall Spaces**, `arXiv, 2412.14171`, [arxiv](http://arxiv.org/abs/2412.14171v1), [pdf](http://arxiv.org/pdf/2412.14171v1.pdf), cication: [**-1**](None) 

	 *Jihan Yang, Shusheng Yang, Anjali W. Gupta, ..., Li Fei-Fei, Saining Xie* · ([vision-x-nyu.github](https://vision-x-nyu.github.io/thinking-in-space.github.io/)) · ([thinking-in-space.git](https://github.com/vision-x-nyu/thinking-in-space.git) - vision-x-nyu) ![Star](https://img.shields.io/github/stars/vision-x-nyu/thinking-in-space.git.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/datasets/nyu-visionx/VSI-Bench))
- 🌟 **Progressive Multimodal Reasoning via Active Retrieval**, `arXiv, 2412.14835`, [arxiv](http://arxiv.org/abs/2412.14835v1), [pdf](http://arxiv.org/pdf/2412.14835v1.pdf), cication: [**-1**](None) 

	 *Guanting Dong, Chenghao Zhang, Mengjie Deng, ..., Zhicheng Dou, Ji-Rong Wen*
- 🌟 **Diving into Self-Evolving Training for Multimodal Reasoning**, `arXiv, 2412.17451`, [arxiv](http://arxiv.org/abs/2412.17451v1), [pdf](http://arxiv.org/pdf/2412.17451v1.pdf), cication: [**-1**](None) 

	 *Wei Liu, Junlong Li, Xiwen Zhang, ..., Yu Cheng, Junxian He* · ([mstar-lmm.github](https://mstar-lmm.github.io/))
- **TACO: Learning Multi-modal Action Models with Synthetic 
  Chains-of-Thought-and-Action**, `arXiv, 2412.05479`, [arxiv](http://arxiv.org/abs/2412.05479v2), [pdf](http://arxiv.org/pdf/2412.05479v2.pdf), cication: [**-1**](None) 

	 *Zixian Ma, Jianguo Zhang, Zhiwei Liu, ..., Ranjay Krishna, Silvio Savarese* · ([taco-project.github](https://taco-project.github.io)) · ([TACO](https://github.com/SalesforceAIResearch/TACO) - SalesforceAIResearch) ![Star](https://img.shields.io/github/stars/SalesforceAIResearch/TACO.svg?style=social&label=Star)
- 🌟 **LLaVA-o1: Let Vision Language Models Reason Step-by-Step**, `arXiv, 2411.10440`, [arxiv](http://arxiv.org/abs/2411.10440v1), [pdf](http://arxiv.org/pdf/2411.10440v1.pdf), cication: [**-1**](None) 

	 *Guowei Xu, Peng Jin, Li Hao, ..., Lichao Sun, Li Yuan* · ([LLaVA-o1](https://github.com/PKU-YuanGroup/LLaVA-o1) - PKU-YuanGroup) ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LLaVA-o1.svg?style=social&label=Star)
- [Llama-3.2V-11B-cot is the first version of LLaVA-o1, which is a visual language model capable of spontaneous, systematic reasoning.](https://huggingface.co/Xkev/Llama-3.2V-11B-cot)  🤗 
- **Vision-Language Models Can Self-Improve Reasoning via Reflection**, `arXiv, 2411.00855`, [arxiv](http://arxiv.org/abs/2411.00855v1), [pdf](http://arxiv.org/pdf/2411.00855v1.pdf), cication: [**-1**](None) 

	 *Kanzhi Cheng, Yantao Li, Fangzhi Xu, ..., Hao Zhou, Yang Liu*

## Evaluation

- **OVO-Bench: How Far is Your Video-LLMs from Real-World Online Video 
  Understanding?**, `arXiv, 2501.05510`, [arxiv](http://arxiv.org/abs/2501.05510v1), [pdf](http://arxiv.org/pdf/2501.05510v1.pdf), cication: [**-1**](None) 

	 *Yifei Li, Junbo Niu, Ziyang Miao, ..., Conghui He, Jiaqi Wang* · ([OVO-Bench](https://github.com/JoeLeelyf/OVO-Bench) - JoeLeelyf) ![Star](https://img.shields.io/github/stars/JoeLeelyf/OVO-Bench.svg?style=social&label=Star)
- **Multi-Dimensional Insights: Benchmarking Real-World Personalization in 
  Large Multimodal Models**, `arXiv, 2412.12606`, [arxiv](http://arxiv.org/abs/2412.12606v1), [pdf](http://arxiv.org/pdf/2412.12606v1.pdf), cication: [**-1**](None) 

	 *YiFan Zhang, Shanglin Lei, Runqi Qiao, ..., Xiaofei Wang, Honggang Zhang* · ([mdi-benchmark.github](https://mdi-benchmark.github.io/))
- **VisionArena: 230K Real World User-VLM Conversations with Preference 
  Labels**, `arXiv, 2412.08687`, [arxiv](http://arxiv.org/abs/2412.08687v1), [pdf](http://arxiv.org/pdf/2412.08687v1.pdf), cication: [**-1**](None) 

	 *Christopher Chou, Lisa Dunlap, Koki Mashita, ..., Joseph E. Gonzalez, Wei-Lin Chiang* · ([huggingface](https://huggingface.co/lmarena-ai))
- **VideoAutoArena: An Automated Arena for Evaluating Large Multimodal 
  Models in Video Analysis through User Simulation**, `arXiv, 2411.13281`, [arxiv](http://arxiv.org/abs/2411.13281v1), [pdf](http://arxiv.org/pdf/2411.13281v1.pdf), cication: [**-1**](None) 

	 *Ziyang Luo, Haoning Wu, Dongxu Li, ..., Mohan Kankanhalli, Junnan Li* · ([videoautoarena.github](https://videoautoarena.github.io!))
- **ViBe: A Text-to-Video Benchmark for Evaluating Hallucination in Large 
  Multimodal Models**, `arXiv, 2411.10867`, [arxiv](http://arxiv.org/abs/2411.10867v1), [pdf](http://arxiv.org/pdf/2411.10867v1.pdf), cication: [**-1**](None) 

	 *Vipula Rawte, Sarthak Jain, Aarush Sinha, ..., Amit P. Sheth, Amitava Das*
- **M-Longdoc: A Benchmark For Multimodal Super-Long Document Understanding 
  And A Retrieval-Aware Tuning Framework**, `arXiv, 2411.06176`, [arxiv](http://arxiv.org/abs/2411.06176v1), [pdf](http://arxiv.org/pdf/2411.06176v1.pdf), cication: [**-1**](None) 

	 *Yew Ken Chia, Liying Cheng, Hou Pong Chan, ..., Soujanya Poria, Lidong Bing* · ([multimodal-documents.github](https://multimodal-documents.github.io))
- **DynaMath: A Dynamic Visual Benchmark for Evaluating Mathematical 
  Reasoning Robustness of Vision Language Models**, `arXiv, 2411.00836`, [arxiv](http://arxiv.org/abs/2411.00836v1), [pdf](http://arxiv.org/pdf/2411.00836v1.pdf), cication: [**-1**](None) 

	 *Chengke Zou, Xingang Guo, Rui Yang, ..., Bin Hu, Huan Zhang* · ([DynaMath](https://github.com/DynaMath/DynaMath) - DynaMath) ![Star](https://img.shields.io/github/stars/DynaMath/DynaMath.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/datasets/DynaMath/DynaMath_Sample.))
- 🌟 **Both Text and Images Leaked! A Systematic Analysis of Multimodal LLM 
  Data Contamination**, `arXiv, 2411.03823`, [arxiv](http://arxiv.org/abs/2411.03823v1), [pdf](http://arxiv.org/pdf/2411.03823v1.pdf), cication: [**-1**](None) 

	 *Dingjie Song, Sicheng Lai, Shunian Chen, ..., Lichao Sun, Benyou Wang* · ([MM-Detect](https://github.com/MLLM-Data-Contamination/MM-Detect) - MLLM-Data-Contamination) ![Star](https://img.shields.io/github/stars/MLLM-Data-Contamination/MM-Detect.svg?style=social&label=Star)
- **StreamingBench: Assessing the Gap for MLLMs to Achieve Streaming Video 
  Understanding**, `arXiv, 2411.03628`, [arxiv](http://arxiv.org/abs/2411.03628v1), [pdf](http://arxiv.org/pdf/2411.03628v1.pdf), cication: [**-1**](None) 

	 *Junming Lin, Zheng Fang, Chi Chen, ..., Yang Liu, Maosong Sun*
- **TOMATO: Assessing Visual Temporal Reasoning Capabilities in Multimodal 
  Foundation Models**, `arXiv, 2410.23266`, [arxiv](http://arxiv.org/abs/2410.23266v1), [pdf](http://arxiv.org/pdf/2410.23266v1.pdf), cication: [**-1**](None) 

	 *Ziyao Shangguan, Chuhan Li, Yuxuan Ding, ..., Tesca Fitzgerald, Arman Cohan* · ([TOMATO](https://github.com/yale-nlp/TOMATO) - yale-nlp) ![Star](https://img.shields.io/github/stars/yale-nlp/TOMATO.svg?style=social&label=Star)
- **Image2Struct: Benchmarking Structure Extraction for Vision-Language 
  Models**, `arXiv, 2410.22456`, [arxiv](http://arxiv.org/abs/2410.22456v1), [pdf](http://arxiv.org/pdf/2410.22456v1.pdf), cication: [**-1**](None)

	 *Josselin Somerville Roberts, Tony Lee, Chi Heem Wong, ..., Yifan Mai, Percy Liang* · ([crfm.stanford](https://crfm.stanford.edu/helm/image2struct/v1.0.1/)) · ([x](https://x.com/JossSomerville/status/1852354431766909264))
- **AVHBench: A Cross-Modal Hallucination Benchmark for Audio-Visual Large 
  Language Models**, `arXiv, 2410.18325`, [arxiv](http://arxiv.org/abs/2410.18325v1), [pdf](http://arxiv.org/pdf/2410.18325v1.pdf), cication: [**-1**](None)

	 *Kim Sung-Bin, Oh Hyun-Bin, JungMok Lee, ..., Joon Son Chung, Tae-Hyun Oh*

	 · ([AVHBench](https://github.com/AVHBench/AVHBench) - AVHBench) ![Star](https://img.shields.io/github/stars/AVHBench/AVHBench.svg?style=social&label=Star)
- **MMIE: Massive Multimodal Interleaved Comprehension Benchmark for Large 
  Vision-Language Models**, `arXiv, 2410.10139`, [arxiv](http://arxiv.org/abs/2410.10139v1), [pdf](http://arxiv.org/pdf/2410.10139v1.pdf), cication: [**-1**](None)

	 *Peng Xia, Siwei Han, Shi Qiu, ..., Lijuan Wang, Huaxiu Yao* · ([mmie-bench.github](https://mmie-bench.github.io/)) · ([MMIE](https://github.com/Lillianwei-h/MMIE) - Lillianwei-h) ![Star](https://img.shields.io/github/stars/Lillianwei-h/MMIE.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/MMIE/MMIE-Score))
- **MEGA-Bench: Scaling Multimodal Evaluation to over 500 Real-World Tasks**, `arXiv, 2410.10563`, [arxiv](http://arxiv.org/abs/2410.10563v1), [pdf](http://arxiv.org/pdf/2410.10563v1.pdf), cication: [**-1**](None) 

	 *Jiacheng Chen, Tianhao Liang, Sherman Siu, ..., Xiang Yue, Wenhu Chen* · ([tiger-ai-lab.github](https://tiger-ai-lab.github.io/MEGA-Bench/))
- **LiveXiv -- A Multi-Modal Live Benchmark Based on Arxiv Papers Content**, `arXiv, 2410.10783`, [arxiv](http://arxiv.org/abs/2410.10783v2), [pdf](http://arxiv.org/pdf/2410.10783v2.pdf), cication: [**-1**](None) 

	 *Nimrod Shabtay, Felipe Maia Polo, Sivan Doveh, ..., Leonid Karlinsky, Raja Giryes*
- **TemporalBench: Benchmarking Fine-grained Temporal Understanding for 
  Multimodal Video Models**, `arXiv, 2410.10818`, [arxiv](http://arxiv.org/abs/2410.10818v2), [pdf](http://arxiv.org/pdf/2410.10818v2.pdf), cication: [**-1**](None)

	 *Mu Cai, Reuben Tan, Jianrui Zhang, ..., Yong Jae Lee, Jianwei Yang*
- **NaturalBench: Evaluating Vision-Language Models on Natural Adversarial 
  Samples**, `arXiv, 2410.14669`, [arxiv](http://arxiv.org/abs/2410.14669v2), [pdf](http://arxiv.org/pdf/2410.14669v2.pdf), cication: [**-1**](None)

	 *Baiqi Li, Zhiqiu Lin, Wenxuan Peng, ..., Graham Neubig, Deva Ramanan* · ([arxiv](https://arxiv.org/abs/2410.14669)) · ([huggingface](https://huggingface.co/datasets/BaiqiL/NaturalBench)) · ([linzhiqiu.github](https://linzhiqiu.github.io/papers/naturalbench/))
- **WorldCuisines: A Massive-Scale Benchmark for Multilingual and 
  Multicultural Visual Question Answering on Global Cuisines**, `arXiv, 2410.12705`, [arxiv](http://arxiv.org/abs/2410.12705v1), [pdf](http://arxiv.org/pdf/2410.12705v1.pdf), cication: [**-1**](None)

	 *Genta Indra Winata, Frederikus Hudi, Patrick Amadeus Irawan, ..., Alice Oh, Chong-Wah Ngo*
- **HumanEval-V: Evaluating Visual Understanding and Reasoning Abilities of 
  Large Multimodal Models Through Coding Tasks**, `arXiv, 2410.12381`, [arxiv](http://arxiv.org/abs/2410.12381v2), [pdf](http://arxiv.org/pdf/2410.12381v2.pdf), cication: [**-1**](None)

	 *Fengji Zhang, Linquan Wu, Huiyu Bai, ..., Bei Chen, Jacky Keung*

## Efficient

- **HiMix: Reducing Computational Complexity in Large Vision-Language Models**, `arXiv, 2501.10318`, [arxiv](http://arxiv.org/abs/2501.10318v1), [pdf](http://arxiv.org/pdf/2501.10318v1.pdf), cication: [**-1**](None) 

	 *Xuange Zhang, Dengjie Li, Bo Liu, ..., Zheng Zhao, Tongtong Yuan* · ([xuange923.github](https://xuange923.github.io/HiMix))
- [SmolVLM Grows Smaller – Introducing the 250M & 500M Models!](https://huggingface.co/blog/smolervlm)  🤗 
- **LLaVA-Mini: Efficient Image and Video Large Multimodal Models with One 
  Vision Token**, `arXiv, 2501.03895`, [arxiv](http://arxiv.org/abs/2501.03895v1), [pdf](http://arxiv.org/pdf/2501.03895v1.pdf), cication: [**-1**](None) 

	 *Shaolei Zhang, Qingkai Fang, Zhe Yang, ..., Yang Feng*
- **Feather the Throttle: Revisiting Visual Token Pruning for 
  Vision-Language Model Acceleration**, `arXiv, 2412.13180`, [arxiv](http://arxiv.org/abs/2412.13180v1), [pdf](http://arxiv.org/pdf/2412.13180v1.pdf), cication: [**-1**](None) 

	 *Mark Endo, Xiaohan Wang, Serena Yeung-Levy* · ([web.stanford](https://web.stanford.edu/))
- 🌟 [SmolVLM - small yet mighty Vision Language Model](https://huggingface.co/blog/smolvlm)  🤗 

	 · ([𝕏](https://x.com/andi_marafioti/status/1861437314351632662)) · ([huggingface](https://huggingface.co/HuggingFaceTB/SmolVLM-Instruct))
- **Treat Visual Tokens as Text? But Your MLLM Only Needs Fewer Efforts to 
  See**, `arXiv, 2410.06169`, [arxiv](http://arxiv.org/abs/2410.06169v2), [pdf](http://arxiv.org/pdf/2410.06169v2.pdf), cication: [**-1**](None) 

	 *Zeliang Zhang, Phu Pham, Wentian Zhao, ..., Ajinkya Kale, Chenliang Xu* · ([YOPO_MLLM_Pruning](https://github.com/ZhangAIPI/YOPO_MLLM_Pruning/tree/main?tab=readme-ov-file) - ZhangAIPI) ![Star](https://img.shields.io/github/stars/ZhangAIPI/YOPO_MLLM_Pruning.svg?style=social&label=Star)
- 🌟 **BlueLM-V-3B: Algorithm and System Co-Design for Multimodal Large 
  Language Models on Mobile Devices**, `arXiv, 2411.10640`, [arxiv](http://arxiv.org/abs/2411.10640v1), [pdf](http://arxiv.org/pdf/2411.10640v1.pdf), cication: [**-1**](None) 

	 *Xudong Lu, Yinghao Chen, Cheng Chen, ..., Shuai Ren, Hongsheng Li*
- **Inference Optimal VLMs Need Only One Visual Token but Larger Models**, `arXiv, 2411.03312`, [arxiv](http://arxiv.org/abs/2411.03312v1), [pdf](http://arxiv.org/pdf/2411.03312v1.pdf), cication: [**-1**](None) 

	 *Kevin Y. Li, Sachin Goyal, Joao D. Semedo, ..., J. Zico Kolter* · ([llava-token-compression](https://github.com/locuslab/llava-token-compression) - locuslab) ![Star](https://img.shields.io/github/stars/locuslab/llava-token-compression.svg?style=social&label=Star)
- **PyramidDrop: Accelerating Your Large Vision-Language Models via Pyramid 
  Visual Redundancy Reduction**, `arXiv, 2410.17247`, [arxiv](http://arxiv.org/abs/2410.17247v1), [pdf](http://arxiv.org/pdf/2410.17247v1.pdf), cication: [**-1**](None)

	 *Long Xing, Qidong Huang, Xiaoyi Dong, ..., Feng Wu, Dahua Lin*

	 · ([PyramidDrop](https://github.com/Cooperx521/PyramidDrop) - Cooperx521) ![Star](https://img.shields.io/github/stars/Cooperx521/PyramidDrop.svg?style=social&label=Star)

## Generation

- 🌟 [Janus-Pro is a novel autoregressive framework that unifies multimodal understanding and generation.](https://huggingface.co/deepseek-ai/Janus-Pro-7B)  🤗
- **VARGPT: Unified Understanding and Generation in a Visual Autoregressive 
  Multimodal Large Language Model**, `arXiv, 2501.12327`, [arxiv](http://arxiv.org/abs/2501.12327v1), [pdf](http://arxiv.org/pdf/2501.12327v1.pdf), cication: [**-1**](None) 

	 *Xianwei Zhuang, Yuxin Xie, Yufan Deng, ..., Yuguo Yin, Yuexian Zou* · ([vargpt-1.github](https://vargpt-1.github.io/))
- **Flowing from Words to Pixels: A Framework for Cross-Modality Evolution**, `arXiv, 2412.15213`, [arxiv](http://arxiv.org/abs/2412.15213v1), [pdf](http://arxiv.org/pdf/2412.15213v1.pdf), cication: [**-1**](None) 

	 *Qihao Liu, Xi Yin, Alan Yuille, ..., Andrew Brown, Mannat Singh* · ([cross-flow.github](https://cross-flow.github.io/))
- **MetaMorph: Multimodal Understanding and Generation via Instruction 
  Tuning**, `arXiv, 2412.14164`, [arxiv](http://arxiv.org/abs/2412.14164v1), [pdf](http://arxiv.org/pdf/2412.14164v1.pdf), cication: [**-1**](None) 

	 *Shengbang Tong, David Fan, Jiachen Zhu, ..., Saining Xie, Zhuang Liu* · ([𝕏](https://x.com/liuzhuang1234/status/1869576013707084184))
- **LlamaFusion: Adapting Pretrained Language Models for Multimodal 
  Generation**, `arXiv, 2412.15188`, [arxiv](http://arxiv.org/abs/2412.15188v1), [pdf](http://arxiv.org/pdf/2412.15188v1.pdf), cication: [**-1**](None) 

	 *Weijia Shi, Xiaochuang Han, Chunting Zhou, ..., Luke Zettlemoyer, Lili Yu*
- **DiffSensei: Bridging Multi-Modal LLMs and Diffusion Models for 
  Customized Manga Generation**, `arXiv, 2412.07589`, [arxiv](http://arxiv.org/abs/2412.07589v1), [pdf](http://arxiv.org/pdf/2412.07589v1.pdf), cication: [**-1**](None) 

	 *Jianzong Wu, Chao Tang, Jingbo Wang, ..., Xiangtai Li, Yunhai Tong* · ([jianzongwu.github](https://jianzongwu.github.io/projects/diffsensei/)) · ([arxiv](https://arxiv.org/abs/2412.07589)) · ([DiffSensei](https://github.com/jianzongwu/DiffSensei) - jianzongwu) ![Star](https://img.shields.io/github/stars/jianzongwu/DiffSensei.svg?style=social&label=Star)
- **Multimodal Latent Language Modeling with Next-Token Diffusion**, `arXiv, 2412.08635`, [arxiv](http://arxiv.org/abs/2412.08635v1), [pdf](http://arxiv.org/pdf/2412.08635v1.pdf), cication: [**-1**](None) 

	 *Yutao Sun, Hangbo Bao, Wenhui Wang, ..., Jianyong Wang, Furu Wei*
- **EasyRef: Omni-Generalized Group Image Reference for Diffusion Models via 
  Multimodal LLM**, `arXiv, 2412.09618`, [arxiv](http://arxiv.org/abs/2412.09618v1), [pdf](http://arxiv.org/pdf/2412.09618v1.pdf), cication: [**-1**](None) 

	 *Zhuofan Zong, Dongzhi Jiang, Bingqi Ma, ..., Yu Liu, Hongsheng Li* · ([easyref-gen.github](https://easyref-gen.github.io/))
- **TokenFlow: Unified Image Tokenizer for Multimodal Understanding and 
  Generation**, `arXiv, 2412.03069`, [arxiv](http://arxiv.org/abs/2412.03069v1), [pdf](http://arxiv.org/pdf/2412.03069v1.pdf), cication: [**-1**](None) 

	 *Liao Qu, Huichao Zhang, Yiheng Liu, ..., Zehuan Yuan, Xinglong Wu* · ([byteflow-ai.github](https://byteflow-ai.github.io/TokenFlow/)) · ([TokenFlow](https://github.com/ByteFlow-AI/TokenFlow) - ByteFlow-AI) ![Star](https://img.shields.io/github/stars/ByteFlow-AI/TokenFlow.svg?style=social&label=Star)
- **Divot: Diffusion Powers Video Tokenizer for Comprehension and Generation**, `arXiv, 2412.04432`, [arxiv](http://arxiv.org/abs/2412.04432v1), [pdf](http://arxiv.org/pdf/2412.04432v1.pdf), cication: [**-1**](None) 

	 *Yuying Ge, Yizhuo Li, Yixiao Ge, ..., Ying Shan* · ([huggingface](https://huggingface.co/TencentARC/Divot)) · ([Divot](https://github.com/TencentARC/Divot) - TencentARC) ![Star](https://img.shields.io/github/stars/TencentARC/Divot.svg?style=social&label=Star)
- **ILLUME: Illuminating Your LLMs to See, Draw, and Self-Enhance**, `arXiv, 2412.06673`, [arxiv](http://arxiv.org/abs/2412.06673v1), [pdf](http://arxiv.org/pdf/2412.06673v1.pdf), cication: [**-1**](None) 

	 *Chunwei Wang, Guansong Lu, Junwei Yang, ..., Wei Zhang, Hang Xu*
- [**qwen2vl-flux**](https://github.com/erwold/qwen2vl-flux) - erwold ![Star](https://img.shields.io/github/stars/erwold/qwen2vl-flux.svg?style=social&label=Star) 

	 *Unifying Image and Text Guidance for Controllable Image Generation* · ([qwen2vl-flux](https://github.com/erwold/qwen2vl-flux/blob/main/technical-report.pdf) - erwold) ![Star](https://img.shields.io/github/stars/erwold/qwen2vl-flux.svg?style=social&label=Star)
- 🌟 **JanusFlow: Harmonizing Autoregression and Rectified Flow for Unified 
  Multimodal Understanding and Generation**, `arXiv, 2411.07975`, [arxiv](http://arxiv.org/abs/2411.07975v1), [pdf](http://arxiv.org/pdf/2411.07975v1.pdf), cication: [**-1**](None) 

	 *Yiyang Ma, Xingchao Liu, Xiaokang Chen, ..., Jiaying Liu, Chong Ruan* · ([Janus](https://github.com/deepseek-ai/Janus?tab=readme-ov-file) - deepseek-ai) ![Star](https://img.shields.io/github/stars/deepseek-ai/Janus.svg?style=social&label=Star)
- 🌟 **Mixture-of-Transformers: A Sparse and Scalable Architecture for 
  Multi-Modal Foundation Models**, `arXiv, 2411.04996`, [arxiv](http://arxiv.org/abs/2411.04996v1), [pdf](http://arxiv.org/pdf/2411.04996v1.pdf), cication: [**-1**](None) 

	 *Weixin Liang, Lili Yu, Liang Luo, ..., Luke Zettlemoyer, Xi Victoria Lin*
- [VITRON:                    A Unified Pixel-level Vision LLM for                    Understanding, Generating, Segmenting, Editing](https://vitron-llm.github.io/) 

	 · ([Vitron](https://github.com/SkyworkAI/Vitron) - SkyworkAI) ![Star](https://img.shields.io/github/stars/SkyworkAI/Vitron.svg?style=social&label=Star)
- **Janus: Decoupling Visual Encoding for Unified Multimodal Understanding 
  and Generation**, `arXiv, 2410.13848`, [arxiv](http://arxiv.org/abs/2410.13848v1), [pdf](http://arxiv.org/pdf/2410.13848v1.pdf), cication: [**-1**](None)

	 *Chengyue Wu, Xiaokang Chen, Zhiyu Wu, ..., Chong Ruan, Ping Luo*
- **PUMA: Empowering Unified MLLM with Multi-granular Visual Generation**, `arXiv, 2410.13861`, [arxiv](http://arxiv.org/abs/2410.13861v2), [pdf](http://arxiv.org/pdf/2410.13861v2.pdf), cication: [**-1**](None) 

	 *Rongyao Fang, Chengqi Duan, Kun Wang, ..., Hongsheng Li, Xihui Liu*

## Dataset

- 🌟 **2.5 Years in Class: A Multimodal Textbook for Vision-Language 
  Pretraining**, `arXiv, 2501.00958`, [arxiv](http://arxiv.org/abs/2501.00958v2), [pdf](http://arxiv.org/pdf/2501.00958v2.pdf), cication: [**-1**](None) 

	 *Wenqi Zhang, Hang Zhang, Xin Li, ..., Yueting Zhuang, Lidong Bing* · ([multimodal-interleaved-textbook.github](https://multimodal-interleaved-textbook.github.io/)) · ([multimodal_textbook](https://github.com/DAMO-NLP-SG/multimodal_textbook) - DAMO-NLP-SG) ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/multimodal_textbook.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/datasets/DAMO-NLP-SG/multimodal_textbook)) · ([zhuanlan.zhihu](https://zhuanlan.zhihu.com/p/16512014215))
- **MegaPairs: Massive Data Synthesis For Universal Multimodal Retrieval**, `arXiv, 2412.14475`, [arxiv](http://arxiv.org/abs/2412.14475v1), [pdf](http://arxiv.org/pdf/2412.14475v1.pdf), cication: [**-1**](None) 

	 *Junjie Zhou, Zheng Liu, Ze Liu, ..., Defu Lian, Yongping Xiong*
- [MMPR, which includes additional data sources to enhance the data diversity and improves the performance of InternVL2.5](https://huggingface.co/datasets/OpenGVLab/MMPR-v1.1)  🤗 
- 🌟 **LAION-SG: An Enhanced Large-Scale Dataset for Training Complex 
  Image-Text Models with Structural Annotations**, `arXiv, 2412.08580`, [arxiv](http://arxiv.org/abs/2412.08580v1), [pdf](http://arxiv.org/pdf/2412.08580v1.pdf), cication: [**-1**](None) 

	 *Zejian Li, Chenye Meng, Yize Li, ..., Jinxiong Chang, Lingyun Sun* · ([LAION-SG](https://github.com/mengcye/LAION-SG) - mengcye) ![Star](https://img.shields.io/github/stars/mengcye/LAION-SG.svg?style=social&label=Star)
- **Euclid: Supercharging Multimodal LLMs with Synthetic High-Fidelity 
  Visual Descriptions**, `arXiv, 2412.08737`, [arxiv](http://arxiv.org/abs/2412.08737v1), [pdf](http://arxiv.org/pdf/2412.08737v1.pdf), cication: [**-1**](None) 

	 *Jiarui Zhang, Ollie Liu, Tianyu Yu, ..., Jinyi Hu, Willie Neiswanger*
- **BigDocs: An Open and Permissively-Licensed Dataset for Training 
  Multimodal Models on Document and Code Tasks**, `arXiv, 2412.04626`, [arxiv](http://arxiv.org/abs/2412.04626v1), [pdf](http://arxiv.org/pdf/2412.04626v1.pdf), cication: [**-1**](None) 

	 *Juan Rodriguez, Xiangru Jian, Siba Smarak Panigrahi, ..., David Vazquez, Sai Rajeswar* · ([bigdocs.github](https://bigdocs.github.io/))
- **BLIP3-KALE: Knowledge Augmented Large-Scale Dense Captions**, `arXiv, 2411.07461`, [arxiv](http://arxiv.org/abs/2411.07461v1), [pdf](http://arxiv.org/pdf/2411.07461v1.pdf), cication: [**-1**](None) 

	 *Anas Awadalla, Le Xue, Manli Shu, ..., Caiming Xiong, Ran Xu* · ([huggingface](https://huggingface.co/datasets/Salesforce/blip3-kale))
- **HumanVLM: Foundation for Human-Scene Vision-Language Model**, `arXiv, 2411.03034`, [arxiv](http://arxiv.org/abs/2411.03034v1), [pdf](http://arxiv.org/pdf/2411.03034v1.pdf), cication: [**-1**](None) 

	 *Dawei Dai, Xu Long, Li Yutang, ..., Zhang Yuanhui, Shuyin Xia*
- **HourVideo: 1-Hour Video-Language Understanding**, `arXiv, 2411.04998`, [arxiv](http://arxiv.org/abs/2411.04998v1), [pdf](http://arxiv.org/pdf/2411.04998v1.pdf), cication: [**-1**](None) 

	 *Keshigeyan Chandrasegaran, Agrim Gupta, Lea M. Hadzic, ..., Jiajun Wu, Li Fei-Fei* · ([hourvideo.stanford](https://hourvideo.stanford.edu))
- **Infinity-MM: Scaling Multimodal Performance with Large-Scale and 
  High-Quality Instruction Data**, `arXiv, 2410.18558`, [arxiv](http://arxiv.org/abs/2410.18558v1), [pdf](http://arxiv.org/pdf/2410.18558v1.pdf), cication: [**-1**](None)

	 *Shuhao Gu, Jialing Zhang, Siyuan Zhou, ..., Fangxiang Feng, Guang Liu*
- [This dataset is our multimodal, fine-grained, ranking Google Shopping dataset, Marqo-GS-10M](https://huggingface.co/datasets/Marqo/marqo-GS-10M)  🤗 
- **LVD-2M: A Long-take Video Dataset with Temporally Dense Captions**, `arXiv, 2410.10816`, [arxiv](http://arxiv.org/abs/2410.10816v1), [pdf](http://arxiv.org/pdf/2410.10816v1.pdf), cication: [**-1**](None) 

	 *Tianwei Xiong, Yuqing Wang, Daquan Zhou, ..., Jiashi Feng, Xihui Liu*

	 · ([LVD-2M](https://github.com/SilentView/LVD-2M) - SilentView) ![Star](https://img.shields.io/github/stars/SilentView/LVD-2M.svg?style=social&label=Star)
- **Harnessing Webpage UIs for Text-Rich Visual Understanding**, `arXiv, 2410.13824`, [arxiv](http://arxiv.org/abs/2410.13824v2), [pdf](http://arxiv.org/pdf/2410.13824v2.pdf), cication: [**-1**](None) 

	 *Junpeng Liu, Tianyue Ou, Yifan Song, ..., Graham Neubig, Xiang Yue*
- **LVD-2M: A Long-take Video Dataset with Temporally Dense Captions**, `arXiv, 2410.10816`, [arxiv](http://arxiv.org/abs/2410.10816v1), [pdf](http://arxiv.org/pdf/2410.10816v1.pdf), cication: [**-1**](None) 

	 *Tianwei Xiong, Yuqing Wang, Daquan Zhou, ..., Jiashi Feng, Xihui Liu* · ([silentview.github](https://silentview.github.io/LVD-2M/))

## Projects

- 🌟 [**R1-V**](https://github.com/Deep-Agent/R1-V) - Deep-Agent ![Star](https://img.shields.io/github/stars/Deep-Agent/R1-V.svg?style=social&label=Star)

	 *Reinforcing Super Generalization Ability in Vision Language Models with Less Than $3*
- 🌟 [**Qwen2.5-VL**](https://github.com/QwenLM/Qwen2.5-VL) - QwenLM ![Star](https://img.shields.io/github/stars/QwenLM/Qwen2.5-VL.svg?style=social&label=Star)

	 · ([qwenlm.github](https://qwenlm.github.io/blog/qwen2.5-vl/))
- 🌟 [**DeepSeek-VL2**](https://github.com/deepseek-ai/DeepSeek-VL2) - deepseek-ai ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-VL2.svg?style=social&label=Star) 

	 · ([𝕏](https://x.com/deepseek_ai/status/1867545550910017563))
- [Pixtral Large](https://mistral.ai/news/pixtral-large/) 

	 · ([huggingface](https://huggingface.co/mistralai/Pixtral-Large-Instruct-2411))
- [**IPLoc**](https://github.com/SivanDoveh/IPLoc) - SivanDoveh ![Star](https://img.shields.io/github/stars/SivanDoveh/IPLoc.svg?style=social&label=Star) 
- [Vision finetuning is finally in@UnslothAI](https://x.com/danielhanchen/status/1859672815693414853)  𝕏 
- [OmniVision-968M: World's Smallest Vision Language Model](https://nexa.ai/blogs/[object%20Object]) 

	 · ([huggingface](https://huggingface.co/spaces/NexaAIDev/omnivlm-dpo-demo))
- [**neptune**](https://github.com/google-deepmind/neptune) - google-deepmind ![Star](https://img.shields.io/github/stars/google-deepmind/neptune.svg?style=social&label=Star) 

	 · ([storage.googleapis](https://storage.googleapis.com/neptune-paper/neptune-paper.pdf)) · ([research](https://research.google/blog/neptune-the-long-orbit-to-benchmarking-long-video-understanding/?linkId=11668820))

## Products


## Misc

- [Best of 2024 in Vision](https://www.youtube.com/watch?v=76EL7YVAwVo)  :clapper: 
- [SigLIP from timm are interpretable right out-of-the-box](https://x.com/rgilman33/status/1862523581948629413)  𝕏 

	 · ([darkspark](https://darkspark.dev/models/?model=vit_base_patch16_siglip_224-microscope))
- [Understanding Multimodal LLMs](https://magazine.sebastianraschka.com/p/understanding-multimodal-llms) 
- :clapper: [Moondream: how does a tiny vision model slap so hard? — Vikhyat Korrapati](https://www.youtube.com/watch?v=T7sxvrJLJ14) 
- 🌟 [Hannaneh Hajishirzi - OLMo: Accelerating the Science of Language Modeling (COLM)](https://www.youtube.com/watch?v=qMTzor0j418)  :clapper: 