# Chat Evalation Prep

This repo contains two notebooks to help run evaluations of DCAPI's chat functionality

- [PrepareEvaluationData](PrepareEvaluationData.ipynb) - Takes a list of questions and gets answers from DCAPI. Outputs spreadsheet to be used as input for Azure evaluations or for the `ScoreAnswers` notebook.
- [ScoreAnswers](ScoreAnswers.ibynb) - Takes a spreadsheet of question, answer, and ground_truths and scores the responses using AWS Bedrock.