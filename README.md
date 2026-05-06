
# From Sentiment to Emotions: Investigating Investor Emotions in Energy Stock Returns through Theory-Grounded LLMs

Undergraduate dissertation investigating how investor emotions extracted from ESG news relate to energy stock returns.

---

## Overview
This interdisciplinary study investigates the area of behavioural finance and affective computing. We did prompt engineering by applying psychological emotion theory, specifically Ekman's basic emotion and APA dictionary to embed emotion definitions into LLM prompts, simulating the model to infer the emotion an investor would experience. We then benchmarked the LLM-generated emotion score with FinBERT and DistilRoBERTa, and examined their relationships with oil, natural gas and clean energy returns.

| Method | Type |
|---|---|
| Theory-Grounded LLM | Zero-shot prompt |
| DistilRoBERTa | Fine-tuned classifier |
| FinBERT | Sentiment baseline |

---

## Data

- **News:** ESG articles from ProQuest (2016–2026)
- **Returns:** S&P Global Clean Energy Transition Index, S&P GSCI Natural Gas, S&P Global Oil Index
