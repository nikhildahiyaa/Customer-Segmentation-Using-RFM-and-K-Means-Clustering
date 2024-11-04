
# Customer Segmentation Using RFM and K-Means Clustering

## Project Overview
This project performs customer segmentation for a retail business using RFM analysis and K-Means clustering. The segmentation helps identify customer groups based on purchasing behavior, providing insights that can guide targeted marketing and customer retention strategies.

## Dataset
- **Source**: UCI Machine Learning Repository - Online Retail Dataset
- **Period**: Transactions from December 1, 2010, to December 9, 2011
- **Size**: 541,909 rows and 8 columns (InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country)

## Key Steps in the Analysis

1. **Data Cleaning**: Removed entries with missing `CustomerID` values and rows with negative `Quantity` or `UnitPrice` values.
2. **RFM Analysis**: Calculated Recency, Frequency, and Monetary values for each customer and segmented them using quantiles.
3. **K-Means Clustering**: Applied K-Means clustering and determined the optimal number of clusters using the Elbow Method.
4. **Cluster Interpretation**: Defined customer groups such as "Best Customers," "Loyal Customers," "Almost Lost," and "Lost Cheap Customers" based on RFM scores.
5. **Recommendations**: Suggested strategies for each customer segment, including loyalty programs, reactivation campaigns, and retention efforts.

## Requirements
- **Python** 3.x
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `sklearn`

Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

## Usage
1. Clone the repository and open the Jupyter Notebook:
    ```bash
    git clone https://github.com/nikhildahiyaa/Customer-Segmentation-Using-RFM-and-K-Means-Clustering.git
    cd Customer-Segmentation-Using-RFM-and-K-Means-Clustering
    ```
2. Open `Final_Segmentation_with_Comments.ipynb` in Jupyter Notebook or JupyterLab.
3. Run each cell to execute the analysis, visualize data, and interpret clustering results.

## Project Insights and Recommendations
- **Best Customers**: High-frequency, high-spending customers; target with loyalty rewards.
- **Loyal Customers**: High-frequency buyers; engage with retention campaigns.
- **Almost Lost Customers**: Recent but low-frequency buyers; encourage purchases through incentives.
- **Lost Cheap Customers**: Low-frequency, low-spending customers; minimal resources allocated.

## License
This project is licensed under the MIT License.

---

