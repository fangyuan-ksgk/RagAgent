# 🤖 RAG Agent

RAG Agent is an interactive command-line interface (CLI) which allow you to chat with your database using Claude-3.5-Sonnet model. 

## ✨ Features

- 💬 Interactive chat interface with RAG Agent
- 💬 Adaptive on-request RAG
- More to come


## 🛠️ Installation

1. Clone this repository:
   ```
   git clone https://github.com/fangyuan-ksgk/SmallRag.git
   cd RagAgent
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your API keys:
   - Add your Anthropic API key at the start of the file:
     ```python
     os.environ["ANTHROPIC_API_KEY"] = "YOUR_API_KEY"
     os.environ["PANDASAI_API_KEY"] = "YOUR_API_KEY"
     ```

## 🚀 Usage

Run the main script to start the RAG Agent interface:

```
python main.py
```

Once started, you can interact with RAG Agent by typing your queries or commands. Some example interactions:

- "What are the related conversation about insurance?"

Special commands:
- Type 'exit' to end the conversation and close the application.
