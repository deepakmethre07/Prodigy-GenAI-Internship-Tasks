# Task-03: Text Generation with Markov Chains

## 📌 Overview
This project implements a simple **text generation algorithm using Markov Chains**.  
The model learns word-to-word transition probabilities from a given text and generates new text based on those probabilities.

This task demonstrates basic concepts of **Natural Language Processing (NLP)** and **probabilistic modeling** without using deep learning.

---

## 🧠 What is a Markov Chain?
A Markov Chain is a statistical model that predicts the **next state based only on the current state**.

In this project:
- Each **word** is a state
- The **next word** is predicted based on the previous word
- Text is generated one word at a time

---

## ⚙️ How It Works
1. Input text is split into words
2. A dictionary is created mapping:
