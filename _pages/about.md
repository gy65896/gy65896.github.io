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

<div style="background: linear-gradient(to bottom, #f8f9fa 0%, #ffffff 100%); border-radius: 12px; padding: 2.5em; margin: 1.5em 0; border: 1px solid #e0e0e0; box-shadow: 0 2px 8px rgba(0,0,0,0.06);">

<div style="text-align: justify; color: #2c3e50; line-height: 1.8; font-size: 1.02em;">
<p style="margin-bottom: 1.2em;">
Yu Guo is currently a Research Assistant at <a href="https://jcstemlab.netlify.app/" style="color: #5a6c7d; text-decoration: none; border-bottom: 2px solid #a8b8c8;"><strong>WINET lab</strong></a>, City University of Hong Kong. From 2023 to 2024, he completed one significant visiting research period at <a href="http://www.shengfenghe.com/" style="color: #5a6c7d; text-decoration: none; border-bottom: 2px solid #a8b8c8;"><strong>VUG lab</strong></a>, Singapore Management University. He received his B.Sc. degree in Naval Architecture and Ocean Engineering from the Wuhan University of Technology, in 2021.
</p>

<p style="margin-bottom: 1.2em;">
His research interests include <strong style="color: #4a5568;">Computer Vision</strong> and <strong style="color: #4a5568;">Generative Model</strong>. He has published over 30 papers at the top international conferences and journals (<a href='https://scholar.google.com/citations?user=5qAe9ZMAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url\_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>) such as NeurIPS, ICML, ECCV. He has also served as a reviewer of multiple conferences and journals, including ICLR, CVPR, and TCSVT.
</p>

<div style="background: #f0f4f8; border-left: 4px solid #718096; padding: 1.2em 1.5em; border-radius: 6px; margin-top: 1.5em;">
<p style="margin: 0; color: #2d3748;">
<strong style="color: #1a202c;">💡 I am actively seeking like-minded collaborators.</strong> If you are interested in my work, please feel free to contact me via email: <a href="mailto:guoyu65896@gmail.com" style="color: #5a6c7d; text-decoration: none; font-weight: 600;">guoyu65896@gmail.com</a> or add me on <a href="images/Wechat.jpg" style="color: #5a6c7d; text-decoration: none; font-weight: 600;">WeChat</a>.
</p>
</div>

</div>

</div>

# 🔥 News

<div style="background: #f8f9fa; border-radius: 10px; padding: 1.8em; margin: 1em 0; border-left: 4px solid #718096; box-shadow: 0 2px 8px rgba(0,0,0,0.06); max-height: 400px; overflow-y: auto;">
<ul style="list-style: none; padding-left: 0; margin: 0;">
<li style="padding: 0.8em 0; border-bottom: 1px solid #e2e8f0;"><strong style="color: #4a5568;">2025.09</strong>: &nbsp;🎉 One paper has been accepted by <strong><a href="https://neurips.cc/" style="color: #2d3748; text-decoration: none;">NeurIPS 2025</a> (Spotlight)</strong>.</li>
<li style="padding: 0.8em 0; border-bottom: 1px solid #e2e8f0;"><strong style="color: #4a5568;">2025.05</strong>: &nbsp;🎉 One paper has been accepted by <strong><a href="https://icml.cc/" style="color: #2d3748; text-decoration: none;">ICML 2025</a></strong>.</li>
<li style="padding: 0.8em 0; border-bottom: 1px solid #e2e8f0;"><strong style="color: #4a5568;">2024.07</strong>: &nbsp;🎉 Two papers have been accepted by <strong><a href="https://eccv.ecva.net/" style="color: #2d3748; text-decoration: none;">ECCV 2024</a></strong>.</li>
<li style="padding: 0.8em 0;"><strong style="color: #4a5568;">2024.04</strong>: &nbsp;🎉 The constructed <strong><a href="https://github.com/gy65896/FVessel" style="color: #2d3748; text-decoration: none;">FVessel dataset</a></strong> is included in the <strong><a href="https://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm" style="color: #2d3748; text-decoration: none;">CVonline: Image Databases</a></strong> at the University of Edinburgh.</li>
</ul>
</div>

# 📝 Representative Works <span style="color: #4a5568; font-size: 0.8em;">(* means equal contribution)</span>

<div style="display: flex; flex-direction: column; gap: 2em; margin: 1.5em 0;">

<!-- Paper 1: NeurIPS 2025 -->
<div style="background: white; border-radius: 10px; overflow: hidden; box-shadow: 0 2px 10px rgba(0,0,0,0.1); border: 1px solid #e0e0e0; display: flex; flex-direction: row; align-items: center;">
<div style="flex: 0 0 40%; position: relative; background:rgb(255, 255, 255); display: flex; align-items: center; justify-content: center; padding: 1.5em;">
<img src='papers/NeurIPS2025_Neptune-X/abstract.jpg' alt="Neptune-X" style="max-width: 105%; height: auto; object-fit: contain; display: block;">
<div style="position: absolute; top: 12px; left: 12px; background: #2d3748; color: white; padding: 5px 12px; border-radius: 5px; font-size: 0.85em; font-weight: 600; box-shadow: 0 2px 6px rgba(0,0,0,0.2);">NeurIPS 2025</div>
</div>
<div style="flex: 1; padding: 1.5em 2em; display: flex; flex-direction: column; justify-content: center;">
<h4 style="margin: 0 0 0.6em 0; font-size: 1.15em; line-height: 1.35; color: #2d3748;">
<a href="https://arxiv.org/abs/2509.20745" style="color: #2d3748; text-decoration: none;">Neptune-X: Active X-to-Maritime Generation for Universal Maritime Object Detection</a>
</h4>
<p style="margin: 0 0 0.4em 0; color: #718096; font-size: 0.88em; line-height: 1.5;"><strong>Yu Guo</strong>, Shengfeng He, Yuxu Lu, Haonan An, Yihang Tao, Huilin Zhu, Jingxian Liu, Yuguang Fang</p>
<p style="margin: 0 0 0.6em 0; color: #c53030; font-size: 0.82em; font-weight: 600;">(Spotlight, Acceptance Rate 3.2%)</p>
<p style="margin: 0; color: #5a6c7d; font-size: 0.88em; line-height: 1.8;">
<a href="https://gy65896.github.io/projects/NeurIPS2025_Neptune-X/index.html" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Project]</a>
<a href="https://arxiv.org/abs/2509.20745" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Paper]</a>
<a href="" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Video]</a>
<a href="" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Poster]</a>
<a href="https://huggingface.co/datasets/gy65896/MGD" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Dataset]</a>
<a href="https://github.com/gy65896/Neptune-X" target="_blank" style="color: #4a5568; text-decoration: none; font-weight: 500;">[Code]</a>
</p>
</div>
</div>

