# PEFT LoRA Fine-Tuning: DistilBERT Sentiment Analysis (IMDB)

This project applies parameter-efficient fine-tuning (LoRA) to DistilBERT for binary sentiment classification on the IMDB dataset using Hugging Face Transformers and PEFT.
Parameter-efficient fine-tuning (LoRA) applied to DistilBERT for IMDB sentiment classification using Hugging Face Transformers and PEFT. Includes baseline vs fine-tuned evaluation comparison.
## Model
- Base: distilbert-base-uncased
- Task: Binary sentiment classification
- PEFT Method: LoRA
- Target modules: q_lin, v_lin

## Dataset
- IMDB (subset used for faster training)

## Evaluation
- Accuracy
- Weighted F1-score
- Comparison between:
  - Baseline model
  - Fine-tuned model
  - Reloaded PEFT adapter

## Files
- LightweightFineTuning.ipynb — training and evaluation workflow
- peft_adapter.zip — saved LoRA adapter weights
