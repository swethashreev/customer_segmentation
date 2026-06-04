# Customer Segmentation Project

## Overview
Segmented 500 customers into 4 behavioral groups using K-means clustering in Python.

## Tools Used
- Python 3.12
- pandas — data loading and cleaning
- scikit-learn — KMeans clustering, StandardScaler, PCA
- matplotlib & seaborn — visualizations
- Jupyter Notebook

## Steps Followed
1. Generated a dataset of 500 customers with age, income, purchase behavior
2. Explored and cleaned the data
3. Scaled features using StandardScaler
4. Used elbow method to find optimal k=4
5. Applied K-means clustering
6. Visualized segments using PCA scatter plot
7. Exported results to CSV

## Customer Segments Found
| Segment | Age | Income | Frequency | Behavior |
|---|---|---|---|---|
| Active seniors | 55 | $71k | High | Recent buyers |
| At-risk big spenders | 53 | $70k | Low | Not buying recently |
| Frequent mid-spenders | 38 | $67k | Highest | Most active |
| Young occasional buyers | 30 | $64k | Low | Infrequent buyers |

## Files
- `customer_segmentation.ipynb` — main code notebook
- `segmented_customers.csv` — output with segment labels

## Key Results
- Silhouette score: 0.160
- 4 distinct customer segments identified
- Results exported to CSV for business use
