Objective: In this notebook, I will be going over a binary classification problem for movie reviews. The walkthrough will also be on my blog if you have access to that through my portfolio website. 
The objective will be to classify movie reviews as being either positive or negative, based on the content given in the reviews text. 

Dataset:

For this example, we are going to use the IMDB dataset. This dataset contains a set of 50,000 polarized reviews from the movie database. 
It is split into two categories of 25,000 reviews; one for training and one for testing. 
Each of the two sets contain 50% of positive and 50% of negative classes. 
Just as the last example when we used the MNIST dataset, we can access the IMDB dataset from within the Keras package. 
This dataset is already processed, meaning, the sequences of words have already been transformed into integers ready for modeling. 
