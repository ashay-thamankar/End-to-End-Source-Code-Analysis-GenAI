# End-to-End Source Code Analysis Chatbot 🔍💻

A powerful **source code analysis chatbot** that reads entire repositories, extracts knowledge, and performs various operations to return insightful results. 🎯 Powered by **Chromadb**, **OpenAI LLM**, and a user-friendly **Flask UI**, this tool simplifies code analysis! 🚀

---

## Features 🚀  

### 🌐 Backend:  
- 📂 Reads and processes the entire GitHub repository source code.  
- 🧠 Generates vector embeddings with **OpenAI models**.  
- 📊 Builds a **knowledge base** using **Chromadb Vector DB** for efficient semantic search.  

### 💻 Frontend:  
- 🎨 Interactive **Flask UI** for providing the GitHub URL.  
- 🔍 Retrieves ranked results from the knowledge base.  
- 🧾 Provides **contextual and insightful analysis** powered by **OpenAI GPT**.  

---

## Architecture 📐
![Architecture](https://github.com/ashay-thamankar/End-to-End-Source-Code-Analysis-GenAI/blob/main/media/architecture.png)

## Chatbot in Action! 🎉  
![Source Code Analysis Chatbot Screenshot](https://github.com/ashay-thamankar/End-to-End-Source-Code-Analysis-GenAI/blob/main/media/Source%20Code%20Analysis%20Chatbot.png)

---

## How to Run? 🛠️  

### Steps  

1. **Clone the Repository** 🗂️  
   ```bash
   git clone https://github.com/ashay-thamankar/End-to-End-Source-Code-Analysis-GenAI.git
   cd End-to-End-Source-Code-Analysis-GenAI
   ```

2. **Create a Conda Environment** 🐍  
   ```bash
   conda create -n llmapp python=3.10 -y
   conda activate llmapp
   ```

3. **Install the Requirements** 📦  
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Environment Variables** 🔑  
   Create a `.env` file in the root directory with your OpenAI credentials:  
   ```ini
   OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
   ```

5. **Start the Application** 🖥️  
   ```bash
   python app.py
   ```

6. **Access the Application** 🌐  
   Open your browser and visit:  
   ```plaintext
   http://localhost:5000
   ```

---

## Tech Stack 🛠️  
- **Python** 🐍: Backend logic and data processing.  
- **LangChain** 🛠️: Code extraction and embedding pipeline.  
- **Chromadb** 🌌: Storing and querying vector embeddings.  
- **OpenAI GPT** 🧠: Providing intelligent and context-aware insights.  
- **Flask** 🌐: User-friendly web interface for interaction.  

---

## 💻 Author  
**Ashay Thamankar**  
- [GitHub](https://github.com/ashay-thamankar)  
- [LinkedIn](https://www.linkedin.com/in/ashay-thamankar)  

---

🎉 Dive into your codebase with ease and uncover insights like never before! 😊