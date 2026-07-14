# Predicting Student Attrition using Quantum Machine Learning (QML)

An analogy-driven, hands-on implementation of a **Variational Quantum Classifier (VQC)** to predict student dropout risks using **PennyLane**. 

This repository demonstrates how to map real-world classical data (academic performance and attendance drops) into quantum wave states, train a 2-Qubit Quantum Neural Network, and evaluate it using both classical and quantum performance metrics.

---

## 📌 The Core Concept & Real-World Analogies

Instead of treating Quantum Machine Learning (QML) as a dry mathematical formula, this project models the prediction of student dropout risks using three intuitive physical analogies:

### 1. Superposition (The Spinning Coin 🪙)
In classical machine learning, a student's state is binary: either **Safe (0)** or **At Risk (1)**. In our QML model, we use **Angle Embedding** to place the student's data into a **Superposition** state. 
* *Analogy:* It is like spinning a coin on a table—it is simultaneously both heads and tails (0 and 1) until the measurement is taken and the wave function collapses.

### 2. Decoherence (The Muddy Water 🌫️)
In quantum hardware, "decoherence" occurs when environmental noise destroys the delicate quantum state. 
* *Analogy:* We treat academic stress and declining attendance as "environmental noise." High noise causes the student's stable state to decay (decohere), pulling the qubit toward the "Dropout" state.

### 3. Quantum State Fidelity (The In-Tune Guitar 🎸)
To measure how well our quantum waves align with the target states, we compute **Fidelity**.
* *Analogy:* Think of the absolute target boundary as a perfectly tuned guitar string. Fidelity measures how "in-tune" our trained qubit waves are with that perfect target. A fidelity of $100\%$ means perfect overlap.

---

## 📊 Model Performance & Results

Our trained 2-qubit system achieved the following metrics on the evaluation set:

```text
==================================================
             QUANTUM MODEL METRICS                
==================================================
 🎯 Classical Classification Accuracy : 100.00%
 🔮 Average Quantum State Fidelity     : 69.33%
==================================================
