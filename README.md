<div align="center">
    <h2>📊📈 TIME SERIES FORECAST ⌛📉 </h2>
</div>



## 🏗️ Project Materials 🏭

### ℹ️ About ℹ️
- This project is an implementation on predicting future **SALES** using a time-series dataset of a retail store.</br>
-  dataset I am using is of **Favorita Retail Stores (From Ecuador). Found it in a Kaggle Competition</br>
- The notebook contains implementation of 6 different algorithms for prediction.</br>
- Total Runtime is about an hour (Majority of the time is spent on training SARIMA models)

***

### 📁 IPYNB File: RIO_125_Forecasting_Sales.ipynb 📁
- Contains the entire code (Importing Data, Cleaning, EDA, Visualization).
- Models used :
    - ARIMA
    - SARIMA
    - Rolling Window Forecast
    - Facebook Prophet
    - Decision Tree Regressor
    - Random Forest Regressor
- You can improve the prediction accuracy by implementing more models or improving the existing ones.

***

### ⚒ Preparing the dataset to use in the notebook ⚒
[Dataset Link | Drive](https://drive.google.com/drive/folders/1D45Ehi_HQ_OyLtzUW4TPfxxJd6I4sxXS?usp=sharing)

Download the subset of the data from the above link. 
1. If you are mounting drive in your colab file like I did, go the the drive link above > Select Download All.
2. Drive will create a zip file. Extract it.
3. Rename it to `Favorita_Stores_Sales_Dataset` and upload the folder to your google drive.
4. Do not upload it inside some other folder. (Or if you know how to use proper paths, you can. You might have to tweak the path a bit at the start of the notebook.)

***

### ⚠️Reason you shouldn't upload it directly to Colab File Explorer ⚠️
- It takes a really long time to upload.
- Not all the data is read/imported when you read_csv. A lot of rows are missing. (I did not find a solution for the problem)
So avoid uploading directly. Plus, uploading to drive is a one-time setup.

***

> [!NOTE]
> #### The dataset is a subset of this Kaggle Competition Data and can be found [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data?select=transactions.csv) </br>
> #### I am not the owner/publisher of the data.
