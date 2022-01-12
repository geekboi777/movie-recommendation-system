## Movie-Recommendation-System

# What is a Recommendation System ?

The following repository contains the working code for the movie recommendation system that I developed.
Simply put a Recommendation System is a filtration program whose prime goal is to predict the “rating” or 
“preference” of a user towards a domain-specific item or item. In our case, this domain-specific item is a movie,
therefore the main focus of our recommendation system is to filter and predict only those movies which a user 
would prefer given some data about the user him or herself.

# Different types of filtering in a Recommendation System ?

The system could be collaborative based or content based. The above project utilizes content-based filtering.
This filtration strategy is based on the data provided about the items. The algorithm recommends products that 
are similar to the ones that a user has liked in the past. This similarity (generally cosine similarity) is 
computed from the data we have about the items as well as the user’s past preferences.
For example, if a user likes movies such as ‘The Prestige’ then we can recommend him the movies of ‘Christian Bale’
or movies with the genre ‘Thriller’ or maybe even movies directed by ‘Christopher Nolan’.So what happens here the 
recommendation system checks the past preferences of the user and find the film “The Prestige”, then tries to find 
similar movies to that using the information available in the database such as the lead actors, the director,
genre of the film, production house, etc and based on this information find movies similar to “The Prestige”.


