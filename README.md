Customer Segmentation

This project contains a Jupyter Notebook that performs customer segmentation using the K-Means and DBSCAN clustering algorithms.

Project Structure

    Customer_Segmentation.ipynb: The main Jupyter Notebook that contains the entire customer segmentation project.

Key Features

    Data Preprocessing: The notebook handles data cleaning by dropping unnecessary columns such as CustomerID, Gender, and Age.

    Modeling: The project uses K-Means clustering to group customers based on their Annual Income and Spending Score. The optimal number of clusters for K-Means was determined using the KElbowVisualizer, which resulted in an inertia of approximately 62. Additionally, a DBSCAN model was manually tuned by finding the best eps and min_samples parameters.

    Visualization: The results of the clustering are visualized in a 3D scatter plot to show the different customer segments.

Requirements

To run this notebook, you will need the following libraries:

    numpy

    pandas

    matplotlib

    scikit-learn

    seaborn

    plotly

You can install these dependencies using pip:

!pip install numpy pandas matplotlib scikit-learn seaborn plotly

Dataset

The dataset used for this project is the Mall Customer Segmentation Data(https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) from Kaggle. The data is read from a CSV file named Mall_Customers.csv and contains information on CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100).
