# Awesome opengpt

- [Awesome opengpt](#awesome-opengpt)
- [English](#english)
	- [Foundation](#foundation)
		- [OLMo](#olmo)
		- [Phi](#phi)
		- [Mistral](#mistral)
		- [StripedHyena-7B](#stripedhyena-7b)
		- [BLOOM](#bloom)
		- [Mosaic pretrained transformers (MPT)](#mosaic-pretrained-transformers-mpt)
		- [h2oGPT](#h2ogpt)
		- [LLaMA](#llama)
		- [Falcon](#falcon)
		- [Pythia](#pythia)
		- [Other](#other)
	- [Finetuning](#finetuning)
		- [Vicuna](#vicuna)
		- [Alpaca](#alpaca)
		- [Dolly](#dolly)
		- [Misc](#misc)
- [Mulitlingual (chinese)](#mulitlingual-chinese)
	- [Foundation](#foundation-1)
		- [Yi-01](#yi-01)
		- [InterLM](#interlm)
		- [DeepSeek](#deepseek)
		- [Xverse](#xverse)
		- [Qwen](#qwen)
		- [Baichuan](#baichuan)
		- [ChatGLM](#chatglm)
	- [Finetuning](#finetuning-1)
	- [Other](#other-1)
- [Extra](#extra)
- [Toolkits](#toolkits)
- [Extra reference](#extra-reference)


# English

## Foundation
- [**WizardLM-2-8x22B**](https://huggingface.co/alpindale/WizardLM-2-8x22B) - alpindale 🤗

	 · ([wizardlm.github](https://wizardlm.github.io/WizardLM2/)) · ([WizardLM](https://github.com/victorsungo/WizardLM/tree/main/WizardLM-2) - victorsungo) ![Star](https://img.shields.io/github/stars/victorsungo/WizardLM.svg?style=social&label=Star)
- [**MAP-NEO**](https://github.com/multimodal-art-projection/MAP-NEO) - multimodal-art-projection ![Star](https://img.shields.io/github/stars/multimodal-art-projection/MAP-NEO.svg?style=social&label=Star)
- [Snowflake Arctic: The Best LLM for Enterprise AI — Efficiently Intelligent, Truly Open](https://www.snowflake.com/blog/arctic-open-efficient-foundation-language-models-snowflake/)

	 · ([snowflake-arctic](https://github.com/Snowflake-Labs/snowflake-arctic) - Snowflake-Labs) ![Star](https://img.shields.io/github/stars/Snowflake-Labs/snowflake-arctic.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/Snowflake/snowflake-arctic-instruct)) · ([twitter](https://twitter.com/_philschmid/status/1783140561483960620))
- **OpenELM: An Efficient Language Model Family with Open-source Training
  and Inference Framework**, `arXiv, 2404.14619`, [arxiv](http://arxiv.org/abs/2404.14619v1), [pdf](http://arxiv.org/pdf/2404.14619v1.pdf), cication: [**-1**](None)

	 *Sachin Mehta, Mohammad Hossein Sekhavat, Qingqing Cao, Maxwell Horton, Yanzi Jin, Chenfan Sun, Iman Mirzadeh, Mahyar Najibi, Dmitry Belenko, Peter Zatloukal* · ([huggingface](https://huggingface.co/apple/OpenELM)) · ([corenet](https://github.com/apple/corenet) - apple) ![Star](https://img.shields.io/github/stars/apple/corenet.svg?style=social&label=Star)
- **Reka Core, Flash, and Edge: A Series of Powerful Multimodal Language
  Models**, `arXiv, 2404.12387`, [arxiv](http://arxiv.org/abs/2404.12387v1), [pdf](http://arxiv.org/pdf/2404.12387v1.pdf), cication: [**-1**](None)

	 *Aitor Ormazabal, Che Zheng, Cyprien de Masson d'Autume, Dani Yogatama, Deyu Fu, Donovan Ong, Eric Chen, Eugenie Lamprecht, Hai Pham, Isaac Ong*
	- http://showcase.reka.ai
- **Rho-1: Not All Tokens Are What You Need**, `arXiv, 2404.07965`, [arxiv](http://arxiv.org/abs/2404.07965v1), [pdf](http://arxiv.org/pdf/2404.07965v1.pdf), cication: [**-1**](None)

	 *Zhenghao Lin, Zhibin Gou, Yeyun Gong, Xiao Liu, Yelong Shen, Ruochen Xu, Chen Lin, Yujiu Yang, Jian Jiao, Nan Duan* · ([rho](https://github.com/microsoft/rho) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/rho.svg?style=social&label=Star)
- **MiniCPM: Unveiling the Potential of Small Language Models with Scalable
  Training Strategies**, `arXiv, 2404.06395`, [arxiv](http://arxiv.org/abs/2404.06395v1), [pdf](http://arxiv.org/pdf/2404.06395v1.pdf), cication: [**-1**](None)

	 *Shengding Hu, Yuge Tu, Xu Han, Chaoqun He, Ganqu Cui, Xiang Long, Zhi Zheng, Yewei Fang, Yuxiang Huang, Weilin Zhao* · ([MiniCPM](https://github.com/OpenBMB/MiniCPM) - OpenBMB) ![Star](https://img.shields.io/github/stars/OpenBMB/MiniCPM.svg?style=social&label=Star)
- **Stable LM 2 1.6B Technical Report**, `arXiv, 2402.17834`, [arxiv](http://arxiv.org/abs/2402.17834v1), [pdf](http://arxiv.org/pdf/2402.17834v1.pdf), cication: [**-1**](None)

	 *Marco Bellagente, Jonathan Tow, Dakota Mahan, Duy Phung, Maksym Zhuravinskyi, Reshinth Adithyan, James Baicoianu, Ben Brooks, Nathan Cooper, Ashish Datta*
- [**stablelm-2-12b**](https://huggingface.co/stabilityai/stablelm-2-12b) - stabilityai 🤗
- [**c4ai-command-r-plus**](https://huggingface.co/CohereForAI/c4ai-command-r-plus) - CohereForAI 🤗
- **JetMoE: Reaching Llama2 Performance with 0.1M Dollars**, `arXiv, 2404.07413`, [arxiv](http://arxiv.org/abs/2404.07413v1), [pdf](http://arxiv.org/pdf/2404.07413v1.pdf), cication: [**-1**](None)

	 *Yikang Shen, Zhen Guo, Tianle Cai, Zengyi Qin*
- [**JetMoE**](https://github.com/myshell-ai/JetMoE) - myshell-ai ![Star](https://img.shields.io/github/stars/myshell-ai/JetMoE.svg?style=social&label=Star)

	 *Reaching LLaMA2 Performance with 0.1M Dollars* · ([research.myshell](https://research.myshell.ai/jetmoe)) · ([huggingface](https://huggingface.co/jetmoe/jetmoe-8b)) · ([qbitai](https://www.qbitai.com/2024/04/133284.html))
- **Poro 34B and the Blessing of Multilinguality**, `arXiv, 2404.01856`, [arxiv](http://arxiv.org/abs/2404.01856v1), [pdf](http://arxiv.org/pdf/2404.01856v1.pdf), cication: [**-1**](None)

	 *Risto Luukkonen, Jonathan Burdge, Elaine Zosa, Aarne Talman, Ville Komulainen, Väinö Hatanpää, Peter Sarlin, Sampo Pyysalo* · ([huggingface](https://huggingface.co/LumiOpen/Poro-34B))
- [**MicroLlama**](https://github.com/keeeeenw/MicroLlama) - keeeeenw ![Star](https://img.shields.io/github/stars/keeeeenw/MicroLlama.svg?style=social&label=Star)

	 *Micro Llama is a small Llama based model with 300M parameters trained from scratch with $500 budget*
- [**grok-1**](https://github.com/xai-org/grok-1) - xai-org ![Star](https://img.shields.io/github/stars/xai-org/grok-1.svg?style=social&label=Star)

	 *Grok open release* · ([x](https://t.co/MX0e4ZxEFa)) · ([huggingface](https://huggingface.co/xai-org/grok-1)) · ([qbitai](https://www.qbitai.com/2024/03/128546.html))

	 · ([huggingface](https://huggingface.co/hpcai-tech/grok-1)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s/0ZZG50QVrTqH40CfsBTfqQ))

	 · ([x](https://x.ai/blog/grok-1.5)) · ([qbitai](https://www.qbitai.com/2024/03/131680.html))
- [**c4ai-command-r-v01**](https://huggingface.co/CohereForAI/c4ai-command-r-v01) - CohereForAI 🤗

	 · ([txt.cohere](https://txt.cohere.com/command-r/))

	 · ([huggingface](https://huggingface.co/spaces/CohereForAI/c4ai-command-r-v01))
- [**miqu-1-70b**](https://huggingface.co/miqudev/miqu-1-70b) - miqudev 🤗
- **H2O-Danube-1.8B Technical Report**, `arXiv, 2401.16818`, [arxiv](http://arxiv.org/abs/2401.16818v1), [pdf](http://arxiv.org/pdf/2401.16818v1.pdf), cication: [**-1**](None)

	 *Philipp Singer, Pascal Pfeiffer, Yauhen Babakhin, Maximilian Jeblick, Nischay Dhankhar, Gabor Fodor, Sri Satish Ambati*
- [**Smaug-72B-v0.1**](https://huggingface.co/abacusai/Smaug-72B-v0.1) - abacusai 🤗
- [**Smaug-34B-v0.1**](https://huggingface.co/abacusai/Smaug-34B-v0.1) - abacusai 🤗
- [**bagel-34b-v0.2**](https://huggingface.co/jondurbin/bagel-34b-v0.2) - jondurbin 🤗
- **TinyLlama: An Open-Source Small Language Model**, `arXiv, 2401.02385`, [arxiv](http://arxiv.org/abs/2401.02385v1), [pdf](http://arxiv.org/pdf/2401.02385v1.pdf), cication: [**-1**](None)

	 *Peiyuan Zhang, Guangtao Zeng, Tianduo Wang, Wei Lu* · ([TinyLlama](https://github.com/jzhang38/TinyLlama) - jzhang38) ![Star](https://img.shields.io/github/stars/jzhang38/TinyLlama.svg?style=social&label=Star)
- **TigerBot: An Open Multilingual Multitask LLM**, `arXiv, 2312.08688`, [arxiv](http://arxiv.org/abs/2312.08688v1), [pdf](http://arxiv.org/pdf/2312.08688v1.pdf), cication: [**-1**](None)

	 *Ye Chen, Wei Cai, Liangmin Wu, Xiaowei Li, Zhanxuan Xin, Cong Fu*
- [**DeciLM-7B**](https://huggingface.co/Deci/DeciLM-7B) - Deci 🤗
- [**DeciLM-7B-instruct**](https://huggingface.co/Deci/DeciLM-7B-instruct) - Deci 🤗

	 · ([huggingface](https://huggingface.co/spaces/Deci/DeciLM-7B-instruct))
- **LLM360: Towards Fully Transparent Open-Source LLMs**, `arXiv, 2312.06550`, [arxiv](http://arxiv.org/abs/2312.06550v1), [pdf](http://arxiv.org/pdf/2312.06550v1.pdf), cication: [**-1**](None)

	 *Zhengzhong Liu, Aurick Qiao, Willie Neiswanger, Hongyi Wang, Bowen Tan, Tianhua Tao, Junbo Li, Yuqi Wang, Suqi Sun, Omkar Pangarkar*
	- https://www.llm360.ai
- **GPT4All: An Ecosystem of Open Source Compressed Language Models**, `arXiv, 2311.04931`, [arxiv](http://arxiv.org/abs/2311.04931v1), [pdf](http://arxiv.org/pdf/2311.04931v1.pdf), cication: [**-1**](None)

	 *Yuvanesh Anand, Zach Nussbaum, Adam Treat, Aaron Miller, Richard Guo, Ben Schmidt, GPT4All Community, Brandon Duderstadt, Andriy Mulyar* · ([gpt4all](https://github.com/nomic-ai/gpt4all) - nomic-ai) ![Star](https://img.shields.io/github/stars/nomic-ai/gpt4all.svg?style=social&label=Star)
- **OpenChat: Advancing Open-source Language Models with Mixed-Quality Data**, `arXiv, 2309.11235`, [arxiv](http://arxiv.org/abs/2309.11235v1), [pdf](http://arxiv.org/pdf/2309.11235v1.pdf), cication: [**-1**](None)

	 *Guan Wang, Sijie Cheng, Xianyuan Zhan, Xiangang Li, Sen Song, Yang Liu* · ([openchat](https://github.com/imoneoi/openchat) - imoneoi) ![Star](https://img.shields.io/github/stars/imoneoi/openchat.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/openchat)) · ([openchat](https://openchat.team/))
  
- **Zephyr: Direct Distillation of LM Alignment**, `arXiv, 2310.16944`, [arxiv](http://arxiv.org/abs/2310.16944v1), [pdf](http://arxiv.org/pdf/2310.16944v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=5826276281263581161&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lewis Tunstall, Edward Beeching, Nathan Lambert, Nazneen Rajani, Kashif Rasul, Younes Belkada, Shengyi Huang, Leandro von Werra, Clémentine Fourrier, Nathan Habib* · ([alignment-handbook](https://github.com/huggingface/alignment-handbook) - huggingface) ![Star](https://img.shields.io/github/stars/huggingface/alignment-handbook.svg?style=social&label=Star)
- **H2O Open Ecosystem for State-of-the-art Large Language Models**, `arXiv, 2310.13012`, [arxiv](http://arxiv.org/abs/2310.13012v2), [pdf](http://arxiv.org/pdf/2310.13012v2.pdf), cication: [**-1**](None)

	 *Arno Candel, Jon McKinney, Philipp Singer, Pascal Pfeiffer, Maximilian Jeblick, Chun Ming Lee, Marcos V. Conde*

- **BTLM-3B-8K: 7B Parameter Performance in a 3B Parameter Model**, `arXiv, 2309.11568`, [arxiv](http://arxiv.org/abs/2309.11568v1), [pdf](http://arxiv.org/pdf/2309.11568v1.pdf), cication: [**-1**](None)

	 *Nolan Dey, Daria Soboleva, Faisal Al-Khateeb, Bowen Yang, Ribhu Pathria, Hemant Khachane, Shaheer Muhammad, Zhiming, Chen, Robert Myers*
- **OpenBA: An Open-sourced 15B Bilingual Asymmetric seq2seq Model
  Pre-trained from Scratch**, `arXiv, 2309.10706`, [arxiv](http://arxiv.org/abs/2309.10706v2), [pdf](http://arxiv.org/pdf/2309.10706v2.pdf), cication: [**-1**](None)

	 *Juntao Li, Zecheng Tang, Yuyang Ding, Pinzheng Wang, Pei Guo, Wangjie You, Dan Qiao, Wenliang Chen, Guohong Fu, Qiaoming Zhu* · ([openba](https://github.com/opennlg/openba) - opennlg) ![Star](https://img.shields.io/github/stars/opennlg/openba.svg?style=social&label=Star)
- **XGen-7B Technical Report**, `arXiv, 2309.03450`, [arxiv](http://arxiv.org/abs/2309.03450v1), [pdf](http://arxiv.org/pdf/2309.03450v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=117715493627458986&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Erik Nijkamp, Tian Xie, Hiroaki Hayashi, Bo Pang, Congying Xia, Chen Xing, Jesse Vig, Semih Yavuz, Philippe Laban, Ben Krause*
- **FLM-101B: An Open LLM and How to Train It with $100K Budget**, `arXiv, 2309.03852`, [arxiv](http://arxiv.org/abs/2309.03852v2), [pdf](http://arxiv.org/pdf/2309.03852v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=4198426784142613389&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xiang Li, Yiqun Yao, Xin Jiang, Xuezhi Fang, Xuying Meng, Siqi Fan, Peng Han, Jing Li, Li Du, Bowen Qin* · ([huggingface](https://huggingface.co/CofeAI/FLM-101B))
- [**adept-inference**](https://github.com/persimmon-ai-labs/adept-inference) - persimmon-ai-labs ![Star](https://img.shields.io/github/stars/persimmon-ai-labs/adept-inference.svg?style=social&label=Star)

	 *Inference code for Persimmon-8B*
- [**WizardLM**](https://github.com/nlpxucan/WizardLM) - nlpxucan ![Star](https://img.shields.io/github/stars/nlpxucan/WizardLM.svg?style=social&label=Star)

	 *Family of instruction-following LLMs powered by Evol-Instruct: WizardLM, WizardCoder*
- [**FreeWilly2**](https://huggingface.co/stabilityai/FreeWilly2) - stabilityai 🤗
- [**xgen**](https://github.com/salesforce/xgen) - salesforce ![Star](https://img.shields.io/github/stars/salesforce/xgen.svg?style=social&label=Star)

	 *Salesforce open-source LLMs with 8k sequence length.*
- **PolyLM: An Open Source Polyglot Large Language Model**, `arXiv, 2307.06018`, [arxiv](http://arxiv.org/abs/2307.06018v1), [pdf](http://arxiv.org/pdf/2307.06018v1.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=15686217570453587147&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xiangpeng Wei, Haoran Wei, Huan Lin, Tianhao Li, Pei Zhang, Xingzhang Ren, Mei Li, Yu Wan, Zhiwei Cao, Binbin Xie*
- **A Technical Report for Polyglot-Ko: Open-Source Large-Scale Korean
  Language Models**, `arXiv, 2306.02254`, [arxiv](http://arxiv.org/abs/2306.02254v2), [pdf](http://arxiv.org/pdf/2306.02254v2.pdf), cication: [**-1**](None)

	 *Hyunwoong Ko, Kichang Yang, Minho Ryu, Taekyoon Choi, Seungmu Yang, Jiwung Hyun, Sungho Park, Kyubyong Park*
- **Examining User-Friendly and Open-Sourced Large GPT Models: A Survey on
  Language, Multimodal, and Scientific GPT Models**, `arXiv, 2308.14149`, [arxiv](http://arxiv.org/abs/2308.14149v1), [pdf](http://arxiv.org/pdf/2308.14149v1.pdf), cication: [**-1**](None)

	 *Kaiyuan Gao, Sunan He, Zhenyu He, Jiacheng Lin, QiZhi Pei, Jie Shao, Wei Zhang* · ([gpt_alternatives](https://github.com/GPT-Alternatives/gpt_alternatives) - GPT-Alternatives) ![Star](https://img.shields.io/github/stars/GPT-Alternatives/gpt_alternatives.svg?style=social&label=Star) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-12-3))

### Llama 3
- [Welcome Llama 3 - Meta's new open LLM](https://huggingface.co/blog/llama3)
- [Site Unreachable](https://ai.meta.com/blog/meta-llama-3/)
- [**llama3**](https://github.com/meta-llama/llama3/tree/main) - meta-llama ![Star](https://img.shields.io/github/stars/meta-llama/llama3.svg?style=social&label=Star)

	 *The official Meta Llama 3 GitHub site*
- [**Meta-Llama-3-8B-Instruct**](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct) - meta-llama 🤗
- [**Meta-Llama-3-70B-Instruct**](https://huggingface.co/meta-llama/Meta-Llama-3-70B-Instruct) - meta-llama 🤗

- [**Llama-3-Smaug-8B**](https://huggingface.co/abacusai/Llama-3-Smaug-8B) - abacusai 🤗
- [**Llama-3-8B-16K**](https://huggingface.co/mattshumer/Llama-3-8B-16K) - mattshumer 🤗
- [**Llama-3-8B-Special-Tokens-Adjusted**](https://huggingface.co/astronomer/Llama-3-8B-Special-Tokens-Adjusted) - astronomer 🤗
- [Google Colab](https://colab.research.google.com/drive/1aqlNQi7MMJbynFDyOQteD2t0yVfjb9Zh?usp=sharing)
- [**Llama-3-8b-64k-PoSE**](https://huggingface.co/winglian/Llama-3-8b-64k-PoSE) - winglian 🤗
- [**dolphin-2.9-llama3-70b**](https://huggingface.co/cognitivecomputations/dolphin-2.9-llama3-70b) - cognitivecomputations 🤗
- [**Llama-3-8B-Instruct-262k**](https://huggingface.co/gradientai/Llama-3-8B-Instruct-262k) - gradientai 🤗
- [Meditron: An LLM suite especially suited for low-resource medical settings leveraging Meta Llama](https://ai.meta.com/blog/llama-2-3-meditron-yale-medicine-epfl-open-source-llm/)
- [**llama-3-8b-256k-PoSE**](https://huggingface.co/winglian/llama-3-8b-256k-PoSE) - winglian 🤗
- [**Llama-3-8B-Instruct-Gradient-1048k**](https://huggingface.co/gradientai/Llama-3-8B-Instruct-Gradient-1048k) - gradientai 🤗
- [**Hermes-2-Pro-Llama-3-8B**](https://huggingface.co/NousResearch/Hermes-2-Pro-Llama-3-8B) - NousResearch 🤗
- [**Llama3-ChatQA-1.5-8B**](https://huggingface.co/nvidia/Llama3-ChatQA-1.5-8B) - nvidia 🤗
- [**Meta-Llama-3-120B-Instruct**](https://huggingface.co/mlabonne/Meta-Llama-3-120B-Instruct) - mlabonne 🤗
- [What’s up with Llama 3? Arena data analysis | LMSYS Org](https://lmsys.org/blog/2024-05-08-llama3/)
- [Planning for Distillation of Llama 3 70b -> 4x8b / 25b : r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/comments/1cnlmz2/planning_for_distillation_of_llama_3_70b_4x8b_25b/)
- [**Llama-3-Refueled**](https://huggingface.co/refuelai/Llama-3-Refueled) - refuelai 🤗
### Jamba
- **Jamba: A Hybrid Transformer-Mamba Language Model**, `arXiv, 2403.19887`, [arxiv](http://arxiv.org/abs/2403.19887v1), [pdf](http://arxiv.org/pdf/2403.19887v1.pdf), cication: [**-1**](None)

	 *Opher Lieber, Barak Lenz, Hofit Bata, Gal Cohen, Jhonathan Osin, Itay Dalmedigos, Erez Safahi, Shaked Meirom, Yonatan Belinkov, Shai Shalev-Shwartz* · ([huggingface](https://huggingface.co/ai21labs/Jamba-v0.1))
- [**Jamba-v0.1-chat-multilingual**](https://huggingface.co/lightblue/Jamba-v0.1-chat-multilingual?utm_source=ainews&utm_medium=email&utm_campaign=ainews-not-much-happened-today-8015) - lightblue 🤗
- [**Jambatypus-v0.1**](https://huggingface.co/mlabonne/Jambatypus-v0.1) - mlabonne 🤗

### Databricks
- [Introducing DBRX: A New State-of-the-Art Open LLM | Databricks](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm)

	 · ([twitter](https://twitter.com/jefrankle/status/1772961586497425683)) · ([twitter](https://twitter.com/danielhanchen/status/1772981050530316467))
- [**dbrx**](https://github.com/databricks/dbrx) - databricks ![Star](https://img.shields.io/github/stars/databricks/dbrx.svg?style=social&label=Star)

	 *Code examples and resources for DBRX, a large language model developed by Databricks*
- [**dbrx-instruct**](https://huggingface.co/databricks/dbrx-instruct) - databricks 🤗

### Gemma
- [Fetching Title#nst4](https://huggingface.co/google/gemma-1.1-7b-it)
- **Gemma: Open Models Based on Gemini Research and Technology**, `arXiv, 2403.08295`, [arxiv](http://arxiv.org/abs/2403.08295v1), [pdf](http://arxiv.org/pdf/2403.08295v1.pdf), cication: [**-1**](None)

	 *Gemma Team, Thomas Mesnard, Cassidy Hardin, Robert Dadashi, Surya Bhupatiraju, Shreya Pathak, Laurent Sifre, Morgane Rivière, Mihir Sanjay Kale, Juliette Love*
- **Gemini 1.5: Unlocking multimodal understanding across millions of tokens
  of context**, `arXiv, 2403.05530`, [arxiv](http://arxiv.org/abs/2403.05530v1), [pdf](http://arxiv.org/pdf/2403.05530v1.pdf), cication: [**-1**](None)

	 *Machel Reid, Nikolay Savinov, Denis Teplyashin, Dmitry Lepikhin, Timothy Lillicrap, Jean-baptiste Alayrac, Radu Soricut, Angeliki Lazaridou, Orhan Firat, Julian Schrittwieser*
- [Unsloth Fixing Gemma bugs](https://unsloth.ai/blog/gemma-bugs)

	 · ([twitter](https://twitter.com/danielhanchen/status/1765446273661075609))
- [**gemma_pytorch**](https://github.com/google/gemma_pytorch/tree/main) - google ![Star](https://img.shields.io/github/stars/google/gemma_pytorch.svg?style=social&label=Star)

	 *The official PyTorch implementation of Google's Gemma models*
- [**gemma-7b**](https://huggingface.co/google/gemma-7b) - google 🤗

	 · ([ai.google](https://ai.google.dev/gemma/docs)) · ([huggingface](https://huggingface.co/blog/gemma))
- [**gemma.cpp**](https://github.com/google/gemma.cpp) - google ![Star](https://img.shields.io/github/stars/google/gemma.cpp.svg?style=social&label=Star)

	 *lightweight, standalone C++ inference engine for Google's Gemma models.*
- [**gemma-peft**](https://huggingface.co/blog/gemma-peft) -  🤗
- [Understanding, Using, and Finetuning Gemma - a Lightning Studio by sebastian](https://lightning.ai/lightning-ai/studios/understanding-using-and-finetuning-gemma)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-02-28-9))
- [**gemma-7b-dolly-chatml**](https://huggingface.co/philschmid/gemma-7b-dolly-chatml) - philschmid 🤗
- [**catch-me-if-you-can**](https://huggingface.co/spaces/cyzgab/catch-me-if-you-can) - cyzgab 🤗
- [**GemMoE-Beta-1**](https://huggingface.co/Crystalcareai/GemMoE-Beta-1) - Crystalcareai 🤗
- [**Hebrew-Gemma-11B**](https://huggingface.co/yam-peleg/Hebrew-Gemma-11B) - yam-peleg 🤗
- [Gemma finetuning should be much better now : r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/comments/1bd18y8/gemma_finetuning_should_be_much_better_now/?rdt=59207)
- [Gemma-10M Technical Overview. Motivation | by Akshgarg | May, 2024 | Medium](https://medium.com/@akshgarg_36829/gemma-10m-technical-overview-900adc4fbeeb)

	 · ([gemma-2B-10M](https://github.com/mustafaaljadery/gemma-2B-10M?tab=readme-ov-file) - mustafaaljadery) ![Star](https://img.shields.io/github/stars/mustafaaljadery/gemma-2B-10M.svg?style=social&label=Star)
### OLMo
- [OLMo 1.7–7B: A 24 point improvement on MMLU | by AI2 | Apr, 2024 | AI2 Blog](https://blog.allenai.org/olmo-1-7-7b-a-24-point-improvement-on-mmlu-92b43f7d269d)
- [**OLMo-1.7-7B**](https://huggingface.co/allenai/OLMo-1.7-7B) - allenai 🤗
- **OLMo: Accelerating the Science of Language Models**, `arXiv, 2402.00838`, [arxiv](http://arxiv.org/abs/2402.00838v1), [pdf](http://arxiv.org/pdf/2402.00838v1.pdf), cication: [**-1**](None)

	 *Dirk Groeneveld, Iz Beltagy, Pete Walsh, Akshita Bhagia, Rodney Kinney, Oyvind Tafjord, Ananya Harsh Jha, Hamish Ivison, Ian Magnusson, Yizhong Wang* · ([OLMo](https://github.com/allenai/OLMo) - allenai) ![Star](https://img.shields.io/github/stars/allenai/OLMo.svg?style=social&label=Star) · ([allenai](https://allenai.org/olmo)) · ([allenai](https://allenai.org/olmo/olmo-paper.pdf))
- [**OLMo-7B**](https://huggingface.co/allenai/OLMo-7B) - allenai 🤗
- [**OLMo-7B-Instruct**](https://huggingface.co/allenai/OLMo-7B-Instruct) - allenai 🤗

### Phi
- [**models**](https://huggingface.co/models?other=phi3&sort=trending&search=microsoft) -  🤗
- **Phi-3 Technical Report: A Highly Capable Language Model Locally on Your
  Phone**, `arXiv, 2404.14219`, [arxiv](http://arxiv.org/abs/2404.14219v1), [pdf](http://arxiv.org/pdf/2404.14219v1.pdf), cication: [**-1**](None)

	 *Marah Abdin, Sam Ade Jacobs, Ammar Ahmad Awan, Jyoti Aneja, Ahmed Awadallah, Hany Awadalla, Nguyen Bach, Amit Bahree, Arash Bakhtiari, Harkirat Behl*
- [**phi-2**](https://huggingface.co/microsoft/phi-2) - microsoft 🤗
- [**phi-1_5**](https://huggingface.co/microsoft/phi-1_5) - microsoft 🤗
- [**phi-1**](https://huggingface.co/microsoft/phi-1) - microsoft 🤗

- [**phi-2**](https://huggingface.co/spaces/randomblock1/phi-2) - randomblock1 🤗
- [**phixtral-4x2_8**](https://huggingface.co/mlabonne/phixtral-4x2_8) - mlabonne 🤗
### Mistral
- [Cheaper, Better, Faster, Stronger | Mistral AI | Frontier AI in your hands](https://mistral.ai/news/mixtral-8x22b)
- [Fetching Title#dsku](https://huggingface.co/mistralai/Mixtral-8x22B-v0.1)
- [**mixtral-8x22b-instruct-oh**](https://huggingface.co/fireworks-ai/mixtral-8x22b-instruct-oh) - fireworks-ai 🤗
- [**Mistral-22B-v0.2**](https://huggingface.co/Vezora/Mistral-22B-v0.2) - Vezora 🤗
- [**Mistral-22B-v0.1**](https://huggingface.co/Vezora/Mistral-22B-v0.1) - Vezora 🤗
- [**zephyr-orpo-141b-A35b-v0.1**](https://huggingface.co/HuggingFaceH4/zephyr-orpo-141b-A35b-v0.1) - HuggingFaceH4 🤗

	 · ([huggingface](https://huggingface.co/chat/models/HuggingFaceH4/zephyr-orpo-141b-A35b-v0.1))
- [**Mixtral-8x22B-v0.1**](https://huggingface.co/mistral-community/Mixtral-8x22B-v0.1) - mistral-community 🤗
- [**hackathon**](https://github.com/mistralai-sf24/hackathon) - mistralai-sf24 ![Star](https://img.shields.io/github/stars/mistralai-sf24/hackathon.svg?style=social&label=Star)

	 · ([models.mistralcdn](https://models.mistralcdn.com/mistral-7b-v0-2/mistral-7B-v0.2.tar)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-03-25-8))
- [**Mistral-7B-Instruct-v0.2**](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2) - mistralai 🤗
- [**mistral-src**](https://github.com/mistralai/mistral-src) - mistralai ![Star](https://img.shields.io/github/stars/mistralai/mistral-src.svg?style=social&label=Star)

	 *Reference implementation of Mistral AI 7B v0.1 model.* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-29-2))
- [Mixtral of experts | Mistral AI | Open source models](https://mistral.ai/news/mixtral-of-experts/)
- [**mixtral**](https://huggingface.co/blog/mixtral) -  🤗
- [**llama-mistral**](https://github.com/dzhulgakov/llama-mistral?tab=readme-ov-file) - dzhulgakov ![Star](https://img.shields.io/github/stars/dzhulgakov/llama-mistral?tab=readme-ov-file.svg?style=social&label=Star)

	 *Inference code for Mistral and Mixtral hacked up into original Llama implementation*
- [**DiscoLM-mixtral-8x7b-v2**](https://huggingface.co/DiscoResearch/DiscoLM-mixtral-8x7b-v2) - DiscoResearch 🤗
- [**Mixtral-8x7B-Instruct-v0.1**](https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1) - mistralai 🤗

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247633402&idx=2&sn=1d2952609efe41ae8fa74396de5ef4cf))
- [**mixtral-7b-8expert**](https://huggingface.co/DiscoResearch/mixtral-7b-8expert) - DiscoResearch 🤗

	 · ([huggingface](https://t.co/rFz2hhLWat))
- [**mixtral-8x7b-32kseqlen**](https://huggingface.co/someone13574/mixtral-8x7b-32kseqlen) - someone13574 🤗
- [**mixtral-46.7b-chat**](https://huggingface.co/spaces/openskyml/mixtral-46.7b-chat) - openskyml 🤗
- [**Mixtral-8x7B-v0.1-GPTQ**](https://huggingface.co/TheBloke/Mixtral-8x7B-v0.1-GPTQ) - TheBloke 🤗
- [Mixtral 8x7B on Fireworks: faster, cheaper, even before the official release | by Fireworks.ai | Dec, 2023 | Medium](https://blog.fireworks.ai/mixtral-8x7b-on-fireworks-faster-cheaper-even-before-the-official-release-ae024b5ad602)
- [**MixtralKit**](https://github.com/open-compass/MixtralKit) - open-compass ![Star](https://img.shields.io/github/stars/open-compass/MixtralKit.svg?style=social&label=Star)

	 *A toolkit for inference and evaluation of 'mixtral-8x7b-32kseqlen' from Mistral AI*
- [**mistral-playground**](https://huggingface.co/spaces/marcofrodl/mistral-playground) - marcofrodl 🤗
- [**Mixtral-8x7B-Instruct-v0.1-bnb-4bit**](https://huggingface.co/ybelkada/Mixtral-8x7B-Instruct-v0.1-bnb-4bit) - ybelkada 🤗
- [**notux-8x7b-v1**](https://huggingface.co/argilla/notux-8x7b-v1) - argilla 🤗
- [**mixtral-offloading**](https://github.com/dvmazur/mixtral-offloading) - dvmazur ![Star](https://img.shields.io/github/stars/dvmazur/mixtral-offloading.svg?style=social&label=Star)

	 *Run Mixtral-8x7B models in Colab or consumer desktops*
- [**mixtral-test-46.7b-chat**](https://huggingface.co/spaces/johann22/mixtral-test-46.7b-chat) - johann22 🤗
- [**Nous-Hermes-2-Mixtral-8x7B-SFT**](https://huggingface.co/NousResearch/Nous-Hermes-2-Mixtral-8x7B-SFT) - NousResearch 🤗

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-01-16-2))
- [**Nous-Hermes-2-Mixtral-8x7B-DPO**](https://huggingface.co/NousResearch/Nous-Hermes-2-Mixtral-8x7B-DPO) - NousResearch 🤗
- [**Nous-Hermes-2-Mixtral-8x7B-DPO-adapter**](https://huggingface.co/NousResearch/Nous-Hermes-2-Mixtral-8x7B-DPO-adapter) - NousResearch 🤗
- [**miqu-1-70b**](https://huggingface.co/miqudev/miqu-1-70b) - miqudev 🤗
- [**Hermes-2-Pro-Mistral-7B**](https://huggingface.co/NousResearch/Hermes-2-Pro-Mistral-7B) - NousResearch 🤗
- [**dolphin-2.8-mistral-7b-v02**](https://huggingface.co/cognitivecomputations/dolphin-2.8-mistral-7b-v02) - cognitivecomputations 🤗
- [**dolphin-2.8-mistral-7b-v02**](https://huggingface.co/cognitivecomputations/dolphin-2.8-mistral-7b-v02) - cognitivecomputations 🤗

### StripedHyena-7B 
- [**StripedHyena-Hessian-7B**](https://huggingface.co/togethercomputer/StripedHyena-Hessian-7B) - togethercomputer 🤗
- [**StripedHyena-Nous-7B**](https://huggingface.co/togethercomputer/StripedHyena-Nous-7B) - togethercomputer 🤗

	 · ([together](https://www.together.ai/blog/stripedhyena-7b))
 
### BLOOM
- [**BLOOMChat-176B-v1-GPTQ**](https://huggingface.co/TheBloke/BLOOMChat-176B-v1-GPTQ) - TheBloke 🤗

### Mosaic pretrained transformers (MPT)
[GitHub - mosaicml/llm-foundry: LLM training code for MosaicML foundation models](https://github.com/mosaicml/llm-foundry)
- [**mpt-30b-chat**](https://huggingface.co/spaces/mosaicml/mpt-30b-chat) - mosaicml 🤗

### h2oGPT
- **h2oGPT: Democratizing Large Language Models**, `arXiv, 2306.08161`, [arxiv](http://arxiv.org/abs/2306.08161v2), [pdf](http://arxiv.org/pdf/2306.08161v2.pdf), cication: [**-1**](None)

	 *Arno Candel, Jon McKinney, Philipp Singer, Pascal Pfeiffer, Maximilian Jeblick, Prithvi Prabhu, Jeff Gambera, Mark Landry, Shivam Bansal, Ryan Chesler*

### LLaMA
- [**LiteLlama-460M-1T**](https://huggingface.co/ahxt/LiteLlama-460M-1T) - ahxt 🤗

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-01-08-20))
- [**Llama-2-7b-chat-mlx**](https://huggingface.co/mlx-llama/Llama-2-7b-chat-mlx) - mlx-llama 🤗
- [**TinyLlama**](https://github.com/jzhang38/TinyLlama) - jzhang38 ![Star](https://img.shields.io/github/stars/jzhang38/TinyLlama.svg?style=social&label=Star)

	 *The TinyLlama project is an open endeavor to pretrain a 1.1B Llama model on 3 trillion tokens.*
- [**llama-recipes**](https://github.com/facebookresearch/llama-recipes) - facebookresearch ![Star](https://img.shields.io/github/stars/facebookresearch/llama-recipes.svg?style=social&label=Star)

	 *Examples and recipes for Llama 2 model* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652356830&idx=3&sn=2bbccd2a7c376a880f63daf0689fc016)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-27-6)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650884954&idx=4&sn=d409ac067d3e148d55f6a80813d2b653&chksm=84e48f24b3930632faf43e36512448b778ecef21f60c9dab960340e1f33960f9369d9a148853&scene=21#wechat_redirect)) · ([d7mv45xi4m.feishu](https://d7mv45xi4m.feishu.cn/docx/DOHIdmpbCoXhRwx62cCc3RcEnCh))
- [**llama2-13b-orca-8k-3319**](https://huggingface.co/OpenAssistant/llama2-13b-orca-8k-3319) - OpenAssistant 🤗
- [**pyllama**](https://github.com/juncongmoo/pyllama) - juncongmoo ![Star](https://img.shields.io/github/stars/juncongmoo/pyllama.svg?style=social&label=Star)

	 *LLaMA: Open and Efficient Foundation Language Models*
- [**llama-gpt**](https://github.com/getumbrel/llama-gpt) - getumbrel ![Star](https://img.shields.io/github/stars/getumbrel/llama-gpt.svg?style=social&label=Star)

	 *A self-hosted, offline, ChatGPT-like chatbot. Powered by Llama 2. 100% private, with no data leaving your device.*
- [**LLongMA-2-13b-16k**](https://huggingface.co/conceptofmind/LLongMA-2-13b-16k) - conceptofmind 🤗
- [**LLongMA-2-13b**](https://huggingface.co/conceptofmind/LLongMA-2-13b) - conceptofmind 🤗
- [**LLongMA-2-7b-16k**](https://huggingface.co/conceptofmind/LLongMA-2-7b-16k) - conceptofmind 🤗
- [Llama 2: an incredible open LLM - by Nathan Lambert](https://www.interconnects.ai/p/llama-2-from-meta)
- [**llama2-webui**](https://github.com/liltom-eth/llama2-webui) - liltom-eth ![Star](https://img.shields.io/github/stars/liltom-eth/llama2-webui.svg?style=social&label=Star)

	 *Run Llama 2 locally with gradio UI on GPU or CPU from anywhere (Linux/Windows/Mac). Supporting Llama-2-7B/13B/70B with 8-bit, 4-bit. Supporting GPU inference (6 GB VRAM) and CPU inference.*
- [Fine-tune Llama 2 with DPO](https://huggingface.co/blog/dpo-trl)
- [**Flan-Open-Llama-13b**](https://huggingface.co/conceptofmind/Flan-Open-Llama-13b) - conceptofmind 🤗
- [**Llama-2**](https://github.com/amitsangani/Llama-2) - amitsangani ![Star](https://img.shields.io/github/stars/amitsangani/Llama-2.svg?style=social&label=Star)

	 *All the projects related to Llama*

### Falcon
- [Spread Your Wings: Falcon 180B is here](https://huggingface.co/blog/falcon-180b)
- [**Falcon-LLM**](https://github.com/Sentdex/Falcon-LLM) - Sentdex ![Star](https://img.shields.io/github/stars/Sentdex/Falcon-LLM.svg?style=social&label=Star)

	 *Helper scripts and examples for exploring the Falcon LLM models* · ([huggingface](https://huggingface.co/blog/falcon)) · ([huggingface](https://huggingface.co/tiiuae/falcon-40b))
### Pythia
[[2304.01373] Pythia: A Suite for Analyzing Large Language Models Across Training and Scaling](https://arxiv.org/abs/2304.01373)

	 · ([pythia](https://github.com/EleutherAI/pythia) - EleutherAI) ![Star](https://img.shields.io/github/stars/EleutherAI/pythia.svg?style=social&label=Star)

### Other
- [Timeline of recent major LLM releases (past 2 months) : r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/comments/1cn9sxa/timeline_of_recent_major_llm_releases_past_2)
- [The History of Open-Source LLMs: Imitation and Alignment (Part Three)](https://cameronrwolfe.substack.com/p/the-history-of-open-source-llms-imitation)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247623963&idx=1&sn=e4b4be03cf313a55da81384edd8e9283))
- [**os-llms**](https://huggingface.co/blog/os-llms) - blog 🤗

- [​A16Z 刚刚官宣支持8个开源人工智能社区](https://mp.weixin.qq.com/s/NdS4uLFq5aKooLBNDJkBfg?poc_token=HAo18GSj4ZMEfny8SxzCNcB19EiSiStV32OiEUJ-)
- [开源大型语言模型(llm)总结](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247608677&idx=2&sn=55a6b6d710e57527218128efa4107027)

## Finetuning 
### Vicuna
- **Flacuna: Unleashing the Problem Solving Power of Vicuna using FLAN
  Fine-Tuning**, `arXiv, 2307.02053`, [arxiv](http://arxiv.org/abs/2307.02053v1), [pdf](http://arxiv.org/pdf/2307.02053v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=8043646391903993544&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Deepanway Ghosal, Yew Ken Chia, Navonil Majumder, Soujanya Poria*
- [**FastChat**](https://github.com/lm-sys/FastChat) - lm-sys ![Star](https://img.shields.io/github/stars/lm-sys/FastChat.svg?style=social&label=Star)

	 *An open platform for training, serving, and evaluating large language models. Release repo for Vicuna and FastChat-T5.*
### Alpaca 
- [**stanford_alpaca**](https://github.com/tatsu-lab/stanford_alpaca) - tatsu-lab ![Star](https://img.shields.io/github/stars/tatsu-lab/stanford_alpaca.svg?style=social&label=Star)

	 *Code and documentation to train Stanford's Alpaca models, and generate the data.* · ([crfm.stanford](https://crfm.stanford.edu/2023/03/13/alpaca.html))
### Dolly
- [**dolly**](https://github.com/databrickslabs/dolly) - databrickslabs ![Star](https://img.shields.io/github/stars/databrickslabs/dolly.svg?style=social&label=Star)

	 *Databricks’ Dolly, a large language model trained on the Databricks Machine Learning Platform* · ([huggingface](https://huggingface.co/databricks/dolly-v2-12b)) · ([databricks](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm))
### Misc
- [WizardLM - a microsoft Collection](https://huggingface.co/collections/microsoft/wizardlm-661d403f71e6c8257dbd598a)
- [**YamshadowExperiment28-7B**](https://huggingface.co/automerger/YamshadowExperiment28-7B) - automerger 🤗

	 · ([twitter](https://twitter.com/maximelabonne/status/1777610370925871239))
- [Starling-7B: Increasing LLM Helpfulness & Harmlessness with RLAIF](https://starling.cs.berkeley.edu/)

	 · ([huggingface](https://huggingface.co/Nexusflow/Starling-LM-7B-beta)) · ([huggingface](https://huggingface.co/Nexusflow/Starling-RM-34B))
- [**Beagle14-7B**](https://huggingface.co/mlabonne/Beagle14-7B) - mlabonne 🤗
- [Improving Open-Source LLMs - Datasets, Merging and Stacking - The Abacus.AI Blog](https://blog.abacus.ai/blog/2024/01/11/the-open-source-cookbook-how-to-soup-up-your-open-source-llm/)
- [**CrystalChat**](https://huggingface.co/LLM360/CrystalChat) - LLM360 🤗
- [**btlm-3b-8k-chat**](https://huggingface.co/cerebras/btlm-3b-8k-chat) - cerebras 🤗
- [**stablelm-zephyr-3b**](https://huggingface.co/stabilityai/stablelm-zephyr-3b) - stabilityai 🤗

	 · ([huggingface](https://huggingface.co/spaces/Tonic/TonicsStableLM3B))
- [**smol-7b**](https://huggingface.co/rishiraj/smol-7b) - rishiraj 🤗
- **LLM-Blender: Ensembling Large Language Models with Pairwise Ranking and
  Generative Fusion**, `arXiv, 2306.02561`, [arxiv](http://arxiv.org/abs/2306.02561v3), [pdf](http://arxiv.org/pdf/2306.02561v3.pdf), cication: [**-1**](None)

	 *Dongfu Jiang, Xiang Ren, Bill Yuchen Lin* · ([huggingface](https://huggingface.co/llm-blender/PairRM)) · ([LLM-Blender](https://github.com/yuchenlin/LLM-Blender) - yuchenlin) ![Star](https://img.shields.io/github/stars/yuchenlin/LLM-Blender.svg?style=social&label=Star)
- [Intel Neural-Chat 7b: Fine-Tuning on Gaudi2 for Top LLM Performance](https://huggingface.co/blog/Andyrasika/neural-chat-intel)
- [Starling-7B: Increasing LLM Helpfulness & Harmlessness with RLAIF](https://starling.cs.berkeley.edu/)
- [**sparse-llama-gsm8k**](https://huggingface.co/spaces/neuralmagic/sparse-llama-gsm8k) - neuralmagic 🤗
- [**DeciLM-6b**](https://huggingface.co/Deci/DeciLM-6b) - Deci 🤗
- [**GOAT-7B-Community**](https://huggingface.co/GOAT-AI/GOAT-7B-Community) - GOAT-AI 🤗
- [**openchat**](https://github.com/imoneoi/openchat) - imoneoi ![Star](https://img.shields.io/github/stars/imoneoi/openchat.svg?style=social&label=Star)

	 *OpenChat: Less is More for Open-source Models* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652347745&idx=2&sn=67b67467611ffbe6c739577d5894693a))
- [**GPT-4-LLM**](https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM) - Instruction-Tuning-with-GPT-4 ![Star](https://img.shields.io/github/stars/Instruction-Tuning-with-GPT-4/GPT-4-LLM.svg?style=social&label=Star)

	 *Instruction Tuning with GPT-4*
- **Instruction Tuning with GPT-4**, `arXiv, 2304.03277`, [arxiv](http://arxiv.org/abs/2304.03277v1), [pdf](http://arxiv.org/pdf/2304.03277v1.pdf), cication: [**182**](https://scholar.google.com/scholar?cites=9181878060529717689&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Baolin Peng, Chunyuan Li, Pengcheng He, Michel Galley, Jianfeng Gao* · ([instruction-tuning-with-gpt-4.github](https://instruction-tuning-with-gpt-4.github.io/))
- [**deepseek-coder-7b-instruct**](https://huggingface.co/spaces/deepseek-ai/deepseek-coder-7b-instruct) - deepseek-ai 🤗
- [**UltraChat**](https://github.com/thunlp/UltraChat) - thunlp ![Star](https://img.shields.io/github/stars/thunlp/UltraChat.svg?style=social&label=Star)

	 *Large-scale, Informative, and Diverse Multi-round Chat Data (and Models)* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247604939&idx=3&sn=515e3e97c65846da04c361d1eec67b94)) · ([qbitai](https://www.qbitai.com/2023/10/89903.html))
- **How Far Can Camels Go? Exploring the State of Instruction Tuning on Open
  Resources**, `arXiv, 2306.04751`, [arxiv](http://arxiv.org/abs/2306.04751v2), [pdf](http://arxiv.org/pdf/2306.04751v2.pdf), cication: [**40**](https://scholar.google.com/scholar?cites=4520548076856064571&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yizhong Wang, Hamish Ivison, Pradeep Dasigi, Jack Hessel, Tushar Khot, Khyathi Raghavi Chandu, David Wadden, Kelsey MacMillan, Noah A. Smith, Iz Beltagy* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-01-2)) · ([open-instruct](https://github.com/allenai/open-instruct) - allenai) ![Star](https://img.shields.io/github/stars/allenai/open-instruct.svg?style=social&label=Star)

# Mulitlingual (chinese)

## Foundation
- **ChuXin: 1.6B Technical Report**, `arXiv, 2405.04828`, [arxiv](http://arxiv.org/abs/2405.04828v1), [pdf](http://arxiv.org/pdf/2405.04828v1.pdf), cication: [**-1**](None)

	 *Xiaomin Zhuang, Yufan Jiang, Qiaozhi He, Zhihua Wu*
- **Tele-FLM Technical Report**, `arXiv, 2404.16645`, [arxiv](http://arxiv.org/abs/2404.16645v1), [pdf](http://arxiv.org/pdf/2404.16645v1.pdf), cication: [**-1**](None)

	 *Xiang Li, Yiqun Yao, Xin Jiang, Xuezhi Fang, Chao Wang, Xinzhang Liu, Zihan Wang, Yu Zhao, Xin Wang, Yuyao Huang*
- **Chinese Tiny LLM: Pretraining a Chinese-Centric Large Language Model**, `arXiv, 2404.04167`, [arxiv](http://arxiv.org/abs/2404.04167v1), [pdf](http://arxiv.org/pdf/2404.04167v1.pdf), cication: [**-1**](None)

	 *Xinrun Du, Zhouliang Yu, Songyang Gao, Ding Pan, Yuyang Cheng, Ziyang Ma, Ruibin Yuan, Xingwei Qu, Jiaheng Liu, Tianyu Zheng* · ([huggingface](https://huggingface.co/collections/m-a-p/chinese-tiny-llm-660d0133dff6856f94ce0fc6))

- [**Mengzi3**](https://github.com/Langboat/Mengzi3) - Langboat ![Star](https://img.shields.io/github/stars/Langboat/Mengzi3.svg?style=social&label=Star)

	 · ([qbitai](https://www.qbitai.com/2024/04/132445.html))
- [**MiniCPM**](https://github.com/OpenBMB/MiniCPM) - OpenBMB ![Star](https://img.shields.io/github/stars/OpenBMB/MiniCPM.svg?style=social&label=Star)

	 *MiniCPM-2.4B: An end-side LLM outperforms Llama2-13B.*

	 · ([huggingface](https://huggingface.co/openbmb))

	 · ([shengdinghu.notion](https://shengdinghu.notion.site/MiniCPM-Unveiling-the-Potential-of-End-side-Large-Language-Models-d4d3a8c426424654a4e80e42a711cb20))
- [iFlytekSpark-13B: 讯飞星火开源-13B（iFlytekSpark-13B）](https://gitee.com/iflytekopensource/iFlytekSpark-13B)
- **Orion-14B: Open-source Multilingual Large Language Models**, `arXiv, 2401.12246`, [arxiv](http://arxiv.org/abs/2401.12246v1), [pdf](http://arxiv.org/pdf/2401.12246v1.pdf), cication: [**-1**](None)

	 *Du Chen, Yi Huang, Xiaopu Li, Yongqiang Li, Yongqiang Liu, Haihui Pan, Leichao Xu, Dacheng Zhang, Zhipeng Zhang, Kun Han*
- [**Orion**](https://github.com/OrionStarAI/Orion) - OrionStarAI ![Star](https://img.shields.io/github/stars/OrionStarAI/Orion.svg?style=social&label=Star)

	 *Orion-14B is a family of models includes a 14B foundation LLM, and a series of models: a chat model, a long context model, a quantized model, a RAG fine-tuned model, and an Agent fine-tuned model. Orion-14B 系列模型包括一个具有140亿参数的多语言基座大模型以及一系列相关的衍生模型，包括对话模型，长文本模型，量化模型，RAG微调模型，Agent微调模型等。* · ([Orion](https://github.com/OrionStarAI/Orion/blob/master/doc/Orion14B_v3.pdf) - OrionStarAI) ![Star](https://img.shields.io/github/stars/OrionStarAI/Orion.svg?style=social&label=Star)
- **TeleChat Technical Report**, `arXiv, 2401.03804`, [arxiv](http://arxiv.org/abs/2401.03804v1), [pdf](http://arxiv.org/pdf/2401.03804v1.pdf), cication: [**-1**](None)

	 *Zihan Wang, Xinzhang Liu, Shixuan Liu, Yitong Yao, Yuyao Huang, Zhongjiang He, Xuelong Li, Yongxiang Li, Zhonghao Che, Zhaoxi Zhang*
- **YAYI 2: Multilingual Open-Source Large Language Models**, `arXiv, 2312.14862`, [arxiv](http://arxiv.org/abs/2312.14862v1), [pdf](http://arxiv.org/pdf/2312.14862v1.pdf), cication: [**-1**](None)

	 *Yin Luo, Qingchao Kong, Nan Xu, Jia Cao, Bao Hao, Baoyu Qu, Bo Chen, Chao Zhu, Chenyang Zhao, Donglei Zhang*

- **SeaLLMs -- Large Language Models for Southeast Asia**, `arXiv, 2312.00738`, [arxiv](http://arxiv.org/abs/2312.00738v1), [pdf](http://arxiv.org/pdf/2312.00738v1.pdf), cication: [**-1**](None)

	 *Xuan-Phi Nguyen, Wenxuan Zhang, Xin Li, Mahani Aljunied, Qingyu Tan, Liying Cheng, Guanzheng Chen, Yue Deng, Sen Yang, Chaoqun Liu*

	 · ([SeaLLMs](https://github.com/DAMO-NLP-SG/SeaLLMs) - DAMO-NLP-SG) ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/SeaLLMs.svg?style=social&label=Star)
- **YUAN 2.0: A Large Language Model with Localized Filtering-based
  Attention**, `arXiv, 2311.15786`, [arxiv](http://arxiv.org/abs/2311.15786v1), [pdf](http://arxiv.org/pdf/2311.15786v1.pdf), cication: [**-1**](None)

	 *Shaohua Wu, Xudong Zhao, Shenling Wang, Jiangang Luo, Lingjun Li, Xi Chen, Bing Zhao, Wei Wang, Tong Yu, Rongguo Zhang* · ([Yuan-2.0](https://github.com/IEIT-Yuan/Yuan-2.0) - IEIT-Yuan) ![Star](https://img.shields.io/github/stars/IEIT-Yuan/Yuan-2.0.svg?style=social&label=Star)
- **Ziya2: Data-centric Learning is All LLMs Need**, `arXiv, 2311.03301`, [arxiv](http://arxiv.org/abs/2311.03301v1), [pdf](http://arxiv.org/pdf/2311.03301v1.pdf), cication: [**-1**](None)

	 *Ruyi Gan, Ziwei Wu, Renliang Sun, Junyu Lu, Xiaojun Wu, Dixiang Zhang, Kunhao Pan, Ping Yang, Qi Yang, Jiaxing Zhang*

	 · ([huggingface](https://huggingface.co/IDEA-CCNL/Ziya2-13B-Base))

- **Skywork: A More Open Bilingual Foundation Model**, `arXiv, 2310.19341`, [arxiv](http://arxiv.org/abs/2310.19341v1), [pdf](http://arxiv.org/pdf/2310.19341v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=18152031419581471402&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tianwen Wei, Liang Zhao, Lichang Zhang, Bo Zhu, Lijie Wang, Haihua Yang, Biye Li, Cheng Cheng, Weiwei Lü, Rui Hu* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-09-7)) · ([qbitai](https://www.qbitai.com/2023/10/94060.html)) · ([skywork](https://github.com/skyworkai/skywork) - skyworkai) ![Star](https://img.shields.io/github/stars/skyworkai/skywork.svg?style=social&label=Star)
- [**Aquila2**](https://github.com/FlagAI-Open/Aquila2) - FlagAI-Open ![Star](https://img.shields.io/github/stars/FlagAI-Open/Aquila2.svg?style=social&label=Star)

	 *The official repo of Aquila2 series proposed by BAAI, including pretrained & chat large language models.* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652389300&idx=1&sn=bd9a4496d33b5a6209db53c98371d00c))
- [**ColossalAI**](https://github.com/hpcaitech/ColossalAI) - hpcaitech ![Star](https://img.shields.io/github/stars/hpcaitech/ColossalAI.svg?style=social&label=Star)

	 *Making large AI models cheaper, faster and more accessible* · ([qbitai](https://www.qbitai.com/2023/09/86278.html))

- [**VisCPM**](https://github.com/OpenBMB/VisCPM) - OpenBMB ![Star](https://img.shields.io/github/stars/OpenBMB/VisCPM.svg?style=social&label=Star)

	 *基于CPM基础模型的中英双语多模态大模型系列* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-03-3))

### Yi-01
- [Site Unreachable](https://huggingface.co/collections/01-ai/yi-15-2024-05-663f3ecab5f815a3eaca7ca8)
- **Yi: Open Foundation Models by 01.AI**, `arXiv, 2403.04652`, [arxiv](http://arxiv.org/abs/2403.04652v1), [pdf](http://arxiv.org/pdf/2403.04652v1.pdf), cication: [**-1**](None)

	 *01. AI, :, Alex Young, Bei Chen, Chao Li, Chengen Huang, Ge Zhang, Guanwei Zhang, Heng Li, Jiangcheng Zhu*
- [**Yi-9B**](https://huggingface.co/01-ai/Yi-9B) - 01-ai 🤗
- [**Yi**](https://github.com/01-ai/Yi) - 01-ai ![Star](https://img.shields.io/github/stars/01-ai/Yi.svg?style=social&label=Star)

	 *A series of large language models trained from scratch by developers @01-ai*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-12-11-15))

### InterLM
- **InternLM2 Technical Report**, `arXiv, 2403.17297`, [arxiv](http://arxiv.org/abs/2403.17297v1), [pdf](http://arxiv.org/pdf/2403.17297v1.pdf), cication: [**-1**](None)

	 *Zheng Cai, Maosong Cao, Haojiong Chen, Kai Chen, Keyu Chen, Xin Chen, Xun Chen, Zehui Chen, Zhi Chen, Pei Chu*
- [**InternLM**](https://github.com/InternLM/InternLM) - InternLM ![Star](https://img.shields.io/github/stars/InternLM/InternLM.svg?style=social&label=Star)

	 *InternLM has open-sourced a 7 billion parameter base model, a chat model tailored for practical scenarios and the training system.* · ([qbitai](https://www.qbitai.com/2023/09/85229.html)) · ([qbitai](https://www.qbitai.com/2023/08/78638.html))

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652433445&idx=1&sn=0ee21f65b045cbedc99676144d66a502)) · ([huggingface](https://huggingface.co/internlm))
- [**internlm2-chat-7b**](https://huggingface.co/internlm/internlm2-chat-7b) - internlm 🤗
### DeepSeek 
- [**DeepSeek-V2**](https://github.com/deepseek-ai/DeepSeek-V2) - deepseek-ai ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2.svg?style=social&label=Star)

	 · ([DeepSeek-V2](https://github.com/deepseek-ai/DeepSeek-V2/blob/main/deepseek-v2-tech-report.pdf) - deepseek-ai) ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2.svg?style=social&label=Star)
- **DeepSeek-Coder: When the Large Language Model Meets Programming -- The
  Rise of Code Intelligence**, `arXiv, 2401.14196`, [arxiv](http://arxiv.org/abs/2401.14196v1), [pdf](http://arxiv.org/pdf/2401.14196v1.pdf), cication: [**-1**](None)

	 *Daya Guo, Qihao Zhu, Dejian Yang, Zhenda Xie, Kai Dong, Wentao Zhang, Guanting Chen, Xiao Bi, Y. Wu, Y. K. Li*
- [**DeepSeek-MoE**](https://github.com/deepseek-ai/DeepSeek-MoE) - deepseek-ai ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-MoE.svg?style=social&label=Star)

	 · ([huggingface](https://huggingface.co/deepseek-ai/deepseek-moe-16b-chat))
- [**DeepSeek-LLM**](https://github.com/deepseek-ai/DeepSeek-LLM) - deepseek-ai ![Star](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-LLM.svg?style=social&label=Star)

	 *DeepSeek LLM: Let there be answers* · ([huggingface](https://huggingface.co/deepseek-ai)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s/Zj7gPGqJ8UTTxp1umfWjKQ))
- [Fetching Title#j2s8](https://huggingface.co/spaces/deepseek-ai/DeepSeek-VL-7B)

### Xverse
 - [GitHub - xverse-ai/XVERSE-65B: XVERSE-65B: A multilingual large language model developed by XVERSE Technology Inc.](https://github.com/xverse-ai/XVERSE-65B)

	 · ([huggingface](https://huggingface.co/xverse/XVERSE-65B)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-11-06-10))
- [**XVERSE-13B**](https://github.com/xverse-ai/XVERSE-13B) - xverse-ai ![Star](https://img.shields.io/github/stars/xverse-ai/XVERSE-13B.svg?style=social&label=Star)

	 *XVERSE-13B: A multilingual large language model developed by XVERSE Technology Inc.* · ([qbitai](https://www.qbitai.com/2023/08/74566.html)) · ([huggingface](https://huggingface.co/xverse/XVERSE-13B))
 - [xverse/XVERSE-13B-256K · Hugging Face](https://huggingface.co/xverse/XVERSE-13B-256K)
 
### Qwen
- [Qwen1.5-110B-Chat · 模型库](https://modelscope.cn/models/qwen/Qwen1.5-110B-Chat/summary)
- [**Qwen1.5-110B-Chat-demo**](https://huggingface.co/spaces/Qwen/Qwen1.5-110B-Chat-demo) - Qwen 🤗
- [**Qwen1.5-32B**](https://huggingface.co/Qwen/Qwen1.5-32B) - Qwen 🤗
- [Qwen1.5-32B: Fitting the Capstone of the Qwen1.5 Language Model Series | Qwen](https://qwenlm.github.io/blog/qwen1.5-32b/)
- [**Qwen-Agent**](https://github.com/QwenLM/Qwen-Agent) - QwenLM ![Star](https://img.shields.io/github/stars/QwenLM/Qwen-Agent.svg?style=social&label=Star)

	 *Agent framework and applications built upon Qwen1.5, featuring Function Calling, Code Interpreter, RAG, and Chrome extension.*
- [**Qwen1.5**](https://github.com/QwenLM/Qwen1.5) - QwenLM ![Star](https://img.shields.io/github/stars/QwenLM/Qwen1.5.svg?style=social&label=Star)

	 *Qwen1.5 is the improved version of Qwen, the large language model series developed by Qwen team, Alibaba Cloud.* · ([qwenlm.github](https://qwenlm.github.io/))
- [**Qwen**](https://github.com/QwenLM/Qwen) - QwenLM ![Star](https://img.shields.io/github/stars/QwenLM/Qwen.svg?style=social&label=Star)

	 *The official repo of Qwen (通义千问) chat & pretrained large language model proposed by Alibaba Cloud.*
	 - [国产720亿参数开源免费模型来了！对标Llama2 70B，一手实测在此 | 量子位](https://www.qbitai.com/2023/12/102355.html)
- [**Qwen-7B**](https://github.com/QwenLM/Qwen-7B) - QwenLM ![Star](https://img.shields.io/github/stars/QwenLM/Qwen-7B.svg?style=social&label=Star)

	 *The official repo of Qwen-7B (通义千问-7B) chat & pretrained large language model proposed by Alibaba Cloud.* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494650&idx=1&sn=fbeb1cc57092931966b3e57f8733ed82)) · ([qbitai](https://www.qbitai.com/2023/09/86450.html))
- [**Qwen1.5-MoE-A2.7B**](https://huggingface.co/Qwen/Qwen1.5-MoE-A2.7B) - Qwen 🤗
- [**qwen1.5-MoE-A2.7B-Chat-demo**](https://huggingface.co/spaces/Qwen/qwen1.5-MoE-A2.7B-Chat-demo) - Qwen 🤗
- [**Qwen-72B-Chat-Demo**](https://huggingface.co/spaces/Qwen/Qwen-72B-Chat-Demo) - Qwen 🤗
- [Quyen - a vilm Collection](https://huggingface.co/collections/vilm/quyen-65bc71a29fa020161bc87859)
- [**d-Qwen1.5-0.5B**](https://huggingface.co/aloobun/d-Qwen1.5-0.5B?utm_source=ainews&utm_medium=email&utm_campaign=ainews-mm1-apples-first-large-multimodal-model) - aloobun 🤗
### Baichuan
- **Baichuan 2: Open Large-scale Language Models**, `arXiv, 2309.10305`, [arxiv](http://arxiv.org/abs/2309.10305v2), [pdf](http://arxiv.org/pdf/2309.10305v2.pdf), cication: [**16**](https://scholar.google.com/scholar?cites=11092587028861989085&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Aiyuan Yang, Bin Xiao, Bingning Wang, Borong Zhang, Ce Bian, Chao Yin, Chenxu Lv, Da Pan, Dian Wang, Dong Yan* · ([Baichuan2](https://github.com/baichuan-inc/Baichuan2) - baichuan-inc) ![Star](https://img.shields.io/github/stars/baichuan-inc/Baichuan2.svg?style=social&label=Star) · ([cdn.baichuan-ai](https://cdn.baichuan-ai.com/paper/Baichuan2-technical-report.pdf)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494563&idx=1&sn=9c5e8f33f6820532db15b985aecdee8a)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-06-6))
- [**Baichuan-13B**](https://github.com/baichuan-inc/Baichuan-13B) - baichuan-inc ![Star](https://img.shields.io/github/stars/baichuan-inc/Baichuan-13B.svg?style=social&label=Star)

	 *A 13B large language model developed by Baichuan Intelligent Technology* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652350213&idx=1&sn=cd2cc61763c7512ea61fb117e2c56e20))
- [**baichuan-7B**](https://github.com/baichuan-inc/baichuan-7B) - baichuan-inc ![Star](https://img.shields.io/github/stars/baichuan-inc/baichuan-7B.svg?style=social&label=Star)

	 *A large-scale 7B pretraining language model developed by BaiChuan-Inc.*

### ChatGLM
- [**ChatGLM3**](https://github.com/THUDM/ChatGLM3) - THUDM ![Star](https://img.shields.io/github/stars/THUDM/ChatGLM3.svg?style=social&label=Star)

	 *ChatGLM3 series: Open Bilingual Chat LLMs | 开源双语对话语言模型* · ([qbitai](https://www.qbitai.com/2023/10/93519.html))
- [**ChatGLM2-6B**](https://github.com/THUDM/ChatGLM2-6B) - THUDM ![Star](https://img.shields.io/github/stars/THUDM/ChatGLM2-6B.svg?style=social&label=Star)

	 *ChatGLM2-6B: An Open Bilingual Chat LLM | 开源双语对话语言模型* · ([qbitai](https://www.qbitai.com/2023/06/64023.html))
- [**chatglm.cpp**](https://github.com/li-plus/chatglm.cpp) - li-plus ![Star](https://img.shields.io/github/stars/li-plus/chatglm.cpp.svg?style=social&label=Star)

	 *C++ implementation of ChatGLM-6B & ChatGLM2-6B*
- [**TigerBot**](https://github.com/TigerResearch/TigerBot) - TigerResearch ![Star](https://img.shields.io/github/stars/TigerResearch/TigerBot.svg?style=social&label=Star)

	 *TigerBot: A multi-language multi-task LLM* · ([qbitai](https://www.qbitai.com/2023/06/59416.html))

## Finetuning
- [**Llama-Chinese**](https://github.com/LlamaFamily/Llama-Chinese) - LlamaFamily ![Star](https://img.shields.io/github/stars/LlamaFamily/Llama-Chinese.svg?style=social&label=Star)

	 *Llama中文社区，Llama3在线体验和微调模型已开放，实时汇总最新Llama3学习资料，已将所有代码更新适配Llama3，构建最好的中文Llama大模型，完全开源可商用*
- [**llama3-Chinese-chat**](https://github.com/CrazyBoyM/llama3-Chinese-chat) - CrazyBoyM ![Star](https://img.shields.io/github/stars/CrazyBoyM/llama3-Chinese-chat.svg?style=social&label=Star)

	 *Llama3 中文仓库（聚合资料：各种网友及厂商微调、魔改版本有趣权重 & 训练、推理、部署教程视频 & 文档）*
- **Rethinking LLM Language Adaptation: A Case Study on Chinese Mixtral**, `arXiv, 2403.01851`, [arxiv](http://arxiv.org/abs/2403.01851v1), [pdf](http://arxiv.org/pdf/2403.01851v1.pdf), cication: [**-1**](None)

	 *Yiming Cui, Xin Yao* · ([Chinese-Mixtral](https://github.com/ymcui/Chinese-Mixtral) - ymcui) ![Star](https://img.shields.io/github/stars/ymcui/Chinese-Mixtral.svg?style=social&label=Star)
- **Aurora:Activating Chinese chat capability for Mistral-8x7B sparse
  Mixture-of-Experts through Instruction-Tuning**, `arXiv, 2312.14557`, [arxiv](http://arxiv.org/abs/2312.14557v1), [pdf](http://arxiv.org/pdf/2312.14557v1.pdf), cication: [**-1**](None)

	 *Rongsheng Wang, Haoming Chen, Ruizhe Zhou, Yaofei Duan, Kunyan Cai, Han Ma, Jiaxi Cui, Jian Li, Patrick Cheong-Iao Pang, Yapeng Wang*

	 · ([Aurora](https://github.com/WangRongsheng/Aurora) - WangRongsheng) ![Star](https://img.shields.io/github/stars/WangRongsheng/Aurora.svg?style=social&label=Star)
- [**Taiwan-LLaMa**](https://github.com/MiuLab/Taiwan-LLaMa) - MiuLab ![Star](https://img.shields.io/github/stars/MiuLab/Taiwan-LLaMa.svg?style=social&label=Star)

	 *Traditional Mandarin LLMs for Taiwan*
- [**Chinese-LLaMA-Alpaca-2**](https://github.com/ymcui/Chinese-LLaMA-Alpaca-2) - ymcui ![Star](https://img.shields.io/github/stars/ymcui/Chinese-LLaMA-Alpaca-2.svg?style=social&label=Star)

	 *中文LLaMA-2 & Alpaca-2大语言模型 (Chinese LLaMA-2 & Alpaca-2 LLMs)*
- [**TransGPT**](https://github.com/DUOMO/TransGPT) - DUOMO ![Star](https://img.shields.io/github/stars/DUOMO/TransGPT.svg?style=social&label=Star)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-07-25-4))
- [**Llama2-Chinese**](https://github.com/FlagAlpha/Llama2-Chinese) - FlagAlpha ![Star](https://img.shields.io/github/stars/FlagAlpha/Llama2-Chinese.svg?style=social&label=Star)

	 *Llama中文社区，最好的中文Llama大模型，完全开源可商用*
- [**Chinese-Llama-2-7b**](https://github.com/LinkSoul-AI/Chinese-Llama-2-7b) - LinkSoul-AI ![Star](https://img.shields.io/github/stars/LinkSoul-AI/Chinese-Llama-2-7b.svg?style=social&label=Star)

	 *开源社区第一个能下载、能运行的中文 LLaMA2 模型！*
- [**ChatGLM-Efficient-Tuning**](https://github.com/hiyouga/ChatGLM-Efficient-Tuning) - hiyouga ![Star](https://img.shields.io/github/stars/hiyouga/ChatGLM-Efficient-Tuning.svg?style=social&label=Star)

	 *Fine-tuning ChatGLM-6B with PEFT | 基于 PEFT 的高效 ChatGLM 微调*
- **BayLing: Bridging Cross-lingual Alignment and Instruction Following
  through Interactive Translation for Large Language Models**, `arXiv, 2306.10968`, [arxiv](http://arxiv.org/abs/2306.10968v2), [pdf](http://arxiv.org/pdf/2306.10968v2.pdf), cication: [**-1**](None)

	 *Shaolei Zhang, Qingkai Fang, Zhuocheng Zhang, Zhengrui Ma, Yan Zhou, Langlin Huang, Mengyu Bu, Shangtong Gui, Yunji Chen, Xilin Chen* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-30-4)) · ([BayLing](https://github.com/ictnlp/BayLing) - ictnlp) ![Star](https://img.shields.io/github/stars/ictnlp/BayLing.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/ICTNLP/bayling-13b-diff))

## Other
- [Gemini 1.5: Unlocking multimodal understanding across millions of tokens of context](https://storage.googleapis.com/deepmind-media/gemini/gemini_v1_5_report.pdf)
- [Gemini: A Family of Highly Capable Multimodal Models](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf)
- [**LLMs-In-China**](https://github.com/wgwang/LLMs-In-China) - wgwang ![Star](https://img.shields.io/github/stars/wgwang/LLMs-In-China.svg?style=social&label=Star)

	 *中国大模型*
- [中文大语言模型赶考：商汤与上海AI Lab等新发布「书生·浦语」 | 机器之心](https://www.jiqizhixin.com/articles/2023-06-07-3)
- [ChatGLM2保姆级微调教程\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1ds4y1F74y?t=36.9)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s/Lf70i8M0KNDs9ZB8H32h4w))

# Extra
- **SUTRA: Scalable Multilingual Language Model Architecture**, `arXiv, 2405.06694`, [arxiv](http://arxiv.org/abs/2405.06694v1), [pdf](http://arxiv.org/pdf/2405.06694v1.pdf), cication: [**-1**](None)

	 *Abhijit Bendale, Michael Sapienza, Steven Ripplinger, Simon Gibbs, Jaewon Lee, Pranav Mistry*
- **SambaLingo: Teaching Large Language Models New Languages**, `arXiv, 2404.05829`, [arxiv](http://arxiv.org/abs/2404.05829v1), [pdf](http://arxiv.org/pdf/2404.05829v1.pdf), cication: [**-1**](None)

	 *Zoltan Csaki, Bo Li, Jonathan Li, Qiantong Xu, Pian Pawakapan, Leon Zhang, Yun Du, Hengyu Zhao, Changran Hu, Urmish Thakker*
- **Aurora-M: The First Open Source Multilingual Language Model Red-teamed
  according to the U.S. Executive Order**, `arXiv, 2404.00399`, [arxiv](http://arxiv.org/abs/2404.00399v1), [pdf](http://arxiv.org/pdf/2404.00399v1.pdf), cication: [**-1**](None)

	 *Taishi Nakamura, Mayank Mishra, Simone Tedeschi, Yekun Chai, Jason T Stillerman, Felix Friedrich, Prateek Yadav, Tanmay Laud, Vu Minh Chien, Terry Yue Zhuo* · ([huggingface](https://huggingface.co/collections/aurora-m/aurora-m-models-65fdfdff62471e09812f5407))
- **Sailor: Open Language Models for South-East Asia**, `arXiv, 2404.03608`, [arxiv](http://arxiv.org/abs/2404.03608v1), [pdf](http://arxiv.org/pdf/2404.03608v1.pdf), cication: [**-1**](None)

	 *Longxu Dou, Qian Liu, Guangtao Zeng, Jia Guo, Jiahui Zhou, Wei Lu, Min Lin* · ([twitter](https://twitter.com/sivil_taram/status/1776485535747629371))
	- `earning rate can have an even more impact on the dreaded phenomenon known as 𝚌𝚊𝚝𝚊𝚜𝚝𝚛𝚘𝚙𝚑𝚒𝚌 𝚏𝚘𝚛𝚐𝚎𝚝𝚝𝚒𝚗𝚐?`
- **HyperCLOVA X Technical Report**, `arXiv, 2404.01954`, [arxiv](http://arxiv.org/abs/2404.01954v1), [pdf](http://arxiv.org/pdf/2404.01954v1.pdf), cication: [**-1**](None)

	 *Kang Min Yoo, Jaegeun Han, Sookyo In, Heewon Jeon, Jisu Jeong, Jaewook Kang, Hyunwook Kim, Kyung-Min Kim, Munhyong Kim, Sungju Kim*
- **Nemotron-4 15B Technical Report**, `arXiv, 2402.16819`, [arxiv](http://arxiv.org/abs/2402.16819v2), [pdf](http://arxiv.org/pdf/2402.16819v2.pdf), cication: [**-1**](None)

	 *Jupinder Parmar, Shrimai Prabhumoye, Joseph Jennings, Mostofa Patwary, Sandeep Subramanian, Dan Su, Chen Zhu, Deepak Narayanan, Aastha Jhunjhunwala, Ayush Dattagupta*
- **Aya Model: An Instruction Finetuned Open-Access Multilingual Language
  Model**, `arXiv, 2402.07827`, [arxiv](http://arxiv.org/abs/2402.07827v1), [pdf](http://arxiv.org/pdf/2402.07827v1.pdf), cication: [**-1**](None)

	 *Ahmet Üstün, Viraat Aryabumi, Zheng-Xin Yong, Wei-Yin Ko, Daniel D'souza, Gbemileke Onilude, Neel Bhandari, Shivalika Singh, Hui-Lee Ooi, Amr Kayid* · ([hf](https://hf.co/CohereForAI/aya-101))
- **CroissantLLM: A Truly Bilingual French-English Language Model**, `arXiv, 2402.00786`, [arxiv](http://arxiv.org/abs/2402.00786v1), [pdf](http://arxiv.org/pdf/2402.00786v1.pdf), cication: [**-1**](None)

	 *Manuel Faysse, Patrick Fernandes, Nuno Guerreiro, António Loison, Duarte Alves, Caio Corro, Nicolas Boizard, João Alves, Ricardo Rei, Pedro Martins*
- **MaLA-500: Massive Language Adaptation of Large Language Models**, `arXiv, 2401.13303`, [arxiv](http://arxiv.org/abs/2401.13303v1), [pdf](http://arxiv.org/pdf/2401.13303v1.pdf), cication: [**-1**](None)

	 *Peiqin Lin, Shaoxiong Ji, Jörg Tiedemann, André F. T. Martins, Hinrich Schütze* · ([huggingface](https://huggingface.co/MaLA-LM))
- **Multilingual Instruction Tuning With Just a Pinch of Multilinguality**, `arXiv, 2401.01854`, [arxiv](http://arxiv.org/abs/2401.01854v1), [pdf](http://arxiv.org/pdf/2401.01854v1.pdf), cication: [**-1**](None)

	 *Uri Shaham, Jonathan Herzig, Roee Aharoni, Idan Szpektor, Reut Tsarfaty, Matan Eyal*
- **LLaMA Beyond English: An Empirical Study on Language Capability Transfer**, `arXiv, 2401.01055`, [arxiv](http://arxiv.org/abs/2401.01055v1), [pdf](http://arxiv.org/pdf/2401.01055v1.pdf), cication: [**-1**](None)

	 *Jun Zhao, Zhihao Zhang, Qi Zhang, Tao Gui, Xuanjing Huang*
- [2023, year of open LLMs](https://huggingface.co/blog/2023-in-llms)
- **FinGPT: Large Generative Models for a Small Language**, `arXiv, 2311.05640`, [arxiv](http://arxiv.org/abs/2311.05640v1), [pdf](http://arxiv.org/pdf/2311.05640v1.pdf), cication: [**-1**](None)

	 *Risto Luukkonen, Ville Komulainen, Jouni Luoma, Anni Eskelinen, Jenna Kanerva, Hanna-Mari Kupari, Filip Ginter, Veronika Laippala, Niklas Muennighoff, Aleksandra Piktus* · ([turkunlp](https://turkunlp.org/gpt3-finnish))

# Toolkits
- [**LLMZoo**](https://github.com/FreedomIntelligence/LLMZoo) - FreedomIntelligence ![Star](https://img.shields.io/github/stars/FreedomIntelligence/LLMZoo.svg?style=social&label=Star)

	 *⚡LLM Zoo is a project that provides data, models, and evaluation benchmark for large language models.⚡*

## Products
- [The Claude 3 Model Family: Opus, Sonnet, Haiku](https://www-cdn.anthropic.com/de8ba9b01c9ab7cbabf5c33b80b7bbc618857627/Model_Card_Claude_3.pdf)

	 · ([anthropic](https://www.anthropic.com/news/claude-3-haiku))

# Extra reference
- [Ecosystem Graphs for Foundation Models](https://crfm.stanford.edu/ecosystem-graphs/index.html?mode=table)
- [LLM Collection | Prompt Engineering Guide](https://www.promptingguide.ai/models/collection)
- [**open-llms**](https://github.com/eugeneyan/open-llms) - eugeneyan ![Star](https://img.shields.io/github/stars/eugeneyan/open-llms.svg?style=social&label=Star)

	 *📋 A list of open LLMs available for commercial use.*
- [List of Open Sourced Fine-Tuned Large Language Models (LLM) | by Sung Kim | Medium](https://sungkim11.medium.com/list-of-open-sourced-fine-tuned-large-language-models-llm-8d95a2e0dc76)
- [**Awesome-Chinese-LLM**](https://github.com/HqWu-HITCS/Awesome-Chinese-LLM) - HqWu-HITCS ![Star](https://img.shields.io/github/stars/HqWu-HITCS/Awesome-Chinese-LLM.svg?style=social&label=Star)

	 *整理开源的中文大语言模型，以规模较小、可私有化部署、训练成本较低的模型为主，包括底座模型，垂直领域微调及应用，数据集与教程等。*
- [**self-llm**](https://github.com/datawhalechina/self-llm) - datawhalechina ![Star](https://img.shields.io/github/stars/datawhalechina/self-llm.svg?style=social&label=Star)

	 *《开源大模型食用指南》基于AutoDL快速部署开源大模型，更适合中国宝宝的部署教程*