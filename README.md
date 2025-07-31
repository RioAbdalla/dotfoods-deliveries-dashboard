# Dot Foods Deliveries Dashboard

## 📌 Project Overview
This project analyzes **Dot Foods 2023 deliveries** using exploratory data analysis (EDA) and develops **interactive Power BI dashboards** to provide visibility into shipment performance, driver activity, and operational efficiency.  

The analysis covers delivery volumes, distances, weights, and performance benchmarking across states, cities, and drivers — enabling Dot Foods to monitor logistics KPIs and optimize operations.

---

## 📊 Methodology
1. **Data Preparation (EDA)**  
   - Cleaned and explored delivery data using Python in Jupyter Notebook.  
   - Analyzed distributions of **miles traveled, shipment weights, and delivery frequency**.  
   - Identified operational benchmarks such as median load weight (~31K lbs) and median trip distance (~168 miles).  

2. **Dashboard Development (Power BI)**  
   - Built interactive visuals to track:  
     - **Overall delivery performance**  
     - **Deliveries per state/city**  
     - **Driver-level metrics** (most deliveries, most miles, most days driving)  
   - Incorporated filters for states, cities, and drivers to enable flexible analysis.  

---

## 📈 Key Insights
- Total deliveries: **259,508** across the U.S.  
- Median load weight: **31,402 lbs**  
- Median miles per trip: **168 miles**  
- **Top lanes**: Mount Sterling (IL) ↔ Chicago (IL), Mount Sterling (IL) ↔ Tennessee  
- **Driver benchmarks**:  
  - Most deliveries: *Stephen Martin*  
  - Most miles: *Andrew White*  
  - Most days driving: *Richard Butler*  

---

## 🛠️ Tech Stack
- **Python** (EDA): `pandas`, `numpy`, `matplotlib`, `seaborn`  
- **Visualization**: Power BI  
- **Notebook**: Jupyter  

---

## 📂 Repository Structure
```
├── Basic_EDA_Dot_Foods_Phase_2.ipynb     # Jupyter Notebook with EDA
├── Dot Foods Dashboard 2.pdf             # Power BI dashboard export
└── README.md                             # Project documentation
```

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/dotfoods-deliveries-dashboard.git
   cd dotfoods-deliveries-dashboard
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Basic_EDA_Dot_Foods_Phase_2.ipynb
   ```
3. Open the Power BI dashboard in **Power BI Desktop** using the included PDF as reference.

---

## 🤝 Contributors
- Damario Abdalla  

---

## 📜 License
Add your chosen license here (MIT recommended if open-source).  
