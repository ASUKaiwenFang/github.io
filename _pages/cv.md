---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Industrial Engineering, Arizona State University, Tempe, AZ, Aug 2022 - Present
* Master of Financial Mathematics, Minor in Industrial Engineering, University of Minnesota, Minneapolis, MN, Sep 2020 - May 2022
* Bachelor of Economics, Southwestern University of Finance and Economics, Chengdu, China, Sep 2015 - Jun 2019

Teaching Experience
======
* Arizona State University
  * Instructor, IEE 506: Computing for Data-Driven Optimization, Spring 2026
  * Teaching Assistant, IEE 506: Computing for Data-Driven Optimization, Spring 2025
  * Lab Instructor, IEE 376: Operations Research - Deterministic Techniques and Applications, Fall 2024
  
Skills
======
* **Programming Languages**: Python, Julia, MATLAB, C#, R, MS Office

Awards
======
* SCAI Doctoral Fellowship, Spring 2023/2024/2025
* IE Travel Fellowship, Fall 2024
* Experiential Learning Grant, Fall 2024

Projects
======
* **Disjunctive Benders Decomposition** (Jan 2024 - Present)
  * Advisor: Dr. Geunyeong Byeon
  * Develop a new Benders decomposition algorithm that can handle disjunctive constraints
  * Implement the algorithm in Julia and test it on a variety of benchmark problems

* **Differentially Private Federated Learning with James-Stein Estimator** (Jun 2024 - Present)
  * Advisor: Dr. Minseok Ryu, Dr. Geunyeong Byeon
  * Develop a new differentially private federated learning algorithm
  * Implement the algorithm in Python and test it on a variety of benchmark problems

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

Presentations
======
* **K. Fang** and G. Byeon. Benders Lift-and-Project Cuts. *INFORMS Annual Meeting, Seattle, Washington,* October 2024.
* **K. Fang** and G. Byeon. Strengthening Benders Cuts via Disjunction. *The 25th International Symposium on Mathematical Programming (ISMP), Montréal, Canada,* July 2024.
* **K. Fang** and G. Byeon. Accelerating Benders Decomposition via Exploration. *INFORMS Annual Meeting, Phoenix, Arizona,* October 2023.
