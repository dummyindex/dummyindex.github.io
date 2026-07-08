---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p>A one-page PDF résumé is available on request. Full publication list on the <a href="/publications/">Publications</a> page.</p>

Education
======
* **Ph.D. in Computational Biology**, Joint CMU–Pitt Ph.D. Program in Computational Biology (CPCB), 2019–2025 (thesis defended November 2025)
  * Program spans Carnegie Mellon's School of Computer Science (2019–2020) and the University of Pittsburgh School of Medicine (2021 onward), within the joint program.
  * Collaborated with the Xing lab and the Xu lab on live-cell imaging and cryo-EM deep-learning research.
* **M.S. in Computer Science**, University of California, Santa Barbara, 2017–2019
  * Research focus on natural language processing and understanding.
* **B.S. in Computer Science**, University of California, Santa Barbara, 2015–2017
  * Major GPA 3.96/4.00; Dean's Honors 2015–2017.

Experience
======
_Descriptions are kept intentionally brief; details available on request._

* **Amazon**, Applied Scientist, Seattle, WA (2026–Present)
  * Multimodal and large language models; mechanistic interpretability; generative AI for data efficiency and robustness.
* **Independent Research, Agentic Systems** (self-funded), Remote (2024–2025)
  * Built LLM-in-a-loop multi-agent systems, including a tool-use code agent, progressing toward FARS.
* **Carnegie Mellon University & University of Pittsburgh**, Research Assistant, Pittsburgh, PA (2019–2025)
  * Deep-learning computer-vision frameworks for live-cell imaging (LivecellX, LivecellAction); open-source contributions.
* **Shanghai Ragamuffin Networks Inc.**, Engineering Lead, Shanghai, China (2020–2021)
  * Led delivery of a cloud-based operations platform.
* **FusionTech** (Startup), Co-Founder / ML Research Engineer, China (2020)
  * AI-driven medical imaging diagnostics; the startup was later acquired.
* **University of California, Santa Barbara**, Research / Teaching Assistant, Santa Barbara, CA (2016–2017)
  * NLP research with Prof. William Yang Wang; TA for parallel computing, C++, and a graduate deep-learning course.
* **Arista Networks**, Software Engineer Intern, Santa Clara, CA (2017)
* **UCSB L&S IT**, Software Engineering Intern, Santa Barbara, CA (2016)

Selected Publications
======
<ul>{% for post in site.publications reversed %}
  {% if post.category == 'selected' %}
    {% include archive-single-cv.html %}
  {% endif %}{% endfor %}</ul>

See the [Publications](/publications/) page for the complete list, including co-authored papers.

Skills & Training
======
* **Research areas:** Multimodal models (MLLMs/VLMs), large language models, mechanistic interpretability, reinforcement learning & post-training (SFT, PEFT, RLHF/RLAIF), computer vision, natural language processing, agentic systems, computational genomics.
* **Graduate coursework:** reinforcement learning, machine learning, probabilistic graphical models, evolution dynamics modeling, computational genomics (CMU); structural biology, protein structure prediction, biophysics (Pitt).
* **Master's coursework:** parameterized algorithms, quantum computing, advanced linear algebra, numerical analysis, cryptoengineering, computer graphics, augmented reality, distributed systems, graph/network analysis, computer vision, NLP, runtime systems, FPGA (Vivado, VHDL).

Awards & Service
======
See the [Service & Activities](/service/) page for talks, awards, and professional involvement.
