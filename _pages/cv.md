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

## Education

* MEng in Computer Science — Singapore University of Technology and Design (SUTD), 2026  
* MSc in Computer Science (Cybersecurity Track) — Università di Trento, 2024  
* BSc in Software Engineering — Bahir Dar University, 2019  

---

## Professional Experience

* Lecturer — Bahir Dar Institute of Technology (BiT), Bahir Dar University, Ethiopia (2026 – Present)

---

## Research Interests

* Cybersecurity in Communication Systems  
* O-RAN Security and Intelligent RAN Monitoring  
* Performance Degradation Detection (Non-RT RIC)  
* VES (VNF Event Streaming) Systems  
* Real-time Network Anomaly Detection  
* Telecom Network Observability  
* Data-driven Security Analytics  
* Adversarial Machine Learning in Telecom Systems  

---

## Research Activities

* Development of Python-based VES Collector for telecom event ingestion and processing  
* Integration of Wireshark with containerized O-RAN environments for traffic analysis  
* Design of real-time anomaly detection pipelines for virtualized telecom systems  
* Research on security testing, attack simulation, and ML-based intrusion detection  
* Implementation of Kafka + InfluxDB-based observability and telemetry systems  

---

## Technical Skills

* Programming: Python, Bash  
* Networking Tools: Wireshark  
* Streaming & Data Systems: Kafka, InfluxDB  
* Visualization: Grafana  
* Containerization: Docker, Kubernetes (Minikube)  
* Platforms: Linux, Virtualized Telecom Environments  

---

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

## Talks

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

---

## Teaching

<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

## Academic Service

* Supervision of undergraduate research projects  
* Teaching and lab support in computing and cybersecurity courses  
* Participation in telecom and network security research activities  
