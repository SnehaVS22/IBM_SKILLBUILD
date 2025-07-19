# IBM_SKILLBUILD

# 🤖 Smart Medical Triage Assistant using Gemini + LangGraph

This project demonstrates a **smart medical triage system** that classifies a patient's symptoms into one of the following categories:

- 🏥 General
- 🚨 Emergency
- 🧠 Mental Health

It uses **Gemini 1.5 Flash**, **LangGraph**, and **LangChain** to build an intelligent and interactive conversational flow.

---

## 📌 Features

- Accepts patient symptoms as input via terminal/CLI.
- Uses Google's **Gemini 1.5 Flash** model to classify the symptom.
- Routes the patient to the correct department based on classification.
- Modular LangGraph structure with nodes for each task.
- Easy to extend and customize.

---

## 🛠️ Tech Stack

- [Google Gemini 1.5 Flash](https://ai.google.dev/)
- [LangGraph](https://github.com/langchain-ai/langgraph)
- [LangChain](https://www.langchain.com/)
- Google Colab / Python 3.10+

---

## 🧪 How it Works

1. **User Input**: Prompt the patient to enter their symptom.
2. **LLM Classification**: Gemini categorizes it into `General`, `Emergency`, or `Mental Health`.
3. **Routing**: Based on the category, the LangGraph routes the state to the appropriate handler node.
4. **Response**: A tailored message is printed to the patient based on the classified category.

---


