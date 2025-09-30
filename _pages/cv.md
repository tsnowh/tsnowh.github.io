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
* MSc. in Computer Science, University of Toronto, Sept 2024 - Present
  * GPA: 4.0 / 4.0
* BS. in Mathematics, University of Waterloo, Sept 2019 - Dec 2023
  * GPA: 3.86 / 4.0
  * Dean's Honours

Research
======
* University of Waterloo: Undergraduate Research Assistant (URA) 
  * May 2023 - Aug 2023 & Jan 2024 - Apr 2024 $$\cdot$$ Waterloo, Canada
  * Worked under the supervision of [Prof. Kanstantsin Pashkovich](https://kanstantsinpashkovich.bitbucket.io/index.html) and [Prof. Ricardo Fukasawa](https://www.math.uwaterloo.ca/~rfukasaw/).
  * Worked on Online Algorithms for matchings in the adversarial edge arrival model.
  * [Published](https://tsnowh.github.io/publication/WAOA-2025) in the Proceedings of the Workshop on Approximation and Online Algorithms (WAOA), part of ALGO 2025.
  * Gave a 20-minute presentation outlining our work and contributions at ALGO 2025.
  * Research funded by NSERC Undergraduate Student Research Award (USRA) and Mathematics Undergraduate Research Award (MURA).

Work experience
======
* Public Services and Procurement Canada: Data Scientist / Operations Researcher 
  * May 2024 – Aug 2024 $$\cdot$$ Ottawa, Canada
  * Produced a real property report analyzing the predicted occupancy and true benchmark counts.
  * Utilized copulas to model the joint distribution of multiple count types over a multitude of buildings in order to analyze their dependency structure and better predict the true occupancy counts, with data manipulation and analysis done through R.

* Sun Life Financial: Security Developer
  * May 2022 – Aug 2022 $$\cdot$$ Waterloo, Canada
  * Co-developed a library in Java that scans and validates uploaded files for
malicious content, supporting a variety of file types.
  * Coordinated efforts and collaborated with multiple teams and third parties to remediate penetration test findings.
  * Utilized Burp Suite Professional to recreate vulnerabilities and flag false positives.

* Sun Life Financial: Application Security Developer
  * May 2021 – Aug 2021 $$\cdot$$  Waterloo, Canada
  * Developed an extension for Burp Suite Professional using Java and SQLite to
test the security of web applications.
  * Wrote an API using ASP.NET in C\# to check for insecure login credentials.
  * Developed tools in C++ to perform HTTP requests and process the responses.
  
Awards
======
* Ontario Graduate Scholarship (OGS) 2025 ~ $15,000
* Mathematics Undergraduate Research Award (MURA) 2024 ~ $6,000
* NSERC Undergraduate Student Research Award (USRA) 2023 ~ $6,000
* University of Waterloo President Scholarship 2020 ~ $2,000 

Publications
======
Referred Conferences
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
  
