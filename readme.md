# 🚀 Generative AI Applications with AWS Bedrock & LangChain

## 📌 Overview

This project demonstrates how to build Generative AI applications using **Amazon Bedrock** and **LangChain**. It covers real-world use cases such as text generation and summarization using large language models (LLMs).

The implementation is based on AWS Skill Builder lab exercises and showcases how to integrate foundation models into applications using Python and Boto3.

---

## 🧠 Features

* Text generation using Amazon Bedrock (Nova Lite model)
* Automated email response generation based on customer feedback
* Text summarization workflows
* Hands-on integration with LangChain
* End-to-end implementation in Amazon SageMaker Studio

---

## 🛠️ Tech Stack

* **AWS Bedrock**
* **LangChain**
* **Python (Boto3)**
* **Amazon SageMaker Studio**
* Jupyter Notebook

---

## 📂 Project Structure

```
LabRepository/
│
├── en_us/
│   ├── Task1a.ipynb   # Text Generation
│   ├── Task1b.ipynb
│   ├── Task2a.ipynb   # Text Summarization
│   ├── Task2b.ipynb
│   └── ...
│
├── rag_data/          # Data used for RAG tasks
├── letters/           # Sample inputs
```

---

## ⚙️ Setup & Execution

### 1. Clone the repository

```bash
git clone https://github.com/mitalipatel2606-star/aws-genai-bedrock-app.git
cd aws-genai-bedrock-lab
```

### 2. Open in Jupyter Notebook / SageMaker Studio

* Launch JupyterLab or SageMaker Studio
* Open notebooks from the `en_us/` folder

### 3. Run the notebook

* Select kernel: `Python 3 (ipykernel)`
* Run cells sequentially using `Shift + Enter`

---

## 💡 Example Use Case

The project generates automated email responses for customers who provided negative feedback:

* Understand customer sentiment
* Generate polite, human-like responses
* Improve customer experience using AI

---

## 📸 Sample Output

*(Add screenshots here after running the notebook)*

---

## ⚠️ Notes

* AWS credentials and permissions are required to access Amazon Bedrock
* Some responses may be delayed due to API throttling limits
* Ensure correct AWS region (e.g., `us-east-1`)

---

## 🎯 Learning Outcomes

* Understand how LLMs work in real-world applications
* Learn prompt engineering (zero-shot prompting)
* Integrate AWS Bedrock with Python applications
* Build scalable GenAI workflows

---

## 📬 Future Improvements

* Add Retrieval-Augmented Generation (RAG)
* Deploy as an API-based service
* Integrate with frontend UI

---

## 🙌 Acknowledgment

This project is based on AWS Skill Builder lab:
**"Developing Generative AI Applications on AWS"**

---

## ⭐ If you found this useful

Give this repo a star ⭐