<!-- Paper 2: ICML 2025 -->
<div style="background: white; border-radius: 10px; overflow: hidden; box-shadow: 0 2px 10px rgba(0,0,0,0.1); border: 1px solid #e0e0e0; display: flex; flex-direction: row; align-items: center;">
<div style="flex: 0 0 40%; position: relative; background:rgb(255, 255, 255); display: flex; align-items: center; justify-content: center; padding: 1.5em;">
<img src='papers/ICML2025_Instruct2See/abstract.png' alt="Instruct2See" style="max-width: 105%; height: auto; object-fit: contain; display: block;">
<div style="position: absolute; top: 12px; left: 12px; background: #2d3748; color: white; padding: 5px 12px; border-radius: 5px; font-size: 0.85em; font-weight: 600; box-shadow: 0 2px 6px rgba(0,0,0,0.2);">ICML 2025</div>
</div>
<div style="flex: 1; padding: 1.5em 2em; display: flex; flex-direction: column; justify-content: center;">
<h4 style="margin: 0 0 0.6em 0; font-size: 1.15em; line-height: 1.35; color: #2d3748;">
<a href="https://arxiv.org/abs/2505.17649" style="color: #2d3748; text-decoration: none;">Instruct2See: Learning to Remove Any Obstructions Across Distributions</a>
</h4>
<p style="margin: 0 0 0.6em 0; color: #718096; font-size: 0.88em; line-height: 1.5;">Junhang Li*, <strong>Yu Guo</strong>*, Chuhua Xian, Shengfeng He</p>
<p style="margin: 0; color: #5a6c7d; font-size: 0.88em; line-height: 1.8;">
<a href="https://jhscut.github.io/Instruct2See/" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Project]</a>
<a href="https://arxiv.org/abs/2505.17649" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Paper]</a>
<a href="https://icml.cc/virtual/2025/poster/45263" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Video]</a>
<a href="https://gy65896.github.io/papers/ICML2025_Instruct2See/Instruct2See_poster.png" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Poster]</a>
<a href="" target="_blank" style="color: #4a5568; text-decoration: none; font-weight: 500;">[Code]</a>
</p>
</div>
</div>

