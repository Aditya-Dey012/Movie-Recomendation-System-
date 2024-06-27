# MOVIE_RECOMMENDATION_SYSTEM
Google drive video link : https://drive.google.com/file/d/1Fy6IEBHLN741fsCmXYfCe92b-gH3QjVI/view?usp=sharing

This project is a movie recommendation system that suggests movies based on their similarity to a given movie. It uses a combination of data processing, machine learning, and web development techniques to provide recommendations through an interactive web application.

##### Overview

The Movie Recommendation System uses a dataset of movies to recommend similar movies based on their features. It employs natural language processing techniques to analyze movie descriptions and genres, and calculates similarity using cosine similarity. The recommendations are presented in a user-friendly web application built with Streamlit.

#### Features

Data Handling and Preprocessing: Load and process movie data using pandas.
Feature Extraction: Convert text data into token counts using CountVectorizer.
Similarity Calculation: Use cosine similarity to find similar movies.
Model Persistence: Save the recommendation model using pickle.
Web Application: Interactive user interface built with Streamlit.
API Integration: Fetch and display movie posters using the TMDB API.

#### Usage

###### Run the main script to preprocess data and build the model using jupyter, google collab, kaggle, etc:
python main.py (jupyter source file)

###### Launch the Streamlit web application:
open your vs code or anyother application go to the new terminal in the pythone file app.py and type :-
streamlit run app.py

###### Open your web browser and go to http://localhost:8501 to use the application.

#### Technologies Used :
Python: Programming language used for development.
Pandas: Library for data manipulation and analysis.
Scikit-learn: Machine learning library used for feature extraction and similarity calculation.
Streamlit: Framework for building interactive web applications.
Pickle: Module for serializing and deserializing Python objects.
TMDB API: API for fetching movie posters.

#### Dataset : 

The movie dataset used in this project is sourced from Kaggle: https://www.kaggle.com/datasets/ahsanaseer/top-rated-tmdb-movies-10k?fbclid=IwAR2MpWrWpcw2QNCv_FZg2l0sjBh9xAvhrqtnZBO9K-QS6PHI1aHkdB6qLa0

#### Api Key link : https://developer.themoviedb.org/docs/getting-started

Google drive video link : https://drive.google.com/file/d/1Fy6IEBHLN741fsCmXYfCe92b-gH3QjVI/view?usp=sharing

Contributing If you have suggestions or would like to contribute to the project, please feel free to fork the repository and create a pull request. We welcome all contributions that can improve the prototype and enhance the user experience.

License : This project is licensed under the MIT License - see the LICENSE file for details.

Contact For any questions or inquiries, please contact Aditya Dey at aditya2002dey@gmail.com
