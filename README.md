# Project: Movie Recommender System Using Machine Learning!

This is a streamlit web application that can recommend various kinds of similar movies based on an user interest.
here is a demo,

API CALL IS NOT WORKING WITH JIO NETWORK, TRY USING OTHER !



# Demo:

<img src="https://firebasestorage.googleapis.com/v0/b/portfolio-c5c0a.appspot.com/o/movierecommender.png?alt=media&token=0b6df5be-d02f-43db-b196-cea5db7823b7" alt="workflow" width="70%">

# Dataset has been used:

- [Dataset link](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

# Concept used to build the model.pkl file : cosine_similarity

1 . Cosine Similarity is a metric that allows you to measure the similarity of the documents.

2 . In order to demonstrate cosine similarity function we need vectors. Here vectors are numpy array.

3 . Finally, Once we have vectors, We can call cosine_similarity() by passing both vectors. It will calculate the cosine similarity between these two.

4 . It will be a value between [0,1]. If it is 0 then both vectors are complete different. But in the place of that if it is 1, It will be completely similar.

5 . For more details , check URL : https://www.learndatasci.com/glossary/cosine-similarity/

# How to run?

### STEPS:

Clone the repository

```bash
https://github.com/entbappy/Movie_Recommender_MachineLearning.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
run RecommenderSystem.ipynb to get pickle files
```

```bash
conda create -n movie python=3.7.10 -y
```

```bash
conda activate movie
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

```bash
#run this file to generate the models

Movie Recommender System Data Analysis.ipynb
```

Now run,

```bash
streamlit run app.py
```
