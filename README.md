# LoRA Fine-Tuning for gpt2-medium

## Overview

A concise implementation of Low-Rank Adaptation (LoRA) for fine-tuning gpt2-medium, developed independently for the Block-Seminar on Deep Learning at the University of Freiburg.

## Setup

- Mount Google Drive: `from google.colab import drive; drive.mount('/content/drive')`
- Install `transformers`, `datasets`

## Model and Dataset

- Model: `gpt2-medium`
- Dataset: Needs to be located in Google Drive. Can be any type of dataset that works with gpt2, in this case it was a modified version of https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset?rvi=1

## Features

- Fine-tuning gpt2-medium with full parameter updates and LoRA.
- Custom LoRA implementation for GPT-2's attention mechanism - inspired by https://github.com/tsmatz/finetune_llm_with_lora
- Utility functions for model evaluation and text generation.

## Limitations

Demonstrates resource constraints in full model fine-tuning on platforms like Google Colab's free tier.

## Usage

- Adjust `path_to_file` for dataset location.
- Run fine-tuning and evaluation functions as per requirement.
