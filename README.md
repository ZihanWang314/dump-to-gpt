
# 🛠️ dump-to-GPT

**dump-to-GPT** is a super simple tool to share your entire codebase with GPT models in just one step! No more endless explanations or copying snippets – this tool gathers your code, organizes it, and prepares a detailed report ready to send to GPT.

## ✨ Features

- 🚀 **One-Line Command**: Capture your entire codebase with a single line.
- 📝 **Customizable Output**: Get a clear report of all files, functions, and classes.
- ⏱️ **Saves Time**: No more explaining your code to GPT from scratch!
- 🌍 **Works with Any Project**: Just point it to your codebase, and it does the rest.

## 📦 Installation

First, clone this repo:

```bash
git clone https://github.com/ZihanWang314/dump-to-gpt
cd dump-to-gpt
```

## 🚀 Quick Start

Generate a report with just one line:

```bash
python main.py --dir my_project
```

The tool will create a detailed report of your codebase, ready to paste into GPT. 

The first time you run it, the system will ask you whether to include each file in the report. Your preferences will be recorded for your future use!

## 📄 What’s in the Report?

Here’s a sample of what the report looks like:

```
FILE 1: src/main.py
"""
# Main script for project initialization and configuration
import config
import utils

def main():
    print("Hello, GPT!")
    # More main logic here

if __name__ == "__main__":
    main()
"""

FILE 2: src/utils.py
"""
# Utility functions for data processing
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b
"""

And so on…
```

Each file is listed with:
- **File path**
- **File contents** 

This structured output gives GPT everything it needs to understand your project’s organization, main functions, and configurations.

## 🤔 Why dump-to-GPT?

Perfect for developers who:
- Work with large codebases and need a fast summary.
- Regularly use GPT for coding help or project overviews.
- Want a lightweight, no-fuss solution to work with GPT faster.

## 🤝 Contributing

Got ideas? Found a bug? Open an issue or pull request – contributions are always welcome!

## 📢 Stay in Touch!

This tool is part of **AI-wrench**, a series of simple tools to boost AI engineering productivity. Follow for more at [AI-wrench on GitHub](http://www.github.com/zihanwang314/AI-wrench)!

---

With **dump-to-GPT**, sharing your code with AI just got a whole lot easier. Happy coding! 🚀
