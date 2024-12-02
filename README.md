# **Data Cleaning and Modelling: Top 5 Categories Analysis**

This repository contains a data analysis project focused on cleaning, merging, and analyzing data to identify the top 5 performing categories based on popularity scores. The project was completed in two main phases: **data cleaning** and **data modelling**.

---

## **Project Overview**

The goal of this project was to:
1. **Clean datasets** to ensure data consistency and usability.
2. **Merge datasets** to create a comprehensive dataset for analysis.
3. **Identify and analyze the top 5 categories** based on aggregate popularity scores.

### **Key Deliverables**
- A cleaned dataset.
- A final merged dataset.
- Insights into the top 5 categories by aggregate popularity scores.
- Visualizations (bar chart and pie chart) for better data understanding.
- A presentation summarizing the tasks and results.

---

## **Tasks and Methodology**

### **Task 1: Data Cleaning**
The first phase of the project involved cleaning three datasets:
1. Removing duplicates and irrelevant columns.
2. Ensuring data consistency (e.g., handling missing values).
3. Preparing the datasets for merging.

The cleaned datasets are available in the `data/cleaned_data.xlsx` file.

---

### **Task 2: Data Modelling**
This phase involved merging datasets and calculating aggregate popularity scores for each category.

**Steps:**
1. **Merging Datasets**:
   - Used the `Reaction` table as the base table.
   - Joined relevant columns from the `Content` and `Reaction Types` datasets using a **VLOOKUP** formula.
2. **Calculating Scores**:
   - Used the **SUMIF** formula to aggregate popularity scores for each category.
3. **Identifying the Top 5 Categories**:
   - Ranked categories by their total scores to identify the top 5 performers.

The final dataset can be found in `data/final_data.xlsx`.

---

### **Results**
#### **Top 5 Categories**
The analysis revealed the following top-performing categories:
1. **Animals**
2. **Science**
3. **Healthy Eating**
4. **Technology**
5. **Food**

#### **Visualizations**
- A **bar chart** visualizing the aggregate popularity scores for the top 5 categories.
- A **pie chart** showing the percentage share of each category in the top 5.
