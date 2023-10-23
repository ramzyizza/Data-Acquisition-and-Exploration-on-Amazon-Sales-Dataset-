# Data Acquisition and Exploration on Amazon Sales Dataset

A comprehensive analysis focusing on data acquisition, exploration, and preliminary insights derived from the Amazon Sales Dataset.

## Table of Contents

-   [Dataset Overview](#dataset-overview)
-  [Task](#task)
-   [Dataset Features](#dataset-features)
-   [Visualization Highlights](#visualization-highlights)
-   [Dataset Quality Assessment](#dataset-quality-assessment)
-   [Potential Machine Learning Implementations](#potential-machine-learning-implementations)

## Dataset Overview

-   **Dataset Source**: [Amazon Sales Dataset on Kaggle](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)
    
-   **Description**:
    
    -   The dataset covers 1465 entries with 16 distinct attributes, detailing authentic Amazon Product Ratings and Reviews.
    -   The data has been extracted from Amazon's official website, containing 1351 unique values and 1194 unique user IDs.
    -   It serves as a strong tool for business analytics, especially for retail and e-commerce domains.
    -   The primary focus of this project is on data acquisition, exploration, and foundational analysis.

## Task

Amazon, a leading multinational e-commerce company, offers a various of products and services globally. This dataset captures product information and real customer reviews, enabling researchers and analysts to reveal market trends, consumer behavior, and sales insights.

## Dataset Features

-   **product_id**: Unique identifier for each product.
-   **product_name**: Descriptive name of the product.
-   **category**: Classification category of the product.
-   **discounted_price**: Offered price after discounts.
-   **actual_price**: Original price of the product without discounts.
-   **discount_percentage**: Discount rate applied to the product.
-   **rating**: Average rating given to the product.
-   **rating_count**: Number of individual ratings the product received.
-   **about_product**: Brief description of the product.
-   **user_id**: Unique identifier for each user.
-   **user_name**: Name of the user who provided the review.
-   **review_id**: Unique identifier for each review.
-   **review_title**: Short summary of the review.
-   **review_content**: Detailed review content.
-   **img_link**: Link directing to the product's image.
-   **product_link**: Direct link to the official product page.

## Visualization Highlights

1.  **Distribution of Top 10 Product Categories Sales**:
    
    -   A pie chart representation revealing the significant sales of computer and electronic products, capturing 36.2% and 11.9% of sales, respectively.
    -   The dataset identifies 211 distinct categories, offering insights into the highest and lowest contributors in sales.
    -   Amazon appears as a prime marketplace for customers seeking electronic accessories.
    
		 <img src="https://github.com/ramzyizza/Data-Acquisition-and-Exploration-on-Amazon-Sales-Dataset-/assets/89899122/0d91e517-1eb5-49cc-ad1a-e369c400ba30" width="90%"></img>
 
2.  **Average Product Rating of 50 Categories**:
    
    -   The bar chart suggests the Computer & Accessories category as the frontrunner with an average rating of approximately 4.6/5.0.
    -   The graph subtly indicates the popularity and demand for computer and electronic accessories.
 
		 <img src="https://github.com/ramzyizza/Data-Acquisition-and-Exploration-on-Amazon-Sales-Dataset-/assets/89899122/ad41c277-be0f-4c73-95b0-7982566e1220" width="90%"></img>
   
3.  **Top 10 Best-Selling Products With The Highest Rating Counts**:
    
    -   AmazonBasics Flexible Premium HDMI cable is recognized as the top-rated product with over 800,000 ratings globally.
    -   A recurring trend is observed with computer and electronic accessories reigning in popularity and demand.
    <img src="https://github.com/ramzyizza/Data-Acquisition-and-Exploration-on-Amazon-Sales-Dataset-/assets/89899122/dd1a7007-2631-466d-b3d8-d0ed8c2e3670" width="90%"></img> 

## Dataset Quality Assessment

-   **Data Validity**:
    
    -   The dataset is authenticated and ratified by Kaggle.
    -   Each record references the official product page and corresponding image, underscoring the dataset's authenticity.
-   **Data Accessibility**:
    
    -   Accessible to all under the CC BY-NC-SA 4.0 license.
    -   The dataset is well-structured, facilitating smooth data manipulations and visualizations.
-   **Data Completeness**:
    
    -   While the dataset is comprehensive, minor missing values in the ratings column were addressed during the exploration phase.
-   **Data Consistency**:
    
    -   Some discrepancies in data formatting and structure were noted, yet the dataset predominantly maintains consistency.
-   **Data Size**:
    
    -   The dataset, with its 1465 entries, is relatively concise, but it provides substantial data for preliminary analysis.

## Potential Machine Learning Implementations

1.  **Price Optimization**:
    
    -   A predictive model to refine pricing strategies based on market dynamics and consumer feedback.
2.  **Product Recommendation**:
    
    -   A machine learning-driven recommendation system suggesting products aligned with a user's purchase history and reviews.
3.  **Sentiment Analysis**:
    
    -   A model to sift through product reviews and categorize them as positive, negative, or neutral, offering insights into customer satisfaction and product areas requiring enhancement.

> **Note**: The dataset, though insightful, presents certain limitations like sample size, geographical bias, and data recency. These factors should be considered when extrapolating results or venturing into extensive machine learning applications.
