# 🚖 RideSmart OLA Rides Analysis  

An end-to-end data analysis project exploring booking patterns, cancellations, payments, customer/driver ratings, and revenue for OLA rides.  
The project leverages **SQL for data querying** and **Power BI for interactive dashboards**, delivering insights that can help optimize operations, reduce cancellations, and improve customer experience.  

---

## 📊 Dashboards  
Interactive dashboards are built in **Power BI** to visualize key metrics like revenue, cancellations, ratings, and booking patterns.  

> 🔎 For **detailed insights, interpretations, and recommendations**, please open the  
**`RideSmart - OLA Rides Analysis.pdf`** report included in this repository.  

---

### Overall Page  
![Overall Dashboard]()  

**Booking Status Breakdown**  
**Insights:**  
- Majority of rides were successful, while 17% were driver cancellations and 10% were customer cancellations, showing both operational and customer-side challenges.  
- 9% of rides failed due to drivers not being found, highlighting gaps in geographic coverage or real-time tracking.  

**Recommendation:**  
- Optimize driver allocation and scheduling during peak demand, and implement automated customer reminders.  
- Investigate high “driver not found” areas and incentivize high-performing drivers to maintain reliability.  

**Ride Volume Over Time**  
**Insights:**  
- Daily ride volumes in July range from 3,072 to 3,432, showing peak demand days.  
- Highlights unusually high or low days, useful for operational planning.  

**Recommendation:**  
- Use ride volume trends to optimize driver scheduling and detect anomalies proactively.  

-- Total bookings: 103,024; total booking value: ₹35.08M.  
-- Dates can be adjusted to analyze trends for different periods.  

---

### Vehicle Type  
📸 *Dashboard Screenshot*  

**Vehicle Type Performance**  
**Insights:**  
- Premium vehicles (Prime Sedan, Prime SUV, Prime Plus) generate the highest revenue and success booking value, with average distances ~25 km, reflecting strong utilization and preference for longer trips.  
- Mini, Bike, and E-Bike maintain consistent performance, while Auto has shorter average distance (~10 km) indicating short urban trips.  
- Success booking values are consistently lower than total booking value, showing cancellations or incomplete rides, suggesting demand-based allocation and promotions.  

**Recommendation:**  
- Focus marketing, premium offers, and loyalty programs on high-performing vehicles to boost revenue and encourage longer trips.  
- Optimize allocation of short-distance vehicles (Auto, Bike, E-Bike) to dense trip areas; leverage E-Bike’s high utilization.  
- Address cancellations (especially Mini and Auto) and adjust pricing, surge, or driver incentives to improve success rate.  

---

### Revenue  
📸 *Dashboard Screenshot*  

**Revenue by Payment Method**  
**Insights:**  
- Cash dominates with revenue exceeding ₹15M, showing heavy reliance on traditional payment methods.  
- UPI follows at ~₹12M, reflecting growing digital adoption, while cards contribute minimally.  

**Recommendation:**  
- Encourage digital payments via cashback and loyalty rewards to reduce dependency on cash.  
- Partner with banks to boost UPI usage, improving efficiency and reducing risks from cash handling.  

**Revenue Contribution by Distance Range**  
**Insights:**  
- Long-distance rides (20+ km) generate the highest revenue, highlighting profitability in extended trips.  
- 10–20 km trips contribute moderately, while short-distance rides add little revenue despite higher volume.  

**Recommendation:**  
- Introduce surge pricing and premium offers for long trips to maximize margins.  
- Promote cost-effective options (Auto, Bike, E-Bike) for short trips to maintain affordability while balancing profits.  

-- The top customer alone contributes over ₹6,000 in bookings, reflecting strong loyalty. Launch loyalty rewards and referral programs to retain high-value customers and encourage repeat bookings.  
-- Added slicers allow analysis by vehicle type and date range for deeper insights.  

---

### Cancellation & Ratings  
📸 *Dashboard Screenshots*  

**Cancelled Rides by Customers**  
**Insights:**  
- 30% due to drivers not moving towards pickup and 25% from drivers asking customers to cancel highlight service reliability issues.  
- 19% “change of plans” and 14% “AC not working” show unpredictability and vehicle condition gaps.  

**Recommendation:**  
- Strengthen driver monitoring and accountability to reduce service-driven cancellations.  
- Offer flexible rebooking and regular maintenance checks to reduce customer-side issues.  

**Cancelled Rides by Drivers**  
**Insights:**  
- 35% cancellations due to personal & car-related issues, the largest cause.  
- 29% customer-related issues, 19% sickness, and 15% excess passengers reflect safety/compliance factors.  

**Recommendation:**  
- Introduce vehicle health checks and driver support to reduce operational issues.  
- Provide training and stricter policies to handle customer-related cancellations.  

-- Driver ratings are consistent across vehicle types (3.98–4.01), showing stable service quality.  
-- Customer ratings average ~4.0, suggesting satisfactory but improvable experience.  

---

## 📂 SQL Queries  
All SQL queries used in this project are stored separately in **`SQL_Queries.txt`**.  
You can review them independently to understand the exact data extraction and transformations applied.  

---

## 🛠 Tech Stack  
- **SQL** → Data extraction & cleaning  
- **Power BI** → Dashboard creation & visualization  
- **Excel/CSV** → Raw data handling  

---

## 👨‍💻 Created By  

**Aditya Raj**  
> B.Tech CSE | Bennett University  
> Data Analytics & AI Enthusiast  

- 📧 Email: [aditya.work0902@gmail.com](mailto:aditya.work0902@gmail.com)  
- 💻 GitHub: [@Aditya-0009](https://github.com/Aditya-0009)  
- 👔 LinkedIn: [Aditya Raj](https://www.linkedin.com/in/aditya-raj-0009/)  
- 📸 Instagram: [@ig._adi_](https://www.instagram.com/ig._adi_/)
