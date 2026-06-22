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

Greetings! I'm Jiamian Wang, a final-year Ph.D. candidate at Rochester Institute of Technology (RIT), advised by Dr. [Zhiqiang Tao](https://ztao.cc/index.html) as his first Ph.D. student. I work on **multimodal representation learning and vision-language models** — building systems that model and align visual–textual semantics under uncertainty. My research has appeared at **CVPR (Highlight), ECCV (Oral), NeurIPS, ICCV, and TPAMI**, including state-of-the-art text-video retrieval across five benchmarks. Before RIT, I spent a year at Santa Clara University with Dr. Tao; I received my M.S. from USC (2020) and B.E. from Tianjin University (2018).

A recurring theme across my work is **modeling and exploiting uncertainty to bridge representation gaps**. I began in computational imaging and efficient low-level vision — modeling mask/hardware uncertainty for more interpretable and robust reconstruction ([ECCV Oral](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136790109.pdf); [TPAMI](https://ieeexplore.ieee.org/document/10899382); [NeurIPS](https://openreview.net/pdf?id=zxSWIdyW3A)) and making super-resolution efficient via train-from-scratch pruning ([ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Iterative_Soft_Shrinkage_Learning_for_Efficient_Image_Super-Resolution_ICCV_2023_paper.pdf)). This led me to the vision–language semantics gap: I model text as a stochastic *"mass"* rather than a point to better align text and video ([T-MASS, CVPR Highlight](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_Text_Is_MASS_Modeling_as_Stochastic_Embedding_for_Text-Video_Retrieval_CVPR_2024_paper.pdf)), recast retrieval as diffusion-inspired iterative alignment ([NeurIPS](https://openreview.net/pdf?id=SrQua0ATRZ)) and as LLM chain-of-thought reasoning for explainable ranking ([X-CoT, EMNLP](https://arxiv.org/pdf/2509.21559)), and improve visual instruction through self-questioning ([SQ-LLaVA, ECCV](https://arxiv.org/pdf/2403.11299)). My guiding insight: intelligent systems should *explore, address, and exploit* uncertainty — knowing, acting on, and benefiting from the unknown — for better performance, trustworthiness, and reduced hallucination.

Building on this, my current work extends **alignment toward agency**, along three connected threads (the **3 A's**): **Agent** — turning raw documents into controllable training environments for multimodal search/QA agents ([DocArena](https://drive.google.com/file/d/1HgomrTu4acObIiKn0u01xWaraJVs9JJW/view?usp=sharing), at Adobe Research); **Algorithm** — post-training methods, including preference optimization and Bayesian-grounded approaches, that push environment signals into models efficiently and losslessly ([Visual Self-Refinement, EMNLP](https://arxiv.org/pdf/2510.00993)); and **Autonomy** — post-training VLA models for command-aligned autonomous driving (at NVIDIA). I'm always glad to discuss these directions — and their intersections.

<p class="job-note">I expect to graduate in 2026 and am actively seeking full-time opportunities. Feel free to reach out if there's a potential match!</p>

<p><a class="email-btn" href="mailto:jiamiansc@gmail.com"><i class="fas fa-envelope"></i>&nbsp; Email me</a></p>


## Experience

<div class="cv-exp" markdown="1">

- [**NVIDIA**](https://www.nvidia.com/en-us/industries/automotive/) — *Deep Learning Intern* <span class="cv-meta">Santa Clara, CA · May 2026 – Aug 2026</span>
  - Developing OPD-based solutions for VLA-based autonomous-driving model post-training.
  - I'm currently on-site at NVIDIA HQ in Santa Clara — feel free to reach out if you're interested!

- [**Adobe Research**](https://research.adobe.com/) (Document Intelligence Lab) — *Research Scientist Intern* <span class="cv-meta">San Jose, CA · May 2025 – Mar 2026</span>
  - <span class="cv-mentor">Mentors: [Ruiyi Zhang](https://scholar.google.com/citations?user=-seCWbAAAAAJ&hl=en), [Tong Sun](https://research.adobe.com/person/tong-sun/)</span>
  - Built an agent for multi-turn, multimodal document retrieval and question-answering:
    - an automated, customized, and scalable data-curation pipeline;
    - a complete search-agent training and deployment infrastructure;
    - a search agent built upon the curated data and infrastructure.

- [**Bosch Center for Artificial Intelligence**](https://www.linkedin.com/company/bosch-center-for-artificial-intelligence-bcai/posts/?feedView=all) — *Machine Learning Research Intern* <span class="cv-meta">Pittsburgh, PA · May 2024 – Nov 2024</span>
  - <span class="cv-mentor">Mentors: [Chen Qiu](https://scholar.google.com/citations?user=uX5Y9XUAAAAJ&hl=en), [Chaithanya Kumar Mummadi](https://scholar.google.com/citations?user=XJLtaG4AAAAJ&hl=en)</span>
  - Developed visual autoregressive models for low-level vision, studying error accumulation in next-token prediction and a post-processing solution for better visual quality and coherence.

- [**SenseBrain Technology (SenseTime)**](https://www.sensetime.com/en) — *Research Intern* <span class="cv-meta">San Jose, CA · Jun 2022 – Aug 2022</span>
  - Developed a one-shot over-exposure pixel calibration method compatible with the Sony quad Bayer sensor.

</div>


## News
<div class="news-box" markdown="1">

2026.06: **[IROS'26]** Two papers accepted to IROS 2026: *Latent-Centroid Steering* for command-aligned autonomous driving, and *Visual Autoregressive Modeling Through Online Multi-Scale Preference Optimization* for low-level image perception.

2026.05: I started as a Deep Learning Intern at **NVIDIA**, working on VLA-based autonomous-driving model post-training.

2025.10: I passed my Ph.D. proposal defense!

2025.08: **[EMNLP'25]** Two papers accepted to EMNLP 2025: *Visual Self-Refinement for Autoregressive Models* (Findings) and *X-CoT: Explainable Text-to-Video Retrieval via LLM-based Chain-of-Thought Reasoning* (Main).

2025.05: I joined **Adobe Research** (Document Intelligence Lab) as a Research Scientist Intern, working on agents for multimodal document retrieval and question-answering.

2025.02: **[TPAMI]** *S²-Transformer for Mask-Aware Hyperspectral Image Reconstruction* accepted to IEEE Transactions on Pattern Analysis and Machine Intelligence.

2024.10: **[NeurIPS'24]** I received NeurIPS'24 Travel Award. Thanks to [NeurIPS](https://neurips.cc/) and looking forward to visiting Vancouver!

2024.09: **[NeurIPS'24]** Two papers are accepted by NeurIPS 2024. One is [FedHP](https://arxiv.org/pdf/2306.01176.pdf), in which we developed a federated learning framework to effectively cooperate cross-silo computational imaging systems without breaking the privacy concern. One is about text-video retrieval, where we devised a diffusion-inspired iterative alignment process to solve for the multimodal modality gap and achieves encouraging performance. Code, pretrained models, and the manuscript will be released soon!

2024.09：I will server as a reviewer for AAAI 2025 and ICLR 2025.

2024.07: **[ECCV'24]** Our work of [SQ-LLaVA](https://arxiv.org/abs/2403.11299) has been accepted by ECCV 2024. Congratulations to Guohao!

2024.06: [Poster](https://drive.google.com/file/d/1HNQ9kDYeegRWG_GuXzTubbPCPjEuDPlA/view?usp=sharing), [Video](https://www.youtube.com/watch?v=Uvw1EcdZ_a0), and [Supplementary Material](https://drive.google.com/file/d/1HAjKjVpXvAYasmoeoQtC2MTJn3k22wNW/view?usp=drive_link) has been released, looking forward to present our work in [CVPR2024](https://cvpr.thecvf.com/)!

2024.05: I will serve as a reviewer for NeurIPS 2024.

2024.03: I will join Bosch Research and Technology Center as a research intern, focusing on autoregressive image generation, starting from May 2024.

2024.02: **[CVPR'24]** One paper on multi-modality text-video retrieval is accepted by CVPR 2024 as Highlight (2.8%). Check out the [manuscript](https://arxiv.org/pdf/2403.17998.pdf).

2024.02: I will serve as a reviewer for ECCV 2024.

2023.11: I will serve as a reviewer for CVPR 2024.

2023.08: **[ICCV'23]** Code, including training, testing scripts, and pretrained models have been released. Check out [Iterative-Soft-Shrinkage-SR](https://github.com/Jiamian-Wang/SR_pruning_official) for more details.

2023.07: **[ICCV'23]** One paper on efficient image super-resolution ([Arxiv](https://arxiv.org/pdf/2303.09650.pdf)) is accepted by ICCV 2023. Looking forward to sharing our work in [Paris](https://iccv2023.thecvf.com/paris.convention.center-36700-3-13-7.php).

2023.06: **[Preprint]** Check out our Federated learning method on snapshot compressive imaging, Federated Hardware-Prompt Learning ([FedHP](https://arxiv.org/pdf/2306.01176.pdf)). This is the first attempt of discussing the power of FL in the field of SCI.

2023.03: **[Preprint]** Check out our new pruning method that flexibly handles diverse off-the-shelf SR network architectures without pre-training: [Arxiv](https://arxiv.org/abs/2303.09650). Thanks to my co-authors' great support.

2022.06. **[ECCV'22]** One paper on uncertainty quantification on SCI system is accpeted as an Oral paper by ECCV 2022 (2.7%). Check out the [manuscript](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136790109.pdf) and the [code](https://github.com/Jiamian-Wang/mask_uncertainty_spectral_SCI).

</div>

## Selected Publications and Preprints

For a complete list, please see my <a href="https://scholar.google.com/citations?user=MGSkEscAAAAJ&hl=en">Google Scholar</a>.

<table style="border: none; border-collapse: collapse;">

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/LatentCentroid_framework.png?v=2" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Latent-Centroid Steering: Single-Pass Classifier-Free Guidance for Command-Aligned Autonomous Driving.<br>
    Meibo Hu, <b>Jiamian Wang</b>, Pichao Wang, Zhiqiang Tao.<br>
    <b>IROS</b>, 2026. (Contributed Paper)<br>
    <i>Paper and code coming soon.</i><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/VisualAR_framework.png?v=2" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Visual Autoregressive Modeling Through Online Multi-Scale Preference Optimization for Low-Level Image Perception.<br>
    Ziqi Zhou, <b>Jiamian Wang</b>, Chen Qiu, Chaithanya Kumar Mummadi, Qi Yu, Zhiqiang Tao.<br>
    <b>IROS</b>, 2026. (Contributed Paper)<br>
    <i>Paper and code coming soon.</i><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/DocArena_framework.png?v=2" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    DocArena: Turning Raw Documents into Controllable Training Environments for Document Search Agents.<br>
    <b>Jiamian Wang</b>, Ruiyi Zhang, Tong Yu, Jing Shi, Samyadeep Basu, Rajiv Jain, Zhiqiang Tao, Tong Sun.<br>
    <b>Preprint</b>, 2025.<br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://drive.google.com/file/d/1HgomrTu4acObIiKn0u01xWaraJVs9JJW/view?usp=sharing">PDF</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/VisualSelfRefine_framework.png?v=2" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Visual Self-Refinement for Autoregressive Models.<br>
    <b>Jiamian Wang</b>, Ziqi Zhou, Chaithanya Kumar Mummadi, Sohail Dianat, Majid Rabbani, Raghuveer Rao, Chen Qiu, Zhiqiang Tao.<br>
    <b>EMNLP Findings</b>, 2025.<br>
    <img src="/images/arxiv_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://arxiv.org/pdf/2510.00993">Paper</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/XCoT_framework.png?v=2" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    X-CoT: Explainable Text-to-Video Retrieval via LLM-based Chain-of-Thought Reasoning.<br>
    Prasanna Reddy Pulakurthi, <b>Jiamian Wang</b>, Majid Rabbani, Sohail Dianat, Raghuveer Rao, Zhiqiang Tao.<br>
    <b>EMNLP Main</b>, 2025.<br>
    <img src="/images/arxiv_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://arxiv.org/pdf/2509.21559">Paper</a></span><br>
    <img src="/images/github_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://github.com/prasannapulakurthi/X-CoT">Code</a></span><br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://prasannapulakurthi.github.io/X-CoT/">Demo</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/S2VIT_coverfig.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    S²-Transformer for Mask-Aware Hyperspectral Image Reconstruction.<br>
    <b>Jiamian Wang</b>, Kunpeng Li, Yulun Zhang, Xin Yuan, Zhiqiang Tao.<br>
    <b>IEEE TPAMI</b>, 2025.<br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://ieeexplore.ieee.org/document/10899382">Paper</a></span><br>
    <img src="/images/github_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://github.com/Jiamian-Wang/S2-transformer-HSI">Code</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/DITS_framework.png?v=2" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Diffusion-Inspired Truncated Sampler for Text-Video Retrieval.<br>
    <b>Jiamian Wang</b>, Pichao Wang, Dongfang Liu, Qiang Guan, Sohail Dianat, Majid Rabbani, Raghuveer Rao, Zhiqiang Tao.<br>
    <b>NeurIPS</b>, 2024. <span class="pub-badge pub-badge-award">NeurIPS Scholar Award</span><br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://openreview.net/pdf?id=SrQua0ATRZ">Paper</a></span><br>
    <img src="/images/pdf_icon.jpeg" width="20" height="20" hspace="5">
    <span><a href="https://neurips.cc/media/PosterPDFs/NeurIPS%202024/95072.png?t=1731809505.9690995">Poster</a></span><br>
  </td>
</tr>

<tr style="border-collapse: separate; border-spacing:none;">
  <td style="border-collapse: collapse; border: none;">
    <img src="/images/papers/framework_tmass.png" width="280" />
  </td>
  <td style="border-collapse: collapse; border: none;">
    Text Is MASS: Modeling as Stochastic Embedding for Text-Video Retrieval.<br>
    <b>Jiamian Wang</b>, Guohao Sun, Pichao Wang, Dongfang Liu, Sohail Dianat, Majid Rabbani, Raghuveer Rao, Zhiqiang Tao.<br>
    <b>CVPR</b>, 2024. <span class="pub-badge pub-badge-highlight">Highlight · 2.8%</span><br>
    <img src="/images/arxiv_icon.png" width="20" height="20" hspace="5">
    <span><a href="https://arxiv.org/pdf/2403.17998.pdf">Paper</a></span><br>
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
    <b>ICCV</b>, 2023.<br>
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
    <b>ECCV</b>, 2022. <span class="pub-badge pub-badge-oral">Oral · 2.7%</span><br>
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


## Invited Talks
- *Recent Advances in Text-Video Retrieval* — Twelve Labs, San Francisco, CA <span class="cv-meta">Oct 2024</span>
- *Snapshot-based Hyperspectral Imaging Meets with Deep Learning* — Computer Science and Engineering, Santa Clara University, Santa Clara, CA <span class="cv-meta">Apr 2022</span>

## Honors and Awards
- NeurIPS 2024 Scholar Award (Travel Award), Neural Information Processing Systems Foundation <span class="cv-meta">Oct 2024</span>
- Second Prize Academic Scholarship, Tianjin University <span class="cv-meta">2018</span>

## Professional Services
- **Conference Reviewer:** ICLR (2024–2026), CVPR (2024–2026), NeurIPS (2024–2026), AAAI (2023–2025), ECCV (2024, 2026), ICML (2024–2026), CIKM (2021–2023), ACM SIGKDD (2022–2023).
- **Journal Reviewer:** TPAMI, IJCV, TIP, TNNLS, TMM, TCSVT, Pattern Recognition, TETCI.

## Hobbies
Outside of research, I enjoy swimming and kayaking.

