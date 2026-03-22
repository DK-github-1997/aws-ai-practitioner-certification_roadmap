# 🛠️ Week 3 & 4 — AWS AI Services

## 🎯 What You Will Learn
- All major AWS AI/ML services and what they do
- When to use which service (exam loves these questions!)
- Real-world use cases for each service
- Amazon SageMaker deep dive

---

## 📦 AWS AI Services Quick Reference

### 🔵 Amazon SageMaker — Build, Train, Deploy ML Models
**What:** Fully managed platform to build, train, and deploy ML models  
**Why use it:** No need to manage infrastructure — AWS handles servers  
**Exam tip:** SageMaker = the main service when you need CUSTOM ML models

| SageMaker Feature | What It Does |
|-------------------|-------------|
| SageMaker Studio | IDE for data scientists |
| SageMaker Autopilot | Auto builds ML models (AutoML) |
| SageMaker Ground Truth | Label training data |
| SageMaker Canvas | No-code ML for business users |
| SageMaker Clarify | Detect bias in models |
| SageMaker Pipelines | Automate ML workflows |

---

### 👁️ Amazon Rekognition — Vision AI
**What:** Analyse images and videos using AI  
**Use cases:**
- Face detection and recognition
- Object/scene detection ("car", "beach", "person")
- Content moderation (detect unsafe images)
- Celebrity recognition
- Text in images (OCR)

---

### 📝 Amazon Comprehend — Natural Language Processing (NLP)
**What:** Understand text — find meaning, sentiment, entities  
**Use cases:**
- Sentiment analysis ("Is this review positive or negative?")
- Entity extraction (names, places, dates in text)
- Document classification
- Key phrase extraction

---

### 📄 Amazon Textract — Extract Text from Documents
**What:** Extract text, tables, and forms from scanned documents/PDFs  
**Use cases:**
- Read bank statements, invoices, tax forms
- Extract data from handwritten forms
- Process insurance claims, medical records

**Difference from Rekognition:**  
Rekognition = general image analysis | Textract = structured document extraction

---

### 🎙️ Amazon Transcribe — Speech to Text
**What:** Convert audio/video speech into written text  
**Use cases:**
- Generate subtitles for videos
- Transcribe customer call recordings
- Voice input for applications
- Meeting notes automation

---

### 🌍 Amazon Translate — Language Translation
**What:** Translate text between 75+ languages  
**Use cases:**
- Translate website content
- Multilingual customer support
- Translate documents automatically

---

### 🗣️ Amazon Polly — Text to Speech
**What:** Convert text into lifelike spoken audio  
**Use cases:**
- Accessibility apps (read for visually impaired)
- Audiobook creation
- Voice alerts and notifications

---

### 💬 Amazon Lex — Build Chatbots
**What:** Build conversational chatbots using voice and text  
**Use cases:**
- Customer service chatbots
- Voice assistants
- Automated phone systems (IVR)

**Fun fact:** Same technology that powers Amazon Alexa!

---

### 🔍 Amazon Kendra — Intelligent Enterprise Search
**What:** AI-powered search for your company's internal documents  
**Use cases:**
- Search across SharePoint, S3, databases
- Smart FAQ for employees
- Find answers from large document libraries

---

### 🤖 Amazon Q — AI Business Assistant
**What:** Generative AI assistant for business tasks  
**Use cases:**
- Answer questions about your company data
- Summarise documents and reports
- Connect to business systems (Jira, Salesforce, S3)

---

### 🎯 Amazon Personalize — Recommendations Engine
**What:** Build personalised recommendation systems  
**Use cases:**
- "Customers who bought X also bought Y"
- Personalised content feeds
- Product recommendations (like Netflix, Amazon.com)

---

### 🔮 Amazon Forecast — Time Series Predictions
**What:** Predict future values using historical data  
**Use cases:**
- Predict inventory demand
- Forecast website traffic
- Predict sales revenue

---

## 🧠 Which Service to Use — Decision Guide

```
Need to analyse an IMAGE?          → Amazon Rekognition
Need to read a DOCUMENT/PDF?       → Amazon Textract
Need to understand TEXT meaning?   → Amazon Comprehend
Need to convert SPEECH to TEXT?    → Amazon Transcribe
Need to TRANSLATE languages?       → Amazon Translate
Need to convert TEXT to SPEECH?    → Amazon Polly
Need to build a CHATBOT?           → Amazon Lex
Need to SEARCH company documents?  → Amazon Kendra
Need a RECOMMENDATION engine?      → Amazon Personalize
Need to PREDICT future values?     → Amazon Forecast
Need to BUILD CUSTOM ML models?    → Amazon SageMaker
Need GENERATIVE AI (Foundation Models)? → Amazon Bedrock
```

## ✅ Week 3 & 4 Checklist
- [ ] Know all 12 AWS AI services and their use cases
- [ ] Can answer "which service should I use for X?"
- [ ] Understand SageMaker's key features
- [ ] Know difference between Textract vs Rekognition
- [ ] Know difference between Lex vs Comprehend

> 👉 **Next:** [../04-generative-ai/README.md](../04-generative-ai/README.md)
