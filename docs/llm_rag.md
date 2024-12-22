# LLM Rag

- [LLM Rag](#llm-rag) 
  - [Survey](#survey)
  - [RAG](#rag)
  - [Multi Modal](#multi-modal)
  - [Embedding](#embedding)
  - [Evaluation](#evaluation)
  - [Database](#database)
  - [Projects](#projects)
  - [Products](#products)
  - [Misc](#misc)
  - [Vector Database](#vector-database)


## Survey


## RAG

- [GemmaEmbed is a dense-vector embedding model, trained especially for retrieval.](https://huggingface.co/google/Gemma-Embeddings-v1.0)  🤗
- 🌟 **Smarter, Better, Faster, Longer: A Modern Bidirectional Encoder for
  Fast, Memory Efficient, and Long Context Finetuning and Inference**, `arXiv, 2412.13663`, [arxiv](http://arxiv.org/abs/2412.13663v2), [pdf](http://arxiv.org/pdf/2412.13663v2.pdf), cication: [**-1**](None) 

	 *Benjamin Warner, Antoine Chaffin, Benjamin Clavié, ..., Jeremy Howard, Iacopo Poli* · ([huggingface](https://huggingface.co/blog/modernbert)) · ([𝕏](https://x.com/jeremyphoward/status/1869786023963832509?s=46))
- **Auto-RAG: Autonomous Retrieval-Augmented Generation for Large Language 
  Models**, `arXiv, 2411.19443`, [arxiv](http://arxiv.org/abs/2411.19443v1), [pdf](http://arxiv.org/pdf/2411.19443v1.pdf), cication: [**-1**](None) 

	 *Tian Yu, Shaolei Zhang, Yang Feng* · ([Auto-RAG](https://github.com/ictnlp/Auto-RAG) - ictnlp) ![Star](https://img.shields.io/github/stars/ictnlp/Auto-RAG.svg?style=social&label=Star)
- [NV-Embed-v2, a generalist embedding model that ranks No. 1 on the Massive Text Embedding Benchmark (MTEB benchmark)](https://huggingface.co/nvidia/NV-Embed-v2)  🤗 

	 · ([arxiv](https://arxiv.org/pdf/2405.17428))
- [Jina CLIP v2: Multilingual Multimodal Embeddings for Texts and Images](https://huggingface.co/jinaai/jina-clip-v2)  🤗 

	 · ([huggingface](https://huggingface.co/jinaai/jina-clip-v2))
- **Long Term Memory: The Foundation of AI Self-Evolution**, `arXiv, 2410.15665`, [arxiv](http://arxiv.org/abs/2410.15665v2), [pdf](http://arxiv.org/pdf/2410.15665v2.pdf), cication: [**-1**](None) 

	 *Xun Jiang, Feng Li, Han Zhao, ..., Mengdi Wang, Tianqiao Chen* · ([𝕏](https://x.com/TankaChat/status/1857272126358880267))
- [Binary vector embeddings are so cool](https://emschwartz.me/binary-vector-embeddings-are-so-cool/) 
- 🌟 **HtmlRAG: HTML is Better Than Plain Text for Modeling Retrieved Knowledge 
  in RAG Systems**, `arXiv, 2411.02959`, [arxiv](http://arxiv.org/abs/2411.02959v1), [pdf](http://arxiv.org/pdf/2411.02959v1.pdf), cication: [**-1**](None) 

	 *Jiejun Tan, Zhicheng Dou, Wen Wang, ..., Weipeng Chen, Ji-Rong Wen*
- **M3DocRAG: Multi-modal Retrieval is What You Need for Multi-page 
  Multi-document Understanding**, `arXiv, 2411.04952`, [arxiv](http://arxiv.org/abs/2411.04952v1), [pdf](http://arxiv.org/pdf/2411.04952v1.pdf), cication: [**-1**](None) 

	 *Jaemin Cho, Debanjan Mahata, Ozan Irsoy, ..., Yujie He, Mohit Bansal* · ([m3docrag.github](https://m3docrag.github.io/))
- **In Defense of RAG in the Era of Long-Context Language Models**, `arXiv, 2409.01666`, [arxiv](http://arxiv.org/abs/2409.01666v1), [pdf](http://arxiv.org/pdf/2409.01666v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=3261789221345650637&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII) 

	 *Tan Yu, Anbang Xu, Rama Akkiraju* · ([zyphra](https://www.zyphra.com/post/reaching-1b-context-length-with-rag))
- **Toward General Instruction-Following Alignment for Retrieval-Augmented 
  Generation**, `arXiv, 2410.09584`, [arxiv](http://arxiv.org/abs/2410.09584v1), [pdf](http://arxiv.org/pdf/2410.09584v1.pdf), cication: [**-1**](None)

	 *Guanting Dong, Xiaoshuai Song, Yutao Zhu, ..., Zhicheng Dou, Ji-Rong Wen* · ([FollowRAG.github](https://FollowRAG.github.io)) · ([arxiv](https://arxiv.org/pdf/2410.09584)) · ([FollowRAG](https://github.com/dongguanting/FollowRAG) - dongguanting) ![Star](https://img.shields.io/github/stars/dongguanting/FollowRAG.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/datasets/dongguanting/VIF-RAG-QA-110K))
- **Meta-Chunking: Learning Efficient Text Segmentation via Logical 
  Perception**, `arXiv, 2410.12788`, [arxiv](http://arxiv.org/abs/2410.12788v1), [pdf](http://arxiv.org/pdf/2410.12788v1.pdf), cication: [**-1**](None)

	 *Jihao Zhao, Zhiyuan Ji, Pengnian Qi, ..., Feiyu Xiong, Zhiyu Li* · ([Meta-Chunking](https://github.com/IAAR-Shanghai/Meta-Chunking) - IAAR-Shanghai) ![Star](https://img.shields.io/github/stars/IAAR-Shanghai/Meta-Chunking.svg?style=social&label=Star) · ([arxiv](https://arxiv.org/abs/2410.12788))
- **Your Mixture-of-Experts LLM Is Secretly an Embedding Model For Free**, `arXiv, 2410.10814`, [arxiv](http://arxiv.org/abs/2410.10814v2), [pdf](http://arxiv.org/pdf/2410.10814v2.pdf), cication: [**-1**](None) 

	 *Ziyue Li, Tianyi Zhou* · ([MoE-Embedding](https://github.com/tianyi-lab/MoE-Embedding) - tianyi-lab) ![Star](https://img.shields.io/github/stars/tianyi-lab/MoE-Embedding.svg?style=social&label=Star)

## Multi Modal

- [MM-Embed, an extension of NV-Embed-v1 with multimodal retrieval capability.](https://huggingface.co/nvidia/MM-Embed)  🤗 
- **Beyond Text: Optimizing RAG with Multimodal Inputs for Industrial 
  Applications**, `arXiv, 2410.21943`, [arxiv](http://arxiv.org/abs/2410.21943v1), [pdf](http://arxiv.org/pdf/2410.21943v1.pdf), cication: [**-1**](None)

	 *Monica Riedler, Stefan Langer* · ([x](https://x.com/omarsar0/status/1851479149690642456))
- **VisRAG: Vision-based Retrieval-augmented Generation on Multi-modality 
  Documents**, `arXiv, 2410.10594`, [arxiv](http://arxiv.org/abs/2410.10594v1), [pdf](http://arxiv.org/pdf/2410.10594v1.pdf), cication: [**-1**](None)

	 *Shi Yu, Chaoyue Tang, Bokai Xu, ..., Zhiyuan Liu, Maosong Sun*
- [Introducing Multimodal Embed 3: Powering AI Search](https://cohere.com/blog/multimodal-embed-3) 
- **MMed-RAG: Versatile Multimodal RAG System for Medical Vision Language 
  Models**, `arXiv, 2410.13085`, [arxiv](http://arxiv.org/abs/2410.13085v1), [pdf](http://arxiv.org/pdf/2410.13085v1.pdf), cication: [**-1**](None)

	 *Peng Xia, Kangyu Zhu, Haoran Li, ..., James Zou, Huaxiu Yao*

## Embedding


## Evaluation

- **OmniEval: An Omnidirectional and Automatic RAG Evaluation Benchmark in
  Financial Domain**, `arXiv, 2412.13018`, [arxiv](http://arxiv.org/abs/2412.13018v1), [pdf](http://arxiv.org/pdf/2412.13018v1.pdf), cication: [**-1**](None) 

	 *Shuting Wang, Jiejun Tan, Zhicheng Dou, ..., Ji-Rong Wen* · ([OmniEval](https://github.com/RUC-NLPIR/OmniEval) - RUC-NLPIR) ![Star](https://img.shields.io/github/stars/RUC-NLPIR/OmniEval.svg?style=social&label=Star)
- **Long Context RAG Performance of Large Language Models**, `arXiv, 2411.03538`, [arxiv](http://arxiv.org/abs/2411.03538v1), [pdf](http://arxiv.org/pdf/2411.03538v1.pdf), cication: [**-1**](None) 

	 *Quinn Leng, Jacob Portes, Sam Havens, ..., Matei Zaharia, Michael Carbin*
- **CORAL: Benchmarking Multi-turn Conversational Retrieval-Augmentation 
  Generation**, `arXiv, 2410.23090`, [arxiv](http://arxiv.org/abs/2410.23090v1), [pdf](http://arxiv.org/pdf/2410.23090v1.pdf), cication: [**-1**](None)

	 *Yiruo Cheng, Kelong Mao, Ziliang Zhao, ..., Ji-Rong Wen, Zhicheng Dou* · ([CORAL](https://github.com/Ariya12138/CORAL) - Ariya12138) ![Star](https://img.shields.io/github/stars/Ariya12138/CORAL.svg?style=social&label=Star)

## Database


## Projects

- [**onyx**](https://github.com/onyx-dot-app/onyx) - onyx-dot-app ![Star](https://img.shields.io/github/stars/onyx-dot-app/onyx.svg?style=social&label=Star) 
- [**fast-graphrag**](https://github.com/circlemind-ai/fast-graphrag) - circlemind-ai ![Star](https://img.shields.io/github/stars/circlemind-ai/fast-graphrag.svg?style=social&label=Star) 
- [**txtai**](https://github.com/neuml/txtai) - neuml ![Star](https://img.shields.io/github/stars/neuml/txtai.svg?style=social&label=Star) 
- [**Perplexica**](https://github.com/ItzCrazyKns/Perplexica) - ItzCrazyKns ![Star](https://img.shields.io/github/stars/ItzCrazyKns/Perplexica.svg?style=social&label=Star) 
- [**dsRAG**](https://github.com/D-Star-AI/dsRAG) - D-Star-AI ![Star](https://img.shields.io/github/stars/D-Star-AI/dsRAG.svg?style=social&label=Star) 
- 🌟 [**RAGViz**](https://github.com/cxcscmu/RAGViz) - cxcscmu ![Star](https://img.shields.io/github/stars/cxcscmu/RAGViz.svg?style=social&label=Star) 

	 · ([youtube](https://www.youtube.com/embed/cTAbuTu6ur4?si=-uZ2AyNLx-5p8MZC))
- [**pgai**](https://github.com/timescale/pgai) - timescale ![Star](https://img.shields.io/github/stars/timescale/pgai.svg?style=social&label=Star) 
- [Contextual RAG from Anthropic](https://x.com/togethercompute/status/1850939031301099919)  𝕏 

	 · ([together-cookbook](https://github.com/togethercomputer/together-cookbook/blob/main/Open_Contextual_RAG.ipynb) - togethercomputer) ![Star](https://img.shields.io/github/stars/togethercomputer/together-cookbook.svg?style=social&label=Star)
- [**AutoRAG**](https://github.com/Marker-Inc-Korea/AutoRAG) - Marker-Inc-Korea ![Star](https://img.shields.io/github/stars/Marker-Inc-Korea/AutoRAG.svg?style=social&label=Star) 
- [**KAG**](https://github.com/OpenSPG/KAG) - OpenSPG ![Star](https://img.shields.io/github/stars/OpenSPG/KAG.svg?style=social&label=Star) 

	 *Knowledge Augmented Generation*

## Products


## Misc

- [GraphRAG-esque metadata tagging + retrieval](https://x.com/jerryjliu0/status/1856768968973062620)  𝕏 

	 · ([llama_parse](https://github.com/run-llama/llama_parse/blob/main/examples/advanced_rag/dynamic_section_retrieval.ipynb) - run-llama) ![Star](https://img.shields.io/github/stars/run-llama/llama_parse.svg?style=social&label=Star)
- [What is Agentic RAG](https://weaviate.io/blog/what-is-agentic-rag) 

	 · ([𝕏](https://x.com/helloiamleonie/status/1853832634448687451))
- [Expert Support case study: Bolstering a RAG app with LLM-as-a-Judge](https://huggingface.co/blog/digital-green-llm-judge)  🤗 

## Vector Database