# Gen AI Query Pipeline

Build a generative AI pipeline that automatically composes engaging event descriptions for ticket listings using an API (e.g., Google Gemini, OpenAI).

---

## Environment Setup

Install and import the required libraries:

```bash
pip install openai requests
```

```python
import os
import openai
import requests
# Add any additional imports here
```

---

## Prompt Engineering

- Define reusable templates with placeholders (e.g., artist, date, venue).
- Experiment with parameters such as temperature, max tokens, and system vs. user prompts.

---

## API Integration

- Configure API keys (e.g., via `OPENAI_API_KEY` environment variable) and implement rate limiting.
- Create wrapper functions for API calls, including error handling and retry logic.

---

## Post-Processing

- Clean up generated text: remove unwanted characters and enforce length constraints.
- Apply brand guidelines and SEO optimizations (e.g., keywords, style consistency).

---

## Evaluation

- Compare AI-generated descriptions against manual samples.
- Compute readability metrics (e.g., Flesch–Kincaid score) to assess quality.

---

## Usage

1. Ensure your API key is set:
   ```bash
   export OPENAI_API_KEY="your_key_here"
   ```
2. Launch Jupyter and run the notebook cells in order.
3. Review and refine prompt templates and parameters as needed.

---
