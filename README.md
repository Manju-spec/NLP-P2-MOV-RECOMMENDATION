# NLP-P2-MOV-RECOMMENDATION
A content-based movie recommender system built using Natural Language Processing (NLP) techniques. This project recommends movies based on the similarity of their plot/storylines using TF-IDF vectorization and cosine similarity.

About
This project uses movie storylines (overview/plot) to recommend similar movies. Unlike systems that rely on user ratings, this one focuses on the content itself. The system is built using Python, Jupyter Notebook for model training, and Flask for web deployment.

Features
Content-based movie recommendations
NLP preprocessing: lowercasing, removing stopwords, etc.
TF-IDF vectorization + cosine similarity
Flask-based web app with simple UI
Scalable and customizable with additional metadata


Project Flow
User inputs movie title
System fetches storyline and preprocesses it
Vectorizes all storylines using TF-IDF
Computes similarity using cosine similarity
Displays top N similar movies on the web interface


Installation
# Navigate to project
cd imdb-storyline-recommender

# Install dependencies
pip install -r requirements.txt

# Train the model (Jupyter Notebook)
jupyter notebook training.ipynb

# Run the Flask app
python app.py
