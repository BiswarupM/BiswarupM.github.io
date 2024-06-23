---
layout: archive
title: ""
permalink: /talks/
author_profile: true

---
<div style="display: flex; justify-content: center; align-items: center; background-color: #3498db; color: #fff; padding: 20px; width: 100%; height: 50px; font-size: 30px;">
  <p style="margin: 0; color: #fff;">Talks & Presentations</p>
</div>

<style>
a {
    color: #0077b6 !important;
    text-decoration: none; 
}
</style>

<style>
  @media only screen and (max-width: 600px) {
    p {
      font-size: 20px;
    }
  }
</style>

### Invited
* 'Optimal Planning of SPC and MPC Stations for EVs in MV Distribution Networks' at SUPSI (presented with Prof. F. Sossan), November, 2021, Mendrisio, Switzerland.
* 'Introduction to OpenModelica for Power Systems Modeling' at Anna University, May, 2019, Chennai, India.
* 'OpenIPSL Tutorial - Hands-on-OpenIPSL.org using OpenModelica' at Indian Institute of Technology-Bombay, 2018, Mumbai, India.
* 'An Overview of Global scenario of Electricity Market: European and Indian context' at University of Calcutta, 2017, Kolkata, India.
* 'Gas Turbine Control for Islanded Operation and Re-synchronization' -ITEA3 OpenCPS Meeting at Linköping University, 2017, Sweden.


### Conference/workshop
* 'Smart Charging, Vehicle-to-Grid, and Reactive Power Support from Electric Vehicles in Distribution Grids: A Performance Comparison' at 2021 IEEE PES ISGT Europe, Espoo, Finland.
* 'Scheduling the Charge of Electric Vehicles Including Reactive Power Support: Application to a Medium-Voltage Grid' at 26th International Conference and Exhibition on Electricity Distribution CIRED 2021 (virtual).

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
