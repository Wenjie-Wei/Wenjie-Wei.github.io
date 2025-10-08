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

Hello👋! This is Wenjie Wei（卫文杰）. I am currently a Ph.D. student (from fall 2022) in <a href="https://www.scse.uestc.edu.cn/en/" style="text-decoration: none;">the School of Computer Science and Engineering</a> at <a href="https://en.uestc.edu.cn/" style="text-decoration: none;"> the University of Electronic Science and Technology of China</a> (Chengdu, Sichuan). I am supervised by Prof. <a href="https://www.scse.uestc.edu.cn/info/1081/12350.htm" style="text-decoration: none;">Malu Zhang（张马路）</a>. Prior to joining UESTC, I obtained my Bachelor’s degree from <a href="http://international.zzu.edu.cn/" style="text-decoration: none;">Zhengzhou University</a> in 2021.

My research interests broadly encompass Brain-inspired Computing, Spiking Neural Networks, Model Compression, Neuromorphic Vision, etc. I have published more than 20 papers at the top international AI conferences/journals with a total Google Scholar citations <a href='https://scholar.google.com.hk/citations?user=OIZR2YYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

# 💬 Academic Services
- Journal Reviewer: Neural Networks, IEEE TETCI, IEEE TCDS, IEEE TBioCAS, Neurocomputing, Frontiers in Neuroscience, etc.
- Conference Reviewer: NeurIPS, ICLR, ICML, CVPR, AAAI, ĲCAI, etc.
- Invited Oral Presentation titled "Event-Driven Learning for Spiking Neural Networks", at the 11th IEEE International Conference on CIS-RAM Young Scholars Workshop.
- Core Contributor of the WeChat Official Account named "Progress in Brain-Inspired Intelligence", regularly shares the latest developments in the Brain-Inspired Intelligence field.

# 🔥 News
- *2025.09*: &nbsp;🎉🎉 One survey paper about EEG and SNNs is accepted by Neural Networks.
- *2025.09*: &nbsp;🎉🎉 Three papers are accepted by NeurIPS-2025.
- *2025.09*: &nbsp;🎉🎉 One survey paper about Photonic Chips and SNNs is accepted by Nanophotonics.
- *2025.08*: &nbsp;🎉🎉 One paper is accepted by IEEE Trans. Evolutionary Computation.
- *2025.07*: &nbsp;🎉🎉 One paper is accepted by ACMMM-2025.
- *2025.06*: &nbsp;🎉🎉 One paper is accepted by Neural Networks.
- *2025.05*: &nbsp;🎉🎉 One paper is accepted by ICML-2025.
- *2025.04*: &nbsp;🎉🎉 One paper is accepted by IJCAI-2025.
- *2025.02*: &nbsp;🎉🎉 One paper is accepted by CVPR-2025 (Oral, 3.3%).
- *2025.01*: &nbsp;🎉🎉 Two papers are accepted by ICLR-2025.
- *2024.12*: &nbsp;🎉🎉 One paper is accepted by AAAI-2025 (Oral, 4.5%).
- *2024.12*: &nbsp;🎉🎉 Created my own personal homepage.

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

Renjie Li†, Qi Xin†, **Wenjie Wei**, Xiaoli Liu, Sixuan Mao, Erik Ma, Zijian Chen, Malu Zhang, Haizhou Li, Zhaoyu Zhang
- This review surveys emerging photonic hardware optimized for next-generation generative AI computing. 
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2505.05794)

</div>
</div>

## Selected Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/nips25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

S<sup>2</sup>NN: Sub-bit Spiking Neural Networks ![](https://img.shields.io/badge/CCF--A-darkblue)

**Wenjie Wei**, Malu Zhang<sup>&#9993;</sup>, Jieyuan Zhang, Ammar Belatreche, Shuai Wang, Yimeng Shan, Hanwen Liu, Honglin Cao, Guoqing Wang, Yang Yang, Haizhou Li
- This work introduces sub-bit SNNs, which compress synaptic weights to below one bit using outlier-aware sub-bit quantization and membrane potential-based feature distillation, achieving state-of-the-art efficiency and performance for edge computing applications.

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2509.24266)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/iclr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

