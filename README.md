

### 📧 Cold Email Generator

This project is an AI-powered cold email generator built using Streamlit and LangChain. It integrates with vector databases (ChromaDB) and large language models (via Groq API) to produce personalized, high-quality email content.


### 🚀 Features

* 🔗 **LangChain integration** for building dynamic prompts and LLM pipelines
* 📚 **ChromaDB** for fast semantic search and context retrieval
* ⚡ **Groq API** for fast, low-latency LLM completions
* 🖥️ **Streamlit UI** for an interactive email generation experience
* 🧠 Contextual email generation based on user input or document data


## 🚀 Demo
![img](https://github.com/user-attachments/assets/4917e923-880a-4829-8e4c-82107da94ec6)


### 🧰 Requirements

Install all dependencies with:

```bash
pip install -r requirements.txt
```

Required packages include:

* `langchain`, `langchain-groq`, `chromadb`
* `streamlit` for the web app interface
* `selenium`, `unstructured`, and `pandas` for data extraction and preprocessing
* `python-dotenv` for managing environment variables (e.g., API keys)


### 📝 How to Use

1. Clone the repository and navigate to the project directory.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Add your API keys to a `.env` file:

   ```
   GROQ_API_KEY=your_api_key
   ```
4. Run the app:

   ```bash
   streamlit run email_generator.ipynb
   ```

> *Note: If `streamlit` doesn't support `.ipynb` files in your setup, convert the notebook to `.py` using Jupyter or VS Code.*


### 📂 Project Structure

```
cold-email-generator/
├── email_generator.ipynb       # Streamlit interface to generate emails
├── tutorial_chromadb.ipynb     # Sample use of ChromaDB for retrieval
├── tutorial_groq.ipynb         # Demonstration of Groq API usage
├── requirements.txt            # Dependencies
└── .env                        # API keys and environment settings (not committed)
```


### 📌 Future Enhancements

* Export emails directly to Gmail or Outlook
* Add user authentication and email history
* Enhance prompt templates with more personalization

---

### 🧑‍💻 Author

[Gyan0706](https://github.com/Gyan0706)

