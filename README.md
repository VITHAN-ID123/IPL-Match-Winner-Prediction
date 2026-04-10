# IPL Match Winner Prediction

Predict IPL match winners using historical match data and a Random Forest model.

## Project Overview
- Dataset: IPL matches (team1, team2, toss, venue, winner)
- Goal: Predict match winner
- Problem Type: Classification

## Tools & Libraries
- Python (Pandas, Matplotlib)
- Scikit-learn (Random Forest)

## Steps Performed
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
   - Wins per team
   - Toss effect on winning
3. Encode categorical variables
4. Train-test split
5. Train Random Forest model
6. Predictions & evaluation (accuracy + confusion matrix)
7. Feature importance visualization
8. Sample winner prediction function

## Insights
- Certain teams have higher win rates at specific venues
- Toss winner choice (bat/field) can slightly influence match outcome
- Random Forest identifies key features affecting match results
