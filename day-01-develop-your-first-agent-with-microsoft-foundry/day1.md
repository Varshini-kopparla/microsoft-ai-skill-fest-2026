# Day 1 - Develop Your First Agent with Microsoft Foundry

## Overview

Today I completed the Microsoft AI Skills Fest learning path:

**Develop Your First Agent with Microsoft Foundry**

The goal of this lab was to understand the basics of Generative AI, AI agents, Azure AI Foundry, and how to build and interact with a custom AI agent.

---

## What is Generative AI?

Generative AI is a type of artificial intelligence that can create new content such as:

- Text
- Code
- Images
- Audio
- Videos

Instead of only finding information, Generative AI can generate responses based on the patterns it learned from large amounts of data.

Examples:

- ChatGPT
- GitHub Copilot
- Microsoft Copilot
- Claude
- Gemini

---

## What is an AI Agent?

An AI agent is more than a chatbot.

A chatbot simply answers questions.

An AI agent can:

- Follow specific instructions
- Use tools
- Make decisions
- Perform tasks
- Remember context
- Interact with applications

Think of an AI agent as an AI assistant designed for a specific purpose.

Examples:

- Customer support agent
- Coding assistant
- Interview coach
- Travel planner
- System design mentor

---

## What is Microsoft Foundry?

Microsoft Foundry is a platform that helps developers:

- Build AI applications
- Create AI agents
- Manage AI models
- Test prompts
- Deploy AI solutions

It provides tools to quickly develop and experiment with AI-powered applications.

---

## What I Built

For this lab, I created a custom AI agent called:

**System-Design-Mentor**

The purpose of the agent is to help software engineers learn system design interviews step-by-step.

The agent was instructed to:

- Act like a Senior Staff Software Engineer
- Teach system design from beginner to advanced level
- Use active learning
- Ask questions one step at a time
- Explain tradeoffs and design decisions
- Guide users through interview preparation

---

## Steps I Completed

### 1. Created an Azure AI Foundry Project

- Signed into Azure
- Created a Microsoft Foundry project
- Explored the Foundry playground

### 2. Created a Custom AI Agent

- Added custom instructions
- Defined the behavior of the agent
- Configured the model
- Tested conversations in the playground

### 3. Tested the Agent

I asked the agent system design questions such as:

- Design WhatsApp
- Design Uber

The agent responded by guiding me through requirements clarification before jumping into architecture discussions.

This mimics how system design interviews are usually conducted.

### 4. Installed Microsoft Foundry Toolkit in VS Code

I connected Visual Studio Code with Microsoft Foundry and explored:

- Prompt Agents
- Models
- Hosted Agents
- Agent Builder

### 5. Connected to the Agent Using Python

I created a Python application that:

- Authenticated with Azure
- Connected to my Foundry project
- Referenced my custom agent
- Sent prompts to the agent
- Printed responses in the terminal

### 6. Enhanced the Application

I modified the sample code so that:

- Users can continuously enter prompts
- The conversation runs in a loop
- Typing `quit` exits the application

This made the application behave more like a real chatbot.

---

## Key Concepts Learned

### Prompt Engineering

Prompt engineering is the process of writing instructions that guide how an AI model behaves.

Good prompts lead to more accurate and useful responses.

---

### Agent Instructions

Agent instructions define:

- Personality
- Behavior
- Scope
- Response style

These instructions help transform a general AI model into a specialized assistant.

---

### Azure AI Foundry

Azure AI Foundry provides:

- Model management
- Agent creation
- Testing environments
- Deployment tools
- Monitoring capabilities

---

### Azure AI Projects SDK

The Azure AI Projects SDK allows developers to interact with AI agents programmatically using code.

This is how applications communicate with AI agents outside the playground.

---

## Challenges Faced

- Understanding the Azure resource hierarchy
- Publishing the agent correctly
- Connecting VS Code to Microsoft Foundry
- Configuring Azure CLI authentication
- Learning how agent references work in Python

---

## Final Outcome

By the end of the lab, I successfully:

✅ Built a custom AI agent

✅ Published the agent in Microsoft Foundry

✅ Connected to the agent using Python

✅ Modified the application to support interactive conversations

✅ Learned the fundamentals of Generative AI and AI agents

---

## Screenshots

1. Agent created in Microsoft Foundry

<img width="933" height="504" alt="image" src="https://github.com/user-attachments/assets/8ccc539c-cc89-4fcb-99f0-dc78768139c4" />
<br>
<br>

<img width="933" height="505" alt="image" src="https://github.com/user-attachments/assets/09add1d8-c350-494a-bd89-b3f328801ee8" />


<br>
<br>
2. Microsoft Foundry Toolkit in VS Code

<img width="934" height="590" alt="image" src="https://github.com/user-attachments/assets/3aecfe61-af3c-493d-8470-1e1cbc0859f1" />

<br>
<br>

<img width="934" height="593" alt="image" src="https://github.com/user-attachments/assets/4e35dd28-9274-4cff-a47f-a6e7aada0c66" />

<br>
<br>
3. Python code connecting to the agent

<img width="934" height="588" alt="image" src="https://github.com/user-attachments/assets/6985156b-b7d2-4537-ab14-0b3ad4b43893" />
<br>
<br>

   
4. Successful terminal interaction

   <img width="934" height="587" alt="image" src="https://github.com/user-attachments/assets/18ab9f24-f01b-4ca5-860c-878c05c9eec9" />
<br>
<br>
5. Using GitHub Copilot to Enhance the Agent

   <img width="932" height="582" alt="image" src="https://github.com/user-attachments/assets/89b8ecc7-289d-414f-b329-2f6ecb14e0e0" />


---

## Reflection

This was a great introduction to AI agents and Microsoft's AI ecosystem.

The most interesting part was seeing how a custom AI agent can be designed with specific instructions and then accessed directly through code using Python.

I'm excited to continue exploring agentic AI, Azure AI Foundry, and real-world AI application development throughout Microsoft AI Skills Fest 2026.
