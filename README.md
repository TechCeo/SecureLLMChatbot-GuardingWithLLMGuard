
# SecureLLMChatbot-GuardingWithLLMGuard

**Author**: Yusuf Adamu  
**Project**: Prompt Injection Detection in TinyLLaMA Chatbots using LLM Guard  
**Environment**: Google Colab | Python | Transformers | Hugging Face | Scikit-learn

---

## 🚀 Overview

This project demonstrates the integration of [LLM Guard](https://github.com/protectai/llm-guard) with the TinyLLaMA-1.1B-Chat model to detect and defend against prompt injection attacks. The system combines input and output scanning to ensure safe and reliable chatbot responses, evaluated using adversarial and safe prompt datasets.

---

## 🔒 Key Features

- ✅ Input sanitization with `PromptInjection` and `BanTopics` scanners
- ✅ Unsafe prompt blocking with risk score explanation
- ✅ End-to-end pipeline: scan → sanitize → respond or reject
- ✅ Evaluation on [Safe-Gaurd Prompt Injection Dataset](https://huggingface.co/datasets/xTRam1/safe-guard-prompt-injection)
- ✅ Metrics: Accuracy, F1, ROC-AUC, Confusion Matrix

---

## 📊 Results Summary

| Metric       | Value      |
|--------------|------------|
| Accuracy     | 94.6%      |
| Precision    | 99.8%      |
| Recall       | 82.8%      |
| F1 Score     | 90.5%      |
| ROC AUC      | ~0.95      |

---

## 📁 Project Structure

- `LLMGAURD_Project.ipynb` – Main implementation in Colab
- `README.md` – Project overview (this file)

---

## 📬 Contact

For questions or collaboration: **yusufadamu.research@gmail.com**
