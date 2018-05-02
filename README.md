# RiskEx-News and Their Effect on Bitcoin Price
## Toward a Better RSS Recomendation System



### Introduction and Motivation

News events continue to be of outmost importance during the price discovery process of any asset. Some news events -- such as press releases -- have been found to represent a potential explanation for up to 24% of an asset's price movements. We seek to understand and classify what causes a news event to have a statistically significant effect on price. In particular, we aim to implement machine learning (ML) processes, and Natural Language Processing (NLP) techniques to extract what traders intuitively know when they choose which news articles/publications/news-beats to listen to, and consequently base their trading decisions on. 

The following represent a collaborative project for identifying, processing, predicting, and recommending relevant information from news events to sophisticated traders.



### Methodology
For this project we decided to split our overall scope into three steps. 
 
#### I. Data Cleaning
    1) Web Scrapping and/or API utilization
    2) IMetadata Extraction
    3) Preprocessing and Writing

#### II. NLP Modeling and Time Series Analysis
    1) Filtering of relevant content 
    2) Preprocessing of content for modeling purposes

#### III. Analysize and Classify
    1) Perform Clustering Analysis
    2) Classify events based on sentiment analysis
    3) Establish a causal relationship between a news even and its effect on the price of bitcoin 



### Next Steps
Further steps will involve the development of a learning recommender system built around both supervised and unsupervised learning methods. In particular, based on the foundation establish by our team, we believe the following projects could readily be implemented to increase the robustness and capacity of our model.

    1. Acheive better granularity of data - create series of crawlers that extract the desired granular data.
       1.a Examples include: pricing data, google trend data, etc.  
    2. Create two tiers of data acquisition processes.
       2.a Broad spectrum crawlers should be scheduled to stay up to data with current events, while minimizing load. 
       2.b Event driven crawlers should be developed around predictive modeling and/or event detection.
    3. Implement a predictive pricing model for asset classes. 
       3.a Use pricing predictions to trigger searches for relevant articles, and evaluate pricing and recommender models.
       3.b Predictive pricing models could also be used for arbitrage purposes, and optimization of LOB processes.
    4. Implement a distributive compuatition architecture
       4.a In order to implement just-in-time analysis, future team will nead to export processes to cloud.
    5. Increase the quality of prediction by instituting a magnitude/directional component to our time series modeling.



## Start Here:
Python was used for all data gathering, cleaning, and modeling purposes.

Multiple python notebooks (Jupyter) were written in order to carry out project. To execute our procedure follow the following in order:

1) Scrapping (in order):

    news_to_features(1o3)
    
    url_to_contents(2o3)
    
    many_df_to_one(3o3)
        
2) Time Series Modeling and Event Detection (in no particular order): 

    <name to be included upon completion>	
    
    <name to be included upon completion>
  
    <name to be included upon completion>

3) Natural Language Processing and Formulations:

    <name to be included upon completion>
    
    <name to be included upon completion>
    
    <name to be included upon completion>
  
  
  
   

### A brief consideration:
##### Majority of labor associated with this project is consumed by data gathering and clean up. Should you choose to expand on our efforts, please reach out to any member directly and we can share the preprocessed and cleaned data sets we used to train our models. 
