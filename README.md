### <a id='overview'>1. Overview</a>

#### Motivation
- To detect transaction pattern across multiple factors (age, gender, transaction type) in an anonymized data from a Czeck bank with 1M+ transactions and 5k+ clients  

#### Method
- SQL and pandas are used for ET
- Visulization are created with matplotlib and seaborn

### <a id='sam'>2. About the author: Kam Leung Yeung (Sam)</a>
* PhD in Cognitive Psychology, Iowa State University in Ames, Iowa, USA

**Social media**:

* [LinkedIn](https://www.linkedin.com/in/kamleungyeung/)
* [Google Scholar](https://scholar.google.com/citations?user=OwUmaN8AAAAJ)
* [GitHub](https://github.com/k-l-yeung)
* [Tableau](https://public.tableau.com/app/profile/kam.leung.yeung#!/)

About the dataset 
- Anonymized data with 5k+ clients and **1M+** transactions records from a Czeck bank
- [1999 Czech Financial Dataset - Real Anonymized Transactions](https://data.world/lpetrocelli/some-translatedreformatted-czech-banking-data)
- More details about the goal of the dataset creation. [[1]](https://webpages.charlotte.edu/mirsad/itcs6265/group1/index.html)[[2]](https://data.world/lpetrocelli/czech-bank-beginner-r-analysis/workspace/project-summary?agentid=lpetrocelli&datasetid=czech-financial-dataset-real-anonymized-transactions)

### <a id='toc'>3. Table of content</a>

1. <a href='#overview'>Overview</a>  
2. <a href='#sam'>About the author: Kam Leung Yeung</a> 
3. <a href='#toc'>Table of content</a> 
4. <a href='#function'>Functions for EDA</a> 
5. <a href='#eda'>Data exploration</a>  
 - <a href='#missing_plot'>Plots of missing data pattern</a>  
 - <a href='#format'>A brief look at the dataset, recoding, and renaming</a>  
     - account table 
     - card table 
     - client table 
     - disp table 
     - transaction table
6. <a href='#q'>Decteing transactional patterns</a>
    - <a href='#typedemo'>Type of account and demographics</a> 
    - <a href='#trans_patt'>Deposit and withdrawl pattern across 
        - gender
        - age group
        - type of accounts one hold </a>
        - <a href='#patt_time'>Balance pattern across time </a>
