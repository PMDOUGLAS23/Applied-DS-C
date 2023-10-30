# Applied-DS-C
Applied Data Science Capstone Project for the IBM Data Science Professional Certifcate with Coursera

SpaceX is able to propose rocket launch at inexpensive price because they can reuse the 1st stage. Thus, to predict the price of a rocket launch, we use public data on SpaceX past launches to train a machine learning model which can predict if the 1st stage will land successfully.
•  We proceed with the following methodology :
•  We first collect data on spaceX past launches using SpaceX API and Web Scrapping Beautiful python package, then we clean the data
obtained and perform data wrangling to produce dataset ready for further analysis.
•  We continue with Exploratory Data Analysis using Pandas, SQL, visualization (with matplotlib and seaborn), interactive visualization (with Folium) to understand the data and chose the best features.
•  We build a dash board using Plotly Dash allowing users to visualize relationships between the booster versions, the payload mass, the launch sites, and the success rate of 1st stage landing on past launches data.
•  We perform prediction analysis with 3 classification models : Support Vector Machine(SVM), Decision Tree and K Nearest Neighbors(KNN).
•  Following the EDA, we observe that the success of the 1st stage landing is related to the Launch Site, The Payload mass, the Orbit, the Booster, Flight Number, the landing pad, ...
•  The Decision Tree Model has the best performance in predicting the success of 1st stage landing with an accuracy score of 94,4% compare to SVM and KNN.
