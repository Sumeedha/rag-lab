# 🔍 Retrieval Augmented Generation (RAG) Lab using LangChain and IBM Granite

This project contains my implementation and learning from a hands-on **RAG Lab** conducted via **IBM SkillsBuild**, using tools like **LangChain**, **Replicate API**, and **IBM Granite models**.

---

## 📌 What is RAG?

**RAG (Retrieval Augmented Generation)** is an advanced technique in AI where the model:
1. **Retrieves relevant documents** based on a query
2. **Generates an answer** using both its internal knowledge and the retrieved data

This improves **accuracy**, reduces **hallucination**, and makes AI more grounded in real facts.

---

## 🔧 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| 🧠 LangChain | Orchestrates LLM + external document retrieval |
| 🧬 IBM Granite LLM | Language model used for generation |
| 📚 Vector Database | Stores chunks of documents for similarity search |
| 🔗 Replicate API | Provides access to hosted AI models |
| 📁 Google Colab | Notebook-based execution |
| 💻 GitHub | Version control and cloud storage for code |

---

## 🎯 Lab Objectives

✅ Understand the concept of RAG  
✅ Load a large language model via Replicate  
✅ Create and populate a vector database  
✅ Perform similarity-based search  
✅ Use retrieved chunks to generate final answers

---

## 🔄 How the Lab Works (Step-by-Step)

1. **Load the LangChain framework**
2. **Split input text** into small chunks
3. **Create a vector store** to hold those chunks
4. **Take a query**, and search for similar chunks
5. **Refine the prompt** using retrieved chunks
6. **Generate an answer** with the model (IBM Granite)

## 💡 What I Learned

- The complete flow of building a **smart Q&A system**
- Setting up **Replicate API tokens**
- How to connect LLMs to **external documents**
- Gained hands-on with **vector stores**, **prompt templates**, and **Colab execution**



## ✅ How to Run

> Note: To run this notebook, you’ll need a valid **Replicate API Token** and GitHub authorization inside Colab.

1. Open the notebook in **Google Colab**
2. Install dependencies
3. Paste your API token
4. Run all cells sequentially

---

## 📬 Contact

Feel free to open an issue or connect with me on [linkedin.com/in/sumeedha-bibi) if you'd like to collaborate or learn together!
