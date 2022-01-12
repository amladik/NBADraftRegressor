# NBADraftRegressor
A Regression Model trained on previous NBA Draft Statistics to predict a future NBA player's rank in the NBA Draft

# Data Source
Used beautifulSoup to webscrape data from https://www.sports-reference.com/cbb/players. This website contains all essential data related to all NCAA Basketball Players

# Models/Tools Used
This project utilizes Ridge Regression in order to fully take into account all of the features of the data. Lasso regression and other regression models focused too heavily on certain features, and produced innacurate results. For Data Visualization, Seaborn was used

# Results
The model projected Paolo Banchero to go as the first overall pick, Chet Holmgren to go as the second overall pick, and Azuolas Tubelis to go as the third overall pick. These results are similar to many projections of the 2022 draft, but can only be truly tested on draft night in September.

# Future Improvements
One important addition to this project is solving the problem of overfitting by implementing cross-validation. Additionally, feature selection and feature redundancy are issues that also must be addressed. The current hyperparameters provide the strongest results, so there is a possibility of improvement with the data preparation.
