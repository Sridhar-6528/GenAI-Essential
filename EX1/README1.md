# **Exercise 1– Groq LLM Basic Response Generation**

##  **Overview**

This exercise demonstrates how to use a **Groq Large Language Model (LLM)** with an OpenAI-compatible Python client to generate responses.

The program sends a prompt to the model and prints the generated output in the terminal.  
This helps in understanding how fast LLM APIs work and how they can be integrated into Python applications.

---

## **Objective**

The objectives of this exercise are:

* To understand how to connect to the **Groq API**

* To learn how to use an **OpenAI-compatible client**

* To generate responses using a Large Language Model

* To securely manage API keys using environment variables

---

## **Technologies Used**

* Python

* OpenAI Python SDK

* Groq LLM API

* python-dotenv

---

## **Project Files**

.  
├── main.py  
├── .env  
└── README.md

* **app.py** – Contains the code to call Groq LLM and generate response

* **.env** – Stores API key securely

* **README.md** – Documentation

---

## **Installation**

### **1\. Create Virtual Environment**

python \-m venv venv

#### **Activate the environment:**

**Windows:**

venv\\Scripts\\activate  
---

### **2\. Install Dependencies**

pip install openai python-dotenv  
---

### **3\. Configure Environment Variables**

Create a `.env` file and add:

GROQ\_API\_KEY=your\_api\_key\_here  
---

## **Running the Program**

python app.py

## **Workflow**

User Prompt  
   ↓  
Groq API Request  
   ↓  
LLM Processing  
   ↓  
Generated Response  
   ↓  
Output in Terminal

## **Screenshot:(EX1SCREENSHOT.pdf)** 

## **Conclusion**

This exercise demonstrates how to use a **Groq LLM with Python** to generate responses.

It helps in understanding:

* API integration

* Fast inference using LLMs

* Secure key management

