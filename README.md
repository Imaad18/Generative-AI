<h1 align="center">Introduction to Generative AI</h1>

<p align="center">
  <a href="https://colab.research.google.com/drive/1EYz-NZXBxlkaG2wHa1BlmuADM3R6Rmvy#scrollTo=bARz1ZhrfnFn">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
  <img src="https://img.shields.io/badge/Python-3.9%2B-blue?logo=python" alt="Python 3.9+"/>
  <img src="https://img.shields.io/badge/Google%20Cloud-GenAI-orange?logo=googlecloud" alt="Google Cloud"/>
  <img src="https://img.shields.io/badge/License-MIT-green" alt="MIT License"/>
  <img src="https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter" alt="Jupyter"/>
</p>

<p align="center">
  Complete course notes and hands-on code examples based on Google Cloud's <strong>Introduction to Generative AI</strong> learning path.<br/>
  Written by <strong>Imaad Mahmood</strong> — BS AI Student | AI & GenAI Explorer
</p>

---

## Table of Contents

- [Overview](#overview)
- [Topics Covered](#topics-covered)
- [Getting Started](#getting-started)
  - [Option 1: Google Colab (Recommended)](#option-1-google-colab-recommended)
  - [Option 2: Local Setup](#option-2-local-setup)
- [Hands-on Code Examples](#hands-on-code-examples)
- [Learning Path](#learning-path)
- [Resources](#resources)
- [Contributing](#contributing)
- [Author](#author)

---

## Overview

This repository contains structured course notes, visual aids, and runnable code examples covering the fundamentals of Generative AI — including how LLMs work, responsible AI practices, and how to use Google's GenAI tools in practice.

Whether you're a student, developer, or self-learner, this resource gives you both the **theory** and the **hands-on experience** to start building with GenAI.

---

## Topics Covered

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | **Introduction to Generative AI** | GenAI vs Traditional AI, Discriminative vs Generative models, real-world applications |
| 2 | **Large Language Models (LLMs)** | GPT-4 / PaLM 2, Transformer architecture, tokenization, pretraining vs fine-tuning |
| 3 | **Responsible AI** | Bias, hallucinations, privacy, Google's 7 AI Principles |
| 4 | **Google GenAI Tools** | Vertex AI, PaLM 2 API, Imagen, MakerSuite, prompt design |
| 5 | **Hands-on Code** | API setup, text generation, prompt engineering, parameters & temperature |

---

## Getting Started

### Option 1: Google Colab (Recommended)

No setup required. Click the badge to open directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EYz-NZXBxlkaG2wHa1BlmuADM3R6Rmvy#scrollTo=bARz1ZhrfnFn)

### Option 2: Local Setup

```bash
# 1. Clone the repository
git clone https://github.com/Imaad18/Generative-AI.git
cd Generative-AI

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook Generative_AI.ipynb
```

> **API Key:** To run the hands-on code cells, you'll need a Google AI Studio API key.
> Get one free at [aistudio.google.com](https://aistudio.google.com).

---

## Hands-on Code Examples

The notebook includes runnable code cells for:

- **Environment Setup** — Install `google-generativeai` and configure your API key
- **Basic Text Generation** — Generate content using Gemini Pro
- **Prompt Engineering** — Zero-shot, one-shot, and few-shot prompting with live examples
- **Parameter Tuning** — Explore how `temperature`, `top_p`, and `max_tokens` affect output
- **Chat / Multi-turn Conversations** — Build a stateful conversational AI session

---

## Learning Path

Follow this order for the best learning experience:

```
1. Read the course notes (slides in notebook)
      |
      v
2. Understand the concepts (Theory sections)
      |
      v
3. Run the hands-on code cells
      |
      v
4. Experiment: modify prompts, change parameters
      |
      v
5. Explore Google AI Studio & Vertex AI
```

---

## Resources

| Resource | Link |
|----------|------|
| Google AI Studio (free API key) | [aistudio.google.com](https://aistudio.google.com) |
| Google Cloud Skills Boost | [cloudskillsboost.google.com](https://cloudskillsboost.google.com) |
| Vertex AI Documentation | [cloud.google.com/vertex-ai](https://cloud.google.com/vertex-ai) |
| Google Generative AI SDK | [github.com/google/generative-ai-python](https://github.com/google/generative-ai-python) |
| Gemini API Docs | [ai.google.dev/docs](https://ai.google.dev/docs) |

---

## Contributing

Contributions, improvements, and corrections are welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-improvement`
3. Commit your changes: `git commit -m "Add: your improvement description"`
4. Push and open a Pull Request

---

## Author

**Imaad Mahmood**
BS AI Student | AI & GenAI Explorer

Feel free to explore my [GitHub](https://github.com/Imaad18) for more AI content.

---

> If you found this helpful, give the repo a star and share it with your peers!

---

*Based on Google Cloud's "Introduction to Generative AI" learning path. Licensed under [MIT](./LICENSE).*
