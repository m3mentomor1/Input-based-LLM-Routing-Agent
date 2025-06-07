<div align="center">
  <h1>Input-based LLM Routing Agent</h1>
</div>

### 🧐 I. Overview

A dynamic input-based LLM routing AI-agent built with n8n. It selects the most suitable language model: 
- Sonar (Perplexity)
- GPT o3-mini-high (OpenAI)
- Claude 3.5 Sonnet (Anthropic)

based on user queries, and uses the selected model to answer, solve, or address the input accordingly.
<br><br>
##

### ⛓️ II. Workflow
![image](https://github.com/user-attachments/assets/02b88522-7284-4da4-b807-0d975c712279)

The workflow above contains the following nodes: 

- ``Chat Trigger`` (Chat Input) 

- ``AI Agent`` (Routing Agent, Agent Output)

- ``OpenRouter Chat Model`` (gpt-4o-mini, Dynamic Model)

- ``Simple Memory`` (Memory 1, Memory 2)

- ``Structured Output Parser``
<br><br>
##

### 🛠️ III. Use this repository

**1. Make sure to have the following requirements:**

- **n8n** account (Click [here](https://app.n8n.cloud/register) to create an account.)
- **OpenRouter** account (Click [here](https://openrouter.ai/) to create an account.)
- **Docker Desktop** (Optional for local hosting. Download [here](https://www.docker.com/).)
<br>

**2. Clone this repository.**

   Run this command in your terminal: 
   ```
   git clone https://github.com/m3mentomor1/Input-based-LLM-Routing-Agent.git
   ```
(Optional: You can also ```Fork``` this repository.)

<br>

**3. Go to the repository's main directory.**

   Run this command in your terminal: 
   ```
   cd Input-based-LLM-Routing-Agent
   ```
<br>



