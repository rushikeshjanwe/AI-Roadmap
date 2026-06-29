# 🗺️ AI Roadmap: No-Code ML for Developers

An actionable roadmap to mastering LLMs, Prompt Engineering, and RAG without dealing with complex Machine Learning frameworks like TensorFlow or PyTorch.

---

## 🧠 1. LLM Basics
* **What is an LLM?** – Understanding Large Language Models at a high level.
* **Tokens** – How models read text and calculate costs.
* **Context Window** – The memory limits of an LLM.

---

## 🔌 2. LLM APIs
* **OpenAI API** – Integrating GPT models.
* **Gemini API** – Leveraging Google's multimodal models.
* **Claude API** – Utilizing Anthropic's reasoning models.

---

## ✍️ 3. Prompt Engineering
* **System Prompt** – Setting the persona, rules, and behavioral boundaries.
* **User Prompt** – Crafting clear instructions and context for tasks.
* **Key Parameters:**
  * **Temperature** – Controlling creativity vs. deterministic responses.
  * **Max Tokens** – Limiting the length of the model's output.

---

## 📚 4. RAG (Retrieval-Augmented Generation)
* **Why RAG?** – Overcoming hallucinations and giving LLMs access to private or up-to-date data.
* **Document Chunking** – Breaking down large files into digestible pieces.
* **Embeddings (High Level)** – Turning text into mathematical vectors that capture meaning.
* **Vector Database (High Level)** – Storing and searching across text embeddings efficiently.
* **The Workflow:**
  1. **Retrieval** – Fetching the most relevant chunks based on a user query.
  2. **Generation** – Passing those chunks to the LLM to get an accurate, context-backed answer.

---

## 🛠️ 5. Build One Project
Choose one of the following hands-on projects to tie everything together using your favorite backend stack (like Spring Boot):

* **🤖 Spring Boot AI Chatbot** – A conversational interface with chat memory.
* **📄 AI Resume Analyzer** – A tool that parses resumes and maps them against job descriptions.
* **📂 PDF Q&A Assistant** – A full RAG pipeline allowing users to upload documents and ask questions.

---

> ⚠️ **Note:** Absolutely no deep learning background required. No ML, no TensorFlow, no PyTorch—just pure API integration and software engineering.
