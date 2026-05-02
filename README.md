# 📊 Website Traffic Analysis (Python EDA)

## 📌 Project Overview
This project focuses on analyzing website traffic and user engagement data using Python. The goal is to uncover user behavior patterns, identify high-performing marketing channels, and provide actionable insights to improve overall website performance.

## 🎯 Objectives
*   **Analyze** traffic trends across different hours of the day
*   **Evaluate** performance of acquisition channels
*   **Measure** user engagement metrics
*   **Identify** high-performing and underutilized channels
*   **Provide** data-driven recommendations

---

## 🛠️ Tech Stack
*   **Python**
*   **Pandas** – Data manipulation
*   **NumPy** – Numerical operations
*   **Matplotlib & Seaborn** – Data visualization

## 📂 Dataset
The dataset contains website analytics data with the following features:
*   Channel Group
*   Date & Time
*   Users
*   Sessions
*   Engaged Sessions
*   Engagement Rate
*   Average Engagement Time
*   Events per Session
*   Event Count

---

## ⚙️ Data Processing
*   Renamed columns for better readability
*   Converted datetime column to proper format
*   Handled missing and incorrect data types
*   Extracted hour for time-based analysis

## 📈 Key KPIs
*   **Total Users**
*   **Total Sessions**
*   **Average Engagement Rate**

---

## 📊 Analysis & Visualizations
*   Hourly traffic trends (Users & Sessions)
*   Channel-wise user distribution
*   Engagement time by channel
*   Sessions vs Engagement relationship
*   Engagement rate by channel
*   Sessions distribution (boxplot)
*   Dual-axis analysis (Sessions vs Engagement by hour)

---

## 🔍 Key Insights

### ⏰ Time-Based Insights
*   **Peak traffic** occurs between **11 AM – 12 PM**.
*   **Highest sessions** observed between **7 PM – 10 PM** (post-work browsing).
*   **Lowest activity** between 2 AM – 7 AM, but engagement is higher during this period.
*   **Peak engagement** time is **11 AM – 1 PM**.

### 📢 Channel Performance Insights
*   **Organic Social** drives the highest traffic.
*   **Direct** and **Organic Search** are also strong contributors.
*   **Organic Video** has the highest engagement rate.
*   **Referral** and **Organic Social** also perform well in engagement.

### ⚖️ Traffic vs Engagement Insight
*   High traffic does not always mean high engagement.
*   **Example:**
    *   *Organic Social* → High traffic but lower engagement.
    *   *Organic Video & Email* → Lower traffic but higher engagement.

### 🚀 Opportunity Insights
*   **Email** and **Organic Video** are underutilized channels.
*   These channels have high engagement but low traffic, indicating strong growth potential.

---

## 💡 Recommendations
1.  **Increase investment** in Organic Video and Email marketing.
2.  **Optimize Organic Social** to improve engagement quality.
3.  **Schedule content** around peak hours (11 AM – 1 PM & 7 PM – 10 PM).
4.  **Target late-night users** with high-quality content (high engagement segment).

---

## 📁 Project Structure
```text
website-traffic-analysis/
│
├── data/
│   └── website.csv
│
├── notebooks/
│   └── website_analysis.ipynb
│
├── images/
│   ├── line_chart.png
│   └── sess_vs_enga.png
│
└── README.md
```

## 📸 Sample Visualizations


---

## 🚀 How to Run

1.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

2.  **Launch the Notebook:**
    ```bash
    jupyter notebook Website_Analysis.ipynb
    ```

---

## 📌 Conclusion
This analysis highlights how user behavior varies by time and channel. By focusing on high-engagement channels and optimizing traffic sources, businesses can significantly improve conversion and user retention.
```
