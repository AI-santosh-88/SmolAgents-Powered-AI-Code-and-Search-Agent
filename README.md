# Title: SmolAgents-Powered AI Code and Search Agent
## Description:
* This project builds an AI-powered agent using the SmolAgents library to generate code and perform web-based information retrieval. It leverages models from Hugging Face (using the HfApiModel) and integrates with external search tools like DuckDuckGo to provide intelligent responses to complex queries. The agent can autonomously handle tool-based tasks, retrieve information, and generate code based on user prompts.

## Responsibilities:
### 1.Model Integration:
* Connect to Hugging Face models using the HfApiModel class and API keys.
* Configure the CodeAgent and ToolCallingAgent with the necessary models and tools.
### 2.Information Retrieval:
* Set up the DuckDuckGoSearchTool to perform real-time web searches.
* Process search results and pass them to the model for analysis and output.
### 3.Code Generation:
* Use the CodeAgent to generate code snippets or scripts based on user prompts.
* Handle programming logic and syntax errors.
### 4.Agent Handling:
* Manage multiple agents for different tasks (e.g., coding vs. search).
* Optimize agent performance and output quality.
### 5.User Interaction:
* Develop an intuitive interface for user input and agent responses.
* Implement logging and error handling for improved user experience.

### Libraries Used:
✅ smolagents – For building AI agents

✅ os – For setting environment variables

✅ Hugging Face (HF) – For accessing machine learning models

✅ DuckDuckGoSearchTool – For web search integration

## Summary:
* The project creates an AI-driven agent that combines code generation with real-time information retrieval. It enables dynamic responses to complex questions, automates code-related tasks, and enhances productivity using a multi-agent framework. The CodeAgent handles coding tasks, while the ToolCallingAgent processes search queries — making the solution versatile for various AI and automation applications.

