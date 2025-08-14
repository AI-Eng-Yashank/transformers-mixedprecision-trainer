# Seq2Seq Model Fine-Tuning

This project demonstrates fine-tuning a Seq2Seq model using Hugging Face Transformers and PyTorch.  
It uses a dataset from the Hugging Face Hub and includes:
- Tokenization
- Mixed precision training for efficiency
- Checkpoint saving with automatic cleanup
- Resume-from-checkpoint support

## 📌 Features
- Load dataset from Hugging Face
- Tokenize input-output pairs for sequence-to-sequence training
- Fine-tune a model on GPU (if available)
- Save and load checkpoints easily
- Train with mixed precision for faster performance

## 📂 Dataset
- **Name:** [chibbss/fitness-chat-prompt-completion-dataset](https://huggingface.co/datasets/chibbss/fitness-chat-prompt-completion-dataset)
- Format: `instruction` → `output`

## 🛠 Installation
```bash
git clone https://github.com/AI-Eng-Yashank/transformers-mixedprecision-trainer.git
cd seq2seq-finetune
pip install -r requirements.txt
