# Chat Evalation Prep

This repo contains two notebooks to help run evaluations of DCAPI's chat functionality. 

- [PrepareEvaluationData](PrepareEvaluationData.ipynb) - Takes a list of questions and gets answers from DCAPI. Outputs spreadsheet to be used as input for for the `ScoreAnswers` notebook (or for Azure evaluations).
- [ScoreAnswers](ScoreAnswers.ibynb) - Takes a spreadsheet of question, answer, and ground_truths produced from `PrepareEvaluationData` and scores the responses using AWS Bedrock.

## AWS and DCAPI authorization

- `PrepareEvaluationData` - requires you to obtain a DCAPI authorization token and [Setup Environment Variables](PrepareEvaluationData.ipynb#Setup-Environment-Variables). 
- `ScoreAnswers` requires you to be logged in as either a `staging` or `production` user (login in your terminal **__before__** launching your Jupyter notebook)


## Environment Setup (optional)

Python virtual environments can be a great way to bundle a collection of libraries for a specific research area or project and keep it separate from other activities.
There are two steps: First, you must create the virtual environment; second, you must install the virtual environment as a Jupyter kernel.

Here are some resources describing how to do this: 
 - [Using a virtual environment with Jupyter Notebook](https://docs.support.arc.umich.edu/python/jupyter_virtualenv/)
 - [Using Virtual Environments in Jupyter Notebook and Python](https://janakiev.com/blog/jupyter-virtual-envs/)
 - [Using Jupyter Notebook in Virtual Environment](https://www.geeksforgeeks.org/using-jupyter-notebook-in-virtual-environment/)
 - [Using a Virtual Environment with Jupyter Notebook](https://www.uvm.edu/vacc/kb/knowledge-base/virtual-environments-in-jupyter-notebook/)
 - [Chat GPT](https://chat.openai.com/)
