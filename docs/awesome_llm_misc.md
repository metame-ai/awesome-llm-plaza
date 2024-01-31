# Awesome llm misc

- [Awesome llm misc](#awesome-llm-misc)
	- [Survey](#survey)
	- [Toolkits](#toolkits)
	- [Unlearning](#unlearning)
	- [Personality](#personality)
	- [World Model](#world-model)
	- [Red teaming](#red-teaming)
	- [Chat arena](#chat-arena)
	- [New launguage model](#new-launguage-model)
	- [LLM detection](#llm-detection)
	- [Explanation](#explanation)
	- [Generaliazation](#generaliazation)
	- [LLM editting](#llm-editting)
	- [AGI insights](#agi-insights)
	- [Callibration](#callibration)
	- [Books](#books)
	- [Privacy](#privacy)
	- [Misc](#misc)
	- [Extra reference](#extra-reference)

## Survey
- **From Google Gemini to OpenAI Q* (Q-Star): A Survey of Reshaping the
  Generative Artificial Intelligence (AI) Research Landscape**, `arXiv, 2312.10868`, [arxiv](http://arxiv.org/abs/2312.10868v1), [pdf](http://arxiv.org/pdf/2312.10868v1.pdf), cication: [**-1**](None)

	 *Timothy R. McIntosh, Teo Susnjak, Tong Liu, Paul Watters, Malka N. Halgamuge*
- **A Survey of Large Language Models Attribution**, `arXiv, 2311.03731`, [arxiv](http://arxiv.org/abs/2311.03731v1), [pdf](http://arxiv.org/pdf/2311.03731v1.pdf), cication: [**-1**](None)

	 *Dongfang Li, Zetian Sun, Xinshuo Hu, Zhenyu Liu, Ziyang Chen, Baotian Hu, Aiguo Wu, Min Zhang* · ([awesome-llm-attributions](https://github.com/HITsz-TMG/awesome-llm-attributions) - HITsz-TMG) ![Star](https://img.shields.io/github/stars/HITsz-TMG/awesome-llm-attributions.svg?style=social&label=Star)
- **On the Origin of LLMs: An Evolutionary Tree and Graph for 15,821 Large
  Language Models**, `arXiv, 2307.09793`, [arxiv](http://arxiv.org/abs/2307.09793v1), [pdf](http://arxiv.org/pdf/2307.09793v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=10725945032792348366&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Sarah Gao, Andrew Kean Gao* · ([constellation.sites.stanford](https://constellation.sites.stanford.edu/))
- **A Survey of Large Language Models**, `arXiv, 2303.18223`, [arxiv](http://arxiv.org/abs/2303.18223v12), [pdf](http://arxiv.org/pdf/2303.18223v12.pdf), cication: [**285**](https://scholar.google.com/scholar?cites=4202230929734215725&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wayne Xin Zhao, Kun Zhou, Junyi Li, Tianyi Tang, Xiaolei Wang, Yupeng Hou, Yingqian Min, Beichen Zhang, Junjie Zhang, Zican Dong* · ([LLMSurvey](https://github.com/RUCAIBox/LLMSurvey) - RUCAIBox) ![Star](https://img.shields.io/github/stars/RUCAIBox/LLMSurvey.svg?style=social&label=Star)

### Blogs
- [2023, year of open LLMs](https://huggingface.co/blog/2023-in-llms)
- [Research Papers in November 2023](https://magazine.sebastianraschka.com/p/research-papers-in-november-2023)
- [AI and Open Source in 2023 - by Sebastian Raschka, PhD](https://magazine.sebastianraschka.com/p/ai-and-open-source-in-2023)
- [The History of Open-Source LLMs: Imitation and Alignment (Part Three)](https://cameronrwolfe.substack.com/p/the-history-of-open-source-llms-imitation)
- [Research Papers (October 2023) - by Sebastian Raschka, PhD](https://magazine.sebastianraschka.com/p/research-papers-october-2023)
- [A Survey of Techniques for Maximizing LLM Performance](https://www.youtube.com/watch?v=ahnGLM-RC1Y&ab_channel=OpenAI)
- [Transformer Taxonomy (the last lit review) | kipply's blog](https://kipp.ly/transformer-taxonomy/?continueFlag=a897a8d0eb16dcae5398f1b58cc5e06f)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-14-9))
- [Catching up on the weird world of LLMs](https://simonwillison.net/2023/Aug/3/weird-world-of-llms/)

## Toolkits
- [**amazing-openai-api**](https://github.com/soulteary/amazing-openai-api) - soulteary ![Star](https://img.shields.io/github/stars/soulteary/amazing-openai-api.svg?style=social&label=Star)

	 *Convert different model APIs into the OpenAI API format out of the box.*
- [**jan**](https://github.com/janhq/jan) - janhq ![Star](https://img.shields.io/github/stars/janhq/jan.svg?style=social&label=Star)

	 *Jan is an open source alternative to ChatGPT that runs 100% offline on your computer*
- [**GPT_API_free**](https://github.com/chatanywhere/GPT_API_free) - chatanywhere ![Star](https://img.shields.io/github/stars/chatanywhere/GPT_API_free.svg?style=social&label=Star)

	 *Free ChatGPT API Key，免费ChatGPT API，支持GPT4 API（免费），ChatGPT国内可用免费转发API，直连无需代理。可以搭配ChatBox等软件/插件使用，极大降低接口使用成本。国内即可无限制畅快聊天。*
- [**BricksLLM**](https://github.com/bricks-cloud/BricksLLM) - bricks-cloud ![Star](https://img.shields.io/github/stars/bricks-cloud/BricksLLM.svg?style=social&label=Star)

	 *Simplifying LLM ops in production*
- [**skypilot**](https://github.com/skypilot-org/skypilot) - skypilot-org ![Star](https://img.shields.io/github/stars/skypilot-org/skypilot.svg?style=social&label=Star)

	 *SkyPilot: Run LLMs, AI, and Batch jobs on any cloud. Get maximum savings, highest GPU availability, and managed execution—all with a simple interface.*
- [**vllm**](https://github.com/vllm-project/vllm) - vllm-project ![Star](https://img.shields.io/github/stars/vllm-project/vllm.svg?style=social&label=Star)

	 *A high-throughput and memory-efficient inference and serving engine for LLMs*
- [**langflow**](https://github.com/logspace-ai/langflow) - logspace-ai ![Star](https://img.shields.io/github/stars/logspace-ai/langflow.svg?style=social&label=Star)

	 *⛓️ LangFlow is a UI for LangChain, designed with react-flow to provide an effortless way to experiment and prototype flows.*
- [**torchscale**](https://github.com/microsoft/torchscale) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/torchscale.svg?style=social&label=Star)

	 *Foundation Architecture for (M)LLMs*
- [**LLM-As-Chatbot**](https://github.com/deep-diver/LLM-As-Chatbot) - deep-diver ![Star](https://img.shields.io/github/stars/deep-diver/LLM-As-Chatbot.svg?style=social&label=Star)

	 *LLM as a Chatbot Service*
- [**Llama-2-Open-Source-LLM-CPU-Inference**](https://github.com/kennethleungty/Llama-2-Open-Source-LLM-CPU-Inference) - kennethleungty ![Star](https://img.shields.io/github/stars/kennethleungty/Llama-2-Open-Source-LLM-CPU-Inference.svg?style=social&label=Star)

	 *Running Llama 2 and other Open-Source LLMs on CPU Inference Locally for Document Q&A*
- [**ollama**](https://github.com/jmorganca/ollama) - jmorganca ![Star](https://img.shields.io/github/stars/jmorganca/ollama.svg?style=social&label=Star)

	 *Get up and running with large language models locally*
- [**OpenLLM**](https://github.com/bentoml/OpenLLM) - bentoml ![Star](https://img.shields.io/github/stars/bentoml/OpenLLM.svg?style=social&label=Star)

	 *An open platform for operating large language models (LLMs) in production. Fine-tune, serve, deploy, and monitor any LLMs with ease.*
- [**litellm**](https://github.com/BerriAI/litellm) - BerriAI ![Star](https://img.shields.io/github/stars/BerriAI/litellm.svg?style=social&label=Star)

	 *Call all LLM APIs using the OpenAI format. Use Bedrock, Azure, OpenAI, Cohere, Anthropic, Ollama, Sagemaker, HuggingFace, Replicate (100+ LLMs)*
- [**ollama**](https://github.com/jmorganca/ollama) - jmorganca ![Star](https://img.shields.io/github/stars/jmorganca/ollama.svg?style=social&label=Star)

	 *Get up and running with Llama 2 and other large language models locally*
- [**gpu_poor**](https://github.com/RahulSChand/gpu_poor) - RahulSChand ![Star](https://img.shields.io/github/stars/RahulSChand/gpu_poor.svg?style=social&label=Star)

	 *Calculate GPU memory requirement & breakdown for training/inference of LLM models. Supports ggml/bnb quantization*
- [**leptonai**](https://github.com/leptonai/leptonai) - leptonai ![Star](https://img.shields.io/github/stars/leptonai/leptonai.svg?style=social&label=Star)

	 *A Pythonic framework to simplify AI service building*
- [**exllamav2**](https://github.com/turboderp/exllamav2) - turboderp ![Star](https://img.shields.io/github/stars/turboderp/exllamav2.svg?style=social&label=Star)

	 *A fast inference library for running LLMs locally on modern consumer-class GPUs*
- [**outlines**](https://github.com/normal-computing/outlines) - normal-computing ![Star](https://img.shields.io/github/stars/normal-computing/outlines.svg?style=social&label=Star)

	 *Generative Model Programming*
- [**one-api**](https://github.com/songquanpeng/one-api) - songquanpeng ![Star](https://img.shields.io/github/stars/songquanpeng/one-api.svg?style=social&label=Star)

	 *OpenAI 接口管理 & 分发系统，支持 Azure、Anthropic Claude、Google PaLM 2、智谱 ChatGLM、百度文心一言、讯飞星火认知以及阿里通义千问，可用于二次分发管理 key，仅单可执行文件，已打包好 Docker 镜像，一键部署，开箱即用. OpenAI key management & redistribution system, using a single API for all LLMs, and features an English UI.*
- [**LLaMA2-Accessory**](https://github.com/Alpha-VLLM/LLaMA2-Accessory) - Alpha-VLLM ![Star](https://img.shields.io/github/stars/Alpha-VLLM/LLaMA2-Accessory.svg?style=social&label=Star)

	 *An Open-source Toolkit for LLM Development*
- [**Flowise**](https://github.com/FlowiseAI/Flowise) - FlowiseAI ![Star](https://img.shields.io/github/stars/FlowiseAI/Flowise.svg?style=social&label=Star)

	 *Drag & drop UI to build your customized LLM flow*
- [**simpleaichat**](https://github.com/minimaxir/simpleaichat) - minimaxir ![Star](https://img.shields.io/github/stars/minimaxir/simpleaichat.svg?style=social&label=Star)

	 *Python package for easily interfacing with chat apps, with robust features and minimal code complexity.*
- [**TypeChat**](https://github.com/Microsoft/TypeChat) - Microsoft ![Star](https://img.shields.io/github/stars/Microsoft/TypeChat.svg?style=social&label=Star)

	 *TypeChat is a library that makes it easy to build natural language interfaces using types.*
- [**petals**](https://github.com/bigscience-workshop/petals) - bigscience-workshop ![Star](https://img.shields.io/github/stars/bigscience-workshop/petals.svg?style=social&label=Star)

	 *🌸 Run large language models at home, BitTorrent-style. Fine-tuning and inference up to 10x faster than offloading*
- [**chatbox**](https://github.com/Bin-Huang/chatbox) - Bin-Huang ![Star](https://img.shields.io/github/stars/Bin-Huang/chatbox.svg?style=social&label=Star)

	 *Chatbox is a desktop app for GPT/LLM that supports Windows, Mac, Linux & Web Online*
- [**h2o-llmstudio**](https://github.com/h2oai/h2o-llmstudio) - h2oai ![Star](https://img.shields.io/github/stars/h2oai/h2o-llmstudio.svg?style=social&label=Star)

	 *H2O LLM Studio - a framework and no-code GUI for fine-tuning LLMs*
- [**LMFlow**](https://github.com/OptimalScale/LMFlow) - OptimalScale ![Star](https://img.shields.io/github/stars/OptimalScale/LMFlow.svg?style=social&label=Star)

	 *An Extensible Toolkit for Finetuning and Inference of Large Foundation Models. Large Model for All.*
- [**FlagAI**](https://github.com/FlagAI-Open/FlagAI) - FlagAI-Open ![Star](https://img.shields.io/github/stars/FlagAI-Open/FlagAI.svg?style=social&label=Star)

	 *FlagAI (Fast LArge-scale General AI models) is a fast, easy-to-use and extensible toolkit for large-scale model.*

## Unlearning
- **TOFU: A Task of Fictitious Unlearning for LLMs**, `arXiv, 2401.06121`, [arxiv](http://arxiv.org/abs/2401.06121v1), [pdf](http://arxiv.org/pdf/2401.06121v1.pdf), cication: [**-1**](None)

	 *Pratyush Maini, Zhili Feng, Avi Schwarzschild, Zachary C. Lipton, J. Zico Kolter*
- **Large Language Model Unlearning**, `arXiv, 2310.10683`, [arxiv](http://arxiv.org/abs/2310.10683v1), [pdf](http://arxiv.org/pdf/2310.10683v1.pdf), cication: [**-1**](None)

	 *Yuanshun Yao, Xiaojun Xu, Yang Liu*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-12-13-6)) · ([llm_unlearn](https://github.com/kevinyaobytedance/llm_unlearn) - kevinyaobytedance) ![Star](https://img.shields.io/github/stars/kevinyaobytedance/llm_unlearn.svg?style=social&label=Star)
- **Improving Language Plasticity via Pretraining with Active Forgetting**, `arXiv, 2307.01163`, [arxiv](http://arxiv.org/abs/2307.01163v2), [pdf](http://arxiv.org/pdf/2307.01163v2.pdf), cication: [**-1**](None)

	 *Yihong Chen, Kelly Marchisio, Roberta Raileanu, David Ifeoluwa Adelani, Pontus Stenetorp, Sebastian Riedel, Mikel Artetxe*
- [Announcing the first Machine Unlearning Challenge – Google Research Blog](https://ai.googleblog.com/2023/06/announcing-first-machine-unlearning.html)

## Personality
- **Large Language Models Understand and Can be Enhanced by Emotional
  Stimuli**, `arXiv, 2307.11760`, [arxiv](http://arxiv.org/abs/2307.11760v7), [pdf](http://arxiv.org/pdf/2307.11760v7.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=5825846437972489885&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Cheng Li, Jindong Wang, Yixuan Zhang, Kaijie Zhu, Wenxin Hou, Jianxun Lian, Fang Luo, Qiang Yang, Xing Xie*
- **When Large Language Models Meet Personalization: Perspectives of
  Challenges and Opportunities**, `arXiv, 2307.16376`, [arxiv](http://arxiv.org/abs/2307.16376v1), [pdf](http://arxiv.org/pdf/2307.16376v1.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=801122460433394373&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jin Chen, Zheng Liu, Xu Huang, Chenwang Wu, Qi Liu, Gangwei Jiang, Yuanhao Pu, Yuxuan Lei, Xiaolong Chen, Xingmei Wang*
- **Personality Traits in Large Language Models**, `arXiv, 2307.00184`, [arxiv](http://arxiv.org/abs/2307.00184v3), [pdf](http://arxiv.org/pdf/2307.00184v3.pdf), cication: [**17**](https://scholar.google.com/scholar?cites=3059704921021154305&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Greg Serapio-García, Mustafa Safdari, Clément Crepy, Luning Sun, Stephen Fitz, Peter Romero, Marwa Abdulhai, Aleksandra Faust, Maja Matarić*

## World Model
- **The Geometry of Truth: Emergent Linear Structure in Large Language Model
  Representations of True/False Datasets**, `arXiv, 2310.06824`, [arxiv](http://arxiv.org/abs/2310.06824v1), [pdf](http://arxiv.org/pdf/2310.06824v1.pdf), cication: [**-1**](None)

	 *Samuel Marks, Max Tegmark* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652393580&idx=2&sn=31bcdd233c49fb79e78d06045df491dc))
- **Language Models Represent Space and Time**, `arXiv, 2310.02207`, [arxiv](http://arxiv.org/abs/2310.02207v1), [pdf](http://arxiv.org/pdf/2310.02207v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=2674847876149703750&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wes Gurnee, Max Tegmark* · ([world-models](https://github.com/wesg52/world-models) - wesg52) ![Star](https://img.shields.io/github/stars/wesg52/world-models.svg?style=social&label=Star)
- [How far are we from AGI?](https://aisupremacy.substack.com/p/how-far-are-we-from-agi)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652366759&idx=2&sn=48422d1a7ffae891ea61108761f4d582))

- [OpenAI「登月计划」剑指超级AI！LeCun提出AGI之路七阶段，打造世界模型是首位](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652419855&idx=3&sn=a5f20e0a0061c01e1ec87d4a81c23e68)[https://mp.weixin.qq.com/s?\_\_biz=MzI3MTA0MTk1MA==&mid=2652419855&idx=3&sn=a5f20e0a0061c01e1ec87d4a81c23e68](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652419855&idx=3&sn=a5f20e0a0061c01e1ec87d4a81c23e68)
## Red teaming (safety)
- **MART: Improving LLM Safety with Multi-round Automatic Red-Teaming**, `arXiv, 2311.07689`, [arxiv](http://arxiv.org/abs/2311.07689v1), [pdf](http://arxiv.org/pdf/2311.07689v1.pdf), cication: [**-1**](None)

	 *Suyu Ge, Chunting Zhou, Rui Hou, Madian Khabsa, Yi-Chia Wang, Qifan Wang, Jiawei Han, Yuning Mao*
- **Moral Foundations of Large Language Models**, `arXiv, 2310.15337`, [arxiv](http://arxiv.org/abs/2310.15337v1), [pdf](http://arxiv.org/pdf/2310.15337v1.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=2033876937451648547&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Marwa Abdulhai, Gregory Serapio-Garcia, Clément Crepy, Daria Valter, John Canny, Natasha Jaques*
- **FLIRT: Feedback Loop In-context Red Teaming**, `arXiv, 2308.04265`, [arxiv](http://arxiv.org/abs/2308.04265v1), [pdf](http://arxiv.org/pdf/2308.04265v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=3679628265599247085&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ninareh Mehrabi, Palash Goyal, Christophe Dupuy, Qian Hu, Shalini Ghosh, Richard Zemel, Kai-Wei Chang, Aram Galstyan, Rahul Gupta*
- **Explore, Establish, Exploit: Red Teaming Language Models from Scratch**, `arXiv, 2306.09442`, [arxiv](http://arxiv.org/abs/2306.09442v3), [pdf](http://arxiv.org/pdf/2306.09442v3.pdf), cication: [**16**](https://scholar.google.com/scholar?cites=17596552078024127407&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Stephen Casper, Jason Lin, Joe Kwon, Gatlen Culp, Dylan Hadfield-Menell*

## Chat arena
- [**GodMode**](https://github.com/smol-ai/GodMode) - smol-ai ![Star](https://img.shields.io/github/stars/smol-ai/GodMode.svg?style=social&label=Star)

	 *AI Chat Browser: Fast, Full webapp access to ChatGPT / Claude / Bard / Bing / Llama2! I use this 20 times a day.*
- [**ChatALL**](https://github.com/sunner/ChatALL) - sunner ![Star](https://img.shields.io/github/stars/sunner/ChatALL.svg?style=social&label=Star)

	 *Concurrently chat with ChatGPT, Bing Chat, Bard, Alpaca, Vicuna, Claude, ChatGLM, MOSS, 讯飞星火, 文心一言 and more, discover the best answers*

## New model
- **Transfer Learning for Text Diffusion Models**, `arXiv, 2401.17181`, [arxiv](http://arxiv.org/abs/2401.17181v1), [pdf](http://arxiv.org/pdf/2401.17181v1.pdf), cication: [**-1**](None)

	 *Kehang Han, Kathleen Kenealy, Aditya Barua, Noah Fiedel, Noah Constant*
- [🦅 Eagle 7B : Soaring past Transformers with 1 Trillion Tokens Across 100+ Languages (RWKV-v5)](https://blog.rwkv.com/p/eagle-7b-soaring-past-transformers)
- **MambaByte: Token-free Selective State Space Model**, `arXiv, 2401.13660`, [arxiv](http://arxiv.org/abs/2401.13660v1), [pdf](http://arxiv.org/pdf/2401.13660v1.pdf), cication: [**-1**](None)

	 *Junxiong Wang, Tushaar Gangavarapu, Jing Nathan Yan, Alexander M Rush*
- **MoE-Mamba: Efficient Selective State Space Models with Mixture of
  Experts**, `arXiv, 2401.04081`, [arxiv](http://arxiv.org/abs/2401.04081v1), [pdf](http://arxiv.org/pdf/2401.04081v1.pdf), cication: [**-1**](None)

	 *Maciej Pióro, Kamil Ciebiera, Krystian Król, Jan Ludziejewski, Sebastian Jaszczur*
- [The Annotated S4](https://srush.github.io/annotated-s4/)
- [Paving the way to efficient architectures: StripedHyena-7B, open source models offering a glimpse into a world beyond Transformers](https://www.together.ai/blog/stripedhyena-7b)
- **Mamba: Linear-Time Sequence Modeling with Selective State Spaces**, `arXiv, 2312.00752`, [arxiv](http://arxiv.org/abs/2312.00752v1), [pdf](http://arxiv.org/pdf/2312.00752v1.pdf), cication: [**-1**](None)

	 *Albert Gu, Tri Dao* · ([mamba](https://github.com/state-spaces/mamba) - state-spaces) ![Star](https://img.shields.io/github/stars/state-spaces/mamba.svg?style=social&label=Star)
- **TCNCA: Temporal Convolution Network with Chunked Attention for Scalable
  Sequence Processing**, `arXiv, 2312.05605`, [arxiv](http://arxiv.org/abs/2312.05605v1), [pdf](http://arxiv.org/pdf/2312.05605v1.pdf), cication: [**-1**](None)

	 *Aleksandar Terzic, Michael Hersche, Geethan Karunaratne, Luca Benini, Abu Sebastian, Abbas Rahimi*
- **GIVT: Generative Infinite-Vocabulary Transformers**, `arXiv, 2312.02116`, [arxiv](http://arxiv.org/abs/2312.02116v1), [pdf](http://arxiv.org/pdf/2312.02116v1.pdf), cication: [**-1**](None)

	 *Michael Tschannen, Cian Eastwood, Fabian Mentzer*
- **Text Rendering Strategies for Pixel Language Models**, `arXiv, 2311.00522`, [arxiv](http://arxiv.org/abs/2311.00522v1), [pdf](http://arxiv.org/pdf/2311.00522v1.pdf), cication: [**-1**](None)

	 *Jonas F. Lotz, Elizabeth Salesky, Phillip Rust, Desmond Elliott*
- **Retentive Network: A Successor to Transformer for Large Language Models**, `arXiv, 2307.08621`, [arxiv](http://arxiv.org/abs/2307.08621v4), [pdf](http://arxiv.org/pdf/2307.08621v4.pdf), cication: [**14**](https://scholar.google.com/scholar?cites=14499954689213944503&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yutao Sun, Li Dong, Shaohan Huang, Shuming Ma, Yuqing Xia, Jilong Xue, Jianyong Wang, Furu Wei*
- **Copy Is All You Need**, `arXiv, 2307.06962`, [arxiv](http://arxiv.org/abs/2307.06962v1), [pdf](http://arxiv.org/pdf/2307.06962v1.pdf), cication: [**217**](https://scholar.google.com/scholar?cites=15114021291138625040&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tian Lan, Deng Cai, Yan Wang, Heyan Huang, Xian-Ling Mao*
- **BiPhone: Modeling Inter Language Phonetic Influences in Text**, `arXiv, 2307.03322`, [arxiv](http://arxiv.org/abs/2307.03322v1), [pdf](http://arxiv.org/pdf/2307.03322v1.pdf), cication: [**-1**](None)

	 *Abhirut Gupta, Ananya B. Sai, Richard Sproat, Yuri Vasilevski, James S. Ren, Ambarish Jash, Sukhdeep S. Sodhi, Aravindan Raghuveer*
- **Deep Language Networks: Joint Prompt Training of Stacked LLMs using
  Variational Inference**, `arXiv, 2306.12509`, [arxiv](http://arxiv.org/abs/2306.12509v1), [pdf](http://arxiv.org/pdf/2306.12509v1.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=14503894489688541656&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Alessandro Sordoni, Xingdi Yuan, Marc-Alexandre Côté, Matheus Pereira, Adam Trischler, Ziang Xiao, Arian Hosseini, Friederike Niedtner, Nicolas Le Roux*
- **Backpack Language Models**, `arXiv, 2305.16765`, [arxiv](http://arxiv.org/abs/2305.16765v1), [pdf](http://arxiv.org/pdf/2305.16765v1.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=6150502937498838062&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *John Hewitt, John Thickstun, Christopher D. Manning, Percy Liang* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-25-5)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247608689&idx=2&sn=ed29c1ee1f571f98b191805472feb79a))

## LLM detection
- [**LLM-generated-text-detection**](https://github.com/thunlp/LLM-generated-text-detection) - thunlp ![Star](https://img.shields.io/github/stars/thunlp/LLM-generated-text-detection.svg?style=social&label=Star)
- **Adaptive Text Watermark for Large Language Models**, `arXiv, 2401.13927`, [arxiv](http://arxiv.org/abs/2401.13927v1), [pdf](http://arxiv.org/pdf/2401.13927v1.pdf), cication: [**-1**](None)

	 *Yepeng Liu, Yuheng Bu*
- **Spotting LLMs With Binoculars: Zero-Shot Detection of Machine-Generated
  Text**, `arXiv, 2401.12070`, [arxiv](http://arxiv.org/abs/2401.12070v1), [pdf](http://arxiv.org/pdf/2401.12070v1.pdf), cication: [**-1**](None)

	 *Abhimanyu Hans, Avi Schwarzschild, Valeriia Cherepanova, Hamid Kazemi, Aniruddha Saha, Micah Goldblum, Jonas Geiping, Tom Goldstein*
- **LLM-as-a-Coauthor: The Challenges of Detecting LLM-Human Mixcase**, `arXiv, 2401.05952`, [arxiv](http://arxiv.org/abs/2401.05952v1), [pdf](http://arxiv.org/pdf/2401.05952v1.pdf), cication: [**-1**](None)

	 *Chujie Gao, Dongping Chen, Qihui Zhang, Yue Huang, Yao Wan, Lichao Sun* · ([MixSet](https://github.com/Dongping-Chen/MixSet) - Dongping-Chen) ![Star](https://img.shields.io/github/stars/Dongping-Chen/MixSet.svg?style=social&label=Star)
- **A Survey of Text Watermarking in the Era of Large Language Models**, `arXiv, 2312.07913`, [arxiv](http://arxiv.org/abs/2312.07913v4), [pdf](http://arxiv.org/pdf/2312.07913v4.pdf), cication: [**-1**](None)

	 *Aiwei Liu, Leyi Pan, Yijian Lu, Jingjing Li, Xuming Hu, Xi Zhang, Lijie Wen, Irwin King, Hui Xiong, Philip S. Yu* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-01-26))
- **Ghostbuster: Detecting Text Ghostwritten by Large Language Models**, `arXiv, 2305.15047`, [arxiv](http://arxiv.org/abs/2305.15047v2), [pdf](http://arxiv.org/pdf/2305.15047v2.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=13263500511172823777&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Vivek Verma, Eve Fleisig, Nicholas Tomlin, Dan Klein* · ([bair.berkeley](https://bair.berkeley.edu/blog/2023/11/14/ghostbuster/))
- [‘ChatGPT detector’ catches AI-generated papers with unprecedented accuracy](https://www.nature.com/articles/d41586-023-03479-4)
- **GPT detectors are biased against non-native English writers**, `arXiv, 2304.02819`, [arxiv](http://arxiv.org/abs/2304.02819v3), [pdf](http://arxiv.org/pdf/2304.02819v3.pdf), cication: [**42**](https://scholar.google.com/scholar?cites=517481798147034142&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Weixin Liang, Mert Yuksekgonul, Yining Mao, Eric Wu, James Zou*
- **Three Bricks to Consolidate Watermarks for Large Language Models**, `arXiv, 2308.00113`, [arxiv](http://arxiv.org/abs/2308.00113v2), [pdf](http://arxiv.org/pdf/2308.00113v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=10192059197680159637&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Pierre Fernandez, Antoine Chaffin, Karim Tit, Vivien Chappelier, Teddy Furon*
- **Robust Distortion-free Watermarks for Language Models**, `arXiv, 2307.15593`, [arxiv](http://arxiv.org/abs/2307.15593v2), [pdf](http://arxiv.org/pdf/2307.15593v2.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=8195690178514933158&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Rohith Kuditipudi, John Thickstun, Tatsunori Hashimoto, Percy Liang*
- **Can AI-Generated Text be Reliably Detected?**, `arXiv, 2303.11156`, [arxiv](http://arxiv.org/abs/2303.11156v2), [pdf](http://arxiv.org/pdf/2303.11156v2.pdf), cication: [**93**](https://scholar.google.com/scholar?cites=6956709800612024780&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Vinu Sankar Sadasivan, Aounon Kumar, Sriram Balasubramanian, Wenxiao Wang, Soheil Feizi* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652358133&idx=4&sn=79515be33a6c66221480408134193581))
- [Digital tool spots academic text spawned by ChatGPT with 99% accuracy | The University of Kansas](http://today.ku.edu/2023/05/19/digital-tool-spots-academic-text-spawned-chatgpt-99-percent-accuracy)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652345558&idx=4&sn=95686435d5cad05d44cbe02bc26d6859))

## Interpretability 
- [Circuits Updates - January 2024](https://transformer-circuits.pub/2024/jan-update/index.html)
- **Patchscope: A Unifying Framework for Inspecting Hidden Representations
  of Language Models**, `arXiv, 2401.06102`, [arxiv](http://arxiv.org/abs/2401.06102v1), [pdf](http://arxiv.org/pdf/2401.06102v1.pdf), cication: [**-1**](None)

	 *Asma Ghandeharioun, Avi Caciularu, Adam Pearce, Lucas Dixon, Mor Geva*
- [Vayu Robotics Blog - Interpretable End-to-End Robot Navigation](https://www.vayurobotics.com/blog/interpretable-end-to-end-driving-agent-for-robotic-mobility)
- [Fact Finding: Attempting to Reverse-Engineer Factual Recall on the Neuron Level (Post 1) — AI Alignment Forum](https://www.alignmentforum.org/s/hpWHhjvjn67LJ4xXX/p/iGuwZTHWb6DFY3sKB)
- [deep learning does approximate Solomonoff induction](https://twitter.com/johnschulman2/status/1741178475946602979)
- [**awesome-llm-interpretability**](https://github.com/JShollaj/awesome-llm-interpretability) - JShollaj ![Star](https://img.shields.io/github/stars/JShollaj/awesome-llm-interpretability.svg?style=social&label=Star)

	 *A curated list of Large Language Model (LLM) Interpretability resources.*

- [Site Unreachable](https://windowsontheory.org/2023/12/22/emergent-abilities-and-grokking-fundamental-mirage-or-both/)
- **Challenges with unsupervised LLM knowledge discovery**, `arXiv, 2312.10029`, [arxiv](http://arxiv.org/abs/2312.10029v1), [pdf](http://arxiv.org/pdf/2312.10029v1.pdf), cication: [**-1**](None)

	 *Sebastian Farquhar, Vikrant Varma, Zachary Kenton, Johannes Gasteiger, Vladimir Mikulik, Rohin Shah*
- **Using Captum to Explain Generative Language Models**, `arXiv, 2312.05491`, [arxiv](http://arxiv.org/abs/2312.05491v1), [pdf](http://arxiv.org/pdf/2312.05491v1.pdf), cication: [**-1**](None)

	 *Vivek Miglani, Aobo Yang, Aram H. Markosyan, Diego Garcia-Olano, Narine Kokhlikyan*
- **Beyond Surface: Probing LLaMA Across Scales and Layers**, `arXiv, 2312.04333`, [arxiv](http://arxiv.org/abs/2312.04333v1), [pdf](http://arxiv.org/pdf/2312.04333v1.pdf), cication: [**-1**](None)

	 *Nuo Chen, Ning Wu, Shining Liang, Ming Gong, Linjun Shou, Dongmei Zhang, Jia Li*
- [**llm-viz**](https://github.com/bbycroft/llm-viz) - bbycroft ![Star](https://img.shields.io/github/stars/bbycroft/llm-viz.svg?style=social&label=Star)

	 *3D Visualization of an GPT-style LLM*
- **White-Box Transformers via Sparse Rate Reduction: Compression Is All
  There Is?**, `arXiv, 2311.13110`, [arxiv](http://arxiv.org/abs/2311.13110v2), [pdf](http://arxiv.org/pdf/2311.13110v2.pdf), cication: [**-1**](None)

	 *Yaodong Yu, Sam Buchanan, Druv Pai, Tianzhe Chu, Ziyang Wu, Shengbang Tong, Hao Bai, Yuexiang Zhai, Benjamin D. Haeffele, Yi Ma* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652411597&idx=1&sn=a110c3008a6725d424c9baff337cdb16&poc_token=HEt8Y2WjW94eS5ngCe9T1PO8B0ABkk44PoUjOvZj))
- **Pretraining Data Mixtures Enable Narrow Model Selection Capabilities in
  Transformer Models**, `arXiv, 2311.00871`, [arxiv](http://arxiv.org/abs/2311.00871v1), [pdf](http://arxiv.org/pdf/2311.00871v1.pdf), cication: [**-1**](None)

	 *Steve Yadlowsky, Lyric Doshi, Nilesh Tripuraneni* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-07-6))
- **The Generative AI Paradox: "What It Can Create, It May Not Understand"**, `arXiv, 2311.00059`, [arxiv](http://arxiv.org/abs/2311.00059v1), [pdf](http://arxiv.org/pdf/2311.00059v1.pdf), cication: [**-1**](None)

	 *Peter West, Ximing Lu, Nouha Dziri, Faeze Brahman, Linjie Li, Jena D. Hwang, Liwei Jiang, Jillian Fisher, Abhilasha Ravichander, Khyathi Chandu*
- **The Impact of Depth and Width on Transformer Language Model
  Generalization**, `arXiv, 2310.19956`, [arxiv](http://arxiv.org/abs/2310.19956v1), [pdf](http://arxiv.org/pdf/2310.19956v1.pdf), cication: [**-1**](None)

	 *Jackson Petty, Sjoerd van Steenkiste, Ishita Dasgupta, Fei Sha, Dan Garrette, Tal Linzen*
- **Can Large Language Models Explain Themselves? A Study of LLM-Generated
  Self-Explanations**, `arXiv, 2310.11207`, [arxiv](http://arxiv.org/abs/2310.11207v1), [pdf](http://arxiv.org/pdf/2310.11207v1.pdf), cication: [**-1**](None)

	 *Shiyuan Huang, Siddarth Mamidanna, Shreedhar Jangam, Yilun Zhou, Leilani H. Gilpin*
- [Towards Monosemanticity: Decomposing Language Models With Dictionary Learning](https://transformer-circuits.pub/2023/monosemantic-features/index.html)

	 · ([qbitai](https://www.qbitai.com/2023/10/87969.html))
- **Representation Engineering: A Top-Down Approach to AI Transparency**, `arXiv, 2310.01405`, [arxiv](http://arxiv.org/abs/2310.01405v3), [pdf](http://arxiv.org/pdf/2310.01405v3.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=7486178775253953945&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Andy Zou, Long Phan, Sarah Chen, James Campbell, Phillip Guo, Richard Ren, Alexander Pan, Xuwang Yin, Mantas Mazeika, Ann-Kathrin Dombrowski* · ([representation-engineering](https://github.com/andyzoujm/representation-engineering) - andyzoujm) ![Star](https://img.shields.io/github/stars/andyzoujm/representation-engineering.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652386851&idx=1&sn=0c828b9880d272e367c5810f82120bdc))
- **Attention Satisfies: A Constraint-Satisfaction Lens on Factual Errors of
  Language Models**, `arXiv, 2309.15098`, [arxiv](http://arxiv.org/abs/2309.15098v1), [pdf](http://arxiv.org/pdf/2309.15098v1.pdf), cication: [**-1**](None)

	 *Mert Yuksekgonul, Varun Chandrasekaran, Erik Jones, Suriya Gunasekar, Ranjita Naik, Hamid Palangi, Ece Kamar, Besmira Nushi*
- **Language Modeling Is Compression**, `arXiv, 2309.10668`, [arxiv](http://arxiv.org/abs/2309.10668v1), [pdf](http://arxiv.org/pdf/2309.10668v1.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=8098408536892148709&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Grégoire Delétang, Anian Ruoss, Paul-Ambroise Duquenne, Elliot Catt, Tim Genewein, Christopher Mattern, Jordi Grau-Moya, Li Kevin Wenliang, Matthew Aitchison, Laurent Orseau*
- **Sorted LLaMA: Unlocking the Potential of Intermediate Layers of Large
  Language Models for Dynamic Inference Using Sorted Fine-Tuning (SoFT)**, `arXiv, 2309.08968`, [arxiv](http://arxiv.org/abs/2309.08968v1), [pdf](http://arxiv.org/pdf/2309.08968v1.pdf), cication: [**-1**](None)

	 *Parsa Kavehzadeh, Mojtaba Valipour, Marzieh Tahaei, Ali Ghodsi, Boxing Chen, Mehdi Rezagholizadeh*
- **Sparse Autoencoders Find Highly Interpretable Features in Language
  Models**, `arXiv, 2309.08600`, [arxiv](http://arxiv.org/abs/2309.08600v3), [pdf](http://arxiv.org/pdf/2309.08600v3.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=3171773312943220036&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hoagy Cunningham, Aidan Ewart, Logan Riggs, Robert Huben, Lee Sharkey*
- [Human Language Understanding & Reasoning](https://direct.mit.edu/daed/article/151/2/127/110621/Human-Language-Understanding-amp-Reasoning)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652372005&idx=2&sn=9d5025db51ff939bf39e8cf861938a34))
- [Do Machine Learning Models Memorize or Generalize?](https://pair.withgoogle.com/explorables/grokking/)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652371869&idx=5&sn=e05c029912da214a6592d9e5f2418aa9))
- [**CIMI**](https://github.com/Daftstone/CIMI) - Daftstone ![Star](https://img.shields.io/github/stars/Daftstone/CIMI.svg?style=social&label=Star)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-11-5))
- [Do Machine Learning Models Memorize or Generalize?](https://pair.withgoogle.com/explorables/grokking/)

	 · ([qbitai](https://www.qbitai.com/2023/08/76083.html))
- **Studying Large Language Model Generalization with Influence Functions**, `arXiv, 2308.03296`, [arxiv](http://arxiv.org/abs/2308.03296v1), [pdf](http://arxiv.org/pdf/2308.03296v1.pdf), cication: [**12**](https://scholar.google.com/scholar?cites=4154155767169928682&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Roger Grosse, Juhan Bae, Cem Anil, Nelson Elhage, Alex Tamkin, Amirhossein Tajdini, Benoit Steiner, Dustin Li, Esin Durmus, Ethan Perez*
- [Can foundation models label data like humans?](https://huggingface.co/blog/llm-leaderboard)
- **Scan and Snap: Understanding Training Dynamics and Token Composition in
  1-layer Transformer**, `arXiv, 2305.16380`, [arxiv](http://arxiv.org/abs/2305.16380v4), [pdf](http://arxiv.org/pdf/2305.16380v4.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=10559864520549789725&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuandong Tian, Yiping Wang, Beidi Chen, Simon Du* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652339033&idx=3&sn=7c45e1f38e8ce0bd91869ac2a47078fa))
- **Label Words are Anchors: An Information Flow Perspective for
  Understanding In-Context Learning**, `arXiv, 2305.14160`, [arxiv](http://arxiv.org/abs/2305.14160v2), [pdf](http://arxiv.org/pdf/2305.14160v2.pdf), cication: [**-1**](None)

	 *Lean Wang, Lei Li, Damai Dai, Deli Chen, Hao Zhou, Fandong Meng, Jie Zhou, Xu Sun* · ([qbitai](https://www.qbitai.com/2023/12/105631.html))

## Generaliazation
- **Time is Encoded in the Weights of Finetuned Language Models**, `arXiv, 2312.13401`, [arxiv](http://arxiv.org/abs/2312.13401v1), [pdf](http://arxiv.org/pdf/2312.13401v1.pdf), cication: [**-1**](None)

	 *Kai Nylund, Suchin Gururangan, Noah A. Smith*
- **Pretraining Data Mixtures Enable Narrow Model Selection Capabilities in
  Transformer Models**, `arXiv, 2311.00871`, [arxiv](http://arxiv.org/abs/2311.00871v1), [pdf](http://arxiv.org/pdf/2311.00871v1.pdf), cication: [**-1**](None)

	 *Steve Yadlowsky, Lyric Doshi, Nilesh Tripuraneni*

## LLM editting
- **A Comprehensive Study of Knowledge Editing for Large Language Models**, `arXiv, 2401.01286`, [arxiv](http://arxiv.org/abs/2401.01286v2), [pdf](http://arxiv.org/pdf/2401.01286v2.pdf), cication: [**-1**](None)

	 *Ningyu Zhang, Yunzhi Yao, Bozhong Tian, Peng Wang, Shumin Deng, Mengru Wang, Zekun Xi, Shengyu Mao, Jintian Zhang, Yuansheng Ni*
- **Evaluating the Ripple Effects of Knowledge Editing in Language Models**, `arXiv, 2307.12976`, [arxiv](http://arxiv.org/abs/2307.12976v1), [pdf](http://arxiv.org/pdf/2307.12976v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=3039858131654435599&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Roi Cohen, Eden Biran, Ori Yoran, Amir Globerson, Mor Geva*
- **Editing Large Language Models: Problems, Methods, and Opportunities**, `arXiv, 2305.13172`, [arxiv](http://arxiv.org/abs/2305.13172v2), [pdf](http://arxiv.org/pdf/2305.13172v2.pdf), cication: [**12**](https://scholar.google.com/scholar?cites=15387184595402526264&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yunzhi Yao, Peng Wang, Bozhong Tian, Siyuan Cheng, Zhoubo Li, Shumin Deng, Huajun Chen, Ningyu Zhang* · ([easyedit](https://github.com/zjunlp/easyedit) - zjunlp) ![Star](https://img.shields.io/github/stars/zjunlp/easyedit.svg?style=social&label=Star)
- [**ModelEditingPapers**](https://github.com/zjunlp/ModelEditingPapers) - zjunlp ![Star](https://img.shields.io/github/stars/zjunlp/ModelEditingPapers.svg?style=social&label=Star)

	 *Must-read Papers on Model Editing.*

## AGI insights
- [Self-driving as a case study for AGI](https://web.archive.org/web/20240122062223/https://karpathy.github.io/2024/01/21/selfdriving-agi/)
- **Perspectives on the State and Future of Deep Learning -- 2023**, `arXiv, 2312.09323`, [arxiv](http://arxiv.org/abs/2312.09323v1), [pdf](http://arxiv.org/pdf/2312.09323v1.pdf), cication: [**-1**](None)

	 *Micah Goldblum, Anima Anandkumar, Richard Baraniuk, Tom Goldstein, Kyunghyun Cho, Zachary C Lipton, Melanie Mitchell, Preetum Nakkiran, Max Welling, Andrew Gordon Wilson*
- [AI and Open Source in 2023 - by Sebastian Raschka, PhD](https://magazine.sebastianraschka.com/p/ai-and-open-source-in-2023)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652414828&idx=4&sn=7780ba9182ef40d0dac9b076a2d40003))
- [Some intuitions about large language models](https://docs.google.com/presentation/d/1hQUd3pF8_2Gr2Obc89LKjmHL0DlH-uof9M0yFVd3FA4/edit#slide=id.g16197112905_0_0)
- [Role play with large language models | Nature](https://www.nature.com/articles/s41586-023-06647-8)

	 · ([qbitai](https://www.qbitai.com/2023/11/99062.html))
- **Levels of AGI: Operationalizing Progress on the Path to AGI**, `arXiv, 2311.02462`, [arxiv](http://arxiv.org/abs/2311.02462v1), [pdf](http://arxiv.org/pdf/2311.02462v1.pdf), cication: [**-1**](None)

	 *Meredith Ringel Morris, Jascha Sohl-dickstein, Noah Fiedel, Tris Warkentin, Allan Dafoe, Aleksandra Faust, Clement Farabet, Shane Legg*
- **Consciousness in Artificial Intelligence: Insights from the Science of
  Consciousness**, `arXiv, 2308.08708`, [arxiv](http://arxiv.org/abs/2308.08708v3), [pdf](http://arxiv.org/pdf/2308.08708v3.pdf), cication: [**15**](https://scholar.google.com/scholar?cites=8239061011717183910&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Patrick Butlin, Robert Long, Eric Elmoznino, Yoshua Bengio, Jonathan Birch, Axel Constant, George Deane, Stephen M. Fleming, Chris Frith, Xu Ji* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-08-22-4))
- [Collective Intelligence for Deep Learning: A Survey of Recent Developments | 大トロ](https://blog.otoro.net/2022/10/01/collectiveintelligence/)

- [好问题比好答案更重要｜沈向洋大模型五问](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494275&idx=1&sn=4860205e6043435fe7ff871c8fb4c9c1)

## Callibration
- **Llamas Know What GPTs Don't Show: Surrogate Models for Confidence
  Estimation**, `arXiv, 2311.08877`, [arxiv](http://arxiv.org/abs/2311.08877v1), [pdf](http://arxiv.org/pdf/2311.08877v1.pdf), cication: [**-1**](None)

	 *Vaishnavi Shrivastava, Percy Liang, Ananya Kumar*
- **Do Large Language Models Know What They Don't Know?**, `arXiv, 2305.18153`, [arxiv](http://arxiv.org/abs/2305.18153v2), [pdf](http://arxiv.org/pdf/2305.18153v2.pdf), cication: [**16**](https://scholar.google.com/scholar?cites=18069947573459721243&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhangyue Yin, Qiushi Sun, Qipeng Guo, Jiawen Wu, Xipeng Qiu, Xuanjing Huang*

## Books
- [大规模语言模型：从理论到实践](https://intro-llm.github.io/)

## Privacy
- [PIISA](http://piisa.org/)

## Misc
- **Prompt2Model: Generating Deployable Models from Natural Language
  Instructions**, `arXiv, 2308.12261`, [arxiv](http://arxiv.org/abs/2308.12261v1), [pdf](http://arxiv.org/pdf/2308.12261v1.pdf), cication: [**-1**](None)

	 *Vijay Viswanathan, Chenyang Zhao, Amanda Bertsch, Tongshuang Wu, Graham Neubig* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652381740&idx=3&sn=ea1973275259430a24f3a086a82ca617))
- **xVal: A Continuous Number Encoding for Large Language Models**, `arXiv, 2310.02989`, [arxiv](http://arxiv.org/abs/2310.02989v1), [pdf](http://arxiv.org/pdf/2310.02989v1.pdf), cication: [**-1**](None)

	 *Siavash Golkar, Mariel Pettee, Michael Eickenberg, Alberto Bietti, Miles Cranmer, Geraud Krawezik, Francois Lanusse, Michael McCabe, Ruben Ohana, Liam Parker* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652393209&idx=5&sn=d2bd7eabf982afe4b8643b0ef9ff467c))
- **GraphGPT: Graph Instruction Tuning for Large Language Models**, `arXiv, 2310.13023`, [arxiv](http://arxiv.org/abs/2310.13023v1), [pdf](http://arxiv.org/pdf/2310.13023v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=2388076328359031272&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jiabin Tang, Yuhao Yang, Wei Wei, Lei Shi, Lixin Su, Suqi Cheng, Dawei Yin, Chao Huang* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652396739&idx=2&sn=c992b43cb881ac14b6b6402248568854))
- [A taxonomy and review of generalization research in NLP | Nature Machine Intelligence](https://www.nature.com/articles/s42256-023-00729-y?utm_source=twitter&utm_medium=organic_social&utm_campaign=research&utm_content=link)
- **Neurons in Large Language Models: Dead, N-gram, Positional**, `arXiv, 2309.04827`, [arxiv](http://arxiv.org/abs/2309.04827v1), [pdf](http://arxiv.org/pdf/2309.04827v1.pdf), cication: [**-1**](None)

	 *Elena Voita, Javier Ferrando, Christoforos Nalmpantis*
- [ACL 2023最佳论文出炉！CMU西交大等摘桂冠，杰出论文奖华人学者占半壁江](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652350213&idx=3&sn=01843319b9d89fcfda5096af994b2050)山


## Impacts
- [MIT新研究：打工人不用担心被AI淘汰！成本巨贵，视觉工作只有23%可替代](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652436863&idx=3&sn=cd329df965557870646c7dd6fcb460cc)

## Course & Tutorial
- [**LLMs-from-scratch**](https://github.com/rasbt/LLMs-from-scratch) - rasbt ![Star](https://img.shields.io/github/stars/rasbt/LLMs-from-scratch.svg?style=social&label=Star)

	 *Implementing a ChatGPT-like LLM from scratch, step by step*
- [**MachineLearning-QandAI-book**](https://github.com/rasbt/MachineLearning-QandAI-book/tree/main) - rasbt ![Star](https://img.shields.io/github/stars/rasbt/MachineLearning-QandAI-book.svg?style=social&label=Star)

	 *Machine Learning Q and AI book*
- [**ML-YouTube-Courses**](https://github.com/dair-ai/ML-YouTube-Courses) - dair-ai ![Star](https://img.shields.io/github/stars/dair-ai/ML-YouTube-Courses.svg?style=social&label=Star)

	 *📺 Discover the latest machine learning / AI courses on YouTube.*
- [**llm-course**](https://github.com/mlabonne/llm-course) - mlabonne ![Star](https://img.shields.io/github/stars/mlabonne/llm-course.svg?style=social&label=Star)

	 *Course to get into Large Language Models (LLMs) with roadmaps and Colab notebooks.*
- [[1hr Talk] Intro to Large Language Models - YouTube](https://www.youtube.com/watch?v=zjkBMFhNj_g&ab_channel=AndrejKarpathy)

	 · ([drive.google](https://drive.google.com/file/d/1pxx_ZI7O-Nwl7ZLNk5hI3WzAsTLwvNU7/view?pli=1)) · ([drive.google](https://drive.google.com/file/d/1FPUpFMiCkMRKPFjhi9MAhby68MHVqe8u/view?pli=1))

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247620373&idx=1&sn=f319bf1583d025e4f191b2f4a3d156ac))
	 
- [ML 2023 Spring](https://speech.ee.ntu.edu.tw/~hylee/ml/2023-spring.php)
- [80分鐘快速了解大型語言模型 (5:30 有咒術迴戰雷) - YouTube](https://www.youtube.com/watch?v=wG8-IUtqu-s&t=5s&ab_channel=Hung-yiLee)
- [Stanford CS224N: Natural Language Processing with Deep Learning | 2023 - YouTube](https://www.youtube.com/playlist?list=PLoROMvodv4rMFqRtEuo6SGjY4XbRIVRd4)

### CUDA
- [introduce CUDA in a way that will be accessible to Python folks](https://twitter.com/jeremyphoward/status/1752071227228008471)

	 · ([youtu](https://youtu.be/nOxKexn3iBo))

## Extra reference
- [**how-to-optim-algorithm-in-cuda**](https://github.com/BBuf/how-to-optim-algorithm-in-cuda) - BBuf ![Star](https://img.shields.io/github/stars/BBuf/how-to-optim-algorithm-in-cuda.svg?style=social&label=Star)

	 *how to optimize some algorithm in cuda.*
- [MLC-LLM 支持RWKV-5推理以及对RWKV-5的一些思考](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247534749&idx=2&sn=74ee2be683af033e5e39422240ca6e39)