# pythia-70m-fine-tuning
## Overview
This repository shows the impact of fine tunning a small model on a medical dataset to understand the possible trade-offs of using a small model in terms of precision and computational requirements.

## The model

The model used is part of the *Pythia Scaling Suite* that is a collection of models. In this case the smallest one (70M) was used to have it trained quickly.

### Model Details

**Developed by:** EleutherAI

**Model type:** Transformer-based Language Model

**Language:** English

**Learn more:** Pythia's GitHub repository for training procedure, config files, and details on how to use. See paper for more evals and implementation details.

**Library:** GPT-NeoX

**License:** Apache 2.0

**Contact:** to ask questions about this model, join the EleutherAI Discord, and post them in #release-discussion. Please read the existing Pythia documentation before asking about it in the EleutherAI Discord. For general correspondence: contact@eleuther. ai.

## The dataset

The dataset used contains an extensive recopilation of question-answer regarding several medical conditions. The purpose of using this dataset is to show a possible application of fine tuning a small model to serve as an agent to solve medical queries.

https://www.kaggle.com/datasets/jpmiller/layoutlm
