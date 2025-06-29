
# Fine-Grained Evaluation of LLMs for Text Generation and Open-Ended QA

This project investigates the **fine-grained evaluation of open-source Large Language Models (LLMs)** with a focus on **text generation** and **open-ended question answering** tasks. Inspired by frameworks like **FLASK** and tools like **Prometheus**, this study proposes a **custom evaluation rubric** designed to align more closely with human judgment.

---

## 🧠 Abstract

Evaluating LLMs remains a challenging task due to the complex and subjective nature of language. This study explores whether a **FLASK-like fine-grained evaluation framework** can offer a more nuanced and human-aligned assessment of LLM outputs. Ten LLaMA-based open-source models were evaluated on:

- **Standard metrics**: BLEU, ROUGE, BERTScore
- **Custom fine-grained criteria**: Tailored specifically for text generation and open-ended QA

Correlation analysis revealed a **strong alignment** between our custom metric and BERTScore/ROUGE-L, suggesting its effectiveness.

---

## 📚 Keywords

`LLM` · `text-generation` · `open-ended question answering` · `fine-grained evaluation` · `Prometheus` · `FLASK`

---

## 🔍 Project Structure

```

├── data/                # Evaluation datasets (custom instructions)
├── models/              # Config files and model download instructions
├── evaluations/
│   ├── standard/        # BLEU, ROUGE, BERTScore results
│   └── custom/          # Prometheus-based fine-grained results
├── prompts/             # Standardized prompt formats per model
├── analysis/            # Correlation analysis and visualizations
├── report/              # Final report and appendix
└── README.md

```

---

## 🧪 Evaluation Overview

### ✅ Standard Metrics
- **BLEU**
- **ROUGE-L**
- **BERTScore (Precision, Recall, F1)**

### 🌟 Custom Fine-Grained Criteria (via Prometheus)
Evaluated across dimensions like:
- Relevance
- Clarity & Coherence
- Completeness
- Accuracy
- Logical Soundness
- Creativity
- Engagement
- Empathy
- Efficiency

> Each response is scored from **1 (poor)** to **5 (excellent)** based on rubrics derived from human communication norms.

---

## 📊 Key Findings

| Metric      | Correlation with Prometheus |
|-------------|-----------------------------|
| BLEU        | Weak or Negative (-0.76)    |
| BERTScore   | Strong Positive (~0.81)     |
| ROUGE-L     | Strong Positive (~0.81)     |

- Models like **WizardLM-13B-V1.1** scored highest overall.
- Custom metrics **align more with semantic and contextual quality** than lexical similarity.

---

## 🔧 Tools & Models

- **LLMs**: 10 open-source LLaMA-based models (≤13B parameters)
- **Evaluation Engine**: [Prometheus](https://github.com/kaistAI/Prometheus)
- **Dataset**: Custom-built, inspired by Alpaca, Ultrachat, No Robots
- **Hardware**: NVIDIA A800 40GB GPU

---

## 🧠 Future Work

- Benchmarking against **FLASK** and **Human Evaluation**
- Expand to more instruction types (summarization, critique, etc.)
- Use **state-of-the-art closed models** like ChatGPT for comparison

---

## 📄 Citation

If you use this work or build upon it, please cite:
```

@misc{finegrained-llm-eval,
title={Fine-Grained Evaluation of LLMs},
author={Your Name},
year={2025},
url={[https://github.com/yourusername/llm-finegrained-eval}](https://github.com/yourusername/llm-finegrained-eval})
}

```

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

For questions or collaboration, feel free to reach out at `sarangchouguley284@example.com`.

```

---
