## Data-warehousing-Netflix-project

### The Business/Organization & Opportunity: <br/>
Netflix is a subscription-based streaming service that allows its members to watch tv shows and movies without commercials on an internet-connected device (ref. netflix.com). There is an opportunity to optimize the selection of tv shows and movies for the business to increase member subscriptions and/or stock prices by analyzing the current total number  of TV shows/movies, top 20 director of movie and Tv shows etc.

### Problem: <br/>
The system helps us to find out what the most popular genre of movies/shows are in the current Netflix shows/movies selection and in Which country has highest no of movie and also by each year 

### Dimensional Model: <br/>
![image](![Screenshot 2024-05-09 131218](https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/assets/154571318/567f712e-e8e4-41a5-b68e-506c10969a88)
)


### Detailed Design: <br/>
The datasets we found from Kaggle.com allow us to analyze the Netflix’s movies and shows selection. For ETL steps, we chose to use python because it is one of the popular general-purpose programming languages that is capable of performing the tasks and the team is familiar with. We chose to run our data warehouse on MySQL server because it is a popular relational database management system that provides secure and fast data storage, fast query speed and I am also familiar with it. Finally, I chose Tableau to create visualizations because it is a powerful visualization tool that offers ease of use and many visualization possibilities.  using these technologies I can easily pick up how to use them because there are many instructions or documentations available for these technologies which will significantly reduce the training time and cost.

### ETL: <br/>
![image](![ETL](https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/assets/154571318/274820c6-b648-40a1-acd2-ea1afa33ad8a)
) <br/>

### Final Schema: <br/>
![image](![Screenshot 2024-05-09 215504](https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/assets/154571318/f6d32da5-00eb-45e0-9922-68fb3fcc0768)
)

The final schema for our project is a Star schema which contains two fact tables and four dimensional tables. <br/>

### Dashboard Application: <br/>

![image](![Screenshot 2024-05-18 162319](https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/assets/154571318/e956f75d-bcfe-457a-ac1f-aec62572af08)
)

Use MySQL workbench to monitor performance <br/>

### Connect Tableau to MySQL and Tableau analysis: <br/>
![image](![Screenshot 2024-05-18 162654](https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/assets/154571318/97ac0eb1-4aef-453d-a71d-53da28207904)
)

The analytics/visualization in the dashboard help answer the questions in the Problem section.

What are total no of movies and Tv shows on Netflix 
[image](![Screenshot 2024-05-18 162808](https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/assets/154571318/de240f3c-1ced-49b9-a50f-99819a1672fa)
)

what are top 20 director of movies and Tv shows
[image](![Screenshot 2024-05-18 162917](https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/assets/154571318/c6e00197-535d-4cc5-ac0c-172996e97352)
)

In Which country has most no of Movie In which year most movie and Tv show released 
[image](![Screenshot 2024-05-18 163014](https://github.com/AsfandAliMemon25/Data-Warehousing-Netflix-Data-Analysis/assets/154571318/dbb733fc-d736-425d-a13e-3bcd613ae4f6)
)


### Conclusion: <br/>
The analytics built in Tableau using data transformed by the data source helped answer the problems we identified during the planning section and learned from data analysis that there are room to improve the movie/show selections in genres that received high IMDB rating, produce more high quality Netflix original movies/shows and increase movies/shows from countries that have higher than average IMDB ratings to attract more and retain existing subscriptions. <br/>

During this project , I got the opportunity to work on tasks that are practical and identical to real life project and it was a tremendous and valuable experience. I have learned about ETL, MYSQL and tableau to Data Visualization and also Data Visualization using Python how to figure out what directions to seek answers when I was stuck, effectively ask and follow-up with questions, perform researches (mostly online) using keywords and quickly acquired the necessary skillsets to solve various problems I ran into. I hope it will be beneficial for me as a Data Analyst or any other positions in the future. 

