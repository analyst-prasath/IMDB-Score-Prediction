# IMDb Score Prediction

This project aims to predict the IMDb score of movies using machine learning algorithms. It uses a dataset of movies that includes various features such as the director, actors, genre, budget, and more.

## Dataset

The dataset used for this project is sourced from IMDb and contains information about thousands of movies. It consists of both numerical and categorical features, including:

- Title: The title of the movie.
- Director: The director of the movie.
- Actors: The main actors in the movie.
- Genre: The genre(s) of the movie.
- Budget: The budget of the movie.
- Duration: The duration of the movie.
- Year: The release year of the movie.
- IMDb Score: The actual IMDb score of the movie (target variable).

The dataset is included in the `dataset.csv` file.

## Dependencies

The following dependencies are required to run the project:

- Python 3.7+
- scikit-learn
- pandas
- numpy
- matplotlib

You can install the required dependencies using pip:

## Usage

1. Clone the repository:


2. Change to the project directory:


3. Install the dependencies (if not already installed):


4. Run the prediction script:


The script will load the dataset, preprocess the data, train a machine learning model, and predict the IMDb scores for a set of test movies.

## Results

After running the prediction script, the predicted IMDb scores for the test movies will be displayed, along with evaluation metrics such as mean squared error (MSE) and R-squared.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please create a new issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.


