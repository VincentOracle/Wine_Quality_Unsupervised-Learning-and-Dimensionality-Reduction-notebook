

Instructions for running the code:

1.Download and install Anaconda (https://www.anaconda.com/products/individual).
2.Clone or download the project repository.
3.Open Anaconda Prompt and navigate to the project directory using the "cd" command.
4.Create a new conda environment by running the following command:
conda create --name clustering python=3.8
5.Activate the conda environment:
conda activate clustering
6.Install the required packages:
pip install -r requirements.txt
7.Run the Jupyter notebook:
jupyter notebook
8.Open the notebook "Clustering and Dimensionality Reduction.ipynb" and run the cells sequentially.

One should also note that: Make sure to have the Wine_Quality_Data.csv and Country_data.csv files in the project directory before running the code.
Open a jupyter notebook for running the Unsupervised Algorithmn as follows

We will use the following clustering algorithms on the Jupyter Notebook:
K-Means clustering
Expectation Maximization
For both clustering algorithms, we will use the Euclidean distance as our measure of similarity.
K-Means Clustering:
We will start by applying K-Means clustering to the Wine Quality dataset.
We will run the algorithm with different values of K 
and choose the best K based on the within-cluster sum of squares (WCSS) and the silhouette score.

The last four algorithms are then runned, that is, dimensionality reduction algorithms:
3.	PCA
4.	ICA
5.	Randomized Projections
6.	Any other feature selection algorithm you desire 
