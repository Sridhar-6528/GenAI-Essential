# **Exercise2 – LangChain Agent with Groq LLM**

## **Overview**

## This exercise demonstrates how to build a simple **AI agent using LangChain and Groq LLM**. The agent is capable of using a custom tool to perform specific tasks—in this case, calculating the length of a word.

The system combines:

* A **Groq-powered LLM**

* A **custom tool**

* A **LangChain agent pipeline**

to process user queries intelligently.

---

## **Objective**

The objectives of this exercise are:

* To understand how **LangChain agents** work

* To integrate **Groq LLM** with LangChain

* To create and use **custom tools**

* To enable the agent to decide when to use tools

* To process and respond to user queries

---

## **Technologies Used**

* Python

* LangChain

* LangChain Groq Integration

* Groq LLM API

* python-dotenv

---

## **Project Files**

.  
├── agent.py  
├── .env  
└── README.md

* **agent.py** – Contains agent \+ tool implementation

* **.env** – Stores API key and model name

* **README.md** – Documentation

---

 **Installation**

### **1\. Create Virtual Environment**

python \-m venv venv

#### **Activate the environment:**

**Windows:**

venv\\Scripts\\activate  
---

### **2\. Install Dependencies**

pip install langchain langchain-groq python-dotenv  
---

### **3\. Configure Environment Variables**

Create a .env file and add:

GROQ\_API\_KEY=your\_api\_key\_here  
GROQ\_MODEL\_NAME=llama-3.3-70b-versatile  
---

## **Running the Program**

python [agent.py](http://agent.py)

## **Workflow**

User Question  
   ↓  
LangChain Agent  
   ↓  
Tool Selection (if needed)  
   ↓  
Groq LLM Processing  
   ↓  
Final Response  
   ↓  
Output in Terminal

## **Conclusion**

This exercise demonstrates how to build an **intelligent agent using LangChain and Groq LLM**.

It helps in understanding:

* Tool-based AI systems

* Agent decision-making

* Integration of LLM with external functions