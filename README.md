# Instruction Fine-Tuning OPT-350M

This repository contains an instruction fine-tuning pipeline for Facebook OPT-350M using Hugging Face Transformers, PEFT, and PyTorch.

The project demonstrates parameter-efficient fine-tuning techniques such as LoRA and QLoRA for adapting large language models to instruction-following tasks with lower GPU memory usage.

## Model

Base model used:

- facebook/opt-350ml

## Features

- Instruction fine-tuning for OPT-350M
- LoRA and QLoRA support
- 4-bit quantization with BitsAndBytes
- Hugging Face Trainer integration
- Dataset preprocessing and tokenization
- Training and evaluation pipeline
- Model saving and adapter loading
- GPU-efficient training workflow

## Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- PEFT
- BitsAndBytes
- Accelerate
- Datasets

## Dataset

This project uses the `CodeAlpaca-20k` dataset for instruction fine-tuning.

### Dataset Overview

CodeAlpaca-20k is a synthetic instruction-following dataset focused on programming and software development tasks.  
It contains approximately 20,000 prompt-response pairs designed to improve coding capabilities in language models.

### Dataset Features

- Programming-related instructions
- Code generation tasks
- Debugging examples
- Algorithm explanations
- Multiple coding concepts
- Instruction-response formatting

### Example Format

```json
{
  "instruction": "Write a Python function to reverse a string.",
  "input": "",
  "output": "def reverse_string(s):\n    return s[::-1]"
}
