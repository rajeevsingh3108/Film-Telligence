# Film Telligence

This project is a simple yet effective Movie Recommendation System built using Python and the Pandas library. It leverages a subset of the MovieLens dataset to recommend movies based on user input and movie correlations.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This Movie Recommendation System analyzes user ratings and movie data to suggest similar movies based on a selected title. The system uses correlation techniques to find movies that are most similar to the one entered by the user.

## Features
- Input a movie title and get the top 4 recommended movies.
- Utilizes Pandas for data manipulation and analysis.
- Simple and interactive interface (via Jupyter Notebook).
- Easy to extend and customize for more advanced recommendation logic.

## Dataset
- **dataset.csv**: Contains user ratings for movies (subset of MovieLens dataset).
- **movieIdTitles.csv**: Maps movie IDs to their titles.
- **MovieRecommendations.csv**: Stores generated recommendations (optional/output).

## Requirements
- Python 3.7+
- pandas
- numpy
- Jupyter Notebook (for running the notebook interface)

## Installation
Follow these steps to clone and set up the project:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/rajeevsingh3108/Film-Telligence.git
   ```
   Or download the ZIP and extract it.

2. **Navigate to the project directory:**
   ```sh
   cd Film Telligence
   ```

3. **(Optional) Create a virtual environment:**
   ```sh
   python -m venv venv
   venv\Scripts\activate
   ```

4. **Install required packages:**
   ```sh
   pip install pandas numpy jupyter
   ```

## How to Run
1. **Start Jupyter Notebook:**
   ```sh
   jupyter notebook
   ```

2. **Open the notebook:**
   - Open `Movie Recommender System.ipynb` in your browser via the Jupyter interface.

3. **Run the cells:**
   - Follow the instructions in the notebook. Enter a movie title in the input bar to get recommendations.

## Usage
- Enter the name of a movie in the provided input bar.
- The system will output the top 4 recommended movies based on correlation analysis.
- You can modify the code to change the number of recommendations or the recommendation logic.

## Project Structure
```
Movie-Recommendation-System-Using-Python-and-Pandas-master/
│
├── dataset.csv                # User ratings data
├── movieIdTitles.csv          # Movie ID to title mapping
├── MovieRecommendations.csv   # Output recommendations (optional)
├── Movie Recommender System.ipynb  # Main Jupyter Notebook
└── README.md                  # Project documentation
```

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to your fork.
4. Open a pull request describing your changes.

## License
This project is for educational purposes. Please check the dataset's original license for usage restrictions.
