# Flask-Netflix-Recommendation-System
A flask web-app which can be used to get recommendations for a tv-show/movie, the app recommends a list of media according to the input.

# Screenshot 1 : Main Page 
Here the user can enter their movie of choice, for example I have entered La Casa De Papel a Spanish Netflix original show.
![](Screenshots/screenshot1.PNG)
# Screenshot 2 : Recommendation Page 
Here the user will get recommendations, for example I recieved Elite(another spanish Netflix original) as my top recommendation 
![](Screenshots/screenshot2.PNG)

A flask web-app which can be used to get recommendations for a tv-show/movie, the app recommends a list of media according to the input.

Problem Description :
Netflix is all about connecting people to the movies they love. To help customers find those movies, they developed world-class movie recommendation system: CinematchSM. 
Its job is to predict whether someone will enjoy a movie based on how much they liked or disliked other movies. 
Netflix use those predictions to make personal movie recommendations based on each customer’s unique tastes. And while Cinematch is doing pretty well, it can always be made better.
Now there are a lot of interesting alternative approaches to how Cinematch works that netflix haven’t tried. 
Some are described in the literature, some aren’t. We’re curious whether any of these can beat Cinematch by making better predictions. 
Because, frankly, if there is a much better approach it could make a big difference to our customers and our business.

Problem Statement :
Netflix provided a lot of anonymous rating data, and a prediction accuracy bar that is 10% better than what Cinematch can do on the same training data set. 
(Accuracy is a measurement of how closely predicted ratings of movies match subsequent actual ratings.)

Data Overview 
Source of Data : https://www.kaggle.com/netflix-inc/netflix-prize-data

Data files : combined_data_1.txt combined_data_2.txt combined_data_3.txt combined_data_4.txt movie_titles.csv

The first line of each file [combined_data_1.txt, combined_data_2.txt, combined_data_3.txt, combined_data_4.txt] contains the movie id followed by a colon. 

Each subsequent line in the file corresponds to a rating from a customer and its date in the following format:
CustomerID,Rating,Date

MovieIDs range from 1 to 17770 sequentially. 
CustomerIDs range from 1 to 2649429, with gaps. 
There are 480189 users. Ratings are on a five star (integral) scale from 1 to 5. Dates have the format YYYY-MM-DD.
