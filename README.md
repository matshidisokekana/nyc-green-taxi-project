
---  

## **1. Introduction**  
The **NYC Green Taxi project** aims to extract, transform, and analyze taxi trip data to gain insights into the most frequently used pickup/drop-off locations, demand patterns, and operational efficiencies.  

### **Business Objective:**  
- Identify high-demand zones for green taxis.  
- Optimize taxi distribution based on trip data.  
- Improve reporting efficiency using Power BI.  

---  

## **2. Problem Statement**  
### **Q: How can we efficiently analyze and visualize NYC Green Taxi trip data to identify demand patterns and optimize operations?**  

### **Answer:**  
By leveraging **Azure Data Factory for ingestion, Databricks for transformation, and Power BI for visualization**, we processed and analyzed trip data to uncover key demand locations, trends, and inefficiencies in taxi operations.  

---  

## **3. Skills Demonstrated**  
✅ **Data Ingestion:** Fetching data from a website and APIs using **Azure Data Factory (ADF)**.  
✅ **Data Engineering:** Using **Databricks clusters** for data transformation.  
✅ **Data Modeling:** Implementing a **Medallion Architecture** (Bronze, Silver, Gold layers).  
✅ **ETL Pipelines:** Using **ForEach loops, parameters, and linked services** in **ADF**.  
✅ **Security Management:** Configuring **Service Principal & Data Lake Access**.  
✅ **Data Visualization:** Connecting **Databricks Delta Tables** directly to **Power BI**.  

---  

## **4. Data Sourcing**  
- **Source:** API ingestion via **Azure Data Factory**.  
- **Storage:** Data stored in **Azure Data Lake Gen2** in **Parquet format**.  
- **Processing:** Managed using **Databricks clusters**.  

---  

## **5. Data Transformation**  
### **Medallion Architecture:**  
- **Bronze Layer:** Stores **raw Parquet files** from the API.  
- **Silver Layer:** PySpark transformations applied → Data stored in **Parquet**.  
- **Gold Layer:** Data transformed into **Delta Tables** for analytics.  

### **Key Transformations:**  
- Filtering **Top 10 Pickup/Drop-off Locations** to reduce data volume.  
- Aggregating trip counts to identify **high-demand zones**.  
- Optimizing data structure for faster reporting in **Power BI**.  

---  

## **6. Data Modeling**  
A **flat-table model** was used to simplify relationships, making **Power BI connections more efficient**. Key tables:  
- **TaxiType** (Trip types, descriptions)  
- **TaxiZone** (Borough, service zones)  
- **TripsData2023** (Pickup & Drop-off locations, Vendor IDs)  

---  

## **7. Analysis & Visualizations**  
Created a **Power BI dashboard** with the following insights:  
✅ **Top Pickup & Drop-off Zones:** Identified high-traffic areas.  
✅ **Trip Counts by Borough & Zone:** Compared demand across different locations.  
✅ **Demand Patterns:** Highlighted busiest areas using **bar charts & pie charts**.  

---  

## **8. Conclusion & Recommendations**  
### **Findings:**  
1. **Manhattan & Brooklyn** have the highest taxi demand.  
2. Some **drop-off locations have significantly lower counts**, indicating inefficiencies.  
3. **Power BI performance improved** by filtering the top 10 locations.  

### **Recommendations:**  
✅ **Optimize taxi fleet distribution** based on high-demand areas.  
✅ **Improve routing efficiency** by analyzing imbalances between pickup & drop-off.  
✅ **Enhance Power BI reporting** by maintaining a structured data model.  

---  

## **9. Technologies Used**  
- **Azure Data Factory** → Ingestion (APIs, pipelines)  
- **Databricks** → Data transformation & cluster management  
- **Azure Data Lake** → Data storage in **Parquet & Delta formats**  
- **Power BI** → Reporting & data visualization  
- **Service Principal** → Secure access management  

---  

### 🚀 **Project Impact:**  
✅ **Reduced data load by filtering key insights** (Top 10 locations).  
✅ **Improved Power BI performance & dashboard usability**.  
✅ **Enabled real-time analytics with Delta Tables**.  
✅ **Enhanced decision-making for fleet distribution**.  

---  
