---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a class="btn btn--primary" href="{{ base_path }}/cv/CV_Nguyen_Ngoc_Hung_updated_2026.pdf" target="_blank"><i class="fas fa-file-pdf" aria-hidden="true"></i> Download full CV (PDF)</a></p>

Research Interests
======

* **Edge and networked systems:** mobile edge computing, cloud/edge computing, IoT, XR systems, deadline-aware task offloading and scheduling
* **AI for systems and networking:** machine learning, deep learning and deep reinforcement learning for resource allocation, optimization and intelligent control
* **Algorithms and optimization:** greedy methods, graph-based algorithms, metaheuristics and evolutionary computation

Education
======

<div class="cv-entry">
  <div class="cv-entry__head"><span class="cv-entry__org">Lund University</span><span class="cv-entry__date">2025 – 2029</span></div>
  <div class="cv-entry__role">Ph.D. in Electrical and Information Technology · Lund, Sweden</div>
  <ul>
    <li>Research topic: Algorithms for XR in 6G networks</li>
    <li>Supervisor: Prof. Björn Landfeldt</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry__head"><span class="cv-entry__org">Hanyang University</span><span class="cv-entry__date">09/2021 – 02/2024</span></div>
  <div class="cv-entry__role">M.Sc. in Electrical and Electronic Engineering · Ansan, South Korea</div>
  <ul>
    <li>Thesis: <a href="https://repository.hanyang.ac.kr/handle/20.500.11754/188311" target="_blank"><em>Offloading under Hard Deadline Constraints in Mobile Edge Computing</em></a></li>
    <li>Supervisor: Prof. Sang-Woon Jeon</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry__head"><span class="cv-entry__org">Hanoi University of Science and Technology</span><span class="cv-entry__date">09/2013 – 08/2018</span></div>
  <div class="cv-entry__role">Bachelor of Engineering · Hanoi, Vietnam</div>
  <ul>
    <li>Thesis: <em>Applied Numerical Methods in Chemical Engineering</em></li>
    <li>Supervisors: Prof. Nguyen Dang Binh Thanh and Prof. Bui Minh Dinh</li>
  </ul>
</div>

Work Experience
======

<div class="cv-entry">
  <div class="cv-entry__head"><span class="cv-entry__org">Lund University</span><span class="cv-entry__date">2025 – Present</span></div>
  <div class="cv-entry__role">Doctoral Researcher, Department of Electrical and Information Technology · Lund, Sweden</div>
  <ul>
    <li>Research on algorithms for XR and edge computing in 6G systems.</li>
    <li>Teaching duty (20%): teaching assistant for <em>Computer Communication</em> (2025, 2026) and <em>Computer Architecture</em> (2026).</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry__head"><span class="cv-entry__org">Phenikaa University</span><span class="cv-entry__date">2025 – Present</span></div>
  <div class="cv-entry__role">Researcher and Lecturer, School of Computing (on temporary leave) · Hanoi, Vietnam</div>
  <ul>
    <li>Taught undergraduate courses in <em>Cloud Computing</em>, <em>Computer Architecture</em> and <em>Data Processing with Python</em>.</li>
    <li>Supervised and conducted research with students in the ICNL Lab.</li>
    <li>Contributed to research in networked systems, optimization and applied AI.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry__head"><span class="cv-entry__org">VinUniversity</span><span class="cv-entry__date">03/2024 – Present</span></div>
  <div class="cv-entry__role">Research Assistant · Hanoi, Vietnam</div>
  <ul>
    <li>Research on intelligent transportation systems using metaheuristics and deep reinforcement learning.</li>
    <li>Investigated AI- and IoT-enabled solutions for aquaculture and smart monitoring applications.</li>
    <li>Collaborated on interdisciplinary projects combining optimization, intelligent control and cyber-physical systems.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry__head"><span class="cv-entry__org">FPT Software</span><span class="cv-entry__date">01/2024 – 12/2024</span></div>
  <div class="cv-entry__role">Senior AI Engineer, AI Center · Hanoi, Vietnam</div>
  <ul>
    <li>Applied model quantization to image classification and object detection models, including ResNet, SSD-ResNet and DETR-based models.</li>
    <li>Developed quantized inference pipelines using QAT, PTQ and TVM-based CPU deployment.</li>
    <li>Benchmarked AI models for latency, efficiency and deployment feasibility.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry__head"><span class="cv-entry__org">Hanyang University</span><span class="cv-entry__date">09/2021 – 02/2024</span></div>
  <div class="cv-entry__role">Research Assistant · Ansan, South Korea</div>
  <ul>
    <li>Research in wireless communications and mobile edge computing.</li>
    <li>Applied deep learning and reinforcement learning to task offloading and scheduling problems.</li>
    <li>Designed greedy and learning-based algorithms for resource allocation in MEC systems; co-inventor of a patent on deadline-constrained job scheduling.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry__head"><span class="cv-entry__org">LG Electronics</span><span class="cv-entry__date">10/2018 – 07/2021</span></div>
  <div class="cv-entry__role">Senior Embedded Engineer · Hanoi, Vietnam</div>
  <ul>
    <li>Developed Wi-Fi middleware as part of the Wi-Fi core framework for embedded platforms.</li>
    <li>Implemented SPI middleware components and supporting modules for device-level integration.</li>
    <li>Wrote unit tests with Google Test and built internal tools for automated C/C++ unit-test generation.</li>
    <li>Built testing and performance-analysis tools with Qt Creator on Windows.</li>
    <li>Developed algorithms for camera sharpness evaluation, autofocus and low-contrast brightness enhancement.</li>
  </ul>
</div>

Honors and Awards
======

* Third Prize, Student Research Award, Hanoi University of Science and Technology (2017 – 2018)

Skills
======

* **Programming:** Python, C/C++, CUDA C++, MATLAB
* **Machine learning:** PyTorch, TensorFlow, NumPy, Pandas
* **Research areas:** mathematical modeling, numerical methods, optimization, mobile edge computing, (deep) reinforcement learning
* **Languages:** Vietnamese (native), English (fluent)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Academic Service
======

* Journal reviewer (20+ reviews): IEEE Internet of Things Journal, IEEE Communications Letters, IEEE Transactions on Intelligent Transportation Systems, Computer Networks, Computer Communications
