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
