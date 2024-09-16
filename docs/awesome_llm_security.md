#  Awesome llm security

- [Awesome llm security](#awesome-llm-security)
	- [Survey](#survey)
	- [Papers](#papers)
	- [Projects](#projects)
	- [Other](#other)
	- [Extra reference](#extra-reference)


## Survey
- **AI Deception: A Survey of Examples, Risks, and Potential Solutions**, `patterns, 2024`, [arxiv](http://arxiv.org/abs/2308.14752v1), [pdf](http://arxiv.org/pdf/2308.14752v1.pdf), cication: [**78**](https://scholar.google.com/scholar?cites=6393651602609022233&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Peter S. Park, Simon Goldstein, Aidan O'Gara, Michael Chen, Dan Hendrycks*
- **JailbreakZoo: Survey, Landscapes, and Horizons in Jailbreaking Large
  Language and Vision-Language Models**, `arXiv, 2407.01599`, [arxiv](http://arxiv.org/abs/2407.01599v1), [pdf](http://arxiv.org/pdf/2407.01599v1.pdf), cication: [**-1**](None)

	 *Haibo Jin, Leyang Hu, Xinuo Li, Peiyan Zhang, Chonghan Chen, Jun Zhuang, Haohan Wang*

	 · ([chonghan-chen](https://chonghan-chen.com/llm-jailbreak-zoo-survey/)) · ([JailbreakZoo](https://github.com/Allen-piexl/JailbreakZoo) - Allen-piexl) ![Star](https://img.shields.io/github/stars/Allen-piexl/JailbreakZoo.svg?style=social&label=Star)
- **Against The Achilles' Heel: A Survey on Red Teaming for Generative
  Models**, `arXiv, 2404.00629`, [arxiv](http://arxiv.org/abs/2404.00629v1), [pdf](http://arxiv.org/pdf/2404.00629v1.pdf), cication: [**-1**](None)

	 *Lizhi Lin, Honglin Mu, Zenan Zhai, Minghan Wang, Yuxia Wang, Renxi Wang, Junjie Gao, Yixuan Zhang, Wanxiang Che, Timothy Baldwin*
- **Breaking Down the Defenses: A Comparative Survey of Attacks on Large
  Language Models**, `arXiv, 2403.04786`, [arxiv](http://arxiv.org/abs/2403.04786v1), [pdf](http://arxiv.org/pdf/2403.04786v1.pdf), cication: [**-1**](None)

	 *Arijit Ghosh Chowdhury, Md Mofijul Islam, Vaibhav Kumar, Faysal Hossain Shezan, Vaibhav Kumar, Vinija Jain, Aman Chadha*
- **Open-Sourcing Highly Capable Foundation Models: An evaluation of risks,
  benefits, and alternative methods for pursuing open-source objectives**, `arXiv, 2311.09227`, [arxiv](http://arxiv.org/abs/2311.09227v1), [pdf](http://arxiv.org/pdf/2311.09227v1.pdf), cication: [**-1**](None)

	 *Elizabeth Seger, Noemi Dreksler, Richard Moulange, Emily Dardaman, Jonas Schuett, K. Wei, Christoph Winter, Mackenzie Arnold, Seán Ó hÉigeartaigh, Anton Korinek*
- [**Adversarial Attacks on LLMs | Lil'Log**](https://lilianweng.github.io/posts/2023-10-25-adv-attack-llm/)

## Red teaming
- **Ferret: Faster and Effective Automated Red Teaming with Reward-Based
  Scoring Technique**, `arXiv, 2408.10701`, [arxiv](http://arxiv.org/abs/2408.10701v1), [pdf](http://arxiv.org/pdf/2408.10701v1.pdf), cication: [**-1**](None)

	 *Tej Deep Pala, Vernon Y. H. Toh, Rishabh Bhardwaj, Soujanya Poria* · ([ferret](https://github.com/declare-lab/ferret) - declare-lab) ![Star](https://img.shields.io/github/stars/declare-lab/ferret.svg?style=social&label=Star)
- [Challenges in Red Teaming AI Systems \\ Anthropic](https://www.anthropic.com/news/challenges-in-red-teaming-ai-systems)
- **ALERT: A Comprehensive Benchmark for Assessing Large Language Models'
  Safety through Red Teaming**, `arXiv, 2404.08676`, [arxiv](http://arxiv.org/abs/2404.08676v1), [pdf](http://arxiv.org/pdf/2404.08676v1.pdf), cication: [**-1**](None)

	 *Simone Tedeschi, Felix Friedrich, Patrick Schramowski, Kristian Kersting, Roberto Navigli, Huu Nguyen, Bo Li*

	 · ([ALERT](https://github.com/Babelscape/ALERT) - Babelscape) ![Star](https://img.shields.io/github/stars/Babelscape/ALERT.svg?style=social&label=Star)
- [Red-Teaming Language Models with DSPy | Haize Labs Blog 🕊️](https://blog.haizelabs.com/posts/dspy/)
- [Curiosity-driven Red-teaming for Large Language Models](https://openreview.net/pdf?id=4KqkizXgXU)

	 · ([curiosity_redteam](https://github.com/Improbable-AI/curiosity_redteam) - Improbable-AI) ![Star](https://img.shields.io/github/stars/Improbable-AI/curiosity_redteam.svg?style=social&label=Star)
- **Recourse for reclamation: Chatting with generative language models**, `arXiv, 2403.14467`, [arxiv](http://arxiv.org/abs/2403.14467v1), [pdf](http://arxiv.org/pdf/2403.14467v1.pdf), cication: [**-1**](None)

	 *Jennifer Chien, Kevin R. McKee, Jackie Kay, William Isaac*
- **Evaluating Frontier Models for Dangerous Capabilities**, `arXiv, 2403.13793`, [arxiv](http://arxiv.org/abs/2403.13793v1), [pdf](http://arxiv.org/pdf/2403.13793v1.pdf), cication: [**-1**](None)

	 *Mary Phuong, Matthew Aitchison, Elliot Catt, Sarah Cogan, Alexandre Kaskasoli, Victoria Krakovna, David Lindner, Matthew Rahtz, Yannis Assael, Sarah Hodkinson*
- **A Safe Harbor for AI Evaluation and Red Teaming**, `arXiv, 2403.04893`, [arxiv](http://arxiv.org/abs/2403.04893v1), [pdf](http://arxiv.org/pdf/2403.04893v1.pdf), cication: [**-1**](None)

	 *Shayne Longpre, Sayash Kapoor, Kevin Klyman, Ashwin Ramaswami, Rishi Bommasani, Borhane Blili-Hamelin, Yangsibo Huang, Aviya Skowron, Zheng-Xin Yong, Suhas Kotha*
- **Rainbow Teaming: Open-Ended Generation of Diverse Adversarial Prompts**, `arXiv, 2402.16822`, [arxiv](http://arxiv.org/abs/2402.16822v1), [pdf](http://arxiv.org/pdf/2402.16822v1.pdf), cication: [**-1**](None)

	 *Mikayel Samvelyan, Sharath Chandra Raparthy, Andrei Lupu, Eric Hambro, Aram H. Markosyan, Manish Bhatt, Yuning Mao, Minqi Jiang, Jack Parker-Holder, Jakob Foerster*
- **MART: Improving LLM Safety with Multi-round Automatic Red-Teaming**, `arXiv, 2311.07689`, [arxiv](http://arxiv.org/abs/2311.07689v1), [pdf](http://arxiv.org/pdf/2311.07689v1.pdf), cication: [**-1**](None)

	 *Suyu Ge, Chunting Zhou, Rui Hou, Madian Khabsa, Yi-Chia Wang, Qifan Wang, Jiawei Han, Yuning Mao*
- **Summon a Demon and Bind it: A Grounded Theory of LLM Red Teaming in the
  Wild**, `arXiv, 2311.06237`, [arxiv](http://arxiv.org/abs/2311.06237v2), [pdf](http://arxiv.org/pdf/2311.06237v2.pdf), cication: [**-1**](None)

	 *Nanna Inie, Jonathan Stray, Leon Derczynski*
- **Moral Foundations of Large Language Models**, `arXiv, 2310.15337`, [arxiv](http://arxiv.org/abs/2310.15337v1), [pdf](http://arxiv.org/pdf/2310.15337v1.pdf), cication: [**7**](https://scholar.google.com/scholar?cites=2033876937451648547&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Marwa Abdulhai, Gregory Serapio-Garcia, Clément Crepy, Daria Valter, John Canny, Natasha Jaques*
- **FLIRT: Feedback Loop In-context Red Teaming**, `arXiv, 2308.04265`, [arxiv](http://arxiv.org/abs/2308.04265v1), [pdf](http://arxiv.org/pdf/2308.04265v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=3679628265599247085&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ninareh Mehrabi, Palash Goyal, Christophe Dupuy, Qian Hu, Shalini Ghosh, Richard Zemel, Kai-Wei Chang, Aram Galstyan, Rahul Gupta*
- **Explore, Establish, Exploit: Red Teaming Language Models from Scratch**, `arXiv, 2306.09442`, [arxiv](http://arxiv.org/abs/2306.09442v3), [pdf](http://arxiv.org/pdf/2306.09442v3.pdf), cication: [**16**](https://scholar.google.com/scholar?cites=17596552078024127407&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Stephen Casper, Jason Lin, Joe Kwon, Gatlen Culp, Dylan Hadfield-Menell*

## Papers
- [How to Evaluate Jailbreak Methods: A Case Study with the StrongREJECT Benchmark – The Berkeley Artificial Intelligence Research Blog](https://bair.berkeley.edu/blog/2024/08/28/strong-reject/)
- **CYBERSECEVAL 3: Advancing the Evaluation of Cybersecurity Risks and
  Capabilities in Large Language Models**, `arXiv, 2408.01605`, [arxiv](http://arxiv.org/abs/2408.01605v1), [pdf](http://arxiv.org/pdf/2408.01605v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=12377625893403588904&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Shengye Wan, Cyrus Nikolaidis, Daniel Song, David Molnar, James Crnkovich, Jayson Grace, Manish Bhatt, Sahana Chennabasappa, Spencer Whitman, Stephanie Ding*
- **Efficient Detection of Toxic Prompts in Large Language Models**, `arXiv, 2408.11727`, [arxiv](http://arxiv.org/abs/2408.11727v1), [pdf](http://arxiv.org/pdf/2408.11727v1.pdf), cication: [**-1**](None)

	 *Yi Liu, Junzhe Yu, Huijia Sun, Ling Shi, Gelei Deng, Yuqi Chen, Yang Liu*
- **BackdoorLLM: A Comprehensive Benchmark for Backdoor Attacks on Large
  Language Models**, `arXiv, 2408.12798`, [arxiv](http://arxiv.org/abs/2408.12798v1), [pdf](http://arxiv.org/pdf/2408.12798v1.pdf), cication: [**-1**](None)

	 *Yige Li, Hanxun Huang, Yunhan Zhao, Xingjun Ma, Jun Sun* · ([BackdoorLLM](https://github.com/bboylyg/BackdoorLLM) - bboylyg) ![Star](https://img.shields.io/github/stars/bboylyg/BackdoorLLM.svg?style=social&label=Star)
- **Empirical Analysis of Large Vision-Language Models against Goal
  Hijacking via Visual Prompt Injection**, `arXiv, 2408.03554`, [arxiv](http://arxiv.org/abs/2408.03554v1), [pdf](http://arxiv.org/pdf/2408.03554v1.pdf), cication: [**-1**](None)

	 *Subaru Kimura, Ryota Tanaka, Shumpei Miyawaki, Jun Suzuki, Keisuke Sakaguchi*
- **Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risk
  of Language Models**, `arXiv, 2408.08926`, [arxiv](http://arxiv.org/abs/2408.08926v1), [pdf](http://arxiv.org/pdf/2408.08926v1.pdf), cication: [**-1**](None)

	 *Andy K. Zhang, Neil Perry, Riya Dulepet, Eliot Jones, Justin W. Lin, Joey Ji, Celeste Menders, Gashon Hussein, Samantha Liu, Donovan Jasper* · ([cybench](https://github.com/andyzorigin/cybench) - andyzorigin) ![Star](https://img.shields.io/github/stars/andyzorigin/cybench.svg?style=social&label=Star)
- **WalledEval: A Comprehensive Safety Evaluation Toolkit for Large Language
  Models**, `arXiv, 2408.03837`, [arxiv](http://arxiv.org/abs/2408.03837v1), [pdf](http://arxiv.org/pdf/2408.03837v1.pdf), cication: [**-1**](None)

	 *Prannaya Gupta, Le Qi Yau, Hao Han Low, I-Shiang Lee, Hugo Maximus Lim, Yu Xin Teoh, Jia Hng Koh, Dar Win Liew, Rishabh Bhardwaj, Rajat Bhardwaj*
- **ShieldGemma: Generative AI Content Moderation Based on Gemma**, `arXiv, 2407.21772`, [arxiv](http://arxiv.org/abs/2407.21772v2), [pdf](http://arxiv.org/pdf/2407.21772v2.pdf), cication: [**-1**](None)

	 *Wenjun Zeng, Yuchi Liu, Ryan Mullins, Ludovic Peran, Joe Fernandez, Hamza Harkous, Karthik Narasimhan, Drew Proud, Piyush Kumar, Bhaktipriya Radharapu* · ([huggingface](https://huggingface.co/google/shieldgemma-2b))
- **AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge
  Bases**, `arXiv, 2407.12784`, [arxiv](http://arxiv.org/abs/2407.12784v1), [pdf](http://arxiv.org/pdf/2407.12784v1.pdf), cication: [**-1**](None)

	 *Zhaorun Chen, Zhen Xiang, Chaowei Xiao, Dawn Song, Bo Li*
- **Towards Guaranteed Safe AI: A Framework for Ensuring Robust and Reliable
  AI Systems**, `arXiv, 2405.06624`, [arxiv](http://arxiv.org/abs/2405.06624v3), [pdf](http://arxiv.org/pdf/2405.06624v3.pdf), cication: [**12**](https://scholar.google.com/scholar?cites=12483606360867487294&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *David "davidad" Dalrymple, Joar Skalse, Yoshua Bengio, Stuart Russell, Max Tegmark, Sanjit Seshia, Steve Omohundro, Christian Szegedy, Ben Goldhaber, Nora Ammann* · ([mp.weixin.qq](https://mp.weixin.qq.com/s/tDa46iKHeLqJS39PamnAPw))
- **The GPT Dilemma: Foundation Models and the Shadow of Dual-Use**, `arXiv, 2407.20442`, [arxiv](http://arxiv.org/abs/2407.20442v1), [pdf](http://arxiv.org/pdf/2407.20442v1.pdf), cication: [**-1**](None)

	 *Alan Hickey*
- [Improving Model Safety Behavior with Rule-Based Rewards | OpenAI](https://openai.com/index/improving-model-safety-behavior-with-rule-based-rewards/)

	 · ([cdn.openai](https://cdn.openai.com/rule-based-rewards-for-language-model-safety.pdf)) · ([safety-rbr-code-and-data](https://github.com/openai/safety-rbr-code-and-data) - openai) ![Star](https://img.shields.io/github/stars/openai/safety-rbr-code-and-data.svg?style=social&label=Star)
- **Safe Unlearning: A Surprisingly Effective and Generalizable Solution to
  Defend Against Jailbreak Attacks**, `arXiv, 2407.02855`, [arxiv](http://arxiv.org/abs/2407.02855v1), [pdf](http://arxiv.org/pdf/2407.02855v1.pdf), cication: [**-1**](None)

	 *Zhexin Zhang, Junxiao Yang, Pei Ke, Shiyao Cui, Chujie Zheng, Hongning Wang, Minlie Huang*

	 · ([SafeUnlearning](https://github.com/thu-coai/SafeUnlearning) - thu-coai) ![Star](https://img.shields.io/github/stars/thu-coai/SafeUnlearning.svg?style=social&label=Star)
- **WildGuard: Open One-Stop Moderation Tools for Safety Risks, Jailbreaks,
  and Refusals of LLMs**, `arXiv, 2406.18495`, [arxiv](http://arxiv.org/abs/2406.18495v1), [pdf](http://arxiv.org/pdf/2406.18495v1.pdf), cication: [**-1**](None)

	 *Seungju Han, Kavel Rao, Allyson Ettinger, Liwei Jiang, Bill Yuchen Lin, Nathan Lambert, Yejin Choi, Nouha Dziri*
- **Jailbreaking as a Reward Misspecification Problem**, `arXiv, 2406.14393`, [arxiv](http://arxiv.org/abs/2406.14393v1), [pdf](http://arxiv.org/pdf/2406.14393v1.pdf), cication: [**-1**](None)

	 *Zhihui Xie, Jiahui Gao, Lei Li, Zhenguo Li, Qi Liu, Lingpeng Kong*
- **Adversarial Attacks on Multimodal Agents**, `arXiv, 2406.12814`, [arxiv](http://arxiv.org/abs/2406.12814v1), [pdf](http://arxiv.org/pdf/2406.12814v1.pdf), cication: [**-1**](None)

	 *Chen Henry Wu, Jing Yu Koh, Ruslan Salakhutdinov, Daniel Fried, Aditi Raghunathan* · ([agent-attack](https://github.com/ChenWu98/agent-attack) - ChenWu98) ![Star](https://img.shields.io/github/stars/ChenWu98/agent-attack.svg?style=social&label=Star)
- **Merging Improves Self-Critique Against Jailbreak Attacks**, `arXiv, 2406.07188`, [arxiv](http://arxiv.org/abs/2406.07188v1), [pdf](http://arxiv.org/pdf/2406.07188v1.pdf), cication: [**-1**](None)

	 *Victor Gallego*

	 · ([merging-self-critique-jailbreaks](https://github.com/vicgalle/merging-self-critique-jailbreaks) - vicgalle) ![Star](https://img.shields.io/github/stars/vicgalle/merging-self-critique-jailbreaks.svg?style=social&label=Star)
- **LLM Agents can Autonomously Exploit One-day Vulnerabilities**, `arXiv, 2404.08144`, [arxiv](http://arxiv.org/abs/2404.08144v2), [pdf](http://arxiv.org/pdf/2404.08144v2.pdf), cication: [**-1**](None)

	 *Richard Fang, Rohan Bindu, Akul Gupta, Daniel Kang* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247567179&idx=1&sn=52b0e7927174e9c1e235b109165ce1e6))
- **Introducing v0.5 of the AI Safety Benchmark from MLCommons**, `arXiv, 2404.12241`, [arxiv](http://arxiv.org/abs/2404.12241v1), [pdf](http://arxiv.org/pdf/2404.12241v1.pdf), cication: [**-1**](None)

	 *Bertie Vidgen, Adarsh Agrawal, Ahmed M. Ahmed, Victor Akinwande, Namir Al-Nuaimi, Najla Alfaraj, Elie Alhajjar, Lora Aroyo, Trupti Bavalatti, Borhane Blili-Hamelin*
- [**PrivacyBackdoor**](https://github.com/ShanglunFengatETHZ/PrivacyBackdoor) - ShanglunFengatETHZ ![Star](https://img.shields.io/github/stars/ShanglunFengatETHZ/PrivacyBackdoor.svg?style=social&label=Star)

	 *Privacy backdoors*
- [What Was Your Prompt? A Remote Keylogging Attack on AI Assistants](https://cdn.arstechnica.net/wp-content/uploads/2024/03/LLM-Side-Channel.pdf)

	 · ([youtu](https://youtu.be/UfenH7xKO1s)) · ([twitter](https://twitter.com/felix_red_panda/status/1769363356094230837?t=JMMb3OldqfhhCH8X5e7ljA&s=09))
- **JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large
  Language Models**, `arXiv, 2404.01318`, [arxiv](http://arxiv.org/abs/2404.01318v1), [pdf](http://arxiv.org/pdf/2404.01318v1.pdf), cication: [**-1**](None)

	 *Patrick Chao, Edoardo Debenedetti, Alexander Robey, Maksym Andriushchenko, Francesco Croce, Vikash Sehwag, Edgar Dobriban, Nicolas Flammarion, George J. Pappas, Florian Tramer*
- **What's in Your "Safe" Data?: Identifying Benign Data that Breaks Safety**, `arXiv, 2404.01099`, [arxiv](http://arxiv.org/abs/2404.01099v1), [pdf](http://arxiv.org/pdf/2404.01099v1.pdf), cication: [**-1**](None)

	 *Luxi He, Mengzhou Xia, Peter Henderson*
- [Many-shot Jailbreaking](https://cdn.sanity.io/files/4zrzovbb/website/af5633c94ed2beb282f6a53c595eb437e8e7b630.pdf)

	 · ([anthropic](https://www.anthropic.com/research/many-shot-jailbreaking))
	- ` it includes a very large number of faux dialogues (~256) preceding the final question which effectively steers the model to produce harmful responses.`
- **Don't Listen To Me: Understanding and Exploring Jailbreak Prompts of
  Large Language Models**, `arXiv, 2403.17336`, [arxiv](http://arxiv.org/abs/2403.17336v1), [pdf](http://arxiv.org/pdf/2403.17336v1.pdf), cication: [**-1**](None)

	 *Zhiyuan Yu, Xiaogeng Liu, Shunning Liang, Zach Cameron, Chaowei Xiao, Ning Zhang*
- **Decoding Compressed Trust: Scrutinizing the Trustworthiness of Efficient
  LLMs Under Compression**, `arXiv, 2403.15447`, [arxiv](http://arxiv.org/abs/2403.15447v1), [pdf](http://arxiv.org/pdf/2403.15447v1.pdf), cication: [**-1**](None)

	 *Junyuan Hong, Jinhao Duan, Chenhui Zhang, Zhangheng Li, Chulin Xie, Kelsey Lieberman, James Diffenderfer, Brian Bartoldson, Ajay Jaiswal, Kaidi Xu*

	 · ([decoding-comp-trust.github](https://decoding-comp-trust.github.io/))
	- ` quantization is better than pruning for maintaining efficiency and trustworthiness.`

- **SafeDecoding: Defending against Jailbreak Attacks via Safety-Aware
  Decoding**, `arXiv, 2402.08983`, [arxiv](http://arxiv.org/abs/2402.08983v2), [pdf](http://arxiv.org/pdf/2402.08983v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=12112148021973739744&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Zhangchen Xu, Fengqing Jiang, Luyao Niu, Jinyuan Jia, Bill Yuchen Lin, Radha Poovendran* · ([SafeDecoding](https://github.com/uw-nsl/SafeDecoding) - uw-nsl) ![Star](https://img.shields.io/github/stars/uw-nsl/SafeDecoding.svg?style=social&label=Star)
- **DrAttack: Prompt Decomposition and Reconstruction Makes Powerful LLM
  Jailbreakers**, `arXiv, 2402.16914`, [arxiv](http://arxiv.org/abs/2402.16914v1), [pdf](http://arxiv.org/pdf/2402.16914v1.pdf), cication: [**-1**](None)

	 *Xirui Li, Ruochen Wang, Minhao Cheng, Tianyi Zhou, Cho-Jui Hsieh* · ([DrAttack](https://github.com/xirui-li/DrAttack) - xirui-li) ![Star](https://img.shields.io/github/stars/xirui-li/DrAttack.svg?style=social&label=Star)
- **Coercing LLMs to do and reveal (almost) anything**, `arXiv, 2402.14020`, [arxiv](http://arxiv.org/abs/2402.14020v1), [pdf](http://arxiv.org/pdf/2402.14020v1.pdf), cication: [**-1**](None)

	 *Jonas Geiping, Alex Stein, Manli Shu, Khalid Saifullah, Yuxin Wen, Tom Goldstein*
- **How Easy is It to Fool Your Multimodal LLMs? An Empirical Analysis on
  Deceptive Prompts**, `arXiv, 2402.13220`, [arxiv](http://arxiv.org/abs/2402.13220v1), [pdf](http://arxiv.org/pdf/2402.13220v1.pdf), cication: [**-1**](None)

	 *Yusu Qian, Haotian Zhang, Yinfei Yang, Zhe Gan*
- **LLM Agents can Autonomously Hack Websites**, `arXiv, 2402.06664`, [arxiv](http://arxiv.org/abs/2402.06664v3), [pdf](http://arxiv.org/pdf/2402.06664v3.pdf), cication: [**-1**](None)

	 *Richard Fang, Rohan Bindu, Akul Gupta, Qiusi Zhan, Daniel Kang*
- **Robust Prompt Optimization for Defending Language Models Against
  Jailbreaking Attacks**, `arXiv, 2401.17263`, [arxiv](http://arxiv.org/abs/2401.17263v1), [pdf](http://arxiv.org/pdf/2401.17263v1.pdf), cication: [**-1**](None)

	 *Andy Zhou, Bo Li, Haohan Wang* · ([rpo](https://github.com/andyz245/rpo) - andyz245) ![Star](https://img.shields.io/github/stars/andyz245/rpo.svg?style=social&label=Star)
- **A Cross-Language Investigation into Jailbreak Attacks in Large Language
  Models**, `arXiv, 2401.16765`, [arxiv](http://arxiv.org/abs/2401.16765v1), [pdf](http://arxiv.org/pdf/2401.16765v1.pdf), cication: [**-1**](None)

	 *Jie Li, Yi Liu, Chongyang Liu, Ling Shi, Xiaoning Ren, Yaowen Zheng, Yang Liu, Yinxing Xue*
- **Weak-to-Strong Jailbreaking on Large Language Models**, `arXiv, 2401.17256`, [arxiv](http://arxiv.org/abs/2401.17256v1), [pdf](http://arxiv.org/pdf/2401.17256v1.pdf), cication: [**-1**](None)

	 *Xuandong Zhao, Xianjun Yang, Tianyu Pang, Chao Du, Lei Li, Yu-Xiang Wang, William Yang Wang* · ([weak-to-strong](https://github.com/XuandongZhao/weak-to-strong) - XuandongZhao) ![Star](https://img.shields.io/github/stars/XuandongZhao/weak-to-strong.svg?style=social&label=Star)
- **Red Teaming Visual Language Models**, `arXiv, 2401.12915`, [arxiv](http://arxiv.org/abs/2401.12915v1), [pdf](http://arxiv.org/pdf/2401.12915v1.pdf), cication: [**-1**](None)

	 *Mukai Li, Lei Li, Yuwei Yin, Masood Ahmed, Zhenguang Liu, Qi Liu*
- **AttackEval: How to Evaluate the Effectiveness of Jailbreak Attacking on
  Large Language Models**, `arXiv, 2401.09002`, [arxiv](http://arxiv.org/abs/2401.09002v1), [pdf](http://arxiv.org/pdf/2401.09002v1.pdf), cication: [**-1**](None)

	 *Dong shu, Mingyu Jin, Suiyuan Zhu, Beichen Wang, Zihao Zhou, Chong Zhang, Yongfeng Zhang*
- **Open the Pandora's Box of LLMs: Jailbreaking LLMs through Representation
  Engineering**, `arXiv, 2401.06824`, [arxiv](http://arxiv.org/abs/2401.06824v1), [pdf](http://arxiv.org/pdf/2401.06824v1.pdf), cication: [**-1**](None)

	 *Tianlong Li, Xiaoqing Zheng, Xuanjing Huang*
- **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to
  Challenge AI Safety by Humanizing LLMs**, `arXiv, 2401.06373`, [arxiv](http://arxiv.org/abs/2401.06373v1), [pdf](http://arxiv.org/pdf/2401.06373v1.pdf), cication: [**-1**](None)

	 *Yi Zeng, Hongpeng Lin, Jingwen Zhang, Diyi Yang, Ruoxi Jia, Weiyan Shi* · ([chats-lab.github](https://chats-lab.github.io/persuasive_jailbreaker/)) · ([persuasive_jailbreaker](https://github.com/CHATS-lab/persuasive_jailbreaker) - CHATS-lab) ![Star](https://img.shields.io/github/stars/CHATS-lab/persuasive_jailbreaker.svg?style=social&label=Star)
- **Sleeper Agents: Training Deceptive LLMs that Persist Through Safety
  Training**, `arXiv, 2401.05566`, [arxiv](http://arxiv.org/abs/2401.05566v1), [pdf](http://arxiv.org/pdf/2401.05566v1.pdf), cication: [**-1**](None)

	 *Evan Hubinger, Carson Denison, Jesse Mu, Mike Lambert, Meg Tong, Monte MacDiarmid, Tamera Lanham, Daniel M. Ziegler, Tim Maxwell, Newton Cheng*

	 · ([qbitai](https://www.qbitai.com/2024/01/113745.html))
- **Exploiting Novel GPT-4 APIs**, `arXiv, 2312.14302`, [arxiv](http://arxiv.org/abs/2312.14302v1), [pdf](http://arxiv.org/pdf/2312.14302v1.pdf), cication: [**-1**](None)

	 *Kellin Pelrine, Mohammad Taufeeque, Michał Zając, Euan McLean, Adam Gleave*
- [**adversarial-random-search-gpt4**](https://github.com/max-andr/adversarial-random-search-gpt4) - max-andr ![Star](https://img.shields.io/github/stars/max-andr/adversarial-random-search-gpt4.svg?style=social&label=Star)

	 *Adversarial Attacks on GPT-4 via Simple Random Search [Dec 2023]* · ([andriushchenko](https://www.andriushchenko.me/gpt4adv.pdf))
- **Control Risk for Potential Misuse of Artificial Intelligence in Science**, `arXiv, 2312.06632`, [arxiv](http://arxiv.org/abs/2312.06632v1), [pdf](http://arxiv.org/pdf/2312.06632v1.pdf), cication: [**-1**](None)

	 *Jiyan He, Weitao Feng, Yaosen Min, Jingwei Yi, Kunsheng Tang, Shuai Li, Jie Zhang, Kejiang Chen, Wenbo Zhou, Xing Xie* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652419855&idx=4&sn=21f7f3da5aedff2af360057d555eb29f))
- **Llama Guard: LLM-based Input-Output Safeguard for Human-AI Conversations**, `arXiv, 2312.06674`, [arxiv](http://arxiv.org/abs/2312.06674v1), [pdf](http://arxiv.org/pdf/2312.06674v1.pdf), cication: [**-1**](None)

	 *Hakan Inan, Kartikeya Upasani, Jianfeng Chi, Rashi Rungta, Krithika Iyer, Yuning Mao, Michael Tontchev, Qing Hu, Brian Fuller, Davide Testuggine*

	 · ([ai.meta](https://ai.meta.com/research/publications/llama-guard-llm-based-input-output-safeguard-for-human-ai-conversations/))
	 · ([pdf](https://scontent-xsp1-3.xx.fbcdn.net/v/t39.2365-6/408725049_3688557441468029_8103913771964668529_n.pdf?_nc_cat=100&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=_gWcFD1K96gAX_s7udO&_nc_ht=scontent-xsp1-3.xx&oh=00_AfAihkcrUuum2SXpzSJ3bpLugpBbzNsVTkOoV7TcSeer2w&oe=65773519))
- **Scalable and Transferable Black-Box Jailbreaks for Language Models via
  Persona Modulation**, `arXiv, 2311.03348`, [arxiv](http://arxiv.org/abs/2311.03348v2), [pdf](http://arxiv.org/pdf/2311.03348v2.pdf), cication: [**-1**](None)

	 *Rusheb Shah, Quentin Feuillade--Montixi, Soroush Pour, Arush Tagade, Stephen Casper, Javier Rando*
- **Scalable Extraction of Training Data from (Production) Language Models**, `arXiv, 2311.17035`, [arxiv](http://arxiv.org/abs/2311.17035v1), [pdf](http://arxiv.org/pdf/2311.17035v1.pdf), cication: [**-1**](None)

	 *Milad Nasr, Nicholas Carlini, Jonathan Hayase, Matthew Jagielski, A. Feder Cooper, Daphne Ippolito, Christopher A. Choquette-Choo, Eric Wallace, Florian Tramèr, Katherine Lee* · ([qbitai](https://www.qbitai.com/2023/11/102130.html))
- **Scalable AI Safety via Doubly-Efficient Debate**, `arXiv, 2311.14125`, [arxiv](http://arxiv.org/abs/2311.14125v1), [pdf](http://arxiv.org/pdf/2311.14125v1.pdf), cication: [**-1**](None)

	 *Jonah Brown-Cohen, Geoffrey Irving, Georgios Piliouras* · ([debate](https://github.com/google-deepmind/debate) - google-deepmind) ![Star](https://img.shields.io/github/stars/google-deepmind/debate.svg?style=social&label=Star)
- **DeepInception: Hypnotize Large Language Model to Be Jailbreaker**, `arXiv, 2311.03191`, [arxiv](http://arxiv.org/abs/2311.03191v1), [pdf](http://arxiv.org/pdf/2311.03191v1.pdf), cication: [**-1**](None)

	 *Xuan Li, Zhanke Zhou, Jianing Zhu, Jiangchao Yao, Tongliang Liu, Bo Han* · ([DeepInception](https://github.com/tmlr-group/DeepInception) - tmlr-group) ![Star](https://img.shields.io/github/stars/tmlr-group/DeepInception.svg?style=social&label=Star) · ([deepinception.github](https://deepinception.github.io/))
- **Removing RLHF Protections in GPT-4 via Fine-Tuning**, `arXiv, 2311.05553`, [arxiv](http://arxiv.org/abs/2311.05553v2), [pdf](http://arxiv.org/pdf/2311.05553v2.pdf), cication: [**-1**](None)

	 *Qiusi Zhan, Richard Fang, Rohan Bindu, Akul Gupta, Tatsunori Hashimoto, Daniel Kang* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=Mzg4OTEwNjMzMA==&mid=2247534723&idx=3&sn=5d812e7f65334a9dbbdaf052c21a58ce))
- **Frontier Language Models are not Robust to Adversarial Arithmetic, or
  "What do I need to say so you agree 2+2=5?**, `arXiv, 2311.07587`, [arxiv](http://arxiv.org/abs/2311.07587v1), [pdf](http://arxiv.org/pdf/2311.07587v1.pdf), cication: [**-1**](None)

	 *C. Daniel Freeman, Laura Culp, Aaron Parisi, Maxwell L Bileschi, Gamaleldin F Elsayed, Alex Rizkowsky, Isabelle Simpson, Alex Alemi, Azade Nova, Ben Adlam*
- **Unveiling Safety Vulnerabilities of Large Language Models**, `arXiv, 2311.04124`, [arxiv](http://arxiv.org/abs/2311.04124v1), [pdf](http://arxiv.org/pdf/2311.04124v1.pdf), cication: [**-1**](None)

	 *George Kour, Marcel Zalmanovici, Naama Zwerdling, Esther Goldbraich, Ora Nova Fandina, Ateret Anaby-Tavor, Orna Raz, Eitan Farchi*
- **Managing AI Risks in an Era of Rapid Progress**, `arXiv, 2310.17688`, [arxiv](http://arxiv.org/abs/2310.17688v1), [pdf](http://arxiv.org/pdf/2310.17688v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=8498230073239105680&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yoshua Bengio, Geoffrey Hinton, Andrew Yao, Dawn Song, Pieter Abbeel, Yuval Noah Harari, Ya-Qin Zhang, Lan Xue, Shai Shalev-Shwartz, Gillian Hadfield* · ([managing-ai-risks](https://managing-ai-risks.com/))
- **Jailbreaking Black Box Large Language Models in Twenty Queries**, `arXiv, 2310.08419`, [arxiv](http://arxiv.org/abs/2310.08419v2), [pdf](http://arxiv.org/pdf/2310.08419v2.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=1618697255803227028&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Patrick Chao, Alexander Robey, Edgar Dobriban, Hamed Hassani, George J. Pappas, Eric Wong* · ([qbitai](https://www.qbitai.com/2023/11/95723.html))
- **How Robust is Google's Bard to Adversarial Image Attacks?**, `arXiv, 2309.11751`, [arxiv](http://arxiv.org/abs/2309.11751v2), [pdf](http://arxiv.org/pdf/2309.11751v2.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=10841564815936420494&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Yinpeng Dong, Huanran Chen, Jiawei Chen, Zhengwei Fang, Xiao Yang, Yichi Zhang, Yu Tian, Hang Su, Jun Zhu* · ([jiqizhixin](https://www.jiqizhixin.com/articles/2023-10-17-5))
- **Fine-tuning Aligned Language Models Compromises Safety, Even When Users
  Do Not Intend To!**, `arXiv, 2310.03693`, [arxiv](http://arxiv.org/abs/2310.03693v1), [pdf](http://arxiv.org/pdf/2310.03693v1.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=14332933435628840179&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xiangyu Qi, Yi Zeng, Tinghao Xie, Pin-Yu Chen, Ruoxi Jia, Prateek Mittal, Peter Henderson* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652389679&idx=4&sn=a8860988614a66fab78392cbdbbd65fc&poc_token=HKlELGWjp2JYi7j0UAJ9dNwBEC2cxSIKZST7h0YT))
- **GPTFUZZER: Red Teaming Large Language Models with Auto-Generated
  Jailbreak Prompts**, `arXiv, 2309.10253`, [arxiv](http://arxiv.org/abs/2309.10253v2), [pdf](http://arxiv.org/pdf/2309.10253v2.pdf), cication: [**5**](https://scholar.google.com/scholar?cites=734711173091882842&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Jiahao Yu, Xingwei Lin, Zheng Yu, Xinyu Xing* · ([gptfuzz](https://github.com/sherdencooper/gptfuzz) - sherdencooper) ![Star](https://img.shields.io/github/stars/sherdencooper/gptfuzz.svg?style=social&label=Star)
- **"Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak
  Prompts on Large Language Models**, `arXiv, 2308.03825`, [arxiv](http://arxiv.org/abs/2308.03825v1), [pdf](http://arxiv.org/pdf/2308.03825v1.pdf), cication: [**25**](https://scholar.google.com/scholar?cites=2730450320382131594&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xinyue Shen, Zeyuan Chen, Michael Backes, Yun Shen, Yang Zhang*
- **MasterKey: Automated Jailbreak Across Multiple Large Language Model
  Chatbots**, `arXiv, 2307.08715`, [arxiv](http://arxiv.org/abs/2307.08715v2), [pdf](http://arxiv.org/pdf/2307.08715v2.pdf), cication: [**13**](https://scholar.google.com/scholar?cites=3831799754403709253&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Gelei Deng, Yi Liu, Yuekang Li, Kailong Wang, Ying Zhang, Zefeng Li, Haoyu Wang, Tianwei Zhang, Yang Liu* · ([qbitai](https://www.qbitai.com/2023/11/97487.html))
- **Universal and Transferable Adversarial Attacks on Aligned Language
  Models**, `arXiv, 2307.15043`, [arxiv](http://arxiv.org/abs/2307.15043v1), [pdf](http://arxiv.org/pdf/2307.15043v1.pdf), cication: [**58**](https://scholar.google.com/scholar?cites=18196466655097322708&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Andy Zou, Zifan Wang, J. Zico Kolter, Matt Fredrikson* · ([llm-attacks](https://github.com/llm-attacks/llm-attacks) - llm-attacks) ![Star](https://img.shields.io/github/stars/llm-attacks/llm-attacks.svg?style=social&label=Star) · ([qbitai](https://www.qbitai.com/2023/07/72014.html))
- **PUMA: Secure Inference of LLaMA-7B in Five Minutes**, `arXiv, 2307.12533`, [arxiv](http://arxiv.org/abs/2307.12533v3), [pdf](http://arxiv.org/pdf/2307.12533v3.pdf), cication: [**3**](https://scholar.google.com/scholar?cites=15180019305746166242&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Ye Dong, Wen-jie Lu, Yancheng Zheng, Haoqi Wu, Derun Zhao, Jin Tan, Zhicong Huang, Cheng Hong, Tao Wei, Wenguang Chen*
- **International Institutions for Advanced AI**, `arXiv, 2307.04699`, [arxiv](http://arxiv.org/abs/2307.04699v2), [pdf](http://arxiv.org/pdf/2307.04699v2.pdf), cication: [**9**](https://scholar.google.com/scholar?cites=1522776054133119216&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Lewis Ho, Joslyn Barnhart, Robert Trager, Yoshua Bengio, Miles Brundage, Allison Carnegie, Rumman Chowdhury, Allan Dafoe, Gillian Hadfield, Margaret Levi*
- **"Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak
  Prompts on Large Language Models**, `arXiv, 2308.03825`, [arxiv](http://arxiv.org/abs/2308.03825v2), [pdf](http://arxiv.org/pdf/2308.03825v2.pdf), cication: [**162**](https://scholar.google.com/scholar?cites=2730450320382131594&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Xinyue Shen, Zeyuan Chen, Michael Backes, Yun Shen, Yang Zhang* · ([jailbreak_llms](https://github.com/verazuo/jailbreak_llms?tab=readme-ov-file) - verazuo) ![Star](https://img.shields.io/github/stars/verazuo/jailbreak_llms.svg?style=social&label=Star)
- **An Overview of Catastrophic AI Risks**, `arXiv, 2306.12001`, [arxiv](http://arxiv.org/abs/2306.12001v6), [pdf](http://arxiv.org/pdf/2306.12001v6.pdf), cication: [**20**](https://scholar.google.com/scholar?cites=13657604724019544721&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Dan Hendrycks, Mantas Mazeika, Thomas Woodside* · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652349067&idx=5&sn=8fabac5f652ec41a0dfe86a078def978))
- **Jailbroken: How Does LLM Safety Training Fail?**, `arXiv, 2307.02483`, [arxiv](http://arxiv.org/abs/2307.02483v1), [pdf](http://arxiv.org/pdf/2307.02483v1.pdf), cication: [**54**](https://scholar.google.com/scholar?cites=14029412962367612376&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Alexander Wei, Nika Haghtalab, Jacob Steinhardt*
- **PromptBench: Towards Evaluating the Robustness of Large Language Models
  on Adversarial Prompts**, `arXiv, 2306.04528`, [arxiv](http://arxiv.org/abs/2306.04528v4), [pdf](http://arxiv.org/pdf/2306.04528v4.pdf), cication: [**32**](https://scholar.google.com/scholar?cites=6727691362756502405&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Kaijie Zhu, Jindong Wang, Jiaheng Zhou, Zichen Wang, Hao Chen, Yidong Wang, Linyi Yang, Wei Ye, Yue Zhang, Neil Zhenqiang Gong*
## Projects
- [**redteam-arena**](https://github.com/redteaming-arena/redteam-arena) - redteaming-arena ![Star](https://img.shields.io/github/stars/redteaming-arena/redteam-arena.svg?style=social&label=Star)
- [**CJA_Comprehensive_Jailbreak_Assessment**](https://github.com/Junjie-Chu/CJA_Comprehensive_Jailbreak_Assessment) - Junjie-Chu ![Star](https://img.shields.io/github/stars/Junjie-Chu/CJA_Comprehensive_Jailbreak_Assessment.svg?style=social&label=Star)

	 *This is the public code repository of paper 'Comprehensive Assessment of Jailbreak Attacks Against LLMs'*
- [**Llama-Guard-3-8B**](https://huggingface.co/meta-llama/Llama-Guard-3-8B) - meta-llama 🤗
- [**Prompt-Guard-86M**](https://huggingface.co/meta-llama/Prompt-Guard-86M) - meta-llama 🤗
- [**jailbreak_llms**](https://github.com/verazuo/jailbreak_llms?tab=readme-ov-file) - verazuo ![Star](https://img.shields.io/github/stars/verazuo/jailbreak_llms.svg?style=social&label=Star)

	 *[CCS'24] A dataset consists of 15,140 ChatGPT prompts from Reddit, Discord, websites, and open-source datasets (including 1,405 jailbreak prompts).*
- [**prompt-injection-defenses**](https://github.com/tldrsec/prompt-injection-defenses) - tldrsec ![Star](https://img.shields.io/github/stars/tldrsec/prompt-injection-defenses.svg?style=social&label=Star)

	 *Every practical and proposed defense against prompt injection.*
- [**PurpleLlama**](https://github.com/meta-llama/PurpleLlama) - meta-llama ![Star](https://img.shields.io/github/stars/meta-llama/PurpleLlama.svg?style=social&label=Star)

	 *Set of tools to assess and improve LLM security.*
- [**ps-fuzz**](https://github.com/prompt-security/ps-fuzz?tab=readme-ov-file) - prompt-security ![Star](https://img.shields.io/github/stars/prompt-security/ps-fuzz.svg?style=social&label=Star)

	 *Make your GenAI Apps Safe & Secure Test & harden your system prompt*
- [**PyRIT**](https://github.com/Azure/PyRIT) - Azure ![Star](https://img.shields.io/github/stars/Azure/PyRIT.svg?style=social&label=Star)

	 *The Python Risk Identification Tool for generative AI (PyRIT) is an open access automation framework to empower security professionals and machine learning engineers to proactively find risks in their generative AI systems.*
- [**ai-exploits**](https://github.com/protectai/ai-exploits) - protectai ![Star](https://img.shields.io/github/stars/protectai/ai-exploits.svg?style=social&label=Star)

	 *A collection of real world AI/ML exploits for responsibly disclosed vulnerabilities*
- [**chatgpt_system_prompt**](https://github.com/LouisShark/chatgpt_system_prompt) - LouisShark ![Star](https://img.shields.io/github/stars/LouisShark/chatgpt_system_prompt.svg?style=social&label=Star)

	 *store all chatgpt's system prompt*
- [**cipherchat**](https://github.com/robustnlp/cipherchat) - robustnlp ![Star](https://img.shields.io/github/stars/robustnlp/cipherchat.svg?style=social&label=Star)

	 *A framework to evaluate the generalization capability of safety alignment for LLMs*

## Other
- [A Primer on LLM Security – Hacking Large Language Models for Beginners](https://kleiber.me/blog/2024/03/17/llm-security-primer/)
- [Making a SOTA Adversarial Attack on LLMs 38x Faster | Haize Labs Blog 🕊️](https://blog.haizelabs.com/posts/acg/)
- [Introducing the Red-Teaming Resistance Leaderboard](https://huggingface.co/blog/leaderboards-on-the-hub-haizelab)
- [fast.ai - AI Safety and the Age of Dislightenment](https://www.fast.ai/posts/2023-11-07-dislightenment.html)
- [PoisonGPT: How We Hid a Lobotomized LLM on Hugging Face to Spread Fake News](https://blog.mithrilsecurity.io/poisongpt-how-we-hid-a-lobotomized-llm-on-hugging-face-to-spread-fake-news/)

	 · ([mp.weixin.qq](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652349939&idx=3&sn=54b2ca4d0ddf092c8883ad3625e13dd8))


- [ChatGPT最近被微软内部禁用！GPTs新bug：数据两句话就能套走 | 量子位](https://www.qbitai.com/2023/11/97309.html)
- [一段话让模型自曝「系统提示词」！ChatGPT、Bing无一幸免 | 量子位](https://www.qbitai.com/2023/10/91673.html)
- [一段乱码，竟让ChatGPT越狱！乱序prompt让LLM火速生成勒索软件，Jim Fan惊了](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652367811&idx=4&sn=5737319e04c9ea80a506854350c438fa)


## Extra reference