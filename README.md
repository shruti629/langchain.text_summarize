

# LangChain Text Summarizer 📝

## A  application that summarizes content from YouTube videos and websites using LangChain and LLMs.
 This tool helps you quickly extract key insights without going through long videos or reading lengthy articles.

## 🚀 Features

📺 Summarize YouTube videos (just paste the link).

🌐 Summarize any website content.

🤖 Powered by LangChain + LLMs for high-quality summaries.

🖥️ Simple and interactive Streamlit UI.



## 🛠️ Tech Stack

    Python

    Streamlit

    LangChain

    [OpenAI / Groq / Any LLM API] (depending on your setup)

## 📦 Installation

Clone this repository:

    git clone https://github.com/shruti629/langchain.text_summarize.git
    cd langchain.text_summarize


Create a virtual environment & activate it:

     python -m venv venv
     source venv/bin/activate   # for Linux/Mac
     venv\Scripts\activate      # for Windows


Install dependencies:

    pip install -r requirements.txt

## ⚙️ Setup

Get your LLM API key (e.g., OpenAI / Groq).

Create a .env file in the project root and add:

OPENAI_API_KEY=your_api_key_here


(or GROQ_API_KEY if you are using Groq)

## ▶️ Usage

Run the Streamlit app:

streamlit run app.py


## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo, open issues, and submit PRs.

## 📜 License

This project is licensed under the MIT License.
