
# LangChain Language Translator using Groq +  🚀

This is a simple Language Translator app built using:

- 🗣️ **Groq API** — For fast inference using `Gemma2-9b-It` model
- ⚙️ **LangServe** — To expose chains via HTTP endpoints

## 🔧 Features

- Translate user input into any target language using Groq LLM.
- Clean chain structure using LangChain's `ChatPromptTemplate`, `StrOutputParser`.


## 📦 How to Run

```bash
pip install -r requirements.txt
python serve.py
```
.

## 🔑 Environment Variables

Ensure you have a `.env` file with:
```env
GROQ_API_KEY=your_groq_api_key_here
```

---

💡 **Author**: Shiba Sankar Sahu  
🔗 GitHub: [imshibasankarsahu](https://github.com/imshibasankarsahu)
