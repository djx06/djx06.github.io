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
.proj-list { margin-top: 0.5em; }
.proj-row { display: flex; gap: 1.4em; align-items: flex-start; padding: 1.1em 0; border-bottom: 1px solid #e5e5e5; }
.proj-row:last-child { border-bottom: none; }
.proj-media { flex: 0 0 40%; max-width: 40%; }
.proj-media img { width: 100%; border-radius: 6px; border: 1px solid #eee; display: block; }
.proj-media .video { position: relative; width: 100%; aspect-ratio: 16 / 9; }
.proj-media .video iframe { position: absolute; inset: 0; width: 100%; height: 100%; border: 0; border-radius: 6px; }
.proj-info { flex: 1; min-width: 0; font-size: 0.85em; line-height: 1.5; }
.proj-title { font-weight: 700; font-size: 1.05em; margin: 0 0 0.2em; }
.proj-title a { text-decoration: none; }
.proj-authors { color: #555; margin: 0 0 0.15em; }
.proj-venue { font-style: italic; color: #333; margin: 0 0 0.45em; }
.proj-badge { display: inline-block; font-style: normal; font-size: 0.8em; font-weight: 700; color: #b3261e; border: 1px solid #b3261e; border-radius: 4px; padding: 0 0.4em; margin-left: 0.3em; }
.proj-desc { margin: 0 0 0.45em; }
.proj-links a { margin-right: 0.9em; font-weight: 600; }
@media (max-width: 700px) {
  .proj-row { flex-direction: column; }
  .proj-media { flex: none; max-width: 100%; width: 100%; }
}
</style>

I am a PhD student in the Department of Electrical & Computer Engineering at the University of Washington, advised by Prof. Akshay Gadre and Prof. Shwetak Patel. I received my master’s degree in Information Science from a dual-degree program between the University of Washington and Tsinghua University in 2024. Prior to that, I earned my B.E. in Computer Science from Tsinghua University in 2021, along with a second bachelor’s degree (B.A.) in Product Design.

My research lies at the intersection of **multimodal LLMs** and **human-computer interaction**. I post-train LLMs/VLMs with supervised fine-tuning and reinforcement learning (GRPO) to understand and model human behavior from **eye tracking** and **wearable sensing**, enabling personalized, context-aware AI assistants — for example, modeling human visual search with a VLM ([VLGaze](https://drive.google.com/file/d/1diBcZHLuZOglUQNKuy4ITRXfikHLhld4/view?usp=sharing)) and using gaze as an implicit prompt for LLM personalization ([GazeSummary](https://dl.acm.org/doi/abs/10.1145/3789514.3792037)). I also build benchmarks and retrieval methods for **LLM agents** that reason over long-horizon, heterogeneous, and evolving context: as an Applied Scientist Intern at Microsoft (Copilot, Agents & Platform), I built [PULSE](https://arxiv.org/abs/2611.28374), a benchmark for persistent project-state understanding of enterprise agents. Previously, I worked on gaze-based reading assistance, wearable XR input, and acoustic sensing in the Ubicomp Lab at UW and the Pervasive HCI Lab at Tsinghua University, advised by Prof. Yuanchun Shi and Prof. Yuntao Wang.

**I am looking for research internships (Research Scientist / Applied Scientist) for Summer 2027. Feel free to reach out!**

<img src='/images/research_overview.png' alt='Overview of my research: human behavior modeling with LLMs/VLMs, LLM agents and benchmarks, gaze-aware reading assistants, XR and wearable input, and attention sensing.'>

## Selected Projects

<div class="proj-list">

<div class="proj-row">
  <div class="proj-media"><a href="https://arxiv.org/abs/2611.28374"><img src="/images/projects/pulse.png" alt="PULSE worked example: linking a promise to its fulfillment, project-state snapshots, and an employee's stale view" loading="lazy"></a></div>
  <div class="proj-info">
    <p class="proj-title"><a href="https://arxiv.org/abs/2611.28374">Taking the PULSE of Enterprise Workflows: Evaluating Persistent Project-State Understanding</a></p>
    <p class="proj-authors"><b>Jiexin Ding</b>, Lin Ai, Adam Davies, Scott Counts</p>
    <p class="proj-venue">Preprint, 2026 · Work done at Microsoft</p>
    <p class="proj-desc">A benchmark of 1,573 questions over 30 enterprise project histories testing whether agents know what is still open, what changed, and what each collaborator has (not) seen. Retrieval is the largest bottleneck, but explicit project state adds substantial gains even with gold evidence.</p>
    <p class="proj-links"><a href="https://arxiv.org/abs/2611.28374">Paper</a><a href="/portfolio/portfolio-01-pulse/">Project</a></p>
  </div>
</div>

<div class="proj-row">
  <div class="proj-media"><a href="https://drive.google.com/file/d/1diBcZHLuZOglUQNKuy4ITRXfikHLhld4/view?usp=sharing"><img src="/images/projects/vlgaze.png" alt="VLGaze: a VLM policy samples a group of scanpaths, each rewarded for resembling humans and penalized for resembling other samples" loading="lazy"></a></div>
  <div class="proj-info">
    <p class="proj-title"><a href="https://drive.google.com/file/d/1diBcZHLuZOglUQNKuy4ITRXfikHLhld4/view?usp=sharing">VLGaze: Modeling Human Visual Search with Accuracy and Natural Behavioral Variability</a></p>
    <p class="proj-authors"><b>Jiexin Ding</b>, Xinyun Liu, Ruotong Yu, Zhihan Zhang, Yuntao Wang, Shwetak Patel, Yue Jiang, Akshay Gadre</p>
    <p class="proj-venue">Under review, 2026</p>
    <p class="proj-desc">Post-trains a VLM with SFT and GRPO using a distribution-matching reward. VLGaze achieves state-of-the-art distributional metrics on COCO-Search18 while matching or beating all baselines on accuracy, with a tunable accuracy-variability trade-off.</p>
    <p class="proj-links"><a href="https://drive.google.com/file/d/1diBcZHLuZOglUQNKuy4ITRXfikHLhld4/view?usp=sharing">Paper</a><a href="/portfolio/portfolio-02-vlgaze/">Project</a></p>
  </div>
</div>

<div class="proj-row">
  <div class="proj-media"><a href="https://dl.acm.org/doi/abs/10.1145/3789514.3792037"><img src="/images/projects/gazesummary.png" alt="GazeSummary: a gaze heatmap is fed to an LLM to produce a personalized summary" loading="lazy"></a></div>
  <div class="proj-info">
    <p class="proj-title"><a href="https://dl.acm.org/doi/abs/10.1145/3789514.3792037">GazeSummary: Exploring Gaze as an Implicit Prompt for Personalization in Text-based LLM Tasks</a></p>
    <p class="proj-authors"><b>Jiexin Ding</b>, Yizhuo Zhang, Xinyun Liu, Ke Chen, Yuntao Wang, Shwetak Patel, Akshay Gadre</p>
    <p class="proj-venue">HotMobile 2026</p>
    <p class="proj-desc">Uses gaze as an implicit prompt so LLMs can summarize what the reader actually cared about. Gaze heatmaps outperform other gaze representations and even explicit user prompts at the phrase level, with lower mental effort in a user study.</p>
    <p class="proj-links"><a href="https://dl.acm.org/doi/abs/10.1145/3789514.3792037">Paper</a><a href="/portfolio/portfolio-03-gazesummary/">Project</a></p>
  </div>
</div>

<div class="proj-row">
  <div class="proj-media"><div class="video"><iframe src="https://www.youtube.com/embed/ynx4yIN_hLg" title="Unknown word detection video" loading="lazy" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div></div>
  <div class="proj-info">
    <p class="proj-title"><a href="https://dl.acm.org/doi/full/10.1145/3706598.3714181">Unknown Word Detection for English as a Second Language (ESL) Learners Using Gaze and Pre-trained Language Models</a></p>
    <p class="proj-authors"><b>Jiexin Ding</b>, Bowen Zhao, Yuntao Wang, Xinyun Liu, Rui Hao, Ishan Chatterjee, Yuanchun Shi</p>
    <p class="proj-venue">CHI 2025</p>
    <p class="proj-desc">A gaze-text transformer fused with a pre-trained language model detects unknown words in real time, reaching 97.6% accuracy (71.1 F1) and staying robust on webcam-based gaze.</p>
    <p class="proj-links"><a href="https://dl.acm.org/doi/full/10.1145/3706598.3714181">Paper</a><a href="https://www.youtube.com/watch?v=ynx4yIN_hLg">Video</a><a href="/portfolio/portfolio-1-eyelingo/">Project</a></p>
  </div>
</div>

<div class="proj-row">
  <div class="proj-media"><div class="video"><iframe src="https://www.youtube.com/embed/mz0XIEK4Cz4" title="FlowRing video" loading="lazy" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div></div>
  <div class="proj-info">
    <p class="proj-title"><a href="https://dl.acm.org/doi/full/10.1145/3743706">FlowRing: Integrated Microgesture and Surface Interaction Ring for Versatile XR Input</a></p>
    <p class="proj-authors">Ishan Chatterjee*, <b>Jiexin Ding*</b>, Anandghan Waghmare*, Joseph Breda, Yuquan Deng, Bo Liu, Yuntao Wang, Shwetak Patel</p>
    <p class="proj-venue">MobileHCI 2025</p>
    <p class="proj-desc">A ring fusing an optical flow sensor, contact microphone, and IMU for both microgestures and mouse-grade 2D surface input: 93.6% gesture accuracy across sessions and 90.1% on new users with only four examples.</p>
    <p class="proj-links"><a href="https://dl.acm.org/doi/full/10.1145/3743706">Paper</a><a href="https://www.youtube.com/watch?v=mz0XIEK4Cz4">Video</a><a href="/portfolio/portfolio-2-flowring/">Project</a></p>
  </div>
</div>

<div class="proj-row">
  <div class="proj-media"><div class="video"><iframe src="https://www.youtube.com/embed/S-qsTzXQv2o" title="FaceOri video" loading="lazy" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div></div>
  <div class="proj-info">
    <p class="proj-title"><a href="https://dl.acm.org/doi/10.1145/3491102.3517698">FaceOri: Tracking Head Position and Orientation Using Ultrasonic Ranging on Earphones</a></p>
    <p class="proj-authors">Yuntao Wang*, <b>Jiexin Ding*</b>, Ishan Chatterjee, Farshid Salemi Parizi, Yuzhou Zhuang, Yukang Yan, Shwetak Patel, Yuanchun Shi</p>
    <p class="proj-venue">CHI 2022</p>
    <p class="proj-desc">Tracks head position and orientation with ultrasonic ranging between a device's speaker and earphone microphones: 3.7° median yaw error and 93.5% accuracy in detecting whether the user faces the device.</p>
    <p class="proj-links"><a href="https://dl.acm.org/doi/10.1145/3491102.3517698">Paper</a><a href="https://www.youtube.com/watch?v=S-qsTzXQv2o">Video</a><a href="/portfolio/portfolio-3-faceori/">Project</a></p>
  </div>
</div>

</div>

\* denotes equal contribution. See all papers on the [Publications](/publications/) page.

[Download CV here](/files/Resume_Jiexin_Ding_research_1124.pdf)
