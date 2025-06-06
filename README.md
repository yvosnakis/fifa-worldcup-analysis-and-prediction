# FIFA World Cup Data Analysis and Prediction

This repository contains a comprehensive data analysis and machine learning project focused on the FIFA World Cup. The notebook (`analysis.ipynb`) explores historical data, visualizes trends, and builds a predictive model to forecast potential winners of future tournaments.

## Project Structure

- **Data Loading & Cleaning**: Robust loading from multiple directories and thorough standardization of country and stadium names.
- **Exploratory Data Analysis (EDA)**:
  - Distribution of tournament results (Winner, Runner-Up, Third Place)
  - Total and average goals by team and tournament
  - Year-by-year trends in attendance, goals, and number of teams
  - Match outcomes (win/loss/draw)
  - Matches with highest attendance
- **Visualizations**: Uses Plotly, Seaborn, and Matplotlib for rich, informative visual displays.
- **Machine Learning**:
  - Random Forest Classifier trained on past team performance and match metrics
  - Encoded categorical features (team name, position, etc.)
  - Prediction of top contenders for the next World Cup

## Model Highlights

The model was trained on features such as:
- Tournament performance history (Winner, Runner-Up, etc.)
- Goals scored across matches
- Match-level attendance
- Final standing in the tournament

It outputs probabilities of winning the next tournament and highlights the top 5 contenders based on historical data.

## Key Discoveries

- Brazil, Germany, and Italy lead in historical World Cup victories and podium appearances.
- Match attendance steadily increased over the decades.
- Host nations tend to perform better in their home tournaments.
- The predictive model identifies statistically probable winners for upcoming tournaments like the 2026 World Cup.


The datasets are publicly available, including from platforms like Kaggle.

## Running the Project

Open `fifa_world_cup_full_code.ipynb` in Jupyter Notebook or JupyterLab and run all cells. The notebook will display visual insights and model predictions.

## Note

Interactive Plotly charts may not render on GitHub. For full interactivity, run the notebook locally or download and open the 'analysis.html' file.
