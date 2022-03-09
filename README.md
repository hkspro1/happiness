## Blogpost link: https://nycdatascience.com/blog/python/how-happy-is-the-world-can-data-answer-this-question/

I was motivated to do this analysis from my curiosity to understand how happy the world is and which countries are happiest and the least happy. Furthermore, I have assessed whether this data can help us identify the potential correlations with economic or social factors.

World Happiness Report is published every year with data on comparative happiness of countries. As this report is being published for many years, there is rich historical data already available. This EDA compares the trends over time, trends by geographical regions and the potential correlations of different variables with the Happiness Index.  The data includes around 140 countries, some countries are removed where the data was sparse or inconsistent and amounted to <5% of the world population.

The data mainly consists of the below metrics and the categorical variables are Country and Region.

Happiness score: This is the primary data point of the survey, gathered from the Cantril Ladder, where the respondents are asked to imagine themselves on a ladder with steps from zero to ten. Zero is worst possible and a ten is the best possible.
Log GDP per capita: GDP per capita is interns of Purchasing Power Parity ( PPP) adjusted to constant 2011 international dollars.
Social support: The national average of the binary responses ( 0= No, 1 = Yes) to the Gallup World Poll ( GWP) question, "If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?"
Healthy life expectancy: Health life expectancy at birth based on the data from WHO Global Health Observatory data repository.
Freedom to make life choices: It is the national average of binary responses to the GWP question, "Are you satisfied or dissatisfied with your freedom to choose what you do with your life?"
Generosity: It is the residual of regressing the national average of GWP responses to the question, "Have you donated money to a charity in the past month?"
Perceptions of corruption: It is the average of binary answers to two GWP questions, "Is corruption widespread throughout the government or not?" and "Is corruption widespread within businesses oar not?"
Specifically, These are the questions this article will try to answer

1) How 2021 Happiness score data compares to previous years?

2) How has Happiness varied over last 10 years across different regions?

3) How some of the national/ international issues impacted Happiness score? e.g. Has Covid-19 impacted the average happiness score of the world?

4) Which available variables shows high correlation with Happiness Score?

5) What inferences can be drawn from this analysis? e.g. Can you decide to relocate to a happier place based on this analysis?

6) How this analysis can be improved?
