# 👋 Hi, I'm Ashutosh Kumar

### Generative AI | Machine Learning | Deep Learning | Computer Vision | AI Research

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1000&color=36BCF7&center=true&vCenter=true&width=850&lines=Building+Intelligent+AI+Systems;Exploring+LLMs+and+Retrieval-Augmented+Generation;Developing+Computer+Vision+and+Deep+Learning+Solutions;Researching+Federated+Learning+and+Multi-Agent+Reinforcement+Learning" alt="Animated introduction" />
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

I'm pursuing an **M.Tech in Computer Science and Engineering (Analytics) at the National Institute of Technology Delhi**. My interests include Generative AI, Large Language Models, Retrieval-Augmented Generation, Machine Learning, Deep Learning, Computer Vision, Time-Series Anomaly Detection, and Federated Learning.

I enjoy building AI applications, experimenting with deep learning architectures, and exploring how research methods can be developed into practical systems.

- 🎓 M.Tech CSE (Analytics), NIT Delhi.
- 🤖 Interested in LLMs, RAG, and Generative AI applications.
- 🧠 Building solutions in computer vision and time-series analysis.
- 🔬 Researching physics-guided federated multi-agent reinforcement learning.
- 🛠️ Working with Python, PyTorch, TensorFlow, FastAPI, Docker, and AI tooling.
- 👥 Training and Placement Coordinator at NIT Delhi.
- 🏆 Third place in the MathWorks CodeMATrix Sprint Hackathon.

---

## 🧭 Navigation

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

### FeedbackForage — AI-Powered Customer Feedback Intelligence Platform

**Tech Stack:** Python, Streamlit, SentenceTransformers, BERTopic, DistilBERT, ChromaDB, LangGraph, RAG, OpenAI API, Plotly

FeedbackForage is an AI-powered platform that transforms customer reviews from app stores and social media into actionable business insights. It combines NLP, machine learning, semantic search, and generative AI to identify recurring customer concerns, analyze sentiment, and support data-driven product decisions.

<details>
<summary><strong>Explore Project Details</strong></summary>

**Key Features**

- **Multi-Source Data Processing:** Collects, cleans, normalizes, and deduplicates customer feedback from multiple sources.
- **Topic Modeling:** Uses BERTopic with UMAP, HDBSCAN, and c-TF-IDF to discover recurring customer issues and product-related themes.
- **Sentiment Analysis:** Applies DistilBERT to classify reviews as positive or negative and combines sentiment with topic-level analysis.
- **Semantic Search and RAG:** Uses SentenceTransformers (`all-MiniLM-L6-v2`) and ChromaDB to retrieve relevant reviews and generate context-grounded answers using an LLM.
- **Multi-Agent Architecture:** Uses LangGraph to coordinate query routing, feedback retrieval, visualization, summarization, and proposed ticket generation with human approval.
- **Interactive Dashboard:** Uses Streamlit and Plotly to explore customer sentiment, topic distributions, trends, and feedback insights.

**Documented Data Pipeline**

- 7,156 raw feedback records collected from multiple sources.
- 600 unique reviews after deduplication.
- Approximately 2,000 records after documented NLP-based augmentation.

**End-to-End Workflow**

`Data Collection → Preprocessing → Embeddings → Topic Modeling + Sentiment Analysis → ChromaDB → RAG + LangGraph Agents → Streamlit Dashboard`

**Key Objective:** Convert unstructured customer feedback into searchable evidence, interpretable insights, and potential actions for product improvement.

</details>

**Repository:** [GitHub](YOUR_REPOSITORY_URL) · 


## 2. 🤖 AI Document Assistant Using Retrieval-Augmented Generation (RAG)

**Repository:** [View Project on GitHub](REPLACE_WITH_RAG_REPOSITORY_URL)

An AI-powered document question-answering application that combines semantic retrieval with language-model generation to help users find relevant information in PDF documents.

