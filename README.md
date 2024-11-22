# Movie Recommender System 

This project is a **content-based movie recommender system** developed using the **TMDB dataset**. The system recommends movies based on user preferences by analyzing key features such as **genres, keywords**, and **cast**.

## Technologies Used
- **Python** for the development and data processing.
- **Pandas** and **NumPy** for handling and manipulating data.
- **scikit-learn** for calculating **cosine similarity** and creating recommendation algorithms.

## Features
- **Cosine Similarity**: Measures similarity between movies based on extracted features.
- **TMDB Dataset**: Used as a source for movie data, including metadata like genres, keywords, and cast.
  
## Approach
1. Extracted relevant features from the dataset.
2. Used **cosine similarity** to compare movies and generate recommendations.
3. Built a recommendation engine capable of suggesting movies based on user input.

## How to Run
1. Clone this repository.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python script to get movie recommendations.

## Future Improvements
- Integration of collaborative filtering for hybrid recommendation.
- Adding a user interface for interactive use.

Enjoy exploring the movie recommendations!
