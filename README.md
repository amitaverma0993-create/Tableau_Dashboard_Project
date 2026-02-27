# Tableau Dashboard_Daikibo Factory Telemetry Analysis

## **Project Overview**

This project was completed as part of a **Deloitte - Data Analytics Job Simulation**, where I analyzed machine telemetry data from multiple manufacturing factories using **Tableau**.

## **Objective**

The objective was to transform raw operational data into **actionable business insights** by building interactive **dashboards**.

## **Business Problem (KPI'S)** 

Daikibo collected telemetry data from machines across four global factories to understand operational efficiency and machine failures.
The client wanted answers to:

**1. Which factory experienced the highest machine downtime?**

**2. Which machine types failed most frequently in that factory?**

**Factory Locations:**

1. Daikibo Factory **Meiyo** – Tokyo, Japan
2. Daikibo Factory **Seiko** – Osaka, Japan
3. Daikibo **Berlin** – Germany
4. Daikibo **Shenzhen** – China
Each factory operates **9 machine types**, sending status messages every **10 minutes**.

## **Dataset Information**

1. Format: JSON file
2. Data Type: Machine telemetry logs
3. Frequency: Every 10 minutes
4. Data Source: Client telemetry system

## **Tools & Technologies**

1. Tableau Desktop Public Edition
2. Data Visualization
3. Data Cleaning & Transformation
4. Calculated Fields
5. Interactive Dashboard Design

## **Project Workflow**

### **1. Data Preparation**

1. Imported JSON telemetry dataset into Tableau
2. Reviewed machine status fields
3. Cleaned and structured raw data

### **2. Calculated Field Creation**

1. Created a calculated measure for Unhealthy Field
2. Represents 10 minutes of downtime per unhealthy signal

### **3. Visualization Development**

#### **Down Time per Factory**

1. Bar chart showing total downtime by factory
2. Helps identify worst-performing location

#### **Down Time per Device Type**

1. Bar chart showing downtime by machine type
2. Identifies failure-prone machines

### **4. Dashboard Creation**

Built an interactive dashboard including:
1. Factory downtime visualization
2. Device-type downtime visualization
3. Cross-filter functionality 

#### Selecting a factory dynamically filters machine performance.

## **Dashboard Features**

1. Interactive filtering
2. Business-focused visualization
3. Operational performance tracking
4. Decision-support analytics

## **Key Insights**

1. Identified the factory with the maximum downtime
2. Highlighted machines contributing most to operational failure
3. Enabled management to prioritize maintenance decisions

## **Learning Outcomes**

1. Converted raw machine data into insights
2. Built interactive dashboards using Tableau
3. Applied real-world analytics workflow
4. Understood manufacturing performance monitoring

## **Skills Demonstrated**

1. Data Analysis
2. Tableau Dashboard Development
3. Business Intelligence Reporting
4. Data Visualization
5. Analytical Thinking
6. Problem Solving
7. KPI Monitoring
   
## **Future Improvements**

1. Add predictive maintenance analytics
2. Integrate real-time telemetry streaming
3. Build automated reporting dashboards







