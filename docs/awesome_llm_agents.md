# Awesome llm agents

- [Awesome llm agents](#awesome-llm-agents)
	- [Survey](#survey)
	- [LLM OS](#llm-os)
	- [Agents](#agents)
		- [Other](#other)
	- [AutoGPT](#autogpt)
		- [Other](#other-1)
	- [Augmented LLM](#augmented-llm)
		- [Other](#other-2)
	- [Web browsing](#web-browsing)
		- [Other](#other-3)
	- [Retrieval agumented generation](#retrieval-agumented-generation)
		- [Embedding](#embedding)
		- [Other](#other-4)
	- [Code Interpreter](#code-interpreter)
	- [GPTs](#gpts)
		- [Plugins](#plugins)
		- [Other](#other-5)
	- [Evaluation](#evaluation)
	- [Other](#other-6)
	- [Vector Database](#vector-database)
		- [Other](#other-7)
	- [Extra reference](#extra-reference)

## Survey
- **RAG and RAU: A Survey on Retrieval-Augmented Language Model in Natural
  Language Processing**, `arXiv, 2404.19543`, [arxiv](http://arxiv.org/abs/2404.19543v1), [pdf](http://arxiv.org/pdf/2404.19543v1.pdf), cication: [**-1**](None)

	 *Yucheng Hu, Yuxing Lu* · ([ralm_survey](https://github.com/2471023025/ralm_survey) - 2471023025) ![Star](https://img.shields.io/github/stars/2471023025/ralm_survey.svg?style=social&label=Star)
- **The Landscape of Emerging AI Agent Architectures for Reasoning,
  Planning, and Tool Calling: A Survey**, `arXiv, 2404.11584`, [arxiv](http://arxiv.org/abs/2404.11584v1), [pdf](http://arxiv.org/pdf/2404.11584v1.pdf), cication: [**-1**](None)

	 *Tula Masterman, Sandi Besen, Mason Sawtell, Alex Chao*
- **Retrieval-Augmented Generation for AI-Generated Content: A Survey**, `arXiv, 2402.19473`, [arxiv](http://arxiv.org/abs/2402.19473v1), [pdf](http://arxiv.org/pdf/2402.19473v1.pdf), cication: [**-1**](None)

	 *Penghao Zhao, Hailin Zhang, Qinhan Yu, Zhengren Wang, Yunteng Geng, Fangcheng Fu, Ling Yang, Wentao Zhang, Bin Cui* · ([RAG-Survey](https://github.com/hymie122/RAG-Survey) - hymie122) ![Star](https://img.shields.io/github/stars/hymie122/RAG-Survey.svg?style=social&label=Star)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495643&idx=2&sn=f759dc738477d76143ffc53a043b398c&poc_token=HPiN6mWjzo5Wn8_C9o639UGw2ABkm8pA7X9RusYq))
- **Large Multimodal Agents: A Survey**, `arXiv, 2402.15116`, [arxiv](http://arxiv.org/abs/2402.15116v1), [pdf](http://arxiv.org/pdf/2402.15116v1.pdf), cication: [**-1**](None)

	 *Junlin Xie, Zhihong Chen, Ruifei Zhang, Xiang Wan, Guanbin Li*

	 · ([awesome-large-multimodal-agents](https://github.com/jun0wanan/awesome-large-multimodal-agents) - jun0wanan) ![Star](https://img.shields.io/github/stars/jun0wanan/awesome-large-multimodal-agents.svg?style=social&label=Star)
- **Large Language Model based Multi-Agents: A Survey of Progress and
  Challenges**, `arXiv, 2402.01680`, [arxiv](http://arxiv.org/abs/2402.01680v1), [pdf](http://arxiv.org/pdf/2402.01680v1.pdf), cication: [**-1**](None)

	 *Taicheng Guo, Xiuying Chen, Yaqi Wang, Ruidi Chang, Shichao Pei, Nitesh V. Chawla, Olaf Wiest, Xiangliang Zhang*
- **Personal LLM Agents: Insights and Survey about the Capability,
  Efficiency and Security**, `arXiv, 2401.05459`, [arxiv](http://arxiv.org/abs/2401.05459v1), [pdf](http://arxiv.org/pdf/2401.05459v1.pdf), cication: [**-1**](None)

	 *Yuanchun Li, Hao Wen, Weijun Wang, Xiangyu Li, Yizhen Yuan, Guohong Liu, Jiacheng Liu, Wenxing Xu, Xiang Wang, Yi Sun* · ([Personal_LLM_Agents_Survey](https://github.com/MobileLLM/Personal_LLM_Agents_Survey) - MobileLLM) ![Star](https://img.shields.io/github/stars/MobileLLM/Personal_LLM_Agents_Survey.svg?style=social&label=Star)
- **Retrieval-Augmented Generation for Large Language Models: A Survey**, `arXiv, 2312.10997`, [arxiv](http://arxiv.org/abs/2312.10997v1), [pdf](http://arxiv.org/pdf/2312.10997v1.pdf), cication: [**-1**](None)

	 *Yunfan Gao, Yun Xiong, Xinyu Gao, Kangxiang Jia, Jinliu Pan, Yuxi Bi, Yi Dai, Jiawei Sun, Haofen Wang* · ([rag-survey](https://github.com/tongji-kgllm/rag-survey) - tongji-kgllm) ![Star](https://img.shields.io/github/stars/tongji-kgllm/rag-survey.svg?style=social&label=Star)
- **Large Language Models Empowered Agent-based Modeling and Simulation: A
  Survey and Perspectives**, `arXiv, 2312.11970`, [arxiv](http://arxiv.org/abs/2312.11970v1), [pdf](http://arxiv.org/pdf/2312.11970v1.pdf), cication: [**-1**](None)

	 *Chen Gao, Xiaochong Lan, Nian Li, Yuan Yuan, Jingtao Ding, Zhilun Zhou, Fengli Xu, Yong Li* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652430840&idx=5&sn=5a68ba11dce9d88540f297c2aa594e80))
- [**LLM Powered Autonomous Agents | Lil'Log**](https://lilianweng.github.io/posts/2023-06-23-agent/)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652350213&idx=4&sn=47bef78ae85d99fccc45487e2fb1ff6b))
 
## LLM OS
- **AIOS: LLM Agent Operating System**, `arXiv, 2403.16971`, [arxiv](http://arxiv.org/abs/2403.16971v2), [pdf](http://arxiv.org/pdf/2403.16971v2.pdf), cication: [**-1**](None)

	 *Kai Mei, Zelong Li, Shuyuan Xu, Ruosong Ye, Yingqiang Ge, Yongfeng Zhang*

	 · ([AIOS](https://github.com/agiresearch/AIOS) - agiresearch) ![Star](https://img.shields.io/github/stars/agiresearch/AIOS.svg?style=social&label=Star)
- [**01**](https://github.com/OpenInterpreter/01) - OpenInterpreter ![Star](https://img.shields.io/github/stars/OpenInterpreter/01.svg?style=social&label=Star)

	 *The open-source language model computer*

	 · ([qbitai](https://www.qbitai.com/2024/03/129864.html))
- **UFO: A UI-Focused Agent for Windows OS Interaction**, `arXiv, 2402.07939`, [arxiv](http://arxiv.org/abs/2402.07939v1), [pdf](http://arxiv.org/pdf/2402.07939v1.pdf), cication: [**-1**](None)

	 *Chaoyun Zhang, Liqun Li, Shilin He, Xu Zhang, Bo Qiao, Si Qin, Minghua Ma, Yu Kang, Qingwei Lin, Saravan Rajmohan* · ([UFO](https://github.com/microsoft/UFO) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/UFO.svg?style=social&label=Star)
- **OS-Copilot: Towards Generalist Computer Agents with Self-Improvement**, `arXiv, 2402.07456`, [arxiv](http://arxiv.org/abs/2402.07456v2), [pdf](http://arxiv.org/pdf/2402.07456v2.pdf), cication: [**-1**](None)

	 *Zhiyong Wu, Chengcheng Han, Zichen Ding, Zhenmin Weng, Zhoumianze Liu, Shunyu Yao, Tao Yu, Lingpeng Kong*

	 · ([FRIDAY](https://github.com/OS-Copilot/FRIDAY) - OS-Copilot) ![Star](https://img.shields.io/github/stars/OS-Copilot/FRIDAY.svg?style=social&label=Star)
- [At the Intersection of LLMs and Kernels - Research Roundup](https://charlesfrye.github.io/programming/2023/11/10/llms-systems.html)
- [**llama2.c**](https://github.com/trholding/llama2.c) - trholding ![Star](https://img.shields.io/github/stars/trholding/llama2.c.svg?style=social&label=Star)

	 *Llama 2 Everywhere (L2E)* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-07-14))
	
- [**MemGPT**](https://github.com/cpacker/MemGPT) - cpacker ![Star](https://img.shields.io/github/stars/cpacker/MemGPT.svg?style=social&label=Star)

	 *Teaching LLMs memory management for unbounded context 📚🦙*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-18-4))
## Agents
- [**pywinassistant**](https://github.com/a-real-ai/pywinassistant) - a-real-ai ![Star](https://img.shields.io/github/stars/a-real-ai/pywinassistant.svg?style=social&label=Star)

	 *The first open source Large Action Model generalist Artificial Narrow Intelligence that controls completely human user interfaces by only using natural language. PyWinAssistant utilizes Visualization-of-Thought Elicits Spatial Reasoning in Large Language Models.*
- [**agentkit**](https://github.com/holmeswww/agentkit) - holmeswww ![Star](https://img.shields.io/github/stars/holmeswww/agentkit.svg?style=social&label=Star)

	 *An intuitive LLM prompting framework for multifunctional agents, by explicitly constructing a complex "thought process" from simple natural language prompts.*
- **FlowMind: Automatic Workflow Generation with LLMs**, `arXiv, 2404.13050`, [arxiv](http://arxiv.org/abs/2404.13050v1), [pdf](http://arxiv.org/pdf/2404.13050v1.pdf), cication: [**-1**](None)

	 *Zhen Zeng, William Watson, Nicole Cho, Saba Rahimi, Shayleen Reynolds, Tucker Balch, Manuela Veloso*
- [**maestro**](https://github.com/Doriandarko/maestro) - Doriandarko ![Star](https://img.shields.io/github/stars/Doriandarko/maestro.svg?style=social&label=Star)

	 *A framework for Claude Opus to intelligently orchestrate subagents.*
- **Scaling Instructable Agents Across Many Simulated Worlds**, `arXiv, 2404.10179`, [arxiv](http://arxiv.org/abs/2404.10179v2), [pdf](http://arxiv.org/pdf/2404.10179v2.pdf), cication: [**-1**](None)

	 *SIMA Team, Maria Abi Raad, Arun Ahuja, Catarina Barros, Frederic Besse, Andrew Bolt, Adrian Bolton, Bethanie Brownfield, Gavin Buttimore, Max Cant*
- **Autonomous Evaluation and Refinement of Digital Agents**, `arXiv, 2404.06474`, [arxiv](http://arxiv.org/abs/2404.06474v2), [pdf](http://arxiv.org/pdf/2404.06474v2.pdf), cication: [**-1**](None)

	 *Jiayi Pan, Yichi Zhang, Nicholas Tomlin, Yifei Zhou, Sergey Levine, Alane Suhr* · ([Agent-Eval-Refine](https://github.com/Berkeley-NLP/Agent-Eval-Refine) - Berkeley-NLP) ![Star](https://img.shields.io/github/stars/Berkeley-NLP/Agent-Eval-Refine.svg?style=social&label=Star)
- **More Agents Is All You Need**, `arXiv, 2402.05120`, [arxiv](http://arxiv.org/abs/2402.05120v1), [pdf](http://arxiv.org/pdf/2402.05120v1.pdf), cication: [**-1**](None)

	 *Junyou Li, Qin Zhang, Yangbin Yu, Qiang Fu, Deheng Ye*
- **AgentStudio: A Toolkit for Building General Virtual Agents**, `arXiv, 2403.17918`, [arxiv](http://arxiv.org/abs/2403.17918v1), [pdf](http://arxiv.org/pdf/2403.17918v1.pdf), cication: [**-1**](None)

	 *Longtao Zheng, Zhiyuan Huang, Zhenghai Xue, Xinrun Wang, Bo An, Shuicheng Yan* · ([skyworkai.github](https://skyworkai.github.io/agent-studio/))
- **AllHands: Ask Me Anything on Large-scale Verbatim Feedback via Large
  Language Models**, `arXiv, 2403.15157`, [arxiv](http://arxiv.org/abs/2403.15157v1), [pdf](http://arxiv.org/pdf/2403.15157v1.pdf), cication: [**-1**](None)

	 *Chaoyun Zhang, Zicheng Ma, Yuhao Wu, Shilin He, Si Qin, Minghua Ma, Xiaoting Qin, Yu Kang, Yuyi Liang, Xiaoyu Gou*
- **Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for
  Large Language Models**, `arXiv, 2403.12881`, [arxiv](http://arxiv.org/abs/2403.12881v1), [pdf](http://arxiv.org/pdf/2403.12881v1.pdf), cication: [**-1**](None)

	 *Zehui Chen, Kuikun Liu, Qiuchen Wang, Wenwei Zhang, Jiangning Liu, Dahua Lin, Kai Chen, Feng Zhao* · ([Agent-FLAN](https://github.com/InternLM/Agent-FLAN) - InternLM) ![Star](https://img.shields.io/github/stars/InternLM/Agent-FLAN.svg?style=social&label=Star)
- **SOTOPIA-$π$: Interactive Learning of Socially Intelligent Language
  Agents**, `arXiv, 2403.08715`, [arxiv](http://arxiv.org/abs/2403.08715v2), [pdf](http://arxiv.org/pdf/2403.08715v2.pdf), cication: [**-1**](None)

	 *Ruiyi Wang, Haofei Yu, Wenxin Zhang, Zhengyang Qi, Maarten Sap, Graham Neubig, Yonatan Bisk, Hao Zhu*
- **AgentLite: A Lightweight Library for Building and Advancing
  Task-Oriented LLM Agent System**, `arXiv, 2402.15538`, [arxiv](http://arxiv.org/abs/2402.15538v1), [pdf](http://arxiv.org/pdf/2402.15538v1.pdf), cication: [**-1**](None)

	 *Zhiwei Liu, Weiran Yao, Jianguo Zhang, Liangwei Yang, Zuxin Liu, Juntao Tan, Prafulla K. Choubey, Tian Lan, Jason Wu, Huan Wang*

	 · ([agentlite](https://github.com/salesforceairesearch/agentlite) - salesforceairesearch) ![Star](https://img.shields.io/github/stars/salesforceairesearch/agentlite.svg?style=social&label=Star)
- **KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents**, `arXiv, 2403.03101`, [arxiv](http://arxiv.org/abs/2403.03101v1), [pdf](http://arxiv.org/pdf/2403.03101v1.pdf), cication: [**-1**](None)

	 *Yuqi Zhu, Shuofei Qiao, Yixin Ou, Shumin Deng, Ningyu Zhang, Shiwei Lyu, Yue Shen, Lei Liang, Jinjie Gu, Huajun Chen*

	 · ([KnowAgent](https://github.com/zjunlp/KnowAgent) - zjunlp) ![Star](https://img.shields.io/github/stars/zjunlp/KnowAgent.svg?style=social&label=Star) · ([zjunlp.github](https://zjunlp.github.io/project/KnowAgent/))
- **Trial and Error: Exploration-Based Trajectory Optimization for LLM
  Agents**, `arXiv, 2403.02502`, [arxiv](http://arxiv.org/abs/2403.02502v1), [pdf](http://arxiv.org/pdf/2403.02502v1.pdf), cication: [**-1**](None)

	 *Yifan Song, Da Yin, Xiang Yue, Jie Huang, Sujian Li, Bill Yuchen Lin* · ([ETO](https://github.com/Yifan-Song793/ETO) - Yifan-Song793) ![Star](https://img.shields.io/github/stars/Yifan-Song793/ETO.svg?style=social&label=Star)
- [**Qwen-Agent**](https://github.com/QwenLM/Qwen-Agent) - QwenLM ![Star](https://img.shields.io/github/stars/QwenLM/Qwen-Agent.svg?style=social&label=Star)

	 *Agent framework and applications built upon Qwen1.5, featuring Function Calling, Code Interpreter, RAG, and Chrome extension.*
- **Assisting in Writing Wikipedia-like Articles From Scratch with Large
  Language Models**, `arXiv, 2402.14207`, [arxiv](http://arxiv.org/abs/2402.14207v2), [pdf](http://arxiv.org/pdf/2402.14207v2.pdf), cication: [**-1**](None)

	 *Yijia Shao, Yucheng Jiang, Theodore A. Kanell, Peter Xu, Omar Khattab, Monica S. Lam* · ([storm](https://github.com/stanford-oval/storm) - stanford-oval) ![Star](https://img.shields.io/github/stars/stanford-oval/storm.svg?style=social&label=Star)
- **AgentOhana: Design Unified Data and Training Pipeline for Effective
  Agent Learning**, `arXiv, 2402.15506`, [arxiv](http://arxiv.org/abs/2402.15506v1), [pdf](http://arxiv.org/pdf/2402.15506v1.pdf), cication: [**-1**](None)

	 *Jianguo Zhang, Tian Lan, Rithesh Murthy, Zhiwei Liu, Weiran Yao, Juntao Tan, Thai Hoang, Liangwei Yang, Yihao Feng, Zuxin Liu*
- **AgentScope: A Flexible yet Robust Multi-Agent Platform**, `arXiv, 2402.14034`, [arxiv](http://arxiv.org/abs/2402.14034v1), [pdf](http://arxiv.org/pdf/2402.14034v1.pdf), cication: [**-1**](None)

	 *Dawei Gao, Zitao Li, Weirui Kuang, Xuchen Pan, Daoyuan Chen, Zhijian Ma, Bingchen Qian, Liuyi Yao, Lin Zhu, Chen Cheng* · ([agentscope](https://github.com/modelscope/agentscope) - modelscope) ![Star](https://img.shields.io/github/stars/modelscope/agentscope.svg?style=social&label=Star)
- **LongAgent: Scaling Language Models to 128k Context through Multi-Agent
  Collaboration**, `arXiv, 2402.11550`, [arxiv](http://arxiv.org/abs/2402.11550v1), [pdf](http://arxiv.org/pdf/2402.11550v1.pdf), cication: [**-1**](None)

	 *Jun Zhao, Can Zu, Hao Xu, Yi Lu, Wei He, Yiwen Ding, Tao Gui, Qi Zhang, Xuanjing Huang*
- **Small LLMs Are Weak Tool Learners: A Multi-LLM Agent**, `arXiv, 2401.07324`, [arxiv](http://arxiv.org/abs/2401.07324v3), [pdf](http://arxiv.org/pdf/2401.07324v3.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=2111122559950733757&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Weizhou Shen, Chenliang Li, Hongzhan Chen, Ming Yan, Xiaojun Quan, Hehong Chen, Ji Zhang, Fei Huang* · ([Multi-LLM-agent](https://github.com/X-PLUG/Multi-LLM-agent) - X-PLUG) ![Star](https://img.shields.io/github/stars/X-PLUG/Multi-LLM-agent.svg?style=social&label=Star) · ([qbitai](https://www.qbitai.com/2024/02/120390.html))
- **An Interactive Agent Foundation Model**, `arXiv, 2402.05929`, [arxiv](http://arxiv.org/abs/2402.05929v1), [pdf](http://arxiv.org/pdf/2402.05929v1.pdf), cication: [**-1**](None)

	 *Zane Durante, Bidipta Sarkar, Ran Gong, Rohan Taori, Yusuke Noda, Paul Tang, Ehsan Adeli, Shrinidhi Kowshika Lakshmikanth, Kevin Schulman, Arnold Milstein*
- **More Agents Is All You Need**, `arXiv, 2402.05120`, [arxiv](http://arxiv.org/abs/2402.05120v1), [pdf](http://arxiv.org/pdf/2402.05120v1.pdf), cication: [**-1**](None)

	 *Junyou Li, Qin Zhang, Yangbin Yu, Qiang Fu, Deheng Ye* · ([anonymous.4open](https://anonymous.4open.science/r/more_agent_is_all_you_need))
- **PokéLLMon: A Human-Parity Agent for Pokémon Battles with Large
  Language Models**, `arXiv, 2402.01118`, [arxiv](http://arxiv.org/abs/2402.01118v1), [pdf](http://arxiv.org/pdf/2402.01118v1.pdf), cication: [**-1**](None)

	 *Sihao Hu, Tiansheng Huang, Ling Liu* · ([PokeLLMon](https://github.com/git-disl/PokeLLMon) - git-disl) ![Star](https://img.shields.io/github/stars/git-disl/PokeLLMon.svg?style=social&label=Star) · ([poke-llm-on.github](https://poke-llm-on.github.io/))
- **V-IRL: Grounding Virtual Intelligence in Real Life**, `arXiv, 2402.03310`, [arxiv](http://arxiv.org/abs/2402.03310v1), [pdf](http://arxiv.org/pdf/2402.03310v1.pdf), cication: [**-1**](None)

	 *Jihan Yang, Runyu Ding, Ellis Brown, Xiaojuan Qi, Saining Xie* · ([virl-platform.github](https://virl-platform.github.io/)) · ([VIRL](https://github.com/VIRL-Platform/VIRL) - VIRL-Platform) ![Star](https://img.shields.io/github/stars/VIRL-Platform/VIRL.svg?style=social&label=Star)
- **TravelPlanner: A Benchmark for Real-World Planning with Language Agents**, `arXiv, 2402.01622`, [arxiv](http://arxiv.org/abs/2402.01622v2), [pdf](http://arxiv.org/pdf/2402.01622v2.pdf), cication: [**-1**](None)

	 *Jian Xie, Kai Zhang, Jiangjie Chen, Tinghui Zhu, Renze Lou, Yuandong Tian, Yanghua Xiao, Yu Su* · ([osu-nlp-group.github](https://osu-nlp-group.github.io/TravelPlanner/)) · ([TravelPlanner](https://github.com/OSU-NLP-Group/TravelPlanner) - OSU-NLP-Group) ![Star](https://img.shields.io/github/stars/OSU-NLP-Group/TravelPlanner.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652442972&idx=2&sn=f8a866ff62f5e170fe9eabfb14a5c52f))
- **Investigate-Consolidate-Exploit: A General Strategy for Inter-Task Agent
  Self-Evolution**, `arXiv, 2401.13996`, [arxiv](http://arxiv.org/abs/2401.13996v1), [pdf](http://arxiv.org/pdf/2401.13996v1.pdf), cication: [**-1**](None)

	 *Cheng Qian, Shihao Liang, Yujia Qin, Yining Ye, Xin Cong, Yankai Lin, Yesai Wu, Zhiyuan Liu, Maosong Sun* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-02-06-7))
- **Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual
  Perception**, `arXiv, 2401.16158`, [arxiv](http://arxiv.org/abs/2401.16158v1), [pdf](http://arxiv.org/pdf/2401.16158v1.pdf), cication: [**-1**](None)

	 *Junyang Wang, Haiyang Xu, Jiabo Ye, Ming Yan, Weizhou Shen, Ji Zhang, Fei Huang, Jitao Sang* · ([MobileAgent](https://github.com/X-PLUG/MobileAgent) - X-PLUG) ![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)

	 · ([huggingface](https://huggingface.co/spaces/junyangwang0410/Mobile-Agent))
- **SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents**, `arXiv, 2401.10935`, [arxiv](http://arxiv.org/abs/2401.10935v1), [pdf](http://arxiv.org/pdf/2401.10935v1.pdf), cication: [**-1**](None)

	 *Kanzhi Cheng, Qiushi Sun, Yougang Chu, Fangzhi Xu, Yantao Li, Jianbing Zhang, Zhiyong Wu* · ([SeeClick](https://github.com/njucckevin/SeeClick) - njucckevin) ![Star](https://img.shields.io/github/stars/njucckevin/SeeClick.svg?style=social&label=Star)
- **Investigate-Consolidate-Exploit: A General Strategy for Inter-Task Agent
  Self-Evolution**, `arXiv, 2401.13996`, [arxiv](http://arxiv.org/abs/2401.13996v1), [pdf](http://arxiv.org/pdf/2401.13996v1.pdf), cication: [**-1**](None)

	 *Cheng Qian, Shihao Liang, Yujia Qin, Yining Ye, Xin Cong, Yankai Lin, Yesai Wu, Zhiyuan Liu, Maosong Sun*
- **ChatQA: Building GPT-4 Level Conversational QA Models**, `arXiv, 2401.10225`, [arxiv](http://arxiv.org/abs/2401.10225v1), [pdf](http://arxiv.org/pdf/2401.10225v1.pdf), cication: [**-1**](None)

	 *Zihan Liu, Wei Ping, Rajarshi Roy, Peng Xu, Mohammad Shoeybi, Bryan Catanzaro*
- **Tool-LMM: A Large Multi-Modal Model for Tool Agent Learning**, `arXiv, 2401.10727`, [arxiv](http://arxiv.org/abs/2401.10727v1), [pdf](http://arxiv.org/pdf/2401.10727v1.pdf), cication: [**-1**](None)

	 *Chenyu Wang, Weixin Luo, Qianyu Chen, Haonan Mai, Jindi Guo, Sixun Dong, Xiaohua, Xuan, Zhengxin Li, Lin Ma* · ([Tool-LMM?tab=readme-ov-file](https://github.com/Tool-LMM/Tool-LMM?tab=readme-ov-file) - Tool-LMM) ![Star](https://img.shields.io/github/stars/Tool-LMM/Tool-LMM?tab=readme-ov-file.svg?style=social&label=Star)
- **Bootstrapping LLM-based Task-Oriented Dialogue Agents via Self-Talk**, `arXiv, 2401.05033`, [arxiv](http://arxiv.org/abs/2401.05033v1), [pdf](http://arxiv.org/pdf/2401.05033v1.pdf), cication: [**-1**](None)

	 *Dennis Ulmer, Elman Mansimov, Kaixiang Lin, Justin Sun, Xibin Gao, Yi Zhang*
- **GitAgent: Facilitating Autonomous Agent with GitHub by Tool Extension**, `arXiv, 2312.17294`, [arxiv](http://arxiv.org/abs/2312.17294v1), [pdf](http://arxiv.org/pdf/2312.17294v1.pdf), cication: [**-1**](None)

	 *Bohan Lyu, Xin Cong, Heyang Yu, Pan Yang, Yujia Qin, Yining Ye, Yaxi Lu, Zhong Zhang, Yukun Yan, Yankai Lin*
- **Pangu-Agent: A Fine-Tunable Generalist Agent with Structured Reasoning**, `arXiv, 2312.14878`, [arxiv](http://arxiv.org/abs/2312.14878v1), [pdf](http://arxiv.org/pdf/2312.14878v1.pdf), cication: [**-1**](None)

	 *Filippos Christianos, Georgios Papoudakis, Matthieu Zimmer, Thomas Coste, Zhihao Wu, Jingxuan Chen, Khyati Khandelwal, James Doran, Xidong Feng, Jiacheng Liu*
- **AppAgent: Multimodal Agents as Smartphone Users**, `arXiv, 2312.13771`, [arxiv](http://arxiv.org/abs/2312.13771v1), [pdf](http://arxiv.org/pdf/2312.13771v1.pdf), cication: [**-1**](None)

	 *Zhao Yang, Jiaxuan Liu, Yucheng Han, Xin Chen, Zebiao Huang, Bin Fu, Gang Yu*

	 · ([AppAgent](https://github.com/mnotgod96/AppAgent) - mnotgod96) ![Star](https://img.shields.io/github/stars/mnotgod96/AppAgent.svg?style=social&label=Star)
- **KwaiAgents: Generalized Information-seeking Agent System with Large
  Language Models**, `arXiv, 2312.04889`, [arxiv](http://arxiv.org/abs/2312.04889v1), [pdf](http://arxiv.org/pdf/2312.04889v1.pdf), cication: [**-1**](None)

	 *Haojie Pan, Zepeng Zhai, Hao Yuan, Yaojia Lv, Ruiji Fu, Ming Liu, Zhongyuan Wang, Bing Qin* · ([kwaiagents](https://github.com/kwaikeg/kwaiagents) - kwaikeg) ![Star](https://img.shields.io/github/stars/kwaikeg/kwaiagents.svg?style=social&label=Star)
- **CogAgent: A Visual Language Model for GUI Agents**, `arXiv, 2312.08914`, [arxiv](http://arxiv.org/abs/2312.08914v1), [pdf](http://arxiv.org/pdf/2312.08914v1.pdf), cication: [**-1**](None)

	 *Wenyi Hong, Weihan Wang, Qingsong Lv, Jiazheng Xu, Wenmeng Yu, Junhui Ji, Yan Wang, Zihan Wang, Yuxiao Dong, Ming Ding*

	 · ([CogVLM](https://github.com/THUDM/CogVLM) - THUDM) ![Star](https://img.shields.io/github/stars/THUDM/CogVLM.svg?style=social&label=Star)
- **Creative Agents: Empowering Agents with Imagination for Creative Tasks**, `arXiv, 2312.02519`, [arxiv](http://arxiv.org/abs/2312.02519v1), [pdf](http://arxiv.org/pdf/2312.02519v1.pdf), cication: [**-1**](None)

	 *Chi Zhang, Penglin Cai, Yuhui Fu, Haoqi Yuan, Zongqing Lu*

	 · ([Creative-Agents](https://github.com/PKU-RL/Creative-Agents) - PKU-RL) ![Star](https://img.shields.io/github/stars/PKU-RL/Creative-Agents.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652418572&idx=5&sn=332ac225c1058c20150f8c18697cabc0))
- **An LLM Compiler for Parallel Function Calling**, `arXiv, 2312.04511`, [arxiv](http://arxiv.org/abs/2312.04511v1), [pdf](http://arxiv.org/pdf/2312.04511v1.pdf), cication: [**-1**](None)

	 *Sehoon Kim, Suhong Moon, Ryan Tabrizi, Nicholas Lee, Michael W. Mahoney, Kurt Keutzer, Amir Gholami* · ([llmcompiler](https://github.com/squeezeailab/llmcompiler) - squeezeailab) ![Star](https://img.shields.io/github/stars/squeezeailab/llmcompiler.svg?style=social&label=Star)
- **Beyond ChatBots: ExploreLLM for Structured Thoughts and Personalized
  Model Responses**, `arXiv, 2312.00763`, [arxiv](http://arxiv.org/abs/2312.00763v1), [pdf](http://arxiv.org/pdf/2312.00763v1.pdf), cication: [**-1**](None)

	 *Xiao Ma, Swaroop Mishra, Ariel Liu, Sophie Su, Jilin Chen, Chinmay Kulkarni, Heng-Tze Cheng, Quoc Le, Ed Chi*
- [**taskweaver**](https://github.com/microsoft/taskweaver) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/taskweaver.svg?style=social&label=Star)

	 *A code-first agent framework for seamlessly planning and executing data analytics tasks.*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-01-16))
- **Igniting Language Intelligence: The Hitchhiker's Guide From
  Chain-of-Thought Reasoning to Language Agents**, `arXiv, 2311.11797`, [arxiv](http://arxiv.org/abs/2311.11797v1), [pdf](http://arxiv.org/pdf/2311.11797v1.pdf), cication: [**-1**](None)

	 *Zhuosheng Zhang, Yao Yao, Aston Zhang, Xiangru Tang, Xinbei Ma, Zhiwei He, Yiming Wang, Mark Gerstein, Rui Wang, Gongshen Liu* · ([CoT-Igniting-Agent](https://github.com/Zoeyyao27/CoT-Igniting-Agent) - Zoeyyao27) ![Star](https://img.shields.io/github/stars/Zoeyyao27/CoT-Igniting-Agent.svg?style=social&label=Star)
- **ToolTalk: Evaluating Tool-Usage in a Conversational Setting**, `arXiv, 2311.10775`, [arxiv](http://arxiv.org/abs/2311.10775v1), [pdf](http://arxiv.org/pdf/2311.10775v1.pdf), cication: [**-1**](None)

	 *Nicholas Farn, Richard Shin* · ([ToolTalk](https://github.com/microsoft/ToolTalk) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/ToolTalk.svg?style=social&label=Star)
- **TPTU-v2: Boosting Task Planning and Tool Usage of Large Language
  Model-based Agents in Real-world Systems**, `arXiv, 2311.11315`, [arxiv](http://arxiv.org/abs/2311.11315v1), [pdf](http://arxiv.org/pdf/2311.11315v1.pdf), cication: [**-1**](None)

	 *Yilun Kong, Jingqing Ruan, Yihong Chen, Bin Zhang, Tianpeng Bao, Shiwei Shi, Guoqing Du, Xiaoru Hu, Hangyu Mao, Ziyue Li*
- [**multi-agent-postgres-data-analytics**](https://github.com/disler/multi-agent-postgres-data-analytics) - disler ![Star](https://img.shields.io/github/stars/disler/multi-agent-postgres-data-analytics.svg?style=social&label=Star)

	 *The way we interact with our data is changing.*
- [**ProAgent**](https://github.com/OpenBMB/ProAgent) - OpenBMB ![Star](https://img.shields.io/github/stars/OpenBMB/ProAgent.svg?style=social&label=Star)

	 · ([ProAgent](https://github.com/OpenBMB/ProAgent/blob/main/paper/paper.pdf) - OpenBMB) ![Star](https://img.shields.io/github/stars/OpenBMB/ProAgent.svg?style=social&label=Star)
- **JARVIS-1: Open-World Multi-task Agents with Memory-Augmented Multimodal
  Language Models**, `arXiv, 2311.05997`, [arxiv](http://arxiv.org/abs/2311.05997v1), [pdf](http://arxiv.org/pdf/2311.05997v1.pdf), cication: [**-1**](None)

	 *Zihao Wang, Shaofei Cai, Anji Liu, Yonggang Jin, Jinbing Hou, Bowei Zhang, Haowei Lin, Zhaofeng He, Zilong Zheng, Yaodong Yang* · ([craftjarvis-jarvis1.github](https://craftjarvis-jarvis1.github.io))
- **Lumos: Learning Agents with Unified Data, Modular Design, and
  Open-Source LLMs**, `arXiv, 2311.05657`, [arxiv](http://arxiv.org/abs/2311.05657v1), [pdf](http://arxiv.org/pdf/2311.05657v1.pdf), cication: [**-1**](None)

	 *Da Yin, Faeze Brahman, Abhilasha Ravichander, Khyathi Chandu, Kai-Wei Chang, Yejin Choi, Bill Yuchen Lin* · ([lumos](https://github.com/allenai/lumos) - allenai) ![Star](https://img.shields.io/github/stars/allenai/lumos.svg?style=social&label=Star) · ([allenai.github](https://allenai.github.io/lumos/))
- [**OpenAI_Agent_Swarm**](https://github.com/daveshap/OpenAI_Agent_Swarm) - daveshap ![Star](https://img.shields.io/github/stars/daveshap/OpenAI_Agent_Swarm.svg?style=social&label=Star)

	 *HAAS = Hierarchical Autonomous Agent Swarm - "Resistance is futile!"*
- **LLaVA-Plus: Learning to Use Tools for Creating Multimodal Agents**, `arXiv, 2311.05437`, [arxiv](http://arxiv.org/abs/2311.05437v1), [pdf](http://arxiv.org/pdf/2311.05437v1.pdf), cication: [**-1**](None)

	 *Shilong Liu, Hao Cheng, Haotian Liu, Hao Zhang, Feng Li, Tianhe Ren, Xueyan Zou, Jianwei Yang, Hang Su, Jun Zhu*

- **Octopus: Embodied Vision-Language Programmer from Environmental Feedback**, `arXiv, 2310.08588`, [arxiv](http://arxiv.org/abs/2310.08588v1), [pdf](http://arxiv.org/pdf/2310.08588v1.pdf), cication: [**-1**](None)

	 *Jingkang Yang, Yuhao Dong, Shuai Liu, Bo Li, Ziyue Wang, Chencheng Jiang, Haoran Tan, Jiamu Kang, Yuanhan Zhang, Kaiyang Zhou* · ([Octopus](https://github.com/dongyh20/Octopus) - dongyh20) ![Star](https://img.shields.io/github/stars/dongyh20/Octopus.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652403403&idx=5&sn=8c265c36ba692eb614e537894406b72b))
- **War and Peace (WarAgent): Large Language Model-based Multi-Agent
  Simulation of World Wars**, `arXiv, 2311.17227`, [arxiv](http://arxiv.org/abs/2311.17227v1), [pdf](http://arxiv.org/pdf/2311.17227v1.pdf), cication: [**-1**](None)

	 *Wenyue Hua, Lizhou Fan, Lingyao Li, Kai Mei, Jianchao Ji, Yingqiang Ge, Libby Hemphill, Yongfeng Zhang* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652424662&idx=5&sn=9fcf5d95d12d548f806cd5375257f783))
- **Neural MMO 2.0: A Massively Multi-task Addition to Massively Multi-agent
  Learning**, `arXiv, 2311.03736`, [arxiv](http://arxiv.org/abs/2311.03736v1), [pdf](http://arxiv.org/pdf/2311.03736v1.pdf), cication: [**-1**](None)

	 *Joseph Suárez, Phillip Isola, Kyoung Whan Choe, David Bloomin, Hao Xiang Li, Nikhil Pinnaparaju, Nishaanth Kanna, Daniel Scott, Ryan Sullivan, Rose S. Shuman*
- [From Copilot to CoOrchestration](https://blog.salesforceairesearch.com/from-copilot-to-coorchestration/)
- **OpenAgents: An Open Platform for Language Agents in the Wild**, `arXiv, 2310.10634`, [arxiv](http://arxiv.org/abs/2310.10634v1), [pdf](http://arxiv.org/pdf/2310.10634v1.pdf), cication: [**-1**](None)

	 *Tianbao Xie, Fan Zhou, Zhoujun Cheng, Peng Shi, Luoxuan Weng, Yitao Liu, Toh Jing Hua, Junning Zhao, Qian Liu, Che Liu*
- [**agenttuning**](https://github.com/thudm/agenttuning) - thudm ![Star](https://img.shields.io/github/stars/thudm/agenttuning.svg?style=social&label=Star)

	 *AgentTuning: Enabling Generalized Agent Abilities for LLMs*
- **Humanoid Agents: Platform for Simulating Human-like Generative Agents**, `arXiv, 2310.05418`, [arxiv](http://arxiv.org/abs/2310.05418v1), [pdf](http://arxiv.org/pdf/2310.05418v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=16164127293972935454&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhilin Wang, Yu Ying Chiu, Yu Cheung Chiu* · ([humanoidagents](https://github.com/humanoidagents/humanoidagents) - humanoidagents) ![Star](https://img.shields.io/github/stars/humanoidagents/humanoidagents.svg?style=social&label=Star)
- [**XAgent**](https://github.com/OpenBMB/XAgent) - OpenBMB ![Star](https://img.shields.io/github/stars/OpenBMB/XAgent.svg?style=social&label=Star)

	 *An Autonomous LLM Agent for Complex Task Solving* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-17-7))
- **Reason for Future, Act for Now: A Principled Framework for Autonomous
  LLM Agents with Provable Sample Efficiency**, `arXiv, 2309.17382`, [arxiv](http://arxiv.org/abs/2309.17382v2), [pdf](http://arxiv.org/pdf/2309.17382v2.pdf), cication: [**-1**](None)

	 *Zhihan Liu, Hao Hu, Shenao Zhang, Hongyi Guo, Shuqi Ke, Boyi Liu, Zhaoran Wang*
- **Humanoid Agents: Platform for Simulating Human-like Generative Agents**, `arXiv, 2310.05418`, [arxiv](http://arxiv.org/abs/2310.05418v1), [pdf](http://arxiv.org/pdf/2310.05418v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=16164127293972935454&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhilin Wang, Yu Ying Chiu, Yu Cheung Chiu* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652391398&idx=1&sn=0c2ed56e8721858398a8e3b501349a5c))
- **A Zero-Shot Language Agent for Computer Control with Structured
  Reflection**, `arXiv, 2310.08740`, [arxiv](http://arxiv.org/abs/2310.08740v3), [pdf](http://arxiv.org/pdf/2310.08740v3.pdf), cication: [**-1**](None)

	 *Tao Li, Gang Li, Zhiwei Deng, Bryan Wang, Yang Li*
- **Lemur: Harmonizing Natural Language and Code for Language Agents**, `arXiv, 2310.06830`, [arxiv](http://arxiv.org/abs/2310.06830v1), [pdf](http://arxiv.org/pdf/2310.06830v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=14859965768820951174&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yiheng Xu, Hongjin Su, Chen Xing, Boyu Mi, Qian Liu, Weijia Shi, Binyuan Hui, Fan Zhou, Yitao Liu, Tianbao Xie*
- **EcoAssistant: Using LLM Assistant More Affordably and Accurately**, `arXiv, 2310.03046`, [arxiv](http://arxiv.org/abs/2310.03046v1), [pdf](http://arxiv.org/pdf/2310.03046v1.pdf), cication: [**-1**](None)

	 *Jieyu Zhang, Ranjay Krishna, Ahmed H. Awadallah, Chi Wang*
- [**khoj**](https://github.com/khoj-ai/khoj) - khoj-ai ![Star](https://img.shields.io/github/stars/khoj-ai/khoj.svg?style=social&label=Star)

	 *An AI personal assistant for your digital brain*
- **AssistGPT: A General Multi-modal Assistant that can Plan, Execute,
  Inspect, and Learn**, `arXiv, 2306.08640`, [arxiv](http://arxiv.org/abs/2306.08640v2), [pdf](http://arxiv.org/pdf/2306.08640v2.pdf), cication: [**-1**](None)

	 *Difei Gao, Lei Ji, Luowei Zhou, Kevin Qinghong Lin, Joya Chen, Zihan Fan, Mike Zheng Shou*

- **Suspicion-Agent: Playing Imperfect Information Games with Theory of Mind
  Aware GPT-4**, `arXiv, 2309.17277`, [arxiv](http://arxiv.org/abs/2309.17277v2), [pdf](http://arxiv.org/pdf/2309.17277v2.pdf), cication: [**-1**](None)

	 *Jiaxian Guo, Bo Yang, Paul Yoo, Bill Yuchen Lin, Yusuke Iwasawa, Yutaka Matsuo*
- [**autogen**](https://github.com/microsoft/autogen) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/autogen.svg?style=social&label=Star)

	 *Enable Next-Gen Large Language Model Applications. Join our Discord: https://discord.gg/pAbnFJrkgZ*
- **How FaR Are Large Language Models From Agents with Theory-of-Mind?**, `arXiv, 2310.03051`, [arxiv](http://arxiv.org/abs/2310.03051v1), [pdf](http://arxiv.org/pdf/2310.03051v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=7978252366042560178&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Pei Zhou, Aman Madaan, Srividya Pranavi Potharaju, Aditya Gupta, Kevin R. McKee, Ari Holtzman, Jay Pujara, Xiang Ren, Swaroop Mishra, Aida Nematzadeh* · ([qbitai](https://www.qbitai.com/2023/10/89929.html))
- [**AutoAgents**](https://github.com/LinkSoul-AI/AutoAgents) - LinkSoul-AI ![Star](https://img.shields.io/github/stars/LinkSoul-AI/AutoAgents.svg?style=social&label=Star)

	 *Generate different roles for GPTs to form a collaborative entity for complex tasks.*
- **LASER: LLM Agent with State-Space Exploration for Web Navigation**, `arXiv, 2309.08172`, [arxiv](http://arxiv.org/abs/2309.08172v1), [pdf](http://arxiv.org/pdf/2309.08172v1.pdf), cication: [**-1**](None)

	 *Kaixin Ma, Hongming Zhang, Hongwei Wang, Xiaoman Pan, Dong Yu*
- **Agents: An Open-source Framework for Autonomous Language Agents**, `arXiv, 2309.07870`, [arxiv](http://arxiv.org/abs/2309.07870v2), [pdf](http://arxiv.org/pdf/2309.07870v2.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=17378587224686315113&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wangchunshu Zhou, Yuchen Eleanor Jiang, Long Li, Jialong Wu, Tiannan Wang, Shi Qiu, Jintian Zhang, Jing Chen, Ruipu Wu, Shuai Wang* · ([agents](https://github.com/aiwaves-cn/agents) - aiwaves-cn) ![Star](https://img.shields.io/github/stars/aiwaves-cn/agents.svg?style=social&label=Star)
- [MindAgent: Emergent Gaming Interaction - Microsoft Research](https://www.microsoft.com/en-us/research/publication/mindagent-emergent-gaming-interaction/)

	 · ([qbitai](https://www.qbitai.com/2023/09/85935.html))
- **The Rise and Potential of Large Language Model Based Agents: A Survey**, `arXiv, 2309.07864`, [arxiv](http://arxiv.org/abs/2309.07864v3), [pdf](http://arxiv.org/pdf/2309.07864v3.pdf), cication: [**23**](https://scholar.google.com/scholar?cites=10681175205933279445&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhiheng Xi, Wenxiang Chen, Xin Guo, Wei He, Yiwen Ding, Boyang Hong, Ming Zhang, Junzhe Wang, Senjie Jin, Enyu Zhou* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-09-19-8)) · ([LLM-Agent-Paper-List](https://github.com/WooooDyy/LLM-Agent-Paper-List) - WooooDyy) ![Star](https://img.shields.io/github/stars/WooooDyy/LLM-Agent-Paper-List.svg?style=social&label=Star)
- **Cognitive Architectures for Language Agents**, `arXiv, 2309.02427`, [arxiv](http://arxiv.org/abs/2309.02427v2), [pdf](http://arxiv.org/pdf/2309.02427v2.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=4166085628183562359&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Theodore R. Sumers, Shunyu Yao, Karthik Narasimhan, Thomas L. Griffiths* · ([awesome-language-agents](https://github.com/ysymyth/awesome-language-agents) - ysymyth) ![Star](https://img.shields.io/github/stars/ysymyth/awesome-language-agents.svg?style=social&label=Star)
- **AgentVerse: Facilitating Multi-Agent Collaboration and Exploring
  Emergent Behaviors**, `arXiv, 2308.10848`, [arxiv](http://arxiv.org/abs/2308.10848v3), [pdf](http://arxiv.org/pdf/2308.10848v3.pdf), cication: [**13**](https://scholar.google.com/scholar?cites=13815451266857953260&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Weize Chen, Yusheng Su, Jingwei Zuo, Cheng Yang, Chenfei Yuan, Chi-Min Chan, Heyang Yu, Yaxi Lu, Yi-Hsin Hung, Chen Qian* · ([agentverse](https://github.com/openbmb/agentverse) - openbmb) ![Star](https://img.shields.io/github/stars/openbmb/agentverse.svg?style=social&label=Star)
- [**AI-town**](https://github.com/a16z-infra/AI-town) - a16z-infra ![Star](https://img.shields.io/github/stars/a16z-infra/AI-town.svg?style=social&label=Star)

	 *A MIT-licensed, deployable starter kit for building and customizing your own version of AI town - a virtual town where AI characters live, chat and socialize.*
- **TPTU: Large Language Model-based AI Agents for Task Planning and Tool
  Usage**, `arXiv, 2308.03427`, [arxiv](http://arxiv.org/abs/2308.03427v3), [pdf](http://arxiv.org/pdf/2308.03427v3.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=215173853357937829&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jingqing Ruan, Yihong Chen, Bin Zhang, Zhiwei Xu, Tianpeng Bao, Guoqing Du, Shiwei Shi, Hangyu Mao, Ziyue Li, Xingyu Zeng*
- [SHOW-1 and Showrunner Agents in Multi-Agent Simulations](https://fablestudio.github.io/showrunner-agents/)

	 · ([fablestudio.github](https://fablestudio.github.io/showrunner-agents/)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652355390&idx=2&sn=ebceb562ebbf687157a5e44ff90ad91f))
- **Building Cooperative Embodied Agents Modularly with Large Language
  Models**, `arXiv, 2307.02485`, [arxiv](http://arxiv.org/abs/2307.02485v1), [pdf](http://arxiv.org/pdf/2307.02485v1.pdf), cication: [**-1**](None)

	 *Hongxin Zhang, Weihua Du, Jiaming Shan, Qinhong Zhou, Yilun Du, Joshua B. Tenenbaum, Tianmin Shu, Chuang Gan*

- [**autotab-starter**](https://github.com/Planetary-Computers/autotab-starter) - Planetary-Computers ![Star](https://img.shields.io/github/stars/Planetary-Computers/autotab-starter.svg?style=social&label=Star)

	 *Build browser agents for real world tasks*
- [**openagents**](https://github.com/xlang-ai/openagents) - xlang-ai ![Star](https://img.shields.io/github/stars/xlang-ai/openagents.svg?style=social&label=Star)

	 *OpenAgents: An Open Platform for Language Agents in the Wild*
- [**octopus**](https://github.com/dongyh20/octopus) - dongyh20 ![Star](https://img.shields.io/github/stars/dongyh20/octopus.svg?style=social&label=Star)

	 *🐙Octopus, an embodied vision-language model trained with RLEF, emerging superior in embodied visual planning and programming.*
- [**gollie**](https://github.com/hitz-zentroa/gollie) - hitz-zentroa ![Star](https://img.shields.io/github/stars/hitz-zentroa/gollie.svg?style=social&label=Star)

	 *Guideline following Large Language Model for Information Extraction*
- [NexusRaven-13B: Surpassing the state-of-the-art in open-source function calling LLMs.](https://huggingface.co/Nexusflow/NexusRaven-13B)

	 · ([nexusflow](https://nexusflow.ai/blog))
- **ModelScope-Agent: Building Your Customizable Agent System with
  Open-source Large Language Models**, `arXiv, 2309.00986`, [arxiv](http://arxiv.org/abs/2309.00986v1), [pdf](http://arxiv.org/pdf/2309.00986v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=2246653548879289665&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Chenliang Li, Hehong Chen, Ming Yan, Weizhou Shen, Haiyang Xu, Zhikai Wu, Zhicheng Zhang, Wenmeng Zhou, Yingda Chen, Chen Cheng* · ([modelscope-agent](https://github.com/modelscope/modelscope-agent) - modelscope) ![Star](https://img.shields.io/github/stars/modelscope/modelscope-agent.svg?style=social&label=Star)
- [**trl-text-environment**](https://huggingface.co/spaces/trl-lib/trl-text-environment) - trl-lib 🤗
- [**awesome-ai-devtools**](https://github.com/jamesmurdza/awesome-ai-devtools#agents) - jamesmurdza ![Star](https://img.shields.io/github/stars/jamesmurdza/awesome-ai-devtools.svg?style=social&label=Star)

	 *Curated list of AI-powered developer tools.*
- **TPTU: Large Language Model-based AI Agents for Task Planning and Tool
  Usage**, `arXiv, 2308.03427`, [arxiv](http://arxiv.org/abs/2308.03427v3), [pdf](http://arxiv.org/pdf/2308.03427v3.pdf), cication: [**11**](https://scholar.google.com/scholar?cites=215173853357937829&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jingqing Ruan, Yihong Chen, Bin Zhang, Zhiwei Xu, Tianpeng Bao, Guoqing Du, Shiwei Shi, Hangyu Mao, Ziyue Li, Xingyu Zeng*
- [**functionary**](https://github.com/musabgultekin/functionary) - musabgultekin ![Star](https://img.shields.io/github/stars/musabgultekin/functionary.svg?style=social&label=Star)

	 *Chat language model that can interpret and execute functions/plugins*
- **Tool Documentation Enables Zero-Shot Tool-Usage with Large Language
  Models**, `arXiv, 2308.00675`, [arxiv](http://arxiv.org/abs/2308.00675v1), [pdf](http://arxiv.org/pdf/2308.00675v1.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=10301950723538634763&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Cheng-Yu Hsieh, Si-An Chen, Chun-Liang Li, Yasuhisa Fujii, Alexander Ratner, Chen-Yu Lee, Ranjay Krishna, Tomas Pfister*
- [**gorilla**](https://github.com/ShishirPatil/gorilla) - ShishirPatil ![Star](https://img.shields.io/github/stars/ShishirPatil/gorilla.svg?style=social&label=Star)

	 *Gorilla: An API store for LLMs*
- **ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world
  APIs**, `arXiv, 2307.16789`, [arxiv](http://arxiv.org/abs/2307.16789v2), [pdf](http://arxiv.org/pdf/2307.16789v2.pdf), cication: [**33**](https://scholar.google.com/scholar?cites=18087391995547841318&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yujia Qin, Shihao Liang, Yining Ye, Kunlun Zhu, Lan Yan, Yaxi Lu, Yankai Lin, Xin Cong, Xiangru Tang, Bill Qian* · ([ToolBench](https://github.com/OpenBMB/ToolBench) - OpenBMB) ![Star](https://img.shields.io/github/stars/OpenBMB/ToolBench.svg?style=social&label=Star)
- **Android in the Wild: A Large-Scale Dataset for Android Device Control**, `arXiv, 2307.10088`, [arxiv](http://arxiv.org/abs/2307.10088v2), [pdf](http://arxiv.org/pdf/2307.10088v2.pdf), cication: [**4**](https://scholar.google.com/scholar?cites=12177699480233945897&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Christopher Rawles, Alice Li, Daniel Rodriguez, Oriana Riva, Timothy Lillicrap* · ([google-research](https://github.com/google-research/google-research/tree/master/android_in_the_wild) - google-research) ![Star](https://img.shields.io/github/stars/google-research/google-research.svg?style=social&label=Star)
- [**amadeusgpt**](https://github.com/adaptivemotorcontrollab/amadeusgpt) - adaptivemotorcontrollab ![Star](https://img.shields.io/github/stars/adaptivemotorcontrollab/amadeusgpt.svg?style=social&label=Star)

	 *We turn natural language descriptions of behaviors into machine-executable code*
- **Towards Language Models That Can See: Computer Vision Through the LENS
  of Natural Language**, `arXiv, 2306.16410`, [arxiv](http://arxiv.org/abs/2306.16410v1), [pdf](http://arxiv.org/pdf/2306.16410v1.pdf), cication: [**-1**](None)

	 *William Berrios, Gautam Mittal, Tristan Thrush, Douwe Kiela, Amanpreet Singh* · ([lens](https://github.com/contextualai/lens) - contextualai) ![Star](https://img.shields.io/github/stars/contextualai/lens.svg?style=social&label=Star)
- **ViperGPT: Visual Inference via Python Execution for Reasoning**, `arXiv, 2303.08128`, [arxiv](http://arxiv.org/abs/2303.08128v1), [pdf](http://arxiv.org/pdf/2303.08128v1.pdf), cication: [**76**](https://scholar.google.com/scholar?cites=4650814090908712272&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Dídac Surís, Sachit Menon, Carl Vondrick*
- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging
  Face**, `arXiv, 2303.17580`, [arxiv](http://arxiv.org/abs/2303.17580v3), [pdf](http://arxiv.org/pdf/2303.17580v3.pdf), cication: [**233**](https://scholar.google.com/scholar?cites=14990757005844289549&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang*
- **LOVM: Language-Only Vision Model Selection**, `arXiv, 2306.08893`, [arxiv](http://arxiv.org/abs/2306.08893v1), [pdf](http://arxiv.org/pdf/2306.08893v1.pdf), cication: [**-1**](None)

	 *Orr Zohar, Shih-Cheng Huang, Kuan-Chieh Wang, Serena Yeung*
- **CREATOR: Tool Creation for Disentangling Abstract and Concrete Reasoning
  of Large Language Models**, `arXiv, 2305.14318`, [arxiv](http://arxiv.org/abs/2305.14318v2), [pdf](http://arxiv.org/pdf/2305.14318v2.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=11838226438475363604&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Cheng Qian, Chi Han, Yi R. Fung, Yujia Qin, Zhiyuan Liu, Heng Ji* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-12-4))
- [**gorilla**](https://github.com/ShishirPatil/gorilla/) - ShishirPatil ![Star](https://img.shields.io/github/stars/ShishirPatil/gorilla.svg?style=social&label=Star)

	 *Gorilla: An API store for LLMs* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-05-26-9)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652338143&idx=5&sn=24b350988a7328ac72bfa04a857e000e))
- **ReWOO: Decoupling Reasoning from Observations for Efficient Augmented
  Language Models**, `arXiv, 2305.18323`, [arxiv](http://arxiv.org/abs/2305.18323v1), [pdf](http://arxiv.org/pdf/2305.18323v1.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=16471505160659542910&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Binfeng Xu, Zhiyuan Peng, Bowen Lei, Subhabrata Mukherjee, Yuchen Liu, Dongkuan Xu* · ([rewoo](https://github.com/billxbf/rewoo) - billxbf) ![Star](https://img.shields.io/github/stars/billxbf/rewoo.svg?style=social&label=Star)
- **OlaGPT: Empowering LLMs With Human-like Problem-Solving Abilities**, `arXiv, 2305.16334`, [arxiv](http://arxiv.org/abs/2305.16334v1), [pdf](http://arxiv.org/pdf/2305.16334v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=2252208966238122327&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yuanzhen Xie, Tao Xie, Mingxiong Lin, WenTao Wei, Chenglin Li, Beibei Kong, Lei Chen, Chengxiang Zhuo, Bo Hu, Zang Li* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652336823&idx=4&sn=c0559ee72df731edbb381b7593f623be))
- **Natural Language Commanding via Program Synthesis**, `arXiv, 2306.03460`, [arxiv](http://arxiv.org/abs/2306.03460v1), [pdf](http://arxiv.org/pdf/2306.03460v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=4911123869793861169&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Apurva Gandhi, Thong Q. Nguyen, Huitian Jiao, Robert Steen, Ameya Bhatawdekar*
- **Think Before You Act: Decision Transformers with Internal Working Memory**, `arXiv, 2305.16338`, [arxiv](http://arxiv.org/abs/2305.16338v1), [pdf](http://arxiv.org/pdf/2305.16338v1.pdf), cication: [**-1**](None)

	 *Jikun Kang, Romain Laroche, Xindi Yuan, Adam Trischler, Xue Liu, Jie Fu* · ([qbitai](https://www.qbitai.com/2023/06/59572.html))
- **Visual Programming: Compositional visual reasoning without training**, `arXiv, 2211.11559`, [arxiv](http://arxiv.org/abs/2211.11559v1), [pdf](http://arxiv.org/pdf/2211.11559v1.pdf), cication: [**-1**](None)

	 *Tanmay Gupta, Aniruddha Kembhavi*

---
- [Stanford CS25: V3 I Beyond LLMs: Agents, Emergent Abilities, Intermediate-Guided Reasoning, BabyLM - YouTube](https://youtu.be/ylEk1TE1uBo?list=PLoROMvodv4rNiJRchCzutFw5ItR_Z27CM&t=1182)
- [Open-source LLMs as LangChain Agents](https://huggingface.co/blog/open-source-llms-as-agents)

---
- [从第一性原理看大模型Agent技术](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495233&idx=1&sn=a6f99f5ed298dc4dad8477979d0c19a8&poc_token=HARdjWWjobSAo4kfK_sgvyLGAic2WQe64y8tToVY)
- [AI最大赛道Agent机遇全解析](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495167&idx=1&sn=f9151855988a1cc29f01cf8658c23c3f)
- [Chat 向左，Agent 向右 - 知乎](https://zhuanlan.zhihu.com/p/662704254)
- [功能超全的AI Agents开源库来了，能写小说，还能当导购、销售 | 机器之心](https://www.jiqizhixin.com/articles/2023-09-21-2)
- [AI革新之路：14篇AI Agents论文，探讨人工智能未来](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247609813&idx=2&sn=668922b98c7891b569a78ff4c2a32280)
- [数字身份智能体的基本原理及应用前景展望](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247611020&idx=1&sn=eeea2012a2bcfe541a138c9a4c42b837)

## AutoGPT
- [**plandex**](https://github.com/plandex-ai/plandex) - plandex-ai ![Star](https://img.shields.io/github/stars/plandex-ai/plandex.svg?style=social&label=Star)
- [**aideml**](https://github.com/WecoAI/aideml) - WecoAI ![Star](https://img.shields.io/github/stars/WecoAI/aideml.svg?style=social&label=Star)

	 *AIDE: Autonomous AI for Data Science* · ([weco](https://www.weco.ai/blog/technical-report))
- [**codel**](https://github.com/semanser/codel) - semanser ![Star](https://img.shields.io/github/stars/semanser/codel.svg?style=social&label=Star)

	 *✨ Fully autonomous AI Agent that can perform complicated tasks and projects using terminal, browser, and editor.*
- **Data Interpreter: An LLM Agent For Data Science**, `arXiv, 2402.18679`, [arxiv](http://arxiv.org/abs/2402.18679v3), [pdf](http://arxiv.org/pdf/2402.18679v3.pdf), cication: [**-1**](None)

	 *Sirui Hong, Yizhang Lin, Bang Liu, Bangbang Liu, Binhao Wu, Danyang Li, Jiaqi Chen, Jiayi Zhang, Jinlin Wang, Li Zhang* · ([MetaGPT](https://github.com/geekan/MetaGPT) - geekan) ![Star](https://img.shields.io/github/stars/geekan/MetaGPT.svg?style=social&label=Star)
- **AutoDev: Automated AI-Driven Development**, `arXiv, 2403.08299`, [arxiv](http://arxiv.org/abs/2403.08299v1), [pdf](http://arxiv.org/pdf/2403.08299v1.pdf), cication: [**-1**](None)

	 *Michele Tufano, Anisha Agarwal, Jinu Jang, Roshanak Zilouchian Moghaddam, Neel Sundaresan*

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652455514&idx=1&sn=53e4d927ea3a783d7b146d8635457549))
- [**crewAI**](https://github.com/joaomdmoura/crewAI) - joaomdmoura ![Star](https://img.shields.io/github/stars/joaomdmoura/crewAI.svg?style=social&label=Star)

	 *Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly, tackling complex tasks.*
- [**self-operating-computer**](https://github.com/OthersideAI/self-operating-computer) - OthersideAI ![Star](https://img.shields.io/github/stars/OthersideAI/self-operating-computer.svg?style=social&label=Star)
- [**open-interpreter**](https://github.com/KillianLucas/open-interpreter) - KillianLucas ![Star](https://img.shields.io/github/stars/KillianLucas/open-interpreter.svg?style=social&label=Star)

	 *OpenAI's Code Interpreter in your terminal, running locally.*
- [**ChatDev**](https://github.com/OpenBMB/ChatDev) - OpenBMB ![Star](https://img.shields.io/github/stars/OpenBMB/ChatDev.svg?style=social&label=Star)

	 *Create Customized Software using Natural Language Idea (through Multi-Agent Collaboration)*
- [**gpt-researcher**](https://github.com/assafelovic/gpt-researcher) - assafelovic ![Star](https://img.shields.io/github/stars/assafelovic/gpt-researcher.svg?style=social&label=Star)

	 *GPT based autonomous agent that does online comprehensive research on any given topic*
- [**gpt-llm-trainer**](https://github.com/mshumer/gpt-llm-trainer) - mshumer ![Star](https://img.shields.io/github/stars/mshumer/gpt-llm-trainer.svg?style=social&label=Star)

	 · ([qbitai](https://www.qbitai.com/2023/08/78155.html))
- [**MetaGPT**](https://github.com/geekan/MetaGPT) - geekan ![Star](https://img.shields.io/github/stars/geekan/MetaGPT.svg?style=social&label=Star)

	 *The Multi-Agent Meta Programming Framework: Given one line Requirement, return PRD, Design, Tasks, Repo | 多智能体元编程框架：给定老板需求，输出产品文档、架构设计、任务列表、代码*

	 · ([qbitai](https://www.qbitai.com/2024/03/128153.html))
- [Toward Actionable Generative AI](https://blog.salesforceairesearch.com/large-action-models/)
- [**PromptAppGPT**](https://github.com/mleoking/PromptAppGPT) - mleoking ![Star](https://img.shields.io/github/stars/mleoking/PromptAppGPT.svg?style=social&label=Star)

	 *A rapid prompt app development framework based on GPT* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652343982&idx=3&sn=b9a4a664b29431b19b4077217f27d768))
- **Responsible Task Automation: Empowering Large Language Models as
  Responsible Task Automators**, `arXiv, 2306.01242`, [arxiv](http://arxiv.org/abs/2306.01242v1), [pdf](http://arxiv.org/pdf/2306.01242v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=15333508948166383051&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhizheng Zhang, Xiaoyi Zhang, Wenxuan Xie, Yan Lu* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-06-22-3))
- **Auto-GPT for Online Decision Making: Benchmarks and Additional Opinions**, `arXiv, 2306.02224`, [arxiv](http://arxiv.org/abs/2306.02224v1), [pdf](http://arxiv.org/pdf/2306.02224v1.pdf), cication: [**10**](https://scholar.google.com/scholar?cites=10760126869775216861&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hui Yang, Sifu Yue, Yunzhong He* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652340210&idx=4&sn=faa472d3af543a7fc36e3eb5f13bc081))
- **CAMEL: Communicative Agents for "Mind" Exploration of Large Language
  Model Society**, `arXiv, 2303.17760`, [arxiv](http://arxiv.org/abs/2303.17760v2), [pdf](http://arxiv.org/pdf/2303.17760v2.pdf), cication: [**-1**](None)

	 *Guohao Li, Hasan Abed Al Kader Hammoud, Hani Itani, Dmitrii Khizbullin, Bernard Ghanem*
- **Language Models can Solve Computer Tasks**, `arXiv, 2303.17491`, [arxiv](http://arxiv.org/abs/2303.17491v2), [pdf](http://arxiv.org/pdf/2303.17491v2.pdf), cication: [**50**](https://scholar.google.com/scholar?cites=2552584892380879541&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Geunwoo Kim, Pierre Baldi, Stephen McAleer*
- [**SuperAGI**](https://github.com/TransformerOptimus/SuperAGI) - TransformerOptimus ![Star](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI.svg?style=social&label=Star)

	 *<⚡️> SuperAGI - A dev-first open source autonomous AI agent framework. Enabling developers to build, manage & run useful autonomous agents quickly and reliably.*
- [**babyagi**](https://github.com/yoheinakajima/babyagi) - yoheinakajima ![Star](https://img.shields.io/github/stars/yoheinakajima/babyagi.svg?style=social&label=Star)
- **Re3: Generating Longer Stories With Recursive Reprompting and Revision**, `arXiv, 2210.06774`, [arxiv](http://arxiv.org/abs/2210.06774v3), [pdf](http://arxiv.org/pdf/2210.06774v3.pdf), cication: [**55**](https://scholar.google.com/scholar?cites=12913281204520727323&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Kevin Yang, Yuandong Tian, Nanyun Peng, Dan Klein*
- **Language Models as Zero-Shot Planners: Extracting Actionable Knowledge
  for Embodied Agents**, `ICML, 2022`, [arxiv](http://arxiv.org/abs/2201.07207v2), [pdf](http://arxiv.org/pdf/2201.07207v2.pdf), cication: [**341**](https://scholar.google.com/scholar?cites=11998123682359381476&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Wenlong Huang, Pieter Abbeel, Deepak Pathak, Igor Mordatch* · ([huangwl18.github](https://huangwl18.github.io/language-planner))

---
- [Godmode.space](https://godmode.space/?ref=futuretools.io)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652349067&idx=1&sn=99bd053f20c8821a5c821dc2e7a972dc)) · ([cognosys](https://www.cognosys.ai/)) · ([doanythingmachine](https://www.doanythingmachine.com/))
- [AgentGPT](https://agentgpt.reworkd.ai/)

## Augmented LLM
- **FollowIR: Evaluating and Teaching Information Retrieval Models to Follow
  Instructions**, `arXiv, 2403.15246`, [arxiv](http://arxiv.org/abs/2403.15246v1), [pdf](http://arxiv.org/pdf/2403.15246v1.pdf), cication: [**-1**](None)

	 *Orion Weller, Benjamin Chang, Sean MacAvaney, Kyle Lo, Arman Cohan, Benjamin Van Durme, Dawn Lawrie, Luca Soldaini*
- [WhatAreToolsAnyway.pdf](https://zorazrw.github.io/files/WhatAreToolsAnyway.pdf)
- **LLMs in the Imaginarium: Tool Learning through Simulated Trial and Error**, `arXiv, 2403.04746`, [arxiv](http://arxiv.org/abs/2403.04746v1), [pdf](http://arxiv.org/pdf/2403.04746v1.pdf), cication: [**-1**](None)

	 *Boshi Wang, Hao Fang, Jason Eisner, Benjamin Van Durme, Yu Su*

	 · ([simulated-trial-and-error](https://github.com/microsoft/simulated-trial-and-error) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/simulated-trial-and-error.svg?style=social&label=Star)
- [**gorilla**](https://github.com/ShishirPatil/gorilla) - ShishirPatil ![Star](https://img.shields.io/github/stars/ShishirPatil/gorilla.svg?style=social&label=Star)

	 *Gorilla: An API store for LLMs* · ([gorilla.cs.berkeley](https://gorilla.cs.berkeley.edu/leaderboard.html))
- **API-BLEND: A Comprehensive Corpora for Training and Benchmarking API
  LLMs**, `arXiv, 2402.15491`, [arxiv](http://arxiv.org/abs/2402.15491v1), [pdf](http://arxiv.org/pdf/2402.15491v1.pdf), cication: [**-1**](None)

	 *Kinjal Basu, Ibrahim Abdelaziz, Subhajit Chaudhury, Soham Dan, Maxwell Crouse, Asim Munawar, Sadhana Kumaravel, Vinod Muthusamy, Pavan Kapanipathi, Luis A. Lastras*
- **AnyTool: Self-Reflective, Hierarchical Agents for Large-Scale API Calls**, `arXiv, 2402.04253`, [arxiv](http://arxiv.org/abs/2402.04253v1), [pdf](http://arxiv.org/pdf/2402.04253v1.pdf), cication: [**-1**](None)

	 *Yu Du, Fangyun Wei, Hongyang Zhang*
- **Efficient Tool Use with Chain-of-Abstraction Reasoning**, `arXiv, 2401.17464`, [arxiv](http://arxiv.org/abs/2401.17464v1), [pdf](http://arxiv.org/pdf/2401.17464v1.pdf), cication: [**-1**](None)

	 *Silin Gao, Jane Dwivedi-Yu, Ping Yu, Xiaoqing Ellen Tan, Ramakanth Pasunuru, Olga Golovneva, Koustuv Sinha, Asli Celikyilmaz, Antoine Bosselut, Tianlu Wang*
- **LLM Augmented LLMs: Expanding Capabilities through Composition**, `arXiv, 2401.02412`, [arxiv](http://arxiv.org/abs/2401.02412v1), [pdf](http://arxiv.org/pdf/2401.02412v1.pdf), cication: [**-1**](None)

	 *Rachit Bansal, Bidisha Samanta, Siddharth Dalmia, Nitish Gupta, Shikhar Vashishth, Sriram Ganapathy, Abhishek Bapna, Prateek Jain, Partha Talukdar*
- **ProTIP: Progressive Tool Retrieval Improves Planning**, `arXiv, 2312.10332`, [arxiv](http://arxiv.org/abs/2312.10332v1), [pdf](http://arxiv.org/pdf/2312.10332v1.pdf), cication: [**-1**](None)

	 *Raviteja Anantha, Bortik Bandyopadhyay, Anirudh Kashi, Sayantan Mahinder, Andrew W Hill, Srinivas Chappidi*
- **Memory Augmented Language Models through Mixture of Word Experts**, `arXiv, 2311.10768`, [arxiv](http://arxiv.org/abs/2311.10768v1), [pdf](http://arxiv.org/pdf/2311.10768v1.pdf), cication: [**-1**](None)

	 *Cicero Nogueira dos Santos, James Lee-Thorp, Isaac Noble, Chung-Ching Chang, David Uthus*
- **ControlLLM: Augment Language Models with Tools by Searching on Graphs**, `arXiv, 2310.17796`, [arxiv](http://arxiv.org/abs/2310.17796v2), [pdf](http://arxiv.org/pdf/2310.17796v2.pdf), cication: [**-1**](None)

	 *Zhaoyang Liu, Zeqiang Lai, Zhangwei Gao, Erfei Cui, Zhiheng Li, Xizhou Zhu, Lewei Lu, Qifeng Chen, Yu Qiao, Jifeng Dai*
- **Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language**, `arXiv, 2204.00598`, [arxiv](http://arxiv.org/abs/2204.00598v2), [pdf](http://arxiv.org/pdf/2204.00598v2.pdf), cication: [**202**](https://scholar.google.com/scholar?cites=17485588102904105060&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Andy Zeng, Maria Attarian, Brian Ichter, Krzysztof Choromanski, Adrian Wong, Stefan Welker, Federico Tombari, Aveek Purohit, Michael Ryoo, Vikas Sindhwani* · ([socraticmodels.github](https://socraticmodels.github.io/#code))
- **Understanding Retrieval Augmentation for Long-Form Question Answering**, `arXiv, 2310.12150`, [arxiv](http://arxiv.org/abs/2310.12150v1), [pdf](http://arxiv.org/pdf/2310.12150v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=13555030950984354517&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Hung-Ting Chen, Fangyuan Xu, Shane Arora, Eunsol Choi*
- **Reward-Augmented Decoding: Efficient Controlled Text Generation With a
  Unidirectional Reward Model**, `arXiv, 2310.09520`, [arxiv](http://arxiv.org/abs/2310.09520v3), [pdf](http://arxiv.org/pdf/2310.09520v3.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=5740043218256432933&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Haikang Deng, Colin Raffel*
- **RECOMP: Improving Retrieval-Augmented LMs with Compression and Selective
  Augmentation**, `arXiv, 2310.04408`, [arxiv](http://arxiv.org/abs/2310.04408v1), [pdf](http://arxiv.org/pdf/2310.04408v1.pdf), cication: [**-1**](None)

	 *Fangyuan Xu, Weijia Shi, Eunsol Choi*
- **InstructRetro: Instruction Tuning post Retrieval-Augmented Pretraining**, `arXiv, 2310.07713`, [arxiv](http://arxiv.org/abs/2310.07713v1), [pdf](http://arxiv.org/pdf/2310.07713v1.pdf), cication: [**-1**](None)

	 *Boxin Wang, Wei Ping, Lawrence McAfee, Peng Xu, Bo Li, Mohammad Shoeybi, Bryan Catanzaro*
- **RA-DIT: Retrieval-Augmented Dual Instruction Tuning**, `arXiv, 2310.01352`, [arxiv](http://arxiv.org/abs/2310.01352v3), [pdf](http://arxiv.org/pdf/2310.01352v3.pdf), cication: [**-1**](None)

	 *Xi Victoria Lin, Xilun Chen, Mingda Chen, Weijia Shi, Maria Lomeli, Rich James, Pedro Rodriguez, Jacob Kahn, Gergely Szilvasy, Mike Lewis*

- **Retroformer: Retrospective Large Language Agents with Policy Gradient
  Optimization**, `arXiv, 2308.02151`, [arxiv](http://arxiv.org/abs/2308.02151v1), [pdf](http://arxiv.org/pdf/2308.02151v1.pdf), cication: [**6**](https://scholar.google.com/scholar?cites=15394605017148461219&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Weiran Yao, Shelby Heinecke, Juan Carlos Niebles, Zhiwei Liu, Yihao Feng, Le Xue, Rithesh Murthy, Zeyuan Chen, Jianguo Zhang, Devansh Arpit*
- **Meta-training with Demonstration Retrieval for Efficient Few-shot
  Learning**, `arXiv, 2307.00119`, [arxiv](http://arxiv.org/abs/2307.00119v1), [pdf](http://arxiv.org/pdf/2307.00119v1.pdf), cication: [**-1**](None)

	 *Aaron Mueller, Kanika Narang, Lambert Mathias, Qifan Wang, Hamed Firooz*
- **AVIS: Autonomous Visual Information Seeking with Large Language Model
  Agent**, `arXiv, 2306.08129`, [arxiv](http://arxiv.org/abs/2306.08129v3), [pdf](http://arxiv.org/pdf/2306.08129v3.pdf), cication: [**-1**](None)

	 *Ziniu Hu, Ahmet Iscen, Chen Sun, Kai-Wei Chang, Yizhou Sun, David A Ross, Cordelia Schmid, Alireza Fathi* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652368752&idx=4&sn=4028750afec250eb722937fe934b80b1))
- **Modular Visual Question Answering via Code Generation**, `arXiv, 2306.05392`, [arxiv](http://arxiv.org/abs/2306.05392v1), [pdf](http://arxiv.org/pdf/2306.05392v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=10338616761686111271&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Sanjay Subramanian, Medhini Narasimhan, Kushal Khangaonkar, Kevin Yang, Arsha Nagrani, Cordelia Schmid, Andy Zeng, Trevor Darrell, Dan Klein*
- **Reimagining Retrieval Augmented Language Models for Answering Queries**, `arXiv, 2306.01061`, [arxiv](http://arxiv.org/abs/2306.01061v1), [pdf](http://arxiv.org/pdf/2306.01061v1.pdf), cication: [**-1**](None)

	 *Wang-Chiew Tan, Yuliang Li, Pedro Rodriguez, Richard James, Xi Victoria Lin, Alon Halevy, Scott Yih*
- **TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with
  Millions of APIs**, `arXiv, 2303.16434`, [arxiv](http://arxiv.org/abs/2303.16434v1), [pdf](http://arxiv.org/pdf/2303.16434v1.pdf), cication: [**113**](https://scholar.google.com/scholar?cites=6110768434458856967&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yaobo Liang, Chenfei Wu, Ting Song, Wenshan Wu, Yan Xia, Yu Liu, Yang Ou, Shuai Lu, Lei Ji, Shaoguang Mao* · ([taskmatrix](http://taskmatrix.ai/))

---
- [陈丹琦ACL学术报告来了！详解大模型「外挂」数据库7大方向3大挑战，3小时干货满满 | 量子位](https://www.qbitai.com/2023/07/67259.html)

## Web browsing
- [**webllama**](https://github.com/McGill-NLP/webllama) - McGill-NLP ![Star](https://img.shields.io/github/stars/McGill-NLP/webllama.svg?style=social&label=Star)
- **AutoCrawler: A Progressive Understanding Web Agent for Web Crawler
  Generation**, `arXiv, 2404.12753`, [arxiv](http://arxiv.org/abs/2404.12753v1), [pdf](http://arxiv.org/pdf/2404.12753v1.pdf), cication: [**-1**](None)

	 *Wenhao Huang, Chenghao Peng, Zhixu Li, Jiaqing Liang, Yanghua Xiao, Liqian Wen, Zulong Chen* · ([AutoCrawler](https://github.com/EZ-hwh/AutoCrawler) - EZ-hwh) ![Star](https://img.shields.io/github/stars/EZ-hwh/AutoCrawler.svg?style=social&label=Star)
- [**Perplexica**](https://github.com/ItzCrazyKns/Perplexica/) - ItzCrazyKns ![Star](https://img.shields.io/github/stars/ItzCrazyKns/Perplexica.svg?style=social&label=Star)

	 *Perplexica is an AI-powered search engine. It is an Open source alternative to Perplexity AI*
- **WILBUR: Adaptive In-Context Learning for Robust and Accurate Web Agents**, `arXiv, 2404.05902`, [arxiv](http://arxiv.org/abs/2404.05902v1), [pdf](http://arxiv.org/pdf/2404.05902v1.pdf), cication: [**-1**](None)

	 *Michael Lutz, Arth Bohra, Manvel Saroyan, Artem Harutyunyan, Giovanni Campagna*
- [**FreeAskInternet**](https://github.com/nashsu/FreeAskInternet) - nashsu ![Star](https://img.shields.io/github/stars/nashsu/FreeAskInternet.svg?style=social&label=Star)

	 *FreeAskInternet is a completely free, private and locally running search aggregator & answer generate using LLM, without GPU needed. The user can ask a question and the system will make a multi engine search and combine the search result to the ChatGPT3.5 LLM and generate the answer based on search results.*
- **Stream of Search (SoS): Learning to Search in Language**, `arXiv, 2404.03683`, [arxiv](http://arxiv.org/abs/2404.03683v1), [pdf](http://arxiv.org/pdf/2404.03683v1.pdf), cication: [**-1**](None)

	 *Kanishk Gandhi, Denise Lee, Gabriel Grand, Muxin Liu, Winson Cheng, Archit Sharma, Noah D. Goodman*

	 · ([stream-of-search](https://github.com/kanishkg/stream-of-search) - kanishkg) ![Star](https://img.shields.io/github/stars/kanishkg/stream-of-search.svg?style=social&label=Star)
- **AutoWebGLM: Bootstrap And Reinforce A Large Language Model-based Web
  Navigating Agent**, `arXiv, 2404.03648`, [arxiv](http://arxiv.org/abs/2404.03648v1), [pdf](http://arxiv.org/pdf/2404.03648v1.pdf), cication: [**-1**](None)

	 *Hanyu Lai, Xiao Liu, Iat Long Iong, Shuntian Yao, Yuxuan Chen, Pengbo Shen, Hao Yu, Hanchen Zhang, Xiaohan Zhang, Yuxiao Dong* · ([AutoWebGLM](https://github.com/THUDM/AutoWebGLM) - THUDM) ![Star](https://img.shields.io/github/stars/THUDM/AutoWebGLM.svg?style=social&label=Star)
- [**llm-answer-engine**](https://github.com/developersdigest/llm-answer-engine) - developersdigest ![Star](https://img.shields.io/github/stars/developersdigest/llm-answer-engine.svg?style=social&label=Star)

	 *Build a Perplexity-Inspired Answer Engine Using Next.js, Groq, Mixtral, Langchain, OpenAI, Brave & Serper*

	 · ([twitter](https://twitter.com/LangChainAI/status/1774502671669501973?utm_source=ainews&utm_medium=email&utm_campaign=ainews-adamw-aarond))
- [**skyvern**](https://github.com/Skyvern-AI/skyvern) - Skyvern-AI ![Star](https://img.shields.io/github/stars/Skyvern-AI/skyvern.svg?style=social&label=Star)

	 *Automate browser-based workflows with LLMs and Computer Vision*
- [**LaVague**](https://github.com/lavague-ai/LaVague) - lavague-ai ![Star](https://img.shields.io/github/stars/lavague-ai/LaVague.svg?style=social&label=Star)

	 *Automate automation with Large Action Model framework*
- [**api**](https://github.com/MULTI-ON/api) - MULTI-ON ![Star](https://img.shields.io/github/stars/MULTI-ON/api.svg?style=social&label=Star)

	 *MultiOn API*
- **OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist
  Autonomous Agents for Desktop and Web**, `arXiv, 2402.17553`, [arxiv](http://arxiv.org/abs/2402.17553v1), [pdf](http://arxiv.org/pdf/2402.17553v1.pdf), cication: [**-1**](None)

	 *Raghav Kapoor, Yash Parag Butala, Melisa Russak, Jing Yu Koh, Kiran Kamble, Waseem Alshikh, Ruslan Salakhutdinov*
- **VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web
  Tasks**, `arXiv, 2401.13649`, [arxiv](http://arxiv.org/abs/2401.13649v1), [pdf](http://arxiv.org/pdf/2401.13649v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=6599905016676901235&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jing Yu Koh, Robert Lo, Lawrence Jang, Vikram Duvvur, Ming Chong Lim, Po-Yu Huang, Graham Neubig, Shuyan Zhou, Ruslan Salakhutdinov, Daniel Fried* · ([visualwebarena](https://github.com/web-arena-x/visualwebarena) - web-arena-x) ![Star](https://img.shields.io/github/stars/web-arena-x/visualwebarena.svg?style=social&label=Star) · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652443845&idx=3&sn=db2b541768e9c9f77536e52b21de8ba4))
- **WebLINX: Real-World Website Navigation with Multi-Turn Dialogue**, `arXiv, 2402.05930`, [arxiv](http://arxiv.org/abs/2402.05930v1), [pdf](http://arxiv.org/pdf/2402.05930v1.pdf), cication: [**-1**](None)

	 *Xing Han Lù, Zdeněk Kasner, Siva Reddy* · ([mcgill-nlp.github](https://mcgill-nlp.github.io/weblinx))
- [**search_with_lepton**](https://github.com/leptonai/search_with_lepton) - leptonai ![Star](https://img.shields.io/github/stars/leptonai/search_with_lepton.svg?style=social&label=Star)

	 *Building a quick conversation-based search demo with Lepton AI.*
- **WebVoyager: Building an End-to-End Web Agent with Large Multimodal
  Models**, `arXiv, 2401.13919`, [arxiv](http://arxiv.org/abs/2401.13919v1), [pdf](http://arxiv.org/pdf/2401.13919v1.pdf), cication: [**-1**](None)

	 *Hongliang He, Wenlin Yao, Kaixin Ma, Wenhao Yu, Yong Dai, Hongming Zhang, Zhenzhong Lan, Dong Yu*
- **GPT-4V(ision) is a Generalist Web Agent, if Grounded**, `arXiv, 2401.01614`, [arxiv](http://arxiv.org/abs/2401.01614v1), [pdf](http://arxiv.org/pdf/2401.01614v1.pdf), cication: [**-1**](None)

	 *Boyuan Zheng, Boyu Gou, Jihyung Kil, Huan Sun, Yu Su* · ([SeeAct](https://github.com/OSU-NLP-Group/SeeAct) - OSU-NLP-Group) ![Star](https://img.shields.io/github/stars/OSU-NLP-Group/SeeAct.svg?style=social&label=Star) · ([osu-nlp-group.github](https://osu-nlp-group.github.io/SeeAct/))
- [**webglm**](https://github.com/thudm/webglm) - thudm ![Star](https://img.shields.io/github/stars/thudm/webglm.svg?style=social&label=Star)

	 *WebGLM: An Efficient Web-enhanced Question Answering System (KDD 2023)*
- **FreshLLMs: Refreshing Large Language Models with Search Engine
  Augmentation**, `arXiv, 2310.03214`, [arxiv](http://arxiv.org/abs/2310.03214v1), [pdf](http://arxiv.org/pdf/2310.03214v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=5401685431323690843&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Tu Vu, Mohit Iyyer, Xuezhi Wang, Noah Constant, Jerry Wei, Jason Wei, Chris Tar, Yun-Hsuan Sung, Denny Zhou, Quoc Le* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-10-2))
- **GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone
  GUI Navigation**, `arXiv, 2311.07562`, [arxiv](http://arxiv.org/abs/2311.07562v1), [pdf](http://arxiv.org/pdf/2311.07562v1.pdf), cication: [**-1**](None)

	 *An Yan, Zhengyuan Yang, Wanrong Zhu, Kevin Lin, Linjie Li, Jianfeng Wang, Jianwei Yang, Yiwu Zhong, Julian McAuley, Jianfeng Gao* · ([MM-Navigator](https://github.com/zzxslp/MM-Navigator) - zzxslp) ![Star](https://img.shields.io/github/stars/zzxslp/MM-Navigator.svg?style=social&label=Star)

	 · ([qbitai](https://www.qbitai.com/2023/11/98316.html))
- [**vimGPT**](https://github.com/ishan0102/vimGPT) - ishan0102 ![Star](https://img.shields.io/github/stars/ishan0102/vimGPT.svg?style=social&label=Star)

	 *Browse the web with GPT-4V and Vimium*
- **A Real-World WebAgent with Planning, Long Context Understanding, and
  Program Synthesis**, `arXiv, 2307.12856`, [arxiv](http://arxiv.org/abs/2307.12856v3), [pdf](http://arxiv.org/pdf/2307.12856v3.pdf), cication: [**13**](https://scholar.google.com/scholar?cites=11247435352141794384&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Izzeddin Gur, Hiroki Furuta, Austin Huang, Mustafa Safdari, Yutaka Matsuo, Douglas Eck, Aleksandra Faust*
- [**WebGLM**](https://github.com/THUDM/WebGLM) - THUDM ![Star](https://img.shields.io/github/stars/THUDM/WebGLM.svg?style=social&label=Star)

	 *WebGLM: An Efficient Web-enhanced Question Answering System (KDD 2023)*
- [WebArena: A Realistic Web Environment for Building Autonomous Agents](https://webarena.dev/#try-it-yourself)

	 · ([twitter](https://twitter.com/shuyanzhxyc/status/1683917253597855744))
- **Query2doc: Query Expansion with Large Language Models**, `arXiv, 2303.07678`, [arxiv](http://arxiv.org/abs/2303.07678v2), [pdf](http://arxiv.org/pdf/2303.07678v2.pdf), cication: [**23**](https://scholar.google.com/scholar?cites=18151428791630750924&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Liang Wang, Nan Yang, Furu Wei* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495205&idx=2&sn=ac64211d4b112ca68b7562ea1e4a5a1f))

---
- [GPT-4V学会用键鼠上网，人类眼睁睁看着它发帖玩游戏 | 量子位](https://www.qbitai.com/2023/11/95456.html)

## Retrieval agumented generation
- [**context-cite**](https://github.com/MadryLab/context-cite) - MadryLab ![Star](https://img.shields.io/github/stars/MadryLab/context-cite.svg?style=social&label=Star)

	 *Attribute (or cite) statements generated by LLMs back to in-context information.* · ([gradientscience](http://gradientscience.org/contextcite/)) · ([huggingface](https://huggingface.co/spaces/contextcite/context-cite))
- **When to Retrieve: Teaching LLMs to Utilize Information Retrieval
  Effectively**, `arXiv, 2404.19705`, [arxiv](http://arxiv.org/abs/2404.19705v1), [pdf](http://arxiv.org/pdf/2404.19705v1.pdf), cication: [**-1**](None)

	 *Tiziano Labruna, Jon Ander Campos, Gorka Azkune*
- **Retrieval Head Mechanistically Explains Long-Context Factuality**, `arXiv, 2404.15574`, [arxiv](http://arxiv.org/abs/2404.15574v1), [pdf](http://arxiv.org/pdf/2404.15574v1.pdf), cication: [**-1**](None)

	 *Wenhao Wu, Yizhong Wang, Guangxuan Xiao, Hao Peng, Yao Fu*
- [**phidata**](https://github.com/phidatahq/phidata) - phidatahq ![Star](https://img.shields.io/github/stars/phidatahq/phidata.svg?style=social&label=Star)

	 *Add memory, knowledge and tools to LLMs*
- **Superposition Prompting: Improving and Accelerating Retrieval-Augmented
  Generation**, `arXiv, 2404.06910`, [arxiv](http://arxiv.org/abs/2404.06910v1), [pdf](http://arxiv.org/pdf/2404.06910v1.pdf), cication: [**-1**](None)

	 *Thomas Merth, Qichen Fu, Mohammad Rastegari, Mahyar Najibi*
- [**goku**](https://github.com/aishwaryaprabhat/goku/tree/main/goku/dream) - aishwaryaprabhat ![Star](https://img.shields.io/github/stars/aishwaryaprabhat/goku.svg?style=social&label=Star)

	 · ([linkedin](https://t.co/twl5N4tAkM))
- **Reducing hallucination in structured outputs via Retrieval-Augmented
  Generation**, `arXiv, 2404.08189`, [arxiv](http://arxiv.org/abs/2404.08189v1), [pdf](http://arxiv.org/pdf/2404.08189v1.pdf), cication: [**-1**](None)

	 *Patrice Béchard, Orlando Marquez Ayala*
- **A Survey on Retrieval-Augmented Text Generation for Large Language
  Models**, `arXiv, 2404.10981`, [arxiv](http://arxiv.org/abs/2404.10981v1), [pdf](http://arxiv.org/pdf/2404.10981v1.pdf), cication: [**-1**](None)

	 *Yizheng Huang, Jimmy Huang*
- **How faithful are RAG models? Quantifying the tug-of-war between RAG and
  LLMs' internal prior**, `arXiv, 2404.10198`, [arxiv](http://arxiv.org/abs/2404.10198v1), [pdf](http://arxiv.org/pdf/2404.10198v1.pdf), cication: [**-1**](None)

	 *Kevin Wu, Eric Wu, James Zou*
- [**MaxKB**](https://github.com/1Panel-dev/MaxKB) - 1Panel-dev ![Star](https://img.shields.io/github/stars/1Panel-dev/MaxKB.svg?style=social&label=Star)

	 *💬 基于 LLM 大语言模型的知识库问答系统。开箱即用，支持快速嵌入到第三方业务系统，1Panel 官方出品。*
- [**StreamRAG**](https://github.com/video-db/StreamRAG) - video-db ![Star](https://img.shields.io/github/stars/video-db/StreamRAG.svg?style=social&label=Star)

	 *Video Search and Streaming Agent 🕵️‍♂️*
- **ARAGOG: Advanced RAG Output Grading**, `arXiv, 2404.01037`, [arxiv](http://arxiv.org/abs/2404.01037v1), [pdf](http://arxiv.org/pdf/2404.01037v1.pdf), cication: [**-1**](None)

	 *Matouš Eibich, Shivay Nagpal, Alexander Fred-Ojala*
- **Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language
  Models through Question Complexity**, `arXiv, 2403.14403`, [arxiv](http://arxiv.org/abs/2403.14403v2), [pdf](http://arxiv.org/pdf/2403.14403v2.pdf), cication: [**-1**](None)

	 *Soyeong Jeong, Jinheon Baek, Sukmin Cho, Sung Ju Hwang, Jong C. Park* · ([twitter](https://twitter.com/LangChainAI/status/1775917799065653250?utm_source=ainews&utm_medium=email&utm_campaign=ainews-cohere-command-r-anthropic-claude-tool-use)) · ([twitter](https://twitter.com/llama_index/status/1775912690529288556?utm_source=ainews&utm_medium=email&utm_campaign=ainews-cohere-command-r-anthropic-claude-tool-use)) · ([notebooks](https://github.com/cohere-ai/notebooks/blob/main/notebooks/react_agent_adaptive_rag_cohere.ipynb) - cohere-ai) ![Star](https://img.shields.io/github/stars/cohere-ai/notebooks.svg?style=social&label=Star) · ([youtube](https://www.youtube.com/watch?v=04ighIjMcAI&ab_channel=LangChain))
- [**AutoRAG**](https://github.com/Marker-Inc-Korea/AutoRAG) - Marker-Inc-Korea ![Star](https://img.shields.io/github/stars/Marker-Inc-Korea/AutoRAG.svg?style=social&label=Star)

	 *RAG AutoML Tool - Find optimal RAG pipeline for your own data.*
- [**cookbook**](https://github.com/mistralai/cookbook/tree/main/third_party/LlamaIndex) - mistralai ![Star](https://img.shields.io/github/stars/mistralai/cookbook.svg?style=social&label=Star)
- [**LLocalSearch**](https://github.com/nilsherzig/LLocalSearch) - nilsherzig ![Star](https://img.shields.io/github/stars/nilsherzig/LLocalSearch.svg?style=social&label=Star)

	 *LLocalSearch is a completely locally running search aggregator using LLM Agents. The user can ask a question and the system will use a chain of LLMs to find the answer. The user can see the progress of the agents and the final answer. No OpenAI or Google API keys are needed.*
- [**ragflow**](https://github.com/infiniflow/ragflow) - infiniflow ![Star](https://img.shields.io/github/stars/infiniflow/ragflow.svg?style=social&label=Star)

	 *RAGFlow is an open-source RAG (Retrieval-Augmented Generation) engine based on deep document understanding.*
- [**llama_parse**](https://github.com/run-llama/llama_parse/tree/main) - run-llama ![Star](https://img.shields.io/github/stars/run-llama/llama_parse.svg?style=social&label=Star)

	 *Parse files for optimal RAG*
- **RAFT: Adapting Language Model to Domain Specific RAG**, `arXiv, 2403.10131`, [arxiv](http://arxiv.org/abs/2403.10131v1), [pdf](http://arxiv.org/pdf/2403.10131v1.pdf), cication: [**-1**](None)

	 *Tianjun Zhang, Shishir G. Patil, Naman Jain, Sheng Shen, Matei Zaharia, Ion Stoica, Joseph E. Gonzalez*

	 · ([gorilla](https://github.com/ShishirPatil/gorilla) - ShishirPatil) ![Star](https://img.shields.io/github/stars/ShishirPatil/gorilla.svg?style=social&label=Star)
	- `(RAFT) for enhancing LLMs for open-book, in-domain question answering by training them to identify and disregard non-helpful "distractor" documents while accurately citing relevant information from the right sources. `
- [**rerankers**](https://github.com/AnswerDotAI/rerankers/) - AnswerDotAI ![Star](https://img.shields.io/github/stars/AnswerDotAI/rerankers.svg?style=social&label=Star)
- [**fully-local-pdf-chatbot**](https://github.com/jacoblee93/fully-local-pdf-chatbot) - jacoblee93 ![Star](https://img.shields.io/github/stars/jacoblee93/fully-local-pdf-chatbot.svg?style=social&label=Star)

	 *Yes, it's another chat over documents implementation... but this one is entirely local!*
- **RAT: Retrieval Augmented Thoughts Elicit Context-Aware Reasoning in
  Long-Horizon Generation**, `arXiv, 2403.05313`, [arxiv](http://arxiv.org/abs/2403.05313v1), [pdf](http://arxiv.org/pdf/2403.05313v1.pdf), cication: [**-1**](None)

	 *Zihao Wang, Anji Liu, Haowei Lin, Jiaqi Li, Xiaojian Ma, Yitao Liang*

	 · ([craftjarvis.github](https://craftjarvis.github.io/RAT))
- **Backtracing: Retrieving the Cause of the Query**, `arXiv, 2403.03956`, [arxiv](http://arxiv.org/abs/2403.03956v1), [pdf](http://arxiv.org/pdf/2403.03956v1.pdf), cication: [**-1**](None)

	 *Rose E. Wang, Pawan Wirawarn, Omar Khattab, Noah Goodman, Dorottya Demszky* · ([backtracing](https://github.com/rosewang2008/backtracing/blob/main) - rosewang2008) ![Star](https://img.shields.io/github/stars/rosewang2008/backtracing.svg?style=social&label=Star)
	- `"backtracing" as a task to help content creators like lecturers identify the text segments that led to user queries, aiming to enhance content delivery in education, news, and conversation domains.`
- [**chat-with-mlx**](https://github.com/qnguyen3/chat-with-mlx) - qnguyen3 ![Star](https://img.shields.io/github/stars/qnguyen3/chat-with-mlx.svg?style=social&label=Star)

	 *Chat with your data natively on Apple Silicon using MLX Framework.*
- **In Search of Needles in a 11M Haystack: Recurrent Memory Finds What LLMs
  Miss**, `arXiv, 2402.10790`, [arxiv](http://arxiv.org/abs/2402.10790v2), [pdf](http://arxiv.org/pdf/2402.10790v2.pdf), cication: [**-1**](None)

	 *Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev*
- **PreFLMR: Scaling Up Fine-Grained Late-Interaction Multi-modal Retrievers**, `arXiv, 2402.08327`, [arxiv](http://arxiv.org/abs/2402.08327v1), [pdf](http://arxiv.org/pdf/2402.08327v1.pdf), cication: [**-1**](None)

	 *Weizhe Lin, Jingbiao Mei, Jinghong Chen, Bill Byrne*

	 · ([preflmr.github](https://preflmr.github.io/)) · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-03-25-10))
- **What Evidence Do Language Models Find Convincing?**, `arXiv, 2402.11782`, [arxiv](http://arxiv.org/abs/2402.11782v1), [pdf](http://arxiv.org/pdf/2402.11782v1.pdf), cication: [**-1**](None)

	 *Alexander Wan, Eric Wallace, Dan Klein*
- **ARKS: Active Retrieval in Knowledge Soup for Code Generation**, `arXiv, 2402.12317`, [arxiv](http://arxiv.org/abs/2402.12317v1), [pdf](http://arxiv.org/pdf/2402.12317v1.pdf), cication: [**-1**](None)

	 *Hongjin Su, Shuyang Jiang, Yuhang Lai, Haoyuan Wu, Boao Shi, Che Liu, Qian Liu, Tao Yu* · ([arks](https://github.com/xlang-ai/arks) - xlang-ai) ![Star](https://img.shields.io/github/stars/xlang-ai/arks.svg?style=social&label=Star) · ([arks-codegen.github](https://arks-codegen.github.io/))
- **Seven Failure Points When Engineering a Retrieval Augmented Generation
  System**, `arXiv, 2401.05856`, [arxiv](http://arxiv.org/abs/2401.05856v1), [pdf](http://arxiv.org/pdf/2401.05856v1.pdf), cication: [**2**](https://scholar.google.com/scholar?cites=7363169033457600032&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Scott Barnett, Stefanus Kurniawan, Srikanth Thudumu, Zach Brannelly, Mohamed Abdelrazek* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247630803&idx=1&sn=031ce2af8d4e12377897fc89e2a55829))
- **MultiHop-RAG: Benchmarking Retrieval-Augmented Generation for Multi-Hop
  Queries**, `arXiv, 2401.15391`, [arxiv](http://arxiv.org/abs/2401.15391v1), [pdf](http://arxiv.org/pdf/2401.15391v1.pdf), cication: [**-1**](None)

	 *Yixuan Tang, Yi Yang* · ([MultiHop-RAG](https://github.com/yixuantt/MultiHop-RAG) - yixuantt) ![Star](https://img.shields.io/github/stars/yixuantt/MultiHop-RAG.svg?style=social&label=Star)
- [**GeneGPT**](https://github.com/ncbi/GeneGPT) - ncbi ![Star](https://img.shields.io/github/stars/ncbi/GeneGPT.svg?style=social&label=Star)

	 *Code and data for GeneGPT.*
- [**trt-llm-rag-windows**](https://github.com/NVIDIA/trt-llm-rag-windows) - NVIDIA ![Star](https://img.shields.io/github/stars/NVIDIA/trt-llm-rag-windows.svg?style=social&label=Star)

	 *A developer reference project for creating Retrieval Augmented Generation (RAG) chatbots on Windows using TensorRT-LLM*
- **RAPTOR: Recursive Abstractive Processing for Tree-Organized Retrieval**, `arXiv, 2401.18059`, [arxiv](http://arxiv.org/abs/2401.18059v1), [pdf](http://arxiv.org/pdf/2401.18059v1.pdf), cication: [**-1**](None)

	 *Parth Sarthi, Salman Abdullah, Aditi Tuli, Shubh Khanna, Anna Goldie, Christopher D. Manning*

	 · ([RAPTOR](https://github.com/parthsarthi03/RAPTOR) - parthsarthi03) ![Star](https://img.shields.io/github/stars/parthsarthi03/RAPTOR.svg?style=social&label=Star)
- **Corrective Retrieval Augmented Generation**, `arXiv, 2401.15884`, [arxiv](http://arxiv.org/abs/2401.15884v1), [pdf](http://arxiv.org/pdf/2401.15884v1.pdf), cication: [**-1**](None)

	 *Shi-Qi Yan, Jia-Chen Gu, Yun Zhu, Zhen-Hua Ling*
- [**flagembedding**](https://github.com/flagopen/flagembedding) - flagopen ![Star](https://img.shields.io/github/stars/flagopen/flagembedding.svg?style=social&label=Star)

	 *Dense Retrieval and Retrieval-augmented LLMs*
- [**autollm**](https://github.com/safevideo/autollm) - safevideo ![Star](https://img.shields.io/github/stars/safevideo/autollm.svg?style=social&label=Star)

	 *Ship RAG based LLM web apps in seconds.*
- **The Power of Noise: Redefining Retrieval for RAG Systems**, `arXiv, 2401.14887`, [arxiv](http://arxiv.org/abs/2401.14887v2), [pdf](http://arxiv.org/pdf/2401.14887v2.pdf), cication: [**-1**](None)

	 *Florin Cuconasu, Giovanni Trappolini, Federico Siciliano, Simone Filice, Cesare Campagnano, Yoelle Maarek, Nicola Tonellotto, Fabrizio Silvestri*
- [**RAGatouille**](https://github.com/bclavie/RAGatouille) - bclavie ![Star](https://img.shields.io/github/stars/bclavie/RAGatouille.svg?style=social&label=Star)
- [**simple-rag**](https://github.com/lamini-ai/simple-rag) - lamini-ai ![Star](https://img.shields.io/github/stars/lamini-ai/simple-rag.svg?style=social&label=Star)
- [**pdftochat**](https://github.com/Nutlope/pdftochat) - Nutlope ![Star](https://img.shields.io/github/stars/Nutlope/pdftochat.svg?style=social&label=Star)

	 *Chat with your PDFs with AI* · ([pdftochat](https://www.pdftochat.com/))
- [**RAGxplorer**](https://github.com/gabrielchua/RAGxplorer) - gabrielchua ![Star](https://img.shields.io/github/stars/gabrielchua/RAGxplorer.svg?style=social&label=Star)

	 *Visualise and explore your RAG documents*
- **RAG vs Fine-tuning: Pipelines, Tradeoffs, and a Case Study on
  Agriculture**, `arXiv, 2401.08406`, [arxiv](http://arxiv.org/abs/2401.08406v1), [pdf](http://arxiv.org/pdf/2401.08406v1.pdf), cication: [**-1**](None)

	 *Aman Gupta, Anup Shirgaonkar, Angels de Luis Balaguer, Bruno Silva, Daniel Holstein, Dawei Li, Jennifer Marsman, Leonardo O. Nunes, Mahsa Rouzbahman, Morris Sharp*
- **Improving Text Embeddings with Large Language Models**, `arXiv, 2401.00368`, [arxiv](http://arxiv.org/abs/2401.00368v1), [pdf](http://arxiv.org/pdf/2401.00368v1.pdf), cication: [**-1**](None)

	 *Liang Wang, Nan Yang, Xiaolong Huang, Linjun Yang, Rangan Majumder, Furu Wei*
- [**QAnything**](https://github.com/netease-youdao/QAnything) - netease-youdao ![Star](https://img.shields.io/github/stars/netease-youdao/QAnything.svg?style=social&label=Star)

	 *Question and Answer based on Anything.*
- [**embedchain**](https://github.com/embedchain/embedchain) - embedchain ![Star](https://img.shields.io/github/stars/embedchain/embedchain.svg?style=social&label=Star)

	 *The Open Source RAG framework*
- **Retrieval-Augmented Generation for Large Language Models: A Survey**, `arXiv, 2312.10997`, [arxiv](http://arxiv.org/abs/2312.10997v1), [pdf](http://arxiv.org/pdf/2312.10997v1.pdf), cication: [**-1**](None)

	 *Yunfan Gao, Yun Xiong, Xinyu Gao, Kangxiang Jia, Jinliu Pan, Yuxi Bi, Yi Dai, Jiawei Sun, Haofen Wang* · ([rag-survey](https://github.com/tongji-kgllm/rag-survey) - tongji-kgllm) ![Star](https://img.shields.io/github/stars/tongji-kgllm/rag-survey.svg?style=social&label=Star)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495441&idx=2&sn=cb2cfb2eab441f8a5262ad5b98c1757f))
- [**CodeFuse-DevOps-Model**](https://github.com/codefuse-ai/CodeFuse-DevOps-Model) - codefuse-ai ![Star](https://img.shields.io/github/stars/codefuse-ai/CodeFuse-DevOps-Model.svg?style=social&label=Star)

	 *DevOps-Models is a series of industrial-first LLMs for theDevOps domain. Asking it for any question in the DevOps domain to get solution!*
- [**codefuse-chatbot**](https://github.com/codefuse-ai/codefuse-chatbot) - codefuse-ai ![Star](https://img.shields.io/github/stars/codefuse-ai/codefuse-chatbot.svg?style=social&label=Star)

	 *An open-sourced AI assistant/agents for the full-life cycle of AI native software developing, supporting chat interactions plus knowledge base, invoking tools, sandbox execution, etc.* · ([qbitai](https://www.qbitai.com/2023/12/106372.html))
- **Context Tuning for Retrieval Augmented Generation**, `arXiv, 2312.05708`, [arxiv](http://arxiv.org/abs/2312.05708v1), [pdf](http://arxiv.org/pdf/2312.05708v1.pdf), cication: [**-1**](None)

	 *Raviteja Anantha, Tharun Bethi, Danil Vodianik, Srinivas Chappidi*
- **TextGenSHAP: Scalable Post-hoc Explanations in Text Generation with Long
  Documents**, `arXiv, 2312.01279`, [arxiv](http://arxiv.org/abs/2312.01279v1), [pdf](http://arxiv.org/pdf/2312.01279v1.pdf), cication: [**-1**](None)

	 *James Enouen, Hootan Nakhost, Sayna Ebrahimi, Sercan O Arik, Yan Liu, Tomas Pfister*
- [**LongContext_vs_RAG_NeedleInAHaystack**](https://github.com/A-Roucher/LongContext_vs_RAG_NeedleInAHaystack) - A-Roucher ![Star](https://img.shields.io/github/stars/A-Roucher/LongContext_vs_RAG_NeedleInAHaystack.svg?style=social&label=Star)

	 *Comparing retrieval abilities from GPT4-Turbo and a RAG system on a toy example for various context lengths*
- **Chain-of-Note: Enhancing Robustness in Retrieval-Augmented Language
  Models**, `arXiv, 2311.09210`, [arxiv](http://arxiv.org/abs/2311.09210v1), [pdf](http://arxiv.org/pdf/2311.09210v1.pdf), cication: [**-1**](None)

	 *Wenhao Yu, Hongming Zhang, Xiaoman Pan, Kaixin Ma, Hongwei Wang, Dong Yu*
- **SUQL: Conversational Search over Structured and Unstructured Data with
  Large Language Models**, `arXiv, 2311.09818`, [arxiv](http://arxiv.org/abs/2311.09818v2), [pdf](http://arxiv.org/pdf/2311.09818v2.pdf), cication: [**-1**](None)

	 *Shicheng Liu, Jialiang Xu, Wesley Tjangnaka, Sina J. Semnani, Chen Jie Yu, Monica S. Lam* · ([suql](https://github.com/stanford-oval/suql) - stanford-oval) ![Star](https://img.shields.io/github/stars/stanford-oval/suql.svg?style=social&label=Star)
- **Learning to Filter Context for Retrieval-Augmented Generation**, `arXiv, 2311.08377`, [arxiv](http://arxiv.org/abs/2311.08377v1), [pdf](http://arxiv.org/pdf/2311.08377v1.pdf), cication: [**-1**](None)

	 *Zhiruo Wang, Jun Araki, Zhengbao Jiang, Md Rizwan Parvez, Graham Neubig* · ([filco](https://github.com/zorazrw/filco) - zorazrw) ![Star](https://img.shields.io/github/stars/zorazrw/filco.svg?style=social&label=Star)
- [**gpt-crawler**](https://github.com/BuilderIO/gpt-crawler) - BuilderIO ![Star](https://img.shields.io/github/stars/BuilderIO/gpt-crawler.svg?style=social&label=Star)

	 *Crawl a site to generate knowledge files to create your own custom GPT from a URL*
- [**Langchain-Chatchat**](https://github.com/chatchat-space/Langchain-Chatchat) - chatchat-space ![Star](https://img.shields.io/github/stars/chatchat-space/Langchain-Chatchat.svg?style=social&label=Star)

	 *Langchain-Chatchat（原Langchain-ChatGLM）基于 Langchain 与 ChatGLM 等语言模型的本地知识库问答 | Langchain-Chatchat (formerly langchain-ChatGLM), local knowledge based LLM (like ChatGLM) QA app with langchain*
- [**privateGPT**](https://github.com/imartinez/privateGPT) - imartinez ![Star](https://img.shields.io/github/stars/imartinez/privateGPT.svg?style=social&label=Star)

	 *Interact with your documents using the power of GPT, 100% privately, no data leaks*

- **KITAB: Evaluating LLMs on Constraint Satisfaction for Information
  Retrieval**, `arXiv, 2310.15511`, [arxiv](http://arxiv.org/abs/2310.15511v1), [pdf](http://arxiv.org/pdf/2310.15511v1.pdf), cication: [**-1**](None)

	 *Marah I Abdin, Suriya Gunasekar, Varun Chandrasekaran, Jerry Li, Mert Yuksekgonul, Rahee Ghosh Peshawaria, Ranjita Naik, Besmira Nushi*
- [**Langchain-Chatchat**](https://github.com/chatchat-space/Langchain-Chatchat) - chatchat-space ![Star](https://img.shields.io/github/stars/chatchat-space/Langchain-Chatchat.svg?style=social&label=Star)

	 *Langchain-Chatchat（原Langchain-ChatGLM）基于 Langchain 与 ChatGLM 等语言模型的本地知识库问答 | Langchain-Chatchat (formerly langchain-ChatGLM), local knowledge based LLM (like ChatGLM) QA app with langchain*
- [**DocsGPT**](https://github.com/arc53/DocsGPT) - arc53 ![Star](https://img.shields.io/github/stars/arc53/DocsGPT.svg?style=social&label=Star)

	 *GPT-powered chat for documentation, chat with your documents* · ([qbitai](https://www.qbitai.com/2023/10/87996.html))
- **LMDX: Language Model-based Document Information Extraction and
  Localization**, `arXiv, 2309.10952`, [arxiv](http://arxiv.org/abs/2309.10952v1), [pdf](http://arxiv.org/pdf/2309.10952v1.pdf), cication: [**-1**](None)

	 *Vincent Perot, Kai Kang, Florian Luisier, Guolong Su, Xiaoyu Sun, Ramya Sree Boppana, Zilong Wang, Jiaqi Mu, Hao Zhang, Nan Hua*
- **PDFTriage: Question Answering over Long, Structured Documents**, `arXiv, 2309.08872`, [arxiv](http://arxiv.org/abs/2309.08872v2), [pdf](http://arxiv.org/pdf/2309.08872v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=851640409311189815&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jon Saad-Falcon, Joe Barrow, Alexa Siu, Ani Nenkova, David Seunghyun Yoon, Ryan A. Rossi, Franck Dernoncourt*
- [**sec-insights**](https://github.com/run-llama/sec-insights) - run-llama ![Star](https://img.shields.io/github/stars/run-llama/sec-insights.svg?style=social&label=Star)

	 *A real world full-stack application using LlamaIndex*
- [**simplyretrieve**](https://github.com/rcgai/simplyretrieve) - rcgai ![Star](https://img.shields.io/github/stars/rcgai/simplyretrieve.svg?style=social&label=Star)

	 *An Easy-to-use Private and Lightweight Retrieval-Centric Generative AI Tool. Create chat tool with your documents and open-source LLMs, highly customizable.*
- [**FastGPT**](https://github.com/labring/FastGPT) - labring ![Star](https://img.shields.io/github/stars/labring/FastGPT.svg?style=social&label=Star)

	 *A platform that uses the OpenAI API to quickly build an AI knowledge base, supporting many-to-many relationships.*
- [**factool**](https://github.com/gair-nlp/factool) - gair-nlp ![Star](https://img.shields.io/github/stars/gair-nlp/factool.svg?style=social&label=Star)

	 *A fact-checking tool that detects factual errors.*
- [**Llama-2-Open-Source-LLM-CPU-Inference**](https://github.com/kennethleungty/Llama-2-Open-Source-LLM-CPU-Inference) - kennethleungty ![Star](https://img.shields.io/github/stars/kennethleungty/Llama-2-Open-Source-LLM-CPU-Inference.svg?style=social&label=Star)

	 *Running Llama 2 and other Open-Source LLMs on CPU Inference Locally for Document Q&A*
- [**danswer**](https://github.com/danswer-ai/danswer) - danswer-ai ![Star](https://img.shields.io/github/stars/danswer-ai/danswer.svg?style=social&label=Star)

	 *Ask Questions in natural language and get Answers backed by private sources. Connects to tools like Slack, GitHub, Confluence, etc.*
- [**quivr**](https://github.com/StanGirard/quivr) - StanGirard ![Star](https://img.shields.io/github/stars/StanGirard/quivr.svg?style=social&label=Star)

	 *🧠 Dump all your files and thoughts into your private GenerativeAI Second Brain and chat with it 🧠*
- [**chatgpt-retrieval**](https://github.com/techleadhd/chatgpt-retrieval) - techleadhd ![Star](https://img.shields.io/github/stars/techleadhd/chatgpt-retrieval.svg?style=social&label=Star)
- [**localGPT**](https://github.com/PromtEngineer/localGPT) - PromtEngineer ![Star](https://img.shields.io/github/stars/PromtEngineer/localGPT.svg?style=social&label=Star)

	 *Chat with your documents on your local device using GPT models. No data leaves your device and 100% private.*
- [**privateGPT**](https://github.com/imartinez/privateGPT) - imartinez ![Star](https://img.shields.io/github/stars/imartinez/privateGPT.svg?style=social&label=Star)

	 *Interact privately with your documents using the power of GPT, 100% privately, no data leaks*

### Embedding
- [**snowflake-arctic-embed-m**](https://huggingface.co/Snowflake/snowflake-arctic-embed-m) - Snowflake 🤗

	 · ([snowflake](https://www.snowflake.com/blog/introducing-snowflake-arctic-embed-snowflakes-state-of-the-art-text-embedding-family-of-models/))
- [Pile-T5 | EleutherAI Blog](https://blog.eleuther.ai/pile-t5/)

	 · ([huggingface](https://huggingface.co/collections/EleutherAI/pile-t5-65a76a0d0022dd270b385a66)) · ([improved-t5](https://github.com/EleutherAI/improved-t5) - EleutherAI) ![Star](https://img.shields.io/github/stars/EleutherAI/improved-t5.svg?style=social&label=Star)
- **LLM2Vec: Large Language Models Are Secretly Powerful Text Encoders**, `arXiv, 2404.05961`, [arxiv](http://arxiv.org/abs/2404.05961v1), [pdf](http://arxiv.org/pdf/2404.05961v1.pdf), cication: [**-1**](None)

	 *Parishad BehnamGhader, Vaibhav Adlakha, Marius Mosbach, Dzmitry Bahdanau, Nicolas Chapados, Siva Reddy*
- **Gecko: Versatile Text Embeddings Distilled from Large Language Models**, `arXiv, 2403.20327`, [arxiv](http://arxiv.org/abs/2403.20327v1), [pdf](http://arxiv.org/pdf/2403.20327v1.pdf), cication: [**-1**](None)

	 *Jinhyuk Lee, Zhuyun Dai, Xiaoqi Ren, Blair Chen, Daniel Cer, Jeremy R. Cole, Kai Hui, Michael Boratko, Rajvi Kapadia, Wen Ding*

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-04-07-10))
- [**FlagEmbedding**](https://github.com/FlagOpen/FlagEmbedding) - FlagOpen ![Star](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding.svg?style=social&label=Star)

	 *Retrieval and Retrieval-augmented LLMs* · ([huggingface](https://huggingface.co/BAAI/bge-base-en-v1.5))
- [Binary and Scalar Embedding Quantization for Significantly Faster & Cheaper Retrieval](https://huggingface.co/blog/embedding-quantization)
- **Is Cosine-Similarity of Embeddings Really About Similarity?**, `arXiv, 2403.05440`, [arxiv](http://arxiv.org/abs/2403.05440v1), [pdf](http://arxiv.org/pdf/2403.05440v1.pdf), cication: [**-1**](None)

	 *Harald Steck, Chaitanya Ekanadham, Nathan Kallus*
- [**echo-embeddings**](https://github.com/jakespringer/echo-embeddings?tab=readme-ov-file) - jakespringer ![Star](https://img.shields.io/github/stars/jakespringer/echo-embeddings.svg?style=social&label=Star)
- [🪆 Introduction to Matryoshka Embedding Models](https://huggingface.co/blog/matryoshka)
- **Multilingual E5 Text Embeddings: A Technical Report**, `arXiv, 2402.05672`, [arxiv](http://arxiv.org/abs/2402.05672v1), [pdf](http://arxiv.org/pdf/2402.05672v1.pdf), cication: [**-1**](None)

	 *Liang Wang, Nan Yang, Xiaolong Huang, Linjun Yang, Rangan Majumder, Furu Wei* · ([unilm](https://github.com/microsoft/unilm/tree/master/e5) - microsoft) ![Star](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social&label=Star)
- [**contrastors**](https://github.com/nomic-ai/contrastors) - nomic-ai ![Star](https://img.shields.io/github/stars/nomic-ai/contrastors.svg?style=social&label=Star)

	 *Train Models Contrastively in Pytorch* · ([huggingface](https://huggingface.co/nomic-ai/nomic-embed-text-v1)) · ([mp.weixin.qq](https://mp.weixin.qq.com/s/EMWNf9TiDwuxxkwwqsl73g))

---
- [Smaller, Faster, Cheaper: Introducing Jina Rerankers Turbo and Tiny](https://jina.ai/news/smaller-faster-cheaper-jina-rerankers-turbo-and-tiny/)
- [Advanced RAG 10: Corrective Retrieval Augmented Generation (CRAG) | by Florian June | Apr, 2024 | AI Advances](https://ai.gopubby.com/advanced-rag-10-corrective-retrieval-augmented-generation-crag-3f5a140796f9)
- [World's Most Accurate RAG? Langchain/Pinecone, LlamaIndex and EyeLevel Duke it Out](https://www.eyelevel.ai/post/most-accurate-rag)
- [Unlocking the Power of Multi-Document Agents with LlamaIndex | by Ankush k Singal | Apr, 2024 | AI Advances](https://ai.gopubby.com/unlocking-the-power-of-multi-document-agents-with-llamaindex-d09e4d7dfe0e)


	 · ([twitter](https://twitter.com/jerryjliu0/status/1776971813874028694))
- [Cheap RAGs up for grabs: How we cut LLM costs without sacrificing accuracy? | Pathway](https://pathway.com/developers/showcases/adaptive-rag)
- [Introducing RAG 2.0 - Contextual AI](https://contextual.ai/introducing-rag2/)
- [**dspy-gradio-rag**](https://github.com/diicellman/dspy-gradio-rag) - diicellman ![Star](https://img.shields.io/github/stars/diicellman/dspy-gradio-rag.svg?style=social&label=Star)

	 *RAG example using DSPy, Gradio, FastAPI*
- [excellent demo of a highly capable LLM-RAG setup](https://twitter.com/rasbt/status/1765787891349749891)
- [Towards Long Context RAG](https://www.llamaindex.ai/blog/towards-long-context-rag)
- **The First Place Solution of WSDM Cup 2024: Leveraging Large Language
  Models for Conversational Multi-Doc QA**, `arXiv, 2402.18385`, [arxiv](http://arxiv.org/abs/2402.18385v1), [pdf](http://arxiv.org/pdf/2402.18385v1.pdf), cication: [**-1**](None)

	 *Yiming Li, Zhao Zhang*

	 · ([WSDM-Cup-2024](https://github.com/zhangzhao219/WSDM-Cup-2024?tab=readme-ov-file) - zhangzhao219) ![Star](https://img.shields.io/github/stars/zhangzhao219/WSDM-Cup-2024.svg?style=social&label=Star)
- [**chunk_visualizer**](https://huggingface.co/spaces/m-ric/chunk_visualizer) - m-ric 🤗
- [Stanford CS25: V3 I Retrieval Augmented Language Models - YouTube](https://youtu.be/mE7IDf2SmJg)
- [Retrieval Augmented Generation (RAG) for LLMs | Prompt Engineering Guide<!-- -->](https://www.promptingguide.ai/research/rag)
- [A Cheat Sheet and Some Recipes For Building Advanced RAG | by Andrei | Jan, 2024 | LlamaIndex Blog](https://blog.llamaindex.ai/a-cheat-sheet-and-some-recipes-for-building-advanced-rag-803a9d94c41b)
- [Build a search engine, not a vector DB](https://blog.elicit.com/search-vs-vector-db/)

---
- [4W字RAG技术总结和串讲](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495746&idx=2&sn=05772cca38b342f5fa7b683389623ba6)
- [RAG效果评估经验](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495725&idx=2&sn=c6d2b3527041fd2742363b2e0b2d1f44&poc_token=HFaa-2WjKGGmLnBa3yZCBSXFENCcHwsqDs6M5c5Z)
- [微调与RAG的优缺点分析](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495628&idx=2&sn=d65b3370121a1d2bd832c17218bb1090)
- [Langchain中改进RAG能力的3种常用的扩展查询方法](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247630649&idx=2&sn=d02f9e3022d5e987de5d60ed06ea3bd8&poc_token=HO-d1WWjKnv0HWessjo9YkkKt1GkCKEDCJoS3wUW)
- [通过4个任务比较LangChain和LlamaIndex](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247631125&idx=2&sn=97801ab722a786cdf5116779804fb0c9)
- [self-RAG｜大模型决策的典型案例探究](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495565&idx=2&sn=833660e930818b3dfa11a22ce1f263d4)
- [RAG研发真实图鉴：一周出Demo，半年用不好](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495552&idx=2&sn=5dc6957f860fa90afa01f547df71ff02)
- [大模型RAG的迭代路径](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495480&idx=1&sn=71ba95734ab559fb21408993d1800741)
- [大模型RAG问答技术架构及核心模块回顾](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495441&idx=2&sn=cb2cfb2eab441f8a5262ad5b98c1757f)
- [【大模型外挂知识库(RAG)优化】如何炼成强大的向量化召回模型 - 知乎](https://zhuanlan.zhihu.com/p/661867062)
- [RAG调优方案](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495402&idx=2&sn=6222df8ddb5e08ac48d946b7f989ff4e)
- [RAG+GPT-4 Turbo让模型性能飙升！更长上下文不是终局，「大海捞针」实验成本仅4%](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652415774&idx=3&sn=8672aeb9f7cce15c3cb43620873b25bb)
- [问答场景常用大模型解决方案](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247494688&idx=2&sn=d871403a80a7fcf656ce0100f266f939)

## Code Interpreter
- [**instructor**](https://github.com/jxnl/instructor) - jxnl ![Star](https://img.shields.io/github/stars/jxnl/instructor.svg?style=social&label=Star)

	 *structured outputs for llms*
- [**FuzzTypes**](https://github.com/genomoncology/FuzzTypes) - genomoncology ![Star](https://img.shields.io/github/stars/genomoncology/FuzzTypes.svg?style=social&label=Star)

	 *Pydantic extension for annotating autocorrecting fields.*
- [**function-calling-eval**](https://github.com/interstellarninja/function-calling-eval?utm_source=ainews&utm_medium=email&utm_campaign=ainews-mm1-apples-first-large-multimodal-model) - interstellarninja ![Star](https://img.shields.io/github/stars/interstellarninja/function-calling-eval.svg?style=social&label=Star)

	 *A framework for evaluating function calls made by LLMs*
- [**Hermes-Function-Calling**](https://github.com/NousResearch/Hermes-Function-Calling/tree/main?utm_source=ainews&utm_medium=email&utm_campaign=ainews-mm1-apples-first-large-multimodal-model) - NousResearch ![Star](https://img.shields.io/github/stars/NousResearch/Hermes-Function-Calling.svg?style=social&label=Star)
- [**phidata**](https://github.com/phidatahq/phidata) - phidatahq ![Star](https://img.shields.io/github/stars/phidatahq/phidata.svg?style=social&label=Star)

	 *Build AI Assistants using function calling*
- [**open-interpreter**](https://github.com/KillianLucas/open-interpreter) - KillianLucas ![Star](https://img.shields.io/github/stars/KillianLucas/open-interpreter.svg?style=social&label=Star)

	 *OpenAI's Code Interpreter in your terminal, running locally*

## GPTs
- [**awesome-prompts**](https://github.com/ai-boost/awesome-prompts) - ai-boost ![Star](https://img.shields.io/github/stars/ai-boost/awesome-prompts.svg?style=social&label=Star)

	 *Curated list of chatgpt prompts from the top-rated GPTs in the GPTs Store. Prompt Engineering, prompt attack & prompt protect. Advanced Prompt Engineering papers.*
- [**BlackFriday-GPTs-Prompts**](https://github.com/friuns2/BlackFriday-GPTs-Prompts) - friuns2 ![Star](https://img.shields.io/github/stars/friuns2/BlackFriday-GPTs-Prompts.svg?style=social&label=Star)

	 *List of free GPTs that doesn't require plus subscription*
- [**GPTs**](https://github.com/linexjlin/GPTs) - linexjlin ![Star](https://img.shields.io/github/stars/linexjlin/GPTs.svg?style=social&label=Star)

	 *leaked prompts of GPTs*
- [**rags**](https://github.com/run-llama/rags) - run-llama ![Star](https://img.shields.io/github/stars/run-llama/rags.svg?style=social&label=Star)
- [**GPT-Baker**](https://huggingface.co/spaces/abidlabs/GPT-Baker) - abidlabs 🤗
- [**gpts-works**](https://github.com/all-in-aigc/gpts-works) - all-in-aigc ![Star](https://img.shields.io/github/stars/all-in-aigc/gpts-works.svg?style=social&label=Star)

	 *A Third-party GPTs store*
- [**gpt-crawler**](https://github.com/BuilderIO/gpt-crawler) - BuilderIO ![Star](https://img.shields.io/github/stars/BuilderIO/gpt-crawler.svg?style=social&label=Star)

	 *Crawl a site to generate knowledge files to create your own custom GPT from a URL*
- [**Awesome-GPTs**](https://github.com/ai-boost/Awesome-GPTs) - ai-boost ![Star](https://img.shields.io/github/stars/ai-boost/Awesome-GPTs.svg?style=social&label=Star)

	 *Curated list of awesome GPTs 👍.*
- [**Awesome-GPT-Agents**](https://github.com/fr0gger/Awesome-GPT-Agents) - fr0gger ![Star](https://img.shields.io/github/stars/fr0gger/Awesome-GPT-Agents.svg?style=social&label=Star)

	 *A curated list of GPT agents for cybersecurity*
- [**Awesome-GPT-Store**](https://github.com/Anil-matcha/Awesome-GPT-Store) - Anil-matcha ![Star](https://img.shields.io/github/stars/Anil-matcha/Awesome-GPT-Store.svg?style=social&label=Star)

	 *A collection of major GPTS available in public*
- [**awesome-gpts**](https://github.com/taranjeet/awesome-gpts) - taranjeet ![Star](https://img.shields.io/github/stars/taranjeet/awesome-gpts.svg?style=social&label=Star)

	 *Collection of all the GPTs created by the community*
- [**opengpts**](https://github.com/langchain-ai/opengpts) - langchain-ai ![Star](https://img.shields.io/github/stars/langchain-ai/opengpts.svg?style=social&label=Star)

### Plugins
- [GPT-4调用插件40次都没成功，果断放弃，无效调用、拒绝回答时有发生 | 机器之心](https://www.jiqizhixin.com/articles/2023-08-12)k
### Other 
- [Featured GPTs | Best Curated Custom GPTs List for your Daily Tasks](https://www.featuredgpts.com/)
- [Discover the Best GPTs](https://supertools.therundown.ai/gpts)
- [AI of the day by SamurAI](https://www.thesamur.ai/ai-of-the-day)
- [各路大神献出自定义GPT，24小时Top 9名单在这 | 机器之心](https://www.jiqizhixin.com/articles/2023-11-13-13)

## Evaluation
- [**stark**](https://github.com/snap-stanford/stark) - snap-stanford ![Star](https://img.shields.io/github/stars/snap-stanford/stark.svg?style=social&label=Star)

	 *Official Code of "STaRK: Benchmarking LLM Retrieval on Textual and Relational Knowledge Bases"*
- **MMInA: Benchmarking Multihop Multimodal Internet Agents**, `arXiv, 2404.09992`, [arxiv](http://arxiv.org/abs/2404.09992v1), [pdf](http://arxiv.org/pdf/2404.09992v1.pdf), cication: [**-1**](None)

	 *Ziniu Zhang, Shulin Tian, Liangyu Chen, Ziwei Liu* · ([mmina.cliangyu](https://mmina.cliangyu.com))
- **AgentBoard: An Analytical Evaluation Board of Multi-turn LLM Agents**, `arXiv, 2401.13178`, [arxiv](http://arxiv.org/abs/2401.13178v1), [pdf](http://arxiv.org/pdf/2401.13178v1.pdf), cication: [**-1**](None)

	 *Chang Ma, Junlei Zhang, Zhihao Zhu, Cheng Yang, Yujiu Yang, Yaohui Jin, Zhenzhong Lan, Lingpeng Kong, Junxian He* · ([AgentBoard](https://github.com/hkust-nlp/AgentBoard) - hkust-nlp) ![Star](https://img.shields.io/github/stars/hkust-nlp/AgentBoard.svg?style=social&label=Star)
- [**codefuse-devops-eval**](https://github.com/codefuse-ai/codefuse-devops-eval) - codefuse-ai ![Star](https://img.shields.io/github/stars/codefuse-ai/codefuse-devops-eval.svg?style=social&label=Star)

	 *Industrial-first evaluation benchmark for LLMs in the DevOps/AIOps domain.*
- **GAIA: a benchmark for General AI Assistants**, `arXiv, 2311.12983`, [arxiv](http://arxiv.org/abs/2311.12983v1), [pdf](http://arxiv.org/pdf/2311.12983v1.pdf), cication: [**-1**](None)

	 *Grégoire Mialon, Clémentine Fourrier, Craig Swift, Thomas Wolf, Yann LeCun, Thomas Scialom* · ([huggingface](https://huggingface.co/gaia-benchmark))
- **Testing Language Model Agents Safely in the Wild**, `arXiv, 2311.10538`, [arxiv](http://arxiv.org/abs/2311.10538v1), [pdf](http://arxiv.org/pdf/2311.10538v1.pdf), cication: [**-1**](None)

	 *Silen Naihin, David Atkinson, Marc Green, Merwane Hamadi, Craig Swift, Douglas Schonholtz, Adam Tauman Kalai, David Bau*
- **BOLAA: Benchmarking and Orchestrating LLM-augmented Autonomous Agents**, `arXiv, 2308.05960`, [arxiv](http://arxiv.org/abs/2308.05960v1), [pdf](http://arxiv.org/pdf/2308.05960v1.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=7461840210213149264&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhiwei Liu, Weiran Yao, Jianguo Zhang, Le Xue, Shelby Heinecke, Rithesh Murthy, Yihao Feng, Zeyuan Chen, Juan Carlos Niebles, Devansh Arpit* · ([BOLAA](https://github.com/salesforce/BOLAA) - salesforce) ![Star](https://img.shields.io/github/stars/salesforce/BOLAA.svg?style=social&label=Star)
- [**mlagentbench**](https://github.com/snap-stanford/mlagentbench) - snap-stanford ![Star](https://img.shields.io/github/stars/snap-stanford/mlagentbench.svg?style=social&label=Star)
- [**smartplay**](https://github.com/microsoft/smartplay) - microsoft ![Star](https://img.shields.io/github/stars/microsoft/smartplay.svg?style=social&label=Star)

	 *SmartPlay is a benchmark for Large Language Models (LLMs). It is designed to be easy to use, and to provide a wide variety of games to test agents on.*
- **AgentBench: Evaluating LLMs as Agents**, `arXiv, 2308.03688`, [arxiv](http://arxiv.org/abs/2308.03688v2), [pdf](http://arxiv.org/pdf/2308.03688v2.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=17298865796446863019&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xiao Liu, Hao Yu, Hanchen Zhang, Yifan Xu, Xuanyu Lei, Hanyu Lai, Yu Gu, Hangliang Ding, Kaiwen Men, Kejuan Yang*

## Other
- [How to evaluate an LLM-powered RAG application automatically. - YouTube](https://www.youtube.com/watch?v=ZPX3W77h_1E&t=3s&ab_channel=Underfitted)
- [What's next for AI agentic workflows ft. Andrew Ng of AI Fund - YouTube](https://www.youtube.com/watch?v=sal78ACtGTc&t=108)

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-04-01-6))
- [**Nexus_Function_Calling_Leaderboard**](https://huggingface.co/spaces/Nexusflow/Nexus_Function_Calling_Leaderboard) - Nexusflow 🤗
- [Learning few-shot imitation as cultural transmission | Nature Communications](https://www.nature.com/articles/s41467-023-42875-2)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247619960&idx=2&sn=1e1e4e21b2a8ffbeb08fc4f7dcd0932c))
- [Rapidly build an application in Gradio power by a Generative AI Agent | Google Cloud Blog](https://cloud.google.com/blog/products/ai-machine-learning/rapidly-build-an-application-in-gradio-power-by-a-generative-ai-agent)

- [吴恩达：AI智能体工作流今年将有巨大进展，可能超过下一代基础模型 | 机器之心](https://www.jiqizhixin.com/articles/2024-03-22-3)
- [从第一性原理看大模型Agent技术](https://mp.weixin.qq.com/s?__biz=MzAxMTk4NDkwNw==&mid=2247495233&idx=1&sn=a6f99f5ed298dc4dad8477979d0c19a8)
- [万字长文！何谓Agent，为何Agent？](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247620278&idx=1&sn=6d0171c6bc1d97fb0872dbaa7aea4e0a)
- [首个获得驾照的AI！Agent担任私人助理样样精通，还能帮助考试作弊](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652412307&idx=4&sn=f02fe42f4de8c01cac8c0a719b9966bf)
- [多智能体(Agents)协作框架：人工智能的下一个方向和挑战](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247619958&idx=3&sn=8dc113e0eae29f08d1185389588faf8a)
- [Agent 将是 AI 最大的赛道！](https://mp.weixin.qq.com/s?__biz=MzIyMzk1MDE3Nw==&mid=2247619501&idx=4&sn=2daf3a6609fb0e73dead22fac0404619)


## Vector Database
- [**awesome-vector-database**](https://github.com/dangkhoasdc/awesome-vector-database) - dangkhoasdc ![Star](https://img.shields.io/github/stars/dangkhoasdc/awesome-vector-database.svg?style=social&label=Star)

	 *A curated list of awesome works related to high dimensional structure/vector search & database*
- [How to choose your vector database in 2023?](https://www.sicara.fr/blog-technique/how-to-choose-your-vector-database-in-2023)

	 · ([youtube](https://www.youtube.com/watch?v=0g4w3xgLoVE&ab_channel=DVCorg))

### Other
- [GPT成功背后的秘密--向量数据库简介 - 知乎](https://zhuanlan.zhihu.com/p/627254037)
- [7个向量数据库对比：Milvus、Pinecone、Vespa、Weaviate、Vald、GSI 和 Qdrant - 墨天轮](https://www.modb.pro/db/516016#:~:text=%E8%BF%99%E7%AF%87%E5%8D%9A%E6%96%87%E6%80%BB%E7%BB%93%E4%BA%86%207,%E4%B8%AA%E5%90%91%20%E9%87%8F%20%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B9%8B%E9%97%B4%E7%9A%84%E5%85%B1%E6%80%A7%E5%92%8C%E5%B7%AE%E5%BC%82%EF%BC%8C%E6%AF%8F%E4%B8%AA%E9%83%BD%E6%8F%90%E4%BE%9B%E5%95%86%E4%B8%9A%E4%BA%91%E6%94%AF%E6%8C%81%E3%80%82)

## Extra reference
- [**awesome-large-multimodal-agents**](https://github.com/jun0wanan/awesome-large-multimodal-agents) - jun0wanan ![Star](https://img.shields.io/github/stars/jun0wanan/awesome-large-multimodal-agents.svg?style=social&label=Star)
- [**llm-agent-survey**](https://github.com/paitesanshi/llm-agent-survey) - paitesanshi ![Star](https://img.shields.io/github/stars/paitesanshi/llm-agent-survey.svg?style=social&label=Star)
- [**awesome-ai-agents**](https://github.com/e2b-dev/awesome-ai-agents) - e2b-dev ![Star](https://img.shields.io/github/stars/e2b-dev/awesome-ai-agents.svg?style=social&label=Star)

	 *A list of AI autonomous agents*
- [**generative_agents**](https://github.com/joonspk-research/generative_agents) - joonspk-research ![Star](https://img.shields.io/github/stars/joonspk-research/generative_agents.svg?style=social&label=Star)

	 *Generative Agents: Interactive Simulacra of Human Behavior*