Anime Recommendation System

📋 Project Description
This Anime Recommendation System is built using Python and various machine learning models, designed to recommend anime based on user preferences. It features:

Multiple Recommendation Models: Cosine similarity, KNN, Random Forest, and Naive Bayes.
Data Preprocessing: Clean the data and extract relevant features for modeling.
User Interface: A Tkinter-based GUI for an interactive experience.
Anime Dataset: The system uses the Anime Recommendations Database.

🌟 Features
Cosine Similarity: Recommends anime using CountVectorizer or TfidfVectorizer.
K-Nearest Neighbors (KNN): Finds similar anime based on synopsis.
Random Forest & Naive Bayes: Models trained to predict scores and titles.
Interactive GUI: Built with Tkinter for easy user interaction.
Multiple Models: Users can choose between different recommendation algorithms.

🛠️ Requirements
pandas: For data manipulation.
numpy: For array operations.
scikit-learn: For machine learning models like KNN, Random Forest, and Naive Bayes.
tkinter: For creating the graphical user interface (GUI).
PIL: For handling images in the GUI.
requests: For fetching images from the web.
matplotlib: (Optional) For visualizations.

📦 Installation
Clone the repository:
 ```bash
 git clone https://github.com/your-username/Anime-Recommendation-System.git

Install the dependencies:
  ```bash
 pip install -r requirements.txt
Download the Anime Recommendations Database:https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database

Run the application:
  ```bash
 python anime_recommender.py
