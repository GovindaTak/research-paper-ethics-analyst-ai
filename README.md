# research-paper-ethics-analyst-ai
An AI-powered LangChain-based application that transforms and summarizes research paper abstracts for different target audiences such as general readers, healthcare companies, and AI startups. It leverages GPT-4o-mini and conversational prompting techniques using ChatPromptTemplate from LangChain.

```markdown
# 🧠 Research Paper Ethics Analyst using GPT-4o-mini & LangChain

A hands-on LangChain-based project designed to **analyze and transform AI research paper abstracts** based on the needs of different target audiences. This tool makes AI content accessible for the general public, structured for corporate decision-makers, and detailed for AI development teams.

---

## 📌 Objective

Transform the abstract of a generative AI ethics research paper into:
- A concise, simple summary for **general users**.
- A detailed ethical analysis for **healthcare companies**.
- A deep dive with key data-modality points for **Generative AI startups**.

---

## 🚀 Features

✅ Use of **LangChain ChatPromptTemplate** for dynamic message chaining  
✅ **Three distinct audiences** targeted via unique prompt templates  
✅ Uses **GPT-4o-mini** for cost-efficient and fast inference  
✅ Full pipeline: PDF to prompt, LLM to output  
✅ Output includes: summary, pros/cons of ethical impact, and domain-specific insight

---

## 🧪 Technologies Used

- 🐍 Python
- 🔗 LangChain (Core, Community, OpenAI modules)
- 🤖 GPT-4o-mini (OpenAI API)
- 📄 PDF Source Abstract
- 💬 ChatPromptTemplate
- ✅ `map()` and `invoke()` chaining


## 💡 Skills Gained

Through this project, I gained hands-on expertise in:

- ✅ **LangChain Prompt Engineering**: Used ChatPromptTemplate and chaining with system + human messages
- ✅ **Conversational AI Structure**: Built a multi-output chat system tailored to target personas
- ✅ **Ethical AI Understanding**: Learned how ethical concerns vary across domains (text/image/structured)
- ✅ **LLM Evaluation**: Compared GPT-4o-mini's responses across user contexts
- ✅ **Domain Adaptation**: Designed AI responses for general vs. technical users
- ✅ **Chain Composition**: Used `.map()` and `.invoke()` for concurrent multi-prompt executions

---

## 🛠 Installation

```bash
git clone https://github.com/GovindaTak/research-paper-ethics-analyst-ai.git
cd research-paper-ethics-analyst-ai
````

Add your OpenAI API key:

```python
import os
os.environ["OPENAI_API_KEY"] = "your-key-here"
```

---

## 📈 Sample Outputs

| 🎯 Audience        | 🧾 Output Type                     |
| ------------------ | ---------------------------------- |
| General Public     | 10-line readable summary           |
| Healthcare Company | Ethical Pros & Cons report         |
| AI Company         | Detailed analysis by data modality |

---

## 🧑‍💻 Author

**Govinda Tak**
AI/GenAI Developer | LLM Prompt Engineer
📧 [govindatak19@gmail.com](mailto:govindatak19@gmail.com)
🔗 [GitHub](https://github.com/Govinda-Tak)

---

## 📜 License

This project is licensed under the MIT License.

---
