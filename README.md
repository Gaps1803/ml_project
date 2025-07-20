🎬 Movie Recommendation Analysis

📝 Project Overview

This project analyzes movie data from various streaming platforms using the Movies on Streaming Platforms dataset. It leverages data preprocessing and visualization techniques with Python, Pandas, Matplotlib, and Seaborn to compare average IMDb and Rotten Tomatoes ratings across Netflix, Hulu, Prime Video, and Disney+. The goal is to provide insights into movie quality across these platforms, which can inform recommendation systems or user preferences.



✨ Features





Dataset: Uses the Movies on Streaming Platforms dataset, containing movie details such as title, year, age rating, IMDb score, Rotten Tomatoes score, streaming platforms, genres, directors, and more.



Data Preprocessing: Handles missing values and converts Rotten Tomatoes percentages to decimal format for consistent analysis.



Visualization: Generates bar plots to compare average IMDb and Rotten Tomatoes scores across Netflix, Hulu, Prime Video, and Disney+.



Reproducibility: Ensures clear and executable code in a Jupyter Notebook for easy replication and further analysis.



🛠️ Prerequisites

To run this project, ensure you have the following installed:





Python 3.x



Pandas



Scikit-learn



NumPy



Matplotlib



Seaborn



Jupyter Notebook (to run the provided .ipynb file)



🚀 Installation





Clone the Repository:

git clone <repository-url>
cd <repository-directory>



Install Dependencies:

pip install pandas scikit-learn numpy matplotlib seaborn



Download the Dataset:





Obtain the Movies on Streaming Platforms dataset from Kaggle.



Place the dataset file (MoviesOnStreamingPlatforms_updated1.csv) in the project directory or update the file path in the notebook.



📊 Dataset

The project uses the Movies on Streaming Platforms dataset, which includes:





Columns: ID, Title, Year, Age, IMDb, Rotten Tomatoes, Netflix, Hulu, Prime Video, Disney+, Type, Directors, Genres, Country, Language, Runtime.



Size: 16,744 movies with details on availability across Netflix, Hulu, Prime Video, and Disney+.



Key Features:





IMDb and Rotten Tomatoes scores for quality assessment.



Binary indicators (0 or 1) for streaming platform availability.



Categorical data for genres, directors, countries, and languages.

The dataset is preprocessed to handle missing IMDb and Rotten Tomatoes values (filled with 0) and convert Rotten Tomatoes percentages to decimals.



📖 Usage





Run the Jupyter Notebook: Launch movie_recommendation_model.ipynb in Jupyter Notebook and execute the cells sequentially:

jupyter notebook movie_recommendation_model.ipynb



Key Notebook Steps:





Dependency Installation: Installs required libraries (Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn).



Data Loading: Loads the dataset from MoviesOnStreamingPlatforms_updated1.csv.



Data Preprocessing: Fills missing IMDb and Rotten Tomatoes values and converts Rotten Tomatoes percentages to decimals.



Analysis and Visualization: Calculates average IMDb and Rotten Tomatoes scores for each platform (Netflix, Hulu, Prime Video, Disney+) and visualizes them using a bar plot.



Output: Displays a bar plot comparing average ratings across platforms, with IMDb and Rotten Tomatoes scores side by side.



Interpreting Results:





The bar plot shows the average IMDb (0–10 scale) and Rotten Tomatoes (0–1 scale) scores for movies on each platform.



Use these insights to understand which platforms host higher-rated movies, aiding in movie recommendations or platform comparisons.



📈 Results





The notebook generates a bar plot comparing average IMDb and Rotten Tomatoes scores across Netflix, Hulu, Prime Video, and Disney+.



The visualization highlights differences in movie quality, with IMDb scores typically ranging from 0 to 10 and Rotten Tomatoes scores normalized to 0 to 1.



The analysis can be extended to filter movies by genre, year, or other attributes for more granular insights.

🤝 Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss improvements, such as adding new visualizations, filtering by genres, or implementing recommendation algorithms.



🙏 Acknowledgments





The Movies on Streaming Platforms dataset is provided by Ruchi798 under the CC0: Public Domain license.



Built with Pandas, Matplotlib, Seaborn, and other open-source libraries.
