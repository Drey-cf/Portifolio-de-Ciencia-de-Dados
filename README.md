<h1 align = 'center'>Portfólio de Ciência de Dados</h1>

<h2>Sobre</h2>

<p>This repositoire contains the Data Science projects that I've finished at the moment. The 'Análise Exoplanetas.ipynb' was done during my graduation thesis, when I worked with a data base about exoplanets. 
  The task was to build an end-to-end data pipeline to clear the database of over 5,000 objects and deploy statistical models to verify if the 3 Keplerian Laws apply in exoplanets context. For that I used Python (Pandas and NumPy) to clean and prepare the raw datasets, and also to calculate new columns and error propagations. Scikit-Learn was used to apply a Linear Regression and to validate the model. And to create clear data visualizations I imported Matplotlib and Seaborn.
As some results, I graduated with an A grade. The study was published in a Qualis A1 journal [RBEF](https://www.scielo.br/j/rbef/a/hfq9phTfChYCH8sjTM3tmXf/abstract/?lang=pt).

  The other project was made during my course on 'Time Series and NLP', from my Post Graduation. In this second project, I focused on Time Series predictions using different models (Moving Averages, RNN, Decision Tree, ARIMA and TCN). 
I wanted to build a data pipeline to clean the raw data, train multiple architectures (Moving Averages, ARIMA, Decision Tree, RNN and TCN) and evaluate their performance for the task based on MAE, MSE and correlation for different prediction horizons. So, again, I used Pandas and NumPy to preprocess, clean and prepare the raw time series. Trained models using Scikit-Learn, TensorFlow/Keras and TCN. Created clear data visualizations with Matplotlib to explain the findings.
Results: All the models are bad for short and medium horizons (correlation <60%). But Moving Averages, Decision Tree and TCN are excellent for long horizons (>90% of correlation).
