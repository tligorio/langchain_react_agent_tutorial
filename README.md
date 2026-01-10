# Simple ReAct Agent using LangChain and OpenRouter
In this demo, we build a simple ReAct agent using the LangChain framework to illustrate how much a framework can abstract and automate compared to our previous demo, where we implemented the agent loop from scratch.

As before, the agent follows the ReAct pattern by iteratively alternating between reasoning and acting to accomplish a task. However, in this version most of the control flow —such as managing the reasoning loop, invoking tools, and handling intermediate state— is handled by the framework (and thus standardized) rather implemented directly by the agent developer.
