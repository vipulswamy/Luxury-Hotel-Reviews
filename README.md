![alt text](https://besserlaengerleben.at/wp-content/uploads/2014/03/LOBBY-LOUNGE1.jpg)
##### **this image is for illustration purpose only and it belongs to the respective owners**
# Luxury Hotel review Analysis

As a Business Analyst for an independent Agency that curates, reviews, rates and consult Luxury Hotels in Europe, I have used multiple data Analysis Tools and processes to assess and evaluate the Businesses in this category. The following are the 2 points agenda of this work:
1. Understand the reason for a high review rates
2. Provide solution to the ones with average reviews

## Contents
1. Business Objective - an NLP problem with Sentiment analysis & Business solution
2. Data gathering, merging, Data cleaning and EDA
3. Bag of words
4. Tokenization, text cleaning, stemming, Lemmatization
5. TF-IDF Transformation
6. Train test split
7. Applying classification or predictive model based on the end goal
8. Evaluation and reporting

Note: certain parts of the codes were built on an environment in Anaconda Navigator, while the rest of the notebook-codes were built using google-collab due to limitations of Libraries on Jupyter Notebook

## Business Objective
To gain insights into the hotel reviews and understand the customers' feelings and feedback more accurately, 
we needed to understand the customer opinions and segmentation in our dataset with the available data.

Additionally, 
the large corpus of customer feedback makes it time-consuming to manually review them to capture customers' preferences and pain points. 
Therefore, we also proceeded to analyze the review texts with Natural Language Processing techniques to understand the intrinsic feelings and emotions behind reviews and recognize which aspects of the hotel required improvements.

## Data Description
Coloumns: 17,rows: 515738, size: 227 MB 

-data set Fields:
* Hotel_Address
* Additional_Number_of_Scoring
* Review_Date
* Average_Score
* Hotel_Name
* Reviewer_Nationality
* Negative_Review
* Review_Total_Negative_Word_Counts
* Total_Number_of_Reviews
* Positive_Review
* Review_Total_Positive_Word_Counts
* Total_Number_of_Reviews_Reviewer_Has_Given
* Reviewer_Score
* Tags
* days_since_review
* lat(lattitude)
* lng(longitude)


## Sources
* Hotel image: https://besserlaengerleben.at/reisen/hoteltipps/ein-ausergewohnliche-5-sterne-hotel.html
* data Source: https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe

