---
license: mit
tags:
- generated_from_trainer
model-index:
- name: PROJECT_GUTENBERG_GOTHIC_FICTION_TEXT_GENERATION_gpt2
  results: []
language:
- en
library_name: transformers
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# PROJECT_GUTENBERG_GOTHIC_FICTION_TEXT_GENERATION_gpt2

This model is a fine-tuned version of [gpt2](https://huggingface.co/gpt2) trained on the dataset of text from Project Guttenberg(https://www.gutenberg.org/), 
From which we picked the contents of 12 books related to Gothic Fiction which has 1051518 Words and 6002980 characters to perform the Text-Generation 
for the same Genre .

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 3

### Training results



### Framework versions

- Transformers 4.26.1
- Pytorch 1.13.1+cu116
- Datasets 2.10.0
- Tokenizers 0.13.2