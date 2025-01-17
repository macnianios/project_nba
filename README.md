# PROJECT NBA

Objectives:

•	In this analysis, we'll explore how factors beyond shooting impact winning outcomes in the NBA. We'll examine the home-court advantage, as well as rebounding and assist totals, to see how they influence game results.
•	Additionally, we'll investigate potential correlations between point, rebound and assists differential between teams.
•	Finally, we'll analyze how these factors, points, rebounds, and assists, have changed within the NBA over the past two decades.

#Running the Notebook in Google Colab
  1.	Open Google Colab: Go to https://colab.research.google.com/.
  2.	Upload the Notebook:
  3.	Click on "File" -> "Upload notebook" and select "nba_reb_ass_analysis.ipynb" from your local machine.
  4.	Alternatively, you can upload the entire project directory (including "nba_reb_ass_analysis.ipynb") to your Google Drive and open the notebook directly from there.

#Methods Used

    •	Data Manipulation (pandas,numpy)  
    •	Data Visualization(seaborn,matplotlib)
    •	Machine Learning (sklearn, Linear regression)


#DATA
  •	the datafile is from https://www.kaggle.com/datasets/nathanlauga/nba-games


#Results

  • The data clearly reveals a trend: teams with more assists tend to win more games. Teams with more rebounds also see higher win rates, followed by teams that play at home
  
  • The analysis reveals a moderate positive correlation (0.60) between assist differential and point differential. While this suggests a trend, it's not definitive. We can expect exceptions and outliers in the data. Similarly, the correlation         (0.46) between point differential and rebound differential is weaker, implying a less pronounced trend and potentially more exceptions and outliers.
  
  • Our analysis reveals a notable rise in both points and assists averaged per game, alongside a modest increase in rebounds per game. Let's visualize these trends through the course of our 20-year data using plots.
