# ML
# Recommender Systems with Python 
##(Thanks Dr Tarek Aly )
## how to implement Recommender systems with python 


What is Recommender Systems : They are used to predict the "rating" or "preference" that a user
would give to an item.
 > Amazon uses it to suggest products to customers. </br>
 > YouTube uses it to decide which video to play next on autoplay. </br>
 > Facebook uses it to recommend pages to like and people to follow.  </br>
 > There are also popular recommender systems for domains like restaurants, movies, and online dating. </br>
## Libraries Part : 
 ## Pandas :  is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.
 ## Sklearn : Simple and efficient tools for predictive data analysis - Accessible to everybody, and reusable in various contexts - Built on NumPy, SciPy, and matplotlib- Open source, commercially usable - BSD license
 ## NumPy is a general-purpose array-processing package. It provides a high-performance multidimensional array object, and tools for working with these arrays. It is the fundamental package for scientific computing with Python
 
 
 Smample of code uisng Panda : 
 
## Import Pandas
import pandas as pd
## Load Movies Metadata
metadata = pd.read_csv('movies_metadata.csv',
low_memory=False)
## Print the first three rows
metadata.head(3)

## Sort movies based on score calculated above
q_movies = q_movies.sort_values('score', ascending=False)

## Print the top 15 movies
q_movies[['title', 'vote_count', 'vote_average', 'score']].head(20)
