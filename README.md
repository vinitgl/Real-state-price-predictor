# Real-state-price-predictor

In the case of a Real Estate Investment Trust (REIT), which invests in houses and apartments in New York state, part of the REIT business
is try to predict the fair transaction price of a property before it's sold. They do so to calibrate their internal pricing models and 
keep a pulse on the market.

The REIT currently employs a third-party appraisal service for estimating the price of the property with their own expertise. 
In practice, the skill level of individual appraisers vary quite large.

To estimate the mis-priced range, the REIT run a trial run to compare the actual transaction prices to the estimates from the appraiser. 
It was found that the estimates given by inexperienced appraisers differs $70,000 on average.

They currently have an untapped dataset of transaction prices for previous properties on the market.
The data was collected in 2016.
Our task is to build a real-estate pricing model using that dataset.
If we can build a model to predict transaction prices with an average error of under US Dollars 70,000, then our client will be very
satisfied with the our resultant model.
