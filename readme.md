# Project Credit Card Customer Segmentation

The Project_CreditCardCustomerSegmentation notebook appears to be a data analysis project that involves segmenting credit card customers based on their credit card usage patterns. Here's a brief summary of the notebook:

The notebook begins by importing the necessary libraries for data manipulation, visualization, and clustering.

The credit card customer data is then loaded into a pandas DataFrame.

The data is preprocessed by removing unnecessary columns, handling missing values, and converting categorical variables to numerical variables.

Exploratory data analysis (EDA) is performed to gain insights into the data and visualize the relationships between different features.

The data is then scaled using the z-score method to ensure that all the features are on the same scale and have equal importance during clustering.

K-means clustering algorithm is applied to segment the customers into different groups based on their credit card usage patterns. The optimal number of clusters is determined using the elbow method and silhouette scores.

Hierarchical clustering algorithm is also applied to the data to compare the results with K-means clustering.

The results of the clustering algorithms are visualized using various plots and graphs.

Overall, the notebook provides a comprehensive analysis of credit card customer data and demonstrates how clustering algorithms can be used to segment customers based on their usage patterns.

## Libraries Used

The following libraries were used in the `Project_CreditCardCustomerSegmentation` notebook:

- Pandas: A library for data manipulation and analysis. It is used to load, clean, and preprocess the credit card customer data.

- Numpy: A library for numerical computing in Python. It is used for various mathematical operations in the notebook.

- Matplotlib and Seaborn: Libraries for data visualization. They are used to create various plots and graphs to visualize the relationships between different features and the results of the clustering algorithms.

- Scikit-learn: A library for machine learning. It is used to scale the data and apply clustering algorithms such as K-means and hierarchical clustering.

- Scipy: A library for scientific computing and technical computing. It is used to compute distances, perform hierarchical clustering, and create dendrograms.

- Yellowbrick: A library for machine learning visualization. It is used to visualize the elbow curve and silhouette scores.
