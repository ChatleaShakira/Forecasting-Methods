# Forecasting-Methods
## Forecasting Methods for the Stock Price Index of Garuda Indonesia Company in the International Stock Market from June 2018 to June 2023 for the Period of July 2023 to November 2023
\
Forecasting Methods is one of the elective courses in the Statistics program at the University of Indonesia that I took in my fourth semester. The course equips students with the skills to analyze time series data using Exponential Smoothing methods and forecasting perspectives, along with knowledge of linear models.\
\
The project I am sharing this time is the final project of the course titled "Forecasting Methods for the Stock Price Index of Garuda Indonesia Company in the International Stock Market from June 2018 to June 2023 for the Period of July 2023 to November 2023"\
\
The data for this project was obtained from [Yahoo Finance](https://finance.yahoo.com/quote/GIAA.JK/history?p=GIAA.JK) and has been downloaded in CSV format, available in the file [GIAA.JK.csv.](https://github.com/ChatleaShakira/Forecasting-Methods/blob/0c6dec311edc38d079fa415d46d14c0d6f358c5c/GIAA.JK.csv)\
\
**Project Objectives:**
1. Explain the data analysis process needed to obtain the best model suitable for forecasting.
2. Determine the best time series model for predicting the closing price of PT. Garuda Indonesia (Persero) Tbk using the ARIMA (Autoregressive Integrated Moving Average) method.
3. Find out the forecast of the closing price of PT. Garuda Indonesia (Persero) Tbk using the ARIMA method for the period of June 1, 2018 - June 1, 2023.

**Analysis Tools:**
The analysis was conducted using the R programming language and R Studio. The relevant R code can be found in the files [Uji Stationeritas, Spesifikasi Model, dan Estimasi Parameter.R](https://github.com/ChatleaShakira/Forecasting-Methods/blob/82e9291a6bce68edba4a33728c88584a056e8dc7/Uji%20Stasioneritas%2C%20Spesifikasi%20Model%2C%20dan%20Estimasi%20Parameter.R) and [Diagnostik Model dan Peramalan.R](https://github.com/ChatleaShakira/Forecasting-Methods/blob/4c14fd0e7be6ef4ba3419e83c94190e68933ecc9/Diagnostic%20Model%20dan%20Peramalan.R).

**Project Details:**
For more in-depth details, please refer to the [Laporan Tugas Akhir Metode PERAMALAN - Kelompok 2.pdf](https://github.com/ChatleaShakira/Forecasting-Methods/blob/e5950104c778971689dd9e8eb1c9bc1424039753/Laporan%20Tugas%20Akhir%20Metode%20Peramalan%20-%20Kelompok%202.pdf) in section 2.3 Metode Analisis Data.\
\
**Project Conclusion:**
1. The data is likely to become stationary after differencing 1 time, suggesting that the proposed forecasting model for PT. Garuda Indonesia (Persero) Tbk is ARIMA(p,1,q).
2. The model obtained to forecast the closing price of Garuda Indonesia is the ARIMA(0,1,1) model with the general form Yt = Yt-1 + et - θet-1. The final model after the parameter estimation process is Yt = Yt-1 - 3.02686 + et + 0.28247et-1. This model is a fit model after going through the overfitting and cross-validation stages.
3. It is predicted that the closing price of Garuda Indonesia shares for the next 5 months will decrease from July 2023 - November 2023 with the forecast details, namely $60.08121 / share in July 2023, $57.05.

## Acknowledgments

I would like to express my gratitude to the following individuals for their valuable contributions and support throughout the development of this project:
- Jihan Sandrina Halim
- Zahrah Mahfuzah

Their hard work and teamwork have not only made this project possible but have also created an environment of creativity and efficiency. I am truly grateful for the opportunity to work alongside such talented individuals.

Thank you for your outstanding contributions.

Chatlea.



