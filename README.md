# Welcome to the pipeline to fine-tune a basic LLaMA model through SFT and RLHF/RLAIF
- This repo includes a notebook file possible to run on Google Colab Pro on an A100 GPU containing both a supervised finetuning step (finetuning base model and reward model) and a proximal policy optimization step (optimizing finetuned model through proximal policy optimization with reward model)

- The notebook was written by Samuel Höglund and Josef Khedri for their bachelor's thesis on comparing RLHF and RLAIF
  - For more information about our work, head over to https://huggingface.co/KTH/psychology-alpaca

- The following code uses a forked GitHub repository originally created by user https://github.com/jackaduma
