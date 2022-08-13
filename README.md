# Smart Pillow Stress Detection Machine Learning


#### -- Project Status: [Completed]

## Project Description
Smart-Yoga Pillow (SaYopillow) is a Smart Pillow connected to a wireless tracker to monitor sleeping habits and features to determine stress levels. There are 630 records in this dataset and each record contains sleeping information such as snoring rate, number of hours of sleep, body temperature (Fahrenheit), etc. A common issue people have is reducing their snoring (rate). Using multi-linear regression modeling to predict snoring rate, it is possible to determine what features can be adjusted to reduce the snoring rate. Another issue is specifying stress levels. When asked by a medical professional on how stressed you are from a scale of 0 to 4 (0 being not stressed/low stress levels), there should be a more simplified version of that scale such as a categorical scale (not stressed, stressed, over stressed). Using k-means clustering, we can reduce the numerical stress level scale 0 to 4 to three categories. This is useful for early detection of being over stressed and receiving proper treatment prematurely. For example, if someone is classified as stressed only on the numerical scale, but is actually overly stressed on the categorical scale, this can lead to improper treatment. 


### Methods Used
* Multi-Linear Regression Modeling for Predictive Modeling
* Feature Correlation Selection
* K-Means Clustering 
* Elbow Method
* Data Visualizations (Correlation Matrix & Elbow Plot)

### Technologies 
* Python
* Jupyter Notebook


## Resources

* https://www.smohanty.org/Presentations/2018/Mohanty_iSES-2018_Smart-Pillow_Talk.pdf (SaYo Pillow info)

* https://www.kaggle.com/datasets/laavanya/human-stress-detection-in-and-through-sleep?select=SaYoPillow.csv (dataset)

* https://datatofish.com/multiple-linear-regression-python/ (multi-linear regression model)

* https://predictivehacks.com/k-means-elbow-method-code-for-python/ (k-means)
