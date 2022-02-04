**Step 2:** Let us now create an RDD using a file from the file system. We shall be using the textFile API to create an RDD from the file system. 

Ratings.csv - http://bit.ly/2L8IEBS

Each line of this file represents one rating of one movie by one user, and has the following format: userId,movieId,rating,timestamp

`val ratings = sc.textFile("files/spark-rdd/ratings.csv")` 