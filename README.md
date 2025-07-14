# Email Sending using Agentic AI

This project demonstrates how to build an intelligent email-sending assistant using Agentic AI concepts powered by the `langchain` framework and `langchain_google_genai`. It integrates with IMAP for reading emails and uses LLMs for decision-making in sending responses.

## 🚀 Features

- Reads emails using `imaplib`
- Integrates with Google's GenAI model via `langchain_google_genai`
- Maintains session and email tracking using `pickle`
- Automates intelligent email responses

## 🛠️ Installation

Dowload the repository and install the required dependencies.

### Install Dependencies

```bash
pip install langchain langchain-google-genai
```

> Note: Additional dependencies used in the project (`email`, `imaplib`, `os`, `pickle`) are part of Python’s standard library.

## 📁 File Structure

```plaintext
.
├── email_sending_using_Agentic_AI.ipynb   # Main notebook
├── README.md                              # Project description and instructions
```

## 📌 Usage

1. Ensure you have access credentials for your email account (for `imaplib` to work).
2. Make sure your environment has access to the required Google GenAI credentials.
3. Open the notebook using Jupyter:

```bash
jupyter notebook email_sending_using_Agentic_AI.ipynb
```

4. Run all the cells step by step, configuring credentials and model parameters where necessary.

