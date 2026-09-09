---
layout: default
title: Portfolio
permalink: /portfolioDS/
---
### [About me (EN)](/) | [Обо мне (RU)](/about_ru/)
### [Portfolio DA (EN)](/portfolioDA/) | [Портфолио DA (RU)](/portfolioDA_ru/)
### Portfolio DS/ML/DL (EN) | [Портфолио DS/ML/DL (RU)](/portfolioDS_ru/)

---

## Cases:

### [**Predicting the value of real estate**](https://github.com/mishandri/Data-Science/tree/main/%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%BD%D0%B5%D0%B4%D0%B2%D0%B8%D0%B6%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8)
- **Problem:** Real estate aggregators need to automatically determine the market value of properties based on their characteristics for relevant pricing and optimal sales strategy selection.
- **Solution:** Developed a machine learning model based on Lasso regression with 3rd-degree polynomial features. Implemented a preprocessing pipeline: missing value imputation, IQR-based outlier capping, categorical feature encoding, date transformation, and scaling. The model was trained on 18,349 properties. Achieved R² = 0.6863 (exceeding the 0.6 threshold). The model successfully captures non-linear relationships while avoiding overfitting through L1 regularization. Generated predictions for 3,087 test properties, ready for submission.

---

### [**Predicting transport company delays**](https://github.com/mishandri/Data-Science/tree/main/%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%B4%D0%B5%D1%80%D0%B6%D0%B5%D0%BA%20%D1%82%D1%80%D0%B0%D0%BD%D1%81%D0%BF%D0%BE%D1%80%D1%82%D0%BD%D0%BE%D0%B9%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8)
- **Problem:** A transportation company needs to predict whether an order will be delivered late to proactively identify problematic shipments, improve customer service, and reduce costs.
- **Solution:** Developed a classification model based on Random Forest with class balancing. Performed feature engineering: frequency encoding for high-cardinality categorical features, created derived features (order processing time, seasonality, product density, price-to-shipping ratio), and one-hot encoding for payment methods. The model was trained on historical data of delivered orders. Achieved F1-score = 0.3255 (exceeding the 0.3 threshold). The model enables early identification of at-risk orders, allowing the company to take preventive measures. Generated predictions for 8,558 test orders.

---

###  [**Targeted Marketing: Predicting Campaign Responses**](https://github.com/mishandri/Data-Science/tree/main/%D0%A2%D0%B0%D1%80%D0%B3%D0%B5%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D1%8B%D0%B9%20%D0%BC%D0%B0%D1%80%D0%BA%D0%B5%D1%82%D0%B8%D0%BD%D0%B3)
- **Problem:** A business needs to predict whether a customer will respond to promotional offers to optimize marketing budgets and increase profits by targeting only promising customers.
- **Solution:** Developed a classification model based on Gaussian Naive Bayes. Performed preprocessing: ordinal encoding of categorical features (education level, marital status), median imputation for missing income values, and MinMaxScaler normalization for numerical features. The target variable was defined as a response to at least one of 6 campaigns. The model enables prediction of customer response probability, allowing the business to target offers only to the relevant audience. Generated predictions for 448 test clients.

---

### [**Forecasting restaurant profitability**](https://github.com/mishandri/Data-Science/tree/main/%D0%A0%D0%B5%D0%BD%D1%82%D0%B0%D0%B1%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D1%8C%20%D1%80%D0%B5%D1%81%D1%82%D0%BE%D1%80%D0%B0%D0%BD%D0%B0)
- **Problem:** A restaurant needs to classify menu items by profitability level (Low/Medium/High) to analyze the menu, adjust prices and ingredient composition to improve business efficiency.
- **Solution:** Developed a multi-class classification model based on OneVsRestClassifier with Logistic Regression. Performed feature engineering: one-hot encoding for categorical features (RestaurantID, MenuCategory, MenuItem) and binary encoding for ingredients (each ingredient as a separate feature). The target variable was encoded as numeric labels. Achieved Accuracy = 0.8154 (exceeding the 0.75 threshold). The model enables automated menu analysis and data-driven business decisions based on dish composition and category. Generated predictions for 195 test dishes.

---

### [**Customer Segmentation Model Development**](https://github.com/mishandri/Data-Science/tree/main/%D0%A0%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D0%BC%D0%BE%D0%B5%D0%B4%D0%BB%D0%B8%20%D0%BA%D0%BB%D0%B0%D1%81%D1%82%D0%B5%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8%20%D0%B1%D0%B0%D0%B7%D1%8B%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2)
- **Problem:** A fast-food restaurant needs to segment customers based on their brand perception, demographic, and behavioral characteristics to develop targeted marketing strategies.
- **Solution:** Developed a clustering model based on KMeans with centroid initialization using exemplar customers. Performed preprocessing: categorical feature encoding and StandardScaler scaling for numerical features. The optimal number of clusters (k=4) was determined using the elbow method. Visualized clusters using PCA. Achieved Accuracy = 0.8018 (exceeding the 0.8 threshold). The model enables assigning each customer a segment based on archetypes, allowing the restaurant to define personalized marketing strategies. Generated a segmentation file for 1,453 customers.

