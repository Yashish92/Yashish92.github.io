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
* B.S. in Biomedical Engineering, University of Moratuwa, Sri Lanka, 2017
* M.S. in Electrical Engineering, University of Maryland College park, USA, 2022
* Ph.D in Electrical and Computer Engineering, University of Maryland College park, 2022 (expected)

Work experience
======
* Fall 2019 - present: Graduate Research Assistant
  * Speech Communication Lab (https://scl.umd.edu/) at Univeristy of Maryland College Park
  * Supervisors: Professor Carol Espy-Wilson and Professor Shihab Shamma
  * Contributions: 
	  * Developing an unsupervised learning algorithm inspired by the sensorimotor interactions in humans to learn control parameters to a given articulatory/audio synthesizer (Python/PyTorch, DIVA music synthesizer, libRenderman, pink-trombone)
	  * Improving an Acoustic-to-Articulatory speech inversion system with data augmentation and multi-task learning frameworks (Python/keras, librosa, audiomentation)
	  * Working on incorporating nasal and glottal parameters to the existing speech inversion frameworks
	  * Developed a deep learning based articulatory speech synthesizer from vocal tract variables extracted from a speech inversion system (Python/PyTorch)
	  * Implemented a multimodal CNN with vocal tract variables and Facial Action Units for assessing articulatory coordination in speech to detect positive symptoms in schizophrenia (Matlab, Python/keras, OpenFace 2.0)
	  * Developed a mutimodal speech emotion recognition system with articulatory coordination features and text embedding (Python/keras, librosa, GloVe, eGeMAPS)

* Summer 2022: Machine Learning Engineer Intern
  * Skylyte(https://www.skylyte.com/), NY, USA
  * Contributions: 
	  * Conducted a detailed analysis on vocal biomarkers to identify the best predictors of burnout and resilience (openSMILE, librosa)
	  * Developed ML models to classify different levels of burnout, resilience, valence and arousal of speech collected from people working in teams at corporate settings
	  * Designed and started a speech data collection to capture burnout symptoms at work place

* Fall 2018-Spring 2020: Graduate Teaching Assistent
* Department of Electrical and Computer Engineering at Univeristy of Maryland College Park
  * Worked as a GTA for graduate level class on “Compilers and Optimization” in 2020 spring. Guided students to develop a basic compiler in llvm for cloning functions
  * Worked as a GTA for undergrad level “Signals and Systems” class in 2019 spring/2019 fall and “Elements of Discrete Signal Analysis” class in 2018 fall.
 
* May 2017-July 2018: Research Engineer
  * Synergen Technology Labs (https://www.synergentl.com/), Nugegoda, Sri Lanka
  * Contributions: 
	  * Developed (and delivered) the communication interface for a wearable ring for capturing PPG and motion signals for a cardiac arrest monitoring system by Rodin Scientific (https://www.rodinscientific.com/)
	  * Programmed and developed an android mobile app to communicate with a wearable baby monitor device via BLE and to calculate parameters like heart rate, respiratory rate and SpO2 level from the PPG signal.
	  
* Oct 2015-April 2016: Research Intern
  * Synergen Technology Labs (https://www.synergentl.com/), Nugegoda, Sri Lanka
  * Contributions: 
	  * Worked on establishing the data communication protocol between a custom developed mobile app and an Insole with pressure sensors to detect pressure variation in the foot for diabetic foot ulcer detection.
 
Research Interests
======
* Articulatory speech production
* Speech Inversion
* Speech and Music Synthesis
* Machine Learning
* Multi-modal systems
* Speech in mental health

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards and Professional Membership
======
* Awarded with Jacob K. Goldhaber Travel Award to attend Interspeech 2022
* Awarded Acoustical Society of America (ASA) travel grant and Jacob K. Goldhaber Travel award to attend 181st meeting of Acoustical Society of America 2021
* Awarded with the “Mahapola Higher Education (Merit) Scholarship” for being in the top 100 in the island in G.C.E Advance Level Examination 2011 from the Mathematics stream.
* Awarded with the “Sisu Udana Scholarship Award” and “Dialog Merit Scholarship” for being island 7th in G.C.E Ordinary Level Examination 2008
* Student member of Acoustical Society of America and IEEE signal processing society
