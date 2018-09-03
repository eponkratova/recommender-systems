# Recommender-systems
The code prepared as a part of the 'Recommender Systems Specialization' from University of Minnesota (https://www.coursera.org/specializations/recommender-systems)

## Introduction to Recommender Systems
The first assignment to the course 'Introduction to Recommender Systems' introduces non-personalized and lightly-personalized recommendations (see https://github.com/eponkratova/recommender-systems/blob/master/1st_assignment_intro.ipynb). The dataset 'HW1-data' includes headers that provide movie ID and user ID (but not name). There is a second column that represents gender, with 1=female and 0=male. The rest of the cells are a 20x20 ratings matrix (user-movie ratings) where blank cells represent the lack of a rating. 

During the second assignment to the course 'Introduction to Recommeder Systems', content-based profiles are created (see https://github.com/eponkratova/recommender-systems/blob/master/2nd_assignment_intro.ipynb). The dataset contains a table of content attributes for 20 documents across 10 attributes. It also lists two users’ evaluations of five documents each. For purposes of this assignment, content attributes are treated as boolean (either an article is about a topic or it isn’t) and evaluations as positive (liked it), negative (disliked it), or unknown (never saw it).

## Nearest Neighbor Collaborative Filtering
The first assignment to the course 'Nearest Neighbor Collaborative Filtering' requires to implement user-user collaborative filtering (see https://github.com/eponkratova/recommender-systems/blob/master/1st_assgnmt_collab.ipynb). The dataset is a 25 user x 100 movie matrix of ratings selected from the class data set. 

The second assignment will explore item-based collaborative filtering. The dataset is a 20x20 matrix where columns represent movies, rows represent users, and each cell represents a user-movie rating (see https://github.com/eponkratova/recommender-systems/blob/master/2nd_assignment_collab.ipynb).

## Recommender Systems: Evaluation and Metrics
The first assignment (see at https://github.com/eponkratova/recommender-systems/blob/master/3rd_assignment_evaluation_metrics.ipynb) tests your ability to compute basic recommender system metrics from a matrix of ratings and a matrix of predicted values for those ratings. Rows 3-12 provide the ratings matrix for 10 users by 10 movies. For example, cell D10 shows a 3.5, showing that user 2492 gave the movie Forrest Gump a score of 3.5 stars. Many cells are empty -- these reflect movies for which we do not have ratings by those users. To make things easier for later computation, we've also included the count of movie ratings per user, and per movie. 
Rows 17-26 provide a similar matrix, but in this case these are predictions from our recommender algorithm. For example, D24 shows 4.2, which means that user 2492 is prediced to give Forrest Gump 4.2 stars. This means the prediction is 0.7 stars higher than the actual rating. Predictions are all between 0 and 5 stars.

## Matrix Factorization and Advanced Techniques
The first assignment (see ) explores matrix factorization collaborative filtering. There are 2 files: an Items and Users files. The Items file contains the feature values for 100 items and 15 features, along with the weight (singular value) for each feature. The Users file contains the feature values for 20 users and those 15 features.
