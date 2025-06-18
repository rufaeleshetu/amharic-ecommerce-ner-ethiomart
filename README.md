# Amharic E-commerce NER for EthioMart

This project fine-tunes Amharic NER models on Telegram-based e-commerce data to extract products, prices, and locations. The goal is to help EthioMart identify top vendors for micro-lending.

## Tasks
- Data scraping from Telegram
- Amharic NER labeling (CoNLL format)
- Model fine-tuning (XLM-Roberta, AfroXLMR, etc.)
- Model interpretability (SHAP, LIME)
- Vendor scoring system for FinTech lending

## Folder Structure
- `data/` - raw and cleaned Telegram data
- `notebooks/` - notebooks for scraping, training, and evaluation
- `models/` - saved fine-tuned models
- `utils/` - Python helpers (e.g., tokenizer, cleaning)
- `vendor_scorecard/` - scripts to score vendors