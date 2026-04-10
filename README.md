# 👋 Hi, I'm Aldrin Lizardo

**BS Computer Science Graduate** | **Polytechnic University of the Philippines**  
🎓 Former Intern at Accenture | 🤖 ML Enthusiast | 📊 Data & Automation

---

## 🔗 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aldrin-lizardo-0abb29280/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Laacertaa)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aldrinlizardoa@gmail.com)

---

## 🚀 Featured Project: Filipino Sign Language Recognition Dataset Builder

### Thesis | Semi-supervised Machine Learning | December 2024

**Problem:** Labeled Filipino Sign Language (FSL) data is extremely sparse, limiting the development of assistive technologies for the Deaf community in the Philippines.

**Solution:** Built an automated dataset builder using **Semi-supervised Co-training** with SVM and KNN classifiers to label unlabeled FSL video data.

### 🛠️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Language** | Python |
| **ML Libraries** | Scikit-learn (SVM, KNN), PyTorch, TensorFlow/Keras |
| **Computer Vision** | MediaPipe, OpenCV, InceptionV3 |
| **Data Collection** | Scrapy (web scraping) |
| **Sequence Model** | GRU (Gated Recurrent Unit) - 32 units |

### 📊 Key Results

#### Co-training Model (SVM + KNN) vs. Standalone SVM

| Metric | SVM + KNN Co-training | SVM Classifier (Standalone) |
| :--- | :--- | :--- |
| **Accuracy** | **89.31%** | 61.07% |
| **Precision** | 89.46% | 89.53% |
| **Recall** | **89.31%** | 61.07% |
| **F1 Score** | **88.89%** | 67.03% |

**✅ Improvement:** Co-training outperformed standalone SVM by **+28.24% in accuracy** and **+21.86% in F1 score**

#### GRU Model Performance (for FSL Recognition)

| Dataset Used | Accuracy | Precision | Recall | F1 Score |
| :--- | :--- | :--- | :--- | :--- |
| Co-training Dataset | 8.70% | 8.89% | 80.00% | 16.00% |
| SVM Classifier Dataset | 13.04% | 27.27% | 8.57% | 13.19% |

> **Note:** The GRU model struggled with class imbalance and over-prediction bias, highlighting areas for future optimization such as better data preprocessing and alternative architectures (transformers, hybrid CNN-RNN).

### 🔬 What I Contributed

- **Web Scraping Pipeline:** Built automated data collection using Python's **Scrapy** library to scrape unlabeled FSL video data from online sources (educational websites, social media, video platforms)
- **Data Preprocessing & Feature Extraction:** Managed the end-to-end preprocessing pipeline using **MediaPipe** to extract hand keypoints, perform background subtraction, and isolate signer movements from video frames
- **Co-training Implementation:** Implemented the iterative co-training loop logic between SVM and KNN classifiers for semi-supervised labeling
- **Performance Evaluation:** Conducted model evaluation using confusion matrices, precision/recall/F1 calculations, and paired t-tests (p < 0.05) to prove statistical significance
- **FSL Expert Collaboration:** Worked with certified FSL experts to validate ground truth labels and ensure cultural/linguistic accuracy of the dataset

### 📄 Thesis Abstract

> *"The co-training approach, which integrates Support Vector Machines (SVM) and K-Nearest Neighbors (KNN), was evaluated and compared to a standalone SVM classifier. The co-training approach achieved 89.31% accuracy, indicating that it correctly classified a significant portion of samples through its iterative labeling process. In contrast, the standalone SVM classifier achieved a much lower accuracy of 61.07%, showing that without the collaborative mechanism of KNN, it struggled to make accurate predictions."*

**📬 Request the full thesis manuscript:** [Send me an email](mailto:aldrinlizardoa@gmail.com?subject=Request%20for%20FSL%20Thesis%20Manuscript)

---

## 💼 Experience Highlights

| Role | Company | Key Skills |
| :--- | :--- | :--- |
| **Computer Science Intern** | Accenture | QA testing, Git, Agile methodologies, test case execution, code reviews |
| **Customer Care / Retention Agent** | Empata/VoiceTeam PH | Retention strategy, conflict resolution, KPI management, QA score compliance |
| **Collections Agent** | Fort Rolins | Compliance (Data Privacy Act), negotiation, high-volume calls (80+/day) |
| **Customer Service Representative** | ProbeCX | CRM platforms, chat/phone support, escalations, KPI tracking |

---

## 📫 Reach Me

- **Email:** aldrinlizardoa@gmail.com
- **LinkedIn:** [linkedin.com/in/aldrin-lizardo-0abb29280/](https://www.linkedin.com/in/aldrin-lizardo-0abb29280/)
- **Location:** Pasig City, Metro Manila, Philippines

---

*Built with Python ☕ and a passion for accessible technology.*
