# 🎬 Movie Recommender System
This is a Movie Recommender System built using Python, Streamlit, Pandas, and Machine Learning techniques. It suggests movies based on user preferences using cosine similarity and natural language processing (NLP).

🚀 Features
📌 Movie Recommendation: Get top 5 similar movie recommendations based on a selected movie.
🎞️ Movie Posters: Displays posters of recommended movies fetched using The Movie Database (TMDb) API.
🏷️ Tag-Based Matching: Uses genres, keywords, cast, crew, and overview for similarity calculation.
🤖 Machine Learning: Implements CountVectorizer and Cosine Similarity for recommendations.
🌐 Interactive UI: Built using Streamlit for a seamless user experience.

# Below are the images of the Movie Recommendation System
![Screenshot 2025-02-26 190122](https://github.com/user-attachments/assets/91a17f8a-0057-454b-a3b8-c3842bcd6c9c)
![Screenshot 2025-02-26 190151](https://github.com/user-attachments/assets/e1e5cb1e-b44b-4366-bd97-540595ded7d7)
![Screenshot 2025-02-26 190224](https://github.com/user-attachments/assets/2117e3c5-6319-4846-801d-c2e3ca285022)
![Screenshot 2025-02-26 190234](https://github.com/user-attachments/assets/17a01cb6-f26e-4524-b7dc-1f30f8949d62)


📂 Project Structure

📁 Movie-Recommender
│-- 📜 App.py          # Streamlit app for UI and recommendations
│-- 📜 Movie.py        # Data processing and similarity calculation
│-- 📜 movie_dict.pkl  # Preprocessed movie data
│-- 📜 similarity.pkl  # Precomputed similarity matrix
│-- 📂 Data            # CSV files with movie and credit details


🛠️ Technologies Used:

Python 🐍

Pandas, NumPy 📊
Scikit-Learn 🤖
Streamlit 🌐
Pickle 📦
TMDb API 🎥


🔧 Setup & Installation
1️⃣ Clone the repository:

git clone https://github.com/your-username/Movie-Recommender.git
2️⃣ Install dependencies:

pip install -r requirements.txt
3️⃣ Run the Streamlit app:

streamlit run App.py
📸 Screenshots
(Add screenshots of your app UI here)

💡 How It Works

Select a movie from the dropdown list.
Click on the "Recommend" button.
The system displays 5 recommended movies along with their posters.
📌 Future Enhancements
🎯 Add more advanced recommendation techniques (e.g., deep learning-based recommendations).
🌍 Support multilingual recommendations.
📊 Include additional filtering options (e.g., genre-based recommendations).
🤝 Contributing
Feel free to open issues and submit pull requests! 🎉
