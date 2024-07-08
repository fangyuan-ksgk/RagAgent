# 🤖 Claude Agent

Claude Engineer is an advanced interactive command-line interface (CLI) that harnesses the power of Anthropic's Claude-3.5-Sonnet model to assist with a wide range of software development tasks. This tool seamlessly combines the capabilities of a state-of-the-art large language model with practical file system operations, web search functionality, and intelligent code analysis.

## ✨ Features

- 💬 Interactive chat interface with Claude-3.5-Sonnet
- 📁 Comprehensive file system operations (create folders, files, read/write files)
- 🔍 Web search capabilities using Tavily API for up-to-date information
- 🌈 Enhanced syntax highlighting for code snippets
- 🏗️ Intelligent project structure creation and management
- 🧐 Advanced code analysis and improvement suggestions

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

- "Create a new Python project structure for a web application"
- "Explain the code in file.py and suggest improvements"
- "Search for the latest best practices in React development"
- "Help me debug this error: [paste your error message]"

Special commands:
- Type 'exit' to end the conversation and close the application.
- Type 'image' to include an image in your message.
- Type 'automode [number]' to enter Autonomous mode with a specific number of iterations.
- Press Ctrl+C at any time to exit the automode and return to regular chat.
