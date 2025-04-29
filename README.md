# movie-success-prediction
Sentiment-based analysis and regression modeling of movie success

# Movie Success Prediction and Sentiment Study

This project aims to analyze the relationship between public sentiment (from YouTube comments on movie trailers) and the box office success of movies. It includes sentiment analysis and regression modeling using Python tools.

---

## Objective

- Predict movie box office success using metadata and sentiment scores.
- Analyze genre-wise sentiment patterns using YouTube trailer comment data.

---

## Dataset

- `movies_youtube_sentiments.csv`  
  Contains scraped YouTube trailer data, movie metadata, and sentiment scores generated using **VADER**.

### Key Columns:
- `name`, `genre`, `rating`, `budget`, `gross`, `votes`, `runtime`
- `sentiment_scores` (includes `positive`, `neutral`, `negative`)
- `favorability`: A custom metric based on sentiment

---

## Tools & Libraries

- Python
- NLTK (VADER Sentiment Analysis)
- Pandas, Matplotlib, Seaborn
- Scikit-learn (Linear Regression)

---

## Key Steps

1. Load and clean dataset
2. Analyze sentiment distributions
3. Perform genre-wise sentiment analysis
4. Build regression model to predict `gross` revenue
5. Visualize results and key insights

---

## Sample Visualizations

- Sentiment trend by genre
- Favorability vs. Box Office Gross
- Top movies by favorability score
- Correlation heatmap




