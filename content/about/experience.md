---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Senior Data Scientist
    company: Deep Dive
    company_url: ''
    company_logo: org-gc
    location: Mexico City
    date_start: '2023-04-01'
    date_end: ''
    description: |2-        
        * Working on creating an Augmented Language Model (ALM) for advertising by calling API tools (Brandwatch, Google Trends and propietary data) to augment LMs’ capabilities by using Langchain library and GPT-4 OpenAI API service.
        * Working on reducing latency and costs of the company's main services by deploying a forecasting model of AWS Lambda functions' preserved concurrency.
        *	Deployed a Streamlit web app to check if senators’ initiatives discuss a particular topic and displayed related summarized points using Langchain and text-davinci-003 GPT3 OpenAI model.

  - title: Junior Data Scientist
    company: Deep Dive
    company_url: ''
    company_logo: org-x
    location: Mexico City
    date_start: '2022-08-01'
    date_end: '2023-03-31'
    description: |2-     
        *	Developed a spanish Sentence Transformer language model using a knowledge distillation process, between DeBERTa and RoBERTa BERT variants, and trained on anthropological data of Mexican citizens.
        * Accomplished a 20% reduction in the probability of file generation error, as measured by the error rate, by implementing JSON and ADX file processing interfaces using Docker containers, pandas, and orchestrated scripts from different corporate servers.

  - title: Data Scientist Intern
    company: Deep Dive
    company_url: ''
    company_logo: org-x
    location: Mexico City
    date_start: '2022-01-01'
    date_end: '2022-07-31'
    description: |2-
        * Established the first comprehensive dataset of Mexican firms' legal and corporate actions information, by using bots (web scraping) that ingest thousands of new observations monthly into a AWS cloud database.

design:
  columns: '1'
---
