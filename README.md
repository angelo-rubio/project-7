# project-7: Unsupervised Learning (K-Means & Hierarchical Clustering)

## Overview
This project focuses on clustering techniques (K-Means and Hierarchical Clustering) applied to stock market data. By grouping stocks exhibiting similar characteristics, one can make more informed decisions about allocating investments and diversifying portfolios.

## Project Structure
- **USL_Project_LearnerNotebook_FullCode-1.ipynb**: Jupyter Notebook with detailed exploratory data analysis, data preprocessing, and clustering implementation steps.
- **stock_data.csv**: Dataset containing stock data (current price, volatility, financial ratios, etc.) from several NYSE-listed companies.
- **README.md**: Documentation on project purpose, requirements, and usage guidelines.

## Getting Started
1. **Install dependencies**:
   - Python 3.x
   - pandas, numpy, matplotlib, seaborn, scikit-learn, scipy
   - yellowbrick

2. **Set up environment** (example with pip):
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy yellowbrick
   ```

3. **Run the Notebook**:
   1. Open the Jupyter Notebook (USL_Project_LearnerNotebook_FullCode-1.ipynb).
   2. Restart the kernel and run all cells sequentially.

## Methodology
1. **Data Loading**: Reads and cleans the stock dataset.
2. **Exploratory Analysis**: Uses summary statistics and plots to explore data distribution.
3. **Preprocessing**: Standardizes and prepares data for clustering.
4. **K-Means Clustering**: Determines the optimal number of clusters using the elbow method and silhouette analysis.
5. **Hierarchical Clustering**: Explores dendrograms to select the best linkage and clusters.

## Results & Insights
- Stocks are grouped into clusters based on similarities in financial metrics, which aids in creating a balanced and diversified portfolio.
- K-Means provides direct cluster assignments, while Hierarchical Clustering offers a visual representation (dendrogram) of how stocks group together across different levels of similarity.

## Contributing
Contributions in the form of issue reports or suggestions are welcome.