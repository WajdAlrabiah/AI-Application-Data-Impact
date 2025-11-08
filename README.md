# AI Application: Impact of Data on ML Models

This project investigates how **data quantity and quality** influence the performance of machine learning models.  
It fine-tunes the **Microsoft GIT (Generative Image-to-Text)** model on the **Pokemon BLIP Captions dataset** to generate captions for images.

---

## Overview

The notebook demonstrates three main experiments:

1. **Full Dataset Training** – Fine-tunes the model using the entire dataset.  
2. **Subset Training (400 examples)** – Tests how reducing the training data affects model performance.  
3. **Data Quality Reduction** – Removes samples containing specific keywords to analyze the impact of low-quality or biased data.

Each part includes training, evaluation, and inference for comparison.

---

## Features

- Dataset preprocessing and transformation  
- Fine-tuning using the `transformers` library  
- Evaluation using **Word Error Rate (WER)** metric  
- Caption generation under multiple inference settings (`temperature` and `do_sample`)  
- Comparison between:
  - Full dataset  
  - Subset of 400 examples  
  - Filtered (lower-quality) dataset  

---

## Hello and Welcome

Thank you for visiting my GitHub page!  
I’m currently in the process of uploading my previous projects and doing my best to make them publicly available in an organized and clear manner.  

At the moment, I’m adding each project with some **light updates and clarifying adjustments**, and I plan to include more **comprehensive notes, explanations, and detailed READMEs** very soon — to help others better understand each project’s idea and usage.  

If you have any questions, suggestions, or would simply like to connect, I’d be delighted to hear from you:  
- [LinkedIn](https://www.linkedin.com/in/wajdalrabiah)  
- [X (Twitter)](https://x.com/wajdalrabiah)  

Thank you again for your time and interest.  
Your feedback and interaction are always appreciated

> _More updates coming soon — stay tuned!_  
