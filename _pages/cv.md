---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV (PDF)](/files/Resume_Jiexin_Ding_research_1124.pdf)

Research Interests
======
My research lies at the intersection of **multimodal LLMs** and **human-computer interaction**. I post-train **LLMs/VLMs** with **SFT** and **reinforcement learning** to understand and model human behavior from **eye tracking** and **wearable sensing**, enabling **personalized**, **context-aware** AI assistants. I also build benchmarks and retrieval methods for **LLM agents** that reason over long-horizon, heterogeneous, and evolving context.

Education
======
* **Ph.D. in Electrical & Computer Engineering**, University of Washington, Sept. 2024 – Present
* **Master of Science in Technology Innovation**, University of Washington, Sept. 2022 – Mar. 2024
* **Master of Engineering in Data Science and Information Technology (with Honors)**, Tsinghua University, Sept. 2021 – June 2024
* **Bachelor of Engineering in Computer Science and Technology**, Tsinghua University, Sept. 2017 – June 2021
* **Bachelor of Arts in Product Design (Second Major)**, Tsinghua University, Sept. 2018 – June 2020

Experience
======
* **Applied Scientist Intern**, Microsoft, Copilot, Agents & Platform, Redmond, WA (June 2026 – Sept. 2026)
  * Built **PULSE**, a benchmark for persistent project-state understanding of enterprise agents with 1,573 questions based on the HERB corpus, covering open loops, project evolution, and team-vs-individual view gaps. [[Paper]](https://arxiv.org/abs/2611.28374)
  * Benchmarked ReAct agents, graph/memory-augmented retrieval, long-context, and oracle settings; showed retrieval is the largest bottleneck (F1 31.4 → 66.9 with gold evidence), while explicit state construction adds further gains (78.1), and cross-source and perspective-dependent reasoning remain hard.
  * Designed a **Workstream Graph** retriever that improved gold-evidence recall by +22.7 and answer quality by +4.9 compared to the RAG baseline with the same token budget.

* **Research Assistant**, Ubicomp Lab & NEWT Lab, University of Washington (Sept. 2024 – Present)
  * Advisors: Prof. Shwetak Patel, Prof. Akshay Gadre
  * Proposed **VLGaze**, post-training a VLM with SFT and GRPO using a novel distribution-matching reward that rewards human-like scanpaths while penalizing intra-group similarity, to model human visual search. [[Paper]](https://drive.google.com/file/d/1diBcZHLuZOglUQNKuy4ITRXfikHLhld4/view?usp=sharing)
  * Achieved SOTA on distributional metrics while matching or beating all baselines on accuracy, the first method to do both on COCO-Search18, with a tunable accuracy-variability trade-off.
  * Used gaze as an **implicit prompt** for LLM personalization: gaze heatmaps outperformed explicit user prompts, and a fine-tuned lightweight 3B gaze-aware LLM matched Gemini 2.0 on personalized summarization. [[Paper]](https://dl.acm.org/doi/abs/10.1145/3789514.3792037)
  * Detecting users' cognitive states from physiological signals during LLM use to enable adaptive interaction.

* **Machine Learning Engineer Intern**, AnalyticDB, Alibaba Cloud, Beijing, China (June 2024 – Sept. 2024)
  * Developed a churn prediction model using a Behavior Sequence Transformer on large-scale user behavior logs.
  * Built distributed training and inference pipelines using DeepSpeed and Triton on cloud.

* **Research Assistant**, Ubicomp Lab, University of Washington (Sept. 2022 – Mar. 2024)
  * Advisor: Prof. Shwetak Patel
  * Led **FlowRing**, an XR input ring supporting both microgestures and mouse-grade 2D surface input.
  * Designed and trained a multimodal model fusing optical flow, contact-microphone, and IMU signals, achieving 93.6% microgesture accuracy across sessions and 90.1% on unseen users with only four examples. [[Paper]](https://dl.acm.org/doi/full/10.1145/3743706)
  * Built a real-time music-player demo showing context-aware subtle input with a sensing ring (UIST 23 Best Demo). [[Paper]](https://dl.acm.org/doi/10.1145/3586182.3615809)

* **Research Assistant**, Pervasive HCI Lab, Tsinghua University (June 2020 – June 2024)
  * Advisors: Prof. Yuanchun Shi, Prof. Yuntao Wang
  * Built a gaze-text multimodal transformer fused with a pre-trained language model (RoBERTa) to detect unknown words for ESL learners, reaching 97.6% accuracy and staying robust on webcam gaze. [[CHI 25]](https://dl.acm.org/doi/full/10.1145/3706598.3714181) [[CHI EA 23]](https://dl.acm.org/doi/10.1145/3544549.3585790)
  * Built earbud-based ultrasonic head tracking robust to low SNR, achieving 3.7° median yaw error and 93.5% accuracy in detecting device-facing attention. [[Paper]](https://dl.acm.org/doi/10.1145/3491102.3517698)

* **Teaching Assistant**, Global Innovation Exchange, Tsinghua University (Autumn 2022)
  * Essentials to Signal Processing and Data Management for AIoT Applications

Publications
======
\* denotes equal contribution.
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors
======
* Outstanding Graduate (Top 2%), Tsinghua University, 2024
* Jury Best Demo Award, UIST, 2023
* Excellent Comprehensive Scholarship, Tsinghua University, 2023
* China National Scholarship (Top 0.2%), 2022
* Fellowship (Top 10 in Beijing in the National College Entrance Exams), Tsinghua University, 2017

Skills
======
* **Languages**: Python, C/C++, Java, JavaScript, TypeScript, HTML/CSS
* **ML & LLM**: PyTorch, TensorFlow, TRL, PEFT/LoRA, CUDA, scikit-learn
* **Methods**: LLM/VLM Post-training (SFT, GRPO), LLM Agents (ReAct, Tool Use), RAG, Vector Search, Prompt Engineering, Transformers, Time-Series & Sensor Fusion, Eye Tracking, User Studies
* **Systems & Tools**: Linux, Git, Docker, React, Node.js, Unity, BLE, Embedded C (nRF52)
* **Prototyping**: Soldering, 3D Printing, Laser Cutting, 3D Modeling (Rhino, SketchUp)
