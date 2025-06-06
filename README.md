# 🚲 Divvy_Bikeshare_Analysis: Members vs. Casual Riders

## 🎯 Project Overview
This project leverages Divvy BikeShare trip data to conduct a comprehensive analysis of how annual members and casual riders utilize the bike-sharing service differently. The insights aim to inform strategic decisions for optimizing operations, marketing, and converting casuals to members for Divvy BikeShare.

## ❓ Business Question
**"How do members and casual riders use Divvy bikes differently, and what are the key implications for Divvy BikeShare's business strategy?"**

## 📂 Data Source & Tools
* **Data Source:** Divvy BikeShare trip data (CSV files for a full year, e.g., January 2024 - December 2024).  
* **Tools Used:**
     * **PowerPoint: For report summary and visuals.  
    * **Microsoft Excel:** For data cleaning, transformation, complex pivot table analysis, and advanced charting.
    * **Microsoft Word pdf:** For the comprehensive project report detailing methodology and findings.
    * **Google Cloud Storage:** Utilized for hosting the large Excel workbook containing detailed analysis (due to GitHub file size limits).

---

## 💡 Executive Summary & Key Insights


1.  **Who takes the most frequent trips?:**
    * Members consistently account for **~63%** of all rides, forming the core user base  3,708,910 rides.
    * Casual riders contributed 2,151,658 rides (approximately 37%).
    * •	<a href="https://drive.google.com/file/d/1PS26uOX9xsYmNv5CgQmAWkMcRkIz2gUs/view?usp=sharing" target="_blank">IMAGE</a>
      

2.  **Distinct Daily Usage Patterns:**
    * **Members** show high, consistent ridership during **weekdays**, indicating commuting or routine use.
    * **Casual riders** exhibit pronounced peaks on **weekends**, suggesting leisure or recreational usage.
   3.  **Casual Riders Take Longer Trips:**
    * On average, casual riders take significantly **longer trips** compared to members across all days of the week. This points to recreational or exploration-based use.
   

4.  **Rideable Type Preference:**
    * Both user types primarily use classic and electric bikes.
    * However, casual riders show a relatively higher proportion of **electric scooter** usage compared to members, hinting at different preferences for short, effortless trips.
    * *(Optional: Embed your "Users by rideable Type" chart here - Screenshot (99).png)*

---

## 📈 Methodology (Brief Overview)

* **Data Acquisition & Combining:** Loaded 12 monthly CSV files using Excel Power Query. Files were combined and transformed, leveraging consistent column structures.
* **Data Cleaning:** Filtered rows, removed unwanted columns. Specifically addressed negative 'ride length' values by using the absolute value (ABS) function and removing inconsistent records to ensure data integrity.
* **Feature Engineering:** Calculated `ride_length` from start/end times.
* **Analysis:** Utilized Excel's pivot tables and charting features to identify trends, aggregations, and comparisons across user types, time periods (monthly, daily), and rideable types.

---

## 📦 Project Deliverables

* **Full Data Analysis Workbook (Microsoft Excel .xlsx):**
    * Contains all raw data, detailed pivot tables, interactive charts, and behind-the-scenes calculations.
    * **Size:** ~180MB.
    * **Access:**(https://docs.google.com/spreadsheets/d/1w5MpDWtkH3bndmDN2HgLajPrI9w2YhJg/edit?usp=sharing&ouid=102853951415568760346&rtpof=true&sd=true) < [Download Divvy Bike Share Analysis Workbook (.xlsx)]
    * *Note: This file is hosted externally on Google Drive due to
## 📦 Project Deliverables

* **Full Data Analysis Workbook (Microsoft Excel .xlsx):**
    * Contains all raw data, detailed pivot tables, interactive charts, and behind-the-scenes calculations.
    * **Size:** ~180MB.
    * **Access:**(https://docs.google.com/spreadsheets/d/1w5MpDWtkH3bndmDN2HgLajPrI9w2YhJg/edit?usp=sharing&ouid=102853951415568760346&rtpof=true&sd=true) < [Download Divvy Bike Share Analysis Workbook (.xlsx)]
    * *Note: This file is hosted externally on Google Drive due to GitHub's file size limitations for direct repository uploads, ensuring optimal performance and accessibility.*

* **Comprehensive Project Report (Microsoft Word .pdf):**
    * Provides an in-depth discussion of the project scope, detailed methodology, all findings, conclusions, and strategic recommendations.
    * **Access:** [Divvy_Bike_Analysis_Report.docx](Divvy_Bike_Analysis_Report.pdfx)

* **Project Summary Presentation (Microsoft PowerPoint .pptx):**
    * A concise and visually impactful presentation summarizing the key insights and strategic implications.
    * **Access:** [Divvy_Bike_Key_Findings_Presentation.pptx](Divvy_Bike_Key_Findings_Presentation.pptx)

* **Raw Data (Optional):**
  *The raw CSVs for January2024 to December2024, link to the folder can be access here: https://divvy-tripdata.s3.amazonaws.com/index.html

---

## 🚀 Key Recommendations & Business Implications


* **Seasonal Marketing:** Implement aggressive campaigns targeting casual riders in spring/summer to convert them to members.
* **Dynamic Fleet Management:** Optimize bike rebalancing and availability based on strong seasonal and daily peaks, especially in recreational areas during summer weekends.
* **Membership Incentives:** Develop compelling offers to encourage casual riders (especially those taking longer trips) to become members.
* **Service Reliability:** Maintain high service quality for consistent member usage year-round, including off-peak seasons.
## 📦 Project Deliverables

* **Full Data Analysis Workbook (Microsoft Excel .xlsx):**
    * Contains all raw data, detailed pivot tables, interactive charts, and behind-the-scenes calculations.
    * **Size:** ~180MB.
    * **Access:**(https://docs.google.com/spreadsheets/d/1w5MpDWtkH3bndmDN2HgLajPrI9w2YhJg/edit?usp=sharing&ouid=102853951415568760346&rtpof=true&sd=true) < [Download Divvy Bike Share Analysis Workbook (.xlsx)]
    * *Note: This file is hosted externally on Google Drive due to GitHub's file size limitations for direct repository uploads, ensuring optimal performance and accessibility.*

* **Comprehensive Project Report (Microsoft Word .pdf):**
    * Provides an in-depth discussion of the project scope, detailed methodology, all findings, conclusions, and strategic recommendations.
    * **Access:** [Divvy_Bike_Analysis_Report.docx](Divvy_Bike_Analysis_Report.pdfx)

* **Project Summary Presentation (Microsoft PowerPoint .pptx):**
    * A concise and visually impactful presentation summarizing the key insights and strategic implications.
    * **Access:** [Divvy_Bike_Key_Findings_Presentation.pptx](Divvy_Bike_Key_Findings_Presentation.pptx)

* **Raw Data (Optional):**
  *The raw CSVs for January2024 to December2024, link to the folder can be access here: https://divvy-tripdata.s3.amazonaws.com/index.html

---

## 🚀 Key Recommendations & Business Implications


* **Seasonal Marketing:** Implement aggressive campaigns targeting casual riders in spring/summer to convert them to members.
* **Dynamic Fleet Management:** Optimize bike rebalancing and availability based on strong seasonal and daily peaks, especially in recreational areas during summer weekends.
* **Membership Incentives:** Develop compelling offers to encourage casual riders (especially those taking longer trips) to become members.
* **Service Reliability:** Maintain high service quality for consistent member usage year-round, including off-peak seasons.
---

## ✍️ Author
Abiola Adeniyi Adeyemo
https://www.linked
