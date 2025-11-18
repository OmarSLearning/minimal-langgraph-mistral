# minimal-langgraph-mistral
A minimal example to demonstrate how to build a one-node chat workflow using LangGraph and Mistral. Perfect as a first hands-on example for discovering agentic AI.

Requirements

Install dependencies:

pip install langchain langgraph mistralai

How to Run

Run the script:

python src/minimal_chat_workflow.py


You will be asked to enter your Mistral API key.

Description

This minimal example:

defines a simple state with a question and a response

creates a LangGraph with one node

invokes the Mistral model to generate an answer

prints the final response

It serves as a clean and minimal foundation before exploring more advanced agentic workflows.
