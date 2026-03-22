# ⚖️ Week 6 — Responsible AI, Security & Governance

## 🎯 What You Will Learn
- Responsible AI principles
- AI bias, fairness, and transparency
- AWS tools for safe and secure AI
- Compliance and governance for AI systems

---

## 🤝 What is Responsible AI?

Responsible AI = Building and using AI in a way that is **fair, safe, transparent, and ethical**

**AWS 6 Pillars of Responsible AI:**
| Pillar | Meaning |
|--------|---------|
| **Fairness** | AI treats all people equally, no discrimination |
| **Explainability** | AI decisions can be understood and explained |
| **Privacy & Security** | User data is protected |
| **Safety** | AI won't cause harm |
| **Controllability** | Humans can override AI decisions |
| **Veracity & Robustness** | AI gives accurate, reliable answers |

---

## ⚠️ AI Bias & Fairness

**What is Bias?**  
When an AI model gives unfair or inaccurate results for certain groups of people

**Causes of Bias:**
- Training data that is not representative (e.g., only trained on male faces)
- Historical discrimination baked into data
- Poor feature selection

**Types of Bias:**
| Type | Example |
|------|---------|
| **Data Bias** | Hiring model trained mostly on male applicants → biased against women |
| **Algorithm Bias** | Model weights certain features too heavily |
| **Confirmation Bias** | Model reinforces existing stereotypes |

**AWS Tool:** Amazon SageMaker Clarify — detects bias in datasets and models

---

## 🔍 Explainability & Transparency

**Why it matters:** People should understand WHY an AI made a decision  
**Example:** A loan rejection AI must explain which factors caused rejection

**AWS Tool:** SageMaker Clarify also provides explainability reports

---

## 🛡️ AWS Security for AI

| AWS Service | How It Protects AI |
|-------------|-------------------|
| **IAM** | Control WHO can access AI models and data |
| **KMS** (Key Management Service) | Encrypt your AI training data and model artifacts |
| **CloudTrail** | Audit log of ALL AI API calls — who did what, when |
| **VPC** | Keep AI workloads in private network |
| **Macie** | Detect sensitive data (PII) in S3 used for training |
| **Bedrock Guardrails** | Add content filters to GenAI responses |

---

## 📋 AI Governance & Compliance

**What is AI Governance?**  
Rules and processes to ensure AI is used responsibly in an organisation

**Key Concepts:**
| Term | Meaning |
|------|---------|
| **Model Card** | Document describing a model's intended use, limitations, bias |
| **Data Lineage** | Track where training data came from |
| **Model Monitoring** | Watch for model drift and performance degradation |
| **Human in the Loop** | Always have humans review critical AI decisions |
| **Audit Trail** | Logs of all AI decisions for review |

---

## 🚨 AI Risks to Know for Exam

| Risk | Description |
|------|-------------|
| **Hallucination** | AI confidently gives wrong/made-up information |
| **Prompt Injection** | Malicious input tricks AI into doing unintended things |
| **Data Poisoning** | Attacker corrupts training data to manipulate model |
| **Model Inversion** | Attacker extracts training data from a model |
| **Bias Amplification** | AI makes existing human biases worse at scale |

---

## ✅ Week 6 Checklist
- [ ] Know AWS 6 Pillars of Responsible AI
- [ ] Understand what AI bias is and how to detect it
- [ ] Know SageMaker Clarify, IAM, CloudTrail, KMS roles
- [ ] Understand what Bedrock Guardrails does
- [ ] Know key AI risks: hallucination, prompt injection, data poisoning

> 👉 **Next:** [../06-exam-prep/README.md](../06-exam-prep/README.md)
