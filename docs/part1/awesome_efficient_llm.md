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
- **A Survey of Low-bit Large Language Models: Basics, Systems, and
  Algorithms**, `arXiv, 2409.16694`, [arxiv](http://arxiv.org/abs/2409.16694v2), [pdf](http://arxiv.org/pdf/2409.16694v2.pdf), cication: [**-1**](None)

	 *Ruihao Gong, Yifu Ding, Zining Wang, Chengtao Lv, Xingyu Zheng, Jinyang Du, Haotong Qin, Jinyang Guo, Michele Magno, Xianglong Liu*
- **Small Language Models: Survey, Measurements, and Insights**, `arXiv, 2409.15790`, [arxiv](http://arxiv.org/abs/2409.15790v1), [pdf](http://arxiv.org/pdf/2409.15790v1.pdf), cication: [**-1**](None)

	 *Zhenyan Lu, Xiang Li, Dongqi Cai, Rongjie Yi, Fangming Liu, Xiwen Zhang, Nicholas D. Lane, Mengwei Xu*
- **Hardware Acceleration of LLMs: A comprehensive survey and comparison**, `arXiv, 2409.03384`, [arxiv](http://arxiv.org/abs/2409.03384v1), [pdf](http://arxiv.org/pdf/2409.03384v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=270840162181392146&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Nikoletta Koilia, Christoforos Kachris*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-09-20-4))
- **On-Device Language Models: A Comprehensive Review**, `arXiv, 2409.00088`, [arxiv](http://arxiv.org/abs/2409.00088v2), [pdf](http://arxiv.org/pdf/2409.00088v2.pdf), cication: [**-1**](None)

	 *Jiajun Xu, Zhiyuan Li, Wei Chen, Qun Wang, Xin Gao, Qi Cai, Ziyuan Ling*
- **Attention Heads of Large Language Models: A Survey**, `arXiv, 2409.03752`, [arxiv](http://arxiv.org/abs/2409.03752v1), [pdf](http://arxiv.org/pdf/2409.03752v1.pdf), cication: [**-1**](None)

	 *Zifan Zheng, Yezhaohui Wang, Yuxin Huang, Shichao Song, Bo Tang, Feiyu Xiong, Zhiyu Li* · ([Awesome-Attention-Heads](https://github.com/IAAR-Shanghai/Awesome-Attention-Heads) - IAAR-Shanghai) ![Star](https://img.shields.io/github/stars/IAAR-Shanghai/Awesome-Attention-Heads.svg?style=social&label=Star)
- **What is the Role of Small Models in the LLM Era: A Survey**, `arXiv, 2409.06857`, [arxiv](http://arxiv.org/abs/2409.06857v2), [pdf](http://arxiv.org/pdf/2409.06857v2.pdf), cication: [**-1**](None)

	 *Lihu Chen, Gaël Varoquaux* · ([role_of_small_models](https://github.com/tigerchen52/role_of_small_models) - tigerchen52) ![Star](https://img.shields.io/github/stars/tigerchen52/role_of_small_models.svg?style=social&label=Star)
- **Achieving Peak Performance for Large Language Models: A Systematic
  Review**, `arXiv, 2409.04833`, [arxiv](http://arxiv.org/abs/2409.04833v1), [pdf](http://arxiv.org/pdf/2409.04833v1.pdf), cication: [**-1**](None)

	 *Zhyar Rzgar K Rostam, Sándor Szénási, Gábor Kertész*
- **Parameter-Efficient Fine-Tuning for Large Models: A Comprehensive Survey**, `arXiv, 2403.14608`, [arxiv](http://arxiv.org/abs/2403.14608v5), [pdf](http://arxiv.org/pdf/2403.14608v5.pdf), cication: [**18**](https://scholar.google.com/scholar?cites=9566826564470542329&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zeyu Han, Chao Gao, Jinyang Liu, Jeff Zhang, Sai Qian Zhang*
- **A Comprehensive Survey of Accelerated Generation Techniques in Large
  Language Models**, `arXiv, 2405.13019`, [arxiv](http://arxiv.org/abs/2405.13019v1), [pdf](http://arxiv.org/pdf/2405.13019v1.pdf), cication: [**-1**](None)

	 *Mahsa Khoshnoodi, Vinija Jain, Mingye Gao, Malavika Srikanth, Aman Chadha*
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
- **Flexora: Flexible Low Rank Adaptation for Large Language Models**, `arXiv, 2408.10774`, [arxiv](http://arxiv.org/abs/2408.10774v2), [pdf](http://arxiv.org/pdf/2408.10774v2.pdf), cication: [**-1**](None)

	 *Chenxing Wei, Yao Shu, Ying Tiffany He, Fei Richard Yu* · ([x](https://x.com/rohanpaul_ai/status/1826733730746282290))
- **LoRA Learns Less and Forgets Less**, `arXiv, 2405.09673`, [arxiv](http://arxiv.org/abs/2405.09673v1), [pdf](http://arxiv.org/pdf/2405.09673v1.pdf), cication: [**17**](https://scholar.google.com/scholar?cites=11449236051528835430&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Dan Biderman, Jose Gonzalez Ortiz, Jacob Portes, Mansheej Paul, Philip Greengard, Connor Jennings, Daniel King, Sam Havens, Vitaliy Chiley, Jonathan Frankle*
- **Let the Expert Stick to His Last: Expert-Specialized Fine-Tuning for
  Sparse Architectural Large Language Models**, `arXiv, 2407.01906`, [arxiv](http://arxiv.org/abs/2407.01906v2), [pdf](http://arxiv.org/pdf/2407.01906v2.pdf), cication: [**-1**](None)

	 *Zihan Wang, Deli Chen, Damai Dai, Runxin Xu, Zhuoshu Li, Y. Wu*
- **OLoRA: Orthonormal Low-Rank Adaptation of Large Language Models**, `arXiv, 2406.01775`, [arxiv](http://arxiv.org/abs/2406.01775v1), [pdf](http://arxiv.org/pdf/2406.01775v1.pdf), cication: [**-1**](None)

	 *Kerim Büyükakyüz*
- **VeLoRA: Memory Efficient Training using Rank-1 Sub-Token Projections**, `arXiv, 2405.17991`, [arxiv](http://arxiv.org/abs/2405.17991v1), [pdf](http://arxiv.org/pdf/2405.17991v1.pdf), cication: [**-1**](None)

	 *Roy Miles, Pradyumna Reddy, Ismail Elezi, Jiankang Deng*
- **$\textit{Trans-LoRA}$: towards data-free Transferable Parameter
  Efficient Finetuning**, `arXiv, 2405.17258`, [arxiv](http://arxiv.org/abs/2405.17258v1), [pdf](http://arxiv.org/pdf/2405.17258v1.pdf), cication: [**-1**](None)

	 *Runqian Wang, Soumya Ghosh, David Cox, Diego Antognini, Aude Oliva, Rogerio Feris, Leonid Karlinsky*
- **Towards Modular LLMs by Building and Reusing a Library of LoRAs**, `arXiv, 2405.11157`, [arxiv](http://arxiv.org/abs/2405.11157v1), [pdf](http://arxiv.org/pdf/2405.11157v1.pdf), cication: [**-1**](None)

	 *Oleksiy Ostapenko, Zhan Su, Edoardo Maria Ponti, Laurent Charlin, Nicolas Le Roux, Matheus Pereira, Lucas Caccia, Alessandro Sordoni*
- **MoRA: High-Rank Updating for Parameter-Efficient Fine-Tuning**, `arXiv, 2405.12130`, [arxiv](http://arxiv.org/abs/2405.12130v1), [pdf](http://arxiv.org/pdf/2405.12130v1.pdf), cication: [**-1**](None)

	 *Ting Jiang, Shaohan Huang, Shengyue Luo, Zihan Zhang, Haizhen Huang, Furu Wei, Weiwei Deng, Feng Sun, Qi Zhang, Deqing Wang*
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
- [TGI Multi-LoRA: Deploy Once, Serve 30 Models](https://huggingface.co/blog/multi-lora-serving)
- [Finetuning LLMs with LoRA and QLoRA: Insights from Hundreds of Experiments - Lightning AI](https://lightning.ai/pages/community/lora-insights/)
-  [instruction tuning experiments with LoRA/QLoRA](https://twitter.com/cwolferesearch/status/1788998798414410032)
- [LoRA及其变体概述：LoRA, DoRA, AdaLoRA, Delta-LoRA](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247632908&idx=2&sn=f2daa489741ccc4a7f8f9c4c178c4740)

## Quantization
### Survey
- **A Performance Evaluation of a Quantized Large Language Model on Various
  Smartphones**, `arXiv, 2312.12472`, [arxiv](http://arxiv.org/abs/2312.12472v1), [pdf](http://arxiv.org/pdf/2312.12472v1.pdf), cication: [**-1**](None)

	 *Tolga Çöplü, Marc Loedi, Arto Bendiken, Mykhailo Makohin, Joshua J. Bouw, Stephen Cobb*
- **A Survey on Model Compression for Large Language Models**, `arXiv, 2308.07633`, [arxiv](http://arxiv.org/abs/2308.07633v3), [pdf](http://arxiv.org/pdf/2308.07633v3.pdf), cication: [**-1**](None)

	 *Xunyu Zhu, Jian Li, Yong Liu, Can Ma, Weiping Wang* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-26-5))

### Papers
- **VPTQ: Extreme Low-bit Vector Post-Training Quantization for Large
  Language Models**, `arXiv, 2409.17066`, [arxiv](http://arxiv.org/abs/2409.17066v1), [pdf](http://arxiv.org/pdf/2409.17066v1.pdf), cication: [**-1**](None)

	 *Yifei Liu, Jicheng Wen, Yang Wang, Shengyu Ye, Li Lyna Zhang, Ting Cao, Cheng Li, Mao Yang* · ([VPTQ](https://github.com/microsoft/VPTQ) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/VPTQ.svg?style=social&label=Star)
- **MobileQuant: Mobile-friendly Quantization for On-device Language Models**, `arXiv, 2408.13933`, [arxiv](http://arxiv.org/abs/2408.13933v1), [pdf](http://arxiv.org/pdf/2408.13933v1.pdf), cication: [**-1**](None)

	 *Fuwen Tan, Royson Lee, Łukasz Dudziak, Shell Xu Hu, Sourav Bhattacharya, Timothy Hospedales, Georgios Tzimiropoulos, Brais Martinez* · ([MobileQuant](https://github.com/saic-fi/MobileQuant) - saic-fi) ![Star](https://img.shields.io/github/stars/saic-fi/MobileQuant.svg?style=social&label=Star)
- **LLMC: Benchmarking Large Language Model Quantization with a Versatile
  Compression Toolkit**, `arXiv, 2405.06001`, [arxiv](http://arxiv.org/abs/2405.06001v2), [pdf](http://arxiv.org/pdf/2405.06001v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=8755898344620001632&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ruihao Gong, Yang Yong, Shiqiao Gu, Yushi Huang, Chentao Lv, Yunchen Zhang, Xianglong Liu, Dacheng Tao* · ([llmc](https://github.com/modeltc/llmc) - modeltc) ![Star](https://img.shields.io/github/stars/modeltc/llmc.svg?style=social&label=Star)
- **Spectra: A Comprehensive Study of Ternary, Quantized, and FP16 Language
  Models**, `arXiv, 2407.12327`, [arxiv](http://arxiv.org/abs/2407.12327v1), [pdf](http://arxiv.org/pdf/2407.12327v1.pdf), cication: [**-1**](None)

	 *Ayush Kaushal, Tejas Pandey, Tejas Vaidhya, Aaryan Bhagat, Irina Rish*
- **Q-Sparse: All Large Language Models can be Fully Sparsely-Activated**, `arXiv, 2407.10969`, [arxiv](http://arxiv.org/abs/2407.10969v1), [pdf](http://arxiv.org/pdf/2407.10969v1.pdf), cication: [**-1**](None)

	 *Hongyu Wang, Shuming Ma, Ruiping Wang, Furu Wei*
- **Q-GaLore: Quantized GaLore with INT4 Projection and Layer-Adaptive
  Low-Rank Gradients**, `arXiv, 2407.08296`, [arxiv](http://arxiv.org/abs/2407.08296v1), [pdf](http://arxiv.org/pdf/2407.08296v1.pdf), cication: [**-1**](None)

	 *Zhenyu Zhang, Ajay Jaiswal, Lu Yin, Shiwei Liu, Jiawei Zhao, Yuandong Tian, Zhangyang Wang*
- **4-bit Shampoo for Memory-Efficient Network Training**, `arXiv, 2405.18144`, [arxiv](http://arxiv.org/abs/2405.18144v1), [pdf](http://arxiv.org/pdf/2405.18144v1.pdf), cication: [**-1**](None)

	 *Sike Wang, Jia Li, Pan Zhou, Hua Huang*
- **QServe: W4A8KV4 Quantization and System Co-design for Efficient LLM
  Serving**, `arXiv, 2405.04532`, [arxiv](http://arxiv.org/abs/2405.04532v1), [pdf](http://arxiv.org/pdf/2405.04532v1.pdf), cication: [**-1**](None)

	 *Yujun Lin, Haotian Tang, Shang Yang, Zhekai Zhang, Guangxuan Xiao, Chuang Gan, Song Han* · ([qserve](https://github.com/mit-han-lab/qserve) - mit-han-lab) ![Star](https://img.shields.io/github/stars/mit-han-lab/qserve.svg?style=social&label=Star)
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
- [A Visual Guide to Quantization - by Maarten Grootendorst](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-quantization)
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
- [Do you want to learn about quantization? Here are five free resources to get started](https://x.com/osanseviero/status/1820124474965897466?utm_source=ainews&utm_medium=email&utm_campaign=ainews-how-carlini-uses-ai)
- [Overview of natively supported quantization schemes in 🤗 Transformers](https://huggingface.co/blog/overview-quantization-transformers)
- [Making LLMs lighter with AutoGPTQ and transformers](https://huggingface.co/blog/gptq-integration)
- [TheBloke (Tom Jobbins)](https://huggingface.co/TheBloke)
- [Quantization](https://huggingface.co/docs/accelerate/usage_guides/quantization)

## Distillation
- **LLM Pruning and Distillation in Practice: The Minitron Approach**, `arXiv, 2408.11796`, [arxiv](http://arxiv.org/abs/2408.11796v2), [pdf](http://arxiv.org/pdf/2408.11796v2.pdf), cication: [**-1**](None)

	 *Sharath Turuvekere Sreenivas, Saurav Muralidharan, Raviraj Joshi, Marcin Chochowski, Mostofa Patwary, Mohammad Shoeybi, Bryan Catanzaro, Jan Kautz, Pavlo Molchanov*
- [DistillKit - Arcee-AI](https://arcee-ai-distillkit.my.canva.site/)

	 · ([DistillKit](https://github.com/arcee-ai/DistillKit) - arcee-ai) ![Star](https://img.shields.io/github/stars/arcee-ai/DistillKit.svg?style=social&label=Star)
- **PLaD: Preference-based Large Language Model Distillation with
  Pseudo-Preference Pairs**, `arXiv, 2406.02886`, [arxiv](http://arxiv.org/abs/2406.02886v2), [pdf](http://arxiv.org/pdf/2406.02886v2.pdf), cication: [**-1**](None)

	 *Rongzhi Zhang, Jiaming Shen, Tianqi Liu, Haorui Wang, Zhen Qin, Feng Han, Jialu Liu, Simon Baumgartner, Michael Bendersky, Chao Zhang*
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
- **Inheritune: Training Smaller Yet More Attentive Language Models**, `arXiv, 2404.08634`, [arxiv](http://arxiv.org/abs/2404.08634v2), [pdf](http://arxiv.org/pdf/2404.08634v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=3581681678753917814&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Sunny Sanyal, Ravid Shwartz-Ziv, Alexandros G. Dimakis, Sujay Sanghavi* · ([LLM-Inheritune](https://github.com/sanyalsunny111/LLM-Inheritune) - sanyalsunny111) ![Star](https://img.shields.io/github/stars/sanyalsunny111/LLM-Inheritune.svg?style=social&label=Star) · ([x](https://x.com/ziv_ravid/status/1844755154383311007))
- **MaskLLM: Learnable Semi-Structured Sparsity for Large Language Models**, `arXiv, 2409.17481`, [arxiv](http://arxiv.org/abs/2409.17481v1), [pdf](http://arxiv.org/pdf/2409.17481v1.pdf), cication: [**-1**](None)

	 *Gongfan Fang, Hongxu Yin, Saurav Muralidharan, Greg Heinrich, Jeff Pool, Jan Kautz, Pavlo Molchanov, Xinchao Wang* · ([MaskLLM](https://github.com/NVlabs/MaskLLM) - NVlabs) ![Star](https://img.shields.io/github/stars/NVlabs/MaskLLM.svg?style=social&label=Star)
- **Training-Free Activation Sparsity in Large Language Models**, `arXiv, 2408.14690`, [arxiv](http://arxiv.org/abs/2408.14690v1), [pdf](http://arxiv.org/pdf/2408.14690v1.pdf), cication: [**-1**](None)

	 *James Liu, Pragaash Ponnusamy, Tianle Cai, Han Guo, Yoon Kim, Ben Athiwaratkun* · ([teal](https://github.com/fasterdecoding/teal) - fasterdecoding) ![Star](https://img.shields.io/github/stars/fasterdecoding/teal.svg?style=social&label=Star)
- **Compact Language Models via Pruning and Knowledge Distillation**, `arXiv, 2407.14679`, [arxiv](http://arxiv.org/abs/2407.14679v1), [pdf](http://arxiv.org/pdf/2407.14679v1.pdf), cication: [**-1**](None)

	 *Saurav Muralidharan, Sharath Turuvekere Sreenivas, Raviraj Joshi, Marcin Chochowski, Mostofa Patwary, Mohammad Shoeybi, Bryan Catanzaro, Jan Kautz, Pavlo Molchanov* · ([minitron](https://github.com/nvlabs/minitron) - nvlabs) ![Star](https://img.shields.io/github/stars/nvlabs/minitron.svg?style=social&label=Star)
- **ShiftAddLLM: Accelerating Pretrained LLMs via Post-Training
  Multiplication-Less Reparameterization**, `arXiv, 2406.05981`, [arxiv](http://arxiv.org/abs/2406.05981v2), [pdf](http://arxiv.org/pdf/2406.05981v2.pdf), cication: [**-1**](None)

	 *Haoran You, Yipin Guo, Yichao Fu, Wei Zhou, Huihong Shi, Xiaofan Zhang, Souvik Kundu, Amir Yazdanbakhsh, Yingyan, Lin* · ([ShiftAddLLM](https://github.com/GATECH-EIC/ShiftAddLLM) - GATECH-EIC) ![Star](https://img.shields.io/github/stars/GATECH-EIC/ShiftAddLLM.svg?style=social&label=Star)

- **Scalable MatMul-free Language Modeling**, `arXiv, 2406.02528`, [arxiv](http://arxiv.org/abs/2406.02528v1), [pdf](http://arxiv.org/pdf/2406.02528v1.pdf), cication: [**-1**](None)

	 *Rui-Jie Zhu, Yu Zhang, Ethan Sifferman, Tyler Sheaves, Yiqiao Wang, Dustin Richmond, Peng Zhou, Jason K. Eshraghian* · ([matmulfreellm](https://github.com/ridgerchu/matmulfreellm) - ridgerchu) ![Star](https://img.shields.io/github/stars/ridgerchu/matmulfreellm.svg?style=social&label=Star)
- **Perplexed by Perplexity: Perplexity-Based Data Pruning With Small
  Reference Models**, `arXiv, 2405.20541`, [arxiv](http://arxiv.org/abs/2405.20541v1), [pdf](http://arxiv.org/pdf/2405.20541v1.pdf), cication: [**-1**](None)

	 *Zachary Ankner, Cody Blakeney, Kartik Sreenivasan, Max Marion, Matthew L. Leavitt, Mansheej Paul*
- [**PruneGPT**](https://github.com/nyunAI/PruneGPT) - nyunAI ![Star](https://img.shields.io/github/stars/nyunAI/PruneGPT.svg?style=social&label=Star)

	 · ([huggingface](https://huggingface.co/nyunai/nyun-llama3-62B))
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
- **KV Prediction for Improved Time to First Token**, `arXiv, 2410.08391`, [arxiv](http://arxiv.org/abs/2410.08391v1), [pdf](http://arxiv.org/pdf/2410.08391v1.pdf), cication: [**-1**](None)

	 *Maxwell Horton, Qingqing Cao, Chenfan Sun, Yanzi Jin, Sachin Mehta, Mohammad Rastegari, Moin Nabi* · ([corenet](https://github.com/apple/corenet/tree/main/projects/kv-prediction) - apple) ![Star](https://img.shields.io/github/stars/apple/corenet.svg?style=social&label=Star)
- **LayerSkip: Enabling Early Exit Inference and Self-Speculative Decoding**, `arXiv, 2404.16710`, [arxiv](http://arxiv.org/abs/2404.16710v3), [pdf](http://arxiv.org/pdf/2404.16710v3.pdf), cication: [**25**](https://scholar.google.com/scholar?cites=2243830506588578267&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Mostafa Elhoushi, Akshat Shrivastava, Diana Liskovich, Basil Hosmer, Bram Wasti, Liangzhen Lai, Anas Mahmoud, Bilge Acun, Saurabh Agarwal, Ahmed Roman* · ([LayerSkip](https://github.com/facebookresearch/LayerSkip) - facebookresearch) ![Star](https://img.shields.io/github/stars/facebookresearch/LayerSkip.svg?style=social&label=Star)
- **TPI-LLM: Serving 70B-scale LLMs Efficiently on Low-resource Edge Devices**, `arXiv, 2410.00531`, [arxiv](http://arxiv.org/abs/2410.00531v1), [pdf](http://arxiv.org/pdf/2410.00531v1.pdf), cication: [**-1**](None)

	 *Zonghang Li, Wenjiao Feng, Mohsen Guizani, Hongfang Yu* · ([TPI-LLM](https://github.com/Lizonghang/TPI-LLM) - Lizonghang) ![Star](https://img.shields.io/github/stars/Lizonghang/TPI-LLM.svg?style=social&label=Star)
- [**LMCache**](https://github.com/LMCache/LMCache) - LMCache ![Star](https://img.shields.io/github/stars/LMCache/LMCache.svg?style=social&label=Star)

	 · ([lmcache.github](https://lmcache.github.io/2024-09-17-release/)) · ([x](https://x.com/lmcache/status/1836136395477520507))
- [**optillm**](https://github.com/codelion/optillm) - codelion ![Star](https://img.shields.io/github/stars/codelion/optillm.svg?style=social&label=Star)

	 *Optimizing inference proxy for LLMs*
- **NanoFlow: Towards Optimal Large Language Model Serving Throughput**, `arXiv, 2408.12757`, [arxiv](http://arxiv.org/abs/2408.12757v1), [pdf](http://arxiv.org/pdf/2408.12757v1.pdf), cication: [**-1**](None)

	 *Kan Zhu, Yilong Zhao, Liangyu Zhao, Gefei Zuo, Yile Gu, Dedong Xie, Yufei Gao, Qinyu Xu, Tian Tang, Zihao Ye* · ([Nanoflow](https://github.com/efeslab/Nanoflow) - efeslab) ![Star](https://img.shields.io/github/stars/efeslab/Nanoflow.svg?style=social&label=Star)
- **LlamaDuo: LLMOps Pipeline for Seamless Migration from Service LLMs to
  Small-Scale Local LLMs**, `arXiv, 2408.13467`, [arxiv](http://arxiv.org/abs/2408.13467v2), [pdf](http://arxiv.org/pdf/2408.13467v2.pdf), cication: [**-1**](None)

	 *Chansung Park, Juyong Jiang, Fan Wang, Sayak Paul, Jing Tang* · ([llamaduo](https://github.com/deep-diver/llamaduo) - deep-diver) ![Star](https://img.shields.io/github/stars/deep-diver/llamaduo.svg?style=social&label=Star)
- [How to double tokens per second for Llama 3 with Medusa](https://www.baseten.co/blog/how-to-double-tokens-per-second-for-llama-3-with-medusa/)

	 · ([x](https://x.com/basetenco/status/1825897599573844107))
- [**LitServe**](https://github.com/Lightning-AI/LitServe) - Lightning-AI ![Star](https://img.shields.io/github/stars/Lightning-AI/LitServe.svg?style=social&label=Star)

	 *High-throughput serving engine for AI models. Easy to use. Flexible. Enterprise scale.* · ([lightning](https://lightning.ai/docs/litserve/home/speed-up-serving-by-200x))
- **MagicDec: Breaking the Latency-Throughput Tradeoff for Long Context
  Generation with Speculative Decoding**, `arXiv, 2408.11049`, [arxiv](http://arxiv.org/abs/2408.11049v3), [pdf](http://arxiv.org/pdf/2408.11049v3.pdf), cication: [**-1**](None)

	 *Jian Chen, Vashisth Tiwari, Ranajoy Sadhukhan, Zhuoming Chen, Jinyuan Shi, Ian En-Hsu Yen, Beidi Chen* · ([MagicDec](https://github.com/Infini-AI-Lab/MagicDec/) - Infini-AI-Lab) ![Star](https://img.shields.io/github/stars/Infini-AI-Lab/MagicDec.svg?style=social&label=Star)
- [Text Generation Inference](https://huggingface.co/docs/text-generation-inference/en/index)
- **ThinK: Thinner Key Cache by Query-Driven Pruning**, `arXiv, 2407.21018`, [arxiv](http://arxiv.org/abs/2407.21018v1), [pdf](http://arxiv.org/pdf/2407.21018v1.pdf), cication: [**-1**](None)

	 *Yuhui Xu, Zhanming Jie, Hanze Dong, Lei Wang, Xudong Lu, Aojun Zhou, Amrita Saha, Caiming Xiong, Doyen Sahoo*
- [Achieving Faster Open-Source Llama3 Serving with SGLang Runtime (vs. TensorRT-LLM, vLLM)](https://lmsys.org/blog/2024-07-25-sglang-llama3/)
- **LazyLLM: Dynamic Token Pruning for Efficient Long Context LLM Inference**, `arXiv, 2407.14057`, [arxiv](http://arxiv.org/abs/2407.14057v1), [pdf](http://arxiv.org/pdf/2407.14057v1.pdf), cication: [**-1**](None)

	 *Qichen Fu, Minsik Cho, Thomas Merth, Sachin Mehta, Mohammad Rastegari, Mahyar Najibi*
- **Inference Performance Optimization for Large Language Models on CPUs**, `arXiv, 2407.07304`, [arxiv](http://arxiv.org/abs/2407.07304v1), [pdf](http://arxiv.org/pdf/2407.07304v1.pdf), cication: [**-1**](None)

	 *Pujiang He, Shan Zhou, Wenhuan Huang, Changqing Li, Duyi Wang, Bin Guo, Chen Meng, Sheng Gui, Weifei Yu, Yi Xie* · ([xFasterTransformer](https://github.com/intel/xFasterTransformer) - intel) ![Star](https://img.shields.io/github/stars/intel/xFasterTransformer.svg?style=social&label=Star)
- **Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving**, `arXiv, 2407.00079`, [arxiv](http://arxiv.org/abs/2407.00079v3), [pdf](http://arxiv.org/pdf/2407.00079v3.pdf), cication: [**-1**](None)

	 *Ruoyu Qin, Zheming Li, Weiran He, Mingxing Zhang, Yongwei Wu, Weimin Zheng, Xinran Xu* · ([Mooncake](https://github.com/kvcache-ai/Mooncake) - kvcache-ai) ![Star](https://img.shields.io/github/stars/kvcache-ai/Mooncake.svg?style=social&label=Star)
- **Cascade Reward Sampling for Efficient Decoding-Time Alignment**, `arXiv, 2406.16306`, [arxiv](http://arxiv.org/abs/2406.16306v1), [pdf](http://arxiv.org/pdf/2406.16306v1.pdf), cication: [**-1**](None)

	 *Bolian Li, Yifan Wang, Ananth Grama, Ruqi Zhang*
- **MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via
  Dynamic Sparse Attention**, `arXiv, 2407.02490`, [arxiv](http://arxiv.org/abs/2407.02490v1), [pdf](http://arxiv.org/pdf/2407.02490v1.pdf), cication: [**-1**](None)

	 *Huiqiang Jiang, Yucheng Li, Chengruidong Zhang, Qianhui Wu, Xufang Luo, Surin Ahn, Zhenhua Han, Amir H. Abdi, Dongsheng Li, Chin-Yew Lin*

	 · ([MInference](https://github.com/microsoft/MInference) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/MInference.svg?style=social&label=Star) · ([aka](https://aka.ms/MInference))
- **Towards Fast Multilingual LLM Inference: Speculative Decoding and
  Specialized Drafters**, `arXiv, 2406.16758`, [arxiv](http://arxiv.org/abs/2406.16758v1), [pdf](http://arxiv.org/pdf/2406.16758v1.pdf), cication: [**-1**](None)

	 *Euiin Yi, Taehyeon Kim, Hongseok Jeung, Du-Seong Chang, Se-Young Yun* · ([Multilingual-SpecBench](https://github.com/Kthyeon/Multilingual-SpecBench) - Kthyeon) ![Star](https://img.shields.io/github/stars/Kthyeon/Multilingual-SpecBench.svg?style=social&label=Star)
- **EAGLE-2: Faster Inference of Language Models with Dynamic Draft Trees**, `arXiv, 2406.16858`, [arxiv](http://arxiv.org/abs/2406.16858v1), [pdf](http://arxiv.org/pdf/2406.16858v1.pdf), cication: [**-1**](None)

	 *Yuhui Li, Fangyun Wei, Chao Zhang, Hongyang Zhang*
- [Optimizing AI Inference at Character.AI](https://research.character.ai/optimizing-inference/)
- **A Simple and Effective $L_2$ Norm-Based Strategy for KV Cache
  Compression**, `arXiv, 2406.11430`, [arxiv](http://arxiv.org/abs/2406.11430v1), [pdf](http://arxiv.org/pdf/2406.11430v1.pdf), cication: [**-1**](None)

	 *Alessio Devoto, Yu Zhao, Simone Scardapane, Pasquale Minervini*
- **PowerInfer-2: Fast Large Language Model Inference on a Smartphone**, `arXiv, 2406.06282`, [arxiv](http://arxiv.org/abs/2406.06282v2), [pdf](http://arxiv.org/pdf/2406.06282v2.pdf), cication: [**-1**](None)

	 *Zhenliang Xue, Yixin Song, Zeyu Mi, Le Chen, Yubin Xia, Haibo Chen*
- [PowerInfer-2: Fast Large Language Model Inference on a Smartphone | PowerInfer](www.powerinfer.ai/v2)
- **Talaria: Interactively Optimizing Machine Learning Models for Efficient
  Inference**, `proceedings of the chi conference on human factors in computing systems, 2024`, [arxiv](http://arxiv.org/abs/2404.03085v1), [pdf](http://arxiv.org/pdf/2404.03085v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=7871074300050378048&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Fred Hohman, Chaoqun Wang, Jinmook Lee, Jochen Görtler, Dominik Moritz, Jeffrey P Bigham, Zhile Ren, Cecile Foret, Qi Shan, Xiaoyi Zhang* · ([machinelearning.apple](https://machinelearning.apple.com/research/talaria?utm_source=ainews&utm_medium=email&utm_campaign=ainews-talaria-apples-new-mlops-superweapon-4066))
- **Turbo Sparse: Achieving LLM SOTA Performance with Minimal Activated
  Parameters**, `arXiv, 2406.05955`, [arxiv](http://arxiv.org/abs/2406.05955v2), [pdf](http://arxiv.org/pdf/2406.05955v2.pdf), cication: [**-1**](None)

	 *Yixin Song, Haotong Xie, Zhengyan Zhang, Bo Wen, Li Ma, Zeyu Mi, Haibo Chen* · ([huggingface](https://huggingface.co/PowerInfer))
- **Parrot: Efficient Serving of LLM-based Applications with Semantic
  Variable**, `arXiv, 2405.19888`, [arxiv](http://arxiv.org/abs/2405.19888v1), [pdf](http://arxiv.org/pdf/2405.19888v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=9249664411081274625&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chaofan Lin, Zhenhua Han, Chengruidong Zhang, Yuqing Yang, Fan Yang, Chen Chen, Lili Qiu*
- **Nearest Neighbor Speculative Decoding for LLM Generation and Attribution**, `arXiv, 2405.19325`, [arxiv](http://arxiv.org/abs/2405.19325v2), [pdf](http://arxiv.org/pdf/2405.19325v2.pdf), cication: [**-1**](None)

	 *Minghan Li, Xilun Chen, Ari Holtzman, Beidi Chen, Jimmy Lin, Wen-tau Yih, Xi Victoria Lin*
- [Hamel’s Blog - Optimizing latency](https://hamel.dev/notes/llm/inference/03_inference.html)
- **Distributed Speculative Inference of Large Language Models**, `arXiv, 2405.14105`, [arxiv](http://arxiv.org/abs/2405.14105v1), [pdf](http://arxiv.org/pdf/2405.14105v1.pdf), cication: [**-1**](None)

	 *Nadav Timor, Jonathan Mamou, Daniel Korat, Moshe Berchansky, Oren Pereg, Moshe Wasserblat, Tomer Galanti, Michal Gordon, David Harel*
- **Reducing Transformer Key-Value Cache Size with Cross-Layer Attention**, `arXiv, 2405.12981`, [arxiv](http://arxiv.org/abs/2405.12981v1), [pdf](http://arxiv.org/pdf/2405.12981v1.pdf), cication: [**-1**](None)

	 *William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly*
- **PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM
  Inference**, `arXiv, 2405.12532`, [arxiv](http://arxiv.org/abs/2405.12532v1), [pdf](http://arxiv.org/pdf/2405.12532v1.pdf), cication: [**-1**](None)

	 *Dongjie Yang, XiaoDong Han, Yan Gao, Yao Hu, Shilin Zhang, Hai Zhao*
- **Layer-Condensed KV Cache for Efficient Inference of Large Language
  Models**, `arXiv, 2405.10637`, [arxiv](http://arxiv.org/abs/2405.10637v1), [pdf](http://arxiv.org/pdf/2405.10637v1.pdf), cication: [**-1**](None)

	 *Haoyi Wu, Kewei Tu* · ([LCKV](https://github.com/whyNLP/LCKV) - whyNLP) ![Star](https://img.shields.io/github/stars/whyNLP/LCKV.svg?style=social&label=Star)
- [**vidur**](https://github.com/microsoft/vidur) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/vidur.svg?style=social&label=Star)

	 *A large-scale simulation framework for LLM inference*
- **Conv-Basis: A New Paradigm for Efficient Attention Inference and
  Gradient Computation in Transformers**, `arXiv, 2405.05219`, [arxiv](http://arxiv.org/abs/2405.05219v1), [pdf](http://arxiv.org/pdf/2405.05219v1.pdf), cication: [**-1**](None)

	 *Jiuxiang Gu, Yingyu Liang, Heshan Liu, Zhenmei Shi, Zhao Song, Junze Yin*
- [**ThunderKittens**](https://github.com/HazyResearch/ThunderKittens) - HazyResearch ![Star](https://img.shields.io/github/stars/HazyResearch/ThunderKittens.svg?style=social&label=Star)

	 *Tile primitives for speedy kernels* · ([hazyresearch.stanford](https://hazyresearch.stanford.edu/blog/2024-05-12-tk))
- **vAttention: Dynamic Memory Management for Serving LLMs without
  PagedAttention**, `arXiv, 2405.04437`, [arxiv](http://arxiv.org/abs/2405.04437v1), [pdf](http://arxiv.org/pdf/2405.04437v1.pdf), cication: [**-1**](None)

	 *Ramya Prabhu, Ajay Nayak, Jayashree Mohan, Ramachandran Ramjee, Ashish Panwar*
- **Hybrid LLM: Cost-Efficient and Quality-Aware Query Routing**, `arXiv, 2404.14618`, [arxiv](http://arxiv.org/abs/2404.14618v1), [pdf](http://arxiv.org/pdf/2404.14618v1.pdf), cication: [**-1**](None)

	 *Dujian Ding, Ankur Mallick, Chi Wang, Robert Sim, Subhabrata Mukherjee, Victor Ruhle, Laks V. S. Lakshmanan, Ahmed Hassan Awadallah*
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
- **CLLMs: Consistency Large Language Models**, `arXiv, 2403.00835`, [arxiv](http://arxiv.org/abs/2403.00835v3), [pdf](http://arxiv.org/pdf/2403.00835v3.pdf), cication: [**-1**](None)

	 *Siqi Kou, Lanxiang Hu, Zhezhi He, Zhijie Deng, Hao Zhang* · ([Consistency_LLM](https://github.com/hao-ai-lab/Consistency_LLM) - hao-ai-lab) ![Star](https://img.shields.io/github/stars/hao-ai-lab/Consistency_LLM.svg?style=social&label=Star) · ([hao-ai-lab.github](https://hao-ai-lab.github.io/blogs/cllm/))
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
- [Faster Assisted Generation with Dynamic Speculation](https://huggingface.co/blog/dynamic_speculation_lookahead)
- [Cerebras This is instant A](https://inference.cerebras.ai/)
- [Faster ternary inference is possible : r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/comments/1egg8qx/faster_ternary_inference_is_possible/)
- [Benchmarking Text Generation Inference](https://huggingface.co/blog/tgi-benchmarking)
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
- **Squid: Long Context as a New Modality for Energy-Efficient On-Device
  Language Models**, `arXiv, 2408.15518`, [arxiv](http://arxiv.org/abs/2408.15518v2), [pdf](http://arxiv.org/pdf/2408.15518v2.pdf), cication: [**-1**](None)

	 *Wei Chen, Zhiyuan Li, Shuo Xin, Yihao Wang*

	 · ([huggingface](https://huggingface.co/NexaAIDev/Dolphin))
- [machinelearning.apple.com/papers/apple\_intelligence\_foundation\_language\_models.pdf](https://machinelearning.apple.com/papers/apple_intelligence_foundation_language_models.pdf)
- **MobileLLM: Optimizing Sub-billion Parameter Language Models for
  On-Device Use Cases**, `arXiv, 2402.14905`, [arxiv](http://arxiv.org/abs/2402.14905v2), [pdf](http://arxiv.org/pdf/2402.14905v2.pdf), cication: [**15**](https://scholar.google.com/scholar?cites=10746600429526080063&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zechun Liu, Changsheng Zhao, Forrest Iandola, Chen Lai, Yuandong Tian, Igor Fedorov, Yunyang Xiong, Ernie Chang, Yangyang Shi, Raghuraman Krishnamoorthi*

	 · ([MobileLLM](https://github.com/facebookresearch/MobileLLM) - facebookresearch) ![Star](https://img.shields.io/github/stars/facebookresearch/MobileLLM.svg?style=social&label=Star)
- **HARE: HumAn pRiors, a key to small language model Efficiency**, `arXiv, 2406.11410`, [arxiv](http://arxiv.org/abs/2406.11410v2), [pdf](http://arxiv.org/pdf/2406.11410v2.pdf), cication: [**-1**](None)

	 *Lingyun Zhang, Bin jin, Gaojian Ge, Lunhui Liu, Xuewen Shen, Mingyong Wu, Houqian Zhang, Yongneng Jiang, Shiqi Chen, Shi Pu*
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
- [**xFasterTransformer**](https://github.com/intel/xFasterTransformer?tab=readme-ov-file#web-demo) - intel ![Star](https://img.shields.io/github/stars/intel/xFasterTransformer.svg?style=social&label=Star)
- [**flash-linear-attention**](https://github.com/sustcsonglin/flash-linear-attention) - sustcsonglin ![Star](https://img.shields.io/github/stars/sustcsonglin/flash-linear-attention.svg?style=social&label=Star)

	 *Efficient implementations of state-of-the-art linear attention models in Pytorch and Triton*
- [Introduction to ggml](https://huggingface.co/blog/introduction-to-ggml)
- [FlexAttention: The Flexibility of PyTorch with the Performance of FlashAttention | PyTorch](https://pytorch.org/blog/flexattention/)

	 · ([eb339f9ff2261616e563ea7684d1df0c](https://gist.github.com/Chillee/eb339f9ff2261616e563ea7684d1df0c) - Chillee) ![Star](https://img.shields.io/github/stars/Chillee/eb339f9ff2261616e563ea7684d1df0c.svg?style=social&label=Star)
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
- **Differential Transformer**, `arXiv, 2410.05258`, [arxiv](http://arxiv.org/abs/2410.05258v1), [pdf](http://arxiv.org/pdf/2410.05258v1.pdf), cication: [**-1**](None)

	 *Tianzhu Ye, Li Dong, Yuqing Xia, Yutao Sun, Yi Zhu, Gao Huang, Furu Wei*
- **Selective Attention Improves Transformer**, `arXiv, 2410.02703`, [arxiv](http://arxiv.org/abs/2410.02703v1), [pdf](http://arxiv.org/pdf/2410.02703v1.pdf), cication: [**-1**](None)

	 *Yaniv Leviathan, Matan Kalman, Yossi Matias*
- **Addition is All You Need for Energy-efficient Language Models**, `arXiv, 2410.00907`, [arxiv](http://arxiv.org/abs/2410.00907v2), [pdf](http://arxiv.org/pdf/2410.00907v2.pdf), cication: [**-1**](None)

	 *Hongyin Luo, Wei Sun*
- **SageAttention: Accurate 8-Bit Attention for Plug-and-play Inference
  Acceleration**, `arXiv, 2410.02367`, [arxiv](http://arxiv.org/abs/2410.02367v1), [pdf](http://arxiv.org/pdf/2410.02367v1.pdf), cication: [**-1**](None)

	 *Jintao Zhang, Jia wei, Pengle Zhang, Jun Zhu, Jianfei Chen* · ([SageAttention](https://github.com/thu-ml/SageAttention) - thu-ml) ![Star](https://img.shields.io/github/stars/thu-ml/SageAttention.svg?style=social&label=Star)
- **Gated Slot Attention for Efficient Linear-Time Sequence Modeling**, `arXiv, 2409.07146`, [arxiv](http://arxiv.org/abs/2409.07146v1), [pdf](http://arxiv.org/pdf/2409.07146v1.pdf), cication: [**-1**](None)

	 *Yu Zhang, Songlin Yang, Ruijie Zhu, Yue Zhang, Leyang Cui, Yiqiao Wang, Bolun Wang, Freda Shi, Bailin Wang, Wei Bi*
- **GoldFinch: High Performance RWKV/Transformer Hybrid with Linear Pre-Fill
  and Extreme KV-Cache Compression**, `arXiv, 2407.12077`, [arxiv](http://arxiv.org/abs/2407.12077v1), [pdf](http://arxiv.org/pdf/2407.12077v1.pdf), cication: [**-1**](None)

	 *Daniel Goldstein, Fares Obeid, Eric Alcaide, Guangyu Song, Eugene Cheah* · ([GoldFinch-paper](https://github.com/recursal/GoldFinch-paper) - recursal) ![Star](https://img.shields.io/github/stars/recursal/GoldFinch-paper.svg?style=social&label=Star)
- [FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision | Tri Dao](https://tridao.me/blog/2024/flash3/)

	 · ([flash-attention](https://github.com/Dao-AILab/flash-attention) - Dao-AILab) ![Star](https://img.shields.io/github/stars/Dao-AILab/flash-attention.svg?style=social&label=Star)
- **MoA: Mixture of Sparse Attention for Automatic Large Language Model
  Compression**, `arXiv, 2406.14909`, [arxiv](http://arxiv.org/abs/2406.14909v1), [pdf](http://arxiv.org/pdf/2406.14909v1.pdf), cication: [**-1**](None)

	 *Tianyu Fu, Haofeng Huang, Xuefei Ning, Genghan Zhang, Boju Chen, Tianqi Wu, Hongyi Wang, Zixiao Huang, Shiyao Li, Shengen Yan*
- [Flash Attention (Fast and Memory-Efficient Exact Attention wi](https://towardsdatascience.com/flash-attention-fast-and-memory-efficient-exact-attention-with-io-awareness-a-deep-dive-724af489997b)
- **Block Transformer: Global-to-Local Language Modeling for Fast Inference**, `arXiv, 2406.02657`, [arxiv](http://arxiv.org/abs/2406.02657v1), [pdf](http://arxiv.org/pdf/2406.02657v1.pdf), cication: [**-1**](None)

	 *Namgyu Ho, Sangmin Bae, Taehyeon Kim, Hyunjik Jo, Yireun Kim, Tal Schuster, Adam Fisch, James Thorne, Se-Young Yun*

	 · ([block-transformer](https://github.com/itsnamgyu/block-transformer) - itsnamgyu) ![Star](https://img.shields.io/github/stars/itsnamgyu/block-transformer.svg?style=social&label=Star)
- **LLaMA-NAS: Efficient Neural Architecture Search for Large Language
  Models**, `arXiv, 2405.18377`, [arxiv](http://arxiv.org/abs/2405.18377v1), [pdf](http://arxiv.org/pdf/2405.18377v1.pdf), cication: [**-1**](None)

	 *Anthony Sarah, Sharath Nittur Sridhar, Maciej Szankin, Sairam Sundaresan*
- **SLAB: Efficient Transformers with Simplified Linear Attention and
  Progressive Re-parameterized Batch Normalization**, `arXiv, 2405.11582`, [arxiv](http://arxiv.org/abs/2405.11582v1), [pdf](http://arxiv.org/pdf/2405.11582v1.pdf), cication: [**-1**](None)

	 *Jialong Guo, Xinghao Chen, Yehui Tang, Yunhe Wang* · ([SLAB](https://github.com/xinghaochen/SLAB) - xinghaochen) ![Star](https://img.shields.io/github/stars/xinghaochen/SLAB.svg?style=social&label=Star)
- **You Only Cache Once: Decoder-Decoder Architectures for Language Models**, `arXiv, 2405.05254`, [arxiv](http://arxiv.org/abs/2405.05254v2), [pdf](http://arxiv.org/pdf/2405.05254v2.pdf), cication: [**-1**](None)

	 *Yutao Sun, Li Dong, Yi Zhu, Shaohan Huang, Wenhui Wang, Shuming Ma, Quanlu Zhang, Jianyong Wang, Furu Wei* · ([aka](https://aka.ms/YOCO)) · ([unilm](https://github.com/microsoft/unilm/tree/master/YOCO) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star)
- **Is Flash Attention Stable?**, `arXiv, 2405.02803`, [arxiv](http://arxiv.org/abs/2405.02803v1), [pdf](http://arxiv.org/pdf/2405.02803v1.pdf), cication: [**-1**](None)

	 *Alicia Golden, Samuel Hsia, Fei Sun, Bilge Acun, Basil Hosmer, Yejin Lee, Zachary DeVito, Jeff Johnson, Gu-Yeon Wei, David Brooks*
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

- [**zml**](https://github.com/zml/zml) - zml ![Star](https://img.shields.io/github/stars/zml/zml.svg?style=social&label=Star)

	 *High performance AI inference stack. Built for production. @ziglang / @openxla / MLIR / @bazelbuild*
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