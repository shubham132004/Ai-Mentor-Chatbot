# Ai-Mentor-Chatbot


https://github.com/user-attachments/assets/90fc9060-df07-4125-9acf-ae644ac39e47


# 🤖 AI Mentor – Agentic AI Telegram Assistant

The **AI Mentor** is an automated 24/7 Agentic AI system built using **n8n**, **Google Gemini Chat Model**, **Simple Memory**, and **Telegram Bot API**.  
It helps students learn Python, EDA, Machine Learning, and Deep Learning by providing instant, step-by-step explanations for their technical doubts.

---

## 🚀 Project Overview

This bot acts as a **virtual AI mentor** for students.  
Using n8n’s Agentic AI capabilities, it receives messages from Telegram, processes them using Gemini, remembers previous context using Simple Memory, and sends intelligent replies back to users.

---

## 🏗️ Workflow Architecture

<img width="288" height="245" alt="image" src="https://github.com/user-attachments/assets/710a132d-2d61-435e-a403-ebd2ed4422ed" />


### **1. Telegram Trigger**
Receives incoming messages from students on Telegram.

### **2. AI Agent**
Connected with:
- **Google Gemini Chat Model (Chat Model input)**
- **Simple Memory (Memory input)**

This node contains the main system prompt that guides the AI Mentor.

### **3. Telegram Send Message**
Delivers the final AI-generated response back to the student.

---

## 🧠 AI Mentor Prompt Logic (Step-by-Step)

The Agent follows these rules:

1. **Greet students** when they say “hi”, “hello”, or similar greetings.  
2. **Ask the student to choose a topic** (Python, EDA, Machine Learning, Deep Learning).  
3. **Store the selected topic** using Simple Memory for the current conversation.  
4. **Ask for the student’s technical doubt** related to that topic.  
5. **Send the doubt to the Google Gemini LLM** for explanation.  
6. **Reply with a clear, step-by-step explanation** in an easy-to-understand format.  
7. **Work continuously 24/7** to support students anytime.

---

## 📁 Workflow JSON File

You can find the exported n8n workflow JSON here: https://github.com/shubham132004/Ai-Mentor-Chatbot/tree/main/JSON%20FILE


---

## ✨ Features

- Smart greeting system  
- Topic selection and context memory  
- AI-powered doubt-solving using Gemini  
- Continuous learning support  
- Fully automated Telegram chat assistant  
- Context-aware responses  

---

## 🛠️ Tech Stack

- **n8n** (Agentic AI Workflows)  
- **Google Gemini Chat Model**  
- **Simple Memory**  
- **Telegram Bot API**  
- **Node.js**

---

## 📌 Use Cases

- Student learning support  
- Automated doubt-solving assistant  
- AI-powered education systems  
- Telegram-based study assistant  

---




