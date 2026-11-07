# Introduction to LLMs Course Notebooks

Welcome to the **Introduction to LLMs** course repository! 

This repository contains Jupyter notebooks designed to help you learn the basics of Large Language Models through hands-on examples and exercises.

The notebooks are designed to accompany the Introduction to Large Language Models course which can be found here: 

https://learn.365datascience.com/courses/preview/intro-to-llms/

https://www.udemy.com/course/intro-to-large-language-models-llms/

## Installed Packages

These are the installed packages and versions used for this course. All were installed in a conda environment (see below for how I created this). 

python=3.15

```
openai
config
langchain
pydantic
tiktoken
faiss-cpu
transformers
torch
datasets
evaluate
accelerate
ipywidgets
matplotlib
seaborn
clean-text
scikit-learn
sentencepiece
pandas
python-dotenv
```

## Updates

The world of AI is constantly evolving with new techniques and models emerging all the time. So, while we do our best to keep everything up to date, sometimes the code in this repo may get updated before the accompanying video lessons. To make sure you're getting the most out of this course, we recommend you always use the latest code here alongside the video lessons, while we work on updating the videos. 

## Use Google Colab

[Google Colab](https://colab.research.google.com/) has the only fastest environment for running jupyter notebooks especially if you have a slower PC. 
Luckily, it is an asset if you have a high-performance PC as you can also run notebooks in an IDE fastly.

If you use an IDE like VS Code or PyCharm for this project, run in terminal:
```
uv venv
uv pip install -r requirements.txt
```

## Note

1. You will face problem with installing `langchain` because newer python version 3.15 does not support 3.14 its modules.