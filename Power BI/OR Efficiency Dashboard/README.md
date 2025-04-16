# OR Efficiency Dashboard

This Power BI dashboard project analyzes Operating Room (OR) efficiency using data from three distinct surgical services. The goal is to identify opportunities to reduce inefficient use of OR resources, such as idle time or surgical delays, and to provide actionable insights to hospital administrators.

---

## 📊 Dashboard Overview

The dashboard consists of **five pages**, each offering a different analytical perspective:

### 1. Overview

<img width="987" alt="Screenshot 2025-04-16 at 12 11 54 AM" src="https://github.com/user-attachments/assets/dda95c62-7bce-454e-b0de-8423a2e39216" />

Provides a high-level summary of OR efficiency through key metrics and visualizations:
- **KPIs**:  
  - Average First Case On-Time Start (%)  
  - Average Block Utilization (%)
  - and more  
- **Visuals**:  
  - Surgeries Count by Surgeon (Bar Chart)  
  - FCOTS by Room (Bar Chart)  
  - Average Overtime by Surgeon (Bar Chart)  
  - and more

### 2. FCOTS Analysis (First Case On-Time Starts)

<img width="988" alt="Screenshot 2025-04-16 at 12 12 34 AM" src="https://github.com/user-attachments/assets/935efa20-b26e-46ca-8d23-e35dde6d3e1b" />

- First surgeries starting on time is a critical indicator of OR efficiency.  
- Gauge charts show FCOTS (%) by room.  
- Institutions aim for **90%+ FCOTS** for optimal performance.  
- Histogram and bar charts included, with **red flags for late starts**.

### 3. Block Utilization

<img width="1002" alt="Screenshot 2025-04-16 at 12 13 09 AM" src="https://github.com/user-attachments/assets/e24c1cdd-93cc-4958-b307-58429d53f5cc" />

- Highlights how efficiently scheduled OR time is used.
- Gauge chart target: **80% utilization** (not too high to maintain flexibility).

### 4. Overrun

<img width="999" alt="Screenshot 2025-04-16 at 12 13 47 AM" src="https://github.com/user-attachments/assets/5ff12418-bf92-464a-91fc-4c3b7dd2485a" />

- Overruns occur when surgeries go beyond their scheduled time.
- Visuals include:
  - Overrun Count by Surgeon  
  - Average Turnover Time by Surgeon  
  - and more

### 5. About

<img width="988" alt="Screenshot 2025-04-16 at 12 14 18 AM" src="https://github.com/user-attachments/assets/753f7b56-9743-4e25-819c-debecec90018" />

Outlines business objectives, benefits, and definitions of key metrics.

---

## 🔍 Insights & Findings

### 🚨 Room C: FCOTS Issues

<img width="173" alt="image" src="https://github.com/user-attachments/assets/2913a6f0-2528-4cbb-a560-8517f9af536e" />
<img width="287" alt="image" src="https://github.com/user-attachments/assets/04b9bdca-20cf-450f-b04c-9708d3f8cea0" />

- Room C has the **lowest on-time start rate**, with delays of 15–20 minutes.
- These delays create a ripple effect for the rest of the day.
- **Recommendations**:  
  - Improve evening-before setup  
  - Send automated reminders to surgeons and staff

### 🧱 Block Utilization & Overruns

<img width="189" alt="image" src="https://github.com/user-attachments/assets/e705d442-bb0d-44d9-9ebe-7e24b9f742f0" />
<img width="164" alt="image" src="https://github.com/user-attachments/assets/63ca15bd-9431-4c29-b02e-13e82f69a7a5" />
<img width="211" alt="image" src="https://github.com/user-attachments/assets/eb226cbf-ec29-4202-966a-1487d2c57b60" />
<img width="220" alt="image" src="https://github.com/user-attachments/assets/e0165028-98d8-434d-8905-55c606d387b8" />

- **Dr. Red** consistently exceeds 90% utilization (sometimes >100%), with **28 overruns** and the **longest average surgery duration**.
- Suggests complex cases or unrealistic scheduling.
- **Recommendations**:  
  - Add buffer time to schedule  
  - Investigate case complexity  
  - Monitor trends for adjustments

### 🔁 Room A: Turnover Inefficiency

<img width="281" alt="image" src="https://github.com/user-attachments/assets/862e011d-bea2-4e26-893e-5d494dbc01a0" />

- Room A has the **longest turnover time**.
- Shared by **Dr. Black and Dr. Green**, possibly causing transition delays.
- **Recommendations**:  
  - Better coordination between shared surgeons  
  - Optimize equipment reset workflows

---

## ✅ Next Steps for OR Optimization

1. **Improve Room Setup Procedures**  
   → Ensure full readiness the day before, not the morning of.

2. **Strengthen Communication**  
   → Automated alerts to OR teams about case start times.

3. **Schedule Adjustments**  
   → Allocate realistic time blocks for complex cases (e.g., Dr. Red).

4. **Enhance Collaboration in Shared Rooms**  
   → Review case handoff protocols for shared ORs.

5. **Long-Term Monitoring**  
   → Expand KPIs to include cancellation rates, and enable continuous feedback loops from staff and surgeons.

---

## 💡 Business Impact

> Inefficient OR utilization leads to **fewer surgeries per day**, increased costs, and reduced patient throughput.  
This dashboard provides visibility into key inefficiencies and empowers stakeholders to drive **data-informed decisions** that improve operational performance.



