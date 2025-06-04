# Autogen + Mistral: A Minimal Agentic AI Example

This project demonstrates how to build a lightweight Autogen agent using Hugging Face’s Mistral-7B-Instruct model. It serves as a practical "Hello World" for anyone curious about working with Microsoft's open-source Autogen framework and exploring agentic AI design patterns.

## Project Overview

- **Goal:** Run a single-agent conversational assistant using Hugging Face’s transformer models and Microsoft Autogen’s `ConversableAgent` interface.
- **LLM Backend:** `mistralai/Mistral-7B-Instruct-v0.1` hosted on Hugging Face.
- **Framework:** [Autogen](https://github.com/microsoft/autogen) – an open-source library for building multi-agent workflows.
- **Runtime:** Google Colab (GPU required for full performance).

## Features

- Uses `ConversableAgent` to create an AI assistant capable of multi-turn conversations.
- Runs a local function to perform inference using Mistral with `transformers`.
- Supports both 1-turn static prompts and multi-turn interactive chat loops.
- Easily extendable to include:
  - Critic agents
  - Tool-using agents
  - Planning or await agents
  - Multi-agent cooperation (e.g., two-agent chat)

## What You Can Learn

- How to build and interact with Autogen agents using any Hugging Face model.
- How to integrate open-source LLMs into low-code interfaces with Python.
- Basics of agent conversation design including role-based memory, response routing, and prompt chaining.
- How to use agentic programming frameworks for rapid prototyping and complex task execution.

## Expandable Concepts

This starter project can evolve into more advanced implementations such as:

- Code-executing agents with sandboxed tools
- Agent loops for automated debugging or content review
- Integration with APIs, databases, or enterprise logic
- Visual workflows via Autogen Studio (Autogen's official low-code UI)

## Keywords and Topics

`agentic AI`, `autogen studio`, `assistantagent`, `critic agent`, `code execution`, `human feedback`, `await agent`, `event driven`, `cross language support`, `low code interface`, `multi agent`, `solving complex tasks`, `design patterns`, `framework for building`, `autogen import assistantagent`, `open source framework`, `generated code`, `building multi-agent workflows`

## Getting Started

To reproduce the setup:
- Use a GPU-enabled Google Colab notebook.
- Log into Hugging Face to access the Mistral model.
- Follow the step-by-step instructions in the notebook to initialize your assistant agent.

## Contributions Welcome

This repo is an evolving demo of how Autogen can interface with the wider AI ecosystem. If you'd like to:
- Add more agents
- Connect tools or APIs
- Port to another LLM
- Create a full workflow or feedback loop

Feel free to open a pull request or file an issue.

## Credits

- [Microsoft Autogen](https://github.com/microsoft/autogen)  
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)  
- [Mistral-7B-Instruct-v0.1](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1)
