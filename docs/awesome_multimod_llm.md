# Awesome-multimod-llms

- [Awesome-multimod-llms](#awesome-multimod-llms)
	- [Survey](#survey)
	- [Vision](#vision)
		- [Video](#video)
		- [Image](#image)
	- [Audio](#audio)
	- [Efficient](#efficient)
	- [Extra Modalities](#extra-modalities)
	- [Projects](#projects)
	- [Benchmarks](#benchmarks)
	- [Datasets](#datasets)
	- [Other](#other)
	- [Reference](#reference)

## Survey
- **A Review of Multi-Modal Large Language and Vision Models**, `arXiv, 2404.01322`, [arxiv](http://arxiv.org/abs/2404.01322v1), [pdf](http://arxiv.org/pdf/2404.01322v1.pdf), cication: [**-1**](None)

	 *Kilian Carolan, Laura Fennelly, Alan F. Smeaton*
- **Multimodal Pretraining, Adaptation, and Generation for Recommendation: A
  Survey**, `arXiv, 2404.00621`, [arxiv](http://arxiv.org/abs/2404.00621v1), [pdf](http://arxiv.org/pdf/2404.00621v1.pdf), cication: [**-1**](None)

	 *Qijiong Liu, Jieming Zhu, Yanting Yang, Quanyu Dai, Zhaocheng Du, Xiao-Ming Wu, Zhou Zhao, Rui Zhang, Zhenhua Dong*
- **Veagle: Advancements in Multimodal Representation Learning**, `arXiv, 2403.08773`, [arxiv](http://arxiv.org/abs/2403.08773v1), [pdf](http://arxiv.org/pdf/2403.08773v1.pdf), cication: [**-1**](None)

	 *Rajat Chawla, Arkajit Datta, Tushar Verma, Adarsh Jha, Anmol Gautam, Ayush Vatsal, Sukrit Chaterjee, Mukunda NS, Ishaan Bhola*
- **MM-LLMs: Recent Advances in MultiModal Large Language Models**, `arXiv, 2401.13601`, [arxiv](http://arxiv.org/abs/2401.13601v1), [pdf](http://arxiv.org/pdf/2401.13601v1.pdf), cication: [**-1**](None)

	 *Duzhen Zhang, Yahan Yu, Chenxing Li, Jiahua Dong, Dan Su, Chenhui Chu, Dong Yu*
- **A Survey of Resource-efficient LLM and Multimodal Foundation Models**, `arXiv, 2401.08092`, [arxiv](http://arxiv.org/abs/2401.08092v1), [pdf](http://arxiv.org/pdf/2401.08092v1.pdf), cication: [**-1**](None)

	 *Mengwei Xu, Wangsong Yin, Dongqi Cai, Rongjie Yi, Daliang Xu, Qipeng Wang, Bingyang Wu, Yihao Zhao, Chen Yang, Shihe Wang*

## Vision
### Vision Encoder
- **ViTamin: Designing Scalable Vision Models in the Vision-Language Era**, `arXiv, 2404.02132`, [arxiv](http://arxiv.org/abs/2404.02132v1), [pdf](http://arxiv.org/pdf/2404.02132v1.pdf), cication: [**-1**](None)

	 *Jienneg Chen, Qihang Yu, Xiaohui Shen, Alan Yuille, Liang-Chieh Chen* · ([ViTamin](https://github.com/Beckschen/ViTamin) - Beckschen) ![Star](https://img.shields.io/github/stars/Beckschen/ViTamin.svg?style=social&label=Star)
- **ViTAR: Vision Transformer with Any Resolution**, `arXiv, 2403.18361`, [arxiv](http://arxiv.org/abs/2403.18361v1), [pdf](http://arxiv.org/pdf/2403.18361v1.pdf), cication: [**-1**](None)

	 *Qihang Fan, Quanzeng You, Xiaotian Han, Yongfei Liu, Yunzhe Tao, Huaibo Huang, Ran He, Hongxia Yang*
	- `addresses the challenge of Vision Transformers limited scalability across various image resolutions, introducing dynamic resolution adjustment and fuzzy positional encoding.`
- **EfficientVMamba: Atrous Selective Scan for Light Weight Visual Mamba**, `arXiv, 2403.09977`, [arxiv](http://arxiv.org/abs/2403.09977v1), [pdf](http://arxiv.org/pdf/2403.09977v1.pdf), cication: [**-1**](None)

	 *Xiaohuan Pei, Tao Huang, Chang Xu* · ([EfficientVMamba](https://github.com/TerryPei/EfficientVMamba) - TerryPei) ![Star](https://img.shields.io/github/stars/TerryPei/EfficientVMamba.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247556253&idx=3&sn=618d4eb61d5fc8b24f9e71931d44c1a8&poc_token=HHjeBGajQSQY6cy7jA_4js-7G5qkkI1EMpYFlg56))
- **SiMBA: Simplified Mamba-Based Architecture for Vision and Multivariate
  Time series**, `arXiv, 2403.15360`, [arxiv](http://arxiv.org/abs/2403.15360v1), [pdf](http://arxiv.org/pdf/2403.15360v1.pdf), cication: [**-1**](None)

	 *Badri N. Patro, Vijay S. Agneeswaran* · ([Simba](https://github.com/badripatro/Simba) - badripatro) ![Star](https://img.shields.io/github/stars/badripatro/Simba.svg?style=social&label=Star)
- **xT: Nested Tokenization for Larger Context in Large Images**, `arXiv, 2403.01915`, [arxiv](http://arxiv.org/abs/2403.01915v1), [pdf](http://arxiv.org/pdf/2403.01915v1.pdf), cication: [**-1**](None)

	 *Ritwik Gupta, Shufan Li, Tyler Zhu, Jitendra Malik, Trevor Darrell, Karttikeya Mangalam* · ([bair.berkeley](https://bair.berkeley.edu/blog/2024/03/21/xt/)) · ([ai-climate.berkeley](http://ai-climate.berkeley.edu/xt-website/))
- **When Do We Not Need Larger Vision Models?**, `arXiv, 2403.13043`, [arxiv](http://arxiv.org/abs/2403.13043v1), [pdf](http://arxiv.org/pdf/2403.13043v1.pdf), cication: [**-1**](None)

	 *Baifeng Shi, Ziyang Wu, Maolin Mao, Xin Wang, Trevor Darrell* · ([scaling_on_scales](https://github.com/bfshi/scaling_on_scales) - bfshi) ![Star](https://img.shields.io/github/stars/bfshi/scaling_on_scales.svg?style=social&label=Star)
- **LocalMamba: Visual State Space Model with Windowed Selective Scan**, `arXiv, 2403.09338`, [arxiv](http://arxiv.org/abs/2403.09338v1), [pdf](http://arxiv.org/pdf/2403.09338v1.pdf), cication: [**-1**](None)

	 *Tao Huang, Xiaohuan Pei, Shan You, Fei Wang, Chen Qian, Chang Xu*
- **Denoising Vision Transformers**, `arXiv, 2401.02957`, [arxiv](http://arxiv.org/abs/2401.02957v1), [pdf](http://arxiv.org/pdf/2401.02957v1.pdf), cication: [**-1**](None)

	 *Jiawei Yang, Katie Z Luo, Jiefeng Li, Kilian Q Weinberger, Yonglong Tian, Yue Wang*
- [**LocalMamba**](https://github.com/hunto/LocalMamba) - hunto ![Star](https://img.shields.io/github/stars/hunto/LocalMamba.svg?style=social&label=Star)

	 *Code for paper LocalMamba: Visual State Space Model with Windowed Selective Scan*

### Video
- **Koala: Key frame-conditioned long video-LLM**, `arXiv, 2404.04346`, [arxiv](http://arxiv.org/abs/2404.04346v1), [pdf](http://arxiv.org/pdf/2404.04346v1.pdf), cication: [**-1**](None)

	 *Reuben Tan, Ximeng Sun, Ping Hu, Jui-hsien Wang, Hanieh Deilamsalehy, Bryan A. Plummer, Bryan Russell, Kate Saenko*
- **MA-LMM: Memory-Augmented Large Multimodal Model for Long-Term Video
  Understanding**, `arXiv, 2404.05726`, [arxiv](http://arxiv.org/abs/2404.05726v1), [pdf](http://arxiv.org/pdf/2404.05726v1.pdf), cication: [**-1**](None)

	 *Bo He, Hengduo Li, Young Kyun Jang, Menglin Jia, Xuefei Cao, Ashish Shah, Abhinav Shrivastava, Ser-Nam Lim* · ([MA-LMM](https://github.com/boheumd/MA-LMM) - boheumd) ![Star](https://img.shields.io/github/stars/boheumd/MA-LMM.svg?style=social&label=Star)
- **MiniGPT4-Video: Advancing Multimodal LLMs for Video Understanding with
  Interleaved Visual-Textual Tokens**, `arXiv, 2404.03413`, [arxiv](http://arxiv.org/abs/2404.03413v1), [pdf](http://arxiv.org/pdf/2404.03413v1.pdf), cication: [**-1**](None)

	 *Kirolos Ataallah, Xiaoqian Shen, Eslam Abdelrahman, Essam Sleiman, Deyao Zhu, Jian Ding, Mohamed Elhoseiny* · ([MiniGPT4-video](https://github.com/Vision-CAIR/MiniGPT4-video) - Vision-CAIR) ![Star](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT4-video.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652463844&idx=1&sn=d7505ee993179cc5df3b5cedc07d1ddc&poc_token=HK4CEmajV8CJghkQWcmVb-3AVTfO3_iIp_s9-VEV))
- **Streaming Dense Video Captioning**, `arXiv, 2404.01297`, [arxiv](http://arxiv.org/abs/2404.01297v1), [pdf](http://arxiv.org/pdf/2404.01297v1.pdf), cication: [**-1**](None)

	 *Xingyi Zhou, Anurag Arnab, Shyamal Buch, Shen Yan, Austin Myers, Xuehan Xiong, Arsha Nagrani, Cordelia Schmid* · ([scenic](https://github.com/google-research/scenic/tree/main/scenic/projects/streaming_dvc) - google-research) ![Star](https://img.shields.io/github/stars/google-research/scenic.svg?style=social&label=Star)
- **Direct Preference Optimization of Video Large Multimodal Models from
  Language Model Reward**, `arXiv, 2404.01258`, [arxiv](http://arxiv.org/abs/2404.01258v2), [pdf](http://arxiv.org/pdf/2404.01258v2.pdf), cication: [**-1**](None)

	 *Ruohong Zhang, Liangke Gui, Zhiqing Sun, Yihao Feng, Keyang Xu, Yuanhan Zhang, Di Fu, Chunyuan Li, Alexander Hauptmann, Yonatan Bisk*
- **LITA: Language Instructed Temporal-Localization Assistant**, `arXiv, 2403.19046`, [arxiv](http://arxiv.org/abs/2403.19046v1), [pdf](http://arxiv.org/pdf/2403.19046v1.pdf), cication: [**-1**](None)

	 *De-An Huang, Shijia Liao, Subhashree Radhakrishnan, Hongxu Yin, Pavlo Molchanov, Zhiding Yu, Jan Kautz* · ([LITA](https://github.com/NVlabs/LITA) - NVlabs) ![Star](https://img.shields.io/github/stars/NVlabs/LITA.svg?style=social&label=Star)
- **An Image Grid Can Be Worth a Video: Zero-shot Video Question Answering
  Using a VLM**, `arXiv, 2403.18406`, [arxiv](http://arxiv.org/abs/2403.18406v1), [pdf](http://arxiv.org/pdf/2403.18406v1.pdf), cication: [**-1**](None)

	 *Wonkyun Kim, Changin Choi, Wonseok Lee, Wonjong Rhee* · ([IG-VLM](https://github.com/imagegridworth/IG-VLM) - imagegridworth) ![Star](https://img.shields.io/github/stars/imagegridworth/IG-VLM.svg?style=social&label=Star)
- **VidLA: Video-Language Alignment at Scale**, `arXiv, 2403.14870`, [arxiv](http://arxiv.org/abs/2403.14870v1), [pdf](http://arxiv.org/pdf/2403.14870v1.pdf), cication: [**-1**](None)

	 *Mamshad Nayeem Rizve, Fan Fei, Jayakrishnan Unnikrishnan, Son Tran, Benjamin Z. Yao, Belinda Zeng, Mubarak Shah, Trishul Chilimbi*
- **InternVideo2: Scaling Video Foundation Models for Multimodal Video
  Understanding**, `arXiv, 2403.15377`, [arxiv](http://arxiv.org/abs/2403.15377v1), [pdf](http://arxiv.org/pdf/2403.15377v1.pdf), cication: [**-1**](None)

	 *Yi Wang, Kunchang Li, Xinhao Li, Jiashuo Yu, Yinan He, Guo Chen, Baoqi Pei, Rongkun Zheng, Jilan Xu, Zun Wang* · ([InternVideo2](https://github.com/OpenGVLab/InternVideo2/) - OpenGVLab) ![Star](https://img.shields.io/github/stars/OpenGVLab/InternVideo2.svg?style=social&label=Star)
- **VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding**, `arXiv, 2403.11481`, [arxiv](http://arxiv.org/abs/2403.11481v1), [pdf](http://arxiv.org/pdf/2403.11481v1.pdf), cication: [**-1**](None)

	 *Yue Fan, Xiaojian Ma, Rujie Wu, Yuntao Du, Jiaqi Li, Zhi Gao, Qing Li*
- **VideoAgent: Long-form Video Understanding with Large Language Model as
  Agent**, `arXiv, 2403.10517`, [arxiv](http://arxiv.org/abs/2403.10517v1), [pdf](http://arxiv.org/pdf/2403.10517v1.pdf), cication: [**-1**](None)

	 *Xiaohan Wang, Yuhui Zhang, Orr Zohar, Serena Yeung-Levy*
- **Video Mamba Suite: State Space Model as a Versatile Alternative for
  Video Understanding**, `arXiv, 2403.09626`, [arxiv](http://arxiv.org/abs/2403.09626v1), [pdf](http://arxiv.org/pdf/2403.09626v1.pdf), cication: [**-1**](None)

	 *Guo Chen, Yifei Huang, Jilan Xu, Baoqi Pei, Zhe Chen, Zhiqi Li, Jiahao Wang, Kunchang Li, Tong Lu, Limin Wang*

	 · ([video-mamba-suite](https://github.com/OpenGVLab/video-mamba-suite) - OpenGVLab) ![Star](https://img.shields.io/github/stars/OpenGVLab/video-mamba-suite.svg?style=social&label=Star)
- **CAT: Enhancing Multimodal Large Language Model to Answer Questions in
  Dynamic Audio-Visual Scenarios**, `arXiv, 2403.04640`, [arxiv](http://arxiv.org/abs/2403.04640v1), [pdf](http://arxiv.org/pdf/2403.04640v1.pdf), cication: [**-1**](None)

	 *Qilang Ye, Zitong Yu, Rui Shao, Xinyu Xie, Philip Torr, Xiaochun Cao*

	 · ([Bay-CAT](https://github.com/rikeilong/Bay-CAT) - rikeilong) ![Star](https://img.shields.io/github/stars/rikeilong/Bay-CAT.svg?style=social&label=Star)
- **MovieLLM: Enhancing Long Video Understanding with AI-Generated Movies**, `arXiv, 2403.01422`, [arxiv](http://arxiv.org/abs/2403.01422v1), [pdf](http://arxiv.org/pdf/2403.01422v1.pdf), cication: [**-1**](None)

	 *Zhende Song, Chenchen Wang, Jiamu Sheng, Chi Zhang, Gang Yu, Jiayuan Fan, Tao Chen*
- **LLMBind: A Unified Modality-Task Integration Framework**, `arXiv, 2402.14891`, [arxiv](http://arxiv.org/abs/2402.14891v1), [pdf](http://arxiv.org/pdf/2402.14891v1.pdf), cication: [**-1**](None)

	 *Bin Zhu, Peng Jin, Munan Ning, Bin Lin, Jinfa Huang, Qi Song, Mingjun Pan, Li Yuan*
- **VideoPrism: A Foundational Visual Encoder for Video Understanding**, `arXiv, 2402.13217`, [arxiv](http://arxiv.org/abs/2402.13217v1), [pdf](http://arxiv.org/pdf/2402.13217v1.pdf), cication: [**-1**](None)

	 *Long Zhao, Nitesh B. Gundavarapu, Liangzhe Yuan, Hao Zhou, Shen Yan, Jennifer J. Sun, Luke Friedman, Rui Qian, Tobias Weyand, Yue Zhao*
- **AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling**, `arXiv, 2402.12226`, [arxiv](http://arxiv.org/abs/2402.12226v1), [pdf](http://arxiv.org/pdf/2402.12226v1.pdf), cication: [**-1**](None)

	 *Jun Zhan, Junqi Dai, Jiasheng Ye, Yunhua Zhou, Dong Zhang, Zhigeng Liu, Xin Zhang, Ruibin Yuan, Ge Zhang, Linyang Li* · ([junzhan2000.github](https://junzhan2000.github.io/AnyGPT.github.io/))
- [V-JEPA: Video Joint Embedding Predictive Architecture](https://ai.meta.com/blog/v-jepa-yann-lecun-ai-model-video-joint-embedding-predictive-architecture/)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652444680&idx=1&sn=d5a948141e5ba81d48cf4a7e34e39738))

	 · ([jepa](https://github.com/facebookresearch/jepa) - facebookresearch) ![Star](https://img.shields.io/github/stars/facebookresearch/jepa.svg?style=social&label=Star)
- **World Model on Million-Length Video And Language With RingAttention**, `arXiv, 2402.08268`, [arxiv](http://arxiv.org/abs/2402.08268v1), [pdf](http://arxiv.org/pdf/2402.08268v1.pdf), cication: [**-1**](None)

	 *Hao Liu, Wilson Yan, Matei Zaharia, Pieter Abbeel* · ([LWM](https://github.com/LargeWorldModel/LWM) - LargeWorldModel) ![Star](https://img.shields.io/github/stars/LargeWorldModel/LWM.svg?style=social&label=Star)
- **Distilling Vision-Language Models on Millions of Videos**, `arXiv, 2401.06129`, [arxiv](http://arxiv.org/abs/2401.06129v1), [pdf](http://arxiv.org/pdf/2401.06129v1.pdf), cication: [**-1**](None)

	 *Yue Zhao, Long Zhao, Xingyi Zhou, Jialin Wu, Chun-Te Chu, Hui Miao, Florian Schroff, Hartwig Adam, Ting Liu, Boqing Gong*
- **LEGO:Language Enhanced Multi-modal Grounding Model**, `arXiv, 2401.06071`, [arxiv](http://arxiv.org/abs/2401.06071v1), [pdf](http://arxiv.org/pdf/2401.06071v1.pdf), cication: [**-1**](None)

	 *Zhaowei Li, Qi Xu, Dong Zhang, Hang Song, Yiqing Cai, Qi Qi, Ran Zhou, Junting Pan, Zefeng Li, Van Tu Vu* · ([LEGO](https://github.com/lzw-lzw/LEGO) - lzw-lzw) ![Star](https://img.shields.io/github/stars/lzw-lzw/LEGO.svg?style=social&label=Star)
- **COSMO: COntrastive Streamlined MultimOdal Model with Interleaved
  Pre-Training**, `arXiv, 2401.00849`, [arxiv](http://arxiv.org/abs/2401.00849v1), [pdf](http://arxiv.org/pdf/2401.00849v1.pdf), cication: [**-1**](None)

	 *Alex Jinpeng Wang, Linjie Li, Kevin Qinghong Lin, Jianfeng Wang, Kevin Lin, Zhengyuan Yang, Lijuan Wang, Mike Zheng Shou*
- **General Object Foundation Model for Images and Videos at Scale**, `arXiv, 2312.09158`, [arxiv](http://arxiv.org/abs/2312.09158v1), [pdf](http://arxiv.org/pdf/2312.09158v1.pdf), cication: [**-1**](None)

	 *Junfeng Wu, Yi Jiang, Qihao Liu, Zehuan Yuan, Xiang Bai, Song Bai*

	 · ([glee-vision.github](https://glee-vision.github.io))
- **Video Understanding with Large Language Models: A Survey**, `arXiv, 2312.17432`, [arxiv](http://arxiv.org/abs/2312.17432v2), [pdf](http://arxiv.org/pdf/2312.17432v2.pdf), cication: [**-1**](None)

	 *Yunlong Tang, Jing Bi, Siting Xu, Luchuan Song, Susan Liang, Teng Wang, Daoan Zhang, Jie An, Jingyang Lin, Rongyi Zhu* · ([Awesome-LLMs-for-Video-Understanding](https://github.com/yunlong10/Awesome-LLMs-for-Video-Understanding) - yunlong10) ![Star](https://img.shields.io/github/stars/yunlong10/Awesome-LLMs-for-Video-Understanding.svg?style=social&label=Star)
- **OneLLM: One Framework to Align All Modalities with Language**, `arXiv, 2312.03700`, [arxiv](http://arxiv.org/abs/2312.03700v1), [pdf](http://arxiv.org/pdf/2312.03700v1.pdf), cication: [**-1**](None)

	 *Jiaming Han, Kaixiong Gong, Yiyuan Zhang, Jiaqi Wang, Kaipeng Zhang, Dahua Lin, Yu Qiao, Peng Gao, Xiangyu Yue*

	 · ([onellm](https://github.com/csuhan/onellm) - csuhan) ![Star](https://img.shields.io/github/stars/csuhan/onellm.svg?style=social&label=Star)
- **CoDi-2: In-Context, Interleaved, and Interactive Any-to-Any Generation**, `arXiv, 2311.18775`, [arxiv](http://arxiv.org/abs/2311.18775v1), [pdf](http://arxiv.org/pdf/2311.18775v1.pdf), cication: [**-1**](None)

	 *Zineng Tang, Ziyi Yang, Mahmoud Khademi, Yang Liu, Chenguang Zhu, Mohit Bansal* · ([i-Code](https://github.com/microsoft/i-Code/tree/main/CoDi-2) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social&label=Star) · ([codi-2.github](https://codi-2.github.io/))
- **LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models**, `arXiv, 2311.17043`, [arxiv](http://arxiv.org/abs/2311.17043v1), [pdf](http://arxiv.org/pdf/2311.17043v1.pdf), cication: [**-1**](None)

	 *Yanwei Li, Chengyao Wang, Jiaya Jia* · ([llama-vid](https://github.com/dvlab-research/llama-vid) - dvlab-research) ![Star](https://img.shields.io/github/stars/dvlab-research/llama-vid.svg?style=social&label=Star)
- **Chat-UniVi: Unified Visual Representation Empowers Large Language Models
  with Image and Video Understanding**, `arXiv, 2311.08046`, [arxiv](http://arxiv.org/abs/2311.08046v1), [pdf](http://arxiv.org/pdf/2311.08046v1.pdf), cication: [**-1**](None)

	 *Peng Jin, Ryuichi Takanobu, Caiwan Zhang, Xiaochun Cao, Li Yuan* · ([Chat-UniVi](https://github.com/PKU-YuanGroup/Chat-UniVi) - PKU-YuanGroup) ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Chat-UniVi.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/spaces/Chat-UniVi/Chat-UniVi)) · ([qbitai](https://www.qbitai.com/2023/11/101783.html))
- **Mirasol3B: A Multimodal Autoregressive model for time-aligned and
  contextual modalities**, `arXiv, 2311.05698`, [arxiv](http://arxiv.org/abs/2311.05698v2), [pdf](http://arxiv.org/pdf/2311.05698v2.pdf), cication: [**-1**](None)

	 *AJ Piergiovanni, Isaac Noble, Dahun Kim, Michael S. Ryoo, Victor Gomes, Anelia Angelova*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-28-10))
- **UniRepLKNet: A Universal Perception Large-Kernel ConvNet for Audio,
  Video, Point Cloud, Time-Series and Image Recognition**, `arXiv, 2311.15599`, [arxiv](http://arxiv.org/abs/2311.15599v1), [pdf](http://arxiv.org/pdf/2311.15599v1.pdf), cication: [**-1**](None)

	 *Xiaohan Ding, Yiyuan Zhang, Yixiao Ge, Sijie Zhao, Lin Song, Xiangyu Yue, Ying Shan*
- **PG-Video-LLaVA: Pixel Grounding Large Video-Language Models**, `arXiv, 2311.13435`, [arxiv](http://arxiv.org/abs/2311.13435v1), [pdf](http://arxiv.org/pdf/2311.13435v1.pdf), cication: [**-1**](None)

	 *Shehan Munasinghe, Rusiru Thushara, Muhammad Maaz, Hanoona Abdul Rasheed, Salman Khan, Mubarak Shah, Fahad Khan*
- **VideoCon: Robust Video-Language Alignment via Contrast Captions**, `arXiv, 2311.10111`, [arxiv](http://arxiv.org/abs/2311.10111v1), [pdf](http://arxiv.org/pdf/2311.10111v1.pdf), cication: [**-1**](None)

	 *Hritik Bansal, Yonatan Bitton, Idan Szpektor, Kai-Wei Chang, Aditya Grover*
- **Video-LLaVA: Learning United Visual Representation by Alignment Before
  Projection**, `arXiv, 2311.10122`, [arxiv](http://arxiv.org/abs/2311.10122v1), [pdf](http://arxiv.org/pdf/2311.10122v1.pdf), cication: [**-1**](None)

	 *Bin Lin, Bin Zhu, Yang Ye, Munan Ning, Peng Jin, Li Yuan*
- **ST-LLM: Large Language Models Are Effective Temporal Learners**, `arXiv, 2404.00308`, [arxiv](http://arxiv.org/abs/2404.00308v1), [pdf](http://arxiv.org/pdf/2404.00308v1.pdf), cication: [**-1**](None)

	 *Ruyang Liu, Chen Li, Haoran Tang, Yixiao Ge, Ying Shan, Ge Li*

	 · ([ST-LLM](https://github.com/TencentARC/ST-LLM) - TencentARC) ![Star](https://img.shields.io/github/stars/TencentARC/ST-LLM.svg?style=social&label=Star)
- **Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video
  Understanding**, `arXiv, 2306.02858`, [arxiv](http://arxiv.org/abs/2306.02858v4), [pdf](http://arxiv.org/pdf/2306.02858v4.pdf), cication: [**39**](https://scholar.google.com/scholar?cites=243345481669305195&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hang Zhang, Xin Li, Lidong Bing*
	 · [[Video-LLaMA](https://github.com/DAMO-NLP-SG/Video-LLaMA) - DAMO-NLP-SG] ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/Video-LLaMA.svg?style=social&label=Star)
### Image
- **Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs**, `arXiv, 2404.05719`, [arxiv](http://arxiv.org/abs/2404.05719v1), [pdf](http://arxiv.org/pdf/2404.05719v1.pdf), cication: [**-1**](None)

	 *Keen You, Haotian Zhang, Eldon Schoop, Floris Weers, Amanda Swearngin, Jeffrey Nichols, Yinfei Yang, Zhe Gan*
- **No "Zero-Shot" Without Exponential Data: Pretraining Concept Frequency
  Determines Multimodal Model Performance**, `arXiv, 2404.04125`, [arxiv](http://arxiv.org/abs/2404.04125v1), [pdf](http://arxiv.org/pdf/2404.04125v1.pdf), cication: [**-1**](None)

	 *Vishaal Udandarao, Ameya Prabhu, Adhiraj Ghosh, Yash Sharma, Philip H. S. Torr, Adel Bibi, Samuel Albanie, Matthias Bethge* · ([huggingface](https://huggingface.co/datasets/bethgelab/Let-It-Wag)) · ([frequency_determines_performance](https://github.com/bethgelab/frequency_determines_performance) - bethgelab) ![Star](https://img.shields.io/github/stars/bethgelab/frequency_determines_performance.svg?style=social&label=Star)
- **LLaVA-Gemma: Accelerating Multimodal Foundation Models with a Compact
  Language Model**, `arXiv, 2404.01331`, [arxiv](http://arxiv.org/abs/2404.01331v1), [pdf](http://arxiv.org/pdf/2404.01331v1.pdf), cication: [**-1**](None)

	 *Musashi Hinck, Matthew L. Olson, David Cobbley, Shao-Yen Tseng, Vasudev Lal*
- **Noise-Aware Training of Layout-Aware Language Models**, `arXiv, 2404.00488`, [arxiv](http://arxiv.org/abs/2404.00488v1), [pdf](http://arxiv.org/pdf/2404.00488v1.pdf), cication: [**-1**](None)

	 *Ritesh Sarkhel, Xiaoqi Ren, Lauro Beltrao Costa, Guolong Su, Vincent Perot, Yanan Xie, Emmanouil Koukoumidis, Arnab Nandi*
- **Mini-Gemini: Mining the Potential of Multi-modality Vision Language
  Models**, `arXiv, 2403.18814`, [arxiv](http://arxiv.org/abs/2403.18814v1), [pdf](http://arxiv.org/pdf/2403.18814v1.pdf), cication: [**-1**](None)

	 *Yanwei Li, Yuechen Zhang, Chengyao Wang, Zhisheng Zhong, Yixin Chen, Ruihang Chu, Shaoteng Liu, Jiaya Jia* · ([MiniGemini](https://github.com/dvlab-research/MiniGemini) - dvlab-research) ![Star](https://img.shields.io/github/stars/dvlab-research/MiniGemini.svg?style=social&label=Star)
	- `Mini-Gemini is a framework aimed at improving multi-modal vision language models (VLMs) through high-resolution visual tokens, a high-quality dataset, and VLM-guided generation.`
- **MyVLM: Personalizing VLMs for User-Specific Queries**, `arXiv, 2403.14599`, [arxiv](http://arxiv.org/abs/2403.14599v1), [pdf](http://arxiv.org/pdf/2403.14599v1.pdf), cication: [**-1**](None)

	 *Yuval Alaluf, Elad Richardson, Sergey Tulyakov, Kfir Aberman, Daniel Cohen-Or*
- **MathVerse: Does Your Multi-modal LLM Truly See the Diagrams in Visual
  Math Problems?**, `arXiv, 2403.14624`, [arxiv](http://arxiv.org/abs/2403.14624v1), [pdf](http://arxiv.org/pdf/2403.14624v1.pdf), cication: [**-1**](None)

	 *Renrui Zhang, Dongzhi Jiang, Yichi Zhang, Haokun Lin, Ziyu Guo, Pengshuo Qiu, Aojun Zhou, Pan Lu, Kai-Wei Chang, Peng Gao*
- **HyperLLaVA: Dynamic Visual and Language Expert Tuning for Multimodal
  Large Language Models**, `arXiv, 2403.13447`, [arxiv](http://arxiv.org/abs/2403.13447v1), [pdf](http://arxiv.org/pdf/2403.13447v1.pdf), cication: [**-1**](None)

	 *Wenqiao Zhang, Tianwei Lin, Jiang Liu, Fangxun Shu, Haoyuan Li, Lei Zhang, He Wanggui, Hao Zhou, Zheqi Lv, Hao Jiang* · ([HyperLLaVA](https://github.com/DCDmllm/HyperLLaVA) - DCDmllm) ![Star](https://img.shields.io/github/stars/DCDmllm/HyperLLaVA.svg?style=social&label=Star)
- **Chart-based Reasoning: Transferring Capabilities from LLMs to VLMs**, `arXiv, 2403.12596`, [arxiv](http://arxiv.org/abs/2403.12596v1), [pdf](http://arxiv.org/pdf/2403.12596v1.pdf), cication: [**-1**](None)

	 *Victor Carbune, Hassan Mansoor, Fangyu Liu, Rahul Aralikatte, Gilles Baechler, Jindong Chen, Abhanshu Sharma*
- **mPLUG-DocOwl 1.5: Unified Structure Learning for OCR-free Document
  Understanding**, `arXiv, 2403.12895`, [arxiv](http://arxiv.org/abs/2403.12895v1), [pdf](http://arxiv.org/pdf/2403.12895v1.pdf), cication: [**-1**](None)

	 *Anwen Hu, Haiyang Xu, Jiabo Ye, Ming Yan, Liang Zhang, Bo Zhang, Chen Li, Ji Zhang, Qin Jin, Fei Huang* · ([mPLUG-DocOwl](https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/DocOwl1.5) - X-PLUG) ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-DocOwl.svg?style=social&label=Star)
- **LLaVA-UHD: an LMM Perceiving Any Aspect Ratio and High-Resolution Images**, `arXiv, 2403.11703`, [arxiv](http://arxiv.org/abs/2403.11703v1), [pdf](http://arxiv.org/pdf/2403.11703v1.pdf), cication: [**-1**](None)

	 *Ruyi Xu, Yuan Yao, Zonghao Guo, Junbo Cui, Zanlin Ni, Chunjiang Ge, Tat-Seng Chua, Zhiyuan Liu, Maosong Sun, Gao Huang* · ([LLaVA-UHD](https://github.com/thunlp/LLaVA-UHD) - thunlp) ![Star](https://img.shields.io/github/stars/thunlp/LLaVA-UHD.svg?style=social&label=Star)
- **Uni-SMART: Universal Science Multimodal Analysis and Research
  Transformer**, `arXiv, 2403.10301`, [arxiv](http://arxiv.org/abs/2403.10301v1), [pdf](http://arxiv.org/pdf/2403.10301v1.pdf), cication: [**-1**](None)

	 *Hengxing Cai, Xiaochen Cai, Shuwen Yang, Jiankun Wang, Lin Yao, Zhifeng Gao, Junhan Chang, Sihang Li, Mingjun Xu, Changxin Wang*
- **Griffon v2: Advancing Multimodal Perception with High-Resolution Scaling
  and Visual-Language Co-Referring**, `arXiv, 2403.09333`, [arxiv](http://arxiv.org/abs/2403.09333v1), [pdf](http://arxiv.org/pdf/2403.09333v1.pdf), cication: [**-1**](None)

	 *Yufei Zhan, Yousong Zhu, Hongyin Zhao, Fan Yang, Ming Tang, Jinqiao Wang*

	 · ([Griffon](https://github.com/jefferyZhan/Griffon) - jefferyZhan) ![Star](https://img.shields.io/github/stars/jefferyZhan/Griffon.svg?style=social&label=Star)
- **GiT: Towards Generalist Vision Transformer through Universal Language
  Interface**, `arXiv, 2403.09394`, [arxiv](http://arxiv.org/abs/2403.09394v1), [pdf](http://arxiv.org/pdf/2403.09394v1.pdf), cication: [**-1**](None)

	 *Haiyang Wang, Hao Tang, Li Jiang, Shaoshuai Shi, Muhammad Ferjad Naeem, Hongsheng Li, Bernt Schiele, Liwei Wang*

	 · ([GiT](https://github.com/Haiyang-W/GiT) - Haiyang-W) ![Star](https://img.shields.io/github/stars/Haiyang-W/GiT.svg?style=social&label=Star)
	- `GiT is a framework leveraging a basic Vision Transformer (ViT) for a wide range of vision tasks that is focused on simplifying the architecture by using a universal language interface for tasks like captioning, detection, and segmentation.`
- **MM1: Methods, Analysis & Insights from Multimodal LLM Pre-training**, `arXiv, 2403.09611`, [arxiv](http://arxiv.org/abs/2403.09611v1), [pdf](http://arxiv.org/pdf/2403.09611v1.pdf), cication: [**-1**](None)

	 *Brandon McKinzie, Zhe Gan, Jean-Philippe Fauconnier, Sam Dodge, Bowen Zhang, Philipp Dufter, Dhruti Shah, Xianzhi Du, Futang Peng, Floris Weers*
	- `advances multimodal LLMs by analyzing architecture and data strategies and proposes the 30B MM1 model series, which excels in pretraining and finetuning across benchmarks.`
	- *NOTE*
- **MoAI: Mixture of All Intelligence for Large Language and Vision Models**, `arXiv, 2403.07508`, [arxiv](http://arxiv.org/abs/2403.07508v1), [pdf](http://arxiv.org/pdf/2403.07508v1.pdf), cication: [**-1**](None)

	 *Byung-Kwan Lee, Beomchan Park, Chae Won Kim, Yong Man Ro*

	 · ([MoAI](https://github.com/ByungKwanLee/MoAI) - ByungKwanLee) ![Star](https://img.shields.io/github/stars/ByungKwanLee/MoAI.svg?style=social&label=Star)
- **DeepSeek-VL: Towards Real-World Vision-Language Understanding**, `arXiv, 2403.05525`, [arxiv](http://arxiv.org/abs/2403.05525v1), [pdf](http://arxiv.org/pdf/2403.05525v1.pdf), cication: [**-1**](None)

	 *Haoyu Lu, Wen Liu, Bo Zhang, Bingxuan Wang, Kai Dong, Bo Liu, Jingxiang Sun, Tongzheng Ren, Zhuoshu Li, Yaofeng Sun*

	 · ([DeepSeek-VL](https://github.com/deepseek-ai/DeepSeek-VL) - deepseek-ai) ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-VL.svg?style=social&label=Star)
- **RegionGPT: Towards Region Understanding Vision Language Model**, `arXiv, 2403.02330`, [arxiv](http://arxiv.org/abs/2403.02330v1), [pdf](http://arxiv.org/pdf/2403.02330v1.pdf), cication: [**-1**](None)

	 *Qiushan Guo, Shalini De Mello, Hongxu Yin, Wonmin Byeon, Ka Chun Cheung, Yizhou Yu, Ping Luo, Sifei Liu*
- **Multi-modal Instruction Tuned LLMs with Fine-grained Visual Perception**, `arXiv, 2403.02969`, [arxiv](http://arxiv.org/abs/2403.02969v1), [pdf](http://arxiv.org/pdf/2403.02969v1.pdf), cication: [**-1**](None)

	 *Junwen He, Yifan Wang, Lijun Wang, Huchuan Lu, Jun-Yan He, Jin-Peng Lan, Bin Luo, Xuansong Xie*

- **Enhancing Vision-Language Pre-training with Rich Supervisions**, `arXiv, 2403.03346`, [arxiv](http://arxiv.org/abs/2403.03346v1), [pdf](http://arxiv.org/pdf/2403.03346v1.pdf), cication: [**-1**](None)

	 *Yuan Gao, Kunyu Shi, Pengkai Zhu, Edouard Belval, Oren Nuriel, Srikar Appalaraju, Shabnam Ghadar, Vijay Mahadevan, Zhuowen Tu, Stefano Soatto*
	- Strongly Supervised pretraining with ScreenShots (S4) introduces a new pretraining approach for vision-LLMs using web screenshots along with leveraging the inherent tree-structured hierarchy of HTML elements. 
- **Feast Your Eyes: Mixture-of-Resolution Adaptation for Multimodal Large
  Language Models**, `arXiv, 2403.03003`, [arxiv](http://arxiv.org/abs/2403.03003v1), [pdf](http://arxiv.org/pdf/2403.03003v1.pdf), cication: [**-1**](None)

	 *Gen Luo, Yiyi Zhou, Yuxin Zhang, Xiawu Zheng, Xiaoshuai Sun, Rongrong Ji* · ([LLaVA-HR](https://github.com/luogen1996/LLaVA-HR) - luogen1996) ![Star](https://img.shields.io/github/stars/luogen1996/LLaVA-HR.svg?style=social&label=Star)
- **Finetuned Multimodal Language Models Are High-Quality Image-Text Data
  Filters**, `arXiv, 2403.02677`, [arxiv](http://arxiv.org/abs/2403.02677v1), [pdf](http://arxiv.org/pdf/2403.02677v1.pdf), cication: [**-1**](None)

	 *Weizhi Wang, Khalil Mrini, Linjie Yang, Sateesh Kumar, Yu Tian, Xifeng Yan, Heng Wang*
- **InfiMM-HD: A Leap Forward in High-Resolution Multimodal Understanding**, `arXiv, 2403.01487`, [arxiv](http://arxiv.org/abs/2403.01487v1), [pdf](http://arxiv.org/pdf/2403.01487v1.pdf), cication: [**-1**](None)

	 *Haogeng Liu, Quanzeng You, Xiaotian Han, Yiqi Wang, Bohan Zhai, Yongfei Liu, Yunzhe Tao, Huaibo Huang, Ran He, Hongxia Yang*
- **ScreenAI: A Vision-Language Model for UI and Infographics Understanding**, `arXiv, 2402.04615`, [arxiv](http://arxiv.org/abs/2402.04615v2), [pdf](http://arxiv.org/pdf/2402.04615v2.pdf), cication: [**-1**](None)

	 *Gilles Baechler, Srinivas Sunkara, Maria Wang, Fedir Zubach, Hassan Mansoor, Vincent Etter, Victor Cărbune, Jason Lin, Jindong Chen, Abhanshu Sharma* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652450859&idx=3&sn=6f66af61606ce574b7755a17e9ac8c6c))
- **VisionLLaMA: A Unified LLaMA Interface for Vision Tasks**, `arXiv, 2403.00522`, [arxiv](http://arxiv.org/abs/2403.00522v1), [pdf](http://arxiv.org/pdf/2403.00522v1.pdf), cication: [**-1**](None)

	 *Xiangxiang Chu, Jianlin Su, Bo Zhang, Chunhua Shen* · ([VisionLLaMA](https://github.com/Meituan-AutoML/VisionLLaMA) - Meituan-AutoML) ![Star](https://img.shields.io/github/stars/Meituan-AutoML/VisionLLaMA.svg?style=social&label=Star)
- **Subobject-level Image Tokenization**, `arXiv, 2402.14327`, [arxiv](http://arxiv.org/abs/2402.14327v1), [pdf](http://arxiv.org/pdf/2402.14327v1.pdf), cication: [**-1**](None)

	 *Delong Chen, Samuel Cahyawijaya, Jianfeng Liu, Baoyuan Wang, Pascale Fung* · ([subobjects](https://github.com/ChenDelong1999/subobjects) - ChenDelong1999) ![Star](https://img.shields.io/github/stars/ChenDelong1999/subobjects.svg?style=social&label=Star)
- **TinyLLaVA: A Framework of Small-scale Large Multimodal Models**, `arXiv, 2402.14289`, [arxiv](http://arxiv.org/abs/2402.14289v1), [pdf](http://arxiv.org/pdf/2402.14289v1.pdf), cication: [**-1**](None)

	 *Baichuan Zhou, Ying Hu, Xi Weng, Junlong Jia, Jie Luo, Xien Liu, Ji Wu, Lei Huang*
- **PALO: A Polyglot Large Multimodal Model for 5B People**, `arXiv, 2402.14818`, [arxiv](http://arxiv.org/abs/2402.14818v1), [pdf](http://arxiv.org/pdf/2402.14818v1.pdf), cication: [**-1**](None)

	 *Muhammad Maaz, Hanoona Rasheed, Abdelrahman Shaker, Salman Khan, Hisham Cholakal, Rao M. Anwer, Tim Baldwin, Michael Felsberg, Fahad S. Khan* · ([PALO](https://github.com/mbzuai-oryx/PALO) - mbzuai-oryx) ![Star](https://img.shields.io/github/stars/mbzuai-oryx/PALO.svg?style=social&label=Star) · ([palo.mbzuai-oryx.ngrok](https://palo.mbzuai-oryx.ngrok.app/))
- **ALLaVA: Harnessing GPT4V-synthesized Data for A Lite Vision-Language
  Model**, `arXiv, 2402.11684`, [arxiv](http://arxiv.org/abs/2402.11684v1), [pdf](http://arxiv.org/pdf/2402.11684v1.pdf), cication: [**-1**](None)

	 *Guiming Hardy Chen, Shunian Chen, Ruifei Zhang, Junying Chen, Xiangbo Wu, Zhiyi Zhang, Zhihong Chen, Jianquan Li, Xiang Wan, Benyou Wang*
- **Vision-Flan: Scaling Human-Labeled Tasks in Visual Instruction Tuning**, `arXiv, 2402.11690`, [arxiv](http://arxiv.org/abs/2402.11690v1), [pdf](http://arxiv.org/pdf/2402.11690v1.pdf), cication: [**-1**](None)

	 *Zhiyang Xu, Chao Feng, Rulin Shao, Trevor Ashby, Ying Shen, Di Jin, Yu Cheng, Qifan Wang, Lifu Huang*
- **CoLLaVO: Crayon Large Language and Vision mOdel**, `arXiv, 2402.11248`, [arxiv](http://arxiv.org/abs/2402.11248v2), [pdf](http://arxiv.org/pdf/2402.11248v2.pdf), cication: [**-1**](None)

	 *Byung-Kwan Lee, Beomchan Park, Chae Won Kim, Yong Man Ro*
- **FinTral: A Family of GPT-4 Level Multimodal Financial Large Language
  Models**, `arXiv, 2402.10986`, [arxiv](http://arxiv.org/abs/2402.10986v1), [pdf](http://arxiv.org/pdf/2402.10986v1.pdf), cication: [**-1**](None)

	 *Gagan Bhatia, El Moatez Billah Nagoudi, Hasan Cavusoglu, Muhammad Abdul-Mageed*
- **PaLM2-VAdapter: Progressively Aligned Language Model Makes a Strong
  Vision-language Adapter**, `arXiv, 2402.10896`, [arxiv](http://arxiv.org/abs/2402.10896v1), [pdf](http://arxiv.org/pdf/2402.10896v1.pdf), cication: [**-1**](None)

	 *Junfei Xiao, Zheng Xu, Alan Yuille, Shen Yan, Boyu Wang*
- **Lumos : Empowering Multimodal LLMs with Scene Text Recognition**, `arXiv, 2402.08017`, [arxiv](http://arxiv.org/abs/2402.08017v1), [pdf](http://arxiv.org/pdf/2402.08017v1.pdf), cication: [**-1**](None)

	 *Ashish Shenoy, Yichao Lu, Srihari Jayakumar, Debojeet Chatterjee, Mohsen Moslehpour, Pierce Chuang, Abhay Harpale, Vikas Bhardwaj, Di Xu, Shicong Zhao*
- **Prismatic VLMs: Investigating the Design Space of Visually-Conditioned
  Language Models**, `arXiv, 2402.07865`, [arxiv](http://arxiv.org/abs/2402.07865v1), [pdf](http://arxiv.org/pdf/2402.07865v1.pdf), cication: [**-1**](None)

	 *Siddharth Karamcheti, Suraj Nair, Ashwin Balakrishna, Percy Liang, Thomas Kollar, Dorsa Sadigh*

	 · ([prismatic-vlms](https://github.com/TRI-ML/prismatic-vlms) - TRI-ML) ![Star](https://img.shields.io/github/stars/TRI-ML/prismatic-vlms.svg?style=social&label=Star) · ([vlm-evaluation](https://github.com/TRI-ML/vlm-evaluation) - TRI-ML) ![Star](https://img.shields.io/github/stars/TRI-ML/vlm-evaluation.svg?style=social&label=Star)
	- *NOTE* 
- **PIVOT: Iterative Visual Prompting Elicits Actionable Knowledge for VLMs**, `arXiv, 2402.07872`, [arxiv](http://arxiv.org/abs/2402.07872v1), [pdf](http://arxiv.org/pdf/2402.07872v1.pdf), cication: [**-1**](None)

	 *Soroush Nasiriany, Fei Xia, Wenhao Yu, Ted Xiao, Jacky Liang, Ishita Dasgupta, Annie Xie, Danny Driess, Ayzaan Wahid, Zhuo Xu* · ([huggingface](https://huggingface.co/spaces/pivot-prompt/pivot-prompt-demo))
- **Question Aware Vision Transformer for Multimodal Reasoning**, `arXiv, 2402.05472`, [arxiv](http://arxiv.org/abs/2402.05472v1), [pdf](http://arxiv.org/pdf/2402.05472v1.pdf), cication: [**-1**](None)

	 *Roy Ganz, Yair Kittenplon, Aviad Aberdam, Elad Ben Avraham, Oren Nuriel, Shai Mazor, Ron Litman*
- **SPHINX-X: Scaling Data and Parameters for a Family of Multi-modal Large
  Language Models**, `arXiv, 2402.05935`, [arxiv](http://arxiv.org/abs/2402.05935v1), [pdf](http://arxiv.org/pdf/2402.05935v1.pdf), cication: [**-1**](None)

	 *Peng Gao, Renrui Zhang, Chris Liu, Longtian Qiu, Siyuan Huang, Weifeng Lin, Shitian Zhao, Shijie Geng, Ziyi Lin, Peng Jin* · ([LLaMA2-Accessory](https://github.com/Alpha-VLLM/LLaMA2-Accessory) - Alpha-VLLM) ![Star](https://img.shields.io/github/stars/Alpha-VLLM/LLaMA2-Accessory.svg?style=social&label=Star)
- **ScreenAI: A Vision-Language Model for UI and Infographics Understanding**, `arXiv, 2402.04615`, [arxiv](http://arxiv.org/abs/2402.04615v1), [pdf](http://arxiv.org/pdf/2402.04615v1.pdf), cication: [**-1**](None)

	 *Gilles Baechler, Srinivas Sunkara, Maria Wang, Fedir Zubach, Hassan Mansoor, Vincent Etter, Victor Cărbune, Jason Lin, Jindong Chen, Abhanshu Sharma*
- **MobileVLM V2: Faster and Stronger Baseline for Vision Language Model**, `arXiv, 2402.03766`, [arxiv](http://arxiv.org/abs/2402.03766v1), [pdf](http://arxiv.org/pdf/2402.03766v1.pdf), cication: [**-1**](None)

	 *Xiangxiang Chu, Limeng Qiao, Xinyu Zhang, Shuang Xu, Fei Wei, Yang Yang, Xiaofei Sun, Yiming Hu, Xinyang Lin, Bo Zhang* · ([MobileVLM](https://github.com/Meituan-AutoML/MobileVLM) - Meituan-AutoML) ![Star](https://img.shields.io/github/stars/Meituan-AutoML/MobileVLM.svg?style=social&label=Star)
- **EVA-CLIP-18B: Scaling CLIP to 18 Billion Parameters**, `arXiv, 2402.04252`, [arxiv](http://arxiv.org/abs/2402.04252v1), [pdf](http://arxiv.org/pdf/2402.04252v1.pdf), cication: [**-1**](None)

	 *Quan Sun, Jinsheng Wang, Qiying Yu, Yufeng Cui, Fan Zhang, Xiaosong Zhang, Xinlong Wang*
- **CogCoM: Train Large Vision-Language Models Diving into Details through
  Chain of Manipulations**, `arXiv, 2402.04236`, [arxiv](http://arxiv.org/abs/2402.04236v1), [pdf](http://arxiv.org/pdf/2402.04236v1.pdf), cication: [**-1**](None)

	 *Ji Qi, Ming Ding, Weihan Wang, Yushi Bai, Qingsong Lv, Wenyi Hong, Bin Xu, Lei Hou, Juanzi Li, Yuxiao Dong*
- [**OmniLMM**](https://github.com/OpenBMB/OmniLMM) - OpenBMB ![Star](https://img.shields.io/github/stars/OpenBMB/OmniLMM.svg?style=social&label=Star)

	 *Large Multi-modal Models for Strong Performance and Efficient Deployment* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652439897&idx=1&sn=e5e9a0ab370aaf6b4bd0e8a0ee64e814))
- **MM-Interleaved: Interleaved Image-Text Generative Modeling via
  Multi-modal Feature Synchronizer**, `arXiv, 2401.10208`, [arxiv](http://arxiv.org/abs/2401.10208v1), [pdf](http://arxiv.org/pdf/2401.10208v1.pdf), cication: [**-1**](None)

	 *Changyao Tian, Xizhou Zhu, Yuwen Xiong, Weiyun Wang, Zhe Chen, Wenhai Wang, Yuntao Chen, Lewei Lu, Tong Lu, Jie Zhou* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-02-01-4)) · ([MM-Interleaved](https://github.com/OpenGVLab/MM-Interleaved) - OpenGVLab) ![Star](https://img.shields.io/github/stars/OpenGVLab/MM-Interleaved.svg?style=social&label=Star)
- **Octavius: Mitigating Task Interference in MLLMs via MoE**, `arXiv, 2311.02684`, [arxiv](http://arxiv.org/abs/2311.02684v1), [pdf](http://arxiv.org/pdf/2311.02684v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=12245060539687688497&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zeren Chen, Ziqin Wang, Zhen Wang, Huayang Liu, Zhenfei Yin, Si Liu, Lu Sheng, Wanli Ouyang, Yu Qiao, Jing Shao* · ([openlamm.github](https://openlamm.github.io/paper_list/Octavius))
- **Enhancing Multimodal Large Language Models with Vision Detection Models:
  An Empirical Study**, `arXiv, 2401.17981`, [arxiv](http://arxiv.org/abs/2401.17981v1), [pdf](http://arxiv.org/pdf/2401.17981v1.pdf), cication: [**-1**](None)

	 *Qirui Jiao, Daoyuan Chen, Yilun Huang, Yaliang Li, Ying Shen*
- **Overcoming the Pitfalls of Vision-Language Model Finetuning for OOD
  Generalization**, `arXiv, 2401.15914`, [arxiv](http://arxiv.org/abs/2401.15914v1), [pdf](http://arxiv.org/pdf/2401.15914v1.pdf), cication: [**-1**](None)

	 *Yuhang Zang, Hanlin Goh, Josh Susskind, Chen Huang*
- **MouSi: Poly-Visual-Expert Vision-Language Models**, `arXiv, 2401.17221`, [arxiv](http://arxiv.org/abs/2401.17221v1), [pdf](http://arxiv.org/pdf/2401.17221v1.pdf), cication: [**-1**](None)

	 *Xiaoran Fan, Tao Ji, Changhao Jiang, Shuo Li, Senjie Jin, Sirui Song, Junke Wang, Boyang Hong, Lu Chen, Guodong Zheng*
- **LLaVA-Phi: Efficient Multi-Modal Assistant with Small Language Model**, `arXiv, 2401.02330`, [arxiv](http://arxiv.org/abs/2401.02330v2), [pdf](http://arxiv.org/pdf/2401.02330v2.pdf), cication: [**-1**](None)

	 *Yichen Zhu, Minjie Zhu, Ning Liu, Zhicai Ou, Xiaofeng Mou, Jian Tang* · ([llava-phi](https://github.com/zhuyiche/llava-phi?tab=readme-ov-file) - zhuyiche) ![Star](https://img.shields.io/github/stars/zhuyiche/llava-phi.svg?style=social&label=Star)
- **InternLM-XComposer2: Mastering Free-form Text-Image Composition and
  Comprehension in Vision-Language Large Model**, `arXiv, 2401.16420`, [arxiv](http://arxiv.org/abs/2401.16420v1), [pdf](http://arxiv.org/pdf/2401.16420v1.pdf), cication: [**-1**](None)

	 *Xiaoyi Dong, Pan Zhang, Yuhang Zang, Yuhang Cao, Bin Wang, Linke Ouyang, Xilin Wei, Songyang Zhang, Haodong Duan, Maosong Cao* · ([InternLM-XComposer](https://github.com/InternLM/InternLM-XComposer?tab=readme-ov-file) - InternLM) ![Star](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star)
- **MoE-LLaVA: Mixture of Experts for Large Vision-Language Models**, `arXiv, 2401.15947`, [arxiv](http://arxiv.org/abs/2401.15947v1), [pdf](http://arxiv.org/pdf/2401.15947v1.pdf), cication: [**-1**](None)

	 *Bin Lin, Zhenyu Tang, Yang Ye, Jiaxi Cui, Bin Zhu, Peng Jin, Junwu Zhang, Munan Ning, Li Yuan* · ([MoE-LLaVA](https://github.com/PKU-YuanGroup/MoE-LLaVA) - PKU-YuanGroup) ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/MoE-LLaVA.svg?style=social&label=Star)
- **Small Language Model Meets with Reinforced Vision Vocabulary**, `arXiv, 2401.12503`, [arxiv](http://arxiv.org/abs/2401.12503v1), [pdf](http://arxiv.org/pdf/2401.12503v1.pdf), cication: [**-1**](None)

	 *Haoran Wei, Lingyu Kong, Jinyue Chen, Liang Zhao, Zheng Ge, En Yu, Jianjian Sun, Chunrui Han, Xiangyu Zhang* · ([Vary-toy](https://github.com/Ucas-HaoranWei/Vary-toy) - Ucas-HaoranWei) ![Star](https://img.shields.io/github/stars/Ucas-HaoranWei/Vary-toy.svg?style=social&label=Star) · ([qbitai](https://www.qbitai.com/2024/01/117000.html))
- **ShareGPT4V: Improving Large Multi-Modal Models with Better Captions**, `arXiv, 2311.12793`, [arxiv](http://arxiv.org/abs/2311.12793v2), [pdf](http://arxiv.org/pdf/2311.12793v2.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=7333634103049317300&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lin Chen, Jinsong Li, Xiaoyi Dong, Pan Zhang, Conghui He, Jiaqi Wang, Feng Zhao, Dahua Lin* · ([sharegpt4v.github](https://sharegpt4v.github.io/)) · ([InternLM-XComposer](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) - InternLM) ![Star](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/spaces/Lin-Chen/ShareGPT4V-7B))
- **Multimodal Pathway: Improve Transformers with Irrelevant Data from Other
  Modalities**, `arXiv, 2401.14405`, [arxiv](http://arxiv.org/abs/2401.14405v1), [pdf](http://arxiv.org/pdf/2401.14405v1.pdf), cication: [**-1**](None)

	 *Yiyuan Zhang, Xiaohan Ding, Kaixiong Gong, Yixiao Ge, Ying Shan, Xiangyu Yue* · ([M2PT](https://github.com/AILab-CVC/M2PT) - AILab-CVC) ![Star](https://img.shields.io/github/stars/AILab-CVC/M2PT.svg?style=social&label=Star)
- **ConTextual: Evaluating Context-Sensitive Text-Rich Visual Reasoning in
  Large Multimodal Models**, `arXiv, 2401.13311`, [arxiv](http://arxiv.org/abs/2401.13311v1), [pdf](http://arxiv.org/pdf/2401.13311v1.pdf), cication: [**-1**](None)

	 *Rohan Wadhawan, Hritik Bansal, Kai-Wei Chang, Nanyun Peng* · ([con-textual.github](https://con-textual.github.io/))

	 · ([huggingface](https://huggingface.co/blog/leaderboard-contextual))
- **SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning
  Capabilities**, `arXiv, 2401.12168`, [arxiv](http://arxiv.org/abs/2401.12168v1), [pdf](http://arxiv.org/pdf/2401.12168v1.pdf), cication: [**-1**](None)

	 *Boyuan Chen, Zhuo Xu, Sean Kirmani, Brian Ichter, Danny Driess, Pete Florence, Dorsa Sadigh, Leonidas Guibas, Fei Xia* · ([spatial-vlm.github](https://spatial-vlm.github.io/))
- **Improving fine-grained understanding in image-text pre-training**, `arXiv, 2401.09865`, [arxiv](http://arxiv.org/abs/2401.09865v1), [pdf](http://arxiv.org/pdf/2401.09865v1.pdf), cication: [**-1**](None)

	 *Ioana Bica, Anastasija Ilić, Matthias Bauer, Goker Erdogan, Matko Bošnjak, Christos Kaplanis, Alexey A. Gritsenko, Matthias Minderer, Charles Blundell, Razvan Pascanu*
- **Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs**, `arXiv, 2401.06209`, [arxiv](http://arxiv.org/abs/2401.06209v1), [pdf](http://arxiv.org/pdf/2401.06209v1.pdf), cication: [**-1**](None)

	 *Shengbang Tong, Zhuang Liu, Yuexiang Zhai, Yi Ma, Yann LeCun, Saining Xie* · ([tsb0601.github](https://tsb0601.github.io/mmvp_blog/))

	 · ([MMVP](https://github.com/tsb0601/MMVP) - tsb0601) ![Star](https://img.shields.io/github/stars/tsb0601/MMVP.svg?style=social&label=Star)
- **GATS: Gather-Attend-Scatter**, `arXiv, 2401.08525`, [arxiv](http://arxiv.org/abs/2401.08525v1), [pdf](http://arxiv.org/pdf/2401.08525v1.pdf), cication: [**-1**](None)

	 *Konrad Zolna, Serkan Cabi, Yutian Chen, Eric Lau, Claudio Fantacci, Jurgis Pasukonis, Jost Tobias Springenberg, Sergio Gomez Colmenarejo*
- **Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs**, `arXiv, 2401.06209`, [arxiv](http://arxiv.org/abs/2401.06209v1), [pdf](http://arxiv.org/pdf/2401.06209v1.pdf), cication: [**-1**](None)

	 *Shengbang Tong, Zhuang Liu, Yuexiang Zhai, Yi Ma, Yann LeCun, Saining Xie* · ([MMVP](https://github.com/tsb0601/MMVP) - tsb0601) ![Star](https://img.shields.io/github/stars/tsb0601/MMVP.svg?style=social&label=Star)
- **LLaVA-$φ$: Efficient Multi-Modal Assistant with Small Language Model**, `arXiv, 2401.02330`, [arxiv](http://arxiv.org/abs/2401.02330v1), [pdf](http://arxiv.org/pdf/2401.02330v1.pdf), cication: [**-1**](None)

	 *Yichen Zhu, Minjie Zhu, Ning Liu, Zhicai Ou, Xiaofeng Mou, Jian Tang* · ([llava-phi](https://github.com/zhuyiche/llava-phi) - zhuyiche) ![Star](https://img.shields.io/github/stars/zhuyiche/llava-phi.svg?style=social&label=Star)
- **A Vision Check-up for Language Models**, `arXiv, 2401.01862`, [arxiv](http://arxiv.org/abs/2401.01862v1), [pdf](http://arxiv.org/pdf/2401.01862v1.pdf), cication: [**-1**](None)

	 *Pratyusha Sharma, Tamar Rott Shaham, Manel Baradad, Stephanie Fu, Adrian Rodriguez-Munoz, Shivam Duggal, Phillip Isola, Antonio Torralba*
- **DocLLM: A layout-aware generative language model for multimodal document
  understanding**, `arXiv, 2401.00908`, [arxiv](http://arxiv.org/abs/2401.00908v1), [pdf](http://arxiv.org/pdf/2401.00908v1.pdf), cication: [**-1**](None)

	 *Dongsheng Wang, Natraj Raman, Mathieu Sibue, Zhiqiang Ma, Petr Babkin, Simerjot Kaur, Yulong Pei, Armineh Nourbakhsh, Xiaomo Liu*
- **V*: Guided Visual Search as a Core Mechanism in Multimodal LLMs**, `arXiv, 2312.14135`, [arxiv](http://arxiv.org/abs/2312.14135v2), [pdf](http://arxiv.org/pdf/2312.14135v2.pdf), cication: [**-1**](None)

	 *Penghao Wu, Saining Xie* · ([vstar](https://github.com/penghao-wu/vstar) - penghao-wu) ![Star](https://img.shields.io/github/stars/penghao-wu/vstar.svg?style=social&label=Star)
- **Learning Vision from Models Rivals Learning Vision from Data**, `arXiv, 2312.17742`, [arxiv](http://arxiv.org/abs/2312.17742v1), [pdf](http://arxiv.org/pdf/2312.17742v1.pdf), cication: [**-1**](None)

	 *Yonglong Tian, Lijie Fan, Kaifeng Chen, Dina Katabi, Dilip Krishnan, Phillip Isola*
- **Parrot Captions Teach CLIP to Spot Text**, `arXiv, 2312.14232`, [arxiv](http://arxiv.org/abs/2312.14232v1), [pdf](http://arxiv.org/pdf/2312.14232v1.pdf), cication: [**-1**](None)

	 *Yiqi Lin, Conghui He, Alex Jinpeng Wang, Bin Wang, Weijia Li, Mike Zheng Shou*
- **Harnessing Diffusion Models for Visual Perception with Meta Prompts**, `arXiv, 2312.14733`, [arxiv](http://arxiv.org/abs/2312.14733v1), [pdf](http://arxiv.org/pdf/2312.14733v1.pdf), cication: [**-1**](None)

	 *Qiang Wan, Zilong Huang, Bingyi Kang, Jiashi Feng, Li Zhang* · ([meta-prompts](https://github.com/fudan-zvg/meta-prompts) - fudan-zvg) ![Star](https://img.shields.io/github/stars/fudan-zvg/meta-prompts.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652432856&idx=2&sn=aec76c63be2f2e264e2f3f3a7ae34e10&poc_token=HPAmrGWjbyEx5YDsFT2_tC4bunuulQpCZBIg6hx1))
- **VCoder: Versatile Vision Encoders for Multimodal Large Language Models**, `arXiv, 2312.14233`, [arxiv](http://arxiv.org/abs/2312.14233v1), [pdf](http://arxiv.org/pdf/2312.14233v1.pdf), cication: [**-1**](None)

	 *Jitesh Jain, Jianwei Yang, Humphrey Shi*

	 · ([VCoder](https://github.com/SHI-Labs/VCoder) - SHI-Labs) ![Star](https://img.shields.io/github/stars/SHI-Labs/VCoder.svg?style=social&label=Star) · ([praeclarumjj3.github](https://praeclarumjj3.github.io/vcoder/))
- **InternVL: Scaling up Vision Foundation Models and Aligning for Generic
  Visual-Linguistic Tasks**, `arXiv, 2312.14238`, [arxiv](http://arxiv.org/abs/2312.14238v2), [pdf](http://arxiv.org/pdf/2312.14238v2.pdf), cication: [**-1**](None)

	 *Zhe Chen, Jiannan Wu, Wenhai Wang, Weijie Su, Guo Chen, Sen Xing, Muyan Zhong, Qinglong Zhang, Xizhou Zhu, Lewei Lu*

	 · ([internvl](https://github.com/opengvlab/internvl) - opengvlab) ![Star](https://img.shields.io/github/stars/opengvlab/internvl.svg?style=social&label=Star) · ([internvl.opengvlab](https://internvl.opengvlab.com/))
- **Generative Multimodal Models are In-Context Learners**, `arXiv, 2312.13286`, [arxiv](http://arxiv.org/abs/2312.13286v1), [pdf](http://arxiv.org/pdf/2312.13286v1.pdf), cication: [**-1**](None)

	 *Quan Sun, Yufeng Cui, Xiaosong Zhang, Fan Zhang, Qiying Yu, Zhengxiong Luo, Yueze Wang, Yongming Rao, Jingjing Liu, Tiejun Huang* · ([Emu](https://github.com/baaivision/Emu) - baaivision) ![Star](https://img.shields.io/github/stars/baaivision/Emu.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/BAAI/Emu2))
- **Osprey: Pixel Understanding with Visual Instruction Tuning**, `arXiv, 2312.10032`, [arxiv](http://arxiv.org/abs/2312.10032v1), [pdf](http://arxiv.org/pdf/2312.10032v1.pdf), cication: [**-1**](None)

	 *Yuqian Yuan, Wentong Li, Jian Liu, Dongqi Tang, Xinjie Luo, Chi Qin, Lei Zhang, Jianke Zhu* · ([osprey](https://github.com/circleradon/osprey) - circleradon) ![Star](https://img.shields.io/github/stars/circleradon/osprey.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/sunshine-lwt/Osprey-7b/tree/main))
- **Gemini: A Family of Highly Capable Multimodal Models**, `arXiv, 2312.11805`, [arxiv](http://arxiv.org/abs/2312.11805v1), [pdf](http://arxiv.org/pdf/2312.11805v1.pdf), cication: [**-1**](None)

	 *Gemini Team, Rohan Anil, Sebastian Borgeaud, Yonghui Wu, Jean-Baptiste Alayrac, Jiahui Yu, Radu Soricut, Johan Schalkwyk, Andrew M. Dai, Anja Hauth*
- **Silkie: Preference Distillation for Large Visual Language Models**, `arXiv, 2312.10665`, [arxiv](http://arxiv.org/abs/2312.10665v1), [pdf](http://arxiv.org/pdf/2312.10665v1.pdf), cication: [**-1**](None)

	 *Lei Li, Zhihui Xie, Mukai Li, Shunian Chen, Peiyi Wang, Liang Chen, Yazheng Yang, Benyou Wang, Lingpeng Kong*
- **G-LLaVA: Solving Geometric Problem with Multi-Modal Large Language Model**, `arXiv, 2312.11370`, [arxiv](http://arxiv.org/abs/2312.11370v1), [pdf](http://arxiv.org/pdf/2312.11370v1.pdf), cication: [**-1**](None)

	 *Jiahui Gao, Renjie Pi, Jipeng Zhang, Jiacheng Ye, Wanjun Zhong, Yufei Wang, Lanqing Hong, Jianhua Han, Hang Xu, Zhenguo Li*
- **Merlin:Empowering Multimodal LLMs with Foresight Minds**, `arXiv, 2312.00589`, [arxiv](http://arxiv.org/abs/2312.00589v1), [pdf](http://arxiv.org/pdf/2312.00589v1.pdf), cication: [**-1**](None)

	 *En Yu, Liang Zhao, Yana Wei, Jinrong Yang, Dongming Wu, Lingyu Kong, Haoran Wei, Tiancai Wang, Zheng Ge, Xiangyu Zhang* · ([qbitai](https://www.qbitai.com/2023/12/106838.html))
- **VL-GPT: A Generative Pre-trained Transformer for Vision and Language
  Understanding and Generation**, `arXiv, 2312.09251`, [arxiv](http://arxiv.org/abs/2312.09251v1), [pdf](http://arxiv.org/pdf/2312.09251v1.pdf), cication: [**-1**](None)

	 *Jinguo Zhu, Xiaohan Ding, Yixiao Ge, Yuying Ge, Sijie Zhao, Hengshuang Zhao, Xiaohua Wang, Ying Shan*
- **Honeybee: Locality-enhanced Projector for Multimodal LLM**, `arXiv, 2312.06742`, [arxiv](http://arxiv.org/abs/2312.06742v1), [pdf](http://arxiv.org/pdf/2312.06742v1.pdf), cication: [**-1**](None)

	 *Junbum Cha, Wooyoung Kang, Jonghwan Mun, Byungseok Roh*

	 · ([honeybee](https://github.com/kakaobrain/honeybee) - kakaobrain) ![Star](https://img.shields.io/github/stars/kakaobrain/honeybee.svg?style=social&label=Star)
- **Interfacing Foundation Models' Embeddings**, `arXiv, 2312.07532`, [arxiv](http://arxiv.org/abs/2312.07532v1), [pdf](http://arxiv.org/pdf/2312.07532v1.pdf), cication: [**-1**](None)

	 *Xueyan Zou, Linjie Li, Jianfeng Wang, Jianwei Yang, Mingyu Ding, Zhengyuan Yang, Feng Li, Hao Zhang, Shilong Liu, Arul Aravinthan* · ([FIND](https://github.com/UX-Decoder/FIND) - UX-Decoder) ![Star](https://img.shields.io/github/stars/UX-Decoder/FIND.svg?style=social&label=Star)
- **VILA: On Pre-training for Visual Language Models**, `arXiv, 2312.07533`, [arxiv](http://arxiv.org/abs/2312.07533v1), [pdf](http://arxiv.org/pdf/2312.07533v1.pdf), cication: [**-1**](None)

	 *Ji Lin, Hongxu Yin, Wei Ping, Yao Lu, Pavlo Molchanov, Andrew Tao, Huizi Mao, Jan Kautz, Mohammad Shoeybi, Song Han*

	 · ([huggingface](https://huggingface.co/Efficient-Large-Model))
- **Vary: Scaling up the Vision Vocabulary for Large Vision-Language Models**, `arXiv, 2312.06109`, [arxiv](http://arxiv.org/abs/2312.06109v1), [pdf](http://arxiv.org/pdf/2312.06109v1.pdf), cication: [**-1**](None)

	 *Haoran Wei, Lingyu Kong, Jinyue Chen, Liang Zhao, Zheng Ge, Jinrong Yang, Jianjian Sun, Chunrui Han, Xiangyu Zhang*
- **Generating Illustrated Instructions**, `arXiv, 2312.04552`, [arxiv](http://arxiv.org/abs/2312.04552v1), [pdf](http://arxiv.org/pdf/2312.04552v1.pdf), cication: [**-1**](None)

	 *Sachit Menon, Ishan Misra, Rohit Girdhar*
- **Alpha-CLIP: A CLIP Model Focusing on Wherever You Want**, `arXiv, 2312.03818`, [arxiv](http://arxiv.org/abs/2312.03818v1), [pdf](http://arxiv.org/pdf/2312.03818v1.pdf), cication: [**-1**](None)

	 *Zeyi Sun, Ye Fang, Tong Wu, Pan Zhang, Yuhang Zang, Shu Kong, Yuanjun Xiong, Dahua Lin, Jiaqi Wang* · ([aleafy.github](https://aleafy.github.io/alpha-clip/))
- **LLaVA-Grounding: Grounded Visual Chat with Large Multimodal Models**, `arXiv, 2312.02949`, [arxiv](http://arxiv.org/abs/2312.02949v1), [pdf](http://arxiv.org/pdf/2312.02949v1.pdf), cication: [**-1**](None)

	 *Hao Zhang, Hongyang Li, Feng Li, Tianhe Ren, Xueyan Zou, Shilong Liu, Shijia Huang, Jianfeng Gao, Lei Zhang, Chunyuan Li* · ([LLaVA-Grounding](https://github.com/UX-Decoder/LLaVA-Grounding) - UX-Decoder) ![Star](https://img.shields.io/github/stars/UX-Decoder/LLaVA-Grounding.svg?style=social&label=Star)
- **Q-Instruct: Improving Low-level Visual Abilities for Multi-modality
  Foundation Models**, `arXiv, 2311.06783`, [arxiv](http://arxiv.org/abs/2311.06783v1), [pdf](http://arxiv.org/pdf/2311.06783v1.pdf), cication: [**-1**](None)

	 *Haoning Wu, Zicheng Zhang, Erli Zhang, Chaofeng Chen, Liang Liao, Annan Wang, Kaixin Xu, Chunyi Li, Jingwen Hou, Guangtao Zhai* · ([Q-Instruct](https://github.com/Q-Future/Q-Instruct) - Q-Future) ![Star](https://img.shields.io/github/stars/Q-Future/Q-Instruct.svg?style=social&label=Star)
- **Mitigating Object Hallucinations in Large Vision-Language Models through
  Visual Contrastive Decoding**, `arXiv, 2311.16922`, [arxiv](http://arxiv.org/abs/2311.16922v1), [pdf](http://arxiv.org/pdf/2311.16922v1.pdf), cication: [**-1**](None)

	 *Sicong Leng, Hang Zhang, Guanzheng Chen, Xin Li, Shijian Lu, Chunyan Miao, Lidong Bing*

	 · ([VCD](https://github.com/DAMO-NLP-SG/VCD) - DAMO-NLP-SG) ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/VCD.svg?style=social&label=Star)
- **ChartLlama: A Multimodal LLM for Chart Understanding and Generation**, `arXiv, 2311.16483`, [arxiv](http://arxiv.org/abs/2311.16483v1), [pdf](http://arxiv.org/pdf/2311.16483v1.pdf), cication: [**-1**](None)

	 *Yucheng Han, Chi Zhang, Xin Chen, Xu Yang, Zhibin Wang, Gang Yu, Bin Fu, Hanwang Zhang* · ([tingxueronghua.github](https://tingxueronghua.github.io/ChartLlama/)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-12-04-2))
- **LION : Empowering Multimodal Large Language Model with Dual-Level Visual
  Knowledge**, `arXiv, 2311.11860`, [arxiv](http://arxiv.org/abs/2311.11860v2), [pdf](http://arxiv.org/pdf/2311.11860v2.pdf), cication: [**-1**](None)

	 *Gongwei Chen, Leyang Shen, Rui Shao, Xiang Deng, Liqiang Nie* · ([JiuTian](https://github.com/rshaojimmy/JiuTian) - rshaojimmy) ![Star](https://img.shields.io/github/stars/rshaojimmy/JiuTian.svg?style=social&label=Star) · ([rshaojimmy.github](https://rshaojimmy.github.io/Projects/JiuTian-LION)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652414572&idx=5&sn=112bf60707fade37ef1b46a1239a126b))
- **GPT4Vis: What Can GPT-4 Do for Zero-shot Visual Recognition?**, `arXiv, 2311.15732`, [arxiv](http://arxiv.org/abs/2311.15732v1), [pdf](http://arxiv.org/pdf/2311.15732v1.pdf), cication: [**-1**](None)

	 *Wenhao Wu, Huanjin Yao, Mengxi Zhang, Yuxin Song, Wanli Ouyang, Jingdong Wang* · ([GPT4Vis](https://github.com/whwu95/GPT4Vis) - whwu95) ![Star](https://img.shields.io/github/stars/whwu95/GPT4Vis.svg?style=social&label=Star)
- **DocPedia: Unleashing the Power of Large Multimodal Model in the
  Frequency Domain for Versatile Document Understanding**, `arXiv, 2311.11810`, [arxiv](http://arxiv.org/abs/2311.11810v3), [pdf](http://arxiv.org/pdf/2311.11810v3.pdf), cication: [**-1**](None)

	 *Hao Feng, Qi Liu, Hao Liu, Wengang Zhou, Houqiang Li, Can Huang* · ([qbitai](https://www.qbitai.com/2023/12/103190.html))
- **Merlin:Empowering Multimodal LLMs with Foresight Minds**, `arXiv, 2312.00589`, [arxiv](http://arxiv.org/abs/2312.00589v1), [pdf](http://arxiv.org/pdf/2312.00589v1.pdf), cication: [**-1**](None)

	 *En Yu, Liang Zhao, Yana Wei, Jinrong Yang, Dongming Wu, Lingyu Kong, Haoran Wei, Tiancai Wang, Zheng Ge, Xiangyu Zhang*
- **UniIR: Training and Benchmarking Universal Multimodal Information
  Retrievers**, `arXiv, 2311.17136`, [arxiv](http://arxiv.org/abs/2311.17136v1), [pdf](http://arxiv.org/pdf/2311.17136v1.pdf), cication: [**-1**](None)

	 *Cong Wei, Yang Chen, Haonan Chen, Hexiang Hu, Ge Zhang, Jie Fu, Alan Ritter, Wenhu Chen* · ([UniIR](https://github.com/TIGER-AI-Lab/UniIR) - TIGER-AI-Lab) ![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/UniIR.svg?style=social&label=Star) · ([tiger-ai-lab.github](https://tiger-ai-lab.github.io/UniIR/))
- **ShareGPT4V: Improving Large Multi-Modal Models with Better Captions**, `arXiv, 2311.12793`, [arxiv](http://arxiv.org/abs/2311.12793v1), [pdf](http://arxiv.org/pdf/2311.12793v1.pdf), cication: [**-1**](None)

	 *Lin Chen, Jisong Li, Xiaoyi Dong, Pan Zhang, Conghui He, Jiaqi Wang, Feng Zhao, Dahua Lin* · ([sharegpt4v.github](https://sharegpt4v.github.io/)) · ([InternLM-XComposer](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) - InternLM) ![Star](https://img.shields.io/github/stars/InternLM/InternLM-XComposer.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/spaces/Lin-Chen/ShareGPT4V-7B))
- **UnifiedVisionGPT: Streamlining Vision-Oriented AI through Generalized
  Multimodal Framework**, `arXiv, 2311.10125`, [arxiv](http://arxiv.org/abs/2311.10125v1), [pdf](http://arxiv.org/pdf/2311.10125v1.pdf), cication: [**-1**](None)

	 *Chris Kelly, Luhui Hu, Cindy Yang, Yu Tian, Deshun Yang, Bang Yang, Zaoshan Huang, Zihao Li, Yuexian Zou* · ([SA-Segment-Anything](https://github.com/LHBuilder/SA-Segment-Anything) - LHBuilder) ![Star](https://img.shields.io/github/stars/LHBuilder/SA-Segment-Anything.svg?style=social&label=Star)
- **Monkey: Image Resolution and Text Label Are Important Things for Large
  Multi-modal Models**, `arXiv, 2311.06607`, [arxiv](http://arxiv.org/abs/2311.06607v1), [pdf](http://arxiv.org/pdf/2311.06607v1.pdf), cication: [**-1**](None)

	 *Zhang Li, Biao Yang, Qiang Liu, Zhiyin Ma, Shuo Zhang, Jingxu Yang, Yabo Sun, Yuliang Liu, Xiang Bai* · ([monkey](https://github.com/yuliang-liu/monkey) - yuliang-liu) ![Star](https://img.shields.io/github/stars/yuliang-liu/monkey.svg?style=social&label=Star)
- **SPHINX: The Joint Mixing of Weights, Tasks, and Visual Embeddings for
  Multi-modal Large Language Models**, `arXiv, 2311.07575`, [arxiv](http://arxiv.org/abs/2311.07575v1), [pdf](http://arxiv.org/pdf/2311.07575v1.pdf), cication: [**-1**](None)

	 *Ziyi Lin, Chris Liu, Renrui Zhang, Peng Gao, Longtian Qiu, Han Xiao, Han Qiu, Chen Lin, Wenqi Shao, Keqin Chen* · ([LLaMA2-Accessory](https://github.com/Alpha-VLLM/LLaMA2-Accessory) - Alpha-VLLM) ![Star](https://img.shields.io/github/stars/Alpha-VLLM/LLaMA2-Accessory.svg?style=social&label=Star)
- **To See is to Believe: Prompting GPT-4V for Better Visual Instruction
  Tuning**, `arXiv, 2311.07574`, [arxiv](http://arxiv.org/abs/2311.07574v1), [pdf](http://arxiv.org/pdf/2311.07574v1.pdf), cication: [**-1**](None)

	 *Junke Wang, Lingchen Meng, Zejia Weng, Bo He, Zuxuan Wu, Yu-Gang Jiang* · ([LVIS-INSTRUCT4V](https://github.com/X2FD/LVIS-INSTRUCT4V) - X2FD) ![Star](https://img.shields.io/github/stars/X2FD/LVIS-INSTRUCT4V.svg?style=social&label=Star)
- **Q-Instruct: Improving Low-level Visual Abilities for Multi-modality
  Foundation Models**, `arXiv, 2311.06783`, [arxiv](http://arxiv.org/abs/2311.06783v1), [pdf](http://arxiv.org/pdf/2311.06783v1.pdf), cication: [**-1**](None)

	 *Haoning Wu, Zicheng Zhang, Erli Zhang, Chaofeng Chen, Liang Liao, Annan Wang, Kaixin Xu, Chunyi Li, Jingwen Hou, Guangtao Zhai* · ([q-future.github](https://q-future.github.io/Q-Instruct))
- **Florence-2: Advancing a Unified Representation for a Variety of Vision
  Tasks**, `arXiv, 2311.06242`, [arxiv](http://arxiv.org/abs/2311.06242v1), [pdf](http://arxiv.org/pdf/2311.06242v1.pdf), cication: [**-1**](None)

	 *Bin Xiao, Haiping Wu, Weijian Xu, Xiyang Dai, Houdong Hu, Yumao Lu, Michael Zeng, Ce Liu, Lu Yuan*
- **SILC: Improving Vision Language Pretraining with Self-Distillation**, `arXiv, 2310.13355`, [arxiv](http://arxiv.org/abs/2310.13355v1), [pdf](http://arxiv.org/pdf/2310.13355v1.pdf), cication: [**-1**](None)

	 *Muhammad Ferjad Naeem, Yongqin Xian, Xiaohua Zhai, Lukas Hoyer, Luc Van Gool, Federico Tombari*
- **u-LLaVA: Unifying Multi-Modal Tasks via Large Language Model**, `arXiv, 2311.05348`, [arxiv](http://arxiv.org/abs/2311.05348v1), [pdf](http://arxiv.org/pdf/2311.05348v1.pdf), cication: [**-1**](None)

	 *Jinjin Xu, Liwu Xu, Yuzhe Yang, Xiang Li, Yanchun Xie, Yi-Jie Huang, Yaqian Li*
- **LLaVA-Plus: Learning to Use Tools for Creating Multimodal Agents**, `arXiv, 2311.05437`, [arxiv](http://arxiv.org/abs/2311.05437v1), [pdf](http://arxiv.org/pdf/2311.05437v1.pdf), cication: [**-1**](None)

	 *Shilong Liu, Hao Cheng, Haotian Liu, Hao Zhang, Feng Li, Tianhe Ren, Xueyan Zou, Jianwei Yang, Hang Su, Jun Zhu* · ([LLaVA-Plus-Codebase](https://github.com/LLaVA-VL/LLaVA-Plus-Codebase) - LLaVA-VL) ![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Plus-Codebase.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/datasets/LLaVA-VL/llava-plus-data))
- **NExT-Chat: An LMM for Chat, Detection and Segmentation**, `arXiv, 2311.04498`, [arxiv](http://arxiv.org/abs/2311.04498v1), [pdf](http://arxiv.org/pdf/2311.04498v1.pdf), cication: [**-1**](None)

	 *Ao Zhang, Liming Zhao, Chen-Wei Xie, Yun Zheng, Wei Ji, Tat-Seng Chua*

	 · ([NExT-Chat](https://github.com/NExT-ChatV/NExT-Chat) - NExT-ChatV) ![Star](https://img.shields.io/github/stars/NExT-ChatV/NExT-Chat.svg?style=social&label=Star)
	 · [[20d12192149d0748e2.gradio](https://20d12192149d0748e2.gradio.live/)]
- **LanguageBind: Extending Video-Language Pretraining to N-modality by
  Language-based Semantic Alignment**, `arXiv, 2310.01852`, [arxiv](http://arxiv.org/abs/2310.01852v5), [pdf](http://arxiv.org/pdf/2310.01852v5.pdf), cication: [**-1**](None)

	 *Bin Zhu, Bin Lin, Munan Ning, Yang Yan, Jiaxi Cui, HongFa Wang, Yatian Pang, Wenhao Jiang, Junwu Zhang, Zongwei Li*
	 · [LanguageBind](https://github.com/PKU-YuanGroup/LanguageBind) - PKU-YuanGroup] ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LanguageBind.svg?style=social&label=Star) · [[jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-09-3)]
- **OtterHD: A High-Resolution Multi-modality Model**, `arXiv, 2311.04219`, [arxiv](http://arxiv.org/abs/2311.04219v1), [pdf](http://arxiv.org/pdf/2311.04219v1.pdf), cication: [**-1**](None)

	 *Bo Li, Peiyuan Zhang, Jingkang Yang, Yuanhan Zhang, Fanyi Pu, Ziwei Liu*
- **mPLUG-Owl2: Revolutionizing Multi-modal Large Language Model with
  Modality Collaboration**, `arXiv, 2311.04257`, [arxiv](http://arxiv.org/abs/2311.04257v1), [pdf](http://arxiv.org/pdf/2311.04257v1.pdf), cication: [**-1**](None)

	 *Qinghao Ye, Haiyang Xu, Jiabo Ye, Ming Yan, Haowei Liu, Qi Qian, Ji Zhang, Fei Huang, Jingren Zhou*
	 · [mPLUG-Owl](https://github.com/X-PLUG/mPLUG-Owl/blob/main/mPLUG-Owl2) - X-PLUG] ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-Owl.svg?style=social&label=Star)
- **GLaMM: Pixel Grounding Large Multimodal Model**, `arXiv, 2311.03356`, [arxiv](http://arxiv.org/abs/2311.03356v1), [pdf](http://arxiv.org/pdf/2311.03356v1.pdf), cication: [**-1**](None)

	 *Hanoona Rasheed, Muhammad Maaz, Sahal Shaji, Abdelrahman Shaker, Salman Khan, Hisham Cholakkal, Rao M. Anwer, Erix Xing, Ming-Hsuan Yang, Fahad S. Khan*
- **CogVLM: Visual Expert for Pretrained Language Models**, `arXiv, 2311.03079`, [arxiv](http://arxiv.org/abs/2311.03079v1), [pdf](http://arxiv.org/pdf/2311.03079v1.pdf), cication: [**-1**](None)

	 *Weihan Wang, Qingsong Lv, Wenmeng Yu, Wenyi Hong, Ji Qi, Yan Wang, Junhui Ji, Zhuoyi Yang, Lei Zhao, Xixuan Song*
- **CoVLM: Composing Visual Entities and Relationships in Large Language
  Models Via Communicative Decoding**, `arXiv, 2311.03354`, [arxiv](http://arxiv.org/abs/2311.03354v1), [pdf](http://arxiv.org/pdf/2311.03354v1.pdf), cication: [**-1**](None)

	 *Junyan Li, Delin Chen, Yining Hong, Zhenfang Chen, Peihao Chen, Yikang Shen, Chuang Gan*
- **Grounding Visual Illusions in Language: Do Vision-Language Models
  Perceive Illusions Like Humans?**, `arXiv, 2311.00047`, [arxiv](http://arxiv.org/abs/2311.00047v1), [pdf](http://arxiv.org/pdf/2311.00047v1.pdf), cication: [**-1**](None)

	 *Yichi Zhang, Jiayi Pan, Yuchen Zhou, Rui Pan, Joyce Chai*
- **De-Diffusion Makes Text a Strong Cross-Modal Interface**, `arXiv, 2311.00618`, [arxiv](http://arxiv.org/abs/2311.00618v1), [pdf](http://arxiv.org/pdf/2311.00618v1.pdf), cication: [**-1**](None)

	 *Chen Wei, Chenxi Liu, Siyuan Qiao, Zhishuai Zhang, Alan Yuille, Jiahui Yu*
- **LLaVA-Interactive: An All-in-One Demo for Image Chat, Segmentation,
  Generation and Editing**, `arXiv, 2311.00571`, [arxiv](http://arxiv.org/abs/2311.00571v1), [pdf](http://arxiv.org/pdf/2311.00571v1.pdf), cication: [**-1**](None)

	 *Wei-Ge Chen, Irina Spiridonova, Jianwei Yang, Jianfeng Gao, Chunyuan Li*

- **Multimodal ChatGPT for Medical Applications: an Experimental Study of
  GPT-4V**, `arXiv, 2310.19061`, [arxiv](http://arxiv.org/abs/2310.19061v1), [pdf](http://arxiv.org/pdf/2310.19061v1.pdf), cication: [**-1**](None)

	 *Zhiling Yan, Kai Zhang, Rong Zhou, Lifang He, Xiang Li, Lichao Sun*
- **MM-VID: Advancing Video Understanding with GPT-4V(ision)**, `arXiv, 2310.19773`, [arxiv](http://arxiv.org/abs/2310.19773v1), [pdf](http://arxiv.org/pdf/2310.19773v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=12286689398194122588&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Kevin Lin, Faisal Ahmed, Linjie Li, Chung-Ching Lin, Ehsan Azarnasab, Zhengyuan Yang, Jianfeng Wang, Lin Liang, Zicheng Liu, Yumao Lu*
- **Woodpecker: Hallucination Correction for Multimodal Large Language
  Models**, `arXiv, 2310.16045`, [arxiv](http://arxiv.org/abs/2310.16045v1), [pdf](http://arxiv.org/pdf/2310.16045v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=522629295517903693&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shukang Yin, Chaoyou Fu, Sirui Zhao, Tong Xu, Hao Wang, Dianbo Sui, Yunhang Shen, Ke Li, Xing Sun, Enhong Chen*
	 · [woodpecker](https://github.com/bradyfu/woodpecker) - bradyfu] ![Star](https://img.shields.io/github/stars/bradyfu/woodpecker.svg?style=social&label=Star) · [qbitai](https://www.qbitai.com/2023/10/93715.html)
- **PaLI-3 Vision Language Models: Smaller, Faster, Stronger**, `arXiv, 2310.09199`, [arxiv](http://arxiv.org/abs/2310.09199v2), [pdf](http://arxiv.org/pdf/2310.09199v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=14650423215196634958&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xi Chen, Xiao Wang, Lucas Beyer, Alexander Kolesnikov, Jialin Wu, Paul Voigtlaender, Basil Mustafa, Sebastian Goodman, Ibrahim Alabdulmohsin, Piotr Padlewski*
	 · [mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652396354&idx=4&sn=deaf17ff855ad0c103d07d432b1a33d9)
- **Large Language Models are Visual Reasoning Coordinators**, `arXiv, 2310.15166`, [arxiv](http://arxiv.org/abs/2310.15166v1), [pdf](http://arxiv.org/pdf/2310.15166v1.pdf), cication: [**-1**](None)

	 *Liangyu Chen, Bo Li, Sheng Shen, Jingkang Yang, Chunyuan Li, Kurt Keutzer, Trevor Darrell, Ziwei Liu*
- **Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding in GPT-4V**, `arXiv, 2310.11441`, [arxiv](http://arxiv.org/abs/2310.11441v2), [pdf](http://arxiv.org/pdf/2310.11441v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=15918217840843846675&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jianwei Yang, Hao Zhang, Feng Li, Xueyan Zou, Chunyuan Li, Jianfeng Gao*
	 · [SoM](https://github.com/microsoft/SoM) - microsoft] ![Star](https://img.shields.io/github/stars/microsoft/SoM.svg?style=social&label=Star) · [jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-23-13)]

- **Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding in GPT-4V**, `arXiv, 2310.11441`, [arxiv](http://arxiv.org/abs/2310.11441v2), [pdf](http://arxiv.org/pdf/2310.11441v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=15918217840843846675&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jianwei Yang, Hao Zhang, Feng Li, Xueyan Zou, Chunyuan Li, Jianfeng Gao*
- **From CLIP to DINO: Visual Encoders Shout in Multi-modal Large Language
  Models**, `arXiv, 2310.08825`, [arxiv](http://arxiv.org/abs/2310.08825v2), [pdf](http://arxiv.org/pdf/2310.08825v2.pdf), cication: [**-1**](None)

	 *Dongsheng Jiang, Yuchen Liu, Songlin Liu, Xiaopeng Zhang, Jin Li, Hongkai Xiong, Qi Tian*
	 · [[comm](https://github.com/yuchenliu98/comm) - yuchenliu98] ![Star](https://img.shields.io/github/stars/yuchenliu98/comm.svg?style=social&label=Star)
- **PaLI-3 Vision Language Models: Smaller, Faster, Stronger**, `arXiv, 2310.09199`, [arxiv](http://arxiv.org/abs/2310.09199v2), [pdf](http://arxiv.org/pdf/2310.09199v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=14650423215196634958&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xi Chen, Xiao Wang, Lucas Beyer, Alexander Kolesnikov, Jialin Wu, Paul Voigtlaender, Basil Mustafa, Sebastian Goodman, Ibrahim Alabdulmohsin, Piotr Padlewski*
	 · [[jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-17-6)]
- **MiniGPT-v2: large language model as a unified interface for
  vision-language multi-task learning**, `arXiv, 2310.09478`, [arxiv](http://arxiv.org/abs/2310.09478v3), [pdf](http://arxiv.org/pdf/2310.09478v3.pdf), cication: [**-1**](None)

	 *Jun Chen, Deyao Zhu, Xiaoqian Shen, Xiang Li, Zechun Liu, Pengchuan Zhang, Raghuraman Krishnamoorthi, Vikas Chandra, Yunyang Xiong, Mohamed Elhoseiny*
- **Idea2Img: Iterative Self-Refinement with GPT-4V(ision) for Automatic
  Image Design and Generation**, `arXiv, 2310.08541`, [arxiv](http://arxiv.org/abs/2310.08541v1), [pdf](http://arxiv.org/pdf/2310.08541v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=960845636818346506&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhengyuan Yang, Jianfeng Wang, Linjie Li, Kevin Lin, Chung-Ching Lin, Zicheng Liu, Lijuan Wang*
- **Kosmos-G: Generating Images in Context with Multimodal Large Language
  Models**, `arXiv, 2310.02992`, [arxiv](http://arxiv.org/abs/2310.02992v1), [pdf](http://arxiv.org/pdf/2310.02992v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=11534635979893554099&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xichen Pan, Li Dong, Shaohan Huang, Zhiliang Peng, Wenhu Chen, Furu Wei*
- **CogVLM: Visual Expert for Pretrained Language Models**, `arXiv, 2311.03079`, [arxiv](http://arxiv.org/abs/2311.03079v1), [pdf](http://arxiv.org/pdf/2311.03079v1.pdf), cication: [**-1**](None)

	 *Weihan Wang, Qingsong Lv, Wenmeng Yu, Wenyi Hong, Ji Qi, Yan Wang, Junhui Ji, Zhuoyi Yang, Lei Zhao, Xixuan Song*
	 · [[CogVLM](https://github.com/THUDM/CogVLM) - THUDM] ![Star](https://img.shields.io/github/stars/THUDM/CogVLM.svg?style=social&label=Star) · [[qbitai](https://www.qbitai.com/2023/10/88782.html)]
- **Making LLaMA SEE and Draw with SEED Tokenizer**, `arXiv, 2310.01218`, [arxiv](http://arxiv.org/abs/2310.01218v1), [pdf](http://arxiv.org/pdf/2310.01218v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=14781111967367961466&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuying Ge, Sijie Zhao, Ziyun Zeng, Yixiao Ge, Chen Li, Xintao Wang, Ying Shan*
	 · [[SEED](https://github.com/AILab-CVC/SEED) - AILab-CVC] ![Star](https://img.shields.io/github/stars/AILab-CVC/SEED.svg?style=social&label=Star)
- **Improved Baselines with Visual Instruction Tuning**, `arXiv, 2310.03744`, [arxiv](http://arxiv.org/abs/2310.03744v1), [pdf](http://arxiv.org/pdf/2310.03744v1.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=3728182044736997490&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Haotian Liu, Chunyuan Li, Yuheng Li, Yong Jae Lee*
	 · [mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652387513&idx=1&sn=6ce09815e418582eaa1b4bf5302a6cb9&poc_token=HJs5I2Wj6qIOmBuS1VELumrD9cgAWsWNBRC0g0IE)] · [[llava-vl.github](https://llava-vl.github.io/)
	- *NOTE*
- **Investigating the Catastrophic Forgetting in Multimodal Large Language
  Models**, `arXiv, 2309.10313`, [arxiv](http://arxiv.org/abs/2309.10313v3), [pdf](http://arxiv.org/pdf/2309.10313v3.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=13813400105448769431&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuexiang Zhai, Shengbang Tong, Xiao Li, Mu Cai, Qing Qu, Yong Jae Lee, Yi Ma*
	 · [mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652385812&idx=2&sn=326d6c259ca7491af814798254b30889)
- **MiniGPT-5: Interleaved Vision-and-Language Generation via Generative
  Vokens**, `arXiv, 2310.02239`, [arxiv](http://arxiv.org/abs/2310.02239v2), [pdf](http://arxiv.org/pdf/2310.02239v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=1997615847083584812&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Kaizhi Zheng, Xuehai He, Xin Eric Wang*
	 · [[minigpt-5](https://github.com/eric-ai-lab/minigpt-5) - eric-ai-lab] ![Star](https://img.shields.io/github/stars/eric-ai-lab/minigpt-5.svg?style=social&label=Star)
- **Leveraging Unpaired Data for Vision-Language Generative Models via Cycle
  Consistency**, `arXiv, 2310.03734`, [arxiv](http://arxiv.org/abs/2310.03734v1), [pdf](http://arxiv.org/pdf/2310.03734v1.pdf), cication: [**-1**](None)

	 *Tianhong Li, Sangnie Bhardwaj, Yonglong Tian, Han Zhang, Jarred Barber, Dina Katabi, Guillaume Lajoie, Huiwen Chang, Dilip Krishnan*
- **AutoCLIP: Auto-tuning Zero-Shot Classifiers for Vision-Language Models**, `arXiv, 2309.16414`, [arxiv](http://arxiv.org/abs/2309.16414v2), [pdf](http://arxiv.org/pdf/2309.16414v2.pdf), cication: [**-1**](None)

	 *Jan Hendrik Metzen, Piyapat Saranrittichai, Chaithanya Kumar Mummadi*
- **InternLM-XComposer: A Vision-Language Large Model for Advanced
  Text-image Comprehension and Composition**, `arXiv, 2309.15112`, [arxiv](http://arxiv.org/abs/2309.15112v4), [pdf](http://arxiv.org/pdf/2309.15112v4.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=16508322221918671254&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Pan Zhang, Xiaoyi Dong, Bin Wang, Yuhang Cao, Chao Xu, Linke Ouyang, Zhiyuan Zhao, Shuangrui Ding, Songyang Zhang, Haodong Duan*
	 · [[mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652388609&idx=1&sn=82aec0ed78ea4153d389bee1644084cb)] · [[internlm-xcomposer](https://github.com/internlm/internlm-xcomposer) - internlm] ![Star](https://img.shields.io/github/stars/internlm/internlm-xcomposer.svg?style=social&label=Star)
- **AnyMAL: An Efficient and Scalable Any-Modality Augmented Language Model**, `arXiv, 2309.16058`, [arxiv](http://arxiv.org/abs/2309.16058v1), [pdf](http://arxiv.org/pdf/2309.16058v1.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=4437915502458784872&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Seungwhan Moon, Andrea Madotto, Zhaojiang Lin, Tushar Nagarajan, Matt Smith, Shashank Jain, Chun-Fu Yeh, Prakash Murugesan, Peyman Heidari, Yue Liu*
	 · [[jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-03-2)]
- **The Dawn of LMMs: Preliminary Explorations with GPT-4V(ision)**, `arXiv, 2309.17421`, [arxiv](http://arxiv.org/abs/2309.17421v2), [pdf](http://arxiv.org/pdf/2309.17421v2.pdf), cication: [**20**](https://scholar.google.com/scholar?cites=15832597276306837362&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhengyuan Yang, Linjie Li, Kevin Lin, Jianfeng Wang, Chung-Ching Lin, Zicheng Liu, Lijuan Wang*
	 · [[qbitai](https://www.qbitai.com/2023/10/87661.html)]
- **DeepSpeed-VisualChat: Multi-Round Multi-Image Interleave Chat via
  Multi-Modal Causal Attention**, `arXiv, 2309.14327`, [arxiv](http://arxiv.org/abs/2309.14327v2), [pdf](http://arxiv.org/pdf/2309.14327v2.pdf), cication: [**-1**](None)

	 *Zhewei Yao, Xiaoxia Wu, Conglong Li, Minjia Zhang, Heyang Qin, Olatunji Ruwase, Ammar Ahmad Awan, Samyam Rajbhandari, Yuxiong He*
- **Kosmos-2.5: A Multimodal Literate Model**, `arXiv, 2309.11419`, [arxiv](http://arxiv.org/abs/2309.11419v1), [pdf](http://arxiv.org/pdf/2309.11419v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=4181892944615954441&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tengchao Lv, Yupan Huang, Jingye Chen, Lei Cui, Shuming Ma, Yaoyao Chang, Shaohan Huang, Wenhui Wang, Li Dong, Weiyao Luo*
- **DreamLLM: Synergistic Multimodal Comprehension and Creation**, `arXiv, 2309.11499`, [arxiv](http://arxiv.org/abs/2309.11499v1), [pdf](http://arxiv.org/pdf/2309.11499v1.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=9906106921805979798&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Runpei Dong, Chunrui Han, Yuang Peng, Zekun Qi, Zheng Ge, Jinrong Yang, Liang Zhao, Jianjian Sun, Hongyu Zhou, Haoran Wei*
- **Multimodal Foundation Models: From Specialists to General-Purpose
  Assistants**, `arXiv, 2309.10020`, [arxiv](http://arxiv.org/abs/2309.10020v1), [pdf](http://arxiv.org/pdf/2309.10020v1.pdf), cication: [**14**](https://scholar.google.com/scholar?cites=6422184334822064295&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chunyuan Li, Zhe Gan, Zhengyuan Yang, Jianwei Yang, Linjie Li, Lijuan Wang, Jianfeng Gao*
- **TextBind: Multi-turn Interleaved Multimodal Instruction-following in the
  Wild**, `arXiv, 2309.08637`, [arxiv](http://arxiv.org/abs/2309.08637v3), [pdf](http://arxiv.org/pdf/2309.08637v3.pdf), cication: [**-1**](None)

	 *Huayang Li, Siheng Li, Deng Cai, Longyue Wang, Lemao Liu, Taro Watanabe, Yujiu Yang, Shuming Shi*
- **An Empirical Study of Scaling Instruct-Tuned Large Multimodal Models**, `arXiv, 2309.09958`, [arxiv](http://arxiv.org/abs/2309.09958v1), [pdf](http://arxiv.org/pdf/2309.09958v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=7981959352926225566&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yadong Lu, Chunyuan Li, Haotian Liu, Jianwei Yang, Jianfeng Gao, Yelong Shen*
- **NExT-GPT: Any-to-Any Multimodal LLM**, `arXiv, 2309.05519`, [arxiv](http://arxiv.org/abs/2309.05519v2), [pdf](http://arxiv.org/pdf/2309.05519v2.pdf), cication: [**12**](https://scholar.google.com/scholar?cites=10489512657753192238&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shengqiong Wu, Hao Fei, Leigang Qu, Wei Ji, Tat-Seng Chua*
- **DreamLLM: Synergistic Multimodal Comprehension and Creation**, `arXiv, 2309.11499`, [arxiv](http://arxiv.org/abs/2309.11499v1), [pdf](http://arxiv.org/pdf/2309.11499v1.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=9906106921805979798&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Runpei Dong, Chunrui Han, Yuang Peng, Zekun Qi, Zheng Ge, Jinrong Yang, Liang Zhao, Jianjian Sun, Hongyu Zhou, Haoran Wei*

	 · [[DreamLLM](https://github.com/RunpeiDong/DreamLLM) - RunpeiDong] ![Star](https://img.shields.io/github/stars/RunpeiDong/DreamLLM.svg?style=social&label=Star)
- **ImageBind-LLM: Multi-modality Instruction Tuning**, `arXiv, 2309.03905`, [arxiv](http://arxiv.org/abs/2309.03905v2), [pdf](http://arxiv.org/pdf/2309.03905v2.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=7633131358609482991&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jiaming Han, Renrui Zhang, Wenqi Shao, Peng Gao, Peng Xu, Han Xiao, Kaipeng Zhang, Chris Liu, Song Wen, Ziyu Guo*
- **Scaling Autoregressive Multi-Modal Models: Pretraining and Instruction
  Tuning**, `arXiv, 2309.02591`, [arxiv](http://arxiv.org/abs/2309.02591v1), [pdf](http://arxiv.org/pdf/2309.02591v1.pdf), cication: [**12**](https://scholar.google.com/scholar?cites=64722431145661227&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lili Yu, Bowen Shi, Ramakanth Pasunuru, Benjamin Muller, Olga Golovneva, Tianlu Wang, Arun Babu, Binh Tang, Brian Karrer, Shelly Sheynin*
- **Large Content And Behavior Models To Understand, Simulate, And Optimize
  Content And Behavior**, `arXiv, 2309.00359`, [arxiv](http://arxiv.org/abs/2309.00359v3), [pdf](http://arxiv.org/pdf/2309.00359v3.pdf), cication: [**-1**](None)

	 *Ashmit Khandelwal, Aditya Agrawal, Aanisha Bhattacharyya, Yaman K Singla, Somesh Singh, Uttaran Bhattacharya, Ishita Dasgupta, Stefano Petrangeli, Rajiv Ratn Shah, Changyou Chen*
- **Point-Bind & Point-LLM: Aligning Point Cloud with Multi-modality for 3D
  Understanding, Generation, and Instruction Following**, `arXiv, 2309.00615`, [arxiv](http://arxiv.org/abs/2309.00615v1), [pdf](http://arxiv.org/pdf/2309.00615v1.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=4061841926044239004&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ziyu Guo, Renrui Zhang, Xiangyang Zhu, Yiwen Tang, Xianzheng Ma, Jiaming Han, Kexin Chen, Peng Gao, Xianzhi Li, Hongsheng Li*

- **PointLLM: Empowering Large Language Models to Understand Point Clouds**, `arXiv, 2308.16911`, [arxiv](http://arxiv.org/abs/2308.16911v1), [pdf](http://arxiv.org/pdf/2308.16911v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=5467745697550987528&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Runsen Xu, Xiaolong Wang, Tai Wang, Yilun Chen, Jiangmiao Pang, Dahua Lin*
	 · [[pointllm](https://github.com/openrobotlab/pointllm) - openrobotlab] ![Star](https://img.shields.io/github/stars/openrobotlab/pointllm.svg?style=social&label=Star)
- **InstructionGPT-4: A 200-Instruction Paradigm for Fine-Tuning MiniGPT-4**, `arXiv, 2308.12067`, [arxiv](http://arxiv.org/abs/2308.12067v2), [pdf](http://arxiv.org/pdf/2308.12067v2.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=9653142586779586757&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lai Wei, Zihao Jiang, Weiran Huang, Lichao Sun*
	 · [[minigpt-v2.github](https://minigpt-v2.github.io/)] · [[jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-29-4)]
- **BLIVA: A Simple Multimodal LLM for Better Handling of Text-Rich Visual
  Questions**, `arXiv, 2308.09936`, [arxiv](http://arxiv.org/abs/2308.09936v1), [pdf](http://arxiv.org/pdf/2308.09936v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=10363074134135382704&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wenbo Hu, Yifan Xu, Yi Li, Weiyue Li, Zeyuan Chen, Zhuowen Tu*
	 · [[bliva](https://github.com/mlpc-ucsd/bliva) - mlpc-ucsd] ![Star](https://img.shields.io/github/stars/mlpc-ucsd/bliva.svg?style=social&label=Star)
- **Qwen-VL: A Versatile Vision-Language Model for Understanding,
  Localization, Text Reading, and Beyond**, `arXiv, 2308.12966`, [arxiv](http://arxiv.org/abs/2308.12966v3), [pdf](http://arxiv.org/pdf/2308.12966v3.pdf), cication: [**17**](https://scholar.google.com/scholar?cites=8374957261235476914&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jinze Bai, Shuai Bai, Shusheng Yang, Shijie Wang, Sinan Tan, Peng Wang, Junyang Lin, Chang Zhou, Jingren Zhou*
	 · [[Qwen-VL](https://github.com/QwenLM/Qwen-VL) - QwenLM] ![Star](https://img.shields.io/github/stars/QwenLM/Qwen-VL.svg?style=social&label=Star) · [jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-25)
- **Generating Images with Multimodal Language Models**, `arXiv, 2305.17216`, [arxiv](http://arxiv.org/abs/2305.17216v3), [pdf](http://arxiv.org/pdf/2305.17216v3.pdf), cication: [**27**](https://scholar.google.com/scholar?cites=18125197563162628220&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jing Yu Koh, Daniel Fried, Ruslan Salakhutdinov*
	 · [[mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652369597&idx=4&sn=cc541b279b064a97fcdfb4dfa24e354c)]
- **Link-Context Learning for Multimodal LLMs**, `arXiv, 2308.07891`, [arxiv](http://arxiv.org/abs/2308.07891v1), [pdf](http://arxiv.org/pdf/2308.07891v1.pdf), cication: [**-1**](None)

	 *Yan Tai, Weichen Fan, Zhao Zhang, Feng Zhu, Rui Zhao, Ziwei Liu*
	 · [[Link-Context-Learning](https://github.com/isekai-portal/Link-Context-Learning) - isekai-portal] ![Star](https://img.shields.io/github/stars/isekai-portal/Link-Context-Learning.svg?style=social&label=Star)
- **Visual Instruction Tuning**, `arXiv, 2304.08485`, [arxiv](http://arxiv.org/abs/2304.08485v1), [pdf](http://arxiv.org/pdf/2304.08485v1.pdf), cication: [**301**](https://scholar.google.com/scholar?cites=9083483030705185424&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee*
	 · [[llava-vl.github](https://llava-vl.github.io/)]
- **Fine-tuning Multimodal LLMs to Follow Zero-shot Demonstrative
  Instructions**, `arXiv, 2308.04152`, [arxiv](http://arxiv.org/abs/2308.04152v3), [pdf](http://arxiv.org/pdf/2308.04152v3.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=11040006820313015524&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Juncheng Li, Kaihang Pan, Zhiqi Ge, Minghe Gao, Hanwang Zhang, Wei Ji, Wenqiao Zhang, Tat-Seng Chua, Siliang Tang, Yueting Zhuang*
	 · [[cheetah](https://github.com/dcdmllm/cheetah) - dcdmllm] ![Star](https://img.shields.io/github/stars/dcdmllm/cheetah.svg?style=social&label=Star)
- **OpenFlamingo: An Open-Source Framework for Training Large Autoregressive
  Vision-Language Models**, `arXiv, 2308.01390`, [arxiv](http://arxiv.org/abs/2308.01390v2), [pdf](http://arxiv.org/pdf/2308.01390v2.pdf), cication: [**31**](https://scholar.google.com/scholar?cites=17957043568315120670&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Anas Awadalla, Irena Gao, Josh Gardner, Jack Hessel, Yusuf Hanafy, Wanrong Zhu, Kalyani Marathe, Yonatan Bitton, Samir Gadre, Shiori Sagawa*
	 · [[open_flamingo](https://github.com/mlfoundations/open_flamingo) - mlfoundations] ![Star](https://img.shields.io/github/stars/mlfoundations/open_flamingo.svg?style=social&label=Star)
- **UniVTG: Towards Unified Video-Language Temporal Grounding**, `ICCV, 2023`, [arxiv](http://arxiv.org/abs/2307.16715v2), [pdf](http://arxiv.org/pdf/2307.16715v2.pdf), cication: [**-1**](None)

	 *Kevin Qinghong Lin, Pengchuan Zhang, Joya Chen, Shraman Pramanick, Difei Gao, Alex Jinpeng Wang, Rui Yan, Mike Zheng Shou*
	 · [[UniVTG](https://github.com/showlab/UniVTG) - showlab] ![Star](https://img.shields.io/github/stars/showlab/UniVTG.svg?style=social&label=Star)
- **Backdooring Instruction-Tuned Large Language Models with Virtual Prompt
  Injection**, `arXiv, 2307.16888`, [arxiv](http://arxiv.org/abs/2307.16888v2), [pdf](http://arxiv.org/pdf/2307.16888v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=9126439675689346864&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jun Yan, Vikas Yadav, Shiyang Li, Lichang Chen, Zheng Tang, Hai Wang, Vijay Srinivasan, Xiang Ren, Hongxia Jin*
- **Unified Model for Image, Video, Audio and Language Tasks**, `arXiv, 2307.16184`, [arxiv](http://arxiv.org/abs/2307.16184v1), [pdf](http://arxiv.org/pdf/2307.16184v1.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=859458810768231220&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Mustafa Shukor, Corentin Dancette, Alexandre Rame, Matthieu Cord*
- **3D-LLM: Injecting the 3D World into Large Language Models**, `arXiv, 2307.12981`, [arxiv](http://arxiv.org/abs/2307.12981v1), [pdf](http://arxiv.org/pdf/2307.12981v1.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=9113313701189648384&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yining Hong, Haoyu Zhen, Peihao Chen, Shuhong Zheng, Yilun Du, Zhenfang Chen, Chuang Gan*
- **Meta-Transformer: A Unified Framework for Multimodal Learning**, `arXiv, 2307.10802`, [arxiv](http://arxiv.org/abs/2307.10802v1), [pdf](http://arxiv.org/pdf/2307.10802v1.pdf), cication: [**23**](https://scholar.google.com/scholar?cites=11077145075852511910&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yiyuan Zhang, Kaixiong Gong, Kaipeng Zhang, Hongsheng Li, Yu Qiao, Wanli Ouyang, Xiangyu Yue*
- **Augmenting CLIP with Improved Visio-Linguistic Reasoning**, `arXiv, 2307.09233`, [arxiv](http://arxiv.org/abs/2307.09233v2), [pdf](http://arxiv.org/pdf/2307.09233v2.pdf), cication: [**-1**](None)

	 *Samyadeep Basu, Maziar Sanjabi, Daniela Massiceti, Shell Xu Hu, Soheil Feizi*
- **Planting a SEED of Vision in Large Language Model**, `arXiv, 2307.08041`, [arxiv](http://arxiv.org/abs/2307.08041v2), [pdf](http://arxiv.org/pdf/2307.08041v2.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=13637721602251375035&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuying Ge, Yixiao Ge, Ziyun Zeng, Xintao Wang, Ying Shan*
- **BuboGPT: Enabling Visual Grounding in Multi-Modal LLMs**, `arXiv, 2307.08581`, [arxiv](http://arxiv.org/abs/2307.08581v1), [pdf](http://arxiv.org/pdf/2307.08581v1.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=15466553126669319734&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yang Zhao, Zhijie Lin, Daquan Zhou, Zilong Huang, Jiashi Feng, Bingyi Kang*
	 · [[bubogpt](https://github.com/magic-research/bubogpt) - magic-research] ![Star](https://img.shields.io/github/stars/magic-research/bubogpt.svg?style=social&label=Star)
- **Vision-Language Models for Vision Tasks: A Survey**, `arXiv, 2304.00685`, [arxiv](http://arxiv.org/abs/2304.00685v1), [pdf](http://arxiv.org/pdf/2304.00685v1.pdf), cication: [**27**](https://scholar.google.com/scholar?cites=15920918924905530692&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jingyi Zhang, Jiaxing Huang, Sheng Jin, Shijian Lu*
	 · [[vlm_survey](https://github.com/jingyi0000/vlm_survey) - jingyi0000] ![Star](https://img.shields.io/github/stars/jingyi0000/vlm_survey.svg?style=social&label=Star)
- **What Matters in Training a GPT4-Style Language Model with Multimodal
  Inputs?**, `arXiv, 2307.02469`, [arxiv](http://arxiv.org/abs/2307.02469v2), [pdf](http://arxiv.org/pdf/2307.02469v2.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=4132439189633573873&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yan Zeng, Hanbo Zhang, Jiani Zheng, Jiangnan Xia, Guoqiang Wei, Yang Wei, Yuchen Zhang, Tao Kong*
	 · [[jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-15-3)] · [[lynx-llm](https://github.com/bytedance/lynx-llm) - bytedance] ![Star](https://img.shields.io/github/stars/bytedance/lynx-llm.svg?style=social&label=Star)
- **Generative Pretraining in Multimodality**, `arXiv, 2307.05222`, [arxiv](http://arxiv.org/abs/2307.05222v1), [pdf](http://arxiv.org/pdf/2307.05222v1.pdf), cication: [**19**](https://scholar.google.com/scholar?cites=15140367052685955488&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Quan Sun, Qiying Yu, Yufeng Cui, Fan Zhang, Xiaosong Zhang, Yueze Wang, Hongcheng Gao, Jingjing Liu, Tiejun Huang, Xinlong Wang*
- **EgoVLPv2: Egocentric Video-Language Pre-training with Fusion in the
  Backbone**, `ICCV, 2023`, [arxiv](http://arxiv.org/abs/2307.05463v2), [pdf](http://arxiv.org/pdf/2307.05463v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=2418402012858604493&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shraman Pramanick, Yale Song, Sayan Nag, Kevin Qinghong Lin, Hardik Shah, Mike Zheng Shou, Rama Chellappa, Pengchuan Zhang*
- **SVIT: Scaling up Visual Instruction Tuning**, `arXiv, 2307.04087`, [arxiv](http://arxiv.org/abs/2307.04087v2), [pdf](http://arxiv.org/pdf/2307.04087v2.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=3544235904917954440&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Bo Zhao, Boya Wu, Tiejun Huang*
- **GPT4RoI: Instruction Tuning Large Language Model on Region-of-Interest**, `arXiv, 2307.03601`, [arxiv](http://arxiv.org/abs/2307.03601v2), [pdf](http://arxiv.org/pdf/2307.03601v2.pdf), cication: [**15**](https://scholar.google.com/scholar?cites=7500549576538416374&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shilong Zhang, Peize Sun, Shoufa Chen, Min Xiao, Wenqi Shao, Wenwei Zhang, Yu Liu, Kai Chen, Ping Luo*
	 · [[GPT4RoI](https://github.com/jshilong/GPT4RoI) - jshilong] ![Star](https://img.shields.io/github/stars/jshilong/GPT4RoI.svg?style=social&label=Star)
- **mPLUG-DocOwl: Modularized Multimodal Large Language Model for Document
  Understanding**, `arXiv, 2307.02499`, [arxiv](http://arxiv.org/abs/2307.02499v1), [pdf](http://arxiv.org/pdf/2307.02499v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=6566181958221003013&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jiabo Ye, Anwen Hu, Haiyang Xu, Qinghao Ye, Ming Yan, Yuhao Dan, Chenlin Zhao, Guohai Xu, Chenliang Li, Junfeng Tian*
- **What Matters in Training a GPT4-Style Language Model with Multimodal
  Inputs?**, `arXiv, 2307.02469`, [arxiv](http://arxiv.org/abs/2307.02469v2), [pdf](http://arxiv.org/pdf/2307.02469v2.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=4132439189633573873&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yan Zeng, Hanbo Zhang, Jiani Zheng, Jiangnan Xia, Guoqiang Wei, Yang Wei, Yuchen Zhang, Tao Kong*
- **LLaVAR: Enhanced Visual Instruction Tuning for Text-Rich Image
  Understanding**, `arXiv, 2306.17107`, [arxiv](http://arxiv.org/abs/2306.17107v1), [pdf](http://arxiv.org/pdf/2306.17107v1.pdf), cication: [**12**](https://scholar.google.com/scholar?cites=10736203767548895528&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yanzhe Zhang, Ruiyi Zhang, Jiuxiang Gu, Yufan Zhou, Nedim Lipka, Diyi Yang, Tong Sun*
- **Shikra: Unleashing Multimodal LLM's Referential Dialogue Magic**, `arXiv, 2306.15195`, [arxiv](http://arxiv.org/abs/2306.15195v2), [pdf](http://arxiv.org/pdf/2306.15195v2.pdf), cication: [**26**](https://scholar.google.com/scholar?cites=17373863579289672244&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Keqin Chen, Zhao Zhang, Weili Zeng, Richong Zhang, Feng Zhu, Rui Zhao*
	 · [[shikra](https://github.com/shikras/shikra) - shikras] ![Star](https://img.shields.io/github/stars/shikras/shikra.svg?style=social&label=Star)
- **Towards Language Models That Can See: Computer Vision Through the LENS
  of Natural Language**, `arXiv, 2306.16410`, [arxiv](http://arxiv.org/abs/2306.16410v1), [pdf](http://arxiv.org/pdf/2306.16410v1.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=8194990482450812506&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *William Berrios, Gautam Mittal, Tristan Thrush, Douwe Kiela, Amanpreet Singh*
	- https://github.com/ContextualAI/lens  
- **PandaGPT: One Model To Instruction-Follow Them All**, `arXiv, 2305.16355`, [arxiv](http://arxiv.org/abs/2305.16355v1), [pdf](http://arxiv.org/pdf/2305.16355v1.pdf), cication: [**42**](https://scholar.google.com/scholar?cites=3148713146598870294&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yixuan Su, Tian Lan, Huayang Li, Jialu Xu, Yan Wang, Deng Cai*
	 · [[panda-gpt.github](https://panda-gpt.github.io/)] · [[mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652343523&idx=3&sn=7ca64f18eacae061b815c9d53003803e)]
- **Macaw-LLM: Multi-Modal Language Modeling with Image, Audio, Video, and
  Text Integration**, `arXiv, 2306.09093`, [arxiv](http://arxiv.org/abs/2306.09093v1), [pdf](http://arxiv.org/pdf/2306.09093v1.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=15696066130009507422&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chenyang Lyu, Minghao Wu, Longyue Wang, Xinting Huang, Bingshuai Liu, Zefeng Du, Shuming Shi, Zhaopeng Tu*
- **Otter: A Multi-Modal Model with In-Context Instruction Tuning**, `arXiv, 2305.03726`, [arxiv](http://arxiv.org/abs/2305.03726v1), [pdf](http://arxiv.org/pdf/2305.03726v1.pdf), cication: [**69**](https://scholar.google.com/scholar?cites=14453137911172739574&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Bo Li, Yuanhan Zhang, Liangyu Chen, Jinghao Wang, Jingkang Yang, Ziwei Liu*
	 · [[Otter](https://github.com/Luodian/Otter) - Luodian] ![Star](https://img.shields.io/github/stars/Luodian/Otter.svg?style=social&label=Star) · [[mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652339033&idx=1&sn=77048c8ae9d2c401ae7da24477665bfd)]
- **Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and
  Language Models**, `arXiv, 2306.05424`, [arxiv](http://arxiv.org/abs/2306.05424v1), [pdf](http://arxiv.org/pdf/2306.05424v1.pdf), cication: [**30**](https://scholar.google.com/scholar?cites=13699030569069918768&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Muhammad Maaz, Hanoona Rasheed, Salman Khan, Fahad Shahbaz Khan*
	 · [[video-chatgpt](https://github.com/mbzuai-oryx/video-chatgpt) - mbzuai-oryx] ![Star](https://img.shields.io/github/stars/mbzuai-oryx/video-chatgpt.svg?style=social&label=Star)
- **Revisiting the Role of Language Priors in Vision-Language Models**, `arXiv, 2306.01879`, [arxiv](http://arxiv.org/abs/2306.01879v2), [pdf](http://arxiv.org/pdf/2306.01879v2.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=13754762341203173877&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhiqiu Lin, Xinyue Chen, Deepak Pathak, Pengchuan Zhang, Deva Ramanan*
- **Language Models are General-Purpose Interfaces**, `arXiv, 2206.06336`, [arxiv](http://arxiv.org/abs/2206.06336v1), [pdf](http://arxiv.org/pdf/2206.06336v1.pdf), cication: [**51**](https://scholar.google.com/scholar?cites=592495788723068636&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yaru Hao, Haoyu Song, Li Dong, Shaohan Huang, Zewen Chi, Wenhui Wang, Shuming Ma, Furu Wei*
- **Flamingo: a Visual Language Model for Few-Shot Learning**, `NeurIPS, 2022`, [arxiv](http://arxiv.org/abs/2204.14198v2), [pdf](http://arxiv.org/pdf/2204.14198v2.pdf), cication: [**989**](https://scholar.google.com/scholar?cites=2325917221075842848&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jean-Baptiste Alayrac, Jeff Donahue, Pauline Luc, Antoine Miech, Iain Barr, Yana Hasson, Karel Lenc, Arthur Mensch, Katie Millican, Malcolm Reynolds*
- **Revisiting the Role of Language Priors in Vision-Language Models**, `arXiv, 2306.01879`, [arxiv](http://arxiv.org/abs/2306.01879v2), [pdf](http://arxiv.org/pdf/2306.01879v2.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=13754762341203173877&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhiqiu Lin, Xinyue Chen, Deepak Pathak, Pengchuan Zhang, Deva Ramanan*
- **Kosmos-2: Grounding Multimodal Large Language Models to the World**, `arXiv, 2306.14824`, [arxiv](http://arxiv.org/abs/2306.14824v3), [pdf](http://arxiv.org/pdf/2306.14824v3.pdf), cication: [**52**](https://scholar.google.com/scholar?cites=15444663084916607877&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhiliang Peng, Wenhui Wang, Li Dong, Yaru Hao, Shaohan Huang, Shuming Ma, Furu Wei*
	 · [[huggingface](https://huggingface.co/spaces/ydshieh/Kosmos-2)] · [[unilm](https://github.com/microsoft/unilm/tree/master/kosmos-2) - microsoft] ![Star](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star) · [[thegenerality](https://thegenerality.com/agi/)]
- **Macaw-LLM: Multi-Modal Language Modeling with Image, Audio, Video, and
  Text Integration**, `arXiv, 2306.09093`, [arxiv](http://arxiv.org/abs/2306.09093v1), [pdf](http://arxiv.org/pdf/2306.09093v1.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=15696066130009507422&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chenyang Lyu, Minghao Wu, Longyue Wang, Xinting Huang, Bingshuai Liu, Zefeng Du, Shuming Shi, Zhaopeng Tu*
	 · [[macaw-llm](https://github.com/lyuchenyang/macaw-llm#macaw-llm-multi-modal-language-modeling-with-image-audio-video-and-text-integration) - lyuchenyang] ![Star](https://img.shields.io/github/stars/lyuchenyang/macaw-llm#macaw-llm-multi-modal-language-modeling-with-image-audio-video-and-text-integration.svg?style=social&label=Star)
- **Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video
  Understanding**, `arXiv, 2306.02858`, [arxiv](http://arxiv.org/abs/2306.02858v4), [pdf](http://arxiv.org/pdf/2306.02858v4.pdf), cication: [**39**](https://scholar.google.com/scholar?cites=243345481669305195&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hang Zhang, Xin Li, Lidong Bing*
	 · [[Video-LLaMA](https://github.com/DAMO-NLP-SG/Video-LLaMA) - DAMO-NLP-SG] ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/Video-LLaMA.svg?style=social&label=Star)
- **ImageBind: One Embedding Space To Bind Them All**, `CVPR, 2023`, [arxiv](http://arxiv.org/abs/2305.05665v2), [pdf](http://arxiv.org/pdf/2305.05665v2.pdf), cication: [**36**](https://scholar.google.com/scholar?cites=1657173986906232916&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Rohit Girdhar, Alaaeldin El-Nouby, Zhuang Liu, Mannat Singh, Kalyan Vasudev Alwala, Armand Joulin, Ishan Misra*
	 · [[facebookresearch.github](https://facebookresearch.github.io/ImageBind/paper)] · [[ImageBind](https://github.com/facebookresearch/ImageBind) - facebookresearch] ![Star](https://img.shields.io/github/stars/facebookresearch/ImageBind.svg?style=social&label=Star)
- **InstructBLIP: Towards General-purpose Vision-Language Models with
  Instruction Tuning**, `arXiv, 2305.06500`, [arxiv](http://arxiv.org/abs/2305.06500v2), [pdf](http://arxiv.org/pdf/2305.06500v2.pdf), cication: [**301**](https://scholar.google.com/scholar?cites=9083483030705185424&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wenliang Dai, Junnan Li, Dongxu Li, Anthony Meng Huat Tiong, Junqi Zhao, Weisheng Wang, Boyang Li, Pascale Fung, Steven Hoi*
	 · [[LAVIS](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) - salesforce] ![Star](https://img.shields.io/github/stars/salesforce/LAVIS.svg?style=social&label=Star) · [[LAVIS](https://github.com/salesforce/LAVIS/tree/main) - salesforce] ![Star](https://img.shields.io/github/stars/salesforce/LAVIS.svg?style=social&label=Star)
- **Language Is Not All You Need: Aligning Perception with Language Models**, `arXiv, 2302.14045`, [arxiv](http://arxiv.org/abs/2302.14045v2), [pdf](http://arxiv.org/pdf/2302.14045v2.pdf), cication: [**133**](https://scholar.google.com/scholar?cites=17880336204125555846&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shaohan Huang, Li Dong, Wenhui Wang, Yaru Hao, Saksham Singhal, Shuming Ma, Tengchao Lv, Lei Cui, Owais Khan Mohammed, Barun Patra*

## Audio

- **ChatMusician: Understanding and Generating Music Intrinsically with LLM**, `arXiv, 2402.16153`, [arxiv](http://arxiv.org/abs/2402.16153v1), [pdf](http://arxiv.org/pdf/2402.16153v1.pdf), cication: [**-1**](None)

	 *Ruibin Yuan, Hanfeng Lin, Yi Wang, Zeyue Tian, Shangda Wu, Tianhao Shen, Ge Zhang, Yuhang Wu, Cong Liu, Ziya Zhou*
- **SpiRit-LM: Interleaved Spoken and Written Language Model**, `arXiv, 2402.05755`, [arxiv](http://arxiv.org/abs/2402.05755v1), [pdf](http://arxiv.org/pdf/2402.05755v1.pdf), cication: [**-1**](None)

	 *Tu Anh Nguyen, Benjamin Muller, Bokai Yu, Marta R. Costa-jussa, Maha Elbayad, Sravya Popuri, Paul-Ambroise Duquenne, Robin Algayres, Ruslan Mavlyutov, Itai Gat*
- **Audio Flamingo: A Novel Audio Language Model with Few-Shot Learning and
  Dialogue Abilities**, `arXiv, 2402.01831`, [arxiv](http://arxiv.org/abs/2402.01831v1), [pdf](http://arxiv.org/pdf/2402.01831v1.pdf), cication: [**-1**](None)

	 *Zhifeng Kong, Arushi Goel, Rohan Badlani, Wei Ping, Rafael Valle, Bryan Catanzaro*
- **SpeechGPT-Gen: Scaling Chain-of-Information Speech Generation**, `arXiv, 2401.13527`, [arxiv](http://arxiv.org/abs/2401.13527v2), [pdf](http://arxiv.org/pdf/2401.13527v2.pdf), cication: [**-1**](None)

	 *Dong Zhang, Xin Zhang, Jun Zhan, Shimin Li, Yaqian Zhou, Xipeng Qiu* · ([speechgpt](https://github.com/0nutation/speechgpt) - 0nutation) ![Star](https://img.shields.io/github/stars/0nutation/speechgpt.svg?style=social&label=Star)
- **On the Audio Hallucinations in Large Audio-Video Language Models**, `arXiv, 2401.09774`, [arxiv](http://arxiv.org/abs/2401.09774v1), [pdf](http://arxiv.org/pdf/2401.09774v1.pdf), cication: [**-1**](None)

	 *Taichi Nishimura, Shota Nakada, Masayoshi Kondo*
- **E-chat: Emotion-sensitive Spoken Dialogue System with Large Language
  Models**, `arXiv, 2401.00475`, [arxiv](http://arxiv.org/abs/2401.00475v2), [pdf](http://arxiv.org/pdf/2401.00475v2.pdf), cication: [**-1**](None)

	 *Hongfei Xue, Yuhao Liang, Bingshen Mu, Shiliang Zhang, Mengzhe Chen, Qian Chen, Lei Xie*
- **Boosting Large Language Model for Speech Synthesis: An Empirical Study**, `arXiv, 2401.00246`, [arxiv](http://arxiv.org/abs/2401.00246v1), [pdf](http://arxiv.org/pdf/2401.00246v1.pdf), cication: [**-1**](None)

	 *Hongkun Hao, Long Zhou, Shujie Liu, Jinyu Li, Shujie Hu, Rui Wang, Furu Wei*
- **Multimodal Data and Resource Efficient Device-Directed Speech Detection
  with Large Foundation Models**, `arXiv, 2312.03632`, [arxiv](http://arxiv.org/abs/2312.03632v1), [pdf](http://arxiv.org/pdf/2312.03632v1.pdf), cication: [**-1**](None)

	 *Dominik Wagner, Alexander Churchill, Siddharth Sigtia, Panayiotis Georgiou, Matt Mirsamadi, Aarshee Mishra, Erik Marchi*
- **WhisBERT: Multimodal Text-Audio Language Modeling on 100M Words**, `arXiv, 2312.02931`, [arxiv](http://arxiv.org/abs/2312.02931v2), [pdf](http://arxiv.org/pdf/2312.02931v2.pdf), cication: [**-1**](None)

	 *Lukas Wolf, Greta Tuckute, Klemen Kotar, Eghbal Hosseini, Tamar Regev, Ethan Wilcox, Alex Warstadt*
- **Acoustic Prompt Tuning: Empowering Large Language Models with Audition
  Capabilities**, `arXiv, 2312.00249`, [arxiv](http://arxiv.org/abs/2312.00249v1), [pdf](http://arxiv.org/pdf/2312.00249v1.pdf), cication: [**-1**](None)

	 *Jinhua Liang, Xubo Liu, Wenwu Wang, Mark D. Plumbley, Huy Phan, Emmanouil Benetos*

	 · ([APT](https://github.com/JinhuaLiang/APT) - JinhuaLiang) ![Star](https://img.shields.io/github/stars/JinhuaLiang/APT.svg?style=social&label=Star)
- **Qwen-Audio: Advancing Universal Audio Understanding via Unified
  Large-Scale Audio-Language Models**, `arXiv, 2311.07919`, [arxiv](http://arxiv.org/abs/2311.07919v1), [pdf](http://arxiv.org/pdf/2311.07919v1.pdf), cication: [**-1**](None)

	 *Yunfei Chu, Jin Xu, Xiaohuan Zhou, Qian Yang, Shiliang Zhang, Zhijie Yan, Chang Zhou, Jingren Zhou*

	 · ([Qwen-Audio](https://github.com/QwenLM/Qwen-Audio) - QwenLM) ![Star](https://img.shields.io/github/stars/QwenLM/Qwen-Audio.svg?style=social&label=Star)
- **Towards General-Purpose Speech Abilities for Large Language Models Using
  Unpaired Data**, `arXiv, 2311.06753`, [arxiv](http://arxiv.org/abs/2311.06753v1), [pdf](http://arxiv.org/pdf/2311.06753v1.pdf), cication: [**-1**](None)

	 *Yassir Fathullah, Chunyang Wu, Egor Lakomkin, Junteng Jia, Yuan Shangguan, Jay Mahadeokar, Ozlem Kalinli, Christian Fuegen, Mike Seltzer*
- **Attention or Convolution: Transformer Encoders in Audio Language Models
  for Inference Efficiency**, `arXiv, 2311.02772`, [arxiv](http://arxiv.org/abs/2311.02772v1), [pdf](http://arxiv.org/pdf/2311.02772v1.pdf), cication: [**-1**](None)

	 *Sungho Jeon, Ching-Feng Yeh, Hakan Inan, Wei-Ning Hsu, Rashi Rungta, Yashar Mehdad, Daniel Bikel*
- **SALMONN: Towards Generic Hearing Abilities for Large Language Models**, `arXiv, 2310.13289`, [arxiv](http://arxiv.org/abs/2310.13289v1), [pdf](http://arxiv.org/pdf/2310.13289v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=10631342040411306525&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Changli Tang, Wenyi Yu, Guangzhi Sun, Xianzhao Chen, Tian Tan, Wei Li, Lu Lu, Zejun Ma, Chao Zhang*
	 · [SALMONN](https://github.com/bytedance/SALMONN/) - bytedance ![Star](https://img.shields.io/github/stars/bytedance/SALMONN.svg?style=social&label=Star)
- **LLaSM: Large Language and Speech Model**, `arXiv, 2308.15930`, [arxiv](http://arxiv.org/abs/2308.15930v3), [pdf](http://arxiv.org/pdf/2308.15930v3.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=2920079584099209720&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yu Shu, Siwei Dong, Guangyao Chen, Wenhao Huang, Ruihua Zhang, Daochen Shi, Qiqi Xiang, Yemin Shi*
	· [[llasm](https://github.com/linksoul-ai/llasm) - linksoul-ai] ![Star](https://img.shields.io/github/stars/linksoul-ai/llasm.svg?style=social&label=Star)
- **Prompting Large Language Models with Speech Recognition Abilities**, `arXiv, 2307.11795`, [arxiv](http://arxiv.org/abs/2307.11795v1), [pdf](http://arxiv.org/pdf/2307.11795v1.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=1465389802386940744&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yassir Fathullah, Chunyang Wu, Egor Lakomkin, Junteng Jia, Yuan Shangguan, Ke Li, Jinxi Guo, Wenhan Xiong, Jay Mahadeokar, Ozlem Kalinli*
- **Any-to-Any Generation via Composable Diffusion**, `arXiv, 2305.11846`, [arxiv](http://arxiv.org/abs/2305.11846v1), [pdf](http://arxiv.org/pdf/2305.11846v1.pdf), cication: [**-1**](None)

	 *Zineng Tang, Ziyi Yang, Chenguang Zhu, Michael Zeng, Mohit Bansal* · ([codi-gen.github](https://codi-gen.github.io/)) · ([i-Code](https://github.com/microsoft/i-Code/tree/main/i-Code-V3) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social&label=Star)

---
- ["宝藏AI神器"通义听悟上新：超长音视频随便问，高校师生可获500小时免费时长 | 量子位](https://www.qbitai.com/2024/03/129271.html)

## CLIP
- **MagicLens: Self-Supervised Image Retrieval with Open-Ended Instructions**, `arXiv, 2403.19651`, [arxiv](http://arxiv.org/abs/2403.19651v1), [pdf](http://arxiv.org/pdf/2403.19651v1.pdf), cication: [**-1**](None)

	 *Kai Zhang, Yi Luan, Hexiang Hu, Kenton Lee, Siyuan Qiao, Wenhu Chen, Yu Su, Ming-Wei Chang* · ([open-vision-language.github](https://open-vision-language.github.io/MagicLens/))
	- `leverages text instructions to facilitate the search for images based on a broad spectrum of relations beyond visual similarity.`
- **Long-CLIP: Unlocking the Long-Text Capability of CLIP**, `arXiv, 2403.15378`, [arxiv](http://arxiv.org/abs/2403.15378v1), [pdf](http://arxiv.org/pdf/2403.15378v1.pdf), cication: [**-1**](None)

	 *Beichen Zhang, Pan Zhang, Xiaoyi Dong, Yuhang Zang, Jiaqi Wang* · ([Long-CLIP](https://github.com/beichenzbc/Long-CLIP) - beichenzbc) ![Star](https://img.shields.io/github/stars/beichenzbc/Long-CLIP.svg?style=social&label=Star)
- **What do we learn from inverting CLIP models?**, `arXiv, 2403.02580`, [arxiv](http://arxiv.org/abs/2403.02580v1), [pdf](http://arxiv.org/pdf/2403.02580v1.pdf), cication: [**-1**](None)

	 *Hamid Kazemi, Atoosa Chegini, Jonas Geiping, Soheil Feizi, Tom Goldstein*
- **CLoVe: Encoding Compositional Language in Contrastive Vision-Language
  Models**, `arXiv, 2402.15021`, [arxiv](http://arxiv.org/abs/2402.15021v1), [pdf](http://arxiv.org/pdf/2402.15021v1.pdf), cication: [**-1**](None)

	 *Santiago Castro, Amir Ziai, Avneesh Saluja, Zhuoning Yuan, Rada Mihalcea* · ([clove](https://github.com/netflix/clove) - netflix) ![Star](https://img.shields.io/github/stars/netflix/clove.svg?style=social&label=Star)
- **MobileCLIP: Fast Image-Text Models through Multi-Modal Reinforced
  Training**, `arXiv, 2311.17049`, [arxiv](http://arxiv.org/abs/2311.17049v1), [pdf](http://arxiv.org/pdf/2311.17049v1.pdf), cication: [**-1**](None)

	 *Pavan Kumar Anasosalu Vasu, Hadi Pouransari, Fartash Faghri, Raviteja Vemulapalli, Oncel Tuzel* · ([ml-mobileclip](https://github.com/apple/ml-mobileclip) - apple) ![Star](https://img.shields.io/github/stars/apple/ml-mobileclip.svg?style=social&label=Star)
- **VeCLIP: Improving CLIP Training via Visual-enriched Captions**, `arXiv, 2310.07699`, [arxiv](http://arxiv.org/abs/2310.07699v2), [pdf](http://arxiv.org/pdf/2310.07699v2.pdf), cication: [**8**](https://scholar.google.com/scholar?cites=3904647199650419901&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhengfeng Lai, Haotian Zhang, Bowen Zhang, Wentao Wu, Haoping Bai, Aleksei Timofeev, Xianzhi Du, Zhe Gan, Jiulong Shan, Chen-Nee Chuah* · ([ml-veclip](https://github.com/apple/ml-veclip) - apple) ![Star](https://img.shields.io/github/stars/apple/ml-veclip.svg?style=social&label=Star)
## Alignment
- **BBA: Bi-Modal Behavioral Alignment for Reasoning with Large
  Vision-Language Models**, `arXiv, 2402.13577`, [arxiv](http://arxiv.org/abs/2402.13577v1), [pdf](http://arxiv.org/pdf/2402.13577v1.pdf), cication: [**-1**](None)

	 *Xueliang Zhao, Xinting Huang, Tingchen Fu, Qintong Li, Shansan Gong, Lemao Liu, Wei Bi, Lingpeng Kong*

## Efficient 
- **Cobra: Extending Mamba to Multi-Modal Large Language Model for Efficient
  Inference**, `arXiv, 2403.14520`, [arxiv](http://arxiv.org/abs/2403.14520v1), [pdf](http://arxiv.org/pdf/2403.14520v1.pdf), cication: [**-1**](None)

	 *Han Zhao, Min Zhang, Wei Zhao, Pengxiang Ding, Siteng Huang, Donglin Wang* · ([sites.google](https://sites.google.com/view/cobravlm))

	 · ([cobra](https://github.com/h-zhao1997/cobra) - h-zhao1997) ![Star](https://img.shields.io/github/stars/h-zhao1997/cobra.svg?style=social&label=Star) · ([twitter](https://twitter.com/han_zhao97/status/1772316050845053100))
	- *NOTE*
- **Small Language Model Meets with Reinforced Vision Vocabulary**, `arXiv, 2401.12503`, [arxiv](http://arxiv.org/abs/2401.12503v1), [pdf](http://arxiv.org/pdf/2401.12503v1.pdf), cication: [**-1**](None)

	 *Haoran Wei, Lingyu Kong, Jinyue Chen, Liang Zhao, Zheng Ge, En Yu, Jianjian Sun, Chunrui Han, Xiangyu Zhang*

## Extra Modalities 

- **VisionGPT-3D: A Generalized Multimodal Agent for Enhanced 3D Vision
  Understanding**, `arXiv, 2403.09530`, [arxiv](http://arxiv.org/abs/2403.09530v1), [pdf](http://arxiv.org/pdf/2403.09530v1.pdf), cication: [**-1**](None)

	 *Chris Kelly, Luhui Hu, Jiayin Hu, Yu Tian, Deshun Yang, Bang Yang, Cindy Yang, Zihao Li, Zaoshan Huang, Yuexian Zou*
- **Beyond Language Models: Byte Models are Digital World Simulators**, `arXiv, 2402.19155`, [arxiv](http://arxiv.org/abs/2402.19155v1), [pdf](http://arxiv.org/pdf/2402.19155v1.pdf), cication: [**-1**](None)

	 *Shangda Wu, Xu Tan, Zili Wang, Rui Wang, Xiaobing Li, Maosong Sun*
- **ChartX & ChartVLM: A Versatile Benchmark and Foundation Model for
  Complicated Chart Reasoning**, `arXiv, 2402.12185`, [arxiv](http://arxiv.org/abs/2402.12185v1), [pdf](http://arxiv.org/pdf/2402.12185v1.pdf), cication: [**-1**](None)

	 *Renqiu Xia, Bo Zhang, Hancheng Ye, Xiangchao Yan, Qi Liu, Hongbin Zhou, Zijun Chen, Min Dou, Botian Shi, Junchi Yan* · ([chartvlm](https://github.com/unimodal4reasoning/chartvlm) - unimodal4reasoning) ![Star](https://img.shields.io/github/stars/unimodal4reasoning/chartvlm.svg?style=social&label=Star)
- **Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision,
  Language, Audio, and Action**, `arXiv, 2312.17172`, [arxiv](http://arxiv.org/abs/2312.17172v1), [pdf](http://arxiv.org/pdf/2312.17172v1.pdf), cication: [**-1**](None)

	 *Jiasen Lu, Christopher Clark, Sangho Lee, Zichen Zhang, Savya Khosla, Ryan Marten, Derek Hoiem, Aniruddha Kembhavi*
- **AI-Generated Content (AIGC) for Various Data Modalities: A Survey**, `arXiv, 2308.14177`, [arxiv](http://arxiv.org/abs/2308.14177v4), [pdf](http://arxiv.org/pdf/2308.14177v4.pdf), cication: [**-1**](None)

	 *Lin Geng Foo, Hossein Rahmani, Jun Liu*
- **M3DBench: Let's Instruct Large Models with Multi-modal 3D Prompts**, `arXiv, 2312.10763`, [arxiv](http://arxiv.org/abs/2312.10763v1), [pdf](http://arxiv.org/pdf/2312.10763v1.pdf), cication: [**-1**](None)

	 *Mingsheng Li, Xin Chen, Chi Zhang, Sijin Chen, Hongyuan Zhu, Fukun Yin, Gang Yu, Tao Chen*
## Projects
- [**internlm-xcomposer2-4khd-7b**](https://huggingface.co/internlm/internlm-xcomposer2-4khd-7b) - internlm 🤗
- [anotherjesse.com - Rorschach Test For LLaVA LLM](https://anotherjesse.com/posts/llava-rorschach/)
- [**nanoLLaVA**](https://huggingface.co/qnguyen3/nanoLLaVA?utm_source=ainews) - qnguyen3 🤗
- [**Cerule-v0.1**](https://huggingface.co/Tensoic/Cerule-v0.1) - Tensoic 🤗
- [**LL3M**](https://github.com/jiasenlu/LL3M) - jiasenlu ![Star](https://img.shields.io/github/stars/jiasenlu/LL3M.svg?style=social&label=Star)

	 *LL3M: Large Language and Multi-Modal Model in Jax*
- [**uform**](https://github.com/unum-cloud/uform) - unum-cloud ![Star](https://img.shields.io/github/stars/unum-cloud/uform.svg?style=social&label=Star)

	 *Pocket-Sized Multimodal AI for content understanding and generation across multilingual texts, images, and 🔜 video, up to 5x faster than OpenAI CLIP and LLaVA 🖼️ & 🖋️* · ([unum-cloud.github](https://unum-cloud.github.io/uform/))
- [**DeepSeek-VL**](https://github.com/deepseek-ai/DeepSeek-VL) - deepseek-ai ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-VL.svg?style=social&label=Star)

	 *DeepSeek-VL: Towards Real-World Vision-Language Understanding* · ([huggingface](https://huggingface.co/spaces/deepseek-ai/DeepSeek-VL-7B))
- [**uform-gen2-qwen-500m**](https://huggingface.co/unum-cloud/uform-gen2-qwen-500m) - unum-cloud 🤗
- [**imp**](https://github.com/MILVLG/imp) - MILVLG ![Star](https://img.shields.io/github/stars/MILVLG/imp.svg?style=social&label=Star)

	 *a family of multimodal small language models* · ([huggingface](https://huggingface.co/MILVLG/imp-v1-3b)) · ([xmbot](https://xmbot.net/imp/))
- [**reading-analog-gauge**](https://huggingface.co/spaces/Synanthropic/reading-analog-gauge) - Synanthropic 🤗
- [**moondream**](https://github.com/vikhyat/moondream) - vikhyat ![Star](https://img.shields.io/github/stars/vikhyat/moondream.svg?style=social&label=Star)

	 *tiny vision language model* · ([huggingface](https://huggingface.co/vikhyatk/moondream1))

	 · ([huggingface](https://huggingface.co/spaces/vikhyatk/moondream2))
- [**FireLLaVA-13b**](https://huggingface.co/fireworks-ai/FireLLaVA-13b) - fireworks-ai 🤗

	 · ([app.fireworks](https://app.fireworks.ai/blog/firellava-the-first-commercially-permissive-oss-llava-model))
- [**Yi-VL-6B**](https://huggingface.co/01-ai/Yi-VL-6B) - 01-ai 🤗
- [**Yi-VL-34B**](https://huggingface.co/01-ai/Yi-VL-34B) - 01-ai 🤗
- [**hermes-llava**](https://github.com/qnguyen3/hermes-llava) - qnguyen3 ![Star](https://img.shields.io/github/stars/qnguyen3/hermes-llava.svg?style=social&label=Star)

	 · ([huggingface](https://huggingface.co/NousResearch/Nous-Hermes-2-Vision-Alpha))
- [**multimodal-maestro**](https://github.com/roboflow/multimodal-maestro) - roboflow ![Star](https://img.shields.io/github/stars/roboflow/multimodal-maestro.svg?style=social&label=Star)

	 *Effective prompting for Large Multimodal Models like GPT-4 Vision or LLaVA. 🔥*
- [**mic**](https://github.com/haozhezhao/mic) - haozhezhao ![Star](https://img.shields.io/github/stars/haozhezhao/mic.svg?style=social&label=Star)

	 *MMICL, a state-of-the-art VLM with the in context learning ability from ICL, PKU*
- [**awesome-openai-vision-api-experiments**](https://github.com/roboflow/awesome-openai-vision-api-experiments) - roboflow ![Star](https://img.shields.io/github/stars/roboflow/awesome-openai-vision-api-experiments.svg?style=social&label=Star)

	 *Examples showing how to use the OpenAI vision API to run inference on images, video files and webcam streams*
- [**fuyu-8b**](https://huggingface.co/adept/fuyu-8b) - adept 🤗

	 · [[qbitai](https://www.qbitai.com/2023/10/91055.html)]
- [**Mini-DALLE3**](https://github.com/Zeqiang-Lai/Mini-DALLE3) - Zeqiang-Lai ![Star](https://img.shields.io/github/stars/Zeqiang-Lai/Mini-DALLE3.svg?style=social&label=Star)

	 *Mini-DALLE3: Interactive Text to Image by Prompting Large Language Models*
- [**idefics-80b-instruct**](https://huggingface.co/HuggingFaceM4/idefics-80b-instruct) - HuggingFaceM4 🤗

	 · ([huggingface](https://huggingface.co/blog/idefics))
- [**LLaMA2-Accessory**](https://github.com/Alpha-VLLM/LLaMA2-Accessory) - Alpha-VLLM ![Star](https://img.shields.io/github/stars/Alpha-VLLM/LLaMA2-Accessory.svg?style=social&label=Star)

	 *An Open-source Toolkit for LLM Development*
- [**open_flamingo**](https://github.com/mlfoundations/open_flamingo) - mlfoundations ![Star](https://img.shields.io/github/stars/mlfoundations/open_flamingo.svg?style=social&label=Star)

	 *An open-source framework for training large multimodal models.*
- [**BakLLaVA-1**](https://huggingface.co/SkunkworksAI/BakLLaVA-1) - SkunkworksAI 🤗

## Evaluation
- **Are Language Models Puzzle Prodigies? Algorithmic Puzzles Unveil Serious
  Challenges in Multimodal Reasoning**, `arXiv, 2403.03864`, [arxiv](http://arxiv.org/abs/2403.03864v3), [pdf](http://arxiv.org/pdf/2403.03864v3.pdf), cication: [**-1**](None)

	 *Deepanway Ghosal, Vernon Toh Yan Han, Chia Yew Ken, Soujanya Poria*
- **How Far Are We from Intelligent Visual Deductive Reasoning?**, `arXiv, 2403.04732`, [arxiv](http://arxiv.org/abs/2403.04732v1), [pdf](http://arxiv.org/pdf/2403.04732v1.pdf), cication: [**-1**](None)

	 *Yizhe Zhang, He Bai, Ruixiang Zhang, Jiatao Gu, Shuangfei Zhai, Josh Susskind, Navdeep Jaitly*
	- `This study explores the capabilities of state-of-the-art Vision-Language Models (VLMs) like GPT-4V in the nuanced field of vision-based deductive reasoning, uncovering significant blindspots in visual deductive reasoning, and finding that techniques effective for text-based reasoning in LLMs don't directly apply to visual reasoning challenges.`
- **Are We on the Right Way for Evaluating Large Vision-Language Models?**, `arXiv, 2403.20330`, [arxiv](http://arxiv.org/abs/2403.20330v1), [pdf](http://arxiv.org/pdf/2403.20330v1.pdf), cication: [**-1**](None)

	 *Lin Chen, Jinsong Li, Xiaoyi Dong, Pan Zhang, Yuhang Zang, Zehui Chen, Haodong Duan, Jiaqi Wang, Yu Qiao, Dahua Lin*
- **Unsolvable Problem Detection: Evaluating Trustworthiness of Vision
  Language Models**, `arXiv, 2403.20331`, [arxiv](http://arxiv.org/abs/2403.20331v1), [pdf](http://arxiv.org/pdf/2403.20331v1.pdf), cication: [**-1**](None)

	 *Atsuyuki Miyai, Jingkang Yang, Jingyang Zhang, Yifei Ming, Qing Yu, Go Irie, Yixuan Li, Hai Li, Ziwei Liu, Kiyoharu Aizawa*
- **VL-ICL Bench: The Devil in the Details of Benchmarking Multimodal
  In-Context Learning**, `arXiv, 2403.13164`, [arxiv](http://arxiv.org/abs/2403.13164v1), [pdf](http://arxiv.org/pdf/2403.13164v1.pdf), cication: [**-1**](None)

	 *Yongshuo Zong, Ondrej Bohdal, Timothy Hospedales* · ([VL-ICL](https://github.com/ys-zong/VL-ICL) - ys-zong) ![Star](https://img.shields.io/github/stars/ys-zong/VL-ICL.svg?style=social&label=Star)
- [**open_vlm_leaderboard**](https://huggingface.co/spaces/opencompass/open_vlm_leaderboard?utm_source=ainews&utm_medium=email&utm_campaign=ainews-mm1-apples-first-large-multimodal-model) - opencompass 🤗
- [**VLMEvalKit**](https://github.com/open-compass/VLMEvalKit) - open-compass ![Star](https://img.shields.io/github/stars/open-compass/VLMEvalKit.svg?style=social&label=Star)

	 *Open-source evaluation toolkit of large vision-language models (LVLMs), support GPT-4v, Gemini, QwenVLPlus, 30+ HF models, 15+ benchmarks*
- [**lmms-eval**](https://github.com/EvolvingLMMs-Lab/lmms-eval) - EvolvingLMMs-Lab ![Star](https://img.shields.io/github/stars/EvolvingLMMs-Lab/lmms-eval.svg?style=social&label=Star)

	 *Accelerating the development of large multimodal models (LMMs) with lmms-eval* · ([lmms-lab.github](https://lmms-lab.github.io/lmms-eval-blog/lmms-eval-0.1/))
- [**NPHardEval4V**](https://github.com/lizhouf/NPHardEval4V) - lizhouf ![Star](https://img.shields.io/github/stars/lizhouf/NPHardEval4V.svg?style=social&label=Star)
- [**ConTextual**](https://github.com/rohan598/ConTextual) - rohan598 ![Star](https://img.shields.io/github/stars/rohan598/ConTextual.svg?style=social&label=Star)
- [**TempCompass**](https://github.com/llyx97/TempCompass) - llyx97 ![Star](https://img.shields.io/github/stars/llyx97/TempCompass.svg?style=social&label=Star)

	 *A benchmark to evaluate the temporal perception ability of Video LLMs*
- [**vision-arena**](https://huggingface.co/spaces/WildVision/vision-arena) - WildVision 🤗
- **Mementos: A Comprehensive Benchmark for Multimodal Large Language Model
  Reasoning over Image Sequences**, `arXiv, 2401.10529`, [arxiv](http://arxiv.org/abs/2401.10529v2), [pdf](http://arxiv.org/pdf/2401.10529v2.pdf), cication: [**-1**](None)

	 *Xiyao Wang, Yuhang Zhou, Xiaoyu Liu, Hongjin Lu, Yuancheng Xu, Feihong He, Jaehong Yoon, Taixi Lu, Gedas Bertasius, Mohit Bansal* · ([mementos-bench.github](https://mementos-bench.github.io))
- [Leaderboards | LAMM](https://openlamm.github.io/Leaderboards)
- **LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset,
  Framework, and Benchmark**, `arXiv, 2306.06687`, [arxiv](http://arxiv.org/abs/2306.06687v3), [pdf](http://arxiv.org/pdf/2306.06687v3.pdf), cication: [**-1**](None)

	 *Zhenfei Yin, Jiong Wang, Jianjian Cao, Zhelun Shi, Dingning Liu, Mukai Li, Lu Sheng, Lei Bai, Xiaoshui Huang, Zhiyong Wang* · ([LAMM](https://github.com/OpenGVLab/LAMM) - OpenGVLab) ![Star](https://img.shields.io/github/stars/OpenGVLab/LAMM.svg?style=social&label=Star)
- **BenchLMM: Benchmarking Cross-style Visual Capability of Large Multimodal
  Models**, `arXiv, 2312.02896`, [arxiv](http://arxiv.org/abs/2312.02896v2), [pdf](http://arxiv.org/pdf/2312.02896v2.pdf), cication: [**-1**](None)

	 *Rizhao Cai, Zirui Song, Dayan Guan, Zhenhao Chen, Xing Luo, Chenyu Yi, Alex Kot* · ([aifeg.github](https://aifeg.github.io/BenchLMM/)) · ([BenchLMM](https://github.com/AIFEG/BenchLMM) - AIFEG) ![Star](https://img.shields.io/github/stars/AIFEG/BenchLMM.svg?style=social&label=Star)
- [**MVBench_Leaderboard**](https://huggingface.co/spaces/OpenGVLab/MVBench_Leaderboard) - OpenGVLab 🤗
- **MMMU: A Massive Multi-discipline Multimodal Understanding and Reasoning
  Benchmark for Expert AGI**, `arXiv, 2311.16502`, [arxiv](http://arxiv.org/abs/2311.16502v1), [pdf](http://arxiv.org/pdf/2311.16502v1.pdf), cication: [**-1**](None)

	 *Xiang Yue, Yuansheng Ni, Kai Zhang, Tianyu Zheng, Ruoqi Liu, Ge Zhang, Samuel Stevens, Dongfu Jiang, Weiming Ren, Yuxuan Sun* · ([mmmu-benchmark.github](https://mmmu-benchmark.github.io/)) · ([MMMU](https://github.com/MMMU-Benchmark/MMMU) - MMMU-Benchmark) ![Star](https://img.shields.io/github/stars/MMMU-Benchmark/MMMU.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/datasets/MMMU/MMMU))
- **Video-Bench: A Comprehensive Benchmark and Toolkit for Evaluating
  Video-based Large Language Models**, `arXiv, 2311.16103`, [arxiv](http://arxiv.org/abs/2311.16103v2), [pdf](http://arxiv.org/pdf/2311.16103v2.pdf), cication: [**-1**](None)

	 *Munan Ning, Bin Zhu, Yujia Xie, Bin Lin, Jiaxi Cui, Lu Yuan, Dongdong Chen, Li Yuan* · ([video-bench](https://github.com/pku-yuangroup/video-bench) - pku-yuangroup) ![Star](https://img.shields.io/github/stars/pku-yuangroup/video-bench.svg?style=social&label=Star)
- **SEED-Bench: Benchmarking Multimodal LLMs with Generative Comprehension**, `arXiv, 2307.16125`, [arxiv](http://arxiv.org/abs/2307.16125v2), [pdf](http://arxiv.org/pdf/2307.16125v2.pdf), cication: [**12**](https://scholar.google.com/scholar?cites=16683160716323634121&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Bohao Li, Rui Wang, Guangzhi Wang, Yuying Ge, Yixiao Ge, Ying Shan*
- **HallusionBench: You See What You Think? Or You Think What You See? An
  Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5,
  and Other Multi-modality Models**, `arXiv, 2310.14566`, [arxiv](http://arxiv.org/abs/2310.14566v1), [pdf](http://arxiv.org/pdf/2310.14566v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=16632318392973274660&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Fuxiao Liu, Tianrui Guan, Zongxia Li, Lichang Chen, Yaser Yacoob, Dinesh Manocha, Tianyi Zhou*
- **VisIT-Bench: A Benchmark for Vision-Language Instruction Following
  Inspired by Real-World Use**, `arXiv, 2308.06595`, [arxiv](http://arxiv.org/abs/2308.06595v2), [pdf](http://arxiv.org/pdf/2308.06595v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=7953954865512108233&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yonatan Bitton, Hritik Bansal, Jack Hessel, Rulin Shao, Wanrong Zhu, Anas Awadalla, Josh Gardner, Rohan Taori, Ludwig Schimdt*
- **On the Hidden Mystery of OCR in Large Multimodal Models**, `arXiv, 2305.07895`, [arxiv](http://arxiv.org/abs/2305.07895v5), [pdf](http://arxiv.org/pdf/2305.07895v5.pdf), cication: [**29**](https://scholar.google.com/scholar?cites=13368693482898036166&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuliang Liu, Zhang Li, Biao Yang, Chunyuan Li, Xucheng Yin, Cheng-lin Liu, Lianwen Jin, Xiang Bai* · ([MultimodalOCR](https://github.com/Yuliang-Liu/MultimodalOCR) - Yuliang-Liu) ![Star](https://img.shields.io/github/stars/Yuliang-Liu/MultimodalOCR.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652442102&idx=4&sn=64a53646c57797a00b9db186f339c5eb))

## Datasets
- **Unlocking the conversion of Web Screenshots into HTML Code with the
  WebSight Dataset**, `arXiv, 2403.09029`, [arxiv](http://arxiv.org/abs/2403.09029v1), [pdf](http://arxiv.org/pdf/2403.09029v1.pdf), cication: [**-1**](None)

	 *Hugo Laurençon, Léo Tronchon, Victor Sanh*
- [**RAVEN**](https://huggingface.co/datasets/HuggingFaceM4/RAVEN) - HuggingFaceM4 🤗

	 · ([huggingface](https://huggingface.co/spaces/HuggingFaceM4/ai_raven))
- **Synth$^2$: Boosting Visual-Language Models with Synthetic Captions and
  Image Embeddings**, `arXiv, 2403.07750`, [arxiv](http://arxiv.org/abs/2403.07750v1), [pdf](http://arxiv.org/pdf/2403.07750v1.pdf), cication: [**-1**](None)

	 *Sahand Sharifzadeh, Christos Kaplanis, Shreya Pathak, Dharshan Kumaran, Anastasija Ilic, Jovana Mitrovic, Charles Blundell, Andrea Banino*
- **CapsFusion: Rethinking Image-Text Data at Scale**, `arXiv, 2310.20550`, [arxiv](http://arxiv.org/abs/2310.20550v2), [pdf](http://arxiv.org/pdf/2310.20550v2.pdf), cication: [**-1**](None)

	 *Qiying Yu, Quan Sun, Xiaosong Zhang, Yufeng Cui, Fan Zhang, Yue Cao, Xinlong Wang, Jingjing Liu*
- **OBELICS: An Open Web-Scale Filtered Dataset of Interleaved Image-Text
  Documents**, `NeurIPS, 2023`, [arxiv](http://arxiv.org/abs/2306.16527v2), [pdf](http://arxiv.org/pdf/2306.16527v2.pdf), cication: [**8**](https://scholar.google.com/scholar?cites=11222715136811886717&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hugo Laurençon, Lucile Saulnier, Léo Tronchon, Stas Bekman, Amanpreet Singh, Anton Lozhkov, Thomas Wang, Siddharth Karamcheti, Alexander M. Rush, Douwe Kiela*
- **DataComp: In search of the next generation of multimodal datasets**, `arXiv, 2304.14108`, [arxiv](http://arxiv.org/abs/2304.14108v5), [pdf](http://arxiv.org/pdf/2304.14108v5.pdf), cication: [**71**](https://scholar.google.com/scholar?cites=17915054761876319494&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Samir Yitzhak Gadre, Gabriel Ilharco, Alex Fang, Jonathan Hayase, Georgios Smyrnis, Thao Nguyen, Ryan Marten, Mitchell Wortsman, Dhruba Ghosh, Jieyu Zhang* · ([datacomp](http://www.datacomp.ai/))

## Other
- [Adept Fuyu-Heavy: A new multimodal model](https://www.adept.ai/blog/adept-fuyu-heavy)
- [GPT-4 Vision Alternatives](https://blog.roboflow.com/gpt-4-vision-alternatives/)
- **Multimodal Neurons in Pretrained Text-Only Transformers**, `ICCV, 2023`, [arxiv](http://arxiv.org/abs/2308.01544v2), [pdf](http://arxiv.org/pdf/2308.01544v2.pdf), cication: [**-1**](None)

	 *Sarah Schwettmann, Neil Chowdhury, Samuel Klein, David Bau, Antonio Torralba*

- [三年16篇一作，前谷歌研究科学家Yi Tay官宣新模型，21B媲美Gemini Pro、GPT-3.5 | 机器之心](https://www.jiqizhixin.com/articles/2024-02-15-13)
- [多模态LLM多到看不过来？先看这26个SOTA模型吧 | 机器之心](https://www.jiqizhixin.com/articles/2024-01-31-3)
- [多模态和多模态大模型](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247619958&idx=1&sn=493798d55e1aa583d103ee10ed04ef55)
- [中科院自动化所全模态大模型亮相，图文音视频3D传感器信号全能 | 量子位](https://www.qbitai.com/2023/06/61901.html)
- [从零训练一个多模态LLM](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494284&idx=2&sn=f3a4bbc3e1f5f0061e7da945ef7c88f6)

## Reference
- [**Awesome-LLM-3D**](https://github.com/ActiveVisionLab/Awesome-LLM-3D) - ActiveVisionLab ![Star](https://img.shields.io/github/stars/ActiveVisionLab/Awesome-LLM-3D.svg?style=social&label=Star)

	 *Awesome-LLM-3D: a curated list of Multi-modal Large Language Model in 3D world Resources*
- [**awesome-foundation-and-multimodal-models**](https://github.com/SkalskiP/awesome-foundation-and-multimodal-models) - SkalskiP ![Star](https://img.shields.io/github/stars/SkalskiP/awesome-foundation-and-multimodal-models.svg?style=social&label=Star)

	 *👁️ + 💬 + 🎧 = 🤖 Curated list of top foundation and multimodal models! [Paper + Code]*
- [**Awesome-Multimodal-Assistant**](https://github.com/zjr2000/Awesome-Multimodal-Assistant) - zjr2000 ![Star](https://img.shields.io/github/stars/zjr2000/Awesome-Multimodal-Assistant.svg?style=social&label=Star)

	 *Awesome Multimodal Assistant is a curated list of multimodal chatbots/conversational assistants that utilize various modes of interaction, such as text, speech, images, and videos, to provide a seamless and versatile user experience.*
- [**Awesome-Multimodal-Large-Language-Models**](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) - BradyFU ![Star](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star)

	 *:sparkles::sparkles:Latest Papers and Datasets on Multimodal Large Language Models, and Their Evaluation.*