# Stock-Prediction-model-using-Deep-Learning
A Stock Market Prediction Model using ARIMA, LSTM, and liner regression algorithms .


# Stock-Market-Prediction-Web-App-using-Machine-Learning
**Stock Market Prediction** Web App based on **Machine Learning** and **Sentiment Analysis** of Tweets **(API keys included in code)**. The front end of the Web App is based on **Flask** and **Wordpress**. The App forecasts stock prices of the next seven days for any given stock under **NASDAQ** or **NSE** as input by the user. Predictions are made using three algorithms: **ARIMA, LSTM, Linear Regression**. The Web App combines the predicted prices of the next seven days with the **sentiment analysis of tweets** to give recommendation whether the price is going to rise or fall.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#system-description-and-functions">System Description and Functions</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#links">Links</a></li>
  </ol>
</details>

## System Description and Functions


**Admin Creds:** <br/>
Username: admin <br/>
Email Address: stockpredictorapp@gmail.com <br/>
Password: Samplepass@123 <br/>

There are two roles in the system: **Admin** and **User**.<br/><br/>
Users can:<br/>
<ol>
    <li>Register and Login </li>
    <li>Check Real Time stock prices</li>
    <li>Read recent news about different stocks</li>
    <li>Currency Converter</li>
    <li>Edit or delete their own profile</li>
    <li>Educate the user about stocks</li>
    <li>Download list of stock tickers</li>
    <li>Predict Stock prices for the next 7 days for all NASDAQ and NSE stocks</li>
</ol>

Admin can:<br/>
<ol>
    <li>Create, Retrieve, Update Delete Users.</li>
    <li>Manually trigger emails.</li>
    <li>Register and Login </li>
    <li>Check Real Time stock prices</li>
    <li>Read recent news about different stocks</li>
    <li>Currency Converter</li>
    <li>Edit or delete their own profile</li>
    <li>Educate the user about stocks</li>
    <li>Download list of stock tickers</li>
    <li>Predict Stock prices for the next 7 days for all NASDAQ and NSE stocks</li>
</ol>


## Installation
1. Install XAMPP server
2. Download wordpress zip folder from <a href="https://drive.google.com/file/d/1J753gY0Nv6HGSkPngSxrogNghDQnoIlk/view?usp=sharing">this link</a>.
3. Extract the downloaded zip into ```htdocs``` folder of XAMPP.
4. Open the ```wp-config.php``` file from the extracted folder and add your phpmyadmin username and password.
5. Go to phpmyadmin, create a new database called ```wordpress```.
6. Select this database, go to Operations tab and Import the ```wordpress.sql``` file into this created databse.
7. Clone the repo, cd into it
4. Run ```pip install -r requirements.txt```
5. Run ```python main.py``` to start server.
7. Go to ```localhost/wordpress``` to access the app.



