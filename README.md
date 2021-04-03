# Counts@IITK at SemEval-2021 Task 8: SciBERT Based Entity And Semantic Relation Extraction For Scientific Data

This repository contains all the code created as part of the SemEval-2021 Task 8 (MeasEval). We participated in the task as part of CS698X (Statistical Natural Language Processing) under the mentorship of Prof. Ashutosh Modi. The paper was accepted at Proceedings of the 15th International Workshop on Semantic Evaluation. 

MeasEval is a new entity and semantic relation extraction task focused on finding counts and measurements, attributes of these quantities, and additional information including measured entities, properties, and measurement contexts.

We proposed a SciBERT + CRF model for entity and semantic relation extraction from a corpus of scientific articles. For the unit detection subtask, we trained a character-based BiLSTM, and for the modifier subtask, we finetuned SciBERT with contextual embedding averaging. 

We achieved an overall fifth rank (among 19 participating teams) in the competition. We were also placed first in Quantity (tied) and Unit subtasks, second in MeasuredEntity, Modifier and Qualifies subtasks, and third in Qualifier subtask.

The instructions to run our code are given below :