<!-- Paper 3: ECCV 2024 -->
<div style="background: white; border-radius: 10px; overflow: hidden; box-shadow: 0 2px 10px rgba(0,0,0,0.1); border: 1px solid #e0e0e0; display: flex; flex-direction: row; align-items: center;">
<div style="flex: 0 0 40%; position: relative; background:rgb(255, 255, 255); display: flex; align-items: center; justify-content: center; padding: 1.5em;">
<img src='papers/ECCV2024_OneRestore/abstract.jpg' alt="OneRestore" style="max-width: 105%; height: auto; object-fit: contain; display: block;">
<div style="position: absolute; top: 12px; left: 12px; background: #2d3748; color: white; padding: 5px 12px; border-radius: 5px; font-size: 0.85em; font-weight: 600; box-shadow: 0 2px 6px rgba(0,0,0,0.2);">ECCV 2024</div>
</div>
<div style="flex: 1; padding: 1.5em 2em; display: flex; flex-direction: column; justify-content: center;">
<h4 style="margin: 0 0 0.6em 0; font-size: 1.15em; line-height: 1.35; color: #2d3748;">
<a href="https://arxiv.org/abs/2407.04621" style="color: #2d3748; text-decoration: none;">OneRestore: A Universal Restoration Framework for Composite Degradation</a>
</h4>
<p style="margin: 0 0 0.6em 0; color: #718096; font-size: 0.88em; line-height: 1.5;"><strong>Yu Guo</strong>*, Yuan Gao*, Yuxu Lu, Huilin Zhu, Ryan Wen Liu, Shengfeng He</p>
<p style="margin: 0 0 0.5em 0; color: #5a6c7d; font-size: 0.88em; line-height: 1.8;">
<a href="https://gy65896.github.io/projects/ECCV2024_OneRestore/index.html" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Project]</a>
<a href="https://arxiv.org/abs/2407.04621" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Paper]</a>
<a href="https://www.youtube.com/embed/AFr5tZdPlZ4" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Video]</a>
<a href="https://gy65896.github.io/papers/ECCV2024_OneRestore/OneRestore_poster.png" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Poster]</a>
<a href="https://onedrive.live.com/?id=CBB69E4E3408EBCD%2138238&resid=CBB69E4E3408EBCD%2138238&ithint=folder&authkey=%21AMxuLGqPrvXXQ4c&cid=cbb69e4e3408ebcd" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Dataset]</a>
<a href="https://github.com/gy65896/OneRestore" target="_blank" style="color: #4a5568; text-decoration: none; font-weight: 500;">[Code]</a>
</p>
<p style="margin: 0; font-size: 0.85em;">
<img src="https://img.shields.io/github/stars/gy65896/OneRestore?label=%F0%9F%8C%9F%20Star&color=blue" alt="stars" style="vertical-align: middle;">
<img src="https://img.shields.io/github/forks/gy65896/OneRestore?label=%F0%9F%94%A7%20Fork&color=green" alt="forks" style="vertical-align: middle; margin-left: 0.5em;">
</p>
</div>
</div>

