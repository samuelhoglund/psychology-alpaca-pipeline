# Welcome to the pipeline to fine-tune a basic LLaMA model through SFT and RLHF/RLAIF
- This repo includes a notebook file possible to run on Google Colab Pro on an A100 GPU containing both a supervised finetuning step (finetuning base model and reward model) and a proximal policy optimization step (optimizing finetuned model through proximal policy optimization with reward model)

- The notebook was written by Samuel Höglund and Josef Khedri for their bachelor's thesis on comparing RLHF and RLAIF
  - For more information about our work, head over to https://huggingface.co/KTH/psychology-alpaca
  - Read the paper [here](https://www.diva-portal.org/smash/record.jsf?dswid=3835&pid=diva2%3A1782683&c=2&searchType=SIMPLE&language=en&query=rlhf&af=%5B%5D&aq=%5B%5B%5D%5D&aq2=%5B%5B%5D%5D&aqe=%5B%5D&noOfRows=50&sortOrder=author_sort_asc&sortOrder2=title_sort_asc&onlyFullText=false&sf=undergraduate)!

- The following code uses a [forked GitHub repository](https://github.com/jkhedri/Alpaca-LoRA-RLHF-PyTorch) originally created by user https://github.com/jackaduma
