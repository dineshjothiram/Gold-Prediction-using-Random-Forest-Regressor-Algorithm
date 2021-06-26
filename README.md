# Gold Price Prediction using Random Forest Regressor Algorithm | Python

**Necessary Python Libraries**

    Numpy
 
     Pandas
 
     MatplotLib
 
     Seaborn
 
    SKlearn
 
**Work Flow **

1.Gold Price Data set

    Data set is contain 2289 Rowns and 6 Columns(Data,SPX,GLD,USO,SLV,EUR/USD)
   
2.Data Pre Processing

     Loading CSV data into Data frame.
 
    Checking Missing values,Statistical Measures of the Data frame.
   
3.Data Analysis

     Analysing Correlation of data by Heat Map.
    
4.Train Test Split

    Features - SPX,GLD,USO,SLV,EUR/USD
   
     Target   - GLD
  
     Train data size - 80%
   
    Test  data size - 20%
   
5.Random Forest Regressor

    Working by constructing several decision trees during the training traing time.
  
    Fit Random Forest Regressor to Data set.
  
6.Evaluation

    R Squared Error : 0.9891333556597924
  
    There is no specific analysis for R squared error.
  
    But this is good result for our  Data set.
