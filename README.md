
# 🚖 Uber Trip Analysis  

This project presents a detailed analysis of Uber ride bookings using **Power BI**. It provides insights into booking patterns, trip distances, vehicle preferences, payment methods, and location-based trends. The analysis is based on Uber trip datasets and visualized in an interactive dashboard.  

---

## 📂 Project Files  

- **`uber.pbix`** → Power BI dashboard file containing the analysis and visualizations.  
- **`Uber Trip Details.xlsx`** → Dataset containing trip-level details such as booking amount, distance, trip type, and timestamps.  
- **`Location Table.xlsx`** → Dataset with location details for pickup and drop-off points.  
- **`Output.png`** → Example dashboard view of the analysis.  

---

## 📊 Dashboard Insights  

### 🔹 Key Metrics  
- **Total Bookings:** 103.7K  
- **Total Booking Amount:** $1.55M  
- **Average Booking Amount:** $14.98  
- **Total Trip Distance:** 348.9K miles  
- **Average Trip Distance:** 3 miles  
- **Average Trip Time:** 16 minutes  

### 🔹 Vehicle Trip Analysis  
| Vehicle       | Total Bookings | Total Booking Amount | Avg. Booking ($) | Total Distance |
|---------------|---------------:|---------------------:|-----------------:|---------------:|
| UberX         | 38,744         | $583,879.64          | $15.07           | 131.5K miles   |
| Uber Black    | 16,710         | $250,192.46          | $14.97           | 56.1K miles    |
| UberXL        | 16,698         | $249,424.43          | $14.94           | 55.7K miles    |
| Uber Green    | 14,498         | $216,180.79          | $14.91           | 48.8K miles    |
| Uber Comfort  | 17,078         | $253,995.49          | $14.87           | 56.8K miles    |

### 🔹 Payment Mode Distribution  
- **Uber Wallet** → 66.26%  
- **Cash / Other methods** → 33.74%  

### 🔹 Trip Type Distribution  
- **Day Trips:** 60.39%  
- **Night Trips:** 39.61%  

### 🔹 Location Insights  
- **Most Frequent Pickup Point:** Penn Station / Madison Sq.  
- **Most Frequent Drop-off Point:** Upper East Side North  
- **Top Locations by Bookings:**  
  - Penn Station (4.5K)  
  - Upper East Side (4.5K)  
  - Times Sq. (4.1K)  
  - Lenox Hill (4.0K)  
  - Upper West Side (3.8K)  

### 🔹 Vehicle Preferences  
- **Most Preferred Vehicle:** UberX (7.7K bookings)  
- Uber Comfort, Black, XL, and Green follow with ~3–3.5K bookings each.  

### 🔹 Trend Analysis  
- **Total Bookings by Day** → Clear peaks and troughs across the month, with several spikes reaching **4K+ daily bookings**.  

---

## ⚙️ Tools & Technologies  

- **Power BI** → Data modeling & visualization.  
- **Excel** → Raw datasets for trip details and locations.  
- **DAX** → Calculations for average booking, distance, and filtering.  

---

## 🚀 How to Use  

1. Clone the repository:  
   ```bash
   git clone https://github.com/itsvishal1012/Uber_Data_Analysis.git
   cd uber-trip-analysis
   ```
2. Open the Power BI file `uber.pbix` in **Power BI Desktop**.  
3. Connect datasets (`Uber Trip Details.xlsx`, `Location Table.xlsx`) if required.  
4. Explore the interactive dashboard with filters (Date, City).  

---

## 📌 Learning Outcomes  

- Data cleaning and preparation using Excel.  
- Creating relationships between multiple datasets in Power BI.  
- Using **DAX** for calculated measures like average booking, trip time, and distance.  
- Visual storytelling through charts:  
  - Donut charts for payments and trip type.  
  - Line charts for daily trends.  
  - Bar charts for location and vehicle preferences.  
- Business insights into **customer behavior, revenue drivers, and operational efficiency**.  

---

## 📷 Dashboard Preview  

![Uber Trip Dashboard](Output.png)  

---

## ✨ Future Enhancements  

- Add **predictive analytics** (e.g., peak demand forecasting).  
- Integrate **real-time data** for live monitoring.  
- Expand analysis to include **driver performance** and **customer ratings**.  

---

## 📝 Author  

👤 **Vishal Saini**  
- 📧 Email: vishalsaini0328.email@example.com  
- 🌐 GitHub:(https://github.com/itsvishal1012)  
