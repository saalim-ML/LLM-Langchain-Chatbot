# LLM-Langchain-Chatbot
This project is a command-line chatbot built using 'LangChain and OpenAI' LLMs.   It demonstrates how to create a conversational AI application using 'prompt templates', LLM chains and chat history management.


## 📌 Key Concepts Covered

- Large Language Models (LLMs)
- LangChain framework
- Prompt Engineering
- Chat History handling
- OpenAI API integration
- Output parsing
- CLI-based chatbot

---

## 🧠 Technologies Used

- Python
- LangChain
- OpenAI (`ChatOpenAI`)
- GPT-4o-mini
- Environment Variables

---

## 🤖 How the Chatbot Works

1. Initializes a system prompt defining chatbot behavior  
2. Accepts user input continuously  
3. Maintains conversation history  
4. Sends prompts to OpenAI via LangChain  
5. Parses and prints the LLM response  
6. Stops when the user types `exit` or `quit`

---

## ⚙️ Model Configuration

- Model: GPT-4o-mini  
- Temperature: 0 (deterministic responses)  
- Output Parser: `StrOutputParser`
