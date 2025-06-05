# Prodigal AI Agents

## Overview

This project implements a modular AI Agent framework using Python with:

- MessageBus to route messages between agents
- OllamaAgent to call offline LLM models (tinylama)
- TaskManagerAgent to process tasks by delegating to OllamaAgent
- Runtime to manage the message bus and agents
- Tests for agents, bus, and runtime

## Setup

1. Install dependencies:

```bash
pip install -r requirements.txt
