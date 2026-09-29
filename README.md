🧠 NeuroVital V4 — Attractive GUI Wellness Tracker

NeuroVital V4 is a Python-based educational wellness tracking application with a graphical user interface (GUI). It allows users to record selected lifestyle and wellness information, view wellness-related results, maintain records, and explore a simple machine-learning demonstration.

«⚠️ Disclaimer: NeuroVital is an educational wellness tracker and is not a medical diagnosis, clinical prediction, or professional medical advice system.»

---

✨ What's New in V4?

Version 4 focuses on improving the overall user experience with a more attractive and organized graphical interface.

Main Features

- 🖥️ Graphical User Interface
  
  - Built using Python Tkinter
  - Organized screens and interactive controls
  - User-friendly navigation

- 🔐 User Accounts
  
  - Account creation and login system
  - Password hashing using SHA-256
  - Local user data storage

- 📋 Wellness Tracking
  
  - Records selected lifestyle and wellness inputs
  - Stores user records locally
  - Allows users to review their previous entries

- 💧 Lifestyle Tracking
  
  - Water intake/goal
  - Sleep information
  - Mood
  - Medication-related input
  - Symptoms
  - Heart rate
  - BMI

- 📊 Wellness Score
  
  - Generates a wellness-oriented score from the entered information
  - Provides general wellness-related feedback

- 📈 Charts & Visualization
  
  - Uses Matplotlib for graphical visualization
  - Allows wellness information to be viewed through charts

- 🤖 Machine Learning Demonstration
  
  - Uses "DecisionTreeClassifier" from scikit-learn
  - Includes a synthetic dataset for educational ML experimentation
  - Uses training/testing data
  - Calculates metrics such as:
    - Accuracy
    - Precision
    - Recall
    - Confusion matrix

- 📝 Report Generation
  
  - Generates a wellness report from the recorded information

---

🛠️ Technologies Used

Technology| Purpose
Python| Main programming language
Tkinter| Graphical user interface
Matplotlib| Charts and visualization
NumPy| Numerical operations
Scikit-learn| Machine-learning demonstration
JSON| Local data storage
hashlib| Password hashing

---

📂 Project Structure

Neurovital-v4/
│
├── NeuroVital_V4_Attractive_GUI.py
└── README.md

The main application is contained in:

NeuroVital_V4_Attractive_GUI.py

---

🚀 How to Run

1. Install Python

Make sure Python 3 is installed on your computer.

2. Install the required libraries

pip install matplotlib numpy scikit-learn

Tkinter is normally included with standard Python installations, although availability can depend on the operating system.

3. Run NeuroVital V4

python NeuroVital_V4_Attractive_GUI.py

The NeuroVital graphical interface should open.

---

🔬 Machine Learning Component

NeuroVital V4 contains an educational machine-learning demonstration using a Decision Tree classifier.

The project creates synthetic wellness-related data and demonstrates a basic ML workflow:

Synthetic Data
      ↓
Train / Test Split
      ↓
Decision Tree Classifier
      ↓
Prediction
      ↓
Evaluation
      ↓
Accuracy / Precision / Recall / Confusion Matrix

The machine-learning component is intended for learning and demonstration purposes and should not be interpreted as a medically validated prediction model.

---

🔒 Data & Privacy

NeuroVital uses local JSON-based storage for application data.

The project is designed as a local educational application. Users should still avoid entering highly sensitive personal or medical information into experimental software.

---

⚠️ Important Disclaimer

NeuroVital V4 is a student/educational software project.

It:

- ❌ Does not diagnose diseases
- ❌ Does not replace a doctor or healthcare professional
- ❌ Does not provide clinical diagnosis
- ❌ Is not a medically validated prediction system
- ❌ Should not be used to make medical decisions

The wellness results and machine-learning component are intended for educational experimentation and personal wellness tracking only.

---

📌 Version History

V1

Initial concept and implementation.

V2

Python-based modular development.

V3

Introduced a machine-learning demonstration using a Decision Tree classifier and synthetic data.

V4

Introduced a more complete GUI-based wellness tracker with account management, wellness tracking, visualization, reports, and an integrated ML demonstration.

---

👩‍💻 Project

Project: NeuroVital
Version: V4
Language: Python
Type: Educational Wellness Tracker
Repository: GitHub

---

🌱 Future Improvements

Possible future development areas include:

- Improved data visualization
- Better user-interface design
- More modular project structure
- Expanded educational ML experiments
- Improved data management
- Additional wellness-tracking features
- Testing and code optimization

---

⭐ NeuroVital V4

Track. Visualize. Learn.

Built as an educational project to explore Python, GUI development, data handling, visualization, and machine learning.