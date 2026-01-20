---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="http://larryli1999.github.io/files/Larry_Li.pdf" class="cv-download-btn">
  <i class="fas fa-download"></i> Download CV
</a>

## Education

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">2017 — 2022</div>
    <div class="timeline-content">
      <h3>University of Waterloo</h3>
      <p class="timeline-subtitle">B.A.Sc. in Mechatronics Engineering with AI Option</p>
      <p class="timeline-detail">GPA: 90.6/100 • Dean's List</p>
    </div>
  </div>
</div>

## Work Experience

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">May 2024 — Present</div>
    <div class="timeline-content">
      <h3>Data Scientist</h3>
      <p class="timeline-subtitle">Arteria AI • Toronto, ON</p>
      <ul>
        <li>Led end-to-end development of production document extraction systems for major financial institutions, processing 10K+ pages daily via AWS Textract</li>
        <li>Evaluated Zero-shot Vision Language Models (Qwen, Idefics) for layout analysis and table extraction</li>
        <li>Fine-tuned Transformer-based encoder architectures; applied post-training quantization (ONNX) to reduce inference latency by 50%</li>
        <li>Architected multi-agent workflows using CrewAI for synthetic data generation and automated document reasoning</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">Oct 2022 — May 2024</div>
    <div class="timeline-content">
      <h3>Data Scientist</h3>
      <p class="timeline-subtitle">Telus • Toronto, ON</p>
      <ul>
        <li>Designed and deployed an Offline RL agent (Q-learning based) for HVAC optimization, achieving 20% reduction in energy costs</li>
        <li>Engineered production ML pipelines on GCP Vertex AI, automating training, validation, and drift monitoring using BigQuery</li>
        <li>Led a 4-person squad to develop unsupervised clustering for fiber network fault detection, reducing MTTR by 40%</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">Sep — Dec 2020</div>
    <div class="timeline-content">
      <h3>Machine Learning Engineer Intern</h3>
      <p class="timeline-subtitle">Huawei Canada • Montreal, QC</p>
      <ul>
        <li>Executed 8-bit Quantization Aware Training (QAT) on BERT encoders using PyTorch, compressing model size by 75% while retaining 98% of FP32 performance</li>
        <li>Implemented knowledge distillation techniques and structured pruning for Feed Forward Networks</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">Jan — Apr 2020</div>
    <div class="timeline-content">
      <h3>Deep Learning Engineering Intern</h3>
      <p class="timeline-subtitle">Synapse Technology • Palo Alto, CA</p>
      <ul>
        <li>Developed 2D and 3D object detection algorithms for weapon detection</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">May — Aug 2019</div>
    <div class="timeline-content">
      <h3>Machine Learning Developer Intern</h3>
      <p class="timeline-subtitle">Primate Labs • Toronto, ON</p>
      <ul>
        <li>Developed deep learning applications for Android benchmarking</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">Jan — Apr 2018</div>
    <div class="timeline-content">
      <h3>Robotics Software Developer Intern</h3>
      <p class="timeline-subtitle">Engineering Services Inc. • Toronto, ON</p>
      <ul>
        <li>Developed navigation algorithm for autonomous indoor robots</li>
      </ul>
    </div>
  </div>
</div>

## Research Experience

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">May — Dec 2021</div>
    <div class="timeline-content">
      <h3>Undergraduate Research Assistant</h3>
      <p class="timeline-subtitle">University of Waterloo (Data Systems Group) • Supervisor: Prof. Jimmy Lin</p>
      <ul>
        <li>Co-developed a multi-stage retrieval system utilizing Neural Query Synthesis (NQS) with T5-3B to decompose complex EHRs into atomic search queries</li>
        <li>Solved the quadratic inference bottleneck of cross-encoding long document pairs; system achieved <strong>1st place at TREC 2021</strong> (0.71 nDCG)</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">Sep — Dec 2018</div>
    <div class="timeline-content">
      <h3>Undergraduate Research Assistant</h3>
      <p class="timeline-subtitle">University of Waterloo (Kimia Lab) • Supervisor: Prof. Hamid Tizhoosh</p>
      <ul>
        <li>Researched medical image search and keyword extraction</li>
      </ul>
    </div>
  </div>
</div>

## Projects

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-date">2024</div>
    <div class="timeline-content">
      <h3>Smart Kitchen Multi-Agent System (SKMS)</h3>
      <p class="timeline-subtitle">Python, Google ADK, Gemini, Arize Phoenix</p>
      <ul>
        <li>Architected a hierarchical agent system with routing and negative constraints; designed a custom persistence layer using Google Sheets API</li>
        <li>Engineered a stateful "Soft-Lock" transaction protocol to handle concurrency and prevent hallucinated inventory deductions</li>
        <li>Built a hybrid normalization engine achieving 98% unit conversion accuracy; integrated Arize Phoenix for LLM trace observability</li>
      </ul>
    </div>
  </div>
</div>

## Skills

<div class="skills-grid">
  <div class="skill-category">
    <h4><i class="fas fa-code"></i> Languages</h4>
    <p>Python, C++, C#, SQL, Java, Matlab, R</p>
  </div>
  <div class="skill-category">
    <h4><i class="fas fa-cogs"></i> Frameworks</h4>
    <p>PyTorch, TensorFlow, Hugging Face (Transformers), CrewAI, Scikit-learn</p>
  </div>
  <div class="skill-category">
    <h4><i class="fas fa-cloud"></i> Cloud & MLOps</h4>
    <p>GCP (Vertex AI, BigQuery), AWS (Textract), Docker, Databricks, ONNX Runtime</p>
  </div>
</div>
