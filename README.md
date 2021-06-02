# Project Nvidia - Real or Not? NLP with Disaster Tweets

## Data Mining and Machine Learning - University of Lausanne

### :pencil: Project description

In this project we are challenged to build a Machine Learning model that can predict which tweets are about real disasters and which are not. The
project topic is based around a Kaggle competition. We have a training set with tweets and the information of it is a real disaster or a fake news. 
The goal is to train this model to have the best accuracy we can on the test set that is located on [AICROWD](https://www.aicrowd.com/challenges/final-project-of-the-data-mining-and-machine-learning-course). 
Each teams can make up to 5 submission a day and then see it's accuracy and it's ranking. We can see the results of our fellow and makes the challenge even more competitive!


### :books: Data

The training set is composed of 6471 tweets that was uploaded to our colab project. 
As we have built different models and trained it on the training data, we generated predictions for the (unlabelled) test data.
We made sure that our submission file had the correct format as it was recommended on AICrowd - CSV format.
We then tried each week to train our models differently and with more complex functions in order to improve the test set accuracy.


### :calendar: Weekly project progress

- Week 1 
  - Created the GitHub repository
  - Created the colab project linked to the GitHub repository
  - Uploaded the data on the colab project
  - Cleaned a first time the dataframe
  - Visualization of the dataframe with some EDA functions
  - Trained the dataframe
  - Calculated a 1st value with Logistic regression with and without Cross Validation
  - Submited our 1st prediction on AICrowd

- Week 2: 
  - Calculated the base rate
  - Further cleaning and merging of keywords with the text
  - Calculated optimal Logistic regression parameters without the merged keywords
  - Calculated optimal Logistic regression parameters with the merged keywords
  - Updated the readme file
  
- Week 3:
  - Calculated optimal TFID - vector -> Overfitting
  - Merged optimal Log regression and tfidf parameters -> Overfitting
  - Pipeline function with standardization
  - Completed the readme file
  - Arranged and cleaned our code on colab

- Last Week:
  - Regex function - removed hyperlinks, removed special characters
  - Final Version of the readme file
  - Final Version of the code

### :bulb: Results

- [x] 1st Week:  0.81
- [x] 2nd Week:  0.823
- [x] 3rd Week:  0.8169
- [x] Last Week: 0.8185

The best results was obtained during Week 2, with the accuracy of 0.823 :white_check_mark:

:movie_camera: Follow the project presentation with our [YouTube](https://www.youtube.com/watch?v=XspXjrlGmkk&feature=youtu.be&ab_channel=IgOr) video