---

### [**Credit Card Customer Analysis Using Clustering Methods**](https://github.com/mishandri/Data-Science/tree/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D0%BA%D1%80%D0%B5%D0%B4%D0%B8%D1%82%D0%BD%D1%8B%D1%85%20%D0%BA%D0%B0%D1%80%D1%82%20%D1%81%20%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%D0%BC%20%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%BE%D0%B2%20%D0%BA%D0%BB%D0%B0%D1%81%D1%82%D0%B5%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8)
- **Problem:** A bank needs to segment customers based on their credit card usage behavior (transactions, balances, payments) to adapt business strategies and personalize services.
- **Solution:** Performed cluster analysis of the customer base (8,950 customers, 17 features) using the DBSCAN algorithm. Conducted data preprocessing: missing value imputation and feature standardization. Performed hyperparameter tuning (eps=0.9, min_samples=12) with quality assessment using Silhouette Score and Calinski-Harabasz Index. Visualized clusters using PCA. Identified 4 meaningful clusters and detected anomalies (~49% noise). Silhouette Score = 0.391 (good separability), Calinski-Harabasz Index = 80.91 (excellent separation). The model enables the bank to understand customer structure and adapt marketing strategies for each segment.

---

### [**Recommendation system for an online store**](https://github.com/mishandri/Data-Science/tree/main/%D0%A0%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0%20%D0%B4%D0%BB%D1%8F%20%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0)
- **Problem:** An online store needs to personalize product rankings for each user to increase CTR, conversion, and customer retention.
- **Solution:** Developed a ranking model based on XGBoost LambdaMART optimized for NDCG@5. Performed preprocessing: merging user, item, and interaction data, categorical feature encoding, numerical scaling, and grouping by user_id. The model was trained on 30,000+ interactions (720 users) and validated on 20% of users. Achieved NDCG@5 = 0.9464 (exceeding the 0.9 threshold). The model enables personalized recommendations, automating the product ranking process. Generated predictions for 3,993 test interactions.

---

### [**Association Rule-Based Product Recommendation Development**](https://github.com/mishandri/Data-Science/tree/main/%D0%A0%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D1%82%D0%BE%D0%B2%D0%B0%D1%80%D0%BD%D1%8B%D1%85%20%D1%80%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%86%D0%B8%D0%B9%20%D0%BD%D0%B0%20%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5%20%D0%B0%D1%81%D1%81%D0%BE%D1%86%D0%B8%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D1%85%20%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D0%BB)
- **Problem:** An online store needs to offer customers additional products based on purchase history to increase average order value and basket depth.
- **Solution:** Developed a product recommendation system based on the Apriori algorithm. Analyzed 97,152 transactions: identified frequent itemsets (min_support = 0.05) and generated association rules (min_confidence = 0.5). For each test item, the rule with the highest confidence is selected to recommend a complementary product. Achieved Accuracy = 0.909 (10 out of 11 recommendations correct). The system enables automatic generation of complementary product recommendations, increasing cross-sales and improving user experience. Generated recommendations for 11 test items.

---

### [**Image-Based Product Retrieval using Convolutional Neural Networks (CNN)**](https://github.com/mishandri/Data-Science/tree/main/%D0%A0%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0%20%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%20%D0%B4%D0%BB%D1%8F%20%D0%BF%D0%BE%D0%B8%D1%81%D0%BA%D0%B0%20%D1%82%D0%BE%D0%B2%D0%B0%D1%80%D0%BE%D0%B2%20%D0%BF%D0%BE%20%D0%B8%D1%85%20%D0%B2%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%BC%D1%83%20%D1%81%D1%85%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D1%83%20(CNN))
- **Problem:** An online clothing store needs to find visually similar products in the catalog to recommend to customers, increasing purchase probability and customer loyalty.
- **Solution:** Developed a visual search system based on a pre-trained VGG16 convolutional neural network (feature extractor). Extracted feature vectors for all catalog images, computed cosine similarity between each query vector and the database, excluded images with the same ID, and selected the most similar product. Implemented image preprocessing (augmentation, normalization). Achieved Accuracy = 0.72 (exceeding the 0.7 threshold). The model enables finding visually similar products, improving recommendation relevance and user experience. Generated predictions for 50 query images.

---

*Last updated: 2026-09-09*