<!-- Paper 4: T-ITS 2023 -->
<div style="background: white; border-radius: 10px; overflow: hidden; box-shadow: 0 2px 10px rgba(0,0,0,0.1); border: 1px solid #e0e0e0; display: flex; flex-direction: row; align-items: center;">
<div style="flex: 0 0 40%; position: relative; background:rgb(255, 255, 255); display: flex; align-items: center; justify-content: center; padding: 1.5em;">
<img src='papers/TITS2023_DeepSORVF/method.jpg' alt="DeepSORVF" style="max-width: 105%; height: auto; object-fit: contain; display: block;">
<div style="position: absolute; top: 12px; left: 12px; background: #2d3748; color: white; padding: 5px 12px; border-radius: 5px; font-size: 0.85em; font-weight: 600; box-shadow: 0 2px 6px rgba(0,0,0,0.2);">T-ITS 2023</div>
</div>
<div style="flex: 1; padding: 1.5em 2em; display: flex; flex-direction: column; justify-content: center;">
<h4 style="margin: 0 0 0.6em 0; font-size: 1.15em; line-height: 1.35; color: #2d3748;">
<a href="https://ieeexplore.ieee.org/document/10159572" style="color: #2d3748; text-decoration: none;">Asynchronous Trajectory Matching-based Multimodal Maritime Data Fusion for Vessel Traffic Surveillance in Inland Waterways</a>
</h4>
<p style="margin: 0 0 0.6em 0; color: #718096; font-size: 0.88em; line-height: 1.5;"><strong>Yu Guo</strong>, Ryan Wen Liu, Jingxiang Qu, Yuxu Lu, Fenghua Zhu, Yisheng Lv</p>
<p style="margin: 0 0 0.5em 0; color: #5a6c7d; font-size: 0.88em; line-height: 1.8;">
<a href="https://gy65896.github.io/projects/TITS2023_DeepSORVF/index.html" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Project]</a>
<a href="https://ieeexplore.ieee.org/document/10159572" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Paper]</a>
<a href="https://github.com/gy65896/FVessel" target="_blank" style="color: #4a5568; text-decoration: none; margin-right: 1em; font-weight: 500;">[Dataset]</a>
<a href="https://github.com/gy65896/DeepSORVF" target="_blank" style="color: #4a5568; text-decoration: none; font-weight: 500;">[Code]</a>
</p>
<p style="margin: 0; font-size: 0.85em;">
<img src="https://img.shields.io/github/stars/gy65896/FVessel?label=%F0%9F%8C%9F%20Star&color=blue" alt="stars" style="vertical-align: middle;">
<img src="https://img.shields.io/github/forks/gy65896/FVessel?label=%F0%9F%94%A7%20Fork&color=green" alt="forks" style="vertical-align: middle; margin-left: 0.5em;">
<img src="https://img.shields.io/github/stars/gy65896/DeepSORVF?label=%F0%9F%8C%9F%20Star&color=blue" alt="stars" style="vertical-align: middle;">
<img src="https://img.shields.io/github/forks/gy65896/DeepSORVF?label=%F0%9F%94%A7%20Fork&color=green" alt="forks" style="vertical-align: middle; margin-left: 0.5em;">
</p>
</div>
</div>

</div>

<div style="text-align: center; margin: 2em 0;">
<button id="toggleFullList" style="
    background: #5a6c7d;
    color: white;
    border: none;
    padding: 12px 36px;
    font-size: 1.05em;
    font-weight: 600;
    border-radius: 8px;
    cursor: pointer;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    transition: all 0.3s ease;
    outline: none;
">📚 Full Publication List</button>
</div>

<div id="fullListPublications" style="
    display: none;
    background: #f8f9fa;
    border-radius: 10px;
    padding: 2em;
    margin: 1.5em 0;
    border: 1px solid #e0e0e0;
    box-shadow: 0 2px 8px rgba(0,0,0,0.06);
    transition: all 0.4s ease;
">

<h3 style="text-align: center; color: #2d3748; font-size: 1.3em; margin-bottom: 1.5em; font-weight: 600;">📖 Complete Publications</h3>

<div style="background: white; padding: 1.5em; border-radius: 8px; margin-bottom: 1.2em; box-shadow: 0 1px 4px rgba(0,0,0,0.08); border-left: 3px solid #718096;">
<h4 style="text-align: center; color: #4a5568; font-size: 1.2em; margin-bottom: 1em; border-bottom: 2px solid #cbd5e0; padding-bottom: 0.5em; display: inline-block; width: 100%;">🎯 2025</h4>

