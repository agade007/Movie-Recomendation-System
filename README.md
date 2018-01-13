# movie-recomendation-system
Main aim is to generate movie recommendations for a user, given the movie they already watched and the respective rating they gave for those movies. I used Pandas library for most of data preparation and analysis and approached this problem in the following steps: <br>
 <ul> • Data aggregation and preparation which includes cleaning and sorting. </ul>
  <ul>• Analysis  oFinding similarity between two users. </ul>
  
 Finding Top N recommendations for the active users. 
 
 Data Source and Learning algorithm: I used Movielens data set which is maintained by the Department of Computer Science at the University of Minnesota. There were several data sets available but I chose a small data set of 100K data points where each row is a rating given by one user for one movie at particular date and time. 
 The data set consists of: <br>
  <ul>• 100,000 ratings (1-5) from 943 users on 1682 movies. </ul>
 <ul> • Each user has rated at least 20 movies - Found this through of data exploration.</ul> 
  <ul>• Simple information of users (age, gender, occupation, zip). </ul>

Learning algorithm was K Nearest neighbors of the active user, then use their ratings to predict the active users’ ratings for other movies.