<details>
<summary><strong>📖 Read the Full Project Explanation</strong></summary>

### Problem Statement

Searching lengthy documents manually can be time-consuming. Keyword-based search can also overlook relevant passages when a user's wording differs from the document's wording.

This project explores Retrieval-Augmented Generation (RAG), which retrieves relevant document content and supplies it to a language model to generate context-aware answers.

### System Architecture

**1. Document ingestion**

Accept PDF documents as input.

**2. Text extraction**

Extract readable text from the documents using the document-processing pipeline.

**3. Text chunking**

Split the extracted text into smaller passages suitable for embedding and retrieval.

**4. Embedding generation**

Use Sentence Transformers or another configured embedding model to convert text chunks into vector representations.

**5. Vector indexing**

Store embeddings in a FAISS index for similarity-based retrieval.

**6. Query processing**

Convert a user's question into an embedding using the compatible embedding model.

**7. Semantic retrieval**

Retrieve relevant passages from the vector index.

**8. Context construction**

Combine the retrieved passages into context for the language model.

**9. Answer generation**

Generate a response using the question and retrieved context.

### End-to-End Pipeline

`PDF → Text Extraction → Chunking → Embeddings → FAISS Index → Semantic Retrieval → Context Construction → LLM Response`

### Technical Highlights

- Semantic search over document content.
- Vector indexing with FAISS.
- Modular document ingestion and retrieval.
- Integration of an LLM with retrieved context.
- Extensible design for experimenting with embedding models and retrieval strategies.

### Technology Stack

`Python` `LangChain` `Hugging Face` `Sentence Transformers` `FAISS` `LLMs` `RAG`

### Possible Extensions

- Source citations and page-level references.
- Hybrid search and reranking.
- Retrieval-quality evaluation.
- Answer-grounding and faithfulness checks.

</details>

---

## 3. 🐆 Animal Re-Identification for Wildlife Monitoring

**Repository:** [View Project on GitHub](REPLACE_WITH_ANIMAL_REID_REPOSITORY_URL)

**Duration:** April 2026 – May 2026 | **Reported result:** 84.08% mAP

A computer-vision system designed to identify individual animals across different images for wildlife monitoring and conservation applications, using CLIP ViT-B/16, gated cross-attention, and multi-scale visual features.

<details>
<summary><strong>📖 Read the Full Project Explanation</strong></summary>

### Problem Statement

Wildlife images are captured under varying lighting conditions, poses, camera angles, and backgrounds. Identifying the same animal across different images is challenging because its appearance may change considerably between observations.

Animal re-identification focuses on distinguishing individual animals rather than simply predicting their species.

### Datasets

- **ATRW:** Amur tiger re-identification dataset.
- **LeopardID2022:** Leopard identification dataset.

### Model Architecture

**1. Image preprocessing**

Prepare input images using the required resizing, normalization, and transformation steps.

**2. CLIP ViT-B/16 feature extraction**

Use the pretrained vision-transformer backbone to extract rich visual representations.

**3. Gated Cross-Attention**

Integrate complementary feature information through a gated cross-attention mechanism.

**4. Multi-scale features**

Capture visual information at different scales to represent both broad appearance and localized distinguishing characteristics.

**5. Partial fine-tuning**

Adapt selected pretrained components to the animal re-identification task.

**6. Similarity-based retrieval**

Compare image embeddings to rank candidate images for a query animal.

### Pipeline

`Wildlife Images → Preprocessing → CLIP ViT-B/16 → Feature Extraction → Gated Cross-Attention → Embeddings → Similarity Ranking → Animal Re-Identification`

### Why CLIP Instead of a Conventional CNN?

CLIP learns visual representations through image-text pretraining, which can provide transferable semantic features. A conventional CNN can also be effective, but its representation quality depends on the architecture, training data, and objective.

The benefit of CLIP should be assessed through controlled comparisons rather than assumed automatically.

### Technical Highlights

