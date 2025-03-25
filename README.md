# Structured Sentiment Analysis using BiLSTM

## Project Overview
 We want to find opinions in sentences and make them into small graphs. Each opinion has four parts:
-Who is giving the opinion (holder)
-What the opinion is about (target)
-What words show the opinion (expression)
-Is it good or bad (polarity)
The task involves:
Monolingual SSA: Extracting sentiment graphs in a single language (e.g., English).
Cross-lingual SSA: Transferring knowledge to low-resource languages (e.g., Basque).

## Dataset
The dataset consists of texts with opinion tuples, including:
- Opinion Holders
- Opinion Targets
- Sentiment Polarities

## Model Architecture
We used BiLSTM model, which includes:
- Embedding Layer: for  dense vector representations.
- BiLSTM Layer: for contextual dependencies in both forward and backward directions.
- Fully Connected Layers: to structured sentiment output.

## Training Process
The model is trained using:
- Categorical Crossentropy Loss for multi-class classification.
- Adam Optimizer for efficient gradient updates.
- Batch Processing for stable convergence.
- Evaluation Metric: Sentiment Graph F1-score.

## Future Improvements
- Transformer-based Models (e.g., BERT, RoBERTa) for improved performance.
- Data Augmentation to enhance generalization.
- Cross-lingual Adaptations for better multilingual support.

## Contributors
- Hardik Sachdeva
- Rahul
- Ayan



