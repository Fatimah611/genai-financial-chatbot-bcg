# GenAI Financial Chatbot (BCG Virtual Experience)

A financial chatbot that combines rule-based logic with LLM-driven responses to answer questions about company financials. It uses Python and Pandas to analyse data extracted from 10-K and 10-Q reports and turns it into financial insights.

## Notebooks

- `BCG_data_prep.ipynb`: data preparation and exploration of the extracted financial data, including charts
- `BCG_AI_chatbot.ipynb`: the chatbot, combining rule-based handling of common queries with LLM-generated answers

## Tech stack

Python, Pandas, Jupyter, LLM API

## Setup

1. Install dependencies:

        pip install pandas openpyxl matplotlib notebook

2. Place the extracted data file (`DATA EXTRACTION.xlsx`) next to the notebooks. The data file is not included in this repository.
3. If a notebook calls an LLM API, provide your own key through an environment variable. Keys are never committed.
4. Open the notebooks with Jupyter and run the cells in order.

## Context

Built as part of the BCG GenAI virtual experience on Forage.