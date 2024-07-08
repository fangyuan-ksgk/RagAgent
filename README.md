# 🤖 RAG Agent

RAG Agent is an interactive command-line interface (CLI) which allow you to chat with your database using Claude-3.5-Sonnet model. 

## ✨ Features

- 💬 Interactive chat interface with Claude-3.5-Sonnet
- 💬 Adaptive on-request RAG


## 🛠️ Installation

1. Clone this repository:
   ```
   git clone https://github.com/Doriandarko/claude-engineer.git
   cd claude-engineer
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your API keys:
   - Add your Anthropic and Tavily API keys at the start of the file:
     ```python
     client = Anthropic(api_key="YOUR API KEY")
     tavily = TavilyClient(api_key="YOUR API KEY")
     ```

## 🚀 Usage

Run the main script to start the Claude Engineer interface:

```
python main.py
```

Once started, you can interact with Claude Engineer by typing your queries or commands. Some example interactions:

- "What are the related conversation about insurance?"

Special commands:
- Type 'exit' to end the conversation and close the application.