<ul style="line-height: 1.8; text-align: justify;">
<li><strong>Yu Guo</strong>, Shengfeng He, Yuxu Lu, Haonan An, Yihang Tao, Huilin Zhu, Jingxian Liu, Yuguang Fang, <a href="https://arxiv.org/abs/2509.20745">Neptune-X: Active X-to-Maritime Generation for Universal Maritime Object Detection</a>, <strong>NeurIPS 2025 (Spotlight)</strong></li>
<li>Zhengru Fang, Zhenghao Liu, Jingjing Wang, Senkang Hu, <strong>Yu Guo</strong>, Yiqin Deng, Yuguang Fang, <a href="https://arxiv.org/abs/2504.18317">Task-oriented Communications for Visual Navigation with Edge-aerial Collaboration in Low Altitude Economy</a>, <strong>GlobeCom 2025</strong></li>
<li>Junhang Li*, <strong>Yu Guo</strong>*, Chuhua Xian, Shengfeng He, <a href="https://arxiv.org/abs/2505.17649">Instruct2See: Learning to Remove Any Obstructions Across Distributions</a>, <strong>ICML 2025</strong></li>
</ul>
</div>

<div style="background: white; padding: 1.5em; border-radius: 8px; margin-bottom: 1.2em; box-shadow: 0 1px 4px rgba(0,0,0,0.08); border-left: 3px solid #718096;">
<h4 style="text-align: center; color: #4a5568; font-size: 1.2em; margin-bottom: 1em; border-bottom: 2px solid #cbd5e0; padding-bottom: 0.5em; display: inline-block; width: 100%;">🎯 2024</h4>

<ul style="line-height: 1.8; text-align: justify;">
<li><strong>Yu Guo</strong>*, Yuan Gao*, Yuxu Lu, Huilin Zhu, Ryan Wen Liu, Shengfeng He, <a href="https://arxiv.org/abs/2407.04621">OneRestore: A Universal Restoration Framework for Composite Degradation</a>, <strong>ECCV 2024</strong></li>
<li>Huilin Zhu, Jingling Yuan, Zhengwei Yang, <strong>Yu Guo</strong>, Zheng Wang, Xian Zhong, Shengfeng He, <a href="https://arxiv.org/abs/2407.04948">Zero-shot Object Counting with Good Exemplars</a>, <strong>ECCV 2024</strong></li>
<li>Ryan Wen Liu, Yuxu Lu, Yuan Gao, <strong>Yu Guo</strong>, Wenqi Ren, Fenghua Zhu, Fei-Yue Wang, <a href="https://ieeexplore.ieee.org/abstract/document/10682473/">Real-Time Multi-Scene Visibility Enhancement for Promoting Navigational Safety of Vessels Under Complex Weather Conditions</a>, <strong>T-ITS 2024</strong></li>
<li>Wenyu Xu, Dong Yang, Yuan Gao, Yuxu Lu, Jingming Zhang, <strong>Yu Guo</strong>, <a href="https://ieeexplore.ieee.org/abstract/document/10598186/">MvKSR: Multi-view Knowledge-guided Scene Recovery for Hazy and Rainy Degradation</a>, <strong>TIM 2024</strong></li>
<li>Yuxu Lu, Dong Yang, Yuan Gao, Ryan Wen Liu, Jun Liu, <strong>Yu Guo</strong>, <a href="https://www.sciencedirect.com/science/article/pii/S0950705124004209">AoSRNet: All-in-One Scene Recovery Networks via Multi-knowledge Integration</a>, <strong>KBS 2024</strong></li>
<li>Jingxiang Qu, Ryan Wen Liu, Yuan Gao, <strong>Yu Guo</strong>, Fenghua Zhu, Fei-Yue Wang, <a href="https://ieeexplore.ieee.org/abstract/document/10423894/">Double Domain Guided Real-time Low-light Image Enhancement for Ultra-high-definition Transportation Surveillance</a>, <strong>T-ITS 2024</strong></li>
</ul>
</div>

<div style="background: white; padding: 1.5em; border-radius: 8px; margin-bottom: 1.2em; box-shadow: 0 1px 4px rgba(0,0,0,0.08); border-left: 3px solid #718096;">
<h4 style="text-align: center; color: #4a5568; font-size: 1.2em; margin-bottom: 1em; border-bottom: 2px solid #cbd5e0; padding-bottom: 0.5em; display: inline-block; width: 100%;">🎯 2023</h4>

