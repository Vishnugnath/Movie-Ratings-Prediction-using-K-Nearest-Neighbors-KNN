
# Movie Ratings Prediction Using K-Nearest Neighbors (KNN)

This project implements a K-Nearest Neighbors (KNN) algorithm to predict movie ratings based on user-defined tags and genres. The aim is to provide insights into how users might rate movies given certain attributes.

## Table of Contents

- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [How to Run the Notebook](#how-to-run-the-notebook)
- [File Structure](#file-structure)
- [Requirements](#requirements)
- [License](#license)

## Project Overview

The Movie Ratings Prediction project utilizes KNN to predict ratings for movies based on user input for tags and genres. The model is trained on a dataset comprising user ratings, movie details, and associated tags. The KNN algorithm is chosen for its simplicity and effectiveness in handling multi-dimensional data.

## Datasets

The project uses the following datasets located in the `/dataset` directory:

- **links.csv**: Contains identifiers that can be used to link to other sources.
  - Columns: `movieId`, `imdbId`, `tmdbId`
  
- **movies.csv**: Contains movie information.
  - Columns: `movieId`, `title`, `genres`
  
- **ratings.csv**: Contains ratings of movies by users.
  - Columns: `userId`, `movieId`, `rating`, `timestamp`
  
- **tags.csv**: Contains tags applied to movies by users.
  - Columns: `userId`, `movieId`, `tag`, `timestamp`

## How to Run the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/Vishnugnath/Movie-Ratings-Prediction-using-K-Nearest-Neighbors-KNN.git
   cd Movie-Ratings-Prediction-using-K-Nearest-Neighbors-KNN
   ```

2. Install the required libraries:
   ```bash
   pip install pandas scikit-learn
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Movie Ratings Prediction K-Nearest Neighbors (KNN).ipynb"
   ```

4. Follow the instructions in the notebook to train the model and make predictions.

## File Structure

```
/Movie-Ratings-Prediction-using-K-Nearest-Neighbors-KNN/
├── dataset/
│   ├── links.csv
│   ├── movies.csv
│   ├── ratings.csv
│   └── tags.csv
├── "Movie Ratings Prediction K-Nearest Neighbors (KNN).ipynb"
└── README.md
```

## Requirements

- Python 3.x
- pandas
- scikit-learn
- jupyter

## License

This project is licensed under the MIT License. See the LICENSE file for details.