- Vision-transformer-based feature extraction.
- Gated cross-attention for feature integration.
- Multi-scale feature representation.
- Partial fine-tuning of a pretrained backbone.
- Image similarity and retrieval for animal identification.

### Technology Stack

`Python` `PyTorch` `CLIP ViT-B/16` `Gated Cross-Attention` `YOLOv8` `OpenCV` `CUDA`

</details>

---

## 4. 📈 Time-Series Signal Anomaly Detection Using an LSTM Autoencoder

**Repository:** [View Project on GitHub](REPLACE_WITH_LSTM_ANOMALY_REPOSITORY_URL)

**Duration:** February 2026 – April 2026

A reconstruction-based anomaly detection system that learns temporal patterns from time-series data and identifies unusual observations using an LSTM Autoencoder.

<details>
<summary><strong>📖 Read the Full Project Explanation</strong></summary>

### Problem Statement

Time-series signals can contain unexpected changes caused by equipment faults, sensor errors, unusual system behavior, or other abnormal conditions.

An LSTM Autoencoder learns to reconstruct input sequences. When trained on representative normal data, it can help identify sequences that differ from learned temporal patterns.

### Model Architecture

**1. Data preprocessing**

Inspect the data, handle missing values, normalize input features, and create chronological training, validation, and test splits.

**2. Sliding-window generation**

Convert continuous signals into fixed-length sequences that preserve local temporal relationships.

**3. LSTM encoder**

Encode each sequence into a compact latent representation.

**4. Latent representation**

Capture important information about the sequence's temporal behavior.

**5. LSTM decoder**

Reconstruct the input sequence from its encoded representation.

**6. Reconstruction error**

Compare the original sequence and its reconstruction using an error function such as mean squared error.

**7. Threshold-based detection**

Flag sequences whose reconstruction errors exceed a threshold selected using validation data.

### Pipeline

`Time-Series Data → Preprocessing → Sliding Windows → LSTM Encoder → Latent Representation → LSTM Decoder → Reconstruction Error → Anomaly Detection`

### Mathematical Foundation

For an input sequence \(X\) and its reconstruction \(\hat{X}\), mean squared reconstruction error can be expressed as:

\[
E(X)=\frac{1}{N}\sum_{i=1}^{N}(X_i-\hat{X}_i)^2
\]

An observation may be classified as anomalous when:

\[
E(X)>\tau
\]

where \(\tau\) is the selected detection threshold.

### Application and Deployment

- **PyTorch:** Model implementation and training.
- **NumPy and Pandas:** Numerical computation and data processing.
- **Scikit-learn:** Supporting preprocessing and evaluation utilities.
- **FastAPI:** API layer for model inference.
- **Docker:** Application packaging and deployment.
- **Streamlit:** Interactive user interface and visualization.

### Technical Highlights

- Sequential modeling with LSTM layers.
- Reconstruction-based anomaly detection.
- Sliding-window time-series processing.
- Configurable anomaly threshold.
- API-oriented inference workflow.

### Technology Stack

`Python` `PyTorch` `LSTM` `Autoencoders` `NumPy` `Pandas` `Scikit-learn` `FastAPI` `Docker` `Streamlit`

</details>

---

## 5. 🗄️ Schema Scence — Query-Aware Optimization for RDB-to-NoSQL Transformation

**Repository:** [View Project on GitHub](REPLACE_WITH_SCHEMA_SCENCE_REPOSITORY_URL)

**Duration:** April 2026 – May 2026

A database transformation project exploring query-aware relational-to-NoSQL schema design, using relationship analysis, candidate schema evaluation, and data migration workflows.

<details>
<summary><strong>📖 Read the Full Project Explanation</strong></summary>

### Problem Statement

Relational databases represent data through tables, keys, and relationships. Document-oriented databases organize data differently, often using embedded documents or references.

Simply converting each relational table into a document collection may not preserve efficient query execution. Schema design should therefore consider how the application accesses and combines data.

