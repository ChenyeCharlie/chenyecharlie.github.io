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

# About Me

Hi! I am Ye Chen (陈晔), a fourth-year undergraduate student at [Xi&#39;an Jiaotong University (XJTU)](https://www.xjtu.edu.cn/) and [Politecnico di Milano (POLIMI)](https://www.polimi.it/). Currently, I am pursuing a triple Bachelor degree, including a B.Eng in Computer Science and Technology at XJTU (supervised by Prof. [Qin Xia](https://gr.xjtu.edu.cn/en/web/qin.xia/home)) and a Dual B.Arch in Architecture at XJTU and POLIMI (supervised by Prof. [Shanyao Zhu](https://gr.xjtu.edu.cn/en/web/way.zsy)).

I am a research beginner, full of passion and self-motivated. My research interest includes Multimodal LLM and Agentic System. In addition, I possess a strong curiosity regarding cutting-edge research topics and interdisciplinary applications.

Currently, I am experiencing my internship as Machine Learning intern at [OriginArkAI](), supervised by [Wenhui Dong](https://dwenhui.com/). And I am serving as an intern at [T-Lab](https://xiaoyingtang-cuhk.github.io/zh/index.html) at [The Chinese University of Hong Kong, Shenzhen (CUHKSZ)](https://cuhk.edu.cn/zh-hans), supervised by Prof. [Xiaoying Tang](https://sse.cuhk.edu.cn/faculty/tangxiaoying).

Beside those, I am a keen enthusiast of basketball and swimming. If you would like to connect with me, please feel free to drop me an email or add my [WeChat](../images/wechatqr.jpg).

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News
<!-- - *2026.08*: The work I participated in (Emoupdate) was announced on Arxiv! -->
- *2026.08*: &nbsp;🎉🎉 The work I participated in (SEPO) was accept by EMNLP(Findings) 2026!
- *2026.08*: The work I participated in (HN-Clip) was announced on Arxiv!
- *2026.07*: The work I participated in (TARA) was announced on Arxiv!
- *2026.07*: The work I participated in (CMVF) was announced on Arxiv!
- *2026.04*: &nbsp;🎉🎉 The first work I participated in (POES) was announced on Arxiv!


# 📝 Publications 

- [SEPO: Evidence-Grounded Prompt Optimization via Structural Editing](), Xiaoyu Ma, Haoyue Liu, Yiwen li, Jionghao Zhu, Zhichao Wang, **Ye Chen**, Xiaoying Tang, **EMNLP(Findings) 2026**

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP(Findings) 2026</div><img src='images/SEPO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SEPO: Evidence-Grounded Prompt Optimization via Structural Editing]()

Xiaoyu Ma, Haoyue Liu, Yiwen li, Jionghao Zhu, Zhichao Wang, **Ye Chen**, Xiaoying Tang

[**Project**]() <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- SEPO is a framework replacing opaque whole-prompt rewrites with structured, evidence-grounded local edits that are traceable, more accurate, and substantially more token-efficient.
</div>
</div>



# 📝 Preprints

<!-- - [Do SpeechLMs Hear Their Own Opinions? Diagnosing and Mitigating Previous-Belief Contamination in Streaming Emotion Understanding](), Haoyue Liu, Zhichao Wang, **Ye Chen**, Haonan Deng, Xiaoying Tang, **Arxiv** -->
- [Which Negatives Matter? Ask Your Text Encoder: Adaptive Similarity Margins for Dense-Caption Retrieval](https://arxiv.org/abs/2608.18521), Haoyue Liu, **Ye Chen**, Zhichao Wang, Xiaoying Tang, **Arxiv**
- [Are Prompt Optimizers Blind? Cross-Modal Visual Feedback for Automatic Prompt Optimization](https://arxiv.org/abs/2607.24354), Haoyue Liu, Xiaoyu Ma, **Ye Chen**, Yuexian Zou, Xiaoying Tang, **Arxiv**
- [One Rewrite to Fix Them All? Type-Aware Repair Allocation for Text-to-Image Prompt Optimization](https://arxiv.org/abs/2607.18724), Haoyue Liu, Xiaoyu Ma, **Ye Chen**, Shuguang Cui, Xiaoying Tang, **Arxiv**
- [Select Smarter, Not More: Prompt-Aware Evaluation Scheduling with Submodular Guarantees](https://arxiv.org/abs/2604.11328), Xiaoyu Ma, Yiwen Li, Haoyue Liu, Zhichao Wang, **Ye Chen**, Yongxin Guo, Xiaoying Tang, **Arxiv**



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/Emoupdate.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Do SpeechLMs Hear Their Own Opinions? Diagnosing and Mitigating Previous-Belief Contamination in Streaming Emotion Understanding]()

H Liu, Z Wang, **Y Chen**, H Deng, X Tang*

[**Project**]() <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Emoupdate is a training-free framework that separates current-audio perception from historical state revision through three components: prior-blind acoustic firewall, evidence-shrunk causal belief filter and decontamination operator.
</div>
</div> -->



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/HNClip.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Which Negatives Matter? Ask Your Text Encoder: Adaptive Similarity Margins for Dense-Caption Retrieval](https://arxiv.org/pdf/2608.18521)

H Liu, **Y Chen**, Z Wang, X Tang*

[**Project**](https://arxiv.org/pdf/2608.18521) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- HN-CLIP is a method that uses the text encoder's own text-text geometry to construct per-negative adaptive similarity margins.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/CMVF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Are Prompt Optimizers Blind? Cross-Modal Visual Feedback for Automatic Prompt Optimization](https://arxiv.org/pdf/2607.24354)

H Liu, X Ma, **Y Chen**, Y Zou, X Tang*

[**Project**](https://arxiv.org/pdf/2607.24354) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A framework that lets prompt optimizers inspect failed images during optimization, distill recurring visual blind spots into a reusable text prompt, and improve multimodal performance with no additional inference-time cost.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/TARA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[One Rewrite to Fix Them All? Type-Aware Repair Allocation for Text-to-Image Prompt Optimization](https://arxiv.org/pdf/2607.18724)

H Liu, X Ma, **Y Chen**, S Cui, X Tang*

[**Project**](https://arxiv.org/pdf/2607.18724) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A training-free framework that diagnoses different text-to-image generation failures, routes each to a type-specific repair, and compiles them into a single optimized prompt to improve semantic fidelity with only one additional regeneration.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/POES.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Select Smarter, Not More: Prompt-Aware Evaluation Scheduling with Submodular Guarantees](https://arxiv.org/pdf/2604.11328)

X Ma, Y Li, H Liu, Z Wang, **Y Chen**, Y Guo, X Tang*

[**Project**](https://arxiv.org/pdf/2604.11328) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A framework that treats APO as an online adaptive testing problem to dynamically select the most informative evaluation subsets for higher accuracy and less computational costs. 
</div>
</div>



# 🎖 Honors and Awards

- *2026.05* The Mathematical Contest in Modeling Honorable Mentioned
- *2025.11* School Scholarship of XJTU-POLIMI Joint School
- *2025.10* Outstanding Peer Instructor of Xi'an Jiaotong University
- *2024.12* National Scholarship
- *2024.05* National TOP 30 of Taobao University Student Innovation Challenge
- *2023.12* University Scholarship of Xi'an Jiaotong University

# 📖 Educations

- *2024.03 - 2027.06 (Expeted)*, Undergraduate, B.Eng in Computer Science and Technology, Xi'an Jiaotong University.
- *2022.09 - 2027.06 (Expeted)*, Undergraduate, B.Arch in Architecture, Politecnico di Milano.
- *2022.09 - 2027.06 (Expeted)*, Undergraduate, B.Arch in Architecture, Xi'an Jiaotong University.
- *2019.09 - 2022.06*, Zhejiang Ouhai Middle School, Wenzhou.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships

- *2026.06 - present*, [OriginArkAI](), Hangzhou. (Machine Learning Intern, supervised by [Wenhui Dong](https://dwenhui.com/))
- *2025.07 - present*, [T-Lab](https://xiaoyingtang-cuhk.github.io/zh/index.html), [The Chinese University of Hong Kong (Shenzhen)](https://cuhk.edu.cn/zh-hans), Shenzhen. (Lab Intern, supervised by Prof. [Xiaoying Tang](https://sse.cuhk.edu.cn/faculty/tangxiaoying))
- *2026.05 - 2025.06*, [Z-Data Team](https://www.zhipuai.cn/zh), [ZhipuAI](https://www.zhipuai.cn/zh), Beijing. (AI Data Intern, Remote)
- *2025.03 - 2025.11*, [LDLab](https://space.bilibili.com/3546828471536346?spm_id_from=333.337.0.0), [Xi&#39;an Jiaotong University](https://www.xjtu.edu.cn/), Xi'an. (Lab Intern, supervised by Prof. [Donghe Li](https://gr.xjtu.edu.cn/en/web/lidonghe2020/home))
- *2024.07 - 2024.08*, [Beijing Computing Center](https://www.bcc.ac.cn/pc/zh/index.html), Beijing. (ML Intern, supervised by Fanyin Meng)