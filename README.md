# imdb-movie-reviews-sentiment-analysis

The goal of this project was to build a binary sentiment analyzer using Logistic Regression. I have implemented a custom Logistic Regression class from scratch as well as using Sci-Kit and reported the accuracy and F1 for each of the two models trained. A key takeaway from this project was using textual data to create feature vectors. In simple terms, we want to classify whether a movie review is positive or negative. 

About the Dataset:

I have borrowed the IMDB Movie Reviews Dataset from Kaggle (Link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data). The dataset contains 50,000 reviews split evenly into 25k train and 25k test sets. The overall distribution of labels is balanced (25k pos and 25k neg).There are two top-level directories `[train/, test/]` corresponding to the training and test sets. Each contains `[pos/, neg/]` directories for the reviews with binary labels positive and negative. Within these directories, reviews are stored in text files named following the convention `<id>_<rating>.txt` where `id` is a unique id and `rating` is the star rating for that review on a 1-10 scale.

For any queries, feel free to reach out to me at 25100325@lums.edu.pk
