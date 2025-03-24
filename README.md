### **README: Pixar Movies Power BI Dashboard**  

#### **📌 Overview**  
This Power BI report was created as part of a challenge for **Maven Analytics**. The dashboard provides an interactive analysis of **Pixar movies**, covering key insights such as budget vs box office performance, ratings, genres, and profitability.  

---

#### **📊 Key Features & Visuals**  
✔ **Budget vs Box Office Comparison** – Analyze how each movie performed financially.  
✔ **Genre Analysis** – Explore the distribution of genres and subgenres.  
✔ **Profitability Insights** – Identify top-grossing and underperforming movies.  
✔ **Runtime Breakdown** – Convert and display movie durations in an easy-to-read format.  
✔ **Dynamic Filters** – Use slicers to filter by **Year, Genre, and Box Office Performance**.  

---

#### **🔍 Data Processing & Transformations**  
- **Power Query**:  
  - Cleaned and structured the Pixar movie dataset.  
  - Transformed categorical values for better analysis.  
  - Grouped and pivoted role-based data for better visualization.  

- **DAX Functions Used**:  
  - **CALCULATE**: To filter and aggregate values dynamically.  
  - **SUMX / AVERAGEX**: To compute financial performance metrics.  
  - **FORMAT**: To convert runtime from minutes to "X hrs Y min" format.  
  - **IF / SWITCH**: For conditional formatting and classification.  

---

#### **🖥️ How to Use the Dashboard**  
1️⃣ Open the **Power BI (.pbix) file** in Power BI Desktop.  
2️⃣ Use the **slicers** to filter movies by Year, Genre, or Performance.  
3️⃣ Hover over visuals for additional insights via **tooltips**.  
4️⃣ Click on different sections to explore relationships between Budget, Box Office, and Ratings.  

---

#### **📂 Data Source**  
- Pixar movie data compiled from multiple sources including public datasets.  
- Enriched with additional metrics using DAX and Power Query.  

---

#### **🚀 Future Enhancements**  
🔹 **Incorporate IMDb/Rotten Tomatoes ratings** for a deeper analysis.  
🔹 **Add a timeline visualization** to track Pixar’s financial trends over the years.  
🔹 **Enhance UX/UI** with better interactivity and animations.  

---

Hope you find this dashboard insightful! 🎬📊  
Let me know if you have any feedback or suggestions. 🚀  
