# 🧠 Automated Resume Tailoring Workflow (n8n + LLMs)

## 📋 Requirements

1. **n8n account** – create one at [n8n.io](https://n8n.io)
2. **Run n8n locally (free)** or use the **cloud version** (free trial available)
3. Obtain API keys for the required integrations:
   - **Google Sheets API** – from [Google Cloud Console](https://console.cloud.google.com/)
   - **Gemini API** – from [Google AI Studio](https://aistudio.google.com/)
   - **Firecrawl API** – from [Firecrawl.dev](https://firecrawl.dev/)
   - **OpenAI API** – from [platform.openai.com](https://platform.openai.com/)

---

## 🚀 Overview

This workflow automates the **resume tailoring process** for job applications using **n8n** and **Large Language Models (LLMs)**.

Traditionally, customizing a resume for each role takes about **15 minutes** per application.  
With this workflow, the entire **tailoring step is automated**, allowing **parallel execution for multiple job descriptions** — drastically reducing manual effort and saving significant time.

The only manual steps are:
- Finding relevant job postings  
- Uploading your resume template (done only once)
- Submitting the final tailored resume  

Everything in between — extracting job details, matching requirements, rewriting bullet points, and aligning keywords — is handled automatically by the workflow’s LLM logic and system prompts.

These **system prompts are customizable** to match your profile or tone; simply modify them in n8n to reflect your experience and preferences.

---

## 🧩 Tech Stack

- **n8n** for orchestration  
- **Google Sheets** for structured data input/output  
- **Gemini / OpenAI APIs** for LLM-driven tailoring  
- **Firecrawl** for extracting job descriptions from links  

---

## 🧠 Customization

You can adjust:
- The **system prompts** to reflect your professional background  
- The **data sources** (e.g., replace Google Sheets with Airtable or CSV)  
- The **output format** (resume, summary, or cover letter)

---

## ⚙️ Notes

- Exported workflow JSONs **do not include credentials**, so it’s safe to share publicly.  
- Each user must connect their own API keys inside n8n after importing the workflow.

---

## 📸 Example

> _Add your screenshots or diagrams here (e.g., workflow overview, example input/output)._
