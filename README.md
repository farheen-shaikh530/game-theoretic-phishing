# 🎯 Game-Theoretic Phishing Defense System

[![Status](https://img.shields.io/badge/status-active-brightgreen)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)]()
[![Python](https://img.shields.io/badge/python-3.9+-yellow.svg)]()

This research models phishing as a **repeated two-player zero-sum game** between an adaptive defender and a Q-learning attacker. It leverages **game theory, reinforcement learning, NLP classification**, and **sandboxing** to simulate dynamic cybersecurity strategies and visualize how adaptive defenses mitigate phishing attempts over time.

---

## 🔍 Problem Statement

Phishing attacks evolve continuously, outpacing traditional rule-based detection. This project reframes the phishing problem as a **strategic interaction** where:

- 🎯 The **defender** adaptively updates their detection strategy using response history, NLP, and sandbox results.
- ⚔️ The **attacker** learns through **Q-learning** to avoid detection and maximize phishing success.

---

## 🧠 Methodology

- **Game-Theoretic Framework**: Repeated two-player zero-sum game
- **Attacker**: Q-learning agent with evolving strategy weights
- **Defender**: Adaptive filters + sandbox + NLP classifier (Naive Bayes or LSTM)
- **Payoffs**: Based on phishing success or detection
- **Visualization**: Heatmaps, strategy weights, and payoff trajectories

---

## 📊 Key Features

- 🔁 Simulates multi-round phishing-defense interactions
- 📈 Visualizes evolving attacker strategies using bar graphs and line charts
- 🧠 Incorporates NLP-based email classification (scam vs. legitimate)
- 🧪 Includes a sandbox module to test unknown payloads
- 🛡️ Defender learns from past attacks using adaptive strategy updates

---

## 🖼 Sample Visualizations

> (📌 Include screenshots like heatmaps, payoff graphs, strategy history here)

---

## 🧪 Installation

```bash
git clone https://github.com/farheen-shaikh530/game-theoretic-phishing.git
cd game-theoretic-phishing
pip install -r requirements.txt
python phishing_simulation.py
