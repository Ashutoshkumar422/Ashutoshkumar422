# Hi, I'm Ashutosh Kumar 👋

### Generative AI • Machine Learning • Deep Learning • Computer Vision • AI Engineering

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&pause=1000&color=2563EB&center=true&vCenter=true&width=850&lines=Building+Intelligent+AI+Systems;Exploring+LLMs%2C+RAG+%26+Agentic+AI;Researching+UAV+Swarm+Intelligence;Computer+Vision+%26+Deep+Learning;From+Research+to+Real-World+Applications" alt="Animated introduction" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ashutoshkumar2910/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/Ashutoshkumar422">
    <img src="https://img.shields.io/badge/GitHub-Explore%20Projects-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="mailto:ashutoshkumarskt.29@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## 🧭 Navigate My Profile

<details open>
<summary><b>Explore sections</b></summary>

- [About Me](#-about-me)
- [Research Portfolio](#-research-portfolio)
- [Featured Projects](#-featured-projects)
- [Technical Skills](#-technical-skills)
- [Research Publication](#-research-publication)
- [Professional Experience](#-professional-experience)
- [Leadership and Achievements](#-leadership-and-achievements)
- [GitHub Activity](#-github-activity)
- [Current Interests](#-current-interests)
- [Let's Connect](#-lets-connect)

</details>

---

## 👨‍💻 About Me

I'm an **M.Tech student in Computer Science and Engineering (Analytics) at the National Institute of Technology Delhi**, with a strong interest in building intelligent, scalable, and production-oriented AI systems.

My work spans Generative AI, Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), deep learning, computer vision, time-series anomaly detection, database engineering, and multi-agent learning for intelligent communication networks.

I enjoy exploring both the theoretical and practical sides of AI: understanding why an algorithm works, identifying its limitations, implementing it, evaluating it through experiments, and translating it into a usable application.

### 🎓 Education

| Degree | Institution | Duration |
|---|---|---|
| M.Tech, Computer Science and Engineering (Analytics) | National Institute of Technology Delhi | 2025–2027 |
| B.Tech, Computer Science and Engineering | Inderprastha Engineering College, Ghaziabad | 2020–2024 |

### 🔬 My technical approach

I approach AI development as a complete engineering lifecycle:

**Problem formulation → Data processing → Model and algorithm design → Training → Evaluation → API development → Deployment → Optimization**

I am particularly interested in systems where multiple areas of computer science intersect, such as combining computer vision with representation learning, LLMs with semantic retrieval, or reinforcement learning with wireless communication and UAV coordination.

### 🏆 Highlights

- 🥉 Third place in the MathWorks CodeMATrix Sprint Hackathon.
- 📄 Published research on student attentiveness and attendance monitoring in IRJMETS.
- 🔬 Research interests in UAV swarm intelligence, privacy-preserving learning, communication optimization, and trajectory planning.
- 💻 Experience building AI applications using PyTorch, TensorFlow, FastAPI, Docker, LangChain, Hugging Face, and vector search.
- 👥 Training & Placement Coordinator at NIT Delhi.

---

## 🔬 Research Portfolio

My research interests focus on developing efficient, reliable, and intelligent systems under real-world constraints. I am interested in more than improving a single model metric: I also study scalability, communication overhead, privacy, physical constraints, safety, and reproducibility.

<details open>
<summary><b>Research 01 — Secure Federated Multi-Agent Reinforcement Learning for RIS-Carrying UAV Swarms in Blocked Urban Environments</b></summary>

### Research motivation

Urban wireless communication is challenging because buildings obstruct direct links between base stations, UAVs, and ground users. A UAV swarm can provide flexible aerial connectivity, but coordinating multiple UAVs introduces additional challenges involving interference, energy consumption, user association, security, and communication reliability.

Reconfigurable Intelligent Surfaces (RIS) offer a way to influence radio propagation by adjusting the phase response of reflected signals. Combining RIS-equipped UAVs with multi-agent reinforcement learning creates an opportunity to coordinate aerial communication in dynamic, blockage-prone environments.

### Research objective

The objective is to investigate a unified learning framework that coordinates RIS-carrying UAVs to improve communication efficiency while accounting for blockage, UAV energy constraints, user association, and secrecy-related objectives.

### Proposed methodology

**1. Environment and communication modeling**

The framework models an urban environment with buildings, ground users, UAVs, and a base station. Communication performance depends on factors such as line-of-sight availability, channel conditions, interference, and aerial relay links.

**2. RIS-assisted communication**

RIS-equipped UAVs are considered as mobile communication platforms that can help improve propagation conditions when direct communication paths are obstructed.

**3. Federated multi-agent reinforcement learning**

A federated multi-agent PPO-based approach, referred to as FedMAPPO, is investigated to support coordinated learning across UAV agents. The framework explores federated policy learning and configurable aggregation strategies, including resource-aware aggregation and uniform aggregation.

The central idea is to learn coordination policies while reducing the need to centralize all local learning experiences. Federated learning does not automatically guarantee privacy, so privacy assumptions and any additional protection mechanisms must be evaluated separately.

**4. User association and aerial relaying**

The system considers user-to-UAV association, UAV coordination, and half-duplex decode-and-forward aerial relaying. Association decisions must account for communication quality and system constraints rather than merely assigning each user to the nearest UAV.

**5. Secrecy-aware optimization**

Passive eavesdroppers are included in the communication model. Secrecy-related reward terms help investigate the trade-off between useful communication, energy efficiency, fairness, and secure transmission.

### Evaluation methodology

The simulation framework investigates:

- Energy efficiency and communication utility.
- Aggregate data-rate performance.
- Secrecy-rate behavior under passive eavesdropping.
- User association and service coverage.
- Fairness across users.
- Training convergence and scalability.
- Comparisons against alternative learning baselines.

The manuscript and associated experiments investigate these trade-offs using a simulated urban UAV communication environment. Final claims should be tied to the exact experiment configuration and validated results reported in the manuscript.

### Research contribution

The intended contribution is a unified framework connecting RIS-assisted aerial communication, federated multi-agent policy learning, blockage-aware channel modeling, user association, and secrecy-aware optimization.

The research question is whether coordinated learning can improve communication performance under realistic physical and operational constraints, rather than optimizing an isolated communication metric.

**Research areas:** Federated Learning · Multi-Agent Reinforcement Learning · PPO · RIS · UAV Networks · Wireless Communication · Physical-Layer Security

**Status:** Research manuscript and experimental framework.

</details>

<details>
<summary><b>Research 02 — AI-Based Trajectory Prediction and Collision-Free Optimization for Large UAV Swarms</b></summary>

### Research motivation

When a UAV swarm grows in size, planning safe trajectories becomes substantially more difficult. Each UAV must reach its destination while respecting motion constraints and avoiding collisions with other UAVs.

A trajectory planner that checks only the UAV positions at discrete time steps can miss collisions occurring between consecutive samples. This problem is especially important when UAVs move quickly or follow trajectories that cross between sampled positions.

The research therefore focuses on scalable swarm trajectory coordination, collision detection, and continuous-time safety validation.

### Research objective

To develop and evaluate a trajectory-planning pipeline that can coordinate a large number of UAVs while maintaining collision-free motion, controlling trajectory deviations, and reducing computational overhead.

### Methodology and implementation

**1. Reference implementation and reproducibility**

The project began with a literature-based reference implementation and a structured implementation and validation workflow. The reference algorithm is used as a baseline for testing improvements.

**2. Geometric collision detection**

The implementation includes continuous segment-based closest-point-of-approach (CPA) checks. Instead of checking only sampled UAV positions, the method examines relative motion over a time interval to detect potential collisions between samples.

This is important because discrete-time collision checks can incorrectly report a safe trajectory even when two UAVs pass dangerously close between sampled positions.

**3. ICDATS-based trajectory coordination**

The implementation uses an ICDATS reference workflow to organize UAV trajectory coordination into batches. Batching is investigated as a way to manage computational complexity and coordinate larger swarms.

**4. Cross-batch collision handling**

A separate validation stage checks interactions between UAVs belonging to different planning batches. This is necessary because individually safe batches are not necessarily safe when executed simultaneously.

**5. Cubic Hermite vertical staging**

The later implementation incorporates cubic Hermite vertical staging, using a transition height and a climb-width parameter to help coordinate vertical separation during staging.

The design aims to reduce conflicts between UAVs during transitions while maintaining trajectory endpoint constraints.

**6. Automated validation**

The research workflow includes checks for:

- Intra-batch collisions.
- Cross-batch collisions.
- Minimum separation and clearance.
- Trajectory endpoint deviations.
- Residual collisions missed by simpler checks.
- Computational runtime and scalability.

### Experimental development

The implementation has progressed through reference testing, collision-geometry validation, batch coordination, and cross-batch safety checks.

One recorded reference configuration used 50 UAVs, 201 time samples, a time step of 1, a minimum separation parameter of 0.5, and random seed 42. In that configuration, continuous collision checking exposed residual conflicts that were not adequately captured by simpler checks.

Subsequent validation work investigated vertical staging and cross-batch coordination. These are configuration-specific development results, not a claim that the method is universally collision-free.

### Research contribution

The key research direction is to combine scalable trajectory coordination with continuous collision validation, explicit cross-batch safety checks, and constrained trajectory transitions.

A complete evaluation should compare the method with established baselines across swarm sizes, random seeds, collision rates, runtime, path length, and trajectory deviation.

**Research areas:** Multi-UAV Systems · Trajectory Planning · Computational Geometry · Collision Avoidance · Swarm Coordination · Safety Validation

**Status:** Active implementation and experimental validation.

</details>

<details>
<summary><b>Research 03 — An Efficient Privacy-Preserving Intrusion Detection Scheme for UAV Swarm Networks</b></summary>

### Research motivation

UAV swarm networks are increasingly used in applications requiring coordinated communication among mobile aerial agents. However, their wireless links are exposed to interference, changing channel conditions, mobility, and potentially malicious network activity.

Intrusion detection in this setting is difficult because the system must identify suspicious behavior without imposing excessive communication, computation, or data-sharing overhead on resource-constrained UAVs.

Traditional centralized detection can require gathering information from multiple agents at a single location. This can increase communication requirements and expose locally collected information.

### Research objective

The research investigates an efficient intrusion-detection framework for UAV swarm networks, with an emphasis on privacy-preserving learning, communication-aware features, and the constraints of distributed aerial systems.

### Proposed feature representation

The modeled communication and mobility information includes:

- **3D distance:** Spatial separation between communicating UAVs or network entities.
- **Elevation angle:** Geometric information relevant to aerial communication.
- **SNR:** Signal-to-noise ratio, indicating signal quality relative to noise.
- **SINR:** Signal-to-interference-plus-noise ratio, accounting for interference as well as noise.
- **Channel gain:** A representation of the wireless channel's effect on the transmitted signal.
- **Interference:** Information about competing transmissions.
- **UAV speed:** Mobility information that can influence communication patterns.
- **Communication status:** Indicators describing the state of a communication link or interaction.

These features provide complementary physical-layer, mobility, and communication information that can be investigated for distinguishing normal behavior from potentially suspicious activity.

### Research workflow

**1. Data preparation**

Communication and mobility features are organized into a consistent representation suitable for model training and evaluation.

**2. Intrusion-detection model**

Python and PyTorch provide the implementation environment for developing and evaluating the detection model.

**3. Privacy-preserving learning**

Federated learning is a potential mechanism for training across distributed UAV agents without routinely collecting all raw local data at a central server. Its actual privacy guarantees depend on the threat model, aggregation design, and any additional mechanisms employed.

**4. Evaluation**

The framework should be assessed using detection-oriented metrics such as precision, recall, F1-score, false-positive rate, and detection latency. Resource overhead and performance under changing communication conditions are also important.

### Research contribution

The goal is to investigate whether distributed learning and communication-aware features can support efficient intrusion detection in UAV swarm environments while limiting unnecessary raw-data sharing.

The work must distinguish the privacy benefits of decentralized data handling from formal privacy guarantees, and must evaluate detection quality against appropriate centralized and non-federated baselines.

**Research areas:** UAV Networks · Federated Learning · Intrusion Detection · PyTorch · Wireless Communication · Privacy-Preserving AI

**Status:** Ongoing research under the supervision of Dr. Karan Verma, NIT Delhi.

</details>

### How my research connects

| Research direction | Main challenge | Core techniques |
|---|---|---|
| RIS-assisted UAV communication | Communication efficiency, coordination, and secrecy | FedMAPPO, federated learning, wireless channel modeling |
| UAV trajectory optimization | Scalable coordination and collision-free motion | ICDATS reference workflow, CPA geometry, vertical staging |
| UAV intrusion detection | Threat detection under distributed constraints | Communication features, PyTorch, federated-learning research |
| Student attendance and attentiveness | Face analysis and automated records | Haar Cascade, DLIB, LBPH, OpenCV, MySQL |

The common theme across these projects is **building intelligent systems that account for the constraints of the environment in which they operate**.

---

## 🚀 Featured Projects

<details open>
<summary><b>01 — AI Document Assistant using Retrieval-Augmented Generation (RAG)</b></summary>

**Focus:** Generative AI · LLM Applications · Semantic Search

### Problem

Large language models can produce useful explanations but may not have access to the contents of a user's private documents. They can also generate answers that are not adequately supported by the available material.

### Solution

I developed a document question-answering workflow using Retrieval-Augmented Generation. The system retrieves relevant document content and uses that context to guide the language model's response.

### Pipeline

`PDF Upload → Text Extraction → Chunking → Embedding Generation → FAISS Retrieval → Context Assembly → LLM Response`

### Main components

- **Document processing:** Converts document content into representations suitable for retrieval.
- **Text chunking:** Divides lengthy documents into smaller passages that can be retrieved independently.
- **Embeddings:** Maps text into vector representations that capture semantic relationships.
- **FAISS:** Supports efficient similarity search over document embeddings.
- **LangChain:** Helps organize the retrieval and generation workflow.
- **Prompt engineering:** Supplies relevant retrieved context to guide answer generation.

### Engineering considerations

A robust RAG system requires more than a vector database. Retrieval quality depends on chunk size, overlap, embedding quality, similarity thresholds, and document structure.

The quality of the generated answer also depends on whether the retrieved passages contain sufficient evidence. Retrieval evaluation and answer-grounding checks are therefore important areas for improvement.

**Technologies:** Python, LangChain, Hugging Face, Sentence Transformers, FAISS.

</details>

<details>
<summary><b>02 — Animal Re-Identification for Wildlife Monitoring</b></summary>

**Focus:** Computer Vision · Fine-Grained Recognition · Representation Learning

### Problem

Wildlife monitoring often requires identifying the same animal across different images captured by different cameras or at different times. Changes in viewpoint, lighting, pose, background, and partial occlusion make this challenging.

### Solution

I developed an animal re-identification pipeline using pretrained visual representations and feature interaction techniques.

### Pipeline

`Wildlife Images → Preprocessing → Visual Feature Extraction → Feature Interaction → Similarity Evaluation → Identity Matching`

### Main components

- **ATRW and LeopardID2022:** Benchmarks used in the project for animal re-identification experiments.
- **CLIP ViT-B/16:** A pretrained vision transformer used to extract informative visual representations.
- **Gated Cross-Attention:** Used to support interactions between feature representations.
- **Multi-scale feature extraction:** Helps capture visual information at different levels of detail.
- **Partial backbone fine-tuning:** Adapts selected pretrained components to the target task.
- **PyTorch, OpenCV, YOLOv8 and CUDA:** Support model development and computer-vision processing.

### Why CLIP?

CLIP provides pretrained visual representations learned through image-text alignment. These representations offer a useful starting point for transfer learning, while task-specific fine-tuning and feature interaction help adapt the model to the fine-grained identity discrimination problem.

### Result

**84.08% mAP** — the reported mean Average Precision for the project configuration.

Mean Average Precision evaluates retrieval quality across ranked candidate matches. The result should be interpreted alongside the dataset split, evaluation protocol, and baseline methods used in the experiment.

**Technologies:** Python, PyTorch, CLIP ViT-B/16, OpenCV, YOLOv8, CUDA.

</details>

<details>
<summary><b>03 — Time-Series Signal Anomaly Detection using LSTM Autoencoder</b></summary>

**Focus:** Deep Learning · Sequential Modeling · Model Deployment

### Problem

Time-series data can contain abnormal patterns that differ from normal temporal behavior. Such anomalies may be difficult to identify through fixed thresholds alone, especially when the signal's behavior changes over time.

### Solution

I implemented an LSTM Autoencoder that learns to reconstruct normal signal sequences. Reconstruction error is then used as an anomaly score.

### Pipeline

`Time-Series Data → Cleaning and Scaling → Sliding Windows → LSTM Encoder → Latent Representation → LSTM Decoder → Reconstruction Error → Anomaly Decision`

### How it works

1. **Preprocessing:** Clean and scale the sequential signal.
2. **Sliding windows:** Convert the time series into fixed-length sequences.
3. **Encoder:** Use an LSTM to learn temporal dependencies and compress each sequence into a latent representation.
4. **Decoder:** Reconstruct the input sequence from the learned representation.
5. **Anomaly scoring:** Calculate the difference between the original and reconstructed sequences.
6. **Thresholding:** Flag sequences whose reconstruction errors exceed a selected threshold.
7. **Deployment:** Expose inference through FastAPI, containerize the service with Docker, and provide an interactive interface through Streamlit.

### Important considerations

Anomaly detection depends on the quality of the normal training data and the threshold-selection procedure. A useful evaluation should measure precision, recall, F1-score, false alarms, and detection delay, rather than relying only on reconstruction loss.

**Technologies:** Python, PyTorch, NumPy, Pandas, Scikit-learn, FastAPI, Docker, Streamlit.

</details>

<details>
<summary><b>04 — Schema Scence: Query-Aware RDB-to-NoSQL Transformation</b></summary>

**Focus:** Database Engineering · Query Workloads · Data Migration

### Problem

Relational databases organize information using tables and relationships, while document-oriented NoSQL databases store information using flexible document structures. A direct table-to-collection conversion may not produce an efficient design for the application's query workload.

### Solution

I developed a query-aware schema evaluation and migration workflow for investigating relational-to-document database transformation.

### Pipeline

`PostgreSQL Schema → SQL Workload Analysis → DAG Representation → Candidate Schema Evaluation → Transformation → MongoDB Migration → Comparison Dashboard`

### Main components

- **Relational schema modeling:** Represents tables, relationships, and dependencies.
- **Query workload analysis:** Uses SQL query patterns to understand application access requirements.
- **DAG representation:** Models schema dependencies and relationships for analysis.
- **Schema evaluation:** Uses a six-metric scoring pipeline within the project's QBMetrics–Metamorfose hybrid approach.
- **Migration processing:** Supports relational-to-document transformation and MongoDB data migration.
- **Distributed processing:** Uses Apache Spark and MapReduce concepts for migration processing.
- **Streamlit dashboard:** Presents schema structures, query workloads, migration steps, and comparison results.

### Engineering perspective

The objective is not to assume that NoSQL is always faster than SQL. Instead, the project explores how query patterns and data relationships can inform schema design and migration decisions.

A rigorous comparison should consider query latency, join or lookup overhead, storage duplication, update complexity, and workload characteristics.

**Technologies:** Python, PostgreSQL, MongoDB, Apache Spark, Streamlit.

</details>

<details>
<summary><b>05 — Deepfake Audio Detection using Deep Learning</b></summary>

**Focus:** Audio AI · Signal Processing · Binary Classification

### Problem

AI-generated and manipulated speech can resemble authentic speech, making audio authenticity difficult to determine through casual listening alone.

### Solution

I developed a deep learning pipeline for analyzing speech representations and distinguishing authentic from potentially manipulated audio.

### Pipeline

`Audio Input → Resampling and Normalization → MFCC / Mel-Spectrogram → CNN Feature Extraction → LSTM Temporal Modeling → Classification → Evaluation`

### Main components

- **Librosa:** Supports audio loading and feature extraction.
- **MFCC:** Represents spectral characteristics useful for speech analysis.
- **Mel-spectrograms:** Represent the distribution of signal energy over time and frequency.
- **CNN layers:** Learn local patterns in the time-frequency representation.
- **LSTM layers:** Model temporal dependencies in the learned features.
- **Evaluation:** Uses classification reports and confusion matrices to analyze prediction behavior.

The project investigates audio-based authenticity classification using ASVspoof and real-world audio data. Robust evaluation requires attention to speaker overlap, recording conditions, dataset imbalance, and the difference between training and test distributions.

**Technologies:** Python, TensorFlow, Keras, Librosa, NumPy, LSTM.

</details>

<details>
<summary><b>06 — Student Attentiveness and Attendance System</b></summary>

**Focus:** Computer Vision · Face Recognition · Database Integration

### Problem

Manual attendance recording can be time-consuming, and classroom monitoring can require repeated administrative effort.

### Solution

This published project combines face detection, facial processing, recognition, and database management to support automated attendance recording and classroom attentiveness monitoring.

### Pipeline

`Classroom Image → Face Detection → Facial Processing → LBPH Recognition → Student Identity → MySQL Record → Attendance Information`

### Main components

- **Haar Cascade:** Used for face detection.
- **DLIB:** Used for facial feature processing.
- **LBPH:** Local Binary Patterns Histograms-based face recognition.
- **OpenCV:** Provides computer-vision processing.
- **MySQL:** Stores student and attendance information.

The system explores how face analysis and database integration can support classroom attendance workflows. Recognition reliability depends on lighting, pose, image quality, enrollment data, and the recognition threshold.

**Technologies:** Python, OpenCV, DLIB, Haar Cascade, LBPH, MySQL.

**Publication:** IRJMETS, Volume 06, Issue 04, April 2024.

</details>

---

## 🛠️ Technical Skills

<details open>
<summary><b>Programming and Data Processing</b></summary>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

</details>

<details>
<summary><b>Machine Learning and Deep Learning</b></summary>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

Regression, classification, clustering, neural networks, CNNs, LSTMs, autoencoders, U-Net, transfer learning, feature engineering, fine-tuning, and model evaluation.

</details>

<details>
<summary><b>Generative AI and LLM Engineering</b></summary>

![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Search-2563EB?style=flat-square)

LLMs, Transformers, Retrieval-Augmented Generation, prompt engineering, embeddings, semantic search, vector retrieval, context assembly, and context-aware AI applications.

</details>

<details>
<summary><b>Computer Vision and Audio AI</b></summary>

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Librosa](https://img.shields.io/badge/Librosa-Audio%20Processing-7C3AED?style=flat-square)

CLIP, YOLOv8, DLIB, Haar Cascade, LBPH, CNNs, MFCC, Mel-spectrograms, audio classification, and representation learning.

</details>

<details>
<summary><b>Databases and Data Engineering</b></summary>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

Relational and NoSQL databases, schema design, SQL workloads, schema transformation, query-aware optimization, migration pipelines, DAG modeling, Spark, and MapReduce.

</details>

<details>
<summary><b>APIs, Deployment and Engineering Tools</b></summary>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

FastAPI, REST APIs, Docker, Streamlit, ONNX Runtime, Git, Linux, model inference, application integration, and deployment workflows.

</details>

---

## 📄 Research Publication

### Student Attentiveness and Attendance System

**International Research Journal of Modernization in Engineering Technology and Science (IRJMETS)**

- **Volume:** 06
- **Issue:** 04
- **Publication:** April 2024
- **Authors:** Kirti Kushwah, Archit Jain, Ashutosh Kumar, Devyansh Sinha, Piyush

The paper presents a computer-vision-based approach to attendance and classroom attentiveness monitoring using Haar Cascade, DLIB, LBPH, OpenCV, and MySQL.

**Read the paper:** [Student Attentiveness and Attendance System — PDF](https://www.irjmets.com/uploadedfiles/paper/issue_4_april_2024/54308/final/fin_irjmets1714726617.pdf)

---

## 💼 Professional Experience

### CSE Trainee — National Thermal Power Corporation (NTPC)

**June 2023 – July 2023**

- Developed Python scripts for operational data processing and workflow automation.
- Worked with MySQL databases for data-driven backend workflows.
- Integrated database operations with REST API-based workflows.
- Gained practical exposure to backend development and operational data management.

---

## 👥 Leadership and Achievements

### Training & Placement Coordinator — NIT Delhi

- Coordinate placement-related communication between students and recruiters.
- Support recruitment activities and placement coordination.
- Assist with student-recruiter interactions and placement-related information management.

### General Secretary — TROH Society

**Inderprastha Engineering College**

- Led student initiatives and coordinated society activities.
- Organized technical and social events.
- Supported planning, teamwork, and execution of student-led initiatives.

### 🥉 MathWorks CodeMATrix Sprint Hackathon — Third Place

Secured third place in the MathWorks CodeMATrix Sprint Hackathon.

The experience strengthened my ability to interpret problem statements, develop practical technical solutions, experiment under time constraints, and communicate implementation decisions.

### Certifications

- Oracle Database Foundations — Oracle Academy.
- AWS Cloud Practitioner Essentials — Amazon Web Services.

---

## 📊 GitHub Activity

<p align="center">
  <a href="https://github.com/Ashutoshkumar422">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=Ashutoshkumar422&show_icons=true&hide_border=true&include_all_commits=true&rank_icon=github&theme=default#gh-light-mode-only" alt="GitHub statistics"/>
  </a>
  <a href="https://github.com/Ashutoshkumar422">
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ashutoshkumar422&layout=compact&hide_border=true&theme=default#gh-light-mode-only" alt="Most used languages"/>
  </a>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Ashutoshkumar422&hide_border=true&theme=default" alt="GitHub contribution streak"/>
</p>

<p align="center">
  <i>Statistics are generated by third-party services and may not include every repository or contribution.</i>
</p>

---

## 🎯 Current Research and Learning Interests

I'm particularly interested in exploring:

- **Generative AI:** LLM applications, RAG, agentic AI, and reliable retrieval.
- **Computer Vision:** Fine-grained recognition, re-identification, and multimodal learning.
- **Federated Learning:** Distributed training, communication efficiency, and privacy-aware AI.
- **Multi-Agent Reinforcement Learning:** Coordination, policy optimization, and decentralized decision-making.
- **UAV Swarm Intelligence:** Trajectory planning, collision avoidance, communication optimization, and intrusion detection.
- **Time-Series AI:** Anomaly detection, sequential representation learning, and robust evaluation.
- **AI Engineering:** Efficient inference, API integration, deployment, and model optimization.
- **Data Engineering:** Query-aware database design, schema transformation, and scalable data processing.

---

## 🌱 My Engineering Philosophy

> Learn the fundamentals → Build the system → Evaluate the results → Identify limitations → Optimize → Deploy → Keep improving.

I believe strong AI engineering requires more than selecting a model or framework. It requires understanding the data, assumptions, algorithms, evaluation protocol, system architecture, deployment constraints, and the problem being solved.

I aim to build systems that are not only technically interesting but also measurable, reproducible, and useful.

---

## 🤝 Let's Connect

I'm interested in AI/ML engineering opportunities, research collaborations, Generative AI, computer vision, and intelligent systems.

<p align="center">
  <a href="https://www.linkedin.com/in/ashutoshkumar2910/">
    <img src="https://img.shields.io/badge/LinkedIn-Ashutosh%20Kumar-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/Ashutoshkumar422">
    <img src="https://img.shields.io/badge/GitHub-Ashutoshkumar422-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="mailto:ashutoshkumarskt.29@gmail.com">
    <img src="https://img.shields.io/badge/Email-Say%20Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

<p align="center">
  <b>Thanks for visiting my profile!</b><br/>
  Let's build intelligent, reliable, and impactful AI systems. 🚀
</p>
