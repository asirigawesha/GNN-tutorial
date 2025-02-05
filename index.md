---
layout: default
---

<!-- **\[UPDATE\]** We kindly ask you to fill in this [anonymous form](https://docs.google.com/forms/d/1Am4LBsYtyOVzo3axIRqYOC7vHOB5BQ9aSMyvTsjjF7I/edit) regarding the overall quality of the tutorial. As we are planning to present it to other venues, your feedback might be extremely important for us 🙏🙂 -->

## Overview of the Tutorial

This workshop is designed to provide participants with an in-depth understanding of TinyML (Tiny Machine Learning), focusing on compression techniques, practical applications like keyword spotting and plant disease identification, and the development of end-to-end pipelines. By combining theoretical insights and hands-on sessions, participants will gain the skills necessary to implement TinyML in real-world scenarios.


## GNN Tutorial Schedule

| Time Duration         | Description                                      | Resource Person            |
|----------------------|------------------------------------------------|----------------------------|
| 8:30 – 9:10 (40 min) | - Introduction to tutorial  <br> - Introduction to GNN and its applications <br> - Basic graph theory <br> - Graph neural networks <br> - Message passing GNN (MPGNN) | Dr. Mahima Weerasinghe    |
| 9:10 - 9:20 (10 min) | **Break**                                      |                            |
| 9:20 – 10:00 (40 min) | - GCN architecture <br> - GAT architecture     | Mr. Sanka Mohottala        |
| 10:00 – 10:40 (40 min) | - GNN application (Coding session)             | Mr. Asiri Gawesha          |
| 10:40 – 11:20 (40 min) | - New frontiers of GNN                         | Mr. Jeewaka Perera         |
| 11:20 – 11:30 (10 min) | - Q and A session                              | All resource persons will be present |


## Target Audience
This workshop is suitable for:
- Machine learning enthusiasts, students, and professionals interested in edge AI.
- Developers aiming to optimize ML models for resource-constrained devices.
- Educators and researchers exploring the latest advancements in TinyML.

## Learning Objectives
Participants will:
1. Understand the significance and applications of TinyML.
2. Explore key model compression techniques: Quantization and Pruning.
3. Develop TinyML models for head pose estimation.
4. Gain proficiency in tools like Google Colab, TFLite, and Android Studio for TinyML deployment.
5. Discover emerging research opportunities in TinyML and brainstorm innovative use cases.

## Workshop Agenda
### **Introduction**
- **Objective:** Welcome participants, introduce TinyML, and outline workshop goals.
- Agenda and logistics for the day.
- Brief discussion on the importance of TinyML in real-world applications.

### **TinyML Background and Compression Techniques**
- **Slides:** Overview of TinyML and key techniques:
  - Quantization
  - Pruning
  - Knowledge Distillation
- **Hands-On (Google Colab):**
  - Implement Post-Training Quantization (PTQ): Full integer, Float 16, and Dynamic range.
  - Compare PTQ with Quantization-Aware Training (QAT).
  - Pruning demonstration to reduce model size while retaining accuracy.

### **TinyML for Head Pose Estimation**
- **Slides:** Overview of the head pose estimation pipeline using TinyML.
- **Hands-On (Google Colab):**
  - Train and export a model for head pose estimation.
- **Android App Development:**
  - Guide participants to use Android Studio for building an app integrating the trained model.
  - **Note:** Ensure participants have Android Studio pre-installed.

### **Advanced Applications in TinyML**

## Required Materials and Prerequisites
- A laptop with Google Colab access and Android Studio pre-installed.
- Basic understanding of machine learning and Python programming.
- Basic understanding of Android, Java, and Android Studio.
- Enthusiasm for exploring TinyML applications!

## Outcomes
By the end of the workshop, participants will:
- Design and optimize TinyML models using state-of-the-art techniques.
- Deploy TinyML models on embedded devices and mobile applications.
- Identify advanced applications of TinyML.

**Closing remarks and Q&A**: 10 minutes

## Additional useful material

| Title | Paper                                                                                     | Slides                                                                                    | Code                                                           | Venue     | Year |
|---|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|----------------------------------------------------------------|----------|------|
| How Neighborhood Exploration Influences Novelty and Diversity in Graph Collaborative Filtering | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/MORS.pdf)   | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/MORS.pdf)   | [link](https://github.com/sisinflab/Novelty-Diversity-Graph)   | MORS @ RecSys  | 2022 |
| Auditing Consumer- and Producer-Fairness in Graph Collaborative Filtering | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/ECIR.pdf)   | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/ECIR.pdf)   | [link](https://github.com/sisinflab/ECIR2023-Graph-CF)         | ECIR           | 2023 |
| An Out-of-the-Box Application for Reproducible Graph Collaborative Filtering extending the Elliot Framework | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/UMAP.pdf)   | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/UMAP.pdf)   | [link](https://github.com/sisinflab/Graph-Demo)                | UMAP/GLB @ KDD | 2023 |
| Challenging the Myth of Graph Collaborative Filtering: a Reasoned and Reproducibility-driven Analysis | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/RecSys.pdf) | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/RecSys.pdf) | [link](https://github.com/sisinflab/Graph-RSs-Reproducibility) | RecSys         | 2023 |
| A Topology-aware Analysis of Graph Collaborative Filtering | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/arXiv.pdf)  |                                                                                           | [link](https://github.com/sisinflab/Graph-Characteristics)     | arXiv          | 2023 |
| Disentangling the Performance Puzzle of Multimodal-aware Recommender Systems | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/KDD.pdf) | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/KDD.pdf) | [link](https://github.com/sisinflab/MultiModal-Eval) | EvalRS@KDD | 2023 |
| On Popularity Bias of Multimodal-aware Recommender Systems: a Modalities-driven Analysis | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/MM.pdf)     |  [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/MMIR.pdf)                                                                                          | [link](https://github.com/sisinflab/MultiMod-Popularity-Bias)  | MMIR @ MM      | 2023 |
| Formalizing Multimedia Recommendation through Multimodal Deep Learning | [link](https://dl.acm.org/doi/pdf/10.1145/3662738)   |                                                                                           | [link](https://github.com/sisinflab/Formal-MultiMod-Rec)                                                       | arXiv          | 2023 |

## Facilitators

### **Dr. Dinuka Sahabandu**
![Dr. Dinuka Sahabandu](path/to/image.jpg)
Dr. Dinuka Sahabandu is a Senior Lecturer (HG) at the Department of Computer Science, Faculty of Computing, Sri Lanka Institute of Information Technology (SLIIT). He received his Ph.D. from the Department of Electrical and Computer Engineering at the University of Washington, Seattle, WA, USA. His research interests include the security and privacy of machine learning algorithms, applications of game theory and learning for cybersecurity, and the control of multi-agent networks. He also shares an interest in the theoretical aspects of graph neural networks and their applications.

### **Mr. Asiri Gawesha**
![Mr. Asiri Gawesha](path/to/image.jpg)
Asiri Gawesha is a Research Assistant and an MPhil candidate at the Department of Software Engineering, Faculty of Computing, Sri Lanka Institute of Information Technology (SLIIT). His research focuses on image processing, computer vision, edge computing, and cloud computing. His professional achievements include developing AI-powered autism screening tools and optimizing deep learning models for edge devices.

### **Mr. Sanka Mohottala**
![Mr. Sanka Mohottala](path/to/image.jpg)
Sanka Mohottala is a Research Assistant and an MPhil candidate at the Department of Computer Science, Faculty of Computing, Sri Lanka Institute of Information Technology (SLIIT). His research interests include Graph Neural Networks (GNNs), data-efficient deep learning methods, and computer vision. He has hands-on experience in developing GNN-based models across multiple domains.

## Conclusion
This workshop offers a comprehensive introduction to TinyML, emphasizing practical skills and future possibilities. Join us to unlock the potential of machine learning on tiny devices and revolutionize edge computing!

## **Facilitators Team**
<p align="center">
  <img src="path/to/image1.jpg" width="200">
  <img src="path/to/image2.jpg" width="200">
  <img src="path/to/image3.jpg" width="200">
</p>