### System Workflow

**1. Relational schema analysis**

Inspect tables, columns, primary keys, foreign keys, and relationships in PostgreSQL.

**2. Query workload analysis**

Consider the application's query patterns to identify data frequently accessed together.

**3. Relationship representation**

Represent relevant schema dependencies using a directed acyclic graph (DAG), where applicable.

**4. Candidate NoSQL model generation**

Explore alternative document designs, including embedding and referencing strategies.

**5. Schema scoring**

Apply the project's six-metric scoring approach to compare candidate designs. The exact metrics and weights should follow the implemented scoring configuration.

**6. Data transformation**

Transform relational records into the chosen document-oriented structure.

**7. Migration**

Use the configured migration workflow and Apache Spark where appropriate to transfer data into MongoDB.

**8. Interactive interface**

Use Streamlit to expose relevant schema and migration functionality.

### Pipeline

`PostgreSQL → Schema Analysis → Query Workload Analysis → Relationship DAG → Candidate Document Models → Multi-Metric Scoring → Data Migration → MongoDB`

### Technical Highlights

- Query-aware relational-to-document transformation.
- Schema relationship analysis.
- Embedding-versus-referencing design considerations.
- Hybrid approach involving QBMetrics and Metamorfose concepts.
- Six-metric schema evaluation.
- Spark-based data migration workflow.
- Interactive Streamlit interface.

### Technology Stack

`Python` `PostgreSQL` `MongoDB` `Apache Spark` `Streamlit` `DAGs` `Database Migration`

</details>

---

## 6. 🎙️ Deepfake Audio Detection Using Deep Learning

**Repository:** [View Project on GitHub](REPLACE_WITH_DEEPFAKE_AUDIO_REPOSITORY_URL)

**Duration:** November 2025 – December 2025

A deep learning-based audio classification project that explores detecting manipulated or synthetically generated speech through acoustic feature extraction and neural-network modeling.

<details>
<summary><strong>📖 Read the Full Project Explanation</strong></summary>

### Problem Statement

Modern speech synthesis and voice-cloning systems can generate realistic audio. Detecting synthetic or manipulated speech is an important challenge in media authenticity and audio security.

This project explores the use of acoustic representations and deep learning to distinguish genuine speech from spoofed audio.

### Audio Processing Pipeline

**1. Dataset preparation**

Prepare labeled real and spoofed audio samples. ASVspoof datasets provide relevant benchmarks for audio spoofing research.

**2. Audio preprocessing**

Load audio samples, standardize sampling rates where necessary, and apply consistent segmentation and normalization.

**3. Feature extraction**

Generate acoustic representations such as:

- **MFCCs:** Mel-Frequency Cepstral Coefficients representing characteristics of the spectral envelope.
- **Mel-spectrograms:** Time-frequency representations on the Mel frequency scale.

**4. CNN feature extraction**

Use convolutional layers to learn local patterns in time-frequency representations.

**5. LSTM temporal modeling**

Use recurrent layers to capture temporal dependencies across audio frames.

**6. Classification**

Generate predictions for the configured genuine-versus-spoofed audio classes.

### Pipeline

`Audio Input → Preprocessing → MFCC / Mel-Spectrogram → CNN → LSTM → Classification`

### Technical Highlights

- Audio signal preprocessing.
- MFCC and Mel-spectrogram feature extraction.
- CNN-based acoustic feature learning.
- LSTM-based temporal modeling.
- Deep learning for synthetic audio detection.

### Technology Stack

`Python` `TensorFlow` `Keras` `Librosa` `CNN` `LSTM` `MFCC` `Mel-Spectrograms`

</details>

---

## 7. 👁️ Student Attentiveness and Attendance System

**Repository:** [View Project on GitHub](REPLACE_WITH_ATTENDANCE_PROJECT_REPOSITORY_URL)

**Publication:** IRJMETS, Volume 6, Issue 4, April 2024

