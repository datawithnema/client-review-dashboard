# client-review-dashboard
Excel dashboard showing clients who are over due for a review or up to date 
# Client Revenue & Review Dashboard

## 📊 Project Overview
This project simulates how a financial planning company tracks **client reviews** and **revenue**.  
The goal is to identify clients who are **overdue for review (12+ months)** and provide advisors with a dashboard that summarizes this information.

This is a common real-world problem in financial planning companies — client reviews must be up to date to ensure compliance, client satisfaction, and revenue retention.

---

## 🗂️ Dataset
- **File:** `client_revenue_review.csv`
- **Columns:**
  - `client_id` → Unique client identifier
  - `client_name` → Client’s name
  - `advisor` → Assigned financial advisor
  - `last_review_date` → Date of the last client review
  - `estimated_annual_revenue` → Annual revenue from the client

---

## ⚙️ Analysis Steps
1. Imported dataset into Excel.  
2. Added a calculated column**review_status** to flag clients as:
   - **Overdue** → last review ≥ 12 months ago  
   - **Up to date** → last review < 12 months ago
3. Added a calculated column **Days Since Review** - showing days since the last review was done for the client.
4. Built a PivotTable showing **Overdue vs. Up to date clients** grouped by advisor.  
5. Applied Conditional Formatting to highlight overdue clients in red.  
6. Created a PivotChart to visualize overdue reviews by advisor.

---

## 📸 Dashboard Preview

![Dashboard Screenshot](<img width="713" height="402" alt="image" src="https://github.com/user-attachments/assets/5deb390b-170a-4f5d-837c-19eefd1afe3e" />)

---

## 💡 Key Insights
- Advisor C has the **highest number of overdue clients**.  
- ~30% of clients in the dataset are overdue for review.  
- Estimated revenue at risk from overdue clients is **$X** (based on dataset).  

---

## 🛠️ Tools Used
- Microsoft Excel (PivotTables, Conditional Formatting, Charts)  
- GitHub (Version control, portfolio presentation)  

---

## 🚀 Next Steps
- Automate overdue tracking using SQL queries or Power BI dashboards.  
- Add alerts for clients who are due for review in the next 30 days.  
- Extend analysis to include client communications and product performance.

