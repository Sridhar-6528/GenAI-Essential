# **Exercise 5 – LangGraph Chatbot with Langfuse Monitoring**

## **Overview**

This exercise demonstrates how to integrate **LLM monitoring and tracing** into a chatbot pipeline using LangGraph and Langfuse.  
The chatbot processes user queries using the Groq LLM model and sends tracing data to Langfuse for monitoring and analysis.

Langfuse records details such as:

* Prompt and response data  
* Execution traces  
* Model latency  
* Token usage

This helps developers debug and evaluate AI systems.

---

# **Objective**

The objectives of this exercise are:

* Understand LLM observability and tracing  
* Integrate Langfuse monitoring with LangGraph  
* Track AI model performance  
* Analyze chatbot execution traces

---

# **Technologies Used**

* Python  
* LangGraph  
* LangChain  
* Groq LLM API  
* Langfuse  
* python-dotenv

---

# **Project Files**

trace.py – Chatbot implementation with Langfuse tracing  
README5.md – Documentation for this exercise

---

# **Installation**

## **1 Create Virtual Environment**

python \-m venv venv

**Activate environment**

**Windows:**

venv\\Scripts\\activate

---

## **2 Install Dependencies**

pip install \-r requirements.txt

---

## **3 Configure Environment Variables**

Create a .env file and add:

GROQ\_API\_KEY=your\_api\_key  
GROQ\_MODEL\_NAME=llama-3.3-70b-versatile

LANGFUSE\_PUBLIC\_KEY=your\_public\_key  
LANGFUSE\_SECRET\_KEY=your\_secret\_key  
LANGFUSE\_HOST=[https://cloud.langfuse.com](https://cloud.langfuse.com/)

---

# **Running the Application**

Run the chatbot:

python trace.py

Example interaction:

You: Hello  
Groq Bot: Hello\! How can I help you today?

---

**Workflow**

User Input  
↓  
LangGraph Pipeline  
↓  
Groq LLM Response  
↓  
Langfuse Trace Recording  
↓  
Dashboard Visualization

Langfuse collects the execution traces and displays them in the monitoring dashboard.

---

**Output Screenshots(EX5SCREENSHOT.pdf)**

**Conclusion**  
This exercise demonstrates how Langfuse can be integrated with LangGraph pipelines to monitor chatbot interactions and performance.  
Using observability tools helps developers debug AI systems and optimize model performance.  