A computer-vision-based classroom system designed to support face detection, student identification, and attendance recording using OpenCV, Haar Cascade, DLIB, LBPH, and MySQL.

<details>
<summary><strong>📖 Read the Full Project Explanation</strong></summary>

### Problem Statement

Manual attendance recording can take classroom time and introduce errors. Face detection and recognition can help automate parts of attendance management.

This project combines image processing, face recognition, and database operations in an attendance-oriented workflow.

### System Architecture

**1. Image or video capture**

Capture classroom frames using a camera.

**2. Face detection**

Use Haar Cascade-based detection to identify candidate face regions.

**3. Facial processing**

Use DLIB-based face processing as part of the configured computer-vision pipeline.

**4. Face recognition**

Use Local Binary Patterns Histograms (LBPH) for recognition based on local facial texture patterns.

**5. Student identification**

Match recognized faces against enrolled student records.

**6. Attendance recording**

Store attendance-related information in MySQL.

**7. Attentiveness-related functionality**

Describe or evaluate any attentiveness functionality according to what is actually implemented. Visual cues should not be treated as definitive evidence of a student's attention or understanding.

### Pipeline

`Camera Input → Frame Processing → Face Detection → Facial Processing → LBPH Recognition → Attendance Logic → MySQL`

### Technical Highlights

- Face detection using Haar Cascade.
- DLIB-based facial processing.
- LBPH-based face recognition.
- Database-backed attendance records.
- Python and OpenCV integration.

### Technology Stack

`Python` `OpenCV` `Haar Cascade` `DLIB` `LBPH` `MySQL`

### Publication

**“Student Attentiveness and Attendance System”** was published in the *International Research Journal of Modernization in Engineering Technology and Science (IRJMETS)*, Volume 6, Issue 4, April 2024.

</details>

---

# 🔬 Research Portfolio

## Physics-Guided Federated Multi-Agent Reinforcement Learning for RIS-Carrying UAV Swarms

**Publication venue:** *Vehicular Communications*  
**Status:** Manuscript under review

Research on a physics-guided federated multi-agent reinforcement learning framework for coordinating RIS-carrying UAVs in blockage-prone urban wireless environments.

<details>
<summary><strong>📖 Read the Full Research Overview</strong></summary>

### Research Motivation

Buildings and other obstructions can weaken direct wireless communication links in urban environments. UAVs carrying Reconfigurable Intelligent Surfaces (RISs) provide a potential approach for improving communication conditions through aerial positioning and controllable signal reflection.

Coordinating multiple UAVs requires balancing communication quality, user association, interference, energy consumption, and the information available to individual agents.

This work studies a federated multi-agent learning approach in which agents perform local policy updates and periodically aggregate model information.

### Proposed Framework

The framework combines communication-system modeling with a federated version of Multi-Agent Proximal Policy Optimization (MAPPO).

Its design considers:

- **Blockage-aware channel modeling:** Incorporates urban propagation conditions.
- **RIS-carrying UAV coordination:** Studies multiple aerial agents in a shared wireless environment.
- **Federated learning:** Supports local model updates followed by federated aggregation.
- **FedMAPPO:** Combines federated aggregation with multi-agent policy optimization.
- **Aggregation strategies:** Compares resource-aware and uniform aggregation.
- **User association:** Incorporates constraint-aware association and matching decisions.
- **Aerial relaying:** Considers half-duplex decode-and-forward relaying.
- **Secrecy-aware optimization:** Includes passive eavesdroppers and secrecy-related reward terms.
- **Energy-aware communication:** Considers communication performance alongside resource constraints.

Federated learning by itself does not guarantee complete privacy; privacy depends on the aggregation protocol and any additional safeguards.

### Learning Workflow

`Urban Environment → Channel Modeling → Multi-Agent Observations → Local MAPPO Updates → Federated Aggregation → Policy Updates → User Association and UAV Coordination → Communication Evaluation`

