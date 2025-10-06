# Steam Games Dataset - Data Science Analysis

## Overview
This repository contains a comprehensive data science analysis of the Steam Games dataset. The analysis demonstrates various data science techniques and provides insights into the gaming industry on Steam.

## Dataset
- **File**: `steam_games.csv`
- **Size**: 71,429+ games
- **Features**: Game information including prices, reviews, genres, platforms, developers, publishers, and more

## Analysis Notebook
The main analysis is contained in `steam_games_analysis.ipynb`, which includes:

### 1. Data Exploration
- Dataset overview and structure
- Statistical summaries
- Missing value analysis

### 2. Data Preprocessing
- Data cleaning and transformation
- Feature engineering
- Parsing complex data types (genres, categories, platforms)

### 3. Exploratory Data Analysis (EDA)
- **Release Status Analysis**: Distribution of released vs unreleased games
- **Price Distribution**: Analyzing game pricing patterns and statistics
- **Genre Analysis**: Most popular game genres on Steam
- **Platform Analysis**: Game availability across Windows, Mac, and Linux
- **Release Timeline**: Historical trends in game releases
- **Review Analysis**: User review patterns and sentiment
- **Achievement Analysis**: Distribution of achievements in games
- **Category Analysis**: Most common game features and categories
- **Developer & Publisher Insights**: Top contributors to the platform

### 4. Statistical Analysis
- Correlation analysis between features
- Price vs Review relationships
- Genre vs Price analysis

### 5. Key Findings
- Comprehensive insights about the Steam gaming ecosystem
- Trends and patterns in game development
- User engagement metrics
- Pricing strategies

### 6. Machine Learning for Game Success Prediction
- Feature engineering for predictive modeling
- Random Forest classifier implementation
- Model evaluation and performance metrics
- Feature importance analysis

### 7. Price Optimization Analysis
- Price vs success rate analysis
- Genre-specific pricing recommendations
- Optimal pricing strategies

## Visualizations
The notebook includes 20+ professional visualizations using matplotlib and seaborn:
- Pie charts for categorical distributions
- Histograms for continuous distributions
- Bar charts for comparisons
- Line plots for trends over time
- Scatter plots for relationships
- Box plots for statistical distributions
- Heatmaps for correlations

## How to Use

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn jupyter notebook
```

### Running the Analysis
```bash
jupyter notebook steam_games_analysis.ipynb
```

Or execute all cells:
```bash
jupyter nbconvert --to notebook --execute steam_games_analysis.ipynb
```

## Key Insights

### 📊 Dataset Statistics
- Total games analyzed: 71,000+
- Released games: ~70%
- Free games: ~8%

### 💰 Pricing
- Average game price: ~$12-15
- Most common price point: $4.99
- Price sweet spot: $5-$15

### 🎮 Popular Genres
- Indie: Most prevalent genre
- Action: Second most common
- Adventure: Third most popular

### 💻 Platform Support
- Windows: Dominant platform (95%+)
- Multi-platform support: Growing trend
- Linux support: Still relatively limited

### ⭐ User Engagement
- Average positive review rate: ~75%
- Games with achievements: ~40%
- Review distribution: Long-tail pattern

## What Can You Do With This Dataset?

This analysis demonstrates:
1. ✅ Data loading and exploration techniques
2. ✅ Data cleaning and preprocessing
3. ✅ Exploratory data analysis with visualizations
4. ✅ Statistical analysis and correlations
5. ✅ Insight generation and business intelligence
6. ✅ Professional data presentation
7. ✅ **NEW: Machine learning for predictive modeling**
8. ✅ **NEW: Price optimization and recommendations**

## Implemented Extensions
- ✅ **Machine learning models for game success prediction** - Random Forest classifier to predict game success based on features
- ✅ **Price optimization analysis** - Genre-specific pricing recommendations and optimal price range analysis

## Potential Future Extensions
- Recommendation system based on genres and features
- Sentiment analysis on reviews
- Time series forecasting for releases
- Market segmentation analysis
- Developer/Publisher portfolio analysis

## Technologies Used
- Python 3.12+
- pandas: Data manipulation and analysis
- numpy: Numerical computing
- matplotlib: Data visualization
- seaborn: Statistical visualizations
- scikit-learn: Machine learning models
- Jupyter: Interactive notebook environment

## New Features

### 🤖 Machine Learning for Game Success Prediction
The analysis now includes a Random Forest classifier that predicts game success based on various features:
- **Success Definition**: Games with >80% positive reviews and >50 total reviews
- **Features Used**: Price, achievements, platform support, genres, review count
- **Model Performance**: ~60% accuracy with feature importance insights
- **Key Finding**: Total reviews is the most important predictor of success

### 💰 Price Optimization Analysis
Comprehensive pricing strategy recommendations:
- **Price Range Analysis**: Success rates across different price brackets
- **Optimal Price Range**: $4.99 - $17.99 for maximum success probability
- **Genre-Specific Pricing**: Tailored recommendations for Indie, Action, Adventure, Casual, and Strategy games
- **Business Insights**: Sweet spot pricing strategies for game developers

## License
MIT License - see LICENSE file for details