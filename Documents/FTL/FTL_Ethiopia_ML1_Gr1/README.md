# AI-Driven Hybrid Cyber Defensive System for Intelligent Malware Detection and Threat Insight

## 📌 Overview

This project focuses on building a hybrid AI-based system to detect malware and provide threat insights. It leverages deep learning models (CNN and LSTM), feature-based classification, and multithreading for efficient detection. The tool aims to bolster cyber defenses by identifying threats at various abstraction levels.

---

## 🧠 Features

- CNN and LSTM-based malware detection models
- Feature-based classical ML classifier
- Multithreaded processing for performance
- Custom GUI/icon support
- Jupyter Notebook for training and analysis
- Modular and extensible codebase

---

## 🗂️ Project Structure

```bash
Project/
│
├── dataset/ # Malware and benign sample data
├── doc/ # Documentation report
├── model/ # Pretrained models (CNN, LSTM, etc.)
├── notebook/ # Jupyter notebook for training
├── src/ # Source code (scripts and icons)
│ ├── Malware_detection_tool.py
│ ├── multithreading.py
│ └── *.ico # Custom icons for UI
│
├── .gitignore
├── README.md
├── requirements.txt
```

## ▶️ Run the Tool
```bash
cd src
python Malware_detection_tool.py
```

## 📓 Model Training
To retrain the model or analyze data:

```bash
cd notebook
jupyter notebook Training_Model.ipynb
```

## 📚 Dependencies
See requirements.txt for all Python packages.
