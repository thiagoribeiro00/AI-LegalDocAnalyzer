# AI-LegalDocAnalyzer

## Overview

The AI-LegalDocAnalyzer project leverages ReAct prompting, Autogen, and AI agents to analyze and review legal documents. This project automates the process of identifying key clauses, detecting potential issues, and suggesting improvements in legal documents.

## Objectives

- **Automated Document Analysis**: Use AI to analyze legal documents and extract relevant information.
- **ReAct Prompting**: Employ ReAct prompts to guide the AI agents in their analysis and decision-making process.
- **AI Agent Interaction**: Define AI agents that interact with users and execute tasks based on the ReAct prompts.
- **Improvement Suggestions**: Provide suggestions for improving the legal soundness of the documents.

## Technologies and Tools

- **Python**: The primary programming language used for the project.
- **Autogen**: A framework for generating and managing AI agents and user proxies.
- **OpenAI GPT-3.5**: Utilized for generating ReAct prompts and analyzing search results.
- **LocalCommandLineCodeExecutor**: Used for executing code locally.
- **Cache**: Mechanisms for caching results to improve efficiency.

## Project Structure

The project is structured into the following components:

- **Configuration**: Settings for the LLM models to use.
  - This includes the configuration for the OpenAI API key and the model specifications.

- **ReAct Prompts**: Pre-defined prompts for legal planning and analysis.
  - These prompts guide the AI agents in their analysis and decision-making process.

- **AI Agents**: Defined agents for legal planning and document analysis.
  - The `LegalPlannerAssistant` is the primary AI agent responsible for analyzing legal documents.

- **Code Execution**: Mechanisms for executing code snippets generated during the analysis.
  - This is handled by the `LocalCommandLineCodeExecutor`.

- **Caching**: Mechanisms for caching LLM responses.
  - This improves the efficiency of the project by reducing the need for repeated computations.

## How to Run the Project

### Prerequisites

- **Python 3.8+**: Ensure you have a compatible version of Python installed.
- **Autogen and Dependencies**: Install the necessary dependencies using `pip install autogen`.
- **OpenAI API Key**: Obtain an API key from OpenAI and set it as an environment variable.

### Steps to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/AI-LegalDocAnalyzer.git
