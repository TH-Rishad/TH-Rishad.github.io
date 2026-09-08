---
title: ""
layout: archive
sitemap: true
permalink: /
author_profile: true
---

<!--<img src="/assets/images/Rishad_side_view.jpg" width="340px" alt="Nora Loose" align="right" padding="20px" />-->


# Biography
---
I am a **PhD in Mechanical Engineering** student at [Hong Kong University of Science and Technology (HKUST)](https://hkust.edu.hk/), researching Robotic Manipulation in Space under [Dr. GAO, Yang](https://facultyprofiles.hkust.edu.hk/profiles.php?profile=yang-gao-yanggao).

Previously I was a **Junior Lecturer** of the Mechanical and Production Engineering (MPE) department of [Islamic University of Technology (IUT)](https://iutoic-dhaka.edu/), Bangladesh. Before that I was an **adjunct lecturer** of Mechanical Engineering at the [Military Institute of Science and Technology (MIST)](https://mist.ac.bd/), Bangladesh. 

I completed my Bachelor of science In Mechanical Engineering from the [Islamic University of Technology (IUT)](https://www.iutoic-dhaka.edu/). For my undergraduate thesis, I worked under the supervision of [Dr. Md. Zahid Hossain](https://mpe.iutoic-dhaka.edu/profile/zahid/education) on Fluid-Structure Interaction based vibration control. I also collaborated on cascaded Brayton Cycle optimization research under [Dr. Mohammad Monjurul Ehsan](https://mpe.iutoic-dhaka.edu/profile/ehsan/education). 

My previous robotics projects span, autonomous flight and relief delivery of a VTOL system for [***ANTS***](https://www.linkedin.com/company/bewithants/posts/?feedView=all), for the [IMechE UAS Challenge-2021](https://www.imeche.org/events/challenges/uas-challenge), and also leading the chassis design subteam of [***Project-Altair***](https://www.altairrover.com/) for the [European Rover Challenge](https://roverchallenge.eu/)-2023, Poland. 

Apart from the academics and research, I enjoy playing violin and building LEGO sets.


# Research Interest
---
<ul>
  <li>Model/Learning Based Control for Dexterous Manipulation</li>
  <li>RTactile Sensing and Reinforcement Learning</li>
  <li>Grasp Planning in Microgravitys</li>
</ul>




# Skills
---
**Design and Simulation**: SOLIDWORKS, Fusion 360, ANSYS Fluent  
**Programming**: ROS, Python, Arduino, Julia, OpenAI Gym  
**Control and Automation**: MATLAB, LABVIEW, Ardupilot Mission Planner  
**AI**: Reinforcement Learning


# Latest News
---
<ul>
  {% assign recent_news = site.news | sort: 'date' | reverse %}
  {% for item in recent_news limit: 3 %}
    <li style="margin-bottom: 1.5rem;">
      <time datetime="{{ item.date | date_to_xmlschema }}" style="font-weight: bold; color: #666;">
        {{ item.date | date: "%B %-d, %Y" }}
      </time>
      <p style="margin: 0.3rem 0 0;">
        {{ item.content | markdownify }}
      </p>
    </li>
  {% endfor %}
</ul>
