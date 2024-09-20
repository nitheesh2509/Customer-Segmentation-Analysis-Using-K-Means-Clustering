
# Customer Segmentation Using K-Means Clustering

## Overview

This project focuses on segmenting customers based on their annual income and spending score using the K-Means clustering algorithm. This analysis helps identify distinct customer groups, enabling targeted marketing strategies and personalized customer service.

## Key Features
- **Elbow Method**: Determines the optimal number of clusters for K-Means.
- **K-Means Clustering**: Segments customers into 5 distinct clusters based on their annual income and spending score.
- **Visualizations**: Provides clear, colored scatter plots to visualize the clusters.
- **Model Saving**: Saves the trained K-Means model using `joblib` for later predictions.

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/nitheesh2509/Customer-Segmentation-Analysis-Using-K-Means-Clustering.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Customer-Segmentation-Analysis-Using-K-Means-Clustering
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Explore the notebook:
   - Run the `Customer_Segmentation.ipynb` notebook to see the clustering process and visualizations.

## How to Use

- **Data Analysis**: Perform data preprocessing and exploratory analysis.
- **Clustering**: Apply K-Means to cluster customers based on income and spending scores.
- **Visualization**: Visualize the results of clustering.
- **Model Prediction**: Use the saved model to make predictions on new data points.

## Requirements

- Python 3.x
- pandas
- matplotlib
- scikit-learn
- joblib

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
