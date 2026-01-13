# LangChain Core Concepts

This repository provides a structured and practical exploration of LangChain’s core abstractions that are used to build reliable and scalable LLM applications.

Instead of focusing on end applications, this repository focuses on understanding how LangChain works internally by breaking it down into its fundamental building blocks.

## What This Repository Covers

This repository consolidates all foundational LangChain concepts into a single, well-organized codebase.

The focus is on clarity, composability, and correctness.

## Core Concepts Implemented

### Prompts
Covers how prompts are created, parameterized, reused, and loaded.

Includes:
- Static prompts
- PromptTemplate
- ChatPromptTemplate
- Saving and loading prompts from files

### Models
Demonstrates how LangChain interacts with different LLM backends.

Includes:
- OpenAI-compatible chat models
- Hugging Face API-based models
- Locally hosted Hugging Face models

### Structured Output
Explains how LLMs can be guided to return machine-readable output.

Includes:
- TypedDict-based schemas
- Pydantic-based schemas
- JSON Schema based structured output

### Output Parsers
Shows how raw LLM responses are converted into structured formats.

Includes:
- StringOutputParser
- JsonOutputParser
- StructuredOutputParser
- PydanticOutputParser

### Chains
Demonstrates how multiple LangChain components are composed into execution pipelines.

Includes:
- Basic single-step chains
- Multi-step chains
- Chains combined with output parsers

### Runnables
Explores LangChain’s Runnable interface for building flexible and composable workflows.

Includes:
- Runnable basics
- Runnable pipelines
- Branching and composition patterns

## Why This Structure Matters

LangChain applications become complex very quickly.

Understanding these core abstractions allows to:
- Build maintainable LLM pipelines
- Enforce structured and validated outputs
- Compose reusable workflows
- Scale from experiments to production systems

This repository reflects how LangChain is designed conceptually and how it should be used in real-world systems.


