# Classification-Data-Challenge -  April 2020
Company Y is a B2B insurance company offereing employee benefits products to employers across the US
Company Y would like to use machine learning models to suggest best strategy for increasing sales of productX across the US
# Scope
* Three type of data provided. These are employers, geographical, and sales data
* Augmented data provided by blending with US Census Bureau zipcode level data on County Business Patterns
# Vision
* Predict sale success ("sold" or "lost") of ProductX based on features provided
* Find best model and most important features
# Impact
* Employees and ClientTenure are consistently the most importances features in all tree-based models
* Results suggests targeting employers whose ClientTenure is low for increased sales of ProductX. Probaliity of sales success sharply drops by 60% with increase in client tenure from 0 to 3.5 years
* Partial dependence plot shows an initial linear relationship between sale success and employee headcount with a sharp downward trend starting from circa 60 Employees. **This suggests higher payoff when targeting micro, small and medium employers**
