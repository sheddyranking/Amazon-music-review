# Amazon musical Instrument Reviews 
Sentiment Analysis  Project on Amazon-musical-instrument-review using Python 

### Project Workflow
1.import needed libarries 

2.load dataset

3.check dataset info

4.Preprocessing and data cleansing

>   Check Null values and Fillna

5.Deciding on the Nature of the dataset

>   get overall rating distribution/count

>   combine reviewText and summary and drop the column from the DataFrame.

6.Create Sentiment column

>   Write a function using rating

>   apply the function on the sentiment column

>   Sentiment Count

7.Split the date

>   split date and year on semi-colon Delimeter

>   Split date column on Space delimetre.

8.review count distribution over the years

9.group sentiment size by years

10.remove unneccesary 






### Problem statement.
This is the Problem Statement given by ISRO to classify the customer comments. This would be helpful for the organization to understand Customer feedbacks.
Webportals like Bhuvan get vast amount of feedback from the users. To go through all the feedback's can be a tedious job. You have to categorize opinions expressed in feedback forums. This can be utilized for feedback management system. We Classification of individual comments/reviews.and we also determining overall rating based on individual comments/reviews. So that company can get a complete idea on feedback's provided by customers and can take care on those particular fields. This makes more loyal Customers to the company, increase in business , fame ,brand value ,profits.

### Project Objective
1.Reviews Preprocessing and Cleaning

2.EDA Visualization from reviews
### Dataset Attributes
This dataset has reviewer ID , User ID, Reviewer Name, Reviewer text, helpful, Summary(obtained from Reviewer text), Overall Rating on a scale 5 and Review time.

Description of columns in the file:

1.reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B

2.asin - ID of the product, e.g. 0000013714

3.reviewerName - name of the reviewer

4.helpful - helpfulness rating of the review, e.g. 2/3

5.reviewText - text of the review

6.overall - rating of the product

7.summary - summary of the review

8.unixReviewTime - time of the review (unix time)

9.reviewTime - time of the review (raw)


### Deciding on nature of Sentiment
The sentiments of review is decided on the overall score. It means that

1.if the score is greater than 3, the sentiment is Positive
2.if the value is less than 3, the sentiment is Negative
3.and if it is equal to 3, the sentiment is Neutral.


# TO BE CONTINUED 
