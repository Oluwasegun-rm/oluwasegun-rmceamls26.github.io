---
layout: project
title: My project
permalink: /about-my-project.html

subtitle: Cross-View Multi-Graph Contrastive Learning with LLM-Guided Knowledge Initialization for Predicting Antidepressant Treatment Response in Major Depressive Disorder

project_title: "My Summer Research Project"

problem: |
  The Problem of Trial-and-Error Psychiatry
  Imagine breaking an arm, and your doctor puts a cast on your leg for six weeks just to "see if it helps." If it doesn't work, you swap to a different cast and wait another six weeks. This sounds unthinkable, but it is exactly how we treat Major Depressive Disorder (MDD) today. Depression is a leading cause of disability worldwide, affecting over 280 million people. Yet, finding the right antidepressant is currently a slow process of trial and error. Between one-third and one-half of patients fail to respond to the first drug they are prescribed. Because these medications take four to six weeks to show results, patients often endure months of severe emotional suffering and grueling side effects before finding a treatment that actually works.

  Moving Toward Personalized, Day-One Medicine
  Our project aims to shift psychiatry away from subjective guessing and toward objective, personalized care. We want to predict whether a specific antidepressant will work for a patient before they ever take a single pill. To do this, we look at a patient's biological markers using three distinct layers of data: their permanent DNA blueprint, their active gene expression, and the environmental chemical switches sitting on top of their genetics. By analyzing a patient's biological profile right at the start, we can give doctors an objective forecasting tool, helping them select the right treatment on day one and sparing patients months of unnecessary struggle.

  Overcoming the Artificial Intelligence Gap
  While this biological data holds the answers, standard computer models completely choke when trying to process it. Clinical studies are necessarily small, giving us data for only about 100 patients, but each patient has hundreds of thousands of genetic markers. Standard AI gets overwhelmed by this imbalance and ends up memorizing random coincidences instead of learning real science. Furthermore, traditional models treat biological data like a flat Excel spreadsheet, ignoring the natural web-like "social networks" in which human genes interact. Our project bridges this gap by building a unique network-based AI that connects with a medical-textbook-trained language model, ensuring our system starts with real medical knowledge and focuses on how genes talk to one another.

approach: |
  Step 1 — Establish Baselines and a Benchmark: We will start by running four classic machine learning models (including Logistic Regression and XGBoost) on a publicly available, fully matched dataset of 111 depressed patients. Because random guessing on this dataset yields about a 55% accuracy rate, this step fixes the exact "score to beat" that our future, more advanced models must clear to prove they are learning real biology.

  Step 2 — Build the Knowledge-Guided Graph AI (MV-GCLLLM): Next, we will construct our main hybrid AI architecture. We will use a frozen Large Language Model (LLM) to read biomedical gene descriptions and generate a medical "cheat sheet." This cheat sheet will be injected into a Graph Convolutional Network (GCN), which organizes the patient's DNA, RNA, and chemical switches into interconnected webs rather than a flat spreadsheet. We will use InfoNCE Contrastive Learning to ensure these different data layers are perfectly aligned and balanced.

  Step 3 — Blind Testing and Biological Evaluation: To test our model, we will use a strict, multi-layered nested cross-validation protocol. This means we will repeatedly hide a portion of our patient data during training and force the AI to make predictions blindly. Once we confirm it accurately predicts patient responses, we will look inside the AI's brain and plug its favorite genetic clues into the DAVID and KEGG medical databases to verify that it independently discovered real biological pathways (like immune and inflammation systems).

  Step 4 — Communicate and Present the Findings: We will document our entire bioinformatics framework, making our code open-source and accessible to other researchers. We will share our progress through weekly program showcases, present a final research poster at the conclusion of the summer program, and ultimately compile our design, benchmark results, and biological discoveries into a formal research paper for submission to a bioinformatics journal.

outcome: |
  By the end of this summer research program, our project will produce three major deliverables designed to advance personalized medicine in psychiatry:

  A Working Bioinformatics Prototype: We will deliver a fully functional, open-source AI codebase built on our unique architecture (MV-GCLLLM). This prototype will include the data preprocessing pipelines, the graph convolutional network (GCN) code, and the contrastive learning training scripts.

  A Formal Research Paper Draft: We will produce a short, high-quality research manuscript documenting our framework, our benchmarking results against standard machine learning models, and our biological discoveries. This text will be prepared for submission to a peer-reviewed bioinformatics or psychiatric research journal.

  An Academic Research Poster: We will design a comprehensive visual poster summarizing our problem statement, the core architecture, our model's predictive accuracy, and the biological pathways it uncovered. This will be used to present our findings at the final summer research showcase.
  
final_report_url: https://example.com/your-report.pdf

grad_mentor:
  name: Ricky Gole
  linkedin: https://www.linkedin.com/in/ricky-gole/

faculty_mentor:
  name: Dr. Jamell Dacon
  linkedin: https://www.linkedin.com/in/jamelldacon/
---
