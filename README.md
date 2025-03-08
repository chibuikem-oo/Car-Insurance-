# **Car Insurance Policies Analysis**

## **Project Overview**
This repository contains an analysis of car insurance policies and claims data to identify key patterns in customer demographics, claim amounts, and risk factors. The dataset includes information about **customer details, vehicle attributes, insurance claims, and financial metrics**. The goal of this project is to derive actionable insights to improve insurance policy strategies and risk assessment.

## **Objectives**
- Analyze **car usage distribution** based on gender and household demographics
- Identify **car makes and models** with the highest insurance claims
- Examine **correlations between education level and claim frequency**
- Determine **the impact of car color on insurance claims**
- Evaluate **claim variations across different coverage zones**
- Assess **the relationship between household income and claim behavior**
- Provide an interactive **Power BI dashboard** to visualize key findings

## **Data Sources and Tools Used**
- **Dataset**: Car Insurance Dataset (containing customer and claim records)
- **Tools Used**:
  - **Microsoft Excel**: Data cleaning and preprocessing
  - **Power BI Desktop**: Data visualization and dashboard creation

## **Exploratory Data Analysis (EDA)**
### **Data Description**
The dataset contains the following key columns:
- **id** – Unique customer ID
- **birthdate** – Customer’s date of birth
- **marital_status** – Marital status of the customer
- **car_use** – Purpose of the car (private or commercial use)
- **gender** – Gender of the customer
- **kids_driving** – Number of kids using the car
- **parent** – Whether the customer is a parent
- **education** – Education level of the customer
- **car_make** – Manufacturer of the car
- **car_model** – Model of the car
- **car_color** – Color of the car
- **car_year** – Year the car was manufactured
- **claim_freq** – Number of times the customer has made an insurance claim
- **coverage_zone** – The geographic coverage area for the insurance
- **claim_amt** – Amount claimed by the customer
- **household_income** – Household income of the customer

## **Methodology**
### **Data Cleaning & Preparation**
- Handled missing values and corrected inconsistencies in Excel
- Standardized numerical values for claim amounts and income
- Categorized data to analyze trends across different demographics

### **Data Analysis in Excel**
- Used Pivot Tables to analyze claim frequency by **car make, model, and color**
- Assessed **customer claim behavior** based on education level and household income
- Examined insurance coverage zones and their impact on claim amounts

### **Visualization & Insights in Power BI**
- Built an interactive dashboard summarizing key findings
- Created bar charts to compare **car usage by gender and kids driving**
- Visualized **insurance claims by car make and model**
- Analyzed **claim amount distribution by education level**
- Identified **top car colors associated with frequent insurance claims**

## **Key Insights & Interpretation**
### **1. Car Usage by Gender and Kids Driving**
- Males and females show **equal distribution in car usage**, but commercial use is higher among males.
- Households with **kids driving have a higher claim frequency**, indicating increased risk.

### **2. Car Makes and Models with the Most Claims**
- The **Grand Prix, Corvette, and Mustang** had the highest number of claims.
- Certain luxury brands had **higher average claim amounts**, suggesting expensive repairs.

### **3. Claim Frequency by Education Level**
- Customers with **Bachelor's and High School degrees** had the most claims.
- Higher education levels (Masters, PhD) correlated with slightly lower claim frequency.

### **4. Car Color and Insurance Claims**
- **Turquoise, Aquamarine, and Green cars** were associated with the highest claim frequencies.
- Possible explanations include **visibility factors or customer preference trends**.

### **5. Claim Amount by Coverage Zone**
- **Highly urban areas had the highest total claim amounts**.
- Rural areas had **fewer claims but relatively high average claim amounts**.

### **6. Household Income and Claim Behavior**
- **Middle-income earners filed the most claims**, followed by low-income groups.
- Higher-income earners had **fewer claims but larger claim amounts**.

## **Data Visuals**
The Power BI dashboard includes:
- **Distribution of kids driving by gender**
- **Most claimed car makes and models**
- **Claim frequency and amounts by education level**
- **Insurance claims by car color**
- **Coverage zone analysis of claim amounts**
- **Household income vs. claim behavior**

### **Dashboard Preview**
![image](https://github.com/user-attachments/assets/277b6106-f29d-4d8d-8235-da7b5ff98fa9)

## **Data Story**
This dashboard was created to explore how **customer demographics, car attributes, and financial factors** influence car insurance claims. The goal is to provide insights for optimizing **insurance pricing, risk assessment, and policy strategies**.

### **Key Findings**
- Households with **kids driving have higher claim frequencies**.
- **Luxury car brands** tend to have higher **average claim amounts**.
- **Middle-income earners** file the most claims, while high-income earners have fewer but more expensive claims.
- **Urban areas have higher total claim amounts**, whereas rural areas have fewer but costlier claims.

### **Conclusion**
To improve risk management in car insurance policies:
- Adjust **policy pricing based on coverage zones** and **income groups**.
- Consider **car make and color** as potential risk factors.
- Encourage **safe driving habits among households with kids driving**.
