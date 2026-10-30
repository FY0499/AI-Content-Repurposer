# AI Content Repurposer

I built this n8n workflow to turn one piece of content into ready-to-review posts for LinkedIn, X (Twitter), and Instagram.

<img width="889" height="160" alt="AI Content Repurposer workflow demo" src="https://github.com/user-attachments/assets/65e887af-fe85-499b-bc80-0cd0053d215f" />

## How it works

1. The user submits the original content through a form.
2. The workflow sends it to an AI model to create platform-specific versions.
3. The response is formatted and organized.
4. The generated posts are saved to Google Sheets and sent through Telegram.

## Technologies

n8n, Groq API, Llama 3.3, JavaScript, Google Sheets, and Telegram.

## Setup

Import [workflow.json](./workflow.json) into n8n, configure the AI API, Google Sheets, and Telegram credentials, then connect your own sheet and Telegram chat.
