# Titanic-Machine-learning-from-Disaster-Kaggle

<div>
  <h2> Predict surival on the titanic</h2>
  <br> * Defining the problem statement</br>
  <br> * Collecting Data </br>
  <br> * Exploratory Data Analysis </br>
  <br> * Feature engineering </br>
  <br> * Feature Selection </br>
  <br> * Modeling </br>
  <br> * Testing </br>
</div>

<div>
<h3> Defining the problem statement </h3>
  
Complete the analysis of what sort of people were likely to survive.
In particularly, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy
</div>

<div>
  <h3> Data Dictionary </h3>

* Survived : 0 = No, 1 = Yes
* Pclass : Ticket class 1 = 1st, 2 = 2nd, 3 = 3rd
* SibSp : # of sibling / spouses aboard the Titanic
* Parch : # of parents / children aboard the Titanic
* Ticket : Ticket number
* Cabin : Cabin number
* Embarked : Port of Embarkation C = Cherbourg, Q = Queenstown, S = Southampton

</div>

<div>
  <h3> Exploratory Data Analysis </h3>
  
  
  Bar chart for categorical values
  
* Pclass
* Sex
* SibSp (# of sibling and spouse)
* Parch (# of parents and children)
* Embarked
* Cabin
  
<img src="https://github.com/JM-Rishav/Titanic-Machine-learning-from-Disaster-Kaggle/blob/main/Data/Pclass_bar_chart.png" width="900" height="400">
<br></br>
<img src="https://github.com/JM-Rishav/Titanic-Machine-learning-from-Disaster-Kaggle/blob/main/Data/sex_bar_chart.png" width="900" height="400">
<br></br>
<img src="https://github.com/JM-Rishav/Titanic-Machine-learning-from-Disaster-Kaggle/blob/main/Data/SibSp_bar_chart.png" width="900" height="400">
<br></br>
<img src="https://github.com/JM-Rishav/Titanic-Machine-learning-from-Disaster-Kaggle/blob/main/Data/Parch_bar_chart.png" width="900" height="400">
<br></br>
<img src="https://github.com/JM-Rishav/Titanic-Machine-learning-from-Disaster-Kaggle/blob/main/Data/Embarked_bar_chart.png" width="900" height="400">
  
</div>  

<div>
 <h3> Feature Engineering </h3>
 Feature engineering is the process of using domain knowledge of the data to create features (feature vectors) that make machine learning algorithms work.

 feature vector is an n-demensional vector of numerical features that represent some object. Many algorithms in machine learning require a numerical representation of objects,    since such representations facilitate processsing and statistical analysis.
<br></br>
sank from the bow of the ship where third class rooms located conclusion, Pclass is key feature for classifier
<img src = "https://static1.squarespace.com/static/5006453fe4b09ef2252ba068/t/5090b249e4b047ba54dfd258/1351660113175/TItanic-Survival-Infographic.jpg?format=1500w">
</div> 

<div>
  <h3> Modeling <h3>
    Explanation :- lets consider that simsons survived or not. 
    <img src="https://github.com/JM-Rishav/Titanic-Machine-learning-from-Disaster-Kaggle/blob/main/Data/Titanic_ML_1.png">
    For better understanding, we consider there is only 2 features in the data represented on x-axis and y-axis.
    
    1. KNN 
       <img src="https://github.com/JM-Rishav/Titanic-Machine-learning-from-Disaster-Kaggle/blob/main/Data/Titanic_ML_2.png">
       for k = 3, 2 survived and one dead, so simsons survived
    2.
    3.
    4.
    5.
    6.
    
</div>
