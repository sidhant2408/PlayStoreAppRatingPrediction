<h1>Predicting Google Play Store App Rating with Decision Tree, Random Forest, Gradient Boosting & ADA Boosting Classification.</h1>
<br><br>
Project Overview:<br>
<ul>
  <li>This is a project for play store app rating prediction.</li>
  <li>The dataset used is <b>"Google Play Store Apps"</b> from Kaggle.</li>
  <li>Dataset containes <b>9600+</b> records.</li>
  <li>Steps performed:
    <ul>
      <li>Importing necessary libraries.</li>
      <li>Loading dataset.</li>
      <li>Exploratory data analysis</li>
      <li>Data cleansing</li>
      <li>Data preparation</li>
      <li>Model preparation</li>
      <li>Model training</li>
      <li>Prediction and testing</li>
    </ul></li>
  <li>Plot for feature importance for each model is shown.</li>
</ul>
    <br>
    
![image](https://user-images.githubusercontent.com/72664379/185337802-fa503489-ec3d-49e2-81cb-bcb5f8dee962.png)
<br>
Pie chart showing rating category of apps. High means rating >3.5 and low is <=3.5.<br><br>

![image](https://user-images.githubusercontent.com/72664379/185341526-56668404-8731-42fe-ab75-6b794ca6581d.png)
<br>
This plot shows the significance of all the independent features in predicting the app rating for decison tree classifier model. <br><br>

![image](https://user-images.githubusercontent.com/72664379/185339685-015a45dd-75aa-45a3-88e3-037a064d0327.png)
<br>
This plot shows the significance of all the independent features in predicting the app rating for random forest classifier model. <br><br>

![image](https://user-images.githubusercontent.com/72664379/185339943-ab684b1b-1da2-4d1a-bb47-590cee50c8ed.png)
<br>
This plot shows the significance of all the independent features in predicting the app rating for gradient boosting classifier model. <br><br>

![image](https://user-images.githubusercontent.com/72664379/185340283-9fd49a28-2082-4d82-9aec-6ee2d634a9f4.png)
<br>
This plot shows the significance of all the independent features in predicting the app rating for ADA boosting classifier model. <br>
<br>
Accuracies achieved:
<ul>
  <li>Decision Tree Classifier:
    <ul>
      <li>Training: <b>100%</b></li>
      <li>Testing: <b>84%</b></li>
    </ul>
  </li>
  <li>Random Forest Classifier:
    <ul>
      <li>Training: <b>100%</b></li>
      <li>Testing: <b>89%</b></li>
    </ul> 
  </li>
  <li>Gradient Boosting Classifier:
    <ul>
      <li>Training: <b>90%</b></li>
      <li>Testing: <b>89%</b></li>
    </ul>
  </li>
  <li>ADA Boosting Classifier:
    <ul>
      <li>Training: <b>89%</b></li>
      <li>Testing: <b>89%</b></li>
    </ul>
  </li>
</ul>

<h3>Conclusions:</h3>
<ul>
<li>From the features vs importance plot, we can conclude that the 'Reviews' column has the greatest significance in predicting the rating of an app.</li>
<li>Along with 'Reviews', 'Category' ,'Size' and 'Installs' also play a much efficient role in the predictions.</li>
<li>'Content Rating' and 'Type' has the least significance that shows that the age group and money doesn't matters much for the rating of and app.</li>
</ul>





