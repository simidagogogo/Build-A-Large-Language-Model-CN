# Bonus Material

Several folders contain optional materials as a bonus for interested readers:



## Setup

- [Python Setup Tips](https://github.com/rasbt/LLMs-from-scratch/blob/main/setup/01_optional-python-setup-preferences)
- [Installing Python Packages and Libraries Used In This Book](https://github.com/rasbt/LLMs-from-scratch/blob/main/setup/02_installing-python-libraries)
- [Docker Environment Setup Guide](https://github.com/rasbt/LLMs-from-scratch/blob/main/setup/03_optional-docker-environment)



## Chapter 2: Working with text data

- [Byte Pair Encoding (BPE) Tokenizer From Scratch](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch02/05_bpe-from-scratch/bpe-from-scratch.ipynb)
- [Comparing Various Byte Pair Encoding (BPE) Implementations](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch02/02_bonus_bytepair-encoder)
- [Understanding the Difference Between Embedding Layers and Linear Layers](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch02/03_bonus_embedding-vs-matmul)
- [Dataloader Intuition with Simple Numbers](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch02/04_bonus_dataloader-intuition)



## Chapter 3: Coding attention mechanisms

- [Comparing Efficient Multi-Head Attention Implementations](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch03/02_bonus_efficient-multihead-attention/mha-implementations.ipynb)
- [Understanding PyTorch Buffers](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch03/03_understanding-buffers/understanding-buffers.ipynb)



## Chapter 4: Implementing a GPT model from scratch

- [FLOPS Analysis](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch04/02_performance-analysis/flops-analysis.ipynb)
- [KV Cache](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch04/03_kv-cache)



## Chapter 5: Pretraining on unlabeled data:

- [Alternative Weight Loading Methods](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/02_alternative_weight_loading)
- [Pretraining GPT on the Project Gutenberg Dataset](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/03_bonus_pretraining_on_gutenberg)
- [Adding Bells and Whistles to the Training Loop](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/04_learning_rate_schedulers)
- [Optimizing Hyperparameters for Pretraining](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/05_bonus_hparam_tuning)
- [Building a User Interface to Interact With the Pretrained LLM](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/06_user_interface)
- [Converting GPT to Llama](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/07_gpt_to_llama)
- [Llama 3.2 From Scratch](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/07_gpt_to_llama/standalone-llama32.ipynb)
- [Qwen3 Dense and Mixture-of-Experts (MoE) From Scratch](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/11_qwen3)
- [Gemma 3 From Scratch](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/12_gemma3)
- [Memory-efficient Model Weight Loading](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/08_memory_efficient_weight_loading/memory-efficient-state-dict.ipynb)
- [Extending the Tiktoken BPE Tokenizer with New Tokens](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/09_extending-tokenizers/extend-tiktoken.ipynb)
- [PyTorch Performance Tips for Faster LLM Training](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/10_llm-training-speed)



## Chapter 6: Finetuning for classification

- [Additional experiments finetuning different layers and using larger models](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch06/02_bonus_additional-experiments)
- [Finetuning different models on 50k IMDb movie review dataset](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch06/03_bonus_imdb-classification)
- [Building a User Interface to Interact With the GPT-based Spam Classifier](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch06/04_user_interface)



## **Chapter 7: Finetuning to follow instructions**

  - [Dataset Utilities for Finding Near Duplicates and Creating Passive Voice Entries](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch07/02_dataset-utilities)
  - [Evaluating Instruction Responses Using the OpenAI API and Ollama](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch07/03_model-evaluation)
  - [Generating a Dataset for Instruction Finetuning](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch07/05_dataset-generation/llama3-ollama.ipynb)
  - [Improving a Dataset for Instruction Finetuning](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch07/05_dataset-generation/reflection-gpt4.ipynb)
  - [Generating a Preference Dataset with Llama 3.1 70B and Ollama](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch07/04_preference-tuning-with-dpo/create-preference-data-ollama.ipynb)
  - [Direct Preference Optimization (DPO) for LLM Alignment](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch07/04_preference-tuning-with-dpo/dpo-from-scratch.ipynb)
  - [Building a User Interface to Interact With the Instruction Finetuned GPT Model](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch07/06_user_interface)