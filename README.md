# 🎧 Call Centre Performance Analysis | Power BI

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power_Query-51A0D5?style=for-the-badge&logo=powerquery&logoColor=white) ![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

An interactive Power BI dashboard developed to analyze call-centre performance across call volume, resolution, abandonment, response time, handling time, customer satisfaction, and individual agent performance.

![Call Centre Dashboard Overview](screenshot/Screenshot%202026-08-11%20215420.png)

---

## 🎯 Business Objective

The objective of this project was to transform call-centre interaction data into an interactive management dashboard that helps identify:

*   **Overall call volume and service performance**
*   **Call resolution and abandonment patterns**
*   **Customer satisfaction levels**
*   **Response and handling-time trends**
*   **Agent-level performance**
*   **Time-based call volume patterns**

## 📊 Dataset

The dataset contains **5,000 call records** across **10 fields**, including:

*   Call ID
*   Agent
*   Date and time
*   Call topic
*   Answered status
*   Resolution status
*   Speed of answer
*   Average talk duration
*   Customer satisfaction rating

## 🛠️ Tools Used

*   **Microsoft Power BI:** Primary analytics and visualization platform.
*   **Power Query:** Data cleaning and transformation.
*   **DAX (Data Analysis Expressions):** Custom measure calculations.
*   **Data Visualization & Interactive Filters:** Slicers for dynamic reporting.

## 📈 Dashboard

The dashboard provides an overview of call-centre performance through KPI cards, agent-level analysis, satisfaction analysis, and time-based trends.

### Key KPIs
*   **Total Calls:** 5,000[cite: 1]
*   **Call Resolved:** 89.94%[cite: 1]
*   **Call Abandoned:** 18.92%[cite: 1]
*   **CSAT:** 68.07%[cite: 1]
*   **Average Speed of Answer:** 67.52 seconds[cite: 1]
*   **Average Call Handling Time:** 224.92 seconds for answered calls[cite: 1]

### Interactive Analysis
Users can filter the dashboard by:
*   Agent
*   Call topic
*   Month
*   Week Day

The dashboard also includes agent-level comparisons across call volume, abandonment, response speed, resolution rate, and customer satisfaction[cite: 1].

## 💡 Key Findings

### Service Performance
The dashboard shows an overall resolution rate of **89.94%**[cite: 1], while **18.92% of calls were abandoned**[cite: 1].

### Customer Satisfaction
The average customer satisfaction score was **68.07%**[cite: 1], indicating an opportunity to investigate the drivers of lower satisfaction.

### Response & Handling Time
*   The average speed of answer was approximately **67.52 seconds**[cite: 1].
*   For answered calls, the average handling time was approximately **224.92 seconds**[cite: 1].

### Agent Performance
Agent-level reporting enables the comparison of:
*   Total calls handled
*   Call abandonment
*   Speed of answer
*   Resolution rate
*   Customer satisfaction

This allows potential performance differences to be identified for further investigation.

### Call Volume Patterns
Call volume was analyzed across both hours of the day and weekdays to identify periods of higher and lower demand.

## 📂 Project Structure

```text
call-centre-performance-analysis-powerbi/
│
├── README.md
├── data/
│   └── call-center-dataset.csv
├── powerbi/
│   └── Call_Centre_Performance_Dashboard.pbix
└── screenshots/
    └── Screenshot 2026-08-11 215420.png
