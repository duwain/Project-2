Car Insurance
Author: Duwain Hofmeester

Business problem: We have to determine the outcome of a customer's behaviour based on the different features.

Dataset name: Car_Insurance_Claim.csv

The dataset cosnsist of the following:
There are 10000 rows, and 19 columns.
The rows represent 10000 observations, and the columns represent 18 features and 1 target variable.

RangeIndex: 10000 entries, 0 to 9999
Data columns (total 19 columns):
 #   Column               Non-Null Count  Dtype  
---  ------               --------------  -----  
 0   ID                   10000 non-null  int64  
 1   AGE                  10000 non-null  object 
 2   GENDER               10000 non-null  object 
 3   RACE                 10000 non-null  object 
 4   DRIVING_EXPERIENCE   10000 non-null  object 
 5   EDUCATION            10000 non-null  object 
 6   INCOME               10000 non-null  object 
 7   CREDIT_SCORE         9018 non-null   float64
 8   VEHICLE_OWNERSHIP    10000 non-null  float64
 9   VEHICLE_YEAR         10000 non-null  object 
 10  MARRIED              10000 non-null  float64
 11  CHILDREN             10000 non-null  float64
 12  POSTAL_CODE          10000 non-null  int64  
 13  ANNUAL_MILEAGE       9043 non-null   float64
 14  VEHICLE_TYPE         10000 non-null  object 
 15  SPEEDING_VIOLATIONS  10000 non-null  int64  
 16  DUIS                 10000 non-null  int64  
 17  PAST_ACCIDENTS       10000 non-null  int64  
 18  OUTCOME              10000 non-null  float64
 
Methods Check for duplicate rows- Duplicate rows can impact the qaulity of your analysis and lead to decrease insights, and potentially cause erros in machine learning.![image](https://github.com/duwain/Project-2/assets/53176086/dc02f89c-16b9-4aa9-b40b-00330ac9f8ed)

Sample image Check for Null values in the categorical columns and the numeric columns. If any null values are found in the categorical columns we will replace it with the most occuring value If any null values are found in the numerical columns we will replace it with the mean vaule

Analysis
![image](https://github.com/duwain/Project-2/assets/53176086/dcfe9144-1034-4806-a9c3-613a35f6b8d5)
We can see from the graph above that the more driving experience the customer has, the less likely it will be for them to process a claim.

![image](https://github.com/duwain/Project-2/assets/53176086/dcd392a9-7bf1-488c-ad7f-3a739ad3822f)
In the graph above we can see that the more annual mileage a customer has on his/her vehiche the more likely they will be to process a claim/loan.


Model metrics Results for testing data on best performing model:
![image](https://github.com/duwain/Project-2/assets/53176086/9d498a2b-facc-4920-9a34-6d433857afa8)

How will the model solve the business problem: The model will assist with identifying high risk customers (customers likely to process a claim). This information can be use to formulate a premium that will benefit the organisation and satify the customer's needs. 
It also elimate the manual process of evaluating the likelihood of a customer processing a claim. 


For further information Duwain4@gmail.com
