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

I’m Hongpeng Chen, a Ph.D. candidate at The Hong Kong Polytechnic University, researching intelligent robotics and human-robot collaboration. I focus on integrating AI and robotics to build practical, human-centered solutions for smart manufacturing.

# 🔥 Research Interests
- Robot manipulation; 
- Task and motion planning; 
- Robot learning; 
- Robot Dynamics; 
- Simulation-to-Reality (Sim2Real); 
- Vision-Language Model; 
- Human-Robot Collaboration

# 📝 Publications 

## International Refereed Journals
1. **Hongpeng Chen**, Shimin Liu, Zhiyuan Li, Liqiao Xia, David Navarro-Alarcon, Pai Zheng.  
   *GLaM-P: A grounded language model-based multi-agent system for long-horizon robotic task planning in industrial settings.*  
   _IEEE Transactions on Industrial Informatics_ (Under revision).

2. Wenhang Dong, Dongpeng Li, Yuchen Ji, **Hongpeng Chen**, Shimin Liu, Pai Zheng.  
   *Towards a next-generation LLM empowered low-code programming industrial robotic system for human-centric smart manufacturing.*  
   _Journal of Manufacturing System_ (Under revision).

3. **Hongpeng Chen**, Shengzeng Huo, Muhammad Muddassir, Hoi-Yin Lee, Yuli Liu, Junxi Li, Anqing Duan, Pai Zheng, David Navarro-Alarcon.  
   *<a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-TW&user=Zn4ROH4AAAAJ&citation_for_view=Zn4ROH4AAAAJ:2osOgNQ5qMEC" target="_blank">PSO-based optimal coverage path planning for surface defect inspection of 3C components with a robotic line scanner</a>.*  
   _IEEE Transactions on Instrumentation and Measurement_ (2025), accepted. <span class='show_paper_citations' data='Zn4ROH4AAAAJ:2osOgNQ5qMEC'></span>

4. **Hongpeng Chen**, Shufei Li, Junming Fan, Anqing Duan, Chenguang Yang, David Navarro-Alarcon, Pai Zheng.  
   *<a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-TW&user=Zn4ROH4AAAAJ&citation_for_view=Zn4ROH4AAAAJ:UeHWp8X0CEIC" target="_blank">Human-in-the-loop robot learning for smart manufacturing: A human-centric perspective</a>.*  
   _IEEE Transactions on Automation Science and Engineering_ (2025), accepted. <span class='show_paper_citations' data='Zn4ROH4AAAAJ:UeHWp8X0CEIC'></span>

5. **Hongpeng Chen**, Handong Xu, Zhensheng Yang.  
   *<a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-TW&user=Zn4ROH4AAAAJ&citation_for_view=Zn4ROH4AAAAJ:u-x6o8ySG0sC" target="_blank">A novel hybrid method to detect arrival times of elastic waves with low SNR based on Jensen–Shannon divergence and cumulative sum algorithm</a>.*  
   _IEEE Transactions on Instrumentation and Measurement_ 71 (2022): 1–12. <span class='show_paper_citations' data='Zn4ROH4AAAAJ:u-x6o8ySG0sC'></span>

6. **Hongpeng Chen**, Zhensheng Yang.  
   *<a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-TW&user=Zn4ROH4AAAAJ&citation_for_view=Zn4ROH4AAAAJ:u5HHmVD_uO8C" target="_blank">Arrival picking of acoustic emission signals using a hybrid algorithm based on AIC and histogram distance</a>.*  
   _IEEE Transactions on Instrumentation and Measurement_ 70 (2020): 1–8. <span class='show_paper_citations' data='Zn4ROH4AAAAJ:u5HHmVD_uO8C'></span>

## International Refereed Conference Proceedings

1. **Hongpeng Chen**, Shimin Liu, Zhiyuan Li, David Navarro-Alarcon, Pai Zheng.  
   *Multimodal Autonomous Robotic Long-Horizon Task Planning via Embodied Language Model and Behavior Trees.*  
   _2025 IEEE/RSJ International Conference on Intelligent Robots and Systems_ (Accepted).

