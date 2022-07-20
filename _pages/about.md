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

I’m Lunyiu Nie, a computer science Master student at Tsinghua University. My advisor is Prof. [Jidong Zhai](https://pacman.cs.tsinghua.edu.cn/~zjd/) and I am also co-advised by Prof. [Juanzi Li](http://keg.cs.tsinghua.edu.cn/persons/ljz/). My research interests mainly lie in the intersection of programming language and natural language, including NL-to-code generation (semantic parsing) and code representation learning.

I completed my Bachelor’s Degree study at the Chinese University of Hong Kong, during which I was advised by Prof. [Helen Meng](https://www.se.cuhk.edu.hk/people/academic-staff/prof-meng-mei-ling-helen/) and Prof. [Wai Lam](http://www1.se.cuhk.edu.hk/~textmine/). Previously I also worked as a research intern at the Institute of Computing Technology, Chinese Academy of Sciences co-supervised by Prof. [Yungang Bao](http://acs.ict.ac.cn/baoyg/) and Prof. [Qun Huang](https://huangqundl.github.io/).


# 🔥 News
- *2022.06*: I've joined Microsoft Research Asia as a summer intern at Data, Knowledge, and Intelligence Group.
- *2022.05*: Our work _KQA Pro_ has been accepted by ACL 2022 as a long paper. &nbsp;🎉
 

# 📝 Publications 
[GraphQ IR: Unifying Semantic Parsing of Graph Query Language with Intermediate Representation](https://arxiv.org/abs/2205.12078)

**Lunyiu Nie**, Shulin Cao, Jiaxin Shi, Qi Tian, Lei Hou, Juanzi Li, Jidong Zhai

- TLDR: We propose GraphQ IR, a novel intermediate representation that aims to bridge the semantic gap between natural language and graph query languages (e.g., SPARQL, Cypher, Lambda-DCS, KoPL, etc). Experiments show that our approach can consistently achieve state-of-the-art performance on several semantic parsing benchmarks *Overnight*, *KQA Pro*, *GrailQA* and *MetaQA-Cypher*, with promising generalizability under non-IID (compositional generalization and zero-shot) as well as low-resource settings. We also implement a source-to-source compiler that supports transpilation among graph query languages.

------
[KQA Pro: A Dataset with Explicit Compositional Programs for Complex Question Answering over Knowledge Base](https://aclanthology.org/2022.acl-long.422/)

Shulin Cao, Jiaxin Shi, Liangming Pan, **Lunyiu Nie**, Yutong Xiang, Lei Hou, Juanzi Li, Hanwang Zhang, Bin He

- In _ACL 2022_ (Long Paper)
- TLDR: We introduce KQA Pro, a dataset for complex KBQA including ~120K diverse natural language questions, which is currently also the largest parellel corpus for NLQ-to-SPARQL task. The questions are very diverse and challenging, requiring complex reasoning capabilities including compositional reasoning, multi-hop reasoning, quantitative comparison, set operations, and etc.

------
[Code Structure Guided Transformer for Source Code Summarization](https://dl.acm.org/doi/10.1145/3522674)

Shuzheng Gao, Cuiyun Gao, Yulan He, Jichuan Zeng, **Lunyiu Nie**, Xin Xia, Michael Lyu

- In _ACM Transactions on Software Engineering and Methodology (TOSEM)_ (2022)
- TLDR: We propose SG-Trans to incorporate code structural features into the Transformer framework. To capture the hierarchical characteristics of code, we inject the local symbolic information (e.g., code tokens) and global syntactic structure (e.g., data flow) into the self-attention module as inductive bias. 

------
[CoreGen: Contextualized Code Representation Learning for Commit Message Generation](https://doi.org/10.1016/j.neucom.2021.05.039)

**Lunyiu Nie**, Cuiyun Gao, Zhicong Zhong, Wai Lam, Yang Liu, Zenglin Xu

- In *Neurocomputing* (2021)
- TLDR: We propose a novel code representation learning method named CoreGen that exploits the contextual information behind the code changes via self-supervised learning. Evaluation on the commit message generation benchmark shows that our model outperforms over the baseline models with >28.18% BLEU-4 score improvement.

------
[Unstructured Knowledge Access in Task-oriented Dialog Modeling using Language Inference, Knowledge Retrieval and Knowledge-Integrative Response Generation](https://arxiv.org/abs/2101.06066)

Mudit Chaudhary, Borislav Dzodzo, Sida Huang, Chun Hei Lo, Mingzhi Lyu, **Lunyiu Nie**, Jinbo Xing, Tianhua Zhang, Xiaoying Zhang, Jingyan Zhou, Hong Cheng, Wai Lam, Helen Meng

- In *AAAI-21 DSTC9 Workshop* (2021), Finalist of The 9th Dialog System Technology Challenge (DSTC9) Track 1.
- TLDR: We propose a pipeline framework for task-oriented dialog modeling with unstructured knowledge access. Our methods can significantly improve the performance of dialog systems and generate high-quality responses, achieving at least 58.77% improvement on BLEU-4 score over the baseline.

------
[ATOM: Commit Message Generation Based on Abstract Syntax Tree and Hybrid Reranking](https://doi.org/10.1109/TSE.2020.3038681)

Shangqing Liu, Cuiyun Gao, Sen Chen, **Lunyiu Nie**, Yang Liu.

- In *IEEE Transactions on Software Engineering (TSE)* (2020)
- TLDR: We develop a novel commit message generation model that explicitly incorporates the abstract syntax tree for representing code changes and integrates both retrieved and generated messages through hybrid ranking. Experimental results demonstrate that our approach improves the state-of-the-art models by 30.72% in terms of BLEU-4.


# 🏆 Honors and Awards
- *2021*    Tsinghua University - Weihai Talent Scholarship. 
- *2018-20* CUHK Faculty Dean's List (Top 10%).
- *2019-20* CUHK Wu Yee Sun Collge Master's List (Ranked 1st/major).
- *2017-18* Deparment Academic Excellence Award.
- *2017*    HKSAR Government Scholarship.

# 📖 Educations
- *2020.09 - 2023.07 (now)*, Tsinghua University, Master’s Degree in Computer Science and Technology. CGPA: 3.76 / 4.00. 
- *2015.08 - 2020.07*, The Chinese University of Hong Kong, B.B.A. (Honours) Degree, Second Major in Computer Science. CGPA: 3.60 / 4.00, Computer Science GPA: 3.70 / 4.00.

# 💻 Internships
- *2022.06 - Present*, Microsoft Research Asia
- *2021.07 - 2022.03*, Alibaba Cloud
- *2018.07 - 2018.08*, Institute of Computing Technology, Chinese Academy of Sciences
