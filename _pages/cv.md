---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Computer Science, Dublin City University, Ireland, October 2022 - September 2026 (expected)
* Master’s in Computer Science, University of Trento, Italy, September 2018 - June 2021
* Bachelor’s in Computer Science, University of Trento, Italy, September 2015 - September 2018

Work experience
======
* Training Instructor - Introduction to LLMs, June 2024
  * ADVANCE CRT Summer School, Muckross, Ireland
  * Co-organized and delivered a one-day training session for PhD students focusing on LLMs.
  * Created hands-on exercises and practical demonstrations.

* Co-supervisor Master’s Thesis, January 2024 - Present
  * Dublin City University, Ireland
  * Provided guidance on methodology, data collection, model development, analysis, and final thesis submission.

* Teaching Assistant, May 2023 – Present
  * Dublin City University, Ireland
  * Teaching Assistant for three modules: Introduction to Machine Learning, Human Factors in NLP, and Deep Learning in NLP.
  * Taught lab sessions on topics such as linear regressions, Recurrent Neural Networks, LSTM, Transformers, and Fine-Tuning, and provided hands-on guidance with tools like Python, PyTorch, and HuggingFace Transformers.

* Research Assistant, July 2021 – May 2022
  * University of Trento, Italy
  * Developed AI Coach, a Conversational Agent that helps people with Autism Spectrum Disorder deal with daily social and emotional challenges.
  * Designed the human evaluation of generated texts using crowd-sourcing platforms.

* Industry Internship, September 2019 - March 2020
  * Fairtile, Milan, Italy
  * Worked on an authentication module with AWS Cognito.
  * Implemented an NLP pipeline with Spacy and Apache Spark to analyse phone call transcriptions.

* Research Internship, March 2018 – June 2018
  * University of New South Wales, Sydney, Australia
  * Designed and developed a chatbot that can execute commands of Amazon EC2.

Projects
======
* Exploring Attribute-Specialised Modules for Stylistically and Semantically Controllable Text Generation, October 2022 - Present
  * Development of CTG techniques for multiple attribute control, from prompt engineering to PEFT techniques.
  * Investigation of evaluation methods to measure the effectiveness of the implemented control.
  * Tools: Python, Pytorch, HuggingFace libraries (transformer, peft, and datasets).

* Response Selection Models for Personal Healthcare Agents in the Mental Health Domain, October 2020 – May 2021
  * Dublin City University, Ireland
  * Implemented two Information Retrieval models and two Neural Network architectures in the context of a Personal Healthcare Agent (PHA) in the mental health domain.
  * Tools: Python, Pytorch, numpy, spacy, nltk.
  
Skills
======
* Soft Skills
  * Team player
  * Excellent time management skills
  * Public speaking
* Programming Languages
  * Python
  * Java
  * C++
* Data Science & Machine Learning
  * PyTorch
  * Scikit-learn
  * Pandas
* NLP Tools
  * SpaCy
  * NLTK
  * Hugging Face libraries (Transformers, peft, and datasets)
* NLP Models
  * GPT
  * LLaMa
  * Mistral
  * Gemma
  * LSTM
  * BERT
* Cloud Technologies
  * Google Cloud
  * AWS
* Other Tools & Technologies
  * Git
  * Jupyter
  * LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
