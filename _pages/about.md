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

Hello! This is Wenjie Wei. I am currently a Research Fellow at the National University of Singapore, working with Prof. Haizhou Li. I received my Ph.D. from the University of Electronic Science and Technology of China in June 2026, under the supervision of Prof. Malu Zhang. Prior to this, I obtained my Bachelor’s degree from Zhengzhou University in 2021. 

My research interests include software-hardware co-design, brain-inspired computing, spiking neural networks, and speech intelligence.
- 📔 Software-hardware co-design: model compression, binary neural networks, quantization, pruning, etc.
- 📔 Neuromorphic computing: spiking neural networks, event-driven learning, etc.
- 📔 Speech intelligence: speech processing, and efficient speech models, etc.

Contact: wjwei@nus.edu.sg. Please feel free to reach out to me.

# 💬 Academic Services
- Journal Reviewer: Expert Systems With Applications, Neural Networks, IEEE TETCI, IEEE TCDS, IEEE TBioCAS, Neurocomputing, Frontiers in Neuroscience, etc.
- Conference Reviewer: NeurIPS, ICLR, ICML, CVPR, AAAI, ĲCAI, etc.
- Invited Oral Presentation titled "Event-Driven Learning for Spiking Neural Networks", at the 11th IEEE International Conference on CIS-RAM Young Scholars Workshop.
- Core Contributor of the WeChat Official Account named "Progress in Brain-Inspired Intelligence", regularly shares the latest developments in the Brain-Inspired Intelligence field.
  
# 🔥 News

<div style="max-height: 300px; overflow-y: auto; padding-right: 10px; line-height: 1.53;">

<ul style="margin-top: 0; padding-left: 20px;">
  <li style="margin-bottom: 3px;"><em>2026.04</em>: 🎉🎉 Joined NUS as a Research Fellow.</li>
  <li style="margin-bottom: 3px;"><em>2026.04</em>: 🎉🎉 Passed my Ph.D. dissertation defense with all excellent evaluations.</li>
  <li style="margin-bottom: 3px;"><em>2026.05</em>: 🎉🎉 Four papers are accepted by ICML-2026.</li>
  <li style="margin-bottom: 3px;"><em>2026.04</em>: 🎉🎉 One paper is accepted by SCIENCE CHINA Information Sciences.</li>
  <li style="margin-bottom: 3px;"><em>2026.03</em>: 🎉🎉 Submitted my Ph.D. dissertation.</li> 
  <li style="margin-bottom: 3px;"><em>2026.02</em>: 🎉🎉 One paper is accepted by CVPR-2026.</li>
  <li style="margin-bottom: 3px;"><em>2026.01</em>: 🎉🎉 One paper is accepted by ICLR-2026.</li>
  <li style="margin-bottom: 3px;"><em>2026.01</em>: 🎉🎉 Two papers are accepted by ICASSP-2026.</li>
  <li style="margin-bottom: 3px;"><em>2025.11</em>: 🎉🎉 Two papers are accepted by AAAI-2026.</li>
  <li style="margin-bottom: 3px;"><em>2025.09</em>: 🎉🎉 One survey paper about EEG and SNNs is accepted by Neural Networks.</li>
  <li style="margin-bottom: 3px;"><em>2025.09</em>: 🎉🎉 Three papers are accepted by NeurIPS-2025.</li>
  <li style="margin-bottom: 3px;"><em>2025.09</em>: 🎉🎉 One survey paper about photonic chips and SNNs is accepted by Nanophotonics.</li>
  <li style="margin-bottom: 3px;"><em>2025.08</em>: 🎉🎉 One paper is accepted by IEEE Transactions on Evolutionary Computation.</li>
  <li style="margin-bottom: 3px;"><em>2025.07</em>: 🎉🎉 One paper is accepted by ACM MM-2025.</li>
  <li style="margin-bottom: 3px;"><em>2025.06</em>: 🎉🎉 One paper is accepted by Neural Networks.</li>
  <li style="margin-bottom: 3px;"><em>2025.05</em>: 🎉🎉 One paper is accepted by ICML-2025.</li>
  <li style="margin-bottom: 3px;"><em>2025.04</em>: 🎉🎉 One paper is accepted by IJCAI-2025.</li>
  <li style="margin-bottom: 3px;"><em>2025.02</em>: 🎉🎉 One paper is accepted by CVPR-2025.</li>
  <li style="margin-bottom: 3px;"><em>2025.01</em>: 🎉🎉 Two papers are accepted by ICLR-2025.</li>
  <li style="margin-bottom: 3px;"><em>2024.12</em>: 🎉🎉 One paper is accepted by AAAI-2025.</li>
  <li style="margin-bottom: 3px;"><em>2024.12</em>: 🎉🎉 Created my personal homepage.</li>
