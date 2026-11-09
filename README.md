# Spam and Phishing Email Detection: Language Models, BERT Encoders, T5 and BART

Experiment notebooks for the paper *"Prompting, LoRA, or Full Fine Tuning? Benchmarking Language Models, BERT Encoders and Encoder-Decoder Models for Spam and Phishing Email Detection"* by Annas Wasim Malik, Rubab Javaid and Ali Saeed (University of Central Punjab, Lahore, Pakistan).

All 22 experiments are public Kaggle notebooks with full code, outputs and trained weights. Every notebook uses the same cleaned data, the same split and the same frozen test set of 6,575 emails (checked by a SHA-256 fingerprint).

Dataset: [Phishing Email Dataset](https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset) (Kaggle, CC BY-SA 4.0).

## Kaggle notebooks for all experiments

| Class | Model | Notebook |
|---|---|---|
| Pilot | Qwen2.5-0.5B-Instruct | https://www.kaggle.com/code/awasim/qwen2-5-0-5b-phishing-email-classifier-sft |
| Language models (LMs) | Llama-3.2-3B-Instruct | https://www.kaggle.com/code/awasim/phishing-llm-llama-3-2-3b-instruct |
| | Phi-3.5-mini-instruct | https://www.kaggle.com/code/awasim/phishing-llm-phi-3-5-mini-instruct |
| | Qwen2.5-3B-Instruct | https://www.kaggle.com/code/awasim/phishing-llm-qwen2-5-3b-instruct |
| | Gemma-2-2B-IT | https://www.kaggle.com/code/awasim/phishing-llm-gemma-2-2b-it |
| | Mistral-7B-Instruct-v0.3 | https://www.kaggle.com/code/awasim/phishing-llm-mistral-7b-instruct-v0-3 |
| | TinyLlama-1.1B-Chat | https://www.kaggle.com/code/awasim/phishing-llm-tinyllama-1-1b-chat |
| | SmolLM3-3B | https://www.kaggle.com/code/awasim/phishing-llm-smollm3-3b |
| BERT family | BERT-base-uncased | https://www.kaggle.com/code/awasim/phishing-bert-bert-base-uncased |
| | DistilBERT-base-uncased | https://www.kaggle.com/code/awasim/phishing-bert-distilbert-base-uncased |
| | RoBERTa-base | https://www.kaggle.com/code/awasim/phishing-bert-roberta-base |
| | DistilRoBERTa-base | https://www.kaggle.com/code/awasim/phishing-bert-distilroberta-base |
| | ALBERT-base-v2 | https://www.kaggle.com/code/awasim/phishing-bert-albert-base-v2 |
| | ELECTRA-base-discriminator | https://www.kaggle.com/code/awasim/phishing-bert-electra-base-discriminator |
| | DeBERTa-v3-base | https://www.kaggle.com/code/awasim/phishing-bert-deberta-v3-base |
| | SecureBERT | https://www.kaggle.com/code/awasim/phishing-bert-securebert |
| | ModernBERT-base | https://www.kaggle.com/code/awasim/phishing-bert-modernbert-base |
| T5 and BART (encoder-decoder) | T5-small | https://www.kaggle.com/code/awasim/phishing-seq2seq-t5-small |
| | T5-base | https://www.kaggle.com/code/awasim/phishing-seq2seq-t5-base |
| | T5-large | https://www.kaggle.com/code/awasim/phishing-seq2seq-t5-large |
| | BART-base | https://www.kaggle.com/code/awasim/phishing-seq2seq-bart-base |
| | BART-large | https://www.kaggle.com/code/awasim/phishing-seq2seq-bart-large |
