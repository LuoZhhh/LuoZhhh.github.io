---
permalink: /
title: ""
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

Hello, I am Zihan Luo, currently an Assistant Researcher at Chongqing University (CQU) <img src='./images/CQU.jpg' style="width: 1.5em;">. I received my Ph.D. in Computer Science from Huazhong University of Science and Technology (HUST) <img src='./images/hust.png' style="width: 4em;">, where I was fortunate to be supervised by Professor [Hong Huang (黄宏)](https://faculty.hust.edu.cn/honghuang/en/index.htm) and Principal Researcher [Jianxun Lian (练建勋)](https://www.microsoft.com/en-us/research/people/jialia/) from Microsoft Research Asia <img src='./images/microsoft_logo.svg' style="width: 4em;">. Before that, I received my Bachelor's degree in Electronic Engineering from HUST <img src='./images/hust.png' style="width: 4em;"> in 2020, and was fortunate to work closely with Professor [Rui Yin (尹睿)](https://rayin-saber.github.io/yinrui.github.io/) from the University of Florida <img src='./images/ufl.webp' style="width: 4em;">. During my academic journey, I also enriched my research experience through internships at **Zhipu AI** <img src='./images/zhipu-color (1).svg' style="width: 1.5em;"> (focusing on LLM Alignment for Machine Learning Engineering) and **OPPO** <img src='./images/Oppo-Logo.wine.svg' style="width: 3em;"> (working on LLM-based in-conversation recommendation). I actively serve the academic community as a reviewer for top-tier venues such as **NeurIPS**, **KDD**, **WWW**, **COLM**, and **Frontiers of Computer Science**.

My research broadly lies at the intersection of **Large Language Models (LLMs)** and **Graph Data Mining**. I am deeply passionate about building AI systems that are not only intelligent but also robust, reliable, and beneficial to society. My current research focuses on:

*   **Trustworthy AI:** Enhancing the fairness, robustness, and interpretability of Graph Neural Networks and LLMs against biases and adversarial attacks.
*   **Societal AI & Alignment:** Calibrating and aligning large language models with human preference and exploring the mutual enhancement between complex AI systems and interdisciplinary fields such as sociology and psychology.

**✨ Prospective Students & Collaborators:**
> I am always on the lookout for <b style="color:#FC4E2A">highly self-motivated</b> undergraduate and graduate students to join my research group. If you are passionate about <b style="color:#FC4E2A">LLMs, data mining, or trustworthy AI</b>, and are driven by a strong curiosity to solve <b style="color:#FC4E2A">impactful real-world problems</b>, I would love to hear from you! Please feel free to <b style="color:#FC4E2A">drop me an email</b> with your CV and a brief introduction of your background. You can check my full publication list on google scholar <a href='https://scholar.google.com/citations?user=JWUJkawAAAAJ'><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FLuoZhhh%2Fluozhhh.github.io%40google-scholar-stats%2Fgs_data_shieldsio.json&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" style="display:inline-block; vertical-align:middle;"></a>.


# 🔥 News

<div style="max-height: 180px; overflow-y: auto; padding: 15px; border: 1px solid #e2e8f0; border-radius: 8px; margin-bottom: 20px; background-color: #fafafa;">
  <ul style="margin: 0; padding-left: 20px;">
    <li style="margin-bottom: 10px;">
      <span style="color:#FC4E2A"><b>[2026.06]</b></span>: &nbsp; <a href="https://arxiv.org/abs/2606.08466" target="_blank">ToolRec</a> is released on arxiv. Please check out!
    </li>
    <li style="margin-bottom: 10px;">
      <span style="color:#FC4E2A"><b>[2026.04]</b></span>: &nbsp; One paper on evaluation of LLM-based paper revision is accepted by <b>ACL 2026</b> as findings, accept rate 18%.
    </li>
    <li style="margin-bottom: 10px;">
      <span style="color:#FC4E2A"><b>[2026.01]</b></span>: &nbsp; I am invited to serve as the reviewer for <b>COLM 2026</b>.
    </li>
    <li style="margin-bottom: 10px;">
      <span style="color:#FC4E2A"><b>[2025.10]</b></span>: &nbsp; <a href="https://arxiv.org/abs/2403.04483" target="_blank">GraphInstruct</a> is accepted by <b>Frontiers of Computer Science</b>. Please check out!
    </li>
    <li style="margin-bottom: 10px;">
      <span style="color:#FC4E2A"><b>[2024.11]</b></span>: &nbsp; One paper on GNN hybrid fairness is accepted by <b>KDD 2025</b>, accept rate 19%.
    </li>
    <li style="margin-bottom: 0;">
      <span style="color:#FC4E2A"><b>[2024.09]</b></span>: &nbsp; One paper on graph fairness attacks is accepted by <b>NeurIPS 2024</b>, accept rate 25.8%.
    </li>
  </ul>
</div>

# 📝 Publications 
- <span style="color:#337AB7">[**Preprint**]</span> **Zihan Luo**, Lingkui Chen, Ruike Zhang, Hong Huang, Boyang Zhang, Ziniu Chen, Lizhong Wang. **ToolRec: Calibrated Preference Alignment for Query Recommendation in On-Device Assistants.**
  Under review. [[PAPER](https://arxiv.org/abs/2606.08466)]

- <span style="color:#337AB7">[**ACL'26**]</span> **Zihan Luo**, Hong Huang, Jianxun Lian, Yu Chang, Xing Xie, Hai Jin. **Can AI Revise Research Papers with Human Review Feedback? An Empirical Study and Benchmark.**
  In *Findings of Annual Meeting of the Association for Computational Linguistics (ACL)*, 2026. (<span style="color:#FC4E2A">CCF-A</span>) [[CODE](https://github.com/CGCL-codes/ReviseBench)] 

- <span style="color:#337AB7">[**Frontiers of Computer Science**]</span> **Zihan Luo**, Xiran Song, Hong Huang, Jianxun Lian, Chenhao Zhang, Jinqi Jiang, Xing Xie, Hai Jin. **GraphInstruct: Empowering Large Language Models with Graph Understanding and Reasoning Capability.**
  In *Frontiers of Computer Science (FCS)*, 2025. (<span style="color:#FC4E2A">CCF-T1</span>) [[PAPER](https://arxiv.org/abs/2403.04483)] [[CODE](https://github.com/CGCL-codes/GraphInstruct)] 

- <span style="color:#337AB7">[**KDD'25**]</span> **Zihan Luo**, Hong Huang, Jianxun Lian, Xiran Song, Hai Jin. **Towards Controllable Hybrid Fairness in Graph Neural Networks.**
  In *ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)*, 2025. (<span style="color:#FC4E2A">CCF-A</span>) [[PAPER](https://dl.acm.org/doi/10.1145/3690624.3709224)]

- <span style="color:#337AB7">[**NeurIPS'24**]</span> **Zihan Luo**, Hong Huang, Yongkang Zhou, Jiping Zhang, Nuo Chen, Hai Jin. **Are Your Models Still Fair? Fairness Attacks on Graph Neural Networks via Node Injections.**
  In *Annual Conference on Neural Information Processing Systems (NeurIPS)*, 2024. (<span style="color:#FC4E2A">CCF-A</span>) [[PAPER](https://arxiv.org/abs/2406.03052)] [[CODE](https://github.com/LuoZhhh/NIFA)] [[AI-TIME](https://www.bilibili.com/video/BV1i5UQYNEeX/?share_source=copy_web&vd_source=9196fa9a82ed33188b75c84264f0f084)]

- <span style="color:#337AB7">[**NeurIPS'23**]</span> **Zihan Luo**, Hong Huang, Jianxun Lian, Xiran Song, Xing Xie, Hai Jin. **Cross-links Matter for Link Prediction: Rethinking the Debiased GNN from a Data Perspective.**
  In *Annual Conference on Neural Information Processing Systems (NeurIPS)*, 2023. (<span style="color:#FC4E2A">CCF-A</span>) [[PAPER](https://openreview.net/pdf?id=sJDkwMVqb9)] [[CODE](https://github.com/CGCL-codes/Cross-links-Bias)] 

- <span style="color:#337AB7">[**WWW'23**]</span> Xiran Song, Jianxun Lian, Hong Huang, **Zihan Luo**, Wei Zhou, Xue Lin, Mingqi Wu, Chaozhuo Li, Xing Xie, Hai Jin. **xGCN: An Extreme Graph Convolutional Network for Large-scale Social Link Prediction.**
  In *ACM Web Conference (WWW)*, 2023. (<span style="color:#FC4E2A">CCF-A</span>) [[PAPER](https://dl.acm.org/doi/10.1145/3543507.3583340)] [[CODE](https://github.com/CGCL-codes/XGCN_library)] [[Youtube](https://www.youtube.com/watch?v=8yedOmd_3Fw)]

- <span style="color:#337AB7">[**Journal of Biomedical Informatics**]</span> Rui Yin\*, **Zihan Luo**\*, Pei Zhuang, Chee Keong Kwoh, Zhuoyi Lin. **ViPal: A Framework for Virulence Prediction of Influenza Viruses with Prior Viral Knowledge Using Genomic Sequences.**
  In *Journal of Biomedical Informatics (JBI)*, 2023. (<span style="color:#FC4E2A">CCF-C</span>) [[PAPER](https://www.biorxiv.org/content/biorxiv/early/2022/03/27/2022.03.24.485635.full.pdf)] [[CODE](https://github.com/Rayin-saber/ViPal)]

- <span style="color:#337AB7">[**WSDM'22**]</span> **Zihan Luo**, Jianxun Lian, Hong Huang, Xing Xie, Hai Jin. **Ada-GNN: Adapting to Local Patterns for Improving Graph Neural Networks.**
  In *ACM International Conference on Web Search and Data Mining (WSDM)*, 2022. (<span style="color:#FC4E2A">CCF-B</span>) [[PAPER](https://dl.acm.org/doi/abs/10.1145/3488560.3498460)] [[CODE](https://github.com/LuoZhhh/Ada-GNN)]

- <span style="color:#337AB7">[**Current Genomics**]</span> Rui Yin, **Zihan Luo**, Chee Keong Kwoh. **Exploring the Lethality ofHuman-adapted Coronavirus through Alignment-free Machine Learning Approaches Using Genomic Sequences.**
  In *Current Genomics*, 2021. [[PAPER](https://www.benthamdirect.com/content/journals/cg/10.2174/1389202923666211221110857)] [[CODE](https://github.com/Rayin-saber/Alignment-free-lethality-prediction-of-coronavirus)]

- <span style="color:#337AB7">[**Bioinformatics**]</span> Rui Yin, **Zihan Luo**, Pei Zhuang, Zhuoyi Lin, Chee Keong Kwoh. **VirPreNet: A Weighted Ensemble Convolutional Neural Network for the Virulence Prediction of Influenza A Virus Using All Eight Segments.**
  In *Bioinformatics*, 2021. (<span style="color:#FC4E2A">CCF-A</span>) [[PAPER](https://www.biorxiv.org/content/biorxiv/early/2020/07/31/2020.07.31.230904.full.pdf)] [[CODE](https://github.com/Rayin-saber/VirPreNet)]
