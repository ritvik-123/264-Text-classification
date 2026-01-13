# Text Classification Project

This repository contains a **text classification** project implemented using Python and Jupyter Notebook.  
The goal of the project is to demonstrate how textual data can be processed and classified into predefined categories. Make up a text classification model, classifying student's responses into various rubric/requirements, this makes it easier for the professor/graders to make a gist of the submission and see the submission divided into the required goals for the assignment. The dataset used here portrays essays from the IELTS writing section, and the need is to classify the essays into three rubrics being used for the grading of these essays, i.e., Task Response. coherence and correlation, and Lexical resources (Vocabulary).

---

## Files

- `264_Project_Classification_model_arch.ipynb` — Jupyter Notebook containing the text classification workflow.
- `264_Project_Classification_model_arch.pdf` — PDF export of the notebook.
- Additional project documents related to the model and analysis.

---

## Project Overview

The notebook includes a basic text classification pipeline, including text preprocessing, feature extraction using fine-tuned BERT (for getting feature embeddings), and performing classification using the BERT base model. After training/fine-tuning the model, the performance is evaluated, and the labels are predicted for the test data.
