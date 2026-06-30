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

I am an undergraduate researcher in Virtual Reality Technology at **Nanyang Institute of Technology** (expected Jun. 2026), ranked **1st in my major**. I have been a research intern at the **Future Lab, Tsinghua University**, where I designed and built AI-driven AR systems for everyday repair and sustainability.

My work spans two interconnected threads: **(1) interactive AR/XR systems** that use AI to scaffold hands-on tasks such as repair and repurposing, and **(2) multi-modal AI pipelines** that help researchers make sense of complex, heterogeneous data — from historical photographs to oral history interviews. Across three publications, I have served as the primary technical implementer, independently building complete XR systems and LLM agent pipelines that enabled user studies at top HCI venues.

I am applying for **PhD / MS programs in Human-Computer Interaction** for Fall 2027.

# 🔥 News
- *2026.07*: &nbsp; Currently working on a co-first-author project applying multi-modal AI (object detection, NLP, CLIP, graph modeling) to reconstruct the material culture of Chinese domestic spaces from oral histories and historical photographs. Paper writing in progress.
- *2026.04*: &nbsp;🎉 Our paper *ReFashionPal* appeared at **CHI EA 2026**!
- *2026.04*: &nbsp;🎉 Our paper *RePairAR* on AI-generated AR reassembly guidance published at **CHI 2026**!
- *2025.10*: &nbsp;🏆 Our UIST 2025 poster received the **Special Recognition for Sustainability in Posters** award!
- *2025.09*: &nbsp; Started as Research Assistant at **HKUST (Guangzhou)**.
- *2025.04*: &nbsp; Joined **Future Lab, Tsinghua University** as AR Development Intern.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI 2026</div><img src='images/chi2026.png' alt="RePairAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AI-Generated AR Reassembly Guidance from Disassembly Videos to Scaffold Everyday Repair](https://doi.org/10.1145/3772318.3790494)

Wenjing Deng, Zhihao Yao, Xinhui Kang, Qirui Sun, Xintong Wu, **Sisi He**, Chenzhuo Xiang, Haipeng Mi

*Proceedings of the ACM CHI Conference on Human Factors in Computing Systems*, 2026

- Built the complete XR system (Unity + AR Foundation) as sole implementer: spatial alignment, step-card display, component highlighting, and in-context video review — without CAD model dependency.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UIST 2025</div><img src='images/uist2025.png' alt="UIST 2025" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AI Extraction of Disassembly Videos for Generating AR Repair Instructions](https://doi.org/10.1145/3746058.3758436)

Wenjing Deng, **Sisi He**, Xintong Wu, Y. Wan, Chenzhuo Xiang, Zhihao Yao, Haipeng Mi

*Adjunct Proceedings of the ACM Symposium on User Interface Software and Technology* (Poster), 2025 &nbsp; 🏆 **Special Recognition for Sustainability in Posters**

- Independently built the AR system; co-designed and implemented the multi-agent AI pipeline; led user study design and data processing.
</div>
</div>

- [ReFashionPal: Exploring AI Assistant Embedded in How-to Videos to Support Garment Repurposing](https://doi.org/10.1145/3772363.3798775), Wenjing Deng, Shuzi Yin, Danqi Huang, **Sisi He**, Haipeng Mi, **CHI EA 2026** \| Independently built the full interaction system, website, and LLM agent pipeline.

# 🎖 Honors and Awards
- *2025.10* &nbsp; 🏆 UIST 2025 **Special Recognition for Sustainability in Posters**
- *2025* &nbsp; National Inspirational Scholarship *(top students nationwide)*
- *2025* &nbsp; 1st Prize, 18th Advanced Robotics & Simulation Competition — National Finals (DF1)
- *2024* &nbsp; National Inspirational Scholarship *(top students nationwide)*
- *2024* &nbsp; 1st Prize, National College Innovation & Entrepreneurship Competition
- *2024* &nbsp; 2nd Prize, National College Student Computer Ability Competition
- *2023* &nbsp; National Invention Patent: *Method and System for Medical Image Electronic Information Processing*
- *2023* &nbsp; 2nd Prize (Provincial), 16th "Challenge Cup"

# 📖 Educations
- *2022.06 - 2026.06*, B.Eng. in Virtual Reality Technology, Nanyang Institute of Technology, China. **Ranked 1st in major** (GPA: 4.1/5.0)

# 💻 Internships
- *2026.02 - Present*, Unity Client Development Intern, [Muyan Zhiyu Technology](https://www.muyan-ai.com/), Beijing. Built real-time LLM conversational interaction framework; designed multi-role dialogue scheduling strategy, improving character consistency by 20%.
- *2025.09 - 2026.02*, Research Assistant, Hong Kong University of Science and Technology (Guangzhou), Guangdong. Led Kinect V2–based motion-sensing XR game development; organized and analyzed user experiments.
- *2025.04 - 2025.09*, AR Development Intern, [Future Lab, Tsinghua University](https://thfl.tsinghua.edu.cn/), Beijing. Solely built complete AR/XR system for AI-driven repair guidance; co-designed multi-agent LLM pipeline. → CHI 2026, UIST 2025
- *2024.05 - 2024.08*, VR Development Intern, Weidu Zhijian Technology, Beijing. Optimized VR interaction logic; built custom shaders; integrated Oculus haptic feedback and Meta Store API.
