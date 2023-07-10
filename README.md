# Amazon_review_analysis

## This notebook is designed for the analysis of Amazon review data, aiming to identify patterns in customer reviews using NLP techniques and visualization.

## Table of Contents

1. Data Loading and Preprocessing

2. Exploratory Data Analysis<br>
   2.1 Summary Statistics<br>
   2.2 Rating Distribution<br>
   2.3 Correlation between Rating and Helpful Votes<br>
   2.4 Number of reviews per year<br>
   2.5 Average review score per year

3. Top 10 and Worst 10 Products by Rating

4. Visualization of Top 10 and Bottom 10 Products

5. Word Count Analysis and Visualization<br>
   5.1 Word Counts of Whole Review<br>
   5.2 Average Rating for Each Word<br>
   5.3 Most common words in low rating reviews<br>
   5.4 Most common words exclusively appear on bad reviews<br>
   5.5 Differences Between Good and Bad Reviews<br>
   5.6 Differences Between Helpful and Non-Helpful Reviews

Data Origin: https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews
<small>
The dataset contains the following columns:

- Id: The ID of the review. 
- ProductId: The ID of the product.
- UserId: The ID of the user.
- ProfileName: The name of the user.
- HelpfulnessNumerator: Number of users who found the review helpful.
- HelpfulnessDenominator: Number of users who indicated whether they found the review helpful.
- Score: The rating of the product.
- Time: The time of the review (in Unix time).
- Summary: A brief summary of the review.
- Text: The text of the review.
</small>
