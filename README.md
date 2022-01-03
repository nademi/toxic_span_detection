- SemEval 2021 Task 5: Toxic Spans Detection:


### Task:

Link to SemEval-2021: Task 5 Toxic Span Detection is [https://competitions.codalab.org/competitions/25623](https://competitions.codalab.org/competitions/25623)

### References:
1. https://huggingface.co/docs/transformers/training - To understand how to train model.
2. https://huggingface.co/docs/transformers/model_doc/roberta - To understand Roberta model and corresponding tokenizer
3. https://huggingface.co/docs/transformers/model_doc/distilbert - To understand DistilBert and corresponding rokeniser
4. https://github.com/huggingface/transformers/issues/14305 - to understand postprocessing of predicted labels to spans
5. https://github.com/huggingface/notebooks/blob/master/examples/token_classification-tf.ipynb - Copied function tokenize_and_align_labels() from this tutorial notebook from huggingface and followed the certain steps to fine tune model on custom dataset.
6. https://github.com/ipavlopoulos/toxic_spans/blob/master/evaluation/metrics.py - F1 score function provided by competition is modified to accomodate our model output

- This project was conducted in a group for project of CMPUT 501- Introduction to NLP. Other group member is Ravika Nagpal
