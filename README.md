# DS Growth Case Study

## Context: 
A user is looking for loans on Google and enters a search query. Depending on how related the search query is to FFN business, we choose to bid for the query with the goal of maximizing the user impressions using Google Adwords (Google actually showing the ad to the user when they execute the search). This would lead to more clicks on ads, and potentially more signups, activations, and revenue. Here activation is defined as a user successfully contacted by FFN call center.

## Questions:

1.	Using the dataset attached ‘clicks-activation_v2.csv’, build a model to predict the probability of activation per click.

2.	Please create a presentation using the following guidelines:
  -	Describe the workflow steps (explicitly setting up the optimization problem and choice of objective function) and your hypothesis.
  -	Evaluate the performance of the model (pre-production)?
  -	What are some of the shortcomings of this approach?
  -	What are some other features you might need to come up with a better model?

3.	What does the engineering architecture to productionize one of the solutions looks like? What trade-offs would you use to productionize promising algorithms faster?

4.	Discuss how will you analyze the business performance of the algorithm once in production using metrics such as marketing ROI etc.?

Each of the four parts above carry equal weightage in evaluation. We don’t think you need to spend more than 3 hours on the overall exercise (please feel free to take more time if you want). If you have questions please contact: azajic@freedomfinancialnetwork.com

## Data Dictionary:

1.	created_date - date on which the click was recorded
2.	location_in_query - city name that appeared in search query
3.	platform - platform such as web/mobile
4.	campaign_state - US state where the ad campaign was run
5.	in_city - whether the ad campaign was run in a city or not
6.	is_prime - whether the word fico prime appeared in the search query
7.	is_hardship - whether the word hardship appeared in the search query
8.	category_debt_type - type of debt solution that appeared in the search query
9.	[TARGET] is_activated – whether the user talked to FFN call center or not
