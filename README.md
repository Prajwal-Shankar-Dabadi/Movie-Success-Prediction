# Movie Success Prediction using TMDB Dataset

##  Project Description

This project predicts whether a movie will be successful (Hit) or not (Flop) using the TMDB dataset.  
I used movie details such as budget, revenue, vote average, and popularity to build a machine learning model.

The model helps understand what factors affect movie success.

## Objective

- Analyze movie data
- Calculate movie profit
- Classify movies as Hit or Flop
- Build a machine learning prediction model
  
##  Dataset Used

- tmdb_5000_movies.csv  
- tmdb_5000_credits.csv  

These datasets contain information about:
- Budget  
- Revenue  
- Ratings  
- Popularity  
- Cast and crew  

## Steps Performed

1. Loaded both TMDB datasets.
2. Merged them using the title column.
3. Cleaned the dataset.
4. Removed movies with zero budget.
5. Created a new column:
   
   Profit = Revenue − Budget

6. Created a success column:
   - 1 = Hit (Profit > 0)
   - 0 = Flop (Profit ≤ 0)

7. Selected important features:
   - Budget
   - Vote Average
   - Popularity

8. Split data into training and testing sets.
9. Trained a Random Forest classification model.
10. Checked model accuracy.

## Machine Learning Model

Model Used: Random Forest Classifier  
Type: Binary Classification  

The model predicts whether a movie will be a Hit or Flop.

## Results

- Budget has strong impact on revenue.
- Popularity also influences success.
- The model successfully predicts movie success using historical data.

## How to Run

1. Install required libraries:
   pip install pandas numpy matplotlib scikit-learn

2. Place dataset files in same folder as notebook.

3. Open the notebook:
   Movie Success Prediction using TMDB Dataset.ipynb

4. Run all cells.

## Project Files

- Jupyter Notebook (.ipynb)
- Final Report (.pdf)
- Dataset files (.csv)
- README.md

