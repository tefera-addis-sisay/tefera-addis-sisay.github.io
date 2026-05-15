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

.cv-content a {
  color: #1a73e8;
  text-decoration: none;
}

.cv-content a:hover {
  text-decoration: underline;
}
</style>

<div class="cv-content">

<h2 class="cv-section">Education</h2>

* **MEng in Computer Science** — <a href="https://www.sutd.edu.sg" target="_blank">Singapore University of Technology and Design (SUTD)</a>, 2026  
* **MSc in Computer Science (Cybersecurity Track)** — <a href="https://www.unitn.it/en" target="_blank">Università di Trento</a>, 2024  
* **BSc in Software Engineering** — <a href="https://www.bdu.edu.et" target="_blank">Bahir Dar University</a>, 2019  

---

<h2 class="cv-section">Professional Experience</h2>

* **Lecturer** — Bahir Dar Institute of Technology (BiT), Bahir Dar University  
  • 2026 – Present  

---

<h2 class="cv-section">Research Interests</h2>

* Cybersecurity  
* Intelligent Communication Systems  
* Networked Infrastructures  
* O-RAN Security  
* Performance Degradation Detection (Non-RT RIC)  
* Real-time Anomaly Detection in Telecom Systems  
* VES (VNF Event Streaming) Systems  
* Data Processing and Monitoring (InfluxDB, Grafana)  
* Adversarial Machine Learning (Data Poisoning & Pipeline Manipulation)

---

<h2 class="cv-section">Research Focus</h2>

My research focuses on real-time anomaly detection in virtualized telecom environments and VES-based systems. I also explore security evaluation using adversarial machine learning, including data poisoning and ML pipeline manipulation techniques.

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

</div>
