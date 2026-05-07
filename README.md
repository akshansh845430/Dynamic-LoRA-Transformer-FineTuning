# Dynamic-LoRA-Transformer-FineTuning
Comparative analysis of Full Fine-Tuning, LoRA, and Dynamic LoRA for parameter-efficient transformer adaptation.
# Dynamic LoRA for Parameter-Efficient Fine-Tuning

This project presents a comparative analysis of:

- Full Fine-Tuning
- LoRA (Low-Rank Adaptation)
- Dynamic LoRA

for transformer-based NLP models using BERT on the IMDB sentiment classification dataset.

## Features

- Parameter-efficient transformer adaptation
- Dynamic importance-based LoRA pruning
- Comparative evaluation using:
  - Accuracy
  - F1-score
  - Training time
  - Trainable parameters

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- Google Colab

## Results

| Method | Accuracy | F1 Score | Trainable Params |
|--------|----------|----------|------------------|
| Full Fine-Tuning | 88.8% | 88.64% | 109M |
| LoRA | 84.3% | 84.68% | 296K |

## Future Scope

- Adaptive SVD-based rank allocation
- Integration with quantization
- Deployment on edge devices
- Extension to LLMs such as LLaMA and GPT

## Author

Akshansh Kumar Tiwari 
