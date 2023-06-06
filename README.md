# Python-Analysis-of-US-Presidential-Elections
Our project is an analysis of the 2016 and 2020 US presidential elections with a specific focus on the influence of specific demographic factors on voting outcomes. We have chosen this topic because we have both always had a very keen interest in politics as a whole and were particularly intrigued by the drama of the US presidential elections in 2016 and 2020. Our primary goal for this project was to gain a better of what demographic variables play the biggest role in determining election outcomes. We decided to use Jupyter Notebook as the base for our framework. 
One important thing to note regarding this topic is the fact that the USA uses an electoral college system in its presidential elections unlike most countries in Europe. This electoral college system assigns a certain number of votes to each state, a factor which often dictates results. 

The first step that we took in this process was brainstorming. We had to come up with the variables that we believed would be most important to look at in order to learn what influences people’s voting decisions. After some consideration, we decided that voter turnout, racial demographics, median age, average income, level of education, and crime rates were the variables that we wanted to look at. 

Data Retrieval
For the main data base of our project, we webscrapped election information from Wikipedia for both 2016 and 2020, using the Selenium package. 

Data Visualisation. 
For our first visualisation, we wanted to demonstrate the closeness of both elections, feeling as though a pie-chart from Matplotlib displayed this data in the clearest manner. We also felt the presence of the 3rd party, the Libertarains, was important to emphasise, with their percentage of votes being decisive in both elections. 

We also created a Geopandas visualisation for both election results to highlight the key battle grounds of both parties. 

Data Modelling 
For the modelling aspect of our project, we focused on the correlation between certain factors and the way people voted. We compiled a database of statistics manually, using statistics from reputable sources such as Census data and government websites. 
Our major findings were as follows: 
•	Higher voter turnout tends to favour Democrats and was a critical factor in the 2020 election. 
•	States with older populations tend to lean towards Republicans. 
•	Democratic states experienced considerably larger increases in income than Republican states between 2016 and 2020. This may have played a role in convincing swing state voters to vote blue. 

Taking our Project one step further: 
We wanted to focus on an individual state for our final aspect of the project, in the end choosing key swing state Wisconsin. We created a clustering model to categorise each individual county into either a rural or urban area based on their population density. The result clearly identifies the dominance of the Republican party in the vast majority of counties,  however this is still outweighed by the large populations in Democrat supporting areas.

In conclusion, we are both very happy with the outcome of our project. We really feel that we have accomplished our goals of both improving and displaying our Python skills and simultaneously gaining a better understanding of what factors influence the outcomes of elections. Beginning this module with very little experience in coding , we are proud of how far we have come and of how far our skills have developed. We are also both very grateful for all of the tremendous help we’ve been given throughout the semester :) 
