# Data-science--covid19-time-series


## Instructions for Running Python Notebooks Locally

1. requirements.txt
2. Use Google colab
3. Run notebooks as usual by using a jupyter notebook server, Vscode etc.

## Jupyter notebook Fbprophet installation 
 * !conda install -c conda-forge fbprophet -y
 * !pip install prophet



#### Target of Model:
The time series dependent facebook prophet model is used to fit the data and provide future predictions. This model aimed to determine the pandemic prediction of COVID-19 in Several countries, using the Time Series Analysis to observe and predict the coronavirus pandemic’s spread daily or weekly.

#### Dataset: 
The data used in this analysis consists of the daily Confirmed, Recovered and Death cases of COVID-19 for several Countries and their respective region or provinces. where the raw data was sourced from the john Hopkins university.  
#### Visualization 
In all over world Covid19 cases in Confirmed, Recovered and Death case.
![image](https://user-images.githubusercontent.com/73145010/156256681-93d8bcec-7e84-4808-98e9-5024cd82c644.png)

#### Analysing the Top 10 countries affected by corona cases from the dataset shows below:

![image](https://user-images.githubusercontent.com/73145010/156257130-a53fcd1b-ccc3-4cc4-b5a2-17db413146a6.png)
![image](https://user-images.githubusercontent.com/73145010/156257153-55dcae32-9ca1-4f46-8bb4-3d43618a2a2c.png)
![image](https://user-images.githubusercontent.com/73145010/156257192-881ecd82-106d-4a30-b8d1-7d2c3a7f248e.png)


#### Model Description: 
In order to predict Coronavirus disease (COVID-19), I used the Time Series Analysis using facebook Prophet Model, which is an open-source library developed by Facebook, designed for making forecasts for time series.

![image](https://user-images.githubusercontent.com/73145010/156255858-94a5b333-c4f6-48ef-ad45-2564a7656013.png)


### Prediction of Confirmed Cases:
![image](https://user-images.githubusercontent.com/73145010/156257670-61e06e5d-36bf-4d6a-ae3c-3343854583a9.png)

### Weekly analysis :
![image](https://user-images.githubusercontent.com/73145010/156257847-adec9b78-593d-4473-99ab-fdfbe0d87beb.png)

### Model Performance for Confirmed Case :
![image](https://user-images.githubusercontent.com/73145010/156257994-782ea132-9011-4e97-a137-1be9788a8b32.png)


#### Prediction of Recovered Cases
![image](https://user-images.githubusercontent.com/73145010/156258397-08af1475-ce4b-4a66-aeca-8bc51c7ca393.png)

### Weekly analysis :
![image](https://user-images.githubusercontent.com/73145010/156258443-a53672a2-9d20-4ac8-9fcd-18773829797b.png)


### Model Performance for Recovered Case :
![image](https://user-images.githubusercontent.com/73145010/156258504-fd2e154e-e4c5-4b87-ae4a-d113de315d92.png)



### Prediction of Death Cases
![image](https://user-images.githubusercontent.com/73145010/156258655-1e84f2de-b258-4509-9406-1af046571ee8.png)

### Weekly analysis :
![image](https://user-images.githubusercontent.com/73145010/156258443-a53672a2-9d20-4ac8-9fcd-18773829797b.png)


### Model Performance for Death Case :
![image](https://user-images.githubusercontent.com/73145010/156258805-7575b7fb-49fd-4f68-bc72-8b776c15197f.png)



