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


Hi there! I’m a founding research engineer at General Robotics, focusing on robot learning methods that enable generalizable manipulation across diverse robot form-factors including arms, mobile manipulators, and humanoids.

Prior to General Robotics, I did my Master's in Robotics at Robotics Institute, Carnegie Mellon University. I was advised by Prof. Katerina Fragkiadaki and my research focused on enabling embodied agents to learn from internet-scale data.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News

- Sept, 2025: Released our work [DreamControl](https://www.generalrobotics.company/post/dreamcontrol-building-humanoid-ai-skills) on leveraging large-scale human motion datasets for humanoid whole-body skill learning.
- June, 2025: Released [TrossenAI](https://www.generalrobotics.company/post/trossen-robots-on-grid) bimanual mobile manipulators with pick-and-place manipulation skill into GRID. 
- March, 2025: Served as a TA in GRID Workshop at Nvidia GTC’25 in San Jose.
- Dec, 2024: Co-developed [GRID-Isaac](https://x.com/genrobotics_ai/status/1892250420711481524) on OpenGRID platform serving 3000+ active users, multiple enterprise clients.
- July, 2024: Joined General Robotics to work on robot learning, manipulation and humanoids.
- June, 2024: Presented ODIN at CVPR in Seattle, WA.
- May, 2024: Presented Gen2Sim at ICRA in Yokohama, Japan.
- February, 2024: Our work ODIN: A Single Model for 2D and 3D Perception accepted at CVPR 2024.
- January, 2024: Our work Gen2Sim: Scaling up Robot Learning in Simulation with Generative Models accepted at ICRA 2024.
- November, 2023: Served as a reviewer at CVPR 2024, ICRA 2024, ICLR 2024.
- November, 2023: Volunteered at CoRL 2023. Presented Gen2Sim in Towards Generalist Robots Workshop at CoRL 2023.
- August, 2022: Joined Carnegie Mellon University for MS in Robotics.
- July, 2021: Our work RTVS accepted at IRoS 2021.
- Aug, 2020: Our work DeepMPCVS accepted at CoRL 2020.
- October, 2019: Attended Google Summer of Code Mentor Summit in Munich, Germany.
- May, 2018: Joined JdeRobot - Universidad Rey Juan Carlos for Google Summer of Code program.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/dreamcontrol.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DreamControl: Human-Inspired Whole-Body Humanoid Control for
Scene Interaction via Guided Diffusion](https://genrobo.github.io/DreamControl/)

Dvij Kalaria, Sudarshan S Harithas, **Pushkal Katara**, Sangkyung Kwak, Sarthak Bhagat, Shankar Sastry, Srinath Sridhar, Sai Vemprala, Ashish Kapoor, Jonathan Chung-Kuan Huang

[**Website**](https://genrobo.github.io/DreamControl/) <strong> | [**Code**](https://github.com/GenRobo/DreamControl/tree/main) | [**Arxiv**](https://arxiv.org/abs/2509.143536)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/odin-teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ODIN: A Single Model for 2D and 3D Perception](https://odin-seg.github.io/)

Ayush Jain, **Pushkal Katara**, Nikolaos Gkanatsios, Adam W. Harley,
Gabriel Sarch, Kriti Aggarwal, Vishrav Chaudhary, Katerina Fragkiadaki

[**Website**](https://odin-seg.github.io/) <strong> | [**Code**](https://github.com/ayushjain1144/odin) | [**Arxiv**](https://arxiv.org/abs/2401.02416)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='images/ap.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Gen2Sim: Scaling up Robot Learning in Simulation with Generative Models](https://gen2sim.github.io/)

**Pushkal Katara**, Zhou Xian, Katerina Fragkiadaki

<!-- [**Website**](https://gen2sim.github.io/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
[**Website**](https://gen2sim.github.io/) <strong> | [**Code**](https://github.com/pushkalkatara/Gen2Sim) | [**Arxiv**](https://arxiv.org/abs/2310.18308)

- Generation to Simulation (Gen2Sim), a method for scaling up robotic skill learning in simulation.

- Leverages foundational generative models of image and language to scale up simulation environments, tasks and demonstrations.

</div>
</div>

- [**IRoS 2021**] [RTVS: Deep Model Predictive Control for Visual Servoing](https://ieeexplore.ieee.org/document/9636290) <br>
**Pushkal Katara**, M. Nomaan Qureshi, Abhinav Gupta, Harit Pandya, Y V S Harish, K. Madhava Krishna

- [**CoRL 2020**] [DeepMPCVS: Deep Model Predictive Control for Visual Servoing](https://arxiv.org/abs/2105.00788) <br>
**Pushkal Katara**, Y V S Harish, Harit Pandya, Abhinav Gupta, Madhava Krishna K

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *Aug 2022 - June 2024*, Masters of Science in Robotics, Carnegie Mellon University.
- *Aug 2016 - May 2020*, Bachelors of Technology in Computer Science, SRM University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->