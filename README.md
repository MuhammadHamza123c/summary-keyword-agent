# 📑 Summary & Keyword Agent  

An AI-powered project built with **LangChain** and **Gemini 2.5 Flash**, featuring two specialized agents:  
- **Summary Agent** → Generates concise summaries of any text input.  
- **Keyword Agent** → Extracts key terms and phrases for quick insights.  

---

## 🚀 Features  
- Text summarization using LLMs  
- Keyword extraction (one-shot prompting)  
- Easy-to-use Jupyter Notebook workflow  
- Secure handling of API keys via `.env`  

---

## 📂 Repository Structure  

```

summary-keyword-agent/
│-- .gitignore
│-- main.ipynb
│-- requirements.txt

```


---

## ⚙️ Installation  

Clone the repo and install dependencies:  
```bash
git clone https://github.com/MuhammadHamza123c/summary-keyword-agent.git
cd summary-keyword-agent
pip install -r requirements.txt

```

## **Environment Setup**

Create a .env file in the root directory and add your API key:

```

GEMINI_API_KEY=your_api_key_here

```
## **Usage**

Run the Jupyter Notebook:

```
jupyter notebook main.ipynb

```
### **Summary Agent → Pass a text and get its summary.**

### **Keyword Agent → Pass a text and get extracted keywords.**

## **License**

This project is licensed under the MIT License.

## **✨ Made with love by Hamza ✨**
