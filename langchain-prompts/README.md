# LangChain Prompts

This repository contains Python code examples demonstrating how prompts work in LangChain.

The code is based on hands-on learning of LangChain prompt concepts, including static prompts, dynamic prompts, prompt templates, chat prompts, and message placeholders.

## Topics Covered

- Static text prompts
- Dynamic prompts
- PromptTemplate
- Saving and loading prompt templates
- ChatPromptTemplate
- System, Human, and AI messages
- Chat history handling
- Message placeholders
- Simple chatbot with and without memory
- Prompt chaining with models

## Tech Stack

- Python
- LangChain
- OpenAI API
- Streamlit (for prompt-based UI examples)

## Purpose

This repository is intended for:
- Learning LangChain prompt concepts through code
- Serving as a reference for prompt-related LangChain implementations


## Example Application: Research Paper Summarization UI

This repository includes a Streamlit-based application that demonstrates how
**dynamic prompt templates** can be used to build a controlled, production-style
LLM interface.

### Application Overview

The Research Tool allows users to:
- Select a research paper from a predefined list
- Choose an explanation style:
  - Beginner-Friendly
  - Technical
  - Code-Oriented
  - Mathematical
- Choose an explanation length:
  - Short
  - Medium
  - Long
- Generate a structured summary using a LangChain `PromptTemplate`

Instead of accepting free-text prompts, the application uses **template-driven
prompt construction** to ensure consistent, safe, and predictable LLM outputs.

### Key LangChain Concepts Demonstrated

- PromptTemplate with runtime variables
- JSON-based prompt template loading
- Prompt–model chaining using LangChain Expression Language (`template | model`)
- UI-driven prompt inputs with Streamlit
- Separation of prompt logic from application logic

### Output Example

Below is an example of the Streamlit UI and the generated output produced by the
dynamic prompt pipeline.

#### Research Tool Interface
![Research Tool UI](images/research_tool_ui.png)

#### Generated Summary Output
![Generated Output](images/research_tool_output.png)

### Why This Matters

This pattern reflects how prompts are used in real-world applications such as:
- Research assistants
- Internal AI tools
- Knowledge summarization systems
- Controlled enterprise LLM workflows

The design ensures:
- Reduced prompt hallucination
- Consistent response structure
- Better user experience through guided inputs

