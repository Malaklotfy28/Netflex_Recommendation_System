# Netflix Content Recommendation System

## Project Overview

This project implements a content-based recommendation system
for Netflix titles using Python and Machine Learning techniques.

The system recommends similar movies or TV shows based on
their content-related features.

## Dataset

The dataset contains Netflix titles and information such as:

- Title
- Type
- Director
- Country
- Release Year
- Rating
- Genres

## Methodology

The project follows these steps:

1. Data loading
2. Data exploration
3. Data cleaning
4. Feature engineering
5. Text vectorization using TF-IDF
6. Cosine similarity calculation
7. Recommendation generation
8. Recommendation evaluation
9. Data visualization

## Machine Learning Technique

TF-IDF is used to convert textual content features into
numerical vectors.

Cosine similarity is then used to measure the similarity
between Netflix titles.

## Recommendation System

The system accepts a Netflix title and returns the most
similar titles based on their content features.

## Evaluation

Recommendation quality is evaluated using genre overlap
between the original title and recommended titles.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn