# Capstone-Project-3---Mobile-Price-Range-Prediction


![image](https://github.com/Alisyed098/Capstone-Project-3---Mobile-Price-Range-Prediction/assets/134094832/19a78b11-e179-4591-970b-ca60db5a1311)

Mobile Price Range Prediction is a crucial task in the smartphone industry. By using machine learning techniques, we can analyze the features of mobile phones and predict their price ranges accurately. This project provides a framework to build and evaluate such prediction models.

Built a Multi-Class classification model to find the relation between features of a mobile phone(RAM, Internal Memory etc) and its selling price. Model will predict the price range indicating how high the price is.

pip install -r requirements.txt

It is recommended to use a new environment before running the pip install.

The dataset consists of csv file: data_mobile_price_range.csv

Data Files:

data_mobile_price_range.csv holds info , specification & price range of mobile phones

The repo contains main.py that runs the main script from step one until the end.

1. **Business Problem**

      In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price.

In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

2. **Solution Strategy**

      My strategy to solve this challenge was:
      
      Step 01: **Data Description**- Use statistics metrics to identify data distributions.
      
      Step 02: **Feature Engineering**: Derive new attributes based on the original variables to better describe the phenomenon that will be model.
      
      Step 03: **Exploratory Data Analysis**: Explore the data to find insights and better understand the impact of variables on model learning.
      
      Step 04: **Feature Selection**: Selection of the most significant attributes for training the model.
      
      Step 05: **Machine Learning Modelling**: Machine Learning model training.
      
      Step 06: **Cross Validation & Hyperparameter Tuning**: choose the best values for each of the parameters of the model selected from the previous step.
      
      Step 07: **Convert Model Performance to Business Values**: Convert the performance of the Machine Learning model into a business result.
      
      Step 08: **Deploy Model to Production**: Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.

3. **Data Insights**

      * I found that mobile phones with more ram are usually having higher cost.
      * Battery does not necessarily improve by increasing the Ram of the mobile phones.
      
      

4. **Machine Learning Models Applied**

      At this stage, 5 models were used for analysis: 
      * Logistic Regression 
      * Decision Tree with GridsearchCV 
      * Random Forest Regressor with GridsearchCV 
      * XGBoost Regressor with GridsearchCV
      * SVM with GridsearchCV

5. **Machine Learning Model Performance**

      **Model 1 (with columns screen_resolution & screen_size instead of sc_h, sc_w, px_width, px_height)**
* **Logistic Regression** 

  ![image](https://github.com/Alisyed098/Capstone-Project-3---Mobile-Price-Range-Prediction/assets/134094832/771aad54-fa2b-488f-87a4-c0d3197e9f74)

* **Decision Tree with GridsearchCV** 

  ![image](https://github.com/Alisyed098/Capstone-Project-3---Mobile-Price-Range-Prediction/assets/134094832/a0219e68-d95c-4c48-82e4-6dec6c66962d)
      

* **Random Forest Regressor with GridsearchCV** 

  ![image](https://github.com/Alisyed098/Capstone-Project-3---Mobile-Price-Range-Prediction/assets/134094832/22035620-2050-42f6-ab15-2a0c3473c57b)

* **XGBoost Regressor with GridsearchCV**

  ![image](https://github.com/Alisyed098/Capstone-Project-3---Mobile-Price-Range-Prediction/assets/134094832/ef88960a-651f-45d2-9948-25d98aa0d9c5)

* **SVM with GridsearchCV**

  ![image](https://github.com/Alisyed098/Capstone-Project-3---Mobile-Price-Range-Prediction/assets/134094832/374cb644-4359-4439-a446-178592f36766)

      


**Model 2 (including columns sc_h, sc_w, px_width, px_height)**

* **Logistic Regression**

  ![image](https://github.com/Alisyed098/Capstone-Project-3---Mobile-Price-Range-Prediction/assets/134094832/22a7d53d-3f0a-4861-bb26-cbb62cfe9776)

* **SVM with GridsearchCV**

  ![image](https://github.com/Alisyed098/Capstone-Project-3---Mobile-Price-Range-Prediction/assets/134094832/5c180f68-6b1c-422f-9f0d-da192566ac14)

6. **Conclusions**

      The price range forecast and the generated insights provide the company with valuable tools to decide the price range of upcoming mobile phone.





      



-----------------------------------------------------
