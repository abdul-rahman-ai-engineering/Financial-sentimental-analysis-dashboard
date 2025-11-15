# AI-Powered Financial Sentiment Analysis Dashboard

[Python 3.9+](https://www.python.org/downloads/)
[Streamlit 1.29+](https://streamlit.io)
[PyTorch 2.1+](https://pytorch.org)
[Transformers 4.36+](https://huggingface.co/transformers/)

Real-time financial sentiment analysis dashboard powered by a custom fine-tuned FinBERT model. 
Built for Bitcoin, stocks, forex, and cryptocurrency market sentiment tracking.

# Project Overview

This project provides an end-to-end AI-powered sentiment analysis system tailored for financial markets. It gathers data from multiple financial sources, processes it using advanced NLP methods, evaluates sentiment using a fine-tuned FinBERT model, and displays results through a fully interactive dashboard.

# Key Highlights

* Custom fine-tuned FinBERT model optimized for financial sentiment (90%+ accuracy)
* Aggregation from multiple financial news sources
* Real-time analysis of 100–300+ articles per refresh
* Professional Streamlit dashboard with interactive visualizations
* Robust error handling, logging, and fallback logic
* Works with free data sources; premium APIs optional

# Dashboard Preview

# Main Dashboard Features

* Real-time sentiment distribution (positive, neutral, negative)
* Trend-focused key performance indicators
* Multi-source aggregation tracking
* Confidence scores for predictions
* Interactive filtering by instrument, time, or sentiment
* Data export to CSV

# Available Visualizations

1. Sentiment overview with distribution graphs
2. Time series sentiment analysis
3. Instrument-based sentiment breakdown
4. Raw data table with full article text and metadata

# AI and Machine Learning Features

* Custom FinBERT model fine-tuned on financial text
* Three-class sentiment classification
* Confidence scoring for each prediction
* Efficient batch processing
* Full model save/load capabilities

# Data Collection Features

* Multi-source aggregation with failover
* Automatic rate limiting
* Financial instrument detection
* Real-time refresh of data

# Dashboard Features

* Interactive Plotly visualizations
* Configurable auto-refresh
* Search, filtering, and time-based analysis
* Simple export functionality
* Responsive layout and performance metrics

# Technical Features

* Production-level logging
* Centralized configuration
* Streamlit caching for performance
* Modular codebase designed for maintainability

---

# Quick Start (5 Minutes)

# Prerequisites

You will need:

* Python 3.9 or higher
* pip
* Git
* At least 8GB RAM
* At least 5GB free storage

# Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/sentiment-dashboard.git
cd sentiment-dashboard
```

2. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate
```

(Windows instructions unchanged)

3. Install dependencies:

```bash
pip install --upgrade pip
pip install -r requirements.txt
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords')"
```

4. Configure the environment (optional):

```bash
cp .env.example .env
```

5. Train the model:

```bash
python train_model.py
```

6. Run the dashboard:

```bash
streamlit run app.py
```

Your dashboard will open in the browser.
