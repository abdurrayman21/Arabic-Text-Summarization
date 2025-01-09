# Arabic Text Summarization and Analysis

This project demonstrates an end-to-end pipeline for Arabic text summarization using the **mT5 model**, along with dataset analysis and ROUGE score evaluation for summarization quality. The code is modularized for clarity and ease of use.

## Features
- **Text Summarization**: Summarizes Arabic text using the multilingual mT5 model.
- **ROUGE Score Evaluation**: Computes and visualizes ROUGE scores to assess summarization quality.
- **Dataset Analysis**: Includes visualizations for text length distribution, category distribution, and sample text lengths.

---

## Project Structure
The project is divided into the following modules:

### 1. Summarization Module
Handles the process of summarizing input text using the **mT5 model**.

**Functionality**:
- Preprocesses input text.
- Generates concise summaries using beam search.

### 2. ROUGE Score Calculation and Visualization
Computes and visualizes **ROUGE-1**, **ROUGE-2**, **ROUGE-L**, and **ROUGE-Lsum** scores for generated summaries.

**Functionality**:
- Evaluates summarization quality.
- Displays ROUGE scores as a bar chart.

### 3. Dataset Analysis and Visualization
Explores and visualizes characteristics of the Arabic text dataset.

**Functionality**:
- Text length distribution.
- Category distribution (if applicable).
- Sample text length comparisons.

---

## Installation

To set up the environment, install the required dependencies:

```bash
pip install transformers datasets evaluate matplotlib seaborn

