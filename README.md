# Startup Idea Generator

An AI-driven startup idea generator leveraging Transformers and Gradio.  
Powered by the LaMini-Flan-T5 (783M) model, it crafts detailed startup pitches based on a domain keyword input.

## 🚀 Key Features

- Enter any domain or industry keyword such as AgriTech, FinTech, or EdTech.
- Automatically produces a structured pitch including:  
  - Concise Business Idea (2–3 sentences)  
  - Clear Problem Statement highlighting industry challenges  
  - Innovative Solution outlining the startup’s approach
- User-friendly web interface built with Gradio.
- Option to share your project via a public Gradio link.

## 📦 Setup

To get started, install the required packages:
```bash
pip install transformers gradio torch accelerate
