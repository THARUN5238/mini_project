**AGRICULTURAL TEXT CLASSIFICATION METHOD BASED ON DYNAMIC FUSION OF MULTIPLE FEATURES**

# 🌾 Agricultural Text Classification — Dynamic Fusion of Multiple Features

A **Text Classification System** designed to classify agricultural text based on phenotypic numerical values using a **Multi-Feature Dynamic Fusion model** combining CNN, Bi-LSTM, and Attention mechanisms.

🚀 Built using **Python + Django**, featuring ML pipelines and interactive web visualizations.

---

## 📌 Project Objectives

* Extract **global semantic features** using Bi-LSTM + Attention
* Extract **local multi-scale features** using Multiple CNN kernels
* Create a **numerical feature vector** for phenotypic attributes
* Use **Attention-based fusion** to dynamically weight multiple features
* Improve classification accuracy for agricultural datasets

---

## 🧠 System Architecture

* **Frontend** : HTML, CSS, JavaScript
* **Backend** : Django Framework
* **ML Models** : MLP-Classifier, GradientBoostingClassifier, Ensemble Voting
* **Database** : MySQL (WAMP Server)
* **Dataset** : `Datasets.csv` (Agricultural text)

---

## ✅ Features / Modules (Admin & User)

| Role                         | Features                                                                      |
| ---------------------------- | ----------------------------------------------------------------------------- |
| **Service Provider (Admin)** | Train & Test Datasets, Bar & Pie Charts, View Users, Download Classified Data |
| **Remote User**              | Register/Login, Predict Crop Classification, View Profile                     |

---

## 📊 Output Screens

* 🔹 Home Page
* 🔹 Service Provider Login
* 🔹 Dataset Upload & Train/Test
* 🔹 Accuracy View – **Bar Graph**
* 🔹 Classification Type – **Pie Chart**
* 🔹 Prediction Interface

> (Screens referenced from report pages: 45–48) 

---

## 🛠️ Setup & Installation

### ✅ Prerequisites

```bash
Python 3.x
Django Framework
MySQL / WAMP Server
```

### ✅ Install Dependencies

```bash
pip install -r requirements.txt
```

### ✅ Run Django Server

```bash
python manage.py runserver
```

---

## 📈 Model Accuracy

* Ensemble Learning using MLP + Gradient Boosting
* Voting Classifier used for final predictions
* Accuracy metrics displayed via bar charts ✔️

(Accuracy code confirmed in report ML section) 

---

## 📌 Future Enhancements

(According to report section) 

* Integrate **Transformers (BERT / GPT models)**
* Add **multimodal data** (images/videos)
* Real-time decision support using edge computing
* Incremental & adaptive learning

---

## 🏁 Conclusion

The proposed **dynamic fusion technique** demonstrates improved performance and better semantic feature extraction for agricultural texts.

---

## 🧑‍💻 Authors

| Name           | Reg No.       |
| -------------- | ------------- |
| Padilam Tharun | 22Q95A7205    |
| Team Members   | As per report |

---

