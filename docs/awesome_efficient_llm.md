# Awesome efficient llm

- [Awesome efficient llm](#awesome-efficient-llm)
	- [Efficient finetuning](#efficient-finetuning)
		- [Adapter](#adapter)
	- [Quantization](#quantization)
		- [Survey](#survey)
		- [Papers](#papers)
		- [Projects](#projects)
		- [Other](#other)
	- [Distillation](#distillation)
	- [Pruning](#pruning)
	- [Efficient Inference](#efficient-inference)
		- [Other](#other-1)
	- [Mobile](#mobile)
	- [Toolkits](#toolkits)
	- [Efficient transformer](#efficient-transformer)

## Survey
- **Efficient Large Language Models: A Survey**, `arXiv, 2312.03863`, [arxiv](http://arxiv.org/abs/2312.03863v1), [pdf](http://arxiv.org/pdf/2312.03863v1.pdf), cication: [**-1**](None)

	 *Zhongwei Wan, Xin Wang, Che Liu, Samiul Alam, Yu Zheng, Zhongnan Qu, Shen Yan, Yi Zhu, Quanlu Zhang, Mosharaf Chowdhury* · ([Efficient-LLMs-Survey](https://github.com/AIoT-MLSys-Lab/Efficient-LLMs-Survey) - AIoT-MLSys-Lab) ![Star](https://img.shields.io/github/stars/AIoT-MLSys-Lab/Efficient-LLMs-Survey.svg?style=social&label=Star)
- **The Efficiency Spectrum of Large Language Models: An Algorithmic Survey**, `arXiv, 2312.00678`, [arxiv](http://arxiv.org/abs/2312.00678v1), [pdf](http://arxiv.org/pdf/2312.00678v1.pdf), cication: [**-1**](None)

	 *Tianyu Ding, Tianyi Chen, Haidong Zhu, Jiachen Jiang, Yiqi Zhong, Jinxin Zhou, Guangzhi Wang, Zhihui Zhu, Ilya Zharkov, Luming Liang*

## Efficient finetuning
- [Practical Tips for Finetuning LLMs Using LoRA (Low-Rank Adaptation)](https://magazine.sebastianraschka.com/p/practical-tips-for-finetuning-llms?continueFlag=0c2e38ff6893fba31f1492d815bf928b)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-12-04-14))
- **MultiLoRA: Democratizing LoRA for Better Multi-Task Learning**, `arXiv, 2311.11501`, [arxiv](http://arxiv.org/abs/2311.11501v1), [pdf](http://arxiv.org/pdf/2311.11501v1.pdf), cication: [**-1**](None)

	 *Yiming Wang, Yu Lin, Xiaodong Zeng, Guannan Zhang*
- **Tied-Lora: Enhacing parameter efficiency of LoRA with weight tying**, `arXiv, 2311.09578`, [arxiv](http://arxiv.org/abs/2311.09578v1), [pdf](http://arxiv.org/pdf/2311.09578v1.pdf), cication: [**-1**](None)

	 *Adithya Renduchintala, Tugrul Konuk, Oleksii Kuchaiev*
- **SiRA: Sparse Mixture of Low Rank Adaptation**, `arXiv, 2311.09179`, [arxiv](http://arxiv.org/abs/2311.09179v1), [pdf](http://arxiv.org/pdf/2311.09179v1.pdf), cication: [**-1**](None)

	 *Yun Zhu, Nevan Wichers, Chu-Cheng Lin, Xinyi Wang, Tianlong Chen, Lei Shu, Han Lu, Canoee Liu, Liangchen Luo, Jindong Chen*
- **Parameter-Efficient Orthogonal Finetuning via Butterfly Factorization**, `arXiv, 2311.06243`, [arxiv](http://arxiv.org/abs/2311.06243v1), [pdf](http://arxiv.org/pdf/2311.06243v1.pdf), cication: [**-1**](None)

	 *Weiyang Liu, Zeju Qiu, Yao Feng, Yuliang Xiu, Yuxuan Xue, Longhui Yu, Haiwen Feng, Zhen Liu, Juyeon Heo, Songyou Peng* · ([boft.wyliu](https://boft.wyliu.com/))
- **Punica: Multi-Tenant LoRA Serving**, `arXiv, 2310.18547`, [arxiv](http://arxiv.org/abs/2310.18547v1), [pdf](http://arxiv.org/pdf/2310.18547v1.pdf), cication: [**-1**](None)

	 *Lequn Chen, Zihao Ye, Yongji Wu, Danyang Zhuo, Luis Ceze, Arvind Krishnamurthy* · ([punica](https://github.com/punica-ai/punica#punica-serving-multiple-lora-finetuned-llm-as-one) - punica-ai) ![Star](https://img.shields.io/github/stars/punica-ai/punica.svg?style=social&label=Star)
- **S-LoRA: Serving Thousands of Concurrent LoRA Adapters**, `arXiv, 2311.03285`, [arxiv](http://arxiv.org/abs/2311.03285v2), [pdf](http://arxiv.org/pdf/2311.03285v2.pdf), cication: [**-1**](None)

	 *Ying Sheng, Shiyi Cao, Dacheng Li, Coleman Hooper, Nicholas Lee, Shuo Yang, Christopher Chou, Banghua Zhu, Lianmin Zheng, Kurt Keutzer* · ([s-lora](https://github.com/s-lora/s-lora) - s-lora) ![Star](https://img.shields.io/github/stars/s-lora/s-lora.svg?style=social&label=Star)
- **LoRAShear: Efficient Large Language Model Structured Pruning and
  Knowledge Recovery**, `arXiv, 2310.18356`, [arxiv](http://arxiv.org/abs/2310.18356v2), [pdf](http://arxiv.org/pdf/2310.18356v2.pdf), cication: [**-1**](None)

	 *Tianyi Chen, Tianyu Ding, Badal Yadav, Ilya Zharkov, Luming Liang*
- **VeRA: Vector-based Random Matrix Adaptation**, `arXiv, 2310.11454`, [arxiv](http://arxiv.org/abs/2310.11454v1), [pdf](http://arxiv.org/pdf/2310.11454v1.pdf), cication: [**-1**](None)

	 *Dawid Jan Kopiczko, Tijmen Blankevoort, Yuki Markus Asano* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247620489&idx=4&sn=6e857b766797438f18cf9c70f1978f9e))
- **LoftQ: LoRA-Fine-Tuning-Aware Quantization for Large Language Models**, `arXiv, 2310.08659`, [arxiv](http://arxiv.org/abs/2310.08659v3), [pdf](http://arxiv.org/pdf/2310.08659v3.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=13848184224730711263&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yixiao Li, Yifan Yu, Chen Liang, Pengcheng He, Nikos Karampatziakis, Weizhu Chen, Tuo Zhao*
- **QA-LoRA: Quantization-Aware Low-Rank Adaptation of Large Language Models**, `arXiv, 2309.14717`, [arxiv](http://arxiv.org/abs/2309.14717v2), [pdf](http://arxiv.org/pdf/2309.14717v2.pdf), cication: [**-1**](None)

	 *Yuhui Xu, Lingxi Xie, Xiaotao Gu, Xin Chen, Heng Chang, Hengheng Zhang, Zhengsu Chen, Xiaopeng Zhang, Qi Tian* · ([qa-lora](https://github.com/yuhuixu1993/qa-lora) - yuhuixu1993) ![Star](https://img.shields.io/github/stars/yuhuixu1993/qa-lora.svg?style=social&label=Star)
- **LongLoRA: Efficient Fine-tuning of Long-Context Large Language Models**, `arXiv, 2309.12307`, [arxiv](http://arxiv.org/abs/2309.12307v1), [pdf](http://arxiv.org/pdf/2309.12307v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=15175040643590476650&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yukang Chen, Shengju Qian, Haotian Tang, Xin Lai, Zhijian Liu, Song Han, Jiaya Jia* · ([LongLoRA](https://github.com/dvlab-research/LongLoRA) - dvlab-research) ![Star](https://img.shields.io/github/stars/dvlab-research/LongLoRA.svg?style=social&label=Star)
- **LoraHub: Efficient Cross-Task Generalization via Dynamic LoRA
  Composition**, `arXiv, 2307.13269`, [arxiv](http://arxiv.org/abs/2307.13269v1), [pdf](http://arxiv.org/pdf/2307.13269v1.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=9929120063144632612&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chengsong Huang, Qian Liu, Bill Yuchen Lin, Tianyu Pang, Chao Du, Min Lin*
- **Stack More Layers Differently: High-Rank Training Through Low-Rank
  Updates**, `arXiv, 2307.05695`, [arxiv](http://arxiv.org/abs/2307.05695v3), [pdf](http://arxiv.org/pdf/2307.05695v3.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=16347103820657222273&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Vladislav Lialin, Namrata Shivagunde, Sherin Muckatira, Anna Rumshisky* · ([peft_pretraining](https://github.com/guitaricet/peft_pretraining) - guitaricet) ![Star](https://img.shields.io/github/stars/guitaricet/peft_pretraining.svg?style=social&label=Star)
- [**LLaMA-Efficient-Tuning**](https://github.com/hiyouga/LLaMA-Efficient-Tuning) - hiyouga ![Star](https://img.shields.io/github/stars/hiyouga/LLaMA-Efficient-Tuning.svg?style=social&label=Star)

	 *Fine-tuning LLaMA with PEFT (PT+SFT+RLHF with QLoRA)*
- **InRank: Incremental Low-Rank Learning**, `arXiv, 2306.11250`, [arxiv](http://arxiv.org/abs/2306.11250v1), [pdf](http://arxiv.org/pdf/2306.11250v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=11715677115240227852&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jiawei Zhao, Yifei Zhang, Beidi Chen, Florian Schäfer, Anima Anandkumar* · ([inrank](https://github.com/jiaweizzhao/inrank) - jiaweizzhao) ![Star](https://img.shields.io/github/stars/jiaweizzhao/inrank.svg?style=social&label=Star)
- **One-for-All: Generalized LoRA for Parameter-Efficient Fine-tuning**, `arXiv,  2306.07967`, [arxiv](http://arxiv.org/abs/2306.07967v2), [pdf](http://arxiv.org/pdf/2306.07967v2.pdf), cication: [**-1**](None)

	 *Arnav Chavan, Zhuang Liu, Deepak Gupta, Eric Xing, Zhiqiang Shen* · ([ViT-Slim](https://github.com/Arnav0400/ViT-Slim/tree/master/GLoRA) - Arnav0400) ![Star](https://img.shields.io/github/stars/Arnav0400/ViT-Slim.svg?style=social&label=Star)
- **Full Parameter Fine-tuning for Large Language Models with Limited
  Resources**, `arXiv,  2306.09782`, [arxiv](http://arxiv.org/abs/2306.09782v1), [pdf](http://arxiv.org/pdf/2306.09782v1.pdf), cication: [**-1**](None)

	 *Kai Lv, Yuqing Yang, Tengxiao Liu, Qinghui Gao, Qipeng Guo, Xipeng Qiu* · ([LOMO](https://github.com/OpenLMLab/LOMO) - OpenLMLab) ![Star](https://img.shields.io/github/stars/OpenLMLab/LOMO.svg?style=social&label=Star)
- **PockEngine: Sparse and Efficient Fine-tuning in a Pocket**, `arXiv, 2310.17752`, [arxiv](http://arxiv.org/abs/2310.17752v1), [pdf](http://arxiv.org/pdf/2310.17752v1.pdf), cication: [**-1**](None)

	 *Ligeng Zhu, Lanxiang Hu, Ji Lin, Wei-Chen Wang, Wei-Ming Chen, Chuang Gan, Song Han*
- [AI and Memory Wall. (This blogpost has been written in… | by Amir Gholami | riselab | Medium](https://medium.com/riselab/ai-and-memory-wall-2cb4265cb0b8)

### Adapter
- **Adapters: A Unified Library for Parameter-Efficient and Modular Transfer
  Learning**, `arXiv, 2311.11077`, [arxiv](http://arxiv.org/abs/2311.11077v1), [pdf](http://arxiv.org/pdf/2311.11077v1.pdf), cication: [**-1**](None)

	 *Clifton Poth, Hannah Sterz, Indraneil Paul, Sukannya Purkayastha, Leon Engländer, Timo Imhof, Ivan Vulić, Sebastian Ruder, Iryna Gurevych, Jonas Pfeiffer* · ([adapterhub](https://adapterhub.ml/adapters))
- **Cheap and Quick: Efficient Vision-Language Instruction Tuning for Large
  Language Models**, `arXiv, 2305.15023`, [arxiv](http://arxiv.org/abs/2305.15023v3), [pdf](http://arxiv.org/pdf/2305.15023v3.pdf), cication: [**18**](https://scholar.google.com/scholar?cites=4819532122205705554&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Gen Luo, Yiyi Zhou, Tianhe Ren, Shengxin Chen, Xiaoshuai Sun, Rongrong Ji* · ([LaVIN](https://github.com/luogen1996/LaVIN) - luogen1996) ![Star](https://img.shields.io/github/stars/luogen1996/LaVIN.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247522540&idx=4&sn=2e2808a7a10cd216a8f2db6135a15a0b))
- **LLaMA-Adapter V2: Parameter-Efficient Visual Instruction Model**, `arXiv, 2304.15010`, [arxiv](http://arxiv.org/abs/2304.15010v1), [pdf](http://arxiv.org/pdf/2304.15010v1.pdf), cication: [**82**](https://scholar.google.com/scholar?cites=13538765489639770783&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Peng Gao, Jiaming Han, Renrui Zhang, Ziyi Lin, Shijie Geng, Aojun Zhou, Wei Zhang, Pan Lu, Conghui He, Xiangyu Yue* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652345558&idx=3&sn=2a4d204397fe364a05ce5a35bb93d6ce))


## Quantization
### Survey
- **A Survey on Model Compression for Large Language Models**, `arXiv, 2308.07633`, [arxiv](http://arxiv.org/abs/2308.07633v3), [pdf](http://arxiv.org/pdf/2308.07633v3.pdf), cication: [**-1**](None)

	 *Xunyu Zhu, Jian Li, Yong Liu, Can Ma, Weiping Wang* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-26-5))

### Papers
- **LQ-LoRA: Low-rank Plus Quantized Matrix Decomposition for Efficient
  Language Model Finetuning**, `arXiv, 2311.12023`, [arxiv](http://arxiv.org/abs/2311.12023v1), [pdf](http://arxiv.org/pdf/2311.12023v1.pdf), cication: [**-1**](None)

	 *Han Guo, Philip Greengard, Eric P. Xing, Yoon Kim* · ([lq-lora](https://github.com/hanguo97/lq-lora) - hanguo97) ![Star](https://img.shields.io/github/stars/hanguo97/lq-lora.svg?style=social&label=Star)
- **QUIK: Towards End-to-End 4-Bit Inference on Generative Large Language
  Models**, `arXiv, 2310.09259`, [arxiv](http://arxiv.org/abs/2310.09259v2), [pdf](http://arxiv.org/pdf/2310.09259v2.pdf), cication: [**-1**](None)

	 *Saleh Ashkboos, Ilia Markov, Elias Frantar, Tingxuan Zhong, Xincheng Wang, Jie Ren, Torsten Hoefler, Dan Alistarh* · ([quik](https://github.com/ist-daslab/quik) - ist-daslab) ![Star](https://img.shields.io/github/stars/ist-daslab/quik.svg?style=social&label=Star)
- **Atom: Low-bit Quantization for Efficient and Accurate LLM Serving**, `arXiv, 2310.19102`, [arxiv](http://arxiv.org/abs/2310.19102v2), [pdf](http://arxiv.org/pdf/2310.19102v2.pdf), cication: [**-1**](None)

	 *Yilong Zhao, Chien-Yu Lin, Kan Zhu, Zihao Ye, Lequn Chen, Size Zheng, Luis Ceze, Arvind Krishnamurthy, Tianqi Chen, Baris Kasikci*
- **FP8-LM: Training FP8 Large Language Models**, `arXiv, 2310.18313`, [arxiv](http://arxiv.org/abs/2310.18313v1), [pdf](http://arxiv.org/pdf/2310.18313v1.pdf), cication: [**-1**](None)

	 *Houwen Peng, Kan Wu, Yixuan Wei, Guoshuai Zhao, Yuxiang Yang, Ze Liu, Yifan Xiong, Ziyue Yang, Bolin Ni, Jingcheng Hu*
- **LLM-FP4: 4-Bit Floating-Point Quantized Transformers**, `arXiv, 2310.16836`, [arxiv](http://arxiv.org/abs/2310.16836v1), [pdf](http://arxiv.org/pdf/2310.16836v1.pdf), cication: [**-1**](None)

	 *Shih-yang Liu, Zechun Liu, Xijie Huang, Pingcheng Dong, Kwang-Ting Cheng*
- **QMoE: Practical Sub-1-Bit Compression of Trillion-Parameter Models**, `arXiv, 2310.16795`, [arxiv](http://arxiv.org/abs/2310.16795v1), [pdf](http://arxiv.org/pdf/2310.16795v1.pdf), cication: [**-1**](None)

	 *Elias Frantar, Dan Alistarh* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247622372&idx=2&sn=68489c38e6d66f18049df007cd4eb635))
- **BitNet: Scaling 1-bit Transformers for Large Language Models**, `arXiv, 2310.11453`, [arxiv](http://arxiv.org/abs/2310.11453v1), [pdf](http://arxiv.org/pdf/2310.11453v1.pdf), cication: [**-1**](None)

	 *Hongyu Wang, Shuming Ma, Li Dong, Shaohan Huang, Huaijie Wang, Lingxiao Ma, Fan Yang, Ruiping Wang, Yi Wu, Furu Wei*
- **TEQ: Trainable Equivalent Transformation for Quantization of LLMs**, `arXiv, 2310.10944`, [arxiv](http://arxiv.org/abs/2310.10944v1), [pdf](http://arxiv.org/pdf/2310.10944v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=13502474972419396143&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wenhua Cheng, Yiyang Cai, Kaokao Lv, Haihao Shen*
- **Efficient Post-training Quantization with FP8 Formats**, `arXiv, 2309.14592`, [arxiv](http://arxiv.org/abs/2309.14592v1), [pdf](http://arxiv.org/pdf/2309.14592v1.pdf), cication: [**-1**](None)

	 *Haihao Shen, Naveen Mellempudi, Xin He, Qun Gao, Chang Wang, Mengni Wang* · ([neural-compressor](https://github.com/intel/neural-compressor) - intel) ![Star](https://img.shields.io/github/stars/intel/neural-compressor.svg?style=social&label=Star)
- **QA-LoRA: Quantization-Aware Low-Rank Adaptation of Large Language Models**, `arXiv, 2309.14717`, [arxiv](http://arxiv.org/abs/2309.14717v2), [pdf](http://arxiv.org/pdf/2309.14717v2.pdf), cication: [**-1**](None)

	 *Yuhui Xu, Lingxi Xie, Xiaotao Gu, Xin Chen, Heng Chang, Hengheng Zhang, Zhengsu Chen, Xiaopeng Zhang, Qi Tian*
- **Optimize Weight Rounding via Signed Gradient Descent for the
  Quantization of LLMs**, `arXiv, 2309.05516`, [arxiv](http://arxiv.org/abs/2309.05516v2), [pdf](http://arxiv.org/pdf/2309.05516v2.pdf), cication: [**-1**](None)

	 *Wenhua Cheng, Weiwei Zhang, Haihao Shen, Yiyang Cai, Xin He, Kaokao Lv*
- **Memory Efficient Optimizers with 4-bit States**, `arXiv, 2309.01507`, [arxiv](http://arxiv.org/abs/2309.01507v3), [pdf](http://arxiv.org/pdf/2309.01507v3.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=4080914880108526887&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Bingrui Li, Jianfei Chen, Jun Zhu* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-08-5))
- **OmniQuant: Omnidirectionally Calibrated Quantization for Large Language
  Models**, `arXiv, 2308.13137`, [arxiv](http://arxiv.org/abs/2308.13137v2), [pdf](http://arxiv.org/pdf/2308.13137v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=17294293173749479580&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wenqi Shao, Mengzhao Chen, Zhaoyang Zhang, Peng Xu, Lirui Zhao, Zhiqian Li, Kaipeng Zhang, Peng Gao, Yu Qiao, Ping Luo* · ([OmniQuant](https://github.com/OpenGVLab/OmniQuant) - OpenGVLab) ![Star](https://img.shields.io/github/stars/OpenGVLab/OmniQuant.svg?style=social&label=Star)

- **FLIQS: One-Shot Mixed-Precision Floating-Point and Integer Quantization
  Search**, `arXiv, 2308.03290`, [arxiv](http://arxiv.org/abs/2308.03290v1), [pdf](http://arxiv.org/pdf/2308.03290v1.pdf), cication: [**-1**](None)

	 *Jordan Dotzel, Gang Wu, Andrew Li, Muhammad Umar, Yun Ni, Mohamed S. Abdelfattah, Zhiru Zhang, Liqun Cheng, Martin G. Dixon, Norman P. Jouppi*
- **QuIP: 2-Bit Quantization of Large Language Models With Guarantees**, `arXiv, 2307.13304`, [arxiv](http://arxiv.org/abs/2307.13304v1), [pdf](http://arxiv.org/pdf/2307.13304v1.pdf), cication: [**-1**](None)

	 *Jerry Chee, Yaohui Cai, Volodymyr Kuleshov, Christopher De Sa* · ([quip](https://github.com/jerry-chee/quip) - jerry-chee) ![Star](https://img.shields.io/github/stars/jerry-chee/quip.svg?style=social&label=Star)

- **Quantizable Transformers: Removing Outliers by Helping Attention Heads
  Do Nothing**, `arXiv, 2306.12929`, [arxiv](http://arxiv.org/abs/2306.12929v2), [pdf](http://arxiv.org/pdf/2306.12929v2.pdf), cication: [**-1**](None)

	 *Yelysei Bondarenko, Markus Nagel, Tijmen Blankevoort*
- **Training Transformers with 4-bit Integers**, `arXiv,  2306.11987`, [arxiv](http://arxiv.org/abs/2306.11987v2), [pdf](http://arxiv.org/pdf/2306.11987v2.pdf), cication: [**-1**](None)

	 *Haocheng Xi, Changhao Li, Jianfei Chen, Jun Zhu* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-30-7))
- **SpQR: A Sparse-Quantized Representation for Near-Lossless LLM Weight
  Compression**, `arXiv, 2306.03078`, [arxiv](http://arxiv.org/abs/2306.03078v1), [pdf](http://arxiv.org/pdf/2306.03078v1.pdf), cication: [**-1**](None)

	 *Tim Dettmers, Ruslan Svirschevski, Vage Egiazarian, Denis Kuznedelev, Elias Frantar, Saleh Ashkboos, Alexander Borzunov, Torsten Hoefler, Dan Alistarh*
- **SpQR: A Sparse-Quantized Representation for Near-Lossless LLM Weight
  Compression**, `arXiv, 2306.03078`, [arxiv](http://arxiv.org/abs/2306.03078v1), [pdf](http://arxiv.org/pdf/2306.03078v1.pdf), cication: [**-1**](None)

	 *Tim Dettmers, Ruslan Svirschevski, Vage Egiazarian, Denis Kuznedelev, Elias Frantar, Saleh Ashkboos, Alexander Borzunov, Torsten Hoefler, Dan Alistarh* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-07-5))

### Projects
- [**exllamav2**](https://github.com/turboderp/exllamav2) - turboderp ![Star](https://img.shields.io/github/stars/turboderp/exllamav2.svg?style=social&label=Star)

	 *A fast inference library for running LLMs locally on modern consumer-class GPUs* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247617952&idx=2&sn=e643da17456e72bd9e7c0289559d620b))
- [**PB-LLM**](https://github.com/hahnyuan/PB-LLM) - hahnyuan ![Star](https://img.shields.io/github/stars/hahnyuan/PB-LLM.svg?style=social&label=Star)

	 *PB-LLM: Partially Binarized Large Language Models*
- [**AttentionIsOFFByOne**](https://github.com/kyegomez/AttentionIsOFFByOne) - kyegomez ![Star](https://img.shields.io/github/stars/kyegomez/AttentionIsOFFByOne.svg?style=social&label=Star)

	 *Implementation of "Attention Is Off By One" by Evan Miller* · ([evanmiller](https://www.evanmiller.org/attention-is-off-by-one.html?continueFlag=5d0e431f4edf1d8cccea47871e82fbc4)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-25))
- [**llama.cpp**](https://github.com/ggerganov/llama.cpp) - ggerganov ![Star](https://img.shields.io/github/stars/ggerganov/llama.cpp.svg?style=social&label=Star)

	 *Port of Facebook's LLaMA model in C/C++* · ([finbarr](https://finbarr.ca/how-is-llama-cpp-possible/))
- [**llama2-webui**](https://github.com/liltom-eth/llama2-webui) - liltom-eth ![Star](https://img.shields.io/github/stars/liltom-eth/llama2-webui.svg?style=social&label=Star)

	 *Run Llama 2 locally with gradio UI on GPU or CPU from anywhere (Linux/Windows/Mac). Supporting Llama-2-7B/13B/70B with 8-bit, 4-bit. Supporting GPU inference (6 GB VRAM) and CPU inference.*
- [**neural-compressor**](https://github.com/intel/neural-compressor) - intel ![Star](https://img.shields.io/github/stars/intel/neural-compressor.svg?style=social&label=Star)

	 *Provide unified APIs for SOTA model compression techniques, such as low precision (INT8/INT4/FP4/NF4) quantization, sparsity, pruning, and knowledge distillation on mainstream AI frameworks such as TensorFlow, PyTorch, and ONNX Runtime.* · ([neural-compressor](https://github.com/intel/neural-compressor/blob/master/docs/source/smooth_quant.md) - intel) ![Star](https://img.shields.io/github/stars/intel/neural-compressor.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652346855&idx=1&sn=7310cbdc26601f49614e67266426da5b))
- [**exllama**](https://github.com/turboderp/exllama) - turboderp ![Star](https://img.shields.io/github/stars/turboderp/exllama.svg?style=social&label=Star)

	 *A more memory-efficient rewrite of the HF transformers implementation of Llama for use with quantized weights.*
- [**squeezellm**](https://github.com/squeezeailab/squeezellm) - squeezeailab ![Star](https://img.shields.io/github/stars/squeezeailab/squeezellm.svg?style=social&label=Star)

	 *SqueezeLLM: Dense-and-Sparse Quantization*

### Other
- [Overview of natively supported quantization schemes in 🤗 Transformers](https://huggingface.co/blog/overview-quantization-transformers)
- [Making LLMs lighter with AutoGPTQ and transformers](https://huggingface.co/blog/gptq-integration)
- [TheBloke (Tom Jobbins)](https://huggingface.co/TheBloke)
- [Quantization](https://huggingface.co/docs/accelerate/usage_guides/quantization)

## Distillation
- **Initializing Models with Larger Ones**, `arXiv, 2311.18823`, [arxiv](http://arxiv.org/abs/2311.18823v1), [pdf](http://arxiv.org/pdf/2311.18823v1.pdf), cication: [**-1**](None)

	 *Zhiqiu Xu, Yanjie Chen, Kirill Vishniakov, Yida Yin, Zhiqiang Shen, Trevor Darrell, Lingjie Liu, Zhuang Liu* · ([weight-selection](https://github.com/oscarxzq/weight-selection) - oscarxzq) ![Star](https://img.shields.io/github/stars/oscarxzq/weight-selection.svg?style=social&label=Star)
- **Tailoring Self-Rationalizers with Multi-Reward Distillation**, `arXiv, 2311.02805`, [arxiv](http://arxiv.org/abs/2311.02805v1), [pdf](http://arxiv.org/pdf/2311.02805v1.pdf), cication: [**-1**](None)

	 *Sahana Ramnath, Brihi Joshi, Skyler Hallinan, Ximing Lu, Liunian Harold Li, Aaron Chan, Jack Hessel, Yejin Choi, Xiang Ren*
- **Co-training and Co-distillation for Quality Improvement and Compression
  of Language Models**, `arXiv, 2311.02849`, [arxiv](http://arxiv.org/abs/2311.02849v2), [pdf](http://arxiv.org/pdf/2311.02849v2.pdf), cication: [**-1**](None)

	 *Hayeon Lee, Rui Hou, Jongpil Kim, Davis Liang, Hongbo Zhang, Sung Ju Hwang, Alexander Min*
- **TeacherLM: Teaching to Fish Rather Than Giving the Fish, Language
  Modeling Likewise**, `arXiv, 2310.19019`, [arxiv](http://arxiv.org/abs/2310.19019v2), [pdf](http://arxiv.org/pdf/2310.19019v2.pdf), cication: [**-1**](None)

	 *Nan He, Hanyu Lai, Chenyang Zhao, Zirui Cheng, Junting Pan, Ruoyu Qin, Ruofan Lu, Rui Lu, Yunchen Zhang, Gangming Zhao*
- **Farzi Data: Autoregressive Data Distillation**, `arXiv, 2310.09983`, [arxiv](http://arxiv.org/abs/2310.09983v1), [pdf](http://arxiv.org/pdf/2310.09983v1.pdf), cication: [**-1**](None)

	 *Noveen Sachdeva, Zexue He, Wang-Cheng Kang, Jianmo Ni, Derek Zhiyuan Cheng, Julian McAuley*
- **Distilling Step-by-Step! Outperforming Larger Language Models with Less
  Training Data and Smaller Model Sizes**, `arXiv, 2305.02301`, [arxiv](http://arxiv.org/abs/2305.02301v2), [pdf](http://arxiv.org/pdf/2305.02301v2.pdf), cication: [**48**](https://scholar.google.com/scholar?cites=1016106613020195157&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Cheng-Yu Hsieh, Chun-Liang Li, Chih-Kuan Yeh, Hootan Nakhost, Yasuhisa Fujii, Alexander Ratner, Ranjay Krishna, Chen-Yu Lee, Tomas Pfister*
- **Composable Function-preserving Expansions for Transformer Architectures**, `arXiv, 2308.06103`, [arxiv](http://arxiv.org/abs/2308.06103v1), [pdf](http://arxiv.org/pdf/2308.06103v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=10053823054939078023&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Andrea Gesmundo, Kaitlin Maile*
- **UniversalNER: Targeted Distillation from Large Language Models for Open
  Named Entity Recognition**, `arXiv, 2308.03279`, [arxiv](http://arxiv.org/abs/2308.03279v1), [pdf](http://arxiv.org/pdf/2308.03279v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=18239610379074827059&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wenxuan Zhou, Sheng Zhang, Yu Gu, Muhao Chen, Hoifung Poon*
- **Generalized Knowledge Distillation for Auto-regressive Language Models**, `arXiv,  2306.13649`, [arxiv](http://arxiv.org/abs/2306.13649v2), [pdf](http://arxiv.org/pdf/2306.13649v2.pdf), cication: [**-1**](None)

	 *Rishabh Agarwal, Nino Vieillard, Yongchao Zhou, Piotr Stanczyk, Sabela Ramos, Matthieu Geist, Olivier Bachem*
- **Knowledge Distillation of Large Language Models**, `arXiv,  2306.08543`, [arxiv](http://arxiv.org/abs/2306.08543v1), [pdf](http://arxiv.org/pdf/2306.08543v1.pdf), cication: [**-1**](None)

	 *Yuxian Gu, Li Dong, Furu Wei, Minlie Huang*

## Pruning
- **Sheared LLaMA: Accelerating Language Model Pre-training via Structured
  Pruning**, `arXiv, 2310.06694`, [arxiv](http://arxiv.org/abs/2310.06694v1), [pdf](http://arxiv.org/pdf/2310.06694v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=9713425200262995197&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Mengzhou Xia, Tianyu Gao, Zhiyuan Zeng, Danqi Chen* · ([qbitai](https://www.qbitai.com/2023/10/89367.html)) · ([xiamengzhou.github](https://xiamengzhou.github.io/sheared-llama/)) · ([llm-shearing](https://github.com/princeton-nlp/llm-shearing) - princeton-nlp) ![Star](https://img.shields.io/github/stars/princeton-nlp/llm-shearing.svg?style=social&label=Star)
- [**wanda**](https://github.com/locuslab/wanda) - locuslab ![Star](https://img.shields.io/github/stars/locuslab/wanda.svg?style=social&label=Star)

	 *A simple and effective LLM pruning approach.*

## Efficient Inference
- [**vllm**](https://github.com/vllm-project/vllm) - vllm-project ![Star](https://img.shields.io/github/stars/vllm-project/vllm.svg?style=social&label=Star)

	 *A high-throughput and memory-efficient inference and serving engine for LLMs*
- **SparQ Attention: Bandwidth-Efficient LLM Inference**, `arXiv, 2312.04985`, [arxiv](http://arxiv.org/abs/2312.04985v1), [pdf](http://arxiv.org/pdf/2312.04985v1.pdf), cication: [**-1**](None)

	 *Luka Ribar, Ivan Chelombiev, Luke Hudlass-Galley, Charlie Blake, Carlo Luschi, Douglas Orr*
- [Notion – The all-in-one workspace for your notes, tasks, wikis, and databases.](https://yaofu.notion.site/Towards-100x-Speedup-Full-Stack-Transformer-Inference-Optimization-43124c3688e14cffaf2f1d6cbdf26c6c)

	 · ([yaofu.notion](https://yaofu.notion.site/Towards-100x-Transformer-Inference-Speedup-43124c3688e14cffaf2f1d6cbdf26c6c#b8a5e5fc309c48e5b743c90382b01c62))
- [Optimum-NVIDIA Unlocking blazingly fast LLM inference in just 1 line of code](https://huggingface.co/blog/optimum-nvidia)
- **PaSS: Parallel Speculative Sampling**, `arXiv, 2311.13581`, [arxiv](http://arxiv.org/abs/2311.13581v1), [pdf](http://arxiv.org/pdf/2311.13581v1.pdf), cication: [**-1**](None)

	 *Giovanni Monea, Armand Joulin, Edouard Grave*
- [Break the Sequential Dependency of LLM Inference Using Lookahead Decoding | LMSYS Org](https://lmsys.org/blog/2023-11-21-lookahead-decoding/)

	 · ([LookaheadDecoding](https://github.com/hao-ai-lab/LookaheadDecoding) - hao-ai-lab) ![Star](https://img.shields.io/github/stars/hao-ai-lab/LookaheadDecoding.svg?style=social&label=Star)
- **FlashDecoding++: Faster Large Language Model Inference on GPUs**, `arXiv, 2311.01282`, [arxiv](http://arxiv.org/abs/2311.01282v3), [pdf](http://arxiv.org/pdf/2311.01282v3.pdf), cication: [**-1**](None)

	 *Ke Hong, Guohao Dai, Jiaming Xu, Qiuli Mao, Xiuhong Li, Jun Liu, Kangdi Chen, Yuhan Dong, Yu Wang*
- **Deja Vu: Contextual Sparsity for Efficient LLMs at Inference Time**, `ICML, 2023`, [arxiv](http://arxiv.org/abs/2310.17157v1), [pdf](http://arxiv.org/pdf/2310.17157v1.pdf), cication: [**16**](https://scholar.google.com/scholar?cites=8791787452586294840&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zichang Liu, Jue Wang, Tri Dao, Tianyi Zhou, Binhang Yuan, Zhao Song, Anshumali Shrivastava, Ce Zhang, Yuandong Tian, Christopher Re*
- [**TensorRT-LLM**](https://github.com/NVIDIA/TensorRT-LLM#-a-tensorrt-toolbox-for-large-language-models-) - NVIDIA ![Star](https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM.svg?style=social&label=Star)

	 *TensorRT-LLM provides users with an easy-to-use Python API to define Large Language Models (LLMs)*
- **Approximating Two-Layer Feedforward Networks for Efficient Transformers**, `arXiv, 2310.10837`, [arxiv](http://arxiv.org/abs/2310.10837v2), [pdf](http://arxiv.org/pdf/2310.10837v2.pdf), cication: [**-1**](None)

	 *Róbert Csordás, Kazuki Irie, Jürgen Schmidhuber*
- [**deepsparse**](https://github.com/neuralmagic/deepsparse) - neuralmagic ![Star](https://img.shields.io/github/stars/neuralmagic/deepsparse.svg?style=social&label=Star)

	 *Inference runtime offering GPU-class performance on CPUs and APIs to integrate ML into your application* · ([huggingface](https://huggingface.co/spaces/neuralmagic/sparse-mpt-7b-gsm8k))
- [**attention_sinks**](https://github.com/tomaarsen/attention_sinks) - tomaarsen ![Star](https://img.shields.io/github/stars/tomaarsen/attention_sinks.svg?style=social&label=Star)

	 *Extend existing LLMs way beyond the original training length with constant memory usage, and without retraining*
- **Efficient Streaming Language Models with Attention Sinks**, `arXiv, 2309.17453`, [arxiv](http://arxiv.org/abs/2309.17453v1), [pdf](http://arxiv.org/pdf/2309.17453v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=12541350049673575482&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Guangxuan Xiao, Yuandong Tian, Beidi Chen, Song Han, Mike Lewis*
	- https://github.com/mit-han-lab/streaming-llm

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652386603&idx=2&sn=aed316edfc58beb3eb20c7071d7e55b3&poc_token=HCFiHmWjgjWgmSKY8EIYNnmzjCuQutsQF1Qe4SW8))
- **Efficient Memory Management for Large Language Model Serving with
  PagedAttention**, `proceedings of the 29th symposium on operating systems principles, 2023`, [arxiv](http://arxiv.org/abs/2309.06180v1), [pdf](http://arxiv.org/pdf/2309.06180v1.pdf), cication: [**21**](https://scholar.google.com/scholar?cites=7491415560688410174&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Woosuk Kwon, Zhuohan Li, Siyuan Zhuang, Ying Sheng, Lianmin Zheng, Cody Hao Yu, Joseph E. Gonzalez, Hao Zhang, Ion Stoica* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-25-14))
- [**llama2.mojo**](https://github.com/tairov/llama2.mojo) - tairov ![Star](https://img.shields.io/github/stars/tairov/llama2.mojo.svg?style=social&label=Star)

	 *Inference Llama 2 in one file of pure 🔥* · ([qbitai](https://www.qbitai.com/2023/09/83193.html))
- [**fastllm**](https://github.com/ztxz16/fastllm/) - ztxz16 ![Star](https://img.shields.io/github/stars/ztxz16/fastllm.svg?style=social&label=Star)

	 *纯c++的全平台llm加速库，支持python调用，chatglm-6B级模型单卡可达10000+token / s，支持glm, llama, moss基座，手机端流畅运行*
- [**flexflow**](https://github.com/flexflow/flexflow) - flexflow ![Star](https://img.shields.io/github/stars/flexflow/flexflow.svg?style=social&label=Star)

	 *A distributed deep learning framework.*
- **Accelerating LLM Inference with Staged Speculative Decoding**, `arXiv, 2308.04623`, [arxiv](http://arxiv.org/abs/2308.04623v1), [pdf](http://arxiv.org/pdf/2308.04623v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=15114171689819298090&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Benjamin Spector, Chris Re*
- [**CTranslate2**](https://github.com/OpenNMT/CTranslate2) - OpenNMT ![Star](https://img.shields.io/github/stars/OpenNMT/CTranslate2.svg?style=social&label=Star)

	 *Fast inference engine for Transformer models*
- **Skeleton-of-Thought: Large Language Models Can Do Parallel Decoding**, `arXiv, 2307.15337`, [arxiv](http://arxiv.org/abs/2307.15337v2), [pdf](http://arxiv.org/pdf/2307.15337v2.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=15736405249316021980&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xuefei Ning, Zinan Lin, Zixuan Zhou, Zifu Wang, Huazhong Yang, Yu Wang*
- **SkipDecode: Autoregressive Skip Decoding with Batching and Caching for
  Efficient LLM Inference**, `arXiv,  2307.02628`, [arxiv](http://arxiv.org/abs/2307.02628v1), [pdf](http://arxiv.org/pdf/2307.02628v1.pdf), cication: [**-1**](None)

	 *Luciano Del Corro, Allie Del Giorno, Sahaj Agarwal, Bin Yu, Ahmed Awadallah, Subhabrata Mukherjee*
- **An Efficient Sparse Inference Software Accelerator for Transformer-based
  Language Models on CPUs**, `arXiv, 2306.16601`, [arxiv](http://arxiv.org/abs/2306.16601v1), [pdf](http://arxiv.org/pdf/2306.16601v1.pdf), cication: [**-1**](None)

	 *Haihao Shen, Hengyu Meng, Bo Dong, Zhe Wang, Ofir Zafrir, Yi Ding, Yu Luo, Hanwen Chang, Qun Gao, Ziheng Wang*
- **NeuralFuse: Learning to Improve the Accuracy of Access-Limited Neural
  Network Inference in Low-Voltage Regimes**, `arXiv, 2306.16869`, [arxiv](http://arxiv.org/abs/2306.16869v1), [pdf](http://arxiv.org/pdf/2306.16869v1.pdf), cication: [**-1**](None)

	 *Hao-Lun Sun, Lei Hsiung, Nandhini Chandramoorthy, Pin-Yu Chen, Tsung-Yi Ho*
- **H$_2$O: Heavy-Hitter Oracle for Efficient Generative Inference of Large
  Language Models**, `arXiv, 2306.14048`, [arxiv](http://arxiv.org/abs/2306.14048v2), [pdf](http://arxiv.org/pdf/2306.14048v2.pdf), cication: [**-1**](None)

	 *Zhenyu Zhang, Ying Sheng, Tianyi Zhou, Tianlong Chen, Lianmin Zheng, Ruisi Cai, Zhao Song, Yuandong Tian, Christopher Ré, Clark Barrett* · ([H2O](https://github.com/FMInference/H2O) - FMInference) ![Star](https://img.shields.io/github/stars/FMInference/H2O.svg?style=social&label=Star)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652415599&idx=3&sn=c515f30e75705c8bcf5fbdc1130862c3))
- [DeepSpeed ZeRO++: A leap in speed for LLM and chat model training with 4X less communication - Microsoft Research](https://www.microsoft.com/en-us/research/blog/deepspeed-zero-a-leap-in-speed-for-llm-and-chat-model-training-with-4x-less-communication/)

	 · ([zhuanlan.zhihu](https://zhuanlan.zhihu.com/p/639002087))
- [**vllm**](https://github.com/vllm-project/vllm) - vllm-project ![Star](https://img.shields.io/github/stars/vllm-project/vllm.svg?style=social&label=Star)

	 *A high-throughput and memory-efficient inference and serving engine for LLMs* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652342722&idx=1&sn=ca07bcb901a1de650c13b02a65fa78ae)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-21-6))
- **SpecInfer: Accelerating Generative Large Language Model Serving with
  Speculative Inference and Token Tree Verification**, `arXiv, 2305.09781`, [arxiv](http://arxiv.org/abs/2305.09781v2), [pdf](http://arxiv.org/pdf/2305.09781v2.pdf), cication: [**-1**](None)

	 *Xupeng Miao, Gabriele Oliaro, Zhihao Zhang, Xinhao Cheng, Zeyu Wang, Rae Ying Yee Wong, Alan Zhu, Lijie Yang, Xiaoxiang Shi, Chunan Shi* · ([FlexFlow](https://github.com/flexflow/FlexFlow/tree/inference) - flexflow) ![Star](https://img.shields.io/github/stars/flexflow/FlexFlow.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247606830&idx=2&sn=cd8abf6c0fcbf70f33f6615221f46fb4))
- [**llama.cpp**](https://github.com/ggerganov/llama.cpp) - ggerganov ![Star](https://img.shields.io/github/stars/ggerganov/llama.cpp.svg?style=social&label=Star)

	 *Port of Facebook's LLaMA model in C/C++* · ([ggml](http://ggml.ai/)) · ([llama.cpp](https://github.com/ggerganov/llama.cpp/discussions/205) - ggerganov) ![Star](https://img.shields.io/github/stars/ggerganov/llama.cpp.svg?style=social&label=Star)

### Other
- [Sparse LLM Inference on CPU](https://huggingface.co/blog/mwitiderrick/llm-infrerence-on-cpu)
- [Optimizing your LLM in production](https://huggingface.co/blog/optimize-llm)
- [Speculative execution for LLMs is an excellent inference-time optimization.](https://twitter.com/karpathy/status/1697318534555336961)
- [**tvm_mlir_learn**](https://github.com/BBuf/tvm_mlir_learn) - BBuf ![Star](https://img.shields.io/github/stars/BBuf/tvm_mlir_learn.svg?style=social&label=Star)

	 *compiler learning resources collect.* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247527916&idx=2&sn=3ea2123d04509704e83486fe8a77ab14))
- [LLM生成延迟降低50%！DeepSpeed团队发布FastGen：动态SplitFuse技术，提升2.3倍有效吞吐量](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652413447&idx=5&sn=12a0246fd44783e7afc880f7751daa3d)
- [不用4个H100！340亿参数Code Llama在Mac可跑，每秒20个token，代码生成最拿手](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652371869&idx=3&sn=15310cc5305fa4c19edf318490c2dffc)｜Karpathy转赞
- [研究完llama.cpp，我发现手机跑大模型竟这么简单 | 机器之心](https://www.jiqizhixin.com/articles/2023-08-17-8)

## Mobile
- [**mlc-llm**](https://github.com/mlc-ai/mlc-llm) - mlc-ai ![Star](https://img.shields.io/github/stars/mlc-ai/mlc-llm.svg?style=social&label=Star)

	 *Enable everyone to develop, optimize and deploy AI models natively on everyone's devices.* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-05-04)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-05-2))

## Toolkits
- [**gigaGPT**](https://github.com/Cerebras/gigaGPT) - Cerebras ![Star](https://img.shields.io/github/stars/Cerebras/gigaGPT.svg?style=social&label=Star)

	 *a small code base for training large models* · ([cerebras](https://www.cerebras.net/blog/introducing-gigagpt-gpt-3-sized-models-in-565-lines-of-code))
- [**EAGLE**](https://github.com/SafeAILab/EAGLE) - SafeAILab ![Star](https://img.shields.io/github/stars/SafeAILab/EAGLE.svg?style=social&label=Star)

	 *EAGLE: Lossless Acceleration of LLM Decoding by Feature Extrapolation* · ([sites.google](https://sites.google.com/view/eagle-llm))
- [**optimum-nvidia**](https://github.com/huggingface/optimum-nvidia) - huggingface ![Star](https://img.shields.io/github/stars/huggingface/optimum-nvidia.svg?style=social&label=Star)
- [**unsloth**](https://github.com/unslothai/unsloth) - unslothai ![Star](https://img.shields.io/github/stars/unslothai/unsloth.svg?style=social&label=Star)

	 *5X faster 50% less memory LLM finetuning*
- [**lit-gpt**](https://github.com/Lightning-AI/lit-gpt) - Lightning-AI ![Star](https://img.shields.io/github/stars/Lightning-AI/lit-gpt.svg?style=social&label=Star)

	 *Hackable implementation of state-of-the-art open-source LLMs based on nanoGPT. Supports flash attention, 4-bit and 8-bit quantization, LoRA and LLaMA-Adapter fine-tuning, pre-training. Apache 2.0-licensed.*
- [**gpt-fast**](https://github.com/pytorch-labs/gpt-fast) - pytorch-labs ![Star](https://img.shields.io/github/stars/pytorch-labs/gpt-fast.svg?style=social&label=Star)

	 *Simple and efficient pytorch-native transformer text generation in <1000 LOC of python.*
- [**MS-AMP**](https://github.com/Azure/MS-AMP#ms-amp-microsoft-automatic-mixed-precision) - Azure ![Star](https://img.shields.io/github/stars/Azure/MS-AMP.svg?style=social&label=Star)

	 *Microsoft Automatic Mixed Precision Library*
- [**DeepSpeed**](https://github.com/microsoft/DeepSpeed) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/DeepSpeed.svg?style=social&label=Star)

	 *DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective.*

## Efficient transformer
- **Rethinking Compression: Reduced Order Modelling of Latent Features in
  Large Language Models**, `arXiv, 2312.07046`, [arxiv](http://arxiv.org/abs/2312.07046v1), [pdf](http://arxiv.org/pdf/2312.07046v1.pdf), cication: [**-1**](None)

	 *Arnav Chavan, Nahush Lele, Deepak Gupta*
- [Paving the way to efficient architectures: StripedHyena-7B, open source models offering a glimpse into a world beyond Transformers](https://www.together.ai/blog/stripedhyena-7b)
- **Efficient Monotonic Multihead Attention**, `arXiv, 2312.04515`, [arxiv](http://arxiv.org/abs/2312.04515v1), [pdf](http://arxiv.org/pdf/2312.04515v1.pdf), cication: [**-1**](None)

	 *Xutai Ma, Anna Sun, Siqi Ouyang, Hirofumi Inaguma, Paden Tomasello*
- **Mamba: Linear-Time Sequence Modeling with Selective State Spaces**, `arXiv, 2312.00752`, [arxiv](http://arxiv.org/abs/2312.00752v1), [pdf](http://arxiv.org/pdf/2312.00752v1.pdf), cication: [**-1**](None)

	 *Albert Gu, Tri Dao* · ([qbitai](https://www.qbitai.com/2023/12/103440.html))
- **Simplifying Transformer Blocks**, `arXiv, 2311.01906`, [arxiv](http://arxiv.org/abs/2311.01906v1), [pdf](http://arxiv.org/pdf/2311.01906v1.pdf), cication: [**-1**](None)

	 *Bobby He, Thomas Hofmann* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-28-12))
- **Exponentially Faster Language Modelling**, `arXiv, 2311.10770`, [arxiv](http://arxiv.org/abs/2311.10770v1), [pdf](http://arxiv.org/pdf/2311.10770v1.pdf), cication: [**-1**](None)

	 *Peter Belcak, Roger Wattenhofer*
	 - [GitHub - pbelcak/UltraFastBERT: The repository for the code of the UltraFastBERT paper](https://github.com/pbelcak/UltraFastBERT)
- **Simplifying Transformer Blocks**, `arXiv, 2311.01906`, [arxiv](http://arxiv.org/abs/2311.01906v1), [pdf](http://arxiv.org/pdf/2311.01906v1.pdf), cication: [**-1**](None)

	 *Bobby He, Thomas Hofmann*
- **Alternating Updates for Efficient Transformers**, `arXiv, 2301.13310`, [arxiv](http://arxiv.org/abs/2301.13310v2), [pdf](http://arxiv.org/pdf/2301.13310v2.pdf), cication: [**-1**](None)

	 *Cenk Baykal, Dylan Cutler, Nishanth Dikkala, Nikhil Ghosh, Rina Panigrahy, Xin Wang*
- **FlashAttention: Fast and Memory-Efficient Exact Attention with
  IO-Awareness**, `NeurIPS, 2022`, [arxiv](http://arxiv.org/abs/2205.14135v2), [pdf](http://arxiv.org/pdf/2205.14135v2.pdf), cication: [**278**](https://scholar.google.com/scholar?cites=4436654227589737701&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tri Dao, Daniel Y. Fu, Stefano Ermon, Atri Rudra, Christopher Ré*
- **Fast Transformer Decoding: One Write-Head is All You Need**, `arXiv, 1911.02150`, [arxiv](http://arxiv.org/abs/1911.02150v1), [pdf](http://arxiv.org/pdf/1911.02150v1.pdf), cication: [**61**](https://scholar.google.com/scholar?cites=10300170731250747989&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Noam Shazeer*

	 · ([zhuanlan.zhihu](https://zhuanlan.zhihu.com/p/634236135))

##  Other
- [Schedule | NeurIPS Large Language Model Efficiency Challenge:1 LLM + 1GPU + 1Day](https://llm-efficiency-challenge.github.io/schedule)
- [Dynamic LoRA loading for better performance and optimized resource usage](https://huggingface.co/blog/lora-adapters-dynamic-loading)
## Courses
### EfficientML
- [EfficientML.ai Lecture, Fall 2023, MIT 6.5940 - YouTube](https://www.youtube.com/playlist?list=PL80kAHvQbh-pT4lCkDT53zT8DKmhE0idB)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-25-15)) · ([bilibili](https://www.bilibili.com/video/BV1W14y1C7jv/?spm_id_from=333.999.0.0&vd_source=1453a06a1e0b377f5c40946333b4423a)) · ([dropbox](https://www.dropbox.com/sh/0ftluqbd1afzqpy/AADqxwkYrt1FbGnSQ4KP3Kpva?dl=0))