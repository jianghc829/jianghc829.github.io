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
* M.S. in Computer Science, University of Washington, Jun 2022 (expected)
* M.S. in Mechanical Engineering, Brown University, May 2020
* M.S. in Mechanical Engineering, Washington State University, May 2018

Work experience
======
* 2021 - present: Software Engineering Intern
  * The MathWorks Inc
  * Supervisor: Dr. Yan Gu
  * Responsibilities: 
    * Refactored an internal infrastructure tool Dashy using theReact, Node.Js, and MySQL
    * Dashy is a web application that allows MathWorks staffs to collect, browse and demonstrate a range of internal figures in a dashboard
    * Used a session-based SSO authentication system to handle user login and log-out
    * Used agile, scrum, and Jira to manage the software development

* 2018 - 2020: Graduate Research Assistant
  * Brown University
  * Supervisor: Prof. Daniel Harris
  * Responsibilities: 
    * Performed research on water wave physics
    * Designed and built a tunable water wave generator (vertical shaker) and a high-speed imaging system for the PIV
    * Adapted an open-source PIV package MatPIV to process experimental results; The new data pipeline not only can reconstruct 3D waves but also can measure 2D flow on the water surface
    * Analysed the relationship between water wave (amplitude, frequency, viscosity, etc) and vibration source using a home-made PIV system

* 2016 - 2018: Graduate Research Assistant
  * Washington State University
  * Supervisor: Prof. Hua Tan
  * Responsibilities:
    * Developed a fast one-dimensional simulation of inkjet using MATLAB
    * Built a low cost and robust inkjet visualization system with a high-speed imaging technique
    * Created an image processing pipeline to obtain droplet properties from experimental results
    * Presented results at academic conferences and published two peer-reviewed articles

* 2013 - 2016: SAP Specialist
  * State Grid Corporation of China
  * Supervisor: Dr. Wei Du
  * Responsibilities:
    * Established SAP Material Management module and Project Process module for the company
    * Maintained SAP ERP system and trained new SAP users
    * Created monthly, seasonal, and annual procurement plan and strategies
  
Skills
======
* **Programming Languages:** `Java` `Python` `JavaScript` `Ruby` `MATLAB` `Go` `C++` `Bash` `SQL`
* **Web Development:** `React` `Node.js` `Bootstrap` `Rails` `Apache Tomcat` `Spring Boot` `Elasticsearch`
* **Deployment:** `AWS` `GCP` `Git` `Docker` `Kubernetes` `HAProxy` `CircleCI`

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Download PDF version [here](http://jianghc829.github.io/files/resume.pdf "Resume PDF")
