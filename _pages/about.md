---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
  body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; }
  
  .resume-item {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 5px;
  }
  .resume-org { font-weight: bold; font-size: 1.05em; color: #333; }
  .resume-loc { font-style: italic; color: #666; font-size: 0.9em; }
  .resume-role { font-style: italic; color: #555; margin-bottom: 15px; display: block;}
  
  .pub-item { margin-bottom: 25px; }
  .pub-title { font-weight: bold; color: #000; font-size: 1.05em; }
  .pub-authors { color: #444; }
  .pub-venue { font-weight: bold; color: #d9534f; }
  
  .pub-btn {
    display: inline-block;
    padding: 3px 8px;
    margin-right: 5px;
    margin-top: 5px;
    background-color: #f6f8fa;
    border: 1px solid #d0d7de;
    border-radius: 6px;
    color: #24292f;
    text-decoration: none !important;
    font-size: 0.85em;
    transition: 0.2s;
  }
  .pub-btn:hover { background-color: #eef1f4; border-color: #0969da; color: #0969da; }

  .tldr-box {
    margin-top: 8px;
    padding: 8px 12px;
    background-color: #f1f8ff;
    border-left: 3px solid #0969da;
    border-radius: 0 4px 4px 0;
    color: #444;
    font-size: 0.9em;
    line-height: 1.4;
  }
  
  .alert-banner {
    background-color: #fff5f5;
    border: 1px solid #ff8182;
    color: #cf222e;
    padding: 12px;
    border-radius: 6px;
    text-align: center;
    margin-bottom: 20px;
    font-weight: 500;
  }
</style>

<div style="background-color: #ffe6e6; border: 1px solid #ff0000; padding: 10px; margin-bottom: 20px; border-radius: 5px; text-align: center; color: #cc0000;">
    <strong>🔥 I am actively looking for Ph.D. positions in Robotics and Computer Vision starting in Fall 2026.</strong>
</div>

I am a Master's student at the University of Zurich, majoring in Artificial Intelligence. Since August 2024, I have been working as a Student Researcher at the **Computer Vision Lab (CVL), ETH Zurich**, fortunately advised by Prof. Dr. [Guolei Sun](https://guoleisun.github.io/) and Dr. [Yawei Li](https://yaweili.bitbucket.io/).

My research aims to build **efficient and robust perception systems** for intelligent agents. Currently, I focus on:
* **Video Understanding:** Robust segmentation and object tracking in dynamic scenes (crucial for robot perception).
* **Efficient AI:** Model quantization and compression to enable foundation models on resource-constrained edge devices.
* **Embodied AI:** Bridging the gap between vision foundation models and robotic control.

Prior to my master's, I spent 3 years as an Algorithm Engineer at Servyou Group, where I specialized in building large-scale ML infrastructure and real-time deployment systems.

---

# 🔥 News
* **[Sept. 2025]** One paper on Video Camouflaged Object Segmentation (CamSAM2) was accepted to **NeurIPS 2025**!
* **[Jun. 2025]** One paper was accepted to **Visual Intelligence**!
* **[Aug. 2024]** Joined **Computer Vision Lab (CVL)** at **ETH Zurich** as a Student Researcher.

---

# 📝 Publications

(\* indicates equal contribution)

**Yuli Zhou**, Qingxuan Chen, Luca Benini, Guolei Sun, Yawei Li. **Revisiting adaptive rounding with vectorized reparameterization for LLM quantization.** *preprint* (2025).  
[[paper](https://arxiv.org/pdf/2602.02151)] [[code](https://github.com/zhoustan/VQRound)].
<!-- > **TL;DR:** Proposed VQRound to enable competitive 2-bit/3-bit quantization on billion-parameter models, significantly reducing memory for edge deployment. -->


**Yuli Zhou**, Yawei Li, Yuqian Fu, Luca Benini, Ender Konukoglu, Guolei Sun. **CamSAM2: Segment anything accurately in camouflaged videos.** *NeurIPS 2025* (2025).  
[[paper](https://arxiv.org/pdf/2503.19730)] [[code](https://github.com/zhoustan/CamSAM2)]  
<!-- > **TL;DR:** Proposed a framework enhancing temporal coherence and segmentation accuracy in challenging camouflaged video scenes without modifying SAM2's parameters. -->


**Yuli Zhou**, Guolei Sun, Yawei Li, Guo-Sen Xie, Luca Benini, Ender Konukoglu. **When SAM2 meets video camouflaged object segmentation: a comprehensive evaluation and adaptation.** *Visual Intelligence* 3, 10 (2025).  
[[paper](https://link.springer.com/article/10.1007/s44267-025-00082-1)] [[code](https://github.com/zhoustan/SAM2-VCOS)]

Yung-Hsin Chen\*, **Yuli Zhou\***. **Enhancing OCR performance through Post-OCR models: Adopting glyph embedding for improved correction.** *arXiv preprint* (2023).  
[[paper](https://arxiv.org/pdf/2308.15262)]

Canghong Jin, **Yuli Zhou**, Shengyu Ying, Chi Zhang, Weisong Wang, Minghui Wu. **A knowledge-fusion ranking system with an attention network for making assignment recommendations.** *Computational Intelligence and Neuroscience*, 6748430 (2020).  
[[paper](https://onlinelibrary.wiley.com/doi/pdf/10.1155/2020/6748430)]


---

## 🎓 Education

<div class="resume-item">
  <span class="resume-org">University of Zurich</span>
  <span class="resume-loc">Zurich, Switzerland</span>
</div>
<span class="resume-role">M.Sc. in Artificial Intelligence, Minor in Data Science (Feb. 2023 - Present)</span>

<div class="resume-item">
  <span class="resume-org">ETH Zurich</span>
  <span class="resume-loc">Zurich, Switzerland</span>
</div>
<span class="resume-role">Special Student in Computer Science (Feb. 2023 - Present)</span>

<div class="resume-item">
  <span class="resume-org">Zhejiang University City College</span>
  <span class="resume-loc">Hangzhou, China</span>
</div>
<span class="resume-role">B.Eng. in Computer Science (Sep. 2016 - Jun. 2020)</span>

---

## 💻 Work Experience

<div class="resume-item">
  <span class="resume-org">Servyou Software Group Co., Ltd.</span>
  <span class="resume-loc">Hangzhou, China</span>
</div>
<span class="resume-role">Algorithm Engineer (Jun. 2019 - Jul. 2022)</span>

* **Machine Learning Platform:** Designed a Kubernetes-based ML platform; implemented core compilers and data pipelines.
* **Intelligent Customer Service:** Built a BERT-based Q&A bot achieving 90% resolution rate.
* **Image Recognition:** Architected high-concurrency OCR systems (CNN+LSTM, YOLO) with 99.99% SLA.


<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=a&t=tt&d=dechcSMjaGO07G6CymH4u-Bg05CWw8GLJyjQW_JhEZg'></script>
