🎬 Movie Recommender System
This is a content-based Movie Recommender System built using Python, Streamlit, and TMDb API. It suggests movies similar to the user's selection and displays posters using TMDb.

📌 Features
Recommend 5 similar movies based on selected input

Display movie posters using TMDb API

User-friendly interface built with Streamlit

Lightweight and fast recommendation engine

📂 Project Structure
perl
Copy
Edit
movie-recommender-system/
│
├── app.py                 # Streamlit app script
├── movies.pkl             # Movie metadata (title + id)
├── similarity.pkl         # Precomputed similarity matrix
├── requirements.txt       # List of Python dependencies
└── README.md              # Project documentation
🚀 How to Run
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Streamlit app
bash
Copy
Edit
streamlit run app.py
🧠 How It Works
The system uses a content-based filtering approach.

Movie data is vectorized using NLP techniques.

Cosine similarity is calculated between movies.

The top 5 most similar movies are displayed along with posters.

🔑 TMDb API Key Setup
To fetch movie posters, the app uses The Movie Database (TMDb) API.

Go to TMDb

Sign up and navigate to Settings → API → Request API Key

Replace the placeholder API key in your app.py:

python
Copy
Edit
api_key = 'YOUR_TMDB_API_KEY'
📸 Screenshots
Movie Selection	Recommendations

🛠️ Requirements
Python 3.7+

streamlit

pandas

requests

pickle

scikit-learn (if preprocessing is included)

🙋‍♂️ Author
Yuvrajsinh Rajput
📧 rajputyuvrajsinh@example.com
💼 LinkedIn
