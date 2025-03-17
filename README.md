
🎬 Movie Recommender System 🎥
This repository contains a content-based movie recommendation system built with Streamlit for an interactive user experience. The system suggests similar movies based on a selected title using precomputed similarity scores.

🚀 Features:
Content-Based Filtering: Recommends movies based on similarity measures.
Interactive UI: Built using Streamlit for an easy-to-use experience.
Movie Posters: Fetches and displays movie posters using The Movie Database (TMDb) API.
Preloaded Data: Uses pickle files for efficient loading of movie data and similarity scores.
📌 How It Works:
Select a movie from the dropdown list.
Click the "Show Recommendation" button.
Get 5 recommended movies along with their posters!
🛠️ Technologies Used:
Python
Streamlit
Pickle (for pre-stored data)
Requests (for fetching posters from TMDb API)
🔧 Setup Instructions:
Clone this repository.
Install dependencies:
# pip install streamlit requests pickle-mixin
Run the application:
# streamlit run app.py
📌 Note: You may need a valid API key from TMDb to fetch movie posters.
