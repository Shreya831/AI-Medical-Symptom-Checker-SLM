# AI Medical Symptom Checker using Small Language Models (DistilBERT)

This project builds an **AI-powered medical symptom checker** using a **Small Language Model (DistilBERT)** to predict possible diseases from user-reported symptoms.

The system analyzes symptoms using **Natural Language Processing (NLP)** and predicts the **top possible diseases with probability scores**.

An interactive **web application built with Gradio** allows users to enter symptoms and visualize predictions.

---

## Project Overview

Healthcare systems often require fast initial analysis of symptoms.
This project demonstrates how **transformer-based language models** can assist in symptom analysis.

The model takes symptoms as input and predicts **likely diseases along with confidence scores**.

---

## Key Features

* Symptom-based disease prediction
* Transformer-based NLP model (DistilBERT)
* Top 3 predicted diseases with probabilities
* Prediction confidence visualization
* Interactive web application using Gradio
* Simple and beginner-friendly implementation

---

## Example Input

fever headache body pain fatigue

---

## Example Output

1. Flu — 0.82
2. Dengue — 0.11
3. Common Cold — 0.06

A confidence chart is also generated to visualize prediction probabilities.

---

## Tech Stack

Python
HuggingFace Transformers
PyTorch
Scikit-learn
Gradio
Matplotlib

---

## Project Structure

AI-Medical-Symptom-Checker-SLM

│
├── Medical_Symptom_Disease_Predictor_SLM.ipynb
├── app.py
├── requirements.txt
└── README.md

---

## Applications

Healthcare AI
Clinical decision support systems
Medical NLP research
AI-assisted symptom analysis

---

## Disclaimer

This project is **for educational purposes only** and is **not intended for medical diagnosis or treatment**.

---

## Future Improvements

* Train the model on a larger medical dataset
* Add more symptoms and diseases
* Deploy the application as a full web service
* Integrate medical knowledge retrieval (RAG)

---

## Author

AI/ML project exploring applications of **Small Language Models in healthcare AI**.
