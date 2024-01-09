# Automated Realistic Story Generation

This repository showcases the generation of realistic stories using the GPT-2 model and evaluates the generated stories using various metrics.

## Overview

This project focuses on utilizing GPT-2, a powerful language generation model from the Hugging Face Transformers library, to automatically generate realistic stories. The aim is to create compelling narratives that exhibit realism, coherence, and natural language fluency.

## Dataset

The dataset used for this project is sourced from the [Atlas Storyteller Dataset](https://huggingface.co/datasets/AtlasUnified/atlas-storyteller?row=42) available on the Hugging Face Datasets Hub. This dataset contains a collection of stories suitable for training language models like GPT-2.

## GPT-2 Model

The GPT-2 model from the Hugging Face Transformers library ([documentation here](https://huggingface.co/docs/transformers/model_doc/gpt2)) serves as the core for generating stories. This model has been fine-tuned on the provided dataset to facilitate the creation of realistic and engaging narratives.

## Evaluation Metrics

The following evaluation metrics have been calculated to assess the quality of the generated stories:
- Character Error Rate (CER)
- Word Error Rate (WER)
- Exact Match (EM)
- BLEU Score
- METEOR Score

These metrics help quantify the accuracy, fluency, and similarity of the generated stories compared to the reference or ground truth stories.

