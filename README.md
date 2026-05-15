# Instruction Fine-Tuning OPT-350M

This repository contains an instruction fine-tuning pipeline for Facebook OPT-350M using Hugging Face Transformers, PEFT, and PyTorch.

The project demonstrates parameter-efficient fine-tuning techniques such as LoRA and QLoRA for adapting large language models to instruction-following tasks with lower GPU memory usage.

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

## Model

Base model used:

- facebook/opt-350ml
