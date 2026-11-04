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
```

## Updates

The world of AI is constantly evolving with new techniques and models emerging all the time. So, while we do our best to keep everything up to date, sometimes the code in this repo may get updated before the accompanying video lessons. To make sure you're getting the most out of this course, we recommend you always use the latest code here alongside the video lessons, while we work on updating the videos. 

## UV Environment

Virtual environments are a great way to manage different packages for different projects. Creating a virtual environment for this section of the course allows you to ensure you can use the correct packages to follow along, without affecting any other packages you already have installed. 

```
uv venv
uv pip install -r requirements.txt
```
## Note

1. You need to install [Microsoft VS Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) now for ```langchain``` but may not be required in future.
2. `faiss-cpu` will not work with python 3.15 version now but may be during 2027.
3. To run `sentencepiece`, you need to first run `winget install Kitware.CMake`.