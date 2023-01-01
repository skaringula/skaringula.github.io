<h1> About Me </h1>

Hey there! My name is Shivani Karingula and I am an aspiring data scientist. As someone who has always been an inquisitive person, data science is a field that immediately caught my attention. It's something that not only allows me to use my analytical skills to answer questions and solve problems but it also gives me a chance to put my creativity and love for storytelling to use via data visualization. 

As for my background, I have a double-major Bachelor's degree from Rutgers Business School in Business Analytics & Information Technology as well as Supply Chain Management. During my time in undergrad, I completed two 1-year co-ops with leading multi-national companies in the field of supply chain and analytics. For my first co-op, I worked in the transportation department of Supply Chain at Shiseido, the fifth largest cosmetic company in the world. Later, I worked at Ethicon (Johnson & Johnson's medical devices company) as a Supply Chain Analytics Co-op where I spearheaded report automation projects utilizing Tableau and Python which resulted signifiant savings for the organization. 

Post graduating from Rutgers, I switched gears and worked as an Implementation Consultant in the healthcare sector at Medidata Inc. After gaining valauble skills here, I decided it was time for me to make a career shift that aligns more with my interest in developing my technical knowledge, which is when I decided to pursue the Data Science Master's Certification Program from Simplilearn. 

Now that you know a little more about me and how I got to where I am right now, feel free take a look at the projects I've worked on: 


# Portfolio

---

## Projects 

### [Project No. 1: Healthcare (Binary Classification)](https://github.com/skaringula/Healthcare-Capstone-Project)
<img src="/images/diabetes.png"/>

**Introduction:** NIDDK (National Institute of Diabetes and Digestive and Kidney Diseases) research creates knowledge about and treatments for the most chronic, costly, and consequential diseases. The dataset used in this project is originally from NIDDK. The objective was to predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.  

**Objective:** 
I completed this project for my capstone which was the final assessment for the Data Science Master's Program from Simplilearn. The objective of this project was to analyze the datasets from NIDKK to draw valauble insights from the medical predictor variables (glucose, insulin, blood pressure, etc.) and see how those impact the target variable (outcome - whether the patient is diagnosed with diabetes or not). After preliminary cleaning, transformation, and exploratory data analysis of the dataset, I moved on to train multiple classification algorithms for the prediction of diabetes in patients. I compared the performance of these models to find that the Random Forest machine learning model produced the best performance for this project. Lastly, I created a dashboard for the visualization the relationship between the parameters and the outcome in the data which can be found here.

**Tasks performed in this project:**
- Data Cleaning
- Data Transformation
- Data Modeling - various classification model
- Data Modeling - performance evaluation using various metrics
- Data Reporting - dashboarding in tableau

**Tools Used:**
Python Libraries: pandas, numpy, sklearn, matplotlib, seaborn, gridSearchCV; Tableau
ML Models: Logistic Regression, Decision Tree, Random Forest, SVM (Support Vector Machine) , Naive Bayes, KNN (K-Nearest Neighbors)

**Future Implementations:** 
- I am working to deploy the model via Python Flask on Heroku. 

---

### [Project No. 2: Income Qualification](https://github.com/skaringula/Income-Qualification-Project) 
<img src="/images/income.png"/>

**Introduction:** Many social programs have a hard time ensuring that the right people are given enough aid. It’s difficult when a program focuses on the poorest segment of the population. This segment of the population can’t provide the necessary income and expense records to prove that they qualify. The Inter-American Development Bank (IDB) believes that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance. 

**Objective:** I completed this project towards to the assessment for the Machine Learning Module of my Data Science Master's Program from Simplilearn. My task was to identify the level of income qualification needed for the families for social welfare program in Latin America using given dataset. I also had to identify important features among the predictor variables and comment on their importance in model performance.

**Tasks performed in this project:**
- Data Cleaning
- Data Transformation
- Data Modeling - RandomForest Classifier
- Data Modeling - performance evaluation using various metrics

**Tools Used:**
- Python Libraries: pandas, numpy, sklearn, matplotlib, seaborn, gridSearchCV
- ML Models: Random Forest Classifier


## Projects Coming Soon

### Project No. 3: Youtube Food Influencer Analysis
<img src="images/youtube.png?raw=true"/>

**Introduction:** 
My pride and joy [**The Spice Voyage**](https://thespicevoyage.com/) is a food blog that I started two years ago to combine my passion for cooking, food travel, and writing. I've primarily stuck to static photography shots of the recipes I develop on my social media page and article style posts on my blog. But it's clear that video is THE format to delve into if you're looking for growth and engagement as a content creator in the current digital era. From Tiktok, Instagram Reels, to recently, Youtube Shorts, short-form videos do a great job of reaching your target audience and making them come back for more, that is, if you have the right strategy in place. Since I am looking to expand into video content for my recipes and restaurant reviews, I thought it'd be interesting to take a look at what some of the biggest food influencers on arguably the most prominent video platform, Youtube, have been doing to amass such a big following and level of engagemnt. These insights will allow me to create a content strategy for my Youtube channel that will eventually see results similar to those of these food Youtubers -- a loyal audience and opportunities for monetization.

**Objective:** 
For this project, I plan to connect to the Youtube API to grab channel statistic, video, and comment data for the following 10 Youtube food influencers (with a minimum of 1 million subscribers):
1. You Suck at Cooking
2. Joshua Weissman
3. Babish Culinary Universe
4. Marion's Kitchen
5. Not Another Cooking Show
6. Ethan Chlebowski
7. Adam Ragusea
8. Laura in the Kitchen
9. Maangchi
10. Pro Home Cooks

After cleaning up and transforming this data, I will primarily use Exploratory Data Analysis (EDA) to draw the following insights:
- Popular channels by subscribers 
- Popular channels by views 
- Total views, likes, dislikes, and comments of all videos by channel
- Average # of likes, dislikes, and comments on each video by channel
- Average engagement ratio (reactors vs. total viewers) for each channel
- By year: subscribers, views, # of videos, likes, comments 
- Top 10 food videos from all channels

I will also analyze the data from each of these creators to answer some crucial content strategy questions such as: 
1. What is the relation between views and engagement (likes/comments)? 
2. How does video duration impact likes and comments on a video? 
3. Does title length affect the number of views a video receives? 
4. How many tags do good performing videos tend to have? What are the common tags among these 5. videos? 
6. Across all these creators, how often do they upload and which days of the week do they tend to upload on? 
7. What time of the year (by season and month) tends to produce the best performing food content? 

After extracting these insights from the data, I will visualize the data in the form of an interactive Tableau analytics dashboard that will allow the user to see an aggregated view of these analytics across all ten Youtube food influencers as well as give them the option to drill down on these statistics based on a particular channel or by month/year. 

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
