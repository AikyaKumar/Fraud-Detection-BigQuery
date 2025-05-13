# Fraud-Detection-BigQuery
This project analyzes a dataset stored in BigQuery using Google Cloud’s Vertex AI Notebooks to identify patterns of suspicious user behavior, such as hardcoded passwords and unapproved package installations following JFrog Artifactory.

# Fraud Detection Using BigQuery & Vertex AI

This project focuses on detecting suspicious patterns in a user activity dataset using **Google Cloud BigQuery** and **Vertex AI Notebooks**.

## Objective

The goal is to classify records based on behaviors like:
- Suspicious `pip install` commands (e.g., direct `.zip`, `.tar.gz`, `whl`, etc.)
- Hardcoded passwords in user interactions
- Use of unapproved Python package repositories

## Technologies Used

- Google Cloud BigQuery
- Vertex AI Jupyter Notebooks
- Python 3
- SQL
- Git & GitHub

