# Simple ReAct Agent using LangChain and OpenRouter
#### Tiziana Ligorio for *AI Agents - CSCI 395.32* taught at Hunter College of The City University of New York

#### This demo has two parts:

#### In **Part 1** 
We build a simple ReAct agent using the LangChain framework to illustrate how much a framework can abstract and automate compared to our previous demo, where we implemented the agent loop from scratch.

As before, the agent follows the ReAct pattern by iteratively alternating between reasoning and acting to accomplish a task. However, in this version most of the control flow —such as managing the reasoning loop, invoking tools, and handling intermediate state— is handled by the framework (and thus standardized) rather implemented directly by the agent developer.  

#### In **Part 2** 
We demonstrate how to trace and run evals using LangSmith. 

## Getting Started

### Option 1: Run in Google Colab (Recommended for Part 1 of the notebook ONLY)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tligorio/langchain_react_agent_tutorial/blob/main/LangChain_ReAct_agent_OpenRouter.ipynb)

Click the badge above to open the notebook directly in Google Colab.

### Option 2: Run Locally

For local installation, clone this repository and follow the instructions in [SETUP.md](SETUP.md).
