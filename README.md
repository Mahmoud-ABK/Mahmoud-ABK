# Mahmoud Ben Abdelkader

I build AI systems: training and fine-tuning models, the RAG pipelines around them, and the backend that serves them, with a bias toward local, cloud-free inference. Software engineering student at ISIMM Monastir, graduating 2027.

---

## What I'm doing at Yonnov'IA

AI Engineer (part-time, remote) since September 2025. Local LLM serving and retrieval: hybrid dense + BM25 search across Qdrant and Weaviate, output schema-validated. NLP pipelines and ML experimentation, as asynchronous services on distributed task queues. Self-hosted, no cloud dependency, tuned to local VRAM/CPU limits.

Before that, a full-time internship (Summer 2025): a fully local assistant built on a fine-tuned Qwen 2.5 7B.

---

## Projects

- **[Yaqadha](https://github.com/Mahmoud-ABK/yaqadha)**: patients report drug side effects to an LLM forbidden from giving advice, a pharmacist validates every case by phone.
  - An LLM abstraction layer whose two operations return only a next question or structured fields, never advice.
  - Pharmacist NL queries become SQL, validated single-statement and SELECT-only before running on a read-only connection.
  - A DRAFT to QUEUED to IN\_CALL to VALIDATED state machine; signing freezes an immutable snapshot. Frontend types come from the backend's OpenAPI schema.
- **[Guide Dog Classifier](https://github.com/Mahmoud-ABK/finetune-efficientnetb3-low-vram)**: EfficientNet-B3 fine-tuned on Stanford Dogs inside a 4 GB RTX 3050 Ti, mixed precision with gradient accumulation replacing a run that runs out of memory without it.
- **[AutoReview-NLP-Arabic](https://github.com/Mahmoud-ABK/AutoReview-NLP-Arabic)**: reviewer assignment over 1,600+ Arabic papers via OCR, an Author-Article graph, and TF-IDF/cosine expertise matching.
- **[Sentinelle](https://github.com/Mahmoud-ABK/fire-monitoring-pipeline-sentinelle)**: NASA FIRMS fire detections clustered on a 0.1° grid, population exposure counted over 168,005 GeoNames cities within 50 km via PostgreSQL earthdistance.
- **[University Scheduling API](https://github.com/Mahmoud-ABK/UniversityScheduling_backend)**: Spring Boot API for four roles, with conflict detection, a makeup-session approval flow, and Excel import.

---

## Writing and notes

A modular Obsidian knowledge base (MuLearning) spanning programming, backend, AI/ML, systems, and math. Published:

- [Beyond Basic Python](https://mahmoud-abk.github.io/mmu-vault-beyond-basic-python/summary.html)
- [Auxiliary Tools for Engineers](https://mahmoud-abk.github.io/mmu-vault-auxiliary-tools/Introduction)
- [GPU Memory Optimization Techniques](https://www.linkedin.com/pulse/optimizing-gpu-memory-3-techniques-efficient-local-ben-abdelkader-7z99e/) (article)

---

## Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**AI/ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-555555?style=flat-square)

**Backend**
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Data / Systems**
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-555555?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-555555?style=flat-square)
![Weaviate](https://img.shields.io/badge/Weaviate-555555?style=flat-square)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

---

## Certifications

NVIDIA Deep Learning Institute: [Diffusion Models](https://learn.nvidia.com/certificates?id=4mdz493QR7urnCwYUTlh7Q) · [Anomaly Detection](https://learn.nvidia.com/certificates?id=nCforveUQiSTmH6Y18yuKg) · [AI Cybersecurity Pipelines](https://learn.nvidia.com/certificates?id=uS7BQJo9QPeVC_ucN1Q9Pw) · [Deep Learning Fundamentals](https://learn.nvidia.com/certificates?id=RJzQ7wTGQmiD3mZlqTXfXw)

---

## Languages

Arabic (native) · French (fluent) · English (C1, onSET) · German (beginner)

---

## Reach me

- **Email:** benabdelkadermahmoud2003@gmail.com
- **LinkedIn:** [mahmoud-ben-abdelkader](https://www.linkedin.com/in/mahmoud-ben-abdelkader/)
