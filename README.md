# Customer Segmentation using Machine Learning

This project applies unsupervised machine learning to segment customers based on their purchasing behavior. Using the K-Means clustering algorithm, it groups customers into distinct categories such as high-value shoppers, average buyers, and low spenders.

The goal is to help businesses:
- Understand different customer types
- Personalize marketing strategies
- Improve customer engagement and sales

By analyzing features like income and spending score, the model reveals patterns that support data-driven decision-making.
## How It Works

1.   **Data Collection**
   - The dataset contains information like Customer ID, Age, Gender, Annual Income, and Spending Score.

2. **Data Preprocessing**  
   - Unnecessary columns (like Customer ID) are removed.
   - Relevant features (e.g., Income and Spending Score) are selected.
   - Data is scaled if needed for better clustering performance.

3. **Choosing the Right Number of Clusters**  
   - The **Elbow Method** is used to find the optimal number of customer groups (clusters).

4. **Clustering**  
   - The **K-Means algorithm** is applied to group customers based on similarities in spending behavior and income level.

5. **Visualization**  
   - The clusters are visualized using scatter plots to show how customers are grouped.

6. **Insights**  
   - Each cluster represents a different customer type (e.g., high spenders, budget-conscious shoppers), helping businesses tailor their strategies.
