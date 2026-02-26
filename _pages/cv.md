---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

<div style="text-align: center; margin-bottom: 30px;">
  <a href="https://drive.google.com/file/d/10YcdyhZmvKeJy-dX56QC4cYkm_-1VuWR/view?usp=share_link" class="btn btn--primary btn--large" target="_blank">
    📄 Download CV (PDF)
  </a>
</div>

---

## Education

### Master of Science in Computer Software Engineering (Thesis Track)

**Arizona State University** | *Tempe, AZ* | Aug. 2024 – May 2026
**GPA:** 3.83/4.0

**Thesis:** Use of Deep Reinforcement Learning and LLMs for Ontology Alignment
**Advisor:** Dr. Srividya Bansal

### Bachelor of Engineering in Information Science and Engineering

**Visvesvaraya Technological University** | *Bengaluru, India* | Aug. 2023

---

## Research Experience

### Independent Study: Foundations and RAG with Knowledge Graphs

**Arizona State University** | *Tempe, AZ* | Aug. 2025 – Present

- Analyzed Entity Alignment techniques for merging heterogeneous graphs, specifically evaluating Graph Convolutional Networks and attribute embedding models for cross-lingual integration
- Evaluated Retrieval-Augmented Generation (RAG) frameworks, focusing on how structured knowledge graphs act as a verification layer to mitigate hallucinations in generative systems
- Explored the intersection of Linked Data and NLP, documenting techniques for grounding Large Language Models in factual, curated ontologies to enhance reasoning capabilities

### Volunteer Researcher

**Fireline Science** | *Tempe, AZ* | July 2025 – Present

- Designing and fine-tuning offline models specifically engineered to assist Wilderness First Responders in disconnected areas, addressing critical safety gaps caused by isolation
- Assisted with the development and testing of Fireline Science's educational workflow system TWS including the first use of their external API
- Implementing human-in-the-loop workflows to counteract skill decay and role ambiguity, ensuring reliable guidance for critical care in the wild

### Research Aide and Grader

**Arizona State University, W.P. Carey School of Business** | *Tempe, AZ* | May 2025 – Present

- Formulated data-driven strategies for curriculum optimization by researching and implementing LLMs to identify organizational skill gaps, leading to more targeted learning pathways
- Performed advanced statistical analyses (SEM, ANOVA, ANCOVA, Regression Discontinuity, Survival Analysis) and other data analysis, cleaning, and visualizations on Canvas LMS data and internal data for industry reports
- Communicated key findings to sponsors to support strategic decision-making
- Facilitate course delivery, evaluate assignments, and mentor students in AWS Cloud Foundations course (CIS 194)

---

## Professional Experience

### AWS Cloud and Full-Stack Developer Intern

**The India Cloud** | *Bengaluru, India* | Aug. 2023 – Jan. 2024

- Enhanced website performance and scalability using AWS services (EC2, S3, Route 53, CloudFront)
- Established CI/CD pipelines via AWS CodeBuild, CodeCommit, and CodePipeline for continuous delivery
- Built full-stack solutions with Node.js, React, and Passport for seamless frontend-backend integration
- Designed AI-driven chatbot for HR onboarding process, enabling new hires to query documents efficiently

### Data Science and AI Internship Training

**New Age Solutions Technologies (NASTECH)** | *Bengaluru, India* | March 2022 – June 2022

- Applied AI and data science techniques including machine learning, deep learning, and big data analysis
- Utilized TensorFlow, Keras, Scikit-learn, Pandas, Matplotlib, and Seaborn for model development and visualization
- Created and deployed real-time object detection service using YOLOv5 on edge devices (60 FPS, <50ms latency)

---

## Technical Skills

<div class="skills-grid" style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 20px 0;">

<div>
<strong>Programming Languages</strong><br>
R, Python, C, C++, JavaScript, CSS, SQL, PHP, Java, Scala
</div>

