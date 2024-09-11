# Movie Recommender System

## Project Overview

The **Movie Recommender System** is a web-based application that uses **Streamlit**, **Pandas**, and **The Movie Database (TMDb) API** to provide movie recommendations. The system helps users discover new movies based on their current preferences.

## Key Features

- **Movie Selection**: Users can select a movie from a dropdown list containing various movie titles.
- **Recommendations**: The app generates five similar movie recommendations based on the selected movie, using a pre-computed similarity matrix.
- **Posters Display**: It fetches and displays movie posters for each recommended movie using the TMDb API.

## How It Works

- **Data**: 
  - Movie data (titles and IDs) is stored in `movies_dict.pkl`.
  - A similarity matrix (pre-calculated) is stored in `similarity.pkl` to find similar movies.

- **TMDb API**: 
  - The app uses the TMDb API to fetch movie posters by passing the movie ID and retrieving the image URL.

- **User Interface**: 
  - Built with Streamlit, the app provides an interactive interface where users select a movie, and the app displays recommendations along with movie posters.

## Objective

The project showcases how to integrate a machine learning-based recommendation system with a user-friendly web interface, and how to use an external API to enhance the user experience by providing movie posters.
