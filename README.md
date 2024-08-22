# Spark ALS Movie Recommendation System

This repository contains a Jupyter Notebook that demonstrates how to build a movie recommendation system using Apache Spark's Alternating Least Squares (ALS) algorithm. The notebook leverages the MovieLens dataset to train and evaluate a recommendation model.

## Overview

The goal of this notebook is to provide an end-to-end example of building a collaborative filtering recommendation system using Spark's ALS model. The notebook covers the following steps:

1. **Data Loading:** Load and preprocess the MovieLens dataset, which consists of user ratings for movies.
2. **Exploratory Data Analysis (EDA):** Examine the structure and content of the datasets.
3. **Model Training:** Train an ALS model using the user-movie ratings data.
4. **Model Evaluation:** Evaluate the performance of the recommendation system.
5. **Recommendation Generation:** Generate movie recommendations for users based on the trained model.

## Prerequisites

To run this notebook, you need the following installed on your system:

- [Apache Spark](https://spark.apache.org/)
- [Jupyter Notebook](https://jupyter.org/)
- Python 3.x
- PySpark library

You can install the necessary Python dependencies using pip:

```bash
pip install pyspark
```

## Dataset

The notebook uses the [MovieLens 10M Dataset](https://grouplens.org/datasets/movielens/10m/). The dataset includes 10 million ratings for 10,000 movies by 72,000 users. The data is loaded from the following files:

- `ratings.dat`: Contains user ratings for movies.
- `movies.dat`: Contains movie metadata, including titles and genres.

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/spark-als-recommender.git
   cd spark-als-recommender
   ```

2. **Download the MovieLens dataset:**
   
   Download and extract the MovieLens 10M dataset into the repository directory.

3. **Run the notebook:**
   
   Launch Jupyter Notebook and open `spark_recommender.ipynb`.

   ```bash
   jupyter notebook spark_recommender.ipynb
   ```

4. **Execute the cells:**
   
   Follow the instructions in the notebook to execute each cell and build the recommendation system.

## Results

The notebook will output several key results, including:

- A trained ALS model.
- Performance metrics such as Root Mean Square Error (RMSE).
- Example movie recommendations for a sample of users.

## Customization

You can customize the model parameters and the dataset path by modifying the relevant sections in the notebook. Adjusting the ALS hyperparameters can help in tuning the model for better performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The MovieLens dataset is provided by [GroupLens](https://grouplens.org/), a research lab at the University of Minnesota.
