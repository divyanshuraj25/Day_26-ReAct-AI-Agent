# Day 26 – Manual ReAct AI Agent 🤖

## 📌 Overview

This project implements a **ReAct (Reasoning + Acting) AI Agent manually in Python without using an agent framework**.

The goal is to understand how an AI agent works internally by implementing the complete loop:

**Thought → Action → Observation → Thought → ... → Final Answer**

The agent uses the **Gemini API** as the LLM and can autonomously select and execute different tools to solve multi-step problems.

---

## 🎯 Objectives

- Understand the ReAct agent architecture
- Implement the ReAct loop manually
- Connect an LLM with external tools
- Create a tool registry and dispatch system
- Execute multi-step tasks using multiple tools
- Observe the agent's tool-selection behavior
- Analyze agent failures and reliability

---

## 🛠️ Technologies Used

- Python
- Google Gemini API
- Google Colab
- JSON
- Regular Expressions
- Python AST

---

## 🔧 Tools Implemented

The agent has three tools:

### 1. Calculator

```python
calculator(expression)
