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
datasets:
- Dwaraka/Training_Dataset_of_Project_Gutebberg_Gothic_Fiction
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# PROJECT_GUTENBERG_GOTHIC_FICTION_TEXT_GENERATION_gpt2

This model is a fine-tuned version of [gpt2](https://huggingface.co/gpt2) trained on the dataset of text from Project Guttenberg(https://www.gutenberg.org/), 
From which we picked the contents of 12 books related to Gothic Fiction which has 1051518 Words and 6002980 characters to perform the Text-Generation 
for the same Genre .

Can be used to generate the text of the vocabulary and writing style : GOTHIC FICTION.
## Model description

GPT-2 is a transfomer model originally trained on a very large corpus(billions of tokens) from Internet, by Open AI in a supervised learning pattern.
The Dataset consits huge amount of data types , which includes: news articles, books, scientific papers, web pages, and online forum discussions, which made the model to
experience diverse varieties of data. from which it learnt the patterns and relationships in language that are common across a wide range of contexts.

Apart from this, GPT-2 is trained in an unsupervised learning fashion for language modelling to perform the tasks like predicting the next/preceeding words in a text, which helps the model to learn further.

For the model : PROJECT_GUTENBERG_GOTHIC_FICTION_TEXT_GENERATION_gpt2, GPT-2 is re-trained on a large corpus which is collected from the Project Guttenberg Website : https://www.gutenberg.org/
The specific dataset consists of the text of 12 books which are related to Gothic Fiction. This customized GPT-2 model outputs the Gothic Fiction Texts on which it is trained on.

The books that are used for the dataset are:
The modern Prometheus, The liar of the white worm by bram Stoker, The Vampyre; a Tale, Nightmare Abbey; by Thomas Love Peacock', The History of Caliph Vathek by William Beckford
The Lock and Key Library :Classic Mystery and Detectives Stories: Old Time, Caleb Williams; Or,Things as they are by William Godwin
, The Private Memoirs and confessions of a justified sinner, Confessions of an English Opium Eater, The mysteries of udolpho, Wieland;Or,The Transformation: An American Tale by Charles Brocken Brown, The Castle of Otranto

## Intended uses & limitations
Uses:
  This model can be used for creative writing, content generation, language modeling, language learning,  
Limitations:
Since the model is trained on the text related to Gothic Fiction, it might not do well in generating the text from a different genre.

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