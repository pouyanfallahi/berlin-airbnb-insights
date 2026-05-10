# Berlin Airbnb: Clustering, Sentiment & Price Prediction

**Author:** Pouyan Fallahi  
**Contact:** fallahipouyan78@gmail.com  
**LinkedIn:** [linkedin.com/in/pouyan-fallahi](https://linkedin.com/in/pouyan-fallahi)

## Overview
This project analyzes Berlin’s Airbnb market using over 635,000 reviews and 14,000 listings. It segments listings via K‑Means clustering, extracts guest sentiment with VADER, and builds predictive models for listing price and superhost status.

## Key Results
- **Clustering:** Two distinct segments – Premium (larger, higher‑priced, higher superhost ratio) and Budget (affordable, smaller).
- **Sentiment:** Both clusters are predominantly positive (65‑66%), but budget listings show slightly more mixed feelings.
- **Price Prediction (Random Forest):** R² = 0.927, MAE = €6.92.
- **Superhost Classification:** 96% accuracy.
- **Top Drivers:** Location, review scores, and amenities count dominate both price and superhost status.

## Tech Stack
Python | pandas | NumPy | scikit‑learn | NLTK (VADER) | Matplotlib | Seaborn | Jupyter Notebook | LaTeX

## Repository Structure
- `notebooks/` – Jupyter Notebook with the full analysis pipeline.
- `data/` – Instructions to download the dataset (not included due to size).
- `report/` – PDF report and LaTeX source.
- `outputs/` – Saved intermediate files (optional).

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/berlin-airbnb-insights.git
   cd berlin-airbnb-insights