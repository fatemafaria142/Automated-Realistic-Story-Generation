# Automated Realistic Story Generation

This repository showcases the generation of realistic stories using the GPT-2 model and evaluates the generated stories using various metrics.

## Overview

This project utilizes the capabilities of GPT-2 and GPT-2 Medium, powerful language generation models from the Hugging Face Transformers library, to autonomously generate realistic stories. The primary goal is to craft captivating narratives that showcase realism, coherence, and natural language fluency.

## Dataset

The dataset used for this project is sourced from the [Atlas Storyteller Dataset](https://huggingface.co/datasets/AtlasUnified/atlas-storyteller?row=42) available on the Hugging Face Datasets Hub. This dataset contains a collection of stories suitable for training language models like GPT-2 and GPT-2 Medium.

## GPT-2 and GPT-2 Medium Model

The story generation process relies on both the GPT-2 model and the GPT-2 Medium model, available in the Hugging Face Transformers library. You can find the documentation for GPT-2 [here](https://huggingface.co/docs/transformers/model_doc/gpt2) and access the GPT-2 Medium model directly [here](https://huggingface.co/gpt2-medium). These models serve as the core for generating stories in this project. They have been fine-tuned on the provided dataset to facilitate the creation of realistic and engaging narratives.

## Evaluation Metrics

The following evaluation metrics have been calculated to assess the quality of the generated stories:
- Character Error Rate (CER)
- Word Error Rate (WER)
- Exact Match (EM)
- BLEU Score
- METEOR Score

These metrics help quantify the accuracy, fluency, and similarity of the generated stories compared to the reference or ground truth stories.

