# The Titanic Dataset Data Exploration

## Dataset

The dataset containing fares and attributes for approximately 891 of the RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after it collided with an iceberg during its maiden voyage from Southampton to New York City. There were an estimated 2,224 passengers and crew aboard the ship, and more than 1,500 died.

Dataset: https://www.kaggle.com/c/titanic/data

The sinking of the Titanic is one of the most infamous shipwrecks in history.


## Summary of Findings

In the exploration, I found that there was a strong relationship between the
parent and siblinings, sum total of female in our dataset 233 Survived the and the remaining 81 died Sex: 
There were more males than females aboard the ship, roughly double the amount.Most of the women survived, and the majority of the male died in the shipwreck. So it looks like the saying “Woman and children first” actually applied in this scenario.
64.7% make up the population of men onboard in the ship while the remaining were women, the number include both adults and kids. 
Most of the people died in the shipwreck, only around 300 people survived in total.
Pclass: The majority of the people traveling, had tickets to the 3rd class. That is 1st class more likely survivied than other classes.
If one will look in the gender approach then one can say women were more likely to survive the accident.
Fare: Passenger with high fare has higher chance to survived the acciden

## Key Insights for Presentation

For the presentation, I focus on just the influence of the survival of passengersand leave out most of the intermediate derivations.
I'm most interested in figuring out what features are best for determine the sirvival of the travellers in the titanic dataset.
In this challenge, I'll try to answers the question: “what sorts of people were more likely to survive?” 
using passenger data (ie fare, age, gender, socio-economic class, etc). Afterwards, I introduce each of the categorical variables one by one. To start,
I use the heatmap plots to generally detect some anomalies.The deck shows most values to be null (Missing values)
and some values are null in the age field aswell, also 2 values messing in the embark_twon

Recommended questions & Visualization
Visual the survival of the titanic datase
Does the class of passenger play a role in Survival?
Does gender (sex) influence survival?
Does Age effect the chances of surviving?
Does Fare play a role in survial?

I start by visualizing the survived variable, followed by the passenger class (pclass), sex, age and fare 
using various plot types like, countplot, catplot, bar, boxplot etc. 
I've made sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.
