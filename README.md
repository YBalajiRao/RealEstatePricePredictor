# Real Estate Price Predictor
![GIF Logo](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmxrbHZlbXlxZmVjdGttZ29lcWpjamVkYjdhOXozYTFtMjA4NnFmcSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/fbfV1naktgX34jDNy7/giphy.gif)


Welcome to Real Estate Price Predictor! This project aims to provide insights into real estate pricing and predict property prices based on various features. Whether you're a homebuyer, real estate agent, or investor, this tool can help you make informed decisions about buying or selling properties.

## Overview

This project consists of three main components:

1. **Dataset**: We use a dataset containing information about various properties, such as their area, number of bedrooms and bathrooms, location, and more. You can find the dataset [here](https://github.com/YBalajiRao/RealEstatePricePredictor/blob/main/Housing.csv).

2. **Project Code**: The project code is organized into a Jupyter Notebook, which you can access [here](https://github.com/YBalajiRao/RealEstatePricePredictor/blob/main/RealEstatePricePrediction.ipynb). This notebook guides you through the entire data science pipeline, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and predictions.

3. **Trained Model**: After training the machine learning model on the dataset, we save the trained model using joblib. You can download the trained model [here](https://github.com/YBalajiRao/RealEstatePricePredictor/blob/main/trained_model.joblib). This model can be used to predict property prices based on input features.

## Usage

1. **Clone the Repository**: Begin by cloning the repository to your local machine:
   ```
   git clone https://github.com/YBalajiRao/RealEstatePricePredictor.git
   ```

2. **Install Dependencies**: Install the required Python dependencies by running:
   ```
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**: Launch the Jupyter Notebook containing the project code:
   ```
   jupyter notebook RealEstatePricePrediction.ipynb
   ```

4. **Follow Along**: Follow the instructions and explanations provided in the notebook to explore the dataset, preprocess the data, analyze key features, train the machine learning model, evaluate its performance, and make predictions.

## Project Code Details

The Jupyter Notebook is divided into the following sections:

1. **Data Preprocessing**: We start by loading the dataset and performing preprocessing tasks such as handling missing values, encoding categorical variables, and splitting the data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**: In this section, we conduct exploratory data analysis to gain insights into the dataset. We visualize key features, analyze their distributions, correlations, and relationships with the target variable (property prices).

3. **Model Training**: We train a machine learning model using various algorithms such as Random Forest, Support Vector Machine (SVM), and Linear Regression. We use k-fold cross-validation to evaluate the models' performance and select the best performing model.

4. **Model Evaluation**: We evaluate the selected model's performance using metrics such as Mean Squared Error (MSE) and visualize the actual vs. predicted property prices.

5. **Making Predictions**: Finally, we use the trained model to make predictions on new data, allowing users to estimate property prices based on input features.

## Contributing

Contributions are welcome! If you have any suggestions, feature requests, or bug reports, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/YBalajiRao/RealEstatePricePredictor/blob/main/LICENSE) file for details.
