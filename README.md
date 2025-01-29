# Book Recommendation System

This repository contains a **Book Recommendation System (BRS)** implemented in Python using **KNN (K-Nearest Neighbors)**. The system analyzes book ratings and metadata to suggest books based on user preferences.

## Features
- **Data Exploration**: Analyzes book scores, authors, and comment trends.
- **Data Preprocessing**: Cleans and normalizes the dataset using MinMax scaling.
- **Recommendation System**: Uses the KNN algorithm to provide book recommendations.

## Dataset
The dataset includes book ratings, authors, and user reviews, with scores ranging between 0 and 5. It has been cleaned and prepared for analysis.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/your-repository.git
   ```
2. Navigate to the project folder:
   ```sh
   cd your-repository
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the Jupyter Notebook to execute the analysis and recommendation system:
```sh
jupyter notebook brs.ipynb
```

## Algorithm
- **Data Processing**: Combines multiple dataframes, renames features, and scales values.
- **KNN Implementation**: Uses similarity metrics to suggest books based on input preferences.

## Results
- Identifies top-rated books and most reviewed books.
- Provides book recommendations based on user preferences.

