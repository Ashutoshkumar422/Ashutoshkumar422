# 👋 Hi, I'm Ashutosh Kumar

### Generative AI · Machine Learning · Deep Learning · Computer Vision · AI Engineering

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1000&color=36BCF7&center=true&vCenter=true&width=850&lines=Building+Intelligent+AI+Systems;Exploring+LLMs%2C+RAG%2C+and+Generative+AI;Developing+Deep+Learning+and+Computer+Vision+Solutions;Researching+Federated+Learning+and+Multi-Agent+RL" alt="Animated introduction" />
</p>

<p align="center">
  <a href="https://github.com/Ashutoshkumar422">
    <img src="https://img.shields.io/badge/GitHub-Ashutoshkumar422-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/ashutoshkumar2910/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
  <a href="mailto:ashutoshkumarskt.29@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## 🧑‍💻 About Me

I'm an **M.Tech Computer Science and Engineering (Analytics) student at the National Institute of Technology Delhi**, passionate about developing intelligent, scalable, and practical AI systems.

My interests span **Generative AI, Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), Machine Learning, Deep Learning, Computer Vision, Time-Series Anomaly Detection, and Federated Learning**.

I enjoy taking ideas from research and experimentation toward working applications, with an emphasis on understanding the underlying algorithms, building reliable pipelines, evaluating model performance, and exploring real-world deployment.

- 🎓 Pursuing M.Tech in CSE (Analytics) at **NIT Delhi**.
- 🤖 Exploring LLM applications, RAG pipelines, and AI-powered systems.
- 🧠 Developing deep learning solutions for computer vision and time-series analysis.
- 🔬 Conducting research on physics-guided federated multi-agent reinforcement learning.
- 🛠️ Working with Python, PyTorch, TensorFlow, FastAPI, Docker, and modern AI tooling.
- 👥 Serving as a **Training and Placement Coordinator** at NIT Delhi.
- 🏆 Secured **3rd place in the MathWorks CodeMATrix Sprint Hackathon**.

---

## 🧭 Quick Navigation