<div>
<strong>Libraries & Tools</strong><br>
PyTorch, TensorFlow, Keras, Hugging Face, LangChain, PEFT (LoRA/QLoRA), FHE, FAISS, Scikit-learn, Pandas, Matplotlib, OpenCV, Mediapipe, Node.js, React
</div>

<div>
<strong>Cloud & DevOps</strong><br>
AWS (EC2, S3, Route 53, CloudFront, Developer Tools), Kubernetes, Docker, Git, Agile, Tableau, Spark, Kafka
</div>

</div>

**Certifications:**

- Generative AI for Everyone (DeepLearning.ai)
- AWS Cloud Practitioner
- RCR - Responsible Conduct of Research (CITI Program)
- IRB - Social, Behavioral Research (CITI Program)

## Talks and Presentations

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

---

## Teaching Experience

### Teaching Assistant and Grader | CIS 194: AWS Cloud Foundations

**Arizona State University** | *May 2025 – Present*

- Instructed students in cloud computing fundamentals and AWS services
- Conducted regular office hours providing academic support and guidance
- Evaluated assignments with comprehensive feedback to enhance learning outcomes

<!-- Dynamic teaching posts (currently empty)
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
-->

---

## Selected Projects

### DRAL-OA: Deep Reinforcement Adaptive Learning for Ontology Alignment

**Role:** Researcher and Developer | **Status:** Submitted to OAEI 2025

- Enhanced and submitted a deep reinforcement and adaptive learning ontology alignment framework to the OAEI 2025 campaign, achieving benchmark scores of **82% Precision and Recall** on the complex anatomy track
- Currently leading research into integrating MCP and local agentic reasoning model of LLMs to further boost alignment accuracy, with the objective of surpassing the benchmark

### GEMR:KG - Global Emerging Market Risk Knowledge Graph

**Role:** Researcher

- Architected a neuro-symbolic knowledge graph merging World Bank economic and credit risk and political risk datasets into a unified RDF/OWL ontology on GraphDB to model contagion dynamics and temporal correlations
- Built a Python-based ETL pipeline for semantic normalization and integrated an LLM-to-SPARQL interface, enabling complex multi-hop reasoning to uncover hidden macroeconomic stress signals and geographic default propagation paths across siloed financial data

### Smart Portfolio Builder 🏆

**Role:** AWS Cloud & Backend Developer | **Award:** Most Innovative Project, Innovation Hacks 2025

- Won the **MOST INNOVATIVE PROJECT** at INNOVATION HACKS - 2025
- Integrated AWS Bedrock to provide AI-enhanced resume summarization and orchestrated processing of user portfolio data
- Designed a Node.js/Express.js RESTful backend, processing **100+** resumes and videos via Multer-powered uploads, achieving high uptime through PostgreSQL

### HR Onboarding Chatbot

**Role:** Full Stack Developer | **Tech Stack:** OpenAI, FAISS, NLTK, AWS

- Engineered a LLM chatbot solution integrated with OpenAI modules, sentence transformers, FAISS, NLTK, NumPy, and Pandas
- Built natural language queries against proprietary content and ensured seamless integration with existing AWS infrastructure
- Pioneered NLP pipeline improving content retrieval accuracy by **30%** and reducing query processing time by **40%** on AWS

---

## Awards and Honors

🏆 **Most Innovative Project** | Innovation Hacks 2025
*Smart Portfolio Builder project*

---

## Service and Leadership

### Chair of Academia | ACM at ASU

*Jan 2025 – Mar 2025*

- Curated interactive workshops and information sessions for ACM SIGs and Student Research Competition
- Guided **100+ students** through submission processes and enhanced application quality
- Organized academic events to foster research culture among undergraduate students

### Volunteer Teacher | Noble Cause Foundation

*Aug 2020 – Apr 2024* | **3 years 9 months**

- Tutored underprivileged students in STEM subjects (mathematics, science, social studies)
- Participated in community outreach events and environmental cleaning drives
- Contributed to social welfare initiatives impacting local communities

<!-- Professional Memberships (add when applicable)
Professional Memberships
======
* [Professional memberships to be added]
-->
