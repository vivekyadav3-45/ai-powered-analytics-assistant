# AI-Powered Analytics Assistant

A Python-based analytics application that helps users explore CSV datasets, inspect data quality, and generate descriptive insights through a simple web interface.

This project is a foundation for exploring how data analytics can be combined with Large Language Models (LLMs), Generative AI, and the Model Context Protocol (MCP).

## Overview

The goal is to make data exploration easier by allowing users to upload datasets, understand their structure, identify data-quality issues, and review basic statistical summaries without writing code for every routine task.

## Features

- **CSV Data Upload:** Upload a CSV file for analysis.
- **Dataset Overview:** View the number of rows, columns, missing values, and duplicate records.
- **Data Preview:** Inspect the uploaded dataset and column data types.
- **Data Quality Analysis:** Identify missing values and duplicate rows.
- **Descriptive Statistics:** Review summary statistics for numerical columns.
- **Predefined Questions:** Ask supported questions about dataset structure and data quality through the interface.

## Technology Stack

- Python
- Pandas
- Streamlit
- Git and GitHub

## Architecture

1. The user uploads a CSV dataset.
2. Pandas processes the data.
3. The application calculates dataset metrics and descriptive statistics.
4. Streamlit displays the results through an interactive interface.
5. A future extension can introduce LLM-powered question answering and MCP-based tool integration.

## Getting Started

### Prerequisites

- Python 3.10 or later
- pip

### Installation

Clone the repository:

```bash
git clone https://github.com/vivekyadav3-45/ai-powered-analytics-assistant.git
cd ai-powered-analytics-assistant
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal and upload a CSV file.

## Example Questions

- How many rows are in this dataset?
- Which columns contain missing values?
- What columns are available?
- Show summary statistics.
- How many duplicate rows are present?

## Current Scope and Roadmap

The current starter version focuses on CSV-based data exploration and predefined analytical questions.

Planned improvements:

- [ ] Integrate an LLM API for natural-language analytics.
- [ ] Implement MCP tools for controlled access to analytical functions.
- [ ] Add validation and error handling for analytical queries.
- [ ] Add unit tests and sample datasets.
- [ ] Deploy a demo application.
- [ ] Document architecture and example workflows.

## Security

- Never commit API keys, passwords, or access tokens.
- Do not upload confidential or personally identifiable data.
- Validate uploaded files and treat external data as untrusted input.
- Keep LLM and MCP integrations disabled until they have been implemented and tested.

## About

I'm a Data Analyst developing practical projects that combine Python, SQL, Power BI, and data analytics with emerging AI technologies.

This project represents my learning journey toward building useful AI-powered analytical tools.

**Author:** Vivek Yadav

**GitHub:** https://github.com/vivekyadav3-45
