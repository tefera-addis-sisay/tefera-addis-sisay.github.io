---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
hide_title: true
---

{% include base_path %}

<style>
.cv-section {
  color: #1a73e8;
  font-size: 1.4em;
  margin-top: 25px;
  border-bottom: 2px solid #e0e0e0;
  padding-bottom: 5px;
}

.cv-subtitle {
  color: #444;
}
</style>

<div class="cv-subtitle">
<h2 class="cv-section">Education</h2>

* MEng in Computer Science, <a href="https://www.sutd.edu.sg" target="_blank">Singapore University of Technology and Design</a>, 2026  
* M.S. in Computer Science (Cybersecurity track), <a href="https://www.unitn.it/en" target="_blank">Università di Trento</a>, 2024  
* B.S. in Software Engineering, <a href="https://www.bdu.edu.et" target="_blank">Bahir Dar University</a>, 2019  

---

<h2 class="cv-section">Work Experience</h2>

* Spring 2024: Academic Pages Collaborator  
  * GitHub University  
  * Duties includes: Updates and improvements to template  
  * Supervisor: The Users  

* Fall 2015: Research Assistant  
  * GitHub University  
  * Duties included: Merging pull requests  
  * Supervisor: Professor Hub  

* Summer 2015: Research Assistant  
  * GitHub University  
  * Duties included: Tagging issues  
  * Supervisor: Professor Git  

---

<h2 class="cv-section">Skills</h2>

* Skill 1  
* Skill 2  
  * Sub-skill 2.1  
  * Sub-skill 2.2  
  * Sub-skill 2.3  
* Skill 3  

---

<h2 class="cv-section">Publications</h2>

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

<h2 class="cv-section">Talks</h2>

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

---

<h2 class="cv-section">Teaching</h2>

<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

<h2 class="cv-section">Service and Leadership</h2>

* Currently signed in to 43 different Slack teams
</div>
