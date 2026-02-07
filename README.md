Music Recommendation System

This project implements a Music Recommendation System that provides personalized and diverse music recommendations using Spotify audio features. The system combines content-based filtering with an agentic decision-making layer that dynamically selects recommendation strategies based on reward feedback.

Features
Content-based music recommendation using audio features
Cosine similarity for personalized song matching
Exploration strategy to improve music discovery
Agentic decision layer for dynamic strategy selection
Interactive Streamlit web interface
Album artwork integration using iTunes Search API
Recommendation Logic
Content-Based Filtering: Uses cosine similarity on normalized audio features such as danceability, energy, tempo, and valence.

Exploration Strategy: Introduces diversity by recommending random or playlist-diverse songs.

Agentic Decision Layer: Selects the optimal recommendation strategy using cumulative reward feedback.

Tech Stack
Python
Streamlit
Pandas
NumPy
Scikit-learn
How to Run the Project
The project can be run on a local system by installing the required dependencies and launching the Streamlit application using a single command:

py -3 -m streamlit run agenticai_ui.py
