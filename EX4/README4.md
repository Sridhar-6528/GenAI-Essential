# **Exercise 4 – LangGraph Chatbot with Tools**

## **Overview**

This exercise demonstrates how to build a chatbot that can use **external tools** to answer user questions.  
The chatbot is built using LangGraph and a Groq Large Language Model.

Unlike the basic chatbot in Exercise 1, this version can **call tools automatically** when the user asks for tasks such as checking weather or performing calculations.

---

## **Objective**

The objectives of this exercise are:

* Understand how tool calling works in LLM applications  
* Integrate external tools with a chatbot  
* Build an agent workflow using LangGraph  
* Allow the AI model to dynamically select tools when needed

---

## **Tools Implemented**

### **1\. Weather Tool**

This tool returns weather information for a given location.

Example:

User: What is the weather in Chennai?  
Tool Output: The weather in Chennai is currently 72°F and sunny.

---

### **2\. Calculator Tool**

This tool performs a simple addition between two numbers.

Example:

User: Add 5 and 7  
Tool Output: 12

---

## **Technologies Used**

* Python  
* LangGraph  
* LangChain  
* Groq LLM API  
* python-dotenv

---

## **Project Files**

**tools.py** – Main chatbot implementation with tool integration  
**README4.md** – Documentation for this exercise

---

## **Installation**

### **1\. Create Virtual Environment**

python \-m venv venv

**Activate the environment:**

**Windows:**

venv\\Scripts\\activate

---

### **2\. Install Dependencies**

pip install \-r requirements.txt

---

### **3\. Configure Environment Variables**

Create a .env file and add:

GROQ\_API\_KEY=your\_api\_key  
GROQ\_MODEL\_NAME=llama-3.3-70b-versatile

---

## **Running the Application**

Run the chatbot using:

python tools.py

---

## **Example Interaction**

You: What is the weather in Delhi?

Agent is calling tool 'get\_weather'

Tool returned: The weather in Delhi is currently 72°F and sunny.

Groq Bot: The weather in Delhi is currently 72°F and sunny.

---

You: Add 8 and 12

Agent is calling tool 'calculate\_sum'

Tool returned: 20

Groq Bot: The sum of 8 and 12 is 20\.

---

## 

## 

## 

## **Screenshot: (EX4SCREENSHOT.pdf)**

## **Workflow**

User Input  
↓  
Chatbot Node  
↓  
Check if Tool is Needed  
↓  
Execute Tool  
↓  
Return Result  
↓  
AI Response

---

## 

## **Conclusion**

This exercise demonstrates how a chatbot can interact with external tools to perform specific tasks such as calculations and information retrieval.  
Tool integration is an important concept for building intelligent AI agents.

