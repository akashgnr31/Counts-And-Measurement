# Counts@IITK at SemEval-2021 Task 8: SciBERT Based Entity And Semantic Relation Extraction For Scientific Data

This repository contains all the code created as part of the SemEval-2021 Task 8 (MeasEval). We participated in the task as part of CS779 (Statistical Natural Language Processing) under the mentorship of Prof. Ashutosh Modi. The paper was accepted at Proceedings of the 15th International Workshop on Semantic Evaluation. 

MeasEval is a new entity and semantic relation extraction task focused on finding counts and measurements, attributes of these quantities, and additional information including measured entities, properties, and measurement contexts.

We proposed a SciBERT + CRF model for entity and semantic relation extraction from a corpus of scientific articles. For the unit detection subtask, we trained a character-based BiLSTM, and for the modifier subtask, we finetuned SciBERT with contextual embedding averaging. 

We achieved an overall fifth rank (among 19 participating teams) in the competition. We were also placed first in Quantity (tied) and Unit subtasks, second in MeasuredEntity, Modifier and Qualifies subtasks, and third in Qualifier subtask.

The instructions to run our code are given below :

## Getting Started
Download the train and dev dataset from the following link: https://drive.google.com/drive/folders/16ZsJIHmW4FDQC6SrOQ7CEhPSQCBxoadl?usp=sharing

## Training Scripts
QuantityExtraction.ipynb : Contains the training Code for Quantity Extraction 

MeasuredEntity_HasQuantity_Extraction.ipynb: Contains the training code for MeasuredEntity and HasQuanity Relation Extraction

## Pretrained Models
Pretrained Model for Quantity Extraction (SciBERT + CRF Model) : https://drive.google.com/file/d/1nwt5y7w_kevUUB5V9EEt-Zkh-0oqyPXe/view?usp=sharing

Pretrained Model for MeasuredEntity and HasQuantity Extraction (SciBERT + CRF Model) : https://drive.google.com/file/d/1zmkwq-JAj91zYPzSSdYBtLb2TFFbgWkP/view?usp=sharing