<ul style="line-height: 1.8; text-align: justify;">
<li>Jingxiang Qu, Ryan Wen Liu, Chenjie Zhao, <strong>Yu Guo</strong>, Sendren Sheng-Dong Xu, Fenghua Zhu, Yisheng Lv, <a href="https://ieeexplore.ieee.org/abstract/document/10311073/">Multi-task Learning-enabled Automatic Vessel Draft Reading for Intelligent Maritime Surveillance</a>, <strong>T-ITS 2023</strong></li>
<li><strong>Yu Guo</strong>, Ryan Wen Liu, Yuxu Lu, Jiangtian Nie, Lingjuan Lyu, Zehui Xiong, Jiawen Kang, Han Yu, Dusit Niyato, <a href="https://ieeexplore.ieee.org/abstract/document/10192090/">Haze Visibility Enhancement for Promoting Traffic Situational Awareness in Vision-Enabled Intelligent Transportation</a>, <strong>TVT 2023 & AAAIW 2022 (BP)</strong></li>
<li><strong>Yu Guo</strong>, Ryan Wen Liu, Jingxiang Qu, Yuxu Lu, Fenghua Zhu, Yisheng Lv, <a href="https://ieeexplore.ieee.org/abstract/document/10159572/">Asynchronous Trajectory Matching-based Multimodal Maritime Data Fusion for Vessel Traffic Surveillance in Inland Waterways</a>, <strong>T-ITS 2023</strong></li>
<li><strong>Yu Guo</strong>, Yuxu Lu, Ryan Wen Liu, Fenghua Zhu, <a href="https://ieeexplore.ieee.org/abstract/document/10012299/">Blind Image Despeckling Using Multi-scale Attention-guided Neural Network</a>, <strong>TAI 2023</strong></li>
<li><strong>Yu Guo</strong>, Yuan Gao, Wen Liu, Yuxu Lu, Jingxiang Qu, Shengfeng He, Wenqi Ren, <a href="https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/html/Guo_SCANet_Self-Paced_Semi-Curricular_Attention_Network_for_Non-Homogeneous_Image_Dehazing_CVPRW_2023_paper.html">SCANet: Self-paced Semi-curricular Attention Network for Non-homogeneous Image Dehazing</a>, <strong>CVPRW 2023</strong></li>
</ul>
</div>

<div style="background: white; padding: 1.5em; border-radius: 8px; box-shadow: 0 1px 4px rgba(0,0,0,0.08); border-left: 3px solid #718096;">
<h4 style="text-align: center; color: #4a5568; font-size: 1.2em; margin-bottom: 1em; border-bottom: 2px solid #cbd5e0; padding-bottom: 0.5em; display: inline-block; width: 100%;">🎯 2022</h4>

<ul style="line-height: 1.8; text-align: justify;">
<li><strong>Yu Guo</strong>*, Yuxu Lu*, Jingxiang Qu, Ryan Wen Liu, Wenqi Ren, <a href="https://ieeexplore.ieee.org/abstract/document/9953166/">MDSFE: Multi-scale Deep Stacking Fusion Enhancer Network for Visual Data Enhancement</a>, <strong>TIM 2022</strong></li>
<li>Yuxu Lu*, <strong>Yu Guo</strong>*, Ryan Wen Liu, Kwok Tai Chui, Brij B Gupta, <a href="https://ieeexplore.ieee.org/abstract/document/9858613/">GradDT: Gradient-guided Despeckling Transformer for Industrial Imaging Sensors</a>, <strong>TII 2022</strong></li>
<li>Ryan Wen Liu, <strong>Yu Guo</strong>, Yuxu Lu, Kwok Tai Chui, Brij B Gupta, <a href="https://ieeexplore.ieee.org/abstract/document/9764372/">Deep Network-Enabled Haze Visibility Enhancement for Visual IoT-driven Intelligent Transportation Systems</a>, <strong>TII 2022</strong></li>
<li>Yuxu Lu*, <strong>Yu Guo</strong>*, Ryan Wen Liu, Wenqi Ren, <a href="https://ieeexplore.ieee.org/abstract/document/9741357/">MTRBNet: Multi-branch Topology Residual Block-based Network for Low-light Enhancement</a>, <strong>SPL 2022</strong></li>
<li>Ryan Wen Liu, <strong>Yu Guo</strong>, Jiangtian Nie, Qin Hu, Zehui Xiong, Han Yu, Mohsen Guizani, <a href="https://ieeexplore.ieee.org/abstract/document/9731523/">Intelligent Edge-enabled Efficient Multi-source Data Fusion for Autonomous Surface Vehicles in Maritime Internet of Things</a>, <strong>TGCN 2022</strong></li>
<li><strong>Yu Guo</strong>*, Yuxu Lu*, Ryan Wen Liu, <a href="https://www.cambridge.org/core/journals/journal-of-navigation/article/lightweight-deep-networkenabled-realtime-lowvisibility-enhancement-for-promoting-vessel-detection-in-maritime-video-surveillance/BB396AE954852926137B71B751CEA310">Lightweight Deep Network-enabled Real-time Low-visibility Enhancement for Promoting Vessel Detection in Maritime Video Surveillance</a>, <strong>JON 2022</strong></li>
</ul>
</div>

