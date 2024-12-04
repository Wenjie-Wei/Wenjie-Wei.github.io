---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
## Biography
Hello👋! This is Wenjie Wei🙎‍♀️. I am currently pursuing🏃‍♀️ a Ph.D. in [the University of Electronic Science and Technology of China](https://en.uestc.edu.cn/)🏫, under the supervision of Prof. [Malu Zhang](https://sites.google.com/view/malu-zhang/home)🧑‍🏫. Prior to this, I obtained my Bachelor’s degree👩‍🎓 from [Zhengzhou University](http://international.zzu.edu.cn/)🏫 in 2021. My research interests broadly include 🧠neuromorphic computing💻 and 🤏efficient deep learning🤖.

## Research Interests
- 📘 Neuromorphic Computing: Spiking Neural Networks, Brain-inspired Neural Architecture Design, etc.
- 📘 Efficient Deep Learning: Network Binarization, Quantization, Pruning, etc.

## Publications
- Temporal-coded spiking neural networks with dynamic firing threshold: Learning with event-driven backpropagation. ICCV 2023. [paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Wei_Temporal-Coded_Spiking_Neural_Networks_with_Dynamic_Firing_Threshold_Learning_with_ICCV_2023_paper.pdf)<br><font color=red>Wenjie Wei</font>, Malu Zhang*, Hong Qu, Ammar Belatreche, Jian Zhang, Hong Chen


## Academic Services
- Reviewer for conferences and journals, including ICLR2025, Neural Networks, IEEE TETCI, etc.
- Invited speaker at the IEEE CIS-RAM 2024 Young Scholars Workshop on "*Event-Driven Learning for Spiking Neural Networks*". [Poster](#image)
<div id="image-container" style="display:none;">
    <div id="image-overlay" onclick="closeImage()"></div>
    <div id="image-content">
        <img src="../images/CIS-RAM.png" alt="CIS Image" />
        <button id="close-btn" onclick="closeImage()">×</button>
    </div>
</div>

<script>
    // 显示图片
    document.querySelector('a[href="#image"]').addEventListener('click', function(e) {
        e.preventDefault();
        document.getElementById('image-container').style.display = 'block';
    });

    // 关闭图片
    function closeImage() {
        document.getElementById('image-container').style.display = 'none';
    }
</script>

<style>
    #image-container {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.8);
        display: none;
        justify-content: center;
        align-items: center;
        z-index: 1000;
    }
    
    #image-overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.5);
    }

    #image-content {
        position: relative;
        max-width: 90%;
        max-height: 90%;
    }

    #image-content img {
        max-width: 100%;
        max-height: 100%;
        display: block;
        margin: 0 auto;
    }

    #close-btn {
        position: absolute;
        top: 10px;
        right: 10px;
        background: transparent;
        border: none;
        font-size: 30px;
        color: white;
        cursor: pointer;
    }

    #close-btn:hover {
        color: red;
    }
</style>
