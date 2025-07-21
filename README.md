## 🧠 Sentiment Analysis in Jupyter Notebook

This project analyzes customer feedback using **TextBlob**, **Pandas**, and **Matplotlib**, all within a Jupyter Notebook environment. Feedback data is sourced from an Excel file, and sentiment is categorized as Positive, Neutral, or Negative based on the **calculated polarity** of each text entry.

## 📘 Project Overview

- Format: Jupyter Notebook (`.ipynb`)
- Input: Customer feedback from Excel (`.xlsx`)
- Output: Sentiment classification + visual insights
- Objective: Identify sentiment trends to help improve customer satisfaction

## 🛠️ Tools & Libraries

- `Python`
- `Jupyter Notebook`
- `Pandas` — data manipulation
- `TextBlob` — sentiment analysis via polarity scores
- `Matplotlib.pyplot` — data visualization

## 📊 Key Features

- Reads `.xlsx` file into a DataFrame
- Cleans and processes textual feedback
- Calculates **polarity** of each entry using TextBlob
- Classifies sentiment:
  - **Positive** if polarity > 0
  - **Neutral** if polarity = 0
  - **Negative** if polarity < 0
- Visualizes sentiment distribution with a bar chart
- Displays sentiment labels next to feedback entries

## 📦 Installation

```bash
pip install pandas textblob matplotlib
python -m textblob.download_corpora
