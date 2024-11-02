# Online Retail K-Means & Hierarchical Clustering
Let’s delve into the intriguing realm of clustering, where we’ll examine K-means and Hierarchical methods to analyze data from online retail.
### Overview of the Online Retail Dataset
The Online Retail dataset encompasses all transactions from December 1, 2010, to December 9, 2011, for a UK-based non-store online retailer specializing in unique gifts for various occasions. A notable portion of its customer base consists of wholesalers. 

We will utilize this transactional dataset to perform K-means clustering and identify the optimal customer segments for the company to target. Discover the valuable insights this dataset has to offer! Access the data [here](https://www.kaggle.com/datasets/hellbuoy/online-retail-customer-clustering).


### Library Descriptions

- **pandas**: A powerful data manipulation and analysis library that provides data structures like DataFrames to handle and analyze structured data efficiently.

- **seaborn**: A statistical data visualization library based on Matplotlib that provides an easy-to-use interface for creating informative and attractive graphics.

- **plotly.express**: A high-level interface for Plotly, enabling the creation of interactive visualizations with simple syntax, ideal for exploring data dynamically.

- **matplotlib.pyplot**: A plotting library that provides a MATLAB-like interface for creating static, animated, and interactive visualizations in Python.

- **sklearn.cluster (KMeans)**: A module from Scikit-learn that implements the K-means clustering algorithm, allowing for partitioning data into distinct groups based on feature similarities.

- **sklearn.metrics (silhouette_score)**: A function that computes the silhouette coefficient, a measure of how similar an object is to its own cluster compared to other clusters, used to evaluate clustering performance.

- ### Clustering Journey: From Wrangling to Visualization

In the exciting world of data analysis, the first step is always to wrangle the data! I kicked things off with a dedicated wrangle function, transforming the dataset into a more convenient format for my analysis. For this customer clustering adventure, I carefully selected two key features from the dataset, laying the groundwork for effective grouping.

As I navigated through calculations to refine the dataset, I documented every step of this journey in my project. My trusty companion for this endeavor was the K-means clustering model. 

One of the intriguing challenges I faced was deciding whether to use a trimmed dataset (without outliers) or the original, non-trimmed version. After some deliberation, I opted for both! This led me to create two distinct models—one for the trimmed data and one for the non-trimmed data. In the initial phase, I focused on simplicity, using three clusters without diving into hyperparameter tuning.

Once I established these preliminary models, it was time for some fine-tuning! I conducted hyperparameter tuning for both models, carefully adjusting parameters to enhance performance. To determine the ideal number of clusters (or the magical "k" value), I visualized the results with two insightful graphs: one depicting the relationship between the silhouette score and the number of clusters, and the other showcasing inertia against the number of clusters.

After analyzing these graphs, I confidently selected a k value of 5. With this decision made, I built my final model and evaluated its performance by plotting a graph that revealed five beautiful clusters, bringing my clustering adventure to a triumphant close!


### Unveiling Insights and Interactive Exploration

As I crafted the final models for both datasets, a pivotal question that had been lingering in my mind found its answer. I meticulously documented all my findings and insights in the project, inviting you to explore and draw your own conclusions from the results.

To make the journey even more engaging, I developed an interactive dashboard that showcases all my findings in a sleek and accessible format. It's a one-stop destination to dive into the insights of my clustering analysis. 

I encourage you to take a look and immerse yourself in the exploration of this project—discover the conclusions, interact with the data, and experience the story behind the clusters firsthand!
