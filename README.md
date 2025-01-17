
# Movie Recommender System

A content-based movie recommendation system that uses machine learning techniques to suggest movies based on user preferences. This project processes the 5000 Movies dataset, leveraging feature extraction and similarity metrics to deliver personalized recommendations. 

## Features
- Suggests movies based on genres, keywords, cast, and crew information.
- Interactive user interface built with Streamlit for a seamless user experience.
- Efficient and scalable implementation using cosine similarity.

## Tech Stack
- **Frontend**: Streamlit
- **Backend**: Python, Scikit-learn
- **Data Processing**: Numpy, Pandas

## Dataset
The system utilizes the **5000 Movies dataset**. This dataset includes metadata about movies such as genres, keywords, cast, and crew.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommender-system.git
   cd movie-recommender-system
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
2. Open the local server link in your browser (usually `http://localhost:8501`).
3. Enter a movie name in the search bar to receive recommendations.

## Methodology
1. **Data Preprocessing**: Cleaned and processed the dataset to extract relevant features (e.g., genres, keywords, cast, and crew).
2. **Feature Vectorization**: Used Scikit-learn's CountVectorizer for text vectorization.
3. **Similarity Calculation**: Implemented cosine similarity to measure the closeness between movie feature vectors.
4. **Recommendation Logic**: Sorted movies based on their similarity scores to the input movie.

## Future Enhancements
- Incorporate user feedback to improve recommendations.
- Add collaborative filtering for enhanced personalization.
- Expand dataset to include user ratings and reviews.


## Contact
For questions or suggestions, feel free to reach out:  
Email: [mamillatejaswini345@gmail.com](mailto:mamillatejaswini345@gmail.com)
