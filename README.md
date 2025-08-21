# n8n_workflows
Agentic AI workflow using N8n 

Resume Screening
=================
This is Agentic AI where the user provides -
1. Candidate Name
2. Resume Text
3. Job Description

The workflow is executed using Gemini LLM API and gives the output having -
1. Status - Shortlist/Rejected
2. Reason
3. Confidence Score

The given output is saved in Google sheet for future references.

Health Image Generator to Telegram
==================================
This is Agentic AI where the Gemini LLM fetches the random content from the Google Sheet tool and generate a high quality image with embedded text. This image is then posted by Telegram bot to the different telegram chat IDs
