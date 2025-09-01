---
permalink: /
title: "About Me"
excerpt: "Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link href="bootstrap/css/bootstrap.min.css" rel="stylesheet">
<script src="bootstrap/js/bootstrap.bundle.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    :root {
      font-size: 16px; /* 默认16px，改为18px（所有rem单位会按比例缩放） */
    }
</style>


I am Mengyi Yan, 
currently is the assistant Professor at School of Artificial Intelligence, Shandong University.
In Jun. 2025, I received my Ph.D. degree at [the School of Computer Science and Engineering, Beihang University](https://scse.buaa.edu.cn/) (BUAA), under the supervision of [Prof. Jianxin Li](https://scse.buaa.edu.cn/info/1546/10597.htm). 
Before that, I received my bachelor degree at [the School of Mathematical Science, Beihang University](https://math.buaa.edu.cn/) (BUAA) in 2017.
My work focuses on Database, Data Quality, Data Cleaning, and AI4DB with LLM. I welcome collaborations and discussions—feel free to reach out via email yanmy@sdu.edu.cn; yanmy1008@buaa.edu.cn; or yanmy1008@gmail.com.


<h2 style="color: black;">News</h2>
<ul style="list-style-type:disc; padding-left: 0; margin-left: 0;height: 400px;overflow: hidden;overflow-y: scroll;"> 
<li><span class="badge bg-success">AUG 2025</span> Our  <a href="https://authurlord.github.io/files/Conference/PUER_EMNLP.pdf">PUER: Boosting Few-shot Positive-Unlabeled Entity Resolution with Reinforcement Learning</a> paper was accepted to <b>EMNLP 2025</b>. </li>
<li><span class="badge bg-success">JUN 2025</span> Our  <a href="https://authurlord.github.io/files/Journal/FUSER_FCS.pdf">Towards uncertainty-calibrated structural data enrichment with large language model for few-shot entity resolution</a> paper was accepted to <b>Frontiers of Computer Science, 2025</b>. </li>
<li><span class="badge bg-success">DEC 2024</span> Our  <a href="https://authurlord.github.io/files/Conference/UEADB_BigData.pdf">Unsupervised Domain Adaptation for Entity Blocking Leveraging Large Language Models</a> paper was accepted to <b>IEEE Big Data 2024</b>. </li>
</ul>

# Selected Publications
(*Corresponding author. ⁺Alphabetical order.)

**Mengyi Yan**, Wenfei Fan, Yaoshu Wang, and Min Xie*, Enriching Relations with Additional Attributes for ER, *Proceedings of the VLDB Endowment (VLDB)*, 2024. [Link](https://dl.acm.org/doi/10.14778/3681954.3681987)

**Mengyi Yan**, Yaoshu Wang*, Yue Wang, Xiaoye Miao, and Jianxin Li, GIDCL: A Graph-Enhanced Interpretable Data Cleaning Framework with Large Language Models, *ACM SIGMOD International Conference on Management of Data (SIGMOD)*, 2025. [Link](https://github.com/SICS-Fundamental-Research-Center/GIDCL/blob/main/supplementary/GIDCL_Revision_v6_appendix.pdf) [Camera-Ready](https://doi.org/10.1145/3698811)

**Mengyi Yan**, Yaoshu Wang*, Kehan Pang, Min Xie, and Jianxin Li*, Efficient Mixture of Experts based on Large Language Models for Low-Resource Data Preprocessing, *ACM SIGKDD Conference on Knowledge Discovery and Data Mining (SIGKDD)*, 2024. [Link](https://dl.acm.org/doi/10.1145/3637528.3671873)

**Mengyi Yan**, Weilong Ren*, Yaoshu Wang, and Jianxin Li*, A Retrieval-Augmented Framework for Tabular Interpretation with Large Language Model, *Database Systems for Advanced Applications (DASFAA)*, 2024. [Link](https://github.com/SICS-Fundamental-Research-Center/RAFL/blob/master/supplementary/DASFAA_Camera_Ready.pdf)

#### Full Version is available at Publication page above.

# Research Interests
My research focuses on on Database, Data Quality, Data Cleaning, and AI4DB with LLM, with publications in SIGMOD, VLDB, KDD, DASFAA, EMNLP, etc. A brief summary of my past work can be found below.


### Cost-Efficient Data Preprocessing for Data-Centric AI

I have worked on building a high data- and cost-efficient data preprocessing pipeline for LLM, by minimizing labelling and computing cost(most capable on consumer-level hardware with offline LLM) to achieve comparatable results in various data preprocessing scenarios, e.g. Entity Resolution, Tabular Representation Learning and Relation Extraction. Relevant results were published in [[KDD'24](https://authurlord.github.io/files/Conference/MELD_KDD24.pdf), [DASFAA'24](https://authurlord.github.io/files/Conference/DASFAA_Camera_Ready.pdf), [BigData'24](https://authurlord.github.io/files/Conference/UEADB_BigData.pdf) and [EMNLP'25](https://authurlord.github.io/files/Conference/PUER_EMNLP.pdf)].

### Data Cleaning
I have worked on improving the performance of data cleaning systems, by leveraging knowledge-enhanced approaches, e.g. LLM-based agent, Knowledge Graph.  Relevant results were published in [[SIGMOD'25](https://authurlord.github.io/files/Conference/GIDCL-SIGMOD25.pdf), [SIGMOD'24](https://authurlord.github.io/files/Conference/SPLIT-SIGMOD24.pdf), [VLDB'24](https://authurlord.github.io/files/Conference/ENRICH-VLDB24.pdf)]

### Data Evaluation and Synthesis
My research focuses on evaluating and optimizing synthetic data for Large Language Models (LLMs). By applying a suite of machine learning tools (e.g.  Uncertainty Quantification, Influence Functions, and Submodular Optimization), I assess the redundancy and value of data assets throughout the pre-training, fine-tuning, and domain-specific adaptation stages. The primary goal is to determine the optimal composition of training datasets for various specialized tasks, thereby maximizing model performance and training efficiency. Relevant results were published in [[FCS'25](https://authurlord.github.io/files/Journal/FUSER_FCS.pdf), [AIJ'23](https://doi.org/10.1016/j.artint.2023.103886) and [arxiv](https://arxiv.org/pdf/1711.09219)].





<!--
# News
* (2024/11) Our [GPU-Accelerated Graph Cleaning with a Single Machine](https://hsiaoko.github.io/files/paper/miniclean_paper.pdf) paper was accepted to **SIGMOD 2025**.
* (2024/11) Our [A Single Machine System for Querying Big Graphs with PRAM](https://hsiaoko.github.io/files/paper/planar_paper.pdf) paper was accepted to **VLDB 2025**.
* (2024/10) Our [Deep Learning Service for Efficient Data Distribution Aware Sorting](https://hsiaoko.github.io/files/paper/NN-sort_paper.pdf) paper was accepted to **BigData 2024**.
* (2024/10) Our [HyperBlocker: Accelerating Rule-based Blocking in Entity Resolution using GPUs](https://hsiaoko.github.io/files/paper/HyperBlocker_full_paper.pdf) paper was accepted to **VLDB 2025**.
* (2023/04) Our [MiniGraph: Querying Big Graphs with a Single Machine](https://hsiaoko.github.io/files/paper/MiniGraph_full_paper.pdf) paper was accepted to **VLDB 2023**.
* (2022/02) Our [Deep and Collective Entity Resolution in Parallel](https://hsiaoko.github.io/files/paper/PER_paper.pdf) paper was accepted to **ICDE 2022**.
* (2021/09) I joined [Shenzhen Institute of Computing Science](https://en.sics.ac.cn) (SICS) as a research intern.
* (2021/07) Our [DLB: Deep Learning Based Load Balancing](https://hsiaoko.github.io/files/paper/DLB_paper.pdf) paper was accepted to **CLOUD 2021**.
* 
# Talks
* "MiniGraph: Querying Big Graphs with a Single Machine"
  * Great Bay Area Digital Tech Workshop, June 2023
  * VLDB conference, September 2023
* "DLB: Deep Learning Based Load Balancing"
  * IEEE CLOUD conference, September 2021


# Professional Services
### External Reviewer
* ICDE'24, ICDE'25

<br/><br/>
-->

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=000000&w=230&t=tt&d=eHHOFbP732DR-cMe1ytaYJxII5gJ_ocpixMhAWlufLU&co=ffffff&ct=0a0909&cmn=00fff0&cmo=f3cefc'></script>
