---
permalink: /
title: 
excerpt: 
author_profile: true
redirect_from: 
  - /main_page/
  - /main_page.html
---

Hi, this is Mengcheng Li. I am a Ph.D. student in the Department of Automation at Tsinghua University, advised by Prof. [Yebin Liu](http://www.liuyebin.com/). My research focuses on hand motion capture, hand 3D reconstruction, hand interaction and motion generation, and hand avatar generation.

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2x2 视频阵列</title>
    <style>
        .video-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            grid-gap: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        
        .video-container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        video {
            width: 100%;
            max-width: 480px;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        
        .caption {
            margin-top: 10px;
            text-align: center;
            font-family: Arial, sans-serif;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="video-grid">
        <!-- 第一行 -->
        <div class="video-container">
            <video autoplay loop muted>
                <source src="files/recon.m4v" type="video/mp4">
            </video>
            <div class="caption">Hand Reconstruction</div>
        </div>
        
        <div class="video-container">
            <video autoplay loop muted>
                <source src="files/intaghand.m4v" type="video/mp4">
            </video>
            <div class="caption">Two Hand Interaction</div>
        </div>
        
        <!-- 第二行 -->
        <div class="video-container">
            <video autoplay loop muted>
                <source src="files/avatar.m4v" type="video/mp4">
            </video>
            <div class="caption">Hand Avatar</div>
        </div>
        
        <div class="video-container">
            <video autoplay loop muted>
                <source src="files/twohand.m4v" type="video/mp4">
            </video>
            <div class="caption">Two Hand Avatar</div>
        </div>
    </div>
</body>

## Education

- Bachelor’s Degree in physics, **Tsinghua University** *(2014-2018)*
- Ph.D student in automation, **Tsinghua University** *(2018-now)*


## Research

<div>
<table style="width:100%;border:none;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;font-size: large">
<tr>
<td style="padding:20px;width:30%;vertical-align:middle;border:none" align="center">
<img width="350" src="../project/HHMR/assets/teaser.png"/>
</td>
<td style="padding:20px;width:70%;vertical-align:middle;border: none" align="left">
<b>HHMR: Holistic Hand Mesh Recovery by Enhancing the Multimodal Controllability of Graph Diffusion Models</b><br>
<b>Mengcheng Li</b>, Hongwen Zhang, Yuxiang Zhang, Ruizhi Shao, Tao Yu, Yebin Liu.<br>
<i>IEEE Conference on Computer Vision and Pattern Recognition (<b>CVPR</b>), 2024 <b><font color='#FF0000'>☆ HighLight Paper</font></b></i><br>
<a href="/project/HHMR/HHMR.html"><i class="fas fa-fw fa-globe"></i>Projectpage</a> /
<a href="/project/HHMR/assets/main.pdf"><i class="fas fa-fw fa-file-pdf"></i>Paper</a> /
<!-- <a><i class="fab fa-fw fa-github fa-github"></i>Code (Coming Soon)</a> -->
</td>
</tr>
</table>
</div>

---

<div>
<table style="width:100%;border:none;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;font-size: large">
<tr>
<td style="padding:20px;width:30%;vertical-align:middle;border:none" align="center">
<img width="350" src="../project/IntagHand/assets/results1.png"/>
</td>
<td style="padding:20px;width:70%;vertical-align:middle;border: none" align="left">
<b>Interacting Attention Graph for Single Image Two-Hand Reconstruction</b><br>
<b>Mengcheng Li</b>, Liang An, Hongwen Zhang, Lianpeng Wu, Feng Chen, Tao Yu, Yebin Liu.<br>
<i>IEEE Conference on Computer Vision and Pattern Recognition (<b>CVPR</b>), 2022 <b><font color='#FF0000'>☆ Oral Paper</font></b></i><br>
<a href="/project/IntagHand/Intaghand.html"><i class="fas fa-fw fa-globe"></i>Projectpage</a> /
<a href="https://arxiv.org/abs/2203.09364.pdf"><i class="fas fa-fw fa-file-pdf"></i>Paper</a> /
<a href="https://github.com/Dw1010/IntagHand"><i class="fab fa-fw fa-github fa-github"></i>Code</a>
</td>
</tr>
</table>
</div>

---

<div>
<table style="width:100%;border:none;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;font-size: large">
<tr>
<td style="padding:20px;width:30%;vertical-align:middle;border:none" align="center">
<img width="350" src="/images/pymaf-x.jpg"/>
</td>
<td style="padding:20px;width:70%;vertical-align:middle;border: none" align="left">
<b>PyMAF-X: Towards Well-aligned Full-body Model Regression from Monocular Images</b><br>
Hongwen Zhang, Yating Tian, Yuxiang Zhang, <b>Mengcheng Li</b>, Liang An, Zhenan Sun, Yebin Liu.<br>
<i>IEEE Transactions on Pattern Analysis and Machine Intelligence (<b>TPAMI</b>), 2023</i><br>
<a href="https://www.liuyebin.com/pymaf-x/"><i class="fas fa-fw fa-globe"></i>Projectpage</a> /
<a href="https://arxiv.org/pdf/2207.06400.pdf"><i class="fas fa-fw fa-file-pdf"></i>Paper</a> /
<a href="https://github.com/HongwenZhang/PyMAF-X"><i class="fab fa-fw fa-github fa-github"></i>Code</a>
</td>
</tr>
</table>
</div>

---

<div>
<table style="width:100%;border:none;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;font-size: large">
<tr>
<td style="padding:20px;width:30%;vertical-align:middle;border:none" align="center">
<img width="350" src="/images/lwtotalcap.jpg"/>
</td>
<td style="padding:20px;width:70%;vertical-align:middle;border: none" align="left">
<b>Light-weight Multi-person Total Capture Using Sparse Multi-view Cameras</b><br>
Yuxiang Zhang，Zhe Li，Tao Yu, <b>Mengcheng Li</b>, Liang An, Yebin Liu.<br>
<i>IEEE Conference on International Conference on Computer Vision (<b>ICCV</b>), 2021</i><br>
<a href="https://www.liuyebin.com/lwtotalcap/lwtotalcap.html"><i class="fas fa-fw fa-globe"></i>Projectpage</a> /
<a href="https://www.liuyebin.com/lwtotalcap/assets/main.pdf"><i class="fas fa-fw fa-file-pdf"></i>Paper</a>
</td>
</tr>
</table>
</div>

---

<div>
<table style="width:100%;border:none;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;font-size: large">
<tr>
<td style="padding:20px;width:30%;vertical-align:middle;border:none" align="center">
<img width="350" src="/images/CHOI.jpg"/>
</td>
<td style="padding:20px;width:70%;vertical-align:middle;border: none" align="left">
<b>Learning Explicit Contact for Implicit Reconstruction of Hand-held Objects from Monocular Images</b><br>
Junxing Hu, Hongwen Zhang, Zerui Chen, <b>Mengcheng Li</b>, Yunlong Wang, Yebin Liu, Zhenan Sun.<br>
<i>AAAI Conference on Artificial Intelligence (<b>AAAI</b>), 2024</i><br>
<a href="https://junxinghu.github.io/projects/hoi.html"><i class="fas fa-fw fa-globe"></i>Projectpage</a> /
<a href="https://ojs.aaai.org/index.php/AAAI/article/view/27995"><i class="fas fa-fw fa-file-pdf"></i>Paper</a> /
<a href="https://github.com/JunxingHu/CHOI"><i class="fab fa-fw fa-github fa-github"></i>Code</a>
</td>
</tr>
</table>
</div>

---
