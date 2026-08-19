
# QuantumSentinel 

**QuantumSentinel** is a Quantum Machine Learning (QML) framework designed for intrusion detection in Internet of Things (IoT) network traffic. Built as part of the **QIntern** project by **QWorld**, this project evaluates quantum baseline models against classical approaches for cybersecurity anomaly detection on the **Bot-IoT** and **CICIoT** datasets.

---

## Project Overview

IoT networks are increasingly vulnerable to distributed cyberattacks, requiring fast and high-precision detection models. QuantumSentinel explores quantum-enhanced paradigms—including Quantum Support Vector Machines (QSVM) and Variational Quantum Classifiers (VQC)—to assess whether quantum feature spaces offer higher sensitivity and accuracy compared to classical machine learning baselines.

---

## Project Structure

```text
QuantumSentinel/
├── classical_baseline/        # Baseline classical models (Random Forest, SVM, XGBoost)
├── data/
│   └── FROZEN/
│       └── BOT-IOT/           # Frozen subsets and preprocessed Bot-IoT data
├── scripts/                   # Data preprocessing and utility scripts
├── team-artifacts/            # Benchmarks, figures, presentation slides, and notes
├── cicio-training-v01 (1).ipynb # Training notebook for CICIoT dataset
├── the-final-bot-iot.ipynb    # Final quantum training pipeline for Bot-IoT dataset
├── the-final-ciciot.ipynb     # Final quantum training pipeline for CICIoT dataset
├── LICENSE                    # MIT License
└── README.md                  # Project documentation

```

---

## 📊 Datasets

1. **Bot-IoT Dataset**: Contains synthetic and real-world network traffic representing various attack types (DDoS, DoS, Reconnaissance, Keylogging).
2. **CICIoT Dataset**: Benchmarking dataset specifically targeting IoT ecosystem security attacks.

---

##  Key Features & Workflow

* **Data Preprocessing & Reduction**: Normalization, dimensionality reduction (PCA/Autoencoders) to fit qubit constraints.
* **Classical Baselines**: Benchmarks established using classical models in `classical_baseline/`.
* **Quantum Classifier Implementation**: Feature map encoding (e.g., Angle Encoding, ZZFeatureMap) and variational ansatz circuit design using Qiskit / PennyLane.
* **Evaluation Metrics**: Comparison based on Accuracy, Precision, Recall, F1-Score, and execution time.

---

## 🛠️ Installation & Setup

1. **Clone the Repository**
```bash
git clone [https://github.com/Arjun-E-Naik/QuantumSentinel.git](https://github.com/Arjun-E-Naik/QuantumSentinel.git)
cd QuantumSentinel

```


2. **Create a Virtual Environment & Install Dependencies**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install qiskit qiskit-machine-learning pennylane scikit-learn pandas numpy matplotlib seaborn jupyter

```


3. **Run Jupyter Notebooks**
```bash
jupyter notebook

```


Open `the-final-bot-iot.ipynb` or `the-final-ciciot.ipynb` to explore the training pipelines.

---

##  Acknowledgments & Mentions

* **Organization**: [QWorld](https://qworld.net/)
* **Program**: QIntern Project
* **Author**: [Arjun E Naik](https://github.com/Arjun-E-Naik)

---
```

```
