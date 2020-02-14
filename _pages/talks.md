---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

<p style="text-decoration:underline;"><a href="/talkmap.ipynb">See a map of all the places I've given a talk!</a></p>

1. "Gas Turbine Control for Islanded Operation and Re-synchronization" -ITEA3 OpenCPS Meeting at Linköping University, Sweden.
2. "An Overview of Global scenario of Electricity Market: European and Indian context" at University of Calcutta, 2017, Kolkata, India.
3. "OpenIPSL Tutorial (Hands-on-OpenIPSL.org using OpenModelica)" at Indian Institute of Technology-Bombay, 2018, Mumbai, India.
4. "Introduction to OpenModelica for Power Systems Modeling" at Anna University, May, 2019, Chennai, India.

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
