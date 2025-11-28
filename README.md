# Gemma3-Unsloth
This repository contains code for fine-tuning the Gemma-3 model using Unsloth and GRPO (Guided Reinforcement Policy Optimization) for math reasoning tasks on the GSM8K dataset. The project leverages advanced techniques such as LoRA PEFT (Parameter-Efficient Fine-Tuning) and 4-bit quantization to optimize training efficiency on CUDA-enabled GPUs.

## Key Features
- **Model**: Gemma-3-1b-it (instruction-tuned version).
- **Dataset**: GSM8K (madrylab/gsm8k-platinum).
- **Training Frameworks**: Hugging Face Transformers, TRL (GRPOTrainer), PyTorch.
- **Optimization Techniques**: LoRA PEFT, mixed precision, gradient accumulation.

## Repository Links
- [Gemma-3 tokenizer (LoRA Adapters)](https://huggingface.co/RomaizDabeer/gemma-3)

- [Gemma-3 LoRA Adapters](https://huggingface.co/RomaizDabeer/gemma-3-1b-finetuned-unsloth)

- [Gemma-3-1b 16-bit finetuned model](https://huggingface.co/RomaizDabeer/gemma-3-finetune-finetuned-unsloth)

- [GSM8K Dataset](https://huggingface.co/datasets/madrylab/gsm8k-platinums)


## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Romaiz/Gemma3-Unsloth.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook `Notebook.ipynb` to start fine-tuning.

## License
This project is licensed under the MIT License.