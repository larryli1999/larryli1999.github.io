---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download my CV [here](http://larryli1999.github.io/files/CV.pdf)

Education
======
* **University of Waterloo** — Sep 2017 - Apr 2022<br/>
  * *B.A.Sc. in Mechatronics Engineering with AI Option*<br/>
  * GPA: 90.6/100 (Dean's List)

Work Experience
======
* **Data Scientist** - Arteria AI<br/>
  * *May 2024 - Present;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Toronto, ON*<br/>
  * Led end-to-end development of production document extraction systems for major financial institutions, processing 10K+ pages daily via AWS Textract
  * Evaluated Zero-shot Vision Language Models (Qwen, Idefics) for layout analysis and table extraction
  * Fine-tuned Transformer-based encoder architectures; applied post-training quantization (ONNX) to reduce inference latency by 50%
  * Architected multi-agent workflows using CrewAI for synthetic data generation and automated document reasoning
<br/>

* **Data Scientist** - Telus<br/>
  * *Oct 2022 - May 2024;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Toronto, ON*<br/>
  * Designed and deployed an Offline RL agent (Q-learning based) for HVAC optimization, achieving 20% reduction in energy costs
  * Engineered production ML pipelines on GCP Vertex AI, automating training, validation, and drift monitoring using BigQuery
  * Led a 4-person squad to develop unsupervised clustering for fiber network fault detection, reducing MTTR by 40%
<br/>

* **Machine Learning Engineer Intern** - Huawei Canada<br/>
  * *Sep - Dec 2020;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Montreal, QC*<br/>
  * Executed 8-bit Quantization Aware Training (QAT) on BERT encoders using PyTorch, compressing model size by 75% while retaining 98% of FP32 performance
  * Implemented knowledge distillation techniques and structured pruning for Feed Forward Networks
<br/>

* **Deep Learning Engineering Intern** - Synapse Technology<br/>
  * *Jan - Apr 2020;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Palo Alto, CA*<br/>
  * Developed 2D and 3D object detection algorithms for weapon detection
<br/>

* **Machine Learning Developer Intern** - Primate Labs<br/>
  * *May - Aug 2019;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Toronto, ON*<br/>
  * Developed deep learning applications for Android benchmarking
<br/>

* **Robotics Software Developer Intern** - Engineering Services Inc.<br/>
  * *Jan - Apr 2018;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Toronto, ON*<br/>
  * Developed navigation algorithm for autonomous indoor robots

Research Experience
======
* **Undergraduate Research Assistant** - University of Waterloo (Data Systems Group)<br/>
  * *May - Dec 2021;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Waterloo, ON*<br/>
  * Co-developed a multi-stage retrieval system utilizing Neural Query Synthesis (NQS) with T5-3B to decompose complex EHRs into atomic search queries
  * Solved the quadratic inference bottleneck of cross-encoding long document pairs; system achieved **1st place at TREC 2021** (0.71 nDCG)
  * Supervisor: Prof. Jimmy Lin
<br/>

* **Undergraduate Research Assistant** - University of Waterloo ([Kimia Lab](https://kimialab.uwaterloo.ca/kimia/))<br/>
  * *Sep - Dec 2018;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Waterloo, ON*<br/>
  * Researched medical image search and keyword extraction
  * Supervisor: Prof. Hamid Tizhoosh

Projects
======
* **Smart Kitchen Multi-Agent System (SKMS)**<br/>
  * *Python, Google ADK, Gemini, Arize Phoenix*<br/>
  * Architected a hierarchical agent system with routing and negative constraints; designed a custom persistence layer using Google Sheets API
  * Engineered a stateful "Soft-Lock" transaction protocol to handle concurrency and prevent hallucinated inventory deductions
  * Built a hybrid normalization engine achieving 98% unit conversion accuracy; integrated Arize Phoenix for LLM trace observability

Skills
======
* **Languages:** Python, C++, C#, SQL, Java, Matlab, R
* **Frameworks:** PyTorch, TensorFlow, Hugging Face (Transformers), CrewAI, Scikit-learn
* **Cloud & MLOps:** GCP (Vertex AI, BigQuery), AWS (Textract), Docker, Databricks, ONNX Runtime
