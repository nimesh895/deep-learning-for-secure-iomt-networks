# Deep Learning for Secure IoMT Networks  
**A Comprehensive Literature Review on Intrusion Detection and Attack Mitigation (2026)**

**Author**: K.H.N.A Peiris  
**Domain**: Cybersecurity | Healthcare Technology | Artificial Intelligence  

---

### Project Overview

This independent research project presents an in-depth literature review exploring the application of deep learning techniques for network attack detection and mitigation in Internet of Medical Things (IoMT) environments. As healthcare systems become increasingly interconnected, the attack surface has expanded dramatically. This work systematically analyzes 15 high-impact studies from Q1 and Q2 journals and conferences to evaluate state-of-the-art deep learning solutions and their practical implications for real-world medical networks.

The review focuses on four core areas:  
- Advanced deep learning architectures for intrusion detection  
- Privacy-preserving federated learning frameworks  
- Hybrid reinforcement learning models for adaptive mitigation  
- Performance evaluation on modern IoMT-specific datasets  

The goal is to provide a clear synthesis of current capabilities, identify critical research gaps, and propose actionable directions for building more resilient and trustworthy healthcare security systems.

### Research Objectives

- Examine the evolution of deep learning methods (CNN, LSTM, CNN-LSTM, BERT hybrids, and deep reinforcement learning) specifically for IoMT intrusion detection  
- Assess privacy-preserving techniques, particularly federated learning, in compliance with healthcare regulations  
- Compare model performance across key metrics (accuracy, F1-score, false positive reduction) using datasets such as CICIoMT2024 and ToN-IoT  
- Analyze real-world implications for edge devices, 5G networks, and clinical environments  
- Identify persistent challenges and recommend future research priorities  

### Key Findings & Technical Insights

The reviewed literature demonstrates that hybrid deep learning models consistently outperform traditional approaches in high-dimensional, time-varying IoMT traffic. Notable results include:

- LSTM networks achieving **97% accuracy** on intrusion detection tasks  
- CNN-LSTM hybrids reaching **99% accuracy** through combined spatial-temporal feature extraction  
- BERT-integrated hybrid models delivering **99.9% accuracy** with significant reduction in false positives  
- Hybrid deep reinforcement learning (DDPG-based) models providing adaptive mitigation in dynamic 5G medical environments  

Federated learning emerged as a standout solution for privacy preservation, enabling collaborative model training without sharing sensitive patient data. Ensemble and hybrid approaches further improved robustness against multi-class attacks such as DoS, man-in-the-middle, spoofing, and scanning.

### Visual Analysis & Contributions

To enhance understanding, the project includes:
- **IoMT Architecture Diagram** – illustrating connectivity layers and attack surfaces  
- **Performance Comparison Table** – summarizing top model accuracies  
- **Accuracy Bar Chart** – visual comparison of LSTM, CNN-LSTM, Hybrid BERT, and Hybrid RL models  
- **Research Gaps Visualization** – highlighting challenges in datasets, scalability, explainability, and privacy  

These visuals were created to translate complex technical concepts into clear, actionable insights.

### Challenges Identified

Despite significant advancements, several critical limitations remain:
- Scarcity of large-scale, labelled IoMT-specific datasets  
- Resource constraints on edge devices limiting deployment of complex models  
- Lack of explainable AI (XAI) integration, reducing clinical trust  
- Privacy and regulatory compliance challenges in centralized training environments  

### Proposed Future Directions

Future work should focus on:
- Development of new public IoMT benchmarks incorporating 5G and edge scenarios  
- Lightweight hybrid models optimized for resource-constrained medical devices  
- Integration of explainable AI techniques (SHAP, LIME) into intrusion detection systems  
- Advanced federated learning frameworks combined with differential privacy and blockchain for enhanced security and non-repudiation  
- Adaptive systems capable of evolving with emerging threats without frequent retraining  

### Repository Structure

Deep-Learning-IoMT-Intrusion-Detection-Literature-Review/
├── Final_Paper.pdf                  # Complete 8-page literature review  
├── figures/                         # All diagrams and charts
│   ├── IoMT_Architecture.png
│   ├── Accuracy_Comparison_Chart.png
│   └── Research_Gaps_Visualization.png
├── sources_link.txt                 # OneDrive folder containing all 15 reference papers
├── video_summary.txt                # Link to 4-minute project explanation video
└── README.md


### Technologies & Models Reviewed

- Convolutional Neural Networks (CNN)  
- Long Short-Term Memory (LSTM) & CNN-LSTM hybrids  
- Bidirectional Encoder Representations from Transformers (BERT)  
- Deep Deterministic Policy Gradient (DDPG) Reinforcement Learning  
- Federated Learning  
- Datasets: CICIoMT2024, ToN-IoT, BlueTack  

### Personal Note

This project reflects my deep interest in the intersection of artificial intelligence and healthcare security. Through this independent research, I aimed to bridge the gap between academic literature and practical deployment challenges in connected medical systems. The insights gained have strengthened my understanding of how deep learning can safeguard patient lives and data in an increasingly digital healthcare landscape.

I welcome feedback, discussions, and potential collaboration from researchers and professionals working in IoMT security, deep learning for cybersecurity, or healthcare technology.

---

**Made with dedication to building safer healthcare systems.**

⭐ If you found this project valuable, please star the repository.  
Open to connections and opportunities in cybersecurity research.

K.H.N.A Peiris  
Cybersecurity Enthusiast | IoMT Security Researcher
