# Aspect-Based Sentiment Analysis with PyABSA

## Overview

This project demonstrates Aspect-Based Sentiment Analysis (ABSA) using PyABSA, a library for aspect-based sentiment analysis. The application allows users to input a sentence, and it extracts aspects, predicts sentiment, and displays the results in a tabular form.

## Getting Started

### Prerequisites

- Python 3.x
- Install required dependencies: `streamlit`, `pyabsa`, `pandas`

```bash
pip install -r requirements
```

## Running the Application

1. Clone the repository

```bash
git clone https://github.com/shaadclt/Aspect-Based-Sentiment-Analysis.git
cd Aspect-Based-Sentiment-Analysis
```

2. Run the streamlit app

```bash
streamlit run ABSA.py
```

## Usage

1. Enter a sentence in the provided text input.
2. Click the "Analyze" button to perform Aspect-based Sentiment Analysis.
3. View the results in the displayed table.


## Result Format

The analysis result is displayed in a table with the following columns.

- **Aspect**: Aspect number
- **Term**: Extracted aspect term
- **Sentiment**: Predicted sentiment (Positive/Negative)
- **Confidence (%)**: Confidence level of the sentiment prediction in percentage. 


## Contributing 

If you'd like to contribute to this project, please follow the standard GitHub Fork & Pull Request workflow.


## License

This project is licensed under the MIT License.

