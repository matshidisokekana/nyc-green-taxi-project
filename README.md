
---

## **1. Introduction**  
This project is an end-to-end **NYC Green Taxi project** built using **Azure Data Factory, Databricks, Delta Lake, and Power BI**. It follows a structured **Medallion Architecture (Bronze, Silver, Gold)** to ensure optimized data processing, transformation, and reporting.  

---

## **2. Problem Statement**  

### **Q: How can we optimize NYC Green Taxi operations by identifying high-demand locations?**  

### **Answer:**  
- By analyzing **pickup and drop-off patterns**, we can pinpoint **high-demand zones**.  
- This helps taxi companies **optimize fleet distribution** and **improve service efficiency**.  
- Using **Power BI**, we create dynamic dashboards for real-time decision-making.  

---

## **3. Skills Demonstrated**  
✅ **Data Engineering** → Data ingestion, transformation, and storage using **Azure Data Factory & Databricks**.  
✅ **Data Modeling** → Implemented **Medallion Architecture** (Bronze, Silver, Gold) for structured data processing.  
✅ **Power BI Visualization** → Built interactive dashboards showing **top pickup/drop-off locations**.  
✅ **Security & Access Control** → Used **Service Principal** to manage access in **Azure Data Lake**.  

---

## **4. Data Sourcing**  
- **Fetched data directly from the website.**  
- **Azure Data Factory** was used for ingestion via **API connections**.  
- Data was stored in **Azure Data Lake (Gen2)** using **Parquet format** for efficiency.  

---

## **5. Data Transformation**  
✔ **Bronze Layer:** Raw data stored in **Parquet format**.  
✔ **Silver Layer:** Used **PySpark transformations** to clean and filter the data.  
✔ **Gold Layer:** Created **Delta Tables** for efficient querying in Power BI.  

### **Specific Transformation:**  
- Filtered **Top 10 Pickup & Drop-off Locations** based on trip count.  
- Aggregated data for **performance optimization** in Power BI.  

---

## **6. Data Modeling**  
- Used **Flat Tables** to simplify relationships between **trip data, taxi zones, and taxi types**.  
- Directly connected **Power BI to Databricks Delta Tables** for real-time analytics.  
- Optimized data queries for **better dashboard performance**.  

---

## **7. Analysis & Visualizations**  
Key Insights from Power BI Dashboard:  
- **Top Boroughs & Zones:** Identified **high-demand locations** (e.g., JFK, Manhattan).  
- **Trip Volume Trends:** Analyzed **peak hours and days** for better fleet management.  
- **Drop-off vs. Pickup Patterns:** Helped **optimize taxi allocation strategies**.  

---

## **8. Conclusion & Recommendations**  

### **Conclusion:**  
✔ **Manhattan & JFK Airport** are the most frequent taxi zones.  
✔ **Optimizing fleet allocation** in high-demand areas can improve efficiency.  
✔ **Real-time dashboards** help businesses track trends and make data-driven decisions.  

### **Recommendations:**  
- Deploy **dynamic pricing models** for high-demand zones.  
- Increase taxi availability in **peak hours** for better service.  
- Use **real-time analytics** for **data-driven fleet management**.  

---

## **9. Challenges & Growth**  

### **Challenges Faced:**  
❌ **Large data volume** – Optimized using **Parquet & Delta Tables**.  
❌ **Security restrictions** – Implemented **Service Principal for Data Lake access**.  
❌ **Performance issues in Power BI** – Solved by **filtering top 10 locations**.  

### **Growth & Learning:**  
✅ Improved **Azure Data Engineering** skills.  
✅ Gained experience in **Databricks Cluster Management**.  
✅ Enhanced **Power BI Report Optimization** techniques.  

---

## **10. Technologies Used**  
- **Azure Data Factory** → Data ingestion via **APIs**.  
- **Databricks** → Managed **clusters, transformations, and Delta Tables**.  
- **Azure Data Lake Gen2** → Stored data in **Parquet & Delta format**.  
- **Power BI** → Built **interactive dashboards & visualizations**.  

---


