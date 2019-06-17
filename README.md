# SpringBoard Capstone Project1

## Project Name: New York City Taxi Fare Prediction

### Problem Statement: predicting the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations

Who is your client and why do they care about this problem? In other words, what will your client do or decide based on your analysis that they wouldn’t have done otherwise?
 - The client receives a fare estimate inclusive of tolls when they add the destination. The fare estimate plays a important role in deciding which ride hailing app the potential client might end up using. More accurate predicitions means happy customers.

Data science Hypothesis(es)/solutions considering: One or multiple angles to consider solving this problem with data science. This could be as many as 10+ questions for what you are considering to solve through analysis, visualizations, and machine learning

 1) Density of pickups & Drop offs
 2) Fare Amount predictions

What data are you using? How will you acquire the data?
 1) Data sets to be used: API --> kaggle competitions download -c new-york-city-taxi-fare-prediction
 2) Link to the Kaggle Competition --> https://www.kaggle.com/c/new-york-city-taxi-fare-prediction

Data sets to be used: Share the links and files, .csvs, .js, .xlsx, .txt, website URLs. If you are usng web scraping or APIs, note the appropriate links and strategies here as well. Also describe how large are your data files and if you are concerned on any shortcomings of your data.

Potential business cases relative to project: improve accuracy & make better product

Potential stakeholders who would find this interesting: Ride hailing companies

Potential places to share your results post project (world, website)

What are your deliverables? Code, & a slide deck.

Briefly outline how you’ll solve this problem. Your approach may change later, but this is a good first step to get you thinking about a method and solution.

1) Frame the problem and look at the big picture
2) Get the data, create the work space. Do we need to create an isolated (virtualenv) environment in Python? 
3) Look at the data structure: like top five rows, bottom five rows, get the description of the data .info(), get the summary of the numerical attributes .describe(), plot the histogram for the entire project data using .hist(), look for Correlations.corr()
4) Create a Test Data Set and Training Data set: 80/20 rule
5) Prepare the data for Machine Learning Algorithms:
6) Data Cleaning:
   - Getting rid of some attributes which aren't useful
   - Getting rid of null values
   - <Adding more here>
7) Explore many different models and combine them
8) Fine-tune your models
9) Present the solution and repeat step 6-7 till you get better results 
10) Couple of factors which can affect my pricing/estimates:
   - Min/hr -- $15/hr
   - Congestion pricing - Same as Singapore (Tolls)
   - City bikes - Electric bikes share, car, electric scooters, taxi 

Data dictionaries to describe the data types you're using: 

