---
license: ecl-2.0
task_categories:
- text-classification
language:
- en
tags:
- public
- tabular
- text
- classification
- education
pretty_name: Spam Eail 5k5
size_categories:
- 1K<n<10K
configs:
- config_name: dataset
  data_files:
  - split: train
    path: 
    - "spam_emails_5k5.csv"
---

# Spam Eail 5k5

Description  
SpamMail-Binary is a curated email corpus designed for training and evaluating spam-detection systems. Each record contains:

- **Message** – full email text, including subject and body  
- **Category** – binary label: **Spam** or **Ham** (non-spam)

The collection spans a diverse range of phishing attempts, promotional blasts, newsletters, and legitimate correspondence, offering clean, real-world language patterns for natural-language-processing and machine-learning tasks.