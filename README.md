# Custmer-segmentaion-using-KMeans
It is a custmer segmentation end to end project that predict the custemor category 
#  Customer Segmentation using K-Means (Unsupervised Machine Learning)

This project demonstrates an **end-to-end customer segmentation system** using the **K-Means clustering algorithm**, an unsupervised machine learning technique. The goal is to group customers into meaningful segments based on their **Age**, **Annual Income**, and **Spending Score**.

The project also allows **real-time user input** to predict which customer segment a new customer belongs to.

---

##  Project Overview

Customer segmentation helps businesses:

* Identify **premium customers**
* Detect **low-priority customers**
* Target **potential customers** effectively

In this project, we:

* Created a custom customer dataset
* Scaled features using **StandardScaler**
* Applied **K-Means clustering**
* Predicted clusters for new customers
* Visualized clusters using **Matplotlib**

---

##  Technologies Used

* **Python 3**
* **Pandas** – data handling
* **NumPy** – numerical operations
* **Scikit-learn** – K-Means, StandardScaler
* **Matplotlib** – data visualization

---

##  Project Structure

```
customer-segmentation/
│
├── customer_segmentation.py   # Main Python script
├── README.md                  # Project documentation
```

---

##  Dataset Description

The dataset consists of the following features:

| Feature Name   | Description                |
| -------------- | -------------------------- |
| Age            | Customer age               |
| Annual_Income  | Income in thousands        |
| Spending_Score | Customer spending behavior |

---

##  How the Project Works

1. Load and prepare the dataset
2. Select important features
3. Scale the data using `StandardScaler`
4. Train a **K-Means clustering model**
5. Assign cluster labels to customers
6. Accept new customer input
7. Predict the customer segment
8. Visualize customer clusters

---

##  Customer Segments

Each cluster is mapped to a business-friendly label:

* **Premium Customer**
* **Low Priority Customer**
* **Potential Customer**

---

##  How to Run the Project

### 1️ Install Required Libraries

```bash
pip install pandas numpy matplotlib scikit-learn
```

### 2️ Run the Script

```bash
python customer_segmentation.py
```

### 3️ Enter Customer Details

```text
Enter Age: 30
Enter Annual Income: 40
Enter Spending Score: 70
```

### 4️ Output Example

```text
Customer Segment: Premium Customer
```

---

##  Visualization

The project generates a scatter plot showing:

* Annual Income vs Spending Score
* Color-coded customer clusters

This helps visually understand how customers are grouped.

---

##  Machine Learning Concepts Used

* Unsupervised Learning
* K-Means Clustering
* Feature Scaling
* Cluster Prediction
* Data Visualization

---

##  Future Enhancements that i want to do 

* Automatic K selection using **Elbow Method**
* PCA-based 2D/3D visualization
* Streamlit web application
* Real-world dataset integration

---

##  Myself...

**Vikas Thakur**
Aspiring Machine Learning Engineer

📌 *This project is part of my hands-on learning journey in Machine Learning.*

---

⭐ If you like this project, consider giving it a **star** on GitHub!
