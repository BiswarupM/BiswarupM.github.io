---
layout: archive
title: ""
permalink: /talks/
author_profile: true

---
![Alt text](/images/Talks.svg)

###
<p align="justify">
* "Optimal Planning of SPC and MPC Stations for EVs in MV Distribution Networks" at SUPSI (presented with Prof. F. Sossan), November, 2021, Switzerland.</p>
<p align="justify">
* "Introduction to OpenModelica for Power Systems Modeling" at Anna University, May, 2019, Chennai, India.</p>
<p align="justify">
* "OpenIPSL Tutorial (Hands-on-OpenIPSL.org using OpenModelica)" at Indian Institute of Technology-Bombay, 2018, Mumbai, India.</p>
<p align="justify">
* "An Overview of Global scenario of Electricity Market: European and Indian context" at University of Calcutta, 2017, Kolkata, India.</p>
<p align="justify">
* "Gas Turbine Control for Islanded Operation and Re-synchronization" -ITEA3 OpenCPS Meeting at Linköping University, 2017, Sweden.</p>


{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
