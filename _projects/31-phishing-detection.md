---
layout: page
title: "Phishing Website Detection"
description: "Classifies web pages as phishing or legitimate from their HTML."
importance: 31
category: ai and data
related_publications: false
---

**Code:** [GitHub](https://github.com/mishraShilpa-28/Detecting-Phishing-Websites-using-ML) · **Tech:** Python, scikit-learn, Hugging Face tokenizers, Docker

## The problem

Phishing pages copy real sites closely. Their HTML still leaves patterns a model can learn.

## What it does

- **Byte-pair-encoding tokenizer** trained on page HTML, with TF-IDF features.
- **Random forest classifier** trained on labelled phishing and legitimate pages.
- **Test any URL** with a trained or pre-trained model; Docker setup included.

## What I learned

- Tokenising unusual text such as HTML, and why subword tokenizers help.
- Evaluating a security classifier: false negatives are costly.
