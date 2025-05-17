# FinalProject_2025_Baptiste_ARNOLD

The notebook (Final_report) documents the development of a personalized short-video recommender system using the KuaiRec dataset. It systematically walks through the steps of building a hybrid recommendation engine that combines collaborative filtering with content-based features.

### **Workflow**

## Dataset Loading & Exploration

The notebook begins by loading interaction data and metadata (e.g., video tags and features). It performs basic exploratory data analysis to understand distributions and identify preprocessing needs.
## Data Preprocessing

Multiple CSV files are cleaned and merged. User-item interactions are structured into a sparse matrix format suitable for model training. Categorical features are encoded, and missing values are handled.

## Modeling

One model based on content-based filtering was implemented.

## Recommendation Algorithm

A custom implementation of recommender algorithm that analyzes user's preferences then recommends similar videos.

## Evaluation
The notebook evaluates the model using metrics such as:
- Precision@K
- NDCG@K
- MRR@K
- Serendipity@K

### **Summary**
Overall, this notebook reflects a thoughtful application of content-based recommendation techniques and demonstrates the ability to process real-world scale data for personalized media recommendations.