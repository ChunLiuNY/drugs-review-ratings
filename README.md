# Drugs Review Sentiment Analysis
Drugs.com is an online pharmaceutical encyclopedia that provides drug information for consumers and healthcare professionals. This analysis is based on drug reviews data from drugs.com. The goal of this analysis is to conduct sentiment analysis based on drug reviews by predicting customers' rating on specific drugs. 

## Dataset Description

The dataset is this analysis is publically available at [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29). The dataset provides 215K patient reviews on specific drugs along with related conditions and a 10 star patient rating reflecting overall patient satisfaction. The attributes in the dataset include name of drug, name of condition, patient review, 10 star patient rating, date of review entry and number of users who found review useful.  

### Exploratory Data Analysis

The distribution of reviews is imbalanced as most of reviews were 8-10 and 1 stars. 

![ratingsdistribution](https://user-images.githubusercontent.com/26207455/116010209-a5a6c600-a5eb-11eb-82e5-ac4f16743cbd.png)


Most reviews were related to side effects. 

![frequent_words](https://user-images.githubusercontent.com/26207455/116010635-31b9ed00-a5ee-11eb-98db-b5d65892183b.png)


Number of reviews per year. 

![reviewsperyear](https://user-images.githubusercontent.com/26207455/116010733-dccaa680-a5ee-11eb-8f88-44483e1af988.png)

Top 20 drugs with 10/10 rating.

![top20drugswith10rating](https://user-images.githubusercontent.com/26207455/116010818-7003dc00-a5ef-11eb-82b3-96e77a5aa411.png)


Top 20 drugs with 1/10 rating.

![top20drugswith1rating](https://user-images.githubusercontent.com/26207455/116010847-91fd5e80-a5ef-11eb-8087-aac64418abc2.png)


### LSTM

### Random Forest

### Model Performance

## Conclusion
