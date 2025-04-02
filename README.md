![Bellabeat logo](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/backdrop%20bellabeats.PNG?raw=true)

# Bellabeats - fitness health data tracker - analytics
Capstone project - Google data analytics professional 

## Context
Bellabeat is a health and wellness technology company that focuses on tracking women's health. The company creates smart jewelry, fitness trackers, and wellness apps designed to help women monitor various health metrics, including activity, sleep, stress, menstrual cycles, etc. 

**Goal**

* This analysis aims to identify customer usage of the smart devices.

**Dataset source**
* The data originate from the FitBit Fitness tracker datasets made available through Mobius. You can access the dataset [here](https://www.kaggle.com/datasets/arashnic/fitbit)

## Stakeholders
* Management of Bellabeat
* Bellabeat marketing analytics team
* Bellabeat customers

## Analysis and Insights

### Correlation among variables

![Heatmap](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/heatmap%20correlation.PNG?raw=true)
* We can see a positive correlation between Calories and TotalDistance (corr: 0.64), TotalSteps (corr: 0.59), and TotalActiveMinutes (corr: 0.47).
* In contrast, there is a negative correlation between Calories and SedentaryMinutes (corr: -0.11).

### Calories burnt VS total steps
![calories vs totalsteps](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/calories%20burn%20vs%20total%20steps.PNG?raw=true)
* The scatter plot shows that the higher the number of TotalSteps, the more calories are burnt.

### Calories burnt VS sedentary minutes
![calories vs sedentary minutes](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/calories%20burn%20vs%20sedentary%20minutes.PNG?raw=true)
* Sedentary minutes may weakly correlate to the calories being burnt. 

### Sedentary minutes VS total active minutes
![Sedentary vs total active minutes](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/sedentary%20minutes%20vs%20total%20active%20minutes.PNG?raw=true)
* There is a huge gap between sedentary minutes (about five times higher) than TotalActiveMinutes.

### Calories burnt by days
![Weekly calories burnt](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/Calories%20burned%20by%20the%20week.PNG?raw=true)
* Most users tend to burn their calories on Saturday.
* Monday is the day when the least amount of calories are burned.

### Total steps by days
![Weekly total steps](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/Total%20steps%20taken%20by%20the%20day%20of%20the%20week.PNG?raw=true)
* Most users spend more time exercising on weekends than weekdays. 

### Total asleep or resting time by days
![Total asleep time](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/Total%20daily%20asleep%20by%20hours.PNG?raw=true)
* Users spend more time resting on Monday (probably the busiest day in weekdays) and Saturday (After losing most of their calories or after exercising)

### Total steps by hours within a day
![Totals steps within a day](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/Total%20steps%20within%20a%20day.PNG?raw=true)
* Users start getting active usually from 8 am to 7 pm. After that, their activities are continuously decreasing (probably) due to resting.


## Recommendation
Based on the previous insights of our analysis, we have formulated some actionable recommendations that may improve Bellabeat's operational through 'promotion' and 'customer retention'

**Promotion**

* The data shows that people are less active between 8 and 10 p.m., just before bedtime. This is the best time for Bellabeat to run ads for maximum impact. Platforms like Google Ads allow businesses to schedule when their ads appear, ensuring they reach the right audience at the right time. Using this strategy, Bellabeat can effectively connect with potential customers while also saving money on advertising costs.

**Retention**

* Keeping customers engaged is just as important as attracting new ones. [Research](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Assets/Online%2BMembership%2BIndustry%2BReport%2B-%2B2019.pdf) shows that 80% of customers cancel their subscriptions within two years. To keep users engaged, Bellabeat should provide personalized content that adds value. For example, the data shows a strong link between the number of steps taken and calories burned—people who walk more burn more calories. However, many users struggle to reach the recommended 10,000 steps per day for a healthy lifestyle. Bellabeat can support users by sharing useful tips and advice on how to stay active. These can be posted regularly on its website. Additionally, Bellabeat can introduce fun challenges to motivate users to walk more. This will not only encourage engagement but also help users stay on track with their health goals.

* Another key finding is that people spend more time being inactive than active. A sedentary lifestyle is linked to health issues like obesity, heart disease, and stroke. Bellabeat can create educational content—such as blog posts and explainer videos—to inform users about the risks of inactivity and how to stay healthy. This also presents an opportunity to promote Bellabeat’s other products, like the Bellabeat app, which provides health insights, and Bellabeat Time, which syncs with the app to track daily well-being.


## Asset
* Notebook: Bellabeat analytics (Python) - [Link](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/google-data-analytics-capstone-bellabeat-python.ipynb)
* Notebook: Bellabeat analytics (using R) - [Link](https://github.com/harishmuh/Bellabeats_Capstone_Google_Data_Analytics/blob/main/Bellabeat_user_data_analysis_using_R.ipynb)

