# chocolate lovers
group project 


## Self-Assessment

#### Team:

Dainita Longman

Valeriya Hamm

Amber Middendorf

Swathy Rao

#### Each responsibilities: 

Amber Middendorf -  Managing Github and Data Visualization (Dashboard)

Swathy - Database set up,creating tables and importing the data from csv to the tables, linking database to the AWS for the team access and using psycop2 to coonect database to the Machine Learning model.

Dainita Longman -  cleaning up the data, database connection setup to the machine learning learning model,  managing google slides set up and presentation 

Valeriya Hamm - Analysis phase, machine learning model using K-nearest Neighbor

#### My responsibility:

- Creating the initial ERD (Entitiy relationship diagram ) for the database along with its datatypes and connection between the tables

- Setting up the Database (Chocolate_db) for this project in PostgreSQL. 

- Creating Tables(chocolate, regions, tastes ) in the database 

- linking the database fromPostgreSQL to the AWS to  have team access to the dataabse 

- using psycop2  to get  database connection  to the machine learning model.


#### Challenges 

We had some challenges to load data to the table but were able to get the database loaded after making several adjustments and tweaks to the data. 

## Team-Assessment

We worked very well as team. Each of the member were responsible for their part of the project as well as worked as a team to help resolve isuues came up through the course of the project. 

We used Slack as our main communication . 

## Summary of the project 

Chocolate Lovers Project, it is fun and interesting topic, we all enjoy eating chocolate and wanted to learn what features influenced the best rated chocolate. 

We have used the chocolate.csv data file from Kaggle
* 10 columns with features, with 3 that will be broken into bins
* Ratings is the Output for our classification.

Through this project, we wanted to discover if it was the ingredients or the origin of the beans that impacted the chocolate ratings the most? Where do best cocoa comes from? Where does the best chocolate come from and What words do people use to describe the best chocolate bar?

#### The Technologies,languages,tools and algorithms used: 

Python 3.7.6
Jupyter Notebooks
K-nearest Neighbor - Machine learning model
AWS- Database
PostgreSQL - Database
Tableau - Visualization and dashboard 
Google slides - presentation 

#### Results of the analysis 

The majority of chocolate bars were rated between 3 and 4. Less than 9% of chocolate bars was rated lower than 2.5 and was considered Unsatisfactory.  By utilizing bar charts, we were able to see where the top rated beans come from, Venezuela, Peru, Dominican Republic. Ecuador, and Madagascar. The countries that produced the majority of chocolate bars were United States, France, Canada, U.K,and Italy. The average rating for chocolate bars produced by Soma is 3.75. The majority of the bars had between 70% and 75% of cocoa, with 70% being the most popular concentration, so we can make the conclusion that more cocoa does not mean better rated chocolate. 



###### Visualizations:
* Map of the countries with highest rated chocolate or best beans.

![BeanOrigin](https://user-images.githubusercontent.com/95837693/170160404-0cce849e-75bc-429b-852d-e8e98e20b790.PNG)

* Pie chart to show top rated chocolates by ingredient and / or country.

![CompanyLocations](https://user-images.githubusercontent.com/95837693/170160418-b984d22d-5c8b-4658-bfd4-aeb3b2ccfbc8.PNG)

* Avg rating by country or region.

![AvgPerBeanOrigin](https://user-images.githubusercontent.com/95837693/170160438-bffbd400-fb00-4626-af2d-8e1b010cf0eb.PNG)


* Tastes related to ratings & visualization of common words

![Rated4](https://user-images.githubusercontent.com/95837693/170157155-0f01b9d7-116d-45a3-91e3-aa2480da9bd6.png)


###### Dashboard:

Dashboard created in Tableau to demonstrate the origins of beans of the top rated chocolates and the top tastes used to describe those chocolates. You'll be able to filter the rating of chocolates to see correlating information.

![DashboardConcept](https://user-images.githubusercontent.com/95837693/171538039-2054d1a0-79c9-4d66-92ba-0b1f6e12ddbe.PNG)

[Dashboard](https://public.tableau.com/app/profile/amber.middendorf/viz/Chocolate_Lovers_Maps/ChocolateStory?publish=yes)

