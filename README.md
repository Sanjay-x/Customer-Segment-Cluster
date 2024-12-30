

# Customer Segmentation Analysis

## Overview

This project is about grouping customers based on their buying behavior using different clustering methods like **K-Means**, **Hierarchical Clustering**, **Gaussian Mixture Model (GMM)**, and a **Custom Clustering Method**. The aim is to sort customers into different categories like **Inactive**, **Casual**, and **Regular** based on how they interact with an online store.

## Project Structure

1. **Data Preprocessing**: This step involves cleaning and organizing the raw customer data.
2. **Feature Quantization**: Here, we turn continuous data like how often a customer buys or how much they spend into categories (like "low", "medium", or "high").
3. **Feature Encoding**: After categorizing the data, we turn these categories into numbers so they can be used in the clustering process.
4. **Clustering Techniques**:
    - **K-Means**: This method groups customers based on similarities in their behavior.
    - **Hierarchical Clustering**: It builds a tree-like structure to show how customers can be grouped.
    - **Gaussian Mixture Model (GMM)**: This approach finds groups by considering multiple overlapping clusters based on probabilities.
    - **Custom Clustering Method**: Here, we create our own customer segments based on specific rules or behaviors.
5. **Visualization**: The results of the clustering are shown using charts to make the customer segments easy to understand.

## Steps in the Code

### 1. **Data Loading and Preparation**

The first step is to load the customer data, clean it up by handling missing values, and prepare the data so it's ready to be used for grouping.

### 2. **Feature Quantization**

Next, we take continuous data like how many days it's been since a customer last bought something, how much they’ve spent in total, and how often they purchase, and group them into categories like "low", "medium", or "high". This makes it easier to group customers based on their behavior.

### 3. **Feature Encoding**

Once the data is categorized, we turn these categories into numbers (e.g., "low" might be -1, "medium" 0, and "high" 1) so that we can apply clustering methods.

### 4. **Clustering Algorithms**

We then use different clustering methods to group customers:
- **K-Means**: We divide customers into three groups based on their buying habits.
- **Hierarchical Clustering**: We build a tree-like structure to visualize how customers can be grouped together.
- **Gaussian Mixture Model (GMM)**: This method identifies overlapping groups by using probability distributions.
- **Custom Clustering Method**: We define custom customer segments based on specific rules we’ve set.

### 5. **Visualization**

Finally, we show the results of the clustering by creating pie charts that help visualize the distribution of customers in each segment. This makes it easier to understand how customers are grouped.

## Conclusion

This project helps group customers into segments using various clustering techniques. These segments allow businesses to understand their customers better and create targeted marketing strategies to improve customer engagement.
