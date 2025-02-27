---
permalink: /
title: ""
excerpt: "About me"
layout: single
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
## About Me


Greetings! I'm Jiamian Wang, a student at Golisano College of Computing and Information Sciences, Rochester Institute of Technology, under the guidance of Dr. [Zhiqiang Tao](https://ztao.cc/index.html). Prior to joining RIT, I spent one year in the Department of Computer Science and Engineering at Santa Clara University (San Jose, USA) with Dr.Tao. I received my M.S. degree from University of Southern California (Los Angeles, USA) in 2020 and B.E. degree from Tianjin University (Tianjin, China) in 2018.

My research primarily revolves around low-level vision tasks, such as image super-resolution. I am engaged in enhancing the trustworthiness, robustness, and performance of snapshot compressive imaging systems (SCI). My recent work delves into harnessing the power of diffusion models for both low-level vision tasks and high-level multi-modal retrieval task.



## News
2024.10: **[NeurIPS'24]** I received NeurIPS'24 Travel Award. Thanks to [NeurIPS](https://neurips.cc/) and looking forward to visiting Vancouver!

2024.09: **[NeurIPS'24]** Two papers are accepted by NeurIPS 2024. One is [FedHP](https://arxiv.org/pdf/2306.01176.pdf), in which we developed a federated learning framework to effectively cooperate cross-silo computational imaging systems without breaking the privacy concern. One is about text-video retrieval, where we devised a diffusion-inspired iterative alignment process to solve for the multimodal modality gap and achieves encouraging performance. Code, pretrained models, and the manuscript will be released soon!

2024.09：I will server as a reviewer for AAAI 2025 and ICLR 2025.

2024.07: **[ECCV'24]** Our work of [SQ-LLaVA](https://arxiv.org/abs/2403.11299) has been accepted by ECCV 2024. Congratulations to Guohao!

2024.06: [Poster](https://drive.google.com/file/d/1HNQ9kDYeegRWG_GuXzTubbPCPjEuDPlA/view?usp=sharing), [Video](https://www.youtube.com/watch?v=Uvw1EcdZ_a0), and [Supplementary Material](https://drive.google.com/file/d/1HAjKjVpXvAYasmoeoQtC2MTJn3k22wNW/view?usp=drive_link) has been released, looking forward to present our work in [CVPR2024](https://cvpr.thecvf.com/)!

2024.05: I will serve as a reviewer for NeurIPS 2024.

2024.03: I will join Bosch Research and Technology Center as a research intern, focusing on autoregressive image generation, starting from May 2024.

2024.02: **[CVPR'24]** One paper on multi-modality text-video retrieval is accepted by CVPR 2024 as Highlight (11.9%). Check out the [manuscript](https://arxiv.org/pdf/2403.17998.pdf) and the [code](https://github.com/Jiamian-Wang/T-MASS-text-video-retrieval).

2024.02: I will serve as a reviewer for ECCV 2024.

2023.11: I will serve as a reviewer for CVPR 2024.

2023.08: **[ICCV'23]** Code, including training, testing scripts, and pretrained models have been released. Check out [Iterative-Soft-Shrinkage-SR](https://github.com/Jiamian-Wang/SR_pruning_official) for more details.

2023.07: **[ICCV'23]** One paper on efficient image super-resolution ([Arxiv](https://arxiv.org/pdf/2303.09650.pdf)) is accepted by ICCV 2023. Looking forward to sharing our work in [Paris](https://iccv2023.thecvf.com/paris.convention.center-36700-3-13-7.php).

2023.06: **[Preprint]** Check out our Federated learning method on snapshot compressive imaging, Federated Hardware-Prompt Learning ([FedHP](https://arxiv.org/pdf/2306.01176.pdf)). This is the first attempt of discussing the power of FL in the field of SCI.

2023.03: **[Preprint]** Check out our new pruning method that flexibly handles diverse off-the-shelf SR network architectures without pre-training: [Arxiv](https://arxiv.org/abs/2303.09650). Thanks to my co-authors' great support.

2022.06. **[ECCV'22]** One paper on uncertainty quantification on SCI system is accpeted as an Oral paper by ECCV 2022 (2.7%). Check out the [manuscript](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136790109.pdf) and the [code](https://github.com/Jiamian-Wang/mask_uncertainty_spectral_SCI).

## Selected Publications and Preprints

<table style="border: none; border-collapse: collapse;">

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/framework_tmass.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Text Is MASS: Modeling as Stochastic Embedding for Text-Video Retrieval.<br>
    <b>Jiamian Wang</b>, Guohao Sun, Pichao Wang, Dongfang Liu, Sohail Dianat, Majid Rabbani, Raghuveer Rao, Zhiqiang Tao.<br>
    <b>CVPR Highlight (11.9%)</b>, 2024.<br>
    <img src="/images/arxiv_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://arxiv.org/pdf/2403.17998.pdf">Paper</a></span><br>
    <img src="/images/github_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://github.com/Jiamian-Wang/T-MASS-text-video-retrieval">Code</a></span><br>
    <img src="/images/youtube_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://www.youtube.com/watch?v=Uvw1EcdZ_a0">Video</a></span><br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://drive.google.com/file/d/1HAjKjVpXvAYasmoeoQtC2MTJn3k22wNW/view?usp=drive_link">Supply</a></span><br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://drive.google.com/file/d/1HNQ9kDYeegRWG_GuXzTubbPCPjEuDPlA/view?usp=sharing ">Poster</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/framework_SQLLaVA.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    SQ-LLaVA: Self-Questioning for Large Vision-Language Assistant.<br>
    Guohao Sun, Can Qin, <b>Jiamian Wang</b>, Zeyuan Chen, Ran Xu, Zhiqiang Tao.<br>
    <b>ECCV</b>, 2024.<br>
    <img src="/images/arxiv_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://arxiv.org/pdf/2403.11299.pdf">Arxiv</a></span><br>
    <img src="/images/github_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://github.com/heliossun/SQ-LLaVA">Code</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/FedHP_framework.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Cooperative Hardware-Prompt Learning for Snapshot Compressive Imaging.<br>
    <b>Jiamian Wang</b>, Zongliang Wu, Yulun Zhang, Xin Yuan, Tao Lin, Zhiqiang Tao.<br>
    <b>NeurIPS</b>, 2024.<br>
    <img src="/images/arxiv_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://arxiv.org/pdf/2306.01176.pdf">Arxiv</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/ISSP_framework.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Iterative Soft Shrinkage Learning for Efficient Image Super-Resolution.<br>
    <b>Jiamian Wang</b>, Huan Wang, Yulun Zhang, Yun Fu, Zhiqiang Tao.<br>
    <b>ICCV Poster (26.15%)</b>, 2023.<br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://arxiv.org/pdf/2303.09650.pdf">Paper</a></span><br>
    <img src="/images/github_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://github.com/Jiamian-Wang/IST_for_SR_pruning">Code</a></span><br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://drive.google.com/file/d/1GT5d5nq3pJWJe80bB6Wpv1O1miZ9_aYM/view?usp=sharing ">Supply</a></span><br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://drive.google.com/file/d/1DCThVAF_80tqxezh-yeeG0oI-_01Lh9q/view?usp=sharing">Poster</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/ECCV2022_framework_v2.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Modeling Mask Uncertainty in Hyperspectral Image Reconstruction.<br>
    <b>Jiamian Wang</b>, Yulun Zhang, Xin Yuan, Ziyi Meng, Zhiqiang Tao.<br>
    <b>ECCV Oral (2.7%)</b>, 2022.<br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136790109.pdf">Paper (Supply)</a></span><br>
    <img src="/images/github_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://github.com/Jiamian-Wang/mask_uncertainty_spectral_SCI">Code</a></span><br>
    <img src="/images/youtube_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://www.youtube.com/watch?v=vzGV-trPqnI">Video</a></span><br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://drive.google.com/file/d/189WgQREvUIWGpK6p0VKaXY1eV1bB3B3I/view?usp=sharing">Poster</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/CIKM2022_framework.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Calibrate Automated Graph Neural Network via Hyperparameter Uncertainty.<br>
    Xueying Yang, <b>Jiamian Wang</b>, Sheng Li, Zhiqiang Tao.<br>
    <b>CIKM</b>, 2022.<br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://zxj32.github.io/data/CIKM_2022.pdf">Paper</a></span><br>
    <img src="/images/github_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://github.com/xyang2316/HyperU-GCN">Code</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/S2VIT_coverfig.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    S2-Transformer for Mask-Aware Hyperspectral Image Reconstruction.<br>
    <b>Jiamian Wang</b>, Kunpeng Li, Yulun Zhang, Xin Yuan, Zhiqiang Tao.<br>
    <b>Arxiv</b>, 2022.<br>
    <img src="/images/arxiv_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://arxiv.org/pdf/2209.12075.pdf">Arxiv</a></span><br>
    <img src="/images/github_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://github.com/Jiamian-Wang/S2-transformer-HSI">Code</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/HSIbaseline_framework.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    A new backbone for hyperspectral image reconstruction.<br>
    <b>Jiamian Wang</b>, Yulun Zhang, Xin Yuan, Yun Fu, Zhiqiang Tao.<br>
    <b>Arxiv</b>, 2022.<br>
    <img src="/images/arxiv_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://arxiv.org/pdf/2108.07739.pdf">Arxiv</a></span><br>
    <img src="/images/github_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://github.com/Jiamian-Wang/HSI_baseline">Code</a></span><br>
  </td>
</tr>

</table>


## Professional Services
- Journal Reviewer: TPAMI, PR, JSTSP, IJCV, TIP, TNNLS, TETCI, Neurocomputing.
- Conference Reviewer: NIPS2024, CVPR2024, ECCV2024, ICML2024, CIKM 2021-2023, ACM SIGKDD 2022-2023.

