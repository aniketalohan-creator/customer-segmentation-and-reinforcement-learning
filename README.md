# Customer Segmentation & Reinforcement Learning

An applied Machine Learning project demonstrating **customer segmentation using K-Means clustering** and the fundamentals of **Reinforcement Learning** through a delivery-route optimization scenario.

## Overview

This project explores two Machine Learning approaches through practical business use cases:

* **Unsupervised Learning:** Customer segmentation using K-Means clustering
* **Reinforcement Learning:** Action-reward based decision-making for delivery route selection

The objective is to understand how Machine Learning techniques can support **business analysis, customer targeting, and operational decision-making**.

## Project Objectives

* Segment customers based on spending and engagement behaviour.
* Identify meaningful customer groups using K-Means clustering.
* Interpret clusters from a business perspective.
* Understand the fundamental components of Reinforcement Learning.
* Demonstrate the concepts of agents, actions, rewards, exploration, and exploitation.
* Connect Machine Learning techniques with practical business applications.

## Project Structure

```text
customer-segmentation-and-reinforcement-learning/
│
├── part-a/
│   └── unsupervised-learning/
│       ├── Unsupervised_and_Reinforcement_Learning_Practical_Name.ipynb
│       └── customer-segmentation.png
│
└── README.md
```

## Part A — Customer Segmentation

### Business Problem

An online retailer wants to identify different types of customers using two behavioural indicators:

* Monthly Spending
* App Visits

K-Means clustering is used to divide customers into **three groups**.

### Methodology

1. Create the customer dataset.
2. Select Monthly Spending and App Visits as clustering features.
3. Apply K-Means with `K = 3`.
4. Assign each customer to a cluster.
5. Visualize the resulting customer segments.
6. Interpret the clusters from a business perspective.

### Business Applications

The resulting segments can support targeted marketing strategies such as:

* Loyalty programs for high-value customers
* Personalized recommendations
* Re-engagement campaigns for lower-engagement customers

> **Note:** Cluster numbers are model-generated labels and do not inherently represent customer value. Business interpretation should be based on the underlying customer behaviour.

## Part B — Reinforcement Learning

### Business Problem

A delivery company has two possible routes and wants to understand how a system can learn to prefer routes that historically provide better delivery performance.

The project uses a simplified reward-based scenario:

* **Agent:** Delivery decision system
* **Environment:** Roads and traffic
* **Action:** Select Route A or Route B
* **Reward:** Feedback based on delivery performance

### Exploration vs Exploitation

The project demonstrates the two fundamental decision-making concepts:

**Exploration**
Trying a less-used or new option to gather additional information.

**Exploitation**
Selecting the option that is already known to provide better results.

The practical also demonstrates both concepts programmatically using route selection and average rewards.

## Technologies

* **Python**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**
* **Google Colab**
* **Jupyter Notebook**

## Key Concepts

| Concept               | Application                    |
| --------------------- | ------------------------------ |
| K-Means Clustering    | Customer segmentation          |
| Unsupervised Learning | Discovering customer patterns  |
| Agent                 | Delivery decision system       |
| Action                | Route selection                |
| Reward                | Delivery performance feedback  |
| Exploration           | Trying different routes        |
| Exploitation          | Selecting the best-known route |

## Machine Learning Context

| ML Type                | Core Idea                         | Business Application      |
| ---------------------- | --------------------------------- | ------------------------- |
| Supervised Learning    | Learn from known answers          | Customer churn prediction |
| Unsupervised Learning  | Discover hidden patterns          | Customer segmentation     |
| Reinforcement Learning | Learn through actions and rewards | Route optimization        |

## Key Takeaways

This project demonstrates how Machine Learning can move beyond model implementation into **business-oriented decision-making**.

The customer segmentation component shows how behavioural data can be transformed into actionable customer groups, while the Reinforcement Learning component introduces how systems can use feedback to improve decisions.

## Repository Contents

The main notebook contains the complete practical implementation, including:

* Dataset creation
* Feature selection
* K-Means clustering
* Cluster visualization
* Business interpretation
* Route reward analysis
* Exploration example
* Exploitation example
* Machine Learning comparison

## Author

**Aniketa Lohan**

BBA FinTech Student

---

*This project was developed as a practical exploration of Machine Learning concepts and their applications in business decision-making.*
