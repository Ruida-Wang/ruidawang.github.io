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

I’m a Research Associate at Institute of Information Engineering, Chinese Academy of Sciences (IIE, CAS).

My research focuses on Cryptography, with a particular emphasis on the theory, implementation and application of Fully Homomorphic Encryption **(FHE)**.

You can find my publications and citation statistics on my  
<a href='https://scholar.google.com/citations?user=hpoTTfgAAAAJ'>Google Scholar profile</a>, and view the current citation count via this badge:  
<a href='https://scholar.google.com/citations?user=hpoTTfgAAAAJ'>
  <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>

---
- My research focuses on Cryptography, with a particular emphasis on the theory, implementation and application of Fully Homomorphic Encryption (FHE).
- I obtained my PhD degree in cybersecurity at IIE, CAS. 
- Before coming to IIE, I obtained my Bachelor’s degree in Mathematics and Applied Mathematics at Taishan College, Shandong University.



# 🔥 News

---

# 📝 Selected Publications

<!-- Tetris -->
<div class='paper-box'>
  <!-- 有配图时可启用 -->
  <!--
  <div class='paper-box-image'>
    <div>
      <div class="badge">ePrint 2025</div>
      <img src='images/500x300.png' alt="Tetris" width="100%">
    </div>
  </div>
  -->
  <div class='paper-box-text' markdown="1">

**Tetris: Versatile TFHE LUT and Its Application to FHE Instruction Set Architecture**  
*Ruida Wang, **Jikang Bai**, Xuan Shen, Xianhui Lu, Zhihao Li, Binwu Xiang, Zhiwei Wang, Hongyu Wang, Lutan Zhao, Kunpeng Wang*  

[**Paper (IACR ePrint 2025/1623)**](https://eprint.iacr.org/2025/1623)  
<span class='show_paper_citations' data='TODO_REPLACE_TETRIS_ID'></span>  

**Circuit Bootstrapping: Faster and Smaller** 
* **Ruida Wang**, Yundi Wen, Zhihao Li, Xianhui Lu*, Benqiang Wei, Kun Liu, Kunpeng Wang*
[**Annual International Conference on the Theory and Applications of Cryptographic Techniques (EUROCRYPT) • 2024**](
https://link.springer.com/chapter/10.1007/978-3-031-58751-1_1)<span class='show_paper_citations' data='WbkHhVStYXYC'></span>  

[2] Refined TFHE Leveled Homomorphic Evaluation and Its Application
Ruida Wang, Jincheol Ha (co-first author), Xuan Shen, Xianhui Lu*, Chunling Chen, Kunpeng Wang, Jooyoung Lee*
ACM SIGSAC Conference on Computer and Communications Security (CCS) • 2025
https://dl.acm.org/doi/10.1145/3702112.3710189
[3] Phalanx: An FHE-Friendly SNARK for Verifiable Computation on Encrypted Data
Xinxuan Zhang, Ruida Wang*, Zeyu Liu, Binwu Xiang, Yi Deng*, Xianhui Lu*
ACM SIGSAC Conference on Computer and Communications Security (CCS) • 2025
https://dl.acm.org/doi/10.1145/3719027.3765226


# 🎖 Honors and Awards

---

# 📖 Educations

- I obtained my PhD degree in cybersecurity at IIE, CAS. 
- Before coming to IIE, I obtained my Bachelor’s degree in Mathematics and Applied Mathematics at Taishan College, Shandong University.

# 🧪 Research Keywords

**Fully Homomorphic Encryption (FHE)** · **TFHE / FHEW** · **Programmable Bootstrapping** · **Homomorphic LUTs** ·  
**FHE Instruction Set Architecture (FHE-ISA)** · **Bootstrapping over Algebraic Structures** ·  
