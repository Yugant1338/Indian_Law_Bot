# ⚖️ Indian Law Chatbot using Generative AI

This project is an intelligent chatbot designed to answer Indian legal questions related to IPC (Indian Penal Code) and statutory law using **Generative AI** (FLAN-T5) combined with **semantic search**. It enables users to interact naturally with legal data and get relevant responses in real-time.

---

## 🚀 Features

- ✅ **Semantic Context Retrieval** using Sentence Transformers (`all-MiniLM-L6-v2`)
- ✅ **Generative Question Answering** with `FLAN-T5`
- ✅ Trained on Indian law sections and IPC offenses (from Kaggle datasets)
- ✅ Interactive **Gradio-based chatbot UI**
- ✅ Runs fully on **Google Colab**

---

## 📂 Datasets Used

- 📘 [Indian Laws Dataset](https://www.kaggle.com/datasets/anishparkhe0401/indian-laws)  
- ⚖️ [IPC FIR Dataset](https://www.kaggle.com/datasets/omdabral/indian-penal-code-complete-dataset)

These datasets contain text descriptions of Indian law sections and IPC offenses, which are used for context during answer generation.

---

## 🧠 Model Architecture

- **Retriever**: Sentence-BERT (`all-MiniLM-L6-v2`)
- **Generator**: `google/flan-t5-base`
- **Pipeline**: Question → Semantic Context → Prompt → Generated Answer

---

## 🧪 Sample Questions

Try these to test the chatbot:

- What does Section 420 of IPC mean?
- Is theft a bailable offense?
- What is the short title of the Motor Vehicles Act?
- What is house trespass under IPC?
- What is the punishment for forgery?

---

## 🖥️ How to Run

### 🔗 [Open in Google Colab](https://colab.research.google.com/drive/1UEX4JMW6O8kriDmJWAutNvTSHTLnoGqb?usp=drive_link)


---

---

## 📈 Future Improvements

- 🔁 Fine-tune FLAN-T5 on Indian legal Q&A dataset
- 🌐 Add multilingual support (Hindi, Bengali, etc.)
- 📄 Accept PDF input for FIRs or legal documents
- 🧠 Improve relevance with FAISS-based vector search

---

## 👨‍⚖️ License

This project is for academic and educational purposes only. Legal accuracy is not guaranteed.

---

## 🙌 Credits

- Hugging Face Transformers & Datasets
- Sentence Transformers by UKPLab
- Kaggle contributors for the datasets


