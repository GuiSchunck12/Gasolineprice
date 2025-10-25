# 🛢️ Brazil Fuel Price Dashboard

This project analyzes **fuel price trends across Brazil** using open government data.  
The dashboard was built in **Microsoft Excel** with **Power Query**, **Power Pivot**, and **DAX**, providing interactive insights into the variation of fuel prices by **region, state, and time period**.

---

## 📂 Data Source
The dataset was obtained from the **Brazilian Government’s Open Data Portal**, which publishes semiannual information on fuel prices collected across the country.  
Each record includes details such as fuel type, region, state, municipality, and collection date.

📎 *Source:* [https://dados.gov.br](https://dados.gov.br)

---

## 🧠 Tools and Techniques
- **Microsoft Excel** (Power Query + Power Pivot)
- **DAX (Data Analysis Expressions)** for creating measures:
  - `Average Price (Preço Médio)`
  - `Maximum Price (Preço Máximo)`
  - `Minimum Price (Preço Mínimo)`
- **Pivot Tables and Slicers** for interactivity
- **Map Visualization** using Bing Maps integration
- **Dashboard Layout** for intuitive data exploration

---

## ⚙️ Data Modeling Approach
Due to Excel’s row limit (1,048,576 rows), it was not possible to load the entire dataset directly into worksheets.  
To handle large volumes of data efficiently:
- The data was **loaded directly from Power Query into the Power Pivot data model**,  
  without creating intermediate Excel tables.
- All transformations and calculations were done within **Power Query** and **DAX**,  
  ensuring optimized performance and a lightweight dashboard.
- The **Power Pivot Data Model** acts as the single source of truth for all visualizations.

This architecture allows Excel to manage millions of records efficiently while maintaining interactivity and performance.

---

## 📊 Dashboard Overview
The dashboard includes:

- 📅 **Time filter** by data collection period  
- 🗺️ **Regional map** showing average prices by state  
- ⛽ **Comparison by fuel type** (Gasoline, Diesel, Ethanol, GNV)  
- 📈 **Price trends** over time  
- 🏷️ **Brand analysis** (comparison between different distributors)

---

## 💡 Key Insights
- Clear visualization of **regional price disparities**  
- Identification of **fuel types with the highest variation**  
- **Monthly trends** in fuel prices across Brazil  

---

## 🧩 Project Structure


---

## 🔗 View the Dashboard
You can view or download the dashboard here:  
👉 [View on OneDrive](https://onedrive.live.com/) *(replace this link with your actual URL)*  

---

## 👨‍💻 Author
**Guilherme Cassimiro Schunck Cazac**  
📍 São Paulo, Brazil  
🔗 [LinkedIn](www.linkedin.com/in/guilherme-schunck1207199712)  

---

⭐ *If you found this project useful, feel free to star this repository!*