### Simulation Configuration

| Parameter | Configuration |
|---|---|
| Urban area | 620 × 620 m |
| Number of buildings | 72 |
| Base station position | (-200, 0, 25) |
| UAV agents | 12 |
| Users | 50 |
| Passive eavesdroppers | 2 |
| User clusters | 4 |
| Clustered users | 60% |
| Training episodes | 3,000 |

### Evaluation Focus

The research studies energy efficiency, user data rates, fairness, training convergence, scalability, the effect of federated aggregation strategies, and communication performance under blockage and passive eavesdropping.

### Research Contribution

The central direction is to integrate physics-informed wireless-system modeling with federated multi-agent policy learning to study coordination, resource utilization, and communication performance in blocked urban environments.

### Technology Stack

`Python` `PyTorch` `Federated Learning` `MAPPO` `Reinforcement Learning` `RIS` `UAV Networks` `Wireless Communications`

### Manuscript Status

The manuscript is **under review at *Vehicular Communications***. It is not represented as an accepted or published paper.

</details>

---

# 🧰 Technical Skills

### Programming Languages

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL"/>
</p>

### Machine Learning and Deep Learning

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
</p>

### Generative AI and LLMs

<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/RAG-6A5ACD?style=for-the-badge" alt="RAG"/>
  <img src="https://img.shields.io/badge/FAISS-Vector_Search-007ACC?style=for-the-badge" alt="FAISS"/>
</p>

### Computer Vision and Audio Processing

<p>
  <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/CLIP-Vision_Models-5B5BD6?style=for-the-badge" alt="CLIP"/>
  <img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge" alt="YOLOv8"/>
  <img src="https://img.shields.io/badge/Librosa-Audio_Processing-8A2BE2?style=for-the-badge" alt="Librosa"/>
</p>

### APIs, Deployment, and Tools

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

### Databases and Data Engineering

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark"/>
</p>

---

# 🎓 Education

### National Institute of Technology Delhi

**M.Tech — Computer Science and Engineering (Analytics)**  
2025 – 2027

### Inderprastha Engineering College, Ghaziabad

**B.Tech — Computer Science and Engineering**  
2020 – 2024

---

# 📄 Publication

### Student Attentiveness and Attendance System

**Journal:** International Research Journal of Modernization in Engineering Technology and Science (IRJMETS)  
**Volume:** 6 | **Issue:** 4 | **April 2024

Research and development involving computer vision, face detection, face recognition, and attendance-related automation using Python, OpenCV, Haar Cascade, DLIB, LBPH, and MySQL.

---

# 💼 Experience

### CSE Trainee — NTPC

**June 2023 – July 2023**

- Gained exposure to a professional technical environment.
- Developed an understanding of technical workflows and engineering practices.

---

# 👥 Leadership & Achievements

### 🎯 Training and Placement Coordinator — NIT Delhi

- Support placement-related coordination and communication.
- Assist with student engagement and placement activities.

### 🏛️ General Secretary — TROH Society

- Contribute to student-community coordination and organizational activities.
- Support collaboration and participation in student initiatives.

### 🏆 MathWorks CodeMATrix Sprint Hackathon

**Achievement: 3rd Place**

Participated in a technical hackathon focused on problem-solving and practical solution development.

---

# 📜 Certifications

- Oracle Database Foundations
- AWS Cloud Practitioner Essentials

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

- Building practical Generative AI and RAG applications.
- Strengthening Machine Learning, Deep Learning, and Computer Vision foundations.
- Developing reproducible experiments for federated multi-agent reinforcement learning.
- Improving model evaluation, deployment, and software engineering skills.

---

# 📫 Let's Connect

<p align="center">
  <a href="https://github.com/Ashutoshkumar422">
    <img src="https://img.shields.io/badge/GitHub-Explore_My_Projects-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/ashutoshkumar2910/">
    <img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
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
