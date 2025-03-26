# 📊 Analysis of Booking Data for a Multi-Service Business  

---

## **1. Introduction**
The objective of this assessment is to analyze the booking data for a multi-service business. The dataset contains various types of bookings, including class enrollments, facility rentals, birthday party reservations, and subscriptions. The goal of this project is to clean and analyze the dataset, identify trends, and present insights using an interactive dashboard.

---

## **2. Data Cleaning & Preprocessing**

### **2.1 Identified Data Issues**
- **Missing Values:** Found in `Class Type`, `Instructor`, `Facility`, `Time Slot`, and `Theme`.
- **Duplicate Entries:** Checked and removed duplicates.
- **Inconsistent Formatting:**
  - Standardized `Time Slot` and `Customer Phone`.
  - Ensured `Booking Date` was in datetime format.
  
### **2.2 Data Cleaning Steps**
- **Filled missing values** with "Unknown" or "Not Applicable" where appropriate.
- **Converted numeric columns** (`Price`, `Duration (mins)`) into proper data types.
- **Checked for outliers** in `Price` and `Duration` (values above the 99th percentile).

---

## **3. Exploratory Data Analysis (EDA) & Insights**

### **3.1 Bookings Distribution by Type**
- **Facility Rentals, Birthday Parties, and Classes** are the most frequently booked services.
- **Subscriptions** have significantly lower bookings.

### **3.2 Revenue Insights**
- **Facility Rentals contribute the highest revenue** (~$48,769).
- **Birthday Parties generate lower revenue than expected** despite high booking numbers.

### **3.3 Monthly Booking Trends**
- **Bookings peaked in April and May.**
- **March had the lowest bookings**, indicating potential seasonal fluctuations.

---

## **4. Interactive Dashboard**
- Developed using **Power BI/Tableau/Python Dash**.
- **Key Visualizations Included:**
  - **Booking trends over time.**
  - **Revenue breakdown by service type.**
  - **Most popular services and facilities.**

---

## **5. Challenges & Solutions**
| Challenge | Solution |
|-----------|----------|
| Missing values in key columns | Used logical imputation based on booking type |
| Outliers in pricing | Reviewed extreme values and handled them accordingly |
| Data inconsistencies | Standardized categories and formats |

---

## **6. Conclusion & Recommendations**

### **6.1 Key Findings**
- **Facility Rentals drive the most revenue.**
- **Birthday parties have high bookings but lower revenue impact.**
- **Seasonal demand peaks in April & May.**

### **6.2 Business Recommendations**
✅ **Optimize pricing for Birthday Party bookings.**  
✅ **Introduce promotions during March to boost low bookings.**  
✅ **Expand facilities that generate the most revenue.**  

---

## **7. Final Deliverables**
✔ **Interactive Dashboard** (Power BI/Tableau)  
✔ **Cleaned Final Dataset**  
✔ **Report**  
 

---

