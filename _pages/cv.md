---
layout: archive-no-title
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume/
  - /resume.html
---

{% include base_path %}

## Education
------

<img style="float: right;" src="/images/berkeley.png" width="110" height="110"/> 
**University of California, Berkeley**<br>
M.Eng. Bioengineering<br>
*Bioinformatics & Computational Biology Concentration*<br>
*August 2019 - May 2020*
* GPA: 3.86
* Relevant Courses: 
  * Machine Learning in Computational Biology
  * Probabilistic Modeling in Computational Biology
  * Advanced Orthopedic Biomechanics
  * Clinical Need-Based Therapy Solutions
  * Communications for Engineering Leaders
  * Project Management & Teaming
  * Coaching for High Performance Teams
  * R&D Technology Management
  
<img style="float: right;" src="/images/rutgers.png" width="110" height="110"/> 
**University of Rutgers, New Brunswick**<br>
B.S. Biomedical Engineering<br>
*Computer Science Minor*<br>
*September 2015 - May 2019*
* GPA: 3.53
* Relevant Courses: 
  * Advanced Biomedical Devices
  * Musculoskeletal Mechanics
  * Cardiovascular Engineering
  * Biomaterials
  * Biomechanics
  * Genetics
  * Biomedical Transport Phenomena
  * Numerical Modeling in Biomedical Systems
  * Intro to Data Science
  * Software Methodology
  * Data Structures
  * Principles of Information & Data Management


## Work Experience
------

<img style="float: right;" src="/images/evolution.png" width="220" height="200"/> 
**Evolution Devices**<br>
R&D Engineer, Capstone Team Leader<br>
*September 2019 - May 2020*<br>
*Berkeley, CA*
* Managed interdisciplinary capstone team, set objectives and deadlines for team
* Developed protocols and ran experiments on neurological patients to collect kinematic, EMG, and IMU data
* Trained machine learning classifier with Python and TensorFlow able to differentiate 6 gaits with 87% accuracy
* Ebmedded CNN on Adafruit BLE microcontroller using TFLite and Arduino IDE for real-time model inference
* Increased 3D gait metrics detected by 225% using rotational matrices for a 4 camera motion-tracking system 

<img style="float: right;" src="/images/alcyone.jpg" width="220" height="180"/> 
**Alcyone Lifesciences**<br>
R&D Intern<br>
*June 2018 - August 2018*<br>
*Lowell, MA*
* Created test system for catheter membrane burst pressures in SolidWorks, generated pressure data in LabVIEW 
* Developed fixtures for 3D-printed spinal models and pump housing with SolidWorks
* Wrote an ImageJ plugin in Java using image processing to record drug concentration over time in spinal models
* Documented design changes, generated test procedure documents, gave oral presentations on updates

<img style="float: right;" src="/images/rutgersbme.jpg" width="220" height="200"/> 
**Yarmush Lab, Rutgers Biomedical Engineering**<br>
Research Assistant<br>
*June 2017 - June 2018*<br> 
*Piscataway, NJ* 
* Optimized polymeric nanoparticle production, decreasing particle size by 78% and assembly time by 71%
* Created MATLAB model to predict expected protein diffusion from nanoparticles
* Trained students on new protocols and GLP, presented findings at university research symposiums
* Presented research project *"Nanoparticle formulations for drug delivery of immunomodulatory compounds"*


## Skills
------

**Programming**
Python, MATLAB, Java, SQL, Arduino, Bash

**Software**
SolidWorks, LabVIEW, ImageJ, Microsoft Suite

**Libraries**
TensorFlow, Keras, NumPy, Pandas, SciPy

**Technical**
Biomechanics, IMU, EMG, Signal Processing, 3D Printing

**Development**
Rapid Prototyping, Statistical Analysis, Verification Testing, ISO 13485, FDA QSR

**General**
Communication, Leadership, Project Management, Technical Writing, Teamwork


## Organizations
------

* Delta Upsilon International Fraternity, Rutgers
  * President, 2017-2018
  * VP of Academic Excellence, 2016-2017

* Tewksbury First Aid & Rescue Squad, Tewksbury, NJ
  * Volunteer EMT-B, 2013-2017


## Awards
------

* Fung Excellence Scholar, UC Berkeley
* NSF/SB3C Undergraduate Design Competition Finalist, 2019
* Magna Cum Laude, Rutgers 2019
* Biomedical Engineering Honors Academy, Rutgers 2018-2019
* Gamma Sigma Alpha Honors Society, Rutgers 2017-2019
* Honors College, Rutgers
* Presidential Scholar, Rutgers
* National Merit Scholar, Rutgers 
* Dean's List, Rutgers 2015-2019


## Projects
------

  <!-- <ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

  {% for post in site.portfolio %}
    {% if post.path contains 'evonoodles' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

  {% for post in site.portfolio %}
    {% if post.path contains 'gait' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

  {% for post in site.portfolio %}
    {% if post.path contains 'tactile' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

  {% for post in site.portfolio %}
    {% if post.path contains 'femoral' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

  {% for post in site.portfolio %}
    {% if post.path contains 'tka' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

  {% for post in site.portfolio %}
    {% if post.path contains 'disease' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

  {% for post in site.portfolio %}
    {% if post.path contains 'bar' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

  {% for post in site.portfolio %}
    {% if post.path contains 'java' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

  {% for post in site.portfolio %}
    {% if post.path contains 'nfl' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}