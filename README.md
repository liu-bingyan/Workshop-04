# Workshop-04

## Analysis of Movie Reviews
Users’ movie reviews can influence our decision to watch or not and hence affect the movie’s commercial success. In this project you will use natural language processing and other workshop techniques to better understand a dataset of movie reviews, writing predictive models that can classify the reviews into interesting categories.

### Data access 
The data for this project is provided at the following Kaggle site: 
https://www.kaggle.com/rmisra/imdb-spoiler-dataset 
You may use the internet to find additional information or comparison datasets. Note that this data is in json format, so you will want to look into the python json package.

### Understanding the data
Start by spending some significant time just understanding the large amounts of information in the data set, calculating statistics, and making a range of histograms and other plots. In this exploratory phase you’ll likely learn the answers to lots of interesting questions. For example:

 - What is the distribution of ratings? Release dates? Durations? etc.
 - What are the most common terms appearing in the movie reviews?  
 - How do the terms in the movie reviews compare to other text datasets (e.g., the email dataset from Workshop #3)? 
 - Are there trends between, for example, duration and rating?

### Making predictions

Split the dataset into training, test, and validation samples. Using the training data, write predictive models that predict, e.g., whether or not a given review contains a spoiler (which is the suggested question on Kaggle). However, you do not need to limit yourself to this question! You may consider choosing one of the following scenarios:

- Imagine you are a streaming content provider trying to understand what aspects of movies make people give higher review ratings. Write a model that predicts the review rating based on duration, genre, the content of the review, and other available information.
- Imagine you work for the Writers Guild of America, and want to provide statistical guidance on what plot elements lead to high reviews. Write a model that predicts review score based on plot synopsis, or that predicts elements of a synopsis based on positive or negative reviews. 
- Imagine you work for a data mining company and want to understand the ways in which reviews cluster together. Use various learning methods to cluster reviews, and to interpret your results.
- Imagine you are a review website that wants to hide spoilers. Write a predictive model for whether or not a review contains a spoiler.

This is not an exhaustive list of directions you could take the project. As you explore the data, you may come up with other ideas or things you want to predict. Have fun!

## Models
NLP models on spoiler detecter
- use the trained model https://huggingface.co/bhavyagiri/roberta-base-finetuned-imdb-spoilers
    -- improve it using some preprocess
- train the reberta model
- using the models on Kaggle site
- build our own model following the workflow:
    -- tokenization
    -- vectorization
    -- feature engineering
    -- models on the vectorization embedding
        --- XGBoost
        --- DL models

NLP models on sentimental detection

NLP models : predict genre using reviews

