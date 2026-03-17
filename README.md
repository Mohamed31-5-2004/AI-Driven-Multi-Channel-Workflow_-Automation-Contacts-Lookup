# AI-Driven-Multi-Channel-Workflow_-Automation-Contacts-Lookup
AI-Driven Multi-Channel Workflow Automation Using n8n
Course: AI-Based Systems
Lab Type: Practical Implementation
Max Team Size: 2 students
Submission Components:

.json export of the implemented n8n workflow

Short demo video (3–5 minutes)

One submission per team

🎯 Objective
The goal of this lab is to design and implement a fully automated intelligent workflow for business users that integrates communication platforms (e.g., WhatsApp, Telegram) with email processing and LLM-based natural language understanding using n8n and the Multi-Channel Protocol (MCP).

🧩 Scenario Overview
A company owner wishes to extract insights from email correspondence using AI. Instead of manually searching, they send a structured message via WhatsApp or Telegram, containing:

A custom prompt (e.g., “Summarize support issues in the last 2 days”)

A dynamic list of email addresses

Your workflow must respond by:

Receiving the message through WhatsApp/Telegram.

Parsing the message to extract the prompt and email list.

Filtering and retrieving the latest 10 emails for each email address.

Combining email content with the input prompt.

Sending the combined input to an LLM (e.g., OpenAI GPT or similar).

Processing and refining the response.

Sending the result:

Back to the origin platform (WhatsApp/Telegram)

And to the admin’s email

🛠️ Technical Requirements
Deploy n8n locally (self-hosted, not cloud version).

Use n8n to design the entire data flow with clear node logic.

Integrate multiple services (Telegram/WhatsApp, Email, LLM) under MCP architecture.

Maintain logs for input and output communication.

Validate your workflow with at least one test message.

📂 Expected Deliverables
✅ workflow.json export file

🎥 A recorded video demo that:

Shows the system being triggered by a WhatsApp/Telegram message

Demonstrates email retrieval, LLM response generation

Displays the final result sent back to the user

📩 Email confirmation sent to the administrator

 

MCP-Based Automated Workflow for Email Insight Extraction
 image.png
📌 Bonus
- Integrate with google contacts at the chat ask search for mohamed or ail and from google contacts you can get their emails and continue your normal flow 

📌 Notes for Students
Ensure the message parsing handles dynamic email counts.

You are encouraged to use third-party APIs such as Gmail, Outlook, or IMAP-compatible services.

Choose the LLM that best fits your needs (GPT, Claude, local model).

You may use open-source Telegram bots or WhatsApp Cloud API for integration.

Think modularly: test each node of your workflow in isolation first.

