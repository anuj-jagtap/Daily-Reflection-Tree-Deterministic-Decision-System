# 🌳 Daily Reflection Tree – Deterministic Reflection System

## 📌 Overview

This project is a **deterministic reflection tool** designed to guide users through a structured end-of-day review.

Instead of using AI at runtime, the system uses a **decision tree** where:
- Users select from fixed options
- The system follows predefined paths
- Reflections are generated deterministically

The goal is to help users build awareness about:
- Their sense of control
- Their contribution mindset
- Their focus (self vs others)

---

## 🎯 Core Idea

This system is built around **three psychological axes**:

### 1. Locus of Control
- Did the user take ownership?
- Or feel controlled by external factors?

### 2. Contribution vs Entitlement
- Did the user focus on giving?
- Or on what they expected?

### 3. Radius of Focus
- Was the focus only on self?
- Or also on others and broader impact?

---

## 🧠 How It Works

1. The user starts the reflection session
2. Answers a series of fixed-choice questions
3. Each answer adds a **signal** (e.g., internal, external)
4. Decision nodes evaluate dominant signals
5. The system shows reflections based on those paths
6. A final summary is generated

👉 Same inputs → Same outputs (fully deterministic)

---

## 📁 Project Structure


---

## 🌳 Decision Tree Design

- 25+ nodes
- 3 axes (Locus → Contribution → Radius)
- Fixed options (no free text)
- Signal-based branching
- Separate reflections for each path

---

## 🔄 Node Types Used

- **start** – Entry point  
- **question** – User selects an option  
- **decision** – Routes based on signals  
- **reflection** – Displays insight  
- **bridge** – Connects axes  
- **summary** – Final reflection  
- **end** – Session closure  

---

## 🚫 No AI at Runtime

This system does **not use LLMs or AI models during execution**.

All intelligence is:
- Predefined
- Structured
- Fully traceable

---

## 💡 Design Philosophy

- Simple and clear questions
- Non-judgmental reflections
- Deterministic behavior
- Structured thinking over randomness

---

## 🔧 Future Improvements

- More personalized summaries
- Additional branching depth
- CLI/Web-based reflection agent

---

## 🙌 Conclusion

This project demonstrates how psychological insights can be converted into a **structured, deterministic system** that guides meaningful reflection without relying on AI generation.

---
