---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
hide_specific_content: true  # 添加这个控制变量
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am Cao Yixin, a professor at Shanghai Innovation Institute, as well as Institute of Trustworthy Embodied AI, Fudan University. I obtained Ph.D. from KEG at Tsinghua University, advised by Prof. Li Juanzi. I have held positions as a research fellow, research assistant professor, and assistant professor at the National University of Singapore, Nanyang Technological University, and Singapore Management University. I am a recipient of the National Youth Talent Program and the Shanghai Leading Talent Program. My research areas include natural language processing, knowledge engineering, and multimodal information processing. I have published over 60 papers at international renowned conferences and journals, with more than 11,000 citations on Google Scholar. My research achievements have been awarded the Best Paper/Nomination at two international conferences. I have received Lee Kong Chian Fellowship, Google South Asia & Southeast Asia Awards, and the AI2000 Most Influential Scholar honorable mention. I also serve as the demonstration program chair or area chair for multiple international conferences, and as a reviewer for international journals.


# 🔥 News
- *2026.05*: &nbsp;🎉🎉 Four papers are accepted by ICML2026!
- *2026.04*: &nbsp;🎉🎉 Three/Two papers are accepted by ACL2026/Findings!
- *2026.01*: &nbsp;🎉🎉 Four papers are accepted by ICLR2026!
- *2025.09*: &nbsp;🎉🎉 Two papers are accepted by NeurIPS2025!
- *2025.05*: &nbsp;🎉🎉 Four/four papers are accepted by ACL2025/Findings!
- *2025.01*: &nbsp;🎉🎉 Two papers are accepted by ICLR2025!
- *2024.12*: &nbsp;🎉🎉 Two papers are accepted by AAAI2025!
- *2024.09*: &nbsp;🎉🎉 One/Three papers are accepted by NeurIPs spotlight/poster, respectively!
- *2024.09*: &nbsp;🎉🎉 Two/Four papers are accepted by EMNLP main conference/Findings, respectively!
- *2024.05*: &nbsp;🎉🎉 Four/Five papers are accepted by ACL main conference/Findings, respectively!
- *2023.10*: &nbsp;🎉🎉 Two/Four papers are accepted by EMNLP main conference/Findings, respectively!

# 📝 Publications 

