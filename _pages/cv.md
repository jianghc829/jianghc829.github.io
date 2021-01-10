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
* M.S. in Computer Science, University of Washington, Dec 2021 (expected)
* M.S. in Mechanical Engineering, Brown University, May 2020
* M.S. in Mechanical Engineering, Washington State University, May 2018

Work experience
======
* 2018 - 2020: Graduate Research Assistant
  * Brown University
  * Responsibilities: 
    * Performed research on water wave physics
    * Designed and built a tunable water wave generator (vertical shaker) and a high-speed imaging system for the PIV
    * Adapted an open-source PIV package MatPIV to process experimental results; The new data pipeline not only can reconstruct 3D waves but also can measure 2D flow on the water surface
    * Analysed the relationship between water wave (amplitude, frequency, viscosity, etc) and vibration source using a home-made PIV system
  * Supervisor: Prof. Daniel Harris

* 2016 - 2018: Graduate Research Assistant
  * Washington State University
  * Responsibilities:
    * Developed a fast one-dimensional simulation of inkjet using MATLAB
    * Built a low cost and robust inkjet visualization system with a high-speed imaging technique
    * Created an image processing pipeline to obtain droplet properties from experimental results
    * Presented results at academic conferences and published two peer-reviewed articles
  * Supervisor: Prof. Hua Tan

* 2013 - 2016: SAP Specialist
  * State Grid Corporation of China
  * Responsibilities:
    * Established SAP Material Management module and Project Process module for the company
    * Maintained SAP ERP system and trained new SAP users
    * Created monthly, seasonal, and annual procurement plan and strategies
  * Supervisor: Dr. Wei Du
  
Skills
======
* **Programming Languages:** `Java` `Python` `MATLAB` `Go` `C/C++` `Bash` `SQL`
* **Web/Mobile Development:** `React` `Node.js` `JavaScript/HTML/CSS` `Apache Tomcat` `Elasticsearch`
* **Deployment:** `Amazon Web Services (AWS)` `Google Cloud Platform (GCP)` `Git` `Docker` `Kubernetes`

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Download PDF version [link](http://jianghc829.github.io/files/resume.pdf "here")