2. Liqiao Xia, **Hongpeng Chen**, Jiazhen Pang, Shimin Liu, Pai Zheng.  
   *LLM-Augmented multi-Fidelity Bayesian Optimization for Parameter Optimization in Human-Robot Collaborative Assembly.*  
   _2025 IEEE/ASME International Conference on Advanced Intelligent Mechatronics_ (Accepted).

3. Junxi Li, Biao Ma, Tian Hao, Shouwen Wang, **Hongpeng Chen**, Henry Chu.  
   *Semantic Particle Filter Based Graph Matching for Real-Time Global Localization in Large Scale Indoor Environments.*  
   _2026 IEEE International Conference on Robotics & Automation_ (Submitted).

# 💻 Projects

## A Grounded Language Model-Based Framework for Long-Horizon Robotic Planning (2024.07–2025.07)
- Proposed a grounded multi-agent planning framework (GLaM-P) that integrates vision-language models (VLMs) and large language models (LLMs) to enable zero-shot symbolic task planning in industrial environments.
- Developed a VLM-based hierarchical task understanding module and a PDDL-defined skill library, allowing robots to interpret human instructions and generate behavior trees for robust long-horizon task execution.
- Designed an LLM-based zero-shot planning paradigm that translates high-level instructions into executable behavior trees without task-specific training.
- Demonstrated superior performance on five real-world industrial tasks with over 82% success rate, outperforming baseline methods in task success, planning latency, and execution robustness.

## LLM-Empowered Low-Code Drilling System for Human-Centric Smart Manufacturing (2024.07–2025.07)
- Proposed a next-generation low-code programming framework for industrial robots that empowers unskilled operators to perform complex tasks via natural language instructions.
- Designed a multi-agent programming module combining intent recognition, parameter parsing, and human verification, enabling robust interpretation of unstructured commands in real-world manufacturing.
- Integrated a retrieval-augmented generation (RAG) cognitive assistant to reduce operator cognitive load using multi-source knowledge bases, including historical logs, safety manuals, and real-time environmental data.
- Verified the system through an aircraft panel drilling case study, demonstrating that untrained workers could complete precision tasks reliably and efficiently using voice-based LLM interaction.

## LLM-Augmented Bayesian Optimization in Human-Robot Collaborative Assembly (2024.05–2025.01)
- Proposed a multi-fidelity Bayesian optimization framework that incorporates a large language model (LLM) as a physics-informed low-fidelity surrogate, aiming to reduce the need for expensive high-fidelity experiments in human-robot collaborative assembly (HRCA).
- Designed a latent variable Gaussian process (LVGP) to link LLM predictions with high-fidelity simulations, enabling residual-based uncertainty quantification and enhancing optimization robustness across fidelity levels.
- Implemented an iterative prompt engineering mechanism and variance-controlled LLM querying to reduce hallucination risk, systematically improving the physical reasoning quality of the low-fidelity model.
- Demonstrated the effectiveness of the proposed framework through a robotic drilling task in aircraft cabin assembly.

## Semantic Particle Filter Based Graph Matching for Real-Time Global Localization (2024.03–2024.12)
- Proposed a particle filter-based global localization framework that leverages 3D semantic graph matching to address repeated topological features and local optima in large-scale indoor environments.
- Introduced a dual-strategy semantic label utilization framework, combining object-level histogram descriptors and topological constraints to improve matching robustness and particle weight updating.
- Integrated graph-matching-derived motion models with adaptive particle filtering, enhancing real-time pose estimation accuracy and convergence speed under sparse or ambiguous observations.
- Validated on a real-world campus dataset, demonstrating superior accuracy and efficiency over baseline methods (e.g., Histogram-based, X-View, BoW).

