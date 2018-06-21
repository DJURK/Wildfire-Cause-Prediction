# Wildfire-Cause-Prediction
For this project, I attempted to create a model that could classify the cause of a fire.  About 25% of the wildfires in the database I looked at had their cause unidentified - I thought I could look at trends and gain insight toward what their potential causes could have been.  I began with looking at a baseline with the following features: Year of fire, month of fire, fire size, latitude/longitude, state, and owner of land burned (govt property, private property).    In my initial EDA, I found a couple interesting things: several causes of fires were extremely seasonal, different states have drastically different distributions of fire causes, and slightly more fires occurred on the weekend.  


## Strategy
1. Read and clean data
2. Initial modelling gave me results that weren't as useful as I wanted them to be
3. Changed scope to look at fires in California
4. Tuned hyperparameters for an xgboost model
5. Used my model to predict unlabeled fires in California
