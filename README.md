# Aspect-Based Sentiment Analysis on Student Feedback

## Overview

This project analyzes student feedback using aspect-based sentiment analysis (ABSA) to extract actionable insights for academic decision-making. It combines unstructured text with structured responses.

## Methodology

* Data prepared using publicly available feedback with simulated academic attributes
* Multiple aspect extraction methods explored (keyword, LDA, clustering, transformer)
* Final pipeline uses transformer-based extraction with rule-based refinement
* Sentiment analyzed at sentence level and aggregated per aspect

## Dataset

* Semi-synthetic dataset combining real feedback text and generated metadata
* Includes feedback text, course details, aspects, sentiment, and MCQs

## Use Case

Supports department-level analysis of student feedback to identify issues in teaching, workload, and evaluation.

## Tech Stack

Python, Pandas, Scikit-learn, Sentence Transformers, NLTK, Streamlit (planned)

## Status

Work in progress; further refinement and validation ongoing.
