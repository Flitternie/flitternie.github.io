---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I’m Lunyiu Nie, a computer science PhD student at UT Austin advised by Prof. [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/). My research interests mainly lie in the intersection of **Programming Languages** and **Natural Language Processing**. 

I completed my computer science Master's Degree at Tsinghua University. My advisor at Tsinghua was Prof. [Jidong Zhai](https://pacman.cs.tsinghua.edu.cn/~zjd/) and I also received advice from Prof. [Juanzi Li](http://keg.cs.tsinghua.edu.cn/persons/ljz/). I obtained my Bachelor’s Degree at the Chinese University of Hong Kong, during which I was advised by Prof. [Helen Meng](https://www.se.cuhk.edu.hk/people/academic-staff/prof-meng-mei-ling-helen/) and Prof. [Wai Lam](http://www1.se.cuhk.edu.hk/~textmine/). 

# 🔥 News
- *2023.08*: Started my PhD journey! Nice to see you all at Austin! 🙌
- *2022.11*: Our work _"Guiding the PLMs with Semantic Anchors"_ has been accepted by AAAI 2023 as a long paper. &nbsp;🎉 
- *2022.10*: Our work _"GraphQ IR"_ has been accepted by EMNLP 2022 as a long paper. &nbsp;🎉 
 

# 📝 Publications 
[Online Cascade Learning for Efficient Inference over Streams](https://arxiv.org/abs/2402.04513)

**Lunyiu Nie**, Zhimin Ding, Erdong Hu, Christopher Jermaine, Swarat Chaudhuri
- TLDR: This work presents an online cascade learning framework for enhancing the efficiency of LLMs in handling streaming queries. Theoretical analysis provides a no-regret performance guarantee for the algorithm. Experimental results on several benchmarks confirmed the effectiveness of our approach, showing that it can achieve comparable accuracy as LLMs while saving up to 90% of the inference costs

------
[Unveiling the Black Box of PLMs with Semantic Anchors: Towards Interpretable Neural Semantic Parsing](https://arxiv.org/abs/2210.01425/)

**Lunyiu Nie\***, Jiuding Sun\*, Yanling Wang, Lun Du, Han Shi, Dongmei Zhang, Lei Hou, Juanzi Li, Jidong Zhai  
- In _AAAI 2023_ (Long Paper, Oral) [[🖇️Code]](https://github.com/Flitternie/Semantic_Anchor)
- TLDR: Current PLM-based neural semantic parsers are often suffering from hallucination issues due to their negligence of logical form structures and lacking in intrinsic interpretability. To alleviate the problems, we propose a novel hierarchical decoder architecture and two intermediate supervision tasks that explicitly guiding the PLMs to address the structural information alongside the fine-tuning. By probing the PLM inner layer outputs, our work also provides a novel testbed for interpreting the intermediate process of logical form generation.

------
[GraphQ IR: Unifying the Semantic Parsing of Graph Query Languages with One Intermediate Representation](https://arxiv.org/abs/2205.12078)

**Lunyiu Nie**, Shulin Cao, Jiaxin Shi, Qi Tian, Lei Hou, Juanzi Li, Jidong Zhai

- In _EMNLP 2022_ (Long Paper) [[🖇️Code]](https://github.com/Flitternie/GraphQ_IR)
- TLDR: We propose GraphQ IR, a novel intermediate representation that aims to bridge the semantic gap between natural language and graph query languages (e.g., SPARQL, Cypher, Lambda-DCS, KoPL, etc). With GraphQ IR as a middleware, we also implement a transpiler that supports translation among multiple graph query languages. Experiments show that our approach can consistently achieve SOTA performance on several semantic parsing benchmarks *Overnight*, *KQA Pro*, *GrailQA* and *MetaQA-Cypher*, with promising generalizability under non-IID (compositional generalization and zero-shot) & low-resource settings. 

------
[KQA Pro: A Dataset with Explicit Compositional Programs for Complex Question Answering over Knowledge Base](https://aclanthology.org/2022.acl-long.422/)

Shulin Cao, Jiaxin Shi, Liangming Pan, **Lunyiu Nie**, Yutong Xiang, Lei Hou, Juanzi Li, Hanwang Zhang, Bin He

- In _ACL 2022_ (Long Paper) [[🖇️Dataset]](https://thukeg.gitee.io/kqa-pro/)
- TLDR: We introduce KQA Pro, a dataset for complex KBQA including ~120K diverse natural language questions, which is currently also the largest parellel corpus for NLQ-to-SPARQL task. The questions are very diverse and challenging, requiring complex reasoning capabilities including compositional reasoning, multi-hop reasoning, quantitative comparison, set operations, and etc.

------
[Code Structure Guided Transformer for Source Code Summarization](https://dl.acm.org/doi/10.1145/3522674)

Shuzheng Gao, Cuiyun Gao, Yulan He, Jichuan Zeng, **Lunyiu Nie**, Xin Xia, Michael Lyu

- In _ACM Transactions on Software Engineering and Methodology (TOSEM)_ (2022) [[🖇️Code]](https://github.com/shuzhenggao/SG-Trans)
- TLDR: We propose SG-Trans to incorporate code structural features into the Transformer framework. To capture the hierarchical characteristics of code, we inject the local symbolic information (e.g., code tokens) and global syntactic structure (e.g., data flow) into the self-attention module as inductive bias. 

------
[CoreGen: Contextualized Code Representation Learning for Commit Message Generation](https://doi.org/10.1016/j.neucom.2021.05.039)

**Lunyiu Nie**, Cuiyun Gao, Zhicong Zhong, Wai Lam, Yang Liu, Zenglin Xu

- In *Neurocomputing* (2021) [[🖇️Code]](https://github.com/Flitternie/CoreGen)
- TLDR: We propose a novel code representation learning method named CoreGen that exploits the contextual information behind the code changes via self-supervised learning. Evaluation on the commit message generation benchmark shows that our model outperforms over the baseline models with >28.18% BLEU-4 score improvement.

------
[Unstructured Knowledge Access in Task-oriented Dialog Modeling using Language Inference, Knowledge Retrieval and Knowledge-Integrative Response Generation](https://arxiv.org/abs/2101.06066)

Mudit Chaudhary, Borislav Dzodzo, Sida Huang, Chun Hei Lo, Mingzhi Lyu, **Lunyiu Nie**, Jinbo Xing, Tianhua Zhang, Xiaoying Zhang, Jingyan Zhou, Hong Cheng, Wai Lam, Helen Meng 

- In *AAAI-21 DSTC9 Workshop* (2021), Finalist of the 9th Dialog System Technology Challenge (DSTC9) Track 1. [[🖇️Code]](https://github.com/muditchaudhary/CUHK-DSTC9)
- TLDR: We propose a pipeline framework for task-oriented dialog modeling with unstructured knowledge access. Our methods can significantly improve the performance of dialog systems and generate high-quality responses, achieving at least 58.77% improvement on BLEU-4 score over the baseline.

------
[ATOM: Commit Message Generation Based on Abstract Syntax Tree and Hybrid Reranking](https://doi.org/10.1109/TSE.2020.3038681)

Shangqing Liu, Cuiyun Gao, Sen Chen, **Lunyiu Nie**, Yang Liu.

- In *IEEE Transactions on Software Engineering (TSE)* (2020) 
- TLDR: We develop a novel commit message generation model that explicitly incorporates the abstract syntax tree for representing code changes and integrates both retrieved and generated messages through hybrid ranking. Experimental results demonstrate that our approach improves the state-of-the-art models by 30.72% in terms of BLEU-4.


# 🏆 Honors and Awards
- *2022*    Tsinghua Outstanding Thesis Award & Outstanding Graduate Award (**Top 1** in CS Department)
- *2022*    Tsinghua Special Class Scholarship (**Highest** award for Hong Kong Students, <0.5%).
- *2022*    Microsoft Research Asia - Award of Excellence.
- *2021*    Tsinghua Comprehensive Excellence Scholarship. 
- *2018-20* CUHK Faculty Dean's List (Top 10%).
- *2019-20* CUHK Wu Yee Sun Collge Master's List (Ranked 1st/major).
- *2017-18* Deparment Academic Excellence Award.
- *2017*    HKSAR Government Scholarship.

# 📖 Educations
- *2023.08 - Now*, The University of Texas at Austin, Ph.D. Student in Computer Science.
- *2020.09 - 2023.06*, Tsinghua University, M.Sc. in Computer Science and Technology. 
- *2015.08 - 2020.07*, The Chinese University of Hong Kong, B.B.A. (Honours) in Professional Accountancy, Second Major in Computer Science.

# 💻 Internships
- *2022.06 - 2022.09*, Microsoft Research Asia.
- *2021.07 - 2022.03*, Alibaba Cloud.
- *2018.07 - 2018.08*, Institute of Computing Technology, Chinese Academy of Sciences.
