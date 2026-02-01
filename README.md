

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Analyze stock sentiment with GPT-4o and create Asana tasks with Slack alerts

Advanced n8n automation for Analyze stock sentiment with GPT-4o and create Asana tasks with Slack alerts.

## Overview
- Category: Crypto Trading, AI RAG
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Automate real-time stock sentiment from X/Instagram: AI scores buy/sell intent and urgency, then creates Asana tasks and Slack alerts. Learn more.

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.lmChatAzureOpenAi`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.mcpClientTool`
- `n8n-nodes-base.asana`
- `n8n-nodes-base.code`
- `n8n-nodes-base.errorTrigger`
- `n8n-nodes-base.set`
- `n8n-nodes-base.slack`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.webhook`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.