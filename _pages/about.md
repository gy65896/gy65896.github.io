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
<div style="text-align: justify;">
Yu Guo is currently a Research Assistant at    <a href="https://jcstemlab.netlify.app/"><strong>WINET lab</strong></a>, City University of Hong Kong.    He is pursuing his Ph.D. degree in Traffic Information Engineering and Control at Wuhan University of Technology.    From 2023 to 2024, he completed one significant visiting research period at    <a href="http://www.shengfenghe.com/"><strong>VUG lab</strong></a>, Singapore Management University.    He received his B.Sc. degree in Naval Architecture and Ocean Engineering from the Wuhan University of Technology, in 2021.   <br><br>   His research interests include Computer Vision and Intelligent Transportation.    He has published over 30 papers at the top international conferences and journals    (<a href='https://scholar.google.com/citations?user=klYz-acAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url\_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>)  such as ECCV, T-ITS, TII. He has also served as a reviewer of multiple conferences and journals,    including ICLR, TII, TCSVT, and TVT.   <br><br><strong>I am actively seeking like-minded collaborators.</strong>    If you are interested in my work, please feel free to contact me via email:    guoyu65896@gmail.com or add me on <a href="images/Wechat.jpg">WeChat</a>.
</div>

# 🔥 News

- **2024.07**: &nbsp;🎉 Two papers have been accepted by **<a href="https://eccv.ecva.net/">ECCV 2024</a>**.
- **2024.04**: &nbsp;🎉 The constructed **[FVessel dataset](https://github.com/gy65896/FVessel)** is included in the **[CVonline: Image Databases](https://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm)** at the University of Edinburgh.

# 📝 Publications

<p style="text-align: left; font-weight: bold; font-size: 1.2em; margin-bottom: -0.5em;">Representative Works</p>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='papers/ECCV2024_OneRestore/abstract.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OneRestore: A Universal Restoration Framework for Composite Degradation](https://arxiv.org/abs/2407.04621)

<strong>Yu Guo</strong><sup>†</sup>, Yuan Gao<sup>†</sup>, Yuxu Lu, Huilin Zhu, Ryan Wen Liu<sup>*</sup>, Shengfeng He<sup>*</sup>

[**Project**](https://gy65896.github.io/projects/ECCV2024_OneRestore/index.html) <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:pyW8ca7W8N0C'></span></strong>

<a href="https://arxiv.org/abs/2407.04621" target="_blank">Paper</a> |  <a href="https://www.youtube.com/embed/AFr5tZdPlZ4">Video</a> |  <a href="https://gy65896.github.io/papers/ECCV2024_OneRestore/OneRestore_poster.png">Poster</a> | <a href="https://onedrive.live.com/?id=CBB69E4E3408EBCD%2138238&resid=CBB69E4E3408EBCD%2138238&ithint=folder&authkey=%21AMxuLGqPrvXXQ4c&cid=cbb69e4e3408ebcd" target="_blank">Dataset</a> |
<a href="https://github.com/gy65896/OneRestore" target="_blank">Code</a> <img src="https://img.shields.io/github/stars/gy65896/OneRestore?label=%F0%9F%8C%9F%20Star&color=blue"> <img src="https://img.shields.io/github/forks/gy65896/OneRestore?label=%F0%9F%94%A7%20Fork&color=green">

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-ITS 2023</div><img src='papers/TITS2023_DeepSORVF/method.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Asynchronous Trajectory Matching-based Multimodal Maritime Data Fusion for Vessel Traffic Surveillance in Inland Waterways](https://arxiv.org/abs/2407.04621)

<strong>Yu Guo</strong>, Ryan Wen Liu<sup>*</sup>, Jingxiang Qu, Yuxu Lu, Fenghua Zhu<sup>*</sup>, Yisheng Lv

[**Project**](https://gy65896.github.io/projects/TITS2023_DeepSORVF/index.html) <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:70eg2SAEIzsC'></span></strong>

<a href="https://ieeexplore.ieee.org/document/10159572" target="_blank">Paper</a> | <a href="https://github.com/gy65896/DeepSORVF" target="_blank">Code</a> <img src="https://img.shields.io/github/stars/gy65896/DeepSORVF?label=%F0%9F%8C%9F%20Star&color=blue"> <img src="https://img.shields.io/github/forks/gy65896/DeepSORVF?label=%F0%9F%94%A7%20Fork&color=green"> | <a href="https://github.com/gy65896/FVessel" target="_blank">Dataset</a> <img src="https://img.shields.io/github/stars/gy65896/FVessel?label=%F0%9F%8C%9F%20Star&color=blue"> <img src="https://img.shields.io/github/forks/gy65896/FVessel?label=%F0%9F%94%A7%20Fork&color=green">
</div>
</div>

<p style="text-align: center; font-weight: bold; font-size: 1.2em; margin-bottom: 0.5em;">2024</p>

- **Yu Guo**<sup>†</sup>, Yuan Gao<sup>†</sup>, Yuxu Lu, Huilin Zhu, Ryan Wen Liu, Shengfeng He, [OneRestore: A Universal Restoration Framework for Composite Degradation](https://arxiv.org/abs/2407.04621), **ECCV 2024** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:pyW8ca7W8N0C'></span></strong>
- Huilin Zhu, Jingling Yuan, Zhengwei Yang, **Yu Guo**, Zheng Wang, Xian Zhong, Shengfeng He, [Zero-shot Object Counting with Good Exemplars](https://arxiv.org/abs/2407.04948), **ECCV 2024** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:bFI3QPDXJZMC'></span></strong>
- Ryan Wen Liu, Yuxu Lu, Yuan Gao, **Yu Guo**, Wenqi Ren, Fenghua Zhu, Fei-Yue Wang, [Real-Time Multi-Scene Visibility Enhancement for Promoting Navigational Safety of Vessels Under Complex Weather Conditions](https://ieeexplore.ieee.org/abstract/document/10682473/), **T-ITS 2024** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:NhqRSupF_l8C'></span></strong>
- Ryan Wen Liu, **Yu Guo**, Yuxu Lu, Xi-Le Zhao, An-An Liu, [S3Net: Semi-self-supervised Neural Network for Visibility Enhancement of Speckled Images](https://www.sciencedirect.com/science/article/pii/S004579062400291X), **CAEE 2024** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:cFHS6HbyZ2cC'></span></strong>
- Wenyu Xu, Dong Yang, Yuan Gao, Yuxu Lu, Jingming Zhang, **Yu Guo**, [MvKSR: Multi-view Knowledge-guided Scene Recovery for Hazy and Rainy Degradation](https://ieeexplore.ieee.org/abstract/document/10598186/), **TIM 2024** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:EUQCXRtRnyEC'></span></strong>
- Yuxu Lu, Dong Yang, Yuan Gao, Ryan Wen Liu, Jun Liu, **Yu Guo**, [AoSRNet: All-in-One Scene Recovery Networks via Multi-knowledge Integration](https://www.sciencedirect.com/science/article/pii/S0950705124004209), **KBS 2024** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:f2IySw72cVMC'></span></strong>
- Jingxiang Qu, Ryan Wen Liu, Yuan Gao, **Yu Guo**, Fenghua Zhu, Fei-Yue Wang, [Double Domain Guided Real-time Low-light Image Enhancement for Ultra-high-definition Transportation Surveillance](https://ieeexplore.ieee.org/abstract/document/10423894/), **T-ITS 2024** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:b0M2c_1WBrUC'></span></strong>

<p style="text-align: center; font-weight: bold; font-size: 1.2em; margin-bottom: 0.5em;">2023</p>

- Ryan Wen Liu, Yuxu Lu, **Yu Guo**, Wenqi Ren, Fenghua Zhu, Yisheng Lv, [AiOENet: All-in-one Low-visibility Enhancement to Improve Visual Perception for Intelligent Marine Vehicles Under Severe Weather Conditions](https://ieeexplore.ieee.org/abstract/document/10375786/), **TIV 2023** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:HoB7MX3m0LUC'></span></strong>
- Jingxiang Qu, Ryan Wen Liu, Chenjie Zhao, **Yu Guo**, Sendren Sheng-Dong Xu, Fenghua Zhu, Yisheng Lv, [Multi-task Learning-enabled Automatic Vessel Draft Reading for Intelligent Maritime Surveillance](https://ieeexplore.ieee.org/abstract/document/10311073/), **T-ITS 2023** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:pqnbT2bcN3wC'></span></strong>
- **Yu Guo**, Ryan Wen Liu, Yuxu Lu, Jiangtian Nie, Lingjuan Lyu, Zehui Xiong, Jiawen Kang, Han Yu, Dusit Niyato, [Haze Visibility Enhancement for Promoting Traffic Situational Awareness in Vision-Enabled Intelligent Transportation](https://ieeexplore.ieee.org/abstract/document/10192090/), **TVT 2023 & AAAIW 2022 (BP)** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:ldfaerwXgEUC'></span></strong>
- **Yu Guo**, Ryan Wen Liu, Jingxiang Qu, Yuxu Lu, Fenghua Zhu, Yisheng Lv, [Asynchronous Trajectory Matching-based Multimodal Maritime Data Fusion for Vessel Traffic Surveillance in Inland Waterways](https://ieeexplore.ieee.org/abstract/document/10159572/), **T-ITS 2023** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:70eg2SAEIzsC'></span></strong>
- Jingxiang Qu, Ryan Wen Liu, **Yu Guo**, Yuxu Lu, Jianlong Su, Peizheng Li, [Improving Maritime Traffic Surveillance in Inland Waterways using the Robust Fusion of AIS and Visual Data](https://www.sciencedirect.com/science/article/pii/S0029801823005826), **OE 2023** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:ns9cj8rnVeAC'></span></strong>
- **Yu Guo**, Yuxu Lu, Ryan Wen Liu, Fenghua Zhu, [Blind Image Despeckling Using Multi-scale Attention-guided Neural Network](https://ieeexplore.ieee.org/abstract/document/10012299/), **TAI 2023** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:4OULZ7Gr8RgC'></span></strong>
- **Yu Guo**, Yuan Gao, Wen Liu, Yuxu Lu, Jingxiang Qu, Shengfeng He, Wenqi Ren, [SCANet: Self-paced Semi-curricular Attention Network for Non-homogeneous Image Dehazing](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/html/Guo_SCANet_Self-Paced_Semi-Curricular_Attention_Network_for_Non-Homogeneous_Image_Dehazing_CVPRW_2023_paper.html), **CVPRW 2023** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:35N4QoGY0k4C'></span></strong> <img src="https://img.shields.io/github/stars/gy65896/SCANet?label=%F0%9F%8C%9F%20Star&color=blue"> <img src="https://img.shields.io/github/forks/gy65896/SCANet?label=%F0%9F%94%A7%20Fork&color=green">

<p style="text-align: center; font-weight: bold; font-size: 1.2em; margin-bottom: 0.5em;">2022</p>

- **Yu Guo**<sup>†</sup>, Yuxu Lu<sup>†</sup>, Jingxiang Qu, Ryan Wen Liu, Wenqi Ren, [MDSFE: Multi-scale Deep Stacking Fusion Enhancer Network for Visual Data Enhancement](https://ieeexplore.ieee.org/abstract/document/9953166/), **TIM 2022** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:2P1L_qKh6hAC'></span></strong>
- Yuxu Lu<sup>†</sup>, **Yu Guo**<sup>†</sup>, Ryan Wen Liu, Kwok Tai Chui, Brij B Gupta, [GradDT: Gradient-guided Despeckling Transformer for Industrial Imaging Sensors](https://ieeexplore.ieee.org/abstract/document/9858613/), **TII 2022** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:isC4tDSrTZIC'></span></strong>
- Ryan Wen Liu, **Yu Guo**, Yuxu Lu, Kwok Tai Chui, Brij B Gupta, [Deep Network-Enabled Haze Visibility Enhancement for Visual IoT-driven Intelligent Transportation Systems](https://ieeexplore.ieee.org/abstract/document/9764372/), **TII 2022** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:JV2RwH3_ST0C'></span></strong>
- Yuxu Lu<sup>†</sup>, **Yu Guo**<sup>†</sup>, Ryan Wen Liu, Wenqi Ren, [MTRBNet: Multi-branch Topology Residual Block-based Network for Low-light Enhancement](https://ieeexplore.ieee.org/abstract/document/9741357/), **SPL 2022** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:eQOLeE2rZwMC'></span></strong>
- Ryan Wen Liu, **Yu Guo**, Jiangtian Nie, Qin Hu, Zehui Xiong, Han Yu, Mohsen Guizani, [Intelligent Edge-enabled Efficient Multi-source Data Fusion for Autonomous Surface Vehicles in Maritime Internet of Things](https://ieeexplore.ieee.org/abstract/document/9731523/), **TGCN 2022** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:YsMSGLbcyi4C'></span></strong>
- **Yu Guo**<sup>†</sup>, Yuxu Lu<sup>†</sup>, Ryan Wen Liu, [Lightweight Deep Network-enabled Real-time Low-visibility Enhancement for Promoting Vessel Detection in Maritime Video Surveillance](https://www.cambridge.org/core/journals/journal-of-navigation/article/lightweight-deep-networkenabled-realtime-lowvisibility-enhancement-for-promoting-vessel-detection-in-maritime-video-surveillance/BB396AE954852926137B71B751CEA310), **JON 2022** <strong><span id='total_cit' class='show_paper_citations' data='klYz-acAAAAJ:4TOpqqG69KYC'></span></strong>

# 🎖 Honors and Awards

* <b>Ph.D. National Scholarship</b> <b>(Top 1%)</b>, 2023, Rank: 1.
* <b>National Third Prize</b> of the China Graduate Robot Innovation Design Competition, 2023, Rank: 3.
* <b>National Second Prize</b> of the China Intelligent Unmanned Boat Search and Rescue Competition, 2023, Rank: 5.
* <b>First Prize</b> of the Smart Shipping and Crew Quality Training Seminar Workshop, 2023, Rank: 1.
* <b>Third Prize</b> of the Smart Shipping and Crew Quality Training Seminar Workshop, 2023, Rank: 4.
* <b>Provincial Science & Technology Progress</b> <b>Second Prize</b> of China Institute of Navigation, 2023, Rank: 9.
* <b>Best Paper Award</b> of the AAAI-2022 Workshop: AI for Transportation, 2022, Rank: 1.
* <b>Excellent Undergraduate Thesis</b> of WHUT <b>(Top 3%)</b>, 2021, Rank: 1.
* <b>Excellent Undergraduate Graduate</b> of WHUT, 2021, Rank: 1.
* <b>Excellent Completion</b> of the National Undergraduate Innovation and Entrepreneurship Training Program, 2021, Rank: 2.
* <b>Hubei Provincial Silver Award</b> of the China International College Students "Internet+" Innovation and Entrepreneurship Competition, 2020, Rank: 1.
* <b>National Grand Prize</b> of the China Ocean Vehicle Design and Production Competition, 2020, Rank: 1.
* <b>National First Prize</b> of the China Ocean Vehicle Design and Production Competition, 2020, Rank: 3.
* <b>National Third Prize</b> of the China Undergraduate Computer Design Competition, 2020, Rank: 2.

# 📖 Educations

* **🎓 Ph.D. in Traffic Information Engineering and Control, 2021 - Now**

<span style="color:darkgray; padding-left: 4em;">Wuhan University of Technology, Wuhan, China</span>

* **🎓 Joint Ph.D. in Computing and Information Systems, 2023 - 2024**

<span style="color:darkgray; padding-left: 4em;">Singapore Management Unversity, Singapore</span>

* **🎓 B.Sc. in Naval Architecture and Ocean Engineering, 2017 - 2021**

<span style="color:darkgray; padding-left: 4em;">Wuhan University of Technology, Wuhan, China

# 💻 Internships

* **📝 Research Assistant, 2024.10 - Now**

<span style="color:darkgray; padding-left: 4em;">City University of Hong Kong, Hong Kong, China

* **📝 Remote Intern, 2024.07 - 2024.10**

<span style="color:darkgray; padding-left: 4em;">City University of Hong Kong, Hong Kong, China

