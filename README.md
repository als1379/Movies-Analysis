# Movie Dataset Analysis Using Bayesian Networks

## Overview

This project involves the analysis of a movie dataset using Bayesian Networks. Bayesian Networks are probabilistic graphical models that represent a set of variables and their conditional dependencies through a directed acyclic graph (DAG). The analysis aims to uncover relationships between various attributes in the dataset, such as genres, budgets, ratings, and box office performance, and make predictions based on probabilistic reasoning.

## Objectives

- **Understand Relationships**: Identify and quantify relationships between different features in the movie dataset.
- **Predict Outcomes**: Use the Bayesian Network to predict attributes such as the success of a movie (e.g., box office revenue) based on other factors.
- **Data Visualization**: Visualize the network and dependencies for better interpretability.

## Dataset

The dataset includes the following key features:

- **Movie Title**: Name of the movie.
- **Genre**: Categories such as action, comedy, drama, etc.
- **Director**: Name of the director.
- **Budget**: Production cost of the movie.
- **Box Office Revenue**: Total earnings from ticket sales.
- **IMDB Rating**: Viewer ratings on a scale of 1 to 10.
- **Cast**: Information about the main actors.
- **Release Year**: The year the movie was released.

## Methodology

1. **Data Preprocessing**

   - Handle missing values.
   - Encode categorical variables.
   - Normalize numerical data.

2. **Bayesian Network Construction**

   - Use domain knowledge and algorithms to construct the Bayesian Network.
   - Identify conditional dependencies between features.

3. **Parameter Learning**

   - Estimate conditional probability distributions for each node in the network.

4. **Inference**

   - Perform queries to predict or analyze relationships.
   - Examples:
     - "Given a high budget and top-rated director, what is the probability of a movie earning more than \$100M?"
     - "What are the most influential factors affecting IMDB ratings?"

5. **Evaluation**

   - Validate the network using metrics like log-likelihood and accuracy on test queries.

## Tools and Technologies

- **Python**: Core programming language for data analysis.
- **Libraries**:
  - `pgmpy` or `pomegranate` for Bayesian Network modeling.
  - `pandas` and `numpy` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.
- **Jupyter Notebook**: For an interactive coding environment.

## Results

- Insights into key factors influencing box office success and ratings.
- Predictive capabilities for estimating outcomes based on input features.
- Visual representation of the Bayesian Network and dependencies.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/username/movie-bayesian-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis notebook:
   ```bash
   jupyter notebook analysis.ipynb
   ```

## Future Work

- Integrate additional datasets (e.g., streaming platform metrics).
- Explore dynamic Bayesian Networks for temporal analysis.
- Extend the model to include sentiment analysis of reviews.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

