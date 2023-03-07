
# Innovation Challenge: PepsiCo Data Science 2022 Challenge
### By Zahra Adahman
#### 22nd October 2022
https://www.nyas.org/challenges/pepsico-2022-challenge/?tab=overview
### Data Challenge
Build  a model to predict what products from what countries are likely to be have the most added sugars using the dataset provided by PepsiCo.
Data was provided in .csv file format. Data was wrangled and cleaned. Missing data was removed and 20 features out of 204 feature were selected based on criteria of missing values.
![image](https://user-images.githubusercontent.com/59964869/223546423-8e4a003d-7f83-4d38-8587-f6486f31174e.png)
#### Features
![image](https://user-images.githubusercontent.com/59964869/223546591-40de10df-bda8-43fd-827d-d2c3964c6c33.png)
#### Correlation analysis
![image](https://user-images.githubusercontent.com/59964869/223546795-c6c57974-d403-405d-9958-4057d2be1d83.png)
![image](https://user-images.githubusercontent.com/59964869/223546899-ac0ea294-b459-4f0d-a788-0de0b2a84ba5.png)
#### Data classification
Added sugar feature was classified into three groups based on FDA recommendations
![image](https://user-images.githubusercontent.com/59964869/223547264-de9f3fb4-26ce-4d36-bab8-041ec673b635.png)
![image](https://user-images.githubusercontent.com/59964869/223547595-fc59438d-3017-4548-8d54-dd476b02f28b.png)
#### Looking for the best classification model
![image](https://user-images.githubusercontent.com/59964869/223549025-ec81d4d8-7a7c-4d9c-b36e-7d2a927058c1.png)

## Decision Tree
## Of Test Dataset
![image](https://user-images.githubusercontent.com/59964869/223555225-4e8d8704-9b21-4362-8bdc-5a6e62b7fdf5.png)
## Of Train Dataset
![image](https://user-images.githubusercontent.com/59964869/223557244-8c739b77-c0b4-45ae-b09d-a45a86f48ab3.png)

![image](https://user-images.githubusercontent.com/59964869/223549526-ba5d85b8-0bcf-42e3-942f-0184f448439f.png)
### The dataset has some shotcomings which may have affected the analysis. There are a lot of missing data and incomplete profiles for each data entry (about 80%). This led to over 180 features to be discarded for the modeling. Considering only about 20% of the orginal dataset was used for the modeling. The 80% of data being removed for a complete dataset could be the reason for the model drift observed when the test and train decison trees predict different countries for products with low sugar content. 