## ArXiv 
- (My recent talk about these two papers is attached below!)
- Toward **Generalizable Evaluation** in the LLM Era: A Survey Beyond Benchmarks. Yixin Cao, Shibo Hong, Xinze Li, Jiahao Ying, Yubo Ma, Haiyuan Liang, Yantao Liu, Zijun Yao, Xiaozhi Wang, et. al. [Paper](https://arxiv.org/abs/2504.18838). 
- **Model Utility Law**: Evaluating LLMs beyond Performance through Mechanism Interpretable Metric. Yixin Cao, Jiahao Ying, Yaoning Wang, Xipeng Qiu, Xuanjing Huang, Yugang Jiang. [Paper](https://arxiv.org/abs/2504.07440).


{% unless page.hide_specific_content %}
- Long or short CoT? Investigating Instance-level Switch of Large Reasoning Models. Ruiqi Zhang, Changyi Xiao, Yixin Cao.
- EffiEval: Efficient and Generalizable Model Evaluation via Capability Coverage Maximization. Yaoning Wang, Jiahao Ying, Yixin Cao, Yubo Ma, Yugang Jiang.
- BNPO: Beta Normalization Policy Optimization. Changyi Xiao, Mengdi Zhang, Yixin Cao.
- All by Large Language Model Itself. Changyi Xiao, Yixin Cao.
- Beyond Benchmarks: Understanding Mixture-of-Experts Models through Internal Mechanisms. Jiahao Ying, Mingbao Lin, Qianru Sun, Yixin Cao.
- Diagnosing and Remedying Knowledge Deficiencies in LLMs via Label-free Curricular Meaningful Learning. Kai Xiong, Xiao Ding, Yixin Cao, Li Du, Jiahao Ying, Yang Zhao, Bing Qin, Ting Liu.
- Smarter Not Harder: Generative Process Evaluation with Intrinsic-Signal Driving and Ability‑Adaptive Reward Shaping. Tao He, Rongchuan Mu, Lizi Liao, Yixin Cao, Yang Li, Yijia Luo, Weixun Wang, Ming Liu, Bing Qin.
- Less Data Less Tokens: Multilingual Unification Learning for Efficient Test-Time Reasoning in LLMs. chenkang, Mengdi Zhang, Zhuoka Feng, Yixin Cao.
- EMemBench: Interactive Benchmarking of Episodic Memory for VLM Agents. Xinze Li, Ziyue Zhu, Siyuan Liu, Yubo Ma, Yuhang Zang, Yixin Cao, Aixin Sun.
- What Do LLM Agents Know About Their World? Task2Quiz: A Paradigm for Studying Environment Understanding. Siyuan Liu, Hongbang Yuan, Xinze Li, Ziyue Zhu, Yixin Cao, Yu-Gang Jiang.
- ARM: Role-Conditioned Neuron Transplantation for Training-Free Generalist LLM Agent Merging. Zhuoka Feng, chenkang, SIHAN ZHAO, Kai Xiong, Yaoning Wang, Yu Minshen, Junjie Nian, Changyi Xiao, Yixin Cao, Yu-Gang Jiang.
- EffiEval: Efficient Model Evaluation via Capability Coverage Maximization. Yaoning Wang, Jiahao Ying, Yixin Cao, Yubo Ma, Yu-Gang Jiang.
- CoDiQ: Test-Time Scaling for Controllable Difficult Question Generation. Zhongyuan Peng, Caijun Xu, Changyi Xiao, Shibo Hong, Ge Zhang, Wenhao Huang, Yixin Cao.
- Reinforcement Learning with Conditional Expectation Reward. Changyi Xiao, Caijun Xu, Yixin Cao.
- NEX: Neuron Explore–Exploit Scoring for Label-Free Chain-of-Thought Selection and Model Ranking. chenkang, Zhuoka Feng, SIHAN ZHAO, Kai Xiong, Junjie Nian, Yaoning Wang, Changyi Xiao, Yixin Cao

{% endunless %}

## 2026
- Do LLMs Signal When They’re Right? Evidence from Neuron Agreement. chenkang, Yaoning Wang, Kai Xiong, Zhuoka Feng, Wenhe Sun, Haotian Chen, **Yixin Cao**. ICML2026 (Spotlight).
- DLEBench: Evaluating Small-scale Object Editing Ability for Instruction-based Image Editing Model. Shibo Hong, Boxian Ai, Jun Kuang, Wei Wang, FengJiao Chen, Zhongyuan Peng, Chenhao Huang, **Yixin Cao**. ICML2026.
- GAM-RAG: Gain-Adaptive Memory for Evolving Retrieval in Retrieval-Augmented Generation. Yifan Wang, Mingxuan Jiang, Zhihao Sun, **Yixin Cao**, Yicun Liu, Keyang Chen, Guangnan Ye, Hongfeng Chai. ICML2026.
- Beyond Literal Translation: Evaluating Cultural Effectiveness in Social Media UGC. Linjuan Wu, Ruiqi Zhang, Xinze Lyu, Ye Guo, Daoxin Zhang, Zhe Xu, Yao Hu, **Yixin Cao**, Yongliang Shen, Weiming Lu. ICML2026.
- Rethinking the Role of Entropy in Optimizing Tool-Use Behaviors for Large Language Model Agents. Zeping Li, Hongru WANG, Zhao Yiwen, Guanhua Chen, Yixia Li, Keyang Chen, **Yixin Cao**, Guangnan Ye, Hongfeng Chai, Mengdi Wang, Zhenfei Yin. ACL2026.
- PRISM: Probabilistic Reward Model with Inherent Structural Modeling. Yuhang Zhou, **Yixin Cao**, Yuchen Ni, Shihan Dou, Xutian Chen, Ge Zhang, Xiang Liu, Guangnan Ye. ACL2026.
- CriticLean: Critic-Guided Reinforcement Learning for Mathematical Formalization. Zhongyuan Peng, Yifan Yao, Kaijing Ma, et al. ACL2026.
- Thinking Traps in Long Chain-of-Thought: A Measurable Study and Trap-Aware Adaptive Restart. chenkang, Fan Yu, Junjie Nian, SIHAN ZHAO, Zhuoka Feng, Zijun Yao, wang heng, Yu Minshen, **Yixin Cao**. ACL2026 Findings.
- SCALER: Synthetic Scalable Adaptive Learning Environment for Reasoning. Caijun Xu, Changyi Xiao, Zhongyuan Peng, Xinrun Wang, **Yixin Cao**. ACL2026 Findings.
- FRABench and UFEval: Unified Fine-grained Evaluation with Task and Aspect Generalization. Shibo Hong, Jiahao Ying, Haiyuan Liang, Mengdi Zhang, Jun Kuang, Jiazheng Zhang, **Yixin Cao**. ICLR2026.
- Teach2Eval: An Interaction-Driven LLMs Evaluation Method via Teaching Effectiveness. Yuhang Zhou, Xutian Chen, **Yixin Cao**, Yuchen Ni, Yu He, Siyu Tian, Xiang Liu, Yunwen Chen, Guangnan Ye, Xipeng Qiu, Hongfeng Chai. ICLR2026.
- Smarter Not Harder: Generative Process Evaluation with Intrinsic-Signal Driving and Ability‑Adaptive Reward Shaping. Tao He, Rongchuan Mu, Lizi Liao, **Yixin Cao**, Yang Li, Yijia Luo, Weixun Wang, Ming Liu, Bing Qin. ICLR2026.
- Diagnosing and Remedying Knowledge Deficiencies in LLMs via Label-free Curricular Meaningful Learning. Kai Xiong, Xiao Ding, **Yixin Cao**, Li Du, Jiahao Ying, Yang Zhao, Bing Qin, Ting Liu. ICLR2026.

## 2025
- Subgraph-Centric Multi-Agent Reinforcement Learning for Multi-hop Knowledge Graph Reasoning. Tao He, Zerui Chen, Lizi Liao, **Yixin Cao**,Yuanxing Liu,Wei Tang,Xun Mao,Kai Lv,Ming Liu,Bing Qin. TKDE2025.
- MultiHGPT: Multi-Task Heterogeneous Graph Prompt Tuning. Yifan Wang; Yixin Cao; Zeping Li; Bowen Dong; Hongfeng Chai. IPM2025.
- ForgerySleuth: Empowering Multimodal Large Language Models for Image Manipulation Detection. Zhihao Sun, Haoran Jiang, Haoran Chen, **Yixin Cao**, Xipeng Qiu, Zuxuan Wu, Yu-Gang Jiang. NeurIPS2025.
- Learning 3D Anisotropic Noise Distributions Improves Molecular Force Fields. Xixian Liu, Rui Jiao, Zhiyuan Liu, Yurou Liu, Yang Liu, Ziheng Lu, Wenbing Huang, Yang Zhang, **Yixin Cao**. NeurIPS2025.
- EvoWiki: Evaluating LLMs on Evolving Knowledge. Wei Tang, **Yixin Cao**, Yang Deng, Jiahao Ying, Bo Wang, Yizhe Yang, Yuyue Zhao, Qi Zhang, Xuanjing Huang, Yu-Gang Jiang, Yong Liao. ACL2025.
- Com^2: A Causal-Guided Benchmark for Exploring Complex Commonsense Reasoning in Large Language Models. Kai Xiong, Xiao Ding, **Yixin Cao**, Yuxiong Yan, Li Du, Yufei Zhang, Jinglong Gao, Jiaqian Liu, Bing Qin, Ting Liu. ACL2025.
- Disentangling Language Medium and Culture Context for Evaluating Multilingual Large Language Models. Jiahao Ying, Wei Tang, Yiran Zhao, **Yixin Cao**, Yu Rong, Wenxuan Zhang. ACL2025.
- LogicPro: Improving Complex Logical Reasoning via Program-Guided Learning. Jin Jiang, Yuchen Yan, Yang Liu, Jianing Wang, Shuai Peng, Xunliang Cai, **Yixin Cao**, Mengdi Zhang, Liangcai Gao. ACL2025.
- XFinBench: Benchmarking LLMs in Complex Financial Problem Solving and Reasoning. Zhihan Zhang, Yixin Cao, Lizi Liao. ACL2025 Findings.
- Breaking the Reasoning Barrier A Survey on LLM Complex Reasoning through the Lens of Self-Evolution. Tao He, Hao Li, Jingchang Chen, Runxuan Liu, **Yixin Cao**, Lizi Liao, Zihao Zheng, Zheng Chu, Jiafeng Liang, Ming Liu, Bing Qin. ACL2025 Findings.
- Towards Storage-Efficient Visual Document Retrieval: An Empirical Study on Reducing Patch-Level Embeddings. Yubo Ma, Jinsong Li, Yuhang Zang, Xiaobao Wu, Xiaoyi Dong, Pan Zhang, Yuhang Cao, Haodong Duan, Jiaqi Wang, Yixin Cao, Aixin Sun. ACL2025 Findings.
- Are LLMs Rational Investors? A Study on the Financial Bias in LLMs. Yuhang Zhou, Yuchen Ni, Zhiheng Xi, Zhangyue Yin, Yu He, Gan Yunhui, Xiang Liu, Zhang Jian, Sen Liu, Xipeng Qiu, Yixin Cao, Guangnan Ye, Hongfeng Chai. ACL2025 Findings.
- RM-Bench: Benchmarking Reward Models of Language Models with Subtlety and Style. Yantao Liu, Zijun Yao, Rui Min, **Yixin Cao**, Lei Hou, Juanzi Li. ICLR2025. (Oral)
- Precise Localization of Memories: A Fine-grained Neuron-level Knowledge Editing Technique for LLMs. Haowen Pan, Xiaozhi Wang, **Yixin Cao**, Zenglin Shi, Xun Yang*, Juanzi Li, Meng Wang. ICLR2025. 
- Simulation-Free Hierarchical Latent Policy Planning for Proactive Dialogues. Tao He, Lizi Liao, **Yixin Cao**, Yuanxing Liu, Yiheng Sun, Zerui Chen, Ming Liu, Bing Qin. AAAI2025.
- S^3cMath: Spontaneous Step-level Self-correction Makes Large Language Models Better Mathematical Reasoners. Yuchen Yan, Jin Jiang, Yang Liu, **Yixin Cao**, Xin Xu, Mengdi Zhang, Xunliang Cai, Jian Shao. AAAI2025.

## 2024
- Automating Dataset Updates Towards Reliable and Timely Evaluation of Large Language Models. Jiahao Ying, **Yixin Cao**, Bo Wang, Wei Tang, Yizhe Yang, Shuicheng Yan. NeurIPS2024.
- MMLONGBENCH-DOC: Benchmarking Long-context Document Understanding with Visualizations. Yubo Ma, Yuhang Zang, Liangyu Chen, Meiqi Chen, Yizhu Jiao, Xinze Li, Xinyuan Lu, Ziyu Liu, Yan Ma, Xiaoyi Dong, Pan Zhang, Liangming Pan, Yu-Gang Jiang, Jiaqi Wang, **Yixin Cao**, Aixin Sun. NeurIPS2024 (spotlight).
- Meaningful Learning: Advancing Abstract Reasoning in Large Language Models via Generic Fact Guidance. Kai Xiong, Xiao Ding, Ting Liu, Bing Qin, Dongliang Xu, Qing Yang, Hongtao Liu, **Yixin Cao**. NeurIPS2024.
- Knowledge Graph Completion by Intermediate Variables Regularization. Changyi Xiao, **Yixin Cao**. NeurIPS2024.
- MORE: Evaluating and Quantifying Unimodal Biases in Multimodal Large Language Models through a Causal Lens. Meiqi Chen, **Yixin Cao**, Yan Zhang, Chaochao Lu. EMNLP Findings 2024. 
- LLMs-as-Instructors: Learning from Errors Toward Automating Model Improvement. Jiahao Ying, Mingbao Lin, **Yixin Cao**, Wei Tang, Bo Wang, Qianru Sun, Xuanjing Huang, Shuicheng Yan. EMNLP Findings 2024.
- Navigating the Nuances: A Fine-grained Evaluation of Vision-Language Navigation. Zehao Wang, Minye Wu, **Yixin Cao**, Yubo Ma, Meiqi Chen, Tinne Tuytelaars. EMNLP Findings 2024.
- QRMeM: Unleash the Length Limitation through Question then Reflection Memory Mechanism. Bo Wang, Heyan Huang, **Yixin Cao**, Jiahao Ying, Wei Tang, Chong Feng. EMNLP Findings 2024.
- SciAgent: Tool-augmented Language Models for Scientific Reasoning. Yubo Ma, Zhibin Gou, Junheng Hao, Ruochen Xu, Shuohang Wang, Liangming Pan, Yujiu Yang, **Yixin Cao**, Aixin Sun, Hany Awadalla, Weizhu Chen. EMNLP 2024.
- LLMs Assist NLP Researchers: Critique Paper (Meta-)Reviewing. EMNLP 2024.
- Analyzing Temporal Complex Events with Large Language Models? A Benchmark towards Temporal, Long Context Understanding. Zhihan Zhang, **Yixin Cao**, Chenchen Ye, Yunshan Ma, Lizi Liao, Tat-Seng Chua. ACL 2024.
- Intuitive or Dependent? Investigating LLMs' Behavior Style to Conflicting Prompts. Jiahao Ying, **Yixin Cao**, Kai Xiong, Yidong He, Long Cui, Yongbin Liu. ACL 2024.
- Planning Like Human: A Dual-process Framework for Dialogue Planning. Tao He, Lizi Liao, **Yixin Cao**, Yuanxing Liu, Ming Liu, Zerui Chen, Bing Qin. ACL 2024.
- Improving Large Language Models in Event Relation Logical Prediction. Meiqi Chen, Yubo Ma, Kaitao Song, **Yixin Cao**, Yan Zhang, Dongsheng Li. ACL 2024. (Oral)
- Complex Logical Query Answering by Calibrating Knowledge Graph Completion Models. Changyi Xiao, **Yixin Cao**. ACL Findings 2024.
- A + B: A General Generator-Reader Framework for Optimizing LLMs to Unleash Synergy Potential. Wei Tang, **Yixin Cao**, Jiahao Ying, Bo Wang, Yuyue Zhao, Yong Liao, Pengyuan Zhou. ACL Findings 2024.
- Finding and Editing Multi-Modal Neurons in Pre-Trained Transformers. Haowen Pan, **Yixin Cao**, Xiaozhi Wang, Xun Yang, Meng Wang. ACL Findings 2024.
- Towards Verifiable Generation: A Benchmark for Knowledge-aware Language Model Attribution. Xinze Li, **Yixin Cao**, Liangming Pan, Yubo Ma, Aixin Sun. ACL findings 2024.
- Recognizing Everything from All Modalities at Once: Grounded Multimodal Universal Information Extraction. Meishan Zhang, Hao Fei, Bin Wang, Shengqiong Wu, **Yixin Cao**, Fei Li, Min Zhang. ACL Findings 2024.
- Event-level Knowledge Editing. Hao Peng, Xiaozhi Wang, Chunyang Li, Kaisheng Zeng, Jiangshan Duo, **Yixin Cao**, Lei Hou, Juanzi Li. Arxiv.
- HoGRN: Explainable Sparse Knowledge Graph Completion via High-order Graph Reasoning Network. Weijian Chen, **Yixin Cao**, Fuli Feng, Xiangnan He, Yongdong Zhang. TKDE 2024.
- X-eval: Generalizable multi-aspect text evaluation via augmented instruction tuning with auxiliary evaluation aspects. Minqian Liu, Ying Shen, Zhiyang Xu, **Yixin Cao**, Eunah Cho, Vaibhav Kumar, Reza Ghanadan, Lifu Huang. NAACL 2024.
- Screening through a broad pool: Towards better diversity for lexically constrained text generation. Changsen Yuan, Heyan Huang, **Yixin Cao**, Qianwen Cao. Information Processing & Management.
- VEM^2L: an easy but effective framework for fusing text and structure knowledge on sparse knowledge graph completion. Tao He, Ming Liu, **Yixin Cao**, Meng Qu, Zihao Zheng, Bing Qin. Data Mining and Knowledge Discovery.
- Exploring & Exploiting High-Order Graph Structure for Sparse Knowledge Graph Completion. Tao He, Ming Liu, **Yixin Cao**, Zekun Wang, Zihao Zheng, Zheng Chu, Bing Qin. Frontiers of Computer Science

## 2023
- A Comprehensive Evaluation of Large Language Models on Legal Judgment Prediction. Ruihao Shui, **Yixin Cao**, Xiang Wang, Tat-Seng Chua. EMNLP Findings 2023.
- CoVariance-based Causal Debiasing for Entity and Relation Extraction. Lin Ren, Yongbin Liu, **Yixin Cao**, Chunping Ouyang. EMNLP Findings 2023.
- MolCA: Molecular Graph-Language Modeling with Cross-Modal Projector and Uni-Modal Adapter. Zhiyuan Liu, Sihang Li, Yanchen Luo, Hao Fei, **Yixin Cao**, Kenji Kawaguchi, Xiang Wang, Tat-Seng Chua. EMNLP 2023.
- Robust Prompt Optimization for Large Language Models Against Distribution Shifts. Moxin Li, Wenjie Wang, Fuli Feng, **Yixin Cao**, Jizhi Zhang, Tat-Seng Chua. EMNLP 2023.
- Benchmarking Foundation Models with Language-Model-as-an-Examiner. Yushi Bai, Jiahao Ying, **Yixin Cao**, Xin Lv, Yuze He, Xiaozhi Wang, Jifan Yu, Kaisheng Zeng, Yijia Xiao, Haozhe Lyu, Jiayin Zhang, Juanzi Li, Lei Hou. NeurIPs 2023.
- Examining the Inter-Consistency of Large Language Models: An In-depth Analysis via Debate. Kai Xiong, Xiao Ding, **Yixin Cao**, Ting Liu, Bing Qin. EMNLP Findings 2023.
- Large Language Model Is Not a Good Few-shot Information Extractor, but a Good Reranker for Hard Samples! Yubo Ma, **Yixin Cao**, Yong Ching Hong, Aixin Sun. EMNLP 2023 (Findings), [Paper](https://arxiv.org/abs/2303.08559).
- FollowupQG: Towards information-seeking follow-up question generation. Yan Meng, Liangming Pan, **Yixin Cao** and Min-Yen Kan. AACL 2023.
- Constructing Holistic Spatio-Temporal Scene Graph for Video Semantic Role Labeling. Yu Zhao, Hao Fei, **Yixin Cao**, Bobo Li, Meishan Zhang, Jianguo Wei, Min Zhang, Tat-Seng Chua. ACM MM2023.
- Context-aware Event Forecasting via Graph Disentanglement. Yunshan Ma, Chenchen Ye, Zijian Wu, Xiang Wang, **Yixin Cao**, and Tat-Seng Chua. KDD2023.
- Document-level Relation Extraction via Separate Relation Representation and Logical Reasoning. Heyan Huang, Changsen Yuan, Qian Liu, and **Yixin Cao**. TOIS2023.
- Information Screening whilst Exploiting! Multimodal Relation Extraction with Feature Denoising and Multimodal Topic Modeling. Shengqiong Wu, Hao Fei, **Yixin Cao**, Lidong Bing and Tat-Seng Chua. ACL2023. Best Paper nomination.
- Discriminative Reasoning with Sparse Event Representation for Document-level Event-Event Relation Extraction. Changsen Yuan, Heyan Huang, **Yixin Cao** and Yonggang Wen. ACL2023.
- CHEER: Centrality-aware High-order Event Reasoning Network for Document-level Event Causality Identification. Meiqi Chen, **Yixin Cao**, Yan Zhang and Zhiwei Liu. ACL2023.
- Take a Break in the Middle: Investigating Subgoals towards Hierarhical Script Generation. Xinze Li, **Yixin Cao**, Muhao Chen and Aixin Sun. Findings of ACL2023.
- Few-shot Event Detection: An Empirical Study and a Unified View. Yubo Ma, Zehao Wang, **Yixin Cao** and Aixin Sun. ACL2023.
- Knowledge Graph Embedding by Normalizing Flows. Changyi Xiao, Xiangnan He, **Yixin Cao**. AAAI2023
- To be or not to be? an exploration of continuously controllable prompt engineering. Yuhan Sun, Mukai Li, **Yixin Cao**, Kun Wang, Wenxiao Wang, Xingyu Zeng, Rui Zhao. Arxiv.


## 2022
- R2F: A General Retrieval, Reading and Fusion Framework for Document-level Natural Language Inference. Hao Wang, **Yixin Cao**, Yangguang Li, Zhen Huang, Kun Wang, Jing Shao. EMNLP2022
- ERGO: Event Relational Graph Transformer for Document-level Event Causality Identification. Meiqi Chen, **Yixin Cao**, Kunquan Deng, Mukai Li, Kun Wang, Jing Shao, Yan Zhang. COLING2022.
- ICLEA: Interactive Contrastive Learning for Self-supervised Entity Alignment. Kaisheng Zeng, Zhenhao Dong, Lei Hou, **Yixin Cao**, Minghao Hu, Jifan Yu, Xin Lv, Juanzi Li, Ling Feng. CIKM2022.
- TGDM: Target Guided Dynamic Mixup for Cross-Domain Few-Shot Learning. Linhai Zhuo, Yuqian Fu, Jingjing Chen, **Yixin Cao**, Yu-Gang Jiang. MM2022
- DocEE: A Large-Scale and Fine-grained Benchmark for Document-level Event Extraction. Meihan Tong, Bin Xu, Shuai Wang, Meihuan Han, **Yixin Cao**, Jiangqi Zhu, Siyu Chen, Lei Hou, Juanzi Li. NAACL2022.
- What Makes The Story Forward? Inferring Commonsense Explanations as Prompts for Future Event Generation. Lin Li, **Yixin Cao**, Lifu Huang, Shu'ang Li, Lijie Wen. SIGIR2022.
- MMEKG: Multi-modal Event Knowledge Graph towards Universal Representation across Modalities. Yubo Ma†, Zehao Wang†, Mukai Li†, **Yixin Cao**, Meiqi Chen, Xinze Li, Wenqi Sun, Kunquan Deng, Kun Wang, Aixin Sun, Jing Shao. ACL2022 Demo.
- Do Pre-trained Models Benefit Knowledge Graph Completion? A Reliable Evaluation and a Reasonable Approach. Xin Lv, Yankai Lin, **Yixin Cao**, Lei Hou, Juanzi Li, Zhiyuan Liu, Peng Li, Jie Zhou. ACL2022 Finding.
- Prompt for Extraction? PAIE: Prompting Argument Interaction for Event Argument Extraction. Yubo Ma† , Zehao Wang† , **Yixin Cao**, Mukai Li, Meiqi Chen, Kun Wang, Jing Shao. ACL2022.
- Debiasing NLU Models via Causal Intervention and Counterfactual Reasoning. Bing Tian, **Yixin Cao**, Yong Zhang, Chunxiao Xing. AAAI2022.
- Training Free Graph Neural Networks for Graph Matching. Zhiyuan Liu, **Yixin Cao**, Fuli Feng, Xiang Wang, Jie Tang, Kenji Kawaguchi, Tat-Seng Chua. Arxiv.

## 2021
- Missing Data Imputation for Solar Yield Prediction using Temporal Multi-Modal Variational Auto-Encoder. Meng Shen, Huaizheng Zhang, **Yixin Cao**, Fan Yang, Yonggang Wen. MM2021.
- Is Multi-Hop Reasoning Really Explainable? Towards Benchmarking Reasoning Interpretability. Xin Lv, **Yixin Cao**, Lei Hou, Juanzi Li, Zhiyuan Liu, Yichi Zhang, Zelin Dai. EMNLP2021.
- Learning Relation Prototype from Unlabeled Texts for Long-tail Relation Extraction. **Yixin Cao**, Kuang Jun, Ming Gao, Aoying Zhou, Yonggang Wen and Tat-Seng Chua. TKDE2021.
- Are Missing Links Predictable? An Inferential Benchmark for Knowledge Graph Completion. **Yixin Cao**, Xiang Ji, Xin Lv, Juanzi Li, Yonggang Wen and Hanwang Zhang. ACL2021.
- How does Knowledge Graph and Attention Help? A Qualitative Analysis into Bag-level Relation Extraction. Zikun Hu, **Yixin Cao**, Lifu Huang and Tat-Seng Chua. ACL2021.
- Learning from Miscellaneous Other-Class Words for Few-shot Named Entity Recognition. Meihan Tong, Shuai Wang, Bin Xu, **Yixin Cao**, Minghui Liu, Lei Hou and Juanzi Li. ACL2021.

## 2020
- Tree-augmented Cross-Modal Encoding for Complex-Query Video Retrieval. Xun Yang, Jianfeng Dong, **Yixin Cao**, Xun Yang, Meng Wang and Tat-Seng Chua. SIGIR2020.
- Exploring and Evaluating Attributes, Values, and Structure for Entity Alignment. Zhiyuan Liu, **Yixin Cao**, Liangming Pan, Juanzi Li, Zhiyuan Liu and Tat-Seng Chua. EMNLP2020.
- Expertise Style Transfer A New Task Towards Better Communication between Experts and Laymen. **Yixin Cao**, Ruihao Shui, Liangming Pan, Min-Yen Kan, Zhiyuan Liu and Tat-Seng Chua. ACL2020.
- Improving Event Detection via Open-domain Event Trigger Knowledge. Mei Han Tong, Shuai Wang, **Yixin Cao**, Bin Xu, Lei Hou, Juanzi Li and Jun Xie. ACL2020.
- Reinforced Negative Sampling over Knowledge Graph for Recommendation. Xiang Wang, Yaokun Xu, Xiangnan He, **Yixin Cao**, Meng Wang and Tat-Seng Chua. WWW2020.
- Image Enchanced Event Detection in News Articles. Meihan Tong, Shuai Wang, **Yixin Cao**, Bin Xu, Juanzi Li, Lei Hou, Tat-Seng Chua. AAAI2020.
- DSEL: A Domain-specific Entity Linking System. Xinru Zhang, Huifang Xu, **Yixin Cao**, Yuanpeng Tan, Lei Hou, Juanzi Li, Jiaxin Shi. JIST2020.
- Improving Neural Relation Extraction with Implicit Mutual Relations. Jun Kuang, **Yixin Cao**, Jianbing Zheng, Xiangnan He, Ming Gao, Aoying Zhou. ICDE2020.

## 2019
- Low-Resource Name Tagging Learned with Weakly Labeled Data. **Yixin Cao**, Zikun Hu, Tat-seng Chua, Zhiyuan Liu and Heng Ji. EMNLP2019.
- Semi-supervised Entity Alignment via Joint Knowledge Embedding Model and Cross-graph Model. Chengjiang Li, **Yixin Cao**, Lei Hou, Jiaxin Shi, Juanzi Li and Tat-Seng Chua. EMNLP2019.
- Who, Where, and What to Wear? Extracting Fashion Knowledge from Social Media. Yunshan Ma, Xun Yang, Lizi Liao, **Yixin Cao** and Tat-seng Chua. MM2019.
- Personalized Fashion Recommendation with Visual Explanations based on Multimodal Attention Network: Towards Visually Explainable Recommendation. Xu Chen, Hanxiong Chen, Hongteng Xu, Yongfeng Zhang, **Yixin Cao**, Zheng Qin, Hongyuan Zha. SIGIR2019.
- Explainable reasoning over knowledge graphs for recommendation. Xiang Wang, Dingxian Wang, Canran Xu, Xiangnan He, **Yixin Cao**, Tat-Seng Chua. AAAI2019.
- Multi-Channel Graph Neural Network for Entity Alignment. **Yixin Cao**, Zhiyuan Liu, Chengjiang Li, Juanzi Li, Tat-Seng Chua. ACL2019.
- KGAT: Knowledge Graph Attention Network for Recommendation. Xiang Wang, Xiangnan He, **Yixin Cao**, Meng Liu, Tat-Seng Chua. KDD2019.
- Unifying Knowledge Graph Learning and Recommendation: Towards a Better Understanding of User Preferences. **Yixin Cao**, Xiang Wang, Xiangnan He, Zikun Hu, Tat-Seng Chua. WWW2019.

## 2018
- Joint Representation Learning of Cross-lingual Words and Entities via Attentive Distant Supervision. **Yixin Cao**, Lei Hou, Juanzi Li, Zhiyuan Liu, Chengjiang Li, Xu Chen, Tiansi Dong. EMNLP2018.
- Neural collective entity linking. **Yixin Cao**, Lei Hou, Juanzi Li, Zhiyuan Liu. COLING2018.
- Category Multi-Representation: A Unified Solution for Named Entity Recognition in Clinical Texts. Jiangtao Zhang, Juanzi Li, Shuai Wang, Yan Zhang, **Yixin Cao**, Lei Hou, Xiao-Li Li. PAKDD2018.
- Is a Common Phrase an Entity Mention or Not? Dual Representations for Domain-Specific Named Entity Recognition. Jiangtao Zhang, Juanzi Li, Xiao-Li Li, **Yixin Cao**, Lei Hou, Shuai Wang. DASFAA2018.
- Sequential recommendation with user memory networks. Xu Chen, Hongteng Xu, Yongfeng Zhang, Jiaxi Tang, **Yixin Cao**, Zheng Qin, Hongyuan Zha. WSDM2018.

## 2017
- On Modeling Sense Relatedness in Multi-prototype Word Embedding. **Yixin Cao**, Jiaxin Shi, Juanzi Li, Zhiyuan Liu, Chengjiang Li. IJCNLP2017.
- XLink: An unsupervised bilingual entity linking system. Jing Zhang, **Yixin Cao**, Lei Hou, Juanzi Li, Hai-Tao Zheng. CCL2017.
- Bridge text and knowledge by learning multi-prototype entity mention embedding. **Yixin Cao**, Lifu Huang, Heng Ji, Xu Chen, Juanzi Li. ACL2017.

## 2015
- Target Detection and Knowledge Learning for Domain Restricted Question Answering. Mengdi Zhang, Tao Huang, **Yixin Cao**, Lei Hou. NLPCC2015.
- Name list only? target entity disambiguation in short texts. **Yixin Cao**, Juanzi Li, Xiaofei Guo, Shuanhu Bai, Heng Ji, Jie Tang. EMNLP2015.

# 🎖 Honors and Awards
- *2024* AI2000 most influential scholar honorable mention
- *2023* Google South Asia & Southeast Asia Awards
- *2023* SMU Lee Kong Chian Fellowship (2023-2025)
- *2023* ACL best paper nomination
- *2023* Frontier Science Award, International Foundation Science Conference
- *2020* WWW20/KDD20 most influential paper by PaperDigest
- *2019* WWW19 most influential paper by PaperDigest

# 📖 Experience
- *2024.07 - now*, tenure-track Professor, School of Computer Science, Fudan University.
- *2023.01 - 2024.07*, Assistant Professor, School of Computing and Information Systems, Singapore Management University.
- *2020.10 - 2022.12*, Research Assistant Professor, School of Computer Science and Engineering, Nanyang Technological University. 
- *2018.07 - 2020.12*, Research Fellow, School of Computing, National University of Singapore. 
- *2013.09 - 2018.07*, PhD, School of Computer Science, Tsinghua University. 

# 💬 Invited Talks

- Beyond Benchmarks: the path towards generalizable evaluation
- - KU Leuven [video start@43:00](https://kuleuven-my.sharepoint.com/personal/zehao_wang_kuleuven_be/_layouts/15/stream.aspx?id=%2Fpersonal%2Fzehao%5Fwang%5Fkuleuven%5Fbe%2FDocuments%2FRecordings%2FInvitation%5F%20Meet%2DThe%2DJury%20Seminar%20with%20Prof%2E%20Parisa%20Kordjamshidi%2C%20Prof%2E%20Yixin%20Cao%2C%20and%20Prof%2E%20Jos%C3%A9%20Oramas%2D20250430%5F100553%2D%E4%BC%9A%E8%AE%AE%E8%AE%B0%E5%BD%95%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E256d4c1b%2D8401%2D45d3%2Dacda%2Dcdf0c878e708)
  - AITIME [中文视频](https://www.bilibili.com/video/BV1ULJBzsE1f/?vd_source=858d88d3660cb87fd63590287f6a2499)

- Context scaling: an introduction to RAG and long context LLMs
- - [tutorial@SIGIR2025](https://sites.google.com/view/sigir25-lc-vs-rag/material#h.81284lripwwd)

- From Evaluation To Evolvement: Auto-benchmarking Techniques in the Era of LLMs
- - Shanghai AI Lab Annual conference
  - CCKS2024, CCF China Software Conference2024
  - Huawei Singapore Sentosa sumit2024
  - 
- Towards complex reasoning by meaningful learning with symbolic & neuron systems
- - NLPCC2024
  - COLING2025
  - IAS BU AI Young Scientist Forum2024
  - 
- From Evaluation To Understanding: Auto-benchmarking (Multi-modal) LLMs and Beyond
- - The Chinese University of Hong Kong
  - The Web Conference (WWW) 2024 

- Trustworthy NLP with knowledge guidance.
- - Renmin University, USTC, Fudan University
  - WSDM 2023 

- Multi-modal Event Knowledge Graph
- - CCKS 2022 invited talk
  - Tsinghua University 

- Introduction to Knowledge Graph
- - MITB AI seminar

- Self-guided Universal Knowledge Graph Construction.
- - HIT, Oct, 2021
  - UIUC, Sep, 2021
  - SMU, Aug, 2021

- Domain Specific Knowledge Graph Construction: Towards Wellness Applications
- - NExT++ workshop, NUS, Singapore, 2019.
  - 6Estates, Singapore, 2018.

# 💻 Academic Services
- *2024*,
- - Program Chair@ACL system demo track,
- - Area Chair@(ACL, EMNLP, COLING, ARR)
  - Local organizer@(WWW, EMNLP)
  - Reviewer@(NeurIPS, ICLR, COLM, ICML)
- *2023*,
- - Area Chair@(ACL, EMNLP, COLING, ARR, AACL, CCL)
  - Local organizer@WSDM
  - Reviewer@(NeurIPS, ICLR, COLM, ICML)
- *2022*,
- - Senior Area Chair@(AACL)
  - Area Chair@(ACL, EMNLP, COLING, ARR, AACL, CCL)
  - Reviewer@(NeurIPS, ICLR, COLM, ICML)
