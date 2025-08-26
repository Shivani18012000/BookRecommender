# 📚 Book Recommender System #

A Python-based book recommendation system that suggests books to users based on their preferences using item-based collaborative filtering and K-Nearest Neighbors (KNN). The system includes an interactive front-end built with Streamlit.

  ## 🔍 Features ##

  * Item-Based Collaborative Filtering: Recommends books similar to the ones the user likes.

  * K-Nearest Neighbors: Calculates similarity distances between books to find the most relevant recommendations.

  * Interactive Front-End: Simple and user-friendly interface using Streamlit for real-time book suggestions.

  * Dynamic Recommendations: Offers personalized book suggestions based on user input.

  * No Pre-Computed Similarity Matrices: Similarity is computed on-the-fly using KNN.

## 🛠️ Technologies Used ##

* Python – Core programming language

* pandas & NumPy – Data manipulation and processing

* scikit-learn – KNN implementation for computing similarity

Streamlit – Front-end for web interface

## 🚀 How to Run ##

* Clone the repository

       git clone https://github.com/Shivani18012000/BookRecommender.git
     
       cd BookRecommender


* Install dependencies

       pip install -r requirements.txt


* Run the Streamlit app
 
       streamlit run app.py


* Interact with the system

   * Enter a book name or select from a list.

   * Get personalized recommendations instantly.

## 📂 Project Structure ##

          book-recommender/
                  │
                  ├── data/               # Dataset files
                  ├── app.py              # Streamlit front-end
                  ├── recommender.py      # Recommendation logic using KNN
                  ├── requirements.txt    # Python dependencies
                  └── README.md
