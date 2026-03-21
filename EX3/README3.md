# **Exercise 3– Basic LangGraph Chatbot**

## **Overview**

This exercise demonstrates how to build a simple chatbot using **LangGraph** and **Groq Large Language Models (LLMs)**.The chatbot takes user input from the terminal and generates responses using the Groq LLM.

The purpose of this exercise is to understand how a basic **LangGraph workflow pipeline** works for conversational AI.

---

## **Objective**

The objectives of this exercise are:

* Understand the basics of LangGraph pipelines  
* Integrate a Groq LLM with Python  
* Create a simple chatbot that accepts user input from the terminal  
* Learn how conversation messages are stored and processed

---

## **Technologies Used**

* Python  
* LangGraph  
* LangChain  
* Groq LLM API  
* python-dotenv

---

## **Project Files**

[chatbot.py](http://chatbot.py)  
[README.md](http://README.md)  
chatbot.py-Contains the LangGraph chatbot implementation.

## **Installation**

#### **1\. Clone the Repository**

git clone https://github.com/yourusername/langgraph-course-tasks.git  
cd  langgraph\_project

---

#### **2\. Create Virtual Environment**

python \-m venv venv

**Activate the environment:**

Windows

venv\\Scripts\\activate  
---

### **3\. Install Dependencies**

pip install \-r requirements.txt  
---

### **4\. Configure Environment Variables**

Create a .env file and add your Groq API key:

GROQ\_API\_KEY=your\_api\_key  
GROQ\_MODEL\_NAME=llama-3.3-70b-versatile  
---

## **Running the Chatbot**

Run the program using:

python chatbot.py

# 

# 

# **Screenshot:**

EX3SCREENSHOT.pdf

**Workflow**

The LangGraph pipeline for this exercise follows a simple flow:

User Input

    ↓

LangGraph State

    ↓

Groq LLM Processing

    ↓

AI Response

    ↓

Output in Terminal

**Conclusion**

This exercise demonstrates the basic usage of **LangGraph with Groq LLM** to build a simple chatbot.  
It helps understand how conversational pipelines are structured and how AI responses are generated using modern LLM frameworks.

