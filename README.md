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
    * •	<a href="https://drive.google.com/file/d/1PS26uOX9xsYmNv5CgQmAWkMcRkIz2gUs/view?usp=sharing" target="_blank">CHART.png</a>
      

2.  **Which rideable type is the most preferred?:**
    * Both user types primarily use classic and electric bikes.
    * However, casual riders show a relatively higher proportion of **electric scooter** usage compared to members, hinting at different preferences for short, effortless trips.
    * <a href="https://drive.google.com/file/d/1Lg4-wO35vkYaLJ5qfRXltopDAtjNxYFL/view?usp=sharing" target="_blank">CHART.png</a>


3. Which months have the highest number of cycling trips?
    * Both user types exhibit seasonality, but casual riders' usage is far more dependent on favourable weather conditions, showing extreme peaks during warmer months, while members maintain more consistent year-round activity.
    * Peak usage for casual riders occurs during July (320,581 rides) and August (318,398 rides),while members,While members also show increased activity during warmer months, peaking in August (437,406 rides), their baseline ridership remains significantly higher throughout the year, even during colder periods.
    *  <a href="https://drive.google.com/file/d/13jASZ9wpkx9GqqHnlg-scLtYt5CgSDGk/view?usp=sharing" target="_blank">CHART.png</a>


4.  Which month has the highest length of cycling trips?
    *Throughout the entire year, casual riders use Divvy bikes for a significantly longer average duration per trip compared to annual members.
    *This highlights a fundamental difference in usage intent. Casual riders likely use bikes for leisure, longer recreational outings, or tourism, while members may use them more for efficient, shorter commutes or quick errands.
    * <a href=" <a href="https://drive.google.com/file/d/13jASZ9wpkx9GqqHnlg-scLtYt5CgSDGk/view?usp=sharing" target="_blank">CHART.png</a>    

5.  *What are the most cycling popular days?
    * Members show high, consistent ridership during **weekdays**, indicating commuting or routine use.
    * Casual riders exhibit pronounced peaks on **weekends**, suggesting leisure or recreational usage.
    * On average, casual riders take significantly **longer trips** compared to members across all days of the week. This points to recreational or exploration-based use. 
    * <a href="https://drive.google.com/file/d/1__BkU_tWPvz1TpgJSUI82QM5m0CijIAm/view?usp=sharing" target="_blank">CHART.png</a>
  
6.  * What is the longest Average ride Length?
    * Casual riders consistently take significantly longer trips on average compared to member riders.
    * The average ride length for casual riders (ranging approximately from 780 minutes to 1002 minutes,whereas members on the other hand, it ranges approximately from 715 minutes to 717.6 minutes.
    * <a href="<a href="https://drive.google.com/file/d/1__BkU_tWPvz1TpgJSUI82QM5m0CijIAm/view?usp=sharing" target="_blank">CHART.png</a>
---

## 📈 Methodology (Brief Overview)

* **Data Acquisition & Combining:** Loaded 12 monthly CSV files using Excel Power Query. Files were combined and transformed, leveraging consistent column structures.
* **Data Cleaning:** Filtered rows, removed unwanted columns. Specifically addressed negative 'ride length' values by using the absolute value (ABS) function and removing inconsistent records to ensure data integrity.
* **Feature Engineering:** Calculated `ride_length` from start/end times.
* **Analysis:** Utilized Excel's pivot tables and charting features to identify trends, aggregations, and comparisons across user types, time periods (monthly, daily), and rideable types.

---
## 📦 Project Deliverables

* **Full Data Analysis Workbook (Microsoft Excel .xlsx):** 

    * Contains all detailed pivot tables, interactive charts, and behind-the-scenes calculations.
    * **Size:** ~180MB.
    * **Access:**<a href="https://docs.google.com/spreadsheets/d/1HiI9J5tca1AvrOLZHZTuAIahOLMJSKne/edit?usp=sharing&ouid=109954983979009566655&rtpof=true&sd=true" target="_blank">[Download Divvy Bike Share Analysis Workbook (.xlsx)]</a> 
    * *Note: This file is hosted externally on Google Drive.


* **Comprehensive Project Report (Microsoft Word .pdf):**
    * Provides an in-depth discussion of the project scope, detailed methodology, all findings, conclusions, and strategic recommendations.
    * **Access:** <a href="<a href="https://docs.google.com/spreadsheets/d/1HiI9J5tca1AvrOLZHZTuAIahOLMJSKne/edit?usp=sharing&ouid=109954983979009566655&rtpof=true&sd=true" target="_blank"> (Divvy_Bike_Analysis_Report.pdf)</a>

* **Project Summary Presentation (Microsoft PowerPoint .pptx):**
    * A concise and visually impactful presentation summarizing the key insights and strategic implications.
    * **Access:** [Divvy_Bike_Key_Findings_Presentation.pptx] <a href="<a href="https://docs.google.com/presentation/d/1O4YtODuMvZl7bwP2H98FS_aOA_YCz4EY/edit?usp=sharing&ouid=109954983979009566655&rtpof=true&sd=true" target="_blank">(Divvy_Bike_Key_Findings_Presentation.pptx) </a>
--- 

* **Raw Data (Optional):**
  *The raw CSVs for January2024 to December2024, link to the folder can be access here:<a href=" https://divvy-tripdata.s3.amazonaws.com/index.html
" target="_blank">RAW DATA</a>
      
---

## 🚀 Key Recommendations & Business Implications


* **Seasonal Marketing:** Implement aggressive campaigns targeting casual riders in spring/summer to convert them to members.
* **Dynamic Fleet Management:** Optimize bike rebalancing and availability based on strong seasonal and daily peaks, especially in recreational areas during summer weekends.
* **Membership Incentives:** Develop compelling offers to encourage casual riders (especially those taking longer trips) to become members.
* **Service Reliability:** Maintain high service quality for consistent member usage year-round, including off-peak seasons.
---


---

## ✍️ Author
About Me
👤 Abiola Adeniyi Adeyemo
Data Analyst (Excel,Power BI,MYSQL,R-programming, and Tableau Tools)
•	LinkedIn: www.linkedin.com/in/abiola-adeyemo-85031b135
•	Portfolio: Divvy_Bikeshare_Analysis
•	Contact: adeniyiabiola2@gmail.com

