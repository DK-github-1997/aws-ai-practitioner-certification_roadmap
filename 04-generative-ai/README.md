# ✨ Week 5 — Generative AI & Amazon Bedrock

## 🎯 What You Will Learn
- What Generative AI really is (in simple words)
- Foundation Models and Large Language Models (LLMs)
- Amazon Bedrock — what it is and how to use it
- Prompt engineering basics
- RAG (Retrieval Augmented Generation)

---

## 🤖 What is Generative AI?

Generative AI = AI that **creates new content** (text, images, code, audio, video)

| Traditional AI | Generative AI |
|----------------|---------------|
| Classifies existing data | Creates brand new content |
| "Is this email spam?" | "Write me an email" |
| "Recognise this face" | "Generate a face image" |
| Answer = Yes/No/Category | Answer = New text, image, code |

---

## 🧠 Foundation Models (FMs)

**What:** Large AI models trained on HUGE amounts of data  
**Key feature:** One model can do MANY different tasks  
**Examples:** GPT-4, Claude, Llama, Stable Diffusion

| Term | Simple Meaning |
|------|---------------|
| **LLM** (Large Language Model) | FM specialised in text |
| **Parameters** | The "knowledge" stored in a model (billions of numbers) |
| **Token** | A chunk of text (word or part of word) — models process tokens |
| **Context Window** | Maximum text the model can process at one time |
| **Hallucination** | When model confidently gives wrong/made-up answers |

---

## 🛏️ Amazon Bedrock — AWS GenAI Platform

**What is it?**  
Amazon Bedrock = Fully managed service to ACCESS and USE foundation models from AWS and other AI companies — without managing any infrastructure.

**Why use Bedrock?**
- No need to build your own LLM — too expensive!
- Choose from multiple top AI models in ONE place
- Fully serverless — no servers to manage
- Private & secure — your data is NOT used to train models

**Models available in Bedrock:**
| Provider | Model | Best For |
|----------|-------|---------|
| Amazon | Amazon Titan | Text, embeddings |
| Anthropic | Claude | Complex reasoning, long text |
| Meta | Llama | Open-source tasks |
| Mistral AI | Mistral | Fast text generation |
| Stability AI | Stable Diffusion | Image generation |
| Cohere | Command | Enterprise text tasks |

**Key Bedrock Features:**
| Feature | What It Does |
|---------|-------------|
| **Model Playground** | Test models interactively |
| **Fine-tuning** | Customise a model on your own data |
| **Knowledge Bases** | Connect your documents for RAG |
| **Agents** | Build AI that takes actions automatically |
| **Guardrails** | Add safety filters to AI responses |

---

## 💬 Prompt Engineering

**What:** The skill of writing good instructions to get the best AI output  
**Why it matters:** Same model gives very different outputs based on how you ask!

### Prompting Techniques:

| Technique | What It Means | Example |
|-----------|--------------|---------|
| **Zero-shot** | No examples given | "Summarise this text: ..." |
| **One-shot** | One example given | "Here is an example... Now do the same for: ..." |
| **Few-shot** | 2–5 examples given | Best for complex or specific formats |
| **Chain of Thought** | Ask model to "think step by step" | "Solve this step by step: ..." |
| **System Prompt** | Set context/role for the AI | "You are a helpful SQL expert..." |

### Prompt Best Practices:
- Be **specific and clear** — vague prompts = vague answers
- Give **context** — who you are, what you want
- Specify **format** — "Respond in bullet points"
- Use **examples** for complex tasks
- Set **constraints** — "In under 100 words"

---

## 🔍 RAG — Retrieval Augmented Generation

**Problem:** LLMs have a knowledge cutoff date — they don't know your company's data  
**Solution:** RAG = Connect the LLM to your REAL, current data at query time

**How RAG Works:**
```
User asks question
      ↓
Search your documents/database (Retrieval)
      ↓
Send relevant documents + question to LLM
      ↓
LLM generates answer based on YOUR real data (Augmented Generation)
      ↓
User gets accurate, up-to-date answer
```

**AWS RAG tool:** Amazon Bedrock Knowledge Bases

---

## ✅ Week 5 Checklist
- [ ] Can explain Generative AI vs traditional AI
- [ ] Know what Foundation Models and LLMs are
- [ ] Understand what Amazon Bedrock is and why it exists
- [ ] Know the models available in Bedrock (Claude, Titan, Llama, etc.)
- [ ] Understand prompt engineering techniques
- [ ] Can explain RAG in simple words

> 👉 **Next:** [../05-responsible-ai/README.md](../05-responsible-ai/README.md)
