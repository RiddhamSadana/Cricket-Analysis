# Cricket-Analysis
## It is a short project that analyses cricket data for 6 international teams over the years 1990-2019 and looks for a correlation in Test and ODI win percentage.

## Results:
#### Scatter Plot:The visual shows the scatter plots (win percentages) for six cricket playing nations using the match results data for the years 1990-2019 in both test and one-day cricket.
#### Win percentage for each year from 1990 to 2019 was calculated for different teams in both test and one-day matches. scatter plots are then drawn with each point corresponding to a particular year as represented in the colorbar.

## Interpretation:
#### It can be clearly interpreted from the visual that there exists no direct or significant correlation between the test and odi win percentages for the teams. Though for some teams like India, odi and test win % percentage seem to be correlated but for most of the other teams, the plots appear pretty scattered around. Thus, a good test playing nation might not play good one-day cricket in the same year and vice-versa.

## Cairo's Principles:
#### Truthfulness : Data is taken only for the nations playing pretty regular and consistent odi and test cricket. Also, to take sufficient number of matches per year for finding the win %, I have considered data from the year 1990 onwards. Thus, the data presents a true picture of the scenario. I have considered matches that had a result to avoid misleading representations

#### Beauty : I have tried to make it look pleasing by using subplots to avoid multiple x and y axes for each subplot. I have carefully customized the locations of title, labels and also made the plot pretty much square-like. Also, I have used a custom colorbar for the plot to avoid very light colors.

#### Functionality : I used scatter plots for answering the question as they are appropriate for finding the correlation between two variables and easily understandable to the reader. Also, I added a colorbar in case, one wants to see the performance of teams over the years in test/odi cricket.

#### Insightfulness : Well, I tried my best to make the plot look really symmetric and used custom style 'seaborn-colorblind' to make it look attractive to the eye. I will try and learn to incorporate more insightfulness into my plots in future.
