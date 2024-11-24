# LLM Eval

- [LLM Eval](#llm-eval) 
  - [Survey](#survey)
  - [LLM Evaluation](#llm-evaluation)
  - [Leaderboard](#leaderboard)
  - [Projects](#projects)
  - [Misc](#misc)


## Survey

- **When Benchmarks are Targets: Revealing the Sensitivity of Large Language 
  Model Leaderboards**, `arXiv, 2402.01781`, [arxiv](http://arxiv.org/abs/2402.01781v2), [pdf](http://arxiv.org/pdf/2402.01781v2.pdf), cication: [**-1**](None) 

	 *Norah Alzahrani, Hisham Abdullah Alyahya, Yazeed Alnumay, ..., M Saiful Bari, Haidar Khan* · ([lm-evaluation-harness](https://github.com/National-Center-for-AI-Saudi-Arabia/lm-evaluation-harness) - National-Center-for-AI-Saudi-Arabia) ![Star](https://img.shields.io/github/stars/National-Center-for-AI-Saudi-Arabia/lm-evaluation-harness.svg?style=social&label=Star)

## LLM Evaluation

- [Enhancing Evaluation Coverage and Validation with Language Models](https://www.youtube.com/watch?v=Gp6Na2mdKDs&list=PLWRU-w8UhT6jNg64UfBB0VtlvI4Upe914&index=7)  :clapper:
- [Emotional Intelligence Benchmark for LLMs](https://eqbench.com/judgemark.html) 
- **Adding Error Bars to Evals: A Statistical Approach to Language Model 
  Evaluations**, `arXiv, 2411.00640`, [arxiv](http://arxiv.org/abs/2411.00640v1), [pdf](http://arxiv.org/pdf/2411.00640v1.pdf), cication: [**-1**](None) 

	 *Evan Miller*

	 · ([anthropic](https://www.anthropic.com/research/statistical-approach-to-model-evals))
- **Chinese SimpleQA: A Chinese Factuality Evaluation for Large Language 
  Models**, `arXiv, 2411.07140`, [arxiv](http://arxiv.org/abs/2411.07140v2), [pdf](http://arxiv.org/pdf/2411.07140v2.pdf), cication: [**-1**](None) 

	 *Yancheng He, Shilong Li, Jiaheng Liu, ..., Wenbo Su, Bo Zheng*
- [Mira: A Decentralized Network for Trustless AI Output Verification](https://mira.network/research/mira-whitepaper.pdf) 

	 · ([mira](https://mira.network/)) · ([huggingface](https://huggingface.co/datasets/Mira-Network/ensemble-validation?row=0))
- **FrontierMath: A Benchmark for Evaluating Advanced Mathematical Reasoning 
  in AI**, `arXiv, 2411.04872`, [arxiv](http://arxiv.org/abs/2411.04872v1), [pdf](http://arxiv.org/pdf/2411.04872v1.pdf), cication: [**-1**](None) 

	 *Elliot Glazer, Ege Erdil, Tamay Besiroglu, ..., Tetiana Grechuk, Shreepranav Varma Enugandla* · ([epochai](https://epochai.org/frontiermath)) · ([𝕏](https://x.com/EpochAIResearch/status/1854993676524831046))
- [SimpleQA that measures the ability for language models to answer short, fact-seeking questions.](https://openai.com/index/introducing-simpleqa/) 

	 · ([cdn.openai](https://cdn.openai.com/papers/simpleqa.pdf)) · ([simple-evals](https://github.com/openai/simple-evals/) - openai) ![Star](https://img.shields.io/github/stars/openai/simple-evals.svg?style=social&label=Star)
- **Are LLMs Better than Reported? Detecting Label Errors and Mitigating 
  Their Effect on Model Performance**, `arXiv, 2410.18889`, [arxiv](http://arxiv.org/abs/2410.18889v1), [pdf](http://arxiv.org/pdf/2410.18889v1.pdf), cication: [**-1**](None)

	 *Omer Nahum, Nitay Calderon, Orgad Keller, ..., Idan Szpektor, Roi Reichart*
- :clapper: [How to Construct Domain Specific LLM Evaluation Systems: Hamel Husain and Emil Sedgh](https://www.youtube.com/watch?v=eLXF0VojuSs) 
- 🌟 [Creating a LLM-as-a-Judge That Drives Business Results](https://hamel.dev/blog/posts/llm-judge/) 
- **LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive 
  Memory**, `arXiv, 2410.10813`, [arxiv](http://arxiv.org/abs/2410.10813v1), [pdf](http://arxiv.org/pdf/2410.10813v1.pdf), cication: [**-1**](None)

	 *Di Wu, Hongwei Wang, Wenhao Yu, ..., Kai-Wei Chang, Dong Yu*
- **CompassJudger-1: All-in-one Judge Model Helps Model Evaluation and 
  Evolution**, `arXiv, 2410.16256`, [arxiv](http://arxiv.org/abs/2410.16256v1), [pdf](http://arxiv.org/pdf/2410.16256v1.pdf), cication: [**-1**](None)

	 *Maosong Cao, Alexander Lam, Haodong Duan, ..., Songyang Zhang, Kai Chen* · ([CompassJudger](https://github.com/open-compass/CompassJudger) - open-compass) ![Star](https://img.shields.io/github/stars/open-compass/CompassJudger.svg?style=social&label=Star)
- **UCFE: A User-Centric Financial Expertise Benchmark for Large Language 
  Models**, `arXiv, 2410.14059`, [arxiv](http://arxiv.org/abs/2410.14059v2), [pdf](http://arxiv.org/pdf/2410.14059v2.pdf), cication: [**-1**](None)

	 *Yuzhe Yang, Yifei Zhang, Yan Hu, ..., Honghai Yu, Benyou Wang*
- **MixEval-X: Any-to-Any Evaluations from Real-World Data Mixtures**, `arXiv, 2410.13754`, [arxiv](http://arxiv.org/abs/2410.13754v2), [pdf](http://arxiv.org/pdf/2410.13754v2.pdf), cication: [**-1**](None) 

	 *Jinjie Ni, Yifan Song, Deepanway Ghosal, ..., Yang You, Michael Shieh*
- **JudgeBench: A Benchmark for Evaluating LLM-based Judges**, `arXiv, 2410.12784`, [arxiv](http://arxiv.org/abs/2410.12784v1), [pdf](http://arxiv.org/pdf/2410.12784v1.pdf), cication: [**-1**](None) 

	 *Sijun Tan, Siyuan Zhuang, Kyle Montgomery, ..., Raluca Ada Popa, Ion Stoica* · ([JudgeBench](https://github.com/ScalerLab/JudgeBench) - ScalerLab) ![Star](https://img.shields.io/github/stars/ScalerLab/JudgeBench.svg?style=social&label=Star)
- **Large Language Model Evaluation via Matrix Nuclear-Norm**, `arXiv, 2410.10672`, [arxiv](http://arxiv.org/abs/2410.10672v1), [pdf](http://arxiv.org/pdf/2410.10672v1.pdf), cication: [**-1**](None) 

	 *Yahan Li, Tingyu Xia, Yi Chang, ..., Yuan Wu* · ([MatrixNuclearNorm](https://github.com/MLGroupJLU/MatrixNuclearNorm) - MLGroupJLU) ![Star](https://img.shields.io/github/stars/MLGroupJLU/MatrixNuclearNorm.svg?style=social&label=Star)

## Leaderboard

- [Judge Arena: Benchmarking LLMs as Evaluators](https://huggingface.co/blog/arena-atla)  🤗 

	 · ([huggingface](https://huggingface.co/spaces/AtlaAI/judge-arena))
- [TIGER-Lab / MMLU-Pro](https://huggingface.co/spaces/TIGER-Lab/MMLU-Pro/tree/main) 🤗 

## Projects

- [**RPBench-Auto**](https://github.com/boson-ai/RPBench-Auto) - boson-ai ![Star](https://img.shields.io/github/stars/boson-ai/RPBench-Auto.svg?style=social&label=Star) 

	 · ([boson](https://boson.ai/rpbench-blog/))
- [**documind**](https://github.com/DocumindHQ/documind) - DocumindHQ ![Star](https://img.shields.io/github/stars/DocumindHQ/documind.svg?style=social&label=Star) 
- 🌟 [**evalchemy**](https://github.com/mlfoundations/evalchemy) - mlfoundations ![Star](https://img.shields.io/github/stars/mlfoundations/evalchemy.svg?style=social&label=Star) 
- [**OLMo-Eval**](https://github.com/allenai/OLMo-Eval) - allenai ![Star](https://img.shields.io/github/stars/allenai/OLMo-Eval.svg?style=social&label=Star) 
- [**olmes**](https://github.com/allenai/olmes) - allenai ![Star](https://img.shields.io/github/stars/allenai/olmes.svg?style=social&label=Star) 
- 🌟 [**simple-evals**](https://github.com/openai/simple-evals) - openai ![Star](https://img.shields.io/github/stars/openai/simple-evals.svg?style=social&label=Star) 

## Misc

- [Crisp and fuzzy tasks](https://aligned.substack.com/p/crisp-and-fuzzy-tasks) 
- [Letting Large Models Debate: The First Multilingual LLM Debate Competition](https://huggingface.co/blog/debate)  🤗
- [Say What You Mean: A Response to 'Let Me Speak Freely'](https://blog.dottxt.co/say-what-you-mean.html) 
- [Chatbot Arena Categories](https://lmarena.github.io/blog/2024/arena-category/) 

	 · ([x](https://x.com/lmarena_ai/status/1852400728935150017))