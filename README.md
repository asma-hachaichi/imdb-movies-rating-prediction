# IMDb Ratings Predictor

## Overview

This project dives deep into figuring out IMDb movie ratings, mixing data science and machine learning tricks. It started with scraping IMDb to pull together a detailed dataset with features like genre, runtime, year, and more. After getting that dataset ready, a Jupyter notebook was put together to train a model that tries to predict IMDb movie ratings using all those features.

## Project Structure

- **Data Collection**: Utilized web scraping techniques to extract detailed movie information from IMDb. The script ensures data integrity and relevance, catering to a broad analysis scope.
- **Dataset**: The compiled dataset is a result of extensive data cleaning and preprocessing, making it ready for exploratory data analysis and model training.
- **Model Training Notebook**: A Jupyter notebook that walks through the data analysis, feature engineering, and model training process. It showcases the methodology for predicting movie ratings, including model selection, training, evaluation, and refinement.
- **Results**: Our model demonstrates promising accuracy in predicting IMDb ratings, providing insights into significant factors influencing movie ratings.

## Dataset Description

This dataset is designed for analyzing and predicting IMDb movie ratings. It comprises a curated collection of features extracted from IMDb, targeting a wide range of movies across different genres and years. The dataset is structured to facilitate both exploratory data analysis and the development of machine learning models to predict movie ratings. Below is a detailed description of the dataset's features and the label.

### Features

- **Title**: The name of the movie. It is a string that represents the movie's original title as listed on IMDb.
- **Year**: The release year of the movie. This is an integer value representing the year the movie was first released to the public.
- **Runtime**: The duration of the movie in minutes. It is an integer value that represents the total runtime of the movie, including all credits.
- **Genre**: The genre(s) of the movie. This is a string or list of strings that categorizes the movie into one or more genres, such as Drama, Comedy, Thriller, etc.

### Label

- **Rating**: The IMDb rating of the movie. This is a numerical value ranging from 0 to 10, representing the average rating given by IMDb users. The rating is a float value, allowing for a nuanced assessment of a movie's reception.

## Technologies Used

- Python for web scraping (BeautifulSoup, requests) and data manipulation (Pandas, NumPy).
- Jupyter Notebook for interactive data analysis and model training.
- Scikit-learn for machine learning model development and evaluation.

## How to Use

1. **Data Collection**: Run the scraping script to collect your dataset. Adjust the parameters as needed to target specific movie attributes or time frames.
2. **Exploratory Data Analysis**: Use the provided notebook to explore the dataset, uncover patterns, and prepare the data for modeling.
3. **Model Training**: Follow the steps in the notebook to train the machine learning model. Experiment with different algorithms and parameters to improve accuracy.
4. **Evaluation**: Assess the model's performance using the evaluation metrics provided in the notebook.

## License

This project, which cleverly collects movie information from IMDb using scraping tools and uses this data to guess movie ratings, is openly shared under the MIT License. This ensures that anyone interested can use, modify, and distribute the work or any derivative versions, promoting open collaboration and innovation.
