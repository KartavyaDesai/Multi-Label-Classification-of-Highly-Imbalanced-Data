# Multi-Label-Classification-of-Highly-Imbalanced-Data
Explore and implement multi-label classification of movie genres using poster images. This repository features a TensorFlow-based model architecture inspired by UCML, designed to handle the challenges of imbalanced datasets. Includes training scripts, evaluation metrics, and dataset resources.

### Project Title
**Multi-Label Classification of Highly Imbalanced Image Dataset using a UCML-Based Algorithm: Predicting Movie Genres from Posters**

### Overview
This project aims to perform multi-label classification of movie genres based on their posters. The objective is to develop a model that effectively extracts features and makes predictions, overcoming bias and handling the significant class imbalance present across multiple genre categories in the dataset.

### Features
- **Dataset:** Approximately 8000 unique movie posters spanning 20 genres.
- **UCML-Inspired Architecture:** Utilizes an architecture inspired by UCML (Uncorrelated Cost Sensitive Multiset Learning) to mitigate bias and manage class imbalance.

### Dependencies
- Pandas
- Numpy
- TensorFlow
- Scikit-learn

### Dataset
The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/neha1703/movie-genre-from-its-poster).

### Model Architecture
![Model Architecture](https://github.com/KartavyaDesai/Multi-Label-Classification-of-Highly-Imbalanced-Data/assets/126103657/29087f7d-66fb-43a0-aad0-87dddd34102b)


### Subset Construction
![Subset Construction Strategy - 1](https://github.com/KartavyaDesai/Multi-Label-Classification-of-Highly-Imbalanced-Data/assets/126103657/707e16db-f06f-4e1f-b624-a3c87bd3a017)


### Training
The final model is trained using a neural network framework where weights are shared between multiple subsets. Each subset enhances the cluster structure using a neighbor discriminant term and encourages complementary feature learning to diversify feature extraction over time.

### Evaluation
Each subset is evaluated separately using the final model. Evaluation metrics include:
- Hamming Loss
- Accuracy
- F1 Score
- Precision
- Recall

### Acknowledgements
Special thanks to Dr. Soumi Chhatopadhyay and Prolay Mallick for their invaluable guidance throughout the project, without whom this work would not have been possible.

### Genre Labels
The following genres are considered for classification:
- Comedy
- Drama
- Action
- Crime
- Horror
- Romance
- Adventure
- Thriller
- Mystery
- Fantasy
- Sci-Fi
- Family
- Documentary
- Animation
- Music
- Biography
- History
- Sport
- War
- Musical