</div>

<style>
#toggleFullList:hover {
    background: #4a5568;
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}

#toggleFullList:active {
    transform: translateY(1px);
}

#fullListPublications.show {
    animation: slideDown 0.4s ease-out;
}

@keyframes slideDown {
    from {
        opacity: 0;
        transform: translateY(-10px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
    var btn = document.getElementById("toggleFullList");
    var pubList = document.getElementById("fullListPublications");
    
    btn.addEventListener("click", function () {
        if (pubList.style.display === "none" || pubList.style.display === "") {
            pubList.style.display = "block";
            pubList.classList.add("show");
            btn.textContent = "🔼 Hide List";
            btn.style.background = "#718096";
        } else {
            pubList.style.display = "none";
            pubList.classList.remove("show");
            btn.textContent = "📚 Full Publication List";
            btn.style.background = "#5a6c7d";
        }
    });
});
</script>

# 🎖 Honors and Awards

<div style="background: #f8f9fa; border-radius: 10px; padding: 2em; margin: 1em 0; border: 1px solid #e0e0e0; box-shadow: 0 2px 8px rgba(0,0,0,0.06);">

<div style="background: white; padding: 1.2em; border-radius: 8px; margin-bottom: 1em; border-left: 3px solid #718096; box-shadow: 0 1px 4px rgba(0,0,0,0.08);">
<h4 style="color: #2d3748; margin: 0 0 0.8em 0; font-size: 1.15em;">🏆 Ph.D. Period (2021-2025)</h4>
<ul style="line-height: 2; margin: 0;">
<li><strong>Ph.D. National Scholarship</strong> <span style="background: #718096; color: #fff; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 600;">Top 1</span>, 2023, Rank: 1</li>
<li><strong>National Third Prize</strong> of the China Graduate Robot Innovation Design Competition, 2023, Rank: 3</li>
<li><strong>National Second Prize</strong> of the China Intelligent Unmanned Boat Search and Rescue Competition, 2023, Rank: 5</li>
<li><strong>First Prize</strong> of the Smart Shipping and Crew Quality Training Seminar Workshop, 2023, Rank: 1</li>
<li><strong>Third Prize</strong> of the Smart Shipping and Crew Quality Training Seminar Workshop, 2023, Rank: 4</li>
<li><strong>Provincial Science & Technology Progress Second Prize</strong> of China Institute of Navigation, 2023, Rank: 9</li>
<li><strong>Best Paper Award</strong> of the AAAI-2022 Workshop: AI for Transportation, 2022, Rank: 1</li>
</ul>
</div>

<div style="background: white; padding: 1.2em; border-radius: 8px; border-left: 3px solid #718096; box-shadow: 0 1px 4px rgba(0,0,0,0.08);">
<h4 style="color: #2d3748; margin: 0 0 0.8em 0; font-size: 1.15em;">🎓 Undergraduate Period (2017-2021)</h4>
<ul style="line-height: 2; margin: 0;">
<li><strong>Excellent Undergraduate Thesis</strong> of WHUT <span style="background: #718096; color: #fff; padding: 2px 8px; border-radius: 4px; font-size: 0.85em; font-weight: 600;">Top 3%</span>, 2021, Rank: 1</li>
<li><strong>Excellent Undergraduate Graduate</strong> of WHUT, 2021, Rank: 1</li>
<li><strong>Excellent Completion</strong> of the National Undergraduate Innovation and Entrepreneurship Training Program, 2021, Rank: 2</li>
<li><strong>Hubei Provincial Silver Award</strong> of the China International College Students "Internet+" Innovation and Entrepreneurship Competition, 2020, Rank: 1</li>
<li><strong>National Grand Prize</strong> of the China Ocean Vehicle Design and Production Competition, 2020, Rank: 1</li>
<li><strong>National First Prize</strong> of the China Ocean Vehicle Design and Production Competition, 2020, Rank: 3</li>
<li><strong>National Third Prize</strong> of the China Undergraduate Computer Design Competition, 2020, Rank: 2</li>
</ul>
</div>

</div>

# 📖 Educations

<div style="display: flex; flex-direction: column; gap: 1.2em; margin: 1em 0;">

<div style="background: white; border-radius: 8px; padding: 1.8em; box-shadow: 0 2px 8px rgba(0,0,0,0.08); border-left: 4px solid #4a5568;">
<h4 style="color: #2d3748; margin: 0 0 0.5em 0; font-size: 1.2em;">🎓 Ph.D. in Traffic Information Engineering and Control</h4>
<p style="color: #4a5568; margin: 0.3em 0; font-size: 1em;"><strong>📅 2021 - 2025</strong></p>
<p style="color: #718096; margin: 0.5em 0 0 0; font-size: 0.95em;">📍 Wuhan University of Technology, Wuhan, China</p>
</div>

<div style="background: white; border-radius: 8px; padding: 1.8em; box-shadow: 0 2px 8px rgba(0,0,0,0.08); border-left: 4px solid #718096;">
<h4 style="color: #2d3748; margin: 0 0 0.5em 0; font-size: 1.2em;">🎓 Visiting Ph.D. in Computing and Information Systems</h4>
<p style="color: #4a5568; margin: 0.3em 0; font-size: 1em;"><strong>📅 2023 - 2024</strong></p>
<p style="color: #718096; margin: 0.5em 0 0 0; font-size: 0.95em;">📍 Singapore Management University, Singapore</p>
</div>

<div style="background: white; border-radius: 8px; padding: 1.8em; box-shadow: 0 2px 8px rgba(0,0,0,0.08); border-left: 4px solid #8a95a1;">
<h4 style="color: #2d3748; margin: 0 0 0.5em 0; font-size: 1.2em;">🎓 B.Sc. in Naval Architecture and Ocean Engineering</h4>
<p style="color: #4a5568; margin: 0.3em 0; font-size: 1em;"><strong>📅 2017 - 2021</strong></p>
<p style="color: #718096; margin: 0.5em 0 0 0; font-size: 0.95em;">📍 Wuhan University of Technology, Wuhan, China</p>
</div>

</div>

# 💻 Internships

<div style="display: flex; flex-direction: column; gap: 1.2em; margin: 1em 0;">

<div style="background: white; border-radius: 8px; padding: 1.8em; box-shadow: 0 2px 8px rgba(0,0,0,0.08); border-left: 4px solid #5a6c7d; position: relative;">
<div style="position: absolute; top: 1.5em; right: 1.5em; background: #5a6c7d; color: white; padding: 4px 10px; border-radius: 4px; font-size: 0.85em; font-weight: 600;">Current</div>
<h4 style="color: #2d3748; margin: 0 0 0.5em 0; font-size: 1.2em;">📝 Research Assistant</h4>
<p style="color: #4a5568; margin: 0.3em 0; font-size: 1em;"><strong>📅 2024.10 - Present</strong></p>
<p style="color: #718096; margin: 0.5em 0 0 0; font-size: 0.95em;">📍 City University of Hong Kong, Hong Kong, China</p>
</div>

<div style="background: white; border-radius: 8px; padding: 1.8em; box-shadow: 0 2px 8px rgba(0,0,0,0.08); border-left: 4px solid #8a95a1; position: relative;">
<h4 style="color: #2d3748; margin: 0 0 0.5em 0; font-size: 1.2em;">📝 Remote Intern</h4>
<p style="color: #4a5568; margin: 0.3em 0; font-size: 1em;"><strong>📅 2024.07 - 2024.10</strong></p>
<p style="color: #718096; margin: 0.5em 0 0 0; font-size: 0.95em;">📍 City University of Hong Kong, Hong Kong, China</p>
</div>

</div>

