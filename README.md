<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=Topic%203%20Multi%20Component%20Customer%20Assistant;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=Topic-3-Multi-Component-Customer-Assistant&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant) · [🐞 Report Issue](https://github.com/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant/issues/new) · [⭐ Star](https://github.com/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/Topic-3-Multi-Component-Customer-Assistant/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

# Topic 3 – Multi-Component Customer Assistant

## Overview

This project is an AI-powered **Multi-Component Customer Assistant** built with **n8n**. It demonstrates how an AI Agent can work with a chat interface, conversational memory, a calculator tool, an OpenAI Chat Model, and structured output parsing to handle customer conversations and arithmetic requests.

## Workflow

**Chat Trigger → Customer Assistant Agent**

The AI Agent is connected to:

- **OpenAI Chat Model** – GPT-4o-mini
- **Window Buffer Memory** – Maintains recent conversation context
- **Calculator Tool** – Handles arithmetic calculations
- **Structured Output Parser** – Produces consistent JSON output

## Key Configuration

| Component | Configuration |
|---|---|
| AI Model | GPT-4o-mini |
| Temperature | 0 |
| Maximum Tokens | 1000 |
| Maximum Iterations | 5 |
| Memory | Window Buffer Memory |
| Memory Context | 10 messages |
| Tool | Calculator |
| Output | Structured JSON |

## Main Capabilities

- Multi-turn customer conversations
- Conversation memory and recall
- Calculator-based arithmetic for totals and discounts
- Structured JSON responses
- Concise and professional customer assistance

## Structured Output

```json
{
  "response": "Customer-facing answer",
  "category": "sales",
  "calculation_used": true,
  "result": "53.973"
}
```

## Example

For a purchase of 3 items at $19.99 each with a 10% discount, the Calculator Tool returns the precise result **53.973**, which can be presented to the customer as **$53.97** when rounded to two decimal places.

## Demo

🎥 **Loom Demo:**
https://www.loom.com/share/16ad65aaefdf4638aad6dfb5ef40c87d

## Repository Contents

- **n8n workflow JSON** – Exported workflow for import and reuse
- **Assessment documentation PDF** – Project documentation and evidence summary
- **README.md** – Project overview and usage information
- **Screenshots / evidence** – Workflow and validation evidence

## How to Use

1. Import the exported workflow JSON into n8n.
2. Configure the required AI credentials.
3. Open the Chat Trigger interface.
4. Start a conversation with the Customer Assistant.
5. Test memory recall using multiple messages in the same session.
6. Test arithmetic requests to verify Calculator Tool usage.
7. Verify the structured JSON output.

## Assessment Focus

This project demonstrates practical use of:

- n8n AI Agent
- Chat Trigger
- OpenAI Chat Model
- Conversational Memory
- Calculator Tool
- Structured Output Parser
- Multi-turn conversations
- Prompt-based agent instructions

## Status

**Completed – Topic 3 LMS Assessment**
