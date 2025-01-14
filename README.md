# Health-Analysis
__Deployed at [dash-health-app.herokuapp](https://dash-health-app.herokuapp.com/)__  
__Note:__ Since the app uses single heroku dyno first loading could take some time to load  

Also checkout __[Kubernetes Deployment Steps](https://github.com/kshitijmamgain/Health-Analysis/tree/master/Kubernetes)__.  
Read the article for reference on my [blog](https://kshitijmamgain.github.io/designing-and-deploying-web-app-using-python/).  

### Samsung health data analysis  
Python provides powerful tools to analyze time series data. I have tried to analyze health data of an individual. The data has been taken from a samsung user. The provided datasets would come under 3 classes defined by Samsung:<br>

* Activity: step_count, exercise, floors_climbed
* Rest: sleep, sleep_data
* Health Care: calories_burned, heart_rate, stress
* Summary: daily_summary, step_daily_trend
  
The schema of the project would be:
  
#### Data Preprocessing  
Data Collecting, Cleaning, Transforming, Imputing  
  
#### Data Trend Analysis  
i. Sleep Trends  
ii. Exercise Trends  
iii. Heart Rate Trends  
iv. Stress Trends  
v. Step Counts Trends  
#### Data Daily Analysis  
i. Preparing a daily profile of the user using - step count, heart rate and sleep data
