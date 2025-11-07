# 🏥 Hospital Wait Time Analysis Project

## 📜 Project Overview

This project aims to analyze hospital patient wait times to identify trends, bottlenecks, and opportunities for operational improvements. By examining various factors such as day of the week, time of day, and different patient/consultation types, we can gain insights into optimizing patient flow and reducing wait times.

## ✨ Key Features & Analysis Highlights
This project demonstrates proficiency in several Excel functions and analytical techniques:

* **Data Cleaning & Preparation:**
    * Ensuring data consistency and handling missing values.
    * Calculating `Wait Time (min)` from `Entry Time` and `Post-Consultation Time` fields.
    * Deriving `Day of the week` and `Hour` from date/time stamps for granular analysis.
      <img width="1919" height="601" alt="image" src="https://github.com/user-attachments/assets/e4e55ec5-5f21-4ad2-a31a-c5de8e09da29" />

* **Dynamic Analysis with Pivot Tables:**
    * Created pivot tables to aggregate and summarize data, revealing patterns in patient volume and average wait times across different hours and days of the week.
        * **Patient Volume by Hour & Day:**
          <img width="936" height="386" alt="image" src="https://github.com/user-attachments/assets/b43fda5a-9a93-4eea-a2d8-df88bfeb27c9" />
        * **Patient Volume by Hour & Day:**
          <img width="814" height="382" alt="image" src="https://github.com/user-attachments/assets/3c0a5f68-4d40-4f31-8922-2be962d3db28" />
        * **Patient Process Time and Their Insurance:**
          
          <img width="482" height="234" alt="image" src="https://github.com/user-attachments/assets/ef0e6876-48af-4044-910a-1dc86e711eec" />

* **Visual Data Representation:**
    * Designed clear and insightful charts to communicate key findings effectively.
        * **Consultation Time vs Process Time (Overall):** A pie chart illustrating the proportion of time spent in consultation versus overall process time.
          
          <img width="591" height="323" alt="image" src="https://github.com/user-attachments/assets/a34e201a-f282-4b3a-95b3-ab6a4c788bf9" />

        * **Consultation vs Process Time on Weekday:** A column chart comparing average consultation and process times across different days of the week, highlighting variations in operational efficiency.
          <img width="729" height="451" alt="image" src="https://github.com/user-attachments/assets/3019c84f-4d4e-4d4b-a628-f4cf65462c1e" />

* **Conditional Formatting:**
    * Applied conditional formatting to highlight critical data points, such as exceptionally long wait times or high-volume periods
      <img width="475" height="248" alt="image" src="https://github.com/user-attachments/assets/f0a39d6e-3046-440b-9e01-ddc158d5a99b" />

      <img width="452" height="277" alt="image" src="https://github.com/user-attachments/assets/572cdeab-9406-47e9-b604-5a93e439512a" />


## 💡 Key Findings & Insights
- Monday is the Peak Stress Day: Monday consistently shows the highest patient volume, resulting in the longest average wait time (59 minutes).
- Morning Rush Bottleneck: Wait times peak sharply around 10 AM, hitting nearly 60 minutes. This indicates the morning hours (9 AM–12 PM) are critical for potential staff shortages or system overload.
- Process Time Bottleneck Confirmed: Due to data limitations, the exact consultation time was not calculable. However, with the efficient checkout process established as being under 5 minutes, the major bottleneck (the 88% of non-consultation time) is confidently attributed to the pre-consultation process (patient check-in, initial triage, and waiting room time).
- Operational Focus on Major Insurance Types: While Medicare patients may show the longest average wait time, they represent a statistically insignificant portion (approx. 1%) of the overall patient volume.
Operational focus should be placed on Insurance (the specific type with 46 min wait) and the high-volume segments like Private and HMO, as these categories significantly impact the overall patient flow and resource management.


## 🛠️ Technologies Used

* **Microsoft Excel** (Version [e.g., 365, 2019])
    * Pivot Tables
    * Conditional Formatting
    * Formulas (e.g., `HOUR()`, `TEXT()`, `DATEDIF()` or custom time calculations)
    * Charts & Dashboards
