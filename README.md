# How to Fine Tune Llama 3 for Better Instruction Following

## INDEX

![alt text](image.png)

---

## COMMANDS

UNSLOTH GitHub LINK: <https://github.com/unslothai/unsloth>

```
conda create --name finetune_llama_unsloth python=3.10 -y
conda activate finetune_llama_unsloth
conda install pytorch-cuda=12.1 pytorch cudatoolkit xformers -c pytorch -c nvidia -c xformers
pip install "unsloth[colab-new] @ git+https://github.com/unslothai/unsloth.git"
pip install --no-deps trl peft accelerate bitsandbytes
pip install wandb
wandb login
export HF_TOKEN=xxxxxxxxxxxxx

conda install -n finetune_llama_unsloth ipykernel --update-deps --force-reinstall
```

---
