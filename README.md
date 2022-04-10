## Iris Dataset Clustering - Overview
This peoject was done on the classis Iris dataset
Created a model that uses k-means clustering to group the data into clusters
## Code and Resources Used
Python Version: 3.7
Packages: pandas, numpy, sklearn, matplotlib, seaborn

## Project Methodology

- After loading the libraries and data, the intial exploration of the data was done
- The data was clean and no changes were required
- Next, k-means clustering was done on unscaled data and results were plotted
- Data was scaled
- Number of clusters were determined based on the elbow method
- Clustering was done on the scaled data with the number of clusters determined from the elbow method
## Observations
1. The Eblow method is imperfect (we might have opted for 2 or even 4)
2. k-means is very useful in moments where we already know the number of clusters - in this case: 3
