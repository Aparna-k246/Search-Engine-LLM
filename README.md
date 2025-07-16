# 🔍 Search Engine with LLM

This project is a Search Engine powered by a Large Language Model (LLM), providing intelligent search results and context-aware answers using advanced natural language understanding. Built using `Streamlit`, this app allows users to ask questions and receive relevant responses from the indexed knowledge base.

---

## 📌 Features

- 🔎 LLM-powered semantic search
- 📂 Custom data indexing and retrieval
- 🧠 Context-aware responses
- 💡 Clean and responsive Streamlit UI
- 🚀 Automatic deployment to Hugging Face Spaces via GitHub Actions

---

## 📁 Project Structure

```
Search-Engine-LLM/
├── .github/
│   └── workflows/
│       └── main.yaml          # GitHub Actions workflow to sync to Hugging Face
├── app.py                     # Main Streamlit app
├── requirements.txt           # Python dependencies
├── LICENSE
└── README.md
```

---

## 🚀 Setup & Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Aparna-k246/Search-Engine-LLM.git
cd Search-Engine-LLM
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the app

```bash
streamlit run app.py
```

---

## ☁️ Hugging Face Spaces Deployment (CI/CD)

This project includes a GitHub Actions workflow to auto-sync the latest changes to Hugging Face Spaces.

### 🔐 Steps to Enable:

1. Generate a [Hugging Face token](https://huggingface.co/settings/tokens) with write access.
2. Add it to your GitHub repository’s **Secrets** as `HF_TOKEN`.
3. Push to `main` — GitHub Actions will handle the rest.


## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

**Aparna K**  
🔗 [GitHub](https://github.com/Aparna-k246) • [LinkedIn](https://www.linkedin.com/in/aparna-k-628005167/)
