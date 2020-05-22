# 170-Project-Social-Media-Sentiment-Analysis-vs.-Approval-Rate

To review the project as described in submission requirement, please use the notebook file in Demo folder and do not change structure of folders.


All the Jupyter notebooks of this project are in Scrpts folder.
  1. Data Collection and peek: 
      Using Twitter and Reddit API to collect data about COVID-19 and Trump. And reading the given twitter date and save them into database. And to do simple visualization of the datesets. (Don't run withour DB)
  2. ML emotion detection: 
      NLP preprocessing and using the train, dev, and test dataset in the root folder, to build models and save them into file. Caution: Don't run the BERT module in this part, or it will take several hours to finish word embedding.
  3. Data Classification and extraction:
      Extract data from Database and do the NLP preprocessing and using VADER and our trained model to classify and aggreate the daily data, and building the word vector for the SVP models.
  4. Plot and Analysis
      Using the aggregated data to exploring the data and building models and making prediction and evaluate each model. (Data for building linear regression and Autoregression model is included in the same folder, but the data for two SVP models are not, because of the size of word vector is too large to be put on github.)

                                              