QP-SNNs: Quantized and Pruned Spiking Neural Networks

**Wenjie Wei**, Malu Zhang<sup>&#9993;</sup>, Zijian Zhou, Ammar Belatreche, Yimeng Shan, Yu Liang, Honglin Cao, Jieyuan Zhang, Yang Yang

- This paper proposes QP-SNN, a lightweight and hardware-friendly model that combines weight rescaling-based quantization with singular value-based pruning for efficient edge deployment.

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=MiPyle6Jef)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/mm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Q-SNNs: Quantized Spiking Neural Networks ![](https://img.shields.io/badge/CCF--A-darkblue)

**Wenjie Wei**, Yu Liang, Ammar Belatreche, Yichen Xiao, Honglin Cao, Zhenbang Ren, Guoqing Wang, Malu Zhang<sup>&#9993;</sup>, Yang Yang

- This paper introduces quantized spiking neural networks with binary weights and low-bit membrane potentials, along with a Weight-Spike Dual Regulation method, to achieve energy efficiency and high performance.

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2406.13672) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)](https://github.com/Wenjie-Wei/Q-SNNs)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/iccv23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Temporal-coded spiking neural networks with dynamic firing threshold: Learning with event-driven backpropagation ![](https://img.shields.io/badge/CCF--A-darkblue)

**Wenjie Wei**, Malu Zhang<sup>&#9993;</sup>, Hong Qu, Ammar Belatreche, Jian Zhang, Hong Chen

- This paper introduces a dynamic firing threshold and direct training algorithm that enable temporal-coded SNNs to achieve high accuracy and energy efficiency.

- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openaccess.thecvf.com/content/ICCV2023/papers/Wei_Temporal-Coded_Spiking_Neural_Networks_with_Dynamic_Firing_Threshold_Learning_with_ICCV_2023_paper.pdf) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)](https://github.com/Wenjie-Wei/DTA-TTFS)
</div>
</div>

## Others
- ![](https://img.shields.io/badge/ACMMM-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/CCF--A-darkblue) Temporal-coded Spiking Transformer.
<br> Qian Sun, Chengzhuo Lu, Wenyu Chen, **Wenjie Wei**<sup>&#9993;</sup>, Jingya Wang, Jieyuan Zhang, Xiaoli Liu, Yalan Ye, Yang Yang, Malu Zhang

- ![](https://img.shields.io/badge/Neural--Networks-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/IF:6.3-darkblue) ESTSformer: Efficient Spatio-Temporal Spiking Transformer.
<br> Chengzhuo Lu, Huilin Du, **Wenjie Wei**<sup>&#9993;</sup>, Qian Sun, Yuchen Wang, Dingyi Zeng, Wenyu Chen, Malu Zhang, Yang Yang

- ![](https://img.shields.io/badge/IEEE--TEVC-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/IF:12-darkblue) Spike-Driven Lightweight Large Language Model With Evolutionary Computation. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ieeexplore.ieee.org/abstract/document/11152565)
<br> Malu Zhang, **Wenjie Wei (Student First Author)**, Zijian Zhou, Wanlong Liu, Jie Zhang, Ammar Belatreche, Yang Yang

- ![](https://img.shields.io/badge/AAAI-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/CCF--A-darkblue) ![](https://img.shields.io/badge/Oral-red) Towards Accurate Binary Spiking Neural Networks: Learning with Adaptive Gradient Modulation Mechanism. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ojs.aaai.org/index.php/AAAI/article/view/32130)
<br> Yu Liang, **Wenjie Wei**, Ammar Belatreche, Honglin Cao, Zijian Zhou, Shuai Wang, Malu Zhang, Yang Yang

- ![](https://img.shields.io/badge/ICML-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/CCF--A-darkblue) BSO: Binary Spiking Online Optimization Algorithm. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=V2bw5SmpF6)
<br> Yu Liang, Yu Yang, **Wenjie Wei**, Ammar Belatreche, Shuai Wang, Malu Zhang, Yang Yang

- ![](https://img.shields.io/badge/IJCAI-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/CCF--A-darkblue) Binary Event-Driven Spiking Transformer. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ojs.aaai.org/index.php/AAAI/article/view/32130)
<br> Honglin Cao†, Zijian Zhou†, **Wenjie Wei**, Ammar Belatreche, Yu Liang, Dehao Zhang, Malu Zhang, Yang Yang, Haizhou Li

- ![](https://img.shields.io/badge/ICLR-green) ![](https://img.shields.io/badge/2025-yellow) Quantized Spike-driven Transformer. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/pdf?id=5J9B7Sb8rO)
<br> Xuerui Qiu†, Malu Zhang, Jieyuan Zhang†, **Wenjie Wei**, Honglin Cao, Junsheng Guo, Rui-Jie Zhu, Yimeng Shan, Yang Yang, Haizhou Li

- ![](https://img.shields.io/badge/CVPR-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/CCF--A-darkblue) ![](https://img.shields.io/badge/Oral-red) Rethinking Spiking Self-Attention Mechanism: Implementing a-XNOR Similarity Calculation in Spiking Transformers. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openaccess.thecvf.com/content/CVPR2025/papers/Xiao_Rethinking_Spiking_Self-Attention_Mechanism_Implementing_a-XNOR_Similarity_Calculation_in_Spiking_CVPR_2025_paper.pdf)
<br> Yichen Xiao†, Shuai Wang†, Dehao Zhang, **Wenjie Wei**, Yimeng Shan, Xiaoli Liu, Yulin Jiang, Malu Zhang

- ![](https://img.shields.io/badge/NeurIPS-green) ![](https://img.shields.io/badge/2024-yellow) ![](https://img.shields.io/badge/CCF--A-darkblue) Spike-based Neuromorphic Model for Sound Source Localization. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://proceedings.neurips.cc/paper_files/paper/2024/file/ce953d71deeb33d9ffa2c879b518d273-Paper-Conference.pdf)
<br> Dehao Zhang†, Shuai Wang†, Ammar Belatreche, **Wenjie Wei**, Yichen Xiao, Haorui Zheng, Zijian Zhou, Malu Zhang, Yang Yang

- ![](https://img.shields.io/badge/IEEE--CIM-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/IF:11.2-darkblue) Towards Energy-Efficient Spike-Based Deep Reinforcement Learning With Temporal Coding. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ieeexplore.ieee.org/abstract/document/10976463)
<br> Malu Zhang, Shuai Wang, Jibin Wu, **Wenjie Wei**, Dehao Zhang, Zijian Zhou, Siying Wang, Fan Zhang, Yang Yang

- ![](https://img.shields.io/badge/ICASSP-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/CCF--B-darkblue) Memory-Free and Parallel Computation for Quantized Spiking Neural Networks. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ieeexplore.ieee.org/abstract/document/10890361)
<br> Dehao Zhang, Shuai Wang, Yichen Xiao, **Wenjie Wei**, Yimeng Shan, Malu Zhang, Yang Yang

- ![](https://img.shields.io/badge/Neural--Networks-green) ![](https://img.shields.io/badge/2025-yellow) ![](https://img.shields.io/badge/IF:6.3-darkblue) Ternary spike-based neuromorphic signal processing system. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://www.sciencedirect.com/science/article/abs/pii/S0893608025002126)
<br> Shuai Wang, Dehao Zhang, Ammar Belatreche, Yichen Xiao, Hongyu Qing, **Wenjie Wei**, Malu Zhang, Yang Yang

- ![](https://img.shields.io/badge/Arxiv-green) ![](https://img.shields.io/badge/2025-yellow) Sdtrack: A baseline for event-based tracking via spiking neural networks. [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2503.08703) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)](https://github.com/YmShan/SDTrack)
<br> Yimeng Shan, Zhenbang Ren, Haodi Wu, **Wenjie Wei**, Rui-Jie Zhu, Shuai Wang, et al.




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
