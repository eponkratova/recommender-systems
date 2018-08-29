# Recommender-systems
The code prepared as a part of the 'Recommender Systems Specialization' from University of Minnesota (https://www.coursera.org/specializations/recommender-systems)

## Introduction to Recommender Systems
The first assignment to the course 'Introduction to Recommender Systems' introduces non-personalized and lightly-personalized recommendations (see the file 1st_assignment). The dataset 'HW1-data' includes headers that provide movie ID and user ID (but not name). There is a second column that represents gender, with 1=female and 0=male. The rest of the cells are a 20x20 ratings matrix (user-movie ratings) where blank cells represent the lack of a rating. 

During the second assignment to the course 'Introduction to Recommeder Systems', content-based profiles are created (see the file 2nd assignment). The dataset contains a table of content attributes for 20 documents across 10 attributes. It also lists two users’ evaluations of five documents each. For purposes of this assignment, content attributes are treated as boolean (either an article is about a topic or it isn’t) and evaluations as positive (liked it), negative (disliked it), or unknown (never saw it).

## Nearest Neighbor Collaborative Filtering
The first assignment to the course 'Nearest Neighbor Collaborative Filtering' requires to implement user-user collaborative filtering (see the file 1st_assignment_collab). The dataset is a 25 user x 100 movie matrix of ratings selected from the class data set. 

The second assignment will explore item-based collaborative filtering. The dataset is a 20x20 matrix where columns represent movies, rows represent users, and each cell represents a user-movie rating (see the file 2nd_assignment_collab).