</ul>
</div>

# 📝 Publications
## Survey Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='images/eeg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Spiking Neural Networks for EEG Signal Analysis: From Theory to Practice ![](https://img.shields.io/badge/IF:6.3-darkblue)

Siqi Cai, Zheyuan Lin, Xiaoli Liu, **Wenjie Wei**<sup>&#9993;</sup>, Shuai Wang, Malu Zhang, Tanja Schultz, Haizhou Li
- The review encompasses foundational knowledge of SNNs, detailed implementation strategies for EEG analysis, and challenges inherent to SNN-based methods.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://www.sciencedirect.com/science/article/pii/S089360802501007X) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)](https://github.com/i-spoon/EEG-Spiking-Network)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nanophotonics</div><img src='images/nano.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

What Is Next for LLMs? Next-Generation AI Computing Hardware Using Photonic Chips ![](https://img.shields.io/badge/IF:6.6-darkblue)

Renjie Li, Qi Xin, **Wenjie Wei**, Xiaoli Liu, Sixuan Mao, Erik Ma, Zijian Chen, Malu Zhang, Haizhou Li<sup>&#9993;</sup>, Zhaoyu Zhang<sup>&#9993;</sup>
- This review surveys emerging photonic hardware optimized for next-generation generative AI computing. 
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://www.degruyterbrill.com/document/doi/10.1515/nanoph-2025-0217/html)

</div>
</div>

## Selected Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SCIENCE CHINA Information Sciences</div><img src='images/scis26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Event-driven learning for spiking neural networks ![](https://img.shields.io/badge/CCF--A-darkblue)

**Wenjie Wei**, Malu Zhang<sup>&#9993;</sup>, Jilin Zhang, Ammar Belatreche, Jibin Wu, Zijing Xu, Xuerui Qiu, Hong Chen, Yang Yang, Haizhou Li

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)]([https://openreview.net/pdf?id=L5llQD0nMf](https://arxiv.org/pdf/2403.00270))
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/iclr26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

TP-Spikformer: Token Pruned Spiking Transformer ![](https://img.shields.io/badge/CCF--A-darkblue)

**Wenjie Wei**, Xiaolong Zhou, Malu Zhang<sup>&#9993;</sup>, Ammar Belatreche, Qian Sun, Yimeng Shan, Dehao Zhang, Zijian Zhou, Zeyu Ma, Yang Yang, Haizhou Li

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=L5llQD0nMf) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)]([https://github.com/Wenjie-Wei/QP-SNN](https://github.com/xlzhou126/TP-Spikformer))
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/nips25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

S<sup>2</sup>NN: Sub-bit Spiking Neural Networks ![](https://img.shields.io/badge/CCF--A-darkblue)

**Wenjie Wei**, Malu Zhang<sup>&#9993;</sup>, Jieyuan Zhang, Ammar Belatreche, Shuai Wang, Yimeng Shan, Hanwen Liu, Honglin Cao, Guoqing Wang, Yang Yang, Haizhou Li

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2509.24266)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/iclr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

QP-SNNs: Quantized and Pruned Spiking Neural Networks ![](https://img.shields.io/badge/CCF--A-darkblue)

**Wenjie Wei**, Malu Zhang<sup>&#9993;</sup>, Zijian Zhou, Ammar Belatreche, Yimeng Shan, Yu Liang, Honglin Cao, Jieyuan Zhang, Yang Yang

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=MiPyle6Jef) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)](https://github.com/Wenjie-Wei/QP-SNN)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/mm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Q-SNNs: Quantized Spiking Neural Networks ![](https://img.shields.io/badge/CCF--A-darkblue)

**Wenjie Wei**, Yu Liang, Ammar Belatreche, Yichen Xiao, Honglin Cao, Zhenbang Ren, Guoqing Wang, Malu Zhang<sup>&#9993;</sup>, Yang Yang

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2406.13672) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)](https://github.com/Wenjie-Wei/Q-SNNs)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/iccv23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Temporal-coded spiking neural networks with dynamic firing threshold: Learning with event-driven backpropagation ![](https://img.shields.io/badge/CCF--A-darkblue)

**Wenjie Wei**, Malu Zhang<sup>&#9993;</sup>, Hong Qu, Ammar Belatreche, Jian Zhang, Hong Chen

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openaccess.thecvf.com/content/ICCV2023/papers/Wei_Temporal-Coded_Spiking_Neural_Networks_with_Dynamic_Firing_Threshold_Learning_with_ICCV_2023_paper.pdf) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)](https://github.com/Wenjie-Wei/DTA-TTFS)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/icml26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SmoothSpike: Spiking Transformer with Learnable Hadamard Transformation ![](https://img.shields.io/badge/CCF--A Spotlight-darkblue)

Zijian Zhou, **Wenjie Wei**<sup>&#9993;</sup>, Yu Liang, Jialin Li, Ammar Belatreche, Honglin Cao, Shuai Wang, Malu Zhang, Yang Yang, Haizhou Li

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=UoUKCLHjRa) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)](https://github.com/CayleyZ/SmoothSpike)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/mm25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Temporal-coded Spiking Transformer. ![](https://img.shields.io/badge/CCF--A-darkblue)
  
Qian Sun, Chengzhuo Lu, Wenyu Chen, **Wenjie Wei**<sup>&#9993;</sup>, Jingya Wang, Jieyuan Zhang, Xiaoli Liu, Yalan Ye, Yang Yang, Malu Zhang
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://dl.acm.org/doi/pdf/10.1145/3746027.3754545)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural--Networks</div><img src='images/nn25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
ESTSformer: Efficient Spatio-Temporal Spiking Transformer. ![](https://img.shields.io/badge/IF:6.3-darkblue)
  
Chengzhuo Lu, Huilin Du, **Wenjie Wei**<sup>&#9993;</sup>, Qian Sun, Yuchen Wang, Dingyi Zeng, Wenyu Chen, Malu Zhang, Yang Yang
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://www.sciencedirect.com/science/article/abs/pii/S0893608025006665)
</div>
</div>




# 🏆 Honors and Awards
- 2025.08: Best Dataset & Benchmark Award, ĲCAI2025-SpikeCV Competition: Infinity-WUJI. (Only 1 Team Worldwide)
- 2022.11: Outstanding Student Leader, University of Electronic Science and Technology of China.
- 2021.09: First-Class Scholarship, University of Electronic Science and Technology of China. 
- 2021.06: Outstanding Graduate, Zhengzhou University.
- 2019, 2020.11: National Encouragement Scholarship, Zhengzhou University.
- 2018.11: Outstanding Contributor in Social Service, Zhengzhou University.

# 📖 Educations
- 2022.09 - 2026.06, Ph.D. Candidate in School of Computer Science and Engineering, University of Electronic Science and Technology of China. (Supervisor: Malu Zhang)
- 2021.09 - 2022.06, M.S. in School of Computer Science and Engineering, University of Electronic Science and Technology of China.
- 2017.09 - 2021.06, B.S. in School of Information Engineering, Zhengzhou University.
