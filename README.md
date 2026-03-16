# Project Description
The FIFA Player Dataset (Game.xlsx) contains detailed information about football players,
including:
* Demographics: Age, Nationality, Club, Position
* Performance metrics: Overall rating, Potential rating
* Financial data: Wage, Value
* Physical attributes: Weight, Height
* Skills: Dribbling, Passing, Shooting, etc.

* This dataset, taken from a football simulation game, provides a great opportunity to analyze players’ profiles, performance potential, and market value using Python and Pandas.
* The goal of this project is to perform an end-to-end data analysis, applying statistical methods like distribution analysis, outlier detection, confidence intervals, and the Central Limit Theorem, along with correlation and demographic analyses. Visualizations are included to make insights clear and easy to interpret.
* This analysis can help football scouts, team managers, and game developers understand player trends, evaluate talent, and make data-driven decisions.

# Dataset Information 
* Number of rows: 18,207 players
* Columns include:88
* ID - Unique player ID
* Name- Player’s name
* Age- Age of the player
* Nationality- Player’s Country of origin
* Club- Team
* Overall- Current rating
* Potential-Maximum rating
* Wage- salary
* Value- market value
* Physical attributes: Weight, Height
* Skills - Attributes 
* File Used: Game.xlsx
* Sheet Name: Game_data

* The data is stored in an Excel file (Game.xlsx) with a single sheet named Game_data. Some columns need preprocessing (like converting wages or weights to numeric values) before analysis.



# Insights
* Wage Distribution: Top clubs pay significantly higher wages; some players have unusually high wages (outliers).
* Potential Distribution: Most players have moderate potential; young players (16–20) show the highest growth potential.
* Correlation Analysis: Potential and wages are positively correlated — higher potential often comes with higher wages.
* Age by Position: Certain positions like goalkeepers tend to be older, while attacking players are generally younger.
* Skill Metrics vs Performance: Key skills like Dribbling, Finishing, and Passing strongly influence Overall and Potential ratings.

# Tools and Libraries I used :-
* Python: Core programming language
* Pandas: Data manipulation and analysis
* NumPy: For Numerical computations
* SciPy: Statistical functions and tests
* Matplotlib/Seaborn: Data visualization
* Excel: For reading the input dataset
