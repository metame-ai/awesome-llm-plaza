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
- **Beyond the Speculative Game: A Survey of Speculative Execution in Large
  Language Models**, `arXiv, 2404.14897`, [arxiv](http://arxiv.org/abs/2404.14897v1), [pdf](http://arxiv.org/pdf/2404.14897v1.pdf), cication: [**-1**](None)

	 *Chen Zhang, Zhuorui Liu, Dawei Song*
- **A Survey on Efficient Inference for Large Language Models**, `arXiv, 2404.14294`, [arxiv](http://arxiv.org/abs/2404.14294v1), [pdf](http://arxiv.org/pdf/2404.14294v1.pdf), cication: [**-1**](None)

	 *Zixuan Zhou, Xuefei Ning, Ke Hong, Tianyu Fu, Jiaming Xu, Shiyao Li, Yuming Lou, Luning Wang, Zhihang Yuan, Xiuhong Li*
- **A Survey on Knowledge Distillation of Large Language Models**, `arXiv, 2402.13116`, [arxiv](http://arxiv.org/abs/2402.13116v3), [pdf](http://arxiv.org/pdf/2402.13116v3.pdf), cication: [**-1**](None)

	 *Xiaohan Xu, Ming Li, Chongyang Tao, Tao Shen, Reynold Cheng, Jinyang Li, Can Xu, Dacheng Tao, Tianyi Zhou* · ([Awesome-Knowledge-Distillation-of-LLMs](https://github.com/Tebmer/Awesome-Knowledge-Distillation-of-LLMs) - Tebmer) ![Star](https://img.shields.io/github/stars/Tebmer/Awesome-Knowledge-Distillation-of-LLMs.svg?style=social&label=Star) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-03-18))
- **Efficient Exploration for LLMs**, `arXiv, 2402.00396`, [arxiv](http://arxiv.org/abs/2402.00396v1), [pdf](http://arxiv.org/pdf/2402.00396v1.pdf), cication: [**-1**](None)

	 *Vikranth Dwaracherla, Seyed Mohammad Asghari, Botao Hao, Benjamin Van Roy*
- **A Comprehensive Survey of Compression Algorithms for Language Models**, `arXiv, 2401.15347`, [arxiv](http://arxiv.org/abs/2401.15347v1), [pdf](http://arxiv.org/pdf/2401.15347v1.pdf), cication: [**-1**](None)

	 *Seungcheol Park, Jaehyeon Choi, Sojin Lee, U Kang*
- **A Survey of Resource-efficient LLM and Multimodal Foundation Models**, `arXiv, 2401.08092`, [arxiv](http://arxiv.org/abs/2401.08092v1), [pdf](http://arxiv.org/pdf/2401.08092v1.pdf), cication: [**-1**](None)

	 *Mengwei Xu, Wangsong Yin, Dongqi Cai, Rongjie Yi, Daliang Xu, Qipeng Wang, Bingyang Wu, Yihao Zhao, Chen Yang, Shihe Wang*

	 · ([efficient_foundation_model_survey](https://github.com/ubiquitouslearning/efficient_foundation_model_survey) - ubiquitouslearning) ![Star](https://img.shields.io/github/stars/ubiquitouslearning/efficient_foundation_model_survey.svg?style=social&label=Star)
- **Understanding LLMs: A Comprehensive Overview from Training to Inference**, `arXiv, 2401.02038`, [arxiv](http://arxiv.org/abs/2401.02038v2), [pdf](http://arxiv.org/pdf/2401.02038v2.pdf), cication: [**-1**](None)

	 *Yiheng Liu, Hao He, Tianle Han, Xu Zhang, Mengyuan Liu, Jiaming Tian, Yutong Zhang, Jiaqi Wang, Xiaohui Gao, Tianyang Zhong*
- **Efficient Large Language Models: A Survey**, `arXiv, 2312.03863`, [arxiv](http://arxiv.org/abs/2312.03863v1), [pdf](http://arxiv.org/pdf/2312.03863v1.pdf), cication: [**-1**](None)

	 *Zhongwei Wan, Xin Wang, Che Liu, Samiul Alam, Yu Zheng, Zhongnan Qu, Shen Yan, Yi Zhu, Quanlu Zhang, Mosharaf Chowdhury* · ([Efficient-LLMs-Survey](https://github.com/AIoT-MLSys-Lab/Efficient-LLMs-Survey) - AIoT-MLSys-Lab) ![Star](https://img.shields.io/github/stars/AIoT-MLSys-Lab/Efficient-LLMs-Survey.svg?style=social&label=Star)
- **Towards Efficient Generative Large Language Model Serving: A Survey from
  Algorithms to Systems**, `arXiv, 2312.15234`, [arxiv](http://arxiv.org/abs/2312.15234v1), [pdf](http://arxiv.org/pdf/2312.15234v1.pdf), cication: [**-1**](None)

	 *Xupeng Miao, Gabriele Oliaro, Zhihao Zhang, Xinhao Cheng, Hongyi Jin, Tianqi Chen, Zhihao Jia* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247624080&idx=3&sn=f3b3f16bd4bd811cfa6f62155370eab8))
- **The Efficiency Spectrum of Large Language Models: An Algorithmic Survey**, `arXiv, 2312.00678`, [arxiv](http://arxiv.org/abs/2312.00678v1), [pdf](http://arxiv.org/pdf/2312.00678v1.pdf), cication: [**-1**](None)

	 *Tianyu Ding, Tianyi Chen, Haidong Zhu, Jiachen Jiang, Yiqi Zhong, Jinxin Zhou, Guangzhi Wang, Zhihui Zhu, Ilya Zharkov, Luming Liang*
- **Scaling Down to Scale Up: A Guide to Parameter-Efficient Fine-Tuning**, `arXiv, 2303.15647`, [arxiv](http://arxiv.org/abs/2303.15647v1), [pdf](http://arxiv.org/pdf/2303.15647v1.pdf), cication: [**-1**](None)

	 *Vladislav Lialin, Vijeta Deshpande, Anna Rumshisky*
## Efficient finetuning
- **LoRA Land: 310 Fine-tuned LLMs that Rival GPT-4, A Technical Report**, `arXiv, 2405.00732`, [arxiv](http://arxiv.org/abs/2405.00732v1), [pdf](http://arxiv.org/pdf/2405.00732v1.pdf), cication: [**-1**](None)

	 *Justin Zhao, Timothy Wang, Wael Abid, Geoffrey Angus, Arnav Garg, Jeffery Kinnison, Alex Sherstinsky, Piero Molino, Travis Addair, Devvret Rishi*
- **PiSSA: Principal Singular Values and Singular Vectors Adaptation of
  Large Language Models**, `arXiv, 2404.02948`, [arxiv](http://arxiv.org/abs/2404.02948v1), [pdf](http://arxiv.org/pdf/2404.02948v1.pdf), cication: [**-1**](None)

	 *Fanxu Meng, Zhaohui Wang, Muhan Zhang* · ([PiSSA](https://github.com/GraphPKU/PiSSA) - GraphPKU) ![Star](https://img.shields.io/github/stars/GraphPKU/PiSSA.svg?style=social&label=Star)
- **ReFT: Representation Finetuning for Language Models**, `arXiv, 2404.03592`, [arxiv](http://arxiv.org/abs/2404.03592v1), [pdf](http://arxiv.org/pdf/2404.03592v1.pdf), cication: [**-1**](None)

	 *Zhengxuan Wu, Aryaman Arora, Zheng Wang, Atticus Geiger, Dan Jurafsky, Christopher D. Manning, Christopher Potts* · ([pyreft](https://github.com/stanfordnlp/pyreft) - stanfordnlp) ![Star](https://img.shields.io/github/stars/stanfordnlp/pyreft.svg?style=social&label=Star)
	- `by manipulating a small fraction of model representations it is possible to effectively steer model behavior to achieve better downstream performance at inference time; also proposes LoReFT as a drop-in replacement for PEFTs that is 10-50x more parameter efficient.`
- **Model Stock: All we need is just a few fine-tuned models**, `arXiv, 2403.19522`, [arxiv](http://arxiv.org/abs/2403.19522v1), [pdf](http://arxiv.org/pdf/2403.19522v1.pdf), cication: [**-1**](None)

	 *Dong-Hwan Jang, Sangdoo Yun, Dongyoon Han*
	- `uses just two models for layer-wise weight averaging.`
- **DiJiang: Efficient Large Language Models through Compact Kernelization**, `arXiv, 2403.19928`, [arxiv](http://arxiv.org/abs/2403.19928v1), [pdf](http://arxiv.org/pdf/2403.19928v1.pdf), cication: [**-1**](None)

	 *Hanting Chen, Zhicheng Liu, Xutao Wang, Yuchuan Tian, Yunhe Wang* · ([DiJiang](https://github.com/YuchuanTian/DiJiang) - YuchuanTian) ![Star](https://img.shields.io/github/stars/YuchuanTian/DiJiang.svg?style=social&label=Star)
- **LISA: Layerwise Importance Sampling for Memory-Efficient Large Language
  Model Fine-Tuning**, `arXiv, 2403.17919`, [arxiv](http://arxiv.org/abs/2403.17919v1), [pdf](http://arxiv.org/pdf/2403.17919v1.pdf), cication: [**-1**](None)

	 *Rui Pan, Xiang Liu, Shizhe Diao, Renjie Pi, Jipeng Zhang, Chi Han, Tong Zhang*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-04-01-13)) · ([LMFlow](https://github.com/OptimalScale/LMFlow) - OptimalScale) ![Star](https://img.shields.io/github/stars/OptimalScale/LMFlow.svg?style=social&label=Star)
	- `randomly freezing middle layers during training based on importance sampling, which is efficient and can outperform both LoRA and and full LLM finetuning by a noticeable margin in terms of model performance.`
- **Mixture-of-LoRAs: An Efficient Multitask Tuning for Large Language
  Models**, `arXiv, 2403.03432`, [arxiv](http://arxiv.org/abs/2403.03432v1), [pdf](http://arxiv.org/pdf/2403.03432v1.pdf), cication: [**-1**](None)

	 *Wenfeng Feng, Chuzhan Hao, Yuewei Zhang, Yu Han, Hao Wang*
- **GaLore: Memory-Efficient LLM Training by Gradient Low-Rank Projection**, `arXiv, 2403.03507`, [arxiv](http://arxiv.org/abs/2403.03507v1), [pdf](http://arxiv.org/pdf/2403.03507v1.pdf), cication: [**-1**](None)

	 *Jiawei Zhao, Zhenyu Zhang, Beidi Chen, Zhangyang Wang, Anima Anandkumar, Yuandong Tian*
	 · ([galore](https://github.com/jiaweizzhao/galore) - jiaweizzhao) ![Star](https://img.shields.io/github/stars/jiaweizzhao/galore.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/blog/galore))
	- `Gradient Low-Rank Projection (GaLore) is a new training strategy that significantly reduces memory usage by up to 65.5% for optimizer states during the training of LLMs, without sacrificing performance.`

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247634034&idx=2&sn=7cd5c5e8af9bab29c786f52e9ea3b6e7))
- **LoRA+: Efficient Low Rank Adaptation of Large Models**, `arXiv, 2402.12354`, [arxiv](http://arxiv.org/abs/2402.12354v1), [pdf](http://arxiv.org/pdf/2402.12354v1.pdf), cication: [**-1**](None)

	 *Soufiane Hayou, Nikhil Ghosh, Bin Yu*
- **DoRA: Weight-Decomposed Low-Rank Adaptation**, `arXiv, 2402.09353`, [arxiv](http://arxiv.org/abs/2402.09353v1), [pdf](http://arxiv.org/pdf/2402.09353v1.pdf), cication: [**-1**](None)

	 *Shih-Yang Liu, Chien-Yi Wang, Hongxu Yin, Pavlo Molchanov, Yu-Chiang Frank Wang, Kwang-Ting Cheng, Min-Hung Chen* · ([dora](https://github.com/catid/dora?tab=readme-ov-file) - catid) ![Star](https://img.shields.io/github/stars/catid/dora.svg?style=social&label=Star)

	 · ([magazine.sebastianraschka](https://t.co/uPzXgBQ9vh))
- **Astraios: Parameter-Efficient Instruction Tuning Code Large Language
  Models**, `arXiv, 2401.00788`, [arxiv](http://arxiv.org/abs/2401.00788v1), [pdf](http://arxiv.org/pdf/2401.00788v1.pdf), cication: [**-1**](None)

	 *Terry Yue Zhuo, Armel Zebaze, Nitchakarn Suppattarachai, Leandro von Werra, Harm de Vries, Qian Liu, Niklas Muennighoff*
- **Parameter Efficient Tuning Allows Scalable Personalization of LLMs for
  Text Entry: A Case Study on Abbreviation Expansion**, `arXiv, 2312.14327`, [arxiv](http://arxiv.org/abs/2312.14327v1), [pdf](http://arxiv.org/pdf/2312.14327v1.pdf), cication: [**-1**](None)

	 *Katrin Tomanek, Shanqing Cai, Subhashini Venugopalan*
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

	 · ([peft](https://github.com/huggingface/peft/tree/main/examples/loftq_finetuning) - huggingface) ![Star](https://img.shields.io/github/stars/huggingface/peft.svg?style=social&label=Star)
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

### Other
- [LoRA及其变体概述：LoRA, DoRA, AdaLoRA, Delta-LoRA](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247632908&idx=2&sn=f2daa489741ccc4a7f8f9c4c178c4740)

## Quantization
### Survey
- **A Performance Evaluation of a Quantized Large Language Model on Various
  Smartphones**, `arXiv, 2312.12472`, [arxiv](http://arxiv.org/abs/2312.12472v1), [pdf](http://arxiv.org/pdf/2312.12472v1.pdf), cication: [**-1**](None)

	 *Tolga Çöplü, Marc Loedi, Arto Bendiken, Mykhailo Makohin, Joshua J. Bouw, Stephen Cobb*
- **A Survey on Model Compression for Large Language Models**, `arXiv, 2308.07633`, [arxiv](http://arxiv.org/abs/2308.07633v3), [pdf](http://arxiv.org/pdf/2308.07633v3.pdf), cication: [**-1**](None)

	 *Xunyu Zhu, Jian Li, Yong Liu, Can Ma, Weiping Wang* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-26-5))

### Papers
- **QuaRot: Outlier-Free 4-Bit Inference in Rotated LLMs**, `arXiv, 2404.00456`, [arxiv](http://arxiv.org/abs/2404.00456v1), [pdf](http://arxiv.org/pdf/2404.00456v1.pdf), cication: [**-1**](None)

	 *Saleh Ashkboos, Amirkeivan Mohtashami, Maximilian L. Croci, Bo Li, Martin Jaggi, Dan Alistarh, Torsten Hoefler, James Hensman* · ([QuaRot](https://github.com/spcl/QuaRot?tab=readme-ov-file) - spcl) ![Star](https://img.shields.io/github/stars/spcl/QuaRot.svg?style=social&label=Star)
- **EasyQuant: An Efficient Data-free Quantization Algorithm for LLMs**, `arXiv, 2403.02775`, [arxiv](http://arxiv.org/abs/2403.02775v1), [pdf](http://arxiv.org/pdf/2403.02775v1.pdf), cication: [**-1**](None)

	 *Hanlin Tang, Yifu Sun, Decheng Wu, Kai Liu, Jianchen Zhu, Zhanhui Kang*
- **The Era of 1-bit LLMs: All Large Language Models are in 1.58 Bits**, `arXiv, 2402.17764`, [arxiv](http://arxiv.org/abs/2402.17764v1), [pdf](http://arxiv.org/pdf/2402.17764v1.pdf), cication: [**-1**](None)

	 *Shuming Ma, Hongyu Wang, Lingxiao Ma, Lei Wang, Wenhui Wang, Shaohan Huang, Li Dong, Ruiping Wang, Jilong Xue, Furu Wei*

	 · ([unilm](https://github.com/microsoft/unilm/blob/master/bitnet/The-Era-of-1-bit-LLMs__Training_Tips_Code_FAQ.pdf) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star) · ([unilm](https://github.com/microsoft/unilm/tree/master/bitnet) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star)
	 - [NousResearch/OLMo-Bitnet-1B · Hugging Face](https://huggingface.co/NousResearch/OLMo-Bitnet-1B)
	 - [1bitLLM/bitnet\_b1\_58-3B · Hugging Face](https://huggingface.co/1bitLLM/bitnet_b1_58-3B)
- **GPTVQ: The Blessing of Dimensionality for LLM Quantization**, `arXiv, 2402.15319`, [arxiv](http://arxiv.org/abs/2402.15319v1), [pdf](http://arxiv.org/pdf/2402.15319v1.pdf), cication: [**-1**](None)

	 *Mart van Baalen, Andrey Kuzmin, Markus Nagel, Peter Couperus, Cedric Bastoul, Eric Mahurin, Tijmen Blankevoort, Paul Whatmough*
- **OneBit: Towards Extremely Low-bit Large Language Models**, `arXiv, 2402.11295`, [arxiv](http://arxiv.org/abs/2402.11295v1), [pdf](http://arxiv.org/pdf/2402.11295v1.pdf), cication: [**-1**](None)

	 *Yuzhuang Xu, Xu Han, Zonghan Yang, Shuo Wang, Qingfu Zhu, Zhiyuan Liu, Weidong Liu, Wanxiang Che*
- **Extreme Compression of Large Language Models via Additive Quantization**, `arXiv, 2401.06118`, [arxiv](http://arxiv.org/abs/2401.06118v2), [pdf](http://arxiv.org/pdf/2401.06118v2.pdf), cication: [**-1**](None)

	 *Vage Egiazarian, Andrei Panferov, Denis Kuznedelev, Elias Frantar, Artem Babenko, Dan Alistarh* · ([aqlm](https://github.com/vahe1994/aqlm?tab=readme-ov-file) - vahe1994) ![Star](https://img.shields.io/github/stars/vahe1994/aqlm.svg?style=social&label=Star)
- **KIVI: A Tuning-Free Asymmetric 2bit Quantization for KV Cache**, `arXiv, 2402.02750`, [arxiv](http://arxiv.org/abs/2402.02750v1), [pdf](http://arxiv.org/pdf/2402.02750v1.pdf), cication: [**-1**](None)

	 *Zirui Liu, Jiayi Yuan, Hongye Jin, Shaochen Zhong, Zhaozhuo Xu, Vladimir Braverman, Beidi Chen, Xia Hu* · ([kivi](https://github.com/jy-yuan/kivi) - jy-yuan) ![Star](https://img.shields.io/github/stars/jy-yuan/kivi.svg?style=social&label=Star)
- **Towards Next-Level Post-Training Quantization of Hyper-Scale
  Transformers**, `arXiv, 2402.08958`, [arxiv](http://arxiv.org/abs/2402.08958v1), [pdf](http://arxiv.org/pdf/2402.08958v1.pdf), cication: [**-1**](None)

	 *Junhan Kim, Kyungphil Park, Chungman Lee, Ho-young Kim, Joonyoung Kim, Yongkweon Jeon*
- **TP-Aware Dequantization**, `arXiv, 2402.04925`, [arxiv](http://arxiv.org/abs/2402.04925v1), [pdf](http://arxiv.org/pdf/2402.04925v1.pdf), cication: [**-1**](None)

	 *Adnan Hoque, Mudhakar Srivatsa, Chih-Chieh Yang, Raghu Ganti*
- **BiLLM: Pushing the Limit of Post-Training Quantization for LLMs**, `arXiv, 2402.04291`, [arxiv](http://arxiv.org/abs/2402.04291v1), [pdf](http://arxiv.org/pdf/2402.04291v1.pdf), cication: [**-1**](None)

	 *Wei Huang, Yangdong Liu, Haotong Qin, Ying Li, Shiming Zhang, Xianglong Liu, Michele Magno, Xiaojuan Qi*
- **FP6-LLM: Efficiently Serving Large Language Models Through FP6-Centric
  Algorithm-System Co-Design**, `arXiv, 2401.14112`, [arxiv](http://arxiv.org/abs/2401.14112v1), [pdf](http://arxiv.org/pdf/2401.14112v1.pdf), cication: [**-1**](None)

	 *Haojun Xia, Zhen Zheng, Xiaoxia Wu, Shiyang Chen, Zhewei Yao, Stephen Youn, Arash Bakhtiari, Michael Wyatt, Donglin Zhuang, Zhongzhu Zhou*
- **ZeroQuant(4+2): Redefining LLMs Quantization with a New FP6-Centric
  Strategy for Diverse Generative Tasks**, `arXiv, 2312.08583`, [arxiv](http://arxiv.org/abs/2312.08583v1), [pdf](http://arxiv.org/pdf/2312.08583v1.pdf), cication: [**-1**](None)

	 *Xiaoxia Wu, Haojun Xia, Stephen Youn, Zhen Zheng, Shiyang Chen, Arash Bakhtiari, Michael Wyatt, Yuxiong He, Olatunji Ruwase, Leon Song*
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
- **Atom: Low-bit Quantization for Efficient and Accurate LLM Serving**, `arXiv, 2310.19102`, [arxiv](http://arxiv.org/abs/2310.19102v2), [pdf](http://arxiv.org/pdf/2310.19102v2.pdf), cication: [**-1**](None)

	 *Yilong Zhao, Chien-Yu Lin, Kan Zhu, Zihao Ye, Lequn Chen, Size Zheng, Luis Ceze, Arvind Krishnamurthy, Tianqi Chen, Baris Kasikci* · ([atom](https://github.com/efeslab/atom) - efeslab) ![Star](https://img.shields.io/github/stars/efeslab/atom.svg?style=social&label=Star)
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

	 *Tim Dettmers, Ruslan Svirschevski, Vage Egiazarian, Denis Kuznedelev, Elias Frantar, Saleh Ashkboos, Alexander Borzunov, Torsten Hoefler, Dan Alistarh* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-07-5))
- **AWQ: Activation-aware Weight Quantization for LLM Compression and
  Acceleration**, `arXiv, 2306.00978`, [arxiv](http://arxiv.org/abs/2306.00978v2), [pdf](http://arxiv.org/pdf/2306.00978v2.pdf), cication: [**-1**](None)

	 *Ji Lin, Jiaming Tang, Haotian Tang, Shang Yang, Xingyu Dang, Chuang Gan, Song Han*
- **GPTQ: Accurate Post-Training Quantization for Generative Pre-trained
  Transformers**, `arXiv, 2210.17323`, [arxiv](http://arxiv.org/abs/2210.17323v2), [pdf](http://arxiv.org/pdf/2210.17323v2.pdf), cication: [**-1**](None)

	 *Elias Frantar, Saleh Ashkboos, Torsten Hoefler, Dan Alistarh* · ([gptq](https://github.com/IST-DASLab/gptq) - IST-DASLab) ![Star](https://img.shields.io/github/stars/IST-DASLab/gptq.svg?style=social&label=Star)
-  [[2208.07339] LLM.int8(): 8-bit Matrix Multiplication for Transformers at Scale](https://arxiv.org/abs/2208.07339)

	 · ([bitsandbytes](https://github.com/timdettmers/bitsandbytes) - timdettmers) ![Star](https://img.shields.io/github/stars/timdettmers/bitsandbytes.svg?style=social&label=Star)

### Projects
- [lmstudio-community (LM Studio Community)](https://huggingface.co/lmstudio-community)
- [**BitMat**](https://github.com/astramind-ai/BitMat) - astramind-ai ![Star](https://img.shields.io/github/stars/astramind-ai/BitMat.svg?style=social&label=Star)

	 *An efficent implementation of the method proposed in "The Era of 1-bit LLMs"*
- [1bitLLM (1bitLLM)](https://huggingface.co/1bitLLM?utm_source=ainews&utm_medium=email&utm_campaign=ainews-adamw-aarond)
- [**QLLM**](https://github.com/wejoncy/QLLM) - wejoncy ![Star](https://img.shields.io/github/stars/wejoncy/QLLM.svg?style=social&label=Star)

	 日*A general 2-8 bits quantization toolbox with GPTQ/AWQ/HQQ, and export to onnx/onnx-runtime easily.*
- [**hqq**](https://github.com/mobiusml/hqq) - mobiusml ![Star](https://img.shields.io/github/stars/mobiusml/hqq.svg?style=social&label=Star)

	 *Official implementation of Half-Quadratic Quantization (HQQ)* · ([mobiusml.github](https://mobiusml.github.io/hqq_blog/))
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
- **Divide-or-Conquer? Which Part Should You Distill Your LLM?**, `arXiv, 2402.15000`, [arxiv](http://arxiv.org/abs/2402.15000v1), [pdf](http://arxiv.org/pdf/2402.15000v1.pdf), cication: [**-1**](None)

	 *Zhuofeng Wu, He Bai, Aonan Zhang, Jiatao Gu, VG Vinod Vydiswaran, Navdeep Jaitly, Yizhe Zhang*
- **DistiLLM: Towards Streamlined Distillation for Large Language Models**, `arXiv, 2402.03898`, [arxiv](http://arxiv.org/abs/2402.03898v1), [pdf](http://arxiv.org/pdf/2402.03898v1.pdf), cication: [**-1**](None)

	 *Jongwoo Ko, Sungnyun Kim, Tianyi Chen, Se-Young Yun* · ([distillm](https://github.com/jongwooko/distillm) - jongwooko) ![Star](https://img.shields.io/github/stars/jongwooko/distillm.svg?style=social&label=Star)
- **Scavenging Hyena: Distilling Transformers into Long Convolution Models**, `arXiv, 2401.17574`, [arxiv](http://arxiv.org/abs/2401.17574v1), [pdf](http://arxiv.org/pdf/2401.17574v1.pdf), cication: [**-1**](None)

	 *Tokiniaina Raharison Ralambomihanta, Shahrad Mohammadzadeh, Mohammad Sami Nur Islam, Wassim Jabbour, Laurence Liang*
- [Proceedings of the BabyLM Challenge at the 27th Conference on Computational Natural Language Learning - ACL Anthology](https://aclanthology.org/volumes/2023.conll-babylm/)

	 · ([twitter](https://twitter.com/a_stadt/status/1737849248560066794?s=20))
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
- **The Unreasonable Ineffectiveness of the Deeper Layers**, `arXiv, 2403.17887`, [arxiv](http://arxiv.org/abs/2403.17887v1), [pdf](http://arxiv.org/pdf/2403.17887v1.pdf), cication: [**-1**](None)

	 *Andrey Gromov, Kushal Tirumala, Hassan Shapourian, Paolo Glorioso, Daniel A. Roberts*
	- `selectively pruning up to half the layers of pretrained LLMs, followed by strategic finetuning with quantization and QLoRA, minimally impacts performance on question-answering tasks.`
- **ShortGPT: Layers in Large Language Models are More Redundant Than You
  Expect**, `arXiv, 2403.03853`, [arxiv](http://arxiv.org/abs/2403.03853v1), [pdf](http://arxiv.org/pdf/2403.03853v1.pdf), cication: [**-1**](None)

	 *Xin Men, Mingyu Xu, Qingyu Zhang, Bingning Wang, Hongyu Lin, Yaojie Lu, Xianpei Han, Weipeng Chen*
	- This study introduces the Block Influence (BI) metric to assess each layer's importance in LLMs and proposes ShortGPT, a pruning approach that removes redundant layers based on BI scores.
- **Shortened LLaMA: A Simple Depth Pruning for Large Language Models**, `arXiv, 2402.02834`, [arxiv](http://arxiv.org/abs/2402.02834v1), [pdf](http://arxiv.org/pdf/2402.02834v1.pdf), cication: [**-1**](None)

	 *Bo-Kyeong Kim, Geonmin Kim, Tae-Ho Kim, Thibault Castells, Shinkook Choi, Junho Shin, Hyoung-Kyu Song*
- **SliceGPT: Compress Large Language Models by Deleting Rows and Columns**, `arXiv, 2401.15024`, [arxiv](http://arxiv.org/abs/2401.15024v1), [pdf](http://arxiv.org/pdf/2401.15024v1.pdf), cication: [**-1**](None)

	 *Saleh Ashkboos, Maximilian L. Croci, Marcelo Gennari do Nascimento, Torsten Hoefler, James Hensman*
- [Fast Llama 2 on CPUs With Sparse Fine-Tuning and DeepSparse - Neural Magic](https://neuralmagic.com/blog/fast-llama-2-on-cpus-with-sparse-fine-tuning-and-deepsparse/)
- **The LLM Surgeon**, `arXiv, 2312.17244`, [arxiv](http://arxiv.org/abs/2312.17244v1), [pdf](http://arxiv.org/pdf/2312.17244v1.pdf), cication: [**-1**](None)

	 *Tycho F. A. van der Ouderaa, Markus Nagel, Mart van Baalen, Yuki M. Asano, Tijmen Blankevoort*
- **Mini-GPTs: Efficient Large Language Models through Contextual Pruning**, `arXiv, 2312.12682`, [arxiv](http://arxiv.org/abs/2312.12682v1), [pdf](http://arxiv.org/pdf/2312.12682v1.pdf), cication: [**-1**](None)

	 *Tim Valicenti, Justice Vidal, Ritik Patnaik*
- **Sheared LLaMA: Accelerating Language Model Pre-training via Structured
  Pruning**, `arXiv, 2310.06694`, [arxiv](http://arxiv.org/abs/2310.06694v1), [pdf](http://arxiv.org/pdf/2310.06694v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=9713425200262995197&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Mengzhou Xia, Tianyu Gao, Zhiyuan Zeng, Danqi Chen* · ([qbitai](https://www.qbitai.com/2023/10/89367.html)) · ([xiamengzhou.github](https://xiamengzhou.github.io/sheared-llama/)) · ([llm-shearing](https://github.com/princeton-nlp/llm-shearing) - princeton-nlp) ![Star](https://img.shields.io/github/stars/princeton-nlp/llm-shearing.svg?style=social&label=Star)
- [**wanda**](https://github.com/locuslab/wanda) - locuslab ![Star](https://img.shields.io/github/stars/locuslab/wanda.svg?style=social&label=Star)

	 *A simple and effective LLM pruning approach.*
- **ResiDual: Transformer with Dual Residual Connections**, `arXiv, 2304.14802`, [arxiv](http://arxiv.org/abs/2304.14802v1), [pdf](http://arxiv.org/pdf/2304.14802v1.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=13454570814273304026&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shufang Xie, Huishuai Zhang, Junliang Guo, Xu Tan, Jiang Bian, Hany Hassan Awadalla, Arul Menezes, Tao Qin, Rui Yan* · ([ResiDual](https://github.com/microsoft/ResiDual) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/ResiDual.svg?style=social&label=Star)

## Efficient Inference
- **Clover: Regressive Lightweight Speculative Decoding with Sequential
  Knowledge**, `arXiv, 2405.00263`, [arxiv](http://arxiv.org/abs/2405.00263v1), [pdf](http://arxiv.org/pdf/2405.00263v1.pdf), cication: [**-1**](None)

	 *Bin Xiao, Chunan Shi, Xiaonan Nie, Fan Yang, Xiangwei Deng, Lei Su, Weipeng Chen, Bin Cui*
- **Kangaroo: Lossless Self-Speculative Decoding via Double Early Exiting**, `arXiv, 2404.18911`, [arxiv](http://arxiv.org/abs/2404.18911v1), [pdf](http://arxiv.org/pdf/2404.18911v1.pdf), cication: [**-1**](None)

	 *Fangcheng Liu, Yehui Tang, Zhenhua Liu, Yunsheng Ni, Kai Han, Yunhe Wang* · ([Kangaroo](https://github.com/Equationliu/Kangaroo) - Equationliu) ![Star](https://img.shields.io/github/stars/Equationliu/Kangaroo.svg?style=social&label=Star)
- **Better & Faster Large Language Models via Multi-token Prediction**, `arXiv, 2404.19737`, [arxiv](http://arxiv.org/abs/2404.19737v1), [pdf](http://arxiv.org/pdf/2404.19737v1.pdf), cication: [**-1**](None)

	 *Fabian Gloeckle, Badr Youbi Idrissi, Baptiste Rozière, David Lopez-Paz, Gabriel Synnaeve* · ([qbitai](https://www.qbitai.com/2024/05/139356.html))
- **Layer Skip: Enabling Early Exit Inference and Self-Speculative Decoding**, `arXiv, 2404.16710`, [arxiv](http://arxiv.org/abs/2404.16710v1), [pdf](http://arxiv.org/pdf/2404.16710v1.pdf), cication: [**-1**](None)

	 *Mostafa Elhoushi, Akshat Shrivastava, Diana Liskovich, Basil Hosmer, Bram Wasti, Liangzhen Lai, Anas Mahmoud, Bilge Acun, Saurabh Agarwal, Ahmed Roman*
- **BASS: Batched Attention-optimized Speculative Sampling**, `arXiv, 2404.15778`, [arxiv](http://arxiv.org/abs/2404.15778v1), [pdf](http://arxiv.org/pdf/2404.15778v1.pdf), cication: [**-1**](None)

	 *Haifeng Qian, Sujan Kumar Gonugondla, Sungsoo Ha, Mingyue Shang, Sanjay Krishna Gouda, Ramesh Nallapati, Sudipta Sengupta, Xiaofei Ma, Anoop Deoras*
- **XC-Cache: Cross-Attending to Cached Context for Efficient LLM Inference**, `arXiv, 2404.15420`, [arxiv](http://arxiv.org/abs/2404.15420v1), [pdf](http://arxiv.org/pdf/2404.15420v1.pdf), cication: [**-1**](None)

	 *João Monteiro, Étienne Marcotte, Pierre-André Noël, Valentina Zantedeschi, David Vázquez, Nicolas Chapados, Christopher Pal, Perouz Taslakian*
- **TriForce: Lossless Acceleration of Long Sequence Generation with
  Hierarchical Speculative Decoding**, `arXiv, 2404.11912`, [arxiv](http://arxiv.org/abs/2404.11912v1), [pdf](http://arxiv.org/pdf/2404.11912v1.pdf), cication: [**-1**](None)

	 *Hanshi Sun, Zhuoming Chen, Xinyu Yang, Yuandong Tian, Beidi Chen* · ([TriForce](https://github.com/Infini-AI-Lab/TriForce) - Infini-AI-Lab) ![Star](https://img.shields.io/github/stars/Infini-AI-Lab/TriForce.svg?style=social&label=Star)
- **Prepacking: A Simple Method for Fast Prefilling and Increased Throughput
  in Large Language Models**, `arXiv, 2404.09529`, [arxiv](http://arxiv.org/abs/2404.09529v1), [pdf](http://arxiv.org/pdf/2404.09529v1.pdf), cication: [**-1**](None)

	 *Siyan Zhao, Daniel Israel, Guy Van den Broeck, Aditya Grover* · ([prepacking](https://github.com/siyan-zhao/prepacking) - siyan-zhao) ![Star](https://img.shields.io/github/stars/siyan-zhao/prepacking.svg?style=social&label=Star)
- **DistServe: Disaggregating Prefill and Decoding for Goodput-optimized
  Large Language Model Serving**, `arXiv, 2401.09670`, [arxiv](http://arxiv.org/abs/2401.09670v1), [pdf](http://arxiv.org/pdf/2401.09670v1.pdf), cication: [**-1**](None)

	 *Yinmin Zhong, Shengyu Liu, Junda Chen, Jianbo Hu, Yibo Zhu, Xuanzhe Liu, Xin Jin, Hao Zhang* · ([hao-ai-lab.github](https://hao-ai-lab.github.io/blogs/distserve/))
- **Recurrent Drafter for Fast Speculative Decoding in Large Language Models**, `arXiv, 2403.09919`, [arxiv](http://arxiv.org/abs/2403.09919v1), [pdf](http://arxiv.org/pdf/2403.09919v1.pdf), cication: [**-1**](None)

	 *Aonan Zhang, Chong Wang, Yi Wang, Xuanyu Zhang, Yunfei Cheng*
- **Dynamic Memory Compression: Retrofitting LLMs for Accelerated Inference**, `arXiv, 2403.09636`, [arxiv](http://arxiv.org/abs/2403.09636v1), [pdf](http://arxiv.org/pdf/2403.09636v1.pdf), cication: [**-1**](None)

	 *Piotr Nawrot, Adrian Łańcucki, Marcin Chochowski, David Tarjan, Edoardo M. Ponti*
- **Keyformer: KV Cache Reduction through Key Tokens Selection for Efficient
  Generative Inference**, `arXiv, 2403.09054`, [arxiv](http://arxiv.org/abs/2403.09054v1), [pdf](http://arxiv.org/pdf/2403.09054v1.pdf), cication: [**-1**](None)

	 *Muhammad Adnan, Akhil Arunkumar, Gaurav Jain, Prashant J. Nair, Ilya Soloveychik, Purushotham Kamath*
- **Sequoia: Scalable, Robust, and Hardware-aware Speculative Decoding**, `arXiv, 2402.12374`, [arxiv](http://arxiv.org/abs/2402.12374v2), [pdf](http://arxiv.org/pdf/2402.12374v2.pdf), cication: [**-1**](None)

	 *Zhuoming Chen, Avner May, Ruslan Svirschevski, Yuhsun Huang, Max Ryabinin, Zhihao Jia, Beidi Chen* · ([Sequoia](https://github.com/Infini-AI-Lab/Sequoia) - Infini-AI-Lab) ![Star](https://img.shields.io/github/stars/Infini-AI-Lab/Sequoia.svg?style=social&label=Star)
- **An Image is Worth 1/2 Tokens After Layer 2: Plug-and-Play Inference
  Acceleration for Large Vision-Language Models**, `arXiv, 2403.06764`, [arxiv](http://arxiv.org/abs/2403.06764v1), [pdf](http://arxiv.org/pdf/2403.06764v1.pdf), cication: [**-1**](None)

	 *Liang Chen, Haozhe Zhao, Tianyu Liu, Shuai Bai, Junyang Lin, Chang Zhou, Baobao Chang*

	 · ([FastV](https://github.com/pkunlp-icler/FastV) - pkunlp-icler) ![Star](https://img.shields.io/github/stars/pkunlp-icler/FastV.svg?style=social&label=Star)
- **GEAR: An Efficient KV Cache Compression Recipe for Near-Lossless
  Generative Inference of LLM**, `arXiv, 2403.05527`, [arxiv](http://arxiv.org/abs/2403.05527v2), [pdf](http://arxiv.org/pdf/2403.05527v2.pdf), cication: [**-1**](None)

	 *Hao Kang, Qingru Zhang, Souvik Kundu, Geonhwa Jeong, Zaoxing Liu, Tushar Krishna, Tuo Zhao* · ([GEAR](https://github.com/HaoKang-Timmy/GEAR) - HaoKang-Timmy) ![Star](https://img.shields.io/github/stars/HaoKang-Timmy/GEAR.svg?style=social&label=Star)
- **DéjàVu: KV-cache Streaming for Fast, Fault-tolerant Generative LLM
  Serving**, `arXiv, 2403.01876`, [arxiv](http://arxiv.org/abs/2403.01876v1), [pdf](http://arxiv.org/pdf/2403.01876v1.pdf), cication: [**-1**](None)

	 *Foteini Strati, Sara Mcallister, Amar Phanishayee, Jakub Tarnawski, Ana Klimovic*
- **Think Big, Generate Quick: LLM-to-SLM for Fast Autoregressive Decoding**, `arXiv, 2402.16844`, [arxiv](http://arxiv.org/abs/2402.16844v1), [pdf](http://arxiv.org/pdf/2402.16844v1.pdf), cication: [**-1**](None)

	 *Benjamin Bergner, Andrii Skliar, Amelie Royer, Tijmen Blankevoort, Yuki Asano, Babak Ehteshami Bejnordi*
- **Ouroboros: Speculative Decoding with Large Model Enhanced Drafting**, `arXiv, 2402.13720`, [arxiv](http://arxiv.org/abs/2402.13720v1), [pdf](http://arxiv.org/pdf/2402.13720v1.pdf), cication: [**-1**](None)

	 *Weilin Zhao, Yuxiang Huang, Xu Han, Chaojun Xiao, Zhiyuan Liu, Maosong Sun* · ([Ouroboros](https://github.com/thunlp/Ouroboros) - thunlp) ![Star](https://img.shields.io/github/stars/thunlp/Ouroboros.svg?style=social&label=Star)
- **Speculative Streaming: Fast LLM Inference without Auxiliary Models**, `arXiv, 2402.11131`, [arxiv](http://arxiv.org/abs/2402.11131v1), [pdf](http://arxiv.org/pdf/2402.11131v1.pdf), cication: [**-1**](None)

	 *Nikhil Bhendawade, Irina Belousova, Qichen Fu, Henry Mason, Mohammad Rastegari, Mahyar Najibi*
- **Sequoia: Scalable, Robust, and Hardware-aware Speculative Decoding**, `arXiv, 2402.12374`, [arxiv](http://arxiv.org/abs/2402.12374v1), [pdf](http://arxiv.org/pdf/2402.12374v1.pdf), cication: [**-1**](None)

	 *Zhuoming Chen, Avner May, Ruslan Svirschevski, Yuhsun Huang, Max Ryabinin, Zhihao Jia, Beidi Chen*
- **Tandem Transformers for Inference Efficient LLMs**, `arXiv, 2402.08644`, [arxiv](http://arxiv.org/abs/2402.08644v1), [pdf](http://arxiv.org/pdf/2402.08644v1.pdf), cication: [**-1**](None)

	 *Aishwarya P S, Pranav Ajit Nair, Yashas Samaga, Toby Boyd, Sanjiv Kumar, Prateek Jain, Praneeth Netrapalli*
- **Fiddler: CPU-GPU Orchestration for Fast Inference of Mixture-of-Experts
  Models**, `arXiv, 2402.07033`, [arxiv](http://arxiv.org/abs/2402.07033v1), [pdf](http://arxiv.org/pdf/2402.07033v1.pdf), cication: [**-1**](None)

	 *Keisuke Kamahori, Yile Gu, Kan Zhu, Baris Kasikci* · ([fiddler](https://github.com/efeslab/fiddler) - efeslab) ![Star](https://img.shields.io/github/stars/efeslab/fiddler.svg?style=social&label=Star)
- **SubGen: Token Generation in Sublinear Time and Memory**, `arXiv, 2402.06082`, [arxiv](http://arxiv.org/abs/2402.06082v1), [pdf](http://arxiv.org/pdf/2402.06082v1.pdf), cication: [**-1**](None)

	 *Amir Zandieh, Insu Han, Vahab Mirrokni, Amin Karbasi*
- **Hydragen: High-Throughput LLM Inference with Shared Prefixes**, `arXiv, 2402.05099`, [arxiv](http://arxiv.org/abs/2402.05099v1), [pdf](http://arxiv.org/pdf/2402.05099v1.pdf), cication: [**-1**](None)

	 *Jordan Juravsky, Bradley Brown, Ryan Ehrlich, Daniel Y. Fu, Christopher Ré, Azalia Mirhoseini*
- [**flashinfer**](https://github.com/flashinfer-ai/flashinfer/) - flashinfer-ai ![Star](https://img.shields.io/github/stars/flashinfer-ai/flashinfer.svg?style=social&label=Star)

	 *FlashInfer: Kernel Library for LLM Serving*
- **EAGLE: Speculative Sampling Requires Rethinking Feature Uncertainty**, `arXiv, 2401.15077`, [arxiv](http://arxiv.org/abs/2401.15077v1), [pdf](http://arxiv.org/pdf/2401.15077v1.pdf), cication: [**-1**](None)

	 *Yuhui Li, Fangyun Wei, Chao Zhang, Hongyang Zhang*
- **BiTA: Bi-Directional Tuning for Lossless Acceleration in Large Language
  Models**, `arXiv, 2401.12522`, [arxiv](http://arxiv.org/abs/2401.12522v1), [pdf](http://arxiv.org/pdf/2401.12522v1.pdf), cication: [**-1**](None)

	 *Feng Lin, Hanling Yi, Hongbin Li, Yifan Yang, Xiaotian Yu, Guangming Lu, Rong Xiao*
- **Medusa: Simple LLM Inference Acceleration Framework with Multiple
  Decoding Heads**, `arXiv, 2401.10774`, [arxiv](http://arxiv.org/abs/2401.10774v1), [pdf](http://arxiv.org/pdf/2401.10774v1.pdf), cication: [**-1**](None)

	 *Tianle Cai, Yuhong Li, Zhengyang Geng, Hongwu Peng, Jason D. Lee, Deming Chen, Tri Dao*

	 · ([medusa](https://github.com/fasterdecoding/medusa) - fasterdecoding) ![Star](https://img.shields.io/github/stars/fasterdecoding/medusa.svg?style=social&label=Star)
- **DeepSpeed-FastGen: High-throughput Text Generation for LLMs via MII and
  DeepSpeed-Inference**, `arXiv, 2401.08671`, [arxiv](http://arxiv.org/abs/2401.08671v1), [pdf](http://arxiv.org/pdf/2401.08671v1.pdf), cication: [**-1**](None)

	 *Connor Holmes, Masahiro Tanaka, Michael Wyatt, Ammar Ahmad Awan, Jeff Rasley, Samyam Rajbhandari, Reza Yazdani Aminabadi, Heyang Qin, Arash Bakhtiari, Lev Kurilenko*
- **Inferflow: an Efficient and Highly Configurable Inference Engine for
  Large Language Models**, `arXiv, 2401.08294`, [arxiv](http://arxiv.org/abs/2401.08294v1), [pdf](http://arxiv.org/pdf/2401.08294v1.pdf), cication: [**-1**](None)

	 *Shuming Shi, Enbo Zhao, Deng Cai, Leyang Cui, Xinting Huang, Huayang Li* · ([inferflow](https://github.com/inferflow/inferflow) - inferflow) ![Star](https://img.shields.io/github/stars/inferflow/inferflow.svg?style=social&label=Star)
- [**PainlessInferenceAcceleration**](https://github.com/alipay/PainlessInferenceAcceleration) - alipay ![Star](https://img.shields.io/github/stars/alipay/PainlessInferenceAcceleration.svg?style=social&label=Star)
- **Unlocking Efficiency in Large Language Model Inference: A Comprehensive
  Survey of Speculative Decoding**, `arXiv, 2401.07851`, [arxiv](http://arxiv.org/abs/2401.07851v1), [pdf](http://arxiv.org/pdf/2401.07851v1.pdf), cication: [**-1**](None)

	 *Heming Xia, Zhe Yang, Qingxiu Dong, Peiyi Wang, Yongqi Li, Tao Ge, Tianyu Liu, Wenjie Li, Zhifang Sui*
- **Efficient LLM inference solution on Intel GPU**, `arXiv, 2401.05391`, [arxiv](http://arxiv.org/abs/2401.05391v1), [pdf](http://arxiv.org/pdf/2401.05391v1.pdf), cication: [**-1**](None)

	 *Hui Wu, Yi Gan, Feng Yuan, Jing Ma, Wei Zhu, Yutao Xu, Hong Zhu, Yuhua Zhu, Xiaoli Liu, Jinghui Gu*
- [**SwiftInfer**](https://github.com/hpcaitech/SwiftInfer) - hpcaitech ![Star](https://img.shields.io/github/stars/hpcaitech/SwiftInfer.svg?style=social&label=Star)

	 *Efficient AI Inference & Serving* · ([qbitai](https://www.qbitai.com/2024/01/112437.html))
- **Infinite-LLM: Efficient LLM Service for Long Context with DistAttention
  and Distributed KVCache**, `arXiv, 2401.02669`, [arxiv](http://arxiv.org/abs/2401.02669v1), [pdf](http://arxiv.org/pdf/2401.02669v1.pdf), cication: [**-1**](None)

	 *Bin Lin, Tao Peng, Chen Zhang, Minmin Sun, Lanbo Li, Hanyu Zhao, Wencong Xiao, Qi Xu, Xiafei Qiu, Shen Li*
- [**nitro**](https://github.com/janhq/nitro) - janhq ![Star](https://img.shields.io/github/stars/janhq/nitro.svg?style=social&label=Star)

	 *A fast, lightweight, embeddable inference engine to supercharge your apps with local AI. OpenAI-compatible API*
- [**jan**](https://github.com/janhq/jan) - janhq ![Star](https://img.shields.io/github/stars/janhq/jan.svg?style=social&label=Star)

	 *Jan is an open source alternative to ChatGPT that runs 100% offline on your computer*
- **Fairness in Serving Large Language Models**, `arXiv, 2401.00588`, [arxiv](http://arxiv.org/abs/2401.00588v1), [pdf](http://arxiv.org/pdf/2401.00588v1.pdf), cication: [**-1**](None)

	 *Ying Sheng, Shiyi Cao, Dacheng Li, Banghua Zhu, Zhuohan Li, Danyang Zhuo, Joseph E. Gonzalez, Ion Stoica* · ([s-lora](https://github.com/s-lora/s-lora) - s-lora) ![Star](https://img.shields.io/github/stars/s-lora/s-lora.svg?style=social&label=Star)
- [**tricksy**](https://github.com/austinsilveria/tricksy) - austinsilveria ![Star](https://img.shields.io/github/stars/austinsilveria/tricksy.svg?style=social&label=Star)

	 *Fast approximate inference on a single GPU with sparsity aware offloading*
- [**mixtral-offloading**](https://github.com/dvmazur/mixtral-offloading) - dvmazur ![Star](https://img.shields.io/github/stars/dvmazur/mixtral-offloading.svg?style=social&label=Star)

	 *Run Mixtral-8x7B models in Colab or consumer desktops*
- **LLM in a flash: Efficient Large Language Model Inference with Limited
  Memory**, `arXiv, 2312.11514`, [arxiv](http://arxiv.org/abs/2312.11514v1), [pdf](http://arxiv.org/pdf/2312.11514v1.pdf), cication: [**-1**](None)

	 *Keivan Alizadeh, Iman Mirzadeh, Dmitry Belenko, Karen Khatamifard, Minsik Cho, Carlo C Del Mundo, Mohammad Rastegari, Mehrdad Farajtabar*
- **Efficiently Programming Large Language Models using SGLang**, `arXiv, 2312.07104`, [arxiv](http://arxiv.org/abs/2312.07104v1), [pdf](http://arxiv.org/pdf/2312.07104v1.pdf), cication: [**-1**](None)

	 *Lianmin Zheng, Liangsheng Yin, Zhiqiang Xie, Jeff Huang, Chuyue Sun, Cody Hao Yu, Shiyi Cao, Christos Kozyrakis, Ion Stoica, Joseph E. Gonzalez* · ([sglang?tab=readme-ov-file](https://github.com/sgl-project/sglang?tab=readme-ov-file) - sgl-project) ![Star](https://img.shields.io/github/stars/sgl-project/sglang?tab=readme-ov-file.svg?style=social&label=Star) · ([lmsys](https://lmsys.org/blog/2024-01-17-sglang/))
- **PowerInfer: Fast Large Language Model Serving with a Consumer-grade GPU**, `arXiv, 2312.12456`, [arxiv](http://arxiv.org/abs/2312.12456v1), [pdf](http://arxiv.org/pdf/2312.12456v1.pdf), cication: [**-1**](None)

	 *Yixin Song, Zeyu Mi, Haotong Xie, Haibo Chen* · ([PowerInfer](https://github.com/SJTU-IPADS/PowerInfer) - SJTU-IPADS) ![Star](https://img.shields.io/github/stars/SJTU-IPADS/PowerInfer.svg?style=social&label=Star)
- **Cascade Speculative Drafting for Even Faster LLM Inference**, `arXiv, 2312.11462`, [arxiv](http://arxiv.org/abs/2312.11462v1), [pdf](http://arxiv.org/pdf/2312.11462v1.pdf), cication: [**-1**](None)

	 *Ziyi Chen, Xiaocong Yang, Jiacheng Lin, Chenkai Sun, Jie Huang, Kevin Chen-Chuan Chang*
- [**LLMLingua**](https://github.com/microsoft/LLMLingua) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/LLMLingua.svg?style=social&label=Star)

	 *To speed up LLMs' inference and enhance LLM's perceive of key information, compress the prompt and KV-Cache, which achieves up to 20x compression with minimal performance loss.*
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
- **Dissecting the Runtime Performance of the Training, Fine-tuning, and
  Inference of Large Language Models**, `arXiv, 2311.03687`, [arxiv](http://arxiv.org/abs/2311.03687v2), [pdf](http://arxiv.org/pdf/2311.03687v2.pdf), cication: [**-1**](None)

	 *Longteng Zhang, Xiang Liu, Zeyu Li, Xinglin Pan, Peijie Dong, Ruibo Fan, Rui Guo, Xin Wang, Qiong Luo, Shaohuai Shi*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-12-27-3))
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

	 · ([streaming-llm](https://github.com/mit-han-lab/streaming-llm) - mit-han-lab) ![Star](https://img.shields.io/github/stars/mit-han-lab/streaming-llm.svg?style=social&label=Star)

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
- [Accelerate Mixtral 8x7B with Speculative Decoding and Quantziation on Amazon SageMaker](https://www.philschmid.de/sagemaker-awq-medusa)
- [LLM Inference Provider Leaderboard](https://leaderboard.withmartian.com/)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-01-26-2))
- [Accelerating SD Turbo and SDXL Turbo Inference with ONNX Runtime and Olive](https://huggingface.co/blog/sdxl_ort_inference)
- [Unbelievable! Run 70B LLM Inference on a Single 4GB GPU with This NEW Technique | by Gavin Li | Nov, 2023 | AI Advances](https://ai.gopubby.com/unbelievable-run-70b-llm-inference-on-a-single-4gb-gpu-with-this-new-technique-93e2057c7eeb)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247628081&idx=1&sn=d507243342fa7c1ba59e18f909e847a4))
- [How to make LLMs go fast](https://vgel.me/posts/faster-inference/)
- [Sparse LLM Inference on CPU](https://huggingface.co/blog/mwitiderrick/llm-infrerence-on-cpu)
- [Optimizing your LLM in production](https://huggingface.co/blog/optimize-llm)
- [Speculative execution for LLMs is an excellent inference-time optimization.](https://twitter.com/karpathy/status/1697318534555336961)
- [**tvm_mlir_learn**](https://github.com/BBuf/tvm_mlir_learn) - BBuf ![Star](https://img.shields.io/github/stars/BBuf/tvm_mlir_learn.svg?style=social&label=Star)

	 *compiler learning resources collect.* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247527916&idx=2&sn=3ea2123d04509704e83486fe8a77ab14))
- [LLM生成延迟降低50%！DeepSpeed团队发布FastGen：动态SplitFuse技术，提升2.3倍有效吞吐量](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652413447&idx=5&sn=12a0246fd44783e7afc880f7751daa3d)
- [不用4个H100！340亿参数Code Llama在Mac可跑，每秒20个token，代码生成最拿手](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652371869&idx=3&sn=15310cc5305fa4c19edf318490c2dffc)｜Karpathy转赞
- [研究完llama.cpp，我发现手机跑大模型竟这么简单 | 机器之心](https://www.jiqizhixin.com/articles/2023-08-17-8)

## Mobile
- **Octopus v2: On-device language model for super agent**, `arXiv, 2404.01744`, [arxiv](http://arxiv.org/abs/2404.01744v2), [pdf](http://arxiv.org/pdf/2404.01744v2.pdf), cication: [**-1**](None)

	 *Wei Chen, Zhiyuan Li*
- **Transformer-Lite: High-efficiency Deployment of Large Language Models on
  Mobile Phone GPUs**, `arXiv, 2403.20041`, [arxiv](http://arxiv.org/abs/2403.20041v1), [pdf](http://arxiv.org/pdf/2403.20041v1.pdf), cication: [**-1**](None)

	 *Luchang Li, Sheng Qian, Jie Lu, Lunxi Yuan, Rui Wang, Qin Xie*
- **MobiLlama: Towards Accurate and Lightweight Fully Transparent GPT**, `arXiv, 2402.16840`, [arxiv](http://arxiv.org/abs/2402.16840v1), [pdf](http://arxiv.org/pdf/2402.16840v1.pdf), cication: [**-1**](None)

	 *Omkar Thawakar, Ashmal Vayani, Salman Khan, Hisham Cholakal, Rao M. Anwer, Michael Felsberg, Tim Baldwin, Eric P. Xing, Fahad Shahbaz Khan*

	 · ([MobiLlama](https://github.com/mbzuai-oryx/MobiLlama) - mbzuai-oryx) ![Star](https://img.shields.io/github/stars/mbzuai-oryx/MobiLlama.svg?style=social&label=Star)
- **MobileLLM: Optimizing Sub-billion Parameter Language Models for
  On-Device Use Cases**, `arXiv, 2402.14905`, [arxiv](http://arxiv.org/abs/2402.14905v1), [pdf](http://arxiv.org/pdf/2402.14905v1.pdf), cication: [**-1**](None)

	 *Zechun Liu, Changsheng Zhao, Forrest Iandola, Chen Lai, Yuandong Tian, Igor Fedorov, Yunyang Xiong, Ernie Chang, Yangyang Shi, Raghuraman Krishnamoorthi*
- **MobileVLM : A Fast, Reproducible and Strong Vision Language Assistant
  for Mobile Devices**, `arXiv, 2312.16886`, [arxiv](http://arxiv.org/abs/2312.16886v1), [pdf](http://arxiv.org/pdf/2312.16886v1.pdf), cication: [**-1**](None)

	 *Xiangxiang Chu, Limeng Qiao, Xinyang Lin, Shuang Xu, Yang Yang, Yiming Hu, Fei Wei, Xinyu Zhang, Bo Zhang, Xiaolin Wei* · ([MobileVLM](https://github.com/Meituan-AutoML/MobileVLM) - Meituan-AutoML) ![Star](https://img.shields.io/github/stars/Meituan-AutoML/MobileVLM.svg?style=social&label=Star)
- 
- [**mlc-llm**](https://github.com/mlc-ai/mlc-llm) - mlc-ai ![Star](https://img.shields.io/github/stars/mlc-ai/mlc-llm.svg?style=social&label=Star)

	 *Enable everyone to develop, optimize and deploy AI models natively on everyone's devices.* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-05-04)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-05-2))

## Toolkits
- [**transformer-heads**](https://github.com/center-for-humans-and-machines/transformer-heads) - center-for-humans-and-machines ![Star](https://img.shields.io/github/stars/center-for-humans-and-machines/transformer-heads.svg?style=social&label=Star)

	 *Toolkit for attaching, training, saving and loading of new heads for transformer models*
- [**quanto**](https://github.com/huggingface/quanto) - huggingface ![Star](https://img.shields.io/github/stars/huggingface/quanto.svg?style=social&label=Star)

	 *A pytorch Quantization Toolkit* · ([huggingface](https://huggingface.co/blog/quanto-introduction))
- [**fsdp_qlora**](https://github.com/AnswerDotAI/fsdp_qlora) - AnswerDotAI ![Star](https://img.shields.io/github/stars/AnswerDotAI/fsdp_qlora.svg?style=social&label=Star)

	 *Training LLMs with QLoRA + FSDP* · ([answer](https://www.answer.ai/posts/2024-03-06-fsdp-qlora.html#a-first-step)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247629628&idx=6&sn=a37c12303d04dd1dcabed6d02616e7be))
- [**GPTFast**](https://github.com/MDK8888/GPTFast) - MDK8888 ![Star](https://img.shields.io/github/stars/MDK8888/GPTFast.svg?style=social&label=Star)

	 *Accelerate your Hugging Face Transformers 6-7x. Native to Hugging Face and PyTorch.*
- [**vllm**](https://github.com/vllm-project/vllm/pull/1804) - vllm-project ![Star](https://img.shields.io/github/stars/vllm-project/vllm.svg?style=social&label=Star)
- [**lorax**](https://github.com/predibase/lorax) - predibase ![Star](https://img.shields.io/github/stars/predibase/lorax.svg?style=social&label=Star)

	 *Multi-LoRA inference server that scales to 1000s of fine-tuned LLMs*
- [Winners 🏆 | NeurIPS Large Language Model Efficiency Challenge:1 LLM + 1GPU + 1Day](https://llm-efficiency-challenge.github.io/leaderboard)
- [**gigaGPT**](https://github.com/Cerebras/gigaGPT) - Cerebras ![Star](https://img.shields.io/github/stars/Cerebras/gigaGPT.svg?style=social&label=Star)

	 *a small code base for training large models* · ([cerebras](https://www.cerebras.net/blog/introducing-gigagpt-gpt-3-sized-models-in-565-lines-of-code))
- [**EAGLE**](https://github.com/SafeAILab/EAGLE) - SafeAILab ![Star](https://img.shields.io/github/stars/SafeAILab/EAGLE.svg?style=social&label=Star)

	 *EAGLE: Lossless Acceleration of LLM Decoding by Feature Extrapolation* · ([sites.google](https://sites.google.com/view/eagle-llm))

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-12-14-2))
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
- **RecurrentGemma: Moving Past Transformers for Efficient Open Language
  Models**, `arXiv, 2404.07839`, [arxiv](http://arxiv.org/abs/2404.07839v1), [pdf](http://arxiv.org/pdf/2404.07839v1.pdf), cication: [**-1**](None)

	 *Aleksandar Botev, Soham De, Samuel L Smith, Anushan Fernando, George-Cristian Muraru, Ruba Haroun, Leonard Berrada, Razvan Pascanu, Pier Giuseppe Sessa, Robert Dadashi* · ([recurrentgemma](https://github.com/google-deepmind/recurrentgemma) - google-deepmind) ![Star](https://img.shields.io/github/stars/google-deepmind/recurrentgemma.svg?style=social&label=Star)
- [8bit HippoAttention: Up to 3X Faster Compared to FlashAttentionV2 | by HippoML Blog | Medium](https://blog.hippoml.com/8bit-hippoattention-up-to-3x-faster-compared-to-flashattentionv2-8f9def90b482)
- [**LASP**](https://github.com/OpenNLPLab/LASP?tab=readme-ov-file) - OpenNLPLab ![Star](https://img.shields.io/github/stars/OpenNLPLab/LASP.svg?style=social&label=Star)

	 *Linear Attention Sequence Parallelism (LASP)*
- **Simple linear attention language models balance the recall-throughput
  tradeoff**, `arXiv, 2402.18668`, [arxiv](http://arxiv.org/abs/2402.18668v1), [pdf](http://arxiv.org/pdf/2402.18668v1.pdf), cication: [**-1**](None)

	 *Simran Arora, Sabri Eyuboglu, Michael Zhang, Aman Timalsina, Silas Alberti, Dylan Zinsley, James Zou, Atri Rudra, Christopher Ré*

	 · ([based](https://github.com/hazyresearch/based) - hazyresearch) ![Star](https://img.shields.io/github/stars/hazyresearch/based.svg?style=social&label=Star)
- **Griffin: Mixing Gated Linear Recurrences with Local Attention for
  Efficient Language Models**, `arXiv, 2402.19427`, [arxiv](http://arxiv.org/abs/2402.19427v1), [pdf](http://arxiv.org/pdf/2402.19427v1.pdf), cication: [**-1**](None)

	 *Soham De, Samuel L. Smith, Anushan Fernando, Aleksandar Botev, George Cristian-Muraru, Albert Gu, Ruba Haroun, Leonard Berrada, Yutian Chen, Srivatsan Srinivasan*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-03-04-7))

	 · ([huggingface](https://huggingface.co/google/recurrentgemma-2b-it)) · ([twitter](https://twitter.com/rohanpaul_ai/status/1777747790564589844?utm_source=ainews&utm_medium=email&utm_campaign=ainews-gemini-pro-and-gpt4t-vision-go-ga-on-the))
- **ChunkAttention: Efficient Self-Attention with Prefix-Aware KV Cache and
  Two-Phase Partition**, `arXiv, 2402.15220`, [arxiv](http://arxiv.org/abs/2402.15220v1), [pdf](http://arxiv.org/pdf/2402.15220v1.pdf), cication: [**-1**](None)

	 *Lu Ye, Ze Tao, Yong Huang, Yang Li*
- **Linear Transformers are Versatile In-Context Learners**, `arXiv, 2402.14180`, [arxiv](http://arxiv.org/abs/2402.14180v1), [pdf](http://arxiv.org/pdf/2402.14180v1.pdf), cication: [**-1**](None)

	 *Max Vladymyrov, Johannes von Oswald, Mark Sandler, Rong Ge*
- **The Hedgehog & the Porcupine: Expressive Linear Attentions with Softmax
  Mimicry**, `arXiv, 2402.04347`, [arxiv](http://arxiv.org/abs/2402.04347v1), [pdf](http://arxiv.org/pdf/2402.04347v1.pdf), cication: [**-1**](None)

	 *Michael Zhang, Kush Bhatia, Hermann Kumbong, Christopher Ré*
- [FireAttention — Serving Open Source Models 4x faster than vLLM by quantizing with \~no tradeoffs | by Fireworks.ai | Jan, 2024 | Medium](https://blog.fireworks.ai/fireattention-serving-open-source-models-4x-faster-than-vllm-by-quantizing-with-no-tradeoffs-a29a85ad28d0)
- [**flash-linear-attention**](https://github.com/sustcsonglin/flash-linear-attention) - sustcsonglin ![Star](https://img.shields.io/github/stars/sustcsonglin/flash-linear-attention.svg?style=social&label=Star)

	 *Fast implementations of causal linear attention for autogressive language modeling (Pytorch)*
- **PanGu-$π$: Enhancing Language Model Architectures via Nonlinearity
  Compensation**, `arXiv, 2312.17276`, [arxiv](http://arxiv.org/abs/2312.17276v1), [pdf](http://arxiv.org/pdf/2312.17276v1.pdf), cication: [**-1**](None)

	 *Yunhe Wang, Hanting Chen, Yehui Tang, Tianyu Guo, Kai Han, Ying Nie, Xutao Wang, Hailin Hu, Zheyuan Bai, Yun Wang*
- **Agent Attention: On the Integration of Softmax and Linear Attention**, `arXiv, 2312.08874`, [arxiv](http://arxiv.org/abs/2312.08874v1), [pdf](http://arxiv.org/pdf/2312.08874v1.pdf), cication: [**-1**](None)

	 *Dongchen Han, Tianzhu Ye, Yizeng Han, Zhuofan Xia, Shiji Song, Gao Huang* · ([agent-attention](https://github.com/leaplabthu/agent-attention?tab=readme-ov-file) - leaplabthu) ![Star](https://img.shields.io/github/stars/leaplabthu/agent-attention?tab=readme-ov-file.svg?style=social&label=Star)
- **Weight subcloning: direct initialization of transformers using larger
  pretrained ones**, `arXiv, 2312.09299`, [arxiv](http://arxiv.org/abs/2312.09299v1), [pdf](http://arxiv.org/pdf/2312.09299v1.pdf), cication: [**-1**](None)

	 *Mohammad Samragh, Mehrdad Farajtabar, Sachin Mehta, Raviteja Vemulapalli, Fartash Faghri, Devang Naik, Oncel Tuzel, Mohammad Rastegari*
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

## Hardware
- **Adding NVMe SSDs to Enable and Accelerate 100B Model Fine-tuning on a
  Single GPU**, `arXiv, 2403.06504`, [arxiv](http://arxiv.org/abs/2403.06504v1), [pdf](http://arxiv.org/pdf/2403.06504v1.pdf), cication: [**-1**](None)

	 *Changyue Liao, Mo Sun, Zihan Yang, Kaiqi Chen, Binhang Yuan, Fei Wu, Zeke Wang*
- **Progressive Gradient Flow for Robust N:M Sparsity Training in
  Transformers**, `arXiv, 2402.04744`, [arxiv](http://arxiv.org/abs/2402.04744v1), [pdf](http://arxiv.org/pdf/2402.04744v1.pdf), cication: [**-1**](None)

	 *Abhimanyu Rajeshkumar Bambhaniya, Amir Yazdanbakhsh, Suvinay Subramanian, Sheng-Chun Kao, Shivani Agrawal, Utku Evci, Tushar Krishna*
- **FlightLLM: Efficient Large Language Model Inference with a Complete
  Mapping Flow on FPGAs**, `arXiv, 2401.03868`, [arxiv](http://arxiv.org/abs/2401.03868v2), [pdf](http://arxiv.org/pdf/2401.03868v2.pdf), cication: [**-1**](None)

	 *Shulin Zeng, Jun Liu, Guohao Dai, Xinhao Yang, Tianyu Fu, Hongyi Wang, Wenheng Ma, Hanbo Sun, Shiyao Li, Zixiao Huang*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-01-10-4))

- [大模型最快推理芯片一夜易主：每秒500tokens干翻GPU！谷歌TPU人马打造](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247542664&idx=1&sn=bbeafd798d4f207c6871a05e8d26cdc5)

##  Other
- [How to make LLMs go fast](https://vgel.me/posts/faster-inference/?continueFlag=dc32042695bb7e31fb9280e21ab25f8c)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-02-14-2))
- [Make LLM Fine-tuning 2x faster with Unsloth and 🤗 TRL](https://huggingface.co/blog/unsloth-trl)
- [Schedule | NeurIPS Large Language Model Efficiency Challenge:1 LLM + 1GPU + 1Day](https://llm-efficiency-challenge.github.io/schedule)
- [Dynamic LoRA loading for better performance and optimized resource usage](https://huggingface.co/blog/lora-adapters-dynamic-loading)
## Courses
- [Code LoRA from Scratch - a Lightning Studio by sebastian](https://lightning.ai/lightning-ai/studios/code-lora-from-scratch?view=public&section=all)
### EfficientML
- [EfficientML.ai Lecture, Fall 2023, MIT 6.5940 - YouTube](https://www.youtube.com/playlist?list=PL80kAHvQbh-pT4lCkDT53zT8DKmhE0idB)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-25-15)) · ([bilibili](https://www.bilibili.com/video/BV1W14y1C7jv/?spm_id_from=333.999.0.0&vd_source=1453a06a1e0b377f5c40946333b4423a)) · ([dropbox](https://www.dropbox.com/sh/0ftluqbd1afzqpy/AADqxwkYrt1FbGnSQ4KP3Kpva?dl=0))

## Extra Reference
- [**Awesome-Knowledge-Distillation-of-LLMs**](https://github.com/Tebmer/Awesome-Knowledge-Distillation-of-LLMs) - Tebmer ![Star](https://img.shields.io/github/stars/Tebmer/Awesome-Knowledge-Distillation-of-LLMs.svg?style=social&label=Star)

	 *This repository collects papers for "A Survey on Knowledge Distillation of Large Language Models". We break down KD into Knowledge Elicitation and Distillation Algorithms, and explore the Skill & Vertical Distillation of LLMs.*
- [**Awesome-LLM-Compression**](https://github.com/HuangOwen/Awesome-LLM-Compression) - HuangOwen ![Star](https://img.shields.io/github/stars/HuangOwen/Awesome-LLM-Compression.svg?style=social&label=Star)

	 *Awesome LLM compression research papers and tools.*