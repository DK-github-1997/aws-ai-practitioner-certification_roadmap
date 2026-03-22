# 🤖 Week 2 — AI / ML Core Concepts

## 🎯 What You Will Learn This Week
- Difference between AI, ML, Deep Learning
- Types of Machine Learning
- How a ML model is trained
- Important ML terms for the exam

## 📖 Topics

### 1. AI vs ML vs Deep Learning

```
Artificial Intelligence (AI)
  └── Machine Learning (ML)
        └── Deep Learning (DL)
              └── Generative AI (GenAI)
```

| Term | Simple Meaning | Example |
|------|---------------|---------|
| AI | Machines doing smart tasks | Chess-playing computer |
| ML | Machines learning from data | Spam email filter |
| Deep Learning | ML using neural networks | Face recognition |
| Generative AI | AI that CREATES new content | ChatGPT, Claude, Stable Diffusion |

### 2. Types of Machine Learning

| Type | How It Learns | Example |
|------|--------------|---------|
| **Supervised** | Learns from labelled data (input + answer) | Email = Spam or Not Spam |
| **Unsupervised** | Finds patterns in unlabelled data | Customer grouping (clustering) |
| **Reinforcement** | Learns by trial and reward/punishment | Robot learning to walk |

### 3. The ML Pipeline (Step by Step)

```
Step 1: Collect Data      → Gather raw data (CSV, images, text)
Step 2: Prepare Data      → Clean, label, split (train/test)
Step 3: Choose Algorithm  → Pick the right ML model type
Step 4: Train Model       → Feed data, model learns patterns
Step 5: Evaluate Model    → Check accuracy, precision, recall
Step 6: Deploy Model      → Put model into production
Step 7: Monitor           → Watch for drift, retrain if needed
```

### 4. Key ML Terms (Exam Favourites!)

| Term | Meaning |
|------|---------|
| **Training Data** | Data used to teach the model |
| **Test Data** | Data used to check model accuracy |
| **Overfitting** | Model memorises training data, fails on new data |
| **Underfitting** | Model too simple, misses patterns |
| **Bias** | Model is unfair or skewed toward certain groups |
| **Variance** | Model too sensitive to small changes in data |
| **Accuracy** | % of correct predictions |
| **Precision** | Of all positives predicted, how many were actually positive |
| **Recall** | Of all actual positives, how many did the model find |
| **F1 Score** | Balance between Precision and Recall |
| **Inference** | Using a trained model to make predictions |
| **Feature** | An input variable used to make predictions |
| **Label** | The output/answer the model is trying to predict |

### 5. Neural Networks (Simple Explanation)
Think of a neural network like a human brain:
- **Input Layer** → receives data (like your eyes seeing)
- **Hidden Layers** → process and find patterns (like your brain thinking)
- **Output Layer** → gives the prediction (like you speaking the answer)

## ✅ Week 2 Checklist
- [ ] Can explain AI vs ML vs Deep Learning in simple words
- [ ] Know Supervised vs Unsupervised vs Reinforcement learning
- [ ] Understand the 7-step ML pipeline
- [ ] Know what overfitting, bias, precision, recall mean
- [ ] Watch: "Machine Learning for Beginners" on YouTube (FreeCodeCamp)

## 🔗 Resources
- [AWS ML Terminology Guide](https://docs.aws.amazon.com/sagemaker/latest/dg/how-it-works-mlconcepts.html)
- [Google ML Crash Course (Free)](https://developers.google.com/machine-learning/crash-course)

> 👉 **Next:** [../03-aws-ai-services/README.md](../03-aws-ai-services/README.md)