- [Featured Projects](#-featured-projects)
- [Research Portfolio](#-research-portfolio)
- [Technical Skills](#-technical-skills)
- [Education](#-education)
- [Publication](#-publication)
- [Experience](#-experience)
- [Leadership and Achievements](#-leadership--achievements)
- [Certifications](#-certifications)
- [GitHub Statistics](#-github-statistics)
- [Contact](#-lets-connect)

---

# 🚀 Featured Projects

My projects cover Generative AI, computer vision, deep learning, data engineering, audio analysis, and intelligent applications. Expand any project to explore its objectives, architecture, implementation, and technical highlights.

## 1. 🌾 FeedbackForage — Feedback Collection and Analysis

**Project focus:** Feedback-oriented application  
**Status:** Project details and implementation information to be added

FeedbackForage is included in my featured project portfolio. The following section is reserved for the project's verified description, functionality, implementation, and results.

<details>
<summary><strong>📖 Read the full project explanation</strong></summary>

### Project Overview

**Project description:** Add the actual problem statement and explain what FeedbackForage is designed to accomplish, who its intended users are, and how it addresses the target problem.

### Key Features

- Describe the core functionality.
- Explain the user workflow and the main use cases.
- Document any feedback collection, organization, analysis, or reporting features that are actually implemented.
- Explain the project's distinguishing features and practical value.

### Architecture and Implementation

Add the verified architecture, data flow, modules, and implementation details here.

### Technology Stack

`Add verified technologies`

### Results and Evaluation

Include actual testing results, performance measurements, or demonstrated outcomes, if available.

### Project Links

- **Repository:** Add the FeedbackForage repository URL.
- **Demo:** Add a live demo URL if available.

</details>

---

## 2. 🤖 AI Document Assistant Using Retrieval-Augmented Generation (RAG)

**Domain:** Generative AI · LLMs · Semantic Search  
**Technologies:** Python, LangChain, Hugging Face, Sentence Transformers, FAISS

An AI-powered document question-answering system designed to retrieve relevant information from PDF documents and use the retrieved context to generate grounded, context-aware responses.

<details>
<summary><strong>📖 Read the full project explanation</strong></summary>

### Problem Statement

Searching large documents manually is time-consuming. Conventional keyword search may also miss relevant information when a question uses wording different from the source document.

The objective of this project is to build a document assistant that combines semantic retrieval with language-model generation.

### System Architecture

1. **Document ingestion:** Accept PDF documents as input.
2. **Text extraction:** Extract readable text from the documents.
3. **Text chunking:** Divide the extracted content into smaller, manageable passages.
4. **Embedding generation:** Convert the chunks into numerical semantic representations using a Sentence Transformer.
5. **Vector indexing:** Store the embeddings in a FAISS vector index.
6. **Query processing:** Encode the user's question into an embedding.
7. **Semantic retrieval:** Retrieve relevant document chunks using vector similarity.
8. **Context construction:** Assemble retrieved passages into a context for the language model.
9. **Response generation:** Generate a response using the retrieved information and the selected LLM.

### Pipeline

`PDF → Text Extraction → Chunking → Embeddings → FAISS Index → Semantic Retrieval → Context Assembly → LLM Response`

### Technical Highlights

- Semantic rather than purely keyword-based retrieval.
- Vector search for efficient retrieval of relevant passages.
- Modular document-ingestion and question-answering pipeline.
- Context-grounded generation to help reduce unsupported answers.
- Extensible design for experimenting with different embedding models and LLMs.

### Technology Stack

`Python` `LangChain` `Hugging Face` `Sentence Transformers` `FAISS` `LLMs` `RAG`

### Potential Improvements

- Add source citations and page-level references.
- Evaluate retrieval quality using Recall@K, Precision@K, and MRR.
- Measure answer quality and faithfulness.
- Experiment with reranking, hybrid search, and alternative chunking strategies.

</details>

---

## 3. 🐆 Animal Re-Identification for Wildlife Monitoring

**Duration:** April 2026 – May 2026  
**Domain:** Computer Vision · Wildlife Monitoring · Visual Recognition  
**Reported result:** **84.08% mAP**  
**Technologies:** CLIP ViT-B/16, Gated Cross-Attention, YOLOv8, OpenCV, CUDA

A deep learning-based animal re-identification system designed to distinguish individual animals across different images, supporting wildlife monitoring and conservation-related applications.

<details>
<summary><strong>📖 Read the full project explanation</strong></summary>

### Problem Statement

Wildlife monitoring often relies on camera-trap images collected at different locations and times. Identifying the same animal across images is challenging because of changes in viewpoint, lighting, pose, occlusion, and background.

Animal re-identification aims to learn visual representations that help distinguish individual animals rather than merely classify their species.

### Dataset

The project uses wildlife re-identification datasets including:

- **ATRW:** Amur tiger re-identification dataset.
- **LeopardID2022:** Leopard identification dataset.

Dataset-specific splits and preprocessing should be maintained consistently during training and evaluation to avoid data leakage.

### Model Architecture

**1. Image preprocessing**

Images are prepared for model input using the required resizing, normalization, and transformation pipeline.

**2. Visual feature extraction**

CLIP ViT-B/16 is used as the visual feature backbone to obtain semantically rich image representations.

**3. Gated Cross-Attention**

A gated cross-attention mechanism is incorporated to help combine complementary feature information and emphasize potentially discriminative visual cues.

**4. Multi-scale feature representation**

Multi-scale features help capture both broader appearance patterns and more localized visual characteristics.

**5. Partial fine-tuning**

Selected parts of the pretrained network can be fine-tuned for the wildlife re-identification task while retaining useful pretrained representations.

**6. Similarity-based identification**

Extracted image representations can be compared to rank candidate matches for a query animal image.

### Pipeline

`Wildlife Images → Preprocessing → CLIP ViT-B/16 → Feature Extraction → Gated Cross-Attention → Embedding Representation → Similarity Ranking → Re-Identification`

### Why CLIP Instead of a Conventional CNN?

CLIP is pretrained using image-text pairs, providing rich visual representations that can transfer to downstream tasks. A conventional CNN can be effective for image recognition, but its representations depend heavily on the training objective and dataset.

The use of CLIP does not automatically guarantee better re-identification. The advantage must be established through controlled experiments against appropriate CNN and vision-transformer baselines.

### Evaluation

The project achieved a **reported mean Average Precision (mAP) of 84.08%**.

For a re-identification task, evaluation should also consider Rank-1 accuracy, retrieval quality, and performance across different identities and dataset splits.

### Technology Stack

`Python` `PyTorch` `CLIP` `Vision Transformers` `Gated Cross-Attention` `YOLOv8` `OpenCV` `CUDA`

### Applications

- Wildlife population monitoring.
- Individual animal identification.
- Camera-trap image analysis.
- Conservation research and movement studies.

</details>

---

## 4. 📈 Time-Series Signal Anomaly Detection Using an LSTM Autoencoder

**Duration:** February 2026 – April 2026  
**Domain:** Deep Learning · Time-Series Analysis · Anomaly Detection  
**Technologies:** PyTorch, NumPy, Pandas, Scikit-learn, FastAPI, Docker, Streamlit

A time-series anomaly detection system that learns normal temporal patterns through an LSTM Autoencoder and identifies unusual observations using reconstruction error.

<details>
<summary><strong>📖 Read the full project explanation</strong></summary>

### Problem Statement

Time-series signals often contain irregular patterns that may indicate faults, unexpected behavior, sensor issues, or abnormal operating conditions.

Manually defining thresholds for every signal can be difficult, particularly when normal behavior changes over time. This project explores reconstruction-based anomaly detection using a recurrent neural network.

### Why an LSTM Autoencoder?

Long Short-Term Memory (LSTM) networks are designed to learn sequential dependencies. An autoencoder learns to reconstruct its input, allowing the model to capture patterns present in the training data.

When trained primarily on normal observations, an LSTM Autoencoder may reconstruct familiar patterns more accurately than unusual patterns.

### Model Architecture

**1. Data preprocessing**

- Load and inspect time-series observations.
- Handle missing or invalid values.
- Normalize features using training-set statistics.
- Split the signal into chronological training, validation, and test sets.

**2. Sliding-window generation**

Transform the continuous signal into overlapping windows of fixed length so the model can learn temporal dependencies.

**3. LSTM encoder**

Compress each input window into a latent representation.

**4. Latent representation**

Represent the important temporal information learned from the input sequence.

**5. LSTM decoder**

Reconstruct the original sequence from the learned representation.

**6. Reconstruction-error calculation**

Compare the original sequence with its reconstruction using an appropriate error measure, such as mean squared error.

**7. Anomaly detection**

Flag observations or windows whose reconstruction error exceeds a threshold calibrated on validation data.

### Pipeline

`Time-Series Data → Preprocessing → Sliding Windows → LSTM Encoder → Latent Representation → LSTM Decoder → Reconstruction Error → Threshold-Based Detection`

### Mathematical Foundation

For an input window \(X\) and reconstructed window \(\hat{X}\), a simple reconstruction loss is:

\[
L_{\mathrm{reconstruction}}
=
\frac{1}{N}\sum_{i=1}^{N}(X_i-\hat{X}_i)^2
\]

An observation can be flagged as anomalous when its reconstruction error exceeds a chosen threshold:

\[
\operatorname{Anomaly}(X)=
\begin{cases}
1, & E(X)>\tau\\
0, & E(X)\leq\tau
\end{cases}
\]

Here, \(E(X)\) is the reconstruction error and \(\tau\) is the detection threshold. The threshold should be selected using validation data rather than tuned against the final test set.

### Deployment

- **FastAPI:** Provides an API layer for submitting data and returning predictions.
- **Docker:** Packages the application and its dependencies into a reproducible environment.
- **Streamlit:** Provides an interactive interface for data exploration and anomaly visualization.

### Evaluation Considerations

Useful metrics include precision, recall, F1-score, PR-AUC, false-positive rate, and detection delay, depending on the dataset and operational requirements.

### Technology Stack

`Python` `PyTorch` `LSTM` `Autoencoders` `NumPy` `Pandas` `Scikit-learn` `FastAPI` `Docker` `Streamlit`

</details>

---

## 5. 🗄️ Schema Scence — Query-Aware Optimization for RDB-to-NoSQL Transformation

**Duration:** April 2026 – May 2026  
**Domain:** Data Engineering · Database Migration · Query Optimization  
**Technologies:** PostgreSQL, MongoDB, Apache Spark, Streamlit

A query-aware database transformation project focused on translating relational database structures into NoSQL document models while considering access patterns and migration requirements.

<details>
<summary><strong>📖 Read the full project explanation</strong></summary>

### Problem Statement

Relational databases and document-oriented databases organize information differently.

A relational schema typically represents relationships through tables, keys, and joins. A document database such as MongoDB can represent related data through embedding or references. A direct table-to-collection conversion may therefore fail to preserve efficient query behavior.

The project explores a query-aware approach to relational-to-NoSQL transformation.

### System Workflow

**1. Relational schema analysis**

Inspect tables, columns, keys, and relationships from the source relational database.

**2. Query workload analysis**

Consider representative query patterns to understand which data is accessed together and which operations are important.

**3. Schema relationship representation**

Represent relevant schema relationships and transformation dependencies using a directed acyclic graph (DAG), where applicable.

**4. Candidate schema generation**

Explore alternative document-model designs, including embedding and referencing strategies.

**5. Schema evaluation**

Use a six-metric scoring approach to compare candidate designs. The exact metric definitions and weights should be documented in the implementation so that the scoring remains reproducible.

**6. Data migration**

Use Apache Spark and a migration pipeline to transform and transfer data into the target document-oriented database.

**7. Interactive analysis**

Use Streamlit to present schema choices, migration information, or evaluation results.

### Pipeline

`PostgreSQL Schema → Schema and Workload Analysis → Relationship DAG → Candidate NoSQL Models → Multi-Metric Evaluation → Migration Pipeline → MongoDB`

### Technical Highlights

- Query-aware relational-to-document transformation.
- Schema relationship analysis using a DAG representation.
- A hybrid approach combining QBMetrics and Metamorfose concepts.
- Multi-metric evaluation of candidate schema designs.
- Data migration using a Spark-based pipeline.
- An interactive interface for exploring the transformation workflow.

### Technology Stack

`Python` `PostgreSQL` `MongoDB` `Apache Spark` `Streamlit` `DAGs` `Database Migration`

### Evaluation Considerations

A rigorous evaluation can compare query latency, the number of joins or document lookups, data duplication, storage requirements, migration time, and workload performance. The final metrics should reflect those actually implemented and measured.

</details>

---

## 6. 🎙️ Deepfake Audio Detection Using Deep Learning

**Duration:** November 2025 – December 2025  
**Domain:** Audio Processing · Deep Learning · Synthetic Speech Detection  
**Technologies:** TensorFlow, Keras, Librosa, MFCC, Mel-Spectrograms, CNN-LSTM

A deep learning-based audio classification project focused on distinguishing genuine speech from manipulated or synthetically generated audio.

<details>
<summary><strong>📖 Read the full project explanation</strong></summary>

### Problem Statement

Advances in speech synthesis and voice cloning have made synthetic audio increasingly realistic. Detecting manipulated audio is important for research into media authenticity, voice-based security, and misinformation prevention.

The project investigates the use of audio signal features and deep learning models to identify patterns associated with genuine and synthetic speech.

### Audio Processing Pipeline

**1. Dataset preparation**

Prepare labeled real and spoofed audio examples. ASVspoof datasets are relevant benchmarks for spoofing and synthetic-speech detection.

**2. Audio preprocessing**

Load audio, standardize sampling rates where required, and apply consistent segmentation and normalization.

**3. Feature extraction**

Extract representations such as:

- **MFCCs:** Compact representations of the spectral envelope.
- **Mel-spectrograms:** Time-frequency representations on a Mel-scaled frequency axis.

**4. CNN feature learning**

Use convolutional layers to learn local time-frequency patterns from audio features.

**5. LSTM temporal modeling**

Use recurrent layers to capture sequential dependencies across audio frames.

**6. Classification**

Generate class predictions for real versus manipulated audio.

**7. Evaluation**

Assess the classifier using an appropriate held-out dataset and metrics suitable for imbalanced or security-sensitive classification.

### Pipeline

`Audio → Preprocessing → MFCC / Mel-Spectrogram → CNN Feature Extraction → LSTM Temporal Modeling → Classification → Evaluation`

### Technology Stack

`Python` `TensorFlow` `Keras` `Librosa` `CNN` `LSTM` `MFCC` `Mel-Spectrograms`

### Evaluation Considerations

Depending on the benchmark, useful metrics include precision, recall, F1-score, ROC-AUC, and equal error rate (EER). Testing on unseen speakers and different synthesis systems helps assess generalization.

</details>

---

## 7. 👁️ Student Attentiveness and Attendance System

**Publication:** IRJMETS, Volume 6, Issue 4, April 2024  
**Domain:** Computer Vision · Face Recognition · Classroom Analytics  
**Technologies:** Python, OpenCV, Haar Cascade, DLIB, LBPH, MySQL

A computer-vision-based classroom monitoring prototype designed to support face-based student identification and attendance recording, with attentiveness-related analysis.

<details>
<summary><strong>📖 Read the full project explanation</strong></summary>

### Problem Statement

Manual attendance tracking can consume classroom time and introduce record-keeping errors. Computer vision provides a way to automate parts of the process by detecting faces and identifying enrolled individuals.

The project combines face detection, face-related feature processing, recognition, and database storage.

### System Architecture

**1. Video capture**

Capture classroom images or video frames from a camera.

**2. Face detection**

Use Haar Cascade-based detection to locate candidate faces in each frame.

**3. Facial feature processing**

Use DLIB-based face processing as part of the computer-vision pipeline where applicable.

**4. Face recognition**

Use Local Binary Patterns Histograms (LBPH) for recognition based on local texture patterns.

**5. Attendance recording**

Match recognized identities with the student records and store attendance information in MySQL.

**6. Attentiveness-related analysis**

Process visual observations for the intended classroom monitoring workflow. Any attentiveness estimate should be treated as an imperfect visual proxy, not a definitive measurement of a student's attention or understanding.

### Pipeline

`Camera Input → Frame Processing → Face Detection → Facial Feature Processing → LBPH Recognition → Attendance Logic → MySQL Database`

### Technology Stack

`Python` `OpenCV` `Haar Cascade` `DLIB` `LBPH` `MySQL`

### Publication

The project was published as **“Student Attentiveness and Attendance System”** in *International Research Journal of Modernization in Engineering Technology and Science (IRJMETS)*, Volume 6, Issue 4, April 2024.

</details>

---

# 🔬 Research Portfolio

## Physics-Guided Federated Multi-Agent Reinforcement Learning for RIS-Carrying UAV Swarms

**Manuscript status:** Under review at *Vehicular Communications*  
**Research area:** Federated Learning · Multi-Agent Reinforcement Learning · Wireless Communications · Reconfigurable Intelligent Surfaces

This research investigates a physics-guided federated multi-agent reinforcement learning framework for coordinating RIS-carrying UAVs in blockage-prone urban wireless environments.

<details>
<summary><strong>📖 Read the full research overview</strong></summary>

### 1. Research Motivation

Urban wireless environments contain buildings and other obstructions that can weaken or interrupt direct communication links. UAVs equipped with Reconfigurable Intelligent Surfaces (RISs) offer a potential means of improving communication conditions through aerial positioning and controllable signal reflection.

However, coordinating multiple UAVs involves several coupled decisions, including user association, communication quality, energy consumption, and interference. Centralized learning may also require collecting information from multiple agents at a single location.

This research studies a federated multi-agent learning approach that allows agents to train locally and periodically aggregate model information.

### 2. Proposed Framework

The research combines physical communication modeling with a federated multi-agent reinforcement learning approach based on Multi-Agent Proximal Policy Optimization (MAPPO).

The framework considers:

- **Blockage-aware channel modeling:** Incorporates urban propagation conditions into communication evaluation.
- **RIS-carrying UAV coordination:** Studies coordinated aerial agents in an urban environment.
- **Federated learning:** Aggregates locally learned model parameters without requiring all raw local observations to be centralized.
- **FedMAPPO:** Combines federated aggregation with multi-agent policy optimization.
- **Aggregation strategies:** Compares resource-aware aggregation with uniform aggregation.
- **User association:** Incorporates constraint-aware association and matching decisions.
- **Aerial relaying:** Considers half-duplex decode-and-forward relaying.
- **Secrecy-aware optimization:** Includes passive eavesdroppers and secrecy-related reward terms in the communication objective.
- **Energy-aware operation:** Considers communication performance alongside UAV resource constraints.

Federated learning alone does not guarantee complete privacy. Its privacy properties depend on the aggregation protocol, information exchanged, and any additional privacy mechanisms.

### 3. Learning Workflow

`Urban Environment and Channel Model → Multi-Agent Observations → Local MAPPO Updates → Federated Aggregation → Updated Policies → UAV Coordination and User Association → Communication Evaluation → Reward and Policy Updates`

### 4. Simulation Environment

The simulation configuration includes the following parameters:

| Parameter | Configuration |
|---|---|
| Urban simulation area | 620 × 620 m |
| Number of buildings | 72 |
| Base station location | (-200, 0, 25) |
| Number of UAV agents | 12 |
| Number of users | 50 |
| Number of passive eavesdroppers | 2 |
| Number of clusters | 4 |
| Clustered user proportion | 60% |
| Training duration | 3,000 episodes |

These parameters describe the configured simulation scenario; they should not be interpreted as real-world deployment measurements.

### 5. Evaluation Objectives

The framework is evaluated with respect to multiple aspects of communication and learning performance, including:

- Energy consumption and energy efficiency.
- User data rate and communication performance.
- Fairness across users.
- Training convergence and reward trends.
- Scalability with the number of agents.
- Effects of federated aggregation strategies.
- Communication performance under blockage and passive eavesdropping.

The results should be interpreted against the selected baselines and the experimental settings used in the manuscript.

### 6. Research Contribution

The central research direction is to integrate physically informed wireless-system modeling with federated multi-agent policy learning for coordinated RIS-carrying UAVs.

The goal is to study how local learning, federated aggregation, and communication-aware reward design affect coordination, resource utilization, and wireless performance in blocked urban environments.

### Research Tools

`Python` `PyTorch` `Federated Learning` `MAPPO` `Reinforcement Learning` `RIS` `UAV Networks` `Wireless Channel Modeling`

### Manuscript

**Status:** Under review at *Vehicular Communications*. The manuscript is not yet an accepted or published article.

</details>

---

# 🧰 Technical Skills

## Programming Languages

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL"/>
</p>

## Machine Learning and Deep Learning

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
</p>

## Generative AI and LLMs

<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/RAG-6A5ACD?style=for-the-badge" alt="RAG"/>
  <img src="https://img.shields.io/badge/FAISS-Vector_Search-007ACC?style=for-the-badge" alt="FAISS"/>
  <img src="https://img.shields.io/badge/Transformers-Modeling-F4B400?style=for-the-badge" alt="Transformers"/>
</p>

## Computer Vision and Audio Processing

<p>
  <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/CLIP-Vision_Models-5B5BD6?style=for-the-badge" alt="CLIP"/>
  <img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge" alt="YOLOv8"/>
  <img src="https://img.shields.io/badge/Librosa-Audio_Processing-8A2BE2?style=for-the-badge" alt="Librosa"/>
</p>

## APIs, Deployment, and Tools

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

## Databases and Data Engineering

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark"/>
</p>

## Core Areas of Interest

- Generative AI and Large Language Models
- Retrieval-Augmented Generation and semantic search
- Machine Learning and Deep Learning
- Computer Vision and visual recognition
- Time-series modeling and anomaly detection
- Federated Learning and Multi-Agent Reinforcement Learning
- AI system development, evaluation, and deployment
- Wireless communication and intelligent UAV systems

---

# 🎓 Education

### National Institute of Technology Delhi

**M.Tech — Computer Science and Engineering (Analytics)**  
2025 – 2027

Focus areas: Machine Learning, Artificial Intelligence, Deep Learning, Data Analytics, and research-oriented AI systems.

### Inderprastha Engineering College, Ghaziabad

**B.Tech — Computer Science and Engineering**  
2020 – 2024

Undergraduate project: Student Attentiveness and Attendance System.

---

# 📄 Publication

### Student Attentiveness and Attendance System

**Published in:** International Research Journal of Modernization in Engineering Technology and Science (IRJMETS)  
**Volume:** 6 · **Issue:** 4 · **Month:** April 2024

The project explores computer-vision techniques for face detection, recognition, and attendance-related automation using Python, OpenCV, Haar Cascade, DLIB, LBPH, and MySQL.

---

# 💼 Experience

### CSE Trainee — NTPC

**June 2023 – July 2023**

- Gained exposure to a professional technical environment.
- Developed an understanding of technology workflows and practical engineering practices.

*Add specific responsibilities, tools, or outcomes here if you want this section to reflect the exact work completed during the training.*

---

# 👥 Leadership & Achievements

### 🎯 Training and Placement Coordinator — NIT Delhi

- Contribute to student placement-related coordination and communication.
- Support coordination between students and placement activities.
- Help facilitate information sharing and student engagement.

### 🏛️ General Secretary — TROH Society

- Contribute to student-community coordination and organizational activities.
- Support collaboration and participation in student initiatives.

### 🏆 MathWorks CodeMATrix Sprint Hackathon

**Achievement: 3rd Place**

Participated in a technical hackathon focused on problem-solving and developing practical solutions under time constraints.

---

# 📜 Certifications

- Oracle Database Foundations.
- AWS Cloud Practitioner Essentials.

---

# 📊 GitHub Statistics

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Ashutoshkumar422&show_icons=true&rank_icon=github&hide_border=true&include_all_commits=true" alt="GitHub statistics"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ashutoshkumar422&layout=compact&hide_border=true&langs_count=8" alt="Most used programming languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Ashutoshkumar422&hide_border=true" alt="GitHub contribution streak"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Ashutoshkumar422&style=flat-square&color=blue" alt="Profile views"/>
</p>

---

# 🎯 Current Focus

- Building and improving practical Generative AI and RAG applications.
- Strengthening foundations in Machine Learning, Deep Learning, and Computer Vision.
- Developing reproducible experiments for research in federated multi-agent reinforcement learning.
- Improving model evaluation, deployment practices, and software engineering skills.
- Exploring how AI research can translate into useful and reliable applications.

---

# 📫 Let's Connect

<p align="center">
  <a href="https://github.com/Ashutoshkumar422">
    <img src="https://img.shields.io/badge/GitHub-Explore_My_Projects-181717?style=for-the-badge&logo=github" alt="GitHub profile"/>
  </a>
  <a href="https://www.linkedin.com/in/ashutoshkumar2910/">
    <img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn profile"/>
  </a>
  <a href="mailto:ashutoshkumarskt.29@gmail.com">
    <img src="https://img.shields.io/badge/Email-Send_a_Message-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

<p align="center">
  <i>Learn continuously. Build thoughtfully. Experiment rigorously. Improve every day.</i>
</p>

<p align="center">
  ⭐ Thanks for visiting my profile!
</p>
