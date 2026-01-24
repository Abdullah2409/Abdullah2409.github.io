---
layout: about
title: about
permalink: /
subtitle: abdullaharshad2409 [at] gmail [dot] com

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
I am a Computer Science graduate from [Lahore University of Management Sciences (LUMS)](https://lums.edu.pk/) in Pakistan, where I completed my Bachelor of Science in Computer Science (September 2021 – July 2025).

My research interests center on **healthcare informatics** and **clinical AI systems**, with a particular focus on applying **LLMs**, **multimodal ML**, and advanced NLP to real-world healthcare challenges. I have worked on multiple research projects involving large language models for mental health assessment, multimodal prediction of anxiety and depression from clinical data, and healthcare information extraction at scale.

Currently, I am the Lead Software Engineer at **SensAI** (DariaTech), an AI-powered medical scribing platform that converts multilingual doctor–patient conversations into structured clinical notes, problem lists, ICD-10 codes, and order sets.

I am passionate about leveraging artificial intelligence and machine learning to solve real world problems in **healthcare informatics**, including clinical decision support systems, medical natural language processing, and scalable AI systems that enhance patient care and clinical workflows.

## Education

---

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>Lahore University of Management Sciences (LUMS)</strong>, Lahore, Pakistan
  </div>
  <div style=" white-space: nowrap;">
    September 2021 - June 2025
  </div>
</div>
<div style="margin-top: 0.2em;">
  <span style="">B.S. in Computer Science</span>
</div>

**Relevant Coursework:** Artificial Intelligence, Computer Networks, Distributed Systems, LLM Systems, Machine Learning, Generative AI, Operating Systems, Software Engineering

## Publications

---

**A Clinical Analysis of the Presentation of Depression in Pakistan**

- *[Paper](assets/pdf/draft_Proof_hi.pdf) Under Review at British Journal of Psychiatry (Cambridge/RCPsych)*
- ***Abdullah Arshad***, Shiza Ihtisham, Basmaa Ali, Clifton Chow

## Research Experience

---

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>Mental Health Assessment Using Patient Records in Zanjabee Dataset</strong>
  </div>
  <div style="white-space: nowrap;">
    September 2024 – Present
  </div>
</div>
<div style="margin-top: 0.2em;">
  <em>Advisors: Dr. Basmaa Ali, Dr. Clifton Chow, Shiza Ihtisham</em>
</div>

- Scaled depression severity modelling to the **Zanjabee** EMR dataset: 10 years of records from a suburban Boston practice covering **4,750 patients** and **16,450 encounters**
- Replaced brittle rule-based extraction with an LLM-assisted pipeline using **GPT-5** and **Gemini 2.5 Pro** to surface context-aware symptom descriptions and map them to **PHQ-9 severity categories**
- Improved severity classification on imbalanced data by collaborating with physicians to validate features and training **Random Forest**, **Gradient Boosting**, and **SVM** classifiers with SMOTE and class weighting

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>A Clinical Analysis of the Presentation of Depression in Pakistan</strong>
  </div>
  <div style="white-space: nowrap;">
    January 2025 – January 2026
  </div>
</div>
<div style="margin-top: 0.2em;">
  <em>Advisors: Basmaa Ali, Clifton Chow, Shiza Ihtisham</em>
</div>

- Quantified depression prevalence/treatment and somatic vs. cognitive symptom expression in a tertiary-care medicine cohort in urban Pakistan (**N=356**), benchmarking patterns against Global North reports
- Built Python NLP pipelines to preprocess unstructured clinical notes into an encounter-level **binary symptom vector** feature matrix and generate interpretable visualizations (word clouds, normalized heatmaps)
- Predicted PHQ-9 scores for unscreened patients (**n=59**) by training a **Random Forest** on observed PHQ-9 encounters (**n=297**) within the extracted feature matrix

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>Multimodal Prediction of Anxiety/Depression Using LLMs</strong>
  </div>
  <div style="white-space: nowrap;">
    September 2024 – July 2025
  </div>
</div>
<div style="margin-top: 0.2em;">
  <em>Advisors: Dr. Basmaa Ali, Dr. Agha Ali Raza</em>
</div>

- Developed a multimodal Urdu anxiety/depression prediction system on **450 structured clinical interviews** collected at Chughtai Lab, Pakistan's largest diagnostic center
- Fine-tuned **Qwen2-Audio** in PyTorch to capture richer prosodic and spectral cues than MFCC-based baselines
- Augmented acoustic features with **Google Gemini Speech** transcripts (8.3% WER) and spaCy-derived lexical markers to strengthen model robustness
- Applied **SMOTE** to address class imbalance, yielding a **15% improvement in F1** over baseline models for early mental health screening

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>Utilising LLMs for Streamlined Analysis of PTA Datasets</strong>
  </div>
  <div style="white-space: nowrap;">
    January 2024 – June 2024
  </div>
</div>
<div style="margin-top: 0.2em;">
  <em>Advisors: Dr. Zafar Ayyub Qazi, Dr. Ihsan Ayyub Qazi</em>
</div>

- Built a Python pipeline using **PyPDF2** to segment multi-hundred-page Pakistan Telecommunication Authority (PTA) Quality of Service (QoS) reports into city-specific clusters and convert them into structured **JSON**, reducing hallucinations and enabling reliable querying
- Combined structural segmentation with **few-shot Chain-of-Thought** prompting, raising retrieval accuracy from **7.84% to 96.8%** and enabling robust automated broadband benchmarking and KPI-based policy reports

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>Detecting Political Polarization in News Channels Using LLMs</strong>
  </div>
  <div style="white-space: nowrap;">
    September 2024 – December 2024
  </div>
</div>
<div style="margin-top: 0.2em;">
  <em>Advisors: Dr. Zafar Ayyub Qazi, Dr. Ihsan Ayyub Qazi</em>
</div>

- Developed a multimodal LLM-based methodology to quantify implicit political bias, addressing a critical gap in traditional text-only analysis by integrating visual framing, emotional tone, and screen-time metrics
- Achieved a Cohen’s Kappa of **0.98**, indicating high inter-rater reliability across **9** annotated videos; established a high quality gold standard for bias detection and future algorithmic scaling

## Work Experience

---

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>Lead Software Engineer</strong>, SensAI – AI Physician Assistant Platform
  </div>
  <div style="white-space: nowrap;">
    September 2025 – Present
  </div>
</div>
<div style="margin-top: 0.2em;">
  DariaTech, Lahore, Pakistan
</div>

- Leading the design and implementation of SensAI, an AI-powered medical scribing platform that converts multilingual doctor–patient conversations into structured notes, problem lists, ICD-10 codes, and order sets
- Refactored the monolithic transcription flow into 11 parallel Gemini bin extractors with real-time WebSocket streaming, cutting total processing time from **60–75s to 30–35s** and time-to-first-result from **60s to 3–5s**
- Improved reliability by adding exponential-backoff retries and an IndexedDB-based offline audio queue, raising API success rate from **92% to 99.5%** and eliminating offline data loss
- Reduced Gemini token usage per request by **40%** via context caching and domain-specific few-shot prompts, while improving extraction accuracy by **15–20%** on complex clinical fields (medications, diagnoses, ICD codes)
- Optimized backend performance with atomic database updates, smart polling with WebSocket fallback, and conditional bin extraction, cutting database round-trips from **15 to 6** queries per visit and lowering redundant polling traffic by **75%**

## Teaching Experience

---

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>Teaching Assistant</strong>, Lahore University of Management Sciences
  </div>
  <div style="white-space: nowrap;">
    January 2023 - July 2023
  </div>
</div>
<div style="margin-top: 0.2em;">
  <em>CS-100: Introduction to Computing</em>
</div>

- Conducted tutorials, held office hours, and graded assignments for over 200 students each semester
- Guided students through fundamental programming concepts and problem-solving techniques in C++

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>Head of IT Department</strong>, Society for Promotion And Development of Engineering and Science
  </div>
  <div style="white-space: nowrap;">
    February 2023 – January 2024
  </div>
</div>
<div style="margin-top: 0.2em;">
  LUMS
</div>

- Led the front-end development team and supervised the design and implementation of the main SPADES website
- Assigned projects and monitored team progress to ensure timely and high-quality deliverables
- Conducted workshops on front-end development, focusing on HTML, CSS, and JavaScript

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap;">
  <div>
    <strong>Private Tutor</strong>, Self-Employed
  </div>
  <div style="white-space: nowrap;">
    January 2022 – Present
  </div>
</div>

- Taught programming languages (Java, Python, C++) to A-level and university-level students
- Prepared students for academic success by providing tailored lessons and hands-on coding exercises
- Mentored students on best practices in software development and problem-solving techniques

## Development Projects

---

**CS100 Virtual Teaching Assistant** | _C++, Generative AI, Google Gemini_

- Developed a virtual teaching assistant tailored for CS-100 students at LUMS to provide coding guidance, evaluate solutions, and offer reinforcement exercises.
- Implemented features such as sanity and sufficiency checks, problem-solving guidance, and quizzes, focusing on C++ and aligning with the course curriculum.

**Content Moderation and Toxicity Classification** | _BERT, Transformers, Python, Jigsaw Toxic Comment Dataset_

- Built a machine learning pipeline to classify toxic content (e.g., threats, insults, identity hate) using the Jigsaw Toxic Comment Dataset, leveraging models like Logistic Regression, RNNs, and Transformer-based architectures (BERT, DeBERTa).
- Designed preprocessing workflows and implemented Transformers for feature extraction and model training, achieving high accuracy in toxicity detection.

**Distributed Key-Value Store** | _Golang_

- Implemented a distributed, fault-tolerant key-value store supporting leader elections and log replication with persistence.

**KIYA - Succession Planning System** | _MERN Stack_

- Developed a web application for automated employee succession planning based on promotion criteria.

**Command-line Shell** | _C_

- Created a shell in C capable of handling conjugated commands and pipelining.

## Skills

---

**Programming Languages:** Java, Python, C, C++, SQL (PostgreSQL), JavaScript, HTML/CSS, R

**Frameworks and Tools:** React, Node.js, Flask, FastAPI, WordPress, Material-UI, JUnit

**Developer Tools:** Git, Docker, TravisCI, Google Cloud Platform (GCP), VS Code, PyCharm, IntelliJ, Eclipse

**Libraries and Packages:** pandas, NumPy, Matplotlib, SciKit-Learn

<!-- ![1764375253022](image/about/1764375253022.png)![1764375256891](image/about/1764375256891.png) -->

<!-- ## Awards
--- -->

<!-- - Recognized as a **High Achiever** for securing 13 A*/A grades in O Levels -->

<!-- - Awarded a **100% merit-based scholarship** for the entire duration of A Levels -->

---
