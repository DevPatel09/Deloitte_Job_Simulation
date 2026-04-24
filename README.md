# Deloitte_Job_Simulation

## Exceutive Summary

Daikibo Industrial, a global manufacturing organization operating across four factories in Tokyo, Osaka, Berlin, and Shenzhen, provided a unified telemetry dataset generated from machine activity logs collected over one month (May 2021). Each factory operates multiple machine types that continuously generate performance data at regular intervals.

Using this dataset, the Deloitte simulation focused on transforming raw telemetry data into actionable insights to support operational efficiency and workforce equity decision-making.

## **Business Problem**

### 1. Operational Performance (Machine Breakdown)

Daikibo Industrial collected telemetry data from four global factories (Tokyo, Osaka, Berlin, Shenzhen) to improve operational reliability and production efficiency. However, leadership lacked clear visibility into machine performance across locations.

The client aimed to answer two key business questions:

- Which factory location experiences the highest frequency of machine breakdowns?
- Which machine types contribute most to breakdowns within the worst-performing location?

### 2. Workforce Equity (Gender Pay Analysis)

Daikibo Industrial received increasing internal concerns regarding potential gender-based pay inequality across multiple job roles and global locations. Although a forensic analytics team developed an algorithm to quantify the “level of gender pay equality” for each role, the output was not yet fully analyzed or translated into actionable business insights.

As a result, leadership lacked a clear understanding of where pay disparities existed across factories and job roles, limiting their ability to assess fairness, ensure compliance, and make informed HR policy decisions.

## **Methodology**

### Task 1:

- Imported unified JSON telemetry dataset (May 2021) covering 4 factories
- Created calculated field named unhealthy with a value of 10 for every unhealthy status
- Created a bar chart named “Down Time per Factory” and a new sheet with new bar chart named “Down Time per Device Type”
- Developed interactive Tableau dashboard with filter actions with the 2 previous sheets
- Identified factory with highest downtime and root machine contributions

### Task 2:

- Analyzed gender pay equality scores across job roles and factories
- Applied IF logic to classify equality level
- Converted raw scores into structures categories: Fair, Unfair, High Discriminative
- Enabled comparative analysis across job levels and locations

## **Skills Applied**

- Tableau Dashboard Development
- Data Visualization & Storytelling
- Excel (IF Functions)
- Data Transformation (JSON dataset handling)
- Analytical Problem Solving

## **Key Results**

### Operational Insights

- Identified factory with highest machine downtime across 4 global locations
- Highlighted critical machine types contributing to production inefficiencies
- Improved visibility into operational disruptions using interactive dashboards
- Enabled faster decision-making through visual analytics

### HR Equity Insights

- Classified gender pay equality across job roles using structured logic
- Identified leadership roles as highest risk for inequality

## **Business Impact**

- Converted raw telemetry data into actionable operational insights
- Improved clarity in workforce equity assessment through structured classification
- Enabled leadership to identify high-risk operational and HR areas
- Strengthened data-driven decision-making across operations and HR functions

## **Key Findings**

- Certain factories showed significantly higher downtime, indicating operational inefficiencies
- Leadership-level roles showed stronger patterns of pay inequality compared to technical roles
- Data visualization significantly improved interpretability of complex datasets

## **Business Recommendations**

### **Operations**

- Implement predictive maintenance systems to reduce machine failures
- Standardize monitoring dashboards across all factories
- Focus maintenance efforts on high-failure machine categories

### **HR / Workforce**

- Conduct formal pay equity audits across all job roles
- Introduce standardized compensation frameworks globally
- Continuously monitor gender pay equality using analytics tools

## **Next Steps (Outside Scope)**

- Integrate real-time IoT telemetry for live factory monitoring
- Build predictive models for machine failure detection
- Automate dashboards using scheduled data pipelines
- Expand HR analytics to include promotion and hiring bias analysis
- Combine operational + HR datasets for enterprise-wide intelligence system
