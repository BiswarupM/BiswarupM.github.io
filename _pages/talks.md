---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

5. "Optimal Planning of SPC and MPC Stations for EVs in MV Distribution Networks" at SUPSI (presented with Prof. F. Sossan), November, 2021, Switzerland. 
4. "Introduction to OpenModelica for Power Systems Modeling" at Anna University, May, 2019, Chennai, India.
3. "OpenIPSL Tutorial (Hands-on-OpenIPSL.org using OpenModelica)" at Indian Institute of Technology-Bombay, 2018, Mumbai, India.
2. "An Overview of Global scenario of Electricity Market: European and Indian context" at University of Calcutta, 2017, Kolkata, India.
1. "Gas Turbine Control for Islanded Operation and Re-synchronization" -ITEA3 OpenCPS Meeting at Linköping University, Sweden.



{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