## A Survey on Human-in-the-Loop (HITL) Robot Learning for Smart Manufacturing (2023.09–2024.03)
- Proposed a unified human-centric HITL framework that integrates human perception, cognition, behavior, and empathy to enhance robot learning and decision-making in dynamic manufacturing environments.
- Categorized human roles in the training loop (operator, collaborator, supervisor) and introduced a four-level HITL taxonomy to systematically describe how humans contribute to robot learning processes.
- Outlined future challenges such as sim-to-real transfer, multi-agent learning, BCI-controlled robots, and embodied intelligence integration with LLMs for Industry 5.0.

## Optimization-Based Control for Ultrasound-Guided Scoliosis Assessment (2022.10–2023.06)
- Developed a real-time ultrasound-guided robotic system for scoliosis assessment using an optimization-based control framework, formulated as a constrained quadratic programming (QP) problem.
- Incorporated variable impedance regulation into the control loop, with gains learned from human demonstrations using GMM/GMR, enabling safe and adaptive physical human-robot interaction.
- Validated the proposed system through both simulation and experiments on spine phantoms and human subjects.

## A Robotic Line Scan System to Automatically Perform Visual Inspection Tasks (2021.10–2022.10)
- Developed a robotic inspection framework combining line-scan imaging with a PSO-based optimal coverage path planning method for surface defect detection on 3C free-form components.
- Introduced a hybrid region segmentation algorithm using RANSAC and enhanced K-means clustering with curvature features for accurate local scanning path definition.
- Implemented an adaptive region-of-interest (ROI) strategy for generating local scanning paths, and formulated a global inspection path as a constrained traveling salesman problem solved by particle swarm optimization to minimize inspection time.
- Validated the proposed method through simulation and real-world experiments on 3C components.


# 🎖 Honors and Awards
- **PolyU Postgraduate Research Scholarship** (2023–2026)
- **PolyU Departmental MSc Dissertation Scholarship** (2022) – HK$60,000
- **Outstanding Undergraduate Thesis Award** (2020)
- **Shanghai Maritime University Outstanding Graduate** (2020)

# 📖 Educations
- **The Hong Kong Polytechnic University**  
  Ph.D. in Industrial and Systems Engineering (Sep 2023 – Aug 2026, expected)  
  Advisor: Prof. Pai Zheng & Prof. David Navarro-Alarcon

- **The Hong Kong Polytechnic University**  
  MSc. in Mechanical Engineering (Sep 2021 – Jun 2023)  
  Advisor: Prof. David Navarro-Alarcon

- **Shanghai Maritime University**  
  BEng. in Mechanical and Electronic Engineering (Sep 2016 – Jun 2020)  
  GPA: 3.48/4.0 — Ranking 3/72 (Top 5%)  
  Advisor: Dr. Zhensheng Yang

# 💻 Professional Skills 
- **Theory:** Pattern Recognition and Computer Vision, Deep Learning, Optimal Control Theory, Signal Processing, Dynamics of Robot Manipulators, Vision-Language Model, Large Language Model
- **Programming:** C++, Python, Matlab
- **Model and Analysis:** SolidWorks, ANSYS
- **Robotics:** Ubuntu, ROS, Universal Robots, PyTorch
- **3D Vision:** OpenCV, RGB-D Camera, Point Cloud Library (PCL)
- **Others:** Linux, LaTeX

# 📝 Professional Service
- **Session Chair**
  - 2023 PolyU ISE Research Student Conference
  - 2024 PolyU ISE Research Student Conference

- **Teaching Assistant**
  - ISE2001 Introduction to Enterprise
  - ISE430 New Product Planning and Development
  - ISE512 Warehousing & Material Handling System

- **Technical Reviewer**
  - Robotics and Computer-Integrated Manufacturing
  - Journal of Intelligent Manufacturing
  - Journal of Field Robotics
  - IEEE/ASME International Conference on Advanced Intelligent Mechatronics (AIM)
  - IEEE International Conference on Robotics and Biomimetics (ROBIO)
  - NAMRI/SME North American Manufacturing Research Conference (NAMRC)