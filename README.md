# 🚀 Market Segmentation Example: Satisfaction & Loyalty

This repository demonstrates **customer segmentation** using **K-Means clustering**, based on two key metrics: **Satisfaction** and **Loyalty**. The goal is to identify customer segments for targeted marketing campaigns.

---

## 📊 Dataset

The dataset `3.12.+Example.csv` contains two columns:  
- **Satisfaction** – numerical rating of customer satisfaction.  
- **Loyalty** – numerical rating of customer loyalty.  

---

## 🛠 Approach

1. **Visualization**  
   Plotting the distribution of customers on the Satisfaction vs Loyalty plane.

2. **K-Means Clustering**  
   Applying K-Means to group customers into segments. Tested **2, 3, and 4 clusters**.

3. **Scaling**  
   Standardizing data so that both metrics contribute equally to distance calculations.

4. **WCSS (Within-Cluster Sum of Squares)**  
   Calculate WCSS for different numbers of clusters to find the optimal cluster count using the **Elbow Method**.

---

## 🔍 Identified Segments

### **2 Clusters**
- **High Satisfaction & High Loyalty** – happy and loyal customers, potential brand advocates.  
- **Low Satisfaction & Low Loyalty** – disengaged customers, focus on retention.

### **3 Clusters**
- **High Satisfaction & High Loyalty** – same as above.  
- **Medium Satisfaction & Medium Loyalty** – customers to motivate for increased loyalty.  
- **Low Satisfaction & Low Loyalty** – same as above.

### **4 Clusters**
- **High Satisfaction & High Loyalty** – loyal & happy customers.  
- **High Satisfaction & Low Loyalty** – satisfied but not fully loyal; opportunity to increase engagement.  
- **Low Satisfaction & High Loyalty** – loyal but dissatisfied; priority segment for intervention.  
- **Low Satisfaction & Low Loyalty** – high-risk customers for churn.

## 💡 Customer Insights

The script will generate scatter plots showing customer segments for 2, 3, and 4 clusters.

**Using Satisfaction and Loyalty to Identify Actionable Segments:**

- ⭐ **Reward happy and loyal customers**  
  Keep your most satisfied and loyal customers engaged and appreciated.

- 🔧 **Improve satisfaction for loyal but unhappy customers**  
  Identify pain points and enhance their experience to maintain loyalty.

- 🚀 **Motivate moderately satisfied customers to boost loyalty**  
  Offer incentives or personalized communication to turn them into loyal advocates.

- 🔄 **Focus on retention or re-engagement for unhappy, disloyal customers**  
  Target these customers with campaigns to win them back or prevent churn.


---

## ⚡ Usage

1. Clone the repository:
   ```bash
   git clone <repo-url>
2. Install dependencies:
    ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3.Run the script:
  ```bash
  python market_segmentation.py
