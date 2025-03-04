# Awesom long-context llm

- [Awesom long-context llm](#awesom-long-context-llm)
	- [Survey](#survey)
	- [Papers](#papers)
	- [Projects](#projects)
	- [Other](#other)
	- [Extra reference](#extra-reference)

## Survey
- **In-Context Learning with Long-Context Models: An In-Depth Exploration**, `arXiv, 2405.00200`, [arxiv](http://arxiv.org/abs/2405.00200v1), [pdf](http://arxiv.org/pdf/2405.00200v1.pdf), cication: [**-1**](None)

	 *Amanda Bertsch, Maor Ivgi, Uri Alon, Jonathan Berant, Matthew R. Gormley, Graham Neubig*
- **Length Extrapolation of Transformers: A Survey from the Perspective of
  Position Encoding**, `arXiv, 2312.17044`, [arxiv](http://arxiv.org/abs/2312.17044v2), [pdf](http://arxiv.org/pdf/2312.17044v2.pdf), cication: [**-1**](None)

	 *Liang Zhao, Xiaocheng Feng, Xiachong Feng, Bing Qin, Ting Liu* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-01-15-16))
- **Advancing Transformer Architecture in Long-Context Large Language
  Models: A Comprehensive Survey**, `arXiv, 2311.12351`, [arxiv](http://arxiv.org/abs/2311.12351v1), [pdf](http://arxiv.org/pdf/2311.12351v1.pdf), cication: [**-1**](None)

	 *Yunpeng Huang, Jingwei Xu, Zixu Jiang, Junyu Lai, Zenan Li, Yuan Yao, Taolue Chen, Lijuan Yang, Zhou Xin, Xiaoxing Ma* · ([long-llms-learning](https://github.com/Strivin0311/long-llms-learning) - Strivin0311) ![Star](https://img.shields.io/github/stars/Strivin0311/long-llms-learning.svg?style=social&label=Star)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495588&idx=1&sn=22347cb1213ab2a49fc76d16eb302b19))
- [The Transformer Family | Lil'Log](https://lilianweng.github.io/posts/2020-04-07-the-transformer-family/#adaptive-computation-time-act)
- [The Transformer Family Version 2.0 | Lil'Log](https://lilianweng.github.io/posts/2023-01-27-the-transformer-family-v2/)
- [Attention? Attention! | Lil'Log](https://lilianweng.github.io/posts/2018-06-24-attention/#a-family-of-attention-mechanisms)

## Evaluation
- **LongGenBench: Long-context Generation Benchmark**, `arXiv, 2410.04199`, [arxiv](http://arxiv.org/abs/2410.04199v2), [pdf](http://arxiv.org/pdf/2410.04199v2.pdf), cication: [**-1**](None)

	 *Xiang Liu, Peijie Dong, Xuming Hu, Xiaowen Chu*
- **A Controlled Study on Long Context Extension and Generalization in LLMs**, `arXiv, 2409.12181`, [arxiv](http://arxiv.org/abs/2409.12181v2), [pdf](http://arxiv.org/pdf/2409.12181v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=18417659314857474187&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yi Lu, Jing Nathan Yan, Songlin Yang, Justin T. Chiu, Siyu Ren, Fei Yuan, Wenting Zhao, Zhiyong Wu, Alexander M. Rush* · ([HelloBench](https://github.com/Quehry/HelloBench) - Quehry) ![Star](https://img.shields.io/github/stars/Quehry/HelloBench.svg?style=social&label=Star)
- **Michelangelo: Long Context Evaluations Beyond Haystacks via Latent
  Structure Queries**, `arXiv, 2409.12640`, [arxiv](http://arxiv.org/abs/2409.12640v2), [pdf](http://arxiv.org/pdf/2409.12640v2.pdf), cication: [**-1**](None)

	 *Kiran Vodrahalli, Santiago Ontanon, Nilesh Tripuraneni, Kelvin Xu, Sanil Jain, Rakesh Shivanna, Jeffrey Hui, Nishanth Dikkala, Mehran Kazemi, Bahare Fatemi*
- **LongGenbench: Benchmarking Long-Form Generation in Long Context LLMs**, `arXiv, 2409.02076`, [arxiv](http://arxiv.org/abs/2409.02076v3), [pdf](http://arxiv.org/pdf/2409.02076v3.pdf), cication: [**-1**](None)

	 *Yuhao Wu, Ming Shan Hee, Zhiqing Hu, Roy Ka-Wei Lee* · ([SGT](https://github.com/mozhu621/SGT/tree/main/Dataset) - mozhu621) ![Star](https://img.shields.io/github/stars/mozhu621/SGT.svg?style=social&label=Star)
- **NeedleBench: Can LLMs Do Retrieval and Reasoning in 1 Million Context
  Window?**, `arXiv, 2407.11963`, [arxiv](http://arxiv.org/abs/2407.11963v1), [pdf](http://arxiv.org/pdf/2407.11963v1.pdf), cication: [**-1**](None)

	 *Mo Li, Songyang Zhang, Yunxin Liu, Kai Chen* · ([opencompass](https://github.com/open-compass/opencompass) - open-compass) ![Star](https://img.shields.io/github/stars/open-compass/opencompass.svg?style=social&label=Star)
- **Summary of a Haystack: A Challenge to Long-Context LLMs and RAG Systems**, `arXiv, 2407.01370`, [arxiv](http://arxiv.org/abs/2407.01370v1), [pdf](http://arxiv.org/pdf/2407.01370v1.pdf), cication: [**-1**](None)

	 *Philippe Laban, Alexander R. Fabbri, Caiming Xiong, Chien-Sheng Wu*
- **Counting-Stars: A Simple, Efficient, and Reasonable Strategy for
  Evaluating Long-Context Large Language Models**, `arXiv, 2403.11802`, [arxiv](http://arxiv.org/abs/2403.11802v2), [pdf](http://arxiv.org/pdf/2403.11802v2.pdf), cication: [**-1**](None)

	 *Mingyang Song, Mao Zheng, Xuan Luo* · ([Counting-Stars](https://github.com/nick7nlp/Counting-Stars) - nick7nlp) ![Star](https://img.shields.io/github/stars/nick7nlp/Counting-Stars.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s/rH7PNHYeTkZOlhSoFL6bpA))
- **Evaluating Very Long-Term Conversational Memory of LLM Agents**, `arXiv, 2402.17753`, [arxiv](http://arxiv.org/abs/2402.17753v1), [pdf](http://arxiv.org/pdf/2402.17753v1.pdf), cication: [**-1**](None)

	 *Adyasha Maharana, Dong-Ho Lee, Sergey Tulyakov, Mohit Bansal, Francesco Barbieri, Yuwei Fang*

## Papers
- **LongCite: Enabling LLMs to Generate Fine-grained Citations in
  Long-context QA**, `arXiv, 2409.02897`, [arxiv](http://arxiv.org/abs/2409.02897v3), [pdf](http://arxiv.org/pdf/2409.02897v3.pdf), cication: [**-1**](None)

	 *Jiajie Zhang, Yushi Bai, Xin Lv, Wanjun Gu, Danqing Liu, Minhao Zou, Shulin Cao, Lei Hou, Yuxiao Dong, Ling Feng* · ([x](https://x.com/rasbt/status/1845468766118850862))
- **DAPE: Data-Adaptive Positional Encoding for Length Extrapolation**, `arXiv, 2405.14722`, [arxiv](http://arxiv.org/abs/2405.14722v5), [pdf](http://arxiv.org/pdf/2405.14722v5.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=15380823334373100515&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chuanyang Zheng, Yihang Gao, Han Shi, Minbin Huang, Jingyao Li, Jing Xiong, Xiaozhe Ren, Michael Ng, Xin Jiang, Zhenguo Li* · ([DAPE](https://github.com/chuanyang-Zheng/DAPE) - chuanyang-Zheng) ![Star](https://img.shields.io/github/stars/chuanyang-Zheng/DAPE.svg?style=social&label=Star) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-10-12))
- **Long-Context LLMs Meet RAG: Overcoming Challenges for Long Inputs in RAG**, `arXiv, 2410.05983`, [arxiv](http://arxiv.org/abs/2410.05983v1), [pdf](http://arxiv.org/pdf/2410.05983v1.pdf), cication: [**-1**](None)

	 *Bowen Jin, Jinsung Yoon, Jiawei Han, Sercan O. Arik*
- **Ruler: A Model-Agnostic Method to Control Generated Length for Large
  Language Models**, `arXiv, 2409.18943`, [arxiv](http://arxiv.org/abs/2409.18943v2), [pdf](http://arxiv.org/pdf/2409.18943v2.pdf), cication: [**-1**](None)

	 *Jiaming Li, Lei Zhang, Yunshui Li, Ziqiang Liu, yuelin bai, Run Luo, Longze Chen, Min Yang* · ([Ruler](https://github.com/Geaming2002/Ruler) - Geaming2002) ![Star](https://img.shields.io/github/stars/Geaming2002/Ruler.svg?style=social&label=Star)
- **Discovering the Gems in Early Layers: Accelerating Long-Context LLMs
  with 1000x Input Token Reduction**, `arXiv, 2409.17422`, [arxiv](http://arxiv.org/abs/2409.17422v1), [pdf](http://arxiv.org/pdf/2409.17422v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=9375432174449913232&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhenmei Shi, Yifei Ming, Xuan-Phi Nguyen, Yingyu Liang, Shafiq Joty* · ([GemFilter](https://github.com/SalesforceAIResearch/GemFilter) - SalesforceAIResearch) ![Star](https://img.shields.io/github/stars/SalesforceAIResearch/GemFilter.svg?style=social&label=Star)
- **RetrievalAttention: Accelerating Long-Context LLM Inference via Vector
  Retrieval**, `arXiv, 2409.10516`, [arxiv](http://arxiv.org/abs/2409.10516v2), [pdf](http://arxiv.org/pdf/2409.10516v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=4240926382873051229&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Di Liu, Meng Chen, Baotong Lu, Huiqiang Jiang, Zhenhua Han, Qianxi Zhang, Qi Chen, Chengruidong Zhang, Bailu Ding, Kai Zhang*
- [Late Chunking in Long-Context Embedding Models](https://jina.ai/news/late-chunking-in-long-context-embedding-models/?nocache=1)
- **LongRecipe: Recipe for Efficient Long Context Generalization in Large
  Language Models**, `arXiv, 2409.00509`, [arxiv](http://arxiv.org/abs/2409.00509v2), [pdf](http://arxiv.org/pdf/2409.00509v2.pdf), cication: [**-1**](None)

	 *Zhiyuan Hu, Yuliang Liu, Jinman Zhao, Suyuchen Wang, Yan Wang, Wei Shen, Qing Gu, Anh Tuan Luu, See-Kiong Ng, Zhiwei Jiang* · ([LongRecipe](https://github.com/zhiyuanhubj/LongRecipe) - zhiyuanhubj) ![Star](https://img.shields.io/github/stars/zhiyuanhubj/LongRecipe.svg?style=social&label=Star)
- **Writing in the Margins: Better Inference Pattern for Long Context
  Retrieval**, `arXiv, 2408.14906`, [arxiv](http://arxiv.org/abs/2408.14906v1), [pdf](http://arxiv.org/pdf/2408.14906v1.pdf), cication: [**-1**](None)

	 *Melisa Russak, Umar Jamil, Christopher Bryant, Kiran Kamble, Axel Magnuson, Mateusz Russak, Waseem AlShikh* · ([writing-in-the-margins](https://github.com/writer/writing-in-the-margins) - writer) ![Star](https://img.shields.io/github/stars/writer/writing-in-the-margins.svg?style=social&label=Star)
- **FocusLLM: Scaling LLM's Context by Parallel Decoding**, `arXiv, 2408.11745`, [arxiv](http://arxiv.org/abs/2408.11745v1), [pdf](http://arxiv.org/pdf/2408.11745v1.pdf), cication: [**-1**](None)

	 *Zhenyu Li, Yike Zhang, Tengyu Pan, Yutao Sun, Zhichao Duan, Junjie Fang, Rong Han, Zixuan Wang, Jianyong Wang* · ([FocusLLM](https://github.com/leezythu/FocusLLM) - leezythu) ![Star](https://img.shields.io/github/stars/leezythu/FocusLLM.svg?style=social&label=Star)
- **LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs**, `arXiv, 2408.07055`, [arxiv](http://arxiv.org/abs/2408.07055v1), [pdf](http://arxiv.org/pdf/2408.07055v1.pdf), cication: [**-1**](None)

	 *Yushi Bai, Jiajie Zhang, Xin Lv, Linzhi Zheng, Siqi Zhu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li* · ([LongWriter](https://github.com/THUDM/LongWriter) - THUDM) ![Star](https://img.shields.io/github/stars/THUDM/LongWriter.svg?style=social&label=Star)
- **ChatQA 2: Bridging the Gap to Proprietary LLMs in Long Context and RAG
  Capabilities**, `arXiv, 2407.14482`, [arxiv](http://arxiv.org/abs/2407.14482v1), [pdf](http://arxiv.org/pdf/2407.14482v1.pdf), cication: [**-1**](None)

	 *Peng Xu, Wei Ping, Xianchao Wu, Zihan Liu, Mohammad Shoeybi, Bryan Catanzaro*
- **Human-like Episodic Memory for Infinite Context LLMs**, `arXiv, 2407.09450`, [arxiv](http://arxiv.org/abs/2407.09450v1), [pdf](http://arxiv.org/pdf/2407.09450v1.pdf), cication: [**-1**](None)

	 *Zafeirios Fountas, Martin A Benfeghoul, Adnan Oomerjee, Fenia Christopoulou, Gerasimos Lampouras, Haitham Bou-Ammar, Jun Wang*
- **Associative Recurrent Memory Transformer**, `arXiv, 2407.04841`, [arxiv](http://arxiv.org/abs/2407.04841v1), [pdf](http://arxiv.org/pdf/2407.04841v1.pdf), cication: [**-1**](None)

	 *Ivan Rodkin, Yuri Kuratov, Aydar Bulatov, Mikhail Burtsev*
- **Is It Really Long Context if All You Need Is Retrieval? Towards
  Genuinely Difficult Long Context NLP**, `arXiv, 2407.00402`, [arxiv](http://arxiv.org/abs/2407.00402v1), [pdf](http://arxiv.org/pdf/2407.00402v1.pdf), cication: [**-1**](None)

	 *Omer Goldman, Alon Jacovi, Aviv Slobodkin, Aviya Maimon, Ido Dagan, Reut Tsarfaty*
- **Sparser is Faster and Less is More: Efficient Sparse Attention for
  Long-Range Transformers**, `arXiv, 2406.16747`, [arxiv](http://arxiv.org/abs/2406.16747v1), [pdf](http://arxiv.org/pdf/2406.16747v1.pdf), cication: [**-1**](None)

	 *Chao Lou, Zixia Jia, Zilong Zheng, Kewei Tu*
- **Recite, Reconstruct, Recollect: Memorization in LMs as a Multifaceted
  Phenomenon**, `arXiv, 2406.17746`, [arxiv](http://arxiv.org/abs/2406.17746v1), [pdf](http://arxiv.org/pdf/2406.17746v1.pdf), cication: [**-1**](None)

	 *USVSN Sai Prashanth, Alvin Deng, Kyle O'Brien, Jyothir S V, Mohammad Aflah Khan, Jaydeep Borkar, Christopher A. Choquette-Choo, Jacob Ray Fuehne, Stella Biderman, Tracy Ke*
- **Can Long-Context Language Models Subsume Retrieval, RAG, SQL, and More?**, `arXiv, 2406.13121`, [arxiv](http://arxiv.org/abs/2406.13121v1), [pdf](http://arxiv.org/pdf/2406.13121v1.pdf), cication: [**-1**](None)

	 *Jinhyuk Lee, Anthony Chen, Zhuyun Dai, Dheeru Dua, Devendra Singh Sachan, Michael Boratko, Yi Luan, Sébastien M. R. Arnold, Vincent Perot, Siddharth Dalmia* · ([loft](https://github.com/google-deepmind/loft) - google-deepmind) ![Star](https://img.shields.io/github/stars/google-deepmind/loft.svg?style=social&label=Star)
- **THEANINE: Revisiting Memory Management in Long-term Conversations with
  Timeline-augmented Response Generation**, `arXiv, 2406.10996`, [arxiv](http://arxiv.org/abs/2406.10996v1), [pdf](http://arxiv.org/pdf/2406.10996v1.pdf), cication: [**-1**](None)

	 *Seo Hyun Kim, Kai Tzu-iunn Ong, Taeyoon Kwon, Namyoung Kim, Keummin Ka, SeongHyeon Bae, Yohan Jo, Seung-won Hwang, Dongha Lee, Jinyoung Yeo* · ([theanine-693b0.web](https://theanine-693b0.web.app/))
- **Recurrent Context Compression: Efficiently Expanding the Context Window
  of LLM**, `arXiv, 2406.06110`, [arxiv](http://arxiv.org/abs/2406.06110v1), [pdf](http://arxiv.org/pdf/2406.06110v1.pdf), cication: [**-1**](None)

	 *Chensen Huang, Guibo Zhu, Xuepeng Wang, Yifei Luo, Guojing Ge, Haoran Chen, Dong Yi, Jinqiao Wang* · ([RCC_Transformer](https://github.com/WUHU-G/RCC_Transformer?tab=readme-ov-file) - WUHU-G) ![Star](https://img.shields.io/github/stars/WUHU-G/RCC_Transformer.svg?style=social&label=Star)
- **Contextual Position Encoding: Learning to Count What's Important**, `arXiv, 2405.18719`, [arxiv](http://arxiv.org/abs/2405.18719v2), [pdf](http://arxiv.org/pdf/2405.18719v2.pdf), cication: [**-1**](None)

	 *Olga Golovneva, Tianlu Wang, Jason Weston, Sainbayar Sukhbaatar*
- **Are Long-LLMs A Necessity For Long-Context Tasks?**, `arXiv, 2405.15318`, [arxiv](http://arxiv.org/abs/2405.15318v1), [pdf](http://arxiv.org/pdf/2405.15318v1.pdf), cication: [**-1**](None)

	 *Hongjin Qian, Zheng Liu, Peitian Zhang, Kelong Mao, Yujia Zhou, Xu Chen, Zhicheng Dou*
- **Challenges in Deploying Long-Context Transformers: A Theoretical Peak
  Performance Analysis**, `arXiv, 2405.08944`, [arxiv](http://arxiv.org/abs/2405.08944v1), [pdf](http://arxiv.org/pdf/2405.08944v1.pdf), cication: [**-1**](None)

	 *Yao Fu*
- **Extending Llama-3's Context Ten-Fold Overnight**, `arXiv, 2404.19553`, [arxiv](http://arxiv.org/abs/2404.19553v1), [pdf](http://arxiv.org/pdf/2404.19553v1.pdf), cication: [**-1**](None)

	 *Peitian Zhang, Ninglu Shao, Zheng Liu, Shitao Xiao, Hongjin Qian, Qiwei Ye, Zhicheng Dou* · ([FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding) - FlagOpen) ![Star](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding.svg?style=social&label=Star)
- **Make Your LLM Fully Utilize the Context**, `arXiv, 2404.16811`, [arxiv](http://arxiv.org/abs/2404.16811v1), [pdf](http://arxiv.org/pdf/2404.16811v1.pdf), cication: [**-1**](None)

	 *Shengnan An, Zexiong Ma, Zeqi Lin, Nanning Zheng, Jian-Guang Lou* · ([FILM](https://github.com/microsoft/FILM) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/FILM.svg?style=social&label=Star)
- **SnapKV: LLM Knows What You are Looking for Before Generation**, `arXiv, 2404.14469`, [arxiv](http://arxiv.org/abs/2404.14469v1), [pdf](http://arxiv.org/pdf/2404.14469v1.pdf), cication: [**-1**](None)

	 *Yuhong Li, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, Deming Chen* · ([SnapKV](https://github.com/FasterDecoding/SnapKV) - FasterDecoding) ![Star](https://img.shields.io/github/stars/FasterDecoding/SnapKV.svg?style=social&label=Star)
- **LongEmbed: Extending Embedding Models for Long Context Retrieval**, `arXiv, 2404.12096`, [arxiv](http://arxiv.org/abs/2404.12096v1), [pdf](http://arxiv.org/pdf/2404.12096v1.pdf), cication: [**-1**](None)

	 *Dawei Zhu, Liang Wang, Nan Yang, Yifan Song, Wenhao Wu, Furu Wei, Sujian Li* · ([LongEmbed](https://github.com/dwzhu-pku/LongEmbed/blob/main) - dwzhu-pku) ![Star](https://img.shields.io/github/stars/dwzhu-pku/LongEmbed.svg?style=social&label=Star)
- **Megalodon: Efficient LLM Pretraining and Inference with Unlimited
  Context Length**, `arXiv, 2404.08801`, [arxiv](http://arxiv.org/abs/2404.08801v1), [pdf](http://arxiv.org/pdf/2404.08801v1.pdf), cication: [**-1**](None)

	 *Xuezhe Ma, Xiaomeng Yang, Wenhan Xiong, Beidi Chen, Lili Yu, Hao Zhang, Jonathan May, Luke Zettlemoyer, Omer Levy, Chunting Zhou* · ([megalodon](https://github.com/XuezheMax/megalodon) - XuezheMax) ![Star](https://img.shields.io/github/stars/XuezheMax/megalodon.svg?style=social&label=Star)
- **TransformerFAM: Feedback attention is working memory**, `arXiv, 2404.09173`, [arxiv](http://arxiv.org/abs/2404.09173v1), [pdf](http://arxiv.org/pdf/2404.09173v1.pdf), cication: [**-1**](None)

	 *Dongseong Hwang, Weiran Wang, Zhuoyuan Huo, Khe Chai Sim, Pedro Moreno Mengibar*
- **LLoCO: Learning Long Contexts Offline**, `arXiv, 2404.07979`, [arxiv](http://arxiv.org/abs/2404.07979v1), [pdf](http://arxiv.org/pdf/2404.07979v1.pdf), cication: [**-1**](None)

	 *Sijun Tan, Xiuyu Li, Shishir Patil, Ziyang Wu, Tianjun Zhang, Kurt Keutzer, Joseph E. Gonzalez, Raluca Ada Popa* · ([lloco](https://github.com/jeffreysijuntan/lloco) - jeffreysijuntan) ![Star](https://img.shields.io/github/stars/jeffreysijuntan/lloco.svg?style=social&label=Star)
- **RULER: What's the Real Context Size of Your Long-Context Language
  Models?**, `arXiv, 2404.06654`, [arxiv](http://arxiv.org/abs/2404.06654v1), [pdf](http://arxiv.org/pdf/2404.06654v1.pdf), cication: [**-1**](None)

	 *Cheng-Ping Hsieh, Simeng Sun, Samuel Kriman, Shantanu Acharya, Dima Rekesh, Fei Jia, Boris Ginsburg*
- **Leave No Context Behind: Efficient Infinite Context Transformers with
  Infini-attention**, `arXiv, 2404.07143`, [arxiv](http://arxiv.org/abs/2404.07143v1), [pdf](http://arxiv.org/pdf/2404.07143v1.pdf), cication: [**-1**](None)

	 *Tsendsuren Munkhdalai, Manaal Faruqui, Siddharth Gopal*
- **Long-context LLMs Struggle with Long In-context Learning**, `arXiv, 2404.02060`, [arxiv](http://arxiv.org/abs/2404.02060v1), [pdf](http://arxiv.org/pdf/2404.02060v1.pdf), cication: [**-1**](None)

	 *Tianle Li, Ge Zhang, Quy Duc Do, Xiang Yue, Wenhu Chen*
	- `the LLMs perform relatively well under the token length of 20K. However, after the context window exceeds 20K, most LLMs except GPT-4 will dip dramatically.`
- **BurstAttention: An Efficient Distributed Attention Framework for
  Extremely Long Sequences**, `arXiv, 2403.09347`, [arxiv](http://arxiv.org/abs/2403.09347v1), [pdf](http://arxiv.org/pdf/2403.09347v1.pdf), cication: [**-1**](None)

	 *Sun Ao, Weilin Zhao, Xu Han, Cheng Yang, Zhiyuan Liu, Chuan Shi, Maosong Sun, Shengnan Wang, Teng Su*
	- `optimizes distributed attention in Transformer-based models for long sequences, cutting communication overhead by 40% and doubling processing speed on GPUs.`
- **Gemini 1.5: Unlocking multimodal understanding across millions of tokens
  of context**, `arXiv, 2403.05530`, [arxiv](http://arxiv.org/abs/2403.05530v1), [pdf](http://arxiv.org/pdf/2403.05530v1.pdf), cication: [**-1**](None)

	 *Machel Reid, Nikolay Savinov, Denis Teplyashin, Dmitry Lepikhin, Timothy Lillicrap, Jean-baptiste Alayrac, Radu Soricut, Angeliki Lazaridou, Orhan Firat, Julian Schrittwieser*
- **Resonance RoPE: Improving Context Length Generalization of Large
  Language Models**, `arXiv, 2403.00071`, [arxiv](http://arxiv.org/abs/2403.00071v1), [pdf](http://arxiv.org/pdf/2403.00071v1.pdf), cication: [**-1**](None)

	 *Suyuchen Wang, Ivan Kobyzev, Peng Lu, Mehdi Rezagholizadeh, Bang Liu*
- **Long-Context Language Modeling with Parallel Context Encoding**, `arXiv, 2402.16617`, [arxiv](http://arxiv.org/abs/2402.16617v1), [pdf](http://arxiv.org/pdf/2402.16617v1.pdf), cication: [**-1**](None)

	 *Howard Yen, Tianyu Gao, Danqi Chen* · ([qbitai](https://www.qbitai.com/2024/02/124308.html))

	 · ([cepe](https://github.com/princeton-nlp/cepe) - princeton-nlp) ![Star](https://img.shields.io/github/stars/princeton-nlp/cepe.svg?style=social&label=Star)
- **A Human-Inspired Reading Agent with Gist Memory of Very Long Contexts**, `arXiv, 2402.09727`, [arxiv](http://arxiv.org/abs/2402.09727v2), [pdf](http://arxiv.org/pdf/2402.09727v2.pdf), cication: [**-1**](None)

	 *Kuang-Huei Lee, Xinyun Chen, Hiroki Furuta, John Canny, Ian Fischer* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652463844&idx=3&sn=b6b5d8ba204d8fc108c6b1590d9679f4))
- **Training-Free Long-Context Scaling of Large Language Models**, `arXiv, 2402.17463`, [arxiv](http://arxiv.org/abs/2402.17463v1), [pdf](http://arxiv.org/pdf/2402.17463v1.pdf), cication: [**-1**](None)

	 *Chenxin An, Fei Huang, Jun Zhang, Shansan Gong, Xipeng Qiu, Chang Zhou, Lingpeng Kong* · ([ChunkLlama](https://github.com/HKUNLP/ChunkLlama) - HKUNLP) ![Star](https://img.shields.io/github/stars/HKUNLP/ChunkLlama.svg?style=social&label=Star)
- **LongRoPE: Extending LLM Context Window Beyond 2 Million Tokens**, `arXiv, 2402.13753`, [arxiv](http://arxiv.org/abs/2402.13753v1), [pdf](http://arxiv.org/pdf/2402.13753v1.pdf), cication: [**-1**](None)

	 *Yiran Ding, Li Lyna Zhang, Chengruidong Zhang, Yuanyuan Xu, Ning Shang, Jiahang Xu, Fan Yang, Mao Yang*
- **$\infty$Bench: Extending Long Context Evaluation Beyond 100K Tokens**, `arXiv, 2402.13718`, [arxiv](http://arxiv.org/abs/2402.13718v1), [pdf](http://arxiv.org/pdf/2402.13718v1.pdf), cication: [**-1**](None)

	 *Xinrong Zhang, Yingfa Chen, Shengding Hu, Zihang Xu, Junhao Chen, Moo Khai Hao, Xu Han, Zhen Leng Thai, Shuo Wang, Zhiyuan Liu*
- **LongAgent: Scaling Language Models to 128k Context through Multi-Agent
  Collaboration**, `arXiv, 2402.11550`, [arxiv](http://arxiv.org/abs/2402.11550v1), [pdf](http://arxiv.org/pdf/2402.11550v1.pdf), cication: [**-1**](None)

	 *Jun Zhao, Can Zu, Hao Xu, Yi Lu, Wei He, Yiwen Ding, Tao Gui, Qi Zhang, Xuanjing Huang*
- **InfLLM: Unveiling the Intrinsic Capacity of LLMs for Understanding
  Extremely Long Sequences with Training-Free Memory**, `arXiv, 2402.04617`, [arxiv](http://arxiv.org/abs/2402.04617v1), [pdf](http://arxiv.org/pdf/2402.04617v1.pdf), cication: [**-1**](None)

	 *Chaojun Xiao, Pengle Zhang, Xu Han, Guangxuan Xiao, Yankai Lin, Zhengyan Zhang, Zhiyuan Liu, Song Han, Maosong Sun*

	 · ([InfLLM](https://github.com/thunlp/InfLLM) - thunlp) ![Star](https://img.shields.io/github/stars/thunlp/InfLLM.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652453563&idx=5&sn=0384b125deb9cc79f7a09df503269e94))
- **In Search of Needles in a 10M Haystack: Recurrent Memory Finds What LLMs
  Miss**, `arXiv, 2402.10790`, [arxiv](http://arxiv.org/abs/2402.10790v1), [pdf](http://arxiv.org/pdf/2402.10790v1.pdf), cication: [**-1**](None)

	 *Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev*
- **Data Engineering for Scaling Language Models to 128K Context**, `arXiv, 2402.10171`, [arxiv](http://arxiv.org/abs/2402.10171v1), [pdf](http://arxiv.org/pdf/2402.10171v1.pdf), cication: [**-1**](None)

	 *Yao Fu, Rameswar Panda, Xinyao Niu, Xiang Yue, Hannaneh Hajishirzi, Yoon Kim, Hao Peng* · ([long-context-data-engineering](https://github.com/franxyao/long-context-data-engineering?tab=readme-ov-file) - franxyao) ![Star](https://img.shields.io/github/stars/franxyao/long-context-data-engineering.svg?style=social&label=Star)
- **Transformers Can Achieve Length Generalization But Not Robustly**, `arXiv, 2402.09371`, [arxiv](http://arxiv.org/abs/2402.09371v1), [pdf](http://arxiv.org/pdf/2402.09371v1.pdf), cication: [**-1**](None)

	 *Yongchao Zhou, Uri Alon, Xinyun Chen, Xuezhi Wang, Rishabh Agarwal, Denny Zhou*
- **KVQuant: Towards 10 Million Context Length LLM Inference with KV Cache
  Quantization**, `arXiv, 2401.18079`, [arxiv](http://arxiv.org/abs/2401.18079v1), [pdf](http://arxiv.org/pdf/2401.18079v1.pdf), cication: [**-1**](None)

	 *Coleman Hooper, Sehoon Kim, Hiva Mohammadzadeh, Michael W. Mahoney, Yakun Sophia Shao, Kurt Keutzer, Amir Gholami*
- [**Long-Context-Data-Engineering**](https://github.com/FranxYao/Long-Context-Data-Engineering) - FranxYao ![Star](https://img.shields.io/github/stars/FranxYao/Long-Context-Data-Engineering.svg?style=social&label=Star)

	 *Implementation of paper Data Engineering for Scaling Language Models to 128K Context*
- **LongAlign: A Recipe for Long Context Alignment of Large Language Models**, `arXiv, 2401.18058`, [arxiv](http://arxiv.org/abs/2401.18058v1), [pdf](http://arxiv.org/pdf/2401.18058v1.pdf), cication: [**-1**](None)

	 *Yushi Bai, Xin Lv, Jiajie Zhang, Yuze He, Ji Qi, Lei Hou, Jie Tang, Yuxiao Dong, Juanzi Li* · ([LongAlign](https://github.com/THUDM/LongAlign) - THUDM) ![Star](https://img.shields.io/github/stars/THUDM/LongAlign.svg?style=social&label=Star)
- **With Greater Text Comes Greater Necessity: Inference-Time Training Helps
  Long Text Generation**, `arXiv, 2401.11504`, [arxiv](http://arxiv.org/abs/2401.11504v1), [pdf](http://arxiv.org/pdf/2401.11504v1.pdf), cication: [**-1**](None)

	 *Y. Wang, D. Ma, D. Cai* · ([zhuanlan.zhihu](https://zhuanlan.zhihu.com/p/679713147))
- **E^2-LLM: Efficient and Extreme Length Extension of Large Language Models**, `arXiv, 2401.06951`, [arxiv](http://arxiv.org/abs/2401.06951v2), [pdf](http://arxiv.org/pdf/2401.06951v2.pdf), cication: [**-1**](None)

	 *Jiaheng Liu, Zhiqi Bai, Yuanxing Zhang, Chenchen Zhang, Yu Zhang, Ge Zhang, Jiakai Wang, Haoran Que, Yukang Chen, Wenbo Su*
- **Extending LLMs' Context Window with 100 Samples**, `arXiv, 2401.07004`, [arxiv](http://arxiv.org/abs/2401.07004v1), [pdf](http://arxiv.org/pdf/2401.07004v1.pdf), cication: [**-1**](None)

	 *Yikai Zhang, Junlong Li, Pengfei Liu* · ([Entropy-ABF](https://github.com/GAIR-NLP/Entropy-ABF) - GAIR-NLP) ![Star](https://img.shields.io/github/stars/GAIR-NLP/Entropy-ABF.svg?style=social&label=Star)
- **Transformers are Multi-State RNNs**, `arXiv, 2401.06104`, [arxiv](http://arxiv.org/abs/2401.06104v1), [pdf](http://arxiv.org/pdf/2401.06104v1.pdf), cication: [**-1**](None)

	 *Matanel Oren, Michael Hassid, Yossi Adi, Roy Schwartz* · ([TOVA](https://github.com/schwartz-lab-NLP/TOVA) - schwartz-lab-NLP) ![Star](https://img.shields.io/github/stars/schwartz-lab-NLP/TOVA.svg?style=social&label=Star)
- **Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence
  Lengths in Large Language Models**, `arXiv, 2401.04658`, [arxiv](http://arxiv.org/abs/2401.04658v1), [pdf](http://arxiv.org/pdf/2401.04658v1.pdf), cication: [**-1**](None)

	 *Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong* · ([lightning-attention](https://github.com/OpenNLPLab/lightning-attention) - OpenNLPLab) ![Star](https://img.shields.io/github/stars/OpenNLPLab/lightning-attention.svg?style=social&label=Star)
- **Infinite-LLM: Efficient LLM Service for Long Context with DistAttention
  and Distributed KVCache**, `arXiv, 2401.02669`, [arxiv](http://arxiv.org/abs/2401.02669v1), [pdf](http://arxiv.org/pdf/2401.02669v1.pdf), cication: [**-1**](None)

	 *Bin Lin, Tao Peng, Chen Zhang, Minmin Sun, Lanbo Li, Hanyu Zhao, Wencong Xiao, Qi Xu, Xiafei Qiu, Shen Li*
- **LLM Maybe LongLM: Self-Extend LLM Context Window Without Tuning**, `arXiv, 2401.01325`, [arxiv](http://arxiv.org/abs/2401.01325v1), [pdf](http://arxiv.org/pdf/2401.01325v1.pdf), cication: [**-1**](None)

	 *Hongye Jin, Xiaotian Han, Jingfeng Yang, Zhimeng Jiang, Zirui Liu, Chia-Yuan Chang, Huiyuan Chen, Xia Hu* · ([qbitai](https://www.qbitai.com/2024/01/112273.html))
- **Cached Transformers: Improving Transformers with Differentiable Memory
  Cache**, `arXiv, 2312.12742`, [arxiv](http://arxiv.org/abs/2312.12742v1), [pdf](http://arxiv.org/pdf/2312.12742v1.pdf), cication: [**-1**](None)

	 *Zhaoyang Zhang, Wenqi Shao, Yixiao Ge, Xiaogang Wang, Jinwei Gu, Ping Luo*
- **Extending Context Window of Large Language Models via Semantic
  Compression**, `arXiv, 2312.09571`, [arxiv](http://arxiv.org/abs/2312.09571v1), [pdf](http://arxiv.org/pdf/2312.09571v1.pdf), cication: [**-1**](None)

	 *Weizhi Fei, Xueyan Niu, Pingyi Zhou, Lu Hou, Bo Bai, Lei Deng, Wei Han*
- **Zebra: Extending Context Window with Layerwise Grouped Local-Global
  Attention**, `arXiv, 2312.08618`, [arxiv](http://arxiv.org/abs/2312.08618v1), [pdf](http://arxiv.org/pdf/2312.08618v1.pdf), cication: [**-1**](None)

	 *Kaiqiang Song, Xiaoyang Wang, Sangwoo Cho, Xiaoman Pan, Dong Yu*
- **Ultra-Long Sequence Distributed Transformer**, `arXiv, 2311.02382`, [arxiv](http://arxiv.org/abs/2311.02382v2), [pdf](http://arxiv.org/pdf/2311.02382v2.pdf), cication: [**-1**](None)

	 *Xiao Wang, Isaac Lyngaas, Aristeidis Tsaris, Peng Chen, Sajal Dash, Mayanka Chandra Shekar, Tao Luo, Hong-Jun Yoon, Mohamed Wahib, John Gouley*
- **HyperAttention: Long-context Attention in Near-Linear Time**, `arXiv, 2310.05869`, [arxiv](http://arxiv.org/abs/2310.05869v2), [pdf](http://arxiv.org/pdf/2310.05869v2.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=12733927342294964560&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Insu Han, Rajesh Jayaram, Amin Karbasi, Vahab Mirrokni, David P. Woodruff, Amir Zandieh*
- **CLEX: Continuous Length Extrapolation for Large Language Models**, `arXiv, 2310.16450`, [arxiv](http://arxiv.org/abs/2310.16450v1), [pdf](http://arxiv.org/pdf/2310.16450v1.pdf), cication: [**-1**](None)

	 *Guanzheng Chen, Xin Li, Zaiqiao Meng, Shangsong Liang, Lidong Bing*
- **TRAMS: Training-free Memory Selection for Long-range Language Modeling**, `arXiv, 2310.15494`, [arxiv](http://arxiv.org/abs/2310.15494v2), [pdf](http://arxiv.org/pdf/2310.15494v2.pdf), cication: [**-1**](None)

	 *Haofei Yu, Cunxiang Wang, Yue Zhang, Wei Bi*
- **Ring Attention with Blockwise Transformers for Near-Infinite Context**, `arXiv, 2310.01889`, [arxiv](http://arxiv.org/abs/2310.01889v4), [pdf](http://arxiv.org/pdf/2310.01889v4.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=8066346532887973744&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hao Liu, Matei Zaharia, Pieter Abbeel* · ([RingAttention](https://github.com/lhao499/RingAttention) - lhao499) ![Star](https://img.shields.io/github/stars/lhao499/RingAttention.svg?style=social&label=Star)
- **Walking Down the Memory Maze: Beyond Context Limit through Interactive
  Reading**, `arXiv, 2310.05029`, [arxiv](http://arxiv.org/abs/2310.05029v1), [pdf](http://arxiv.org/pdf/2310.05029v1.pdf), cication: [**-1**](None)

	 *Howard Chen, Ramakanth Pasunuru, Jason Weston, Asli Celikyilmaz* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652394913&idx=5&sn=173aada0b5d667541f02c12ddda4a357))
- **Scaling Laws of RoPE-based Extrapolation**, `arXiv, 2310.05209`, [arxiv](http://arxiv.org/abs/2310.05209v1), [pdf](http://arxiv.org/pdf/2310.05209v1.pdf), cication: [**-1**](None)

	 *Xiaoran Liu, Hang Yan, Shuo Zhang, Chenxin An, Xipeng Qiu, Dahua Lin* · ([qbitai](https://www.qbitai.com/2023/10/91648.html))
- **Walking Down the Memory Maze: Beyond Context Limit through Interactive
  Reading**, `arXiv, 2310.05029`, [arxiv](http://arxiv.org/abs/2310.05029v1), [pdf](http://arxiv.org/pdf/2310.05029v1.pdf), cication: [**-1**](None)

	 *Howard Chen, Ramakanth Pasunuru, Jason Weston, Asli Celikyilmaz*
- **Ring Attention with Blockwise Transformers for Near-Infinite Context**, `arXiv, 2310.01889`, [arxiv](http://arxiv.org/abs/2310.01889v3), [pdf](http://arxiv.org/pdf/2310.01889v3.pdf), cication: [**-1**](None)

	 *Hao Liu, Matei Zaharia, Pieter Abbeel*
- **EIPE-text: Evaluation-Guided Iterative Plan Extraction for Long-Form
  Narrative Text Generation**, `arXiv, 2310.08185`, [arxiv](http://arxiv.org/abs/2310.08185v1), [pdf](http://arxiv.org/pdf/2310.08185v1.pdf), cication: [**-1**](None)

	 *Wang You, Wenshan Wu, Yaobo Liang, Shaoguang Mao, Chenfei Wu, Maosong Cao, Yuzhe Cai, Yiduo Guo, Yan Xia, Furu Wei*
- **CoCA: Fusing position embedding with Collinear Constrained Attention for
  fine-tuning free context window extending**, `arXiv, 2309.08646`, [arxiv](http://arxiv.org/abs/2309.08646v2), [pdf](http://arxiv.org/pdf/2309.08646v2.pdf), cication: [**-1**](None)

	 *Shiyi Zhu, Jing Ye, Wei Jiang, Qi Zhang, Yifan Wu, Jianguo Li* · ([Collinear-Constrained-Attention](https://github.com/codefuse-ai/Collinear-Constrained-Attention) - codefuse-ai) ![Star](https://img.shields.io/github/stars/codefuse-ai/Collinear-Constrained-Attention.svg?style=social&label=Star) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-13-9))
- **PoSE: Efficient Context Window Extension of LLMs via Positional
  Skip-wise Training**, `arXiv, 2309.10400`, [arxiv](http://arxiv.org/abs/2309.10400v3), [pdf](http://arxiv.org/pdf/2309.10400v3.pdf), cication: [**-1**](None)

	 *Dawei Zhu, Nan Yang, Liang Wang, Yifan Song, Wenhao Wu, Furu Wei, Sujian Li* · ([PoSE](https://github.com/dwzhu-pku/PoSE) - dwzhu-pku) ![Star](https://img.shields.io/github/stars/dwzhu-pku/PoSE.svg?style=social&label=Star)
- **Effective Long-Context Scaling of Foundation Models**, `arXiv, 2309.16039`, [arxiv](http://arxiv.org/abs/2309.16039v2), [pdf](http://arxiv.org/pdf/2309.16039v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=11499544443437070837&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wenhan Xiong, Jingyu Liu, Igor Molybog, Hejia Zhang, Prajjwal Bhargava, Rui Hou, Louis Martin, Rashi Rungta, Karthik Abinav Sankararaman, Barlas Oguz* · ([qbitai](https://www.qbitai.com/2023/09/87178.html))
- **LM-Infinite: Simple On-the-Fly Length Generalization for Large Language
  Models**, `arXiv, 2308.16137`, [arxiv](http://arxiv.org/abs/2308.16137v4), [pdf](http://arxiv.org/pdf/2308.16137v4.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=12333597550468686714&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chi Han, Qifan Wang, Wenhan Xiong, Yu Chen, Heng Ji, Sinong Wang*
- **DeepSpeed Ulysses: System Optimizations for Enabling Training of Extreme
  Long Sequence Transformer Models**, `arXiv, 2309.14509`, [arxiv](http://arxiv.org/abs/2309.14509v2), [pdf](http://arxiv.org/pdf/2309.14509v2.pdf), cication: [**-1**](None)

	 *Sam Ade Jacobs, Masahiro Tanaka, Chengming Zhang, Minjia Zhang, Shuaiwen Leon Song, Samyam Rajbhandari, Yuxiong He*
- **YaRN: Efficient Context Window Extension of Large Language Models**, `arXiv, 2309.00071`, [arxiv](http://arxiv.org/abs/2309.00071v2), [pdf](http://arxiv.org/pdf/2309.00071v2.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=4031663212894418290&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Bowen Peng, Jeffrey Quesnelle, Honglu Fan, Enrico Shippole* · ([yarn](https://github.com/jquesnelle/yarn) - jquesnelle) ![Star](https://img.shields.io/github/stars/jquesnelle/yarn.svg?style=social&label=Star) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-13-10))
- **In-context Autoencoder for Context Compression in a Large Language Model**, `arXiv, 2307.06945`, [arxiv](http://arxiv.org/abs/2307.06945v2), [pdf](http://arxiv.org/pdf/2307.06945v2.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=16575040938931374371&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tao Ge, Jing Hu, Lei Wang, Xun Wang, Si-Qing Chen, Furu Wei*
- **Focused Transformer: Contrastive Training for Context Scaling**, `arXiv, 2307.03170`, [arxiv](http://arxiv.org/abs/2307.03170v1), [pdf](http://arxiv.org/pdf/2307.03170v1.pdf), cication: [**12**](https://scholar.google.com/scholar?cites=9230341592198565561&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Szymon Tworkowski, Konrad Staniszewski, Mikołaj Pacek, Yuhuai Wu, Henryk Michalewski, Piotr Miłoś*
- **Lost in the Middle: How Language Models Use Long Contexts**, `arXiv, 2307.03172`, [arxiv](http://arxiv.org/abs/2307.03172v2), [pdf](http://arxiv.org/pdf/2307.03172v2.pdf), cication: [**64**](https://scholar.google.com/scholar?cites=9077647831317733932&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang*
- **Compressing Context to Enhance Inference Efficiency of Large Language
  Models**, `arXiv, 2310.06201`, [arxiv](http://arxiv.org/abs/2310.06201v1), [pdf](http://arxiv.org/pdf/2310.06201v1.pdf), cication: [**45**](https://scholar.google.com/scholar?cites=13868303632723655161&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yucheng Li, Bo Dong, Chenghua Lin, Frank Guerin* · ([selective_context](https://github.com/liyucheng09/selective_context) - liyucheng09) ![Star](https://img.shields.io/github/stars/liyucheng09/selective_context.svg?style=social&label=Star)
- **LongNet: Scaling Transformers to 1,000,000,000 Tokens**, `arXiv, 2307.02486`, [arxiv](http://arxiv.org/abs/2307.02486v2), [pdf](http://arxiv.org/pdf/2307.02486v2.pdf), cication: [**15**](https://scholar.google.com/scholar?cites=9993250623533435628&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jiayu Ding, Shuming Ma, Li Dong, Xingxing Zhang, Shaohan Huang, Wenhui Wang, Nanning Zheng, Furu Wei*
- **Extending Context Window of Large Language Models via Positional
  Interpolation**, `arXiv, 2306.15595`, [arxiv](http://arxiv.org/abs/2306.15595v2), [pdf](http://arxiv.org/pdf/2306.15595v2.pdf), cication: [**36**](https://scholar.google.com/scholar?cites=16329089917044170292&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shouyuan Chen, Sherman Wong, Liangjian Chen, Yuandong Tian* · ([qbitai](https://www.qbitai.com/2023/06/64516.html))
- **The Impact of Positional Encoding on Length Generalization in
  Transformers**, `arXiv, 2305.19466`, [arxiv](http://arxiv.org/abs/2305.19466v2), [pdf](http://arxiv.org/pdf/2305.19466v2.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=4006212005145195153&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Amirhossein Kazemnejad, Inkit Padhi, Karthikeyan Natesan Ramamurthy, Payel Das, Siva Reddy*
- **Long-range Language Modeling with Self-retrieval**, `arXiv, 2306.13421`, [arxiv](http://arxiv.org/abs/2306.13421v1), [pdf](http://arxiv.org/pdf/2306.13421v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=13798183978039596966&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ohad Rubin, Jonathan Berant*
- **Block-State Transformers**, `arXiv, 2306.09539`, [arxiv](http://arxiv.org/abs/2306.09539v4), [pdf](http://arxiv.org/pdf/2306.09539v4.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=15343899864948628782&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Mahan Fathi, Jonathan Pilault, Orhan Firat, Christopher Pal, Pierre-Luc Bacon, Ross Goroshin*
- **LeanDojo: Theorem Proving with Retrieval-Augmented Language Models**, `arXiv, 2306.15626`, [arxiv](http://arxiv.org/abs/2306.15626v2), [pdf](http://arxiv.org/pdf/2306.15626v2.pdf), cication: [**14**](https://scholar.google.com/scholar?cites=16638561208416938954&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Kaiyu Yang, Aidan M. Swope, Alex Gu, Rahul Chalamala, Peiyang Song, Shixing Yu, Saad Godil, Ryan Prenger, Anima Anandkumar*
- **GLIMMER: generalized late-interaction memory reranker**, `arXiv, 2306.10231`, [arxiv](http://arxiv.org/abs/2306.10231v1), [pdf](http://arxiv.org/pdf/2306.10231v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=13889321003607649821&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Michiel de Jong, Yury Zemlyanskiy, Nicholas FitzGerald, Sumit Sanghai, William W. Cohen, Joshua Ainslie*
- **The Impact of Positional Encoding on Length Generalization in
  Transformers**, `NeurIPS, 2024`, [arxiv](http://arxiv.org/abs/2305.19466v2), [pdf](http://arxiv.org/pdf/2305.19466v2.pdf), cication: [**74**](https://scholar.google.com/scholar?cites=15655673383746969532&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Amirhossein Kazemnejad, Inkit Padhi, Karthikeyan Natesan Ramamurthy, Payel Das, Siva Reddy*
- **Augmenting Language Models with Long-Term Memory**, `arXiv, 2306.07174`, [arxiv](http://arxiv.org/abs/2306.07174v1), [pdf](http://arxiv.org/pdf/2306.07174v1.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=10032266285163330345&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Weizhi Wang, Li Dong, Hao Cheng, Xiaodong Liu, Xifeng Yan, Jianfeng Gao, Furu Wei* · ([aka](https://aka.ms/LongMem))
- **Sequence Parallelism: Long Sequence Training from System Perspective**, `arXiv, 2105.13120`, [arxiv](http://arxiv.org/abs/2105.13120v3), [pdf](http://arxiv.org/pdf/2105.13120v3.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=1387350093305756276&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shenggui Li, Fuzhao Xue, Chaitanya Baranwal, Yongbin Li, Yang You*

## Projects
- [**EasyContext**](https://github.com/jzhang38/EasyContext) - jzhang38 ![Star](https://img.shields.io/github/stars/jzhang38/EasyContext.svg?style=social&label=Star)

	 *Memory optimization and training recipes to extrapolate language models' context length to 1 million tokens, with minimal hardware.* · ([twitter](https://twitter.com/PY_Z001/status/1776176932687892796))
- [**LLMLingua**](https://github.com/microsoft/LLMLingua) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/LLMLingua.svg?style=social&label=Star)

	 *To speed up LLMs' inference and enhance LLM's perceive of key information, compress the prompt and KV-Cache, which achieves up to 20x compression with minimal performance loss.*
- [**long-context**](https://github.com/abacusai/long-context) - abacusai ![Star](https://img.shields.io/github/stars/abacusai/long-context.svg?style=social&label=Star)

	 *This repository contains code and tooling for the Abacus.AI LLM Context Expansion project. Also included are evaluation scripts and benchmark tasks that evaluate a model’s information retrieval capabilities with context expansion. We also include key experimental results and instructions for reproducing and building on them.*
- [LLaMA rope_scaling](https://huggingface.co/docs/transformers/main/en/model_doc/llama#transformers.LlamaConfig.rope_scaling)
- [**long_llama**](https://github.com/cstankonrad/long_llama) - cstankonrad ![Star](https://img.shields.io/github/stars/cstankonrad/long_llama.svg?style=social&label=Star)

	 *LongLLaMA is a large language model capable of handling long contexts. It is based on OpenLLaMA and fine-tuned with the Focused Transformer (FoT) method.*

## Other
- [A failed experiment: Infini-Attention, and why we should keep trying?](https://huggingface.co/blog/infini-attention)
- [Long Context RAG Performance of LLMs | Databricks Blog](https://www.databricks.com/blog/long-context-rag-performance-llms)

	 · ([x](https://x.com/DbrxMosaicAI/status/1823129597288046979?utm_source=ainews&utm_medium=email&utm_campaign=ainews-gemini-live))
-  [influential papers from the recent past, exploring efficient context-window increase of LLMs](https://x.com/rohanpaul_ai/status/1805382628742234179)
- [Unlocking Longer Generation with Key-Value Cache Quantization](https://huggingface.co/blog/kv-cache-quantization)
- [Unsloth - 4x longer context windows & 1.7x larger batch sizes](https://unsloth.ai/blog/long-context)
-  [a certain pattern among many attention heads](https://twitter.com/arankomatsuzaki/status/1767276661894943226)
- [How Do Language Models put Attention Weights over Long Context?](https://yaofu.notion.site/How-Do-Language-Models-put-Attention-Weights-over-Long-Context-10250219d5ce42e8b465087c383a034e)
- [gemini use case](https://twitter.com/Swarooprm7/status/1762892253234913349)
- [Understanding data influence on context scaling: a close look at baseline solution](https://yaofu.notion.site/Understanding-data-influence-on-context-scaling-a-close-look-at-baseline-solution-eb17eab795dd4132b1a1ffe73f5e850a)
- [Anthropic \\ Long context prompting for Claude 2.1](https://www.anthropic.com/index/claude-2-1-prompting)
- [The Secret Sauce behind 100K context window in LLMs: all tricks in one place | by Galina Alperovich | May, 2023 | GoPenAI](https://blog.gopenai.com/how-to-speed-up-llms-and-use-100k-context-window-all-tricks-in-one-place-ffd40577b4c)
- [Extending Context is Hard | kaiokendev.github.io](https://kaiokendev.github.io/context)

- [一句话解锁100k+上下文大模型真实力，27分涨到98，GPT-4、Claude2.1适用 | 量子位](https://www.qbitai.com/2023/12/105450.html)
- [500万token巨兽，一次读完全套「哈利波特」！比ChatGPT长1000多倍](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652338537&idx=2&sn=8aaf7f6e61ca91fd65a4d42e845f77f5)

## Extra reference