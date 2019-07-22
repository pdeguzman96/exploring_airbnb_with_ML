# Exploring Airbnb Listings Datasets

**What's the point of this project?**

Arguably, one of the most important steps in a data science/machine learning project is communicating results. Why go through the trouble of doing all this work if findings and/or results aren't communicated with others? This project was created to practice wrangling a dataset and find interesting things in the data that can tell us something useful about the reality it represents. 

---

Data Source: [insideairbnb.com](http://insideairbnb.com/get-the-data.html)

[My blog post](https://medium.com/@patrickjohnyudeguzman/digging-for-gold-in-airbnb-datasets-2ae10f1a7054?sk=1cc9261994d82e321f77d1026a581e36) for this analysis.

Analysis can be found in the Airbnb.ipynb and/or the Airbnb.html files.

---

## Project Description

This is a simple data analysis & machine learning project. In this Jupyter Notebook, I analyzed the following 3 Airbnb listings datasets.

1. San Francisco, CA
2. New York, NY
3. Austin, TX

I used *Exploratory Data Analysis* techniques and some *machine learning* algorithms to answer the following three questions...

1. What are the strongest predictors for Airbnb listing price?
2. Do hosts with many properties give better or worse service than hosts with only one?
3. Do reviews matter when considering price?

In the analysis, I explain my thought processes and decisions as I go. I hope you find this interesting and useful!

**TL;DR?** Here are my findings from these datasets...
1. I saw that hosts with only one listing are rated slightly higher than hosts with more than one listing.
2. I saw that hosts with no recent reviews are priced slightly higher than hosts with recent reviews, and as a bonus, I saw that Superhosts are typically more expensive than non-Superhosts.
3. I found that the size of the property, whether or not the property is an Apartment in NY, and luxurious amenities were all strong predictors of the price.

---

## Repository Contents

- Airbnb.ipynb : Jupyter notebook containing analysis
- Airbnb.html : HTML-friendly version of the notebook above
- .gitignore : used to prevent committing datasets and ipynb checkpoints to repo

---

## Dependencies

**Machine Learning**
- sklearn

**Visualization**
- plotly
- plotly_express
- seaborn
- matplotlib

**Data Analysis**
- pandas
- numpy
- scipy
- category_encoders
- math
- collections
- datetime

---

## Acknowledgements

- insideairbnb.com for collecting the data
- Airbnb for creating the data, and allowing it to be publicly accessible
- Udacity for the project idea and the feedback
- Contributers to the libraries I leveraged above 