# Anime Recommendation System
Alamein University  
Faculty of Computer Science & Engineering  
![Project Banner](network-banner.png)

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

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Anime-Recommendation-System.git
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt

5. Download the dataset:
   ```bash
   https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database
7. Run the application:
   ```bash
   python anime_recommender.py

📑 Usage
Open the GUI, select a recommendation model, and enter an anime title.
Get anime recommendations based on the chosen model.
Explore different models and find the best recommendations for you!
