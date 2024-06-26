

# Car-Price-Prediction
Predicting the price of the Car using Machine Learning

# Prerequisites
<h3>To run this project, will need the following:<br></h3>

Python 3.x<br>
Jupyter Notebook<br>
scikit-learn library<br>
pandas library<br>
numpy library<br>

# Car Price Prediction (Case Study)
 given some information about dataset like:<br>
 
 ![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/9173d60d-e018-4eac-b3e3-3d5133ee6035)

  # How  did I do?

<h3>The dataset I am using for the Car Price Prediction task is downloaded from Kaggle. Now let’s start with this task by importing the necessary Python libraries and dataset:<br></h3>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/f036148a-0a28-4189-ba92-986f56a64f7b)

<h3>Now before moving forward, let’s have a look at whether this dataset contains any null values or not:<br></h3>

data.isnull().sum()<br>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/c8c52633-3dc2-476d-afa3-782d8e3afb50)

<h3>The dataset doesn’t have any null values</h3>

<h3>Dropping the year column</h3>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/c8fe5d91-8fc7-4b47-91f7-54dc5c1f59c0)

<h3>Removing the outlier of the Selling Price</h3>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/63a5382b-3631-4f76-8d67-e9c41b30c117)

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/a3676e5e-b954-4ef5-b6a9-6342b4f4c9c8)

<h3>Converting the Fuel Type, Seller Type, Transmissin Type into a encoding values</h3>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/4ea558df-6243-4f19-bac9-c3fbabd9f225)

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/32a7e14f-6ea7-49fc-b6c7-bbedb0ef1b1f)

# Car Price Prediction Model
<h3>Importing the Models and Training</h3>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/4b04001f-31cd-4bb4-b146-1977d2281e8f)

<h3>. Prediction on Test Data</h3>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/464ae0a1-e241-45b3-b486-6d14f6522dae)

<h3>Evaluating the Algorithm</h3>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/7479d13d-efd1-43c5-823e-47102896c562)

<h3>Save The Model</h3>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/c16db73c-1ed1-4b6f-9676-838e5c690d30)

<h3>Prediction on New Data</h3>

![image](https://github.com/Sanketarali/Car-Price-Prediction/assets/110754364/5f93961b-6d68-4f73-a651-d929fb34665b)







 
