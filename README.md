# ReAct Agent with LangGraph

This repository contains the implementation of a **ReAct (Reasoning + Acting) agent** built using [LangGraph](https://langgraph.dev). ReAct agents combine reasoning and action to achieve complex problem-solving tasks by leveraging large language models (LLMs) in a graph-based workflow.

## 🚀 Features
- **LangGraph Integration**: Utilize LangGraph's stateful, graph-based structure to create dynamic and intelligent ReAct workflows.
- **Reasoning + Acting**: Implements the ReAct framework for agents to reason through problems, take appropriate actions, and iteratively improve outcomes.
- **Customizable Workflows**: Easily modify the graph structure to support a variety of tasks and multi-agent scenarios.
- **Multi-Agent Coordination**: Includes an example of multiple agents working together to achieve shared goals.
- **Real-World Applications**: Pre-built templates for knowledge retrieval, question answering, and decision-making tasks.

## 📚 Setup

### Python version

To get the most out of this course, please ensure you're using Python 3.11 or later. 
This version is required for optimal compatibility with LangGraph. If you're on an older version, upgrading will ensure everything runs smoothly.
```
python3 --version
```

### Clone repo
```
$ git clone https://github.com/troniak/langgraph-agent.git
$ cd langgraph-agent
```

### Create an environment and install dependencies
#### Mac/Linux/WSL
```
$ python3 -m venv lg-env
$ source lg-env/bin/activate
$ pip install -r requirements.txt
```
