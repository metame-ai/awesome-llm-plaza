# Vision-Language Models

- [Vision-Language Models](#vision-language-models)
  - [Survey](#survey)
  - [Vision-Language Models](#vision-language-models-1)
  - [Image](#image)
  - [Video](#video)
  - [Encoder](#encoder)
  - [Alignment](#alignment)
  - [Evaluation](#evaluation)
  - [Efficient](#efficient)
  - [Generation](#generation)
  - [Dataset](#dataset)
  - [Projects](#projects)
  - [Products](#products)
  - [Misc](#misc)


## Survey

- [short survey of trends in VLMs since Llava 1.0 came out](https://x.com/mervenoyann/status/1851708916729798799)

	 · ([huggingface](https://huggingface.co/collections/merve/mit-talk-31-10-papers-671f6a16e156f77739820c89)) · ([youtube](https://www.youtube.com/watch?v=_TlhKHTgWjY))
- **Towards Unifying Understanding and Generation in the Era of Vision
  Foundation Models: A Survey from the Autoregression Perspective**, `arXiv, 2410.22217`, [arxiv](http://arxiv.org/abs/2410.22217v2), [pdf](http://arxiv.org/pdf/2410.22217v2.pdf), cication: [**-1**](None)

	 *Shenghao Xie, Wenqiang Zu, Mingyang Zhao, ..., Shanghang Zhang, Lei Ma*
- **A Survey of Hallucination in Large Visual Language Models**, `arXiv, 2410.15359`, [arxiv](http://arxiv.org/abs/2410.15359v1), [pdf](http://arxiv.org/pdf/2410.15359v1.pdf), cication: [**-1**](None)

	 *Wei Lan, Wenyi Chen, Qingfeng Chen, ..., Huiyu Zhou, Yi Pan*

## Vision-Language Models

- :star2: 🤗 **CLEAR: Character Unlearning in Textual and Visual Modalities**, `arXiv, 2410.18057`, [arxiv](http://arxiv.org/abs/2410.18057v1), [pdf](http://arxiv.org/pdf/2410.18057v1.pdf), cication: [**-1**](None)

	 *Alexey Dontsov, Dmitrii Korzh, Alexey Zhavoronkin, ..., Ivan Oseledets, Elena Tutubalina* · ([huggingface](https://huggingface.co/datasets/therem/CLEAR)) · ([multimodal_unlearning](https://github.com/somvy/multimodal_unlearning) - somvy) ![Star](https://img.shields.io/github/stars/somvy/multimodal_unlearning.svg?style=social&label=Star)
- **Improve Vision Language Model Chain-of-thought Reasoning**, `arXiv, 2410.16198`, [arxiv](http://arxiv.org/abs/2410.16198v1), [pdf](http://arxiv.org/pdf/2410.16198v1.pdf), cication: [**-1**](None)

	 *Ruohong Zhang, Bowen Zhang, Yanghao Li, ..., Ruoming Pang, Yiming Yang*

	 · ([LLaVA-Reasoner-DPO](https://github.com/RifleZhang/LLaVA-Reasoner-DPO) - RifleZhang) ![Star](https://img.shields.io/github/stars/RifleZhang/LLaVA-Reasoner-DPO.svg?style=social&label=Star)
- **Mitigating Object Hallucination via Concentric Causal Attention**, `arXiv, 2410.15926`, [arxiv](http://arxiv.org/abs/2410.15926v1), [pdf](http://arxiv.org/pdf/2410.15926v1.pdf), cication: [**-1**](None)

	 *Yun Xing, Yiheng Li, Ivan Laptev, ..., Shijian Lu*

	 · ([cca-llava](https://github.com/xing0047/cca-llava) - xing0047) ![Star](https://img.shields.io/github/stars/xing0047/cca-llava.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/abs/2410.15926))

## Image

- 🤗 **Teach Multimodal LLMs to Comprehend Electrocardiographic Images**, `arXiv, 2410.19008`, [arxiv](http://arxiv.org/abs/2410.19008v1), [pdf](http://arxiv.org/pdf/2410.19008v1.pdf), cication: [**-1**](None)

	 *Ruoqi Liu, Yuelin Bai, Xiang Yue, ..., Ping Zhang*

## Video

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

- **LARP: Tokenizing Videos with a Learned Autoregressive Generative Prior**, `arXiv, 2410.21264`, [arxiv](http://arxiv.org/abs/2410.21264v1), [pdf](http://arxiv.org/pdf/2410.21264v1.pdf), cication: [**-1**](None)

	 *Hanyu Wang, Saksham Suri, Yixuan Ren, ..., Hao Chen, Abhinav Shrivastava* · ([hywang66.github](https://hywang66.github.io/larp/))
- **Breaking the Memory Barrier: Near Infinite Batch Size Scaling for
  Contrastive Loss**, `arXiv, 2410.17243`, [arxiv](http://arxiv.org/abs/2410.17243v1), [pdf](http://arxiv.org/pdf/2410.17243v1.pdf), cication: [**-1**](None)

	 *Zesen Cheng, Hang Zhang, Kehan Li, ..., Xin Li, Lidong Bing*

	 · ([Inf-CLIP](https://github.com/DAMO-NLP-SG/Inf-CLIP) - DAMO-NLP-SG) ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/Inf-CLIP.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/pdf/2410.17243))

## Alignment

- **MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large
  Vision-Language Models**, `arXiv, 2410.17637`, [arxiv](http://arxiv.org/abs/2410.17637v1), [pdf](http://arxiv.org/pdf/2410.17637v1.pdf), cication: [**-1**](None)

	 *Ziyu Liu, Yuhang Zang, Xiaoyi Dong, ..., Dahua Lin, Jiaqi Wang*

## Evaluation

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

- **PyramidDrop: Accelerating Your Large Vision-Language Models via Pyramid
  Visual Redundancy Reduction**, `arXiv, 2410.17247`, [arxiv](http://arxiv.org/abs/2410.17247v1), [pdf](http://arxiv.org/pdf/2410.17247v1.pdf), cication: [**-1**](None)

	 *Long Xing, Qidong Huang, Xiaoyi Dong, ..., Feng Wu, Dahua Lin*

	 · ([PyramidDrop](https://github.com/Cooperx521/PyramidDrop) - Cooperx521) ![Star](https://img.shields.io/github/stars/Cooperx521/PyramidDrop.svg?style=social&label=Star)

## Generation

- **Janus: Decoupling Visual Encoding for Unified Multimodal Understanding
  and Generation**, `arXiv, 2410.13848`, [arxiv](http://arxiv.org/abs/2410.13848v1), [pdf](http://arxiv.org/pdf/2410.13848v1.pdf), cication: [**-1**](None)

	 *Chengyue Wu, Xiaokang Chen, Zhiyu Wu, ..., Chong Ruan, Ping Luo*
- **PUMA: Empowering Unified MLLM with Multi-granular Visual Generation**, `arXiv, 2410.13861`, [arxiv](http://arxiv.org/abs/2410.13861v2), [pdf](http://arxiv.org/pdf/2410.13861v2.pdf), cication: [**-1**](None)

	 *Rongyao Fang, Chengqi Duan, Kun Wang, ..., Hongsheng Li, Xihui Liu*

## Dataset

- 🤗 **Infinity-MM: Scaling Multimodal Performance with Large-Scale and
  High-Quality Instruction Data**, `arXiv, 2410.18558`, [arxiv](http://arxiv.org/abs/2410.18558v1), [pdf](http://arxiv.org/pdf/2410.18558v1.pdf), cication: [**-1**](None)

	 *Shuhao Gu, Jialing Zhang, Siyuan Zhou, ..., Fangxiang Feng, Guang Liu*
- 🤗 [This dataset is our multimodal, fine-grained, ranking Google Shopping dataset, Marqo-GS-10M](https://huggingface.co/datasets/Marqo/marqo-GS-10M)
- **LVD-2M: A Long-take Video Dataset with Temporally Dense Captions**, `arXiv, 2410.10816`, [arxiv](http://arxiv.org/abs/2410.10816v1), [pdf](http://arxiv.org/pdf/2410.10816v1.pdf), cication: [**-1**](None)

	 *Tianwei Xiong, Yuqing Wang, Daquan Zhou, ..., Jiashi Feng, Xihui Liu*

	 · ([LVD-2M](https://github.com/SilentView/LVD-2M) - SilentView) ![Star](https://img.shields.io/github/stars/SilentView/LVD-2M.svg?style=social&label=Star)
- **Harnessing Webpage UIs for Text-Rich Visual Understanding**, `arXiv, 2410.13824`, [arxiv](http://arxiv.org/abs/2410.13824v2), [pdf](http://arxiv.org/pdf/2410.13824v2.pdf), cication: [**-1**](None)

	 *Junpeng Liu, Tianyue Ou, Yifan Song, ..., Graham Neubig, Xiang Yue*
- **LVD-2M: A Long-take Video Dataset with Temporally Dense Captions**, `arXiv, 2410.10816`, [arxiv](http://arxiv.org/abs/2410.10816v1), [pdf](http://arxiv.org/pdf/2410.10816v1.pdf), cication: [**-1**](None)

	 *Tianwei Xiong, Yuqing Wang, Daquan Zhou, ..., Jiashi Feng, Xihui Liu* · ([silentview.github](https://silentview.github.io/LVD-2M/))

## Projects


## Products


## Misc

- [Understanding Multimodal LLMs](https://magazine.sebastianraschka.com/p/understanding-multimodal-llms)
- :clapper: [Moondream: how does a tiny vision model slap so hard? — Vikhyat Korrapati](https://www.youtube.com/watch?v=T7sxvrJLJ14)
- :clapper: [Hannaneh Hajishirzi - OLMo: Accelerating the Science of Language Modeling (COLM)](https://www.youtube.com/watch?v=qMTzor0j418)