# Taylor Swift Big Data Project </br>

<ins>**By:**</ins> Spencer Hao, Lucy Kopin, Margo Lewis

<ins>**Blog post**</ins> (https://medium.com/@lewism2_11369/taylor-swift-analyzer-understanding-taylor-swift-over-time-66eb88e46aca)

<ins>**Files:**</ins> </br>
**Genius.ipynb </br>**
Contains code to get lyrics from all of Taylor Swift's songs off of Genius. Creates a folder for each album with a file of lyrics for each song.

**ML Models.ipynb </br>**
Contains code to create and evaulate two machine learning models that take in Taylor Swift's songs and predict their album. The first model is based on Spotify API features of each song and the second model is based on a Bag of Words (lyrics) for each song.

**Song_analysis.ipynb </br>**
Uses Genius data to create a wordcloud for each album. Uses sentiment analysis on lyrics to create graphs of the distribution of positive, neutral, and negative lyrics for each album. Also creates a plot of the top 10 most used positive and negative words for each album and their frequencies. 

**SpotifyGetter.ipynb </br>**
Contains code to draw Taylor Swift song metrics from Spotify API and organize by album into individual CSV files and aggregate file. Creates two sets of graphs: 1) graphs with each metric by album and 2) graphs with average of each metric by album
