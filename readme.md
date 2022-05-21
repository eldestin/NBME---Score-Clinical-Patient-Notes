## This task is a Question-Answering competition holding on Kaggle

Dataset can be downloading or visiting [here](https://www.kaggle.com/competitions/nbme-score-clinical-patient-notes "Dataset URLS").

## Model using here

The model I use in this task is [Roberta-large](https://github.com/huggingface/transformers/blob/main/src/transformers/models/roberta/modeling_roberta.py#L693 "Pretrained from HuggingFace")  +  Dense Layer. Notice that this task is represented as a binary classification problem, which means judging whether a span is in the labels or not.

## Train the model

Just download the Dataset and run the following cell with specific paths.
