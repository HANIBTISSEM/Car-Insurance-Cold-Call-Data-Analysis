# **Car Insurance Cold Call Data Analysis** 

<p align="center"> 
    <img src="https://challengemyrate.com/wp-content/uploads/2019/01/INSURANCE-AUTO_ALPHA.gif" alt="drawing" width="600"/> </p>


This dataset comes from an American bank that offers car insurance in addition to its standard services. This bank has potential customers’ data, and bank employees call them for advertising available car insurance options.




* This dataset contains general customer data (age, employment, etc.), as well as more detailed information on the current insurance sales campaign (communication, last contact day), as well as data from earlier campaigns (attributes like previous attempts, outcome).

* This dataset has two subsets,one to train the model(training set) and another subset to test the trained model.

* The task is to predict for 1000 customers (test set) who were contacted during the current campaign, whether they will buy car insurance or not.

___
# TABLE OF CONTENTS
___


[1. EXPLORATORY DATA ANALYSIS](#1) 
> [1.1. Discrete Variables](#11)   
   >> [1.1.1. The Column Names](#111)        
   >> [1.1.2. The Datatypes of the Numerical Columns](#112)     
   >> [1.1.3. Is There Any Missing Data?](#113)   
   >> [1.1.4. The Statistics of the Discrete features](#114)       
   >> [1.1.5  The Statistical Analysis](#115) 
   
> [1.2. Categorical Variables](#12) 
   >> [1.2.1. The Column Names ](#121)       
   >> [1.2.2. The Datatypes of the Numerical Columns](#122)       
   >> [1.2.3. Is There Any Missing Data?](#123)       
   >> [1.2.4. The Statistics of the Discrete Features](#124)       
   >> [1.2.5.  The Statistical Analysis](#125)
        
> [1.3. Understand the Shape of the Data](#13) 
       >> [1.3.1. Discrete Variables](#131)  
       >> [1.3.2. Categorical Variables](#132)  
  

[2. OUTLIER ANALYSIS](#2)

[3. HANDLING MISSING VALUES](#3)

[4. CORRELATION ](#4)
> [4.1. Pearson's correlation](#41)

> [4.2. Spearman's correlation](#42)



[5. DATA VISUALIZATION](#5)
> [5.1. Categorical Variables Visualization](#51)  
   >> [5.1.1. Plots & Graphs](#511)    
   >> [5.1.2. Plot Interpretation](#512)   

> [5.2. Discrete Variables Visualization](#52)  
   >> [5.2.1. Plots & Graphs](#521)   
   >> [5.2.2. Plot Interpretation](#522)






[6. FEATURE ENGINEERING](#6)

[7. MODEL DEVELOPMENT](#7)
   >> [7.1. Classification Algorithms](#71)   
   >> [7.2. Features Importance](#72)

[8. FINAL INTERPRETATION](#8)
   >> [8.1. Target Clients](#81)   
   >> [8.2. Insightful Suggestions](#82)
_______________________________
