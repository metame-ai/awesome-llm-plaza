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

- [short survey of trends in VLMs since Llava 1.0 came out](https://x.com/mervenoyann/status/1851708916729798799)  𝕏 

	 · ([huggingface](https://huggingface.co/collections/merve/mit-talk-31-10-papers-671f6a16e156f77739820c89)) · ([youtube](https://www.youtube.com/watch?v=_TlhKHTgWjY))
- **Towards Unifying Understanding and Generation in the Era of Vision 
  Foundation Models: A Survey from the Autoregression Perspective**, `arXiv, 2410.22217`, [arxiv](http://arxiv.org/abs/2410.22217v2), [pdf](http://arxiv.org/pdf/2410.22217v2.pdf), cication: [**-1**](None)

	 *Shenghao Xie, Wenqiang Zu, Mingyang Zhao, ..., Shanghang Zhang, Lei Ma*
- **A Survey of Hallucination in Large Visual Language Models**, `arXiv, 2410.15359`, [arxiv](http://arxiv.org/abs/2410.15359v1), [pdf](http://arxiv.org/pdf/2410.15359v1.pdf), cication: [**-1**](None) 

	 *Wei Lan, Wenyi Chen, Qingfeng Chen, ..., Huiyu Zhou, Yi Pan*

## Vision-Language Models

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

- **Teach Multimodal LLMs to Comprehend Electrocardiographic Images**, `arXiv, 2410.19008`, [arxiv](http://arxiv.org/abs/2410.19008v1), [pdf](http://arxiv.org/pdf/2410.19008v1.pdf), cication: [**-1**](None) 

	 *Ruoqi Liu, Yuelin Bai, Xiang Yue, ..., Ping Zhang*

## Video

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

- **V-DPO: Mitigating Hallucination in Large Vision Language Models via 
  Vision-Guided Direct Preference Optimization**, `arXiv, 2411.02712`, [arxiv](http://arxiv.org/abs/2411.02712v1), [pdf](http://arxiv.org/pdf/2411.02712v1.pdf), cication: [**-1**](None) 

	 *Yuxi Xie, Guanzhen Li, Xiao Xu, ..., Min-Yen Kan* · ([V-DPO](https://github.com/YuxiXie/V-DPO) - YuxiXie) ![Star](https://img.shields.io/github/stars/YuxiXie/V-DPO.svg?style=social&label=Star)
- **MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large 
  Vision-Language Models**, `arXiv, 2410.17637`, [arxiv](http://arxiv.org/abs/2410.17637v1), [pdf](http://arxiv.org/pdf/2410.17637v1.pdf), cication: [**-1**](None)

	 *Ziyu Liu, Yuhang Zang, Xiaoyi Dong, ..., Dahua Lin, Jiaqi Wang*

## Reasoning

- **Vision-Language Models Can Self-Improve Reasoning via Reflection**, `arXiv, 2411.00855`, [arxiv](http://arxiv.org/abs/2411.00855v1), [pdf](http://arxiv.org/pdf/2411.00855v1.pdf), cication: [**-1**](None) 

	 *Kanzhi Cheng, Yantao Li, Fangzhi Xu, ..., Hao Zhou, Yang Liu*

## Evaluation

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

- **Inference Optimal VLMs Need Only One Visual Token but Larger Models**, `arXiv, 2411.03312`, [arxiv](http://arxiv.org/abs/2411.03312v1), [pdf](http://arxiv.org/pdf/2411.03312v1.pdf), cication: [**-1**](None) 

	 *Kevin Y. Li, Sachin Goyal, Joao D. Semedo, ..., J. Zico Kolter* · ([llava-token-compression](https://github.com/locuslab/llava-token-compression) - locuslab) ![Star](https://img.shields.io/github/stars/locuslab/llava-token-compression.svg?style=social&label=Star)
- **PyramidDrop: Accelerating Your Large Vision-Language Models via Pyramid 
  Visual Redundancy Reduction**, `arXiv, 2410.17247`, [arxiv](http://arxiv.org/abs/2410.17247v1), [pdf](http://arxiv.org/pdf/2410.17247v1.pdf), cication: [**-1**](None)

	 *Long Xing, Qidong Huang, Xiaoyi Dong, ..., Feng Wu, Dahua Lin*

	 · ([PyramidDrop](https://github.com/Cooperx521/PyramidDrop) - Cooperx521) ![Star](https://img.shields.io/github/stars/Cooperx521/PyramidDrop.svg?style=social&label=Star)

## Generation

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

- [**neptune**](https://github.com/google-deepmind/neptune) - google-deepmind ![Star](https://img.shields.io/github/stars/google-deepmind/neptune.svg?style=social&label=Star) 

	 · ([storage.googleapis](https://storage.googleapis.com/neptune-paper/neptune-paper.pdf)) · ([research](https://research.google/blog/neptune-the-long-orbit-to-benchmarking-long-video-understanding/?linkId=11668820))

## Products


## Misc

- [Understanding Multimodal LLMs](https://magazine.sebastianraschka.com/p/understanding-multimodal-llms) 
- :clapper: [Moondream: how does a tiny vision model slap so hard? — Vikhyat Korrapati](https://www.youtube.com/watch?v=T7sxvrJLJ14) 
- :clapper: [Hannaneh Hajishirzi - OLMo: Accelerating the Science of Language Modeling (COLM)](https://www.youtube.com/watch?v=qMTzor0j418) 