# Football Player Market Value Predictions

## Introduction  

Football (soccer) is the world's most popular sport, with a multi-billion-dollar transfer market that drives club strategies and player careers. Accurately predicting player market values is crucial for clubs, agents, and analysts to make informed decisions about transfers, contracts, and squad planning.  

This project leverages machine learning to analyze and predict football players' market values based on their performance statistics, demographics, and historical valuation trends. By combining datasets from player profiles, match appearances, valuations, and game records, we build predictive models that estimate a player's worth in the transfer market.  

Key challenges addressed include:  
- Data integration from multiple sources with varying structures  
- Feature engineering to capture performance trends over time  
- Model selection to balance accuracy and interpretability  
- Evaluation metrics to assess real-world applicability  

The implemented solution provides:  
✔ Transparent valuation insights for scouting and recruitment  
✔ Performance-based projections to identify undervalued players  
✔ Benchmarking tools for contract negotiations  

This repository contains the complete data processing pipeline, exploratory analysis, and machine learning implementation to replicate and extend this research.  

## Project Description

The implementation includes:
- Data collection from public football datasets
- Comprehensive data preprocessing and feature engineering
- Exploratory data analysis of market value trends
- Machine learning models (Linear Regression and KNN Regressor)
- Model evaluation and visualization

## Key Features

- Data Integration: Combines multiple football data dimensions
- Performance Analysis: Goals, assists, cards, and playing time metrics
- Temporal Features: Current and previous season statistics
- Visual Analytics: Market value trends and model performance graphs

## Results

- Linear Regression: MSE 0.8228
- KNN Regressor: Improved performance with MSE 0.7796
- Effective predictions particularly for mid-range market values

## Data Requirements

The project uses these datasets from Kaggle (must be downloaded separately):

1. [Player Information (players.csv)](https://www.kaggle.com/datasets/dayidcariboo/player-scores?select=players.csv)
2. [Player Valuations (player_valuations.csv)](https://www.kaggle.com/datasets/dayidcariboo/player-scores?select=player_valuations.csv)
3. [Player Appearances (appearances.csv)](https://www.kaggle.com/datasets/dayidcariboo/player-scores?select=appearances.csv)
4. [Games Data (games.csv)](https://www.kaggle.com/datasets/dayidcariboo/player-scores?select=games.csv)

After downloading, place all CSV files in a `data/` directory in the project root.

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/vishal2807/vishal2807-Football-Player-Market-Value-Predictions]
   cd football-market-value-prediction
   ```

2. Create data directory and add datasets:
   ```bash
   mkdir data
   # Add downloaded CSV files to the data/ directory
   ```

3. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the Jupyter notebook:
```bash
jupyter notebook FinalProject.ipynb
```

## Dependencies

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- tensorflow (optional)
- jupyter

## Future Enhancements

- Implement advanced ensemble models
- Add player injury history and team performance metrics
- Develop interactive web dashboard
- Include transfer market news sentiment analysis

## Contributors

Vishal Bachal - vishalbachal0703@gmail.com

