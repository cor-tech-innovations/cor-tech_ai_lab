# Cor-Tech Innovations AI Lab

This repository serves as the official portfolio and development lab for my AI prototypes and projects. As the **Lead Innovation Architect**, I use this space to build, test, and showcase solutions that bridge the gap between AI, cloud infrastructure, and cybersecurity.

## 🚀 AI-102 Prototypes (My "Prototype-to-Pass" Plan)

This section contains the hands-on projects I built while preparing for the AI-102 (Azure AI Engineer) certification. Each prototype solves a specific business problem and demonstrates mastery of a core Azure AI service.

### 🛡️ Prototype 1: CMMC Compliance Bot (Azure AI Foundry)

* **Project:** Designed and deployed a secure, **RAG (Retrieval-Augmented Generation)** agent in **Azure AI Foundry (AI Studio)** to serve as a CMMC Compliance Bot.
* **Accomplishment:** Engineered a robust system prompt ("Instructions") to ground the `gpt-4o` model, ensuring it *only* answered questions based on private CMMC documentation and securely refused all off-topic queries.
* **Skills:** `Azure AI Foundry`, `Generative AI`, `RAG`, `Prompt Engineering`, `Security & Grounding`

### 📸 Prototype 2: Insurance Claim App V0.1 (Custom Vision)

* **Project:** Developed an **Object Detection** model in **Azure Custom Vision** to identify 'dents' and 'scratches' on vehicles for an automated insurance claim app.
* **Accomplishment:** Successfully trained the model to distinguish between real damage and false positives (like light reflections and shadows) by adding a dedicated **'Negative' image class**, significantly improving model precision.
* **Skills:** `Azure Custom Vision`, `Object Detection`, `Model Training`, `Troubleshooting`, `False Positives`

### 🏷️ Prototype 3: Helpdesk Sorter V1 (Custom Language)

* **Project:** Built and trained a **Custom Text Classification** model in **Azure AI Language Studio** to automatically triage helpdesk tickets.
* **Accomplishment:** Diagnosed and fixed **Class Ambiguity** and **minimum data thresholds**. Proved that building a high-quality, balanced, and clearly-labeled dataset is the correct method to increase model accuracy.
* **Skills:** `Azure AI Language`, `Custom Text Classification`, `Data Labeling`, `Model Training`, `Troubleshooting`

### ✍️ Prototype 4: SOP Generator V1 (Generative AI)

* **Project:** Architected a **Generative AI** solution to automate the creation of Standard Operating Procedures (SOPs).
* **Accomplishment:** Developed a complex, multi-part "meta-prompt" that guides the LLM to generate highly structured, formatted documents based on simple user inputs, turning a multi-hour task into a 2-minute process.
* **Skills:** `Prompt Engineering`, `Generative AI`, `Azure OpenAI`, `Workflow Automation`
