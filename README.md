# RiskEx-Data-Mining
## Toward a Better RSS Recomendation System

#### Introduction 
Part 1 of a collaborative project for identifying, processing, predicting and recommending relevant information (e.g. news artilces), to sophisticated traders. 

Project seeks to gather, model and recommend articles relevant to the decision making of asset traders. In particular, this repository is built around the processes required to perform the task of data mining. In particular:
    1) Web Scrapping and/or API utilization
    2) Metadata Extraction
    3) Preprocessing and Writing


#### Motivation
Information is of the utmost importance to traders throughout the world. Services such as Bloomberg's 'Terminal' are an imperative part of any trading house -- as they allow not only for execution of trades, but also for the sharing of information. RiskEx, seeks to build a product that focuses solely on the speed, veracity, value of the information shared. In doing so, we hope to equip traders with immediate and relevant information to their decision making.


#### Methodology
For this project we decided to split our overall scope into steps. This first step focuses solely on data acquisition, validation, cleaning, and preprocessing -- i.e. data mining. Moreover, our efforts for this part of the project are centered around the following:

    1) Variable websource scraping
    2) Deep level conent extraction (iterating over a single url's pages)
    3) Filtering of relevant content (user generated filtering)
    4) Preprocessing of content for modeling purposes
    5) Ensure robustness and flexibility of process -- so as to handle multiple asset classes


##### Notes on Methodology

1) Variable websource scraping: Process was built around a single website, using the html parsing package Beautiful Soup.  

2) Deep level content extraction: Is an expansion of process one. Our goal was to allow the user to specify a period (say two months prior to some event), to serve as the range of relevant information to scrape over - in a single url. 

3) Filtering of relevant content: To minimize computational load, and reduce data storage, this part of the process considers 'tags' given by the user as filtering consideration during scraping. 

4) Preprocessing of content for modeling purpose. During scraping iterations, our code automatically produces relevant metadata (date, author, keywords, etc.), as well some data preprocessing (remove null values, duplicates, etc.). Moreover, our code extracts content and formats it for further modeling purposes (such as bag-of-words from Natural Language Processing).  

5) Ensure robustness and flexibility of processes: our goal is to make our code into a system of black boxes, thus allowing for exportation into various languages or simple convertion of notebooks into scripts/executables.





#### Next Steps
Depending on time, and difficulty of this part of our process, further steps will involve the development of a learning recommender system build around both supervised and unsupervised learning methods (Part 2). Additionally, once parts 1 and 2 are completed, our following steps will involve the integration of our system into a chat bot, and allow for at-scale, and just-in-time data management and manipulation.





## Start Here:
Python was used for all data gathering, cleaning, and modeling purposes.

Multiple python notebooks (Jupyter) were written in order to carry out project. To execute our procedure follow the following in order:

1) Scrapping (in order):

    Rx1_request_read.ipynb
    
    <name to be included upon completion>
    
    <name to be included upon completion>
        
2) Recommender System (in no particular order): 

    <name to be included upon completion>	
    
    <name to be included upon completion>
  
    <name to be included upon completion>

3) Bot Integration and At-Scale Data Handling (in no particular order):

    <name to be included upon completion>
    
    <name to be included upon completion>
    
    <name to be included upon completion>
  
  
  
   

### A brief consideration:
##### Majority of labor associated with this project is consumed by data gathering and clean up. Should you choose to expand on our efforts, please reach out to any member directly and we can share the raw, preprocessed data sets we used to train our models. 

