# classification_song_interest

Will You Like Music?

The main inspiration behind this project is to determine if a person will like music based on a series of questions and queries.

## Data Source
https://www.kaggle.com/c/MusicHackathon/data
  * ~300,000 rows
  
## EDA

### Correlation Plot

Q1: I enjoy actively searching for and discovering music that I have never heard before
Q2: I find it easy to find new music
Q3: I am constantly interested in looking for
more music
Q7: I enjoy music primarily from going out to
dance
Q8: Music for me is all about nightlife and 
going out
Q17: I find a new artist / band on TV a useful way
of discovering new music
Q18: I like to be at the cutting edge of new music

As you can see, there is a strong correlation between Q1 and Q3. This shows us that these questions are highly correlated, in which one of the questions were removed to create a better model.

# Best Model
## KNN

* **Accuracy: .76882
* **F- Score: .82
* **Best params: {‘metric’ : ‘manhattan’, ‘n_neighbors’:3, ‘weights’: ‘distance’}
