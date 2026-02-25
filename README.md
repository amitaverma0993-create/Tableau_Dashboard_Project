# Tableau Dashboard_Daikibo Factory Telemetry Analysis

##**Project Overview**

This project was completed as part of a **Deloitte - Data Analytics Job Simulation**, where I analyzed machine telemetry data from multiple manufacturing factories using **Tableau**.

##**Objective**

The objective was to transform raw operational data into **actionable business insights** by building interactive **dashboards**.

##**Business Problem**

Daikibo collected telemetry data from machines across four global factories to understand operational efficiency and machine failures.
The client wanted answers to:

**1. Which factory experienced the highest machine downtime?**
**2. Which machine types failed most frequently in that factory?**

**Factory Locations:**

1. Daikibo Factory **Meiyo** – Tokyo, Japan
2. Daikibo Factory **Seiko** – Osaka, Japan
3. Daikibo **Berlin** – Germany\n
4. Daikibo **Shenzhen** – China\n

Each factory operates **9 machine types**, sending status messages every **10 minutes**.

##**Dataset Information**

1. Format: JSON file\n
2. Data Type: Machine telemetry logs\n
3. Frequency: Every 10 minutes\n
4. Data Source: Client telemetry system\n

##**Tools & Technologies**

1. Tableau Desktop Public Edition\n
2. Data Visualization\n
3. Data Cleaning & Transformation\n
4. Calculated Fields\n
5. Interactive Dashboard Design\n

##**Project Workflow**

###**1. Data Preparation**
1. Imported JSON telemetry dataset into Tableau\n
2. Reviewed machine status fields\n
3. Cleaned and structured raw data\n

###**2. Calculated Field Creation**
1. Created a calculated measure for Unhealthy Field\n
2. Represents 10 minutes of downtime per unhealthy signal\n

###**3. Visualization Development**
####**Down Time per Factory**
1. Bar chart showing total downtime by factory\n
2. Helps identify worst-performing location\n

####**Down Time per Device Type**
1. Bar chart showing downtime by machine type\n
2. Identifies failure-prone machines\n

###**4. Dashboard Creation**

Built an interactive dashboard including:\n
1. Factory downtime visualization\n
2. Device-type downtime visualization\n
3. Cross-filter functionality\n

####Selecting a factory dynamically filters machine performance.
